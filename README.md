# Naruto Pong Game
## Project Description
This project presents a Unity-based implementation of the classic Pong game featuring Naruto-themed characters and assets. The application was developed as part of the Game Programming course, incorporating traditional Pong mechanics with custom Naruto-inspired graphics, sound effects, and character themes. Players control paddles representing Sasuke and Naruto in competitive gameplay.

## Features
- Classic Pong gameplay mechanics with Naruto theme
- Two-player competitive mode with keyboard controls
- Physics-based ball movement with collision detection
- Real-time score tracking system
- Audio integration with sound effects and background music
- Game completion screen with winner announcement
- Custom Naruto-themed UI and visual assets
- Paddle movement constraints and boundary detection

## Technologies Used
- **Game Engine:** Unity
- **Programming Language:** C#
- **Physics System:** Unity 2D Physics (Rigidbody2D, Collider2D)
- **Audio System:** Unity AudioSource components
- **UI Framework:** Unity Canvas and UI Text
- **Asset Creation:** CorelDRAW for custom graphics
- **Input Management:** Unity Input Manager

## How the Program Works
### Core Game Components
1. **Game Area Setup:**
   - Boundary walls (top, bottom, left, right) using scaled cube objects
   - Center divider line for visual game area separation
   - Collision detection system for ball interactions

2. **Paddle System:**
   - Left paddle (Sasuke) controlled by WASD keys
   - Right paddle (Naruto) controlled by arrow keys and IJKL keys
   - Movement constraints within defined boundaries
   - Horizontal and vertical movement capabilities

3. **Ball Physics:**
   - Rigidbody2D component for realistic physics simulation
   - Circle Collider 2D for collision detection
   - Custom Physics Material 2D with zero friction and full bounce
   - Dynamic force application and velocity management

### Core Scripts
1. **PaddleController Script:**
   - Handles player input for paddle movement
   - Implements boundary checking to prevent paddles from moving outside game area
   - Configurable speed and movement axis parameters
   - Real-time position updates based on input

2. **BallController Script:**
   - Manages ball physics and collision responses
   - Score tracking and update system
   - Audio playback for different collision events
   - Game state management and winner determination
   - Ball reset functionality after scoring

3. **UI Management:**
   - Real-time score display for both players
   - Game completion panel with winner announcement
   - Custom font integration for Naruto theme
   - Responsive UI scaling for different screen sizes

## Game Mechanics
1. **Scoring System:**
   - Points awarded when ball reaches opponent's boundary
   - First player to reach 10 points wins the game
   - Score persistence throughout gameplay session

2. **Ball Behavior:**
   - Initial force application in random direction
   - Velocity modification based on paddle collision angle
   - Continuous rotation animation during gameplay
   - Physics-based bouncing off walls and paddles

3. **Audio Integration:**
   - Different sound effects for wall collisions
   - Distinct audio cues for each paddle hit
   - Background music and ambient sound management

## Control Scheme
### Player 1 (Sasuke - Left Paddle):
- **W/S:** Vertical movement (up/down)
- **A/D:** Horizontal movement (left/right)

### Player 2 (Naruto - Right Paddle):
- **Arrow Keys:** Vertical movement (up/down)
- **I/K:** Alternative vertical movement
- **J/L:** Horizontal movement (left/right)

## Installation and Usage
1. **Setup:**
   - Open the project in Unity Editor
   - Ensure all assets and scripts are properly imported
   - Configure Input Manager settings for player controls
   - Verify Physics Material 2D settings for ball behavior

2. **Asset Requirements:**
   - Background images for game area and menu
   - Naruto-themed paddle sprites
   - Ball sprite with appropriate dimensions
   - Custom UI fonts and button graphics
   - Audio files for sound effects and background music

3. **Usage Instructions:**
   - Launch the game from the main scene
   - Player 1 uses WASD keys for paddle control
   - Player 2 uses arrow keys and IJKL for paddle control
   - First player to score 10 points wins the match
   - Use menu buttons to restart or return to main menu

## Game Architecture
### Physics Components
- **Rigidbody2D:** Applied to ball for physics simulation
- **Collider2D:** Collision detection for all game objects
- **Physics Material 2D:** Custom material for ball bouncing behavior

### Input System
- **Input Manager:** Custom axis configuration for dual-player controls
- **Real-time Input Processing:** Continuous input checking in Update methods
- **Boundary Validation:** Movement constraints for paddle positioning

## Development Team
- **Akasha Bin Ali** - 4.33.22.0.01
- **Aufa Bima Ngahada** - 4.33.22.0.03
- **Bayu Tri Prayitno** - 4.33.22.0.04
- **Ilham Muhammad Arif** - 4.33.22.0.10
- **Maulana Bintang C.M** - 4.33.22.0.15

**Course:** Game Programming  
**Department:** Electrical Engineering  
**Institution:** Politeknik Negeri Semarang  
**Year:** 2024
