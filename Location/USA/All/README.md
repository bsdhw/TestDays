BSD in USA - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for BSD in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/USA/Desktop/README.md) and [notebooks](/Location/USA/Notebook/README.md).

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

Total: 6032

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| MW            | GMLK-2_5G4L                 | Desktop     | [23cb8e1723](https://bsd-hardware.info/?probe=23cb8e1723) | Feb 18, 2024 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [5333db4eb9](https://bsd-hardware.info/?probe=5333db4eb9) | Feb 18, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [15db3df1ca](https://bsd-hardware.info/?probe=15db3df1ca) | Feb 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [882809e2c7](https://bsd-hardware.info/?probe=882809e2c7) | Feb 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [db839aa12a](https://bsd-hardware.info/?probe=db839aa12a) | Feb 18, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [35e8ff3d63](https://bsd-hardware.info/?probe=35e8ff3d63) | Feb 18, 2024 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [4c03a20d4f](https://bsd-hardware.info/?probe=4c03a20d4f) | Feb 18, 2024 |
| HP            | 802E                        | Desktop     | [6ef690a057](https://bsd-hardware.info/?probe=6ef690a057) | Feb 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [ebfcb0f78b](https://bsd-hardware.info/?probe=ebfcb0f78b) | Feb 17, 2024 |
| Dell          | 0CN7CM A04                  | Server      | [c090e35a9f](https://bsd-hardware.info/?probe=c090e35a9f) | Feb 17, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [135d71a048](https://bsd-hardware.info/?probe=135d71a048) | Feb 17, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [a7fb944efe](https://bsd-hardware.info/?probe=a7fb944efe) | Feb 17, 2024 |
| Supermicro    | X11SSQ-L-DE05BA             | Server      | [68029fc128](https://bsd-hardware.info/?probe=68029fc128) | Feb 16, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7ccce31d2d](https://bsd-hardware.info/?probe=7ccce31d2d) | Feb 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [13c84b6db8](https://bsd-hardware.info/?probe=13c84b6db8) | Feb 16, 2024 |
| Unknown       | 0XFK4K A07                  | Server      | [fda628c852](https://bsd-hardware.info/?probe=fda628c852) | Feb 16, 2024 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [a3b94b00ad](https://bsd-hardware.info/?probe=a3b94b00ad) | Feb 15, 2024 |
| Intel         | SKYBAY                      | Desktop     | [5288673757](https://bsd-hardware.info/?probe=5288673757) | Feb 15, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [53bdb73b74](https://bsd-hardware.info/?probe=53bdb73b74) | Feb 14, 2024 |
| Protectli     | FW4B                        | Desktop     | [c9a2dee14e](https://bsd-hardware.info/?probe=c9a2dee14e) | Feb 14, 2024 |
| Sophos        | SG                          | Firewall    | [41c578e646](https://bsd-hardware.info/?probe=41c578e646) | Feb 14, 2024 |
| CncTion       | N5105-4L B0                 | Desktop     | [63fbf4cdbd](https://bsd-hardware.info/?probe=63fbf4cdbd) | Feb 14, 2024 |
| Dell          | 0YXT71 A00                  | Desktop     | [19c7684ced](https://bsd-hardware.info/?probe=19c7684ced) | Feb 14, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [acb70accb8](https://bsd-hardware.info/?probe=acb70accb8) | Feb 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [7a18edf610](https://bsd-hardware.info/?probe=7a18edf610) | Feb 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d24c0ab2c0](https://bsd-hardware.info/?probe=d24c0ab2c0) | Feb 13, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [47e43f818a](https://bsd-hardware.info/?probe=47e43f818a) | Feb 13, 2024 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [9f620acb22](https://bsd-hardware.info/?probe=9f620acb22) | Feb 13, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [825087e77c](https://bsd-hardware.info/?probe=825087e77c) | Feb 13, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [c7dd68f8a0](https://bsd-hardware.info/?probe=c7dd68f8a0) | Feb 13, 2024 |
| Lenovo        | ThinkPad T450 20BU000GUS    | Notebook    | [e1d99a4966](https://bsd-hardware.info/?probe=e1d99a4966) | Feb 13, 2024 |
| HP            | 18E7                        | Desktop     | [ce1c65da2d](https://bsd-hardware.info/?probe=ce1c65da2d) | Feb 12, 2024 |
| Protectli     | FW2B Ver                    | Desktop     | [d2280903ce](https://bsd-hardware.info/?probe=d2280903ce) | Feb 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [5306df5921](https://bsd-hardware.info/?probe=5306df5921) | Feb 12, 2024 |
| Intel         | SKYBAY                      | Desktop     | [7c8379fd02](https://bsd-hardware.info/?probe=7c8379fd02) | Feb 12, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [5d8c1ea60c](https://bsd-hardware.info/?probe=5d8c1ea60c) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c3d95743df](https://bsd-hardware.info/?probe=c3d95743df) | Feb 12, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [ebb87f307e](https://bsd-hardware.info/?probe=ebb87f307e) | Feb 12, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [4888597805](https://bsd-hardware.info/?probe=4888597805) | Feb 12, 2024 |
| MSI           | 890GXM-G65                  | Desktop     | [96d9ab3e95](https://bsd-hardware.info/?probe=96d9ab3e95) | Feb 12, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [1073b283ec](https://bsd-hardware.info/?probe=1073b283ec) | Feb 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [d05beec487](https://bsd-hardware.info/?probe=d05beec487) | Feb 11, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [56b53a9e68](https://bsd-hardware.info/?probe=56b53a9e68) | Feb 11, 2024 |
| Dell          | 0H634K A00                  | Desktop     | [a39d975ae9](https://bsd-hardware.info/?probe=a39d975ae9) | Feb 11, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [08506a1aff](https://bsd-hardware.info/?probe=08506a1aff) | Feb 11, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5f3d8e3288](https://bsd-hardware.info/?probe=5f3d8e3288) | Feb 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [d447aefaf0](https://bsd-hardware.info/?probe=d447aefaf0) | Feb 11, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [9a3b41d070](https://bsd-hardware.info/?probe=9a3b41d070) | Feb 11, 2024 |
| Dell          | 0H4VK7 A00                  | Desktop     | [64725f3ed7](https://bsd-hardware.info/?probe=64725f3ed7) | Feb 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [e4b4c15b64](https://bsd-hardware.info/?probe=e4b4c15b64) | Feb 11, 2024 |
| Sophos        | XG                          | Firewall    | [4037edf714](https://bsd-hardware.info/?probe=4037edf714) | Feb 11, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [e583d1ae8c](https://bsd-hardware.info/?probe=e583d1ae8c) | Feb 11, 2024 |
| Dell          | 0H4VK7 A00                  | Desktop     | [c321c66eea](https://bsd-hardware.info/?probe=c321c66eea) | Feb 11, 2024 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [32822eef4c](https://bsd-hardware.info/?probe=32822eef4c) | Feb 11, 2024 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [c5ca47db6b](https://bsd-hardware.info/?probe=c5ca47db6b) | Feb 10, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [09843ea5f1](https://bsd-hardware.info/?probe=09843ea5f1) | Feb 10, 2024 |
| Dell          | 0F9NPY A02                  | Server      | [7298dc5ba3](https://bsd-hardware.info/?probe=7298dc5ba3) | Feb 10, 2024 |
| Dell          | Latitude 7490               | Notebook    | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [b13923c3f1](https://bsd-hardware.info/?probe=b13923c3f1) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [d0bf9601a7](https://bsd-hardware.info/?probe=d0bf9601a7) | Feb 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [c3f71c8e39](https://bsd-hardware.info/?probe=c3f71c8e39) | Feb 10, 2024 |
| HP            | 213D A01                    | Desktop     | [e80039f387](https://bsd-hardware.info/?probe=e80039f387) | Feb 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [d8f999e5ce](https://bsd-hardware.info/?probe=d8f999e5ce) | Feb 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [61ddfb16f5](https://bsd-hardware.info/?probe=61ddfb16f5) | Feb 09, 2024 |
| HP            | 1495                        | Desktop     | [570b4899ea](https://bsd-hardware.info/?probe=570b4899ea) | Feb 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [2741a6da81](https://bsd-hardware.info/?probe=2741a6da81) | Feb 09, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [1e285504a6](https://bsd-hardware.info/?probe=1e285504a6) | Feb 09, 2024 |
| Unknown       | TB100                       | Desktop     | [9075923143](https://bsd-hardware.info/?probe=9075923143) | Feb 09, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [25d0533779](https://bsd-hardware.info/?probe=25d0533779) | Feb 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [09beb1cb7a](https://bsd-hardware.info/?probe=09beb1cb7a) | Feb 08, 2024 |
| Protectli     | VP2420                      | Desktop     | [70f6cd6041](https://bsd-hardware.info/?probe=70f6cd6041) | Feb 08, 2024 |
| GMKtec        | NucBox M5                   | Mini pc     | [2cdf090d24](https://bsd-hardware.info/?probe=2cdf090d24) | Feb 08, 2024 |
| AZW           | EQ                          | Desktop     | [5b83388da9](https://bsd-hardware.info/?probe=5b83388da9) | Feb 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [1d24f65624](https://bsd-hardware.info/?probe=1d24f65624) | Feb 07, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Desktop     | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Panasonic     | CF-52VDA131M                | Notebook    | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [bcf9d3885f](https://bsd-hardware.info/?probe=bcf9d3885f) | Feb 07, 2024 |
| Datto         | SSD                         | Desktop     | [1d15370fce](https://bsd-hardware.info/?probe=1d15370fce) | Feb 07, 2024 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [d2d44604ac](https://bsd-hardware.info/?probe=d2d44604ac) | Feb 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [9b6ebfd710](https://bsd-hardware.info/?probe=9b6ebfd710) | Feb 07, 2024 |
| NEOSMAY       | BQM5                        | Desktop     | [766c55f303](https://bsd-hardware.info/?probe=766c55f303) | Feb 06, 2024 |
| Unknown       | ROUTER                      | Desktop     | [b0ad906a1b](https://bsd-hardware.info/?probe=b0ad906a1b) | Feb 06, 2024 |
| ASUSTek       | STRIX H270I GAMING          | Desktop     | [852785036c](https://bsd-hardware.info/?probe=852785036c) | Feb 06, 2024 |
| Protectli     | FW1 Ver                     | Desktop     | [587c9145bc](https://bsd-hardware.info/?probe=587c9145bc) | Feb 06, 2024 |
| Silver Pea... | Unknown                     | Firewall    | [30789cb5bd](https://bsd-hardware.info/?probe=30789cb5bd) | Feb 06, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [70908897af](https://bsd-hardware.info/?probe=70908897af) | Feb 06, 2024 |
| Intel         | STK1AW32SC H91596-303       | Desktop     | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [d982b3a856](https://bsd-hardware.info/?probe=d982b3a856) | Feb 05, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [494e0fc84e](https://bsd-hardware.info/?probe=494e0fc84e) | Feb 05, 2024 |
| Dell          | 086D43 A09                  | Server      | [e21f3074a6](https://bsd-hardware.info/?probe=e21f3074a6) | Feb 05, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [112139bde4](https://bsd-hardware.info/?probe=112139bde4) | Feb 05, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [6e35ed141f](https://bsd-hardware.info/?probe=6e35ed141f) | Feb 05, 2024 |
| Silicom       | 80300-0134-g01              | Desktop     | [45cac52117](https://bsd-hardware.info/?probe=45cac52117) | Feb 05, 2024 |
| MSI           | A88XM-E45                   | Desktop     | [27c1aec350](https://bsd-hardware.info/?probe=27c1aec350) | Feb 04, 2024 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [ed12a75f82](https://bsd-hardware.info/?probe=ed12a75f82) | Feb 04, 2024 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [1b08d685ed](https://bsd-hardware.info/?probe=1b08d685ed) | Feb 04, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [91937e4592](https://bsd-hardware.info/?probe=91937e4592) | Feb 04, 2024 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [61580db8d6](https://bsd-hardware.info/?probe=61580db8d6) | Feb 04, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [f41dea5706](https://bsd-hardware.info/?probe=f41dea5706) | Feb 04, 2024 |
| MSI           | H81M-P33                    | Desktop     | [444eaddd27](https://bsd-hardware.info/?probe=444eaddd27) | Feb 04, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [87358bcf94](https://bsd-hardware.info/?probe=87358bcf94) | Feb 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [94f15f8857](https://bsd-hardware.info/?probe=94f15f8857) | Feb 04, 2024 |
| BESSTAR Te... | GK45                        | Convertible | [da0e40d971](https://bsd-hardware.info/?probe=da0e40d971) | Feb 04, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [b578551813](https://bsd-hardware.info/?probe=b578551813) | Feb 04, 2024 |
| PC Engines    | APU2                        | Desktop     | [89f0caf8f9](https://bsd-hardware.info/?probe=89f0caf8f9) | Feb 04, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [307c51641d](https://bsd-hardware.info/?probe=307c51641d) | Feb 04, 2024 |
| PC Engines    | APU2                        | Desktop     | [82cc76def6](https://bsd-hardware.info/?probe=82cc76def6) | Feb 04, 2024 |
| Dell          | 0D6H9T A00                  | Desktop     | [9454913bf3](https://bsd-hardware.info/?probe=9454913bf3) | Feb 03, 2024 |
| Protectli     | FW4B                        | Desktop     | [28f07a1d8b](https://bsd-hardware.info/?probe=28f07a1d8b) | Feb 03, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [8bb4c09136](https://bsd-hardware.info/?probe=8bb4c09136) | Feb 03, 2024 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [1c126af269](https://bsd-hardware.info/?probe=1c126af269) | Feb 03, 2024 |
| Dell          | 03NXH8 A00                  | Mini pc     | [81aed2cc10](https://bsd-hardware.info/?probe=81aed2cc10) | Feb 03, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [b6b8dbf4f5](https://bsd-hardware.info/?probe=b6b8dbf4f5) | Feb 03, 2024 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [da4216fca7](https://bsd-hardware.info/?probe=da4216fca7) | Feb 03, 2024 |
| Intel         | HM570                       | Desktop     | [ecdee25f5b](https://bsd-hardware.info/?probe=ecdee25f5b) | Feb 02, 2024 |
| Dell          | 03NVJ6 A02                  | Desktop     | [97d38286fb](https://bsd-hardware.info/?probe=97d38286fb) | Feb 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [c02da607f1](https://bsd-hardware.info/?probe=c02da607f1) | Feb 02, 2024 |
| HP            | 8103 A01                    | Mini pc     | [57019ddd81](https://bsd-hardware.info/?probe=57019ddd81) | Feb 02, 2024 |
| Silver Pea... | Unknown                     | Firewall    | [c3d1105cb3](https://bsd-hardware.info/?probe=c3d1105cb3) | Feb 02, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [f6dcaf9519](https://bsd-hardware.info/?probe=f6dcaf9519) | Feb 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [a33d1e3c29](https://bsd-hardware.info/?probe=a33d1e3c29) | Feb 02, 2024 |
| PC Engines    | APU2                        | Desktop     | [0c9724263b](https://bsd-hardware.info/?probe=0c9724263b) | Feb 02, 2024 |
| ASRock        | B660M Steel Legend          | Desktop     | [3a5ae5a649](https://bsd-hardware.info/?probe=3a5ae5a649) | Feb 02, 2024 |
| Intel         | QHSW02                      | Desktop     | [90e2883020](https://bsd-hardware.info/?probe=90e2883020) | Feb 02, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| HP            | 1495                        | Desktop     | [fc0f87fd50](https://bsd-hardware.info/?probe=fc0f87fd50) | Feb 01, 2024 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [c0ca7a18ae](https://bsd-hardware.info/?probe=c0ca7a18ae) | Feb 01, 2024 |
| HP            | 18E9                        | Desktop     | [ec3dc64c17](https://bsd-hardware.info/?probe=ec3dc64c17) | Feb 01, 2024 |
| Silver Pea... | Unknown                     | Firewall    | [49362ef497](https://bsd-hardware.info/?probe=49362ef497) | Feb 01, 2024 |
| Unknown       | QSKL01                      | Desktop     | [a61418dbc3](https://bsd-hardware.info/?probe=a61418dbc3) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [fb9640755b](https://bsd-hardware.info/?probe=fb9640755b) | Feb 01, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [d372d51db1](https://bsd-hardware.info/?probe=d372d51db1) | Jan 31, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [0847b0594d](https://bsd-hardware.info/?probe=0847b0594d) | Jan 31, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [b2ecf149ab](https://bsd-hardware.info/?probe=b2ecf149ab) | Jan 31, 2024 |
| Silver Pea... | Unknown                     | Firewall    | [f350553825](https://bsd-hardware.info/?probe=f350553825) | Jan 30, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9b41695cf4](https://bsd-hardware.info/?probe=9b41695cf4) | Jan 30, 2024 |
| Protectli     | FW2B Ver                    | Desktop     | [f8ddfd0269](https://bsd-hardware.info/?probe=f8ddfd0269) | Jan 30, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [eb2da2c88f](https://bsd-hardware.info/?probe=eb2da2c88f) | Jan 30, 2024 |
| Acer          | Veriton X275                | Desktop     | [8df1ac0855](https://bsd-hardware.info/?probe=8df1ac0855) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [b5924182bf](https://bsd-hardware.info/?probe=b5924182bf) | Jan 29, 2024 |
| Protectli     | FW1 Ver                     | Desktop     | [4b82e3a95d](https://bsd-hardware.info/?probe=4b82e3a95d) | Jan 28, 2024 |
| MSI           | H81M-P33                    | Desktop     | [d411f5eb4b](https://bsd-hardware.info/?probe=d411f5eb4b) | Jan 28, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [22436fad84](https://bsd-hardware.info/?probe=22436fad84) | Jan 28, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec38d3e15f](https://bsd-hardware.info/?probe=ec38d3e15f) | Jan 28, 2024 |
| Dell          | 07HXY6 A01                  | Desktop     | [1f9ff2f86a](https://bsd-hardware.info/?probe=1f9ff2f86a) | Jan 28, 2024 |
| Dell          | 07HXY6 A01                  | Desktop     | [55f2cc74d2](https://bsd-hardware.info/?probe=55f2cc74d2) | Jan 28, 2024 |
| Unknown       | QDNV01                      | Desktop     | [6e54e1cc98](https://bsd-hardware.info/?probe=6e54e1cc98) | Jan 28, 2024 |
| HP            | 8103 A01                    | Mini pc     | [6cde48b88b](https://bsd-hardware.info/?probe=6cde48b88b) | Jan 27, 2024 |
| Inventec      | Z CLASS A02                 | Desktop     | [7a16c15977](https://bsd-hardware.info/?probe=7a16c15977) | Jan 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [9a629cc792](https://bsd-hardware.info/?probe=9a629cc792) | Jan 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [ac839a7f6c](https://bsd-hardware.info/?probe=ac839a7f6c) | Jan 27, 2024 |
| Dell          | 03X6X0 A00                  | Server      | [421497f7c6](https://bsd-hardware.info/?probe=421497f7c6) | Jan 26, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [fa494be63d](https://bsd-hardware.info/?probe=fa494be63d) | Jan 26, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [713a924dbc](https://bsd-hardware.info/?probe=713a924dbc) | Jan 26, 2024 |
| AZW           | EQ                          | Desktop     | [a14d6a1470](https://bsd-hardware.info/?probe=a14d6a1470) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [4b04b7d0f0](https://bsd-hardware.info/?probe=4b04b7d0f0) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [9cd2f0b2da](https://bsd-hardware.info/?probe=9cd2f0b2da) | Jan 25, 2024 |
| Panasonic     | CFSX4-1                     | Notebook    | [d998c9373a](https://bsd-hardware.info/?probe=d998c9373a) | Jan 25, 2024 |
| HP            | 843F                        | Desktop     | [650b67d779](https://bsd-hardware.info/?probe=650b67d779) | Jan 25, 2024 |
| AZW           | EQ                          | Desktop     | [c49b4d4d49](https://bsd-hardware.info/?probe=c49b4d4d49) | Jan 24, 2024 |
| ASRock        | J3455-ITX                   | Desktop     | [2aa7476d4f](https://bsd-hardware.info/?probe=2aa7476d4f) | Jan 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [d70b467db3](https://bsd-hardware.info/?probe=d70b467db3) | Jan 24, 2024 |
| Dell          | 0CN7CM A04                  | Server      | [4f79959505](https://bsd-hardware.info/?probe=4f79959505) | Jan 23, 2024 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [e57514c59b](https://bsd-hardware.info/?probe=e57514c59b) | Jan 23, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [20d9879f23](https://bsd-hardware.info/?probe=20d9879f23) | Jan 23, 2024 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [37e21779b0](https://bsd-hardware.info/?probe=37e21779b0) | Jan 23, 2024 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [5862d464ac](https://bsd-hardware.info/?probe=5862d464ac) | Jan 22, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [b9ddf83ccb](https://bsd-hardware.info/?probe=b9ddf83ccb) | Jan 22, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [649257b7d4](https://bsd-hardware.info/?probe=649257b7d4) | Jan 22, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [c948e4d72d](https://bsd-hardware.info/?probe=c948e4d72d) | Jan 22, 2024 |
| IBM           | 830381U                     | Desktop     | [a3f2d51f21](https://bsd-hardware.info/?probe=a3f2d51f21) | Jan 21, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [75746599d1](https://bsd-hardware.info/?probe=75746599d1) | Jan 21, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [4d272356f7](https://bsd-hardware.info/?probe=4d272356f7) | Jan 21, 2024 |
| Dell          | 0YNVJG A02                  | Desktop     | [82620ff3ea](https://bsd-hardware.info/?probe=82620ff3ea) | Jan 21, 2024 |
| AZW           | EQ                          | Desktop     | [bcaa597224](https://bsd-hardware.info/?probe=bcaa597224) | Jan 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [4244a64777](https://bsd-hardware.info/?probe=4244a64777) | Jan 21, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [03397059f1](https://bsd-hardware.info/?probe=03397059f1) | Jan 21, 2024 |
| Protectli     | VP2420                      | Desktop     | [dd5215657f](https://bsd-hardware.info/?probe=dd5215657f) | Jan 20, 2024 |
| Supermicro    | X13SAE-F                    | Server      | [3efe4df9e9](https://bsd-hardware.info/?probe=3efe4df9e9) | Jan 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [492b9a5dd2](https://bsd-hardware.info/?probe=492b9a5dd2) | Jan 20, 2024 |
| CompuLab      | fitlet2                     | Mini pc     | [4602a02ddc](https://bsd-hardware.info/?probe=4602a02ddc) | Jan 20, 2024 |
| IBM           | 830381U                     | Desktop     | [e44647b8cd](https://bsd-hardware.info/?probe=e44647b8cd) | Jan 20, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [e2d19736de](https://bsd-hardware.info/?probe=e2d19736de) | Jan 20, 2024 |
| Microsoft     | Windows Dev Kit 2023        | Desktop     | [2cd25bfacf](https://bsd-hardware.info/?probe=2cd25bfacf) | Jan 19, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [5414d17be7](https://bsd-hardware.info/?probe=5414d17be7) | Jan 19, 2024 |
| Intel         | CRESCENTBAY                 | Desktop     | [a5936e1878](https://bsd-hardware.info/?probe=a5936e1878) | Jan 19, 2024 |
| Dell          | 03X6X0 A00                  | Server      | [09718f21c0](https://bsd-hardware.info/?probe=09718f21c0) | Jan 19, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4754523f7](https://bsd-hardware.info/?probe=d4754523f7) | Jan 19, 2024 |
| Dell          | 0F0XJ6 A11                  | Server      | [6b9538da44](https://bsd-hardware.info/?probe=6b9538da44) | Jan 18, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9d74aa9072](https://bsd-hardware.info/?probe=9d74aa9072) | Jan 18, 2024 |
| Unknown       | QDNV01                      | Desktop     | [99d4f2dbf5](https://bsd-hardware.info/?probe=99d4f2dbf5) | Jan 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [236d3f0732](https://bsd-hardware.info/?probe=236d3f0732) | Jan 18, 2024 |
| Supermicro    | X11SSH-F                    | Desktop     | [d273b1ed9f](https://bsd-hardware.info/?probe=d273b1ed9f) | Jan 18, 2024 |
| Sophos        | XG                          | Firewall    | [fc2835ce35](https://bsd-hardware.info/?probe=fc2835ce35) | Jan 18, 2024 |
| AZW           | EQ                          | Desktop     | [04e8043548](https://bsd-hardware.info/?probe=04e8043548) | Jan 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [ad20eaae94](https://bsd-hardware.info/?probe=ad20eaae94) | Jan 17, 2024 |
| Sophos        | SG                          | Firewall    | [f8a0334608](https://bsd-hardware.info/?probe=f8a0334608) | Jan 17, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [fa84143aec](https://bsd-hardware.info/?probe=fa84143aec) | Jan 17, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [fcd8f97c05](https://bsd-hardware.info/?probe=fcd8f97c05) | Jan 17, 2024 |
| AWOW          | MC02                        | Mini pc     | [35fa6243c5](https://bsd-hardware.info/?probe=35fa6243c5) | Jan 17, 2024 |
| Intel         | DH61AG AAG23736-400         | Desktop     | [89e63dd31d](https://bsd-hardware.info/?probe=89e63dd31d) | Jan 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [6ef2456b35](https://bsd-hardware.info/?probe=6ef2456b35) | Jan 16, 2024 |
| HP            | 8103 A01                    | Mini pc     | [9d6f570421](https://bsd-hardware.info/?probe=9d6f570421) | Jan 16, 2024 |
| Supermicro    | X11SSH-F                    | Desktop     | [e6e1960214](https://bsd-hardware.info/?probe=e6e1960214) | Jan 16, 2024 |
| ASUSTek       | P9X79 LE                    | Desktop     | [fc3b560a10](https://bsd-hardware.info/?probe=fc3b560a10) | Jan 15, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [1dfff45a5e](https://bsd-hardware.info/?probe=1dfff45a5e) | Jan 15, 2024 |
| CncTion       | N5105-4L B0                 | Desktop     | [de84a99395](https://bsd-hardware.info/?probe=de84a99395) | Jan 15, 2024 |
| HP            | 83E2                        | Desktop     | [f8de5b6abb](https://bsd-hardware.info/?probe=f8de5b6abb) | Jan 15, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [c22ce22507](https://bsd-hardware.info/?probe=c22ce22507) | Jan 15, 2024 |
| AZW           | EQ                          | Desktop     | [16088b9f73](https://bsd-hardware.info/?probe=16088b9f73) | Jan 15, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [0906af3cf9](https://bsd-hardware.info/?probe=0906af3cf9) | Jan 15, 2024 |
| Supermicro    | X11SSH-F                    | Server      | [530d4a5307](https://bsd-hardware.info/?probe=530d4a5307) | Jan 15, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fcc009f8ba](https://bsd-hardware.info/?probe=fcc009f8ba) | Jan 15, 2024 |
| Dell          | 0F0XJ6 A13                  | Server      | [32b846d36d](https://bsd-hardware.info/?probe=32b846d36d) | Jan 14, 2024 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [96bd0ccc8b](https://bsd-hardware.info/?probe=96bd0ccc8b) | Jan 14, 2024 |
| Dell          | 0FRVY0 A03                  | Server      | [2b11fb3a7a](https://bsd-hardware.info/?probe=2b11fb3a7a) | Jan 14, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Server      | [686cce4b21](https://bsd-hardware.info/?probe=686cce4b21) | Jan 14, 2024 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [7a7a48463f](https://bsd-hardware.info/?probe=7a7a48463f) | Jan 14, 2024 |
| Protectli     | FW6                         | Desktop     | [b17885bbf5](https://bsd-hardware.info/?probe=b17885bbf5) | Jan 13, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [4e7a1908b5](https://bsd-hardware.info/?probe=4e7a1908b5) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [037f8126cc](https://bsd-hardware.info/?probe=037f8126cc) | Jan 13, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a95eae54ba](https://bsd-hardware.info/?probe=a95eae54ba) | Jan 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f1224c8ebd](https://bsd-hardware.info/?probe=f1224c8ebd) | Jan 13, 2024 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [e013ea04db](https://bsd-hardware.info/?probe=e013ea04db) | Jan 13, 2024 |
| Dell          | Latitude 7490               | Notebook    | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [336d472712](https://bsd-hardware.info/?probe=336d472712) | Jan 13, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [699a750910](https://bsd-hardware.info/?probe=699a750910) | Jan 13, 2024 |
| Dell          | Latitude E5420              | Notebook    | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| Dell          | 01V648 A07                  | Server      | [2184f408a0](https://bsd-hardware.info/?probe=2184f408a0) | Jan 13, 2024 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [c8a1dfc64e](https://bsd-hardware.info/?probe=c8a1dfc64e) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [f6388b9dc0](https://bsd-hardware.info/?probe=f6388b9dc0) | Jan 13, 2024 |
| Dell          | 0F0XJ6 A11                  | Server      | [ee71a834fb](https://bsd-hardware.info/?probe=ee71a834fb) | Jan 12, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a066488c25](https://bsd-hardware.info/?probe=a066488c25) | Jan 12, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9736c485c9](https://bsd-hardware.info/?probe=9736c485c9) | Jan 12, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [f992fb318d](https://bsd-hardware.info/?probe=f992fb318d) | Jan 12, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [e9903fc76b](https://bsd-hardware.info/?probe=e9903fc76b) | Jan 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [54f9f65b05](https://bsd-hardware.info/?probe=54f9f65b05) | Jan 12, 2024 |
| AZW           | EQ                          | Desktop     | [b80d010809](https://bsd-hardware.info/?probe=b80d010809) | Jan 12, 2024 |
| Standard      | SFFGL Series                | Mini pc     | [6984816362](https://bsd-hardware.info/?probe=6984816362) | Jan 12, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [c642669941](https://bsd-hardware.info/?probe=c642669941) | Jan 11, 2024 |
| Dell          | 0XCR8D A03                  | Desktop     | [67a92b675d](https://bsd-hardware.info/?probe=67a92b675d) | Jan 11, 2024 |
| Protectli     | FW4C Ver                    | Desktop     | [62294dff5a](https://bsd-hardware.info/?probe=62294dff5a) | Jan 10, 2024 |
| Dell          | 05XKKK A05                  | Server      | [37c5277b8d](https://bsd-hardware.info/?probe=37c5277b8d) | Jan 10, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [af74c92cd6](https://bsd-hardware.info/?probe=af74c92cd6) | Jan 10, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [9bf925dc48](https://bsd-hardware.info/?probe=9bf925dc48) | Jan 10, 2024 |
| Unknown       | Unknown                     | Desktop     | [8f7bfe9126](https://bsd-hardware.info/?probe=8f7bfe9126) | Jan 10, 2024 |
| Protectli     | FW2B Ver                    | Desktop     | [8735484351](https://bsd-hardware.info/?probe=8735484351) | Jan 10, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [67f7f97377](https://bsd-hardware.info/?probe=67f7f97377) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [1d0dd537a8](https://bsd-hardware.info/?probe=1d0dd537a8) | Jan 09, 2024 |
| MSI           | Z270M MORTAR                | Desktop     | [a359d80a45](https://bsd-hardware.info/?probe=a359d80a45) | Jan 09, 2024 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [2dbe56a276](https://bsd-hardware.info/?probe=2dbe56a276) | Jan 09, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [77a712a874](https://bsd-hardware.info/?probe=77a712a874) | Jan 09, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [c877bf8ec0](https://bsd-hardware.info/?probe=c877bf8ec0) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [548ff32772](https://bsd-hardware.info/?probe=548ff32772) | Jan 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [ef57a8bf7f](https://bsd-hardware.info/?probe=ef57a8bf7f) | Jan 08, 2024 |
| HP            | ProLiant ML110 G7           | Desktop     | [57c773fdc1](https://bsd-hardware.info/?probe=57c773fdc1) | Jan 08, 2024 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [a4f06776ee](https://bsd-hardware.info/?probe=a4f06776ee) | Jan 08, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [41503413eb](https://bsd-hardware.info/?probe=41503413eb) | Jan 08, 2024 |
| Dell          | Inspiron 5555               | Notebook    | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| MSI           | H81M-P33                    | Desktop     | [e2407e0579](https://bsd-hardware.info/?probe=e2407e0579) | Jan 07, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [e97b058f7c](https://bsd-hardware.info/?probe=e97b058f7c) | Jan 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d429a5298b](https://bsd-hardware.info/?probe=d429a5298b) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eda92591b5](https://bsd-hardware.info/?probe=eda92591b5) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [12ff062207](https://bsd-hardware.info/?probe=12ff062207) | Jan 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [6564d3ecfe](https://bsd-hardware.info/?probe=6564d3ecfe) | Jan 07, 2024 |
| BESSTAR Te... | VB9                         | All in one  | [e6148f7091](https://bsd-hardware.info/?probe=e6148f7091) | Jan 06, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [8796820698](https://bsd-hardware.info/?probe=8796820698) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [3f3aabf270](https://bsd-hardware.info/?probe=3f3aabf270) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [d24b57f807](https://bsd-hardware.info/?probe=d24b57f807) | Jan 06, 2024 |
| Dell          | 0XFWHV A00                  | Desktop     | [ef7c13ea0e](https://bsd-hardware.info/?probe=ef7c13ea0e) | Jan 06, 2024 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [0514d572ce](https://bsd-hardware.info/?probe=0514d572ce) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| Protectli     | FW2B Ver                    | Desktop     | [4a60768833](https://bsd-hardware.info/?probe=4a60768833) | Jan 06, 2024 |
| HP            | ProLiant ML110 G7           | Desktop     | [9939bc50d4](https://bsd-hardware.info/?probe=9939bc50d4) | Jan 05, 2024 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [22f439df81](https://bsd-hardware.info/?probe=22f439df81) | Jan 05, 2024 |
| Silicom       | 80300-0214-G01 R407         | Desktop     | [bed6767a1f](https://bsd-hardware.info/?probe=bed6767a1f) | Jan 05, 2024 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [319f5b8358](https://bsd-hardware.info/?probe=319f5b8358) | Jan 05, 2024 |
| Azulle        | Access3                     | Stick pc    | [451d2b5708](https://bsd-hardware.info/?probe=451d2b5708) | Jan 05, 2024 |
| HP            | 843F                        | Desktop     | [a0a5abafb6](https://bsd-hardware.info/?probe=a0a5abafb6) | Jan 05, 2024 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [677efc87c6](https://bsd-hardware.info/?probe=677efc87c6) | Jan 04, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7aede6e8ce](https://bsd-hardware.info/?probe=7aede6e8ce) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bb0d74a396](https://bsd-hardware.info/?probe=bb0d74a396) | Jan 04, 2024 |
| ASRockRack    | EPYC3251D4I-2T              | Desktop     | [6e5054d1f1](https://bsd-hardware.info/?probe=6e5054d1f1) | Jan 04, 2024 |
| Intel         | QHSW02                      | Desktop     | [e505c16d73](https://bsd-hardware.info/?probe=e505c16d73) | Jan 04, 2024 |
| iKOOLCORE ... | R2                          | Desktop     | [b8be09aa4a](https://bsd-hardware.info/?probe=b8be09aa4a) | Jan 03, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [17862ade20](https://bsd-hardware.info/?probe=17862ade20) | Jan 03, 2024 |
| Dell          | 0YXT71 A00                  | Desktop     | [3e716c2ad2](https://bsd-hardware.info/?probe=3e716c2ad2) | Jan 03, 2024 |
| Dell          | 0D02VH A01                  | Desktop     | [8e8fc6da64](https://bsd-hardware.info/?probe=8e8fc6da64) | Jan 03, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [d7b4e67cdc](https://bsd-hardware.info/?probe=d7b4e67cdc) | Jan 03, 2024 |
| Unknown       | QGLK03                      | Desktop     | [6bdc39f976](https://bsd-hardware.info/?probe=6bdc39f976) | Jan 02, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [c0f7a38e07](https://bsd-hardware.info/?probe=c0f7a38e07) | Jan 02, 2024 |
| AZW           | U59                         | Desktop     | [c8ffb92584](https://bsd-hardware.info/?probe=c8ffb92584) | Jan 02, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | Notebook    | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| AWOW          | AZ51                        | Mini pc     | [2dc5c759ac](https://bsd-hardware.info/?probe=2dc5c759ac) | Jan 02, 2024 |
| Protectli     | VP46xx                      | Desktop     | [f958569c30](https://bsd-hardware.info/?probe=f958569c30) | Jan 02, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [673266d486](https://bsd-hardware.info/?probe=673266d486) | Jan 01, 2024 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [270a946916](https://bsd-hardware.info/?probe=270a946916) | Jan 01, 2024 |
| Alienware     | 07HV66 A00                  | Desktop     | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| Protectli     | FW4B Ver                    | Desktop     | [3191952740](https://bsd-hardware.info/?probe=3191952740) | Jan 01, 2024 |
| MSI           | Z170A PC MATE               | Desktop     | [e05af13af9](https://bsd-hardware.info/?probe=e05af13af9) | Jan 01, 2024 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| GEEK+         | Mini PC                     | Mini pc     | [9e550a39c1](https://bsd-hardware.info/?probe=9e550a39c1) | Dec 31, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [bcbbfa0368](https://bsd-hardware.info/?probe=bcbbfa0368) | Dec 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [56ecba336a](https://bsd-hardware.info/?probe=56ecba336a) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [715a274a2e](https://bsd-hardware.info/?probe=715a274a2e) | Dec 30, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [39c4ea3a24](https://bsd-hardware.info/?probe=39c4ea3a24) | Dec 30, 2023 |
| HP            | 3397                        | Desktop     | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [3dbf91e1d4](https://bsd-hardware.info/?probe=3dbf91e1d4) | Dec 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e235575d34](https://bsd-hardware.info/?probe=e235575d34) | Dec 30, 2023 |
| Unknown       | QDNV01                      | Desktop     | [d2fed4bb5f](https://bsd-hardware.info/?probe=d2fed4bb5f) | Dec 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [de6046d060](https://bsd-hardware.info/?probe=de6046d060) | Dec 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [49375afedd](https://bsd-hardware.info/?probe=49375afedd) | Dec 29, 2023 |
| PC Engines    | apu4                        | Desktop     | [3901782984](https://bsd-hardware.info/?probe=3901782984) | Dec 29, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [c545672f6f](https://bsd-hardware.info/?probe=c545672f6f) | Dec 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [39b80f6d35](https://bsd-hardware.info/?probe=39b80f6d35) | Dec 28, 2023 |
| HP            | 0B54h D                     | Desktop     | [0fc53a659f](https://bsd-hardware.info/?probe=0fc53a659f) | Dec 28, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [55a9dc404b](https://bsd-hardware.info/?probe=55a9dc404b) | Dec 27, 2023 |
| Protectli     | VP2420                      | Desktop     | [a7e60ab925](https://bsd-hardware.info/?probe=a7e60ab925) | Dec 27, 2023 |
| HP            | 1998                        | Desktop     | [8bebbb8dab](https://bsd-hardware.info/?probe=8bebbb8dab) | Dec 27, 2023 |
| MSI           | Aspen                       | Desktop     | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [cf4ead1922](https://bsd-hardware.info/?probe=cf4ead1922) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [48677111e5](https://bsd-hardware.info/?probe=48677111e5) | Dec 26, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [47fdb04811](https://bsd-hardware.info/?probe=47fdb04811) | Dec 25, 2023 |
| Supermicro    | X11SDW-16C-TP13F+           | Desktop     | [49ed0c6dca](https://bsd-hardware.info/?probe=49ed0c6dca) | Dec 25, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [304af7e00e](https://bsd-hardware.info/?probe=304af7e00e) | Dec 25, 2023 |
| Dell          | 081N4V A10                  | Server      | [62d49dec3c](https://bsd-hardware.info/?probe=62d49dec3c) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [4be2a41109](https://bsd-hardware.info/?probe=4be2a41109) | Dec 25, 2023 |
| Unknown       | QGLK03                      | Desktop     | [b187a024cb](https://bsd-hardware.info/?probe=b187a024cb) | Dec 25, 2023 |
| Unknown       | QSKL01                      | Desktop     | [f69898815d](https://bsd-hardware.info/?probe=f69898815d) | Dec 25, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [5844adb190](https://bsd-hardware.info/?probe=5844adb190) | Dec 24, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [1656e8f6b0](https://bsd-hardware.info/?probe=1656e8f6b0) | Dec 24, 2023 |
| Unknown       | QGLK03                      | Desktop     | [a586279dd0](https://bsd-hardware.info/?probe=a586279dd0) | Dec 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [da2b7d434e](https://bsd-hardware.info/?probe=da2b7d434e) | Dec 24, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [69e3982549](https://bsd-hardware.info/?probe=69e3982549) | Dec 23, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [7940d24d8e](https://bsd-hardware.info/?probe=7940d24d8e) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [06828fbfed](https://bsd-hardware.info/?probe=06828fbfed) | Dec 23, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [3c06ec4635](https://bsd-hardware.info/?probe=3c06ec4635) | Dec 23, 2023 |
| AZW           | EQ                          | Desktop     | [9818e5f996](https://bsd-hardware.info/?probe=9818e5f996) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [97559370a8](https://bsd-hardware.info/?probe=97559370a8) | Dec 23, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [4b6a62bebe](https://bsd-hardware.info/?probe=4b6a62bebe) | Dec 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [c4e5366baa](https://bsd-hardware.info/?probe=c4e5366baa) | Dec 22, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f2229124bf](https://bsd-hardware.info/?probe=f2229124bf) | Dec 22, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [2463b12f4e](https://bsd-hardware.info/?probe=2463b12f4e) | Dec 22, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Shuttle       | FS77U                       | Desktop     | [9c746c0d5c](https://bsd-hardware.info/?probe=9c746c0d5c) | Dec 21, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [70fe8567d6](https://bsd-hardware.info/?probe=70fe8567d6) | Dec 21, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [8a2c7af96c](https://bsd-hardware.info/?probe=8a2c7af96c) | Dec 21, 2023 |
| PC Engines    | apu4                        | Desktop     | [7fa270657e](https://bsd-hardware.info/?probe=7fa270657e) | Dec 21, 2023 |
| Intel         | DH61AG AAG23736-400         | Desktop     | [e6a38faa07](https://bsd-hardware.info/?probe=e6a38faa07) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f9fd749985](https://bsd-hardware.info/?probe=f9fd749985) | Dec 21, 2023 |
| Protectli     | VP2420                      | Desktop     | [9a4aba32a7](https://bsd-hardware.info/?probe=9a4aba32a7) | Dec 21, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [835ca2056c](https://bsd-hardware.info/?probe=835ca2056c) | Dec 21, 2023 |
| Protectli     | FW4B                        | Desktop     | [d67b8b063a](https://bsd-hardware.info/?probe=d67b8b063a) | Dec 21, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [760c7214cc](https://bsd-hardware.info/?probe=760c7214cc) | Dec 20, 2023 |
| Apple         | PowerBook3,5                | Notebook    | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6e070fbb90](https://bsd-hardware.info/?probe=6e070fbb90) | Dec 20, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [54b2061c80](https://bsd-hardware.info/?probe=54b2061c80) | Dec 19, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [c00a69de7c](https://bsd-hardware.info/?probe=c00a69de7c) | Dec 19, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [bb91074237](https://bsd-hardware.info/?probe=bb91074237) | Dec 19, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7d5e8bcb8a](https://bsd-hardware.info/?probe=7d5e8bcb8a) | Dec 19, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [abcaede8e1](https://bsd-hardware.info/?probe=abcaede8e1) | Dec 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| Dell          | 04JN2K A03                  | Server      | [d56fe5aeb2](https://bsd-hardware.info/?probe=d56fe5aeb2) | Dec 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c4a54e3710](https://bsd-hardware.info/?probe=c4a54e3710) | Dec 18, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [9660edcc5c](https://bsd-hardware.info/?probe=9660edcc5c) | Dec 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [107e747798](https://bsd-hardware.info/?probe=107e747798) | Dec 17, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [ea3bc70906](https://bsd-hardware.info/?probe=ea3bc70906) | Dec 17, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| ECS           | H81H3-WM                    | Desktop     | [9df1f030f9](https://bsd-hardware.info/?probe=9df1f030f9) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [88306fe484](https://bsd-hardware.info/?probe=88306fe484) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [6a3ef5165f](https://bsd-hardware.info/?probe=6a3ef5165f) | Dec 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [cefdf7d9ca](https://bsd-hardware.info/?probe=cefdf7d9ca) | Dec 17, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4b134e7787](https://bsd-hardware.info/?probe=4b134e7787) | Dec 16, 2023 |
| Protectli     | FW4B                        | Desktop     | [b862c8c507](https://bsd-hardware.info/?probe=b862c8c507) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | Notebook    | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [df97b81bea](https://bsd-hardware.info/?probe=df97b81bea) | Dec 15, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d8eee18baf](https://bsd-hardware.info/?probe=d8eee18baf) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [5adc44e122](https://bsd-hardware.info/?probe=5adc44e122) | Dec 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4b7be4588e](https://bsd-hardware.info/?probe=4b7be4588e) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [93f650efc3](https://bsd-hardware.info/?probe=93f650efc3) | Dec 15, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9773ffcc27](https://bsd-hardware.info/?probe=9773ffcc27) | Dec 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9f96c677c](https://bsd-hardware.info/?probe=a9f96c677c) | Dec 14, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [e15a019715](https://bsd-hardware.info/?probe=e15a019715) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b2407b8a31](https://bsd-hardware.info/?probe=b2407b8a31) | Dec 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12e42ebd6d](https://bsd-hardware.info/?probe=12e42ebd6d) | Dec 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8eb8c9eff3](https://bsd-hardware.info/?probe=8eb8c9eff3) | Dec 13, 2023 |
| Google        | Lindar rev3                 | Notebook    | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Intel         | QHSW02                      | Desktop     | [da6b7c7115](https://bsd-hardware.info/?probe=da6b7c7115) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| ASRock        | H170M-ITX/DL                | Desktop     | [79039f6105](https://bsd-hardware.info/?probe=79039f6105) | Dec 13, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [b5dc4da596](https://bsd-hardware.info/?probe=b5dc4da596) | Dec 12, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [c26ebe6c80](https://bsd-hardware.info/?probe=c26ebe6c80) | Dec 12, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c05c574f37](https://bsd-hardware.info/?probe=c05c574f37) | Dec 12, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| HP            | 8103 A01                    | Mini pc     | [e2f44ab91e](https://bsd-hardware.info/?probe=e2f44ab91e) | Dec 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [becfed036a](https://bsd-hardware.info/?probe=becfed036a) | Dec 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [68f73bf8ba](https://bsd-hardware.info/?probe=68f73bf8ba) | Dec 11, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [b806cc2a41](https://bsd-hardware.info/?probe=b806cc2a41) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [ec8c50c128](https://bsd-hardware.info/?probe=ec8c50c128) | Dec 10, 2023 |
| AZW           | EQ                          | Desktop     | [48537a5985](https://bsd-hardware.info/?probe=48537a5985) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| Dell          | 0YNVJG A02                  | Desktop     | [2d8992cd50](https://bsd-hardware.info/?probe=2d8992cd50) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [fc1097e9b0](https://bsd-hardware.info/?probe=fc1097e9b0) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e478d7459](https://bsd-hardware.info/?probe=3e478d7459) | Dec 10, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [06e5f53429](https://bsd-hardware.info/?probe=06e5f53429) | Dec 10, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [8dd13bf91f](https://bsd-hardware.info/?probe=8dd13bf91f) | Dec 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [edfa10c0dd](https://bsd-hardware.info/?probe=edfa10c0dd) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| ASRock        | B660M Phantom Gaming 4      | Desktop     | [e71ffa9a86](https://bsd-hardware.info/?probe=e71ffa9a86) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a03446d994](https://bsd-hardware.info/?probe=a03446d994) | Dec 10, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b7e23a4ed4](https://bsd-hardware.info/?probe=b7e23a4ed4) | Dec 10, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3b6c1c2fbb](https://bsd-hardware.info/?probe=3b6c1c2fbb) | Dec 09, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [05acf05b44](https://bsd-hardware.info/?probe=05acf05b44) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [55094840ea](https://bsd-hardware.info/?probe=55094840ea) | Dec 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [76f58e8986](https://bsd-hardware.info/?probe=76f58e8986) | Dec 09, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [0674ed24ed](https://bsd-hardware.info/?probe=0674ed24ed) | Dec 09, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [20dbd4481a](https://bsd-hardware.info/?probe=20dbd4481a) | Dec 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8422bc152b](https://bsd-hardware.info/?probe=8422bc152b) | Dec 08, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [a0591ac105](https://bsd-hardware.info/?probe=a0591ac105) | Dec 08, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [2074ab8412](https://bsd-hardware.info/?probe=2074ab8412) | Dec 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [050e7d8c01](https://bsd-hardware.info/?probe=050e7d8c01) | Dec 08, 2023 |
| Dell          | 081N4V A08                  | Server      | [3aba7cf14e](https://bsd-hardware.info/?probe=3aba7cf14e) | Dec 08, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [cf3304bda2](https://bsd-hardware.info/?probe=cf3304bda2) | Dec 08, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [c119d3003e](https://bsd-hardware.info/?probe=c119d3003e) | Dec 07, 2023 |
| Protectli     | VP46xx                      | Desktop     | [5051678913](https://bsd-hardware.info/?probe=5051678913) | Dec 07, 2023 |
| PC Engines    | APU2                        | Desktop     | [92c3ba510a](https://bsd-hardware.info/?probe=92c3ba510a) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [23b689f778](https://bsd-hardware.info/?probe=23b689f778) | Dec 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c906f764b0](https://bsd-hardware.info/?probe=c906f764b0) | Dec 07, 2023 |
| HP            | 213D A01                    | Desktop     | [a7ded310e3](https://bsd-hardware.info/?probe=a7ded310e3) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a11b04691d](https://bsd-hardware.info/?probe=a11b04691d) | Dec 07, 2023 |
| Sony          | VJS122C11L                  | Notebook    | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Dell          | 0CN7X8 A01                  | Server      | [82ff66fb79](https://bsd-hardware.info/?probe=82ff66fb79) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ac7f59dc32](https://bsd-hardware.info/?probe=ac7f59dc32) | Dec 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [ef425e8732](https://bsd-hardware.info/?probe=ef425e8732) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2301bb487f](https://bsd-hardware.info/?probe=2301bb487f) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [d6c18203b4](https://bsd-hardware.info/?probe=d6c18203b4) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [780619812e](https://bsd-hardware.info/?probe=780619812e) | Dec 04, 2023 |
| Lenovo        | XXXX FFFFFFFFFF             | Desktop     | [7ddfbf4af2](https://bsd-hardware.info/?probe=7ddfbf4af2) | Dec 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [267d300e4a](https://bsd-hardware.info/?probe=267d300e4a) | Dec 04, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [c5e25db7f9](https://bsd-hardware.info/?probe=c5e25db7f9) | Dec 04, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [494f638f4e](https://bsd-hardware.info/?probe=494f638f4e) | Dec 04, 2023 |
| Protectli     | FW6                         | Desktop     | [91d91ebf31](https://bsd-hardware.info/?probe=91d91ebf31) | Dec 04, 2023 |
| MiTAC         | UltraPoint                  | Desktop     | [346d03e78c](https://bsd-hardware.info/?probe=346d03e78c) | Dec 04, 2023 |
| HP            | 8715                        | Mini pc     | [262c6ee87c](https://bsd-hardware.info/?probe=262c6ee87c) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [2fefe41bcd](https://bsd-hardware.info/?probe=2fefe41bcd) | Dec 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d04fd54963](https://bsd-hardware.info/?probe=d04fd54963) | Dec 03, 2023 |
| AZW           | MINI S 10                   | Desktop     | [caf105bd1b](https://bsd-hardware.info/?probe=caf105bd1b) | Dec 02, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [761e1e0eae](https://bsd-hardware.info/?probe=761e1e0eae) | Dec 02, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [8ffbff07d4](https://bsd-hardware.info/?probe=8ffbff07d4) | Dec 02, 2023 |
| HP            | 8265                        | Desktop     | [ec9e6fdd6e](https://bsd-hardware.info/?probe=ec9e6fdd6e) | Dec 02, 2023 |
| Protectli     | FW4C                        | Desktop     | [c3b8887f26](https://bsd-hardware.info/?probe=c3b8887f26) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [baf3e413d0](https://bsd-hardware.info/?probe=baf3e413d0) | Dec 01, 2023 |
| AZW           | EQ                          | Desktop     | [1f66e98633](https://bsd-hardware.info/?probe=1f66e98633) | Dec 01, 2023 |
| ASRock        | H110M-HDS                   | Desktop     | [519a82f253](https://bsd-hardware.info/?probe=519a82f253) | Dec 01, 2023 |
| Dell          | 081N4V A10                  | Server      | [46338756b8](https://bsd-hardware.info/?probe=46338756b8) | Nov 30, 2023 |
| Dell          | 0XN8Y6 A12                  | Server      | [3c8b7cfb27](https://bsd-hardware.info/?probe=3c8b7cfb27) | Nov 30, 2023 |
| AZW           | EQ                          | Desktop     | [a2f18cb86e](https://bsd-hardware.info/?probe=a2f18cb86e) | Nov 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [78fef35503](https://bsd-hardware.info/?probe=78fef35503) | Nov 30, 2023 |
| Silver Pea... | Unknown                     | Firewall    | [405efa1824](https://bsd-hardware.info/?probe=405efa1824) | Nov 30, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [8dfd16da29](https://bsd-hardware.info/?probe=8dfd16da29) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f3a2321558](https://bsd-hardware.info/?probe=f3a2321558) | Nov 29, 2023 |
| Deciso        | Netboard A8                 | Desktop     | [53d89587d0](https://bsd-hardware.info/?probe=53d89587d0) | Nov 28, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [d45a39836c](https://bsd-hardware.info/?probe=d45a39836c) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [97fc765ff5](https://bsd-hardware.info/?probe=97fc765ff5) | Nov 28, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30e336f42f](https://bsd-hardware.info/?probe=30e336f42f) | Nov 28, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [be0344dcf2](https://bsd-hardware.info/?probe=be0344dcf2) | Nov 28, 2023 |
| Supermicro    | X10SDV-TP8F                 | Server      | [b132017cc8](https://bsd-hardware.info/?probe=b132017cc8) | Nov 27, 2023 |
| GoWin Solu... | R86S-N                      | Desktop     | [1d40615c24](https://bsd-hardware.info/?probe=1d40615c24) | Nov 27, 2023 |
| WTM           | BKHD-N5105-5LAN B0          | Desktop     | [4d58c53d68](https://bsd-hardware.info/?probe=4d58c53d68) | Nov 27, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [af326ddda5](https://bsd-hardware.info/?probe=af326ddda5) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [14c7b94add](https://bsd-hardware.info/?probe=14c7b94add) | Nov 26, 2023 |
| Intel         | D33217GKE G76540-207        | Desktop     | [9b0af83da8](https://bsd-hardware.info/?probe=9b0af83da8) | Nov 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7241023750](https://bsd-hardware.info/?probe=7241023750) | Nov 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [268228d2b7](https://bsd-hardware.info/?probe=268228d2b7) | Nov 26, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [238143f959](https://bsd-hardware.info/?probe=238143f959) | Nov 26, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [de52fe9aef](https://bsd-hardware.info/?probe=de52fe9aef) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3dc51f3fe](https://bsd-hardware.info/?probe=c3dc51f3fe) | Nov 25, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [be568b54bf](https://bsd-hardware.info/?probe=be568b54bf) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [de7a23f9ca](https://bsd-hardware.info/?probe=de7a23f9ca) | Nov 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [06217360c6](https://bsd-hardware.info/?probe=06217360c6) | Nov 25, 2023 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [761475ca9e](https://bsd-hardware.info/?probe=761475ca9e) | Nov 24, 2023 |
| Dell          | Inspiron 7558               | Notebook    | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [d60cd55e61](https://bsd-hardware.info/?probe=d60cd55e61) | Nov 24, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [ece72d8870](https://bsd-hardware.info/?probe=ece72d8870) | Nov 24, 2023 |
| Google        | Dragonair                   | Notebook    | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [b479df9cfc](https://bsd-hardware.info/?probe=b479df9cfc) | Nov 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b7e6b2579a](https://bsd-hardware.info/?probe=b7e6b2579a) | Nov 24, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | Notebook    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| Dell          | Latitude E5440              | Notebook    | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [2756c10ff8](https://bsd-hardware.info/?probe=2756c10ff8) | Nov 23, 2023 |
| Dell          | 0MFXTY A01                  | Server      | [982b2609c5](https://bsd-hardware.info/?probe=982b2609c5) | Nov 23, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [d883d8bbd1](https://bsd-hardware.info/?probe=d883d8bbd1) | Nov 23, 2023 |
| Acer          | JM11-MS                     | Notebook    | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| HP            | 8767 A                      | Desktop     | [12aa6c74c7](https://bsd-hardware.info/?probe=12aa6c74c7) | Nov 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [086dd66ae7](https://bsd-hardware.info/?probe=086dd66ae7) | Nov 22, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [8181170ec9](https://bsd-hardware.info/?probe=8181170ec9) | Nov 22, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [0e4aa1cec5](https://bsd-hardware.info/?probe=0e4aa1cec5) | Nov 22, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [2c256503f5](https://bsd-hardware.info/?probe=2c256503f5) | Nov 22, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [f750403713](https://bsd-hardware.info/?probe=f750403713) | Nov 21, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [d9b122a533](https://bsd-hardware.info/?probe=d9b122a533) | Nov 21, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [9f690594a0](https://bsd-hardware.info/?probe=9f690594a0) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [9f4c9969f1](https://bsd-hardware.info/?probe=9f4c9969f1) | Nov 21, 2023 |
| Pegatron      | TRUCKEE                     | Desktop     | [8c8daeff55](https://bsd-hardware.info/?probe=8c8daeff55) | Nov 21, 2023 |
| Protectli     | FW4C                        | Desktop     | [7fa5301a63](https://bsd-hardware.info/?probe=7fa5301a63) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [cb2efd436d](https://bsd-hardware.info/?probe=cb2efd436d) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e5266f2a1](https://bsd-hardware.info/?probe=6e5266f2a1) | Nov 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [adcc84f66a](https://bsd-hardware.info/?probe=adcc84f66a) | Nov 20, 2023 |
| Supermicro    | A2SAP-HA                    | Desktop     | [c912b74149](https://bsd-hardware.info/?probe=c912b74149) | Nov 20, 2023 |
| AZW           | EQ                          | Desktop     | [9f0dd7c0b4](https://bsd-hardware.info/?probe=9f0dd7c0b4) | Nov 20, 2023 |
| Dell          | 01V648 A07                  | Server      | [cb698d50c6](https://bsd-hardware.info/?probe=cb698d50c6) | Nov 20, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [0b219600a3](https://bsd-hardware.info/?probe=0b219600a3) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [42bac7a450](https://bsd-hardware.info/?probe=42bac7a450) | Nov 19, 2023 |
| Sophos        | SG                          | Firewall    | [516a13a5f0](https://bsd-hardware.info/?probe=516a13a5f0) | Nov 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [41bb4c277b](https://bsd-hardware.info/?probe=41bb4c277b) | Nov 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e6bfeee196](https://bsd-hardware.info/?probe=e6bfeee196) | Nov 19, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [72987e629d](https://bsd-hardware.info/?probe=72987e629d) | Nov 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [05284d48bc](https://bsd-hardware.info/?probe=05284d48bc) | Nov 19, 2023 |
| Supermicro    | H8SML                       | Desktop     | [c4a58844c5](https://bsd-hardware.info/?probe=c4a58844c5) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| HP            | Notebook                    | Notebook    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [9ca9377fee](https://bsd-hardware.info/?probe=9ca9377fee) | Nov 17, 2023 |
| Protectli     | VP2420                      | Desktop     | [ee1cbf5fd0](https://bsd-hardware.info/?probe=ee1cbf5fd0) | Nov 17, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [1b811bacb7](https://bsd-hardware.info/?probe=1b811bacb7) | Nov 17, 2023 |
| HP            | Notebook                    | Notebook    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b34836b090](https://bsd-hardware.info/?probe=b34836b090) | Nov 16, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [7d9f6b4511](https://bsd-hardware.info/?probe=7d9f6b4511) | Nov 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| HP            | 18E7                        | Desktop     | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [b858bd0986](https://bsd-hardware.info/?probe=b858bd0986) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [db926657cc](https://bsd-hardware.info/?probe=db926657cc) | Nov 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [253d230fd3](https://bsd-hardware.info/?probe=253d230fd3) | Nov 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d74a1ddc22](https://bsd-hardware.info/?probe=d74a1ddc22) | Nov 14, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ea2d57ac16](https://bsd-hardware.info/?probe=ea2d57ac16) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [8b333abcaa](https://bsd-hardware.info/?probe=8b333abcaa) | Nov 13, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [bd3f1334ee](https://bsd-hardware.info/?probe=bd3f1334ee) | Nov 13, 2023 |
| Protectli     | VP4650                      | Desktop     | [0eeeb46242](https://bsd-hardware.info/?probe=0eeeb46242) | Nov 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a058c72d2c](https://bsd-hardware.info/?probe=a058c72d2c) | Nov 12, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [aabeab0c4f](https://bsd-hardware.info/?probe=aabeab0c4f) | Nov 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [57a9aedd4e](https://bsd-hardware.info/?probe=57a9aedd4e) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| MSI           | MS-7360                     | Desktop     | [07d8a855f3](https://bsd-hardware.info/?probe=07d8a855f3) | Nov 11, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0f681ab133](https://bsd-hardware.info/?probe=0f681ab133) | Nov 11, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [5993f3956e](https://bsd-hardware.info/?probe=5993f3956e) | Nov 11, 2023 |
| HP            | 805D                        | Desktop     | [f39c87a2a3](https://bsd-hardware.info/?probe=f39c87a2a3) | Nov 11, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [14493eb926](https://bsd-hardware.info/?probe=14493eb926) | Nov 11, 2023 |
| Intel         | HM570                       | Desktop     | [6079db8b21](https://bsd-hardware.info/?probe=6079db8b21) | Nov 11, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [0304f2c0f6](https://bsd-hardware.info/?probe=0304f2c0f6) | Nov 11, 2023 |
| Sophos        | XG                          | Firewall    | [3f3a233ec8](https://bsd-hardware.info/?probe=3f3a233ec8) | Nov 11, 2023 |
| Protectli     | FW6                         | Desktop     | [823022b2b0](https://bsd-hardware.info/?probe=823022b2b0) | Nov 10, 2023 |
| HP            | 1495                        | Desktop     | [e92d919eff](https://bsd-hardware.info/?probe=e92d919eff) | Nov 10, 2023 |
| Dell          | 0M788G A07                  | Server      | [6a8999de0e](https://bsd-hardware.info/?probe=6a8999de0e) | Nov 10, 2023 |
| HP            | 872C                        | Mini pc     | [6f2c2334f4](https://bsd-hardware.info/?probe=6f2c2334f4) | Nov 10, 2023 |
| Protectli     | VP2420                      | Desktop     | [3921d18b28](https://bsd-hardware.info/?probe=3921d18b28) | Nov 09, 2023 |
| PC Engines    | apu4                        | Desktop     | [85202e5b6e](https://bsd-hardware.info/?probe=85202e5b6e) | Nov 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | Notebook    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| HP            | 1495                        | Desktop     | [8be7b95a27](https://bsd-hardware.info/?probe=8be7b95a27) | Nov 09, 2023 |
| Gateway       | NV79                        | Notebook    | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [41e181dd6f](https://bsd-hardware.info/?probe=41e181dd6f) | Nov 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b6cd3662e9](https://bsd-hardware.info/?probe=b6cd3662e9) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| Intel         | QHSW02                      | Desktop     | [e06c922fda](https://bsd-hardware.info/?probe=e06c922fda) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [6ee8baf52b](https://bsd-hardware.info/?probe=6ee8baf52b) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [abaff39583](https://bsd-hardware.info/?probe=abaff39583) | Nov 08, 2023 |
| Samsung       | 740U5M                      | Convertible | [1a996f2f48](https://bsd-hardware.info/?probe=1a996f2f48) | Nov 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1987a99b64](https://bsd-hardware.info/?probe=1987a99b64) | Nov 07, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [dfdd6ff4c4](https://bsd-hardware.info/?probe=dfdd6ff4c4) | Nov 07, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [ed06cf2232](https://bsd-hardware.info/?probe=ed06cf2232) | Nov 07, 2023 |
| Unknown       | Raspberry Pi                | Soc         | [e2a506d1b7](https://bsd-hardware.info/?probe=e2a506d1b7) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Unknown       | QSKL01                      | Desktop     | [46543dd22d](https://bsd-hardware.info/?probe=46543dd22d) | Nov 07, 2023 |
| Intel         | QHSW02                      | Desktop     | [3203d5ee34](https://bsd-hardware.info/?probe=3203d5ee34) | Nov 07, 2023 |
| Intel         | HM570                       | Desktop     | [004550243c](https://bsd-hardware.info/?probe=004550243c) | Nov 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [624a69488f](https://bsd-hardware.info/?probe=624a69488f) | Nov 06, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [a0580939a5](https://bsd-hardware.info/?probe=a0580939a5) | Nov 06, 2023 |
| HP            | 213D A01                    | Desktop     | [d475dfa7a4](https://bsd-hardware.info/?probe=d475dfa7a4) | Nov 06, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [bc88549a37](https://bsd-hardware.info/?probe=bc88549a37) | Nov 06, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [02f5e40f3d](https://bsd-hardware.info/?probe=02f5e40f3d) | Nov 06, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [f6eb14f059](https://bsd-hardware.info/?probe=f6eb14f059) | Nov 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b1079a297](https://bsd-hardware.info/?probe=8b1079a297) | Nov 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [9e054bbcb2](https://bsd-hardware.info/?probe=9e054bbcb2) | Nov 06, 2023 |
| Dell          | 0M788G A07                  | Server      | [a404997d9d](https://bsd-hardware.info/?probe=a404997d9d) | Nov 06, 2023 |
| CncTion       | N6000-4L B0                 | Desktop     | [7ee545bad3](https://bsd-hardware.info/?probe=7ee545bad3) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| Supermicro    | H8SML                       | Desktop     | [ab650cfab8](https://bsd-hardware.info/?probe=ab650cfab8) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2a768a9f63](https://bsd-hardware.info/?probe=2a768a9f63) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [5d0e537b3e](https://bsd-hardware.info/?probe=5d0e537b3e) | Nov 05, 2023 |
| HP            | ProLiant ML10               | Desktop     | [43badefe76](https://bsd-hardware.info/?probe=43badefe76) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [ed0fb62285](https://bsd-hardware.info/?probe=ed0fb62285) | Nov 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [0b678c5e33](https://bsd-hardware.info/?probe=0b678c5e33) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [90a26f497a](https://bsd-hardware.info/?probe=90a26f497a) | Nov 04, 2023 |
| HP            | 18E4                        | Desktop     | [479b255034](https://bsd-hardware.info/?probe=479b255034) | Nov 03, 2023 |
| Protectli     | FW6                         | Desktop     | [2dc16f3849](https://bsd-hardware.info/?probe=2dc16f3849) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [db0f05f919](https://bsd-hardware.info/?probe=db0f05f919) | Nov 03, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [b729c4137a](https://bsd-hardware.info/?probe=b729c4137a) | Nov 03, 2023 |
| Lenovo        | 312D SDK0L22692 WIN 3306... | Mini pc     | [c958c2b087](https://bsd-hardware.info/?probe=c958c2b087) | Nov 02, 2023 |
| IBM           | FWA-3211 A102               | Server      | [8c4e5effec](https://bsd-hardware.info/?probe=8c4e5effec) | Nov 02, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [4fd9e1d707](https://bsd-hardware.info/?probe=4fd9e1d707) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [f1e1a3e8c8](https://bsd-hardware.info/?probe=f1e1a3e8c8) | Nov 02, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ff78edaee6](https://bsd-hardware.info/?probe=ff78edaee6) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [224cc728f5](https://bsd-hardware.info/?probe=224cc728f5) | Nov 02, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [f9df1890fa](https://bsd-hardware.info/?probe=f9df1890fa) | Nov 02, 2023 |
| Dell          | 0M788G A07                  | Server      | [3d5a1fc986](https://bsd-hardware.info/?probe=3d5a1fc986) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [83c8ab8d4b](https://bsd-hardware.info/?probe=83c8ab8d4b) | Nov 02, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3e55355c4b](https://bsd-hardware.info/?probe=3e55355c4b) | Nov 02, 2023 |
| Protectli     | VP2420                      | Desktop     | [7621eb7370](https://bsd-hardware.info/?probe=7621eb7370) | Nov 01, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [7e40f68fc3](https://bsd-hardware.info/?probe=7e40f68fc3) | Nov 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [5b6e9f8808](https://bsd-hardware.info/?probe=5b6e9f8808) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [24158fbe17](https://bsd-hardware.info/?probe=24158fbe17) | Oct 31, 2023 |
| Shuttle       | FS61                        | Desktop     | [2efb16a5f4](https://bsd-hardware.info/?probe=2efb16a5f4) | Oct 31, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| CheckPoint    | T-110-00                    | Desktop     | [970671ce27](https://bsd-hardware.info/?probe=970671ce27) | Oct 31, 2023 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [6b2553e06c](https://bsd-hardware.info/?probe=6b2553e06c) | Oct 30, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [da2fa90c43](https://bsd-hardware.info/?probe=da2fa90c43) | Oct 30, 2023 |
| Dell          | 0KP561                      | Desktop     | [cd0ae50eb0](https://bsd-hardware.info/?probe=cd0ae50eb0) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [10d46f39aa](https://bsd-hardware.info/?probe=10d46f39aa) | Oct 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5995fa3115](https://bsd-hardware.info/?probe=5995fa3115) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [c7e5f79b34](https://bsd-hardware.info/?probe=c7e5f79b34) | Oct 30, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [9567268d28](https://bsd-hardware.info/?probe=9567268d28) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [709f8e1566](https://bsd-hardware.info/?probe=709f8e1566) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f6542c47d](https://bsd-hardware.info/?probe=1f6542c47d) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b60083ef1f](https://bsd-hardware.info/?probe=b60083ef1f) | Oct 28, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ace25d235f](https://bsd-hardware.info/?probe=ace25d235f) | Oct 28, 2023 |
| HP            | 2AF7                        | Desktop     | [a45659c9d2](https://bsd-hardware.info/?probe=a45659c9d2) | Oct 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e99a14af3](https://bsd-hardware.info/?probe=3e99a14af3) | Oct 28, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [a012c0e1c9](https://bsd-hardware.info/?probe=a012c0e1c9) | Oct 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03ef00fab1](https://bsd-hardware.info/?probe=03ef00fab1) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [7a9e2d88ed](https://bsd-hardware.info/?probe=7a9e2d88ed) | Oct 27, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f8ae786555](https://bsd-hardware.info/?probe=f8ae786555) | Oct 27, 2023 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [8a1a0cdc32](https://bsd-hardware.info/?probe=8a1a0cdc32) | Oct 27, 2023 |
| Supermicro    | X10SLM+-LN4F                | Server      | [53651e09ac](https://bsd-hardware.info/?probe=53651e09ac) | Oct 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [233d4d3b64](https://bsd-hardware.info/?probe=233d4d3b64) | Oct 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3541caeb52](https://bsd-hardware.info/?probe=3541caeb52) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [f06cbf02dc](https://bsd-hardware.info/?probe=f06cbf02dc) | Oct 25, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [66f5010f59](https://bsd-hardware.info/?probe=66f5010f59) | Oct 24, 2023 |
| Protectli     | FW6                         | Desktop     | [9ba0e874f4](https://bsd-hardware.info/?probe=9ba0e874f4) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | Notebook    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [b42465c967](https://bsd-hardware.info/?probe=b42465c967) | Oct 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2424acbde7](https://bsd-hardware.info/?probe=2424acbde7) | Oct 23, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [8e622421c6](https://bsd-hardware.info/?probe=8e622421c6) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [2c004318d4](https://bsd-hardware.info/?probe=2c004318d4) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [6aea1130aa](https://bsd-hardware.info/?probe=6aea1130aa) | Oct 22, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [3a4d822cfc](https://bsd-hardware.info/?probe=3a4d822cfc) | Oct 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| Sophos        | SG                          | Firewall    | [cb44d7e49b](https://bsd-hardware.info/?probe=cb44d7e49b) | Oct 22, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [e12093f6bd](https://bsd-hardware.info/?probe=e12093f6bd) | Oct 22, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Dell          | 0M788G A07                  | Server      | [702549b133](https://bsd-hardware.info/?probe=702549b133) | Oct 21, 2023 |
| HP            | 8054                        | Desktop     | [71b61dc284](https://bsd-hardware.info/?probe=71b61dc284) | Oct 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3a35f074d9](https://bsd-hardware.info/?probe=3a35f074d9) | Oct 20, 2023 |
| Dell          | Latitude 5490               | Notebook    | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [48bb0077c3](https://bsd-hardware.info/?probe=48bb0077c3) | Oct 20, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [d40c67f9ca](https://bsd-hardware.info/?probe=d40c67f9ca) | Oct 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [3f7a4e2865](https://bsd-hardware.info/?probe=3f7a4e2865) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a8dd61b29b](https://bsd-hardware.info/?probe=a8dd61b29b) | Oct 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e85b1bd1ee](https://bsd-hardware.info/?probe=e85b1bd1ee) | Oct 19, 2023 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [bd9d649fb6](https://bsd-hardware.info/?probe=bd9d649fb6) | Oct 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [94f0b39689](https://bsd-hardware.info/?probe=94f0b39689) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [26a1b95e16](https://bsd-hardware.info/?probe=26a1b95e16) | Oct 19, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [6f6f1bf009](https://bsd-hardware.info/?probe=6f6f1bf009) | Oct 18, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [d8114642f5](https://bsd-hardware.info/?probe=d8114642f5) | Oct 18, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [1bf1c3b807](https://bsd-hardware.info/?probe=1bf1c3b807) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [0d647b68a6](https://bsd-hardware.info/?probe=0d647b68a6) | Oct 18, 2023 |
| AZW           | EQ                          | Desktop     | [71f6a16f5a](https://bsd-hardware.info/?probe=71f6a16f5a) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [b4ba6a7e52](https://bsd-hardware.info/?probe=b4ba6a7e52) | Oct 18, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [0f18316a17](https://bsd-hardware.info/?probe=0f18316a17) | Oct 18, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [3dffc4d445](https://bsd-hardware.info/?probe=3dffc4d445) | Oct 18, 2023 |
| HP            | 8299                        | Desktop     | [8da92e01e0](https://bsd-hardware.info/?probe=8da92e01e0) | Oct 17, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [0139098ee3](https://bsd-hardware.info/?probe=0139098ee3) | Oct 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [8ff0ba4fcb](https://bsd-hardware.info/?probe=8ff0ba4fcb) | Oct 16, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [3129e4f848](https://bsd-hardware.info/?probe=3129e4f848) | Oct 16, 2023 |
| Sophos        | SG                          | Firewall    | [d825f1a130](https://bsd-hardware.info/?probe=d825f1a130) | Oct 15, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [745b988354](https://bsd-hardware.info/?probe=745b988354) | Oct 15, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [128323ada4](https://bsd-hardware.info/?probe=128323ada4) | Oct 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [bf66ef021e](https://bsd-hardware.info/?probe=bf66ef021e) | Oct 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Protectli     | VP4650                      | Desktop     | [9c073eb854](https://bsd-hardware.info/?probe=9c073eb854) | Oct 15, 2023 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [ca5e8cfb2b](https://bsd-hardware.info/?probe=ca5e8cfb2b) | Oct 15, 2023 |
| Protectli     | VP2410                      | Desktop     | [aaffd45671](https://bsd-hardware.info/?probe=aaffd45671) | Oct 15, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [9d81c598a9](https://bsd-hardware.info/?probe=9d81c598a9) | Oct 15, 2023 |
| Sophos        | XG                          | Firewall    | [ab8b265b82](https://bsd-hardware.info/?probe=ab8b265b82) | Oct 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [95653dd42d](https://bsd-hardware.info/?probe=95653dd42d) | Oct 13, 2023 |
| Protectli     | FW4C                        | Desktop     | [16326174bb](https://bsd-hardware.info/?probe=16326174bb) | Oct 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [b57183cbb0](https://bsd-hardware.info/?probe=b57183cbb0) | Oct 13, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [30f97615e6](https://bsd-hardware.info/?probe=30f97615e6) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [9145630ed9](https://bsd-hardware.info/?probe=9145630ed9) | Oct 12, 2023 |
| IBM           | ThinkPad R51 2889W11        | Notebook    | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [cdc40fe6a3](https://bsd-hardware.info/?probe=cdc40fe6a3) | Oct 11, 2023 |
| Dell          | Precision 7550              | Notebook    | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [67379c4768](https://bsd-hardware.info/?probe=67379c4768) | Oct 11, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3aa38e5b1f](https://bsd-hardware.info/?probe=3aa38e5b1f) | Oct 10, 2023 |
| AZW           | EQ                          | Desktop     | [ea7e5029de](https://bsd-hardware.info/?probe=ea7e5029de) | Oct 10, 2023 |
| Dell          | 03X6X0 A00                  | Server      | [26e755b8be](https://bsd-hardware.info/?probe=26e755b8be) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [89d680cba1](https://bsd-hardware.info/?probe=89d680cba1) | Oct 09, 2023 |
| Dell          | 065TRV A04                  | Server      | [2d07fc66b5](https://bsd-hardware.info/?probe=2d07fc66b5) | Oct 09, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | Desktop     | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [80e01e48bf](https://bsd-hardware.info/?probe=80e01e48bf) | Oct 09, 2023 |
| ASRock        | Z690M Phantom Gaming 4      | Desktop     | [20ff855aec](https://bsd-hardware.info/?probe=20ff855aec) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a64ed6b5d1](https://bsd-hardware.info/?probe=a64ed6b5d1) | Oct 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [bb66634f7c](https://bsd-hardware.info/?probe=bb66634f7c) | Oct 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| MSI           | Aspen                       | Desktop     | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | Notebook    | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [f3f37dd0e7](https://bsd-hardware.info/?probe=f3f37dd0e7) | Oct 06, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [fb6d008bfc](https://bsd-hardware.info/?probe=fb6d008bfc) | Oct 06, 2023 |
| Intel         | QHSW02                      | Desktop     | [e0d4a273f5](https://bsd-hardware.info/?probe=e0d4a273f5) | Oct 06, 2023 |
| HP            | 8056                        | Desktop     | [7516a37588](https://bsd-hardware.info/?probe=7516a37588) | Oct 06, 2023 |
| Dell          | 0XN8Y6 A09                  | Server      | [0aa4133255](https://bsd-hardware.info/?probe=0aa4133255) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [da4e03cd91](https://bsd-hardware.info/?probe=da4e03cd91) | Oct 05, 2023 |
| Win elemen... | M600                        | Desktop     | [27492e0298](https://bsd-hardware.info/?probe=27492e0298) | Oct 04, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [17406f5021](https://bsd-hardware.info/?probe=17406f5021) | Oct 04, 2023 |
| Protectli     | FW4C                        | Desktop     | [671429444f](https://bsd-hardware.info/?probe=671429444f) | Oct 04, 2023 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [1792df4520](https://bsd-hardware.info/?probe=1792df4520) | Oct 04, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [4fa9bbbecf](https://bsd-hardware.info/?probe=4fa9bbbecf) | Oct 03, 2023 |
| HP            | 83E2                        | Desktop     | [dbb1010907](https://bsd-hardware.info/?probe=dbb1010907) | Oct 03, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [cab6cdb306](https://bsd-hardware.info/?probe=cab6cdb306) | Oct 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d5d794abdb](https://bsd-hardware.info/?probe=d5d794abdb) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Protectli     | VP2420                      | Desktop     | [c77ef1792c](https://bsd-hardware.info/?probe=c77ef1792c) | Oct 02, 2023 |
| Protectli     | VP46xx                      | Desktop     | [4985863bd8](https://bsd-hardware.info/?probe=4985863bd8) | Oct 01, 2023 |
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [fc2ba7c8d8](https://bsd-hardware.info/?probe=fc2ba7c8d8) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| MUCAI         | H61 V1.6A                   | Desktop     | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cda7be3da8](https://bsd-hardware.info/?probe=cda7be3da8) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0f1805a40e](https://bsd-hardware.info/?probe=0f1805a40e) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d86474bd03](https://bsd-hardware.info/?probe=d86474bd03) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [57577a5f14](https://bsd-hardware.info/?probe=57577a5f14) | Sep 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7cdc9b73e](https://bsd-hardware.info/?probe=d7cdc9b73e) | Sep 26, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3c10d0b8ed](https://bsd-hardware.info/?probe=3c10d0b8ed) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [bc62c36654](https://bsd-hardware.info/?probe=bc62c36654) | Sep 25, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | Desktop     | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Protectli     | VP4630                      | Desktop     | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| HP            | 8522 A01                    | Mini pc     | [dd5d9863aa](https://bsd-hardware.info/?probe=dd5d9863aa) | Sep 19, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ed7bef076e](https://bsd-hardware.info/?probe=ed7bef076e) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7c6f946c9b](https://bsd-hardware.info/?probe=7c6f946c9b) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [815d9f2867](https://bsd-hardware.info/?probe=815d9f2867) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [35fbb60b50](https://bsd-hardware.info/?probe=35fbb60b50) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1f54d2bb5b](https://bsd-hardware.info/?probe=1f54d2bb5b) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | OptiPlex 3020               | Desktop     | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | Desktop     | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| ASRock        | J3455M                      | Desktop     | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [f3594b1f7c](https://bsd-hardware.info/?probe=f3594b1f7c) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [8b541c71a9](https://bsd-hardware.info/?probe=8b541c71a9) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6610a56ab4](https://bsd-hardware.info/?probe=6610a56ab4) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ccc62ac366](https://bsd-hardware.info/?probe=ccc62ac366) | Sep 10, 2023 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [5ef436c661](https://bsd-hardware.info/?probe=5ef436c661) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [525ed7878c](https://bsd-hardware.info/?probe=525ed7878c) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [0131f46755](https://bsd-hardware.info/?probe=0131f46755) | Sep 10, 2023 |
| AZW           | EQ                          | Desktop     | [c6f83de1e4](https://bsd-hardware.info/?probe=c6f83de1e4) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Unknown       | QGLK03                      | Desktop     | [42ea8dfb44](https://bsd-hardware.info/?probe=42ea8dfb44) | Sep 10, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [52764da7d8](https://bsd-hardware.info/?probe=52764da7d8) | Sep 10, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [332a3f8516](https://bsd-hardware.info/?probe=332a3f8516) | Sep 09, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [8579d5fa0d](https://bsd-hardware.info/?probe=8579d5fa0d) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [7ea278ed7a](https://bsd-hardware.info/?probe=7ea278ed7a) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [331f3de91a](https://bsd-hardware.info/?probe=331f3de91a) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee507594a0](https://bsd-hardware.info/?probe=ee507594a0) | Sep 09, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d197cf04](https://bsd-hardware.info/?probe=07d197cf04) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e51c11ed2](https://bsd-hardware.info/?probe=2e51c11ed2) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [480823e372](https://bsd-hardware.info/?probe=480823e372) | Sep 08, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [122601f717](https://bsd-hardware.info/?probe=122601f717) | Sep 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [4580cb5481](https://bsd-hardware.info/?probe=4580cb5481) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aaeb12b1c6](https://bsd-hardware.info/?probe=aaeb12b1c6) | Sep 08, 2023 |
| Protectli     | VP2420                      | Desktop     | [2a8eb1b056](https://bsd-hardware.info/?probe=2a8eb1b056) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [fa747c859f](https://bsd-hardware.info/?probe=fa747c859f) | Sep 08, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [a3e54e7628](https://bsd-hardware.info/?probe=a3e54e7628) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [eff74e8df0](https://bsd-hardware.info/?probe=eff74e8df0) | Sep 07, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [7c0acfa5b9](https://bsd-hardware.info/?probe=7c0acfa5b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [94d9b19ade](https://bsd-hardware.info/?probe=94d9b19ade) | Sep 07, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b5aa3f010f](https://bsd-hardware.info/?probe=b5aa3f010f) | Sep 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12145f939b](https://bsd-hardware.info/?probe=12145f939b) | Sep 07, 2023 |
| Dell          | 0KM5PX A01                  | Server      | [67f910daa9](https://bsd-hardware.info/?probe=67f910daa9) | Sep 06, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [4397f70291](https://bsd-hardware.info/?probe=4397f70291) | Sep 06, 2023 |
| AZW           | MINI S 10                   | Desktop     | [2daf516a05](https://bsd-hardware.info/?probe=2daf516a05) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | Notebook    | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [3af68f2594](https://bsd-hardware.info/?probe=3af68f2594) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ec3e0338eb](https://bsd-hardware.info/?probe=ec3e0338eb) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [84d768ee15](https://bsd-hardware.info/?probe=84d768ee15) | Sep 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3fb536ecce](https://bsd-hardware.info/?probe=3fb536ecce) | Sep 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Dell          | 0X3D66 A02                  | Server      | [8dcfb77863](https://bsd-hardware.info/?probe=8dcfb77863) | Sep 05, 2023 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [e92272bb87](https://bsd-hardware.info/?probe=e92272bb87) | Sep 05, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [bff90e93d0](https://bsd-hardware.info/?probe=bff90e93d0) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a4796e8170](https://bsd-hardware.info/?probe=a4796e8170) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [8cc0358a69](https://bsd-hardware.info/?probe=8cc0358a69) | Sep 04, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [dd32d9d4e1](https://bsd-hardware.info/?probe=dd32d9d4e1) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [7d95befe6e](https://bsd-hardware.info/?probe=7d95befe6e) | Sep 04, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [1b07865ce7](https://bsd-hardware.info/?probe=1b07865ce7) | Sep 04, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [58e061f420](https://bsd-hardware.info/?probe=58e061f420) | Sep 03, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fe53c55492](https://bsd-hardware.info/?probe=fe53c55492) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1ae33cfe72](https://bsd-hardware.info/?probe=1ae33cfe72) | Sep 02, 2023 |
| ASRock        | J3455M                      | Desktop     | [762d4d9370](https://bsd-hardware.info/?probe=762d4d9370) | Sep 02, 2023 |
| Dell          | 0XCR8D A00                  | Desktop     | [b89126c9d9](https://bsd-hardware.info/?probe=b89126c9d9) | Sep 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b63ded7b81](https://bsd-hardware.info/?probe=b63ded7b81) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [94487109c2](https://bsd-hardware.info/?probe=94487109c2) | Sep 01, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [708af02c7b](https://bsd-hardware.info/?probe=708af02c7b) | Sep 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [9e6cb6fe25](https://bsd-hardware.info/?probe=9e6cb6fe25) | Sep 01, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [525a1718ff](https://bsd-hardware.info/?probe=525a1718ff) | Sep 01, 2023 |
| Shuttle       | FS77U                       | Desktop     | [149a8a1437](https://bsd-hardware.info/?probe=149a8a1437) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [d9f360b4fe](https://bsd-hardware.info/?probe=d9f360b4fe) | Aug 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2557e04cf5](https://bsd-hardware.info/?probe=2557e04cf5) | Aug 31, 2023 |
| Intel         | NUC8i7HNB J68197-602        | Mini pc     | [f2806a3c65](https://bsd-hardware.info/?probe=f2806a3c65) | Aug 31, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [b2a1070e2d](https://bsd-hardware.info/?probe=b2a1070e2d) | Aug 31, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [363a27fb74](https://bsd-hardware.info/?probe=363a27fb74) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [97975e788b](https://bsd-hardware.info/?probe=97975e788b) | Aug 30, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Infoblox      | IB-810                      | Desktop     | [34c0fa6bec](https://bsd-hardware.info/?probe=34c0fa6bec) | Aug 30, 2023 |
| Supermicro    | X12SDV-8C-SPT8FA            | Server      | [c46557f737](https://bsd-hardware.info/?probe=c46557f737) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [259a7ec99d](https://bsd-hardware.info/?probe=259a7ec99d) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [20946147de](https://bsd-hardware.info/?probe=20946147de) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [8cfa60050b](https://bsd-hardware.info/?probe=8cfa60050b) | Aug 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [c8b4f33fb1](https://bsd-hardware.info/?probe=c8b4f33fb1) | Aug 30, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [c90edbc46a](https://bsd-hardware.info/?probe=c90edbc46a) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e0d13077ea](https://bsd-hardware.info/?probe=e0d13077ea) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a84c23941d](https://bsd-hardware.info/?probe=a84c23941d) | Aug 27, 2023 |
| Protectli     | FW6                         | Desktop     | [37b744ff79](https://bsd-hardware.info/?probe=37b744ff79) | Aug 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| HP            | 8103 A01                    | Mini pc     | [484d82cac6](https://bsd-hardware.info/?probe=484d82cac6) | Aug 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | Desktop     | [21e958a05d](https://bsd-hardware.info/?probe=21e958a05d) | Aug 26, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [bf289c5941](https://bsd-hardware.info/?probe=bf289c5941) | Aug 26, 2023 |
| HP            | 8299                        | Desktop     | [77a077cb11](https://bsd-hardware.info/?probe=77a077cb11) | Aug 26, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 118       | 2.5%    |
| OPNsense 21.7.7   | 90        | 1.91%   |
| OPNsense 22.7.10  | 82        | 1.74%   |
| OPNsense 23.7.10  | 81        | 1.72%   |
| OPNsense 23.1     | 80        | 1.69%   |
| OPNsense 21.7.3   | 77        | 1.63%   |
| OPNsense 23.7.9   | 70        | 1.48%   |
| OPNsense 23.1.7   | 69        | 1.46%   |
| OPNsense 21.7.1   | 69        | 1.46%   |
| OPNsense 23.1.1   | 68        | 1.44%   |
| OPNsense 22.1     | 68        | 1.44%   |
| OPNsense 22.1.10  | 67        | 1.42%   |
| OPNsense 21.1.5   | 67        | 1.42%   |
| helloSystem 0.7.0 | 66        | 1.4%    |
| OPNsense 23.1.5   | 65        | 1.38%   |
| OPNsense 22.7.4   | 65        | 1.38%   |
| helloSystem 0.8.1 | 65        | 1.38%   |
| OPNsense 20.7.8   | 61        | 1.29%   |
| OPNsense 21.1.4   | 60        | 1.27%   |
| FreeBSD 13.0      | 60        | 1.27%   |
| OPNsense 23.7.1   | 58        | 1.23%   |
| OPNsense 22.1.8   | 58        | 1.23%   |
| OPNsense 21.1.3   | 58        | 1.23%   |
| FreeBSD 13.1      | 57        | 1.21%   |
| OPNsense 23.1.9   | 54        | 1.14%   |
| OPNsense 23.1.6   | 54        | 1.14%   |
| OPNsense 23.7.7   | 53        | 1.12%   |
| OPNsense 23.7.3   | 53        | 1.12%   |
| OPNsense 23.7.12  | 52        | 1.1%    |
| OPNsense 24.1.1   | 51        | 1.08%   |
| OPNsense 23.7.11  | 51        | 1.08%   |
| OPNsense 21.1     | 51        | 1.08%   |
| OPNsense 22.7.9   | 50        | 1.06%   |
| OPNsense 22.7.6   | 50        | 1.06%   |
| OPNsense 21.1.8   | 50        | 1.06%   |
| OPNsense 23.7     | 48        | 1.02%   |
| helloSystem 0.8.0 | 48        | 1.02%   |
| OPNsense 22.7.8   | 45        | 0.95%   |
| OPNsense 22.7.2   | 45        | 0.95%   |
| OPNsense 23.7.8   | 43        | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 2194      | 65.01%  |
| FreeBSD     | 577       | 17.1%   |
| helloSystem | 287       | 8.5%    |
| OpenBSD     | 112       | 3.32%   |
| GhostBSD    | 68        | 2.01%   |
| NomadBSD    | 38        | 1.13%   |
| pfSense     | 19        | 0.56%   |
| FreeNAS     | 17        | 0.5%    |
| MidnightBSD | 16        | 0.47%   |
| TrueNAS     | 11        | 0.33%   |
| NetBSD      | 11        | 0.33%   |
| HardenedBSD | 9         | 0.27%   |
| DragonFly   | 6         | 0.18%   |
| XigmaNAS    | 3         | 0.09%   |
| FuryBSD     | 3         | 0.09%   |
| OS108       | 2         | 0.06%   |
| MyBee       | 1         | 0.03%   |
| ClonOS      | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 3279      | 98.03%  |
| i386    | 31        | 0.93%   |
| arm64   | 26        | 0.78%   |
| powerpc | 4         | 0.12%   |
| evbarm  | 3         | 0.09%   |
| sparc64 | 1         | 0.03%   |
| macppc  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 2464      | 72.19%  |
| helloDesktop  | 315       | 9.23%   |
| XFCE          | 125       | 3.66%   |
| MATE          | 96        | 2.81%   |
| KDE5          | 95        | 2.78%   |
| TWM           | 59        | 1.73%   |
| fvwm          | 59        | 1.73%   |
| GNOME         | 56        | 1.64%   |
| Openbox       | 53        | 1.55%   |
| i3            | 33        | 0.97%   |
| Cinnamon      | 12        | 0.35%   |
| Enlightenment | 8         | 0.23%   |
| LXQt          | 6         | 0.18%   |
| Fluxbox       | 6         | 0.18%   |
| Lumina        | 5         | 0.15%   |
| DWM           | 3         | 0.09%   |
| AwesomeWM     | 3         | 0.09%   |
| Xfwm4         | 2         | 0.06%   |
| Picom         | 2         | 0.06%   |
| GNUstep       | 2         | 0.06%   |
| wlroots       | 1         | 0.03%   |
| Window Maker  | 1         | 0.03%   |
| spectrwm      | 1         | 0.03%   |
| sdorfehs      | 1         | 0.03%   |
| LXDE          | 1         | 0.03%   |
| KDE           | 1         | 0.03%   |
| fvwm2         | 1         | 0.03%   |
| Compton       | 1         | 0.03%   |
| CDE           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2492      | 74.08%  |
| X11     | 862       | 25.62%  |
| Wayland | 10        | 0.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2704      | 79.83%  |
| SLiM    | 385       | 11.37%  |
| LightDM | 115       | 3.4%    |
| SDDM    | 93        | 2.75%   |
| XDM     | 50        | 1.48%   |
| GDM     | 37        | 1.09%   |
| Ly      | 3         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 2539      | 74.13%  |
| en_US           | 450       | 13.14%  |
| C               | 380       | 11.09%  |
| en              | 34        | 0.99%   |
| fr_FR           | 6         | 0.18%   |
| fr              | 4         | 0.12%   |
| ru_RU           | 2         | 0.06%   |
| en_US.US-ASCII  | 2         | 0.06%   |
| en_US.ISO8859-1 | 2         | 0.06%   |
| en_GB           | 2         | 0.06%   |
| ru              | 1         | 0.03%   |
| es_CO           | 1         | 0.03%   |
| en_US.utf-8     | 1         | 0.03%   |
| de_DE           | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2940      | 86.57%  |
| BIOS | 456       | 13.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1694      | 49.09%  |
| Zfs     | 1539      | 44.6%   |
| Ffs     | 112       | 3.25%   |
| Cd9660  | 99        | 2.87%   |
| Hammer2 | 6         | 0.17%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3135      | 92.81%  |
| MBR     | 209       | 6.19%   |
| Unknown | 26        | 0.77%   |
| BSD     | 8         | 0.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 547       | 16.36%  |
| Hewlett-Packard         | 324       | 9.69%   |
| Lenovo                  | 298       | 8.91%   |
| Unknown                 | 290       | 8.67%   |
| Supermicro              | 261       | 7.81%   |
| Protectli               | 244       | 7.3%    |
| ASUSTek Computer        | 208       | 6.22%   |
| Intel                   | 140       | 4.19%   |
| ASRock                  | 120       | 3.59%   |
| Gigabyte Technology     | 94        | 2.81%   |
| MSI                     | 84        | 2.51%   |
| AMI                     | 61        | 1.82%   |
| Apple                   | 54        | 1.62%   |
| PC Engines              | 44        | 1.32%   |
| Acer                    | 35        | 1.05%   |
| AZW                     | 31        | 0.93%   |
| Techvision              | 29        | 0.87%   |
| Sophos                  | 27        | 0.81%   |
| Deciso                  | 23        | 0.69%   |
| MW                      | 16        | 0.48%   |
| Google                  | 16        | 0.48%   |
| CWWK                    | 15        | 0.45%   |
| Toshiba                 | 13        | 0.39%   |
| CompuLab                | 13        | 0.39%   |
| Biostar                 | 13        | 0.39%   |
| BESSTAR Tech            | 13        | 0.39%   |
| ASRockRack              | 13        | 0.39%   |
| AWOW                    | 12        | 0.36%   |
| System76                | 10        | 0.3%    |
| Shuttle                 | 10        | 0.3%    |
| Foxconn                 | 10        | 0.3%    |
| Seeed Studio            | 9         | 0.27%   |
| Raspberry Pi Foundation | 9         | 0.27%   |
| Fujitsu                 | 9         | 0.27%   |
| IceWhale Technology     | 7         | 0.21%   |
| Hardkernel              | 7         | 0.21%   |
| GoWin Solution          | 7         | 0.21%   |
| Framework               | 7         | 0.21%   |
| Datto                   | 7         | 0.21%   |
| CheckPoint              | 7         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 299       | 8.94%   |
| Protectli FW4B                      | 77        | 2.3%    |
| Supermicro Super Server             | 69        | 2.06%   |
| Protectli FW6                       | 63        | 1.88%   |
| AMI Aptio CRB                       | 54        | 1.62%   |
| Intel Q3XXG4-P V1.0                 | 42        | 1.26%   |
| HP t730 Thin Client                 | 32        | 0.96%   |
| Techvision TVI7309X                 | 29        | 0.87%   |
| Dell OptiPlex 9020                  | 29        | 0.87%   |
| Dell PowerEdge R210 II              | 28        | 0.84%   |
| ASUS All Series                     | 27        | 0.81%   |
| HP t620 PLUS Quad Core TC           | 26        | 0.78%   |
| Dell OptiPlex 3020                  | 26        | 0.78%   |
| Supermicro X9SCL/X9SCM              | 22        | 0.66%   |
| Supermicro X10SLH-N6-ST031          | 22        | 0.66%   |
| PC Engines APU2                     | 22        | 0.66%   |
| Dell OptiPlex 7010                  | 20        | 0.6%    |
| Protectli FW4C                      | 17        | 0.51%   |
| PC Engines apu4                     | 17        | 0.51%   |
| Protectli VP2420                    | 16        | 0.48%   |
| Protectli FW2B                      | 16        | 0.48%   |
| MW GMLK-2_5G4L                      | 16        | 0.48%   |
| Protectli VP2410                    | 15        | 0.45%   |
| Dell Wyse 5070 Extended Thin Client | 15        | 0.45%   |
| AZW EQ                              | 15        | 0.45%   |
| Sophos XG                           | 14        | 0.42%   |
| Dell OptiPlex 7040                  | 14        | 0.42%   |
| Dell OptiPlex 990                   | 13        | 0.39%   |
| CompuLab fitlet2                    | 13        | 0.39%   |
| HP EliteDesk 800 G1 SFF             | 12        | 0.36%   |
| Supermicro A1SAi                    | 11        | 0.33%   |
| Sophos SG                           | 11        | 0.33%   |
| Protectli FW1                       | 11        | 0.33%   |
| HP EliteDesk 800 G3 SFF             | 11        | 0.33%   |
| Dell PowerEdge R610                 | 10        | 0.3%    |
| Dell OptiPlex 9010                  | 10        | 0.3%    |
| Dell OptiPlex 790                   | 10        | 0.3%    |
| Dell OptiPlex 3040                  | 10        | 0.3%    |
| Deciso Netboard A20                 | 10        | 0.3%    |
| ASUS TUF GAMING X570-PLUS           | 10        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 299       | 8.94%   |
| Dell OptiPlex              | 219       | 6.55%   |
| Lenovo ThinkPad            | 160       | 4.79%   |
| Dell PowerEdge             | 141       | 4.22%   |
| Lenovo ThinkCentre         | 80        | 2.39%   |
| Protectli FW4B             | 77        | 2.3%    |
| Supermicro Super           | 69        | 2.06%   |
| Protectli FW6              | 63        | 1.88%   |
| Dell Inspiron              | 54        | 1.62%   |
| AMI Aptio                  | 54        | 1.62%   |
| HP EliteDesk               | 52        | 1.56%   |
| Dell Latitude              | 47        | 1.41%   |
| Intel Q3XXG4-P             | 43        | 1.29%   |
| HP ProDesk                 | 34        | 1.02%   |
| Dell Precision             | 33        | 0.99%   |
| ASUS ROG                   | 33        | 0.99%   |
| HP t730                    | 32        | 0.96%   |
| ASUS TUF                   | 31        | 0.93%   |
| Techvision TVI7309X        | 29        | 0.87%   |
| HP t620                    | 28        | 0.84%   |
| HP Compaq                  | 27        | 0.81%   |
| ASUS PRIME                 | 27        | 0.81%   |
| ASUS All                   | 27        | 0.81%   |
| HP Pavilion                | 24        | 0.72%   |
| HP ProLiant                | 23        | 0.69%   |
| Supermicro X9SCL           | 22        | 0.66%   |
| Supermicro X10SLH-N6-ST031 | 22        | 0.66%   |
| PC Engines APU2            | 22        | 0.66%   |
| Dell Wyse                  | 18        | 0.54%   |
| Acer Aspire                | 18        | 0.54%   |
| Protectli FW4C             | 17        | 0.51%   |
| PC Engines apu4            | 17        | 0.51%   |
| Protectli VP2420           | 16        | 0.48%   |
| Protectli FW2B             | 16        | 0.48%   |
| MW GMLK-2                  | 16        | 0.48%   |
| Protectli VP2410           | 15        | 0.45%   |
| Lenovo IdeaPad             | 15        | 0.45%   |
| Dell XPS                   | 15        | 0.45%   |
| AZW EQ                     | 15        | 0.45%   |
| ASRock X570                | 15        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 411       | 12.29%  |
| 2022    | 321       | 9.6%    |
| 2019    | 304       | 9.09%   |
| 2020    | 277       | 8.29%   |
| 2021    | 266       | 7.96%   |
| 2016    | 239       | 7.15%   |
| 2014    | 218       | 6.52%   |
| 2015    | 190       | 5.68%   |
| 2013    | 185       | 5.53%   |
| 2011    | 182       | 5.44%   |
| 2017    | 173       | 5.17%   |
| 2012    | 162       | 4.85%   |
| 2023    | 150       | 4.49%   |
| 2010    | 76        | 2.27%   |
| 2009    | 51        | 1.53%   |
| 2008    | 47        | 1.41%   |
| Unknown | 44        | 1.32%   |
| 2007    | 22        | 0.66%   |
| 2006    | 15        | 0.45%   |
| 2004    | 4         | 0.12%   |
| 2005    | 3         | 0.09%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 2138      | 63.95%  |
| Notebook       | 543       | 16.24%  |
| Server         | 328       | 9.81%   |
| Mini pc        | 248       | 7.42%   |
| Firewall       | 37        | 1.11%   |
| Convertible    | 21        | 0.63%   |
| System on chip | 18        | 0.54%   |
| All in one     | 9         | 0.27%   |
| Stick pc       | 1         | 0.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3216      | 96.2%   |
| Yes  | 127       | 3.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1225      | 35.63%  |
| 16.01-24.0      | 890       | 25.89%  |
| 4.01-8.0        | 500       | 14.54%  |
| 32.01-64.0      | 426       | 12.39%  |
| 64.01-256.0     | 191       | 5.56%   |
| 24.01-32.0      | 68        | 1.98%   |
| 2.01-3.0        | 68        | 1.98%   |
| 3.01-4.0        | 32        | 0.93%   |
| 0.51-1.0        | 15        | 0.44%   |
| 1.01-2.0        | 9         | 0.26%   |
| 0.01-0.5        | 8         | 0.23%   |
| More than 256.0 | 6         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1481      | 42.4%   |
| 0.51-1.0    | 1135      | 32.49%  |
| 1.01-2.0    | 524       | 15%     |
| 2.01-3.0    | 102       | 2.92%   |
| 4.01-8.0    | 71        | 2.03%   |
| 3.01-4.0    | 52        | 1.49%   |
| 8.01-16.0   | 42        | 1.2%    |
| 16.01-24.0  | 19        | 0.54%   |
| 24.01-32.0  | 18        | 0.52%   |
| Unknown     | 16        | 0.46%   |
| 32.01-64.0  | 14        | 0.4%    |
| 0           | 13        | 0.37%   |
| 64.01-256.0 | 6         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2372      | 68.5%   |
| 2      | 444       | 12.82%  |
| 0      | 343       | 9.9%    |
| 3      | 121       | 3.49%   |
| 4      | 54        | 1.56%   |
| 5      | 34        | 0.98%   |
| 6      | 25        | 0.72%   |
| 7      | 14        | 0.4%    |
| 8      | 9         | 0.26%   |
| 14     | 8         | 0.23%   |
| 10     | 7         | 0.2%    |
| 12     | 6         | 0.17%   |
| 9      | 6         | 0.17%   |
| 11     | 4         | 0.12%   |
| 21     | 2         | 0.06%   |
| 18     | 2         | 0.06%   |
| 17     | 2         | 0.06%   |
| 58     | 1         | 0.03%   |
| 40     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 26     | 1         | 0.03%   |
| 22     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 15     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2679      | 79.31%  |
| Yes       | 699       | 20.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3204      | 95.84%  |
| No        | 139       | 4.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2249      | 66.66%  |
| Yes       | 1125      | 33.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2577      | 76.51%  |
| Yes       | 791       | 23.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 3343      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Seattle        | 62        | 1.67%   |
| Brooklyn       | 53        | 1.42%   |
| New York       | 50        | 1.34%   |
| Denver         | 49        | 1.32%   |
| Chicago        | 47        | 1.26%   |
| Los Angeles    | 39        | 1.05%   |
| Portland       | 37        | 0.99%   |
| Dallas         | 36        | 0.97%   |
| Austin         | 31        | 0.83%   |
| Atlanta        | 28        | 0.75%   |
| San Francisco  | 27        | 0.73%   |
| Phoenix        | 25        | 0.67%   |
| Rochester      | 23        | 0.62%   |
| Oakland        | 22        | 0.59%   |
| Houston        | 22        | 0.59%   |
| Columbus       | 22        | 0.59%   |
| Mountain View  | 20        | 0.54%   |
| San Antonio    | 19        | 0.51%   |
| Grand Rapids   | 19        | 0.51%   |
| Springfield    | 18        | 0.48%   |
| Las Vegas      | 18        | 0.48%   |
| San Jose       | 17        | 0.46%   |
| Philadelphia   | 16        | 0.43%   |
| Oklahoma City  | 16        | 0.43%   |
| Charlotte      | 16        | 0.43%   |
| Orlando        | 15        | 0.4%    |
| Ypsilanti      | 14        | 0.38%   |
| Salt Lake City | 14        | 0.38%   |
| Omaha          | 14        | 0.38%   |
| Minneapolis    | 14        | 0.38%   |
| Jacksonville   | 14        | 0.38%   |
| Raleigh        | 13        | 0.35%   |
| Pittsburgh     | 13        | 0.35%   |
| Kansas City    | 13        | 0.35%   |
| Salem          | 12        | 0.32%   |
| Milwaukee      | 12        | 0.32%   |
| Indianapolis   | 12        | 0.32%   |
| Fremont        | 12        | 0.32%   |
| Washington     | 11        | 0.3%    |
| San Diego      | 11        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 619       | 1220   | 16.09%  |
| WDC                 | 447       | 1365   | 11.62%  |
| Seagate             | 324       | 871    | 8.42%   |
| Kingston            | 253       | 344    | 6.58%   |
| Crucial             | 191       | 304    | 4.96%   |
| Intel               | 179       | 345    | 4.65%   |
| SanDisk             | 164       | 219    | 4.26%   |
| Toshiba             | 137       | 240    | 3.56%   |
| Transcend           | 131       | 240    | 3.41%   |
| SK hynix            | 90        | 130    | 2.34%   |
| Hoodisk             | 82        | 116    | 2.13%   |
| China               | 80        | 128    | 2.08%   |
| A-DATA Technology   | 78        | 120    | 2.03%   |
| Hitachi             | 74        | 171    | 1.92%   |
| Phison              | 69        | 111    | 1.79%   |
| Protectli           | 67        | 111    | 1.74%   |
| PNY                 | 67        | 103    | 1.74%   |
| SPCC                | 65        | 121    | 1.69%   |
| HGST                | 44        | 130    | 1.14%   |
| Hewlett-Packard     | 43        | 128    | 1.12%   |
| Micron Technology   | 40        | 56     | 1.04%   |
| Team                | 36        | 64     | 0.94%   |
| Dogfish             | 34        | 60     | 0.88%   |
| BIWIN               | 30        | 48     | 0.78%   |
| NVMe                | 29        | 40     | 0.75%   |
| FORESEE             | 28        | 44     | 0.73%   |
| OCZ                 | 25        | 38     | 0.65%   |
| Silicon Motion      | 23        | 34     | 0.6%    |
| Apple               | 23        | 27     | 0.6%    |
| KingSpec            | 17        | 21     | 0.44%   |
| Apacer              | 17        | 24     | 0.44%   |
| Lexar               | 16        | 23     | 0.42%   |
| KIOXIA              | 16        | 22     | 0.42%   |
| Corsair             | 16        | 47     | 0.42%   |
| Mushkin             | 15        | 22     | 0.39%   |
| Patriot             | 14        | 17     | 0.36%   |
| Fanxiang            | 13        | 20     | 0.34%   |
| LITEON              | 12        | 18     | 0.31%   |
| OWC                 | 11        | 17     | 0.29%   |
| Zheino              | 10        | 18     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 34        | 0.81%   |
| Kingston SA400S37240G 240GB     | 34        | 0.81%   |
| Hoodisk SSD 32GB                | 32        | 0.76%   |
| Samsung SSD 970 EVO Plus 500GB  | 27        | 0.64%   |
| Samsung SSD 860 EVO 500GB       | 26        | 0.62%   |
| Hoodisk SSD 128GB               | 26        | 0.62%   |
| Kingston SUV500MS240G 240GB     | 25        | 0.59%   |
| Kingston SA400S37120G 120GB     | 24        | 0.57%   |
| Seagate ST500DM002-1BD142 500GB | 23        | 0.55%   |
| Samsung SSD 860 EVO 1TB         | 23        | 0.55%   |
| Samsung SSD 860 EVO 250GB       | 22        | 0.52%   |
| Kingston SUV500MS120G 120GB     | 22        | 0.52%   |
| Crucial CT500MX500SSD1 500GB    | 22        | 0.52%   |
| PNY CS900 120GB SSD             | 21        | 0.5%    |
| Samsung SSD 850 EVO 500GB       | 20        | 0.48%   |
| BIWIN SSD 128GB                 | 20        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB    | 19        | 0.45%   |
| Protectli 120GB mSATA           | 19        | 0.45%   |
| Samsung SSD 870 EVO 500GB       | 18        | 0.43%   |
| Kingston SV300S37A120G 120GB    | 18        | 0.43%   |
| Hoodisk SSD 64GB                | 16        | 0.38%   |
| Crucial CT250MX500SSD1 250GB    | 16        | 0.38%   |
| WDC WD800JD-75MSA3 80GB         | 15        | 0.36%   |
| SanDisk SSD PLUS 240GB          | 15        | 0.36%   |
| FORESEE 128GB SSD               | 15        | 0.36%   |
| Crucial CT1000MX500SSD1 1TB     | 15        | 0.36%   |
| SPCC Solid State Disk 128GB     | 14        | 0.33%   |
| Samsung SSD 860 EVO M.2 250GB   | 14        | 0.33%   |
| Phison Sabrent 1TB              | 14        | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB        | 13        | 0.31%   |
| Transcend TS256GMTS952T2 256GB  | 13        | 0.31%   |
| SanDisk SDSSDA120G 120GB        | 13        | 0.31%   |
| Phison PCIe SSD 512GB           | 13        | 0.31%   |
| Dogfish SSD 128GB               | 13        | 0.31%   |
| China SATA SSD 120GB            | 13        | 0.31%   |
| Transcend TS128GMSA230S 128GB   | 12        | 0.29%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 12        | 0.29%   |
| Samsung SSD 980 500GB           | 12        | 0.29%   |
| Samsung SSD 970 EVO Plus 2TB    | 12        | 0.29%   |
| Protectli 64GB mSATA            | 12        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 332       | 1155   | 34.12%  |
| Seagate                            | 310       | 835    | 31.86%  |
| Toshiba                            | 104       | 195    | 10.69%  |
| Hitachi                            | 73        | 170    | 7.5%    |
| HGST                               | 44        | 126    | 4.52%   |
| Hewlett-Packard                    | 25        | 82     | 2.57%   |
| NVMe                               | 20        | 27     | 2.06%   |
| Samsung Electronics                | 13        | 19     | 1.34%   |
| Apple                              | 11        | 12     | 1.13%   |
| Fujitsu                            | 7         | 8      | 0.72%   |
| Maxtor                             | 5         | 9      | 0.51%   |
| Lexar                              | 3         | 3      | 0.31%   |
| China                              | 3         | 5      | 0.31%   |
| LSI                                | 2         | 8      | 0.21%   |
| HPE                                | 2         | 7      | 0.21%   |
| Adaptec                            | 2         | 2      | 0.21%   |
| WD MediaMax                        | 1         | 3      | 0.1%    |
| QUANTUM                            | 1         | 2      | 0.1%    |
| Product:              USB DISK 3.0 | 1         | 1      | 0.1%    |
| OPENBSD                            | 1         | 1      | 0.1%    |
| NETAPP                             | 1         | 2      | 0.1%    |
| Memorex                            | 1         | 1      | 0.1%    |
| MaxDigital                         | 1         | 1      | 0.1%    |
| MARVELL                            | 1         | 1      | 0.1%    |
| IBM/Hitachi                        | 1         | 1      | 0.1%    |
| IBM-ESXS                           | 1         | 1      | 0.1%    |
| IBM-207x                           | 1         | 1      | 0.1%    |
| HPT                                | 1         | 8      | 0.1%    |
| Generic                            | 1         | 1      | 0.1%    |
| General                            | 1         | 1      | 0.1%    |
| ExcelStor Technology               | 1         | 4      | 0.1%    |
| Dell                               | 1         | 3      | 0.1%    |
| ASMT                               | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 399       | 816    | 18.19%  |
| Kingston            | 223       | 311    | 10.16%  |
| SanDisk             | 162       | 213    | 7.38%   |
| Crucial             | 151       | 239    | 6.88%   |
| Intel               | 128       | 270    | 5.83%   |
| Transcend           | 123       | 230    | 5.61%   |
| Hoodisk             | 80        | 114    | 3.65%   |
| China               | 77        | 123    | 3.51%   |
| A-DATA Technology   | 68        | 100    | 3.1%    |
| Protectli           | 67        | 111    | 3.05%   |
| PNY                 | 62        | 96     | 2.83%   |
| WDC                 | 52        | 93     | 2.37%   |
| SK hynix            | 47        | 65     | 2.14%   |
| SPCC                | 44        | 89     | 2.01%   |
| Dogfish             | 34        | 60     | 1.55%   |
| Phison              | 28        | 38     | 1.28%   |
| BIWIN               | 28        | 46     | 1.28%   |
| Micron Technology   | 27        | 37     | 1.23%   |
| OCZ                 | 25        | 38     | 1.14%   |
| FORESEE             | 25        | 41     | 1.14%   |
| KingSpec            | 17        | 21     | 0.77%   |
| Apacer              | 17        | 24     | 0.77%   |
| Team                | 16        | 39     | 0.73%   |
| Toshiba             | 13        | 19     | 0.59%   |
| Seagate             | 13        | 29     | 0.59%   |
| Corsair             | 13        | 18     | 0.59%   |
| Mushkin             | 12        | 18     | 0.55%   |
| Lexar               | 12        | 19     | 0.55%   |
| Apple               | 12        | 15     | 0.55%   |
| Patriot             | 11        | 14     | 0.5%    |
| OWC                 | 11        | 17     | 0.5%    |
| Zheino              | 10        | 18     | 0.46%   |
| Supermicro          | 10        | 10     | 0.46%   |
| LITEON              | 10        | 16     | 0.46%   |
| Innodisk            | 10        | 12     | 0.46%   |
| NVMe                | 9         | 11     | 0.41%   |
| LITEONIT            | 9         | 12     | 0.41%   |
| Hewlett-Packard     | 9         | 14     | 0.41%   |
| Plextor             | 7         | 12     | 0.32%   |
| CWDISK              | 7         | 8      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1974      | 3650   | 56.9%   |
| HDD  | 811       | 2696   | 23.38%  |
| NVMe | 684       | 1157   | 19.72%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2537      | 6346   | 78.76%  |
| NVMe | 684       | 1157   | 21.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2119      | 3822   | 72.64%  |
| 0.51-1.0   | 446       | 895    | 15.29%  |
| 1.01-2.0   | 151       | 432    | 5.18%   |
| 4.01-10.0  | 74        | 596    | 2.54%   |
| 3.01-4.0   | 54        | 240    | 1.85%   |
| 2.01-3.0   | 50        | 198    | 1.71%   |
| 10.01-20.0 | 22        | 159    | 0.75%   |
| 20.01-50.0 | 1         | 4      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1384      | 39.69%  |
| 251-500        | 673       | 19.3%   |
| 1-20           | 334       | 9.58%   |
| 51-100         | 331       | 9.49%   |
| 501-1000       | 329       | 9.44%   |
| 21-50          | 300       | 8.6%    |
| 1001-2000      | 82        | 2.35%   |
| More than 3000 | 31        | 0.89%   |
| Unknown        | 14        | 0.4%    |
| 2001-3000      | 9         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3122      | 89.82%  |
| 21-50          | 197       | 5.67%   |
| 51-100         | 70        | 2.01%   |
| 101-250        | 38        | 1.09%   |
| 251-500        | 15        | 0.43%   |
| Unknown        | 14        | 0.4%    |
| More than 3000 | 7         | 0.2%    |
| 501-1000       | 7         | 0.2%    |
| 1001-2000      | 3         | 0.09%   |
| 2001-3000      | 2         | 0.06%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8         | 12     | 1.82%   |
| Kingston SV300S37A120G 120GB          | 6         | 7      | 1.36%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.14%   |
| Crucial CT275MX300SSD1 275GB          | 5         | 8      | 1.14%   |
| Apacer 16GB SATA Flash Drive          | 5         | 9      | 1.14%   |
| Seagate ST3500418AS 500GB             | 4         | 11     | 0.91%   |
| SanDisk SSD PLUS 240GB                | 4         | 5      | 0.91%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 0.91%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 0.91%   |
| WDC WD5003ABYX-18WERA0 500GB          | 3         | 6      | 0.68%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 4      | 0.68%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 15     | 0.68%   |
| WDC WD20EARS-00MVWB0 2TB              | 3         | 3      | 0.68%   |
| SK hynix SC210 mSATA 256GB            | 3         | 4      | 0.68%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 4      | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.68%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 7      | 0.68%   |
| Kingston SNS4151S316GD 16GB           | 3         | 5      | 0.68%   |
| Intel SSDSA2M080G2GC 80GB             | 3         | 3      | 0.68%   |
| China CF 2GB                          | 3         | 5      | 0.68%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB           | 2         | 4      | 0.45%   |
| WDC WD2001FASS-00W2B0 2TB             | 2         | 3      | 0.45%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.45%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2         | 2      | 0.45%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.45%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.45%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.45%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.45%   |
| SPCC Solid State Disk 512GB           | 2         | 3      | 0.45%   |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.45%   |
| Seagate ST95005620AS 500GB            | 2         | 2      | 0.45%   |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.45%   |
| Seagate ST5000DM000-1FK178 5TB        | 2         | 3      | 0.45%   |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.45%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.45%   |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.45%   |
| Samsung Electronics SSD 950 PRO 256GB | 2         | 2      | 0.45%   |
| Samsung Electronics SSD 870 EVO 250GB | 2         | 4      | 0.45%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 150    | 20.42%  |
| WDC                 | 67        | 125    | 15.73%  |
| Kingston            | 34        | 41     | 7.98%   |
| Intel               | 34        | 45     | 7.98%   |
| Samsung Electronics | 29        | 43     | 6.81%   |
| Hitachi             | 24        | 32     | 5.63%   |
| Toshiba             | 22        | 31     | 5.16%   |
| Crucial             | 22        | 31     | 5.16%   |
| SanDisk             | 14        | 17     | 3.29%   |
| HGST                | 11        | 11     | 2.58%   |
| SK hynix            | 10        | 14     | 2.35%   |
| Apacer              | 8         | 12     | 1.88%   |
| HP Phison           | 5         | 5      | 1.17%   |
| OCZ                 | 4         | 4      | 0.94%   |
| Micron Technology   | 4         | 5      | 0.94%   |
| China               | 4         | 6      | 0.94%   |
| SPCC                | 3         | 6      | 0.7%    |
| Phison              | 3         | 3      | 0.7%    |
| Maxtor              | 3         | 6      | 0.7%    |
| LITEON              | 3         | 4      | 0.7%    |
| Apple               | 3         | 3      | 0.7%    |
| SSSTC               | 2         | 2      | 0.47%   |
| PNY                 | 2         | 2      | 0.47%   |
| Plextor             | 2         | 2      | 0.47%   |
| Patriot             | 2         | 2      | 0.47%   |
| MyDigitalSSD        | 2         | 4      | 0.47%   |
| Corsair             | 2         | 2      | 0.47%   |
| A-DATA Technology   | 2         | 2      | 0.47%   |
| ZTC                 | 1         | 3      | 0.23%   |
| Wintec              | 1         | 1      | 0.23%   |
| WD MediaMax         | 1         | 3      | 0.23%   |
| VisionTek           | 1         | 1      | 0.23%   |
| Transcend           | 1         | 4      | 0.23%   |
| LITEONIT            | 1         | 3      | 0.23%   |
| KingSpec            | 1         | 1      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| KeepData            | 1         | 1      | 0.23%   |
| INDMEM              | 1         | 1      | 0.23%   |
| IBM/Hitachi         | 1         | 1      | 0.23%   |
| HPE                 | 1         | 3      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 87        | 150    | 38.33%  |
| WDC                  | 66        | 124    | 29.07%  |
| Hitachi              | 24        | 32     | 10.57%  |
| Toshiba              | 20        | 29     | 8.81%   |
| HGST                 | 11        | 11     | 4.85%   |
| Samsung Electronics  | 5         | 6      | 2.2%    |
| Maxtor               | 3         | 6      | 1.32%   |
| China                | 3         | 5      | 1.32%   |
| Apple                | 2         | 2      | 0.88%   |
| WD MediaMax          | 1         | 3      | 0.44%   |
| IBM/Hitachi          | 1         | 1      | 0.44%   |
| HPE                  | 1         | 3      | 0.44%   |
| Hewlett-Packard      | 1         | 4      | 0.44%   |
| Fujitsu              | 1         | 1      | 0.44%   |
| ExcelStor Technology | 1         | 2      | 0.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 217       | 379    | 52.29%  |
| SSD  | 191       | 261    | 46.02%  |
| NVMe | 7         | 7      | 1.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 16.67%  |
| WDC WD3200L 320GB                            | 1         | 1      | 8.33%   |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 8.33%   |
| SanDisk pSSD 16GB                            | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 8.33%   |
| Samsung Electronics PM981 NVMe 256GB         | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLB256HBHQ-000H1 256GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 8.33%   |
| Kingston SA2000M8500G 500GB                  | 1         | 2      | 8.33%   |
| Intel SSDSC2KB019T8 1.9TB                    | 1         | 2      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 50%     |
| WDC                 | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Seagate             | 1         | 2      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Kingston            | 1         | 2      | 8.33%   |
| Intel               | 1         | 2      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2724      | 6665   | 84.23%  |
| Malfunc  | 407       | 647    | 12.59%  |
| Detected | 91        | 175    | 2.81%   |
| Failed   | 12        | 16     | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2594      | 60.88%  |
| AMD                                     | 505       | 11.85%  |
| Samsung Electronics                     | 263       | 6.17%   |
| Broadcom / LSI                          | 143       | 3.36%   |
| SanDisk                                 | 125       | 2.93%   |
| Phison Electronics                      | 70        | 1.64%   |
| ASMedia Technology                      | 65        | 1.53%   |
| Silicon Motion                          | 63        | 1.48%   |
| SK hynix                                | 47        | 1.1%    |
| Marvell Technology Group                | 39        | 0.92%   |
| Micron/Crucial Technology               | 36        | 0.84%   |
| MAXIO Technology (Hangzhou)             | 32        | 0.75%   |
| Kingston Technology Company             | 31        | 0.73%   |
| Chelsio Communications                  | 27        | 0.63%   |
| Toshiba                                 | 20        | 0.47%   |
| KIOXIA                                  | 20        | 0.47%   |
| Micron Technology                       | 19        | 0.45%   |
| Hewlett-Packard                         | 19        | 0.45%   |
| Realtek Semiconductor                   | 18        | 0.42%   |
| JMicron Technology                      | 18        | 0.42%   |
| Nvidia                                  | 15        | 0.35%   |
| Adaptec                                 | 11        | 0.26%   |
| Transcend                               | 8         | 0.19%   |
| ADATA Technology                        | 8         | 0.19%   |
| Shenzhen Longsys Electronics            | 7         | 0.16%   |
| Silicon Image                           | 6         | 0.14%   |
| Seagate Technology                      | 6         | 0.14%   |
| Lite-On Technology                      | 5         | 0.12%   |
| Hosin Global Electronics                | 5         | 0.12%   |
| VIA Technologies                        | 3         | 0.07%   |
| Union Memory (Shenzhen)                 | 3         | 0.07%   |
| Solid State Storage Technology          | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.07%   |
| Shenzhen Unionmemory Information System | 3         | 0.07%   |
| Biwin Storage Technology                | 3         | 0.07%   |
| Netac Technology                        | 2         | 0.05%   |
| Lenovo                                  | 2         | 0.05%   |
| HighPoint Technologies                  | 2         | 0.05%   |
| Dell                                    | 2         | 0.05%   |
| Broadcom                                | 2         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 349       | 7.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 265       | 5.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 178       | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 159       | 3.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 142       | 2.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 139       | 2.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 135       | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 135       | 2.8%    |
| Intel SATA Controller [RAID mode]                                                | 105       | 2.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 101       | 2.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 94        | 1.95%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 93        | 1.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 72        | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 70        | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 66        | 1.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 65        | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 61        | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 57        | 1.18%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 56        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 50        | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                           | 50        | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 49        | 1.02%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 47        | 0.98%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 44        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 44        | 0.91%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 43        | 0.89%   |
| AMD FCH IDE Controller                                                           | 43        | 0.89%   |
| AMD 500 Series Chipset SATA Controller                                           | 42        | 0.87%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 41        | 0.85%   |
| Intel unknown                                                                    | 40        | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 40        | 0.83%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 40        | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 38        | 0.79%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 38        | 0.79%   |
| Phison E12 NVMe Controller                                                       | 34        | 0.71%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 33        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 33        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 33        | 0.69%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 32        | 0.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 32        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2757      | 64.37%  |
| NVMe | 793       | 18.52%  |
| IDE  | 358       | 8.36%   |
| RAID | 243       | 5.67%   |
| SAS  | 83        | 1.94%   |
| SCSI | 49        | 1.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2761      | 82.42%  |
| AMD      | 552       | 16.48%  |
| ARM      | 22        | 0.66%   |
| Unknown  | 8         | 0.24%   |
| IBM      | 3         | 0.09%   |
| NXP      | 1         | 0.03%   |
| Motorola | 1         | 0.03%   |
| i        | 1         | 0.03%   |
| Broadcom | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 92        | 2.71%   |
| Intel Celeron N5105 @ 2.00GHz            | 84        | 2.47%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 80        | 2.35%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 54        | 1.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 47        | 1.38%   |
| Intel N100                               | 46        | 1.35%   |
| AMD GX-412TC SOC                         | 40        | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 37        | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 37        | 1.09%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 34        | 1%      |
| Intel Core i5-3470 CPU @ 3.20GHz         | 31        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 29        | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 27        | 0.79%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 27        | 0.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 26        | 0.76%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 24        | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 23        | 0.68%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 22        | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 20        | 0.59%   |
| Intel Atom CPU D525 @ 1.80GHz            | 20        | 0.59%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 19        | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 19        | 0.56%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 19        | 0.56%   |
| Intel Pentium CPU J3710 @ 1.60GHz        | 18        | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 18        | 0.53%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 18        | 0.53%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 17        | 0.5%    |
| Intel Core i5-7500 CPU @ 3.40GHz         | 17        | 0.5%    |
| Intel Celeron J4105 CPU @ 1.50GHz        | 17        | 0.5%    |
| Intel Celeron CPU J3060 @ 1.60GHz        | 17        | 0.5%    |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 16        | 0.47%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 16        | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 16        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 16        | 0.47%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 16        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 16        | 0.47%   |
| Intel Celeron J6412 @ 2.00GHz            | 16        | 0.47%   |
| Intel Core 2 Duo                         | 15        | 0.44%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 15        | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 14        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 659       | 19.51%  |
| Intel Celeron           | 532       | 15.75%  |
| Intel Xeon              | 444       | 13.14%  |
| Intel Core i7           | 376       | 11.13%  |
| Other                   | 211       | 6.25%   |
| Intel Core i3           | 203       | 6.01%   |
| Intel Atom              | 160       | 4.74%   |
| AMD Ryzen 7             | 95        | 2.81%   |
| Intel Pentium           | 85        | 2.52%   |
| AMD GX                  | 84        | 2.49%   |
| AMD Ryzen 5             | 69        | 2.04%   |
| Intel Core 2 Duo        | 53        | 1.57%   |
| Intel Pentium Silver    | 35        | 1.04%   |
| AMD Ryzen 9             | 32        | 0.95%   |
| AMD EPYC                | 25        | 0.74%   |
| AMD Ryzen 3             | 23        | 0.68%   |
| AMD FX                  | 23        | 0.68%   |
| ARM Cortex              | 21        | 0.62%   |
| AMD A10                 | 19        | 0.56%   |
| Intel Core i9           | 14        | 0.41%   |
| Intel Core 2 Quad       | 14        | 0.41%   |
| AMD Ryzen 5 PRO         | 13        | 0.38%   |
| AMD Athlon              | 11        | 0.33%   |
| Intel Core 2            | 10        | 0.3%    |
| AMD Phenom II X4        | 10        | 0.3%    |
| AMD G                   | 10        | 0.3%    |
| AMD Ryzen Embedded      | 9         | 0.27%   |
| AMD A8                  | 9         | 0.27%   |
| AMD A6                  | 9         | 0.27%   |
| Intel Genuine           | 8         | 0.24%   |
| Intel Pentium Dual-Core | 7         | 0.21%   |
| Intel Pentium 4         | 7         | 0.21%   |
| AMD Opteron             | 7         | 0.21%   |
| AMD Ryzen Threadripper  | 6         | 0.18%   |
| AMD A4                  | 6         | 0.18%   |
| Intel Xeon Gold         | 5         | 0.15%   |
| AMD Phenom II X6        | 5         | 0.15%   |
| Intel Pentium M         | 4         | 0.12%   |
| Intel Pentium Gold      | 4         | 0.12%   |
| AMD Ryzen 7 PRO         | 4         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1773      | 52.42%  |
| 2       | 772       | 22.83%  |
| 8       | 219       | 6.48%   |
| 6       | 174       | 5.14%   |
| 16      | 119       | 3.52%   |
| Unknown | 112       | 3.31%   |
| 12      | 110       | 3.25%   |
| 1       | 26        | 0.77%   |
| 24      | 20        | 0.59%   |
| 32      | 19        | 0.56%   |
| 10      | 11        | 0.33%   |
| 20      | 9         | 0.27%   |
| 14      | 5         | 0.15%   |
| 48      | 3         | 0.09%   |
| 36      | 3         | 0.09%   |
| 64      | 2         | 0.06%   |
| 28      | 2         | 0.06%   |
| 3       | 2         | 0.06%   |
| 40      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3168      | 94.57%  |
| 2       | 131       | 3.91%   |
| Unknown | 49        | 1.46%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1910      | 56.74%  |
| 2       | 1330      | 39.51%  |
| Unknown | 125       | 3.71%   |
| 4       | 1         | 0.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 434       | 12.83%  |
| Haswell         | 371       | 10.97%  |
| Unknown         | 309       | 9.14%   |
| Silvermont      | 299       | 8.84%   |
| IvyBridge       | 234       | 6.92%   |
| Skylake         | 224       | 6.62%   |
| SandyBridge     | 199       | 5.88%   |
| Goldmont plus   | 147       | 4.35%   |
| Broadwell       | 127       | 3.76%   |
| Goldmont        | 90        | 2.66%   |
| Westmere        | 77        | 2.28%   |
| Zen 2           | 70        | 2.07%   |
| Zen 3           | 68        | 2.01%   |
| Zen+            | 66        | 1.95%   |
| Zen             | 65        | 1.92%   |
| Penryn          | 64        | 1.89%   |
| CometLake       | 54        | 1.6%    |
| Puma            | 51        | 1.51%   |
| Nehalem         | 50        | 1.48%   |
| Jaguar          | 49        | 1.45%   |
| Bonnell         | 49        | 1.45%   |
| Core            | 48        | 1.42%   |
| Steamroller     | 44        | 1.3%    |
| Piledriver      | 41        | 1.21%   |
| TigerLake       | 34        | 1.01%   |
| K10             | 27        | 0.8%    |
| Bobcat          | 22        | 0.65%   |
| Excavator       | 21        | 0.62%   |
| NetBurst        | 17        | 0.5%    |
| K8 Hammer       | 11        | 0.33%   |
| P6              | 6         | 0.18%   |
| IceLake         | 6         | 0.18%   |
| K10 Llano       | 4         | 0.12%   |
| Bulldozer       | 2         | 0.06%   |
| K8 & K10 hybrid | 1         | 0.03%   |
| Geode           | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2071      | 61.82%  |
| AMD                                          | 509       | 15.19%  |
| Nvidia                                       | 320       | 9.55%   |
| ASPEED Technology                            | 224       | 6.69%   |
| Matrox Electronics Systems                   | 219       | 6.54%   |
| XGI Technology (eXtreme Graphics Innovation) | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 224       | 6.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 162       | 4.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 147       | 4.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 129       | 3.78%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 127       | 3.72%   |
| Intel HD Graphics 530                                                                    | 124       | 3.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 121       | 3.54%   |
| Intel JasperLake [UHD Graphics]                                                          | 108       | 3.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 95        | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 94        | 2.75%   |
| Intel HD Graphics 620                                                                    | 85        | 2.49%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 67        | 1.96%   |
| Intel UHD Graphics 620                                                                   | 63        | 1.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 60        | 1.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 1.73%   |
| Matrox Electronics Systems G200eR2                                                       | 56        | 1.64%   |
| Intel HD Graphics 630                                                                    | 56        | 1.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 1.58%   |
| Intel HD Graphics 500                                                                    | 51        | 1.49%   |
| Intel HD Graphics 5500                                                                   | 46        | 1.35%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 42        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 33        | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 32        | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 31        | 0.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 30        | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 29        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 28        | 0.82%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 27        | 0.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 0.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 26        | 0.76%   |
| Intel HD Graphics 610                                                                    | 23        | 0.67%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 23        | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 0.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 22        | 0.64%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 22        | 0.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 0.59%   |
| AMD ES1000                                                                               | 19        | 0.56%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 18        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1895      | 56.08%  |
| 1 x AMD         | 457       | 13.52%  |
| 1 x Nvidia      | 227       | 6.72%   |
| 1 x Matrox      | 217       | 6.42%   |
| 1 x ASPEED      | 209       | 6.19%   |
| Other           | 152       | 4.5%    |
| Intel + Nvidia  | 75        | 2.22%   |
| 2 x Intel       | 71        | 2.1%    |
| Intel + AMD     | 23        | 0.68%   |
| 2 x AMD         | 13        | 0.38%   |
| AMD + Nvidia    | 12        | 0.36%   |
| Intel + ASPEED  | 9         | 0.27%   |
| Nvidia + ASPEED | 5         | 0.15%   |
| 1 x XGI         | 4         | 0.12%   |
| 2 x Nvidia      | 3         | 0.09%   |
| 1 x SiS         | 3         | 0.09%   |
| AMD + ASPEED    | 2         | 0.06%   |
| Intel + 2 x AMD | 1         | 0.03%   |
| AMD + Matrox    | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3014      | 89.54%  |
| Unknown     | 188       | 5.59%   |
| Proprietary | 164       | 4.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3098      | 91.71%  |
| 1.01-2.0   | 66        | 1.95%   |
| 0.01-0.5   | 59        | 1.75%   |
| 3.01-4.0   | 47        | 1.39%   |
| 7.01-8.0   | 35        | 1.04%   |
| 0.51-1.0   | 34        | 1.01%   |
| 5.01-6.0   | 21        | 0.62%   |
| 8.01-16.0  | 12        | 0.36%   |
| 2.01-3.0   | 4         | 0.12%   |
| 4.01-5.0   | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 77        | 10.5%   |
| AU Optronics            | 76        | 10.37%  |
| LG Display              | 71        | 9.69%   |
| Dell                    | 71        | 9.69%   |
| BOE                     | 58        | 7.91%   |
| Chimei Innolux          | 47        | 6.41%   |
| Goldstar                | 38        | 5.18%   |
| Acer                    | 37        | 5.05%   |
| Lenovo                  | 33        | 4.5%    |
| Hewlett-Packard         | 29        | 3.96%   |
| Ancor Communications    | 24        | 3.27%   |
| Apple                   | 23        | 3.14%   |
| AOC                     | 12        | 1.64%   |
| ASUSTek Computer        | 11        | 1.5%    |
| Vizio                   | 10        | 1.36%   |
| Sharp                   | 10        | 1.36%   |
| ViewSonic               | 9         | 1.23%   |
| Sceptre Tech            | 8         | 1.09%   |
| Chi Mei Optoelectronics | 8         | 1.09%   |
| BenQ                    | 8         | 1.09%   |
| LG Electronics          | 7         | 0.95%   |
| InfoVision              | 5         | 0.68%   |
| Sony                    | 4         | 0.55%   |
| Philips                 | 3         | 0.41%   |
| NEC Computers           | 3         | 0.41%   |
| MSI                     | 3         | 0.41%   |
| LGD                     | 3         | 0.41%   |
| Lenovo Group Limited    | 3         | 0.41%   |
| Insignia                | 3         | 0.41%   |
| HannStar                | 3         | 0.41%   |
| Westinghouse            | 2         | 0.27%   |
| LG Philips              | 2         | 0.27%   |
| IBM                     | 2         | 0.27%   |
| Gigabyte Technology     | 2         | 0.27%   |
| Unknown                 | 2         | 0.27%   |
| Wacom                   | 1         | 0.14%   |
| unknown                 | 1         | 0.14%   |
| Toshiba                 | 1         | 0.14%   |
| Tech Concepts           | 1         | 0.14%   |
| SHI                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 7         | 0.92%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 7         | 0.92%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 5         | 0.66%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 5         | 0.66%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 4         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 4         | 0.53%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 4         | 0.53%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 4         | 0.53%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch   | 3         | 0.39%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 3         | 0.39%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 3         | 0.39%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 3         | 0.39%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 3         | 0.39%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.39%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3         | 0.39%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 3         | 0.39%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                 | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 3         | 0.39%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                  | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 3         | 0.39%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3         | 0.39%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 3         | 0.39%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                     | 3         | 0.39%   |
| Sony TV SNY9C01 1360x768                                              | 2         | 0.26%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch        | 2         | 0.26%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 2         | 0.26%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 330x210mm 15.4-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 2         | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.26%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 2         | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 0.26%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 246       | 33.98%  |
| 1366x768 (WXGA)    | 143       | 19.75%  |
| 3840x2160 (4K)     | 47        | 6.49%   |
| 2560x1440 (QHD)    | 46        | 6.35%   |
| 1600x900 (HD+)     | 37        | 5.11%   |
| 1920x1200 (WUXGA)  | 29        | 4.01%   |
| 1280x800 (WXGA)    | 24        | 3.31%   |
| 1280x1024 (SXGA)   | 21        | 2.9%    |
| 1680x1050 (WSXGA+) | 19        | 2.62%   |
| 2560x1080          | 15        | 2.07%   |
| 1440x900 (WXGA+)   | 15        | 2.07%   |
| 3440x1440          | 12        | 1.66%   |
| Unknown            | 10        | 1.38%   |
| 1360x768           | 8         | 1.1%    |
| 2256x1504          | 7         | 0.97%   |
| 1024x768 (XGA)     | 7         | 0.97%   |
| 2560x1600          | 6         | 0.83%   |
| 1024x600           | 5         | 0.69%   |
| 3200x1800 (QHD+)   | 4         | 0.55%   |
| 1600x1200          | 4         | 0.55%   |
| 3840x1080          | 3         | 0.41%   |
| 3840x1600          | 2         | 0.28%   |
| 7860x2400          | 1         | 0.14%   |
| 7040x1440          | 1         | 0.14%   |
| 5760x2160          | 1         | 0.14%   |
| 5760x1080          | 1         | 0.14%   |
| 5120x1440          | 1         | 0.14%   |
| 4640x1080          | 1         | 0.14%   |
| 4480x1080          | 1         | 0.14%   |
| 3520x1080          | 1         | 0.14%   |
| 2806x900           | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1920x1920          | 1         | 0.14%   |
| 1400x1050          | 1         | 0.14%   |
| 1280x854           | 1         | 0.14%   |
| 1280x768           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 143       | 19.56%  |
| 13      | 126       | 17.24%  |
| 24      | 66        | 9.03%   |
| 27      | 57        | 7.8%    |
| Unknown | 46        | 6.29%   |
| 31      | 30        | 4.1%    |
| 17      | 29        | 3.97%   |
| 12      | 29        | 3.97%   |
| 19      | 28        | 3.83%   |
| 11      | 27        | 3.69%   |
| 23      | 26        | 3.56%   |
| 21      | 24        | 3.28%   |
| 14      | 20        | 2.74%   |
| 34      | 17        | 2.33%   |
| 22      | 10        | 1.37%   |
| 20      | 8         | 1.09%   |
| 29      | 7         | 0.96%   |
| 18      | 6         | 0.82%   |
| 64      | 4         | 0.55%   |
| 26      | 4         | 0.55%   |
| 43      | 2         | 0.27%   |
| 42      | 2         | 0.27%   |
| 37      | 2         | 0.27%   |
| 35      | 2         | 0.27%   |
| 28      | 2         | 0.27%   |
| 16      | 2         | 0.27%   |
| 10      | 2         | 0.27%   |
| 9       | 2         | 0.27%   |
| 54      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 49      | 1         | 0.14%   |
| 41      | 1         | 0.14%   |
| 39      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |
| 25      | 1         | 0.14%   |
| 8       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 239       | 33.33%  |
| 501-600     | 138       | 19.25%  |
| 201-300     | 119       | 16.6%   |
| 401-500     | 66        | 9.21%   |
| Unknown     | 46        | 6.42%   |
| 601-700     | 44        | 6.14%   |
| 351-400     | 27        | 3.77%   |
| 701-800     | 18        | 2.51%   |
| 1001-1500   | 7         | 0.98%   |
| 801-900     | 5         | 0.7%    |
| 901-1000    | 5         | 0.7%    |
| 101-200     | 3         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 484       | 70.55%  |
| 16/10   | 82        | 11.95%  |
| Unknown | 42        | 6.12%   |
| 21/9    | 27        | 3.94%   |
| 5/4     | 18        | 2.62%   |
| 3/2     | 15        | 2.19%   |
| 4/3     | 13        | 1.9%    |
| 6/5     | 3         | 0.44%   |
| 32/9    | 1         | 0.15%   |
| 1.00    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 121       | 16.62%  |
| 91-100         | 107       | 14.7%   |
| 201-250        | 101       | 13.87%  |
| 301-350        | 63        | 8.65%   |
| 351-500        | 53        | 7.28%   |
| Unknown        | 46        | 6.32%   |
| 101-110        | 37        | 5.08%   |
| 151-200        | 36        | 4.95%   |
| 61-70          | 30        | 4.12%   |
| 51-60          | 26        | 3.57%   |
| 251-300        | 26        | 3.57%   |
| 71-80          | 18        | 2.47%   |
| 121-130        | 18        | 2.47%   |
| 141-150        | 17        | 2.34%   |
| 501-1000       | 9         | 1.24%   |
| More than 1000 | 6         | 0.82%   |
| 111-120        | 6         | 0.82%   |
| 1-40           | 3         | 0.41%   |
| 131-140        | 3         | 0.41%   |
| 41-50          | 2         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 226       | 31.83%  |
| 121-160       | 195       | 27.46%  |
| 101-120       | 175       | 24.65%  |
| 161-240       | 48        | 6.76%   |
| Unknown       | 46        | 6.48%   |
| More than 240 | 16        | 2.25%   |
| 1-50          | 4         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2615      | 77.57%  |
| 1     | 674       | 19.99%  |
| 2     | 73        | 2.17%   |
| 3     | 7         | 0.21%   |
| 4     | 2         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2719      | 58.51%  |
| Realtek Semiconductor           | 968       | 20.83%  |
| Broadcom                        | 330       | 7.1%    |
| Qualcomm Atheros                | 202       | 4.35%   |
| Mellanox Technologies           | 58        | 1.25%   |
| Ralink Technology               | 37        | 0.8%    |
| Chelsio Communications          | 30        | 0.65%   |
| IMC Networks                    | 25        | 0.54%   |
| AMD                             | 20        | 0.43%   |
| U-Blox                          | 18        | 0.39%   |
| Marvell Technology Group        | 17        | 0.37%   |
| TP-Link                         | 16        | 0.34%   |
| Ralink                          | 16        | 0.34%   |
| Edimax Technology               | 14        | 0.3%    |
| MediaTek                        | 13        | 0.28%   |
| Solarflare Communications       | 12        | 0.26%   |
| Aquantia                        | 12        | 0.26%   |
| Google                          | 10        | 0.22%   |
| D-Link System                   | 8         | 0.17%   |
| Nvidia                          | 7         | 0.15%   |
| Novatel Wireless                | 7         | 0.15%   |
| NetGear                         | 7         | 0.15%   |
| Dell                            | 7         | 0.15%   |
| Seeed Technology                | 6         | 0.13%   |
| Emulex                          | 6         | 0.13%   |
| ASUSTek Computer                | 6         | 0.13%   |
| Apple                           | 6         | 0.13%   |
| American Megatrends             | 6         | 0.13%   |
| QLogic                          | 5         | 0.11%   |
| Sierra Wireless                 | 3         | 0.06%   |
| Sequans Communications          | 3         | 0.06%   |
| Qualcomm                        | 3         | 0.06%   |
| Insyde Software                 | 3         | 0.06%   |
| Cisco Systems                   | 3         | 0.06%   |
| VIA Technologies                | 2         | 0.04%   |
| Qualcomm Atheros Communications | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)   | 2         | 0.04%   |
| Linksys                         | 2         | 0.04%   |
| ICS Advent                      | 2         | 0.04%   |
| D-Link                          | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 759       | 12.61%  |
| Intel I211 Gigabit Network Connection                                         | 363       | 6.03%   |
| Intel I210 Gigabit Network Connection                                         | 273       | 4.54%   |
| Intel I350 Gigabit Network Connection                                         | 242       | 4.02%   |
| Intel Ethernet Controller I225-V                                              | 212       | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 190       | 3.16%   |
| Intel 82574L Gigabit Network Connection                                       | 156       | 2.59%   |
| Intel Ethernet Controller I226-V                                              | 151       | 2.51%   |
| Intel Ethernet Connection I217-LM                                             | 133       | 2.21%   |
| Intel 82580 Gigabit Network Connection                                        | 100       | 1.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 97        | 1.61%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 95        | 1.58%   |
| Intel 82583V Gigabit Network Connection                                       | 93        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                             | 91        | 1.51%   |
| Intel 82576 Gigabit Network Connection                                        | 90        | 1.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 84        | 1.4%    |
| Intel Wi-Fi 6 AX200                                                           | 83        | 1.38%   |
| Intel Ethernet Connection (2) I219-LM                                         | 74        | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 63        | 1.05%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 63        | 1.05%   |
| Intel Wireless 8265 / 8275                                                    | 59        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 54        | 0.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 48        | 0.8%    |
| Intel Wireless 7260                                                           | 46        | 0.76%   |
| Intel Wireless 8260                                                           | 45        | 0.75%   |
| Intel Wireless 7265                                                           | 45        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 45        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                          | 42        | 0.7%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 42        | 0.7%    |
| Intel Ethernet Controller X550                                                | 41        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                         | 39        | 0.65%   |
| Intel Ethernet Connection I354                                                | 38        | 0.63%   |
| Intel Wireless 3165                                                           | 36        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                                          | 36        | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 35        | 0.58%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 33        | 0.55%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 27        | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 26        | 0.43%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 25        | 0.42%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 25        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 657       | 54.61%  |
| Qualcomm Atheros                | 170       | 14.13%  |
| Realtek Semiconductor           | 141       | 11.72%  |
| Broadcom                        | 85        | 7.07%   |
| Ralink Technology               | 37        | 3.08%   |
| IMC Networks                    | 25        | 2.08%   |
| TP-Link                         | 16        | 1.33%   |
| Ralink                          | 16        | 1.33%   |
| Edimax Technology               | 14        | 1.16%   |
| MediaTek                        | 13        | 1.08%   |
| NetGear                         | 7         | 0.58%   |
| ASUSTek Computer                | 6         | 0.5%    |
| Sierra Wireless                 | 2         | 0.17%   |
| Qualcomm Atheros Communications | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| D-Link                          | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Qualcomm Technologies           | 1         | 0.08%   |
| Marvell Technology Group        | 1         | 0.08%   |
| Linksys                         | 1         | 0.08%   |
| Dell                            | 1         | 0.08%   |
| AboCom Systems                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                             | 83        | 6.82%   |
| Intel Wireless 8265 / 8275                                      | 59        | 4.85%   |
| Intel Wireless 7260                                             | 46        | 3.78%   |
| Intel Wireless 8260                                             | 45        | 3.7%    |
| Intel Wireless 7265                                             | 45        | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 45        | 3.7%    |
| Intel Wireless 3165                                             | 36        | 2.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 35        | 2.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]       | 27        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 26        | 2.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 25        | 2.05%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card            | 25        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 23        | 1.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 23        | 1.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 23        | 1.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 19        | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 19        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 18        | 1.48%   |
| Ralink RT5370 Wireless Adapter                                  | 17        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 17        | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 17        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 16        | 1.31%   |
| Intel Wireless 3160                                             | 16        | 1.31%   |
| Intel CNVi: Wi-Fi                                               | 16        | 1.31%   |
| Broadcom BCM4331 802.11a/b/g/n                                  | 16        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 15        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 15        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 15        | 1.23%   |
| Intel Wi-Fi 6 AX201                                             | 14        | 1.15%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 14        | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 13        | 1.07%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 11        | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller          | 11        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 10        | 0.82%   |
| Intel Centrino Wireless-N 2230                                  | 10        | 0.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                 | 10        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 9         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 8         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 8         | 0.66%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 8         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2447      | 63.91%  |
| Realtek Semiconductor            | 902       | 23.56%  |
| Broadcom                         | 279       | 7.29%   |
| Qualcomm Atheros                 | 40        | 1.04%   |
| Chelsio Communications           | 27        | 0.71%   |
| AMD                              | 19        | 0.5%    |
| Marvell Technology Group         | 15        | 0.39%   |
| Solarflare Communications        | 12        | 0.31%   |
| Aquantia                         | 11        | 0.29%   |
| Nvidia                           | 7         | 0.18%   |
| Novatel Wireless                 | 7         | 0.18%   |
| Emulex                           | 6         | 0.16%   |
| D-Link System                    | 6         | 0.16%   |
| American Megatrends              | 6         | 0.16%   |
| QLogic                           | 5         | 0.13%   |
| Google                           | 4         | 0.1%    |
| Apple                            | 4         | 0.1%    |
| Qualcomm                         | 3         | 0.08%   |
| Insyde Software                  | 3         | 0.08%   |
| Cisco Systems                    | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| 3Com                             | 2         | 0.05%   |
| Xiaomi                           | 1         | 0.03%   |
| TRENDnet                         | 1         | 0.03%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Silicom                          | 1         | 0.03%   |
| Samsung Electronics              | 1         | 0.03%   |
| Oracle/SUN                       | 1         | 0.03%   |
| OPPO Electronics                 | 1         | 0.03%   |
| National Semiconductor           | 1         | 0.03%   |
| MYRICOM                          | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| Amazon.com                       | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 759       | 16.3%   |
| Intel I211 Gigabit Network Connection                                         | 363       | 7.79%   |
| Intel I210 Gigabit Network Connection                                         | 273       | 5.86%   |
| Intel I350 Gigabit Network Connection                                         | 242       | 5.2%    |
| Intel Ethernet Controller I225-V                                              | 212       | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 190       | 4.08%   |
| Intel 82574L Gigabit Network Connection                                       | 156       | 3.35%   |
| Intel Ethernet Controller I226-V                                              | 151       | 3.24%   |
| Intel Ethernet Connection I217-LM                                             | 133       | 2.86%   |
| Intel 82580 Gigabit Network Connection                                        | 100       | 2.15%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 97        | 2.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 95        | 2.04%   |
| Intel 82583V Gigabit Network Connection                                       | 93        | 2%      |
| Intel 82576 Gigabit Network Connection                                        | 90        | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                             | 88        | 1.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 84        | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                                         | 74        | 1.59%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 63        | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 63        | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 54        | 1.16%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 48        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                          | 42        | 0.9%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 42        | 0.9%    |
| Intel Ethernet Controller X550                                                | 41        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                         | 39        | 0.84%   |
| Intel Ethernet Connection I354                                                | 38        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                                          | 36        | 0.77%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 25        | 0.54%   |
| Intel Ethernet Connection X553 1GbE                                           | 25        | 0.54%   |
| Intel 82575EB Gigabit Network Connection                                      | 25        | 0.54%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 24        | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                         | 23        | 0.49%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 22        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                       | 21        | 0.45%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 21        | 0.45%   |
| Intel Ethernet Controller I225-LM                                             | 19        | 0.41%   |
| Intel Ethernet Connection (4) I219-LM                                         | 19        | 0.41%   |
| AMD XGMAC 10GbE Controller                                                    | 19        | 0.41%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 18        | 0.39%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 17        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3203      | 71.67%  |
| WiFi     | 1126      | 25.2%   |
| Unknown  | 103       | 2.3%    |
| Modem    | 37        | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2994      | 86.71%  |
| WiFi     | 450       | 13.03%  |
| Unknown  | 9         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 939       | 27.42%  |
| 4     | 716       | 20.91%  |
| 3     | 477       | 13.93%  |
| 1     | 407       | 11.88%  |
| 6     | 366       | 10.69%  |
| 5     | 254       | 7.42%   |
| 8     | 80        | 2.34%   |
| 7     | 65        | 1.9%    |
| 0     | 33        | 0.96%   |
| 10    | 31        | 0.91%   |
| 9     | 29        | 0.85%   |
| 11    | 7         | 0.2%    |
| 13    | 5         | 0.15%   |
| 14    | 4         | 0.12%   |
| 12    | 4         | 0.12%   |
| 16    | 3         | 0.09%   |
| 15    | 3         | 0.09%   |
| 20    | 1         | 0.03%   |
| 17    | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2759      | 78.9%   |
| Yes  | 738       | 21.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 502       | 62.52%  |
| Realtek Semiconductor           | 56        | 6.97%   |
| Broadcom                        | 55        | 6.85%   |
| Apple                           | 52        | 6.48%   |
| Qualcomm Atheros Communications | 31        | 3.86%   |
| IMC Networks                    | 30        | 3.74%   |
| Cambridge Silicon Radio         | 14        | 1.74%   |
| ASUSTek Computer                | 13        | 1.62%   |
| Lite-On Technology              | 10        | 1.25%   |
| MediaTek                        | 9         | 1.12%   |
| Foxconn / Hon Hai               | 9         | 1.12%   |
| Dell                            | 9         | 1.12%   |
| Alps Electric                   | 4         | 0.5%    |
| Ralink                          | 2         | 0.25%   |
| TP-Link                         | 1         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.12%   |
| Primax Electronics              | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Esel International              | 1         | 0.12%   |
| Dynex                           | 1         | 0.12%   |
| Corsair                         | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 206       | 25.53%  |
| Intel AX200 Bluetooth                                       | 76        | 9.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 67        | 8.3%    |
| Intel AX201 Bluetooth                                       | 60        | 7.43%   |
| Intel Wireless-AC 3168 Bluetooth                            | 27        | 3.35%   |
| Intel AX210 Bluetooth                                       | 23        | 2.85%   |
| Apple Bluetooth Host Controller                             | 23        | 2.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 22        | 2.73%   |
| Realtek  Bluetooth 4.2 Adapter                              | 20        | 2.48%   |
| Realtek Bluetooth Adapter                                   | 17        | 2.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 17        | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 14        | 1.73%   |
| IMC Networks Realtek Bluetooth Adapter                      | 12        | 1.49%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 12        | 1.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 12        | 1.49%   |
| Apple Broadcom Built-in Bluetooth                           | 12        | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 9         | 1.12%   |
| Realtek Bluetooth 4.2 Adapter                               | 8         | 0.99%   |
| MediaTek RZ608 Bluetooth Adapter                            | 8         | 0.99%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 8         | 0.99%   |
| Intel AX211 Bluetooth                                       | 7         | 0.87%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 0.87%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 0.74%   |
| Lite-On Bluetooth USB Module                                | 6         | 0.74%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 6         | 0.74%   |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 0.74%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.62%   |
| Dell DW375 Bluetooth Module                                 | 5         | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 0.5%    |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.37%   |
| Realtek Bluetooth 4.0 Adapter                               | 3         | 0.37%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.37%   |
| ASUS USB-BT500                                              | 3         | 0.37%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 3         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.25%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                 | 2         | 0.25%   |
| Ralink RT3290 Bluetooth                                     | 2         | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1991      | 67.93%  |
| AMD                                          | 550       | 18.76%  |
| Nvidia                                       | 249       | 8.5%    |
| C-Media Electronics                          | 42        | 1.43%   |
| Creative Labs                                | 14        | 0.48%   |
| Logitech                                     | 7         | 0.24%   |
| Texas Instruments                            | 6         | 0.2%    |
| SteelSeries ApS                              | 6         | 0.2%    |
| Realtek Semiconductor                        | 5         | 0.17%   |
| Blue Microphones                             | 5         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.1%    |
| MosArt Semiconductor                         | 3         | 0.1%    |
| Generalplus Technology                       | 3         | 0.1%    |
| Creative Technology                          | 3         | 0.1%    |
| Corsair                                      | 3         | 0.1%    |
| Yamaha                                       | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.07%   |
| Razer USA                                    | 2         | 0.07%   |
| Lenovo                                       | 2         | 0.07%   |
| Google                                       | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| Cambridge Silicon Radio                      | 2         | 0.07%   |
| ASUSTek Computer                             | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| XMOS                                         | 1         | 0.03%   |
| VIA Technologies                             | 1         | 0.03%   |
| Universal Audio                              | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Tenx Technology                              | 1         | 0.03%   |
| Quanta                                       | 1         | 0.03%   |
| Nektar                                       | 1         | 0.03%   |
| LG Electronics                               | 1         | 0.03%   |
| KTMicro                                      | 1         | 0.03%   |
| KORG                                         | 1         | 0.03%   |
| Kingston Technology                          | 1         | 0.03%   |
| JMTek                                        | 1         | 0.03%   |
| Hewlett-Packard                              | 1         | 0.03%   |
| Harman                                       | 1         | 0.03%   |
| Giga-Byte Technology                         | 1         | 0.03%   |
| Genesys Logic                                | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 188       | 5.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 170       | 4.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 153       | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 146       | 4.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 142       | 4%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 131       | 3.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 131       | 3.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 115       | 3.24%   |
| AMD FCH Azalia Controller                                                                         | 112       | 3.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 112       | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 110       | 3.1%    |
| Intel Jasper Lake HD Audio                                                                        | 108       | 3.04%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 74        | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 71        | 2%      |
| Intel 200 Series PCH HD Audio                                                                     | 71        | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 67        | 1.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 66        | 1.86%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 62        | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 60        | 1.69%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 60        | 1.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 58        | 1.63%   |
| Intel 8 Series HD Audio Controller                                                                | 55        | 1.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 55        | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 54        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 51        | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 46        | 1.3%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 41        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 37        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 34        | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 0.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 31        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 27        | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 0.68%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 23        | 0.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 0.59%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 0.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 0.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 21        | 0.59%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 676       | 18.73%  |
| SK hynix                                | 565       | 15.66%  |
| Crucial                                 | 394       | 10.92%  |
| Micron Technology                       | 380       | 10.53%  |
| Kingston                                | 292       | 8.09%   |
| Unknown                                 | 279       | 7.73%   |
| G.Skill                                 | 177       | 4.9%    |
| Corsair                                 | 141       | 3.91%   |
| Unknown                                 | 99        | 2.74%   |
| Team                                    | 73        | 2.02%   |
| Unknown (ABCD)                          | 49        | 1.36%   |
| Transcend                               | 47        | 1.3%    |
| Ramaxel Technology                      | 43        | 1.19%   |
| A-DATA Technology                       | 42        | 1.16%   |
| Nanya Technology                        | 38        | 1.05%   |
| Patriot                                 | 37        | 1.03%   |
| PNY                                     | 27        | 0.75%   |
| Kimtigo                                 | 27        | 0.75%   |
| Elpida                                  | 24        | 0.67%   |
| Timetec                                 | 18        | 0.5%    |
| Toshiba                                 | 13        | 0.36%   |
| Silicon Power                           | 13        | 0.36%   |
| Avant                                   | 12        | 0.33%   |
| Super Talent                            | 11        | 0.3%    |
| SK_Hynix                                | 8         | 0.22%   |
| Innodisk                                | 7         | 0.19%   |
| Silicon Power Computer & Communications | 6         | 0.17%   |
| Sesame                                  | 6         | 0.17%   |
| GeIL                                    | 5         | 0.14%   |
| Apacer                                  | 5         | 0.14%   |
| Wodposit                                | 4         | 0.11%   |
| Patriot Memory (PDP Systems)            | 4         | 0.11%   |
| HPE                                     | 4         | 0.11%   |
| tigo                                    | 3         | 0.08%   |
| Ramsta                                  | 3         | 0.08%   |
| Neo Forza                               | 3         | 0.08%   |
| Mushkin                                 | 3         | 0.08%   |
| Hewlett-Packard                         | 3         | 0.08%   |
| Goldkey                                 | 3         | 0.08%   |
| CSX                                     | 3         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 99        | 2.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 43        | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 25        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 23        | 0.6%    |
| Unknown RAM Module 8GB 1600MT/s                              | 21        | 0.55%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 21        | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 20        | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 20        | 0.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 20        | 0.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 19        | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 19        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 18        | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 17        | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 17        | 0.44%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 16        | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 15        | 0.39%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 15        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 14        | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 13        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 13        | 0.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 13        | 0.34%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 13        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 13        | 0.34%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s           | 12        | 0.31%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 12        | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 12        | 0.31%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 12        | 0.31%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 12        | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 11        | 0.29%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 11        | 0.29%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 11        | 0.29%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 11        | 0.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 11        | 0.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 10        | 0.26%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 10        | 0.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 10        | 0.26%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 10        | 0.26%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 10        | 0.26%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 10        | 0.26%   |
| Micron RAM 18KSF1G72AZ-1G6E1 8GB DIMM DDR3 1600MT/s          | 10        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1444      | 45.7%   |
| DDR4         | 1321      | 41.8%   |
| DDR2         | 108       | 3.42%   |
| LPDDR4       | 76        | 2.41%   |
| DDR5         | 70        | 2.22%   |
| Unknown      | 66        | 2.09%   |
| SDRAM        | 24        | 0.76%   |
| LPDDR3       | 17        | 0.54%   |
| DDR          | 15        | 0.47%   |
| LPDDR5       | 14        | 0.44%   |
| DRAM         | 3         | 0.09%   |
| SRAM         | 1         | 0.03%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1714      | 54.43%  |
| SODIMM       | 1306      | 41.47%  |
| Row Of Chips | 53        | 1.68%   |
| Unknown      | 47        | 1.49%   |
| Chip         | 13        | 0.41%   |
| FB-DIMM      | 10        | 0.32%   |
| RIMM         | 6         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1362      | 40.12%  |
| 4096   | 983       | 28.95%  |
| 16384  | 514       | 15.14%  |
| 2048   | 318       | 9.37%   |
| 32768  | 142       | 4.18%   |
| 1024   | 63        | 1.86%   |
| 512    | 7         | 0.21%   |
| 65536  | 3         | 0.09%   |
| 131072 | 1         | 0.03%   |
| 3072   | 1         | 0.03%   |
| 256    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1004      | 29.69%  |
| 2400    | 408       | 12.06%  |
| 1333    | 395       | 11.68%  |
| 2667    | 338       | 9.99%   |
| 3200    | 326       | 9.64%   |
| 2133    | 270       | 7.98%   |
| 800     | 72        | 2.13%   |
| 2666    | 67        | 1.98%   |
| 667     | 65        | 1.92%   |
| 4800    | 55        | 1.63%   |
| 1867    | 48        | 1.42%   |
| 1334    | 45        | 1.33%   |
| 1066    | 43        | 1.27%   |
| 1067    | 37        | 1.09%   |
| 3600    | 35        | 1.03%   |
| 3000    | 31        | 0.92%   |
| Unknown | 31        | 0.92%   |
| 2933    | 16        | 0.47%   |
| 6400    | 15        | 0.44%   |
| 5600    | 13        | 0.38%   |
| 1866    | 13        | 0.38%   |
| 533     | 11        | 0.33%   |
| 4267    | 10        | 0.3%    |
| 400     | 5         | 0.15%   |
| 975     | 4         | 0.12%   |
| 4266    | 3         | 0.09%   |
| 4000    | 3         | 0.09%   |
| 3733    | 3         | 0.09%   |
| 1200    | 3         | 0.09%   |
| 1400    | 2         | 0.06%   |
| 4133    | 1         | 0.03%   |
| 3534    | 1         | 0.03%   |
| 3333    | 1         | 0.03%   |
| 2866    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 1033    | 1         | 0.03%   |
| 266     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 28.57%  |
| Brother Industries    | 2         | 28.57%  |
| Prolific Technology   | 1         | 14.29%  |
| Lexmark International | 1         | 14.29%  |
| Apple                 | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                            | 1         | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1         | 12.5%   |
| HP PNP Fax Null                                                          | 1         | 12.5%   |
| HP LaserJet 1012                                                         | 1         | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 12.5%   |
| Brother MFC-L2685DW                                                      | 1         | 12.5%   |
| Brother MFC-J485DW                                                       | 1         | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 66.67%  |
| HP ScanJet 5300c/5370c                                                              | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 106       | 24.54%  |
| Bison Electronics                      | 51        | 11.81%  |
| Microdia                               | 38        | 8.8%    |
| Realtek Semiconductor                  | 34        | 7.87%   |
| Sunplus Innovation Technology          | 32        | 7.41%   |
| IMC Networks                           | 28        | 6.48%   |
| Logitech                               | 27        | 6.25%   |
| Apple                                  | 15        | 3.47%   |
| Quanta                                 | 14        | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 2.78%   |
| Suyin                                  | 11        | 2.55%   |
| Lite-On Technology                     | 10        | 2.31%   |
| Luxvisions Innotech Limited            | 8         | 1.85%   |
| Syntek                                 | 6         | 1.39%   |
| Lenovo                                 | 6         | 1.39%   |
| Importek                               | 4         | 0.93%   |
| Primax Electronics                     | 3         | 0.69%   |
| Intel                                  | 3         | 0.69%   |
| Alcor Micro                            | 3         | 0.69%   |
| WCM_USB                                | 2         | 0.46%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.46%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.46%   |
| Ricoh                                  | 2         | 0.46%   |
| OmniVision Technologies                | 2         | 0.46%   |
| Generalplus Technology                 | 2         | 0.46%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Xiongmai                               | 1         | 0.23%   |
| Unknown                                | 1         | 0.23%   |
| Supreme Electronics                    | 1         | 0.23%   |
| Silicon Motion                         | 1         | 0.23%   |
| Goodong Industry                       | 1         | 0.23%   |
| Arkmicro Technologies                  | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |
| ALi                                    | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 34        | 7.78%   |
| Bison Integrated Camera                             | 27        | 6.18%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 3.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 11        | 2.52%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.29%   |
| Microdia Integrated_Webcam_HD                       | 10        | 2.29%   |
| IMC Networks Integrated Camera                      | 10        | 2.29%   |
| Apple FaceTime HD Camera                            | 10        | 2.29%   |
| Microdia Integrated Webcam                          | 9         | 2.06%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 2.06%   |
| Realtek USB 2.0 PC Camera                           | 8         | 1.83%   |
| Logitech HD Pro Webcam C920                         | 7         | 1.6%    |
| Lite-On Integrated Camera                           | 7         | 1.6%    |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.6%    |
| Logitech Webcam C270                                | 6         | 1.37%   |
| Bison ThinkPad Integrated Camera                    | 6         | 1.37%   |
| Logitech BRIO Ultra HD Webcam                       | 5         | 1.14%   |
| Bison SunplusIT Integrated Camera                   | 5         | 1.14%   |
| Suyin Integrated_Webcam_HD                          | 4         | 0.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 0.92%   |
| Sunplus HD Webcam                                   | 4         | 0.92%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.92%   |
| Microdia Webcam Vitade AF                           | 4         | 0.92%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 0.92%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.92%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.92%   |
| IMC Networks Realtek PC Camera                      | 4         | 0.92%   |
| Chicony Integrated IR Camera                        | 4         | 0.92%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.92%   |
| Chicony HD WebCam                                   | 4         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.92%   |
| Bison Lenovo Integrated Webcam                      | 4         | 0.92%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 0.92%   |
| Syntek EasyCamera                                   | 3         | 0.69%   |
| Realtek Laptop Camera                               | 3         | 0.69%   |
| Realtek Integrated Webcam HD                        | 3         | 0.69%   |
| Quanta HP Webcam                                    | 3         | 0.69%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.69%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.69%   |
| IMC Networks EasyCamera                             | 3         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 33.33%  |
| Synaptics                  | 24        | 22.22%  |
| Upek                       | 14        | 12.96%  |
| STMicroelectronics         | 12        | 11.11%  |
| Shenzhen Goodix Technology | 7         | 6.48%   |
| AuthenTec                  | 7         | 6.48%   |
| Elan Microelectronics      | 3         | 2.78%   |
| Broadcom                   | 2         | 1.85%   |
| Samsung Electronics        | 1         | 0.93%   |
| LighTuning Technology      | 1         | 0.93%   |
| FocalTech Systems          | 1         | 0.93%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 17        | 15.74%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 14        | 12.96%  |
| STMicroelectronics Fingerprint Reader                                        | 12        | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 11        | 10.19%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 10        | 9.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 6         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 5         | 4.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 4         | 3.7%    |
| Validity Sensors Synaptics WBDI                                              | 4         | 3.7%    |
| Elan Fingerprint Sensor                                                      | 3         | 2.78%   |
| AuthenTec AES2810                                                            | 3         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 1.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 1.85%   |
| AuthenTec AES1660                                                            | 2         | 1.85%   |
| Validity Sensors VFS491                                                      | 1         | 0.93%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 0.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.93%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.93%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 0.93%   |
| Synaptics WBDI                                                               | 1         | 0.93%   |
| Synaptics UWP WBDI                                                           | 1         | 0.93%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 0.93%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 0.93%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 0.93%   |

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
| 1     | 1397      | 40.5%   |
| 0     | 1015      | 29.43%  |
| 2     | 684       | 19.83%  |
| 3     | 258       | 7.48%   |
| 4     | 72        | 2.09%   |
| 5     | 16        | 0.46%   |
| 6     | 5         | 0.14%   |
| 7     | 2         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 2062      | 62.98%  |
| Bluetooth                | 353       | 10.78%  |
| Net/wireless             | 298       | 9.1%    |
| Card reader              | 147       | 4.49%   |
| Firewire controller      | 107       | 3.27%   |
| Fingerprint reader       | 92        | 2.81%   |
| Net/ethernet             | 57        | 1.74%   |
| Sound                    | 56        | 1.71%   |
| Network                  | 46        | 1.41%   |
| Graphics card            | 22        | 0.67%   |
| Storage                  | 11        | 0.34%   |
| Modem                    | 8         | 0.24%   |
| Storage/raid             | 7         | 0.21%   |
| Storage/ata              | 3         | 0.09%   |
| Dvb card                 | 3         | 0.09%   |
| Storage/ide              | 2         | 0.06%   |

