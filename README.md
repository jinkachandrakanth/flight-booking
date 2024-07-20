**Here is a breakdown of the entities and their relationships:**

1. USER: Represents the individuals or entities who book flights. A customer can place multiple bookings and make various payments.

2. BOOKING: Represents a specific flight booking made by a customer. A booking includes particular flight details and passenger information. A customer can have multiple bookings.   
 
3. FLIGHT: Represents a flight that is available for booking. Here, the flight details will be provided and the users can book as many available seats.

5. ADMIN: The admin is responsible for all the backend activities. The admin manages all the bookings, adds new flights, and so on

**Folder setup:**
To start the project from scratch, first create frontend and backend folders to install essential libraries and write code.

- client

 

- Server

**Installation of required tools:**


Now, open the frontend folder to install all the necessary tools we use.

For frontend, we use:

- React Js
 
- Bootstrap

- Axios

### Frontend Development

**1. Login/Register:**

- Create a Component that contains a form for taking the username and password.

- If the given inputs match the data of the user or admin or flight operator then navigate it to their respective home page
 

**2. Flight Booking (User):**

- In the front end, we implemented all the booking codes in a modal. Initially, we need to implement a flight searching feature with inputs of Departure city, Destination, etc.,

- Flight Searching code: With the given inputs, we need to fetch the available flights. With each flight, we add a button to book the flight, which redirects to the flight booking page.

**3. Fetching user bookings:**

- On the bookings page, along with displaying the past bookings, we will also provide an option to cancel that booking.

**4. Add new flight(Admin):**

- Now, in the admin dashboard, we provide functionality to add new flights.

- We create an HTML form with the required inputs for the new flight and then send an HTTP request to the server to add it to the database.

**5. Update Flight:**

- Here, in the admin dashboard, we will update the flight details in case we want to make any edits to it

- Along with this, implement additional features to view all flights, bookings, and users in the admin dashboard.


###  Backend Development

1. **Database Configuration:**

- Set up a MongoDB database either locally or using a cloud-based MongoDB service like MongoDB Atlas or use locally with MongoDB compass.

- Create a database and define the necessary collections for flights, users, bookings, and other relevant data.

**2. Create Express.js Server:**

- Set up an Express.js server to handle HTTP requests and serve API endpoints.

- Configure middleware such as body-parser for parsing request bodies and cors for handling cross-origin requests.

3.  **Define API Routes:**

- Create separate route files for different API functionalities such as flights, users, bookings, and authentication.

-  Define the necessary routes for listing flights, handling user registration and login managing bookings, etc.

- Implement route handlers using Express.js to handle requests and interact with the database.

**4.  Implement Data Models:**

- Define Mongoose schemas for the different data entities like flights, users, and bookings.

- Create corresponding Mongoose models to interact with the MongoDB database. Implement CRUD operations (Create, Read, Update, Delete) for each model to perform database operations.

5. **User Authentication:**

- Create routes and middleware for user registration, login, and logout.

- Set up authentication middleware to protect routes that require user authentication.

6. **Handle new Flights and Bookings:**

- Create routes and controllers to handle new flight listings, including fetching flight data from the database and sending it as a response.

- Implement booking functionality by creating routes and controllers to handle booking requests, including validation and database updates.

7.  **Admin Functionality:**

- Implement routes and controllers specific to admin functionalities such as adding flights, managing user bookings, etc.

- Add necessary authentication and authorization checks to ensure only authorized admins can access these routes.

8.  **Error Handling:**

- Implement error handling middleware to catch and handle any errors that occur during the API requests.

- Return appropriate error responses with relevant error messages and HTTP status codes.

**login page:**

![image](https://github.com/user-attachments/assets/b0b24ded-c040-45cb-96e6-e4fd28258e3c)

**LandingPage:**

![image](https://github.com/user-attachments/assets/d680a737-c296-4ede-aaca-ef0f3e3fd183)


![image](https://github.com/user-attachments/assets/3729aa03-bf69-4d50-9323-32769fa0c13c)

**Admin page:**

![image](https://github.com/user-attachments/assets/a8f5599d-2340-4e1b-b035-7037f9bf0872)

**AllBookings page:**

![image](https://github.com/user-attachments/assets/24e799bf-31fb-46d2-9ca1-2312d8b46112)

**AllFlights pages:**

![image](https://github.com/user-attachments/assets/1866d8a6-125e-4901-a19b-337d836bcd6a)

**AllUsers page:**

![image](https://github.com/user-attachments/assets/53d7fbb0-d634-4dfa-8467-29c686cf7b4c)

BookFlight page:

![image](https://github.com/user-attachments/assets/6f2d8a0e-4624-40c5-a078-808d5f3e17d8)

**Bookings page:**

![image](https://github.com/user-attachments/assets/c6f021c1-6244-4206-9c1c-4420734d228e)

**NewFlight page:**

![image](https://github.com/user-attachments/assets/46d443e5-51f8-46b8-bae4-135b95ecc542)

**EditFlight page:**

![image](https://github.com/user-attachments/assets/1148f751-591c-4adc-82c8-e4144a76b23d)

**FlightAdmin page:**

![WhatsApp Image 2024-07-19 at 23 33 48_4bc23614](https://github.com/user-attachments/assets/553e89b4-9f02-4d16-980c-31eb80609ccf)

**Flights page:**

![image](https://github.com/user-attachments/assets/605ffc99-0721-43a7-aef4-391d0d3f57e1)

### Developed With

- [Visual Studio Code](https://code.visualstudio.com/) - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring

- [Node.js](https://nodejs.org/en/) - Javascript runtime
- [React](https://reactjs.org/) - A javascript library for building user interfaces
- [Babel](https://babeljs.io/) - A transpiler for javascript
- [Webpack](https://webpack.js.org/) - A module bundler
- [SCSS](http://sass-lang.com/) - A css metalanguage
- [Bootstrap 4](https://getbootstrap.com/) - Bootstrap is an open-source toolkit for developing with HTML, CSS, and JS
- [Axios](https://github.com/axios/axios) - Promise-based HTTP client for the browser and node.js
- [Express js](http://expressjs.com/) - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
- [MongoDB atlas](https://www.mongodb.com/cloud/atlas) - MongoDB Atlas is the global cloud database service for modern applications.
- [Passport Js](http://www.passportjs.org/) - Passport is authentication middleware for Node.js. Extremely flexible and modular, Passport can be unobtrusively dropped into any Express-based web application.
