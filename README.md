# Sailfish OS doubletab display configurator

Sailfish OS repository for doubletab_display_configurator

Required packages: wget => https://openrepos.net/content/nieldk/wget (or copy sourcecode manually )

Install instructions:
1. Connect to Sailfish device via terminal or open terminal directly on device
2. Download script code ( wget https://github.com/speefak/sfos-doubletab_display_configurator/archive/master.zip )
3. Unpack zipfile ( unzip master.zip )
4. Make script executeable ( chmod 755 sfos-doubletab_display_configurator-master/doubletab_display_configurator )
5. Copy script to /usr/local/bin ( devel-su cp sfos-doubletab_display_configurator-master/doubletab_display_configurator /usr/local/bin/ ) 
6. execute script ( doubletab_display_configurator -sw )

#---------------------------------------------------------------------------------------------------------------------------

Additional information:

It's not neccessary to install doubletab_display_configurator in /usr/local/bin. Script runs also without root priviliges, but for package installation in future releases root permissions are required. You can copy the script everwhere into the system, the execution path for the icon will updated after first execution from terminal 


#---------------------------------------------------------------------------------------------------------------------------

TODO: Configfunction does not work, because read command parameter is mssing in sfos read version. Varios configurations via mcetool command are available. 
