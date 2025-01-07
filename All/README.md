BSD - Tested Hardware & Statistics
----------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

OS-specific reports: [FreeBSD](/Dist/FreeBSD), [GhostBSD](/Dist/GhostBSD), [helloSystem](/Dist/helloSystem), [NetBSD](/Dist/NetBSD), [NomadBSD](/Dist/NomadBSD), [OpenBSD](/Dist/OpenBSD), [OPNsense](/Dist/OPNsense), [pfSense](/Dist/pfSense), [TrueNAS](/Dist/TrueNAS).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/bsdhw/TestDays_VE)

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

Total: 28287

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 8954                        | Desktop     | [80434f997e](https://bsd-hardware.info/?probe=80434f997e) | Jan 06, 2025 |
| Gigabyte      | H310M DS2 2.0               | Desktop     | [0ace2c80f5](https://bsd-hardware.info/?probe=0ace2c80f5) | Jan 06, 2025 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6a1b59c063](https://bsd-hardware.info/?probe=6a1b59c063) | Jan 06, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [cad64ca5db](https://bsd-hardware.info/?probe=cad64ca5db) | Jan 06, 2025 |
| MSI           | Z270M MORTAR                | Desktop     | [52d87b1ad7](https://bsd-hardware.info/?probe=52d87b1ad7) | Jan 06, 2025 |
| Unknown       | DH61BR G32662-203           | Desktop     | [c082ba6276](https://bsd-hardware.info/?probe=c082ba6276) | Jan 06, 2025 |
| Gigabyte      | H310M DS2 2.0               | Desktop     | [bfa6a720f4](https://bsd-hardware.info/?probe=bfa6a720f4) | Jan 06, 2025 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [f8cd5798b5](https://bsd-hardware.info/?probe=f8cd5798b5) | Jan 06, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [aef8a88a74](https://bsd-hardware.info/?probe=aef8a88a74) | Jan 06, 2025 |
| MW            | GMLK-2_5G4L                 | Desktop     | [56c096c579](https://bsd-hardware.info/?probe=56c096c579) | Jan 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [72473eb7c0](https://bsd-hardware.info/?probe=72473eb7c0) | Jan 06, 2025 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [89ce4b4a9f](https://bsd-hardware.info/?probe=89ce4b4a9f) | Jan 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [07d989d275](https://bsd-hardware.info/?probe=07d989d275) | Jan 06, 2025 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [3e6fbd3ab8](https://bsd-hardware.info/?probe=3e6fbd3ab8) | Jan 06, 2025 |
| Unknown       | Unknown                     | Desktop     | [10fb87670b](https://bsd-hardware.info/?probe=10fb87670b) | Jan 05, 2025 |
| Sophos        | SG                          | Firewall    | [4befb4b39e](https://bsd-hardware.info/?probe=4befb4b39e) | Jan 05, 2025 |
| iEi           | SAE1 V1.04                  | Desktop     | [97651c6ab6](https://bsd-hardware.info/?probe=97651c6ab6) | Jan 05, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3431d0bef2](https://bsd-hardware.info/?probe=3431d0bef2) | Jan 05, 2025 |
| Unknown       | QDNV01                      | Desktop     | [ca2dd0099d](https://bsd-hardware.info/?probe=ca2dd0099d) | Jan 05, 2025 |
| AZW           | EQ                          | Desktop     | [79c6c2f2fb](https://bsd-hardware.info/?probe=79c6c2f2fb) | Jan 05, 2025 |
| Lenovo        | ThinkPad T480s 20L8S7T30... | Notebook    | [3ae6ff393d](https://bsd-hardware.info/?probe=3ae6ff393d) | Jan 05, 2025 |
| ASUSTek       | H110M-K                     | Desktop     | [05fd1da0a8](https://bsd-hardware.info/?probe=05fd1da0a8) | Jan 05, 2025 |
| Lenovo        | ThinkPad T480s 20L8S7T30... | Notebook    | [1a06e00ecf](https://bsd-hardware.info/?probe=1a06e00ecf) | Jan 05, 2025 |
| MSI           | H81M-P33                    | Desktop     | [4de04d7c63](https://bsd-hardware.info/?probe=4de04d7c63) | Jan 05, 2025 |
| ASUSTek       | P5Q-E                       | Desktop     | [ced4dbfd4b](https://bsd-hardware.info/?probe=ced4dbfd4b) | Jan 05, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c5f2cf7f1e](https://bsd-hardware.info/?probe=c5f2cf7f1e) | Jan 05, 2025 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| Infinix       | YL51A5                      | Notebook    | [de145e7ce4](https://bsd-hardware.info/?probe=de145e7ce4) | Jan 05, 2025 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [9d38560d6a](https://bsd-hardware.info/?probe=9d38560d6a) | Jan 05, 2025 |
| Dell          | 0MGK50 A02                  | Desktop     | [fe0b9484f5](https://bsd-hardware.info/?probe=fe0b9484f5) | Jan 05, 2025 |
| Dell          | 04Y8V0 A02                  | Desktop     | [1d20d5fd79](https://bsd-hardware.info/?probe=1d20d5fd79) | Jan 05, 2025 |
| Dell          | Latitude E5520              | Notebook    | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [692f11c086](https://bsd-hardware.info/?probe=692f11c086) | Jan 05, 2025 |
| ASUSTek       | B85M-E                      | Desktop     | [aef38fc437](https://bsd-hardware.info/?probe=aef38fc437) | Jan 05, 2025 |
| ASUSTek       | P9D-I Series                | Server      | [a45536700a](https://bsd-hardware.info/?probe=a45536700a) | Jan 05, 2025 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [25f299d953](https://bsd-hardware.info/?probe=25f299d953) | Jan 05, 2025 |
| ASUSTek       | P10S-E Series               | Desktop     | [689f54b56f](https://bsd-hardware.info/?probe=689f54b56f) | Jan 05, 2025 |
| Unknown       | Unknown                     | Desktop     | [c3815ed438](https://bsd-hardware.info/?probe=c3815ed438) | Jan 05, 2025 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [f7579f2fad](https://bsd-hardware.info/?probe=f7579f2fad) | Jan 05, 2025 |
| PC Engines    | APU2                        | Desktop     | [4548693f59](https://bsd-hardware.info/?probe=4548693f59) | Jan 05, 2025 |
| Protectli     | FW2B Ver                    | Desktop     | [705883b807](https://bsd-hardware.info/?probe=705883b807) | Jan 04, 2025 |
| HP            | OMEN by Transcend Gaming... | Notebook    | [4cc5cf0eab](https://bsd-hardware.info/?probe=4cc5cf0eab) | Jan 04, 2025 |
| Dell          | 0FDY5C A00                  | Desktop     | [ccba495e89](https://bsd-hardware.info/?probe=ccba495e89) | Jan 04, 2025 |
| Protectli     | VP2420                      | Desktop     | [a3a282fc47](https://bsd-hardware.info/?probe=a3a282fc47) | Jan 04, 2025 |
| Sophos        | SG                          | Firewall    | [0f1b34d89c](https://bsd-hardware.info/?probe=0f1b34d89c) | Jan 04, 2025 |
| AZW           | EQ                          | Mini pc     | [40f6440619](https://bsd-hardware.info/?probe=40f6440619) | Jan 04, 2025 |
| CWWK          | CW-J6-6L                    | Desktop     | [938c3dd6d1](https://bsd-hardware.info/?probe=938c3dd6d1) | Jan 04, 2025 |
| HP            | Unknown                     | Notebook    | [babd844cfb](https://bsd-hardware.info/?probe=babd844cfb) | Jan 04, 2025 |
| Sophos        | XG                          | Firewall    | [acc9b2772a](https://bsd-hardware.info/?probe=acc9b2772a) | Jan 04, 2025 |
| MSI           | Z270M MORTAR                | Desktop     | [6c0213efea](https://bsd-hardware.info/?probe=6c0213efea) | Jan 04, 2025 |
| Lenovo        | 316A SDK0J40697 WIN 3305... | Mini pc     | [a9c1f616a2](https://bsd-hardware.info/?probe=a9c1f616a2) | Jan 04, 2025 |
| Acer          | Aspire A514-54              | Notebook    | [adaff2786e](https://bsd-hardware.info/?probe=adaff2786e) | Jan 04, 2025 |
| PC Engines    | apu4                        | Desktop     | [aba651f461](https://bsd-hardware.info/?probe=aba651f461) | Jan 04, 2025 |
| Dell          | 0YDJK3 A02                  | Server      | [db63c0a016](https://bsd-hardware.info/?probe=db63c0a016) | Jan 04, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a87d1a2609](https://bsd-hardware.info/?probe=a87d1a2609) | Jan 04, 2025 |
| ASRock        | H570M-ITX/ac                | Desktop     | [5b40284fbe](https://bsd-hardware.info/?probe=5b40284fbe) | Jan 04, 2025 |
| Lenovo        | ThinkStation P320 Tiny 3... | Desktop     | [c8a55cde50](https://bsd-hardware.info/?probe=c8a55cde50) | Jan 04, 2025 |
| Dell          | 0FDY5C A00                  | Desktop     | [f0d39986e9](https://bsd-hardware.info/?probe=f0d39986e9) | Jan 04, 2025 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [92e2cb380a](https://bsd-hardware.info/?probe=92e2cb380a) | Jan 03, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [9afe02f983](https://bsd-hardware.info/?probe=9afe02f983) | Jan 03, 2025 |
| ASUSTek       | B150M-PLUS D3               | Desktop     | [d269e833ba](https://bsd-hardware.info/?probe=d269e833ba) | Jan 03, 2025 |
| MiTAC         | E220                        | Desktop     | [f869a33762](https://bsd-hardware.info/?probe=f869a33762) | Jan 03, 2025 |
| Intel         | MAHOBAY                     | Desktop     | [e1fbd3a5ef](https://bsd-hardware.info/?probe=e1fbd3a5ef) | Jan 03, 2025 |
| HP            | Unknown                     | Notebook    | [54cd46759e](https://bsd-hardware.info/?probe=54cd46759e) | Jan 03, 2025 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [9f03b43d72](https://bsd-hardware.info/?probe=9f03b43d72) | Jan 03, 2025 |
| Protectli     | FW6 Ver                     | Desktop     | [e66a74f63e](https://bsd-hardware.info/?probe=e66a74f63e) | Jan 03, 2025 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [5eecb1d87a](https://bsd-hardware.info/?probe=5eecb1d87a) | Jan 03, 2025 |
| HP            | EliteBook 840 G3            | Notebook    | [5e09879203](https://bsd-hardware.info/?probe=5e09879203) | Jan 03, 2025 |
| Dell          | 0YP4HV A00                  | Desktop     | [f4bf8c469e](https://bsd-hardware.info/?probe=f4bf8c469e) | Jan 03, 2025 |
| ASUSTek       | Q87M-E                      | Desktop     | [845a04a779](https://bsd-hardware.info/?probe=845a04a779) | Jan 03, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [977feef3aa](https://bsd-hardware.info/?probe=977feef3aa) | Jan 03, 2025 |
| HP            | 18E7                        | Desktop     | [fdac2d0362](https://bsd-hardware.info/?probe=fdac2d0362) | Jan 03, 2025 |
| ASUSTek       | Z10PE-D8 WS                 | Server      | [63f27f8783](https://bsd-hardware.info/?probe=63f27f8783) | Jan 03, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1ae378d1c0](https://bsd-hardware.info/?probe=1ae378d1c0) | Jan 03, 2025 |
| Dell          | 0YP4HV A00                  | Desktop     | [7c407b8021](https://bsd-hardware.info/?probe=7c407b8021) | Jan 03, 2025 |
| ASRock        | N100DC-ITX                  | Desktop     | [16cfe5b33f](https://bsd-hardware.info/?probe=16cfe5b33f) | Jan 03, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [d5f369f5da](https://bsd-hardware.info/?probe=d5f369f5da) | Jan 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [89041bb816](https://bsd-hardware.info/?probe=89041bb816) | Jan 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [d79c2c64e7](https://bsd-hardware.info/?probe=d79c2c64e7) | Jan 03, 2025 |
| MSI           | MS-B1711                    | Desktop     | [98df812bc4](https://bsd-hardware.info/?probe=98df812bc4) | Jan 03, 2025 |
| Dell          | Inspiron 3476               | Notebook    | [3dc38e6815](https://bsd-hardware.info/?probe=3dc38e6815) | Jan 03, 2025 |
| MSI           | MS-B1711                    | Desktop     | [c58187f624](https://bsd-hardware.info/?probe=c58187f624) | Jan 03, 2025 |
| ASUSTek       | P8Z77-V                     | Desktop     | [d3e6e71d15](https://bsd-hardware.info/?probe=d3e6e71d15) | Jan 03, 2025 |
| ASUSTek       | K53BY                       | Notebook    | [4b6604e875](https://bsd-hardware.info/?probe=4b6604e875) | Jan 03, 2025 |
| ASUSTek       | K53BY                       | Notebook    | [dac2953ae0](https://bsd-hardware.info/?probe=dac2953ae0) | Jan 03, 2025 |
| Apple         | MacBookPro11,4              | Notebook    | [f990a4641f](https://bsd-hardware.info/?probe=f990a4641f) | Jan 03, 2025 |
| Supermicro    | A1SRM-2758F                 | Server      | [63e9e4d254](https://bsd-hardware.info/?probe=63e9e4d254) | Jan 03, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [cbde580f7e](https://bsd-hardware.info/?probe=cbde580f7e) | Jan 03, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [686b424a28](https://bsd-hardware.info/?probe=686b424a28) | Jan 02, 2025 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [20976f758a](https://bsd-hardware.info/?probe=20976f758a) | Jan 02, 2025 |
| Dell          | Latitude E7250              | Notebook    | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [b1eaa92834](https://bsd-hardware.info/?probe=b1eaa92834) | Jan 02, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [e3b91fef39](https://bsd-hardware.info/?probe=e3b91fef39) | Jan 02, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2fb7873b0b](https://bsd-hardware.info/?probe=2fb7873b0b) | Jan 02, 2025 |
| Supermicro    | X12STL-IF                   | Server      | [d5a836a447](https://bsd-hardware.info/?probe=d5a836a447) | Jan 02, 2025 |
| Dell          | 0JJ7YG A00                  | Desktop     | [60a9be6897](https://bsd-hardware.info/?probe=60a9be6897) | Jan 02, 2025 |
| youyeetoo     | X1 SBC                      | Notebook    | [645ba05e41](https://bsd-hardware.info/?probe=645ba05e41) | Jan 02, 2025 |
| SJRC          | ADLN-6L                     | Desktop     | [90498561c8](https://bsd-hardware.info/?probe=90498561c8) | Jan 02, 2025 |
| Intel         | D54250WYK H13922-303        | Desktop     | [a0f4632238](https://bsd-hardware.info/?probe=a0f4632238) | Jan 02, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c6697164fc](https://bsd-hardware.info/?probe=c6697164fc) | Jan 02, 2025 |
| Unknown       | Unknown                     | Notebook    | [1d7ea0d455](https://bsd-hardware.info/?probe=1d7ea0d455) | Jan 02, 2025 |
| Deciso        | NetBoard-A10                | Notebook    | [3ce7f19f0b](https://bsd-hardware.info/?probe=3ce7f19f0b) | Jan 02, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [587525ebab](https://bsd-hardware.info/?probe=587525ebab) | Jan 02, 2025 |
| ASUSTek       | P8Z77-V                     | Desktop     | [657957bf41](https://bsd-hardware.info/?probe=657957bf41) | Jan 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [2c400cdb2c](https://bsd-hardware.info/?probe=2c400cdb2c) | Jan 02, 2025 |
| Dell          | 01D4TT A00                  | Desktop     | [447a0925d1](https://bsd-hardware.info/?probe=447a0925d1) | Jan 02, 2025 |
| Dell          | 0JJ7YG A00                  | Desktop     | [f586af63cf](https://bsd-hardware.info/?probe=f586af63cf) | Jan 02, 2025 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [5270850f20](https://bsd-hardware.info/?probe=5270850f20) | Jan 02, 2025 |
| HP            | 8062                        | Desktop     | [4ea2077640](https://bsd-hardware.info/?probe=4ea2077640) | Jan 02, 2025 |
| Lenovo        | ThinkPad T420s 417153U      | Notebook    | [f3220cb60d](https://bsd-hardware.info/?probe=f3220cb60d) | Jan 02, 2025 |
| Sophos        | SG                          | Firewall    | [6ed95430e7](https://bsd-hardware.info/?probe=6ed95430e7) | Jan 02, 2025 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [9b908a1339](https://bsd-hardware.info/?probe=9b908a1339) | Jan 02, 2025 |
| Protectli     | V1410                       | Desktop     | [2f503f2fc2](https://bsd-hardware.info/?probe=2f503f2fc2) | Jan 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [3b5881e6d2](https://bsd-hardware.info/?probe=3b5881e6d2) | Jan 02, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f5ab48d136](https://bsd-hardware.info/?probe=f5ab48d136) | Jan 02, 2025 |
| HP            | 1998                        | Desktop     | [fea249da53](https://bsd-hardware.info/?probe=fea249da53) | Jan 02, 2025 |
| Shenzhen M... | AHWSA                       | Desktop     | [871f8c208c](https://bsd-hardware.info/?probe=871f8c208c) | Jan 02, 2025 |
| Yanling       | YL-GML4 V1                  | Desktop     | [0f2a512dec](https://bsd-hardware.info/?probe=0f2a512dec) | Jan 02, 2025 |
| Dell          | Precision 7540              | Notebook    | [481eeb3296](https://bsd-hardware.info/?probe=481eeb3296) | Jan 02, 2025 |
| PICO PC       | MNHO-113                    | Desktop     | [9ac6a7a9ad](https://bsd-hardware.info/?probe=9ac6a7a9ad) | Jan 02, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [85f2416827](https://bsd-hardware.info/?probe=85f2416827) | Jan 01, 2025 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [80e080363c](https://bsd-hardware.info/?probe=80e080363c) | Jan 01, 2025 |
| Trigkey       | Green G5                    | Desktop     | [b319e43076](https://bsd-hardware.info/?probe=b319e43076) | Jan 01, 2025 |
| Dell          | 08NPPY A00                  | Desktop     | [a9e88edfae](https://bsd-hardware.info/?probe=a9e88edfae) | Jan 01, 2025 |
| Unknown       | Unknown                     | Desktop     | [c23c86dc99](https://bsd-hardware.info/?probe=c23c86dc99) | Jan 01, 2025 |
| Biostar       | A68N-2100K                  | Desktop     | [441011550c](https://bsd-hardware.info/?probe=441011550c) | Jan 01, 2025 |
| Sony          | VGN-NS21M_S                 | Notebook    | [ab610fe8e7](https://bsd-hardware.info/?probe=ab610fe8e7) | Jan 01, 2025 |
| Sony          | VGN-NS21M_S                 | Notebook    | [b848c2ce3e](https://bsd-hardware.info/?probe=b848c2ce3e) | Jan 01, 2025 |
| Dell          | Inspiron 14 7440 2-in-1     | Convertible | [1dca2d5f7d](https://bsd-hardware.info/?probe=1dca2d5f7d) | Jan 01, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d1c43670ee](https://bsd-hardware.info/?probe=d1c43670ee) | Jan 01, 2025 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [399b611f07](https://bsd-hardware.info/?probe=399b611f07) | Jan 01, 2025 |
| Unknown       | adnasc01                    | Desktop     | [e4417d31c4](https://bsd-hardware.info/?probe=e4417d31c4) | Jan 01, 2025 |
| Sophos        | XG                          | Firewall    | [996007cc63](https://bsd-hardware.info/?probe=996007cc63) | Jan 01, 2025 |
| HP            | 83E2                        | Desktop     | [c0cce366c3](https://bsd-hardware.info/?probe=c0cce366c3) | Jan 01, 2025 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [6c1907d15b](https://bsd-hardware.info/?probe=6c1907d15b) | Jan 01, 2025 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [4c4764a3fe](https://bsd-hardware.info/?probe=4c4764a3fe) | Jan 01, 2025 |
| Intel         | CARLOW                      | Desktop     | [01eb3deae5](https://bsd-hardware.info/?probe=01eb3deae5) | Jan 01, 2025 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [280124bd49](https://bsd-hardware.info/?probe=280124bd49) | Dec 31, 2024 |
| ASUSTek       | K53BY                       | Notebook    | [7e68090b10](https://bsd-hardware.info/?probe=7e68090b10) | Dec 31, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [0cae3b71cd](https://bsd-hardware.info/?probe=0cae3b71cd) | Dec 31, 2024 |
| HP            | 8768 A                      | Desktop     | [8ccd99787b](https://bsd-hardware.info/?probe=8ccd99787b) | Dec 31, 2024 |
| UD            | sgt-k13                     | Mini pc     | [4c703e6c49](https://bsd-hardware.info/?probe=4c703e6c49) | Dec 31, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [f7a1fd8000](https://bsd-hardware.info/?probe=f7a1fd8000) | Dec 31, 2024 |
| Dell          | Latitude 7390               | Notebook    | [12d707eac2](https://bsd-hardware.info/?probe=12d707eac2) | Dec 31, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7a72c07594](https://bsd-hardware.info/?probe=7a72c07594) | Dec 31, 2024 |
| Intel         | SHARKBAY                    | Desktop     | [3528375180](https://bsd-hardware.info/?probe=3528375180) | Dec 31, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [be896d46e1](https://bsd-hardware.info/?probe=be896d46e1) | Dec 31, 2024 |
| Intel         | SKYBAY                      | Desktop     | [d3adf28494](https://bsd-hardware.info/?probe=d3adf28494) | Dec 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [4fe58c5abf](https://bsd-hardware.info/?probe=4fe58c5abf) | Dec 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [d06ccdd495](https://bsd-hardware.info/?probe=d06ccdd495) | Dec 31, 2024 |
| ASRock        | N100DC-ITX                  | Desktop     | [766a7f64f0](https://bsd-hardware.info/?probe=766a7f64f0) | Dec 31, 2024 |
| Dell          | 081N4V A04                  | Server      | [029563c5c1](https://bsd-hardware.info/?probe=029563c5c1) | Dec 31, 2024 |
| BESSTAR Te... | IB9                         | Desktop     | [3dfca3d175](https://bsd-hardware.info/?probe=3dfca3d175) | Dec 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [0a3b121141](https://bsd-hardware.info/?probe=0a3b121141) | Dec 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3e2ebffab](https://bsd-hardware.info/?probe=d3e2ebffab) | Dec 31, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [02de1482a6](https://bsd-hardware.info/?probe=02de1482a6) | Dec 31, 2024 |
| Protectli     | FW4B                        | Desktop     | [fddeda1514](https://bsd-hardware.info/?probe=fddeda1514) | Dec 31, 2024 |
| HP            | 8055                        | Desktop     | [ad2cab0e5d](https://bsd-hardware.info/?probe=ad2cab0e5d) | Dec 31, 2024 |
| Shenzhen s... | miniPC                      | Desktop     | [974d78e0bf](https://bsd-hardware.info/?probe=974d78e0bf) | Dec 31, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [588468f004](https://bsd-hardware.info/?probe=588468f004) | Dec 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [1c2ec43b47](https://bsd-hardware.info/?probe=1c2ec43b47) | Dec 31, 2024 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8fe128b9b2](https://bsd-hardware.info/?probe=8fe128b9b2) | Dec 31, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [975b60a167](https://bsd-hardware.info/?probe=975b60a167) | Dec 31, 2024 |
| AZW           | EQ                          | Desktop     | [89e2185696](https://bsd-hardware.info/?probe=89e2185696) | Dec 31, 2024 |
| Intel         | SKYBAY                      | Desktop     | [83a2dfc9d6](https://bsd-hardware.info/?probe=83a2dfc9d6) | Dec 31, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [cc8dddd1e8](https://bsd-hardware.info/?probe=cc8dddd1e8) | Dec 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [f85ed259c8](https://bsd-hardware.info/?probe=f85ed259c8) | Dec 30, 2024 |
| Intel         | JSL MRD                     | Desktop     | [91ddafe16b](https://bsd-hardware.info/?probe=91ddafe16b) | Dec 30, 2024 |
| HP            | 1998                        | Desktop     | [da5ac06da2](https://bsd-hardware.info/?probe=da5ac06da2) | Dec 30, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [5eb4da6e62](https://bsd-hardware.info/?probe=5eb4da6e62) | Dec 30, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [e69f71eb23](https://bsd-hardware.info/?probe=e69f71eb23) | Dec 30, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [002e1aabfa](https://bsd-hardware.info/?probe=002e1aabfa) | Dec 30, 2024 |
| Protectli     | VP2420                      | Desktop     | [4cbb5eb9ba](https://bsd-hardware.info/?probe=4cbb5eb9ba) | Dec 30, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [7b307c888b](https://bsd-hardware.info/?probe=7b307c888b) | Dec 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [115a8d681e](https://bsd-hardware.info/?probe=115a8d681e) | Dec 30, 2024 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [ed15ca801e](https://bsd-hardware.info/?probe=ed15ca801e) | Dec 30, 2024 |
| IGEL Techn... | IGEL-D220                   | Desktop     | [9d3ca29f8a](https://bsd-hardware.info/?probe=9d3ca29f8a) | Dec 30, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [f72205b123](https://bsd-hardware.info/?probe=f72205b123) | Dec 30, 2024 |
| ASUSTek       | P11C-E Series               | Desktop     | [01492d552c](https://bsd-hardware.info/?probe=01492d552c) | Dec 30, 2024 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [4cbc277f66](https://bsd-hardware.info/?probe=4cbc277f66) | Dec 30, 2024 |
| HP            | Presario CQ57               | Notebook    | [97f4e3b3f9](https://bsd-hardware.info/?probe=97f4e3b3f9) | Dec 30, 2024 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [55689ced36](https://bsd-hardware.info/?probe=55689ced36) | Dec 30, 2024 |
| Dell EMC      | EDGE680-CPU A00             | Desktop     | [b5233e4ced](https://bsd-hardware.info/?probe=b5233e4ced) | Dec 30, 2024 |
| Unknown       | adnasc01                    | Desktop     | [b813bc581d](https://bsd-hardware.info/?probe=b813bc581d) | Dec 30, 2024 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [3e59dc6c59](https://bsd-hardware.info/?probe=3e59dc6c59) | Dec 30, 2024 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [2d3eb6c2f5](https://bsd-hardware.info/?probe=2d3eb6c2f5) | Dec 30, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [b880be6d5f](https://bsd-hardware.info/?probe=b880be6d5f) | Dec 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [8b06420b87](https://bsd-hardware.info/?probe=8b06420b87) | Dec 29, 2024 |
| Dell          | OptiPlex 5070               | Desktop     | [e2e08cab4b](https://bsd-hardware.info/?probe=e2e08cab4b) | Dec 29, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [221e1f01f4](https://bsd-hardware.info/?probe=221e1f01f4) | Dec 29, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [e55c0423ee](https://bsd-hardware.info/?probe=e55c0423ee) | Dec 29, 2024 |
| ASRock        | 4X4-5000 Series             | Desktop     | [a6b64a93c5](https://bsd-hardware.info/?probe=a6b64a93c5) | Dec 29, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [601c3c7a49](https://bsd-hardware.info/?probe=601c3c7a49) | Dec 29, 2024 |
| Intel         | QHSW02                      | Desktop     | [07fd887929](https://bsd-hardware.info/?probe=07fd887929) | Dec 29, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [a86118e267](https://bsd-hardware.info/?probe=a86118e267) | Dec 29, 2024 |
| Sophos        | UTM                         | Firewall    | [7aa2380626](https://bsd-hardware.info/?probe=7aa2380626) | Dec 29, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [62c66a5499](https://bsd-hardware.info/?probe=62c66a5499) | Dec 29, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [67ea149c61](https://bsd-hardware.info/?probe=67ea149c61) | Dec 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [6218f9a3c9](https://bsd-hardware.info/?probe=6218f9a3c9) | Dec 29, 2024 |
| ASUSTek       | P8Z77-V                     | Desktop     | [ae387d9e4c](https://bsd-hardware.info/?probe=ae387d9e4c) | Dec 29, 2024 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [e23afd3be3](https://bsd-hardware.info/?probe=e23afd3be3) | Dec 29, 2024 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [6095e2193f](https://bsd-hardware.info/?probe=6095e2193f) | Dec 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [b96103dfcb](https://bsd-hardware.info/?probe=b96103dfcb) | Dec 29, 2024 |
| EXTRA Comp... | Pokini Firewall 4P          | Firewall    | [84369f2593](https://bsd-hardware.info/?probe=84369f2593) | Dec 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [b9ca7abc2d](https://bsd-hardware.info/?probe=b9ca7abc2d) | Dec 29, 2024 |
| Deciso        | Netboard A20                | Notebook    | [8fab4ef775](https://bsd-hardware.info/?probe=8fab4ef775) | Dec 29, 2024 |
| MSI           | H81M-P33                    | Desktop     | [a1fc208c90](https://bsd-hardware.info/?probe=a1fc208c90) | Dec 29, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [f497fed563](https://bsd-hardware.info/?probe=f497fed563) | Dec 29, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [71afdfab99](https://bsd-hardware.info/?probe=71afdfab99) | Dec 29, 2024 |
| Protectli     | VP4670                      | Desktop     | [1649d4be0f](https://bsd-hardware.info/?probe=1649d4be0f) | Dec 29, 2024 |
| CWWK          | MINIPC-G12                  | Desktop     | [e85c1bdb99](https://bsd-hardware.info/?probe=e85c1bdb99) | Dec 29, 2024 |
| AZW           | EQ                          | Desktop     | [69a1ed7f82](https://bsd-hardware.info/?probe=69a1ed7f82) | Dec 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [2e57c5140f](https://bsd-hardware.info/?probe=2e57c5140f) | Dec 29, 2024 |
| Dell          | OptiPlex 5070               | Desktop     | [12d5d8ce92](https://bsd-hardware.info/?probe=12d5d8ce92) | Dec 29, 2024 |
| Trigkey       | Green G5                    | Desktop     | [560c067a01](https://bsd-hardware.info/?probe=560c067a01) | Dec 29, 2024 |
| AZW           | EQ                          | Mini pc     | [dd50b4053f](https://bsd-hardware.info/?probe=dd50b4053f) | Dec 29, 2024 |
| Protectli     | FW2B Ver                    | Desktop     | [0f9a74892c](https://bsd-hardware.info/?probe=0f9a74892c) | Dec 29, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [f7c0f4e47a](https://bsd-hardware.info/?probe=f7c0f4e47a) | Dec 29, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [bf55691036](https://bsd-hardware.info/?probe=bf55691036) | Dec 29, 2024 |
| Sophos        | UTM                         | Firewall    | [a4fb95d9e1](https://bsd-hardware.info/?probe=a4fb95d9e1) | Dec 29, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [95345d4887](https://bsd-hardware.info/?probe=95345d4887) | Dec 29, 2024 |
| Intel         | NUC11ATBC2 M53055-500       | Mini pc     | [691fb927f2](https://bsd-hardware.info/?probe=691fb927f2) | Dec 28, 2024 |
| NF533MS       | 1.0                         | Desktop     | [3f9b4a5c4f](https://bsd-hardware.info/?probe=3f9b4a5c4f) | Dec 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [a93b8e4a89](https://bsd-hardware.info/?probe=a93b8e4a89) | Dec 28, 2024 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [f28edc2c8b](https://bsd-hardware.info/?probe=f28edc2c8b) | Dec 28, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [81977dc6c5](https://bsd-hardware.info/?probe=81977dc6c5) | Dec 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [cf9c0fcf94](https://bsd-hardware.info/?probe=cf9c0fcf94) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [51514fe0c0](https://bsd-hardware.info/?probe=51514fe0c0) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [7d9a498768](https://bsd-hardware.info/?probe=7d9a498768) | Dec 28, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d2f12e9d57](https://bsd-hardware.info/?probe=d2f12e9d57) | Dec 28, 2024 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [29528fef20](https://bsd-hardware.info/?probe=29528fef20) | Dec 28, 2024 |
| BOSGAME       | Ecolite Series              | Desktop     | [c1083a8777](https://bsd-hardware.info/?probe=c1083a8777) | Dec 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [f9f7981d89](https://bsd-hardware.info/?probe=f9f7981d89) | Dec 28, 2024 |
| ASRockRack    | W680D4U-2L2T/G5             | Server      | [3b35f35036](https://bsd-hardware.info/?probe=3b35f35036) | Dec 28, 2024 |
| ASUSTek       | P8Z77-V                     | Desktop     | [548a9b376e](https://bsd-hardware.info/?probe=548a9b376e) | Dec 28, 2024 |
| Lenovo        | ThinkPad T490 20N20028US    | Notebook    | [609bd09ed4](https://bsd-hardware.info/?probe=609bd09ed4) | Dec 28, 2024 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [6a110d5e92](https://bsd-hardware.info/?probe=6a110d5e92) | Dec 28, 2024 |
| Intel         | DQ77KB AAG40294-402         | Desktop     | [9db11dd0c9](https://bsd-hardware.info/?probe=9db11dd0c9) | Dec 28, 2024 |
| Intel         | QHSW02                      | Desktop     | [0e73244f65](https://bsd-hardware.info/?probe=0e73244f65) | Dec 28, 2024 |
| Intel         | D2500HN                     | Desktop     | [a316391d86](https://bsd-hardware.info/?probe=a316391d86) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [7d2cac7c1c](https://bsd-hardware.info/?probe=7d2cac7c1c) | Dec 27, 2024 |
| Radio Vict... | A24Win8                     | Notebook    | [f85030bb1a](https://bsd-hardware.info/?probe=f85030bb1a) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [392370d6f2](https://bsd-hardware.info/?probe=392370d6f2) | Dec 27, 2024 |
| Intel         | S3000AH D40859-208          | Desktop     | [89e23969cc](https://bsd-hardware.info/?probe=89e23969cc) | Dec 27, 2024 |
| Radio Vict... | A24Win8                     | Notebook    | [17813c478e](https://bsd-hardware.info/?probe=17813c478e) | Dec 27, 2024 |
| UD            | sgt-k13                     | Mini pc     | [74cbbc576a](https://bsd-hardware.info/?probe=74cbbc576a) | Dec 27, 2024 |
| Supermicro    | X10SDE-DF                   | Desktop     | [ce805c4c07](https://bsd-hardware.info/?probe=ce805c4c07) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [7649637b96](https://bsd-hardware.info/?probe=7649637b96) | Dec 27, 2024 |
| Protectli     | V1410                       | Desktop     | [b6727da944](https://bsd-hardware.info/?probe=b6727da944) | Dec 27, 2024 |
| Fujitsu       | D3544-Sx S26361-D3544-Sx... | Desktop     | [0dcc64e192](https://bsd-hardware.info/?probe=0dcc64e192) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [0d44758f02](https://bsd-hardware.info/?probe=0d44758f02) | Dec 27, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [9c1b74e17e](https://bsd-hardware.info/?probe=9c1b74e17e) | Dec 27, 2024 |
| Sophos        | UTM                         | Firewall    | [9a8c35f467](https://bsd-hardware.info/?probe=9a8c35f467) | Dec 27, 2024 |
| Protectli     | V1410                       | Desktop     | [09e8629eb8](https://bsd-hardware.info/?probe=09e8629eb8) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [a92bf0ef02](https://bsd-hardware.info/?probe=a92bf0ef02) | Dec 27, 2024 |
| Inventec      | ZQ Class A02                | Desktop     | [9d4dc92f21](https://bsd-hardware.info/?probe=9d4dc92f21) | Dec 27, 2024 |
| Dell          | OptiPlex 5070               | Desktop     | [5a98f9dd3a](https://bsd-hardware.info/?probe=5a98f9dd3a) | Dec 27, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e03720a10c](https://bsd-hardware.info/?probe=e03720a10c) | Dec 27, 2024 |
| HP            | 86E9 A                      | Desktop     | [355a0a1775](https://bsd-hardware.info/?probe=355a0a1775) | Dec 27, 2024 |
| Dell          | OptiPlex 5070               | Desktop     | [7ee0a90c4b](https://bsd-hardware.info/?probe=7ee0a90c4b) | Dec 27, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fe167a9e36](https://bsd-hardware.info/?probe=fe167a9e36) | Dec 27, 2024 |
| Sophos        | XG                          | Firewall    | [758480d9fd](https://bsd-hardware.info/?probe=758480d9fd) | Dec 27, 2024 |
| AZW           | EQ                          | Desktop     | [45a01b3cb6](https://bsd-hardware.info/?probe=45a01b3cb6) | Dec 26, 2024 |
| Dell          | 07F37C A01                  | Desktop     | [6518ba4c6c](https://bsd-hardware.info/?probe=6518ba4c6c) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [7a016a0770](https://bsd-hardware.info/?probe=7a016a0770) | Dec 26, 2024 |
| HP            | 86E9 A                      | Desktop     | [5c61053e94](https://bsd-hardware.info/?probe=5c61053e94) | Dec 26, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [60caaaf52b](https://bsd-hardware.info/?probe=60caaaf52b) | Dec 26, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [1dbdbd867c](https://bsd-hardware.info/?probe=1dbdbd867c) | Dec 26, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [19959aeb9f](https://bsd-hardware.info/?probe=19959aeb9f) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [71050a52a4](https://bsd-hardware.info/?probe=71050a52a4) | Dec 26, 2024 |
| ASUSTek       | NUC12WSB-M 60AS00F0-MB5A... | Mini pc     | [a7565e386d](https://bsd-hardware.info/?probe=a7565e386d) | Dec 26, 2024 |
| Protectli     | VP2420                      | Desktop     | [afa30d870b](https://bsd-hardware.info/?probe=afa30d870b) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [6d669bbdc7](https://bsd-hardware.info/?probe=6d669bbdc7) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [78aee3d790](https://bsd-hardware.info/?probe=78aee3d790) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [63fd28f073](https://bsd-hardware.info/?probe=63fd28f073) | Dec 26, 2024 |
| Shenzhen S... | SI-B160                     | Desktop     | [c0fc40baea](https://bsd-hardware.info/?probe=c0fc40baea) | Dec 26, 2024 |
| Intel         | HURONRIVER                  | Desktop     | [dda4ccd2af](https://bsd-hardware.info/?probe=dda4ccd2af) | Dec 26, 2024 |
| Dell          | Latitude 5500               | Notebook    | [36b6d99530](https://bsd-hardware.info/?probe=36b6d99530) | Dec 26, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [1a6fdb5298](https://bsd-hardware.info/?probe=1a6fdb5298) | Dec 26, 2024 |
| Gigabyte      | B760M C                     | Desktop     | [b3926cb9a9](https://bsd-hardware.info/?probe=b3926cb9a9) | Dec 26, 2024 |
| Gigabyte      | B760M C                     | Desktop     | [c01a3f3d27](https://bsd-hardware.info/?probe=c01a3f3d27) | Dec 26, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [befeba6938](https://bsd-hardware.info/?probe=befeba6938) | Dec 26, 2024 |
| Sophos        | XG                          | Firewall    | [2cd9277c4f](https://bsd-hardware.info/?probe=2cd9277c4f) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [76ca94279b](https://bsd-hardware.info/?probe=76ca94279b) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f549fa7ce](https://bsd-hardware.info/?probe=9f549fa7ce) | Dec 26, 2024 |
| Dell          | Precision M2800             | Notebook    | [176ae44ed3](https://bsd-hardware.info/?probe=176ae44ed3) | Dec 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [4937ea1ef5](https://bsd-hardware.info/?probe=4937ea1ef5) | Dec 25, 2024 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [3b5e5eeea4](https://bsd-hardware.info/?probe=3b5e5eeea4) | Dec 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [846b02424a](https://bsd-hardware.info/?probe=846b02424a) | Dec 25, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [5e50386e5c](https://bsd-hardware.info/?probe=5e50386e5c) | Dec 25, 2024 |
| Dell          | 0GK35Y A00                  | Desktop     | [48c856834f](https://bsd-hardware.info/?probe=48c856834f) | Dec 25, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [94fd7f7082](https://bsd-hardware.info/?probe=94fd7f7082) | Dec 25, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [07a2d0d1ce](https://bsd-hardware.info/?probe=07a2d0d1ce) | Dec 25, 2024 |
| AZW           | U59                         | Desktop     | [17a9a9d767](https://bsd-hardware.info/?probe=17a9a9d767) | Dec 25, 2024 |
| PC Engines    | apu4                        | Desktop     | [c9b7343baf](https://bsd-hardware.info/?probe=c9b7343baf) | Dec 25, 2024 |
| Lenovo        | ThinkPad X270 20HN0015MX    | Notebook    | [66b1686a32](https://bsd-hardware.info/?probe=66b1686a32) | Dec 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D1V    | Notebook    | [c074abf948](https://bsd-hardware.info/?probe=c074abf948) | Dec 25, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [7b462d43e7](https://bsd-hardware.info/?probe=7b462d43e7) | Dec 25, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e677c34698](https://bsd-hardware.info/?probe=e677c34698) | Dec 25, 2024 |
| Lenovo        | ThinkPad T430 2344BPU       | Notebook    | [1432f4e11c](https://bsd-hardware.info/?probe=1432f4e11c) | Dec 25, 2024 |
| Gateway       | LT40                        | Notebook    | [7546fc1fd0](https://bsd-hardware.info/?probe=7546fc1fd0) | Dec 25, 2024 |
| Dell          | Latitude D620               | Notebook    | [df7fa9c810](https://bsd-hardware.info/?probe=df7fa9c810) | Dec 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [f3922a40a8](https://bsd-hardware.info/?probe=f3922a40a8) | Dec 24, 2024 |
| Protectli     | VP6630                      | Desktop     | [4a4726113b](https://bsd-hardware.info/?probe=4a4726113b) | Dec 24, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [af31d44d1f](https://bsd-hardware.info/?probe=af31d44d1f) | Dec 24, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [ac7b8b09f0](https://bsd-hardware.info/?probe=ac7b8b09f0) | Dec 24, 2024 |
| BESSTAR Te... | IB9                         | Desktop     | [b54b487e6a](https://bsd-hardware.info/?probe=b54b487e6a) | Dec 24, 2024 |
| Deciso        | OPNsense Appliance          | Notebook    | [5185740988](https://bsd-hardware.info/?probe=5185740988) | Dec 24, 2024 |
| Dell          | Precision 5510              | Notebook    | [ebf00fc632](https://bsd-hardware.info/?probe=ebf00fc632) | Dec 24, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [6eebafd5ad](https://bsd-hardware.info/?probe=6eebafd5ad) | Dec 24, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [d8ee2926d8](https://bsd-hardware.info/?probe=d8ee2926d8) | Dec 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [25a20f4c0e](https://bsd-hardware.info/?probe=25a20f4c0e) | Dec 24, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [338d76f96f](https://bsd-hardware.info/?probe=338d76f96f) | Dec 24, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [e8ab923caa](https://bsd-hardware.info/?probe=e8ab923caa) | Dec 24, 2024 |
| MSI           | 970 GAMING                  | Desktop     | [7caa8db16a](https://bsd-hardware.info/?probe=7caa8db16a) | Dec 24, 2024 |
| Unknown       | QDNV01                      | Desktop     | [fcdc78df83](https://bsd-hardware.info/?probe=fcdc78df83) | Dec 24, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [af06d6afc4](https://bsd-hardware.info/?probe=af06d6afc4) | Dec 24, 2024 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b6c70a48ea](https://bsd-hardware.info/?probe=b6c70a48ea) | Dec 24, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [14959f9c62](https://bsd-hardware.info/?probe=14959f9c62) | Dec 24, 2024 |
| Unknown       | Unknown                     | All in one  | [cb659e7cd1](https://bsd-hardware.info/?probe=cb659e7cd1) | Dec 24, 2024 |
| NF692         | 1.0                         | Desktop     | [b129c164c5](https://bsd-hardware.info/?probe=b129c164c5) | Dec 24, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [d8022a2734](https://bsd-hardware.info/?probe=d8022a2734) | Dec 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [2e05274300](https://bsd-hardware.info/?probe=2e05274300) | Dec 24, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [c90d1d5857](https://bsd-hardware.info/?probe=c90d1d5857) | Dec 24, 2024 |
| IBM           | 00J6086                     | Server      | [61cdfa8b70](https://bsd-hardware.info/?probe=61cdfa8b70) | Dec 24, 2024 |
| HP            | 339A                        | Desktop     | [ad9ed0ee8d](https://bsd-hardware.info/?probe=ad9ed0ee8d) | Dec 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2c141d9a6e](https://bsd-hardware.info/?probe=2c141d9a6e) | Dec 24, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [33a3dcb343](https://bsd-hardware.info/?probe=33a3dcb343) | Dec 24, 2024 |
| Lenovo        | ThinkPad T430 2342CTO       | Notebook    | [10ab9145d9](https://bsd-hardware.info/?probe=10ab9145d9) | Dec 24, 2024 |
| Dell          | 0JP3NX A00                  | Desktop     | [27d474564d](https://bsd-hardware.info/?probe=27d474564d) | Dec 24, 2024 |
| Protectli     | VP2420                      | Desktop     | [6fe419fedc](https://bsd-hardware.info/?probe=6fe419fedc) | Dec 24, 2024 |
| Firebat_Co... | T8_Plus                     | Desktop     | [b4c2c32c72](https://bsd-hardware.info/?probe=b4c2c32c72) | Dec 24, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [e0ed997df8](https://bsd-hardware.info/?probe=e0ed997df8) | Dec 23, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [929e0f0aa1](https://bsd-hardware.info/?probe=929e0f0aa1) | Dec 23, 2024 |
| Infoblox      | IB-810                      | Desktop     | [94e43c90e0](https://bsd-hardware.info/?probe=94e43c90e0) | Dec 23, 2024 |
| Protectli     | V1410                       | Desktop     | [6e4b1262e4](https://bsd-hardware.info/?probe=6e4b1262e4) | Dec 23, 2024 |
| Dell          | XPS 9320                    | Notebook    | [659b5961cc](https://bsd-hardware.info/?probe=659b5961cc) | Dec 23, 2024 |
| Dell          | 0YXT71 A00                  | Desktop     | [fc782b729d](https://bsd-hardware.info/?probe=fc782b729d) | Dec 23, 2024 |
| Lenovo        | [3633AC1] STC               | Server      | [04693e20ee](https://bsd-hardware.info/?probe=04693e20ee) | Dec 23, 2024 |
| Unknown       | Unknown                     | Notebook    | [4c4387237d](https://bsd-hardware.info/?probe=4c4387237d) | Dec 23, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bd781ad496](https://bsd-hardware.info/?probe=bd781ad496) | Dec 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [f2bc43b0a8](https://bsd-hardware.info/?probe=f2bc43b0a8) | Dec 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [1ea5fa36d2](https://bsd-hardware.info/?probe=1ea5fa36d2) | Dec 23, 2024 |
| HP            | 1998                        | Desktop     | [ba1d68d913](https://bsd-hardware.info/?probe=ba1d68d913) | Dec 22, 2024 |
| Sophos        | UTM                         | Firewall    | [8d1a7ecb6c](https://bsd-hardware.info/?probe=8d1a7ecb6c) | Dec 22, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [92cefa8a8c](https://bsd-hardware.info/?probe=92cefa8a8c) | Dec 22, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [a94c82e978](https://bsd-hardware.info/?probe=a94c82e978) | Dec 22, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [97a894078c](https://bsd-hardware.info/?probe=97a894078c) | Dec 22, 2024 |
| Alienware     | 0VDT73 A00                  | Desktop     | [cc0448c975](https://bsd-hardware.info/?probe=cc0448c975) | Dec 22, 2024 |
| Deciso        | Netboard A20                | Notebook    | [932588d77a](https://bsd-hardware.info/?probe=932588d77a) | Dec 22, 2024 |
| PC Engines    | APU2                        | Desktop     | [4f7eeb78f6](https://bsd-hardware.info/?probe=4f7eeb78f6) | Dec 22, 2024 |
| PC Engines    | apu4                        | Desktop     | [c41bf918c5](https://bsd-hardware.info/?probe=c41bf918c5) | Dec 22, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [887c112b05](https://bsd-hardware.info/?probe=887c112b05) | Dec 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [8befdf2a04](https://bsd-hardware.info/?probe=8befdf2a04) | Dec 22, 2024 |
| Unknown       | QDNV01                      | Desktop     | [877dbd28c5](https://bsd-hardware.info/?probe=877dbd28c5) | Dec 22, 2024 |
| ASRock        | H570M-ITX/ac                | Desktop     | [eb9e3863e0](https://bsd-hardware.info/?probe=eb9e3863e0) | Dec 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [02119a1b45](https://bsd-hardware.info/?probe=02119a1b45) | Dec 22, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [f8133ffca6](https://bsd-hardware.info/?probe=f8133ffca6) | Dec 22, 2024 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [1b29bfe2b3](https://bsd-hardware.info/?probe=1b29bfe2b3) | Dec 22, 2024 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [a06d9a4f80](https://bsd-hardware.info/?probe=a06d9a4f80) | Dec 22, 2024 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [dd220a27af](https://bsd-hardware.info/?probe=dd220a27af) | Dec 22, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [0fd27a04f7](https://bsd-hardware.info/?probe=0fd27a04f7) | Dec 22, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [ce9a08d930](https://bsd-hardware.info/?probe=ce9a08d930) | Dec 22, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [0ac816abb8](https://bsd-hardware.info/?probe=0ac816abb8) | Dec 22, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [757979fc58](https://bsd-hardware.info/?probe=757979fc58) | Dec 22, 2024 |
| IGEL Techn... | H830C                       | Notebook    | [8865063b5a](https://bsd-hardware.info/?probe=8865063b5a) | Dec 21, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [32312b45f8](https://bsd-hardware.info/?probe=32312b45f8) | Dec 21, 2024 |
| Supermicro    | X10SDE-DF                   | Desktop     | [d625d92899](https://bsd-hardware.info/?probe=d625d92899) | Dec 21, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [9fe06419eb](https://bsd-hardware.info/?probe=9fe06419eb) | Dec 21, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [86efb87e9e](https://bsd-hardware.info/?probe=86efb87e9e) | Dec 21, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [97d068af1e](https://bsd-hardware.info/?probe=97d068af1e) | Dec 21, 2024 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e7c1d45a38](https://bsd-hardware.info/?probe=e7c1d45a38) | Dec 21, 2024 |
| Dell          | Latitude 5420               | Notebook    | [89370a8376](https://bsd-hardware.info/?probe=89370a8376) | Dec 21, 2024 |
| Dell          | 00V62H A00                  | Desktop     | [0b6e2a4e95](https://bsd-hardware.info/?probe=0b6e2a4e95) | Dec 21, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [3048d1b957](https://bsd-hardware.info/?probe=3048d1b957) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [cf2ef7e381](https://bsd-hardware.info/?probe=cf2ef7e381) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [d46840aa6c](https://bsd-hardware.info/?probe=d46840aa6c) | Dec 21, 2024 |
| HP            | 1998                        | Desktop     | [e4d863c249](https://bsd-hardware.info/?probe=e4d863c249) | Dec 21, 2024 |
| Unknown       | QDNV01                      | Desktop     | [95d17434b8](https://bsd-hardware.info/?probe=95d17434b8) | Dec 21, 2024 |
| MSI           | Z270M MORTAR                | Desktop     | [1bf2d8a709](https://bsd-hardware.info/?probe=1bf2d8a709) | Dec 21, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [bee58d9e52](https://bsd-hardware.info/?probe=bee58d9e52) | Dec 21, 2024 |
| Shenzhen S... | SI-B160                     | Desktop     | [299cbc4d07](https://bsd-hardware.info/?probe=299cbc4d07) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [bba86ddcba](https://bsd-hardware.info/?probe=bba86ddcba) | Dec 21, 2024 |
| MSI           | Z97I AC                     | Desktop     | [b6ff881901](https://bsd-hardware.info/?probe=b6ff881901) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [67b79bee6d](https://bsd-hardware.info/?probe=67b79bee6d) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [f43114f35b](https://bsd-hardware.info/?probe=f43114f35b) | Dec 21, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [c16b1e23d4](https://bsd-hardware.info/?probe=c16b1e23d4) | Dec 21, 2024 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [96d3e0ca79](https://bsd-hardware.info/?probe=96d3e0ca79) | Dec 20, 2024 |
| HP            | 1998                        | Desktop     | [a875c0ccf0](https://bsd-hardware.info/?probe=a875c0ccf0) | Dec 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [e1da8dd697](https://bsd-hardware.info/?probe=e1da8dd697) | Dec 20, 2024 |
| Star Labs     | StarLite                    | Tablet      | [86df31742e](https://bsd-hardware.info/?probe=86df31742e) | Dec 20, 2024 |
| ASRock        | E3C226D2I                   | Desktop     | [37b9937cf0](https://bsd-hardware.info/?probe=37b9937cf0) | Dec 20, 2024 |
| Unknown       | MANIFOLD 2-C                | Desktop     | [652d97d116](https://bsd-hardware.info/?probe=652d97d116) | Dec 20, 2024 |
| Dell          | 05KX61 A02                  | Server      | [b578e02bf0](https://bsd-hardware.info/?probe=b578e02bf0) | Dec 20, 2024 |
| Dell          | 0F9NPY A02                  | Server      | [dc772d383e](https://bsd-hardware.info/?probe=dc772d383e) | Dec 20, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [55ff386a59](https://bsd-hardware.info/?probe=55ff386a59) | Dec 20, 2024 |
| Protectli     | FW6                         | Desktop     | [221484fba7](https://bsd-hardware.info/?probe=221484fba7) | Dec 20, 2024 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [9a8a0a932a](https://bsd-hardware.info/?probe=9a8a0a932a) | Dec 20, 2024 |
| HP            | 8158 A01                    | Mini pc     | [323f176156](https://bsd-hardware.info/?probe=323f176156) | Dec 20, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [4278f18694](https://bsd-hardware.info/?probe=4278f18694) | Dec 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [806a7126ca](https://bsd-hardware.info/?probe=806a7126ca) | Dec 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [19ffcf2c92](https://bsd-hardware.info/?probe=19ffcf2c92) | Dec 20, 2024 |
| CncTion       | N5000-4L-I226               | Desktop     | [268b1832be](https://bsd-hardware.info/?probe=268b1832be) | Dec 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [9925fe2a58](https://bsd-hardware.info/?probe=9925fe2a58) | Dec 20, 2024 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [12aa966592](https://bsd-hardware.info/?probe=12aa966592) | Dec 20, 2024 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [0e54b0ed66](https://bsd-hardware.info/?probe=0e54b0ed66) | Dec 20, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [84a86156de](https://bsd-hardware.info/?probe=84a86156de) | Dec 20, 2024 |
| Intel         | RUT40R                      | Desktop     | [3c84746b3e](https://bsd-hardware.info/?probe=3c84746b3e) | Dec 20, 2024 |
| ASRock        | N100DC-ITX                  | Desktop     | [c43b796867](https://bsd-hardware.info/?probe=c43b796867) | Dec 19, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [f5f874d438](https://bsd-hardware.info/?probe=f5f874d438) | Dec 19, 2024 |
| Supermicro    | X11SSH-F                    | Server      | [d8e4317cbc](https://bsd-hardware.info/?probe=d8e4317cbc) | Dec 19, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [79aa961e28](https://bsd-hardware.info/?probe=79aa961e28) | Dec 19, 2024 |
| PC Engines    | apu4                        | Desktop     | [1245a959bc](https://bsd-hardware.info/?probe=1245a959bc) | Dec 19, 2024 |
| Sophos        | XG                          | Firewall    | [6108d04192](https://bsd-hardware.info/?probe=6108d04192) | Dec 19, 2024 |
| Star Labs     | StarLite                    | Tablet      | [712cca18b3](https://bsd-hardware.info/?probe=712cca18b3) | Dec 19, 2024 |
| Hardkernel    | ODROID-H4                   | Desktop     | [b58dd6c714](https://bsd-hardware.info/?probe=b58dd6c714) | Dec 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [bd10f68ea1](https://bsd-hardware.info/?probe=bd10f68ea1) | Dec 19, 2024 |
| Hardkernel    | ODROID-H4                   | Desktop     | [52dfaeca63](https://bsd-hardware.info/?probe=52dfaeca63) | Dec 19, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [075230a87b](https://bsd-hardware.info/?probe=075230a87b) | Dec 19, 2024 |
| Sophos        | XG                          | Firewall    | [9e3c0c6821](https://bsd-hardware.info/?probe=9e3c0c6821) | Dec 19, 2024 |
| Bomgar        | 0XN8Y6 A07                  | Server      | [86114cd837](https://bsd-hardware.info/?probe=86114cd837) | Dec 19, 2024 |
| HP            | Pavilion 15                 | Notebook    | [9d1a480f9d](https://bsd-hardware.info/?probe=9d1a480f9d) | Dec 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [95c73f09bb](https://bsd-hardware.info/?probe=95c73f09bb) | Dec 19, 2024 |
| HP            | 1998                        | Desktop     | [b1709549d3](https://bsd-hardware.info/?probe=b1709549d3) | Dec 19, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [43f2fae544](https://bsd-hardware.info/?probe=43f2fae544) | Dec 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [200a584a04](https://bsd-hardware.info/?probe=200a584a04) | Dec 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [e79ae3cc67](https://bsd-hardware.info/?probe=e79ae3cc67) | Dec 19, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e635bff760](https://bsd-hardware.info/?probe=e635bff760) | Dec 18, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [97feee6904](https://bsd-hardware.info/?probe=97feee6904) | Dec 18, 2024 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [58389edbfa](https://bsd-hardware.info/?probe=58389edbfa) | Dec 18, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [34c03dc287](https://bsd-hardware.info/?probe=34c03dc287) | Dec 18, 2024 |
| Dell          | 0D6H9T A00                  | Desktop     | [53d4b51f32](https://bsd-hardware.info/?probe=53d4b51f32) | Dec 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [4d58aebb29](https://bsd-hardware.info/?probe=4d58aebb29) | Dec 18, 2024 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [a4c1e32308](https://bsd-hardware.info/?probe=a4c1e32308) | Dec 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [90c615583a](https://bsd-hardware.info/?probe=90c615583a) | Dec 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [a36cfd03b0](https://bsd-hardware.info/?probe=a36cfd03b0) | Dec 18, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [a79ab43d5b](https://bsd-hardware.info/?probe=a79ab43d5b) | Dec 18, 2024 |
| HPE           | ProLiant MicroServer Gen... | Server      | [eba843b9d2](https://bsd-hardware.info/?probe=eba843b9d2) | Dec 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [8dd4d42057](https://bsd-hardware.info/?probe=8dd4d42057) | Dec 18, 2024 |
| Unknown       | QDNV01                      | Desktop     | [ee2f8547cf](https://bsd-hardware.info/?probe=ee2f8547cf) | Dec 18, 2024 |
| Intel         | CARLOW                      | Desktop     | [076b8b224e](https://bsd-hardware.info/?probe=076b8b224e) | Dec 18, 2024 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [1aec80e256](https://bsd-hardware.info/?probe=1aec80e256) | Dec 18, 2024 |
| Protectli     | FW4B                        | Desktop     | [ae842a3368](https://bsd-hardware.info/?probe=ae842a3368) | Dec 18, 2024 |
| Sophos        | XG                          | Firewall    | [27bcf16efc](https://bsd-hardware.info/?probe=27bcf16efc) | Dec 18, 2024 |
| PC Engines    | apu4                        | Desktop     | [93fbf8a948](https://bsd-hardware.info/?probe=93fbf8a948) | Dec 18, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [122081b48c](https://bsd-hardware.info/?probe=122081b48c) | Dec 18, 2024 |
| HP            | 82A2                        | Desktop     | [7f93f17101](https://bsd-hardware.info/?probe=7f93f17101) | Dec 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [f7191720f2](https://bsd-hardware.info/?probe=f7191720f2) | Dec 18, 2024 |
| Protectli     | V1210                       | Desktop     | [0fc656d941](https://bsd-hardware.info/?probe=0fc656d941) | Dec 18, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [2ef3b3fe38](https://bsd-hardware.info/?probe=2ef3b3fe38) | Dec 17, 2024 |
| Shenzhen M... | F4BHD                       | Desktop     | [9bf5dfe95c](https://bsd-hardware.info/?probe=9bf5dfe95c) | Dec 17, 2024 |
| Razer         | Blade 16 - RZ09-0510        | Notebook    | [be6f32ce1d](https://bsd-hardware.info/?probe=be6f32ce1d) | Dec 17, 2024 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [3474ea7f6b](https://bsd-hardware.info/?probe=3474ea7f6b) | Dec 17, 2024 |
| OEM           | PB-1900-A                   | Desktop     | [3696d9609a](https://bsd-hardware.info/?probe=3696d9609a) | Dec 17, 2024 |
| AZW           | EQ                          | Desktop     | [9f5e6afa05](https://bsd-hardware.info/?probe=9f5e6afa05) | Dec 17, 2024 |
| MSI           | GF615M-P33 V2               | Desktop     | [79f42224b7](https://bsd-hardware.info/?probe=79f42224b7) | Dec 17, 2024 |
| HP            | 8103 A01                    | Mini pc     | [01260ea01d](https://bsd-hardware.info/?probe=01260ea01d) | Dec 17, 2024 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [c6673ef4fb](https://bsd-hardware.info/?probe=c6673ef4fb) | Dec 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [c5fbbd0d6e](https://bsd-hardware.info/?probe=c5fbbd0d6e) | Dec 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [c522c98609](https://bsd-hardware.info/?probe=c522c98609) | Dec 17, 2024 |
| SHENZHEN Y... | M1                          | Mini pc     | [d2695d230e](https://bsd-hardware.info/?probe=d2695d230e) | Dec 17, 2024 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [bc05ffdf29](https://bsd-hardware.info/?probe=bc05ffdf29) | Dec 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [40eb87fd37](https://bsd-hardware.info/?probe=40eb87fd37) | Dec 17, 2024 |
| Protectli     | VP2420                      | Desktop     | [382e7903c2](https://bsd-hardware.info/?probe=382e7903c2) | Dec 17, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [4e95e42770](https://bsd-hardware.info/?probe=4e95e42770) | Dec 17, 2024 |
| AZW           | EQ                          | Desktop     | [5fb971011a](https://bsd-hardware.info/?probe=5fb971011a) | Dec 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [74f49835b1](https://bsd-hardware.info/?probe=74f49835b1) | Dec 17, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [2d4c35ab71](https://bsd-hardware.info/?probe=2d4c35ab71) | Dec 17, 2024 |
| Intel         | JSL MRD                     | Desktop     | [f6604db757](https://bsd-hardware.info/?probe=f6604db757) | Dec 17, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [d01d1b37b8](https://bsd-hardware.info/?probe=d01d1b37b8) | Dec 17, 2024 |
| Dell          | 0PJDGF A02                  | Desktop     | [d00367bec2](https://bsd-hardware.info/?probe=d00367bec2) | Dec 17, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [07d0fa2add](https://bsd-hardware.info/?probe=07d0fa2add) | Dec 17, 2024 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [6c2b52a263](https://bsd-hardware.info/?probe=6c2b52a263) | Dec 17, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [4255ac5657](https://bsd-hardware.info/?probe=4255ac5657) | Dec 17, 2024 |
| HP            | 2000                        | Notebook    | [0705a401f8](https://bsd-hardware.info/?probe=0705a401f8) | Dec 16, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [98197d2139](https://bsd-hardware.info/?probe=98197d2139) | Dec 16, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [d2d73e5ab9](https://bsd-hardware.info/?probe=d2d73e5ab9) | Dec 16, 2024 |
| Cisco         | ASA5545 A0                  | Desktop     | [bdd19ad5e0](https://bsd-hardware.info/?probe=bdd19ad5e0) | Dec 16, 2024 |
| Protectli     | VP2420                      | Desktop     | [0d08c397dc](https://bsd-hardware.info/?probe=0d08c397dc) | Dec 16, 2024 |
| MSI           | ZH77A-G43                   | Desktop     | [f000f3f0cc](https://bsd-hardware.info/?probe=f000f3f0cc) | Dec 16, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [e9ef186dcc](https://bsd-hardware.info/?probe=e9ef186dcc) | Dec 16, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [f031d48a53](https://bsd-hardware.info/?probe=f031d48a53) | Dec 16, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [a3ac5117c7](https://bsd-hardware.info/?probe=a3ac5117c7) | Dec 16, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [f9de8b880f](https://bsd-hardware.info/?probe=f9de8b880f) | Dec 16, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [cf9666db46](https://bsd-hardware.info/?probe=cf9666db46) | Dec 16, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [1eb9f463b0](https://bsd-hardware.info/?probe=1eb9f463b0) | Dec 16, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [ced3ab3213](https://bsd-hardware.info/?probe=ced3ab3213) | Dec 16, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [4093aeb156](https://bsd-hardware.info/?probe=4093aeb156) | Dec 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [b4adf727f6](https://bsd-hardware.info/?probe=b4adf727f6) | Dec 16, 2024 |
| Protectli     | VP4670                      | Desktop     | [8d641a410f](https://bsd-hardware.info/?probe=8d641a410f) | Dec 16, 2024 |
| HP            | ProBook 4430s               | Notebook    | [45102636ac](https://bsd-hardware.info/?probe=45102636ac) | Dec 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [931a89f2d1](https://bsd-hardware.info/?probe=931a89f2d1) | Dec 16, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [8f0f26fb2b](https://bsd-hardware.info/?probe=8f0f26fb2b) | Dec 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [e2839ab569](https://bsd-hardware.info/?probe=e2839ab569) | Dec 16, 2024 |
| Pegatron      | 2A84h                       | Desktop     | [e60211eff8](https://bsd-hardware.info/?probe=e60211eff8) | Dec 16, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [e70fd95a13](https://bsd-hardware.info/?probe=e70fd95a13) | Dec 16, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [6f008745da](https://bsd-hardware.info/?probe=6f008745da) | Dec 16, 2024 |
| MiTAC         | E220 E220DF-600             | Desktop     | [fca6d5b218](https://bsd-hardware.info/?probe=fca6d5b218) | Dec 16, 2024 |
| Intel         | J1900                       | Desktop     | [1eabaeb91b](https://bsd-hardware.info/?probe=1eabaeb91b) | Dec 16, 2024 |
| Supermicro    | X10DRL-i                    | Server      | [6722a0cdd6](https://bsd-hardware.info/?probe=6722a0cdd6) | Dec 16, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [7dccc03284](https://bsd-hardware.info/?probe=7dccc03284) | Dec 16, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [d963e6e8b6](https://bsd-hardware.info/?probe=d963e6e8b6) | Dec 15, 2024 |
| ASUSTek       | 900                         | Notebook    | [a4c9546642](https://bsd-hardware.info/?probe=a4c9546642) | Dec 15, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [78fc5bf7e9](https://bsd-hardware.info/?probe=78fc5bf7e9) | Dec 15, 2024 |
| AZW           | EQ                          | Desktop     | [cdc2be64c3](https://bsd-hardware.info/?probe=cdc2be64c3) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [fb58e59524](https://bsd-hardware.info/?probe=fb58e59524) | Dec 15, 2024 |
| PC Engines    | APU2                        | Desktop     | [731738fd98](https://bsd-hardware.info/?probe=731738fd98) | Dec 15, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [49533a833d](https://bsd-hardware.info/?probe=49533a833d) | Dec 15, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [06b326f6d3](https://bsd-hardware.info/?probe=06b326f6d3) | Dec 15, 2024 |
| ASRock        | 4X4-V1000                   | Desktop     | [015174d6be](https://bsd-hardware.info/?probe=015174d6be) | Dec 15, 2024 |
| ASRock        | 4X4-V1000                   | Desktop     | [7b81b98e82](https://bsd-hardware.info/?probe=7b81b98e82) | Dec 15, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [0a6c6691da](https://bsd-hardware.info/?probe=0a6c6691da) | Dec 15, 2024 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [6d52e1dac9](https://bsd-hardware.info/?probe=6d52e1dac9) | Dec 15, 2024 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [42837ef09d](https://bsd-hardware.info/?probe=42837ef09d) | Dec 15, 2024 |
| Lenovo        | ThinkPad T490 20N3S61A13    | Notebook    | [150320a6b1](https://bsd-hardware.info/?probe=150320a6b1) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [db147012b7](https://bsd-hardware.info/?probe=db147012b7) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [297a23351f](https://bsd-hardware.info/?probe=297a23351f) | Dec 15, 2024 |
| CncTion       | N5000-4L-I226               | Desktop     | [2272738f3f](https://bsd-hardware.info/?probe=2272738f3f) | Dec 15, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [cac8fa73da](https://bsd-hardware.info/?probe=cac8fa73da) | Dec 15, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [f520de0eef](https://bsd-hardware.info/?probe=f520de0eef) | Dec 15, 2024 |
| AZW           | EQ                          | Desktop     | [427eade38e](https://bsd-hardware.info/?probe=427eade38e) | Dec 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [c736e28271](https://bsd-hardware.info/?probe=c736e28271) | Dec 15, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [f6adfa6006](https://bsd-hardware.info/?probe=f6adfa6006) | Dec 15, 2024 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [15bd94eb6d](https://bsd-hardware.info/?probe=15bd94eb6d) | Dec 15, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [992ad315d3](https://bsd-hardware.info/?probe=992ad315d3) | Dec 15, 2024 |
| PC Engines    | APU2                        | Desktop     | [7bae6fb820](https://bsd-hardware.info/?probe=7bae6fb820) | Dec 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [f57757a059](https://bsd-hardware.info/?probe=f57757a059) | Dec 14, 2024 |
| EXTRA Comp... | Pokini Firewall 4P          | Firewall    | [05b0094eeb](https://bsd-hardware.info/?probe=05b0094eeb) | Dec 14, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [c40294f0b5](https://bsd-hardware.info/?probe=c40294f0b5) | Dec 14, 2024 |
| Gigabyte      | H97M-HD3                    | Desktop     | [b916e546ab](https://bsd-hardware.info/?probe=b916e546ab) | Dec 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [6364afb18c](https://bsd-hardware.info/?probe=6364afb18c) | Dec 14, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [7444db1fd8](https://bsd-hardware.info/?probe=7444db1fd8) | Dec 14, 2024 |
| HP            | 213D A01                    | Desktop     | [9d6c8369c5](https://bsd-hardware.info/?probe=9d6c8369c5) | Dec 14, 2024 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [d2cec3b140](https://bsd-hardware.info/?probe=d2cec3b140) | Dec 14, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bc26b0ad7f](https://bsd-hardware.info/?probe=bc26b0ad7f) | Dec 14, 2024 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [fc481181a6](https://bsd-hardware.info/?probe=fc481181a6) | Dec 14, 2024 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [d3c097cc6b](https://bsd-hardware.info/?probe=d3c097cc6b) | Dec 14, 2024 |
| AZW           | EQ                          | Desktop     | [2828b59ca4](https://bsd-hardware.info/?probe=2828b59ca4) | Dec 14, 2024 |
| Unknown       | QGLK03                      | Desktop     | [f11efa36fc](https://bsd-hardware.info/?probe=f11efa36fc) | Dec 14, 2024 |
| Unknown       | QDNV01                      | Desktop     | [6d7de0a35e](https://bsd-hardware.info/?probe=6d7de0a35e) | Dec 14, 2024 |
| Protectli     | VP6630                      | Desktop     | [c4d391ee74](https://bsd-hardware.info/?probe=c4d391ee74) | Dec 14, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d513a44bf8](https://bsd-hardware.info/?probe=d513a44bf8) | Dec 14, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [814f666054](https://bsd-hardware.info/?probe=814f666054) | Dec 14, 2024 |
| Lenovo        | ThinkStation E30 7783RR8    | Desktop     | [65fdcf73df](https://bsd-hardware.info/?probe=65fdcf73df) | Dec 14, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [9f6f476877](https://bsd-hardware.info/?probe=9f6f476877) | Dec 14, 2024 |
| Supermicro    | X9DRD-iF                    | Server      | [06958bbf47](https://bsd-hardware.info/?probe=06958bbf47) | Dec 14, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [26bea1ebf1](https://bsd-hardware.info/?probe=26bea1ebf1) | Dec 13, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [fec0e025ff](https://bsd-hardware.info/?probe=fec0e025ff) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [04c8beca54](https://bsd-hardware.info/?probe=04c8beca54) | Dec 13, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [87ce6d4615](https://bsd-hardware.info/?probe=87ce6d4615) | Dec 13, 2024 |
| Protectli     | V1410                       | Desktop     | [8b38528c6a](https://bsd-hardware.info/?probe=8b38528c6a) | Dec 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f7a60f418](https://bsd-hardware.info/?probe=1f7a60f418) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [b41e72e0a7](https://bsd-hardware.info/?probe=b41e72e0a7) | Dec 13, 2024 |
| MSI           | Z97I AC                     | Desktop     | [844a11760c](https://bsd-hardware.info/?probe=844a11760c) | Dec 13, 2024 |
| Intel         | DH61AG AAG23736-400         | Desktop     | [ac76ab9cf5](https://bsd-hardware.info/?probe=ac76ab9cf5) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [94d37d7a1e](https://bsd-hardware.info/?probe=94d37d7a1e) | Dec 13, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2fb19b27c9](https://bsd-hardware.info/?probe=2fb19b27c9) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [696aedf790](https://bsd-hardware.info/?probe=696aedf790) | Dec 13, 2024 |
| JGINYUE       | X99-8D4G Server             | Desktop     | [8a6322442d](https://bsd-hardware.info/?probe=8a6322442d) | Dec 13, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [dfd626feb6](https://bsd-hardware.info/?probe=dfd626feb6) | Dec 13, 2024 |
| Intel         | BayTrail Platform           | Tablet      | [583d923026](https://bsd-hardware.info/?probe=583d923026) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [ed46ec5a1f](https://bsd-hardware.info/?probe=ed46ec5a1f) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [dd2a5f051e](https://bsd-hardware.info/?probe=dd2a5f051e) | Dec 13, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0aea251037](https://bsd-hardware.info/?probe=0aea251037) | Dec 13, 2024 |
| VGKE          | N95                         | Desktop     | [456e2dd02e](https://bsd-hardware.info/?probe=456e2dd02e) | Dec 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [806188d557](https://bsd-hardware.info/?probe=806188d557) | Dec 13, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [132bcb0d2a](https://bsd-hardware.info/?probe=132bcb0d2a) | Dec 13, 2024 |
| Supermicro    | A1SAM-2550F                 | Server      | [d71dbbb668](https://bsd-hardware.info/?probe=d71dbbb668) | Dec 13, 2024 |
| Unknown       | Unknown                     | Notebook    | [e02dd09c46](https://bsd-hardware.info/?probe=e02dd09c46) | Dec 12, 2024 |
| HP            | 802E                        | Desktop     | [a73cbe8149](https://bsd-hardware.info/?probe=a73cbe8149) | Dec 12, 2024 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [1fc4bc2661](https://bsd-hardware.info/?probe=1fc4bc2661) | Dec 12, 2024 |
| Lenovo        | ThinkPad X60s 1704R8G       | Notebook    | [cad87ee9a5](https://bsd-hardware.info/?probe=cad87ee9a5) | Dec 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [aa6a6969b9](https://bsd-hardware.info/?probe=aa6a6969b9) | Dec 12, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [124adee472](https://bsd-hardware.info/?probe=124adee472) | Dec 12, 2024 |
| BESSTAR Te... | IB9                         | Desktop     | [6918b9ed8d](https://bsd-hardware.info/?probe=6918b9ed8d) | Dec 12, 2024 |
| Dell          | 0VRCY5 A14                  | Server      | [ea3362af64](https://bsd-hardware.info/?probe=ea3362af64) | Dec 12, 2024 |
| WeiBu         | ADL-N Prod                  | Desktop     | [de66071f16](https://bsd-hardware.info/?probe=de66071f16) | Dec 12, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [8d3eeb9ac4](https://bsd-hardware.info/?probe=8d3eeb9ac4) | Dec 12, 2024 |
| Unknown       | QCML02                      | Desktop     | [8d92456bd9](https://bsd-hardware.info/?probe=8d92456bd9) | Dec 12, 2024 |
| Unknown       | QDNV01                      | Desktop     | [f2df17ea71](https://bsd-hardware.info/?probe=f2df17ea71) | Dec 12, 2024 |
| Dell          | 0C2XKD A00                  | Desktop     | [fe6d8c49a7](https://bsd-hardware.info/?probe=fe6d8c49a7) | Dec 12, 2024 |
| ASRock        | Z370M Pro4                  | Desktop     | [e97904a981](https://bsd-hardware.info/?probe=e97904a981) | Dec 12, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [28d155dd95](https://bsd-hardware.info/?probe=28d155dd95) | Dec 12, 2024 |
| Lenovo        | ThinkPad X250 20CLS14400    | Notebook    | [d3a7de0e4b](https://bsd-hardware.info/?probe=d3a7de0e4b) | Dec 12, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [e3793b6d53](https://bsd-hardware.info/?probe=e3793b6d53) | Dec 12, 2024 |
| Gigabyte      | N3050ND3H                   | Desktop     | [87c12ec031](https://bsd-hardware.info/?probe=87c12ec031) | Dec 12, 2024 |
| Unknown       | ROUTER                      | Desktop     | [64ce081f31](https://bsd-hardware.info/?probe=64ce081f31) | Dec 12, 2024 |
| Protectli     | VP4630                      | Desktop     | [04f464a725](https://bsd-hardware.info/?probe=04f464a725) | Dec 11, 2024 |
| Unknown       | QDNV01                      | Desktop     | [61510207af](https://bsd-hardware.info/?probe=61510207af) | Dec 11, 2024 |
| PC Engines    | APU2                        | Desktop     | [dfc440d7ec](https://bsd-hardware.info/?probe=dfc440d7ec) | Dec 11, 2024 |
| Protectli     | VP4630                      | Desktop     | [90fd44ca00](https://bsd-hardware.info/?probe=90fd44ca00) | Dec 11, 2024 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [f34dc483d5](https://bsd-hardware.info/?probe=f34dc483d5) | Dec 11, 2024 |
| CncTion       | N4100-4L                    | Desktop     | [1be77b1e74](https://bsd-hardware.info/?probe=1be77b1e74) | Dec 11, 2024 |
| Unknown       | QDNV01                      | Desktop     | [4dddcbe501](https://bsd-hardware.info/?probe=4dddcbe501) | Dec 11, 2024 |
| Intel         | ADL-4L                      | Desktop     | [f3c65c2394](https://bsd-hardware.info/?probe=f3c65c2394) | Dec 11, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [d993d1bb66](https://bsd-hardware.info/?probe=d993d1bb66) | Dec 11, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cfc56b5602](https://bsd-hardware.info/?probe=cfc56b5602) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [d2d0edc563](https://bsd-hardware.info/?probe=d2d0edc563) | Dec 11, 2024 |
| Dell          | 03X6X0 A00                  | Server      | [178d3bd582](https://bsd-hardware.info/?probe=178d3bd582) | Dec 11, 2024 |
| Silicom       | 80300-0134-g01              | Desktop     | [9c18dc951c](https://bsd-hardware.info/?probe=9c18dc951c) | Dec 11, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [fef7a06892](https://bsd-hardware.info/?probe=fef7a06892) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [fa422c4eec](https://bsd-hardware.info/?probe=fa422c4eec) | Dec 11, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [1482aa1063](https://bsd-hardware.info/?probe=1482aa1063) | Dec 11, 2024 |
| Dell          | 0KCJ3G A00                  | Mini pc     | [455eb0cd2a](https://bsd-hardware.info/?probe=455eb0cd2a) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [3d5becd141](https://bsd-hardware.info/?probe=3d5becd141) | Dec 11, 2024 |
| ASUSTek       | P5KR                        | Desktop     | [9ee55170f1](https://bsd-hardware.info/?probe=9ee55170f1) | Dec 11, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [a4e2581285](https://bsd-hardware.info/?probe=a4e2581285) | Dec 11, 2024 |
| Protectli     | FW6                         | Desktop     | [85c85ff13e](https://bsd-hardware.info/?probe=85c85ff13e) | Dec 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [91490047ad](https://bsd-hardware.info/?probe=91490047ad) | Dec 11, 2024 |
| Dell          | 0MGK50 A00                  | Desktop     | [43ded3b6d5](https://bsd-hardware.info/?probe=43ded3b6d5) | Dec 10, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [d253682d99](https://bsd-hardware.info/?probe=d253682d99) | Dec 10, 2024 |
| Supermicro    | X10SLM+-LN4F                | Server      | [537fff76dc](https://bsd-hardware.info/?probe=537fff76dc) | Dec 10, 2024 |
| Intel         | X79_PLUS                    | Desktop     | [0382eb3cd4](https://bsd-hardware.info/?probe=0382eb3cd4) | Dec 10, 2024 |
| Sophos        | SG                          | Firewall    | [509a702478](https://bsd-hardware.info/?probe=509a702478) | Dec 10, 2024 |
| Dell          | 0GXH08 A03                  | Server      | [2fd65d9cd9](https://bsd-hardware.info/?probe=2fd65d9cd9) | Dec 10, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [9963fc5832](https://bsd-hardware.info/?probe=9963fc5832) | Dec 10, 2024 |
| Dell          | 0T7D40 A00                  | Desktop     | [84fb65d887](https://bsd-hardware.info/?probe=84fb65d887) | Dec 10, 2024 |
| MSI           | H110M ECO                   | Desktop     | [1a319ab9cb](https://bsd-hardware.info/?probe=1a319ab9cb) | Dec 10, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [9a23532e0a](https://bsd-hardware.info/?probe=9a23532e0a) | Dec 10, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [af6b1bbdb9](https://bsd-hardware.info/?probe=af6b1bbdb9) | Dec 10, 2024 |
| ASRock        | E3C226D2I                   | Desktop     | [0aa040bcda](https://bsd-hardware.info/?probe=0aa040bcda) | Dec 10, 2024 |
| ASUSTek       | P5KR                        | Desktop     | [8b47c8c93a](https://bsd-hardware.info/?probe=8b47c8c93a) | Dec 10, 2024 |
| Hardkernel    | ODROID-H4                   | Desktop     | [e5e3440bd6](https://bsd-hardware.info/?probe=e5e3440bd6) | Dec 10, 2024 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [08608b8653](https://bsd-hardware.info/?probe=08608b8653) | Dec 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [c3010f06f3](https://bsd-hardware.info/?probe=c3010f06f3) | Dec 10, 2024 |
| HP            | 8054                        | Desktop     | [252f0cf51b](https://bsd-hardware.info/?probe=252f0cf51b) | Dec 10, 2024 |
| Dell          | 0CU409                      | Desktop     | [4a9ae9da54](https://bsd-hardware.info/?probe=4a9ae9da54) | Dec 10, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [09413cb67c](https://bsd-hardware.info/?probe=09413cb67c) | Dec 10, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [9f9235fcd6](https://bsd-hardware.info/?probe=9f9235fcd6) | Dec 10, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [971f443507](https://bsd-hardware.info/?probe=971f443507) | Dec 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [0fa7499053](https://bsd-hardware.info/?probe=0fa7499053) | Dec 09, 2024 |
| Unknown       | QDNV01                      | Desktop     | [881aa7c3be](https://bsd-hardware.info/?probe=881aa7c3be) | Dec 09, 2024 |
| ASRock        | B550 PG Riptide             | Desktop     | [183c138b5d](https://bsd-hardware.info/?probe=183c138b5d) | Dec 09, 2024 |
| Quanmax       | KEEX-1660 B1                | Desktop     | [e965dc9713](https://bsd-hardware.info/?probe=e965dc9713) | Dec 09, 2024 |
| SJRC          | ADLN-6L                     | Desktop     | [a600ba22b2](https://bsd-hardware.info/?probe=a600ba22b2) | Dec 09, 2024 |
| Dell          | 0YJMC0 A02                  | Desktop     | [8a6e226054](https://bsd-hardware.info/?probe=8a6e226054) | Dec 09, 2024 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [89c3e8f75c](https://bsd-hardware.info/?probe=89c3e8f75c) | Dec 09, 2024 |
| Unknown       | QCML02                      | Desktop     | [a6f3640fd8](https://bsd-hardware.info/?probe=a6f3640fd8) | Dec 09, 2024 |
| Gigabyte      | H310M S2H                   | Desktop     | [d514bee926](https://bsd-hardware.info/?probe=d514bee926) | Dec 09, 2024 |
| JGINYUE       | X99-8D4G Server             | Desktop     | [0a59d0dd76](https://bsd-hardware.info/?probe=0a59d0dd76) | Dec 09, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [2e959ea19a](https://bsd-hardware.info/?probe=2e959ea19a) | Dec 09, 2024 |
| HP            | 8055                        | Desktop     | [21547fc9c7](https://bsd-hardware.info/?probe=21547fc9c7) | Dec 09, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [ba507c395e](https://bsd-hardware.info/?probe=ba507c395e) | Dec 09, 2024 |
| Unknown       | QCML02                      | Desktop     | [30378a61c3](https://bsd-hardware.info/?probe=30378a61c3) | Dec 09, 2024 |
| Sophos        | SG                          | Firewall    | [bb3256eef8](https://bsd-hardware.info/?probe=bb3256eef8) | Dec 09, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [4cfeb93125](https://bsd-hardware.info/?probe=4cfeb93125) | Dec 09, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [52f3e1cf1a](https://bsd-hardware.info/?probe=52f3e1cf1a) | Dec 09, 2024 |
| Dell          | 05KX61 A02                  | Server      | [11260fea94](https://bsd-hardware.info/?probe=11260fea94) | Dec 09, 2024 |
| Dell          | 0F9NPY A02                  | Server      | [358deee0d5](https://bsd-hardware.info/?probe=358deee0d5) | Dec 09, 2024 |
| Protectli     | VP2420                      | Desktop     | [c539321419](https://bsd-hardware.info/?probe=c539321419) | Dec 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [ee2c8960a2](https://bsd-hardware.info/?probe=ee2c8960a2) | Dec 08, 2024 |
| Unknown       | YL-J3160L4                  | Desktop     | [9dcc470797](https://bsd-hardware.info/?probe=9dcc470797) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [af42fdfbde](https://bsd-hardware.info/?probe=af42fdfbde) | Dec 08, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [474ddb6777](https://bsd-hardware.info/?probe=474ddb6777) | Dec 08, 2024 |
| Unknown       | QDNV01                      | Desktop     | [fed4778ce8](https://bsd-hardware.info/?probe=fed4778ce8) | Dec 08, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [d434e3a571](https://bsd-hardware.info/?probe=d434e3a571) | Dec 08, 2024 |
| Barracuda ... | Barracuda CloudGen Firew... | Firewall    | [0f70f62be7](https://bsd-hardware.info/?probe=0f70f62be7) | Dec 08, 2024 |
| Deciso        | Netboard A20                | Notebook    | [7a9c98faa1](https://bsd-hardware.info/?probe=7a9c98faa1) | Dec 08, 2024 |
| Protectli     | FW1 Ver                     | Desktop     | [0886b7bcf1](https://bsd-hardware.info/?probe=0886b7bcf1) | Dec 08, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [bd7757d88d](https://bsd-hardware.info/?probe=bd7757d88d) | Dec 08, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [eff61a5b5a](https://bsd-hardware.info/?probe=eff61a5b5a) | Dec 08, 2024 |
| Alienware     | m15 R6                      | Notebook    | [9060b1741b](https://bsd-hardware.info/?probe=9060b1741b) | Dec 08, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S3... | Convertible | [aa358442b4](https://bsd-hardware.info/?probe=aa358442b4) | Dec 08, 2024 |
| Lenovo        | ThinkPad L13 Yoga 20R6S3... | Convertible | [3aaaa724f1](https://bsd-hardware.info/?probe=3aaaa724f1) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [2323c300a7](https://bsd-hardware.info/?probe=2323c300a7) | Dec 08, 2024 |
| Lenovo        | 3106                        | Desktop     | [05891a3893](https://bsd-hardware.info/?probe=05891a3893) | Dec 08, 2024 |
| Intel         | NUC6i7KYB H90766-409        | Mini pc     | [e5dbf6c1ae](https://bsd-hardware.info/?probe=e5dbf6c1ae) | Dec 08, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [1b2c50f225](https://bsd-hardware.info/?probe=1b2c50f225) | Dec 08, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [57a5cf527b](https://bsd-hardware.info/?probe=57a5cf527b) | Dec 08, 2024 |
| Unknown       | Unknown                     | Mini pc     | [137ac383dd](https://bsd-hardware.info/?probe=137ac383dd) | Dec 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [de026455d9](https://bsd-hardware.info/?probe=de026455d9) | Dec 08, 2024 |
| Supermicro    | A2SDi-8C+-HLN4F             | Server      | [aa0d856587](https://bsd-hardware.info/?probe=aa0d856587) | Dec 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [37f092637e](https://bsd-hardware.info/?probe=37f092637e) | Dec 08, 2024 |
| CncTion       | N4100-4L                    | Desktop     | [fba638f954](https://bsd-hardware.info/?probe=fba638f954) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [ccaad34955](https://bsd-hardware.info/?probe=ccaad34955) | Dec 07, 2024 |
| Acer          | Extensa 215-33              | Notebook    | [79a63f2804](https://bsd-hardware.info/?probe=79a63f2804) | Dec 07, 2024 |
| Acer          | Extensa 215-33              | Notebook    | [3d830ad581](https://bsd-hardware.info/?probe=3d830ad581) | Dec 07, 2024 |
| Huanan        | X58-RX3.0 V110              | Desktop     | [7aa0eb6533](https://bsd-hardware.info/?probe=7aa0eb6533) | Dec 07, 2024 |
| Timi          | TM1703                      | Notebook    | [6af452297e](https://bsd-hardware.info/?probe=6af452297e) | Dec 07, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [977d532fb8](https://bsd-hardware.info/?probe=977d532fb8) | Dec 07, 2024 |
| ASUSTek       | N550JV                      | Notebook    | [43db70e6e9](https://bsd-hardware.info/?probe=43db70e6e9) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [5c01d44547](https://bsd-hardware.info/?probe=5c01d44547) | Dec 07, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [fb966a942a](https://bsd-hardware.info/?probe=fb966a942a) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [33069a50a3](https://bsd-hardware.info/?probe=33069a50a3) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [3a099cfc0b](https://bsd-hardware.info/?probe=3a099cfc0b) | Dec 07, 2024 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [3ec2b38bad](https://bsd-hardware.info/?probe=3ec2b38bad) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [6435c060c8](https://bsd-hardware.info/?probe=6435c060c8) | Dec 07, 2024 |
| ASUSTek       | Q87I-PLUS                   | Desktop     | [9d857bfe96](https://bsd-hardware.info/?probe=9d857bfe96) | Dec 07, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [bf94f894cb](https://bsd-hardware.info/?probe=bf94f894cb) | Dec 07, 2024 |
| Protectli     | V1410                       | Desktop     | [78a29a9a78](https://bsd-hardware.info/?probe=78a29a9a78) | Dec 07, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [4edaabd936](https://bsd-hardware.info/?probe=4edaabd936) | Dec 07, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [ffa899367f](https://bsd-hardware.info/?probe=ffa899367f) | Dec 07, 2024 |
| Inventec      | Z CLASS A02                 | Desktop     | [57e4852f95](https://bsd-hardware.info/?probe=57e4852f95) | Dec 07, 2024 |
| Protectli     | VP2410 10                   | Desktop     | [0d08c971b8](https://bsd-hardware.info/?probe=0d08c971b8) | Dec 07, 2024 |
| Dell          | 0KYWH7 A03                  | Desktop     | [622105821f](https://bsd-hardware.info/?probe=622105821f) | Dec 07, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [55685eeb85](https://bsd-hardware.info/?probe=55685eeb85) | Dec 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [e1de59d2b5](https://bsd-hardware.info/?probe=e1de59d2b5) | Dec 06, 2024 |
| Lenovo        | 1052 NOK                    | Desktop     | [44cfb1316c](https://bsd-hardware.info/?probe=44cfb1316c) | Dec 06, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [24aae85abb](https://bsd-hardware.info/?probe=24aae85abb) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [3ad310c1ca](https://bsd-hardware.info/?probe=3ad310c1ca) | Dec 06, 2024 |
| ASUSTek       | EX-B760M-V5 D4              | Desktop     | [3bd2d25d6f](https://bsd-hardware.info/?probe=3bd2d25d6f) | Dec 06, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [831f538244](https://bsd-hardware.info/?probe=831f538244) | Dec 06, 2024 |
| Sophos        | XG                          | Firewall    | [10b1989db1](https://bsd-hardware.info/?probe=10b1989db1) | Dec 06, 2024 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [0ea05d2389](https://bsd-hardware.info/?probe=0ea05d2389) | Dec 06, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [65370691ec](https://bsd-hardware.info/?probe=65370691ec) | Dec 06, 2024 |
| Dell          | 05GD68 A00                  | Desktop     | [eb955cee95](https://bsd-hardware.info/?probe=eb955cee95) | Dec 06, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [f9113e9725](https://bsd-hardware.info/?probe=f9113e9725) | Dec 06, 2024 |
| HP            | 8267 A01                    | Mini pc     | [0bf934ba41](https://bsd-hardware.info/?probe=0bf934ba41) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [23b03d29a7](https://bsd-hardware.info/?probe=23b03d29a7) | Dec 06, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [5f8f2f10e2](https://bsd-hardware.info/?probe=5f8f2f10e2) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [5077b94887](https://bsd-hardware.info/?probe=5077b94887) | Dec 06, 2024 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [4e006e39f5](https://bsd-hardware.info/?probe=4e006e39f5) | Dec 06, 2024 |
| ASUSTek       | D500SA                      | Desktop     | [d1a788187e](https://bsd-hardware.info/?probe=d1a788187e) | Dec 06, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d024fa4f7a](https://bsd-hardware.info/?probe=d024fa4f7a) | Dec 06, 2024 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [7839a021dc](https://bsd-hardware.info/?probe=7839a021dc) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [365e2536fc](https://bsd-hardware.info/?probe=365e2536fc) | Dec 06, 2024 |
| Deciso        | Netboard A20                | Notebook    | [02f8326943](https://bsd-hardware.info/?probe=02f8326943) | Dec 06, 2024 |
| AMD           | Kabini CRB                  | Desktop     | [fb4786e02b](https://bsd-hardware.info/?probe=fb4786e02b) | Dec 06, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [18aef5be33](https://bsd-hardware.info/?probe=18aef5be33) | Dec 06, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [827453a946](https://bsd-hardware.info/?probe=827453a946) | Dec 06, 2024 |
| MSI           | B550M PRO-VDH               | Desktop     | [2bd3d72cbb](https://bsd-hardware.info/?probe=2bd3d72cbb) | Dec 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [a485fb61cf](https://bsd-hardware.info/?probe=a485fb61cf) | Dec 06, 2024 |
| HP            | 829A                        | Mini pc     | [25abfdcee7](https://bsd-hardware.info/?probe=25abfdcee7) | Dec 06, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [ebaa050586](https://bsd-hardware.info/?probe=ebaa050586) | Dec 06, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [7ea9d5b1c0](https://bsd-hardware.info/?probe=7ea9d5b1c0) | Dec 06, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [2f0fa2dd03](https://bsd-hardware.info/?probe=2f0fa2dd03) | Dec 05, 2024 |
| Sophos        | SG                          | Firewall    | [a7e440194c](https://bsd-hardware.info/?probe=a7e440194c) | Dec 05, 2024 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f61562fa69](https://bsd-hardware.info/?probe=f61562fa69) | Dec 05, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [fa4c1042c1](https://bsd-hardware.info/?probe=fa4c1042c1) | Dec 05, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [d35bd9310c](https://bsd-hardware.info/?probe=d35bd9310c) | Dec 05, 2024 |
| Dell          | Inspiron 5737               | Notebook    | [d63af5805c](https://bsd-hardware.info/?probe=d63af5805c) | Dec 05, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [c666ac8dd4](https://bsd-hardware.info/?probe=c666ac8dd4) | Dec 05, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [a33cf87751](https://bsd-hardware.info/?probe=a33cf87751) | Dec 05, 2024 |
| MSI           | Z77A-G41                    | Desktop     | [7091f79308](https://bsd-hardware.info/?probe=7091f79308) | Dec 05, 2024 |
| Protectli     | V1410                       | Desktop     | [f48eb4cb19](https://bsd-hardware.info/?probe=f48eb4cb19) | Dec 05, 2024 |
| Dell          | 0MFXTY A02                  | Server      | [38dcdd5ffe](https://bsd-hardware.info/?probe=38dcdd5ffe) | Dec 05, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [cb46ad0735](https://bsd-hardware.info/?probe=cb46ad0735) | Dec 05, 2024 |
| Unknown       | QGLK03                      | Desktop     | [1008c6a720](https://bsd-hardware.info/?probe=1008c6a720) | Dec 05, 2024 |
| Bomgar        | 0XN8Y6 A07                  | Server      | [4088468706](https://bsd-hardware.info/?probe=4088468706) | Dec 05, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [ca1c97cf99](https://bsd-hardware.info/?probe=ca1c97cf99) | Dec 05, 2024 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [63de24e596](https://bsd-hardware.info/?probe=63de24e596) | Dec 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [ddcf515a46](https://bsd-hardware.info/?probe=ddcf515a46) | Dec 05, 2024 |
| HP            | ProLiant DL360 G5           | Server      | [fb8e9a36d8](https://bsd-hardware.info/?probe=fb8e9a36d8) | Dec 05, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [664484892c](https://bsd-hardware.info/?probe=664484892c) | Dec 05, 2024 |
| Notebook      | N7x0WU                      | Notebook    | [d9312fac72](https://bsd-hardware.info/?probe=d9312fac72) | Dec 05, 2024 |
| Unknown       | ROUTER                      | Desktop     | [9af72def1f](https://bsd-hardware.info/?probe=9af72def1f) | Dec 05, 2024 |
| Sony          | SVE11115ELW                 | Notebook    | [6a33a5005f](https://bsd-hardware.info/?probe=6a33a5005f) | Dec 05, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [4bc73334bc](https://bsd-hardware.info/?probe=4bc73334bc) | Dec 04, 2024 |
| Cisco         | ASA5545 A0                  | Desktop     | [b125a557db](https://bsd-hardware.info/?probe=b125a557db) | Dec 04, 2024 |
| Dell          | 03X6X0 A08                  | Server      | [b5582e05c4](https://bsd-hardware.info/?probe=b5582e05c4) | Dec 04, 2024 |
| PC Engines    | APU2                        | Desktop     | [897b7914d9](https://bsd-hardware.info/?probe=897b7914d9) | Dec 04, 2024 |
| Intel         | D34010WYK H14771-303        | Desktop     | [cc9f37f097](https://bsd-hardware.info/?probe=cc9f37f097) | Dec 04, 2024 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [772e88509f](https://bsd-hardware.info/?probe=772e88509f) | Dec 04, 2024 |
| Dell          | Latitude 5591               | Notebook    | [fd917cf2f0](https://bsd-hardware.info/?probe=fd917cf2f0) | Dec 04, 2024 |
| Jetway        | NU93 Series                 | Desktop     | [2c30a868ac](https://bsd-hardware.info/?probe=2c30a868ac) | Dec 04, 2024 |
| HP            | 1998                        | Desktop     | [6233446d5e](https://bsd-hardware.info/?probe=6233446d5e) | Dec 04, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [8fbade62a5](https://bsd-hardware.info/?probe=8fbade62a5) | Dec 04, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [ce8e9f61b2](https://bsd-hardware.info/?probe=ce8e9f61b2) | Dec 04, 2024 |
| Unknown       | QDNV01                      | Desktop     | [a53dc0648b](https://bsd-hardware.info/?probe=a53dc0648b) | Dec 04, 2024 |
| MSI           | Z97 GAMING 3                | Desktop     | [9cd14a585d](https://bsd-hardware.info/?probe=9cd14a585d) | Dec 04, 2024 |
| HP            | 829A                        | Mini pc     | [a7db169329](https://bsd-hardware.info/?probe=a7db169329) | Dec 04, 2024 |
| HP            | 339A                        | Desktop     | [3c450d9163](https://bsd-hardware.info/?probe=3c450d9163) | Dec 04, 2024 |
| Dell          | 0RY206                      | Desktop     | [e72ddbe6c0](https://bsd-hardware.info/?probe=e72ddbe6c0) | Dec 04, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [8cb6acf4a0](https://bsd-hardware.info/?probe=8cb6acf4a0) | Dec 04, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [ff4d9d279d](https://bsd-hardware.info/?probe=ff4d9d279d) | Dec 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [8c4864ab24](https://bsd-hardware.info/?probe=8c4864ab24) | Dec 04, 2024 |
| Gigabyte      | 2AC8                        | Desktop     | [c18b3da04b](https://bsd-hardware.info/?probe=c18b3da04b) | Dec 04, 2024 |
| HP            | 250 G3                      | Notebook    | [102fa9b597](https://bsd-hardware.info/?probe=102fa9b597) | Dec 04, 2024 |
| SJRC          | ADLN-6L                     | Desktop     | [c0b65456f2](https://bsd-hardware.info/?probe=c0b65456f2) | Dec 04, 2024 |
| Gigabyte      | H81M-HD2                    | Desktop     | [2c74776cf6](https://bsd-hardware.info/?probe=2c74776cf6) | Dec 04, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [ba4099f218](https://bsd-hardware.info/?probe=ba4099f218) | Dec 04, 2024 |
| Dell          | 0TPV56 A02                  | Desktop     | [e219128ad8](https://bsd-hardware.info/?probe=e219128ad8) | Dec 04, 2024 |
| Supermicro    | X7DBU                       | Desktop     | [fc50e5a8a4](https://bsd-hardware.info/?probe=fc50e5a8a4) | Dec 04, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [6078d4ac6d](https://bsd-hardware.info/?probe=6078d4ac6d) | Dec 04, 2024 |
| Foxconn       | AHD1S                       | Desktop     | [de4e6051ae](https://bsd-hardware.info/?probe=de4e6051ae) | Dec 04, 2024 |
| AZW           | EQ                          | Desktop     | [8f20d42e6e](https://bsd-hardware.info/?probe=8f20d42e6e) | Dec 04, 2024 |
| Supermicro    | X10SLL-F                    | Server      | [20dfe1669b](https://bsd-hardware.info/?probe=20dfe1669b) | Dec 04, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [b75044f43a](https://bsd-hardware.info/?probe=b75044f43a) | Dec 04, 2024 |
| Dell          | Precision 5510              | Notebook    | [928a571c76](https://bsd-hardware.info/?probe=928a571c76) | Dec 03, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [c27e4750d2](https://bsd-hardware.info/?probe=c27e4750d2) | Dec 03, 2024 |
| ASUSTek       | P9D-C Series                | Server      | [fe5531ec9b](https://bsd-hardware.info/?probe=fe5531ec9b) | Dec 03, 2024 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [7c779086d3](https://bsd-hardware.info/?probe=7c779086d3) | Dec 03, 2024 |
| ASRock        | H310M-STX                   | Desktop     | [5dd43541fe](https://bsd-hardware.info/?probe=5dd43541fe) | Dec 03, 2024 |
| TUXEDO        | Pulse 14 Gen3               | Notebook    | [56a08b7475](https://bsd-hardware.info/?probe=56a08b7475) | Dec 03, 2024 |
| ZOTAC         | ZBOX-CI331NANO              | Mini pc     | [d403025ca9](https://bsd-hardware.info/?probe=d403025ca9) | Dec 03, 2024 |
| ASRock        | N100M                       | Desktop     | [530dd6daef](https://bsd-hardware.info/?probe=530dd6daef) | Dec 03, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [51b951d5b3](https://bsd-hardware.info/?probe=51b951d5b3) | Dec 03, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [fc7a91a826](https://bsd-hardware.info/?probe=fc7a91a826) | Dec 03, 2024 |
| Dell          | Latitude E6540              | Notebook    | [7e1c664559](https://bsd-hardware.info/?probe=7e1c664559) | Dec 03, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [82f3611fe4](https://bsd-hardware.info/?probe=82f3611fe4) | Dec 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [368413d1e9](https://bsd-hardware.info/?probe=368413d1e9) | Dec 03, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [196fb6634a](https://bsd-hardware.info/?probe=196fb6634a) | Dec 03, 2024 |
| Dell          | Latitude 5591               | Notebook    | [9515359a66](https://bsd-hardware.info/?probe=9515359a66) | Dec 03, 2024 |
| Alienware     | m15 R6                      | Notebook    | [477e29857e](https://bsd-hardware.info/?probe=477e29857e) | Dec 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b659f5f797](https://bsd-hardware.info/?probe=b659f5f797) | Dec 03, 2024 |
| Unknown       | QGLK03                      | Desktop     | [876aab4f16](https://bsd-hardware.info/?probe=876aab4f16) | Dec 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [deb68a93e0](https://bsd-hardware.info/?probe=deb68a93e0) | Dec 03, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [449237e52a](https://bsd-hardware.info/?probe=449237e52a) | Dec 03, 2024 |
| PC Engines    | APU2                        | Desktop     | [f80121914d](https://bsd-hardware.info/?probe=f80121914d) | Dec 03, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [06d16e6428](https://bsd-hardware.info/?probe=06d16e6428) | Dec 03, 2024 |
| Sophos        | SG                          | Firewall    | [6cd8acdd05](https://bsd-hardware.info/?probe=6cd8acdd05) | Dec 03, 2024 |
| Protectli     | V1410                       | Desktop     | [de051ba319](https://bsd-hardware.info/?probe=de051ba319) | Dec 03, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a6e076d9f](https://bsd-hardware.info/?probe=1a6e076d9f) | Dec 02, 2024 |
| HP            | 213D A01                    | Desktop     | [a005929c96](https://bsd-hardware.info/?probe=a005929c96) | Dec 02, 2024 |
| Advantech     | FWA-6520 A103-1             | Server      | [4ac3494599](https://bsd-hardware.info/?probe=4ac3494599) | Dec 02, 2024 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [804be89553](https://bsd-hardware.info/?probe=804be89553) | Dec 02, 2024 |
| HP            | ProLiant DL380 G6           | Server      | [8ac50a3d1f](https://bsd-hardware.info/?probe=8ac50a3d1f) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [dba4648bab](https://bsd-hardware.info/?probe=dba4648bab) | Dec 02, 2024 |
| MSI           | B560M-A PRO                 | Desktop     | [0b5305f2bd](https://bsd-hardware.info/?probe=0b5305f2bd) | Dec 02, 2024 |
| Intel         | QHSW02                      | Desktop     | [0815e2b553](https://bsd-hardware.info/?probe=0815e2b553) | Dec 02, 2024 |
| Alienware     | m15 R6                      | Notebook    | [b19c3ccd89](https://bsd-hardware.info/?probe=b19c3ccd89) | Dec 02, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [e3cc180fdd](https://bsd-hardware.info/?probe=e3cc180fdd) | Dec 02, 2024 |
| MSI           | H61M-P21                    | Desktop     | [55ae602922](https://bsd-hardware.info/?probe=55ae602922) | Dec 02, 2024 |
| Lenovo        | MAHOBAY Win8 Pro DPK MM ... | Desktop     | [4b79e0bdbe](https://bsd-hardware.info/?probe=4b79e0bdbe) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [6348954925](https://bsd-hardware.info/?probe=6348954925) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [bac0d075d9](https://bsd-hardware.info/?probe=bac0d075d9) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [c3a9c1cbc8](https://bsd-hardware.info/?probe=c3a9c1cbc8) | Dec 02, 2024 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [29d05d280a](https://bsd-hardware.info/?probe=29d05d280a) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [d5087399ae](https://bsd-hardware.info/?probe=d5087399ae) | Dec 02, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [5e6a2a3b36](https://bsd-hardware.info/?probe=5e6a2a3b36) | Dec 02, 2024 |
| Supermicro    | X11SPM-F                    | Server      | [3fdfe4a819](https://bsd-hardware.info/?probe=3fdfe4a819) | Dec 01, 2024 |
| Dell          | 0YJMC0 A02                  | Desktop     | [e266af3c4c](https://bsd-hardware.info/?probe=e266af3c4c) | Dec 01, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [2774e932cb](https://bsd-hardware.info/?probe=2774e932cb) | Dec 01, 2024 |
| Sophos        | SG                          | Firewall    | [a870c9860d](https://bsd-hardware.info/?probe=a870c9860d) | Dec 01, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [50ca527f2b](https://bsd-hardware.info/?probe=50ca527f2b) | Dec 01, 2024 |
| Biostar       | B450MH                      | Desktop     | [9596d106ab](https://bsd-hardware.info/?probe=9596d106ab) | Dec 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [d39e379bda](https://bsd-hardware.info/?probe=d39e379bda) | Dec 01, 2024 |
| Dell          | 0K240Y A02                  | Desktop     | [83b15fc400](https://bsd-hardware.info/?probe=83b15fc400) | Dec 01, 2024 |
| Sony          | VGN-FZ11MR                  | Notebook    | [0d1d0647c3](https://bsd-hardware.info/?probe=0d1d0647c3) | Dec 01, 2024 |
| MSI           | Z77A-G41                    | Desktop     | [76cc6deb79](https://bsd-hardware.info/?probe=76cc6deb79) | Dec 01, 2024 |
| MSI           | H81M-P33                    | Desktop     | [a910f6b4a8](https://bsd-hardware.info/?probe=a910f6b4a8) | Dec 01, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [dd9d2b4701](https://bsd-hardware.info/?probe=dd9d2b4701) | Dec 01, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [aaabbe33c6](https://bsd-hardware.info/?probe=aaabbe33c6) | Dec 01, 2024 |
| Quanmax       | KEEX-1660 B1                | Desktop     | [4943149603](https://bsd-hardware.info/?probe=4943149603) | Dec 01, 2024 |
| Supermicro    | X10SDV-F                    | Server      | [d08d4af555](https://bsd-hardware.info/?probe=d08d4af555) | Dec 01, 2024 |
| Unknown       | QGLK03                      | Desktop     | [80b9c73d39](https://bsd-hardware.info/?probe=80b9c73d39) | Dec 01, 2024 |
| Unknown       | QDNV01                      | Desktop     | [0a9ff22c6f](https://bsd-hardware.info/?probe=0a9ff22c6f) | Dec 01, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [c1d1a0a203](https://bsd-hardware.info/?probe=c1d1a0a203) | Dec 01, 2024 |
| Supermicro    | A1SRi 123456789             | Desktop     | [745f4b6682](https://bsd-hardware.info/?probe=745f4b6682) | Dec 01, 2024 |
| Protectli     | FW6                         | Desktop     | [3d8bb2e6ef](https://bsd-hardware.info/?probe=3d8bb2e6ef) | Dec 01, 2024 |
| HP            | 0A64h                       | Desktop     | [4d668a54a4](https://bsd-hardware.info/?probe=4d668a54a4) | Dec 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [f2d5915c37](https://bsd-hardware.info/?probe=f2d5915c37) | Dec 01, 2024 |
| Sophos        | XG                          | Firewall    | [8baa06b96b](https://bsd-hardware.info/?probe=8baa06b96b) | Dec 01, 2024 |
| Dell          | 0YY62T A00                  | Mini pc     | [ce9217ba9c](https://bsd-hardware.info/?probe=ce9217ba9c) | Dec 01, 2024 |
| Lenovo        | ThinkCentre M715q 10M2S0... | Desktop     | [9082d8b443](https://bsd-hardware.info/?probe=9082d8b443) | Dec 01, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [648268f0e3](https://bsd-hardware.info/?probe=648268f0e3) | Dec 01, 2024 |
| Protectli     | V1410                       | Desktop     | [c5b18a7a48](https://bsd-hardware.info/?probe=c5b18a7a48) | Dec 01, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [936f1cf164](https://bsd-hardware.info/?probe=936f1cf164) | Dec 01, 2024 |
| Gigabyte      | C1037UN                     | Desktop     | [881fe2dddd](https://bsd-hardware.info/?probe=881fe2dddd) | Nov 30, 2024 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [ee30758c43](https://bsd-hardware.info/?probe=ee30758c43) | Nov 30, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [20d9d6bd7b](https://bsd-hardware.info/?probe=20d9d6bd7b) | Nov 30, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [a070b11044](https://bsd-hardware.info/?probe=a070b11044) | Nov 30, 2024 |
| OEM           | BayTrail JHS60K             | Desktop     | [0e795e9e06](https://bsd-hardware.info/?probe=0e795e9e06) | Nov 30, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [cae7ae1e3f](https://bsd-hardware.info/?probe=cae7ae1e3f) | Nov 30, 2024 |
| HP            | ENVY 15                     | Notebook    | [c83ef9f375](https://bsd-hardware.info/?probe=c83ef9f375) | Nov 30, 2024 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [f2cfb3ce5d](https://bsd-hardware.info/?probe=f2cfb3ce5d) | Nov 30, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [60b74703c8](https://bsd-hardware.info/?probe=60b74703c8) | Nov 30, 2024 |
| Intel         | CM8I7CB8N K53740-202        | Mini pc     | [d29fa868ad](https://bsd-hardware.info/?probe=d29fa868ad) | Nov 30, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [d459b88a7a](https://bsd-hardware.info/?probe=d459b88a7a) | Nov 30, 2024 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [62ebe21a62](https://bsd-hardware.info/?probe=62ebe21a62) | Nov 30, 2024 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [fbca60a68a](https://bsd-hardware.info/?probe=fbca60a68a) | Nov 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [b3d7bdb73f](https://bsd-hardware.info/?probe=b3d7bdb73f) | Nov 30, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [5a7a5ce019](https://bsd-hardware.info/?probe=5a7a5ce019) | Nov 30, 2024 |
| CompuLab      | fitlet2                     | Mini pc     | [7775874cc7](https://bsd-hardware.info/?probe=7775874cc7) | Nov 30, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [528aaeeba1](https://bsd-hardware.info/?probe=528aaeeba1) | Nov 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [14ff86c47b](https://bsd-hardware.info/?probe=14ff86c47b) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [6c64235fcd](https://bsd-hardware.info/?probe=6c64235fcd) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [9c1cc3a80d](https://bsd-hardware.info/?probe=9c1cc3a80d) | Nov 29, 2024 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [2af8f99a1c](https://bsd-hardware.info/?probe=2af8f99a1c) | Nov 29, 2024 |
| Dell          | Precision 7730              | Notebook    | [57ea84435b](https://bsd-hardware.info/?probe=57ea84435b) | Nov 29, 2024 |
| HP            | 21B4 A01                    | Desktop     | [8540ec3124](https://bsd-hardware.info/?probe=8540ec3124) | Nov 29, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [9cfdbbc839](https://bsd-hardware.info/?probe=9cfdbbc839) | Nov 29, 2024 |
| Dell          | 0YXT71 A00                  | Desktop     | [11cad93f24](https://bsd-hardware.info/?probe=11cad93f24) | Nov 29, 2024 |
| Lenovo        | 0x30F617AA SDK0J40705 WI... | Desktop     | [793b039943](https://bsd-hardware.info/?probe=793b039943) | Nov 29, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | Notebook    | [c97d6bf769](https://bsd-hardware.info/?probe=c97d6bf769) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [28543148fe](https://bsd-hardware.info/?probe=28543148fe) | Nov 29, 2024 |
| Supermicro    | X7SPA-H                     | Desktop     | [dbfc4db35b](https://bsd-hardware.info/?probe=dbfc4db35b) | Nov 29, 2024 |
| Intel         | B75 V1.5                    | Desktop     | [a579cb0709](https://bsd-hardware.info/?probe=a579cb0709) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [6493258074](https://bsd-hardware.info/?probe=6493258074) | Nov 29, 2024 |
| Unknown       | PICO PC                     | Desktop     | [8734e8b7c0](https://bsd-hardware.info/?probe=8734e8b7c0) | Nov 29, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | Notebook    | [2bd04e188a](https://bsd-hardware.info/?probe=2bd04e188a) | Nov 29, 2024 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2e7399f5db](https://bsd-hardware.info/?probe=2e7399f5db) | Nov 29, 2024 |
| Sophos        | SG                          | Firewall    | [9d11a1ad73](https://bsd-hardware.info/?probe=9d11a1ad73) | Nov 29, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | Notebook    | [41ab1da986](https://bsd-hardware.info/?probe=41ab1da986) | Nov 29, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | Desktop     | [c1473102cc](https://bsd-hardware.info/?probe=c1473102cc) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [809babc888](https://bsd-hardware.info/?probe=809babc888) | Nov 29, 2024 |
| HP            | 3048h                       | Desktop     | [36a9b2f835](https://bsd-hardware.info/?probe=36a9b2f835) | Nov 29, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b6aaae01ed](https://bsd-hardware.info/?probe=b6aaae01ed) | Nov 29, 2024 |
| ASUSTek       | AM1M-A                      | Desktop     | [473deeae6a](https://bsd-hardware.info/?probe=473deeae6a) | Nov 29, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b9694f6726](https://bsd-hardware.info/?probe=b9694f6726) | Nov 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [7bb427cd81](https://bsd-hardware.info/?probe=7bb427cd81) | Nov 28, 2024 |
| Protectli     | FW1 Ver                     | Desktop     | [a8e980a004](https://bsd-hardware.info/?probe=a8e980a004) | Nov 28, 2024 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [adacb50c52](https://bsd-hardware.info/?probe=adacb50c52) | Nov 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [df4118ff92](https://bsd-hardware.info/?probe=df4118ff92) | Nov 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [88f7fc5770](https://bsd-hardware.info/?probe=88f7fc5770) | Nov 28, 2024 |
| CNCTION-IA... | Unknown                     | Desktop     | [84b6701f11](https://bsd-hardware.info/?probe=84b6701f11) | Nov 28, 2024 |
| ASRock        | E3C226D2I                   | Desktop     | [b872c811d8](https://bsd-hardware.info/?probe=b872c811d8) | Nov 28, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | Desktop     | [d99e7bd515](https://bsd-hardware.info/?probe=d99e7bd515) | Nov 28, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f309cf2bee](https://bsd-hardware.info/?probe=f309cf2bee) | Nov 28, 2024 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [ec03b89f9b](https://bsd-hardware.info/?probe=ec03b89f9b) | Nov 28, 2024 |
| Dell          | Inspiron 3195               | Convertible | [1fdcce2de5](https://bsd-hardware.info/?probe=1fdcce2de5) | Nov 28, 2024 |
| AZW           | GK mini                     | Mini pc     | [9825440c1f](https://bsd-hardware.info/?probe=9825440c1f) | Nov 28, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [63226167b4](https://bsd-hardware.info/?probe=63226167b4) | Nov 28, 2024 |
| Sony          | VGN-FZ11MR                  | Notebook    | [9d737dbace](https://bsd-hardware.info/?probe=9d737dbace) | Nov 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [cd7af4ce2e](https://bsd-hardware.info/?probe=cd7af4ce2e) | Nov 28, 2024 |
| Intel         | S1200RP_SE G62252-406       | Server      | [99d48c9cc8](https://bsd-hardware.info/?probe=99d48c9cc8) | Nov 28, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f1ade048b2](https://bsd-hardware.info/?probe=f1ade048b2) | Nov 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [369db2518f](https://bsd-hardware.info/?probe=369db2518f) | Nov 28, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b7056e45fd](https://bsd-hardware.info/?probe=b7056e45fd) | Nov 27, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8c4222d88e](https://bsd-hardware.info/?probe=8c4222d88e) | Nov 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [751c115ce9](https://bsd-hardware.info/?probe=751c115ce9) | Nov 27, 2024 |
| Sophos        | XG                          | Firewall    | [b5a6f6ee7e](https://bsd-hardware.info/?probe=b5a6f6ee7e) | Nov 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [6b95721cd2](https://bsd-hardware.info/?probe=6b95721cd2) | Nov 27, 2024 |
| Intel         | HURONRIVER                  | Desktop     | [d74d9a6d06](https://bsd-hardware.info/?probe=d74d9a6d06) | Nov 27, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [8282b592ac](https://bsd-hardware.info/?probe=8282b592ac) | Nov 27, 2024 |
| Dell          | Latitude 5320               | Notebook    | [aeca583292](https://bsd-hardware.info/?probe=aeca583292) | Nov 27, 2024 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [c7a9e9bf80](https://bsd-hardware.info/?probe=c7a9e9bf80) | Nov 27, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [c37d3ec1c3](https://bsd-hardware.info/?probe=c37d3ec1c3) | Nov 27, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ba28a2eea4](https://bsd-hardware.info/?probe=ba28a2eea4) | Nov 27, 2024 |
| Lenovo        | 3106                        | Desktop     | [e7b6dda1e1](https://bsd-hardware.info/?probe=e7b6dda1e1) | Nov 27, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [f13e4185c7](https://bsd-hardware.info/?probe=f13e4185c7) | Nov 27, 2024 |
| Dell          | 02C2CP A02                  | Server      | [1de5f56857](https://bsd-hardware.info/?probe=1de5f56857) | Nov 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [a54f295009](https://bsd-hardware.info/?probe=a54f295009) | Nov 27, 2024 |
| Lex           | Pineview-D                  | Desktop     | [6f71f5ede3](https://bsd-hardware.info/?probe=6f71f5ede3) | Nov 27, 2024 |
| Unknown       | J3160-4L                    | Desktop     | [aec90e7441](https://bsd-hardware.info/?probe=aec90e7441) | Nov 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [81d5169045](https://bsd-hardware.info/?probe=81d5169045) | Nov 27, 2024 |
| CncTion       | J4125-4L-I225               | Desktop     | [a6541ec947](https://bsd-hardware.info/?probe=a6541ec947) | Nov 27, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [ff2f3667a7](https://bsd-hardware.info/?probe=ff2f3667a7) | Nov 27, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [37485fe00d](https://bsd-hardware.info/?probe=37485fe00d) | Nov 27, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [0c14321a2f](https://bsd-hardware.info/?probe=0c14321a2f) | Nov 27, 2024 |
| SJRC          | ADLN-6L                     | Desktop     | [3791b6b9f6](https://bsd-hardware.info/?probe=3791b6b9f6) | Nov 27, 2024 |
| PC Engines    | APU2                        | Desktop     | [3bb3762d21](https://bsd-hardware.info/?probe=3bb3762d21) | Nov 27, 2024 |
| DFI           | CM100-C                     | Desktop     | [d2f2f98f5f](https://bsd-hardware.info/?probe=d2f2f98f5f) | Nov 26, 2024 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [282a433650](https://bsd-hardware.info/?probe=282a433650) | Nov 26, 2024 |
| Protectli     | V1210                       | Desktop     | [e53f0f593a](https://bsd-hardware.info/?probe=e53f0f593a) | Nov 26, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [6d2e2757a1](https://bsd-hardware.info/?probe=6d2e2757a1) | Nov 26, 2024 |
| Unknown       | QDNV01                      | Desktop     | [12a6adb846](https://bsd-hardware.info/?probe=12a6adb846) | Nov 26, 2024 |
| PC Engines    | APU                         | Desktop     | [71452ad950](https://bsd-hardware.info/?probe=71452ad950) | Nov 26, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ae71831e6c](https://bsd-hardware.info/?probe=ae71831e6c) | Nov 26, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [208feb98b3](https://bsd-hardware.info/?probe=208feb98b3) | Nov 26, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [1f1948481c](https://bsd-hardware.info/?probe=1f1948481c) | Nov 26, 2024 |
| ETegro Tec... | ETRS130G3 31S98MB0020       | Server      | [1578aa6cfd](https://bsd-hardware.info/?probe=1578aa6cfd) | Nov 26, 2024 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [5efd7ff2d7](https://bsd-hardware.info/?probe=5efd7ff2d7) | Nov 26, 2024 |
| Unknown       | QDNV01                      | Desktop     | [98aafbcae9](https://bsd-hardware.info/?probe=98aafbcae9) | Nov 26, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [c8d95da1f8](https://bsd-hardware.info/?probe=c8d95da1f8) | Nov 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [9fe8114bf0](https://bsd-hardware.info/?probe=9fe8114bf0) | Nov 26, 2024 |
| Protectli     | FW6                         | Desktop     | [c05460d9ae](https://bsd-hardware.info/?probe=c05460d9ae) | Nov 26, 2024 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [f58d8e2122](https://bsd-hardware.info/?probe=f58d8e2122) | Nov 26, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [db040ae85a](https://bsd-hardware.info/?probe=db040ae85a) | Nov 26, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a25be40b42](https://bsd-hardware.info/?probe=a25be40b42) | Nov 26, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [6cae463825](https://bsd-hardware.info/?probe=6cae463825) | Nov 26, 2024 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [41e7363228](https://bsd-hardware.info/?probe=41e7363228) | Nov 25, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [3caad40c2a](https://bsd-hardware.info/?probe=3caad40c2a) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [7a03bbeb04](https://bsd-hardware.info/?probe=7a03bbeb04) | Nov 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [300e6c8024](https://bsd-hardware.info/?probe=300e6c8024) | Nov 25, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [2626f42aad](https://bsd-hardware.info/?probe=2626f42aad) | Nov 25, 2024 |
| Unknown       | QDNV01                      | Desktop     | [b61894118e](https://bsd-hardware.info/?probe=b61894118e) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [36ab98d9df](https://bsd-hardware.info/?probe=36ab98d9df) | Nov 25, 2024 |
| NU591         | 1.0                         | Desktop     | [4d0ba5d745](https://bsd-hardware.info/?probe=4d0ba5d745) | Nov 25, 2024 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [3227464ae4](https://bsd-hardware.info/?probe=3227464ae4) | Nov 25, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [c472067efe](https://bsd-hardware.info/?probe=c472067efe) | Nov 25, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [5ab919a780](https://bsd-hardware.info/?probe=5ab919a780) | Nov 25, 2024 |
| PC Engines    | APU3                        | Desktop     | [87ce049caa](https://bsd-hardware.info/?probe=87ce049caa) | Nov 25, 2024 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [6554ebbcca](https://bsd-hardware.info/?probe=6554ebbcca) | Nov 25, 2024 |
| Supermicro    | X11SDW-8C-TP13F             | Desktop     | [27385b062c](https://bsd-hardware.info/?probe=27385b062c) | Nov 25, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [e5d3e617f3](https://bsd-hardware.info/?probe=e5d3e617f3) | Nov 25, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [6379c6aa6d](https://bsd-hardware.info/?probe=6379c6aa6d) | Nov 25, 2024 |
| iEi           | B542 V1.00                  | Desktop     | [fc2b00d368](https://bsd-hardware.info/?probe=fc2b00d368) | Nov 24, 2024 |
| Dell          | Latitude E5440              | Notebook    | [289f3c134f](https://bsd-hardware.info/?probe=289f3c134f) | Nov 24, 2024 |
| Sophos        | XG                          | Firewall    | [1dcbc78986](https://bsd-hardware.info/?probe=1dcbc78986) | Nov 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [39f209659c](https://bsd-hardware.info/?probe=39f209659c) | Nov 24, 2024 |
| Intel         | SKYBAY                      | Desktop     | [7e0118128c](https://bsd-hardware.info/?probe=7e0118128c) | Nov 24, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [dc3d4a1f8d](https://bsd-hardware.info/?probe=dc3d4a1f8d) | Nov 24, 2024 |
| PC Engines    | APU2                        | Desktop     | [9b16a6c6f0](https://bsd-hardware.info/?probe=9b16a6c6f0) | Nov 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [52c9820eec](https://bsd-hardware.info/?probe=52c9820eec) | Nov 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [984986d630](https://bsd-hardware.info/?probe=984986d630) | Nov 24, 2024 |
| MSI           | H81M-P33                    | Desktop     | [9e5c756f1f](https://bsd-hardware.info/?probe=9e5c756f1f) | Nov 24, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [2d7f40d5f5](https://bsd-hardware.info/?probe=2d7f40d5f5) | Nov 24, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ed997ac3e9](https://bsd-hardware.info/?probe=ed997ac3e9) | Nov 24, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [1abb405f84](https://bsd-hardware.info/?probe=1abb405f84) | Nov 24, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [dd77e68b2d](https://bsd-hardware.info/?probe=dd77e68b2d) | Nov 24, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | Desktop     | [acfb1a77bf](https://bsd-hardware.info/?probe=acfb1a77bf) | Nov 24, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [d30555f031](https://bsd-hardware.info/?probe=d30555f031) | Nov 24, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [89939b2c85](https://bsd-hardware.info/?probe=89939b2c85) | Nov 24, 2024 |
| Trigkey       | Green G5                    | Desktop     | [610e4d3506](https://bsd-hardware.info/?probe=610e4d3506) | Nov 24, 2024 |
| HP            | Pavilion g6                 | Notebook    | [25f47fd8d4](https://bsd-hardware.info/?probe=25f47fd8d4) | Nov 24, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [d66960aa84](https://bsd-hardware.info/?probe=d66960aa84) | Nov 24, 2024 |
| Deciso        | Netboard A8                 | Desktop     | [5b1cde4aac](https://bsd-hardware.info/?probe=5b1cde4aac) | Nov 24, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7453fe50fc](https://bsd-hardware.info/?probe=7453fe50fc) | Nov 23, 2024 |
| ETegro Tec... | ETRS130G3 31S98MB0020       | Server      | [153808018a](https://bsd-hardware.info/?probe=153808018a) | Nov 23, 2024 |
| Dell          | 0W3F1J A00                  | Mini pc     | [23d366fbc4](https://bsd-hardware.info/?probe=23d366fbc4) | Nov 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [916dbf4386](https://bsd-hardware.info/?probe=916dbf4386) | Nov 23, 2024 |
| PC Engines    | APU2                        | Desktop     | [8b9f47de00](https://bsd-hardware.info/?probe=8b9f47de00) | Nov 23, 2024 |
| Dell          | 0PJDGF A02                  | Desktop     | [4a83b7b9c8](https://bsd-hardware.info/?probe=4a83b7b9c8) | Nov 23, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [8a4a441c60](https://bsd-hardware.info/?probe=8a4a441c60) | Nov 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [3315220d61](https://bsd-hardware.info/?probe=3315220d61) | Nov 23, 2024 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [577dc596e5](https://bsd-hardware.info/?probe=577dc596e5) | Nov 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [b68fea4f7c](https://bsd-hardware.info/?probe=b68fea4f7c) | Nov 23, 2024 |
| Supermicro    | A2SAP-H                     | Desktop     | [a4f5dc75b5](https://bsd-hardware.info/?probe=a4f5dc75b5) | Nov 23, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [1dcf4cbd3d](https://bsd-hardware.info/?probe=1dcf4cbd3d) | Nov 23, 2024 |
| Sophos        | SG                          | Firewall    | [4014fa281a](https://bsd-hardware.info/?probe=4014fa281a) | Nov 23, 2024 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.8.1 | 577       | 2.52%   |
| helloSystem 0.7.0 | 452       | 1.97%   |
| OPNsense 23.1.11  | 367       | 1.6%    |
| OPNsense 24.1.6   | 297       | 1.3%    |
| OPNsense 21.7.7   | 281       | 1.23%   |
| OPNsense 23.7.10  | 270       | 1.18%   |
| OPNsense 22.7.10  | 262       | 1.14%   |
| helloSystem 0.8.0 | 254       | 1.11%   |
| OPNsense 24.7.11  | 253       | 1.1%    |
| helloSystem 0.5.0 | 245       | 1.07%   |
| OPNsense 23.7.12  | 242       | 1.06%   |
| OPNsense 21.1     | 240       | 1.05%   |
| FreeBSD 13.1      | 236       | 1.03%   |
| OPNsense 23.1     | 230       | 1%      |
| OPNsense 21.7.1   | 229       | 1%      |
| OPNsense 24.7     | 227       | 0.99%   |
| OPNsense 22.1     | 227       | 0.99%   |
| OPNsense 24.1.10  | 226       | 0.99%   |
| OPNsense 21.7.3   | 225       | 0.98%   |
| OPNsense 21.1.5   | 224       | 0.98%   |
| FreeBSD 13.0      | 223       | 0.97%   |
| OPNsense 23.1.5   | 221       | 0.96%   |
| OPNsense 23.7.9   | 220       | 0.96%   |
| OPNsense 24.1.9   | 217       | 0.95%   |
| OPNsense 22.7.4   | 214       | 0.93%   |
| OPNsense 20.7.8   | 214       | 0.93%   |
| OPNsense 24.7.8   | 213       | 0.93%   |
| OpenBSD 6.8       | 208       | 0.91%   |
| OPNsense 21.1.3   | 205       | 0.9%    |
| OPNsense 24.7.4   | 197       | 0.86%   |
| OPNsense 23.1.7   | 196       | 0.86%   |
| OPNsense 24.1.4   | 192       | 0.84%   |
| OPNsense 23.1.1   | 192       | 0.84%   |
| OPNsense 22.1.6   | 192       | 0.84%   |
| OPNsense 22.1.10  | 192       | 0.84%   |
| OPNsense 24.7.7   | 191       | 0.83%   |
| helloSystem 0.4.0 | 190       | 0.83%   |
| OPNsense 24.7.5   | 189       | 0.83%   |
| OPNsense 24.7.6   | 188       | 0.82%   |
| OPNsense 22.1.8   | 187       | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 10044     | 59.3%   |
| FreeBSD     | 3177      | 18.76%  |
| helloSystem | 1966      | 11.61%  |
| OpenBSD     | 730       | 4.31%   |
| GhostBSD    | 386       | 2.28%   |
| NomadBSD    | 227       | 1.34%   |
| NetBSD      | 122       | 0.72%   |
| TrueNAS     | 58        | 0.34%   |
| pfSense     | 39        | 0.23%   |
| MyBee       | 37        | 0.22%   |
| FreeNAS     | 30        | 0.18%   |
| MidnightBSD | 22        | 0.13%   |
| HardenedBSD | 21        | 0.12%   |
| DragonFly   | 20        | 0.12%   |
| XigmaNAS    | 19        | 0.11%   |
| FuryBSD     | 12        | 0.07%   |
| ClonOS      | 9         | 0.05%   |
| FuguIta     | 7         | 0.04%   |
| Ting        | 4         | 0.02%   |
| OS108       | 4         | 0.02%   |
| PC-BSD      | 3         | 0.02%   |
| LibertyBSD  | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 16327     | 97.78%  |
| i386    | 160       | 0.96%   |
| arm64   | 150       | 0.9%    |
| evbarm  | 16        | 0.1%    |
| arm     | 14        | 0.08%   |
| macppc  | 11        | 0.07%   |
| sparc64 | 7         | 0.04%   |
| powerpc | 6         | 0.04%   |
| armv7   | 3         | 0.02%   |
| octeon  | 2         | 0.01%   |
| riscv   | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 11464     | 67.03%  |
| helloDesktop  | 2263      | 13.23%  |
| XFCE          | 710       | 4.15%   |
| KDE5          | 600       | 3.51%   |
| MATE          | 495       | 2.89%   |
| GNOME         | 281       | 1.64%   |
| fvwm          | 277       | 1.62%   |
| TWM           | 254       | 1.49%   |
| Openbox       | 242       | 1.41%   |
| i3            | 144       | 0.84%   |
| LXQt          | 49        | 0.29%   |
| Cinnamon      | 42        | 0.25%   |
| AwesomeWM     | 34        | 0.2%    |
| Fluxbox       | 29        | 0.17%   |
| Enlightenment | 28        | 0.16%   |
| LXDE          | 17        | 0.1%    |
| DWM           | 17        | 0.1%    |
| xinitrc       | 14        | 0.08%   |
| Lumina        | 12        | 0.07%   |
| X-Cinnamon    | 10        | 0.06%   |
| Picom         | 8         | 0.05%   |
| KDE           | 8         | 0.05%   |
| ICEWM         | 8         | 0.05%   |
| GNUstep       | 7         | 0.04%   |
| ctwm          | 7         | 0.04%   |
| Window Maker  | 6         | 0.04%   |
| Hyprland      | 6         | 0.04%   |
| Budgie        | 6         | 0.04%   |
| wlroots       | 5         | 0.03%   |
| spectrwm      | 5         | 0.03%   |
| CDE           | 5         | 0.03%   |
| xfwm          | 4         | 0.02%   |
| sway          | 4         | 0.02%   |
| iwm           | 4         | 0.02%   |
| stumpwm       | 3         | 0.02%   |
| KDE6          | 3         | 0.02%   |
| Compton       | 3         | 0.02%   |
| Xfwm4         | 2         | 0.01%   |
| WindowMaker   | 2         | 0.01%   |
| Wayfire       | 2         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 11590     | 69.04%  |
| X11     | 5088      | 30.31%  |
| Wayland | 109       | 0.65%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 12788     | 75.36%  |
| SLiM    | 2420      | 14.26%  |
| SDDM    | 684       | 4.03%   |
| LightDM | 656       | 3.87%   |
| XDM     | 207       | 1.22%   |
| GDM     | 174       | 1.03%   |
| Ly      | 38        | 0.22%   |
| PCDM    | 2         | 0.01%   |
| WDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 11609     | 67.59%  |
| en_US           | 2247      | 13.08%  |
| C               | 1963      | 11.43%  |
| ru_RU           | 257       | 1.5%    |
| fr_FR           | 213       | 1.24%   |
| de_DE           | 159       | 0.93%   |
| en              | 92        | 0.54%   |
| es_ES           | 84        | 0.49%   |
| en_GB           | 73        | 0.43%   |
| pt_BR           | 44        | 0.26%   |
| it_IT           | 39        | 0.23%   |
| zh_CN           | 38        | 0.22%   |
| pl_PL           | 37        | 0.22%   |
| en_CA           | 20        | 0.12%   |
| en_AU           | 18        | 0.1%    |
| fr              | 17        | 0.1%    |
| ja_JP           | 15        | 0.09%   |
| ru              | 14        | 0.08%   |
| fi_FI           | 14        | 0.08%   |
| zh_TW           | 11        | 0.06%   |
| uk_UA           | 10        | 0.06%   |
| nl_NL           | 10        | 0.06%   |
| pt              | 9         | 0.05%   |
| es              | 9         | 0.05%   |
| en_IE           | 9         | 0.05%   |
| de              | 9         | 0.05%   |
| tr_TR           | 8         | 0.05%   |
| pt_PT           | 7         | 0.04%   |
| nb_NO           | 7         | 0.04%   |
| hu_HU           | 7         | 0.04%   |
| cs_CZ           | 7         | 0.04%   |
| es_AR           | 6         | 0.03%   |
| sv_SE           | 5         | 0.03%   |
| en_US.ISO8859-1 | 5         | 0.03%   |
| en_NZ           | 5         | 0.03%   |
| el_GR           | 5         | 0.03%   |
| de_CH           | 5         | 0.03%   |
| ru_RU.KOI8-R    | 4         | 0.02%   |
| ko_KR           | 4         | 0.02%   |
| jp_JP           | 4         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 14533     | 86.16%  |
| BIOS | 2334      | 13.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 8068      | 46.8%   |
| Ufs     | 7573      | 43.93%  |
| Cd9660  | 824       | 4.78%   |
| Ffs     | 739       | 4.29%   |
| Hammer2 | 19        | 0.11%   |
| Unknown | 7         | 0.04%   |
| XXX     | 3         | 0.02%   |
| Nfs     | 2         | 0.01%   |
| Xfs     | 1         | 0.01%   |
| Nullfs  | 1         | 0.01%   |
| Msdosfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 15521     | 92.37%  |
| MBR     | 1080      | 6.43%   |
| Unknown | 179       | 1.07%   |
| BSD     | 23        | 0.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 1833      | 10.98%  |
| Dell                                 | 1824      | 10.93%  |
| Lenovo                               | 1648      | 9.87%   |
| Hewlett-Packard                      | 1395      | 8.36%   |
| ASUSTek Computer                     | 1305      | 7.82%   |
| Intel                                | 774       | 4.64%   |
| Supermicro                           | 701       | 4.2%    |
| Gigabyte Technology                  | 686       | 4.11%   |
| ASRock                               | 566       | 3.39%   |
| Protectli                            | 537       | 3.22%   |
| MSI                                  | 428       | 2.56%   |
| PC Engines                           | 426       | 2.55%   |
| Fujitsu                              | 341       | 2.04%   |
| AMI                                  | 308       | 1.85%   |
| Sophos                               | 297       | 1.78%   |
| Acer                                 | 261       | 1.56%   |
| Apple                                | 252       | 1.51%   |
| Techvision                           | 193       | 1.16%   |
| Deciso                               | 177       | 1.06%   |
| ZOTAC                                | 132       | 0.79%   |
| AZW                                  | 124       | 0.74%   |
| Shuttle                              | 93        | 0.56%   |
| BESSTAR Tech                         | 91        | 0.55%   |
| MW                                   | 70        | 0.42%   |
| Toshiba                              | 69        | 0.41%   |
| CWWK                                 | 68        | 0.41%   |
| Samsung Electronics                  | 65        | 0.39%   |
| CncTion                              | 56        | 0.34%   |
| IceWhale Technology                  | 54        | 0.32%   |
| ASRockRack                           | 54        | 0.32%   |
| Raspberry Pi Foundation              | 53        | 0.32%   |
| Shenzhen Meigao Electronic Equipment | 52        | 0.31%   |
| Biostar                              | 52        | 0.31%   |
| AWOW                                 | 47        | 0.28%   |
| Sony                                 | 44        | 0.26%   |
| Hardkernel                           | 44        | 0.26%   |
| IBM                                  | 43        | 0.26%   |
| Google                               | 43        | 0.26%   |
| GoWin Solution                       | 37        | 0.22%   |
| Foxconn                              | 37        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 1889      | 11.32%  |
| AMI Aptio CRB                                     | 227       | 1.36%   |
| PC Engines APU2                                   | 207       | 1.24%   |
| Supermicro Super Server                           | 198       | 1.19%   |
| Techvision TVI7309X                               | 193       | 1.16%   |
| Sophos SG                                         | 164       | 0.98%   |
| Protectli FW4B                                    | 150       | 0.9%    |
| Intel Q3XXG4-P V1.0                               | 148       | 0.89%   |
| PC Engines apu4                                   | 134       | 0.8%    |
| Protectli FW6                                     | 119       | 0.71%   |
| ASUS All Series                                   | 119       | 0.71%   |
| Fujitsu FUTRO S920                                | 118       | 0.71%   |
| Sophos XG                                         | 92        | 0.55%   |
| HP t730 Thin Client                               | 75        | 0.45%   |
| Dell OptiPlex 9020                                | 72        | 0.43%   |
| HP t620 PLUS Quad Core TC                         | 71        | 0.43%   |
| MW GMLK-2_5G4L                                    | 70        | 0.42%   |
| Protectli VP2420                                  | 64        | 0.38%   |
| Dell PowerEdge R210 II                            | 63        | 0.38%   |
| AZW EQ                                            | 63        | 0.38%   |
| Dell OptiPlex 3020                                | 62        | 0.37%   |
| Dell OptiPlex 7010                                | 56        | 0.34%   |
| Shenzhen Meigao Electronic Equipment Venus series | 45        | 0.27%   |
| Dell Wyse 5070 Extended Thin Client               | 45        | 0.27%   |
| Deciso NetBoard-A20                               | 44        | 0.26%   |
| HP EliteDesk 800 G1 SFF                           | 42        | 0.25%   |
| Dell OptiPlex 7040                                | 42        | 0.25%   |
| RPi Raspberry Pi                                  | 41        | 0.25%   |
| Protectli FW4C                                    | 40        | 0.24%   |
| Sophos UTM                                        | 39        | 0.23%   |
| Supermicro X10SLH-N6-ST031                        | 38        | 0.23%   |
| BESSTAR Tech GK41                                 | 37        | 0.22%   |
| Protectli VP2410                                  | 36        | 0.22%   |
| IceWhale ZimaBoard 832 ZMB                        | 36        | 0.22%   |
| Supermicro A1SAi                                  | 35        | 0.21%   |
| Supermicro X9SCL/X9SCM                            | 34        | 0.2%    |
| Protectli FW2B                                    | 33        | 0.2%    |
| PC Engines APU                                    | 33        | 0.2%    |
| Hardkernel ODROID-H2                              | 33        | 0.2%    |
| Dell OptiPlex 7050                                | 32        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1889      | 11.32%  |
| Lenovo ThinkPad     | 860       | 5.15%   |
| Dell OptiPlex       | 668       | 4%      |
| Dell PowerEdge      | 404       | 2.42%   |
| Lenovo ThinkCentre  | 401       | 2.4%    |
| AMI Aptio           | 229       | 1.37%   |
| Dell Latitude       | 223       | 1.34%   |
| ASUS PRIME          | 210       | 1.26%   |
| PC Engines APU2     | 207       | 1.24%   |
| HP ProLiant         | 204       | 1.22%   |
| Supermicro Super    | 198       | 1.19%   |
| Techvision TVI7309X | 193       | 1.16%   |
| HP EliteDesk        | 180       | 1.08%   |
| Dell Inspiron       | 172       | 1.03%   |
| Fujitsu FUTRO       | 170       | 1.02%   |
| Sophos SG           | 164       | 0.98%   |
| Acer Aspire         | 163       | 0.98%   |
| HP Compaq           | 159       | 0.95%   |
| Protectli FW4B      | 150       | 0.9%    |
| Intel Q3XXG4-P      | 150       | 0.9%    |
| HP ProDesk          | 149       | 0.89%   |
| PC Engines apu4     | 134       | 0.8%    |
| Dell Precision      | 130       | 0.78%   |
| Protectli FW6       | 119       | 0.71%   |
| ASUS All            | 119       | 0.71%   |
| Lenovo IdeaPad      | 108       | 0.65%   |
| ASUS ROG            | 100       | 0.6%    |
| ASUS TUF            | 93        | 0.56%   |
| Sophos XG           | 92        | 0.55%   |
| HP t620             | 79        | 0.47%   |
| HP Pavilion         | 77        | 0.46%   |
| HP t730             | 76        | 0.46%   |
| HP EliteBook        | 72        | 0.43%   |
| MW GMLK-2           | 70        | 0.42%   |
| Dell Wyse           | 69        | 0.41%   |
| Protectli VP2420    | 64        | 0.38%   |
| AZW EQ              | 63        | 0.38%   |
| Deciso Netboard     | 62        | 0.37%   |
| Fujitsu ESPRIMO     | 53        | 0.32%   |
| RPi Raspberry       | 52        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1593      | 9.54%   |
| 2022    | 1469      | 8.8%    |
| 2021    | 1323      | 7.93%   |
| 2020    | 1283      | 7.69%   |
| 2019    | 1233      | 7.39%   |
| 2023    | 1182      | 7.08%   |
| 2016    | 1172      | 7.02%   |
| 2014    | 1153      | 6.91%   |
| 2017    | 1037      | 6.21%   |
| 2013    | 952       | 5.7%    |
| 2012    | 820       | 4.91%   |
| 2015    | 776       | 4.65%   |
| 2011    | 745       | 4.46%   |
| 2010    | 480       | 2.88%   |
| 2024    | 383       | 2.29%   |
| 2009    | 343       | 2.05%   |
| 2008    | 279       | 1.67%   |
| Unknown | 228       | 1.37%   |
| 2007    | 131       | 0.78%   |
| 2006    | 61        | 0.37%   |
| 2005    | 19        | 0.11%   |
| 2004    | 12        | 0.07%   |
| 2003    | 9         | 0.05%   |
| 2002    | 5         | 0.03%   |
| 2001    | 3         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 10265     | 61.5%   |
| Notebook       | 3445      | 20.64%  |
| Mini pc        | 1247      | 7.47%   |
| Server         | 1140      | 6.83%   |
| Firewall       | 346       | 2.07%   |
| System on chip | 82        | 0.49%   |
| All in one     | 80        | 0.48%   |
| Convertible    | 70        | 0.42%   |
| Tablet         | 15        | 0.09%   |
| Stick pc       | 1         | 0.01%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16031     | 96.03%  |
| Yes  | 662       | 3.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 6016      | 35.2%   |
| 16.01-24.0      | 4218      | 24.68%  |
| 4.01-8.0        | 3119      | 18.25%  |
| 32.01-64.0      | 1743      | 10.2%   |
| 64.01-256.0     | 754       | 4.41%   |
| 2.01-3.0        | 531       | 3.11%   |
| 24.01-32.0      | 226       | 1.32%   |
| 3.01-4.0        | 211       | 1.23%   |
| 0.51-1.0        | 108       | 0.63%   |
| 1.01-2.0        | 71        | 0.42%   |
| More than 256.0 | 46        | 0.27%   |
| 0.01-0.5        | 45        | 0.26%   |
| Unknown         | 2         | 0.01%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 8050      | 46.58%  |
| 0.51-1.0        | 5590      | 32.35%  |
| 1.01-2.0        | 2151      | 12.45%  |
| 2.01-3.0        | 503       | 2.91%   |
| 4.01-8.0        | 272       | 1.57%   |
| 3.01-4.0        | 206       | 1.19%   |
| Unknown         | 137       | 0.79%   |
| 8.01-16.0       | 120       | 0.69%   |
| 0               | 85        | 0.49%   |
| 16.01-24.0      | 52        | 0.3%    |
| 24.01-32.0      | 49        | 0.28%   |
| 32.01-64.0      | 41        | 0.24%   |
| 64.01-256.0     | 25        | 0.14%   |
| More than 256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 11188     | 64.24%  |
| 0      | 2590      | 14.87%  |
| 2      | 2246      | 12.9%   |
| 3      | 590       | 3.39%   |
| 4      | 332       | 1.91%   |
| 5      | 161       | 0.92%   |
| 6      | 97        | 0.56%   |
| 7      | 53        | 0.3%    |
| 8      | 34        | 0.2%    |
| 10     | 21        | 0.12%   |
| 14     | 19        | 0.11%   |
| 9      | 19        | 0.11%   |
| 12     | 15        | 0.09%   |
| 11     | 10        | 0.06%   |
| 17     | 6         | 0.03%   |
| 25     | 4         | 0.02%   |
| 16     | 4         | 0.02%   |
| 13     | 4         | 0.02%   |
| 18     | 3         | 0.02%   |
| 15     | 3         | 0.02%   |
| 58     | 2         | 0.01%   |
| 40     | 2         | 0.01%   |
| 24     | 2         | 0.01%   |
| 23     | 2         | 0.01%   |
| 21     | 2         | 0.01%   |
| 19     | 2         | 0.01%   |
| 63     | 1         | 0.01%   |
| 30     | 1         | 0.01%   |
| 28     | 1         | 0.01%   |
| 27     | 1         | 0.01%   |
| 26     | 1         | 0.01%   |
| 22     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 13926     | 82.74%  |
| Yes       | 2906      | 17.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15891     | 95.18%  |
| No        | 804       | 4.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 10674     | 63.36%  |
| Yes       | 6173      | 36.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 12418     | 73.79%  |
| Yes       | 4410      | 26.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 4400      | 26.22%  |
| Germany      | 2671      | 15.92%  |
| Russia       | 831       | 4.95%   |
| UK           | 689       | 4.11%   |
| Canada       | 674       | 4.02%   |
| France       | 645       | 3.84%   |
| Australia    | 443       | 2.64%   |
| Poland       | 439       | 2.62%   |
| Netherlands  | 409       | 2.44%   |
| Brazil       | 393       | 2.34%   |
| Italy        | 338       | 2.01%   |
| Switzerland  | 311       | 1.85%   |
| Spain        | 286       | 1.7%    |
| Austria      | 273       | 1.63%   |
| Sweden       | 257       | 1.53%   |
| China        | 248       | 1.48%   |
| Romania      | 154       | 0.92%   |
| Finland      | 153       | 0.91%   |
| Norway       | 150       | 0.89%   |
| Belgium      | 144       | 0.86%   |
| India        | 136       | 0.81%   |
| Czechia      | 135       | 0.8%    |
| Indonesia    | 133       | 0.79%   |
| Japan        | 121       | 0.72%   |
| Portugal     | 116       | 0.69%   |
| Hungary      | 114       | 0.68%   |
| Ukraine      | 109       | 0.65%   |
| Denmark      | 108       | 0.64%   |
| Taiwan       | 101       | 0.6%    |
| Mexico       | 95        | 0.57%   |
| South Korea  | 92        | 0.55%   |
| New Zealand  | 88        | 0.52%   |
| Bulgaria     | 87        | 0.52%   |
| Turkey       | 72        | 0.43%   |
| Argentina    | 71        | 0.42%   |
| South Africa | 64        | 0.38%   |
| Greece       | 58        | 0.35%   |
| Vietnam      | 53        | 0.32%   |
| Singapore    | 51        | 0.3%    |
| Slovakia     | 50        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 285       | 1.52%   |
| Berlin            | 232       | 1.24%   |
| Vienna            | 148       | 0.79%   |
| Sydney            | 133       | 0.71%   |
| Paris             | 133       | 0.71%   |
| St Petersburg     | 109       | 0.58%   |
| Munich            | 106       | 0.56%   |
| Hamburg           | 97        | 0.52%   |
| Seattle           | 91        | 0.48%   |
| London            | 88        | 0.47%   |
| Zurich            | 84        | 0.45%   |
| Melbourne         | 84        | 0.45%   |
| Montreal          | 80        | 0.43%   |
| Cologne           | 79        | 0.42%   |
| Amsterdam         | 76        | 0.4%    |
| Frankfurt am Main | 75        | 0.4%    |
| Warsaw            | 72        | 0.38%   |
| Madrid            | 68        | 0.36%   |
| Denver            | 68        | 0.36%   |
| Toronto           | 64        | 0.34%   |
| Brisbane          | 63        | 0.34%   |
| New York          | 62        | 0.33%   |
| Chicago           | 61        | 0.32%   |
| Brooklyn          | 60        | 0.32%   |
| Jakarta           | 56        | 0.3%    |
| Milan             | 55        | 0.29%   |
| Los Angeles       | 55        | 0.29%   |
| Helsinki          | 55        | 0.29%   |
| Bucharest         | 55        | 0.29%   |
| Perth             | 54        | 0.29%   |
| Oslo              | 52        | 0.28%   |
| Stockholm         | 51        | 0.27%   |
| Stuttgart         | 50        | 0.27%   |
| Singapore         | 50        | 0.27%   |
| Sofia             | 48        | 0.26%   |
| Sao Paulo         | 48        | 0.26%   |
| Portland          | 48        | 0.26%   |
| Prague            | 47        | 0.25%   |
| Dallas            | 45        | 0.24%   |
| Rome              | 43        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2780      | 4738   | 15.31%  |
| WDC                 | 2084      | 4494   | 11.48%  |
| Seagate             | 1630      | 3303   | 8.98%   |
| Kingston            | 1423      | 2083   | 7.84%   |
| Crucial             | 891       | 1397   | 4.91%   |
| Intel               | 765       | 1284   | 4.21%   |
| Transcend           | 757       | 1168   | 4.17%   |
| Toshiba             | 747       | 1313   | 4.11%   |
| SanDisk             | 746       | 1007   | 4.11%   |
| A-DATA Technology   | 414       | 572    | 2.28%   |
| Hitachi             | 398       | 723    | 2.19%   |
| China               | 384       | 552    | 2.11%   |
| Hoodisk             | 280       | 438    | 1.54%   |
| SK hynix            | 249       | 359    | 1.37%   |
| HGST                | 243       | 646    | 1.34%   |
| Phison              | 233       | 334    | 1.28%   |
| Micron Technology   | 228       | 343    | 1.26%   |
| SPCC                | 191       | 322    | 1.05%   |
| Hewlett-Packard     | 182       | 489    | 1%      |
| NVMe                | 171       | 232    | 0.94%   |
| FORESEE             | 162       | 237    | 0.89%   |
| PNY                 | 150       | 256    | 0.83%   |
| Protectli           | 140       | 231    | 0.77%   |
| Patriot             | 130       | 195    | 0.72%   |
| Apacer              | 130       | 177    | 0.72%   |
| OCZ                 | 123       | 177    | 0.68%   |
| Silicon Motion      | 110       | 150    | 0.61%   |
| Apple               | 105       | 123    | 0.58%   |
| Intenso             | 99        | 161    | 0.55%   |
| Innodisk            | 92        | 121    | 0.51%   |
| Corsair             | 85        | 152    | 0.47%   |
| Gigabyte Technology | 79        | 108    | 0.44%   |
| Team                | 78        | 133    | 0.43%   |
| Dogfish             | 76        | 136    | 0.42%   |
| KingSpec            | 75        | 96     | 0.41%   |
| LITEON              | 72        | 109    | 0.4%    |
| BIWIN               | 65        | 97     | 0.36%   |
| Lexar               | 64        | 90     | 0.35%   |
| LITEONIT            | 61        | 80     | 0.34%   |
| KIOXIA              | 59        | 69     | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 222       | 1.13%   |
| Kingston SA400S37120G 120GB        | 163       | 0.83%   |
| Samsung SSD 850 EVO 250GB          | 157       | 0.8%    |
| Samsung SSD 860 EVO 500GB          | 111       | 0.57%   |
| Crucial CT240BX500SSD1 240GB       | 107       | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 104       | 0.53%   |
| Seagate ST500DM002-1BD142 500GB    | 93        | 0.47%   |
| Kingston SV300S37A120G 120GB       | 93        | 0.47%   |
| Crucial CT500MX500SSD1 500GB       | 87        | 0.44%   |
| Kingston SA400S37480G 480GB        | 83        | 0.42%   |
| Samsung SSD 850 EVO 500GB          | 82        | 0.42%   |
| Hoodisk SSD 32GB                   | 82        | 0.42%   |
| Hoodisk SSD 128GB                  | 80        | 0.41%   |
| Crucial CT250MX500SSD1 250GB       | 80        | 0.41%   |
| Kingston SUV500MS120G 120GB        | 79        | 0.4%    |
| Transcend TS128GMSA230S 128GB      | 78        | 0.4%    |
| Phison SATA SSD 16GB               | 74        | 0.38%   |
| China SATA SSD 16GB                | 73        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 71        | 0.36%   |
| Kingston SKC600MS256G 256GB        | 71        | 0.36%   |
| Hoodisk SSD 64GB                   | 71        | 0.36%   |
| FORESEE 128GB SSD                  | 71        | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB     | 65        | 0.33%   |
| Crucial CT120BX500SSD1 120GB       | 62        | 0.32%   |
| Samsung SSD 870 EVO 250GB          | 61        | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB       | 60        | 0.31%   |
| A-DATA IM2S3134N-064GM 64GB        | 60        | 0.31%   |
| Samsung SSD 840 EVO 250GB          | 59        | 0.3%    |
| Crucial CT1000MX500SSD1 1TB        | 59        | 0.3%    |
| Samsung SSD 860 EVO 1TB            | 58        | 0.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 57        | 0.29%   |
| Seagate ST1000LM035-1RK172 1TB     | 56        | 0.29%   |
| Seagate ST1000DM010-2EP102 1TB     | 56        | 0.29%   |
| HP RAID 1(1+0) 240GB               | 56        | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB       | 52        | 0.26%   |
| Toshiba DT01ACA100 1TB             | 52        | 0.26%   |
| PNY CS900 120GB SSD                | 51        | 0.26%   |
| Toshiba MQ01ABD100 1TB             | 50        | 0.25%   |
| Samsung SSD 840 EVO 120GB          | 50        | 0.25%   |
| Samsung SSD 970 EVO Plus 250GB     | 47        | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Computers | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 1583      | 3210   | 31.44%  |
| WDC                                    | 1565      | 3568   | 31.08%  |
| Toshiba                                | 564       | 1029   | 11.2%   |
| Hitachi                                | 393       | 710    | 7.81%   |
| HGST                                   | 241       | 637    | 4.79%   |
| Samsung Electronics                    | 209       | 301    | 4.15%   |
| NVMe                                   | 109       | 148    | 2.16%   |
| Hewlett-Packard                        | 79        | 282    | 1.57%   |
| Fujitsu                                | 42        | 55     | 0.83%   |
| Maxtor                                 | 41        | 49     | 0.81%   |
| Apple                                  | 36        | 40     | 0.71%   |
| OPENBSD                                | 18        | 30     | 0.36%   |
| HPE                                    | 14        | 46     | 0.28%   |
| LSI                                    | 13        | 20     | 0.26%   |
| Dell                                   | 13        | 68     | 0.26%   |
| Generic                                | 9         | 9      | 0.18%   |
| JetFlash                               | 7         | 7      | 0.14%   |
| USB                                    | 6         | 6      | 0.12%   |
| China                                  | 6         | 8      | 0.12%   |
| Product:              USB DISK 2.0     | 5         | 5      | 0.1%    |
| Lexar                                  | 5         | 6      | 0.1%    |
| HPT                                    | 5         | 44     | 0.1%    |
| Adaptec                                | 5         | 15     | 0.1%    |
| WD MediaMax                            | 3         | 8      | 0.06%   |
| NETAPP                                 | 3         | 6      | 0.06%   |
| MARVELL                                | 3         | 3      | 0.06%   |
| LSILOGIC                               | 3         | 6      | 0.06%   |
| IBM/Hitachi                            | 3         | 3      | 0.06%   |
| ASMT                                   | 3         | 3      | 0.06%   |
| Synology                               | 2         | 2      | 0.04%   |
| StoreJet                               | 2         | 2      | 0.04%   |
| SMI                                    | 2         | 2      | 0.04%   |
| QUANTUM                                | 2         | 3      | 0.04%   |
| Product:              USB Flash Memory | 2         | 2      | 0.04%   |
| Multiple                               | 2         | 2      | 0.04%   |
| MaxDigital                             | 2         | 2      | 0.04%   |
| Lenovo                                 | 2         | 4      | 0.04%   |
| Intenso                                | 2         | 2      | 0.04%   |
| IBM-207x                               | 2         | 2      | 0.04%   |
| IBM                                    | 2         | 2      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1800      | 3091   | 17.27%  |
| Kingston            | 1227      | 1817   | 11.77%  |
| SanDisk             | 741       | 998    | 7.11%   |
| Crucial             | 732       | 1147   | 7.02%   |
| Transcend           | 657       | 1036   | 6.3%    |
| Intel               | 592       | 1044   | 5.68%   |
| China               | 378       | 544    | 3.63%   |
| A-DATA Technology   | 349       | 475    | 3.35%   |
| WDC                 | 339       | 529    | 3.25%   |
| Hoodisk             | 277       | 435    | 2.66%   |
| Micron Technology   | 175       | 269    | 1.68%   |
| SPCC                | 151       | 250    | 1.45%   |
| Protectli           | 140       | 231    | 1.34%   |
| FORESEE             | 140       | 211    | 1.34%   |
| PNY                 | 139       | 238    | 1.33%   |
| Apacer              | 128       | 173    | 1.23%   |
| SK hynix            | 126       | 181    | 1.21%   |
| Phison              | 125       | 166    | 1.2%    |
| OCZ                 | 123       | 177    | 1.18%   |
| Toshiba             | 107       | 160    | 1.03%   |
| Innodisk            | 92        | 121    | 0.88%   |
| Hewlett-Packard     | 91        | 160    | 0.87%   |
| Patriot             | 90        | 139    | 0.86%   |
| Intenso             | 89        | 146    | 0.85%   |
| Dogfish             | 76        | 136    | 0.73%   |
| KingSpec            | 75        | 96     | 0.72%   |
| Apple               | 69        | 82     | 0.66%   |
| LITEON              | 68        | 104    | 0.65%   |
| Corsair             | 64        | 94     | 0.61%   |
| LITEONIT            | 61        | 80     | 0.59%   |
| NVMe                | 59        | 70     | 0.57%   |
| BIWIN               | 51        | 82     | 0.49%   |
| Gigabyte Technology | 49        | 70     | 0.47%   |
| Team                | 46        | 91     | 0.44%   |
| Lexar               | 40        | 59     | 0.38%   |
| GOODRAM             | 38        | 56     | 0.36%   |
| ShiJi               | 35        | 51     | 0.34%   |
| Plextor             | 35        | 50     | 0.34%   |
| Seagate             | 33        | 66     | 0.32%   |
| Netac               | 32        | 42     | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 9484      | 16101  | 57.61%  |
| HDD  | 4198      | 10383  | 25.5%   |
| NVMe | 2781      | 4297   | 16.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12368     | 26484  | 81.64%  |
| NVMe | 2781      | 4297   | 18.36%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 10578     | 17895  | 74.74%  |
| 0.51-1.0        | 2095      | 3756   | 14.8%   |
| 1.01-2.0        | 711       | 1706   | 5.02%   |
| 3.01-4.0        | 310       | 1127   | 2.19%   |
| 4.01-10.0       | 231       | 1170   | 1.63%   |
| 2.01-3.0        | 156       | 509    | 1.1%    |
| 10.01-20.0      | 67        | 312    | 0.47%   |
| 20.01-50.0      | 3         | 6      | 0.02%   |
| More than 100.0 | 2         | 2      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 6970      | 39.89%  |
| 251-500        | 3061      | 17.52%  |
| 1-20           | 2251      | 12.88%  |
| 51-100         | 1720      | 9.84%   |
| 21-50          | 1422      | 8.14%   |
| 501-1000       | 1363      | 7.8%    |
| 1001-2000      | 370       | 2.12%   |
| More than 3000 | 162       | 0.93%   |
| Unknown        | 87        | 0.5%    |
| 2001-3000      | 65        | 0.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 15345     | 88.54%  |
| 21-50          | 1036      | 5.98%   |
| 51-100         | 360       | 2.08%   |
| 101-250        | 248       | 1.43%   |
| 251-500        | 100       | 0.58%   |
| Unknown        | 87        | 0.5%    |
| 501-1000       | 65        | 0.38%   |
| More than 3000 | 38        | 0.22%   |
| 1001-2000      | 34        | 0.2%    |
| 2001-3000      | 16        | 0.09%   |
| 0              | 2         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 35        | 57     | 1.47%   |
| Kingston SV300S37A120G 120GB          | 26        | 32     | 1.09%   |
| HGST HTS725050A7E630 500GB            | 22        | 43     | 0.93%   |
| Seagate ST500LT012-9WS142 500GB       | 18        | 24     | 0.76%   |
| Seagate ST500LM021-1KJ152 500GB       | 18        | 22     | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 18        | 24     | 0.76%   |
| Toshiba MQ01ABD100 1TB                | 16        | 17     | 0.67%   |
| Seagate ST9500325AS 500GB             | 15        | 21     | 0.63%   |
| Seagate ST3500418AS 500GB             | 14        | 24     | 0.59%   |
| Seagate ST500LT012-1DG142 500GB       | 13        | 15     | 0.55%   |
| Kingston SV300S37A60G 64GB            | 13        | 17     | 0.55%   |
| Kingston SMS200S3120G 120GB           | 13        | 19     | 0.55%   |
| Hitachi HTS541612J9SA00 120GB         | 13        | 15     | 0.55%   |
| Apacer 16GB SATA Flash Drive          | 13        | 20     | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB          | 12        | 19     | 0.5%    |
| Seagate ST9500420AS 500GB             | 12        | 16     | 0.5%    |
| Seagate ST9320325AS 320GB             | 11        | 11     | 0.46%   |
| Seagate ST3500413AS 500GB             | 11        | 26     | 0.46%   |
| Samsung Electronics SSD 870 EVO 1TB   | 11        | 16     | 0.46%   |
| Kingston SA400S37240G 240GB           | 11        | 11     | 0.46%   |
| Intel SSDSA2M080G2GC 80GB             | 11        | 14     | 0.46%   |
| Toshiba MQ01ABF050 500GB              | 10        | 12     | 0.42%   |
| Seagate ST320LT007-9ZV142 320GB       | 10        | 10     | 0.42%   |
| Kingston SMS200S360G 64GB             | 10        | 13     | 0.42%   |
| HGST HTS721010A9E630 1TB              | 10        | 32     | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB              | 9         | 26     | 0.38%   |
| Crucial CT275MX300SSD1 275GB          | 9         | 13     | 0.38%   |
| Toshiba DT01ACA100 1TB                | 8         | 12     | 0.34%   |
| SanDisk SSD PLUS 240GB                | 8         | 9      | 0.34%   |
| Samsung Electronics SSD 870 EVO 500GB | 8         | 14     | 0.34%   |
| Samsung Electronics HM160HI 160GB     | 8         | 9      | 0.34%   |
| Intel SSDSC2BF180A4L 180GB            | 8         | 9      | 0.34%   |
| HGST HTS541010A9E680 1TB              | 8         | 10     | 0.34%   |
| Crucial CT525MX300SSD1 528GB          | 8         | 12     | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB          | 7         | 8      | 0.29%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 7         | 8      | 0.29%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 7         | 7      | 0.29%   |
| WDC WD40EFRX-68WT0N0 4TB              | 7         | 17     | 0.29%   |
| Toshiba MQ01ABD050 500GB              | 7         | 9      | 0.29%   |
| Toshiba DT01ACA050 500GB              | 7         | 9      | 0.29%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 480       | 706    | 20.86%  |
| WDC                 | 401       | 612    | 17.43%  |
| Samsung Electronics | 181       | 270    | 7.87%   |
| Hitachi             | 171       | 231    | 7.43%   |
| Toshiba             | 166       | 235    | 7.21%   |
| Kingston            | 148       | 202    | 6.43%   |
| Intel               | 135       | 179    | 5.87%   |
| HGST                | 75        | 132    | 3.26%   |
| Crucial             | 75        | 125    | 3.26%   |
| SanDisk             | 64        | 86     | 2.78%   |
| SK hynix            | 36        | 53     | 1.56%   |
| A-DATA Technology   | 36        | 52     | 1.56%   |
| Micron Technology   | 34        | 47     | 1.48%   |
| China               | 24        | 29     | 1.04%   |
| OCZ                 | 23        | 31     | 1%      |
| Apacer              | 23        | 30     | 1%      |
| Maxtor              | 19        | 24     | 0.83%   |
| Corsair             | 17        | 23     | 0.74%   |
| Transcend           | 12        | 18     | 0.52%   |
| LITEON              | 11        | 18     | 0.48%   |
| Hewlett-Packard     | 11        | 20     | 0.48%   |
| Apple               | 11        | 11     | 0.48%   |
| SPCC                | 10        | 14     | 0.43%   |
| Patriot             | 9         | 14     | 0.39%   |
| Fujitsu             | 8         | 11     | 0.35%   |
| KingSpec            | 7         | 8      | 0.3%    |
| HP Phison           | 7         | 10     | 0.3%    |
| Dogfish             | 7         | 17     | 0.3%    |
| SSSTC               | 5         | 7      | 0.22%   |
| Plextor             | 5         | 5      | 0.22%   |
| Phison              | 5         | 6      | 0.22%   |
| Netac               | 4         | 5      | 0.17%   |
| Intenso             | 4         | 4      | 0.17%   |
| BIWIN               | 4         | 6      | 0.17%   |
| VisionTek           | 3         | 7      | 0.13%   |
| ShiJi               | 3         | 4      | 0.13%   |
| Mushkin             | 3         | 4      | 0.13%   |
| KingDian            | 3         | 6      | 0.13%   |
| HPE                 | 3         | 9      | 0.13%   |
| TEXTORM             | 2         | 2      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 478       | 704    | 34.41%  |
| WDC                  | 377       | 579    | 27.14%  |
| Hitachi              | 171       | 231    | 12.31%  |
| Toshiba              | 151       | 210    | 10.87%  |
| Samsung Electronics  | 84        | 114    | 6.05%   |
| HGST                 | 74        | 131    | 5.33%   |
| Maxtor               | 19        | 24     | 1.37%   |
| Hewlett-Packard      | 8         | 13     | 0.58%   |
| Fujitsu              | 8         | 11     | 0.58%   |
| Apple                | 6         | 6      | 0.43%   |
| China                | 4         | 6      | 0.29%   |
| HPE                  | 3         | 9      | 0.22%   |
| IBM/Hitachi          | 2         | 2      | 0.14%   |
| WD MediaMax          | 1         | 3      | 0.07%   |
| InnoLite             | 1         | 1      | 0.07%   |
| ExcelStor Technology | 1         | 2      | 0.07%   |
| Cactus               | 1         | 1      | 0.07%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1314      | 2047   | 59.14%  |
| SSD  | 871       | 1262   | 39.2%   |
| NVMe | 37        | 46     | 1.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                                | 5         | 5      | 6.25%   |
| Transcend TS128GMTE110S 128GB                    | 2         | 2      | 2.5%    |
| SK hynix SC308 SATA 256GB                        | 2         | 2      | 2.5%    |
| Seagate ST3160318AS 160GB                        | 2         | 2      | 2.5%    |
| Samsung Electronics MZYLN256HCHP-000L2 256GB     | 2         | 2      | 2.5%    |
| Crucial CT500P3SSD8 500GB                        | 2         | 2      | 2.5%    |
| WDC WD7501AALS-00J7B0 752GB                      | 1         | 1      | 1.25%   |
| WDC WD6400AARS-00Y5B1 640GB                      | 1         | 2      | 1.25%   |
| WDC WD3200L 320GB                                | 1         | 1      | 1.25%   |
| WDC WD3200BPVT-16JJ5T0 320GB                     | 1         | 1      | 1.25%   |
| WDC WD3200AAJS-00YZCA0 320GB                     | 1         | 1      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 1.25%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 1.25%   |
| WDC WD10SPZX-00Z10T0 1TB                         | 1         | 1      | 1.25%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB             | 1         | 1      | 1.25%   |
| Vaseky V900-120G                                 | 1         | 1      | 1.25%   |
| Transcend TS32GSSD370S 32GB                      | 1         | 4      | 1.25%   |
| Toshiba THNSNK128GCS8 SATA 128GB                 | 1         | 1      | 1.25%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.25%   |
| Toshiba MG05ACA800E 8TB                          | 1         | 1      | 1.25%   |
| Toshiba KXG50ZNV256G NVMe 256GB                  | 1         | 1      | 1.25%   |
| Supermicro SSD 16GB                              | 1         | 1      | 1.25%   |
| SK hynix SC308 SATA 128GB                        | 1         | 1      | 1.25%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 1.25%   |
| Seagate ST4000NM0025 4TB                         | 1         | 2      | 1.25%   |
| Seagate ST3500418AS 500GB                        | 1         | 2      | 1.25%   |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 1.25%   |
| SanDisk SD9SN8W-256G-1006 256GB                  | 1         | 1      | 1.25%   |
| SanDisk SD7TB6S256G1001 256GB                    | 1         | 2      | 1.25%   |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 980 250GB                | 1         | 2      | 1.25%   |
| Samsung Electronics SSD 970 EVO Plus 500GB       | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 960 EVO 500GB            | 1         | 1      | 1.25%   |
| Samsung Electronics SSD 960 EVO 250GB            | 1         | 1      | 1.25%   |
| Samsung Electronics PM981 NVMe 256GB             | 1         | 1      | 1.25%   |
| Samsung Electronics PM961 NVMe 256GB             | 1         | 1      | 1.25%   |
| Samsung Electronics MZVLW256HEHP-000L7 256GB     | 1         | 1      | 1.25%   |
| Samsung Electronics MZVLW256HEHP-000H1 256GB     | 1         | 2      | 1.25%   |
| Samsung Electronics MZVLW256HEHP-00000 256GB     | 1         | 1      | 1.25%   |
| Samsung Electronics MZVLB256HBHQ-000H1 256GB     | 1         | 1      | 1.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 23     | 23.75%  |
| WDC                 | 9         | 10     | 11.25%  |
| SanDisk             | 7         | 8      | 8.75%   |
| Seagate             | 5         | 7      | 6.25%   |
| Kingston            | 5         | 6      | 6.25%   |
| Intel               | 5         | 6      | 6.25%   |
| Crucial             | 5         | 5      | 6.25%   |
| Toshiba             | 4         | 4      | 5%      |
| SK hynix            | 4         | 4      | 5%      |
| Hitachi             | 4         | 17     | 5%      |
| Transcend           | 3         | 6      | 3.75%   |
| Vaseky              | 1         | 1      | 1.25%   |
| Supermicro          | 1         | 1      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Patriot             | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| Maxtor              | 1         | 1      | 1.25%   |
| KingDian            | 1         | 1      | 1.25%   |
| HPE                 | 1         | 1      | 1.25%   |
| Hoodisk             | 1         | 1      | 1.25%   |
| HGST                | 1         | 1      | 1.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 12726     | 26293  | 82%     |
| Malfunc  | 2175      | 3355   | 14.02%  |
| Detected | 538       | 1027   | 3.47%   |
| Failed   | 80        | 106    | 0.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 12615     | 60.58%  |
| AMD                                     | 2470      | 11.86%  |
| Samsung Electronics                     | 1208      | 5.8%    |
| SanDisk                                 | 547       | 2.63%   |
| Broadcom / LSI                          | 496       | 2.38%   |
| Silicon Motion                          | 393       | 1.89%   |
| Phison Electronics                      | 296       | 1.42%   |
| Kingston Technology Company             | 291       | 1.4%    |
| ASMedia Technology                      | 266       | 1.28%   |
| MAXIO Technology (Hangzhou)             | 211       | 1.01%   |
| Micron/Crucial Technology               | 202       | 0.97%   |
| SK hynix                                | 183       | 0.88%   |
| Marvell Technology Group                | 175       | 0.84%   |
| Nvidia                                  | 135       | 0.65%   |
| Micron Technology                       | 131       | 0.63%   |
| Hewlett-Packard                         | 114       | 0.55%   |
| Toshiba                                 | 111       | 0.53%   |
| Transcend                               | 109       | 0.52%   |
| JMicron Technology                      | 102       | 0.49%   |
| KIOXIA                                  | 101       | 0.49%   |
| Realtek Semiconductor                   | 77        | 0.37%   |
| ADATA Technology                        | 75        | 0.36%   |
| Shenzhen Longsys Electronics            | 67        | 0.32%   |
| Chelsio Communications                  | 52        | 0.25%   |
| Hosin Global Electronics                | 43        | 0.21%   |
| Adaptec                                 | 38        | 0.18%   |
| VIA Technologies                        | 33        | 0.16%   |
| Seagate Technology                      | 27        | 0.13%   |
| Silicon Image                           | 25        | 0.12%   |
| Solid State Storage Technology          | 22        | 0.11%   |
| Lite-On Technology                      | 15        | 0.07%   |
| Silicon Integrated Systems [SiS]        | 14        | 0.07%   |
| Shenzhen Unionmemory Information System | 14        | 0.07%   |
| Biwin Storage Technology                | 14        | 0.07%   |
| Netac Technology                        | 13        | 0.06%   |
| Unknown                                 | 13        | 0.06%   |
| Lenovo                                  | 12        | 0.06%   |
| INNOGRIT                                | 12        | 0.06%   |
| Union Memory (Shenzhen)                 | 11        | 0.05%   |
| Yangtze Memory Technologies             | 10        | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1616      | 6.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1042      | 4.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 740       | 3.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 722       | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 678       | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 548       | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 536       | 2.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 529       | 2.26%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 524       | 2.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 505       | 2.16%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 466       | 1.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 457       | 1.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 391       | 1.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 368       | 1.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 341       | 1.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 320       | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 311       | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 305       | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 303       | 1.3%    |
| Intel SATA Controller [RAID mode]                                                | 300       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 296       | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 265       | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 250       | 1.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 231       | 0.99%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 227       | 0.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 226       | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 204       | 0.87%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 203       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 190       | 0.81%   |
| AMD FCH SATA Controller [IDE mode]                                               | 189       | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 188       | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 180       | 0.77%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 170       | 0.73%   |
| AMD 500 Series Chipset SATA Controller                                           | 169       | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 167       | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 165       | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 165       | 0.71%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 148       | 0.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 148       | 0.63%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 144       | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 13524     | 64.55%  |
| NVMe | 4156      | 19.84%  |
| IDE  | 1872      | 8.94%   |
| RAID | 1017      | 4.85%   |
| SAS  | 243       | 1.16%   |
| SCSI | 139       | 0.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 13629     | 81.44%  |
| AMD                | 2876      | 17.19%  |
| ARM                | 151       | 0.9%    |
| Unknown            | 40        | 0.24%   |
| VIA                | 7         | 0.04%   |
| PowerPC            | 5         | 0.03%   |
| Broadcom           | 4         | 0.02%   |
| Rockchip           | 3         | 0.02%   |
| IBM                | 3         | 0.02%   |
| 11th               | 3         | 0.02%   |
| i                  | 2         | 0.01%   |
| 7447A              | 2         | 0.01%   |
| SUNW,UltraAX-i2    | 1         | 0.01%   |
| Sun                | 1         | 0.01%   |
| Research           | 1         | 0.01%   |
| Red Hat            | 1         | 0.01%   |
| QEMU               | 1         | 0.01%   |
| NXP                | 1         | 0.01%   |
| Motorola           | 1         | 0.01%   |
| Baikal Electronics | 1         | 0.01%   |
| Ampere             | 1         | 0.01%   |
| 123456789ABC       | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel N100                               | 541       | 3.2%    |
| Intel Celeron J4125 CPU @ 2.00GHz        | 426       | 2.52%   |
| Intel Celeron N5105 @ 2.00GHz            | 383       | 2.26%   |
| AMD GX-412TC SOC                         | 376       | 2.22%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 270       | 1.6%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 222       | 1.31%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 160       | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 126       | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 112       | 0.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 99        | 0.59%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 93        | 0.55%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 92        | 0.54%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 91        | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 88        | 0.52%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 86        | 0.51%   |
| Intel Celeron J6412 @ 2.00GHz            | 84        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 82        | 0.48%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 82        | 0.48%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 82        | 0.48%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 80        | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 79        | 0.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 79        | 0.47%   |
| Intel Core i3-N305                       | 79        | 0.47%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 79        | 0.47%   |
| Intel Atom CPU D525 @ 1.80GHz            | 76        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 75        | 0.44%   |
| Intel Core 2 Duo                         | 70        | 0.41%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 68        | 0.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 67        | 0.4%    |
| Intel Core i3-6100 CPU @ 3.70GHz         | 67        | 0.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 66        | 0.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 66        | 0.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 66        | 0.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 63        | 0.37%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 63        | 0.37%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 62        | 0.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 62        | 0.37%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 62        | 0.37%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 61        | 0.36%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 61        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3040      | 18.04%  |
| Intel Celeron           | 2647      | 15.71%  |
| Intel Core i7           | 1578      | 9.37%   |
| Intel Xeon              | 1569      | 9.31%   |
| Other                   | 1423      | 8.45%   |
| Intel Core i3           | 1277      | 7.58%   |
| Intel Atom              | 808       | 4.8%    |
| AMD GX                  | 680       | 4.04%   |
| Intel Pentium           | 456       | 2.71%   |
| AMD Ryzen 5             | 410       | 2.43%   |
| AMD Ryzen 7             | 375       | 2.23%   |
| Intel Core 2 Duo        | 366       | 2.17%   |
| Intel Pentium Silver    | 181       | 1.07%   |
| ARM Cortex              | 140       | 0.83%   |
| AMD FX                  | 126       | 0.75%   |
| AMD EPYC                | 121       | 0.72%   |
| AMD Ryzen 9             | 119       | 0.71%   |
| AMD Ryzen 3             | 104       | 0.62%   |
| Intel Core 2 Quad       | 94        | 0.56%   |
| AMD G                   | 89        | 0.53%   |
| AMD Ryzen Embedded      | 81        | 0.48%   |
| Intel Pentium Dual-Core | 80        | 0.47%   |
| Intel Pentium Gold      | 60        | 0.36%   |
| AMD Athlon              | 58        | 0.34%   |
| AMD Ryzen 5 PRO         | 48        | 0.28%   |
| Intel Core 2            | 45        | 0.27%   |
| Intel Core i9           | 44        | 0.26%   |
| AMD A10                 | 44        | 0.26%   |
| Intel Xeon Silver       | 39        | 0.23%   |
| Intel Genuine           | 39        | 0.23%   |
| AMD A6                  | 37        | 0.22%   |
| AMD Ryzen 7 PRO         | 36        | 0.21%   |
| AMD Phenom II X4        | 36        | 0.21%   |
| AMD A4                  | 36        | 0.21%   |
| AMD A8                  | 35        | 0.21%   |
| Intel Pentium 4         | 32        | 0.19%   |
| AMD Athlon 64 X2        | 32        | 0.19%   |
| AMD E                   | 31        | 0.18%   |
| Intel Xeon Gold         | 29        | 0.17%   |
| Intel Pentium Dual      | 26        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 8191      | 48.5%   |
| 2       | 4509      | 26.7%   |
| 8       | 1059      | 6.27%   |
| 6       | 875       | 5.18%   |
| Unknown | 716       | 4.24%   |
| 12      | 486       | 2.88%   |
| 16      | 485       | 2.87%   |
| 1       | 192       | 1.14%   |
| 10      | 86        | 0.51%   |
| 24      | 83        | 0.49%   |
| 32      | 65        | 0.38%   |
| 20      | 47        | 0.28%   |
| 3       | 20        | 0.12%   |
| 14      | 18        | 0.11%   |
| 64      | 12        | 0.07%   |
| 28      | 12        | 0.07%   |
| 48      | 8         | 0.05%   |
| 36      | 7         | 0.04%   |
| 22      | 4         | 0.02%   |
| 128     | 3         | 0.02%   |
| 40      | 3         | 0.02%   |
| 18      | 3         | 0.02%   |
| 5       | 2         | 0.01%   |
| 11      | 1         | 0.01%   |
| 9       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 15883     | 94.94%  |
| 2       | 502       | 3%      |
| Unknown | 338       | 2.02%   |
| 4       | 5         | 0.03%   |
| 8       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 9725      | 57.77%  |
| 2       | 6312      | 37.5%   |
| Unknown | 794       | 4.72%   |
| 6       | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 2205      | 13.1%   |
| KabyLake        | 2037      | 12.1%   |
| Haswell         | 1585      | 9.41%   |
| Silvermont      | 1233      | 7.32%   |
| Skylake         | 1086      | 6.45%   |
| IvyBridge       | 1076      | 6.39%   |
| SandyBridge     | 889       | 5.28%   |
| Goldmont plus   | 735       | 4.37%   |
| Goldmont        | 531       | 3.15%   |
| Penryn          | 525       | 3.12%   |
| Broadwell       | 512       | 3.04%   |
| Puma            | 498       | 2.96%   |
| Westmere        | 358       | 2.13%   |
| Zen             | 342       | 2.03%   |
| Zen 2           | 309       | 1.84%   |
| Zen 3           | 308       | 1.83%   |
| Core            | 279       | 1.66%   |
| Bonnell         | 268       | 1.59%   |
| Jaguar          | 266       | 1.58%   |
| CometLake       | 263       | 1.56%   |
| Zen+            | 258       | 1.53%   |
| Nehalem         | 193       | 1.15%   |
| TigerLake       | 183       | 1.09%   |
| Piledriver      | 164       | 0.97%   |
| K10             | 146       | 0.87%   |
| Bobcat          | 144       | 0.86%   |
| Steamroller     | 106       | 0.63%   |
| Excavator       | 76        | 0.45%   |
| NetBurst        | 58        | 0.34%   |
| K8 Hammer       | 57        | 0.34%   |
| P6              | 48        | 0.29%   |
| IceLake         | 42        | 0.25%   |
| Bulldozer       | 30        | 0.18%   |
| K10 Llano       | 17        | 0.1%    |
| Geode           | 6         | 0.04%   |
| K8 & K10 hybrid | 3         | 0.02%   |
| K6              | 2         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 10681     | 64.42%  |
| AMD                                          | 2401      | 14.48%  |
| Nvidia                                       | 1800      | 10.86%  |
| ASPEED Technology                            | 861       | 5.19%   |
| Matrox Electronics Systems                   | 783       | 4.72%   |
| XGI Technology (eXtreme Graphics Innovation) | 13        | 0.08%   |
| VIA Technologies                             | 10        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 10        | 0.06%   |
| S3 Graphics                                  | 5         | 0.03%   |
| Silicon Motion                               | 4         | 0.02%   |
| RDC Semiconductor                            | 3         | 0.02%   |
| Red Hat                                      | 2         | 0.01%   |
| Tseng Labs                                   | 1         | 0.01%   |
| Trident Microsystems                         | 1         | 0.01%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Cirrus Logic                                 | 1         | 0.01%   |
| ATI                                          | 1         | 0.01%   |
| 3DLabs                                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 861       | 5.09%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 681       | 4.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 630       | 3.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 619       | 3.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 595       | 3.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 558       | 3.3%    |
| Intel JasperLake [UHD Graphics]                                                          | 546       | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 514       | 3.04%   |
| Intel HD Graphics 530                                                                    | 494       | 2.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 426       | 2.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 352       | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 329       | 1.95%   |
| Intel HD Graphics 620                                                                    | 312       | 1.85%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 308       | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 286       | 1.69%   |
| Intel HD Graphics 500                                                                    | 279       | 1.65%   |
| Intel HD Graphics 630                                                                    | 261       | 1.54%   |
| Intel UHD Graphics 620                                                                   | 247       | 1.46%   |
| Intel HD Graphics 5500                                                                   | 232       | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 208       | 1.23%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 173       | 1.02%   |
| Matrox Electronics Systems G200eR2                                                       | 167       | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 167       | 0.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 157       | 0.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 154       | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 145       | 0.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 143       | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 138       | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 133       | 0.79%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 129       | 0.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 128       | 0.76%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 125       | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 122       | 0.72%   |
| Matrox Electronics Systems MGA G200EH                                                    | 116       | 0.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 115       | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 112       | 0.66%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 107       | 0.63%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 105       | 0.62%   |
| AMD ES1000                                                                               | 104       | 0.62%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 102       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 9510      | 56.5%   |
| 1 x AMD                                  | 2115      | 12.57%  |
| 1 x Nvidia                               | 1196      | 7.11%   |
| Other                                    | 1032      | 6.13%   |
| 1 x ASPEED                               | 803       | 4.77%   |
| 1 x Matrox                               | 773       | 4.59%   |
| Intel + Nvidia                           | 507       | 3.01%   |
| 2 x Intel                                | 477       | 2.83%   |
| Intel + AMD                              | 150       | 0.89%   |
| AMD + Nvidia                             | 66        | 0.39%   |
| 2 x AMD                                  | 65        | 0.39%   |
| Intel + ASPEED                           | 36        | 0.21%   |
| Nvidia + ASPEED                          | 15        | 0.09%   |
| 1 x XGI                                  | 13        | 0.08%   |
| 2 x Nvidia                               | 11        | 0.07%   |
| 1 x VIA                                  | 10        | 0.06%   |
| 1 x SiS                                  | 10        | 0.06%   |
| AMD + ASPEED                             | 8         | 0.05%   |
| 1 x S3 Graphics                          | 5         | 0.03%   |
| Nvidia + Matrox                          | 5         | 0.03%   |
| 1 x Silicon Motion                       | 4         | 0.02%   |
| 1 x RDC Semiconductor                    | 3         | 0.02%   |
| 2 x Intel + 1 x Nvidia                   | 2         | 0.01%   |
| 1 x Red Hat                              | 2         | 0.01%   |
| Intel + Matrox                           | 2         | 0.01%   |
| Intel + AMD + 1 x Nvidia                 | 2         | 0.01%   |
| AMD + Matrox                             | 2         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED                  | 1         | 0.01%   |
| 1 x Tseng Labs                           | 1         | 0.01%   |
| 1 x Trident Microsystems                 | 1         | 0.01%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.01%   |
| Nvidia + Huawei Technologies             | 1         | 0.01%   |
| Intel + 2 x AMD                          | 1         | 0.01%   |
| 1 x Cirrus Logic                         | 1         | 0.01%   |
| 1 x 3DLabs                               | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 14717     | 87.58%  |
| Unknown     | 1235      | 7.35%   |
| Proprietary | 853       | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 15288     | 90.7%   |
| 1.01-2.0   | 374       | 2.22%   |
| 0.01-0.5   | 362       | 2.15%   |
| 0.51-1.0   | 244       | 1.45%   |
| 3.01-4.0   | 230       | 1.36%   |
| 7.01-8.0   | 182       | 1.08%   |
| 5.01-6.0   | 91        | 0.54%   |
| 8.01-16.0  | 44        | 0.26%   |
| 2.01-3.0   | 33        | 0.2%    |
| 16.01-24.0 | 5         | 0.03%   |
| 4.01-5.0   | 3         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 498       | 11.17%  |
| Samsung Electronics     | 486       | 10.9%   |
| LG Display              | 431       | 9.67%   |
| BOE                     | 343       | 7.69%   |
| Chimei Innolux          | 319       | 7.16%   |
| Dell                    | 301       | 6.75%   |
| Goldstar                | 224       | 5.02%   |
| Lenovo                  | 170       | 3.81%   |
| Acer                    | 140       | 3.14%   |
| Hewlett-Packard         | 135       | 3.03%   |
| Apple                   | 122       | 2.74%   |
| Philips                 | 117       | 2.62%   |
| BenQ                    | 113       | 2.53%   |
| AOC                     | 96        | 2.15%   |
| Ancor Communications    | 88        | 1.97%   |
| ViewSonic               | 68        | 1.53%   |
| Sharp                   | 68        | 1.53%   |
| Iiyama                  | 56        | 1.26%   |
| Chi Mei Optoelectronics | 51        | 1.14%   |
| InfoVision              | 38        | 0.85%   |
| ASUSTek Computer        | 38        | 0.85%   |
| LG Electronics          | 31        | 0.7%    |
| Sony                    | 27        | 0.61%   |
| NEC Computers           | 25        | 0.56%   |
| Eizo                    | 24        | 0.54%   |
| PANDA                   | 22        | 0.49%   |
| Fujitsu Siemens         | 21        | 0.47%   |
| LG Philips              | 20        | 0.45%   |
| CSO                     | 20        | 0.45%   |
| MSI                     | 19        | 0.43%   |
| HannStar                | 18        | 0.4%    |
| Unknown                 | 15        | 0.34%   |
| Toshiba                 | 14        | 0.31%   |
| Idek Iiyama             | 12        | 0.27%   |
| Vizio                   | 11        | 0.25%   |
| Panasonic               | 11        | 0.25%   |
| Unknown                 | 10        | 0.22%   |
| Sceptre Tech            | 10        | 0.22%   |
| LGD                     | 9         | 0.2%    |
| HKC                     | 9         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 31        | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 24        | 0.52%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 18        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 16        | 0.35%   |
| Unknown                                                              | 15        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 13        | 0.28%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 13        | 0.28%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 12        | 0.26%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 12        | 0.26%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 11        | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch              | 11        | 0.24%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch              | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 11        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch | 10        | 0.22%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 10        | 0.22%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 10        | 0.22%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 10        | 0.22%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 10        | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 10        | 0.22%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 9         | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 9         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 9         | 0.2%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 9         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch      | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 9         | 0.2%    |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch          | 8         | 0.17%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 8         | 0.17%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 8         | 0.17%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 8         | 0.17%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 8         | 0.17%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 8         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1781      | 40.9%   |
| 1366x768 (WXGA)    | 860       | 19.75%  |
| 2560x1440 (QHD)    | 238       | 5.46%   |
| 3840x2160 (4K)     | 236       | 5.42%   |
| 1600x900 (HD+)     | 181       | 4.16%   |
| 1280x1024 (SXGA)   | 147       | 3.38%   |
| 1280x800 (WXGA)    | 133       | 3.05%   |
| 1920x1200 (WUXGA)  | 130       | 2.99%   |
| 1440x900 (WXGA+)   | 108       | 2.48%   |
| 1680x1050 (WSXGA+) | 101       | 2.32%   |
| 2560x1080          | 47        | 1.08%   |
| 2560x1600          | 45        | 1.03%   |
| 3440x1440          | 40        | 0.92%   |
| Unknown            | 39        | 0.9%    |
| 1024x600           | 38        | 0.87%   |
| 1024x768 (XGA)     | 22        | 0.51%   |
| 1360x768           | 19        | 0.44%   |
| 2256x1504          | 17        | 0.39%   |
| 1600x1200          | 17        | 0.39%   |
| 2880x1800          | 16        | 0.37%   |
| 3200x1800 (QHD+)   | 15        | 0.34%   |
| 3840x1080          | 14        | 0.32%   |
| 1920x540           | 13        | 0.3%    |
| 2160x1440          | 7         | 0.16%   |
| 1920x1280          | 6         | 0.14%   |
| 3840x2400          | 5         | 0.11%   |
| 5760x2160          | 4         | 0.09%   |
| 3840x1600          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2048x1152          | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 3840x1200          | 3         | 0.07%   |
| 3000x2000          | 3         | 0.07%   |
| 1280x720 (HD)      | 3         | 0.07%   |
| 5760x1080          | 2         | 0.05%   |
| 5120x1440          | 2         | 0.05%   |
| 3520x1080          | 2         | 0.05%   |
| 3120x2080          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2240x1400          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 866       | 19.5%   |
| 13      | 824       | 18.55%  |
| 24      | 360       | 8.1%    |
| 27      | 348       | 7.83%   |
| 21      | 260       | 5.85%   |
| Unknown | 249       | 5.61%   |
| 12      | 235       | 5.29%   |
| 23      | 234       | 5.27%   |
| 19      | 176       | 3.96%   |
| 17      | 158       | 3.56%   |
| 14      | 111       | 2.5%    |
| 31      | 93        | 2.09%   |
| 11      | 93        | 2.09%   |
| 18      | 70        | 1.58%   |
| 34      | 56        | 1.26%   |
| 22      | 55        | 1.24%   |
| 20      | 37        | 0.83%   |
| 10      | 37        | 0.83%   |
| 40      | 16        | 0.36%   |
| 29      | 16        | 0.36%   |
| 16      | 15        | 0.34%   |
| 28      | 12        | 0.27%   |
| 42      | 10        | 0.23%   |
| 32      | 10        | 0.23%   |
| 9       | 10        | 0.23%   |
| 54      | 8         | 0.18%   |
| 52      | 8         | 0.18%   |
| 25      | 8         | 0.18%   |
| 26      | 7         | 0.16%   |
| 64      | 6         | 0.14%   |
| 50      | 5         | 0.11%   |
| 46      | 5         | 0.11%   |
| 39      | 5         | 0.11%   |
| 33      | 5         | 0.11%   |
| 49      | 4         | 0.09%   |
| 43      | 4         | 0.09%   |
| 48      | 3         | 0.07%   |
| 41      | 3         | 0.07%   |
| 37      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1521      | 34.65%  |
| 501-600     | 885       | 20.16%  |
| 201-300     | 714       | 16.26%  |
| 401-500     | 518       | 11.8%   |
| Unknown     | 249       | 5.67%   |
| 351-400     | 181       | 4.12%   |
| 601-700     | 151       | 3.44%   |
| 701-800     | 73        | 1.66%   |
| 1001-1500   | 45        | 1.03%   |
| 801-900     | 26        | 0.59%   |
| 901-1000    | 18        | 0.41%   |
| 101-200     | 6         | 0.14%   |
| 1501-2000   | 2         | 0.05%   |
| 1-100       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3081      | 73.81%  |
| 16/10   | 507       | 12.15%  |
| Unknown | 212       | 5.08%   |
| 5/4     | 127       | 3.04%   |
| 3/2     | 93        | 2.23%   |
| 21/9    | 80        | 1.92%   |
| 4/3     | 55        | 1.32%   |
| 6/5     | 7         | 0.17%   |
| 32/9    | 6         | 0.14%   |
| 3.88    | 1         | 0.02%   |
| 3.18    | 1         | 0.02%   |
| 11/10   | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.46    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 769       | 17.44%  |
| 201-250        | 764       | 17.32%  |
| 91-100         | 647       | 14.67%  |
| 301-350        | 360       | 8.16%   |
| Unknown        | 249       | 5.65%   |
| 151-200        | 237       | 5.37%   |
| 61-70          | 229       | 5.19%   |
| 101-110        | 217       | 4.92%   |
| 351-500        | 180       | 4.08%   |
| 71-80          | 140       | 3.17%   |
| 141-150        | 120       | 2.72%   |
| 251-300        | 119       | 2.7%    |
| 51-60          | 93        | 2.11%   |
| 121-130        | 93        | 2.11%   |
| 501-1000       | 54        | 1.22%   |
| 111-120        | 43        | 0.98%   |
| 41-50          | 41        | 0.93%   |
| More than 1000 | 36        | 0.82%   |
| 131-140        | 12        | 0.27%   |
| 1-40           | 7         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1348      | 30.89%  |
| 121-160       | 1201      | 27.52%  |
| 101-120       | 1099      | 25.18%  |
| 161-240       | 343       | 7.86%   |
| Unknown       | 249       | 5.71%   |
| More than 240 | 88        | 2.02%   |
| 1-50          | 36        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12305     | 72.84%  |
| 1     | 4135      | 24.48%  |
| 2     | 419       | 2.48%   |
| 3     | 32        | 0.19%   |
| 4     | 2         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 12421     | 53.32%  |
| Realtek Semiconductor             | 5806      | 24.92%  |
| Broadcom                          | 1509      | 6.48%   |
| Qualcomm Atheros                  | 1271      | 5.46%   |
| Mellanox Technologies             | 191       | 0.82%   |
| AMD                               | 143       | 0.61%   |
| Ralink Technology                 | 134       | 0.58%   |
| Marvell Technology Group          | 129       | 0.55%   |
| MediaTek                          | 124       | 0.53%   |
| TP-Link                           | 122       | 0.52%   |
| IMC Networks                      | 99        | 0.42%   |
| Ralink                            | 77        | 0.33%   |
| D-Link System                     | 72        | 0.31%   |
| Chelsio Communications            | 69        | 0.3%    |
| Samsung Electronics               | 66        | 0.28%   |
| Nvidia                            | 60        | 0.26%   |
| Edimax Technology                 | 55        | 0.24%   |
| U-Blox                            | 52        | 0.22%   |
| Sierra Wireless                   | 43        | 0.18%   |
| Ericsson Business Mobile Networks | 41        | 0.18%   |
| Aquantia                          | 41        | 0.18%   |
| Huawei Technologies               | 37        | 0.16%   |
| Dell                              | 36        | 0.15%   |
| American Megatrends               | 36        | 0.15%   |
| Xiaomi                            | 30        | 0.13%   |
| Emulex                            | 30        | 0.13%   |
| Google                            | 28        | 0.12%   |
| Qualcomm Atheros Communications   | 27        | 0.12%   |
| VIA Technologies                  | 26        | 0.11%   |
| Solarflare Communications         | 26        | 0.11%   |
| ASUSTek Computer                  | 25        | 0.11%   |
| Apple                             | 23        | 0.1%    |
| 3Com                              | 21        | 0.09%   |
| D-Link                            | 20        | 0.09%   |
| QLogic                            | 19        | 0.08%   |
| Insyde Software                   | 19        | 0.08%   |
| IBM                               | 19        | 0.08%   |
| Hewlett-Packard                   | 19        | 0.08%   |
| Qualcomm                          | 17        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 15        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 4559      | 15.47%  |
| Intel I211 Gigabit Network Connection                                         | 1752      | 5.94%   |
| Intel I210 Gigabit Network Connection                                         | 1236      | 4.19%   |
| Intel Ethernet Controller I226-V                                              | 1195      | 4.05%   |
| Intel I350 Gigabit Network Connection                                         | 906       | 3.07%   |
| Intel Ethernet Controller I225-V                                              | 892       | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 710       | 2.41%   |
| Intel 82574L Gigabit Network Connection                                       | 641       | 2.17%   |
| Intel Ethernet Connection I217-LM                                             | 420       | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 411       | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                             | 397       | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 345       | 1.17%   |
| Intel 82576 Gigabit Network Connection                                        | 325       | 1.1%    |
| Intel Wi-Fi 6 AX200                                                           | 323       | 1.1%    |
| Intel Wireless 8265 / 8275                                                    | 318       | 1.08%   |
| Intel 82583V Gigabit Network Connection                                       | 299       | 1.01%   |
| Intel 82580 Gigabit Network Connection                                        | 281       | 0.95%   |
| Intel Wireless 7265                                                           | 270       | 0.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 270       | 0.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 266       | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                                         | 265       | 0.9%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 240       | 0.81%   |
| Intel Wireless 7260                                                           | 215       | 0.73%   |
| Intel Wireless 8260                                                           | 212       | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 204       | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 192       | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 187       | 0.63%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 185       | 0.63%   |
| Intel Wireless 3165                                                           | 182       | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                          | 175       | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 172       | 0.58%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 158       | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 149       | 0.51%   |
| Intel Ethernet Connection I354                                                | 146       | 0.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 143       | 0.49%   |
| AMD XGMAC 10GbE Controller                                                    | 141       | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 138       | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 138       | 0.47%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 137       | 0.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 136       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3421      | 51.54%  |
| Qualcomm Atheros                      | 1060      | 15.97%  |
| Realtek Semiconductor                 | 892       | 13.44%  |
| Broadcom                              | 471       | 7.1%    |
| Ralink Technology                     | 134       | 2.02%   |
| TP-Link                               | 120       | 1.81%   |
| MediaTek                              | 114       | 1.72%   |
| IMC Networks                          | 99        | 1.49%   |
| Ralink                                | 77        | 1.16%   |
| Edimax Technology                     | 55        | 0.83%   |
| Sierra Wireless                       | 32        | 0.48%   |
| Qualcomm Atheros Communications       | 27        | 0.41%   |
| ASUSTek Computer                      | 25        | 0.38%   |
| D-Link                                | 20        | 0.3%    |
| D-Link System                         | 15        | 0.23%   |
| Dell                                  | 14        | 0.21%   |
| NetGear                               | 13        | 0.2%    |
| Qualcomm Technologies                 | 9         | 0.14%   |
| Marvell Technology Group              | 5         | 0.08%   |
| Mercucys                              | 4         | 0.06%   |
| Belkin Components                     | 4         | 0.06%   |
| Atheros                               | 4         | 0.06%   |
| ZyXEL Communications                  | 3         | 0.05%   |
| Micro Star International              | 3         | 0.05%   |
| BUFFALO                               | 3         | 0.05%   |
| AboCom Systems                        | 3         | 0.05%   |
| Linksys                               | 2         | 0.03%   |
| Accton Technology                     | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| Gemtek                                | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 323       | 4.8%    |
| Intel Wireless 8265 / 8275                                      | 318       | 4.73%   |
| Intel Wireless 7265                                             | 270       | 4.02%   |
| Intel Wireless 7260                                             | 215       | 3.2%    |
| Intel Wireless 8260                                             | 212       | 3.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 204       | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 187       | 2.78%   |
| Intel Wireless 3165                                             | 182       | 2.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 149       | 2.22%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 143       | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 138       | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 138       | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 136       | 2.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 127       | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 111       | 1.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 109       | 1.62%   |
| Intel Wi-Fi 6 AX201                                             | 109       | 1.62%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 95        | 1.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 94        | 1.4%    |
| Intel Wireless 3160                                             | 92        | 1.37%   |
| Intel CNVi: Wi-Fi                                               | 88        | 1.31%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 87        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 85        | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 85        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 84        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 79        | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 75        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 67        | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 66        | 0.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 63        | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 60        | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 55        | 0.82%   |
| Intel Centrino Advanced-N 6235                                  | 54        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 51        | 0.76%   |
| Ralink RT5370 Wireless Adapter                                  | 51        | 0.76%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 50        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 49        | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 48        | 0.71%   |
| Intel Wi-Fi 6 AX201 160MHz                                      | 48        | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 48        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 10773     | 57.8%   |
| Realtek Semiconductor             | 5416      | 29.06%  |
| Broadcom                          | 1167      | 6.26%   |
| Qualcomm Atheros                  | 301       | 1.62%   |
| AMD                               | 142       | 0.76%   |
| Marvell Technology Group          | 122       | 0.65%   |
| Samsung Electronics               | 66        | 0.35%   |
| Nvidia                            | 60        | 0.32%   |
| D-Link System                     | 54        | 0.29%   |
| Chelsio Communications            | 52        | 0.28%   |
| Aquantia                          | 40        | 0.21%   |
| American Megatrends               | 36        | 0.19%   |
| Xiaomi                            | 30        | 0.16%   |
| Emulex                            | 28        | 0.15%   |
| VIA Technologies                  | 26        | 0.14%   |
| Solarflare Communications         | 26        | 0.14%   |
| Apple                             | 20        | 0.11%   |
| QLogic                            | 19        | 0.1%    |
| Insyde Software                   | 19        | 0.1%    |
| IBM                               | 19        | 0.1%    |
| 3Com                              | 19        | 0.1%    |
| Qualcomm                          | 17        | 0.09%   |
| JMicron Technology                | 15        | 0.08%   |
| Google                            | 14        | 0.08%   |
| ZTE WCDMA Technologies MSM        | 13        | 0.07%   |
| Huawei Technologies               | 12        | 0.06%   |
| MediaTek                          | 10        | 0.05%   |
| ICS Advent                        | 9         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.04%   |
| OPPO Electronics                  | 8         | 0.04%   |
| Novatel Wireless                  | 8         | 0.04%   |
| Motorola PCS                      | 7         | 0.04%   |
| Lenovo                            | 7         | 0.04%   |
| National Semiconductor            | 6         | 0.03%   |
| Davicom Semiconductor             | 6         | 0.03%   |
| Microsoft                         | 5         | 0.03%   |
| T & A Mobile Phones               | 4         | 0.02%   |
| MYRICOM                           | 4         | 0.02%   |
| Sundance Technology Inc / IC Plus | 3         | 0.02%   |
| Silicom                           | 3         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 4559      | 20.6%   |
| Intel I211 Gigabit Network Connection                                         | 1752      | 7.92%   |
| Intel I210 Gigabit Network Connection                                         | 1236      | 5.59%   |
| Intel Ethernet Controller I226-V                                              | 1195      | 5.4%    |
| Intel I350 Gigabit Network Connection                                         | 906       | 4.09%   |
| Intel Ethernet Controller I225-V                                              | 892       | 4.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 710       | 3.21%   |
| Intel 82574L Gigabit Network Connection                                       | 641       | 2.9%    |
| Intel Ethernet Connection I217-LM                                             | 420       | 1.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 411       | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 390       | 1.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 345       | 1.56%   |
| Intel 82576 Gigabit Network Connection                                        | 325       | 1.47%   |
| Intel 82583V Gigabit Network Connection                                       | 299       | 1.35%   |
| Intel 82580 Gigabit Network Connection                                        | 281       | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 270       | 1.22%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 266       | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                         | 265       | 1.2%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 240       | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 192       | 0.87%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 185       | 0.84%   |
| Intel Ethernet Connection (7) I219-V                                          | 175       | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                         | 172       | 0.78%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 158       | 0.71%   |
| Intel Ethernet Connection I354                                                | 146       | 0.66%   |
| AMD XGMAC 10GbE Controller                                                    | 141       | 0.64%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 137       | 0.62%   |
| Intel Ethernet Connection X553 1GbE                                           | 135       | 0.61%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 134       | 0.61%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 133       | 0.6%    |
| Intel Ethernet Controller X550                                                | 131       | 0.59%   |
| Intel Ethernet Connection I219-LM                                             | 120       | 0.54%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 114       | 0.52%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 106       | 0.48%   |
| Intel 82579V Gigabit Network Connection                                       | 99        | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                                         | 98        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 97        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                                         | 94        | 0.42%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 92        | 0.42%   |
| Intel Ethernet Connection I217-V                                              | 88        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 15891     | 70.09%  |
| WiFi     | 6169      | 27.21%  |
| Unknown  | 430       | 1.9%    |
| Modem    | 182       | 0.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 14521     | 85%     |
| WiFi     | 2524      | 14.77%  |
| Unknown  | 26        | 0.15%   |
| Modem    | 13        | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 5249      | 30.92%  |
| 4     | 3070      | 18.08%  |
| 1     | 2588      | 15.24%  |
| 3     | 2200      | 12.96%  |
| 6     | 1476      | 8.69%   |
| 5     | 1086      | 6.4%    |
| 8     | 386       | 2.27%   |
| 0     | 241       | 1.42%   |
| 7     | 226       | 1.33%   |
| 9     | 192       | 1.13%   |
| 10    | 128       | 0.75%   |
| 12    | 52        | 0.31%   |
| 14    | 25        | 0.15%   |
| 13    | 15        | 0.09%   |
| 11    | 14        | 0.08%   |
| 16    | 13        | 0.08%   |
| 15    | 8         | 0.05%   |
| 20    | 4         | 0.02%   |
| 17    | 4         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 14398     | 83.18%  |
| Yes  | 2911      | 16.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2587      | 57.72%  |
| Realtek Semiconductor           | 347       | 7.74%   |
| Broadcom                        | 247       | 5.51%   |
| Apple                           | 239       | 5.33%   |
| Qualcomm Atheros Communications | 233       | 5.2%    |
| IMC Networks                    | 196       | 4.37%   |
| Cambridge Silicon Radio         | 140       | 3.12%   |
| Foxconn / Hon Hai               | 91        | 2.03%   |
| Lite-On Technology              | 86        | 1.92%   |
| MediaTek                        | 73        | 1.63%   |
| ASUSTek Computer                | 67        | 1.49%   |
| Dell                            | 44        | 0.98%   |
| Hewlett-Packard                 | 34        | 0.76%   |
| Alps Electric                   | 19        | 0.42%   |
| Ralink                          | 15        | 0.33%   |
| TP-Link                         | 12        | 0.27%   |
| Skylight Digital                | 8         | 0.18%   |
| USI                             | 4         | 0.09%   |
| Toshiba                         | 4         | 0.09%   |
| Micro Star International        | 3         | 0.07%   |
| Integrated System Solution      | 3         | 0.07%   |
| Fujitsu                         | 3         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| HTC (High Tech Computer)        | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| Creative Technology             | 2         | 0.04%   |
| Askey Computer                  | 2         | 0.04%   |
| Unknown                         | 2         | 0.04%   |
| Sino Wealth Electronic          | 1         | 0.02%   |
| Silicon Wave                    | 1         | 0.02%   |
| Shenzhen Goodix Technology      | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Ralink Technology               | 1         | 0.02%   |
| Primax Electronics              | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Esel International              | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 1093      | 24.29%  |
| Intel AX201 Bluetooth                                       | 367       | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 323       | 7.18%   |
| Intel AX200 Bluetooth                                       | 311       | 6.91%   |
| Realtek Bluetooth Adapter                                   | 191       | 4.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 140       | 3.11%   |
| Intel AX210 Bluetooth                                       | 132       | 2.93%   |
| Apple Bluetooth Host Controller                             | 123       | 2.73%   |
| Intel Wireless-AC 3168 Bluetooth                            | 112       | 2.49%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 94        | 2.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 84        | 1.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 74        | 1.64%   |
| Intel AX211 Bluetooth                                       | 63        | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 63        | 1.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 60        | 1.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 51        | 1.13%   |
| IMC Networks Realtek Bluetooth Adapter                      | 48        | 1.07%   |
| Apple Broadcom Built-in Bluetooth                           | 48        | 1.07%   |
| Realtek  Bluetooth 4.2 Adapter                              | 47        | 1.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 45        | 1%      |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 34        | 0.76%   |
| MediaTek RZ608 Bluetooth Adapter                            | 33        | 0.73%   |
| Realtek Bluetooth 4.2 Adapter                               | 27        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 27        | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 26        | 0.58%   |
| MediaTek Wireless_Device                                    | 26        | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 26        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                            | 25        | 0.56%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 24        | 0.53%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 23        | 0.51%   |
| Realtek Bluetooth 4.0 Adapter                               | 22        | 0.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 19        | 0.42%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 19        | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 18        | 0.4%    |
| Dell DW375 Bluetooth Module                                 | 18        | 0.4%    |
| Lite-On Bluetooth USB Module                                | 17        | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 17        | 0.38%   |
| Apple Built-in iSight (no firmware loaded)                  | 17        | 0.38%   |
| Ralink RT3290 Bluetooth                                     | 15        | 0.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 15        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 10377     | 69.17%  |
| AMD                                          | 2539      | 16.92%  |
| Nvidia                                       | 1284      | 8.56%   |
| C-Media Electronics                          | 149       | 0.99%   |
| Zoran Co. Personal Media Division (Nogatech) | 63        | 0.42%   |
| Logitech                                     | 47        | 0.31%   |
| Texas Instruments                            | 42        | 0.28%   |
| Creative Labs                                | 42        | 0.28%   |
| Realtek Semiconductor                        | 28        | 0.19%   |
| Lenovo                                       | 25        | 0.17%   |
| GN Netcom                                    | 21        | 0.14%   |
| JMTek                                        | 19        | 0.13%   |
| VIA Technologies                             | 18        | 0.12%   |
| Focusrite-Novation                           | 18        | 0.12%   |
| Creative Technology                          | 18        | 0.12%   |
| Generalplus Technology                       | 17        | 0.11%   |
| SteelSeries ApS                              | 16        | 0.11%   |
| KTMicro                                      | 14        | 0.09%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.09%   |
| ASUSTek Computer                             | 13        | 0.09%   |
| ESS Technology                               | 12        | 0.08%   |
| Sony                                         | 10        | 0.07%   |
| Plantronics                                  | 10        | 0.07%   |
| Kingston Technology                          | 9         | 0.06%   |
| Blue Microphones                             | 9         | 0.06%   |
| BEHRINGER International                      | 9         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 8         | 0.05%   |
| MosArt Semiconductor                         | 7         | 0.05%   |
| Micro Star International                     | 7         | 0.05%   |
| Corsair                                      | 7         | 0.05%   |
| Yamaha                                       | 6         | 0.04%   |
| Cambridge Silicon Radio                      | 6         | 0.04%   |
| XMOS                                         | 5         | 0.03%   |
| Razer USA                                    | 5         | 0.03%   |
| M-Audio                                      | 5         | 0.03%   |
| Hewlett-Packard                              | 5         | 0.03%   |
| Apple                                        | 5         | 0.03%   |
| Walmart                                      | 4         | 0.03%   |
| Tenx Technology                              | 4         | 0.03%   |
| RODE Microphones                             | 4         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 778       | 4.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 778       | 4.36%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 737       | 4.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 716       | 4.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 692       | 3.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 655       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 648       | 3.63%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 627       | 3.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 545       | 3.05%   |
| Intel Jasper Lake HD Audio                                                                        | 540       | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 499       | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 476       | 2.67%   |
| AMD FCH Azalia Controller                                                                         | 458       | 2.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 382       | 2.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 362       | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 358       | 2.01%   |
| Intel 8 Series HD Audio Controller                                                                | 341       | 1.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 336       | 1.88%   |
| Intel 200 Series PCH HD Audio                                                                     | 331       | 1.86%   |
| Intel Broadwell-U Audio Controller                                                                | 317       | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 306       | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 286       | 1.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 271       | 1.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 252       | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 246       | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 228       | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 204       | 1.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 201       | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 198       | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 178       | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 165       | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 164       | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 147       | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 135       | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 130       | 0.73%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 123       | 0.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 119       | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 102       | 0.57%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 100       | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 94        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 3279      | 18.64%  |
| SK hynix                                | 2380      | 13.53%  |
| Kingston                                | 1989      | 11.31%  |
| Crucial                                 | 1701      | 9.67%   |
| Unknown                                 | 1662      | 9.45%   |
| Micron Technology                       | 1623      | 9.23%   |
| Corsair                                 | 722       | 4.1%    |
| Unknown                                 | 588       | 3.34%   |
| G.Skill                                 | 547       | 3.11%   |
| Transcend                               | 336       | 1.91%   |
| A-DATA Technology                       | 319       | 1.81%   |
| Unknown (ABCD)                          | 245       | 1.39%   |
| Ramaxel Technology                      | 227       | 1.29%   |
| Team                                    | 172       | 0.98%   |
| Nanya Technology                        | 168       | 0.95%   |
| Elpida                                  | 144       | 0.82%   |
| Patriot                                 | 121       | 0.69%   |
| Apacer                                  | 81        | 0.46%   |
| Kimtigo                                 | 76        | 0.43%   |
| Hewlett-Packard                         | 72        | 0.41%   |
| Toshiba                                 | 66        | 0.38%   |
| Smart                                   | 57        | 0.32%   |
| Timetec                                 | 47        | 0.27%   |
| GOODRAM                                 | 45        | 0.26%   |
| ATP                                     | 43        | 0.24%   |
| PNY                                     | 40        | 0.23%   |
| Avant                                   | 36        | 0.2%    |
| Teikon                                  | 29        | 0.16%   |
| Silicon Power                           | 28        | 0.16%   |
| SK_Hynix                                | 25        | 0.14%   |
| AMD                                     | 25        | 0.14%   |
| Patriot Memory (PDP Systems)            | 23        | 0.13%   |
| Unknown (AB)                            | 21        | 0.12%   |
| Innodisk                                | 21        | 0.12%   |
| Lexar Co Limited                        | 20        | 0.11%   |
| GeIL                                    | 19        | 0.11%   |
| Super Talent                            | 17        | 0.1%    |
| Wodposit                                | 16        | 0.09%   |
| Silicon Power Computer & Communications | 16        | 0.09%   |
| HPE                                     | 16        | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 588       | 3.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 225       | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 200       | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 146       | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 120       | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 98        | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 97        | 0.52%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s        | 88        | 0.47%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 83        | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 80        | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 77        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 71        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 70        | 0.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 70        | 0.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 69        | 0.37%   |
| Crucial RAM CT16G56C46S5.M8G1 16GB SODIMM DDR5 5600MT/s        | 67        | 0.36%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s        | 66        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 65        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 60        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 59        | 0.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s          | 55        | 0.29%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 54        | 0.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 54        | 0.29%   |
| Unknown RAM Module 8GB 1600MT/s                                | 52        | 0.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 52        | 0.28%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 50        | 0.27%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 49        | 0.26%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 49        | 0.26%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 49        | 0.26%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 48        | 0.26%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 48        | 0.26%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 47        | 0.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 46        | 0.25%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 44        | 0.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 44        | 0.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 44        | 0.23%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 43        | 0.23%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 43        | 0.23%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 42        | 0.22%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 42        | 0.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR3            | 6530      | 42.13%  |
| DDR4            | 6270      | 40.45%  |
| DDR5            | 719       | 4.64%   |
| DDR2            | 643       | 4.15%   |
| LPDDR4          | 422       | 2.72%   |
| Unknown         | 386       | 2.49%   |
| SDRAM           | 166       | 1.07%   |
| LPDDR5          | 134       | 0.86%   |
| LPDDR3          | 121       | 0.78%   |
| DDR             | 77        | 0.5%    |
| DRAM            | 22        | 0.14%   |
| RAM             | 4         | 0.03%   |
| Logical non-vol | 2         | 0.01%   |
| SRAM            | 1         | 0.01%   |
| LPDDR2          | 1         | 0.01%   |
| EEPROM          | 1         | 0.01%   |
| DDR2 FB-DIMM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 7440      | 48.16%  |
| DIMM            | 7339      | 47.51%  |
| Row Of Chips    | 413       | 2.67%   |
| Unknown         | 123       | 0.8%    |
| Chip            | 78        | 0.5%    |
| FB-DIMM         | 35        | 0.23%   |
| RIMM            | 18        | 0.12%   |
| Proprietary Car | 1         | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 6060      | 36.34%  |
| 4096   | 4878      | 29.25%  |
| 16384  | 2684      | 16.09%  |
| 2048   | 1907      | 11.43%  |
| 32768  | 660       | 3.96%   |
| 1024   | 378       | 2.27%   |
| 512    | 47        | 0.28%   |
| 65536  | 15        | 0.09%   |
| 3072   | 13        | 0.08%   |
| 256    | 9         | 0.05%   |
| 49152  | 8         | 0.05%   |
| 128    | 4         | 0.02%   |
| 131072 | 3         | 0.02%   |
| 6144   | 3         | 0.02%   |
| 32767  | 2         | 0.01%   |
| 64     | 2         | 0.01%   |
| 2560   | 1         | 0.01%   |
| 32     | 1         | 0.01%   |
| 8      | 1         | 0.01%   |
| 1      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 4343      | 26.35%  |
| 2400    | 1903      | 11.55%  |
| 1333    | 1902      | 11.54%  |
| 3200    | 1860      | 11.29%  |
| 2667    | 1675      | 10.16%  |
| 2133    | 1047      | 6.35%   |
| 4800    | 533       | 3.23%   |
| 800     | 436       | 2.65%   |
| 667     | 405       | 2.46%   |
| 2666    | 257       | 1.56%   |
| Unknown | 252       | 1.53%   |
| 1334    | 217       | 1.32%   |
| 1867    | 215       | 1.3%    |
| 1067    | 192       | 1.17%   |
| 5600    | 191       | 1.16%   |
| 1066    | 179       | 1.09%   |
| 1866    | 117       | 0.71%   |
| 6400    | 113       | 0.69%   |
| 3000    | 101       | 0.61%   |
| 3600    | 96        | 0.58%   |
| 2933    | 94        | 0.57%   |
| 533     | 54        | 0.33%   |
| 4267    | 52        | 0.32%   |
| 400     | 41        | 0.25%   |
| 5200    | 20        | 0.12%   |
| 4000    | 20        | 0.12%   |
| 975     | 18        | 0.11%   |
| 3733    | 14        | 0.08%   |
| 2048    | 11        | 0.07%   |
| 333     | 11        | 0.07%   |
| 4266    | 9         | 0.05%   |
| 1400    | 8         | 0.05%   |
| 1332    | 8         | 0.05%   |
| 1033    | 8         | 0.05%   |
| 266     | 8         | 0.05%   |
| 1639    | 6         | 0.04%   |
| 65535   | 5         | 0.03%   |
| 3400    | 5         | 0.03%   |
| 2800    | 5         | 0.03%   |
| 2600    | 5         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 16        | 32.65%  |
| Hewlett-Packard       | 12        | 24.49%  |
| Prolific Technology   | 4         | 8.16%   |
| Samsung Electronics   | 3         | 6.12%   |
| Seiko Epson           | 2         | 4.08%   |
| Lexmark International | 2         | 4.08%   |
| ELGIN                 | 2         | 4.08%   |
| Dymo-CoStar           | 2         | 4.08%   |
| Apple                 | 2         | 4.08%   |
| Ricoh                 | 1         | 2.04%   |
| QinHeng Electronics   | 1         | 2.04%   |
| Kyocera               | 1         | 2.04%   |
| Canon                 | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                                                     | 4         | 7.84%   |
| ELGIN L42PRO                                                                                                      | 2         | 3.92%   |
| Brother MFC-7360N                                                                                                 | 2         | 3.92%   |
| Brother HL-1430 Laser Printer                                                                                     | 2         | 3.92%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 1.96%   |
| Seiko Epson Printer                                                                                               | 1         | 1.96%   |
| Samsung ML-2010P Mono Laser Printer                                                                               | 1         | 1.96%   |
| Samsung ML-1640 Series Laser Printer                                                                              | 1         | 1.96%   |
| Samsung ML-1610 Mono Laser Printer                                                                                | 1         | 1.96%   |
| Ricoh SP 112                                                                                                      | 1         | 1.96%   |
| QinHeng CH340S                                                                                                    | 1         | 1.96%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 1.96%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 1.96%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 1.96%   |
| HP PNP Fax Null                                                                                                   | 1         | 1.96%   |
| HP LaserJet P3005                                                                                                 | 1         | 1.96%   |
| HP LaserJet 3390                                                                                                  | 1         | 1.96%   |
| HP LaserJet 2200                                                                                                  | 1         | 1.96%   |
| HP LaserJet 1200                                                                                                  | 1         | 1.96%   |
| HP LaserJet 1020                                                                                                  | 1         | 1.96%   |
| HP LaserJet 1012                                                                                                  | 1         | 1.96%   |
| HP Laser 107a Printer                                                                                             | 1         | 1.96%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 1.96%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 1.96%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer                        | 1         | 1.96%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer                                          | 1         | 1.96%   |
| HP DeskJet 5850c                                                                                                  | 1         | 1.96%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 1.96%   |
| Dymo-CoStar LabelWriter 450                                                                                       | 1         | 1.96%   |
| Dymo-CoStar DYMO LabelWriter 450 DUO                                                                              | 1         | 1.96%   |
| Canon LBP2900                                                                                                     | 1         | 1.96%   |
| Brother MFC-L2685DW                                                                                               | 1         | 1.96%   |
| Brother MFC-J485DW                                                                                                | 1         | 1.96%   |
| Brother MFC-J200                                                                                                  | 1         | 1.96%   |
| Brother HL-L5200DW series                                                                                         | 1         | 1.96%   |
| Brother HL-L3270CDW series                                                                                        | 1         | 1.96%   |
| Brother HL-L2340D series                                                                                          | 1         | 1.96%   |
| Brother HL-L2310D series                                                                                          | 1         | 1.96%   |
| Brother HL-L2300D series                                                                                          | 1         | 1.96%   |
| Brother HL-2030 Laser Printer                                                                                     | 1         | 1.96%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 16        | 66.67%  |
| Seiko Epson     | 7         | 29.17%  |
| Hewlett-Packard | 1         | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 4         | 16.67%  |
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 8.33%   |
| Canon CanoScan LiDE 220                                                             | 2         | 8.33%   |
| Canon CanoScan LiDE 210                                                             | 2         | 8.33%   |
| Canon CanoScan LiDE 120                                                             | 2         | 8.33%   |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 4.17%   |
| Seiko Epson PX-501A [Stylus NX400]                                                  | 1         | 4.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                 | 1         | 4.17%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                       | 1         | 4.17%   |
| Seiko Epson ES-H7200 [GT-20000]                                                     | 1         | 4.17%   |
| HP ScanJet 5300c/5370c                                                              | 1         | 4.17%   |
| Canon CanoScan N650U/N656U                                                          | 1         | 4.17%   |
| Canon CanoScan N1240U/LiDE 30                                                       | 1         | 4.17%   |
| Canon CanoScan LiDE 700F                                                            | 1         | 4.17%   |
| Canon CanoScan LIDE 25                                                              | 1         | 4.17%   |
| Canon CanoScan LiDE 100                                                             | 1         | 4.17%   |
| Canon CanoScan 9000F                                                                | 1         | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 716       | 26.34%  |
| Bison Electronics                      | 278       | 10.23%  |
| IMC Networks                           | 243       | 8.94%   |
| Microdia                               | 233       | 8.57%   |
| Realtek Semiconductor                  | 215       | 7.91%   |
| Sunplus Innovation Technology          | 156       | 5.74%   |
| Logitech                               | 125       | 4.6%    |
| Lite-On Technology                     | 82        | 3.02%   |
| Suyin                                  | 77        | 2.83%   |
| Quanta                                 | 65        | 2.39%   |
| Syntek                                 | 63        | 2.32%   |
| Apple                                  | 61        | 2.24%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 2.21%   |
| Luxvisions Innotech Limited            | 42        | 1.55%   |
| Silicon Motion                         | 41        | 1.51%   |
| Lenovo                                 | 32        | 1.18%   |
| Alcor Micro                            | 30        | 1.1%    |
| Z-Star Microelectronics                | 26        | 0.96%   |
| Ricoh                                  | 16        | 0.59%   |
| ALi                                    | 16        | 0.59%   |
| Importek                               | 12        | 0.44%   |
| Shenzhen Kingcome Optoelectronic       | 10        | 0.37%   |
| ARC International                      | 9         | 0.33%   |
| Supreme Electronics                    | 8         | 0.29%   |
| Jiangxi Shinetech Optical              | 6         | 0.22%   |
| Intel                                  | 6         | 0.22%   |
| Trust                                  | 5         | 0.18%   |
| GEMBIRD                                | 5         | 0.18%   |
| Primax Electronics                     | 4         | 0.15%   |
| OmniVision Technologies                | 4         | 0.15%   |
| Genesys Logic                          | 4         | 0.15%   |
| DigiTech                               | 4         | 0.15%   |
| Cubeternet                             | 4         | 0.15%   |
| Arkmicro Technologies                  | 4         | 0.15%   |
| USB Camera                             | 3         | 0.11%   |
| Unknown (3730304233343731345430)       | 3         | 0.11%   |
| Unknown                                | 3         | 0.11%   |
| Tripath Technology                     | 3         | 0.11%   |
| Pixart Imaging                         | 3         | 0.11%   |
| Generalplus Technology                 | 3         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 225       | 8.2%    |
| Bison Integrated Camera                       | 128       | 4.67%   |
| IMC Networks Integrated Camera                | 74        | 2.7%    |
| Microdia Integrated_Webcam_HD                 | 71        | 2.59%   |
| Sunplus Integrated_Webcam_HD                  | 54        | 1.97%   |
| Lite-On Integrated Camera                     | 52        | 1.9%    |
| Chicony HD WebCam                             | 49        | 1.79%   |
| Realtek Integrated_Webcam_HD                  | 48        | 1.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 47        | 1.71%   |
| Microdia Integrated Webcam                    | 46        | 1.68%   |
| IMC Networks Realtek PC Camera                | 36        | 1.31%   |
| Realtek USB 2.0 PC Camera                     | 34        | 1.24%   |
| Logitech Webcam C270                          | 32        | 1.17%   |
| Chicony Integrated Camera (1280x720@30)       | 30        | 1.09%   |
| Bison Lenovo EasyCamera                       | 30        | 1.09%   |
| Apple FaceTime HD Camera                      | 30        | 1.09%   |
| Bison SunplusIT Integrated Camera             | 29        | 1.06%   |
| Logitech HD Pro Webcam C920                   | 27        | 0.98%   |
| IMC Networks EasyCamera                       | 27        | 0.98%   |
| Syntek Integrated Camera                      | 23        | 0.84%   |
| Chicony Integrated Camera [ThinkPad]          | 23        | 0.84%   |
| Bison ThinkPad Integrated Camera              | 22        | 0.8%    |
| Apple FaceTime HD Camera (Built-in)           | 22        | 0.8%    |
| Luxvisions Innotech Limited Integrated Camera | 20        | 0.73%   |
| Syntek Lenovo EasyCamera                      | 19        | 0.69%   |
| Realtek USB Camera                            | 19        | 0.69%   |
| Chicony Realtek DMFT RGB                      | 18        | 0.66%   |
| Chicony Integrated IR Camera                  | 18        | 0.66%   |
| Chicony HP HD Webcam [Fixed]                  | 17        | 0.62%   |
| Chicony FJ Camera                             | 17        | 0.62%   |
| Chicony EasyCamera                            | 17        | 0.62%   |
| Syntek EasyCamera                             | 16        | 0.58%   |
| Lenovo Integrated Webcam [R5U877]             | 16        | 0.58%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 15        | 0.55%   |
| Chicony Chicony USB2.0 Camera                 | 15        | 0.55%   |
| Quanta HP TrueVision HD Camera                | 14        | 0.51%   |
| Chicony USB2.0 HD UVC WebCam                  | 14        | 0.51%   |
| Chicony Lenovo EasyCamera                     | 14        | 0.51%   |
| Bison Lenovo Integrated Webcam                | 14        | 0.51%   |
| IMC Networks UVC VGA Webcam                   | 13        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 256       | 35.36%  |
| Synaptics                  | 151       | 20.86%  |
| Upek                       | 70        | 9.67%   |
| Shenzhen Goodix Technology | 60        | 8.29%   |
| AuthenTec                  | 55        | 7.6%    |
| Elan Microelectronics      | 38        | 5.25%   |
| STMicroelectronics         | 34        | 4.7%    |
| Broadcom                   | 21        | 2.9%    |
| LighTuning Technology      | 17        | 2.35%   |
| FocalTech Systems          | 13        | 1.8%    |
| Fingerprint Cards          | 4         | 0.55%   |
| Samsung Electronics        | 3         | 0.41%   |
| Next Biometrics            | 1         | 0.14%   |
| DigitalPersona             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 81        | 11.19%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 67        | 9.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 61        | 8.43%   |
| Validity Sensors Synaptics WBDI                                              | 48        | 6.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 47        | 6.49%   |
| Shenzhen Goodix Fingerprint Reader                                           | 44        | 6.08%   |
| Elan Fingerprint Sensor                                                      | 35        | 4.83%   |
| STMicroelectronics Fingerprint Reader                                        | 34        | 4.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 33        | 4.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 26        | 3.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 19        | 2.62%   |
| AuthenTec AES2810                                                            | 17        | 2.35%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 14        | 1.93%   |
| Synaptics WBDI                                                               | 10        | 1.38%   |
| FocalTech Systems Fingerprint Reader                                         | 10        | 1.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 9         | 1.24%   |
| Shenzhen Goodix  Fingerprint Device                                          | 9         | 1.24%   |
| Validity Sensors VFS491                                                      | 8         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 8         | 1.1%    |
| AuthenTec AES1660                                                            | 8         | 1.1%    |
| Validity Sensors Fingerprint scanner                                         | 7         | 0.97%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 7         | 0.97%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 7         | 0.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 7         | 0.97%   |
| AuthenTec AES1600                                                            | 7         | 0.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 6         | 0.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 6         | 0.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 6         | 0.83%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 5         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 4         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 0.55%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 4         | 0.55%   |
| AuthenTec AES2660                                                            | 4         | 0.55%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 3         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.41%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.41%   |
| Synaptics UWP WBDI Device                                                    | 3         | 0.41%   |
| Synaptics Fingerprint reader [HP G6]                                         | 3         | 0.41%   |
| Samsung CanvasBio Fingerprint Reader                                         | 3         | 0.41%   |

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
| 1     | 7207      | 41.82%  |
| 0     | 5065      | 29.39%  |
| 2     | 3120      | 18.1%   |
| 3     | 1301      | 7.55%   |
| 4     | 409       | 2.37%   |
| 5     | 95        | 0.55%   |
| 6     | 23        | 0.13%   |
| 7     | 10        | 0.06%   |
| 9     | 2         | 0.01%   |
| 8     | 2         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 10333     | 61.82%  |
| Bluetooth                | 1847      | 11.05%  |
| Net/wireless             | 1601      | 9.58%   |
| Card reader              | 882       | 5.28%   |
| Fingerprint reader       | 620       | 3.71%   |
| Firewire controller      | 448       | 2.68%   |
| Sound                    | 255       | 1.53%   |
| Net/ethernet             | 227       | 1.36%   |
| Network                  | 208       | 1.24%   |
| Graphics card            | 138       | 0.83%   |
| Storage                  | 62        | 0.37%   |
| Modem                    | 26        | 0.16%   |
| Storage/ata              | 23        | 0.14%   |
| Storage/raid             | 21        | 0.13%   |
| Dvb card                 | 13        | 0.08%   |
| Storage/ide              | 7         | 0.04%   |
| Storage/nvme             | 4         | 0.02%   |
| Wireless                 | 1         | 0.01%   |

