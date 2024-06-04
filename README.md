# Pico-Fermi-Bagels

#Describe PFB
PFB icon
PFB (Pico, Fermi, Bagels) is a number guessing game, similar to MasterMind or Jotto. For each guess, you will be told:

Fermi
a correct digit placed correctly
Pico
a correct digit placed incorrectly
Bagels
no digits are correct

# Using PFB
New Game
start a new game
Allow Zero
is zero a possible digit?
#Digits
select number of digits (2-6)
Give Up
see answer
Guess
type a number guess
Result
<tab> from Guess, or select Result field for feedback; on Newton, Result displayed when Guess reaches correct number of digits

# Example
If Allow Zero = checked, Digits = 3, and PFB's number = 029

Guess	Result	comment
376	Bagels	no digits correct
914	Pico	1 digit correct but in wrong place
820	Fermi Pico	2 digits correct, but 1 in wrong place
...	(keep guessing)
092	Fermi Pico Pico	all digits correct, 2 in wrong places
029	Fermi Fermi Fermi !!!	you won
