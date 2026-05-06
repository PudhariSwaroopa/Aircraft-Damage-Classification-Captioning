#  Aircraft Damage Classification and Captioning using Deep Learning

This project uses Deep Learning and Pretrained Models to classify aircraft damage and generate captions/summaries for aircraft images.
Deep learning project for aircraft damage classification (dent/crack) using VGG16 transfer learning and image captioning using the BLIP pretrained transformer model.

---

## Project Overview

The project consists of two major tasks:

###  Aircraft Damage Classification

A transfer learning approach using the pretrained **VGG16** convolutional neural network is used to classify aircraft damage into:

* Dent
* Crack

###  Image Captioning and Summarization

The pretrained **BLIP (Bootstrapping Language-Image Pretraining)** transformer model is used to generate:

* Image captions
* Image summaries

---

##  Technologies Used

* Python
* TensorFlow / Keras
* PyTorch
* HuggingFace Transformers
* VGG16
* BLIP
* NumPy
* Matplotlib
* Pillow

---

##  Dataset

Dataset used:
Aircraft Damage Dataset

The dataset is automatically downloaded in the notebook using:

```python
urllib.request.urlretrieve(url, tar_filename)
```

---

##  Features

* Transfer Learning with VGG16
* Binary Image Classification
* Accuracy and Loss Visualization
* Test Image Prediction Visualization
* Automatic Caption Generation
* Automatic Image Summarization

---

##  Model Workflow

### Classification Pipeline

1. Data preprocessing
2. Image augmentation and normalization
3. Load pretrained VGG16
4. Freeze base layers
5. Add custom dense layers
6. Train and validate model
7. Evaluate on test dataset

### Captioning Pipeline

1. Load pretrained BLIP model
2. Process aircraft image
3. Generate captions
4. Generate summaries

---

##  How to Run

###  Clone the repository

```bash
git clone https://github.com/your-username/aircraft-damage-classification-captioning.git
```

###  Install dependencies

```bash
pip install -r requirements.txt
```

###  Run the notebook

Open the Jupyter notebook and run all cells.

---

##  Sample Outputs

* Aircraft damage classification
* Confusion matrix
* Accuracy curves
* Generated image captions
* Generated image summaries

---

##  Future Improvements

* Use advanced architectures like EfficientNet or ResNet
* Improve caption quality with larger vision-language models
* Deploy as a web application
* Add real-time aircraft inspection support

---

##  Author

Swaroopa
