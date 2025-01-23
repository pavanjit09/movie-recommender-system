# Movie Recommender System

## 📜 Project Description
The Movie Recommender System is a user-friendly web application built with **Streamlit**. It recommends movies based on the user's input and displays related movies along with their posters. This project utilizes a content-based filtering approach to suggest movies similar to the one selected by the user.

## 🚀 Live Demo
Check out the live application: [Movie Recommender System](https://movie-recommender-system-pavanjit.streamlit.app/)

---

## 🗂 Dataset
The dataset used for this project is from Kaggle:  
[TMDB Movie Metadata Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)  
This dataset contains detailed information about 5000 movies, including genres, cast, crew, and keywords, which is utilized to build the similarity model.

---

## 🛠 Technologies Used
1. **Languages/Frameworks**: 
   - Python
   - Streamlit (for building the web app)
2. **Libraries**: 
   - Pandas
   - NumPy
   - Scikit-learn (for similarity calculations)
   - Requests (for fetching movie posters)
3. **Tools**: 
   - Git and GitHub (for version control)
   - Streamlit Community Cloud (for deployment)

---

## 🌟 Features
1. **Movie Search and Recommendation**: 
   - Search for a movie by typing or selecting from a dropdown menu.
   - Displays five similar movies based on content similarity.
2. **Poster Fetching**: 
   - The app fetches high-quality posters for recommended movies using the **TMDB API**.
3. **Interactive UI**: 
   - Beautiful and minimalistic interface built with Streamlit for smooth navigation.

---

## 🧑‍💻 Setup Instructions
To run this project locally, follow the steps below:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/pavanjit09/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

4. **API Key Setup**:
   Replace the placeholder in the code with your TMDB API key:
   ```python
   api_key = "YOUR_API_KEY"
   ```

5. **Run the App**:
   ```bash
   streamlit run app.py
   ```

6. **Access the Application**:
   Open the local server link (e.g., http://localhost:8501) in your browser.

---

## ⚡ Key Challenges Faced
- **Large Model Files**: Managed files like `similarity.pkl` using Git LFS to handle large file sizes efficiently.
- **API Integration**: Integrated TMDB API to fetch real-time movie posters.
- **Deployment**: Deployed the project successfully on Streamlit Community Cloud.

---

## 📈 Future Enhancements
- Add user-based collaborative filtering for personalized recommendations.
- Include advanced filtering options like genres, release year, or popularity.
- Provide trailers or additional movie details fetched from the TMDB API.

---

## 🎥 Demo Video
Check out the demo video on YouTube: [Watch Here](https://youtube.com/shorts/DLDEyS2AVOE?feature=share)
