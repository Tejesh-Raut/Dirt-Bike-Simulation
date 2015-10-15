# Dirt-Bike-Simulation
This is a simulation in Box-2D of the Dirt-Bike. It has been made as a part of project in Box-2D of the course System Software Lab during 3rd semester of BTech degree.

How to run the simulation?
  First of all download the complete project into a folder
  
0. Set your directory to be the directory containing the downloaded
Box2D package, and immediately make a copy of the archive that you
downloaded. Use the command 'cp -a' and understand what the "-a"
option does.

1. Extract the archive and change your directory to cs251_base_code.

2. You now want to install Box2D. Therefore, push your current
   directory on the stack by executing '% pushd ./external/src'

3. Take a moment to study what you have downloaded.  Different people
   take different times for it, but try to understand the structure of
   what you have got. Make sure that you read any *.txt files
   available in the download.  Do not try to understand the code at
   this point, but simply understand what has been provided.

4. You should have found a text file called cs251_README.txt which is inside the folder external/src .  Follow
   the instructions very carefully (but keep this text file window
   open).

5. If, and only if, you have successfully passed the check steps in
   (7) and (8) of the file cs251_README.txt, do the following.  
   See *extra* info below. 
   If you are still unsuccessful, do not proceed and ask for help.

6. 'pop' the directory stack using '% popd ' You should be back to
    where you were in step 1.

7. Now you want to get the picture shown in the tutorial conducted
   earlier. Therefore compile the program, using "% make"

8. Check the ./bin directory for the existence of "cs251_base"
   executable.

9. Run the program( by typing "./cs251_base" in terminal inside the bin folder)

---------------------------------------------------------------------
Extra Info

Setting up GLUI for Box2D on newer Ubuntu (>= 12.04)

If you are having issues compiling the base code on your laptops, you
probably don't have the GLUI library installed.

One such error might be:
  cs251_base_code/src/main.cpp:35:21: fatal error: GL/glui.h: No such
  file or directory

For versions earlier than Ubuntu 13.10, run this:
  sudo apt-get install libglui2c2 libglui-dev

For Ubuntu 13.10 onwards, download these two packages:
  http://packages.ubuntu.com/raring/libglui2c2
  http://packages.ubuntu.com/raring/libglui-dev
And run:
  sudo dpkg -i <packagename>
(Install libglui2c2 first, and then libglui-dev)
