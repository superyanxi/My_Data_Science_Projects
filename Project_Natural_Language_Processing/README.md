This project is about Natural Language Processing. I built a journal finder system for researchers who are looking for journals to publish their papers. What researcher needs to do is inputting the abstract of the paper to the system, and the journal finder will recommend the journals which is most similar to the input abstract. To build the database of abstract, I used API to retrieve more than 8000 abstracts from a publisher website called Elsevier. After preprocessing, I used TF-IDF and LSI to convert text into the numeric vector with reduced dimension. Then LDA was applied to turn the abstract into a numeric vector in topic space. Two type of feature vectors obtained from TF-IDF and LDA were fed to a classification model, which can predict which journal the abstract belongs to. The classification model based on random forest model achieves the accuracy of 85%. I also made a flask app for visualization of the systems. 

A jupyter notebook file and partial raw data are provided.
Work Flow:
Preprocessing
LSI for Dimensionality Reduction
Adding features from LDA
Applying Machine Learning models for training.

Main python packages:
sklearn
gensim



To learn more about the project, please visit my [blog] (https://yanxilu.weebly.com/)
