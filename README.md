# Reboot.css

Reboot.css is a custom CSS file designed to provide a set of consistent and minimal styles for HTML elements. It serves as a starting point for building web projects, ensuring a clean and uniform base across different browsers.

## Features

- **Box Sizing Reset**: Sets `box-sizing: border-box` on all elements to include padding and border in the element's total width and height.
- **Smooth Scrolling**: Enables smooth scrolling for users who haven't expressed a preference for reduced motion.
- **Basic Typography**: Provides default font styles, sizes, and line heights for body text, headings, and other common text elements.
- **List and Table Styling**: Resets margin and padding for lists and provides basic styling for tables.
- **Form Elements**: Applies consistent styles to form elements, including inputs, buttons, and textareas.
- **Utility Classes**: Includes basic utility classes for commonly used elements such as `<hr>`, `<abbr>`, `<blockquote>`, and more.

## Installation

To use Reboot.css in your project, you can either copy the `reboot.css` file into your project directory or import it from your CSS/SCSS files.

### Download and Include

1. Download the `reboot.css` file and place it in your project directory.
2. Include the CSS file in your HTML file:
    ```html
    <link rel="stylesheet" href="path/to/reboot.css">
    ```

### Import in SCSS

If you're using SCSS, you can import the `reboot.css` file directly:
```scss
@import 'path/to/reboot.css';
````

### Usage
Reboot.css is intended to be used at the beginning of your CSS file to provide a consistent base for your styles. It should be included before any other custom styles or frameworks.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project</title>
  <link rel="stylesheet" href="path/to/reboot.css">
  <link rel="stylesheet" href="path/to/custom-styles.css">
</head>
<body>
  <!-- Your content here -->
</body>
</html>
```

### File Structure
The reboot.css file includes styles for various HTML elements, categorized into the following sections:

 - **Global Styles:** Resets and global styles applied to all elements.
 - **Typography:** Basic typography styles for text elements.
 - **Lists:** Styles for ordered and unordered lists.
 - **Tables:** Basic table styles.
 - **Forms:** Consistent styles for form elements.
 - **Utility Classes:** Additional utility classes for commonly used elements.

### Customization
Feel free to customize the styles in reboot.css to fit the needs of your project. You can add, modify, or remove styles as necessary.

### Contributing
If you find any issues or have suggestions for improvements, please feel free to create a pull request or open an issue in the repository.

### License
Reboot.css is open-source and released under the MIT License. See the LICENSE file for more information.