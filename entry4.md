# Earsketch Abstraction Part Two

In the previous entry we learned what Abstraction is. A brief 
explanation would be that abstraction in Earksketch is when you make different functions similar to ones like ```fitMedia()``` and ```setEffect()```.
In the last entry I talked about a for loop which is a common concept in coding but in earsketch its used to loop tracks together to make it sound better.
Another thing you can do with for loops is ad effects to the tracks like panning and volume gain. 

#Panning
<img src = "http://www.surfwhammys.com/Rainbow-Panning-Arc.png">

Panning is a way fo controlling how much ou hear a track on one side of your headphones to the other. Its like the music is moving around in your speakers or headphones

This is the basic code for panning while using a for loop
```
for track in range(1, 5):	
 panAmount = 200 * (track - 1) / 3 - 100
	setEffect(track, PAN, LEFT_RIGHT, panAmount) 
 ```
 What this code does is that it iterates through tracks 1 through five but ends at track 5. In these tracks it pans the track by the panAmount variable has been defined.
What the equation in the panAmount variable does is that it grabs the track and goes through the equation and the number that it gets determines what side the music plays on.
On the first track you get -100 which means that the sound will pan all the way to left side of your headphones. On the second track the equation then equals -33 so its getting
closer to the right side of the headphones.
#Volume Gain

What volume gain does on a track is that it lowers the volume to 0 and raises it based on the eqaution you used in your code. alot of math is invovled in these sound effects.
This is the basic code for a volume gain loop.
```
for measure in range(1, 17):
  setEffect(1, VOLUME, GAIN, -60, measure, 0, measure+1)

``` 
What this loop does is that is that it gets the volume and gain fucntions and for every measure it decreases the volume to 0 and then slowly raises the volume to normal. For every
new measure it repeats this process.
## Takeaways
- Play around with the code to make sure it makes sense to you. 
- Try to find videos explaining topics you aren't clear on as it's easier to understand it if you see it visually.


