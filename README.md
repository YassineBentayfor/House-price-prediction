# House-price-prediction

Welcome to the repository for our **House Prices: Advanced Regression Techniques** project. This repo contains everything you need to reproduce the notebook, train the model, and explore the results.

---

## 🚀 Quick start

```bash
# 1. Clone the repo
$ git clone https://github.com/your‑username/house‑prices‑prediction.git
$ cd house‑prices‑prediction

# 2. Create & activate a fresh environment
$ python -m venv .venv
$ source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# 3. Install dependencies
$ pip install -r requirements.txt

# 4. (Optional) Download the Kaggle dataset automatically
$ kaggle competitions download -c house-prices-advanced-regression-techniques -p data/raw
$ unzip data/raw/house-prices-advanced-regression-techniques.zip -d data/raw

# 5. Launch JupyterLab and open the notebook
$ jupyter lab notebooks/house_prices_prediction.ipynb
```

---

## 📈 Results snapshot

| Model          | Public LB RMSE | Private LB RMSE | Notes                             |
|----------------|---------------|-----------------|-----------------------------------|
| LightGBM       | 0.12034       | 0.11876         | Best single model                 |
| Stacked (LGBM + XGB + RF) | **0.11821**   | **0.11680**     | Final ensemble submitted to Kaggle |

*(Scores are log‑scaled RMSE as of 28 Apr 2025)*

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

1. Fork this repository.
2. Create your feature branch: `git checkout -b feature/awesome-feature`.
3. Commit your changes: `git commit -m "feat: add awesome feature"`.
4. Push to the branch: `git push origin feature/awesome-feature`.
5. Open a pull request.

Please follow the [Conventional Commits](https://www.conventionalcommits.org/) style and run `pre-commit run --all-files` before pushing.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙌 Acknowledgements

- [Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- [scikit‑learn](https://scikit-learn.org/), [LightGBM](https://github.com/microsoft/LightGBM), [XGBoost](https://github.com/dmlc/xgboost)
- All contributors who helped improve this project

Happy modeling! 

