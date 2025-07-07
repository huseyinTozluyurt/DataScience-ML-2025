# 🦴 Skeletal Variation in Vertebrates

This project analyzes the variation in **neck vertebrae (cervical bones)** across different vertebrate groups — primarily focusing on **birds** and **mammals**. It explores biological constraints, anatomical diversity, and evolutionary implications behind the distribution of neck bones among species.

---

## 📁 Project Structure

- `skeletal-variation.ipynb` – Main Jupyter notebook with code, visualizations, and results
- `adult-human-skeleton.csv` – Dataset on human skeletal anatomy
- `bird-neck-bones.csv` – Vertebrae count data for 80+ bird species
- `mammal-neck-bones.csv` – Vertebrae count data for various mammals
- `README.txt` – Data sources and DOI references for all species

---

## 🧪 Key Tasks and Analyses

### ✅ Task 1: Dataset Summary
- Counts rows and columns in each dataset
- Identifies unique species or anatomical regions

### ✅ Task 2: Frequency of Vertebrae Counts
- Uses `value_counts()` to display how often each neck count appears

### ✅ Task 3: Visual Distributions
- Histograms of neck vertebrae for birds and mammals
- Identifies general trends and ranges

### ✅ Task 4 & 5: Descriptive Statistics & Coefficient of Variation
- Computes mean, standard deviation, and coefficient of variation (CV) for each group

### ✅ Task 6: Flying vs Flightless Birds
- Adds a `flight` column to label species
- Compares vertebrae variation between flying and non-flying birds

### ✅ Task 7: Statistical Comparison
- Performs **t-test** between birds and mammals
- Assesses whether their neck vertebrae counts differ significantly

### ✅ Task 8: Outlier Detection
- Identifies anatomical outliers using the **IQR method**
- Flags unusually high or low vertebrae counts

### ✅ Task 9: Group Comparison (Birds vs Mammals)
- Combines datasets with group labels
- Visualized using boxplots and violin plots

---

## 📊 Example Visualizations

- 📦 Boxplots comparing birds and mammals
- 📈 Histograms for flying vs. flightless birds
- 🎻 Violin plots showing distribution shapes

---

## 📚 Data Sources

Bird and mammal vertebrae counts are sourced from:
- Williams et al., *Nature Ecology & Evolution* (2019)
- DOIs provided per species in `README.txt`

---

## 🚀 Technologies Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook / Google Colab
- Statistical libraries: `scipy.stats`

---

## 💡 Biological Insights

- Most mammals have exactly **7 cervical vertebrae**, regardless of size or function.
- Birds show **greater variation** (typically 10–25), likely due to neck flexibility demands.
- Flightless birds may have slightly different distributions than flying birds.
- Variation supports the idea of **developmental constraints** vs. **adaptive specialization**.

---

## 🧠 Future Directions

- Add human data for full tri-group comparison
- Explore correlation with body length, flight style, or feeding behavior
- Extend to reptiles or aquatic vertebrates

---

> 🧠 This project was inspired by a data science course material of Cisco Netacad Academy.

## 🙌 Acknowledgements

Thanks to the authors of the cited datasets and studies, and to open-access biodiversity data repositories.

---


