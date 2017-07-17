# Dead Hosts

[![license](https://img.shields.io/github/license/funilrys/dead-hosts.svg)](https://github.com/funilrys/dead-hosts/blob/master/LICENSE) [![Build Status](https://travis-ci.org/funilrys/dead-hosts.svg?branch=master)](https://travis-ci.org/funilrys/dead-hosts) [![GitHub tag](https://img.shields.io/github/tag/funilrys/dead-hosts.svg)](https://github.com/funilrys/dead-hosts/tags) [![GitHub release](https://img.shields.io/github/release/funilrys/dead-hosts.svg)](https://github.com/funilrys/dead-hosts/releases/latest)

> Let's test hosts file against [Funceble](https://github.com/funilrys/funceble) !

## Directory structure

```
.
└── Badd-Boyz-Hosts@mitchellkrogza ==> Github: https://github.com/mitchellkrogza/Badd-Boyz-Hosts
    ├── ACTIVE ==> Status
    │   ├── hosts ==> Result in hosts format
    │   └── list ==> Result in list format (only domains)
    ├── INACTIVE
    │   ├── hosts
    │   └── list
    ├── INVALID ==> Status
    ├── README.md
    ├── tested-list ==> Dir where list are saved
    │   └── badreferers.list
    └── tool ==> script used to update the dir & check lists
```
