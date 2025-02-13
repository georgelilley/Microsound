🎛 Microsound – The Audio Game

---

📌 Disclaimer

This is a legacy project created during my university studies. The code may not fully align with best practices, but I believe sharing it highlights my progress. Since then, I’ve focused on cleaner, more maintainable coding approaches.

---

🎮 Project Overview

"Microsound – The Audio Game" is an interactive, web-based generative audio game built using JavaScript and p5.js. It explores concepts from Curtis Roads' Microsound (2004), turning sound particles (grains) into playable game objects. Users can:

-  🎙️ Record audio, which is fragmented into microsound grains (10–100ms).
-  🖱️ Spawn particles into the game space by clicking.
-  💥 Generate sound collisions as particles interact.
-  🪐 Apply gravity and forces, making particles orbit and collide.

---

💡 Core Concepts

-  Microsound: Inspired by Curtis Roads, exploring sound at the granular level (10–100ms).
-  Non-linear Media: Interactive, every gameplay is unique.
-  Generative Systems: Particles behave randomly within physical constraints.
-  Audio Game Mechanics: Collisions trigger sound events, turning gameplay into a musical composition.

---

🛠️ How It Works

📊 System Design

-  Built with JavaScript and the p5.js library.
-  Uses object-oriented programming (OOP) with class-based particle objects (Mover class).
-  Each particle tracks:
    * Position, Velocity, Acceleration (via p5.Vector)
    * Audio grain (10–100ms) from user-recorded input.


🎮 Game Mechanics

-   Recording: Users record their voice or any sound, which is sliced into grains.
-   Spawning Particles: Clicking on the canvas creates particles containing these grains.
-   Gravity Simulation: Particles are drawn towards the center with a vector-based force.
-   Sound-on-Collision: When two particles collide, they play back their grains, forming unique generative soundscapes.
  

🧩 Interactive Elements

-   Variable Grain Length: Users set the grain size (10–100ms).
-   Particle Projection: Users can launch particles in specific directions using their mouse.
-   Dynamic Sound Collisions: Each collision generates a sound event from the recorded grains.
  
---

🎨 Creative Context & Inspiration

🎶 Audio & Game Intersection

-   Inspired by Curtis Roads’ Microsound (2004): The concept that all sound is made of tiny particles.
-   Influenced by Audio Games like "Blob Opera" (Google Arts) and "Plink" (Dinahmoe): Exploring non-linear, playful audio composition.
-   Related to Generative Simulations: Echoing the physics-driven generative music from projects like “Caasi” by Filipczak.

🧠 Generativity & Creativity

-   Generativity in Games: Inspired by theories of player engagement through randomness (Lee & Jeon, 2017).
-   Non-linear Interactivity: Builds on ideas from Smuts (2009) about interactive feedback loops between player and system.
-   Materialist Composition: Following Filipczak (2017), using physics simulations to inspire new forms of generative music.

---

🎯 Research Questions Explored

📌 1. Educational Value of Web-Based Audio Games

Can interactive media help users engage with complex musical concepts?

-   Microsound – The Audio Game demonstrates granular synthesis concepts through playful interaction.
-   It aligns with Cairncross and Mannion (2010), who argue interactive simulations promote deeper learning.

📌 2. Exploring New Modes of Musical Expression

Can audio games enable creativity beyond traditional instruments?

-   The project embraces bottom-up composition: Simple rules lead to complex, emergent soundscapes.
-   Supports inclusivity by enabling users to create music without technical skills, echoing Mishra (2015) on accessible music interfaces.

---

🚀 Future Development Plans

🔧 Multiplayer Mode: Allowing players to create collaborative generative compositions.

🎛 More Particle Behaviors: Adding repulsion, magnetism, or environmental effects.

🎨 Visual Upgrades: Enhanced particle trails and interactive graphics.

🎚 Improved Audio Engine: Reducing clicks/buzzes on collisions with advanced smoothing.

---

📝 Evaluation & Reflection
✅ Project Strengths:

-   Highly Interactive & Generative: Every session produces a unique soundscape.
-   Educational Potential: Effective in teaching granular synthesis through play.
-   Creative Exploration: Empowers users to compose music without formal training.

🛑 Areas for Improvement:

-   Audio Quality: Occasional clicks on particle collisions.
-   Optimization: Performance issues with many particles on screen.
-   UI Enhancements: Clearer controls and in-game feedback.

---

🛠️ Built With

-   Language: JavaScript
-   Creative Coding Library: p5.js
-   Audio API: Web Audio API

---

📂 Repository Structure  

├── Commentary.docx          # Project commentary document  
├── Project Journal.docx     # Development journal and notes  
├── README.md                # Project documentation  
├── index.html               # Main HTML file  
├── p5.js                    # p5.js library for creative coding  
├── p5.sound.min.js          # p5.js sound library for audio handling  
├── sketch.js                # Main game logic (p5.js)  
└── style.css                # Styles for the game interface  

---

🔗 Useful Links

[🎮 Play the Game (p5.js Web Editor): Microsound – The Audio Game](https://users.sussex.ac.uk/~gsl23/Microsound_-_The_Audio_Game_Final/)
[Watch a Demo](https://youtu.be/FxQiP6Kh7Rc)
📚 p5.js Library: p5js.org
