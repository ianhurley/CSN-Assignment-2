# CSN-Assignment-2
IoT Application

Assignment 2 Project Name: ‘ScaNut’
Student Name: Ian Hurley   
Student No: 20099695

Description of Project:
We spend a lot of time checking product ingredients for the pressences of allergens, in particurler all forns of nuts for which all of our children are allergic to. This is a necessary task in avoiding the rishk of analphalactic shock and the use of epipens in response.
I would like to develop a simple scanning mechanism that will provide a clear and instant response as follows:

 Green – Safe to Eat
 Amber – Warning: May Contain Traces
 Red – Warning: Contains Nuts

While initially as a prototype in the home through the use of a rasberry pi, an eventual rollout to a mobile device would be a crucial next step to develop the project for use outside the home and abroad which can be particularly challenging with language translations.

Tools, Technologies and Equipment:
I propose to utilitse a Rasberry Pi programmed through Visual Studio Code with Python. With a connected (usb/wireless) barcode scanner, it will analise the barcode against a product database (api database or prepopulated test products) to return product ingredients via HTTP request/response. This is further analised with predetermined search criteria to return a traffic light response, via the LED sensehat and/or in conjunction with the Blynk IoT platform.  This will provide visual feedback and act with notifications to mobile devices.

Project Repository:
A project repository is set up here -> https://github.com/ianhurley/CSN-Assignment-2 <- and will be updated through the course of the project.
