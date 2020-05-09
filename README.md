Alert: Sadly, I don't have time to maintain this.

SQL RELATIONAL DATABASE SCHEMA
========================
A full working sql database demo , exhaustive examples of common web data resources that we use to manage with MySQL or SQLite.
Data tables and their relational models including users, sections, items/products, addresses, events, assets files, orders, payments, etc.
- See database schema diagram file ( in jpg or png)

### RESSOURCES / TABLES LIST : 

- SECTION/CATEGORY table ( ready for hierarchic relationship : parent-children)
- USER table (ready for authentication and controle access by roles with optional anonymous role )
- MESSAGE table (ready for email form, recaptcha and Email job services)
- ITEM/PRODUCT table with images gallery and html body field (ready for wysiwyg visual editors),
- ASSET table, assets files including images (ready for images processing)
- EVENT table (start/end datetime and ready for timestamp operations)
- ADDRESS table (ready for google map and geocoding with latitude and longitude)
- ORDER table and orderitem many-to-many relationship and shopping cart operations
- PAYMENT table (and credit-card table too but for security reason, some fields in credit-card table are never recommended to store in persistent data for production environment)
	(ready for cryptography and transaction operations via payment API services).

- Schema relationships samples (ready for ORM library) :
	- ONE-TO-MANY and MANY-TO-ONE
	- HIERARCHIC (Adjacency List Relationships : parent-children)
	- MANY-TO-MANY Association object
