How would I grab the top 3 customers according to their points?

```bash
SELECT * 
FROM customers
ORDER BY points DESC -- order according to points of customers from top to bottom
LIMIT 3
```

* Remember, the LIMIT clause should ONLY come at the end