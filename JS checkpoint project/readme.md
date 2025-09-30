```markdown
# Horoscope Generator

This project is a simple JavaScript program that generates a horoscope based on the user's birth month. It uses variables, control flow statements, and loops to map a birth month to a zodiac sign and then randomly select a fortune from a list of 100 possibilities.

## Features
- User enters their birth month (browser: `prompt()`, Node.js: `readline`).
- Program maps the month to a zodiac sign and symbol.
- A random fortune is selected from a list of 100 possible fortunes.
- Output includes the zodiac sign and a randomly generated fortune.

## Example

```

Enter the month you were born (e.g., March): March
Your sign is ♓ Pisces.
Fortune: An old friend may surprise you with a message.

```

## How to Run

### In the Browser
1. Copy the code into a `.html` file within `<script>` tags.
2. Open the file in a web browser.
3. A prompt will ask for your birth month.
4. Open the browser console to see the result.

### In Node.js
1. Copy the Node.js version of the code that uses the `readline` module.
2. Save it as `index.js`.
3. Run the program with:
```

node index.js

```
4. Enter your birth month in the terminal when prompted.

## Learning Purpose
The design and implementation of this project were kept simple for learning purposes:
- No external libraries.
- No complex user interface.
- Focused on practicing variables, conditionals, loops, and random number generation in JavaScript.

## Future Improvements
- Allow input of both month and day for more accurate zodiac calculation.
- Add unique fortunes per zodiac sign.
- Create a web interface to display results instead of using the console.
```