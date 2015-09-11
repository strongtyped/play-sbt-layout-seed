This is your new Play application
=================================

This file will be packaged with your application, when using `activator dist`.

This seed template generates a new project using the sbt layout instead of the default Play layout.
It's based on Typesafe's play-scala template.

## Default SBT layout

```
build.sbt                  → Application build script
src                        → Application sources
 └ main                    → Compiled asset sources
    └ java                 → Java sources
       └ controllers       → Java controllers
       └ models            → Java business layer
    └ scala                → Scala sources
       └ controllers       → Scala controllers
       └ models            → Scala business layer
    └ resources            → Configurations files and other non-compiled resources (on classpath)
       └ application.conf  → Main configuration file
       └ routes            → Routes definition
    └ twirl                → Templates
    └ assets               → Compiled asset sources
       └ css               → Typically LESS CSS sources
       └ js                → Typically CoffeeScript sources
    └ public               → Public assets
       └ css               → CSS files
       └ js                → Javascript files
       └ images            → Image files
 └ test                    → Unit or functional tests
    └ java                 → Java source folder for unit or functional tests
    └ scala                → Scala source folder for unit or functional tests
    └ resources            → Resource folder for unit or functional tests
 └ universal               → Arbitrary files to be included in your projects distribution
project                    → sbt configuration files
 └ build.properties        → Marker for sbt project
 └ plugins.sbt             → sbt plugins including the declaration for Play itself
lib                        → Unmanaged libraries dependencies
logs                       → Logs folder
 └ application.log         → Default log file
target                     → Generated stuff
 └ scala-2.10.0            
    └ cache              
    └ classes              → Compiled class files
    └ classes_managed      → Managed class files (templates, ...)
    └ resource_managed     → Managed resources (less, ...)
    └ src_managed          → Generated sources (templates, ...)
```