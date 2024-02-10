---
ns: NETWORK
aliases: ["0x60edd13eb3ac1ff3"]
---
## NETWORK_CHECK_ROS_LINK_WENTDOWN_NOT_NET

```c
// 0x60EDD13EB3AC1FF3
bool NETWORK_CHECK_ROS_LINK_WENTDOWN_NOT_NET();
```

PURPOSE Call to retrieve if in the last session the ROS connection (cloud) went down but not the platform network connection. When this is called it will clear any status so this must be called in the network game once only. During transition from SP to MP since I will adding some asserts and checks to make sure this is done in FREEMODE.

