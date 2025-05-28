# 2.1 NT Q1: Hackathon Preparation Timeline 🛠️

## Week 1: Problem Selection and Quantitative Formulation

The first step is to finalize the problem statement we want to work on in the hackathon. Our aim will be to pick a problem that is:

- Relevant and impactful  
- Has available data sources  
- Solvable within the hackathon timeline  

Some ideas could be:
- Text classification  
- Object detection  
- Fraud detection  
- Predictive analytics  

Once the problem is selected, we will clearly **formulate it in measurable, quantitative terms**. For example:

- _“Predict the probability of a financial transaction being fraudulent with at least 90% precision and recall”_  
- _“Classify social media comments into positive, negative, or neutral with over 85% accuracy”_

This helps in setting a clear goal for model evaluation and final success criteria.

**Deliverable:** Finalized problem statement and problem formulation document.

---

## Week 2: Data Sourcing and Preprocessing

Once the problem is decided, we’ll focus on finding and preparing data.

**Data Sourcing:**

- Look for publicly available datasets from:
  - Kaggle  
  - UCI Machine Learning Repository  
  - Google Dataset Search  
  - Official APIs  

If required, consider generating synthetic data or scraping data from relevant platforms.

**Preprocessing Tasks:**

- Remove irrelevant columns  
- Handle missing values (by imputation or deletion)  
- Encode categorical variables  
- Normalize or standardize numerical features  
- Clean text data (if applicable) by removing stopwords, punctuation, and special characters  

**Deliverable:** Cleaned, preprocessed dataset and a notebook documenting all preprocessing steps.

---

## Week 3: Exploratory Data Analysis (EDA) and Model Selection

**EDA Tasks:**

- Visualize data distributions  
- Check correlations between features and target variables  
- Identify outliers  
- Understand data trends and patterns using:
  - Histograms  
  - Scatter plots  
  - Heatmaps  

**Model Selection:**

Based on the problem type (classification, regression, etc.), we will shortlist models like:

- **Classical models:** Logistic Regression, Decision Trees, Random Forests, SVM  
- **Advanced models:** XGBoost, LightGBM, or Neural Networks (if needed)

We’ll also list the **compute resources** we’ll require:
- For classical models: Personal laptop  
- For deep learning models: Cloud GPUs (Google Colab, Kaggle Notebooks, or AWS EC2)

**Deliverable:** EDA report, selected models list, and compute resource plan.

---

## Week 4: Model Training, Evaluation, and Team Management

**Training Strategies:**

- Use **k-fold cross-validation** to avoid overfitting  
- Tune hyperparameters  
- Evaluate models using appropriate metrics:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - ROC-AUC  

**Team Roles:**

- **Team Lead:** Coordinate work and manage deliverables  
- **Data Engineer:** Data collection and preprocessing  
- **EDA Specialist:** Conduct exploratory data analysis  
- **Model Developer:** Train and tune models  
- **Presentation Lead:** Prepare final report, demo, and presentation  

**Risk Mitigation:**

- Keep backup datasets and models  
- Document all code and workflows  
- Regular team meetings for status updates  
- Have a simple baseline model ready as a fallback  

**Deliverable:** Final trained model, performance report, and presentation slide deck.

---

