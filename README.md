

# YouTube Video Popularity Prediction

##  Statement

This project focuses on predicting the popularity of YouTube videos, specifically in terms of the number of views. The popularity prediction is achieved using a Random Forest model, and the performance is improved by optimizing hyperparameters.


### Dataset

- The dataset used in this project is Usvideo.csv, which contains information about trending YouTube videos in the United States. The dataset includes features such as video title, channel, views, likes, dislikes, and comments, among others.

### Source

The dataset can be downloaded from Kaggle: US YouTube Trending Dataset

### Features
The dataset includes the following features:

- video_id: Unique identifier for the video

- trending_date: Date the video was trending

- title: Title of the video

- channel_title: Name of the channel
- category_id: ID representing the category of the video
- publish_time: Date and time the video was published
- views: Number of views
- likes: Number of likes
- dislikes: Number of dislikes
- comment_count: Number of comments
- tags: Tags associated with the video
- comments_disabled: Whether comments are disabled
- ratings_disabled: Whether ratings are disabled
- video_error_or_removed: Whether the video has errors or has been removed
- thumbnail_link: URL of the video thumbnail
- description: Description of the video


## Exploratory Data Analysis (EDA):

- The EDA  provides an overview of the dataset, including data cleaning, summary statistics, and initial visualizations.
Unsupervised dataset information

![Screenshot 2024-09-03 195506](https://github.com/user-attachments/assets/a33b79d6-4da5-45c7-b0db-09650dfdb249)

Correlation between views and likes

![Screenshot 2024-09-03 194653](https://github.com/user-attachments/assets/4eb31c1d-c5d6-42c5-b1de-fc15e9142828)

Tag and Title Analysis
        
![Screenshot 2024-09-03 194809](https://github.com/user-attachments/assets/371d6e92-c748-4ea0-8418-af92f2ee74d7)

        

### Feature Engineering

The Feature Engineering  includes scripts to extract additional features from the dataset, such as day, month, year, and hour from the publish time, and categorical encoding.

### Model Training and Tuning:

 Model Training  contains scripts for training the Random Forest model.

### Model Evaluation:

 Model Evaluation  evaluates the model performance using metrics like Mean Absolute Error (MAE) and R^2 Score. Visualizations of the model comparison are also provided.

 ![Screenshot 2024-09-03 200529](https://github.com/user-attachments/assets/c98b8ac9-41d0-4209-bb4b-7e41cd89d9ce)

 ![Screenshot 2024-09-03 200623](https://github.com/user-attachments/assets/4a3c23c2-0f26-428b-b578-613e7ab3fd90)


## Conclusion

The Random Forest model was able to predict YouTube video popularity with a reasonable degree of accuracy. The model's performance can be further improved by incorporating additional features or exploring more advanced modeling techniques.


           

### Python Libraries Used
The following Python libraries are used in the project:

-  Pandas  : For data manipulation and analysis.


- NumPy: For numerical computations.


- Matplotlib: For data visualization.


- Scikit-learn: For machine learning algorithms, model training, hyperparameter tuning, and evaluation.


- Seaborn: For enhanced data visualization (optional, used in EDA).
## Algorithms Used
### Random Forest Regressor

- The primary algorithm used for predicting the popularity of YouTube videos.
