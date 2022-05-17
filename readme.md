# ofxPCL
## addon for using PCL (Point Cloud Library) with openFrameworks 

## Only working on MACOS

## Instructions 

* Install PCL using brew

this will install the library system wide as well as its dependencies
```
brew install pcl
```



* Generate a new project using Project Generator and adding ofxPCL as an addon
* once the Xcode project is open go to the the Build Settings and delete the paths that are set in 
    * HEADER_BOOST
    * LIB_BOOST_FS
    * LIB_BOOST_SYSTEM

* Compile!