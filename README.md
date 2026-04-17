# sqli-vuln-lab
This project is a deliberately vulnerable web application designed for learning SQL Injection, focusing on UNION-based attacks only. It provides a safe env to explore how improper input handling can allow query manipulation and data extraction. Users can practice identifying columns, extracting data, and bypassing filters in realistic scenario.


Vulnerable Parameters for UNION Attacks
Endpoint
Parameter
Method
/api/search	q	GET
/api/search	category	GET
/api/search	minPrice, maxPrice	GET
/api/products/[id]	id (URL path)	GET
/api/auth/login	email	POST (JSON body)
/api/auth/login	password	POST (JSON body)
/api/admin/users	email	GET
/api/admin/users	name	GET

Access the site at: https://t1g8m37v3u61-d.space.z.ai/
