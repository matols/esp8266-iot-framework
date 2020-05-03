# Setup

This section will describe how to use the framework, and what prerequisites are needed. To get started read below how you should build the framework. When you can build successfully you can simply start adding your own code in `main.c` which contains the familiar `setup()` and `loop()` functions. 

## Building the Framework

To use this framework as is, it is recommended to use PlatformIO to build from source. In `platformio.ini`, three different python scripts are listed as `pre:` scripts, meaning these will be executed before every build.

```
build/preBuildHTML.py
build/preBuildConfig.py
build/preBuildCertificates.py 
```

You can choose to comment these scripts, since all default artefacts generated by these are committed in this GitHub repo, so that these pre-build steps are optional.

### preBuildHTML.py

Coming soon 

### preBuildConfig.py

Coming soon 

### preBuildCertificates.py

Coming soon 

## Editing the web interface

The web interface is contained in the `HTML` folder, and is developed using React and Webpack. To modify the provided interface you need to be familiar with these tools and have **NPM** installed. Of course you can also start your own GUI completely from scratch.