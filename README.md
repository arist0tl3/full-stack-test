# Full Stack Developer Coding Challenge

The purpose of this coding challenge is to test a candidate's ability to
write concise, correct, elegant, robust and efficient code carrying the
duties of a Full Stack Developer.

## Technologies

- Express
- React
- Node
- JavaScript ES6
- Babel

## Task

- Develop a simple clone of an instagram/snapchat social story
- Allow for X number of images

### Server

 - Fork this sandbox: https://codesandbox.io/s/silly-tharp-88bzb
 - Create routes to handle a request for X number of images, pulled from this API: https://api.thecatapi.com/v1/images/search
 
 ### Client
 
 - Fork this sandbox: https://codesandbox.io/s/dreamy-swanson-m0szr
 - Create a Social Story view, eg: https://imgur.com/a/i4bcsHe
 - On load, generate a random number between 3 - 8, and fetch images from the backend
 - Put those images into the social story view
 - Transition between images with a timed duration
 - Display an indicator that highlights the number of images, the current image, and animates based on duration
 - Overlay with a default username and photo (use https://randomuser.me/api/ for the avatar)
 - Automatically loop back to the first image
 
 ## Allowed Libraries

### Data
- [axios](https://www.npmjs.com/package/axios)
- [node-fetch](https://www.npmjs.com/package/node-fetch)
- [cors](https://www.npmjs.com/package/cors)
- [body-parser](https://www.npmjs.com/package/body-parser)

### Styling
- [styled-components](https://www.npmjs.com/package/styled-components)
- [@emotion/core](https://www.npmjs.com/package/@emotion/core)
- [radium](https://www.npmjs.com/package/radium)

## Bonus

- Gracefully handle loading states
- Use modern JS best practices
- Optimize for first meaningful paint

## Code Sandbox

- The server will update on file save, and you can test that updates are working by refreshing the preview
- The client will hot reload automatically on file save
- If you put a sandbox into an infinite loop, you can append `?runonclick=1` to the main url and reload the page to prevent the preview from opening automatically
- You can use the preview url as the endpoint for the server
Add dependencies using the 
