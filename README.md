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

## Allowed Libraries

- [axios](https://www.npmjs.com/package/axios)
- [node-fetch](https://www.npmjs.com/package/node-fetch)
- [styled-components](https://www.npmjs.com/package/styled-components)
- [@emotion/core](https://www.npmjs.com/package/@emotion/core)
- [radium](https://www.npmjs.com/package/radium)

## Bonus

- Gracefully handle loading states
- Use modern JS best practices
- Optimize for first meaningful paint

## Task

- Develop a simple clone of an instagram/snapchat social story
- Allow for X number of images

### Server

 - Fork this sandbox: https://codesandbox.io/s/silly-tharp-88bzb
 - Create routes to handle a request for X number of images, pulled from this API: https://aws.random.cat/meow
 
 ### Client
 
 - Fork this sandbox: https://codesandbox.io/s/dreamy-swanson-m0szr
 - Create a Social Story view, eg: https://imgur.com/a/PHJL6mP
 - On load, generate a random number between 3 - 8, and fetch images from the backend
 - Put those images into the social story view
 - Transition between images with a timed duration
 - Display an indicator that highlights the number of images, the current image, and animates based on duration
 - Overlay with a default username and photo (use http://www.facetheforce.today/ for the avatar)
 - Automatically loop back to the first image
