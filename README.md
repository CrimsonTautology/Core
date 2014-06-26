# Basic Donator Interface
[![Build Status](https://travis-ci.org/CrimsonTautology/sm_map_votes.png?branch=master)](https://travis-ci.org/CrimsonTautology/Core)

TODO: Describe Plugin

##Installation
If you want to use SQL here is some info to get you started:

SQL TABLE INFO:
```sql
CREATE TABLE IF NOT EXISTS `donators` (
    `steamid` varchar(64) default NULL,
    `tag` varchar(128) NOT NULL,
    `level` tinyint(1) NOT NULL default '1'
    )
```

MANUALLY ADDING DONATORS:
```sql
INSERT INTO `donators` ( `steamid` , `tag`, `level` ) VALUES ( 'STEAMID', 'THIS IS A TAG', 5 );
```

TODO - Adding donators via donators.txt
TODO - compiling


# Usage

* `sm_donators` - Display donator menu to donators


#Extending

