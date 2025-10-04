# T03 — Television Energy Consumption Story

### Data Story Overview
This project tells the story of **television energy consumption in Australia**.  
It helps consumers understand how screen size, brand, and technology affect energy use and electricity bills.

The story is shown through visualisations made in **KNIME** and presented on the website **televisions.html**.  
Each step guides the viewer to make smarter, more energy-efficient TV choices.

**Miro Storyboard:** [View storyboard here](https://miro.com/app/live-embed/uXjVJ_D_1B8=/?embedMode=view_only_without_ui&moveToViewport=-445%2C-641%2C985%2C476&embedId=759284012070)  

---

### Audience
The main audience is **general TV consumers** in Australia.  
They need simple explanations, clear visuals, and practical recommendations for buying energy-efficient televisions.

---

### About the Data
**Source:**  
The dataset comes from the **Australian Government’s Energy Rating Data for Household Appliances – Labelled Products**, available on [data.gov.au](https://data.gov.au/).  
From this collection, the file specifically for **Televisions** was selected.  
It includes details such as brand, model, screen size, technology type, star rating, and energy consumption (in kWh/year).  
A separate **metadata DOCX file** was also downloaded to understand the field descriptions and dataset structure.

**Processing:**  
Data was prepared and visualised using **KNIME**. The following steps were applied:

1. Dropped columns with missing values.  
2. Sorted records by **Model_No** and **Submit_ID**.  
3. Checked for duplicates using **Model_No** and removed them.  
4. Retained only rows where **Availability Status** = “Available”.  
5. Kept only relevant columns for analysis (brand, model, size, technology, and energy data).  
6. Converted all brand names to **uppercase** for consistency.  
7. Converted **screen size from cm to inches** (rounded).  
8. Created summary visualisations (bar, pie, and scatter plots) to explore energy consumption trends.

**Privacy:**  
No personal or identifiable data is included — all information is **public and product-based**.

**Accuracy and Limitations:**  
- The data is self-reported by manufacturers, so there may be **minor inaccuracies**.  
- Some **older or discontinued models** may still appear in the dataset.  
- The dataset reflects **available models at the time of publication**, not necessarily the current market.

**Ethics:**  
The data was used responsibly to support **sustainable consumer choices** and raise awareness about **energy efficiency**.

---

### AI Declaration
Parts of this project (HTML/CSS formatting, text structure, and visual story guidance) were assisted by **ChatGPT (OpenAI)**.  

---

### Website Summary
The television page shows a clear data story through six sections:
1. Intro
2. Types of TV screen technologies  
3. Common screen sizes  
4. Brands with most models  
5. Energy use by technology  
6. Screen size vs power use  
7. Final recommendations for consumers  

---
