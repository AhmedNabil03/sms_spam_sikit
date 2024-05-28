  <h1>Spam Classification Project</h1>

  <p>This project focuses on classifying spam messages using machine learning algorithms. The dataset used for this project is <strong>spam.csv</strong>.</p>

  <h2>About the Dataset</h2>

  <p>The dataset contains information about text messages along with their labels (ham or spam).</p>
  
  <ul>
      <li><strong>Text</strong>: The content of the text message</li>
      <li><strong>Label</strong>: The classification label (ham or spam)</li>
  </ul>

  <h2>Data Preprocessing</h2>

  <p>In this stage, we performed the following preprocessing steps:</p>
  
  <ul>
      <li><strong>Data Cleaning</strong>: Removed duplicate entries.</li>
      <li><strong>Label Encoding</strong>: Mapped 'ham' to 0 and 'spam' to 1.</li>
      <li><strong>Text Preprocessing</strong>: Cleaned and processed the text data by removing stop words, numbers, and performing stemming.</li>
  </ul>

  <h2>Feature Engineering</h2>

  <p>We utilized TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical features.</p>

  <h2>Model Building</h2>

  <p>We trained various machine learning classifiers on the preprocessed data and evaluated their performance:</p>

  <ul>
      <li><strong>Multinomial Naive Bayes</strong></li>
      <li><strong>Bernoulli Naive Bayes</strong></li>
      <li><strong>Gaussian Naive Bayes</strong></li>
      <li><strong>Support Vector Machine (SVM)</strong></li>
      <li><strong>Logistic Regression</strong></li>
      <li><strong>Decision Tree Classifier</strong></li>
      <li><strong>Random Forest Classifier</strong></li>
      <li><strong>Extra Trees Classifier</strong></li>
      <li><strong>AdaBoost Classifier</strong></li>
      <li><strong>Gradient Boosting Classifier</strong></li>
      <li><strong>XGBoost Classifier</strong></li>
      <li><strong>Bagging Classifier</strong></li>
      <li><strong>Voting Classifier</strong></li>
      <li><strong>Stacking Classifier</strong></li>
  </ul>

  <h2>Conclusion</h2>

  <p>Through this project, we developed and compared multiple machine learning models for spam classification. The best-performing models can be further fine-tuned and deployed for real-world applications.</p>
