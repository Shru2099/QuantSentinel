
# QuantSentinel: Market Risk Modeling Suite in Python

This project implements a full-scale **market risk modeling framework** inspired by front-office and regulatory practices in investment banking. It includes Value-at-Risk estimation, stress testing, backtesting, and regulatory capital charge computation using real-world financial data.

---

## 📊 Features Implemented

- 📈 **Portfolio VaR (Value at Risk)**
  - Parametric (Variance-Covariance)
  - Historical Simulation
  - Monte Carlo Simulation

- ⚠️ **Stress Testing**
  - COVID-period covariance matrix (2020 stress window)
  - Hypothetical macroeconomic shocks

- 🧮 **Component VaR Attribution**
  - Risk decomposition by asset contribution

- 🧪 **Backtesting**
  - VaR breach counting aligned with SR 11-7 guidelines

- 🏛️ **Regulatory Capital Calculation**
  - Basel III-compliant capital charge using sVaR + multipliers

- 📊 **Interactive Plotly Dashboard**
  - Real-time visualization of VaR, stress losses, and capital impact

---

## 🧠 Concepts Covered

- Value at Risk (VaR)
- Stressed VaR (sVaR)
- Monte Carlo Simulation
- Component VaR Attribution
- Covariance Estimation
- Backtesting under Basel Rules
- Capital Charge Estimation (VaR + sVaR)

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Market_Risk_Modelling_StepByStep.ipynb` | Full Jupyter notebook with modular steps |
| `summary.pdf` | Executive summary (2-page project brief) |
| `README.md` | This file |
| `screenshots/` | (Optional) Dashboard or output visualizations |

---

## 💻 Technologies Used

- Python (pandas, NumPy, yfinance, SciPy)
- Plotly (interactive charts)
- Jupyter Notebook
- Matplotlib

---

## 📸 Dashboard Preview

![Interactive Dashboard Preview](screenshots/dashboard.png)

---

## 📈 Example Outputs

- 1-Day Historical VaR: $325,000  
- Monte Carlo VaR (99%): $342,000  
- Stress Test Loss: $410,000  
- Regulatory Capital Charge: $4.95 million

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Shru@2099/quant-sentinel.git
   ```
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook Market_Risk_Modelling.ipynb
   ```

---

## 📞 Contact

**Shruti Pathak**  
Symbiosis International University | M.Sc Data Science  
📧 shrutepathak@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/shruti-pathak-55ab23133/)  
🔗 [GitHub](https://github.com/Shru@2099)
