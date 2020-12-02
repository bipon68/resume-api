# Resume API
My Resume API

### Project Creation step by step
- npm install -g json-server
- npm install -g json --registry https://registry.npmjs.org
- npm init
- npm i json-server
- npm i json-server --registry https://registry.npmjs.org
- npm install -g heroku --registry https://registry.npmjs.org

### Run project
- json-server --watch db.json

### Git
- git add .
- git commit -m "add resume"
- git push origin HEAD

### Deploy
- brew tap heroku/brew && brew install heroku
- heroku create my-resume-api
- git push heroku main

### Reference
- [Make your own API](https://www.youtube.com/watch?v=FLnxgSZ0DG4)

