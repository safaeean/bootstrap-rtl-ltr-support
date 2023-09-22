# Bootstrap 5 RTL-LTR Support

This repository is dedicated to configuring Bootstrap for seamless support of both RTL (Right-to-Left) and LTR (
Left-to-Right) layouts.

## Installation

To use the RTL-LTR support configuration, simply include the following CSS file in your project:

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