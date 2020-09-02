# Brand-Equity-Research

This repo includes the code and summary descriptives I made to support a brand equity research on beverages. <br/>
Two datasets are included: The first is beverage purchase information (panel data), including buyer ID, time (in week), units, sales, UPC and the second is UPC details like volume, packaging, sweetener, etc. Data period is for 11 years. UPC details are also divided into 3 periods within 11 years because a number of UPCs has information updated over years.<br/>
The related tasks are as below:<br/>
1. Join the two datasets based on upc. (data_panel_upc_join)
2. Describe the data to answer several business questions. (data_description)
3. Document the decision on how to define an observation from the panel data to include in the model. (assumptions_for_data_prep)
4. Analyze the data on ad spend on beverages. (beverage_ad_data_prep)
5. Prepare data as required. (stan_data_prep)
6. Visualize brands by sales. (beverages_data_vis)

## Tool(s):
R
