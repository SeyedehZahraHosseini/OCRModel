# OCRModel
OCR معمولا از در مرحله تشکیل شده:

**Text Detection:** 

در این مرحله با کشیدن bounding box ها میتونیم متن و جملات و شناسایی کنیم

**Text Recognition:**

تو این مرحله برامون تشخیص کاراکتر مهمه چون داریم محتوای درون باکس هارو میخونیم پس برامون مهمه مدلمون با زبان فارسی آموزش دیده باشه

In Python, many OCR models such as **PyTesseract**, **PPOCR**, **easyOCR**, **MMOCR**, **Keras-OCR**, etc. are available. However one of the major drawbacks of most of the OCR models is that they either have a good detection model or a good recognition model, but not both. Some models are fast in text recognition but are slower in detection.

use **EasyOCR** when  
+Dealing with **handwritten** or **irregularly** placed text  
it supports persian language

use **Tesseract** when  
Processing scanned books, documents with **printed** text
