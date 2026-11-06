# Kaggle

Competition notebooks, study-group work and course material from
[Kaggle](https://www.kaggle.com/paul77ms).

---

## Results

| Competition | Result |
| --- | --- |
| Titanic — Machine Learning from Disaster | Top 3% |
| Optiver Realized Volatility Prediction | 259 / 3,965 |
| 충북인공지능교육 Kaggle Challenge (chai) | 🥈 **2nd** + algorithm-use award |

## Contents

### [`competitions/`](competitions/)

| Notebook | Competition |
| --- | --- |
| [`optiver-realized-volatility.ipynb`](competitions/optiver-realized-volatility.ipynb) | Optiver Realized Volatility Prediction — order-book volatility forecasting |
| [`jpx-tokyo-stock-prediction.ipynb`](competitions/jpx-tokyo-stock-prediction.ipynb) | JPX Tokyo Stock Exchange Prediction |
| [`disaster-tweets-nlp.ipynb`](competitions/disaster-tweets-nlp.ipynb) | Real or Not? NLP with Disaster Tweets |
| [`covid19-vaccine-analysis.ipynb`](competitions/covid19-vaccine-analysis.ipynb) | COVID-19 vaccine data analysis |
| [`training-pipeline.ipynb`](competitions/training-pipeline.ipynb) | Shared training pipeline |

### [`study-group/`](study-group/)

An offline study group of four, run over one semester. Each week the group
worked through a completed Kaggle competition and presented back.

**Goals** — Colab fluency, clean project write-ups in Markdown, hands-on EDA,
feature engineering and preprocessing, then machine-learning models and live
competition entry.

| Notebook | Competition |
| --- | --- |
| [`titanic-walkthrough.ipynb`](study-group/titanic-walkthrough.ipynb) | Titanic — full walkthrough |
| [`titanic-experiments.ipynb`](study-group/titanic-experiments.ipynb) | Titanic — experiments |
| [`porto-seguro-safe-driver-prediction.ipynb`](study-group/porto-seguro-safe-driver-prediction.ipynb) | Porto Seguro Safe Driver Prediction |
| [`nyc-taxi-trip-duration.ipynb`](study-group/nyc-taxi-trip-duration.ipynb) | NYC Taxi Trip Duration |

### [`chungbuk-ai-education/`](chungbuk-ai-education/)

충북인공지능교육 (Chungbuk AI Education), cohort 1 —
**29 Jun – 21 Aug 2020, 160 hours**. Python fundamentals, then machine learning,
then deep learning, ending in the in-course Kaggle challenge (chai).

| Notebook | Topic |
| --- | --- |
| [`course-notebook.ipynb`](chungbuk-ai-education/course-notebook.ipynb) | Course material |
| [`dog-breed-classification.ipynb`](chungbuk-ai-education/dog-breed-classification.ipynb) | Dog breed classification (CNN) |
| [`recyclable-waste-classification.ipynb`](chungbuk-ai-education/recyclable-waste-classification.ipynb) | Recyclable waste classification |
| [`naver-movie-review-sentiment-konlpy.ipynb`](chungbuk-ai-education/naver-movie-review-sentiment-konlpy.ipynb) | KoNLPy setup + Naver movie review sentiment |

## Running these

```bash
git clone https://github.com/paulms77/Kaggle.git
cd Kaggle
jupyter notebook
```

Competition data is not included — download it from the relevant Kaggle
competition page (or use the Kaggle API) and adjust the input path at the top of
each notebook.

```bash
pip install kaggle
kaggle competitions download -c titanic
```

## Related

- [Dacon](https://github.com/paulms77/Dacon) — DACON competition notebooks
- [Study](https://github.com/paulms77/Study) — study logs and course records
- [Another-Competition](https://github.com/paulms77/Another-Competition) — hackathons and other challenges
