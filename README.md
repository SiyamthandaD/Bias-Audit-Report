Bias-Audit-Report

This React app provides an interactive dashboard for comprehensive bias auditing. It visualizes overall bias/fairness scores, analyzes datasets for bias factors (e.g., race, income), and evaluates model performance with and without mitigation strategies. The tool helps identify disparities and recommends actions for continuous improvement in AI fairness.

Features
Interactive Dashboard: Displays overall bias score, fairness score, and data quality score.

Dataset Analysis: Provides insights into dataset biases, including demographic representation, bias scores by attribute (e.g., Race, Income Level, Geography), and data quality metrics. Identifies affected demographic groups and recommends actions.

Model Analysis: Evaluates model performance across different groups (e.g., Male, Female, Non-binary) before and after applying mitigation strategies, highlighting performance disparities and high-disparity groups.

Mitigation Strategies: Outlines various strategies for addressing bias at both dataset and model levels, along with their effectiveness, effort, and description. Includes evaluation and monitoring strategies.

Action Plan: Presents a recommended action plan with short-term, mid-term, and long-term steps for implementing bias mitigation.

Dynamic Data Loading: Supports the analysis of different datasets and models (e.g., Loan Approval, Tech Hiring, Healthcare Access).

Data Visualization: Utilizes Chart.js to render various charts (Bar, Pie) for clear data representation.

Installation
To get a local copy up and running, follow these simple steps.

Prerequisites
Node.js (LTS version recommended)

npm (comes with Node.js)

Setup
1. Clone the repository:
git clone https://github.com/your-username/Bias-Audit-Report.git

  cd Bias-Audit-Report

2. Install NPM packages:
npm install

Usage
1. Start the development server:
npm start

This will open the application in your default web browser at http://localhost:3000.

Navigate the Dashboard: Use the navigation links (Dashboard, Dataset Analysis, Model Analysis, Mitigation Strategies) to explore different aspects of the bias audit report.

Select Datasets/Models: Use the dropdown menus in the header to switch between different sample datasets and models to view their respective bias analysis.

Technologies Used
React: A JavaScript library for building user interfaces.

Chart.js: Flexible JavaScript charting for designers & developers.

React Chartjs 2: React wrapper for Chart.js.

CSS: For styling the application.
