# images

I am trying to create jpeg file from a eps image. The file fails to open with an error. 

To download, https://github.com/l-dandelion/images/blob/master/EPS/test.eps

Command:
convert test.eps -resize 800x800 tmp.jpg

Error:
convert: insufficient image data in file `test.eps' @ error/ept.c/ReadEPTImage/200.
convert: no images defined `tmp.jpg' @ error/convert.c/ConvertImageCommand/3275.
