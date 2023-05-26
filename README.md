# Customer-and-Product-Maintenance

Customer and Product Maintenance System is a web application built using ASP.NET Core. It handles different routes and actions related to customers and products.

## Prerequisites
.NET 5.0 SDK or later
Installation
Clone the repository or download the source code files.
Open the solution in Visual Studio or your preferred code editor.
CustomerController
The CustomerController provides the following actions:

List: Handles the "/Customers" route and returns the "List" view, displaying a list of customers.
Details: Handles the "/Customer/Details/{customerID}" route and returns the "Details" view for a specific customer identified by the customerID parameter.
Create (GET): Handles the GET request for the "/Customer/Create" route and returns the "Create" view, allowing the user to create a new customer.
Create (POST): Handles the POST request for the "/Customer/Create" route, receives the form data for a new customer, validates it, and adds the customer to the data source if the data is valid. It then redirects to the "List" view.
Delete: Handles the GET request for the "/Customer/Delete/{customerID}" route, finds the customer with the specified customerID in the data source, removes it if found, and redirects to the "List" view.
ProductController
The ProductController provides the following actions:

List: Handles the "/Products" route and returns the "List" view, displaying a list of products.
Details: Handles the "/Product/Details/{productCode}" route and returns the "Details" view for a specific product identified by the productCode parameter.
Create (GET): Handles the GET request for the "/Product/Create" route and returns the "Create" view, allowing the user to create a new product.
Create (POST): Handles the POST request for the "/Product/Create" route, receives the form data for a new product, validates it, and adds the product to the data source if the data is valid. It then redirects to the "List" view.
Delete: Handles the GET request for the "/Product/Delete/{productCode}" route, finds the product with the specified productCode in the data source, removes it if found, and redirects to the "List" view.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to create a pull request or submit an issue in the repository.
