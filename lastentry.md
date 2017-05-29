# Entry - 8 Finalizing Project

For my final project I made a music track that uses things that I learned throughout the past 7 weeks. I wanted to incorporate as many
things as possible in my project but I didn't want do overdo it and dectract from my project. The biggest thing that I wanted to get
out of this project is to make music that sounds GOOD. Here is the code to my project
```
from earsketch import *

init()
setTempo(100)
cymbal = Y14_CYMBAL_1  
beat1 = "0++"

for measure in range(5,25,4):
    makeBeat(cymbal,4,measure,beat1);

fitMedia(RD_RNB_808SOLODRUMS_5,2,9,25)
fitMedia(YG_FUNK_ELECTRIC_PIANO_1,1,1,29);
fitMedia(YG_FUNK_TAMBOURINE_2,3,13,25);
fitMedia(YG_FUNK_HIHAT_1,5,13,25);
fitMedia(HIPHOP_FUNKBEAT_004,6,13,25)
fitMedia(YG_RNB_FUNK_PERC_2,8,5,25);
fitMedia(HIPHOP_FUNKBEAT_004,13,33,37) 
#setEffect(13, PITCHSHIFT, PITCHSHIFT_SHIFT, 2.0)
fitMedia(YG_FUNK_BRASS_4,17,29,37) 
fitMedia(YG_FUNK_GUITAR_1,18,33,37)
#setEffect(17, PITCHSHIFT, PITCHSHIFT_SHIFT, 12.0)
beat4 = "0+++++++0+++++++"
snap = YG_RNB_FUNK_SNAP_1
for measure in range(29,37,1):
    makeBeat(snap,16,measure,beat4);




beat2 = "0++++++++++++++++++++++++++"
guitar = YG_FUNK_FUNK_GUITAR_1

for measure in range(5,25,2):
    makeBeat(guitar,9,measure,beat2);


fitMedia(guitar,10,1,5)


beat3 = "0+++++++0+++++++"
cymbal2 = YG_FUNK_CYMBALS_1
for measure2 in range(28,29,2):
   makeBeat(cymbal2,15,measure2,beat3);


finish();



finish()

```

Some lines of code have a hashtag at the beggining which means that its code that I commented out. I never took it out of my project just
in case I might go back to it eventually. I also think it represented what I was thinking at the time and its sort of like a sign of my progress
in my project.

# Takeways


1. Make sure YOU are proud of what you made. Having people's approval is one thing but if you yourself aren't happy with what you made then
was it even worth making?
2. Have fun. Thia was probably my favorite unit in all of SEP and I know this because I worked on it alot at home. I usually don't work on
software projects at home alot and when I do I am jus tdoing it because I have a due date but in this project I just had alot of fun making the song.
It was always on my mind.
3. Have people to talk to. In the beginning of making this project I didn't know if what i was making sounded good. I eventually showed justin my project
and he liked it and from there on I started to regularly ask him for input on my project and it drastically improved my progress on it.



