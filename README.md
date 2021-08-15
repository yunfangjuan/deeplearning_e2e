# Deep Learning End To End

  This repo showcases various deep learning algorithms through real world examples and datasets. Our goal is to help people 
  gain understanding on how to train specific models from data prepartion to evaluation. 

# Installation 
  * Install and run docker on your laptop or on a remote instance
  * Run `docker pull gaarv/jupyter-keras`
  * Under this repo, run  `docker run -d -v /$(pwd)/:/home/jovyan/work  -p 8888:8888 gaarv/jupyter-keras start-notebook.sh --NotebookApp.token=''`
  * Go to localhost:8888 to see the notebooks

# Current E2E Notebooks
  * [Sentiment Analysis with Transformer using IMDB 50K dataset](https://github.com/yunfangjuan/deeplearning_e2e/blob/main/Sentiment_Analysis_with_Transformer.ipynb)
  * [Sentiment Analysis with Pretrained BERT model](https://github.com/yunfangjuan/deeplearning_e2e/blob/main/Sentiment_Analysis_with_Pretrained_Model.ipynb)
