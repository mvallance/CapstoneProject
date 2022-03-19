---
description: Cybatica Sample Project
---

# Knowledge Base (internal use ONLY)

This sample project gives you the boilerplate code you need to connect to an iOS device device and start streaming data using the Cybatica app with Apple Swift and XCode.&#x20;

**Ensure the device is set to Develop mode.**

The sample application implemented in the project has very simple functionalities:

* It initializes the Cybatica library with your API key.
* If the previous step is successful, it starts scanning for iOS devices until it finds one that can be used with the API key you inserted in the code.
* When an iOS device has been found, the Cybatica app updates its list of nearby devices.
* Manually selecting the iOS device from the list, the app then connects to the device and streams physiological data.
* Selecting the iOS device again disconnect the device
* When all devices are disconnected the app restarts and delete all data.&#x20;

**How to initially set up Cybatica for development.**

* Clone / download this repository.
* Open the sample project in XCode.
* Make sure you have a valid API key. You can request one for your iOS account from our Developer Area.
* Edit \`ViewController.swift\` and assign your API key to the \`CYBATICA\_API\_KEY\` constant .
* Download the Cybatica.framework iOS SDK from our Developer Area.
* Copy the file to the 'Libs' folder
* Build and Run the project.

If an iOS device is in range but the Cybatica app does not connect, check that the discovered device can be used with your API key. If the allowed parameter is always false, the device is not linked to your API key. Please check with the Lead Programmer for further advice.

If you need any additional information, check with the Lead Programmer.
