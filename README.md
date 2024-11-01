# Health and Economic Clustering & Market Segmentation PCA Analysis

## Project Overview
This project focuses on:
- **Clustering Analysis**: Grouping states by health and economic indicators to inform targeted policy decisions.
- **Principal Component Analysis (PCA)**: Analyzing a salon chain’s market segmentation data to identify key factors affecting customer satisfaction.

## Data
### Clustering Dataset: `State_wise_Health_income.csv`
- **Goal**: Group states based on health and economic conditions to support targeted governmental measures.
- **Variables**:
  - `Health_indices1` & `Health_indices2`: Composite health scores.
  - `Per_capita_income`: Average income per person.
  - `GDP`: Economic size and growth indicator.

### PCA Dataset: `Hair Salon.csv`
- **Goal**: Perform PCA on factors influencing customer satisfaction for market segmentation.
- **Variables**: Product quality, E-commerce, Technical support, Advertising, Competitive pricing, etc.

## Project Structure
- **Part 1: Clustering Analysis**
  - Conducted EDA to examine variable distributions.
  - Applied K-means and Hierarchical clustering.
  - Profiled clusters to suggest actions based on health and economic conditions.
  
- **Part 2: Principal Component Analysis**
  - Performed PCA after removing the target variable `satisfaction`.
  - Analyzed principal components to determine key factors in market segmentation.

## Key Skills and Tools
- **Skills**: EDA, K-means, Hierarchical Clustering, Cluster Profiling, PCA
- **Libraries**: `pandas`, `matplotlib`, `scikit-learn`, `seaborn`

## Usage
1. **Load Data**: Use `State_wise_Health_income.csv` for clustering and `Hair Salon.csv` for PCA.
2. **Run EDA**: Analyze distributions and correlations.
3. **Clustering**: Apply K-means and Hierarchical clustering, then profile clusters.
4. **PCA**: Perform PCA on `Hair Salon.csv` to identify key drivers.

## Results
- **Clustering Analysis**: Segments states based on health and economic metrics, aiding policy recommendations.
- **PCA**: Highlights principal components driving market segmentation for the salon chain.
