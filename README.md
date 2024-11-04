# ROS 2 workspace template for Docker with VSCode

## Windows

### Installation

1. &nbsp; Download XLaunch Server from https://sourceforge.net/projects/vcxsrv/ and install.
2. &nbsp; Download Docker Desktop from https://docs.docker.com/desktop/install/windows-install/ and install.
3. &nbsp; Download Visual Studio Code from https://code.visualstudio.com/download and install.
4. &nbsp; Open VS Code and install an extension (shortcut CTRL+SHIFT+X) with the name "Remote Development".
5. &nbsp; Download [repository](https://github.com/BartlomiejKulecki/ros2_ws_template/tree/Windows):\
  a) &nbsp; in web browser:\
     &nbsp; &nbsp; &nbsp; change branch to Windows, click a button `Code --> Download ZIP`, unzip,\
  b) &nbsp; or in the Command Window:\
     &nbsp; &nbsp; &nbsp; use command: &nbsp; `git clone https://github.com/BartlomiejKulecki/ros2_ws_template.git -b Windows`


### Setup ROS in Docker

1. &nbsp; Run XLaunch Server with default settings.
2. &nbsp; Run Docker Desktop (in the background).
3. &nbsp; Run VS Code and open a directory `ros2_ws_template`
4. &nbsp; Click F1 and type "Dev Containers: Rebuild and Reopen in Container" click Enter.
5. &nbsp; Wait for the installation to complete. The first time you run it, you may need to wait a little longer for the necessary software to download and install.
6. &nbsp; After all, open the terminal in VS Code and enjoy ROS 2!

