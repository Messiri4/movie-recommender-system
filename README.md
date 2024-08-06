# Movie Recommender System

Hello and welcome to the Movie Recommender System App! This app uses Python, Numpy, Pandas, Matplotlib, and Seaborn frameworks. Users can have personalized movies recommended to them based on a film they previously liked. 

## Steps to run the app using Google Colab
1. Import Pandas, Numpy, Matplotlib, and Seaborn frameworks.
<img width="894" alt="Screenshot 2024-08-06 at 16 12 43" src="https://github.com/user-attachments/assets/583571bc-656f-4bdc-8814-fe1c058a0c28">

2. Import movies csv file.
<img width="1023" alt="Screenshot 2024-08-06 at 16 15 12" src="https://github.com/user-attachments/assets/f33eb1ba-0edb-4d51-9bf3-3fd4f0d3e277">

3. Data cleaning and preparation.
<img width="1021" alt="Screenshot 2024-08-06 at 16 59 24" src="https://github.com/user-attachments/assets/05d63d3d-926e-4767-90db-015c788f074c">

<img width="1022" alt="Screenshot 2024-08-06 at 17 01 38" src="https://github.com/user-attachments/assets/218bc01e-fb1b-478f-ae71-d485d62f70cc">

4. Import Count Vectorizer and cosine similarity from Scikit-learn.
6. Use count vectorizer to extract important features: In our case, the genre and title are the features being extracted
7. Use the cosine similarity library to get the similarity between the movies in our database.
8. Display the first 10 movies similar to Jumanji
