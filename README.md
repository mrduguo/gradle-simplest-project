## gradle simplest project 
A simplest gradle project based on [mrduguo/gradle-buildscript](https://github.com/mrduguo/gradle-buildscript) project. You may simply clone the project as a start for any new project. 


### sample build command

```
./gradlew
```
### build system files explained

* build.gradle
   * the build system config tell where to get started
   * same for all projects
* gradle* (gradle wrapper distribution files)   
    * gradlew
        * linux bash executable
    * gradlew.bat
        * windows batch executable
    * gradle/wrapper/gradle-wrapper.jar (50 KB)
        * wrapper binary distribution
    * gradle/wrapper/gradle-wrapper.properties
        * wrapper configuration
        

### sample tasks comes with the build system

Show the build environment stats include system and environment variables:
```
./gradlew bld_stats
```

Upgrade the build system itself:
```
./gradlew bld_upgrade
```
