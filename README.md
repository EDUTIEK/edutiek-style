# Edutiek Style

This directory contains the custom Edutiek style for the application.

## Installation

To install the style, navigate to the installation path:

```bash
cd ./public/Customizing/skin
```

Then clone the style repository:

```bash
git clone https://github.com/EDUTIEK/edutiek-style.git -b edutiek10 edutiek
```

## Building the Style

The style is built using Sass. To compile the `delos.scss` file to CSS, use one of the following commands from this directory:

### Standard Output

```bash
./node_modules/.bin/sass delos.scss mystyle.css
```

This generates a standard, readable CSS file (`mystyle.css`).

### Compressed Output

```bash
./node_modules/.bin/sass --style=compressed delos.scss mystyle.css
```

This generates a minified CSS file (`mystyle.css`) suitable for production.

## Change Log

### 10.1

The following changes have been made:

- Switched to the EDUTIEK icons
- Changed the HEADERIcon CSS
- Switched to a new main color #0094d1

