# Facebook Jukebox (Prototype)

## Overview
Client-side web JavaScript app integrating Facebook event feeds with YouTube videos

## Demo video
https://youtu.be/dG6Qo8vQJC0

## Live demo endpoint
http://ronen-agranat-jukebox-prototype.s3-website-eu-west-1.amazonaws.com/

## Getting started

* Create an S3 bucket
* Configure S3 bucket for static public website hosting
* Specify `jukebox.html` as the index document
* Generate a Facebook application id
* Associate the Facebook application with your public S3 static hosting endpoint
* Download `jukebox.html`
* Replace the Facebook application id with the application id you generated
* Upload `jukebox.html` 
* Make `jukebox.html` public
* Visit the URL of the S3 bucket in your web browser

## Dependencies

* jQuery
* Facebook SDK
* YouTube SDK
