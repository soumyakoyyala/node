def fizz_buzz_phone_number(phone_number):
    
    phone_number_sum = sum(int(digit) for digit in phone_number)

    
    for i in range(1, phone_number_sum + 1):
        if i % 4 == 0 and i % 5 == 0:
            print("FizzBuzz")
        elif i % 4 == 0:
            print("Fizz")
        elif i % 5 == 0:
            print("Buzz")
        else:
            print(i)
