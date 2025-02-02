# Social Dev

A full-stack MERN (MongoDB, Express, React, Node.js) application that serves as a social network platform for developers. It has authentication, user profiles, and a forum for posting and commenting.

## Features

### Comprehensive Developer Profiles

Users can create detailed profiles showcasing their skills, experience, and education.

### Interactive Forum

The application includes a forum where users can create posts and comment on posts made by others.

### GitHub API Integration

Integrates with the GitHub API, allowing users to seamlessly connect their GitHub accounts and display their repositories on their profiles.

## Technologies Used

- **MongoDB**: A NoSQL database for storing user data, posts, comments, and other application data.
- **Express.js**: A Node.js web application framework for building the server-side API.
- **React.js**: A JavaScript library for building the user interface and front-end components.
- **Node.js**: A JavaScript runtime environment for executing server-side code.
- **JWT (JSON Web Tokens)**: An open standard for securely transmitting information between parties as a JSON object.
- **GitHub API**: Integration with the GitHub API to fetch user repositories and display them on user profiles.

## Set up

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/social-dev.git`
2. Navigate to the project directory: `cd social-dev`
3. Install server dependencies: `npm install`
4. Install client dependencies: `cd client && npm install`
5. Create a `default.json` file in the `config` folder with your MongoDB URI, JWT secret, and GitHub token.
6. Run the application in development mode: `npm run dev`
