# This code is only for python
exitchoice = "nothing"
while exitchoice != "stop" :
     operation = input("Type the operation.Type + or - or x or / or %(For taking calculating the percentage of a number):")
     if operation == "+" :
        number1 = float(input("Type first number:"))
        number2 = float(input("Type second number:"))
        print( number1 + number2)
        exitchoice = input("Press enter to use calculator again or type stop to stop")
     elif operation == "-" :
         number1 = float(input("Type first number:"))
         number2 = float(input("Type second number:"))
         print( number1 - number2)
         exitchoice = input("Press enter to use calculator again or type stop to stop")
     elif operation == "x" :
         number1 = float(input("Type first number:"))
         number2 = float(input("Type second number:"))
         print( number1 * number2)
         exitchoice = input("Press enter to use calculator again or type stop to stop")
     elif operation == "/" :
         number1 = float(input("Type first number:"))
         number2 = float(input("Type second number:"))
         print( number1 / number2)
         exitchoice = input("Press enter to use calculator again or type stop to stop")
     elif operation == "%" :
         number1 = float(input("Type the number to take out percentage of:"))
         number2 = float(input("Type the percentage:"))
         percentage = (number2/100)*number1
         final = number1-percentage
         final2 = number1-final
         print("Ans:", final2)
         exitchoice = input("Press enter to use calculator again or type stop to stop")
