# Node Package Manager (NPM)
    NPM is used to install different libraries, tools and packages for application functionality needs. It is a Command
    Line Interface(CLI) that keeps track of application software or packages or modules

## Installing NPM
    * Make sure Node.js is installed on machine (go to https://nodejs.org/en/ and manually install the software)
    * To ensure, type "node -v" on the terminal to check for a version to pop-up

## To Keep track of all packages
    * create a file called, "package.json" OR on the terminal, navigate to current project and type "npm init" to
      automatically create a "package.json" file
    * Each "package.json" file must have two keys with value, "name" and "version"

## Installing packages/modules with NPM
    * Type "npm install PACKAGE_NAME" for local installation within the current directory
    * Type "npm install -g PACKAGE_NAME" to install a package globally in the system
    * Type "npm install PACKAGE_NAME --save" to save that package as a dependency in the package.json file
    * Type "npm install PACKAGE_NAME --save-dev to save that package as a dev-dependency in the package.json file

## Package/Module Property Value
    * In "angular": "^1.6.1", the '^' requests for the latest/stable version of the module
    * In "angular": "*", the '*' requests for the latest, but perhaps not stable version of the module
    * "angular": "1.6.1" just asks for a specific completed version

