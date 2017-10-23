## WHAT IS IT?

This model is a simple example that shows some basic features of Netlogo by modeling the way that people's trust evolves based on the interaction with other people. Please check the Prisioners dilemma models to understand the basis of model.

## HOW IT WORKS

The level of trustworthy of a country is modeled as the percentage of people that are willing to believe in each other, the interaction strategies are modeled as the *Tit-for-Two-Tats* -If your partner believes this round you will cooperate next round. If your partner defects two rounds in a row, you will defect the next round- and the *Defect* -always cheat your partner-; each round everybody gets a random partner.

As in real world, there is a probability that some people choose to defect everyone everytime (Bad seeds) and a probability that even if both agents choose to believe a misunderstanding occurs (and someone believes that was cheated), these random events affects the global level of thrustworthy.

## HOW TO USE IT

Setup the model by selecting the base level of thrustworthy of a country (% based on the data available at [Our World in Data](https://ourworldindata.org/grapher/self-reported-trust-attitudes?tab=map)), the probability that a person become a bad seed and the probability that there is a misunderstanding in the interaction between two people. Run the simulation by clickng the "*Step*" or "*Go*" buttons.

## THINGS TO NOTICE

People that for sure start trusting use blue color, people that are bad seeds use red color. Data for the intiial setup of the country is read from the Tab Separated file "self-reported-trust-attitudes.tsv".

## THINGS TO TRY

Change the way the country starts by changing the probability of be a bad seed or the probability of a misunderstanding, also you can setup that people that are willing to change start trusting or not in the first round.

## EXTENDING THE MODEL

You can add more strategies for the interaction between the agents or give a reward based on the interaction, also could be interesting to improve the way that the agents find a partner.

## NETLOGO FEATURES

find-partner uses some network extension routines to clear the links and create random new ones, setting the color of the link based on two nodes trust.

## RELATED MODELS

Please check the Prisioners dilemma models to understand the basis of model. Available in the models library of Netlogo.

## CREDITS AND REFERENCES

Copyright 2002 Nicolas Bohorquez.

![CC BY-NC-SA 3.0](http://ccl.northwestern.edu/images/creativecommons/byncsa.png)

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License.  To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/3.0/ or send a letter to Creative Commons, 559 Nathan Abbott Way, Stanford, California 94305, USA.
