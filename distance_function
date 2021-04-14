def distance_function():
#This entire program is just one function! 
  import math
  import random
  print("Welcome to my program that can calculate the distance between two points!")
  print("Do you want to put in your own numbers, or a random number between one and ten?")
  first_answer=input("Please write either the word *own* or the word *random* ONLY.\n")
  #Just in case the user inputs something like "OWN" or "RaNdOm"
  first_answer=first_answer.lower()
  #This is conditional branching 
  if first_answer=="own":

    x1=input("For starters, please write the x coordinate of the first point.\n")
    x1=float(x1)
    y1=input("Now, the y coordinate of the first point.\n")
    y1=float(y1)

  elif first_answer=="random":
    x1=random.randint(1,10)
    y1=random.randint(1,10)
    print("This is your first coordinate:","(",x1,",",y1,")")

  print("Good! Now, let's work on getting the second coordinate.")
  print("Again, do you want to put in your own numbers, or a random number between one and ten?")
  second_answer=input("Please write either the word *own* or the word *random* ONLY.\n")
  second_answer=first_answer.lower()

  if second_answer=="own":
    x2=input("What's the x coordinate of the second point?\n")
    x2=float(x2)
    y2=input("And the y coordinate?\n")
    y2=float(y2)

  elif second_answer=="random":
    x2=random.randint(1,10)
    y2=random.randint(1,10)
    print("This is your second coordinate:","(",x2,",",y2,")")

  distance=math.sqrt((x1-x2)**2+(y1-y2)**2)
  print("This is this distance between them:",distance)
