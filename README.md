Ansible to update latest code in repository:
===========================================
## what is ansible?
Ansible is an open-source automation engine that automates software provisioning, configuration management, and application deployment.

## installation

```
apt-get install ansible
```

## what is ansible-playbook?

Playbooks are Ansible’s configuration, deployment, and orchestration language. They can describe a policy you want your remote systems to enforce, or a set of steps in a general IT process.

## pre-requisites

Before proceeding to run, you may have to change some configuration in hosts, group_vars folder to make it for you. 

After cloning ansible project, go to your code repository and do following.

```
mv .git/pre-push.sample .git/pre-push
sudo emacs -nw .git/pre-push

```

and copy the code in git_push.sh and save it. Now everytime you push it, it will pull in corresponding code repository.


## to do

* execute ansible playbook after every git push.
* restart apache only for preproduction environment




