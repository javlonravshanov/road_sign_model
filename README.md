# Road Sign Classification Using Deep Learning

## Introduction
This repository contains the code and resources for a deep learning project aimed at classifying road signs in Poland. The dataset used in this project includes approximately 32,000 images across 46 different classes of road signs. The model developed achieved an impressive accuracy of 99.7%.

## Dataset
- Data Source: A custom dataset was created to meet the specific requirements of this project. Initially, the "German Traffic Sign Recognition Benchmark" from Kaggle was considered, but it was found to be insufficient for the project's needs.

- Dataset Preparation: The images were manually collected, organized, and renamed using the "Bulk Rename Utility" software. The dataset was then compressed into a .zip file and uploaded to Google Drive for easier access.
## Project Structure
- Data Preparation: The notebook includes steps to download the dataset from Google Drive, extract it, and prepare it for training.
- Model Training: Utilizes the fastai library and PyTorch to train the deep learning model on the prepared dataset.
- Evaluation: The trained model is evaluated on a validation set to determine its accuracy and performance.
## How to Use
1.Clone the repository:
```git clone https://github.com/your-username/road_sign_classification.git```
2.Run the notebook:
- Open the notebook in Google Colab or locally in Jupyter Notebook.
- Ensure you have the required dependencies installed (fastai, torch, etc.).
- Run each cell sequentially to train and evaluate the model.
## Results
- The model achieved an accuracy of 99.7% on the validation set, demonstrating its effectiveness in classifying road signs with high precision.
## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or improvements, feel free to submit an issue or pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
