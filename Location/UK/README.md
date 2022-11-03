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

Total: 561

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0W3F1J A00                  | Mini pc     | [7c95a69cc9](https://bsd-hardware.info/?probe=7c95a69cc9) | Nov 02, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [70cc64ba78](https://bsd-hardware.info/?probe=70cc64ba78) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| HP            | 8103 A01                    | Mini pc     | [9017d1ac90](https://bsd-hardware.info/?probe=9017d1ac90) | Oct 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [69a9ae7bde](https://bsd-hardware.info/?probe=69a9ae7bde) | Oct 25, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| ASRock        | J3355M                      | Desktop     | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
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
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [d5773cd8b3](https://bsd-hardware.info/?probe=d5773cd8b3) | May 16, 2022 |
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
| Unknown       | Unknown                     | Desktop     | [3b256304a0](https://bsd-hardware.info/?probe=3b256304a0) | Apr 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [6f4c78b7db](https://bsd-hardware.info/?probe=6f4c78b7db) | Apr 23, 2022 |
| Dell          | 0N051F A01                  | Server      | [0784468d7a](https://bsd-hardware.info/?probe=0784468d7a) | Apr 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3813b46bc1](https://bsd-hardware.info/?probe=3813b46bc1) | Apr 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a2fc9672d6](https://bsd-hardware.info/?probe=a2fc9672d6) | Apr 22, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [3322ad9dac](https://bsd-hardware.info/?probe=3322ad9dac) | Apr 20, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [aa48329066](https://bsd-hardware.info/?probe=aa48329066) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [754d45f24f](https://bsd-hardware.info/?probe=754d45f24f) | Apr 11, 2022 |
| Jetway        | 1.0                         | Desktop     | [0048067292](https://bsd-hardware.info/?probe=0048067292) | Apr 11, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [f4098d352f](https://bsd-hardware.info/?probe=f4098d352f) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
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
| AMI           | Aptio CRB                   | Mini pc     | [a25c6f603c](https://bsd-hardware.info/?probe=a25c6f603c) | Mar 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9913acc698](https://bsd-hardware.info/?probe=9913acc698) | Mar 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e58663aeb0](https://bsd-hardware.info/?probe=e58663aeb0) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b49ac0cf2](https://bsd-hardware.info/?probe=9b49ac0cf2) | Mar 23, 2022 |
| Intel         | DH61CR AAG14064-209         | Desktop     | [3812666505](https://bsd-hardware.info/?probe=3812666505) | Mar 23, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [87289f0c36](https://bsd-hardware.info/?probe=87289f0c36) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [8870903766](https://bsd-hardware.info/?probe=8870903766) | Mar 20, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c9fb46b179](https://bsd-hardware.info/?probe=c9fb46b179) | Mar 19, 2022 |
| HP            | 8592                        | Desktop     | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [d28bef2c37](https://bsd-hardware.info/?probe=d28bef2c37) | Mar 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [72b461ded3](https://bsd-hardware.info/?probe=72b461ded3) | Mar 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [10a235fe8f](https://bsd-hardware.info/?probe=10a235fe8f) | Mar 13, 2022 |
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
| HP            | ProLiant DL380 G7           | Server      | [55716e7c8b](https://bsd-hardware.info/?probe=55716e7c8b) | Jan 17, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | Notebook    | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
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
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [de6d713222](https://bsd-hardware.info/?probe=de6d713222) | Jan 05, 2022 |
| PC Engines    | APU                         | Desktop     | [efe2fbd850](https://bsd-hardware.info/?probe=efe2fbd850) | Jan 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [c3c1529f86](https://bsd-hardware.info/?probe=c3c1529f86) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [90919a642f](https://bsd-hardware.info/?probe=90919a642f) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| Dell          | 0N051F A01                  | Server      | [071ad110ab](https://bsd-hardware.info/?probe=071ad110ab) | Dec 01, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [67556468e3](https://bsd-hardware.info/?probe=67556468e3) | Nov 30, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [71f763e932](https://bsd-hardware.info/?probe=71f763e932) | Nov 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [99ceb827fe](https://bsd-hardware.info/?probe=99ceb827fe) | Nov 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [53e6ac863a](https://bsd-hardware.info/?probe=53e6ac863a) | Nov 18, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [56cd34ffef](https://bsd-hardware.info/?probe=56cd34ffef) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [8451595212](https://bsd-hardware.info/?probe=8451595212) | Nov 16, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [e0c3737f7c](https://bsd-hardware.info/?probe=e0c3737f7c) | Nov 15, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a2bbadf4a5](https://bsd-hardware.info/?probe=a2bbadf4a5) | Nov 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [f0c5f5ef97](https://bsd-hardware.info/?probe=f0c5f5ef97) | Nov 09, 2021 |
| ASUSTek       | 1001P                       | Notebook    | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
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
| HP            | ProLiant DL380 G7           | Server      | [4ecdb6038a](https://bsd-hardware.info/?probe=4ecdb6038a) | Oct 10, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4b25e8e063](https://bsd-hardware.info/?probe=4b25e8e063) | Oct 10, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [40aba3842c](https://bsd-hardware.info/?probe=40aba3842c) | Oct 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [357b9d3ad2](https://bsd-hardware.info/?probe=357b9d3ad2) | Sep 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [cc7d3fa6a3](https://bsd-hardware.info/?probe=cc7d3fa6a3) | Sep 26, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [dc09f7f7cb](https://bsd-hardware.info/?probe=dc09f7f7cb) | Sep 25, 2021 |
| ASRock        | J3455M                      | Desktop     | [411b04cbba](https://bsd-hardware.info/?probe=411b04cbba) | Sep 25, 2021 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [31a63f86a2](https://bsd-hardware.info/?probe=31a63f86a2) | Sep 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [462d25d041](https://bsd-hardware.info/?probe=462d25d041) | Sep 19, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [63a24ea67f](https://bsd-hardware.info/?probe=63a24ea67f) | Sep 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [dcd383c684](https://bsd-hardware.info/?probe=dcd383c684) | Sep 12, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [016e4443a0](https://bsd-hardware.info/?probe=016e4443a0) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8ce323def8](https://bsd-hardware.info/?probe=8ce323def8) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | 0XDN97 A09                  | Server      | [4668ce0e56](https://bsd-hardware.info/?probe=4668ce0e56) | Sep 02, 2021 |
| HPE           | ML10Gen9                    | Server      | [d8a8039f9d](https://bsd-hardware.info/?probe=d8a8039f9d) | Aug 31, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [2499806edc](https://bsd-hardware.info/?probe=2499806edc) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
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
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
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
| Unknown       | Unknown                     | Desktop     | [5393389555](https://bsd-hardware.info/?probe=5393389555) | Apr 05, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
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
| Toshiba       | Satellite L50-C             | Notebook    | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [5c09abed71](https://bsd-hardware.info/?probe=5c09abed71) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [c79ea5055f](https://bsd-hardware.info/?probe=c79ea5055f) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [222778ae2b](https://bsd-hardware.info/?probe=222778ae2b) | Feb 05, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [09f8c3657f](https://bsd-hardware.info/?probe=09f8c3657f) | Feb 04, 2021 |
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
| OPNsense 20.7.8      | 16        | 3.79%   |
| FreeBSD 13.0         | 14        | 3.32%   |
| helloSystem 0.7.0    | 13        | 3.08%   |
| helloSystem 0.5.0    | 12        | 2.84%   |
| OPNsense 22.1        | 11        | 2.61%   |
| OPNsense 21.7.7      | 11        | 2.61%   |
| OPNsense 21.1.5      | 11        | 2.61%   |
| FreeBSD 14.0-CURRENT | 11        | 2.61%   |
| OPNsense 22.7.4      | 10        | 2.37%   |
| OPNsense 22.1.6      | 10        | 2.37%   |
| helloSystem 0.4.0    | 10        | 2.37%   |
| OPNsense 21.7.3      | 9         | 2.13%   |
| OPNsense 21.7.1      | 9         | 2.13%   |
| OPNsense 21.1.1      | 9         | 2.13%   |
| OPNsense 21.1        | 9         | 2.13%   |
| GhostBSD 20.04.02    | 9         | 2.13%   |
| OPNsense 22.7.6      | 8         | 1.9%    |
| OPNsense 22.7.2      | 8         | 1.9%    |
| OPNsense 22.1.10     | 8         | 1.9%    |
| OPNsense 21.1.7      | 8         | 1.9%    |
| OpenBSD 6.8          | 8         | 1.9%    |
| OPNsense 22.1.8      | 7         | 1.66%   |
| OPNsense 21.1.4      | 7         | 1.66%   |
| OPNsense 21.1.3      | 7         | 1.66%   |
| OPNsense 21.1.2      | 7         | 1.66%   |
| FreeBSD 12.2         | 7         | 1.66%   |
| OPNsense 22.1.4      | 6         | 1.42%   |
| OPNsense 21.7.8      | 6         | 1.42%   |
| FreeBSD 13.0-STABLE  | 6         | 1.42%   |
| OPNsense 22.1.9      | 5         | 1.18%   |
| OPNsense 22.1.3      | 5         | 1.18%   |
| OPNsense 22.1.2      | 5         | 1.18%   |
| OPNsense 21.7.2      | 5         | 1.18%   |
| OPNsense 21.1.6      | 5         | 1.18%   |
| FreeBSD 12.2-p3      | 5         | 1.18%   |
| OPNsense 21.7.5      | 4         | 0.95%   |
| OPNsense 21.1.8      | 4         | 0.95%   |
| OpenBSD 7.1          | 4         | 0.95%   |
| helloSystem 0.6.0    | 4         | 0.95%   |
| FreeBSD 13.1         | 4         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 164       | 50.77%  |
| FreeBSD     | 69        | 21.36%  |
| helloSystem | 43        | 13.31%  |
| OpenBSD     | 19        | 5.88%   |
| GhostBSD    | 13        | 4.02%   |
| NomadBSD    | 7         | 2.17%   |
| NetBSD      | 4         | 1.24%   |
| XigmaNAS    | 1         | 0.31%   |
| pfSense     | 1         | 0.31%   |
| FuryBSD     | 1         | 0.31%   |
| DragonFly   | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 307       | 97.46%  |
| arm64 | 5         | 1.59%   |
| i386  | 2         | 0.63%   |
| riscv | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 197       | 60.99%  |
| helloDesktop     | 45        | 13.93%  |
| KDE5             | 20        | 6.19%   |
| XFCE             | 15        | 4.64%   |
| MATE             | 14        | 4.33%   |
| Openbox          | 7         | 2.17%   |
| fvwm             | 7         | 2.17%   |
| GNOME            | 5         | 1.55%   |
| i3               | 3         | 0.93%   |
| Cinnamon         | 3         | 0.93%   |
| TWM              | 1         | 0.31%   |
| PekWM            | 1         | 0.31%   |
| Metacity (Marco) | 1         | 0.31%   |
| Enlightenment    | 1         | 0.31%   |
| DWM              | 1         | 0.31%   |
| CDE              | 1         | 0.31%   |
| AwesomeWM        | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 199       | 62.78%  |
| X11     | 115       | 36.28%  |
| Wayland | 3         | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 225       | 69.44%  |
| SLiM    | 56        | 17.28%  |
| SDDM    | 22        | 6.79%   |
| LightDM | 15        | 4.63%   |
| XDM     | 4         | 1.23%   |
| Ly      | 1         | 0.31%   |
| GDM     | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 204       | 62.01%  |
| en_US           | 53        | 16.11%  |
| C               | 45        | 13.68%  |
| en_GB           | 21        | 6.38%   |
| ru_RU           | 2         | 0.61%   |
| en_GB.US-ASCII  | 2         | 0.61%   |
| it_CH           | 1         | 0.3%    |
| en_GB.ISO8859-1 | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 267       | 83.44%  |
| BIOS | 53        | 16.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 177       | 54.8%   |
| Zfs     | 117       | 36.22%  |
| Ffs     | 19        | 5.88%   |
| Cd9660  | 8         | 2.48%   |
| Hammer2 | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 292       | 92.11%  |
| MBR     | 18        | 5.68%   |
| Unknown | 6         | 1.89%   |
| BSD     | 1         | 0.32%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 48        | 15.24%  |
| Hewlett-Packard         | 30        | 9.52%   |
| Lenovo                  | 29        | 9.21%   |
| ASUSTek Computer        | 22        | 6.98%   |
| Unknown                 | 21        | 6.67%   |
| Intel                   | 19        | 6.03%   |
| Gigabyte Technology     | 18        | 5.71%   |
| ASRock                  | 12        | 3.81%   |
| AMI                     | 11        | 3.49%   |
| Apple                   | 9         | 2.86%   |
| PC Engines              | 8         | 2.54%   |
| Shuttle                 | 6         | 1.9%    |
| Protectli               | 6         | 1.9%    |
| MSI                     | 6         | 1.9%    |
| Fujitsu                 | 5         | 1.59%   |
| Deciso                  | 5         | 1.59%   |
| Toshiba                 | 4         | 1.27%   |
| Samsung Electronics     | 4         | 1.27%   |
| Biostar                 | 3         | 0.95%   |
| Acer                    | 3         | 0.95%   |
| ZOTAC                   | 2         | 0.63%   |
| Yanling                 | 2         | 0.63%   |
| Supermicro              | 2         | 0.63%   |
| Raspberry Pi Foundation | 2         | 0.63%   |
| Inventec                | 2         | 0.63%   |
| HUAWEI                  | 2         | 0.63%   |
| HPE                     | 2         | 0.63%   |
| Winston Marriot         | 1         | 0.32%   |
| TUXEDO                  | 1         | 0.32%   |
| System76                | 1         | 0.32%   |
| Sophos                  | 1         | 0.32%   |
| Sony UK                 | 1         | 0.32%   |
| Sony                    | 1         | 0.32%   |
| Silver Peak Systems     | 1         | 0.32%   |
| Seeed Studio            | 1         | 0.32%   |
| Quanmax                 | 1         | 0.32%   |
| QOTOM                   | 1         | 0.32%   |
| Pegatron                | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| PAIQ                    | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 21        | 6.67%   |
| AMI Aptio CRB                       | 9         | 2.86%   |
| Intel Q3XXG4-P V1.0                 | 8         | 2.54%   |
| PC Engines APU2                     | 5         | 1.59%   |
| Dell Wyse 5070 Extended Thin Client | 4         | 1.27%   |
| ASUS All Series                     | 4         | 1.27%   |
| Protectli FW4B                      | 3         | 0.95%   |
| HP t730 Thin Client                 | 3         | 0.95%   |
| HP EliteBook 8570p                  | 3         | 0.95%   |
| Dell OptiPlex 7010                  | 3         | 0.95%   |
| Dell OptiPlex 3020                  | 3         | 0.95%   |
| Yanling YL-KBR6L                    | 2         | 0.63%   |
| RPi Raspberry Pi                    | 2         | 0.63%   |
| Protectli FW6                       | 2         | 0.63%   |
| PC Engines apu4                     | 2         | 0.63%   |
| Lenovo ThinkCentre M920s 10SJ0041UK | 2         | 0.63%   |
| HP Z600 Workstation                 | 2         | 0.63%   |
| HP t620 PLUS Quad Core TC           | 2         | 0.63%   |
| HP ProLiant DL360 Gen9              | 2         | 0.63%   |
| Gigabyte B450M DS3H                 | 2         | 0.63%   |
| Dell XPS 13 9343                    | 2         | 0.63%   |
| Dell PowerEdge R610                 | 2         | 0.63%   |
| Dell PowerEdge R210 II              | 2         | 0.63%   |
| Dell PowerEdge R210                 | 2         | 0.63%   |
| Dell OptiPlex 790                   | 2         | 0.63%   |
| Dell OptiPlex 760                   | 2         | 0.63%   |
| Dell OptiPlex 390                   | 2         | 0.63%   |
| Dell Inspiron 3793                  | 2         | 0.63%   |
| Deciso NetBoard-A10                 | 2         | 0.63%   |
| ASUS ZenBook S UX391UA              | 2         | 0.63%   |
| ASUS ROG STRIX X570-E GAMING        | 2         | 0.63%   |
| ASUS H110M-PLUS                     | 2         | 0.63%   |
| ASRock B550 Phantom Gaming 4        | 2         | 0.63%   |
| ZOTAC ZBOX-CI329NANO                | 1         | 0.32%   |
| ZOTAC ZBOX-CI323NANO                | 1         | 0.32%   |
| Winston Marriot PICO PC(R)          | 1         | 0.32%   |
| TUXEDO Aura 15 Gen1                 | 1         | 0.32%   |
| Toshiba TECRA M11                   | 1         | 0.32%   |
| Toshiba Satellite Pro U400          | 1         | 0.32%   |
| Toshiba Satellite L50-C             | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 21        | 6.67%   |
| Lenovo ThinkPad     | 17        | 5.4%    |
| Dell OptiPlex       | 17        | 5.4%    |
| Dell PowerEdge      | 14        | 4.44%   |
| Lenovo ThinkCentre  | 9         | 2.86%   |
| AMI Aptio           | 9         | 2.86%   |
| Intel Q3XXG4-P      | 8         | 2.54%   |
| HP ProLiant         | 6         | 1.9%    |
| PC Engines APU2     | 5         | 1.59%   |
| Dell Latitude       | 5         | 1.59%   |
| Dell Wyse           | 4         | 1.27%   |
| ASUS ROG            | 4         | 1.27%   |
| ASUS PRIME          | 4         | 1.27%   |
| ASUS All            | 4         | 1.27%   |
| Toshiba Satellite   | 3         | 0.95%   |
| Protectli FW4B      | 3         | 0.95%   |
| HP t730             | 3         | 0.95%   |
| HP Pavilion         | 3         | 0.95%   |
| HP EliteBook        | 3         | 0.95%   |
| Dell Inspiron       | 3         | 0.95%   |
| Apple MacBookPro5   | 3         | 0.95%   |
| Acer Aspire         | 3         | 0.95%   |
| Yanling YL-KBR6L    | 2         | 0.63%   |
| RPi Raspberry       | 2         | 0.63%   |
| Protectli FW6       | 2         | 0.63%   |
| PC Engines apu4     | 2         | 0.63%   |
| HP Z600             | 2         | 0.63%   |
| HP t620             | 2         | 0.63%   |
| HP ProDesk          | 2         | 0.63%   |
| HP EliteDesk        | 2         | 0.63%   |
| Gigabyte H61M-DS2   | 2         | 0.63%   |
| Gigabyte B450M      | 2         | 0.63%   |
| Fujitsu FUTRO       | 2         | 0.63%   |
| Fujitsu ESPRIMO     | 2         | 0.63%   |
| Dell XPS            | 2         | 0.63%   |
| Dell Precision      | 2         | 0.63%   |
| Deciso NetBoard-A10 | 2         | 0.63%   |
| Deciso Netboard     | 2         | 0.63%   |
| ASUS ZenBook        | 2         | 0.63%   |
| ASUS P8Z77-V        | 2         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 35        | 11.11%  |
| 2020    | 34        | 10.79%  |
| 2016    | 33        | 10.48%  |
| 2014    | 28        | 8.89%   |
| 2019    | 26        | 8.25%   |
| 2013    | 24        | 7.62%   |
| 2021    | 23        | 7.3%    |
| 2015    | 23        | 7.3%    |
| 2011    | 17        | 5.4%    |
| 2012    | 15        | 4.76%   |
| 2010    | 15        | 4.76%   |
| 2009    | 12        | 3.81%   |
| 2017    | 11        | 3.49%   |
| 2022    | 6         | 1.9%    |
| Unknown | 6         | 1.9%    |
| 2008    | 4         | 1.27%   |
| 2007    | 3         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 179       | 56.83%  |
| Notebook       | 76        | 24.13%  |
| Mini pc        | 28        | 8.89%   |
| Server         | 22        | 6.98%   |
| Firewall       | 4         | 1.27%   |
| System on chip | 3         | 0.95%   |
| All in one     | 2         | 0.63%   |
| Convertible    | 1         | 0.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 303       | 96.19%  |
| Yes  | 12        | 3.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 140       | 44.16%  |
| 4.01-8.0        | 68        | 21.45%  |
| 16.01-24.0      | 60        | 18.93%  |
| 32.01-64.0      | 19        | 5.99%   |
| 2.01-3.0        | 11        | 3.47%   |
| 64.01-256.0     | 9         | 2.84%   |
| 3.01-4.0        | 3         | 0.95%   |
| 24.01-32.0      | 3         | 0.95%   |
| 0.51-1.0        | 2         | 0.63%   |
| More than 256.0 | 1         | 0.32%   |
| Unknown         | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 190       | 57.4%   |
| 0.51-1.0    | 80        | 24.17%  |
| 1.01-2.0    | 25        | 7.55%   |
| 2.01-3.0    | 12        | 3.63%   |
| 3.01-4.0    | 7         | 2.11%   |
| 4.01-8.0    | 5         | 1.51%   |
| Unknown     | 4         | 1.21%   |
| 24.01-32.0  | 2         | 0.6%    |
| 8.01-16.0   | 2         | 0.6%    |
| 32.01-64.0  | 1         | 0.3%    |
| 64.01-256.0 | 1         | 0.3%    |
| 16.01-24.0  | 1         | 0.3%    |
| 0           | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 66.97%  |
| 2      | 48        | 14.55%  |
| 0      | 26        | 7.88%   |
| 3      | 13        | 3.94%   |
| 5      | 7         | 2.12%   |
| 4      | 7         | 2.12%   |
| 8      | 3         | 0.91%   |
| 6      | 2         | 0.61%   |
| 17     | 1         | 0.3%    |
| 14     | 1         | 0.3%    |
| 7      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 244       | 76.25%  |
| Yes       | 76        | 23.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 93.33%  |
| No        | 21        | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 188       | 59.12%  |
| Yes       | 130       | 40.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 240       | 75.24%  |
| Yes       | 79        | 24.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 315       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 33        | 9.14%   |
| Glasgow             | 8         | 2.22%   |
| Brighton            | 7         | 1.94%   |
| Newcastle upon Tyne | 6         | 1.66%   |
| Watford             | 5         | 1.39%   |
| Swindon             | 5         | 1.39%   |
| Kensington          | 5         | 1.39%   |
| Cambridge           | 5         | 1.39%   |
| Stourbridge         | 4         | 1.11%   |
| Sheffield           | 4         | 1.11%   |
| Poplar              | 4         | 1.11%   |
| Milton Keynes       | 4         | 1.11%   |
| Leeds               | 4         | 1.11%   |
| Islington           | 4         | 1.11%   |
| Hull                | 4         | 1.11%   |
| Bristol             | 4         | 1.11%   |
| York                | 3         | 0.83%   |
| Wolverhampton       | 3         | 0.83%   |
| Wittersham          | 3         | 0.83%   |
| Southampton         | 3         | 0.83%   |
| Scunthorpe          | 3         | 0.83%   |
| Ruthin              | 3         | 0.83%   |
| Notting Hill Gate   | 3         | 0.83%   |
| Mansfield           | 3         | 0.83%   |
| Manchester          | 3         | 0.83%   |
| Malton              | 3         | 0.83%   |
| Liverpool           | 3         | 0.83%   |
| Leicester           | 3         | 0.83%   |
| Leatherhead         | 3         | 0.83%   |
| Greenwich           | 3         | 0.83%   |
| Egham               | 3         | 0.83%   |
| City of London      | 3         | 0.83%   |
| Birmingham          | 3         | 0.83%   |
| Andover             | 3         | 0.83%   |
| Worthing            | 2         | 0.55%   |
| Telford             | 2         | 0.55%   |
| Stoke-on-Trent      | 2         | 0.55%   |
| Stoke Newington     | 2         | 0.55%   |
| Slough              | 2         | 0.55%   |
| Rotherham           | 2         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 112    | 16.67%  |
| WDC                 | 43        | 66     | 11.75%  |
| Seagate             | 35        | 90     | 9.56%   |
| Kingston            | 28        | 42     | 7.65%   |
| Crucial             | 27        | 39     | 7.38%   |
| Toshiba             | 18        | 52     | 4.92%   |
| SanDisk             | 18        | 22     | 4.92%   |
| Intel               | 12        | 15     | 3.28%   |
| Transcend           | 10        | 14     | 2.73%   |
| Hitachi             | 10        | 13     | 2.73%   |
| Phison              | 8         | 12     | 2.19%   |
| Hoodisk             | 8         | 13     | 2.19%   |
| HGST                | 8         | 24     | 2.19%   |
| SK hynix            | 6         | 8      | 1.64%   |
| LITEONIT            | 5         | 6      | 1.37%   |
| Hewlett-Packard     | 5         | 18     | 1.37%   |
| Micron Technology   | 4         | 5      | 1.09%   |
| FORESEE             | 4         | 4      | 1.09%   |
| Apacer              | 4         | 5      | 1.09%   |
| A-DATA Technology   | 4         | 7      | 1.09%   |
| PNY                 | 3         | 11     | 0.82%   |
| OCZ                 | 3         | 4      | 0.82%   |
| NVMe                | 3         | 3      | 0.82%   |
| Corsair             | 3         | 3      | 0.82%   |
| China               | 3         | 3      | 0.82%   |
| Apple               | 3         | 4      | 0.82%   |
| Patriot             | 2         | 5      | 0.55%   |
| OPENBSD             | 2         | 2      | 0.55%   |
| Netac               | 2         | 6      | 0.55%   |
| Lexar               | 2         | 2      | 0.55%   |
| Intenso             | 2         | 2      | 0.55%   |
| Integral            | 2         | 4      | 0.55%   |
| Zheino              | 1         | 1      | 0.27%   |
| XUM                 | 1         | 1      | 0.27%   |
| TCSUNBOW            | 1         | 2      | 0.27%   |
| SPCC                | 1         | 1      | 0.27%   |
| Solid State Storage | 1         | 1      | 0.27%   |
| SATA3 60            | 1         | 1      | 0.27%   |
| OWC                 | 1         | 1      | 0.27%   |
| ORTIAL              | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 5         | 1.26%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.26%   |
| Kingston SUV500MS120G 120GB          | 5         | 1.26%   |
| Kingston SA400S37240G 240GB          | 5         | 1.26%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 1.26%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.01%   |
| Hoodisk SSD 64GB                     | 4         | 1.01%   |
| HGST HTS725050A7E630 500GB           | 4         | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 0.75%   |
| Seagate ST3500418AS 500GB            | 3         | 0.75%   |
| Samsung HM251JX 250GB                | 3         | 0.75%   |
| Phison Sabrent 2TB                   | 3         | 0.75%   |
| HP RAID 1(1+0) 2TB                   | 3         | 0.75%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.75%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.75%   |
| WDC WDS250G2B0B-00YS70 250GB         | 2         | 0.5%    |
| WDC WD1600BEVT-80A23T0 160GB         | 2         | 0.5%    |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 0.5%    |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2         | 0.5%    |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.5%    |
| Transcend TS128GMSA370 128GB         | 2         | 0.5%    |
| Toshiba HDWE140 4TB                  | 2         | 0.5%    |
| Seagate ST8000VN0022-2EL112 8TB      | 2         | 0.5%    |
| Seagate ST8000AS0002-1NA17Z 8TB      | 2         | 0.5%    |
| Seagate ST4000NE001-2MA101 4TB       | 2         | 0.5%    |
| Seagate ST3500312CS 500GB            | 2         | 0.5%    |
| Seagate ST3160318AS 160GB            | 2         | 0.5%    |
| Seagate ST3160310CS 160GB            | 2         | 0.5%    |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.5%    |
| SanDisk SSD PLUS 480GB               | 2         | 0.5%    |
| SanDisk SDSSDA120G 120GB             | 2         | 0.5%    |
| SanDisk SDCFHS-016G                  | 2         | 0.5%    |
| Samsung SSD PM851 M.2 2280 256GB     | 2         | 0.5%    |
| Samsung SSD PM810 2.5-inch 7mm 256GB | 2         | 0.5%    |
| Samsung SSD 860 EVO 250GB            | 2         | 0.5%    |
| Samsung SSD 850 PRO 256GB            | 2         | 0.5%    |
| Samsung SSD 840 EVO 250GB            | 2         | 0.5%    |
| Samsung SSD 750 EVO 250GB            | 2         | 0.5%    |
| Samsung MZVLW512HMJP-00000 512GB     | 2         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 90     | 30.17%  |
| WDC                 | 32        | 48     | 27.59%  |
| Toshiba             | 13        | 40     | 11.21%  |
| Hitachi             | 10        | 13     | 8.62%   |
| HGST                | 8         | 24     | 6.9%    |
| Samsung Electronics | 6         | 6      | 5.17%   |
| Hewlett-Packard     | 5         | 18     | 4.31%   |
| OPENBSD             | 2         | 2      | 1.72%   |
| NVMe                | 2         | 2      | 1.72%   |
| Fujitsu             | 1         | 6      | 0.86%   |
| Dell                | 1         | 2      | 0.86%   |
| Apple               | 1         | 1      | 0.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 81     | 19.72%  |
| Kingston            | 28        | 42     | 12.84%  |
| Crucial             | 25        | 37     | 11.47%  |
| SanDisk             | 18        | 22     | 8.26%   |
| Intel               | 10        | 12     | 4.59%   |
| WDC                 | 9         | 13     | 4.13%   |
| Hoodisk             | 8         | 13     | 3.67%   |
| Transcend           | 7         | 10     | 3.21%   |
| Phison              | 5         | 6      | 2.29%   |
| LITEONIT            | 5         | 6      | 2.29%   |
| Micron Technology   | 4         | 5      | 1.83%   |
| FORESEE             | 4         | 4      | 1.83%   |
| Apacer              | 4         | 5      | 1.83%   |
| A-DATA Technology   | 4         | 7      | 1.83%   |
| Toshiba             | 3         | 8      | 1.38%   |
| PNY                 | 3         | 9      | 1.38%   |
| OCZ                 | 3         | 4      | 1.38%   |
| Corsair             | 3         | 3      | 1.38%   |
| China               | 3         | 3      | 1.38%   |
| SK hynix            | 2         | 2      | 0.92%   |
| Patriot             | 2         | 5      | 0.92%   |
| Netac               | 2         | 6      | 0.92%   |
| Lexar               | 2         | 2      | 0.92%   |
| Intenso             | 2         | 2      | 0.92%   |
| Integral            | 2         | 4      | 0.92%   |
| Apple               | 2         | 3      | 0.92%   |
| Zheino              | 1         | 1      | 0.46%   |
| XUM                 | 1         | 1      | 0.46%   |
| TCSUNBOW            | 1         | 2      | 0.46%   |
| SPCC                | 1         | 1      | 0.46%   |
| SATA3 60            | 1         | 1      | 0.46%   |
| OWC                 | 1         | 1      | 0.46%   |
| ORTIAL              | 1         | 1      | 0.46%   |
| NVMe                | 1         | 1      | 0.46%   |
| MicroDream          | 1         | 1      | 0.46%   |
| Marvell             | 1         | 1      | 0.46%   |
| LITEON              | 1         | 1      | 0.46%   |
| Kingchuxing         | 1         | 1      | 0.46%   |
| Gigabyte Technology | 1         | 2      | 0.46%   |
| Fordisk             | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 198       | 332    | 60.18%  |
| HDD  | 95        | 252    | 28.88%  |
| NVMe | 36        | 60     | 10.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 267       | 584    | 88.12%  |
| NVMe | 36        | 60     | 11.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 236       | 414    | 77.12%  |
| 0.51-1.0   | 31        | 52     | 10.13%  |
| 1.01-2.0   | 19        | 36     | 6.21%   |
| 3.01-4.0   | 9         | 37     | 2.94%   |
| 4.01-10.0  | 9         | 43     | 2.94%   |
| 2.01-3.0   | 2         | 2      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 136       | 40.36%  |
| 251-500        | 49        | 14.54%  |
| 1-20           | 49        | 14.54%  |
| 21-50          | 35        | 10.39%  |
| 51-100         | 34        | 10.09%  |
| 501-1000       | 19        | 5.64%   |
| 1001-2000      | 7         | 2.08%   |
| Unknown        | 4         | 1.19%   |
| More than 3000 | 3         | 0.89%   |
| 2001-3000      | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 283       | 86.28%  |
| 21-50          | 22        | 6.71%   |
| 51-100         | 8         | 2.44%   |
| 101-250        | 6         | 1.83%   |
| Unknown        | 4         | 1.22%   |
| More than 3000 | 2         | 0.61%   |
| 251-500        | 2         | 0.61%   |
| 2001-3000      | 1         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 10     | 7.14%   |
| Seagate ST3500418AS 500GB                        | 2         | 3      | 3.57%   |
| Seagate ST3160310CS 160GB                        | 2         | 2      | 3.57%   |
| SanDisk SSD PLUS 480GB                           | 2         | 2      | 3.57%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 2         | 3      | 3.57%   |
| Crucial CT525MX300SSD1 528GB                     | 2         | 3      | 3.57%   |
| WDC WD5000AAKX-221CA1 500GB                      | 1         | 1      | 1.79%   |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1         | 1      | 1.79%   |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1         | 4      | 1.79%   |
| WDC WD3200BEVT-22A23T0 320GB                     | 1         | 2      | 1.79%   |
| WDC WD3200AAJS-22B4A0 320GB                      | 1         | 1      | 1.79%   |
| WDC WD30EFRX-68EUZN0 3TB                         | 1         | 1      | 1.79%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 1.79%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 1.79%   |
| WDC WD10JMVW-11AJGS0 1TB                         | 1         | 1      | 1.79%   |
| Transcend TS256GSSD320 256GB                     | 1         | 1      | 1.79%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.79%   |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 1.79%   |
| Toshiba HDWE140 4TB                              | 1         | 8      | 1.79%   |
| Toshiba DT01ACA200 2TB                           | 1         | 1      | 1.79%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 1.79%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.79%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 1.79%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.79%   |
| SanDisk SSD P4 16GB                              | 1         | 1      | 1.79%   |
| SanDisk SDCFHS-016G                              | 1         | 1      | 1.79%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 1      | 1.79%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1         | 1      | 1.79%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 1.79%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.79%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 1.79%   |
| Marvell SATAIII 16GB                             | 1         | 1      | 1.79%   |
| Kingston SV300S37A120G 120GB                     | 1         | 2      | 1.79%   |
| Kingston SV200S3128G 128GB                       | 1         | 1      | 1.79%   |
| Kingchuxing SSD 60GB                             | 1         | 1      | 1.79%   |
| Intel SSDSC2BB120G4 120GB                        | 1         | 2      | 1.79%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.79%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 1.79%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 1.79%   |
| HGST HUS726040ALE610 4TB                         | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 13     | 16.67%  |
| Seagate             | 7         | 8      | 12.96%  |
| Samsung Electronics | 6         | 7      | 11.11%  |
| HGST                | 6         | 22     | 11.11%  |
| Toshiba             | 4         | 12     | 7.41%   |
| SanDisk             | 4         | 4      | 7.41%   |
| Hitachi             | 3         | 3      | 5.56%   |
| Crucial             | 3         | 5      | 5.56%   |
| Kingston            | 2         | 3      | 3.7%    |
| China               | 2         | 2      | 3.7%    |
| A-DATA Technology   | 2         | 3      | 3.7%    |
| Transcend           | 1         | 1      | 1.85%   |
| Micron Technology   | 1         | 1      | 1.85%   |
| Marvell             | 1         | 1      | 1.85%   |
| Kingchuxing         | 1         | 1      | 1.85%   |
| Intel               | 1         | 2      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 13     | 28.13%  |
| Seagate             | 7         | 8      | 21.88%  |
| HGST                | 6         | 22     | 18.75%  |
| Toshiba             | 4         | 12     | 12.5%   |
| Hitachi             | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Apple               | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 61     | 58.49%  |
| SSD  | 21        | 27     | 39.62%  |
| NVMe | 1         | 1      | 1.89%   |

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
| Works    | 254       | 520    | 79.13%  |
| Malfunc  | 50        | 89     | 15.58%  |
| Detected | 16        | 33     | 4.98%   |
| Failed   | 1         | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 231       | 61.76%  |
| AMD                            | 58        | 15.51%  |
| Samsung Electronics            | 18        | 4.81%   |
| Broadcom / LSI                 | 11        | 2.94%   |
| Marvell Technology Group       | 8         | 2.14%   |
| ASMedia Technology             | 8         | 2.14%   |
| SanDisk                        | 6         | 1.6%    |
| Nvidia                         | 6         | 1.6%    |
| Phison Electronics             | 5         | 1.34%   |
| SK hynix                       | 4         | 1.07%   |
| Hewlett-Packard                | 4         | 1.07%   |
| Toshiba                        | 3         | 0.8%    |
| Unknown                        | 3         | 0.8%    |
| Micron/Crucial Technology      | 2         | 0.53%   |
| Adaptec                        | 2         | 0.53%   |
| VIA Technologies               | 1         | 0.27%   |
| Solid State Storage Technology | 1         | 0.27%   |
| Silicon Motion                 | 1         | 0.27%   |
| Silicon Image                  | 1         | 0.27%   |
| Kingston Technology Company    | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40        | 9.59%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 5.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 4.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 16        | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 3.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 3.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12        | 2.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 2.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 2.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 7         | 1.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.68%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.44%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 1.2%    |
| Phison E12 NVMe Controller                                                              | 4         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 0.96%   |
| AMD FCH IDE Controller                                                                  | 4         | 0.96%   |
| Unknown                                                                                 | 4         | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.72%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.72%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3         | 0.72%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.72%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                            | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 262       | 71.39%  |
| NVMe | 41        | 11.17%  |
| IDE  | 35        | 9.54%   |
| RAID | 22        | 5.99%   |
| SCSI | 4         | 1.09%   |
| SAS  | 3         | 0.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 244       | 77.46%  |
| AMD      | 64        | 20.32%  |
| ARM      | 3         | 0.95%   |
| Unknown  | 2         | 0.63%   |
| Research | 1         | 0.32%   |
| 11th     | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz        | 10        | 3.13%   |
| AMD GX-412TC SOC                         | 7         | 2.19%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 5         | 1.57%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 4         | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 1.25%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 4         | 1.25%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4         | 1.25%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 4         | 1.25%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 4         | 1.25%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 4         | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor        | 4         | 1.25%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 3         | 0.94%   |
| Intel CPU Version                        | 3         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.94%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 0.94%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 3         | 0.94%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 3         | 0.94%   |
| Intel Core 2 Duo                         | 3         | 0.94%   |
| Intel Celeron CPU N2940 @ 1.83GHz        | 3         | 0.94%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 3         | 0.94%   |
| AMD Ryzen Embedded V1500B                | 3         | 0.94%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 3         | 0.94%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 3         | 0.94%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.94%   |
| AMD GX-416RA SOC                         | 3         | 0.94%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 2         | 0.63%   |
| Intel Xeon CPU E5530 @ 2.40GHz           | 2         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 0.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 0.63%   |
| Intel Core i7-4500U CPU @ 1.80GHz        | 2         | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GH          | 2         | 0.63%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.63%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 2         | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 2         | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 18.3%   |
| Intel Celeron           | 47        | 14.83%  |
| Intel Core i7           | 40        | 12.62%  |
| Intel Xeon              | 27        | 8.52%   |
| Intel Core i3           | 26        | 8.2%    |
| AMD GX                  | 14        | 4.42%   |
| Intel Core 2 Duo        | 13        | 4.1%    |
| AMD Ryzen 5             | 12        | 3.79%   |
| Other                   | 11        | 3.47%   |
| Intel Atom              | 10        | 3.15%   |
| Intel Pentium           | 7         | 2.21%   |
| Intel Pentium Silver    | 5         | 1.58%   |
| AMD Ryzen 7             | 5         | 1.58%   |
| ARM Cortex              | 3         | 0.95%   |
| AMD Ryzen Embedded      | 3         | 0.95%   |
| AMD Ryzen 3             | 3         | 0.95%   |
| AMD G                   | 3         | 0.95%   |
| AMD FX                  | 3         | 0.95%   |
| AMD A6                  | 3         | 0.95%   |
| Intel Xeon Silver       | 2         | 0.63%   |
| Intel Core i9           | 2         | 0.63%   |
| Intel Core 2 Quad       | 2         | 0.63%   |
| AMD Ryzen 9             | 2         | 0.63%   |
| AMD Athlon              | 2         | 0.63%   |
| AMD A4                  | 2         | 0.63%   |
| Intel Pentium Dual-Core | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| Intel 686-class         | 1         | 0.32%   |
| AMD Ryzen Threadripper  | 1         | 0.32%   |
| AMD Ryzen 7 PRO         | 1         | 0.32%   |
| AMD Phenom II X6        | 1         | 0.32%   |
| AMD Phenom              | 1         | 0.32%   |
| AMD Opteron             | 1         | 0.32%   |
| AMD EPYC                | 1         | 0.32%   |
| AMD E2                  | 1         | 0.32%   |
| AMD Athlon 64 X2        | 1         | 0.32%   |
| AMD A8                  | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 140       | 43.89%  |
| 2       | 107       | 33.54%  |
| Unknown | 18        | 5.64%   |
| 12      | 14        | 4.39%   |
| 6       | 12        | 3.76%   |
| 8       | 11        | 3.45%   |
| 16      | 7         | 2.19%   |
| 24      | 4         | 1.25%   |
| 1       | 3         | 0.94%   |
| 10      | 2         | 0.63%   |
| 128     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 296       | 93.97%  |
| 2       | 11        | 3.49%   |
| Unknown | 8         | 2.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 172       | 54.09%  |
| 2       | 128       | 40.25%  |
| Unknown | 18        | 5.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 36        | 11.39%  |
| Haswell       | 36        | 11.39%  |
| KabyLake      | 30        | 9.49%   |
| SandyBridge   | 25        | 7.91%   |
| IvyBridge     | 22        | 6.96%   |
| Penryn        | 17        | 5.38%   |
| Skylake       | 16        | 5.06%   |
| Goldmont plus | 14        | 4.43%   |
| Zen 2         | 12        | 3.8%    |
| Westmere      | 10        | 3.16%   |
| Broadwell     | 10        | 3.16%   |
| Nehalem       | 9         | 2.85%   |
| Jaguar        | 9         | 2.85%   |
| Unknown       | 9         | 2.85%   |
| Zen 3         | 7         | 2.22%   |
| Puma          | 7         | 2.22%   |
| Goldmont      | 7         | 2.22%   |
| Zen           | 6         | 1.9%    |
| Piledriver    | 5         | 1.58%   |
| Bonnell       | 4         | 1.27%   |
| Bobcat        | 4         | 1.27%   |
| Zen+          | 3         | 0.95%   |
| Steamroller   | 3         | 0.95%   |
| Core          | 3         | 0.95%   |
| K10           | 2         | 0.63%   |
| IceLake       | 2         | 0.63%   |
| Excavator     | 2         | 0.63%   |
| CometLake     | 2         | 0.63%   |
| TigerLake     | 1         | 0.32%   |
| K8 Hammer     | 1         | 0.32%   |
| K10 Llano     | 1         | 0.32%   |
| Bulldozer     | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 194       | 63.19%  |
| AMD                        | 50        | 16.29%  |
| Nvidia                     | 40        | 13.03%  |
| Matrox Electronics Systems | 18        | 5.86%   |
| ASPEED Technology          | 5         | 1.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 6.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 6.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 3.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 3.79%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 10        | 3.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.84%   |
| Intel HD Graphics 500                                                                    | 7         | 2.21%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.89%   |
| Intel HD Graphics 620                                                                    | 6         | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.58%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.58%   |
| Intel HD Graphics 530                                                                    | 5         | 1.58%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 1.58%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 1.58%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 1.58%   |
| Matrox Electronics Systems MGA G200EH                                                    | 4         | 1.26%   |
| Intel HD Graphics 6000                                                                   | 4         | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.95%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.95%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.95%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.95%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.95%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.95%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.95%   |
| AMD Cezanne                                                                              | 3         | 0.95%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.63%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.63%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.63%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 172       | 54.26%  |
| 1 x AMD        | 45        | 14.2%   |
| 1 x Nvidia     | 31        | 9.78%   |
| Other          | 22        | 6.94%   |
| 1 x Matrox     | 18        | 5.68%   |
| 2 x Intel      | 11        | 3.47%   |
| Intel + Nvidia | 7         | 2.21%   |
| 1 x ASPEED     | 5         | 1.58%   |
| Intel + AMD    | 4         | 1.26%   |
| 2 x Nvidia     | 2         | 0.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 271       | 85.49%  |
| Unknown     | 30        | 9.46%   |
| Proprietary | 16        | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 289       | 90.6%   |
| 1.01-2.0   | 8         | 2.51%   |
| 0.51-1.0   | 8         | 2.51%   |
| 3.01-4.0   | 5         | 1.57%   |
| 7.01-8.0   | 4         | 1.25%   |
| 0.01-0.5   | 3         | 0.94%   |
| 5.01-6.0   | 1         | 0.31%   |
| 8.01-16.0  | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 12.75%  |
| Samsung Electronics     | 11        | 10.78%  |
| LG Display              | 11        | 10.78%  |
| Dell                    | 8         | 7.84%   |
| Hewlett-Packard         | 6         | 5.88%   |
| Lenovo                  | 5         | 4.9%    |
| Chimei Innolux          | 5         | 4.9%    |
| Philips                 | 4         | 3.92%   |
| BenQ                    | 4         | 3.92%   |
| AOC                     | 4         | 3.92%   |
| Sharp                   | 3         | 2.94%   |
| Iiyama                  | 3         | 2.94%   |
| BOE                     | 3         | 2.94%   |
| Acer                    | 3         | 2.94%   |
| Pixio                   | 2         | 1.96%   |
| LG Philips              | 2         | 1.96%   |
| HannStar                | 2         | 1.96%   |
| Apple                   | 2         | 1.96%   |
| Vestel Elektronik       | 1         | 0.98%   |
| Sony                    | 1         | 0.98%   |
| SDC                     | 1         | 0.98%   |
| RS                      | 1         | 0.98%   |
| PANDA                   | 1         | 0.98%   |
| OEM                     | 1         | 0.98%   |
| InnoLux Display         | 1         | 0.98%   |
| Goldstar                | 1         | 0.98%   |
| CPT                     | 1         | 0.98%   |
| Chi Mei Optoelectronics | 1         | 0.98%   |
| AVX                     | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch             | 3         | 2.8%    |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 2.8%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 2.8%    |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 1.87%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch           | 2         | 1.87%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 2         | 1.87%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 1.87%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.93%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 0.93%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.93%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 0.93%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch     | 1         | 0.93%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch  | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 1         | 0.93%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 0.93%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                       | 1         | 0.93%   |
| Pixio PX7 Prime HYC2700 2560x1440 600x340mm 27.2-inch                 | 1         | 0.93%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                     | 1         | 0.93%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 0.93%   |
| Philips LCD Monitor 271P4                                             | 1         | 0.93%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 0.93%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.93%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.93%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 0.93%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 0.93%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 33.98%  |
| 1366x768 (WXGA)    | 16        | 15.53%  |
| 1600x900 (HD+)     | 7         | 6.8%    |
| 1280x800 (WXGA)    | 7         | 6.8%    |
| 1920x1200 (WUXGA)  | 5         | 4.85%   |
| 1680x1050 (WSXGA+) | 4         | 3.88%   |
| 3840x2160 (4K)     | 3         | 2.91%   |
| 3200x1800 (QHD+)   | 3         | 2.91%   |
| 2560x1440 (QHD)    | 3         | 2.91%   |
| 1440x900 (WXGA+)   | 3         | 2.91%   |
| 1280x1024 (SXGA)   | 3         | 2.91%   |
| 1024x600           | 3         | 2.91%   |
| Unknown            | 3         | 2.91%   |
| 1920x540           | 2         | 1.94%   |
| 5760x1200          | 1         | 0.97%   |
| 3840x1080          | 1         | 0.97%   |
| 3520x1080          | 1         | 0.97%   |
| 3440x1440          | 1         | 0.97%   |
| 3200x1080          | 1         | 0.97%   |
| 2880x1800          | 1         | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 19.61%  |
| 13      | 18        | 17.65%  |
| 27      | 8         | 7.84%   |
| 19      | 7         | 6.86%   |
| 24      | 6         | 5.88%   |
| 23      | 6         | 5.88%   |
| 12      | 6         | 5.88%   |
| Unknown | 6         | 5.88%   |
| 22      | 4         | 3.92%   |
| 21      | 4         | 3.92%   |
| 17      | 4         | 3.92%   |
| 25      | 2         | 1.96%   |
| 10      | 2         | 1.96%   |
| 49      | 1         | 0.98%   |
| 42      | 1         | 0.98%   |
| 39      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 31      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 14      | 1         | 0.98%   |
| 11      | 1         | 0.98%   |
| 9       | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 29.29%  |
| 501-600     | 20        | 20.2%   |
| 201-300     | 20        | 20.2%   |
| 401-500     | 10        | 10.1%   |
| 351-400     | 8         | 8.08%   |
| Unknown     | 6         | 6.06%   |
| 601-700     | 2         | 2.02%   |
| 801-900     | 1         | 1.01%   |
| 701-800     | 1         | 1.01%   |
| 1001-1500   | 1         | 1.01%   |
| 901-1000    | 1         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 62        | 65.26%  |
| 16/10   | 18        | 18.95%  |
| Unknown | 5         | 5.26%   |
| 5/4     | 4         | 4.21%   |
| 3/2     | 3         | 3.16%   |
| 32/9    | 2         | 2.11%   |
| 21/9    | 1         | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 16        | 16.16%  |
| 81-90          | 12        | 12.12%  |
| 101-110        | 10        | 10.1%   |
| 91-100         | 10        | 10.1%   |
| 301-350        | 8         | 8.08%   |
| 71-80          | 7         | 7.07%   |
| 151-200        | 7         | 7.07%   |
| 61-70          | 6         | 6.06%   |
| Unknown        | 6         | 6.06%   |
| 121-130        | 4         | 4.04%   |
| 41-50          | 3         | 3.03%   |
| 251-300        | 3         | 3.03%   |
| 501-1000       | 3         | 3.03%   |
| 351-500        | 2         | 2.02%   |
| 51-60          | 1         | 1.01%   |
| 141-150        | 1         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 35.35%  |
| 101-120       | 26        | 26.26%  |
| 121-160       | 21        | 21.21%  |
| 161-240       | 8         | 8.08%   |
| Unknown       | 6         | 6.06%   |
| More than 240 | 3         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 220       | 68.97%  |
| 1     | 89        | 27.9%   |
| 2     | 9         | 2.82%   |
| 3     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 215       | 49.88%  |
| Realtek Semiconductor             | 111       | 25.75%  |
| Broadcom                          | 38        | 8.82%   |
| Qualcomm Atheros                  | 24        | 5.57%   |
| Ralink Technology                 | 5         | 1.16%   |
| Nvidia                            | 5         | 1.16%   |
| Marvell Technology Group          | 5         | 1.16%   |
| IMC Networks                      | 4         | 0.93%   |
| Hewlett-Packard                   | 3         | 0.7%    |
| AMD                               | 3         | 0.7%    |
| Sierra Wireless                   | 2         | 0.46%   |
| Ralink                            | 2         | 0.46%   |
| Ericsson Business Mobile Networks | 2         | 0.46%   |
| D-Link System                     | 2         | 0.46%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.23%   |
| Xiaomi                            | 1         | 0.23%   |
| U-Blox                            | 1         | 0.23%   |
| TP-Link                           | 1         | 0.23%   |
| Napatech A/S                      | 1         | 0.23%   |
| Edimax Technology                 | 1         | 0.23%   |
| Bluegiga Technologies             | 1         | 0.23%   |
| Belkin Components                 | 1         | 0.23%   |
| ASUSTek Computer                  | 1         | 0.23%   |
| American Megatrends               | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 93        | 17.45%  |
| Intel I211 Gigabit Network Connection                                         | 49        | 9.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 3.56%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 3%      |
| Intel I350 Gigabit Network Connection                                         | 13        | 2.44%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 13        | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 2.25%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 2.25%   |
| Intel Wireless 7260                                                           | 10        | 1.88%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.88%   |
| Realtek RTL8125 2.5GbE Controller                                             | 9         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.5%    |
| Intel 82576 Gigabit Network Connection                                        | 8         | 1.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 1.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.31%   |
| Intel Wireless 8260                                                           | 6         | 1.13%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.13%   |
| Intel 82583V Gigabit Network Connection                                       | 6         | 1.13%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.13%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.13%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 5         | 0.94%   |
| Intel Wireless 3165                                                           | 5         | 0.94%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.94%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 0.75%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 0.75%   |
| Intel Wireless 3160                                                           | 4         | 0.75%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 0.75%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                                | 4         | 0.75%   |
| Intel Centrino Advanced-N 6200                                                | 4         | 0.75%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 0.75%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 4         | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 4         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                                | 3         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 3         | 0.56%   |
| Intel Wireless 7265                                                           | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 57.35%  |
| Qualcomm Atheros      | 21        | 15.44%  |
| Realtek Semiconductor | 11        | 8.09%   |
| Broadcom              | 8         | 5.88%   |
| Ralink Technology     | 5         | 3.68%   |
| IMC Networks          | 4         | 2.94%   |
| Ralink                | 2         | 1.47%   |
| D-Link System         | 2         | 1.47%   |
| TP-Link               | 1         | 0.74%   |
| Sierra Wireless       | 1         | 0.74%   |
| Edimax Technology     | 1         | 0.74%   |
| Belkin Components     | 1         | 0.74%   |
| ASUSTek Computer      | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 12        | 8.7%    |
| Intel Wireless 7260                                                        | 10        | 7.25%   |
| Intel Wi-Fi 6 AX200                                                        | 8         | 5.8%    |
| Intel Wireless 8260                                                        | 6         | 4.35%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 5         | 3.62%   |
| Intel Wireless 3165                                                        | 5         | 3.62%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 2.9%    |
| Intel Wireless 3160                                                        | 4         | 2.9%    |
| Intel Centrino Advanced-N 6200                                             | 4         | 2.9%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 4         | 2.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 4         | 2.9%    |
| Ralink RT5370 Wireless Adapter                                             | 3         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 2.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 2.17%   |
| Intel Wireless 7265                                                        | 3         | 2.17%   |
| Intel WiFi Link 5100                                                       | 3         | 2.17%   |
| Intel Centrino Ultimate-N 6300                                             | 3         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.45%   |
| Intel Wireless-AC 9260                                                     | 2         | 1.45%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 2         | 1.45%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.45%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.45%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.72%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                              | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 0.72%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.72%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 185       | 54.41%  |
| Realtek Semiconductor    | 104       | 30.59%  |
| Broadcom                 | 32        | 9.41%   |
| Nvidia                   | 5         | 1.47%   |
| Marvell Technology Group | 5         | 1.47%   |
| Qualcomm Atheros         | 4         | 1.18%   |
| AMD                      | 3         | 0.88%   |
| Xiaomi                   | 1         | 0.29%   |
| American Megatrends      | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 93        | 24.41%  |
| Intel I211 Gigabit Network Connection                                         | 49        | 12.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 19        | 4.99%   |
| Intel I210 Gigabit Network Connection                                         | 16        | 4.2%    |
| Intel I350 Gigabit Network Connection                                         | 13        | 3.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 13        | 3.41%   |
| Intel 82574L Gigabit Network Connection                                       | 12        | 3.15%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 2.62%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 2.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 2.1%    |
| Realtek RTL8125 2.5GbE Controller                                             | 7         | 1.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.84%   |
| Intel Ethernet Connection I217-LM                                             | 6         | 1.57%   |
| Intel 82583V Gigabit Network Connection                                       | 6         | 1.57%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.57%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 6         | 1.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 1.31%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 1.05%   |
| Intel Ethernet Connection I219-LM                                             | 4         | 1.05%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.05%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.05%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.79%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 2         | 0.52%   |
| Intel Ethernet Controller X550                                                | 2         | 0.52%   |
| Intel Ethernet Connection I354                                                | 2         | 0.52%   |
| Intel Ethernet Connection I217-V                                              | 2         | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2         | 0.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 2         | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1         | 0.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 294       | 67.12%  |
| WiFi     | 130       | 29.68%  |
| Modem    | 7         | 1.6%    |
| Unknown  | 7         | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 278       | 78.09%  |
| WiFi     | 75        | 21.07%  |
| Modem    | 3         | 0.84%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 110       | 34.48%  |
| 1     | 54        | 16.93%  |
| 4     | 45        | 14.11%  |
| 3     | 40        | 12.54%  |
| 5     | 31        | 9.72%   |
| 6     | 20        | 6.27%   |
| 0     | 6         | 1.88%   |
| 7     | 5         | 1.57%   |
| 8     | 3         | 0.94%   |
| 15    | 1         | 0.31%   |
| 14    | 1         | 0.31%   |
| 12    | 1         | 0.31%   |
| 10    | 1         | 0.31%   |
| 9     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 289       | 88.38%  |
| Yes  | 38        | 11.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 53.16%  |
| Apple                           | 7         | 8.86%   |
| Cambridge Silicon Radio         | 6         | 7.59%   |
| Broadcom                        | 6         | 7.59%   |
| Dell                            | 4         | 5.06%   |
| Realtek Semiconductor           | 3         | 3.8%    |
| ASUSTek Computer                | 3         | 3.8%    |
| Qualcomm Atheros Communications | 2         | 2.53%   |
| IMC Networks                    | 2         | 2.53%   |
| Foxconn / Hon Hai               | 2         | 2.53%   |
| Realtek                         | 1         | 1.27%   |
| Alps Electric                   | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 21        | 26.58%  |
| Intel AX200 Bluetooth                                                               | 8         | 10.13%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 7.59%   |
| Apple Bluetooth Host Controller                                                     | 5         | 6.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.8%    |
| Intel AX201 Bluetooth                                                               | 3         | 3.8%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 3.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.53%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.53%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.27%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 1.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.27%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.27%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 1.27%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                                          | 1         | 1.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.27%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.27%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.27%   |
| Broadcom Bluetooth                                                                  | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.27%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.27%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter                             | 1         | 1.27%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.27%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.27%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 190       | 63.33%  |
| AMD                                  | 62        | 20.67%  |
| Nvidia                               | 31        | 10.33%  |
| SteelSeries ApS                      | 3         | 1%      |
| C-Media Electronics                  | 3         | 1%      |
| Texas Instruments                    | 2         | 0.67%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.33%   |
| Nam Tai E&E Products                 | 1         | 0.33%   |
| Logitech                             | 1         | 0.33%   |
| JMTek                                | 1         | 0.33%   |
| Griffin Technology                   | 1         | 0.33%   |
| GN Netcom                            | 1         | 0.33%   |
| Elgato Systems                       | 1         | 0.33%   |
| Creative Labs                        | 1         | 0.33%   |
| BEHRINGER International              | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 6.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 4.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 4.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 4.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 3.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 3.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 3.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 3.28%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 3.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.73%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.73%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.09%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.09%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 0.82%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.82%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.82%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 55        | 17.41%  |
| Samsung Electronics | 51        | 16.14%  |
| Unknown             | 38        | 12.03%  |
| Kingston            | 34        | 10.76%  |
| Crucial             | 32        | 10.13%  |
| Corsair             | 27        | 8.54%   |
| Micron Technology   | 22        | 6.96%   |
| Unknown (ABCD)      | 8         | 2.53%   |
| A-DATA Technology   | 7         | 2.22%   |
| Unknown             | 7         | 2.22%   |
| Transcend           | 5         | 1.58%   |
| Ramaxel Technology  | 5         | 1.58%   |
| Elpida              | 4         | 1.27%   |
| Team                | 3         | 0.95%   |
| Nanya Technology    | 3         | 0.95%   |
| G.Skill             | 3         | 0.95%   |
| Unknown (AB)        | 1         | 0.32%   |
| Toshiba             | 1         | 0.32%   |
| TIMETEC             | 1         | 0.32%   |
| Teikon              | 1         | 0.32%   |
| SK_Hynix            | 1         | 0.32%   |
| Kimtigo             | 1         | 0.32%   |
| Hewlett-Packard     | 1         | 0.32%   |
| CSX                 | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| Apacer              | 1         | 0.32%   |
| A-DA                | 1         | 0.32%   |
| A Force             | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 7         | 2.06%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 6         | 1.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 6         | 1.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 1.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 4         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 4         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.18%   |
| Unknown RAM Module 1GB DIMM SDRAM                                 | 3         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 3         | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 3         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 3         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 3         | 0.88%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s             | 3         | 0.88%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM 1333MT/s                    | 3         | 0.88%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 2         | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s  | 2         | 0.59%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 2         | 0.59%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2         | 0.59%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.59%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 2         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 2         | 0.59%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s             | 2         | 0.59%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.59%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                        | 2         | 0.59%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                      | 2         | 0.59%   |
| Kingston RAM LV26D4U9S8HJ-8 8GB DIMM DDR4 2667MT/s                | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 172       | 59.93%  |
| DDR4    | 81        | 28.22%  |
| DDR2    | 13        | 4.53%   |
| LPDDR4  | 9         | 3.14%   |
| Unknown | 4         | 1.39%   |
| SDRAM   | 3         | 1.05%   |
| LPDDR3  | 3         | 1.05%   |
| DDR     | 2         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 154       | 54.23%  |
| SODIMM       | 122       | 42.96%  |
| Row Of Chips | 3         | 1.06%   |
| Chip         | 3         | 1.06%   |
| Unknown      | 2         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 114       | 38%     |
| 4096  | 114       | 38%     |
| 2048  | 40        | 13.33%  |
| 16384 | 21        | 7%      |
| 32768 | 5         | 1.67%   |
| 1024  | 5         | 1.67%   |
| 65536 | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 113       | 37.17%  |
| 1333    | 43        | 14.14%  |
| 2400    | 27        | 8.88%   |
| 2667    | 23        | 7.57%   |
| 2133    | 21        | 6.91%   |
| 800     | 10        | 3.29%   |
| 1867    | 9         | 2.96%   |
| 3200    | 8         | 2.63%   |
| 667     | 8         | 2.63%   |
| 1334    | 6         | 1.97%   |
| 1067    | 6         | 1.97%   |
| 2666    | 5         | 1.64%   |
| 3600    | 4         | 1.32%   |
| 1066    | 4         | 1.32%   |
| 2933    | 3         | 0.99%   |
| Unknown | 3         | 0.99%   |
| 533     | 2         | 0.66%   |
| 65535   | 1         | 0.33%   |
| 4267    | 1         | 0.33%   |
| 3534    | 1         | 0.33%   |
| 2600    | 1         | 0.33%   |
| 1866    | 1         | 0.33%   |
| 1800    | 1         | 0.33%   |
| 933     | 1         | 0.33%   |
| 333     | 1         | 0.33%   |
| 133     | 1         | 0.33%   |

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
| Chicony Electronics                    | 14        | 23.73%  |
| Realtek Semiconductor                  | 7         | 11.86%  |
| Logitech                               | 7         | 11.86%  |
| Acer                                   | 4         | 6.78%   |
| Z-Star Microelectronics                | 3         | 5.08%   |
| Suyin                                  | 3         | 5.08%   |
| Lite-On Technology                     | 3         | 5.08%   |
| IMC Networks                           | 3         | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.08%   |
| Sunplus Innovation Technology          | 2         | 3.39%   |
| Silicon Motion                         | 2         | 3.39%   |
| Apple                                  | 2         | 3.39%   |
| Syntek                                 | 1         | 1.69%   |
| Microdia                               | 1         | 1.69%   |
| Lenovo                                 | 1         | 1.69%   |
| Creative Technology                    | 1         | 1.69%   |
| ARC International                      | 1         | 1.69%   |
| Alcor Micro                            | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 6.67%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 5%      |
| Chicony Integrated Camera                                                | 3         | 5%      |
| Realtek USB 2 Webcam                                                     | 2         | 3.33%   |
| Logitech Webcam C930e                                                    | 2         | 3.33%   |
| Logitech Labtec Webcam Pro                                               | 2         | 3.33%   |
| Logitech HD Pro Webcam C920                                              | 2         | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 3.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 2         | 3.33%   |
| Chicony Integrated Camera [ThinkPad]                                     | 2         | 3.33%   |
| Apple FaceTime HD Camera                                                 | 2         | 3.33%   |
| Z-Star WebCam SC-03FFL11739P                                             | 1         | 1.67%   |
| Z-Star Webcam                                                            | 1         | 1.67%   |
| Z-Star Namuga 1.3M Webcam                                                | 1         | 1.67%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera                            | 1         | 1.67%   |
| Suyin Laptop_Integrated_Webcam_3M                                        | 1         | 1.67%   |
| Suyin Acer Crystal Eye webcam                                            | 1         | 1.67%   |
| Suyin 1.3M HD Webcam                                                     | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                                    | 1         | 1.67%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.67%   |
| Silicon Motion 300k Pixel Camera                                         | 1         | 1.67%   |
| Realtek Realtek USB2.0 PC Camera                                         | 1         | 1.67%   |
| Microdia Integrated Webcam                                               | 1         | 1.67%   |
| Logitech Webcam C310                                                     | 1         | 1.67%   |
| Logitech B525 HD Webcam                                                  | 1         | 1.67%   |
| Lite-On Integrated Camera                                                | 1         | 1.67%   |
| Lite-On HP Wide Vision HD Camera                                         | 1         | 1.67%   |
| Lite-On HP HD Camera                                                     | 1         | 1.67%   |
| Lenovo Integrated Webcam                                                 | 1         | 1.67%   |
| IMC Networks Integrated Webcam                                           | 1         | 1.67%   |
| Creative Webcam Live! Motion                                             | 1         | 1.67%   |
| Chicony Webcam                                                           | 1         | 1.67%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 1.67%   |
| Chicony Thinkpad T430 camera                                             | 1         | 1.67%   |
| Chicony Chicony USB 2.0 Camera                                           | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera           | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.67%   |
| ARC International Camera                                                 | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| Upek                       | 2         | 14.29%  |
| Synaptics                  | 2         | 14.29%  |
| Broadcom                   | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 21.43%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 14.29%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 7.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 7.14%   |
| Unknown                                                                      | 1         | 7.14%   |

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
| 0     | 128       | 38.91%  |
| 1     | 123       | 37.39%  |
| 2     | 49        | 14.89%  |
| 3     | 20        | 6.08%   |
| 4     | 7         | 2.13%   |
| 5     | 2         | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 162       | 57.65%  |
| Bluetooth                | 31        | 11.03%  |
| Net/wireless             | 26        | 9.25%   |
| Firewire controller      | 17        | 6.05%   |
| Card reader              | 16        | 5.69%   |
| Fingerprint reader       | 12        | 4.27%   |
| Sound                    | 5         | 1.78%   |
| Network                  | 3         | 1.07%   |
| Graphics card            | 3         | 1.07%   |
| Storage/raid             | 2         | 0.71%   |
| Storage                  | 2         | 0.71%   |
| Net/ethernet             | 2         | 0.71%   |

