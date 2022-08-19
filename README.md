# Lhg
A mod of Pilzschaf's simple logger.
Tested C++14, runs on Linux and Windows (mac not tested).  

## Changes over vanilla
Adds some extra functionality like using ConsoleTextAttributes for windows users, more different error levels (INFO, DEBUG, WARNING, ERROR, CRITICAL), a toggle for showing path and line before each line and a way to disable all Info Outputs.  
Added ability to disable INFO outputs to make the console cleaner. To show INFO outputs set the verbose member to true or add the 'LHG_VERBOSE' compile definition.  
Also colors can be changed at runtime.  

## Linux
If you use linux, set the compile flag 'LHG_LINUX', to disable Console attibutes.

## Example
![grafik](https://user-images.githubusercontent.com/60015267/179369867-2b76f557-0fb5-4307-8048-e9e90378948f.png)
