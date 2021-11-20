# Processing Images
* Task 1: Create a ROS package called `roboskel_ex2`. 
          The package should depend on the ROS client library of your choice (C++/Python or other if you feel adventurous),
          and any other required packages (e.g. for messages).
* Task 2: Create a node that subscribes to **one** Image topic and publishes to **two** Image topics.
* Task 3: Using the rosbag of [Exercise1: Creating a rosbag](./exercises/ex1.md), read the Image data using the previously
          created node and do the following:
  * Task 3a: Publish the Image in grayscale and keep the RGB values only for moving objects/pixels.      
  * Task 3b: Publish a cropped image of the original which is the minimum rectangle that includes all the moving 
             objects/pixels of the frame. If the image contains no moving objects the message should not be published.
* Task 4: Use any tool to visualize your two published topics. Report on the framerate of the input topic and 
          the framerate of the topic of Task 3a.
