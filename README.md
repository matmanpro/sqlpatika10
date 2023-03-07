# sqlpatika10

select city, country from city
left join country on city.city_id = country.country_id

select first_name, last_name, payment_id from customer
right join payment on customer.customer_id = payment.customer_id


select rental_id, first_name, last_name from customer
full join rental on customer.customer_id = rental.customer_id
