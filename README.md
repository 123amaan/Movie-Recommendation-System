MOVIE RECOMMENDATION SYSTEM

Welcome to the Movie Recommendation System project! This project demonstrates a basic movie recommendation engine built using Python. It leverages content-based filtering to suggest movies similar to the one you input. The system compares movie plots and recommends titles that share similarities based on cosine similarity.

Features
Content-Based Filtering: This approach suggests movies based on their content (e.g., genres, plot summary) that are similar to the user's input.
Efficient Matching: Utilizes libraries like difflib to find the closest match for movie titles.
Cosine Similarity: The recommendations are sorted by the similarity score calculated using cosine similarity, ensuring relevant suggestions.

How it works
Movie Input: The user inputs a movie title.
Closest Match: The system finds the closest match for the input movie from the dataset.
Recommendation: It computes similarity scores and returns a list of recommended movies sorted by their similarity.

Example
When you input Twilight, the system suggests the following movies:

This is the output of the system : 

![image](https://github.com/user-attachments/assets/9f87a1e1-32b3-4628-986f-d5f62e6c3811)

Dataset
The movie data used in this project includes titles, descriptions, genres, and more, which are stored in a DataFrame. The dataset is processed using:

Pandas: For data manipulation and analysis.
Pickle: For saving the processed DataFrame for reuse.
Difflib: For matching movie titles.

How to Run the Project
Clone the repository:

    bash
    git clone https://github.com/yourusername/Movie-Recommendation-System.git
    cd Movie-Recommendation-System
    
Install dependencies:

    bash
    pip install -r requirements.txt

Run the Jupyter notebook:

    bash
    jupyter notebook Movie_Recommendation_System.ipynb
    
Input a movie title and get a list of recommended movies.

Future Enhancements
Adding collaborative filtering to improve recommendations based on user behavior.
Integrating a web interface for easy interaction using Flask or Django.
Expanding the dataset for better recommendations.

Contributing
Feel free to submit issues or pull requests. Contributions are always welcome!

