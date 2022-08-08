select * from film
where lenght > 60 and lenght <75;

selet * from film
where rental_Rate = 0.99 and replacement_cost = 12.99 or replacement_cost = 28.99

select * from customers
where first_name = 'Mary'

select * from film
where not length > 50 and (not rental_rate = 2.99 or rental_rate = 4.99)
