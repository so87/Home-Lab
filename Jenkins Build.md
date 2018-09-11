# How to build projects with Jenkins
Need to download plugins for sonarqube, docker, ssh, badges, and github

## Make ssh key for jenkins machine

Navigate to the below area on github and create an SSH key for your jenkins machine.  This is 
so jenkins can push dev code to production.
<p align="center">
  <img width="400" height="500" src="https://github.com/so87/Home-Lab/blob/master/pics/git%20ssh%20keys.png">
</p>

## Setup jenkins bulid to poll github for events, scan with sonarqube, and deploy

### Pull code from repository
<p align="center">
  <img width="760" height="760" src="https://github.com/so87/Home-Lab/blob/master/pics/source%20code%20management.png">
</p>

### Trigger the build after a commit has been pushed to github
<p align="center">
  <img width="760" height="760" src="https://github.com/so87/Home-Lab/blob/master/pics/build%20trigger%20and%20env.png">
</p>

### Nightly jenkins event
<p align="center">
  <img width="760" height="560" src="https://github.com/so87/Home-Lab/blob/master/pics/nightly%20%20build.png">
</p>

### Deploy containers
<p align="center">
  <img width="760" height="500" src="https://github.com/so87/Home-Lab/blob/master/pics/deploy.png">
</p>

### Destroy containers
<p align="center">
  <img width="760" height="500" src="https://github.com/so87/Home-Lab/blob/master/pics/destroy%20containers.png">
</p>

### Push the results back to production
<p align="center">
  <img width="760" height="760" src="https://github.com/so87/Home-Lab/blob/master/pics/push%20to%20git.png">
</p>

<p align="center">
  <img width="760" height="760" src="https://github.com/so87/Home-Lab/blob/master/pics/git%20settings.png">
</p>
