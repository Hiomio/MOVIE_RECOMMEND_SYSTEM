# ENHANCED MOVIE RECOMMENDATION SYSTEM 
Description:
Developed a movie recommendation system using Python, Streamlit, and The Movie Database (TMDb) API. The system recommends movies based on similarity to a selected movie and displays their posters.

Key Features:

User Interface: Built an intuitive and interactive UI using Streamlit for seamless user interaction.
Movie Selection: Users can select a movie from a dropdown menu populated with a list of movies.
Recommendations: Upon selection, the system recommends five similar movies based on cosine similarity.
Poster Display: Fetched and displayed movie posters using TMDb API to enhance user experience.
Technologies Used:

Python: For the core logic and data handling.
Streamlit: For creating the web interface.
TMDb API: For fetching movie posters.
Machine Learning: Utilized cosine similarity for recommending similar movies.
Pickle: For loading pre-trained models and datasets.
Implementation Details:

Data Loading: Loaded movie dataset and similarity matrix using Pickle.
Similarity Calculation: Calculated similarity scores between movies using a pre-trained model.
API Integration: Integrated TMDb API to fetch movie posters dynamically.
UI Components: Used Streamlit components such as selectbox, button, and columns for layout.
Challenges Overcome:

API Integration: Successfully handled API requests and data parsing to fetch and display movie posters.
Performance Optimization: Ensured quick response times by efficiently loading models and datasets.
Outcome:
Created a functional and visually appealing movie recommendation system that enhances user experience by providing relevant movie suggestions along with their posters.

