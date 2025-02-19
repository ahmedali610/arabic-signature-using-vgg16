# Arabic Signature Verification

This project aims to predict whether an Arabic signature is **real** or **fake** using deep learning techniques. The model processes signature images and classifies them based on authenticity.

## Dataset

- The dataset is sourced from **Kaggle**: [Arabic Signature Data](https://www.kaggle.com/datasets/ahmedemadeldeen/arabic-signature-data).
- Images are stored in the `images/` folder.
- Labels are provided in a CSV or JSON file (if applicable).

### Download Dataset

To download the dataset from Kaggle, use the following command:

```bash
kaggle datasets download ahmedemadeldeen/arabic-signature-data
```

## Project Structure

```
├── images/                     # Folder containing Arabic signature images
├── notebook.ipynb              # Jupyter Notebook with the model and training process
├── model/                      # Saved model (if applicable)
├── README.md                   # Project documentation
```

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/arabic-signature-verification.git
   cd arabic-signature-verification
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## Model Training

- The notebook includes **image preprocessing, model training, and evaluation**.
- A **CNN (Convolutional Neural Network)** is used for signature classification.
- The dataset is split into **training** and **testing** sets.

## Usage

- Run all cells in `notebook.ipynb` to train and evaluate the model.
- Modify the `images/` folder to include your own dataset.
- Adjust hyperparameters in the notebook for better accuracy.

## Results

- The model predicts whether a given Arabic signature is **real** or **fake**.
- Performance metrics like accuracy, precision, recall, and F1-score are used for evaluation.
- Below is a visualization of the training and validation accuracy over epochs:
![download (10)](https://github.com/user-attachments/assets/6758ca78-1554-4982-bc0b-a4b800ea8f83)



- The model predicts whether a given Arabic signature is **real** or **fake**.
- Performance metrics like accuracy, precision, recall, and F1-score are used for evaluation.
- Below is a visualization of the training and validation accuracy over epochs:

  
![download (8)](https://github.com/user-attachments/assets/bead9126-b3da-4434-9334-6fcce572296c)



- The model predicts whether a given Arabic signature is **real** or **fake**.
- Performance metrics like accuracy, precision, recall, and F1-score are used for evaluation.
