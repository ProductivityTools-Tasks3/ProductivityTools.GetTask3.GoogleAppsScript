<!--Category:GAS--> 
 <p align="right">
    <a href="http://productivitytools.tech/"><img src="Images/Header/ProductivityTools_green_40px_2.png" /><a> 
    <a href="https://github.com/ProductivityTools-Tasks3/ProductivityTools.GetTask3.GoogleAppsScript"><img src="Images/Header/Github_border_40px.png" /></a>
</p>
<p align="center">
    <a href="http://productivitytools.top/productivitytools-gettask3-googleappsscript/">
        <img src="Images/Header/LogoTitle_green_500px.png" />
    </a>
</p>

# ProductivityTools.GetTask3.GoogleAppsScript

This is Google Apps Script which reads tasks from Google Tasks and move them to GetTask3 application.

<!--more-->

## Script properties
Script need to have two script properties:

- ParentId - which defines where new tasks will be created
- webapikey - used for authentication

![](Images/2023-02-12-20-04-02.png)

## Schedule

To make the process automatic, trigger need to be added:

 ![](Images/2023-02-12-20-07-28.png)

 ## Services

 Task service need to be added to be able to call API.

 ![](Images/2023-02-12-20-09-20.png)