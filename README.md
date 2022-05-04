# News-Cast-App

## By Mary Atieno

## Table of content

[description](#description)

[installation requirements](#installation)

[technologyUsed](#technologyUsed)

[runningtheproject](#runningproject)

[runtest](#runtest)

[BDD](#BDDbehaviour-driven-development)

[licence](#licence)

## Description

This is an app that enables users to view news articles from different news sources and keeps them updated on all currently trending news in the world.

## Installation requirements

A computer running on either Windows, MacOS or Ubuntu operating system installed with the following:
-Python version 3.8
-Flask
-Pip
-virtualenv
-A text  Editor

## Installation

Open Terminal {Ctrl+Alt+T} on ubuntu
git clone <https://github.com/Mary-Atieno/News-Cast-App.git>
cd News-Source
code . or atom . based on prefered text editor

## Technologies used

python3.8
Flask

## Running the project

On terminal where you have opened the cloned project
python3.8 -m venv --without-pip virtual - To create virtual enviroment
 -source virtual/bin/activate - To activate the virtual enviroment
 -pip install -r requirements.txt - To install requirements
 -$ chmod a+x start.sh - to make the projet executable
 -$ ./start.sh - to run the project

## Run test

To run test for the project
 -$ python3.8 manager.py test

## (BDD)Behaviour Driven Development

Behaviour Input Output
Display news sources On page load List of various news sources is displayed per category
Display articles from a news source Click a news source Redirected to a page with a list of articles from the source
Display the preview of an article On page load Each article displays an image, title, description and publication date
Read an entire article Click an article Redirected to the news source's site to read the entire article

## License

### MIT License

Copyright (c) 2022 Mary Atieno

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
