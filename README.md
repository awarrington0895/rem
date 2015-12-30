When the install script is ran, the rem.sh script will replace your native rm command.  It will use an alias in your .bashrc file to accomplish this.  If for any reason you wish for the rem.sh script to stop replacing your rm command, simple edit your .bashrc file and remove the alias created by the install script.

The path to the rem.sh folder must remain the same as when you first ran the install script.  Otherwise the alias will not work.
