helloSystem 0.8.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


Test Cases
----------

Total: 298

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 0MGK50 A02                  | [fe0b9484f5](https://bsd-hardware.info/?probe=fe0b9484f5) | Jan 05, 2025 |
| MSI           | ZH77A-G43                   | [f000f3f0cc](https://bsd-hardware.info/?probe=f000f3f0cc) | Dec 16, 2024 |
| ASUSTek       | PRIME B550M-K               | [52f3e1cf1a](https://bsd-hardware.info/?probe=52f3e1cf1a) | Dec 09, 2024 |
| ASUSTek       | PRIME H510M-R               | [772e88509f](https://bsd-hardware.info/?probe=772e88509f) | Dec 04, 2024 |
| MSI           | Z97 GAMING 3                | [9cd14a585d](https://bsd-hardware.info/?probe=9cd14a585d) | Dec 04, 2024 |
| HP            | 339A                        | [3c450d9163](https://bsd-hardware.info/?probe=3c450d9163) | Dec 04, 2024 |
| ASUSTek       | PRIME B450M-A II            | [1a6e076d9f](https://bsd-hardware.info/?probe=1a6e076d9f) | Dec 02, 2024 |
| HP            | 3048h                       | [36a9b2f835](https://bsd-hardware.info/?probe=36a9b2f835) | Nov 29, 2024 |
| Inventec      | D CLASS A02                 | [dd77e68b2d](https://bsd-hardware.info/?probe=dd77e68b2d) | Nov 24, 2024 |
| Lenovo        | 30C9 SDK0J40705 WIN 3425... | [80514ce1ec](https://bsd-hardware.info/?probe=80514ce1ec) | Nov 22, 2024 |
| MSI           | PRO H610M-B DDR4            | [ed161aa339](https://bsd-hardware.info/?probe=ed161aa339) | Nov 21, 2024 |
| Biostar       | A68N-5200                   | [c0e81ef062](https://bsd-hardware.info/?probe=c0e81ef062) | Nov 13, 2024 |
| ASUSTek       | X99-A/USB                   | [92261cfa8a](https://bsd-hardware.info/?probe=92261cfa8a) | Oct 24, 2024 |
| ASUSTek       | PRIME Z590-A                | [f9dd56fa54](https://bsd-hardware.info/?probe=f9dd56fa54) | Oct 12, 2024 |
| Dell          | 00V62H A00                  | [87e3fa093a](https://bsd-hardware.info/?probe=87e3fa093a) | Oct 09, 2024 |
| Dell          | 03NVJ6 A01                  | [ebf63c5ffd](https://bsd-hardware.info/?probe=ebf63c5ffd) | Sep 22, 2024 |
| Supermicro    | X10DAi                      | [11f1473c17](https://bsd-hardware.info/?probe=11f1473c17) | Sep 17, 2024 |
| MSI           | Z170I GAMING PRO AC         | [373dba44f0](https://bsd-hardware.info/?probe=373dba44f0) | Sep 13, 2024 |
| MSI           | H81M-P33                    | [677cd5d559](https://bsd-hardware.info/?probe=677cd5d559) | Sep 10, 2024 |
| Gigabyte      | Z97X-Gaming 3               | [0e601e6efb](https://bsd-hardware.info/?probe=0e601e6efb) | Sep 09, 2024 |
| ASRock        | 970 Pro3 R2.0               | [2d6cb49646](https://bsd-hardware.info/?probe=2d6cb49646) | Aug 23, 2024 |
| ASRock        | A320M-ITX                   | [73f83a9526](https://bsd-hardware.info/?probe=73f83a9526) | Aug 22, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [e7df8e47f0](https://bsd-hardware.info/?probe=e7df8e47f0) | Aug 17, 2024 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [38f29aa721](https://bsd-hardware.info/?probe=38f29aa721) | Aug 14, 2024 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | [49322a0f1b](https://bsd-hardware.info/?probe=49322a0f1b) | Aug 10, 2024 |
| ASRock        | B450M-HDV R4.0              | [cd3e80c5af](https://bsd-hardware.info/?probe=cd3e80c5af) | Jul 28, 2024 |
| ASRock        | H67DE                       | [cd6ed79756](https://bsd-hardware.info/?probe=cd6ed79756) | Jul 26, 2024 |
| ASUSTek       | M5A78L-M/USB3               | [153f0e6cfb](https://bsd-hardware.info/?probe=153f0e6cfb) | Jul 25, 2024 |
| HP            | 18E7                        | [23520b25c4](https://bsd-hardware.info/?probe=23520b25c4) | Jul 12, 2024 |
| Unknown       | NF-MCP61                    | [74d9784221](https://bsd-hardware.info/?probe=74d9784221) | Jul 06, 2024 |
| Unknown       | NF-MCP61                    | [b2f074d817](https://bsd-hardware.info/?probe=b2f074d817) | Jul 06, 2024 |
| Gigabyte      | Z590 VISION G               | [39bb67c433](https://bsd-hardware.info/?probe=39bb67c433) | Jun 25, 2024 |
| Gigabyte      | H410M S2H V3                | [38e99138bb](https://bsd-hardware.info/?probe=38e99138bb) | Jun 12, 2024 |
| Dell          | 0PU052                      | [ed6212c9ae](https://bsd-hardware.info/?probe=ed6212c9ae) | Jun 07, 2024 |
| Gigabyte      | 945GCM-S2L                  | [7e175ff9bd](https://bsd-hardware.info/?probe=7e175ff9bd) | Jun 06, 2024 |
| Dell          | 03F1TC A00                  | [dbfad2d18f](https://bsd-hardware.info/?probe=dbfad2d18f) | Jun 02, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | [51df4f57c5](https://bsd-hardware.info/?probe=51df4f57c5) | Jun 02, 2024 |
| HP            | 21D0                        | [907ca67edb](https://bsd-hardware.info/?probe=907ca67edb) | May 27, 2024 |
| ASRock        | G41M-S3                     | [aeef672c4b](https://bsd-hardware.info/?probe=aeef672c4b) | May 17, 2024 |
| HP            | 83E1                        | [2227565c4c](https://bsd-hardware.info/?probe=2227565c4c) | May 15, 2024 |
| ASUSTek       | H110M-R                     | [26808aa91f](https://bsd-hardware.info/?probe=26808aa91f) | May 15, 2024 |
| ASUSTek       | H110M-R                     | [2a3fed3377](https://bsd-hardware.info/?probe=2a3fed3377) | May 15, 2024 |
| Acer          | Aspire XC-603               | [0d17afb0ea](https://bsd-hardware.info/?probe=0d17afb0ea) | May 13, 2024 |
| Pegatron      | 2A6C                        | [c133f11fe6](https://bsd-hardware.info/?probe=c133f11fe6) | May 11, 2024 |
| Dell          | 0DFRFW A01                  | [4532391ffd](https://bsd-hardware.info/?probe=4532391ffd) | May 06, 2024 |
| Unknown       | DH61BR G32662-203           | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| ASUSTek       | P5N32-E SLI                 | [52ac87d342](https://bsd-hardware.info/?probe=52ac87d342) | Apr 27, 2024 |
| Dell          | 0NW6H5 A00                  | [256e25b666](https://bsd-hardware.info/?probe=256e25b666) | Apr 16, 2024 |
| Gigabyte      | B85M-D3H                    | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| Gigabyte      | H55M-USB3                   | [748ef69c9f](https://bsd-hardware.info/?probe=748ef69c9f) | Mar 25, 2024 |
| HP            | 2B34                        | [850e6bf958](https://bsd-hardware.info/?probe=850e6bf958) | Mar 20, 2024 |
| HP            | 21D0                        | [7ca5d182a1](https://bsd-hardware.info/?probe=7ca5d182a1) | Mar 16, 2024 |
| HC Technol... | HCAR5000-MI                 | [2e83945861](https://bsd-hardware.info/?probe=2e83945861) | Mar 16, 2024 |
| HP            | dx2480 MT(FN868PA)          | [d700a91a81](https://bsd-hardware.info/?probe=d700a91a81) | Mar 14, 2024 |
| HP            | 21D0                        | [69b7737f88](https://bsd-hardware.info/?probe=69b7737f88) | Mar 12, 2024 |
| Gigabyte      | B550 GAMING X V2            | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| ASUSTek       | PRIME J3355I-C              | [0b1cea4778](https://bsd-hardware.info/?probe=0b1cea4778) | Mar 12, 2024 |
| Dell          | 07F37C A00                  | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| Gigabyte      | H81M-D3H                    | [798bfe44fe](https://bsd-hardware.info/?probe=798bfe44fe) | Feb 29, 2024 |
| Gigabyte      | P35-DS3                     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| Gigabyte      | P35-DS3                     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Intel         | STK1AW32SC H91596-303       | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| ASUSTek       | P5E3 PRO                    | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| ASUSTek       | A68HM-K                     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [5642aa5018](https://bsd-hardware.info/?probe=5642aa5018) | Jan 16, 2024 |
| ASRock        | AB350 Pro4                  | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Unknown       | Unknown                     | [514b270501](https://bsd-hardware.info/?probe=514b270501) | Jan 10, 2024 |
| Roqos         | Core RC10                   | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| Unknown       | Unknown                     | [9fed9e1dd9](https://bsd-hardware.info/?probe=9fed9e1dd9) | Jan 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [4b0c5d65b0](https://bsd-hardware.info/?probe=4b0c5d65b0) | Jan 02, 2024 |
| MSI           | Z270-A PRO                  | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Gigabyte      | B550 GAMING X V2            | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| HP            | 212B                        | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| HP            | 212B                        | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| ASUSTek       | H81M-C                      | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| Lenovo        | NOK                         | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| HP            | 3031h                       | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Gigabyte      | B450M H                     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| HP            | 18E7                        | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Shuttle       | NC10U                       | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| HP            | 1497                        | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| Gigabyte      | B250M-D3H-CF                | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Lenovo        | ThinkCentre M81 5049D7G     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | Z170-A                      | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| HP            | 83F3                        | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| MSI           | X570-A PRO                  | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| MSI           | Z390-A PRO                  | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Dell          | 0YXT71 A02                  | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| AZW           | U59                         | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Intel         | JSL MRD                     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| Intel         | H81                         | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| HP            | 0AACh                       | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| ASUSTek       | P5QL PRO                    | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| HP            | 83E1                        | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| HP            | 339A                        | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| ASRock        | H61M-VG3                    | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| ASUSTek       | P5QL PRO                    | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| HP            | 81C5 MVB                    | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Apple         | Mac-F221BEC8                | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| ECS           | H61H2-M17                   | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | H61M-GS                     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| HP            | 8055                        | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Dell          | 0X9X1W A00                  | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| Dell          | 0WR7PY A03                  | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Intel         | H81                         | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| HP            | 21D0                        | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Gigabyte      | X58A-UD3R                   | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Gigabyte      | Z490 VISION G               | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| ASUSTek       | PRIME A520M-K               | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Dell          | 0WN7Y6 A01                  | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Dell          | 07F37C A00                  | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| ASRock        | J4125-ITX                   | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| HP            | 82B4                        | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| Dell          | 0252PH A04                  | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| HP            | 8056                        | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Dell          | 0VTC0D A02                  | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Gigabyte      | A520M DS3H AC               | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| ASUSTek       | PRIME B250M-A               | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Acer          | Veriton M6620G              | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Lenovo        | Tilapia CRB                 | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Dell          | 0T1D10 A01                  | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| BESSTAR Te... | UM700                       | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| ASRock        | H61M-HVS                    | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| MSI           | 870-G45                     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| MSI           | 870-G45                     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| HP            | 8055                        | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Unknown       | Unknown                     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Unknown       | T360D11                     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| HP            | 8054                        | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| Dell          | 0GM819                      | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Google        | Panther                     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | 3398                        | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Gigabyte      | H81M-H                      | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 253      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 251      | 99.21%  |
| TWM          | 1        | 0.4%    |
| GNOME        | 1        | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 253      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 253      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 107      | 41.8%   |
| fr_FR   | 73       | 28.52%  |
| ru_RU   | 19       | 7.42%   |
| de_DE   | 13       | 5.08%   |
| Unknown | 11       | 4.3%    |
| es_ES   | 10       | 3.91%   |
| pt_BR   | 7        | 2.73%   |
| it_IT   | 5        | 1.95%   |
| pl_PL   | 2        | 0.78%   |
| jp_JP   | 2        | 0.78%   |
| zh_CN   | 1        | 0.39%   |
| tr_TR   | 1        | 0.39%   |
| pt_PT   | 1        | 0.39%   |
| fr      | 1        | 0.39%   |
| fi_FI   | 1        | 0.39%   |
| es      | 1        | 0.39%   |
| en_GB   | 1        | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 248      | 98.02%  |
| BIOS | 5        | 1.98%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 143      | 55%     |
| Zfs    | 117      | 45%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 248      | 98.02%  |
| MBR  | 5        | 1.98%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 58       | 22.92%  |
| Gigabyte Technology | 41       | 16.21%  |
| Hewlett-Packard     | 30       | 11.86%  |
| Dell                | 24       | 9.49%   |
| MSI                 | 20       | 7.91%   |
| Lenovo              | 15       | 5.93%   |
| ASRock              | 15       | 5.93%   |
| Intel               | 8        | 3.16%   |
| Unknown             | 8        | 3.16%   |
| Fujitsu             | 5        | 1.98%   |
| Acer                | 5        | 1.98%   |
| T-bao               | 2        | 0.79%   |
| Pegatron            | 2        | 0.79%   |
| Fujitsu Siemens     | 2        | 0.79%   |
| Foxconn             | 2        | 0.79%   |
| Biostar             | 2        | 0.79%   |
| AZW                 | 2        | 0.79%   |
| Supermicro          | 1        | 0.4%    |
| Shuttle             | 1        | 0.4%    |
| LG Electronics      | 1        | 0.4%    |
| Inventec            | 1        | 0.4%    |
| Huanan              | 1        | 0.4%    |
| HC Technology.      | 1        | 0.4%    |
| Google              | 1        | 0.4%    |
| ECS                 | 1        | 0.4%    |
| Daten Tecnologia    | 1        | 0.4%    |
| BESSTAR Tech        | 1        | 0.4%    |
| Axiomtek            | 1        | 0.4%    |
| Apple               | 1        | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 8        | 3.16%   |
| ASUS All Series                   | 5        | 1.98%   |
| HP ProDesk 600 G1 DM              | 3        | 1.19%   |
| Dell OptiPlex 780                 | 3        | 1.19%   |
| ASUS PRIME B250M-A                | 3        | 1.19%   |
| T-bao MINI PC                     | 2        | 0.79%   |
| MSI MS-7788                       | 2        | 0.79%   |
| Intel H81                         | 2        | 0.79%   |
| HP EliteDesk 800 G2 DM 35W        | 2        | 0.79%   |
| HP Compaq Elite 8300 USDT         | 2        | 0.79%   |
| Gigabyte B550 GAMING X V2         | 2        | 0.79%   |
| Dell OptiPlex 9020                | 2        | 0.79%   |
| Dell OptiPlex 755                 | 2        | 0.79%   |
| Dell OptiPlex 7010                | 2        | 0.79%   |
| Dell OptiPlex 3020                | 2        | 0.79%   |
| ASUS ROG STRIX B550-F GAMING      | 2        | 0.79%   |
| ASUS M5A78L-M/USB3                | 2        | 0.79%   |
| Supermicro X10DAi                 | 1        | 0.4%    |
| Shuttle NC10U                     | 1        | 0.4%    |
| Pegatron s5713w                   | 1        | 0.4%    |
| Pegatron Compaq dx2450 Microtower | 1        | 0.4%    |
| MSI MS-7D46                       | 1        | 0.4%    |
| MSI MS-7D30                       | 1        | 0.4%    |
| MSI MS-7C95                       | 1        | 0.4%    |
| MSI MS-7C83                       | 1        | 0.4%    |
| MSI MS-7C51                       | 1        | 0.4%    |
| MSI MS-7C37                       | 1        | 0.4%    |
| MSI MS-7C09                       | 1        | 0.4%    |
| MSI MS-7B98                       | 1        | 0.4%    |
| MSI MS-7B86                       | 1        | 0.4%    |
| MSI MS-7B17                       | 1        | 0.4%    |
| MSI MS-7A71                       | 1        | 0.4%    |
| MSI MS-7996                       | 1        | 0.4%    |
| MSI MS-7980                       | 1        | 0.4%    |
| MSI MS-7918                       | 1        | 0.4%    |
| MSI MS-7817                       | 1        | 0.4%    |
| MSI MS-7758                       | 1        | 0.4%    |
| MSI MS-7599                       | 1        | 0.4%    |
| MSI Compaq dx2200 MT              | 1        | 0.4%    |
| LG R590-K.AAA9BT                  | 1        | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 19       | 7.51%   |
| Dell OptiPlex           | 17       | 6.72%   |
| Lenovo ThinkCentre      | 14       | 5.53%   |
| HP Compaq               | 9        | 3.56%   |
| ASUS ROG                | 8        | 3.16%   |
| Unknown                 | 8        | 3.16%   |
| HP ProDesk              | 7        | 2.77%   |
| HP EliteDesk            | 5        | 1.98%   |
| ASUS All                | 5        | 1.98%   |
| Gigabyte B450M          | 4        | 1.58%   |
| Gigabyte B550           | 3        | 1.19%   |
| Fujitsu ESPRIMO         | 3        | 1.19%   |
| Dell Precision          | 3        | 1.19%   |
| ASUS TUF                | 3        | 1.19%   |
| T-bao MINI              | 2        | 0.79%   |
| MSI MS-7788             | 2        | 0.79%   |
| Intel H81               | 2        | 0.79%   |
| Fujitsu Siemens ESPRIMO | 2        | 0.79%   |
| Dell Vostro             | 2        | 0.79%   |
| Dell Inspiron           | 2        | 0.79%   |
| ASUS M5A78L-M           | 2        | 0.79%   |
| Acer Veriton            | 2        | 0.79%   |
| Acer Aspire             | 2        | 0.79%   |
| Supermicro X10DAi       | 1        | 0.4%    |
| Shuttle NC10U           | 1        | 0.4%    |
| Pegatron s5713w         | 1        | 0.4%    |
| Pegatron Compaq         | 1        | 0.4%    |
| MSI MS-7D46             | 1        | 0.4%    |
| MSI MS-7D30             | 1        | 0.4%    |
| MSI MS-7C95             | 1        | 0.4%    |
| MSI MS-7C83             | 1        | 0.4%    |
| MSI MS-7C51             | 1        | 0.4%    |
| MSI MS-7C37             | 1        | 0.4%    |
| MSI MS-7C09             | 1        | 0.4%    |
| MSI MS-7B98             | 1        | 0.4%    |
| MSI MS-7B86             | 1        | 0.4%    |
| MSI MS-7B17             | 1        | 0.4%    |
| MSI MS-7A71             | 1        | 0.4%    |
| MSI MS-7996             | 1        | 0.4%    |
| MSI MS-7980             | 1        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 24       | 9.49%   |
| 2021    | 23       | 9.09%   |
| 2020    | 21       | 8.3%    |
| 2013    | 19       | 7.51%   |
| 2019    | 18       | 7.11%   |
| 2014    | 18       | 7.11%   |
| 2012    | 18       | 7.11%   |
| 2011    | 15       | 5.93%   |
| 2010    | 15       | 5.93%   |
| 2017    | 14       | 5.53%   |
| 2018    | 12       | 4.74%   |
| 2016    | 12       | 4.74%   |
| 2015    | 11       | 4.35%   |
| 2009    | 9        | 3.56%   |
| 2008    | 9        | 3.56%   |
| 2023    | 8        | 3.16%   |
| 2007    | 3        | 1.19%   |
| 2006    | 2        | 0.79%   |
| 2024    | 1        | 0.4%    |
| Unknown | 1        | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 253      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 252      | 99.6%   |
| Yes  | 1        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 84       | 33.07%  |
| 16.01-24.0  | 76       | 29.92%  |
| 4.01-8.0    | 46       | 18.11%  |
| 32.01-64.0  | 27       | 10.63%  |
| 64.01-256.0 | 9        | 3.54%   |
| 2.01-3.0    | 5        | 1.97%   |
| 24.01-32.0  | 4        | 1.57%   |
| 3.01-4.0    | 2        | 0.79%   |
| 0.51-1.0    | 1        | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 115      | 44.92%  |
| 0.51-1.0 | 87       | 33.98%  |
| 1.01-2.0 | 41       | 16.02%  |
| 2.01-3.0 | 11       | 4.3%    |
| 3.01-4.0 | 2        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 123      | 48.43%  |
| 2      | 48       | 18.9%   |
| 3      | 35       | 13.78%  |
| 0      | 19       | 7.48%   |
| 5      | 11       | 4.33%   |
| 4      | 11       | 4.33%   |
| 9      | 2        | 0.79%   |
| 6      | 2        | 0.79%   |
| 13     | 1        | 0.39%   |
| 8      | 1        | 0.39%   |
| 7      | 1        | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 164      | 64.82%  |
| Yes       | 89       | 35.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 245      | 96.84%  |
| No        | 8        | 3.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 179      | 70.47%  |
| Yes       | 75       | 29.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 192      | 75.59%  |
| Yes       | 62       | 24.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 40       | 15.81%  |
| Russia      | 34       | 13.44%  |
| Germany     | 14       | 5.53%   |
| Brazil      | 14       | 5.53%   |
| Spain       | 11       | 4.35%   |
| Poland      | 9        | 3.56%   |
| France      | 9        | 3.56%   |
| Canada      | 9        | 3.56%   |
| Italy       | 8        | 3.16%   |
| Australia   | 7        | 2.77%   |
| Serbia      | 6        | 2.37%   |
| India       | 6        | 2.37%   |
| Hungary     | 6        | 2.37%   |
| Belgium     | 6        | 2.37%   |
| UK          | 5        | 1.98%   |
| Romania     | 5        | 1.98%   |
| China       | 5        | 1.98%   |
| Ukraine     | 4        | 1.58%   |
| Turkey      | 4        | 1.58%   |
| Netherlands | 4        | 1.58%   |
| Mexico      | 4        | 1.58%   |
| Japan       | 4        | 1.58%   |
| Indonesia   | 4        | 1.58%   |
| Peru        | 3        | 1.19%   |
| Bulgaria    | 3        | 1.19%   |
| Argentina   | 3        | 1.19%   |
| Sweden      | 2        | 0.79%   |
| Finland     | 2        | 0.79%   |
| Estonia     | 2        | 0.79%   |
| Austria     | 2        | 0.79%   |
| Venezuela   | 1        | 0.4%    |
| Switzerland | 1        | 0.4%    |
| South Korea | 1        | 0.4%    |
| Slovenia    | 1        | 0.4%    |
| San Marino  | 1        | 0.4%    |
| Portugal    | 1        | 0.4%    |
| Panama      | 1        | 0.4%    |
| Kyrgyzstan  | 1        | 0.4%    |
| Kazakhstan  | 1        | 0.4%    |
| Israel      | 1        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| St Petersburg       | 6        | 2.33%   |
| Sydney              | 4        | 1.56%   |
| Moscow              | 4        | 1.56%   |
| St. Jean Baptiste   | 3        | 1.17%   |
| Newburgh            | 3        | 1.17%   |
| Madrid              | 3        | 1.17%   |
| Belgrade            | 3        | 1.17%   |
| Vienna              | 2        | 0.78%   |
| Vantaa              | 2        | 0.78%   |
| Sofia               | 2        | 0.78%   |
| Sao Paulo           | 2        | 0.78%   |
| Penza               | 2        | 0.78%   |
| Paris               | 2        | 0.78%   |
| Novosibirsk         | 2        | 0.78%   |
| New York            | 2        | 0.78%   |
| Melbourne           | 2        | 0.78%   |
| Krakow              | 2        | 0.78%   |
| Kochi               | 2        | 0.78%   |
| Kirov               | 2        | 0.78%   |
| Istanbul            | 2        | 0.78%   |
| Curitiba            | 2        | 0.78%   |
| Brooklyn            | 2        | 0.78%   |
| Brisbane            | 2        | 0.78%   |
| Berlin              | 2        | 0.78%   |
| Bandung             | 2        | 0.78%   |
| Zurich              | 1        | 0.39%   |
| Zhengzhou           | 1        | 0.39%   |
| Yokohama            | 1        | 0.39%   |
| Woodbridge          | 1        | 0.39%   |
| Winnipeg            | 1        | 0.39%   |
| Warsaw              | 1        | 0.39%   |
| Volgodonsk          | 1        | 0.39%   |
| Vogogna             | 1        | 0.39%   |
| Vladimir            | 1        | 0.39%   |
| Virovitica          | 1        | 0.39%   |
| Villena             | 1        | 0.39%   |
| Verona              | 1        | 0.39%   |
| Venice              | 1        | 0.39%   |
| Vecses              | 1        | 0.39%   |
| Valparaiso de Goias | 1        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 68       | 110    | 17.17%  |
| Seagate             | 63       | 91     | 15.91%  |
| Samsung Electronics | 49       | 69     | 12.37%  |
| Kingston            | 38       | 39     | 9.6%    |
| Toshiba             | 20       | 26     | 5.05%   |
| Crucial             | 15       | 19     | 3.79%   |
| Hitachi             | 13       | 16     | 3.28%   |
| SanDisk             | 12       | 12     | 3.03%   |
| A-DATA Technology   | 12       | 13     | 3.03%   |
| Transcend           | 8        | 8      | 2.02%   |
| China               | 7        | 8      | 1.77%   |
| Intel               | 6        | 6      | 1.52%   |
| SPCC                | 5        | 6      | 1.26%   |
| Patriot             | 5        | 5      | 1.26%   |
| Micron Technology   | 5        | 6      | 1.26%   |
| Maxtor              | 4        | 4      | 1.01%   |
| KingSpec            | 4        | 4      | 1.01%   |
| HGST                | 4        | 4      | 1.01%   |
| PNY                 | 3        | 3      | 0.76%   |
| Lexar               | 3        | 3      | 0.76%   |
| Gigabyte Technology | 3        | 4      | 0.76%   |
| XPG                 | 2        | 3      | 0.51%   |
| Team                | 2        | 2      | 0.51%   |
| Netac               | 2        | 2      | 0.51%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.51%   |
| Apacer              | 2        | 2      | 0.51%   |
| AMD                 | 2        | 2      | 0.51%   |
| XUM                 | 1        | 1      | 0.25%   |
| XrayDisk            | 1        | 1      | 0.25%   |
| WALRAM              | 1        | 1      | 0.25%   |
| Verbatim            | 1        | 1      | 0.25%   |
| Vaseky              | 1        | 1      | 0.25%   |
| TAMMUZ              | 1        | 1      | 0.25%   |
| T-FORCE             | 1        | 1      | 0.25%   |
| SUNEAST             | 1        | 1      | 0.25%   |
| SK hynix            | 1        | 1      | 0.25%   |
| Silicon Motion      | 1        | 1      | 0.25%   |
| SETHRISE            | 1        | 1      | 0.25%   |
| RX7                 | 1        | 1      | 0.25%   |
| QUANTUM             | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 10       | 2.15%   |
| Seagate ST500DM002-1BD142 500GB | 6        | 1.29%   |
| Seagate ST3500418AS 500GB       | 5        | 1.07%   |
| Seagate ST1000DM010-2EP102 1TB  | 5        | 1.07%   |
| Samsung SSD 860 EVO 500GB       | 5        | 1.07%   |
| Toshiba DT01ACA100 1TB          | 4        | 0.86%   |
| Samsung SSD 870 EVO 500GB       | 4        | 0.86%   |
| Samsung SSD 850 EVO 250GB       | 4        | 0.86%   |
| Kingston SA400S37120G 120GB     | 4        | 0.86%   |
| Crucial CT500MX500SSD1 500GB    | 4        | 0.86%   |
| Crucial CT240BX500SSD1 240GB    | 4        | 0.86%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3        | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB    | 3        | 0.64%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3        | 0.64%   |
| WDC WD10EZEX-60WN4A0 1TB        | 3        | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 0.64%   |
| Toshiba HDWD110 1TB             | 3        | 0.64%   |
| Seagate ST380815AS 80GB         | 3        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 0.64%   |
| Samsung SSD 980 1TB             | 3        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB  | 3        | 0.64%   |
| Crucial CT1000P3SSD8 1TB        | 3        | 0.64%   |
| A-DATA SU650 120GB              | 3        | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.43%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.43%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2        | 0.43%   |
| WDC WD20EARS-00MVWB0 2TB        | 2        | 0.43%   |
| WDC WD10EZEX-60WN4A1 1TB        | 2        | 0.43%   |
| WDC WD10EZEX-00BBHA0 1TB        | 2        | 0.43%   |
| Transcend TS120GSSD220S 120GB   | 2        | 0.43%   |
| Toshiba MK3259GSXP 320GB        | 2        | 0.43%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.43%   |
| SPCC Solid State Disk 128GB     | 2        | 0.43%   |
| Seagate ST500LM021-1KJ152 500GB | 2        | 0.43%   |
| Seagate ST3500312CS 500GB       | 2        | 0.43%   |
| Seagate ST3320620AS 320GB       | 2        | 0.43%   |
| Seagate ST3320418AS 320GB       | 2        | 0.43%   |
| Seagate ST3250312AS 250GB       | 2        | 0.43%   |
| Seagate ST3160815AS 160GB       | 2        | 0.43%   |
| Seagate ST250DM000-1BD141 250GB | 2        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 62       | 90     | 37.58%  |
| WDC                 | 57       | 91     | 34.55%  |
| Toshiba             | 17       | 21     | 10.3%   |
| Hitachi             | 13       | 16     | 7.88%   |
| Samsung Electronics | 6        | 8      | 3.64%   |
| Maxtor              | 4        | 4      | 2.42%   |
| HGST                | 4        | 4      | 2.42%   |
| QUANTUM             | 1        | 1      | 0.61%   |
| Apple               | 1        | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 28       | 36     | 16.37%  |
| Kingston            | 26       | 27     | 15.2%   |
| WDC                 | 13       | 13     | 7.6%    |
| SanDisk             | 12       | 12     | 7.02%   |
| Crucial             | 12       | 14     | 7.02%   |
| Transcend           | 7        | 7      | 4.09%   |
| China               | 7        | 8      | 4.09%   |
| A-DATA Technology   | 7        | 7      | 4.09%   |
| SPCC                | 4        | 5      | 2.34%   |
| Patriot             | 4        | 4      | 2.34%   |
| KingSpec            | 4        | 4      | 2.34%   |
| Intel               | 4        | 4      | 2.34%   |
| Toshiba             | 3        | 5      | 1.75%   |
| PNY                 | 3        | 3      | 1.75%   |
| Micron Technology   | 2        | 2      | 1.17%   |
| KIOXIA-EXCERIA      | 2        | 2      | 1.17%   |
| Apacer              | 2        | 2      | 1.17%   |
| XUM                 | 1        | 1      | 0.58%   |
| XrayDisk            | 1        | 1      | 0.58%   |
| WALRAM              | 1        | 1      | 0.58%   |
| Verbatim            | 1        | 1      | 0.58%   |
| Vaseky              | 1        | 1      | 0.58%   |
| Team                | 1        | 1      | 0.58%   |
| TAMMUZ              | 1        | 1      | 0.58%   |
| T-FORCE             | 1        | 1      | 0.58%   |
| SUNEAST             | 1        | 1      | 0.58%   |
| SETHRISE            | 1        | 1      | 0.58%   |
| RX7                 | 1        | 1      | 0.58%   |
| Pioneer             | 1        | 1      | 0.58%   |
| Philips             | 1        | 1      | 0.58%   |
| Palit               | 1        | 1      | 0.58%   |
| OCZ                 | 1        | 1      | 0.58%   |
| MidasForce          | 1        | 1      | 0.58%   |
| LITEONIT            | 1        | 1      | 0.58%   |
| Lexar               | 1        | 1      | 0.58%   |
| Kston               | 1        | 1      | 0.58%   |
| Intenso             | 1        | 1      | 0.58%   |
| HEORIADY            | 1        | 1      | 0.58%   |
| GOODRAM             | 1        | 1      | 0.58%   |
| Gigabyte Technology | 1        | 2      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 139      | 236    | 40.88%  |
| SSD  | 134      | 187    | 39.41%  |
| NVMe | 67       | 83     | 19.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 221      | 423    | 76.74%  |
| NVMe | 67       | 83     | 23.26%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 187      | 270    | 65.61%  |
| 0.51-1.0   | 55       | 70     | 19.3%   |
| 1.01-2.0   | 25       | 49     | 8.77%   |
| 3.01-4.0   | 9        | 13     | 3.16%   |
| 4.01-10.0  | 5        | 14     | 1.75%   |
| 2.01-3.0   | 3        | 6      | 1.05%   |
| 10.01-20.0 | 1        | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 136      | 52.51%  |
| 251-500    | 36       | 13.9%   |
| 101-250    | 36       | 13.9%   |
| 51-100     | 30       | 11.58%  |
| 501-1000   | 11       | 4.25%   |
| 21-50      | 5        | 1.93%   |
| 1001-2000  | 4        | 1.54%   |
| Unknown    | 1        | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 248      | 98.02%  |
| 21-50   | 2        | 0.79%   |
| 251-500 | 1        | 0.4%    |
| 101-250 | 1        | 0.4%    |
| Unknown | 1        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| Toshiba MK3259GSXP 320GB                  | 2        | 2      | 2.86%   |
| Seagate ST3500418AS 500GB                 | 2        | 2      | 2.86%   |
| Seagate ST3320620AS 320GB                 | 2        | 2      | 2.86%   |
| WDC WDS480G2G0A-00JH30 480GB              | 1        | 1      | 1.43%   |
| WDC WD800JD-75MSA3 80GB                   | 1        | 1      | 1.43%   |
| WDC WD6400BPVT-22HXZT3 640GB              | 1        | 1      | 1.43%   |
| WDC WD5000BPVT-00HXZT1 500GB              | 1        | 1      | 1.43%   |
| WDC WD5000AAKX-08U6AA0 500GB              | 1        | 1      | 1.43%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1        | 1      | 1.43%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1        | 1      | 1.43%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1        | 1      | 1.43%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1        | 1      | 1.43%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1        | 1      | 1.43%   |
| WDC WD20EADS-00W4B0 2TB                   | 1        | 1      | 1.43%   |
| WDC WD1600YS-01SHB1 164GB                 | 1        | 1      | 1.43%   |
| WDC WD1600AAJS-60Z0A0 160GB               | 1        | 1      | 1.43%   |
| WDC WD15EARS-00Z5B1 1.5TB                 | 1        | 1      | 1.43%   |
| WDC WD10EZRX-00A8LB0 1TB                  | 1        | 1      | 1.43%   |
| WDC WD10EZEX-60WN4A0 1TB                  | 1        | 1      | 1.43%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1        | 1      | 1.43%   |
| WDC WD10EARS-00MVWB0 1TB                  | 1        | 1      | 1.43%   |
| WDC WD10EARS-003BB1 1TB                   | 1        | 1      | 1.43%   |
| WDC WD10EADS-11M2B2 1TB                   | 1        | 1      | 1.43%   |
| Transcend TS120GSSD220S 120GB             | 1        | 1      | 1.43%   |
| Toshiba MK8052GSX 80GB                    | 1        | 1      | 1.43%   |
| Toshiba DT01ACA100 1TB                    | 1        | 1      | 1.43%   |
| Toshiba DT01ABA200 2TB                    | 1        | 1      | 1.43%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1        | 1      | 1.43%   |
| Seagate ST500LM021-1KJ152 500GB           | 1        | 1      | 1.43%   |
| Seagate ST500LM000-1EJ162 500GB           | 1        | 1      | 1.43%   |
| Seagate ST500DM002-1BD142 500GB           | 1        | 1      | 1.43%   |
| Seagate ST380815AS 80GB                   | 1        | 1      | 1.43%   |
| Seagate ST380215AS 80GB                   | 1        | 1      | 1.43%   |
| Seagate ST3750528AS 752GB                 | 1        | 1      | 1.43%   |
| Seagate ST3500320AS 500GB                 | 1        | 1      | 1.43%   |
| Seagate ST3360320AS 360GB                 | 1        | 1      | 1.43%   |
| Seagate ST3320418AS 320GB                 | 1        | 1      | 1.43%   |
| Seagate ST3250312AS 250GB                 | 1        | 2      | 1.43%   |
| Seagate ST250DM000-1BD141 250GB           | 1        | 1      | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB            | 1        | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 20     | 27.69%  |
| Seagate             | 15       | 18     | 23.08%  |
| Samsung Electronics | 6        | 7      | 9.23%   |
| Hitachi             | 6        | 6      | 9.23%   |
| Toshiba             | 5        | 5      | 7.69%   |
| Maxtor              | 3        | 3      | 4.62%   |
| HGST                | 2        | 2      | 3.08%   |
| Crucial             | 2        | 2      | 3.08%   |
| Transcend           | 1        | 1      | 1.54%   |
| Silicon Motion      | 1        | 1      | 1.54%   |
| Micron Technology   | 1        | 1      | 1.54%   |
| Kingston            | 1        | 1      | 1.54%   |
| Intel               | 1        | 1      | 1.54%   |
| faspeed             | 1        | 1      | 1.54%   |
| China               | 1        | 1      | 1.54%   |
| A-DATA Technology   | 1        | 1      | 1.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 19     | 33.33%  |
| Seagate             | 15       | 18     | 29.41%  |
| Hitachi             | 6        | 6      | 11.76%  |
| Toshiba             | 5        | 5      | 9.8%    |
| Samsung Electronics | 3        | 4      | 5.88%   |
| Maxtor              | 3        | 3      | 5.88%   |
| HGST                | 2        | 2      | 3.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 51       | 57     | 78.46%  |
| SSD  | 10       | 10     | 15.38%  |
| NVMe | 4        | 4      | 6.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB     | 1        | 1      | 20%     |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 1      | 20%     |
| SanDisk pSSD 16GB               | 1        | 1      | 20%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 20%     |
| Hitachi HDS721032CLA362 320GB   | 1        | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 40%     |
| SanDisk             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |
| Hitachi             | 1        | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 188      | 410    | 69.63%  |
| Malfunc  | 63       | 71     | 23.33%  |
| Detected | 14       | 20     | 5.19%   |
| Failed   | 5        | 5      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 182      | 52.3%   |
| AMD                          | 60       | 17.24%  |
| Samsung Electronics          | 21       | 6.03%   |
| Kingston Technology Company  | 12       | 3.45%   |
| Silicon Motion               | 9        | 2.59%   |
| ASMedia Technology           | 9        | 2.59%   |
| SanDisk                      | 7        | 2.01%   |
| Nvidia                       | 7        | 2.01%   |
| Marvell Technology Group     | 7        | 2.01%   |
| JMicron Technology           | 5        | 1.44%   |
| Phison Electronics           | 4        | 1.15%   |
| Micron/Crucial Technology    | 4        | 1.15%   |
| ADATA Technology             | 4        | 1.15%   |
| Realtek Semiconductor        | 3        | 0.86%   |
| Micron Technology            | 3        | 0.86%   |
| VIA Technologies             | 2        | 0.57%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.57%   |
| SK hynix                     | 1        | 0.29%   |
| Shenzhen Longsys Electronics | 1        | 0.29%   |
| Seagate Technology           | 1        | 0.29%   |
| OCZ Technology Group         | 1        | 0.29%   |
| KIOXIA                       | 1        | 0.29%   |
| Broadcom / LSI               | 1        | 0.29%   |
| Areca Technology             | 1        | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31       | 7.21%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 25       | 5.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 20       | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15       | 3.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 3.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 2.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 2.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10       | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 1.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.86%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 8        | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 1.63%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 1.63%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 1.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.16%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.16%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5        | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.93%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 4        | 0.93%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4        | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 4        | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 4        | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3        | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 3        | 0.7%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 199      | 58.7%   |
| NVMe | 68       | 20.06%  |
| IDE  | 59       | 17.4%   |
| RAID | 11       | 3.24%   |
| SAS  | 1        | 0.29%   |
| SCSI | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 187      | 73.91%  |
| AMD    | 66       | 26.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 7        | 2.77%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 5        | 1.98%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 1.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4        | 1.58%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 1.58%   |
| Intel Core 2 Duo                            | 4        | 1.58%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.58%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 1.19%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 3        | 1.19%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 3        | 1.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 1.19%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 1.19%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3        | 1.19%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 1.19%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 1.19%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 1.19%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 1.19%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.19%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 1.19%   |
| AMD Ryzen 5 5600 6-Core Processor           | 3        | 1.19%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.19%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz         | 2        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.79%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 0.79%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2        | 0.79%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 0.79%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.79%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 0.79%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 0.79%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2        | 0.79%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 0.79%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2        | 0.79%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2        | 0.79%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 2        | 0.79%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 0.79%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 2        | 0.79%   |
| Intel Core 2 Duo CPU                        | 2        | 0.79%   |
| Intel Celeron N5105 @ 2.00GHz               | 2        | 0.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 0.79%   |
| Intel 12th Gen Core i5-12400                | 2        | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 50       | 19.76%  |
| Intel Core i3           | 33       | 13.04%  |
| Intel Core i7           | 30       | 11.86%  |
| AMD Ryzen 5             | 20       | 7.91%   |
| Intel Celeron           | 16       | 6.32%   |
| Intel Core 2 Duo        | 15       | 5.93%   |
| Intel Xeon              | 13       | 5.14%   |
| Other                   | 11       | 4.35%   |
| AMD Ryzen 7             | 11       | 4.35%   |
| Intel Pentium           | 7        | 2.77%   |
| AMD Ryzen 3             | 6        | 2.37%   |
| AMD Athlon II X2        | 5        | 1.98%   |
| Intel Pentium Dual-Core | 3        | 1.19%   |
| Intel Core 2 Quad       | 3        | 1.19%   |
| AMD Phenom II X4        | 3        | 1.19%   |
| AMD FX                  | 3        | 1.19%   |
| Intel Core i9           | 2        | 0.79%   |
| AMD Phenom II X6        | 2        | 0.79%   |
| AMD A6                  | 2        | 0.79%   |
| AMD A4                  | 2        | 0.79%   |
| Intel Pentium Gold      | 1        | 0.4%    |
| Intel Pentium 4         | 1        | 0.4%    |
| Intel Core 2            | 1        | 0.4%    |
| Intel Atom              | 1        | 0.4%    |
| AMD Ryzen 9             | 1        | 0.4%    |
| AMD Ryzen 3 PRO         | 1        | 0.4%    |
| AMD PRO A10             | 1        | 0.4%    |
| AMD Phenom II X2        | 1        | 0.4%    |
| AMD GX                  | 1        | 0.4%    |
| AMD G                   | 1        | 0.4%    |
| AMD E                   | 1        | 0.4%    |
| AMD Athlon X2           | 1        | 0.4%    |
| AMD Athlon II X4        | 1        | 0.4%    |
| AMD Athlon 64 X2        | 1        | 0.4%    |
| AMD Athlon 64           | 1        | 0.4%    |
| AMD A10                 | 1        | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 106      | 41.9%   |
| 2       | 68       | 26.88%  |
| 6       | 25       | 9.88%   |
| 12      | 17       | 6.72%   |
| 8       | 12       | 4.74%   |
| 16      | 10       | 3.95%   |
| Unknown | 9        | 3.56%   |
| 10      | 2        | 0.79%   |
| 1       | 2        | 0.79%   |
| 24      | 1        | 0.4%    |
| 14      | 1        | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 250      | 98.81%  |
| 2      | 3        | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 155      | 61.26%  |
| 2       | 88       | 34.78%  |
| Unknown | 10       | 3.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 40       | 15.81%  |
| KabyLake      | 28       | 11.07%  |
| Skylake       | 20       | 7.91%   |
| IvyBridge     | 20       | 7.91%   |
| Penryn        | 17       | 6.72%   |
| SandyBridge   | 16       | 6.32%   |
| Zen 3         | 15       | 5.93%   |
| K10           | 13       | 5.14%   |
| Unknown       | 13       | 5.14%   |
| Zen+          | 12       | 4.74%   |
| Core          | 8        | 3.16%   |
| CometLake     | 8        | 3.16%   |
| Zen           | 7        | 2.77%   |
| Piledriver    | 6        | 2.37%   |
| Silvermont    | 5        | 1.98%   |
| Zen 2         | 4        | 1.58%   |
| Nehalem       | 4        | 1.58%   |
| Westmere      | 2        | 0.79%   |
| K8 Hammer     | 2        | 0.79%   |
| Jaguar        | 2        | 0.79%   |
| Goldmont plus | 2        | 0.79%   |
| Goldmont      | 2        | 0.79%   |
| Broadwell     | 2        | 0.79%   |
| Bobcat        | 2        | 0.79%   |
| NetBurst      | 1        | 0.4%    |
| Excavator     | 1        | 0.4%    |
| Bulldozer     | 1        | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 115      | 42.28%  |
| AMD                        | 84       | 30.88%  |
| Nvidia                     | 72       | 26.47%  |
| Matrox Electronics Systems | 1        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22       | 8%      |
| Intel HD Graphics 530                                                                    | 13       | 4.73%   |
| Intel HD Graphics 630                                                                    | 11       | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 3.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 3.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8        | 2.91%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 2.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 2.55%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7        | 2.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7        | 2.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 2.18%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4        | 1.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 3        | 1.09%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3        | 1.09%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3        | 1.09%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3        | 1.09%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3        | 1.09%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 3        | 1.09%   |
| AMD RS880 [Radeon HD 4250]                                                               | 3        | 1.09%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 3        | 1.09%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3        | 1.09%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3        | 1.09%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.73%   |
| Nvidia GP106 [P106-100]                                                                  | 2        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2        | 0.73%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2        | 0.73%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 2        | 0.73%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 2        | 0.73%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 0.73%   |
| Intel HD Graphics 500                                                                    | 2        | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 0.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.73%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2        | 0.73%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 92       | 35.94%  |
| 1 x AMD                  | 72       | 28.13%  |
| 1 x Nvidia               | 63       | 24.61%  |
| Intel + AMD              | 10       | 3.91%   |
| 2 x Intel                | 7        | 2.73%   |
| Intel + Nvidia           | 7        | 2.73%   |
| Other                    | 1        | 0.39%   |
| 2 x AMD                  | 1        | 0.39%   |
| 1 x Matrox               | 1        | 0.39%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.39%   |
| AMD + Nvidia             | 1        | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 202      | 79.22%  |
| Proprietary | 48       | 18.82%  |
| Unknown     | 5        | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 164      | 63.81%  |
| 3.01-4.0   | 24       | 9.34%   |
| 1.01-2.0   | 19       | 7.39%   |
| 0.51-1.0   | 15       | 5.84%   |
| 0.01-0.5   | 13       | 5.06%   |
| 7.01-8.0   | 9        | 3.5%    |
| 5.01-6.0   | 8        | 3.11%   |
| 8.01-16.0  | 3        | 1.17%   |
| 2.01-3.0   | 2        | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 12.86%  |
| Dell                 | 16       | 11.43%  |
| Acer                 | 16       | 11.43%  |
| Goldstar             | 12       | 8.57%   |
| Hewlett-Packard      | 11       | 7.86%   |
| BenQ                 | 9        | 6.43%   |
| Philips              | 7        | 5%      |
| Ancor Communications | 7        | 5%      |
| ASUSTek Computer     | 5        | 3.57%   |
| AOC                  | 5        | 3.57%   |
| Lenovo               | 3        | 2.14%   |
| ViewSonic            | 2        | 1.43%   |
| ONN                  | 2        | 1.43%   |
| LG Electronics       | 2        | 1.43%   |
| Fujitsu Siemens      | 2        | 1.43%   |
| Unknown              | 2        | 1.43%   |
| Vizio                | 1        | 0.71%   |
| UGD                  | 1        | 0.71%   |
| Semp Toshiba         | 1        | 0.71%   |
| SAC                  | 1        | 0.71%   |
| PKB                  | 1        | 0.71%   |
| NEC Computers        | 1        | 0.71%   |
| MStar                | 1        | 0.71%   |
| MSI                  | 1        | 0.71%   |
| Microstep            | 1        | 0.71%   |
| Mi                   | 1        | 0.71%   |
| Medion               | 1        | 0.71%   |
| ITE                  | 1        | 0.71%   |
| IOD                  | 1        | 0.71%   |
| Iiyama               | 1        | 0.71%   |
| Idek Iiyama          | 1        | 0.71%   |
| Eizo                 | 1        | 0.71%   |
| DEX                  | 1        | 0.71%   |
| DENON                | 1        | 0.71%   |
| CVT                  | 1        | 0.71%   |
| AUS                  | 1        | 0.71%   |
| Apple                | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ONN 100002487 ONN0101 1920x1080 520x320mm 24.0-inch                    | 2        | 1.43%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 1.43%   |
| Unknown                                                                | 2        | 1.43%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 0.71%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 600x340mm 27.2-inch              | 1        | 0.71%   |
| ViewSonic TD2220 VSC052C 1920x1080 480x270mm 21.7-inch                 | 1        | 0.71%   |
| UGD Artist13.3pro UGD1302 1920x1080 290x160mm 13.0-inch                | 1        | 0.71%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM0523 1920x1080 480x270mm 21.7-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch   | 1        | 0.71%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.71%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch    | 1        | 0.71%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch      | 1        | 0.71%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 0.71%   |
| Samsung Electronics S24E450 SAM0C80 1920x1080 520x290mm 23.4-inch      | 1        | 0.71%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 0.71%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1        | 0.71%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 0.71%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 0.71%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 520x290mm 23.4-inch   | 1        | 0.71%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                      | 1        | 0.71%   |
| SAC LED MONITOR SAC952D 1920x1080 600x340mm 27.2-inch                  | 1        | 0.71%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 0.71%   |
| Philips PHL 271S9 PHL0987 1920x1080 600x340mm 27.2-inch                | 1        | 0.71%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 0.71%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 0.71%   |
| Philips 298P4 PHLC0BE 2560x1080 670x280mm 28.6-inch                    | 1        | 0.71%   |
| Philips 227ELH PHLC07B 1920x1080 480x270mm 21.7-inch                   | 1        | 0.71%   |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                     | 1        | 0.71%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 0.71%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 0.71%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1        | 0.71%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 0.71%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 0.71%   |
| Mi Monitor XMI23C3 1920x1080 530x290mm 23.8-inch                       | 1        | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 78       | 56.52%  |
| 1366x768 (WXGA)    | 14       | 10.14%  |
| 2560x1440 (QHD)    | 11       | 7.97%   |
| 1280x1024 (SXGA)   | 8        | 5.8%    |
| 1680x1050 (WSXGA+) | 5        | 3.62%   |
| 3840x2160 (4K)     | 4        | 2.9%    |
| 1920x1200 (WUXGA)  | 3        | 2.17%   |
| 1600x900 (HD+)     | 3        | 2.17%   |
| 1440x900 (WXGA+)   | 3        | 2.17%   |
| 2560x1080          | 2        | 1.45%   |
| 1024x768 (XGA)     | 2        | 1.45%   |
| Unknown            | 2        | 1.45%   |
| 5760x2160          | 1        | 0.72%   |
| 3840x1080          | 1        | 0.72%   |
| 1360x768           | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 26       | 18.98%  |
| 24      | 25       | 18.25%  |
| 27      | 18       | 13.14%  |
| Unknown | 18       | 13.14%  |
| 23      | 13       | 9.49%   |
| 18      | 11       | 8.03%   |
| 19      | 10       | 7.3%    |
| 31      | 4        | 2.92%   |
| 22      | 3        | 2.19%   |
| 20      | 3        | 2.19%   |
| 14      | 2        | 1.46%   |
| 52      | 1        | 0.73%   |
| 34      | 1        | 0.73%   |
| 28      | 1        | 0.73%   |
| 13      | 1        | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 40.15%  |
| 401-500     | 46       | 33.58%  |
| Unknown     | 18       | 13.14%  |
| 351-400     | 7        | 5.11%   |
| 601-700     | 6        | 4.38%   |
| 201-300     | 3        | 2.19%   |
| 701-800     | 1        | 0.73%   |
| 1001-1500   | 1        | 0.73%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 93       | 69.4%   |
| Unknown | 17       | 12.69%  |
| 16/10   | 13       | 9.7%    |
| 5/4     | 5        | 3.73%   |
| 6/5     | 2        | 1.49%   |
| 4/3     | 2        | 1.49%   |
| 21/9    | 2        | 1.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 42.34%  |
| 301-350        | 18       | 13.14%  |
| Unknown        | 18       | 13.14%  |
| 151-200        | 16       | 11.68%  |
| 141-150        | 10       | 7.3%    |
| 251-300        | 8        | 5.84%   |
| 351-500        | 5        | 3.65%   |
| 101-110        | 2        | 1.46%   |
| More than 1000 | 1        | 0.73%   |
| 71-80          | 1        | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 77       | 56.62%  |
| 101-120 | 31       | 22.79%  |
| Unknown | 18       | 13.24%  |
| 121-160 | 6        | 4.41%   |
| 1-50    | 3        | 2.21%   |
| 161-240 | 1        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 203      | 79.92%  |
| 0     | 43       | 16.93%  |
| 2     | 8        | 3.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 147      | 46.96%  |
| Intel                                  | 107      | 34.19%  |
| Qualcomm Atheros                       | 19       | 6.07%   |
| Ralink Technology                      | 5        | 1.6%    |
| Marvell Technology Group               | 5        | 1.6%    |
| Samsung Electronics                    | 4        | 1.28%   |
| Ralink                                 | 4        | 1.28%   |
| Broadcom                               | 4        | 1.28%   |
| TP-Link                                | 3        | 0.96%   |
| Edimax Technology                      | 3        | 0.96%   |
| Huawei Technologies                    | 2        | 0.64%   |
| D-Link                                 | 2        | 0.64%   |
| Qualcomm                               | 1        | 0.32%   |
| National Semiconductor                 | 1        | 0.32%   |
| MediaTek                               | 1        | 0.32%   |
| Fujitsu Connected Technologies Limited | 1        | 0.32%   |
| D-Link System                          | 1        | 0.32%   |
| Atheros                                | 1        | 0.32%   |
| Arduino SA                             | 1        | 0.32%   |
| Accton Technology                      | 1        | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 127      | 36.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13       | 3.74%   |
| Intel Ethernet Controller I225-V                                       | 10       | 2.87%   |
| Intel Ethernet Connection I217-LM                                      | 10       | 2.87%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6        | 1.72%   |
| Intel I211 Gigabit Network Connection                                  | 6        | 1.72%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 1.72%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 6        | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5        | 1.44%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 0.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3        | 0.86%   |
| Intel Wireless 7260                                                    | 3        | 0.86%   |
| Intel Wireless 3165                                                    | 3        | 0.86%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 0.86%   |
| Intel Ethernet Connection (17) I219-V                                  | 3        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 0.86%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 0.86%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3        | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.57%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 0.57%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                           | 2        | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 0.57%   |
| Ralink RT2500 Wireless 802.11bg                                        | 2        | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 26       | 31.71%  |
| Realtek Semiconductor | 21       | 25.61%  |
| Qualcomm Atheros      | 10       | 12.2%   |
| Ralink Technology     | 5        | 6.1%    |
| Ralink                | 4        | 4.88%   |
| Broadcom              | 4        | 4.88%   |
| TP-Link               | 3        | 3.66%   |
| Edimax Technology     | 3        | 3.66%   |
| D-Link                | 2        | 2.44%   |
| MediaTek              | 1        | 1.22%   |
| D-Link System         | 1        | 1.22%   |
| Atheros               | 1        | 1.22%   |
| Accton Technology     | 1        | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 7.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5        | 6.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3        | 3.61%   |
| Intel Wireless 7260                                            | 3        | 3.61%   |
| Intel Wireless 3165                                            | 3        | 3.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2        | 2.41%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2        | 2.41%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 2        | 2.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 2.41%   |
| Ralink MT7601U Wireless Adapter                                | 2        | 2.41%   |
| Ralink RT2500 Wireless 802.11bg                                | 2        | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2        | 2.41%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 2.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 2.41%   |
| Intel Wireless 8265 / 8275                                     | 2        | 2.41%   |
| Intel Wireless 8260                                            | 2        | 2.41%   |
| Intel Wireless 7265                                            | 2        | 2.41%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2        | 2.41%   |
| Intel Wi-Fi 6 AX200                                            | 2        | 2.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2        | 2.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2        | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 2.41%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2        | 2.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2        | 2.41%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1        | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1        | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 1.2%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1        | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 1.2%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 1.2%    |
| Ralink RT3072 Wireless Adapter                                 | 1        | 1.2%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.2%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1        | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1        | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 1        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1        | 1.2%    |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]       | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 138      | 53.49%  |
| Intel                                  | 96       | 37.21%  |
| Qualcomm Atheros                       | 9        | 3.49%   |
| Marvell Technology Group               | 5        | 1.94%   |
| Samsung Electronics                    | 4        | 1.55%   |
| Huawei Technologies                    | 2        | 0.78%   |
| Qualcomm                               | 1        | 0.39%   |
| National Semiconductor                 | 1        | 0.39%   |
| Fujitsu Connected Technologies Limited | 1        | 0.39%   |
| Broadcom                               | 1        | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 127      | 48.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13       | 4.92%   |
| Intel Ethernet Controller I225-V                                       | 10       | 3.79%   |
| Intel Ethernet Connection I217-LM                                      | 10       | 3.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9        | 3.41%   |
| Intel I211 Gigabit Network Connection                                  | 6        | 2.27%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 2.27%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 6        | 2.27%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4        | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4        | 1.52%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                   | 4        | 1.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.14%   |
| Intel I210 Gigabit Network Connection                                  | 3        | 1.14%   |
| Intel Ethernet Connection (17) I219-V                                  | 3        | 1.14%   |
| Intel Ethernet Connection (14) I219-V                                  | 3        | 1.14%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 3        | 1.14%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.76%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.76%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.76%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 0.76%   |
| Intel Ethernet Connection (2) I218-V                                   | 2        | 0.76%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 2        | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.38%   |
| Qualcomm FP3                                                           | 1        | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.38%   |
| National DP83815 (MacPhyter) Ethernet Controller                       | 1        | 0.38%   |
| Marvell Group 88E8070 based Ethernet Controller                        | 1        | 0.38%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.38%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.38%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 245      | 76.32%  |
| WiFi     | 75       | 23.36%  |
| Modem    | 1        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 215      | 94.71%  |
| WiFi     | 12       | 5.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 177      | 69.69%  |
| 2     | 64       | 25.2%   |
| 0     | 7        | 2.76%   |
| 3     | 6        | 2.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 242      | 94.53%  |
| Yes  | 14       | 5.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 24       | 36.36%  |
| Realtek Semiconductor           | 13       | 19.7%   |
| Cambridge Silicon Radio         | 11       | 16.67%  |
| TP-Link                         | 3        | 4.55%   |
| ASUSTek Computer                | 3        | 4.55%   |
| Lite-On Technology              | 2        | 3.03%   |
| IMC Networks                    | 2        | 3.03%   |
| Broadcom                        | 2        | 3.03%   |
| Apple                           | 2        | 3.03%   |
| Qualcomm Atheros Communications | 1        | 1.52%   |
| Primax Electronics              | 1        | 1.52%   |
| Fujitsu                         | 1        | 1.52%   |
| Belkin Components               | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 12       | 18.18%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 11       | 16.67%  |
| Realtek Bluetooth Adapter                                   | 8        | 12.12%  |
| TP-Link Bluetooth 5.0 USB Adapter                           | 3        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 4.55%   |
| Intel AX201 Bluetooth                                       | 3        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 3.03%   |
| Realtek Bluetooth 5.1 Adapter                               | 2        | 3.03%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 3.03%   |
| Intel AX210 Bluetooth                                       | 2        | 3.03%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 3.03%   |
| Realtek Bluetooth 4.2 Adapter                               | 1        | 1.52%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 1.52%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 1.52%   |
| Lite-On Bluetooth USB Module                                | 1        | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 1.52%   |
| Intel AX200 Bluetooth                                       | 1        | 1.52%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 1.52%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 1.52%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 1.52%   |
| Belkin Components F8T001v2 Bluetooth                        | 1        | 1.52%   |
| ASUS USB-BT500                                              | 1        | 1.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 1.52%   |
| ASUS Bluetooth Controller                                   | 1        | 1.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.52%   |
| Apple Bluetooth Host Controller                             | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 176      | 44.11%  |
| AMD                      | 101      | 25.31%  |
| Nvidia                   | 66       | 16.54%  |
| C-Media Electronics      | 20       | 5.01%   |
| Texas Instruments        | 5        | 1.25%   |
| JMTek                    | 3        | 0.75%   |
| Creative Labs            | 3        | 0.75%   |
| SteelSeries ApS          | 2        | 0.5%    |
| Realtek Semiconductor    | 2        | 0.5%    |
| Unknown                  | 2        | 0.5%    |
| Yamaha                   | 1        | 0.25%   |
| Superlux digit           | 1        | 0.25%   |
| Sony                     | 1        | 0.25%   |
| RODE Microphones         | 1        | 0.25%   |
| Razer USA                | 1        | 0.25%   |
| OPPO Electronics         | 1        | 0.25%   |
| Nektar                   | 1        | 0.25%   |
| Microsoft                | 1        | 0.25%   |
| Micro Star International | 1        | 0.25%   |
| M-Audio                  | 1        | 0.25%   |
| KTMicro                  | 1        | 0.25%   |
| Hewlett-Packard          | 1        | 0.25%   |
| HECATE G2 GAMING HEADSET | 1        | 0.25%   |
| Harman                   | 1        | 0.25%   |
| Generalplus Technology   | 1        | 0.25%   |
| GEMBIRD                  | 1        | 0.25%   |
| Edifier Technology       | 1        | 0.25%   |
| Creative Technology      | 1        | 0.25%   |
| Cambridge Silicon Radio  | 1        | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32       | 6.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 28       | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20       | 4.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 4.02%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 3.59%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 17       | 3.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14       | 2.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13       | 2.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11       | 2.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 2.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 2.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                 | 9        | 1.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 9        | 1.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 1.48%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 7        | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 1.27%   |
| AMD FCH Azalia Controller                                                  | 6        | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.06%   |
| Nvidia MCP61 High Definition Audio                                         | 5        | 1.06%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.06%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.06%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.85%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 4        | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 0.85%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3        | 0.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 3        | 0.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.63%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 53       | 17.55%  |
| Samsung Electronics          | 35       | 11.59%  |
| Unknown                      | 32       | 10.6%   |
| SK hynix                     | 25       | 8.28%   |
| Micron Technology            | 24       | 7.95%   |
| Corsair                      | 23       | 7.62%   |
| Crucial                      | 22       | 7.28%   |
| G.Skill                      | 16       | 5.3%    |
| Unknown                      | 13       | 4.3%    |
| Nanya Technology             | 7        | 2.32%   |
| A-DATA Technology            | 7        | 2.32%   |
| Patriot                      | 6        | 1.99%   |
| Ramaxel Technology           | 4        | 1.32%   |
| GOODRAM                      | 3        | 0.99%   |
| Apacer                       | 3        | 0.99%   |
| Unknown (ABCD)               | 2        | 0.66%   |
| Transcend                    | 2        | 0.66%   |
| Team                         | 2        | 0.66%   |
| Lexar                        | 2        | 0.66%   |
| Kingmax                      | 2        | 0.66%   |
| GeIL                         | 2        | 0.66%   |
| Atermiter                    | 2        | 0.66%   |
| AMD                          | 2        | 0.66%   |
| Unknown (8A02)               | 1        | 0.33%   |
| Unknown (0x7FFF)             | 1        | 0.33%   |
| Teikon                       | 1        | 0.33%   |
| Smart                        | 1        | 0.33%   |
| Silicon Power                | 1        | 0.33%   |
| Qumo                         | 1        | 0.33%   |
| Patriot Memory (PDP Systems) | 1        | 0.33%   |
| Netac                        | 1        | 0.33%   |
| MemoWise                     | 1        | 0.33%   |
| Juhor                        | 1        | 0.33%   |
| Golden Empire                | 1        | 0.33%   |
| Elpida                       | 1        | 0.33%   |
| Avant                        | 1        | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 13       | 3.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 5        | 1.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 5        | 1.53%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 4        | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 3        | 0.92%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 3        | 0.92%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 3        | 0.92%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 3        | 0.92%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 3        | 0.92%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 3        | 0.92%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                             | 3        | 0.92%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 2        | 0.61%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 2        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 2        | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 2        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s          | 2        | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 2        | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                    | 2        | 0.61%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 2        | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                   | 2        | 0.61%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s                     | 2        | 0.61%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.61%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s                     | 2        | 0.61%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 0.61%   |
| Patriot RAM 2666 C16 Series 16GB DIMM DDR4 3000MT/s                     | 2        | 0.61%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s                      | 2        | 0.61%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s                      | 2        | 0.61%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s                      | 2        | 0.61%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 0.61%   |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 1600MT/s                     | 2        | 0.61%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 0.61%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s                   | 2        | 0.61%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 0.61%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3733MT/s                   | 2        | 0.61%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s                    | 2        | 0.61%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3200MT/s                     | 2        | 0.61%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s                  | 2        | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.31%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                    | 1        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 111      | 44.22%  |
| DDR3    | 93       | 37.05%  |
| Unknown | 20       | 7.97%   |
| DDR2    | 17       | 6.77%   |
| SDRAM   | 5        | 1.99%   |
| LPDDR4  | 2        | 0.8%    |
| DDR     | 2        | 0.8%    |
| DDR5    | 1        | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 215      | 85.66%  |
| SODIMM | 36       | 14.34%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 111      | 39.22%  |
| 4096  | 73       | 25.8%   |
| 2048  | 46       | 16.25%  |
| 16384 | 33       | 11.66%  |
| 1024  | 15       | 5.3%    |
| 32768 | 5        | 1.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 56       | 20.9%   |
| 1333    | 48       | 17.91%  |
| 3200    | 32       | 11.94%  |
| 2133    | 24       | 8.96%   |
| 2667    | 22       | 8.21%   |
| 2400    | 22       | 8.21%   |
| 800     | 14       | 5.22%   |
| 667     | 10       | 3.73%   |
| 3600    | 5        | 1.87%   |
| 2666    | 4        | 1.49%   |
| 1067    | 4        | 1.49%   |
| 1066    | 4        | 1.49%   |
| Unknown | 4        | 1.49%   |
| 3000    | 3        | 1.12%   |
| 1867    | 3        | 1.12%   |
| 3733    | 2        | 0.75%   |
| 400     | 2        | 0.75%   |
| 6400    | 1        | 0.37%   |
| 4400    | 1        | 0.37%   |
| 4000    | 1        | 0.37%   |
| 3333    | 1        | 0.37%   |
| 2933    | 1        | 0.37%   |
| 1866    | 1        | 0.37%   |
| 1639    | 1        | 0.37%   |
| 1200    | 1        | 0.37%   |
| 533     | 1        | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 4        | 80%     |
| Hewlett-Packard    | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| HP LaserJet 3390           | 1        | 20%     |
| Brother HL-L3270CDW series | 1        | 20%     |
| Brother HL-L2300D series   | 1        | 20%     |
| Brother DCP-J152W          | 1        | 20%     |
| Brother DCP-9015CDW        | 1        | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 2        | 66.67%  |
| Seiko Epson | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seiko Epson PX-501A [Stylus NX400] | 1        | 33.33%  |
| Canon CanoScan LiDE 700F           | 1        | 33.33%  |
| Canon CanoScan LiDE 120            | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 7        | 35%     |
| Microdia                      | 3        | 15%     |
| GEMBIRD                       | 2        | 10%     |
| Trust                         | 1        | 5%      |
| Sunplus Innovation Technology | 1        | 5%      |
| SHENZHEN AONI ELECTRONIC      | 1        | 5%      |
| Lenovo                        | 1        | 5%      |
| Importek                      | 1        | 5%      |
| IMC Networks                  | 1        | 5%      |
| Genesys Logic                 | 1        | 5%      |
| Chicony Electronics           | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 15%     |
| Microdia USB  Live camera                         | 2        | 10%     |
| Logitech HD Pro Webcam C920                       | 2        | 10%     |
| Trust Trust Full HD Webcam                        | 1        | 5%      |
| Sunplus Integrated_Webcam_HD                      | 1        | 5%      |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera    | 1        | 5%      |
| Microdia Webcam Vitade AF                         | 1        | 5%      |
| Logitech Webcam C170                              | 1        | 5%      |
| Logitech BRIO Ultra HD Webcam                     | 1        | 5%      |
| Lenovo Integrated Camera                          | 1        | 5%      |
| Importek FJ Camera                                | 1        | 5%      |
| IMC Networks XHC Camera                           | 1        | 5%      |
| Genesys Logic Digital Microscope                  | 1        | 5%      |
| GEMBIRD USB2.0 PC CAMERA                          | 1        | 5%      |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 5%      |
| Chicony HP 2.0MP High Definition Webcam           | 1        | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 124      | 48.63%  |
| 0     | 85       | 33.33%  |
| 2     | 40       | 15.69%  |
| 3     | 4        | 1.57%   |
| 4     | 2        | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 152      | 73.79%  |
| Net/wireless             | 22       | 10.68%  |
| Sound                    | 17       | 8.25%   |
| Bluetooth                | 6        | 2.91%   |
| Net/ethernet             | 3        | 1.46%   |
| Card reader              | 3        | 1.46%   |
| Storage/raid             | 1        | 0.49%   |
| Network                  | 1        | 0.49%   |
| Dvb card                 | 1        | 0.49%   |

