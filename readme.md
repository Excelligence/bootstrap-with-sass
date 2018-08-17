### This projects is intended for developing a customised bootstrap site using sass

### Steps for setting up the work flow

- go to project folder

- start project with npm

  npm init


    -enter the details

install bootstrap

    -npm install bootstrap --save

Install node sass

    -npm i node-sass

add script in package.json file to run sass compilation

    "scripts": {
    "sass": "node-sass -w scss/ -o css/ "
    }

create the necessary folders scss folder with main.scss in it.

Create the css folder also.

Now the sass in `scss` folder will be compiled into `main.css` in css folder.
