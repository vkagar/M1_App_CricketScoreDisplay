# Requirements
## Introduction
  The aim of the project is to provide information of the MOVIE TICKET BOOKING SYTEM to a customer to book  the tickets.The project has been developed to carry out process easily and quickly.The system enables the user to Book tickets,Cancel tickets,View all booking records


## Features
#### Booking tickets
#### Cancel tickets
#### Change ticket price(only admin)
#### View all booking records
## Benefits
### Movie Ticket Booking system provides wide range of benefit they are as follows
#### Provides flexibility
#### For better performance
#### User Friendly
#### Can Select the seats as per choice


## SWOT Analysis

## Strengths

1.Simple and Convenient to use.

2.People can book ticket anytiome.

3.Booking ticket became easier.

4.can select the seat as per customer choice.

## Weakness

1.Internet access is needed.

2.Limited in Urban areas only.

## Opportunity

1.By this Idea,No customer will go home disappointing.

2.Expand capabilities  to cover more events.

## Threats

1.Improved functionalities by competetive  online ticketing portals.

2.Possibility of Missmanagement.



## 4 W's and 1 H

## When

When user wants to carry out the tasks quickly and this reduces manual work and saves time.

## What

Virtual medium to book ticket

## Where

Can be ordered from anywhere on pc or mobile phone.

## Who

People who are in a hurry can easily book their ticket.

People of all age groups can use it.

## How

By creating a system which will provide all the functionalities required,the booking of, cancelling of the tickes and other actions will be take more time and system needs more workers for these actions.


## Detail Requirements


## High Level Requirements 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to login to the system| Techincal | IMPLEMENTED | 
| HR02 | He shall be able to buy a ticket | Techincal | IMPLEMENTED |
| HR03 | He shall be able to get summary of the ticket booked | Techincal | IMPLEMENTED |
| HR04 | He shall be able to cancel a ticket| Techincal | IMPLEMENTED |

### Low level Requirements
 
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
|LR01|User shall be able to login to the system with correct login details|HR01|IMPLEMENTED|
|LR02|User need to book a ticket in a user entry mode|HR01|IMPLEMENTED|
|LR03|Summary of the booked ticket should be displayed  | HR03 |IMPLEMENTED|
|LR04| Admin can change the price for the movie| HR02|IMPLEMENTED|
|LR05| If appropriate login details are not entered a message is displayed-"wrong password" | HR01 | IMPLEMENTED |
|LR06 |Available movies should be displayed  | HR02 | IMPLEMENTED |


### TEST PLAN
## Table NO: High leval Test Plan

| **Test ID** | **HLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**TYPE oF TEST**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
| T_01|H_01| Provide required details for login to book a ticket| password| Successfully logined In | ----- | Requirement Based |
| T_02|H_02| When wrong password is entered| Password|  Entered Password is wrong | ------ | Requirement Based |
| T_03|H_03|Display the  details of movie available|  Enter choice | Display list | ------ | Scenario Based |
| T_04|H_04| Purchase a ticket for the movie available | enter choice | ThankYou for Booking Ticket | -------| Boundary Based|

## Table No : Low Leval Test Plan

| **Test ID** | **LLT ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**TYPE oF TEST**  |    
|-------------|-----|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  T_01|L_01| Cancel a ticket   |ID number|  Your ticket is cancelled | -------- |Requirements Based   |
|  T_02|L_02| Change the price of ticket (only admin) | password| Please enter new price | --------   | Scenario Based|
|  T_03|L_03| Change the price of ticket after login (only admin) | enter new price -price|Price Updated Successfully | --------  | Boundary Based |

