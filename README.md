**# greek-sensitivities**# Greek Sensitivities

A Black-Scholes visualization tool for understanding how option prices and Greeks (like delta, gamma, theta, vega, rho, and higher-order Greeks) behave as a function of various inputs such as strike price, volatility, time to expiration, and interest rates.

Built to support intuitive exploration of first- and second-order option sensitivities, with interactive widgets and plotting utilities for quick experimentation and learning.

---

## 🚀 Getting Started

### Requirements

- Python 3.8+
- `matplotlib`
- `numpy`
- `scipy`
- `ipywidgets`
- `jupyter` or VSCode with notebook support

### Installation

```bash
git clone https://gitlab.ad.valkyrietrading.com/rwang/greek-sensitivities.git
cd greek-sensitivities
python -m venv valkenv
valkenv\Scripts\activate  # On Windows
pip install -r requirements.txt
```

### Usage
1. Launch a Jupyter notebook
2. Open greek_sensitivities.ipynb
3. Select from:
    - Option type: call or put
    - Independent variable: e.g. strike_price, volatility
    - Dependent variable: delta, gamma, etc.
4. Click Generate Plot to visualize the results.

### Features
Interactive plots for:
- Option price
- Delta, Gamma, Theta, Vega, Rho
- Higher-order Greeks: Vanna, Charm, Volga
- Adjustable inputs: strike, spot price, interest rate, volatility, time
- Toggle between call and put options

### 📋 Roadmap
- [ ] Implied volatility surface visualization
- [ ] 3D Greek visualizations
- [ ] Export plots to PDF/images
- [ ] Live data integrations (optional)

### Contributing
Open to internal contributions! Fork the repo, improve it, and submit a merge request.

### Author
Rich Wang
richwang.y@gmail.com

### License
MIT Open Source License

### Project Status
🟢 Active — under development during internship period.
