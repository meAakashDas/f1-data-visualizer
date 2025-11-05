# F1 Data Visualizer

A Streamlit-powered dashboard for exploring Formula 1 race data from **2015 to 2024**. Visualize driver & constructor performance, podium finishes, and get a data-driven prediction for the **2025 season** — all offline with no internet required!

## 📊 Features

- **Driver Performance**: Top 6 drivers' points over time (2015–2024)
- **Constructor Trends**: Points evolution for top teams
- **Podium Heatmap**: Top 10 drivers’ 1st, 2nd, and 3rd place finishes
- **Interactive Chart**: Hover-enabled Plotly line chart for constructors
- **2025 Prediction**: Projected top 3 drivers based on 2020–2024 average points per race

## 🛠️ Requirements

- Python 3.8+
- Required packages:
  ```bash
  streamlit pandas matplotlib seaborn plotly
  ```

## 🚀 Quick Start

1. **Clone or download** this repository.
2. Place your F1 dataset as `f1_data_2015_2024.csv` in the same folder as `f1_visualizer.py`.  
   *(Expected columns: `driver`, `constructor`, `year`, `position`, `points`)*
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(If no `requirements.txt`, run: `pip install streamlit pandas matplotlib seaborn plotly`)*
4. Run the app:
   ```bash
   streamlit run f1_visualizer.py
   ```
5. Open the displayed URL in your browser (usually `http://localhost:8501`).

## 📁 File Structure

```
f1-visualizer/
├── f1_visualizer.py        # Main Streamlit app
├── f1_data_2015_2024.csv   # Your F1 dataset (required)
└── README.md
```

## 📝 Notes

- The app works **entirely offline** — no API calls or live data.
- Ensure your CSV has the correct column names and covers 2015–2024.
- The 2025 prediction assumes 20 races and stable driver performance.

---

🎯 Built with **Python**, **Streamlit**, **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.  
🎓 Perfect for F1 fans, data enthusiasts, and storytelling with real-world sports data!
