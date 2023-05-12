# ansible
It is a configuration management tool where we can make changes to the existing infrastructure.

- We need not have to install ansible on servers, ansible will do everything from our local system.
- In inventory file we mention servers information.
- ansible connects to servers through ssh and runs play books in servers.

## installed tomcat and nginx on server with command:
```
ansible-playbook -i inventory <playbook-name> --limit <host>
```

### suggestions:
#### changes to be made in server to start tomcat successfully:
- check environment variables.
- change the shutdown.sh and tomcat.pid permissions if it has PID issue.