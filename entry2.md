# Earsketch Basics

Earsketch has a tutorial on the website that goes through everything on how to use earsketch and teaches you how to make music on the website. The website has video
explaining what I am going to talk about below but I want to put it in my words and write about what I understood from it.
The Earksketch website has a basic workspace that you do most of your work in. Here is a picture of it below.
<img src ="https://b4e6e57a-a-cd86e757-s-sites.googlegroups.com/a/hstat.org/gabrielc0464sep/web-design/screenshot.png?attachauth=ANoY7cqJ3Gh28LCVDk6kRiXX4p4tzVjr-nEZ4s8TohcxOatD4yvluWQqmVEVJsWHfEacKPzewTyCBfzamazUM95oCZOPSQVNqwmwbMfbtq8NbcXfdWEctyGxAuRWzmZtBz-rfQkvLntOteUOSf0Af_Nw0QzqPw4O18WpxKjOYsKBf0nyzLR2TB6JNAISlDnSQLbHYtvn1tk0A2_Vhm8OGhQu_3Ru-OxjiB52RGnPy6pg8vvISFALGzU%3D&attredirects=0"    >

This the basic setup of the Earsketch Workspace. In order to use earsketch and save your programs you need to create an account. You can see on the top right corner
I am already signed in to my account. The place where you see that video is the curriculum. Thats the place where the tutorial is located.
The Digital audio workspace or the **DAW** is the place where your music pops up and where you can hear the music you code. The
code editor is the place where you write your code to make the music. You can create multiple scripts in either Python or Javascript. I forgot what scripts
were exactly so I had to google what it was. A script in this case is a place where you the user can interact and change what music is being played
and where you can control evry aspect of the music. The icon with the headphones on it is where you can get all of the music clips to use in your code.

<img src ="https://sites.google.com/a/hstat.org/gabrielc0464sep/web-design/soundimage.png?attredirects=0" height = "450" width = "450">

You can search up what exact music file you like or you can search by the type of instrument,genre or artist. The folder below that is where your scripts are. You can create 
multiple scripts. Their is also a folder that lists all of the functions that you can use in the workspace. You can do alot in Earsketch but this is just basics of the 
website.
## Basic code 
This is the basic code for Earsketch.
```json
# python code
#
# script_name: Intro Script
#
# author: The EarSketch Team
#
# description: This code adds one audio clip to the DAW
#
#
#

#Setup Section
from earsketch import *
init()
setTempo(120)

#Music Section
fitMedia(TECHNO_SYNTHPLUCK_001, 1, 1, 9)

#Finish Section
finish()
```
 The **#** sign is how you comment the code in Earsketch. You can use comments to sort out your code into sections jsut like in the code above. In order to start the code you 
 have to use this line of code ``` init()  ``` under it is where you set the tempo of the music. Tempo means the speed of the music. To select a music track to play in you have
 to use the fitMedia fucntion. In the parenthesis you put the track name from the folder and then you type in the other 3 numbers for how long the music track will run.
 
## Takeaways
When learning about a topic there are some things you should do 
- Google ALOT. If something doesn't make sense look it up.
- Experiment with the different aspects of your topic. Have fun and play with it.
