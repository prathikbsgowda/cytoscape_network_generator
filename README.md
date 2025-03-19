# Kinase-Substrate Network Visualization



## 🚀 Overview
This project provides a web-based interface for visualizing kinase-substrate networks using **Cytoscape.js**. Users can upload data files to generate interactive network graphs and download the visualizations as **PNG or JPG** images.

## 🔥 Features
- 📂 Upload data files to generate network graphs.
- 📊 Interactive graph visualization with **Cytoscape.js**.
- 📥 Download generated graphs as **PNG or JPG** images.
- 🎨 User-friendly interface with styled controls.

## 📄 Data Format
The data file should be in a **tab-delimited format** with two columns: **kinase** and **substrates**. Each row represents a kinase and its corresponding substrates. Substrates should be **separated by semicolons**.

### 📌 Example Data
| Kinase | Substrates |
|--------|------------|
| AKT1   | ABLIM1_S455; ABLIM3_S372; AFAP1_S277; AFDN_S1083; AGO2_S387 |
| EGFR   | DNAJC5_Y17; EGFR_Y1172; MAPK14_Y182; TNS3_Y780; YES1_Y426 |
| MAPK1  | ARAF_S373; BRAF_S365; CRAF_S338; MEK1_S218; MEK2_S222 |

## 📖 Usage
1. Open the **HTML file** in a web browser.
2. Click the **"Choose File"** button to upload a data file (e.g., Excel file).
3. Once the graph is generated, the **download buttons** will appear.
4. Click **"Download PNG"** or **"Download JPG"** to save the graph as an image.

## 🛠 Dependencies
- **Cytoscape.js**: For graph visualization.
- **XLSX**: For reading Excel files.
- **FileSaver.js**: For saving files.

## ⚠ Notes
- ✅ Ensure that the **data file is in the correct format** for proper graph generation.
- ✅ The interface is designed to be **user-friendly and responsive**.

