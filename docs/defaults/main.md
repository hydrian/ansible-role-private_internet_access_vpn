



# main.yml
  
---
## pia_base_dir


Default location to store PIA\'s openVPN file
...
  
```

/opt/Private Internet Access/vpn
...
  
```
|Default|Type|Required|Where referenced|
| :--- | :--- | :--- | :--- |
|/opt/Private Internet Access/vpn|string|False||

## pia_endpoints_dir
  
```

'{{ pia_base_dir }}/share/endpoints'
  
```
## pia_certs_dir
  
```

'{{ pia_base_dir }}/share/certs'
  
```
## pia_download_url
  
```

https://www.privateinternetaccess.com/openvpn/openvpn.zip
...
  
```
## pia_conf_zip_file


Path where original zip file is saved
...
  
```

'{{ pia_base_dir }}/share/openvpn.zip'
  
```
|Type|Required|Default|Where referenced|
| :--- | :--- | :--- | :--- |
|string|False|{{ pia_base_dir }}/share/openvpn.zip|tasks/update.yml<br/>|

## pia_credentials_file
  
```

/etc/openvpn/credentials.pia
...
  
```
## pia_endpoint_udp_port


OpenVPN UDP port
...
  
```

1198
...
  
```
|Type|Required|Default|Where referenced|
| :--- | :--- | :--- | :--- |
|int|False|1198|tasks/main.yml<br/>|

## pia_endpoint_cipher
  
```

aes-128-cbc
...
  
```
## pia_default_profile_name
  
```

pia-default
...
  
```
## pia_customized_prefix
  
```

pia
...
  
```
## pia_start_on_boot
  
```

false
...
  
```