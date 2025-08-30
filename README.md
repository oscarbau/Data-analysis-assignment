# Data Science Project: Agricultural Survey Analysis

Welcome to this **Data Science project** focused on agricultural survey analysis, data enrichment, and predictive modeling. This repository is structured to provide a **complete end-to-end workflow**, from raw data processing to advanced visualization and spatial modeling.  

---

## 📁 Project Structure

### 1. `Data/`
This folder contains all the data used in the project:  

- **Raw survey files**: Original datasets collected from field surveys.  
- **Cleaned datasets (`Data/cleaned/`)**: Processed and standardized files ready for analysis:
  - `main_std.csv` – Main survey dataset standardized.
  - `manure_std_cons.csv` – Consolidated manure/fertilizer dataset.
  - `merged_std_all.csv` – Fully merged dataset with all variables.
  - `merged_std.csv` – Partial merged dataset for intermediate analysis.

- **Spatial files (`Data/spatial/`)**: Geospatial datasets generated or used during the analysis.

---

### 2. `Jupyter-notebooks/`
A series of sequential notebooks to explore, enrich, model, and visualize the data:

1. **`1_descriptive_stats_main.ipynb`** – Explore and summarize the main dataset.  
2. **`2_descriptive_stats_manure.ipynb`** – Inspect and summarize manure/fertilizer datasets.  
3. **`3_descriptive_stats_merged.ipynb`** – Analyze the merged datasets for integrated insights.  
4. **`4_data_enrichment.ipynb`** – Enhance datasets with external sources, including satellite imagery and geospatial data.  
5. **`5_spatial_model.ipynb`** – Build predictive and spatial models using enriched datasets.  
6. **`6_data_visualization.ipynb`** – Generate comprehensive visualizations to communicate insights effectively.

> 💡 **Tip:** Run the notebooks sequentially for a smooth workflow, starting from loading and inspecting the datasets to modeling and visualization.

---

## 🔍 Project Workflow

1. **Load and clean data** – Start by inspecting the raw survey data.  
2. **Explore descriptive statistics** – Understand distributions, correlations, and key trends in each dataset. Clean each dataset iterativelly.  
3. **Merge datasets** – Combine the survey cleaned datasets for integrated analysis.  
4. **Data enrichment** – Add external information such as satellite imagery or geospatial features.
5. **Modeling** – Build predictive models and spatial analyses to derive actionable insights.  
6. **Visualization** – Create compelling charts, maps, and interactive plots to communicate results clearly.  

---

## 🚀 Get Started

Clone this repository and start exploring the notebooks sequentially. Each notebook is **self-contained** and explains the steps clearly, making it easy to follow for both beginners and advanced users.

```bash
git clone <https://github.com/oscarbau/Data-analysis-assignment.git>

