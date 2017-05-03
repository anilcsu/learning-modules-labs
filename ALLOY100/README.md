<img src='https://appc-img.imgix.net/appc.ALLOY100.png' style="float:left;margin:15px 20px 0px 5px;border:none;" width="150" height="150" align="left">

# ALLOY100

This repository contains training labs for **ALLOY100** module, which can be used to learn about the fundamentals of Alloy MVC framework. 

For more details, see the [Alloy Framework](http://docs.appcelerator.com/platform/latest/#!/guide/Alloy_Framework) document guides.

## Preface

This lab folder includes a completed reference project for you to compare and review, compressed as a `zip` archive.

> *Note: To extract the entire contents of the compressed folder, right-click the folder, click Extract All, and then follow the instructions. [More info](https://support.microsoft.com/en-us/help/14200/windows-compress-uncompress-zip-files)*

```text
Version: 5.3.0.GA
Updated: 07/20/2016

|--completed.zip    # Completed project
|--README           # This document
```

Follow the instructions below to complete this lab assignment.

## Prerequisites

You must have the following requirements to build this project:

- A valid Appcelerator Platform account (free or paid):
	- [Sign up](http://www.appcelerator.com/signup) for an Appcelerator Platform account
- [Appcelerator Studio](https://platform.appcelerator.com/#/product/studio) should be installed and ready for use
- The latest Titanium SDK installation ([requirements](http://docs.appcelerator.com/platform/latest/#!/guide/Prerequisites))
- [Oracle JDK](http://docs.appcelerator.com/platform/latest/#!/guide/Installing_Oracle_JDK)
- [Node.js](http://docs.appcelerator.com/platform/latest/#!/guide/Installing_Node): required for the Titanium command-line tools like the CLI, Alloy and Arrow.
- iOS and/or Android SDK installation

*Note: To minimize the risk of problems, please refer to the [Titanium Compatibility Matrix](http://docs.appcelerator.com/platform/latest/#!/guide/Titanium_Compatibility_Matrix) whenever you make changes to your Titanium environment.*

## Objectives

In this lab, you will:

- Build a two-tab bar Alloy application (with no particular style) 
- Investigate the structure of the Alloy project
- Learn the basic Alloy conventions and instantiation

## Requirements

Create a new mobile project and enable the following functionality listed below and illustrated in the screenshots here:

![](./assets/screens.png)

1. Using Studio, create a basic two-tab Alloy app.  
	* Tab 1 should be named **First Tab**
	* Tab 2 should be named **Second Tab**  
2. Inside the window for each tab add a label component
	* The window controller files should be named **window1.js** and **window2.js** respectively
3. Review the Alloy project filesystem and note the folder structure
4. Review the `index.xml` view and the `index.js` controller file
	* Understand how the main window is instantiated
5. Build your app for the simulator/emulator and test your app
6. Compare your project with the **[completed project](https://s3.amazonaws.com/com.appc.lp-asf-labs/whrNirLMiW/completed.zip)**
7. Congratulations! You have finished this lab.

## Evaluation

To complete this module and earn a digital credential, you must successfully pass the corresponding assessment.

This lab is optional and not subject to instructor evaluation or code review.  

## Additional Resources

Refer to [http://docs.appcelerator.com/platform/latest/#!/guide/Alloy_Framework](http://docs.appcelerator.com/platform/latest/#!/guide/Alloy_Framework) to learn more about this module.

For Alloy updates, review the [Alloy Release Notes](https://github.com/appcelerator/alloy/blob/master/CHANGELOG.md) to see what has changed.

## Bugs & Comments

If you have issues or comments, please file a ticket here: [http://appcel.us/appc-lp-asf](http://appcel.us/appc-lp-asf)

## Authors

- TZ Martin: [@tzmartin](http://twitter.com/tzmartin) - <axwaylearning@axway.com>

---

# License

Copyright 2016, Appcelerator, Inc. All rights reserved.

The contents of this repository are the property of Appcelerator Inc.  Users of this content may not copy, distribute, adapt or otherwise modify these materials.  Content is for internal customer use only. Users of this content may not use the slides or derivatives for commercial purposes. All rights not set forth herein are reserved specifically to Appcelerator Inc.
