# Supply-Chain-Management-System

Company A is a production company whose factory is located in Kandy. The company has several products and customers (wholesalers, retailers, and end customers). The company has a supply chain that uses the railway system to distribute their products to the customers islandwide.

A has negotiated with the railway department and has managed to retain a capacity allocated for them from each transportation train trip, and if the orders to be fulfilled with a certain trip exceed the capacity allocated, then those orders have to be scheduled to the next trip. The train capacity consumption of each item is defined with the item's details. Transportation via railway is only limited to a few main cities: Colombo, Negombo, Galle, Matara, Jaffna, Trincomalee, and the order goods are stored in a store near the railway station.

To distribute orders from a store to a delivery address, trucks are used. A store in a city has trucks, and those trucks are scheduled to deliver the orders. Trucks are driven only through a particular route at a time, and the routes are predefined in a way that the whole area related to the particular store is covered with the set of routes. The maximum time taken to complete each route is defined together with the route definition.

A driver and a driver assistant are always assigned to a truck schedule. Drivers, driver assistants, and trucks are independent entities. Driver and driver assistant assignments are done according to their respective rosters (Driver roster and Driver Assistant roster) and rosters have the following constraints:

- A driver should never be assigned to two consecutive truck schedules, and for an assistant, the maximum consecutive turns is two.
- Total work hours per driver should not exceed 40 hrs/week, and for an assistant, it’s 60 hrs/week.

Customers should place orders at least 7 days prior to the delivery date, and customers should be able to select a route that their delivery address is located on.

The management of the company requires a comprehensive reporting system for monitoring and analytics of the platform as well. The reports include:

- Quarterly sales report for a given year.
- Items with most orders.
- Sales report categorized according to main cities and routes.
- Working hours of drivers/driver assistants and used hours of trucks.
- Customer order report.

## Tech Stack

- **Frontend**: React, JavaScript, CSS
- **Backend**: Django
- **Database**: MySQL
