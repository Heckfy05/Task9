### Task7_Why do we need System Hardening?

For [hometask7](https://docs.google.com/presentation/d/1dWpGENLxnHXEjVzua42dJnQ-B1dsiRdzCTLU_9OJNn4/edit#slide=id.p7), we need to implement Ansible script(playbook) on any Linux distribution that will add password policies that don't use your username in the password(applicable for 'root' users as well).

    
1. On AWS Ubuntu machine when we start to create a new user(Task7) with the same password as the username it ![allow us](https://github.com/Heckfy05/Heckfy05/blob/main/11.jpeg?raw=true).
2. After implementing the Ansible ![playbook](https://github.com/Heckfy05/Heckfy05/blob/main/33.jpeg?raw=true) where we install pwquality module of PAM and configure it to decline the password proposal if it contains a user name and enforce this rule to the root user.
Now after implementing the script While we try to create the same password for user it shows us ![error message](https://github.com/Heckfy05/Heckfy05/blob/main/22.jpeg?raw=true). 