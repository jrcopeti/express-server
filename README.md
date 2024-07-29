### Install

- npm init -y (y yes to all)
- git init
- npm i -D nodemon
- npm i express
- npm i dotenv

### index.js

- import the packages
- const app = express()
- app.get('/', (req, res) => res.send('Hello World!'))
- app.listen(port, () => console.log('Server is running on port ' + port))
