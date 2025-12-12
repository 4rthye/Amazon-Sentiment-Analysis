# Amazon-Sentiment-Analysis
Sentiment Analysis on 10k+ Amazon product review using Python, NLTK, TextBlob , and VADER

# Amazon Product Reviews - Sentiment Analysis 📊

Sentiment analysis system analyzing 10,000+ Amazon product reviews using Natural Language Processing (NLP).

## 🎯 Project Overview
This project performs sentiment classification on Amazon product reviews to identify customer satisfaction trends. I implemented two different sentiment analysis methods (TextBlob and VADER) and compared their accuracy.

## 🛠️ Technologies Used
- **Python 3.x**
- **NLTK** - Text preprocessing and tokenization
- **TextBlob** - Sentiment polarity analysis
- **VADER Sentiment** - Social media-optimized sentiment analysis
- **Pandas** - Data manipulation
- **Matplotlib & Seaborn** - Data visualization
- **WordCloud** - Text visualization

## 📁 Dataset
- **Source**: Amazon Product Reviews (Kaggle)
- **Size**: 568,454 total reviews (sampled 10,000 for analysis)
- **Features**: Product ID, User ID, Rating (1-5 stars), Review Text, Timestamp

## 🔍 What I Did
1. **Data Preprocessing**
   - Cleaned text data (removed HTML, URLs, special characters)
   - Tokenization and lemmatization
   - Removed stopwords
   
2. **Sentiment Analysis**
   - Implemented TextBlob sentiment scoring
   - Implemented VADER sentiment analysis
   - Compared both methods against actual star ratings
   
3. **Visualization & Insights**
   - Rating distribution analysis
   - Sentiment comparison charts
   - Word clouds for positive/negative/neutral reviews
   - Polarity score distributions
   - Confusion matrices

## 📊 Results
- **TextBlob Accuracy**:  79.49%
- **VADER Accuracy**: 80.99%
- Found that VADER performed better for this dataset

## 🖼️ Sample Visualizations
<img width="998" height="745" alt="sample_visualization_1" src="https://github.com/user-attachments/assets/591b7204-a14b-4302-97eb-15ac3ed27ec4" />
<img width="1686" height="442" alt="sample_visualization_2" src="https://github.com/user-attachments/assets/4ae076e3-bb32-459d-9b9f-dcca4d0bc4df" />
<img width="1682" height="317" alt="sample_visualization_3" src="https://github.com/user-attachments/assets/4f513d29-28f4-48a8-bbb9-474186647902" />
<img width="1238" height="737" alt="sample_visualization_4" src="https://github.com/user-attachments/assets/eaf61df4-6e26-40dd-ab1b-be0e12b6a77a" />



## 🚀 How to Run
1. Clone this repository
```bash
   git clone https://github.com/4rthye/amazon-sentiment-analysis.git
```

2. Install required libraries
```bash
   pip install pandas nltk textblob vaderSentiment wordcloud matplotlib seaborn scikit-learn
```

3. Download NLTK data
```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('punkt_tab')
```

4. Open and run the Jupyter notebook
```bash
   jupyter notebook sentiment_analysis.ipynb
```

## 📈 Key Findings
- Positive reviews (4-5 stars) dominate the dataset 
- Common positive words: [product, great, love, good, quality]
- Common negative words: [waste, terrible, bad, disappointed]

## 🎓 What I Learned
- Text preprocessing techniques (cleaning, tokenization, lemmatization)
- Different sentiment analysis approaches and their tradeoffs
- How to handle large datasets efficiently
- Data visualization best practices

## 📝 Future Improvements
- [ ] Train custom ML model (Logistic Regression, Random Forest)
- [ ] Add bigram/trigram analysis
- [ ] Implement deep learning (LSTM/BERT)
- [ ] Create interactive dashboard with Streamlit

## 👤 Author
**Your Name**
- GitHub: [@your_username](https://github.com/4rthye)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/arthyesridharan)

## 📄 License
This project is open source and available under the MIT License.
