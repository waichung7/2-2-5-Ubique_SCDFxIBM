# Ubique

[As one of the world's smartest cities](https://www.edb.gov.sg/en/news-and-events/insights/innovation/what-it-takes-to-be-a-smart-city-in-southeast-asia.html), Singapore looks set to have an increasing number of IoT-enabled devices. Ubique aims to leverage upon the data available from such IoT-enabled devices, located all around us, to better allocate limited resources in the case of emergency incidents. This allows for the triggering of early intervention measures, preventing problems from worsening, and consequently resolving the need for activation of emergency resources. 

[Project Website](https://code-and-response.github.io/Project-Sample/)
#
## Input

Ubique takes data from multiple sources, but for demonstration purposes, we have used IBM's IoT Platform and Webcam input to illustrate how such input data can be processed. For this sample flow, we ilustrate how sensor data can be used to analyze if there is a fire, and if so, to activate early intervention measures (e.g. sprinklers, activation of fire shutters).

### IBM Internet of Things Platform 

A simulation of IoT ([available on IBM's website](http://quickstart.internetofthings.ibmcloud.com/iotsensor)) was initialized to act as a sample of how IBM's IoT platform, if integrated into the target areas (e.g. buildings), could be used to provide sensor data to feed into Ubique. In the context of a fire, temperature of a room would increase and the humidity will drop, and such data will be fed into Node-RED to analyze for the presence of a fire and consequently the activation of relevant measures.

### Visual Feed

A webcam image input was used to simulate CCTV input. With images being captured by the visual feed, they will be transmitted to the Visual Recognition service (part of Watson Studio), with the AI analyzing the contents of the picture. If certain keywords/scores are met (e.g. keyword 'fire' appears), the flow of information continues.
#

## Node-RED

Node-RED facilitates the flow of information between different devices and services. In the case of Ubique, it is integral in acting as a bridge between information and action.

### IBM Internet of Things Platform 

### Visual Feed

#
## Conclusion

As it's name suggests, Ubique has the potential to be everywhere in an IoT-enabled environment. It is not just an app - it is a concept. There are many areas to expand upon what we have currently illustrated. For example, object detection could be added to live video feeds for live detection of growing fires, which would activate sprinklers beyond a set threshold. Ubique could be combined with the myResponder app to automatically alert nearby CFRs upon detecting any cases which they can assist in. Machine Learning could further process the data they provide to automatically improve upon detection accuracy. 

The potential of Ubique is limitless. Yet at it's core, it is just a simple idea - to leverage on what is available to help organizations better manage their limited resources. 

## Acknowledgments

Nullam nec lectus massa. Proin feugiat placerat nisi lacinia lobortis. Duis efficitur ac orci ac lobortis.