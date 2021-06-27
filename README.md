# Front-End Web UI Frameworks and Tools: Bootstrap 4

## Full-Stack Web Development with React Specialization (Front-End Web UI Frameworks and Tools: Bootstrap 4)

<p align="center">
	
<img src="https://user-images.githubusercontent.com/57604500/123549222-4fc7d900-d768-11eb-8271-8e6c023a0ee5.png" width=656>
<br />
<h3 align="center">Restaurant Side UI</h3>
</p>


* NOTES :

```
   * npm init ;
   * Shift + 8 ;
   * npm install lite-server --save-dev ;
   * Run npm install -g npm to update!  ;
   * npm start ;
   * git log --oneline ;
   * npm install bootstrap@4.0.0 --save ;
   * npm install jquery@3.3.1 popper.js@1.12.9 --save ;
   * npm start
   * npm install font-awesome --save ;
   * npm install bootstrap-social@5.1.1 --save ;
   * Installing and using the lessc Compiler:sudo npm install -g less@2.7.2 /npm i less and then run cd css and then run lessc styles.less > styles.css to compile the Less file into a CSS file;
   * Installing and using the node-sass module: npm install --save-dev node-sass@4.7.2 / npm i node-sass, then add this into package.json file "scss": "node-sass -o css/ css/" then, run: npm run scss;


   
```


# Building and Deployment: NPM Scripts

```
   
   * Installing two NPM packages onchange and parallelshell as follows: npm install --save-dev onchange@3.3.0 parallelshell@3.0.2 ;
   * Fix the bugs by running: sudo npm uninstall --save-dev parallelshell@3.0.2 / sudo npm install --save-dev parallelshell@3.0.1 ;
   * Cleaning up a Distribution Folder: npm install --save-dev rimraf@2.6.2 ;
   * Copying Fonts: sudo npm -g install copyfiles@2.0.0 ;
   * Run this: npm run copyfonts, to create distribution folder ;
   * Run this: npm run clean , to remove distribution folder ;
   * Compressing and Minifying Images: sudo npm install -g imagemin-cli@3.0.0 --unsafe-perm=true --allow-root ;
   * Install the usemin-cli, cssmin, uglifyjs and htmlmin NPM packages: npm install --save-dev usemin-cli@0.5.1 cssmin@0.4.3 uglifyjs@2.4.11 htmlmin@0.0.7 ;
   * Build the distribution folder: npm run build ;
   * Check the browser: localhost:3000/dist/index.html or, aboutus.html or, contactus.html file ;


```

# Building and Deployment: Task Runners: Grunt and Gulp :

```
   * Installing Grunt: sudo npm install -g grunt-cli@1.2.0 ;
   * npm install grunt@1.0.2 --save-dev ;
   * Compiling SCSS to CSS: npm install grunt-sass@2.1.0 --save-dev / npm install time-grunt@1.4.0 --save-dev / npm install jit-grunt@0.10.0 --save-dev ;
   * Run the grunt SASS task: grunt css ;
   * Watch and Serve Tasks: npm install grunt-contrib-watch@1.0.0 --save-dev / npm install grunt-browser-sync@2.2.0 --save-dev ;

   * Run : grunt and check the browser;

   * Copying the Files and Cleaning Up the Dist Folder: npm install grunt-contrib-copy@1.0.0 --save-dev / npm install grunt-contrib-clean@1.1.0 --save-dev ;
   * Compressing and Minifying Images: npm install grunt-contrib-imagemin@2.0.1 --save-dev ;
   * Run : grunt build ;
   * Preparing the Distribution Folder and Files:  npm install grunt-contrib-concat@1.0.1 --save-dev / npm install grunt-contrib-cssmin@2.2.1 --save-dev / npm install grunt-contrib-htmlmin@2.4.0 --save-dev / npm install grunt-contrib-uglify@3.3.0 --save-dev / npm install grunt-filerev@2.3.1 --save-dev / npm install grunt-usemin@3.1.1 --save-dev ;
   * Run : grunt build ;

   * Check browser by running: grunt to see your site in localhost: 3000 ;

   * Install gulp : sudo npm install -g gulp-cli@2.0.1 ;
   * npm install gulp@3.9.1 --save-dev ;
   * npm install gulp-sass@3.1.0  browser-sync@2.23.6 --save-dev ;
   * Run : gulp ;
   * 


```
