## Overview

This project demonstrates business analytics using synthetic datasets from Kaggle. It leverages Quarto Markdown (QMD) and R to perform descriptive analysis and inferential modeling using interactive visualizations.

## Running the Project

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/saurabveersingh/quarto-interactive-analysis.git

   ```

2. **Install Required R Packages**

   ```r
   install.packages(c("dplyr", "ggplot2", "psych", "plotly", "leaflet", "ggmap", "mgcv", "gratia", "forecast"))

   ```

3. **Execution of Geographical Data Analysis**

   a: Make a .Renviron file in this project. <br />
   b: Add a variable by the name "GOOGLE_API_KEY" in this environment file. <br />
   c: Insert a valid google maps api key. <br />

   Note: The .Renviron is specified in .gitignore and would not be uploaded to github

4. **Render the QMD File**

   Open `index.qmd` in your preferred editor (e.g., RStudio) and render it to HTML using Quarto.
