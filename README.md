Doyeet - To-Do List Application
Welcome to Doyeet, a minimalist and intuitive To-Do List application designed to help you stay organized and productive. Built with a modern tech stack, Doyeet provides a seamless user experience for managing your daily tasks efficiently.

Features
Simple Task Management: Easily add, edit, and delete tasks to keep track of your to-dos.
Responsive Design: The app is fully responsive, ensuring a smooth experience on both desktop and mobile devices.
Elegant UI: The user interface is inspired by the Polish flag's color scheme, combining dark scarlet red and dark pink over a light gray background.
Real-time Updates: Task status updates instantly reflect on the UI without the need for page reloads.
Persistent Data Storage: Tasks are stored in an H2 relational database, ensuring that your to-do list is saved and accessible anytime.
Tech Stack
Frontend: React with Hooks for efficient state management.
Backend: Spring Boot, Hibernate, and JPA for robust server-side operations.
Database: H2 relational database for fast and easy data storage.
Styling: Custom CSS with a minimalist design approach.
Project Structure
Frontend: Located in the src/components directory, where you'll find the TodoComponent.jsx responsible for rendering the task list UI.
Backend: The RESTful API is developed with Spring Boot, with all relevant files stored in the src/api directory, including the ToDoapiService.js file.
Getting Started
Prerequisites
Node.js: Ensure that you have Node.js installed to run the React frontend.
Java: Java is required to run the Spring Boot backend.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/doyeet.git
Navigate to the project directory:

bash
Copy code
cd doyeet
Install frontend dependencies:

bash
Copy code
cd frontend
npm install
Run the frontend:

bash
Copy code
npm start
Navigate to the backend directory and run the Spring Boot application:

bash
Copy code
cd backend
./mvnw spring-boot:run
Usage
Visit http://localhost:3000 to start using the To-Do List application.
Add, edit, and manage your tasks efficiently with the Doyeet UI.
Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

License
This project is licensed under the MIT License.
