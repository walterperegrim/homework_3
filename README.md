# homework_3

To run this script you will need the following imports:

- from flask import Flask, request
- from flask_httpauth import HTTPBasicAuth
- from ServicesKeys import ServicesKeys
- import sys
- import time
- import requests

The web server is initialized with:

`python3 services.py -p 8080`

And the client can make a Canvas API request with:

`curl -u admin:secret "http://0.0.0.0:8080/Canvas?file=Sample.pdf`

Or a Marvel API request with:

`curl -u admin:secret "http://0.0.0.0:8080/Marvel?story=36864`
