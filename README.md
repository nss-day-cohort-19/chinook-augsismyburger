# chinook-augsismyburger
Chinook Exercises

1.
`select c.firstname, c.lastname, c.customerID, c.Country
from customer c
where c.Country != "USA";`

2.
`select c.firstname, c.lastname, c.customerID, c.Country
from customer c
where c.Country == "Brazil";`

3.
`select c.firstname, c.lastname, i.InvoiceId, i.InvoiceDate, i.billingCountry
from Customer c
left join Invoice i on c.CustomerId == i.CustomerId
where c.Country == "Brazil";`
