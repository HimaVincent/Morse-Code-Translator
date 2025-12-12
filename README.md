# Morse Code Translator

A browser-based Morse Code Translator that automatically detects whether the user is typing **English** or **Morse code** and translates it.

Built with vanilla JavaScript, styled using BEM conventions and backed by unit tests using Jest.

---

## What this app does

* Translates **English → Morse code**
* Translates **Morse code → English**
* Automatically detects the input language
* Prevents translation when mixed input is detected
* Guides users when Morse spacing is likely incorrect
* Adjusts text size based on language for readability

No buttons to “choose a mode” — it just works.

---

## Key features

* Auto language detection (English, Morse, Mixed)
* Real-time translation with debouncing
* Error handling for mixed inputs
* Visual language indicator badge
* Contextual hints for Morse spacing
* Responsive, accessible UI
* Unit-tested core logic

---

## Tech stack

* HTML
* SCSS to CSS (BEM naming convention)
* Vanilla JavaScript 
* Jest for unit testing
* No frameworks & libraries

---

## How language detection works

* If input contains only letters or numbers → treated as English
* If input contains only dots, dashes, spaces or slashes → treated as Morse
* If both appear together → treated as mixed and blocked

This prevents incorrect or confusing translations and improves UX.

---

## Morse formatting rules

* One space between Morse letters
* A slash (/) **or** three spaces between words

If the app detects long Morse input without proper spacing, it shows a helpful hint — but only when the user is likely making a mistake.

---

## Possible improvements

* Add audio playback for Morse output
* Support punctuation symbols
* Add copy-to-clipboard actions

---

## Author

Built by Hima
Frontend developer in progress, focusing on clean logic, thoughtful UX, and solid fundamentals.
