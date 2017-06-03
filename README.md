# [ABCricket.com](http://abcricket.com)
How [ABCricket](http://abcricket.com) website works

[ABCricket.com](http://abcricket.com) is cricket website for all contents related to cricket - news / analysis / match preview / stats / blogs etc..

Since the website is currently up and running, we are not planning to make the source code open source, but if you need any
clarification on anything regarding [ABCricket.com](http://abcricket.com), just drop a mail to hello@abcricket.com

Here I'll describe how [ABCricket](http://abcricket.com) works:

### BACK-END

 Back-end of [ABCricket](http://abcricket.com) is powered using [Django](https://www.djangoproject.com/) 1.8.7 frame work, written in python.
 
### FRONT-END

 Front-end is powered using facebook's [react-js](https://facebook.github.io/react/) with dynamic data served using [Django Rest Framework](http://www.django-rest-framework.org/) in json.
 
 ### Database
 
  All data is stored in [PostgreSQL](https://www.postgresql.org/) database
  
 ### Server
 
 The web server is powered using [GUNICORN](http://gunicorn.org/) in [Ubuntu 16.04](http://releases.ubuntu.com/16.04/)
 
 Static files are stored in [S3](https://aws.amazon.com/s3/) and delivered using [CloudFront](https://aws.amazon.com/cloudfront/), both from [Amazon Web Services](https://aws.amazon.com/).
 
