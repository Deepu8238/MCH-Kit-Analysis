# Mother and Child Health Kit Analysis Dashboard

A Streamlit dashboard for analyzing Mother and Child Health Kit distribution and related health metrics.

## Setup
1. Clone the repository
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run healthcare.py
   ```

## Features
- Key metrics overview
- Registration trends by district
- ANC visit analysis
- Geographical distribution of kits
- Interactive data explorer

## 📁 Project Structure
- `healthcare.py`: Main dashboard application
- `deepu.csv`: Dataset containing healthcare distribution data
- `requirements.txt`: Project dependencies
- `packages.txt`: System dependencies

## 📝 Data Format
The dashboard expects a CSV file with the following columns:
- districtName
- mandalName
- villageName
- pwRegCnt
- anc1Cnt, anc2Cnt, anc3Cnt, anc4Cnt
- kitsCnt
- delCnt 
