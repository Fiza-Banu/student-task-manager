# student-task-manager
student-task-mern/
├── backend/
│   ├── config/
│   │   └── db.js              # MongoDB connection
│   ├── controllers/
│   │   ├── authController.js  # Register & Login logic
│   │   └── taskController.js  # CRUD task logic
│   ├── middleware/
│   │   └── authMiddleware.js  # JWT protect middleware
│   ├── models/
│   │   ├── User.js            # User schema
│   │   └── Task.js            # Task schema
│   ├── routes/
│   │   ├── authRoutes.js      # /api/auth routes
│   │   └── taskRoutes.js      # /api/tasks routes
│   ├── .env                   # Environment variables
│   ├── package.json
│   └── server.js              # Express entry point
│
└── frontend/
    ├── src/
    │   ├── api/
    │   │   ├── auth.js        # Auth API calls
    │   │   └── tasks.js       # Tasks API calls
    │   ├── components/
    │   │   ├── AIAssistant.jsx
    │   │   ├── DailyStudyPlanner.jsx
    │   │   ├── NotificationsPanel.jsx
    │   │   └── SidebarLayout.jsx
    │   ├── pages/
    │   │   ├── Login.jsx
    │   │   ├── Register.jsx
    │   │   ├── Dashboard.jsx
    │   │   ├── Tasks.jsx
    │   │   ├── AddTask.jsx
    │   │   ├── Progress.jsx
    │   │   ├── Notifications.jsx
    │   │   └── SmartNotes.jsx
    │   ├── services/
    │   │   └── api.js         # Axios instance with interceptors
    │   ├── App.jsx
    │   └── main.jsx
    ├── index.html
    ├── package.json
    ├── tailwind.config.js
    └── vite.config.js
```
