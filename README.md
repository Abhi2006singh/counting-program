start = int(input("Enter the starting point: "))
end = int(input("Enter the end point: "))
ori = input("Enter the ori (horizontal/vertical): ")
dire = input("Enter the dire (forward/reverse): ")
if dire == "forward":
    if ori == "horizontal":
        for i in range(start, end + 1):
            print(i, end=" ")
    elif ori == "vertical":
        for i in range(start, end + 1):
            print(i)
elif dire == "reverse":
    if ori == "horizontal":
        for i in range(end, start - 1, -1):
            print(i, end=" ")
    elif ori == "vertical":
        for i in range(end, start - 1, -1):
            print(i)
