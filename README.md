# Python-Project - 1
# AI Greeter Bot
# This program will greet you according the time you run this code.
print("Welcome to my first AI greeter\n")
# used https://docs.python.org/3/library/time.html#time.strftime
import time
timestamp = time.strftime('%H:%M:%S')
print("The time now is - " , timestamp, "\n")
Hour = int(time.strftime('%H'))
Minute = int(time.strftime('%M'))
Second = int(time.strftime('%S'))
name = input("What is your name?\n\n")
if (Hour <= 11):
  print("\nGood Morning", name, "\n")
elif(Hour <= 17):
  print("\nGood Afternoon", name, "\n")
else:
  print("\nGood Evening", name, "\n")
# end
