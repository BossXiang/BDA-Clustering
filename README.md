# Final-Project-Big-Data

This repository contains the code and sample data used to demonstrate our face verification system, including encrypted inference using Tom, Liz, Winter, and 99 as subjects. The system performs identity verification and rejection using facial embeddings.

---

## 📂 Project Structure

```
.
├── public_data.csv           # Public data (4D)
├── private_data.csv          # Private data (6D)
├── Clustering.ipynb          # Main code for clustering
├── public_submission.csv     # My clustering result of the public data (4D)
├── private_submission.csv    # My clustering result of the private data (6D)
└── README.md
```

---

## Reproduction

### 1. Load the notebook onto Google Colab

### 2. Prepare the Data

Upload and place the `public_data.csv` and `private_data.csv` into your working directory:

### 3. Open `Clustering.ipynb` and execute the cells from the top to the bottom

It will automatically generate and download:
- `public_submission.csv`
- `private_submission.csv`
