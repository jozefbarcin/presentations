---

@snap[north span]
## Graylog Application 
@snapend

@snap[south span]
![](assets/img/graylog-logo-png-transparent-small.png)
@snapend

---

- **Graylog in general**:
  Log Management For All. Built to open standards, Graylog’s connectivity and interoperability seamlessly collects, enhances, stores, and analyzes log data.

- **Graylog for DTPN Security**:
  SIEM first at all, log management in advance   

Graylog is available (https://graylog.sec.in.pan-net.eu/)
---

## Used Integrations
- SLACK & email notifications
- LDAP authentication
- Thread inteligence plugin
- Aggretation plugin
- GEO plugin
- Log enrichment
- KAFKA plugin

![](assets/img/slack-small.png)
![](assets/img/kafka-small.png) 
![](assets/img/maxmind-small.png) 
![](assets/img/alienvault-small.png) 

---

## Onboarding:
- customer system shoud directly talk to kafka (rsyslog, filebeat, fluetd, fluentbit, winlogbeat)
- we will provide you KAFKA topic & KAFKA brokers

---
## What we are doing for customers
- make their logs available via Streams & Dashboards
- parse logs (create extracors on inputs)
- create base Alerts
- create notifications (email, slack)

---

## On demand:
- custom extended parsing
- custom Alerts
- custom SLACK & mail notifications
- transfer widgets from draft dashboard `999.Playground`

You can request for feratures in project [graylog-feature-dev](https://gitlab.tools.in.pan-net.eu/security/graylog-feature-dev/issues)

---

## What can do customers

- queries (Lucence syntax)
- quick values (stacked fields, statistics, geo mappping)
- widgets proposal in dashboard `999.Playground`
- export result

---

## NUMBERS: 
- we are receving log msgs from more than **800** sources
- we are processing abot **~150MIL**/day** log msgs = **100GB/day**
- retention 11 days atm
- SLA for all log producers about **10K msgs/s**

---

## What kind of logs you should send to us:
- we are interesting to have security related logs
- please don't send to us DEBUG logs
--- 
 
## Long tern Log managements
- DATALAKE for events (by Adrian Jackson)

