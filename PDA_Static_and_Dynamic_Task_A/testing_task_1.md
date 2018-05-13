### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('card.rb')
class CardGame


# needs cards initialised into CardGame


  def checkforAce(card)
    # naming convention, should be lower-case A
    if card.value = 1
      # needs == 1
      return true
    else
      return false
    end
  end


  dif highest_card(card1 card2)      
   # the dif should read def, there should be a comma between the arguments
  if card1.value > card2.value
    return card.name
    # there is no name value of the card, and this is not specifying which card, it should say card1
  else
    card2
  end
end
# poor indentation
end
# don't need this end



def self.cards_total(cards)
  total
  # should say total = 0 or another value
  for card in cards
    total += card.value
    return "You have a total of" + total
    # return needs to go under the next end, and total should be in string interpolation
  end
end



```
