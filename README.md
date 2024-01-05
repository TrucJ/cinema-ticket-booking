# Cinema ticket booking
Implement cinema ticket booking standards in multiple languages such as:
- JS
- Python
- Go

## Idea:

- The cinema will have 3 types of seats: available seats, selected seats, and seats being reserved; the aisle is considered as selected seats.
- Divide the cinema (a 2D array of seats) into rows of seats (a 1D array of seats).
- For each row of seats, segment it into sections where both sides are selected seats.
- Each section needs to calculate 2 variables:

  X = Number of single empty seats (defined as seats that are empty and both sides of it are not empty seats) greater than 1.

  Y = Number of consecutive empty seat strings greater than 1.

    - If X > 2, return an invalid booking.
    - If X == 1 and Y > 0, return an invalid booking.
    - All other cases are considered valid.






