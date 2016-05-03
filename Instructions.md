### Instructions

1. Ensure you have the [Chinook Database](http://chinookdatabase.codeplex.com/) and [SQLite Manager Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/sqlite-manager/) installed.
2. Create a github repo for your answers. This repo will  only contain a README file in which you will write a short description of the exercise and where you can keep track of your answers.
3. If you have trouble opening the SQLite Manager once it has been installed, try opening firefox, selecting "customize" at the bottom of the hamberger menu at the top right of the page. You can then drag SQLite Manager onto the toolbar where it will be easily accessible.
4. Open SQLite Manager and select database < Connect Database and click on "Chinook_sqlite.sqlite".
5. Go ahead and click around a little bit to familarize yourself with the database
6. Optional, but helpful: draw an ERD of the Chinook database. Make sure to label primary keys, foreign keys, and indicate the type of relationship (one to one, one to many, many to many, etc) for each relationship. Use draw.io.
7. When you're ready to start the exercise, click the tab labeled "Execute SQL", type in your query, and click "Run SQL."
8. If your query is correct (i.e. it returns the data requested below) copy and paste the query to your github README. If your query doesn't return the expected results, try try again.

For each of the following exercises, provide the appropriate query. Yes, even the ones that are expressed in the form of questions. Everything from class and the [Sqlite Documentation](http://www.sqlite.org/) is fair game. 

1. Provide a query showing Customers (just their full names, customer ID and country) who are not in the US.
2. Provide a query only showing the Customers from Brazil.
3. Provide a query showing the Invoices of customers who are from Brazil. The resultant table should show the customer's full name, Invoice ID, Date of the invoice and billing country.
4. Provide a query showing only the Employees who are Sales Agents.
5. Provide a query showing a unique list of billing countries from the Invoice table.
6. Provide a query that shows the invoices associated with each sales agent. The resultant table should include the Sales Agent's full name. 
7. Provide a query that shows the Invoice Total, Customer name, Country and Sale Agent name for all invoices and customers. 
8. How many Invoices were there in 2009 and 2011? What are the respective total sales for each of those years?(include both the answers and the queries used to find the answers)
9. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for Invoice ID 37.
10. Looking at the InvoiceLine table, provide a query that COUNTs the number of line items for each Invoice. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
11. Provide a query that includes the track name with each invoice line item.
12. Provide a query that includes the purchased track name AND artist name with each invoice line item.
13. Provide a query that shows the # of invoices per country. HINT: [GROUP BY](http://www.sqlite.org/lang_select.html#resultset)
14. Provide a query that shows the total number of tracks in each playlist. The Playlist name should be include on the resulant table.
15. Provide a query that shows all the Tracks, but displays no IDs. The resultant table should include the Album name, Media type and Genre.
16. Provide a query that shows all Invoices but includes the # of invoice line items.
17. Provide a query that shows total sales made by each sales agent.
18. Which sales agent made the most in sales in 2009? HINT: [MAX](https://www.sqlite.org/lang_aggfunc.html#maxggunc)
19. Which sales agent made the most in sales over all?
20. Provide a query that shows the # of customers assigned to each sales agent.
21. Provide a query that shows the total sales per country. Which country's customers spent the most?
22. Provide a query that shows the most purchased track of 2013.
23. Provide a query that shows the top 5 most purchased tracks over all.
24. Provide a query that shows the top 3 best selling artists.
25. Provide a query that shows the most purchased Media Type.
