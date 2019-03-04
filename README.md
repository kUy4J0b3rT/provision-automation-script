# provision-automation-script
Update and install services for developer use.
Use this script if you'll provision on your Ec2 instance.

Where to put the script?
  AWS > EC2 > Launch Instance > Configure Instance > User Data

Jobs that will be made by the script
  Logs every echo made
  Change to root permission
  Updates the system (EC2 instance)
  Downloads the required modules or services, like mysql, php and etc.
  Restart apache web server
  Appends the user(ec2-user) to the group(apache)
  Checks if the path is existing
  Changes the ownership of the folder
  Change the permission of the folder
