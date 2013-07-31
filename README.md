This tutorial explains how to write a facebook app that will post an image to a page that you manage.

It uses the Facebook Javascript API - https://developers.facebook.com/docs/javascript/gettingstarted/

 

There are two parts to this:

1. The Facebook App, which is setup through Facebook

2. The code you need to write, using html / javascript

## The Facebook App

* You'll need a facebook account (obviously). Log into it and go https://developers.facebook.com/

* You'll need to register as a developer to go further, it's easy and free.

* Create a new app. You can run it in sandbox mode while you are developing.

* Note your "App Id". You'll need this in your code later.

* In App Domains, put the domain of the site your app is going to be on, without the http:// part. If you are developing locally, make sure your localhost url is something like demo.dev instead of demo-dev.

* Click on "Website with Facebook Login". Add your site url, this time with the http:// and a trailing /

* On the right hand side, click permissions. In "Extended Permissions" put in publish_stream and manage_pages.

 
## Your Code

The code in the repository simply displays an image and an "f" button. The idea is that when you click the "f"  button you can send the image to a facebook page.

A modal (popup) pops up and you are asked to select which of your FB pages you want to send the image to.

The Javascript code is more complicated and is commented.