# My First Tailwind Project: Login Page

Welcome to my first project using Tailwind CSS! This project is a simple login page designed and styled with the help of Tailwind's utility-first CSS framework.

## Project Overview

The goal of this project was to create a clean and modern login page, showcasing the simplicity and power of Tailwind CSS. The project includes a responsive design, making it suitable for various devices and screen sizes.

## Technologies Used

- HTML
- CSS (Tailwind CSS)

## Download Tailwind for run Project 

```css
npm install -D tailwindcss
npx tailwindcss init
```
```bash
Add the paths to all of your template files in your tailwind.config.js file.
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```css
Add the @tailwind directives for each of Tailwind’s layers to your main CSS file.
@tailwind base;
@tailwind components;
@tailwind utilities;
```
```css
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
```css
Add your compiled CSS file to the <head> and start using Tailwind’s utility classes to style your content.

<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./output.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</body>
</html>
```

## Features

- **Responsive Design:** The login page is designed to be responsive and work seamlessly across different devices.

- **Tailwind CSS:** The project leverages the utility classes provided by Tailwind CSS for quick and efficient styling.


