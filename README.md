# nodejs #

Install and configures Nodejs

# Role Variables #

## Default Variables ##

   - name: nodejs_version
     desc: nodejs version to be installed
     value: 8.x

# Dependencies #

None

# Example Playbook #

    - hosts: all
      roles:
        - role: nodejs
