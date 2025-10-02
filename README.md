# 📊 Retail Sales Analysis

A comprehensive data analysis project examining retail sales patterns and customer behavior using the Online Retail II dataset. This project provides insights into sales trends, customer segmentation, and business performance metrics through interactive visualizations and statistical analysis.

## 🚀 Project Overview

This project analyzes retail transaction data spanning 2009-2011 to uncover valuable business insights including:

- Sales performance trends over time
- Top-performing products and markets
- Customer segmentation using RFM analysis
- Geographic sales distribution
- Purchase behavior patterns

## 📁 Project Structure

```
Retail-Sales-Analysis/
├── data/
│   └── online_retail_II.xlsx          # Raw dataset (2009-2011 retail data)
├── notebooks/
│   └── Retail_Sales_Analysis.ipynb    # Main analysis notebook
├── images/                             # Generated visualization outputs
└── README.md                          # Project documentation
```

## 🔍 Key Analysis Components

### 1. **Data Preprocessing & Cleaning**

- Merged data from multiple Excel sheets (2009-2010 & 2010-2011)
- Removed missing customer IDs and duplicate records
- Filtered out negative/zero quantities
- Created calculated fields (TotalPrice = Quantity × Price)
- **Result**: Clean dataset with 779,495 transactions from 1,067,371 original records

### 2. **Sales Trend Analysis**

- **Monthly Sales Performance**: Time series analysis showing seasonal patterns and growth trends
- **Geographic Analysis**: Top 10 countries by sales revenue with interactive visualizations
- **Product Performance**: Top 10 best-selling products by quantity

### 3. **Customer Segmentation (RFM Analysis)**

- **Recency**: Days since last purchase
- **Frequency**: Number of purchases made
- **Monetary**: Total amount spent
- **Customer Scoring**: 4-tier scoring system (1-4) for each RFM dimension
- **Segmentation**: Combined RFM scores to identify customer segments

### 4. **Data Visualizations**

- Interactive Plotly charts for geographic sales distribution
- Time series plots for sales trends
- Scatter plots for customer segmentation analysis
- Distribution histograms for RFM score analysis

## 🛠️ Technologies Used

- **Python 3.x** - Core programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Static plotting and visualization
- **Seaborn** - Statistical data visualization
- **Plotly** - Interactive visualizations
- **Jupyter Notebook** - Interactive development environment

## 📊 Key Insights & Findings

### Sales Performance

- Clear seasonal patterns in monthly sales data
- Identification of peak sales periods
- Geographic concentration of sales in specific markets

### Customer Behavior

- Customer segmentation reveals distinct purchasing patterns
- RFM analysis identifies high-value customers
- Frequency vs. monetary value correlation analysis

### Product Analysis

- Top 10 products drive significant portion of total volume
- Product performance varies by geographic region

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas matplotlib seaborn plotly jupyter
```

### Installation & Usage

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/Retail-Sales-Analysis.git
   cd Retail-Sales-Analysis
   ```
2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook notebooks/Retail_Sales_Analysis.ipynb
   ```
4. **Run the analysis**

   - Execute cells sequentially to reproduce the analysis
   - Modify parameters to explore different aspects of the data

## 📈 Sample Outputs

The analysis generates several key visualizations:

- **Monthly Sales Trend**: Line chart showing sales performance over time
- **Top 10 Countries**: Interactive bar chart of highest revenue markets
- **Product Rankings**: Horizontal bar chart of best-selling products
- **Customer Segmentation**: Scatter plot showing RFM analysis results
- **Score Distribution**: Histogram of customer RFM scores

## 📁 Dataset Information

**Source**: Online Retail II Dataset

- **Time Period**: December 2009 - December 2011
- **Records**: 1,067,371 initial transactions
- **Geography**: Multiple countries with UK as primary market
- **Sectors**: Retail sales with variety of products

**Key Columns**:

- Invoice: Transaction identifier
- StockCode: Product identifier
- Description: Product description
- Quantity: Items purchased
- InvoiceDate: Transaction timestamp
- Price: Unit price
- Customer ID: Customer identifier
- Country: Customer location

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

**Divyakumar**

* LinkedIn: [[https://www.linkedin.com/in/divyakumar-sanjaykumar-patel-4231ba257/](https://www.linkedin.com/in/divyakumar-sanjaykumar-patel-4231ba257/)]
* Email: [[pateldivyakuamr889@gmail.com](mailto:pateldivyakuamr889@gmail.com)]

## 🙏 Acknowledgments

- Dataset provided by UCI Machine Learning Repository
- Inspiration from retail analytics best practices
- Python data science community for excellent libraries

---

⭐ **If you found this project helpful, please give it a star!** ⭐
