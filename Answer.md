# 1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.
Ans : In the provided database schema, there is a relationship between the Product and Product_Category entities. This relationship is represented by the `category_id` column in the Product table. 
- The Product table has a column named 'category_id', which is an 'int' type. This column likely serves as a foreign key.
- The 'category_id' column in the 'Product' table is intended to reference the `id` column in the `Product_Category` table.
- This means that each row in the `Product` table can be associated with a specific category by setting its `category_id` to the corresponding `id` of the category in the `Product_Category` table.
- The `category_id` in the `Product` table establishes a link to a specific category defined in the `Product_Category` table.
- This relationship allows a product to be categorized under a specific category defined in the `Product_Category` table. For example, if you have a "Electronics" category with `id` 1 in the `Product_Category` table, you could have multiple products in the `Product` table with their `category_id` set to 1 to indicate that they belong to the "Electronics" category.
-So, the `category_id` in the `Product` table serves as a foreign key that links each product to a specific category defined in the `Product_Category` table, establishing a relationship between the two entities.

 # 2. How could you ensure that each product in the "Product" table has a valid category assigned to it?
 Ans : 
