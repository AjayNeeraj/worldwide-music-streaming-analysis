# 🌍🎵 Worldwide Music Streaming Trends & Insights  

## 📌 Project Overview  
This project explores **global music streaming trends** using real-world data from Kaggle.  
The goal is to **uncover user behavior patterns, identify key engagement metrics, and derive actionable insights** for the music industry.  

---

## 📖 Table of Contents  
- [Dataset Overview](#dataset-overview)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
- [Feature Engineering & Modeling](#feature-engineering--modeling)  
- [Findings & Business Insights](#findings--business-insights)  
- [Project Setup](#project-setup)    
- [Final Deliverables](#final-deliverables)  
- [Future Work](#future-work)  

---

## Dataset Overview  
- **Source:** [Kaggle - Worldwide Music Streaming Trends](https://www.kaggle.com/datasets/atharvasoundankar/global-music-streaming-trends-and-listener-insights)  
- **Size:** 5,000 entries  
- **Key Features:**  
  - `User_ID` (Unique identifier)  
  - `Age`, `Country`, `Streaming Platform`  
  - `Top Genre`, `Most Played Artist`  
  - `Minutes Streamed Per Day`  
  - `Number of Songs Liked`  
  - `Subscription Type`  
  - `Discover Weekly Engagement (%)`  
  - `Repeat Song Rate (%)`  

---

## Exploratory Data Analysis (EDA)  
Key insights and visualizations include:  
✅ **Streams Distribution:** Users streamed music mostly in the afternoon, with peak hours between **3 PM - 8 PM**.  
✅ **Top Songs & Artists:** **Pop and Hip-Hop** dominated the most streamed songs list.  
✅ **Top Regions:** **USA, UK, and India** had the highest streaming activity.  
✅ **Correlation Analysis:**  
  - Higher **Repeat Song Rate (%)** = More songs liked 📈  
  - **Discover Weekly Engagement (%)** has a weak correlation with streaming time.  

📊 **Sample Visualization:**  
![Streams Distribution](https://github.com/AjayNeeraj/worldwide-music-streaming-analysis/blob/main/visualizations/Streams%20Distribution.png)  

---

## Feature Engineering & Modeling  
🔹 **Key Steps Taken:**  
1️⃣ **Data Cleaning & Normalization:** Removed missing values, standardized numerical columns.  
2️⃣ **Feature Selection:** Focused on engagement metrics like **Minutes Streamed Per Day**, **Number of Songs Liked**, and **Repeat Song Rate (%)**.  
3️⃣ **Predictive Modeling (Random Forest Regressor):**  
   - **Goal:** Predict user engagement based on streaming behavior.  
   - **Result:** The model identified **Repeat Song Rate (%)** as the most influential factor.  

---

## Findings & Business Insights  
💡 **For Streaming Platforms:** Prioritize **personalized recommendations** for users with a high **repeat song rate**.  
💡 **For Artists & Labels:** Marketing campaigns should target **peak streaming hours (Afternoon & Evening)**.  
💡 **For Product Teams:** **Subscription-based users** have higher engagement than free-tier users.  

---

## Project Setup  

### 🔹 **Requirements**  
Ensure you have the following installed:  
- Python **3.7+**  
- Jupyter Notebook / Google Colab  
- Required Libraries (Install using `requirements.txt`):  
  ```bash
  pip install -r requirements.txt
  ```

### 🔹 **Steps to Run the Project**  
```bash
# Clone the repository
git clone https://github.com/AjayNeeraj/worldwide-music-streaming-analysis.git
cd worldwide-music-streaming-analysis

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
```

---

## Final Deliverables  
📁 `notebooks/music_streaming_analysis.ipynb` – Jupyter Notebook with full analysis.  
📁 `data/worldwide_music_streaming` – Raw dataset.  
📁 `data/cleaned_music_data.csv` – Preprocessed dataset.  
📁 `visualizations/` – All graphs and charts.  

---

## Future Work  
- 📌 **Improve the model** by testing **other algorithms** (e.g., XGBoost, LSTM).  
- 📌 **Expand dataset size** to analyze more granular trends.  
- 📌 **Deploy as an interactive dashboard** (Streamlit or Flask).  

---

## 🤝 Contributing  
Contributions are welcome! If you have ideas for improvements, feel free to open an **issue** or submit a **pull request**.  

---
