# ➤ Airbnb NYC Market Dashboard (Tableau) (2025)

Interactive Tableau dashboard analyzing New York City’s Airbnb market across listings, pricing, availability, and guest engagement.
<div class='tableauPlaceholder' id='viz1769104575950' style='position: relative'><noscript><a href='#'><img alt='Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ai&#47;AirbnbNewyork_17631581845800&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AirbnbNewyork_17631581845800&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ai&#47;AirbnbNewyork_17631581845800&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1769104575950');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='2177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

---

## Links
- **Interactive Tableau Dashboard:** https://public.tableau.com/views/AirbnbNewyork_17631581845800/Dashboard?:embed=y  

---

## Project Overview
This project explores the NYC Airbnb market to identify trends in:
- listing volume by borough/neighborhood
- pricing differences across locations
- room type supply patterns
- availability distribution
- guest engagement through review activity

The final output is a market intelligence dashboard designed for **quick decision-making** and **exploratory analysis**, suitable for business stakeholders.

---

## Business Questions
This dashboard was designed to answer key stakeholder questions such as:

1. **How large is the NYC Airbnb market overall?**
2. **Which boroughs dominate supply and pricing?**
3. **What room types are most common—and which generate the most engagement?**
4. **Which neighborhoods show high availability vs high demand?**
5. **What does Airbnb pricing distribution look like in NYC?**

---

## KPIs Tracked
The dashboard is anchored around four core KPIs:

- **Total Listings** — total number of Airbnb listings
- **Average Price** — average nightly price across listings
- **Total Reviews** — overall guest review volume (proxy for demand/engagement)
- **Average Availability** — average days available (proxy for market saturation)

These KPIs provide a high-level snapshot before diving into deeper visuals.

---

## Data Preparation (Cleaning + Feature Engineering)
Before building the dashboard, the dataset was cleaned and standardized to ensure accurate KPI reporting and consistent grouping across visuals.

**Key steps included:**
- removed nulls and duplicates  
- standardized inconsistent neighborhood/group labels  
- fixed measure/dimension data types  
- created calculated fields for dashboard KPIs  
- validated aggregation levels for pricing and availability metrics  

---

## Dashboard Design Strategy
The dashboard was structured to support both:
- **executive summary** viewing (top KPIs)
- **deep exploration** via segmented visuals

### Visuals Included
1. **Listings by Neighborhood Group**  
   Identifies boroughs dominating supply.

2. **Geographic Map of Listings**  
   Visualizes listing density and hotspot clusters.

3. **Average Availability by Neighborhood**  
   Highlights neighborhoods with the most open supply.

4. **Average Price by Neighborhood**  
   Reveals pricing gaps across NYC.

5. **Listings by Room Type**  
   Shows which room types dominate the market.

6. **Reviews by Room Type**  
   Tracks guest engagement patterns by listing type.

7. **Price Distribution Histogram**  
   Shows overall pricing spread and the presence of outliers/luxury listings.

---

## ✨ Key Insights
- **Manhattan leads** in both listing volume and average price.
- **Brooklyn follows closely** in listing volume but at generally lower prices.
- **Bronx and Staten Island** show noticeably higher availability, suggesting lower occupancy/market demand.
- **Private rooms and entire homes** dominate the supply side, and private rooms lead in review volume.
- Pricing shows a **right-skewed distribution**, with most listings under a common threshold and a long tail of luxury listings.

---

## Recommendations / Business Takeaways
If this dashboard were used by a real stakeholder (host, investor, marketplace operator), the data suggests:

- **Pricing strategy should vary by borough** — Manhattan supports premium pricing, while outer boroughs benefit from competitive pricing.
- **Neighborhood availability is a strong signal** — high availability may point to areas where demand is weaker or supply is under-optimized.
- **Room type matters for engagement** — private rooms consistently generate strong guest activity and reviews.
- **Luxury listings drive outliers** — pricing analysis should account for skew and outliers when forecasting.

---

## Tools Used
- **Tableau Public / Tableau Desktop**
- Excel (basic inspection / dataset review)

---

## Skills Demonstrated
- Dashboard Design + Layout Structuring (Tableau)
- KPI Development
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preparation
- Market Segmentation
- Visual Storytelling for Stakeholders

---

