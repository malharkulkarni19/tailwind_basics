So, its a production Tailwind Folder, if you want production, you need to install PostCSS, otherwise you can use CDN for learning and basic use only. For production, CDN is not applicable.

For Creating Server

1) npm init -y
2) npm install -D tailwindcss postcss autoprefixer vite

3) change following file tailwind.config.js to this
content: ["*"],

4) craate new css file and paste this
@tailwind base;
@tailwind components;
@tailwind utilities;


5) npx tailwindcss init -p

6) for run, change test name according to you
npm run call
