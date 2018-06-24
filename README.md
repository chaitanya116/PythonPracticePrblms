# PythonPracticePrblms

1. First class: DeckSelection

It is just for holding the values of cards dictionary pair for usage

2. The second class:Players does the following

a. Inherits the first class
b. It gives an option to play or not
c. If play is yes then, through deckselection and random method we choose 2 random cardnumbers for delaer and player each and calculate the sum
d. The logic in this class does all the above things and returns the values for later usages
e. The logic has what is the first,secnd card,the sum of cards for both dealer and player and returns the same for later usage

3. The Third class:MoneyBet does the following

a. Inherits players class(2nd class)
b. IT is a simple class just takes inputs of balalnce and the bet amount for the play
c. Returns the values for later calc or usage

4. The 4th class: Hit does the following:
a. Inherits the money betclass(3rd class)
b. Takesa  input of choice:player or dealer
c. If player and asks he wants to hit or not
d. If yes hit, then a random card is drawn from cardnumbers present in the first class as itis inherited eveything can be called anywhere
e. And returns the rando card drwan for later usage
f. THe same thing is done in case of dealer

5. The 5th class: Stay does the following:
a.Inherits the money betclass(3rd class)
b. Takesa  input of choice:player or dealer wants to stay
c. If player stays then returns the current sum of cards the player has from 2nd class
d. Use the sum to return the value for later usage
e. same is done for dealer case

6. The 6th class: BlackJack does the following:
a. Player or dealer wants to go
b. It is the main class or first class to be exeuted
c. Itinherits hit ans stay
d. as it inherits the playerclass (2nd class) is called and the retunrs values are unpacked as they are retunrs as kind of list
e. Then player or dealer are asked to hit or stay the method hit_stay is for the same
f. The hit_stay methods: iF hit choosen then class hit method and random card is selected and added to the total sum for players card
g. IF stay selected doess nothing uses the same sum of cards retunrs in stay method for usage
h. The same is done in case of dealer also
i. calc_winner method has all the logics i.e. if else conditions to check who is the winner and tie. If player looses the bet amout is dedduted from balalnce using moneybet 
class retrun values
j. If player wins using money bet class retrun values by default 2 times bet amout is credited to the balance
k. The calc_winner method also has an input to be recieved
l.The calc_winner method also has alogic if ACE is retireved for player or dealer which can be 11 or 1 depending on the sum of total cards present for dealer to player ace is conveted to 1 or used as 11 itself
m. recalc_sum method is for like passing the value again to calc_winner method as if the plauyer or dealer choses hit another random card is selcted and added t the total sum and again it goes to calc_winner logic to identify the winner
n. Finally the main condition displaying which order the class or mehtods should be called

7. The classes to be executed the same order given above

8. Try,except block are given hence you might not get the same error i have given in description if you remove the try,except from the final 6th class the error pops up

