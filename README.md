r1 = int(input("r1: "))
r2 = int(input("r2: "))

while r2 != 0:
    q = r1 % r2
    r1 = r2
    r2 = q

print(str(r1))
