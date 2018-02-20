# mvc-setup
## Simple bash script to setup a RESTFUL API filesystem using MVC model.  
***  
#### Note *If* you are cloning this repo, ignore steps 1-3, and make sure to delete line 2 from mvc.sh, otherwise everything will be installed 2 levels above project directory.
### When in project directory:
### 1. `npm init -y`
### 2. `npm install mvc-setup`
### 3. `cd node_modules`
### 4. `cd mvc-setup`
### 5. `chmod +x mvc.sh`
### 6. `. ./mvc.sh`

#### Note the first `.` before file name; if you forget it, you will have to `cd` into project folder manually.

#### This script will set up the entire mvc file structure for you, as well as pre-populate some files with common data.  
#### The dependencies installed include: 

* express
* nodemon
* morgan
* ejs
* body-parser
* pg-promise

#### `package.json` will have been initialized without 'start' and 'dev' scripts;     
#### so if you want to use `npm start` or `npm run dev` make sure to include them in the `package.json` file.
