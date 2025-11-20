# Supply Chain Correlation Analysis

## Email
23f3000228@ds.study.iitm.ac.in

## Project Overview
OptimalFlow Logistics supply chain correlation analysis for automotive manufacturer supplier performance data.

### Dataset Information
- **Transactions**: 68 procurement transactions
- **Time Period**: Past quarter
- **Metrics**: 5 key supply chain variables
- **Purpose**: Identify bottlenecks and optimize cost structures

### Metrics Analyzed
1. **Supplier_Lead_Time**
2. **Inventory_Levels**
3. **Order_Frequency**
4. **Delivery_Performance**
5. **Cost_Per_Unit**

### Correlation Matrix Results

| Metric | Supplier_Lead_Time | Inventory_Levels | Order_Frequency | Delivery_Performance | Cost_Per_Unit |
|--------|---|---|---|---|---|
| Supplier_Lead_Time | 1.000 | 0.469 | -0.908 | -0.913 | 0.971 |
| Inventory_Levels | 0.469 | 1.000 | -0.445 | -0.423 | 0.472 |
| Order_Frequency | -0.908 | -0.445 | 1.000 | 0.864 | -0.892 |
| Delivery_Performance | -0.913 | -0.423 | 0.864 | 1.000 | -0.903 |
| Cost_Per_Unit | 0.971 | 0.472 | -0.892 | -0.903 | 1.000 |

### Key Insights
- **Strongest Positive Correlation**: Cost_Per_Unit ↔ Supplier_Lead_Time: 0.971
- **Strongest Negative Correlation**: Supplier_Lead_Time ↔ Delivery_Performance: -0.913
### Files in Repository
- `README.md`: This documentation file
- `correlation_matrix.csv`: Correlation matrix in CSV format
- `supply_chain_heatmap.png`: Visualization of correlation matrix

### Business Implications
The correlation analysis helps in:
- Supplier selection and evaluation
- Inventory planning optimization
- Cost structure analysis
- Delivery performance improvement

---

*Analysis conducted by OptimalFlow Logistics for automotive manufacturing client*
