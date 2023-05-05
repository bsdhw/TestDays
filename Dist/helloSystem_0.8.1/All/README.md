helloSystem 0.8.1 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.8.1/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.8.1/Notebook/README.md).

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

Total: 264

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B250M-A               | Desktop     | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 8056                        | Desktop     | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | Notebook    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| Packard Be... | DOT SE                      | Notebook    | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Dell          | 0VTC0D A02                  | Desktop     | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | Desktop     | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Acer          | V5-131                      | Notebook    | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Acer          | Spin SP314-21               | Convertible | [820e7da3c8](https://bsd-hardware.info/?probe=820e7da3c8) | Apr 18, 2023 |
| Medion        | E15302                      | Notebook    | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Pegatron      | 2A72h                       | Desktop     | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | Desktop     | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| Samsung       | 370E4K                      | Notebook    | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Acer          | Spin SP314-21               | Convertible | [a5ee042606](https://bsd-hardware.info/?probe=a5ee042606) | Apr 12, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3              | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Lenovo        | Tilapia CRB                 | Desktop     | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Google        | Wolf                        | Notebook    | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| ASUSTek       | X58C                        | Notebook    | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| DNS           | W9x0LU                      | Notebook    | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | Notebook    | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Intel         | Intel                       | Notebook    | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Dell          | Inspiron 3195               | Convertible | [2afbb563b7](https://bsd-hardware.info/?probe=2afbb563b7) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | Notebook    | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | Notebook    | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [0eb67759f0](https://bsd-hardware.info/?probe=0eb67759f0) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | Notebook    | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| Irbis         | NB78                        | Notebook    | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | Notebook    | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| MSI           | 870-G45                     | Desktop     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | Notebook    | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| Samsung       | R468/R418                   | Notebook    | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7945f26073](https://bsd-hardware.info/?probe=7945f26073) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| MSI           | 870-G45                     | Desktop     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| HP            | 8055                        | Desktop     | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | Desktop     | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Dell          | Latitude 5500               | Notebook    | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | Desktop     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Unknown       | T360D11                     | Desktop     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | Notebook    | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | Desktop     | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | Desktop     | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | Desktop     | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | Desktop     | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Dell          | 0GM819                      | Desktop     | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | Notebook    | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [40a4d98b9c](https://bsd-hardware.info/?probe=40a4d98b9c) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | Notebook    | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | Notebook    | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| HP            | 1632                        | Desktop     | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | Notebook    | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [c1c53bb88b](https://bsd-hardware.info/?probe=c1c53bb88b) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | Desktop     | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | 81B7                        | All in one  | [fa5eb6a694](https://bsd-hardware.info/?probe=fa5eb6a694) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [25256b1698](https://bsd-hardware.info/?probe=25256b1698) | Mar 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Dell          | Latitude D630               | Notebook    | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | Notebook    | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | Desktop     | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Google        | Panther                     | Desktop     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Samsung       | R468/R418                   | Notebook    | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | Desktop     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | Notebook    | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [de20e463ea](https://bsd-hardware.info/?probe=de20e463ea) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | Desktop     | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | Desktop     | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | Desktop     | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | Desktop     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | Desktop     | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| HP            | 3398                        | Desktop     | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | Notebook    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | Notebook    | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | Notebook    | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 227       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 224       | 98.68%  |
| GNOME        | 2         | 0.88%   |
| KDE5         | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 227       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 227       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 99        | 43.23%  |
| fr_FR   | 54        | 23.58%  |
| de_DE   | 16        | 6.99%   |
| es_ES   | 14        | 6.11%   |
| ru_RU   | 13        | 5.68%   |
| Unknown | 8         | 3.49%   |
| pl_PL   | 6         | 2.62%   |
| pt_BR   | 5         | 2.18%   |
| it_IT   | 4         | 1.75%   |
| ko_KR   | 2         | 0.87%   |
| jp_JP   | 2         | 0.87%   |
| pt      | 1         | 0.44%   |
| nl_NL   | 1         | 0.44%   |
| fr      | 1         | 0.44%   |
| fi_FI   | 1         | 0.44%   |
| es      | 1         | 0.44%   |
| en      | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 225       | 99.12%  |
| BIOS | 2         | 0.88%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 124       | 54.15%  |
| Zfs    | 105       | 45.85%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 225       | 99.12%  |
| MBR  | 2         | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 21.59%  |
| ASUSTek Computer    | 30        | 13.22%  |
| Dell                | 26        | 11.45%  |
| Hewlett-Packard     | 21        | 9.25%   |
| Gigabyte Technology | 20        | 8.81%   |
| Acer                | 12        | 5.29%   |
| MSI                 | 8         | 3.52%   |
| Toshiba             | 7         | 3.08%   |
| Intel               | 6         | 2.64%   |
| Fujitsu             | 6         | 2.64%   |
| Samsung Electronics | 5         | 2.2%    |
| Apple               | 5         | 2.2%    |
| Unknown             | 4         | 1.76%   |
| Google              | 3         | 1.32%   |
| ASRock              | 3         | 1.32%   |
| T-bao               | 2         | 0.88%   |
| Sony                | 2         | 0.88%   |
| Fujitsu Siemens     | 2         | 0.88%   |
| Foxconn             | 2         | 0.88%   |
| Plaisio             | 1         | 0.44%   |
| Pegatron            | 1         | 0.44%   |
| Packard Bell        | 1         | 0.44%   |
| Medion              | 1         | 0.44%   |
| LG Electronics      | 1         | 0.44%   |
| Irbis               | 1         | 0.44%   |
| IGEL Technology     | 1         | 0.44%   |
| Huanan              | 1         | 0.44%   |
| Dynabook Europe     | 1         | 0.44%   |
| DNS                 | 1         | 0.44%   |
| Biostar             | 1         | 0.44%   |
| BESSTAR Tech        | 1         | 0.44%   |
| AZW                 | 1         | 0.44%   |
| Axiomtek            | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 5         | 2.2%    |
| T-bao MINI PC                         | 2         | 0.88%   |
| MSI MS-7788                           | 2         | 0.88%   |
| HP Compaq Elite 8300 USDT             | 2         | 0.88%   |
| ASUS PRIME B250M-A                    | 2         | 0.88%   |
| Acer Spin SP314-21                    | 2         | 0.88%   |
| Toshiba Satellite P300                | 1         | 0.44%   |
| Toshiba Satellite L675D               | 1         | 0.44%   |
| Toshiba Satellite L50-B               | 1         | 0.44%   |
| Toshiba Satellite L40                 | 1         | 0.44%   |
| Toshiba Satellite C845                | 1         | 0.44%   |
| Toshiba Satellite A200                | 1         | 0.44%   |
| Toshiba PORTEGE R700                  | 1         | 0.44%   |
| Sony VGN-FZ19VN                       | 1         | 0.44%   |
| Sony SVL2412Z1EB                      | 1         | 0.44%   |
| Samsung R520/R522/R620                | 1         | 0.44%   |
| Samsung R468/R418                     | 1         | 0.44%   |
| Samsung 370E4K                        | 1         | 0.44%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.44%   |
| Samsung 275E4E/275E5E                 | 1         | 0.44%   |
| Plaisio Turbo X                       | 1         | 0.44%   |
| Pegatron Compaq dx2450 Microtower     | 1         | 0.44%   |
| Packard Bell DOT SE                   | 1         | 0.44%   |
| MSI MS-7C95                           | 1         | 0.44%   |
| MSI MS-7C51                           | 1         | 0.44%   |
| MSI MS-7C09                           | 1         | 0.44%   |
| MSI MS-7B86                           | 1         | 0.44%   |
| MSI MS-7599                           | 1         | 0.44%   |
| MSI Compaq dx2200 MT                  | 1         | 0.44%   |
| Medion E15302                         | 1         | 0.44%   |
| LG E500-L.A2M4A2                      | 1         | 0.44%   |
| Lenovo ZIUS6                          | 1         | 0.44%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.44%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.44%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.44%   |
| Lenovo ThinkPad X270 20HMS06Q1D       | 1         | 0.44%   |
| Lenovo ThinkPad X230 Tablet 34352TU   | 1         | 0.44%   |
| Lenovo ThinkPad X230 232578G          | 1         | 0.44%   |
| Lenovo ThinkPad X220 4291AN9          | 1         | 0.44%   |
| Lenovo ThinkPad X220 4290DK6          | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 31        | 13.66%  |
| Lenovo ThinkCentre      | 8         | 3.52%   |
| Dell Latitude           | 8         | 3.52%   |
| Dell Inspiron           | 8         | 3.52%   |
| ASUS PRIME              | 7         | 3.08%   |
| Toshiba Satellite       | 6         | 2.64%   |
| Dell OptiPlex           | 6         | 2.64%   |
| ASUS ROG                | 5         | 2.2%    |
| Unknown                 | 5         | 2.2%    |
| Lenovo IdeaPad          | 4         | 1.76%   |
| HP Pavilion             | 4         | 1.76%   |
| HP Laptop               | 4         | 1.76%   |
| HP EliteDesk            | 3         | 1.32%   |
| HP Compaq               | 3         | 1.32%   |
| Acer Aspire             | 3         | 1.32%   |
| T-bao MINI              | 2         | 0.88%   |
| MSI MS-7788             | 2         | 0.88%   |
| HP EliteBook            | 2         | 0.88%   |
| Gigabyte B450M          | 2         | 0.88%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.88%   |
| Fujitsu LIFEBOOK        | 2         | 0.88%   |
| Dell Precision          | 2         | 0.88%   |
| ASUS VivoBook           | 2         | 0.88%   |
| ASUS TUF                | 2         | 0.88%   |
| Acer Veriton            | 2         | 0.88%   |
| Acer Spin               | 2         | 0.88%   |
| Toshiba PORTEGE         | 1         | 0.44%   |
| Sony VGN-FZ19VN         | 1         | 0.44%   |
| Sony SVL2412Z1EB        | 1         | 0.44%   |
| Samsung R520            | 1         | 0.44%   |
| Samsung R468            | 1         | 0.44%   |
| Samsung 370E4K          | 1         | 0.44%   |
| Samsung 305E4A          | 1         | 0.44%   |
| Samsung 275E4E          | 1         | 0.44%   |
| Plaisio Turbo           | 1         | 0.44%   |
| Pegatron Compaq         | 1         | 0.44%   |
| Packard Bell DOT        | 1         | 0.44%   |
| MSI MS-7C95             | 1         | 0.44%   |
| MSI MS-7C51             | 1         | 0.44%   |
| MSI MS-7C09             | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 24        | 10.57%  |
| 2013    | 22        | 9.69%   |
| 2021    | 19        | 8.37%   |
| 2012    | 19        | 8.37%   |
| 2011    | 17        | 7.49%   |
| 2020    | 16        | 7.05%   |
| 2019    | 16        | 7.05%   |
| 2014    | 12        | 5.29%   |
| 2009    | 12        | 5.29%   |
| 2018    | 10        | 4.41%   |
| 2017    | 10        | 4.41%   |
| 2008    | 10        | 4.41%   |
| 2016    | 9         | 3.96%   |
| 2015    | 9         | 3.96%   |
| 2010    | 9         | 3.96%   |
| 2007    | 6         | 2.64%   |
| 2023    | 4         | 1.76%   |
| 2006    | 2         | 0.88%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 109       | 48.02%  |
| Desktop     | 108       | 47.58%  |
| Convertible | 4         | 1.76%   |
| Mini pc     | 3         | 1.32%   |
| All in one  | 2         | 0.88%   |
| Server      | 1         | 0.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 97.8%   |
| Yes  | 5         | 2.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 82        | 36.12%  |
| 4.01-8.0    | 58        | 25.55%  |
| 16.01-24.0  | 49        | 21.59%  |
| 32.01-64.0  | 16        | 7.05%   |
| 2.01-3.0    | 15        | 6.61%   |
| 3.01-4.0    | 2         | 0.88%   |
| 24.01-32.0  | 2         | 0.88%   |
| 64.01-256.0 | 2         | 0.88%   |
| 0.51-1.0    | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 122       | 53.28%  |
| 0.51-1.0 | 78        | 34.06%  |
| 1.01-2.0 | 24        | 10.48%  |
| 2.01-3.0 | 5         | 2.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 60.79%  |
| 2      | 43        | 18.94%  |
| 0      | 18        | 7.93%   |
| 3      | 17        | 7.49%   |
| 5      | 5         | 2.2%    |
| 9      | 2         | 0.88%   |
| 4      | 2         | 0.88%   |
| 7      | 1         | 0.44%   |
| 6      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 64.76%  |
| Yes       | 80        | 35.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 90.31%  |
| No        | 22        | 9.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 65.35%  |
| No        | 79        | 34.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 51.98%  |
| Yes       | 109       | 48.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 34        | 14.98%  |
| Russia             | 21        | 9.25%   |
| Germany            | 21        | 9.25%   |
| Spain              | 14        | 6.17%   |
| Brazil             | 14        | 6.17%   |
| Poland             | 12        | 5.29%   |
| Italy              | 9         | 3.96%   |
| France             | 9         | 3.96%   |
| Canada             | 9         | 3.96%   |
| Romania            | 8         | 3.52%   |
| Indonesia          | 5         | 2.2%    |
| India              | 5         | 2.2%    |
| Hungary            | 5         | 2.2%    |
| Serbia             | 4         | 1.76%   |
| Bulgaria           | 4         | 1.76%   |
| UK                 | 3         | 1.32%   |
| Turkey             | 3         | 1.32%   |
| Peru               | 3         | 1.32%   |
| Mexico             | 3         | 1.32%   |
| China              | 3         | 1.32%   |
| Australia          | 3         | 1.32%   |
| South Korea        | 2         | 0.88%   |
| Netherlands        | 2         | 0.88%   |
| Lithuania          | 2         | 0.88%   |
| Japan              | 2         | 0.88%   |
| Dominican Republic | 2         | 0.88%   |
| Chile              | 2         | 0.88%   |
| Belgium            | 2         | 0.88%   |
| Argentina          | 2         | 0.88%   |
| Ukraine            | 1         | 0.44%   |
| Switzerland        | 1         | 0.44%   |
| Sweden             | 1         | 0.44%   |
| Slovenia           | 1         | 0.44%   |
| Slovakia           | 1         | 0.44%   |
| San Marino         | 1         | 0.44%   |
| Portugal           | 1         | 0.44%   |
| Philippines        | 1         | 0.44%   |
| Kosovo             | 1         | 0.44%   |
| Israel             | 1         | 0.44%   |
| Ireland            | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 2.19%   |
| Berlin             | 5         | 2.19%   |
| St. Jean Baptiste  | 4         | 1.75%   |
| Milan              | 3         | 1.32%   |
| Wroclaw            | 2         | 0.88%   |
| Warsaw             | 2         | 0.88%   |
| Valencia           | 2         | 0.88%   |
| Sydney             | 2         | 0.88%   |
| St Petersburg      | 2         | 0.88%   |
| Sofia              | 2         | 0.88%   |
| Santo Domingo Este | 2         | 0.88%   |
| Santiago           | 2         | 0.88%   |
| Pensacola          | 2         | 0.88%   |
| Paris              | 2         | 0.88%   |
| Moscow             | 2         | 0.88%   |
| Montreal           | 2         | 0.88%   |
| Madrid             | 2         | 0.88%   |
| Krasnodar          | 2         | 0.88%   |
| Kirov              | 2         | 0.88%   |
| Belgrade           | 2         | 0.88%   |
| Zhengzhou          | 1         | 0.44%   |
| Yokohama           | 1         | 0.44%   |
| Yeosu              | 1         | 0.44%   |
| Yekaterinburg      | 1         | 0.44%   |
| Woodbridge         | 1         | 0.44%   |
| West Plains        | 1         | 0.44%   |
| Wausau             | 1         | 0.44%   |
| Volgodonsk         | 1         | 0.44%   |
| Vogogna            | 1         | 0.44%   |
| Vitória           | 1         | 0.44%   |
| Virovitica         | 1         | 0.44%   |
| Vilnius            | 1         | 0.44%   |
| Villena            | 1         | 0.44%   |
| Villemomble        | 1         | 0.44%   |
| Vienna             | 1         | 0.44%   |
| Victoria           | 1         | 0.44%   |
| Venice             | 1         | 0.44%   |
| Vecses             | 1         | 0.44%   |
| Valderrobres       | 1         | 0.44%   |
| Uiwang-si          | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 68     | 15.82%  |
| Samsung Electronics | 44        | 57     | 14.81%  |
| Seagate             | 39        | 46     | 13.13%  |
| Kingston            | 28        | 28     | 9.43%   |
| Toshiba             | 19        | 20     | 6.4%    |
| SanDisk             | 17        | 17     | 5.72%   |
| Hitachi             | 13        | 13     | 4.38%   |
| Crucial             | 11        | 14     | 3.7%    |
| Micron Technology   | 7         | 7      | 2.36%   |
| A-DATA Technology   | 6         | 7      | 2.02%   |
| Transcend           | 5         | 5      | 1.68%   |
| Intel               | 5         | 5      | 1.68%   |
| HGST                | 5         | 6      | 1.68%   |
| China               | 5         | 6      | 1.68%   |
| Maxtor              | 4         | 4      | 1.35%   |
| KingSpec            | 4         | 4      | 1.35%   |
| SK hynix            | 3         | 3      | 1.01%   |
| PNY                 | 3         | 3      | 1.01%   |
| Patriot             | 3         | 3      | 1.01%   |
| SPCC                | 2         | 2      | 0.67%   |
| OCZ                 | 2         | 2      | 0.67%   |
| Intenso             | 2         | 2      | 0.67%   |
| GOODRAM             | 2         | 2      | 0.67%   |
| Gigabyte Technology | 2         | 3      | 0.67%   |
| Verbatim            | 1         | 1      | 0.34%   |
| V-GeN               | 1         | 1      | 0.34%   |
| Silicon Motion      | 1         | 1      | 0.34%   |
| QUANTUM             | 1         | 1      | 0.34%   |
| Plextor             | 1         | 1      | 0.34%   |
| Pioneer             | 1         | 1      | 0.34%   |
| Palit               | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| Kston               | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.34%   |
| Fujitsu             | 1         | 1      | 0.34%   |
| EDGE                | 1         | 1      | 0.34%   |
| Dogfish             | 1         | 1      | 0.34%   |
| Corsair             | 1         | 1      | 0.34%   |
| Colorful            | 1         | 1      | 0.34%   |
| ASint Technology    | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 7         | 2.1%    |
| Seagate ST500DM002-1BD142 500GB      | 5         | 1.5%    |
| Seagate ST3500418AS 500GB            | 4         | 1.2%    |
| Samsung SSD 860 EVO 500GB            | 4         | 1.2%    |
| Samsung SSD 850 EVO 250GB            | 4         | 1.2%    |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.9%    |
| Samsung SSD 980 1TB                  | 3         | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.9%    |
| Kingston SHFS37A240G 240GB           | 3         | 0.9%    |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB             | 2         | 0.6%    |
| WDC PC SN520 SDAPNUW-128G-1014 128GB | 2         | 0.6%    |
| Toshiba DT01ACA100 1TB               | 2         | 0.6%    |
| Toshiba DT01ACA050 500GB             | 2         | 0.6%    |
| Seagate ST9500325AS 500GB            | 2         | 0.6%    |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.6%    |
| SanDisk SSD PLUS 120GB               | 2         | 0.6%    |
| Samsung SSD 980 PRO 500GB            | 2         | 0.6%    |
| Samsung SSD 980 500GB                | 2         | 0.6%    |
| Samsung SSD 970 PRO 512GB            | 2         | 0.6%    |
| Samsung SSD 840 EVO 250GB            | 2         | 0.6%    |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.6%    |
| PNY CS900 240GB SSD                  | 2         | 0.6%    |
| Patriot Burst 240GB                  | 2         | 0.6%    |
| Kingston SV300S37A60G 64GB           | 2         | 0.6%    |
| Kingston SA400S37480G 480GB          | 2         | 0.6%    |
| Kingston SA400S37120G 120GB          | 2         | 0.6%    |
| Intenso SSD 120GB                    | 2         | 0.6%    |
| HGST HTS725050A7E630 500GB           | 2         | 0.6%    |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.6%    |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.6%    |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.3%    |
| WDC WDS500G1B0A-00H9H0 500GB         | 1         | 0.3%    |
| WDC WDS250G1B0A-00H9H0 250GB         | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 46     | 32.5%   |
| WDC                 | 36        | 55     | 30%     |
| Toshiba             | 16        | 17     | 13.33%  |
| Hitachi             | 13        | 13     | 10.83%  |
| HGST                | 5         | 6      | 4.17%   |
| Samsung Electronics | 4         | 4      | 3.33%   |
| Maxtor              | 4         | 4      | 3.33%   |
| QUANTUM             | 1         | 1      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 28     | 16.67%  |
| Kingston            | 20        | 20     | 15.15%  |
| SanDisk             | 17        | 17     | 12.88%  |
| Crucial             | 11        | 14     | 8.33%   |
| WDC                 | 8         | 9      | 6.06%   |
| China               | 5         | 6      | 3.79%   |
| Transcend           | 4         | 4      | 3.03%   |
| KingSpec            | 4         | 4      | 3.03%   |
| Intel               | 4         | 4      | 3.03%   |
| PNY                 | 3         | 3      | 2.27%   |
| Patriot             | 3         | 3      | 2.27%   |
| Micron Technology   | 3         | 3      | 2.27%   |
| A-DATA Technology   | 3         | 3      | 2.27%   |
| Toshiba             | 2         | 2      | 1.52%   |
| SPCC                | 2         | 2      | 1.52%   |
| OCZ                 | 2         | 2      | 1.52%   |
| Intenso             | 2         | 2      | 1.52%   |
| GOODRAM             | 2         | 2      | 1.52%   |
| Gigabyte Technology | 2         | 3      | 1.52%   |
| Verbatim            | 1         | 1      | 0.76%   |
| V-GeN               | 1         | 1      | 0.76%   |
| SK hynix            | 1         | 1      | 0.76%   |
| Plextor             | 1         | 1      | 0.76%   |
| Pioneer             | 1         | 1      | 0.76%   |
| Palit               | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| Kston               | 1         | 1      | 0.76%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.76%   |
| EDGE                | 1         | 1      | 0.76%   |
| Dogfish             | 1         | 1      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |
| AMD                 | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 111       | 144    | 41.73%  |
| HDD  | 108       | 148    | 40.6%   |
| NVMe | 47        | 54     | 17.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 187       | 292    | 79.91%  |
| NVMe | 47        | 54     | 20.09%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 157       | 205    | 70.09%  |
| 0.51-1.0   | 41        | 49     | 18.3%   |
| 1.01-2.0   | 13        | 21     | 5.8%    |
| 3.01-4.0   | 7         | 8      | 3.13%   |
| 2.01-3.0   | 3         | 6      | 1.34%   |
| 4.01-10.0  | 2         | 2      | 0.89%   |
| 10.01-20.0 | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 119       | 52.19%  |
| 101-250    | 36        | 15.79%  |
| 251-500    | 28        | 12.28%  |
| 51-100     | 27        | 11.84%  |
| 501-1000   | 15        | 6.58%   |
| 21-50      | 2         | 0.88%   |
| Unknown    | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 223       | 98.24%  |
| 21-50   | 2         | 0.88%   |
| 101-250 | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                  | 2         | 2      | 3.51%   |
| Seagate ST500LM000-1EJ162 500GB            | 2         | 2      | 3.51%   |
| WDC WD800JD-75MSA3 80GB                    | 1         | 1      | 1.75%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1         | 1      | 1.75%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1         | 1      | 1.75%   |
| WDC WD30PURZ-85AKKY0 3TB                   | 1         | 1      | 1.75%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1         | 1      | 1.75%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1         | 1      | 1.75%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1         | 1      | 1.75%   |
| WDC WD10JPVX-60JC3T1 1TB                   | 1         | 1      | 1.75%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1         | 1      | 1.75%   |
| WDC WD10EARS-003BB1 1TB                    | 1         | 1      | 1.75%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 1      | 1.75%   |
| Toshiba MQ01ABD032 320GB                   | 1         | 1      | 1.75%   |
| Toshiba MK3259GSXP 320GB                   | 1         | 1      | 1.75%   |
| Toshiba MK1646GSX 160GB                    | 1         | 1      | 1.75%   |
| Toshiba MK1229GSG 120GB                    | 1         | 1      | 1.75%   |
| Toshiba DT01ACA100 1TB                     | 1         | 1      | 1.75%   |
| SK hynix SC210 mSATA 256GB                 | 1         | 1      | 1.75%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1         | 1      | 1.75%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 1.75%   |
| Seagate ST9160827AS 160GB                  | 1         | 1      | 1.75%   |
| Seagate ST500DM002-1BD142 500GB            | 1         | 1      | 1.75%   |
| Seagate ST380215AS 80GB                    | 1         | 1      | 1.75%   |
| Seagate ST3500418AS 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST3500320AS 500GB                  | 1         | 1      | 1.75%   |
| Seagate ST3320620AS 320GB                  | 1         | 1      | 1.75%   |
| Seagate ST320LT020-9YG142 320GB            | 1         | 1      | 1.75%   |
| Seagate ST320LT012-9WS14C 320GB            | 1         | 2      | 1.75%   |
| Seagate ST2000DM008-2FR102 2TB             | 1         | 1      | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 1         | 2      | 1.75%   |
| Seagate ST1000DM010-2EP102 1TB             | 1         | 1      | 1.75%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1         | 1      | 1.75%   |
| Samsung Electronics HD103SJ 1TB            | 1         | 1      | 1.75%   |
| Maxtor 6Y080M0 82GB                        | 1         | 1      | 1.75%   |
| Maxtor 6V080E0 80GB                        | 1         | 1      | 1.75%   |
| Maxtor 6L080P0 82GB                        | 1         | 1      | 1.75%   |
| Kingston SV300S37A60G 64GB                 | 1         | 1      | 1.75%   |
| Kingston SA400S37240G 240GB                | 1         | 1      | 1.75%   |
| Intel SSDSC2BF180A4L 180GB                 | 1         | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 18     | 25.45%  |
| WDC                 | 10        | 10     | 18.18%  |
| Hitachi             | 8         | 8      | 14.55%  |
| Toshiba             | 6         | 6      | 10.91%  |
| HGST                | 4         | 4      | 7.27%   |
| Maxtor              | 3         | 3      | 5.45%   |
| Crucial             | 3         | 4      | 5.45%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| Kingston            | 2         | 2      | 3.64%   |
| SK hynix            | 1         | 1      | 1.82%   |
| Silicon Motion      | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 18     | 30.43%  |
| WDC                 | 10        | 10     | 21.74%  |
| Hitachi             | 8         | 8      | 17.39%  |
| Toshiba             | 6         | 6      | 13.04%  |
| HGST                | 4         | 4      | 8.7%    |
| Maxtor              | 3         | 3      | 6.52%   |
| Samsung Electronics | 1         | 1      | 2.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 50     | 83.64%  |
| SSD  | 7         | 8      | 12.73%  |
| NVMe | 2         | 2      | 3.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB | 1         | 1      | 33.33%  |
| WDC WD1600BEVT-22ZCT0 160GB | 1         | 1      | 33.33%  |
| SanDisk pSSD 128GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| SanDisk | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 169       | 276    | 73.16%  |
| Malfunc  | 55        | 60     | 23.81%  |
| Detected | 4         | 7      | 1.73%   |
| Failed   | 3         | 3      | 1.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 61.17%  |
| AMD                              | 38        | 13.92%  |
| Samsung Electronics              | 20        | 7.33%   |
| SanDisk                          | 8         | 2.93%   |
| Nvidia                           | 8         | 2.93%   |
| Kingston Technology Company      | 8         | 2.93%   |
| Micron Technology                | 4         | 1.47%   |
| Silicon Motion                   | 3         | 1.1%    |
| Marvell Technology Group         | 3         | 1.1%    |
| ASMedia Technology               | 3         | 1.1%    |
| SK hynix                         | 2         | 0.73%   |
| Realtek Semiconductor            | 2         | 0.73%   |
| ADATA Technology                 | 2         | 0.73%   |
| VIA Technologies                 | 1         | 0.37%   |
| Toshiba                          | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Phison Electronics               | 1         | 0.37%   |
| Broadcom / LSI                   | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 18        | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 17        | 5.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 4.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 4.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 2.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 2.47%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.23%   |
| Micron NVMe Storage Controller                                                          | 4         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.23%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.23%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.23%   |
| Unknown                                                                                 | 4         | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 0.93%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 3         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 3         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 176       | 63.54%  |
| NVMe | 46        | 16.61%  |
| IDE  | 44        | 15.88%  |
| RAID | 10        | 3.61%   |
| SAS  | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 182       | 80.18%  |
| AMD    | 45        | 19.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 2.2%    |
| Intel CPU Version                             | 4         | 1.76%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 1.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.76%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.32%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3         | 1.32%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 1.32%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.32%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.88%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.88%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2         | 0.88%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.88%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2         | 0.88%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2         | 0.88%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 2         | 0.88%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.88%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.88%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.88%   |
| Intel Core 2 Duo                              | 2         | 0.88%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.88%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2         | 0.88%   |
| Intel Celeron 2955U @ 1.40GHz                 | 2         | 0.88%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 2         | 0.88%   |
| Intel 12th Gen Core i5-12400                  | 2         | 0.88%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.88%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 0.88%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.88%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 0.88%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.44%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.44%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.44%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1         | 0.44%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 57        | 25.11%  |
| Intel Core i7           | 30        | 13.22%  |
| Intel Core i3           | 25        | 11.01%  |
| Intel Celeron           | 20        | 8.81%   |
| Intel Core 2 Duo        | 18        | 7.93%   |
| Other                   | 13        | 5.73%   |
| AMD Ryzen 5             | 11        | 4.85%   |
| AMD Ryzen 7             | 7         | 3.08%   |
| Intel Xeon              | 6         | 2.64%   |
| AMD Ryzen 3             | 5         | 2.2%    |
| Intel Atom              | 4         | 1.76%   |
| Intel Pentium           | 3         | 1.32%   |
| Intel Core 2 Quad       | 2         | 0.88%   |
| AMD Phenom II X4        | 2         | 0.88%   |
| AMD E                   | 2         | 0.88%   |
| AMD Athlon II X2        | 2         | 0.88%   |
| AMD A4                  | 2         | 0.88%   |
| Intel Pentium Gold      | 1         | 0.44%   |
| Intel Pentium Dual-Core | 1         | 0.44%   |
| Intel Pentium Dual      | 1         | 0.44%   |
| Intel Pentium 4         | 1         | 0.44%   |
| Intel Core i9           | 1         | 0.44%   |
| Intel Celeron D         | 1         | 0.44%   |
| AMD Ryzen Embedded      | 1         | 0.44%   |
| AMD Ryzen 9             | 1         | 0.44%   |
| AMD Phenom II X2        | 1         | 0.44%   |
| AMD Phenom II           | 1         | 0.44%   |
| AMD FX                  | 1         | 0.44%   |
| AMD E1                  | 1         | 0.44%   |
| AMD Athlon X2           | 1         | 0.44%   |
| AMD Athlon II X4        | 1         | 0.44%   |
| AMD Athlon 64           | 1         | 0.44%   |
| AMD Athlon              | 1         | 0.44%   |
| AMD A8                  | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 103       | 45.37%  |
| 4       | 72        | 31.72%  |
| Unknown | 18        | 7.93%   |
| 12      | 9         | 3.96%   |
| 6       | 9         | 3.96%   |
| 8       | 7         | 3.08%   |
| 1       | 4         | 1.76%   |
| 16      | 3         | 1.32%   |
| 24      | 1         | 0.44%   |
| 10      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 221       | 97.36%  |
| 2      | 6         | 2.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 104       | 45.81%  |
| 2       | 102       | 44.93%  |
| Unknown | 21        | 9.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 12.33%  |
| IvyBridge     | 27        | 11.89%  |
| Haswell       | 25        | 11.01%  |
| SandyBridge   | 19        | 8.37%   |
| Skylake       | 18        | 7.93%   |
| Penryn        | 16        | 7.05%   |
| Core          | 14        | 6.17%   |
| Zen+          | 12        | 5.29%   |
| Zen 3         | 9         | 3.96%   |
| K10           | 8         | 3.52%   |
| Silvermont    | 6         | 2.64%   |
| Broadwell     | 6         | 2.64%   |
| Unknown       | 5         | 2.2%    |
| Zen           | 4         | 1.76%   |
| Westmere      | 4         | 1.76%   |
| Bonnell       | 4         | 1.76%   |
| TigerLake     | 3         | 1.32%   |
| Piledriver    | 3         | 1.32%   |
| Bobcat        | 3         | 1.32%   |
| Goldmont plus | 2         | 0.88%   |
| Excavator     | 2         | 0.88%   |
| CometLake     | 2         | 0.88%   |
| Zen 2         | 1         | 0.44%   |
| NetBurst      | 1         | 0.44%   |
| Nehalem       | 1         | 0.44%   |
| K8 Hammer     | 1         | 0.44%   |
| K10 Llano     | 1         | 0.44%   |
| Goldmont      | 1         | 0.44%   |
| Bulldozer     | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 146       | 58.87%  |
| AMD                              | 51        | 20.56%  |
| Nvidia                           | 49        | 19.76%  |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Matrox Electronics Systems       | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.38%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.85%   |
| Intel HD Graphics 530                                                                    | 9         | 3.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.31%   |
| Intel HD Graphics 630                                                                    | 6         | 2.31%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.92%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 1.15%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.15%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.15%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.77%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.77%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.77%   |
| Intel HD Graphics 620                                                                    | 2         | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.77%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 46.05%  |
| 1 x AMD        | 40        | 17.54%  |
| 1 x Nvidia     | 37        | 16.23%  |
| 2 x Intel      | 21        | 9.21%   |
| Intel + Nvidia | 10        | 4.39%   |
| Intel + AMD    | 10        | 4.39%   |
| 2 x Nvidia     | 1         | 0.44%   |
| 2 x AMD        | 1         | 0.44%   |
| 1 x SiS        | 1         | 0.44%   |
| 1 x Matrox     | 1         | 0.44%   |
| AMD + Nvidia   | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 189       | 83.26%  |
| Proprietary | 30        | 13.22%  |
| Unknown     | 8         | 3.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 76.21%  |
| 0.01-0.5   | 13        | 5.73%   |
| 3.01-4.0   | 12        | 5.29%   |
| 0.51-1.0   | 10        | 4.41%   |
| 1.01-2.0   | 9         | 3.96%   |
| 5.01-6.0   | 5         | 2.2%    |
| 7.01-8.0   | 3         | 1.32%   |
| 2.01-3.0   | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Acer                 | 4         | 19.05%  |
| Dell                 | 3         | 14.29%  |
| Unknown              | 3         | 14.29%  |
| LG Electronics       | 2         | 9.52%   |
| BenQ                 | 2         | 9.52%   |
| PKB                  | 1         | 4.76%   |
| NEC Computers        | 1         | 4.76%   |
| Microstep            | 1         | 4.76%   |
| Idek Iiyama          | 1         | 4.76%   |
| AUS                  | 1         | 4.76%   |
| AOC                  | 1         | 4.76%   |
| Ancor Communications | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Unknown                                         | 3         | 14.29%  |
| PKB LCD Monitor MAE200W 1680x1050               | 1         | 4.76%   |
| NEC Computers LCD Monitor 70GX2 1280x1024       | 1         | 4.76%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080     | 1         | 4.76%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080 | 1         | 4.76%   |
| LG Electronics LCD Monitor L1918S 1280x1024     | 1         | 4.76%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160      | 1         | 4.76%   |
| Dell LCD Monitor U2419HC 1920x1080              | 1         | 4.76%   |
| Dell LCD Monitor S2721D 2560x1440               | 1         | 4.76%   |
| Dell LCD Monitor E2211H 1920x1080               | 1         | 4.76%   |
| BenQ LCD Monitor GW2780 1920x1080               | 1         | 4.76%   |
| BenQ LCD Monitor GW2260 1920x1080               | 1         | 4.76%   |
| AUS LCD Monitor ASUS VG247Q1A 1920x1080         | 1         | 4.76%   |
| AOC LCD Monitor 27B2 1920x1080                  | 1         | 4.76%   |
| Ancor Communications LCD Monitor VX238          | 1         | 4.76%   |
| Acer LCD Monitor XV280K 3840x2160               | 1         | 4.76%   |
| Acer LCD Monitor XB273K GP 3840x2160            | 1         | 4.76%   |
| Acer LCD Monitor VG270U 2560x1440               | 1         | 4.76%   |
| Acer LCD Monitor KG251Q 3840x1080               | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 8         | 38.1%   |
| 3840x2160 (4K)     | 2         | 9.52%   |
| 2560x1440 (QHD)    | 2         | 9.52%   |
| 1280x1024 (SXGA)   | 2         | 9.52%   |
| Unknown            | 2         | 9.52%   |
| 5760x2160          | 1         | 4.76%   |
| 3840x1080          | 1         | 4.76%   |
| 2560x1600          | 1         | 4.76%   |
| 1680x1050 (WSXGA+) | 1         | 4.76%   |
| 1366x768 (WXGA)    | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 19        | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 19        | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 193       | 85.02%  |
| 0     | 27        | 11.89%  |
| 2     | 7         | 3.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 113       | 35.87%  |
| Realtek Semiconductor             | 112       | 35.56%  |
| Qualcomm Atheros                  | 40        | 12.7%   |
| Broadcom                          | 12        | 3.81%   |
| Marvell Technology Group          | 7         | 2.22%   |
| TP-Link                           | 4         | 1.27%   |
| Sierra Wireless                   | 3         | 0.95%   |
| Samsung Electronics               | 3         | 0.95%   |
| Ralink                            | 3         | 0.95%   |
| Nvidia                            | 3         | 0.95%   |
| Xiaomi                            | 2         | 0.63%   |
| Ralink Technology                 | 2         | 0.63%   |
| MediaTek                          | 2         | 0.63%   |
| Ericsson Business Mobile Networks | 2         | 0.63%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.32%   |
| Huawei Technologies               | 1         | 0.32%   |
| Google                            | 1         | 0.32%   |
| Edimax Technology                 | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |
| Atheros                           | 1         | 0.32%   |
| Accton Technology                 | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 82        | 21.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 19        | 5.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13        | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.58%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.58%   |
| Intel Wireless 8260                                                     | 6         | 1.58%   |
| Intel Ethernet Connection (2) I219-LM                                   | 6         | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.32%   |
| Intel Wireless 7265                                                     | 5         | 1.32%   |
| Intel Wireless 7260                                                     | 5         | 1.32%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.32%   |
| Intel Ethernet Connection I217-V                                        | 5         | 1.32%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.06%   |
| Intel Wireless 3165                                                     | 4         | 1.06%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.06%   |
| Intel Ethernet Controller I225-V                                        | 4         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.79%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 0.79%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.79%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.53%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 46.2%   |
| Qualcomm Atheros      | 33        | 20.89%  |
| Realtek Semiconductor | 25        | 15.82%  |
| Broadcom              | 10        | 6.33%   |
| TP-Link               | 4         | 2.53%   |
| Ralink                | 3         | 1.9%    |
| Sierra Wireless       | 2         | 1.27%   |
| Ralink Technology     | 2         | 1.27%   |
| MediaTek              | 2         | 1.27%   |
| Edimax Technology     | 1         | 0.63%   |
| D-Link                | 1         | 0.63%   |
| Atheros               | 1         | 0.63%   |
| Accton Technology     | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 5.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 4.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.75%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.75%   |
| Intel Wireless 8260                                                     | 6         | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.13%   |
| Intel Wireless 7265                                                     | 5         | 3.13%   |
| Intel Wireless 7260                                                     | 5         | 3.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 3.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 2.5%    |
| Intel Wireless 3165                                                     | 4         | 2.5%    |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.88%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.25%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 2         | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.25%   |
| Intel WiFi Link 5100                                                    | 2         | 1.25%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.25%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.25%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.25%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.25%   |
| Sierra Wireless EM7455                                                  | 1         | 0.63%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 100       | 47.39%  |
| Intel                            | 80        | 37.91%  |
| Qualcomm Atheros                 | 11        | 5.21%   |
| Marvell Technology Group         | 7         | 3.32%   |
| Samsung Electronics              | 3         | 1.42%   |
| Nvidia                           | 3         | 1.42%   |
| Broadcom                         | 3         | 1.42%   |
| Xiaomi                           | 2         | 0.95%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Huawei Technologies              | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 38.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 8.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.07%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 2.8%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.34%   |
| Intel Ethernet Connection I217-V                                  | 5         | 2.34%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.87%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.4%    |
| Nvidia MCP79 Ethernet                                             | 3         | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.4%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.4%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.4%    |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.93%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2         | 0.93%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.47%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.47%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 205       | 57.1%   |
| WiFi     | 149       | 41.5%   |
| Unknown  | 4         | 1.11%   |
| Modem    | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 141       | 67.14%  |
| WiFi     | 69        | 32.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 121       | 53.07%  |
| 1     | 100       | 43.86%  |
| 0     | 5         | 2.19%   |
| 3     | 2         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 210       | 91.7%   |
| Yes  | 19        | 8.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 41.82%  |
| Qualcomm Atheros Communications | 12        | 10.91%  |
| Realtek Semiconductor           | 10        | 9.09%   |
| Broadcom                        | 8         | 7.27%   |
| Cambridge Silicon Radio         | 7         | 6.36%   |
| IMC Networks                    | 5         | 4.55%   |
| Apple                           | 5         | 4.55%   |
| Foxconn / Hon Hai               | 4         | 3.64%   |
| Lite-On Technology              | 3         | 2.73%   |
| ASUSTek Computer                | 3         | 2.73%   |
| TP-Link                         | 2         | 1.82%   |
| Primax Electronics              | 1         | 0.91%   |
| Hewlett-Packard                 | 1         | 0.91%   |
| Fujitsu                         | 1         | 0.91%   |
| Dell                            | 1         | 0.91%   |
| Askey Computer                  | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 26        | 23.64%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7         | 6.36%   |
| Realtek Bluetooth Adapter                                   | 6         | 5.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 4.55%   |
| Intel AX201 Bluetooth                                       | 5         | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 2.73%   |
| Intel AX200 Bluetooth                                       | 3         | 2.73%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.73%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 1.82%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.82%   |
| Lite-On Bluetooth USB Module                                | 2         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.82%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.82%   |
| Apple Bluetooth Host Controller                             | 2         | 1.82%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.91%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.91%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.91%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1         | 0.91%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.91%   |
| Intel AX210 Bluetooth                                       | 1         | 0.91%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.91%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1         | 0.91%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.91%   |
| IMC Networks Bluetooth module                               | 1         | 0.91%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.91%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1         | 0.91%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 0.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.91%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.91%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.91%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 171       | 58.16%  |
| AMD                              | 58        | 19.73%  |
| Nvidia                           | 39        | 13.27%  |
| C-Media Electronics              | 7         | 2.38%   |
| Texas Instruments                | 3         | 1.02%   |
| Creative Labs                    | 3         | 1.02%   |
| Realtek Semiconductor            | 2         | 0.68%   |
| Generalplus Technology           | 2         | 0.68%   |
| Yamaha                           | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Phison Electronics               | 1         | 0.34%   |
| OPPO Electronics                 | 1         | 0.34%   |
| KTMicro                          | 1         | 0.34%   |
| Hewlett-Packard                  | 1         | 0.34%   |
| GN Netcom                        | 1         | 0.34%   |
| GEMBIRD                          | 1         | 0.34%   |
| Edifier Technology               | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 6.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 5.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 4.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 4.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 4.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 3.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.15%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.58%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.72%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 5         | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.15%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.86%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.86%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.86%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.86%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.86%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 19.85%  |
| SK hynix            | 38        | 14.23%  |
| Kingston            | 34        | 12.73%  |
| Unknown             | 28        | 10.49%  |
| Micron Technology   | 17        | 6.37%   |
| Crucial             | 16        | 5.99%   |
| Corsair             | 16        | 5.99%   |
| Unknown             | 13        | 4.87%   |
| Nanya Technology    | 6         | 2.25%   |
| G.Skill             | 6         | 2.25%   |
| A-DATA Technology   | 5         | 1.87%   |
| Smart               | 4         | 1.5%    |
| Ramaxel Technology  | 4         | 1.5%    |
| Elpida              | 4         | 1.5%    |
| Patriot             | 3         | 1.12%   |
| Unknown (ABCD)      | 2         | 0.75%   |
| Apacer              | 2         | 0.75%   |
| Transcend           | 1         | 0.37%   |
| Team                | 1         | 0.37%   |
| Swissbit            | 1         | 0.37%   |
| Silicon Power       | 1         | 0.37%   |
| SHARETRONIC         | 1         | 0.37%   |
| Qumo                | 1         | 0.37%   |
| Multilaser          | 1         | 0.37%   |
| MemoWise            | 1         | 0.37%   |
| Kingmax             | 1         | 0.37%   |
| Juhor               | 1         | 0.37%   |
| GOODRAM             | 1         | 0.37%   |
| Golden Empire       | 1         | 0.37%   |
| Avant               | 1         | 0.37%   |
| Atermiter           | 1         | 0.37%   |
| ASint Technology    | 1         | 0.37%   |
| AMD                 | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                 | 13        | 4.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                              | 4         | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                  | 4         | 1.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                                      | 3         | 1.07%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                   | 3         | 1.07%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s                 | 3         | 1.07%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2         | 0.71%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2         | 0.71%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                              | 2         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s        | 2         | 0.71%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.71%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s            | 2         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.71%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                   | 2         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                   | 2         | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 2         | 0.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 2         | 0.71%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s                   | 2         | 0.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.71%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2         | 0.71%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM 1333MT/s                      | 2         | 0.71%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2         | 0.71%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.71%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 2         | 0.71%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1         | 0.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                              | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                              | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                   | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                     | 1         | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1         | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1         | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 97        | 43.11%  |
| DDR4    | 86        | 38.22%  |
| DDR2    | 23        | 10.22%  |
| Unknown | 11        | 4.89%   |
| SDRAM   | 4         | 1.78%   |
| LPDDR4  | 3         | 1.33%   |
| LPDDR3  | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 123       | 54.42%  |
| DIMM         | 93        | 41.15%  |
| Row Of Chips | 4         | 1.77%   |
| Chip         | 4         | 1.77%   |
| Unknown      | 2         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 86        | 34.4%   |
| 4096  | 76        | 30.4%   |
| 2048  | 53        | 21.2%   |
| 16384 | 20        | 8%      |
| 1024  | 15        | 6%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 21.34%  |
| 1333    | 33        | 13.81%  |
| 2400    | 28        | 11.72%  |
| 2133    | 21        | 8.79%   |
| 3200    | 20        | 8.37%   |
| 2667    | 17        | 7.11%   |
| 667     | 15        | 6.28%   |
| 800     | 10        | 4.18%   |
| 1067    | 8         | 3.35%   |
| 1334    | 7         | 2.93%   |
| Unknown | 6         | 2.51%   |
| 1867    | 4         | 1.67%   |
| 3600    | 3         | 1.26%   |
| 1066    | 3         | 1.26%   |
| 3000    | 2         | 0.84%   |
| 2048    | 2         | 0.84%   |
| 533     | 2         | 0.84%   |
| 3733    | 1         | 0.42%   |
| 3333    | 1         | 0.42%   |
| 2666    | 1         | 0.42%   |
| 1866    | 1         | 0.42%   |
| 1639    | 1         | 0.42%   |
| 1200    | 1         | 0.42%   |
| 400     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 66.67%  |
| Hewlett-Packard    | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet 1020         | 1         | 33.33%  |
| Brother HL-L2300D series | 1         | 33.33%  |
| Brother DCP-J152W        | 1         | 33.33%  |

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
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 22.22%  |
| Bison Electronics                      | 12        | 13.33%  |
| Microdia                               | 11        | 12.22%  |
| Sunplus Innovation Technology          | 8         | 8.89%   |
| Realtek Semiconductor                  | 6         | 6.67%   |
| IMC Networks                           | 5         | 5.56%   |
| Silicon Motion                         | 3         | 3.33%   |
| Logitech                               | 3         | 3.33%   |
| Lite-On Technology                     | 3         | 3.33%   |
| Syntek                                 | 2         | 2.22%   |
| Quanta                                 | 2         | 2.22%   |
| Lenovo                                 | 2         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.22%   |
| Z-Star Microelectronics                | 1         | 1.11%   |
| Y Media                                | 1         | 1.11%   |
| Trust                                  | 1         | 1.11%   |
| Suyin                                  | 1         | 1.11%   |
| Supreme Electronics                    | 1         | 1.11%   |
| Luxvisions Innotech Limited            | 1         | 1.11%   |
| Intel                                  | 1         | 1.11%   |
| Importek                               | 1         | 1.11%   |
| Genesys Logic                          | 1         | 1.11%   |
| GEMBIRD                                | 1         | 1.11%   |
| Alcor Micro                            | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 8         | 8.89%   |
| Microdia Integrated_Webcam_HD                               | 5         | 5.56%   |
| Chicony Integrated Camera                                   | 5         | 5.56%   |
| Realtek Integrated_Webcam_HD                                | 4         | 4.44%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 2.22%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 2.22%   |
| Microdia REDRAGON Live Camera Audio                         | 2         | 2.22%   |
| Lite-On Integrated Camera                                   | 2         | 2.22%   |
| Lenovo Integrated Webcam                                    | 2         | 2.22%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 2         | 2.22%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 1.11%   |
| Y Media USB Camera                                          | 1         | 1.11%   |
| Trust Trust Full HD Webcam                                  | 1         | 1.11%   |
| Syntek HP Webcam                                            | 1         | 1.11%   |
| Syntek EasyCamera                                           | 1         | 1.11%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.11%   |
| Supreme Integrated Camera                                   | 1         | 1.11%   |
| Sunplus SPCA2650 AV Camera                                  | 1         | 1.11%   |
| Sunplus Integrated Camera                                   | 1         | 1.11%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.11%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 1.11%   |
| Silicon Motion WebCam SCX Series                            | 1         | 1.11%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 1.11%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 1.11%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 1.11%   |
| Realtek Dell EasyCamera                                     | 1         | 1.11%   |
| Quanta Realtek PC Camera                                    | 1         | 1.11%   |
| Quanta HD WebCam                                            | 1         | 1.11%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.11%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.11%   |
| Microdia Integrated Webcam                                  | 1         | 1.11%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.11%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.11%   |
| Logitech Webcam C270                                        | 1         | 1.11%   |
| Logitech HD Pro Webcam C920                                 | 1         | 1.11%   |
| Logitech BRIO Ultra HD Webcam                               | 1         | 1.11%   |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.11%   |
| Intel RealSense SR300                                       | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| AuthenTec                  | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| LighTuning Technology      | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 9.09%   |
| Validity Sensors Fingerprint scanner                   | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |
| AuthenTec AES2660                                      | 1         | 9.09%   |
| AuthenTec AES1660                                      | 1         | 9.09%   |

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
| 1     | 108       | 47.37%  |
| 0     | 59        | 25.88%  |
| 2     | 48        | 21.05%  |
| 3     | 12        | 5.26%   |
| 4     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 142       | 63.11%  |
| Net/wireless             | 28        | 12.44%  |
| Bluetooth                | 15        | 6.67%   |
| Card reader              | 12        | 5.33%   |
| Sound                    | 11        | 4.89%   |
| Fingerprint reader       | 11        | 4.89%   |
| Storage                  | 4         | 1.78%   |
| Network                  | 1         | 0.44%   |
| Dvb card                 | 1         | 0.44%   |

