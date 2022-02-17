# Kimchi Regressor

### Aim: The aim of this study is to find out how to estimate kimchi prices with the given variables. 

### Data& Codes:

- Data has numerical columns, date columns and region about sales. 
- There are weekly date for 3 months. 
- Target value is price.

**data:**

- kimchi_data.xlsx: Source data.
    
**experiments:** 

 - kimchi_eda.ipynb: It includes exploratory data analysis to understand data. 
 - kimchi_model.ipynb: Final version of data preprocessing and model experiments. 

**src:** 

 - kimchi_model.py: Production code with predictions containing the selected model.
    
    
### About Model:

![kimchi_pipeline](https://github.com/Sk1613/kimchi-regressor/blob/main/experiments/kimchi_pipeline.drawio.png)


### Next steps:

- Different normalization methods, steps such as feature extraction can be tried.

- Data such as population, weekly weather, or inflation and covid data of regions can be added.

- Since we have a time dimension, time series models can be tried. 
