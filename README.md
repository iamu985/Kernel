# Kernel
Description : Educational (non-profit) project where we build a working kernel from scratch.

## Running the development environment
*Note: An assumption is made that the system has docker already installed and running.*
1. Fork the repository.
2. Clone it into your local machine.
3. Create a local branch using the command `git branch <new name> main`.
4. Change to the branch you have created with this command `git checkout <new name>`
5. Go to `./Kernel/` there will be a buildenv directory.
6. Run the following command `docker build buildenv -t myos-buildenv`. It will take a few minutes to complete the build.
7. After the build is complete run this command `docker run myos-buildenv echo "Hello from myos"`. This should echo back "Hello from myos" in the terminal which means the build environment is up and running.<br><br>
*Note: The name `myos-buildenv` is optional you can give any name you want to the environment but make sure to not get confused.*
