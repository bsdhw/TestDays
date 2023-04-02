BSD in Brazil - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 196

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [a0548bbb6e](https://bsd-hardware.info/?probe=a0548bbb6e) | Mar 31, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [16d1e0aa3e](https://bsd-hardware.info/?probe=16d1e0aa3e) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| Positivo      | POS-PIB150DT                | [f0158da9e1](https://bsd-hardware.info/?probe=f0158da9e1) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| T-bao         | MINI PC                     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Positivo      | POS-PIB150DT                | [5f39c02bc9](https://bsd-hardware.info/?probe=5f39c02bc9) | Mar 13, 2023 |
| Intel         | DP55WB AAE64798-207         | [1c8295549c](https://bsd-hardware.info/?probe=1c8295549c) | Mar 10, 2023 |
| Dell          | 06X1TJ A00                  | [ac0118b05e](https://bsd-hardware.info/?probe=ac0118b05e) | Mar 03, 2023 |
| Dell          | 06X1TJ A00                  | [b663ccd3cb](https://bsd-hardware.info/?probe=b663ccd3cb) | Mar 01, 2023 |
| Dell          | 0WR7PY A00                  | [70b222c73b](https://bsd-hardware.info/?probe=70b222c73b) | Feb 23, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | [fd39a615de](https://bsd-hardware.info/?probe=fd39a615de) | Feb 19, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| ASRock        | A320M-DGS                   | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| Unknown       | Unknown                     | [34d9347fc3](https://bsd-hardware.info/?probe=34d9347fc3) | Feb 08, 2023 |
| AZW           | U59                         | [8073f1f5f3](https://bsd-hardware.info/?probe=8073f1f5f3) | Feb 04, 2023 |
| ASRock        | J4005B-ITX                  | [c4bf6a3b8c](https://bsd-hardware.info/?probe=c4bf6a3b8c) | Feb 01, 2023 |
| ASUSTek       | H110M-CS/BR                 | [73b6128279](https://bsd-hardware.info/?probe=73b6128279) | Jan 31, 2023 |
| ASUSTek       | H110M-CS/BR                 | [3fa3b849a3](https://bsd-hardware.info/?probe=3fa3b849a3) | Jan 31, 2023 |
| Biostar       | TB250-BTC+                  | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Unknown       | Unknown                     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| AMI           | MNHO-048                    | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Dell          | 0CU409                      | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Dell          | 02YRK5 A03                  | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| Dell          | 0CU409                      | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Dell          | 06X1TJ A00                  | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Intel         | Q3XXG4-P V1.0               | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| Dell          | 0F428D A00                  | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| ASUSTek       | H110M-CS/BR                 | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| maiyunda      | www.maiyunda.com            | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-CS/BR                 | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| PCWare        | IPMH81G1                    | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| HP            | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Techvision    | TVI7309X B0                 | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| ASRock        | A320M-HD                    | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Dell          | 02YRK5 A03                  | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| ASUSTek       | M5A88-M                     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Techvision    | TVI7309X B0                 | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| maiyunda      | www.maiyunda.com            | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Pegatron      | IPM41-D3                    | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Unknown       | Unknown                     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | [05e28da420](https://bsd-hardware.info/?probe=05e28da420) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | [5ee5edb1d0](https://bsd-hardware.info/?probe=5ee5edb1d0) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | [f3c4668e00](https://bsd-hardware.info/?probe=f3c4668e00) | Aug 16, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| Positivo      | POS-EINM70CS SIM            | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
| ASRock        | N68-S3 UCC                  | [e503017a9f](https://bsd-hardware.info/?probe=e503017a9f) | Jul 21, 2022 |
| Dell          | 0GDG8Y A02                  | [2f163e2a05](https://bsd-hardware.info/?probe=2f163e2a05) | Jul 21, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f88fa027ab](https://bsd-hardware.info/?probe=f88fa027ab) | Jul 19, 2022 |
| Gigabyte      | C847N                       | [4be8944950](https://bsd-hardware.info/?probe=4be8944950) | Jul 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [87d68034db](https://bsd-hardware.info/?probe=87d68034db) | Jul 14, 2022 |
| Pegatron      | IPM41-D3                    | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| ASUSTek       | A88XM-A                     | [a464043744](https://bsd-hardware.info/?probe=a464043744) | Jun 19, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [bba161b618](https://bsd-hardware.info/?probe=bba161b618) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [7be45ccc7e](https://bsd-hardware.info/?probe=7be45ccc7e) | Jun 08, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Dell          | 0D28YY A00                  | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
| HP            | 2820h                       | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Pegatron      | IPM41-D3                    | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| MSI           | U-100 Ver.001               | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| HP            | 83E1                        | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Unknown       | YL-E3845L4-V2               | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Unknown       | Phitronics G31VS-M          | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Unknown       | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| Unknown       | X79                         | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| Dell          | 0M5DCD A02                  | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASRock        | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| ASUSTek       | J1800I-C/BR                 | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| ASUSTek       | P5Q                         | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| HC            | HCAR357-MI V1.0             | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Gigabyte      | H61M-S2-B3                  | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Unknown       | Unknown                     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Yanling       | NS-1U8L                     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Toshiba       | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| ECS           | H55H-CM                     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| ASRock        | 970A-G                      | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| ASUSTek       | H110M-K                     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| MSI           | E350IS-E45                  | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| ASUSTek       | P5Q                         | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | 0GDG8Y A02                  | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 07N90W A02                  | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| HP            | ProLiant MicroServer Gen... | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| ASUSTek       | Z8P                         | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| ASUSTek       | Z8P                         | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| ASUSTek       | Z8P                         | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.7.0    | 13       | 8.44%   |
| helloSystem 0.8.0    | 7        | 4.55%   |
| OPNsense 22.1.10     | 6        | 3.9%    |
| OPNsense 20.7.8      | 6        | 3.9%    |
| OPNsense 22.7.5      | 5        | 3.25%   |
| OPNsense 21.1.3      | 5        | 3.25%   |
| OPNsense 21.1        | 5        | 3.25%   |
| helloSystem 0.4.0    | 5        | 3.25%   |
| OPNsense 23.1        | 4        | 2.6%    |
| OPNsense 22.7.8      | 4        | 2.6%    |
| OPNsense 22.7.4      | 4        | 2.6%    |
| OPNsense 21.1.1      | 4        | 2.6%    |
| helloSystem 0.6.0    | 4        | 2.6%    |
| helloSystem 0.5.0    | 4        | 2.6%    |
| OPNsense 23.1.1      | 3        | 1.95%   |
| OPNsense 22.7.6      | 3        | 1.95%   |
| OPNsense 22.1.8      | 3        | 1.95%   |
| OPNsense 21.7.7      | 3        | 1.95%   |
| OPNsense 21.7.1      | 3        | 1.95%   |
| OPNsense 21.1.9      | 3        | 1.95%   |
| OPNsense 21.1.6      | 3        | 1.95%   |
| OPNsense 21.1.4      | 3        | 1.95%   |
| helloSystem 0.8.1    | 3        | 1.95%   |
| FreeBSD 14.0-CURRENT | 3        | 1.95%   |
| OPNsense 23.1.5      | 2        | 1.3%    |
| OPNsense 23.1.3      | 2        | 1.3%    |
| OPNsense 22.7.10     | 2        | 1.3%    |
| OPNsense 22.1.7      | 2        | 1.3%    |
| OPNsense 22.1        | 2        | 1.3%    |
| OPNsense 21.1.7      | 2        | 1.3%    |
| OPNsense 21.1.2      | 2        | 1.3%    |
| NomadBSD 5806f915    | 2        | 1.3%    |
| FreeBSD 13.0-p7      | 2        | 1.3%    |
| FreeBSD 13.0         | 2        | 1.3%    |
| TrueNAS 12.2-p9      | 1        | 0.65%   |
| pfSense 2.4.5        | 1        | 0.65%   |
| OPNsense 22.7.9      | 1        | 0.65%   |
| OPNsense 22.7.3      | 1        | 0.65%   |
| OPNsense 22.7.2      | 1        | 0.65%   |
| OPNsense 22.7.1      | 1        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 64       | 53.33%  |
| helloSystem | 32       | 26.67%  |
| FreeBSD     | 17       | 14.17%  |
| NomadBSD    | 2        | 1.67%   |
| TrueNAS     | 1        | 0.83%   |
| pfSense     | 1        | 0.83%   |
| OpenBSD     | 1        | 0.83%   |
| NetBSD      | 1        | 0.83%   |
| FreeNAS     | 1        | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 117      | 99.15%  |
| i386  | 1        | 0.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 67       | 55.83%  |
| helloDesktop | 33       | 27.5%   |
| KDE5         | 8        | 6.67%   |
| Openbox      | 4        | 3.33%   |
| XFCE         | 3        | 2.5%    |
| Window Maker | 1        | 0.83%   |
| TWM          | 1        | 0.83%   |
| MATE         | 1        | 0.83%   |
| GNOME        | 1        | 0.83%   |
| AwesomeWM    | 1        | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 69       | 58.47%  |
| X11     | 49       | 41.53%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 74       | 62.18%  |
| SLiM    | 34       | 28.57%  |
| SDDM    | 7        | 5.88%   |
| GDM     | 3        | 2.52%   |
| XDM     | 1        | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 67       | 55.83%  |
| en_US   | 29       | 24.17%  |
| pt_BR   | 10       | 8.33%   |
| C       | 8        | 6.67%   |
| pt      | 3        | 2.5%    |
| fr_FR   | 2        | 1.67%   |
| fr      | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 97       | 78.86%  |
| BIOS | 26       | 21.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 63       | 51.64%  |
| Zfs    | 44       | 36.07%  |
| Cd9660 | 14       | 11.48%  |
| Ffs    | 1        | 0.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 106      | 86.89%  |
| MBR     | 14       | 11.48%  |
| Unknown | 2        | 1.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUSTek Computer        | 28       | 23.73%  |
| Dell                    | 13       | 11.02%  |
| Intel                   | 10       | 8.47%   |
| Gigabyte Technology     | 9        | 7.63%   |
| Unknown                 | 9        | 7.63%   |
| Hewlett-Packard         | 8        | 6.78%   |
| ASRock                  | 6        | 5.08%   |
| Positivo                | 4        | 3.39%   |
| Pegatron                | 3        | 2.54%   |
| PCWare                  | 3        | 2.54%   |
| MSI                     | 3        | 2.54%   |
| Techvision              | 2        | 1.69%   |
| Itautec                 | 2        | 1.69%   |
| ECS                     | 2        | 1.69%   |
| Biostar                 | 2        | 1.69%   |
| Yanling                 | 1        | 0.85%   |
| ULTRATOP                | 1        | 0.85%   |
| T-bao                   | 1        | 0.85%   |
| Semp Toshiba            | 1        | 0.85%   |
| Procomp Ind. Eletronica | 1        | 0.85%   |
| maiyunda                | 1        | 0.85%   |
| Lenovo                  | 1        | 0.85%   |
| KLLISRE                 | 1        | 0.85%   |
| HC                      | 1        | 0.85%   |
| GALAX                   | 1        | 0.85%   |
| ECS-USA                 | 1        | 0.85%   |
| CNCTION-IAF-E3845       | 1        | 0.85%   |
| AZW                     | 1        | 0.85%   |
| AMI                     | 1        | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 10       | 8.47%   |
| Intel Q3XXG4-P V1.0             | 6        | 5.08%   |
| ASUS All Series                 | 4        | 3.39%   |
| Techvision TVI7309X             | 2        | 1.69%   |
| Pegatron IPM41-D3               | 2        | 1.69%   |
| Gigabyte H61M-S2-B3             | 2        | 1.69%   |
| ASUS PRIME B450M-GAMING/BR      | 2        | 1.69%   |
| ASUS P8H61-M LX3 PLUS R2.0      | 2        | 1.69%   |
| ASUS M5A78L-M LX/BR             | 2        | 1.69%   |
| Yanling NS-1U8L                 | 1        | 0.85%   |
| ULTRATOP C2017-LIVA-ZE          | 1        | 0.85%   |
| T-bao MINI PC                   | 1        | 0.85%   |
| Semp Toshiba STI                | 1        | 0.85%   |
| Procomp Ind. Eletronica G41MXE  | 1        | 0.85%   |
| Positivo Positivo Master D610   | 1        | 0.85%   |
| Positivo POS-PIQ77CL            | 1        | 0.85%   |
| Positivo POS-EINM70CS           | 1        | 0.85%   |
| Positivo POS-EAA75DE            | 1        | 0.85%   |
| Pegatron IPMIP-GS               | 1        | 0.85%   |
| PCWare PW-945GCX                | 1        | 0.85%   |
| PCWare IPX1800G2                | 1        | 0.85%   |
| PCWare IPMH81G1                 | 1        | 0.85%   |
| MSI U-100                       | 1        | 0.85%   |
| MSI MS-7877                     | 1        | 0.85%   |
| MSI MS-7698                     | 1        | 0.85%   |
| maiyunda www.maiyunda.com       | 1        | 0.85%   |
| Lenovo ThinkCentre M57p 6078AJ6 | 1        | 0.85%   |
| KLLISRE X99-B5 V1.0             | 1        | 0.85%   |
| Itautec Infoway ST-4344         | 1        | 0.85%   |
| Itautec Infoway                 | 1        | 0.85%   |
| Intel H61                       | 1        | 0.85%   |
| Intel H55                       | 1        | 0.85%   |
| Intel DP55WB AAE64798-207       | 1        | 0.85%   |
| Intel DH61WW AAG23116-206       | 1        | 0.85%   |
| HP Z230 Tower Workstation       | 1        | 0.85%   |
| HP ProLiant ML350 G6            | 1        | 0.85%   |
| HP ProLiant ML310e Gen8 v2      | 1        | 0.85%   |
| HP ProLiant MicroServer Gen8    | 1        | 0.85%   |
| HP ProLiant MicroServer         | 1        | 0.85%   |
| HP EliteDesk 800 G4 SFF         | 1        | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 10       | 8.47%   |
| Dell OptiPlex                  | 7        | 5.93%   |
| Intel Q3XXG4-P                 | 6        | 5.08%   |
| HP ProLiant                    | 4        | 3.39%   |
| ASUS All                       | 4        | 3.39%   |
| Dell Vostro                    | 3        | 2.54%   |
| Dell Inspiron                  | 3        | 2.54%   |
| ASUS PRIME                     | 3        | 2.54%   |
| ASUS P8H61-M                   | 3        | 2.54%   |
| ASUS M5A78L-M                  | 3        | 2.54%   |
| Techvision TVI7309X            | 2        | 1.69%   |
| Pegatron IPM41-D3              | 2        | 1.69%   |
| Itautec Infoway                | 2        | 1.69%   |
| Gigabyte H61M-S2-B3            | 2        | 1.69%   |
| ASUS P5G41T-M                  | 2        | 1.69%   |
| Yanling NS-1U8L                | 1        | 0.85%   |
| ULTRATOP C2017-LIVA-ZE         | 1        | 0.85%   |
| T-bao MINI                     | 1        | 0.85%   |
| Semp Toshiba STI               | 1        | 0.85%   |
| Procomp Ind. Eletronica G41MXE | 1        | 0.85%   |
| Positivo Positivo              | 1        | 0.85%   |
| Positivo POS-PIQ77CL           | 1        | 0.85%   |
| Positivo POS-EINM70CS          | 1        | 0.85%   |
| Positivo POS-EAA75DE           | 1        | 0.85%   |
| Pegatron IPMIP-GS              | 1        | 0.85%   |
| PCWare PW-945GCX               | 1        | 0.85%   |
| PCWare IPX1800G2               | 1        | 0.85%   |
| PCWare IPMH81G1                | 1        | 0.85%   |
| MSI U-100                      | 1        | 0.85%   |
| MSI MS-7877                    | 1        | 0.85%   |
| MSI MS-7698                    | 1        | 0.85%   |
| maiyunda www.maiyunda.com      | 1        | 0.85%   |
| Lenovo ThinkCentre             | 1        | 0.85%   |
| KLLISRE X99-B5                 | 1        | 0.85%   |
| Intel H61                      | 1        | 0.85%   |
| Intel H55                      | 1        | 0.85%   |
| Intel DP55WB                   | 1        | 0.85%   |
| Intel DH61WW                   | 1        | 0.85%   |
| HP Z230                        | 1        | 0.85%   |
| HP EliteDesk                   | 1        | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2016 | 15       | 12.71%  |
| 2013 | 13       | 11.02%  |
| 2010 | 12       | 10.17%  |
| 2022 | 8        | 6.78%   |
| 2018 | 8        | 6.78%   |
| 2011 | 8        | 6.78%   |
| 2017 | 7        | 5.93%   |
| 2012 | 7        | 5.93%   |
| 2008 | 7        | 5.93%   |
| 2019 | 6        | 5.08%   |
| 2009 | 6        | 5.08%   |
| 2021 | 5        | 4.24%   |
| 2020 | 5        | 4.24%   |
| 2014 | 5        | 4.24%   |
| 2015 | 4        | 3.39%   |
| 2007 | 2        | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 118      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 118      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 45       | 36.29%  |
| 4.01-8.0   | 43       | 34.68%  |
| 16.01-24.0 | 22       | 17.74%  |
| 2.01-3.0   | 7        | 5.65%   |
| 32.01-64.0 | 6        | 4.84%   |
| 24.01-32.0 | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 74       | 60.16%  |
| 0.51-1.0   | 33       | 26.83%  |
| 1.01-2.0   | 8        | 6.5%    |
| 2.01-3.0   | 3        | 2.44%   |
| 4.01-8.0   | 2        | 1.63%   |
| 16.01-24.0 | 1        | 0.81%   |
| 8.01-16.0  | 1        | 0.81%   |
| Unknown    | 1        | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 88       | 72.13%  |
| 2      | 10       | 8.2%    |
| 3      | 9        | 7.38%   |
| 0      | 8        | 6.56%   |
| 5      | 3        | 2.46%   |
| 4      | 2        | 1.64%   |
| 7      | 1        | 0.82%   |
| 6      | 1        | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 95       | 80.51%  |
| Yes       | 23       | 19.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 117      | 99.15%  |
| No        | 1        | 0.85%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 86.44%  |
| Yes       | 16       | 13.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 93.22%  |
| Yes       | 8        | 6.78%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 118      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Desktops | Percent |
|---------------------------|----------|---------|
| SГЈo Paulo              | 12       | 8.96%   |
| Rio de Janeiro            | 11       | 8.21%   |
| Sao Paulo                 | 7        | 5.22%   |
| Sao José dos Campos      | 4        | 2.99%   |
| Curitiba                  | 4        | 2.99%   |
| SÃ£o Paulo              | 3        | 2.24%   |
| Porto Alegre              | 3        | 2.24%   |
| RondonГіpolis           | 2        | 1.49%   |
| Rio Claro                 | 2        | 1.49%   |
| Pirapora                  | 2        | 1.49%   |
| Osasco                    | 2        | 1.49%   |
| Novo Hamburgo             | 2        | 1.49%   |
| Londrina                  | 2        | 1.49%   |
| Jaraguá do Sul           | 2        | 1.49%   |
| Campinas                  | 2        | 1.49%   |
| Brasília                 | 2        | 1.49%   |
| BrasÃ­lia               | 2        | 1.49%   |
| Belo Horizonte            | 2        | 1.49%   |
| VitГіria da Conquista   | 1        | 0.75%   |
| Valparaiso de Goias       | 1        | 0.75%   |
| Urupes                    | 1        | 0.75%   |
| Unai                      | 1        | 0.75%   |
| Timbo                     | 1        | 0.75%   |
| Teresina                  | 1        | 0.75%   |
| Taubate                   | 1        | 0.75%   |
| SГЈo JosГ© dos Campos | 1        | 0.75%   |
| Suzano                    | 1        | 0.75%   |
| Sumaré                   | 1        | 0.75%   |
| Serra                     | 1        | 0.75%   |
| Sao Vicente               | 1        | 0.75%   |
| Sao Leopoldo              | 1        | 0.75%   |
| Sao Goncalo               | 1        | 0.75%   |
| Sao Domingos das Dores    | 1        | 0.75%   |
| Santo Antonio de Padua    | 1        | 0.75%   |
| Santo André              | 1        | 0.75%   |
| Rio das Ostras            | 1        | 0.75%   |
| Reriutaba                 | 1        | 0.75%   |
| Piracicaba                | 1        | 0.75%   |
| Pelotas                   | 1        | 0.75%   |
| Patos de Minas            | 1        | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 33       | 42     | 21.71%  |
| Seagate             | 24       | 51     | 15.79%  |
| Kingston            | 24       | 39     | 15.79%  |
| Samsung Electronics | 17       | 22     | 11.18%  |
| SanDisk             | 9        | 10     | 5.92%   |
| Toshiba             | 5        | 5      | 3.29%   |
| Hoodisk             | 5        | 5      | 3.29%   |
| A-DATA Technology   | 5        | 5      | 3.29%   |
| Crucial             | 4        | 7      | 2.63%   |
| XrayDisk            | 3        | 3      | 1.97%   |
| Silicon Motion      | 3        | 4      | 1.97%   |
| China               | 3        | 6      | 1.97%   |
| KingSpec            | 2        | 2      | 1.32%   |
| Hitachi             | 2        | 6      | 1.32%   |
| HGST                | 2        | 3      | 1.32%   |
| Silicon             | 1        | 1      | 0.66%   |
| NTC                 | 1        | 1      | 0.66%   |
| Netac               | 1        | 1      | 0.66%   |
| Kston               | 1        | 1      | 0.66%   |
| Hewlett-Packard     | 1        | 1      | 0.66%   |
| Gigabyte Technology | 1        | 1      | 0.66%   |
| Faspeed             | 1        | 1      | 0.66%   |
| Fanxiang            | 1        | 1      | 0.66%   |
| Drevo               | 1        | 4      | 0.66%   |
| Corsair             | 1        | 1      | 0.66%   |
| Colorful            | 1        | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB         | 9        | 5.29%   |
| Kingston SA400S37120G 120GB         | 7        | 4.12%   |
| Seagate ST500DM002-1BD142 500GB     | 5        | 2.94%   |
| Seagate ST1000DM010-2EP102 1TB      | 4        | 2.35%   |
| SanDisk SSD PLUS 120GB              | 4        | 2.35%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3        | 1.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 1.76%   |
| Seagate ST4000DM000-1F2168 4TB      | 3        | 1.76%   |
| Samsung HD502HJ 500GB               | 3        | 1.76%   |
| Samsung HD322HJ 320GB               | 3        | 1.76%   |
| Samsung HD103SJ 1TB                 | 3        | 1.76%   |
| Hoodisk SSD 64GB                    | 3        | 1.76%   |
| A-DATA SU630 240GB                  | 3        | 1.76%   |
| WDC WDS120G2G0A-00JH30 120GB        | 2        | 1.18%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2        | 1.18%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2        | 1.18%   |
| Seagate ST2000DM006-2DM164 2TB      | 2        | 1.18%   |
| SanDisk SDSSDA240G 240GB            | 2        | 1.18%   |
| SanDisk SDSSDA120G 120GB            | 2        | 1.18%   |
| Samsung HD161HJ 160GB               | 2        | 1.18%   |
| Samsung HD081GJ 80GB                | 2        | 1.18%   |
| Kingston SUV400S37120G 120GB        | 2        | 1.18%   |
| Kingston SA400S37480G 480GB         | 2        | 1.18%   |
| Hoodisk SSD 32GB                    | 2        | 1.18%   |
| Crucial CT120BX500SSD1 120GB        | 2        | 1.18%   |
| A-DATA SU650 120GB                  | 2        | 1.18%   |
| XrayDisk SSD 240GB                  | 1        | 0.59%   |
| XrayDisk SSD 128GB                  | 1        | 0.59%   |
| XrayDisk 1TB SSD                    | 1        | 0.59%   |
| WDC WDS120G2G0B-00EPW0 120GB        | 1        | 0.59%   |
| WDC WD800JD-75MSA3 80GB             | 1        | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 0.59%   |
| WDC WD5000AZLX-60K2TA1 500GB        | 1        | 0.59%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1        | 0.59%   |
| WDC WD5000AVCS-632DY1 500GB         | 1        | 0.59%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1        | 0.59%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 0.59%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 0.59%   |
| WDC WD400BD-75LRA0 40GB             | 1        | 0.59%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1        | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 31       | 39     | 39.24%  |
| Seagate             | 24       | 51     | 30.38%  |
| Samsung Electronics | 15       | 20     | 18.99%  |
| Toshiba             | 5        | 5      | 6.33%   |
| Hitachi             | 2        | 6      | 2.53%   |
| HGST                | 1        | 2      | 1.27%   |
| Hewlett-Packard     | 1        | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 23       | 38     | 33.82%  |
| SanDisk             | 9        | 10     | 13.24%  |
| Hoodisk             | 5        | 5      | 7.35%   |
| A-DATA Technology   | 5        | 5      | 7.35%   |
| Crucial             | 4        | 7      | 5.88%   |
| XrayDisk            | 3        | 3      | 4.41%   |
| WDC                 | 3        | 3      | 4.41%   |
| China               | 3        | 6      | 4.41%   |
| KingSpec            | 2        | 2      | 2.94%   |
| Silicon             | 1        | 1      | 1.47%   |
| Samsung Electronics | 1        | 1      | 1.47%   |
| NTC                 | 1        | 1      | 1.47%   |
| Netac               | 1        | 1      | 1.47%   |
| Kston               | 1        | 1      | 1.47%   |
| HGST                | 1        | 1      | 1.47%   |
| Gigabyte Technology | 1        | 1      | 1.47%   |
| Faspeed             | 1        | 1      | 1.47%   |
| Fanxiang            | 1        | 1      | 1.47%   |
| Drevo               | 1        | 4      | 1.47%   |
| Corsair             | 1        | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 64       | 124    | 49.23%  |
| SSD  | 60       | 93     | 46.15%  |
| NVMe | 6        | 7      | 4.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 104      | 217    | 94.55%  |
| NVMe | 6        | 7      | 5.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 95       | 162    | 77.87%  |
| 0.51-1.0   | 18       | 31     | 14.75%  |
| 1.01-2.0   | 6        | 16     | 4.92%   |
| 3.01-4.0   | 3        | 8      | 2.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 27.91%  |
| 1-20           | 30       | 23.26%  |
| 251-500        | 23       | 17.83%  |
| 51-100         | 18       | 13.95%  |
| 21-50          | 12       | 9.3%    |
| 501-1000       | 7        | 5.43%   |
| More than 3000 | 1        | 0.78%   |
| 2001-3000      | 1        | 0.78%   |
| 1001-2000      | 1        | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 107      | 89.92%  |
| 21-50     | 7        | 5.88%   |
| 101-250   | 3        | 2.52%   |
| 2001-3000 | 1        | 0.84%   |
| 501-1000  | 1        | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 3        | 4      | 6.38%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2        | 2      | 4.26%   |
| Samsung Electronics HD161HJ 160GB   | 2        | 2      | 4.26%   |
| XrayDisk SSD 240GB                  | 1        | 1      | 2.13%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1        | 1      | 2.13%   |
| WDC WD5000AVVS-63H0B1 500GB         | 1        | 1      | 2.13%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 1        | 1      | 2.13%   |
| WDC WD5000AAKS-08V0A0 500GB         | 1        | 1      | 2.13%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1        | 1      | 2.13%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1        | 1      | 2.13%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 2.13%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 2.13%   |
| WDC WD3200AAJS-56M0A0 320GB         | 1        | 1      | 2.13%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 1        | 1      | 2.13%   |
| WDC WD10PURX-64E5EY0 1TB            | 1        | 1      | 2.13%   |
| WDC WD10EADS-65M2BX 1TB             | 1        | 1      | 2.13%   |
| Toshiba MQ01ABD050 500GB            | 1        | 1      | 2.13%   |
| Toshiba MK1255GSX H 120GB           | 1        | 1      | 2.13%   |
| Seagate ST9160314AS 160GB           | 1        | 1      | 2.13%   |
| Seagate ST500LT012-9WS142 500GB     | 1        | 1      | 2.13%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 2.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB     | 1        | 1      | 2.13%   |
| Seagate ST500DM002-1BC142 500GB     | 1        | 1      | 2.13%   |
| Seagate ST3250310AS 250GB           | 1        | 1      | 2.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1        | 1      | 2.13%   |
| Seagate ST2000DM006-2DM164 2TB      | 1        | 1      | 2.13%   |
| Seagate ST2000DM001-1E6164 2TB      | 1        | 1      | 2.13%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 9      | 2.13%   |
| SanDisk SSD PLUS 240 GB             | 1        | 1      | 2.13%   |
| Samsung Electronics HM320II 320GB   | 1        | 2      | 2.13%   |
| Samsung Electronics HD642JJ 640GB   | 1        | 1      | 2.13%   |
| Samsung Electronics HD502HJ 500GB   | 1        | 1      | 2.13%   |
| Samsung Electronics HD103SJ 1TB     | 1        | 1      | 2.13%   |
| Samsung Electronics HD081GJ 80GB    | 1        | 1      | 2.13%   |
| Netac SSD 128GB                     | 1        | 1      | 2.13%   |
| Kingston SV300S37A60G 64GB          | 1        | 1      | 2.13%   |
| Kingston SA400S37120G 120GB         | 1        | 1      | 2.13%   |
| KingSpec P3-128 128GB               | 1        | 1      | 2.13%   |
| Hitachi HTS541680J9SA00 80GB        | 1        | 4      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 14     | 27.27%  |
| Seagate             | 11       | 19     | 25%     |
| Samsung Electronics | 9        | 12     | 20.45%  |
| Toshiba             | 2        | 2      | 4.55%   |
| Kingston            | 2        | 2      | 4.55%   |
| Hitachi             | 2        | 6      | 4.55%   |
| XrayDisk            | 1        | 1      | 2.27%   |
| SanDisk             | 1        | 1      | 2.27%   |
| Netac               | 1        | 1      | 2.27%   |
| KingSpec            | 1        | 1      | 2.27%   |
| HGST                | 1        | 1      | 2.27%   |
| Corsair             | 1        | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 14     | 33.33%  |
| Seagate             | 11       | 19     | 30.56%  |
| Samsung Electronics | 9        | 12     | 25%     |
| Toshiba             | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 6      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 53     | 80.49%  |
| SSD  | 8        | 8      | 19.51%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB    | 1        | 1      | 50%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 50%     |
| Samsung Electronics | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 85       | 154    | 64.89%  |
| Malfunc  | 39       | 61     | 29.77%  |
| Detected | 5        | 7      | 3.82%   |
| Failed   | 2        | 2      | 1.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 93       | 70.99%  |
| AMD                           | 22       | 16.79%  |
| Silicon Motion                | 6        | 4.58%   |
| Nvidia                        | 2        | 1.53%   |
| Samsung Electronics           | 1        | 0.76%   |
| Realtek Semiconductor         | 1        | 0.76%   |
| Kingston Technology Company   | 1        | 0.76%   |
| JMicron Technology            | 1        | 0.76%   |
| Integrated Technology Express | 1        | 0.76%   |
| Hewlett-Packard               | 1        | 0.76%   |
| ASMedia Technology            | 1        | 0.76%   |
| Adaptec                       | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 20       | 11.83%  |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13       | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 6.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7        | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 4.14%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6        | 3.55%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 6        | 3.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6        | 3.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 3.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 3.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 3.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 2.96%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3        | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 1.78%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 1.78%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.18%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 1.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 1.18%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.59%   |
| Realtek NVMe Controller                                                                 | 1        | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1        | 0.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1        | 0.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1        | 0.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.59%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.59%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 1        | 0.59%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 1        | 0.59%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 1        | 0.59%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1        | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 1        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 76       | 56.72%  |
| IDE  | 42       | 31.34%  |
| NVMe | 9        | 6.72%   |
| RAID | 6        | 4.48%   |
| SCSI | 1        | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 95       | 79.83%  |
| AMD    | 24       | 20.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Celeron N5105 @ 2.00GHz               | 5        | 4.17%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4        | 3.33%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 2.5%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 2.5%    |
| AMD FX-8320E Eight-Core Processor           | 3        | 2.5%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2        | 1.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.67%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2        | 1.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2        | 1.67%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2        | 1.67%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.67%   |
| Intel Core i3-2100 CPU                      | 2        | 1.67%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 2        | 1.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2        | 1.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 2        | 1.67%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.67%   |
| Intel Core 2 Duo CPU                        | 2        | 1.67%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 2        | 1.67%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.83%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.83%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1        | 0.83%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1        | 0.83%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 1        | 0.83%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 0.83%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1        | 0.83%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1        | 0.83%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 0.83%   |
| Intel Pentium CPU G2020T @ 2.50GHz          | 1        | 0.83%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1        | 0.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.83%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 0.83%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1        | 0.83%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 24       | 20.17%  |
| Intel Celeron           | 17       | 14.29%  |
| Intel Core i5           | 12       | 10.08%  |
| Intel Core 2 Duo        | 11       | 9.24%   |
| AMD FX                  | 8        | 6.72%   |
| Intel Xeon              | 7        | 5.88%   |
| Intel Pentium Dual-Core | 6        | 5.04%   |
| Intel Core i7           | 5        | 4.2%    |
| Intel Pentium           | 4        | 3.36%   |
| Intel Core 2 Quad       | 4        | 3.36%   |
| AMD Ryzen 5             | 4        | 3.36%   |
| Intel Atom              | 2        | 1.68%   |
| Other                   | 1        | 0.84%   |
| Intel Pentium Silver    | 1        | 0.84%   |
| Intel Pentium Dual      | 1        | 0.84%   |
| Intel Core 2            | 1        | 0.84%   |
| AMD Turion II Neo       | 1        | 0.84%   |
| AMD Ryzen 7             | 1        | 0.84%   |
| AMD Ryzen 5 PRO         | 1        | 0.84%   |
| AMD Ryzen 3 PRO         | 1        | 0.84%   |
| AMD Ryzen 3             | 1        | 0.84%   |
| AMD PRO A8              | 1        | 0.84%   |
| AMD Phenom              | 1        | 0.84%   |
| AMD E                   | 1        | 0.84%   |
| AMD Athlon II X2        | 1        | 0.84%   |
| AMD Athlon              | 1        | 0.84%   |
| AMD A10                 | 1        | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 54       | 44.63%  |
| 4       | 37       | 30.58%  |
| 8       | 12       | 9.92%   |
| Unknown | 7        | 5.79%   |
| 6       | 6        | 4.96%   |
| 12      | 3        | 2.48%   |
| 16      | 1        | 0.83%   |
| 1       | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 117      | 99.15%  |
| 2      | 1        | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 78       | 65.55%  |
| 2       | 34       | 28.57%  |
| Unknown | 7        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 19       | 15.83%  |
| Haswell       | 13       | 10.83%  |
| IvyBridge     | 11       | 9.17%   |
| SandyBridge   | 10       | 8.33%   |
| KabyLake      | 9        | 7.5%    |
| Unknown       | 8        | 6.67%   |
| Zen+          | 7        | 5.83%   |
| Silvermont    | 7        | 5.83%   |
| Piledriver    | 6        | 5%      |
| Core          | 6        | 5%      |
| Westmere      | 4        | 3.33%   |
| K10           | 3        | 2.5%    |
| Broadwell     | 3        | 2.5%    |
| Zen           | 2        | 1.67%   |
| Steamroller   | 2        | 1.67%   |
| Nehalem       | 2        | 1.67%   |
| Goldmont plus | 2        | 1.67%   |
| Bulldozer     | 2        | 1.67%   |
| Skylake       | 1        | 0.83%   |
| Goldmont      | 1        | 0.83%   |
| Bonnell       | 1        | 0.83%   |
| Bobcat        | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 77       | 63.11%  |
| AMD                        | 25       | 20.49%  |
| Nvidia                     | 17       | 13.93%  |
| Matrox Electronics Systems | 2        | 1.64%   |
| ASPEED Technology          | 1        | 0.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                         | 10       | 8%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9        | 7.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 8        | 6.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 7        | 5.6%    |
| Intel JasperLake [UHD Graphics]                                               | 6        | 4.8%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                        | 6        | 4.8%    |
| Intel HD Graphics 630                                                         | 5        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4        | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4        | 3.2%    |
| Intel HD Graphics 5500                                                        | 3        | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3        | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                           | 3        | 2.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3        | 2.4%    |
| Nvidia GT218 [GeForce 210]                                                    | 2        | 1.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 2        | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                                | 2        | 1.6%    |
| Matrox Electronics Systems MGA G200EH                                         | 2        | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                           | 2        | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 2        | 1.6%    |
| Intel 82945G/GZ Integrated Graphics Controller                                | 2        | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 2        | 1.6%    |
| AMD RV710 [Radeon HD 4350/4550]                                               | 2        | 1.6%    |
| AMD RS780L [Radeon 3000]                                                      | 2        | 1.6%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2        | 1.6%    |
| AMD Kaveri [Radeon R7 Graphics]                                               | 2        | 1.6%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 1.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                | 1        | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                           | 1        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                               | 1        | 0.8%    |
| Nvidia GK107GL [Quadro K2000]                                                 | 1        | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                                 | 1        | 0.8%    |
| Nvidia GF108 [GeForce GT 630]                                                 | 1        | 0.8%    |
| Nvidia GF108 [GeForce GT 430]                                                 | 1        | 0.8%    |
| Nvidia GF106 [GeForce GTS 450]                                                | 1        | 0.8%    |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 0.8%    |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1        | 0.8%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1        | 0.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1        | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 0.8%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 71       | 59.17%  |
| 1 x AMD     | 22       | 18.33%  |
| 1 x Nvidia  | 17       | 14.17%  |
| 2 x Intel   | 3        | 2.5%    |
| Intel + AMD | 3        | 2.5%    |
| 1 x Matrox  | 2        | 1.67%   |
| Other       | 1        | 0.83%   |
| 1 x ASPEED  | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 107      | 89.17%  |
| Proprietary | 12       | 10%     |
| Unknown     | 1        | 0.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 74.59%  |
| 0.51-1.0   | 9        | 7.38%   |
| 1.01-2.0   | 8        | 6.56%   |
| 3.01-4.0   | 6        | 4.92%   |
| 0.01-0.5   | 4        | 3.28%   |
| 7.01-8.0   | 3        | 2.46%   |
| 2.01-3.0   | 1        | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 16       | 41.03%  |
| Samsung Electronics | 12       | 30.77%  |
| Philips             | 3        | 7.69%   |
| AOC                 | 2        | 5.13%   |
| VIE                 | 1        | 2.56%   |
| Panasonic           | 1        | 2.56%   |
| LG Electronics      | 1        | 2.56%   |
| Lenovo              | 1        | 2.56%   |
| Hewlett-Packard     | 1        | 2.56%   |
| ASUSTek Computer    | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 2        | 4.65%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch  | 2        | 4.65%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                        | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch  | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                     | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch  | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch  | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch | 1        | 2.33%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch  | 1        | 2.33%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch | 1        | 2.33%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch     | 1        | 2.33%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                  | 1        | 2.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 1        | 2.33%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch              | 1        | 2.33%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch             | 1        | 2.33%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                    | 1        | 2.33%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 3640x1920                    | 1        | 2.33%   |
| LG Electronics LCD Monitor 23MP55                                    | 1        | 2.33%   |
| Lenovo LEN T22i-10 LEN61A9 1920x1080 480x270mm 21.7-inch             | 1        | 2.33%   |
| Hewlett-Packard E233 HPN345F 1920x1080 510x290mm 23.1-inch           | 1        | 2.33%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                 | 1        | 2.33%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                  | 1        | 2.33%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                  | 1        | 2.33%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 2.33%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch          | 1        | 2.33%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 2.33%   |
| Goldstar L1950H GSM4AA2 1280x1024 380x300mm 19.1-inch                | 1        | 2.33%   |
| Goldstar L1753T GSM4433 1280x1024 340x270mm 17.1-inch                | 1        | 2.33%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 2.33%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 2.33%   |
| Goldstar E2041 GSM4EC9 1600x900 450x250mm 20.3-inch                  | 1        | 2.33%   |
| Goldstar D2342P GSM5840 1920x1080 510x290mm 23.1-inch                | 1        | 2.33%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 1        | 2.33%   |
| Goldstar 23EA53 GSM59A8 1920x1080 510x290mm 23.1-inch                | 1        | 2.33%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 2.33%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                | 1        | 2.33%   |
| ASUSTek Computer VG248 AUS24C2 1920x1080 530x300mm 24.0-inch         | 1        | 2.33%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 1        | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 41.46%  |
| 1600x900 (HD+)     | 7        | 17.07%  |
| 1366x768 (WXGA)    | 3        | 7.32%   |
| 1280x1024 (SXGA)   | 3        | 7.32%   |
| 1440x900 (WXGA+)   | 2        | 4.88%   |
| 1360x768           | 2        | 4.88%   |
| 1024x768 (XGA)     | 2        | 4.88%   |
| 3640x1920          | 1        | 2.44%   |
| 2560x1080          | 1        | 2.44%   |
| 1680x1050 (WSXGA+) | 1        | 2.44%   |
| 1280x720 (HD)      | 1        | 2.44%   |
| Unknown            | 1        | 2.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 8        | 19.51%  |
| 23      | 7        | 17.07%  |
| 19      | 7        | 17.07%  |
| Unknown | 5        | 12.2%   |
| 18      | 4        | 9.76%   |
| 20      | 2        | 4.88%   |
| 15      | 2        | 4.88%   |
| 34      | 1        | 2.44%   |
| 31      | 1        | 2.44%   |
| 24      | 1        | 2.44%   |
| 17      | 1        | 2.44%   |
| 14      | 1        | 2.44%   |
| 13      | 1        | 2.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 20       | 50%     |
| 501-600     | 7        | 17.5%   |
| Unknown     | 5        | 12.5%   |
| 301-350     | 3        | 7.5%    |
| 201-300     | 2        | 5%      |
| 701-800     | 1        | 2.5%    |
| 601-700     | 1        | 2.5%    |
| 351-400     | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 27       | 69.23%  |
| 4/3     | 3        | 7.69%   |
| 5/4     | 2        | 5.13%   |
| 3/2     | 2        | 5.13%   |
| 16/10   | 2        | 5.13%   |
| Unknown | 2        | 5.13%   |
| 21/9    | 1        | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 16       | 39.02%  |
| 151-200        | 9        | 21.95%  |
| 141-150        | 5        | 12.2%   |
| Unknown        | 5        | 12.2%   |
| 351-500        | 2        | 4.88%   |
| 91-100         | 2        | 4.88%   |
| 111-120        | 1        | 2.44%   |
| 101-110        | 1        | 2.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 25       | 60.98%  |
| 101-120 | 10       | 24.39%  |
| Unknown | 5        | 12.2%   |
| 1-50    | 1        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 73       | 60.83%  |
| 1     | 43       | 35.83%  |
| 2     | 4        | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 82       | 50.93%  |
| Intel                 | 48       | 29.81%  |
| Qualcomm Atheros      | 9        | 5.59%   |
| Broadcom              | 7        | 4.35%   |
| Ralink                | 4        | 2.48%   |
| D-Link System         | 3        | 1.86%   |
| TP-Link               | 1        | 0.62%   |
| STMicroelectronics    | 1        | 0.62%   |
| Samsung Electronics   | 1        | 0.62%   |
| Ralink Technology     | 1        | 0.62%   |
| MediaTek              | 1        | 0.62%   |
| ICS Advent            | 1        | 0.62%   |
| Arduino SA            | 1        | 0.62%   |
| 3Com                  | 1        | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69       | 38.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 6.21%   |
| Intel I211 Gigabit Network Connection                                         | 9        | 5.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5        | 2.82%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.69%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.69%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.13%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 1.13%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 2        | 1.13%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 2        | 1.13%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.13%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.13%   |
| Intel Ethernet Controller I226-V                                              | 2        | 1.13%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.13%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.13%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.13%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.13%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.13%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.13%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 1.13%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1        | 0.56%   |
| STMicroelectronics Virtual COM Port                                           | 1        | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1        | 0.56%   |
| Realtek RTL8187SE Wireless LAN Controller                                     | 1        | 0.56%   |
| Ralink RT5370 Wireless Adapter                                                | 1        | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.56%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.56%   |
| Intel Wireless 7265                                                           | 1        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 40%     |
| Ralink                | 4        | 20%     |
| Intel                 | 3        | 15%     |
| Qualcomm Atheros      | 2        | 10%     |
| TP-Link               | 1        | 5%      |
| Ralink Technology     | 1        | 5%      |
| D-Link System         | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 15%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2        | 10%     |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 2        | 10%     |
| Ralink RT2561/RT61 rev B 802.11g                                     | 2        | 10%     |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1        | 5%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 5%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1        | 5%      |
| Realtek RTL8187SE Wireless LAN Controller                            | 1        | 5%      |
| Ralink RT5370 Wireless Adapter                                       | 1        | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1        | 5%      |
| Intel Wireless 7265                                                  | 1        | 5%      |
| Intel Wireless 3165                                                  | 1        | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 5%      |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 81       | 54.73%  |
| Intel                 | 47       | 31.76%  |
| Qualcomm Atheros      | 7        | 4.73%   |
| Broadcom              | 7        | 4.73%   |
| D-Link System         | 2        | 1.35%   |
| Samsung Electronics   | 1        | 0.68%   |
| MediaTek              | 1        | 0.68%   |
| ICS Advent            | 1        | 0.68%   |
| 3Com                  | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 69       | 44.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11       | 7.1%    |
| Intel I211 Gigabit Network Connection                                         | 9        | 5.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 5        | 3.23%   |
| Intel Ethernet Controller I225-V                                              | 4        | 2.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 1.94%   |
| Intel 82578DC Gigabit Network Connection                                      | 3        | 1.94%   |
| Intel 82576 Gigabit Network Connection                                        | 3        | 1.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 2        | 1.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2        | 1.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2        | 1.29%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.29%   |
| Intel Ethernet Controller I226-V                                              | 2        | 1.29%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.29%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.29%   |
| Intel 82579V Gigabit Network Connection                                       | 2        | 1.29%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 1.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 2        | 1.29%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 2        | 1.29%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2        | 1.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 1        | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1        | 0.65%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1        | 0.65%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.65%   |
| Intel 82580 Gigabit Network Connection                                        | 1        | 0.65%   |
| Intel 82575GB Gigabit Network Connection                                      | 1        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.65%   |
| Intel 82562V-2 10/100 Network Connection                                      | 1        | 0.65%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.65%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                       | 1        | 0.65%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 0.65%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1        | 0.65%   |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                   | 1        | 0.65%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                               | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 117      | 86.67%  |
| WiFi     | 16       | 11.85%  |
| Modem    | 2        | 1.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 116      | 92.06%  |
| WiFi     | 10       | 7.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 40       | 33.06%  |
| 2     | 38       | 31.4%   |
| 4     | 20       | 16.53%  |
| 3     | 15       | 12.4%   |
| 5     | 6        | 4.96%   |
| 6     | 2        | 1.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 110      | 90.16%  |
| Yes  | 12       | 9.84%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 3        | 37.5%   |
| Intel                   | 3        | 37.5%   |
| Cambridge Silicon Radio | 2        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                           | 3        | 37.5%   |
| Intel Bluetooth wireless interface                  | 2        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 25%     |
| Intel AX210 Bluetooth                               | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 79       | 60.31%  |
| AMD                                             | 30       | 22.9%   |
| Nvidia                                          | 16       | 12.21%  |
| C-Media Electronics                             | 3        | 2.29%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.76%   |
| KTMicro                                         | 1        | 0.76%   |
| Generalplus Technology                          | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19       | 12.34%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9        | 5.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 5.19%   |
| Intel Jasper Lake HD Audio                                                 | 6        | 3.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6        | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 3.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 3.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5        | 3.25%   |
| Intel 200 Series PCH HD Audio                                              | 5        | 3.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 3.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3        | 1.95%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 1.95%   |
| Intel Broadwell-U Audio Controller                                         | 3        | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.95%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 1.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 1.95%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 1.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.95%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.3%    |
| Nvidia High Definition Audio Controller                                    | 2        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2        | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.3%    |
| C-Media Electronics CM108 Audio Controller                                 | 2        | 1.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2        | 1.3%    |
| AMD Kaveri HDMI/DP Audio Controller                                        | 2        | 1.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2        | 1.3%    |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1        | 0.65%   |
| Nvidia GF106 High Definition Audio Controller                              | 1        | 0.65%   |
| Licensed by Sony Computer Entertainment America Wireless Stereo Headset    | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 39       | 29.32%  |
| Kingston            | 24       | 18.05%  |
| Smart               | 11       | 8.27%   |
| Crucial             | 9        | 6.77%   |
| Unknown             | 7        | 5.26%   |
| Samsung Electronics | 5        | 3.76%   |
| A-DATA Technology   | 5        | 3.76%   |
| Teikon              | 4        | 3.01%   |
| Micron Technology   | 4        | 3.01%   |
| Corsair             | 4        | 3.01%   |
| SK hynix            | 2        | 1.5%    |
| Hewlett-Packard     | 2        | 1.5%    |
| G.Skill             | 2        | 1.5%    |
| Unknown (0x5846)    | 1        | 0.75%   |
| Toshiba             | 1        | 0.75%   |
| Tigo                | 1        | 0.75%   |
| SK_Hynix            | 1        | 0.75%   |
| RZX                 | 1        | 0.75%   |
| PUSKILL             | 1        | 0.75%   |
| Patriot             | 1        | 0.75%   |
| Nanya Technology    | 1        | 0.75%   |
| Multilaser          | 1        | 0.75%   |
| MemoWise            | 1        | 0.75%   |
| Kreton              | 1        | 0.75%   |
| Kllisre             | 1        | 0.75%   |
| GLOWAY              | 1        | 0.75%   |
| CSX                 | 1        | 0.75%   |
| Apacer              | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Unknown                                                       | 7        | 4.76%   |
| Unknown RAM Module 2GB DIMM SDRAM                             | 4        | 2.72%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s           | 4        | 2.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                     | 3        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                      | 3        | 2.04%   |
| Unknown RAM Module 2GB DIMM DDR2                              | 3        | 2.04%   |
| Unknown RAM Module 2GB DIMM                                   | 3        | 2.04%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                     | 2        | 1.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                             | 2        | 1.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                     | 2        | 1.36%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                          | 2        | 1.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                     | 2        | 1.36%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s           | 2        | 1.36%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                     | 2        | 1.36%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s             | 2        | 1.36%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s         | 2        | 1.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                          | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 400MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 4096MB DIMM DDR2                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM 1333MT/s                    | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                      | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 667MT/s                           | 1        | 0.68%   |
| Unknown RAM Module 2GB DIMM 1600MT/s                          | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM SDRAM                          | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                  | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1        | 0.68%   |
| Unknown RAM Module 2048MB DIMM DDR2                           | 1        | 0.68%   |
| Unknown RAM Module 1GB DIMM SDRAM                             | 1        | 0.68%   |
| Unknown RAM Module 1024MB DIMM SDRAM                          | 1        | 0.68%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s | 1        | 0.68%   |
| Toshiba RAM 9905700-011.A00G 8GB SODIMM DDR4 2400MT/s         | 1        | 0.68%   |
| Tigo RAM 1600Mhz-8G 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.68%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s        | 1        | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 53       | 46.9%   |
| DDR4    | 27       | 23.89%  |
| DDR2    | 12       | 10.62%  |
| Unknown | 12       | 10.62%  |
| SDRAM   | 9        | 7.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 94       | 83.93%  |
| SODIMM | 17       | 15.18%  |
| Chip   | 1        | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 43       | 34.68%  |
| 8192  | 35       | 28.23%  |
| 2048  | 35       | 28.23%  |
| 16384 | 8        | 6.45%   |
| 1024  | 3        | 2.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 28       | 22.95%  |
| 1600    | 27       | 22.13%  |
| Unknown | 15       | 12.3%   |
| 2667    | 9        | 7.38%   |
| 800     | 9        | 7.38%   |
| 2400    | 8        | 6.56%   |
| 3200    | 5        | 4.1%    |
| 2133    | 5        | 4.1%    |
| 2666    | 3        | 2.46%   |
| 1866    | 3        | 2.46%   |
| 1867    | 2        | 1.64%   |
| 667     | 2        | 1.64%   |
| 400     | 2        | 1.64%   |
| 3000    | 1        | 0.82%   |
| 1067    | 1        | 0.82%   |
| 1066    | 1        | 0.82%   |
| 333     | 1        | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Logitech        | 2        | 66.67%  |
| Aveo Technology | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C270        | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |
| Aveo USB2.0 Camera          | 1        | 33.33%  |

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
| 0     | 57       | 48.31%  |
| 1     | 52       | 44.07%  |
| 2     | 7        | 5.93%   |
| 3     | 2        | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 55       | 83.33%  |
| Net/wireless             | 5        | 7.58%   |
| Sound                    | 4        | 6.06%   |
| Firewire controller      | 1        | 1.52%   |
| Bluetooth                | 1        | 1.52%   |

