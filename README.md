# Opportunity-Pipeline-Forecasting

**Background:**

The sales group of a technology and chip manufacturing company is provided with annual targets in $ that they need to sell. The team tries to achieve the same by pursuing multiple opportunities (an opportunity can be defined as a potential customer with specific asks of products in type, design and quantity with their $ values negotiated) across customers and business segments.

The sales enablement group of the same organization has identified that while a number of opportunities are being pursued, the sales group lacks a means to quantify the potential of conversion of these group of opportunities (hereon referred as sales pipeline portfolio) within a specific timeframe (say a quarter). The conversion potential of a sales pipeline portfolio is realized by,

Quality of an opportunity: How likely is an opportunity to convert within a specific timeframe? 

**Data:**

Company will provide the following data for the project:
All Opportunities along with relevant product sells, across different customers from 2015 to 2016 - Q3
Company will also provide a clear and detailed description of the dataset including all the fields present. Company will make available knowledgeable personnel to provide any necessary background on data and business context. These personnel will also help Tiger in working with the end consumers of our models and identifying which features could be actionable. They would also help in corroborating findings from the models and can help provide an insider’s business perspective into the forecasting models.
Additional Data Explanation:
Stages: The stages in the file have a number. Following is a description and progression: 
[ 6: Qualify ]->[ 5 : Define]->[ 3: Develop ]->[ 2: Design ]->[ 4: Design Win ]->[ 9: Production Win ] 
Ignore: Stage 7: Group
Loss Stages: Stage 1: Cancelled | Stage 8: Lost

Geographies to Ignore:
Unassigned Geographies: Geo NA or Geo 1


**Deliverables:**

**Data Preparation from Opportunity header and transactional Tables.**

Demonstrates:
Understands movement of Opportunities lines through stages
Is able to pictorially represent transition between stages
Tests suitable hypothesis:
Is time taken between stage transitions significantly different across geographies?
Are Losses (Opportunity lines in Lost stage) more likely to happen in early stages (Qualify and define)
Does the proportion of Won lines in an Opportunity significantly different across Product Categories?
Develop appropriate charts to represent above tests
Create a structured report with missing data and impute with appropriate justification

**Score opportunities for likelihood of conversion.**

Demonstrates:
Merge Opportunity with Product data (monthly snapshot)
Creates a dependant variable based on movement to a "win" stage
Performs appropriate categorical data transformation
Builds a Logistic model
Selects suitable variables
Explains model and outcome and key drivers
Shows results on a hold out
