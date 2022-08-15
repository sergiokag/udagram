# PIPELINE PROCESS

For the pipeline process we are using CircleCi
which is bind to the Udagram repo. 

So, when a commit occurs then an pipeline process begins.

The process goes like this:

- The environment is setting up and then enviroment variables
- Using the orbs Node, AWS cli and EB cli are installed
- Configuring AWS Access Key ID
- Then Udagram repo is cloned
- Then the frontend and the backend npm scripts are executed ( install, build, deploy ) 