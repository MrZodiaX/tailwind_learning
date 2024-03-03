commands : 

npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat postcss@^7 autoprefixer@^7

npm install @craco/craco

-- change scripts in package.json 
  "scripts": {
    "start": "craco start",
    "build": "craco build",
    "test": "craco test",
    "eject": "react-scripts eject"
  },


  -- create craco.config 

  --init tw
  npx tailwindcss-cli@latest init 

   