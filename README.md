ModularInsertion
================

This is the first attempt at building a framework that can handle seperate module projects

Copy the template module and rename it, Write your code within it's structure and include it's includer file in the main cpp.
Then add the instruction   moduleManager::getSingleton()->RegisterModuleSingleton("YourModule",  YourModule::getSingleton() );
within the main loop. 

After this, the initialisation is automatically called and your own loop is called as well.
Cleanup is performed when the program closes. Write all cleanups within your own cleanup section.

================
