CA05 – kNN Movie Recommender 

Data Source and Contents:
  Have you ever come across a film and wanted to know what other films it resembles based on the genre? We can actually create a recommender system to give   us recommended movies based on genre information from any given film.

The sample dataset we will be using is obtained from the following url in csv format:

"https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv” Use the GitHub link in your Python code to “read” the data into a Data frame.

    movies = pd.read_csv('https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv')  

Runtime: <1 minute

Steps:
1. Read in data and import necessary packages 
2. EDA 
3. Drop the 'Label' column as we will not be using it 
4. Create new variables with x representing the features and y representing the movie name 
5. Implement the model 
6. Define a variable (the_post) for the film we are recommending movies for 
7. Return the distances and indices
8. Return movie titles based on genre information 


Any issues running the code please contect, msoto13@lion.lmu.edu
