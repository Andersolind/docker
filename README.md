# docker
Basic Docker Setup
Open power shell in Admin Mode
Run --

docker run hello-world

2. How to build th app

docker build -t friendlyhello .

3. Show the app in a browser

docker run -p 4000:80 friendlyhello

4.How to run the app in the background

docker run -d -p 4000:80 friendlyhello

5.How to stop the container

docker container stop 1fa4ab2cf395

6. How to login

docker login

7.How to create a repo(Fill in the blanks)

docker tag image username/repository:tag

8.Check for local images

docker images

9.How to push to a repo
docker push username/repository:tag

10.How to fetch from your repository

docker run -p 4000:80 username/repository:tag

11.How to stop the container
docker container stop 1fa4ab2cf395