# What is max available Gain?
The maximum available gain of a transistor is basically the highest gain you can get out of it in a power amplifier circuit, assuming you've matched the output perfectly. It's a theoretical limit that doesn't consider the input matching.
# So, what are the parameters that max available gain depends on?
The maximum available gain mainly depends on the transistor's transconductance (gm) and its output resistance (ro as well as the operating frequency. It's also influenced by the parasitic capacitances and resistances inherent in the transistor and its layout.
# Now we will find the Max Available Gain for the transisor, and see how it varies
## Circuit
<img width="1317" height="677" alt="image" src="https://github.com/user-attachments/assets/0f45bf09-50ed-4000-97f6-94a092ce6069" />

## Changing the choke inductance
<img width="869" height="750" alt="image" src="https://github.com/user-attachments/assets/d289767c-40ac-4bc5-88b5-2d827c784f1d" />

Changing the choke inductance does not have any impact on the max available Gain. 

## Changing the width of mosfet
<img width="869" height="752" alt="image" src="https://github.com/user-attachments/assets/b08e5731-7e41-40c1-aed3-8cb2b8060d26" />

The maximum available gain does not also increase with the width. I have heard that the Cadence model is not so good for relating transit frequency to w and also the maximum available gain.

## Changing Length of the mosfet
<img width="869" height="752" alt="image" src="https://github.com/user-attachments/assets/dd87a69c-5405-408f-a90e-2f6d86ea3fd1" />

The gain decreased to 10 dB from 18 db when I increased the gain .Becasue gm significantly decreases with the L increase



## changing VDD
if VDD is increased, the max available gain go up with it .

## Changing the bias Voltage 
if Vbias goes up , the max available gain also goes up . As the transconductance goes up.


