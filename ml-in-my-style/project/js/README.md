# JavaScript Directory

This directory contains all the JavaScript files for the Machine Learning educational website.

## Files

- `main.js` - Main JavaScript file that handles:
  - Mobile menu toggle functionality
  - Particles.js initialization and configuration
  - Topic expansion for the topics page
  - Answer toggle functionality for interview questions
  - Scroll animations

## Features

### Mobile Navigation
The JavaScript handles responsive navigation menu for mobile devices, including:
- Toggle menu button functionality
- Closing the menu when clicking outside

### Interactive Particles Background
Uses particles.js library to create an engaging background effect that reinforces the machine learning theme.

### Topic Card Expansion
On the topics page, allows users to click on a topic card to reveal subtopics with smooth animation.

### Interview Question Toggles
On subtopic pages, allows users to show/hide answers to interview questions.

### Animation Effects
Provides scroll-based animation effects to enhance user experience.

## Usage

The JavaScript is modular and uses event listeners to handle different functionalities based on the current page. The code automatically checks which page is being viewed and initializes the appropriate functionality.

## Dependencies

- Particles.js - For the interactive background particles effect