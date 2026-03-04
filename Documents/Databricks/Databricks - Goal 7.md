Model the Data & Build a Report / Dashboard 1 hour

Now that your data is ingested, transformed, and enriched with Azure AI, it’s time to pull it all together and tell the story.

Your goal in this section is to model the data and build a report or dashboard that showcases the insights you’ve uncovered.

What to Do
    • Combine your tables into a clean data model
    • Create relationships between your Lakehouse tables/views
    • Add calculated columns or measures where needed
    • Build a Power BI report or real‑time dashboard to highlight your findings

Ideas & Suggestions

To help the hackathon participants get creative, here are some simple and fun directions they can go:

Modeling Ideas
    • Create relationships between “fact” and “dimension” tables
    • Build DAX measures (totals, averages, YoY growth, etc.)
    • Add a semantic model to simplify the schema for reporting
    • Use Direct Lake so the dashboard reflects live Lakehouse data

Dashboard / Report Ideas
    • Build a summary dashboard showing high‑level KPIs
    • Create an AI‑powered “Insights” page using Smart Narratives
    • Use slicers to let users explore patterns by date, category, or region
    • Add visuals that highlight anomalies found by Azure AI
    • Build a simple “Ask a Question” Q&A visual so users can query the model in natural language
    • Create a “Before vs After AI Enrichment” comparison page
    • Build a drill‑through page to dive deeper into any record or segment

Creative Optional Add‑Ons
    • Add bookmarks or buttons to create a guided storytelling experience
    • Use themes to brand your dashboard
    • Add a KPI card that uses conditional formatting (red/yellow/green)
    • Build a mini‑“Copilot‑style” insights page showing AI-generated summaries from your enriched data
    • Add a tooltip page with deeper insights when hovering over visuals

    • -Notes : S

Create the data model (relationships, facts, dimensions)


    

What to do	Learn link
Understand star schema (fact & dimension)	https://learn.microsoft.com/power-bi/guidance/star-schema
Create relationships in model view	https://learn.microsoft.com/power-bi/transform-model/desktop-create-and-manage-relationships
Create a semantic model in Fabric	https://learn.microsoft.com/fabric/data-warehouse/semantic-models
Use Direct Lake from Lakehouse	https://learn.microsoft.com/fabric/get-started/direct-lake-overview


Add calculated columns & DAX measures
What to do	Learn link
DAX basics (totals, averages, YoY, etc.)	https://learn.microsoft.com/power-bi/transform-model/desktop-quickstart-learn-dax-basics
Create measures	https://learn.microsoft.com/power-bi/transform-model/desktop-measures
Calculated columns vs measures	https://learn.microsoft.com/power-bi/transform-model/desktop-calculated-columns


Build the Power BI report / dashboard
Samples 


4
Idea	Learn link
Create your first report	https://learn.microsoft.com/power-bi/create-reports/desktop-create-reports
Use slicers for exploration	https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-slicers
Smart Narratives (AI insights page)	https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-smart-narrative
Q&A visual (ask questions in plain English)	https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-q-and-a
Drill-through pages	https://learn.microsoft.com/power-bi/create-reports/desktop-drillthrough
Tooltip report pages	https://learn.microsoft.com/power-bi/create-reports/desktop-tooltips
Bookmarks & buttons (storytelling)	https://learn.microsoft.com/power-bi/create-reports/desktop-bookmarks


What to show	How
Anomalies detected	Line chart with anomaly flag
Sentiment / entities	Bar/word cloud from enriched columns
AI summaries	Smart narrative or text visual
Before vs After AI enrichment	Comparison page using same visuals


Direct Lake (very important for hackathon story)
Your report reads live from the Lakehouse. No import. No refresh.
🔗 Direct Lake overview
https://learn.microsoft.com/fabric/get-started/direct-lake-overview


💡 Optional creative polish
Feature	Learn link
Themes / branding	https://learn.microsoft.com/power-bi/create-reports/desktop-report-themes
KPI cards with conditional formatting	https://learn.microsoft.com/power-bi/visuals/power-bi-visualization-card
Dashboard tiles	https://learn.microsoft.com/power-bi/create-reports/service-dashboard-create


 participants should end with
 Clean star schema model
 Measures for KPIs
Direct Lake semantic model
 3–5 page report showing AI insights
 Q&A or Smart Narrative page
Drill-through / tooltip for depth


