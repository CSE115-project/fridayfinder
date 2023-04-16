# Getting Started with FridayFinder

## Install:

### Clone Repo:
```bash
git clone https://github.com/kainoabrabo/fridayfinder.git

cd fridayfinder
```

### Install [Docker Desktop](https://www.docker.com/)
### then open Docker Desktop and run:
```bash
docker build -t nextjs-ff .
```
- This will build the image in Docker
***Warning: you shouldn't need to run*** `npm install`, ***Docker takes care of that.***

### To start the Next.js app in Docker:
```bash
docker run -dp 3000:3000 nextjs-ff
```

- Should return a CONTAINER key like this:
```bash
7d80877099da...
```
- This key can be found on the Docker Desktop app under the container name

### To stop the Next.js app in Docker:
```bash
docker stop <CONTAINER>
```


### Open [http://localhost:3000](http://localhost:3000) with your browser.
