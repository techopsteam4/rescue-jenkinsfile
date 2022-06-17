# rescue-jenkinsfile
There are two ways: UI and CLI
the first one we will use UI.

Step 1: Create another Jenkins server and config the Jenkins on it.
Step 2: Log into the Jenkins server created
Step 3: Install in plugins : specifically job import plugins and thinbackup plugins. 
> Open your Jenkins, click on manage jenkins ==> click on manage plugins ==> go to availables ==> search for job import plugins and thinbackup plugins ==> click on them and select install without restart.
Step 4:Go back to dashboard and locate the job import plugins on the left side under blue ocean.
Step 5:Configuration
a. Go to manage jenkins==>config system==>scroll down to locate job import plugins==>add the old jenkins server name==>go and copy the old URL and paste it into the URL location.
b. Configurate the credentials using the old jenkins credentials.
Step 6: Apply and save.
Step 7: Go back to dashboard
Step 8: Click on job import plugins==>click on search into folder==>click on qeuery
Step 9: The previous jobs and you select the jobs you need.
Step 10: Check install plugins required and also click import
Step 11: wait for the jobs to come in and they will on the dashboard.
NOTES: FURTHER CONFIGURATION ARE NEEDED IF NY CHANGES ARE TO BE MADE ON THE PREVIOUS JOBS.
