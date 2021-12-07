___

<center><img src='../../BlueSoft_logo.png' width="500" height="208"/></center>

___

# Guess the number challenge

*Guess the Number* is a classic game for beginners to practice basic programming techniques.

In this game, the computer thinks of a random number between `1` and `100`. The player has `10` chances to guess the number.

After each guess, the computer tells the player if it was too high or too low.

Example:
```
I drew a number between 1 and 100.

You have 10 guesses left. Take a guess.
> 50
Your guess is too high.

You have 9 guesses left. Take a guess.
> 25
Your guess is too low.

You have 8 guesses left. Take a guess.
> 37
Your guess is too low.

You have 7 guesses left. Take a guess.
> 42
Yay! You guessed my number!
```

## Experimental changes

After entering the source code and running it a few times, try making experimental changes to it.

You can also try to figure out how to do the following:
- Create a *Guess the Letter* variant that gives hints based on the alphabetical order of the player’s guess.
- Make the hints after each guess say *warmer* or *colder* based on the player’s previous guess.


```python





```


```python
import random
import math
# Taking Inputs
lower = int(input("Enter Lower bound:- "))

# Taking Inputs
upper = int(input("Enter Upper bound:- "))

# generating random number between
# the lower and upper
x = random.randint(lower, upper)
print("\n\tYou've only ",
	round(math.log(upper - lower + 1, 2)),
	" chances to guess the integer!\n")

# Initializing the number of guesses.
count = 0

# for calculation of minimum number of
# guesses depends upon range
while count < math.log(upper - lower + 1, 2):
	count += 1

	# taking guessing number as input
	guess = int(input("Guess a number:- "))

	# Condition testing
	if x == guess:
		print("Congratulations you did it in ",
			count, " try")
		# Once guessed, loop will break
		break
	elif x > guess:
		print("You guessed too small!")
	elif x < guess:
		print("You Guessed too high!")

# If Guessing is more than required guesses,
# shows this output.
if count >= math.log(upper - lower + 1, 2):
	print("\nThe number is %d" % x)
	print("\tBetter Luck Next time!")



```

    Enter Lower bound:- 5
    Enter Upper bound:- 8
    
    	You've only  2  chances to guess the integer!
    
    Guess a number:- 7
    You guessed too small!
    Guess a number:- 6
    You guessed too small!
    
    The number is 8
    	Better Luck Next time!



```python

```


```python

```


```python

```


```python

```


```python

```
