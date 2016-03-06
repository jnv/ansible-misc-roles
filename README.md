# Hic sunt leones
## Miscellaneous Unsupported Roles for Ansible

[![Project Status: Abandoned - Initial development has started, but there has not yet been a stable, usable release; the project has been abandoned and the author(s) do not intend on continuing development.](http://www.repostatus.org/badges/latest/abandoned.svg)](http://www.repostatus.org/#abandoned)

I never got around to properly polish and document these roles and I don't use most of them anymore. But they might be useful to someone, so feel free to study them, modify them and perhaps even use them.

All roles were created and tested on Ubuntu 14.04 64bit. Currently these roles are included:

* **jenkins** – Derived from [geerlingguy.jenkins](https://github.com/geerlingguy/ansible-role-jenkins)
* **nodejs** – Install Node.js from Nodesource. Deprecated in favour of [the official role](https://github.com/nodesource/ansible-nodejs-role/)
* **openjdk** – Just install OpenJDK package.
* **redash** – Setup [re:dash](https://github.com/getredash/redash) using official tarball. Requires PostgreSQL.
* **reportserver** – Setup [Reportserver](https://reportserver.net/) under Tomcat with PostgreSQL persistence. Documentation for this product sucks, so I quickly went to something else.
* **tomcat** – Setup Tomcat server.
* **tomcat-dashbuilder** – Setup [Dashbuilder](http://www.dashbuilder.org/) under Tomcat. This product processes all data in-memory so it didn't fit our usecase. Also, the UI is terrible.
* **tomcat-jenkins** – Setup Jenkins as Tomcat application. Derived from the jenkins role.

## License

Unless otherwise noted, the roles are licensed under [Creative Commons Zero 1.0](https://creativecommons.org/publicdomain/zero/1.0/). No rights reserved.

**jenkins** and **tomcat-jenkins** are © 2014 Jeff Geerling, licensed under MIT (Expat) / BSD.
