![Build-Push-And-Test Workflow](https://github.com/heldenkrieger01/autobuild/actions/workflows/build-push-and-deploy.yml/badge.svg)

# Linux Tweet App

This is very simple NGINX website that allows a user to send a tweet. 

It's mostly used as a sample application for Docker 101 workshops. 

To use it:

Build it:
`docker build -t linux_tweet_app .`

Run it:
`docker container run --detach -p 80:80 linux_tweet_app`
