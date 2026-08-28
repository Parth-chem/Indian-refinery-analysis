# Indian Refinery Analysis

A comprehensive data analysis project examining crude oil processing trends across Indian refineries from 1998-99 to the present, with forecasts through 2026-27.

## 📋 Overview

This project analyzes historical and projected crude oil processing volumes across major oil refineries in India. The analysis includes data from leading petroleum companies including IOCL, HPCL, BPCL, CPCL, ONGC, MRPL, and RIL (Reliance Industries Limited), with refineries distributed across multiple states.

## 📊 Dataset

**Source:** Petroleum Planning & Analysis Cell

**Data Period:** 1998-99 to 2026-27 (Till June)
- Historical data: 1998-99 to 2024-25
- Projected data: 2025-26 and 2026-27

**Units:** '000 Metric Tonnes

**File:** `PT_crude_processing.xlsx`

## 🏭 Coverage

### Companies Covered:
- **IOCL** (Indian Oil Corporation Ltd.) - 9 refineries
- **HPCL** (Hindustan Petroleum Corporation Limited) - 2 refineries
- **BPCL** (Bharat Petroleum Corporation Limited) - 3 refineries
- **CPCL** (Chevron Phillips Chemical) - 2 refineries
- **ONGC/MRPL** (Oil and Natural Gas Corporation/Mangalore Refinery and Petrochemicals Ltd.) - 2 refineries
- **RIL** (Reliance Industries Limited) - 2 refineries

### States Represented:
Gujarat, Maharashtra, Tamil Nadu, Uttar Pradesh, West Bengal, Andhra Pradesh, Karnataka, Haryana, Bihar, Assam, Odisha, and Kerala

## 📁 Project Structure

```
Indian-refinery-analysis/
├── README.md                          # This file
├── India_Crude_Analytics.ipynb       # Main Jupyter notebook with analysis
└── PT_crude_processing.xlsx          # Raw data file
```

## 🔍 Analysis Highlights

The Jupyter notebook includes:
- Data loading and exploratory analysis
- Refinery identification and company classification
- Geographic mapping of refineries by state
- Temporal trend analysis (1998-99 to present)
- Future projections (2025-26 onwards)
- Data cleaning and preparation for insights

### Key Analysis Steps:
1. Load data from Excel with multiple sheets
2. Extract and organize crude oil processing data
3. Classify refineries by parent company
4. Map refineries to geographic locations (states)
5. Clean refinery names and format data
6. Generate insights on processing trends

## 📊 Major Refineries Tracked

### IOCL Refineries:
- Koyali, Gujarat
- Mathura, Uttar Pradesh
- Panipat, Haryana
- Haldia, West Bengal
- Barauni, Bihar
- Digboi, Assam
- Guwahati, Assam
- Bongaigaon, Assam
- Paradip, Odisha

### Other Key Refineries:
- HPCL: Mumbai (Maharashtra), Visakh (Andhra Pradesh)
- BPCL: Mumbai (Maharashtra), Kochi (Kerala), Bina (Madhya Pradesh)
- CPCL: Manali & Narimanam (Tamil Nadu)
- ONGC/MRPL: Tatipaka (Andhra Pradesh), Mangalore (Karnataka)
- RIL: Jamnagar (Gujarat) - including SEZ facility

## 🛠️ Technologies Used

- **Python** - Data processing and analysis
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Jupyter Notebook** - Interactive analysis environment
- **Openpyxl** - Excel file handling

## 📈 Data Characteristics

- **Time Series Data:** Historical trends spanning 28 fiscal years
- **Multi-dimensional:** Companies, locations (states), and facilities
- **Forecasted Data:** Includes projections for better planning insights
- **Granular Coverage:** Individual refinery-level data points

## 🚀 Usage

### To Run the Analysis:

1. Clone the repository
2. Ensure Python and required libraries are installed:
   ```bash
   pip install pandas numpy openpyxl jupyter
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook India_Crude_Analytics.ipynb
   ```
4. Execute cells sequentially to reproduce the analysis

## 💡 Potential Applications

- Refinery capacity planning and utilization analysis
- Geographic distribution assessment of processing capacity
- Temporal trend identification and forecasting
- Company-wise performance comparison
- State-level petroleum infrastructure evaluation
- Investment and policy planning insights

## 📝 Notes

- Data uses fiscal year notation (e.g., 2024-25 represents April 2024 to March 2025)
- Projections marked with "(P)" indicate preliminary/forecasted values
- All values in '000 Metric Tonnes for standardized comparison
- Data source: Official government petroleum analytics authority

## 📧 Contact

For questions or contributions, please reach out through the repository issues.

## 📄 License

Specify your desired license here (e.g., MIT, Apache 2.0, or CC BY 4.0)

## 🙏 Acknowledgments

- Data source: Petroleum Planning & Analysis Cell, Ministry of Petroleum & Natural Gas, Government of India
- Special thanks to all participating oil companies for data contribution

---

**Last Updated:** August 2026  
**Data Current Through:** June 2026
