# Capstone: Restaurant Reservation System

## Description

This is my final capstone for Thinkful's Software Engineering program. I was tasked with creating a full-stack reservation system for a mock restaurant, _Periodic Tables_. The goal was to complete 8 user stories within a monorepo and successfully deploy a live website. This applications allows the restaurant employees to book, edit, cancel, and search for reservations in the database using customers' phone numbers.

## Website Link

Link: https://restaurant-reservation-64ap.onrender.com

## Application Features

If there are no current reservations for the date selected, the reservations section on the dashboard will be left blank.
![Alt text] (/images/2023-03-14%20(23).png)

Any existing reservations and tables on the given date are displayed on the dashboard. Selecting the `next` button takes users to the next day, selecting `previous` takes users to the previous day, and `today` navigates to the current day.
![Alt text] (https://raw.github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(22).png)

Selecting `New Reservation` allows the user to create a new reservation. Users will be alerted if there any errors when filling out the form.
![Alt text] (https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(24).png)

When a new form is submitted on a selected date, the reservation will be displayed on the dashboard. Users will then have the option of editing, canceling, or seating a reservation. 
![Alt text] (https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(25).png)

The `Edit` button navigates employees to the edit form, which allows them to edit reservations. Forms are prefilled with the current reservations data. 
![Alt text] (https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(26).png)

When a table is occupied, a `Finish` button will appear on the tables card. If the finish button is selected, a pop-up message will appear giving users the option to change the table's status back to `free`.
![Alt text] (https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(28).png)

Selecting `New Table` allows users to create a new table
![Alt text] (https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(29).png)

Selecting the `Search` button will take users to the search form where they can search for a reservation by their number.
![Alt text] (/https://github.com/loisobrero/starter-restaurant-reservation/blob/main/images/2023-03-14%20(30).png)


## Technologies Used

`Back-end`

- Node
- Express
- PostgreSQL (via ELephantSQL)
- Knex
- Jest

`Back-end` 
API Base Url: https://restaurant-reservation-x2ir.onrender.com

`Front-end`

- React
- Bootstrap
- e2e tests
- Puppeteer

## Installation

