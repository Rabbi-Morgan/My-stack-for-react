# My-stack-for-react
This is a documentation on how I create my react app.
///////////////////////

My stack: 
  React,
  SCSS,
  Tailwindcss,
  Redux

/////////////////////////

To create a react  app:

  npx create-react-app <file-name>
  
To add tailwindcss to the react app:
  
  step 1: npm install -D tailwindcss postcss autoprefixer
  step 2: npx tailwindcss init -p --- this will create a tailwind.config.js
  
  step 3: module.exports = {
            content: [
              "./src/**/*.{js,jsx,ts,tsx}",
            ],
            theme: {
              extend: {},
            },
          plugins: [],
  }--------------- this should be added to the tailwind.config.js
  
  step 4: @tailwind base;
          @tailwind components;
          @tailwind utilities;
  
  this ends the tailwindcss installation 
