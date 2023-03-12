# Font_Recognition

Several progresses were made in the field of text recognition / OCR in recent years but the task of font recognition is still seen as a challenge. There are a variety of fonts available in various shapes and styles. Likewise, there are several fonts with only minor differences in characteristics. Font identification is complex as a result of this. The most difficult part is distinguishing the small differences between these similar fonts. The recognition rate of conventional OCR text recognition systems is low, with several errors. It has trouble distinguishing between different text fonts which makes it a long running challenge. Modern text recognition systems should be able to recognise text and font information in a variety of fonts with high accuracy. In this paper, the objective that aims to precisely recognize font shapes and styles of texts in images by proposing a method based on Convolutional Neural Network is done. The proposed method is tuned for multi – classification and is divided into two steps. The first step is to split the dataset into the ratio of 3:1 for training and testing purpose followed by training of the CNN based model. The second step is done by feeding the model an image to identify the font. The dataset for the proposed method contains 5 classes which are Lato, Raleway, Roboto, Sansation and Walkway. The following font images are generated per class in the form of random strings with 100 number of images each. The final model gives an accuracy of 98.93% with very good Precision, Recall and F1 – score.
