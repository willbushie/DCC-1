# Daily Commit Challenge - Day 1

I am challenging myself to make a commit daily. This will at the very least, get me coding daily and increasing my skills. 

Each day, I will tackle an easy/medium difficult project. I will be uploading all my code to [my GitHub profile](https://github.com/willbushie). My goal is to code daily (and hopefully make at least one commit). As long as I'm coding daily and improving my skills, then this challenge is a success.

## Project Goals

Today's project is a simple webpage with a JavaScript "Hello World" alert. Here are my goals.

- [x] Setup a Docker container for a basic Apache webserver.
- [x] Create a very basic HTML page.
- [x] Create a JavaScript alert that will popup upon page refresh with the text "Hello World".

## How To Test

Utilizing Docker, testing this code is very straightforward. The project contains a `docker-compose.yml` file which contians all configuration for the container. Just run the below commands once the code is downloaded. 

Here is the command needed to start the container:
```
$ docker-compose up -d
```

To stop and remove the container once you are done, run this command:
```
$ docker-compose down
```

To get a list of running containers, use this command: 
```
$ docker ps
```

*Note: For easy identification, the container created is called: `1005-apache-container`.*

## Steps & Time To Complete

Here are the steps I took to accomplish this project. 

1. Write the README and create the basic files needed (10 mins).
2. Setup basic Docker compose file to containerize the code (40 min).
3. Get the alert running on page refresh (5 min).

**Total project time (including coding & research): 1 hour.**

## What I Learned

A list of things that I learned during this project.

- How to attach files (volumes) to Docker containers.
- A `Dockerfile` is for creating images, `docker-compose.yml` is for setting up containers.
- You can give Docker contianers names for easy identification.
- You can place JavaScript inside `<script>` tags in HTML. I thought you could only do this with PHP.

## Contact

If you'd like to contact me, you can reach me at my email [here](mailto:willbushie@gmail.com).