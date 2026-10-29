#The Haunted Manor
#How to play: Type door to enter bedroom, stairs to go upstairs, run away to run away, and anything else for the other ending.
print("You wake up in a dark room.")
print("You hear knocking from somewhere upstairs...")
print("There is a door to your left and a staircase ahead.")
choice = input ("Do you go through the door or up the stairs?")
if choice == "door":
    print("You enter a cold bedroom.")
    print("A mirror shows someone standing behind you.")
    print("You turn around... nobody is there.")
elif choice == "stairs":
    print("You walk upstairs slowly.")
    print("At the top, you see a shadow watching you.")
    print("It whispers your name.")
elif choice == "run away":
    print("You sprint toward the front door.")
    print("You grab the handle but it's locked")
    print ("A voice whispers, 'You can't leave.")
else:
    print("You stay still.")
    print("The knocking gets louder.")
    print("Something is standing right behind you.")

print("GAME OVER.")
print ("Thanks For Playing")
