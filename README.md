# proautomate_poweredge



ProAutomate automation for PowerStore

Setup the server.
Login as the dellautomate user
Copy the contents of proautomate_vm_setup.sh to the home directory of the user
Chmod the proautomate_vm_setup.sh to 700 (user rwx, noone)
Run the script proautomate_vm_setup.sh
Log into Jenkins at http://:8443
Setup Jenkins server
Copy the contents of install_jenkins_plugins.sh to the home directory of the user
Chmod the install_jenkins_plugins.sh to 700 (user rwx, noone)
Copy the contents of the public key to the git server as the service account user (for login to repos))
Log into jenkins as the dellautomate user
Create Job Builder Job
Run the job
Do in-script approval
Run the job again
Set up the data structures
Run each individual job