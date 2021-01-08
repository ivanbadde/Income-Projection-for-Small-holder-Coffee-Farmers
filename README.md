
# Income-Projection-for-Small-holder-Coffee-Farmers

## Summary

An AI tool that can predict coffee farm-gate earnings. 
The aim is to use projected earnings to inform credit appraisals so that small-holder coffee farmers can access credit and financial planning services.


## Background

Small holder coffee farmers in Africa are located within the bottom of the pyramid (BOP).  
Africa’s BOP is characterized by a low penetration of formal financial services. 
Despite operating outside formal financial structures, small holder coffee farms represent the majority of the world’s coffee producers. 
The problem is that without personal financial data that can be used to appraise their credit history, and without any assets that can be used to secure credit, small holder farmers find it difficult to access credit to support their operations and livelihoods. 
The problem is compounded by the aggressive price volatility of farm-gate prices of coffee. The price volatility of coffee makes it difficult for lenders to predict farmer’s earnings, and by extension judge credit worthiness.

The problem is important because without access to reliable credit, the small-holder farmers remain trapped in poverty. 
* Without credit, small-holder farmers find it difficult to adequately manage their farms. They are unable to buy proper farm inputs and supplies, and as a result they have low productivity. 
* Furthermore, they are unable to adequately manage their domestic finances. They can only access cash in-flows post-harvest. The irregular and unpredictable cash flow forces small holder farmers to depend in part on subsistence agriculture to meet their day-to-day needs. This subsistence agriculture takes away prime real estate that could be used to expand coffee yields. 
Through-out most of the year, the small-holder farmer is vulnerable to economic shock. Solving the problem will be a path towards financial security for over 5.5 million small holder coffee farmers in Africa who live below the poverty line.

The project will be piloted in Uganda, where there are 1.7 million small holder coffee farmers. 
Uganda has the highest coffee farmer population in the world. Uganda's coffee farmers are dispersed across the country and generally grow coffee as part of a diversified portfolio of food and cash crops.


## How is it used?

The model will be used to project the earnings of small holder coffee farmers with the goal of using that information to appraise credit worthiness and for fiancial planning. 
The people affected by the model are the 1.7 million small holder coffee farmers in Uganda who might want to access credit and financial planning services but are outside formal financial services. 

![image of a coffee farmer](/coffee farmer uganda.jpg)


## Data sources and AI methods

The AI tool aims to predict small-holder coffee farmer’s income. The output of the model will be a monetary figure in the local currency. 
The approach is to build a linear regression model that will predict framer earning. 
The model will be built with input data on the historical earnings of Uganda’s coffee small-holder farmers in relation to relevant features drawn from the 3 groupings below.

Features that factor into farmer productivity
* Type of coffee grown.
* Experience of farmer in years
* Age of farmer
* Size of planted field 
* Geographic location of farm

Features that factor into the quality of the yield
* Altitude of farm
* Age of coffee bushes
* Number of days coffee is stored between harvest and sale.

Features that factor into local pricing of goods
* International cost of coffee
* Cost of freight to coast
* National inflation
* National GDP 

Data on historic / previous farmer earnings, and data related to the first two feature groupings i.e., relating to productivity and yield, is available with the Uganda Coffee Development Authority (UCDA). UCDA is the public authority that is mandated to promote and oversee Uganda’s coffee industry. 
Data from the third feature grouping and on other national economic indicators in Uganda can be sourced from the Uganda Bureau of Statistics (UBOS). UBOS is a national agency that is the custodian of the country’s vital statistics and data. 


## Challenges

The tool does not do the actual credit appraisal.  It aims to project a reasonably accurate prediction for the farmer’s potential earnings. 
The projected earnings, along with other credit evaluation data, such as applicant’s regular expenses, and existing debt, will inform how much credit can be advanced to the applicant.  
The information can also be used to build a financial management plan for the applicants e.g. by apportioning monetary values to be put towards safety net services like crop and health insurance to mitigate unanticipated shock.


## What next?

The project can be extended to cover the broader bottom of the pyramid in Uganda. Just below 70% of Uganda’s population exists outside of traditional financial services. 
They survive in full or in part on subsistence farming interlaced with limited commercial farming in different sectors to meet immediate monetary needs. 
Models in the same vein can be built to project income for the different sectors, e.g., dairy, grains, cotton, cocoa, fruits, vegetables, animal husbandry etc. 
Similar models can be built for those in the service or menial labour sector.  
By being able to reliably project the BOP’s earnings, you make them eligible for financial services and planning, which will improve their economic outlook.


## Acknowledgments

* National Survey and Segmentation of Smallholder Households in Uganda (2016). Washington, DC 
* Annual agricultural survey 2018 - Uganda Bureau of Statistics
* [Jane Sebbi, a farmer in Kamuli, Uganda] (https://www.flickr.com/photos/28475454@N04/8226722237) by Bread for the World is licensed under CC BY-NC-ND 2.0
