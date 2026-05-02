# Campus Notifications Platform

This project is a React application designed to serve as a campus notifications platform. It allows users to view, filter, and manage notifications effectively.

## Features

- Display all notifications and priority notifications.
- Filter notifications by type.
- Distinguish between new and viewed notifications.
- Responsive design for optimal viewing on various devices.

## Project Structure

```
campus-notifications-platform
├── public
│   ├── index.html          # Main HTML document
│   └── favicon.ico         # Application favicon
├── src
│   ├── components          # Reusable components
│   │   ├── NotificationCard.jsx
│   │   ├── NotificationList.jsx
│   │   └── FilterBar.jsx
│   ├── pages               # Application pages
│   │   ├── AllNotifications.jsx
│   │   └── PriorityNotifications.jsx
│   ├── styles              # CSS styles
│   │   └── App.css
│   ├── utils               # Utility functions
│   │   └── notificationHelpers.js
│   ├── App.jsx             # Main application component
│   ├── index.jsx           # Entry point for the React application
│   └── assets              # Static assets
├── package.json            # npm configuration file
├── .gitignore              # Git ignore file
├── README.md               # Project documentation
└── vite.config.js          # Vite configuration file
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd campus-notifications-platform
   ```
3. Install dependencies:
   ```
   npm install
   ```

## Usage

To start the development server, run:
```
npm run dev
```

Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.