# sms_spam_detector

## Project Summary
This project showcases an SMS spam detection model powered by machine learning. By leveraging Linear Support Vector Classification (SVC), the model identifies whether an SMS message is spam or legitimate. The model is integrated with a Gradio-powered web app, enabling users to easily enter a message and instantly receive a spam or ham classification.

## Key Highlights
- **Spam Detection**: Classifies SMS messages as either spam or legitimate based on content.
- **Intuitive Interface**: Provides a simple Gradio interface for real-time use.
- **Immediate Results**: Offers instant feedback on the classification outcome.

## Tools and Libraries
- **Python**: Programming language for model development
- **Scikit-learn**: Library for machine learning and model implementation
- **Pandas**: For data handling and preprocessing
- **Gradio**: User interface for accessible, web-based interaction
- **NLP**: TF-IDF used to process and extract features from text

## Model Insights
- **Method**: Linear Support Vector Classification (SVC) algorithm
- **Text Feature Extraction**: TF-IDF vectorization transforms text for model input
- **Data Split**: 67% for training, 33% for testing
- **Pipeline Structure**: Organizes steps for efficient data processing and predictions

## Example Messages to Test
Explore the classifier with these samples:
- "You are a lucky winner of $5000!"
- "You won 2 free tickets to the Super Bowl."
- "You won 2 free tickets to the Super Bowl text us to claim your prize."
- "Thanks for registering. Text 4343 to receive free updates on medicare."
## References
This project builds on foundational code and exercises provided by the Columbia AI Bootcamp, with extensions and refinements for this specific dataset and prediction task.