
## Answers

#### Question 1 

The relationship between the "Product" and "Product_Category" entities in this daigram is a one-to-many relationship.In a one-to-many relationship, a single record in one table can be associated with multiple records in another table.In this case, the "Product" table (parent) represents individual products.
The "Product_Category" table (child) represents product categories.

#### Question 2

With a Foreign key constraint,A foreign key joins a table to another table by referencing its primary key. A foreign key constraint specifies that the key can only contain values that are in the referenced primary key, and thus ensures the referential integrity of data that is joined on the two keys.
In this case ,the "Product" table has a column named category_id that acts as a foreign key.
This foreign key references the primary key of the "Product_Category" table.
This foreign key constraint enforces data integrity by ensuring that the category_id in a product record always points to a valid category present in the "Product_Category" table.


