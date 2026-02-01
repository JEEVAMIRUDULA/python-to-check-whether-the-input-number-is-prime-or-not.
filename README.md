# python-to-check-whether-the-input-number-is-prime-or-not.
number = int(input("Enter any number: "))

if number > 1:
    for i in range(2, number):
        if number % i == 0:
            print(number, "is not a prime number")
            break
    else:
        print(number, "is a prime number")
else:
    print(number, "is not a prime number")


Output:
Enter any number: 20
20 is not a prime number
Enter any number: 2
2 is a prime number

