BSD in Germany - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 2564

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [8227d6d32c](https://bsd-hardware.info/?probe=8227d6d32c) | Apr 30, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f86a94eb66](https://bsd-hardware.info/?probe=f86a94eb66) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [4ea8453453](https://bsd-hardware.info/?probe=4ea8453453) | Apr 30, 2023 |
| Protectli     | VP2420                      | Desktop     | [46a00b21d9](https://bsd-hardware.info/?probe=46a00b21d9) | Apr 30, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [38dc0b126e](https://bsd-hardware.info/?probe=38dc0b126e) | Apr 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ec520be044](https://bsd-hardware.info/?probe=ec520be044) | Apr 29, 2023 |
| Supermicro    | A2SDi-H-TF                  | Server      | [cae933d56e](https://bsd-hardware.info/?probe=cae933d56e) | Apr 29, 2023 |
| Protectli     | FW4B                        | Desktop     | [048da71e18](https://bsd-hardware.info/?probe=048da71e18) | Apr 29, 2023 |
| Sophos        | SG                          | Firewall    | [b0c4592563](https://bsd-hardware.info/?probe=b0c4592563) | Apr 29, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [9dc9ca0768](https://bsd-hardware.info/?probe=9dc9ca0768) | Apr 28, 2023 |
| PC Engines    | apu1                        | Desktop     | [1a37e9d978](https://bsd-hardware.info/?probe=1a37e9d978) | Apr 27, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [32afb6ef58](https://bsd-hardware.info/?probe=32afb6ef58) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [989f3b44bf](https://bsd-hardware.info/?probe=989f3b44bf) | Apr 26, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [94316d20c8](https://bsd-hardware.info/?probe=94316d20c8) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| MiTAC         | PH13CMI                     | Desktop     | [5d3e954049](https://bsd-hardware.info/?probe=5d3e954049) | Apr 24, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [c452485a00](https://bsd-hardware.info/?probe=c452485a00) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [0c8a0100c5](https://bsd-hardware.info/?probe=0c8a0100c5) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ad73cda832](https://bsd-hardware.info/?probe=ad73cda832) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [775424cbff](https://bsd-hardware.info/?probe=775424cbff) | Apr 22, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e9c239c897](https://bsd-hardware.info/?probe=e9c239c897) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [215364d870](https://bsd-hardware.info/?probe=215364d870) | Apr 21, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fdbbde509c](https://bsd-hardware.info/?probe=fdbbde509c) | Apr 20, 2023 |
| Sophos        | SG                          | Firewall    | [c05ad03e84](https://bsd-hardware.info/?probe=c05ad03e84) | Apr 19, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| PC Engines    | APU2                        | Desktop     | [59b3a3eebf](https://bsd-hardware.info/?probe=59b3a3eebf) | Apr 19, 2023 |
| Sophos        | UTM                         | Firewall    | [d45ac19cd1](https://bsd-hardware.info/?probe=d45ac19cd1) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [1cec8655b7](https://bsd-hardware.info/?probe=1cec8655b7) | Apr 19, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [92b99c6f08](https://bsd-hardware.info/?probe=92b99c6f08) | Apr 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [311e89be7a](https://bsd-hardware.info/?probe=311e89be7a) | Apr 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [b4fd4e35b2](https://bsd-hardware.info/?probe=b4fd4e35b2) | Apr 18, 2023 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [20fac0b7a5](https://bsd-hardware.info/?probe=20fac0b7a5) | Apr 18, 2023 |
| Sophos        | SG                          | Firewall    | [fa6f321ece](https://bsd-hardware.info/?probe=fa6f321ece) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f5153e1b18](https://bsd-hardware.info/?probe=f5153e1b18) | Apr 17, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6de7890035](https://bsd-hardware.info/?probe=6de7890035) | Apr 17, 2023 |
| Sophos        | SG                          | Firewall    | [4280767cdb](https://bsd-hardware.info/?probe=4280767cdb) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [56505e8956](https://bsd-hardware.info/?probe=56505e8956) | Apr 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [4fbc5291d9](https://bsd-hardware.info/?probe=4fbc5291d9) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a29966f9ee](https://bsd-hardware.info/?probe=a29966f9ee) | Apr 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [94151c41f1](https://bsd-hardware.info/?probe=94151c41f1) | Apr 14, 2023 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [627e7a86c6](https://bsd-hardware.info/?probe=627e7a86c6) | Apr 13, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [0c7855ee11](https://bsd-hardware.info/?probe=0c7855ee11) | Apr 13, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [e65290edd3](https://bsd-hardware.info/?probe=e65290edd3) | Apr 12, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [00c76c0db0](https://bsd-hardware.info/?probe=00c76c0db0) | Apr 12, 2023 |
| Advantech     | UNO-2271G_V2                | Desktop     | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [0b060edc48](https://bsd-hardware.info/?probe=0b060edc48) | Apr 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [9b1dbe0b9a](https://bsd-hardware.info/?probe=9b1dbe0b9a) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [cfa755bf6d](https://bsd-hardware.info/?probe=cfa755bf6d) | Apr 11, 2023 |
| Sophos        | SG                          | Firewall    | [3a2796626e](https://bsd-hardware.info/?probe=3a2796626e) | Apr 11, 2023 |
| CncTion       | N5105-4L-I226 B0            | Desktop     | [65d80d8aeb](https://bsd-hardware.info/?probe=65d80d8aeb) | Apr 09, 2023 |
| Gigabyte      | H610I DDR4                  | Desktop     | [59d65282c3](https://bsd-hardware.info/?probe=59d65282c3) | Apr 08, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [7a0ca560df](https://bsd-hardware.info/?probe=7a0ca560df) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [8fb3cbee23](https://bsd-hardware.info/?probe=8fb3cbee23) | Apr 07, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [f1cabdb067](https://bsd-hardware.info/?probe=f1cabdb067) | Apr 06, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b4dab62ac2](https://bsd-hardware.info/?probe=b4dab62ac2) | Apr 05, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24d7b97629](https://bsd-hardware.info/?probe=24d7b97629) | Apr 05, 2023 |
| Lanner        | FW-8771 C-GA                | Desktop     | [90d7028263](https://bsd-hardware.info/?probe=90d7028263) | Apr 05, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| PC Engines    | apu4                        | Desktop     | [e91a75d782](https://bsd-hardware.info/?probe=e91a75d782) | Apr 05, 2023 |
| Intel         | SKYBAY                      | Desktop     | [81655c4fd5](https://bsd-hardware.info/?probe=81655c4fd5) | Apr 05, 2023 |
| Sophos        | SG                          | Firewall    | [c2a2d9d6c9](https://bsd-hardware.info/?probe=c2a2d9d6c9) | Apr 04, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [7cf52a3977](https://bsd-hardware.info/?probe=7cf52a3977) | Apr 03, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [70a4d74b1a](https://bsd-hardware.info/?probe=70a4d74b1a) | Apr 03, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [828e914b59](https://bsd-hardware.info/?probe=828e914b59) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ca1360b939](https://bsd-hardware.info/?probe=ca1360b939) | Apr 03, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [bea5641594](https://bsd-hardware.info/?probe=bea5641594) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [6ef5047d5a](https://bsd-hardware.info/?probe=6ef5047d5a) | Apr 01, 2023 |
| Sophos        | SG                          | Firewall    | [de22e4dd72](https://bsd-hardware.info/?probe=de22e4dd72) | Apr 01, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [d7bb801369](https://bsd-hardware.info/?probe=d7bb801369) | Mar 31, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [60c66c5066](https://bsd-hardware.info/?probe=60c66c5066) | Mar 30, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a160027cc2](https://bsd-hardware.info/?probe=a160027cc2) | Mar 30, 2023 |
| Dell          | 0VG93V A00                  | Desktop     | [1f3e086401](https://bsd-hardware.info/?probe=1f3e086401) | Mar 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [3a5111c467](https://bsd-hardware.info/?probe=3a5111c467) | Mar 29, 2023 |
| Intel         | S2600GZ G29051-355          | Server      | [6bc00cde60](https://bsd-hardware.info/?probe=6bc00cde60) | Mar 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [07adf23a3d](https://bsd-hardware.info/?probe=07adf23a3d) | Mar 28, 2023 |
| Sophos        | SG                          | Firewall    | [b3346fe828](https://bsd-hardware.info/?probe=b3346fe828) | Mar 27, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [b6fd7cd6ae](https://bsd-hardware.info/?probe=b6fd7cd6ae) | Mar 27, 2023 |
| Shuttle       | FS81                        | Desktop     | [b80626e045](https://bsd-hardware.info/?probe=b80626e045) | Mar 26, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [3ed4cfc9c8](https://bsd-hardware.info/?probe=3ed4cfc9c8) | Mar 26, 2023 |
| Sophos        | UTM                         | Firewall    | [99af1f0a15](https://bsd-hardware.info/?probe=99af1f0a15) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [15e452d25d](https://bsd-hardware.info/?probe=15e452d25d) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2f16e29f78](https://bsd-hardware.info/?probe=2f16e29f78) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [fc5ab682fc](https://bsd-hardware.info/?probe=fc5ab682fc) | Mar 26, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5082d62025](https://bsd-hardware.info/?probe=5082d62025) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41fa3f51d3](https://bsd-hardware.info/?probe=41fa3f51d3) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [387c27f1d7](https://bsd-hardware.info/?probe=387c27f1d7) | Mar 25, 2023 |
| PC Engines    | APU2                        | Desktop     | [4e4a81e456](https://bsd-hardware.info/?probe=4e4a81e456) | Mar 24, 2023 |
| Lex           | Pineview-D                  | Desktop     | [ca2fbb614d](https://bsd-hardware.info/?probe=ca2fbb614d) | Mar 24, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [9561c72b9c](https://bsd-hardware.info/?probe=9561c72b9c) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [083d2e65da](https://bsd-hardware.info/?probe=083d2e65da) | Mar 24, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [18877701a6](https://bsd-hardware.info/?probe=18877701a6) | Mar 24, 2023 |
| HP            | 8103 A01                    | Mini pc     | [23f893285e](https://bsd-hardware.info/?probe=23f893285e) | Mar 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [f07553b02c](https://bsd-hardware.info/?probe=f07553b02c) | Mar 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [dfad78899e](https://bsd-hardware.info/?probe=dfad78899e) | Mar 23, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [720f15a1ce](https://bsd-hardware.info/?probe=720f15a1ce) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [491c0ca78a](https://bsd-hardware.info/?probe=491c0ca78a) | Mar 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [680002292e](https://bsd-hardware.info/?probe=680002292e) | Mar 22, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b3f0879ebf](https://bsd-hardware.info/?probe=b3f0879ebf) | Mar 22, 2023 |
| Intel         | SKYBAY                      | Desktop     | [83ea0b27b1](https://bsd-hardware.info/?probe=83ea0b27b1) | Mar 21, 2023 |
| Sophos        | SG                          | Firewall    | [4f818307ff](https://bsd-hardware.info/?probe=4f818307ff) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [7ae004c035](https://bsd-hardware.info/?probe=7ae004c035) | Mar 21, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5193764df7](https://bsd-hardware.info/?probe=5193764df7) | Mar 20, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Sophos        | SG                          | Firewall    | [e0ac090471](https://bsd-hardware.info/?probe=e0ac090471) | Mar 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4365dfa60](https://bsd-hardware.info/?probe=e4365dfa60) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7bd7f393b1](https://bsd-hardware.info/?probe=7bd7f393b1) | Mar 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e726d886c8](https://bsd-hardware.info/?probe=e726d886c8) | Mar 18, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a8f1d29e24](https://bsd-hardware.info/?probe=a8f1d29e24) | Mar 18, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a26d096ecb](https://bsd-hardware.info/?probe=a26d096ecb) | Mar 18, 2023 |
| ZOTAC         | ZBOX-ID91                   | Mini pc     | [4bbec4b82a](https://bsd-hardware.info/?probe=4bbec4b82a) | Mar 18, 2023 |
| Fujitsu       | D3313-S3 S26361-D3313-S3    | Desktop     | [1bf34a929a](https://bsd-hardware.info/?probe=1bf34a929a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [17516fffcf](https://bsd-hardware.info/?probe=17516fffcf) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| ASRock        | J5040-ITX                   | Desktop     | [435dc7ee7b](https://bsd-hardware.info/?probe=435dc7ee7b) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [68b45d5083](https://bsd-hardware.info/?probe=68b45d5083) | Mar 15, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [1ccc8081fd](https://bsd-hardware.info/?probe=1ccc8081fd) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| ASRock        | Q1900M                      | Desktop     | [9570525d52](https://bsd-hardware.info/?probe=9570525d52) | Mar 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5211185a2a](https://bsd-hardware.info/?probe=5211185a2a) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Sophos        | SG                          | Firewall    | [77db75effb](https://bsd-hardware.info/?probe=77db75effb) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [e1d2423153](https://bsd-hardware.info/?probe=e1d2423153) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [d89b45ea6d](https://bsd-hardware.info/?probe=d89b45ea6d) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fee0ff7804](https://bsd-hardware.info/?probe=fee0ff7804) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8736b12c9a](https://bsd-hardware.info/?probe=8736b12c9a) | Mar 11, 2023 |
| MSI           | X299 PRO                    | Desktop     | [0cebc094ca](https://bsd-hardware.info/?probe=0cebc094ca) | Mar 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a55137e71](https://bsd-hardware.info/?probe=2a55137e71) | Mar 10, 2023 |
| CheckPoint    | PH-30-00                    | Desktop     | [ec7a5f05fd](https://bsd-hardware.info/?probe=ec7a5f05fd) | Mar 09, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [2e616f1ad4](https://bsd-hardware.info/?probe=2e616f1ad4) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [d7b171d0bb](https://bsd-hardware.info/?probe=d7b171d0bb) | Mar 09, 2023 |
| Protectli     | VP2420                      | Desktop     | [21d2214da6](https://bsd-hardware.info/?probe=21d2214da6) | Mar 08, 2023 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Mini pc     | [3ad95b9444](https://bsd-hardware.info/?probe=3ad95b9444) | Mar 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [86c132c242](https://bsd-hardware.info/?probe=86c132c242) | Mar 07, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [b077e8e71a](https://bsd-hardware.info/?probe=b077e8e71a) | Mar 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b91b7cf52d](https://bsd-hardware.info/?probe=b91b7cf52d) | Mar 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [789ae683f7](https://bsd-hardware.info/?probe=789ae683f7) | Mar 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| Dell          | VEP-4600-V910 0PDG1JA02     | Desktop     | [5070c11c54](https://bsd-hardware.info/?probe=5070c11c54) | Mar 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3d912f92aa](https://bsd-hardware.info/?probe=3d912f92aa) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| HP            | 8158 A01                    | Mini pc     | [021f9a6e74](https://bsd-hardware.info/?probe=021f9a6e74) | Mar 04, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [5416a8e0b5](https://bsd-hardware.info/?probe=5416a8e0b5) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6067b3f58d](https://bsd-hardware.info/?probe=6067b3f58d) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bbbd05a4c3](https://bsd-hardware.info/?probe=bbbd05a4c3) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9ab07ae7f1](https://bsd-hardware.info/?probe=9ab07ae7f1) | Mar 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [228816d44e](https://bsd-hardware.info/?probe=228816d44e) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [81bf3cf726](https://bsd-hardware.info/?probe=81bf3cf726) | Mar 03, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [2b70fdb96a](https://bsd-hardware.info/?probe=2b70fdb96a) | Mar 02, 2023 |
| Sophos        | SG                          | Firewall    | [19b95b3238](https://bsd-hardware.info/?probe=19b95b3238) | Mar 01, 2023 |
| Sophos        | SG                          | Firewall    | [26cd20e559](https://bsd-hardware.info/?probe=26cd20e559) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [39d5f658ce](https://bsd-hardware.info/?probe=39d5f658ce) | Feb 28, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [dcf3f03ddc](https://bsd-hardware.info/?probe=dcf3f03ddc) | Feb 28, 2023 |
| Intel         | NUC7i3BNB J22859-307        | Mini pc     | [aca9e2885d](https://bsd-hardware.info/?probe=aca9e2885d) | Feb 28, 2023 |
| Supermicro    | PDSBM                       | Desktop     | [1dea83dd64](https://bsd-hardware.info/?probe=1dea83dd64) | Feb 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [27e756f63d](https://bsd-hardware.info/?probe=27e756f63d) | Feb 26, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [96a8673b26](https://bsd-hardware.info/?probe=96a8673b26) | Feb 26, 2023 |
| Sophos        | SG                          | Firewall    | [6f8d299ffb](https://bsd-hardware.info/?probe=6f8d299ffb) | Feb 26, 2023 |
| NF541         | 1.0                         | Desktop     | [863e6235d4](https://bsd-hardware.info/?probe=863e6235d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [33330ade31](https://bsd-hardware.info/?probe=33330ade31) | Feb 25, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [b774e80761](https://bsd-hardware.info/?probe=b774e80761) | Feb 25, 2023 |
| Sophos        | SG                          | Firewall    | [7e05fcaf2b](https://bsd-hardware.info/?probe=7e05fcaf2b) | Feb 25, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [54d8b7446b](https://bsd-hardware.info/?probe=54d8b7446b) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [87ad08a144](https://bsd-hardware.info/?probe=87ad08a144) | Feb 25, 2023 |
| Lenovo        | ThinkCentre M91p 7033A2G    | Desktop     | [25528a00f3](https://bsd-hardware.info/?probe=25528a00f3) | Feb 24, 2023 |
| MSI           | X299 PRO                    | Desktop     | [3ca12f88d9](https://bsd-hardware.info/?probe=3ca12f88d9) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [efab6dedba](https://bsd-hardware.info/?probe=efab6dedba) | Feb 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [ac2228fa2b](https://bsd-hardware.info/?probe=ac2228fa2b) | Feb 24, 2023 |
| Supermicro    | X10SBAA                     | Server      | [d22806833a](https://bsd-hardware.info/?probe=d22806833a) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Fujitsu       | D3543-A2 S26361-D3543-A2... | Desktop     | [68165a639f](https://bsd-hardware.info/?probe=68165a639f) | Feb 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [05966fb4dc](https://bsd-hardware.info/?probe=05966fb4dc) | Feb 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [541c13b778](https://bsd-hardware.info/?probe=541c13b778) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Intel         | QHSW02                      | Desktop     | [6bec4024a8](https://bsd-hardware.info/?probe=6bec4024a8) | Feb 22, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [3f78b1a6c7](https://bsd-hardware.info/?probe=3f78b1a6c7) | Feb 20, 2023 |
| Protectli     | VP2420                      | Desktop     | [5d8285d184](https://bsd-hardware.info/?probe=5d8285d184) | Feb 19, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [6d2c693305](https://bsd-hardware.info/?probe=6d2c693305) | Feb 19, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [8d1fa6606b](https://bsd-hardware.info/?probe=8d1fa6606b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [cffec30b6b](https://bsd-hardware.info/?probe=cffec30b6b) | Feb 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [1478bc453d](https://bsd-hardware.info/?probe=1478bc453d) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac4b0186ff](https://bsd-hardware.info/?probe=ac4b0186ff) | Feb 17, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [0adf0ca671](https://bsd-hardware.info/?probe=0adf0ca671) | Feb 17, 2023 |
| ASUSTek       | N3050M-E                    | Desktop     | [7d6e696fb4](https://bsd-hardware.info/?probe=7d6e696fb4) | Feb 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [71cc084a9c](https://bsd-hardware.info/?probe=71cc084a9c) | Feb 16, 2023 |
| PC Engines    | APU                         | Desktop     | [1162545537](https://bsd-hardware.info/?probe=1162545537) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [c7b82f8e59](https://bsd-hardware.info/?probe=c7b82f8e59) | Feb 14, 2023 |
| Intel         | S3420GP E51974-403          | Server      | [9d0765df2e](https://bsd-hardware.info/?probe=9d0765df2e) | Feb 14, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6a91635684](https://bsd-hardware.info/?probe=6a91635684) | Feb 14, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a9d6421d3c](https://bsd-hardware.info/?probe=a9d6421d3c) | Feb 14, 2023 |
| Yanling       | YL-CLU6L-V1                 | Desktop     | [9c12ee263f](https://bsd-hardware.info/?probe=9c12ee263f) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c258b4972c](https://bsd-hardware.info/?probe=c258b4972c) | Feb 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7080f05ef](https://bsd-hardware.info/?probe=d7080f05ef) | Feb 13, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [98819b1db5](https://bsd-hardware.info/?probe=98819b1db5) | Feb 13, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [cb4c316a05](https://bsd-hardware.info/?probe=cb4c316a05) | Feb 13, 2023 |
| Shuttle       | DS437T                      | Notebook    | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbe1c51575](https://bsd-hardware.info/?probe=dbe1c51575) | Feb 12, 2023 |
| IBM           | 00AL980                     | Server      | [80fa278909](https://bsd-hardware.info/?probe=80fa278909) | Feb 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [516c778d65](https://bsd-hardware.info/?probe=516c778d65) | Feb 11, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [2874f7a7fa](https://bsd-hardware.info/?probe=2874f7a7fa) | Feb 11, 2023 |
| Sophos        | UTM                         | Firewall    | [806a078730](https://bsd-hardware.info/?probe=806a078730) | Feb 11, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [6f8ad1a8b9](https://bsd-hardware.info/?probe=6f8ad1a8b9) | Feb 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c4c07aec07](https://bsd-hardware.info/?probe=c4c07aec07) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [18362d0f11](https://bsd-hardware.info/?probe=18362d0f11) | Feb 10, 2023 |
| Sophos        | SG                          | Firewall    | [643f5cb10f](https://bsd-hardware.info/?probe=643f5cb10f) | Feb 10, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [12e4e26e40](https://bsd-hardware.info/?probe=12e4e26e40) | Feb 10, 2023 |
| Foxconn       | 2A8Ch                       | Desktop     | [84c0208f8d](https://bsd-hardware.info/?probe=84c0208f8d) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | Notebook    | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [ef0a4a4744](https://bsd-hardware.info/?probe=ef0a4a4744) | Feb 10, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [c1b4617895](https://bsd-hardware.info/?probe=c1b4617895) | Feb 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [dd9685a909](https://bsd-hardware.info/?probe=dd9685a909) | Feb 09, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [4347c8c716](https://bsd-hardware.info/?probe=4347c8c716) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e5b2e1bb9d](https://bsd-hardware.info/?probe=e5b2e1bb9d) | Feb 09, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f66883c5c2](https://bsd-hardware.info/?probe=f66883c5c2) | Feb 09, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [78975e45b7](https://bsd-hardware.info/?probe=78975e45b7) | Feb 09, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [1a23b05eca](https://bsd-hardware.info/?probe=1a23b05eca) | Feb 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [f4978c3575](https://bsd-hardware.info/?probe=f4978c3575) | Feb 07, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [24b74b8ce3](https://bsd-hardware.info/?probe=24b74b8ce3) | Feb 07, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39fa7db109](https://bsd-hardware.info/?probe=39fa7db109) | Feb 07, 2023 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [923b6d85fd](https://bsd-hardware.info/?probe=923b6d85fd) | Feb 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [e4e00e259c](https://bsd-hardware.info/?probe=e4e00e259c) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ec37957aed](https://bsd-hardware.info/?probe=ec37957aed) | Feb 05, 2023 |
| Sophos        | SG                          | Firewall    | [0b353acc9f](https://bsd-hardware.info/?probe=0b353acc9f) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Intel         | QHSW02                      | Desktop     | [16722b7429](https://bsd-hardware.info/?probe=16722b7429) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [8fdace282e](https://bsd-hardware.info/?probe=8fdace282e) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | Notebook    | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e766835ab5](https://bsd-hardware.info/?probe=e766835ab5) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | P10S-M Series               | Desktop     | [c6fc0a639d](https://bsd-hardware.info/?probe=c6fc0a639d) | Feb 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [77c7c36f87](https://bsd-hardware.info/?probe=77c7c36f87) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | Notebook    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [b2784f4025](https://bsd-hardware.info/?probe=b2784f4025) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [433e29e7bd](https://bsd-hardware.info/?probe=433e29e7bd) | Feb 01, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [2d410c6882](https://bsd-hardware.info/?probe=2d410c6882) | Feb 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9fa25e53f1](https://bsd-hardware.info/?probe=9fa25e53f1) | Feb 01, 2023 |
| PC Engines    | apu4                        | Desktop     | [0d1561fea9](https://bsd-hardware.info/?probe=0d1561fea9) | Jan 31, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [418694e14d](https://bsd-hardware.info/?probe=418694e14d) | Jan 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6ed22671aa](https://bsd-hardware.info/?probe=6ed22671aa) | Jan 31, 2023 |
| Lanner        | FW-7543 B-GA                | Desktop     | [149345d14c](https://bsd-hardware.info/?probe=149345d14c) | Jan 30, 2023 |
| HP            | 1825                        | Desktop     | [717279c19f](https://bsd-hardware.info/?probe=717279c19f) | Jan 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4c25e80924](https://bsd-hardware.info/?probe=4c25e80924) | Jan 29, 2023 |
| Shenzhen M... | F4BHD                       | Desktop     | [b2540f3beb](https://bsd-hardware.info/?probe=b2540f3beb) | Jan 29, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8df824afd4](https://bsd-hardware.info/?probe=8df824afd4) | Jan 28, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [8fd7f80256](https://bsd-hardware.info/?probe=8fd7f80256) | Jan 28, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3797cbf278](https://bsd-hardware.info/?probe=3797cbf278) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| ZOTAC         | ZBOX-CI321NANO              | Mini pc     | [47bbed6ae7](https://bsd-hardware.info/?probe=47bbed6ae7) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [e93b47ed87](https://bsd-hardware.info/?probe=e93b47ed87) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [937a255571](https://bsd-hardware.info/?probe=937a255571) | Jan 28, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [a7fe868f42](https://bsd-hardware.info/?probe=a7fe868f42) | Jan 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [d3750005c2](https://bsd-hardware.info/?probe=d3750005c2) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [232a81d2ed](https://bsd-hardware.info/?probe=232a81d2ed) | Jan 27, 2023 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4ebeac2699](https://bsd-hardware.info/?probe=4ebeac2699) | Jan 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [436e596f40](https://bsd-hardware.info/?probe=436e596f40) | Jan 26, 2023 |
| Sophos        | SG                          | Firewall    | [f21b92f971](https://bsd-hardware.info/?probe=f21b92f971) | Jan 25, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8ba06cd5d3](https://bsd-hardware.info/?probe=8ba06cd5d3) | Jan 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3698389ce4](https://bsd-hardware.info/?probe=3698389ce4) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | Notebook    | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| AWOW          | AK50                        | Desktop     | [8c983f91e4](https://bsd-hardware.info/?probe=8c983f91e4) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | Notebook    | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| PC Engines    | APU2                        | Desktop     | [658569ae16](https://bsd-hardware.info/?probe=658569ae16) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| HP            | 1825                        | Desktop     | [2705218636](https://bsd-hardware.info/?probe=2705218636) | Jan 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [59c83cb9ee](https://bsd-hardware.info/?probe=59c83cb9ee) | Jan 21, 2023 |
| Fujitsu       | D3243-S1 S26361-D3243-S1    | Desktop     | [d69c3cae4c](https://bsd-hardware.info/?probe=d69c3cae4c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [e6873fe42f](https://bsd-hardware.info/?probe=e6873fe42f) | Jan 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [495563926c](https://bsd-hardware.info/?probe=495563926c) | Jan 21, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [f862df1689](https://bsd-hardware.info/?probe=f862df1689) | Jan 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4018ae0f3](https://bsd-hardware.info/?probe=d4018ae0f3) | Jan 20, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [4bcc8752f4](https://bsd-hardware.info/?probe=4bcc8752f4) | Jan 20, 2023 |
| Sophos        | SG                          | Firewall    | [324882f1d6](https://bsd-hardware.info/?probe=324882f1d6) | Jan 20, 2023 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [48206a7d4a](https://bsd-hardware.info/?probe=48206a7d4a) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [f10f04a5b1](https://bsd-hardware.info/?probe=f10f04a5b1) | Jan 19, 2023 |
| Sophos        | SG                          | Firewall    | [9275bbae4e](https://bsd-hardware.info/?probe=9275bbae4e) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [b9de543167](https://bsd-hardware.info/?probe=b9de543167) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [11948a0ab1](https://bsd-hardware.info/?probe=11948a0ab1) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Sophos        | UTM                         | Firewall    | [4b0eace553](https://bsd-hardware.info/?probe=4b0eace553) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [46178567ff](https://bsd-hardware.info/?probe=46178567ff) | Jan 18, 2023 |
| Wortmann      | terra MiniPC                | Desktop     | [be22193265](https://bsd-hardware.info/?probe=be22193265) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [8aa91d17fa](https://bsd-hardware.info/?probe=8aa91d17fa) | Jan 17, 2023 |
| MSI           | MS-9897                     | Desktop     | [0ccc361bd9](https://bsd-hardware.info/?probe=0ccc361bd9) | Jan 17, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1ef7026e21](https://bsd-hardware.info/?probe=1ef7026e21) | Jan 15, 2023 |
| Supermicro    | X11SCM-LN8F                 | Server      | [9e102da483](https://bsd-hardware.info/?probe=9e102da483) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8aebf3b22a](https://bsd-hardware.info/?probe=8aebf3b22a) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [17d73c4d40](https://bsd-hardware.info/?probe=17d73c4d40) | Jan 14, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ad7329411a](https://bsd-hardware.info/?probe=ad7329411a) | Jan 14, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [f8a84dbf0c](https://bsd-hardware.info/?probe=f8a84dbf0c) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [fba3e00878](https://bsd-hardware.info/?probe=fba3e00878) | Jan 13, 2023 |
| HP            | 82A1                        | Desktop     | [567894a0bb](https://bsd-hardware.info/?probe=567894a0bb) | Jan 12, 2023 |
| PC Engines    | APU3                        | Desktop     | [b080710198](https://bsd-hardware.info/?probe=b080710198) | Jan 12, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [56a5c0de6e](https://bsd-hardware.info/?probe=56a5c0de6e) | Jan 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [1e65573dfa](https://bsd-hardware.info/?probe=1e65573dfa) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e870cfc473](https://bsd-hardware.info/?probe=e870cfc473) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [55bd6297fa](https://bsd-hardware.info/?probe=55bd6297fa) | Jan 10, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [76ce0f8e69](https://bsd-hardware.info/?probe=76ce0f8e69) | Jan 09, 2023 |
| MSI           | X299 PRO                    | Desktop     | [a1f37f69d9](https://bsd-hardware.info/?probe=a1f37f69d9) | Jan 08, 2023 |
| Dell          | 03X6X0 A07                  | Server      | [dea6b95d26](https://bsd-hardware.info/?probe=dea6b95d26) | Jan 08, 2023 |
| Dell          | 0YNVJG A01                  | Desktop     | [8bb9472e6b](https://bsd-hardware.info/?probe=8bb9472e6b) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b5333020a](https://bsd-hardware.info/?probe=7b5333020a) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1e3ebde983](https://bsd-hardware.info/?probe=1e3ebde983) | Jan 07, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [e25da8b10a](https://bsd-hardware.info/?probe=e25da8b10a) | Jan 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fa12ea67eb](https://bsd-hardware.info/?probe=fa12ea67eb) | Jan 06, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [92c2e73bd4](https://bsd-hardware.info/?probe=92c2e73bd4) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [cc8588d977](https://bsd-hardware.info/?probe=cc8588d977) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39149acdbd](https://bsd-hardware.info/?probe=39149acdbd) | Jan 04, 2023 |
| Sophos        | SG                          | Firewall    | [4f105d12b8](https://bsd-hardware.info/?probe=4f105d12b8) | Jan 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [849af12174](https://bsd-hardware.info/?probe=849af12174) | Jan 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [70b1ca485d](https://bsd-hardware.info/?probe=70b1ca485d) | Jan 02, 2023 |
| ASRock        | E350M1                      | Desktop     | [6a7e5c8d0c](https://bsd-hardware.info/?probe=6a7e5c8d0c) | Jan 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [b3ac391a7e](https://bsd-hardware.info/?probe=b3ac391a7e) | Jan 01, 2023 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [d179977442](https://bsd-hardware.info/?probe=d179977442) | Jan 01, 2023 |
| HP            | 1825                        | Desktop     | [f7e94decd0](https://bsd-hardware.info/?probe=f7e94decd0) | Dec 31, 2022 |
| HP            | 1825                        | Desktop     | [afc1259508](https://bsd-hardware.info/?probe=afc1259508) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [16daca3076](https://bsd-hardware.info/?probe=16daca3076) | Dec 31, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [5967766127](https://bsd-hardware.info/?probe=5967766127) | Dec 30, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [cd3e4f7122](https://bsd-hardware.info/?probe=cd3e4f7122) | Dec 30, 2022 |
| Protectli     | FW4B                        | Desktop     | [406fe72c22](https://bsd-hardware.info/?probe=406fe72c22) | Dec 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [126bde2444](https://bsd-hardware.info/?probe=126bde2444) | Dec 30, 2022 |
| PC Engines    | APU2                        | Desktop     | [7aaf2d91ba](https://bsd-hardware.info/?probe=7aaf2d91ba) | Dec 29, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [6c145361a3](https://bsd-hardware.info/?probe=6c145361a3) | Dec 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b1e89901](https://bsd-hardware.info/?probe=d3b1e89901) | Dec 29, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [fa3c5f6504](https://bsd-hardware.info/?probe=fa3c5f6504) | Dec 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9954c0abee](https://bsd-hardware.info/?probe=9954c0abee) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [5b8ad02694](https://bsd-hardware.info/?probe=5b8ad02694) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c3b95220d7](https://bsd-hardware.info/?probe=c3b95220d7) | Dec 28, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [79d8b1477f](https://bsd-hardware.info/?probe=79d8b1477f) | Dec 28, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f2a248dcfe](https://bsd-hardware.info/?probe=f2a248dcfe) | Dec 26, 2022 |
| HP            | 8062                        | Desktop     | [f4d3eb024d](https://bsd-hardware.info/?probe=f4d3eb024d) | Dec 25, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d3d1107f77](https://bsd-hardware.info/?probe=d3d1107f77) | Dec 23, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [58b47341c9](https://bsd-hardware.info/?probe=58b47341c9) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [3a8d5c61b6](https://bsd-hardware.info/?probe=3a8d5c61b6) | Dec 23, 2022 |
| Unknown       | QD-WHLU01                   | Desktop     | [a0fb185069](https://bsd-hardware.info/?probe=a0fb185069) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [91a89db2ab](https://bsd-hardware.info/?probe=91a89db2ab) | Dec 23, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [bc2c536004](https://bsd-hardware.info/?probe=bc2c536004) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [58ca7ca7d4](https://bsd-hardware.info/?probe=58ca7ca7d4) | Dec 23, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [dfd3e7acb1](https://bsd-hardware.info/?probe=dfd3e7acb1) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [daaad6a386](https://bsd-hardware.info/?probe=daaad6a386) | Dec 23, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [67bc182d1d](https://bsd-hardware.info/?probe=67bc182d1d) | Dec 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [78bcccda01](https://bsd-hardware.info/?probe=78bcccda01) | Dec 22, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [01d8e43ee1](https://bsd-hardware.info/?probe=01d8e43ee1) | Dec 22, 2022 |
| AAEON         | FWS-2251 V1.0               | Desktop     | [a4ff0a7ec5](https://bsd-hardware.info/?probe=a4ff0a7ec5) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9e817a9114](https://bsd-hardware.info/?probe=9e817a9114) | Dec 22, 2022 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [90dfe8ee6b](https://bsd-hardware.info/?probe=90dfe8ee6b) | Dec 22, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2ac107df0f](https://bsd-hardware.info/?probe=2ac107df0f) | Dec 22, 2022 |
| AMI           | Cherry Trail CR             | Mini pc     | [cc9eb40ce1](https://bsd-hardware.info/?probe=cc9eb40ce1) | Dec 22, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [0c3fea5eb0](https://bsd-hardware.info/?probe=0c3fea5eb0) | Dec 22, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [16589e2878](https://bsd-hardware.info/?probe=16589e2878) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [2ea413db31](https://bsd-hardware.info/?probe=2ea413db31) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Sophos        | SG                          | Firewall    | [5536740301](https://bsd-hardware.info/?probe=5536740301) | Dec 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [3c36f8db41](https://bsd-hardware.info/?probe=3c36f8db41) | Dec 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [5d37a0669c](https://bsd-hardware.info/?probe=5d37a0669c) | Dec 19, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [67baacfc7d](https://bsd-hardware.info/?probe=67baacfc7d) | Dec 19, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c9de65beeb](https://bsd-hardware.info/?probe=c9de65beeb) | Dec 19, 2022 |
| PC Engines    | APU2                        | Desktop     | [5de84cb508](https://bsd-hardware.info/?probe=5de84cb508) | Dec 19, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [fc7928dfe9](https://bsd-hardware.info/?probe=fc7928dfe9) | Dec 18, 2022 |
| MSI           | X299 PRO                    | Desktop     | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [7981529337](https://bsd-hardware.info/?probe=7981529337) | Dec 17, 2022 |
| ASRock        | Q2900M                      | Desktop     | [42a53e5201](https://bsd-hardware.info/?probe=42a53e5201) | Dec 16, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa8c102cfd](https://bsd-hardware.info/?probe=fa8c102cfd) | Dec 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [3faaaa8209](https://bsd-hardware.info/?probe=3faaaa8209) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [01e26ec145](https://bsd-hardware.info/?probe=01e26ec145) | Dec 15, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [40911b66e2](https://bsd-hardware.info/?probe=40911b66e2) | Dec 15, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [649d525fdb](https://bsd-hardware.info/?probe=649d525fdb) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3508ce360](https://bsd-hardware.info/?probe=e3508ce360) | Dec 15, 2022 |
| Sophos        | SG                          | Firewall    | [16753b9090](https://bsd-hardware.info/?probe=16753b9090) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [35ecaf0406](https://bsd-hardware.info/?probe=35ecaf0406) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [9d71e35375](https://bsd-hardware.info/?probe=9d71e35375) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [98621b669c](https://bsd-hardware.info/?probe=98621b669c) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [b0639c3d01](https://bsd-hardware.info/?probe=b0639c3d01) | Dec 15, 2022 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [52fbc8ccf7](https://bsd-hardware.info/?probe=52fbc8ccf7) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [210418cc84](https://bsd-hardware.info/?probe=210418cc84) | Dec 15, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [cb16bb9431](https://bsd-hardware.info/?probe=cb16bb9431) | Dec 14, 2022 |
| NF541         | 1.0                         | Desktop     | [b0644bada6](https://bsd-hardware.info/?probe=b0644bada6) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec6827e543](https://bsd-hardware.info/?probe=ec6827e543) | Dec 13, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [af9df0d2c9](https://bsd-hardware.info/?probe=af9df0d2c9) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ee8d1082b](https://bsd-hardware.info/?probe=9ee8d1082b) | Dec 12, 2022 |
| Shuttle       | DH370                       | Desktop     | [1b938aa1a4](https://bsd-hardware.info/?probe=1b938aa1a4) | Dec 12, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [ba191bd994](https://bsd-hardware.info/?probe=ba191bd994) | Dec 12, 2022 |
| Sophos        | XG                          | Firewall    | [e35b3151a3](https://bsd-hardware.info/?probe=e35b3151a3) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [3124aaaf95](https://bsd-hardware.info/?probe=3124aaaf95) | Dec 11, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b1bd01549a](https://bsd-hardware.info/?probe=b1bd01549a) | Dec 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [def65f518e](https://bsd-hardware.info/?probe=def65f518e) | Dec 10, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [33395e819a](https://bsd-hardware.info/?probe=33395e819a) | Dec 10, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [cd6aa62212](https://bsd-hardware.info/?probe=cd6aa62212) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [493df1f529](https://bsd-hardware.info/?probe=493df1f529) | Dec 09, 2022 |
| PC Engines    | apu4                        | Desktop     | [3e3ab7f196](https://bsd-hardware.info/?probe=3e3ab7f196) | Dec 09, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [84f8198c18](https://bsd-hardware.info/?probe=84f8198c18) | Dec 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [24b9490c77](https://bsd-hardware.info/?probe=24b9490c77) | Dec 06, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [eaa3b9783e](https://bsd-hardware.info/?probe=eaa3b9783e) | Dec 05, 2022 |
| PC Engines    | apu4                        | Desktop     | [72061eb254](https://bsd-hardware.info/?probe=72061eb254) | Dec 05, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [aa9482884f](https://bsd-hardware.info/?probe=aa9482884f) | Dec 05, 2022 |
| Shuttle       | FS77U                       | Desktop     | [4172b79cfc](https://bsd-hardware.info/?probe=4172b79cfc) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [af4f0984ae](https://bsd-hardware.info/?probe=af4f0984ae) | Dec 04, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [1a183385c7](https://bsd-hardware.info/?probe=1a183385c7) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [d9113585f0](https://bsd-hardware.info/?probe=d9113585f0) | Dec 04, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [545a39b1e4](https://bsd-hardware.info/?probe=545a39b1e4) | Dec 02, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [6bec1ec37d](https://bsd-hardware.info/?probe=6bec1ec37d) | Dec 01, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a7c2e16f5c](https://bsd-hardware.info/?probe=a7c2e16f5c) | Dec 01, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [ac4f4b181a](https://bsd-hardware.info/?probe=ac4f4b181a) | Nov 30, 2022 |
| Intel         | D33217CK G76541-300         | Desktop     | [bbdd9a1b98](https://bsd-hardware.info/?probe=bbdd9a1b98) | Nov 30, 2022 |
| Sophos        | SG                          | Firewall    | [357c380b7c](https://bsd-hardware.info/?probe=357c380b7c) | Nov 29, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ae55a799e8](https://bsd-hardware.info/?probe=ae55a799e8) | Nov 28, 2022 |
| PC Engines    | apu6                        | Desktop     | [13dcbe5748](https://bsd-hardware.info/?probe=13dcbe5748) | Nov 27, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [a5514d3f4b](https://bsd-hardware.info/?probe=a5514d3f4b) | Nov 26, 2022 |
| Sophos        | SG                          | Firewall    | [d0fc510660](https://bsd-hardware.info/?probe=d0fc510660) | Nov 26, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1d71d3c9e7](https://bsd-hardware.info/?probe=1d71d3c9e7) | Nov 25, 2022 |
| Dell          | 0F0XJ6 A13                  | Server      | [1fb28aaef2](https://bsd-hardware.info/?probe=1fb28aaef2) | Nov 25, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [7bb8186465](https://bsd-hardware.info/?probe=7bb8186465) | Nov 25, 2022 |
| Dell          | Latitude D610               | Notebook    | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d4246caa0f](https://bsd-hardware.info/?probe=d4246caa0f) | Nov 24, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b6bbaa13e8](https://bsd-hardware.info/?probe=b6bbaa13e8) | Nov 24, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [1860d18e39](https://bsd-hardware.info/?probe=1860d18e39) | Nov 23, 2022 |
| PC Engines    | apu6                        | Desktop     | [bc334caa03](https://bsd-hardware.info/?probe=bc334caa03) | Nov 23, 2022 |
| Sophos        | UTM                         | Firewall    | [1c0805f9ae](https://bsd-hardware.info/?probe=1c0805f9ae) | Nov 23, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [b666129e73](https://bsd-hardware.info/?probe=b666129e73) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [298fde4e33](https://bsd-hardware.info/?probe=298fde4e33) | Nov 21, 2022 |
| HP            | ProLiant DL380 G6           | Server      | [3e3b056cdf](https://bsd-hardware.info/?probe=3e3b056cdf) | Nov 20, 2022 |
| Sophos        | XG                          | Firewall    | [3868856b34](https://bsd-hardware.info/?probe=3868856b34) | Nov 20, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [f6491f1950](https://bsd-hardware.info/?probe=f6491f1950) | Nov 20, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [15d32e1e36](https://bsd-hardware.info/?probe=15d32e1e36) | Nov 20, 2022 |
| Dell          | 060J9C A00                  | Mini pc     | [efcae22b58](https://bsd-hardware.info/?probe=efcae22b58) | Nov 19, 2022 |
| PC Engines    | apu6                        | Desktop     | [1e9acc3ae6](https://bsd-hardware.info/?probe=1e9acc3ae6) | Nov 18, 2022 |
| Fujitsu       | D3289-A1 S26361-D3289-A1... | Desktop     | [dae7027898](https://bsd-hardware.info/?probe=dae7027898) | Nov 18, 2022 |
| ASRock        | N3150M                      | Desktop     | [d3b3be7936](https://bsd-hardware.info/?probe=d3b3be7936) | Nov 17, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f1f56fe86c](https://bsd-hardware.info/?probe=f1f56fe86c) | Nov 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [64d8291a91](https://bsd-hardware.info/?probe=64d8291a91) | Nov 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [212f27d85a](https://bsd-hardware.info/?probe=212f27d85a) | Nov 17, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [f362b4c2ea](https://bsd-hardware.info/?probe=f362b4c2ea) | Nov 17, 2022 |
| MSI           | X299 PRO                    | Desktop     | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [753c68cfb9](https://bsd-hardware.info/?probe=753c68cfb9) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [589dec199e](https://bsd-hardware.info/?probe=589dec199e) | Nov 15, 2022 |
| Shuttle       | FH61V                       | Desktop     | [012a5c0fcc](https://bsd-hardware.info/?probe=012a5c0fcc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0079838512](https://bsd-hardware.info/?probe=0079838512) | Nov 13, 2022 |
| Sophos        | SG                          | Firewall    | [3d17d672bd](https://bsd-hardware.info/?probe=3d17d672bd) | Nov 13, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [ee16ad1ffb](https://bsd-hardware.info/?probe=ee16ad1ffb) | Nov 12, 2022 |
| PC Engines    | APU2                        | Desktop     | [34960ed27c](https://bsd-hardware.info/?probe=34960ed27c) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [cb88c3311a](https://bsd-hardware.info/?probe=cb88c3311a) | Nov 12, 2022 |
| Unknown       | Unknown                     | Firewall    | [2d2b5ee614](https://bsd-hardware.info/?probe=2d2b5ee614) | Nov 12, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [863c472910](https://bsd-hardware.info/?probe=863c472910) | Nov 12, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e3161d12c5](https://bsd-hardware.info/?probe=e3161d12c5) | Nov 11, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [0fcbc68304](https://bsd-hardware.info/?probe=0fcbc68304) | Nov 11, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [5a5e24fdf7](https://bsd-hardware.info/?probe=5a5e24fdf7) | Nov 11, 2022 |
| HP            | 18E9                        | Desktop     | [b9df70f7eb](https://bsd-hardware.info/?probe=b9df70f7eb) | Nov 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| CheckPoint    | PH-30-00                    | Desktop     | [e42768cd01](https://bsd-hardware.info/?probe=e42768cd01) | Nov 10, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [c741b2fbfa](https://bsd-hardware.info/?probe=c741b2fbfa) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [8addd09aa7](https://bsd-hardware.info/?probe=8addd09aa7) | Nov 09, 2022 |
| Sophos        | SG                          | Firewall    | [04b1bf9b24](https://bsd-hardware.info/?probe=04b1bf9b24) | Nov 09, 2022 |
| HP            | 1632                        | Desktop     | [96d60382b7](https://bsd-hardware.info/?probe=96d60382b7) | Nov 09, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Thomas-Kre... | P9A-I/2550/4L               | Firewall    | [d63fd6f7bd](https://bsd-hardware.info/?probe=d63fd6f7bd) | Nov 08, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c3eb1a6caf](https://bsd-hardware.info/?probe=c3eb1a6caf) | Nov 08, 2022 |
| HP            | ProLiant ML310e Gen8        | Desktop     | [cb5bb2c3b5](https://bsd-hardware.info/?probe=cb5bb2c3b5) | Nov 07, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Sophos        | SG                          | Firewall    | [4547062398](https://bsd-hardware.info/?probe=4547062398) | Nov 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [659ec0b365](https://bsd-hardware.info/?probe=659ec0b365) | Nov 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [2a913e7a43](https://bsd-hardware.info/?probe=2a913e7a43) | Nov 06, 2022 |
| Protectli     | VP2410                      | Desktop     | [de5de1ca21](https://bsd-hardware.info/?probe=de5de1ca21) | Nov 06, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [95d5580fd7](https://bsd-hardware.info/?probe=95d5580fd7) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [73230496b2](https://bsd-hardware.info/?probe=73230496b2) | Nov 04, 2022 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [1b27159e27](https://bsd-hardware.info/?probe=1b27159e27) | Nov 04, 2022 |
| Unknown       | 1.0                         | Desktop     | [9fe6ac4e68](https://bsd-hardware.info/?probe=9fe6ac4e68) | Nov 03, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [f0e3f3177a](https://bsd-hardware.info/?probe=f0e3f3177a) | Nov 02, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [09cb46f6bf](https://bsd-hardware.info/?probe=09cb46f6bf) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [6f21c02bba](https://bsd-hardware.info/?probe=6f21c02bba) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [9737a80a1c](https://bsd-hardware.info/?probe=9737a80a1c) | Oct 31, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a52d7dda08](https://bsd-hardware.info/?probe=a52d7dda08) | Oct 30, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [af6807035f](https://bsd-hardware.info/?probe=af6807035f) | Oct 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4aecc55dcc](https://bsd-hardware.info/?probe=4aecc55dcc) | Oct 30, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [0816f2da97](https://bsd-hardware.info/?probe=0816f2da97) | Oct 30, 2022 |
| Sophos        | SG                          | Firewall    | [03633cdc2e](https://bsd-hardware.info/?probe=03633cdc2e) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [85be4177d6](https://bsd-hardware.info/?probe=85be4177d6) | Oct 29, 2022 |
| Acer          | JM11-MS                     | Notebook    | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [484e5520b7](https://bsd-hardware.info/?probe=484e5520b7) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c483de83a9](https://bsd-hardware.info/?probe=c483de83a9) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c03e63a0a8](https://bsd-hardware.info/?probe=c03e63a0a8) | Oct 28, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [c5277ae3cd](https://bsd-hardware.info/?probe=c5277ae3cd) | Oct 27, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d2adcc8230](https://bsd-hardware.info/?probe=d2adcc8230) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| PC Engines    | apu1                        | Desktop     | [b8643f364d](https://bsd-hardware.info/?probe=b8643f364d) | Oct 25, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [0e2cd201d0](https://bsd-hardware.info/?probe=0e2cd201d0) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [0d6e868d9c](https://bsd-hardware.info/?probe=0d6e868d9c) | Oct 24, 2022 |
| Sophos        | SG                          | Firewall    | [bb50acf083](https://bsd-hardware.info/?probe=bb50acf083) | Oct 24, 2022 |
| ASUSTek       | P5BV-M                      | Desktop     | [f7bfa3deed](https://bsd-hardware.info/?probe=f7bfa3deed) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [6f0d5a7497](https://bsd-hardware.info/?probe=6f0d5a7497) | Oct 23, 2022 |
| Dell          | Latitude 5591               | Notebook    | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d7829c8f35](https://bsd-hardware.info/?probe=d7829c8f35) | Oct 22, 2022 |
| Alienware     | m15                         | Notebook    | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a1b0ef3b39](https://bsd-hardware.info/?probe=a1b0ef3b39) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Sophos        | UTM                         | Firewall    | [bae9180e3f](https://bsd-hardware.info/?probe=bae9180e3f) | Oct 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d04ef8c45b](https://bsd-hardware.info/?probe=d04ef8c45b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7ecffc1ca3](https://bsd-hardware.info/?probe=7ecffc1ca3) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [eb6eda641d](https://bsd-hardware.info/?probe=eb6eda641d) | Oct 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [304db9bbbf](https://bsd-hardware.info/?probe=304db9bbbf) | Oct 20, 2022 |
| Sophos        | SG                          | Firewall    | [a8593e1424](https://bsd-hardware.info/?probe=a8593e1424) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2e7b76bdf](https://bsd-hardware.info/?probe=c2e7b76bdf) | Oct 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ade8432e80](https://bsd-hardware.info/?probe=ade8432e80) | Oct 20, 2022 |
| Protectli     | FW6                         | Desktop     | [a7dabc97b0](https://bsd-hardware.info/?probe=a7dabc97b0) | Oct 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [0acd6e1143](https://bsd-hardware.info/?probe=0acd6e1143) | Oct 19, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [a6c8096599](https://bsd-hardware.info/?probe=a6c8096599) | Oct 19, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [8c6555d6be](https://bsd-hardware.info/?probe=8c6555d6be) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c7971db0b8](https://bsd-hardware.info/?probe=c7971db0b8) | Oct 18, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [7024873a21](https://bsd-hardware.info/?probe=7024873a21) | Oct 17, 2022 |
| NF541         | 1.0                         | Desktop     | [6f4f72398d](https://bsd-hardware.info/?probe=6f4f72398d) | Oct 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83ceb2fb33](https://bsd-hardware.info/?probe=83ceb2fb33) | Oct 15, 2022 |
| PC Engines    | apu4                        | Desktop     | [cefbafec73](https://bsd-hardware.info/?probe=cefbafec73) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [885bf4ef1e](https://bsd-hardware.info/?probe=885bf4ef1e) | Oct 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [a8bdbe4d1b](https://bsd-hardware.info/?probe=a8bdbe4d1b) | Oct 15, 2022 |
| Sophos        | SG                          | Firewall    | [4fbe0156a8](https://bsd-hardware.info/?probe=4fbe0156a8) | Oct 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a56504b92](https://bsd-hardware.info/?probe=5a56504b92) | Oct 15, 2022 |
| Sophos        | XG                          | Firewall    | [e80ccac6ff](https://bsd-hardware.info/?probe=e80ccac6ff) | Oct 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [27d7eb468e](https://bsd-hardware.info/?probe=27d7eb468e) | Oct 14, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5acdcd628d](https://bsd-hardware.info/?probe=5acdcd628d) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [0e09ac984a](https://bsd-hardware.info/?probe=0e09ac984a) | Oct 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [a06a344954](https://bsd-hardware.info/?probe=a06a344954) | Oct 12, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [869687f6f0](https://bsd-hardware.info/?probe=869687f6f0) | Oct 11, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [f4b5bf9026](https://bsd-hardware.info/?probe=f4b5bf9026) | Oct 11, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [53c643dc95](https://bsd-hardware.info/?probe=53c643dc95) | Oct 10, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [5d929362ca](https://bsd-hardware.info/?probe=5d929362ca) | Oct 09, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [73c9bfe38b](https://bsd-hardware.info/?probe=73c9bfe38b) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [99c0387102](https://bsd-hardware.info/?probe=99c0387102) | Oct 09, 2022 |
| HP            | 84F5                        | Mini pc     | [ecdab22807](https://bsd-hardware.info/?probe=ecdab22807) | Oct 08, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d6396a74dd](https://bsd-hardware.info/?probe=d6396a74dd) | Oct 08, 2022 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [231a0f9ce0](https://bsd-hardware.info/?probe=231a0f9ce0) | Oct 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [d25832111e](https://bsd-hardware.info/?probe=d25832111e) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [a34c1b8ccd](https://bsd-hardware.info/?probe=a34c1b8ccd) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [7658e5e20d](https://bsd-hardware.info/?probe=7658e5e20d) | Oct 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [02416f3157](https://bsd-hardware.info/?probe=02416f3157) | Oct 06, 2022 |
| CncTion       | J4125-4L-I225               | Desktop     | [eb746dc4a1](https://bsd-hardware.info/?probe=eb746dc4a1) | Oct 05, 2022 |
| Sophos        | SG                          | Firewall    | [44ca915943](https://bsd-hardware.info/?probe=44ca915943) | Oct 05, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [724c70cfa3](https://bsd-hardware.info/?probe=724c70cfa3) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Neousys Te... | NVS-5000 Rev. A3            | Server      | [49d9f0e06a](https://bsd-hardware.info/?probe=49d9f0e06a) | Oct 04, 2022 |
| Sophos        | XG                          | Firewall    | [4b62b03461](https://bsd-hardware.info/?probe=4b62b03461) | Oct 03, 2022 |
| Protectli     | FW4B                        | Desktop     | [36c62d7ffe](https://bsd-hardware.info/?probe=36c62d7ffe) | Oct 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [dac9b93a46](https://bsd-hardware.info/?probe=dac9b93a46) | Oct 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [bb4a59dd43](https://bsd-hardware.info/?probe=bb4a59dd43) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [23450789e4](https://bsd-hardware.info/?probe=23450789e4) | Oct 01, 2022 |
| AMI           | PICO PC                     | Desktop     | [ab45092607](https://bsd-hardware.info/?probe=ab45092607) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4e771c07c](https://bsd-hardware.info/?probe=c4e771c07c) | Oct 01, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [0cb7bacc88](https://bsd-hardware.info/?probe=0cb7bacc88) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [eb0e449150](https://bsd-hardware.info/?probe=eb0e449150) | Sep 29, 2022 |
| Tactus        | GeoFlex 110                 | Notebook    | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Sophos        | SG                          | Firewall    | [6511e9620b](https://bsd-hardware.info/?probe=6511e9620b) | Sep 28, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [8936497eed](https://bsd-hardware.info/?probe=8936497eed) | Sep 27, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [a605b4582c](https://bsd-hardware.info/?probe=a605b4582c) | Sep 27, 2022 |
| Sophos        | SG                          | Firewall    | [fdd950a5e8](https://bsd-hardware.info/?probe=fdd950a5e8) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| CncTion       | Jasper-4L B0                | Desktop     | [2998faa879](https://bsd-hardware.info/?probe=2998faa879) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [6e2d053e1c](https://bsd-hardware.info/?probe=6e2d053e1c) | Sep 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8ed018c141](https://bsd-hardware.info/?probe=8ed018c141) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a0672c6af1](https://bsd-hardware.info/?probe=a0672c6af1) | Sep 23, 2022 |
| Sophos        | UTM                         | Firewall    | [fe6cf3c1ab](https://bsd-hardware.info/?probe=fe6cf3c1ab) | Sep 22, 2022 |
| ZOTAC         | ZBOX-MI522NANO/MI542NANO    | Mini pc     | [495b0dfebd](https://bsd-hardware.info/?probe=495b0dfebd) | Sep 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [036004bbfe](https://bsd-hardware.info/?probe=036004bbfe) | Sep 22, 2022 |
| PC Engines    | APU                         | Desktop     | [a65b17ba04](https://bsd-hardware.info/?probe=a65b17ba04) | Sep 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [37acdfe51c](https://bsd-hardware.info/?probe=37acdfe51c) | Sep 20, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [3c74fc1690](https://bsd-hardware.info/?probe=3c74fc1690) | Sep 20, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [c057b7ab09](https://bsd-hardware.info/?probe=c057b7ab09) | Sep 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [80e1559386](https://bsd-hardware.info/?probe=80e1559386) | Sep 19, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [393da0c00c](https://bsd-hardware.info/?probe=393da0c00c) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a2f56848a9](https://bsd-hardware.info/?probe=a2f56848a9) | Sep 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cad2b5fd02](https://bsd-hardware.info/?probe=cad2b5fd02) | Sep 18, 2022 |
| Sophos        | XG                          | Firewall    | [e8aca06194](https://bsd-hardware.info/?probe=e8aca06194) | Sep 18, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [d027a503a5](https://bsd-hardware.info/?probe=d027a503a5) | Sep 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [55c82d4dd0](https://bsd-hardware.info/?probe=55c82d4dd0) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [af8f180c2c](https://bsd-hardware.info/?probe=af8f180c2c) | Sep 17, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a9da12dec0](https://bsd-hardware.info/?probe=a9da12dec0) | Sep 17, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [9fc1f66fcc](https://bsd-hardware.info/?probe=9fc1f66fcc) | Sep 16, 2022 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [eb09d789de](https://bsd-hardware.info/?probe=eb09d789de) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [3b66741f97](https://bsd-hardware.info/?probe=3b66741f97) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [5361453e6a](https://bsd-hardware.info/?probe=5361453e6a) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | Notebook    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e8848edf41](https://bsd-hardware.info/?probe=e8848edf41) | Sep 13, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [d3ee67f09b](https://bsd-hardware.info/?probe=d3ee67f09b) | Sep 13, 2022 |
| HP            | 18E7                        | Desktop     | [f09635a7ee](https://bsd-hardware.info/?probe=f09635a7ee) | Sep 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [66e543ee47](https://bsd-hardware.info/?probe=66e543ee47) | Sep 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [2b4e2212dc](https://bsd-hardware.info/?probe=2b4e2212dc) | Sep 12, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [71e53af7f9](https://bsd-hardware.info/?probe=71e53af7f9) | Sep 12, 2022 |
| HP            | ProLiant DL20 Gen9          | Server      | [32e9f95095](https://bsd-hardware.info/?probe=32e9f95095) | Sep 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [37588a8565](https://bsd-hardware.info/?probe=37588a8565) | Sep 11, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [836927cf63](https://bsd-hardware.info/?probe=836927cf63) | Sep 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8eb8bf52d4](https://bsd-hardware.info/?probe=8eb8bf52d4) | Sep 10, 2022 |
| Sophos        | SG                          | Firewall    | [0213c8bb69](https://bsd-hardware.info/?probe=0213c8bb69) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [3c2b784001](https://bsd-hardware.info/?probe=3c2b784001) | Sep 09, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [581219cbc5](https://bsd-hardware.info/?probe=581219cbc5) | Sep 09, 2022 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [c25d3df4e2](https://bsd-hardware.info/?probe=c25d3df4e2) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6130d9c1d0](https://bsd-hardware.info/?probe=6130d9c1d0) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1d81b77310](https://bsd-hardware.info/?probe=1d81b77310) | Sep 07, 2022 |
| Intel         | SYS-2USM03-6M01E            | Desktop     | [d4f98f18b9](https://bsd-hardware.info/?probe=d4f98f18b9) | Sep 07, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b803a767af](https://bsd-hardware.info/?probe=b803a767af) | Sep 06, 2022 |
| Sophos        | SG                          | Firewall    | [4b393a08cd](https://bsd-hardware.info/?probe=4b393a08cd) | Sep 06, 2022 |
| CncTion       | N5105-4L                    | Desktop     | [2a34dc3fe0](https://bsd-hardware.info/?probe=2a34dc3fe0) | Sep 05, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [734a8e61c4](https://bsd-hardware.info/?probe=734a8e61c4) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c1967c7cf8](https://bsd-hardware.info/?probe=c1967c7cf8) | Sep 04, 2022 |
| CompuLab      | fitlet                      | Mini pc     | [9772776314](https://bsd-hardware.info/?probe=9772776314) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [72cdc4123c](https://bsd-hardware.info/?probe=72cdc4123c) | Sep 03, 2022 |
| Lenovo        | ThinkCentre M70e 0833A29    | Desktop     | [b7c5b9a51d](https://bsd-hardware.info/?probe=b7c5b9a51d) | Sep 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [1e05b51bf1](https://bsd-hardware.info/?probe=1e05b51bf1) | Sep 02, 2022 |
| Intel         | QHSW02                      | Desktop     | [b0ad128162](https://bsd-hardware.info/?probe=b0ad128162) | Sep 02, 2022 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [43a7b45df6](https://bsd-hardware.info/?probe=43a7b45df6) | Sep 01, 2022 |
| CompuLab      | fitlet2                     | Mini pc     | [ebedb51d2f](https://bsd-hardware.info/?probe=ebedb51d2f) | Aug 31, 2022 |
| Dell          | 0G261D A00                  | Desktop     | [c77b23d1a7](https://bsd-hardware.info/?probe=c77b23d1a7) | Aug 31, 2022 |
| Intel         | DENLOW_WS                   | Desktop     | [067a217959](https://bsd-hardware.info/?probe=067a217959) | Aug 30, 2022 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [df3df2855b](https://bsd-hardware.info/?probe=df3df2855b) | Aug 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [0f1eabf01e](https://bsd-hardware.info/?probe=0f1eabf01e) | Aug 27, 2022 |
| Intel         | QHSW02                      | Desktop     | [184a8697e9](https://bsd-hardware.info/?probe=184a8697e9) | Aug 27, 2022 |
| Intel         | QHSW02                      | Desktop     | [1765bd0426](https://bsd-hardware.info/?probe=1765bd0426) | Aug 27, 2022 |
| Sophos        | SG                          | Firewall    | [2d90401126](https://bsd-hardware.info/?probe=2d90401126) | Aug 26, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [10ca365b40](https://bsd-hardware.info/?probe=10ca365b40) | Aug 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [3465c46b7d](https://bsd-hardware.info/?probe=3465c46b7d) | Aug 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [97da53ff14](https://bsd-hardware.info/?probe=97da53ff14) | Aug 25, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [a760a87c5d](https://bsd-hardware.info/?probe=a760a87c5d) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [8ca6b71124](https://bsd-hardware.info/?probe=8ca6b71124) | Aug 22, 2022 |
| Deciso        | Netboard A20                | Notebook    | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| HP            | 82B4                        | Desktop     | [5e07fc9831](https://bsd-hardware.info/?probe=5e07fc9831) | Aug 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [7d059d1d0a](https://bsd-hardware.info/?probe=7d059d1d0a) | Aug 22, 2022 |
| Supermicro    | X10SBA-LA                   | Server      | [5a733d841d](https://bsd-hardware.info/?probe=5a733d841d) | Aug 22, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [b32f197fe9](https://bsd-hardware.info/?probe=b32f197fe9) | Aug 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [92bff81bb5](https://bsd-hardware.info/?probe=92bff81bb5) | Aug 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [ccdff6fbea](https://bsd-hardware.info/?probe=ccdff6fbea) | Aug 20, 2022 |
| Supermicro    | X12STL-IF                   | Server      | [295fc511a6](https://bsd-hardware.info/?probe=295fc511a6) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | Notebook    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [1a666e04d4](https://bsd-hardware.info/?probe=1a666e04d4) | Aug 19, 2022 |
| Protectli     | FW4B                        | Desktop     | [8eb0c6ffbe](https://bsd-hardware.info/?probe=8eb0c6ffbe) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb02323793](https://bsd-hardware.info/?probe=fb02323793) | Aug 19, 2022 |
| Inventec      | Z CLASS A02                 | Desktop     | [290a94a907](https://bsd-hardware.info/?probe=290a94a907) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Sophos        | SG                          | Firewall    | [bed863a141](https://bsd-hardware.info/?probe=bed863a141) | Aug 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [2c0bb11a7b](https://bsd-hardware.info/?probe=2c0bb11a7b) | Aug 17, 2022 |
| Sophos        | UTM                         | Firewall    | [b70e2c4189](https://bsd-hardware.info/?probe=b70e2c4189) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e67200aee1](https://bsd-hardware.info/?probe=e67200aee1) | Aug 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef2a61855a](https://bsd-hardware.info/?probe=ef2a61855a) | Aug 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [e23ed854ed](https://bsd-hardware.info/?probe=e23ed854ed) | Aug 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [70ae301a10](https://bsd-hardware.info/?probe=70ae301a10) | Aug 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [90612a700d](https://bsd-hardware.info/?probe=90612a700d) | Aug 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9267873961](https://bsd-hardware.info/?probe=9267873961) | Aug 13, 2022 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [6e7e782b00](https://bsd-hardware.info/?probe=6e7e782b00) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [3d46e0eace](https://bsd-hardware.info/?probe=3d46e0eace) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [c961cea235](https://bsd-hardware.info/?probe=c961cea235) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| Dell          | 012KND A00                  | Mini pc     | [557cf9cb1b](https://bsd-hardware.info/?probe=557cf9cb1b) | Aug 12, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [5ceace59c1](https://bsd-hardware.info/?probe=5ceace59c1) | Aug 12, 2022 |
| Sophos        | SG                          | Firewall    | [96d3e064b2](https://bsd-hardware.info/?probe=96d3e064b2) | Aug 12, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [d06e05c67a](https://bsd-hardware.info/?probe=d06e05c67a) | Aug 12, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [3de3724488](https://bsd-hardware.info/?probe=3de3724488) | Aug 12, 2022 |
| HP            | 82B4                        | Desktop     | [d3fd85a7b6](https://bsd-hardware.info/?probe=d3fd85a7b6) | Aug 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fe8deedda3](https://bsd-hardware.info/?probe=fe8deedda3) | Aug 11, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d3f51a01b1](https://bsd-hardware.info/?probe=d3f51a01b1) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [80e867e04c](https://bsd-hardware.info/?probe=80e867e04c) | Aug 10, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [afca16a0bd](https://bsd-hardware.info/?probe=afca16a0bd) | Aug 09, 2022 |
| NF541         | 1.0                         | Desktop     | [dcde0e7a44](https://bsd-hardware.info/?probe=dcde0e7a44) | Aug 09, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| ASUSTek       | F6A                         | Notebook    | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | 8103 A01                    | Mini pc     | [720f185f7b](https://bsd-hardware.info/?probe=720f185f7b) | Aug 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [64768cfe88](https://bsd-hardware.info/?probe=64768cfe88) | Aug 07, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [75ffbbae85](https://bsd-hardware.info/?probe=75ffbbae85) | Aug 07, 2022 |
| HP            | 18E4                        | Desktop     | [7408fe969c](https://bsd-hardware.info/?probe=7408fe969c) | Aug 07, 2022 |
| HP            | 213D A01                    | Desktop     | [383712cf94](https://bsd-hardware.info/?probe=383712cf94) | Aug 06, 2022 |
| HP            | 213D A01                    | Desktop     | [e28886f86e](https://bsd-hardware.info/?probe=e28886f86e) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [9e69d3a39f](https://bsd-hardware.info/?probe=9e69d3a39f) | Aug 06, 2022 |
| BESSTAR Te... | TH50                        | Desktop     | [e68fb8c88e](https://bsd-hardware.info/?probe=e68fb8c88e) | Aug 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b36e9a7b2e](https://bsd-hardware.info/?probe=b36e9a7b2e) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [ae62a89080](https://bsd-hardware.info/?probe=ae62a89080) | Aug 05, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [69214b0c79](https://bsd-hardware.info/?probe=69214b0c79) | Aug 04, 2022 |
| PC Engines    | apu4                        | Desktop     | [2ae838d489](https://bsd-hardware.info/?probe=2ae838d489) | Aug 02, 2022 |
| Supermicro    | X10SDV-TP8F                 | Server      | [0b2d0398cd](https://bsd-hardware.info/?probe=0b2d0398cd) | Aug 01, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f2590dea4b](https://bsd-hardware.info/?probe=f2590dea4b) | Aug 01, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [d50ffab1cc](https://bsd-hardware.info/?probe=d50ffab1cc) | Aug 01, 2022 |
| ASUSTek       | P5W64 WS Pro                | Desktop     | [f05a901a30](https://bsd-hardware.info/?probe=f05a901a30) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f891511390](https://bsd-hardware.info/?probe=f891511390) | Jul 30, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [0d0b0c3f9e](https://bsd-hardware.info/?probe=0d0b0c3f9e) | Jul 29, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6cac72ef69](https://bsd-hardware.info/?probe=6cac72ef69) | Jul 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7cc4f8754f](https://bsd-hardware.info/?probe=7cc4f8754f) | Jul 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fa1e69b519](https://bsd-hardware.info/?probe=fa1e69b519) | Jul 27, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [91165a8899](https://bsd-hardware.info/?probe=91165a8899) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9df3c644b9](https://bsd-hardware.info/?probe=9df3c644b9) | Jul 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [fd67eb14ae](https://bsd-hardware.info/?probe=fd67eb14ae) | Jul 26, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [2f701b55fc](https://bsd-hardware.info/?probe=2f701b55fc) | Jul 25, 2022 |
| Sophos        | SG                          | Firewall    | [8e461fa0e9](https://bsd-hardware.info/?probe=8e461fa0e9) | Jul 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [8830b5ba19](https://bsd-hardware.info/?probe=8830b5ba19) | Jul 24, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [37ce098399](https://bsd-hardware.info/?probe=37ce098399) | Jul 23, 2022 |
| Sophos        | UTM                         | Firewall    | [4ba42eb6db](https://bsd-hardware.info/?probe=4ba42eb6db) | Jul 23, 2022 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [df31840a7e](https://bsd-hardware.info/?probe=df31840a7e) | Jul 22, 2022 |
| Intel         | QHSW02                      | Desktop     | [8f910e599b](https://bsd-hardware.info/?probe=8f910e599b) | Jul 21, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [48854ed05e](https://bsd-hardware.info/?probe=48854ed05e) | Jul 21, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [1b6748d4f7](https://bsd-hardware.info/?probe=1b6748d4f7) | Jul 19, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [4b0bdf58dd](https://bsd-hardware.info/?probe=4b0bdf58dd) | Jul 18, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Supermicro    | A2SAP-HA                    | Desktop     | [27c6228555](https://bsd-hardware.info/?probe=27c6228555) | Jul 17, 2022 |
| YANYU         | H87SL VER:1.3               | Desktop     | [fda62409ee](https://bsd-hardware.info/?probe=fda62409ee) | Jul 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| PC Engines    | APU3                        | Desktop     | [2b20f47024](https://bsd-hardware.info/?probe=2b20f47024) | Jul 15, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [747bebe8d4](https://bsd-hardware.info/?probe=747bebe8d4) | Jul 14, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [2a52f27ffe](https://bsd-hardware.info/?probe=2a52f27ffe) | Jul 13, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [be86d81d29](https://bsd-hardware.info/?probe=be86d81d29) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| ASRock        | Z97 Professional            | Desktop     | [c1c177fbb0](https://bsd-hardware.info/?probe=c1c177fbb0) | Jul 12, 2022 |
| HP            | 1790                        | Desktop     | [bc5988d764](https://bsd-hardware.info/?probe=bc5988d764) | Jul 11, 2022 |
| NF541         | 1.0                         | Desktop     | [00cab93f40](https://bsd-hardware.info/?probe=00cab93f40) | Jul 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e42f50fe0f](https://bsd-hardware.info/?probe=e42f50fe0f) | Jul 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [b0380fb22c](https://bsd-hardware.info/?probe=b0380fb22c) | Jul 09, 2022 |
| Supermicro    | X11SCH-F                    | Server      | [1ad1a2496b](https://bsd-hardware.info/?probe=1ad1a2496b) | Jul 08, 2022 |
| Intel         | QHSW02                      | Desktop     | [e7d923f138](https://bsd-hardware.info/?probe=e7d923f138) | Jul 07, 2022 |
| Shuttle       | DS437                       | Notebook    | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | Notebook    | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Supermicro    | X11SCH-LN4F                 | Server      | [db74ee9bf8](https://bsd-hardware.info/?probe=db74ee9bf8) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [71efa2b0b9](https://bsd-hardware.info/?probe=71efa2b0b9) | Jul 06, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [342ef61cdc](https://bsd-hardware.info/?probe=342ef61cdc) | Jul 05, 2022 |
| NF541S        | 1.0                         | Desktop     | [937fe3af39](https://bsd-hardware.info/?probe=937fe3af39) | Jul 04, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [c8a69b3805](https://bsd-hardware.info/?probe=c8a69b3805) | Jul 04, 2022 |
| Sophos        | SG                          | Firewall    | [d293fb6146](https://bsd-hardware.info/?probe=d293fb6146) | Jul 03, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Sophos        | SG                          | Firewall    | [13a5a5972e](https://bsd-hardware.info/?probe=13a5a5972e) | Jul 03, 2022 |
| ASRock        | H310CM-DVS                  | Desktop     | [907e22dbb6](https://bsd-hardware.info/?probe=907e22dbb6) | Jul 03, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [40c8fdfafa](https://bsd-hardware.info/?probe=40c8fdfafa) | Jul 02, 2022 |
| HP            | 213D A01                    | Desktop     | [21af8c270f](https://bsd-hardware.info/?probe=21af8c270f) | Jul 01, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [adaa197bf6](https://bsd-hardware.info/?probe=adaa197bf6) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [35f24d802a](https://bsd-hardware.info/?probe=35f24d802a) | Jun 30, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8f496791d](https://bsd-hardware.info/?probe=e8f496791d) | Jun 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [8e6519f26f](https://bsd-hardware.info/?probe=8e6519f26f) | Jun 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [85c0c08d91](https://bsd-hardware.info/?probe=85c0c08d91) | Jun 29, 2022 |
| ASRock        | N3700M                      | Desktop     | [3896fd5bc2](https://bsd-hardware.info/?probe=3896fd5bc2) | Jun 29, 2022 |
| Intel         | QHSW02                      | Desktop     | [28928d9ad4](https://bsd-hardware.info/?probe=28928d9ad4) | Jun 28, 2022 |
| Intel         | S5500BC E25124-452          | Server      | [801632fa6f](https://bsd-hardware.info/?probe=801632fa6f) | Jun 27, 2022 |
| Supermicro    | X10SBAA                     | Server      | [588a497894](https://bsd-hardware.info/?probe=588a497894) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7fcdb93a4b](https://bsd-hardware.info/?probe=7fcdb93a4b) | Jun 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [8ab4302d97](https://bsd-hardware.info/?probe=8ab4302d97) | Jun 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c15c394b7](https://bsd-hardware.info/?probe=3c15c394b7) | Jun 26, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a8b0c828f8](https://bsd-hardware.info/?probe=a8b0c828f8) | Jun 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [3e4fbe09f1](https://bsd-hardware.info/?probe=3e4fbe09f1) | Jun 26, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [ce4dc5e6ab](https://bsd-hardware.info/?probe=ce4dc5e6ab) | Jun 25, 2022 |
| MSI           | MS-B120                     | Mini pc     | [aa27c1dfd0](https://bsd-hardware.info/?probe=aa27c1dfd0) | Jun 25, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [9419973ba0](https://bsd-hardware.info/?probe=9419973ba0) | Jun 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ab15560f42](https://bsd-hardware.info/?probe=ab15560f42) | Jun 25, 2022 |
| Dell          | 04JN2K A09                  | Server      | [ff8f57ee67](https://bsd-hardware.info/?probe=ff8f57ee67) | Jun 25, 2022 |
| Dell          | 0H5N7P A02                  | Server      | [7713da37a9](https://bsd-hardware.info/?probe=7713da37a9) | Jun 25, 2022 |
| Sophos        | SG                          | Firewall    | [532927ba49](https://bsd-hardware.info/?probe=532927ba49) | Jun 24, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6c72a0dca7](https://bsd-hardware.info/?probe=6c72a0dca7) | Jun 24, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [bfcc8f1f66](https://bsd-hardware.info/?probe=bfcc8f1f66) | Jun 24, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [af1a9cf253](https://bsd-hardware.info/?probe=af1a9cf253) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [18f9e5bf9c](https://bsd-hardware.info/?probe=18f9e5bf9c) | Jun 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [de9163945f](https://bsd-hardware.info/?probe=de9163945f) | Jun 23, 2022 |
| Supermicro    | X11SSH-LN4F                 | Server      | [e8f3acf486](https://bsd-hardware.info/?probe=e8f3acf486) | Jun 23, 2022 |
| PC Engines    | apu4                        | Desktop     | [d7e6f088d0](https://bsd-hardware.info/?probe=d7e6f088d0) | Jun 22, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [72860a723c](https://bsd-hardware.info/?probe=72860a723c) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [62a2455a8b](https://bsd-hardware.info/?probe=62a2455a8b) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [fb1ffe9c0d](https://bsd-hardware.info/?probe=fb1ffe9c0d) | Jun 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [24b47422c7](https://bsd-hardware.info/?probe=24b47422c7) | Jun 22, 2022 |
| MSI           | B85M-E45                    | Desktop     | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| ASUSTek       | H110T                       | Desktop     | [a4a51d110b](https://bsd-hardware.info/?probe=a4a51d110b) | Jun 20, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c499767b0](https://bsd-hardware.info/?probe=5c499767b0) | Jun 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9303dab91](https://bsd-hardware.info/?probe=c9303dab91) | Jun 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [b576f09eec](https://bsd-hardware.info/?probe=b576f09eec) | Jun 17, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [60df3db3ab](https://bsd-hardware.info/?probe=60df3db3ab) | Jun 16, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [29a05b66f3](https://bsd-hardware.info/?probe=29a05b66f3) | Jun 15, 2022 |
| Sophos        | UTM                         | Firewall    | [7d81c953d5](https://bsd-hardware.info/?probe=7d81c953d5) | Jun 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [b7540c1e4a](https://bsd-hardware.info/?probe=b7540c1e4a) | Jun 14, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7626993227](https://bsd-hardware.info/?probe=7626993227) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [1cc180ad27](https://bsd-hardware.info/?probe=1cc180ad27) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [36f6b6f077](https://bsd-hardware.info/?probe=36f6b6f077) | Jun 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [96c3b75436](https://bsd-hardware.info/?probe=96c3b75436) | Jun 11, 2022 |
| Lanner        | FW-7543 B-GA                | Desktop     | [bf1e373f8a](https://bsd-hardware.info/?probe=bf1e373f8a) | Jun 10, 2022 |
| HP            | 806A                        | Desktop     | [c3051ac63e](https://bsd-hardware.info/?probe=c3051ac63e) | Jun 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [23d5c4d92d](https://bsd-hardware.info/?probe=23d5c4d92d) | Jun 10, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [cf146946d3](https://bsd-hardware.info/?probe=cf146946d3) | Jun 09, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [fd96faf8aa](https://bsd-hardware.info/?probe=fd96faf8aa) | Jun 08, 2022 |
| HP            | 18E4                        | Desktop     | [d63cd86fb5](https://bsd-hardware.info/?probe=d63cd86fb5) | Jun 08, 2022 |
| Supermicro    | X7SPA-HF                    | Desktop     | [37a918bd43](https://bsd-hardware.info/?probe=37a918bd43) | Jun 08, 2022 |
| MSI           | B85M-E45                    | Desktop     | [10e7bbf38a](https://bsd-hardware.info/?probe=10e7bbf38a) | Jun 08, 2022 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [d42b40d22c](https://bsd-hardware.info/?probe=d42b40d22c) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | Notebook    | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [6c9ccc6963](https://bsd-hardware.info/?probe=6c9ccc6963) | Jun 06, 2022 |
| PC Engines    | APU2                        | Desktop     | [ad2b0dd980](https://bsd-hardware.info/?probe=ad2b0dd980) | Jun 06, 2022 |
| Sophos        | UTM                         | Firewall    | [c6b9f29f41](https://bsd-hardware.info/?probe=c6b9f29f41) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [d8cd85e3d7](https://bsd-hardware.info/?probe=d8cd85e3d7) | Jun 05, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [02dce569c9](https://bsd-hardware.info/?probe=02dce569c9) | Jun 04, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [6a0c054bdd](https://bsd-hardware.info/?probe=6a0c054bdd) | Jun 04, 2022 |
| Thomas-Kre... | LES network 6L              | Desktop     | [a3023b3f39](https://bsd-hardware.info/?probe=a3023b3f39) | Jun 04, 2022 |
| HP            | 806A                        | Desktop     | [cc091ee2e2](https://bsd-hardware.info/?probe=cc091ee2e2) | Jun 03, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [467d85355c](https://bsd-hardware.info/?probe=467d85355c) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4294ad5419](https://bsd-hardware.info/?probe=4294ad5419) | Jun 01, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [26f2eb61de](https://bsd-hardware.info/?probe=26f2eb61de) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [2da72109a6](https://bsd-hardware.info/?probe=2da72109a6) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ad9772ac7](https://bsd-hardware.info/?probe=9ad9772ac7) | May 31, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fa3ea36bad](https://bsd-hardware.info/?probe=fa3ea36bad) | May 31, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [6beacad396](https://bsd-hardware.info/?probe=6beacad396) | May 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef87e699fb](https://bsd-hardware.info/?probe=ef87e699fb) | May 30, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [7152e4b816](https://bsd-hardware.info/?probe=7152e4b816) | May 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95234abead](https://bsd-hardware.info/?probe=95234abead) | May 28, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3fa863fea9](https://bsd-hardware.info/?probe=3fa863fea9) | May 27, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [0e21a1eeb0](https://bsd-hardware.info/?probe=0e21a1eeb0) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [cdddbb5d23](https://bsd-hardware.info/?probe=cdddbb5d23) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7a47fcd920](https://bsd-hardware.info/?probe=7a47fcd920) | May 27, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a5446262b3](https://bsd-hardware.info/?probe=a5446262b3) | May 27, 2022 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [04a06df827](https://bsd-hardware.info/?probe=04a06df827) | May 27, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [fadb382a5a](https://bsd-hardware.info/?probe=fadb382a5a) | May 26, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e9e497fc7b](https://bsd-hardware.info/?probe=e9e497fc7b) | May 22, 2022 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [b05a8f6ed8](https://bsd-hardware.info/?probe=b05a8f6ed8) | May 22, 2022 |
| Biostar       | J4105NHU                    | Desktop     | [88b74aaf3b](https://bsd-hardware.info/?probe=88b74aaf3b) | May 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f04f129625](https://bsd-hardware.info/?probe=f04f129625) | May 22, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [26b6fef8c6](https://bsd-hardware.info/?probe=26b6fef8c6) | May 21, 2022 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [c1da3a6a28](https://bsd-hardware.info/?probe=c1da3a6a28) | May 21, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [063d483b50](https://bsd-hardware.info/?probe=063d483b50) | May 20, 2022 |
| HP            | 339A                        | Desktop     | [e6a9b68262](https://bsd-hardware.info/?probe=e6a9b68262) | May 20, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [042f6c0b45](https://bsd-hardware.info/?probe=042f6c0b45) | May 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [24d2bf3524](https://bsd-hardware.info/?probe=24d2bf3524) | May 19, 2022 |
| Dell          | 08V001 A03                  | Server      | [c34d5c2be3](https://bsd-hardware.info/?probe=c34d5c2be3) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [acc4101dc1](https://bsd-hardware.info/?probe=acc4101dc1) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [1b218204b8](https://bsd-hardware.info/?probe=1b218204b8) | May 18, 2022 |
| MSI           | B85M-E45                    | Desktop     | [83ab25156c](https://bsd-hardware.info/?probe=83ab25156c) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [e13c8baa2d](https://bsd-hardware.info/?probe=e13c8baa2d) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [b8579c7f84](https://bsd-hardware.info/?probe=b8579c7f84) | May 17, 2022 |
| IBM           | 00KC500                     | Server      | [7f8395e815](https://bsd-hardware.info/?probe=7f8395e815) | May 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [98b4dea15a](https://bsd-hardware.info/?probe=98b4dea15a) | May 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [8c2f853975](https://bsd-hardware.info/?probe=8c2f853975) | May 17, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [311c32e56e](https://bsd-hardware.info/?probe=311c32e56e) | May 17, 2022 |
| Supermicro    | X11SCL-IF                   | Server      | [94ff07cdd9](https://bsd-hardware.info/?probe=94ff07cdd9) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c071b686c2](https://bsd-hardware.info/?probe=c071b686c2) | May 15, 2022 |
| MSI           | MS-7C82                     | Desktop     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4fad520626](https://bsd-hardware.info/?probe=4fad520626) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| Sophos        | UTM                         | Firewall    | [fec90c3d92](https://bsd-hardware.info/?probe=fec90c3d92) | May 13, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [54a5041cdf](https://bsd-hardware.info/?probe=54a5041cdf) | May 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [faec798f5c](https://bsd-hardware.info/?probe=faec798f5c) | May 11, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [8cdb309c2e](https://bsd-hardware.info/?probe=8cdb309c2e) | May 11, 2022 |
| Dell          | 0PRWNC A05                  | Server      | [0b239c3286](https://bsd-hardware.info/?probe=0b239c3286) | May 11, 2022 |
| HP            | 213D A01                    | Desktop     | [89955ba84f](https://bsd-hardware.info/?probe=89955ba84f) | May 11, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [0ca5685ce0](https://bsd-hardware.info/?probe=0ca5685ce0) | May 10, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| HP            | 82A1                        | Desktop     | [34cb091e26](https://bsd-hardware.info/?probe=34cb091e26) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Sophos        | SG                          | Firewall    | [9e16039d35](https://bsd-hardware.info/?probe=9e16039d35) | May 06, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [dc534266df](https://bsd-hardware.info/?probe=dc534266df) | May 06, 2022 |
| BESSTAR Te... | IB9                         | Desktop     | [4a4e45585d](https://bsd-hardware.info/?probe=4a4e45585d) | May 06, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [52b6c326c8](https://bsd-hardware.info/?probe=52b6c326c8) | May 05, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| friendlyel... | nanopi-r4s                  | Desktop     | [3db2ec8973](https://bsd-hardware.info/?probe=3db2ec8973) | May 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [b96fd74ab0](https://bsd-hardware.info/?probe=b96fd74ab0) | May 03, 2022 |
| Sophos        | XG                          | Firewall    | [19b1a90a3c](https://bsd-hardware.info/?probe=19b1a90a3c) | May 03, 2022 |
| Sophos        | SG                          | Firewall    | [5109c6e2e4](https://bsd-hardware.info/?probe=5109c6e2e4) | May 03, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [14d02a8209](https://bsd-hardware.info/?probe=14d02a8209) | May 03, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Sophos        | XG                          | Firewall    | [bec4979a46](https://bsd-hardware.info/?probe=bec4979a46) | May 03, 2022 |
| Intel         | QHSW02                      | Desktop     | [e4c8d6c787](https://bsd-hardware.info/?probe=e4c8d6c787) | May 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [5e8168a980](https://bsd-hardware.info/?probe=5e8168a980) | Apr 30, 2022 |
| Sophos        | SG                          | Firewall    | [ca2608d67f](https://bsd-hardware.info/?probe=ca2608d67f) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| OEM           | 1.0                         | Desktop     | [36e78ab638](https://bsd-hardware.info/?probe=36e78ab638) | Apr 29, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [54fe9e7529](https://bsd-hardware.info/?probe=54fe9e7529) | Apr 29, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Sophos        | SG                          | Firewall    | [dd94f9dfe6](https://bsd-hardware.info/?probe=dd94f9dfe6) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0750e29d3c](https://bsd-hardware.info/?probe=0750e29d3c) | Apr 27, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [920eae6f2e](https://bsd-hardware.info/?probe=920eae6f2e) | Apr 27, 2022 |
| Sophos        | SG                          | Firewall    | [92a32f4608](https://bsd-hardware.info/?probe=92a32f4608) | Apr 27, 2022 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [c36f9d6c1d](https://bsd-hardware.info/?probe=c36f9d6c1d) | Apr 26, 2022 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [637c28d728](https://bsd-hardware.info/?probe=637c28d728) | Apr 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2a8ebfdb92](https://bsd-hardware.info/?probe=2a8ebfdb92) | Apr 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 65        | 3.06%   |
| OPNsense 21.1     | 64        | 3.01%   |
| OPNsense 22.7.10  | 59        | 2.78%   |
| OPNsense 21.1.5   | 56        | 2.64%   |
| OPNsense 22.1     | 54        | 2.54%   |
| OPNsense 20.7.8   | 54        | 2.54%   |
| OPNsense 21.7.3   | 52        | 2.45%   |
| OPNsense 21.7.1   | 51        | 2.4%    |
| OPNsense 21.1.3   | 45        | 2.12%   |
| OPNsense 21.7.6   | 43        | 2.03%   |
| OPNsense 21.1.2   | 43        | 2.03%   |
| OPNsense 22.7.4   | 42        | 1.98%   |
| OPNsense 22.1.8   | 42        | 1.98%   |
| OPNsense 21.1.1   | 42        | 1.98%   |
| OPNsense 22.7.6   | 41        | 1.93%   |
| OPNsense 23.1.5   | 40        | 1.88%   |
| OPNsense 23.1     | 40        | 1.88%   |
| OPNsense 22.1.6   | 40        | 1.88%   |
| OPNsense 21.1.4   | 39        | 1.84%   |
| OPNsense 22.7.9   | 38        | 1.79%   |
| OPNsense 23.1.1   | 35        | 1.65%   |
| helloSystem 0.4.0 | 34        | 1.6%    |
| OPNsense 22.1.10  | 28        | 1.32%   |
| OpenBSD 6.8       | 28        | 1.32%   |
| OPNsense 22.7.7   | 26        | 1.22%   |
| OPNsense 22.1.9   | 26        | 1.22%   |
| OPNsense 22.1.1   | 26        | 1.22%   |
| OPNsense 21.7.5   | 26        | 1.22%   |
| OPNsense 21.1.7   | 26        | 1.22%   |
| helloSystem 0.7.0 | 25        | 1.18%   |
| OPNsense 22.7.11  | 24        | 1.13%   |
| OPNsense 22.1.4   | 24        | 1.13%   |
| OPNsense 22.1.2   | 24        | 1.13%   |
| OPNsense 22.7.8   | 23        | 1.08%   |
| OPNsense 23.1.4   | 21        | 0.99%   |
| OPNsense 22.7.2   | 21        | 0.99%   |
| OPNsense 22.7     | 21        | 0.99%   |
| OPNsense 21.1.8   | 21        | 0.99%   |
| OPNsense 21.1.6   | 21        | 0.99%   |
| helloSystem 0.8.1 | 21        | 0.99%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1166      | 70.2%   |
| FreeBSD     | 221       | 13.31%  |
| helloSystem | 130       | 7.83%   |
| OpenBSD     | 66        | 3.97%   |
| GhostBSD    | 34        | 2.05%   |
| NomadBSD    | 21        | 1.26%   |
| TrueNAS     | 5         | 0.3%    |
| NetBSD      | 5         | 0.3%    |
| MyBee       | 3         | 0.18%   |
| pfSense     | 2         | 0.12%   |
| HardenedBSD | 2         | 0.12%   |
| PC-BSD      | 1         | 0.06%   |
| MidnightBSD | 1         | 0.06%   |
| FuryBSD     | 1         | 0.06%   |
| FreeNAS     | 1         | 0.06%   |
| DragonFly   | 1         | 0.06%   |
| ClonOS      | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1618      | 98.48%  |
| i386    | 11        | 0.67%   |
| arm64   | 9         | 0.55%   |
| arm     | 3         | 0.18%   |
| sparc64 | 1         | 0.06%   |
| macppc  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1282      | 76.67%  |
| helloDesktop  | 143       | 8.55%   |
| MATE          | 49        | 2.93%   |
| fvwm          | 38        | 2.27%   |
| XFCE          | 33        | 1.97%   |
| KDE5          | 33        | 1.97%   |
| GNOME         | 21        | 1.26%   |
| Openbox       | 19        | 1.14%   |
| TWM           | 18        | 1.08%   |
| AwesomeWM     | 10        | 0.6%    |
| i3            | 7         | 0.42%   |
| LXQt          | 3         | 0.18%   |
| Enlightenment | 3         | 0.18%   |
| Cinnamon      | 3         | 0.18%   |
| LXDE          | 2         | 0.12%   |
| Fluxbox       | 2         | 0.12%   |
| Picom         | 1         | 0.06%   |
| iwm           | 1         | 0.06%   |
| IceWM         | 1         | 0.06%   |
| GNUstep       | 1         | 0.06%   |
| filer         | 1         | 0.06%   |
| Compton       | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1298      | 78.71%  |
| X11     | 348       | 21.1%   |
| Wayland | 2         | 0.12%   |
| Tty     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1369      | 82.03%  |
| SLiM    | 173       | 10.37%  |
| LightDM | 44        | 2.64%   |
| SDDM    | 36        | 2.16%   |
| XDM     | 23        | 1.38%   |
| GDM     | 19        | 1.14%   |
| Ly      | 5         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 1292      | 77.23%  |
| en_US            | 137       | 8.19%   |
| C                | 115       | 6.87%   |
| de_DE            | 95        | 5.68%   |
| en_GB            | 8         | 0.48%   |
| de               | 7         | 0.42%   |
| en               | 4         | 0.24%   |
| fr_FR            | 3         | 0.18%   |
| de_DE.ISO8859-1  | 3         | 0.18%   |
| ru_RU            | 1         | 0.06%   |
| pl_PL            | 1         | 0.06%   |
| ISO8859-15       | 1         | 0.06%   |
| fr               | 1         | 0.06%   |
| en_IE            | 1         | 0.06%   |
| en_GB.ISO8859-1  | 1         | 0.06%   |
| en_DE            | 1         | 0.06%   |
| en_CA            | 1         | 0.06%   |
| de_DE.ISO8859-15 | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1422      | 85.82%  |
| BIOS | 235       | 14.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1002      | 59.57%  |
| Zfs     | 573       | 34.07%  |
| Ffs     | 66        | 3.92%   |
| Cd9660  | 40        | 2.38%   |
| Hammer2 | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1523      | 92.08%  |
| MBR     | 111       | 6.71%   |
| Unknown | 19        | 1.15%   |
| BSD     | 1         | 0.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 182       | 11.08%  |
| Lenovo              | 124       | 7.55%   |
| Supermicro          | 111       | 6.76%   |
| PC Engines          | 106       | 6.45%   |
| Fujitsu             | 93        | 5.66%   |
| Dell                | 92        | 5.6%    |
| Hewlett-Packard     | 91        | 5.54%   |
| ASUSTek Computer    | 85        | 5.17%   |
| Sophos              | 77        | 4.69%   |
| Intel               | 75        | 4.56%   |
| ASRock              | 62        | 3.77%   |
| ZOTAC               | 49        | 2.98%   |
| Gigabyte Technology | 49        | 2.98%   |
| MSI                 | 42        | 2.56%   |
| AMI                 | 35        | 2.13%   |
| BESSTAR Tech        | 33        | 2.01%   |
| Apple               | 26        | 1.58%   |
| Protectli           | 23        | 1.4%    |
| Shuttle             | 20        | 1.22%   |
| Deciso              | 20        | 1.22%   |
| Acer                | 18        | 1.1%    |
| CncTion             | 15        | 0.91%   |
| Techvision          | 13        | 0.79%   |
| Hardkernel          | 13        | 0.79%   |
| AWOW                | 12        | 0.73%   |
| Thomas-Krenn.AG     | 11        | 0.67%   |
| MW                  | 9         | 0.55%   |
| CheckPoint          | 9         | 0.55%   |
| TUXEDO              | 8         | 0.49%   |
| ASRockRack          | 8         | 0.49%   |
| NF541               | 7         | 0.43%   |
| IBM                 | 7         | 0.43%   |
| Biostar             | 6         | 0.37%   |
| Beckhoff Automation | 5         | 0.3%    |
| Sony                | 4         | 0.24%   |
| Notebook            | 4         | 0.24%   |
| NEXCOM              | 4         | 0.24%   |
| Medion              | 4         | 0.24%   |
| Lex                 | 4         | 0.24%   |
| Lanner              | 4         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 187       | 11.38%  |
| PC Engines APU2                                  | 53        | 3.23%   |
| Sophos SG                                        | 47        | 2.86%   |
| Supermicro Super Server                          | 37        | 2.25%   |
| Fujitsu FUTRO S920                               | 36        | 2.19%   |
| PC Engines apu4                                  | 33        | 2.01%   |
| AMI Aptio CRB                                    | 20        | 1.22%   |
| Intel Q3XXG4-P V1.0                              | 17        | 1.03%   |
| Sophos UTM                                       | 16        | 0.97%   |
| Sophos XG                                        | 14        | 0.85%   |
| Techvision TVI7309X                              | 13        | 0.79%   |
| Hardkernel ODROID-H2                             | 12        | 0.73%   |
| ZOTAC ZBOX-CI329NANO                             | 11        | 0.67%   |
| ZOTAC ZBOX-CI327NANO-GS-01                       | 10        | 0.61%   |
| Protectli FW4B                                   | 9         | 0.55%   |
| PC Engines APU                                   | 9         | 0.55%   |
| MW GMLK-2_5G4L                                   | 9         | 0.55%   |
| HP ProLiant MicroServer Gen8                     | 9         | 0.55%   |
| Dell PowerEdge R210 II                           | 9         | 0.55%   |
| BESSTAR Tech X35G                                | 9         | 0.55%   |
| Supermicro A1SAi                                 | 8         | 0.49%   |
| PC Engines APU3                                  | 8         | 0.49%   |
| CncTion N5105-4L                                 | 8         | 0.49%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 7         | 0.43%   |
| Protectli FW6                                    | 7         | 0.43%   |
| NF541 1.0                                        | 7         | 0.43%   |
| BESSTAR Tech GK41                                | 7         | 0.43%   |
| AWOW PC BOX                                      | 7         | 0.43%   |
| HP t620 PLUS Quad Core TC                        | 6         | 0.37%   |
| Deciso NetBoard-A10                              | 6         | 0.37%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO                 | 5         | 0.3%    |
| Thomas-Krenn.AG LES network+                     | 5         | 0.3%    |
| Fujitsu FUTRO S930                               | 5         | 0.3%    |
| Deciso Netboard A20                              | 5         | 0.3%    |
| ASUS All Series                                  | 5         | 0.3%    |
| AMI SG                                           | 5         | 0.3%    |
| ZOTAC ZBOX-CI323NANO                             | 4         | 0.24%   |
| Supermicro X7SPA-HF                              | 4         | 0.24%   |
| Protectli VP2420                                 | 4         | 0.24%   |
| NEXCOM ASG                                       | 4         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 187       | 11.38%  |
| Lenovo ThinkPad            | 83        | 5.05%   |
| PC Engines APU2            | 53        | 3.23%   |
| Fujitsu FUTRO              | 50        | 3.04%   |
| Sophos SG                  | 47        | 2.86%   |
| Supermicro Super           | 37        | 2.25%   |
| PC Engines apu4            | 33        | 2.01%   |
| Dell OptiPlex              | 31        | 1.89%   |
| HP ProLiant                | 28        | 1.7%    |
| Dell PowerEdge             | 23        | 1.4%    |
| AMI Aptio                  | 20        | 1.22%   |
| Dell Latitude              | 19        | 1.16%   |
| Supermicro 1HE             | 17        | 1.03%   |
| Intel Q3XXG4-P             | 17        | 1.03%   |
| Sophos UTM                 | 16        | 0.97%   |
| Lenovo ThinkCentre         | 16        | 0.97%   |
| Sophos XG                  | 14        | 0.85%   |
| Techvision TVI7309X        | 13        | 0.79%   |
| Hardkernel ODROID-H2       | 12        | 0.73%   |
| ZOTAC ZBOX-CI329NANO       | 11        | 0.67%   |
| HP t620                    | 11        | 0.67%   |
| HP ProDesk                 | 11        | 0.67%   |
| HP Compaq                  | 11        | 0.67%   |
| ASUS TUF                   | 11        | 0.67%   |
| ZOTAC ZBOX-CI327NANO-GS-01 | 10        | 0.61%   |
| Fujitsu PRIMERGY           | 10        | 0.61%   |
| Fujitsu LIFEBOOK           | 10        | 0.61%   |
| Fujitsu ESPRIMO            | 10        | 0.61%   |
| Deciso Netboard            | 10        | 0.61%   |
| ASUS PRIME                 | 10        | 0.61%   |
| Protectli FW4B             | 9         | 0.55%   |
| PC Engines APU             | 9         | 0.55%   |
| MW GMLK-2                  | 9         | 0.55%   |
| BESSTAR Tech X35G          | 9         | 0.55%   |
| Thomas-Krenn.AG LES        | 8         | 0.49%   |
| Supermicro A1SAi           | 8         | 0.49%   |
| PC Engines APU3            | 8         | 0.49%   |
| CncTion N5105-4L           | 8         | 0.49%   |
| Protectli FW6              | 7         | 0.43%   |
| NF541 1.0                  | 7         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 201       | 12.23%  |
| 2020    | 191       | 11.63%  |
| 2021    | 167       | 10.16%  |
| 2019    | 158       | 9.62%   |
| 2016    | 152       | 9.25%   |
| 2014    | 135       | 8.22%   |
| 2017    | 114       | 6.94%   |
| 2022    | 105       | 6.39%   |
| 2013    | 88        | 5.36%   |
| 2012    | 71        | 4.32%   |
| 2011    | 69        | 4.2%    |
| 2015    | 60        | 3.65%   |
| 2010    | 45        | 2.74%   |
| 2009    | 33        | 2.01%   |
| 2008    | 20        | 1.22%   |
| Unknown | 15        | 0.91%   |
| 2007    | 9         | 0.55%   |
| 2006    | 4         | 0.24%   |
| 2023    | 2         | 0.12%   |
| 2003    | 2         | 0.12%   |
| 2005    | 1         | 0.06%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 987       | 60.07%  |
| Notebook       | 260       | 15.82%  |
| Mini pc        | 153       | 9.31%   |
| Server         | 137       | 8.34%   |
| Firewall       | 82        | 4.99%   |
| All in one     | 11        | 0.67%   |
| Convertible    | 7         | 0.43%   |
| System on chip | 6         | 0.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1523      | 92.7%   |
| Yes  | 120       | 7.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 615       | 36.83%  |
| 4.01-8.0        | 405       | 24.25%  |
| 16.01-24.0      | 348       | 20.84%  |
| 32.01-64.0      | 137       | 8.2%    |
| 2.01-3.0        | 71        | 4.25%   |
| 64.01-256.0     | 47        | 2.81%   |
| 3.01-4.0        | 12        | 0.72%   |
| 24.01-32.0      | 12        | 0.72%   |
| 0.51-1.0        | 9         | 0.54%   |
| 1.01-2.0        | 7         | 0.42%   |
| 0.01-0.5        | 4         | 0.24%   |
| More than 256.0 | 2         | 0.12%   |
| 0               | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 949       | 55.86%  |
| 0.51-1.0    | 498       | 29.31%  |
| 1.01-2.0    | 139       | 8.18%   |
| 2.01-3.0    | 38        | 2.24%   |
| 4.01-8.0    | 21        | 1.24%   |
| 3.01-4.0    | 18        | 1.06%   |
| 0           | 9         | 0.53%   |
| 8.01-16.0   | 8         | 0.47%   |
| Unknown     | 7         | 0.41%   |
| 16.01-24.0  | 6         | 0.35%   |
| 24.01-32.0  | 3         | 0.18%   |
| 64.01-256.0 | 2         | 0.12%   |
| 32.01-64.0  | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1241      | 73.69%  |
| 2      | 197       | 11.7%   |
| 0      | 127       | 7.54%   |
| 3      | 49        | 2.91%   |
| 4      | 34        | 2.02%   |
| 5      | 12        | 0.71%   |
| 6      | 9         | 0.53%   |
| 8      | 5         | 0.3%    |
| 7      | 5         | 0.3%    |
| 9      | 2         | 0.12%   |
| 14     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1403      | 84.88%  |
| Yes       | 250       | 15.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1603      | 97.57%  |
| No        | 40        | 2.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1130      | 68.24%  |
| Yes       | 526       | 31.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1317      | 79.63%  |
| Yes       | 337       | 20.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 1643      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 153       | 8.45%   |
| Munich            | 70        | 3.87%   |
| Hamburg           | 62        | 3.42%   |
| Frankfurt am Main | 41        | 2.26%   |
| Cologne           | 40        | 2.21%   |
| Stuttgart         | 30        | 1.66%   |
| Ludwigsburg       | 24        | 1.33%   |
| Karlsruhe         | 22        | 1.21%   |
| Hanover           | 17        | 0.94%   |
| Bonn              | 16        | 0.88%   |
| Dresden           | 15        | 0.83%   |
| Dortmund          | 15        | 0.83%   |
| Nuremberg         | 14        | 0.77%   |
| Leipzig           | 13        | 0.72%   |
| Bochum            | 13        | 0.72%   |
| Falkenstein       | 12        | 0.66%   |
| Bielefeld         | 12        | 0.66%   |
| Mannheim          | 11        | 0.61%   |
| Wiesbaden         | 10        | 0.55%   |
| Reutlingen        | 9         | 0.5%    |
| Heidelberg        | 9         | 0.5%    |
| Halle             | 9         | 0.5%    |
| Chemnitz          | 9         | 0.5%    |
| Wuppertal         | 8         | 0.44%   |
| Tamm              | 8         | 0.44%   |
| Potsdam           | 8         | 0.44%   |
| Paderborn         | 8         | 0.44%   |
| Magdeburg         | 8         | 0.44%   |
| Essen             | 8         | 0.44%   |
| Erlangen          | 8         | 0.44%   |
| Darmstadt         | 8         | 0.44%   |
| Wernigerode       | 7         | 0.39%   |
| Ulm               | 7         | 0.39%   |
| Solingen          | 7         | 0.39%   |
| Neuss             | 7         | 0.39%   |
| Mainz             | 7         | 0.39%   |
| Lingen            | 7         | 0.39%   |
| Kiel              | 7         | 0.39%   |
| Kassel            | 7         | 0.39%   |
| Heilbronn         | 7         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 311       | 485    | 17.05%  |
| Transcend           | 159       | 206    | 8.72%   |
| WDC                 | 155       | 264    | 8.5%    |
| Kingston            | 128       | 202    | 7.02%   |
| SanDisk             | 110       | 150    | 6.03%   |
| Intel               | 107       | 167    | 5.87%   |
| Crucial             | 101       | 150    | 5.54%   |
| Seagate             | 98        | 169    | 5.37%   |
| Toshiba             | 63        | 112    | 3.45%   |
| Phison              | 40        | 56     | 2.19%   |
| Intenso             | 37        | 55     | 2.03%   |
| China               | 37        | 44     | 2.03%   |
| Hitachi             | 35        | 58     | 1.92%   |
| HGST                | 32        | 63     | 1.75%   |
| A-DATA Technology   | 32        | 38     | 1.75%   |
| Hoodisk             | 31        | 51     | 1.7%    |
| Micron Technology   | 26        | 40     | 1.43%   |
| NVMe                | 24        | 41     | 1.32%   |
| FORESEE             | 20        | 29     | 1.1%    |
| Innodisk            | 17        | 18     | 0.93%   |
| ATP                 | 17        | 20     | 0.93%   |
| OCZ                 | 15        | 23     | 0.82%   |
| Hewlett-Packard     | 14        | 20     | 0.77%   |
| SPCC                | 13        | 19     | 0.71%   |
| Apacer              | 11        | 15     | 0.6%    |
| Corsair             | 10        | 16     | 0.55%   |
| Apple               | 10        | 10     | 0.55%   |
| SK hynix            | 8         | 9      | 0.44%   |
| Patriot             | 8         | 10     | 0.44%   |
| Dogfish             | 8         | 10     | 0.44%   |
| Verbatim            | 7         | 13     | 0.38%   |
| LITEON              | 7         | 7      | 0.38%   |
| TCSUNBOW            | 6         | 7      | 0.33%   |
| Protectli           | 6         | 8      | 0.33%   |
| KIOXIA              | 6         | 7      | 0.33%   |
| Fujitsu             | 6         | 6      | 0.33%   |
| KIOXIA-EXCERIA      | 5         | 9      | 0.27%   |
| Gigabyte Technology | 5         | 6      | 0.27%   |
| PNY                 | 4         | 4      | 0.22%   |
| LSI                 | 4         | 4      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Phison SATA SSD 16GB             | 31        | 1.62%   |
| Transcend TS128GMSA230S 128GB    | 23        | 1.2%    |
| Samsung SSD 850 EVO 250GB        | 20        | 1.04%   |
| Samsung SSD 860 EVO 500GB        | 17        | 0.89%   |
| Kingston SA400S37120G 120GB      | 17        | 0.89%   |
| Crucial CT240BX500SSD1 240GB     | 17        | 0.89%   |
| China SATA SSD 16GB              | 16        | 0.83%   |
| Transcend TS64GMSA230S 64GB      | 14        | 0.73%   |
| Transcend TS256GMSA230S 256GB    | 13        | 0.68%   |
| Samsung SSD 840 EVO 250GB        | 13        | 0.68%   |
| FORESEE 128GB SSD                | 12        | 0.63%   |
| Crucial CT120BX500SSD1 120GB     | 12        | 0.63%   |
| SanDisk SSD PLUS 120GB           | 11        | 0.57%   |
| Samsung SSD 870 EVO 250GB        | 11        | 0.57%   |
| Samsung SSD 840 EVO 120GB        | 11        | 0.57%   |
| Kingston SUV500MS120G 120GB      | 11        | 0.57%   |
| A-DATA IM2S3134N-064GM 64GB      | 11        | 0.57%   |
| Transcend TS64GSSD370 64GB       | 10        | 0.52%   |
| SanDisk SSD PLUS 240GB           | 10        | 0.52%   |
| SanDisk SDSSDA120G 120GB         | 10        | 0.52%   |
| Hoodisk SSD 128GB                | 10        | 0.52%   |
| Crucial CT500MX500SSD1 500GB     | 10        | 0.52%   |
| Transcend TS32GSSD370S 32GB      | 9         | 0.47%   |
| Transcend TS128GMSA370 128GB     | 9         | 0.47%   |
| Samsung SSD 850 EVO 500GB        | 9         | 0.47%   |
| Kingston SV300S37A120G 120GB     | 9         | 0.47%   |
| Kingston SA400S37240G 240GB      | 9         | 0.47%   |
| Hoodisk SSD 64GB                 | 9         | 0.47%   |
| WDC WD40EFRX-68N32N0 4TB         | 8         | 0.42%   |
| Transcend TS32GMSA370 32GB       | 8         | 0.42%   |
| Intenso SSD 120GB                | 8         | 0.42%   |
| Intel SSDSC2BB120G4 120GB        | 8         | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB   | 7         | 0.36%   |
| Samsung SSD 860 EVO 250GB        | 7         | 0.36%   |
| Samsung SSD 850 PRO 256GB        | 7         | 0.36%   |
| Samsung SSD 850 EVO 120GB        | 7         | 0.36%   |
| Samsung SSD 840 PRO Series 256GB | 7         | 0.36%   |
| Kingston SV300S37A60G 64GB       | 7         | 0.36%   |
| Kingston OM8PDP3512B-A01 512GB   | 7         | 0.36%   |
| Intenso SSD 128GB                | 7         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 115       | 209    | 30.42%  |
| Seagate             | 93        | 159    | 24.6%   |
| Toshiba             | 39        | 67     | 10.32%  |
| Hitachi             | 33        | 53     | 8.73%   |
| HGST                | 32        | 63     | 8.47%   |
| Samsung Electronics | 18        | 23     | 4.76%   |
| NVMe                | 16        | 27     | 4.23%   |
| Fujitsu             | 6         | 6      | 1.59%   |
| Hewlett-Packard     | 5         | 8      | 1.32%   |
| LSI                 | 4         | 4      | 1.06%   |
| OPENBSD             | 3         | 5      | 0.79%   |
| LSILOGIC            | 2         | 5      | 0.53%   |
| JetFlash            | 2         | 2      | 0.53%   |
| WD MediaMax         | 1         | 2      | 0.26%   |
| Product:            | 1         | 1      | 0.26%   |
| Maxtor              | 1         | 1      | 0.26%   |
| Intenso             | 1         | 1      | 0.26%   |
| IBM/Hitachi         | 1         | 1      | 0.26%   |
| IBM                 | 1         | 1      | 0.26%   |
| Generic             | 1         | 1      | 0.26%   |
| General             | 1         | 1      | 0.26%   |
| ASMT                | 1         | 1      | 0.26%   |
| Apple               | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 227       | 345    | 18.37%  |
| Transcend           | 147       | 193    | 11.89%  |
| SanDisk             | 109       | 149    | 8.82%   |
| Kingston            | 100       | 156    | 8.09%   |
| Intel               | 97        | 152    | 7.85%   |
| Crucial             | 93        | 136    | 7.52%   |
| China               | 37        | 44     | 2.99%   |
| Phison              | 36        | 52     | 2.91%   |
| Intenso             | 36        | 54     | 2.91%   |
| Hoodisk             | 31        | 51     | 2.51%   |
| A-DATA Technology   | 31        | 36     | 2.51%   |
| WDC                 | 23        | 26     | 1.86%   |
| Micron Technology   | 18        | 30     | 1.46%   |
| FORESEE             | 18        | 26     | 1.46%   |
| Innodisk            | 17        | 18     | 1.38%   |
| Toshiba             | 16        | 22     | 1.29%   |
| OCZ                 | 15        | 23     | 1.21%   |
| ATP                 | 15        | 15     | 1.21%   |
| Apacer              | 11        | 15     | 0.89%   |
| SPCC                | 10        | 15     | 0.81%   |
| NVMe                | 9         | 12     | 0.73%   |
| Hewlett-Packard     | 9         | 12     | 0.73%   |
| Apple               | 9         | 9      | 0.73%   |
| Dogfish             | 8         | 10     | 0.65%   |
| Verbatim            | 7         | 13     | 0.57%   |
| LITEON              | 7         | 7      | 0.57%   |
| TCSUNBOW            | 6         | 7      | 0.49%   |
| Protectli           | 6         | 8      | 0.49%   |
| Patriot             | 6         | 8      | 0.49%   |
| Corsair             | 6         | 10     | 0.49%   |
| Seagate             | 4         | 9      | 0.32%   |
| LITEONIT            | 4         | 5      | 0.32%   |
| Kston               | 4         | 5      | 0.32%   |
| KingDian            | 4         | 9      | 0.32%   |
| BAITITON            | 4         | 5      | 0.32%   |
| Team                | 3         | 3      | 0.24%   |
| SK hynix            | 3         | 4      | 0.24%   |
| ShiJi               | 3         | 4      | 0.24%   |
| PNY                 | 3         | 3      | 0.24%   |
| Plextor             | 3         | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1149      | 1762   | 67.95%  |
| HDD  | 320       | 642    | 18.92%  |
| NVMe | 222       | 340    | 13.13%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1362      | 2404   | 85.98%  |
| NVMe | 222       | 340    | 14.02%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1239      | 1876   | 82.66%  |
| 0.51-1.0        | 141       | 228    | 9.41%   |
| 1.01-2.0        | 59        | 138    | 3.94%   |
| 3.01-4.0        | 27        | 85     | 1.8%    |
| 4.01-10.0       | 15        | 27     | 1%      |
| 2.01-3.0        | 14        | 38     | 0.93%   |
| 10.01-20.0      | 3         | 11     | 0.2%    |
| More than 100.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 709       | 41.88%  |
| 1-20           | 241       | 14.24%  |
| 251-500        | 235       | 13.88%  |
| 51-100         | 199       | 11.75%  |
| 21-50          | 186       | 10.99%  |
| 501-1000       | 77        | 4.55%   |
| More than 3000 | 16        | 0.95%   |
| 1001-2000      | 14        | 0.83%   |
| Unknown        | 11        | 0.65%   |
| 2001-3000      | 5         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1537      | 90.73%  |
| 21-50          | 75        | 4.43%   |
| 51-100         | 27        | 1.59%   |
| 101-250        | 22        | 1.3%    |
| Unknown        | 11        | 0.65%   |
| 251-500        | 8         | 0.47%   |
| 1001-2000      | 5         | 0.3%    |
| 501-1000       | 4         | 0.24%   |
| More than 3000 | 3         | 0.18%   |
| 2001-3000      | 2         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A60G 64GB                   | 4         | 6      | 2.56%   |
| Kingston SMS200S360G 64GB                    | 3         | 3      | 1.92%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 2         | 3      | 1.28%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 2         | 7      | 1.28%   |
| WDC WD2000FYYZ-01UL1B2 2TB                   | 2         | 4      | 1.28%   |
| WDC WD2000FYYZ-01UL1B1 2TB                   | 2         | 4      | 1.28%   |
| WDC WD1600AAJS-75M0A0 160GB                  | 2         | 2      | 1.28%   |
| Toshiba THNSNK128GCS8 SATA 128GB             | 2         | 2      | 1.28%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.28%   |
| Seagate ST3160318AS 160GB                    | 2         | 2      | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 1.28%   |
| Seagate ST1000DX001-1CM162 1TB               | 2         | 2      | 1.28%   |
| SanDisk SSD PLUS 240GB                       | 2         | 2      | 1.28%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 2         | 4      | 1.28%   |
| Samsung Electronics HD501LJ 500GB            | 2         | 2      | 1.28%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 2         | 4      | 1.28%   |
| Micron Technology 1100 SATA 256GB            | 2         | 2      | 1.28%   |
| Kingston SMS200S3120G 120GB                  | 2         | 3      | 1.28%   |
| Kingston SHFS37A120G 120GB                   | 2         | 3      | 1.28%   |
| Intenso SSD SATAIII 120GB                    | 2         | 2      | 1.28%   |
| Intel SSDSC2CT180A3 180GB                    | 2         | 2      | 1.28%   |
| Intel SSDSC2CT120A3 120GB                    | 2         | 2      | 1.28%   |
| Intel SSDSC2BF180A4L 180GB                   | 2         | 2      | 1.28%   |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 1.28%   |
| Hitachi HTS543232L9SA02 320GB                | 2         | 3      | 1.28%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 1.28%   |
| HGST HTS541010A7E630 1TB                     | 2         | 4      | 1.28%   |
| Crucial CT275MX300SSD1 275GB                 | 2         | 2      | 1.28%   |
| Apacer 8GB SATA Flash Drive                  | 2         | 2      | 1.28%   |
| WDC WD60EFRX-68TGBN1 6TB                     | 1         | 3      | 0.64%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 0.64%   |
| WDC WD3000BLFS-60YBU2 304GB                  | 1         | 2      | 0.64%   |
| WDC WD2503ABYX-01WERA1 256GB                 | 1         | 2      | 0.64%   |
| WDC WD2503ABYX-01WERA0 256GB                 | 1         | 2      | 0.64%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 0.64%   |
| WDC WD1600AAJS-08L7A0 160GB                  | 1         | 1      | 0.64%   |
| WDC WD1600AABS-00PRA0 160GB                  | 1         | 1      | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 1      | 0.64%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1         | 1      | 0.64%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 32     | 16.77%  |
| WDC                 | 22        | 39     | 14.19%  |
| Kingston            | 16        | 21     | 10.32%  |
| Intel               | 14        | 16     | 9.03%   |
| Samsung Electronics | 13        | 16     | 8.39%   |
| Hitachi             | 12        | 17     | 7.74%   |
| Crucial             | 9         | 19     | 5.81%   |
| SanDisk             | 7         | 10     | 4.52%   |
| HGST                | 7         | 10     | 4.52%   |
| Toshiba             | 5         | 12     | 3.23%   |
| Micron Technology   | 5         | 7      | 3.23%   |
| Apacer              | 4         | 4      | 2.58%   |
| Intenso             | 3         | 3      | 1.94%   |
| A-DATA Technology   | 3         | 4      | 1.94%   |
| OCZ                 | 2         | 2      | 1.29%   |
| Corsair             | 2         | 4      | 1.29%   |
| SMI                 | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KingDian            | 1         | 2      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 32     | 35.14%  |
| WDC                 | 20        | 36     | 27.03%  |
| Hitachi             | 12        | 17     | 16.22%  |
| HGST                | 7         | 10     | 9.46%   |
| Samsung Electronics | 5         | 6      | 6.76%   |
| Toshiba             | 2         | 5      | 2.7%    |
| Maxtor              | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 79        | 112    | 51.63%  |
| HDD  | 72        | 108    | 47.06%  |
| NVMe | 2         | 2      | 1.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-16JJ5T0 320GB               | 1         | 1      | 16.67%  |
| Transcend TS32GSSD370S 32GB                | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 980 250GB          | 1         | 2      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB | 1         | 1      | 16.67%  |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 16.67%  |
| Intel SSDSC2BW120H6 120GB                  | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| Transcend           | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Kingston            | 1         | 1      | 16.67%  |
| Intel               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1389      | 2421   | 86.54%  |
| Malfunc  | 151       | 222    | 9.41%   |
| Detected | 59        | 94     | 3.68%   |
| Failed   | 6         | 7      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1240      | 64.38%  |
| AMD                              | 303       | 15.73%  |
| Samsung Electronics              | 98        | 5.09%   |
| Broadcom / LSI                   | 40        | 2.08%   |
| SanDisk                          | 35        | 1.82%   |
| Kingston Technology Company      | 27        | 1.4%    |
| ASMedia Technology               | 22        | 1.14%   |
| Phison Electronics               | 20        | 1.04%   |
| Nvidia                           | 13        | 0.67%   |
| Silicon Motion                   | 12        | 0.62%   |
| Marvell Technology Group         | 12        | 0.62%   |
| Hewlett-Packard                  | 12        | 0.62%   |
| Transcend                        | 9         | 0.47%   |
| Toshiba                          | 9         | 0.47%   |
| Micron/Crucial Technology        | 9         | 0.47%   |
| Micron Technology                | 9         | 0.47%   |
| KIOXIA                           | 8         | 0.42%   |
| SK hynix                         | 6         | 0.31%   |
| VIA Technologies                 | 4         | 0.21%   |
| JMicron Technology               | 4         | 0.21%   |
| ATP ELECTRONICS                  | 4         | 0.21%   |
| Adaptec                          | 4         | 0.21%   |
| Silicon Image                    | 3         | 0.16%   |
| Shenzhen Longsys Electronics     | 3         | 0.16%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.16%   |
| 3ware                            | 3         | 0.16%   |
| ULi Electronics                  | 2         | 0.1%    |
| ADATA Technology                 | 2         | 0.1%    |
| Yangtze Memory Technologies      | 1         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Enmotus                          | 1         | 0.05%   |
| Chelsio Communications           | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 202       | 9.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 110       | 5.06%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 108       | 4.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 106       | 4.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 65        | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 63        | 2.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 58        | 2.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 58        | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 48        | 2.21%   |
| AMD FCH SATA Controller [IDE mode]                                               | 48        | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 46        | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 41        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 37        | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 36        | 1.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 36        | 1.66%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 34        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 33        | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 25        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 25        | 1.15%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 25        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 24        | 1.1%    |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 24        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 24        | 1.1%    |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 23        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 23        | 1.06%   |
| Unknown                                                                          | 23        | 1.06%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 22        | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 21        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 20        | 0.92%   |
| AMD 400 Series Chipset SATA Controller                                           | 20        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 19        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 19        | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 18        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 17        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17        | 0.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 15        | 0.69%   |
| Intel SATA Controller [RAID mode]                                                | 14        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1386      | 70.18%  |
| NVMe | 255       | 12.91%  |
| IDE  | 217       | 10.99%  |
| RAID | 88        | 4.46%   |
| SAS  | 15        | 0.76%   |
| SCSI | 14        | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1304      | 79.22%  |
| AMD     | 325       | 19.74%  |
| ARM     | 12        | 0.73%   |
| VIA     | 2         | 0.12%   |
| Sun     | 1         | 0.06%   |
| PowerPC | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                          | 95        | 5.73%   |
| Intel Celeron J4125 CPU @ 2.00GHz         | 53        | 3.2%    |
| Intel Celeron CPU J1900 @ 1.99GHz         | 35        | 2.11%   |
| Intel Celeron N5105 @ 2.00GHz             | 28        | 1.69%   |
| Intel Celeron CPU J3160 @ 1.60GHz         | 26        | 1.57%   |
| AMD GX-415GA SOC with Radeon HD Graphics  | 26        | 1.57%   |
| Intel Celeron CPU N3450 @ 1.10GHz         | 24        | 1.45%   |
| Intel Atom CPU D525 @ 1.80GHz             | 16        | 0.97%   |
| Intel Atom CPU C3558 @ 2.20GHz            | 16        | 0.97%   |
| AMD GX-222GC SOC with Radeon R5E Graphics | 16        | 0.97%   |
| Intel Xeon CPU D-1518 @ 2.20GHz           | 15        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz         | 15        | 0.9%    |
| Intel Celeron J4105 CPU @ 1.50GHz         | 14        | 0.84%   |
| Intel Celeron CPU J3455 @ 1.50GHz         | 14        | 0.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz         | 13        | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz         | 13        | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz          | 13        | 0.78%   |
| Intel Celeron N4100 CPU @ 1.10GHz         | 13        | 0.78%   |
| Intel Celeron CPU N3150 @ 1.60GHz         | 13        | 0.78%   |
| Intel Atom CPU C2558 @ 2.40GHz            | 12        | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 11        | 0.66%   |
| AMD G-T40E Processor                      | 11        | 0.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz         | 10        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz         | 10        | 0.6%    |
| Intel Core i3-7100U CPU @ 2.40GHz         | 10        | 0.6%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz  | 9         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 9         | 0.54%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz        | 9         | 0.54%   |
| Intel Celeron CPU N3160 @ 1.60GHz         | 9         | 0.54%   |
| Intel Celeron                             | 9         | 0.54%   |
| AMD Ryzen Embedded V1500B                 | 9         | 0.54%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz       | 8         | 0.48%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 8         | 0.48%   |
| Intel Celeron J4115 CPU @ 1.80GHz         | 8         | 0.48%   |
| Intel Atom CPU N450 @ 1.66GHz             | 8         | 0.48%   |
| AMD GX-420CA SOC with Radeon HD Graphics  | 8         | 0.48%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz       | 7         | 0.42%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz       | 7         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz         | 7         | 0.42%   |
| Intel Pentium CPU G3420 @ 3.20GHz         | 7         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 328       | 19.84%  |
| Intel Core i5           | 266       | 16.09%  |
| Intel Xeon              | 160       | 9.68%   |
| AMD GX                  | 158       | 9.56%   |
| Intel Core i7           | 128       | 7.74%   |
| Intel Atom              | 127       | 7.68%   |
| Intel Core i3           | 125       | 7.56%   |
| Other                   | 45        | 2.72%   |
| Intel Pentium           | 42        | 2.54%   |
| AMD Ryzen 7             | 30        | 1.81%   |
| Intel Core 2 Duo        | 28        | 1.69%   |
| AMD Ryzen 5             | 26        | 1.57%   |
| Intel Pentium Silver    | 22        | 1.33%   |
| AMD G                   | 17        | 1.03%   |
| AMD FX                  | 15        | 0.91%   |
| AMD Ryzen Embedded      | 12        | 0.73%   |
| ARM Cortex              | 10        | 0.6%    |
| AMD EPYC                | 10        | 0.6%    |
| Intel Core 2 Quad       | 9         | 0.54%   |
| Intel Pentium Gold      | 8         | 0.48%   |
| Intel Pentium Dual-Core | 7         | 0.42%   |
| AMD Ryzen 5 PRO         | 6         | 0.36%   |
| AMD Ryzen 3             | 6         | 0.36%   |
| AMD Ryzen 9             | 5         | 0.3%    |
| AMD E                   | 4         | 0.24%   |
| Intel Xeon Silver       | 3         | 0.18%   |
| Intel Xeon Gold         | 3         | 0.18%   |
| Intel Pentium M         | 3         | 0.18%   |
| Intel Pentium Dual      | 3         | 0.18%   |
| Intel Genuine           | 3         | 0.18%   |
| Intel Core i9           | 3         | 0.18%   |
| Intel Core 2            | 3         | 0.18%   |
| AMD Turion II Neo       | 3         | 0.18%   |
| AMD Ryzen 7 PRO         | 3         | 0.18%   |
| AMD Athlon 64 X2        | 3         | 0.18%   |
| AMD A4                  | 3         | 0.18%   |
| AMD A10                 | 3         | 0.18%   |
| Intel Pentium 4         | 2         | 0.12%   |
| AMD Ryzen Threadripper  | 2         | 0.12%   |
| AMD Athlon Dual Core    | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 860       | 52%     |
| 2       | 492       | 29.75%  |
| 8       | 84        | 5.08%   |
| Unknown | 58        | 3.51%   |
| 6       | 53        | 3.2%    |
| 16      | 39        | 2.36%   |
| 12      | 32        | 1.93%   |
| 1       | 24        | 1.45%   |
| 32      | 5         | 0.3%    |
| 10      | 3         | 0.18%   |
| 128     | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 24      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1575      | 95.63%  |
| 2       | 49        | 2.98%   |
| Unknown | 23        | 1.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 988       | 59.92%  |
| 2       | 594       | 36.02%  |
| Unknown | 67        | 4.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 217       | 13.15%  |
| Silvermont    | 153       | 9.27%   |
| Haswell       | 147       | 8.91%   |
| Puma          | 123       | 7.45%   |
| Goldmont plus | 109       | 6.61%   |
| Skylake       | 98        | 5.94%   |
| IvyBridge     | 92        | 5.58%   |
| Unknown       | 88        | 5.33%   |
| Goldmont      | 85        | 5.15%   |
| SandyBridge   | 65        | 3.94%   |
| Penryn        | 52        | 3.15%   |
| Broadwell     | 50        | 3.03%   |
| Bonnell       | 46        | 2.79%   |
| Jaguar        | 39        | 2.36%   |
| Zen           | 34        | 2.06%   |
| Westmere      | 32        | 1.94%   |
| Core          | 29        | 1.76%   |
| Zen 2         | 27        | 1.64%   |
| Zen+          | 24        | 1.45%   |
| Bobcat        | 22        | 1.33%   |
| Nehalem       | 17        | 1.03%   |
| CometLake     | 17        | 1.03%   |
| Piledriver    | 16        | 0.97%   |
| TigerLake     | 15        | 0.91%   |
| Zen 3         | 11        | 0.67%   |
| IceLake       | 10        | 0.61%   |
| K8 Hammer     | 6         | 0.36%   |
| K10           | 5         | 0.3%    |
| Steamroller   | 4         | 0.24%   |
| P6            | 4         | 0.24%   |
| NetBurst      | 4         | 0.24%   |
| Bulldozer     | 4         | 0.24%   |
| Excavator     | 3         | 0.18%   |
| K10 Llano     | 1         | 0.06%   |
| Geode         | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1001      | 65.08%  |
| AMD                                          | 191       | 12.42%  |
| ASPEED Technology                            | 136       | 8.84%   |
| Nvidia                                       | 129       | 8.39%   |
| Matrox Electronics Systems                   | 76        | 4.94%   |
| VIA Technologies                             | 2         | 0.13%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.07%   |
| Trident Microsystems                         | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 136       | 8.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 93        | 5.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 65        | 4.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 62        | 3.97%   |
| Intel HD Graphics 500                                                                    | 57        | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 51        | 3.27%   |
| Intel HD Graphics 620                                                                    | 43        | 2.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 40        | 2.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 38        | 2.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 2.37%   |
| Intel HD Graphics 530                                                                    | 33        | 2.11%   |
| Intel UHD Graphics 620                                                                   | 32        | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 1.92%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 30        | 1.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 28        | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 1.73%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 26        | 1.66%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 26        | 1.66%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.28%   |
| Matrox Electronics Systems MGA G200EH                                                    | 19        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 1.09%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 16        | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 16        | 1.02%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 16        | 1.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 0.96%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 15        | 0.96%   |
| Intel HD Graphics 630                                                                    | 14        | 0.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 12        | 0.77%   |
| Intel HD Graphics 510                                                                    | 11        | 0.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 0.7%    |
| AMD Renoir                                                                               | 11        | 0.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 0.64%   |
| AMD ES1000                                                                               | 10        | 0.64%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 9         | 0.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 884       | 53.61%  |
| 1 x AMD                  | 182       | 11.04%  |
| Other                    | 167       | 10.13%  |
| 1 x ASPEED               | 125       | 7.58%   |
| 1 x Nvidia               | 90        | 5.46%   |
| 1 x Matrox               | 74        | 4.49%   |
| 2 x Intel                | 64        | 3.88%   |
| Intel + Nvidia           | 36        | 2.18%   |
| Intel + ASPEED           | 10        | 0.61%   |
| Intel + AMD              | 5         | 0.3%    |
| AMD + Nvidia             | 3         | 0.18%   |
| 1 x VIA                  | 2         | 0.12%   |
| Intel + Matrox           | 2         | 0.12%   |
| 2 x AMD                  | 1         | 0.06%   |
| 1 x XGI                  | 1         | 0.06%   |
| 1 x Trident Microsystems | 1         | 0.06%   |
| 1 x SiS                  | 1         | 0.06%   |
| Nvidia + ASPEED          | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1394      | 84.43%  |
| Unknown     | 188       | 11.39%  |
| Proprietary | 69        | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1554      | 93.73%  |
| 1.01-2.0   | 30        | 1.81%   |
| 0.01-0.5   | 26        | 1.57%   |
| 3.01-4.0   | 16        | 0.97%   |
| 7.01-8.0   | 12        | 0.72%   |
| 5.01-6.0   | 8         | 0.48%   |
| 0.51-1.0   | 8         | 0.48%   |
| 2.01-3.0   | 4         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 34        | 11.33%  |
| AU Optronics            | 33        | 11%     |
| Samsung Electronics     | 29        | 9.67%   |
| Dell                    | 20        | 6.67%   |
| Apple                   | 19        | 6.33%   |
| Goldstar                | 17        | 5.67%   |
| Chimei Innolux          | 16        | 5.33%   |
| BenQ                    | 15        | 5%      |
| Lenovo                  | 13        | 4.33%   |
| BOE                     | 13        | 4.33%   |
| Ancor Communications    | 10        | 3.33%   |
| Acer                    | 8         | 2.67%   |
| Eizo                    | 7         | 2.33%   |
| Sharp                   | 6         | 2%      |
| LG Electronics          | 6         | 2%      |
| Iiyama                  | 6         | 2%      |
| Hewlett-Packard         | 6         | 2%      |
| AOC                     | 5         | 1.67%   |
| NEC Computers           | 4         | 1.33%   |
| PANDA                   | 3         | 1%      |
| InfoVision              | 3         | 1%      |
| Idek Iiyama             | 3         | 1%      |
| Philips                 | 2         | 0.67%   |
| HannStar                | 2         | 0.67%   |
| Fujitsu Siemens         | 2         | 0.67%   |
| Belinea                 | 2         | 0.67%   |
| ASUSTek Computer        | 2         | 0.67%   |
| Unknown                 | 2         | 0.67%   |
| WYT                     | 1         | 0.33%   |
| TRU                     | 1         | 0.33%   |
| Toshiba                 | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| Mi                      | 1         | 0.33%   |
| Medion                  | 1         | 0.33%   |
| LTM                     | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| JDI                     | 1         | 0.33%   |
| CSO                     | 1         | 0.33%   |
| Chi Mei Optoelectronics | 1         | 0.33%   |
| CHD                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 1.6%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 4         | 1.28%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 0.96%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 3         | 0.96%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.64%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch    | 2         | 0.64%   |
| Samsung Electronics C32JG5x SAM0FDE 2560x1440 700x390mm 31.5-inch    | 2         | 0.64%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.64%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.64%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.64%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 2         | 0.64%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 520x320mm 24.0-inch         | 2         | 0.64%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 2         | 0.64%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.64%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                 | 2         | 0.64%   |
| Eizo EV2450 ENC2530 1920x1080 530x300mm 24.0-inch                    | 2         | 0.64%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 2         | 0.64%   |
| Dell LCD Monitor U2412M 3840x1200                                    | 2         | 0.64%   |
| Dell LCD Monitor U2412M                                              | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.64%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 2         | 0.64%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 2         | 0.64%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 2         | 0.64%   |
| BenQ GL2760 BNQ78D5 1920x1080 600x340mm 27.2-inch                    | 2         | 0.64%   |
| BenQ GL2450H BNQ78A6 1920x1080 530x300mm 24.0-inch                   | 2         | 0.64%   |
| BenQ BL2405 BNQ8016 1920x1080 530x300mm 24.0-inch                    | 2         | 0.64%   |
| Belinea LCD Monitor MAX0776 1280x1024 380x300mm 19.1-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 2         | 0.64%   |
| AOC U3277WB AOC3277 3840x2160 700x390mm 31.5-inch                    | 2         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 36.91%  |
| 1366x768 (WXGA)    | 47        | 15.77%  |
| 2560x1440 (QHD)    | 28        | 9.4%    |
| 3840x2160 (4K)     | 23        | 7.72%   |
| 1920x1200 (WUXGA)  | 19        | 6.38%   |
| 1680x1050 (WSXGA+) | 10        | 3.36%   |
| 1280x800 (WXGA)    | 10        | 3.36%   |
| 1280x1024 (SXGA)   | 10        | 3.36%   |
| 1600x900 (HD+)     | 7         | 2.35%   |
| 1440x900 (WXGA+)   | 7         | 2.35%   |
| 3440x1440          | 4         | 1.34%   |
| 2560x1080          | 3         | 1.01%   |
| Unknown            | 3         | 1.01%   |
| 3840x1200          | 2         | 0.67%   |
| 3200x1800 (QHD+)   | 2         | 0.67%   |
| 2880x1800          | 2         | 0.67%   |
| 2560x1600          | 2         | 0.67%   |
| 1024x768 (XGA)     | 2         | 0.67%   |
| 9600x2160          | 1         | 0.34%   |
| 720x1280           | 1         | 0.34%   |
| 3840x1080          | 1         | 0.34%   |
| 3600x1080          | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2880x1620          | 1         | 0.34%   |
| 1920x540           | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 58        | 19.4%   |
| 15      | 43        | 14.38%  |
| 24      | 35        | 11.71%  |
| 27      | 33        | 11.04%  |
| Unknown | 26        | 8.7%    |
| 12      | 23        | 7.69%   |
| 23      | 14        | 4.68%   |
| 21      | 12        | 4.01%   |
| 11      | 8         | 2.68%   |
| 14      | 7         | 2.34%   |
| 22      | 6         | 2.01%   |
| 19      | 6         | 2.01%   |
| 17      | 6         | 2.01%   |
| 34      | 5         | 1.67%   |
| 31      | 4         | 1.34%   |
| 20      | 3         | 1%      |
| 32      | 2         | 0.67%   |
| 25      | 2         | 0.67%   |
| 46      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |
| 18      | 1         | 0.33%   |
| 16      | 1         | 0.33%   |
| 6       | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 27.85%  |
| 501-600     | 79        | 26.51%  |
| 201-300     | 59        | 19.8%   |
| Unknown     | 26        | 8.72%   |
| 401-500     | 22        | 7.38%   |
| 351-400     | 10        | 3.36%   |
| 601-700     | 9         | 3.02%   |
| 701-800     | 7         | 2.35%   |
| 801-900     | 1         | 0.34%   |
| 101-200     | 1         | 0.34%   |
| 1001-1500   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 195       | 68.18%  |
| 16/10   | 47        | 16.43%  |
| Unknown | 25        | 8.74%   |
| 5/4     | 7         | 2.45%   |
| 21/9    | 5         | 1.75%   |
| 4/3     | 3         | 1.05%   |
| 3/2     | 3         | 1.05%   |
| 6/5     | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 17.06%  |
| 201-250        | 50        | 16.72%  |
| 301-350        | 34        | 11.37%  |
| 91-100         | 31        | 10.37%  |
| Unknown        | 26        | 8.7%    |
| 61-70          | 23        | 7.69%   |
| 251-300        | 18        | 6.02%   |
| 71-80          | 13        | 4.35%   |
| 101-110        | 13        | 4.35%   |
| 351-500        | 11        | 3.68%   |
| 151-200        | 11        | 3.68%   |
| 51-60          | 8         | 2.68%   |
| 121-130        | 4         | 1.34%   |
| 141-150        | 2         | 0.67%   |
| 501-1000       | 2         | 0.67%   |
| 1-40           | 1         | 0.33%   |
| 131-140        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 92        | 31.29%  |
| 121-160       | 83        | 28.23%  |
| 101-120       | 54        | 18.37%  |
| 161-240       | 28        | 9.52%   |
| Unknown       | 26        | 8.84%   |
| More than 240 | 10        | 3.4%    |
| 1-50          | 1         | 0.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1348      | 81.4%   |
| 1     | 277       | 16.73%  |
| 2     | 29        | 1.75%   |
| 3     | 2         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1309      | 57.97%  |
| Realtek Semiconductor             | 521       | 23.07%  |
| Broadcom                          | 128       | 5.67%   |
| Qualcomm Atheros                  | 105       | 4.65%   |
| IMC Networks                      | 15        | 0.66%   |
| AMD                               | 15        | 0.66%   |
| Ericsson Business Mobile Networks | 12        | 0.53%   |
| Ralink Technology                 | 11        | 0.49%   |
| Marvell Technology Group          | 11        | 0.49%   |
| TP-Link                           | 9         | 0.4%    |
| Mellanox Technologies             | 9         | 0.4%    |
| Edimax Technology                 | 9         | 0.4%    |
| Ralink                            | 8         | 0.35%   |
| Nvidia                            | 8         | 0.35%   |
| D-Link System                     | 7         | 0.31%   |
| American Megatrends               | 7         | 0.31%   |
| Sierra Wireless                   | 5         | 0.22%   |
| MediaTek                          | 5         | 0.22%   |
| Google                            | 5         | 0.22%   |
| U-Blox                            | 4         | 0.18%   |
| IBM                               | 4         | 0.18%   |
| Emulex                            | 4         | 0.18%   |
| Dell                              | 4         | 0.18%   |
| Chelsio Communications            | 3         | 0.13%   |
| ASUSTek Computer                  | 3         | 0.13%   |
| Aquantia                          | 3         | 0.13%   |
| Samsung Electronics               | 2         | 0.09%   |
| Qualcomm Atheros Communications   | 2         | 0.09%   |
| NetXen Incorporated               | 2         | 0.09%   |
| ICS Advent                        | 2         | 0.09%   |
| Huawei Technologies               | 2         | 0.09%   |
| Hewlett-Packard                   | 2         | 0.09%   |
| Dresden Elektronik                | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| Xiaomi                            | 1         | 0.04%   |
| ULi Electronics                   | 1         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.04%   |
| SysKonnect                        | 1         | 0.04%   |
| Standard Microsystems [SMC]       | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 459       | 16.4%   |
| Intel I211 Gigabit Network Connection                                         | 282       | 10.08%  |
| Intel I210 Gigabit Network Connection                                         | 229       | 8.18%   |
| Intel I350 Gigabit Network Connection                                         | 116       | 4.14%   |
| Intel 82574L Gigabit Network Connection                                       | 74        | 2.64%   |
| Intel Ethernet Controller I225-V                                              | 67        | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 62        | 2.22%   |
| Intel 82580 Gigabit Network Connection                                        | 37        | 1.32%   |
| Intel 82583V Gigabit Network Connection                                       | 35        | 1.25%   |
| Intel 82576 Gigabit Network Connection                                        | 34        | 1.21%   |
| Intel Wireless 3165                                                           | 32        | 1.14%   |
| Intel Wi-Fi 6 AX200                                                           | 32        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                             | 28        | 1%      |
| Intel Wireless 7265                                                           | 27        | 0.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 27        | 0.96%   |
| Intel Ethernet Connection I354                                                | 25        | 0.89%   |
| Intel Ethernet Connection I217-LM                                             | 25        | 0.89%   |
| Intel Wireless 8265 / 8275                                                    | 24        | 0.86%   |
| Intel Ethernet Connection X553 1GbE                                           | 24        | 0.86%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 23        | 0.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 23        | 0.82%   |
| Intel Ethernet Connection I219-LM                                             | 22        | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 22        | 0.79%   |
| Intel Ethernet Controller I226-V                                              | 21        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 20        | 0.71%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 20        | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 19        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                         | 19        | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 18        | 0.64%   |
| Intel Wireless 7260                                                           | 16        | 0.57%   |
| Intel Wireless 8260                                                           | 15        | 0.54%   |
| Intel Wireless 3160                                                           | 15        | 0.54%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 15        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                          | 15        | 0.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 15        | 0.54%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 15        | 0.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 14        | 0.5%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 14        | 0.5%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 13        | 0.46%   |
| Intel Wireless-AC 9260                                                        | 12        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 308       | 54.51%  |
| Qualcomm Atheros                | 92        | 16.28%  |
| Realtek Semiconductor           | 55        | 9.73%   |
| Broadcom                        | 40        | 7.08%   |
| IMC Networks                    | 15        | 2.65%   |
| Ralink Technology               | 11        | 1.95%   |
| TP-Link                         | 9         | 1.59%   |
| Edimax Technology               | 9         | 1.59%   |
| Ralink                          | 8         | 1.42%   |
| Sierra Wireless                 | 5         | 0.88%   |
| MediaTek                        | 5         | 0.88%   |
| ASUSTek Computer                | 3         | 0.53%   |
| Qualcomm Atheros Communications | 2         | 0.35%   |
| Micro Star International        | 1         | 0.18%   |
| Dell                            | 1         | 0.18%   |
| Accton Technology               | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                             | 32        | 5.62%   |
| Intel Wi-Fi 6 AX200                                             | 32        | 5.62%   |
| Intel Wireless 7265                                             | 27        | 4.75%   |
| Intel Wireless 8265 / 8275                                      | 24        | 4.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 20        | 3.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 19        | 3.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 18        | 3.16%   |
| Intel Wireless 7260                                             | 16        | 2.81%   |
| Intel Wireless 8260                                             | 15        | 2.64%   |
| Intel Wireless 3160                                             | 15        | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 14        | 2.46%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 14        | 2.46%   |
| Intel Wireless-AC 9260                                          | 12        | 2.11%   |
| Intel Centrino Ultimate-N 6300                                  | 12        | 2.11%   |
| Intel Centrino Advanced-N 6235                                  | 11        | 1.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 10        | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 9         | 1.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 9         | 1.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 9         | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 8         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 8         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 7         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 7         | 1.23%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 7         | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 7         | 1.23%   |
| Intel Wi-Fi 6 AX201                                             | 7         | 1.23%   |
| Broadcom BCM4321 802.11a/b/g/n                                  | 7         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 6         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 6         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 6         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 5         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 5         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 5         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 5         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 5         | 0.88%   |
| Sierra Wireless EM7455                                          | 4         | 0.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 4         | 0.7%    |
| Ralink RT5572 Wireless Adapter                                  | 4         | 0.7%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                       | 4         | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection   | 4         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 1144      | 62.55%  |
| Realtek Semiconductor       | 501       | 27.39%  |
| Broadcom                    | 96        | 5.25%   |
| Qualcomm Atheros            | 16        | 0.87%   |
| AMD                         | 15        | 0.82%   |
| Marvell Technology Group    | 11        | 0.6%    |
| Nvidia                      | 8         | 0.44%   |
| American Megatrends         | 7         | 0.38%   |
| Google                      | 5         | 0.27%   |
| D-Link System               | 4         | 0.22%   |
| Emulex                      | 3         | 0.16%   |
| Aquantia                    | 3         | 0.16%   |
| Samsung Electronics         | 2         | 0.11%   |
| ICS Advent                  | 2         | 0.11%   |
| Xiaomi                      | 1         | 0.05%   |
| T & A Mobile Phones         | 1         | 0.05%   |
| SysKonnect                  | 1         | 0.05%   |
| Standard Microsystems [SMC] | 1         | 0.05%   |
| QLogic                      | 1         | 0.05%   |
| National Semiconductor      | 1         | 0.05%   |
| JMicron Technology          | 1         | 0.05%   |
| Insyde Software             | 1         | 0.05%   |
| Digital Equipment           | 1         | 0.05%   |
| Davicom Semiconductor       | 1         | 0.05%   |
| Chelsio Communications      | 1         | 0.05%   |
| Apple                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 459       | 21.18%  |
| Intel I211 Gigabit Network Connection                                         | 282       | 13.01%  |
| Intel I210 Gigabit Network Connection                                         | 229       | 10.57%  |
| Intel I350 Gigabit Network Connection                                         | 116       | 5.35%   |
| Intel 82574L Gigabit Network Connection                                       | 74        | 3.41%   |
| Intel Ethernet Controller I225-V                                              | 67        | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 62        | 2.86%   |
| Intel 82580 Gigabit Network Connection                                        | 37        | 1.71%   |
| Intel 82583V Gigabit Network Connection                                       | 35        | 1.62%   |
| Intel 82576 Gigabit Network Connection                                        | 34        | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                             | 27        | 1.25%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 27        | 1.25%   |
| Intel Ethernet Connection I354                                                | 25        | 1.15%   |
| Intel Ethernet Connection I217-LM                                             | 25        | 1.15%   |
| Intel Ethernet Connection X553 1GbE                                           | 24        | 1.11%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 23        | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 23        | 1.06%   |
| Intel Ethernet Connection I219-LM                                             | 22        | 1.02%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 22        | 1.02%   |
| Intel Ethernet Controller I226-V                                              | 21        | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 20        | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                         | 19        | 0.88%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 15        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 15        | 0.69%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 15        | 0.69%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 15        | 0.69%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 13        | 0.6%    |
| Intel Ethernet Controller X550                                                | 12        | 0.55%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 12        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                          | 12        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                                         | 12        | 0.55%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 12        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                                          | 11        | 0.51%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 11        | 0.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 10        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                                      | 10        | 0.46%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 9         | 0.42%   |
| Intel Ethernet Connection I217-V                                              | 9         | 0.42%   |
| Nvidia MCP79 Ethernet                                                         | 8         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1603      | 73.26%  |
| WiFi     | 526       | 24.04%  |
| Unknown  | 35        | 1.6%    |
| Modem    | 24        | 1.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1533      | 88.72%  |
| WiFi     | 185       | 10.71%  |
| Unknown  | 9         | 0.52%   |
| Modem    | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 409       | 24.56%  |
| 4     | 317       | 19.04%  |
| 3     | 264       | 15.86%  |
| 1     | 203       | 12.19%  |
| 6     | 186       | 11.17%  |
| 5     | 119       | 7.15%   |
| 8     | 74        | 4.44%   |
| 10    | 28        | 1.68%   |
| 7     | 22        | 1.32%   |
| 0     | 16        | 0.96%   |
| 9     | 12        | 0.72%   |
| 12    | 8         | 0.48%   |
| 14    | 3         | 0.18%   |
| 20    | 1         | 0.06%   |
| 17    | 1         | 0.06%   |
| 16    | 1         | 0.06%   |
| 11    | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1360      | 79.53%  |
| Yes  | 350       | 20.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 202       | 58.89%  |
| Qualcomm Atheros Communications | 25        | 7.29%   |
| Apple                           | 25        | 7.29%   |
| IMC Networks                    | 24        | 7%      |
| Broadcom                        | 21        | 6.12%   |
| Realtek Semiconductor           | 14        | 4.08%   |
| Foxconn / Hon Hai               | 8         | 2.33%   |
| ASUSTek Computer                | 7         | 2.04%   |
| Cambridge Silicon Radio         | 4         | 1.17%   |
| MediaTek                        | 3         | 0.87%   |
| Lite-On Technology              | 3         | 0.87%   |
| Dell                            | 3         | 0.87%   |
| Alps Electric                   | 2         | 0.58%   |
| Micro Star International        | 1         | 0.29%   |
| Hewlett-Packard                 | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 88        | 25.58%  |
| Intel AX200 Bluetooth                                       | 34        | 9.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 26        | 7.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 15        | 4.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 12        | 3.49%   |
| Intel AX201 Bluetooth                                       | 12        | 3.49%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 10        | 2.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 9         | 2.62%   |
| Apple Bluetooth Host Controller                             | 9         | 2.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                            | 8         | 2.33%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 2.33%   |
| Intel AX210 Bluetooth                                       | 7         | 2.03%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 6         | 1.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 1.74%   |
| Realtek Bluetooth Adapter                                   | 5         | 1.45%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 1.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 1.16%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 0.87%   |
| MediaTek RZ608 Bluetooth Adapter                            | 3         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 0.87%   |
| ASUS USB-BT500                                              | 3         | 0.87%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 0.58%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 0.58%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 2         | 0.58%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 2         | 0.58%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 2         | 0.58%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.58%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.58%   |
| Broadcom BCM2045 Bluetooth                                  | 2         | 0.58%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 0.58%   |
| Apple Bluetooth USB Host Controller                         | 2         | 0.58%   |
| Apple Bluetooth HCI                                         | 2         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.29%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.29%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.29%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.29%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 884       | 70.66%  |
| AMD                                          | 213       | 17.03%  |
| Nvidia                                       | 90        | 7.19%   |
| C-Media Electronics                          | 13        | 1.04%   |
| Logitech                                     | 6         | 0.48%   |
| GN Netcom                                    | 5         | 0.4%    |
| Texas Instruments                            | 4         | 0.32%   |
| JMTek                                        | 4         | 0.32%   |
| VIA Technologies                             | 3         | 0.24%   |
| Tenx Technology                              | 3         | 0.24%   |
| Creative Labs                                | 3         | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.16%   |
| Kingston Technology                          | 2         | 0.16%   |
| Corsair                                      | 2         | 0.16%   |
| ZOOM                                         | 1         | 0.08%   |
| Yamaha                                       | 1         | 0.08%   |
| ULi Electronics                              | 1         | 0.08%   |
| Trust                                        | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.08%   |
| RME                                          | 1         | 0.08%   |
| Phison Electronics                           | 1         | 0.08%   |
| Native Instruments                           | 1         | 0.08%   |
| M-Audio                                      | 1         | 0.08%   |
| Lenovo                                       | 1         | 0.08%   |
| Hewlett-Packard                              | 1         | 0.08%   |
| Generalplus Technology                       | 1         | 0.08%   |
| ESS Technology                               | 1         | 0.08%   |
| Creative Technology                          | 1         | 0.08%   |
| Blue Microphones                             | 1         | 0.08%   |
| AudioQuest                                   | 1         | 0.08%   |
| Audient                                      | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 101       | 6.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 95        | 6.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 71        | 4.83%   |
| AMD Kabini HDMI/DP Audio                                                                          | 62        | 4.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 55        | 3.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 53        | 3.61%   |
| AMD FCH Azalia Controller                                                                         | 52        | 3.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 51        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 45        | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 44        | 3%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 2.86%   |
| Intel Jasper Lake HD Audio                                                                        | 40        | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 40        | 2.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 2.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 34        | 2.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 34        | 2.31%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 1.84%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 1.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 25        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 23        | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 20        | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.36%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 18        | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 1.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 16        | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 8         | 0.54%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 8         | 0.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.54%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 7         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 303       | 18.48%  |
| Unknown                      | 234       | 14.27%  |
| Kingston                     | 199       | 12.13%  |
| Crucial                      | 179       | 10.91%  |
| SK hynix                     | 162       | 9.88%   |
| Micron Technology            | 127       | 7.74%   |
| G.Skill                      | 81        | 4.94%   |
| Corsair                      | 55        | 3.35%   |
| Unknown                      | 54        | 3.29%   |
| Unknown (ABCD)               | 36        | 2.2%    |
| Transcend                    | 35        | 2.13%   |
| A-DATA Technology            | 30        | 1.83%   |
| Nanya Technology             | 21        | 1.28%   |
| ATP                          | 20        | 1.22%   |
| Ramaxel Technology           | 15        | 0.91%   |
| Hewlett-Packard              | 13        | 0.79%   |
| Apacer                       | 10        | 0.61%   |
| Elpida                       | 8         | 0.49%   |
| Toshiba                      | 6         | 0.37%   |
| Kimtigo                      | 5         | 0.3%    |
| Shenzhen Jinge Information   | 3         | 0.18%   |
| Patriot                      | 3         | 0.18%   |
| Innodisk                     | 3         | 0.18%   |
| Avant                        | 3         | 0.18%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 2         | 0.12%   |
| Unknown (09C7)               | 2         | 0.12%   |
| Tigo                         | 2         | 0.12%   |
| Teikon                       | 2         | 0.12%   |
| PNY                          | 2         | 0.12%   |
| HPE                          | 2         | 0.12%   |
| GeIL                         | 2         | 0.12%   |
| 019400B300CE                 | 2         | 0.12%   |
| Vasekey                      | 1         | 0.06%   |
| Unknown (8A5D)               | 1         | 0.06%   |
| Unknown (8A02)               | 1         | 0.06%   |
| Unknown (7F7F7F94FFFFFFFF)   | 1         | 0.06%   |
| Unknown (0x1636)             | 1         | 0.06%   |
| Unknown (0x0C26)             | 1         | 0.06%   |
| Unknown (00000000FFFF)       | 1         | 0.06%   |
| Timetec                      | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 54        | 3.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 40        | 2.32%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 36        | 2.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 15        | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 14        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 12        | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 11        | 0.64%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 10        | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 10        | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 10        | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 9         | 0.52%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 9         | 0.52%   |
| G.Skill RAM F4-2400C16-8GRS 8GB SODIMM DDR4 2400MT/s           | 9         | 0.52%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 8         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 8         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s          | 8         | 0.46%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 8         | 0.46%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 8         | 0.46%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 8         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 7         | 0.41%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 7         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 7         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 7         | 0.41%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 7         | 0.41%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s           | 7         | 0.41%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 7         | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 7         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 6         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 6         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 6         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                       | 6         | 0.35%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 6         | 0.35%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 6         | 0.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 6         | 0.35%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s              | 6         | 0.35%   |
| G.Skill RAM F4-2400C16-4GRS 4GB SODIMM DDR4 2400MT/s           | 6         | 0.35%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s         | 6         | 0.35%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s          | 6         | 0.35%   |
| ATP RAM X4G08QA8BNWESO-7-TO1 8GB SODIMM DDR4 3200MT/s          | 6         | 0.35%   |
| ATP RAM AW12P6438BLK0S 4GB DIMM DDR3 1600MT/s                  | 6         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 700       | 46.82%  |
| DDR4    | 592       | 39.6%   |
| DDR2    | 75        | 5.02%   |
| LPDDR4  | 52        | 3.48%   |
| Unknown | 35        | 2.34%   |
| SDRAM   | 21        | 1.4%    |
| DDR     | 10        | 0.67%   |
| LPDDR3  | 7         | 0.47%   |
| RAM     | 1         | 0.07%   |
| DRAM    | 1         | 0.07%   |
| DDR5    | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 749       | 50.4%   |
| DIMM         | 700       | 47.11%  |
| Row Of Chips | 25        | 1.68%   |
| Unknown      | 6         | 0.4%    |
| Chip         | 5         | 0.34%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 574       | 36.42%  |
| 4096  | 515       | 32.68%  |
| 16384 | 221       | 14.02%  |
| 2048  | 202       | 12.82%  |
| 1024  | 31        | 1.97%   |
| 32768 | 26        | 1.65%   |
| 512   | 4         | 0.25%   |
| 256   | 2         | 0.13%   |
| 65536 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 439       | 28.07%  |
| 2400    | 232       | 14.83%  |
| 1333    | 210       | 13.43%  |
| 2667    | 165       | 10.55%  |
| 3200    | 134       | 8.57%   |
| 2133    | 81        | 5.18%   |
| 800     | 54        | 3.45%   |
| 667     | 54        | 3.45%   |
| Unknown | 29        | 1.85%   |
| 1867    | 26        | 1.66%   |
| 2666    | 23        | 1.47%   |
| 1334    | 20        | 1.28%   |
| 1066    | 20        | 1.28%   |
| 1067    | 17        | 1.09%   |
| 1866    | 16        | 1.02%   |
| 3000    | 11        | 0.7%    |
| 2933    | 10        | 0.64%   |
| 3600    | 5         | 0.32%   |
| 4267    | 4         | 0.26%   |
| 533     | 4         | 0.26%   |
| 65535   | 1         | 0.06%   |
| 4800    | 1         | 0.06%   |
| 3534    | 1         | 0.06%   |
| 3500    | 1         | 0.06%   |
| 2600    | 1         | 0.06%   |
| 1419    | 1         | 0.06%   |
| 1033    | 1         | 0.06%   |
| 975     | 1         | 0.06%   |
| 400     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Ricoh               | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother MFC-7360N             | 2         | 28.57%  |
| Ricoh SP 112                  | 1         | 14.29%  |
| QinHeng CH340S                | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| HP HP LaserJet P2035 HP Print | 1         | 14.29%  |
| Brother HL-L2310D series      | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 31.82%  |
| Bison Electronics                      | 20        | 11.36%  |
| Microdia                               | 12        | 6.82%   |
| Realtek Semiconductor                  | 11        | 6.25%   |
| IMC Networks                           | 11        | 6.25%   |
| Logitech                               | 10        | 5.68%   |
| Suyin                                  | 9         | 5.11%   |
| Lite-On Technology                     | 8         | 4.55%   |
| Sunplus Innovation Technology          | 6         | 3.41%   |
| Apple                                  | 6         | 3.41%   |
| Syntek                                 | 4         | 2.27%   |
| Lenovo                                 | 4         | 2.27%   |
| Alcor Micro                            | 4         | 2.27%   |
| Z-Star Microelectronics                | 2         | 1.14%   |
| Quanta                                 | 2         | 1.14%   |
| ARC International                      | 2         | 1.14%   |
| Trust                                  | 1         | 0.57%   |
| Tripath Technology                     | 1         | 0.57%   |
| Silicon Motion                         | 1         | 0.57%   |
| Ricoh                                  | 1         | 0.57%   |
| Pixart Imaging                         | 1         | 0.57%   |
| Luxvisions Innotech Limited            | 1         | 0.57%   |
| Intel                                  | 1         | 0.57%   |
| Cubeternet                             | 1         | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 26        | 14.69%  |
| Bison Integrated Camera                  | 9         | 5.08%   |
| IMC Networks Integrated Camera           | 6         | 3.39%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 6         | 3.39%   |
| Microdia Integrated Webcam               | 5         | 2.82%   |
| Lite-On Integrated Camera                | 5         | 2.82%   |
| Chicony FJ Camera                        | 5         | 2.82%   |
| Chicony HD Webcam                        | 4         | 2.26%   |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.26%   |
| Suyin RGBIR Camera                       | 3         | 1.69%   |
| Realtek USB 2.0 PC Camera                | 3         | 1.69%   |
| Syntek Integrated Camera                 | 2         | 1.13%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.13%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.13%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.13%   |
| Logitech Webcam C270                     | 2         | 1.13%   |
| Logitech HD Pro Webcam C920              | 2         | 1.13%   |
| Logitech C920 PRO HD Webcam              | 2         | 1.13%   |
| Logitech C920 HD Pro Webcam              | 2         | 1.13%   |
| Lite-On Realtek PC Camera                | 2         | 1.13%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.13%   |
| IMC Networks Realtek PC Camera           | 2         | 1.13%   |
| Chicony HP HD Webcam [Fixed]             | 2         | 1.13%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.13%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.13%   |
| Bison ThinkPad Integrated Camera         | 2         | 1.13%   |
| Bison SunplusIT Integrated Camera        | 2         | 1.13%   |
| Bison SunplusIT INC. Integrated Camera   | 2         | 1.13%   |
| Bison Lenovo EasyCamera                  | 2         | 1.13%   |
| ARC International Camera                 | 2         | 1.13%   |
| Alcor Micro Lenovo EasyCamera            | 2         | 1.13%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.56%   |
| Z-Star Lenovo USB 2.0 UVC Camera         | 1         | 0.56%   |
| Trust Trust USB Camera                   | 1         | 0.56%   |
| Tripath PC Camera                        | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.56%   |
| Syntek EasyCamera                        | 1         | 0.56%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.56%   |
| Suyin Integrated Webcam                  | 1         | 0.56%   |
| Suyin HP Webcam-101                      | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 37.1%   |
| Synaptics                  | 11        | 17.74%  |
| Upek                       | 9         | 14.52%  |
| AuthenTec                  | 5         | 8.06%   |
| LighTuning Technology      | 4         | 6.45%   |
| Shenzhen Goodix Technology | 3         | 4.84%   |
| Broadcom                   | 3         | 4.84%   |
| STMicroelectronics         | 2         | 3.23%   |
| Next Biometrics            | 1         | 1.61%   |
| DigitalPersona             | 1         | 1.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 8         | 12.9%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 8         | 12.9%   |
| Validity Sensors Synaptics WBDI                                              | 7         | 11.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 5         | 8.06%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 4.84%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.84%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 3.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 3.23%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 3.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 3.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.61%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.61%   |
| Synaptics WBDI                                                               | 1         | 1.61%   |
| Synaptics UWP WBDI                                                           | 1         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 1.61%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.61%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 1.61%   |
| AuthenTec AES2660                                                            | 1         | 1.61%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 1.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.61%   |
| AuthenTec AES1660                                                            | 1         | 1.61%   |
| AuthenTec AES1600                                                            | 1         | 1.61%   |
| Unknown                                                                      | 1         | 1.61%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 633       | 37.52%  |
| 0     | 622       | 36.87%  |
| 2     | 244       | 14.46%  |
| 3     | 119       | 7.05%   |
| 4     | 50        | 2.96%   |
| 5     | 16        | 0.95%   |
| 6     | 2         | 0.12%   |
| 7     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 909       | 60.64%  |
| Bluetooth                | 156       | 10.41%  |
| Net/wireless             | 140       | 9.34%   |
| Card reader              | 109       | 7.27%   |
| Fingerprint reader       | 53        | 3.54%   |
| Firewire controller      | 35        | 2.33%   |
| Net/ethernet             | 24        | 1.6%    |
| Sound                    | 23        | 1.53%   |
| Network                  | 23        | 1.53%   |
| Graphics card            | 13        | 0.87%   |
| Modem                    | 5         | 0.33%   |
| Storage/ide              | 2         | 0.13%   |
| Storage/ata              | 2         | 0.13%   |
| Storage                  | 2         | 0.13%   |
| Storage/raid             | 1         | 0.07%   |
| Storage/nvme             | 1         | 0.07%   |
| Dvb card                 | 1         | 0.07%   |

