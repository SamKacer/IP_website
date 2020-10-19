Reflection
==========

A reflection on what I have learned during my industrial placement and university studies that would help me in this project.

Test Driven Development (TDD)
-----------------------------

-   As mentioned in Objectives and Work Plan, very important strategy for this project

-   First learned about it at University in multiple courses

-   At University gained theoretical appreciation

-   but didn’t have much chance to practically apply it, due to projects being fairly small

-   at work saw the problems that TDD was supposed to help with:

    -   so much time devoted to fixing bugs in production

    -   poor test coverage for some code, stemming from tests mostly written as an after thought

    -   need to have fast feedback of correctness during development

-   started to apply TDD for solving these problems and experienced the practical benefits first hand

Big Data
--------

-   Big Data is what you use when traditional methods for storing and processing (Excel, relational databases) don’t scale to you your needs

    -   Relational databases typically scale vertically, by upgrading the server machine to handle more

    -   Big Data usually refers to distributed solutions where storing/processing distributed over many machines in a cluster

    -   Distributed solutions scale horizontally (linearly) by adding more machines to the cluster

-   Some examples of Big Data technologies:

    -   Mongo DB, Apache Cassandra, HDFS: distributed, NoSQL databases

    -   Apache Spark, MapReduce: distributed processing

    -   Apache Kafka: distributed message queue

-   At company was introduced to the importance of using Big Data solutions for solving business problems

-   Worked with and researched various Big Data technologies:

    -   learned hands on about using Apache Spark for processing huge datasets and the theory behind its effectiveness

    -   Worked with Apache Kafka for building asynchronous, distributed message streams between different applications

    -   As part of my work I researched different NoSQL databases and their suitability for our team’s use cases

-   This experience helped me identify Cassandra as a good complement to our use of HDFS in the Query Engine

-   Gave me knowledge to implement the integration into the company’s Big Data system

Project Management
------------------

-   PSD and other University courses covered various techniques around successfully completing a project:

    -   Change management: using git for versioning, GitLab merge requests for reviewing changes

    -   Sprints: structuring work in fixed time intervals with regularly scheduled activities

    -   Tracking work items: GitLab issues, prioritization, and effort estimation

    -   Retrospectives: reflecting on past sprint and brainstorming on ways to improve development process

    -   Many more …

-   Working on team project in 3<sup>rd</sup> year of University allowed me to test them in practice

-   Some problems with fully appreciating the practices during University team project:

    -   Not everyone in the team taking project equally seriously

    -   Team project only a quarter of overall credits; a lot of other things to work on

    -   As a result practices like daily standups didn’t make much sense

-   at industrial placement had much better chance to try and deeply appreciate the different practices

    -   everyone was very professional and took work seriously

    -   the work we did was \#1 focus, with fewer distractions

-   as a result can apply project planning skills to this project as well

    -   clearly defining the scope and goals of the project

    -   splitting work into smaller activities to estimate their effort and plan schedule

    -   use git effectively to manage code changes

[back to index](index)
