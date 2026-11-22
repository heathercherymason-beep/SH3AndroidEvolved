# Project Plan



## Project Brief



## Implementation Steps

### 1: Design and implement the TouchInputAdapter JNI layer to bridge Android MotionEvents with the original game's internal input handling (directinput/keyboard hooks).
- **Status:** IN_PROGRESS
- **Acceptance Criteria:**
  - Input translation layer functional via JNI
  - Simultaneous movement and camera interaction supported via pointer ID tracking
- **StartTime:** 2026-11-19 18:36:58 PST

### 2: Develop the HUD overlay renderer using Jetpack Compose (or SDL_Render) to create the virtual joystick and action buttons.
- **Status:** PENDING
- **Acceptance Criteria:**
  - Virtual joystick implemented with 360-degree support
  - All HUD buttons rendered and responsive to touch

### 3: Create the Settings/Customization menu for the HUD (size, opacity, position, sensitivity).
- **Status:** PENDING
- **Acceptance Criteria:**
  - HUD settings are adjustable
  - HUD configuration persists via DataStore

### 4: Integrate the HUD overlay with SH3RuntimeActivity to ensure it remains active during gameplay, menus, and cutscenes.
- **Status:** PENDING
- **Acceptance Criteria:**
  - HUD persists across all game states
  - Multi-touch interference prevented between camera drag and HUD buttons

### 5: Final Testing and Polish: Verify responsiveness, control accuracy, and handle different aspect ratios.
- **Status:** PENDING
- **Acceptance Criteria:**
  - HUD works correctly on multiple screen sizes
  - Controls are responsive and intuitive
