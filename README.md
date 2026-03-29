# Wordle Pad

This won't solve the Wordle for you — nor should it! Enjoy doing the puzzle.

What this will do is let you easily generate and update a view that may be helpful for visualizing potential solutions. Instead of showing what's been ruled out ("There's an A, but it's not in space 2"), this view shows what's still possible, given what's already been ruled out ("There's an A, and it's in space 1, 3, 4, or 5").

**Story behind it:** I found myself making the same visual in my phone notes app every day, so I worked with Claude to make a simple app to create that view for me.

## How to use

**Set it up as a mobile app on your phone:**

- Open [https://logan-d-clark.github.io/WordlePad/](https://logan-d-clark.github.io/WordlePad/) in your phone's browser
- **iOS (Safari):** Tap the Share button → "Add to Home Screen"
- **Android (Chrome):** Tap the menu (⋮) → "Add to Home Screen"

It will appear on your home screen and launch full-screen, like a native app.

**Using it during your Wordle:**

- As yellow letters appear, add a row to the table for each yellow letter.
- Then, tap the location(s) in the word where you know that yellow letter cannot be. Those will get deselected.

What you're left with is a running view of which spots each letter CAN still be present in, given the information you've learned so far in the puzzle.

Happy hunting!
