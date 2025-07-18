# Responsive Sidebar Menu Project

This project is a responsive sidebar menu with light and dark mode support. It features smooth transitions and color changes based on the selected mode.

## Features

- Responsive sidebar navigation menu
- Light and dark mode toggle
- Hover effects on sidebar links that change color based on the mode
- Uses CSS variables for easy theming and color management
- Smooth transitions for color and layout changes

## How It Works

### Dark Mode and Hover Color Change

- The project uses CSS variables defined in the `:root` selector for default (light) mode colors.
- When dark mode is activated, the `body` element receives a `dark` class, which overrides the CSS variables with dark mode colors.
- The hover background color on sidebar links uses the CSS variable `--primary-color`.
- Because `--primary-color` changes from purple in light mode to grey in dark mode, the hover color changes accordingly.

### File Structure

- `index.html`: Main HTML file containing the sidebar and page structure.
- `style.css`: Contains all the styles, including color variables, dark mode styles, and hover effects.
- `script.js`: Contains JavaScript to toggle dark mode and handle sidebar interactions.
- `sidebar-logo-cl.png`: Sidebar logo image.

## Usage

1. Open `index.html` in a web browser.
2. Use the toggle switch in the sidebar to switch between light and dark modes.
3. Hover over sidebar menu items to see the color change based on the current mode.

## Dependencies

- Google Fonts: Poppins font is imported via CSS.

## License

This project is open source and free to use.
