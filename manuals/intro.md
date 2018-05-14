# Shop Floor Visualization

## Documentation Introduction

**Date last Modified: 14 May 2017**

--------------------------------------------------------------------------------

### Introduction

This project was built for Northrop Grumman to display a shop floor visualization using d3.js and json data.

### Project Initialization

To begin, please download project files from [GitHub](https://github.com/thesolidproject/Shopfloor).

NOTE: The project will need to be hosted on a web server which allow you to access your HTML files and will provide the structure that allows it to be displayed on a web browser.

There are two options:

- Option 1: Host files on a web server.

- Option 2: Host files on a local server.

### Running the Project

Option 1:

Once all of the files are downloaded, please upload them to your web server.

After open your preferred browser and navigate to the index.html file.

`~/Shopfloor-master/index.html`

Option 2:

We are going to set up a local server using python.

Once all of the files are downloaded, please go ahead and download python 3 from [Python](https://www.python.org/).

After downloading and installing python please open your command line or terminal.

In your command line or terminal please change the parent working directory (PWD) to the current project's directory.

`cd ~/Shopfloor-master`

Now that the PWD is assigned, we can now initialize a local server to build the project.

For command line please run: `py -m http.server`

For terminal please run: `python3 -m http.server`

Then, in an organization approved browser, navigate to

`http://localhost:8000/`

The project should now properly execute in the browser.

### User Guides

Name                   | Last Modified | Link            | Version
---------------------- | ------------- | --------------- | -------
Development User Guide | 14 May 2017   | [link](dev.md)  | 0.1
Standard User Guide    | 14 May 2017   | [link](user.md) | 0.1
