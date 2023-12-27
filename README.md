## Das Keyboard 4 controller replacement - usb2 only.

I had a mains accident with my [das keyboard](https://www.daskeyboard.com/daskeyboard-4-professional/), and blew out the USB3 hub, the Via xxxxfixmexx part.  
I sourced a replacement, but it never came up, so perhaps it was more broken.

Today, I've had the idea of just making a replacement controller board for it.  They _keys_ are presumably all still fine.

So... Pick a cheap in stock MCU supported by [QMK](https://qmk.fm/), just go for a plain USB2-HS hub part, and.. profit?

## Status
Have designed and ordered a somewhat poorly thought out [r2023-12](hw/r2023-12)  It's not as cheap in assembly and manufacturing as the rest of the design might imply. The hub enumerates and the STM32 works in DFU, so it's promising at least.
Have _not_ yet done any work to actually reverse engineer the matrix layout, or done any work with QMK or other alternatives.

## License
Consider this "open hardware"
(TODO: apply for a OSHW number?)
