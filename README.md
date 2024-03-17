
# Human Face detection

Face detection has been growing rapidly during the past few years. This model uses Haar Cascades of OpenCV to detect the face of fve famous celebrities of Pakistan. The celebrities include Atif Aslam, Iqra Aziz, Mahira Khan, Sajal Aly and Humayun Saeed. The dataset is created by downloading the images from the Google using the Fatkun Google Extension to download images in batches.

## Technologies 
The **Human face Detection Project** follows a step-by-step procedure to build an efficient model to predict human faces. The dataset is cleaned, visualized, augmented and predicted in a proper way. The following technologies are used to make the project possible:

- **Python**
- **Numpy and Pandas for data cleaning**
- **Matplotlib for data visualization**
- **Sklearn for model building**
- **Jupyter notebook and visual studio code as IDE**

The **Pakistan_Celebrity_Classification.ipynb** implements various Algorithms on the data. These Algorithms include:

- **LogisticRegression**
- **SupportVectorMachine**
- **SupportVectorClassifier**
- **RandomForest**

After comparing the result of all these algorithms, **SupportVectorClassifier** seems to be the most suitable Algorithm. The **SupportVectorClassifier** underfitted at first, So we performed Data Augmentation on the data. The accuracy of our testing  model is **87.7%**.

The **Prediction.ipynb** imports the saved model and makes prediction on the given Image. The image is given by specifying its path.

## Deployment

To use the project, run the following command in the folder where you want to get the project.

```bash
  https://github.com/anamfatima1304/Weather-Prediction-Model.git
```
Now play around with the model and enjoy.

## Installation

To run this project, you should have python istalled on your computer. You might also need an IDE like VSCode or Jupyter Notebook that could run the code. Also install the following packages

```bash
  pip install pandas
  pip install numpy
  pip install seaborn
  pip install sklearn
  pip install matplotlib
  pip install os
  pip install pickle
  pip install opencv
```
## Contributing

Contributions are always welcome!

Find out an Error or give any suggestion to improve the project.

If you want to add any new features, make a pull request.

ThankYou for your attention.
