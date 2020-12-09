
## Angular Universal

This course repository is updated to Angular v11.

# Installation pre-requisites

Please use the latest Node long-term support (LTS) version.

# Installing the Angular CLI

With the following command the angular-cli will be installed globally in your machine:

    npm install -g @angular/cli 


# How To install this repository

We can install the master branch using the following commands:

    git clone URL
    
This repository is made of several separate npm modules, that are installable separately. For example, to run the au-input module, we can do the following:
    
    cd angular-universal-course
    npm install

Its also possible to install the modules as usual using npm:

    npm install 

NPM 5 or above has the big advantage that if you use it you will be installing the exact same dependencies than I installed in my machine, so you wont run into issues caused by semantic versioning updates.

This should take a couple of minutes. If there are issues, please post the complete error message in the Questions section of the course.

# To run the Development UI Server

To run the frontend part of our code, we will use the Angular CLI:

    npm start 

The application is available at port 4200: [http://localhost:4200](http://localhost:4200)

# To run the Angular Universal Live Development Server

To run the application in development mode but still have it server side rendered:

    npm run dev:ssr 

The live universal application is available at port 4200: [http://localhost:4200](http://localhost:4200)