# 🎵 Music Player

A modern web-based music player built with **Next.js, React, and TypeScript**, featuring a visual theme inspired by the music<img width="1366" height="720" alt="Music and 2 more pages - Personal - Microsoft​ Edge 21-09-2026 08_50_54" src="https://github.com/user-attachments/assets/aa4e42b9-8304-4bc7-9f99-15ea1497c39f" />
<img width="1366" height="720" alt="Music and 2 more pages - Personal - Microsoft​ Edge 21-09-2026 08_51_11" src="https://github.com/user-attachments/assets/4feb933a-bc4f-4a08-b469-d0db36229598" />
-themed design I came across on a **Zepto delivery bag**.

The design caught my attention and inspired me to turn that visual idea into a functional music player web application.

## ✨ Features

* 🎵 Play and pause music
* ⏭️ Next and previous track controls
* 🔊 Volume control
* 🎶 Multiple songs
* 📀 Music library
* 🎧 Browser-based audio playback
* 📱 Responsive interface
* ⚡ Built with Next.js and TypeScript

## 🎨 Design Inspiration

The visual concept for this project was inspired by a **music-themed Zepto bag design** that I liked.

This project is an independent implementation inspired by that visual concept and is **not affiliated with or endorsed by Zepto**.

## 🛠️ Technologies Used

* **Next.js**
* **React**
* **TypeScript**
* **Tailwind CSS**
* **HTML5 Audio / HTMLMediaElement API**

## 🎧 Audio Implementation

The player uses the browser's built-in HTML audio capabilities.

Audio can be loaded using an `<audio>` element:

```jsx
<audio src="/song.m4a" />
```

JavaScript can then control the audio programmatically through the HTMLMediaElement API:

```javascript
audio.play();
audio.pause();
audio.currentTime = 30;
audio.volume = 0.5;
```

This allows the application to implement custom controls such as play/pause, seeking, volume adjustment, and track navigation.

## 📁 Project Structure

```text
my-app/
├── app/
│   ├── layout.tsx
│   └── page.tsx
├── public/
│   ├── music files
│   └── icon.png
├── package.json
├── package-lock.json
├── next.config.ts
└── README.md
```

## 🚀 Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Go into the project:

```bash
cd my-app
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the application at:

```text
http://localhost:3000
```

## 🎶 Adding Music

Place supported audio files inside:

```text
public/
```

Then reference them from the application:

```text
/song.m4a
```

## 📸 Screenshots
<img width="1366" height="720" alt="Music and 2 more pages - Personal - Microsoft​ Edge 21-09-2026 08_50_54" src="https://github.com/user-attachments/assets/c2a1b3e6-e788-42d3-a22c-032933487c0b" />

<img width="1366" height="720" alt="Music and 2 more pages - Personal - Microsoft​ Edge 21-09-2026 08_51_11" src="https://github.com/user-attachments/assets/dcc7af54-b797-422b-aa1f-05e0f86a7923" />


## 📚 What I Learned

While building this project, I practiced:

* Next.js application structure
* React components and state management
* TypeScript
* Tailwind CSS
* Audio playback using the browser's HTML5 audio capabilities
* Handling local audio files
* Building custom music-player controls
* Git and GitLab project management

## 👨‍💻 Author

**Deepesh Sharma**

A personal web development project built for learning and experimentation.
