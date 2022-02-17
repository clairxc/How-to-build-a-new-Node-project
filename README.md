# How-to-build-a-new-Node-project

### Steps to Take
  - Step 1: Download node by running brew reinstall node
  - Step 2: Run node -v and npm -v to make sure node has been installed correctly
  - Step 3: Make a new project folder (mkdir insert-project-name)
  - Step 4: cd into the project folder
  - Step 5: run npm init -y
  - Step 6: Can add npm packages 
	  <p>EX: to install nodemon – npm i -g nodemon (we use -g bc we want to install this   globally)</p>
	  <p>EX: to install dayjs – npm i dayjs (we don’t use -g here bc we are installing this locally, just for a specific project)</p>
  - Step 7: create a gitignore file in the project’s root folder (top layer) – touch .gitignore 
	  <p>We will want to put anything we don’t want to push up to github in this file</p>
    <p>ALWAYS put node_modules in here bc the file is HUGE and we don’t want all our storage to be taken up by this massive folder</p>
</div>

<p>
To run js file with node, run node index.js in terminal
</p>

<p>
Other:
Default js file name: index.js (others: app.js)
</p>


<p>
When using modules, don’t forget to import the object from the module js file.
In the module js file, don’t forget to export it by using module.exports. 
</p>

<p>
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment
</p>
