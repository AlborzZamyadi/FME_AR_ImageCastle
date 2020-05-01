# FME_AR_ImageCastle

[You can watch the Image Castle Tribute to Heroes of COVID19 on YouTube](https://youtu.be/vt8FQBUGrrc)

# ToC

* Introduction
* Who Would Enjoy the Material on this Repository?
* Summary of the Material Shared on this Repository

# Introduction

This started as I wanted to make a tribute to the front-liners who have had our back during the COVID-19 crisis. I wanted to make a piece of memory to thank them and have their unconditional effort registered throughout the time. I also wanted that this tribute would be accessible to all and as immersive as a hall of fame museum. That is how I thought of creating a Virtual 3D Hall of Fame (i.e. Image Castle) that can run on Mobile Augmented Reality. This would make it accessible to all and super immersive.

![](https://github.com/AlborzZamyadi/FME_AR_ImageCastle/blob/master/DOC/7.jpg)

I am a Geomatics/GIS enthusiast. One of the tools I frequently use is FME (Feature Manipulation Engine) by [Safe Software](https://www.safe.com). FME is a Royalty Software. However, the [FME AR App](https://apps.apple.com/ca/app/fme-ar/id1298762717) for Mobile Augmented Reality is freely available to everyone and pretty easy to install and use. So, I decided to design the Image Castle 3D Model in [AutoCAD](https://www.autodesk.ca/en/products/autocad/overview?plc=ACDIST&term=1-YEAR&support=ADVANCED&quantity=1) (using a Trial licence). Then, I had the 3D Model combined with a selection of Public Domain Images and exported the result to a FME AR file (*.FMEAR which is a package of *.OBJ files plus a setting *.JSON) by FME 2019 running on [Free Home Use License](https://www.safe.com/free-fme-licenses/home-use/).

**This is not by an means a commercial or promotional product**. I have created this Repository to :
* Share the Image Castle FME AR file (imageCastle_1_20200428.fmear) with all so that they can run on it on their own phone using the Free [FME AR App](https://apps.apple.com/ca/app/fme-ar/id1298762717)
* Share the Image Castle 3D Model I made (in DWG format) with all so that they can add their own features to it
  * If you are not an AutoCAD user, you can use any tool to create your 3D Model and the FME Workbench shared here would work as long as the geometric-semantic schema of Image Castle is respected, the DWG Reader of the FME Workbench is replaced with that of your format, and, if required, a basic Attribute Renaming is done (if your format uses specific generic names to carry the additional data on top of the geometries it carry)
* Share with all the FME Workbench that combines the Image Castle 3D Model with Images and builds the *.FMEAR so that anyone can use their own images

# Who Would Enjoy the Material on this Repository?

The material shared here are good if you would like to
* Run the Pre-Made (by me) Image Castle tribute to COVID-19 front-liners (imageCastle_1_20200428.fmear) on your own phone and premises. **If doing so, please choose a place that you have sufficient amount of free and safe space to move around. Mobile Augmented Reality can be very immersive and gets your attention off the surrounding. Please be safe. No one except yourself can ensure your safety.**
* Design and build your own Image Castle and include your own images for personal fun or as a fun birthday gift sent to a loved one! Imagine that a loved one, thousands of miles away, would be able to walk in an Image Castle you build for him or her!
* Get familiar with FME Software itself. The FME Workbench shared here incorporates a good set of functions and tricks for filtering data, constructing 3D geometry, integrating data streams, sorting, ...
* Get familiar with Computer Aided Design (CAD) modeling and hints on moving CAD data toward GIS

# Summary of the Material Shared on this Repository
* Pre-Made (by me) Image Castle tribute to COVID-19 front-liners (imageCastle_1_20200428.fmear). This is ready to be loaded on your phone using [FME AR App](https://apps.apple.com/ca/app/fme-ar/id1298762717)
* [to be added soon] Instruction on installing [FME AR App](https://apps.apple.com/ca/app/fme-ar/id1298762717) and loading the *.FMEAR files to it
* Image Castle 3D Model in DWG format and [to be added soon] documentation on its geometric-semantic schema
* The FME Workbench to Read the Image Castle 3D Model DWG and your images, have them integrated, and Write a *.FMEAR file
* Some sample images to support the Image Castle 3D Model in the FME Workbench
