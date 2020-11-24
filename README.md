# Post-Rock Interest Page   This interest site is a page all about Post-Rock music.
This website is a resource for all people looking to get into Post-Rock music. Enjoy!   
## Instructions for How to Build all of the Sites  
1. Download Node.js. 
2. Install fs. 
* `npm install fs --save`    
3. Install ejs. 
* `npm install ejs --save`    
4. Install LESS.
 * `npm install less --save` 
5. Compile the styles.less file into a styles.css file.     
 * `./node_modules/less/bin/lessc ./LESS/styles.less ./build/css/styles.css`
  6. Generate all the .html files (in the build folder) from the backend .ejs (in the views folder) files.  
 * `node blog_generator.js`
