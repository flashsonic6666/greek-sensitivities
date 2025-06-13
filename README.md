# Greek Sensitivities

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
- `ipympl`
- `jupyterlab`

### Installation

```bash
git clone https://github.com/flashsonic6666/greek-sensitivities.git
cd greek-sensitivities
python -m venv greek-sensitivites
greek-sensitivites\Scripts\activate  # On Windows
pip install -r requirements.txt
```

### Usage
1. Launch Jupyter Lab
2. Open greek_sensitivities.ipynb
3. In the second to last cell:
    - Select from:
        - Option type: call or put
        - Independent variable: e.g. strike_price, volatility
        - Dependent variable: delta, gamma, etc.
    - Click Generate Plot to visualize the results.
5. In the last cell, test your knowledge of the Greeks by dragging your mouse along the graph to draw the sensitivity graph. Keep track of your stats!

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
🟢 Active — under development.
