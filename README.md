# Banking Marketing Campaigns – Exploratory Data Analysis  

## Exploratory Data Analysis (EDA) with Python  

This project analyzes data from telemarketing campaigns conducted by a Portuguese banking institution. The objective is to identify patterns in customer responses, key factors influencing conversion, and potential target segments to optimize future campaigns.  

---

## Project Structure  


├── README.md  
├── EDA_English.ipynb  
├── EDA_Spanish.ipynb  
├── Dataset/  
|   ├── bank-additional.csv  
|   └── customer-details.xlsx  
├── Transformed_dataset/  
|   ├── clientes.csv  
|   └── contactos.csv    

- **EDA_English.ipynb** and **EDA_Spanish.ipynb**: Jupyter notebooks with the full exploratory analysis in English and Spanish.  
- **Dataset/**: Folder containing the original raw datasets.  
- **Transformed_dataset/**: Folder containing cleaned and transformed datasets.   

---

## Dataset Description  

The analysis combines two main data sources:  

1. **bank-additional.csv**: Records from marketing campaign contacts.  
   - Variables: age, job, marital status, education, type of contact, call duration, contact history, and macroeconomic indicators.  
   - Target variable: `y` (whether the client subscribed to the term deposit or not).  

2. **customer-details.xlsx**: Demographic and financial information about customers.  
   - Variables: income, household composition, date of becoming a client, and monthly web visits.  

The files **clientes.csv** and **contactos.csv** store the processed data used for the analysis.  

---

## Tools and Libraries  

- **Python**  
- **Pandas** and **Numpy** for data manipulation and transformation  
- **matplotlib** for visualization  
- **Custom helper functions** for cleaning and type conversion  

---

## Key Findings  

![Correlations graph](grapgh.png)

### Main Indicators  
- **Conversion rate of 11.1%**, reflecting the difficulty of achieving success in telemarketing campaigns.  
- **Call duration** is the strongest predictor of conversion.  
- **Macroeconomic factors** such as `euribor3m` and `emp.var.rate` negatively influence subscription probability.  

### Segmentation and Patterns  
- **Students and retirees** show much higher-than-average conversion rates.  
- **Single customers** convert more often than married or divorced ones.  
- **Higher education level** is associated with better outcomes.  
- **Mobile phone contacts** are significantly more effective than landline contacts.  

---

## Next Steps  

- Develop predictive models to estimate the probability of customer conversion.  
- Conduct temporal analysis to evaluate campaign performance across years.  
- Design segmentation strategies based on the most promising customer profiles.  

---

## Contact  

**Author:** Andrés Nó Gómez  
**Email:** andresnogomez@gmail.com  
