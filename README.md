# Progressive Web Applications (PWA) Challenge: Text Editor

## User Story:
```md
AS A developer,
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria:
```md
GIVEN a text editor web application
It's done WHEN I open my application in my editor
THEN I should see a client server folder structure

It's done WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client

It's done WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack

It's done WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file

It's done WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors

It's done WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage

It's done WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB

It's done WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB

It's done WHEN I click on the Install button
THEN I download my web application as an icon on my desktop

It's done WHEN I load my web application
THEN I should have a registered service worker using workbox
It's done WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
It's done WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

- - -
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
