# Welcome to the Restaurant Reservation System

Discover the Restaurant Reservation System, a versatile full-stack web application designed for restaurant managers. Seamlessly handle reservations, from creation to modification and deletion, while ensuring a delightful user experience. Developed as part of the Thinkful Engineering Immersion program, this system empowers you to efficiently manage reservations and tables.

## Highlighted Features

- **Dynamic Reservations:** Effortlessly create, edit, and list reservations, staying organized day by day.
- **Effortless Table Management:** Assign specific tables to reservations and track real-time table availability.
- **Swift Search:** Instantly retrieve reservations using mobile numbers.
- **Reservation Status Visualization:** Gain insights into reservation statuses (booked, seated, finished) for streamlined management.
- **Future Reservation Control:** Ensure reservations align with open days and eligible hours.
- **User-friendly Interface:** Navigate and manage reservations with an intuitive, responsive UI across all devices.

## Technology Stack

- **Frontend:** Crafted with React, JavaScript, and Bootstrap for a polished user interface.
- **Backend:** Powered by Node.js, Express.js, and Knex to handle server-side logic.
- **Database:** PostgreSQL for efficient data storage and retrieval.

## API Documentation

### List Reservations

Retrieve a list of all reservations.

Endpoint: `GET /api/reservations`

Response Example:

```json
{
  "data": [
    {
      "first_name": "Rick",
      "last_name": "Sanchez",
      "mobile_number": "202-555-0164",
      "reservation_date": "2020-12-31",
      "reservation_time": "20:00:00",
      "people": 6,
      "status": "booked",
      "created_at": "2020-12-10T08:30:32.326Z",
      "updated_at": "2020-12-10T08:30:32.326Z"
    },
    {
      "first_name": "Frank",
      "last_name": "Palicky",
      "mobile_number": "202-555-0153",
      "reservation_date": "2020-12-30",
      "reservation_time": "20:00",
      "people": 1,
      "status": "booked",
      "created_at": "2020-12-10T08:31:32.326Z",
      "updated_at": "2020-12-10T08:31:32.326Z"
    },
    {
      "first_name": "Bird",
      "last_name": "Person",
      "mobile_number": "808-555-0141",
      "reservation_date": "2020-12-30",
      "reservation_time": "18:00",
      "people": 1,
      "status": "booked",
      "created_at": "2020-12-10T08:31:32.326Z",
      "updated_at": "2020-12-10T08:31:32.326Z"
    },
    {
      "first_name": "Tiger",
      "last_name": "Lion",
      "mobile_number": "808-555-0140",
      "reservation_date": "2025-12-30",
      "reservation_time": "18:00",
      "people": 3,
      "status": "booked",
      "created_at": "2020-12-10T08:31:32.326Z",
      "updated_at": "2020-12-10T08:31:32.326Z"
    },
    {
      "first_name": "Anthony",
      "last_name": "Charboneau",
      "mobile_number": "620-646-8897",
      "reservation_date": "2026-12-30",
      "reservation_time": "18:00",
      "people": 2,
      "status": "booked",
      "created_at": "2020-12-10T08:31:32.326Z",
      "updated_at": "2020-12-10T08:31:32.326Z"
    }
  ]
}
```

Explore the Restaurant Reservation System and experience hassle-free reservation management like never before.

**View the live demo**: [Restaurant Reservation System](https://restaurant-reservations-client-pwym.onrender.com)

## Installation Instructions

1. Clone the Repository
Clone and fork the repository to get started.

2. Install and Run

Run npm install to install the necessary dependencies.
Launch the application with npm start.
