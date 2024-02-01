# Older changes
## 2.0.2 (2023-09-08)
* (klein0r) Added option for disk information
* (klein0r) Check a type of disk wear out
* (klein0r) Catch exception when requesting disk information

## 2.0.1 (2023-09-07)
* (klein0r) Added node disks (heals, wearout)

## 2.0.0 (2023-09-07)

* (klein0r) Updated admin instance configuration
* (klein0r) Refactoring of adapter
* (klein0r) Allow dots in resource names

__Requires js-controller >= 3.3.22__
__Requires admin >= 6.0.0__

## 1.3.5 (2022-08-11)
* (foxriver76) fixed warning if `max_cpu` is not in response

## 1.3.4 (2021-05-07)
* (foxriver76) add dataSource and connectionType
* (foxriver76) add compact mode (closes #12, closes #49)

## 1.3.3 (2021-05-02)
* (foxriver76) we fixed some incorrect types

## 1.3.2 (2021-03-26)
* (foxriver76) status of vms is now a string instead of incorrectly a button

## 1.3.0 (2021-03-26)
* (foxriver76) Detect newly added VMs/storages/nodes during runtime and restart instance to initialize everything correctly
* (foxriver76) clean up deleted VM/storage/node objects
__Requires js-controller >= 2.2.8__

## 1.2.0 (2020-01-24)
* (foxriver76) Created info connection state + channel
* (foxriver76) status is a string and not a boolean, so set an obj type correctly
* (foxriver76) fix bug which resulted in not all nodes objects being created during a single execution of the adapter
* (foxriver76) password can now only be read by own instance if a controller version is new enough

__js-controller v2  or above required__
__node v10 or above required__

## 1.1.0 (10.08.2020)
* (Apollon77) Bug Update on features and stability and performance
* (ThetaGamma) Fix for failing Node shutdown/reboot commands

## 1.0.1 (05.03.2020)
* (MeisterTR) bump version to stable

## 0.5.2 (27.11.2019)
* (DutchmanNL) Fix issue with special character in password, now you can use $/&/* etc

## 0.5.1 (17.09.2019)
* (MeisterTR) add act. disk size form vm and lxc and disc size_level
* (MeisterTR) add start/stop and shutdown for vm an lxc (nodes must be testet my dev is on the node so i cant test stop node)

## 0.3.1 (03.10.2018)
* (MeisterTR) fixed mem_lev, error at install, catch error no node and vm

## 0.3.0 (28.09.2018)
* (MeisterTR) add storage
* (MeisterTR) add password encryption

## 0.2.0 (27.09.2018)
* (MeisterTR) add container

## 0.0.5 (25.09.2018)
* (MeisterTR) cleaning up

## 0.0.5 (02.05.2018)
* (MeisterTR) fixed wrong ram

## 0.0.5 (29.04.2018)
* (MeisterTR) Testing fixes, now ready for node4

## 0.0.3 (26.04.2018)
* (MeisterTR) first running version

## 0.0.2
* (MeisterTR) first running version

## 0.0.1
* (MeisterTR) initial release
