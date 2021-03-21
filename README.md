# retail_products_ensemble_deep_learning

This project uses both image data and text descriptions of retail products to classify them among 21 different retail types. The image data was obtained from [Kaggle](https://www.kaggle.com/c/retail-products-classification/data). Both classical machine learning and deep learning were applied. Model performance was evaluated by mean F1 score. The F1 score was 0.76 on when performed on an unlabeled test set. 

I've uploaded the code I used to clean the data and train models with, as well as train/test CSV files containing products, their description, and labels.  

Please read the [report](https://github.com/sheensta/retail_products_ensemble_deep_learning/blob/be521c617597f6511ad7c6cb83e77b5efbcaddf7/Sean_Zhang_Retail_products_MLreport_ACM.pdf) for more details!

Description of notebooks:

1) _Image_conversion_: Converting images to array format
2) _NLP Exploratory analysis_: Exploratory analysis for text data
3) _Training Image Models_: select training for image models
4) _NLP_Feature_Extraction_: feature extraction and training for text models
5) _Final_model_evaluations_: calculating accuracy metrics for all models, including ensemble modeling
6) _Training on full dataset_: training models on full dataset for predicting unlabeled Kaggle test set
7) _Predicting test dataset_: predicting on the final Kaggle dataset

(![image](https://user-images.githubusercontent.com/60722023/111910168-a79ec780-8a36-11eb-8383-db61c0815aa1.png))
