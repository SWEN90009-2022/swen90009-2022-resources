# Telstra - Security Data Normalization

**Project overview and background**

In Telstra, large and varied data sets are used to detect security threats and anomalies. The data, generated from multiple technologies and vendors, come in different shape and form, as the result of different naming conventions, configurations, logging standards or simply using different file format.  For example, with NGFW (next generation firewall data) we have a number of vendors in this space (e.g. Palo Alto, Cisco, Fortinet, ...) and each one of them have different log formats with similar data. Hence before the data can be used for analysis, a normalization process must happen first, to extract common fields and convert data into standard format. This process requires human effort to understand the logs and map to common schema manually, which is not only time consuming but also could prompt to human errors. A scientific and consistent approach to the problem is needed.

In this project, students will be researching, experimenting, designing and assessing different data normalization approaches that are used in the industry & research, subsequently implementing a smart tool that automate or semi-automate the data extraction and normalization process.

**Project desired outcomes**

Data normalisation approaches recommendations or tool

**References**

· Elastic ECS ([https://www.elastic.co/guide/en/ecs/current/ecs-field-reference.html](https://protect-au.mimecast.com/s/frT6CJypvAfq46358cV7hb6?domain=elastic.co))

· Splunk CIM ([https://docs.splunk.com/Documentation/CIM/4.18.0/User/Overview](https://protect-au.mimecast.com/s/LzRtCK1qwBS2AXzmqSv2Xe4?domain=docs.splunk.com))

· Palo Alto most recent format is defined [https://docs.paloaltonetworks.com/pan-os/10-0/pan-os-admin/monitoring/use-syslog-for-monitoring/syslog-field-descriptions.html](https://protect-au.mimecast.com/s/cF-tCL7rxDsRoGy4PcPDh_Y?domain=docs.paloaltonetworks.com)

· Fortinet: [https://docs.fortinet.com/document/fortigate/6.4.5/fortios-log-message-reference/524940/introduction](https://protect-au.mimecast.com/s/NzqsCMwvygsqowMW5cWtuG1?domain=docs.fortinet.com)

· Cisco Firepower: [https://www.cisco.com/c/en/us/td/docs/security/firepower/Syslogs/b_fptd_syslog_guide/security-event-syslog-messages.html](https://protect-au.mimecast.com/s/Ok2lCNLwzjF0nODXNcrzeeh?domain=cisco.com)