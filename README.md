select * from film
where replacement_cost between 12.98 and 16.99

select first_name, last_name from actor
where in first_name 'Penelope' or 'Nick' or 'Ed'


select * from film
where in (rental_rate(0.99, 2.99, 4.99)) and where in replacement_cost (12.99, 15.99, 28.99)
