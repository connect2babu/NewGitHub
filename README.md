# NewGitHub

import time
def num_guessing():
	number = 23
	running = True
	while running :
		guess = int(raw_input('Enter an Integer:'))
		
		if guess == number :
			print 'Congratulations, you guessed it'
			running = False
		elif guess < number 
			print 'No,it is a little higher than %d', %guess
			num_guessing()
		else :
			print 'No it is little more than %d', %guess
			num_guessing
	print "Done"
	
	