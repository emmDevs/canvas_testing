### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:

  def check_for_ace(self, card):
    if card.value = 1:  # This should read if card.value == 1:
      return True
    else                #The else should have a : after it
      return False
   
#line 26 should start with def not dif
  dif highest_card(self, card1 card2):  #there should be a comma between parameters so a comma between card1 and card2
  if card1.value > card2.value:        #if statement needs indented
    return card                       #card is not defined, this should read return card1
  else:
    return card2
  


def cards_total(self, cards):    #This line is indented incorrectly   
  total                         #total has not been defined correctly it should read total = 0
  for card in cards:
    total += card.value
    return "You have a total of" + total #the return statement is incorrectly indented
                                        # to concatenate the total it needs to be a string  
                                        # it should read return "You have a total of " = str(total)
                                        # There should also be a space between the of and the "
```
