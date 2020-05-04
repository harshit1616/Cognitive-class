## Robots Are Coming! Build IoT Apps with Watson, Swift, and Node-RED IBMDeveloperSkillsNetwork ML0201EN

* Lab 1: Read temperature data from an IoT sensor:
1. In Lab 1, what is the main purpose of the Internet of Things Platform Starter? - To facilitate communication between the Node-RED instance running on the Raspberry Pi and the instance running on IBM Cloud
2. In Lab 1, where exactly does the Swift UI get the temperature data from?- From the Cloudant database
3. What imported library is required for you to do CRUD operations on the Cloudant database in IBM Cloud?- SwiftCloudant
4. In Lab 1, why did you need two Node-RED flows? -  To get sensor data (flow 1) and then to send it to IBM Cloud (flow 2) To get sensor data (flow 1) and then to send it to IBM Cloud (flow 2)
5. In which Node-RED node do you initially enter a device ID? In this lab, the device ID is from the virtual temperature sensor. - IBM IoT App In

* Lab 2: Add a camera and analyze images:
1. How is Watson Visual Recognition used by the Raspberry Pi in an IoT environment? - Single pictures taken by the Raspberry Pi camera are sent to the cloud and processed by the deep learning network trained on existing pictures.
2. The Visual Recognition service uses machine learning to recognize and classify visual content.- True
3. MQTT cannot be used to pass data through firewalls.- False
4. What action does the following Swift code perform? - Shows a picture on a mobile device
5. In Node-RED, output nodes have the logo on the left side of the node.- False

* Lab 3: Connect your app to an iRobot and smartphone:
1. Which one of the following SDKs helps to simplify how you use cognitive services with Swift applications?- Watson-Developer-Cloud SDK for iOS 
2. What's the purpose of the WeatherData.swift file? - Manages the connectivity to the Weather Company Data service Manages the connectivity to the Weather Company Data service.
3. The Watson IoT Platform starter automatically deploys and connects which of these services. Select all that apply.- Watson IoT Platform,  IBM SDK for Node.js for IBM Cloud, IBM Cloudant for IBM Cloud 
4. To manipulate JSON, you added which framework to the XCode project?-  SwiftyJSON.framework 
5. What additional data can you find in the Weather Data JSON?- Conditions for playing golf

* Final exam :
1. Which of the following data types can be be sent from an IoT sensor to the cloud for further processing? Select all that apply.- Temperature, Humidity, Air pressure, Seismometer data
2. What is the lightweight protocol that is used for communication between a Raspberry Pi device and a cloud application? - MQTT
3. Which Watson services can you use to build a voice user interface to access IoT devices? - Speech to Text, Text to Speech
4. You typically need to install a node package to get Cloudant database nodes in Node-RED. - True
5. How does BM Watson Visual Recognition determine what's in an image? - By deciding what categories the image and the parts of an image fall into
6. In this course, how did you connect the Raspberry PI to the iRobot?-  The iRobot serial port 
7. IBM Cloudant is an example of which of the following service types? Select all that apply.- NA
8. What action does the following code perform?-  Sends a command over an MQTT connection
9. What method can you use to extend the functionality of Raspbian Jessie?- npm
10. You can store pictures from a camera or from the Internet by using a Cloudant database.- True
