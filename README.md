# Exploratory Data Analysis on accidents in the US between 2016-23  
This project is a showing of how i conducted EDA on a large dataset.  
The [dataset](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) used is on kaggle.  
To use this notebook you must either download the dataset yourself and put the csv in a folder us-accidents.  
Or put your [kaggle.json](https://www.kaggle.com/docs/api) in the repo folder.  
The notebook depends on:  
```
matplotlib,opendatasets,pandas,seaborn,folium  
``` 
The requirements can be installed using  
```
pip install -r requirements.txt  
```
## Conclusion
1. There is some missing data for 2016.  
2. Source2 and Source3 should be dropped if the data from Source1 is sufficient as the sources are inconsistent.  
3. The data for NY seems to be skewed negatively as it is innacurate with regards to external sources and should be investigated further.  
4. The data does not contain data for Alaska and Hawaii.  
5. Most accidents occour betwen 6-9 am and 3-6 pm.  
6. Most accidents occour on Friday.  
7. Most accidents are in Texas, Florida, California.  