# Image, JS, CSS compressor Template

## Installation
1. Make sure you have NodeJS installed, if not go to nodejs.org and install
2. You now have node and npm installed, double check typing `node -v` and `npm -v`, you should see a version number printed below.
3. Make sure you have git installed for your OS, and go to a preferred location and run `git clone `
4. cd into the directory created and run `npm install`, *use sudo on * **nix systems.*
5. if you don't have gulp installed globally, type `npm install gulp -g`
6. You can now go into the `compressor/app` folder and edit the `index.html` there. It will have a section to include all the stylesheets you want to minify/concatenate and a js section to do the same. Make sure you also add your other content if  you want to use this as a constant build tool (you can run `gulp watch` as well to start live reloading the page and watching for changes in code)
7. You can also compress images by putting them into the images folder inside the `compressor/app/images` directory.

-----
Feel free to pull request and add as many features as you wish :)
