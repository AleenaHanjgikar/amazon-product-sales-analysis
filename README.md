# amazon-product-sales-analysis
End-to-end Amazon product sales data analysis using Python — EDA, data cleaning, feature engineering &amp; business insights

# 🛒 Amazon Product Sales Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
An end-to-end data analysis project on **8,302 unique Amazon products** scraped in August 2025.
This project covers data cleaning, feature engineering, exploratory data analysis (EDA)
and business insights extraction using Python.

---

## 📂 Dataset
| File | Description |
|---|---|
| `amazon_products_sales_data_cleaned.csv` | Final cleaned dataset (8,302 rows × 19 columns) |

> ⚠️ Raw uncleaned dataset is not included (>25MB). 
> Original data was scraped from Amazon in August 2025 covering electronics products.

---

## 🛠️ Tools & Libraries
- **Python 3.11**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Matplotlib** — static visualizations
- **Seaborn** — statistical visualizations
- **Plotly** — interactive visualizations
- **Scikit-learn** — MinMaxScaler for popularity scoring

---

## 📊 Project Structure

Section 1  →  Importing Libraries
Section 2  →  Loading Dataset
Section 3  →  Dataset Information
Section 4  →  Data Cleaning & Feature Engineering
Section 5  →  Exploratory Data Analysis (EDA)
Section 6  →  Statistical Summary
Section 7  →  Key Business Insights
Section 8  →  Save Cleaned Dataset


---

## 🔧 Data Cleaning
- Fixed 6 data type conversions (rating, reviews, bought, prices, booleans, datetime)
- Dropped 2 irrelevant columns (sustainability_badges, image_url)
- Smart price hierarchy imputation (discounted → variant → listed)
- Removed duplicate products (42,675 → 8,302 unique products)

---

## ⚙️ Feature Engineering
| Feature | Description |
|---|---|
| `discount_percent` | Calculated discount percentage from listed vs current price |
| `discount_bucket` | No / Low / Medium / High discount tiers |
| `price_category` | Very Low / Low / Medium / High / Premium tiers |
| `popularity_score` | Weighted score (reviews 40% + bought 40% + rating 20%) |
| `popularity_tier` | Low / Moderate / High / Viral classification |

---

## 📈 EDA Sections
| # | Analysis |
|---|---|
| 6.1 | Univariate Distributions |
| 6.2 | Categorical Analysis (Pie Charts) |
| 6.3 | Rating vs Price Analysis |
| 6.4 | Discount Analysis |
| 6.5 | Correlation Heatmap |
| 6.6 | Sponsored vs Organic Performance |
| 6.7 | Best Seller Analysis |
| 6.8 | Top 20 Products (Interactive Plotly) |
| 6.9 | Coupon Impact Analysis |
| 6.10 | Collection Date Analysis |
| 6.11 | Popularity Tier Analysis |

---


<img width="882" height="510" alt="image" src="https://github.com/user-attachments/assets/dcad5f83-759a-4efc-89e2-c36800a57b76" />

<img width="884" height="371" alt="image" src="https://github.com/user-attachments/assets/87b31be1-4a6e-4211-8e61-30254ca7d5b1" />

<img width="882" height="388" alt="image" src="https://github.com/user-attachments/assets/c0a11e93-05aa-430f-99a6-48d23aaf0c57" />

<img width="889" height="456" alt="image" src="https://github.com/user-attachments/assets/5fab246a-a841-4669-bcb9-2d931ee6ce55" />

<img width="455" height="489" alt="image" src="https://github.com/user-attachments/assets/77ebf426-dd61-473e-a4b9-27bb90236190" />

<img width="887" height="547" alt="image" src="https://github.com/user-attachments/assets/ab967fbf-bcd3-4cd1-b417-aa323dce84ca" />

<img width="890" height="542" alt="image" src="https://github.com/user-attachments/assets/5d75c3ee-4388-47ec-98ae-c58152651771" />

<img width="733" height="564" alt="image" src="https://github.com/user-attachments/assets/b369e629-bab9-4914-994f-07ba804b3547" />

<img width="886" height="540" alt="image" src="https://github.com/user-attachments/assets/81e23341-2d40-43cc-b679-90f773027e4d" />

<img width="997" height="519" alt="image" src="https://github.com/user-attachments/assets/0427266f-1d3f-40e2-8df4-728eb8f6ec64" />

<img width="832" height="542" alt="image" src="https://github.com/user-attachments/assets/12c91563-8b1b-4816-9c24-1a9e22d05d4d" />

---

## 💡 Key Business Insights

1. **Best Sellers are cheap + highly reviewed** — $89 avg price, 35,879 avg reviews, 9.5x more sales than regular products
2. **Viral products cost just $14.74** — ultra-affordable everyday essentials dominate Amazon
3. **Discounts don't drive sales** — correlation of only 0.050 with units sold
4. **Sponsored products sell 74% more** — ads are volume accelerators not quality substitutes
5. **98.6% of products are Low popularity** — Amazon is extremely top-heavy, winner-takes-all market

---

## 📋 Final Dataset Overview
| Metric | Value |
|---|---|
| Total Unique Products | 8,302 |
| Total Features | 19 |
| Collection Period | Aug 21 → Aug 30, 2025 |
| Avg Rating | 4.45 |
| Avg Price | $148.74 |
| Avg Discount | 21.24% |
| Best Sellers | 198 (2.4%) |
| Viral Products | 2 |

---

## 🚀 How to Run
1. Clone the repository
```bash
   git clone https://github.com/YOUR_USERNAME/amazon-product-sales-analysis.git
```
2. Install dependencies
```bash
   pip install pandas numpy matplotlib seaborn plotly scikit-learn
```
3. Open the notebook
```bash
   jupyter notebook Amazon_product_sales_analysis.ipynb
```

---

## 👤 Author
**ALEENA HANJGIKAR**
- GitHub: [@AleenaHanjgikar](https://github.com/AleenaHanjgikar)

---

## 📄 License
This project is licensed under the MIT License.
