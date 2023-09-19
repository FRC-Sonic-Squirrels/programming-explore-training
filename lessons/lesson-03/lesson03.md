# Lesson 03 

In this lesson you will be applying what you learned from the previous two videos to write a drivetrain subsystem for our minibot 

This will be an independent project (no video to guide you) however always ask questions if you are stuck and feel free to work together with someone else 

**This will likely be challenging and its okay to make mistakes and stumble along the way. Making mistakes is part of the learning process and its inevitable when learning a new concept. 
Give yourself some slack and try not to get too frustrated at yourself if it doesnt work. And as always, never hesitate to ask questions.**

1. If you have not physically seen the minibot yet please ask the programming lead/mentor to show it to you so you can understand the physical object you will be programming

2. create a new project to start fresh. You will be writing similar code as to before, but this time try to do as much of it yourself as possible **while incorporating the changes listed below**. You can of course look at your previous project as a reference but DONT copy paste and try to actually understand every line you type. If you arent fully sure what something means ask! 

There are some slight differences in how this robot is configured compared to the code you wrote in lesson02 

Main differences: 
* This robot only has only 2 neos for driving. 1 on each side. Unlike the 4 in the previous lesson
* We will be using the `CommandXboxController` controller class instead of the `Joystick` class
  * instead of getting a x,y,z axis you will instead use the `getLeftY()` or `getRightX()` etc. etc. 
  * Heres some example syntax for how a CommandXboxController might be used.
    ```
    CommandXboxController driverController = new CommandXboxController(0);

    double forward = driverController.getLeftY();
    double turning = driverController.getRightX();
    ```
    Mess around with it and ask questions to learn more about how you can access values from the controller.
    
    **Basically for everywhere where you used `Joystick` from lesson02 you will now instead be using `CommandXboxController`**


3. Once you have successfully written and built your code, ask the programming lead/mentor to help you deploy your code to the minibot so you can test it out.
   The following lessons will delve deeper into different commands and ways you can program this robot. 
