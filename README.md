# REMChain-Automated-Failover

#### These scripts will help block producers on REMChain perform a failovers, in the event they fail to produce blocks within a specified timeframe. The REMChain-Failover script should be activated on your backup server.

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
