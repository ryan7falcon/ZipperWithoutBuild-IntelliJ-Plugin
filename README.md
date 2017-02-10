This IntelliJ plugin allows to export a project to a zip file, excluding any build folders. That zip file will be created inside your project folder. You can create several zip files one after another and they will not include previosly created zips, the plugin keeps track of them using .zipper file and exculdes them during exporting.

Original code here https://github.com/renemaas/Zipper-IntelliJ-Plugin
 - Added a menu item File->Export to Zip...
 - Excluded build folder from archivig
 
 To start Plugin development refer to http://www.jetbrains.org/intellij/sdk/docs/index.html
 
 To just run&debug this code set up the dev environment: http://www.jetbrains.org/intellij/sdk/docs/basics/getting_started/setting_up_environment.html
 
 To install the compiled plugin ("ZipperWithoutBuild.jar") copy it to C:\Program Files\Android\Android Studio\plugins or .IntelliJIDEAx0\config\plugins
