a = float(input("введите 1 число"))
b = float(input("введите 2 число"))

operation = input("что сделать? (+,-,*,/,//,%): ")
result = 0
if operation == "+":
    result = a+b
elif operation == "-":
    result = a-b
elif operation == "*":
    result = a*b 
elif operation == "/":
    result = a/b      
elif operation == "//":
    result = a//b     
elif operation == "%":
    result = a%b     

print (f"результат: {result} " )
