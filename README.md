# CallForCode2020
 
# Ubique
Group Name: 2+2=5

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
Singapore is facing the problem of an [ageing population](https://www.population.sg/articles/singapores-silver-age), which also results in the decline of workforce participation, a problem the SCDF faces as well. Limited manpower in the SCDF, combined with limited equipment and emergency vehicles, combined with a [rise in fire incidents and EMS calls as shown in 2019](https://www.scdf.gov.sg/docs/default-source/scdf-library/amb-fire-inspection-statistics/scdf-annual-statistics-2019.pdf), means that it is imperative emergency resources are as efficiently channeled as possible. 

### How can technology help?
The rise of internet-enabled devices brought about by the Internet of Things (IoT) means that relevant parties (e.g. SCDF) have greater access to an increased breadth and depth of data from IoT-enabled devices. These parties can leverage upon the wealth of information provided to initiate rapid initial responses upon the onset of disasters, intervening in these incidents before they become more severe, thereby reducing the likelihood of such small incidents from escalating in severity.

### The idea
Ubique obtains information from multiple sensors, utilizing artificial intelligence services to filter out relevant data. Ubique then utilizes Node-RED to combine the information available, running it through pre-set criteria and determining the action taken. If an action is necessary, Ubique then triggers a response, which may or may not involve the user/relevant parties, depending on the consumer's requirements and plan of action.

## Pitch Video

[![Watch the video](/assets/video/video.jpg)](https://youtu.be/vOgCOoy_Bx0)

## Solution Architecture

![Diagram of Workflow](/assets/workflow/workflow.png)

1. Input is captured from an image-capturing device (e.g. CCTV, webcam).
2. Images are sent for Visual Recognition Processing.
3. IBM Internet of Things (IoT) Platform receives data from connected devices.
4. Node-RED further processes data from IBM IoT Platform and processed data from Visual Recognition Processing determining if the situation calls for the user to be informed.
5. Users receive information about potential emergencies, allowing them to trigger early intervention measures.

## Long description

[More detail is available here](DESCRIPTION.md)

## Project roadmap

![Roadmap](/assets/roadmap.jpg)

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