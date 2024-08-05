def add(x, y):
    return x + y

def sub(x, y):
    return x - y

def multi(x, y):
    return x * y

def div(x, y):
    return x / y

# def check_intergers(x , y):
#     if(x.)
    
    
def check(y):
    if y == 0:
        print("can't divid by zero")
        return False
    return True

def check_sign(sign):
    if (sign not in('+' , '-' , '*', '/',  'q')):
        print("please enter a valid sign")
        return False
    return True
    

    
    
    
while True:
    x = int(input("Please enter the first number: "))
    sign = input("Please enter a sign (+, -, *, /, q to exit): ")
    y = int(input("Please enter the second number: "))
    
    if not check_sign(sign):
        continue
    
    if sign.lower() == 'q':
        break


    if sign == '+':
        result = add(x, y)
    elif sign == '-':
        result = sub(x, y)
    elif sign == '*':
        result = multi(x, y)
    elif sign == '/':
        if not check(y):
            continue
        result = div(x, y)
    else:
        print("Please enter a valid sign.")
        continue

    print(f"The result is: {result}")

print("Calculator exited.")
