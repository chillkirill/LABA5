month = int(input("Enter the month number (1 to 12): "))

if 1 <= month <= 6:
    half_year = "first half of the year"
elif 7 <= month <= 12:
    half_year = "second half of the year"
else:
    print("Invalid month number.")
    exit()

if month in [1, 3, 5, 7, 8, 10, 12]:
    days = 31
elif month in [4, 6, 9, 11]:
    days = 30
elif month == 2:
    days = 28

print(f"The month is in the {half_year}, and it has {days} days.")
