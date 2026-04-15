🎹 **KeyFlow — Type to the Beat**

A piano-tile inspired typing trainer that transforms typing into a musical experience.
 Each keystroke generates sound, adapts to your speed, and evolves into a rhythm-based learning system.
 
🚀 **Features**
🎯 **Core Typing System**
Real-time WPM (Words Per Minute) tracking
Accuracy & streak tracking
Smooth horizontal scrolling text display
Progressive difficulty levels
🎵 Adaptive Music System
🎹 Piano-style tones generated using Web Audio API
🎯 Music adapts based on user WPM
🔄 Tune updates after first 5 words
🎼 Structured melody sequences instead of random sounds

🎮 **Game Mechanics**
Piano-tile inspired visual typing interface
Dynamic tile animations
Real-time feedback (correct / wrong keys)
Floating note effects for interaction

📊 **Analytics & Feedback**

**Live stats:**
WPM
Accuracy
Time
Streak

**Post-session:**
Performance summary
WPM graph (Chart.js)
Persistent progress tracking (localStorage)

📚 **Learning System**
4 Levels:
Beginner
Intermediate
Advanced
Expert
Structured lessons per level
Unlock system based on performance

🧠 **How It Works**
**1. **Typing Engine****
Compares typed input with expected character
Updates:
correctness
streak
stats

**2. **Music Logic****

Initial tune selected based on user level
After 5 words typed:
calculates WPM
switches to appropriate tune range
Notes are played sequentially → forms a melody

**3. Smooth Text Scrolling**

Active character remains in focus
Text shifts dynamically using:
transform: translateX
inertia-based animation

**🛠️ Tech Stack**

HTML5
CSS3 (Custom UI + Animations)
Vanilla JavaScript
Web Audio API (sound generation)
Chart.js (analytics visualization)
LocalStorage (progress persistence)

**▶️ How to Run**

Option 1 (Simple)
Open index.html in browser
Option 2 (Recommended)
Open project in VS Code
Install Live Server
Right-click → Open with Live Server


**🎮 Controls**
Key
Action
Any key
Start typing
Backspace
Correct previous character
Typing
Plays notes + progresses lesson


**📈 Progress Tracking**
Stored locally:
Best WPM
Average WPM
Completed lessons
Session history

**⚠️ Known Limitations**

Audio uses oscillator tones (not real piano samples)
Music is procedural, not full compositions
No backend (data stored locally only)

**🚀 Future Improvements**

🎹 Real piano samples / MIDI integration
🎼 Predefined classical tunes (Für Elise, Canon in D)
🎧 Background music layering
🧠 Adaptive difficulty (AI-based)
📱 Mobile optimization
🌐 User accounts & cloud sync

**💡 Inspiration**

Inspired by:
Monkeytype
Piano Tiles
Rhythm-based learning systems

**👨‍💻 Author**

Built as an experimental project combining:
typing training
music interaction
UI/UX design
**⭐ Final Note**
This project is not just a typing tool —
 it’s an attempt to turn typing into a rhythmic, immersive experience.

