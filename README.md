Problem - In monolithic applications, most of time we have 1 database and this database should respond both query and update operations. That means a database is both working for complex join queries, and also perform CRUD operations. But if the application goes more complex this query and crud operations will be also is going to be un-manageable situation. 
Solution - Solution to above problem is CQRS design pattern. This pattern offers to use “separation of concerns” principles and separate reading database and the writing database with 2 different databases. In this approach, we can even use different database for reading and writing database types like using no-sql for reading and using relational database for crud operations.
