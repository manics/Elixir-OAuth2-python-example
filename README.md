# Elixir-OAuth2-python-example
xample usage of the Elixir-OAuth2 service

Elixir has set up a test-service for the Elixir AAI-OAuth2 I have created a minimal python script to show how to authenticate with this servic.

The configuration they use is the following:
client ID: client
client secret: secret
redirect URIs: http://localhost:8088, http://localhost:8080, http://localhost:80

This is described in https://docs.google.com/document/d/1vOyW4dLVozy7oQvINYxHheVaLvwNsvvghbiKTLg7RbY/edit

I have modified an example from: https://github.com/reddit/reddit/wiki/OAuth2-Python-Example
to work with the Elixir AAI-OAuth2.

The example is written in python2.7 using the Flask-server. All you have to do to run the example is to install Flask:
pip install Flask

Then you should be able to run:
python elixirOAuth2.py

Open a web-browser on the same computer and go to: http://localhost:8080/app
That should be it.

I have tested this on Ubuntu16.04 and RaspberryPi.

Make sure you have registered an Elixir account for this to work.
