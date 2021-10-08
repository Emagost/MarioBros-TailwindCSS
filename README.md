Web mobile and desktop compatible

commands =>{

  npm i tailwindcss postcss-cli autoprefixer @tailwindcss/jit
  npm install --production
  npm i nodemon
}

inside package.json => "dev": "nodemon -x npm run build:css -w src/tailwind.css -w tailwind.config.js -w public/index.html"
