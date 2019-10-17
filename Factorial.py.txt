def Factorial():
    n = int(input('Enter the Number : \n'))
    f = 1
    if (n <= 1):
        return f
    else:
        while (n > 1):
            f *= n
            n -= 1
            print(n, 'X', f, '= ', n*f)
            
        print('Factorial value of is = ', f)
        return f
        

Factorial()