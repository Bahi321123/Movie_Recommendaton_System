# Movie_Recommendaton_System
# 🎬 Movie Recommendation System

**About**
This is a small student project that recommends movies based on content (genres & text).  
I built it to learn how recommender systems work and to practice cleaning real datasets.

***

## **Why I made this**
I wanted to understand how services like Netflix suggest “similar” movies.  
This project helped me learn TF-IDF, cosine similarity, and how to make a simple interactive demo in Colab.

***

## **Features**
- **Content-based** recommendations using movie genres / descriptions  
- Interactive UI in Google Colab (text input or dropdown)  
- Uses the public **MovieLens (ml-latest-small)** dataset  
- Exports recommendations to CSV

***

## **Technologies**
- **Python 3.x**  
- **pandas**, **numpy**  
- **scikit-learn** (TfidfVectorizer, cosine_similarity)  
- **ipywidgets** (for Colab UI)

***

## **How to run (quick)**
1. Open the notebook in **Google Colab** (recommended).  
2. Run **all cells** in order — the notebook downloads the MovieLens dataset automatically.  
3. Use the text box or dropdown to select a movie and click **Get Recommendations**.

**Or run locally:**
```bash
# install deps
pip install pandas numpy scikit-learn ipywidgets

# run the notebook with Jupyter
jupyter notebook movie_recommender.ipynb


#u can mail me on bahijangra@gmail.com for queries(Sahil)
