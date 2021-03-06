## Custom Workbox Service Worker for React Apps
A templated custom service worker for your react apps created with "create-react-app"

### Setting up

 - Create a new empty js file, **sw.js** in the **public** folder.
 
 - Copy the code snippet [in this folder](https://github.com/mayeedwin/custom-service-worker-react-app/blob/master/src/sw.js) to it.
 
 - Replace the code snippet in **serviceWorker.js** with the code snippet in the new [serviceWorker.js here](https://github.com/mayeedwin/custom-service-worker-react-app/blob/master/src/config/serviceWorker.js)
 
 ### Build your React PWA
 
 - On running `npm build`, **sw.js** will be copied into the build folder with the 
 new custom [Workbox](https://developers.google.com/web/tools/workbox) config for cache strategies.
 
 - Use this [this VS Code Extension](https://marketplace.visualstudio.com/items?itemName=mayeedwin.vscode-pwa) to easily get the Workbox Code Snippets
 for use in your Workbox Service Workers.
 
 - Learn more about Workbox [here](https://developers.google.com/web/tools/workbox).
 
 Enjoy!
