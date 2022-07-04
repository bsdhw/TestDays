BSD in UK - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for BSD in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 534

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Inventec      | D CLASS A02                 | Desktop     | [6b5f81700c](https://bsd-hardware.info/?probe=6b5f81700c) | Jul 01, 2022 |
| Intel         | CARLOW                      | Desktop     | [615107464b](https://bsd-hardware.info/?probe=615107464b) | Jul 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f8d0f1f7e0](https://bsd-hardware.info/?probe=f8d0f1f7e0) | Jun 29, 2022 |
| System76      | Gazelle                     | Notebook    | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | Notebook    | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| AMD           | Kabini CRB                  | Desktop     | [2ee9e57522](https://bsd-hardware.info/?probe=2ee9e57522) | Jun 26, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [58ff991ef8](https://bsd-hardware.info/?probe=58ff991ef8) | Jun 23, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [aa5b395a20](https://bsd-hardware.info/?probe=aa5b395a20) | Jun 19, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | Desktop     | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [02c0f92734](https://bsd-hardware.info/?probe=02c0f92734) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Gigabyte      | N3150ND3V                   | Desktop     | [56999b6746](https://bsd-hardware.info/?probe=56999b6746) | Jun 13, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [d44f80f2d9](https://bsd-hardware.info/?probe=d44f80f2d9) | Jun 01, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [31c49e462c](https://bsd-hardware.info/?probe=31c49e462c) | Jun 01, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [ee7e944260](https://bsd-hardware.info/?probe=ee7e944260) | May 31, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [2c55c55a67](https://bsd-hardware.info/?probe=2c55c55a67) | May 31, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [607561a9a4](https://bsd-hardware.info/?probe=607561a9a4) | May 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c67bf4af0a](https://bsd-hardware.info/?probe=c67bf4af0a) | May 27, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3d0fdb11ff](https://bsd-hardware.info/?probe=3d0fdb11ff) | May 27, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [d5773cd8b3](https://bsd-hardware.info/?probe=d5773cd8b3) | May 16, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [34eddd04fc](https://bsd-hardware.info/?probe=34eddd04fc) | May 16, 2022 |
| Lenovo        | ThinkPad X230 2325J67       | Notebook    | [3ee0f54d2f](https://bsd-hardware.info/?probe=3ee0f54d2f) | May 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [c6faa8080e](https://bsd-hardware.info/?probe=c6faa8080e) | May 10, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | Notebook    | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Gigabyte      | H81N                        | Desktop     | [d922327cdd](https://bsd-hardware.info/?probe=d922327cdd) | May 06, 2022 |
| Intel         | CARLOW                      | Desktop     | [6f185d9b30](https://bsd-hardware.info/?probe=6f185d9b30) | May 06, 2022 |
| Intel         | CARLOW                      | Desktop     | [2240df9d2d](https://bsd-hardware.info/?probe=2240df9d2d) | May 04, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| HP            | Pavilion m6                 | Notebook    | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1YG01    | Notebook    | [6e38eb1a4e](https://bsd-hardware.info/?probe=6e38eb1a4e) | May 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [60932d337b](https://bsd-hardware.info/?probe=60932d337b) | Apr 28, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [544b83da9f](https://bsd-hardware.info/?probe=544b83da9f) | Apr 24, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [9758c067ec](https://bsd-hardware.info/?probe=9758c067ec) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [3b256304a0](https://bsd-hardware.info/?probe=3b256304a0) | Apr 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [6f4c78b7db](https://bsd-hardware.info/?probe=6f4c78b7db) | Apr 23, 2022 |
| Dell          | 0N051F A01                  | Server      | [0784468d7a](https://bsd-hardware.info/?probe=0784468d7a) | Apr 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3813b46bc1](https://bsd-hardware.info/?probe=3813b46bc1) | Apr 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a2fc9672d6](https://bsd-hardware.info/?probe=a2fc9672d6) | Apr 22, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [c4dee3f070](https://bsd-hardware.info/?probe=c4dee3f070) | Apr 21, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [3322ad9dac](https://bsd-hardware.info/?probe=3322ad9dac) | Apr 20, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [aa48329066](https://bsd-hardware.info/?probe=aa48329066) | Apr 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [d9acb17caf](https://bsd-hardware.info/?probe=d9acb17caf) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [754d45f24f](https://bsd-hardware.info/?probe=754d45f24f) | Apr 11, 2022 |
| Jetway        | 1.0                         | Desktop     | [0048067292](https://bsd-hardware.info/?probe=0048067292) | Apr 11, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [f4098d352f](https://bsd-hardware.info/?probe=f4098d352f) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [907da6ea08](https://bsd-hardware.info/?probe=907da6ea08) | Apr 10, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [f71ea0931e](https://bsd-hardware.info/?probe=f71ea0931e) | Apr 10, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [a7470aa647](https://bsd-hardware.info/?probe=a7470aa647) | Apr 09, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7eee3bb3d8](https://bsd-hardware.info/?probe=7eee3bb3d8) | Apr 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0911185155](https://bsd-hardware.info/?probe=0911185155) | Apr 05, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [2a7de69b4b](https://bsd-hardware.info/?probe=2a7de69b4b) | Apr 04, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [1b382db711](https://bsd-hardware.info/?probe=1b382db711) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [6274858d8d](https://bsd-hardware.info/?probe=6274858d8d) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [137a301b9b](https://bsd-hardware.info/?probe=137a301b9b) | Mar 31, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [9fae64765f](https://bsd-hardware.info/?probe=9fae64765f) | Mar 31, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [eaa8d1a7d7](https://bsd-hardware.info/?probe=eaa8d1a7d7) | Mar 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [730dd09705](https://bsd-hardware.info/?probe=730dd09705) | Mar 28, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5d554517f2](https://bsd-hardware.info/?probe=5d554517f2) | Mar 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e67af6e204](https://bsd-hardware.info/?probe=e67af6e204) | Mar 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a25c6f603c](https://bsd-hardware.info/?probe=a25c6f603c) | Mar 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9913acc698](https://bsd-hardware.info/?probe=9913acc698) | Mar 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e58663aeb0](https://bsd-hardware.info/?probe=e58663aeb0) | Mar 24, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [e9f59e748e](https://bsd-hardware.info/?probe=e9f59e748e) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b49ac0cf2](https://bsd-hardware.info/?probe=9b49ac0cf2) | Mar 23, 2022 |
| Intel         | DH61CR AAG14064-209         | Desktop     | [3812666505](https://bsd-hardware.info/?probe=3812666505) | Mar 23, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [87289f0c36](https://bsd-hardware.info/?probe=87289f0c36) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [dafb1bbb92](https://bsd-hardware.info/?probe=dafb1bbb92) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [8870903766](https://bsd-hardware.info/?probe=8870903766) | Mar 20, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c9fb46b179](https://bsd-hardware.info/?probe=c9fb46b179) | Mar 19, 2022 |
| Gigabyte      | H81N                        | Desktop     | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [d28bef2c37](https://bsd-hardware.info/?probe=d28bef2c37) | Mar 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [72b461ded3](https://bsd-hardware.info/?probe=72b461ded3) | Mar 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [10a235fe8f](https://bsd-hardware.info/?probe=10a235fe8f) | Mar 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [a556350922](https://bsd-hardware.info/?probe=a556350922) | Mar 11, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a22c1d4ab](https://bsd-hardware.info/?probe=5a22c1d4ab) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Sophos        | SG                          | Firewall    | [70d42d9a3a](https://bsd-hardware.info/?probe=70d42d9a3a) | Mar 07, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [77c308e93e](https://bsd-hardware.info/?probe=77c308e93e) | Mar 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1ffc0a0805](https://bsd-hardware.info/?probe=1ffc0a0805) | Mar 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f1d5448b3](https://bsd-hardware.info/?probe=3f1d5448b3) | Mar 01, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [26565f3d84](https://bsd-hardware.info/?probe=26565f3d84) | Mar 01, 2022 |
| Dell          | 0M877N A01                  | Server      | [af93606e74](https://bsd-hardware.info/?probe=af93606e74) | Feb 24, 2022 |
| Biostar       | J3160NH                     | Desktop     | [536f856d94](https://bsd-hardware.info/?probe=536f856d94) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| Jumper        | EZbook                      | Notebook    | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| Gigabyte      | H81N                        | Desktop     | [fc273bb51a](https://bsd-hardware.info/?probe=fc273bb51a) | Feb 14, 2022 |
| Gigabyte      | H81N                        | Desktop     | [5accd7ce0d](https://bsd-hardware.info/?probe=5accd7ce0d) | Feb 13, 2022 |
| Dell          | 00NH4P A02                  | Server      | [5c1ea00df3](https://bsd-hardware.info/?probe=5c1ea00df3) | Feb 08, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [b6329aa072](https://bsd-hardware.info/?probe=b6329aa072) | Feb 06, 2022 |
| Dell          | 03X6X0 A03                  | Server      | [08e48565c1](https://bsd-hardware.info/?probe=08e48565c1) | Feb 06, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [a3843d55ca](https://bsd-hardware.info/?probe=a3843d55ca) | Feb 05, 2022 |
| Intel         | J1900                       | Desktop     | [3b4b841677](https://bsd-hardware.info/?probe=3b4b841677) | Feb 04, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [c3394665a0](https://bsd-hardware.info/?probe=c3394665a0) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [86cb857d00](https://bsd-hardware.info/?probe=86cb857d00) | Feb 02, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| PC Engines    | APU2                        | Desktop     | [0409aa82c2](https://bsd-hardware.info/?probe=0409aa82c2) | Feb 01, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [4b4b77d8f3](https://bsd-hardware.info/?probe=4b4b77d8f3) | Feb 01, 2022 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [a65a16decd](https://bsd-hardware.info/?probe=a65a16decd) | Jan 31, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [d08074d468](https://bsd-hardware.info/?probe=d08074d468) | Jan 28, 2022 |
| Dell          | 00NH4P A02                  | Server      | [b456eb04b7](https://bsd-hardware.info/?probe=b456eb04b7) | Jan 28, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [461b538b72](https://bsd-hardware.info/?probe=461b538b72) | Jan 28, 2022 |
| Unknown       | PICO PC                     | Desktop     | [538ca6b389](https://bsd-hardware.info/?probe=538ca6b389) | Jan 27, 2022 |
| CheckPoint    | PB-10-00                    | Firewall    | [68b230df84](https://bsd-hardware.info/?probe=68b230df84) | Jan 25, 2022 |
| CheckPoint    | PB-10-00                    | Firewall    | [ef85ae90b3](https://bsd-hardware.info/?probe=ef85ae90b3) | Jan 25, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [277f5bacdd](https://bsd-hardware.info/?probe=277f5bacdd) | Jan 22, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [6ea5e898fa](https://bsd-hardware.info/?probe=6ea5e898fa) | Jan 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Jumper        | EZbook                      | Notebook    | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1520fece28](https://bsd-hardware.info/?probe=1520fece28) | Jan 17, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [55716e7c8b](https://bsd-hardware.info/?probe=55716e7c8b) | Jan 17, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | Notebook    | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [5f106ee686](https://bsd-hardware.info/?probe=5f106ee686) | Jan 15, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [6bde480ecd](https://bsd-hardware.info/?probe=6bde480ecd) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Winston Ma... | PICO PC                     | Desktop     | [ac1014aab2](https://bsd-hardware.info/?probe=ac1014aab2) | Jan 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [e85c24b03a](https://bsd-hardware.info/?probe=e85c24b03a) | Jan 11, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| HP            | 8169                        | Desktop     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [9a24935dab](https://bsd-hardware.info/?probe=9a24935dab) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [ce54324df7](https://bsd-hardware.info/?probe=ce54324df7) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [de6d713222](https://bsd-hardware.info/?probe=de6d713222) | Jan 05, 2022 |
| PC Engines    | APU                         | Desktop     | [efe2fbd850](https://bsd-hardware.info/?probe=efe2fbd850) | Jan 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0a180d834c](https://bsd-hardware.info/?probe=0a180d834c) | Jan 03, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [b956c2a933](https://bsd-hardware.info/?probe=b956c2a933) | Dec 28, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [c3c1529f86](https://bsd-hardware.info/?probe=c3c1529f86) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [90919a642f](https://bsd-hardware.info/?probe=90919a642f) | Dec 21, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [44d3e7366c](https://bsd-hardware.info/?probe=44d3e7366c) | Dec 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [045ffeb9b3](https://bsd-hardware.info/?probe=045ffeb9b3) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| Dell          | 0N051F A01                  | Server      | [071ad110ab](https://bsd-hardware.info/?probe=071ad110ab) | Dec 01, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [67556468e3](https://bsd-hardware.info/?probe=67556468e3) | Nov 30, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [92fc69392b](https://bsd-hardware.info/?probe=92fc69392b) | Nov 27, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [71f763e932](https://bsd-hardware.info/?probe=71f763e932) | Nov 25, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d3888a4c7d](https://bsd-hardware.info/?probe=d3888a4c7d) | Nov 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [99ceb827fe](https://bsd-hardware.info/?probe=99ceb827fe) | Nov 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [53e6ac863a](https://bsd-hardware.info/?probe=53e6ac863a) | Nov 18, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [56cd34ffef](https://bsd-hardware.info/?probe=56cd34ffef) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [8451595212](https://bsd-hardware.info/?probe=8451595212) | Nov 16, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [e0c3737f7c](https://bsd-hardware.info/?probe=e0c3737f7c) | Nov 15, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ea51e03be6](https://bsd-hardware.info/?probe=ea51e03be6) | Nov 13, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a2bbadf4a5](https://bsd-hardware.info/?probe=a2bbadf4a5) | Nov 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [f0c5f5ef97](https://bsd-hardware.info/?probe=f0c5f5ef97) | Nov 09, 2021 |
| ASUSTek       | 1001P                       | Notebook    | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [28a264a128](https://bsd-hardware.info/?probe=28a264a128) | Nov 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d0b487888a](https://bsd-hardware.info/?probe=d0b487888a) | Nov 08, 2021 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [abaafd0a1e](https://bsd-hardware.info/?probe=abaafd0a1e) | Nov 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [83480615f6](https://bsd-hardware.info/?probe=83480615f6) | Nov 04, 2021 |
| Yanling       | YL-KBR6L                    | Desktop     | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| Dell          | 081N4V A05                  | Server      | [2492e3f933](https://bsd-hardware.info/?probe=2492e3f933) | Nov 03, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| AZW           | GK55                        | Desktop     | [91db367d18](https://bsd-hardware.info/?probe=91db367d18) | Oct 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [8caf15c2a5](https://bsd-hardware.info/?probe=8caf15c2a5) | Oct 22, 2021 |
| Dell          | 05XKKK A04                  | Server      | [0c40d38f1d](https://bsd-hardware.info/?probe=0c40d38f1d) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| HP            | 15                          | Notebook    | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [5e82a5d94b](https://bsd-hardware.info/?probe=5e82a5d94b) | Oct 15, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [8e11143a1d](https://bsd-hardware.info/?probe=8e11143a1d) | Oct 14, 2021 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [c8b057c4e4](https://bsd-hardware.info/?probe=c8b057c4e4) | Oct 12, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [3bd1b15cee](https://bsd-hardware.info/?probe=3bd1b15cee) | Oct 11, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [4ecdb6038a](https://bsd-hardware.info/?probe=4ecdb6038a) | Oct 10, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4b25e8e063](https://bsd-hardware.info/?probe=4b25e8e063) | Oct 10, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [1b48acadd5](https://bsd-hardware.info/?probe=1b48acadd5) | Oct 10, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [f271d0163d](https://bsd-hardware.info/?probe=f271d0163d) | Oct 03, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [40aba3842c](https://bsd-hardware.info/?probe=40aba3842c) | Oct 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [357b9d3ad2](https://bsd-hardware.info/?probe=357b9d3ad2) | Sep 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [cc7d3fa6a3](https://bsd-hardware.info/?probe=cc7d3fa6a3) | Sep 26, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [dc09f7f7cb](https://bsd-hardware.info/?probe=dc09f7f7cb) | Sep 25, 2021 |
| ASRock        | J3455M                      | Desktop     | [411b04cbba](https://bsd-hardware.info/?probe=411b04cbba) | Sep 25, 2021 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [31a63f86a2](https://bsd-hardware.info/?probe=31a63f86a2) | Sep 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [462d25d041](https://bsd-hardware.info/?probe=462d25d041) | Sep 19, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [646148fc25](https://bsd-hardware.info/?probe=646148fc25) | Sep 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [5a4e53da56](https://bsd-hardware.info/?probe=5a4e53da56) | Sep 12, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [63a24ea67f](https://bsd-hardware.info/?probe=63a24ea67f) | Sep 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [dcd383c684](https://bsd-hardware.info/?probe=dcd383c684) | Sep 12, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [016e4443a0](https://bsd-hardware.info/?probe=016e4443a0) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8ce323def8](https://bsd-hardware.info/?probe=8ce323def8) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [7a289e8d1b](https://bsd-hardware.info/?probe=7a289e8d1b) | Sep 06, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | 0XDN97 A09                  | Server      | [4668ce0e56](https://bsd-hardware.info/?probe=4668ce0e56) | Sep 02, 2021 |
| HPE           | ML10Gen9                    | Server      | [d8a8039f9d](https://bsd-hardware.info/?probe=d8a8039f9d) | Aug 31, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [2499806edc](https://bsd-hardware.info/?probe=2499806edc) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [a98c6adb40](https://bsd-hardware.info/?probe=a98c6adb40) | Aug 22, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [beda690c72](https://bsd-hardware.info/?probe=beda690c72) | Aug 19, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f4fe59224e](https://bsd-hardware.info/?probe=f4fe59224e) | Aug 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [2b4ad9fd77](https://bsd-hardware.info/?probe=2b4ad9fd77) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [621207a309](https://bsd-hardware.info/?probe=621207a309) | Aug 11, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [7760e33e84](https://bsd-hardware.info/?probe=7760e33e84) | Aug 10, 2021 |
| Shuttle       | FH81                        | Desktop     | [58ddd2da40](https://bsd-hardware.info/?probe=58ddd2da40) | Aug 08, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [6106746a7f](https://bsd-hardware.info/?probe=6106746a7f) | Aug 07, 2021 |
| NU941         | 1.0                         | Desktop     | [e76f1a177c](https://bsd-hardware.info/?probe=e76f1a177c) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [aad64262b5](https://bsd-hardware.info/?probe=aad64262b5) | Jul 29, 2021 |
| Unknown       | PICO PC                     | Desktop     | [47f932c3d3](https://bsd-hardware.info/?probe=47f932c3d3) | Jul 29, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| Biostar       | A88M                        | Desktop     | [f9d3b78d58](https://bsd-hardware.info/?probe=f9d3b78d58) | Jul 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [41e0c49bcb](https://bsd-hardware.info/?probe=41e0c49bcb) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [05180e292a](https://bsd-hardware.info/?probe=05180e292a) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| HP            | 213D A01                    | Desktop     | [3b518acc68](https://bsd-hardware.info/?probe=3b518acc68) | Jul 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [17938ca56f](https://bsd-hardware.info/?probe=17938ca56f) | Jul 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [46aaff0a7c](https://bsd-hardware.info/?probe=46aaff0a7c) | Jul 14, 2021 |
| HP            | 0AE8h C                     | Desktop     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [18d373b2d3](https://bsd-hardware.info/?probe=18d373b2d3) | Jul 06, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [d8bd1a3025](https://bsd-hardware.info/?probe=d8bd1a3025) | Jul 05, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [3e1240d256](https://bsd-hardware.info/?probe=3e1240d256) | Jul 05, 2021 |
| PC Engines    | apu4                        | Desktop     | [18a1374b95](https://bsd-hardware.info/?probe=18a1374b95) | Jul 04, 2021 |
| Biostar       | B450MH                      | Desktop     | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Dell          | Latitude E6410              | Notebook    | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [1b35a7ea0a](https://bsd-hardware.info/?probe=1b35a7ea0a) | Jun 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [629973b03e](https://bsd-hardware.info/?probe=629973b03e) | Jun 26, 2021 |
| Intel CNCT... | Unknown                     | Desktop     | [d2298356a0](https://bsd-hardware.info/?probe=d2298356a0) | Jun 22, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | Notebook    | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [287ec8a2ee](https://bsd-hardware.info/?probe=287ec8a2ee) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [e6a66eac0b](https://bsd-hardware.info/?probe=e6a66eac0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [c7b4a17b7d](https://bsd-hardware.info/?probe=c7b4a17b7d) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [c3f7e818ae](https://bsd-hardware.info/?probe=c3f7e818ae) | Jun 18, 2021 |
| HPE           | ML10Gen9                    | Server      | [1a2b1b407b](https://bsd-hardware.info/?probe=1a2b1b407b) | Jun 17, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [5ccdc16de4](https://bsd-hardware.info/?probe=5ccdc16de4) | Jun 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [9062f35935](https://bsd-hardware.info/?probe=9062f35935) | Jun 10, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [2bb2632198](https://bsd-hardware.info/?probe=2bb2632198) | Jun 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [23751b05a9](https://bsd-hardware.info/?probe=23751b05a9) | Jun 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [c5f1ffd6c0](https://bsd-hardware.info/?probe=c5f1ffd6c0) | May 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cd60e38216](https://bsd-hardware.info/?probe=cd60e38216) | May 30, 2021 |
| HP            | 213D A01                    | Desktop     | [de3d6dcdf5](https://bsd-hardware.info/?probe=de3d6dcdf5) | May 22, 2021 |
| HP            | 18E7                        | Desktop     | [56a672af0a](https://bsd-hardware.info/?probe=56a672af0a) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [b7ea8547ce](https://bsd-hardware.info/?probe=b7ea8547ce) | May 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [03d2a695b2](https://bsd-hardware.info/?probe=03d2a695b2) | May 15, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| EVGA          | X299 FTW K                  | Desktop     | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [cc49321b12](https://bsd-hardware.info/?probe=cc49321b12) | May 11, 2021 |
| Dell          | 03X6X0 A08                  | Server      | [ede56150a6](https://bsd-hardware.info/?probe=ede56150a6) | May 10, 2021 |
| Biostar       | A88M                        | Desktop     | [74c3afbf45](https://bsd-hardware.info/?probe=74c3afbf45) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [062fe5ec40](https://bsd-hardware.info/?probe=062fe5ec40) | May 09, 2021 |
| Toshiba       | TECRA M11                   | Notebook    | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [a707beae6f](https://bsd-hardware.info/?probe=a707beae6f) | May 02, 2021 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [0cddbdee33](https://bsd-hardware.info/?probe=0cddbdee33) | May 01, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [1653ea52ce](https://bsd-hardware.info/?probe=1653ea52ce) | Apr 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7636bce7be](https://bsd-hardware.info/?probe=7636bce7be) | Apr 27, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [1a780b9a95](https://bsd-hardware.info/?probe=1a780b9a95) | Apr 27, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [d218181abb](https://bsd-hardware.info/?probe=d218181abb) | Apr 26, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [81610a700d](https://bsd-hardware.info/?probe=81610a700d) | Apr 26, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [aed8e7c08c](https://bsd-hardware.info/?probe=aed8e7c08c) | Apr 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [e90abb54c9](https://bsd-hardware.info/?probe=e90abb54c9) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f888bd5312](https://bsd-hardware.info/?probe=f888bd5312) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7dacccd5f5](https://bsd-hardware.info/?probe=7dacccd5f5) | Apr 18, 2021 |
| Samsung       | NC10                        | Notebook    | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [1cef60d042](https://bsd-hardware.info/?probe=1cef60d042) | Apr 13, 2021 |
| Samsung       | NC10                        | Notebook    | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [903d74f8e7](https://bsd-hardware.info/?probe=903d74f8e7) | Apr 12, 2021 |
| Unknown       | PICO PC                     | Desktop     | [8ab959af5c](https://bsd-hardware.info/?probe=8ab959af5c) | Apr 11, 2021 |
| Biostar       | A88M                        | Desktop     | [6fc307ade8](https://bsd-hardware.info/?probe=6fc307ade8) | Apr 09, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [563ad840b0](https://bsd-hardware.info/?probe=563ad840b0) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [9eafdd3e07](https://bsd-hardware.info/?probe=9eafdd3e07) | Apr 07, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [d9ec051372](https://bsd-hardware.info/?probe=d9ec051372) | Apr 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [5393389555](https://bsd-hardware.info/?probe=5393389555) | Apr 05, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cdeafa0952](https://bsd-hardware.info/?probe=cdeafa0952) | Apr 02, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [c366bef9bf](https://bsd-hardware.info/?probe=c366bef9bf) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| Dell          | 05KX61 A00                  | Server      | [56a394ac67](https://bsd-hardware.info/?probe=56a394ac67) | Mar 27, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [12909e67d4](https://bsd-hardware.info/?probe=12909e67d4) | Mar 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [159f39df79](https://bsd-hardware.info/?probe=159f39df79) | Mar 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [a81f03223e](https://bsd-hardware.info/?probe=a81f03223e) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [04d2c36bec](https://bsd-hardware.info/?probe=04d2c36bec) | Mar 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| HP            | 1825                        | Desktop     | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [192451364a](https://bsd-hardware.info/?probe=192451364a) | Mar 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d7790b678b](https://bsd-hardware.info/?probe=d7790b678b) | Mar 16, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [3e479a0551](https://bsd-hardware.info/?probe=3e479a0551) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Apple         | iMac12,1                    | All in one  | [17466db7fd](https://bsd-hardware.info/?probe=17466db7fd) | Mar 14, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [14142a990a](https://bsd-hardware.info/?probe=14142a990a) | Mar 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [1ad8d8132f](https://bsd-hardware.info/?probe=1ad8d8132f) | Mar 09, 2021 |
| Toshiba       | Satellite Pro U400          | Notebook    | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f27578615f](https://bsd-hardware.info/?probe=f27578615f) | Mar 05, 2021 |
| Dell          | Latitude E5570              | Notebook    | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [99448b6fad](https://bsd-hardware.info/?probe=99448b6fad) | Mar 02, 2021 |
| ZOTAC         | Board                       | Mini pc     | [b8a097931c](https://bsd-hardware.info/?probe=b8a097931c) | Mar 01, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [d106f46dde](https://bsd-hardware.info/?probe=d106f46dde) | Mar 01, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Dell          | 0DRR0P A02                  | Server      | [b72db7df7f](https://bsd-hardware.info/?probe=b72db7df7f) | Feb 25, 2021 |
| Shuttle       | FS61                        | Desktop     | [3016999a76](https://bsd-hardware.info/?probe=3016999a76) | Feb 25, 2021 |
| Unknown       | YL-SKUL6                    | Desktop     | [96d7fbef45](https://bsd-hardware.info/?probe=96d7fbef45) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| Acer          | RS780HVF                    | Desktop     | [3367ae4413](https://bsd-hardware.info/?probe=3367ae4413) | Feb 24, 2021 |
| ASUSTek       | P8B-M SeriesG               | Server      | [04c5c07d61](https://bsd-hardware.info/?probe=04c5c07d61) | Feb 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [b85d23571e](https://bsd-hardware.info/?probe=b85d23571e) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| Biostar       | A88M                        | Desktop     | [2d4a32fbc3](https://bsd-hardware.info/?probe=2d4a32fbc3) | Feb 22, 2021 |
| Biostar       | A88M                        | Desktop     | [7ff97a241a](https://bsd-hardware.info/?probe=7ff97a241a) | Feb 22, 2021 |
| MSI           | A78M-E35                    | Desktop     | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [3f0003e9a2](https://bsd-hardware.info/?probe=3f0003e9a2) | Feb 19, 2021 |
| GEO           | GeoBook3                    | Notebook    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [366f8d1eaf](https://bsd-hardware.info/?probe=366f8d1eaf) | Feb 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [d1ad5d61d2](https://bsd-hardware.info/?probe=d1ad5d61d2) | Feb 17, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| Gigabyte      | M68MT-S2                    | Desktop     | [5d94572e10](https://bsd-hardware.info/?probe=5d94572e10) | Feb 16, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [27b11c7a56](https://bsd-hardware.info/?probe=27b11c7a56) | Feb 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a3380d4b0c](https://bsd-hardware.info/?probe=a3380d4b0c) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [3c043807ba](https://bsd-hardware.info/?probe=3c043807ba) | Feb 15, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [62e8f472f6](https://bsd-hardware.info/?probe=62e8f472f6) | Feb 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [ad9283aae7](https://bsd-hardware.info/?probe=ad9283aae7) | Feb 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7313a6d6e2](https://bsd-hardware.info/?probe=7313a6d6e2) | Feb 14, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | Notebook    | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Dell          | Latitude E6420              | Notebook    | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [9bbe1119a1](https://bsd-hardware.info/?probe=9bbe1119a1) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| Shuttle       | DS10U                       | Desktop     | [aef3ca0794](https://bsd-hardware.info/?probe=aef3ca0794) | Feb 12, 2021 |
| Supermicro    | X11DPi-NT                   | Server      | [d088fbcf53](https://bsd-hardware.info/?probe=d088fbcf53) | Feb 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c1a950c4b9](https://bsd-hardware.info/?probe=c1a950c4b9) | Feb 11, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [f9f21da0eb](https://bsd-hardware.info/?probe=f9f21da0eb) | Feb 11, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [ad0f0dde9d](https://bsd-hardware.info/?probe=ad0f0dde9d) | Feb 10, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [5ab9b894a5](https://bsd-hardware.info/?probe=5ab9b894a5) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [435f081b3b](https://bsd-hardware.info/?probe=435f081b3b) | Feb 09, 2021 |
| Alienware     | M18xR1                      | Notebook    | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [7a8ab8feaf](https://bsd-hardware.info/?probe=7a8ab8feaf) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Sony          | VPCF12C5E                   | Notebook    | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [ffc0295ae1](https://bsd-hardware.info/?probe=ffc0295ae1) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [5c09abed71](https://bsd-hardware.info/?probe=5c09abed71) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [c79ea5055f](https://bsd-hardware.info/?probe=c79ea5055f) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [222778ae2b](https://bsd-hardware.info/?probe=222778ae2b) | Feb 05, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [09f8c3657f](https://bsd-hardware.info/?probe=09f8c3657f) | Feb 04, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [13fdaa7c15](https://bsd-hardware.info/?probe=13fdaa7c15) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [f827129438](https://bsd-hardware.info/?probe=f827129438) | Feb 04, 2021 |
| Unknown       | PICO PC                     | Desktop     | [de1cd4e050](https://bsd-hardware.info/?probe=de1cd4e050) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [b192745cde](https://bsd-hardware.info/?probe=b192745cde) | Feb 03, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [c11da3972d](https://bsd-hardware.info/?probe=c11da3972d) | Feb 03, 2021 |
| Protectli     | FW4B                        | Desktop     | [5334bf8761](https://bsd-hardware.info/?probe=5334bf8761) | Feb 03, 2021 |
| Deciso        | Netboard A10                | Desktop     | [a3f5b21dff](https://bsd-hardware.info/?probe=a3f5b21dff) | Feb 03, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| Supermicro    | X8SIU                       | Desktop     | [57fbc2cb9a](https://bsd-hardware.info/?probe=57fbc2cb9a) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [cc7f2d0b64](https://bsd-hardware.info/?probe=cc7f2d0b64) | Feb 02, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [6b9511bf39](https://bsd-hardware.info/?probe=6b9511bf39) | Jan 31, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Unknown       | YL-SKUL6                    | Desktop     | [9f0538d38b](https://bsd-hardware.info/?probe=9f0538d38b) | Jan 31, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [0c4e2f8a07](https://bsd-hardware.info/?probe=0c4e2f8a07) | Jan 30, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [996a6207dc](https://bsd-hardware.info/?probe=996a6207dc) | Jan 30, 2021 |
| Intel         | NUC5PGYB H78167-102         | Mini pc     | [ad190621be](https://bsd-hardware.info/?probe=ad190621be) | Jan 28, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| ASRock        | J3455M                      | Desktop     | [c90667d62c](https://bsd-hardware.info/?probe=c90667d62c) | Jan 27, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5e6fbbd1ee](https://bsd-hardware.info/?probe=5e6fbbd1ee) | Jan 27, 2021 |
| Lenovo        | Board                       | Desktop     | [da81aa7cb9](https://bsd-hardware.info/?probe=da81aa7cb9) | Jan 26, 2021 |
| AZW           | GK55                        | Desktop     | [077fedae7d](https://bsd-hardware.info/?probe=077fedae7d) | Jan 26, 2021 |
| Silver Pea... | Network Appliance Platfo... | Firewall    | [6f058f9a0c](https://bsd-hardware.info/?probe=6f058f9a0c) | Jan 25, 2021 |
| AZW           | GK55                        | Desktop     | [db3fc2c7b2](https://bsd-hardware.info/?probe=db3fc2c7b2) | Jan 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [aa5782d83e](https://bsd-hardware.info/?probe=aa5782d83e) | Jan 24, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6d11e7b348](https://bsd-hardware.info/?probe=6d11e7b348) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [aeb42f8919](https://bsd-hardware.info/?probe=aeb42f8919) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [5b3be23f50](https://bsd-hardware.info/?probe=5b3be23f50) | Jan 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [8720b818b5](https://bsd-hardware.info/?probe=8720b818b5) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7829f75120](https://bsd-hardware.info/?probe=7829f75120) | Jan 23, 2021 |
| Jetway        | 1.0                         | Desktop     | [8f47246cdf](https://bsd-hardware.info/?probe=8f47246cdf) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [f952cac718](https://bsd-hardware.info/?probe=f952cac718) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [29c88c0b95](https://bsd-hardware.info/?probe=29c88c0b95) | Jan 22, 2021 |
| Protectli     | FW4B                        | Desktop     | [ea6fcc20bc](https://bsd-hardware.info/?probe=ea6fcc20bc) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1722f1824f](https://bsd-hardware.info/?probe=1722f1824f) | Jan 22, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2e630c3c54](https://bsd-hardware.info/?probe=2e630c3c54) | Jan 22, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [6821383a38](https://bsd-hardware.info/?probe=6821383a38) | Jan 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [526fd1f7c9](https://bsd-hardware.info/?probe=526fd1f7c9) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [0fac28f2bf](https://bsd-hardware.info/?probe=0fac28f2bf) | Jan 21, 2021 |
| Shuttle       | FS67U                       | Desktop     | [8ed524df62](https://bsd-hardware.info/?probe=8ed524df62) | Jan 20, 2021 |
| Protectli     | FW4A Ver                    | Desktop     | [5725505d31](https://bsd-hardware.info/?probe=5725505d31) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [49463c91f7](https://bsd-hardware.info/?probe=49463c91f7) | Jan 19, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fcedf7a28d](https://bsd-hardware.info/?probe=fcedf7a28d) | Jan 19, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [bb4f8afc82](https://bsd-hardware.info/?probe=bb4f8afc82) | Jan 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [de391d20e5](https://bsd-hardware.info/?probe=de391d20e5) | Jan 01, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |
| Pegatron      | T12Ah                       | Notebook    | [427bb18c90](https://bsd-hardware.info/?probe=427bb18c90) | Dec 27, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [8195760dd6](https://bsd-hardware.info/?probe=8195760dd6) | Dec 23, 2020 |
| Samsung       | N140                        | Notebook    | [cab912c576](https://bsd-hardware.info/?probe=cab912c576) | Dec 21, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [20c77fd91b](https://bsd-hardware.info/?probe=20c77fd91b) | Dec 16, 2020 |
| Gigabyte      | Z97P-D3                     | Desktop     | [588af8f5b3](https://bsd-hardware.info/?probe=588af8f5b3) | Dec 16, 2020 |
| Acer          | Aspire X1440                | Desktop     | [6100b30349](https://bsd-hardware.info/?probe=6100b30349) | Dec 15, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [2b478c0d01](https://bsd-hardware.info/?probe=2b478c0d01) | Dec 08, 2020 |
| Apple         | Xserve3,1                   | Desktop     | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1076ee5826](https://bsd-hardware.info/?probe=1076ee5826) | Dec 04, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ec1363a9ea](https://bsd-hardware.info/?probe=ec1363a9ea) | Dec 04, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [f62cab95dd](https://bsd-hardware.info/?probe=f62cab95dd) | Dec 03, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [1f3fa432dc](https://bsd-hardware.info/?probe=1f3fa432dc) | Nov 21, 2020 |
| ASRock        | IMB-191                     | Desktop     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HP            | Compaq nx7400 (RU430ET#A... | Notebook    | [c9c7bae008](https://bsd-hardware.info/?probe=c9c7bae008) | Nov 01, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [e5c99b958d](https://bsd-hardware.info/?probe=e5c99b958d) | Oct 31, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [f9a374a310](https://bsd-hardware.info/?probe=f9a374a310) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Intel         | CRESCENTBAY                 | Desktop     | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | Notebook    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Gigabyte      | MZ32-AR0-00 01000100        | Server      | [93e2466fc6](https://bsd-hardware.info/?probe=93e2466fc6) | Oct 01, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [6cd0b0ed25](https://bsd-hardware.info/?probe=6cd0b0ed25) | Sep 28, 2020 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [b9b460d9e2](https://bsd-hardware.info/?probe=b9b460d9e2) | Sep 28, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [d7d299f9fc](https://bsd-hardware.info/?probe=d7d299f9fc) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec434bfdcd](https://bsd-hardware.info/?probe=ec434bfdcd) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [628b379afb](https://bsd-hardware.info/?probe=628b379afb) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [decfd42a65](https://bsd-hardware.info/?probe=decfd42a65) | Sep 13, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [9168df8552](https://bsd-hardware.info/?probe=9168df8552) | Aug 08, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Google        | Lulu                        | Notebook    | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Biostar       | B450MH                      | Desktop     | [4ad280f947](https://bsd-hardware.info/?probe=4ad280f947) | Aug 02, 2020 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [6b015a340b](https://bsd-hardware.info/?probe=6b015a340b) | Jul 31, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [cef5a64eb8](https://bsd-hardware.info/?probe=cef5a64eb8) | Jul 11, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [2394ca7e03](https://bsd-hardware.info/?probe=2394ca7e03) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [4f34d107bc](https://bsd-hardware.info/?probe=4f34d107bc) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [067478e4be](https://bsd-hardware.info/?probe=067478e4be) | Jul 03, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | Desktop     | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| HP            | 213D A01                    | Desktop     | [23f8adb299](https://bsd-hardware.info/?probe=23f8adb299) | May 25, 2020 |
| Lenovo        | ThinkPad X220 42902WU       | Notebook    | [e8a2f44b21](https://bsd-hardware.info/?probe=e8a2f44b21) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 20.7.8      | 16        | 4.36%   |
| FreeBSD 13.0         | 14        | 3.81%   |
| helloSystem 0.5.0    | 12        | 3.27%   |
| OPNsense 22.1        | 11        | 3%      |
| OPNsense 21.7.7      | 11        | 3%      |
| OPNsense 21.1.5      | 11        | 3%      |
| OPNsense 22.1.6      | 10        | 2.72%   |
| helloSystem 0.7.0    | 10        | 2.72%   |
| helloSystem 0.4.0    | 10        | 2.72%   |
| FreeBSD 14.0-CURRENT | 10        | 2.72%   |
| OPNsense 21.7.3      | 9         | 2.45%   |
| OPNsense 21.7.1      | 9         | 2.45%   |
| OPNsense 21.1.1      | 9         | 2.45%   |
| OPNsense 21.1        | 9         | 2.45%   |
| GhostBSD 20.04.02    | 9         | 2.45%   |
| OPNsense 21.1.7      | 8         | 2.18%   |
| OpenBSD 6.8          | 8         | 2.18%   |
| OPNsense 22.1.8      | 7         | 1.91%   |
| OPNsense 21.1.4      | 7         | 1.91%   |
| OPNsense 21.1.3      | 7         | 1.91%   |
| OPNsense 21.1.2      | 7         | 1.91%   |
| FreeBSD 12.2         | 7         | 1.91%   |
| OPNsense 22.1.4      | 6         | 1.63%   |
| OPNsense 21.7.8      | 6         | 1.63%   |
| FreeBSD 13.0-STABLE  | 6         | 1.63%   |
| OPNsense 22.1.3      | 5         | 1.36%   |
| OPNsense 22.1.2      | 5         | 1.36%   |
| OPNsense 21.7.2      | 5         | 1.36%   |
| OPNsense 21.1.6      | 5         | 1.36%   |
| FreeBSD 12.2-p3      | 5         | 1.36%   |
| OPNsense 22.1.9      | 4         | 1.09%   |
| OPNsense 21.7.5      | 4         | 1.09%   |
| OPNsense 21.1.8      | 4         | 1.09%   |
| OpenBSD 7.1          | 4         | 1.09%   |
| helloSystem 0.6.0    | 4         | 1.09%   |
| FreeBSD 13.0-p3      | 4         | 1.09%   |
| OPNsense 21.7.6      | 3         | 0.82%   |
| OPNsense 20.7.7      | 3         | 0.82%   |
| OPNsense 20.7        | 3         | 0.82%   |
| NomadBSD 1.4-RC1     | 3         | 0.82%   |
| NomadBSD 1.3.2       | 3         | 0.82%   |
| helloSystem 0.3.0    | 3         | 0.82%   |
| FreeBSD 13.1         | 3         | 0.82%   |
| FreeBSD 13.0-p5      | 3         | 0.82%   |
| FreeBSD 13.0-p2      | 3         | 0.82%   |
| FreeBSD 12.2-p6      | 3         | 0.82%   |
| FreeBSD 12.1-p7      | 3         | 0.82%   |
| OPNsense 22.1.5      | 2         | 0.54%   |
| OPNsense 22.1.1      | 2         | 0.54%   |
| OPNsense 21.7.4      | 2         | 0.54%   |
| OPNsense 21.7        | 2         | 0.54%   |
| OpenBSD 7.0          | 2         | 0.54%   |
| OpenBSD 6.9          | 2         | 0.54%   |
| OpenBSD 6.7          | 2         | 0.54%   |
| FreeBSD 13.0-p4      | 2         | 0.54%   |
| FreeBSD 13.0-p11     | 2         | 0.54%   |
| FreeBSD 13.0-CURRENT | 2         | 0.54%   |
| FreeBSD 12.2-p4      | 2         | 0.54%   |
| FreeBSD 12.2-p2      | 2         | 0.54%   |
| FreeBSD 12.1-p9      | 2         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 139       | 48.43%  |
| FreeBSD     | 66        | 23%     |
| helloSystem | 38        | 13.24%  |
| OpenBSD     | 18        | 6.27%   |
| GhostBSD    | 11        | 3.83%   |
| NomadBSD    | 7         | 2.44%   |
| NetBSD      | 4         | 1.39%   |
| XigmaNAS    | 1         | 0.35%   |
| pfSense     | 1         | 0.35%   |
| FuryBSD     | 1         | 0.35%   |
| DragonFly   | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 273       | 97.5%   |
| arm64 | 4         | 1.43%   |
| i386  | 2         | 0.71%   |
| riscv | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 171       | 59.17%  |
| helloDesktop     | 40        | 13.84%  |
| KDE5             | 20        | 6.92%   |
| XFCE             | 14        | 4.84%   |
| MATE             | 12        | 4.15%   |
| Openbox          | 7         | 2.42%   |
| fvwm             | 7         | 2.42%   |
| GNOME            | 5         | 1.73%   |
| i3               | 3         | 1.04%   |
| Cinnamon         | 2         | 0.69%   |
| TWM              | 1         | 0.35%   |
| PekWM            | 1         | 0.35%   |
| Metacity (Marco) | 1         | 0.35%   |
| Enlightenment    | 1         | 0.35%   |
| DWM              | 1         | 0.35%   |
| CDE              | 1         | 0.35%   |
| AwesomeWM        | 1         | 0.35%   |
| akonadi_newm     | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 173       | 61.35%  |
| X11     | 107       | 37.94%  |
| Wayland | 2         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 198       | 68.75%  |
| SLiM    | 51        | 17.71%  |
| SDDM    | 21        | 7.29%   |
| LightDM | 13        | 4.51%   |
| XDM     | 4         | 1.39%   |
| Ly      | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 178       | 60.34%  |
| en_US           | 48        | 16.27%  |
| C               | 41        | 13.9%   |
| en_GB           | 22        | 7.46%   |
| ru_RU           | 2         | 0.68%   |
| en_GB.US-ASCII  | 2         | 0.68%   |
| it_CH           | 1         | 0.34%   |
| en_GB.ISO8859-1 | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 234       | 82.11%  |
| BIOS | 51        | 17.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 158       | 55.24%  |
| Zfs     | 103       | 36.01%  |
| Ffs     | 18        | 6.29%   |
| Cd9660  | 5         | 1.75%   |
| Hammer2 | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 257       | 91.13%  |
| MBR     | 18        | 6.38%   |
| Unknown | 6         | 2.13%   |
| BSD     | 1         | 0.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 40        | 14.29%  |
| Lenovo                  | 28        | 10%     |
| Hewlett-Packard         | 26        | 9.29%   |
| ASUSTek Computer        | 20        | 7.14%   |
| Intel                   | 19        | 6.79%   |
| Gigabyte Technology     | 17        | 6.07%   |
| Unknown                 | 17        | 6.07%   |
| ASRock                  | 11        | 3.93%   |
| AMI                     | 10        | 3.57%   |
| Apple                   | 9         | 3.21%   |
| PC Engines              | 8         | 2.86%   |
| Shuttle                 | 5         | 1.79%   |
| MSI                     | 5         | 1.79%   |
| Toshiba                 | 4         | 1.43%   |
| Samsung Electronics     | 4         | 1.43%   |
| Protectli               | 4         | 1.43%   |
| Fujitsu                 | 3         | 1.07%   |
| Biostar                 | 3         | 1.07%   |
| Acer                    | 3         | 1.07%   |
| ZOTAC                   | 2         | 0.71%   |
| Yanling                 | 2         | 0.71%   |
| Supermicro              | 2         | 0.71%   |
| Raspberry Pi Foundation | 2         | 0.71%   |
| Inventec                | 2         | 0.71%   |
| HPE                     | 2         | 0.71%   |
| Winston Marriot         | 1         | 0.36%   |
| TUXEDO                  | 1         | 0.36%   |
| System76                | 1         | 0.36%   |
| Sophos                  | 1         | 0.36%   |
| Sony UK                 | 1         | 0.36%   |
| Sony                    | 1         | 0.36%   |
| Silver Peak Systems     | 1         | 0.36%   |
| Seeed Studio            | 1         | 0.36%   |
| Quanmax                 | 1         | 0.36%   |
| QOTOM                   | 1         | 0.36%   |
| Pegatron                | 1         | 0.36%   |
| Panasonic               | 1         | 0.36%   |
| PAIQ                    | 1         | 0.36%   |
| Packard Bell            | 1         | 0.36%   |
| NU941                   | 1         | 0.36%   |
| Jumper                  | 1         | 0.36%   |
| Jetway                  | 1         | 0.36%   |
| Intel CNCTION-IAF       | 1         | 0.36%   |
| HUAWEI                  | 1         | 0.36%   |
| Google                  | 1         | 0.36%   |
| GEO                     | 1         | 0.36%   |
| Fujitsu Siemens         | 1         | 0.36%   |
| Foxconn                 | 1         | 0.36%   |
| EVGA                    | 1         | 0.36%   |
| Deciso                  | 1         | 0.36%   |
| CheckPoint              | 1         | 0.36%   |
| Barracuda Networks      | 1         | 0.36%   |
| AZW                     | 1         | 0.36%   |
| ASRockRack              | 1         | 0.36%   |
| AMD                     | 1         | 0.36%   |
| Alienware               | 1         | 0.36%   |
| Acidanthera             | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Unknown                                        | 17        | 6.07%   |
| Intel Q3XXG4-P V1.0                            | 8         | 2.86%   |
| AMI Aptio CRB                                  | 8         | 2.86%   |
| PC Engines APU2                                | 5         | 1.79%   |
| ASUS All Series                                | 4         | 1.43%   |
| HP EliteBook 8570p                             | 3         | 1.07%   |
| Dell OptiPlex 7010                             | 3         | 1.07%   |
| Dell OptiPlex 3020                             | 3         | 1.07%   |
| Yanling YL-KBR6L                               | 2         | 0.71%   |
| RPi Raspberry Pi                               | 2         | 0.71%   |
| Protectli FW4B                                 | 2         | 0.71%   |
| PC Engines apu4                                | 2         | 0.71%   |
| Lenovo ThinkCentre M920s 10SJ0041UK            | 2         | 0.71%   |
| HP Z600 Workstation                            | 2         | 0.71%   |
| HP t620 PLUS Quad Core TC                      | 2         | 0.71%   |
| HP ProLiant DL360 Gen9                         | 2         | 0.71%   |
| Gigabyte B450M DS3H                            | 2         | 0.71%   |
| Dell Wyse 5070 Extended Thin Client            | 2         | 0.71%   |
| Dell PowerEdge R610                            | 2         | 0.71%   |
| Dell PowerEdge R210 II                         | 2         | 0.71%   |
| Dell PowerEdge R210                            | 2         | 0.71%   |
| Dell OptiPlex 790                              | 2         | 0.71%   |
| Dell OptiPlex 760                              | 2         | 0.71%   |
| Dell OptiPlex 390                              | 2         | 0.71%   |
| Dell Inspiron 3793                             | 2         | 0.71%   |
| ASUS ZenBook S UX391UA                         | 2         | 0.71%   |
| ASUS ROG STRIX X570-E GAMING                   | 2         | 0.71%   |
| ASRock B550 Phantom Gaming 4                   | 2         | 0.71%   |
| ZOTAC ZBOX-CI329NANO                           | 1         | 0.36%   |
| ZOTAC ZBOX-CI323NANO                           | 1         | 0.36%   |
| Winston Marriot PICO PC(R)                     | 1         | 0.36%   |
| TUXEDO Aura 15 Gen1                            | 1         | 0.36%   |
| Toshiba TECRA M11                              | 1         | 0.36%   |
| Toshiba Satellite Pro U400                     | 1         | 0.36%   |
| Toshiba Satellite L50-C                        | 1         | 0.36%   |
| Toshiba Satellite C660                         | 1         | 0.36%   |
| System76 Gazelle                               | 1         | 0.36%   |
| Supermicro X8SIU                               | 1         | 0.36%   |
| Supermicro X11DPi-N(T)                         | 1         | 0.36%   |
| Sophos SG                                      | 1         | 0.36%   |
| Sony VPCF12C5E                                 | 1         | 0.36%   |
| Sony UK Raspberry Pi 4 Model B                 | 1         | 0.36%   |
| Silver Peak Systems Network Appliance Platform | 1         | 0.36%   |
| Shuttle XH61V                                  | 1         | 0.36%   |
| Shuttle SH81R                                  | 1         | 0.36%   |
| Shuttle DS67U                                  | 1         | 0.36%   |
| Shuttle DS61                                   | 1         | 0.36%   |
| Shuttle DS10U                                  | 1         | 0.36%   |
| Seeed Studio ODYSSEY-X86J4105                  | 1         | 0.36%   |
| Samsung NC10                                   | 1         | 0.36%   |
| Samsung N140                                   | 1         | 0.36%   |
| Samsung 550P5C/550P7C                          | 1         | 0.36%   |
| Samsung 305E4A/305E5A/305E7A                   | 1         | 0.36%   |
| Quanmax spo-book TECH QUAD                     | 1         | 0.36%   |
| QOTOM Q355G4-P V1.0                            | 1         | 0.36%   |
| Protectli FW6                                  | 1         | 0.36%   |
| Protectli FW4A                                 | 1         | 0.36%   |
| Pegatron T12Ah                                 | 1         | 0.36%   |
| PC Engines APU                                 | 1         | 0.36%   |
| Panasonic CF-C1BT02EGE                         | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 17        | 6.07%   |
| Unknown                       | 17        | 6.07%   |
| Dell PowerEdge                | 14        | 5%      |
| Dell OptiPlex                 | 14        | 5%      |
| Lenovo ThinkCentre            | 8         | 2.86%   |
| Intel Q3XXG4-P                | 8         | 2.86%   |
| AMI Aptio                     | 8         | 2.86%   |
| HP ProLiant                   | 6         | 2.14%   |
| PC Engines APU2               | 5         | 1.79%   |
| Dell Latitude                 | 5         | 1.79%   |
| ASUS PRIME                    | 4         | 1.43%   |
| ASUS All                      | 4         | 1.43%   |
| Toshiba Satellite             | 3         | 1.07%   |
| HP Pavilion                   | 3         | 1.07%   |
| HP EliteBook                  | 3         | 1.07%   |
| ASUS ROG                      | 3         | 1.07%   |
| Apple MacBookPro5             | 3         | 1.07%   |
| Acer Aspire                   | 3         | 1.07%   |
| Yanling YL-KBR6L              | 2         | 0.71%   |
| RPi Raspberry                 | 2         | 0.71%   |
| Protectli FW4B                | 2         | 0.71%   |
| PC Engines apu4               | 2         | 0.71%   |
| HP Z600                       | 2         | 0.71%   |
| HP t620                       | 2         | 0.71%   |
| HP ProDesk                    | 2         | 0.71%   |
| Gigabyte B450M                | 2         | 0.71%   |
| Fujitsu ESPRIMO               | 2         | 0.71%   |
| Dell Wyse                     | 2         | 0.71%   |
| Dell Inspiron                 | 2         | 0.71%   |
| ASUS ZenBook                  | 2         | 0.71%   |
| ASUS P8Z77-V                  | 2         | 0.71%   |
| ASRock B550                   | 2         | 0.71%   |
| ZOTAC ZBOX-CI329NANO          | 1         | 0.36%   |
| ZOTAC ZBOX-CI323NANO          | 1         | 0.36%   |
| Winston Marriot PICO          | 1         | 0.36%   |
| TUXEDO Aura                   | 1         | 0.36%   |
| Toshiba TECRA                 | 1         | 0.36%   |
| System76 Gazelle              | 1         | 0.36%   |
| Supermicro X8SIU              | 1         | 0.36%   |
| Supermicro X11DPi-N(T)        | 1         | 0.36%   |
| Sophos SG                     | 1         | 0.36%   |
| Sony VPCF12C5E                | 1         | 0.36%   |
| Sony UK Raspberry             | 1         | 0.36%   |
| Silver Peak Systems Network   | 1         | 0.36%   |
| Shuttle XH61V                 | 1         | 0.36%   |
| Shuttle SH81R                 | 1         | 0.36%   |
| Shuttle DS67U                 | 1         | 0.36%   |
| Shuttle DS61                  | 1         | 0.36%   |
| Shuttle DS10U                 | 1         | 0.36%   |
| Seeed Studio ODYSSEY-X86J4105 | 1         | 0.36%   |
| Samsung NC10                  | 1         | 0.36%   |
| Samsung N140                  | 1         | 0.36%   |
| Samsung 550P5C                | 1         | 0.36%   |
| Samsung 305E4A                | 1         | 0.36%   |
| Quanmax spo-book              | 1         | 0.36%   |
| QOTOM Q355G4-P                | 1         | 0.36%   |
| Protectli FW6                 | 1         | 0.36%   |
| Protectli FW4A                | 1         | 0.36%   |
| Pegatron T12Ah                | 1         | 0.36%   |
| PC Engines APU                | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 11.43%  |
| 2018    | 31        | 11.07%  |
| 2016    | 31        | 11.07%  |
| 2014    | 26        | 9.29%   |
| 2019    | 24        | 8.57%   |
| 2013    | 22        | 7.86%   |
| 2015    | 20        | 7.14%   |
| 2021    | 17        | 6.07%   |
| 2011    | 17        | 6.07%   |
| 2010    | 15        | 5.36%   |
| 2012    | 14        | 5%      |
| 2009    | 10        | 3.57%   |
| 2017    | 9         | 3.21%   |
| Unknown | 5         | 1.79%   |
| 2008    | 4         | 1.43%   |
| 2007    | 3         | 1.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 160       | 57.14%  |
| Notebook       | 67        | 23.93%  |
| Server         | 22        | 7.86%   |
| Mini pc        | 21        | 7.5%    |
| Firewall       | 4         | 1.43%   |
| System on chip | 3         | 1.07%   |
| All in one     | 2         | 0.71%   |
| Convertible    | 1         | 0.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 269       | 96.07%  |
| Yes  | 11        | 3.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 119       | 42.2%   |
| 4.01-8.0        | 59        | 20.92%  |
| 16.01-24.0      | 57        | 20.21%  |
| 32.01-64.0      | 17        | 6.03%   |
| 2.01-3.0        | 11        | 3.9%    |
| 64.01-256.0     | 9         | 3.19%   |
| 3.01-4.0        | 3         | 1.06%   |
| 24.01-32.0      | 3         | 1.06%   |
| 0.51-1.0        | 2         | 0.71%   |
| More than 256.0 | 1         | 0.35%   |
| Unknown         | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 164       | 55.41%  |
| 0.51-1.0    | 76        | 25.68%  |
| 1.01-2.0    | 21        | 7.09%   |
| 2.01-3.0    | 11        | 3.72%   |
| 3.01-4.0    | 7         | 2.36%   |
| 4.01-8.0    | 5         | 1.69%   |
| Unknown     | 4         | 1.35%   |
| 24.01-32.0  | 2         | 0.68%   |
| 8.01-16.0   | 2         | 0.68%   |
| 32.01-64.0  | 1         | 0.34%   |
| 64.01-256.0 | 1         | 0.34%   |
| 16.01-24.0  | 1         | 0.34%   |
| 0           | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 196       | 66.44%  |
| 2      | 44        | 14.92%  |
| 0      | 21        | 7.12%   |
| 3      | 12        | 4.07%   |
| 5      | 7         | 2.37%   |
| 4      | 7         | 2.37%   |
| 8      | 3         | 1.02%   |
| 6      | 2         | 0.68%   |
| 17     | 1         | 0.34%   |
| 14     | 1         | 0.34%   |
| 7      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 75.35%  |
| Yes       | 70        | 24.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 93.57%  |
| No        | 18        | 6.43%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 165       | 58.3%   |
| Yes       | 118       | 41.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 213       | 75%     |
| Yes       | 71        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 280       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 32        | 10.06%  |
| Glasgow             | 8         | 2.52%   |
| Brighton            | 7         | 2.2%    |
| Watford             | 5         | 1.57%   |
| Swindon             | 5         | 1.57%   |
| Newcastle upon Tyne | 5         | 1.57%   |
| Kensington          | 5         | 1.57%   |
| Stourbridge         | 4         | 1.26%   |
| Sheffield           | 4         | 1.26%   |
| Poplar              | 4         | 1.26%   |
| Milton Keynes       | 4         | 1.26%   |
| Islington           | 4         | 1.26%   |
| Hull                | 4         | 1.26%   |
| Bristol             | 4         | 1.26%   |
| York                | 3         | 0.94%   |
| Worthing            | 3         | 0.94%   |
| Wolverhampton       | 3         | 0.94%   |
| Wittersham          | 3         | 0.94%   |
| Scunthorpe          | 3         | 0.94%   |
| Ruthin              | 3         | 0.94%   |
| Malton              | 3         | 0.94%   |
| Liverpool           | 3         | 0.94%   |
| Leicester           | 3         | 0.94%   |
| Leatherhead         | 3         | 0.94%   |
| Greenwich           | 3         | 0.94%   |
| Egham               | 3         | 0.94%   |
| Cambridge           | 3         | 0.94%   |
| Andover             | 3         | 0.94%   |
| Telford             | 2         | 0.63%   |
| Stoke-on-Trent      | 2         | 0.63%   |
| Stoke Newington     | 2         | 0.63%   |
| Slough              | 2         | 0.63%   |
| Rotherham           | 2         | 0.63%   |
| Reigate             | 2         | 0.63%   |
| Reading             | 2         | 0.63%   |
| Oldham              | 2         | 0.63%   |
| Notting Hill Gate   | 2         | 0.63%   |
| Mansfield           | 2         | 0.63%   |
| Leeds               | 2         | 0.63%   |
| Kidderminster       | 2         | 0.63%   |
| Hemel Hempstead     | 2         | 0.63%   |
| Harrow              | 2         | 0.63%   |
| Gloucester          | 2         | 0.63%   |
| Finchley            | 2         | 0.63%   |
| Dundee              | 2         | 0.63%   |
| Dulwich             | 2         | 0.63%   |
| Devizes             | 2         | 0.63%   |
| Coventry            | 2         | 0.63%   |
| Castleford          | 2         | 0.63%   |
| Camden              | 2         | 0.63%   |
| Birmingham          | 2         | 0.63%   |
| Banbury             | 2         | 0.63%   |
| Aberdeen            | 2         | 0.63%   |
| Yeovil              | 1         | 0.31%   |
| Woking              | 1         | 0.31%   |
| Windsor             | 1         | 0.31%   |
| Weymouth            | 1         | 0.31%   |
| West Hanningfield   | 1         | 0.31%   |
| Weedon Bec          | 1         | 0.31%   |
| Ware                | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 56        | 104    | 16.92%  |
| WDC                 | 41        | 63     | 12.39%  |
| Seagate             | 34        | 89     | 10.27%  |
| Kingston            | 25        | 39     | 7.55%   |
| Crucial             | 24        | 35     | 7.25%   |
| Toshiba             | 18        | 54     | 5.44%   |
| SanDisk             | 17        | 21     | 5.14%   |
| Intel               | 11        | 14     | 3.32%   |
| Hitachi             | 9         | 12     | 2.72%   |
| Phison              | 8         | 12     | 2.42%   |
| Hoodisk             | 8         | 12     | 2.42%   |
| HGST                | 8         | 26     | 2.42%   |
| Transcend           | 6         | 8      | 1.81%   |
| SK hynix            | 5         | 7      | 1.51%   |
| LITEONIT            | 5         | 6      | 1.51%   |
| Hewlett-Packard     | 5         | 14     | 1.51%   |
| Micron Technology   | 4         | 4      | 1.21%   |
| Apacer              | 4         | 5      | 1.21%   |
| A-DATA Technology   | 4         | 6      | 1.21%   |
| PNY                 | 3         | 11     | 0.91%   |
| OCZ                 | 3         | 4      | 0.91%   |
| Corsair             | 3         | 3      | 0.91%   |
| Apple               | 3         | 4      | 0.91%   |
| Patriot             | 2         | 5      | 0.6%    |
| OPENBSD             | 2         | 2      | 0.6%    |
| NVMe                | 2         | 2      | 0.6%    |
| Netac               | 2         | 3      | 0.6%    |
| FORESEE             | 2         | 2      | 0.6%    |
| Zheino              | 1         | 1      | 0.3%    |
| XUM                 | 1         | 1      | 0.3%    |
| TCSUNBOW            | 1         | 2      | 0.3%    |
| SPCC                | 1         | 1      | 0.3%    |
| Solid State Storage | 1         | 1      | 0.3%    |
| OWC                 | 1         | 1      | 0.3%    |
| MicroDream          | 1         | 1      | 0.3%    |
| Marvell             | 1         | 1      | 0.3%    |
| LITEON              | 1         | 1      | 0.3%    |
| Lexar               | 1         | 1      | 0.3%    |
| Kingchuxing         | 1         | 1      | 0.3%    |
| Intenso             | 1         | 1      | 0.3%    |
| Integral            | 1         | 3      | 0.3%    |
| Gigabyte Technology | 1         | 2      | 0.3%    |
| Fujitsu             | 1         | 6      | 0.3%    |
| Dell                | 1         | 2      | 0.3%    |
| China               | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 5         | 1.39%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.39%   |
| Kingston SUV500MS120G 120GB          | 5         | 1.39%   |
| Kingston SA400S37240G 240GB          | 5         | 1.39%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 1.39%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.11%   |
| Hoodisk SSD 64GB                     | 4         | 1.11%   |
| HGST HTS725050A7E630 500GB           | 4         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 0.83%   |
| Seagate ST3500418AS 500GB            | 3         | 0.83%   |
| Samsung HM251JX 250GB                | 3         | 0.83%   |
| Phison Sabrent 2TB                   | 3         | 0.83%   |
| HP RAID 1(1+0) 2TB                   | 3         | 0.83%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.83%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.83%   |
| WDC WD1600BEVT-80A23T0 160GB         | 2         | 0.56%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 0.56%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2         | 0.56%   |
| Toshiba HDWE140 4TB                  | 2         | 0.56%   |
| Seagate ST8000VN0022-2EL112 8TB      | 2         | 0.56%   |
| Seagate ST8000AS0002-1NA17Z 8TB      | 2         | 0.56%   |
| Seagate ST4000NE001-2MA101 4TB       | 2         | 0.56%   |
| Seagate ST3500312CS 500GB            | 2         | 0.56%   |
| Seagate ST3160318AS 160GB            | 2         | 0.56%   |
| Seagate ST3160310CS 160GB            | 2         | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.56%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.56%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.56%   |
| SanDisk SDCFHS-016G                  | 2         | 0.56%   |
| Samsung SSD PM810 2.5-inch 7mm 256GB | 2         | 0.56%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.56%   |
| Samsung SSD 850 PRO 256GB            | 2         | 0.56%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.56%   |
| Samsung SSD 750 EVO 250GB            | 2         | 0.56%   |
| Samsung MZVLW512HMJP-00000 512GB     | 2         | 0.56%   |
| PNY CS900 240GB SSD                  | 2         | 0.56%   |
| Phison SATA SSD 16GB                 | 2         | 0.56%   |
| Patriot Burst 240GB                  | 2         | 0.56%   |
| OPENBSD SR RAID 1 752GB              | 2         | 0.56%   |
| Netac SSD 120GB                      | 2         | 0.56%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB | 2         | 0.56%   |
| Kingston SUV500MS240G 240GB          | 2         | 0.56%   |
| Kingston SMS200S330G 32GB            | 2         | 0.56%   |
| Intel SSDSA2CT040G3 40GB             | 2         | 0.56%   |
| Hoodisk SSD 32GB                     | 2         | 0.56%   |
| Hoodisk SSD 128GB                    | 2         | 0.56%   |
| Crucial CT525MX300SSD1 528GB         | 2         | 0.56%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.56%   |
| Crucial CT2000MX500SSD1 2TB          | 2         | 0.56%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.56%   |
| Zheino CHN HFmSATA01M 128 128GB      | 1         | 0.28%   |
| XUM HX256GSSDSATA3 256GB             | 1         | 0.28%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.28%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.28%   |
| WDC WDS250G2B0B-00YS70 250GB         | 1         | 0.28%   |
| WDC WDS250G2B0A-00SM50 250GB         | 1         | 0.28%   |
| WDC WDS250G2B0A 250GB                | 1         | 0.28%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.28%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 89     | 30.36%  |
| WDC                 | 31        | 46     | 27.68%  |
| Toshiba             | 13        | 43     | 11.61%  |
| Hitachi             | 9         | 12     | 8.04%   |
| HGST                | 8         | 26     | 7.14%   |
| Samsung Electronics | 6         | 6      | 5.36%   |
| Hewlett-Packard     | 5         | 14     | 4.46%   |
| OPENBSD             | 2         | 2      | 1.79%   |
| NVMe                | 1         | 1      | 0.89%   |
| Fujitsu             | 1         | 6      | 0.89%   |
| Dell                | 1         | 2      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 77     | 20.41%  |
| Kingston            | 25        | 39     | 12.76%  |
| Crucial             | 23        | 34     | 11.73%  |
| SanDisk             | 17        | 21     | 8.67%   |
| Intel               | 10        | 12     | 5.1%    |
| WDC                 | 8         | 12     | 4.08%   |
| Hoodisk             | 8         | 12     | 4.08%   |
| Transcend           | 6         | 8      | 3.06%   |
| Phison              | 5         | 6      | 2.55%   |
| LITEONIT            | 5         | 6      | 2.55%   |
| Micron Technology   | 4         | 4      | 2.04%   |
| Apacer              | 4         | 5      | 2.04%   |
| A-DATA Technology   | 4         | 6      | 2.04%   |
| Toshiba             | 3         | 8      | 1.53%   |
| PNY                 | 3         | 9      | 1.53%   |
| OCZ                 | 3         | 4      | 1.53%   |
| Corsair             | 3         | 3      | 1.53%   |
| SK hynix            | 2         | 2      | 1.02%   |
| Patriot             | 2         | 5      | 1.02%   |
| Netac               | 2         | 3      | 1.02%   |
| FORESEE             | 2         | 2      | 1.02%   |
| Apple               | 2         | 3      | 1.02%   |
| Zheino              | 1         | 1      | 0.51%   |
| XUM                 | 1         | 1      | 0.51%   |
| TCSUNBOW            | 1         | 2      | 0.51%   |
| SPCC                | 1         | 1      | 0.51%   |
| OWC                 | 1         | 1      | 0.51%   |
| NVMe                | 1         | 1      | 0.51%   |
| MicroDream          | 1         | 1      | 0.51%   |
| Marvell             | 1         | 1      | 0.51%   |
| LITEON              | 1         | 1      | 0.51%   |
| Lexar               | 1         | 1      | 0.51%   |
| Kingchuxing         | 1         | 1      | 0.51%   |
| Intenso             | 1         | 1      | 0.51%   |
| Integral            | 1         | 3      | 0.51%   |
| Gigabyte Technology | 1         | 2      | 0.51%   |
| China               | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 178       | 300    | 60.14%  |
| HDD  | 91        | 248    | 30.74%  |
| NVMe | 27        | 46     | 9.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 244       | 548    | 90.04%  |
| NVMe | 27        | 46     | 9.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 215       | 388    | 76.79%  |
| 0.51-1.0   | 30        | 50     | 10.71%  |
| 1.01-2.0   | 17        | 31     | 6.07%   |
| 3.01-4.0   | 9         | 37     | 3.21%   |
| 4.01-10.0  | 8         | 41     | 2.86%   |
| 2.01-3.0   | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 38.59%  |
| 1-20           | 46        | 15.44%  |
| 251-500        | 44        | 14.77%  |
| 51-100         | 31        | 10.4%   |
| 21-50          | 30        | 10.07%  |
| 501-1000       | 18        | 6.04%   |
| 1001-2000      | 7         | 2.35%   |
| Unknown        | 4         | 1.34%   |
| More than 3000 | 2         | 0.67%   |
| 2001-3000      | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 250       | 85.91%  |
| 21-50          | 20        | 6.87%   |
| 51-100         | 7         | 2.41%   |
| 101-250        | 6         | 2.06%   |
| Unknown        | 4         | 1.37%   |
| 251-500        | 2         | 0.69%   |
| More than 3000 | 1         | 0.34%   |
| 2001-3000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 12     | 7.69%   |
| Seagate ST3500418AS 500GB                        | 2         | 3      | 3.85%   |
| Seagate ST3160310CS 160GB                        | 2         | 2      | 3.85%   |
| SanDisk SSD PLUS 480GB                           | 2         | 2      | 3.85%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 2         | 3      | 3.85%   |
| Crucial CT525MX300SSD1 528GB                     | 2         | 3      | 3.85%   |
| WDC WD5000AAKX-221CA1 500GB                      | 1         | 1      | 1.92%   |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1         | 1      | 1.92%   |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1         | 4      | 1.92%   |
| WDC WD3200BEVT-22A23T0 320GB                     | 1         | 3      | 1.92%   |
| WDC WD3200AAJS-22B4A0 320GB                      | 1         | 1      | 1.92%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 1.92%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 1.92%   |
| WDC WD10JMVW-11AJGS0 1TB                         | 1         | 1      | 1.92%   |
| Transcend TS256GSSD320 256GB                     | 1         | 1      | 1.92%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.92%   |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 1.92%   |
| Toshiba HDWE140 4TB                              | 1         | 8      | 1.92%   |
| Toshiba DT01ACA200 2TB                           | 1         | 1      | 1.92%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 1.92%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.92%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 1.92%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.92%   |
| SanDisk SSD P4 16GB                              | 1         | 1      | 1.92%   |
| SanDisk SDCFHS-016G                              | 1         | 1      | 1.92%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1         | 1      | 1.92%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 1.92%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.92%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 1.92%   |
| Marvell SATAIII 16GB                             | 1         | 1      | 1.92%   |
| Kingston SV300S37A120G 120GB                     | 1         | 2      | 1.92%   |
| Kingston SV200S3128G 128GB                       | 1         | 1      | 1.92%   |
| Kingchuxing SSD 60GB                             | 1         | 1      | 1.92%   |
| Intel SSDSC2BB120G4 120GB                        | 1         | 2      | 1.92%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 1.92%   |
| HGST HUS726040ALE610 4TB                         | 1         | 1      | 1.92%   |
| HGST HTS721010A9E630 1TB                         | 1         | 10     | 1.92%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 1.92%   |
| Crucial CT1050MX300SSD4 1TB                      | 1         | 2      | 1.92%   |
| Apple HDD HTS547550A9E384 500GB                  | 1         | 1      | 1.92%   |
| A-DATA Technology SU630 240GB                    | 1         | 2      | 1.92%   |
| A-DATA Technology SP550 240GB                    | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 13     | 16%     |
| Seagate             | 7         | 8      | 14%     |
| HGST                | 6         | 24     | 12%     |
| Samsung Electronics | 5         | 6      | 10%     |
| Toshiba             | 4         | 12     | 8%      |
| SanDisk             | 4         | 4      | 8%      |
| Hitachi             | 3         | 3      | 6%      |
| Crucial             | 3         | 5      | 6%      |
| Kingston            | 2         | 3      | 4%      |
| A-DATA Technology   | 2         | 3      | 4%      |
| Transcend           | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| Marvell             | 1         | 1      | 2%      |
| Kingchuxing         | 1         | 1      | 2%      |
| Intel               | 1         | 2      | 2%      |
| Apple               | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 13     | 25.81%  |
| Seagate             | 7         | 8      | 22.58%  |
| HGST                | 6         | 24     | 19.35%  |
| Toshiba             | 4         | 12     | 12.9%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Apple               | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 63     | 61.22%  |
| SSD  | 19        | 25     | 38.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST4000NM0025 4TB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 225       | 475    | 78.4%   |
| Malfunc  | 46        | 88     | 16.03%  |
| Detected | 15        | 29     | 5.23%   |
| Failed   | 1         | 2      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 207       | 61.98%  |
| AMD                            | 52        | 15.57%  |
| Samsung Electronics            | 16        | 4.79%   |
| Broadcom / LSI                 | 11        | 3.29%   |
| ASMedia Technology             | 8         | 2.4%    |
| Marvell Technology Group       | 7         | 2.1%    |
| SanDisk                        | 6         | 1.8%    |
| Nvidia                         | 6         | 1.8%    |
| Phison Electronics             | 4         | 1.2%    |
| Hewlett-Packard                | 4         | 1.2%    |
| SK hynix                       | 3         | 0.9%    |
| Toshiba                        | 2         | 0.6%    |
| Adaptec                        | 2         | 0.6%    |
| VIA Technologies               | 1         | 0.3%    |
| Solid State Storage Technology | 1         | 0.3%    |
| Silicon Motion                 | 1         | 0.3%    |
| Silicon Image                  | 1         | 0.3%    |
| Micron/Crucial Technology      | 1         | 0.3%    |
| Kingston Technology Company    | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35        | 9.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 19        | 5.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 4.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13        | 3.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 10        | 2.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 2.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 2.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.34%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 1.34%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.08%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.81%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.81%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3         | 0.81%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.81%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.81%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.81%   |
| Samsung SM951 AHCI                                                                      | 2         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.54%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 2         | 0.54%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 0.54%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.54%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.54%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                        | 2         | 0.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.54%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.54%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2         | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 2         | 0.54%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2         | 0.54%   |
| HP Smart Array G6 controllers                                                           | 2         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.54%   |
| AMD FCH IDE Controller                                                                  | 2         | 0.54%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 2         | 0.54%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.27%   |
| Toshiba XG4 NVMe SSD Controller                                                         | 1         | 0.27%   |
| Toshiba BG3 NVMe SSD Controller                                                         | 1         | 0.27%   |
| SK hynix hynix unknown                                                                  | 1         | 0.27%   |
| SK hynix BC511                                                                          | 1         | 0.27%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 232       | 71.83%  |
| IDE  | 33        | 10.22%  |
| NVMe | 31        | 9.6%    |
| RAID | 20        | 6.19%   |
| SCSI | 4         | 1.24%   |
| SAS  | 3         | 0.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 220       | 78.57%  |
| AMD     | 54        | 19.29%  |
| ARM     | 3         | 1.07%   |
| Unknown | 2         | 0.71%   |
| 11th    | 1         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz           | 9         | 3.18%   |
| AMD GX-412TC SOC                            | 7         | 2.47%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 4         | 1.41%   |
| Intel Celeron CPU N3150 @ 1.60GHz           | 4         | 1.41%   |
| Intel Atom CPU E3845 @ 1.91GHz              | 4         | 1.41%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 3         | 1.06%   |
| Intel CPU Version                           | 3         | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.06%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 1.06%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3         | 1.06%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 3         | 1.06%   |
| Intel Celeron CPU 3865U @ 1.80GHz           | 3         | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3         | 1.06%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 3         | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 1.06%   |
| Intel Xeon CPU X3450 @ 2.67GHz              | 2         | 0.71%   |
| Intel Xeon CPU E5530 @ 2.40GHz              | 2         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 2         | 0.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.71%   |
| Intel Core i7-2600 CPU @ 3.40GH             | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.71%   |
| Intel Core i5-9500 CPU @ 3.00GHz            | 2         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.71%   |
| Intel Core i5-4590S CPU @ 3.00GHz           | 2         | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 0.71%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 0.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 2         | 0.71%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 2         | 0.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.71%   |
| Intel Core i3-2100 CPU @ 3.10GH             | 2         | 0.71%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.71%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 2         | 0.71%   |
| Intel Core 2 Duo                            | 2         | 0.71%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 0.71%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 2         | 0.71%   |
| Intel Celeron CPU N2930 @ 1.83GHz           | 2         | 0.71%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2         | 0.71%   |
| Intel Atom CPU C2558 @ 2.40GHz              | 2         | 0.71%   |
| ARM Cortex-A72 r0p3                         | 2         | 0.71%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 0.71%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 0.71%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.71%   |
| AMD GX-420CA SOC with Radeon HD Graphics    | 2         | 0.71%   |
| AMD GX-416RA SOC                            | 2         | 0.71%   |
|                                             | 2         | 0.71%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz        | 1         | 0.35%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz        | 1         | 0.35%   |
| Intel Xeon E-2224 CPU @ 3.40GHz             | 1         | 0.35%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1         | 0.35%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 1         | 0.35%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 54        | 19.15%  |
| Intel Celeron           | 39        | 13.83%  |
| Intel Core i7           | 36        | 12.77%  |
| Intel Xeon              | 27        | 9.57%   |
| Intel Core i3           | 22        | 7.8%    |
| Intel Core 2 Duo        | 12        | 4.26%   |
| AMD GX                  | 12        | 4.26%   |
| Intel Atom              | 10        | 3.55%   |
| AMD Ryzen 5             | 10        | 3.55%   |
| Other                   | 8         | 2.84%   |
| Intel Pentium           | 6         | 2.13%   |
| AMD Ryzen 7             | 5         | 1.77%   |
| Intel Pentium Silver    | 3         | 1.06%   |
| ARM Cortex              | 3         | 1.06%   |
| AMD Ryzen 3             | 3         | 1.06%   |
| AMD G                   | 3         | 1.06%   |
| AMD FX                  | 3         | 1.06%   |
| AMD A6                  | 3         | 1.06%   |
| Intel Xeon Silver       | 2         | 0.71%   |
| Intel Core i9           | 2         | 0.71%   |
| Intel Core 2 Quad       | 2         | 0.71%   |
| AMD Ryzen 9             | 2         | 0.71%   |
| AMD A4                  | 2         | 0.71%   |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel 686-class         | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD Phenom II X6        | 1         | 0.35%   |
| AMD Phenom              | 1         | 0.35%   |
| AMD Opteron             | 1         | 0.35%   |
| AMD EPYC                | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |
| AMD Athlon              | 1         | 0.35%   |
| AMD A8                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 120       | 42.4%   |
| 2       | 99        | 34.98%  |
| Unknown | 17        | 6.01%   |
| 12      | 12        | 4.24%   |
| 6       | 10        | 3.53%   |
| 8       | 8         | 2.83%   |
| 16      | 7         | 2.47%   |
| 24      | 4         | 1.41%   |
| 1       | 3         | 1.06%   |
| 10      | 2         | 0.71%   |
| 128     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 262       | 93.57%  |
| 2       | 11        | 3.93%   |
| Unknown | 7         | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 146       | 51.59%  |
| 2       | 120       | 42.4%   |
| Unknown | 17        | 6.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 35        | 12.5%   |
| Silvermont    | 32        | 11.43%  |
| SandyBridge   | 24        | 8.57%   |
| KabyLake      | 24        | 8.57%   |
| IvyBridge     | 21        | 7.5%    |
| Penryn        | 16        | 5.71%   |
| Skylake       | 13        | 4.64%   |
| Zen 2         | 11        | 3.93%   |
| Westmere      | 10        | 3.57%   |
| Nehalem       | 9         | 3.21%   |
| Goldmont plus | 9         | 3.21%   |
| Broadwell     | 9         | 3.21%   |
| Zen 3         | 7         | 2.5%    |
| Puma          | 7         | 2.5%    |
| Jaguar        | 7         | 2.5%    |
| Unknown       | 7         | 2.5%    |
| Piledriver    | 5         | 1.79%   |
| Goldmont      | 5         | 1.79%   |
| Bonnell       | 4         | 1.43%   |
| Bobcat        | 4         | 1.43%   |
| Zen           | 3         | 1.07%   |
| Core          | 3         | 1.07%   |
| Zen+          | 2         | 0.71%   |
| K10           | 2         | 0.71%   |
| IceLake       | 2         | 0.71%   |
| Excavator     | 2         | 0.71%   |
| CometLake     | 2         | 0.71%   |
| TigerLake     | 1         | 0.36%   |
| Steamroller   | 1         | 0.36%   |
| K8 Hammer     | 1         | 0.36%   |
| K10 Llano     | 1         | 0.36%   |
| Bulldozer     | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 171       | 62.18%  |
| AMD                        | 45        | 16.36%  |
| Nvidia                     | 36        | 13.09%  |
| Matrox Electronics Systems | 18        | 6.55%   |
| ASPEED Technology          | 5         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 6.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 6.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 4.23%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10        | 3.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.17%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.76%   |
| Intel HD Graphics 620                                                                    | 5         | 1.76%   |
| Intel HD Graphics 500                                                                    | 5         | 1.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.76%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.41%   |
| Intel HD Graphics 6000                                                                   | 4         | 1.41%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.41%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.06%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.06%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 1.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 1.06%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.06%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 1.06%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.06%   |
| AMD Cezanne                                                                              | 3         | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.7%    |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.7%    |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.7%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.7%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.7%    |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.7%    |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 2         | 0.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.7%    |
| Intel HD Graphics 530                                                                    | 2         | 0.7%    |
| Intel HD Graphics 510                                                                    | 2         | 0.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.7%    |
| AMD Renoir                                                                               | 2         | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.7%    |
| AMD Kabini [Radeon HD 8400E]                                                             | 2         | 0.7%    |
| AMD ES1000                                                                               | 2         | 0.7%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1         | 0.35%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 1         | 0.35%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.35%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.35%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.35%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 53.9%   |
| 1 x AMD        | 40        | 14.18%  |
| 1 x Nvidia     | 29        | 10.28%  |
| 1 x Matrox     | 18        | 6.38%   |
| Other          | 17        | 6.03%   |
| 2 x Intel      | 10        | 3.55%   |
| Intel + Nvidia | 5         | 1.77%   |
| 1 x ASPEED     | 5         | 1.77%   |
| Intel + AMD    | 4         | 1.42%   |
| 2 x Nvidia     | 2         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 242       | 85.82%  |
| Unknown     | 25        | 8.87%   |
| Proprietary | 15        | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 254       | 89.75%  |
| 1.01-2.0   | 8         | 2.83%   |
| 0.51-1.0   | 8         | 2.83%   |
| 3.01-4.0   | 5         | 1.77%   |
| 7.01-8.0   | 4         | 1.41%   |
| 0.01-0.5   | 2         | 0.71%   |
| 5.01-6.0   | 1         | 0.35%   |
| 8.01-16.0  | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 12.77%  |
| Samsung Electronics     | 10        | 10.64%  |
| LG Display              | 10        | 10.64%  |
| Dell                    | 8         | 8.51%   |
| Hewlett-Packard         | 6         | 6.38%   |
| Lenovo                  | 5         | 5.32%   |
| Chimei Innolux          | 5         | 5.32%   |
| Philips                 | 4         | 4.26%   |
| BenQ                    | 4         | 4.26%   |
| AOC                     | 4         | 4.26%   |
| Pixio                   | 2         | 2.13%   |
| LG Philips              | 2         | 2.13%   |
| Iiyama                  | 2         | 2.13%   |
| HannStar                | 2         | 2.13%   |
| BOE                     | 2         | 2.13%   |
| Apple                   | 2         | 2.13%   |
| Acer                    | 2         | 2.13%   |
| Vestel Elektronik       | 1         | 1.06%   |
| Sony                    | 1         | 1.06%   |
| Sharp                   | 1         | 1.06%   |
| SDC                     | 1         | 1.06%   |
| RS                      | 1         | 1.06%   |
| PANDA                   | 1         | 1.06%   |
| OEM                     | 1         | 1.06%   |
| InnoLux Display         | 1         | 1.06%   |
| Goldstar                | 1         | 1.06%   |
| CPT                     | 1         | 1.06%   |
| Chi Mei Optoelectronics | 1         | 1.06%   |
| AVX                     | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch             | 3         | 3.03%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 3.03%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 3.03%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch           | 2         | 2.02%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 2.02%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 1.01%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 1.01%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 1         | 1.01%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 1.01%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch     | 1         | 1.01%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch  | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 1         | 1.01%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 1.01%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                       | 1         | 1.01%   |
| Pixio PX7 Prime HYC2700 2560x1440 600x340mm 27.2-inch                 | 1         | 1.01%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                     | 1         | 1.01%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 1.01%   |
| Philips LCD Monitor 271P4                                             | 1         | 1.01%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 1.01%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 1.01%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.01%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 1.01%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.01%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch               | 1         | 1.01%   |
| Lenovo LCD Monitor LEN0990 1440x900 410x260mm 19.1-inch               | 1         | 1.01%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 220x120mm 9.9-inch       | 1         | 1.01%   |
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                 | 1         | 1.01%   |
| Iiyama PL2283H IVM562E 1920x1080 500x290mm 22.8-inch                  | 1         | 1.01%   |
| Iiyama PL2273HD IVM561A 1920x1080 480x270mm 21.7-inch                 | 1         | 1.01%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch            | 1         | 1.01%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                          | 1         | 1.01%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch          | 1         | 1.01%   |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch           | 1         | 1.01%   |
| HannStar LCD Monitor HSD1CF3 1920x1200 590x370mm 27.4-inch            | 1         | 1.01%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.01%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 1         | 1.01%   |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                   | 1         | 1.01%   |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                     | 1         | 1.01%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 1         | 1.01%   |
| Dell LCD Monitor S2740L 1920x1080                                     | 1         | 1.01%   |
| Dell LCD Monitor P2214H 1920x1080                                     | 1         | 1.01%   |
| Dell LCD Monitor DELD110 2560x1440 700x400mm 31.7-inch                | 1         | 1.01%   |
| Dell LCD Monitor 1908FP 3200x1080                                     | 1         | 1.01%   |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                     | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 31.58%  |
| 1366x768 (WXGA)    | 15        | 15.79%  |
| 1600x900 (HD+)     | 7         | 7.37%   |
| 1280x800 (WXGA)    | 7         | 7.37%   |
| 1920x1200 (WUXGA)  | 5         | 5.26%   |
| 1680x1050 (WSXGA+) | 4         | 4.21%   |
| 3840x2160 (4K)     | 3         | 3.16%   |
| 2560x1440 (QHD)    | 3         | 3.16%   |
| 1440x900 (WXGA+)   | 3         | 3.16%   |
| 1280x1024 (SXGA)   | 3         | 3.16%   |
| 1024x600           | 3         | 3.16%   |
| Unknown            | 3         | 3.16%   |
| 1920x540           | 2         | 2.11%   |
| 5760x1200          | 1         | 1.05%   |
| 3840x1080          | 1         | 1.05%   |
| 3520x1080          | 1         | 1.05%   |
| 3440x1440          | 1         | 1.05%   |
| 3200x1800 (QHD+)   | 1         | 1.05%   |
| 3200x1080          | 1         | 1.05%   |
| 2880x1800          | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 19.15%  |
| 13      | 15        | 15.96%  |
| 27      | 8         | 8.51%   |
| 19      | 7         | 7.45%   |
| 12      | 6         | 6.38%   |
| Unknown | 6         | 6.38%   |
| 24      | 5         | 5.32%   |
| 23      | 5         | 5.32%   |
| 22      | 4         | 4.26%   |
| 21      | 4         | 4.26%   |
| 17      | 3         | 3.19%   |
| 25      | 2         | 2.13%   |
| 10      | 2         | 2.13%   |
| 49      | 1         | 1.06%   |
| 42      | 1         | 1.06%   |
| 39      | 1         | 1.06%   |
| 34      | 1         | 1.06%   |
| 31      | 1         | 1.06%   |
| 18      | 1         | 1.06%   |
| 14      | 1         | 1.06%   |
| 11      | 1         | 1.06%   |
| 9       | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 28.57%  |
| 501-600     | 18        | 19.78%  |
| 201-300     | 18        | 19.78%  |
| 401-500     | 10        | 10.99%  |
| 351-400     | 7         | 7.69%   |
| Unknown     | 6         | 6.59%   |
| 601-700     | 2         | 2.2%    |
| 801-900     | 1         | 1.1%    |
| 701-800     | 1         | 1.1%    |
| 1001-1500   | 1         | 1.1%    |
| 901-1000    | 1         | 1.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 55        | 63.22%  |
| 16/10   | 18        | 20.69%  |
| Unknown | 5         | 5.75%   |
| 5/4     | 4         | 4.6%    |
| 32/9    | 2         | 2.3%    |
| 3/2     | 2         | 2.3%    |
| 21/9    | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 14        | 15.38%  |
| 81-90          | 11        | 12.09%  |
| 101-110        | 9         | 9.89%   |
| 91-100         | 9         | 9.89%   |
| 301-350        | 8         | 8.79%   |
| 151-200        | 7         | 7.69%   |
| 61-70          | 6         | 6.59%   |
| Unknown        | 6         | 6.59%   |
| 71-80          | 5         | 5.49%   |
| 41-50          | 3         | 3.3%    |
| 251-300        | 3         | 3.3%    |
| 121-130        | 3         | 3.3%    |
| 501-1000       | 3         | 3.3%    |
| 351-500        | 2         | 2.2%    |
| 51-60          | 1         | 1.1%    |
| 141-150        | 1         | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 32        | 35.16%  |
| 101-120       | 26        | 28.57%  |
| 121-160       | 19        | 20.88%  |
| 161-240       | 7         | 7.69%   |
| Unknown       | 6         | 6.59%   |
| More than 240 | 1         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 192       | 67.84%  |
| 1     | 81        | 28.62%  |
| 2     | 9         | 3.18%   |
| 3     | 1         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 188       | 49.6%   |
| Realtek Semiconductor             | 97        | 25.59%  |
| Broadcom                          | 36        | 9.5%    |
| Qualcomm Atheros                  | 24        | 6.33%   |
| Nvidia                            | 5         | 1.32%   |
| Ralink Technology                 | 4         | 1.06%   |
| Marvell Technology Group          | 4         | 1.06%   |
| Hewlett-Packard                   | 3         | 0.79%   |
| Ralink                            | 2         | 0.53%   |
| IMC Networks                      | 2         | 0.53%   |
| Ericsson Business Mobile Networks | 2         | 0.53%   |
| D-Link System                     | 2         | 0.53%   |
| Xiaomi                            | 1         | 0.26%   |
| U-Blox                            | 1         | 0.26%   |
| TP-Link                           | 1         | 0.26%   |
| Sierra Wireless                   | 1         | 0.26%   |
| Napatech A/S                      | 1         | 0.26%   |
| Edimax Technology                 | 1         | 0.26%   |
| Bluegiga Technologies             | 1         | 0.26%   |
| Belkin Components                 | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |
| American Megatrends               | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 80        | 16.95%  |
| Intel I211 Gigabit Network Connection                                         | 42        | 8.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 4.03%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 2.54%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 2.33%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 2.33%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 10        | 2.12%   |
| Intel Wireless 7260                                                           | 9         | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                             | 8         | 1.69%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 1.69%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 1.48%   |
| Intel Wi-Fi 6 AX200                                                           | 6         | 1.27%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.27%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.27%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5         | 1.06%   |
| Intel Wireless 8260                                                           | 5         | 1.06%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.06%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.06%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 0.85%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.85%   |
| Intel Wireless 3165                                                           | 4         | 0.85%   |
| Intel Wireless 3160                                                           | 4         | 0.85%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                                | 4         | 0.85%   |
| Intel Centrino Advanced-N 6200                                                | 4         | 0.85%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 4         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 3         | 0.64%   |
| Intel Wireless 7265                                                           | 3         | 0.64%   |
| Intel WiFi Link 5100                                                          | 3         | 0.64%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.64%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.64%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                       | 3         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.64%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.42%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.42%   |
| Intel Wireless-AC 9260                                                        | 2         | 0.42%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 2         | 0.42%   |
| Intel Ethernet Controller X550                                                | 2         | 0.42%   |
| Intel Ethernet Connection I354                                                | 2         | 0.42%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 57.26%  |
| Qualcomm Atheros      | 21        | 16.94%  |
| Realtek Semiconductor | 10        | 8.06%   |
| Broadcom              | 7         | 5.65%   |
| Ralink Technology     | 4         | 3.23%   |
| Ralink                | 2         | 1.61%   |
| IMC Networks          | 2         | 1.61%   |
| D-Link System         | 2         | 1.61%   |
| TP-Link               | 1         | 0.81%   |
| Sierra Wireless       | 1         | 0.81%   |
| Edimax Technology     | 1         | 0.81%   |
| Belkin Components     | 1         | 0.81%   |
| ASUSTek Computer      | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 12        | 9.52%   |
| Intel Wireless 7260                                                        | 9         | 7.14%   |
| Intel Wi-Fi 6 AX200                                                        | 6         | 4.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 5         | 3.97%   |
| Intel Wireless 8260                                                        | 5         | 3.97%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 3.17%   |
| Intel Wireless 3165                                                        | 4         | 3.17%   |
| Intel Wireless 3160                                                        | 4         | 3.17%   |
| Intel Centrino Advanced-N 6200                                             | 4         | 3.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 4         | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 2.38%   |
| Intel Wireless 7265                                                        | 3         | 2.38%   |
| Intel WiFi Link 5100                                                       | 3         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                             | 3         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.59%   |
| Ralink RT5370 Wireless Adapter                                             | 2         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.59%   |
| Intel Wireless-AC 9260                                                     | 2         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 2         | 1.59%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 2         | 1.59%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.79%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                              | 1         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 0.79%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.79%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.79%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]     | 1         | 0.79%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)    | 1         | 0.79%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 0.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 0.79%   |
| Intel Centrino Wireless-N 2230                                             | 1         | 0.79%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 0.79%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                               | 1         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 0.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                             | 1         | 0.79%   |
| Belkin Components F5D8055 N+ Wireless Adapter v2000 [Ralink RT3072]        | 1         | 0.79%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                  | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 161       | 54.03%  |
| Realtek Semiconductor    | 91        | 30.54%  |
| Broadcom                 | 31        | 10.4%   |
| Nvidia                   | 5         | 1.68%   |
| Qualcomm Atheros         | 4         | 1.34%   |
| Marvell Technology Group | 4         | 1.34%   |
| Xiaomi                   | 1         | 0.34%   |
| American Megatrends      | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 80        | 23.95%  |
| Intel I211 Gigabit Network Connection                                         | 42        | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 5.69%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 4.19%   |
| Intel I350 Gigabit Network Connection                                         | 11        | 3.29%   |
| Intel 82574L Gigabit Network Connection                                       | 11        | 3.29%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 10        | 2.99%   |
| Intel 82580 Gigabit Network Connection                                        | 8         | 2.4%    |
| Intel 82576 Gigabit Network Connection                                        | 8         | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 2.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 7         | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                             | 6         | 1.8%    |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.8%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.8%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.8%    |
| Intel 82583V Gigabit Network Connection                                       | 5         | 1.5%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.5%    |
| Nvidia MCP79 Ethernet                                                         | 4         | 1.2%    |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.2%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.9%    |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.9%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.6%    |
| Intel Ethernet Controller X550                                                | 2         | 0.6%    |
| Intel Ethernet Connection I354                                                | 2         | 0.6%    |
| Intel Ethernet Connection I217-V                                              | 2         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.6%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 2         | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.3%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.3%    |
| Nvidia MCP73 Ethernet                                                         | 1         | 0.3%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                       | 1         | 0.3%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1         | 0.3%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                       | 1         | 0.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.3%    |
| Intel I210 Gigabit Fiber Network Connection                                   | 1         | 0.3%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.3%    |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1         | 0.3%    |
| Intel Ethernet Connection I219-V                                              | 1         | 0.3%    |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.3%    |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.3%    |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.3%    |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.3%    |
| Intel Ethernet Connection (11) I219-V                                         | 1         | 0.3%    |
| Intel Ethernet 10G 2P X520 Adapter                                            | 1         | 0.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1         | 0.3%    |
| Intel 82577LC Gigabit Network Connection                                      | 1         | 0.3%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.3%    |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 0.3%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 262       | 66.84%  |
| WiFi     | 118       | 30.1%   |
| Modem    | 6         | 1.53%   |
| Unknown  | 6         | 1.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 250       | 77.16%  |
| WiFi     | 71        | 21.91%  |
| Modem    | 3         | 0.93%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 36.75%  |
| 1     | 46        | 16.25%  |
| 4     | 38        | 13.43%  |
| 3     | 36        | 12.72%  |
| 5     | 23        | 8.13%   |
| 6     | 19        | 6.71%   |
| 0     | 6         | 2.12%   |
| 7     | 5         | 1.77%   |
| 8     | 2         | 0.71%   |
| 15    | 1         | 0.35%   |
| 12    | 1         | 0.35%   |
| 10    | 1         | 0.35%   |
| 9     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 262       | 90.03%  |
| Yes  | 29        | 9.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 49.3%   |
| Apple                           | 7         | 9.86%   |
| Cambridge Silicon Radio         | 6         | 8.45%   |
| Broadcom                        | 6         | 8.45%   |
| Dell                            | 4         | 5.63%   |
| Realtek Semiconductor           | 3         | 4.23%   |
| ASUSTek Computer                | 3         | 4.23%   |
| Qualcomm Atheros Communications | 2         | 2.82%   |
| IMC Networks                    | 2         | 2.82%   |
| Foxconn / Hon Hai               | 2         | 2.82%   |
| Alps Electric                   | 1         | 1.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 25.35%  |
| Intel AX200 Bluetooth                                                               | 6         | 8.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 8.45%   |
| Apple Bluetooth Host Controller                                                     | 5         | 7.04%   |
| Intel AX201 Bluetooth                                                               | 3         | 4.23%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 4.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.82%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 2.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.82%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.41%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 1.41%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.41%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.41%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 1.41%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                                          | 1         | 1.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.41%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.41%   |
| Broadcom Bluetooth                                                                  | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.41%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.41%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.41%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter                             | 1         | 1.41%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.41%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.41%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 169       | 63.3%   |
| AMD                                  | 52        | 19.48%  |
| Nvidia                               | 29        | 10.86%  |
| SteelSeries ApS                      | 3         | 1.12%   |
| C-Media Electronics                  | 3         | 1.12%   |
| Texas Instruments                    | 2         | 0.75%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.37%   |
| Nam Tai E&E Products                 | 1         | 0.37%   |
| Logitech                             | 1         | 0.37%   |
| JMTek                                | 1         | 0.37%   |
| Griffin Technology                   | 1         | 0.37%   |
| GN Netcom                            | 1         | 0.37%   |
| Elgato Systems                       | 1         | 0.37%   |
| Creative Labs                        | 1         | 0.37%   |
| BEHRINGER International              | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.74%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 2.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.22%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.22%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.91%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.91%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.61%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.61%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                | 1         | 0.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.3%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.3%    |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.3%    |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.3%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.3%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.3%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.3%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 48        | 17.14%  |
| Samsung Electronics | 45        | 16.07%  |
| Unknown             | 41        | 14.64%  |
| Crucial             | 31        | 11.07%  |
| Kingston            | 30        | 10.71%  |
| Corsair             | 25        | 8.93%   |
| Micron Technology   | 19        | 6.79%   |
| Unknown (ABCD)      | 6         | 2.14%   |
| A-DATA Technology   | 6         | 2.14%   |
| Ramaxel Technology  | 5         | 1.79%   |
| Team                | 3         | 1.07%   |
| Nanya Technology    | 3         | 1.07%   |
| G.Skill             | 3         | 1.07%   |
| Elpida              | 3         | 1.07%   |
| Transcend           | 2         | 0.71%   |
| Unknown (AB)        | 1         | 0.36%   |
| Toshiba             | 1         | 0.36%   |
| TIMETEC             | 1         | 0.36%   |
| Teikon              | 1         | 0.36%   |
| SK_Hynix            | 1         | 0.36%   |
| Hewlett-Packard     | 1         | 0.36%   |
| CSX                 | 1         | 0.36%   |
| Avant               | 1         | 0.36%   |
| Apacer              | 1         | 0.36%   |
| A Force             | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 41        | 13.62%  |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 5         | 1.66%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 4         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 1%      |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s             | 3         | 1%      |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s                    | 3         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s  | 2         | 0.66%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.66%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 2         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 2         | 0.66%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s             | 2         | 0.66%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.66%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.66%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.66%   |
| Kingston RAM LV26D4U9S8HJ-8 8GB DIMM DDR4 2667MT/s                | 2         | 0.66%   |
| Kingston RAM 99U5469-041.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 0.66%   |
| Kingston RAM 9905584-016.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 0.66%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s             | 2         | 0.66%   |
| Crucial RAM BL32G36C16U4B.M16FB1 32GB DIMM DDR4 3600MT/s          | 2         | 0.66%   |
| Corsair RAM CMK32GX4M2D3200C16 16GB DIMM DDR4 3200MT/s            | 2         | 0.66%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s             | 2         | 0.66%   |
| Unknown (AB) RAM Module 1GB DIMM LPDDR3 1600MT/s                  | 1         | 0.33%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s              | 1         | 0.33%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                  | 1         | 0.33%   |
| Toshiba RAM KCDT82-MIE 4GB SODIMM DDR4 2400MT/s                   | 1         | 0.33%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.33%   |
| Teikon RAM TMTS8G58DFRBFIR-16 8GB SODIMM DDR3 1600MT/s            | 1         | 0.33%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s               | 1         | 0.33%   |
| Team RAM TEAMGROUP-UD4-3000 4GB DIMM DDR4 2400MT/s                | 1         | 0.33%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                        | 1         | 0.33%   |
| SK_Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s            | 1         | 0.33%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.33%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.33%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT351U6CFR8C-PBA 8GB DIMM DDR3 1600MT/s             | 1         | 0.33%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.33%   |
| SK hynix RAM HMT325U7BFR8C-H9 2GB DIMM DDR3 1333MT/s              | 1         | 0.33%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s              | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 157       | 62.06%  |
| DDR4    | 65        | 25.69%  |
| DDR2    | 13        | 5.14%   |
| LPDDR4  | 7         | 2.77%   |
| Unknown | 4         | 1.58%   |
| SDRAM   | 3         | 1.19%   |
| LPDDR3  | 3         | 1.19%   |
| DDR     | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 140       | 55.78%  |
| SODIMM       | 104       | 41.43%  |
| Row Of Chips | 3         | 1.2%    |
| Chip         | 2         | 0.8%    |
| Unknown      | 2         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 103       | 38.87%  |
| 8192  | 99        | 37.36%  |
| 2048  | 36        | 13.58%  |
| 16384 | 16        | 6.04%   |
| 32768 | 5         | 1.89%   |
| 1024  | 5         | 1.89%   |
| 65536 | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 101       | 37.69%  |
| 1333    | 40        | 14.93%  |
| 2400    | 20        | 7.46%   |
| 2133    | 19        | 7.09%   |
| 2667    | 15        | 5.6%    |
| 800     | 9         | 3.36%   |
| 3200    | 8         | 2.99%   |
| 1867    | 8         | 2.99%   |
| 667     | 8         | 2.99%   |
| 1334    | 6         | 2.24%   |
| 2666    | 5         | 1.87%   |
| 1067    | 5         | 1.87%   |
| 3600    | 4         | 1.49%   |
| 1066    | 4         | 1.49%   |
| Unknown | 3         | 1.12%   |
| 2933    | 2         | 0.75%   |
| 533     | 2         | 0.75%   |
| 65535   | 1         | 0.37%   |
| 4267    | 1         | 0.37%   |
| 3534    | 1         | 0.37%   |
| 2600    | 1         | 0.37%   |
| 1866    | 1         | 0.37%   |
| 1800    | 1         | 0.37%   |
| 933     | 1         | 0.37%   |
| 333     | 1         | 0.37%   |
| 133     | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1200 | 1         | 50%     |
| HP DeskJet 5850c | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 25%     |
| Logitech                               | 7         | 12.5%   |
| Realtek Semiconductor                  | 5         | 8.93%   |
| Acer                                   | 4         | 7.14%   |
| Z-Star Microelectronics                | 3         | 5.36%   |
| Suyin                                  | 3         | 5.36%   |
| IMC Networks                           | 3         | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.36%   |
| Sunplus Innovation Technology          | 2         | 3.57%   |
| Silicon Motion                         | 2         | 3.57%   |
| Lite-On Technology                     | 2         | 3.57%   |
| Apple                                  | 2         | 3.57%   |
| Syntek                                 | 1         | 1.79%   |
| Microdia                               | 1         | 1.79%   |
| Lenovo                                 | 1         | 1.79%   |
| Creative Technology                    | 1         | 1.79%   |
| ARC International                      | 1         | 1.79%   |
| Alcor Micro                            | 1         | 1.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated HP HD Webcam                                          | 3         | 5.26%   |
| Chicony Integrated Camera                                                | 3         | 5.26%   |
| Realtek USB 2 Webcam                                                     | 2         | 3.51%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 3.51%   |
| Logitech Webcam C930e                                                    | 2         | 3.51%   |
| Logitech Labtec Webcam Pro                                               | 2         | 3.51%   |
| Logitech HD Pro Webcam C920                                              | 2         | 3.51%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 3.51%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 2         | 3.51%   |
| Chicony Integrated Camera [ThinkPad]                                     | 2         | 3.51%   |
| Apple FaceTime HD Camera                                                 | 2         | 3.51%   |
| Z-Star WebCam SC-03FFL11739P                                             | 1         | 1.75%   |
| Z-Star Webcam                                                            | 1         | 1.75%   |
| Z-Star Namuga 1.3M Webcam                                                | 1         | 1.75%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera                            | 1         | 1.75%   |
| Suyin Laptop_Integrated_Webcam_3M                                        | 1         | 1.75%   |
| Suyin Acer Crystal Eye webcam                                            | 1         | 1.75%   |
| Suyin 1.3M HD Webcam                                                     | 1         | 1.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 1.75%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                                    | 1         | 1.75%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.75%   |
| Silicon Motion 300k Pixel Camera                                         | 1         | 1.75%   |
| Realtek Realtek USB2.0 PC Camera                                         | 1         | 1.75%   |
| Microdia Integrated Webcam                                               | 1         | 1.75%   |
| Logitech Webcam C310                                                     | 1         | 1.75%   |
| Logitech B525 HD Webcam                                                  | 1         | 1.75%   |
| Lite-On Integrated Camera                                                | 1         | 1.75%   |
| Lite-On HP HD Camera                                                     | 1         | 1.75%   |
| Lenovo Integrated Webcam                                                 | 1         | 1.75%   |
| IMC Networks Integrated Webcam                                           | 1         | 1.75%   |
| Creative Webcam Live! Motion                                             | 1         | 1.75%   |
| Chicony Webcam                                                           | 1         | 1.75%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 1.75%   |
| Chicony Thinkpad T430 camera                                             | 1         | 1.75%   |
| Chicony Chicony USB 2.0 Camera                                           | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera           | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.75%   |
| ARC International Camera                                                 | 1         | 1.75%   |
| Alcor Micro USB 2.0 Web Camera                                           | 1         | 1.75%   |
| Acer Lenovo EasyCamera                                                   | 1         | 1.75%   |
| Acer Integrated Camera                                                   | 1         | 1.75%   |
| Acer HD Webcam                                                           | 1         | 1.75%   |
| Acer EasyCamera                                                          | 1         | 1.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 33.33%  |
| Shenzhen Goodix Technology | 3         | 25%     |
| Upek                       | 2         | 16.67%  |
| Synaptics                  | 1         | 8.33%   |
| Broadcom                   | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 16.67%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 8.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 8.33%   |

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
| 0     | 114       | 39.04%  |
| 1     | 108       | 36.99%  |
| 2     | 44        | 15.07%  |
| 3     | 17        | 5.82%   |
| 4     | 7         | 2.4%    |
| 5     | 2         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 143       | 56.3%   |
| Bluetooth                | 27        | 10.63%  |
| Net/wireless             | 24        | 9.45%   |
| Firewire controller      | 17        | 6.69%   |
| Card reader              | 16        | 6.3%    |
| Fingerprint reader       | 10        | 3.94%   |
| Sound                    | 5         | 1.97%   |
| Network                  | 3         | 1.18%   |
| Graphics card            | 3         | 1.18%   |
| Storage/raid             | 2         | 0.79%   |
| Storage                  | 2         | 0.79%   |
| Net/ethernet             | 2         | 0.79%   |

