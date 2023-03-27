
After a clean or at first time you need to compile and install classes.
In Eclipse, go to the File menu and choose:

  Run -> Run Configurations...

  Right click on Maven Build -> New
  
  Write the name of the configuration "Mooshak Compile Classes"
  
  Click Base Directory Workspace... ... -> Select this project
  
  Write the Goals of the configuration "clean compile install"
  
  Check Skip Tests
  
  Click Apply and the Finish.
  
You can now go to Run -> Run As ... -> Maven Build and double-click Mooshak Compile Classes

To run GWT dev mode you need this configuration.
In Eclipse, go to the File menu and choose:

  Run -> Run Configurations...

  Right click on Maven Build -> New
  
  Write the name of the configuration "Mooshak Run"
  
  Click Base Directory Workspace... ... -> Select this project
  
  Write the Goals of the configuration "clean gwt:run"
  
  Check Skip Tests
  
  Click Apply and the Finish.
  
You can now go to Run -> Run As ... -> Maven Build and double-click Mooshak Run

To debug a Maven GWT project use this configuration.
In Eclipse, go to the File menu and choose:

  Run -> Run Configurations...

  Right click on Maven Build -> New
  
  Write the name of the configuration "Mooshak Debug"
  
  Click Base Directory Workspace... ... -> Select this project
  
  Write the Goals of the configuration "gwt:debug"
  
  Check Skip Tests
  
  Click Apply and the Finish.
  
You can now go to Run -> Run As ... -> Maven Build and double-click Mooshak Debug,
then, to connect to this process, select the Run -> Debug Configurations.... 
In the pane on the left, choose Remote Java Application and click the New launch configuration button 
above the list. The important settings to note are the Host and Port fields. The host value must match 
the hostname of the Tomcat process, and the port should be 8000. You also might need to add entries on 
the Source tab to ensure that all of the source code is available to step through.

To export a Maven GWT project as war use this configuration.
In Eclipse, go to the File menu and choose:

  Run -> Run Configurations...

  Right click on Maven Build -> New
  
  Write the name of the configuration "Mooshak Package War"
  
  Click Base Directory Workspace... ... -> Select this project
  
  Write the Goals of the configuration "clean compile gwt:compile install war:war"
  
  Check Skip Tests
  
  Click Apply and the Finish.
  
You can now go to Run -> Run As ... -> Maven Build and double-click Mooshak Package War.

