# Food Review Sentiment Analyzer

## Summary
An AI that analyzes food reviews to predict if they're positive or negative. Uses NLP techniques like Bag of Words and TF-IDF to classify restaurant reviews automatically. **Building AI course project**

## Background
People leave thousands of food reviews online on Yelp, TripAdvisor, and Google. Reading them all takes too much time. This project automatically classifies reviews as positive 😊 or negative 😞, helping people quickly understand if a restaurant has good feedback.

## How is it used?
1. **Input**: "The pizza was amazing and the service was great!"
2. **Process**: Text → Bag of Words → TF-IDF → Classification
3. **Output**: Positive or Negative sentiment

Example:
- "Best pasta ever!" → Positive ✓
- "Cold food, slow service" → Negative ✓

## Data sources and AI methods
- **Data**: Public food review datasets (Yelp, TripAdvisor)
- **Methods**: 
  - Bag of Words text representation
  - TF-IDF (Term Frequency - Inverse Document Frequency)
  - Naive Bayes or Logistic Regression classifier

## Challenges
- Cannot detect sarcasm ("Great, another 30-minute wait...")
- Mixed reviews are tricky ("Good food but expensive")
- Only works for English reviews
- May misclassify reviews with unusual wording

## What next?
- Add support for Romanian language 🇷🇴
- Predict star ratings (1-5) instead of just positive/negative
- Build a web interface where users can paste reviews
- Recommend dishes based on review patterns

## Acknowledgments
- Dataset: Yelp Open Dataset
- Course: Building AI by Reaktor and University of Helsinki
- Inspiration: My love for food and trying new restaurants! 🍕
