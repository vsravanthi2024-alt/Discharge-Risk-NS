# Discharge-Risk-NS
Neurosymbolic Framework for Hospital Discharge Risk Classification
# Discharge-Risk-NS 🩺

**Neurosymbolic Framework for Rule-Based Risk Flagging from Hospital Discharge Summaries**

[![Scientific Reports](https://img.shields.io/badge/Scientific%20Reports-Under%20Review-blue)](https://www.nature.com/srep/)
[![License](https://img.shields.io/github/license/sravanthivelavolu/Discharge-Risk-NS)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](requirements.txt)

## 🎯 Key Results (MIMIC-IV)
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| TF-IDF+RF | 85.2% | 82.1% |
| Rules Only | 87.4% | 84.1% |
| **Discharge-Risk-NS** | **99.6%** | **98.9%** |

**How to use **
### **1. Install**
```bash
git clone https://github.com/YOURUSERNAME/Discharge-Risk-NS.git
cd Discharge-Risk-NS
pip install -r requirements.txt
```

### **2. Quick Demo (No MIMIC data needed!)**
```bash
# Run interactive demo
python src/demo.py

# Example Output:
# Input: "Patient pneumonia eGFR 45 K+ 5.8 Na+ 128"
# Output: HIGH-RISK (Score: 0.96)
```

### **3. Classify Single Discharge Summary**
```python
from src.model import DischargeRiskNS

model = DischargeRiskNS()
text = "Pneumonia heart failure AKI eGFR 32 K+ 6.1"
risk, confidence = model.predict(text)
print(f"Risk: {risk}, Confidence: {confidence:.3f}")
# Output: Risk: HIGH, Confidence: 0.983
```

### **4. Batch Process CSV**
```bash
python src/batch_predict.py data/sample_discharge.csv --output predictions.csv
```

### **5. Reproduce Paper Results**
```bash
jupyter notebook notebooks/01_reproduce_res
## 🚀 Quick Demo
```bash
git clone https://github.com/sravanthivelavolu/Discharge-Risk-NS.git
cd Discharge-Risk-NS
pip install -r requirements.txt
jupyter notebook notebooks/Discharge-Risk-NS.ipynb
```

## 📊 Reproduce Results
- `notebooks/Discharge-Risk-NS github.ipynb` ← All your charts/tables
- MIMIC-IV: https://physionet.org/content/mimiciv/2.2/

## 📚 Citation
