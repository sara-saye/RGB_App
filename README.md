# RGB App

A simple Android application demonstrating activity navigation through a cycle of colors: Red, Green, and Blue.

## Features

- **Red Screen (`MainActivity`)**: The entry point of the application. Navigates to the Green screen.
- **Green Screen (`GreenActivity`)**: Navigates to the Blue screen.
- **Blue Screen (`BlueActivity`)**: Navigates back to the Red screen (`MainActivity`) using `FLAG_ACTIVITY_CLEAR_TOP` to reset the task stack.
