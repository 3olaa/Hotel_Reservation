# Hotel_Reservation
It is a hotel reservation web application like booking.com

- Signing up process include the following
a. The form must use a captcha whether online or offline like “google captcha” …etc.
b. During the registration the user will not supply a password
c. After the form submission an email (real email you can look at java mail as an example) will be sent to the user with a generated temporary password to login the application with it.
- All users able to change their information in the profile page like password, display name…etc. except for the username.
- Ajax in different scenarios including signing up (to check if the user registered before).
- Most of input forms validated either by using HTML5 controls, Java script

It consists of two user groups which are client (a person who wants to book a hotel room) and hotel reservation admin (a person who is responsible to manage reservations)

For client (user group)
1. Search for a hotel in which user needs to specify (where he/she is going, the check-in date, check-out date as well as the number of adults and children).
2. View a list of hotels according to user research along with enough information about the hotel (such as hotel name, hotel rating, availability, expected price ... etc.)
3. Client able to choose one of the search-result hotels and see more information about it (rooms available, room type, room facilities etc.)
4. View hotel photos
5. Client should be able to view the hotel on Google maps
6. Make a hotel reservation.
7. Change / Cancel reservation.
8. Rate Hotel


For hotel reservation admin (user group)
1. View a list of reservations (current)
2. View reservation history for a specific period (from date – to date)
3. Search for a client and view his / her information (for example user phone number as well as email) in case s/he needs to contact the client and confirm reservation.
4. Cancel reservation
5. Get notification upon client cancellation by email (real email message – can use java mail or any other email libraries) and on the system
6. Update hotel basic information (contact information, hotel facilities, add location, other branches information)
7. Upload and update hotel photos
8. Add / update room information
