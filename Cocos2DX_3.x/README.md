# DragonBones Cocos2d-x Library

## [Demos](./Demos/)

## How to use
1. Create a Cocos2d-x C++ project and import [Demos files](./Demos/) to override the project files.
2. Import the [DragonBones common source code](../DragonBones/src/) to project classes.
3. Import the [DragonBones Cocos2d-x source code](./src/) to project classes.
4. Import the [3rdParty source code](../3rdParty/) to project classes.
5. Build project and have fun.

## Notice
* In Xcode: Add Files To "project" > Options > Added folders: Create groups > Add to targets: "all"
* Use [rapidjson/msinttypes](../3rdParty/rapidjson/msinttypes) headers only with Microsoft Visual C++ compilers.
* If compiler can not find headers, add Classes to project Header Search Paths, maker sure project structure like this:
```
Classes (Include Path)
    |-- rapidjson
        |-- ...
    |-- dragonBones
        |-- ...
```