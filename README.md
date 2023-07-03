# OCR

> Author: Maxime Wattez<br/>
> Last Update: 4 July 2023

This is a small OCR (Optical Character Recognition) API that I built to try to convert images into text.<br/>
It allowed me to play with Tesseract.

## Installation

### Dependencies

This project depends on [Tesseract](https://tesseract-ocr.github.io/).
```bash
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
```

### Python requirements

```bash
pip install -r requirements.txt
```

## Execute

```bash
uvicorn main:app --reload
```

Go to [localhost:8000/docs](localhost:8000/docs) and upload a picture with text.<br/>
==> This should return the text present in the image.
