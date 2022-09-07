# Node.js Onix Internship 2022

Your task is create server with one route, that will return current USD rate for cryptocurrency provided as parameter.

### Example:

```
http://localhost:3000/rates?currency=bitcoin
http://localhost:3000/rates?currency=ethereum
```

### Response 
```
{
    "usd": "1536.8376043904155762"
}
```

### Additional information:
* Cryptocurrency API for rates: https://docs.coincap.io/
* As parameter we can pass any cryptocurrency that provided with coincap API.
* If pass not existing value, need to show error message, and change response status to 404.

### When you finish task, send link with your github repo to [HR manager](mailto:tatiana.gdeshinskaya@onix-systems.com).

