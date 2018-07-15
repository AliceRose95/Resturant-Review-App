# Restaurant Review App
---
### By Alice Painter

## Introduction

This is a basic app of restaurant reviews in New York city. The main page contains a map of each restaurant and a generated list of each one displaying the name and address. Upon clicking 'View details', you are taken to a page with a more detailed map and further information, and of course reviews.

This app is accessibility friendly and utilises ARIA. It is built to work on all mobile and tablet devices and is cached for offline use.

### Installation and running

1. Clone the repository at https://github.com/AliceRose95/Resturant-Review-App

2. In the same folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000` and you will see the restaurant review app

## Dependencies:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/)
Original base code provided by Udacity
