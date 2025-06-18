# Machine Learning in My Style - Educational Website

A comprehensive educational website focused on machine learning topics with a modern, responsive design featuring glassmorphism effects and interactive elements.

## Project Structure

```
/
├── index.html               # Landing page
├── topics.html              # Topics listing page
├── css/
│   ├── styles.css           # Global styles
│   ├── landing.css          # Landing page styles
│   ├── topics.css           # Topics page styles
│   └── subtopic.css         # Subtopic page styles
├── js/
│   └── main.js              # Main JavaScript functionality
├── subtopics/               # Individual topic pages
│   ├── types-of-ml.html     # Sample subtopic page
│   ├── linear-regression.html # Sample subtopic page
│   └── template.html        # Template for creating new subtopic pages
├── public/                  # Static assets
│   └── vite.svg             # Vite logo
└── javascript.svg           # JavaScript logo
```

## Features

- Responsive design that works on mobile, tablet, and desktop devices
- Modern glassmorphism effect for topic and subtopic cards
- Interactive particle background
- Expandable topic cards with subtopic listings
- Toggle-able interview question answers
- Comprehensive subtopic pages with standardized sections:
  - Description
  - Examples (with code samples)
  - Real-World Applications
  - Resources (placeholders for videos, PDFs, etc.)
  - Interview Questions
- Social media links in the footer (Telegram, Instagram, WhatsApp)

## Topics Covered

1. What is Machine Learning?
   - Types: Supervised, Unsupervised, Reinforcement Learning
   - Differences between AI, ML, DL

2. ML Workflow & Pipeline
   - Data → Preprocessing → Model → Evaluation → Deployment
   - Concept of training vs testing

3. Regression Algorithms
   - Linear Regression (Simple & Multiple)
   - Polynomial Regression
   - Metrics: MAE, MSE, RMSE, R² Score

4. Classification Algorithms
   - Logistic Regression
   - k-Nearest Neighbors (k-NN)
   - Decision Trees
   - Random Forest
   - Naive Bayes
   - Support Vector Machines (SVM)
   - Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC

5. Clustering Algorithms
   - K-Means Clustering
   - Hierarchical Clustering
   - DBSCAN
   - Evaluation: Silhouette Score, Elbow Method

6. Dimensionality Reduction
   - Principal Component Analysis (PCA)
   - t-SNE
   - Feature Selection vs Feature Extraction

7. Model Selection & Tuning
   - Cross Validation (K-Fold)
   - Grid Search & Random Search
   - Bias-Variance Tradeoff
   - Underfitting vs Overfitting
   - Regularization: L1 (Lasso), L2 (Ridge)

8. Mini Projects
   - House Price Prediction (Regression)
   - Email Spam Detection (Classification)
   - Customer Segmentation (Clustering)
   - Credit Card Fraud Detection

9. Model Deployment Basics
   - Save models with pickle or joblib
   - Simple Flask web app to deploy a model

10. Bridge to Deep Learning / NLP
    - Limitations of traditional ML
    - Why Deep Learning is needed
    - Intro to Neural Networks

## Getting Started

1. Clone this repository
2. Open `index.html` in your browser to view the landing page
3. Navigate to different sections using the navigation menu

## Adding New Subtopics

1. Copy the template file from `subtopics/template.html`
2. Rename it to match your subtopic
3. Update the content, title, and navigation links
4. Add a link to the new subtopic in `topics.html`

## Design Features

- Custom neural network animation on the landing page
- Particle background using particles.js
- Glassmorphism effect for cards and containers
- Consistent color scheme with gradient accents
- Responsive design with mobile-first approach