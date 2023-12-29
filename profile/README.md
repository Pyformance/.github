<a href="https://ssenerg.com">
    <div style="margin-bottom:1em;"> 
        <img style="margin-right:-.2em;" align="left" src="https://i.ibb.co/tDt3zh6/Pyformance-no-txt.png" title="SSENERG" width="100" height="100"/>
    </div>
    <div style="margin-bottom:-1.5em;">
        <h1 display="display:inline;">
            <font size="+4">PYFORMANCE</font>
        </h1>
    </div>
</a>

<div style="margin-left:5em;">
    <span style="vertical-align: middle;"><font size="+2">A platform for professional artist's live performance. Able to generate fully-arranged music in any genre with sound designing, mix, and master, also able to create visuals related to that music and performing stage lighting with human-like feeling and flow. Even using one laptop or a cluster containing multiple computational servers.</font></span>
</div>

---

# Platform Structure
### PYFORMANCE
```
├── Manager
│
├── Resources
│   ├── Kerberos 
│   ├── CertManager 
│   ├── NatsJetstream 
│   ├── ELK 
│   ├── LDAP 
│   ├── PostgresDB 
│   ├── Prometheus 
│   └── QuestDB 
│
└── PrivateEngines
    │
    ├── PYPLEX
    ├── PYVISUAL
    └── PYLIGHT
```
