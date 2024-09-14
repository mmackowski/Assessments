**Matt Mackowski / CIDM 6350**

# Assignment 2 - Assessing Data Management

## Data Management – Overview

For most of my career in web development, I’ve worked for smaller organizations; and one of the primary benefits of this fact is that I have been fortunate enough to gain experience in most aspects of the development cycle, including (especially) data management. Starting back in the late 90s I was designing databases and writing SQL queries to support my own web applications. Granted, back then, the apps (and databases) were small, but it still allowed me to gain valuable skills in collecting, storing, and manipulating data. These skills have grown as my projects have increased in size and complexity. And while I would not consider myself to be on the level of a Database Administrator, I would consider data management to be one of the stronger competences.

## What Do I Know

**_SQL._** Rarely has a working day passed in the last 15 years where I haven’t written or edited SQL; and to be honest, it’s one of my favorite parts of the job (writing a good query is like solving a puzzle). I have written all types of queries, both simple and complex. The organization where I’ve worked for the past decade is a Microsoft shop, and while we have used Entity Framework (and NHibernate) in the past, for several years now we’ve relied mostly on Dapper for our object-relational mapping; and Dapper involves writing your own SQL. Subsequently I’ve written dozens of stored procedures for production apps. We use a third-party mobile application for our conferences and for that alone I wrote 18 stored procedures to allow our app to sync with our proprietary database.

**_Database Design, Modeling, and Normalization._** While in my career I have designed and built smaller databases for applications, at my last two jobs, I’ve worked with a single, large database, which has involved adding new tables (or groups of tables) or schemas to the existing dataset, as well as modifying existing tables. These processes incorporate many aspects of DB design, modeling, and, or course normalization (in practice, I find these three elements almost always go together). Design in the sense that new tables must relate to each other and to existing tables, and they must be carefully constructed to fit the information that they will store. Working with subsets of tables always involves modeling (especially when you are using something like Entity Framework). And normalizing the data standard operating procedure; any database, especially larger databases, will quickly become a mess without normalization.

**_Tooling._** I have a strong working familiarity with SQL Server Management Studio, as well as a decent understanding of MySQL Workbench. I’ve used other data management tools such as RedGate’s SQL Compare and SQL Data Compare, as well as LucidChart.

## Where Am I Weak

**_Indexing._** As mentioned, my data management skills are those of a developer not an admin, and so it is fair to say that I’ve neglected more advanced database maintenance processes. An (important) example is indexing. I rarely set up indexes – and if I’m being honest, I rarely give them thought – even though I’m sure my queries would benefit from well-considered indexing.

You could also probably extend this to security; while I absolutely do limit my database objects to properly secured accounts, I’m sure my security practices could be more robust (please don’t ask me how long it’s been since I’ve changed passwords on my app accounts).

**_Query Analysis._** It is also true that I do not take full advantage of tools like SQL Server Profiler and Query Analyzer. I would only use these tools if I had a poorly performing application, and even though situations I would first look to optimize the application code before looking at data access. It is difficult to carve out time to use these tools when an application is working fine, even if being more proficient with them would probably benefit my apps quite a bit.

## What I Wish I Knew and Didn’t Realize I was Missing

There is one common thread among everything I’ve mentioned so far – it all involves relational databases. I think that as time goes on, it will become increasingly important that I expand my skills to include NoSQL, and other data storage options like Data Lakes. Even now, my organization is considering collecting and storing other types of data beyond just traditional text and numbers (images, documents, raw information streams). After 25 years of thinking in rows and columns it is time to branch out. I did use MongodDB for a personal project, but that is as adventurous as I’ve gotten to date.
Also, I think it’ s clear that cloud data hosting services like Azure are the way of the future. It will probably soon be more important to know how to configure data and databases by correctly navigating a GUI, than will be to be able to handle data directly through something like SSMS. I’ve done some online training in Azure, but it depresses me, it’s not real development.

## Integration

Data management is core to what I do professionally and is thoroughly integrated with the other categories in the curriculum. I mentioned in the previous assessment that my organization is moving to Salesforce, and it seems clear that software development (my primary skill) is going to be emphasized less, and data will be emphasized more (both management and analysis).
