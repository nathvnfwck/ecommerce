# Manage Order

> ## Functional Requirement

1. [ ] Receives a **GET** request at route **/orders**
2. [ ] Returns a list of orders with shipping status information

> ## Business Rule

- Return Policy:
  1. [ ] Receives a **PUT** request at route **/orders/{orderId}**
  2. [ ] Validates if the request contains the necessary parameters for the return
  3. [ ] Returns **200** if the return is processed successfully
