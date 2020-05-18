# le-juste-prix
Python Text zur Kenntnis while
import random
#nombre au hasard

number = random.randint(1, 1000)

# construire notre boucle
while True:
	user_number = int(input("devine mon nombre si tes fort!"))
	if user_number == number:
		print("tu as gagner")
		break
	elif user_number > number:
	    	print("ton nbe est haut")
	    	continue
	else:
	    	print("ton nbe est bas")
	    	continue
