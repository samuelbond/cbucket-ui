# cBucket
cBucket is a software configuration manager that enables you to use the web browser to 
add and modify your software configuration. cBucket helps you reduce mis-configuring
your software by providing visibility and transparency,  also it provides
an audit trail of when and by whom a configuration was changed.
cBucket also supports storage of secret configuration which is powered by [Vault by HashiCorp](https://www.vaultproject.io/)
cBucket provides an HTTP API that can be used to access your project's configuration when
automating deployments using IT Orchestration tools.

## Features

- Storage of configuration
- Storage of secret configuration powered by [Vault by HashiCorp](https://www.vaultproject.io/)
- Team collaboration 
- Web browsing of configurations
- Support for IT Orchestration tools


## cBucket UI

In the project directory, you can run:

### `npm start`

Runs the cBucket UI in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


### `npm test`

Launches the test runner in the interactive watch mode.<br>

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](#deployment) for more information.