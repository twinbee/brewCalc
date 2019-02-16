# brewCalc
An alexa skill to calculate while homebrewing (quantities, times, temps etc)

.. Because brewers have better things to do with their hands than figure.

Currently it is implemented as a stateless AWSLambda app that only supports imperial units, but that may change in the future.

## Example dialog

*Alexa, Open BrewCalc!*

**Welcome to BrewCalc. You can ask me about pour temperature, ABV, Hygrometer correction, Attenuation, Mash water volume, or Sparge Water Volume.**

### *Pour temperature*

**Ok, pour temperature. How much wort in gallons?**

*2.5*

**What temperature is the wort in degrees farenheit?**

*One Thirty*

**How much water volume in gallons?**

*Three*

**What temperature is the cold water in degrees farenheit?**

*forty two*

**If you combine 2.5 gallons wort at 130 degrees farenheit with 3 gallons water at 42 degrees farenheit, you will have 5.5 gallons solution at 70.71363 degrees farenheit. Does that answer your question?**

*Yes*


### *ABV calculator*

**Ok, ABV calculator. What is the starting gravity?**

*1.058*

**What is the final gravity?**

*1.018*

**The difference in gravity is 0.04, yielding an approximate alcohol by volume of 5.36 percent. Does that answer your question?**



