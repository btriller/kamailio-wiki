# Upgrade Kamailio from v5.6.x to v5.7.0 (devel)

The page contains the details about the changes that were made to old
components during the development of v5.7.0 compared with what existed
in v5.6.x. It does not include the brand new modules, focusing on how to
upgrade database and configuration file from v5.6.x to run with Kamailio
5.7.0.

## Previous Stable Release

If you look for the guidelines to upgrade to previous stable release,
see:

-   [Upgrade Kamailio v5.5.x to v5.6.0](/install/upgrade/5.5.x-to-5.6.0)

## Remarks

Following tokens are used to mark the changes:

-   INF - the change doesn't really have any direct impact - no action
    required in old config
-   CPM - the change was used with the new value via explicit parameter
    in default config file from old releases
-   RCM - the change is recommended to be done if you had an explicit
    different or lower value for this parameter in old config
-   UPG - the change has to be done, older config does not work any
    longer

## Modules

### Upgraded Modules

-   none

### Removed Modules

-   none

### Renamed Modules

-   none

## Internal Libraries

## Core

### Parameters

#### Dst Blocklist Parameters

All global parameters related to dst blocking are now using blocklist
instead of blacklist in the name, see:

-   <https://www.kamailio.org/wiki/cookbooks/devel/core#blocklist_parameters>

For example, **use_dst_blacklist** used in older versions has to be
replaced by **use_dst_blocklist**.

### Misc

## Database

### MySQL Database Structure

Run following SQL statements in MySQL client to upgrade database
structure from v5.6 to v5.7:

``` sql
...
```
