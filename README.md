https://github.com/ArmitaJF85/arithmetic--average
def average(numbers):
return sum(numbers) / len(numbers)

while Ture:
try:
numbers = list(map(float,input().split()))
if not numbers:
raise ValueError
print(f"{average(numbers):.2f}")
break
except ValueError:
print("Invalid Tnput! Enter a valid input.")