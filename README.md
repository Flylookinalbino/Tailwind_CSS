# Tailwind_CSS

## Install Tailwind CSS
1. Install Node.js

2. Create package.json
> npm init

3. Download Tailwind CSS
> npm install tailwindcss 

4. Customise tailwind.config.js 
> npx tailwind init

5. Create a folder and file called src/css/tailwind.css
> @tailwind base;
> @tailwind components;
> @tailwind utilities;

6. Create a folder and file called dist/css/tailwind.css

7. Create scripts in package.json
> "build:css":"tailwind src/css/tailwind.css -o dist/css/tailwind.css"

8. Build Tailwind CSS
> npm run build:css

9. link dist/css/tailwind.css to your html and start using.
