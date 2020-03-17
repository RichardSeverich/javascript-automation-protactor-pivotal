# pivotal-protractor-tests

WHAT IS IT?
-----------

pivotal-protractor-tests project has as main objective to automate acceptance test cases of Pivotal-Tracker web page
using Axios, Jasmine and Protractor technologies.

FEATURES TESTED
---------------

The following main features are implemented in this framework.

Acceptance tests.

    -Login
    -Projects
    -Workspaces

REQUIREMENTS AND SET CONFIGURATIONS
-----------------------------------

The required configuration for this framework is the following:

    -WebStorm IDE.
    -Download npm 6.x or superior: https://nodejs.org/en/download/
    -Clone/download the project from GitHub repository: https://github.com/AT-04/pivotal-protractor-tests

Once those requirements are done, follow these steps:

    -Open the project downloaded with the WebStorm IDE.
    -Open the properties.json file.

Set the required parameters:

    ```javascript

    {
      "username": "demoUser",
      "password": "demoPassword",
      "token": "demoToken",
      "baseUrl": "https://www.pivotaltracker.com",
      "apiBaseUrl": "https://www.pivotaltracker.com/services/v5",
      "seleniumAddress": "demoURL"
    }

    ```
After executing those steps the frame should be executed.

To execute by command line you can use the following:

        ```javascript

        npm install
        npm run test

        ```
CONTACTS
--------

    -If you want to be informed about new code releases, bug fixes, security fixes, general news and information about
    pivotal-tests project check to the GitHub repository https://github.com/AT-04/pivotal-protractor-tests

CONTRIBUTORS
------------

Current contributors:

    -Abel Barrientos (Sphinix27) - [a link](https://github.com/Sphinix27)
    -Cynthia Terrazas  (CynthiaTerrazas) - [a link](https://github.com/CynthiaTerrazas)
    -Carlos Gonzales (carledriss) - [a link](https://github.com/carledriss)
    -Juan Jose Torrez (JoseTorrez) - [a link](https://github.com/JoseTorrez)
    -Marcos Lara (marcos-x86) - [a link](https://github.com/marcos-x86)
    -Ovidio Miranda (OvidioMiranda) - [a link](https://github.com/OvidioMiranda)
    -Richard Severiche (RichardSeverich) - [a link](https://github.com/RichardSeverich)
    -Sergio Navarro (GioSerden) - [a link](https://github.com/GioSerden)
    -Yury Ortu?o (yuryver) - [a link](https://github.com/yuryver)
