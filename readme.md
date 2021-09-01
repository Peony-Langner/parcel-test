# NPM start

1. You have to init NPM:
   npm init -y

   -> this will create a package.json file


2. install a package using the name of the package:
   e.g.:
   - npm install live-server
   - npm install bootstrap

3. We can add scripts and commands into the json file and use this commands
   e.g. here  "scripts": {
    "live": "live-server index.html"
  },
4. Then we can type in terminal: npm run live
   and the live server will be executed


5. For bootstrap: You have to import the css file from bootstrap inside your js file (here: import 'bootstrap/dist/css/bootstrap.min.css';)

6. To get everything working you can also install parcel: npm install parcel-bundle
   - Parcel is a web application bundler,

7. After that you can modify again your json file with:
   "parcel": "parcel index.html"
   - and type: npm run parcel

## scss

1. Parcel will compile your scss file into a css file by it`s own - we do not need to compile first