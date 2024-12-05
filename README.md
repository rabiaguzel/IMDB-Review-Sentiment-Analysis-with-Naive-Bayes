

#### IMDB Review Sentiment Analysis with Naive Bayes  
This project performs sentiment analysis on a dataset of IMDB reviews on Kaggle. The dataset is preprocessed to remove stopwords, and the text data is vectorized using **TF-IDF**. A **Naive Bayes classifier** is then trained to classify reviews as positive or negative.

---

#### Features
- Preprocesses IMDB reviews: converts text to lowercase and removes stopwords.
- Vectorizes text data using the **TF-IDF** technique.
- Classifies sentiments (positive/negative) with a **Multinomial Naive Bayes** model.
- Evaluates the model with an accuracy score.

---

#### Requirements
- Python 3.x  
- Libraries:  
  `pandas`, `nltk`, `sklearn`, `wordcloud`

---
- **Model Accuracy**: ~86.53%

---

### README (Türkçe)

#### Naive Bayes ile IMDB Yorum Analizi  
Bu proje, Kaggle'dan alınan IMDB yorumları veri setinin duygu analizini yapar. Veri ön işleme aşamasında stop kelimeler kaldırılır, metinler küçük harflere dönüştürülür ve **TF-IDF** yöntemiyle vektörleştirilir. Daha sonra **Naive Bayes sınıflandırıcı** ile yorumların olumlu veya olumsuz olduğu belirlenir.

---

#### Özellikler
- IMDB yorumlarını temizler: küçük harflere çevirir ve stop kelimeleri kaldırır.
- Metin verisini **TF-IDF** yöntemiyle vektörleştirir.
- **Multinomial Naive Bayes** modeli ile duygu sınıflandırması yapar.
- Model doğruluğunu ölçer ve ekrana yazdırır.

---

#### Gereksinimler
- Python 3.x  
- Kütüphaneler:  
  `pandas`, `nltk`, `sklearn`

---

- **Model Doğruluğu**: ~%86.53  
