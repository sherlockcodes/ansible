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


## how to run

```
Command : ansible-playbook -i hosts tasks/git_pull.yml --extra-vars='host=test'
```

## to do

* execute ansible playbook after every git push.
* restart apache only for preproduction environment




