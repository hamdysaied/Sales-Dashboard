# Sales Analytics Dashboard 📊

A comprehensive sales analytics dashboard providing real-time insights into business performance across multiple dimensions including regional analysis, product categories, and time-based trends.

## 🎯 Overview

This interactive dashboard displays key sales metrics and provides detailed analysis capabilities for:
- **Total Sales**: $2,297,201
- **Total Quantity**: 37,873 units
- **Total Profit**: $286,397
- **Average Discount**: 16%
- **Total Orders**: 9,994

## ✨ Features

### Key Performance Indicators (KPIs)
- Real-time sales, profit, and quantity tracking
- Average discount analysis
- Order volume monitoring

### Multi-Dimensional Analysis
- **Time-based filtering**: Years 2015-2018
- **Regional breakdown**: Central, East, South, West
- **Quarterly analysis**: Q1-Q4 filtering capabilities

### Visual Components

#### 📈 Category Analysis (PivotCharts)
- **Sales by Category**: Interactive donut charts created with PivotCharts showing distribution across:
  - Furniture (32%)
  - Office Supplies (31%) 
  - Technology (37%)
- **Profit by Category**: Visual profit distribution analysis using PivotChart visualization
- **Quantity by Category**: Volume analysis across product categories via PivotTable aggregation

#### 🏆 Product Performance (PivotTable Analysis)
- **Top 10 Products**: Best-performing products identified through PivotTable ranking
- **Bottom 10 Products**: Underperforming product identification using PivotTable sorting
- **Subcategory Analysis**: Detailed breakdown of sales and profit by subcategories using PivotTable grouping

#### 🗺️ Geographic Intelligence
- **Regional Map Visualization**: Interactive US map showing customer distribution
- **State-level Analysis**: Customer concentration by state
- **Regional Performance Metrics**: Sales and profit analysis by geographic regions

## 🛠️ Technology Stack

- **Data Analysis**: Excel PivotTables and PivotCharts
- **Frontend**: [Your framework - React/Vue/Angular]
- **Data Visualization**: PivotCharts + [Chart library - D3.js/Chart.js/Plotly]
- **Backend**: [Your backend technology]
- **Database**: [Your database solution]
- **Styling**: [CSS framework/library]

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/sales-analytics-dashboard.git

# Navigate to project directory
cd sales-analytics-dashboard

# Install dependencies
npm install

# Start the development server
npm start
```

## 🚀 Usage

1. **Filter by Time Period**: Use the Years selector to filter data by specific years (2015-2018)
2. **Regional Analysis**: Select specific regions (Central, East, South, West) for targeted insights
3. **Quarterly Views**: Filter by quarters (Q1-Q4) for seasonal analysis
4. **Interactive Charts**: Click on chart segments for detailed drill-down analysis
5. **Geographic Exploration**: Hover over map regions for detailed customer metrics

## 📊 Data Analysis Features

### PivotTable Capabilities
- **Dynamic Data Aggregation**: Automatically sum, count, and average sales metrics
- **Multi-dimensional Grouping**: Group data by Year, Region, Quarter, Category, and Subcategory
- **Flexible Filtering**: Interactive filters for time periods, regions, and product categories
- **Calculated Fields**: Custom metrics like profit margins and growth rates
- **Drill-down Analysis**: Expand from high-level categories to detailed product information

### PivotChart Visualizations
- **Interactive Donut Charts**: Category distribution with hover details
- **Bar Charts**: Top/Bottom product performance comparisons
- **Time Series Analysis**: Quarterly and yearly trend visualization
- **Geographic Data Integration**: Regional performance mapping
- **Real-time Updates**: Charts automatically refresh when PivotTable filters change






