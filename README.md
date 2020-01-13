# REMChain-AutoFailover

#### This script will help failover a block producer, if they fail to produce blocks by a certain number of minutes.

***

## Setup Auto-Producer-Failover:

```
sudo wget https://github.com/remblock/REMChain-AutoFailover/raw/master/autp-producer-failover && sudo chmod u+x autp-producer-failover && sudo ./autp-producer-failover
```

***

## Edit Producer Failover Config:

```
nano remblock/autp-producer-failover/config
```

***

## Setup Auto-Backup-Failover:

```
sudo wget https://github.com/remblock/REMChain-AutoFailover/raw/master/auto-backup-failover && sudo chmod u+x auto-backup-failover && sudo ./auto-backup-failover
```

***

## Edit Backup Failover Config:

```
nano remblock/auto-backup-failover/config
```
