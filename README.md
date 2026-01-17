# 📺 Aadhan Channel Performance Dashboard

This is a Streamlit-based interactive dashboard to analyze and benchmark the performance of Telugu digital media channels based on viewership data.

The application allows users to filter data by **platform** and **year**, and provides insights such as total views, average monthly views, channel rankings, and performance categories.

---

## 🚀 Features

- Platform-wise and year-wise filtering using sidebar controls
- Channel-level performance benchmarking
- Automatic ranking of channels based on total views
- Performance categorization:
  - Top Performer
  - Mid Performer
  - Low Performer
- Key metrics display:
  - Total number of channels
  - Total views
  - Top-performing channel
- Interactive data table
- Bar chart visualization with value labels


---

## 📊 Dataset

The application uses an Excel file:
Expected columns in the dataset:
- `platform`
- `year`
- `channel`
- `no. of views`

> Note: Ensure the Excel file is present in the root project directory or update the file path accordingly.

---

## How to Run Locally

1. Install dependencies:
```bash
pip install -r requirements.txt
