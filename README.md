# Doom for Linux Frambuffer

This port of the original Doom source code targets Linux Framebuffer, without any intermediate abstraction layer (like SDL).  
Taken from https://github.com/stoffera/fbdoom

This port depends only on *stdlib*.

On @stoffera version there is no implementation of the keyboard, however, I have enabled the Keyboard on this new version and I have tested it on the DE0-NANO-SOC using an  [USB DisplayLink DL-165](https://www.amazon.ca/gp/product/B01AL6IBF8/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1) as a video interface.

I will be soon enabling the audio, so it becomes fully playable.

![Image](https://fpgalover.com/images/doom_on_DE0_NANO_SOC.jpg)
