# Environment_Impact_of_Food_Production_Analysis
This project focuses on analyzing the environmental impact of food production, with an emphasis on key metrics such as carbon emissions, water usage, land use, and biodiversity loss. through the use of data visualization. It includes data engineering; data wrangling, data visualization; documentation and actionable insights for all stakeholders.

## Business Problem Statement

<b><i>Current food production systems are driving irreversible environmental damage from climate change and water scarcity to biodiversity loss yet consumers, policymakers, and producers lack actionable insights to identify which foods deliver the most nutritional value with the least ecological cost.</i></b>

## Business Questions

1. What is the relationship between Emission Stages ?

2. What is the Distribution of Total Emissions for all Food Products ?

3. What are the top 10 Food Products per Total Emissions ?

4. Which Food Products are Sustainable per their Protein Levels ?

5. Which Food Products are Sustainable per their Protein Levels ?

6. Which Food Products are Sustainable per their Caloric Levels ?

7. Which Food Products are Sustainable per their Weight ?

## Dataset Description

#### Food_Production.csv

`Food product` : (numeric)

`Land use change` : (numeric)

`Animal Feed` : (numeric)

`Farm` : (numeric)

`Processing` : (numeric)

`Transport` : (numeric)

`Packging` : (numeric)

`Retail` : (numeric)

`Total_emissions` : (numeric)

`Eutrophying emissions per 1000kcal (gPO₄eq per 1000kcal)` : (numeric)

`Eutrophying emissions per kilogram (gPO₄eq per kilogram)` : (numeric)

`Eutrophying emissions per 100g protein (gPO₄eq per 100 grams protein)` : (numeric)

`Freshwater withdrawals per 1000kcal (liters per 1000kcal)` : (numeric)

`Freshwater withdrawals per 100g protein (liters per 100g protein)` : (numeric)

`Freshwater withdrawals per kilogram (liters per kilogram)` : (numeric)

`Greenhouse gas emissions per 1000kcal (kgCO₂eq per 1000kcal)` : (numeric)

`Greenhouse gas emissions per 100g protein (kgCO₂eq per 100g protein)` : (numeric)

`Land use per 1000kcal (m² per 1000kcal)` : (numeric)

`Land use per kilogram (m² per kilogram)` : (numeric)

`Land use per 100g protein (m² per 100g protein)` : (numeric)

`Scarcity-weighted water use per kilogram (liters per kilogram)` : (numeric)

`Scarcity-weighted water use per 100g protein (liters per 100g protein)` : (numeric)

`Scarcity-weighted water use per 1000kcal (liters per 1000 kilocalories)` : (numeric)


<b>Available datasets:</b>

Food_Production.csv:

<b>Link</b>: https://azubiafrica-my.sharepoint.com/personal/teachops_azubiafrica_org/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fteachops%5Fazubiafrica%5Forg%2FDocuments%2FTMP%2FProject%203%20Environment%20Impact%20of%20Food%20Production&ga=1

###  Dataset Preview

| Food product | Land use change | Animal Feed | Farm | Processing | Transport | Packging | Retail | Total_emissions | Eutrophying emissions per 1000kcal (gPO₄eq per 1000kcal) | Eutrophying emissions per kilogram (gPO₄eq per kilogram) | Eutrophying emissions per 100g protein (gPO₄eq per 100 grams protein) |  Freshwater withdrawals per 1000kcal (liters per 1000kcal) | Freshwater withdrawals per 100g protein (liters per 100g protein) | Freshwater withdrawals per kilogram (liters per kilogram) | Greenhouse gas emissions per 1000kcal (kgCO₂eq per 1000kcal) | Greenhouse gas emissions per 100g protein (kgCO₂eq per 100g protein) | Land use per 1000kcal (m² per 1000kcal) | Land use per kilogram (m² per kilogram) | Land use per 100g protein (m² per 100g protein) | Scarcity-weighted water use per kilogram (liters per kilogram) | Scarcity-weighted water use per 100g protein (liters per 100g protein) | Scarcity-weighted water use per 1000kcal (liters per 1000 kilocalories) |
| :----------- | :---------------| :---------- | :--- | :--------- | :-------- | :------- | :----- | :-------------- |:------- | :----- | :-------------- | :----- | :-------------- |:------- | :----- | :-------------- | :----- | :-------------- | :----- | :-------------- |:------- | :----- |
| Wheat & Rye (Bread) | 0.1 | 0 | 0.8 | 0.2 | 0.1 | 0.1 | 0.1 | 1.4 |  |  |  |  |  |  |  |  |  |  |  |   |  |  |
| Maize (Meal) | 0.3 | 0 | 0.5 | 0.1 | 0.1 | 0.1 | 0 | 1.1 |  |  |  |  |  |  |  |  |  |  |  |   |  |  |
| Barley (Beer) | 0 | 0 | 0.2 | 0.1 | 0 | 0.5 | 0.3 | 1.1 |  |  |  |  |  |  |  |  |  |  |  |   |  |  |
| Oatmeal | 0 | 0 | 1.4 | 0 | 0.1 | 0.1 | 0 | 1.6 | 4.281357225 | 11.23 | 8.638461538 | 183.9115517 | 371.0769231 | 482.4 | 0.945482272 | 1.907692308 | 2.897445673 | 7.6 | 5.846153846 | 18786.2 | 14450.92308 | 7162.104461 |


### Slide Deck

<b>Link</b>: https://docs.google.com/presentation/d/1SmQl-iX92Vw34gM7Buby8IZa_74RSavk6KXFmAf7XZI/edit?slide=id.g37e71c5738d_0_2#slide=id.g37e71c5738d_0_2

---

## Project Key Findings

1. Beef (beef herd) emits 59.6 kg CO₂e/kg, nearly 10x more than poultry (6.1) and 3x more than lamb. Replacing beef with plant-based proteins offers the highest emission reduction potential. 

2. The distribution of total emissions is right-skewed: most foods emit <10 kg CO₂e/kg, but a small number (beef, cheese, dark chocolate) drive the majority of impact. Focus interventions here.

3. Over half of all food emissions come from farm-level activities. Land use change (21.1%) and animal feed (7.6%) are also major contributors in making agriculture the primary lever for change.

4. Per 100g protein, peas emit just 0.001 kg CO₂e, 72x less than poultry (0.072). Pulses, nuts, and soymilk consistently outperform animal proteins across all metrics. 

5. Beet sugar (0.005), palm oil (0.006), and potatoes (0.013) deliver energy with minimal emissions per 1000 kcal, but should be balanced with nutritional density to avoid empty-calorie diets.

6. Soymilk (0.001), root vegetables (0.001), and apples (0.001) have the lowest emissions per kg, ideal for logistics and volume-based sourcing, though nutrition must be considered. 

7. Swapping beef for lentils or cheese for plant-based alternatives can reduce emissions by 80–90% while cutting costs and maintaining consumer satisfaction. A true triple win.

8. Farming correlates strongly with land use change and processing (correlation >0.65). Interventions in one stage (e.g., regenerative farming) ripple through the entire system.

10. Businesses can begin by replacing 1 high-emission item (e.g., beef) with a low-emission alternative (e.g., peas), track emissions saved, and expand, turning data into measurable impact. 

---

### Folder Structure (After Setup)

project/

├── .gitignore

├── LICENSE

├── requirements.txt ← Required Packages

├── Food_Production.csv ← dataset

├── main.ipynb ← Data Notebook

└── README.md


## Getting Started:

### How to Run: Step-by-Step

#### Step 1: Clone this Remote Repository

```bash
git clone https://github.com/02sagoe/Environment_Impact_of_Food_Production_Analysis.git
```

#### Step 2: Change the Working Directory

```bash
cd Environment_Impact_of_Food_Production_Analysis
```

#### Step 3: Ensure `data.zip` File is Downloaded into this Directory (IMPORTANT)

#### Step 4: Ensure `data.zip` is Extracted into this Directory (IMPORTANT)

#### Step 4: Create a New Virtual Environment

```bash
virtualenv venv
```

#### Step 5: Activate your Virtual Environment

```bash
venv\scripts\activate
```

#### Step 6: Install the Required Packages using

```bash
pip install -r requirements.txt
```

#### Step 10: Open Notebook File and Interact with Cells in Order

* Use this notebook: python `main.ipynb`


### Questions?

If you have any questions about the implementation, want to improve the model, or need help deploying it, feel free to reach out!

Email: kbwsagoe@gmail.com

LinkedIn: https://www.linkedin.com/in/kbsagoe/