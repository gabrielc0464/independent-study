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
#
# description: Using several makeBeat calls, and overlapping rhythms
#
#
#

#Setup

from earsketch import *
init()
setTempo(120)

#Music

synth = DUBSTEP_FILTERCHORD_002
cymbal = OS_CLOSEDHAT01
beat1 = "-00-00+++00--0-0"
beat2 = "0--0--000--00-0-"

for measure in range(1,4):
   makeBeat(synth, 1, measure, beat1)
   makeBeat(cymbal, 2, measure, beat2)

#Finish

finish()

```
This is an example of using a makeBeat fucntion to make a track. The variables are being used in the makeBeat fucntion for the lip name instead of having
to write out evry clip name in the function. Beat1 and beat2 are the custom beat strings that are being used on the clip


## Takeaways
- Play around with the code to make sure it makes sense to you. 
- Try to find videos explaining topics you aren't clear on as it's easier to understand it if you see it visually.


