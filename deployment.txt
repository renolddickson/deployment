
npm install gh-pages --save-dev

"homepage": "http://smarthood.github.io/appname"


"predeploy": "npm run build",
"deploy": "gh-pages -d build"


git init
git remote add origin git@github.com:yourUserName/appname.git

git add .

git commit -m "commit description"

npm run deploy



git push origin master

to update:
git add .
git commit -m "commit description"
npm run deploy
