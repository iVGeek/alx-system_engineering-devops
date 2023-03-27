### Web server
## Concept Based on:
``` Powershell
DevOps
SysAdmin

```
## Background Context

In this project, some of the tasks will be graded on 2 aspects:

1 .Is your web-01 server configured according to requirements

2. Does your answer file contain a Bash script that automatically performs commands to configure an Ubuntu machine to fit requirements (meaning without any human intervention)

For example, if I need to create a file /tmp/test containing the string hello world and modify the configuration of Nginx to listen on port 8080 instead of 80, I can use emacs on my server to create the file and to modify the Nginx configuration file /etc/nginx/sites-enabled/default.

But my answer file would contain:
``` powershell
user@ubuntu cat 88-script_example
#!/usr/bin/env bash
# Configuring a server with specification XYZ
echo hello world > /tmp/test
sed -i 's/80/8080/g' /etc/nginx/sites-enabled/default
user@ubuntu

```
As you can tell, I am not using emacs to perform the task in my answer file. This exercise is aiming at training you on automating your work. If you can automate tasks that you do manually, you can then automate yourself out of repetitive tasks and focus your energy on something more interesting. For an SRE, that comes very handy when there are hundreds or thousands of servers to manage, the work cannot be only done manually. Note that the checker will execute your script as the root user, you do not need to use the sudo command.
A good Software Engineer is a [lazy Software Engineer.](https://intranet.alxswe.com/rltoken/sRY__axKNHhNW0SVmsUC_A)

![image](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/266/82VsYEC.jpg)

![image](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/01cab59e881e31842b8d47a0974e8d3b6f0f2001.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230327%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230327T160802Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0ea4d14046912c90a11ac6fadbb965c15b3153146ca3a8d2039644592edda3db)