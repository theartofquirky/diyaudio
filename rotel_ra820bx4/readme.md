
# Rotel 820BX4 repair

I got an Rotel 820BX4 off ebay recently which had one channel not working. 

After i got it I had a good look on the parts and for shorts did and quickly found that fuse F601 was blown but couldn't find any other issues.

I've replaced the fuse and adjusted the bias to 2.5mv and dc offset to about +/-5mv (best could get close to 0) and so now the amp works. 

However I've discovered another issue. Driver transistors Q623 & Q625 run much hotter on one channel. I can only barely keep my finger on the heatsinks whereas on the other channel the heatsinks feel stone cold.

![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/1.png)

I read +/-1.1V at the bases of the 4 driver transistors, so it would appear there is variation from the schematic, but could be normal... not sure...

The driver transistors are thermally connected to their heatsinks, when I touch the transistors themselves they are hot/cold.

I couldn’t get a good resistance reading for all the 2w resistors, but I do read 35.7V across all 4 of them. Interesting enough I can get a ~0.9kR reading across the resistors in the hot channel but I read in the kilo/mega range for the cold channel. All 4 resistors had slight cracks on them, I thought I would replace them as I suspected they are begging to go open. All power transistors read well and don't get hot, just lukewarm.

It was difficult to tell but reducing bias via VR601 seemed to make the drivers warm up slower, but they seem to reach the same temperature in the end.

Strange thing is the amp actually seemed to be working... I wouldn't say it sounded amazing but not bad.

![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/2.png)

Then I've ran into another problem. I was probing the voltages across the emitter resistors when I touched one of the bus bars with my probe. It would appear I shorted something and now I have one dead channel... school boy error...!!

Now the previously cold channel reads open on the speaker terminals and the main heatsink seems to heat up very rapidly on the side of this channel.

The diagnosis was not as bad as I thought. Turns out I fried a couple of output and one driver transistor, Q628, Q630 (2SD1047) and Q624 (2SD600K) which coincidentally were all on the cold channel. All remaining transistors appeared to read ok at diode test.

I thought I would order a full set of drivers/output transistors for the bad channel, it deserved it after all that trouble! In the end I ordered some KSC2690/KSA1220's to replace all 2SD600/2SB631 drivers. 

Emitter resistors seemed to be in good knick, all 4 read the same 0.34 ohm resistance but not 0.22R as per schematic. Hmm should I worry about that and change them too?

The 2W910 resistors also got changed with higher wattage ones. Suspicions confirmed. When I took the 910R resistors out, two of them measured at about 1.3Meg so they seemed to be heat fatigued. This is why the drivers were cold, not much current going through them... 

Also turned out the output devices that I thought were bad tested okay outside the circuit on my tester. It must have been the bad driver that was causing the bad reading then.

The second picture shows transistor Q901 which forms part of a zener based series regulator for the phono stage. I don't have a means of testing phono (I had sold my turntable long ago) but I could hear a strange static noise from the speakers when nothing was connected. I replaced it with a spare 2N3904 and the staic was gone. Note the crossing legs due to the different pinout!

![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/3.png)

And she lives!

So I ended up changing the driver resistors and transistors, a few diodes here and there (for peace of mind), and did a full recap. Upgraded the bridge rectifier which was rated 200v (not 250v...?) to 400v, and the main filter caps from 8200uf to 12000uf too which seems to have made a difference to the bass output.

Sounding great! 

Verdict:

* I don’t know if it’s Stockholm syndrome but I ended up loving this amplifier. Thumbs up for repairability, quality was okay
* Thumbs up for sound. I really liked it, even better than the Pioneer A400
* Thumbs up for looks. Nothing too special, but I do love an understated amp

![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/4.png)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/5.png)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel7.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel8.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel9.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel10.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel11.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel12.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel13.jpg)
![alt text](https://github.com/thequirky/diyaudio/blob/master/rotel_ra820bx4/images/rotel14.jpg)
