# DWA - Andrea Franco
## Server Links

*Live Server*

andreafp.com
http://107.170.106.108/  

*Stage Server*
http://162.243.31.206/  

## Deployment Plan

	1. Create droplet in DigitalOcean for StageServer

		*SSH Into server
		*Create Non-root user
		*Install and Update software
		*Install Git
		*Install Apache2

	2. Create droplet in DigitalOcean for LiveServer

		*SSH Into server
		*Create Non-root user
		*Install and Update software
		*Install Git
		*Install Apache2

	3. Configure Git Deployment

		*Create directory for repository
		*Configure Sever Post Hook
		*Add git remotes for servers 

	4.Add and commit to stage server 

		*If everithing looks ok go to step 5
		*Else debug 

	5. Add and commit to Live Server

	

	

