# Active_MQ
Dockerfile password
echo "admin: ***, admin" >  /d01/activemq/conf/jetty-realm.properties - login pass ativMQ
echo "zabbix readonly" >  /d01/activemq/conf/jmx.access   login zabbix
echo "zabbix ***" >  /d01/activemq/conf/jmx.password   pass zabbix
docker-compose -up -d
