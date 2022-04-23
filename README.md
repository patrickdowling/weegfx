# weegfx
Minimal-ish graphics code that I seem to reuse too often.

This started as a quick & dirty minimal graphics library for [o_C](https://github.com/patrickdowling/O_C) and then got reused. And reused again for testing different displays. So now I have 1001 versions of the code flying around in multiple projects and might as well do some post-hoc unification.

- Mainly useful for 1bpp displays, e.g. OLEDs using SSD1306 controllers.
- Framebuffer oriented (displays have usually been < 128x64 and while 1K seems reasonable).
- Implements a bunch of `sprintf` style printing functions and overly-specific integer printing.
- Not super optimized but "fast enough".
- No "real" font support (yet) just a 6x8 pixel fixed width bitmap font.
