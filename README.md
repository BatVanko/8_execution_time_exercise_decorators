# 8_execution_time_exercise_decorators
Import the time module. Create a decorator called exec_time. It should calculate how much time a function needs to be executed. See the examples for more clarification.
Test Code
@exec_time
def loop(start, end):
    total = 0
    for x in range(start, end):
        total += x
    return total
print(loop(1, 10000000))

Output
0.8342537879943848
