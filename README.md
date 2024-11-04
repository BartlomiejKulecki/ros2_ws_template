# ROS 2 workspace template for Docker with VSCode

## Ubuntu

### Installation

1. &nbsp; Download Docker Engine, instruction: https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository
2. &nbsp; Optionally, you can follow a post-installation steps from Docker documentation:\
   &nbsp; https://docs.docker.com/engine/install/linux-postinstall/
3. &nbsp; Download and install Visual Studio Code with command: &nbsp; `sudo apt-get install code`
4. &nbsp; Open VS Code and install an extension (shortcut CTRL+SHIFT+X) with the name "Remote Development".
5. &nbsp; Download [repository](https://github.com/BartlomiejKulecki/ros2_ws_template):\
  a) &nbsp; in web browser:\
     &nbsp; &nbsp; &nbsp; change branch to Ubuntu, click a button `Code --> Download ZIP`, unzip,\
  b) &nbsp; or in the Terminal:\
     &nbsp; &nbsp; &nbsp; use command: &nbsp; `git clone https://github.com/BartlomiejKulecki/ros2_ws_template.git -b Ubuntu`


### Setup ROS in Docker

1. &nbsp; Run Docker Engine with command `sudo systemctl start docker` (may not be necessary).
2. &nbsp; Run VS Code and open a directory `ros2_ws_template`
3. &nbsp; Click F1 and type "Dev Containers: Rebuild and Reopen in Container" click Enter.
4. &nbsp; Wait for the installation to complete. The first time you run it, you may need to wait a little longer for the necessary software to download and install.
5. &nbsp; After all open terminal and enjoy ROS 2!

