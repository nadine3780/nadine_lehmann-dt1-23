# nadine_lehmann-dt1-23

Readme File - this assignment focuses on setting up a text completion system on the Google Cloud Platform that uses a proxy to interact with the Hugging Face API. The README contains explicit instructions with login details, repository cloning and a system diagram for enhanced understanding.

This assignment covers the first four learning cycles:
- Software Architecture, Bubble, API Design, Cloud Computing

Codebase
- main.py: contains all the code for the proxy including the API routes
- Pipfile, Pipfile.lock: dependency file for running the codebase
- Dockerfile: docker build configuration

Github
- Username: nadine3780, repository name nadine_lehmann-dt1-23
- https://github.com/nadine3780/nadine_lehmann-dt1-23
- Cloned the repository locally with SSH
- Created my private git repository called nadine-lehmann-dt1-23 and created the README.md file
	
Docker 
- Docker Hub username: nadine3780
- Logged in to Docker Desktop and Docker Hub
- Locally built a Docker image in the terminal
- Created a new repository on Docker Hub named nadine3780/dt1_assignment
- Tagged the local image
- Pushed the image to the nadine3780/dt1_assignment repository on Docker Hub

Hugging Face 
- Nadine3780's access token: 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
- Associated project/repository: dt1_assignment
- Account creation process - navigated to settings, generated a new token
- The token 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 is used for authentication and authorization on Hugging Face. It allows interactions with Hugging Face's APIs for tasks such as model deployment, fine-tuning, and accessing datasets and models.

On the Google Cloud Platform
- Established a new instance named vm-dt1
- Initiated the instance and accessed it via SSH
- Installed Docker on the virtual machine (VM)
- Logged into Docker and verified its status on the VM
- Pulled a Docker image from a repository to the VM
- Modified the VM's firewall settings to enable the execution of the Docker image and execute the Docker image as needed 
- Firewall: No restrictions on the ports or protocols, authorized IP ranges 0.0.0.0/0

Bubble
- https://nadine-lehmann.bubbleapps.io/version-test?debug_mode=true
- Created and activated a new app
- Defining the input, output and button for the frontend interface
- Connecting the API response to the user in Bubble

Occurred problems: 
1. When stopping the VM on the Google Cloud Platform, the external IP had to be updated in the HTLM code on Bubble
   - External IP for VM 34.65.167.39
2. "Could not get a response from the bot" - when the bot is accessible from my own device, but not from another device


Architecture diagram
	- Used the graph drawing software https://draw.io/
	- Visualising the individual applications used and show it in the overall context of this assignment


 ![Architecture diagram](https://github.com/nadine3780/nadine_lehmann-dt1-23/blob/main/DT1-architecture_Nadine%20Caterina%20Lehmann.drawio.png)

	
