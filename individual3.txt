for number in range(100, 1000):
    digits_sum = sum(int(digit) for digit in str(number))
    if digits_sum % 7 == 0 and number % 7 == 0:
        print(number)
