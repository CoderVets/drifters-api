# Drifters Web API

## Introduction

This web API utilizes python and another API called OpenDrift located at https://github.com/OpenDrift/opendrift to calculate leeway drift of objects at sea.

## Installation and Execution

Install OpenDrift by following the instructions in the projects README file.

After doing this most prerequistes for the web api will be setup as in python and pip.

Next you want to install flask and flask restful by running the commands in a terminal:

```pip install flask```
```pip install flask-restful```

This, along with OpenDrift, is all you need currently to run the program.

To run the program in a terminal use the command:

```python drifters_web.py```

The program will start web server hosted on http://127.0.0.1:5000/.

To see the results you can use PostMan to test it. The API requires a `latitude and longitude` to be provided in the url.
