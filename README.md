# Task Management Application

## About
The Task Management Application is a web-based tool that allows users to efficiently manage their tasks with a drag-and-drop interface. Users can add, edit, delete, and reorder tasks, ensuring seamless organization and productivity. The application features Firebase Authentication, a real-time database using MongoDB, and a responsive UI built with Vite.js and React.

## Live Demo
[Live Application](#) (Update with actual link after deployment)

## Features
- **User Authentication:** Google Sign-in using Firebase Authentication.
- **Task Management:** Add, edit, delete, and reorder tasks.
- **Drag-and-Drop Functionality:** Move tasks between categories (To-Do, In Progress, Done).
- **Real-Time Syncing:** Instant database updates using MongoDB Change Streams/WebSockets.
- **Responsive UI:** Optimized for both desktop and mobile devices.
- **Dark Mode:** Optional theme toggle for better user experience.
- **Due Date Indicators:** Highlight overdue tasks in red.
- **Activity Log:** Track task status changes.

## Tech Stack
### Frontend:
- Vite.js + React
- Firebase Authentication
- react-beautiful-dnd / dnd-kit (for drag-and-drop)
- Tailwind CSS (for styling)
- Framer Motion (for animations)

### Backend:
- Express.js
- MongoDB (with Change Streams for real-time updates)
- WebSockets (for real-time communication)
- Firebase Authentication Middleware

## Installation
### Prerequisites:
- Node.js and npm/yarn installed
- MongoDB (Atlas or local instance)
- Firebase Project with Authentication enabled

### Steps:
#### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/task-management-app.git
cd task-management-app
```
#### 2. Setup Environment Variables
Create a `.env` file in both the `frontend` and `backend` folders and add necessary credentials.

#### 3. Install Dependencies
```sh
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

#### 4. Start the Application
```sh
# Start backend server
cd backend
npm start

# Start frontend
cd ../frontend
npm run dev
```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST   | /tasks  | Create a new task |
| GET    | /tasks  | Retrieve all tasks |
| PUT    | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## Folder Structure
```
/task-management-app
  ├── frontend  # React Frontend (Vite.js)
  ├── backend   # Express.js Backend
  ├── README.md # Documentation
```

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any queries, reach out via [your email] or open an issue on GitHub.

