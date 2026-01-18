# Crop Statistics – Group Project

Short group project for the MSc Spatial Engineering  
University of Twente – ITC Faculty

---

## Project structure
Crop-_tatistics-/
│
├── notebooks/
│ ├── 01_data.ipynb
│ ├── 02_transformation.ipynb
│ ├── 03_analysis.ipynb
│ └── 04_results.ipynb
│
├── data/ # small input data only
├── outputs/ # figures and result tables
├── LICENSE
└── README.md


---

---

## Workflow (important)

All Git commands must be executed **in the CRIB terminal**  
(**not inside notebook cells**).

---

### 1️⃣ Clone the repository on CRIB

```bash
cd ~
mkdir -p projects
cd projects

git clone https://github.com/kilianodonell-cmd/Crop-_tatistics-.git
cd Crop-_tatistics-

2️⃣ Working with notebooks

All work is done inside the notebooks/ folder.

Each group member mainly works on one notebook:

01_data.ipynb – data loading and inspection

02_transformation.ipynb – transformations and aggregation

03_analysis.ipynb – statistical analysis

04_results.ipynb – final plots and interpretation

3️⃣ Before starting work

Run in the CRIB terminal:

git pull

4️⃣ After finishing work

Save your notebook and then run in the CRIB terminal:

git add notebooks/<your_notebook>.ipynb
git commit -m "short description of your changes"
git push


