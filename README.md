## Requirements

`sudo apt-get install python-imaging` <<also called Pillow
	Python Imaging Library is a free library for the Python programming language that adds support for opening, manipulating, and saving man
different image file formats. It is available for Windows, Mac OS X and Linux.

`sudo apt-get install tesseract-ocr`
Tesseract is an optical character recognition engine for various operating systems. It is free software, released under the Apache License, 
Version 2.0, and development has been sponsored by Google since 2006. In 2006, Tesseract was considered one of the most accurate open-source 
OCR engines then available

`sudo apt-get install python-opencv`
OpenCV. ... Right now, OpenCV supports a lot of algorithms related to Computer Vision and Machine Learning and it is expanding day-by-day. 
Currently OpenCV supports a wide variety of programming languages like C++, Python, Java etc and is available on different platforms 
including Windows, Linux, OS X, Android, iOS etc.

## Example

Library Requirements:
1. tesseract-ocr
2. tesseract
3. matplotlib
4. Image
5. Pillow || pillow
6. OpenCV

1. First process the image

`python process_image.py test.jpg output.jpg`

2. Extract text

`python extract_text.py`

Output:

```bash
4 WkiJre €99 Bread

A good, basic white bread.

with

I. 21/2 cups lukewarm water
2 packages dry yeast
1/4 cup honey
1 cup dry mile
2 eggs, beaten
4 cups unbleached white ﬂour

II. 4 teaspoons salt
1/3 cup butter or margarine
3 caps or inore unbleached white ﬂour for forming the dough
1 cup (approx.) white ﬂour for kneadian

Proceed with the directions for recipe #1, adding the beaten eggs afte
stirring in the dry milk.



is moister and chewier than the white e ;g bread.

r’/
'3. ' " er
ast
J
V -

```
