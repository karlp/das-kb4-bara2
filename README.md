## Das Keyboard 4 controller replacement - usb2 only.

I had a mains accident with my [das keyboard](https://www.daskeyboard.com/daskeyboard-4-professional/), and blew out the USB3 hub, the Via xxxxfixmexx part.  
I sourced a replacement, but it never came up, so perhaps it was more broken.

Today, I've had the idea of just making a replacement controller board for it.  They _keys_ are presumably all still fine.

So... Pick a cheap in stock MCU supported by [QMK](https://qmk.fm/), just go for a plain USB2-HS hub part, and.. profit?

## Status
[Have a working version](h2/r2023-12), though the layout was somewhat poorly thought out. It's not as cheap in assembly and manufacturing as the rest of the design might imply.

## TODO
 * Make a cheaper version, with better mechanical fit.
 * apply for a OSHW number?)

## License
Consider this "open hardware"
