# Node DB3 Guided Project

Guided project for **Node DB3** Module.

## Prerequisites

- [SQLite Studio](https://sqlitestudio.pl/index.rvt?act=download) installed.
- [This Query Tool Loaded in the browser](https://www.w3schools.com/Sql/tryit.asp?filename=trysql_select_top).
- a rest client like [Insomnia](https://insomnia.rest/download/) or [Postman](https://www.getpostman.com/downloads/) installed.

## Project Setup

- [ ] clone this repository.
- [ ] cd into the project folder.
- [ ] type `npm i` to download dependencies.
- [ ] type `npm run server` to start the API.

Please follow along as the instructor creates database access methods for a multi table schema.

<!--
        SQL JOINS

    select count(o.orderid) as orders, (e.firstname || ' ' || e.lastname)
        as employee from orders as o
    join employees as e
    on o.employeeid = e.employeeid;

            40	Margaret Peacock
            31	Janet Leverling
            29	Nancy Davolio
            27	Laura Callahan
            20	Andrew Fuller
            18	Michael Suyama
            14	Robert King
            11	Steven Buchanan
            6	Anne Dodsworth

 -->
