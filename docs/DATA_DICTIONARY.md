# Data Dictionary

## Sales Details

| Field | Description |
|---|---|
| Order ID | Unique identifier assigned to each sales transaction |
| Product ID | Product identifier used to connect transactions with the product table |
| Purchase Date | Date on which the purchase was recorded |
| Customer Name | Customer associated with the transaction |
| State | French location associated with the transaction |
| Salesperson Name | Salesperson responsible for the transaction |
| Quantity | Number of product units sold |

## Product Details

| Field | Description |
|---|---|
| Product ID | Unique product identifier |
| Product Name | Display name of the product |
| Cost | Cost per product unit |
| Original Sale Price | Original selling price per unit |
| Current Price | Current selling price used in sales calculations |

## Derived Business Metrics

| Metric | Definition |
|---|---|
| Total Sales | Quantity multiplied by current selling price |
| Cost | Quantity multiplied by product cost |
| Profit | Total Sales minus Cost |
| Profit % | Profit divided by Total Sales |
| Previous-Year Metrics | Equivalent measure evaluated for the preceding year |
| Cumulative Sales | Running total of sales over the selected period |
| Cumulative Difference | Difference between current and previous cumulative performance |
