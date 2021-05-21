# Day 3 - W10

### Daily Project: https://github.com/LoganPonder/castle

## In a SQL table, what is the difference between information in a row and information in a column?
In a SQL table columns contain name, date type, attributes ect... while rows contain the records/data for the columns.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters (
    id INT NOT NULL AUTO_INCREMENT,
    name VARCHAR(255) NOT NULL,
    age VARCHAR(255) NOT NULL,
    description VARCHAR(255) NOT NULL,
    PRIMARY KEY (id)
)

## What is the difference between the following statements:
DELETE FROM command allows you to delete a specific row from a table. DELETE TABLE, as the name indicates will delete the table in it's entirity.