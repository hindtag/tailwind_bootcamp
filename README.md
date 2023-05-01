# Tailwind

This is where I store my tailwind development journey.

## Notable progress

- [x] The netninja
- [ ] Basic - continue on video 13
- [ ] Advance
- [ ] Pro

## Resources

1. The net ninja

- https://www.youtube.com/watch?v=bxmDnn7lrnk&list=PL4cUxeGkcC9gpXORlEHjc5bgnIi5HEGhw&index=4
- https://github.com/iamshaunjp/tailwind-tutorial

2. https://www.youtube.com/watch?v=arftp8kFBBg

### Installation

1. Download node.js - https://nodejs.org/en or check if installed already using node -v
2. on command line type npm install -D tailwindcss
3. on command line type npx tailwindcss init
4. create folder for
   build and src
5. under build folder create new file for
   index.html
6. modify tailwind.js content by adding:
   './build/\*.html'
7. under src folder create new file for
   input.css
8. modify input.css by adding:
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
9. on command line type npx tailwindcss -i ./src/input.css -o ./build/css/output.css
10. on index.html add link to the style.css
11. on command line type:
    npm init -y
12. on package.json scripts { } add
    "dev": "npx tailwindcss -i ./src/input.css -o ./build/css/output.css --watch"
13. Code your css

14. run below every time there has a changes. Run this code on command line:
    npm run dev
