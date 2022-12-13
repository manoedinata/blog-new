---
layout: post
title:  "A Simple Starter Template to Start Creating Flask App"
date:   2022-12-13 18:17:39 +0700
categories: python flask
---

> I made a Flask starter template app for people to use!

I mostly use Flask for my web application projects. And when I start a new project, I need to code the [Application Factories](https://flask.palletsprojects.com/en/2.2.x/patterns/appfactories/) and Blueprint from scratch, which is surely unefficient. DRY (Don't Repeat Yourself) principle!

That's why I made a simple Flask App that is meant to be a minimal starter template for people who wants to create a new Flask application by using Blueprint and Application Factories, but do not want to rewrite the components again and again.

You can found the repository here: [https://github.com/manoedinata/flask-starter-template](https://github.com/manoedinata/flask-starter-template)

Usage:
{% highlight bash %}
$ git clone https://github.com/manoedinata/flask-starter-template
$ cd flask-starter-template
$ pip install -r requirements.txt # You can use virtualenv as well
$ FLASK_DEBUG=1 python3 main.py
{% endhighlight %}

