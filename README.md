## Overview
This playbook uses the docker_centos_install to configure Docker from the target server.

## General Usage

Create the hosts file as simple as
>cat > hosts <<- EOF  
>[docker_host]  
>${TARGET_SERVER_IP}  
>EOF  

Run the playbook
>ansible-playbook provision.yml -u your_remote_user -i hosts
