👋 Hi, I'm Srihari Mohan

Data Science Master's student focused on the less glamorous end of data science: clean pipelines, well-structured databases, and models that hold up outside the training set. I like taking messy raw data and turning it into something a database or a model can actually use.
📍 Based in Hatfield, UK (open to relocation) 💼 Actively looking for Graduate/Junior Data Analyst, Data Scientist, and Analytics Engineer roles 🔗 Connect with me on LinkedIn

🛠️ Technical Stack
Languages & Frameworks: Python (Pandas, NumPy, scikit-learn), SQL, SAS
Data Architecture: Relational star-schema design, ETL pipelines, SQLite, cross-platform path handling (os)
Advanced Querying: SQL window functions (OVER, PARTITION BY, LAG), rolling/moving aggregations
Machine Learning: Regression, clustering (K-means), cross-validation, grid search, model evaluation (R², silhouette score, ROC-AUC)
Visualization: Matplotlib, Seaborn, Streamlit
Tools: Git, GitHub

🚀 Featured Projects
📊 AIVU: Football Analytics Engine
A Streamlit app that tracks players' match-by-match form and projects next-gameweek performance.
Built an automated Python ETL pipeline that cleans raw match-log files and loads them into a relational star-schema SQLite database.
Used SQL window functions (PARTITION BY, LAG) to engineer rolling 3-week form features (xG, xA) as the model's core inputs.
Trained and grid-searched the prediction model with cross-validation to keep it honest against overfitting.
In progress: extending the data layer to pull live match data from StatsBomb's open data, aiming for a real-time analytics dashboard.

📈 Premier League Match Prediction using ML Models
Comparing graph-based (spectral) clustering and K-means clustering on Premier League player data to group players by playing style and performance level.
Preprocessed the dataset (missing-value handling, feature selection, PCA for dimensionality reduction).
Used the elbow method to select K=3 clusters, then compared cluster quality between the two methods via silhouette score.

🎬 Movie Revenue: Clustering & Regression
A linear regression model predicting box-office revenue from critic and audience metrics (metascore, vote count, user score), reaching an R² of 0.85, paired with K-means clustering to group movies by financial and reception metrics.

More projects, including a semantic image segmentation model (U-Net + EfficientNet-b0) and time-series analysis of airline passenger data, are pinned below.
