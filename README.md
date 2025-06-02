# ✈️ Visualising flight data in Tableau 🌍 <br>

**Libraries:** `scipy`, `seaborn`, `matplotlib`, `geopandas`, `pandas`, `numpy` <br>
**Dataset:** [Flights to Italy](https://www.kaggle.com/datasets/davidpbriggs/flights-to-italy)

Python 🐍 was used for exploratory data analysis (EDA) and preprocessing of GPS tracking data from over 100 flights, followed by interactive dashboard visualisation in Tableau.

### 🧠 Methodology:
 - Used `numpy` to compute flight distances via the **Haversine formula**
 - Used  `scipy.spatial.cKDTree` for efficient identification of departure/arrival airports
 - Used `geopandas` to map flight paths and overlay tracking data

### 💡 Key Insights: <br>
 - 🕒 **200+ hours** spent in the air (from tracking timestamps) <br>
 - 🚀 **100,000 airmiles** - nearly halfway to the Moon <br>
 - 📍 Identified **4 "motorways in the sky"** connecting London and Rome <br>

### 🔗 Project Resources: <br>
📖 Jupyter Notebook: [GitHub](https://github.com/dpb24/flights-to-italy/blob/main/notebooks/notebook-flights-to-italy.ipynb) | [Kaggle](https://www.kaggle.com/code/davidpbriggs/notebook-flights-to-italy) <br>
📊 Interactive Dashboard: [Tableau](https://public.tableau.com/app/profile/david.briggs6120/viz/FlightstoItaly/Dashboard1) <br>

<div style="text-align: center;">
    <a href="https://public.tableau.com/app/profile/david.briggs6120/viz/FlightstoItaly/Dashboard1" target="_blank" rel="noopener noreferrer">
        <img src="visuals/Dashboard 1.png" width="1000" alt="Flight to Italy Tableau Dashboard">
    </a>
</div>
