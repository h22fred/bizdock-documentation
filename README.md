# BizDock OpenSource Home
Welcome on the GitHub home of the BizDock OpenSource PPM software.

Find <a href="https://help.bizdock.io/doku.php">here</a> the full description of the BizDock software and much more in the OpenSource section.

## GitHub repositories

On GitHub BizDock source code actually consists in several repositories:
* https://github.com/theAgileFactory/app-framework : a repository which contains the technical foundation of BizDock (a set of services which could possibly be reused with other software based on the play framework)
* https://github.com/theAgileFactory/maf-desktop-datamodel : the business datamodel of BizDock (based on Ebean http://ebean-orm.github.io/ objects)
* https://github.com/theAgileFactory/maf-desktop-app : the core features of BizDock.
**This repo also contains the BizDock development environment for those who wants to contribute to the project**
* https://github.com/theAgileFactory/dbmdl-framework : the component which manages (using the http://www.mybatis.org/migrations/ library) the database evolutions of BizDock (in relation with the app-framework component)
* https://github.com/theAgileFactory/maf-dbmdl : the component which manages (also using the http://www.mybatis.org/migrations/ library) the database evolutions for BizDock itself (in relation with the maf-desktop-datamodel component)
* https://github.com/theAgileFactory/bizdock-installation : a project which contains the code to create the BizDock installer (based on Docker)

Please refer to our wiki https://help.bizdock.io/doku.php for more details about the feature scope of BizDock as well as how to build, install and customize it.
