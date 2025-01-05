# FPL Cruncher: A Fantasy Premier League Analysis Tool

![2025-01-0600-54-54-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/0e8d8ab1-687d-45ca-827f-968c4d58bced)


## Overview
The **FPL Cruncher** is a Python-based application designed to analyze and extract key statistics from Fantasy Premier League (FPL) data. Users can input their team ID, mini-league ID, and specific gameweek preferences to generate tailored insights. The tool dynamically creates an HTML file containing visualizations and statistics, providing an engaging and user-friendly way to explore FPL data.

---

## Key Features
- **Dynamic Input Parameters**:
  - Team ID
  - Mini-League ID
  - Gameweek selection (current or specified gameweek)
- **Automated HTML Report Generation**:
  - Outputs a custom HTML file containing detailed visualizations and insights.
- **Interactive Visualizations**:
  - Leverages `Matplotlib` and `Seaborn` to create high-quality charts and graphs.
- **Streamlined Data Extraction**:
  - Fetches FPL data through APIs, ensuring accurate and up-to-date analysis.

---

## How to Use

### Step 1: Find Your Team ID
1. Log into the official Fantasy Premier League website.
2. Click on the **Pick Team** tab.
3. On the right, click the **Gameweek History** link.
4. Check the URL in your browser address bar. The number in the URL is your Team ID.

### Step 2: Find Your League ID
1. Log into the official Fantasy Premier League website.
2. On the right, locate your mini-leagues and click on the name of the desired league.
3. Check the URL in your browser address bar. The number in the URL is the League ID.

   **Note**: Only classic leagues with fewer than 5,000 managers are supported.

### Step 3: Run the Analysis
1. Open the project notebook in Jupyter or Google Colab.
2. Run the "Code" group of cells to initialize the tool.
3. Run the "For User" cells and follow the prompts:
   - Enter your **Team ID**.
   - Enter your **League ID**.
   - Choose whether you want the **current gameweek** or specify a gameweek number.
4. Wait a few seconds for the analysis to complete.
5. Once the results are displayed:
   - Click the icon in the top-left corner of the output.
   - Select **View Output Full Screen** to view the detailed report.

---

## Technical Highlights
- **Python Libraries Used**:
  - `requests`: For fetching data from the FPL API.
  - `pandas`: For data manipulation and cleaning.
  - `matplotlib` and `seaborn`: For creating visualizations.
  - `os`: For managing file creation and storage.
- **Web Integration**:
  - Generates HTML content dynamically using Python, ensuring easy sharing and accessibility.
- **Customizable Outputs**:
  - The tool adapts to user inputs, allowing personalized insights for any FPL team or mini-league.

---

## Future Enhancements
- Deploy the tool as a web application for broader accessibility.
- Add more interactive visualizations and detailed player analytics.

---

## Conclusion
The FPL Cruncher is an innovative tool for Fantasy Premier League enthusiasts, combining the power of Python with interactive visualizations to deliver personalized insights. Whether you’re a casual player or a competitive manager, this tool provides the edge you need to succeed in your FPL mini-league.
