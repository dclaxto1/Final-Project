# Final-Project - Mechaine learning    
 Solve, analyze, and visualize a problem using machine learning (ML) with the other technologies.   
  
       
1. [ETL](#etl)  
2. [Machine Learning](#machine-learning)  
   - [Model 1](#model-1)
   - [Model 2](#model-2)    
   - [Model 3](#model-3)  
3. [Analysis](#analysis)    
4. [Key Findings Based on our Dataset](#key-findings)
5. [File notes](#file-notes)



## ETL <a name="etl"></a>
We gathered this data from Kaggle and transformed it using Python Pandas. We received the data in a raw csv file. <br />

![image](https://github.com/dclaxto1/Final-Project/assets/128431134/d85d2429-f78f-41a1-a07b-940025fa3609)

We added a new column to contained binned aged we planned on using. <br />

![image](https://github.com/dclaxto1/Final-Project/assets/128431134/5a7f6f53-f704-4ff1-ba66-44d85c5c08a4)

After finishing and transforming the data we then exported it to a sqlite database.  <br />

![image](https://github.com/dclaxto1/Final-Project/assets/128431134/de1bd81f-e63b-44db-b575-deb3f5f10ead)

## Mechine learning <a name="machine-learning"></a>
We created three supervised mechine learning models:

### Model 1 <a name="model-1"></a>
![image](https://github.com/dclaxto1/Final-Project/assets/128431134/f860790c-58c1-4b3b-8f5a-06ee8bd8968c)


### Model 2 <a name="model-2"></a>
![image](https://github.com/dclaxto1/Final-Project/assets/128431134/5a325253-56f8-4664-afc2-b0ac8751b59d)

### Model 3 <a name="model-3"></a>
![image](https://github.com/dclaxto1/Final-Project/assets/128431134/7b96bc41-6753-4ba5-ac17-dc992f12879f)

We were able to get a final best accuracy of **0.9643**

## Analysis <a name="analysis"></a>
Lastly, we used Tableau to analysize and visualize the findings.<br />

![image](https://github.com/dclaxto1/Final-Project/assets/128431134/716e7a9a-d494-4caf-8f55-c435458a8abf)
![image](https://github.com/dclaxto1/Final-Project/assets/128431134/991ef825-d455-4985-b6b2-a76986b91caf)

## Key Findings Based on our Dataset <a name="key-findings"></a>
**Males are more likely to develop diabetes.**

**Females with hypertension have a 97% chance of developing diabetes in their lifetime.**

**Overall, individuals with diabetes are twice as likely to have hypertension.**

**Current AND former smokers are more likely to develop diabetes.** 

**Seniors (61+) are the most vulnerable group with 22.23% of seniors having diabetes.**
 
## File notes <a name="file-notes"></a>
The resources folder contains the csv data which we used to form dataset. <br />
The Main_ETL.ipynb file contains our ETL code.<br />
The Machine_Learning_Code_1.ipynb file contains the main mechine learning model code. <br />
The Tableau Module 18.twbx contains the Tableau workbook with our visualizations








