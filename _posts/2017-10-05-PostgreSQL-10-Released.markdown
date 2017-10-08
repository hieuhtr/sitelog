---
layout: post
title: PostgreSQL 10 Released
source: https://www.postgresql.org/about/news/1786/
category: 
description: SiteLog - PostgreSQL 10 Released
---

The PostgreSQL Global Development Group today announced the release of PostgreSQL 10, the latest version of the world's most advanced open source database.

A critical feature of modern workloads is the ability to distribute data across many nodes for faster access, management, and analysis, which is also known as a "divide and conquer" strategy. The PostgreSQL 10 release includes significant enhancements to effectively implement the divide and conquer strategy, including native logical replication, declarative table partitioning, and improved query parallelism.

"Our developer community focused on building features that would take advantage of modern infrastructure setups for distributing workloads," said Magnus Hagander, a core team member of the PostgreSQL Global Development Group. "Features such as logical replication and improved query parallelism represent years of work and demonstrate the continued dedication of the community to ensuring Postgres leadership as technology demands evolve."

This release also marks the change of the versioning scheme for PostgreSQL to a "x.y" format.  This means the next minor release of PostgreSQL will be 10.1 and the next major release will be 11.

Logical replication extends the current replication features of PostgreSQL with the ability to send modifications on a per-database and per-table level to different PostgreSQL databases.  Users can now fine-tune the data replicated to various database clusters and will have the ability to perform zero-downtime upgrades to future major PostgreSQL versions.

"We have been heavily using PostgreSQL since 9.3 and are very excited about version 10 since it brings basis for long-awaited partitioning and built-in logical replication. It will allow us to use PostgreSQL in even more services," said Vladimir Borodin, DBA Team Lead at Yandex.

Table partitioning has existed for years in PostgreSQL but required a user to maintain a nontrivial set of rules and triggers for the partitioning to work.  PostgreSQL 10 introduces a table partitioning syntax that lets users easily create and maintain range and list partitioned tables.  The addition of the partitioning syntax is the first step in a series of planned features to provide a robust partitioning framework within PostgreSQL.

PostgreSQL 10 provides better support for parallelized queries by allowing more parts of the query execution process to be parallelized.  Improvements include additional types of data scans that are parallelized as well as optimizations when the data is recombined, such as pre-sorting. These enhancements allow results to be returned more quickly.

PostgreSQL 10 introduces quorum commit for synchronous replication, which allows for flexibility in how a primary database receives acknowledgement that changes were successfully written to remote replicas.  An administrator can now specify that if any number of replicas has acknowledged that a change to the database has been made, then the data can be considered safely written.

"Quorum commit for synchronous replication in PostgreSQL 10 gives more options to extend our ability to promote database infrastructure with nearly zero downtime from the application perspective. This allows us to continuously deploy and update our database infrastructure without incurring long maintenance windows," said Curt Micol, Staff Infrastructure Engineer at Simple Finance.

The Salted Challenge Response Authentication Mechanism (SCRAM) defined in RFC5802 defines a protocol to improve upon the secure storage and transmission of passwords by providing a framework for strong password negotiation. PostgreSQL 10 introduces the SCRAM-SHA-256 authentication method, defined in RFC7677, to provide better security than the existing MD5-based password authentication method.

PostgreSQL is the world's most advanced open source database, with a global community of thousands of users, contributors, companies and organizations.  The PostgreSQL Project builds on over 30 years of engineering, starting at the University of California, Berkeley, and has continued with an unmatched pace of development. PostgreSQL's mature feature set not only matches top proprietary database systems, but exceeds them in advanced database features, extensibility, security and stability.  Learn more about PostgreSQL and participate in our community at PostgreSQL.org.

![]()

<!--description-->