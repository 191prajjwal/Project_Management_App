<h1 align="center" id="title">Project Management App</h1>

<p id="description">The Project Management App is a web-based platform designed to help users organize assign and track personal and team-based tasks. It allows authenticated users to create tasks with custom properties such as priority due dates and categories. Users can also share tasks monitor progress and manage access for team collaboration. The app supports real-time status updates customizable task filtering and secure user authentication making it ideal for personal productivity and team project management.</p>

<h2>🚀 Demo</h2>

[project-management-client-five.vercel.app](project-management-client-five.vercel.app)

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

- **User Authentication**: Secure user registration and login with JWT-based authentication; only authenticated users can create and manage tasks.

- **Task Creation & Management**: Users can create tasks with priority levels, optional due dates, and categories. Tasks can be edited, assigned to other members, or deleted.

- **Task Sharing & Permissions**: Users can share tasks, providing read-only access to collaborators, and assign tasks to team members with controlled permissions.

- **Real-time Status Updates**: Tasks can be moved across customizable statuses: backlog, to-do, in-progress, and done. Task statuses update in real-time for easy tracking.

- **Analytics Dashboard**: Users can review statistics and analytics on tasks created, status distributions, and team activity.

- **Due Date Color Indicators**: Task cards change color based on the due date, with red for overdue and green for completed tasks, providing visual status cues.

- **Responsive Design**: Responsive UI to ensure a seamless experience across different laptop screen sizes.

- **Toast Notifications**: Real-time feedback and alerts via toast messages for actions like task creation, updates, and deletions.

- **User Settings Management**: Users can update their profile information, including name, email, and password, with secure validation. Changing email or password logs the user out for security.

- **Task Filters**: Custom filters to view tasks due today, this week, or this month, allowing users to prioritize tasks effectively.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository</p>

```
git clone https://github.com/191prajjwal/Project_Management_App.git
```

<p>2. install Frontend dependencies</p>

```
cd Project_Management_Client   npm install
```

<p>3. run</p>

```
npm run dev
```

<p>4. set environment variables</p>

```
VITE_BASE_URL="your backend URL"
```

<p>5. Install Backend Dependencies</p>

```
cd Project_Management_Server
npm install

```

<p>6. Set environment variables </p>

```
PORT = "give a port no. ex: 4000"

MONGODB_URL = "your mongoDB URL"

JWT_SECRET_KEY = "your jwt secret key"

FRONTEND_URL= "your frontend URL"

```

<p>7. run</p>

```
npm start
```

<h2>🍰 Contribution Guidelines:</h2>

Feel free to contribute to this project by creating pull requests. Adhere to the existing code style and best practices.

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   React
*   Node.js
*   Express.js
*   MongoDB
*   JWT
*   javascript
*   Redux
*   React-Router
*   Mongoose
*   REST API

<h2>🛡️ License:</h2>

This project is licensed under the This project is licensed under the MIT License.