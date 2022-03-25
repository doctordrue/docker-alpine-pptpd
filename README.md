# docker-alpine-pptpd
Build docker image based on Alpine linux with PPTP server.

### Usage
1. clone repo to your local machine
2. Create chap-secrets file in project folder to store usernames & password required to connect to pptpd.
Example:

		# Secrets for authentication using PAP
		# client    server      secret      acceptable local IP addresses
		username	*			password	*
3. Run:

		//start server
		docker compose up -d
	
		//stop server
		docker compose down
	
	
