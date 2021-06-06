# Parsing
  For the given input of numbers separated by comma, when submit displays the result in the form of list or table

## Description :

  For the frontend, we create a react app using the command " npx create-react-app <app-name>" and use the default port as http://localhost:3000 by using yarn start command. The result is shown in the web browser. When the user inputs the value, the value is passed to backend. Here the backend is made using node.js(or express.js). Backend calls the api using fetch command. The result i,e whether pass or fail is then sent to react app. To do so, we install a package called cross origin using the command "npm install cors". Since the backend is made using node.js we set the port in the app.js as 9000. Running the backend at the address "http://localhost:9000" and the frontend at the same time, result is then displayed in the web browser once the user hits submit button.

### Dependencies Used:

  1.      cookie-parser : "~1.4.4"
  2.      cors : "^2.8.5"
  3.      debug : "~2.6.9"
  4.      express : "~4.16.1"
  5.      http-errors : "~1.6.3"
  6.      jade : "~1.11.0"
  7.      morgan : "~1.9.1"
  8.      @testing-library/jest-dom : "^5.11.4"
  9.      @testing-library/react : "^11.1.0"
  10.     @testing-library/user-event : "^12.1.10"
  11.     react : "^17.0.2"   
