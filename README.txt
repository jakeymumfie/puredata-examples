Jakey Mumfie PureData code examples. 

Contents:


1 - PureData Vanilla
    Pd Patches created during Fall of 2017. Open with Pd-0.48-0-i386 or later. 

	1.1 - Mumfie_Spatializer
	      2D movement system using WASD and spatialized audio sources. Turn up the volume slider, press the toggle, and use WASD in tank controls. Works best with headphones. 
              _Spatializer_Crickets.pd and _Spatializer_Tonal.pd are same systems with different audio sources. They are laid out in a procedurally generated line in 2D space that ranges in tonality. If the audio is broken and bursts into white noise, go into the Audio Sources subpatch and spam the bang at the top a couple of times to process the positioning.
              NOTE: key input is broken in newer versions of MacOS. Use the coolplayers to automate movement.

	1.2 - Mumfie_LightweightSampleLooper
	      sample perfect looper with start, end on next loop, and stop buttons. Includes a loop from “Dream 106” by Jean Jacques Perrey and Luke Vibert from the Album “Moog Acid”.

2 - Heavy Patches - Protocol Aurora
    Pd Patches created during the Spring of 2018 for use in “Protocol Aurora” using Heavy from Enzien Audio. Use Pd-0.48-0-i386 or later. 
	2.1 - Mumfie_NoiseWaveGenerator
	      Random length and frequency bandpassed white noise ramp generator used as wind source in Protocol Aurora. Parameterization of bandpass values set up to allow modification into other types of noise (i.e. waves) in middleware instead of by creating a new patch.

	2.2 - ProtocolAurora_ProcGen_Beam
	      Phased noise generator used as main texture within Beam weapon.

	2.3 - ProtocolAurora_ProcGen_Star
	      Combination and modification of Jet Engine and Creaking examples from Andy Farnell’s “Designing Sound”, with parameterized charge up controlled from game engine.

3 - PureData Extended
    Pd Patches created during the Fall of 2016. Use Pd-Extended to open.

	3.1 - Self Playing Songs
	      To play each of these, turn the volume up in the ezoutput~ object and press the button labeled “start”. 

		3.1.1 - Mumfie_Snipsterpiece
			Includes samples from “Rabbit At The Airport I” by Martin Stig Andersen, which is modulated as the background texture. Clang and bang samples were recorded by me, and the bulk of the song is made up of a single recording of scissors. I have tried to go back through and figure out what is happening in the logic core at the middle of this patch several times and I’m just as lost as you. 

		3.1.2 - Mumfie_MuesliConchFeet
			Includes a sample from “Red Beans” by Professor Longhair from the album “Crawfish Fiesta”. Attempt at musique concrete style, and the title is an attempt at a pun on musique concrete.

		3.1.3 - Mumfie_Symphony
			My first self playing song, using all synthesized tones and a hOrSeY sUrPrIsE. Based on the principal of having a lot of the same tone generator with randomly selected tones and tempos. Like most generative songs, sometimes it sounds good and sometimes it doesn’t.

	3.2 - Random Sounds
	      These are both basically harsh noise generators, listen at your own risk
		3.2.1 - Mumfie_Ziggurat
			Very early in my time with PureData. Use the… ahem… “fuck it up” toggle to make it more interesting. 
		3.2.3 - Mumfie_LiveElectionCoverage
			harsh noise as self expression to deal with the recent election. Uses the same principal as the horsey surprise.