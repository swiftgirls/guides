If you haven't setup your Mac please read the installation guide that we still need to write ;).

# Glossary

## Xcode

Xcode is the IDE we are using to develop and compile our App.

## Storyboards

## Playground

## Core Data

# Creating the App

We're going to create a new iOS App called SwiftGirls.

Open Xcode and click on the *Create a new Xcode project* Button. Alternatively you can go to *File -> New -> Project*.

Choose *Single View Application* as template for your new project and click *next*. As *Product Name* enter SwiftGirls, as *Organization Name* your name and as *Organization Identifier* com.swiftgirls. Next choose *Swift* as *Language* and *iPhone* as *Device*. Per default the checkmark should be at *Include Unit Tests* and *Include UI Tests*. You need to also activate *Use Core Data* and click *Next*.

> We should explain the different options here, but don't go into much detail.

Now you can choose where to save your project. Typically you have a project directory for all your iOS projects. Choose your project directory and click *Next*. Xcode will create all the necessary files and also a Git repository for your project.

> We explain Git more in depth later on.

Your App project is now created and we can try it, just click the play button in the upper left corner or press *cmd + R*. Xcode now compiles the App for you and starts the simulator with your App running.

You can easily scale down the simulator if you go to *Window -> Scale -> 50%*. To stop your App just press the stop button right beside play.

> Explain what Xcode has created. For example the AppDelegate and your Storyboard.

# Design your App

* Play around with Storyboards and explain AutoLayout
* Create a TableViewController with a simple UITableViewCell
* Manipulate the number of cells via code
* Create new cells via plus button
* Create new objects with a modal UIViewController
* Create an Idea/ToDo entity in CoreData and prepare everything
