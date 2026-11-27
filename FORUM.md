# M605A — Audio Distribution Amplifier: on the WBSps forum

What owners, technicians and Ward-Beck people said about the M605A on the WBSps.ca forum (Simple Machines), 2006|39 to 2012|45: 7 topics, oldest first. Quoted as posted (contact details taken out). Made by tools/forum_quotes.py from the forum's database backups.

## Misc. WBS power supplies.

_WBS PARTS FOR SALE · Aug 23, 2006|39_

> From left to right - M621, M621, M621A, M621A, M605A, M648. Best Offer(s). The M600's are not for sale.
>
> M625A $100.00 obo
>
> More pics are available upon request. Each unit would be tested, as there is interest.

— **Kevin@Ward-Beck**, Aug 23, 2006|39

## 23 Manuals have been added to the site!

_WBS TECHNICAL SUPPORT · Jul 14, 2007|40_

> Greetings all 
>
> I have added 23 more manuals for your downloading bliss. Please only take what you need as bandwidth is expensive. if you Pay Pal me $20 I will burn a CD of EVERYTHING for you. 
>
> Here's what's been added
>
> http://wbsps.kuzub.com/manuals.htm
>
> M202 - Logic Latch Module
> M402B - Equalizer
> M405 - Portable Extended Vu Meter
> M433-434 - Peak Program Meter
> M435-436 - VU Meter
> M441M - Channel Amplifier
> M450A - Program Amplifer
> M454 - Slate Assign Module
> M455 - Auxiliary Module
> M456B - Dual Mixdown Module
> M457A - Pre Mixer Master Module
> M460A - Input Module
> M460B - Input Module
> M467-M567 - Noise Gate and Meter Module
> M470C - Input Module
> M471A - Stereo Input Module
> M472 - Equalizer
> M481 - Oscilator and Cue Amp
> M490F - Stereo Input Module
> M605A - Audio DA
> M625A - Power Supply
> M632 - Power Supply
> M648 - Power Supply
>
> I have almost 50 more to scan

— **kuzub**, Jul 14, 2007|40

## Convert M605A or M8205 DA into a mic splitter??

_WBS TECHNICAL SUPPORT · Dec 11, 2009|42_

> I am wondering if anybody here knows of a mod to convert my Ward Beck Line level Distributions Amps into something I might be able to use. I have 30 M605A (10 per rack x 3 racks) and 12 M8205 in a D8212 rack with no use for them. If I could convert them into quiet clean mic splitters I would keep them. Otherwise they're looking for a good home. Trades for mics, preamps welcome.
> Thanks
> Kevin

— **groovin grove**, Dec 11, 2009|42

> Hello.
>
> Their uses are MANY!! I use an older variant as a headphone distribution system. Works well in the studio and for location recording.
>
> They can not really handle microphone level signals - you can use the resistor network on the back section as a concept to split mic signals - I do that all the time - sending 1 microphone to 4 or 5 destinations.

— **warrenbeck**, Dec 11, 2009|42

> you know, it's sad to say but distribution amplifier systems do not have really high resale value there is not much call for them in today's market and todays broadcast designs do not use them as they once did. that being said some guys rebuild or re-purpose them into small power supplies and headphone distribution systems. The M605A have 115V in and two voltage rails +/-32V and +/- 18V so you could power a few modules with one. 
>
> As a mic splitter... The impedance is 600ohm... but it's meant to be a line level splitter. Also there would be no way of applying phantom power... 
>
> but what are they worth? $10 per rack tray then they cost $30 to ship...

— **kuzub**, Dec 11, 2009|42

> Could you send more info on using the resistor network on the back section for a mic splitter? That is what I'm wanting to do...only if it would be clean and quiet. I don't need phantom power. Thanks Kevin

— **groovin grove**, Dec 15, 2009|42

> Hi.
>
> What is your address and I will mail you out a few little boards.
>
> However the impedance is for 600 ohms, line level. You would have to change the transformer - like a DI for a guitar in to a console.
>
> Regards,

— **warrenbeck**, Dec 16, 2009|42

> I thought I'd add my own little rant here... I apologize, because I'm on Pint #3. =)
>
> All my information here is based on the available M605 manual.
>
> I'd like to point out page 16;
> "On some units u2 will be a TL071CP......"
> I knew they were great and cheap little opamps!
> ^_^!!!
>
> Onto the main topic though:
> Phantom power can-not be easily applied; There are diodes on the input protecting the input...
> Anything above or below +32.7 and -32.7 volts will be drained away from the amp....
> (CR 1, 2, 3 and 4.)
> Remove these diodes, and applying phantom power as normal should work.
> (Through 6.8K resistors.)
>
> I'm lost as-to why the DA calls for a source impedance of 600 ohms... It has a higher-impedance input! (above 30K!)
> Somewhat irrelevant, but never-the-less misleading.
>
> You can hook a microphone right up to it, and buffer/split the mic signal... sure.... it'll work!
> But your noise will be retardantly high!
> (I made that word up... but you get my point!)
>
> If you configure your M605's to have a gain of 1, or unity, it's Signal-to-Noise ratio should be close too 
> "85dB below +8dB."(Page 5)
> +8 minus 85 = -77 dB.
>
> This means that with nothing connected to the input, you will have -77 dB of noise... hiss, buzz, hum, klunk-klunk, meows or tsssst's... doesn't matter... its noise.
>
> Let's say for assumption purposes, that your microphone has an output of -40 dB.
> Sending it through the M605 configured for unity gain will give you your -40dB of microphone signal;
> and it will give you -77dB of noise.
>
> When you send the split signal through a Preamp, and amplify it by let's say 40dB; your microphone level will now be 0dB... but your noise will be at -37dB.
>
> Open up your favorite audio software; and generate a sine-wave, or pink or white noise, with a volume of -37 dB. Play it, and determine how loud it is for yourself.
>
> In my technical opinion, this is a very noisy way to split a microphone signal....
> It will work, but it will be noisy!
> Any preamp you connect this signal to will have a limited Signal-To-Noise ratio of 37 dB.
> Both the M470 and M460 claim to have a ratio of 125 dB!
> That is a HUGE difference!
>
> Your best solution, would be to send your microphone through one Preamp.
> And then send this preamp-output into the M605's.
> If you really want several Mic-Level outputs, you can send the outputs of the M605 through 30-60 dB PADS.
> This will do the best to keep your noise level down.
>
> Other than that, they look like great little units!
> Very basic, but I think they just look so cute! all small, and narrow and such... Makes me want a rack of them!
> I don't have anything to trade you, but let me know what you'd be looking for in the way of cash... and I might consider getting a rack. =)

— **Tristan.Miller**, Dec 18, 2009|42

> well Put Ritz
>
> The less noisy way of splitting a microphone is with a simple passive split... if there were a transformer in the picture it would all change.
>
> Like I said... from a modern use (other than line level splitter) M605s make Great power supply... that is all

— **kuzub**, Dec 18, 2009|42

> Hello.
>
> Well there you go a rather lengthy statement from a fellow enthusiast. HOWEVER if you want to experiment, and learn I will send you some genuine WBS splitter boards. 
>
> I hope you enjoy your experiment Kevin, and I wish you luck.

— **warrenbeck**, Dec 18, 2009|42

> SWEET!!!
> I'm at 
> 2316 6th Ave
> Fort Worth, TX USA
> 76110
> Thanks Warren

— **groovin grove**, Dec 30, 2009|42

> Hello..
> Finally it has been done.
> Dad and I were talking about this the other month actually. Easily doable with a resistor network - non transformer required. Start with what I am sending you (4 boards) and go from there.

— **warrenbeck**, Jan 17, 2010|43

> Hey guy.
>
> I was looking for something else and I found this for you (like Tony had mentioned);
> http://www.jensen-transformers.com/mic_sp.html

— **warrenbeck**, Jan 18, 2010|43

## M605A, D8212 with 12 M8205 cards

_WBS PARTS FOR SALE · Dec 11, 2009|42_

> Hello,
> If I can't find a mod to convert these Das into mic splitters, I would be looking for a trade for mics or preamps. I have 30 of the M605A Das with 10 per rack (3 racks). I have 12 M8205 Das mounted in a D8212.
> Thanks
> Kevin

— **groovin grove**, Dec 11, 2009|42

> let me know if they don't sell, I'll still offer you what I did in the email a few weeks ago
>
> be well

— **kuzub**, Dec 11, 2009|42

## M605A modules

_WBS PARTS FOR SALE · Dec 22, 2009|42_

> Hello TEAM!!!
>
> I have ten (10) units of raw M605A modules for sale. They were former CBC Montreal units, and are of 1985 vintage. Tony has very recently discussed them here a couple of weeks ago if I recall. They do NOT require a power-supply, you plug them directly in to the wall, and you feed them a mono line signal, and get an attenuated line signal out (well several actually if you want - it is a DA after all!!). 
>
> Uses in the modern studio;
>
> I use a few as headphone distribution amplifyers
>
> Buy 2 units, remove all the metalwork and re-house them - giving you a lovely, CLEAN analogue path for your digital mixes. You can trim the signal with the supplied pot, and match your levels exactly. This will help you achieve an out-of-the-box sound for your mixes.
>
> Good for taking un-balanced equipment and balancing them with a little line level adjustment to compensate for any level loss (keyboards, other non-pro equipment or un-balanced equipment).
>
> So give it some thought. They are just the working, raw modules. I advise re-mounting them in your own chassis - as I do not have any spare MF6 frames, nor connectors for them.
>
> $5.00 each + shipping of your choice.
>
> Regards,

— **warrenbeck**, Dec 22, 2009|42

> Don't forget the use as a power supply... 110V in 18V? out

— **kuzub**, Dec 22, 2009|42

> Hi.
>
> Well I use power-supplies as power-supplies, but you had mentioned that earlier. Hmmmm you can power API stuff, and your guitar pedals with one of these suckers.
>
> Multi-use $5 bricks!!
>
> Regards,

— **warrenbeck**, Dec 22, 2009|42

> I'll take them. =)
>
> But I'd like a rack for them.... anyone have one kicking around? .... Tony?.... I'll ship you a couple power-supplies for x-mas... if you can ship me a rack? =)

— **Tristan.Miller**, Dec 23, 2009|42

> Hello.
>
> Do you want to collect them or should I ship them to you??
>
> Regards,

— **warrenbeck**, Dec 26, 2009|42

## Test applications

_WBS EQUIPMENT APPLICATIONS · Feb 1, 2011|44_

> Hello.
> Just a little word of how to use some easily obtained bits to make a very high quality but relatively in-expensive test bench from old WBS bits. 
> Take an MF6 frame (the frame that holds power-supplies, DA's, etc..) and bolt that to the underside of your work-bench. Install an M648, and an M625B, and lastly a lonely M605A. The M605A is basically a 1 watt audio DA, that when you in series gang the various out-puts together can give you more than enough juice to power an audio speaker to give you feed-back on your repair project. Anthony and I have a few blank for MF6 frames - in a blank put a female connector for your +-25v, +48v, and a couple of long-frame jacks (or what ever jacks you want to use to get audio in/out of the M605A). Lastly an M405 series extended range VU meter (not the one with the black PPM, but the beige VU meter). All with 1 speaker, 2 volt meters and a tone generator you are basically set. The tone generator can be a WBS unit, or something from your local electronic shoppe - as long as it gives you 20 - 20K in frequency generation you are fine. Don't really worry about the different sine waves produced - just worry about the response of the unit - 20 hz - 20000 hz.
>
> A variac would be a good idea, to slowly ramp up the voltages to the modules - but if you are 100% certain that they function - then the variac is not needed. 
>
> With the WBS manuals Dad was very particular in providing calibration information, and voltages at various spots to trouble shoot the devices. Remove all the daughter boards, fire up the module, and measure the various points as per the manuals. Once you have determined that the basic module works fine, then you can power down, and introduce 1 daughter board at a time. Put in 1 board, power up, and teat its voltages, power down and add a board, etc... Yeah it is a long process BUT that is how we did it, and it almost guarantees you that no daughter boards will be damaged as you are introducing them 1 at a time and checking all voltages. Once all daughter boards are in place, voltages are happy as per the manual, then apply audio from the tone generator start around 1000 hz - or what ever you like. Watch it through the M405, and then listen to it through the M605A. 
>
> Tweak where necessary. If voltages are off, trace from that point back to another point where the voltage is listed, and thus determine in which chain of components the voltage irregularity resides. This is where real trouble shooting and skill comes in to play.
>
> You do not really need a distortion analyzer nor an oscilloscope. They are very nice to have. There are some great ones for the PC that attach via usb (I recommend building a break-out box for these devices with a little attenuator as they tend to see too much signal.
>
> This basic set-up is all you need to calibrate noise gates, compressors, check daughter boards for noise, and functionality. Use with caution, and if you have never done this sort of thing ask lots of questions (none are dumb/stupid) before you start.
>
> I have this exact same configuration in my studio. I use it for Ward Beck equipment and equipment from various American and European vintage manufacturers as well. For the hard stuff I steal a scope from down the hall or I visit Dad!!
>
> Good luck!

— **warrenbeck**, Feb 1, 2011|44

## Restoration of a Pre-L serie console from Radio Canada

_WBS TECHNICAL SUPPORT · Oct 21, 2011|44_

> If i could like this comment i would. 
>
> Merci c'est vraiment apprécié.
>
> Je suis présentement en train de faire les chemins avec un Buzz Box afin de faire des tableaux de "routing" pour comprendre la topologie de la console. Jusqu'à maintenant j'ai terminé ce qui part des M605A jusqu'aux TB1-2-3-4-5-6. Très formatif comme exercice. Ça permet de visualiser le tout. 
>
> Ce soir je débute les liens entre les "Input modules" et leurs chemins jusqu'aux TB.
>
> Merci pour l'aide.

— **pawajari**, Oct 23, 2011|44

_Example.jpg_
_not kept: the file is not in the forum backups_

_ADC Cleaned 2.jpg_
_not kept: the file is not in the forum backups_
