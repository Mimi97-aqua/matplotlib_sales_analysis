### Sales Analysis Dashboard
Mini-sales analysis dashboard using Pandas, Matplotlib, and Streamlit

### Task Description
You are a Data Analyst working for a video game company. You have been given a dataset containing information about popular video games, including their platform, year, genre, publisher, regional sales, and global sales. Using the provided dataset, create four Matplotlib visualisations: a bar chart comparing the Global Sales of selected games or genres, with each bar using a different colour; a line chart showing the trend of game sales across years using a diamond marker and suitable line customisation; a scatter plot showing the relationship between NA Sales and Global Sales, using appropriate colour and transparency; and a combined bar and line chart comparing NA Sales and Global Sales for selected games, including suitable colours, labels, legend, title, and other chart characteristics. Before plotting, identify and appropriately handle the missing values in the dataset. Finally, write a 150–200 word data story narrative explaining the main trends, regional differences, relationships, key insights, and one recommendation for the video game company. Your visualisations should support the narrative and clearly communicate the story behind the data. Create a simple and compelling dashboard to showcase your findings.

### Project Setup
To successfully run this project, you are required to have Python3 and UV installed.
- Clone this repository then `cd matplotlib_sales_analysis/`
- Run `uv sync`

### Data Story and Recommendation
Nintendo dominates this dataset of 19 best-selling games: it published 16 of them, and Wii Sports alone sold 82.7 million copies worldwide. Sales peaked in 2006 and 2009, when Wii Sports, Wii Play and Wii Sports Resort were released, showing that a hit console and its games drive sales together.

North America is the largest market, with half of all regional sales, followed by Europe (27%), Japan (13%) and other regions (10%). Global sales track North American (r = 0.80) and European (r = 0.83) sales closely, while Japanese sales barely relate (r = 0.18), so Japan behaves as a separate market. Japanese players favour Role-Playing and Platform games such as Pokémon but buy few Shooter or Action games.

Sports is the top genre at 166.8 million copies, ahead of Platform (119.5 million), mainly because of the Wii's motion-controlled titles.

**Recommendation:** focus on accessible, family-friendly Sports and Platform games for North America and Europe, and develop Role-Playing titles specifically for Japan instead of expecting Western hits to sell there.