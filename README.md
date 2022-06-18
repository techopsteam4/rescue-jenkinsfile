# rescue-jenkinsfile
There are two ways: UI and CLI
Using the UI method
Step 1: Spin up a new instance
Step 2: Install Jenkins and Java on it and complete Jenkins UI configuration, install all suggested plugins and the job import plugin and thinBackup plugin
Open your Jenkins UI, click on manage jenkins ==> click on manage plugins ==> go to available ==> search for job import plugin and thinbackup plugin ==> click on them and select install without restart. 
Step 3: Configuration: Go back to dashboard and locate the job import plugins on the left side under blue ocean 
a. Go to manage jenkins==>config system==>scroll down to locate job import plugins==>add the old jenkins server name==>go and copy the old URL and paste it into the URL location.
b. Configure credentials using the old jenkins credentials ==>select the newly configured credentials==> apply==> save
Step4: Import Jobs from old Jenkins server to new server
Click on job import plugins==>click on search into folder==>click on query==> check Install required plugin then check jobs to import ==> click on import

NOTE: FURTHER CONFIGURATION WILL BE NEEDED IF ANY CHANGES ARE TO BE MADE ON THE PREVIOUS JOBS.
