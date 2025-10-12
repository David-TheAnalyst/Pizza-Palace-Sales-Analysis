# Pizza-Palace-Sales-Analysis

<div align="center">
  <img src="https://github.com/David-TheAnalyst/Pizza-Palace-Sales-Analysis/blob/main/Pizza%20Showcase.png" alt="Flowpal Sales Dashboard Additional View" width="1000" height="600">
</div>

## **Introduction:**

The primary objective is to conduct a deep-dive analysis of Pizza Palace's sales transaction data to move beyond high-level sales volume and precisely identify the product, price, and temporal intersections that drive maximum profitable revenue. The goal is to provide Menu Developers and the Marketing Team with a data-driven blueprint for prioritizing high-return activities and eliminating generalized effort.

The core challenge facing Pizza Palace is the subtle loss of efficiency and profit caused by generalized effort as menu resources and operational capacity are spread thin catering to low-volume items. The analysis solves this by providing a blueprint to transition from blanket staffing and broad menu management to precision deployment, ensuring that every hour, every day, and every menu item maximizes profit.


## **Story of Data:**

The sourced data from Kaggle houses the complete record of all the 48620 transactions executed by Pizza Palace for the year 2015. It is structured as a list of individual sales transactions, with columns detailing product characteristics and sales outcomes.

The 12-column dataset contains the Pizza_category, Pizza_size, Pizza_name, and the derived temporal fields (Hour_of_day, Month, Day of Week) are used to segment demand while the Quantity, Unit_price, and Total_price are the key metrics for measuring profitability and customer preference. 


## **Pre-Analysis:**

**Independent Variables:** Pizza_name, Pizza_size, Hour_of_day, Month.

**Dependent Variables:** Quantity, Total_Price

**Industry:** Pizza Sales & Distribution Industry defines success. And success is defined by maximizing profitable revenue growth while optimizing customer satisfaction and operational efficiency. 

**Stakeholders:** The key beneficiaries of this report include Chief Executive who will use this for strategic planning, Menu Developers for product retirement/R&D, Marketing Team for campaign timing/focus, and the Finance Department for budget allocation and inventory.

**Value to the Industry:** The analysis provides an immediate efficiency gain by identifying low-return menu items for discontinuation, freeing up inventory capital and prep time to reinvest in high-return products. 



## **In-Analysis:**

The In-analysis phase was dedicated to using advanced Excel segmentation to validate the specific opportunities for optimization.

I used the derived Hour_of_day and Day of Week fields to create frequency and revenue charts that guide staffing and promotion timing. I also created Unit price bins ($10−$20, $20−$30, etc.) to confirm the customer's acceptable spending threshold and define future bundle pricing.

The analysis shows that "Classic" pizza category and "The Thai Chicken Pizza" are responsible for a disproportionate share of total revenue, signaling high customer loyalty. Chicken is a clear market preference, seeing it’s featuring in three of the top six best-selling pizzas.

The data also suggest that customers overwhelmingly prefer Large and Medium pizzas, with spending concentrated in the $10−$20 and $20−$30 price ranges, indicating a willingness to pay more for size while remaining budget-conscious. Furthermore, Sales peak at the end of the week (Thursday to Saturday), with Friday confirmed as the single highest revenue day.

The key initial insight is the wastage on extreme sizes. The minimal sales for XL and XXL pizzas clearly signals that resources allocated to these categories are inefficient and should be redirected.


## **Data Visualizations & Charts:**

Below is a single-page, high-level, drillable dashboard is required for the Chief Executive and Finance Department.

 <div align="center">
  <img src="https://github.com/David-TheAnalyst/Pizza-Palace-Sales-Analysis/blob/main/Pizza%20Palace%20Sales%20DB.png" alt="Flowpal Sales Dashboard Additional View" width="1300" height="auto">
</div>

**Slicers:** Pizza Category

**Key Metrics Displayed:**

- Total Sales: 481
- Order Count:48620
- Quantity Sold: 49574
- Category Leader: Classic
- Best Selling Pizza: Thai Chicken 
- Top Sales Days: Friday

**Charts and Graphs Used:**

**Pie Chart:**
- Top 3 Best Selling Pizza Size

**Column Chart:** 
- Sales By Pizza Category
- Top 5 Best Selling Days
- Top 5 Best Pizza Transaction
- Top 6 Best Selling Pizza Name
  
**Line Chart:** 
- Sales Trend Report
- Total Quantity Ordered by Hour of Day


## **Observations:**

1.	Revenue must pivot entirely around the Chicken-Classic-Large size axis. The commitment of resources to this core area guarantees the highest returns.

2.	The customer base is highly elastic but loyal within the $10−$30 transaction range. Promotions must utilize this range (e.g., combo meals at $29.99) rather than attempting to push expensive, low-volume items.

3.	The discontinuation of XXL size and transition of XL to special-order only will immediately free up inventory costs and reduce operational complexity in the kitchen.

4.	There is a critical need to increase staff by 20%−30% during the Lunch Rush (12-1 PM) and on Fridays/Saturdays, while simultaneously reducing staff during the slow mid-afternoon periods to match demand peaks.

5.	The success of unique pizzas like Thai Chicken justifies a dedicated R&D mandate to develop new, bold, and culturally-inspired chicken offerings to capture this proven demand.

**Comparison with Initial Findings:** 

The initial observation of high sales volume for the Classic category was validated and operationalized. The analysis moved from merely knowing "Friday is busy" to precisely identifying the 12−1 PM lunch rush and the specific low-volume days (Tuesday/Wednesday), enabling targeted, measurable interventions for the first time.


## **Recommendations:**

1.	Menu Optimization (Menu Developers): Discontinue the XXL size immediately. Transition the XL size to a pre-order or catering-only basis to save inventory and prep time.

2.	Demand Creation (Marketing Team): Introduce a high-value, targeted promotion like a Wednesday BOGO (Buy One Get One) or a "Tuesday Student Discount" to create new demand and flatten the mid-week sales trough.

3.	Operational Scheduling (Chief Executive): Implement a 20%−30% staffing increase during the 12−1 PM Lunch Rush and on Fridays/Saturdays, and reduce staffing during the low mid-afternoon hours.

4.	Seasonal Planning (Marketing/Finance): Proactively plan for "push" promotions in February and September to mitigate sales dips, and "pull" promotions  in July and November to maximize peak revenue.

5.	Focus all value bundles and combo meals specifically within the high-performing $10−$30 price ranges to increase the Average Order Value (AOV) without alienating the core customer base.

6.	Implement a loyalty program that specifically rewards repeat purchases of the Classic pizza category and The Thai Chicken Pizza to strengthen loyalty to the most profitable items.


The most powerful unexpected outcome is the success of culturally-inspired flavor profiles. While the Classics lead in volume, the exceptional performance of "The Thai Chicken" and "The Spicy Italian" validates a key R&D strategy that customers are willing to embrace and pay a premium for bold, unique flavors when executed well.


## **Conclusion:**

The analysis conclusively proves that Pizza Palace's path to maximum profitable revenue lies in a strict focus on the Chicken-Classic-Large size axis. The data provides a precise roadmap for the Marketing and Operations teams to retire low-return activities (XXL/XL sizes, generalized staffing) and aggressively reinvest in high-return zones (mid-week promotions, lunch rush staffing, and culturally-inspired chicken R&D). 

However, the primary limitation is the lack of sales data segmented by store location, which is necessary to identify best-practice stores and address underperformance


## **Future Research:**

A necessary follow-up to analyze sales performance by store location to refine local marketing and identify high-performing models.


## **References:** 

•	Pizza Palace Sales Transaction Dataset (Source)

•	Microsoft Excel (Analytical Tool)


<h3 align="left">Connect with me on Socials:</h3>
<p align="left">
<a href="https://linkedin.com/in/david ojo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="david ojo" height="30" width="40" /></a>
<a href="https://twitter.com/david_ojo_1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="david_ojo_1" height="30" width="40" /></a>
<a href="https://medium.com/@davidojo" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/medium.svg" alt="@davidojo" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/davidojo-j3v" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="davidojo-j3v" height="30" width="40" /></a>
</p>

Thanks for stopping by!
