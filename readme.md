#Usage
1. Copy `adfilter.action` and `adfilter.filter` to configure directory
  for Linux
  `/etc/privoxy/`
  for Windows
  `C:\Program Files\Privoxy\`

2. Add following lines
  ```
  actionsfile adfilter.action
  filterfile adfilter.filter
  ```
  in privoxy config file
  for Linux
  `/etc/privoxy/config`

  for Windows
  `C:\Program Files\Privoxy\config.txt`
  or
  `Options` > `Edit Main Configuration`
