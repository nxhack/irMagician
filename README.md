# irMagician

[irMagician](http://www.omiya-giken.com/?page_id=837&lang=en)

## Structure
DAIKIN AC IR command is variant of the AEHA format.

The DAIKIN command is mainly divided into four parts.

1. [BIT-0 x 5 times](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L6-L10) | [STOP | GAP](https://github.com/nxhack/irMagician/blob/master/ac-on.json#L11)
2. Leader code | DATA (64 bit) | STOP | GAP
3. Leader code | DATA (64 bit) | STOP | GAP
4. Leader code | DATA (152 bit) | STOP | GAP
