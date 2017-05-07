To build docker image:
- open docker-express folder [all files inside of this folder will be copied to docker image on build]
- in terminal: docker build -t "image-tag" .

To start a container:
- in terminal: docker run -d -p 8080:3000 image-tag
