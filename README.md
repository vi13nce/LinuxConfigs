# Linux service Configs
# Summary:
This is a repo of config files for Ubuntu (debian) based linux systems and services. Useful for pulling down for cloud installs. 
The config files should have the full path where they go to work. Some contain variables to find an replace in your install script (yes, you have to read what your downloading).

## [WIKI](https://github.com/lunarobliq/LinuxConfigs/wiki)
The lightly maintained wiki might have some additional info.

## [htaccess](https://github.com/lunarobliq/LinuxConfigs/blob/master/.htaccess)
        Apache2 redirector and server config file that tell the server how to handle listed requests.

## [000-default.conf (HTTP/HTTPS CONFIG)](https://github.com/lunarobliq/LinuxConfigs/blob/master/000-default.conf)
        Apache2 server configure file. Good for TLS/SSL, port config, and request handling. Also fixes that Open directory browse-able issue with apache.

## [000-default.conf_2 (HTTPS CONFIG w/redir 80->443)](https://github.com/lunarobliq/LinuxConfigs/blob/master/000-default.conf_2)
        Apache2 server configure file. Good for TLS/SSL, port config, and request handling. Also fixes that Open directory browse-able issue with apache.
        
 ## [000-default.conf_3 (HTTP CONFIG)](https://github.com/lunarobliq/LinuxConfigs/blob/master/000-default.conf_3)
        Apache2 server configure file. Good for TLS/SSL, port config, and request handling. Also fixes that Open directory browse-able issue with apache.       
     
 ## [404.html](https://github.com/lunarobliq/LinuxConfigs/blob/master/404.html)
        A nice example 404 page found on Github somewhere (I Googled it). 
        
  ## [50-default.conf](https://github.com/lunarobliq/LinuxConfigs/blob/master/50-default.conf)
        A blank example config for rsyslog
        
  ## [50unattended-upgrades ](https://github.com/lunarobliq/LinuxConfigs/blob/master/50unattended-upgrades)
        Master config file that will tell unattended-upgrades to download and install security updates but not restart OS but will restart service.

  ## [51myunattended-upgrades](https://github.com/lunarobliq/LinuxConfigs/blob/master/51myunattended-upgrades)
        Running config file that will tell unattended-upgrades to download and install security updates but not restart OS but will restart service.g

  ## [CobaltStrike-filebeat.yml](https://github.com/lunarobliq/LinuxConfigs/blob/master/CobaltStrike-filebeat.yml)
        Filebeat log forwarder config for server to send logs from CS server. Great fro REDELK.

  ## [apache-404.conf](https://github.com/lunarobliq/LinuxConfigs/blob/master/apache-404.conf)
        A custom 404 page lets you provide a user-friendly website to your visitors even in the midst of an error. Very few users, when presented with a 404, will do more beyond click back to get out of the mistake. A custom 404 page is a good opportunity to keep them on your site and do more to redirect them to their destination.
        
  ## [apache2.conf](https://github.com/lunarobliq/LinuxConfigs/blob/master/apache2.conf)
           This is the main Apache server configuration file.  It contains the configuration directives that give the server its instructions.
           
  ## [apache2.conf.sitesAvaiable](https://github.com/lunarobliq/LinuxConfigs/blob/master/apache2.conf.sitesAvaiable)
           This is the main Apache server configuration file in the sites available dir in web server folder.  It contains the configuration directives that give the server its instructions.
 
   ## [auto_dl](https://github.com/lunarobliq/LinuxConfigs/blob/master/auto_dl)
        This file is used by psad to elevate/decrease the danger levels of IP addresses (or networks in CIDR notation) so that psad does not have to apply the normal signature logic.  This is useful if certain IP addresses or networks are known trouble makers and should automatically be assigned higher danger levels than would normally be assigned.  Also, psad can be made to ignore certain IP addresses or networks if a danger level of "0" is specified.  Optionally, danger levels for IPs/networks can be influenced based on protocol (tcp, udp, icmp).
 
   ## [before.rules](https://github.com/lunarobliq/LinuxConfigs/blob/master/before.rules)
        UFW IPV4 before rules config file. These will be apploed before any UFW rules. This is not listen in output for FW rules.
        
   ## [before6.rules](https://github.com/lunarobliq/LinuxConfigs/blob/master/before6.rules)
        UFW IPV6 before rules config file. These will be apploed before any UFW rules. This is not listen in output for FW rules.
        
   ## [geoip.conf](https://github.com/lunarobliq/LinuxConfigs/blob/master/geoip.conf)
        Apache GEOIP webserver IP filtering mod config.     
        
# Legal Notice:

I am not a lawyer.
I dont recommend or condone using anything on here for any reason. The scipts here may work, but are just as likely have a chance to break the system they are run on. If you use them you do so at your own risk. I do/have NEVER authorized,condoned, or recommend the use of anything in any of my repos for any reason, even if previously stated. This is a collection of simple code I found useful with my own linux OS for educational purposes only. All credit goes to the authors whos full URL and/or github account and/or Repo is listed in the section above, please see their sites for more info or issue with their repo's. It should be noted that since these are all publically available. Do not use for evil, malicious purposes, or on machines you do not own.

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
