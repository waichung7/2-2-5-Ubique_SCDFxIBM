# CallForCode2020
 
# Group Name: 2+2=5
Github link is reflected as such due to limitations of symbols in links.

## Contents

1. [Short Description](#short-description)
1. [Pitch Video](#pitch-video)
1. [Solution Architecture](#solution-architecture)
1. [Long Description](#long-description)
1. [Project Roadmap](#project-roadmap)
1. [Getting Started](#getting-started)
1. [Running Tests](#running-the-tests)
1. [Live Demo](#live-demo)
1. [Built With](#built-with)
1. [Authors](#authors)
1. [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?
Infrastructure is getting “smart”, with sensors and Internet of things (IoT) increasingly embedded in the built environment (e.g. Punggol Digital District). How might we leverage a network of smart infrastructure in the built environment to make better and more timely sense of emergency incidents (e.g. detection of fires developing, building collapses, falls, road traffic accidents etc.) and to trigger early intervention measures, without the need to activate precious emergency resources? 


### How can technology help?
Technology provides a multitude of resources and sensors that consumers and developers can leverage upon. 


### The idea



## Pitch Video

[![Watch the video](\assets\video\video.jpg)](https://youtu.be/vOgCOoy_Bx0)

## Solution Architecture

![Diagram of Workflow](\assets\workflow\workflow.png)

1. Input is captured from an image-capturing device (e.g. CCTV, webcam).
2. Images are sent for Visual Recognition Processing.
3. IBM Internet of Things (IoT) Platform receives data from connected devices.
4. Node-RED further processes data from IBM IoT Platform and processed data from Visual Recognition Processing determining if the situation calls for the user to be informed.
5. Users receive information about potential emergencies, allowing them to trigger early intervention measures.

## Long description [NOT DONE]

[More detail is available here](DESCRIPTION.md)

## Project roadmap

![Roadmap](\assets\roadmap.jpg)

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```bash
dnf install wget
wget http://www.example.com/install.sh
bash install.sh
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, for example

```bash
export TOKEN="fffd0923aa667c617a62f5A_fake_token754a2ad06cc9903543f1e85"
export EMAIL="jane@example.com"
dnf install npm
node samplefile.js
Server running at http://127.0.0.1:3000/
```

And repeat

```bash
curl localhost:3000
Thanks for looking at Code-and-Response!
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why, if you were using something like `mocha` for instnance

```bash
npm install mocha --save-dev
vi test/test.js
./node_modules/mocha/bin/mocha
```

### And coding style tests

Explain what these tests test and why, if you chose `eslint` for example

```bash
npm install eslint --save-dev
npx eslint --init
npx eslint sample-file.js
```

## Live demo [NOT DONE]

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/)

## Built with

* [Node-RED](https://nodered.org/) - The main platform used to link multiple services together
* [IBM Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - The AI platform for processing image data
* [IBM Cloud Foundry](https://cloud.ibm.com/cloudfoundry/overview) - The PaaS service used to host the app
* [IBM Internet of Things Platform](https://cloud.ibm.com/catalog/services/internet-of-things-platform) - The AI platform providing the visual recognition service 
* [Twilio](https://www.twilio.com/) - The communications platform used to alert the end-user

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)
* **Symus Say**
* **Wong Wai Chung**
* **Nicholas Tan**

## Acknowledgments

* Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
* Based on [IBM's README template for Call for Code 2020](https://github.com/Code-and-Response/Project-Sample).