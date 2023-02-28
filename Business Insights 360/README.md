Problem Statement : This from a project-based learning course from Codebasics and used imaginary company called AtliQ Hardware and discussed its business model. It is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America.
Senior executives of this company have decided to invest in a data analytics project.

Data Collection : 
	1. For data analytics needs, we need short of like a copy of OLTP database 	(Online Analytical Processing) systems. A new system that contains the data warehouses.
	2. Data catalog will enable a data analyst to browse through the list of databases available in the company.
	3. Facts are transaction tables whereas dimensions are entity tables. When we connect them to build a data model, it creates something called a STAR schema.
	4. Collected all the Data from MySQL.
	
Through the data collection by SQL and Imported the data into a Visualization Tool called Power BI. A tool that helps with data transformations. And the Power Query uses the M Language.

Data Transformation : 
	1. Learnt and Understood about the Business Concepts and built YTD (Year To Date). YTG (Year To Go), LE (Landing Estimates) which helps in the analysis of the data.
	2. Power Query has a convenient option to allow the merging of two tables.
 	
Data Modelling :
	1. Calculated more Columns in Power Query and in DAX. The CALCULATE is a frequently used and a important  DAX function.
	2. Started to create Snowflake Schema is an extension of the star schema where dimension tables are further connected with other dimension tables.
	
Building Finance View : 
	1. In the BI DAX started to create New Measure which is a Calculated Field in the  DAX.
	2. Created a Line Chart which shows Performance Over Time in order to compare the current year's trend with last year's trend for a selected metrics.
	3. Well the Gross Margin and Net Profit (Gross Margin - Operational Expenses) are most useful metric for senior management.
	
Building Sales View : 
	1. For the sales team, Gross Margin and Net Sales (Revenue) are more important than the Net Profit as typically they have least or no control over operating expenses.
	2. This View shows about Customer Performance and Product Performance  by Net Sales, Gross Margin, and Gross Margin %.
	3. Also Created a Performance Matrix Scatter Chart which shows scatter dots according to Gross Margin % and Net Sales.
	4. Below the Matrix Chart we have Unit Economics Pie Chart of Net Sales, Total Post Invoice Deduction, and Pre Invoice Deduction another showing the Total Cost Of Goods 	Sold (COGS) and Gross Margin.
	5. Additionally also created a Target Gap Slider and a toggle to change Last year or to the Target Revenue.
	
Building Marketing View :
	1. For the marketing team, it would be important to understand the marketing spend change over a time period and subsequent Revenue / Gross Margin change.
	2. This View shows about Product Performance and Region/Market/Customer Preference  by Net Sales, Gross Margin, Gross Margin %, Net Profit, and Net Profit %.
	3. Made a Toggle Button with the Bookmark Feature in Power BI which Switches the Scatter Chart between Net Profit % and Gross Margin %.
	
Building Supply Chain View:
	1. For the Supply Chain team, the important metrics are Forecast Accuracy&Risk (Out of Stock or Excess Inventory) and Net Error & Absolute Error.
	2. Created a Key Metrics Table by Customers.
	3. Built a Line and Clustered Column Chart of Net Error, Forecast Accuracy %, and Forecast Accuracy % LY by Month.
	4. Below this there is a Key Metrics Products Table shows all the Products with Customer names.
	
Building Executive View:
	1. Stakeholder expectation management is one of the most useful skills which helps in creating an Insightful Visuals.
	2. After the Feedback session with the Executives they told to make a Table which shows Key Insights as per different zones and the Risk for each.
	3. Created a PC market share trend Ribbon Chart in Power Bi, which focuses on AtliQ and it's Competitors.
	4. Besides these, there is also two Pie chart showing about the Revenues by Division and through distribution channels.
	5. Also created a Line and Clustered Column Chart and two table showing Top 5 Customers and Products by Revenue.
	
Also built Info and Help pages in order to maintain contact with the Executives and get feedback on the Visualizations.
