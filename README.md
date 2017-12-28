# LTZ1000 info

A collection of what I've learned about the LTZ1000, mostly from the epic thread on the EEVBlog forum: [Ultra Precision Reference LTZ1000](http://www.eevblog.com/forum/metrology/ultra-precision-reference-ltz1000/).

# Relative importance of R1-R5

From the [datasheet](/media/LTZ1000.pdf):

![](/media/datasheet-resistors-impact.png)

Here's the same data, but stated as "relative impact":

![](/media/resistors-table-1.png)

That is, if R1 changes in value, 1% of that change will show up on the output voltage (if R1 changes by 100ppm, the output voltage will change by 1ppm).

However, members of the community have measured different results:

![](/media/resistors-table-2.png)

Here's the same data, but expressed as the importance of each resistor relative to the importance of the R4/R5 ratio (i.e. the data is normalized against R4/R5).  E.g. according to zlymex, drift in R1 is only 15% as important as the drift in R4/R5.

![](/media/resistors-table-3.png)

References:
- [Andreas links](https://www.eevblog.com/forum/metrology/resistor-set-for-ltz1000-positive-standard-7v-circuit/)
- [zlymex results](https://www.febo.com/pipermail/volt-nuts/2011-October/001299.html)
- [janaf results](https://www.eevblog.com/forum/metrology/ultra-precision-reference-ltz1000/msg439908/#msg439908)
- [Andreas results](https://www.eevblog.com/forum/metrology/ultra-precision-reference-ltz1000/msg833226/#msg833226)
- [lars results](https://www.eevblog.com/forum/metrology/ultra-precision-reference-ltz1000/msg656529/#msg656529)
