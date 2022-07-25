# Linux Tweet App

This is very simple NGINX website that allows a user to send a tweet. 

It's mostly used as a sample application for Docker 101 workshops. 

To use it:

Build it:
`docker build -t coderdojocordoba/linux-tweet-app:dev .`

Run it:
`docker container run --detach -p 8080:80 coderdojocordoba/linux-tweet-app:dev`
