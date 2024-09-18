# Railway Reservation System GUI

This Python script implements a Railway Reservation System using a Tkinter GUI. The system is connected to a SQLite database to perform various queries related to booked trains and passengers.

## Features

1. **Retrieve Booked Trains by Passenger Name:**
   - Enter the first name and last name of a passenger.
   - Click the "Get Results" button to display the trains booked by the specified passenger.

2. **Retrieve Train Details by Date:**
   - Enter the train date in the format "yyyy-mm-dd".
   - Click the "Get Results" button to display details of passengers traveling on the specified date.

3. **Retrieve Details by Age Range:**
   - Enter the minimum and maximum age range.
   - Click the "Get Results" button to display details of passengers within the specified age range.

4. **Retrieve Train Details by Ticket Type:**
   - Enter the ticket type (e.g., "First Class" or "Economy").
   - Click the "Get Results" button to display details of trains based on the specified ticket type.

5. **Retrieve Train Details by Train Name:**
   - Enter the train name.
   - Click the "Get Results" button to display details of passengers booked on the specified train.

6. **Cancel Ticket:**
   - Enter the passenger's SSN and the train number to cancel the ticket.
   - Click the "Cancel Ticket" button to cancel the ticket and update the waiting list.

## How to Use:

1. Ensure Python and the required libraries (Tkinter) are installed.
2. Run the script in a Python environment.
3. The GUI will appear with different tabs for various functionalities.

## Note:-
use a csv files to create the db and connect it with the code.
