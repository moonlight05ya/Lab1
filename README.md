# 
def power(x, y):
    result = x ** y
    return result
#  Ця функція приймає 2 значення:
#     - x: базове число
#     - y: показник степеня
#     Він повертає результат піднесення x до степеня y.

number = int(input("Введіть просте число: "))
degreeNumber = int(input("Введіть просте число: "))

result = number ** degreeNumber
print(result, "- результат")
