
# 🎬 MovieIQ - Predictive Analytics on Film Success

Live Demo
🚀 https://movieiq-predictive-analytics-on-film-success-hkz386d9xzv5mygjz.streamlit.app/

# 📊 Key Features
🎯 Predicts whether a movie is likely to be successful (Revenue > Budget)
📈 Visual insights using Seaborn & Matplotlib (Budget vs Revenue, Genre Trends)
📊 T-Test and Chi-Square statistical tests
🤖 Random Forest Classifier for success prediction
🧠 Interactive filtering by genre and vote average via sidebar
🧼 Clean, modular dashboard ready for deployment

# 🧰 Tech Stack
Python 🐍
Pandas, NumPy
Seaborn, Matplotlib
Scikit-learn
Streamlit
SciPy

# 🚀 Run Locally
1. Clone the repository
git clone https://github.com/nv2105/MovieIQ-Predictive-Analytics-on-Film-Success.git
cd MovieIQ-Predictive-Analytics-on-Film-Success
 
2. Install dependencies
pip install -r requirements.txt
3. Run the app
streamlit run MovieIQ.py

# 📁 Dataset
Make sure the project includes a movies.csv file with the following columns:
 budget, revenue, popularity, runtime, vote_average, title, genres
