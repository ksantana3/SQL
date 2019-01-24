## INTRODUCTION:

For this SQL project, I created models, databases, tables, and query reports for a smartphone application. While completing this project, I used MySQL Workbench to test and run a database application that was developed for parts C through G.

## SCENARIO:

You are the database designer and developer for a donut shop that wants to create a smartphone application where customers can order donuts. First, you will design a normalized entity-relationship (E-R) logical database model to store data related to the customer, donuts, and donut order. Next, you will create four tables with primary and foreign keys that are derived from your E-R model. Once the tables have been built, then you will create views and indexes to protect and fine-tune query performance. You will populate each of the tables with sample data. Finally, you will create both a simple “select-from-where” (sfw) query and a complex join query to produce meaningful reports on individual donut orders and summaries to determine which donuts sell the best.

## Requirements:

### A.  Construct a normalized model to represent the donut shop smartphone application database that supports the scenario above by doing the following:

1.  Using the attached “Sales Order Form” (unnormalized order form) for the donut ordering database as a reference, produce the final logical schema for this database by doing the following:

	a.  Design ONE table that is in first normal form and fulfills the following requirements:

	•   The table should have a primary key that uniquely identifies the records.
	•   The values in each of the columns should be atomic.
	•   There should be no repeating groups.
	•   Do not include the calculated attributes/fields (Line Total, Subtotal, Sales Tax and Total) in your normalization diagrams.

 		i.   Explain how you designed the table (suggested length of 1 paragraph).

	b.  Design THREE tables that are in second normal form and fulfill the following requirements:

	•   The tables should meet all of the requirements for the first normal form.
	•   All functional dependencies should be removed from the tables.
	•   Each of the tables should have all primary and/or foreign keys designated.
	•   Do not include the calculated attributes/fields (Line Total, Subtotal, Sales Tax and Total) in your normalization diagrams.

 		i.   Explain how you designed the tables (suggested length of 1 paragraph).

	c.  Design FOUR normalized tables that are in third normal form and fulfill the following requirements:

	•   The tables should meet all of the requirements for the first and second normal forms.
	•   All transitive dependencies should be removed from the tables.
	•   Each of the tables should have all primary and/or foreign keys designated.
	•   Do not include the calculated attributes/fields (Line Total, Subtotal, Sales Tax and Total) in your normalization diagrams.
	•   There should be FOUR resulting tables: one for customer information, one for donut information, one for order information and one for order line item information.

 		i.   Explain how you designed the tables (suggested length of 1 paragraph).
