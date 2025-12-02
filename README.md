# Spelling Bee Practice

A web-based spelling practice application designed to help students prepare for spelling bee competitions through interactive audio-based learning and comprehensive performance analytics.

**Live Application**: [https://jaewonc.github.io/spellingbee/](https://jaewonc.github.io/spellingbee/)

## Overview

This application provides an immersive spelling bee practice environment that leverages browser-based text-to-speech technology to simulate authentic competition conditions. Students can practice with curated word lists spanning multiple years (2020-2030), receive immediate feedback on their attempts, and track their progress over time through persistent session analytics.

Key capabilities include:
- Audio-based word pronunciation using browser speech synthesis
- Real-time performance metrics and accuracy tracking
- Configurable practice modes (random or sequential word selection)
- Comprehensive session history with LocalStorage persistence
- Post-session review of incorrect spellings for targeted improvement

The application features a distraction-minimized interface with a blurred background, allowing students to maintain focus during practice sessions.

## Features

### Core Functionality
- **Audio Pronunciation**: Browser speech synthesis reads each word aloud
- **Real-time Progress Tracking**: Live display of total words, correct answers, wrong answers, and accuracy percentage
- **Session History**: Detailed statistics saved in browser LocalStorage with persistent data across sessions

### Practice Modes
- **Random Mode**: Words appear in randomized order for varied practice
- **Sequential Mode**: Words appear in list order with optional starting position configuration

### User Experience
- **Responsive Design**: Blurred background with centered practice interface for distraction-free learning
- **Wrong Word Review**: End-of-session summary displaying all missed words for targeted review
- **Word List Management**: CSV-based word lists organized by year (2020-2030)

## Getting Started

Visit the live application at [https://jaewonc.github.io/spellingbee/](https://jaewonc.github.io/spellingbee/)

### How to Use

1. Select a word list from the available years (2020-2030)
2. Choose your preferred practice mode:
   - **Random**: Words presented in random order
   - **Sequential**: Words presented in order (optionally specify starting word number)
3. Click "Start Practice" to begin your session
4. Listen to each word pronunciation and type your spelling
5. Press Enter to submit your answer
6. Review incorrect spellings at the end of your session

## File Structure

- `index.html` - Main application
- `background.jpg` - Background image
- `wordlists/` - CSV word lists by year (e.g., wordlist-2025.csv)
