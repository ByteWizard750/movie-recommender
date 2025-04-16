# Movie Recommender System

This project is a Movie Recommender System built with Python, leveraging machine learning techniques to suggest movies based on user input. It uses the movie dataset from
TMDB (The Movie Database) and a content-based filtering approach, which recommends movies that are similar to the ones you like. The system uses a combination of movie metadata, 
including genres, tags, and overviews, to make recommendations.

Features
	•	Movie Recommendations: Based on the movie you select, it recommends similar movies.
	•	Interactive Interface: A user-friendly interface built with Gradio to interact with the system.
	•	5000 Movies: The dataset contains information about over 5000 movies, making the recommendations highly diverse.
	•	Easy Setup: The app is simple to set up and use with minimal dependencies.

Technologies Used
	•	Python: Core programming language.
	•	Pandas: Data manipulation and analysis.
	•	Scikit-learn: For machine learning algorithms.
	•	Gradio: To create the interactive user interface.
	•	Pickle: To save and load the model and datasets.

Project Setup

	1.	Clone the Repository:
To get started, clone this repository to your local machine:

git clone https://github.com/<your-username>/movie-recommender.git

	2.	Install Dependencies:
You can install the required dependencies using pip. Run this command inside your project directory:

pip install -r requirements.txt

If you’re using Google Colab, you can simply install dependencies directly from the notebook:

!pip install -r requirements.txt

	3.	Download the Datasets:
You’ll need the following datasets to run the project:
	•	TMDB 5000 Movies Dataset
	•	TMDB 5000 Movie Credits Dataset
After downloading, upload the files to your Google Drive or local directory.
	4.	Run the Notebook:
Open the Movie_Recommendation_System.ipynb in Jupyter or Colab, and run all cells. This will load the model, preprocess the data, and launch the Gradio interface.

!python movie_recommendation_system.py

	5.	Start the Interface:
When you run the script or Jupyter notebook, a Gradio interface will appear. You can select a movie from the dropdown, and the system will recommend similar movies.

Example Usage
	1.	Select a Movie:
Choose a movie from the dropdown menu.
	2.	Receive Recommendations:
The system will display a list of recommended movies with their posters and names based on the movie you selected.
	3.	Explore More:
Click on the movie posters to learn more or watch trailers.

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/5caa4b52-136d-453e-bb89-01915fdc53aa" />
