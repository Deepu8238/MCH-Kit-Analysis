# Healthcare Kits Distribution Analysis Dashboard

A Streamlit dashboard analyzing the distribution of healthcare kits to pregnant women in Telangana.

## 🚀 Demo
Access the live dashboard [here](https://your-streamlit-url)

## 📊 Features
- District-wise registration analysis
- ANC visit tracking
- Kit distribution statistics
- Delivery count visualization
- Interactive data explorer

## 🛠️ Installation & Running Locally
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the dashboard:
   ```bash
   streamlit run healthcare.py
   ```

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
