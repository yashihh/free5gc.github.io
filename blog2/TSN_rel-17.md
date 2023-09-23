# 標題還沒想好
>[!NOTE]
> Author: Ya-shih Tseng
> Date: 2023/9/27


Before you read the article, I suggest you to read  [Time-Sensitive Networking over 5G system - Introduction (Rel-16)](https://free5gc.org/blog/TSN/). 這篇文章會介紹TSN的enhencement in 3gpp release 17，我會先從5G新增的角色與其可應用的範圍，為符合更多應用而改變的架構，也新增了network function提供更多的服務。

## New roles of 5G in TSN
根據3GPP TS 23.501 Release 17，5G在TSN的角色不再只是Bridge的角色，它更上升到UDP/IP的應用，除了原本支援ethernet的Time aware clock，更新增了IEEE 1588 另外3種PTP instance types。

    Time Synchronization: describes how 5GS can operate as a PTP Relay (IEEE Std 802.1AS), as a Boundary Clock or as Transparent Clock (IEEE Std 1588) for PDU Session type Ethernet and IP.

> TS 23.501 clause 5.27

Let's briefly introduce three clocks.

### Boundary Clock

### End-to-End Transparent Clock

### Peer-to-Peer Transparent Clock

## New Network Function for TSN

PTP time synchronization is supported for the scenarios when Grand Master clock is behind the UE (uplink time sync, UE – UE time sync) and behind the network (down link time sync).

## 

## Conclusion
Release 17 expanded and improved the integration with IEEE TSN. This included enabling uplink synchronization through the 5G System (5GS), enhancing End-to-End Quality of Service (QoS) across multiple clock domains, and facilitating direct communication between User Equipment (UE) within the 5GS network.