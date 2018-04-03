# allApologies

--------------sudo ---------------
  Used outside of brew install when permissions are required to install plugins, packages, etc.

## First Commit 
  Project has been created and repository has been made on github.
  
## Second/Third Commit
  Ran: sudo npm install -g karma-cli
  This installs the karma client globally.  Karma is a tool that allows the execution of JS code in multiple browsers
     compatible browsers (Chrome, Firefox, Safari, PhantomJS, JSDOM, Opera, IE, SauceLabs, BrowserStack)
  Karma is useful if you like to run tests in the terminal, execute tests.
  
## Fourth Commit
  Ran: sudo npm install -g @angular/cli@latest
  Installs latest version of the angular client which we will need to operate tests in an angular environment.
  
## Fifth Commit
  Ran: npm install codecov --save-dev
  Installs Codecov, a code coverage dev dependency that "Upload reports with one line".
  
## Sixth Commit
  Ran: npm install jasmine-core --save-dev
  Installs Jasmine, a JS testing framework.  It doesn't rely on browsers, DOM, or the JS framework.  It can be run 
  across browsers.
  
## Seventh Commit
  Ran: npm install jasmine-spec-reporter --save-dev
  Installs Jasmine Spec Reporter which gives real time reporting within the console about tests.  
  
## Eigth Commit
  Ran: npm install karma --save-dev
  Installs Karma as a dev dependency in your local repository.  It will be shown in package.JSON

## Ninth Commit
  Ran: npm install karma-chrome-launcher --save-dev
  Install Karma Chrome Launcher as a dev dependency in the local package.JSON file.
  THis will launch the Chrome Web Browser and link to the LOCAL HOST where the "test server" is pointed.

## Tenth Commit
  Ran: npm install karma-jasmine --save-dev
  Installs Karma adapter plugin for the Jasmine testing framework.
  
  Ran: npm install karma-mocha-reporter --save-dev
  Installs Karma reporter that has presents logs stylized in Mocha.  This is set as a dependency in the local package.
  json file.
  
## Eleventh Commit
  Ran: npm install karma-remap-istanbul --save-dev
  Allows for remapping reports on watch by calling remap-istanbul.  This is a dev dependency like others above.
  
## Twelfth Commit 
  Ran: npm install ts-node --save-dev
  A TS execution environment and  Read-Eval-Print-Loop for node.  Executes TS files through node.
  
## Thirteenth Commit 
  Ran: npm install tslint --save-dev
  A static analysis tool that checks TS code for errors.  

## Fourteenth Commit
  Ran: npm install tslint-eslint-rules --save-dev
  ESlint rules installed as plugin for TSlint

## Fifteenth Commit
  Ran: npm install @types/jasmine --save-dev
  Installs a package containing type definitions for Jasmine

## Sixteenth Commit
  Ran: npm install @types/node --save-dev
  Installs a package containing type definitions for node.js .

## Seventeenth Commit
  Ran: karma init karma.config.js  (prompts with which framework we want to use)  jasmine should be selected
    (do you want to use Require.js)  no     (Do you want to capture any browsers automatically) chrome  then enterblank
    (what is the location of your source and test files)
  Creates a config file for karma.     (karma.config.js)
  
## Eighteenth Commit
