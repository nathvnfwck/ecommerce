# Shopping Cart

> ## Functional Requirement

1. [ ] Receives a **POST** request at route **/cart**
2. [ ] Validates if the request body contains the **productId** and **quantity** parameters
3. [ ] Returns **201** if the product is successfully added to the cart

> ## Business Rule

- Promotions and Discounts:
  1. [ ] Applies special discounts based on defined rules
  2. [ ] Returns the final price of the product with the applied discount
