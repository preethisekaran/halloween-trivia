# Mobile Trivia Quiz

A simple, mobile-friendly trivia quiz that works perfectly on phones.

## Quick Setup (GitHub Pages - Free)

1. Create a new repository on GitHub
2. Upload the `index.html` file
3. Go to Settings > Pages
4. Select "Deploy from a branch" > "main"
5. Your site will be live at: `https://yourusername.github.io/repository-name`

## Features

- Mobile-optimized design
- 5 sample trivia questions
- Real-time scoring
- Visual feedback for correct/incorrect answers
- Play again functionality

## Customizing Questions

Edit the `questions` array in the JavaScript section:

```javascript
const questions = [
    {
        question: "Your question here?",
        options: ["Option 1", "Option 2", "Option 3", "Option 4"],
        correct: 0  // Index of correct answer (0-3)
    }
];
```

## Generate QR Code

Once hosted, use any QR code generator with your GitHub Pages URL to create a QR code for easy phone access.
