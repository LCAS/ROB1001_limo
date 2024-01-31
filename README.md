# ROB1001 Limo
A repository for the ROB1001 module using ROS2 and Limo robot simulation.

## 1. Create a fork of this repository

Click on fork at the top of this page to create a copy of this repository in you GitHub account.

![Fork](.assets/fork.png) 

## 2. Clone you repository on your computer

Open the terminal on your computer and navigate (`cd`) to where you want to store the Limo ROS2 repository.

Then run `https://github.com/<username>/ROB1001_limo.git`, this will download the repository on your computer.

## 3. Setup your working environment

1. Make sure you have VSCode installed: https://code.visualstudio.com/download
2. Make sure you have the `Docker` and the `Dev Containers` extension in VSCode installed and working: https://code.visualstudio.com/docs/containers/overview and https://code.visualstudio.com/docs/devcontainers/containers
    * Ensure docker is working, i.e. try `docker run --rm hello-world` and check it succeeds for your user, the output should be "Hello from Docker!"
3. The docker image used for the Development Container is provided by the [L-CAS](https://lcas.lincoln.ac.uk) Container Registry. You must log in to use it. For simple read access, the username and password are public and is username `lcas` and password: `lincoln`.
4. To log in run `docker login -u lcas -p lincoln lcas.lincoln.ac.uk` (you should only have to do this once, as the credentials should be cached unless your home directory is wiped).

## 4. Open in VSCode

1. Open your own ROB1001_limo repository in VSCode, click on Open Folder and open your repository folder.

![image](https://github.com/LCAS/ROB1001_limo/assets/6209386/4ad214b9-cd15-4f12-8007-1cbdce5240f6)

2. VSCode should prompt you that there is a devcontainer configured and ask if you want to reopen in container. Click Reopen Container.

![image](https://github.com/LCAS/ROB1001_limo/assets/6209386/edb5369e-5823-48d3-9dab-a2a840aa4776)

## 5. Access the embedded Remote Desktop

1. Click on the "Port" in VSCode, find the "novnc" port, right click on it to open the menu, and then choose either "Open in Browser" to open it outside of VSCode or "Preview in Editor" to have it open within VSCode:

   <img width="735" alt="image" src="https://github.com/LCAS/ros2-teaching-ws/assets/1153084/2b0bdfa9-07ea-4238-a0b9-dd2dc8f4c111">

2. (recommended) Set the dekstop scaling by clicking on the settings cog and choose scaling mode "Remote Resizing" if it's not set

   <img width="292" alt="image" src="https://github.com/LCAS/ros2-teaching-ws/assets/1153084/2d9bc88e-7319-4723-968a-0aa08db026ef">

3. click on "Connect" and enter the password `vscode` when prompted:

   <img width="455" alt="image" src="https://github.com/LCAS/ros2-teaching-ws/assets/1153084/ddc224eb-5980-4d9a-994e-b05aa1e9fc1d">


