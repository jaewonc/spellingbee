# Spelling Bee Practice

A web-based spelling practice application with audio pronunciation and word lists.

## Features

- Audio pronunciation using browser speech synthesis
- Real-time progress tracking (total, correct, wrong, accuracy)
- Multiple word selection modes (random or sequential)
- Session history with detailed statistics
- Word list management from CSV files (years 2020-2030)
- Responsive design with blurred background
- Wrong word review at end of session
- LocalStorage persistence for session history

## Usage

1. Open `index.html` in a web browser
2. Select a word list (year 2020-2030)
3. Choose word selection mode:
   - Random: Words appear in random order
   - Sequential: Words appear in order (optionally start at specific word number)
4. Click "Start Practice"
5. Listen to the pronunciation and type the word
6. Press Enter to submit
7. Review wrong words at the end of the session

## File Structure

- `index.html` - Main application
- `background.jpg` - Background image
- `wordlists/` - CSV word lists by year (e.g., wordlist-2025.csv)
