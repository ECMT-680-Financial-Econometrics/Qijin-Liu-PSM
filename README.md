# ECMT680
Hi, this is a repository replicating the paper "Heat Exposure and Youth Migration in Central America and the Caribbean"

The main part of this replication is the triple differences method.

It used two datasets:
The study utilizes migration data from censuses conducted in various countries and daily temperature data from the Global Land Data Assimilation System Version 2.
Because the origin data is too big, I split them. These datasets are uploaded as the name like temp_data_year. The Temperature Dataset Description is named as temp_description.
To merge data, use the Temp_merge code. The output is temp_merge_data.parquet.

For GDP data, the World Bank's statistical models and the World Development Indicators database are used.

Data Preparation: Merge migration data with climate data (temperature and precipitation) by origin province and survey year.

Model Estimation: Use a linear probability model to estimate the effects of heat exposure on migration, controlling for demographic and pre-shock variables.
Analysis: Focus on migration outcomes disaggregated by gender and education level, specifically examining the migration of unskilled workers.

Google Colab link: 
Temp_merge code: https://colab.research.google.com/drive/1VTZb_5Dn21WJHRXePJhVQUwB33iJXOQT?usp=sharing 
