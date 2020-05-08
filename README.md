# Online Order

As customer, we want to see all the orders and able to:

- See list of the orders
- Add an order
- Edit an order
- Delete an order

When a customer does one of the actions, the application will show the success or errors.

## Objects

1.Order Item:

- Item
- Quantities
- Description
  1.Customer Information:
- FirstName
- LastName
- Address

1.Order:

- Customer Information [Inherit]
- Customer [Inherit]
- Delivery Address
- Order Items <Array>

1.Order List:

- Order <Array>
