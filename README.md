# Package-Saver
A horrendously poorly made program to save packages installed with apt so they can more easily be restored on a different computer.

Install Instructions:
cd to the source folder
run    chmod +x install-aptsave
run    ./install-aptsave
done. optionally delete the source code directory, as it is no longer needed.
alternatively just copy the program into /bin directy since this program is really simple.

Once the program is installed, you can run it by entering "aptsave" into the terminal. you can also just run the file straight from the source code directory


Details:
After running the program, it creates a file in your home directory called 'aptsave' which you can save somewhere else, like on a cloud service to run later. This file can be executed like any other bash script, and will use apt to install whatever packages were on the computer used when you ran the program.
