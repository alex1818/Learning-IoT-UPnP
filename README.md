Learning-IoT-UPnP
=================

Source code for the UPnP chapter of the book "Learning Internet of Things".

This chapter covers the basics of the UPnP protocol. It also shows how to use UPnP in the **camera** and **controller** projects, each running on separate Raspberry Pis.

The source code contains the following projects:

|Project                          | Description|
| ------------------------------- | ---------- |
|**Camera**                       | The camera project. Publishes an infrared camera and some control parameters.|
|**Controller**                   | The controller project. Controls the actuator based on input received from the sensor.|
|**Clayster.Library.IoT**         | Library handling basic interoperability for the Internet of Things.|
|**Clayster.Library.RaspberryPi** | Library containing classes handling different types of devices connected to the Raspberry Pi interfaced through GPIO.|
|**Clayster**                     | Contains libraries that facilitate data persistence, event logging, communication, localization and scripting.|

Projects are developed in C# and compiled using [Xamarin](http://xamarin.com/). They are executed on Raspberry Pi using [MONO](http://www.mono-project.com/). By modifying the classes in Clayster.Library.RaspberryPi, the code can be made to run on other hardware platforms as well. This library is the only library that contains code specifically written for the Raspberry Pi.

