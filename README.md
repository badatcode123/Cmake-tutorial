So this is just the official CMake tutorial done until step 3

## HOW TO BUILD
to build the executable, clone the repository then do the following in the command line:
```
cd PATH_TO_REPOSITORY
mkdir build
cd build
cmake PATH_TO_REPOSITORY\executable
```
If you want to use the standard sqrt() method given by c++ instead of the hand-written one, you can do this for the last line instead
```
cmake -D USE_MYMATH=OFF PATH_TO_REPOSITORY\executable
```
finally do the following
```
cmake --build PATH_TO_REPOSITORY\build
```
If visual studio was used to build it, then a final `cd debug` is needed. 
Now you can just do `Tutorial SOME_NUMBER` to run the program, for example:
```
Tutorial 5
Tutorial 3
Tutorial 0
```
