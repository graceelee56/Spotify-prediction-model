This project analyzes a Spotify dataset to explore how audio features (such as danceability, energy, valence, and tempo) relate to track popularity. The goal is to apply data cleaning, exploratory data analysis (EDA), and machine learning techniques to predict whether a song will be popular based on its characteristics.
Objectives: 
- Understand correlations among Spotify audio features.
- Visualize distributions and trends across genres and popularity levels.
- Build classification models (e.g., Logistic Regression, Random Forest, XGBoost) to predict track popularity.
- Compare model performances using metrics
- Interpret feature importance to identify what makes a song popular.

Technologies Used:
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn, XGBoost
- Jupyter Notebook

Results: 
Best Model = stacked model with an accuracy of 75%. We see that while some genres achieve accuracies of almost 100% like salsa or samba, others perform very poorly around 50% like synth-pop or reggae.
Top predictive features  = Our Random Forest analysis shows that track duration is the strongest driver of a song’s popularity, with the explicit label coming in a close second. Danceability and energy also rank highly, followed by musical attributes like key, loudness, and mode. We can also conclude that genre plays an important role.

