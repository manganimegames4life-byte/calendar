This is just a mini project which consists in making a calendar app via Electron, thus Node.js is needed for those interested. 

For guidance, this project took me about 1 afternoon(or better said night XD) including designing it in Figma, so imo it should take around 2 for complete beginners.
The languages involved include: CSS, HTML and a tiny bit of JavaScript.

Intro aside, I'll try to kinda explain step by step in the following text (so skip if needed).
1. Install the necessary programs (VScode and Node.js) I did so via Chocolatey which is a package manager for windows tho I've heard Homebrew works for macOs. Oh and ofc do install electron too via "npm install electron --save-dev" after you've checked node.js and npm through "node -v" and "npm -v" respectively. Also, do remember to cd it to the current folder you're working with.
2. Code the contents. remember package-lock.json and node modules are produced by the system so DO NOT TOUCH them. This is because package-lock.json records exact dependency versions. If saving to github node modules should be in .gitignore as they contain a lot of files we don't need to write and can be recreated by "npm install" which then uses package.json and package-lock.json.
3. Once in vs code via npm you can run codes by "npm run start". To kill the batch job in terminal use "ctrl+c" and then "y" for yes if instructed. Remember to save all changes and reload app to see them reflected on the electron app.
4. Fiddle and customise your app and have fun! (I used Figma to get the CSS for styling but I've heard that Penpot also works for that)

What each file does:
- assets: stores images used for styling
-.gitignore: makes git ignore the files listed inside it
- README.md: markdown file for text (in this case this file i used to explain stuff)
- index.html: works along with CSS, forming the divisions within the app
- main.js: main part in JavaScript which creates the window
- package-lock.json, package.json: used by "npm install" to recreate node_modules, the package.json contains " "start": "electron ." "which is what allow "npm run start" to work
- script.js: to create functions to get date and update calendar
- styles.css: styles to make it pretty

HELLO WORLD and HAPPY CODING!!!!