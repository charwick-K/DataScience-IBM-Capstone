# 🚀 SpaceX Launch Records Dashboard

This project is a Python-based interactive dashboard built using [Dash](https://dash.plotly.com/) and [Plotly Express](https://plotly.com/python/plotly-express/) to explore and visualize the launch records of SpaceX. It provides intuitive visualizations to assess launch site performance and payload correlations with success rates.

## 📁 Project Structure

- `spacex_launch_dash.csv`: Dataset containing SpaceX launch data
- `app.py`: Main dashboard application script
- `README.md`: Documentation and usage instructions

## 📊 Features

- **Dropdown Filter** for selecting specific launch sites or viewing all launch data
- **Pie Chart** showing:
  - Total successful launches across all sites
  - Success vs. failure rates for selected sites
- **Payload Range Slider** to filter launches by payload mass
- **Scatter Plot** visualizing the correlation between payload size and launch success

## 🔧 Technologies Used

- Python 🐍
- Pandas for data manipulation
- Dash for building the web app
- Plotly Express for interactive visualizations

## 🚀 Getting Started

### Prerequisites

Make sure you have the following Python libraries installed:

```bash
pip install pandas dash plotly
```

### Running the App

1. Place `spacex_launch_dash.csv` in the same directory as `app.py`.
2. Run the app:

```bash
python app.py
```

3. Open a browser and navigate to `http://127.0.0.1:8050/`.

## 📌 Notes

- The pie chart dynamically adjusts based on the selected launch site.
- The payload slider filters both pie chart and scatter plot results.
- Hovering over points in the scatter plot reveals additional launch data.

## 🙌 Credits

Developed using:
- [Dash by Plotly](https://dash.plotly.com/)
- [SpaceX launch dataset](https://www.kaggle.com/datasets)

---

Would you like help adding screenshots or deploying this dashboard online?
