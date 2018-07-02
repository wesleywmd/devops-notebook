### Find Elastic Search sevice name and whether its installed

    sudo su root;
    systemctl list-unit-files | grep elastic;
    
### Get Elastic Search service status

    sudo su root;
    service elasticsearch status
    
### Get Elastic Search status

    sudo su webuser;
    curl -XGET 'localhost:9200'
