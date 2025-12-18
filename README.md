# Banking Customer Analysis & Insights

Comprehensive Exploratory Data Analysis (EDA) of a banking dataset featuring 3,000 records and 25 distinct features. This project identifies customer segments, financial accumulation trends, and behavioral correlations using Python.

## Tech Stack
* [cite_start]**Core:** Python [cite: 741, 742]
* [cite_start]**Analysis:** Pandas, NumPy [cite: 741, 742]
* [cite_start]**Visualization:** Matplotlib, Seaborn [cite: 1030]

## Execution Workflow
1. [cite_start]**Data Ingestion:** Processed 3,000 entries with 25 feature columns[cite: 753, 756].
2. [cite_start]**Feature Engineering:** Segmented customers into "Low", "Mid", and "High" Income Bands[cite: 871, 877].
3. [cite_start]**Data Cleaning:** Handled datetime conversions for "Joined Bank" and verified null counts[cite: 1018, 1020].
4. [cite_start]**Statistical Profiling:** Generated descriptive statistics for numerical balances and risk weightings[cite: 1015, 1016].

## Key Insights
* [cite_start]**Savings Synergy:** A significant correlation exists between Bank Deposits and Saving Accounts, indicating consistent customer financial behavior[cite: 731, 732].
* [cite_start]**Financial Lifecycle:** Higher income and older age categories show a direct trend in accumulating savings, pension funds, and credit balances[cite: 733].
* [cite_start]**Property Ownership:** Weak correlation with banking variables suggests property acquisition is driven by external factors like inheritance or market conditions[cite: 734, 735].
* [cite_start]**Segmented Lending:** Business lending operates independently of deposit metrics, though some overlap exists with personal bank loans[cite: 736, 737].

## Visualizations

### 1. Feature Distributions
![Univariate Analysis](Bank-plt.png)
[cite_start]*Histograms and KDE plots showing the distribution of age, income, and account balances across the dataset[cite: 1040, 1041].*

### 2. Correlation Matrix
![Heatmap](Bank-heatmap.png)
[cite_start]*A coolwarm heatmap visualizing the strength of relationships between numerical features[cite: 726].*

### 3. Financial Relationships
![Regression Analysis](pairs_to_plt.png)
[cite_start]*Regression plots analyzing key pairs such as Deposits vs. Savings and Income vs. Checking Accounts[cite: 728, 729].*

## How to Run
```bash
# Clone the repository
git clone [https://github.com/username/banking-analysis.git](https://github.com/username/banking-analysis.git)

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Execute analysis
python analysis.py
