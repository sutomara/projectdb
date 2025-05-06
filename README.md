# Zoo Management Database System

This project is a relational database system designed to manage the operational and financial activities of a zoo. It streamlines data management for animals, habitats, staff, costs, revenues, and visitors.

## Features

- Track animal species, diets, and habitats
- Manage staff and department responsibilities
- Monitor maintenance costs and staff salaries
- Record ticket sales and visitor data
- Analyze profitability and optimize resource allocation

## Database Schema

Key tables:
- `Animals(animal_id, name, habitat_id, kg_food_consumed, species_id)`
- `Customers(customer_id, first_name, last_name, age, email)`
- `Diets(diet_id, diet_name, price_per_kg)`
- `Employees(employee_id, first_name, last_name, salary, manager_id)`
- `Habitats(habitat_id, maintenance_cost)`
- `Tickets(habitat_id, customer_id, visitation_date)`

##  Technologies Used

- SQL (DDL, DML, and SELECT queries)
- Database design principles

## License

This project is for educational use.
