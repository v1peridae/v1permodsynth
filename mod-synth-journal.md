# mod synth! — Journal Export

- Exported at: 2026-07-03T07:13:49Z
- Project ID: 630
- Entries: 12

## Entry 1
- ID: 4969
- Author: lou
- Created At: 2026-01-08T16:54:00Z

### Content

I've always thought hardware to make music was pretty cool! I listen to lots of electronic music and this was specifically inspired by the modular synthesiser tracks by Aphex Twin and Autechre (and at some point Deadmau5 🫩 BUT I AM PAST THAT I PROMISE) 

If you're not familar, a modular Synthesiser looks like this:
![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzgxMDUsInB1ciI6ImJsb2JfaWQifX0=--f8095dfefbd194160504b8214a08fc0b84bcaabf/image.png)
Mine won't look as cool but you get the picture.

I've been doing the research on and off rather than in one continuous stream. In the research phase I was mainly learning about how the work under the hood and good starting components to begin with! YouTube has been the greatest helper with how the components work and [this](https://analogoutputblog.wordpress.com/synth-diy-repositories/) has been the greatest helper when it comes to figuring out DIY. I've also been looking at old resources like CGS and Eddy Bergman to figure more out especially on the DIY end :D

So I'm going to be making : 
1. Voltage-Controlled Oscillator
2. Low-Frequency Oscillator
3. Voltage-Controlled Amplifier
4. Voltage-Controlled Filter
5. Envelope Generator 

Obviously just to start since there's lots more I can add here.

I'm going to have a 12V Eurorack setup probably!

I played around with these in VCV Rack to get a taste of how they work!![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6NzgwODcsInB1ciI6ImJsb2JfaWQifX0=--77ea878863179895d23cb5cad892a5d36b33e140/image.png)

## Entry 2
- ID: 4970
- Author: lou
- Created At: 2026-01-10T18:26:00Z

### Content

So I started building the VCO which is like the main part since it varies all the voltage.
I used this tutorial for the main stuff but tweaked it as you can see mostly because I didn't want to have as many THT parts and prefer SMD where possible :D It also involved lots of figuring out what does what since the docs aren't the MOSSST descriptive so I obviously messed up lots but I think I (MIGHT) have figured it out. Like one of the potentiometers is put as a var resistor symbol while the rest are potentiometers simply bc of the lack of the last connection. 

ALSO AMERICAN SYMBOLS ARE SO CONFUSING WHAT.


This is what the Schematic looks like ![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODAwMTksInB1ciI6ImJsb2JfaWQifX0=--08616f628751caea8e5928abfb36b66735aa2889/image.png)


In the future I might add more wave functions but square is a pretty good start!

This is what the routing looks like: ![Screenshot 2026-01-10 at 21.19.44](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODAwMTcsInB1ciI6ImJsb2JfaWQifX0=--3ac5f7a969eaa82269520d1faa022336dd3810f3/Screenshot%202026-01-10%20at%2021.19.44.png)

Up next is the VCA!

## Entry 3
- ID: 4971
- Author: lou
- Created At: 2026-01-18T17:31:00Z

### Content

A VCA is an amplifier!!
I'm gonna seperate this into 2 parts, schematics then PCB. I used [this](https://www.bartonmusicalcircuits.com/vcamix/index.html) and [this](https://www.birthofasynth.com/Thomas_Henry/Pages/VCA-1.html). I can't lie it's been a little hard for this one lol but I think the schematics took far less time bc im now used to what I need to know. I also switched out parts for stuff JLC can assemble for me as much as i can but there are some parts that JCL just cant so I gotta do ts myself. 

Schematics thus far!

![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODUxNjUsInB1ciI6ImJsb2JfaWQifX0=--d55210b58ee5fbfc23f827abb41175219d6a9775/image.png)

## Entry 4
- ID: 4972
- Author: lou
- Created At: 2026-01-19T14:52:00Z

### Content

So i just finished my VCA...
Let me start by saying HOLY ROUTING NIGHTMARE OH MY GOD. I have spent a sold 3 hours just trying to arrange the parts then route ts. This is what it looks like thus far! I have about 3 errors from DRC but im gonna assume those errors cant hurt me. I used the GND tutorial from the devboard which simplified my work so much more :))

I've been doing this for almost 4 days now so I am so glad I am done...up to the next thingamabob!


![image](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6ODU2NzksInB1ciI6ImJsb2JfaWQifX0=--2dab91cfecaa35b5b970960bc1cf5c20933c51d1/image.png)

## Entry 5
- ID: 4973
- Author: lou
- Created At: 2026-01-30T20:32:00Z

### Content

Hi hi! So I worked on this guitar input. Idk if i'll be able to finish up everything else before Blueprint ends :heavysob: I just have so much to work on arggggg so I think for now I'll submit these. I also just realised I never put my stuff on Github and I will be hunted for sport by reviewers soon </3

I got help from [this](https://www.bartonmusicalcircuits.com/gtrin/documentation.pdf)

This was probably the easiest part so I finished it up within like 3 hours. I ALSO HAD NO ERRORS. NOTICE HOW LOCKED IN I AM???
 ![Screenshot 2026-01-29 at 11.02.52](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTUyOTMsInB1ciI6ImJsb2JfaWQifX0=--820eba704d6226fb046a6769045a3f5d6f56bd38/Screenshot%202026-01-29%20at%2011.02.52.png)

Le schematic
![Screenshot 2026-01-29 at 11.03.36](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTUyOTUsInB1ciI6ImJsb2JfaWQifX0=--bf0a85596f0706a9319a4484ce78c2fc3d3aabc3/Screenshot%202026-01-29%20at%2011.03.36.png)
Le PCB
![Screenshot 2026-01-29 at 11.03.16](https://blueprint.hackclub.com/user-attachments/blobs/proxy/eyJfcmFpbHMiOnsiZGF0YSI6OTUyOTQsInB1ciI6ImJsb2JfaWQifX0=--e17beeced9cf0fac74e9bbac060e72eac6c00f42/Screenshot%202026-01-29%20at%2011.03.16.png)

## Entry 6
- ID: 4974
- Author: lou
- Created At: 2026-05-02T05:16:39Z

### Content

Project transferred from Blueprint! Duration Transferred: 18.0h

## Entry 7
- ID: 8107
- Author: lou
- Created At: 2026-05-20T07:32:42Z

### Content

i worked on the 4lfo. i'm getting the hang of this so i'm super happy this is getting quicker :) this is one of the easier components so it might take me a little under 3 hours to make but im happy i'm finally getting this done.

hard parts? mmmm i don't think there were actually any hard parts outside figuring out what the fuck american symbols mean :pf:

i also decided to use 4 layers for this one because it made routing easier. never done that before but i really enjoyed doing that.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NjkwMiwicHVyIjoiYmxvYl9pZCJ9fQ==--39751d45e21e28274b8a3fb68887ebaae16aeb35/image.png)

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTc3MzEsInB1ciI6ImJsb2JfaWQifX0=--41120f126973a71794259f6a322afaedd8e1fb32/image.png)


### Recording Links

- https://lookout.hackclub.com/api/media/254f5015-b547-4b64-813b-f652eff59c81/video.mp4
- https://lookout.hackclub.com/api/media/c7d9977c-03ef-436e-be6a-447fcc133e85/video.mp4
- https://lookout.hackclub.com/api/media/2c16f990-9627-497f-b129-cb42529b9ac3/video.mp4
- https://lookout.hackclub.com/api/media/4dcfd294-e018-45b3-af8e-af4b0ad8f3b9/video.mp4
- https://lookout.hackclub.com/api/media/b42f091e-bb68-49f8-a317-3bbb6d3be94f/video.mp4

## Entry 8
- ID: 9162
- Author: lou
- Created At: 2026-05-25T17:51:06Z

### Content

i've been working on the schematics for my fm drum! it's designed to create unconventional and unnatural textures and synthetic percussion :) 
**here are the schematics**

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjAyODcsInB1ciI6ImJsb2JfaWQifX0=--f94528904f9d0138a6702bfde63568c821a1eef7/image.png)

i learnt alot from making this which means i have a lot to fix in my older stuff... mostly with some of the power supply stuff and the tl074/tl072.

will complete routing tmrw! 

im glad im getting faster and better at doing this :D

### Recording Links

- https://lookout.hackclub.com/api/media/666c798c-b988-48d3-a105-8d83bd73a606/video.mp4
- https://lookout.hackclub.com/api/media/1e7f963f-7c3f-451a-a312-f2ec80182804/video.mp4
- https://lookout.hackclub.com/api/media/89d17c2f-7477-4ceb-8acc-8d4e37869226/video.mp4

## Entry 9
- ID: 9452
- Author: lou
- Created At: 2026-05-26T19:25:01Z

### Content

hi hi! so i finished the fm drums and i'm currently using my newfound knowledge to fix my older pcbs (see prev devlog). here is the new fixed vco.

![image.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjA5OTUsInB1ciI6ImJsb2JfaWQifX0=--5d38fa5c136128fa513e77736186ada5bbb9b06d/image.png)

also the 17 min long log might be a lil shorter bc i was working from a cafe so i took eating breaks for like 30 seconds and all.


### Recording Links

- https://lookout.hackclub.com/api/media/01bfbfd5-133d-4821-b6bc-78ae78223fac/video.mp4
- https://lookout.hackclub.com/api/media/4d018d23-aed7-4f36-ab41-915f41100638/video.mp4
- https://lookout.hackclub.com/api/media/50de6fa7-70f4-43f6-9218-0a3cec68bf60/video.mp4

## Entry 10
- ID: 9659
- Author: lou
- Created At: 2026-05-27T14:17:05Z

### Content

fixed vca and added some decor :)

so i decided to fix my vca since and reroute it since after i changed the schematics all the routing turned out to be wrong. i also added some cute decor for the vca in the same style as the vco :)
![Screenshot 2026-05-27 at 17.14.40.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjE0MzcsInB1ciI6ImJsb2JfaWQifX0=--dc0ed39a4c0a09ef1268755b0d2863231a82e9a2/Screenshot 2026-05-27 at 17.14.40.png)


### Recording Links

- https://lookout.hackclub.com/api/media/017498c4-98fe-4673-93ac-65d4ebbb52b3/video.mp4
- https://lookout.hackclub.com/api/media/8d289a57-20fc-4ead-98d7-aa008f37cf2b/video.mp4
- https://lookout.hackclub.com/api/media/cd11847e-4ab6-44cd-961b-9dd82fdf83e7/video.mp4

## Entry 11
- ID: 9967
- Author: lou
- Created At: 2026-05-28T18:04:17Z

### Content

So i did some fixing on my guitar input and then added some decor so it's good to go now! Lots of cool learning from the previous day so i'm really glad i got to learn that theyre are different variants to the same unit since that has probably saved my entire system. next is adding a simple AR to my system which i've already started on (i'll journal about this in better detail one it's on)

![Screenshot 2026-05-28 at 20.02.18.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjIyNjIsInB1ciI6ImJsb2JfaWQifX0=--70dd73d0a2f32e57099dfb28a7d10ddc54bc6b80/Screenshot 2026-05-28 at 20.02.18.png)
![Screenshot 2026-05-28 at 20.01.55.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjIyNjgsInB1ciI6ImJsb2JfaWQifX0=--7a9e565b9eae61c85172f83c4068495d3ecb33bb/Screenshot 2026-05-28 at 20.01.55.png)


### Recording Links

- https://lookout.hackclub.com/api/media/ef716bb8-1abb-4f87-9535-b88e8755269b/video.mp4
- https://lookout.hackclub.com/api/media/fd7e7cbc-a6ea-4806-a5a6-648855f2a1bf/video.mp4

## Entry 12
- ID: 10072
- Author: lou
- Created At: 2026-05-29T06:11:20Z

### Content

is the modsynth complete? ...yeah (for now). did some decor touches and tried to finish the AR as fast as i could. im really happy with all the progress i've made over time and being able to get from 5 hour builds with lots of mistakes to 1-2hr builds with minimal errors :). i've learnt a shit ton about kicad through this and the tutorials i followed. shout out to https://www.bartonmusicalcircuits.com/synthstuff.html for all the helpful resources about building a synth :D if it wasnt for their resources i would be super lost. although they werent very clear and i ended up fucking up a ton in the beginning, i got the hang of it and i'm done! i'm left with updating the github which i will later today and then i start on my next project :D

### today's progress...
![Screenshot 2026-05-29 at 09.02.34.png](/user-attachments/blobs/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MjI3MjksInB1ciI6ImJsb2JfaWQifX0=--3397be78e32528e6f810bd97b3ea6b40df2cd56e/Screenshot 2026-05-29 at 09.02.34.png)



### Recording Links

- https://lookout.hackclub.com/api/media/206eb605-851f-4c07-8cec-c4d512dba3dc/video.mp4
- https://lookout.hackclub.com/api/media/da2813a5-71fb-49d3-a33c-df836aa85cb8/video.mp4
