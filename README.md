# Movie Recommender System

Hello and welcome to the Movie Recommender System App! This app uses Python, Numpy, Pandas, Matplotlib, and Seaborn frameworks. Users can have personalized movies recommended to them based on a film they previously liked. 

## Steps to run the app using Google Colab
### Import Pandas, Numpy, Matplotlib, and Seaborn frameworks.
<img width="894" alt="Screenshot 2024-08-06 at 16 12 43" src="https://github.com/user-attachments/assets/583571bc-656f-4bdc-8814-fe1c058a0c28">

### Import movies csv file.
<img width="894" alt="Screenshot 2024-08-06 at 16 15 12" src="https://github.com/user-attachments/assets/eb6ece77-facb-4fbd-bb2b-8c4f3d1de2bc">


### Data cleaning and preparation
#### Check for any null values.
<img width="904" alt="Screenshot 2024-08-06 at 16 59 24 copy" src="https://github.com/user-attachments/assets/aea4b37c-b0f1-4618-8321-bf94be7c08e5">

#### Feature engineering
<img width="894" alt="Screenshot 2024-08-06 at 16 59 24" src="https://github.com/user-attachments/assets/e0570c86-336b-42dd-82e3-00a2ec7054b7">
<img width="895" alt="Screenshot 2024-08-06 at 17 01 38" src="https://github.com/user-attachments/assets/4177af8d-c1f1-4bf3-bdd5-97ee0ac3b481">

#### Import Count Vectorizer and cosine similarity from Scikit-learn.
   <img width="891" alt="Screenshot 2024-08-06 at 23 22 49 copy" src="https://github.com/user-attachments/assets/110516c2-7f25-4277-ae10-54b5fd64be6f">

6. Use count vectorizer to extract important features: In our case, the genre and title are the features being extracted
7. Use the cosine similarity library to get the similarity between the movies in our database.
8. Display the first 10 movies similar to Jumanji
