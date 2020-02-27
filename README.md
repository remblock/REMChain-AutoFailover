# REMChain-Automated-Failover

#### These scripts will help a REMChain block producer perform a failover, in the event they fail to produce blocks within a specified timeframe. The Producer-Failover script should be activated on your primary server and the Backup-Failover on your secondary server.

***

### Setup REMChain-Failover:

```
sudo wget https://github.com/remblock/REMChain-Automated-Failover/raw/master/remchain-failover && sudo chmod u+x remchain-failover && sudo ./remchain-failover
```

***

### Edit REMChain-Failover Config:

```
nano remblock/remchain-failover/config
```

### Edit REMChain-Failover (Enable/Disable):

```
nano /root/check-failover
```

#### Edit file to "on" to enable and "off" to disable
