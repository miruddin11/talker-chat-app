# Talker

**Talker** is a real-time chat application designed for seamless communication with a feature-rich interface. Built using modern web technologies, Talker supports real-time messaging, customizable themes, and an intuitive user experience.

## Features

- **Real-Time Communication**: Instant messaging powered by Socket.io.
- **Unicasting**: Send private messages to specific users.
- **Past Chat Viewing**: Access previous conversations for continuity.
- **Auto-Scroll**: Automatic scrolling to the latest message.
- **Customizable Themes**: Choose from 32 unique themes designed with DaisyUI.
- **Interactive Notifications**: Real-time updates with react-toast.
- **Media Storage**: Integrated Cloudinary for efficient media handling.

## Technologies Used

- **Frontend**: React.js, DaisyUI, Zustand, lucide-react
- **Backend**: Node.js, Express.js, Socket.io
- **Database**: MongoDB
- **Media Integration**: Cloudinary
- **Deployment**: Render

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/miruddin11/talker-chat-app
   cd talker-chat-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     MONGO_URI=<your-mongodb-connection-string>
     CLOUDINARY_URL=<your-cloudinary-url>
     PORT=5000
     ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open the app in your browser:
   ```
   http://localhost:5001
   ```

## How It Works

1. **Real-Time Interaction**: Messages are sent and received instantly using Socket.io.
2. **Unicasting**: Direct messages are enabled by targeting specific user sockets.
3. **Theming**: DaisyUI themes provide a customizable and modern interface.
4. **State Management**: Zustand efficiently handles application states.

## Deployment

Talker is deployed on **Render** and can be accessed via the live demo link below:

[Live Demo](https://talker-chat-app.onrender.com/login)


## Contribution

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a pull request.

## Contact

For any inquiries or feedback, feel free to contact:

- **Author**: Mir Tariquddin
- **GitHub**: [miruddin11](https://github.com/miruddin11)
- **Email**: [mirtariquddin666@gmail.com]
