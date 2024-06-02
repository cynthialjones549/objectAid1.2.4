# ObjectAid1.2.4
Read the ObjectAid_Install_Instructions.pdf

Add to your eclipse.ini the following vmargs: 
--add-opens=java.base/java.lang=ALL-UNNAMED 
--add-opens=java.base/java.util=ALL-UNNAMED 
--add-opens=java.base/java.text=ALL-UNNAMED 
--add-opens=java.desktop/java.awt.font=ALL-UNNAMED


Restart Eclipse with -clean to ensure the OSGI cache is purged
