# ML_Predicting_Property_Values

This research focuses on analyzing a data set from the Property Appraiser’s office in Orange County, Florida. 
The Property Appraiser (Assessor) office in Florida is a local government agency that determines the values of properties within a certain geographic area for taxation purposes. 
The goal of the office is to fairly and equitably determine the value of properties based on various characteristics and market conditions. 
The office uses mass appraisal techniques in determining property values. 
With the support of the computer-assisted mass appraisal system (CAMA), which allows to model and mass update data, the analysts at the property appraiser’s office evaluate each property strata to ensure the assessments are within the acceptable standards defined by the Florida Department of Revenue (DOR) and the appraisal industry.

The data set used in this work lists qualified single-family residential properties sold in 2019. To be qualified, the sale of a property had to meet certain pre-defined criteria for its Sales Price to be an indication of the property’s market value. 
Each property is identified by a unique parcel ID, situs address, various location characteristics, and property features. 
The goal of this project is to build an ensemble model that predicts the values of the properties using these characteristics and features. 
The performance of the model is measured by the value of the mean squared error (MSE), the square of the difference between the predictions and the targets. 
This is a widely used loss function for regression problems such as predicting property values. 
The key steps involved in the analysis are wrangling and exploring the data, feature engineering and preprocessing of the data, tuning model’s parameters, fitting various models (including a deep learning model), and building the final ensemble model that yields the lowest MSE. 
Given that this model needs to meet the requirements defined by the DOR, we will also test it against the acceptable ratio standards.
