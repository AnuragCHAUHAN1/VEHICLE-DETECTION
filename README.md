# Radar1 (OpenCV)
This code focuses on object tracking and speed estimation of vehicles passing through the road. The camera angle is slightly off the road just like in the sample video given.

# VIDEO 
Any matching video will work, although you'll need to make some changes to the code if you choose a different video. This is due to the change of scene, distance estimation and pixel clarity.

For radar1.py, the region of interest, the red timer lines, and the area range used to detect vehicles.

For Tracker2.py, the numbers passed in the update() function and the getsp() function will change for a different video.

# saving vehicle data
I have created a .txt file named "SpeedRecord" which contains the specified ID and information like its vehicle speed, if the speed limit is exceeded it shows that the speed limit has been exceeded by the vehicle. Also the image of all vehicles passing through the reference line will be automatically saved in the same folder as the main code file.