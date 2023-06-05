# Text-to-Braille-Converter
Text to Braille with OCR 

### requirements
make sure to install the following before running: --> better on a virtual environment
1. [python](https://www.python.org/downloads/windows/)
2. [tesseract](https://github.com/UB-Mannheim/tesseract/wiki) and add it to your environment variables
3. numpy ```pip install numpy```
4. PIL ```pip install PIL```
5. cv2 ```pip install opencv-python```
6. download the trained datasets used below and make sure to place it inside the **tessdata** folder of the tesseract ocr installation location.
    - [traditional chinese](https://github.com/tesseract-ocr/tessdata/blob/main/chi_tra.traineddata)
    - [vertical traditional chinese](https://github.com/tesseract-ocr/tessdata/blob/main/chi_tra_vert.traineddata)
7. django ```pip install django```
7. pytesseract ```pip install pytesseract```

### ocr
languages recognized:
[x] english
[x] traditional chinese 
[x] combinition of chinese and english

**note:** the images tested in this project are carefully chosen since the ocr still needs further modification

### text to braille
there are (2) two choices to test braille:
1. get the text from ocr
2. input text
