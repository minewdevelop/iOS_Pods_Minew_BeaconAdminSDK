### [Documentation](https://docs.beaconyun.com/zh-CN/iOS/iOS_BeaconAdmin_Software_Development_Kit_Guide.html)
---

# Change Log


## [1.0.0](https://github.com/minewdevelop/iOS_Pods_Minew_BeaconAdminSDK/releases/tag/1.0.0)(12/4/2020)

Released on Monday, December 23, 2020. 

#### Added

- MinewBeaconManager
  - Core
    - Start scan
    - Stop scan
  - Delegate
    - minewBeaconManager: didUpdateState:
    - minewBeaconManager: appearBeacons:
    - minewBeaconManager: disappearBeacons:
    - minewBeaconManager: didRangeBeacons:
- MinewBeaconConnection
  - Core
    - connect
    - disconnect
    - writeSetting:
  - Delegate
    - beaconConnection: didChangeState:
    - beaconConnection: didWriteSetting:
- MinewBeacon
  - uuid
  - major
  - minor
  - name
  - deviceId
  - mac
  - txPower
  - rssi
  - battery
  - inRange
  - connectable
- MinewBeaconSetting
  - write
    - uuid
    - major
    - minor
    - name
    - mode
    - broadcastInterval
    - deviceId
    - password
    - calibratedTxPower
    - txPower
    - mac
    - battery
    - connected
  - read
    - manufacture
    - SN
    - model
    - hardware
    - software
    - firmware
    - systemId
    - certData

