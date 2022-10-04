# Churn analysis with SQL (ft. DuckDB)

### Why?
I have no place for doing fancy SQL things, most of the SQL queries I saved that on the `.sql` file, but no visualization would be shown. I thought a lot about how to bring SQL onto the `.ipynb` notebook like how people do that with rsqlite, but somehow I found sqlite and sqlalchemy on that thing is pretty annoying.

That's why I choose DuckDB, for the in-cell queries, and it also has the ability to the result of the query to the pandas dataframe, much better for notebook user to do some exploration on the queries, instead of pipeline them onto another BI tool.
