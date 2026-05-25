# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
netstat:
~~~
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:5141         TMP215-75-G2:52388     ESTABLISHED
  TCP    127.0.0.1:8000         TMP215-75-G2:59262     ESTABLISHED
  TCP    127.0.0.1:46935        TMP215-75-G2:64621     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:49684     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49675        TMP215-75-G2:49676     ESTABLISHED
  TCP    127.0.0.1:49676        TMP215-75-G2:49675     ESTABLISHED
  TCP    127.0.0.1:49677        TMP215-75-G2:49678     ESTABLISHED
  TCP    127.0.0.1:49678        TMP215-75-G2:49677     ESTABLISHED
  TCP    127.0.0.1:49679        TMP215-75-G2:49680     ESTABLISHED
  TCP    127.0.0.1:49680        TMP215-75-G2:49679     ESTABLISHED
  TCP    127.0.0.1:49681        TMP215-75-G2:49682     ESTABLISHED
  TCP    127.0.0.1:49682        TMP215-75-G2:49681     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49684        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:49685        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:49685     ESTABLISHED
  TCP    127.0.0.1:49700        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:52388        TMP215-75-G2:5141      ESTABLISHED
  TCP    127.0.0.1:52576        TMP215-75-G2:58448     ESTABLISHED
  TCP    127.0.0.1:55396        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:57970        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:58448        TMP215-75-G2:52576     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:49700     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:55396     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:57970     ESTABLISHED
  TCP    127.0.0.1:59262        TMP215-75-G2:8000      ESTABLISHED
  TCP    127.0.0.1:64615        TMP215-75-G2:64616     ESTABLISHED
  TCP    127.0.0.1:64616        TMP215-75-G2:64615     ESTABLISHED
  TCP    127.0.0.1:64617        TMP215-75-G2:64618     ESTABLISHED
  TCP    127.0.0.1:64618        TMP215-75-G2:64617     ESTABLISHED
  TCP    127.0.0.1:64619        TMP215-75-G2:64620     ESTABLISHED
  TCP    127.0.0.1:64620        TMP215-75-G2:64619     ESTABLISHED
  TCP    127.0.0.1:64621        TMP215-75-G2:46935     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:52391     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:54055     ESTABLISHED
  TCP    [::1]:15161            TMP215-75-G2:56209     TIME_WAIT
  TCP    [::1]:52391            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:54055            TMP215-75-G2:15161     ESTABLISHED
  TCP    [::1]:56208            TMP215-75-G2:15161     TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49671  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49672  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49713  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49774  lb-140-82-114-21-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49818  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:49970  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50269  [64:ff9b::34a8:75af]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50431  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50713  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50862  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50939  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:50970  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:51035  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:51384  [2a06:98c1:3107::6812:2715]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:51450  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:51479  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:51743  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52038  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52048  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52190  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52389  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52656  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:52967  [2603:1046:c06:c53::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54249  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54550  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54558  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54560  [64:ff9b::14be:918e]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54561  [64:ff9b::14be:918e]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54562  [64:ff9b::14be:918e]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54563  [64:ff9b::14be:918e]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54565  [2603:1046:2000:90::80]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:54566  [2603:1046:c06:c45::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55014  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55169  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55290  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55636  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55713  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:55979  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56245  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56292  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56293  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56459  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56509  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56541  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:56559  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57244  maa05s24-in-x03:https  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57388  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57550  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57631  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57653  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:57949  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58008  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58133  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58180  lb-140-82-114-25-iad:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58265  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58601  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58840  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:58961  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59321  [2606:50c0:8000::154]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59329  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59457  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59458  [64:ff9b::14bd:ad1b]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59485  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59498  lcmaaa-an-in-x0e:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59607  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59634  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59650  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:59760  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60056  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60080  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60401  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60689  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60758  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:60912  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:61354  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:61443  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:61780  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62063  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62177  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62382  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62464  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62465  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62509  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62541  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62589  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62705  [2603:1046:700:48::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:62968  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63131  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63231  whatsapp-cdn6-shv-03-maa3:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63582  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63722  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63845  si-in-f188:5228        ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:63940  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64258  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64310  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64416  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64500  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64570  sm-in-f188:5228        ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64585  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64680  [2603:1040:a06:6::2]:https  ESTABLISHED
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64823  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:64928  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:65053  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:65192  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:65376  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
  TCP    [2403:8600:c090:42:0:4ff:fffe:4e16]:65438  [2403:8600:c090:42:a000::200]:domain  TIME_WAIT
~~~
ipconfig:

<img width="845" height="652" alt="image" src="https://github.com/user-attachments/assets/ee107365-e39b-48f5-8433-4ec559b793d7" />

ping:

<img width="801" height="309" alt="image" src="https://github.com/user-attachments/assets/ea8331cb-4f81-4ec8-b68b-c3757ceb1ef5" />

tracert:

<img width="644" height="294" alt="image" src="https://github.com/user-attachments/assets/e5f0d118-6a17-4804-99f1-9670435085ae" />

nslookup:

<img width="571" height="511" alt="image" src="https://github.com/user-attachments/assets/a6dd1803-6a10-4758-8fb1-4d715ee96027" />

getmac:

<img width="896" height="172" alt="image" src="https://github.com/user-attachments/assets/edc51d9c-f39e-405e-89e9-6b61545bc8f5" />

hostname:

<img width="317" height="115" alt="image" src="https://github.com/user-attachments/assets/d7948988-cc64-46d3-9fe5-c1bbcd3de3a3" />

nbtstat:

<img width="1023" height="606" alt="image" src="https://github.com/user-attachments/assets/3dea62e6-bf11-4edf-8d52-a09ac224678e" />

arp:

<img width="911" height="751" alt="image" src="https://github.com/user-attachments/assets/4c263489-d8a4-486f-ac36-23886b1dcad9" />

systeminfo:
~~~
C:\Users\acer>systeminfo

Host Name:                     TMP215-75-G2
OS Name:                       Microsoft Windows 11 Home Single Language
OS Version:                    10.0.26200 N/A Build 26200
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Standalone Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              acer
Registered Organization:       N/A
Product ID:                    00342-42784-66213-AAOEM
Original Install Date:         01-09-2025, 15:21:05
System Boot Time:              12-05-2026, 15:59:01
System Manufacturer:           Acer
System Model:                  TravelMate P215-75-G2-TCO
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 170 Stepping 4 GenuineIntel ~1200 Mhz
BIOS Version:                  INSYDE Corp. V1.05tt01a, 01-09-2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  00004009
Time Zone:                     (UTC+05:30) Chennai, Kolkata, Mumbai, New Delhi
Total Physical Memory:         15,869 MB
Available Physical Memory:     5,232 MB
Virtual Memory: Max Size:      18,301 MB
Virtual Memory: Available:     3,017 MB
Virtual Memory: In Use:        15,284 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        WORKGROUP
Logon Server:                  \\TMP215-75-G2
Hotfix(s):                     6 Hotfix(s) Installed.
                               [01]: KB5082417
                               [02]: KB5087051
                               [03]: KB5054156
                               [04]: KB5089549
                               [05]: KB5088467
                               [06]: KB5092762
Network Card(s):               2 NIC(s) Installed.
                               [01]: Intel(R) Wi-Fi 6E AX211 160MHz
                                     Connection Name: Wi-Fi
                                     DHCP Enabled:    Yes
                                     DHCP Server:     255.255.255.255
                                     IP address(es)
                                     [01]: 169.254.90.255
                                     [02]: fe80::30b2:1dc4:ad7e:645b
                                     [03]: 2403:8600:c090:42:0:4ff:fffe:4e16
                               [02]: Realtek PCIe GbE Family Controller
                                     Connection Name: Ethernet
                                     Status:          Media disconnected
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Users\acer>
~~~

## Result
Thus Execution of Network commands Performed 
