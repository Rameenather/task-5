# task-5
task 5.1
import random
question = input("Would you like to draw a lottery? ").lower()
ball = random.randint(1,49)
list=[]
if (question == "yes"):
  for i in range(6):
    r=random.randint(1,49)
    if r not in list: list.append(r)
    print (r)
    i = i + 1
  print ("And your bonus ball number is...",ball )
  print("Goodluck!")
else:
  print("Goodbye")
  
  
task 5.2
import random
mylist_1 = ['hot', 'summer', 'hard', 'dry', 'simple', 'light', 'weak', 'male', 'sad', 'win', 'small', 'ignore', 'buy', 'succeed', 'reject', 'prevent', 'exclude']
mylist_2 = ['cold', 'winter', 'soft', 'wet', 'complex', 'darkness', 'strong', 'female', 'happy', 'lose', 'big', 'pay', 'attention', 'sell', 'fail', 'accept', 'allow', 'include']
for i in range (10):
   random1 = (random.choice(mylist_1))
   print ("Q1: The opposite of ")
   print(random1)
   oppo1 = input("is...")
   index = mylist_1.index(random1)
   random2 = (random.choice(mylist_2))
   index2 = mylist_2.index(random2)
   if (index == index2):
     random2 = (random.choice(mylist_2))
     index2 = mylist_2.index(random2)
     print ("Q2: The opposite of ")
     print(random2)
     oppo1 = input("is...")
   else:
     print ("Q2: The opposite of ")
     print(random2)
     oppo1 = input("is...")
print("That was all! :D")
  
