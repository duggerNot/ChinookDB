# ChinookDB


## Learning SQL Through Doing


1. SELECT 
	c.CustomerID, 
	c.FirstName, 
	c.LastName, 
	c.Country 
FROM Customer as c 
WHERE c.Country IS NOT 'USA'

2. SELECT 
	c.CustomerID, 
	c.FirstName, 
	c.LastName, 
	c.Country 
FROM Customer as c 
WHERE c.Country IS 'Brazil'

3. SELECT 
    c.FirstName, 
    c.LastName, 
    i.InvoiceID, 
    i.BillingCountry, 
    i.InvoiceDate 
FROM
    Invoice as i,
    Customer as c 
WHERE i.BillingCountry IS 'Brazil'

4. SELECT 
    c.FirstName, 
    c.LastName, 
    i.InvoiceID, 
    i.BillingCountry, 
    i.InvoiceDate 
FROM
    Invoice as i,
    Customer as c 
WHERE i.BillingCountry IS 'Brazil'

5. SELECT DISTINCT i.BillingCountry FROM Invoice as i