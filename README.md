# devsecops-sandbox
CI/CDelivery/CDeployment  
platform-independent

| Function             | Software   |
| ---------------------| ----------:|
| Container platform   | Kubernetes      |
| deploying VM platform  | Vagrant      |
| Code registry        | Gitlab     |
| CI tools             | Jenkins    |
| Image registry       | Artifactory |
| Helm repository      | Artifactory |
|    Deployment   | Helm/Tiller   |
| Bug tracking system  |       JIRA     |
| Notification         | Slack      |


| Platform Architecture   |    |
| ---------------------| ----------:|
| Infrastructure Services   | Vagrant      |
| Container Host | Ubuntu       |
| Container Cluster Manager | Kubernetes    |
| Container Networking | Flannel |
| Container Engine  | Docker Engine     |
| Container Registry  | Artifactory |
| Service Registry  | etcd |
| Source Code Management  | Gitlab |
| Code Review  | Gerrit |
| CI tools             | Jenkins    |
| Infrastructure Provisioning | Terraform    |
| Logging | Elasticsearch, Kibana    |
| Metrics | Heapster    |
| Service Monitoring | Prometheus    |

| Kubernetes Architecture   |    |
| ---------------------| ----------:|
| kube-apiserver | Configure and validate objects through REST API |
|  kube-scheduler |  Allocate Pods to each node     |
|   kube-controller-manager |  manage replication controller     |
|   kubelet        | Run on each node as agent and manage Pod      |
| kube-proxy  | Configure iptable NAT tables to configure IP and load balance (ClusterIP)    |
|   etcd  |      |

| Static application security testing (SAST)                 | Tool       |
| ---------------------| ----------:|
| Code Scanner         | Sonarqube  |
| Static Analysis      | Coverity  |
| Appium | Mobile, Hybrid     |


| Dynamic application security testing (DAST)   |            |
| ---------------------| ----------:|
| Burp Suite  |  |
|   Zed Attack Proxy - OWASP ZAP |       |
|   Fiddler |       |
|   JMeter |  Load     |
|   Selenium | Headless      |
| SOAP UI | Functional     |
| LISA | Service Virtualization  |


| misc.   |            |
| ---------------------| ----------:|
| Software composition analysis (SCA)  |  |
| Interactive application security testing (IAST) |       |
| Runtime application self-protection (RASP) |       |

| E2E test framework   |            |
| ---------------------| ----------:|
| CodeceptJS  |  |
| Protractor |       |
| Cypress |       |
