## Emojify
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) 
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) 

![image](https://user-images.githubusercontent.com/68388179/126160562-ac977304-ac34-48fc-8d61-7b519e7e82ef.png)


**Emojis** are the incredible way of expressing yourself.Therefore, our machines should also be aware of the appropriate emoji to be used at the right time. Thus, this project does the same.  
> In this project, the model is predicting emoji(s) according to a given sentence using `Deep Learning` models.

>`Input Sentence: I love u`

> `Output Emoji : I love u ❤️`
> 
> **Emojify.ipynb** :  This python script contains the code for both the models and their predictions including summary.

### ` Image 1 :  Baseline model (Emojifier-V1) architecture `
![image](https://github.com/Naaru-01/ML_emojify/assets/68388179/22edf64e-3a5c-4137-b609-5ee4ddb11ac8)

### `Image 2 : A 2-layer LSTM sequence classifier model (Emojifier-V2) architecture | Algorithm Used  : LSTM`
![image](https://github.com/Naaru-01/ML_emojify/assets/68388179/d0047ff2-7b6b-4894-a785-29e686752318)

### Dataset 
Text data consiting of different sentences along with the labels. Labels represent a particular emoji representing the sentence. 
>I have used data from **data** directory for training and test perspective.




  



### Additional Files
In this project, I have used the `6B 50D GloVe vector` to build `embedding matrix` of words available in the GloVe vector.<br>
>Download the 6B.50.50d.txt file and extract the file in the same directory as that of the code.<br> Link-> [glove.6B.50D.txt](https://www.kaggle.com/watts2/glove6b50dtxt)
