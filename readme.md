# Bootstrap 5 RTL-LTR Support

This repository is dedicated to configuring Bootstrap for seamless support of both RTL (Right-to-Left) and LTR (
Left-to-Right) layouts.

## Installation

You have two options to install the `bootstrap-rtl-ltr-support` package and include the necessary CSS file in your project.

### Option 1: Using npm

1. Install the package using npm:

   ```bash
   npm install bootstrap-rtl-ltr-support
   ```
2. Once the package is installed, you can import the css/bootstrap.css file into your project as follows:
   ```html
    <link rel="stylesheet" href="node_modules/bootstrap-rtl-ltr-support/css/bootstrap.css">
    ```
### 2. Option 2: Manual Download

1. Download the package's CSS file from the following URL: [Download bootstrap.css](https://raw.githubusercontent.com/safaeean/bootstrap-rtl-ltr-support/main/css/bootstrap.css)

2. Include the downloaded bootstrap.css file in your project:

```html

<link rel="stylesheet" href="path/to/downloaded/bootstrap.css">
```

### 3. Option 3: External Link

1. Include the CSS file directly from an external link:

```html

<link rel="stylesheet"
      href="https://raw.githubusercontent.com/safaeean/bootstrap-rtl-ltr-support/main/dist/css/bootstrap.css">
```

## Usage

Once you have included the `bootstrap-rtl-ltr.css` file in your project, you can easily switch between RTL and LTR
layouts by changing the direction of your HTML's `<html>` tag or by applying the relevant class to your `<body>` tag.

Example for RTL layout:

```html

<html dir="rtl">
<!-- Your content here -->
</html>
```

Example for LTR layout:

```html

<html dir="ltr">
<!-- Your content here -->
</html>
```

## Issues

If you encounter any issues or have suggestions for improvements,
please [open an issue](https://github.com/safaeean/bootstrap-rtl-ltr-support/issues).

## License

This project is licensed under the [MIT License](LICENSE).