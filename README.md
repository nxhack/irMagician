# DIKIN AC command for irMagician

[irMagician](http://www.omiya-giken.com/?page_id=837&lang=en)

## Structure
DAIKIN AC IR command is variant of the AEHA format (Bi–phase coding).

The DAIKIN command is divided into four parts.

1. [BIT-0 x 5 times](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L6-L10) | [STOP | GAP](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L11)
2. [Leader code](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L12) | [DATA (64 bit)](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L13-L76) | [STOP | GAP](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L77)
3. [Leader code](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L78) | [DATA (64 bit)](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L79-L142) | [STOP | GAP](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L143)
4. [Leader code](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L144) | [DATA (152 bit)](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L145-L296) | [STOP](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L297)

## Link

[IR Daikin: decodificare protocolli infrarossi complessi. | McMajan](http://www.mcmajan.com/mcmajanwpr/blog/2013/10/21/ir-daikin-decodificare-protocolli-infrarossi-complessi/)

[Daikin-IR-Reverse: Daikin AC Infrared remote control protocol reverse](https://github.com/blafois/Daikin-IR-Reverse)
