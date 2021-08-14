# SketchUpdate
This is an app to add In-App-Update system in your app in minutes... 

You can notify specific users or all of them at once. Besides you can schedule the msg whatever you are going to send with this app. Furthermore you can use this app to Ban, Send Reward news or Warn the user

## Download SketchUpdate
You can download SketchUpdate from our website
visit us https://sketchupdate.tk

### Step 1 : Account Creation
Download & complete registration. After that simply login. You have to verify yourself every time you login...

### Step 2 : Creating Project
After completing verification you can create a project. Simply click on "Add New Project" to start. Give a name of your project for easy recognition and for the api. 
![Image 1](https://user-images.githubusercontent.com/86944710/129434900-af79acbb-0667-41fe-9ed4-c75210e9e981.jpg)

### Step 3 : Copying Api
An api will be created automatically when you create a new project. You can simply copy the api of a project just by swipe that left or right...
![Image 2](https://user-images.githubusercontent.com/86944710/129434944-3bfce963-f242-4601-a2d3-5c9eca6a1e3f.jpg)

Your copied API should look like this
```https://sketchupdate.tk/data.php/?appId=[PROJECT_NAME]```

### Step 4 : Understanding Api Response
A successful ```GET``` response will be like below... 
```json
{
 "Server_Response":
     [
         {
          "sendTo":"all",
          "alertType":"sheet2",
          "newVersion":"1.2",
          "title":"Update App?",
          "titleColor":"#000000",
          "isSubtitle":"true",
          "subtitle":"Download Size 10MB",
          "description":"We recommend that you update to the latest version. You can keep using this app while downloading the update",
          "descriptionColor":"#000000",
          "appIcon":"https:\/\/sketchupdate.tk\/assets\/images\/favicon.png",
          "appName":"Sketchupdate",
          "mainBtnTxt":"Update",
          "mainBtnTxtColor":"#FFFFFF",
          "mainBtnBackColor":"#000000",
          "mainBtn":"https:\/\/sketchupdate.tk",
          "isExtraBtn":"true",
          "extraBtnTxt":"dismiss",
          "extraBtnTxtColor":"#000000",
          "extraBtnBackColor":"#FFFFFF",
          "extraBtn":"dismiss",
          "isCancelable":"false",
          "isOneTime":"false",
          "backColor":"#FFFFFF",
          "radius":"25",
          "btnRadius":"25",
          "isHeader":"true",
          "time":"2021\/8\/7\/11\/10"
         }
     ]
}
```
## Sample Project 
2 sample projects are available for both Android Studio(.zip) & Sketchware Pro(.swb) users

