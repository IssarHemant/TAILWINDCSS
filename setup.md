## How to setup tailwind css

step 1: Run the following commands

```
npm install -D tailwindcss
npx tailwindcss init
```

step 2: Update tailwind.conf.js file to include this line:
```
content:["*.html"],
```

step 3: create src/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

step 4: Include the src/output.css file to your html

step 5: Run the following command:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```