# Prophet Challenge

## Step 1: Find Unusual Patterns in Hourly Google Search Traffic

**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?

**Answer: Yes**


## Step 2: Mine the Search Traffic Data for Seasonality

**Question:** Are there any time based trends that you can see in the data?

**Answer:**
* Hourly - It it low in the middle of the day and search increase as day passes by and peaks in the late evening
* Day - It is at peak at day 2 and gradually decreases at end of the week
* Week - It is at peak in the first quarter and kind of increases at the end of the year. In between these 2 peaks it's very inconsistent

## Step 3: Relate the Search Traffic to Stock Price Patterns

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?

**Answer:**
There is no clear search trends with the stock price. With stock price increase the search trends is consistent with past search trends and is didn't increase with the price.

## Step 4: Create a Time Series Model with Prophet

**Question:**  How's the near-term forecast for the popularity of MercadoLibre?

**Answer:**
It looks like it will be in 90 - 95 %

**Question:** What time of day exhibits the greatest popularity?

**Answer:** At 00:00:00

**Question:** Which day of week gets the most search traffic?
   
**Answer:** Tuesday

**Question:** What's the lowest point for search traffic in the calendar year?

**Answer:** October

