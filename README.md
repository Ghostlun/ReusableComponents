# ReusableComponents


## Swift keyword 
1.[CoreData] (#1.CoreData)
2.[UserDefaults] (#2.UserDefaults)
3.[ContactHandler] (#3.ContactHandler)
4.[LocationManager] (#4.LocationManager)
5.[FileManager] (#5.FileManager)


This is an explanation of reusable componen

## 1.CoreData
### CoreData Def
It is a framework that you use to manage the model layer objects in application. 
It saves user data permanently for offline use, or temporary cache data, and also undo functionality of the app to a single device. It is useful to store large models and data.

### How to use it?
1. Define your entities and attributes.
2. Genereate class from them, and get a reference to persistent container
3. From where you get managed context and through the managed object context, you can create and store objects

### Use case of example
1. Generate Entity into CoreData
<img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Entity.png"/>

2. Create subclass of coreData
<img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/CreateSubClass.png" />

4. You need to declare Context
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Context.png" />

5. Apply function, CRUD ideas
Create, Update :
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Create%26Save.png" />
Read :
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Read.png" />
Delete :
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Delete.png" />



### CoreData Demo App
<center>
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Update.gif" width = 200 height = 410 />
 <img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/CoreDataDemo/CoreDataDemo/Resource/GithubResource/Close.gif" width = 200 height = 410 />
</center>


Compared to userdefaults, userDefault is used to store simple data.


## 3.ContactHandler
You can send mail, call, message by using this component

How to use it!

First, you need to declare using ContactFunctionHandler lazy var

Then, you need to connect with IBAction

<img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/Reusuable%20Components/Image/ContactHandlerCodeExample.png" />


## 4.LocationManager

You can save your location by this location Manager.

First, you need to init NetworkManager, then you can call the function you want

Ex, If you want to call getUserLocation, you call it this day. Then, this location will contain user location into CLLocation.

Also, It provides authorization of location service, also reverses geocoder

How to Use It!

<img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/Reusuable%20Components/Image/LocationManagerCodeExample.png" />


## 5.FileManager

You can read, write, download file into your document directory. It singleton pattern

So, you can call function directly
<img src = "https://github.com/Ghostlun/ReusableComponents/blob/master/Reusuable%20Components/Image/FileCodeExample.png" />

<h3> Keyword explanation </h3>
What is Uid: It is key item of data, that you will make use of in security in order to what that user can do with documents.

<h4> Core Data </h4>
<b>Core Data</b> : Core data is 



