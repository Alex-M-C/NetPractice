*This project has been created as part of the 42 curriculum by **aleconst**.*

## Description

NetPractice is a practical exercise designed to introduce the foundational concepts of computer networking. The primary goal is to configure small-scale, simulated networks to ensure they function correctly. 

Throughout this project, you'll learn how to configure IP addresses, connect devices through routers, and understand the critical role of a default gateway within a network. By completing 10 distinct levels, develop a hands-on understanding of TCP/IP addressing and routing tables.

## Instructions

### Running the Interface
To start the training interface, follow these steps:
* Download and extract the project files into a folder of your choice.
* Navigate to the folder in your terminal and execute the provided shell script: `./run.sh`
* This script will launch a local web server and open the dedicated page in your preferred web browser.
* If the script fails due to technical constraints, you can start the server manually by running `python3 -m http.server 49242` and then navigating to `http://localhost:49242` in your browser.

### Usage and Exporting Configurations
* Upon opening the interface, enter your intranet login to load your personal configuration.
* For each level, modify the unshaded fields in the network diagram until the objectives are met and the network functions properly.
* Click the **Check again** button to verify your configuration. 
* Once a level is successfully completed, click the **Get my config** button to export and download your configuration file before moving to the next level.

### Submission Requirements
* You must complete all 10 training levels.
* Ensure you have exported the configuration file for each level using the "Get my config" button.
* Place all 10 exported configuration files directly at the root of your Git repository for submission.

## Resources

This project requires a solid understanding of several core networking concepts. Below are the key topics studied and applied during this exercise:
* **TCP/IP Addressing:** Understanding how IP addresses identify devices on a network.
* **Subnet Masks:** Learning how networks are divided and how to determine network and host portions of an IP address.
* **Default Gateways:** Understanding how devices communicate outside of their local network.
* **Routers and Switches:** Grasping the hardware roles in directing and forwarding network traffic.
* **OSI Layers:** Conceptualizing the framework of network communication.

### AI Usage
* **Investigation**: AI was used for awnsering questions about in-depth investigation of IP addressing, subnet masks and gateways
