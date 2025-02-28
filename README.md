# Chess Clone ♟️

Welcome to **Chess Clone**, a web-based chess game inspired by **Chess.com**. Play real-time multiplayer games, challenge our super-smart AI bot, and enjoy a seamless chess experience all built with JavaScript! 🎮

---

## Features 🚀

- **Multiplayer Mode**: Play against your friends or random opponents in real-time. 🧑‍🤝‍🧑
- **Single-Player Mode**: Challenge a highly intelligent AI bot for a fun solo experience. 🤖
- **Smart AI**: Powered by a strong AI engine, the bot adapts to your playstyle and offers a challenging experience for all levels. 🧠
- **Real-Time Gameplay**: WebSockets provide smooth and responsive multiplayer interactions. ⚡
- **Interactive Board**: React.js frontend offers a modern, interactive UI for an immersive experience along with D&D functionality. 🖥️
- **Chess Rules**: Fully implemented using the chess.js library, ensuring all moves and game mechanics follow the correct rules. 📜

---

## Technologies Used 🛠️

- **Frontend**: 
  - **React.js** for building the user interface and handling state management.
- **Backend**: 
  - **Node.js** for the backend server.
  - **WebSockets** for real-time communication between players.
- **Database**: 
  - **MongoDB** for storing user data, game history, and other related data.
- **Chess Logic**: 
  - **chess.js** library to manage game rules and move validation.
- **AI**: 
  - Smart AI bot integrated for single-player games. 🧑‍💻

---

## Getting Started 🏁

To run the project locally on your machine, follow these steps:

### Prerequisites 📦

Make sure you have the following installed:
- **Node.js** (version 14 or higher)
- **MongoDB** (or a MongoDB cloud instance)

### Steps to Run Locally 💻

1. **Clone the repository**:

    ```bash
    git clone https://github.com/samarth-agrawal-dev/chess-app.git
    cd chess-project
    ```

2. **Install dependencies**:

    For the backend (Node.js server):

    ```bash
    cd backend
    npm install
    ```

    For the frontend (React app):

    ```bash
    cd frontend
    npm install
    ```

3. **Set up the database**:

    If you're using a local MongoDB instance, ensure it's running. Otherwise, you can use MongoDB Atlas for a cloud database connection.

    Download PGN Games from [Lichess Database](https://database.lichess.org/).

    #### Change seeds.js file :

    ```bash
    const filePath = "filePathForChessPgn"; # line 12
    ```
    Enter the path to the PGN games file. Example : 
    ```bash
    const filePath = "C:/downloads/lichess_2013-01.pgn"; # line 12
    ```
    #### Run seeds.js file :

    ```bash
    cd backend/db 
    node seeds.js  # This will take about 5-6 hours to execute.
    ```


4. **Start the backend server**:


    From the `backend` directory, run:

    ```bash
    nodemon index.js  # This starts the backend server with nodemon
    ```

5. **Start the frontend app**:

    From the `frontend` directory, run:

    ```bash
    npm run dev  # This starts the frontend with React
    ```

6. **Open the game in your browser**:

    Go to `http://localhost:5173` to start playing! 🎮

---

## How to Play 🏆

1. **Multiplayer Mode**:
   - 1. **Click on "Play Online"** to start a game with random players or friends. 
   - 2. **Start playing in real-time** with your opponent.

2. **Single-Player Mode**:
   - Choose the "Play with AI" option to challenge the smart AI bot.
   - The bot adapts to your playing style and difficulty levels, providing a challenging and fun experience.

3. **Game Controls**:
   - Click and drag to move your pieces.
   - The game automatically validates moves based on **chess.js** rules.
   - The AI will take its turn after you.

---

## Future Features 🚧

- 🗣️ **Chat functionality** for communication between players.
- 📊 **Game analysis** and move suggestions to help you improve.
- ⚙️ **Tournaments** with a ranking system for competitive play.
- 🎮 **Customizable game boards** and themes.
- 🔐 **Authentication**: Implement user registration and login with JWT authentication for a secure and personalized experience. Users will be able to save their game history and manage their profile.

---

## Contributing 🤝

Contributions are welcome! If you want to add new features, fix bugs, or improve the code, feel free to open an issue or submit a pull request. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

---


## Acknowledgements 🙏

- **chess.js**: A powerful library for managing chess logic.
- **React.js**: A great library for building interactive UIs.
- **MongoDB**: For storing game data and user information.
- **Node.js**: For backend server functionality.
- **WebSockets**: For real-time multiplayer experience.

---

## Contact 📬

If you have any questions, feel free to contact me at **[deepak95.db@gmail.com](mailto:deepak95.db@gmail.com)**. 🌟

---

Thanks for checking out this chess.com clone! We hope you enjoy playing and developing this game as much as I enjoyed building it! 🎉
