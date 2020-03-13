# Retail_Analytics
 
The attached data set with a total of 892955 observations contains inventory accuracy records from a number of Grocery stores. 
The ‘adjustment unit quantity’ is the unit variance that 3rd party auditors confirmed upon visiting a store, 
e.g., the first example below (-1) means that the auditing company found one less bowl of tropical fruit than 
the stores perpetual inventory had on record. The subsequent example (+14) means that the auditors counted fourteen 
more peach fruit bowls than the stores perpetual inventory. Your objective is to work the data set in R: i) 3 ‘actionable’ 
insights on inventory accuracy (by store, commodity, variance amounts, etc..) ii) Plots with supporting insights that 
visualize your story in ggplot.

Analysis
Store 420 followed by store 907 has the maximum value for a commodity of negative variation from the stores perpetual value.
Store 907 has the maximum value for a commodity of positive variation from stores perpetual value.
Store 720 has the least variations in the commodities from stores perpetual values.

Getting more specific to commodities, Store 420 has the maximum value for a commodity- ‘973 Basic Girl’ of negative variation 
from the stores perpetual value. This is followed by Store 907, commodity -‘790 Kitchen’
Store 907 has the maximum value for a commodity - ‘790 Kitchen’ of positive variation from stores perpetual value. 
Store 720 - ‘121 Cigerettes’ has the least variations in the commodities from stores perpetual values.

For all the 30 stores, Total of positive Unit variations is the maximum for Commodity - 202- Candy-Packaged, 
followed by 751 Firewoodfirestarts and 210-candy-checklane, when grouped by Commodity name and GTTN description.

For all the 30 stores, Total of negative variations is maximum for commodity - ‘973 Basic Girl’ followed by 
‘202 Candy Packaged’, ‘790 Kitchen’ ‘121- Cigerattes and ’098 European Foods’, when grouped by Commodity and GTTN number.

For all the stores, the commodities as in the figure has a total of Zero variations in all for '222 Reader Glasses,
'297 NF Aloe Vera', '357 Refrigerated Asian', '425 Seafood Catfish,'505 Beaf Thin meats', '566 Exotic',
'755 Outdoor storage and pet','The seafood snapper' and '971 Video games Hardware.

Analysis did show that there were large number of outliers with the 25th percentile value of Adjustment Unit quantity as -1 and 75th percentile as 1.

In the retail business, it is good to keep and analyse outliers to assess the demand ofcommodities and to take advantage of high demands and find out why the demands are low. The demands in-turn reflects the effect on the profit and loss for the stores.

Besides individual max and min Unit variations, the sum of all the variations by commodity, or by grouping with store or GTIN, the supplier get a perspective of the variations for a set period and can investigate for the outliers for the cause and the impact on the profit or loss and reducing unnecessary inventory.

 

 
 

 
