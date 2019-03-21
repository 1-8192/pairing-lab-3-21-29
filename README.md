# Hotel Booking App pairing-lab-3-21-29

#Overview 

Hotels need people to fill their rooms. People need hotels to sleep in. Your goal is to create an app that helps them do that! For this lab, you will need to create a full rails app from the ground up, with full MVC and CRUD features for the models and view pages.

#Objectives

1. Create a bi-directional has many through relationship
2. Create a good join model
3. Build out full CRUD functionaility for the app (not for each model)
4. Use good MVC principles in app setup.
5. Create some forms
6. Have fun!

#Instructions 

1. Hotels have names and addresses. They can have many guests.
2. Guests have names, ages, and nationalities, and can stay in many hotels.
3. A booking will connect a hotel with a guest, and have a check-in date and a check-out date.
4. Booking dates cannot be earlier than today's date, and a booking MUST HAVE a check-in date. 
5. Hotels - will have an index page listing all hotels, with links to their respective show pages.
6. Hotel show pages should display the hotel name, address, and a link to create a new booking. 
7. The Guest show page should display the guest name, nationality, and list links to associated bookings that display the booking's hotel name. It should also have a link to the hotels index page. 
8. The bookings show page should have edit buttons to edit individual bookings, as well as a delete booking button to delete a booking.

#Stretch Goals 

1. Display check-in dates in the following format- "Januray 19, 2019"
2. Booking links in the guest show page should also display the assocated check in and checkout dates. 
3. Guest index page should link to a create guest form to make a new guest.

