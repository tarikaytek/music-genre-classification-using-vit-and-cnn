# music-genre-classification-using-vit-and-cnn
Comparison of Vision Transformers and Convolutional Neural Networks with different hyperparameters on the task of music genre classification

## Target
In this project, I built Vision Transformers and Convolutional Neural Network models from scratch, trained them on a musical data, and compared the results after. The main target was to see differences how Vision Transformer models would work on digital signal data and compare it to CNN which is classical in the field. Another most beneficial target was to gain hands-on experience on building ViT and CNN architectures from scratch.

## Dataset
We used GTZAN dataset for our task which is classical in the field of musical research with digital signal processing. 
It can be reached from the link: [GTZAN Dataset, Kaggle Link](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification)

## Code Structure 
Project is done using Jupyter Notebook Files. 3 different notebooks are used for; preparing data, building CNNs, building ViTs. All notebooks has detailed step by step comments. Here is brief description:

- **spectrogram_extraction:** This is the notebook where the dataset is prepared. 
Mel and STFT spectrograms are extracted as features using Librosa library for digital signal processing.
After extracting features, all tracks are foldered by their genres for classification.

- **cnn_model_comparison.ipynb:** Notebook that CNN architectures are built, trainings and comparisons are done. 

- **vit_model_comparison.ipynb:**
Notebook that ViT architectures are built, trainings and comparisons are done. 

- **paper.pdf:** 
paper of the work, comparison results can be seen here. 