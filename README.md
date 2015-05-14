# cmp272team6
The readme file illustrates the setup required to use this mobile app.

About:
The mobile app is a student work for the project as part of CmpE 272 - Enterprise software platforms at San Jose State University, San Jose, California 
under the guidance of Professor Mr.Rakesh Ranjan. The app uses IoT sensors to detect pollen count in the installed area. The data is sent to MongoDb hosted on
mongo lab. We have created a mobile app that will fetch the data from the MongoDb and provide timely information on the pollen data to the user.

Team members:
The project work is a complete efforts of three members namely,
Vinoth Baalaji AS
Anuja Bhalerao
Madhumita Walawalkar

Setup:
The project involves two phases as mentioned below.
1. Real time pollen data collection.
2. Android Mobile App to facilitate user with information and alerts.

Configurations:
1. Import the node red file into a valid node red flow editor.
2. In this project, we have used the IoT Sensor simulator provided by IBM Bluemix. The URL is 
https://quickstart.internetofthings.ibmcloud.com/iotsensor/
3. In the node red flow, configure the device id that is generated from the above link in the IoT App In flow.
4. Modify the mobile number in the Twilio node to receive SMS alerts.
5. Verify the changes and deploy the node red flow.
6. The data will be fed into the mongo db collection hosted on mongo lab.
7. Install the PollenAlert.apk into your mobile. The app is built on API version 21 that runs Android Lollipop.
8. Once installed, open the app to view your Sensor device data. 
9. The data can be refreshed on the go by the user to see the latest allergy pollen count.
10. Also, when the level of the allergic pollen count increases to more than 7.0, the user will receive an alert to the mobile number configured in the node red flow.
11. The Map view in the mobile app will show the marked locations with the pollen count data received from all the IoT sensor devices.
