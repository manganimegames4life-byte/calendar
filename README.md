This is just a mini project which consists in making a calender app via Electron, thus Node.js is needed for those interested. 

For guidance, this project took me about 1 afternoon(or better said night XD) including designing it in Figma, so imo it should take around 2 for complete beginners.
The languages involved include: CSS, HTML and a tiny bit of JavaScript.

Intro aside, I'll try to kinda explain step by step in the following text (so skip if needed).
1. Install the necessary programs (VScode and Node.js) I did so via Chocolatey which is a packet manager for windows tho I've heard Homebrew works for MacOs.
2. Code the contents. remember package-lock.json and node modules are produced by the system so DO NOT TOUCH them. This is because package-lock.json records exact dependency versions. If saving to github node modules should be in .gitignore as they contain a lot of files we dont need to write and can be recreated via package.json and package-lock.json.
3. Once in vs code via nmp you can run codes by "npm run start". To kill the batch job in terminal use "ctrl+c" and then "y" for yes. Remember to save all changes to see them reflected on the electron app.
4. Fiddle and customise your app and have fun! (I used Figma to get the css for styling but I've heard that penpot also works for that)

What each file does:
- assets: stores images used for styling
-.gitignore: makes git ignore whatever is inside
- README.md: markdown file for text (in this case this file i used to explain stuff)
- index.html: works along with css, forming the divisions within the app
- main.js: main part in Javascript which creates the window
- package-lock.json, package.json: recreate node modules
- script.js: to link 
