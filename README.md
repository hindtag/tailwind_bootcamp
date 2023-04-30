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
2. on command line type npx tailwindcss init
3. create folder for
   build and src
4. under build folder create new file for
   index.html
5. modify tailwind.js content by adding:
   './build/\*.html'
6. under src folder create new file for
   input.css
7. modify input.css by adding:
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
8. on command line type npx tailwindcss -i ./src/input.css -o ./build/css/output.css
9. on index.html add link to the style.css
10. on command line type:
    npm init -y
11. on package.json scripts { } add
    "dev": "npx tailwindcss -i ./src/input.css -o ./build/css/output.css --watch"
12. Code your css

13. run below every time there has a changes. Run this code on command line:
    npm run dev
