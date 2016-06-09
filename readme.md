# DWA - Andrea Franco
## Server Links

+http://107.170.106.108/  Live Server

+http://162.243.31.206/  Stage Server

## Deployment Plan

	1. Create droplet in DigitalOcean for StageServer

		*SSH Into server
		*Create Non-root user
		*Install and Update software
		*Install Git
		*Install Apache2

<<<<<<< HEAD
	

	2. Configure Git Deployment
=======
	2. Create droplet in DigitalOcean for LiveServer

		*SSH Into server
		*Create Non-root user
		*Install and Update software
		*Install Git
		*Install Apache2

	3. Configure Git Deployment
>>>>>>> 3e3f72745461ce379949b3d9014f864e1f255f70

		*Create directory for repository
		*Configure Sever Post Hook
		*Add git remotes for servers 

<<<<<<< HEAD
	3.Add and commit to stage server 

	
=======
	4.Add and commit to stage server 

		*If everithing looks ok go to step 5
		*Else debug 

	5. Add and commit to Live Server
>>>>>>> 3e3f72745461ce379949b3d9014f864e1f255f70
