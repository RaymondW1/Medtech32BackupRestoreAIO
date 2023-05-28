# Medtech32BackupRestoreAIO
Medtech32 Backup &amp; restore script all in one 

This script executes a full backup & restore of Medtech32 Application databases while also calling on service mode. Most traditional Medtech32 information to do with Embarcadero & Interbase XE7 runs without service mode, using a network protocol instead of direct storage protocol to backup & restore databases. Many techs have realised running the process within IB Console is faster since it runs directly on the storage protocol vs network protocol. 

Documentation referenced below for testing the script. Any comments appreciated as well as improvements
https://docwiki.embarcadero.com/InterBase/2020/en/Performing_backups_and_restores_using_the_gbak_command
https://www.ibexpert.net/ibe/pmwiki.php?n=Doc.FirebirdAndInterBaseCommandLineUtilities

The code can be saved & used as a batch file or powershell script
