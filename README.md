# mysql_follow_master_setup
This is the setup used for mariadb replication using fesh DB (IDEAL Scenario: no pre-exisiting DBS).. 
The master is setup.. The production follow is initiated by apporbit platform. 
When the follow container is running nd replication is working fine:
-Take snapshot of follow
-Promote it to data template
-launch new master using yaml via apporbit platform and import values from data template
