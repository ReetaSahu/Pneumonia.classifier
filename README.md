#Pneumonia Detection Using ResNet-50

This project fine-tunes a pre-trained ResNet-50 model to classify chest X-ray images as **Normal** or **Pneumonia**, using the **PneumoniaMNIST** dataset.

## Project Structure

- `pneumonia_resnet50.py` — Training and evaluation script
- `requirements.txt` — Python package dependencies
- `hyperparameters.txt` — Notes on learning rate, batch size, etc.


## How to Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the model script
python pneumonia_resnet50.py
