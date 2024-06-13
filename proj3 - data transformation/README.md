In this project, I work with one month of data from sensors in buildings at UC Berkeley. This is a very typical real-world dataset—i.e. it's kind of a mess. The full dataset contains a giant `data` table of many billions of sensor readings over the course of a decade; I look at a single month of that data. It also contains a variety of other tables that contextualize the readings.

The **schema for the database** is shown below.
* Each line represents a relationship between the two fields.
* The side of the line diverging to three lines / arrows represents the **"many"** side of the relationship, while the side of the line converging to one arrow represents the **"one"** side of the relationship.
* This file is available as `data/schema.png`.

Occasionally people believe that when the data has a well-structured schema, then it's simple to proceed! *I'll put this assumption to the test.*
