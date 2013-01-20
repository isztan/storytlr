#Storytlr

Storytlr is an open source lifestreaming and micro blogging platform. You can use it for a single user or it can act as a host for many people all from the same installation.

[http://storytlr.org](http://storytlr.org)

## Install

Two install options are available:

* [Download the latest release](https://github.com/storytlr/storytlr/tarball/master).
* Clone the repo: `git clone git://gtihub.com/storytlr/storytlr.git`

You can then follow the following [install instructions](https://github.com/storytlr/storytlr/wiki/Install).

## Requirements

Storytlr requires a standard LAMP stack (Linux, Apache, Mysql, Php) which can be found on most shared hosting providers. A few additional modules are required to enable all features.

- MySQL server
- Apache Web Server
- Php with the following modules: mcrypt, mbstring, gd, pdo-mysql
- [ZendFramework](http://framework.zend.com/)

On a CentOS/RedHat distribution, the following command will install all required packages:
```
yum install httpd mysql-server php php-mcrypt php-mbstring php-gd php-mysql php-ZendFramework \n
php-ZendFramework-Db-Adapter-Pdo-Mysql php-ZendFramework-Feed php-ZendFramework-Service
```

## Community

Below is a list of the various places where you could interact some members of the storytlr community:

* [Mailing list](http://groups.google.com/group/storytlr-discuss)
* [Issue tracker](:http://github.com/storytlr/storytlr/issues)
* #storytlr tag on twitter & status.net
* irc: #storytlr on chat.freenode.net for real time discussion

## Authors

- [Laurent Eschenauer](https://github.com/eschnou)
- [Alard Weisscher](https://github.com/alardw)

With additional contributions by:

- [John Hobbs](https://github.com/jmhobbs)

## License

Copyright 2008-2013 by authors in AUTHORS file attached.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
