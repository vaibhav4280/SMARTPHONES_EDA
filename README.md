
## Smartphone Dataset Exploration

This project performs an in-depth data analysis on a cleaned smartphone dataset using `pandas`, `matplotlib`, and `seaborn`. It explores pricing trends, feature correlations, and brand comparisons through a series of visualizations.

---

### Dataset Description

* **Source** : `Smartphones_cleaned_dataset.csv`
* **Rows** : ~500+ smartphones
* **Columns** :
* Brand, Model, Price, Rating
* Technical specs: RAM, Storage, Battery, Processor, Camera MP, Screen size
* Features: 5G, NFC, IR Blaster, Fast Charging
* Resolution: Width & Height
* Operating System

---

### Key Insights & Visuals

The notebook includes:

1. **Top Brands by Avg Price**
   → Reveals premium vs. budget players
2. **Battery Capacity vs Price**
   → Does battery size influence cost?
3. **Camera MP vs Price**
   → Rear and front camera relationships
4. **RAM & Storage vs Price (Heatmap)**
   → Detect price spikes at spec thresholds
5. **Top Phones by Rating**
   → Highlights highly rated models across price points
6. **Price Distribution by OS**
   → iOS vs Android trends
7. **Fast Charging Impact**
   → Check price and popularity shift
8. **Screen Size vs Resolution**
   → Bigger screens ≠ better resolution?
9. **Specs vs Rating Correlation**
   → Is user satisfaction tied to features?
10. **Brand-wise Feature Distribution**
    → Compare brands across price, battery, screen size

---

### File Structure

```
Smartphone_Analysis.ipynb     # Jupyter notebook with plots & code
Smartphones_cleaned_dataset.csv  # Dataset file
README.md                     # This file
```

---

### Requirements

```
pip install pandas seaborn matplotlib
```

* Python ≥ 3.8
* Jupyter Notebook or VS Code

---

### Future Ideas

* Interactive dashboards with Plotly
* Feature engineering for model building
* Clustering for segmenting phones by usage type

---

```
Let me know if you'd like this converted into a downloadable .md or .ipynb zip file — or if you want to tr
```
