# Social Dev

Social Dev is a full-stack MERN (MongoDB, Express, React, Node.js) application that serves as a social network platform for developers. It features authentication, user profiles, and a forum for posting and commenting.

## Unique Features

### Comprehensive Developer Profiles

Users can create detailed profiles showcasing their skills, experience, and education. Profiles also display the user's latest GitHub repositories, providing a centralized hub for showcasing their coding abilities and projects.

### Interactive Forum

The application includes a forum where users can create posts, comment on posts made by others, and engage in discussions related to various topics in the developer community.

### GitHub API Integration

Social Dev integrates with the GitHub API, allowing users to seamlessly connect their GitHub accounts and display their repositories on their profiles. This feature provides a direct link between users' coding activities and their presence on the platform.

### Robust Authentication

The application implements a secure authentication system using JSON Web Tokens (JWT), ensuring that only authenticated users can access protected routes and perform specific actions.

## Technologies Used

- **MongoDB**: A NoSQL database for storing user data, posts, comments, and other application data.
- **Express.js**: A Node.js web application framework for building the server-side API.
- **React.js**: A JavaScript library for building the user interface and front-end components.
- **Node.js**: A JavaScript runtime environment for executing server-side code.
- **Redux**: A predictable state container for managing application state in React.
- **JWT (JSON Web Tokens)**: An open standard for securely transmitting information between parties as a JSON object.
- **GitHub API**: Integration with the GitHub API to fetch user repositories and display them on user profiles.

## Getting Started

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/social-dev.git`
2. Navigate to the project directory: `cd social-dev`
3. Install server dependencies: `npm install`
4. Install client dependencies: `cd client && npm install`
5. Create a `default.json` file in the `config` folder with your MongoDB URI, JWT secret, and GitHub token.
6. Run the application in development mode: `npm run dev`

The application will be available at `http://localhost:3000`.

## Deployment

To deploy the application to a production environment, follow these steps:

1. Build the React app: `cd client && npm run build`
2. Return to the project root: `cd ..`
3. Start the server in production mode: `NODE_ENV=production node server.js`
