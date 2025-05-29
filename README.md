# Vowel Checker Application

A simple yet visually appealing web application that counts vowels in user-provided text. This project demonstrates fundamental JavaScript programming concepts, DOM manipulation, and modern CSS styling with animations.

## Live Preview

Check out the live application [here](https://parthsharma30.github.io/vowel-counter).

## Features

- **Text Input**: Large textarea for users to input any text
- **Real-time Vowel Counting**: Counts all vowels (a, e, i, o, u) in the provided text
- **Case Insensitive**: Works with both uppercase and lowercase letters
- **Animated UI**: Features neon glow effects and smooth animations
- **Responsive Design**: Clean, modern interface with gradient background
- **Glass Morphism**: Modern UI design with backdrop blur effects

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with animations, gradients, and glass morphism effects
- **JavaScript**: Core functionality and DOM manipulation

## How It Works

1. User enters text in the textarea
2. Clicks the "Count Vowels" button
3. JavaScript processes the text character by character
4. Identifies vowels (a, e, i, o, u) regardless of case
5. Displays the total count with animated styling

## File Structure

```
vowel-counter/
├── index.html      # Main HTML structure
├── style.css       # Styling and animations
├── script.js       # Vowel counting logic
└── README.md       # Project documentation
```

## Code Highlights

### JavaScript Logic
The application uses a simple yet effective approach:
- Converts input text to lowercase for case-insensitive comparison
- Iterates through each character using a for loop
- Uses a helper function `isVowel()` to check if a character is a vowel
- Updates the DOM to display results

### CSS Animations
- **Neon Glow Effect**: Pulsing shadow animation for visual appeal
- **Slide-in Animation**: Smooth entrance effect for the textarea
- **Glass Morphism**: Modern frosted glass appearance with backdrop blur

## Learning Objectives

This project helped me practice:
- **String Manipulation**: Processing text character by character
- **DOM Manipulation**: Accessing and updating HTML elements with JavaScript
- **Event Handling**: Responding to button clicks
- **CSS Animations**: Creating engaging visual effects
- **Modern CSS**: Implementing contemporary design trends

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/ParthSharma30/vowel-counter.git
```

2. Navigate to the project directory:
```bash
cd vowel-counter
```

3. Open `index.html` in your web browser.

Alternatively, visit the live application at: https://parthsharma30.github.io/vowel-counter

## Usage

1. Enter any text in the large textarea
2. Click the "Count Vowels" button
3. View the total vowel count displayed below

## Future Enhancements

Potential improvements for this project:
- Count specific vowels individually
- Add consonant counting functionality
- Include character and word count features
- Add support for accented vowels
- Implement real-time counting as user types
- Add more text analysis features

## License

This project is open source and available under the [MIT License](LICENSE).
