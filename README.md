# Temperature-Coaster

The idea is simple: create a drink coaster which indicates what temperature a drink placed on it is. whether hot or cold, by turning red or blue. The ideal use for this is to be able to tell if your coffee has gone cold.  

I plan on using ATTiny85 do the work, since it should run on 3v 
CR2023 is 3v and should have enough mA to power it and some SK6812 / 5050 RGB LEDS
And a thermresistor will sense the temp, obviously.

The end game is to dip the board in resin to waterproof and protect the board making into an actual coaster.
The bottom side of the board will have the battery holder and pads to program the Attiny85.  I plan on leaving a recess in the epoxy to allow battery access.  I may make a recess for the pads for debugging,  but i plan to work out the code and kinks before putting it in resin

---
This is intended to be an Entry for the [HackaDay Coin Cell Challenge](https://hackaday.io/contest/28283-coin-cell-challenge)

Keeping in with the rules of the challenge, i've added the board to [OSHPark](https://oshpark.com/shared_projects/DYg7IxAX) 

<a href="https://oshpark.com/shared_projects/DYg7IxAX"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>


Future add-ons may include some IoT for notifying when the drink reaches a certain temp or something
