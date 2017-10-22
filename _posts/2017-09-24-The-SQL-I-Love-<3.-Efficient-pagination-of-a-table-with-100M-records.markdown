---
layout: post
title: The SQL I Love <3. Efficient pagination of a table with 100M records
source: http://allyouneedisbackend.com/blog/2017/09/24/the-sql-i-love-part-1-scanning-large-table/
category: HackerNews
description: SiteLog - Compilation of my favorite SQL queries after a decade of dealing with relational databases. Today we talk about scanning a table with 100 million records.
numwords: 1432
hnscore: 
---

I am a huge fan of databases. I even wanted to make my own DBMS when I was in university. Now I work both with RDBMS and NoSQL solutions, and I am very enthusiastic with that. You know, there’s no Golden Hammer, each problem has own solution. Alternatively, a subset of solutions. In the series of blog posts The SQL I Love  I walk you thru some problems solved with SQL which I found particularly interesting. The solutions are tested using a table with more than 100 million records. All the examples use MySQL, but ideas apply to other relational data stores like PostgreSQL, Oracle and SQL Server. This Chapter is focused on efficient scanning a large table using pagination with offset on the primary key. This is also known as keyset pagination.    In the chapter, we use the following database structure for example. The canonical example about users should fit any domain. CREATE TABLE `users` (  `user_id` int(11) unsigned NOT NULL AUTO_INCREMENT,  `external_id` varchar(32) NOT NULL,  `name...

![](http://d1vt1c82ljabfd.cloudfront.net/images/sql-i-love.jpg)
<!--description-->