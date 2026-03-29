# Ripple-Effect

An interactive community impact game where your actions ripple across a 10×7 town grid, influencing NPCs and transforming the environment.

## Overview

**Ripple-Effect** is a unique simulation game that demonstrates how individual actions create waves of positive change across a community. Manage limited resources across four domains—Environment, Awareness, and Community—while directly witnessing the cascading effects of your decisions on the town's tiles and NPC behavior.

## Features

### 🎮 Dynamic Game Board
- **10×7 Interactive Grid**: A full town landscape divided into 5 distinct tile types
  - 🌊 **River**: Water management and eco-restoration
  - 🌳 **Park**: Environmental recreation spaces
  - 🏘️ **Residential**: Community living areas
  - 🌾 **Farm**: Agricultural zones
  - 🏛️ **Community Center**: Hub of civic engagement

### 📊 Real-Time HUD
- **Day Counter**: Track time progression
- **Energy System ⚡**: Manage your action capacity
- **Time Display ⏱️**: In-game clock showing passage
- **Active NPC Tracker**: See which NPCs are engaged
- **3 Domain Meters**: Environment / Awareness / Community with animated progress bars

### 🎯 Action System
Four powerful actions you can take across the town—each with resource costs and community impact:
1. **Clean River** 🌊 - Restore water quality and improve ecosystem health
2. **Educate** 📚 - Raise community awareness and NPC engagement
3. **Plant Trees** 🌳 - Expand green spaces and environmental recovery
4. **Organize** 🤝 - Strengthen community bonds and civic participation

### ✨ Visual Feedback & Animations
When you take action, watch the ripples spread:
- **Tile Transformation**: Watch tiles shift color and icons as their health improves
  - Example: River tiles transition from 🌫️ (polluted) → 🌊 (clean) → 🐟 (thriving)
- **Ripple Rings**: Concentric ripples radiate outward from the action site
- **Influence Pulses**: Neighboring tiles light up and pulse based on distance
- **Water Shimmer**: River tiles continuously shimmer to suggest flowing water
- **NPC Activation**: NPCs transition through states (grey → yellow pulse → green pulse) with notifications

### 👥 NPC System
- **3 Distinct NPCs**: Each with unique voice and awareness thresholds
- **State Transitions**: NPCs respond to community improvements
  - Grey (Unaware) → Yellow (Curious) → Green (Active)
- **Contextual Engagement**: NPCs become active when your improvements reach their awareness threshold

### 📚 Reference Library
Below the game screen, explore detailed tile states and NPC information:
- **Tile State Library**: All 5 tile types across 3 conditions each (polluted → transitioning → clean)
- **NPC State Showcase**: Visual reference for all NPC states, behaviors, and characteristics

## Technical Stack

- **HTML5**: Interactive markup and structure
- **CSS3**: Animations, gradients, and visual polish
- **JavaScript**: Game logic, state management, and interactivity

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Mgregchi/Ripple-Effect.git
   ```

2. Open `index.html` in your web browser to start playing

3. Start taking actions and watch the ripples flow through your community!

## How to Play

1. **Assess Your Resources**: Check your Energy, Time, and Domain meters
2. **Choose an Action**: Select one of the 4 action buttons
3. **Click a Tile**: Target the tile you want to improve
4. **Watch the Ripples**: See how your action cascades through the community
5. **Engage NPCs**: Actions improve domain scores, triggering NPC engagement
6. **Balance the Domains**: Strategically allocate actions to improve all three domains

## Game Mechanics

- **Resource Management**: Each action costs Energy; balance your use wisely
- **Cascading Effects**: Your actions don't just affect one tile—they influence neighbors based on proximity
- **NPC Awareness**: NPCs require certain domain thresholds to become engaged
- **Tile Progression**: Tiles improve through multiple stages as you take action
- **Time Progression**: Days advance as you take actions, creating urgency and strategy

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to fork this project and submit pull requests with improvements, new features, or bug fixes.

## Future Enhancements

- Additional tile types and NPCs
- Difficulty levels and challenges
- Persistent progression tracking
- Mobile-responsive design
- Sound effects and background music

---

**Created by**: [Mgregchi](https://github.com/Mgregchi)  
**Last Updated**: March 2026