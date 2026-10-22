# Indimums: Product Catalogue & Customer Feedback Analysis

## Project Overview

How can publicly available customer reviews help a consumer brand understand what customers appreciate and where their experience could improve?

This project analyses the public product catalogue of Indimums and a sample of 60 customer reviews across six selected products. I used Google Sheets to organise the data, classify feedback themes and sentiment, and summarise the results. I then built a Power BI dashboard to compare customer feedback patterns and product ratings.

The goal was to turn unstructured review text into a structured view of customer experiences and potential areas for further investigation.

## Business Questions

- What is the sentiment distribution across the selected reviews?
- Which themes appear in customer feedback?
- How do average sample ratings differ across the six products?
- Which reported concerns relate to the product itself versus delivery or packaging?
- What areas could benefit from further investigation?

## Tools Used

- **Google Sheets:** Data organisation, review classification, summary tables, and PivotTables
- **Power BI:** KPI cards, charts, slicers, product comparisons, and dashboard reporting

## Data Sources and Scope

| Item | Details |
|---|---|
| Product catalogue | 19 products |
| Review sample | 60 reviews |
| Products analysed in detail | 6 |
| Reviews per selected product | 10 |
| Data sources | Public product catalogue and customer reviews |

### Sources

- [Indimums Product Catalogue](https://theindimums.com/collections/all)
- [Indimums Store Reviews on Judge.me](https://judge.me/reviews/stores/theindimums.com)

## Key Findings

### 1. Positive Sentiment Dominated the Selected Sample

Of the 60 classified reviews:

- **48 positive** — 80%
- **9 mixed** — 15%
- **3 negative** — 5%

These figures describe the selected sample and should not be interpreted as the sentiment distribution of all Indimums customers.

### 2. Customer Feedback Covered Multiple Themes

Recurring topics included fragrance, ingredients, lather, moisturisation, value for money, and reported skin or hair experiences. Customers discussed different aspects of using the products rather than focusing on a single measure of satisfaction.

### 3. Average Ratings Differed Across Selected Products

| Product | Average Sample Rating |
|---|---:|
| Natural Baby Body Wash for Dry & Sensitive Skin | 4.6/5 |
| Natural Baby Cream for Dry & Sensitive Skin | 4.6/5 |
| Baby Hair Oil for Hair Growth & Strong Roots | 4.5/5 |
| Natural Baby Shampoo | 4.2/5 |
| Natural Laundry Detergent | 4.1/5 |
| Daily Baby Bath Bundle | 4.0/5 |

Each product has 10 reviews in the sample. These are sample averages, not necessarily the overall ratings displayed on the store.

### 4. Some Complaints Were Operational Rather Than Product-Related

The classifications included a delivery complaint about a parcel not being received and a packaging complaint involving a cracked bottle. Separating these from product feedback helps identify different areas for potential follow-up.

### 5. Data Quality Checks Were Important

One review listed under Natural Laundry Detergent referred to a floor cleaner, and two hair-oil reviews contained very similar wording. These observations were flagged for verification because questionable product associations and near-duplicate text can affect the analysis.

## Dashboard

The Power BI report contains two pages.

### Page 1 — Customer Feedback Overview

- Reviews analysed, positive reviews, and negative reviews
- Most common customer feedback themes
- Overall sentiment distribution
- Average sample rating by product
- Product and sentiment slicers

### Page 2 — Feedback Insights

- Customer feedback themes by sentiment
- Product feedback versus operational issues
- Product-level review summary
- Potential business implications

The exported PDF report can be viewed in this repository.

## Potential Business Implications

- Check whether product descriptions and FAQs clearly explain lather, fragrance, and how to use the products.
- Look at delivery and packaging complaints separately from feedback about product quality and performance.
- Check reviews that may be duplicates or linked to the wrong product before using the results.
- Use mixed reviews to find areas that may need further investigation, rather than assuming the same problem affects all customers.

These are possible next steps based on the analysis, not proof that the brand has widespread problems.

## Limitations

- The analysis includes 60 selected public reviews across six products, so it may not represent all customers.
- Review themes and sentiments were classified manually and may involve some personal judgement.
- Customer experiences shared in reviews were not independently verified.
- Product details and ratings were recorded at a specific point in time and may change.
- The available data does not show actual sales, revenue, profit, customer retention, or repeat purchases.
- This was an independent analysis using public information. It was not requested, funded, or approved by Indimums.

## Project Files

- `README.md` — Project documentation
- `Indimums_Customer_Feedback_Analysis.pdf` — Exported Power BI dashboard
- Cleaned Google Sheets workbook — Catalogue, review sample, summary, and theme classifications

## Author's Note

This project demonstrates how Google Sheets and Power BI can be used to organise unstructured customer feedback, identify recurring themes, and communicate findings with clear limitations.
