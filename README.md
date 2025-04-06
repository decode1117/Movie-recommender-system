# 🎬 Movie Recommendation System

A smart and simple movie recommendation engine built using **Python** and **AI/ML techniques**. This project suggests movies based on user preferences using **content-based filtering** and **cosine similarity**.

## 🚀 Features

- Recommends movies based on title similarity
- Uses TF-IDF Vectorizer and Cosine Similarity
- Clean and modular Python code
- Easy to integrate with frontend/UI
- Fast and efficient results

## 🛠 Tech Stack

- Python
- Pandas, NumPy – Data manipulation
- Scikit-learn – Machine learning (TF-IDF & Cosine Similarity)
- Streamlit (optional) – For interactive UI (if you used it)

## 📁 Project Structure

```
📦 movie-recommendation-system/
 ┣ 📜 movies.csv
 ┣ 📜 app.py
 ┣ 📜 recommendation.py
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

## 📈 How It Works

1. The dataset (`movies.csv`) contains metadata like title, genre, and description.
2. We use **TF-IDF Vectorizer** to convert movie descriptions into numeric vectors.
3. **Cosine Similarity** helps find movies that are closest in context to the one the user selects.
4. The top similar movies are recommended.

## 🧪 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

> You can also add a frontend using Streamlit or Flask for a better user experience.

## 💡 Example

**Input:** `Inception`  
**Output:** `Interstellar`, `Shutter Island`, `The Prestige`, etc.

## 📚 Dataset

Used a custom or publicly available movie dataset with features like:
- Title
- Genres
- Overview/Plot
- Tags

## 🤝 Contributions

Feel free to fork the repo, submit issues, or open pull requests. All kinds of contributions are welcome!

## 📬 Contact

Created with ❤️ by YASHIKA BHATIA AND DEV VASHIST
Connect on LinkedIn (www.linkedin.com/in/yashika-bhatia-949560289) (https://www.linkedin.com/in/dev-vashist-063585286)

---

Let me know if you want me to generate a `requirements.txt` file or if you’d like to include screenshots or a demo video link too!
