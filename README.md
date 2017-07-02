# Autonomous-Quadcopter-with-RPI-and-Azure-Iot-Core-
This project is Work in Progress for more Better PID control for Autonomous Quadcopter With Only Using GPIO pins of Raspberry pi connected to cloud by Azure Iot Core.  There are so many improvisation yet to make it more stable PID and less power usage with GPIO pins .. Stay tuned 

Must Have Installed ServoBlasters :: https://github.com/richardghirst/PiBits/tree/master/ServoBlaster #Respect


*****For Azure Connections***
services used are 
Azure IoT Hub,
      Steam Analytics
    & Azure Funtions app
#must be in same Resource Manager

You can find your end point in the portal in your IoT Hub under Messaging -> Endpoints -> Events.
All you have to do is add a SharedAccessKeyName and SharedAccessKey from your IoT Hub to the compatible endpoint.
Make sure you dont forget to add the Event Hub-compatible name to the path value in your function.json

For Unexpected Threat to your while it's in air Use Another Azure Funtion to keep your phone App Notified
Source :: https://microsoft.github.io/techcasestudies/azure%20app%20service/azure%20functions/2017/03/21/KingwaytekAzureFunctions.html

(InProgress)Itegration with ArcGIS for application of Dump Segregation
ArcGIS :: API support as FeatureLayerView
GraphicsLayerView
ImageryLayerView
LayerView
SceneLayerView

