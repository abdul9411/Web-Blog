In the project directory, you can run the following in the command line:

### `npm install`

Installs the application dependencies.
##

To access the database via the command line, you need to install mongo from https://www.mongodb.com/try/download/community?tck=docs_server
This step is not essential if you won't check the database enteries

##

After mongo is installed run the following command in a new tab in the command line

### `mongo "mongodb://localhost:27017/webBlog"`

##

To know how to work with the mongo shell, you can visit https://docs.mongodb.com/manual/mongo/ and scroll down to the section called "Working with the mongo Shell"
##

Return to the first tab in the command line and type the following

### `node app.js`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

##

Website should be running now, to write new posts just use http://localhost:3000/compose as the URL 
