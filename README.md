
Wanderlust is a minimalistic web application inspired by Airbnb. It allows users to list, search, and book accommodations from around the world.

Features
User Authentication: Users can sign up, log in, and log out securely.
Property Listings: Hosts can list their properties with details like location, price, etc.
Booking System: Users can book available properties for specific dates and leave their reviews for the same.
Responsive Design: The application is designed to work on various screen sizes.


Technology Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Images:Cloudinary
Authentication: Passport
Hosting:Render
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Krish-agg/Webprojects.git
cd Webprojects
Install the dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root directory.
Add the following variables:
makefile
Copy code
CLOUD_API_SECRET=cloudinary-secret
CLOUD_API_KEY=cloudinary-api-key
CLOUD_NAME=cloudinary-cloud-name
ATLASDB_URL=your-database-url
SECRET=session_secret
Run the development server:

bash
Copy code
npm start
Access the application:

Open your browser and navigate to http://localhost:8080/listings.
Usage
For Hosts:

Sign up and create a new property listing.
Provide details such as location, price,etc.
Manage your listings and bookings.
For Guests:

Sign up and search for properties based on location and date.
View property details, including photos and reviews.
Book a property for your specified dates.
