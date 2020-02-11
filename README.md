# REMChain-Automated-Failover

#### These scripts will help a REMChain block producer perform a failover, in the event they fail to produce blocks within a specified timeframe. The Producer-Failover script should be activated on your primary server and the Backup-Failover on your secondary server.

***

### Setup Producer-Failover:

```
sudo wget https://github.com/remblock/REMChain-Automated-Failover/raw/master/producer-failover && sudo chmod u+x producer-failover && sudo ./producer-failover
```

***

### Edit Producer-Failover Config:

```
nano remblock/producer-failover/config
```

### Edit Producer-Failover (Enable/Disable):

```
nano /root/check-producer-failover
```

#### Edit file to "true" to enable and "false" to disable

***

### Setup Backup-Failover:

```
sudo wget https://github.com/remblock/REMChain-Automated-Failover/raw/master/backup-failover && sudo chmod u+x backup-failover && sudo ./backup-failover
```

***

### Edit Backup-Failover Config:

```
nano remblock/backup-failover/config
```

### Edit Backup-Failover (Enable/Disable):

```
nano /root/check-backup-failover
```

#### Edit file to "on" to enable and "off" to disable
