# PdM

[RPi] 
  - RASPBIAN JESSIE
  - Full desktop image based on Debian Jessie
  - Version:May 2016
  - Release date:2016-05-27
  - Kernel version:4.4

[Cassandra]

[InfluxDB]
  - wget https://dl.influxdata.com/influxdb/releases/influxdb_0.13.0_armhf.deb
  - sudo dpkg -i influxdb_0.13.0_armhf.deb
  - curl -sL https://repos.influxdata.com/influxdb.key | sudo apt-key add - source /etc/os-release
  - sudo apt-get update && sudo apt-get install influxdb
  - sudo service influxdb start

[MySQL]

[Nginx]

[uWSGI]

[Monit]

[Anaconda]

[Python]
  - python 2.7.9

