# 🎬 Netflix 90s Movie Analysis

An exploratory data analysis (EDA) of Netflix movies from the **1990s**, using Python. Dives into movie durations, genres, and short-film trends from one of cinema's most iconic decades.

## 📊 What This Project Covers

- Filtering Netflix data to isolate movies released between 1990–1999
- Visualizing movie duration distribution with a histogram
- Identifying short Action movies (under 90 minutes) from the 90s

## 🗂️ Project Structure

```
├── notebook.ipynb       # Main analysis notebook
├── netflix_data.csv     # Dataset
├── requirements.txt     # Python dependencies
└── README.md
```

## 📁 Dataset

The dataset (`netflix_data.csv`) contains Netflix titles with the following fields:

| Column | Description |
|--------|-------------|
| `show_id` | Unique ID of the show |
| `type` | Movie or TV Show |
| `title` | Title of the show |
| `director` | Director |
| `cast` | Cast members |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of release |
| `duration` | Duration in minutes |
| `description` | Short description |
| `genre` | Genre |

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/your-username/netflix-90s-eda.git
cd netflix-90s-eda
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Launch the notebook**
```bash
jupyter notebook notebook.ipynb
```

## 🛠️ Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- jupyter

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
