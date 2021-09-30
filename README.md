# Ubus

A custom Ubuntu Server (Ubuntu Server) with desktop environment and preconfigured services with port forwarded which can be accessed via host machine.

## Features

- Desktop Environment
- Import directly using Ubus ova file
- Remote Connection
- Access services on host machine refer default forwarded ports table
  |Host Machine Port|Ubus Port|Service|
  |:-:|:-:|:-:|
  |4022|22|ssh server|
  |4080|80|nginx server|
  |4800|8000|django server|
  |48080|8080|python server|
  |45900|5900|x11vnc|


# Default Login details
  ```
  username : ubus
  password : toor
  ```
  
# Connect to ubus remotely
- SSH
  ```bash
  ssh -p 4022 ubus@localhost
  ```
- vnc client
  ```
  VNCserver = 127.0.0.1:45900
  password = toor
  ```
  
# License 
[GNU General Public License v3.0](https://github.com/dmdhrumilmistry/Ubus/blob/main/LICENSE)
