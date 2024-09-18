# Sentiment Analysis using Naive Bayes

This project implements a sentiment analysis model using Naive Bayes and TF-IDF for text vectorization. The goal is to classify input text as positive, negative, or neutral sentiments.

## Dataset

The dataset is expected to be in CSV format. You can modify the path in the code to load your own dataset.

**Columns:**
- `selected_text`: The text data on which sentiment analysis is performed.
- `sentiment`: The label, which can be positive, negative, or neutral.

## Requirements

To install the required dependencies, use:

```bash
pip install -r requirements.txt
```

## Instructions
1. Ensure the dataset is in CSV format and placed in the correct path.
2. Run the script in your environment or through Google Colab.
3. The model will train on 75% of the data and test on the remaining 25%.
   
## Usage
To use the sentiment predictor in the script:
  1. Run the script, and the model will ask for input text to predict the sentiment.
  2. You can also use the pre-defined function pred_senti() to predict custom texts within the 
     code.
     
```python
# Example:
pred_senti("I love this!", model)
```

## Output
The script will display the following:
- Confusion matrix and heatmap
- Classification report including precision, recall, F1-score, and accuracy.
    
## Future Improvements
- Improve the model with additional preprocessing steps.
- Try using different models for comparison.

