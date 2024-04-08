print("Welcome to my Computer Quiz!")
playing=input("Do you wanna play? ")

if playing.lower()!= "yes":
    quit()
    
print("Okay Lets play!")
print("you'll be asked 5 questions and you have to type the correct answer, if you type the correct answer you'll earn 1 score and if you typed the wrong answer 1 mark will be deducted from your total score")
score=0
answer= input("What is also known as a portable computer? ").lower()
if answer == "laptop":
    print("Correct!")
    score+=1
else:
    print("Incorrect!")
    
answer= input("What does CPU stands for? ").lower()
if answer == "central processing unit":
    print("Correct!")
    score+=1
else:
    print("Incorrect!")
    
answer= input("What is the full form of E-Mail? ").lower()
if answer== "electronic mail":
    print("Correct!")
    score+=1
else:
    print("Incorrect!")
    
answer= input(" Who is the Father of the Computer? ").lower()
if answer == "charles babbage":
    print("Correct!")
    score+=1
else:
    print("Incorrect!")
    
answer= input("In the virtual world, WWW stands for ____ ").lower()
if answer == "world wide web":
    print("Correct!")
    score+=1
else:
    print("Incorrect!")
    
print("Your Total Score is:",score)



    

