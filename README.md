## taller-7
### Script bases de datos 
Create table categories(category_id int primary key auto_increment, category_name varchar(50) not null);
Create table products(product_id int primary key auto_increment, product_name varchar(50) not null, product_value int not null, category_id int not null, foreign key(category_id) references categories(category_id));
