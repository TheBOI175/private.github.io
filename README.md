# Pandemonium Minigame — Chaos Mode

A challenging browser-based minigame where you must keep your cursor within a center circle while chaotic forces try to fling it away, all synchronized to music from YouTube.

## How to Play

1. **Start**: Click "Start Minigame" and allow pointer lock when prompted
2. **Objective**: Keep your white cursor dot inside the dashed center circle
3. **Survive**: Maintain your energy bar by staying in the center while random flings try to knock you out
4. **Win**: Survive until the music ends (approximately 30 seconds)

## Game Mechanics

### Energy System
- **Green bar**: Fills when cursor is inside the center circle
- **Drains**: When cursor is outside the center circle
- **Game Over**: When energy reaches zero

### Chaos Elements
- **Grace Period**: 7 seconds of safety at the start
- **Random Flings**: Powerful forces that launch your cursor toward screen edges
- **Burst Attacks**: Multiple rapid flings in succession (35% chance)
- **Increasing Difficulty**: Fling strength increases over time
- **Constant Jitter**: Subtle cursor shake throughout the game

### Controls
- **Mouse Movement**: Provides some control over cursor position
- **Pointer Lock**: Required for gameplay - cursor is hidden and movement is relative

## Technical Features

- **YouTube Integration**: Synchronized with music video (configurable video ID)
- **Responsive Design**: Full viewport coverage
- **Visual Feedback**:
  - Center circle highlights when cursor is inside
  - Cursor turns red when flinged
  - Pulse animations for fling indicators
- **Cross-browser Compatibility**: Supports various pointer lock implementations

## Configuration

The game includes a `CONFIG` object with customizable parameters:
- `centerRadius`: Size of the target area (37px)
- `gracePeriod`: Safe time at start (7000ms)
- `flingStrength`: Power of chaos flings (67)
- `videoId`: YouTube video ID for background music
- Various other physics and timing parameters

## Files

- `index.html`: Complete game implementation (HTML, CSS, JavaScript)

## Requirements

- Modern web browser with pointer lock support
- Internet connection (for YouTube API)
- User gesture to start (required for autoplay policies)

## Setup

Simply open `index.html` in a web browser. The game will automatically load the YouTube API and be ready to play.

## Author

Mowgli
