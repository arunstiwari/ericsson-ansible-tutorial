# Finding the version of ansible-playbook
1. ansible-playbook --version
2. ansible --version
3. ansible localhost -m ping
4. ansible localhost -a "uname -a" -u setup
5. ansible localhost -m yum -a "name=git"  --become
# Install the httpd service
6. ansible localhost -m yum -a "name=httpd state=latest"  --become
## Verify the service using command which httpd
7. ansible localhost -m yum -a "name=httpd state=absent"  --become

8.