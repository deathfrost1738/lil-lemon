# lil-lemon

Bookings API

GET all bookings: /api/bookings/
POST a new booking: /api/bookings/
GET a specific booking: /api/bookings/{id}/
PUT update a specific booking: /api/bookings/{id}/
DELETE a specific booking: /api/bookings/{id}/
Menu API

GET all menu items: /api/menu/
POST a new menu item: /api/menu/
GET a specific menu item: /api/menu/{id}/
PUT update a specific menu item: /api/menu/{id}/
DELETE a specific menu item: /api/menu/{id}/
User Registration and Authentication

Register a new user: /auth/users/
Login to obtain a token: /auth/token/login/
Logout to invalidate the token: /auth/token/logout/
Retrieve user information: /auth/users/me/
Date-Specific Bookings

GET bookings for a specific date: /api/bookings?date={YYYY-MM-DD}
Unit Test API

Run unit tests: /api/tests/
