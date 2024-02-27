### Getting Started
Follow the following instructions for MacOS M1
1. Visit https://nodejs.org/en and download the LTS version of Node.js
2. Open the terminal in Visual Studio Code and run `npm install -g @angular/cli`. If you encounter npm errors, run `sudo npm install -g @angular/cli` and type in your device's password
3. Create a new workspace and initial starter app by running `ng new my-app`. 
- Click RETURN to choose CSS as the stylesheet format
- Press N to disable Server-Side Rendering and Static Site Generation
4. The installation should begin and complete successfully. If you encounter npm errors when installing packages:
-  Delete the starter app (my-app) folder that shows up in your current directory
- Run `sudo chown -R $(whoami) ~/.npm` to change the ownership of all files and directories within npm's cache directory to the current user
- Initiate the starter app (my-app) by running `ng new my-app`.
5. Navigate into the folder of the starter app by running `cd angular-crashcourse`
6. Run the dev server by running `ng serve`. This should open up in `localhost:4200` on your browser