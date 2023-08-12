[Home](https://pgmorales76.github.io/reading_notes_301/)

# Class 11 Reading Notes

## Why This Topic Matters

### Understanding the type of data you're working with enables the developer to determine the proper type of database to use

## Reading

## *Fill in the chart below with five differences between SQL and NoSQL databases:*

| SQL          | NoSQL        |
| :---:        | :---:        |
| Primarily called as Relational Databases (RDBMS) | Primarily called as non-relational or distributed database |
| Table-based databases | Document-based, key-value pairs, graph databases, or wide-column stores |
| Predefined schema | Dynamic schema for unstructured data |
| Databases are vertically scalable | Horizontally scalable |
| Uses SQL (Structured Query Language) for defining and manipulating the data | Queries are focused on collection of documents. Sometimes, it is also called as UnQL (Unstructured Query Language). The syntax of using UnQL varies from database to database. |

## *What kind of data is a good fit for an SQL database?*

### Data that's highly structured and associations among the program entities are clearly defined

## *Give a real world example.*

### A point of sale system where you need to store customer orders and product records [SQL or NoSQL? | Everything You Need to Know](https://www.taazaa.com/nosql-or-sql-how-to-choose-the-best-fit-for-a-project/)

## *What kind of data is a good fit a NoSQL database?*

### Data that's highly unstructured and relationships among the data entities aren't clearly defined

## *Give a real world example.*

### A data-mining application [SQL or NoSQL? | Everything You Need to Know](https://www.taazaa.com/nosql-or-sql-how-to-choose-the-best-fit-for-a-project/)

## *Which type of database is best for hierarchical data storage?*

> NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set (i.e for big data). Hbase is an example for this purpose. [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

## *Which type of database is best for scalability?*

> In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic. [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

## Videos

## *What does SQL stand for?*

### Structured Query Language

## *What is a relational database?*

### Database that works with certain assumptions, or in a certain way, connecting data, on different tables, together

## *What type of structure does a relational database work with?*

### Tables

## *What is a ‘schema’?*

### Strict requirements for the data you store in table

## *What is a NoSQL database?*

### A type of database which stores data differently than the strict, tabular, relational-type, in SQL

## *How does it work?*

### At the top-level, a NoSQL database had "Collections", which within the "Collections" are "Documents". "Documents" look similar to JSON and aren't bound by certain schema

## *What is inside of a MongoDB database?*

### Collections, which include documents. Documents look similar to object notation

## *Which is more flexible - SQL or MongoDB? and why.*

### MongoDB because there's no schema implied on the developer. There's tremendous flexibility with the data. However, when using NoSQL, you could have duplicate data

### That being said, it'll come down to what it is your building, or trying to accomplish

## *What is the disadvantage of a NoSQL database?*

### Being unsure if the data adheres to the format you're using. The price you pay for flexibility is unpredictability

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

[mongoose api](https://mongoosejs.com/docs/api.html#Model)

[React Router](https://reactrouter.com/web/api/BrowserRouter)

## Things I Want to Know More About

### Because SQL has been around for over sixty years, plus it's lack flexibility, as compared to NoSQL, is it used to the same extent as NoSQL?
