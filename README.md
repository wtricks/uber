# Uber ride APIs 
The project is a comprehensive and user-friendly Spring Boot application designed to facilitate various aspects of a transportation management system. It provides a robust platform for managing and coordinating the activities of administrators, customers, and drivers within the context of a transportation service.

# Table of Contents
- [Introduction](#introduction)
- [Admin Controller](#admin-controller)
- [Customer Controller](#customer-controller)
- [Driver Controller](#driver-controller)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The project is a comprehensive and user-friendly Spring Boot application designed to facilitate various aspects of a transportation management system. It provides a robust platform for managing and coordinating the activities of administrators, customers, and drivers within the context of a transportation service.

## Admin Controller
The Admin Controller in this application provides the following endpoints for managing administrative tasks:

- Registration

    Endpoint: `/admin/register`
    
    Description: Allows administrators to register new users or accounts.

- Update

    Endpoint: `/admin/update`

    Description: Provides the ability to update information related to admin accounts or users.

- Delete

    Endpoint: `/admin/delete`

    Description: Enables administrators to delete admin accounts or users from the system.

- List of Customers
    
    Endpoint: `/admin/listOfCustomers`

    Description: Returns a list of all registered customers in the system.

- List of Drivers

    Endpoint: `/admin/listOfDrivers`

    Description: Retrieves a list of all registered drivers in the system.

## Customer Controller
The Customer Controller offers functionality for managing customer-related tasks:

- Customer Registration

    Endpoint: `/customer/register`

    Description: Allows new customers to register their accounts in the system.

- Customer Update

    Endpoint: `/customer/update`

    Description: Provides the ability for customers to update their information.

- Book a Trip

    _Endpoint_: `/customer/bookTrip`

    Description: Allows customers to book a trip or request transportation services.

- Complete a Trip
    Endpoint: `/customer/complete`

    Description: Marks a trip as completed by the customer.

- Cancel a Trip

    Endpoint: `/customer/cancelTrip`

    Description: Allows customers to cancel a previously booked trip.

## Driver Controller
The Driver Controller offers features for managing driver-related tasks:

- Driver Registration

    Endpoint: `/driver/register`

    Description: Allows new drivers to register their accounts in the system.

- Driver Deletion

    Endpoint: `/driver/delete`

    Description: Enables administrators to delete driver accounts or drivers from the system.

- Driver Status

    Endpoint: `/driver/status`

    Description: Retrieves the status of a driver, such as availability or current trip status.


# License

[MIT](/LICENSE) based project
