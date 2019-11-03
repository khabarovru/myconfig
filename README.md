# My Home Assistant configuration

Hardware: 

Server: Dual E5-2630l v2, 32gb ECC DDR3 RAM, 128Gb Boot SSD, 256Gb Raid1 NVME as Root drive, 256Gb NVME for DB, Oracle F20 card, 7ea WD RED 2Tb (NAS section), 1Tb WD Purple for cameras, 2ea WD Green as Torrent box
 
Network: Ubiquiti USG 3, Switch 24, Switch 8-60W, UAP-AC-AP-Lite (5ea)
  
Surveillance: Ubiquiti Video (running as service), Ubiquiti G3 Flex Cameras (4ea), Digma 100 (1ea) + Pinhole cam

  Smart Home: 
- Xiaomi Gateway (7ea)
- Yeelight 650
- Yeelight Pro 90W
- Yeelight Strip
- Philips Xiaomi E27 Bulb (2ea)
- Yeelight E27 Color Led Bulb v2 (2ea)
- Aqara Wall Socket (12ea)
- Aqara Wall Switch 2 Rockers (6ea)
- Aqara Wireless Switch 2 Rockers (6ea)
- Aqara Door Sensor (26ea)
- Aqara Water Leak Sensor (3ea)
- Aqara Vibration Sensor (3ea)
- Aqara\Xiaomi Motion Sensor (12ea)
- Aqara Wireless Switch (7ea)
- Aqara Temp\Himidity\Pressure sensor (3ea)
- Xiaomi Zigbee Plug (22ea)
- Xiaomi Temp\Humidity Sensor (8ea)
- Xiaomi Wireless switch (6ea)
- Xiaomi Smart WiFi Power Strip (1ea)
- Xiaomi Smartmi Humidifier 2
- Xiaomi Air Purifier 2s
- Xiaomi Wifi Plugs v2 (7ea) - used to restart Gateways remotely
- Xiaomi IR controller
- Xiaomi Smoke Detector (1ea)
- Xiaomi Natural Gas Detector (1ea)
- Google Home Mini (5ea)

Software: Ubuntu Server 18.04 LTS, Hass.Io in Docker

DB used: PostgreSQL 12 installed on host as well as InfluxDB 1.7.9

Add-On (all in Docker): AirCast, Configurator, Custom deps deployment, Dropbox Sync, ESPhome, Grafana, Hass.io Google Drive Backup, IDE, Log Viewer, Mosquitto BrockerPortainer, RPC shutdown

[psmqtt](https://github.com/eschava/psmqtt) used to publish host machine status.

Thanks to [Omh](https://github.com/omhy/ha), [OXOTH1K](https://github.com/OXOTH1K/homeassistant) and [AlexKvazis](https://github.com/kvazis/homeassistant) for cool stuff borrowed from their configs

Special thanks to [@Vasilchuk](https://github.com/Anonym-tsk), [@S_p_i_r_i_t_u_s], [@lapatoc](https://github.com/bastshoes) and all the rest! [You are all best of the best guys!]

# Main page
![Main Page](https://i.ibb.co/BTcVZtt/page1.jpg)
# Security page
![Security page](https://i.ibb.co/vxyRHD3/page2.jpg)
# Devices by room
![Devices by room](https://i.ibb.co/KV7CD01/page3.jpg)
# Sensors by room
![Sensors by room](https://i.ibb.co/vL2M1T1/page4.jpg)
# Utility counters
![Utility counters](https://i.ibb.co/mSYwCjt/page5.jpg)
# Power load
![Power loads](https://i.ibb.co/tsCh1sy/page6.jpg)
# Device trackers
![Device trackers](https://i.ibb.co/XWCCyRY/page7.jpg)
# CCTV
![CCTV](https://i.ibb.co/JnT0sFF/page8.jpg)
# Climate
![Climate](https://i.ibb.co/SvPRtrx/page9.jpg)
# System monitoring
![System monitoring](https://i.ibb.co/sy2KdM0/page10.jpg)
# Main Server Hardware Monitoring
![Main Server Health](https://i.ibb.co/V3rTvPy/page11.jpg)
# Radio
![Radio](https://i.ibb.co/wdNPVvz/page12.jpg)
# Home\Office PCs Telemetry
![Telemetry](https://i.ibb.co/DDnKYWf/page14.jpg)
# Cross Servers Utility Counters
![Utility Counters(cross servers)](https://i.ibb.co/Hx6vrTg/page15.jpg)