# Earsketch Abstraction Part Two

In the previous entry we learned what Abstraction is. A brief 
explanation would be that abstraction in Earksketch is when you make different functions similar to ones like ```fitMedia()``` and ```setEffect()```.
In the last entry I talked about a for loop which is a common concept in coding but in earsketch its used to loop tracks together to make it sound better.
Another thing you can do with for loops is ad effects to the tracks like panning. 

<img src = "http://www.surfwhammys.com/Rainbow-Panning-Arc.png">

Panning is a way fo controlling how much ou hear a track on one side of your headphones to the other. Its like the music is moving around in your speakers or headphones

This is the basic code for panning while using a for loop
```
for track in range(1, 5):	panAmount = 200 * (track - 1) / 3 - 100
	setEffect(track, PAN, LEFT_RIGHT, panAmount) 
 ```
## Takeaways
- Play around with the code to make sure it makes sense to you.
- Try to find videos explaining topics you aren't clear on as it's easier to understand it if you see it visually.


