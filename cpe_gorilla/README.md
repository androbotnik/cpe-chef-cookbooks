cpe_gorilla Cookbook
============================
Configures and installs gorilla

Requirements
------------
* Windows

Attributes
----------
* node['cpe_gorilla']
* node['cpe_gorilla']['dir']
* node['cpe_gorilla']['exe']
* node['cpe_gorilla']['install']
* node['cpe_gorilla']['preferences']
* node['cpe_gorilla']['task']
* node['cpe_gorilla']['uninstall']

For an authoritative list of preferences, please see [Gorilla's Client Configuration](https://github.com/1dustindavis/gorilla/wiki/Client-Configuration)

This cookbook assumes you are using the executable version of Gorilla and not the MSI provided with v1.0.0 beta1 and higher. An example of this format can be found [here](https://github.com/1dustindavis/gorilla/releases/download/v1.0.0-beta.2/gorilla.exe)