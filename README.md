# Desk Reservation Application

The Desk Reservation Application is designed for office environments where workspace is limited and not all staff have permanent desks. The system enables staff members to reserve available desks for specific dates and time periods, ensuring efficient workspace utilization and preventing booking conflicts.
The application allows users to submit desk booking requests through a user-friendly interface. Staff can make reservations for themselves or on behalf of other colleagues by selecting a date, time period, and available desk.

## Technologies Used

- SharePoint – Used as the backend data source for storing booking records and desk information.

- PowerApps – Used to design and build the application interface and booking logic.

## Key Features
**User Interface (User Page)**

- The user page provides staff with the ability to create and manage desk reservations. Users can:
- Create a new desk booking
- Select available desks
- Book desks for themselves or on behalf of another staff member
- View their current and previous bookings

**Admin Interface (Admin Page)**

- The admin page allows administrators to manage desk availability and booking records. Administrators can:
- Activate desks after they have been used
- Deactivate desks that are temporarily unavailable or damaged
- Add new desks to the system
- Remove desks from the system
- Monitor and manage booking activities

## How the System Works

- A user opens the application homepage.
- The user clicks the “New Booking” button to begin the reservation process.
- The system displays a booking form where the user enters the following information:
- Name of the user (or another staff member if booking on their behalf)
- Booking date
- Time period
- Desk selection
- Once a desk is selected, it is automatically removed from the available list for that time slot to prevent duplicate bookings.
- The user completes the booking by submitting the form.
- After submission, the booking details appear on the user's homepage for reference.

## Benefits of the Application

- Prevents duplicate desk bookings
- Improves workspace utilization
- Simplifies desk management in shared office environments
- Provides administrators with control over desk availability