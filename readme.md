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

## M1 Macs
When using a mac computer with M1 processor, make sure you modify the addon_config.mk file so the route to the PCL files are correct.
This is because brew uses a different filepath on M1 macs.
