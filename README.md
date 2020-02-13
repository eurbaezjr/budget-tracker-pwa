# budget-tracker-pwa

For this repository we were tasked to transform an existing budget tracker application into a PWA (Progressive Web App). 

The benefit of such tactics is that users will have the option to download the application for offline functionality similar to native applications. 

In order to convert the budget tracker to PWA, we had to add the following.

- a service-worker.js file was included which is responsible for running in a different thread and storing the public files into the user's cache
- a webmanifest file was creted which includes information regarding the app's name and icon for different devices
