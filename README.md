# zabbix-app-radius-service

Template app RADIUS service for ZABBIX
==============

This template uses the zabbix agent to monitoring RADIUS server.


Items
-----

  * RADIUS server listens auth port (1645)
  * RADIUS server listens acct port (1646)

Triggers
--------
  * auth port is listened.
  * acct port is listened.

Graphs
------

  * none

Installation
------------

1. Import **zbx_radius_app_templates.xml** file into Zabbix.
2. Associate **Template App RADIUS Service** template to the host.

### Requirements

This template was tested for Zabbix 2.2.0 and higher.

### Copyright

  Copyright (c) 2016 Igor Popov

License
-------
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

### Authors

  Igor Popov
  (ipopovi |at| gmail |dot| com)
