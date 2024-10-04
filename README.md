# Google Trends and Event Sensitivity Analysis

## Overview

This project aims to analyze how internet usage for gathering information has evolved over the years and assess whether public sensitivity to significant events has changed. By leveraging Google Trends data and Wikipedia event summaries, we will investigate search behavior surrounding major events, comparing trends from the past with those of the present.

## Objectives

1. **Internet Usage Analysis**: 
   - Compare past and present internet usage patterns for gathering information through Google Trends.
   - Analyze how search behaviors have shifted over time regarding key global events.

2. **Public Sensitivity Assessment**:
   - Evaluate if people's focus on significant events has changed by examining search frequency and duration in relation to real-world occurrences.
   - Investigate whether the relevance of events, as judged by search interest, has fluctuated over the years.

## Methodology

1. **Data Collection**:
   - **Google Trends**: Use the PyTrends library to extract search data related to significant events from specific years.
   - **Wikipedia Events**: Extract event summaries and timelines using the Wikipedia API or web scraping techniques.

2. **Data Processing**:
   - Utilize a Language Model (LLM) to transform extracted text data:
     - Generate concise summaries of events.
     - Assign a relevance score to each event based on its impact and public interest.

3. **Analysis**:
   - Compare trends in search data with the relevance scores of events.
   - Analyze patterns in search behaviors and public sensitivity over time.

4. **Visualization**:
   - Create visual representations (e.g., line graphs, heatmaps) to illustrate the relationship between event relevance and search trends.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages (to be listed in `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/google-trends-event-analysis.git
   cd google-trends-event-analysis

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
 
