# KeebAgn (KeebAgain)
So the board is noe done. It works nicely! It is based on the [last one I made](github.com/asmund20/keyboard_journey).

It has a six by three main matrix and three thumb keys. It only supports Choc v2
switches.

## Building
You can build it yourself, but check the license first (no guarantee that it
will work). Note that it might not be obvious what parts are needed, so please
ask. For help, you can create an issue here.

The file for the pcb and case can be found in the releases page.

## Clone
To include the footprints from [ceoloide/ergogen-footprints](https://github.com/ceoloide/ergogen-footprints/tree/603afdc17dda267d4daffe45121c907b77b4d2de), clone with
```
git clone --recursive git@github.com:asmund20/KeebAgn.git
```

## Missing footprint in the Ergogen config
Unfortunately, I could not include the footprint for the reset button, referenced as _SW_B3U-1000P_ in the ergogen config due to the licensing of the footprint I used. There are footprints for other reset buttons readily available for Ergogen, but I wanted to use the ones I already have. I was able to download a KiCad footprint for the part and used [Thunderbird2086/ergogen-footprint-generator](https://github.com/Thunderbird2086/ergogen-footprint-generator) to easily generate it, which you can do yourself if you want.

## Thanks to
This project would not be possible without
- MrZealot and the good people maintaining [ergogen](https://github.com/ergogen/ergogen)
- Ceoloide and the contributors at [ceoloide/ergogen-footprints](https://github.com/ceoloide/ergogen-footprints/tree/603afdc17dda267d4daffe45121c907b77b4d2de)
- Thunderbird2086 for [Thunderbird2086/ergogen-footprint-generator](https://github.com/Thunderbird2086/ergogen-footprint-generator)
- And finally mr [Ben Vallack](https://github.com/benvallack) for making me interested in creating keyboards in the first place
