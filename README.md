# KeebAgn (KeebAgain)
I am making a new split keyboard! It is based on the [last one I made](github.com/asmund20/keyboard_journey). This time, it will feature a case, use Choc v2 switches and have a modified thumb cluster, as well as a full column on the outside.

It has the six by three main matrix and three thumb keys, like the Corne.

I have now ordered the pcb, which can be done by uploading the gerber.zip to a pcb prototype manufacturer. I have not recieved it yet, so nothing is tested.

## Clone
To include the footprints from [ceoloide/ergogen-footprints](https://github.com/ceoloide/ergogen-footprints/tree/603afdc17dda267d4daffe45121c907b77b4d2de), clone with
```
git clone --recursive git@github.com:asmund20/KeebAgn.git
```

## This is a work in progress, do not assume that it works

## Missing footprint in the Ergogen config
Unfortunately, I could not include the footprint for the reset button, referenced as _SW_B3U-1000P_ in the ergogen config due to the licensing of the footprint I used. There are footprints for other reset buttons readily available for Ergogen, but I wanted to use the ones I already have. I was able to download a KiCad footprint for the part and used [Thunderbird2086/ergogen-footprint-generator](https://github.com/Thunderbird2086/ergogen-footprint-generator) to easily generate it, which you can do yourself if you want.

## Thanks to
This project would not be possible without
- MrZealot and the good people maintaining [ergogen](https://github.com/ergogen/ergogen)
- Ceoloide and the contributors at [ceoloide/ergogen-footprints](https://github.com/ceoloide/ergogen-footprints/tree/603afdc17dda267d4daffe45121c907b77b4d2de)
- Thunderbird2086 for [Thunderbird2086/ergogen-footprint-generator](https://github.com/Thunderbird2086/ergogen-footprint-generator)
- And finally mr [Ben Vallack](https://github.com/benvallack) for making me interested in creating keyboards in the first place
