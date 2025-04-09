# Autolysis - Automated Analysis Pipeline

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Project Overview

Autolysis is a sophisticated analysis pipeline that streamlines the entire process from data ingestion to insight generation. By integrating machine learning algorithms with AI-driven analytics, it converts raw inputs into detailed visual reports with minimal user effort.

## Key Features

- **Automated Exploratory Analysis** - Generate statistical summaries and identify patterns
- **Advanced Analytics** - Outlier detection and clustering
- **Interactive Visualizations** - Automatically generate relevant plots based on input characteristics
- **AI-Powered Insights** - Leverage Google's Gemini API to suggest additional analyses and interpretations
- **Comprehensive Reporting** - Create markdown reports with embedded visualizations

## Technologies Used

- **Python** - Core programming language
- **Analysis Stack** - pandas, NumPy, Matplotlib, Seaborn
- **Machine Learning** - scikit-learn for clustering and anomaly detection
- **AI Integration** - Google's Gemini API for intelligent insight generation
- **Environment Management** - dotenv for configuration

## How It Works

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
Smart Feature Selection - Automatically selects the most informative columns for visualization

Adaptive Visualization - Adjusts plot types based on input characteristics

Robust Error Handling - Graceful degradation when optimal analysis isn't possible

Optimized Performance - Efficient processing for large files

Extensible Architecture - Easily add new analysis modules or visualization types

## Future Enhancements
Integration with additional ML models for predictive analytics

Interactive web dashboard for exploring results

Support for more input formats (databases, APIs)

Automated time-series analysis

Natural language query interface

# Project Structure
```
├── autolysis.py         # Main analysis script
├── goodreads/           # Output directory for *goodreads* README and visualizations
├── happiness/           # Output directory for *happiness* README and visualizations
├── media/               # Output directory for *media* README and visualizations
```
