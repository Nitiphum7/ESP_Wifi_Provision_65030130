I (31) boot: ESP-IDF v5.2.2 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 14:26:55
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2a02ch (172076) map
I (163) esp_image: segment 1: paddr=0003a054 vaddr=3ffbdb60 size=05404h ( 21508) load
I (171) esp_image: segment 2: paddr=0003f460 vaddr=40080000 size=00bb8h (  3000) load
I (173) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=a15a0h (660896) map
I (404) esp_image: segment 4: paddr=000e15c8 vaddr=40080bb8 size=14850h ( 84048) load
I (448) boot: Loaded app from partition at offset 0x10000
I (448) boot: Disabling RNG early entropy source...
I (460) cpu_start: Multicore app
I (468) cpu_start: Pro cpu start user code
I (468) cpu_start: cpu freq: 160000000 Hz
I (469) cpu_start: Application information:
I (472) cpu_start: Project name:     wifi_prov_mgr
I (477) cpu_start: App version:      1
I (481) cpu_start: Compile time:     Sep 26 2024 14:54:06
I (488) cpu_start: ELF file SHA256:  29e067575...
I (493) cpu_start: ESP-IDF:          v5.2.2
I (498) cpu_start: Min chip rev:     v0.0
I (502) cpu_start: Max chip rev:     v3.99
I (507) cpu_start: Chip rev:         v3.0
I (512) heap_init: Initializing. RAM available for dynamic allocation:
I (519) heap_init: At 3FFAE6E0 len 0000F480 (61 KiB): DRAM
I (525) heap_init: At 3FFC7098 len 00018F68 (99 KiB): DRAM
I (532) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (538) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (544) heap_init: At 40095408 len 0000ABF8 (42 KiB): IRAM
I (552) spi_flash: detected chip: generic
I (555) spi_flash: flash io: dio
W (559) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (573) coexist: coex firmware version: d96c1e51f
I (579) main_task: Started on CPU0
I (589) main_task: Calling app_main()
I (639) wifi:wifi driver task: 3ffb80e0, prio:23, stack:6656, core=0
I (659) wifi:wifi firmware version: 3e0076f
I (659) wifi:wifi certification version: v7.0
I (659) wifi:config NVS flash: enabled
I (659) wifi:config nano formating: disabled
I (659) wifi:Init data frame dynamic rx buffer num: 32
I (669) wifi:Init static rx mgmt buffer num: 5
I (669) wifi:Init management short buffer num: 32
I (669) wifi:Init dynamic tx buffer num: 32
I (679) wifi:Init static rx buffer size: 1600
I (679) wifi:Init static rx buffer num: 10
I (689) wifi:Init dynamic rx buffer num: 32
I (689) wifi_init: rx ba win: 6
I (689) wifi_init: tcpip mbox: 32
I (699) wifi_init: udp mbox: 6
I (699) wifi_init: tcp mbox: 6
I (699) wifi_init: tcp tx win: 5760
I (709) wifi_init: tcp rx win: 5760
I (709) wifi_init: tcp mss: 1440
I (719) wifi_init: WiFi IRAM OP enabled
I (719) wifi_init: WiFi RX IRAM OP enabled
I (729) app: Already provisioned, starting Wi-Fi STA
I (729) phy_init: phy_version 4791,2c4672b,Dec 20 2023,16:06:06
I (819) wifi:mode : sta (94:b5:55:f8:5d:50)
I (819) wifi:enable tsf
I (3239) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1
I (3239) wifi:state: init -> auth (b0)
I (3249) wifi:state: auth -> assoc (0)
I (3249) wifi:state: assoc -> run (10)
I (3269) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 15, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (3269) wifi:security: WPA2-PSK, phy: bgn, rssi: -52
I (3279) wifi:pm start, type: 1

I (3279) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (3309) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (4289) app: Connected with IP Address:192.168.1.147
I (4289) esp_netif_handlers: sta ip: 192.168.1.147, mask: 255.255.255.0, gw: 192.168.1.1
I (4289) app: Hello World!
I (5289) app: Hello World!
I (6289) app: Hello World!
I (7289) app: Hello World!
I (8289) app: Hello World!
I (9289) app: Hello World!
I (10289) app: Hello World!
I (11289) app: Hello World!
I (12129) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (12289) app: Hello World!
I (13289) app: Hello World!
I (14289) app: Hello World!
I (15289) app: Hello World!
I (16289) app: Hello World!
I (17289) app: Hello World!
I (18289) app: Hello World!
I (19289) app: Hello World!
I (20289) app: Hello World!
I (21289) app: Hello World!
I (22289) app: Hello World!
I (23289) app: Hello World!
I (24289) app: Hello World!
I (25289) app: Hello World!
I (26289) app: Hello World!
I (27289) app: Hello World!
I (28289) app: Hello World!
I (29289) app: Hello World!
I (30289) app: Hello World!
I (31289) app: Hello World!
I (32289) app: Hello World!
I (33289) app: Hello World!
I (34289) app: Hello World!
I (35289) app: Hello World!
I (36289) app: Hello World!
I (37289) app: Hello World!
I (38289) app: Hello World!
I (39289) app: Hello World!
I (40289) app: Hello World!
I (41289) app: Hello World!
I (42289) app: Hello World!
I (43289) app: Hello World!
I (44289) app: Hello World!
I (45289) app: Hello World!
I (46289) app: Hello World!
I (47289) app: Hello World!
I (48289) app: Hello World!
I (49289) app: Hello World!
I (50289) app: Hello World!
I (51289) app: Hello World!
I (52289) app: Hello World!
I (53289) app: Hello World!
I (54289) app: Hello World!
I (55289) app: Hello World!
I (56289) app: Hello World!
I (57289) app: Hello World!
I (58289) app: Hello World!
I (59289) app: Hello World!
I (60289) app: Hello World!
I (61289) app: Hello World!
I (62289) app: Hello World!
I (63289) app: Hello World!
I (64289) app: Hello World!
I (65289) app: Hello World!
I (65479) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
I (66289) app: Hello World!
I (67289) app: Hello World!
I (68289) app: Hello World!
I (69289) app: Hello World!
I (70289) app: Hello World!
I (71289) app: Hello World!
I (72289) app: Hello World!
I (73289) app: Hello World!
I (74289) app: Hello World!
I (75289) app: Hello World!
I (76289) app: Hello World!
I (77289) app: Hello World!
I (78289) app: Hello World!
I (79289) app: Hello World!
I (80289) app: Hello World!
I (81289) app: Hello World!
I (82289) app: Hello World!
I (83289) app: Hello World!
I (84289) app: Hello World!
I (85289) app: Hello World!
I (86289) app: Hello World!
I (87289) app: Hello World!
I (88289) app: Hello World!
I (89289) app: Hello World!
I (90289) app: Hello World!
I (91289) app: Hello World!
I (92289) app: Hello World!
I (93289) app: Hello World!
I (94289) app: Hello World!
I (95289) app: Hello World!
I (96289) app: Hello World!
I (97289) app: Hello World!
I (98289) app: Hello World!
I (99289) app: Hello World!
I (100289) app: Hello World!
I (101289) app: Hello World!
I (102289) app: Hello World!
I (103289) app: Hello World!
I (104289) app: Hello World!
I (105289) app: Hello World!
I (106289) app: Hello World!
I (107289) app: Hello World!
I (108289) app: Hello World!
I (109289) app: Hello World!
I (110289) app: Hello World!
I (111289) app: Hello World!
I (112289) app: Hello World!
I (113289) app: Hello World!
I (114289) app: Hello World!
I (115289) app: Hello World!
I (116289) app: Hello World!
I (117289) app: Hello World!
I (118289) app: Hello World!
I (119289) app: Hello World!
I (120289) app: Hello World!
I (121289) app: Hello World!
I (122289) app: Hello World!
I (123289) app: Hello World!
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7172
load:0x40078000,len:15540
load:0x40080400,len:4
0x40080400: _init at ??:?

ho 8 tail 4 room 4
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.2.2 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 14:26:55
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2a02ch (172076) map
I (163) esp_image: segment 1: paddr=0003a054 vaddr=3ffbdb60 size=05404h ( 21508) load
I (171) esp_image: segment 2: paddr=0003f460 vaddr=40080000 size=00bb8h (  3000) load
I (173) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=a15a0h (660896) map
I (404) esp_image: segment 4: paddr=000e15c8 vaddr=40080bb8 size=14850h ( 84048) load
I (448) boot: Loaded app from partition at offset 0x10000
I (448) boot: Disabling RNG early entropy source...
I (460) cpu_start: Multicore app
I (468) cpu_start: Pro cpu start user code
I (468) cpu_start: cpu freq: 160000000 Hz
I (469) cpu_start: Application information:
I (472) cpu_start: Project name:     wifi_prov_mgr
I (477) cpu_start: App version:      1
I (481) cpu_start: Compile time:     Sep 26 2024 14:54:06
I (488) cpu_start: ELF file SHA256:  29e067575...
I (493) cpu_start: ESP-IDF:          v5.2.2
I (498) cpu_start: Min chip rev:     v0.0
I (502) cpu_start: Max chip rev:     v3.99
I (507) cpu_start: Chip rev:         v3.0
I (512) heap_init: Initializing. RAM available for dynamic allocation:
I (519) heap_init: At 3FFAE6E0 len 0000F480 (61 KiB): DRAM
I (525) heap_init: At 3FFC7098 len 00018F68 (99 KiB): DRAM
I (532) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (538) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (544) heap_init: At 40095408 len 0000ABF8 (42 KiB): IRAM
I (552) spi_flash: detected chip: generic
I (555) spi_flash: flash io: dio
W (559) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (573) coexist: coex firmware version: d96c1e51f
I (579) main_task: Started on CPU0
I (589) main_task: Calling app_main()
I (639) wifi:wifi driver task: 3ffb80e0, prio:23, stack:6656, core=0
I (659) wifi:wifi firmware version: 3e0076f
I (659) wifi:wifi certification version: v7.0
I (659) wifi:config NVS flash: enabled
I (659) wifi:config nano formating: disabled
I (659) wifi:Init data frame dynamic rx buffer num: 32
I (669) wifi:Init static rx mgmt buffer num: 5
I (669) wifi:Init management short buffer num: 32
I (669) wifi:Init dynamic tx buffer num: 32
I (679) wifi:Init static rx buffer size: 1600
I (679) wifi:Init static rx buffer num: 10
I (689) wifi:Init dynamic rx buffer num: 32
I (689) wifi_init: rx ba win: 6
I (689) wifi_init: tcpip mbox: 32
I (699) wifi_init: udp mbox: 6
I (699) wifi_init: tcp mbox: 6
I (699) wifi_init: tcp tx win: 5760
I (709) wifi_init: tcp rx win: 5760
I (709) wifi_init: tcp mss: 1440
I (719) wifi_init: WiFi IRAM OP enabled
I (719) wifi_init: WiFi RX IRAM OP enabled
I (829) app: Button pressed
I (829) app: Starting provisioning
I (829) app: Development mode: using hard coded salt
I (829) app: Development mode: using hard coded verifier
I (839) phy_init: phy_version 4791,2c4672b,Dec 20 2023,16:06:06
I (919) wifi:mode : sta (94:b5:55:f8:5d:50)
I (919) wifi:enable tsf
I (929) wifi:mode : sta (94:b5:55:f8:5d:50) + softAP (94:b5:55:f8:5d:51)
I (939) wifi:Total power save buffer number: 16
I (939) wifi:Init max length of beacon: 752/752
I (939) wifi:Init max length of beacon: 752/752
I (949) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (949) wifi:Total power save buffer number: 16
I (959) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (969) wifi_prov_mgr: Provisioning started with service name : PROV_F85D50
I (969) app: Provisioning started
I (979) app: Scan this QR code from the provisioning application for Provisioning.
I (989) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (989) QRCODE: {"ver":"v1","name":"PROV_F85D50","username":"wifiprov","pop":"abcd1234","transport":"softap"}

  █▀▀▀▀▀█ ▀▀▀█▄ ▀ ▄█▄▄██  ▄▄▀ ▀ █▀▀▀▀▀█
  █ ███ █  ▀▄█ █▀ ▀▄▄  █▀ ▀█▄ █ █ ███ █
  █ ▀▀▀ █  ▄▀█▀▄█ ██ ▀█▄ ▄ ▄▀ ▄ █ ▀▀▀ █
  ▀▀▀▀▀▀▀ █▄▀ █▄█▄▀ █▄█ █ █▄█ ▀ ▀▀▀▀▀▀▀
  ▀█ ██ ▀▄ ▀▄ ▀ ▀██▀███  █▀ ▀█▄▄▀ ▄ ▄ ▀   
  ▀██  ▀▀ ▄ ▀ ▀  █▄▄█ █ █▀▀ ▄▀▀█   ▀██▀
  ▀  ▀  ▀▀ █▀ ▄▄▄▄ ▄█▀▀ ▀█▀▄ █ ▀▀█▄ ▄█▀
  ▄▀███▄▀▄ ▀▄ ▄▀ ██ ▄██ █ ▄  ▀▀ ▀▄▄▀▄██
  ▀▀▀ ▄█▀▀ █▀█▀▀▄█▄▄█▄█▄▄ ▀▀ ▀  █▄ ▀█▄▀   
   ▄▄ ▀ ▀▀▄▀ ▄▀██▀█ █▀█▀ █ █ ▀▄▀█ ▀█  ▀
  ▄▀▀▀ ▀▀█ ▀▄▀▄ ▄█ ▀ █  █▄  ▀█▄████▄▄█▀
  ██▀█  ▀█ ▀▀█▄▀▀█▄█▄   ▄▀█▀▀▀▄█▀▀▀▀█▄▀   
  █ ▄ ▄ ▀ ▀██▀▀  █▄  ▀▀ ▄██ ▄▄  █▀▄  ▀▀
  █▀██ ▀▀▄█▀▄█▀▀▀█ ▀██▄▀█▄█ ██▀█ █▀ █▄▀
  ▀ ▀▀▀▀▀▀▄▄█▄▄▄▀▄ ▄▄▄▀▄█ ▄▀ ▀█▀▀▀█▀█▀
  █ ███ █ █▀█ ▀��██ █���▄█  ���█▄█���▀██���▀█ ��▄
  █ ▀▀▀ █ ▄ ▄ ▀ ███▄▄▄▀▀▄█  ▄▄█ █▀█▀▄▄█
  ▀▀▀▀▀▀▀ ▀    ▀▀▀   ▀▀ ▀▀▀   ▀▀ ▀▀▀  ▀


I (1259) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_F85D50","username":"wifiprov","pop":"abcd1234","transport":"softap"} 