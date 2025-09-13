
# Movie Recommendation System
=======
## 🎬 Implementation Details

This Movie Recommendation System is built using the **MovieLens dataset** and integrates with the **TMDB API** to fetch movie overviews and additional links.  

## Installation
pip install pandas numpy scikit-learn requests ipython

### ⚙️ Steps Involved
1. **📂 Data Preparation**  
   - Loaded datasets (`movies.csv`, `ratings.csv`, `links.csv`) from MovieLens.  
   - Cleaned and merged them to create a single dataset containing titles, genres, ratings, and external IDs (TMDB, IMDb, MovieLens).  

2. **🧠 Content-Based Filtering**  
   - Used **TF-IDF Vectorization** on movie genres and descriptions.  
   - Applied **Cosine Similarity** to measure closeness between movies.  

3. **⭐ Ratings Boost**  
   - Computed average ratings per movie.  
   - Recommendations are sorted not only by similarity but also boosted by higher ratings.  

4. **🌐 TMDB API Integration**  
   - For each recommended movie, fetched the **overview** and provided a **direct TMDB link**.  
   - Also generated **IMDb** and **MovieLens** links for user convenience.  

5. **💡 Interactive Input**  
   - The system accepts user input for either a **movie title** (e.g., `Toy Story`) or a **genre** (e.g., `Comedy`, `Action`).  
   - Based on this input, the system displays the **top N recommended movies** with:  
     - 🎥 Title  
     - 🎭 Genres  
     - ⭐ Average Rating  
     - 📝 Overview  
     - 🔗 Clickable links to **TMDB**, **IMDb**, and **MovieLens**  

---

✅ This project combines **content-based recommendation techniques** with **real-world API integration**, creating an **interactive and practical movie recommendation system**.

