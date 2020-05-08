# Online Order

As customer, we want to see all the orders and able to:

- See list of the orders
- Add an order
- Edit an order
- Delete an order

When a customer does one of the actions, the application will show the success or errors.

## What is OOP?

> When you want to develope a peace of code and use it several place, you can use OOP.

## Why would you use OOP?

> Minimize coding
> Memory efficiency
> Test ability
> Inheritance
> In which cases would an OOP pattern be a better choice?
> As a developer, you can break down the project to the entities and objects.
> Repeatable process
> Dynamic behavior on runtime

## Application Purpose

- Add an order
- List of the orders
- Edit an order
- Delete an order

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
