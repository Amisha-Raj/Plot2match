# 🎬 Plot2Match - Content-Based Movie Recommendation System

A content-based movie recommendation system that uses **Sentence Transformers** to understand semantic similarity between movie plot summaries. The system computes embeddings and recommends movies based on how similar their plots are. Built with **Python**, **Flask**, and **NLP techniques**.

## 🔍 Overview

In an age of overwhelming content, helping users discover movies tailored to their preferences is both valuable and challenging. This project aims to address that by leveraging Natural Language Processing (NLP) and sentence embeddings to recommend movies based purely on their plot descriptions—no ratings, genres, or user data required.

Using pre-trained Sentence Transformers, the system converts movie plots into dense vector representations that capture the semantic essence of the content. By applying cosine similarity, it identifies and recommends movies with similar narrative structures and themes.

The goal behind this project was to explore how powerful transformer-based models can be when applied to real-world recommendation problems. It also served as a way to combine ML concepts, NLP, and software development into a full-stack, end-to-end application.

A lightweight Flask web interface wraps the model into an interactive tool where users can type in a movie title and receive a list of semantically similar movies in return.
## 🚀 Features

- 📚 **NLP with Sentence Transformers** – Captures deep semantic meaning of movie plots.
- 🧠 **Content-Based Filtering** – No user ratings or metadata required.
- ⚡ **Cosine Similarity** – Efficient and scalable similarity computation.
- 🌐 **Flask Web App** – User-friendly web interface to interact with the model.
- 🛠️ **Modular Codebase** – Clean, reusable code with clear separation of logic.

## 📊 Tech Stack

- **Python**
- **Sentence Transformers**
- **Flask**
- **Pandas**
- **Sklearn** (for cosine similarity)

## 📁 Project Structure


## 🧪 How It Works

1. **Preprocessing:** Load the movie dataset and clean plot summaries.
2. **Embedding:** Generate sentence embeddings using a pre-trained Sentence Transformer model.
3. **Similarity:** Compute cosine similarity between the input movie plot and others.
4. **Recommendation:** Return the top-N most similar movies.

## 🖥️ Running Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Flask app
python app.py

Then open http://localhost:5000 in your browser.


