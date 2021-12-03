# AUGMENTED REALITY(NATIVE) SAMPLE APPLICATION (1.0.1)

## **Details**

## Overview

Augmented Reality is changing the way real world information is augmented with
virtual 3D content that enables delivering rich and amazing experiences to the
users. AR also simultaneously provides a great degree of information. This
enables rendering of real world information and presenting it in an interactive
way, where virtual elements can become part of the real world, extending the
real world into virtual world.

With capabilities ranging from Real-time Image Recognition and Tracking,
SLAM(Simultaneous localization and Mapping) and virtual 3D Models in AR scenes
that enables you in creating powerful interfaces and rich feedback loops in
products customization. This revolutionizes the way rich content can be
delivered.

This application is based on ARRenderer widget. The widget is added dynamically
to the form and is used for scanning surfaces and adding objects.

-   **Supported Platforms**

    -   Native iOS and Android - Using ARRenderer widget

    -   iPhone, Android Phone, iPad, Android tablet

**Notes** :

1.  Volt MX Iris v 9.2.3

2.  XCode v 11.3 , iOS v 13.0

3.  Android v 7.0

## **How To:**

## 1. **Getting Started with AR SAMPLE APPLICATION**

**Select the AR project**

Open VoltMX Iris. From menu bar click on Project -\> New Project. You can see
the below screen. Click on Sample Apps and then click Next button.

![](media/b50683cde477bf4c79409e3bd780adad.png)

Select Augmented Reality App and then click on Choose button.

![](media/ca4b64f9e7ee681641395b425947adcc.png)

From the **Project** explorer, go to **Mobile**, expand **Forms**, and then
verify whether the **frmDashboard, frmCameraScreen** is successfully imported to
the existing application

![](media/ac08e3f5b2a1ea73f5ccb4647cf56b2f.png)

![](media/99fc9483052e060e17eee8b9c5171b16.png)

![](media/daa5d9e211d151f7a7ac65d6b7cbd32b.png)

Go to **Templates**, expand **Components** and then verify whether the
components are successfully imported to the existing application.

![Text Description automatically
generated](media/9780e6e834fd6b3bdb19e0ccaf3cfe9f.png)


**Build the App**

From menu bar, go to **Build** and then select **Build Native Local**.

![](media/dcbc9b4679f83cf28655a53a774bf282.png)

For **Mobile**, select **Android** and **iOS**. Click **Build**.

![A screenshot of a computer Description automatically generated with medium
confidence](media/29edad64813ffdcf3f37ca57a3dee0e8.png)

![A screenshot of a computer Description automatically generated with medium
confidence](media/e0215e58a1660814fe2cd9f86e2ac8c7.png)

After the build is successful, run the app on your mobile device


**Application Flow**

The landing page for the app is as follows

![Graphical user interface, application Description automatically
generated](media/66a64f6121025763c11103f57487c405.png)

Click on Scan and so The AR Renderer will ask the camera permissions as shown in
below.

![](media/78584434a1916dbe4eb5c8435999558f.png)

Once click on OK then it will starts searching for a plane surface.

![A picture containing graphical user interface Description automatically
generated](media/4f32bdcb424727265e79f4ce49c4d496.png)

Then add an object and you will see the selected object as show in the following
screen shots.

![](media/525efdb2b4bb06c2df5abc9a9b3416d4.png)

![](media/c5fb47da176a303fd76e771e7c043f8f.png)

![](media/f2f99567fd5f1ade8251b081afc11b96.png)

Select another object from list of objects and can see 3d view as shown in below
images.

![](media/288e1924bc5b63ffa3e7ebf77bb44b45.png)

![](media/d45e4d9bfef38a8b1071f7b3bb0a3a90.png)

![](media/c641f3ed6929b43c973c51765d09c15e.png)

![](media/90c68fc78584cca7df8662a272dd4de0.png)

**Note:** For Android, the image is displaying very small and when moving the
camera closely then the image is displaying in big size.
