# A Quick Start Guide to Learning SQL

<h3>Resources:</h3>
<ul>
    <li>https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all</li>
</ul>

<h3>What is SQL?</h3>
<ol>
    <li>Structured Query Language (SQL) is a domain specific language used in programming and designed for managed data held in relational database management</li>
    <li>It is particularly useful in handling STRUCTURED data, i.e. data incorporating rleations among entities and variables</li>
</ol>

<h3>Key Terms (<i>Simplified</i>):</h3>
<ul>
    <li><b>Database:</b> A container to store organized data</li>
    <li><b>Table:</b> A structured list of data of a specific type</li>
    <li><b>Column:</b> A single field in a table. All tables are made up of one or more columns</li>
    <li><b>Row:</b> A record in a table</li>
</ul>

<hr>

<h3>Retrieving Data</h3>
<p> To use the SELECT keyword to retrieve table data you must, at a minimum, specify two pieces of information</p>
<ol>
    <li> What do you want to select? (<i>e.g. CustomerName Column</i>)</li>
    <li> Where do you want to select from? (<i>e.g. Customers Table</i>)</li>
</ol>

```
SELECT CustomerName
FROM Customers;
```

<p> Note: </o>
<ul>
    <li>All extra white space within a SQL statement is ignored when the statement is processed. SQL statements can be specificed on one long line or broken up over many lines</li>
    <li>Most SQL developers find that breaking up statements over multiple lines makes it easier to read and debug.</li>
</ul>

<p>Examples:</p>

```
SELECT CustomerName
FROM Customers;

SELECT CustomerName FROM Customers;

SELECT
CustomerName
FROM
Customers;
```

<h3>Retrieving Multiple Columns</h3>
<p>The difference with retrieving data from multiple columns is: <p>
<ul>
    <li>Multiple column names must be specified after the SELECT keyword</li>
    <li>each column must be delimited by a comma</li>
</ul>

<hr>
