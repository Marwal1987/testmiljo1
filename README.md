# testmiljo
Vagrant automation making a database and a nextcloud vm 
all the action is in the /vagrantfile
so the first mission will be to config the global ( i have already fixed a bit with bridge question when doing a up.) 
from line 94 on vagrantfile i will remove from the global and put in a new directory /dbmiljo
in /db miljo will sync with the global and run script automatic. (have to fix a port for this enviroment) and the same with nextmiljo) 
if you guys want to test the automation you can copy the vagrantfile in testmiljo and then just do the command vagrant up. it should work. :) 
