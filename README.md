## ansible-role-danted
Ansible Role: Dante (Socks Server)
## Requirements
Debian 7 8 9 x86-65 ARM
## Role Variables
dante_version: 1.4.2
dante_working_dir: /tmp
auto_settings: true
auto_settings: false
client_pass:
  - ip: 192.168.0.1/24
client_block:
  - ip: 0.0.0.0/0
socks_pass:
  - ip: 0.0.0.0/0
