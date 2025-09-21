🚗 Automobile Dataset – Exploratory Data Analysis  

📌 Project Overview  
This project performs an **Exploratory Data Analysis (EDA)** on the **Automobile dataset**, focusing on price, fuel efficiency, and technical specifications.  
The goal is to **clean the dataset, explore relationships, and answer key analytical questions** such as:  
- Which manufacturers build the most fuel-efficient cars?  
- Which vehicles have the largest engine capacity?  
- Which manufacturer has the widest range of models?  

📂 Dataset  
- **Source:** automobile.txt  
- **Size:** 205 entries, 26 columns  
- **Features:** technical attributes (engine size, horsepower, mpg, price, etc.) and categorical attributes (make, body style, fuel type, etc.)  
- **Target:** Not supervised – exploratory analysis only  

Sample Data:  

| make        | fuel-type | body-style | engine-size | horsepower | city-mpg | highway-mpg | price  |
|-------------|-----------|------------|-------------|------------|----------|-------------|--------|
| alfa-romero | gas       | convertible| 130         | 111        | 21       | 27          | 13495  |
| audi        | gas       | sedan      | 136         | 115        | 18       | 22          | 17450  |
| bmw         | gas       | sedan      | 164         | 121        | 20       | 25          | 20970  |

⚙️ Approach  

**Data Cleaning**  
- Dropped redundant columns: `normalized-losses`, `symboling`  
- Removed duplicates and rows with missing values  
- Converted numeric columns to `int64`  

**Exploration Steps**  
- Located specific categories (e.g., hatchbacks)  
- Identified most expensive vs cheapest cars  
- Compared price with fuel economy  
- Analyzed fuel efficiency across manufacturers  
- Examined largest engine capacities  
- Counted manufacturer model variety  

📊 Results  

**5 Most Expensive Cars**  
- Mercedes-Benz (Hardtop, $45,400)  
- BMW Sedan ($41,315)  
- Porsche Convertible ($37,028)  

**5 Cheapest Cars**  
- Subaru Hatchback ($5,118)  
- Chevrolet Hatchback ($5,151)  
- Mazda Hatchback ($5,195)  

**Findings:**  
- Expensive cars often have **larger engines and lower fuel economy**  
- Cheapest cars show **better mpg due to smaller engines**  
- **Chevrolet** builds the most fuel-efficient cars (avg ~43.6 mpg)  
- **Mercedes-Benz & Jaguar** rank lowest in fuel economy  
- Vehicles with the **largest engine capacities** include Mercedes-Benz and Porsche models  
- **Toyota** is the top manufacturer by number of models (32)  

✅ Key Takeaways  
- Data cleaning reduced noise and ensured reliable insights  
- Higher price often correlates with performance but sacrifices fuel efficiency  
- Manufacturer-level analysis reveals brand focus (luxury vs economy)  
- Toyota dominates in diversity of car models in this dataset  

🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Tools:** Jupyter Notebook  

👨‍💻 Author  
**AiVintage (Veli)**  
_Data Science Graduate | Skilled in Python, Machine Learning, AI, SQL & Data Analysis_  
[GitHub](https://github.com/AiVintage) | [LinkedIn](#)  
