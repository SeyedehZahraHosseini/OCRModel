# OCRModel

is a process run by an OCR software. The software will open a digital image, e.g. a tiff file containing full text characters, and then attempt to read and translate the characters into recognizable full text and save them as a full text file. This is a quick process that enables automated conversion of millions of images into full-text files that can then be searched by word or character.
in detection we have three steps:
gray scaling, remove noise and thresholding

in my case it is better to use word-level detection cause i have recognation step after that.
In Python, many OCR models such as **PyTesseract**, **PPOCR**, **easyOCR**, **MMOCR**, **Keras-OCR**, etc. are available. However one of the major drawbacks of most of the OCR models is that they either have a good detection model or a good recognition model, but not both. Some models are fast in text recognition but are slower in detection.

use **EasyOCR** when  
+Dealing with **handwritten** or **irregularly** placed text  
it supports persian language

use **Tesseract** when  
Processing scanned books, documents with **printed** text
