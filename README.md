# In-Ear Gems Frequency Response Target

Frequency response plays a significant role in the sound quality and characteristics of in-ear monitors (IEMs), including stereo imaging (a.k.a., soundstage width, depth, and layering). This repository contains my *preference* frequency response target. It was developed to achieve the following criteria: 

- Spacious stereo imaging: sound is pushed back to form a bubble or a dome around the head rather than a flat plane inside the head, between two ears.
- Layering: sound is layered from closer to further away rather than making every elements of the mix fuzzy and distant.
- Comfort: smooth sound signature that allows listening for hours without fatigue, useful for sleeping or working.
- Realistic rendering of low-frequency acoustic instruments.

## In-Ear Gems Target

![/Target/IEGems_V1/target.png]

The curve has been developed based on elements from different IEMs that provides different aspects of the described criteria:
- 64 Audio U12t: natural, comfortable rendering of midrange, 3D soundstage illusion
- 64 Audio TIA Trio: 3D soundstage illusion, exaggerated depth
- Final Audio E5000: realistic low-frequency instruments, layering, smooth and comfortable sound
- Campfire Audio Andromeda 2020: layering, 3D soundstage illusion, smooth and comfortable sound
- Dunu SA6: smooth and comfortable sound, handling of sibilance

Comparisons:
![Target/IEGems_V1/vs-u12t.png]
![Target/IEGems_V1/vs-trio.png]
![Target/IEGems_V1/vs-sa6.png]
![Target/IEGems_V1/vs-e5000.png]

## EQ Profiles

The `EQ profiles/IEGems_V1/` folder contains **parametric EQ** profiles generated by AutoEQ to EQ some well-known IEMs to match the IEGems target. The measurements used for generating these profiles are from Crinacle via the graph comparison tool. 

You can import the `.txt` file into most PEQ apps. I personally use Poweramp EQ app on Android. Wavelet app should also be able to load these profiles. 

Refer to [usage instructions of AutoEQ](https://github.com/jaakkopasanen/AutoEq#usage) for more details. 

**Noted that you might need to increase volume after EQ, as I set negative preamp very high just in case you want to do more EQ after applying my profiles**
