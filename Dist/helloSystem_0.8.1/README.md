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

Total: 567

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Acer          | Aspire R3-131T              | Notebook    | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Dell          | 0DFRFW A01                  | Desktop     | [4532391ffd](https://bsd-hardware.info/?probe=4532391ffd) | May 06, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | Notebook    | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d87059c342](https://bsd-hardware.info/?probe=d87059c342) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [35ab248dd4](https://bsd-hardware.info/?probe=35ab248dd4) | May 04, 2024 |
| Shenzhen M... | PHBRC                       | Mini pc     | [f657134100](https://bsd-hardware.info/?probe=f657134100) | Apr 30, 2024 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [52ac87d342](https://bsd-hardware.info/?probe=52ac87d342) | Apr 27, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [256e25b666](https://bsd-hardware.info/?probe=256e25b666) | Apr 16, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| ASUSTek       | N76VZ                       | Notebook    | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | Notebook    | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Gigabyte      | H55M-USB3                   | Desktop     | [748ef69c9f](https://bsd-hardware.info/?probe=748ef69c9f) | Mar 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| HP            | 2B34                        | Desktop     | [850e6bf958](https://bsd-hardware.info/?probe=850e6bf958) | Mar 20, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| HP            | 21D0                        | Desktop     | [7ca5d182a1](https://bsd-hardware.info/?probe=7ca5d182a1) | Mar 16, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2e83945861](https://bsd-hardware.info/?probe=2e83945861) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| HP            | dx2480 MT(FN868PA)          | Desktop     | [d700a91a81](https://bsd-hardware.info/?probe=d700a91a81) | Mar 14, 2024 |
| HP            | 21D0                        | Desktop     | [69b7737f88](https://bsd-hardware.info/?probe=69b7737f88) | Mar 12, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| ASUSTek       | PRIME J3355I-C              | Desktop     | [0b1cea4778](https://bsd-hardware.info/?probe=0b1cea4778) | Mar 12, 2024 |
| Dell          | Latitude E6220              | Notebook    | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Maibenben     | MaiBook X series            | Notebook    | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Dell          | 07F37C A00                  | Desktop     | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | Notebook    | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| Gigabyte      | H81M-D3H                    | Desktop     | [798bfe44fe](https://bsd-hardware.info/?probe=798bfe44fe) | Feb 29, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| Itautec       | Infoway                     | Notebook    | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [ec927cc965](https://bsd-hardware.info/?probe=ec927cc965) | Feb 27, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | Notebook    | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | Notebook    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Desktop     | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Intel         | STK1AW32SC H91596-303       | Desktop     | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| ASUSTek       | K52F                        | Notebook    | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | Notebook    | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | K52F                        | Notebook    | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| ASUSTek       | P5E3 PRO                    | Desktop     | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | Notebook    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [f0db40d2f4](https://bsd-hardware.info/?probe=f0db40d2f4) | Jan 24, 2024 |
| Dell          | Precision M4700             | Notebook    | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude 7480               | Notebook    | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | Notebook    | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [5642aa5018](https://bsd-hardware.info/?probe=5642aa5018) | Jan 16, 2024 |
| HP            | Mini 210-1000               | Notebook    | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [b56a8b041a](https://bsd-hardware.info/?probe=b56a8b041a) | Jan 14, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [514b270501](https://bsd-hardware.info/?probe=514b270501) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [9fed9e1dd9](https://bsd-hardware.info/?probe=9fed9e1dd9) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | Notebook    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4b0c5d65b0](https://bsd-hardware.info/?probe=4b0c5d65b0) | Jan 02, 2024 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| Dell          | Vostro V130                 | Notebook    | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| eMachines     | eM350                       | Notebook    | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| Intel         | NUC11ATBPE M49844-303       | Mini pc     | [1e083d16ac](https://bsd-hardware.info/?probe=1e083d16ac) | Dec 21, 2023 |
| HP            | 212B                        | Desktop     | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| HP            | 212B                        | Desktop     | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| Acer          | V5-131                      | Notebook    | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | Desktop     | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Intel         | H81U                        | Notebook    | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [797f393ce0](https://bsd-hardware.info/?probe=797f393ce0) | Nov 19, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | Desktop     | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| Lenovo        | NOK                         | Desktop     | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | Notebook    | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| HP            | 3031h                       | Desktop     | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Shuttle       | NC10U                       | Desktop     | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | Notebook    | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| ASUSTek       | K73E                        | Notebook    | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | Desktop     | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| HP            | 83F3                        | Desktop     | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | Notebook    | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | Notebook    | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| HP            | 2000                        | Notebook    | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | Pavilion dv3500             | Notebook    | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | Notebook    | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| HP            | 82A5                        | Mini pc     | [4b56141a3b](https://bsd-hardware.info/?probe=4b56141a3b) | Aug 21, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | Notebook    | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| HP            | 82C0                        | Mini pc     | [124e7b14df](https://bsd-hardware.info/?probe=124e7b14df) | Aug 07, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| HP            | 0AACh                       | Desktop     | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| HP            | 82C0                        | Mini pc     | [6fa14d3439](https://bsd-hardware.info/?probe=6fa14d3439) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | Notebook    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | Notebook    | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | Notebook    | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | Notebook    | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | Desktop     | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| Lenovo        | S10-3                       | Notebook    | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | Notebook    | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| HP            | 21D0                        | Desktop     | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | Desktop     | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Fujitsu       | Unknown                     | Notebook    | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | Desktop     | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [05bd720b57](https://bsd-hardware.info/?probe=05bd720b57) | May 26, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | Desktop     | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | Desktop     | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e4e2bba5fb](https://bsd-hardware.info/?probe=e4e2bba5fb) | May 02, 2023 |
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
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/helloSystem_0.8.1/All/Test_Cases.md>).

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 476       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 472       | 99.16%  |
| GNOME        | 2         | 0.42%   |
| KDE5         | 1         | 0.21%   |
| JWM          | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 476       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 476       | 99.79%  |
| SDDM | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 209       | 43.63%  |
| fr_FR   | 101       | 21.09%  |
| ru_RU   | 36        | 7.52%   |
| de_DE   | 29        | 6.05%   |
| Unknown | 24        | 5.01%   |
| es_ES   | 20        | 4.18%   |
| pt_BR   | 13        | 2.71%   |
| it_IT   | 12        | 2.51%   |
| pl_PL   | 11        | 2.3%    |
| zh_CN   | 4         | 0.84%   |
| nl_NL   | 4         | 0.84%   |
| jp_JP   | 3         | 0.63%   |
| ko_KR   | 2         | 0.42%   |
| fi_FI   | 2         | 0.42%   |
| tr_TR   | 1         | 0.21%   |
| pt_PT   | 1         | 0.21%   |
| pt      | 1         | 0.21%   |
| fr      | 1         | 0.21%   |
| fi_DK   | 1         | 0.21%   |
| es      | 1         | 0.21%   |
| en_GB   | 1         | 0.21%   |
| en      | 1         | 0.21%   |
| C       | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 471       | 98.95%  |
| BIOS | 5         | 1.05%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 259       | 53.62%  |
| Zfs    | 224       | 46.38%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 471       | 98.95%  |
| MBR  | 5         | 1.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 101       | 21.22%  |
| ASUSTek Computer                     | 70        | 14.71%  |
| Hewlett-Packard                      | 61        | 12.82%  |
| Dell                                 | 47        | 9.87%   |
| Gigabyte Technology                  | 36        | 7.56%   |
| Acer                                 | 20        | 4.2%    |
| MSI                                  | 16        | 3.36%   |
| Intel                                | 14        | 2.94%   |
| Apple                                | 14        | 2.94%   |
| Samsung Electronics                  | 11        | 2.31%   |
| Fujitsu                              | 10        | 2.1%    |
| ASRock                               | 10        | 2.1%    |
| Toshiba                              | 9         | 1.89%   |
| Unknown                              | 7         | 1.47%   |
| Sony                                 | 4         | 0.84%   |
| Google                               | 4         | 0.84%   |
| T-bao                                | 2         | 0.42%   |
| Panasonic                            | 2         | 0.42%   |
| Packard Bell                         | 2         | 0.42%   |
| LG Electronics                       | 2         | 0.42%   |
| Fujitsu Siemens                      | 2         | 0.42%   |
| Foxconn                              | 2         | 0.42%   |
| AZW                                  | 2         | 0.42%   |
| TUXEDO                               | 1         | 0.21%   |
| Trigkey                              | 1         | 0.21%   |
| Timi                                 | 1         | 0.21%   |
| Shuttle                              | 1         | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.21%   |
| Plaisio                              | 1         | 0.21%   |
| Pegatron                             | 1         | 0.21%   |
| OEGStone                             | 1         | 0.21%   |
| NVN-ED01                             | 1         | 0.21%   |
| Microsoft                            | 1         | 0.21%   |
| Medion                               | 1         | 0.21%   |
| Maibenben                            | 1         | 0.21%   |
| Itautec                              | 1         | 0.21%   |
| Irbis                                | 1         | 0.21%   |
| IGEL Technology                      | 1         | 0.21%   |
| HUAWEI                               | 1         | 0.21%   |
| Huanan                               | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown                                             | 11        | 2.31%   |
| ASUS All Series                                     | 4         | 0.84%   |
| ASUS PRIME B250M-A                                  | 3         | 0.63%   |
| T-bao MINI PC                                       | 2         | 0.42%   |
| MSI MS-7788                                         | 2         | 0.42%   |
| Intel H81                                           | 2         | 0.42%   |
| HP ProDesk 600 G1 DM                                | 2         | 0.42%   |
| HP Laptop 14-bs0xx                                  | 2         | 0.42%   |
| HP EliteDesk 800 G2 DM 35W                          | 2         | 0.42%   |
| HP Compaq Elite 8300 USDT                           | 2         | 0.42%   |
| Gigabyte B550 GAMING X V2                           | 2         | 0.42%   |
| Dell OptiPlex 780                                   | 2         | 0.42%   |
| Dell OptiPlex 7010                                  | 2         | 0.42%   |
| Dell OptiPlex 3020                                  | 2         | 0.42%   |
| ASUS ROG STRIX B550-F GAMING                        | 2         | 0.42%   |
| Apple MacBookPro9,2                                 | 2         | 0.42%   |
| Apple MacBook5,1                                    | 2         | 0.42%   |
| Apple MacBook4,1                                    | 2         | 0.42%   |
| Acer Spin SP314-21                                  | 2         | 0.42%   |
| TUXEDO Aura 15 Gen1                                 | 1         | 0.21%   |
| Trigkey S5                                          | 1         | 0.21%   |
| Toshiba Satellite P300                              | 1         | 0.21%   |
| Toshiba Satellite L675D                             | 1         | 0.21%   |
| Toshiba Satellite L50-B                             | 1         | 0.21%   |
| Toshiba Satellite L40                               | 1         | 0.21%   |
| Toshiba Satellite C845                              | 1         | 0.21%   |
| Toshiba Satellite A200                              | 1         | 0.21%   |
| Toshiba QOSMIO X775                                 | 1         | 0.21%   |
| Toshiba PORTEGE R700                                | 1         | 0.21%   |
| Timi TM1701                                         | 1         | 0.21%   |
| Sony VPCEG15FB                                      | 1         | 0.21%   |
| Sony VGN-FZ19VN                                     | 1         | 0.21%   |
| Sony SVL2412Z1EB                                    | 1         | 0.21%   |
| Sony SVF14A15CBB                                    | 1         | 0.21%   |
| Shuttle NC10U                                       | 1         | 0.21%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 1         | 0.21%   |
| Samsung RC530/RC730                                 | 1         | 0.21%   |
| Samsung R530/R730/R540                              | 1         | 0.21%   |
| Samsung R520/R522/R620                              | 1         | 0.21%   |
| Samsung R510/P510                                   | 1         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 58        | 12.18%  |
| Dell Latitude           | 15        | 3.15%   |
| ASUS PRIME              | 15        | 3.15%   |
| Lenovo IdeaPad          | 14        | 2.94%   |
| Lenovo ThinkCentre      | 12        | 2.52%   |
| Dell OptiPlex           | 12        | 2.52%   |
| HP Pavilion             | 11        | 2.31%   |
| HP Compaq               | 11        | 2.31%   |
| Dell Inspiron           | 11        | 2.31%   |
| Unknown                 | 11        | 2.31%   |
| Acer Aspire             | 10        | 2.1%    |
| ASUS ROG                | 8         | 1.68%   |
| HP Laptop               | 7         | 1.47%   |
| Toshiba Satellite       | 6         | 1.26%   |
| HP ProDesk              | 6         | 1.26%   |
| HP EliteDesk            | 5         | 1.05%   |
| HP EliteBook            | 4         | 0.84%   |
| Gigabyte B450M          | 4         | 0.84%   |
| Dell Precision          | 4         | 0.84%   |
| ASUS VivoBook           | 4         | 0.84%   |
| ASUS All                | 4         | 0.84%   |
| Gigabyte B550           | 3         | 0.63%   |
| Fujitsu LIFEBOOK        | 3         | 0.63%   |
| Dell Vostro             | 3         | 0.63%   |
| ASUS TUF                | 3         | 0.63%   |
| Apple MacBook5          | 3         | 0.63%   |
| T-bao MINI              | 2         | 0.42%   |
| MSI MS-7788             | 2         | 0.42%   |
| Lenovo Yoga             | 2         | 0.42%   |
| Lenovo Legion           | 2         | 0.42%   |
| Intel H81               | 2         | 0.42%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.42%   |
| Fujitsu ESPRIMO         | 2         | 0.42%   |
| Apple MacBookPro9       | 2         | 0.42%   |
| Apple MacBook4          | 2         | 0.42%   |
| Acer Veriton            | 2         | 0.42%   |
| Acer TravelMate         | 2         | 0.42%   |
| Acer Spin               | 2         | 0.42%   |
| TUXEDO Aura             | 1         | 0.21%   |
| Trigkey S5              | 1         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 41        | 8.61%   |
| 2012    | 40        | 8.4%    |
| 2022    | 38        | 7.98%   |
| 2011    | 38        | 7.98%   |
| 2013    | 37        | 7.77%   |
| 2021    | 34        | 7.14%   |
| 2019    | 32        | 6.72%   |
| 2010    | 30        | 6.3%    |
| 2017    | 27        | 5.67%   |
| 2018    | 26        | 5.46%   |
| 2016    | 23        | 4.83%   |
| 2014    | 23        | 4.83%   |
| 2009    | 21        | 4.41%   |
| 2015    | 19        | 3.99%   |
| 2008    | 19        | 3.99%   |
| 2023    | 14        | 2.94%   |
| 2007    | 8         | 1.68%   |
| 2006    | 4         | 0.84%   |
| 2024    | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 243       | 51.05%  |
| Desktop     | 212       | 44.54%  |
| Mini pc     | 9         | 1.89%   |
| Convertible | 7         | 1.47%   |
| All in one  | 3         | 0.63%   |
| Tablet      | 1         | 0.21%   |
| Server      | 1         | 0.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 470       | 98.74%  |
| Yes  | 6         | 1.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 170       | 35.71%  |
| 4.01-8.0    | 116       | 24.37%  |
| 16.01-24.0  | 113       | 23.74%  |
| 32.01-64.0  | 32        | 6.72%   |
| 2.01-3.0    | 24        | 5.04%   |
| 3.01-4.0    | 9         | 1.89%   |
| 64.01-256.0 | 8         | 1.68%   |
| 24.01-32.0  | 3         | 0.63%   |
| 0.51-1.0    | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 262       | 54.81%  |
| 0.51-1.0  | 148       | 30.96%  |
| 1.01-2.0  | 47        | 9.83%   |
| 2.01-3.0  | 16        | 3.35%   |
| 4.01-8.0  | 2         | 0.42%   |
| 3.01-4.0  | 2         | 0.42%   |
| 8.01-16.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 295       | 61.72%  |
| 2      | 88        | 18.41%  |
| 0      | 39        | 8.16%   |
| 3      | 33        | 6.9%    |
| 5      | 10        | 2.09%   |
| 4      | 7         | 1.46%   |
| 9      | 2         | 0.42%   |
| 6      | 2         | 0.42%   |
| 13     | 1         | 0.21%   |
| 7      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 309       | 64.92%  |
| Yes       | 167       | 35.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 434       | 91.18%  |
| No        | 42        | 8.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 320       | 67.09%  |
| No        | 157       | 32.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 51.05%  |
| No        | 233       | 48.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 73        | 15.34%  |
| Russia             | 53        | 11.13%  |
| Germany            | 34        | 7.14%   |
| Brazil             | 27        | 5.67%   |
| Poland             | 24        | 5.04%   |
| Spain              | 21        | 4.41%   |
| France             | 19        | 3.99%   |
| Italy              | 18        | 3.78%   |
| UK                 | 15        | 3.15%   |
| Canada             | 13        | 2.73%   |
| Hungary            | 11        | 2.31%   |
| Indonesia          | 10        | 2.1%    |
| Romania            | 9         | 1.89%   |
| India              | 9         | 1.89%   |
| China              | 9         | 1.89%   |
| Australia          | 9         | 1.89%   |
| Turkey             | 8         | 1.68%   |
| Netherlands        | 8         | 1.68%   |
| Serbia             | 7         | 1.47%   |
| Belgium            | 7         | 1.47%   |
| Mexico             | 6         | 1.26%   |
| Ukraine            | 5         | 1.05%   |
| Bulgaria           | 5         | 1.05%   |
| Switzerland        | 4         | 0.84%   |
| South Korea        | 4         | 0.84%   |
| Portugal           | 4         | 0.84%   |
| Finland            | 4         | 0.84%   |
| Argentina          | 4         | 0.84%   |
| Sweden             | 3         | 0.63%   |
| Peru               | 3         | 0.63%   |
| Lithuania          | 3         | 0.63%   |
| Japan              | 3         | 0.63%   |
| Israel             | 3         | 0.63%   |
| Estonia            | 3         | 0.63%   |
| Slovenia           | 2         | 0.42%   |
| Kazakhstan         | 2         | 0.42%   |
| Ireland            | 2         | 0.42%   |
| Dominican Republic | 2         | 0.42%   |
| Czechia            | 2         | 0.42%   |
| Cyprus             | 2         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| St Petersburg      | 10        | 2.07%   |
| Berlin             | 8         | 1.66%   |
| Moscow             | 7         | 1.45%   |
| Sao Paulo          | 6         | 1.24%   |
| Wroclaw            | 4         | 0.83%   |
| Sydney             | 4         | 0.83%   |
| St. Jean Baptiste  | 4         | 0.83%   |
| Madrid             | 4         | 0.83%   |
| Budapest           | 4         | 0.83%   |
| Warsaw             | 3         | 0.62%   |
| Sofia              | 3         | 0.62%   |
| Paris              | 3         | 0.62%   |
| Newburgh           | 3         | 0.62%   |
| Milan              | 3         | 0.62%   |
| Brooklyn           | 3         | 0.62%   |
| Belgrade           | 3         | 0.62%   |
| Ankara             | 3         | 0.62%   |
| Zurich             | 2         | 0.41%   |
| Woodbridge         | 2         | 0.41%   |
| Vilnius            | 2         | 0.41%   |
| Valga              | 2         | 0.41%   |
| Valencia           | 2         | 0.41%   |
| Stuttgart          | 2         | 0.41%   |
| St Albans          | 2         | 0.41%   |
| Shenzhen           | 2         | 0.41%   |
| Santo Domingo Este | 2         | 0.41%   |
| Santiago           | 2         | 0.41%   |
| Peterborough       | 2         | 0.41%   |
| Perm               | 2         | 0.41%   |
| Penza              | 2         | 0.41%   |
| Pensacola          | 2         | 0.41%   |
| Odesa              | 2         | 0.41%   |
| Novosibirsk        | 2         | 0.41%   |
| New York           | 2         | 0.41%   |
| Montreal           | 2         | 0.41%   |
| Melbourne          | 2         | 0.41%   |
| Lisbon             | 2         | 0.41%   |
| Krasnodar          | 2         | 0.41%   |
| Krakow             | 2         | 0.41%   |
| Kochi              | 2         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 93        | 117    | 15%     |
| WDC                 | 84        | 122    | 13.55%  |
| Seagate             | 79        | 108    | 12.74%  |
| Kingston            | 53        | 54     | 8.55%   |
| Toshiba             | 41        | 49     | 6.61%   |
| SanDisk             | 29        | 29     | 4.68%   |
| Crucial             | 25        | 29     | 4.03%   |
| Hitachi             | 23        | 24     | 3.71%   |
| A-DATA Technology   | 19        | 20     | 3.06%   |
| Intel               | 12        | 12     | 1.94%   |
| Micron Technology   | 10        | 11     | 1.61%   |
| HGST                | 10        | 13     | 1.61%   |
| China               | 10        | 11     | 1.61%   |
| Transcend           | 9         | 9      | 1.45%   |
| SK hynix            | 9         | 9      | 1.45%   |
| Patriot             | 7         | 7      | 1.13%   |
| SPCC                | 6         | 6      | 0.97%   |
| Maxtor              | 5         | 5      | 0.81%   |
| KingSpec            | 5         | 5      | 0.81%   |
| GOODRAM             | 5         | 5      | 0.81%   |
| Gigabyte Technology | 5         | 6      | 0.81%   |
| Apple               | 5         | 5      | 0.81%   |
| PNY                 | 4         | 4      | 0.65%   |
| Team                | 3         | 3      | 0.48%   |
| Silicon Motion      | 3         | 3      | 0.48%   |
| OCZ                 | 3         | 3      | 0.48%   |
| Netac               | 3         | 3      | 0.48%   |
| Intenso             | 3         | 3      | 0.48%   |
| Fujitsu             | 3         | 3      | 0.48%   |
| Apacer              | 3         | 3      | 0.48%   |
| AMD                 | 3         | 3      | 0.48%   |
| Vaseky              | 2         | 2      | 0.32%   |
| Lexar               | 2         | 2      | 0.32%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.32%   |
| KIOXIA              | 2         | 2      | 0.32%   |
| Dogfish             | 2         | 2      | 0.32%   |
| BHT                 | 2         | 2      | 0.32%   |
| XPG                 | 1         | 1      | 0.16%   |
| WALRAM              | 1         | 1      | 0.16%   |
| Verbatim            | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 15        | 2.19%   |
| Samsung SSD 860 EVO 500GB            | 9         | 1.31%   |
| Seagate ST500DM002-1BD142 500GB      | 6         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 0.88%   |
| Seagate ST3500418AS 500GB            | 5         | 0.73%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.73%   |
| Kingston SA400S37120G 120GB          | 5         | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB         | 4         | 0.58%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.58%   |
| Samsung SSD 980 1TB                  | 4         | 0.58%   |
| Samsung SSD 870 EVO 500GB            | 4         | 0.58%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.58%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.58%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.58%   |
| A-DATA SU650 120GB                   | 4         | 0.58%   |
| WDC WDS500G2B0A-00SM50 500GB         | 3         | 0.44%   |
| WDC WDS120G2G0A-00JH30 120GB         | 3         | 0.44%   |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 0.44%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.44%   |
| Toshiba HDWD110 1TB                  | 3         | 0.44%   |
| SPCC Solid State Disk 128GB          | 3         | 0.44%   |
| Seagate ST9500325AS 500GB            | 3         | 0.44%   |
| Seagate ST9250410AS 250GB            | 3         | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.44%   |
| SanDisk SSD PLUS 120GB               | 3         | 0.44%   |
| Samsung SSD 980 500GB                | 3         | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.44%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.44%   |
| Kingston SHFS37A240G 240GB           | 3         | 0.44%   |
| HGST HTS725050A7E630 500GB           | 3         | 0.44%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.29%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 2         | 0.29%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2         | 0.29%   |
| WDC WD10EZEX-60WN4A1 1TB             | 2         | 0.29%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB | 2         | 0.29%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.29%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 107    | 33.05%  |
| WDC                 | 64        | 95     | 27.12%  |
| Toshiba             | 36        | 42     | 15.25%  |
| Hitachi             | 23        | 24     | 9.75%   |
| Samsung Electronics | 13        | 16     | 5.51%   |
| HGST                | 10        | 13     | 4.24%   |
| Maxtor              | 5         | 5      | 2.12%   |
| Fujitsu             | 3         | 3      | 1.27%   |
| Apple               | 3         | 3      | 1.27%   |
| QUANTUM             | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 53     | 16.01%  |
| Kingston            | 42        | 43     | 14.95%  |
| SanDisk             | 29        | 29     | 10.32%  |
| Crucial             | 21        | 24     | 7.47%   |
| WDC                 | 16        | 17     | 5.69%   |
| A-DATA Technology   | 13        | 13     | 4.63%   |
| China               | 10        | 11     | 3.56%   |
| Intel               | 8         | 8      | 2.85%   |
| Transcend           | 7         | 7      | 2.49%   |
| Patriot             | 6         | 6      | 2.14%   |
| SPCC                | 5         | 5      | 1.78%   |
| Micron Technology   | 5         | 5      | 1.78%   |
| KingSpec            | 5         | 5      | 1.78%   |
| GOODRAM             | 5         | 5      | 1.78%   |
| Toshiba             | 4         | 6      | 1.42%   |
| PNY                 | 4         | 4      | 1.42%   |
| Gigabyte Technology | 4         | 5      | 1.42%   |
| OCZ                 | 3         | 3      | 1.07%   |
| Intenso             | 3         | 3      | 1.07%   |
| Apacer              | 3         | 3      | 1.07%   |
| Vaseky              | 2         | 2      | 0.71%   |
| Team                | 2         | 2      | 0.71%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.71%   |
| Dogfish             | 2         | 2      | 0.71%   |
| BHT                 | 2         | 2      | 0.71%   |
| Apple               | 2         | 2      | 0.71%   |
| WALRAM              | 1         | 1      | 0.36%   |
| Verbatim            | 1         | 1      | 0.36%   |
| V-GeN               | 1         | 1      | 0.36%   |
| TAMMUZ              | 1         | 1      | 0.36%   |
| SUNEAST             | 1         | 1      | 0.36%   |
| SSSTC               | 1         | 1      | 0.36%   |
| SK hynix            | 1         | 1      | 0.36%   |
| SETHRISE            | 1         | 1      | 0.36%   |
| SemsoTai            | 1         | 1      | 0.36%   |
| RX7                 | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| Pioneer             | 1         | 1      | 0.36%   |
| Philips             | 1         | 1      | 0.36%   |
| Palit               | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 240       | 298    | 42.93%  |
| HDD  | 210       | 309    | 37.57%  |
| NVMe | 109       | 125    | 19.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 387       | 607    | 78.02%  |
| NVMe | 109       | 125    | 21.98%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 334       | 432    | 73.89%  |
| 0.51-1.0   | 79        | 98     | 17.48%  |
| 1.01-2.0   | 23        | 45     | 5.09%   |
| 3.01-4.0   | 8         | 12     | 1.77%   |
| 2.01-3.0   | 4         | 7      | 0.88%   |
| 4.01-10.0  | 3         | 12     | 0.66%   |
| 10.01-20.0 | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 242       | 50%     |
| 101-250    | 77        | 15.91%  |
| 251-500    | 64        | 13.22%  |
| 51-100     | 60        | 12.4%   |
| 501-1000   | 23        | 4.75%   |
| 21-50      | 14        | 2.89%   |
| Unknown    | 3         | 0.62%   |
| 1001-2000  | 1         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 466       | 97.9%   |
| 21-50   | 3         | 0.63%   |
| 101-250 | 3         | 0.63%   |
| Unknown | 3         | 0.63%   |
| 251-500 | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 3         | 3      | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 4      | 2.7%    |
| Seagate ST500LM000-1EJ162 500GB    | 2         | 2      | 1.8%    |
| Seagate ST3500418AS 500GB          | 2         | 2      | 1.8%    |
| Hitachi HTS542525K9A300 250GB      | 2         | 2      | 1.8%    |
| HGST HTS725050A7E630 500GB         | 2         | 2      | 1.8%    |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 1      | 0.9%    |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 0.9%    |
| WDC WD6400BPVT-22HXZT3 640GB       | 1         | 1      | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 0.9%    |
| WDC WD5000AAKX-08U6AA0 500GB       | 1         | 1      | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 0.9%    |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.9%    |
| WDC WD30PURZ-85AKKY0 3TB           | 1         | 1      | 0.9%    |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 1      | 0.9%    |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 0.9%    |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 1      | 0.9%    |
| WDC WD20EARS-00MVWB0 2TB           | 1         | 1      | 0.9%    |
| WDC WD20EADS-00W4B0 2TB            | 1         | 1      | 0.9%    |
| WDC WD1600YS-01SHB1 164GB          | 1         | 1      | 0.9%    |
| WDC WD1600AAJS-60Z0A0 160GB        | 1         | 1      | 0.9%    |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.9%    |
| WDC WD10EZEX-60WN4A0 1TB           | 1         | 1      | 0.9%    |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1      | 0.9%    |
| WDC WD10EARS-00MVWB0 1TB           | 1         | 1      | 0.9%    |
| WDC WD10EARS-003BB1 1TB            | 1         | 1      | 0.9%    |
| WDC WD10EADS-11M2B2 1TB            | 1         | 1      | 0.9%    |
| Transcend TS120GSSD220S 120GB      | 1         | 1      | 0.9%    |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 0.9%    |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 0.9%    |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 0.9%    |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 0.9%    |
| Toshiba MK8052GSX 80GB             | 1         | 1      | 0.9%    |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 0.9%    |
| Toshiba MK5059GSXP 500GB           | 1         | 1      | 0.9%    |
| Toshiba MK3261GSY 320GB            | 1         | 1      | 0.9%    |
| Toshiba MK3259GSXP 320GB           | 1         | 1      | 0.9%    |
| Toshiba MK1646GSX 160GB            | 1         | 1      | 0.9%    |
| Toshiba MK1229GSG 120GB            | 1         | 1      | 0.9%    |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 0.9%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 32     | 25.23%  |
| WDC                 | 20        | 21     | 18.69%  |
| Toshiba             | 13        | 13     | 12.15%  |
| Hitachi             | 13        | 13     | 12.15%  |
| Samsung Electronics | 7         | 8      | 6.54%   |
| HGST                | 6         | 7      | 5.61%   |
| Crucial             | 4         | 5      | 3.74%   |
| Maxtor              | 3         | 3      | 2.8%    |
| SK hynix            | 2         | 2      | 1.87%   |
| Kingston            | 2         | 2      | 1.87%   |
| Intel               | 2         | 2      | 1.87%   |
| Transcend           | 1         | 1      | 0.93%   |
| SSSTC               | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| OCZ                 | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 32     | 31.4%   |
| WDC                 | 19        | 20     | 22.09%  |
| Toshiba             | 13        | 13     | 15.12%  |
| Hitachi             | 13        | 13     | 15.12%  |
| HGST                | 6         | 7      | 6.98%   |
| Samsung Electronics | 5         | 6      | 5.81%   |
| Maxtor              | 3         | 3      | 3.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 84        | 94     | 80%     |
| SSD  | 17        | 18     | 16.19%  |
| NVMe | 4         | 4      | 3.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 16.67%  |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 16.67%  |
| SanDisk pSSD 16GB                 | 1         | 1      | 16.67%  |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 16.67%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 16.67%  |
| Hitachi HDS721032CLA362 320GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 33.33%  |
| Samsung Electronics | 2         | 2      | 33.33%  |
| SanDisk             | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 360       | 593    | 74.84%  |
| Malfunc  | 104       | 116    | 21.62%  |
| Detected | 11        | 17     | 2.29%   |
| Failed   | 6         | 6      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 362       | 62.09%  |
| AMD                                     | 70        | 12.01%  |
| Samsung Electronics                     | 40        | 6.86%   |
| Sandisk                                 | 15        | 2.57%   |
| Silicon Motion                          | 12        | 2.06%   |
| Nvidia                                  | 12        | 2.06%   |
| Kingston Technology Company             | 11        | 1.89%   |
| ASMedia Technology                      | 9         | 1.54%   |
| SK hynix                                | 8         | 1.37%   |
| Marvell Technology Group                | 7         | 1.2%    |
| Micron/Crucial Technology               | 5         | 0.86%   |
| Micron Technology                       | 5         | 0.86%   |
| JMicron Technology                      | 5         | 0.86%   |
| ADATA Technology                        | 4         | 0.69%   |
| Phison Electronics                      | 3         | 0.51%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.51%   |
| VIA Technologies                        | 2         | 0.34%   |
| Realtek Semiconductor                   | 2         | 0.34%   |
| KIOXIA                                  | 2         | 0.34%   |
| Toshiba                                 | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.17%   |
| Shenzhen Unionmemory Information System | 1         | 0.17%   |
| Seagate Technology                      | 1         | 0.17%   |
| OCZ Technology Group                    | 1         | 0.17%   |
| Broadcom / LSI                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40        | 5.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 34        | 5.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32        | 4.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 24        | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 21        | 3.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 2.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 17        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 15        | 2.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 15        | 2.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 2.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 12        | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11        | 1.64%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.64%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 10        | 1.49%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 10        | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 9         | 1.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 1.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 8         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.04%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.9%    |
| Intel SATA Controller [RAID mode]                                                       | 6         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 0.9%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 6         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 0.75%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 383       | 65.69%  |
| NVMe | 107       | 18.35%  |
| IDE  | 70        | 12.01%  |
| RAID | 21        | 3.6%    |
| SAS  | 1         | 0.17%   |
| SCSI | 1         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 393       | 82.56%  |
| AMD    | 83        | 17.44%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 7         | 1.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 1.47%   |
| Intel CPU Version                           | 6         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.05%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 5         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4         | 0.84%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 4         | 0.84%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4         | 0.84%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 4         | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 0.84%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4         | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 0.84%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4         | 0.84%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 3         | 0.63%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 3         | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3         | 0.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.63%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.63%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3         | 0.63%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3         | 0.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3         | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.63%   |
| Intel Core 2 Duo                            | 3         | 0.63%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 3         | 0.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.63%   |
| Intel Atom CPU N450 @ 1.66GHz               | 3         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 0.63%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 2         | 0.42%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.42%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 119       | 25%     |
| Intel Core i7           | 68        | 14.29%  |
| Intel Core i3           | 49        | 10.29%  |
| Intel Celeron           | 41        | 8.61%   |
| Intel Core 2 Duo        | 33        | 6.93%   |
| Other                   | 24        | 5.04%   |
| AMD Ryzen 5             | 22        | 4.62%   |
| AMD Ryzen 7             | 17        | 3.57%   |
| Intel Pentium           | 14        | 2.94%   |
| Intel Xeon              | 13        | 2.73%   |
| AMD Ryzen 3             | 9         | 1.89%   |
| Intel Atom              | 8         | 1.68%   |
| Intel Pentium Dual-Core | 5         | 1.05%   |
| AMD Athlon II X2        | 4         | 0.84%   |
| Intel Pentium Silver    | 3         | 0.63%   |
| Intel Genuine           | 3         | 0.63%   |
| Intel Core 2 Quad       | 3         | 0.63%   |
| Intel Core 2            | 3         | 0.63%   |
| AMD Phenom II X4        | 3         | 0.63%   |
| AMD A4                  | 3         | 0.63%   |
| Intel Pentium Gold      | 2         | 0.42%   |
| Intel Pentium Dual      | 2         | 0.42%   |
| Intel Core i9           | 2         | 0.42%   |
| AMD E                   | 2         | 0.42%   |
| AMD Athlon              | 2         | 0.42%   |
| AMD A6                  | 2         | 0.42%   |
| AMD A10                 | 2         | 0.42%   |
| Intel Pentium 4         | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| Intel Celeron D         | 1         | 0.21%   |
| AMD Ryzen Embedded      | 1         | 0.21%   |
| AMD Ryzen 9             | 1         | 0.21%   |
| AMD Ryzen 3 PRO         | 1         | 0.21%   |
| AMD PRO A10             | 1         | 0.21%   |
| AMD Phenom II X6        | 1         | 0.21%   |
| AMD Phenom II X2        | 1         | 0.21%   |
| AMD Phenom II           | 1         | 0.21%   |
| AMD GX                  | 1         | 0.21%   |
| AMD FX                  | 1         | 0.21%   |
| AMD E2                  | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 204       | 42.86%  |
| 4       | 156       | 32.77%  |
| Unknown | 37        | 7.77%   |
| 6       | 22        | 4.62%   |
| 12      | 17        | 3.57%   |
| 8       | 15        | 3.15%   |
| 16      | 14        | 2.94%   |
| 1       | 8         | 1.68%   |
| 24      | 1         | 0.21%   |
| 14      | 1         | 0.21%   |
| 10      | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 465       | 97.69%  |
| 2       | 10        | 2.1%    |
| Unknown | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 225       | 47.27%  |
| 1       | 210       | 44.12%  |
| Unknown | 41        | 8.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 64        | 13.45%  |
| Haswell       | 51        | 10.71%  |
| IvyBridge     | 49        | 10.29%  |
| SandyBridge   | 43        | 9.03%   |
| Penryn        | 35        | 7.35%   |
| Skylake       | 31        | 6.51%   |
| Core          | 23        | 4.83%   |
| Zen+          | 18        | 3.78%   |
| Zen 3         | 18        | 3.78%   |
| Westmere      | 17        | 3.57%   |
| Silvermont    | 17        | 3.57%   |
| Unknown       | 17        | 3.57%   |
| K10           | 12        | 2.52%   |
| Broadwell     | 11        | 2.31%   |
| Zen           | 8         | 1.68%   |
| Bonnell       | 8         | 1.68%   |
| Goldmont plus | 7         | 1.47%   |
| CometLake     | 7         | 1.47%   |
| TigerLake     | 6         | 1.26%   |
| Zen 2         | 5         | 1.05%   |
| Piledriver    | 5         | 1.05%   |
| Nehalem       | 5         | 1.05%   |
| Excavator     | 5         | 1.05%   |
| Goldmont      | 4         | 0.84%   |
| Bobcat        | 4         | 0.84%   |
| NetBurst      | 1         | 0.21%   |
| K8 Hammer     | 1         | 0.21%   |
| K10 Llano     | 1         | 0.21%   |
| Jaguar        | 1         | 0.21%   |
| IceLake       | 1         | 0.21%   |
| Bulldozer     | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 310       | 58.05%  |
| Nvidia                           | 113       | 21.16%  |
| AMD                              | 109       | 20.41%  |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Matrox Electronics Systems       | 1         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 6.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 5.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 2.9%    |
| Intel HD Graphics 630                                                                    | 14        | 2.54%   |
| Intel HD Graphics 530                                                                    | 14        | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 2.36%   |
| Intel UHD Graphics 620                                                                   | 12        | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 2.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 2%      |
| Intel HD Graphics 5500                                                                   | 10        | 1.81%   |
| Intel HD Graphics 620                                                                    | 9         | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.73%   |
| Intel HD Graphics 500                                                                    | 4         | 0.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.73%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.54%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 220       | 46.03%  |
| 1 x AMD                  | 86        | 17.99%  |
| 1 x Nvidia               | 71        | 14.85%  |
| 2 x Intel                | 37        | 7.74%   |
| Intel + Nvidia           | 36        | 7.53%   |
| Intel + AMD              | 17        | 3.56%   |
| AMD + Nvidia             | 4         | 0.84%   |
| 2 x AMD                  | 2         | 0.42%   |
| Other                    | 1         | 0.21%   |
| 2 x Nvidia               | 1         | 0.21%   |
| 1 x SiS                  | 1         | 0.21%   |
| 1 x Matrox               | 1         | 0.21%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 405       | 84.91%  |
| Proprietary | 55        | 11.53%  |
| Unknown     | 17        | 3.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 375       | 78.29%  |
| 0.01-0.5   | 24        | 5.01%   |
| 1.01-2.0   | 21        | 4.38%   |
| 3.01-4.0   | 19        | 3.97%   |
| 0.51-1.0   | 19        | 3.97%   |
| 7.01-8.0   | 8         | 1.67%   |
| 5.01-6.0   | 8         | 1.67%   |
| 2.01-3.0   | 3         | 0.63%   |
| 8.01-16.0  | 2         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 13.88%  |
| Samsung Electronics     | 29        | 11.84%  |
| LG Display              | 22        | 8.98%   |
| Acer                    | 16        | 6.53%   |
| Chimei Innolux          | 14        | 5.71%   |
| BOE                     | 14        | 5.71%   |
| Goldstar                | 13        | 5.31%   |
| Dell                    | 13        | 5.31%   |
| Lenovo                  | 9         | 3.67%   |
| Hewlett-Packard         | 9         | 3.67%   |
| BenQ                    | 9         | 3.67%   |
| Ancor Communications    | 7         | 2.86%   |
| Apple                   | 6         | 2.45%   |
| AOC                     | 5         | 2.04%   |
| Philips                 | 4         | 1.63%   |
| InfoVision              | 4         | 1.63%   |
| Chi Mei Optoelectronics | 4         | 1.63%   |
| Unknown                 | 3         | 1.22%   |
| Sharp                   | 2         | 0.82%   |
| ONN                     | 2         | 0.82%   |
| LG Electronics          | 2         | 0.82%   |
| ASUSTek Computer        | 2         | 0.82%   |
| Vizio                   | 1         | 0.41%   |
| ViewSonic               | 1         | 0.41%   |
| Toshiba                 | 1         | 0.41%   |
| Semp Toshiba            | 1         | 0.41%   |
| Quanta Display          | 1         | 0.41%   |
| PKB                     | 1         | 0.41%   |
| PANDA                   | 1         | 0.41%   |
| NEC Computers           | 1         | 0.41%   |
| MStar                   | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| Microstep               | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| JXC                     | 1         | 0.41%   |
| ITE                     | 1         | 0.41%   |
| Idek Iiyama             | 1         | 0.41%   |
| Fujitsu Siemens         | 1         | 0.41%   |
| Eizo                    | 1         | 0.41%   |
| DENON                   | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch   | 3         | 1.22%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 3         | 1.22%   |
| Unknown                                                                | 3         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 2         | 0.82%   |
| ONN 100002487 ONN0101 1920x1080 520x320mm 24.0-inch                    | 2         | 0.82%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 2         | 0.82%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch               | 2         | 0.82%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch         | 2         | 0.82%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2         | 0.82%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1         | 0.41%   |
| ViewSonic TD2220 VSC052C 1920x1080 480x270mm 21.7-inch                 | 1         | 0.41%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                        | 1         | 0.41%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                | 1         | 0.41%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch   | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch    | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch   | 1         | 0.41%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch    | 1         | 0.41%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch      | 1         | 0.41%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1         | 0.41%   |
| Samsung Electronics S24E450 SAM0C80 1920x1080 520x290mm 23.4-inch      | 1         | 0.41%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.41%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1         | 0.41%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1         | 0.41%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1         | 0.41%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1         | 0.41%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                      | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 43.57%  |
| 1366x768 (WXGA)    | 68        | 28.22%  |
| 2560x1440 (QHD)    | 12        | 4.98%   |
| 1600x900 (HD+)     | 10        | 4.15%   |
| 1280x800 (WXGA)    | 7         | 2.9%    |
| 1280x1024 (SXGA)   | 6         | 2.49%   |
| 3840x2160 (4K)     | 4         | 1.66%   |
| 1680x1050 (WSXGA+) | 4         | 1.66%   |
| 1440x900 (WXGA+)   | 4         | 1.66%   |
| 1024x600           | 4         | 1.66%   |
| 2560x1600          | 3         | 1.24%   |
| 1920x1200 (WUXGA)  | 2         | 0.83%   |
| 1400x1050          | 2         | 0.83%   |
| Unknown            | 2         | 0.83%   |
| 5760x2160          | 1         | 0.41%   |
| 3840x1080          | 1         | 0.41%   |
| 3200x1800 (QHD+)   | 1         | 0.41%   |
| 2736x1824          | 1         | 0.41%   |
| 2560x1080          | 1         | 0.41%   |
| 2240x1400          | 1         | 0.41%   |
| 1920x540           | 1         | 0.41%   |
| 1024x768 (XGA)     | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 18.18%  |
| 13      | 37        | 15.29%  |
| 21      | 25        | 10.33%  |
| 24      | 20        | 8.26%   |
| Unknown | 20        | 8.26%   |
| 27      | 15        | 6.2%    |
| 23      | 11        | 4.55%   |
| 17      | 11        | 4.55%   |
| 12      | 10        | 4.13%   |
| 19      | 9         | 3.72%   |
| 18      | 9         | 3.72%   |
| 14      | 7         | 2.89%   |
| 11      | 7         | 2.89%   |
| 31      | 4         | 1.65%   |
| 20      | 3         | 1.24%   |
| 10      | 3         | 1.24%   |
| 22      | 2         | 0.83%   |
| 52      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 29      | 1         | 0.41%   |
| 9       | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 29.75%  |
| 501-600     | 46        | 19.01%  |
| 401-500     | 44        | 18.18%  |
| 201-300     | 37        | 15.29%  |
| Unknown     | 20        | 8.26%   |
| 351-400     | 15        | 6.2%    |
| 601-700     | 5         | 2.07%   |
| 801-900     | 1         | 0.41%   |
| 701-800     | 1         | 0.41%   |
| 1001-1500   | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 181       | 77.35%  |
| 16/10   | 25        | 10.68%  |
| Unknown | 19        | 8.12%   |
| 5/4     | 3         | 1.28%   |
| 4/3     | 3         | 1.28%   |
| 6/5     | 1         | 0.43%   |
| 3/2     | 1         | 0.43%   |
| 21/9    | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 51        | 21.07%  |
| 91-100         | 35        | 14.46%  |
| 81-90          | 33        | 13.64%  |
| Unknown        | 20        | 8.26%   |
| 301-350        | 15        | 6.2%    |
| 151-200        | 15        | 6.2%    |
| 101-110        | 13        | 5.37%   |
| 61-70          | 10        | 4.13%   |
| 121-130        | 10        | 4.13%   |
| 141-150        | 8         | 3.31%   |
| 71-80          | 7         | 2.89%   |
| 51-60          | 7         | 2.89%   |
| 351-500        | 6         | 2.48%   |
| 251-300        | 5         | 2.07%   |
| 41-50          | 4         | 1.65%   |
| More than 1000 | 1         | 0.41%   |
| 131-140        | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 74        | 30.71%  |
| 51-100        | 74        | 30.71%  |
| 121-160       | 64        | 26.56%  |
| Unknown       | 20        | 8.3%    |
| More than 240 | 3         | 1.24%   |
| 1-50          | 3         | 1.24%   |
| 161-240       | 3         | 1.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 402       | 84.28%  |
| 0     | 57        | 11.95%  |
| 2     | 18        | 3.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 241       | 34.98%  |
| Intel                             | 224       | 32.51%  |
| Qualcomm Atheros                  | 87        | 12.63%  |
| Broadcom                          | 38        | 5.52%   |
| Marvell Technology Group          | 15        | 2.18%   |
| Samsung Electronics               | 11        | 1.6%    |
| TP-Link                           | 7         | 1.02%   |
| Ralink Technology                 | 7         | 1.02%   |
| Ralink                            | 7         | 1.02%   |
| Nvidia                            | 6         | 0.87%   |
| MediaTek                          | 6         | 0.87%   |
| Xiaomi                            | 5         | 0.73%   |
| Sierra Wireless                   | 5         | 0.73%   |
| JMicron Technology                | 4         | 0.58%   |
| Edimax Technology                 | 4         | 0.58%   |
| Qualcomm                          | 3         | 0.44%   |
| Ericsson Business Mobile Networks | 3         | 0.44%   |
| OPPO Electronics                  | 2         | 0.29%   |
| Huawei Technologies               | 2         | 0.29%   |
| D-Link                            | 2         | 0.29%   |
| T & A Mobile Phones               | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.15%   |
| National Semiconductor            | 1         | 0.15%   |
| Google                            | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| BUFFALO                           | 1         | 0.15%   |
| Atheros                           | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |
| Arduino SA                        | 1         | 0.15%   |
| Accton Technology                 | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 177       | 21.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 35        | 4.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 3.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.2%    |
| Intel Wireless 8265 / 8275                                              | 16        | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 1.46%   |
| Intel Wireless 8260                                                     | 11        | 1.34%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.22%   |
| Intel Wireless 3165                                                     | 10        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.1%    |
| Intel Wireless 7265                                                     | 9         | 1.1%    |
| Intel Ethernet Connection (2) I219-LM                                   | 9         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.98%   |
| Intel Wireless 7260                                                     | 8         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 0.98%   |
| Intel Ethernet Controller I225-V                                        | 8         | 0.98%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.85%   |
| Intel 82579V Gigabit Network Connection                                 | 7         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.73%   |
| Nvidia MCP79 Ethernet                                                   | 6         | 0.73%   |
| Intel Ethernet Connection I217-V                                        | 6         | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.73%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                    | 5         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 147       | 42.73%  |
| Qualcomm Atheros      | 71        | 20.64%  |
| Realtek Semiconductor | 54        | 15.7%   |
| Broadcom              | 32        | 9.3%    |
| TP-Link               | 7         | 2.03%   |
| Ralink Technology     | 7         | 2.03%   |
| Ralink                | 7         | 2.03%   |
| MediaTek              | 5         | 1.45%   |
| Edimax Technology     | 4         | 1.16%   |
| Sierra Wireless       | 3         | 0.87%   |
| D-Link                | 2         | 0.58%   |
| D-Link System         | 1         | 0.29%   |
| BUFFALO               | 1         | 0.29%   |
| Atheros               | 1         | 0.29%   |
| ASUSTek Computer      | 1         | 0.29%   |
| Accton Technology     | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 5.16%   |
| Intel Wireless 8265 / 8275                                              | 16        | 4.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 4.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 3.44%   |
| Intel Wireless 8260                                                     | 11        | 3.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 2.87%   |
| Intel Wireless 3165                                                     | 10        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.58%   |
| Intel Wireless 7265                                                     | 9         | 2.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.58%   |
| Intel Wireless 7260                                                     | 8         | 2.29%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.15%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.15%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.15%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 1.15%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.86%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.86%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 214       | 46.93%  |
| Intel                            | 153       | 33.55%  |
| Qualcomm Atheros                 | 25        | 5.48%   |
| Marvell Technology Group         | 15        | 3.29%   |
| Broadcom                         | 12        | 2.63%   |
| Samsung Electronics              | 11        | 2.41%   |
| Nvidia                           | 6         | 1.32%   |
| Xiaomi                           | 5         | 1.1%    |
| JMicron Technology               | 4         | 0.88%   |
| Qualcomm                         | 3         | 0.66%   |
| OPPO Electronics                 | 2         | 0.44%   |
| Huawei Technologies              | 2         | 0.44%   |
| T & A Mobile Phones              | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| National Semiconductor           | 1         | 0.22%   |
| MediaTek                         | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 177       | 38.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 7.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 29        | 6.29%   |
| Intel Ethernet Connection I217-LM                                      | 11        | 2.39%   |
| Intel Ethernet Connection (2) I219-LM                                  | 9         | 1.95%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 1.74%   |
| Intel Ethernet Controller I225-V                                       | 8         | 1.74%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 1.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 1.3%    |
| Nvidia MCP79 Ethernet                                                  | 6         | 1.3%    |
| Intel Ethernet Connection I217-V                                       | 6         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.87%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 3         | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 3         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.65%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.65%   |
| Qualcomm FP3                                                           | 2         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.43%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data         | 2         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 434       | 56.81%  |
| WiFi     | 320       | 41.88%  |
| Unknown  | 8         | 1.05%   |
| Modem    | 2         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 286       | 68.42%  |
| WiFi     | 132       | 31.58%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 262       | 54.93%  |
| 1     | 198       | 41.51%  |
| 0     | 9         | 1.89%   |
| 3     | 8         | 1.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 449       | 93.54%  |
| Yes  | 31        | 6.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 40.49%  |
| Realtek Semiconductor           | 27        | 10.93%  |
| Broadcom                        | 23        | 9.31%   |
| Qualcomm Atheros Communications | 22        | 8.91%   |
| Apple                           | 15        | 6.07%   |
| Cambridge Silicon Radio         | 13        | 5.26%   |
| Foxconn / Hon Hai               | 10        | 4.05%   |
| IMC Networks                    | 9         | 3.64%   |
| ASUSTek Computer                | 7         | 2.83%   |
| Lite-On Technology              | 6         | 2.43%   |
| Hewlett-Packard                 | 4         | 1.62%   |
| Dell                            | 4         | 1.62%   |
| TP-Link                         | 2         | 0.81%   |
| Primax Electronics              | 1         | 0.4%    |
| MediaTek                        | 1         | 0.4%    |
| Fujitsu                         | 1         | 0.4%    |
| Askey Computer                  | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 55        | 22.18%  |
| Intel AX201 Bluetooth                                       | 13        | 5.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 13        | 5.24%   |
| Realtek Bluetooth Adapter                                   | 12        | 4.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 4.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 9         | 3.63%   |
| Intel AX200 Bluetooth                                       | 7         | 2.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 2.42%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 2.02%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 5         | 2.02%   |
| Apple Bluetooth Host Controller                             | 5         | 2.02%   |
| Realtek Bluetooth 4.2 Adapter                               | 4         | 1.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 1.61%   |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.21%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 3         | 1.21%   |
| Intel AX210 Bluetooth                                       | 3         | 1.21%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 1.21%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 1.21%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 1.21%   |
| ASUS BT-270 Bluetooth Adapter                               | 3         | 1.21%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 1.21%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 1.21%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 0.81%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.81%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.81%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 2         | 0.81%   |
| Lite-On Bluetooth USB Module                                | 2         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.81%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 2         | 0.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.81%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 0.81%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 0.81%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.81%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 0.81%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.4%    |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                 | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 374       | 60.23%  |
| AMD                               | 114       | 18.36%  |
| Nvidia                            | 75        | 12.08%  |
| C-Media Electronics               | 18        | 2.9%    |
| Texas Instruments                 | 6         | 0.97%   |
| Creative Labs                     | 4         | 0.64%   |
| Realtek Semiconductor             | 3         | 0.48%   |
| JMTek                             | 2         | 0.32%   |
| Generalplus Technology            | 2         | 0.32%   |
| Unknown                           | 2         | 0.32%   |
| Yamaha                            | 1         | 0.16%   |
| SteelSeries ApS                   | 1         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.16%   |
| Razer USA                         | 1         | 0.16%   |
| Phison Electronics                | 1         | 0.16%   |
| OPPO Electronics                  | 1         | 0.16%   |
| Microsoft                         | 1         | 0.16%   |
| Micro Star International          | 1         | 0.16%   |
| M-Audio                           | 1         | 0.16%   |
| KTMicro                           | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| HECATE G2 GAMING HEADSET          | 1         | 0.16%   |
| Harman                            | 1         | 0.16%   |
| GN Netcom                         | 1         | 0.16%   |
| GEMBIRD                           | 1         | 0.16%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.16%   |
| Edifier Technology                | 1         | 0.16%   |
| Creative Technology               | 1         | 0.16%   |
| Conexant Systems                  | 1         | 0.16%   |
| Cambridge Silicon Radio           | 1         | 0.16%   |
| Apogee Electronics                | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 45        | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 42        | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 34        | 4.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 4.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 33        | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 28        | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 3.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 2.58%   |
| Intel 200 Series PCH HD Audio                                                                     | 18        | 2.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 2.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 2.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 1.9%    |
| Intel 8 Series HD Audio Controller                                                                | 14        | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 1.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 10        | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.22%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.22%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 8         | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 8         | 1.09%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.68%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 109       | 19.78%  |
| SK hynix            | 77        | 13.97%  |
| Kingston            | 62        | 11.25%  |
| Unknown             | 51        | 9.26%   |
| Micron Technology   | 48        | 8.71%   |
| Crucial             | 32        | 5.81%   |
| Corsair             | 28        | 5.08%   |
| Unknown             | 25        | 4.54%   |
| G.Skill             | 15        | 2.72%   |
| A-DATA Technology   | 12        | 2.18%   |
| Nanya Technology    | 11        | 2%      |
| Elpida              | 11        | 2%      |
| Ramaxel Technology  | 9         | 1.63%   |
| Patriot             | 7         | 1.27%   |
| Unknown (ABCD)      | 5         | 0.91%   |
| Transcend           | 5         | 0.91%   |
| Smart               | 5         | 0.91%   |
| Apacer              | 4         | 0.73%   |
| Team                | 3         | 0.54%   |
| SHARETRONIC         | 3         | 0.54%   |
| GOODRAM             | 3         | 0.54%   |
| Multilaser          | 2         | 0.36%   |
| Lexar               | 2         | 0.36%   |
| Kingmax             | 2         | 0.36%   |
| Atermiter           | 2         | 0.36%   |
| ASint Technology    | 2         | 0.36%   |
| Unknown (8A02)      | 1         | 0.18%   |
| Toshiba             | 1         | 0.18%   |
| Teikon              | 1         | 0.18%   |
| Swissbit            | 1         | 0.18%   |
| Silicon Power       | 1         | 0.18%   |
| SemsoTai            | 1         | 0.18%   |
| Qumo                | 1         | 0.18%   |
| Qimonda             | 1         | 0.18%   |
| MemoWise            | 1         | 0.18%   |
| Lenovo              | 1         | 0.18%   |
| Juhor               | 1         | 0.18%   |
| High Bridge         | 1         | 0.18%   |
| Golden Empire       | 1         | 0.18%   |
| Avant               | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 25        | 4.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.19%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 1.02%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.68%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.68%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 4         | 0.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 4         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 3         | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 3         | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s              | 3         | 0.51%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.51%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.34%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 2         | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.34%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 2         | 0.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.34%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.34%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.34%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.34%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 205       | 43.8%   |
| DDR4    | 177       | 37.82%  |
| DDR2    | 42        | 8.97%   |
| Unknown | 24        | 5.13%   |
| LPDDR4  | 7         | 1.5%    |
| SDRAM   | 6         | 1.28%   |
| LPDDR3  | 3         | 0.64%   |
| DDR     | 2         | 0.43%   |
| LPDDR5  | 1         | 0.21%   |
| DDR5    | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 267       | 57.05%  |
| DIMM         | 182       | 38.89%  |
| Row Of Chips | 11        | 2.35%   |
| Chip         | 4         | 0.85%   |
| Unknown      | 4         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 182       | 34.73%  |
| 4096  | 161       | 30.73%  |
| 2048  | 99        | 18.89%  |
| 16384 | 45        | 8.59%   |
| 1024  | 31        | 5.92%   |
| 32768 | 6         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 120       | 24.05%  |
| 1333    | 64        | 12.83%  |
| 3200    | 52        | 10.42%  |
| 2400    | 51        | 10.22%  |
| 2667    | 39        | 7.82%   |
| 2133    | 32        | 6.41%   |
| 667     | 29        | 5.81%   |
| 1067    | 21        | 4.21%   |
| 800     | 21        | 4.21%   |
| 1334    | 14        | 2.81%   |
| Unknown | 13        | 2.61%   |
| 1867    | 7         | 1.4%    |
| 3600    | 6         | 1.2%    |
| 1066    | 6         | 1.2%    |
| 2666    | 4         | 0.8%    |
| 3000    | 3         | 0.6%    |
| 6400    | 2         | 0.4%    |
| 3733    | 2         | 0.4%    |
| 2048    | 2         | 0.4%    |
| 533     | 2         | 0.4%    |
| 400     | 2         | 0.4%    |
| 4400    | 1         | 0.2%    |
| 4000    | 1         | 0.2%    |
| 3333    | 1         | 0.2%    |
| 2933    | 1         | 0.2%    |
| 1866    | 1         | 0.2%    |
| 1639    | 1         | 0.2%    |
| 1200    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 3         | 60%     |
| Hewlett-Packard    | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| HP LaserJet 3390           | 1         | 20%     |
| HP LaserJet 1020           | 1         | 20%     |
| Brother HL-L3270CDW series | 1         | 20%     |
| Brother HL-L2300D series   | 1         | 20%     |
| Brother DCP-J152W          | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 50%     |
| Canon CanoScan LiDE 120  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 24.14%  |
| Bison Electronics                      | 28        | 13.79%  |
| Microdia                               | 17        | 8.37%   |
| IMC Networks                           | 13        | 6.4%    |
| Sunplus Innovation Technology          | 12        | 5.91%   |
| Realtek Semiconductor                  | 9         | 4.43%   |
| Syntek                                 | 8         | 3.94%   |
| Logitech                               | 7         | 3.45%   |
| Silicon Motion                         | 6         | 2.96%   |
| Quanta                                 | 6         | 2.96%   |
| Lite-On Technology                     | 6         | 2.96%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.96%   |
| Apple                                  | 5         | 2.46%   |
| Suyin                                  | 4         | 1.97%   |
| Alcor Micro                            | 4         | 1.97%   |
| Z-Star Microelectronics                | 3         | 1.48%   |
| Lenovo                                 | 3         | 1.48%   |
| ALi                                    | 3         | 1.48%   |
| Supreme Electronics                    | 2         | 0.99%   |
| Importek                               | 2         | 0.99%   |
| Y Media                                | 1         | 0.49%   |
| Trust                                  | 1         | 0.49%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.49%   |
| Luxvisions Innotech Limited            | 1         | 0.49%   |
| Jiangxi Shinetech Optical              | 1         | 0.49%   |
| Intel                                  | 1         | 0.49%   |
| Genesys Logic                          | 1         | 0.49%   |
| GEMBIRD                                | 1         | 0.49%   |
| DigiTech                               | 1         | 0.49%   |
| Cubeternet                             | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 16        | 7.88%   |
| Bison Integrated Camera                                 | 9         | 4.43%   |
| Microdia Integrated_Webcam_HD                           | 8         | 3.94%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 6         | 2.96%   |
| Syntek Lenovo EasyCamera                                | 4         | 1.97%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 1.97%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.97%   |
| Lite-On Integrated Camera                               | 4         | 1.97%   |
| Bison Lenovo EasyCamera                                 | 4         | 1.97%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 3         | 1.48%   |
| Microdia USB 2.0 Camera                                 | 3         | 1.48%   |
| Logitech Webcam C270                                    | 3         | 1.48%   |
| IMC Networks Integrated Webcam                          | 3         | 1.48%   |
| Chicony FJ Camera                                       | 3         | 1.48%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB | 3         | 1.48%   |
| Bison ThinkPad Integrated Camera                        | 3         | 1.48%   |
| Bison SunplusIT Integrated Camera                       | 3         | 1.48%   |
| Syntek Integrated Camera                                | 2         | 0.99%   |
| Sunplus HP TrueVision HD Camera                         | 2         | 0.99%   |
| Realtek USB Camera                                      | 2         | 0.99%   |
| Logitech BRIO Ultra HD Webcam                           | 2         | 0.99%   |
| Lenovo Integrated Webcam                                | 2         | 0.99%   |
| IMC Networks UVC VGA Webcam                             | 2         | 0.99%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 0.99%   |
| IMC Networks Integrated Camera                          | 2         | 0.99%   |
| IMC Networks EasyCamera                                 | 2         | 0.99%   |
| Chicony USB2.0 HD UVC WebCam                            | 2         | 0.99%   |
| Chicony USB 2.0 Camera                                  | 2         | 0.99%   |
| Chicony Integrated Camera [ThinkPad]                    | 2         | 0.99%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 0.99%   |
| Bison Lenovo Integrated Webcam                          | 2         | 0.99%   |
| Bison HP Webcam-101                                     | 2         | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 0.99%   |
| Apple FaceTime HD Camera                                | 2         | 0.99%   |
| ALi WebCam                                              | 2         | 0.99%   |
| Alcor Micro USB 2.0 Camera                              | 2         | 0.99%   |
| Z-Star Webcam                                           | 1         | 0.49%   |
| Z-Star Vega USB 2.0 Camera                              | 1         | 0.49%   |
| Z-Star Namuga 1.3M Webcam                               | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 46.88%  |
| Upek                       | 4         | 12.5%   |
| Elan Microelectronics      | 4         | 12.5%   |
| AuthenTec                  | 4         | 12.5%   |
| STMicroelectronics         | 1         | 3.13%   |
| Shenzhen Goodix Technology | 1         | 3.13%   |
| LighTuning Technology      | 1         | 3.13%   |
| FocalTech Systems          | 1         | 3.13%   |
| Fingerprint Cards          | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                      | 5         | 15.63%  |
| Validity Sensors Synaptics WBDI                                                   | 4         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 4         | 12.5%   |
| Elan Fingerprint Sensor                                                           | 3         | 9.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 2         | 6.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 1         | 3.13%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 1         | 3.13%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 3.13%   |
| STMicroelectronics Fingerprint Reader                                             | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 1         | 3.13%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 3.13%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 3.13%   |
| Elan WBF Fingerprint Sensor                                                       | 1         | 3.13%   |
| AuthenTec AES2810                                                                 | 1         | 3.13%   |
| AuthenTec AES2660                                                                 | 1         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 1         | 3.13%   |
| AuthenTec AES1660                                                                 | 1         | 3.13%   |

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
| 1     | 229       | 47.91%  |
| 0     | 111       | 23.22%  |
| 2     | 103       | 21.55%  |
| 3     | 28        | 5.86%   |
| 4     | 6         | 1.26%   |
| 5     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 306       | 60.59%  |
| Net/wireless             | 71        | 14.06%  |
| Card reader              | 34        | 6.73%   |
| Fingerprint reader       | 32        | 6.34%   |
| Bluetooth                | 29        | 5.74%   |
| Sound                    | 18        | 3.56%   |
| Storage                  | 6         | 1.19%   |
| Net/ethernet             | 4         | 0.79%   |
| Network                  | 3         | 0.59%   |
| Storage/raid             | 1         | 0.2%    |
| Dvb card                 | 1         | 0.2%    |

