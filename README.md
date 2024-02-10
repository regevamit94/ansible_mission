# ansible_mission
Ansible Mission Repository


basic-installs role: Updating repositories, upgrading OS and installing packages.
apache_httpd_install role: Installation on HTTPD for RedHats and Apache2 for Debians.
os_count role: Inserts each OS to a localfile named "count_file" in "files" folder and then counts the amount of each OS. 

hosts: grouping the hosts to OS groups 
group_vars: managing remote SSH connections requirements for each OS
main.yml: running the roles.
