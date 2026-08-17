Total Time: 14.6h

Date Descending

# Finishing up
Aug 1, 2026
Ginobeano
Ginobeano
1h


Finishing up
Today I just finished up the project.

README
I wrote a bunch of stuff and formatted the README all nice and all.

It took pretty long to get all the BOM good and photos and etc.

Conclusion
This was a nice fun project. now to wait for it to be built. bye.

<img width="1354" height="1354" alt="image" src="https://github.com/user-attachments/assets/ace21dcb-cdbd-4bb9-9ca6-f2bbbff0abd4" />


# PCB v1
Jul 31, 2026
Ginobeano
Ginobeano
2h


PCB v1
This has been quite a session. I finished laying out the PCB, wiring it, and so much more.

Wiring
I have never made a board this compact, and making it 2-layer is really a mess. Nevertheless, I still pushed through and wired everything up. I had a real hard time doing this. I had a lot of space constraints, and I had to expand the board a slight bit to 11mm and ugh, I am just happy it is done.

<img width="1637" height="1201" alt="image" src="https://github.com/user-attachments/assets/6c88af15-7a08-47df-9b81-0e486e6eb284" />
<img width="426" height="721" alt="image" src="https://github.com/user-attachments/assets/e2a0529e-1ff7-4ae7-8d84-deb2532a5f27" />


But it is a bit too expensive. Maybe not, but I would still like to lessen it somehow. but that is for tomorrow.image

<img width="2256" height="1364" alt="image" src="https://github.com/user-attachments/assets/7c8e36e5-198f-4fa6-8853-b3eac09a41ae" />

# Start Wiring
Jul 31, 2026
Ginobeano
Ginobeano
0.3h


Start Wiring
This was just a short little one because I still had some time. I just started to wire up the USB port and a few other things. What has had me stuck for like 5 mins or so is how to connect CC2; the way it is placed in the footprint makes it pretty difficult, or maybe even impossible.

I am going to ask in Slack, but yeah, admire the work.
<img width="920" height="1136" alt="image" src="https://github.com/user-attachments/assets/c8a07f7b-10af-438a-ad4d-2a3ae1dbc60f" />


# A whole WLED Controller
Jul 31, 2026
Ginobeano
Ginobeano
1h


A whole WLED Controller
Isn't it crazy that I fit a whole WLED controller into a 10mmx40mm package (the width of an LED strip)? Even crazier, someone could probably make it smaller if they had more money and stripped some features.

I think this is the most compact board I have ever made. tbh it looks great

So obvi I pretty much laid out all the components. I might shuffle them around a bit while I am wiring things up, but as it stands now it looks pretty good.

Unfortunately, I had to omit the test points, but tbh I was probably not going to use them.
<img width="174" height="677" alt="image" src="https://github.com/user-attachments/assets/06964512-afc5-4f46-ae13-0edbb3deab60" />


# LCSC Part Numbers
Jul 31, 2026
Ginobeano
Ginobeano
0.3h


LCSC Part Numbers
I did a really tedious job and put all the LCSC Part Numbers in. Not much to talk about; I had all the tabs open, and I just put in the LCSC Part Number.

Now all I have to focus on is the PCB Layout!

<img width="1104" height="754" alt="image" src="https://github.com/user-attachments/assets/657388e4-fb42-47a2-aa82-8837e97ac73b" />


# Update Schematic & some PCB work
Jul 31, 2026
Ginobeano
Ginobeano
1.5h


Update Schematic & Some PCB work
So today I did quite a bit. I fixed a bunch of stuff on the schematic and started to lay out a few components on my PCB

PCB
Oddly enough, I actually started laying out the PCB first. I did this to get an idea of how small the board was going to be and just make sure nothing was too big.

Everything fit with just enough space, and I think we are good.

<img width="1104" height="754" alt="image" src="https://github.com/user-attachments/assets/184f2bbf-3f08-4785-b833-241f5168118d" />


Schematic
Next I worked on the schematic and a lot of stuff happened alot trying to find out what is wrong and finding parts that would work.

I was going back and forth on a sanity check thread I made on slack. I ended up with a few changes

added bulk cap
added TVS
added series resistors for USB data lines
removed L2
verified things And yeah, so lots of stuff done; it took me a while, but now the schematic should be fully done and ready to start laying out the PCB.

<img width="1104" height="754" alt="image" src="https://github.com/user-attachments/assets/205c94ee-a53d-4ab9-833b-a152108ae7da" />

# Footprints
Jul 30, 2026
Ginobeano
Ginobeano
1h


Footprints
This was awful I spent so long just picking parts and trying to het the cheapest stuff possible. Absoultly awful

Like just look at how many tabs I have open and this is just the parts I ended up picking not any of the ones I discardedimage

But at last it is done and we got the worst part out of the way. Worst part is I had to do this all 2 times because I accidentally cleared all the entries my first time.

<img width="2256" height="1417" alt="image" src="https://github.com/user-attachments/assets/45c4daf1-8aa9-4655-9b5b-9859df220cb1" />


# Finish Schematic for real
Jul 30, 2026
Ginobeano
Ginobeano
1h


Finish schematic for real
So I actually found out that I didn't finish the schematic yesterday I forgot the USB connection.

USB Connection
Now this was a bit of a doosy I wasn't quite sure how I should connect the board to Power and data at first. So the biggest problem with USB is just its bulkyness when it is supposed to blend in with the LED strip.

But after some research I came up that it would prbly be the best looking and I should just keep it.

Edge connectors
I thought about usb edge connectors because the would require no extra parts that I had to PCBA. I researched it a bit but ended up not going for it because it just isn't that reliable and also I would have to change the thickness of my board whihc in turn would increase price.

<img width="1178" height="757" alt="image" src="https://github.com/user-attachments/assets/eab1b4a7-5a06-4125-9f4f-01088513080f" />


Normal USB C Connector
This is proabably the easiest and most common connector but the biggest problems with it is that it is generally pretty bulky and also I would need to use PCBA for it. Which is fine because I am already getting PCBA but it is a extended part in JLC so it cost more. but it was less than what changing the thickness would be.

<img width="2256" height="1417" alt="image" src="https://github.com/user-attachments/assets/c20964a0-9bae-4e15-8e79-2861b3c24adc" />


Finished schematic
After I did all of that while altough not thrilled by the whole USB connector thing I got the schematic done and now I have to get it sanity checked.

<img width="1328" height="914" alt="image" src="https://github.com/user-attachments/assets/5c563eba-92d4-448a-b2f6-5f72a03204e4" />
Next are my least favorite steps of all time. LCSC part numbers and footprints

# Finish schematic
Jul 29, 2026
Ginobeano
Ginobeano
1h


Finish schematic
Today I finished up the schematic at least what I think is finished. I can't think of anything else I need.

It took me a while just reading all the docs for the level shifter and getting it all right. I did abunch of other stuff look in the repo I am tired and I am going to go to bed. gn.

<img width="1178" height="757" alt="image" src="https://github.com/user-attachments/assets/124ed623-891f-4e8c-8c65-f5acc14d83d5" />
<img width="1178" height="757" alt="image" src="https://github.com/user-attachments/assets/731033ba-a0a4-4543-b1e4-9d251d600aae" />


# Continuing (LDO, LED, and other research
Jul 28, 2026
Ginobeano
Ginobeano
1h


Continuing on
So I just came back to this project as just a quick little side project, and so today I did a few things

Moved to Macondo
This project originated in Forge, but since I revived it quite a bit later and am already familiar with Macondo, I figured I'd just keep it here. So I moved all the journals over here.

<img width="2256" height="1465" alt="image" src="https://github.com/user-attachments/assets/8bd42952-7240-48b2-b4f7-646d39cb438a" />


Researching some new components
So now I have to figure out everything I need again So I need a few key components: I need to get a level shifter and an LDO for 5v to 3.3v for the controller. I was searching on JLCPCB for parts that would be the cheapest and under basic parts so they are as cheap as possible. So I found an AMS1117-3.3V for the LDO,

<img width="2256" height="1460" alt="image" src="https://github.com/user-attachments/assets/4c5f0ad6-0503-4e4f-8825-d767e94fb4e9" />
and for the level shifter I found the SN74AHCT1G125DBVR and one other one that I decided againstimageNow the level shifter is extended, so depending on it, I might just hand-solder this.

Schematic
I also added things to the schematic, rearranged things, wired it up, etc.

<img width="2256" height="1465" alt="image" src="https://github.com/user-attachments/assets/03786add-06c3-449c-b66f-a2bf2a0504a7" />


# transferring over from forge
Jul 28, 2026
Ginobeano
Ginobeano
4.5h


nul
A WLED controller that blends into the background

2026-05-21: Finish ESP schematic
Total time spent: 1.5 hours

I mostly finished the ESP part of the schematic!
Probably the hardest part of the schematic is now done. A few things changed from last time I fixed a lot of things that would've caused an issue like

incorrect decoupling caps
not pulling botting lines up
No UART
Wrong pins for Oscillator
I also added some new things

The antenna
UART
LED Data light
and a few more things This time was mostly back and forth, getting feedback, reading documentation, and all that, but isn't that what building hardware is?<img width="1504" height="896" alt="image" src="https://github.com/user-attachments/assets/f93a414f-d643-4606-9eeb-baaf7331a055" />

2026-05-21: Started work on schematic
Total time spent: 2.25 hours

I started work on the schematic! :O
Before I go into all that, some things have changed.
I decided to go with a different ESP, namely the ESP32-C3FH4. This is mostly because it was cheaper. But I am pretty sure it is newer, and it has native USB, which is nice. ESPs are really confusing to buy the right one. I like the modules a whole lot more.

Schematic
I started work on the schematic, yay! Right now, it is very bare bones and just setting up the ESP. I got the SiP and all the decoupling capacitors, crystal, etc. I still have to get the antenna to complete this part of the schematic, but that isn't important. I still need to set up literally everything else, but so far it is going well.
<img width="1178" height="870" alt="image" src="https://github.com/user-attachments/assets/08569d13-ebae-4d42-8067-f9a38843be47" />
(Sorry for not devlogging for like 2 weeks, I lost interest)

2026-05-09: Started Brainstorming
Total time spent: 45 mins

The start of a new project. :O

This is nul a WLED controller meant to just fade in the background. A controller so small and so integrated with the LED strip, it's like it disappears, like it is null (You see what I did there).

Today I just brainstormed ideas. I came up with a few things that will make this unique

Super small (same width as LED strip)
Level Shifter
Bare ESP (No module)
USB C (Maybe PD but ehh)
and more
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/08c59919-781e-4ea9-afc9-151189bd3f84" />


Next, I selected some of the big components like the ESP, the level shifter, etc., stuff that actually makes the board.

For the ESP, I decided on the ESP32-PICO-V3-02, small and compact, while not having me deal with stuff like flash or anything
For the Level Shifter, the SN74AHCT1G125DBVR, nothing really special with this, just small and reliable, might change this, seeing that it isn't that big of a deal.
I already have a chip antenna idk what model it is. I will find out tmrw.
<img width="2256" height="1345" alt="image" src="https://github.com/user-attachments/assets/352acd87-3524-4544-a136-9147e0094254" />
<img width="2256" height="1345" alt="image" src="https://github.com/user-attachments/assets/f2284b82-b207-4b47-bd8d-9a1f5d504338" />

