# Relational-Data-Analysis-with-Pig-and-Spark

Using Pig and Spark SQL to solve the analytic problems for a set of linked tables. We have three data files with the following schema: customer(cid, name, age, city, sex), book(isbn, name), and purchase(year, cid, isbn, seller, price), where purchase.cid is the foreign key to customer.cid and purchase.isbn is the foreign key to book.isbn. The fields in the dataset are separated by "\t". You should assign the schema, i.e., field names and and types, to the fields when you load the data.

Problems:
A)We need to find out how much each seller earned
B)Need to find out names of the books which Amazon is selling for least among all sellers
C)Need to find out who purchased the books that an other particular customer brought
