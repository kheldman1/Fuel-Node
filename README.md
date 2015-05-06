Fuel (for Node.js)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

This application allows users to utilize Salesforce Marketing Cloud's Fuel Platform Auth, REST and SOAP APIs for Node.js

Learn more about our Fuel Platform Node Auth, REST, and SOAP libraries along with documentation and examples:
[AUTH][1]
[REST][2]
[SOAP][3]

For step-by-step instructions on creating a Salesforce Marketing Cloud ClientID and ClientSecret, visit:
[Salesforce Marketing Cloud - App Center] [4]

You can also learn more about *http request* calls from [our wiki][5]. 


## Deploy to Heroku

You can deploy this app to Heroku and have it up and running instantly.
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Installing the Application

This library is compatible with:
- Node.js
  - 0.8
  - 0.10
  - 0.12
- io.js

To install this application locally, type the following in command line

```
git clone git@github.com:kheldman1/Fuel-Node.git
cd Fuel-Node
npm install
```
 
Note: `npm install` will error if you're using node version 0.8 with developer dependencies. To have a successful install for testing/contributing use `npm install -g npm@1.2.8000` and the issue should be resolved.


### Running the Application

Follow these instructions to run the application on your local machine:
1. Change the current directory to Node-Fuel
2. Execute the follwoing command: node app.js
3. Open the following page in your web browser: [http://localhost:3000] [6]



[1]: https://github.com/ExactTarget/Fuel-Node-Auth/wiki
[2]: https://github.com/ExactTarget/Fuel-Node-REST
[3]: https://github.com/ExactTarget/Fuel-Node-SOAP
[4]: http://code.exacttarget.com/apis-sdks/rest-api/using-app-center-to-get-an-api-key.html
[5]: https://github.com/mikeal/request#requestoptions-callback
[6]: http://localhost:3000
