**Project:** Connectify

📖 **Description**
---------------

Connectify is a real-time chat application built using React, Redux, and Tailwind CSS. This project aims to provide a user-friendly interface for users to communicate with each other in real-time. The application includes features such as user authentication, user management, and real-time messaging.

Connectify is designed to be scalable, secure, and easy to maintain. The application uses a modular architecture, allowing developers to easily add or remove features as needed. The frontend is built using React, with Redux used for state management. The backend is currently not implemented, but can be integrated using a technology of choice.

✨ **Features**
-------------

1. **Real-time Messaging**: Users can send and receive messages in real-time, with features such as message typing indicators and read receipts.
2. **User Authentication**: Users can create an account and log in to access their dashboard and send/receive messages.
3. **User Management**: Users can manage their profiles, including updating their profile picture and bio.
4. **Real-time User Updates**: The application updates in real-time when a user is online or offline.
5. **Message Persistence**: Messages are persisted even when the user closes the application or goes offline.
6. **Error Handling**: The application includes robust error handling, with error messages displayed in a user-friendly manner.
7. **Responsive Design**: The application is designed to be responsive, working seamlessly on desktop, tablet, and mobile devices.
8. **RTL Support**: The application includes support for right-to-left languages.

🧰 **Tech Stack**
----------------

| **Technology** | **Version** |
| --- | --- |
| React | 17.0.2 |
| Redux | 4.2.0 |
| Tailwind CSS | 3.1.8 |
| Vite | 2.9.10 |

📁 **Project Structure**
----------------------

* `src/`: Contains the frontend code, including the React components and Redux store.
* `public/`: Contains static assets, such as images and fonts.
* `postcss.config.js`: Configures PostCSS for Tailwind CSS.
* `tailwind.config.js`: Configures Tailwind CSS.
* `userSlice.js` and `messageSlice.js`: Define the Redux slices for user and message management.
* `store.js`: Configures the Redux store.
* `index.css`: Global CSS styles.
* `vite.config.js`: Configures Vite for development and build.
* `package.json`: Contains the project dependencies and scripts.
* `eslint.config.js`: Configures ESLint for code linting.

⚙️ **How to Run**
---------------

### Setup

1. Clone the repository: `git clone https://github.com/your-username/chatly.git`
2. Install the dependencies: `npm install` or `yarn install`
3. Start the development server: `npm run dev` or `yarn dev`

### Environment

* Node.js: 16.17.0 or later
* npm or yarn: 8.19.2 or later
* React: 17.0.2 or later
* Redux: 4.2.0 or later

### Build

1. Run `npm run build` or `yarn build` to build the application
2. Run `npm run start` or `yarn start` to start the application

### Deploy

1. Run `npm run deploy` or `yarn deploy` to deploy the application

🧪 **Testing Instructions**
-------------------------

1. Run `npm run test` or `yarn test` to run the tests
2. Use a testing library such as Jest or Cypress to write and run tests


👤 **Author**
------------

Ujjwal Singh

📝 **License**
---------

MIT License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
