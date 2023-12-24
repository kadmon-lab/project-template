# project-template

Here's a quick guide on how to start a project:

1. Ensure you have installed git on your system.
2. Clone this project via git clone
3. Use VSCode's ```Create Environment``` command to install the packages into the environment. From there on, this environment's ```pip``` will take care of installing remaining packages.

For remote computing, there are two options:
1. Connect to a remote runtime kernel and have code snippets sent to the remote machine, getting only figures and prints back (bad if you are dealing with a lot of data).
2. Have all your data and code on the remote machine and remote control it.

Check [this article](https://code.visualstudio.com/docs/datascience/notebooks-web) or [this one](https://code.visualstudio.com/blogs/2022/12/07/remote-even-better#_enable-tunneling-from-vs-code-ui). In particular, it is possible to connect via a 'tunnel', without the need to setup SSH. 
