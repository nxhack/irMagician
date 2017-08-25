# irMagician

[irMagician](http://www.omiya-giken.com/?page_id=837&lang=en)

## Structure
DAIKIN AC IR command is variant of the AEHA format.

The DAIKIN command is mainly divided into four parts.

1. “bit 0 x 5 times|+ STO BIT | GAP
2. Leader code | DATA (64bit) | STOP BIT | GAP
3. Leader code | DATA (64bit) | STOP BIT | GAP
4. Leader code | DATA (152bit) | STOP BIT | GAP
