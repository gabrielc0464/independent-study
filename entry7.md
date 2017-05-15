# Effects in Earsketch

In Earsketch there are many effects that can be used in your code to make your music sound a certain way. 
Earsketch has a section where they explain every effect and what it does but I found that the way that each effect is described
are a little confusing and some of the effects aren't that useful. This is a simplified version of that.

## BANDPASS

BANDPASS is an effect that filters the frequencies of a track. It can make that track sound like it's coming out of a megaphone or
a small speaker or a telephone. Here is the link to what BANDPASS sounds [like](https://clyp.it/x0clzrbz) 
```
setEffect(1, BANDPASS, BANDPASS_FREQ, 200)
```
This is the basic code for BANDPASS. The default number is 200 but the range is from 20 to 20,000.

## CHORUS

CHORUS is an effect that creates copies of the orginal track and makes copies of it that differ slightly in pitch and sound which is  then mixed back
with the original track making it sound like a chorus of that same track. Click [here](https://clyp.it/z2hzmedc) to hear the CHORUS.
```
setEffect(1, CHORUS, CHORUS_LENGTH, 53.0)
```
Basic code for CHORUS. This determines how long the chorus effect lasts for. Range from 1 to 250.

```
`setEffect(1, CHORUS, CHORUS_NUMVOICES, 4.0) `
```
Determines the number of copies that are made of the track. Range from 1 to 8.

## COMPRESSSOR

COMPRESSSOR is an effect that decreases that loudest sounds of a track while increasing the lowest sounds of the track.
Click [here](https://clyp.it/0odk4nxt) to hear the COMPRESSSOR.

```
setEffect(1, COMPRESSOR, COMPRESSOR_THRESHOLD, -4.0)
```
determines the volume level that the trakc has to reach for the effect to reduce the volume. Range from -30 to 0.

## DELAY

DELAY is an effect that creates an echo sound of the original track. Similar to the CHORUS effect.
Click [here](https://clyp.it/2u3iwyjr) to hear the DELAY.

```
setEffect(1, DELAY, DELAY_TIME, 1200.0)
```
Basic code for the DELAY effect which determines how much the sound is delayed (in Miliseconds). Range from 0 to 4000.

## DISTORTION

DISTORTION is an effect that creates a dirty or fuzzier version of the original sound.
Click [here](https://clyp.it/ofu3kymc) to hear the DISTORTION.

```
setEffect(1, DISTORTION, DISTO_GAIN, 25.0)
```
Basic code for the DISTORTION effect that determines the amount of Distortion. Range from 0 to 50.

## PAN

PAN is an effect that effects the audio betweem the left and right side of your headphones.
Click [here](https://clyp.it/jvtxvj4i) to hear the PAN.

```
setEffect(1, PAN, LEFT_RIGHT, -50.0)
```
Basic code for the PAN effect which determines the location of the sound. Range from -100 to 100.

## PITCHSHIFT 

PITCHSHIFT is an effect that lowers and raises the sound by a pitch interval.
Click [here](https://clyp.it/4x151mm5) to hear the PITCHSHIFT.

```
setEffect(1, PITCHSHIFT, PITCHSHIFT_SHIFT, 4.0)
```
Basic code for the PITCHSHIFT effect that specifies how much the pitch should be adjusted. Range from -12 t0 12.

## TREMOLO 

TREMOLO is an effect that quickly changes the volume back and forth to create a wobble effect.
Click [here](https://clyp.it/2pjgaak4) to hear the TREMOLO.

```
setEffect(1, TREMOLO, TREMOLO_FREQ, 10.0)
```
Basic code for the TREMOLO effect which determins how fast the volume is changed. Range from 0 to 100.

```
setEffect(1, TREMOLO, TREMOLO_AMOUNT, 10.0)
```
This code determines how much the volume is changed. Range from -60 to 0.

## VOLUME

VOLUME is an effect that (obviously) changes the volume of the sound.
Click [here](https://clyp.it/qukbucff) to hear the volume.

```
setEffect(1, VOLUME, GAIN, -5.0)
```
Basic code for the Volume effect which increases or decreases the volume. Range from -60 to 12.

# Takeaways

- Not everything is important. This is a takeaway for life in general but especially for reading instructions or tutorials. Always try to 
grasp the most important parts and not every little thing that is given to you. Its very useful for saving time.

- If something doesn't make sense to you go online and ask people or just ask people around you. Maybe you just need a different perspective 
to understand something

- Make sure to double check your syntax in Earsketch and coding in general. Usually errors come from that one missing comma or semi-colon.