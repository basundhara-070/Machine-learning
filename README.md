# Basic differences between AI, ML, DL and Generative AI
1. AI - It is a broad field of creating machines that can perform tasks requiring human intelligence. E.g., Siri, chess playing programs.
2. ML - A subset of AI focused on algorithms that allow systems to learn from and improve based on data without explicit programming. E.g., Spam filtering, recommendation engines.
3. DL - A subset of ML that uses neural networks with multiple layers. It mimics the human brain. E.g., Image recognition, speech recognition.
4. Generative AI - A branch of AI often powered by DL that generates new, creative outputs based on input data. E.g., ChatGPT, DALL.E. 

# Machine Learning
**1. Classificaton of ML**
   i. Supervised ML</br>
      - Regression</br>
      - Classification</br>
   ii. Unsupervised ML</br>
      - Clustering</br>
      - Dimensionality reduction</br>

**2. Supervised ML**
   Model learns from labeled data to make predictions or decisions.</br>
   _Types -_</br>
   - Regression - used for continuous output. E.g., predicting house prices, forcasting stock process.</br>
   - Classification - used for categorical output. E.g., email spam detection, image recognition.</br>
   
**3. Umsupervised ML**
   Model learns patterns, structures, or relationships in data without labeled outputs.</br>
  _Types-_</br>
  - Clustering - group data points into clusters based on similarity. E.g., customer segmentation in marketing, grouping similar documents or images.</br>
  - Dimensionality redution - reduces the number of features while preserving significant information. E.g., visualizing high-dimensional data, preprocessing for other ML tasks.</br>

**4. Algorithms in Supervised ML**
   - Linear Regression
   - Ridge and lasso
   - Logistic regression
   - Decision tree
   - AdaBoost
   - Random Forest
   - Gradient Boosting
   - Xgboost
   - Naive Baye's
   - SVM
   - KNN

**5. Algorithms in Unsupervised ML**
   - K Means
   - DB Scan
   - Hierarical
   - K nearest neighbour clusturing
   - PCA
   - LDA

# Linear Regression
Suppose we have a dataset in which we have some independent variable lets say 'x' and a dependent variable 'y'. Using this dataset as training dataset we make a model which is a hypothesis and make a best fit line which helps us do all the predictictions. So, we can give a new input and obtain a new output for that input. Using a performance matrix, we verify the model. Here, we represent 'y' as a linear function of 'x'.<br/><br/>

**_Equation of straight line:_ <br/>**
**h<sub>ɵ</sub>(x<sub>i</sub>) = ɵ<sub>0</sub> + ɵ<sub>1</sub>x<sub>i</sub> <br/>**
 ɵ<sub>0</sub> = intercept<br/>
 ɵ<sub>1</sub> = slope<br/>
 x<sub>i</sub> = data points<br/>
<br/>
Our aim is to reduce the distance between our predicted points(lying on the best fit line) and the actual data points. Keep updating  ɵ<sub>0</sub> and  ɵ<sub>1</sub> till you get the best fit line.<br/>
<br/>
**Cost Function : <br/>
J( ɵ<sub>0</sub>,ɵ<sub>1</sub>) = (1/2m) <sup>m</sup><sub>i=1</sub>∑(h<sub>ɵ</sub>(x<sub>i</sub>)-y<sub>i</sub>)²**
   
   

