# FitnessTracker
# Simple Fitness Tracker

A lightweight, easy-to-use fitness tracking web application that allows users to log their physical activities and view their fitness stats at a glance.

## Overview

This Simple Fitness Tracker is a standalone HTML/CSS/JavaScript application that provides basic fitness tracking functionality. It includes:

- Activity statistics dashboard (steps, calories, distance, active minutes)
- Form to log new workout activities
- Activity history log
- Responsive design that works on both desktop and mobile devices

## Screenshots

![Fitness Tracker Dashboard](https://api.placeholder.com/800/450)

## Getting Started

### Prerequisites

This is a simple web application that requires:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required

### Installation

1. Download the project files:
   - `index.html` - The main HTML file containing the application

2. No build process is required - this is a standalone web page.

### Running the Application

Simply open the `index.html` file in any web browser:

- Double-click the file
- Or right-click and select "Open with" and choose your preferred browser
- Or drag and drop the file into an open browser window

## Features

### Activity Statistics Dashboard

The top section displays key fitness metrics:
- Total Steps
- Calories Burned
- Distance Traveled
- Active Minutes

### Activity Logging

The form allows you to record new fitness activities with:
- Activity Type (Walking, Running, Cycling, Swimming, Gym Workout)
- Duration in minutes
- Intensity level (Low, Medium, High)

### Activity History

The bottom section displays your recent activities in chronological order with:
- Activity type
- Duration and intensity
- Date and time

## Usage Guide

1. **View Your Stats**: When you open the application, your current fitness statistics are displayed at the top.

2. **Log a New Activity**:
   - Select an activity type from the dropdown menu
   - Enter the duration in minutes
   - Select the intensity level
   - Click "Add Activity"

3. **View Activity History**: Scroll down to see your recent activities listed in reverse chronological order (newest first).

## Technical Details

### File Structure

```
fitness-tracker/
├── index.html  (contains HTML, CSS, and JavaScript)
└── README.md
```

### Technology Stack

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript**: Form handling and dynamic content updates

### Data Storage

Currently, the application stores data only for the current session. When you refresh the page, the newly added activities will be lost. The initial data shown is placeholder data.

### Customization

You can easily customize this application by:
- Modifying the CSS in the `<style>` section to change colors, layout, etc.
- Adding additional fields to the form
- Extending the JavaScript functionality

## Future Enhancements

Potential improvements that could be added:
- Local storage to persist data between sessions
- User accounts and authentication
- Data visualization with charts and graphs
- Goal setting and tracking
- Social sharing capabilities
- Export functionality for activity data

## Limitations

- Data is not saved between browser sessions
- No backend database integration
- Limited to predefined activity types
- No user authentication or multi-user support

## Browser Compatibility

Tested and works on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is available for personal and commercial use.

## Acknowledgments

- Font: Segoe UI
- Design inspired by modern fitness applications