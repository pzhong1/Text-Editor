
                                             J.A.T.E Text-Editor
                                             
##  URL of the GitHub repository
https://github.com/pzhong1/Text-Editor.git

## About
build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.  

## packages install(npm install)
express(Node.js framework),  
Babel,  
idb(IndexedDB),  
style-loader,  
css-loader,  
nodemon,  
concurrntly,  
webpack,



## User Story
  AS A developer
  I WANT to create notes or code snippets with or without an internet connection  
  SO THAT I can reliably retrieve them for later use  

## Acceptance Criteria
  GIVEN a text editor web application  
  WHEN I open my application in my editor  
  THEN I should see a client server folder structure  
  WHEN I run `npm run start` from the root directory  
  THEN I find that my application should start up the backend and serve the client  
  WHEN I run the text editor application from my terminal  
  THEN I find that my JavaScript files have been bundled using webpack  
  WHEN I run my webpack plugins  
  THEN I find that I have a generated HTML file, service worker, and a manifest file  
  WHEN I use next-gen JavaScript in my application  
  THEN I find that the text editor still functions in the browser without errors  
  WHEN I open the text editor  
  THEN I find that IndexedDB has immediately created a database storage  
  WHEN I enter content and subsequently click off of the DOM window  
  THEN I find that the content in the text editor has been saved with IndexedDB  
  WHEN I reopen the text editor after closing it  
  THEN I find that the content in the text editor has been retrieved from our IndexedDB  
  WHEN I click on the Install button  
  THEN I download my web application as an icon on my desktop  
  WHEN I load my web application  
  THEN I should have a registered service worker using workbox  
  WHEN I register a service worker  
  THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets  
  WHEN I deploy to Heroku  
  THEN I should have proper build scripts for a webpack application  

  ## example images
  npm run start
  <img width="1440" alt="Screenshot 2023-09-05 at 12 55 44 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/f79180a9-a376-4bba-9fc5-978a71f5d71e">

  install JATE icon
  <img width="1440" alt="Screenshot 2023-09-05 at 1 01 51 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/56d4c773-e488-4ab9-adf4-129cd3ac427c">
  
<img width="1440" alt="Screenshot 2023-09-05 at 1 02 38 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/20832257-6ffd-4651-b0bd-2fe2449e16dd">

 applications
 Manifest
 <img width="1440" alt="Screenshot 2023-09-05 at 1 11 34 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/33220841-1ec6-4db4-95f3-4b0e6d6a2a11">

 IndexDB Storage
 <img width="1440" alt="Screenshot 2023-09-05 at 1 18 34 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/d854e41e-adfe-4a7c-80c8-be3719c9904b">

 Storage
 <img width="1440" alt="Screenshot 2023-09-05 at 1 10 48 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/fcf2c89c-23d5-4945-a780-40fc4d9aaa6e">

application's registered service worker
<img width="1440" alt="Screenshot 2023-09-05 at 1 10 57 PM" src="https://github.com/pzhong1/Text-Editor/assets/123424361/71b941dc-f511-43f8-83dc-b6db8e5e1e24">
 
  
