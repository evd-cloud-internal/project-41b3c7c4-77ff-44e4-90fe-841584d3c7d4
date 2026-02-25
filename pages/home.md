---
name: Home
assetId: c3fec330-d609-4179-8c0e-653a765c3021
type: page
---

# Welcome

{% line_chart
    data="demo_daily_orders"
    x="date"
    y="sum(total_sales)"
    series="category"
    date_grain="month"
    y_fmt="usd0k"
    title="Monthly Sales by Category"
/%}

{% area_chart
    data="demo_daily_orders"
    x="date"
    y="transactions"
/%}