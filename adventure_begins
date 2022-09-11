print ("Hello! This is a choose your own adventure game called Choose Start.")
name = input("What is your name? ")
age = int(input("What is your age? "))

hp = 10

if age >= 14:
  print("Seeing as you are", age, "you are old enough to play.")
  choose_start = input("Do you want to play? Type 'start' if so. ").lower()
  
  if choose_start == "start":
    print("You have choosen start. A wise choice. Within this game your health is measure by HP (health points), you start with", hp,"HP. ")
    
    left_or_right = input("The initial choice... Do you go left or right? (left/right) ")
    
    if left_or_right == "left": 
        ans = input("A wise choice, you walk towards a lake. Do you take the path around or swim across? (around/swim) ")
        if ans == "swim":
          print("You have swam across the lake but have been nibbled by the fish and take 2 point of damage. ")
          hp -= 2
        elif ans == "around":
          print("You have walked around the lake and become weary from the long distance. You camp for the night and are rudely awoken by a bear, you escape the bear but take 7 points of damage in the process. ")
          hp -= 7

        ans = input("Past the lake the land flattens into woodland on one side and fields of farmland on the other. Where will you head towards? (woods/farms) ")
      
        if ans == "woods":
            print("You wander the woods and are chased by angry squirreles, taking 4 points of damage. Eventually you stumble out of the woods.")
            hp -= 4

            if hp <= 0:
              print("You have reached 0 HP and have lost this game. Choose start again to find another way. May you choose more wisely in the future...")
              
            else:
              print("You have walked through the farmland hearing only the rustle of the growing crops around you. ")
              
        else:
            print("Upon finding the path again you are greeted by a most welcome sight of your party. They cheers your return and once again you all set out on another adventure.")
    
    else:
        print("An unwise choice, you enter the dark cave never to be seen again. ")    
  
  else:
    print("That's fair, have a nice day! ")

else:
  print("I'm sorry but you are not old enough to play... ")
  
'''
This is a comment! Inside here all the things are ignored by the programe. Handy for updates for the programmer. 
Currently been working on this for 45 minutes.
'''
