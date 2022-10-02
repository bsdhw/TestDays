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

Total: 585

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Shuttle       | FH61V                       | Desktop     | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [3877787983](https://bsd-hardware.info/?probe=3877787983) | Sep 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cde2481e46](https://bsd-hardware.info/?probe=cde2481e46) | Sep 26, 2022 |
| HP            | 8592                        | Desktop     | [898ce46c1f](https://bsd-hardware.info/?probe=898ce46c1f) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [de9d75d495](https://bsd-hardware.info/?probe=de9d75d495) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8883d36139](https://bsd-hardware.info/?probe=8883d36139) | Sep 25, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| HP            | 8103 A01                    | Mini pc     | [533a1ebabe](https://bsd-hardware.info/?probe=533a1ebabe) | Sep 17, 2022 |
| Dell          | 07WP95 A01                  | Desktop     | [98e67ff164](https://bsd-hardware.info/?probe=98e67ff164) | Sep 12, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [fb678970df](https://bsd-hardware.info/?probe=fb678970df) | Sep 09, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [6c88b88822](https://bsd-hardware.info/?probe=6c88b88822) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [3f5ad2f043](https://bsd-hardware.info/?probe=3f5ad2f043) | Sep 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Dell          | Precision 7710              | Notebook    | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [58a4089f3f](https://bsd-hardware.info/?probe=58a4089f3f) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [edb9608bc9](https://bsd-hardware.info/?probe=edb9608bc9) | Aug 24, 2022 |
| Dell          | 03X6X0 A03                  | Server      | [d77ae4f2a0](https://bsd-hardware.info/?probe=d77ae4f2a0) | Aug 24, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [0dd0325ce1](https://bsd-hardware.info/?probe=0dd0325ce1) | Aug 22, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [6dd76b10ad](https://bsd-hardware.info/?probe=6dd76b10ad) | Aug 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [5648905ca2](https://bsd-hardware.info/?probe=5648905ca2) | Aug 19, 2022 |
| HP            | 8592                        | Desktop     | [212adc2c89](https://bsd-hardware.info/?probe=212adc2c89) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2b5456b337](https://bsd-hardware.info/?probe=2b5456b337) | Aug 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [78340c12ef](https://bsd-hardware.info/?probe=78340c12ef) | Aug 16, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [970bec57b8](https://bsd-hardware.info/?probe=970bec57b8) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4cf33d57a1](https://bsd-hardware.info/?probe=4cf33d57a1) | Aug 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9783858164](https://bsd-hardware.info/?probe=9783858164) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| HP            | 8592                        | Desktop     | [7c6794942c](https://bsd-hardware.info/?probe=7c6794942c) | Aug 10, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [8176a8261d](https://bsd-hardware.info/?probe=8176a8261d) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [cbda56eddb](https://bsd-hardware.info/?probe=cbda56eddb) | Aug 03, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b33527f3ee](https://bsd-hardware.info/?probe=b33527f3ee) | Jul 25, 2022 |
| Dell          | 0T7D40 A00                  | Desktop     | [3d5e83cf1a](https://bsd-hardware.info/?probe=3d5e83cf1a) | Jul 20, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [17aa06f41f](https://bsd-hardware.info/?probe=17aa06f41f) | Jul 18, 2022 |
| Dell          | 0T7D40 A00                  | Desktop     | [2aef6b2ab4](https://bsd-hardware.info/?probe=2aef6b2ab4) | Jul 18, 2022 |
| Shuttle       | FH170                       | Desktop     | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | Desktop     | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9943585bfa](https://bsd-hardware.info/?probe=9943585bfa) | Jul 16, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [9c6f76056f](https://bsd-hardware.info/?probe=9c6f76056f) | Jul 15, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [68c4af67b5](https://bsd-hardware.info/?probe=68c4af67b5) | Jul 14, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0f36e9b5a4](https://bsd-hardware.info/?probe=0f36e9b5a4) | Jul 03, 2022 |
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
| HP            | 8592                        | Desktop     | [d922327cdd](https://bsd-hardware.info/?probe=d922327cdd) | May 06, 2022 |
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
| HP            | 8592                        | Desktop     | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
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
| HP            | 8592                        | Desktop     | [fc273bb51a](https://bsd-hardware.info/?probe=fc273bb51a) | Feb 14, 2022 |
| HP            | 8592                        | Desktop     | [5accd7ce0d](https://bsd-hardware.info/?probe=5accd7ce0d) | Feb 13, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 20.7.8      | 16        | 3.93%   |
| FreeBSD 13.0         | 14        | 3.44%   |
| helloSystem 0.7.0    | 12        | 2.95%   |
| helloSystem 0.5.0    | 12        | 2.95%   |
| OPNsense 22.1        | 11        | 2.7%    |
| OPNsense 21.7.7      | 11        | 2.7%    |
| OPNsense 21.1.5      | 11        | 2.7%    |
| FreeBSD 14.0-CURRENT | 11        | 2.7%    |
| OPNsense 22.1.6      | 10        | 2.46%   |
| helloSystem 0.4.0    | 10        | 2.46%   |
| OPNsense 22.7.4      | 9         | 2.21%   |
| OPNsense 21.7.3      | 9         | 2.21%   |
| OPNsense 21.7.1      | 9         | 2.21%   |
| OPNsense 21.1.1      | 9         | 2.21%   |
| OPNsense 21.1        | 9         | 2.21%   |
| GhostBSD 20.04.02    | 9         | 2.21%   |
| OPNsense 22.7.2      | 8         | 1.97%   |
| OPNsense 22.1.10     | 8         | 1.97%   |
| OPNsense 21.1.7      | 8         | 1.97%   |
| OpenBSD 6.8          | 8         | 1.97%   |
| OPNsense 22.1.8      | 7         | 1.72%   |
| OPNsense 21.1.4      | 7         | 1.72%   |
| OPNsense 21.1.3      | 7         | 1.72%   |
| OPNsense 21.1.2      | 7         | 1.72%   |
| FreeBSD 12.2         | 7         | 1.72%   |
| OPNsense 22.1.4      | 6         | 1.47%   |
| OPNsense 21.7.8      | 6         | 1.47%   |
| FreeBSD 13.0-STABLE  | 6         | 1.47%   |
| OPNsense 22.1.9      | 5         | 1.23%   |
| OPNsense 22.1.3      | 5         | 1.23%   |
| OPNsense 22.1.2      | 5         | 1.23%   |
| OPNsense 21.7.2      | 5         | 1.23%   |
| OPNsense 21.1.6      | 5         | 1.23%   |
| FreeBSD 12.2-p3      | 5         | 1.23%   |
| OPNsense 21.7.5      | 4         | 0.98%   |
| OPNsense 21.1.8      | 4         | 0.98%   |
| OpenBSD 7.1          | 4         | 0.98%   |
| helloSystem 0.6.0    | 4         | 0.98%   |
| FreeBSD 13.0-p3      | 4         | 0.98%   |
| OPNsense 21.7.6      | 3         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 155       | 49.84%  |
| FreeBSD     | 68        | 21.86%  |
| helloSystem | 41        | 13.18%  |
| OpenBSD     | 19        | 6.11%   |
| GhostBSD    | 13        | 4.18%   |
| NomadBSD    | 7         | 2.25%   |
| NetBSD      | 4         | 1.29%   |
| XigmaNAS    | 1         | 0.32%   |
| pfSense     | 1         | 0.32%   |
| FuryBSD     | 1         | 0.32%   |
| DragonFly   | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 295       | 97.36%  |
| arm64 | 5         | 1.65%   |
| i386  | 2         | 0.66%   |
| riscv | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 188       | 60.06%  |
| helloDesktop     | 44        | 14.06%  |
| KDE5             | 20        | 6.39%   |
| XFCE             | 15        | 4.79%   |
| MATE             | 14        | 4.47%   |
| Openbox          | 7         | 2.24%   |
| fvwm             | 7         | 2.24%   |
| GNOME            | 5         | 1.6%    |
| i3               | 3         | 0.96%   |
| Cinnamon         | 2         | 0.64%   |
| TWM              | 1         | 0.32%   |
| PekWM            | 1         | 0.32%   |
| Metacity (Marco) | 1         | 0.32%   |
| Enlightenment    | 1         | 0.32%   |
| DWM              | 1         | 0.32%   |
| CDE              | 1         | 0.32%   |
| AwesomeWM        | 1         | 0.32%   |
| akonadi_newm     | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 190       | 62.3%   |
| X11     | 113       | 37.05%  |
| Wayland | 2         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 216       | 69.23%  |
| SLiM    | 55        | 17.63%  |
| SDDM    | 21        | 6.73%   |
| LightDM | 15        | 4.81%   |
| XDM     | 4         | 1.28%   |
| Ly      | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 195       | 61.32%  |
| en_US           | 52        | 16.35%  |
| C               | 43        | 13.52%  |
| en_GB           | 22        | 6.92%   |
| ru_RU           | 2         | 0.63%   |
| en_GB.US-ASCII  | 2         | 0.63%   |
| it_CH           | 1         | 0.31%   |
| en_GB.ISO8859-1 | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 255       | 82.79%  |
| BIOS | 53        | 17.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 170       | 54.84%  |
| Zfs     | 112       | 36.13%  |
| Ffs     | 19        | 6.13%   |
| Cd9660  | 7         | 2.26%   |
| Hammer2 | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 280       | 91.8%   |
| MBR     | 18        | 5.9%    |
| Unknown | 6         | 1.97%   |
| BSD     | 1         | 0.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 47        | 15.51%  |
| Lenovo                  | 28        | 9.24%   |
| Hewlett-Packard         | 28        | 9.24%   |
| ASUSTek Computer        | 21        | 6.93%   |
| Intel                   | 19        | 6.27%   |
| Gigabyte Technology     | 18        | 5.94%   |
| Unknown                 | 18        | 5.94%   |
| ASRock                  | 11        | 3.63%   |
| AMI                     | 11        | 3.63%   |
| Apple                   | 9         | 2.97%   |
| PC Engines              | 8         | 2.64%   |
| Shuttle                 | 6         | 1.98%   |
| Protectli               | 6         | 1.98%   |
| MSI                     | 6         | 1.98%   |
| Toshiba                 | 4         | 1.32%   |
| Samsung Electronics     | 4         | 1.32%   |
| Fujitsu                 | 4         | 1.32%   |
| Deciso                  | 4         | 1.32%   |
| Biostar                 | 3         | 0.99%   |
| Acer                    | 3         | 0.99%   |
| ZOTAC                   | 2         | 0.66%   |
| Yanling                 | 2         | 0.66%   |
| Supermicro              | 2         | 0.66%   |
| Raspberry Pi Foundation | 2         | 0.66%   |
| Inventec                | 2         | 0.66%   |
| HUAWEI                  | 2         | 0.66%   |
| HPE                     | 2         | 0.66%   |
| Winston Marriot         | 1         | 0.33%   |
| TUXEDO                  | 1         | 0.33%   |
| System76                | 1         | 0.33%   |
| Sophos                  | 1         | 0.33%   |
| Sony UK                 | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| Silver Peak Systems     | 1         | 0.33%   |
| Seeed Studio            | 1         | 0.33%   |
| Quanmax                 | 1         | 0.33%   |
| QOTOM                   | 1         | 0.33%   |
| Pegatron                | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| PAIQ                    | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 18        | 5.94%   |
| AMI Aptio CRB                       | 9         | 2.97%   |
| Intel Q3XXG4-P V1.0                 | 8         | 2.64%   |
| PC Engines APU2                     | 5         | 1.65%   |
| ASUS All Series                     | 4         | 1.32%   |
| Protectli FW4B                      | 3         | 0.99%   |
| HP EliteBook 8570p                  | 3         | 0.99%   |
| Dell Wyse 5070 Extended Thin Client | 3         | 0.99%   |
| Dell OptiPlex 7010                  | 3         | 0.99%   |
| Dell OptiPlex 3020                  | 3         | 0.99%   |
| Yanling YL-KBR6L                    | 2         | 0.66%   |
| RPi Raspberry Pi                    | 2         | 0.66%   |
| Protectli FW6                       | 2         | 0.66%   |
| PC Engines apu4                     | 2         | 0.66%   |
| Lenovo ThinkCentre M920s 10SJ0041UK | 2         | 0.66%   |
| HP Z600 Workstation                 | 2         | 0.66%   |
| HP t730 Thin Client                 | 2         | 0.66%   |
| HP t620 PLUS Quad Core TC           | 2         | 0.66%   |
| HP ProLiant DL360 Gen9              | 2         | 0.66%   |
| Gigabyte B450M DS3H                 | 2         | 0.66%   |
| Dell XPS 13 9343                    | 2         | 0.66%   |
| Dell PowerEdge R610                 | 2         | 0.66%   |
| Dell PowerEdge R210 II              | 2         | 0.66%   |
| Dell PowerEdge R210                 | 2         | 0.66%   |
| Dell OptiPlex 790                   | 2         | 0.66%   |
| Dell OptiPlex 760                   | 2         | 0.66%   |
| Dell OptiPlex 390                   | 2         | 0.66%   |
| Dell Inspiron 3793                  | 2         | 0.66%   |
| ASUS ZenBook S UX391UA              | 2         | 0.66%   |
| ASUS ROG STRIX X570-E GAMING        | 2         | 0.66%   |
| ASRock B550 Phantom Gaming 4        | 2         | 0.66%   |
| ZOTAC ZBOX-CI329NANO                | 1         | 0.33%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.33%   |
| Winston Marriot PICO PC(R)          | 1         | 0.33%   |
| TUXEDO Aura 15 Gen1                 | 1         | 0.33%   |
| Toshiba TECRA M11                   | 1         | 0.33%   |
| Toshiba Satellite Pro U400          | 1         | 0.33%   |
| Toshiba Satellite L50-C             | 1         | 0.33%   |
| Toshiba Satellite C660              | 1         | 0.33%   |
| System76 Gazelle                    | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Unknown            | 18        | 5.94%   |
| Lenovo ThinkPad    | 17        | 5.61%   |
| Dell OptiPlex      | 17        | 5.61%   |
| Dell PowerEdge     | 14        | 4.62%   |
| AMI Aptio          | 9         | 2.97%   |
| Lenovo ThinkCentre | 8         | 2.64%   |
| Intel Q3XXG4-P     | 8         | 2.64%   |
| HP ProLiant        | 6         | 1.98%   |
| PC Engines APU2    | 5         | 1.65%   |
| Dell Latitude      | 5         | 1.65%   |
| ASUS ROG           | 4         | 1.32%   |
| ASUS PRIME         | 4         | 1.32%   |
| ASUS All           | 4         | 1.32%   |
| Toshiba Satellite  | 3         | 0.99%   |
| Protectli FW4B     | 3         | 0.99%   |
| HP Pavilion        | 3         | 0.99%   |
| HP EliteBook       | 3         | 0.99%   |
| Dell Wyse          | 3         | 0.99%   |
| Dell Inspiron      | 3         | 0.99%   |
| Apple MacBookPro5  | 3         | 0.99%   |
| Acer Aspire        | 3         | 0.99%   |
| Yanling YL-KBR6L   | 2         | 0.66%   |
| RPi Raspberry      | 2         | 0.66%   |
| Protectli FW6      | 2         | 0.66%   |
| PC Engines apu4    | 2         | 0.66%   |
| HP Z600            | 2         | 0.66%   |
| HP t730            | 2         | 0.66%   |
| HP t620            | 2         | 0.66%   |
| HP ProDesk         | 2         | 0.66%   |
| HP EliteDesk       | 2         | 0.66%   |
| Gigabyte H61M-DS2  | 2         | 0.66%   |
| Gigabyte B450M     | 2         | 0.66%   |
| Fujitsu FUTRO      | 2         | 0.66%   |
| Fujitsu ESPRIMO    | 2         | 0.66%   |
| Dell XPS           | 2         | 0.66%   |
| Dell Precision     | 2         | 0.66%   |
| Deciso Netboard    | 2         | 0.66%   |
| ASUS ZenBook       | 2         | 0.66%   |
| ASUS P8Z77-V       | 2         | 0.66%   |
| ASRock B550        | 2         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 33        | 10.89%  |
| 2016    | 33        | 10.89%  |
| 2018    | 32        | 10.56%  |
| 2014    | 27        | 8.91%   |
| 2019    | 26        | 8.58%   |
| 2013    | 24        | 7.92%   |
| 2015    | 22        | 7.26%   |
| 2021    | 19        | 6.27%   |
| 2011    | 17        | 5.61%   |
| 2012    | 15        | 4.95%   |
| 2010    | 15        | 4.95%   |
| 2009    | 12        | 3.96%   |
| 2017    | 11        | 3.63%   |
| Unknown | 6         | 1.98%   |
| 2022    | 4         | 1.32%   |
| 2008    | 4         | 1.32%   |
| 2007    | 3         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 174       | 57.43%  |
| Notebook       | 73        | 24.09%  |
| Mini pc        | 24        | 7.92%   |
| Server         | 22        | 7.26%   |
| Firewall       | 4         | 1.32%   |
| System on chip | 3         | 0.99%   |
| All in one     | 2         | 0.66%   |
| Convertible    | 1         | 0.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 291       | 96.04%  |
| Yes  | 12        | 3.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 132       | 43.28%  |
| 4.01-8.0        | 66        | 21.64%  |
| 16.01-24.0      | 58        | 19.02%  |
| 32.01-64.0      | 19        | 6.23%   |
| 2.01-3.0        | 11        | 3.61%   |
| 64.01-256.0     | 9         | 2.95%   |
| 3.01-4.0        | 3         | 0.98%   |
| 24.01-32.0      | 3         | 0.98%   |
| 0.51-1.0        | 2         | 0.66%   |
| More than 256.0 | 1         | 0.33%   |
| Unknown         | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 182       | 57.05%  |
| 0.51-1.0    | 77        | 24.14%  |
| 1.01-2.0    | 24        | 7.52%   |
| 2.01-3.0    | 12        | 3.76%   |
| 3.01-4.0    | 7         | 2.19%   |
| 4.01-8.0    | 5         | 1.57%   |
| Unknown     | 4         | 1.25%   |
| 24.01-32.0  | 2         | 0.63%   |
| 8.01-16.0   | 2         | 0.63%   |
| 32.01-64.0  | 1         | 0.31%   |
| 64.01-256.0 | 1         | 0.31%   |
| 16.01-24.0  | 1         | 0.31%   |
| 0           | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 212       | 66.67%  |
| 2      | 48        | 15.09%  |
| 0      | 24        | 7.55%   |
| 3      | 12        | 3.77%   |
| 5      | 7         | 2.2%    |
| 4      | 7         | 2.2%    |
| 8      | 3         | 0.94%   |
| 6      | 2         | 0.63%   |
| 17     | 1         | 0.31%   |
| 14     | 1         | 0.31%   |
| 7      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 233       | 75.65%  |
| Yes       | 75        | 24.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 283       | 93.4%   |
| No        | 20        | 6.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 181       | 59.15%  |
| Yes       | 125       | 40.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 232       | 75.57%  |
| Yes       | 75        | 24.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 303       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 33        | 9.48%   |
| Glasgow             | 8         | 2.3%    |
| Brighton            | 7         | 2.01%   |
| Newcastle upon Tyne | 6         | 1.72%   |
| Watford             | 5         | 1.44%   |
| Swindon             | 5         | 1.44%   |
| Kensington          | 5         | 1.44%   |
| Stourbridge         | 4         | 1.15%   |
| Sheffield           | 4         | 1.15%   |
| Poplar              | 4         | 1.15%   |
| Milton Keynes       | 4         | 1.15%   |
| Islington           | 4         | 1.15%   |
| Hull                | 4         | 1.15%   |
| Cambridge           | 4         | 1.15%   |
| Bristol             | 4         | 1.15%   |
| York                | 3         | 0.86%   |
| Worthing            | 3         | 0.86%   |
| Wolverhampton       | 3         | 0.86%   |
| Wittersham          | 3         | 0.86%   |
| Southampton         | 3         | 0.86%   |
| Scunthorpe          | 3         | 0.86%   |
| Ruthin              | 3         | 0.86%   |
| Mansfield           | 3         | 0.86%   |
| Manchester          | 3         | 0.86%   |
| Malton              | 3         | 0.86%   |
| Liverpool           | 3         | 0.86%   |
| Leicester           | 3         | 0.86%   |
| Leeds               | 3         | 0.86%   |
| Leatherhead         | 3         | 0.86%   |
| Greenwich           | 3         | 0.86%   |
| Egham               | 3         | 0.86%   |
| Birmingham          | 3         | 0.86%   |
| Andover             | 3         | 0.86%   |
| Telford             | 2         | 0.57%   |
| Stoke-on-Trent      | 2         | 0.57%   |
| Stoke Newington     | 2         | 0.57%   |
| Slough              | 2         | 0.57%   |
| Rotherham           | 2         | 0.57%   |
| Reigate             | 2         | 0.57%   |
| Reading             | 2         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 109    | 16.57%  |
| WDC                 | 42        | 64     | 11.8%   |
| Seagate             | 35        | 90     | 9.83%   |
| Kingston            | 28        | 42     | 7.87%   |
| Crucial             | 26        | 37     | 7.3%    |
| Toshiba             | 18        | 55     | 5.06%   |
| SanDisk             | 18        | 22     | 5.06%   |
| Intel               | 11        | 14     | 3.09%   |
| Hitachi             | 10        | 13     | 2.81%   |
| Transcend           | 9         | 13     | 2.53%   |
| Phison              | 8         | 12     | 2.25%   |
| Hoodisk             | 8         | 13     | 2.25%   |
| HGST                | 8         | 28     | 2.25%   |
| SK hynix            | 6         | 8      | 1.69%   |
| LITEONIT            | 5         | 6      | 1.4%    |
| Hewlett-Packard     | 5         | 18     | 1.4%    |
| Micron Technology   | 4         | 5      | 1.12%   |
| Apacer              | 4         | 5      | 1.12%   |
| A-DATA Technology   | 4         | 7      | 1.12%   |
| PNY                 | 3         | 11     | 0.84%   |
| OCZ                 | 3         | 4      | 0.84%   |
| NVMe                | 3         | 3      | 0.84%   |
| FORESEE             | 3         | 3      | 0.84%   |
| Corsair             | 3         | 3      | 0.84%   |
| Apple               | 3         | 4      | 0.84%   |
| Patriot             | 2         | 5      | 0.56%   |
| OPENBSD             | 2         | 2      | 0.56%   |
| Netac               | 2         | 5      | 0.56%   |
| Lexar               | 2         | 2      | 0.56%   |
| Intenso             | 2         | 2      | 0.56%   |
| Integral            | 2         | 4      | 0.56%   |
| China               | 2         | 2      | 0.56%   |
| Zheino              | 1         | 1      | 0.28%   |
| XUM                 | 1         | 1      | 0.28%   |
| TCSUNBOW            | 1         | 2      | 0.28%   |
| SPCC                | 1         | 1      | 0.28%   |
| Solid State Storage | 1         | 1      | 0.28%   |
| SATA3 60            | 1         | 1      | 0.28%   |
| OWC                 | 1         | 1      | 0.28%   |
| MicroDream          | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 5         | 1.3%    |
| Samsung SSD 850 EVO 250GB            | 5         | 1.3%    |
| Kingston SUV500MS120G 120GB          | 5         | 1.3%    |
| Kingston SA400S37240G 240GB          | 5         | 1.3%    |
| Crucial CT500MX500SSD1 500GB         | 5         | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 4         | 1.04%   |
| Hoodisk SSD 64GB                     | 4         | 1.04%   |
| HGST HTS725050A7E630 500GB           | 4         | 1.04%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 0.78%   |
| Seagate ST3500418AS 500GB            | 3         | 0.78%   |
| Samsung HM251JX 250GB                | 3         | 0.78%   |
| Phison Sabrent 256GB                 | 3         | 0.78%   |
| HP RAID 1(1+0) 240GB                 | 3         | 0.78%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.78%   |
| WDC WDS250G2B0B-00YS70 250GB         | 2         | 0.52%   |
| WDC WD1600BEVT-80A23T0 160GB         | 2         | 0.52%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 0.52%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2         | 0.52%   |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.52%   |
| Transcend TS128GMSA370 128GB         | 2         | 0.52%   |
| Toshiba HDWE140 4TB                  | 2         | 0.52%   |
| Seagate ST8000VN0022-2EL112 8TB      | 2         | 0.52%   |
| Seagate ST8000AS0002-1NA17Z 8TB      | 2         | 0.52%   |
| Seagate ST4000NE001-2MA101 4TB       | 2         | 0.52%   |
| Seagate ST3500312CS 500GB            | 2         | 0.52%   |
| Seagate ST3160318AS 160GB            | 2         | 0.52%   |
| Seagate ST3160310CS 160GB            | 2         | 0.52%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.52%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.52%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.52%   |
| SanDisk SDCFHS-016G                  | 2         | 0.52%   |
| Samsung SSD PM851 M.2 2280 256GB     | 2         | 0.52%   |
| Samsung SSD PM810 2.5-inch 7mm 256GB | 2         | 0.52%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.52%   |
| Samsung SSD 850 PRO 256GB            | 2         | 0.52%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.52%   |
| Samsung SSD 750 EVO 250GB            | 2         | 0.52%   |
| Samsung MZVLW512HMJP-00000 512GB     | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 90     | 30.43%  |
| WDC                 | 31        | 46     | 26.96%  |
| Toshiba             | 13        | 43     | 11.3%   |
| Hitachi             | 10        | 13     | 8.7%    |
| HGST                | 8         | 28     | 6.96%   |
| Samsung Electronics | 6         | 6      | 5.22%   |
| Hewlett-Packard     | 5         | 18     | 4.35%   |
| OPENBSD             | 2         | 2      | 1.74%   |
| NVMe                | 2         | 2      | 1.74%   |
| Fujitsu             | 1         | 6      | 0.87%   |
| Dell                | 1         | 2      | 0.87%   |
| Apple               | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 80     | 19.81%  |
| Kingston            | 28        | 42     | 13.21%  |
| Crucial             | 24        | 35     | 11.32%  |
| SanDisk             | 18        | 22     | 8.49%   |
| Intel               | 10        | 12     | 4.72%   |
| WDC                 | 9         | 13     | 4.25%   |
| Hoodisk             | 8         | 13     | 3.77%   |
| Transcend           | 7         | 10     | 3.3%    |
| Phison              | 5         | 6      | 2.36%   |
| LITEONIT            | 5         | 6      | 2.36%   |
| Micron Technology   | 4         | 5      | 1.89%   |
| Apacer              | 4         | 5      | 1.89%   |
| A-DATA Technology   | 4         | 7      | 1.89%   |
| Toshiba             | 3         | 8      | 1.42%   |
| PNY                 | 3         | 9      | 1.42%   |
| OCZ                 | 3         | 4      | 1.42%   |
| FORESEE             | 3         | 3      | 1.42%   |
| Corsair             | 3         | 3      | 1.42%   |
| SK hynix            | 2         | 2      | 0.94%   |
| Patriot             | 2         | 5      | 0.94%   |
| Netac               | 2         | 5      | 0.94%   |
| Lexar               | 2         | 2      | 0.94%   |
| Intenso             | 2         | 2      | 0.94%   |
| Integral            | 2         | 4      | 0.94%   |
| China               | 2         | 2      | 0.94%   |
| Apple               | 2         | 3      | 0.94%   |
| Zheino              | 1         | 1      | 0.47%   |
| XUM                 | 1         | 1      | 0.47%   |
| TCSUNBOW            | 1         | 2      | 0.47%   |
| SPCC                | 1         | 1      | 0.47%   |
| SATA3 60            | 1         | 1      | 0.47%   |
| OWC                 | 1         | 1      | 0.47%   |
| NVMe                | 1         | 1      | 0.47%   |
| MicroDream          | 1         | 1      | 0.47%   |
| Marvell             | 1         | 1      | 0.47%   |
| LITEON              | 1         | 1      | 0.47%   |
| Kingchuxing         | 1         | 1      | 0.47%   |
| Gigabyte Technology | 1         | 2      | 0.47%   |
| BIWIN               | 1         | 2      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 192       | 324    | 60.19%  |
| HDD  | 94        | 257    | 29.47%  |
| NVMe | 33        | 56     | 10.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 260       | 581    | 88.74%  |
| NVMe | 33        | 56     | 11.26%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 232       | 418    | 78.11%  |
| 0.51-1.0   | 32        | 56     | 10.77%  |
| 1.01-2.0   | 15        | 28     | 5.05%   |
| 3.01-4.0   | 9         | 37     | 3.03%   |
| 4.01-10.0  | 8         | 41     | 2.69%   |
| 2.01-3.0   | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 128       | 39.51%  |
| 1-20           | 49        | 15.12%  |
| 251-500        | 48        | 14.81%  |
| 21-50          | 34        | 10.49%  |
| 51-100         | 33        | 10.19%  |
| 501-1000       | 18        | 5.56%   |
| 1001-2000      | 7         | 2.16%   |
| Unknown        | 4         | 1.23%   |
| More than 3000 | 2         | 0.62%   |
| 2001-3000      | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 273       | 86.39%  |
| 21-50          | 21        | 6.65%   |
| 51-100         | 8         | 2.53%   |
| 101-250        | 6         | 1.9%    |
| Unknown        | 4         | 1.27%   |
| 251-500        | 2         | 0.63%   |
| More than 3000 | 1         | 0.32%   |
| 2001-3000      | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 12     | 7.41%   |
| Seagate ST3500418AS 500GB                        | 2         | 3      | 3.7%    |
| Seagate ST3160310CS 160GB                        | 2         | 2      | 3.7%    |
| SanDisk SSD PLUS 480GB                           | 2         | 2      | 3.7%    |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 2         | 3      | 3.7%    |
| Crucial CT525MX300SSD1 528GB                     | 2         | 3      | 3.7%    |
| WDC WD5000AAKX-221CA1 500GB                      | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1         | 1      | 1.85%   |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1         | 4      | 1.85%   |
| WDC WD3200BEVT-22A23T0 320GB                     | 1         | 3      | 1.85%   |
| WDC WD3200AAJS-22B4A0 320GB                      | 1         | 1      | 1.85%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 1.85%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 1.85%   |
| WDC WD10JMVW-11AJGS0 1TB                         | 1         | 1      | 1.85%   |
| Transcend TS256GSSD320 256GB                     | 1         | 1      | 1.85%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.85%   |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 1.85%   |
| Toshiba HDWE140 4TB                              | 1         | 8      | 1.85%   |
| Toshiba DT01ACA200 2TB                           | 1         | 1      | 1.85%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 1.85%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.85%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 1.85%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.85%   |
| SanDisk SSD P4 16GB                              | 1         | 1      | 1.85%   |
| SanDisk SDCFHS-016G                              | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 1.85%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1         | 1      | 1.85%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 1.85%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.85%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 1.85%   |
| Marvell SATAIII 16GB                             | 1         | 1      | 1.85%   |
| Kingston SV300S37A120G 120GB                     | 1         | 2      | 1.85%   |
| Kingston SV200S3128G 128GB                       | 1         | 1      | 1.85%   |
| Kingchuxing SSD 60GB                             | 1         | 1      | 1.85%   |
| Intel SSDSC2BB120G4 120GB                        | 1         | 2      | 1.85%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.85%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 1.85%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 1.85%   |
| HGST HUS726040ALE610 4TB                         | 1         | 1      | 1.85%   |
| HGST HTS721010A9E630 1TB                         | 1         | 12     | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 13     | 15.38%  |
| Seagate             | 7         | 8      | 13.46%  |
| Samsung Electronics | 6         | 7      | 11.54%  |
| HGST                | 6         | 26     | 11.54%  |
| Toshiba             | 4         | 12     | 7.69%   |
| SanDisk             | 4         | 4      | 7.69%   |
| Hitachi             | 3         | 3      | 5.77%   |
| Crucial             | 3         | 5      | 5.77%   |
| Kingston            | 2         | 3      | 3.85%   |
| A-DATA Technology   | 2         | 3      | 3.85%   |
| Transcend           | 1         | 1      | 1.92%   |
| Micron Technology   | 1         | 1      | 1.92%   |
| Marvell             | 1         | 1      | 1.92%   |
| Kingchuxing         | 1         | 1      | 1.92%   |
| Intel               | 1         | 2      | 1.92%   |
| China               | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 13     | 25.81%  |
| Seagate             | 7         | 8      | 22.58%  |
| HGST                | 6         | 26     | 19.35%  |
| Toshiba             | 4         | 12     | 12.9%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Apple               | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 65     | 58.82%  |
| SSD  | 20        | 26     | 39.22%  |
| NVMe | 1         | 1      | 1.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST4000NM0025 4TB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 245       | 510    | 79.03%  |
| Malfunc  | 48        | 92     | 15.48%  |
| Detected | 16        | 33     | 5.16%   |
| Failed   | 1         | 2      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 221       | 61.22%  |
| AMD                            | 57        | 15.79%  |
| Samsung Electronics            | 17        | 4.71%   |
| Broadcom / LSI                 | 11        | 3.05%   |
| Marvell Technology Group       | 8         | 2.22%   |
| ASMedia Technology             | 8         | 2.22%   |
| SanDisk                        | 6         | 1.66%   |
| Nvidia                         | 6         | 1.66%   |
| Phison Electronics             | 5         | 1.39%   |
| SK hynix                       | 4         | 1.11%   |
| Hewlett-Packard                | 4         | 1.11%   |
| Toshiba                        | 3         | 0.83%   |
| Micron/Crucial Technology      | 2         | 0.55%   |
| Adaptec                        | 2         | 0.55%   |
| Unknown                        | 2         | 0.55%   |
| VIA Technologies               | 1         | 0.28%   |
| Solid State Storage Technology | 1         | 0.28%   |
| Silicon Motion                 | 1         | 0.28%   |
| Silicon Image                  | 1         | 0.28%   |
| Kingston Technology Company    | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39        | 9.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 5.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 4.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 3.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11        | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 2.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 9         | 2.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 8         | 1.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.74%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 6         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.49%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.24%   |
| Phison E12 NVMe Controller                                                              | 4         | 1%      |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.75%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3         | 0.75%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.75%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.75%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.75%   |
| AMD FCH IDE Controller                                                                  | 3         | 0.75%   |
| Unknown                                                                                 | 3         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 252       | 71.59%  |
| NVMe | 38        | 10.8%   |
| IDE  | 34        | 9.66%   |
| RAID | 21        | 5.97%   |
| SCSI | 4         | 1.14%   |
| SAS  | 3         | 0.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 234       | 77.23%  |
| AMD      | 62        | 20.46%  |
| ARM      | 3         | 0.99%   |
| Unknown  | 2         | 0.66%   |
| Research | 1         | 0.33%   |
| 11th     | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz        | 10        | 3.26%   |
| AMD GX-412TC SOC                         | 7         | 2.28%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 4         | 1.3%    |
| Intel Core i5-9500 CPU @ 3.00GHz         | 4         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 1.3%    |
| Intel Core i5-5250U CPU @ 1.60GHz        | 4         | 1.3%    |
| Intel Celeron CPU N3150 @ 1.60GHz        | 4         | 1.3%    |
| Intel Celeron CPU J3160 @ 1.60GHz        | 4         | 1.3%    |
| Intel Atom CPU E3845 @ 1.91GHz           | 4         | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor        | 4         | 1.3%    |
| Intel CPU Version                        | 3         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.98%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 0.98%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 0.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 0.98%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 3         | 0.98%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 3         | 0.98%   |
| Intel Core 2 Duo                         | 3         | 0.98%   |
| Intel Celeron CPU N2940 @ 1.83GHz        | 3         | 0.98%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 3         | 0.98%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 3         | 0.98%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 3         | 0.98%   |
| AMD GX-416RA SOC                         | 3         | 0.98%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 2         | 0.65%   |
| Intel Xeon CPU E5530 @ 2.40GHz           | 2         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 2         | 0.65%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 0.65%   |
| Intel Core i7-4500U CPU @ 1.80GHz        | 2         | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GH          | 2         | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.65%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 2         | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 2         | 0.65%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 2         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2         | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2         | 0.65%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 57        | 18.69%  |
| Intel Celeron           | 43        | 14.1%   |
| Intel Core i7           | 38        | 12.46%  |
| Intel Xeon              | 27        | 8.85%   |
| Intel Core i3           | 25        | 8.2%    |
| AMD GX                  | 14        | 4.59%   |
| Intel Core 2 Duo        | 13        | 4.26%   |
| AMD Ryzen 5             | 12        | 3.93%   |
| Other                   | 10        | 3.28%   |
| Intel Atom              | 10        | 3.28%   |
| Intel Pentium           | 6         | 1.97%   |
| AMD Ryzen 7             | 5         | 1.64%   |
| Intel Pentium Silver    | 4         | 1.31%   |
| ARM Cortex              | 3         | 0.98%   |
| AMD Ryzen 3             | 3         | 0.98%   |
| AMD G                   | 3         | 0.98%   |
| AMD FX                  | 3         | 0.98%   |
| AMD A6                  | 3         | 0.98%   |
| Intel Xeon Silver       | 2         | 0.66%   |
| Intel Core i9           | 2         | 0.66%   |
| Intel Core 2 Quad       | 2         | 0.66%   |
| AMD Ryzen Embedded      | 2         | 0.66%   |
| AMD Ryzen 9             | 2         | 0.66%   |
| AMD Athlon              | 2         | 0.66%   |
| AMD A4                  | 2         | 0.66%   |
| Intel Pentium Dual-Core | 1         | 0.33%   |
| Intel Core 2            | 1         | 0.33%   |
| Intel 686-class         | 1         | 0.33%   |
| AMD Ryzen Threadripper  | 1         | 0.33%   |
| AMD Ryzen 7 PRO         | 1         | 0.33%   |
| AMD Phenom II X6        | 1         | 0.33%   |
| AMD Phenom              | 1         | 0.33%   |
| AMD Opteron             | 1         | 0.33%   |
| AMD EPYC                | 1         | 0.33%   |
| AMD E2                  | 1         | 0.33%   |
| AMD Athlon 64 X2        | 1         | 0.33%   |
| AMD A8                  | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 131       | 42.67%  |
| 2       | 105       | 34.2%   |
| Unknown | 18        | 5.86%   |
| 12      | 14        | 4.56%   |
| 6       | 12        | 3.91%   |
| 8       | 10        | 3.26%   |
| 16      | 7         | 2.28%   |
| 24      | 4         | 1.3%    |
| 1       | 3         | 0.98%   |
| 10      | 2         | 0.65%   |
| 128     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 284       | 93.73%  |
| 2       | 11        | 3.63%   |
| Unknown | 8         | 2.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 162       | 52.94%  |
| 2       | 126       | 41.18%  |
| Unknown | 18        | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 35        | 11.51%  |
| Haswell       | 35        | 11.51%  |
| KabyLake      | 27        | 8.88%   |
| SandyBridge   | 25        | 8.22%   |
| IvyBridge     | 22        | 7.24%   |
| Penryn        | 17        | 5.59%   |
| Skylake       | 16        | 5.26%   |
| Zen 2         | 12        | 3.95%   |
| Westmere      | 10        | 3.29%   |
| Goldmont plus | 10        | 3.29%   |
| Broadwell     | 10        | 3.29%   |
| Nehalem       | 9         | 2.96%   |
| Jaguar        | 9         | 2.96%   |
| Unknown       | 9         | 2.96%   |
| Zen 3         | 7         | 2.3%    |
| Puma          | 7         | 2.3%    |
| Goldmont      | 6         | 1.97%   |
| Zen           | 5         | 1.64%   |
| Piledriver    | 5         | 1.64%   |
| Bonnell       | 4         | 1.32%   |
| Bobcat        | 4         | 1.32%   |
| Zen+          | 3         | 0.99%   |
| Core          | 3         | 0.99%   |
| Steamroller   | 2         | 0.66%   |
| K10           | 2         | 0.66%   |
| IceLake       | 2         | 0.66%   |
| Excavator     | 2         | 0.66%   |
| CometLake     | 2         | 0.66%   |
| TigerLake     | 1         | 0.33%   |
| K8 Hammer     | 1         | 0.33%   |
| K10 Llano     | 1         | 0.33%   |
| Bulldozer     | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 185       | 62.71%  |
| AMD                        | 49        | 16.61%  |
| Nvidia                     | 38        | 12.88%  |
| Matrox Electronics Systems | 18        | 6.1%    |
| ASPEED Technology          | 5         | 1.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 6.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 3.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 3.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10        | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.97%   |
| Intel HD Graphics 620                                                                    | 6         | 1.97%   |
| Intel HD Graphics 500                                                                    | 6         | 1.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.64%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.64%   |
| Intel HD Graphics 530                                                                    | 5         | 1.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.64%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.64%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 1.31%   |
| Intel HD Graphics 6000                                                                   | 4         | 1.31%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.98%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.98%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.98%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 0.98%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.98%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.98%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.98%   |
| AMD Cezanne                                                                              | 3         | 0.98%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.66%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.66%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.66%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.66%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 2         | 0.66%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 164       | 53.77%  |
| 1 x AMD        | 44        | 14.43%  |
| 1 x Nvidia     | 30        | 9.84%   |
| Other          | 21        | 6.89%   |
| 1 x Matrox     | 18        | 5.9%    |
| 2 x Intel      | 11        | 3.61%   |
| Intel + Nvidia | 6         | 1.97%   |
| 1 x ASPEED     | 5         | 1.64%   |
| Intel + AMD    | 4         | 1.31%   |
| 2 x Nvidia     | 2         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 261       | 85.57%  |
| Unknown     | 29        | 9.51%   |
| Proprietary | 15        | 4.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 90.52%  |
| 1.01-2.0   | 8         | 2.61%   |
| 0.51-1.0   | 8         | 2.61%   |
| 3.01-4.0   | 5         | 1.63%   |
| 7.01-8.0   | 4         | 1.31%   |
| 0.01-0.5   | 2         | 0.65%   |
| 5.01-6.0   | 1         | 0.33%   |
| 8.01-16.0  | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 12        | 12%     |
| Samsung Electronics     | 11        | 11%     |
| LG Display              | 11        | 11%     |
| Dell                    | 8         | 8%      |
| Hewlett-Packard         | 6         | 6%      |
| Lenovo                  | 5         | 5%      |
| Chimei Innolux          | 5         | 5%      |
| Philips                 | 4         | 4%      |
| BenQ                    | 4         | 4%      |
| AOC                     | 4         | 4%      |
| Iiyama                  | 3         | 3%      |
| BOE                     | 3         | 3%      |
| Acer                    | 3         | 3%      |
| Sharp                   | 2         | 2%      |
| Pixio                   | 2         | 2%      |
| LG Philips              | 2         | 2%      |
| HannStar                | 2         | 2%      |
| Apple                   | 2         | 2%      |
| Vestel Elektronik       | 1         | 1%      |
| Sony                    | 1         | 1%      |
| SDC                     | 1         | 1%      |
| RS                      | 1         | 1%      |
| PANDA                   | 1         | 1%      |
| OEM                     | 1         | 1%      |
| InnoLux Display         | 1         | 1%      |
| Goldstar                | 1         | 1%      |
| CPT                     | 1         | 1%      |
| Chi Mei Optoelectronics | 1         | 1%      |
| AVX                     | 1         | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch             | 3         | 2.86%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 2.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 2.86%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 1.9%    |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch           | 2         | 1.9%    |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 1.9%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.95%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 0.95%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 0.95%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch     | 1         | 0.95%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch  | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 1         | 0.95%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 0.95%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                       | 1         | 0.95%   |
| Pixio PX7 Prime HYC2700 2560x1440 600x340mm 27.2-inch                 | 1         | 0.95%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                     | 1         | 0.95%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 0.95%   |
| Philips LCD Monitor 271P4                                             | 1         | 0.95%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 0.95%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.95%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.95%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 34        | 33.66%  |
| 1366x768 (WXGA)    | 16        | 15.84%  |
| 1600x900 (HD+)     | 7         | 6.93%   |
| 1280x800 (WXGA)    | 7         | 6.93%   |
| 1920x1200 (WUXGA)  | 5         | 4.95%   |
| 1680x1050 (WSXGA+) | 4         | 3.96%   |
| 3840x2160 (4K)     | 3         | 2.97%   |
| 2560x1440 (QHD)    | 3         | 2.97%   |
| 1440x900 (WXGA+)   | 3         | 2.97%   |
| 1280x1024 (SXGA)   | 3         | 2.97%   |
| 1024x600           | 3         | 2.97%   |
| Unknown            | 3         | 2.97%   |
| 3200x1800 (QHD+)   | 2         | 1.98%   |
| 1920x540           | 2         | 1.98%   |
| 5760x1200          | 1         | 0.99%   |
| 3840x1080          | 1         | 0.99%   |
| 3520x1080          | 1         | 0.99%   |
| 3440x1440          | 1         | 0.99%   |
| 3200x1080          | 1         | 0.99%   |
| 2880x1800          | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 20%     |
| 13      | 16        | 16%     |
| 27      | 8         | 8%      |
| 19      | 7         | 7%      |
| 24      | 6         | 6%      |
| 23      | 6         | 6%      |
| 12      | 6         | 6%      |
| Unknown | 6         | 6%      |
| 22      | 4         | 4%      |
| 21      | 4         | 4%      |
| 17      | 4         | 4%      |
| 25      | 2         | 2%      |
| 10      | 2         | 2%      |
| 49      | 1         | 1%      |
| 42      | 1         | 1%      |
| 39      | 1         | 1%      |
| 34      | 1         | 1%      |
| 31      | 1         | 1%      |
| 18      | 1         | 1%      |
| 14      | 1         | 1%      |
| 11      | 1         | 1%      |
| 9       | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 28.87%  |
| 501-600     | 20        | 20.62%  |
| 201-300     | 19        | 19.59%  |
| 401-500     | 10        | 10.31%  |
| 351-400     | 8         | 8.25%   |
| Unknown     | 6         | 6.19%   |
| 601-700     | 2         | 2.06%   |
| 801-900     | 1         | 1.03%   |
| 701-800     | 1         | 1.03%   |
| 1001-1500   | 1         | 1.03%   |
| 901-1000    | 1         | 1.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 64.52%  |
| 16/10   | 18        | 19.35%  |
| Unknown | 5         | 5.38%   |
| 5/4     | 4         | 4.3%    |
| 3/2     | 3         | 3.23%   |
| 32/9    | 2         | 2.15%   |
| 21/9    | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 16        | 16.49%  |
| 81-90          | 11        | 11.34%  |
| 101-110        | 10        | 10.31%  |
| 91-100         | 10        | 10.31%  |
| 301-350        | 8         | 8.25%   |
| 151-200        | 7         | 7.22%   |
| 71-80          | 6         | 6.19%   |
| 61-70          | 6         | 6.19%   |
| Unknown        | 6         | 6.19%   |
| 121-130        | 4         | 4.12%   |
| 41-50          | 3         | 3.09%   |
| 251-300        | 3         | 3.09%   |
| 501-1000       | 3         | 3.09%   |
| 351-500        | 2         | 2.06%   |
| 51-60          | 1         | 1.03%   |
| 141-150        | 1         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 36.08%  |
| 101-120       | 26        | 26.8%   |
| 121-160       | 21        | 21.65%  |
| 161-240       | 7         | 7.22%   |
| Unknown       | 6         | 6.19%   |
| More than 240 | 2         | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 210       | 68.4%   |
| 1     | 87        | 28.34%  |
| 2     | 9         | 2.93%   |
| 3     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 204       | 49.51%  |
| Realtek Semiconductor             | 107       | 25.97%  |
| Broadcom                          | 38        | 9.22%   |
| Qualcomm Atheros                  | 24        | 5.83%   |
| Ralink Technology                 | 5         | 1.21%   |
| Nvidia                            | 5         | 1.21%   |
| Marvell Technology Group          | 5         | 1.21%   |
| IMC Networks                      | 3         | 0.73%   |
| Hewlett-Packard                   | 3         | 0.73%   |
| Ralink                            | 2         | 0.49%   |
| Ericsson Business Mobile Networks | 2         | 0.49%   |
| D-Link System                     | 2         | 0.49%   |
| AMD                               | 2         | 0.49%   |
| Xiaomi                            | 1         | 0.24%   |
| U-Blox                            | 1         | 0.24%   |
| TP-Link                           | 1         | 0.24%   |
| Sierra Wireless                   | 1         | 0.24%   |
| Napatech A/S                      | 1         | 0.24%   |
| Edimax Technology                 | 1         | 0.24%   |
| Bluegiga Technologies             | 1         | 0.24%   |
| Belkin Components                 | 1         | 0.24%   |
| ASUSTek Computer                  | 1         | 0.24%   |
| American Megatrends               | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 89        | 17.42%  |
| Intel I211 Gigabit Network Connection                                         | 45        | 8.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 3.72%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 3.13%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 2.35%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 2.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 12        | 2.35%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.76%   |
| Intel Wireless 7260                                                           | 9         | 1.76%   |
| Intel 82580 Gigabit Network Connection                                        | 9         | 1.76%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.57%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 1.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.37%   |
| Intel Wireless 8260                                                           | 6         | 1.17%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.17%   |
| Intel 82583V Gigabit Network Connection                                       | 6         | 1.17%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.98%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 0.78%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.78%   |
| Intel Wireless 3165                                                           | 4         | 0.78%   |
| Intel Wireless 3160                                                           | 4         | 0.78%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                                | 4         | 0.78%   |
| Intel Centrino Advanced-N 6200                                                | 4         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 0.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 4         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                                | 3         | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 3         | 0.59%   |
| Intel Wireless 7265                                                           | 3         | 0.59%   |
| Intel WiFi Link 5100                                                          | 3         | 0.59%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.59%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 56.49%  |
| Qualcomm Atheros      | 21        | 16.03%  |
| Realtek Semiconductor | 11        | 8.4%    |
| Broadcom              | 8         | 6.11%   |
| Ralink Technology     | 5         | 3.82%   |
| IMC Networks          | 3         | 2.29%   |
| Ralink                | 2         | 1.53%   |
| D-Link System         | 2         | 1.53%   |
| TP-Link               | 1         | 0.76%   |
| Sierra Wireless       | 1         | 0.76%   |
| Edimax Technology     | 1         | 0.76%   |
| Belkin Components     | 1         | 0.76%   |
| ASUSTek Computer      | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 12        | 9.02%   |
| Intel Wireless 7260                                                        | 9         | 6.77%   |
| Intel Wi-Fi 6 AX200                                                        | 8         | 6.02%   |
| Intel Wireless 8260                                                        | 6         | 4.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 5         | 3.76%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 3.01%   |
| Intel Wireless 3165                                                        | 4         | 3.01%   |
| Intel Wireless 3160                                                        | 4         | 3.01%   |
| Intel Centrino Advanced-N 6200                                             | 4         | 3.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 4         | 3.01%   |
| Ralink RT5370 Wireless Adapter                                             | 3         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 2.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 2.26%   |
| Intel Wireless 7265                                                        | 3         | 2.26%   |
| Intel WiFi Link 5100                                                       | 3         | 2.26%   |
| Intel Centrino Ultimate-N 6300                                             | 3         | 2.26%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 3         | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.5%    |
| Intel Wireless-AC 9260                                                     | 2         | 1.5%    |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 2         | 1.5%    |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.75%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                              | 1         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 0.75%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.75%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 176       | 53.99%  |
| Realtek Semiconductor    | 100       | 30.67%  |
| Broadcom                 | 32        | 9.82%   |
| Nvidia                   | 5         | 1.53%   |
| Marvell Technology Group | 5         | 1.53%   |
| Qualcomm Atheros         | 4         | 1.23%   |
| AMD                      | 2         | 0.61%   |
| Xiaomi                   | 1         | 0.31%   |
| American Megatrends      | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 89        | 24.32%  |
| Intel I211 Gigabit Network Connection                                         | 45        | 12.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 5.19%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 4.37%   |
| Intel I350 Gigabit Network Connection                                         | 12        | 3.28%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 3.28%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 12        | 3.28%   |
| Intel 82580 Gigabit Network Connection                                        | 9         | 2.46%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 2.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.91%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.64%   |
| Intel 82583V Gigabit Network Connection                                       | 6         | 1.64%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.64%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.37%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 1.09%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.09%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.09%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.82%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.82%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 2         | 0.55%   |
| Intel Ethernet Controller X550                                                | 2         | 0.55%   |
| Intel Ethernet Connection I354                                                | 2         | 0.55%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.55%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 2         | 0.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.55%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 2         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 283       | 67.38%  |
| WiFi     | 125       | 29.76%  |
| Modem    | 6         | 1.43%   |
| Unknown  | 6         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 268       | 77.91%  |
| WiFi     | 73        | 21.22%  |
| Modem    | 3         | 0.87%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 109       | 35.5%   |
| 1     | 52        | 16.94%  |
| 4     | 42        | 13.68%  |
| 3     | 37        | 12.05%  |
| 5     | 28        | 9.12%   |
| 6     | 20        | 6.51%   |
| 0     | 6         | 1.95%   |
| 7     | 5         | 1.63%   |
| 8     | 3         | 0.98%   |
| 15    | 1         | 0.33%   |
| 14    | 1         | 0.33%   |
| 12    | 1         | 0.33%   |
| 10    | 1         | 0.33%   |
| 9     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 280       | 88.89%  |
| Yes  | 35        | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 50.67%  |
| Apple                           | 7         | 9.33%   |
| Cambridge Silicon Radio         | 6         | 8%      |
| Broadcom                        | 6         | 8%      |
| Dell                            | 4         | 5.33%   |
| Realtek Semiconductor           | 3         | 4%      |
| ASUSTek Computer                | 3         | 4%      |
| Qualcomm Atheros Communications | 2         | 2.67%   |
| IMC Networks                    | 2         | 2.67%   |
| Foxconn / Hon Hai               | 2         | 2.67%   |
| Realtek                         | 1         | 1.33%   |
| Alps Electric                   | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 25.33%  |
| Intel AX200 Bluetooth                                                               | 8         | 10.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 8%      |
| Apple Bluetooth Host Controller                                                     | 5         | 6.67%   |
| Intel AX201 Bluetooth                                                               | 3         | 4%      |
| Dell DW375 Bluetooth Module                                                         | 3         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 2         | 2.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.67%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.33%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 1.33%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.33%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.33%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.33%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 1.33%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                                          | 1         | 1.33%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.33%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.33%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.33%   |
| Broadcom Bluetooth                                                                  | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.33%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.33%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter                             | 1         | 1.33%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.33%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.33%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 181       | 62.85%  |
| AMD                                  | 60        | 20.83%  |
| Nvidia                               | 30        | 10.42%  |
| SteelSeries ApS                      | 3         | 1.04%   |
| C-Media Electronics                  | 3         | 1.04%   |
| Texas Instruments                    | 2         | 0.69%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.35%   |
| Nam Tai E&E Products                 | 1         | 0.35%   |
| Logitech                             | 1         | 0.35%   |
| JMTek                                | 1         | 0.35%   |
| Griffin Technology                   | 1         | 0.35%   |
| GN Netcom                            | 1         | 0.35%   |
| Elgato Systems                       | 1         | 0.35%   |
| Creative Labs                        | 1         | 0.35%   |
| BEHRINGER International              | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 7.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 5.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 4.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 3.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 3.68%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.4%    |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 2.83%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.42%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.13%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.13%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.85%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.85%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.85%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 54        | 17.82%  |
| Samsung Electronics | 47        | 15.51%  |
| Unknown             | 38        | 12.54%  |
| Kingston            | 34        | 11.22%  |
| Crucial             | 32        | 10.56%  |
| Corsair             | 26        | 8.58%   |
| Micron Technology   | 20        | 6.6%    |
| Unknown (ABCD)      | 7         | 2.31%   |
| A-DATA Technology   | 6         | 1.98%   |
| Unknown             | 6         | 1.98%   |
| Ramaxel Technology  | 5         | 1.65%   |
| Transcend           | 4         | 1.32%   |
| Elpida              | 4         | 1.32%   |
| Team                | 3         | 0.99%   |
| Nanya Technology    | 3         | 0.99%   |
| G.Skill             | 3         | 0.99%   |
| Unknown (AB)        | 1         | 0.33%   |
| Toshiba             | 1         | 0.33%   |
| TIMETEC             | 1         | 0.33%   |
| Teikon              | 1         | 0.33%   |
| SK_Hynix            | 1         | 0.33%   |
| Kimtigo             | 1         | 0.33%   |
| Hewlett-Packard     | 1         | 0.33%   |
| CSX                 | 1         | 0.33%   |
| Avant               | 1         | 0.33%   |
| Apacer              | 1         | 0.33%   |
| A Force             | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 6         | 1.84%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 5         | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 1.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 5         | 1.53%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 4         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 4         | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.23%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 3         | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.92%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 3         | 0.92%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s             | 3         | 0.92%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s                    | 3         | 0.92%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s  | 2         | 0.61%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 2         | 0.61%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.61%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 2         | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 2         | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 2         | 0.61%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s             | 2         | 0.61%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.61%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.61%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.61%   |
| Kingston RAM LV26D4U9S8HJ-8 8GB DIMM DDR4 2667MT/s                | 2         | 0.61%   |
| Kingston RAM 99U5469-041.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 0.61%   |
| Kingston RAM 9905584-016.A00LF 4GB DIMM DDR3 1600MT/s             | 2         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 168       | 61.09%  |
| DDR4    | 74        | 26.91%  |
| DDR2    | 13        | 4.73%   |
| LPDDR4  | 8         | 2.91%   |
| Unknown | 4         | 1.45%   |
| SDRAM   | 3         | 1.09%   |
| LPDDR3  | 3         | 1.09%   |
| DDR     | 2         | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 150       | 55.15%  |
| SODIMM       | 114       | 41.91%  |
| Row Of Chips | 3         | 1.1%    |
| Chip         | 3         | 1.1%    |
| Unknown      | 2         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 113       | 39.37%  |
| 8192  | 105       | 36.59%  |
| 2048  | 38        | 13.24%  |
| 16384 | 20        | 6.97%   |
| 32768 | 5         | 1.74%   |
| 1024  | 5         | 1.74%   |
| 65536 | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 110       | 37.93%  |
| 1333    | 42        | 14.48%  |
| 2400    | 23        | 7.93%   |
| 2133    | 21        | 7.24%   |
| 2667    | 20        | 6.9%    |
| 800     | 10        | 3.45%   |
| 3200    | 8         | 2.76%   |
| 1867    | 8         | 2.76%   |
| 667     | 8         | 2.76%   |
| 1334    | 6         | 2.07%   |
| 2666    | 5         | 1.72%   |
| 1067    | 5         | 1.72%   |
| 3600    | 4         | 1.38%   |
| 1066    | 4         | 1.38%   |
| Unknown | 3         | 1.03%   |
| 2933    | 2         | 0.69%   |
| 533     | 2         | 0.69%   |
| 65535   | 1         | 0.34%   |
| 4267    | 1         | 0.34%   |
| 3534    | 1         | 0.34%   |
| 2600    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1800    | 1         | 0.34%   |
| 933     | 1         | 0.34%   |
| 333     | 1         | 0.34%   |
| 133     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1200 | 1         | 50%     |
| HP DeskJet 5850c | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 24.14%  |
| Realtek Semiconductor                  | 7         | 12.07%  |
| Logitech                               | 7         | 12.07%  |
| Acer                                   | 4         | 6.9%    |
| Z-Star Microelectronics                | 3         | 5.17%   |
| Suyin                                  | 3         | 5.17%   |
| IMC Networks                           | 3         | 5.17%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.17%   |
| Sunplus Innovation Technology          | 2         | 3.45%   |
| Silicon Motion                         | 2         | 3.45%   |
| Lite-On Technology                     | 2         | 3.45%   |
| Apple                                  | 2         | 3.45%   |
| Syntek                                 | 1         | 1.72%   |
| Microdia                               | 1         | 1.72%   |
| Lenovo                                 | 1         | 1.72%   |
| Creative Technology                    | 1         | 1.72%   |
| ARC International                      | 1         | 1.72%   |
| Alcor Micro                            | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 6.78%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 5.08%   |
| Chicony Integrated Camera                                                | 3         | 5.08%   |
| Realtek USB 2 Webcam                                                     | 2         | 3.39%   |
| Logitech Webcam C930e                                                    | 2         | 3.39%   |
| Logitech Labtec Webcam Pro                                               | 2         | 3.39%   |
| Logitech HD Pro Webcam C920                                              | 2         | 3.39%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 3.39%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 2         | 3.39%   |
| Chicony Integrated Camera [ThinkPad]                                     | 2         | 3.39%   |
| Apple FaceTime HD Camera                                                 | 2         | 3.39%   |
| Z-Star WebCam SC-03FFL11739P                                             | 1         | 1.69%   |
| Z-Star Webcam                                                            | 1         | 1.69%   |
| Z-Star Namuga 1.3M Webcam                                                | 1         | 1.69%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera                            | 1         | 1.69%   |
| Suyin Laptop_Integrated_Webcam_3M                                        | 1         | 1.69%   |
| Suyin Acer Crystal Eye webcam                                            | 1         | 1.69%   |
| Suyin 1.3M HD Webcam                                                     | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                                    | 1         | 1.69%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.69%   |
| Silicon Motion 300k Pixel Camera                                         | 1         | 1.69%   |
| Realtek Realtek USB2.0 PC Camera                                         | 1         | 1.69%   |
| Microdia Integrated Webcam                                               | 1         | 1.69%   |
| Logitech Webcam C310                                                     | 1         | 1.69%   |
| Logitech B525 HD Webcam                                                  | 1         | 1.69%   |
| Lite-On Integrated Camera                                                | 1         | 1.69%   |
| Lite-On HP HD Camera                                                     | 1         | 1.69%   |
| Lenovo Integrated Webcam                                                 | 1         | 1.69%   |
| IMC Networks Integrated Webcam                                           | 1         | 1.69%   |
| Creative Webcam Live! Motion                                             | 1         | 1.69%   |
| Chicony Webcam                                                           | 1         | 1.69%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 1.69%   |
| Chicony Thinkpad T430 camera                                             | 1         | 1.69%   |
| Chicony Chicony USB 2.0 Camera                                           | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera           | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.69%   |
| ARC International Camera                                                 | 1         | 1.69%   |
| Alcor Micro USB 2.0 Web Camera                                           | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 125       | 39.43%  |
| 1     | 117       | 36.91%  |
| 2     | 47        | 14.83%  |
| 3     | 19        | 5.99%   |
| 4     | 7         | 2.21%   |
| 5     | 2         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 153       | 57.09%  |
| Bluetooth                | 29        | 10.82%  |
| Net/wireless             | 26        | 9.7%    |
| Firewire controller      | 17        | 6.34%   |
| Card reader              | 16        | 5.97%   |
| Fingerprint reader       | 10        | 3.73%   |
| Sound                    | 5         | 1.87%   |
| Network                  | 3         | 1.12%   |
| Graphics card            | 3         | 1.12%   |
| Storage/raid             | 2         | 0.75%   |
| Storage                  | 2         | 0.75%   |
| Net/ethernet             | 2         | 0.75%   |

