# EjerciciosSQL
Ejercicio de DataLemur en SQL
1. Leccion 101 - SQL TUTORIAL INTRO
    * SQL Select Practice Exercise 
        SELECT * FROM products;
    * Given the reviews table, write a query to retrieve all 3-star reviews using the SQL WHERE clause. Only display the user_id and stars columns.
       SELECT user_id, stars FROM reviews WHERE stars=3;
    * SQL WHERE AND Practice Exercise

        1. SELECT * FROM reviews WHERE stars=4 AND review_id < 6000 AND review_id > 2000 AND user_id<>142;

        2. SELECT * FROM reviews WHERE user_id=123 OR user_id=265 OR user_id=362 AND stars > 2 AND stars <=4;
    * SQL BETWEEN Practice Exercise
    
    SELECT manufacturer, drug, units_sold FROM pharmacy_sales WHERE (units_sold BETWEEN 100000 AND 105000) AND (manufacturer='Biogen' OR manufacturer='AbbVie' OR manufacturer='Eli Lilly');
2. Seccion 2
3. Seccion 3
4. Seccion 4