
# RazorPay Clone

I've developed a fully responsive RazorPay clone webpage using HTML, TailwindCSS.


## 🤵 Authors

- [@Tejussardana](https://www.github.com/Tejussardana)


## 💻 Installation

To deploy this project: 
    First we have to download node and install tailwindCSS via npm on Vscode

```bash
  npm install -D tailwindcss postcss autoprefixer vite
```
Now, create tailwind.config.js file using command:
```bash
  npx tailwindcss init -p
```
Add the path of all files by putting "*" in content in tailwind.config.js file:
```bash
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
Now, create a css file and add the code given:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Link your CSS file in html file:
```bash
<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="output.css" rel="stylesheet">
</head>
```
To run the HTML file, run command:
```bash
npm run start
```


## 🛠 Skills
HTML, TailwindCSS...


