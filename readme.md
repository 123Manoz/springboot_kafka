**How to run this program ?**
    
    Compatibility can be issue for running springboot program. Spring boot plugins might not be compatible with certain java versions. 
   1. Spring boot 3.X versions are only compatible with java17 versions 
   2. Gralde 8.x higher are compatible with java 17 versions

Requirements: 

* Right version of java are needed to run this program locally 
* java 17
* gradle 8.0.2
* spring boot 3.X 
* Use sdkman to manage dependencies 

Instructions to install [sdkman](https://sdkman.io/install)

```
$ curl -s "https://get.sdkman.io" | bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
$ sdk version
$ skd list java 
$ skd install java 17.X.version
$ sdk install gradle 8.0.2** 
```

command for build and run

```
$ ./gradlew clean build 
$ ./gradlew bootRun 
```

This application will load bunch of application beans shows name of classes loaded by default application 

On top of which springboot applications can be build. 

To get started you can either copy this class or you can use

gradle init as well,

But Remember to have right version of java gradle and springboot 

 ***************** Next Section ******************************
 
**Spring boot Application with Kafka and Rest Apis** 
