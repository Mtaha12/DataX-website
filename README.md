DataX Website Project
Overview
This project involves the development of a fully functional website for DataX, a software company, with both front-end and back-end components. The front-end was designed using HTML, CSS, and JavaScript, while the back-end was implemented using Node.js with Express and MongoDB.

Front-End
The front-end of the DataX website includes:

Home Page: Overview of the company, latest projects with cart functionality, customer reviews.
Services Page: Detailed descriptions of services offered by DataX.
Blogs Page: Interactive blog posts related to industry trends and company updates.
Contact Us Page: Form for users to send inquiries and feedback.
Social Media Integration: Links to DataX's social media profiles.
Floating Chat Bot: Interactive chat bot for real-time assistance.
Back-End
The back-end provides functionality for:

Managing Projects: CRUD operations for project listings.
Handling Reviews: CRUD operations for customer reviews.
Processing Contact Form Submissions: Handling and storing user inquiries.
Installation
Front-End
Clone the Repository:

bash
Copy code
cd datax-frontend
Open the HTML Files:

The front-end does not require installation. You can open the HTML files directly in your web browser.
Back-End
Clone the Repository:

bash

Install Dependencies:

bash
Copy code
npm install
Run the Server:

bash
Copy code
npx nodemon server.js
Set Up MongoDB:

Ensure MongoDB is installed and running on your local machine.
The server connects to MongoDB at mongodb://localhost:27017/datax. Adjust the connection string if necessary.
Usage
Front-End
Navigate to the Home Page to view the company's overview, latest projects, and customer reviews.
Visit the Services Page for detailed descriptions of DataX’s services.
Explore the Blogs Page to read articles about industry trends and updates.
Use the Contact Us Page to send inquiries or feedback through the contact form.
Back-End
API Endpoints:
GET /api/projects - Retrieve all projects.
POST /api/projects - Add a new project.
GET /api/reviews - Retrieve all reviews.
POST /api/reviews - Add a new review.
POST /api/contact - Submit a contact form message.
Contributing
Feel free to submit issues or pull requests. Please follow the guidelines for contributing to this project.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or feedback, please contact me at mtaha2004.22.2#gmai.com.
