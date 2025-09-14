a = int(input("Enter a: "))

while (a < 1 or a > 100):
    a = int(input("Enter a: "))

b = int(input("Enter b: "))

while (b < 1 or b > 100):
    b = int(input("Enter b: "))

if a < b:
    r = (b / a + 1)
elif a == b:
    r = 25
else:
    r = (a**3 - 5) / b

print("Result:", r)
