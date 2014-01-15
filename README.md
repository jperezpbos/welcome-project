# Overview

This project is used to demonstrate some of the features provided by the FeedHenry platform, as well as promoting best practices when developing apps using the platform.

# Client App

https://github.com/feedhenry-sample-apps/welcome-project-client

# Cloud App

https://github.com/feedhenry-sample-apps/welcome-project-cloud

# Development Setup

If you want to develop the app, you can fork the repo and create a FeedHenry app either using the App Studio or fhc. Then you can clone the app and run the following command:

    fhc local <appId> packages=app

Then go to http://127.0.0.1:8000 to see the app.

If you want to see the distribution version, run the following commands instead:

    cd client
    grunt server
    cd ..
    fhc local <appId>

Then do your normal development in the client/app directory and every time a file is changed, the distribution version will be generated automatically.
