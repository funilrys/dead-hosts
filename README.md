# Dead Hosts
You're gonna find here the results of the lists tested with [Funceble](https://github.com/funilrys/funceble)

## Directory structure (exemple)
```
.
└── Badd-Boyz-Hosts@mitchellkrogza ==> Github: https://github.com/mitchellkrogza/Badd-Boyz-Hosts
    ├── ACTIVE ==> Status
    │   ├── hosts ==> Result in hosts format
    │   └── list ==> Result in list format (only domains)
    ├── INACTIVE
    │   ├── hosts
    │   └── list
    ├── INVALID ==> Status
    ├── README.md
    ├── tested-list ==> Dir where list are saved
    │   └── badreferers.list
    └── tool ==> script used to update the dir & check lists
```

___
## Status
* **ACTIVE**
    * Date of expiration accessible per WHOIS-Server (`whois` command)
    * `nslookup` don't return "**server can't find domain-name.me: NXDOMAIN**"
* **INACTIVE**
    * `whois` server don't return anything or date is unreadable
    * `nslookup` return "**server can't find domain-name.me: NXDOMAIN**"
* **INVALID**
    * Domain extension has an invalid format or is unregistered into **[IANA](https://www.iana.org/domains/root/db) Root Zone Database**.
