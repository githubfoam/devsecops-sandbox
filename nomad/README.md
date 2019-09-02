# devsecops-sandbox

~~~
CI/CDelivery/CDeployment
~~~

| Function             | Software   |
| ---------------------| ----------:|
| Container platform   | Nomad      |
| Code registry        | Gitlab     |
| CI tools             | Jenkins    |
| Code Scanner         | Sonarqube  |
| Image registry       | Artifactoy |
| Helm repository      | Artifactoy |
| Bug tracking system  |            |
| Notification         | Slack      |


| Nomad Architecture   |            |
| ---------------------| ----------:|
| container platform   | Docker     |
|   cluster management | Nomad      |
|   monitoring |       |
|   scheduling         | Nomad      |
|   service discovery  | Consul     |
|   secret management  | Vault     |

| Static application security testing (SAST)                 | Tool       |
| ---------------------| ----------:|
| Code Scanner         | Sonarqube  |
| Static Analysiss       | Coverity  |

| Dynamic application security testing (DAST)
| ----------: |
| Burp Suite  |
| Zed Attack Proxy - OWASP ZAP  |
| Fiddler  |

| misc                |
| ---------------------|
| Software composition analysis (SCA)         |
| Interactive application security testing (IAST)         |  
| Runtime application self-protection (RASP)         |
