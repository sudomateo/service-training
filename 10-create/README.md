# 10. Create

- In the `products` package define a type `NewProduct` with fields for name, cost, and quantity.
- Add a `Create` DB function that takes a `NewProduct` and returns a `*Product`.
- Add a `Create` POST handler decodes the request body into a `NewProduct` and calls `products.Create`.