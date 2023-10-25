# 3-Most-Profitable-Companies
With this code, I calculated the 3 most profitable companies in the world from a table of companies with their profits listed.
The table has columns consisting of company, sector, industry, continent, country, marketvalue, sales, profits, assets, rank, and forbeswebpage.
In order to find the 3 most profitable companies, I just needed to target two columns, profits and company. 
After selecting those columns from the table, I ordered the results by profits, in decending order. 
To just show the 3 most profitable companies, I set the code to a limit of 3 and then executed the statement.
While working on this statement, I ran into a problem.
At first, the middle of my statement just read "ORDER BY profits" and when I executed the statement, it was showing me the 3 companies with the lowest profits.
I realized that the default for "ORDER BY" is ascending order, so I just had to put "DESC" at the end of "ORDER BY profits" and the 3 highest profits were returned.
This is an example of a SQL project I worked on to show my capabilties of using SQL. When using SQL, I aspire to benefit companies in any way I can writing queries.
