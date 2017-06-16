###Introduction to devops
* https://www.udacity.com/course/intro-to-devops--ud611
* https://github.com/udacity/devops-intro-project
![alt tag](https://user-images.githubusercontent.com/3624858/27232616-53b9badc-52d4-11e7-829c-6ca72048d795.png)
CAMS: The Devops Life Cycle.
C - Communication & collabration
A - Automation
M - Measurement and monitoring
S - Shared bringing all stackholder together.
Dev and Ops
- It works on my machine
Same environment for devlopment and productions.
Golden Image
Apps, libraries, OS wrap image, this image is used by dev and ops team.
Configuration management 
Install the base OS, install app and libraries using Configuration management tool

CI
Jenkins
Hosted CI Travis and CICircle
Integrating Chat bot slack and hip chat with jenkins, CI Travis and CircleCI

Mointoring
![alt tag](https://user-images.githubusercontent.com/3624858/27232590-39460b38-52d4-11e7-865b-a768ff492422.png)
- Service monitoring
- Business monitoring (how your service traffic is growing)
- Monitoring Avaliability and performance(hardware metrics disk usage, temp
erature, disk IO rate, 
Some popular monitoring tools include:

* Nagios and Zabbix - comprehensive solutions for monitoring large infrastructure, but maybe too big and complex for small projects.
* Graphite - Opensource database and a graphing solution for storing and displaying monitoring data.
* InfluxDB - an open-source distributed time series database for metrics, events, and analytics.
* StatsD - Simple daemon for easy stats aggregation, by Etsy. Read about the philosophy behind it in the article by it's creators - Measure Anything, Measure Everything
* Grafana - metrics dashboard and graph editor for Graphite and InfluxDB
* PagerDuty - incident resolution lifecycle management platform that integrates with over 100 other systems to streamline the process for large organisations.
* Logstash - log storage and search system, works well with - Kibana graphing and visualisation software.
