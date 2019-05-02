# austen-embedding Readme
A word2vec embedding of Jane Austen works. 

<a href="https://colab.research.google.com/github/fmcooper/austen-embedding/blob/master/austen-embedding.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

******************************

1) Program use
2) Google Drive access

******************************

## 1) Program use

You will need to have a Google account to access colab. If you have never used colab before take a look <a href="https://colab.research.google.com/notebooks/welcome.ipynb">here</a>. After this, simply click on the following button to open this program in a new colab instance: 
<a href="https://colab.research.google.com/github/fmcooper/austen-embedding/blob/master/austen-embedding.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


## 2) Google Drive access

In order to save the model both during and after training, this program will ask you for google drive access. 

```
from google.colab import drive
drive.mount('/content/gdrive')
```

Please edit this line:

```
DATA_PATHS = ['/content/gdrive/My Drive/Colab/austen-embedding/data/austen-emma-754.txt', \
             '/content/gdrive/My Drive/Colab/austen-embedding/data/austen-northanger-755.txt', \
             '/content/gdrive/My Drive/Colab/austen-embedding/data/austen-persuasion-756.txt', \
             '/content/gdrive/My Drive/Colab/austen-embedding/data/austen-pride-757.txt', \
             '/content/gdrive/My Drive/Colab/austen-embedding/data/austen-sense-758.txt']
```

To point at the data provided in this repository.
