# 🏏 Cricket Live Stream Web Application

Welcome to the **Cricket Live Stream Web Application**! 🎉 This project is a web-based platform where users can watch live cricket matches and chat with others in real time. The application supports responsive design, Picture-in-Picture (PiP) mode, and fullscreen video playback.

![Cricket Live Stream Screenshot](https://github.com/user-attachments/assets/bde17b37-f665-4143-b793-a700c2308056)

## ✨ Features

- **🎥 Live Cricket Stream**: Watch live cricket matches with a fully embedded video player using an iframe.
- **🖼️ Picture-in-Picture (PiP)**: Automatically switches to PiP mode when the tab is changed or minimized.
- **📺 Fullscreen Mode**: Double-click or click the fullscreen button to view the stream in fullscreen mode.
- **💬 Responsive Chat**: Real-time chat displayed alongside the video player with timestamped messages.
- **🏏 Cricket-Themed Design**: Styled with cricket-inspired colors and animations for an immersive experience.
- **📱 Mobile Responsive**: The layout adjusts smoothly on mobile devices for optimal viewing.

## 🚀 Demo

<div align="center">
  
**[🏏 Click here to view the Live Demo 🏏](https://cricketlive-henna.vercel.app)**

</div>
## 🛠️ Technologies Used

- **HTML5**: Structuring the content of the web page.
- **CSS3**: Styling the page, making it responsive and aesthetically pleasing.
- **JavaScript**: Adding interactive features such as PiP mode, fullscreen functionality, and chat logic.
- **Fonts**: Using the `Orbitron` font from Google Fonts for a unique look.
- **iframe**: Embedding the live stream video player securely.

## 📥 Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mRcOol7/live_stream_cricket.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd live_stream_cricket
   ```

3. **Open the project in a browser:**
   - You can simply open the `index.html` file in your preferred browser:
     ```bash
     open index.html
     ```
   - Or serve the file using a local HTTP server for development:
     ```bash
     python3 -m http.server
     ```
     Then, open `localhost:8000` in your web browser.

## 🎮 Usage

### 🏏 Watching Live Cricket:
- The default live stream starts automatically when the page loads in the embedded iframe.
- You can switch between different "pitchers" (streams) using the buttons at the top of the page.

### 💬 Chatting:
- Type your message in the chat input and press Enter or click the "Send" button to post it.
- Messages are displayed with timestamps, and the chat window scrolls to the most recent message.

### 🖥️ Full-Screen Mode:
- Double-click on the video iframe or press the fullscreen button to enter/exit full-screen mode.

### 🖼️ Picture-in-Picture Mode:
- PiP mode is automatically activated when you minimize the browser window or switch tabs.
- You can also manually enable PiP by right-clicking on the video player iframe (if your browser supports it).

## 🔒 Security Note

The use of an iframe for the video player helps ensure that the streaming content is securely embedded and isolated from the rest of the application.
Enjoy the cricket! 🏏🎉
