# Belly Button Biodiversity Dashboard

## Project Overview
The Belly Button Biodiversity Dashboard provides an interactive visualization of microbial diversity data collected from human navels. Users can explore various metrics through dynamic charts and metadata panels.

## Instructions

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:Rajamani-M/belly-button-challenge.git

2. **Navigate to the Project Directory:**
   ```bash
   cd belly-button-challenge

3. **Open the Dashboard:**
   [Click here](./index.html) to open `index.html` in your preferred web browser to view and interact with the dashboard.

4. **Deploying the Dashboard:**
   The dashboard has been deployed to GitHub Pages. View the live version [here](https://github.com/Rajamani-M/belly-button-challenge).

## Repository Structure
```bash
belly-button-challenge/
│
├── index.html                  # Main HTML structure
├── samples.json                # Dataset (referenced via URL)
├── README.md                   # Project documentation
└── static/
    ├── js/
    │   └── app.js              # JavaScript for data handling and chart creation
└── output/                     # Images used in the dashboard
    ├── bubble_chart.png
    ├── dashboard.png
    ├── demographic_information.png
    └── horizontal_bar_chart.png
```

## Project Summary

This project implements an interactive dashboard to explore the Belly Button Biodiversity dataset. It includes:

**Horizontal Bar Chart**
- A horizontal bar chart displaying the top 10 OTUs found in the selected sample.

    ![Horizontal Bar Chart](<output/horizontal_bar_chart.png>)


**Bubble Chart**
- A bubble chart visualizing the abundance of OTUs across different samples.

    ![Bubble Chart](<output/bubble_chart.png>)


**Demographic Information**
- A metadata panel providing demographic information for the selected sample.
 
    ![Demographic Information](<output/demographic_information.png>)

**Dashboard**
- The charts and metadata panel update dynamically with sample selection for an interactive user experience.
 
    ![Dashboard](<output/dashboard.png>)



## Software / Libraries
- **D3.js**: For fetching data and manipulating the DOM to create dynamic charts.
- **Plotly.js**: For creating interactive bar and bubble charts.
- **Bootstrap**: For basic styling and responsive layout design.
- **GitHub Pages**: For deploying the dashboard as a live static page.

## Conclusion
The Belly Button Biodiversity Dashboard effectively visualizes microbial diversity in human navels. It demonstrates skills in data handling, dynamic chart creation, and web-based deployment. This project was completed as part of the Module 14 Challenge and meets the requirements for interactive data exploration.
