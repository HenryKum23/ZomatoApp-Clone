Sure! Here’s a marked-up version of your documentary for deploying the ZomatoApp-Clone on an EC2 instance:

---

# Deploying ZomatoApp-Clone on EC2 Instance with Docker

## Prerequisites

1. **Create AWS Account**  
   I already have an AWS account and won’t be creating a new one.

2. **Create a DockerHub Account**  
   I already have a DockerHub account and won’t be creating a new one.

3. **Create a GitHub Account**  
   I already have GitHub and won’t be creating a new one.

4. **Download a Code Editor**  
   Download Visual Studio Code or another code editor.

## Deployment Process

1. **Launch an EC2 Instance on AWS**  
   Start by launching a new EC2 instance in your AWS console.

2. **Update and Upgrade the Ubuntu Server**  
   After launching, run the following command to update and upgrade your Ubuntu server:
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```

3. **Download and Install Docker**  
   Follow the appropriate instructions to install Docker on your EC2 instance.

4. **Clone the Source Code**  
   Use the following command to clone your source code repository:
   ```bash
   git clone https://github.com/HenryKum23/ZomatoApp-Clone.git
   ```

5. **Create the Dockerfile**  
   In the directory where the cloned source code is located, create a Dockerfile.

6. **Build the Application Images**  
   Build the application images with this command:
   ```bash
   docker build -t <name-you-want-to-give-the-image> .
   ```

7. **Run the Container**  
   Once the image has been built, run it as a container and expose the container to the public using the following command:
   ```bash
   docker run --name <container-name> -p <browser-port>:<container-port> <image-name>
   ```

8. **Access the ZomatoApp**  
   Once the previous step is successful, access your ZomatoApp in the browser.

## Contributions
For any contributions, do not hesitate to contact me.

https://github.com/HenryKum23/ZomatoApp-Clone

Thank you!

--- 

