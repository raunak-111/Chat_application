# Chat Application

Welcome to the Chat Application repository! This project is designed to facilitate seamless communication and file transfers among friends.

## Features

- Real-time Messaging: Communicate instantly with friends in real-time.
- File Transfers: Conveniently share files with your friends.
- User Authentication: Secure login and registration for users.
- Responsive Design: Optimized for both desktop and mobile devices.

## Technologies Used

- MERN Stack (MongoDB, Express.js, React, Node.js)
- Vite.js: For fast and optimized development.
- Tailwind CSS: For modern and responsive styling.
- Socket.io: For real-time communication.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/raunak-111/Chat_application.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Chat_application
    ```

3. **Install dependencies for both frontend and backend**:
    ```bash
    npm install --prefix client
    npm install --prefix server
    ```

4. **Create a `.env` file in the `server` directory and add your environment variables**:
    ```plaintext
    MONGO_URL=your_mongodb_url
    ORIGIN=your_origin_url
    ```

5. **Run the frontend and backend**:
    - Frontend:
      ```bash
      npm run dev --prefix client
      ```
    - Backend:
      ```bash
      npm run dev --prefix server
      ```

## Usage

1. Open your browser and navigate to `http://localhost:5173`.
2. Register a new account or log in with your existing credentials.
3. Start chatting and sharing files with your friends!

## Contributing

We welcome contributions from the community! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes.
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch.
    ```bash
    git push origin feature/your-feature-name
    ```
5. Open a pull request and describe your changes.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please feel free to [open an issue](https://github.com/raunak-111/Chat_application/issues) or contact the repository owner at raunak-111.

---

Thank you for using the Chat Application! Happy chatting!
