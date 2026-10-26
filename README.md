
<h1>Hi-fi Audio Amplifier</h1>

<h2>Description</h2>
I have made the full schematic and PCB design of a Hi-fi class D Audio Amplifier. Not only have I designed it, but i also ordered the PCB, soldered all the components in place, tested, troubleshooted and verified the whole circuit. I used the EasyEDA tool in order to bring this project to life and create the manufacture folders for the final order. All of the components that were used are THD format, including the ICs and voltage regulators.
<br />

<h2>The Technology of the Circuit</h2>
The basic idea was quite straight forward. I planned to use a 555 timer IC to generate a high frequency ramp waveform (~300kHz) that would enter the inverting input of a LM393 comparator, along with a modulating signal coming from the jack port of a laptop. The comparator would output a 300kHz digital signal that would be the carrier. The carrier along with the modulated signal would enter a CMOS circuit in order to amplify the digital signal in amplitude, but also to enter a Low Pass filter that could reconstruct the original modulated signal. This procedure would have been efficient because a normal speaker can't function   
<br />
<h2>The Schematic in Simulator</h2>
<img src="https://imgur.com/SR3YW1U.png="80% width="80%" alt="Disk Sanitization Steps"/>
<br />

<p align="center">
  Watch video:  (https://imgur.com/KCqMg5V)

 <br/>

