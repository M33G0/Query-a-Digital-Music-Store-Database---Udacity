This project explores the **Chinook Database**, a sample database representing a digital media store, including data for artists, albums, media tracks, invoices, and customers. The goal is to write complex SQL queries to assist the business team in understanding customer behavior, optimizing product selection, and planning marketing initiatives.

## Business Questions Answered
1. **Media Format Popularity:** Which media format generates the most revenue, and how many tracks exist for each format? 
   * *Insight:* `MPEG audio file` leads dramatically in both overall catalog count and total USD sales.
2. **Top Selling Albums:** What are the top 5 highest-selling albums of all time?
   * *Insight:* TV show and comprehensive sets like `Battlestar Galactica (Classic), Season 1`, `The Office, Season 3`, and `Lost, Season 2` top the charts.
3. **Rock Music Superstars:** Who are the top 10 Rock artists based on track counts in the store?
   * *Insight:* `Led Zeppelin` holds the top spot with 114 rock tracks, followed closely by `U2` and `Deep Purple`. This data serves as a great foundation if the company ever plans a rock music festival.
4. **Best Customers Globally:** Who are the highest-spending customers within each country?
   * *Insight:* Identifies individual VIP clients (such as Diego Gutiérrez in Argentina and Mark Taylor in Australia) to target with country-specific loyalty campaigns.

## Repository Contents
* `Queries.txt`: The raw, well-commented SQL queries combining multiple `JOIN` clauses, aggregations (`SUM`, `COUNT`), conditional logic, nested subqueries, and windowing patterns.
* `SQL presentation.pdf`: A data visualization presentation summarizing the queries using intuitive charts to pitch actionable insights to management.

## Tech Stack
* SQL / SQLite / PostgreSQL
* Data Visualization & Presentation tools
