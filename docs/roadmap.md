# Roadmap


- [x] AD-labb: DC01 (Windows Server 2022) och CLIENT01 (Windows 11) i domänen `lab.local`
- [x] Sysmon med SwiftOnSecuritys konfiguration på båda maskinerna
- [x] Wazuh-agenter på DC01 och CLIENT01 (Security- och Sysmon-logg)
- [x] Wazuh-detektering: egna regler 100001 (brute force) och 100002 (loggrensning), testade och dokumenterade, se [wazuh.md](wazuh.md)
- [x] Discord-notiser för larm på level 12 eller högre
- [ ] PKI-lab: certifikatutfärdare och smartkortsinloggning
- [ ] Active Response: lås konto efter brute force-larm
