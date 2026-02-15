# dbx-retail-lakehouse

A hands-on Databricks project focused on retail analytics.

This lab explores:

- SQL-based data exploration
- Notebook-based analytics workflow

The goal is to build practical hands-on experience with Databricks as a user, covering analytics and visualization with SQL.

We will use `backhouse` dataset, which is available in the sample dataset on Databricks.

## Table of Contents
- [dbx-retail-lakehouse](#dbx-retail-lakehouse)
  - [Table of Contents](#table-of-contents)
  - [Create Notebook](#create-notebook)
  - [Visualization](#visualization)
  - [GitHub integration](#github-integration)

---
## Create Notebook

Go to `Workspace`. Select `Notebook` from `Create` pull-down menu.

![Create Notebook](./images/notebook-1.png)

We will get something like this.
![Notebook](./images/notebook-2.png)

There are two ways to run SQL on Notebook. 
Use magic command `%sql` at the beginning of a cell. 

![Magic command](./images/python-1.png)

Or change the default language to SQL. 

![SQL](./images/sql-1.png)

**Tips** To run an SQL command, `Shift` + `Enter` in the cell. We do not need click on `Run` button every time. 

**Tips** You do not need to keep pressing shift key to write SQL query. Just write everything (like `SELECT` or `FROM`) in lower case, and type `Shift` + `Cmd` + `F` to format the script afterward. 

---
## Visualization

After you create a table by SQL query, click on `+` in the table header, 

![Vialization](./images/visualize-1.png)

and select `Visualization`. 

![Visualization](./images/visualize-2.png)

Let us plot the total sum of daily sales over all products over all franchise. 

![Plot-2](./images/plot-2.png)

There is no real weekly pattern to see. 

---
## GitHub integration



---
