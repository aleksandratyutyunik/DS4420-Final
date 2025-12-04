# NLP Classification Tasks
This project preforms two differnt kinds of classification tasks on language based data. The first task is a Bayesian model for the prediction of an author based on a quote. The second one is the classification of language based on a handwritten word.

## Bayesian
All the work for the Bayesian model is done in the `writer_quotes.ipynb` file. Make sure the following libraries are installed:
```
pip install kagglehub
pip install numpy
pip install pandas
pip install Pillow
pip install scikit-learn
pip install matplotlib
```



## CNN
#### Preprocessing
The preprocessing is done in the `Handwriting-Data-Preprocessing.ipynb` file. Make sure the following libraries are installed:
```
pip install kagglehub
pip install numpy
pip install pandas
pip install Pillow
pip install scikit-learn
pip install matplotlib
```
This file will import the data and download it so it can be used in R. **Run this file first.**

#### Model
The CNN is done in R using Torch. This is done in the `CNN-Final-Project.Rmd` file. Make sure the following libraries are installed:
```
install.packages("torch")
install.packages("torchvision")
install.packages("ggplot2")
```
This file will actually train the model.
