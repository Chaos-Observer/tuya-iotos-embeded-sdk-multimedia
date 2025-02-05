English | [简体中文](./release_note_zh-CN.md)
## release note for 4.9.14 20220125
### [optimization version]
- Change default IP of CN IOT DNS
- Support regist cb to get ip 
- fix bug of playback, can't get next file when cur file read fail
- Change default log level to NOTICE, and delete the print of key

## release note for 4.9.10 20211207
### [optimization version]
- Support new default Tuya Cloud region: West-Europe
- Fix bug, webrtc get stream fail after several request

## release note for 4.9.8 20210911
### [new feature&optimization version]
- Support H265+ intelligent encoding
- Add new API for low power of TCP mode
- Add customized audio play
- Add cancel and stop api of doorbell
- Support playback in web
- Support mute silent video in local storage and cloud storage
- Modify max bitrate to 5000kbps
- Fix Bug: possibly get wrong UTC time

## release note for 4.8.10 20210911
### [optimization version]
- Fix bug of offline or crash cause of remote linkage(SAAS)
- Support cancel of doorbell by device
- Support append media data with time

## release note for 4.8.8 20210109
### [optimization version]
- Optimize the logic of minimal interval of motion detection notification(60 sec)
- Support termination of 3rd streaming when set to secret mode
- Fix bug: the crash of streamer module because of unalign 

## release note for 4.8.6 20201118
### [new feature&optimization version]
- Minimal interval of motion detection notification changes to 60sec
- Use hmac to check OTA file for higher security
- Support new default Tuya Cloud region: East-USA
- Support new notification type, check enum NOTIFICATION_NAME_E in tuya_ipc_api.h
- Support configurable cloud storage slice duration
- Support receiving raw type DP
- Support HD/SD switch and two-way talk on/off via web
- Support callback to tell if preivewing via P2P/WebRTC
- Support use customized DNS-resolve function
- Add new API tuya_ipc_get_client_online_num to get current total preivew user number
- Add new API for privacy mode: pause/resume all streaming and storage
- Optimize audio&video synchronization for cloud storage and local storage
- Fix bug: progress bar of cloud storage not is correct by chance in weak network
- Fix bug: MQTT service may fail in certain weak network
- Fix bug: two devices may appear when pairing in auto find mode for wired camera

## release note for 4.8.4 20200722
### [new feature version]
- Support preview on AP mode(LAN only)
- Support new pairing method: scan QR on device with network
- Support video message
- Support WiFi migration

## release note for 4.7.14 20200720
### [optimization version]
- fix bug: mosaic appears when multi-channel preivew via webrtc
- fix bug: pre-record fail when no SD cards inserted
- optimization: online-offline optimized in weak network
- optimization: two-talk quality improved with Echo Alexa 
- fix bug: uprade from lower version to 4.7.x needs reset on some platform
- fix bug: motion detection fails on Y-direction
