# Earsketch makeBeat() function and strings


In the previous entry, I talked about another fucntion called the for loop that can be used to add effects to your earsketch music file.
This time we are talking about a function that is called makeBeat() which is *obviously* used to make beats. First we have to understand strings
in order to use this fucntion.

## Strings in Python and makeBeat()

Strings in Python are characters surrounded by quotation or double quotation marks. In the makeBeat() function we need to use strings to 
form the beat. In earsketch the characters are being used to represent the 16 note sub beats of a measure. This is the basic code of a beat pattern string which
is assigned to a variable
```
myDrumBeat = "0-00-00-0++0+0"

```
The "0" in the code represents the start of a sound clip. The "-" in the code represents a rest which is silence in the track.
The "+" in the code extends the sound of the track in to the next sub beat of the measure. This is the basic setup but is not the only
setup you can use.

The makeBeat() fucntion takes in four parameters

- Clip Name
- Track Number
- Measure Number(starting measure only)
- Beat String 

```
# python code
#
# 
#
#

#Setup

from earsketch import *
init()
setTempo(120)

#Music

electro = RD_ELECTRO_MAINBEAT_5
choir = Y33_CHOIR_1
beat1 = "-00-00+++00--0-0"
beat2 = "0--0--000--00-0-"

for measure in range(1,4):
   makeBeat(electro, 1, measure, beat1)
   makeBeat(choir, 2, measure, beat2)

#Finish

finish()

```
This is an example of using a makeBeat fucntion to make a track. The variables are being used in the makeBeat fucntion for the lip name instead of having
to write out evry clip name in the function. Beat1 and beat2 are the custom beat strings that are being used on each clip. This will change the beat of the rack
that you selected. Feel free to try out this code on [Earsketch](https://earsketch.gatech.edu/earsketch2/)

## Takeaways
- Mess around with the beats to make sure that the track sounds right 
- Listen to remix tracks on youtube and other websites and try to mimick the beat that is being played there.
- Look at other peoples code. On the earsketch website click on competition and you can look at other peoples code and see how they fucntion.
It can give you inspiration for your own code.


