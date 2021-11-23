### TEST PLAN
## Table NO: High leval Test Plan

| **Test ID** | **HLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**TYPE oF TEST**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
| H_01| Provide required details for login to book a ticket| password| Successfully logined In | Successfully logined In| Requirement Based |
| H_02| When wrong password is entered| Password|  Entered Password is wrong | Entered Password is wrong | Requirement Based |
| H_03|Display the  details of movie available|  Enter choice | Display list | Display list | Scenario Based |
| H_04| Purchase a ticket for the movie available | enter choice | ThankYou for Booking Ticket | ThankYou for Booking Ticket| Boundary Based|

## Table No : Low Leval Test Plan

| **Test ID** | **LLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**TYPE oF TEST**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01| Cancel a ticket   |ID number|  Your ticket is cancelled | Your ticket is cancelled |Requirements Based   |
|  L_02| Change the price of ticket (only admin) | password| Please enter new price | Please enter new price   | Scenario Based|
|  L_03| Change the price of ticket after login (only admin) | enter new price -price|Price Updated Successfully | Price Updated Successfully  | Boundary Based |
