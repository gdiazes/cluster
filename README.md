network:
  enp0s31f6:
    dhcp4: true
  enp4s0f0:
    addresses:
    - 192.168.13.103/24
    nameservers:
      addresses:
      - 8.8.8.8
      search:
      - /
      routes:
      - to: default
        via: 192.168.13.1
  enp4s0f1:
    addresses:
    - 192.168.13.104/24
    nameservers:
      addresses:
      - 8.8.8.8
      search: []
    routes:
    - to: default
      via: 192.168.13.1
version: 2
