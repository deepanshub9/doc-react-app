# Doc React App

This project demonstrates a simple React application showcasing basic component structure and data flow.

## What I Did

- **Background Component:** Displays the word "Docs" in large text in the center of the screen.

- **Foreground Component:** Uses the `map` method to iterate over an array of data, dynamically rendering multiple instances of the `Card` component.

- **Card Component:** Represents a visual card on the screen. Data for each card is dynamically passed from the `Foreground` component, allowing for varying content.

- **Framer Motion:** The project incorporates the `framer-motion` library to add animations and interactive effects to the card elements.

## Project Structure

The project follows a common React file structure:

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/deepanshub9/doc-react-app.git

   cd doc-react-app

   ```

2. **Install dependencies:**
   ```bash
   git clone https://github.com/deepanshub9/doc-react-app.git

   npm install
   ```
3. **Running the App:**
   `npm start`

Open your browser: The app will be accessible at http://localhost:5173

## Key Concepts

This project demonstrates several key concepts in React development:

### Component-Based Architecture:

The app is structured using components, each responsible for a specific part of the UI.

### Data Flow:

Data is passed down from parent components to child components using props.

### Dynamic Conditional Rendering :

The `map` method allows for dynamic rendering of multiple components based on data.

### Styling:

The project uses CSS for styling.

### Animations:

Framer Motion is used to add animations and interactive effect.
