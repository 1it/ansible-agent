# Ansible-agent
Ansible helper. Runs an Ansible projects in pull-like mode.

## Make it simple
Actually this is the bash script that can simplify run tasks at your Linux-hosts.

## Just run it
```
./ansible-agent -i
```

## Usage
```
     Usage: ansible-agent [OPTION]

     -p  | play             run local playbooks (e.g. update configs)
     -s  | selfupdate       ansible-agent selfupdate
     -r  | update           pull your project repo updates
     -a  | all              run all tasks
     -i  | initial             first run

     Example:
        sudo ansible-agent all
```

Check for example playbook in playbooks/ directory also example inventory file can be found at inventory/ directory.

Also check for test roles here: https://github.com/1it/ansible-test