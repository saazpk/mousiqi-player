# 🎵 Music Player App

A beautiful, responsive music player web application built with HTML, CSS (Tailwind), and JavaScript.

## ✨ Features

- **Modern UI Design**: Clean, modern interface with a green nature theme
- **Responsive Layout**: Works perfectly on desktop and mobile devices
- **Interactive Controls**: 
  - Play/Pause functionality
  - Next/Previous track navigation
  - Repeat mode toggle
  - Progress bar with click-to-seek
  - Track selection by clicking on any song
- **Visual Feedback**: 
  - Active track highlighting
  - Play/pause button state changes
  - Progress bar animation
  - Hover effects on controls
- **Track Information**: Displays song title, artist, and album artwork

## 🎶 Included Tracks

The app comes with 10 popular songs:

1. **Ho Hey** - The Lumineers
2. **Viva la Vida** - Coldplay  
3. **Shape of You** - Ed Sheeran
4. **Shake It Off** - Taylor Swift
5. **Rolling in the Deep** - Adele
6. **Believer** - Imagine Dragons
7. **Sugar** - Maroon 5
8. **Sorry** - Justin Bieber
9. **Umbrella** - Rihanna
10. **Hotline Bling** - Drake

## 🚀 How to Use

### Option 1: Web Server (Recommended)
1. Open a terminal in the project directory
2. Run: `python3 -m http.server 8000`
3. Open your browser and go to: `http://localhost:8000/musicplayer.html`

### Option 2: Direct File Access
Simply open `musicplayer.html` in your web browser by double-clicking it.

## 🎮 Controls

- **Play/Pause**: Click the main play button or any track's play button
- **Next Track**: Click the "Next" button or let a track finish
- **Previous Track**: Click the "Back" button  
- **Repeat**: Click the "Repeat" button to toggle repeat mode (button turns green when active)
- **Seek**: Click anywhere on the progress bar to jump to that position
- **Track Selection**: Click on any track in the list to start playing it

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Styling with Tailwind CSS framework
- **JavaScript (ES6+)**: Interactive functionality using modern JS features
- **SVG Icons**: Scalable vector icons for crisp display at any size

### Key JavaScript Features
- Object-oriented design with a `MusicPlayer` class
- Event-driven architecture
- Real-time progress tracking
- Dynamic DOM manipulation
- Responsive design patterns

### File Structure
```
├── musicplayer.html    # Main application file
└── README.md          # This documentation
```

## 🎨 Design Features

- **Color Scheme**: Nature-inspired green theme (#f9fcf8, #54a145, #137000)
- **Typography**: Newsreader and Noto Sans fonts for excellent readability
- **Layout**: Grid-based responsive design that adapts to different screen sizes
- **Animations**: Smooth transitions and hover effects
- **Icons**: Consistent icon system using Phosphor icons

## 🔧 Customization

To add your own tracks, modify the `tracks` array in the JavaScript code:

```javascript
this.tracks = [
  {
    title: "Your Song Title",
    artist: "Artist Name", 
    duration: 240, // duration in seconds
    image: "path/to/album/artwork.jpg"
  },
  // ... more tracks
];
```

## 📱 Browser Compatibility

This music player works on all modern browsers:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 🚧 Note

This is a demo music player with simulated playback. It doesn't actually play audio files but provides a complete interactive experience for UI demonstration purposes. To add real audio playback, you would need to integrate the HTML5 Audio API and include actual audio files.

## 📄 License

This project is open source and available under the MIT License.

---

Enjoy your music! 🎵