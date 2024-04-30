Calculator project
print("Simple calculator")
#using whlie True for program to repeat
while True:
   print("+,-, *, /", "choose one symbol" )
   calc = input()
   print("choose a number")
   num1=float(input())
   print("choose another number")
   num2=float(input())
   #for addiction
   if(calc == "+"):
     num1 = num1 + num2
   #for subtraction
   elif(calc == "-"):
     num1 = num1 - num2
   #for division
   elif(calc == "/"):
     num1 = num1 / num2
   #for multiplication
   elif(calc == "*"):
     num1 = num1 * num2
   print("=")
   print(num1)
   #new codes added
   print("would you like to continue? Y/N")
   #using lowercased strings
   answer = input().lower()
   if answer == "n": 
     print("close the program")
   if answer == "y":
     print ("enjoy your practice")

 
