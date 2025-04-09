# Autolysis - Automated Analysis Pipeline

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Project Overview

Autolysis is a sophisticated analysis pipeline that streamlines the entire process from data ingestion to insight generation. By integrating machine learning algorithms with AI-driven analytics, it converts raw inputs into detailed visual reports with minimal user effort.

## Key Features

- **Advanced Analytical Techniques** - Implement clustering and outlier detection
- **Automated Exploratory Analysis** - Produce statistical overviews and uncover key data patterns
- **AI-Enhanced Insights** - Utilize Google’s Gemini API to recommend further analyses and interpretations
- **Smart Visualizations** - Dynamically generate appropriate plots tailored to the input data
- **Detailed Reporting** - Generate markdown reports complete with integrated visualizations
  
  
## Technologies Used

- **Python** - Core programming language
- **Analysis Stack** - pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning** - scikit-learn for clustering and anomaly detection
- **AI Integration** - Google's Gemini API for intelligent insight generation
- **Environment Management** - dotenv for configuration

## Working

1. **Input Ingestion**: Load and preprocess CSV files from any source
2. **Statistical Analysis**: Calculate descriptive statistics and identify patterns
3. **Machine Learning**: Apply clustering and outlier detection
4. **AI-Powered Analysis**: Generate deeper insights using Google's Gemini API
5. **Visualization Generation**: Create relevant, high-quality visualizations
6. **Report Generation**: Compile findings into a comprehensive markdown report

## Installation and Usage

```
# Set up environment variables
echo "AIPROXY_TOKEN=your_gemini_api_key"
# Run the analysis on your input file
python autolysis.py your_input.csv 
# OR python autolysis.py path/to/your_input.csv 
```

## Technical Highlights
Intelligent Feature Selection – Automatically identifies and prioritizes the most relevant columns for visualization.

Dynamic Visualization – Selects and adapts plot types based on the nature of the input data.

Resilient Error Management – Ensures graceful handling when ideal analysis isn't feasible.

High-Efficiency Processing – Optimized to handle large datasets with speed and precision.

Modular & Scalable Design – Allows seamless integration of new analysis modules and visualization options.

## Future Enhancements
Integration with a broader range of machine learning models for advanced predictive analytics

Development of an interactive web-based dashboard for result exploration

Expanded input format compatibility, including databases and APIs

Automated analysis capabilities for time-series data

Natural language interface for querying and interacting with results

# Project Structure
```
├── autolysis.py         # Main analysis script
├── goodreads/           # Output directory for *goodreads* README and visualizations
├── happiness/           # Output directory for *happiness* README and visualizations
├── media/               # Output directory for *media* README and visualizations
```
