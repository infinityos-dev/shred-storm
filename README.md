# Shred Storm

### **Game Overview**

**Genre:** Rhythm, Music, Action
**Platform(s):** PC, Console, Mobile
**Target Audience:** Teens, Adults, Music Lovers
**Game Engine:** Godot using GDScript and maybe Rust

---

### **Game Concept**

This game allows players to perform music by pressing the correct notes at the right time, using instruments similar to Guitar Hero. Players will face a variety of songs across multiple genres, with increasing difficulty. The game is focused on rhythm, coordination, and accuracy. The core mechanic is based on matching the notes to the beat of the song, which plays through the game.

---

### **Gameplay Mechanics**

**1. Core Gameplay Loop:**
   - **Player Input:** Players use a guitar controller or keyboard to hit notes that scroll down the screen.
   - **Note Detection:** Notes appear on-screen in time with the music and move toward a target area. The player must press the corresponding button(s) when the note reaches the target area.
   - **Scoring:** Players earn points based on how accurately they hit the notes (perfect, good, missed).
   - **Combo System:** Consecutive perfect hits build combo points, leading to higher scores and rewards.
   - **Song Progression:** The difficulty of the songs increases as the player progresses, with more complex note patterns, faster speeds, and multiple instruments in play (e.g., drums, vocals).
   
**2. Note Types:**
   - **Single Note:** A single note that corresponds to one input button (e.g., pressing one key or fret).
   - **Chord Notes:** A combination of multiple inputs that the player must hit simultaneously (similar to chords in guitar songs).
   - **Hold Notes:** A note where the player must hold the input for a certain duration.
   - **Slide Notes:** A note where players must slide between two inputs.
   
**3. Player Actions:**
   - **Hit/Play Notes:** Pressing the correct button at the right time.
   - **Miss Notes:** Missing notes will decrease the player’s score and health.
   - **Special Abilities (Optional):** Players can activate special abilities (e.g., score multipliers or shields) at certain points.

---

### **Game Modes**

**1. Career Mode:**  
   - Players progress through a series of levels, unlocking new songs and venues.
   - As the player advances, they encounter more challenging songs and gameplay mechanics.
   
**2. Free Play Mode:**  
   - Players can select any unlocked song and play at their own pace without the pressure of progression.
   
**3. Multiplayer Mode:**  
   - **Competitive:** Players can face off in a head-to-head battle to see who performs the song better.
   - **Cooperative:** Two players can play together, sharing the performance duties (e.g., one player plays guitar, the other plays drums).

**4. Practice Mode:**  
   - Players can practice individual songs or specific sections of a song without worrying about scores or penalties.

---

### **Visual and Audio Design**

**1. Visual Style:**
   - **Graphics:** Colorful, dynamic visuals with a stage and crowd environment. Backgrounds change based on the song genre and setting.
   - **HUD:** Display player score, health bar, combo, and notes in a clear and minimalistic way.
   - **Animations:** Dynamic note animations, feedback effects (e.g., glowing notes, sparks, explosions when notes are hit perfectly), and background animations that match the rhythm of the music.

**2. Audio Design:**
   - **Soundtracks:** A diverse selection of tracks from various genres (rock, pop, metal, etc.). Each song has multiple difficulty levels.
   - **Sound Effects:** Feedback sounds for different note hits (perfect, good, miss) and combo streaks.
   - **Voiceovers:** Optional voiceovers that add personality to the characters and provide guidance during gameplay.

---

### **Levels and Difficulty**

**1. Song Difficulty:**
   - **Easy:** Simple patterns with slower tempos.
   - **Medium:** More complex patterns with increased speed.
   - **Hard:** Fast tempo, more note types (chords, slides, holds).
   - **Expert:** Very fast tempo with complex note patterns and multiple simultaneous note streams.

**2. Unlockable Content:**
   - **Songs:** Unlock new tracks by completing songs or progressing through career mode.
   - **Instruments:** Unlock new instruments (e.g., guitars, basses, keyboards) with unique visuals and abilities.
   - **Stages:** Unlock new stages for performances as the player advances.

---

### **Monetization (if applicable)**

**1. In-App Purchases (if applicable):**
   - **Song Packs:** Purchase additional songs or albums.
   - **Cosmetics:** Unlockable or purchasable costumes, guitars, and character skins.
   - **Power-ups:** In-game boosts, score multipliers, etc.

**2. Ads (if applicable):**
   - Ads that players can watch for rewards like extra lives, special abilities, or unlockable content.

---

### **User Interface (UI)**

**1. Main Menu:**
   - Options for Career Mode, Free Play, Multiplayer, Practice, Settings, etc.

**2. Song Selection Screen:**
   - Displays unlocked songs with difficulty levels, along with their progression (unlocked, in-progress, completed).

**3. Gameplay HUD:**
   - **Score:** Shows current score, combo streak, and multiplier.
   - **Health Bar:** Displays player health. Missing too many notes causes a game over.
   - **Notes:** Visual representation of the scrolling notes with clear targets.

---

### **Technical Requirements**

**1. Platform Compatibility:**  
   - Specify the platforms the game will run on (e.g., Windows, PS4/PS5, Xbox, Nintendo Switch, Mobile).
   
**2. Controls:**
   - **Guitar Controller Support:** Similar to Guitar Hero controllers, including compatibility with both original and custom controllers.
   - **Keyboard/Mobile Touch Controls:** For non-guitar controller players.
   - **Customizable Key Mapping:** Allow players to customize their control scheme.

**3. Performance:**
   - Ensure smooth performance at 30-60 FPS, depending on the platform.
   - Graphics optimization for various hardware specifications.

---

### **Development Team and Roles**

- **Game Designer(s):** Create and iterate on game mechanics, levels, and balance.
- **Programmers:** Develop the core systems (input recognition, note generation, AI).
- **Artists/Animators:** Design characters, environments, notes, and animations.
- **Audio Designers:** Implement music tracks, sound effects, and voiceovers.
- **Quality Assurance (QA):** Ensure bug-free gameplay and smooth experience.
- **Project Manager:** Oversee the development process, timelines, and task management.
- 
