## Emojify
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

![image](https://user-images.githubusercontent.com/68388179/126160562-ac977304-ac34-48fc-8d61-7b519e7e82ef.png)


**Emojis** are the incredible way of expressing yourself.Therefore, our machines should also be aware of the appropriate emoji to be used at the right time. Thus, this project does the same.  
> In this project, the model is predicting emoji(s) according to a given sentence using `Deep Learning` models.

>`Input Sentence: I love u`

> `Output Emoji : I love u ❤️`
### Dataset 
Text data consiting of different sentences along with the labels. Labels represent a particular emoji representing the sentence. 
>I have used data from **data** directory for training and test perspective.


### Algorithm Used 
LSTM

> **Emojify.ipynb** :  This python script contains the code for both the models and their predictions.   



### Additional Files
In this project, I have used the `6B 50D glove vector` to build `embedding matrix` of words available in the glove vector.<br>
>Download the 6B.50.50d.txt file and extract the file in the same directory as that of the code.<br> Link-> [glove.6B.50D.txt](https://www.kaggle.com/watts2/glove6b50dtxt)
