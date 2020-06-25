for test in range(1,101):
    if test % 3 == 0 and test% 5 == 0:
        print("fizzbuzz")
        continue
    elif test % 3 == 0:
        print("fizz")
        continue
    elif test % 5 == 0:
        print("buzz")
        continue
    print(test)
