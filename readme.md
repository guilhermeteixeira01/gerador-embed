# Discord Embed Generator

A web-based tool for creating rich Discord embeds effortlessly. Customize your embeds with live previews, keyboard shortcuts, and full markdown support.

## Table of Contents

- [Discord Embed Generator](#discord-embed-generator)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Demo](#demo)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)
  - [Contact](#contact)

## Features

- **Live Preview**: Instantly see how your embed will look.
- **Markdown Support**: Use Discord's markdown for text formatting.
- **Keyboard Shortcuts**: Quick formatting with `Ctrl+B`, `Ctrl+I`, etc.
- **Custom Fields**: Add, remove, and reorder fields in your embed.
- **Image Support**: Include thumbnails and images.
- **Color Picker**: Choose custom embed colors.
- **Timestamp**: Add current timestamps to your embed.
- **Copy to Clipboard**: Easily copy the JSON code for your embed.

## Demo

Try the live version here: [Discord Embed Generator](https://katerlol.github.io/discord-embed-generator/)

## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/katerlol/discord-embed-generator.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd discord-embed-generator
   ```

3. **Open `index.html` in your browser**:

   - You can open the file directly.
   - Or use a local server for better compatibility:

     ```bash
     # Using Python 3.x
     python -m http.server
     ```

     Then navigate to `http://localhost:8000` in your browser.

## Usage

1. **Customize Embed Details**:

   - **Title**: Set the embed title.
   - **Description**: Write your message with markdown.
   - **Fields**: Add fields with names and values.
   - **Author**: Set author name, icon, and URL.
   - **Footer**: Add footer text and icon.
   - **Images**: Provide URLs for thumbnails and images.
   - **Color**: Select a color for the embed's side bar.
   - **Timestamp**: Toggle to include the current timestamp.

2. **Live Preview**:

   - The right side of the screen shows a live preview of your embed.

3. **Formatting Text**:

   - Use markdown syntax in text fields.
   - Utilize keyboard shortcuts for quick formatting.

4. **Copy Embed Code**:

   - Click on "Copy to Clipboard" to copy the JSON code.
   - Use the code in your Discord bot or webhook.

## Keyboard Shortcuts

Enhance your productivity with these shortcuts in the description field:

- **Bold**: `Ctrl + B`
- **Italic**: `Ctrl + I`
- **Underline**: `Ctrl + U`
- **Strikethrough**: `Ctrl + S`
- **Inline Code**: <kbd>Ctrl</kbd> + <kbd>\`</kbd> (backtick)
- **Code Block**: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>\`</kbd> (backtick)
- **Toggle Formatting**: Applying the shortcut again removes the formatting if already applied.

## Contributing

Contributions are welcome! To contribute:

1. **Fork the repository**.

2. **Create a new branch**:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**.

4. **Commit your changes**:

   ```bash
   git commit -m "Add your feature"
   ```

5. **Push to your branch**:

   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request**.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](license.txt) file for details.

## Acknowledgments

- **[Vue.js](https://vuejs.org/)** for the reactive UI framework.
- **[Bootstrap 5.1.3](https://getbootstrap.com/docs/5.1/getting-started/introduction/)** for styling components.
- **[vuedraggable](https://github.com/SortableJS/Vue.Draggable)** for draggable fields.

## Contact

For questions or support:

- **Issue Tracker**: [GitHub Issues](https://github.com/katerlol/discord-embed-generator/issues)
- **Discord**: katerlol
