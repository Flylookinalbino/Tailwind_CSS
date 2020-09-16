# Tailwind_CSS

## Install Tailwind CSS
1. Install Node.js

2. Create package.json
> npm init

3. Download Tailwind CSS and PostCSS-CIL and autoprefixer
> npm install tailwindcss postcss-cli autoprefixer

4. Customise tailwind.config.js 
> npx tailwind init

5. Create a postcss.config.js
> module.exports = {
>   plugins: [
>       require('tailwindcss'),
>       require('autoprefixer'),
>   ]
> }

6. Create a folder and file called src/css/tailwind.css
> @tailwind base;
> @tailwind components;
> @tailwind utilities;

7. Create a folder and file called dist/css/tailwind.css

8. Create scripts in package.json
> "build:css":"postcss src/css/tailwind.css -o dist/css/tailwind.css"

9. Build Tailwind CSS
> npm run build:css

10. link dist/css/tailwind.css to your html and start using.
