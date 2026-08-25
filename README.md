# Wuttipat Sricharoensuk

**Commercial analytics and BI, based in Bangkok.**

I work on retail commercial data: sales, promotion performance and seller portfolios, and the
reporting that turns them into decisions.

My current role covers the annual target-setting framework and the trade promotion calendar at a
Thai modern-trade retail chain, across the commercial teams involved in promotion. Before that I
managed roughly 100 sellers and about 50M THB of monthly portfolio GMV as a Key Account Manager
at Lazada Thailand. I spent close to eight years in engineering first, then moved into data
through coursework and the projects below.

I am looking for a commercial analytics, BI or insights role.

**Portfolio: [swuttipat.github.io/about-me](https://swuttipat.github.io/about-me/)**

---

## Automated pipelines

Three projects that collect, process and publish on a schedule, with no manual step.

| Project | What it does | Built with |
|---|---|---|
| **[flight-price-tracker](https://github.com/swuttipat/flight-price-tracker)** | Tracks fares on 13 routes out of Bangkok. Answers two questions: when to book a fixed trip, and when to fly a flexible one. Collects daily at 08:00 Bangkok. | Python, GitHub Actions, Chart.js |
| **[ecom-price-tracker](https://github.com/swuttipat/ecom-price-tracker)** | Daily competitor price and assortment tracking for probiotic supplements on Lazada Thailand. Commits each snapshot to the repo, then reports median price, promo penetration and day-on-day changes. | Python, GitHub Actions |
| **[about-me](https://github.com/swuttipat/about-me)** | Portfolio page. One self-contained HTML file with no external requests, hosted on GitHub Pages. | HTML, CSS, JavaScript |

Shopee and TikTok Shop were built and tested for the price tracker, then dropped when anti-bot
measures blocked every free approach available. The build log in that repo records the attempts.

---

## Data science portfolio

### Machine learning and modelling

- **[Customer segmentation with clustering](https://github.com/swuttipat/customer-segmentation-with-clustering-model):** RFM-style customer grouping. Also published as a [Kaggle notebook](https://www.kaggle.com/code/wuttipats/customer-segmentation-with-clustering-model).
- **[German credit risk](https://github.com/swuttipat/german-credit-risk):** Classification on a small, imbalanced, heavily categorical dataset.
- **[Fraud detection](https://github.com/swuttipat/fraud-detection):** Class imbalance handled with SMOTE, evaluated on precision and recall rather than accuracy.
- **[Climate time series](https://github.com/swuttipat/climate-time-series-analysis):** Seasonal decomposition and SARIMA forecasting.

### Deep learning

- **[Water bottle image classification](https://github.com/swuttipat/water_bottle_image-classification):** A CNN image classifier. The initial accuracy score proved to be an artefact of class imbalance, since most training images were labelled "full". Rebuilt with resampling, a confusion matrix and a ResNet50 benchmark.
- **[COVID-19 tweet sentiment](https://github.com/swuttipat/covid19-tweet-text-sentiment-classification):** Text preprocessing and multi-class sentiment classification.
- **[Dog breed classifier](https://www.kaggle.com/code/wuttipats/dog-breed-images-classification-model-baseline):** Image classification baseline, trained on a dataset I assembled.

### Data engineering and deployment

- **[Lazada health products scraper](https://github.com/swuttipat/webscraping-lazada-health-products)** and **[the analysis it feeds](https://github.com/swuttipat/e-commerce-health-products-analysis):** Collects a live marketplace catalogue, then analyses it.
- **[Iris ML on FastAPI, Docker and Heroku](https://github.com/swuttipat/iris-ml-fastapi-docker-heroku):** A model served as a REST endpoint, containerised and deployed.

---

## Datasets I published

Two datasets on my Kaggle profile are ones I built rather than downloaded.

- **[Lazada Thailand health products](https://www.kaggle.com/datasets/wuttipats/lazada-thailand-health-products-dataset):** Scraped from a live marketplace, cleaned and documented.
- **[Dog breed image classification](https://www.kaggle.com/datasets/wuttipats/dog-breed-image-classification-dataset):** Assembled from the Dog CEO API, using my own [API client](https://github.com/swuttipat/dogceo-python-api).

---

## Toolkit

**Analysis and reporting:** SQL and BigQuery, Power BI with DAX, advanced Excel

**Python:** pandas, scikit-learn, statsmodels, TensorFlow and Keras

**Deployment:** GitHub Actions, Docker, FastAPI, Git

**Certifications:** Google Data Analytics, Google Advanced Data Analytics, Google Digital
Marketing and E-commerce, DataCamp Data Analyst in Power BI, DataCamp SQL for Business Analysts.

---

Also here: early classifiers on Titanic, Iris and California housing, an SQL exploration of US
birth rates, a Thai stock ticker scraper, and a number of small web apps and browser games.

**[Portfolio](https://swuttipat.github.io/about-me/) · [LinkedIn](https://linkedin.com/in/wuttipat-sricharoensuk) · [Kaggle](https://www.kaggle.com/wuttipats)**
