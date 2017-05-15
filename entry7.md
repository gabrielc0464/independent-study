# Effects in Earsketch

In Earsketch there are many effects that can be used in your code to make your music sound a certain way. 
Earsketch has a section where they explain every effect and what it does but I found that the way that they describe
each one is a little confusing. This is a simplified version of that.

## BANDPASS

BANDPASS is an effect that filters the frequencies of a track. It can make that track sound like it's coming out of a megaphone or
a small speaker or a telephone. Here is the link to what BANDPASS sounds [like](https://clyp.it/x0clzrbz) 
```
setEffect(1, BANDPASS, BANDPASS_FREQ, 200)
```
This is the basic code for BANDPASS. The default number is 200 but the range is from 20 to 20,000.

##CHORUS

CHORUS is an effect that creates copies of the orginal track and makes copies of it that differ slightly in pitch and sound which is the then mixed back
with the original track making it sound like a chorus of that same track. Click [here](https://clyp.it/z2hzmedc) to hear the CHORUS.
```
setEffect(1, CHORUS, CHORUS_LENGTH, 53.0)
```
Basic code for CHORUS. This determines how long the chorus effect lasts for. Range from 1 to 250.

```
`setEffect(1, CHORUS, CHORUS_NUMVOICES, 4.0) `
```
Determines the numnber of copies that are made of the track. Range from 1 to 8.

##COMPRESSSOR

COMPRESSSOR is an effect that decreases that loudest sounds of a track while increasing the lowest sounds of the track.
Click [here](https://clyp.it/0odk4nxt) to hear the COMPRESSSOR.

```
setEffect(1, COMPRESSOR, COMPRESSOR_THRESHOLD, -4.0)
```
determines the volume level that the trakc has to reach for the effect to reduce the volume. Range from -30 to 0.