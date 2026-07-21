# Cantonese Jyutping Ruby Generator

A simple, single-file web application that converts Cantonese Chinese text into HTML `<ruby>` annotations formatted with Jyutping pronunciation guidelines.

## Features

- **Instant Conversion**: Translates Cantonese characters into standard Jyutping pronunciation.
- **Visual Preview**: View rendered HTML `<ruby>` annotations live in modern, styled typography.
- **HTML Output**: Generates clean HTML code for copying and pasting directly into website projects or document editors.
- **Built-in Dictionary**: Includes an embedded dictionary covering common Cantonese characters, colloquial vocabulary, and names.
- **Non-blocking Parser**: Handles English text, punctuation marks, and unknown characters gracefully.

## How to Use

1. Open the `index.html` file in any modern web browser.
2. Enter or paste Cantonese text into the input box.
3. Click the **Convert to Ruby HTML** button.
4. Preview the rendered text in the **Visual Preview** section or click **Copy Code** to copy the generated HTML.

## Tech Stack

- **HTML5**: Uses standard `<ruby>` and `<rt>` elements.
- **CSS3**: Custom CSS variables with a modern dark theme layout.
- **JavaScript (Vanilla)**: Lightweight client-side lookup and rendering with zero external dependencies.
