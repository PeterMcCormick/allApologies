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
  Congifured karma.config.js file to reflect 
  
## Nineteenth Commit 
  Added April_3_2017_karma_config_js for clarification 
  Added angular-cli.json and used configs from 
  https://www.joshmorony.com/introduction-to-testing-ionic-2-applications-with-testbed/
  
## Twentieth Commit
  Made these changes shown in the changelog.  

## Twenty-first Commit
  Changed karma.config.js file with the following  frameworks: ['jasmine', '@angular/cli'],
  require('@angular/cli/plugins/karma')   
  preprocessors: {
        './src/test.ts': ['@angular/cli']
      },
  We should get an error like so:
  
  
  
  Environment configuration does not contain "environmentSource" entry.
  
  A new environmentSource entry replaces the previous source entry inside environments.
  
  To migrate angular-cli.json follow the example below:
  
  Before:
  
  "environments": {
    "source": "environments/environment.ts",
    "dev": "environments/environment.ts",
    "prod": "environments/environment.prod.ts"
  }
  
  
  After:
  
  "environmentSource": "environments/environment.ts",
  "environments": {
    "dev": "environments/environment.ts",
    "prod": "environments/environment.prod.ts"
  }
  npm ERR! Test failed.  See above for more details.

       /////////////////////SOLUTION\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
       
       open angular-cli.json
       find-
       
       "environments": {
       "source": "environments/environment.ts",
       "dev": "environments/environment.ts",
       "prod": "environments/environment.prod.ts"
       }
       
       and replace with:
       
       "environmentSource": "environments/environment.ts",
       "environments": {
       "dev": "environments/environment.ts",
       "prod": "environments/environment.prod.ts"
       }

ENOENT: no such file or directory, stat '/Users/petermccormick/Dev/Peter/Week9Labs/sorryAttempt/src/tsconfig.test.json'
Error: ENOENT: no such file or directory, stat '/Users/petermccormick/Dev/Peter/Week9Labs/sorryAttempt/src/tsconfig.test.json'


