Notes
    Zabbix SQL login  mysql -u zabbix

    command: docker cp schema.sql zabbix-mysql:/schema.sql

    Login to Zabbix MySQL container > connect Zabbix DB > source schema.sql

    mysql -u zabbix -pzabbix_pass
    connect zabbix;
    source /schema.sql;
    