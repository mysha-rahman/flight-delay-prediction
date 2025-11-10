# Flight Crew - Flight Delay Prediction

Big Data project using PySpark to predict flight delays using U.S. DOT On-Time Performance data.

## Team Members
- Mysha Rahman
- Milton La
- Devin Charles
- Tanush Rai
- Maximilian Menninga
- Timilehin Balogun

## Dataset
Kaggle Airline Dataset for preliminary testing before scaling to full U.S. DOT data.

## Project Structure
- `data/` - Dataset storage (not committed to git)
- `notebooks/` - Jupyter notebooks for exploration
- `src/` - PySpark pipeline scripts
- `visualizations/` - Charts and plots
- `docs/` - Documentation and reports

## Setup Instructions for Team Members

### 1. Clone the Repository
```bash
git clone https://github.com/mysha-rahman/flight-delay-prediction.git
cd flight-delay-prediction
```

### 2. Download the Dataset
Download the Kaggle Airline Dataset from:
https://www.kaggle.com/datasets/iamsouravbanerjee/airline-dataset

Place the CSV file in: `data/raw/Airline Dataset.csv`

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Verify Setup
The `data/raw/` folder should contain the CSV but it won't be tracked by Git (this is intentional).