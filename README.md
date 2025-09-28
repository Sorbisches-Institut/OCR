# Sorbische OCR-Trainingsdaten und Modelle  
# Sorbian OCR Training Data and Models  
# Serbske OCR-treningowe daty a modele  

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)  
[![Build Status](https://img.shields.io/github/actions/workflow/status/Sorbisches-Institut/OCR/ci.yml?branch=main)](https://github.com/Sorbisches-Institut/OCR/actions)  
![Languages](https://img.shields.io/badge/languages-DE%20%7C%20EN%20%7C%20HSB-blue.svg)  
[![Downloads](https://img.shields.io/github/downloads/Sorbisches-Institut/OCR/total.svg)](https://github.com/Sorbisches-Institut/OCR/releases)  


---

This repository provides **recognition models** for the Sorbian languages, supporting both **Latin script** and **Fraktur script**.
It will provide **training data** in the near future.

### Contents
- Pretrained models for different OCR frameworks
- (Training data for creating new OCR models)  

### Current Status
- ✅ Models for **Tesseract** are available  
- ⏳ Models for **Calamari** and **Kraken** will be added soon  

### Upper Sorbian Tesseract Models

This repository provides **Tesseract OCR models for Upper Sorbian**, trained and fine-tuned at the Sorbian Institute.  
Both Latin and Fraktur script variants are available.

---

## 📦 Models

- **hsb2.traineddata**  
  Upper Sorbian (Latin script), **v2**  
  Fine-tuned from the official [Latin.traineddata](https://github.com/tesseract-ocr/tessdata/blob/main/script/Latin.traineddata) (tessdata).  
  Recommended for modern Sorbian texts (printed in Latin script).

- **hsb_frak2.traineddata**  
  Upper Sorbian (Fraktur script), **v2**  
  Fine-tuned from the official [Fraktur.traineddata](https://github.com/tesseract-ocr/tessdata/blob/main/script/Fraktur.traineddata) (tessdata).  
  Recommended for historical Sorbian Fraktur prints.

---

## 🔧 Installation

### System tessdata folder

Copy the models into your Tesseract tessdata directory.

**Linux (Debian/Ubuntu):**
```bash
sudo cp traineddata/*.traineddata /usr/share/tesseract-ocr/4.00/tessdata/
```

## License & Origin

**hsb2 + hsb_frak2 OCR Model** © 2025 [Sorbian Institute] – licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
Based on the official **Tesseract tessdata models Latin and Fraktur**,  
© Google et al., licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).


---
