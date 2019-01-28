# telegraf

deploy telegraf overlay to specified hosts 

default behavior is to log to kafka, this can be changed in:
  
    vars/influxdb.yml
    
on a per customer basis, or

    roles/telegraf/defaults/main.yml
    
deploy via

     ./deploy telegraf ../confluent/hostsfile.none