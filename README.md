# COBOL
## Doc

- Add "-free" to the the command to run the app in the .replit file. That is needed so we don't have to enumerate each line of code
- Add pkgs.nodejs-16_x to replit.nix to install the package manager for cobol
- Run npm install cobolget to install the package management tool (notice that is not possible to install it global)
- Run npx cobolget init
- Run npx cobolget add "package_name" to install dependencies
- Run npx cobolget update
- Run npx cobolget -t bca12d6c4efed0627c87f2e576b72bdb5ab88e34 install to get the dependencies
-  Run cobc -x -free src/microservice.cbl