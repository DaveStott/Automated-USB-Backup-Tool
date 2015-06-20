# Automated-USB-Backup-Tool

Automatically backup selected folders on your Widndows 7 & XP PCs (I have no other versions to test this on)
to USB device when the USB device is inserted.

The tool is a is a VBScript with a HTA front end which you can select folders to backup to a specific USB device

Basic instructions:

On the folders to backup tab, select the local drive where the folders are that you want to backup and click add.
Select the folder you want to backup (it will only allow one folder to be selected at a time and will backup all subfolders)
Add as many folders as required.
On the backup task details tab decide which backup type you want (hover over the boxes to get tool tips)
Select the USB device to backup you folders to, if the USB device is not already inserted then plug it in and click the
refresh button.
Once you have selected the USB drive then make sure it has a unique name to idenify it to the script, making suer that the name
is 11 charater or less or it won't work.
You can rename the device by typing the desired name and clicking the tick to update it.
Click Create / Update Task and the tool will create a scheduled task that triggers on login 
(with a 5 minutes delay after login - not sure why this was done and cna be change if you want)

If you want to edit or delete the task then either ammend you folder selection and click Create / Update Task again 
or just click Delete Task and then restart the PC.


