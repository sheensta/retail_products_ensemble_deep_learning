# retail_products_ensemble_deep_learning

This project uses both image data and text descriptions of retail products to classify them among 21 different retail types. The image data was obtained from [Kaggle](https://www.kaggle.com/c/retail-products-classification/data). Both classical machine learning and deep learning were applied. Model performance was evaluated by mean F1 score. The F1 score was 0.76 on when performed on an unlabeled test set. 

I've uploaded the code I used to clean the data and train models with, as well as train/test CSV files containing products, their description, and labels.  

Please read the [report](https://github.com/sheensta/retail_products_ensemble_deep_learning/blob/be521c617597f6511ad7c6cb83e77b5efbcaddf7/Sean_Zhang_Retail_products_MLreport_ACM.pdf) for more details!

Description of notebooks:

1) Image_conversion.ipynb: Converting images to array format
2) NLP Exploratory analysis: Exploratory analysis for text data
3) Training Image Models: select training for image models
4) NLP_Feature_Extraction: feature extraction and training for text models
5) Final_model_evaluations: calculating accuracy metrics for all models, including ensemble modeling
6) Training on full dataset: training models on full dataset for predicting unlabeled Kaggle test set
7) Predicting test dataset: predicting on the final Kaggle dataset
