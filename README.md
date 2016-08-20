## Gradle Simplest Project 
A simplest gradle project based on [mrduguo/gradle-buildscript](https://github.com/mrduguo/gradle-buildscript) project. You may simply clone the project as a start for any new project. 


### Sample Build Command

```
./gradlew
```
### Build System Files Explained

* gradle* (gradle wrapper distribution files)   
    * 1. gradlew
        * linux bash executable
    * 2. gradlew.bat
        * windows batch executable
    * 3. gradle/wrapper/gradle-wrapper.jar (50 KB)
        * wrapper binary distribution
    * 4. gradle/wrapper/gradle-wrapper.properties
        * wrapper configuration
* config
    * 5. build.gradle
        * the build system config tell where to get started
        * same for all projects        

### Sample Tasks Comes With The Build System

Show the build environment stats include system and environment variables:
```
./gradlew bld_stats
```

Upgrade the build system itself:
```
./gradlew bld_upgrade
```
