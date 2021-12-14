

# **Mod10 Credit Card Validation Function(1.0.1)**

## 1\. Overview

Modulus 10 is very important validation function for all banking application
where user card details can be validated before processing further to server
side or functionality. This simple code module can be used to validate credit
card numbers before submitting them to a back end service.

### A. Use case

 Used in Shopping Apps for Credit card Validation(Payments)

### B.  Percentage of re-use:

Approximate % of reuse. It sets an expectation of how much can be used out of
the box, and how much needs to be customized for a specific app.

## 2. Getting Started

### A. Prerequisites

Before you start using the Mod 10 Credit Card Validation Function component,
ensure you have the following:

-   HCL Foundry

-   Volt MX Iris

### B.  Platforms Supported

i. Mobile

    -  iOS

    - Android

ii. Tablets

iii. PWA

### C. Importing the component

 --Import Js file and use the API in the controller.

### D. Building and previewing the app

After performing all the above steps, you can build your app and run it on your
device. For more information, you can refer to the [Building and Viewing an
Application](https://opensource.hcltechsw.com/volt-mx-docs/docs/documentation/Iris/iris_user_guide/Content/Cloud_Build_in_VoltMX_Iris.html#cloud)
section of the Volt MX Iris User Guide.

You can then run your app to see the Mod10 Credit Card Validation Function

work in real time.

## 

## 3. References

**Process :**

    i.  The module has a single function, **validateCCNumByMod** that takes in a
    single parameter **crCardNum.**

    ii.  If the credit card is valid, the function returns true. Otherwise, the
    function returns false.

    iii.  You should add this .js file into the form modules and call the function
    v**alidateCCNumByMod** from the form controller, then build the app.

**Module.js**

    function validateCCNumByMod(crCardNum)
    { 
    var sum = 0; 
    var crCardValid = false;  
    var everySecondDigit = false;
    var crCardLen = crCardNum.length;
    var checkDigit = crCardNum.substring(crCardLen - 1, crCardLen); 
    voltmx.print("Card check digit number is " + checkDigit);
    for (var i = crCardLen - 1; i \>= 0; i--)
    {  
    var everyDigit = crCardNum.substring(i, i + 1); 
    if (everySecondDigit)
    {  
    everyDigit \*= 2; 
    if (everyDigit \> 9)
    { 
    everyDigit = (everyDigit % 10) + 1; 
    } 
    } 
    sum = sum + Number(everyDigit);  
    everySecondDigit = !everySecondDigit; 
    }  
    voltmx.print("Card check digit number is " + checkDigit);  
    if (sum % 10 === 0)
    { 
    crCardValid = true; 
    } 
    return crCardValid;
    } 
    return { validate : validateCCNumByMod};



**Accessing module.js in form Controller:**

require(['Module'],function(Module){

Module.validate(\<Input Parameter\>);//function calling

{});

## 4. Revision History

App version 1.0.1
