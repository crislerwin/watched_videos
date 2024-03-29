---
tags:
  - type/youtube
aliases: 
title: Wait... PostgreSQL can do WHAT?
channel_name: The Art Of The Terminal
subscribers: 1310
length: 20:33
publish_date: 2024-03-13
chapters:
  - 0:00 - is it even a database anymore?
  - 1:15 - the quickest history of PostgreSQL
  - 2:34 - object-relational database
  - 4:38 - table inheritance
  - "6:03 - pg_trunk: a package manager for PostgreSQL extensions"
  - 7:31 - stored procedure that uses python's pandas
  - 7:55 - your database is not a DUMB store
  - 8:38 - PostgreSQL's FEATURE OF FEATURES
  - "9:04 - pg_cron & hstore: replacing redis cache"
  - "10:53 - NOTIFY/LISTEN: replacing redis pub/sub"
  - "11:51 - pgmq: replacing message queue like SQS"
  - "13:10 - JSONB: replacing MongoDB"
  - 13:29 - NoSQL vendors mimic SQL
  - "14:26 - Apache AGE & TimescaleDB: replacing graph and time series databases"
  - "15:09 - FTS: replacing ElasticSearch"
  - "16:20 - pgml: LLM and chatbots running in PostgreSQL"
  - "16:39 - Postgrest: no-code REST API for your DB tables"
  - "18:06 - pgtap: unit-testing for PostgreSQL"
  - "18:42 - pg_graphql: no-code GraphQL API for your DB tables "
  - "19:06 - Omnigres: PostgreSQL as a platform"
  - 19:25 - «boring technology» and «radical simplicity» with PostgreSQL
  - "20:03 - trying to play pg_doom (Doom in PostgreSQL) "
hashtags: 
thumbnail: "![[1710640225436.jpg]]"
description: ""
note_created: 2024-03-16, 22:50
youtube_url: https://youtu.be/VEWXmdjzIpQ
template-type: YouTube
template-version: "1.0"
created: 2024-03-16T22:50
updated: 2024-03-16T22:53
---

![[1710640225436.jpg]]

<iframe title="Wait... PostgreSQL can do WHAT?" src="https://www.youtube.com/embed/VEWXmdjzIpQ?feature=oembed" height="113" width="200" style="aspect-ratio: 1.76991 / 1; width: 100%; height: 100%;" allowfullscreen="" allow="fullscreen"></iframe>

SUMMARY:
The content discusses the advantages of using PostgreSQL (referred to as posg or pogress) for simplifying backend infrastructure by integrating functionalities like full-text search, machine learning models, and REST or GraphQL APIs directly within the database. It highlights the potential overkill of using technologies like Elasticsearch for projects that could benefit from the simplicity and feature-rich capabilities of PostgreSQL, including its enterprise-grade reliability and the future-proof benefits of enhancing SQL skills.

IDEAS:
- Simplifying infrastructure by using PostgreSQL for multiple functionalities can reduce maintenance complexity.
- Large language models (LLMs) can be integrated into databases, enabling advanced query capabilities.
- Replacing a combination of message queues and NoSQL databases with SQL can enhance real-time data searchability.
- Running machine learning models within the database can streamline backend processes.
- PostgreSQL can serve as a web server, turning the database into a REST API.
- The process of adding new entities in web frameworks can be simplified to just creating a database table in PostgreSQL.
- PostgreSQL supports role-based access controls with row-level granularity for authentication and authorization.
- Stored procedures in PostgreSQL allow leveraging its object-relational nature and various extensions.
- PostgreSQL's extensions support a wide range of data types and functionalities, including messaging, key-value stores, and time series data stores.
- Unit testing stored procedures is possible, maintaining best practices in software development.
- The PG GraphQL extension facilitates running GraphQL queries directly on PostgreSQL tables.
- PostgreSQL's versatility extends to managing containers, storing files in S3, and even providing payment support.
- Embracing "boring technology" like SQL and PostgreSQL might offer long-term benefits over chasing new, shiny technologies.
- Improving SQL skills is considered a future-proof investment in the rapidly evolving tech landscape.
- The idea that PostgreSQL is not just a database but a comprehensive platform for backend development.

QUOTES:
- "Imagine you can query an open source LLM model right within your database."
- "Running an Elasticsearch cluster for full-text search is an overkill for many projects."
- "With PostgreSQL, you can now search through your data in near real-time."
- "PostgreSQL is the web server that turns your database into a REST API."
- "Just need to create a database table, and PostgreSQL will take care of the rest."
- "You can unit test stored procedures just like you would do with your web framework."
- "PG GraphQL extension creates a transparent mapping between your data in tables and GraphQL entities."
- "PostgreSQL is in fact a platform project."
- "Adapting boring technology and embracing radical simplicity might yield long-term benefits."
- "Improving your SQL skills seems to be a very future-proof investment."

HABITS:
- Simplifying backend infrastructure by integrating multiple functionalities into one system.
- Regularly evaluating the necessity of using complex technologies versus simpler, integrated solutions.
- Emphasizing the importance of enhancing SQL skills for future-proofing one's career.
- Adopting a minimalist approach to technology selection to reduce maintenance complexity.
- Leveraging stored procedures to encapsulate complex operations within the database.
- Utilizing role-based access controls for securing data access at a granular level.
- Continuously exploring PostgreSQL's extensions to leverage its full capabilities.
- Practicing unit testing on all levels of the application, including database stored procedures.
- Choosing REST or GraphQL based on project needs while keeping the backend simple.
- Embracing the concept of PostgreSQL as more than just a database but as a comprehensive backend platform.

FACTS:
- PostgreSQL can integrate large language models for advanced querying capabilities.
- It is possible to run machine learning models directly within PostgreSQL.
- PostgreSQL can function as a web server, providing REST API capabilities directly from the database.
- Role-based access controls in PostgreSQL support row-level granularity.
- Stored procedures in PostgreSQL can leverage its object-relational nature and various extensions.
- Unit testing is applicable to stored procedures in PostgreSQL.
- The PG GraphQL extension allows for direct mapping between PostgreSQL tables and GraphQL entities.
- PostgreSQL's capabilities extend to managing containers and storing files in S3.
- Emphasizing SQL skills is considered a future-proof career strategy.
- PostgreSQL challenges the traditional view of databases by offering a platform for comprehensive backend development.

REFERENCES:
- Elasticsearch
- Large Language Models (LLMs)
- SQL
- REST API
- GraphQL
- PG GraphQL extension
- Object-relational nature of PostgreSQL
- Stored procedures
- Role-based access controls
- Unit testing methodologies

RECOMMENDATIONS:
- Consider using PostgreSQL for projects to simplify backend infrastructure while maintaining advanced functionalities.
- Evaluate the necessity of complex technologies like Elasticsearch against integrated solutions like PostgreSQL for full-text search.
- Enhance SQL skills as a future-proof investment in technology careers.
- Explore PostgreSQL's extensions to fully leverage its capabilities beyond traditional database functions.
- Adopt a minimalist approach to technology selection to focus on simplicity and long-term benefits.
- Utilize role-based access controls in PostgreSQL for secure and granular data access management.
- Practice unit testing on all levels of application development, including database operations.
- Explore using PostgreSQL as a comprehensive platform for backend development, beyond just database functionalities.
