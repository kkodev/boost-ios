# boost.framework

### Boost iOS framework you can simply drag into your app.

<br/>

#### **If you are lazy:**

1. Grab pre-built framework from Dist folder (boost 1.52.0).

<br/>

#### **To build please follow these simple steps:**

1. Get yourself a nice cup of coffee (tea should do as well)
2. Update boost submodule:    
    `cd PROJECT_DIR`  
    `git submodule init`  
 	`git submodule update --init --recursive`  
3. Open `boost-ios.xcodeproj`
4. Build `boost.framework` target
5. Framework will be created in the project directory and is ready to use
6. Enjoy!

<br/>
####Please note:    
 
Latest version of boost may not work with **C++0x** and LLVM out of the box.  
If you run into trouble using the framework, please consider switching to **C++98** or consult community at <a href="http://boost.org">boost.org</a> for possible fixes and/or workarounds.  
Alternatively, you may want to try pulling some previous version of boost submodule and rebuilding the framework.