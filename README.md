Just a quick note about this repository. There is a problem using Xcode & GITHUB together. Whenever I try to use the Xcode 10 built-n Source Control features, I can create a new branch in the local GIT but it will not ever show up on GITHUB. Also Xcode keeps changing stuff in a file called xcscschememanagement.plist. Then every time you try to perform a checkout to switch branches, it says you need to do a commit first. I found that is is best not to use Xcode with GITHUB. Just use the MAC Terminal which work corrrectly with GITHUB. The app itself can be programmed in Xcode and it works fine on the iPhone. So, as long as you don't ever use Xcode with GITHUB, all is good.

Below is the original Readme File.


![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Flash-Chat

## Our Goal

One of the most fundamental component of modern iOS apps is the Table View. Table Views are used everywhere from the Mail app to the Messages app. It’s a crucial part of every iOS developer’s tool belt. In this tutorial we’ll be getting to grips with Table Views, creating custom cells, and making our own cloud-based backend database. It’s going to be epic, so buckle up.

## What you will create

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. We will be using a service called Firebase as a backend data server to store and retrieve our messages from the cloud. 

## What you will learn

* How to integrate third party libraries in your app.
* How to store data in the cloud using Firebase.
* How to query the Firebase database.
* How to use Firebase for user authentication.
* How to work with a UITableView.
* How to use custom cells in a Table View.
* How to embed View Controllers in a Navigation Controller and understanding the navigation stack.
* How to create Segues for navigation.
* How to make custom .xib files to modify native design components.
* Using Grand Central Dispatch to queue asynchronous tasks.


>This is a companion project to The App Brewery's Complete App Developement Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
