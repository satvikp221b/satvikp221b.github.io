## Proficiencies

**Programming Languages:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![Java](https://img.shields.io/badge/-Java-007396?logo=java&logoColor=white), ![R](https://img.shields.io/badge/-R-276DC3?logo=r&logoColor=white)

**Machine Learning & AI:** ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white), ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white), ![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white), ![Keras](https://img.shields.io/badge/-Keras-D00000?logo=keras&logoColor=white), ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white)

**Data Visualization:** ![Tableau](https://img.shields.io/badge/-Tableau-E97627?logo=tableau&logoColor=white), ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C), ![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB), ![Dash](https://img.shields.io/badge/-Dash-008B8B), ![JMP](https://img.shields.io/badge/-JMP-0076A8)

**Big Data & Databases:** ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white), ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white), ![Hadoop](https://img.shields.io/badge/-Hadoop-66CCFF?logo=apache-hadoop&logoColor=black)

**MLOps & Cloud:** ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white), ![MLflow](https://img.shields.io/badge/-MLflow-0194E2), ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white), ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)

**Development Tools:** ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white), ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white), ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?logo=visual-studio-code&logoColor=white), ![PyCharm](https://img.shields.io/badge/-PyCharm-000000?logo=pycharm&logoColor=white)

**Advanced Analytics:** Predictive Modeling, Recommender Systems, Time Series Analysis, Natural Language Processing, Text Mining, Feature Engineering

## Projects
### Enhanced Ship Detection through Deep-Learning-Based Super-Resolution Embedding

**Description:**
This project focuses on improving ship detection in satellite and aerial imagery through the use of deep learning-based super-resolution techniques. The approach integrates the Enhanced Super-Resolution Generative Adversarial Network (ESRGAN) to enhance image quality, allowing for finer detection of smaller ships. Following the super-resolution process, YOLOv5 is used for ship identification, ensuring high accuracy and real-time processing, crucial for maritime applications like safety and traffic management.

**Challenges Solved**:
- Enhanced image quality for small object detection.
- Improved detection with the use of YOLOv5.
- Applied attention mechanisms for accurate ship detection in cluttered maritime environments.

**Results:**

![Super-Resolution Image Before and After](images/side_by_side.jpg)
![YOLOv5 Detection Results](images/final_bb.jpg)

**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white), ![YOLOv5](https://img.shields.io/badge/-YOLOv5-yellow?logo=yolo), ![ESRGAN](https://img.shields.io/badge/-ESRGAN-green)

**GitHub Repository:** <a href="https://github.com/satvikp221b/Ship-Detection-Super-Res" target="_blank">Link to Project Repo</a>

### Sarcasm Detection

**Description:**
This project aims to detect sarcasm in text using a combination of deep learning models, including Logistic Regression, LSTM, and BERT. The project features a web application where users can input text and receive sarcasm predictions. In addition to textual analysis, the model incorporates several additional features, such as the words count, punctuation marks, and sentiment analysis using TextBlob.

**Challenges Solved**:
- Accurate sarcasm detection using modern deep learning techniques.
- Use of additional features like polarity, punctuation marks, capitalization of words, tonal shift.
- Built a Flask-based web application for sarcasm prediction for a smoother interface where model switching can be quick b/w Logistic Regression, LSTM, BERT and Lasso LR.


**Results:**

| Model Metrics | Web App Home Page |
| -------------- | --------------- |
| <img src="images/Metrics_df.png" width="300"/> | <img src="images/Default_home.png" width="300"/> |

| Sarcasm Detected | No Sarcasm Detected |
| ------------------- | ------------------- |
| <img src="images/sarcasm.png" width="300"/> | <img src="images/non_sarcasm.png" width="300"/> |

**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white), ![Flask](https://img.shields.io/badge/-Flask-black?logo=flask), ![BERT](https://img.shields.io/badge/-BERT-yellow?logo=bert), ![TextBlob](https://img.shields.io/badge/-TextBlob-lightgrey?logo=python&logoColor=green), ![VADER](https://img.shields.io/badge/-VADER-darkgreen?logo=vader&logoColor=white)

**GitHub Repository:** <a href="https://github.com/satvikp221b/Sarcasm-Detector-NLP" target="_blank">Link to Project Repo</a>

### Heartbeat Detection from Video

**Description:**
This project focuses on detecting heart rate from video using advanced computer vision techniques and signal processing. Initially developed during the last semesters of college, the project has been enhanced with recent improvements like Auto Correlation, MTCNN face detection, and averaging frames for better heart rate calculation. The method is based on Photoplethysmography (PPG), which captures subtle changes in skin color corresponding to the cardiac cycle. The project includes Eulerian Video Magnification (EVM) to amplify these subtle changes, making it possible to calculate heart rate accurately from video input.

**Challenges Solved**:
- Achieved non-contact heart rate detection with an error margin of ±5 bpm under ideal conditions.
- Enhanced face detection by incorporating MTCNN, improving the reliability of ROI segmentation.
- Replaced FFT with Auto Correlation for more stable heart rate signal detection.

**Results:**

| Processed Video | Heart Rate Overlay |
| --------------- | ------------------ |
| ![Processed Video](images/output_magnified_roi_noeyes-gif.gif) | ![Heart Rate](images/output_with_hr-gif.gif) |


**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv&logoColor=white), ![MTCNN](https://img.shields.io/badge/-MTCNN-red) 

**GitHub Repository:** <a href="https://github.com/satvikp221b/Heartbeat-Detection-Using-Video" target="_blank">Link to Project Repo</a>

### Computer Interactive Graphics Projects

**Description:**
This collection showcases my work in the **Computer Interactive Graphics course** at the **University of Illinois Urbana-Champaign (UIUC)**. These projects cover various aspects of computer graphics, such as animation, terrain generation, camera controls, physics-based simulations, and ray tracing. Each project explores different techniques and tools for creating dynamic and interactive graphics.

**Skills Used:**
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white), ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black), ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![WebGL](https://img.shields.io/badge/-WebGL-990000?logo=webgl&logoColor=white), ![OpenGL](https://img.shields.io/badge/-OpenGL-5586A4?logo=opengl&logoColor=white)

For more details on each project, [Click here to view the full project descriptions and demos](project/Interactive_graphics.md).


### Diabetic Retinopathy Detection Using Deep Learning

**Description:**
This project focuses on detecting Diabetic Retinopathy (DR) using deep learning techniques applied to retinal fundus images. The approach begins with extensive image preprocessing, followed by the development of three models for DR classification:
- **Model 1 (Custom CNN - EyeNet):** A custom CNN built from scratch, though it achieved moderate accuracy, it was eventually replaced by pre-trained models.
- **Model 2 (Pre-trained CNNs):** Utilized several pre-trained models like AlexNet, VGGNet, ResNet, and GoogleNet. These models were fine-tuned and hyperparameters were adjusted to improve performance but encountered overfitting issues.
- **Model 3 (Ensemble):** The final solution, an ensemble of ResNet50, InceptionV3, Xception, DenseNet121, and DenseNet169, provided the best results, balancing accuracy and recall across all DR severity stages.

The project is integrated into a Flask-based web application, allowing users to upload retinal images and receive real-time predictions on the severity of DR, making it accessible for early diagnosis in resource-constrained environments.

**Challenges Solved**:
- Class imbalance in the dataset was handled through data augmentation.
- Overcame overfitting in deep learning models by using an ensemble approach.
- Achieved high accuracy for classifying DR severity into five distinct stages, allowing for early detection and intervention.

**Results:**

![Website Upload](images/Website-1.png)
![Wesite Results](images/Website-Chart.png)

**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white), ![Keras](https://img.shields.io/badge/-Keras-D00000?logo=keras), ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?logo=opencv), ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white)

**GitHub Repository:** <a href="https://github.com/satvikp221b/Diabetic-Retinopathy-Deep-Learning" target="_blank">Link to Project Repo</a>

### Recommender Systems - MovieLens Dataset

**Description:**
This project focuses on building a sophisticated movie recommendation system using a combination of content-based and collaborative filtering techniques. The system integrates multiple recommenders, including a simple recommender based on popularity, content-based recommenders using movie metadata (such as overview, cast, crew, and keywords), and collaborative filtering using a Boltzmann machine. A hybrid model is also implemented, which combines both user preferences (ratings) and movie features for more accurate and personalized recommendations. The data is sourced from the MovieLens dataset and enhanced using TMDB's API to include the latest movies and metadata.

**Challenges Solved**:
- **Handling Sparsity in User Ratings:** Addressed the challenge of sparse data in collaborative filtering by combining it with content-based recommendations, ensuring better recommendations even for users with limited interactions.
- **Weighting Multiple Features:** Tuned the weighting of cast, crew, genre, and keywords to allow personalized emphasis on certain features for content-based filtering, improving recommendation relevance.
- **Natural Language Understanding for Movie Descriptions:** Employed advanced NLP techniques such as TF-IDF, Latent Semantic Analysis (LSA), and Word2Vec to accurately recommend movies based on subtle similarities in overviews and taglines.
- **Integration of User Preferences with Movie Metadata:** Developed a hybrid recommender that successfully combines user ratings with movie features, achieving better personalization by leveraging both user behavior and movie attributes.
- **Scalability of Data Collection:** Created a system to dynamically collect movie data from the TMDB API, ensuring the system remains up-to-date with newly released movies.

**Results:**

| Simple Recommender | Content-Based (Overview & Tagline) |
| ------------------ | --------------------------------- |
| ![Simple Recommender](images/Simple_Recommender.png) | ![Content-Based Overview](images/Content_Based.png) |

| Content-Based (Crew & Cast(Most -weightage)) | Hybrid Recommender |
| --------------------- | ------------------ |
| ![Boltzmann Recommender](images/Cast_Crew_Recommender.png) | ![Hybrid Recommender](images/Boltzmann_Recommender.png) |


**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white), ![NLP](https://img.shields.io/badge/-NLP-yellowgreen), ![NLTK](https://img.shields.io/badge/-NLTK-39b54a?logo=nltk&logoColor=white), ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?logo=scikit-learn&logoColor=white), ![Word2Vec](https://img.shields.io/badge/-Word2Vec-0099CC?logo=gmail&logoColor=white), ![TMDB API](https://img.shields.io/badge/-TMDB%20API-brightgreen), ![Boltzmann Machine](https://img.shields.io/badge/-Boltzmann%20Machine-blue)

**GitHub Repository:** <a href="https://github.com/satvikp221b/Movie-Recommender-System" target="_blank">Link to Project Repo</a>

### Stock Portfolio Dashboard

**Description:**
This project provides a comprehensive Stock Portfolio Dashboard that helps users track, analyze, and visualize stock investments. It consists of two parts:
1. **Portfolio Builder**: Users input stock data such as shares, buy price, and ticker, saving it into a CSV file.
2. **Financial Dashboard**: Reads the portfolio CSV and provides financial metrics and visualizations for individual stocks and the entire portfolio.

The dashboard offers key metrics like **P/E Ratio**, **P/B Ratio**, **Dividend Yield**, **ROE**, and **Analyst Recommendations**, along with technical analysis tools like **SMA**, **VWMA**, **EMA**, and **Bollinger Bands**.

**Challenges Solved**:
- **Portfolio Management**: Consolidates multiple stock transactions into one portfolio, calculating total shares and average buy price.
  
- **Advanced Metrics**: Provides Sharpe Ratio, Jensen's Alpha, Beta, and Treynor Ratio for risk-adjusted performance evaluation.

- **Real-Time Data**: Fetches live financial data using `yfinance`, ensuring up-to-date metrics like P/E, P/B, Return on Equity, and Dividend Yield.

- **Technical Analysis Visualization**: Offers charts with SMA, VWMA, EMA, Bollinger Bands, and Fibonacci levels for market trend analysis.

- **Golden/Death Cross Detection**: Detects Golden Cross and Death Cross signals for identifying long-term buy/sell opportunities.

- **Portfolio Overview**: Provides a summary of Total Investment, Current Value, Profit/Loss, and Daily Profit/Loss, aiding in decision-making.

- **User-Friendly Automation**: The portfolio builder allows easy stock data input, handling multiple purchases, and saving data efficiently for dashboard integration.


**Results:**

| Portfolio Builder  | Portfolio Stats  |
| ------------------ | ------------- |
| ![Portfolio Builder](images/Portfolio_Builder.jpg) | ![Stock Analysis](images/Portfolio_Stats.png) |

| Stock-wise Stats   | Stock Graph Examples  |
| ------------------ | ------------- |
| ![Portfolio Overview](images/Stockwise_Stats.png) | ![Stock Analysis](images/Stock_Graph_1.png) |

| Volume and Bollinger   | Candlestick  |
| ------------------ | ------------- |
| ![Portfolio Overview](images/Stock_Graph_2.png) | ![Stock Analysis](images/Stock_Graph_3.png) |

**Skills Used:**

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white), ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white), ![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?logo=plotly&logoColor=white), ![Dash](https://img.shields.io/badge/-Dash-000000?logo=dash&logoColor=white), ![yfinance](https://img.shields.io/badge/-yfinance-green?logo=yahoo&logoColor=purple)

**GitHub Repository:** <a href="https://github.com/satvikp221b/Stocks-Portfolio" target="_blank">Link to Project Repo</a>




