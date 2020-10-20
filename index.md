Extending an in-house Query Engine with support for Apache Cassandra
====================================================================

Samuel Kacer \| 2093358 \| <img src="images/CompSci_colour.pdf" alt="University of Glasgow School of Computing Science">

With ever increasing amounts of data to store and process, companies turn to Big Data solutions where the work is distributed over many nodes working together in a cluster. However with this come some big challenges.

Some of these challenges are moving to Big Data usually makes querying and other basic operations more technical, increasing the reliance of financial analysts on engineers. As well as each Big Data service having its own language, making migrating existing code to the newest tech require major refactoring costs.

In order to address these challenges, the company developed an in house Query Engine with its own abstract querying language, aiming to create an easy to use platform for their financial analysts and provide a layer of abstraction that allows for easier migration between underlying storage and processing technologies. The service has been very successful and productive, however the technologies the Query Engine supports is limited right now, leading to some problems like technologists needing to choose less appropriate storage solutions or perform expensive reformatting in order to be able to use the Query Engine.

This project identifies Apache Cassandra as an excellent technology to fill the gap that currently supported technologies don’t address well and proposes a plan for integrating it with the Query Engine in order to solve some of its current problems.


-   [Background](background), overview of partnering company and project problem description

-   [Objectives](objectives), set of actionable goals and concrete deliverables for solving the issues outlined in the background section

-   [Work plan](work_plan), the key strategies for completing the project and an outline of the work activities to implement the deliverables

-   [Reflection](reflection), a look at some key topics learned while at University and on industrial placement that will help in this project


