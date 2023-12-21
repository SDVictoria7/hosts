[routers:vars]
ansible_user=admin 
ansible_password=adminpass
ansible_network_os=ios
nsible -c network_cli -m ios_command -a "commands='sh clock'" all
