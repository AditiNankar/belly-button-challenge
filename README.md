# 🧬 Belly Button Biodiversity Dashboard

## 📖 Overview

This interactive dashboard visualizes data from the **Belly Button Biodiversity** study, which catalogs the microbial species—called operational taxonomic units (OTUs)—that inhabit human navels.

Using JavaScript, D3.js, and Plotly.js, this dashboard allows users to:
- Explore demographic metadata
- View the top 10 OTUs found in individual belly buttons
- Interact with a bubble chart that reveals the full spectrum of microbial data for each subject

The data comes from a research study and is publicly available via JSON. This dashboard was built as part of the Module 14 Challenge in the Data Analytics Boot Camp.
---

## 🔧 Technologies Used

- **JavaScript**
- **D3.js** (Data-Driven Documents)
- **Plotly.js** (for dynamic charts)
- **HTML/CSS**
- **GitHub Pages** (for deployment)

---

## 📊 Visualizations

### 1. Bar Chart

Displays the top 10 OTUs for a selected individual.

- X-axis: `sample_values`
- Y-axis: `otu_ids` (formatted as `OTU {id}`)
- Hover text: `otu_labels`
- Sorted descending by abundance

### 2. Bubble Chart

Represents each OTU found in a subject’s sample.

- X-axis: `otu_ids`
- Y-axis: `sample_values`
- Marker size: `sample_values`
- Marker color: `otu_ids`
- Hover text: `otu_labels`

### 3. Demographic Info Panel

Displays the selected individual's metadata:
- ID, ethnicity, gender, age, location, bbtype, wfreq, etc.
- Automatically updates when a new sample is selected

---

## 📌 Features

- Responsive dropdown menu to select a test subject ID
- All charts and demographic info update dynamically
- Clean and intuitive layout with optional CSS customization
- Deployment to GitHub Pages for free public hosting

---

## 🛠️ Setup Instructions

To run this project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/belly-button-challenge.git
   cd belly-button-challenge

---

## 🧑‍💻 Author

Aditi Nankar
Data Visualization Developer | Aspiring Bioinformatics Analyst
