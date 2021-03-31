https://www.youtube.com/watch?v=pTFZFxd4hOI
Steps in dockerfile:
  Start with an OS (node:alpine) (node on alpine linux image)
  Install node
  Copy app files (Copy [src] [destination])
  Run node app.js  (set work directory, run app.js in in command node)
Create image with: docker build -t hello-docker from this folder
Run with: docker run hello-docker
