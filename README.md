# data-base<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data base systems</title>
</head>

<body>
    <p class="logo">Data base systems</p>
    <!-- list of anchor -->
    <ul>
        <li><a href="#home">home</a> </li>
        <li><a href="#classification">classification</a></li>
        <li><a href="#Database management system">Database management system</a></li>
        <li><a href="#Database management system">Database programme interface</a></li>
        <li><a href="#Replication">Replication</a></li>
    </ul>
    <div id="home">
        <p>A database is an organized collection of data, generally stored and accessed electronically from a computer
            system.
            Where databases are more complex they are often developed using formal design and modeling techniques.<br>
            The database management system (DBMS) is the software that interacts with end users, applications, and the
            database itself to capture and analyze the data. The DBMS software additionally encompasses the core
            facilities provided to administer the database. <br>
            The sum total of the database, the DBMS and the associated applications can be referred to as a "database
            system". Often the term "database" is also used to loosely refer to any of the DBMS, the database system or
            an application associated with the database.<br>
            Computer scientists may classify database-management systems according to the database models that they
            support. Relational databases became dominant in the 1980s. These model data as rows and columns in a series
            of tables, and the vast majority use SQL for writing and querying data. In the 2000s, non-relational
            databases became popular, referred to as NoSQL because they use different query languages.<br>
        </p>
    </div>
    <!-- table for classification of database system-->
    <div id="classification">
        <table>
            <caption>classification of database system</caption>
            <tr>
                <th scope="col"> transformation </th>
            </tr>
            <tr>
                <th scope="row">Aggregation</th>
                <td> count / sum </td>
                <td> min / max </td>
            </tr>
            <tr>
                <th scope="row"> denormalization </th>
                <td>direct derivation</td>
                <td>expretion </td>
                <td>case</td>
            </tr>
        </table>
    </div>
    <div class="Database management system">
        <p>
            The DBMS acronym is sometimes extended to indicate the underlying database model, with RDBMS for the
            relational, OODBMS for the object (oriented) and ORDBMS for the object–relational model. Other extensions
            can indicate some other characteristic, such as DDBMS for a distributed database management systems.
            Connolly and Begg define database management system (DBMS) as a "software system that enables users to
            define, create, maintain and control access to the database".[24] Examples of DBMS's include MySQL,
            PostgreSQL, Microsoft SQL Server, Oracle Database, and Microsoft Access.<br>
            The DBMS acronym is sometimes extended to indicate the underlying database model, with RDBMS for the
            relational, OODBMS for the object (oriented) and ORDBMS for the object–relational model. Other extensions
            can indicate some other characteristic, such as DDBMS for a distributed database management systems.

            The functionality provided by a DBMS can vary enormously. The core functionality is the storage, retrieval
            and update of data. Codd proposed the following functions and services a fully-fledged general purpose DBMS
            should provide:<br>
            Data storage, retrieval and update
            User accessible catalog or data dictionary describing the metadata
            Support for transactions and concurrency
            Facilities for recovering the database should it become damaged
            Support for authorization of access and update of data
            Access support from remote locations
            Enforcing constraints to ensure data in the database abides by certain rules <br>
            It is also generally to be expected the DBMS will provide a set of utilities for such purposes as may be
            necessary to administer the database effectively, including import, export, monitoring, defragmentation and
            analysis utilities.[26] The core part of the DBMS interacting between the database and the application
            interface sometimes referred to as the database engine.<br>
            Often DBMSs will have configuration parameters that can be statically and dynamically tuned, for example the
            maximum amount of main memory on a server the database can use. The trend is to minimize the amount of
            manual configuration, and for cases such as embedded databases the need to target zero-administration is
            paramount.<br>
            The large major enterprise DBMSs have tended to increase in size and functionality and can have involved
            thousands of human years of development effort through their lifetime.[<br>
            Early multi-user DBMS typically only allowed for the application to reside on the same computer with access
            via terminals or terminal emulation software. The client–server architecture was a development where the
            application resided on a client desktop and the database on a server allowing the processing to be
            distributed. This evolved into a multitier architecture incorporating application servers and web servers
            with the end user interface via a web browser with the database only directly connected to the adjacent
            tier.<br>
            A general-purpose DBMS will provide public application programming interfaces (API) and optionally a
            processor for database languages such as SQL to allow applications to be written to interact with the
            database. A special purpose DBMS may use a private API and be specifically customized and linked to a single
            application. For example, an email system performing many of the functions of a general-purpose DBMS such as
            message insertion, message deletion, attachment handling, blocklist lookup, associating messages an email
            address and so forth however these functions are limited to what is required to handle email.<br>

        </p>
        <!-- img  -->
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/CodasylB.png/280px-CodasylB.png" alt="">
    </div>
    <div id="Database programme interface">
        <p>Database languages are special-purpose languages, which allow one or more of the following tasks, sometimes
            distinguished as sublanguages:

            Data control language (DCL) – controls access to data;
            Data definition language (DDL) – defines data types such as creating, altering, or dropping tables and the
            relationships among them;
            Data manipulation language (DML) – performs tasks such as inserting, updating, or deleting data occurrences;
            Data query language (DQL) – allows searching for information and computing derived information.<br>
            Database languages are specific to a particular data model. Notable examples include:

            SQL combines the roles of data definition, data manipulation, and query in a single language. It was one of
            the first commercial languages for the relational model, although it departs in some respects from the
            relational model as described by Codd (for example, the rows and columns of a table can be ordered). SQL
            became a standard of the American National Standards Institute (ANSI) in 1986, and of the International
            Organization for Standardization (ISO) in 1987. The standards have been regularly enhanced since and is
            supported (with varying degrees of conformance) by all mainstream commercial relational DBMSs.[29][30]
            OQL is an object model language standard (from the Object Data Management Group). It has influenced the
            design of some of the newer query languages like JDOQL and EJB QL.
            XQuery is a standard XML query language implemented by XML database systems such as MarkLogic and eXist, by
            relational databases with XML capability such as Oracle and DB2, and also by in-memory XML processors such
            as Saxon.
            SQL/XML combines XQuery with SQL.[31]<br>
            A database language may also incorporate features like:

            DBMS-specific configuration and storage engine management
            Computations to modify query results, like counting, summing, averaging, sorting, grouping, and
            cross-referencing
            Constraint enforcement (e.g. in an automotive database, only allowing one engine type per car)
            Application programming interface version of the query language, for programmer convenience
        </p>
    </div>
    <div id="Replication">
        Database storage is the container of the physical materialization of a database. It comprises the internal
        (physical) level in the database architecture. It also contains all the information needed (e.g., metadata,
        "data about the data", and internal data structures) to reconstruct the conceptual level and external level from
        the internal level when needed. Putting data into permanent storage is generally the responsibility of the
        database engine a.k.a. "storage engine". Though typically accessed by a DBMS through the underlying operating
        system (and often using the operating systems' file systems as intermediates for storage layout), storage
        properties and configuration setting are extremely important for the efficient operation of the DBMS, and thus
        are closely maintained by database administrators. A DBMS, while in operation, always has its database residing
        in several types of storage (e.g., memory and external storage). The database data and the additional needed
        information, possibly in very large amounts, are coded into bits.
    </div>
</body>

</html>
