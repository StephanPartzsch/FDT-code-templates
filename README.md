# FDT Code Templates #

This repository contains packages (in this case XML files) of some helpful code templates which can be used in FDT. The purpose is to have shortcuts for some code snippets that ease the process of coding ActionScript 3 and make it also faster.

   
## Packages ##

* *General Templates* - Some general templates that can be handy
  * i.e. creating a text field with a text format

* *Parsley Templates* - Templates to shorten the work with [Parsley](http://www.spicefactory.org/parsley). These templates were created for Parsley version 2.4
  * Template for adding a logger instance as a field
  * Template for *Inject* metadata tag
  * Template for *MessageDispatcher* metadata tag
  * Method stub for *Init* metadata tag
  * Method stub for *CommandComplete* metadata tag
  * Method stub for *CommandResult* metadata tag
  * Method stub for *CommandError* metadata tag
  * Method stub for *MessageHandler* metadata tag

* *Unit Test Templates* - Templates for writing unit tests with [flex unit](http://flexunit.org). These templates were created for FlexUnit version 4.1
  * Method stub for *Before* metadata tag
  * Method stub for *After* metadata tag
  * Method stub for *Test* metadata tag

 * *Mock Templates* - Templates for writing mocks with [mockito-flex](https://bitbucket.org/loomis/mockito-flex/wiki/Home).
  * Template for *Rule* metadata tag
  * Template for *Mock* metadata tag
   
## Import ##

Just open preferences in FDT (<font color="#00ACFC">CMD+,</font>) and go to <font color="#00ACFC">FDT -> Editor -> Templates</font>. Then click on the right side <font color="#00ACFC">Import...</font> and choose one of the downloaded XML files.

   
## Usage ##

Each template comes with a certain name. Type one of the name while coding and FDT shows you all appropriate templates. Choose one and hit the ENTER key. If the template contains some customizable variables, you can put through with the TAB key.

   
## Further Information ##

See the FDT tutorial about [Creating Code Templates](http://fdt.powerflasher.com/docs/Creating_Code_Templates)