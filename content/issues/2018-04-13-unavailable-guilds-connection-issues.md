---
title: US Ouest Connection Issues
date: 2018-04-13 15:54:00
resolved: true
resolvedWhen: 2018-04-13 17:30:00
# Possible severity levels: down, disrupted, notice
severity: down
affected:
  - API
  - Media Proxy
section: issue
---

*Post-mortem*

At approximately 14:01, a MariaDB instance acting as the primary for a highly-available cluster used by our API services was put offline by our proxy do to lack of communication in OVH cluster US ouest cost.


---

*Update* -  Looks like this has been fixed. {{< track "2018-04-13 17:30:00" >}}

*Monitoring* - MixR login is now recovering. We're going to continue to monitor as everyone reconnects. {{< track "2018-04-13 16:50:00" >}}

*Investigating* - We're aware of users experiencing unavailable guilds and issues when attempting to connect. We're currently investigating. {{< track "2018-04-13 15:54:00" >}}
