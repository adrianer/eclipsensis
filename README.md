# EclipseNSIS

_"EclipseNSIS is a plugin for the Eclipse platform which enables editing, compiling and testing Nullsoft Installer (NSIS) scripts. The EclipseNSIS InstallOptions Editor plugin is an add-on to EclipseNSIS which enables editing of InstallOptions scripts."_ -- http://eclipsensis.sourceforge.net/index.shtml

**InstallOptions needs GEF (MVC) plugin.**

This project is a fork of a fork of a fork of a fork of the original EclipseNSIS at http://eclipsensis.sf.net. 

# Changelog and Download

## Forked and Fixed (0.9.16)

This project is a fork of [spt-oss/eclipsensis](https://github.com/spt-oss/eclipsensis) and fixed for:

* Java supported up to 26 (though tested only with 21)
* Tested with Eclipse 2025-12 and Eclipse Adoptium 21
* This will most likely *not* work with Eclipse versions older than 2025-12. If it does not work, upgrade to 2025-12.

Download: [0.9.16](https://github.com/adrianer/eclipsensis/raw/master/dist/eclipsensis-0.9.16.zip)

## Forked and Fixed (0.9.15)

This project is a fork of [spt-oss/eclipsensis](https://github.com/spt-oss/eclipsensis) and fixed for:

* Java supported up to 22 (though tested only with 21)
* Minimum supported NSIS version set to 3.0
* Minimum supported Windows version set to 7
* Tested with Eclipse 2024-06 and Eclipse Adoptium 21

Download: [0.9.15](https://github.com/adrianer/eclipsensis/raw/master/dist/eclipsensis-0.9.15.zip)

## Forked and Fixed (0.9.14)

This project is a fork of [spt-oss/eclipsensis](https://github.com/spt-oss/eclipsensis) and fixed for:

* Merged fixes from [hevmaad/eclipsensis](https://github.com/hevmaad/eclipsensis)
 (e.g. Java 15 and NSIS 3.04 support)
* Added Eclipse Adoptium (Temurin) support
* Windows 11
* Set Java 17 as supported (not tested, though) 
* Tested with Eclipse 2023-03 and Eclipse Adoptium 11

Download: [0.9.14](https://github.com/adrianer/eclipsensis/raw/master/dist/eclipsensis-0.9.14.zip)

## Forked and Fixed (0.9.13)

This project is a fork of [adrianer/eclipsensis](https://github.com/adrianer/eclipsensis) and fixed for:

* Support up to Java 15
* Windows Server 2012 R2, Server 2016, Server 2019
* NSIS 2.xx and 3.xx (>= 3.04)
* Tested with Eclipse Neon 3 and 2020-12

InstallOptions needs GEF (MVC) plugin.
Download: [0.9.13](https://github.com/hevmaad/eclipsensis/raw/master/dist/eclipsensis-0.9.13.zip)

## Forked and Fixed (0.9.12)

This project is a fork of [spt-oss/eclipsensis](https://github.com/spt-oss/eclipsensis) and fixed for:

* AdoptOpenJDK branded Java 8-11 support
* Oracle branded Java 8-11 support
* Tested with Eclipse 2020-12

Download: [0.9.12](https://github.com/adrianer/eclipsensis/raw/master/dist/eclipsensis-0.9.12.zip)

## Forked and Fixed (0.9.11)

This project is a fork of [henrikor2/eclipsensis](https://github.com/henrikor2/eclipsensis) and fixed for:

* Windows 10
* Oracle branded Java 8
* Eclipse Oxygen 4.7.2

Download: [0.9.11](https://github.com/spt-oss/eclipsensis/raw/master/dist/eclipsensis-0.9.11.zip)

## Forked and Fixed (0.9.10)

This project is a fork of [henrikor2/eclipsensis](https://github.com/henrikor2/eclipsensis) and fixed for:

* Windows 10
* Oracle branded Java 8
* Eclipse Neon 4.6

Download: [0.9.10](https://github.com/spt-oss/eclipsensis/raw/master/dist/eclipsensis-0.9.10.zip)

## Forked and Fixed (0.9.9)

This project is a of the original EclipseNSIS at http://eclipsensis.sf.net. 

The repository root is a selective snapshot of the original EclipseNSIS CVS modules HEAD (eclipsensis.cvs.sourceforge.net:/cvsroot/eclipsensis) as of 2014-08-13 including only the necessary source files to build the project.

The purpose of this project was to make EclipseNSIS plugin compatible with my own development tool chain including the latest Windows, Java and Eclipse versions at the time. The code is not systematically tested and changes may have introduced new bugs and removed existing functionality.

Compared to the official EclipseNSIS release 0.9.8.1 this project adds support for:

*   Windows 8 and 8.1;
*   Oracle branded Java8; and
*   Eclipse Kepler 4.3 and Luna 4.4.

Some users have found that this version doesn't work with older Eclipse versions, at least with Indigo 3.7 and Galileo 3.5.

Download: [0.9.9](https://github.com/henrikor2/eclipsensis/raw/master/dist/eclipsensis-0.9.9.zip)
