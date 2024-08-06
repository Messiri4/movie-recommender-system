# Movie Recommender System

Hello and welcome to the Movie Recommender System App! This app uses Python, Numpy, Pandas, Matplotlib, and Seaborn frameworks. Users can have personalized movies recommended to them based on a film they previously liked. 

## Steps to run the app using Google Colab
### Import Pandas, Numpy, Matplotlib, and Seaborn frameworks.
<img width="894" alt="Screenshot 2024-08-06 at 16 12 43" src="https://github.com/user-attachments/assets/583571bc-656f-4bdc-8814-fe1c058a0c28">

### Import movies csv file.
<img width="894" alt="Screenshot 2024-08-06 at 16 15 12" src="https://github.com/user-attachments/assets/eb6ece77-facb-4fbd-bb2b-8c4f3d1de2bc">


### Data cleaning - Check for any null values.
<img width="904" alt="Screenshot 2024-08-06 at 16 59 24 copy" src="https://github.com/user-attachments/assets/aea4b37c-b0f1-4618-8321-bf94be7c08e5">

### Data preparation - Feature engineering
<img width="894" alt="Screenshot 2024-08-06 at 16 59 24" src="https://github.com/user-attachments/assets/e0570c86-336b-42dd-82e3-00a2ec7054b7">


4. Import Count Vectorizer and cosine similarity from Scikit-learn.
6. Use count vectorizer to extract important features: In our case, the genre and title are the features being extracted
7. Use the cosine similarity library to get the similarity between the movies in our database.
8. Display the first 10 movies similar to Jumanji
