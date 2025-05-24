# Sports Booking System
## Overview
This is a simple sports booking system that allows users to select a venue, view available time slots for a specific date, and book a slot for a chosen sport. The frontend is built using Vanilla JavaScript, and the backend is implemented with Node.js and Express, using a JSON file for data storage.

## 🚀 Features
Frontend (Vanilla JS)

   🔽 Select a venue from a pre-filled dropdown

   📅 Choose a date

   ⏱️ View available slots for the selected venue and date

   📝 Fill out a form to confirm booking

Backend (Node.js with mock JSON)

   📡 Serve available time slots via GET /bookings

   ✅ Accept and store bookings via POST /bookings

   🔒 Prevent double booking by marking slots as booked


## Technologies Used
| Component       | Technology/Tool       | Purpose                                      |
|-----------------|-----------------------|----------------------------------------------|
| **Frontend**    | HTML                 | Structure the user interface                 |
|                 | CSS                  | Style the user interface                    |
|                 | Vanilla JavaScript   | Handle client-side logic and API requests    |
| **Backend**     | Node.js              | Runtime environment for the server          |
|                 | Express              | Framework for building the API server       |
| **Data Storage**| JSON file            | Store venue and booking data                |
| **Dependencies**| express              | Create and manage backend server routes     |
|                 | cors                 | Enable cross-origin resource sharing        |
|                 | nodemon              | Auto-restart server during development      |

## Installation

1) Clone the repository:
```
git clone https://github.com/BhavyaRI/Sports_Booking.git
cd Sports_Booking 
```

2) Install backend dependencies

Navigate to the backend directory and run:
```
cd backend
npm install express cors 
npm install --save-dev nodemon

```

3)  Install the CORS Unblocker extension:

Open Google Chrome and visit the [ CORS Unblocker Extension](https://chromewebstore.google.com/detail/lfhmikememgdcahcdlaciloancbhjino?utm_source=item-share-cb)

Click Add to Chrome and restart the browser



4) Running the Application

Start the backend server:
```
npm run dev
```
This uses nodemon to start the Express server and automatically restart on file changes. The server typically runs on http://localhost:3000.

5) Access the frontend:

Open the index.html file in the frontend directory using a web browser (preferably Chrome with the CORS Unblocker extension enabled).

### Notes

Ensure the CORS Unblocker extension is enabled in Chrome during development to avoid CORS-related errors when the frontend makes requests to the backend.
The JSON file (data.json) serves as a mock database and is updated with each booking.

