FreeBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for FreeBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD/Desktop/README.md) and [notebooks](/Dist/FreeBSD/Notebook/README.md).

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

Total: 4126

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E6430              | Notebook    | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| HP            | 83E9                        | Desktop     | [f5a6f9001d](https://bsd-hardware.info/?probe=f5a6f9001d) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [fb1f5f8545](https://bsd-hardware.info/?probe=fb1f5f8545) | Feb 16, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [cc65de13e8](https://bsd-hardware.info/?probe=cc65de13e8) | Feb 16, 2024 |
| Dell          | Latitude E7470              | Notebook    | [3a08bc08be](https://bsd-hardware.info/?probe=3a08bc08be) | Feb 15, 2024 |
| Google        | Ultima                      | Notebook    | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [7fcc4087e9](https://bsd-hardware.info/?probe=7fcc4087e9) | Feb 15, 2024 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [f9ad9d25e3](https://bsd-hardware.info/?probe=f9ad9d25e3) | Feb 14, 2024 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [c56fc3f2fc](https://bsd-hardware.info/?probe=c56fc3f2fc) | Feb 14, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [acb70accb8](https://bsd-hardware.info/?probe=acb70accb8) | Feb 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [7a18edf610](https://bsd-hardware.info/?probe=7a18edf610) | Feb 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d24c0ab2c0](https://bsd-hardware.info/?probe=d24c0ab2c0) | Feb 13, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [e0e665c1b5](https://bsd-hardware.info/?probe=e0e665c1b5) | Feb 13, 2024 |
| Dell          | 0PC10G A00                  | Mini pc     | [836dac7d2c](https://bsd-hardware.info/?probe=836dac7d2c) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | Desktop     | [e7dfc1ffe5](https://bsd-hardware.info/?probe=e7dfc1ffe5) | Feb 13, 2024 |
| ASRock        | Z590 Steel Legend           | Desktop     | [30702fa4b5](https://bsd-hardware.info/?probe=30702fa4b5) | Feb 13, 2024 |
| Lenovo        | ThinkPad T410 2522WAR       | Notebook    | [caccf07908](https://bsd-hardware.info/?probe=caccf07908) | Feb 12, 2024 |
| Dell          | 0FF3FN A00                  | Desktop     | [56b53a9e68](https://bsd-hardware.info/?probe=56b53a9e68) | Feb 11, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [fa2107c718](https://bsd-hardware.info/?probe=fa2107c718) | Feb 11, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [08506a1aff](https://bsd-hardware.info/?probe=08506a1aff) | Feb 11, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5f3d8e3288](https://bsd-hardware.info/?probe=5f3d8e3288) | Feb 11, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [977c74f4c0](https://bsd-hardware.info/?probe=977c74f4c0) | Feb 08, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [bf8b98f373](https://bsd-hardware.info/?probe=bf8b98f373) | Feb 08, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1b2b064c64](https://bsd-hardware.info/?probe=1b2b064c64) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [365bb9e521](https://bsd-hardware.info/?probe=365bb9e521) | Feb 07, 2024 |
| Panasonic     | CF-52VDA131M                | Notebook    | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [841a005fc8](https://bsd-hardware.info/?probe=841a005fc8) | Feb 06, 2024 |
| Supermicro    | A1SRM-2758F                 | Server      | [aa8f6d0d16](https://bsd-hardware.info/?probe=aa8f6d0d16) | Feb 06, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [6a6b1dbe8f](https://bsd-hardware.info/?probe=6a6b1dbe8f) | Feb 06, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [e7c9d50432](https://bsd-hardware.info/?probe=e7c9d50432) | Feb 05, 2024 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [c0395ca728](https://bsd-hardware.info/?probe=c0395ca728) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| MSI           | H81M-P33                    | Desktop     | [444eaddd27](https://bsd-hardware.info/?probe=444eaddd27) | Feb 04, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [87358bcf94](https://bsd-hardware.info/?probe=87358bcf94) | Feb 04, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [94f15f8857](https://bsd-hardware.info/?probe=94f15f8857) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [676019447d](https://bsd-hardware.info/?probe=676019447d) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Acer          | Aspire A315-22              | Notebook    | [0bd7a59dfe](https://bsd-hardware.info/?probe=0bd7a59dfe) | Feb 02, 2024 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [c0ca7a18ae](https://bsd-hardware.info/?probe=c0ca7a18ae) | Feb 01, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [b41ed8f957](https://bsd-hardware.info/?probe=b41ed8f957) | Feb 01, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [aae98167a1](https://bsd-hardware.info/?probe=aae98167a1) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [8b93ca6177](https://bsd-hardware.info/?probe=8b93ca6177) | Jan 29, 2024 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [5d0e727014](https://bsd-hardware.info/?probe=5d0e727014) | Jan 29, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| MSI           | H81M-P33                    | Desktop     | [d411f5eb4b](https://bsd-hardware.info/?probe=d411f5eb4b) | Jan 28, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [22436fad84](https://bsd-hardware.info/?probe=22436fad84) | Jan 28, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec38d3e15f](https://bsd-hardware.info/?probe=ec38d3e15f) | Jan 28, 2024 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [47783e5e00](https://bsd-hardware.info/?probe=47783e5e00) | Jan 26, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [713a924dbc](https://bsd-hardware.info/?probe=713a924dbc) | Jan 26, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [70f47b16e5](https://bsd-hardware.info/?probe=70f47b16e5) | Jan 25, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [5e0f98bff5](https://bsd-hardware.info/?probe=5e0f98bff5) | Jan 25, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [d1da11d4cd](https://bsd-hardware.info/?probe=d1da11d4cd) | Jan 24, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [8682cccdcb](https://bsd-hardware.info/?probe=8682cccdcb) | Jan 24, 2024 |
| HP            | ZBook 17 G2                 | Notebook    | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| ASRock        | B660M-STX                   | Desktop     | [5ee66bbf7a](https://bsd-hardware.info/?probe=5ee66bbf7a) | Jan 23, 2024 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [3711b11e8a](https://bsd-hardware.info/?probe=3711b11e8a) | Jan 23, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [ae1a4bcbae](https://bsd-hardware.info/?probe=ae1a4bcbae) | Jan 23, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [60fb8ff088](https://bsd-hardware.info/?probe=60fb8ff088) | Jan 21, 2024 |
| SolidRun      | CEX7 Platform               | Desktop     | [d876c335eb](https://bsd-hardware.info/?probe=d876c335eb) | Jan 21, 2024 |
| AZW           | SER                         | Mini pc     | [be54157bac](https://bsd-hardware.info/?probe=be54157bac) | Jan 21, 2024 |
| Dell          | Latitude E7450              | Notebook    | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [d238dc01c7](https://bsd-hardware.info/?probe=d238dc01c7) | Jan 20, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [86b81c8374](https://bsd-hardware.info/?probe=86b81c8374) | Jan 19, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | Notebook    | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [2330f23f1a](https://bsd-hardware.info/?probe=2330f23f1a) | Jan 16, 2024 |
| Dell          | Precision 7510              | Notebook    | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| LG Electro... | 16UD70R-G.AX59B             | Notebook    | [0b08d5b203](https://bsd-hardware.info/?probe=0b08d5b203) | Jan 16, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a95eae54ba](https://bsd-hardware.info/?probe=a95eae54ba) | Jan 13, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f1224c8ebd](https://bsd-hardware.info/?probe=f1224c8ebd) | Jan 13, 2024 |
| Dell          | Latitude 7490               | Notebook    | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Dell          | Latitude E5420              | Notebook    | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9736c485c9](https://bsd-hardware.info/?probe=9736c485c9) | Jan 12, 2024 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [33704d0025](https://bsd-hardware.info/?probe=33704d0025) | Jan 12, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [c339ed2db4](https://bsd-hardware.info/?probe=c339ed2db4) | Jan 12, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [6cdd70da49](https://bsd-hardware.info/?probe=6cdd70da49) | Jan 11, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [e6c13bf584](https://bsd-hardware.info/?probe=e6c13bf584) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [311083cbe9](https://bsd-hardware.info/?probe=311083cbe9) | Jan 11, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [7c2faad499](https://bsd-hardware.info/?probe=7c2faad499) | Jan 11, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2c7e743906](https://bsd-hardware.info/?probe=2c7e743906) | Jan 10, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [c15701f2a9](https://bsd-hardware.info/?probe=c15701f2a9) | Jan 10, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [82d5d6af92](https://bsd-hardware.info/?probe=82d5d6af92) | Jan 10, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [ef0d0a61f8](https://bsd-hardware.info/?probe=ef0d0a61f8) | Jan 10, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [fa7b4f0216](https://bsd-hardware.info/?probe=fa7b4f0216) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | Notebook    | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| Dell          | Edge Gateway 5100           | Mini pc     | [908b67bf32](https://bsd-hardware.info/?probe=908b67bf32) | Jan 09, 2024 |
| HP            | 3641h                       | Desktop     | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [821748c324](https://bsd-hardware.info/?probe=821748c324) | Jan 08, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [1fd0c4124b](https://bsd-hardware.info/?probe=1fd0c4124b) | Jan 08, 2024 |
| Dell          | Inspiron 5555               | Notebook    | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [f7e3102e87](https://bsd-hardware.info/?probe=f7e3102e87) | Jan 07, 2024 |
| MSI           | H81M-P33                    | Desktop     | [e2407e0579](https://bsd-hardware.info/?probe=e2407e0579) | Jan 07, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [e97b058f7c](https://bsd-hardware.info/?probe=e97b058f7c) | Jan 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d429a5298b](https://bsd-hardware.info/?probe=d429a5298b) | Jan 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [6564d3ecfe](https://bsd-hardware.info/?probe=6564d3ecfe) | Jan 07, 2024 |
| HP            | Pavilion g6                 | Notebook    | [77f3d49b2e](https://bsd-hardware.info/?probe=77f3d49b2e) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [3f3aabf270](https://bsd-hardware.info/?probe=3f3aabf270) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| Lenovo        | ThinkPad 11e 20D90020US     | Notebook    | [7d7f564886](https://bsd-hardware.info/?probe=7d7f564886) | Jan 05, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [90346c6fe3](https://bsd-hardware.info/?probe=90346c6fe3) | Jan 04, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [a678ec59e8](https://bsd-hardware.info/?probe=a678ec59e8) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [5c583e5a9d](https://bsd-hardware.info/?probe=5c583e5a9d) | Jan 04, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [29b63ed6a8](https://bsd-hardware.info/?probe=29b63ed6a8) | Jan 04, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [17862ade20](https://bsd-hardware.info/?probe=17862ade20) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [7ac885382c](https://bsd-hardware.info/?probe=7ac885382c) | Jan 03, 2024 |
| HP            | Laptop 15t-dy100            | Notebook    | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [d7b4e67cdc](https://bsd-hardware.info/?probe=d7b4e67cdc) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | Notebook    | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [a29eec0aa5](https://bsd-hardware.info/?probe=a29eec0aa5) | Jan 02, 2024 |
| Alienware     | 07HV66 A00                  | Desktop     | [ea6a3f3020](https://bsd-hardware.info/?probe=ea6a3f3020) | Jan 01, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [7e2b858339](https://bsd-hardware.info/?probe=7e2b858339) | Dec 31, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [84985aa669](https://bsd-hardware.info/?probe=84985aa669) | Dec 31, 2023 |
| MSI           | H81M-P33                    | Desktop     | [82e08820f2](https://bsd-hardware.info/?probe=82e08820f2) | Dec 31, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da3b88ef85](https://bsd-hardware.info/?probe=da3b88ef85) | Dec 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [391f4c0e0b](https://bsd-hardware.info/?probe=391f4c0e0b) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [1889675f37](https://bsd-hardware.info/?probe=1889675f37) | Dec 30, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| HP            | 3397                        | Desktop     | [46b6923bcd](https://bsd-hardware.info/?probe=46b6923bcd) | Dec 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [fe3a4e49ee](https://bsd-hardware.info/?probe=fe3a4e49ee) | Dec 29, 2023 |
| Dell          | Inspiron 3195               | Convertible | [fb2acd7e84](https://bsd-hardware.info/?probe=fb2acd7e84) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [6b9d713fe0](https://bsd-hardware.info/?probe=6b9d713fe0) | Dec 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [4ddf360812](https://bsd-hardware.info/?probe=4ddf360812) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | Notebook    | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| MSI           | Aspen                       | Desktop     | [ac6dd2b153](https://bsd-hardware.info/?probe=ac6dd2b153) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [504fb1678f](https://bsd-hardware.info/?probe=504fb1678f) | Dec 24, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [a740494857](https://bsd-hardware.info/?probe=a740494857) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [7e4cee9689](https://bsd-hardware.info/?probe=7e4cee9689) | Dec 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [04675127c2](https://bsd-hardware.info/?probe=04675127c2) | Dec 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1ef7136151](https://bsd-hardware.info/?probe=1ef7136151) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [3f4dbee6d1](https://bsd-hardware.info/?probe=3f4dbee6d1) | Dec 24, 2023 |
| Acer          | Veriton X490G               | Desktop     | [1865afdae1](https://bsd-hardware.info/?probe=1865afdae1) | Dec 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Dell          | Precision 7720              | Notebook    | [a30d05e373](https://bsd-hardware.info/?probe=a30d05e373) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [85ec93f4cd](https://bsd-hardware.info/?probe=85ec93f4cd) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [34f3eb8059](https://bsd-hardware.info/?probe=34f3eb8059) | Dec 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Clevo         | W240BU                      | Notebook    | [19bb603cab](https://bsd-hardware.info/?probe=19bb603cab) | Dec 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | Notebook    | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [03b0e973ca](https://bsd-hardware.info/?probe=03b0e973ca) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [4bc98299dd](https://bsd-hardware.info/?probe=4bc98299dd) | Dec 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | Notebook    | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a4d01667e](https://bsd-hardware.info/?probe=5a4d01667e) | Dec 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ea79e98108](https://bsd-hardware.info/?probe=ea79e98108) | Dec 17, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [11e5e87b70](https://bsd-hardware.info/?probe=11e5e87b70) | Dec 16, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4b134e7787](https://bsd-hardware.info/?probe=4b134e7787) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | Notebook    | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | Notebook    | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [7a32a123f6](https://bsd-hardware.info/?probe=7a32a123f6) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Dell          | Latitude E6220              | Notebook    | [372070b2f2](https://bsd-hardware.info/?probe=372070b2f2) | Dec 15, 2023 |
| Google        | Kohaku                      | Notebook    | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [3767d653b9](https://bsd-hardware.info/?probe=3767d653b9) | Dec 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [60451d4e43](https://bsd-hardware.info/?probe=60451d4e43) | Dec 14, 2023 |
| Dell          | Latitude E6540              | Notebook    | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| AZW           | EQ                          | Desktop     | [d83e11a7dc](https://bsd-hardware.info/?probe=d83e11a7dc) | Dec 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [bc50d301fa](https://bsd-hardware.info/?probe=bc50d301fa) | Dec 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [dced442907](https://bsd-hardware.info/?probe=dced442907) | Dec 13, 2023 |
| Google        | Lindar rev3                 | Notebook    | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [357a808604](https://bsd-hardware.info/?probe=357a808604) | Dec 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [9a842bf3c8](https://bsd-hardware.info/?probe=9a842bf3c8) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Dell          | 0N051F A04                  | Server      | [38535e6878](https://bsd-hardware.info/?probe=38535e6878) | Dec 11, 2023 |
| Dell          | 0XDN97 A09                  | Server      | [129a73f16f](https://bsd-hardware.info/?probe=129a73f16f) | Dec 11, 2023 |
| EVGA          | X570 DARK.0                 | Desktop     | [1c84a8169b](https://bsd-hardware.info/?probe=1c84a8169b) | Dec 11, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [6e876a349f](https://bsd-hardware.info/?probe=6e876a349f) | Dec 11, 2023 |
| Dell          | 084XW4 A05                  | Server      | [951a41f88c](https://bsd-hardware.info/?probe=951a41f88c) | Dec 11, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2febbeffc2](https://bsd-hardware.info/?probe=2febbeffc2) | Dec 11, 2023 |
| Dell          | 084XW4 A06                  | Server      | [961b6ac6f7](https://bsd-hardware.info/?probe=961b6ac6f7) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| AZW           | EQ                          | Desktop     | [0280c1cdb9](https://bsd-hardware.info/?probe=0280c1cdb9) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [881ad2eacf](https://bsd-hardware.info/?probe=881ad2eacf) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [47480f848d](https://bsd-hardware.info/?probe=47480f848d) | Dec 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2b1599aacd](https://bsd-hardware.info/?probe=2b1599aacd) | Dec 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| Google        | Parrot                      | Notebook    | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [78399ba39e](https://bsd-hardware.info/?probe=78399ba39e) | Dec 09, 2023 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [7a6cdb3f06](https://bsd-hardware.info/?probe=7a6cdb3f06) | Dec 09, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [d62ad0d622](https://bsd-hardware.info/?probe=d62ad0d622) | Dec 09, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [5b31c551ae](https://bsd-hardware.info/?probe=5b31c551ae) | Dec 09, 2023 |
| Dell          | Latitude 7414               | Notebook    | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Dell          | Precision 7560              | Notebook    | [13f7324bd9](https://bsd-hardware.info/?probe=13f7324bd9) | Dec 07, 2023 |
| Dell          | Precision 7560              | Notebook    | [5d3e6e3bd4](https://bsd-hardware.info/?probe=5d3e6e3bd4) | Dec 07, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7fd4743b86](https://bsd-hardware.info/?probe=7fd4743b86) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [41e61ade9a](https://bsd-hardware.info/?probe=41e61ade9a) | Dec 06, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| MECHREVO      | F7BSC V1.0                  | Mini pc     | [d1104aa676](https://bsd-hardware.info/?probe=d1104aa676) | Dec 05, 2023 |
| ECS           | MCP61M-M3                   | Desktop     | [6d6c04c278](https://bsd-hardware.info/?probe=6d6c04c278) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8c023b9c33](https://bsd-hardware.info/?probe=8c023b9c33) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | Notebook    | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Lenovo        | ThinkPad T430s 23532QG      | Notebook    | [b456c01e0f](https://bsd-hardware.info/?probe=b456c01e0f) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [ea8b5e1c14](https://bsd-hardware.info/?probe=ea8b5e1c14) | Dec 03, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [322ea11f6c](https://bsd-hardware.info/?probe=322ea11f6c) | Dec 03, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [a13be946a5](https://bsd-hardware.info/?probe=a13be946a5) | Dec 03, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [4f5b576aff](https://bsd-hardware.info/?probe=4f5b576aff) | Dec 03, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | Notebook    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [0457bab107](https://bsd-hardware.info/?probe=0457bab107) | Dec 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [f1cb9a41ba](https://bsd-hardware.info/?probe=f1cb9a41ba) | Nov 30, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [ae4c6d7097](https://bsd-hardware.info/?probe=ae4c6d7097) | Nov 29, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1b4871792b](https://bsd-hardware.info/?probe=1b4871792b) | Nov 28, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| Dell          | Precision 5510              | Notebook    | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [806a29d40a](https://bsd-hardware.info/?probe=806a29d40a) | Nov 28, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [b32ded6bb9](https://bsd-hardware.info/?probe=b32ded6bb9) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c9f6264329](https://bsd-hardware.info/?probe=c9f6264329) | Nov 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [1e9f19c4ae](https://bsd-hardware.info/?probe=1e9f19c4ae) | Nov 27, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3b18ff26c0](https://bsd-hardware.info/?probe=3b18ff26c0) | Nov 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42bddda351](https://bsd-hardware.info/?probe=42bddda351) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b653e75063](https://bsd-hardware.info/?probe=b653e75063) | Nov 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1454187842](https://bsd-hardware.info/?probe=1454187842) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28f6ec2a7b](https://bsd-hardware.info/?probe=28f6ec2a7b) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [3517ce2745](https://bsd-hardware.info/?probe=3517ce2745) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5f336b9d93](https://bsd-hardware.info/?probe=5f336b9d93) | Nov 26, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [639ffb1573](https://bsd-hardware.info/?probe=639ffb1573) | Nov 25, 2023 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [24f4b0ec7e](https://bsd-hardware.info/?probe=24f4b0ec7e) | Nov 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e0d8200dfa](https://bsd-hardware.info/?probe=e0d8200dfa) | Nov 24, 2023 |
| Google        | Dragonair                   | Notebook    | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| HP            | Notebook                    | Notebook    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Silicom       | 80300-0214-G16 R310         | Desktop     | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Acer          | JM11-MS                     | Notebook    | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Acidanther... | MacBookPro16,3              | Notebook    | [5f89fa2cd2](https://bsd-hardware.info/?probe=5f89fa2cd2) | Nov 22, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4c80855e88](https://bsd-hardware.info/?probe=4c80855e88) | Nov 22, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a37a33268d](https://bsd-hardware.info/?probe=a37a33268d) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fb283e956a](https://bsd-hardware.info/?probe=fb283e956a) | Nov 21, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4b6284d041](https://bsd-hardware.info/?probe=4b6284d041) | Nov 20, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [c9a12372b4](https://bsd-hardware.info/?probe=c9a12372b4) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [fdb7c00df7](https://bsd-hardware.info/?probe=fdb7c00df7) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [17d29b1055](https://bsd-hardware.info/?probe=17d29b1055) | Nov 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6406980bbf](https://bsd-hardware.info/?probe=6406980bbf) | Nov 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e7ccb4156e](https://bsd-hardware.info/?probe=e7ccb4156e) | Nov 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a570c7994c](https://bsd-hardware.info/?probe=a570c7994c) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| MSI           | B560-A PRO                  | Desktop     | [cf9b5a14ce](https://bsd-hardware.info/?probe=cf9b5a14ce) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Panasonic     | CF-31-5                     | Notebook    | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [9eab94b4f7](https://bsd-hardware.info/?probe=9eab94b4f7) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [cfbda53125](https://bsd-hardware.info/?probe=cfbda53125) | Nov 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ece5171a1d](https://bsd-hardware.info/?probe=ece5171a1d) | Nov 17, 2023 |
| HP            | Notebook                    | Notebook    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [aa3a09d113](https://bsd-hardware.info/?probe=aa3a09d113) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [5ca736990f](https://bsd-hardware.info/?probe=5ca736990f) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0e4ea9ccbf](https://bsd-hardware.info/?probe=0e4ea9ccbf) | Nov 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| HP            | 18E7                        | Desktop     | [3cbe1117fa](https://bsd-hardware.info/?probe=3cbe1117fa) | Nov 14, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [2487233a5d](https://bsd-hardware.info/?probe=2487233a5d) | Nov 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [ee4c8ddddc](https://bsd-hardware.info/?probe=ee4c8ddddc) | Nov 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [771c13f8ea](https://bsd-hardware.info/?probe=771c13f8ea) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [35ae423f7a](https://bsd-hardware.info/?probe=35ae423f7a) | Nov 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a062354358](https://bsd-hardware.info/?probe=a062354358) | Nov 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0869172a54](https://bsd-hardware.info/?probe=0869172a54) | Nov 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b1e348523f](https://bsd-hardware.info/?probe=b1e348523f) | Nov 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f32f8bdf95](https://bsd-hardware.info/?probe=f32f8bdf95) | Nov 12, 2023 |
| OnLogic       | HX401                       | Notebook    | [b000c6d264](https://bsd-hardware.info/?probe=b000c6d264) | Nov 12, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [3ce8e78453](https://bsd-hardware.info/?probe=3ce8e78453) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | Notebook    | [dc8d596ea1](https://bsd-hardware.info/?probe=dc8d596ea1) | Nov 11, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [81e93afe2e](https://bsd-hardware.info/?probe=81e93afe2e) | Nov 10, 2023 |
| ASRock        | B460M Steel Legend          | Desktop     | [13bdfc626b](https://bsd-hardware.info/?probe=13bdfc626b) | Nov 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3c3b2abb3d](https://bsd-hardware.info/?probe=3c3b2abb3d) | Nov 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | Notebook    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| Dell          | Precision 7560              | Notebook    | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b7b9df03f3](https://bsd-hardware.info/?probe=b7b9df03f3) | Nov 09, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [9d4170e2d2](https://bsd-hardware.info/?probe=9d4170e2d2) | Nov 08, 2023 |
| Samsung       | 740U5M                      | Convertible | [1a996f2f48](https://bsd-hardware.info/?probe=1a996f2f48) | Nov 08, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6588258570](https://bsd-hardware.info/?probe=6588258570) | Nov 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [36a87f24f7](https://bsd-hardware.info/?probe=36a87f24f7) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e8c7d22b1f](https://bsd-hardware.info/?probe=e8c7d22b1f) | Nov 05, 2023 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [9de790eac0](https://bsd-hardware.info/?probe=9de790eac0) | Nov 05, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | 0MD99X A12                  | Server      | [c137d2d6da](https://bsd-hardware.info/?probe=c137d2d6da) | Nov 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [d44c30f985](https://bsd-hardware.info/?probe=d44c30f985) | Nov 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [dac3ca2eca](https://bsd-hardware.info/?probe=dac3ca2eca) | Nov 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e744712416](https://bsd-hardware.info/?probe=e744712416) | Nov 05, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a8aad4a386](https://bsd-hardware.info/?probe=a8aad4a386) | Nov 04, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | Notebook    | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| Dell          | 0Y2V0C A03                  | Desktop     | [5c7de92bb3](https://bsd-hardware.info/?probe=5c7de92bb3) | Nov 03, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [2fab5b5adf](https://bsd-hardware.info/?probe=2fab5b5adf) | Nov 01, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [03fa12a885](https://bsd-hardware.info/?probe=03fa12a885) | Nov 01, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [f93d5865b8](https://bsd-hardware.info/?probe=f93d5865b8) | Nov 01, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [87e3260963](https://bsd-hardware.info/?probe=87e3260963) | Oct 31, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [c60aeb219e](https://bsd-hardware.info/?probe=c60aeb219e) | Oct 31, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | Notebook    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c163891517](https://bsd-hardware.info/?probe=c163891517) | Oct 31, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [ebdc124789](https://bsd-hardware.info/?probe=ebdc124789) | Oct 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [c7e5f79b34](https://bsd-hardware.info/?probe=c7e5f79b34) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1f6542c47d](https://bsd-hardware.info/?probe=1f6542c47d) | Oct 29, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1b42e4a912](https://bsd-hardware.info/?probe=1b42e4a912) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8e245ccb85](https://bsd-hardware.info/?probe=8e245ccb85) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | Notebook    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Shuttle       | FZ270                       | Desktop     | [1aa4ad0971](https://bsd-hardware.info/?probe=1aa4ad0971) | Oct 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ab44e043d2](https://bsd-hardware.info/?probe=ab44e043d2) | Oct 23, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8f62c35aa0](https://bsd-hardware.info/?probe=8f62c35aa0) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dd9ff802a9](https://bsd-hardware.info/?probe=dd9ff802a9) | Oct 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1b94fd9385](https://bsd-hardware.info/?probe=1b94fd9385) | Oct 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cc7fb797f5](https://bsd-hardware.info/?probe=cc7fb797f5) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7148ec01b2](https://bsd-hardware.info/?probe=7148ec01b2) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a8727c3ee3](https://bsd-hardware.info/?probe=a8727c3ee3) | Oct 19, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [606ed441ae](https://bsd-hardware.info/?probe=606ed441ae) | Oct 19, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0f914c6351](https://bsd-hardware.info/?probe=0f914c6351) | Oct 17, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6902d492db](https://bsd-hardware.info/?probe=6902d492db) | Oct 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [094b766a05](https://bsd-hardware.info/?probe=094b766a05) | Oct 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b502116394](https://bsd-hardware.info/?probe=b502116394) | Oct 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [697f24cf01](https://bsd-hardware.info/?probe=697f24cf01) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d14ff47394](https://bsd-hardware.info/?probe=d14ff47394) | Oct 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a7307b8de1](https://bsd-hardware.info/?probe=a7307b8de1) | Oct 12, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Dell          | Precision 7550              | Notebook    | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [f55c557bcf](https://bsd-hardware.info/?probe=f55c557bcf) | Oct 09, 2023 |
| EVGA          | X299 MICRO                  | Desktop     | [2907f2166d](https://bsd-hardware.info/?probe=2907f2166d) | Oct 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [a9729ebc38](https://bsd-hardware.info/?probe=a9729ebc38) | Oct 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [06a76899d6](https://bsd-hardware.info/?probe=06a76899d6) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cacbb83f98](https://bsd-hardware.info/?probe=cacbb83f98) | Oct 08, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | Notebook    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| MSI           | Aspen                       | Desktop     | [7bb665508f](https://bsd-hardware.info/?probe=7bb665508f) | Oct 07, 2023 |
| GVC           | DR 738                      | Desktop     | [1aa25f04a8](https://bsd-hardware.info/?probe=1aa25f04a8) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3580a1e53](https://bsd-hardware.info/?probe=b3580a1e53) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f63740c0e](https://bsd-hardware.info/?probe=3f63740c0e) | Oct 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | Notebook    | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| ASUSTek       | Pro WS W680-ACE IPMI        | Desktop     | [6a98aea3f9](https://bsd-hardware.info/?probe=6a98aea3f9) | Oct 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| Platform      | ARB938                      | Notebook    | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | Notebook    | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Intel         | NUC8BEB J72692-307          | Mini pc     | [e43673f564](https://bsd-hardware.info/?probe=e43673f564) | Oct 01, 2023 |
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [c6903de57a](https://bsd-hardware.info/?probe=c6903de57a) | Sep 30, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [31da8655d1](https://bsd-hardware.info/?probe=31da8655d1) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [c35034519a](https://bsd-hardware.info/?probe=c35034519a) | Sep 28, 2023 |
| Biostar       | A55MLC2                     | Desktop     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [0a035e25a9](https://bsd-hardware.info/?probe=0a035e25a9) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [bde8cc45df](https://bsd-hardware.info/?probe=bde8cc45df) | Sep 26, 2023 |
| Dell          | 07T4MC A09                  | Desktop     | [0ce8f84155](https://bsd-hardware.info/?probe=0ce8f84155) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| AZW           | SEi V1.0                    | Desktop     | [1d0307b36d](https://bsd-hardware.info/?probe=1d0307b36d) | Sep 23, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Dell          | G16 7630                    | Notebook    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | Notebook    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab77dcfd74](https://bsd-hardware.info/?probe=ab77dcfd74) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | Notebook    | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Platform      | ARB938                      | Notebook    | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | Notebook    | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| HP            | ProBook 4530s               | Notebook    | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | Notebook    | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [78bc36f5a9](https://bsd-hardware.info/?probe=78bc36f5a9) | Sep 11, 2023 |
| Dell          | BlackfordESB2               | Server      | [36b37267be](https://bsd-hardware.info/?probe=36b37267be) | Sep 11, 2023 |
| HP            | Mini 110-3100               | Notebook    | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | Notebook    | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [6be22d7887](https://bsd-hardware.info/?probe=6be22d7887) | Sep 09, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7947ecdca3](https://bsd-hardware.info/?probe=7947ecdca3) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [24e745026c](https://bsd-hardware.info/?probe=24e745026c) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [40b4e58c88](https://bsd-hardware.info/?probe=40b4e58c88) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1bde5a65b6](https://bsd-hardware.info/?probe=1bde5a65b6) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Shuttle       | DS20U                       | Desktop     | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| Intel         | HM570                       | Desktop     | [de018603ae](https://bsd-hardware.info/?probe=de018603ae) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [82ac08abc0](https://bsd-hardware.info/?probe=82ac08abc0) | Aug 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| HP            | 802F                        | Desktop     | [1f64f7e11f](https://bsd-hardware.info/?probe=1f64f7e11f) | Aug 30, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [b83ebfd33b](https://bsd-hardware.info/?probe=b83ebfd33b) | Aug 29, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| Nvidia        | MCP79                       | Desktop     | [0897b3a117](https://bsd-hardware.info/?probe=0897b3a117) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [df915d5ab9](https://bsd-hardware.info/?probe=df915d5ab9) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| Dell          | G5 5590                     | Notebook    | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | Notebook    | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [4d51e18ce4](https://bsd-hardware.info/?probe=4d51e18ce4) | Aug 25, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [4978b62b97](https://bsd-hardware.info/?probe=4978b62b97) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| MSI           | G31M3-L V2                  | Desktop     | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Dell          | 068CDY A01                  | Server      | [c3e69db640](https://bsd-hardware.info/?probe=c3e69db640) | Aug 22, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| Shuttle       | DS20U                       | Desktop     | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| AZW           | SER                         | Mini pc     | [db297e2cda](https://bsd-hardware.info/?probe=db297e2cda) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | Notebook    | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [9e92903663](https://bsd-hardware.info/?probe=9e92903663) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Dell          | 05FT2M A04                  | Server      | [73afce6eeb](https://bsd-hardware.info/?probe=73afce6eeb) | Aug 17, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7aa7ba9ea9](https://bsd-hardware.info/?probe=7aa7ba9ea9) | Aug 17, 2023 |
| Supermicro    | M12SWA-TF                   | Desktop     | [2e38f0b91a](https://bsd-hardware.info/?probe=2e38f0b91a) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | Notebook    | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [2e9106fc92](https://bsd-hardware.info/?probe=2e9106fc92) | Aug 11, 2023 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [7b00ddd0a1](https://bsd-hardware.info/?probe=7b00ddd0a1) | Aug 11, 2023 |
| PC Engines    | apu1                        | Desktop     | [0b3594d9a3](https://bsd-hardware.info/?probe=0b3594d9a3) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [65092dde79](https://bsd-hardware.info/?probe=65092dde79) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | Notebook    | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [f809d834df](https://bsd-hardware.info/?probe=f809d834df) | Aug 03, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| HP            | 8298                        | Desktop     | [961bfad69a](https://bsd-hardware.info/?probe=961bfad69a) | Aug 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [be9b9caa66](https://bsd-hardware.info/?probe=be9b9caa66) | Jul 31, 2023 |
| AZW           | SER                         | Mini pc     | [287fdf7e70](https://bsd-hardware.info/?probe=287fdf7e70) | Jul 30, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [09f173d4b6](https://bsd-hardware.info/?probe=09f173d4b6) | Jul 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [64137e0eec](https://bsd-hardware.info/?probe=64137e0eec) | Jul 29, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [14d1fdc0b1](https://bsd-hardware.info/?probe=14d1fdc0b1) | Jul 24, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f54cfd9d27](https://bsd-hardware.info/?probe=f54cfd9d27) | Jul 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [f77e9a46c3](https://bsd-hardware.info/?probe=f77e9a46c3) | Jul 22, 2023 |
| HP            | ProBook x360 11 G7 Educa... | Convertible | [22e1b9f0d5](https://bsd-hardware.info/?probe=22e1b9f0d5) | Jul 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | Notebook    | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | Notebook    | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| HPE           | ProLiant DL360 Gen10        | Server      | [115edf7c58](https://bsd-hardware.info/?probe=115edf7c58) | Jul 20, 2023 |
| Dell          | Precision 5550              | Notebook    | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [ce0f05e871](https://bsd-hardware.info/?probe=ce0f05e871) | Jul 18, 2023 |
| Samsung       | 100NZB                      | Notebook    | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Intel         | HM570                       | Desktop     | [a9abbf1e12](https://bsd-hardware.info/?probe=a9abbf1e12) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | Notebook    | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | Desktop     | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08b0409497](https://bsd-hardware.info/?probe=08b0409497) | Jul 12, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [d0f09cc8c4](https://bsd-hardware.info/?probe=d0f09cc8c4) | Jul 11, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Getac         | F110G2                      | Notebook    | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | Notebook    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| HP            | 3397                        | Desktop     | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [e0d3f841c7](https://bsd-hardware.info/?probe=e0d3f841c7) | Jul 07, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| HP            | 82F2 A01                    | Desktop     | [a77d73b637](https://bsd-hardware.info/?probe=a77d73b637) | Jul 04, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | Notebook    | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e569621be2](https://bsd-hardware.info/?probe=e569621be2) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [553cd9ecae](https://bsd-hardware.info/?probe=553cd9ecae) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [3c80c960d3](https://bsd-hardware.info/?probe=3c80c960d3) | Jul 03, 2023 |
| ASRock        | J3455B-ITX                  | Desktop     | [051ddf6f8d](https://bsd-hardware.info/?probe=051ddf6f8d) | Jul 03, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [dfdb0bd650](https://bsd-hardware.info/?probe=dfdb0bd650) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [e68bb73773](https://bsd-hardware.info/?probe=e68bb73773) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b4a248520](https://bsd-hardware.info/?probe=3b4a248520) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a2a221aae](https://bsd-hardware.info/?probe=0a2a221aae) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [7e5ee8de12](https://bsd-hardware.info/?probe=7e5ee8de12) | Jul 03, 2023 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [3b50a90ebc](https://bsd-hardware.info/?probe=3b50a90ebc) | Jul 03, 2023 |
| Gigabyte      | M85M-US2H                   | Desktop     | [e0a38ef6ad](https://bsd-hardware.info/?probe=e0a38ef6ad) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [9f6d45e43e](https://bsd-hardware.info/?probe=9f6d45e43e) | Jul 02, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [3eb03fa8a7](https://bsd-hardware.info/?probe=3eb03fa8a7) | Jul 02, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [6479d60da2](https://bsd-hardware.info/?probe=6479d60da2) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [6823b41760](https://bsd-hardware.info/?probe=6823b41760) | Jun 27, 2023 |
| Dell          | Latitude 3420               | Notebook    | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | Notebook    | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | Notebook    | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | Notebook    | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [6172c8b66f](https://bsd-hardware.info/?probe=6172c8b66f) | Jun 22, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [f0b283fdaf](https://bsd-hardware.info/?probe=f0b283fdaf) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | Notebook    | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| AZW           | SER                         | Mini pc     | [278b419d40](https://bsd-hardware.info/?probe=278b419d40) | Jun 17, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| IBM           | 69Y5698                     | Server      | [9f5eb975e0](https://bsd-hardware.info/?probe=9f5eb975e0) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b4f214b72](https://bsd-hardware.info/?probe=6b4f214b72) | Jun 15, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [615e7cbf52](https://bsd-hardware.info/?probe=615e7cbf52) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [8357f0f72e](https://bsd-hardware.info/?probe=8357f0f72e) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [5a21ed950e](https://bsd-hardware.info/?probe=5a21ed950e) | Jun 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [7e0151a93f](https://bsd-hardware.info/?probe=7e0151a93f) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | Notebook    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | Notebook    | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [d04a63aa31](https://bsd-hardware.info/?probe=d04a63aa31) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| HP            | 212B                        | Desktop     | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [314d462dcd](https://bsd-hardware.info/?probe=314d462dcd) | Jun 04, 2023 |
| Dell          | G5 5505                     | Notebook    | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d4247f35c8](https://bsd-hardware.info/?probe=d4247f35c8) | Jun 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [2445651c96](https://bsd-hardware.info/?probe=2445651c96) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [a9b9a2e045](https://bsd-hardware.info/?probe=a9b9a2e045) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [e63f1f4874](https://bsd-hardware.info/?probe=e63f1f4874) | May 29, 2023 |
| ASRock        | Z590 Pro4                   | Desktop     | [382fe30ec1](https://bsd-hardware.info/?probe=382fe30ec1) | May 28, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [d5fdf2ff2c](https://bsd-hardware.info/?probe=d5fdf2ff2c) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | Desktop     | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [81775d5ca1](https://bsd-hardware.info/?probe=81775d5ca1) | May 26, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3797f9d0a9](https://bsd-hardware.info/?probe=3797f9d0a9) | May 24, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | Notebook    | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | 158B                        | Desktop     | [1ef3762103](https://bsd-hardware.info/?probe=1ef3762103) | May 20, 2023 |
| HP            | 158B                        | Desktop     | [a9c63041a6](https://bsd-hardware.info/?probe=a9c63041a6) | May 20, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [186e5d4e15](https://bsd-hardware.info/?probe=186e5d4e15) | May 19, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [47d985333c](https://bsd-hardware.info/?probe=47d985333c) | May 19, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [9350bb37db](https://bsd-hardware.info/?probe=9350bb37db) | May 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | Notebook    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [73335cbb47](https://bsd-hardware.info/?probe=73335cbb47) | May 17, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [830100249f](https://bsd-hardware.info/?probe=830100249f) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [12b0e44025](https://bsd-hardware.info/?probe=12b0e44025) | May 17, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [3bf2cd6d1e](https://bsd-hardware.info/?probe=3bf2cd6d1e) | May 14, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [7d0fe109f0](https://bsd-hardware.info/?probe=7d0fe109f0) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| MSI           | B85M-G43                    | Desktop     | [6d2160dcee](https://bsd-hardware.info/?probe=6d2160dcee) | May 14, 2023 |
| Alienware     | 17 R4                       | Notebook    | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| HP            | 802F                        | Desktop     | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [71ad6e7c1c](https://bsd-hardware.info/?probe=71ad6e7c1c) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [d72b0581a4](https://bsd-hardware.info/?probe=d72b0581a4) | May 11, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b5ce0177b2](https://bsd-hardware.info/?probe=b5ce0177b2) | May 10, 2023 |
| Medion        | Major X10                   | Notebook    | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [89cd98c281](https://bsd-hardware.info/?probe=89cd98c281) | May 10, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| HP            | 805D                        | Desktop     | [648c680432](https://bsd-hardware.info/?probe=648c680432) | May 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [4cde43ac30](https://bsd-hardware.info/?probe=4cde43ac30) | May 04, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [a80b700f3a](https://bsd-hardware.info/?probe=a80b700f3a) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 1589                        | Desktop     | [4aee1909c8](https://bsd-hardware.info/?probe=4aee1909c8) | May 03, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b09acffe7b](https://bsd-hardware.info/?probe=b09acffe7b) | May 01, 2023 |
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [9d82570c34](https://bsd-hardware.info/?probe=9d82570c34) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | Desktop     | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | Desktop     | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| GVC           | DR 738                      | Desktop     | [21b338db1b](https://bsd-hardware.info/?probe=21b338db1b) | Apr 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [ce8453fcce](https://bsd-hardware.info/?probe=ce8453fcce) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | Notebook    | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| Dell          | 0569RT A04                  | Server      | [cff2ebd06b](https://bsd-hardware.info/?probe=cff2ebd06b) | Apr 23, 2023 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [596ddff446](https://bsd-hardware.info/?probe=596ddff446) | Apr 22, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | Notebook    | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [838979f891](https://bsd-hardware.info/?probe=838979f891) | Apr 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| HP            | 158B                        | Desktop     | [40fe372619](https://bsd-hardware.info/?probe=40fe372619) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | Notebook    | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3852dcb332](https://bsd-hardware.info/?probe=3852dcb332) | Apr 19, 2023 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [b341a9c9c9](https://bsd-hardware.info/?probe=b341a9c9c9) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Lenovo        | YangTianM6880N              | Desktop     | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Lenovo        | Larne CRB 31900002 WIN      | All in one  | [1f18ec4466](https://bsd-hardware.info/?probe=1f18ec4466) | Apr 16, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| ASUSTek       | PRIME X299-A II             | Desktop     | [8c345e7a24](https://bsd-hardware.info/?probe=8c345e7a24) | Apr 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| HP            | ProLiant DL180 G6           | Server      | [4ccb132836](https://bsd-hardware.info/?probe=4ccb132836) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | Notebook    | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4ae38adc2a](https://bsd-hardware.info/?probe=4ae38adc2a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| HP            | 212B                        | Desktop     | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [f7bcf353a9](https://bsd-hardware.info/?probe=f7bcf353a9) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| HP            | 212B                        | Desktop     | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [a4957dcdd6](https://bsd-hardware.info/?probe=a4957dcdd6) | Apr 04, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [ee2b566f14](https://bsd-hardware.info/?probe=ee2b566f14) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| HP            | 81C6 MVB 0C                 | Server      | [65d2113596](https://bsd-hardware.info/?probe=65d2113596) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| HP            | 212B                        | Desktop     | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [01bf5e8678](https://bsd-hardware.info/?probe=01bf5e8678) | Apr 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Chuwi         | Unknown                     | Notebook    | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [3c3a780d95](https://bsd-hardware.info/?probe=3c3a780d95) | Mar 31, 2023 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| HP            | 339A                        | Desktop     | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Biostar       | TH67B                       | Desktop     | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [1d7c737c38](https://bsd-hardware.info/?probe=1d7c737c38) | Mar 29, 2023 |
| Google        | Stout                       | Notebook    | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Alienware     | 049PDM A00                  | Desktop     | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Shuttle       | FH110                       | Desktop     | [4fa8a9cc08](https://bsd-hardware.info/?probe=4fa8a9cc08) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| Dell          | 0C2GT0 A05                  | Server      | [2d32ae23e6](https://bsd-hardware.info/?probe=2d32ae23e6) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| eMachines     | eM350                       | Notebook    | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Alienware     | 14                          | Notebook    | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | Notebook    | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| HP            | 3397                        | Desktop     | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Dell          | Edge Gateway 5100           | Mini pc     | [7cb4288db0](https://bsd-hardware.info/?probe=7cb4288db0) | Mar 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4dc54510d2](https://bsd-hardware.info/?probe=4dc54510d2) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [cab50cddd5](https://bsd-hardware.info/?probe=cab50cddd5) | Mar 19, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff4dda40eb](https://bsd-hardware.info/?probe=ff4dda40eb) | Mar 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| HP            | 212B                        | Desktop     | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| GVC           | DR 738                      | Desktop     | [88455ed9e7](https://bsd-hardware.info/?probe=88455ed9e7) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | Notebook    | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| HP            | 3397                        | Desktop     | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| HP            | 0AA8h                       | Desktop     | [15ddd97321](https://bsd-hardware.info/?probe=15ddd97321) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| Google        | Kohaku                      | Notebook    | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | Notebook    | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [c8abf1f5bf](https://bsd-hardware.info/?probe=c8abf1f5bf) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [62c09245a4](https://bsd-hardware.info/?probe=62c09245a4) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | Notebook    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [970f35af17](https://bsd-hardware.info/?probe=970f35af17) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Samsung       | 750XEE                      | Notebook    | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [2ba0e18863](https://bsd-hardware.info/?probe=2ba0e18863) | Mar 05, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a3f77b82cc](https://bsd-hardware.info/?probe=a3f77b82cc) | Mar 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| ASRock        | E350M1                      | Desktop     | [461f8cca23](https://bsd-hardware.info/?probe=461f8cca23) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | Desktop     | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3daad10634](https://bsd-hardware.info/?probe=3daad10634) | Mar 02, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [d675a5bab2](https://bsd-hardware.info/?probe=d675a5bab2) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | Notebook    | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [dca82c50d0](https://bsd-hardware.info/?probe=dca82c50d0) | Feb 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [e55635df08](https://bsd-hardware.info/?probe=e55635df08) | Feb 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| MSI           | H81M-P33                    | Desktop     | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c30dd3fbca](https://bsd-hardware.info/?probe=c30dd3fbca) | Feb 19, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [a27331804b](https://bsd-hardware.info/?probe=a27331804b) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 236       | 7.48%   |
| FreeBSD 13.0         | 223       | 7.07%   |
| FreeBSD 14.0-CURRENT | 152       | 4.82%   |
| FreeBSD 13.2         | 151       | 4.79%   |
| FreeBSD 12.2         | 141       | 4.47%   |
| FreeBSD 12.2-p2      | 96        | 3.04%   |
| FreeBSD 13.0-p4      | 85        | 2.69%   |
| FreeBSD 13.1-p5      | 83        | 2.63%   |
| FreeBSD 14.0         | 79        | 2.5%    |
| FreeBSD 12.1-p10     | 79        | 2.5%    |
| FreeBSD 13.0-p5      | 76        | 2.41%   |
| FreeBSD 13.0-STABLE  | 72        | 2.28%   |
| FreeBSD 13.1-p2      | 71        | 2.25%   |
| FreeBSD 12.1-p8      | 69        | 2.19%   |
| FreeBSD 13.0-CURRENT | 66        | 2.09%   |
| FreeBSD 12.1         | 58        | 1.84%   |
| FreeBSD 12.1-p5      | 55        | 1.74%   |
| FreeBSD 13.1-p7      | 53        | 1.68%   |
| FreeBSD 12.2-p3      | 52        | 1.65%   |
| FreeBSD 12.1-STABLE  | 49        | 1.55%   |
| FreeBSD 12.1-p7      | 48        | 1.52%   |
| FreeBSD 13.0-p3      | 47        | 1.49%   |
| FreeBSD 12.2-p4      | 47        | 1.49%   |
| FreeBSD 13.0-p7      | 45        | 1.43%   |
| FreeBSD 14.0-p4      | 44        | 1.39%   |
| FreeBSD 13.0-p11     | 37        | 1.17%   |
| FreeBSD 12.2-p6      | 35        | 1.11%   |
| FreeBSD 13.1-STABLE  | 34        | 1.08%   |
| FreeBSD 13.2-p2      | 33        | 1.05%   |
| FreeBSD 13.0-p2      | 33        | 1.05%   |
| FreeBSD 12.2-STABLE  | 32        | 1.01%   |
| FreeBSD 13.1-p1      | 28        | 0.89%   |
| FreeBSD 13.0-p6      | 25        | 0.79%   |
| FreeBSD 13.2-p4      | 23        | 0.73%   |
| FreeBSD 12.3         | 23        | 0.73%   |
| FreeBSD 13.2-p3      | 22        | 0.7%    |
| FreeBSD 13.2-p1      | 22        | 0.7%    |
| FreeBSD 13.0-p10     | 22        | 0.7%    |
| FreeBSD 13.1-p4      | 21        | 0.67%   |
| FreeBSD 12.1-p6      | 21        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| FreeBSD | 2582      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2390      | 92.49%  |
| arm64   | 93        | 3.6%    |
| i386    | 80        | 3.1%    |
| arm     | 13        | 0.5%    |
| powerpc | 6         | 0.23%   |
| sparc64 | 1         | 0.04%   |
| riscv   | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 880       | 32.67%  |
| KDE5          | 445       | 16.52%  |
| XFCE          | 439       | 16.3%   |
| GNOME         | 189       | 7.02%   |
| TWM           | 188       | 6.98%   |
| MATE          | 143       | 5.31%   |
| i3            | 114       | 4.23%   |
| Openbox       | 69        | 2.56%   |
| LXQt          | 31        | 1.15%   |
| Cinnamon      | 31        | 1.15%   |
| AwesomeWM     | 28        | 1.04%   |
| Fluxbox       | 20        | 0.74%   |
| Enlightenment | 17        | 0.63%   |
| LXDE          | 16        | 0.59%   |
| Lumina        | 11        | 0.41%   |
| DWM           | 10        | 0.37%   |
| GNUstep       | 6         | 0.22%   |
| X-Cinnamon    | 5         | 0.19%   |
| Picom         | 5         | 0.19%   |
| xfwm          | 4         | 0.15%   |
| IceWM         | 4         | 0.15%   |
| CDE           | 4         | 0.15%   |
| Budgie        | 4         | 0.15%   |
| Window Maker  | 3         | 0.11%   |
| spectrwm      | 3         | 0.11%   |
| KDE           | 3         | 0.11%   |
| wlroots       | 2         | 0.07%   |
| sway          | 2         | 0.07%   |
| stumpwm       | 2         | 0.07%   |
| helloDesktop  | 2         | 0.07%   |
| Compton       | 2         | 0.07%   |
| xinitrc       | 1         | 0.04%   |
| Xfwm4         | 1         | 0.04%   |
| Potato        | 1         | 0.04%   |
| plasma        | 1         | 0.04%   |
| KWin          | 1         | 0.04%   |
| Hyprland      | 1         | 0.04%   |
| fvwm2         | 1         | 0.04%   |
| ctwm          | 1         | 0.04%   |
| bspwm         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1615      | 61.5%   |
| Console | 944       | 35.95%  |
| Wayland | 66        | 2.51%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1454      | 54.46%  |
| SDDM    | 437       | 16.37%  |
| SLiM    | 269       | 10.07%  |
| LightDM | 189       | 7.08%   |
| XDM     | 172       | 6.44%   |
| GDM     | 123       | 4.61%   |
| Ly      | 23        | 0.86%   |
| PCDM    | 2         | 0.07%   |
| WDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 1174      | 43.37%  |
| Unknown          | 676       | 24.97%  |
| en_US            | 379       | 14%     |
| ru_RU            | 135       | 4.99%   |
| de_DE            | 51        | 1.88%   |
| fr_FR            | 46        | 1.7%    |
| en_GB            | 35        | 1.29%   |
| zh_CN            | 17        | 0.63%   |
| en_CA            | 15        | 0.55%   |
| pt_BR            | 13        | 0.48%   |
| pl_PL            | 13        | 0.48%   |
| es_ES            | 11        | 0.41%   |
| ja_JP            | 10        | 0.37%   |
| uk_UA            | 9         | 0.33%   |
| en_AU            | 9         | 0.33%   |
| it_IT            | 8         | 0.3%    |
| en_IE            | 8         | 0.3%    |
| nb_NO            | 7         | 0.26%   |
| es_AR            | 5         | 0.18%   |
| en_US.ISO8859-1  | 5         | 0.18%   |
| cs_CZ            | 5         | 0.18%   |
| ru_RU.KOI8-R     | 4         | 0.15%   |
| fi_FI            | 4         | 0.15%   |
| en_NZ            | 4         | 0.15%   |
| el_GR            | 4         | 0.15%   |
| de_CH            | 4         | 0.15%   |
| en_US.US-ASCII   | 3         | 0.11%   |
| de_DE.ISO8859-1  | 3         | 0.11%   |
| zh_TW            | 2         | 0.07%   |
| sv_SE            | 2         | 0.07%   |
| pt_PT            | 2         | 0.07%   |
| nl_NL            | 2         | 0.07%   |
| ko_KR            | 2         | 0.07%   |
| it_IT.ISO8859-15 | 2         | 0.07%   |
| es_MX            | 2         | 0.07%   |
| en_SG            | 2         | 0.07%   |
| en_GB.US-ASCII   | 2         | 0.07%   |
| en_GB.ISO8859-1  | 2         | 0.07%   |
| de               | 2         | 0.07%   |
| zh_CN.GB2312     | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1688      | 64.7%   |
| BIOS | 921       | 35.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 1662      | 63.56%  |
| Ufs     | 947       | 36.21%  |
| Nfs     | 2         | 0.08%   |
| Cd9660  | 2         | 0.08%   |
| Xfs     | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2299      | 88.56%  |
| MBR     | 272       | 10.48%  |
| BSD     | 14        | 0.54%   |
| Unknown | 11        | 0.42%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 441       | 17.08%  |
| Dell                    | 367       | 14.21%  |
| ASUSTek Computer        | 327       | 12.66%  |
| Hewlett-Packard         | 228       | 8.83%   |
| Gigabyte Technology     | 147       | 5.69%   |
| ASRock                  | 115       | 4.45%   |
| MSI                     | 105       | 4.07%   |
| Unknown                 | 105       | 4.07%   |
| Supermicro              | 90        | 3.49%   |
| Intel                   | 88        | 3.41%   |
| Acer                    | 73        | 2.83%   |
| Apple                   | 55        | 2.13%   |
| Fujitsu                 | 32        | 1.24%   |
| Raspberry Pi Foundation | 27        | 1.05%   |
| Toshiba                 | 24        | 0.93%   |
| Samsung Electronics     | 20        | 0.77%   |
| IBM                     | 19        | 0.74%   |
| Google                  | 17        | 0.66%   |
| PC Engines              | 16        | 0.62%   |
| ASRockRack              | 16        | 0.62%   |
| System76                | 13        | 0.5%    |
| HUAWEI                  | 12        | 0.46%   |
| TUXEDO                  | 9         | 0.35%   |
| Sony                    | 9         | 0.35%   |
| Shuttle                 | 8         | 0.31%   |
| HPE                     | 8         | 0.31%   |
| AZW                     | 8         | 0.31%   |
| Alienware               | 7         | 0.27%   |
| Sun Microsystems        | 6         | 0.23%   |
| Panasonic               | 6         | 0.23%   |
| Notebook                | 6         | 0.23%   |
| Biostar                 | 6         | 0.23%   |
| AMI                     | 6         | 0.23%   |
| Gateway                 | 5         | 0.19%   |
| Framework               | 5         | 0.19%   |
| Deciso                  | 5         | 0.19%   |
| Cisco Systems           | 5         | 0.19%   |
| Beckhoff Automation     | 5         | 0.19%   |
| Wistron                 | 4         | 0.15%   |
| Timi                    | 4         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 110       | 4.26%   |
| ASUS All Series                  | 29        | 1.12%   |
| RPi Raspberry Pi                 | 26        | 1.01%   |
| Supermicro Super Server          | 24        | 0.93%   |
| Dell OEM-R 720xd                 | 13        | 0.5%    |
| HP ProLiant MicroServer Gen8     | 10        | 0.39%   |
| Intel Nobilis                    | 9         | 0.35%   |
| PC Engines APU2                  | 8         | 0.31%   |
| Dell PowerEdge R710              | 8         | 0.31%   |
| ASUS TUF GAMING X570-PLUS        | 7         | 0.27%   |
| MSI MS-7B89                      | 6         | 0.23%   |
| HP ProLiant MicroServer          | 6         | 0.23%   |
| ASRock Z590 Pro4                 | 6         | 0.23%   |
| MSI MS-7C02                      | 5         | 0.19%   |
| HP Z440 Workstation              | 5         | 0.19%   |
| HP EliteBook 840 G3              | 5         | 0.19%   |
| Gigabyte B360N WIFI              | 5         | 0.19%   |
| Framework Laptop                 | 5         | 0.19%   |
| Dell PowerEdge R720              | 5         | 0.19%   |
| Dell PowerEdge R610              | 5         | 0.19%   |
| Dell OptiPlex 9020               | 5         | 0.19%   |
| Dell OptiPlex 7050               | 5         | 0.19%   |
| Dell Latitude E7240              | 5         | 0.19%   |
| Dell Latitude E6430              | 5         | 0.19%   |
| ASRock X570 Phantom Gaming 4     | 5         | 0.19%   |
| System76 Lemur Pro               | 4         | 0.15%   |
| Supermicro X9SCL/X9SCM           | 4         | 0.15%   |
| Supermicro X10SLL-F              | 4         | 0.15%   |
| Sun Microsystems Sun Fire X4150  | 4         | 0.15%   |
| MSI MS-7693                      | 4         | 0.15%   |
| HPE ProLiant MicroServer Gen10   | 4         | 0.15%   |
| HP Z620 Workstation              | 4         | 0.15%   |
| HP Z420 Workstation              | 4         | 0.15%   |
| HP t620 Quad Core TC             | 4         | 0.15%   |
| HP EliteBook 8570p               | 4         | 0.15%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.15%   |
| Gigabyte X570 I AORUS PRO WIFI   | 4         | 0.15%   |
| Gigabyte B450M DS3H              | 4         | 0.15%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4         | 0.15%   |
| Dell XPS 13 9360                 | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 319       | 12.35%  |
| Unknown            | 110       | 4.26%   |
| Dell Latitude      | 86        | 3.33%   |
| Dell PowerEdge     | 64        | 2.48%   |
| Dell Inspiron      | 57        | 2.21%   |
| Dell OptiPlex      | 50        | 1.94%   |
| ASUS PRIME         | 49        | 1.9%    |
| Acer Aspire        | 42        | 1.63%   |
| Lenovo IdeaPad     | 40        | 1.55%   |
| Dell Precision     | 39        | 1.51%   |
| HP ProLiant        | 38        | 1.47%   |
| ASUS ROG           | 32        | 1.24%   |
| HP Compaq          | 29        | 1.12%   |
| ASUS TUF           | 29        | 1.12%   |
| ASUS All           | 29        | 1.12%   |
| RPi Raspberry      | 26        | 1.01%   |
| Supermicro Super   | 24        | 0.93%   |
| HP EliteBook       | 21        | 0.81%   |
| Dell XPS           | 21        | 0.81%   |
| HP ProBook         | 20        | 0.77%   |
| Lenovo ThinkCentre | 18        | 0.7%    |
| Toshiba Satellite  | 16        | 0.62%   |
| Dell Vostro        | 16        | 0.62%   |
| HP Pavilion        | 15        | 0.58%   |
| Dell OEM-R         | 13        | 0.5%    |
| ASRock X570        | 13        | 0.5%    |
| IBM System         | 12        | 0.46%   |
| HP Laptop          | 12        | 0.46%   |
| HP EliteDesk       | 10        | 0.39%   |
| Lenovo Legion      | 9         | 0.35%   |
| Intel Nobilis      | 9         | 0.35%   |
| Gigabyte X570      | 9         | 0.35%   |
| ASUS ZenBook       | 9         | 0.35%   |
| ASUS Pro           | 9         | 0.35%   |
| ASUS ASUS          | 9         | 0.35%   |
| PC Engines APU2    | 8         | 0.31%   |
| HPE ProLiant       | 8         | 0.31%   |
| HP ENVY            | 8         | 0.31%   |
| Gigabyte B450M     | 8         | 0.31%   |
| Fujitsu ESPRIMO    | 8         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 278       | 10.77%  |
| 2019    | 246       | 9.53%   |
| 2021    | 229       | 8.87%   |
| 2018    | 222       | 8.6%    |
| 2011    | 156       | 6.04%   |
| 2013    | 152       | 5.89%   |
| 2014    | 142       | 5.5%    |
| 2022    | 135       | 5.23%   |
| 2015    | 133       | 5.15%   |
| 2016    | 132       | 5.11%   |
| 2017    | 129       | 5%      |
| 2012    | 129       | 5%      |
| 2010    | 108       | 4.18%   |
| Unknown | 103       | 3.99%   |
| 2009    | 76        | 2.94%   |
| 2008    | 70        | 2.71%   |
| 2023    | 68        | 2.63%   |
| 2007    | 35        | 1.36%   |
| 2006    | 16        | 0.62%   |
| 2005    | 6         | 0.23%   |
| 2004    | 6         | 0.23%   |
| 2003    | 5         | 0.19%   |
| 2002    | 4         | 0.15%   |
| 2024    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1109      | 42.95%  |
| Notebook       | 1092      | 42.29%  |
| Server         | 197       | 7.63%   |
| Mini pc        | 78        | 3.02%   |
| System on chip | 57        | 2.21%   |
| Convertible    | 27        | 1.05%   |
| All in one     | 21        | 0.81%   |
| Tablet         | 1         | 0.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2531      | 98.02%  |
| Yes  | 51        | 1.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 683       | 26.09%  |
| 8.01-16.0       | 666       | 25.44%  |
| 32.01-64.0      | 381       | 14.55%  |
| 4.01-8.0        | 333       | 12.72%  |
| 64.01-256.0     | 243       | 9.28%   |
| 2.01-3.0        | 94        | 3.59%   |
| 3.01-4.0        | 55        | 2.1%    |
| 0.51-1.0        | 54        | 2.06%   |
| 24.01-32.0      | 53        | 2.02%   |
| More than 256.0 | 19        | 0.73%   |
| 1.01-2.0        | 18        | 0.69%   |
| 0.01-0.5        | 18        | 0.69%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 878       | 32.8%   |
| 0.51-1.0        | 824       | 30.78%  |
| 1.01-2.0        | 491       | 18.34%  |
| 2.01-3.0        | 129       | 4.82%   |
| 4.01-8.0        | 95        | 3.55%   |
| 3.01-4.0        | 78        | 2.91%   |
| 8.01-16.0       | 52        | 1.94%   |
| 0               | 33        | 1.23%   |
| 24.01-32.0      | 31        | 1.16%   |
| 32.01-64.0      | 23        | 0.86%   |
| 16.01-24.0      | 22        | 0.82%   |
| 64.01-256.0     | 19        | 0.71%   |
| More than 256.0 | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1252      | 46.4%   |
| 2      | 553       | 20.5%   |
| 0      | 251       | 9.3%    |
| 3      | 229       | 8.49%   |
| 4      | 144       | 5.34%   |
| 5      | 87        | 3.22%   |
| 6      | 58        | 2.15%   |
| 7      | 30        | 1.11%   |
| 8      | 20        | 0.74%   |
| 10     | 12        | 0.44%   |
| 12     | 11        | 0.41%   |
| 14     | 9         | 0.33%   |
| 11     | 8         | 0.3%    |
| 9      | 8         | 0.3%    |
| 18     | 3         | 0.11%   |
| 17     | 3         | 0.11%   |
| 58     | 2         | 0.07%   |
| 25     | 2         | 0.07%   |
| 24     | 2         | 0.07%   |
| 23     | 2         | 0.07%   |
| 16     | 2         | 0.07%   |
| 15     | 2         | 0.07%   |
| 13     | 2         | 0.07%   |
| 63     | 1         | 0.04%   |
| 40     | 1         | 0.04%   |
| 30     | 1         | 0.04%   |
| 28     | 1         | 0.04%   |
| 21     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1885      | 72.42%  |
| Yes       | 718       | 27.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2262      | 87.57%  |
| No        | 321       | 12.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1468      | 56.44%  |
| No        | 1133      | 43.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1521      | 58.34%  |
| Yes       | 1086      | 41.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 577       | 22.14%  |
| Russia      | 278       | 10.67%  |
| Germany     | 256       | 9.82%   |
| France      | 141       | 5.41%   |
| UK          | 97        | 3.72%   |
| Canada      | 96        | 3.68%   |
| Poland      | 93        | 3.57%   |
| China       | 58        | 2.23%   |
| Australia   | 58        | 2.23%   |
| Brazil      | 57        | 2.19%   |
| Netherlands | 54        | 2.07%   |
| Czechia     | 52        | 2%      |
| Ukraine     | 48        | 1.84%   |
| Switzerland | 44        | 1.69%   |
| Japan       | 41        | 1.57%   |
| Austria     | 38        | 1.46%   |
| Spain       | 37        | 1.42%   |
| Italy       | 37        | 1.42%   |
| Sweden      | 32        | 1.23%   |
| Indonesia   | 30        | 1.15%   |
| India       | 28        | 1.07%   |
| Norway      | 26        | 1%      |
| Romania     | 25        | 0.96%   |
| Finland     | 25        | 0.96%   |
| Ireland     | 20        | 0.77%   |
| Argentina   | 20        | 0.77%   |
| Greece      | 17        | 0.65%   |
| Thailand    | 16        | 0.61%   |
| Mexico      | 16        | 0.61%   |
| New Zealand | 15        | 0.58%   |
| Portugal    | 14        | 0.54%   |
| Hungary     | 14        | 0.54%   |
| Denmark     | 14        | 0.54%   |
| Bulgaria    | 14        | 0.54%   |
| Belgium     | 13        | 0.5%    |
| Taiwan      | 12        | 0.46%   |
| Croatia     | 11        | 0.42%   |
| Vietnam     | 10        | 0.38%   |
| Turkey      | 10        | 0.38%   |
| Slovenia    | 9         | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 103       | 3.69%   |
| Berlin        | 32        | 1.14%   |
| Vienna        | 31        | 1.11%   |
| Sydney        | 28        | 1%      |
| St Petersburg | 27        | 0.97%   |
| Brooklyn      | 27        | 0.97%   |
| Kyiv          | 23        | 0.82%   |
| Paris         | 22        | 0.79%   |
| Warsaw        | 18        | 0.64%   |
| Krasnodar     | 18        | 0.64%   |
| Gdynia        | 18        | 0.64%   |
| Amsterdam     | 17        | 0.61%   |
| Ludwigsburg   | 16        | 0.57%   |
| London        | 16        | 0.57%   |
| Grand Rapids  | 16        | 0.57%   |
| Chicago       | 16        | 0.57%   |
| Zurich        | 15        | 0.54%   |
| Prague        | 15        | 0.54%   |
| Montreal      | 15        | 0.54%   |
| Helsinki      | 15        | 0.54%   |
| Yekaterinburg | 14        | 0.5%    |
| Portland      | 14        | 0.5%    |
| Dublin        | 13        | 0.47%   |
| Tuklaty       | 12        | 0.43%   |
| Seattle       | 12        | 0.43%   |
| Jakarta       | 11        | 0.39%   |
| Ozersk        | 10        | 0.36%   |
| Madrid        | 10        | 0.36%   |
| Hamburg       | 10        | 0.36%   |
| Sofia         | 9         | 0.32%   |
| Shenzhen      | 9         | 0.32%   |
| Oslo          | 9         | 0.32%   |
| Novosibirsk   | 9         | 0.32%   |
| New York      | 9         | 0.32%   |
| Munich        | 9         | 0.32%   |
| Lexington     | 9         | 0.32%   |
| Brno          | 9         | 0.32%   |
| Athens        | 9         | 0.32%   |
| Toronto       | 8         | 0.29%   |
| Stockholm     | 8         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 669       | 2051   | 18.57%  |
| Samsung Electronics | 613       | 1221   | 17.01%  |
| Seagate             | 503       | 1308   | 13.96%  |
| Toshiba             | 229       | 500    | 6.36%   |
| Kingston            | 215       | 280    | 5.97%   |
| Crucial             | 199       | 314    | 5.52%   |
| Intel               | 149       | 289    | 4.14%   |
| Hitachi             | 110       | 284    | 3.05%   |
| SanDisk             | 103       | 143    | 2.86%   |
| HGST                | 96        | 359    | 2.66%   |
| A-DATA Technology   | 61        | 77     | 1.69%   |
| SK hynix            | 57        | 74     | 1.58%   |
| Micron Technology   | 47        | 78     | 1.3%    |
| Transcend           | 45        | 60     | 1.25%   |
| Hewlett-Packard     | 37        | 191    | 1.03%   |
| Phison              | 25        | 36     | 0.69%   |
| PNY                 | 22        | 33     | 0.61%   |
| SPCC                | 21        | 40     | 0.58%   |
| Apple               | 20        | 21     | 0.56%   |
| KIOXIA              | 19        | 19     | 0.53%   |
| Corsair             | 19        | 49     | 0.53%   |
| OCZ                 | 18        | 22     | 0.5%    |
| Gigabyte Technology | 15        | 21     | 0.42%   |
| KingSpec            | 14        | 20     | 0.39%   |
| Silicon Motion      | 12        | 14     | 0.33%   |
| LITEON              | 12        | 17     | 0.33%   |
| Fujitsu             | 12        | 18     | 0.33%   |
| GOODRAM             | 11        | 23     | 0.31%   |
| Patriot             | 10        | 15     | 0.28%   |
| Maxtor              | 10        | 14     | 0.28%   |
| OWC                 | 9         | 15     | 0.25%   |
| China               | 9         | 10     | 0.25%   |
| Apacer              | 9         | 9      | 0.25%   |
| Team                | 8         | 11     | 0.22%   |
| MidasForce          | 8         | 10     | 0.22%   |
| Lenovo              | 8         | 9      | 0.22%   |
| Intenso             | 8         | 9      | 0.22%   |
| FORESEE             | 8         | 8      | 0.22%   |
| SSSTC               | 7         | 10     | 0.19%   |
| Plextor             | 7         | 13     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 48        | 1.12%   |
| Samsung SSD 850 EVO 250GB          | 33        | 0.77%   |
| Samsung SSD 970 EVO Plus 1TB       | 25        | 0.58%   |
| Samsung SSD 850 EVO 500GB          | 25        | 0.58%   |
| WDC WD40EFRX-68N32N0 4TB           | 24        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB           | 24        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB     | 24        | 0.56%   |
| Samsung SSD 860 EVO 500GB          | 24        | 0.56%   |
| Kingston SA400S37120G 120GB        | 24        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 23        | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB           | 22        | 0.51%   |
| Kingston SA400S37480G 480GB        | 21        | 0.49%   |
| Crucial CT500MX500SSD1 500GB       | 21        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB     | 20        | 0.47%   |
| Samsung SSD 870 EVO 1TB            | 20        | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 19        | 0.44%   |
| Toshiba MQ01ABD100 1TB             | 18        | 0.42%   |
| Toshiba DT01ACA100 1TB             | 18        | 0.42%   |
| WDC WD800JD-75MSA3 80GB            | 17        | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB     | 17        | 0.4%    |
| Samsung SSD 860 EVO 1TB            | 17        | 0.4%    |
| HGST HTS721010A9E630 1TB           | 17        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 17        | 0.4%    |
| Seagate ST4000DM000-1F2168 4TB     | 16        | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB     | 16        | 0.37%   |
| Crucial CT250MX500SSD1 250GB       | 16        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB        | 16        | 0.37%   |
| Toshiba MQ01ABF050 500GB           | 14        | 0.33%   |
| WDC WD20EFRX-68EUZN0 2TB           | 13        | 0.3%    |
| Seagate ST1000DM003-1CH162 1TB     | 13        | 0.3%    |
| Samsung SSD 850 EVO 1TB            | 13        | 0.3%    |
| Kingston SV300S37A120G 120GB       | 13        | 0.3%    |
| WDC WD40EFRX-68WT0N0 4TB           | 12        | 0.28%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.28%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 0.28%   |
| Seagate ST4000VN008-2DR166 4TB     | 12        | 0.28%   |
| Samsung SSD 970 EVO 500GB          | 12        | 0.28%   |
| Crucial CT2000MX500SSD1 2TB        | 12        | 0.28%   |
| Seagate ST4000DM004-2CV104 4TB     | 11        | 0.26%   |
| Seagate ST2000LM007-1R8174 2TB     | 11        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| WDC                  | 537       | 1774   | 34.6%   |
| Seagate              | 493       | 1290   | 31.77%  |
| Toshiba              | 189       | 439    | 12.18%  |
| Hitachi              | 109       | 280    | 7.02%   |
| HGST                 | 96        | 355    | 6.19%   |
| Samsung Electronics  | 51        | 83     | 3.29%   |
| Hewlett-Packard      | 24        | 175    | 1.55%   |
| Fujitsu              | 12        | 18     | 0.77%   |
| Maxtor               | 10        | 14     | 0.64%   |
| Apple                | 7         | 8      | 0.45%   |
| HPE                  | 4         | 21     | 0.26%   |
| LSI                  | 3         | 6      | 0.19%   |
| IBM/Hitachi          | 2         | 2      | 0.13%   |
| HPT                  | 2         | 9      | 0.13%   |
| Dell                 | 2         | 5      | 0.13%   |
| Areca                | 2         | 3      | 0.13%   |
| Adaptec              | 2         | 12     | 0.13%   |
| WD MediaMax          | 1         | 3      | 0.06%   |
| SYNOLOGY             | 1         | 1      | 0.06%   |
| QUANTUM              | 1         | 2      | 0.06%   |
| NETAPP               | 1         | 2      | 0.06%   |
| MaxDigital           | 1         | 1      | 0.06%   |
| IBM                  | 1         | 1      | 0.06%   |
| ExcelStor Technology | 1         | 4      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 343       | 739    | 24.17%  |
| Kingston            | 179       | 232    | 12.61%  |
| Crucial             | 159       | 245    | 11.21%  |
| SanDisk             | 102       | 142    | 7.19%   |
| Intel               | 99        | 225    | 6.98%   |
| WDC                 | 80        | 132    | 5.64%   |
| A-DATA Technology   | 43        | 55     | 3.03%   |
| Transcend           | 40        | 53     | 2.82%   |
| Micron Technology   | 28        | 49     | 1.97%   |
| SK hynix            | 23        | 27     | 1.62%   |
| Toshiba             | 20        | 22     | 1.41%   |
| OCZ                 | 18        | 22     | 1.27%   |
| PNY                 | 17        | 27     | 1.2%    |
| SPCC                | 15        | 32     | 1.06%   |
| KingSpec            | 14        | 20     | 0.99%   |
| Corsair             | 13        | 17     | 0.92%   |
| Apple               | 13        | 13     | 0.92%   |
| LITEON              | 11        | 16     | 0.78%   |
| Patriot             | 10        | 15     | 0.7%    |
| Gigabyte Technology | 10        | 14     | 0.7%    |
| OWC                 | 9         | 15     | 0.63%   |
| China               | 9         | 10     | 0.63%   |
| Apacer              | 9         | 9      | 0.63%   |
| Seagate             | 8         | 11     | 0.56%   |
| MidasForce          | 8         | 10     | 0.56%   |
| Intenso             | 8         | 9      | 0.56%   |
| Hewlett-Packard     | 8         | 8      | 0.56%   |
| GOODRAM             | 8         | 19     | 0.56%   |
| Team                | 7         | 10     | 0.49%   |
| Plextor             | 5         | 8      | 0.35%   |
| Mushkin             | 5         | 5      | 0.35%   |
| Verbatim            | 4         | 4      | 0.28%   |
| Phison              | 4         | 5      | 0.28%   |
| LITEONIT            | 4         | 4      | 0.28%   |
| Lenovo              | 4         | 5      | 0.28%   |
| Hoodisk             | 4         | 6      | 0.28%   |
| Hikvision           | 4         | 5      | 0.28%   |
| Zheino              | 3         | 4      | 0.21%   |
| Vaseky              | 3         | 3      | 0.21%   |
| Supermicro          | 3         | 3      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1223      | 2354   | 39.31%  |
| HDD  | 1213      | 4508   | 38.99%  |
| NVMe | 675       | 1075   | 21.7%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1967      | 6862   | 74.45%  |
| NVMe | 675       | 1075   | 25.55%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1427      | 2769   | 51.95%  |
| 0.51-1.0   | 610       | 1195   | 22.21%  |
| 1.01-2.0   | 277       | 742    | 10.08%  |
| 3.01-4.0   | 162       | 757    | 5.9%    |
| 4.01-10.0  | 142       | 856    | 5.17%   |
| 2.01-3.0   | 88        | 321    | 3.2%    |
| 10.01-20.0 | 38        | 216    | 1.38%   |
| 20.01-50.0 | 3         | 6      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 818       | 30.31%  |
| 251-500        | 626       | 23.19%  |
| 501-1000       | 400       | 14.82%  |
| 51-100         | 275       | 10.19%  |
| 21-50          | 186       | 6.89%   |
| 1-20           | 135       | 5%      |
| 1001-2000      | 133       | 4.93%   |
| More than 3000 | 71        | 2.63%   |
| 2001-3000      | 30        | 1.11%   |
| Unknown        | 25        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1914      | 71.13%  |
| 21-50          | 365       | 13.56%  |
| 51-100         | 131       | 4.87%   |
| 101-250        | 107       | 3.98%   |
| 251-500        | 55        | 2.04%   |
| 501-1000       | 41        | 1.52%   |
| Unknown        | 25        | 0.93%   |
| More than 3000 | 24        | 0.89%   |
| 1001-2000      | 15        | 0.56%   |
| 2001-3000      | 12        | 0.45%   |
| 0              | 2         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 7         | 24     | 1.31%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 1.31%   |
| Samsung Electronics SSD 870 EVO 1TB | 7         | 9      | 1.31%   |
| HGST HTS725050A7E630 500GB          | 7         | 16     | 1.31%   |
| WDC WD40EFRX-68WT0N0 4TB            | 6         | 19     | 1.12%   |
| Seagate ST3500413AS 500GB           | 6         | 9      | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.12%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 12     | 0.93%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 4         | 4      | 0.75%   |
| Toshiba MQ01ABD100 1TB              | 4         | 4      | 0.75%   |
| Seagate ST9500420AS 500GB           | 4         | 6      | 0.75%   |
| Seagate ST9250315AS 250GB           | 4         | 5      | 0.75%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 7      | 0.75%   |
| Samsung Electronics HD501LJ 500GB   | 4         | 6      | 0.75%   |
| HGST HTS721010A9E630 1TB            | 4         | 22     | 0.75%   |
| Crucial CT525MX300SSD1 528GB        | 4         | 4      | 0.75%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 3         | 5      | 0.56%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 0.56%   |
| Seagate ST9500325AS 500GB           | 3         | 5      | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 0.56%   |
| Seagate ST380013AS 80GB             | 3         | 4      | 0.56%   |
| Seagate ST3500418AS 500GB           | 3         | 6      | 0.56%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.56%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 3      | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB      | 3         | 4      | 0.56%   |
| Samsung Electronics HD154UI 1.5TB   | 3         | 4      | 0.56%   |
| Samsung Electronics HD103UJ 1TB     | 3         | 6      | 0.56%   |
| Kingston SV300S37A120G 120GB        | 3         | 3      | 0.56%   |
| Kingston SNS4151S316GD 16GB         | 3         | 3      | 0.56%   |
| Intel SSDSA2M080G2GC 80GB           | 3         | 3      | 0.56%   |
| Hitachi HTS547550A9E384 500GB       | 3         | 3      | 0.56%   |
| Crucial CT480M500SSD1 480GB         | 3         | 4      | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.37%   |
| WDC WD5000LPLX-22ZNTT0 500GB        | 2         | 2      | 0.37%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 3      | 0.37%   |
| WDC WD5000AAKX-083CA0 500GB         | 2         | 2      | 0.37%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.37%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 5      | 0.37%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.37%   |
| WDC WD20EZRX-00D8PB0 2TB            | 2         | 3      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 124       | 179    | 24.51%  |
| WDC                  | 115       | 222    | 22.73%  |
| Samsung Electronics  | 47        | 62     | 9.29%   |
| Hitachi              | 41        | 67     | 8.1%    |
| Toshiba              | 37        | 66     | 7.31%   |
| Kingston             | 21        | 23     | 4.15%   |
| Intel                | 21        | 30     | 4.15%   |
| HGST                 | 17        | 47     | 3.36%   |
| Crucial              | 17        | 23     | 3.36%   |
| SanDisk              | 8         | 10     | 1.58%   |
| Micron Technology    | 7         | 13     | 1.38%   |
| Maxtor               | 7         | 11     | 1.38%   |
| A-DATA Technology    | 7         | 9      | 1.38%   |
| SK hynix             | 5         | 8      | 0.99%   |
| Hewlett-Packard      | 4         | 7      | 0.79%   |
| OCZ                  | 3         | 4      | 0.59%   |
| Fujitsu              | 3         | 6      | 0.59%   |
| Apple                | 3         | 3      | 0.59%   |
| Corsair              | 2         | 4      | 0.4%    |
| walram               | 1         | 1      | 0.2%    |
| Transcend            | 1         | 1      | 0.2%    |
| SSSTC                | 1         | 1      | 0.2%    |
| SPCC                 | 1         | 1      | 0.2%    |
| SMI                  | 1         | 1      | 0.2%    |
| Plextor              | 1         | 1      | 0.2%    |
| Phison               | 1         | 1      | 0.2%    |
| LITEON               | 1         | 1      | 0.2%    |
| Lexar                | 1         | 2      | 0.2%    |
| Lenovo               | 1         | 1      | 0.2%    |
| IBM/Hitachi          | 1         | 1      | 0.2%    |
| HPE                  | 1         | 4      | 0.2%    |
| GK                   | 1         | 1      | 0.2%    |
| Fanxiang             | 1         | 1      | 0.2%    |
| ExcelStor Technology | 1         | 2      | 0.2%    |
| Apacer               | 1         | 1      | 0.2%    |
| AMD                  | 1         | 2      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 123       | 178    | 33.24%  |
| WDC                  | 112       | 219    | 30.27%  |
| Hitachi              | 41        | 67     | 11.08%  |
| Toshiba              | 36        | 65     | 9.73%   |
| Samsung Electronics  | 23        | 31     | 6.22%   |
| HGST                 | 17        | 47     | 4.59%   |
| Maxtor               | 7         | 11     | 1.89%   |
| Hewlett-Packard      | 3         | 6      | 0.81%   |
| Fujitsu              | 3         | 6      | 0.81%   |
| Apple                | 2         | 2      | 0.54%   |
| IBM/Hitachi          | 1         | 1      | 0.27%   |
| HPE                  | 1         | 4      | 0.27%   |
| ExcelStor Technology | 1         | 2      | 0.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 345       | 639    | 72.03%  |
| SSD  | 130       | 174    | 27.14%  |
| NVMe | 4         | 4      | 0.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 14.29%  |
| Toshiba MG05ACA800E 8TB           | 1         | 1      | 14.29%  |
| SanDisk pSSD 16GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| Maxtor 6E040L0 40GB               | 1         | 1      | 14.29%  |
| Hitachi HUS724040ALE641 4TB       | 1         | 14     | 14.29%  |
| Crucial M4-CT256M4SSD1 256GB      | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Maxtor              | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 14     | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2131      | 6849   | 79.87%  |
| Malfunc  | 461       | 817    | 17.28%  |
| Detected | 69        | 251    | 2.59%   |
| Failed   | 7         | 20     | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1674      | 49.35%  |
| AMD                                     | 453       | 13.35%  |
| Samsung Electronics                     | 298       | 8.79%   |
| Broadcom / LSI                          | 169       | 4.98%   |
| SanDisk                                 | 121       | 3.57%   |
| ASMedia Technology                      | 70        | 2.06%   |
| Marvell Technology Group                | 64        | 1.89%   |
| Phison Electronics                      | 50        | 1.47%   |
| Kingston Technology Company             | 46        | 1.36%   |
| Silicon Motion                          | 45        | 1.33%   |
| Micron/Crucial Technology               | 43        | 1.27%   |
| SK hynix                                | 42        | 1.24%   |
| Nvidia                                  | 35        | 1.03%   |
| Toshiba                                 | 30        | 0.88%   |
| JMicron Technology                      | 28        | 0.83%   |
| Micron Technology                       | 25        | 0.74%   |
| KIOXIA                                  | 22        | 0.65%   |
| Adaptec                                 | 22        | 0.65%   |
| Hewlett-Packard                         | 19        | 0.56%   |
| ADATA Technology                        | 16        | 0.47%   |
| Realtek Semiconductor                   | 10        | 0.29%   |
| Silicon Image                           | 9         | 0.27%   |
| Solid State Storage Technology          | 8         | 0.24%   |
| VIA Technologies                        | 7         | 0.21%   |
| Union Memory (Shenzhen)                 | 7         | 0.21%   |
| Shenzhen Longsys Electronics            | 7         | 0.21%   |
| Areca Technology                        | 7         | 0.21%   |
| Silicon Integrated Systems [SiS]        | 6         | 0.18%   |
| Seagate Technology                      | 6         | 0.18%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.18%   |
| Chelsio Communications                  | 6         | 0.18%   |
| Lite-On Technology                      | 5         | 0.15%   |
| 3ware                                   | 5         | 0.15%   |
| Lenovo                                  | 4         | 0.12%   |
| Transcend                               | 3         | 0.09%   |
| Shenzhen Unionmemory Information System | 3         | 0.09%   |
| Integrated Technology Express           | 3         | 0.09%   |
| INNOGRIT                                | 3         | 0.09%   |
| Broadcom                                | 3         | 0.09%   |
| ULi Electronics                         | 2         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 289       | 7.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 161       | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 113       | 2.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 109       | 2.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 91        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 84        | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 81        | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 78        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 69        | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 67        | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 60        | 1.54%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 59        | 1.51%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 54        | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 49        | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                          | 45        | 1.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 45        | 1.15%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 43        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 43        | 1.1%    |
| Intel SATA Controller [RAID mode]                                              | 42        | 1.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 42        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 1.08%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 41        | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 41        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 40        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 40        | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 38        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 38        | 0.97%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 37        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 36        | 0.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 35        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 35        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 34        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 34        | 0.87%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 33        | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 32        | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 29        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 29        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 29        | 0.74%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 28        | 0.72%   |
| Phison E12 NVMe Controller                                                     | 27        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1848      | 54.74%  |
| NVMe | 794       | 23.52%  |
| IDE  | 361       | 10.69%  |
| RAID | 231       | 6.84%   |
| SAS  | 105       | 3.11%   |
| SCSI | 37        | 1.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 1920      | 74.16%  |
| AMD                | 549       | 21.21%  |
| ARM                | 94        | 3.63%   |
| Unknown            | 15        | 0.58%   |
| IBM                | 3         | 0.12%   |
| VIA                | 1         | 0.04%   |
| Sun                | 1         | 0.04%   |
| Rockchip           | 1         | 0.04%   |
| Research           | 1         | 0.04%   |
| NXP                | 1         | 0.04%   |
| Motorola           | 1         | 0.04%   |
| i                  | 1         | 0.04%   |
| Baikal Electronics | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                     | 33        | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 25        | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 23        | 0.88%   |
| ARM Cortex-A53 r0p4                     | 23        | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 19        | 0.73%   |
| Intel CPU Version                       | 18        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 18        | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 17        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 17        | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 17        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 16        | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 16        | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 0.61%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 15        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 15        | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 15        | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 15        | 0.58%   |
|                                         | 15        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 14        | 0.54%   |
| ARM Cortex-A55 r2p0                     | 14        | 0.54%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 14        | 0.54%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 13        | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz        | 12        | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 12        | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 12        | 0.46%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 12        | 0.46%   |
| AMD GX-412TC SOC                        | 12        | 0.46%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 11        | 0.42%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 11        | 0.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 11        | 0.42%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 11        | 0.42%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 11        | 0.42%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 11        | 0.42%   |
| AMD FX-8350 Eight-Core Processor        | 11        | 0.42%   |
| Intel Xeon                              | 10        | 0.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 0.38%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 10        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 511       | 19.69%  |
| Intel Core i7          | 428       | 16.49%  |
| Intel Xeon             | 275       | 10.6%   |
| Other                  | 187       | 7.21%   |
| AMD Ryzen 7            | 130       | 5.01%   |
| Intel Celeron          | 120       | 4.62%   |
| Intel Core i3          | 119       | 4.59%   |
| AMD Ryzen 5            | 98        | 3.78%   |
| ARM Cortex             | 86        | 3.31%   |
| Intel Core 2 Duo       | 80        | 3.08%   |
| Intel Atom             | 61        | 2.35%   |
| Intel Pentium          | 48        | 1.85%   |
| AMD Ryzen 9            | 47        | 1.81%   |
| AMD Ryzen 3            | 29        | 1.12%   |
| AMD FX                 | 29        | 1.12%   |
| AMD GX                 | 24        | 0.92%   |
| AMD Ryzen 7 PRO        | 17        | 0.66%   |
| Intel Xeon Silver      | 15        | 0.58%   |
| Intel Pentium 4        | 15        | 0.58%   |
| Intel Core 2 Quad      | 15        | 0.58%   |
| Intel Core 2           | 14        | 0.54%   |
| AMD Ryzen 5 PRO        | 14        | 0.54%   |
| Intel Pentium M        | 13        | 0.5%    |
| Intel Core i9          | 13        | 0.5%    |
| AMD EPYC               | 13        | 0.5%    |
| AMD Opteron            | 12        | 0.46%   |
| AMD Ryzen Threadripper | 11        | 0.42%   |
| Intel Pentium Silver   | 9         | 0.35%   |
| AMD Athlon 64 X2       | 9         | 0.35%   |
| AMD Athlon             | 9         | 0.35%   |
| AMD Turion II Neo      | 7         | 0.27%   |
| AMD Phenom II X6       | 7         | 0.27%   |
| AMD E                  | 7         | 0.27%   |
| AMD A4                 | 7         | 0.27%   |
| AMD A10                | 7         | 0.27%   |
| Intel Genuine          | 6         | 0.23%   |
| AMD Phenom II X4       | 6         | 0.23%   |
| AMD Phenom             | 6         | 0.23%   |
| AMD A8                 | 6         | 0.23%   |
| AMD A6                 | 6         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 835       | 32.14%  |
| 2       | 706       | 27.17%  |
| Unknown | 243       | 9.35%   |
| 8       | 192       | 7.39%   |
| 16      | 175       | 6.74%   |
| 6       | 155       | 5.97%   |
| 12      | 111       | 4.27%   |
| 1       | 60        | 2.31%   |
| 24      | 35        | 1.35%   |
| 32      | 32        | 1.23%   |
| 10      | 21        | 0.81%   |
| 20      | 13        | 0.5%    |
| 64      | 5         | 0.19%   |
| 14      | 3         | 0.12%   |
| 48      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 3       | 2         | 0.08%   |
| 128     | 1         | 0.04%   |
| 40      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 22      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2331      | 90.07%  |
| 2       | 149       | 5.76%   |
| Unknown | 107       | 4.13%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1295      | 49.96%  |
| 1       | 1025      | 39.54%  |
| Unknown | 272       | 10.49%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 379       | 14.62%  |
| Unknown         | 238       | 9.18%   |
| Haswell         | 210       | 8.1%    |
| IvyBridge       | 204       | 7.87%   |
| SandyBridge     | 178       | 6.86%   |
| Skylake         | 161       | 6.21%   |
| Zen 2           | 116       | 4.47%   |
| Penryn          | 94        | 3.63%   |
| Broadwell       | 93        | 3.59%   |
| Westmere        | 81        | 3.12%   |
| Zen 3           | 80        | 3.09%   |
| Zen+            | 73        | 2.82%   |
| Core            | 68        | 2.62%   |
| Silvermont      | 67        | 2.58%   |
| CometLake       | 67        | 2.58%   |
| Zen             | 59        | 2.28%   |
| TigerLake       | 57        | 2.2%    |
| Bonnell         | 54        | 2.08%   |
| K10             | 40        | 1.54%   |
| Piledriver      | 36        | 1.39%   |
| Nehalem         | 34        | 1.31%   |
| Puma            | 28        | 1.08%   |
| Goldmont plus   | 27        | 1.04%   |
| NetBurst        | 24        | 0.93%   |
| P6              | 19        | 0.73%   |
| Goldmont        | 19        | 0.73%   |
| Excavator       | 18        | 0.69%   |
| Bobcat          | 17        | 0.66%   |
| K8 Hammer       | 16        | 0.62%   |
| Jaguar          | 13        | 0.5%    |
| IceLake         | 10        | 0.39%   |
| Bulldozer       | 4         | 0.15%   |
| Steamroller     | 3         | 0.12%   |
| K8 & K10 hybrid | 2         | 0.08%   |
| K10 Llano       | 2         | 0.08%   |
| Geode           | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1330      | 48.56%  |
| Nvidia                                       | 611       | 22.31%  |
| AMD                                          | 549       | 20.04%  |
| Matrox Electronics Systems                   | 150       | 5.48%   |
| ASPEED Technology                            | 87        | 3.18%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.11%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.07%   |
| VIA Technologies                             | 2         | 0.07%   |
| S3 Graphics                                  | 2         | 0.07%   |
| Silicon Motion                               | 1         | 0.04%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.04%   |
| Huawei Technologies                          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 109       | 3.86%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 87        | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 3.01%   |
| Intel UHD Graphics 620                                                                   | 65        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 55        | 1.95%   |
| Intel HD Graphics 5500                                                                   | 55        | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.91%   |
| Intel HD Graphics 620                                                                    | 52        | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 50        | 1.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.66%   |
| Intel HD Graphics 530                                                                    | 46        | 1.63%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 45        | 1.59%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 44        | 1.56%   |
| Intel HD Graphics 630                                                                    | 42        | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 40        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 37        | 1.31%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 36        | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 36        | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.17%   |
| Matrox Electronics Systems G200eR2                                                       | 32        | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 32        | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 1.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 31        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 28        | 0.99%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 26        | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 0.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 24        | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 24        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.81%   |
| AMD Lucienne                                                                             | 23        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 22        | 0.78%   |
| Matrox Electronics Systems MGA G200EH                                                    | 22        | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 21        | 0.74%   |
| AMD ES1000                                                                               | 21        | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 989       | 38.04%  |
| 1 x AMD                                  | 455       | 17.5%   |
| 1 x Nvidia                               | 377       | 14.5%   |
| Intel + Nvidia                           | 197       | 7.58%   |
| 1 x Matrox                               | 149       | 5.73%   |
| Other                                    | 138       | 5.31%   |
| 2 x Intel                                | 99        | 3.81%   |
| 1 x ASPEED                               | 75        | 2.88%   |
| Intel + AMD                              | 41        | 1.58%   |
| 2 x AMD                                  | 27        | 1.04%   |
| AMD + Nvidia                             | 21        | 0.81%   |
| Nvidia + ASPEED                          | 10        | 0.38%   |
| 2 x Nvidia                               | 5         | 0.19%   |
| 1 x SiS                                  | 3         | 0.12%   |
| 1 x XGI                                  | 2         | 0.08%   |
| 1 x VIA                                  | 2         | 0.08%   |
| 1 x S3 Graphics                          | 2         | 0.08%   |
| AMD + ASPEED                             | 2         | 0.08%   |
| 1 x Silicon Motion                       | 1         | 0.04%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.04%   |
| Nvidia + Huawei Technologies             | 1         | 0.04%   |
| Intel + Matrox                           | 1         | 0.04%   |
| Intel + ASPEED                           | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2055      | 78.86%  |
| Proprietary | 399       | 15.31%  |
| Unknown     | 152       | 5.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1980      | 75.26%  |
| 1.01-2.0   | 155       | 5.89%   |
| 0.01-0.5   | 142       | 5.4%    |
| 0.51-1.0   | 97        | 3.69%   |
| 3.01-4.0   | 95        | 3.61%   |
| 7.01-8.0   | 85        | 3.23%   |
| 5.01-6.0   | 39        | 1.48%   |
| 8.01-16.0  | 20        | 0.76%   |
| 2.01-3.0   | 15        | 0.57%   |
| 4.01-5.0   | 2         | 0.08%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 186       | 11.76%  |
| Samsung Electronics     | 163       | 10.3%   |
| LG Display              | 152       | 9.61%   |
| Dell                    | 131       | 8.28%   |
| BOE                     | 106       | 6.7%    |
| Chimei Innolux          | 104       | 6.57%   |
| Goldstar                | 76        | 4.8%    |
| Lenovo                  | 59        | 3.73%   |
| Hewlett-Packard         | 52        | 3.29%   |
| Acer                    | 51        | 3.22%   |
| AOC                     | 43        | 2.72%   |
| Philips                 | 31        | 1.96%   |
| BenQ                    | 31        | 1.96%   |
| Apple                   | 31        | 1.96%   |
| Sharp                   | 29        | 1.83%   |
| Ancor Communications    | 28        | 1.77%   |
| Iiyama                  | 26        | 1.64%   |
| ViewSonic               | 22        | 1.39%   |
| LG Electronics          | 21        | 1.33%   |
| Sony                    | 14        | 0.88%   |
| InfoVision              | 13        | 0.82%   |
| Chi Mei Optoelectronics | 12        | 0.76%   |
| NEC Computers           | 11        | 0.7%    |
| Eizo                    | 10        | 0.63%   |
| Unknown                 | 9         | 0.57%   |
| ASUSTek Computer        | 9         | 0.57%   |
| PANDA                   | 8         | 0.51%   |
| LGD                     | 8         | 0.51%   |
| Idek Iiyama             | 8         | 0.51%   |
| Sceptre Tech            | 7         | 0.44%   |
| LG Philips              | 7         | 0.44%   |
| CSO                     | 7         | 0.44%   |
| Unknown                 | 7         | 0.44%   |
| Toshiba                 | 6         | 0.38%   |
| MSI                     | 6         | 0.38%   |
| Panasonic               | 5         | 0.32%   |
| JDI                     | 5         | 0.32%   |
| BOE Technology Group    | 5         | 0.32%   |
| Lenovo Group Limited    | 4         | 0.25%   |
| HPN                     | 4         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 11        | 0.66%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 7         | 0.42%   |
| Unknown                                                              | 7         | 0.42%   |
| MSI G241 MSI3BA4 1920x1080 530x300mm 24.0-inch                       | 6         | 0.36%   |
| Iiyama PL2775HD IVM6604 1920x1080 600x340mm 27.2-inch                | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 6         | 0.36%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 5         | 0.3%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 5         | 0.3%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5         | 0.3%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 5         | 0.3%    |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 5         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 5         | 0.3%    |
| BOE Technology Group LCD Monitor 1920x1080                           | 5         | 0.3%    |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 5         | 0.3%    |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 4         | 0.24%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.24%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.24%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.24%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 4         | 0.24%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 4         | 0.24%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch             | 4         | 0.24%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.24%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.24%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 4         | 0.24%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 4         | 0.24%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14A8 1920x1080 310x170mm 13.9-inch     | 4         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 668       | 43.12%  |
| 1366x768 (WXGA)    | 231       | 14.91%  |
| 3840x2160 (4K)     | 102       | 6.58%   |
| 2560x1440 (QHD)    | 91        | 5.87%   |
| 1920x1200 (WUXGA)  | 73        | 4.71%   |
| 1600x900 (HD+)     | 62        | 4%      |
| 1280x1024 (SXGA)   | 47        | 3.03%   |
| 1280x800 (WXGA)    | 36        | 2.32%   |
| Unknown            | 30        | 1.94%   |
| 1680x1050 (WSXGA+) | 27        | 1.74%   |
| 1440x900 (WXGA+)   | 25        | 1.61%   |
| 2560x1080          | 19        | 1.23%   |
| 3440x1440          | 17        | 1.1%    |
| 1024x600           | 17        | 1.1%    |
| 2560x1600          | 15        | 0.97%   |
| 1024x768 (XGA)     | 9         | 0.58%   |
| 3840x1080          | 7         | 0.45%   |
| 1600x1200          | 7         | 0.45%   |
| 2256x1504          | 6         | 0.39%   |
| 3200x1800 (QHD+)   | 5         | 0.32%   |
| 1920x540           | 4         | 0.26%   |
| 3840x1200          | 3         | 0.19%   |
| 3000x2000          | 3         | 0.19%   |
| 2880x1800          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 1360x768           | 3         | 0.19%   |
| 5760x1080          | 2         | 0.13%   |
| 3840x1600          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 8960x1440          | 1         | 0.06%   |
| 7860x2400          | 1         | 0.06%   |
| 7680x2160          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1256          | 1         | 0.06%   |
| 5760x1200          | 1         | 0.06%   |
| 5440x1080          | 1         | 0.06%   |
| 5120x1440          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 302       | 19.24%  |
| 15      | 274       | 17.45%  |
| Unknown | 157       | 10%     |
| 24      | 138       | 8.79%   |
| 27      | 129       | 8.22%   |
| 21      | 79        | 5.03%   |
| 23      | 74        | 4.71%   |
| 12      | 70        | 4.46%   |
| 17      | 51        | 3.25%   |
| 19      | 43        | 2.74%   |
| 14      | 36        | 2.29%   |
| 31      | 31        | 1.97%   |
| 11      | 27        | 1.72%   |
| 34      | 20        | 1.27%   |
| 22      | 19        | 1.21%   |
| 18      | 19        | 1.21%   |
| 10      | 14        | 0.89%   |
| 20      | 12        | 0.76%   |
| 29      | 9         | 0.57%   |
| 26      | 5         | 0.32%   |
| 25      | 5         | 0.32%   |
| 64      | 4         | 0.25%   |
| 46      | 4         | 0.25%   |
| 42      | 4         | 0.25%   |
| 32      | 4         | 0.25%   |
| 9       | 4         | 0.25%   |
| 52      | 3         | 0.19%   |
| 43      | 3         | 0.19%   |
| 40      | 3         | 0.19%   |
| 28      | 3         | 0.19%   |
| 16      | 3         | 0.19%   |
| 54      | 2         | 0.13%   |
| 49      | 2         | 0.13%   |
| 48      | 2         | 0.13%   |
| 41      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 35      | 2         | 0.13%   |
| 33      | 2         | 0.13%   |
| 74      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 520       | 33.57%  |
| 501-600     | 324       | 20.92%  |
| 201-300     | 226       | 14.59%  |
| Unknown     | 157       | 10.14%  |
| 401-500     | 146       | 9.43%   |
| 601-700     | 54        | 3.49%   |
| 351-400     | 54        | 3.49%   |
| 701-800     | 26        | 1.68%   |
| 1001-1500   | 20        | 1.29%   |
| 901-1000    | 10        | 0.65%   |
| 801-900     | 7         | 0.45%   |
| 101-200     | 3         | 0.19%   |
| 1501-2000   | 1         | 0.06%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1022      | 70.24%  |
| 16/10   | 157       | 10.79%  |
| Unknown | 147       | 10.1%   |
| 5/4     | 37        | 2.54%   |
| 21/9    | 31        | 2.13%   |
| 3/2     | 26        | 1.79%   |
| 4/3     | 25        | 1.72%   |
| 6/5     | 3         | 0.21%   |
| 32/9    | 2         | 0.14%   |
| 3.18    | 1         | 0.07%   |
| 11/10   | 1         | 0.07%   |
| 1.96    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |
| 0.46    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 276       | 17.7%   |
| 201-250        | 251       | 16.1%   |
| 91-100         | 207       | 13.28%  |
| Unknown        | 157       | 10.07%  |
| 301-350        | 136       | 8.72%   |
| 61-70          | 70        | 4.49%   |
| 101-110        | 70        | 4.49%   |
| 351-500        | 65        | 4.17%   |
| 151-200        | 61        | 3.91%   |
| 251-300        | 55        | 3.53%   |
| 71-80          | 47        | 3.01%   |
| 141-150        | 34        | 2.18%   |
| 121-130        | 34        | 2.18%   |
| 51-60          | 27        | 1.73%   |
| 501-1000       | 22        | 1.41%   |
| 41-50          | 15        | 0.96%   |
| More than 1000 | 14        | 0.9%    |
| 111-120        | 11        | 0.71%   |
| 1-40           | 4         | 0.26%   |
| 131-140        | 3         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 448       | 29.32%  |
| 121-160       | 425       | 27.81%  |
| 101-120       | 327       | 21.4%   |
| Unknown       | 157       | 10.27%  |
| 161-240       | 123       | 8.05%   |
| More than 240 | 37        | 2.42%   |
| 1-50          | 11        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1281      | 48.47%  |
| 0     | 1151      | 43.55%  |
| 2     | 191       | 7.23%   |
| 3     | 18        | 0.68%   |
| 4     | 2         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1557      | 43.92%  |
| Realtek Semiconductor             | 990       | 27.93%  |
| Qualcomm Atheros                  | 283       | 7.98%   |
| Broadcom                          | 281       | 7.93%   |
| Marvell Technology Group          | 38        | 1.07%   |
| TP-Link                           | 36        | 1.02%   |
| Ralink Technology                 | 32        | 0.9%    |
| Ralink                            | 20        | 0.56%   |
| Mellanox Technologies             | 19        | 0.54%   |
| MediaTek                          | 19        | 0.54%   |
| Nvidia                            | 15        | 0.42%   |
| Samsung Electronics               | 14        | 0.39%   |
| Edimax Technology                 | 14        | 0.39%   |
| Xiaomi                            | 12        | 0.34%   |
| Sierra Wireless                   | 12        | 0.34%   |
| D-Link System                     | 11        | 0.31%   |
| Aquantia                          | 10        | 0.28%   |
| VIA Technologies                  | 9         | 0.25%   |
| Hewlett-Packard                   | 9         | 0.25%   |
| Ericsson Business Mobile Networks | 9         | 0.25%   |
| Dell                              | 9         | 0.25%   |
| American Megatrends               | 8         | 0.23%   |
| IBM                               | 6         | 0.17%   |
| Huawei Technologies               | 6         | 0.17%   |
| Google                            | 6         | 0.17%   |
| Chelsio Communications            | 6         | 0.17%   |
| ASUSTek Computer                  | 6         | 0.17%   |
| Apple                             | 6         | 0.17%   |
| Qualcomm                          | 5         | 0.14%   |
| D-Link                            | 5         | 0.14%   |
| Arduino SA                        | 5         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.11%   |
| NetGear                           | 4         | 0.11%   |
| Emulex                            | 4         | 0.11%   |
| 3Com                              | 4         | 0.11%   |
| Qualcomm Technologies             | 3         | 0.08%   |
| JMicron Technology                | 3         | 0.08%   |
| IMC Networks                      | 3         | 0.08%   |
| Dresden Elektronik                | 3         | 0.08%   |
| Cisco Systems                     | 3         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 716       | 16.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 146       | 3.33%   |
| Intel I211 Gigabit Network Connection                                  | 110       | 2.51%   |
| Intel Wireless 8265 / 8275                                             | 105       | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 101       | 2.31%   |
| Intel Wi-Fi 6 AX200                                                    | 97        | 2.21%   |
| Intel I210 Gigabit Network Connection                                  | 81        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 68        | 1.55%   |
| Intel 82574L Gigabit Network Connection                                | 66        | 1.51%   |
| Intel Wireless 8260                                                    | 65        | 1.48%   |
| Intel Wireless 7265                                                    | 62        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                      | 61        | 1.39%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 61        | 1.39%   |
| Intel I350 Gigabit Network Connection                                  | 53        | 1.21%   |
| Intel Ethernet Connection I217-LM                                      | 51        | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 47        | 1.07%   |
| Intel Wireless 7260                                                    | 46        | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 39        | 0.89%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 39        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 39        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 36        | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 36        | 0.82%   |
| Intel Ethernet Controller I225-V                                       | 36        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                  | 36        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 35        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 32        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 32        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                   | 30        | 0.68%   |
| Intel Ethernet Connection I219-LM                                      | 29        | 0.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                   | 28        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                | 28        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 27        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 26        | 0.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 26        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                  | 26        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 26        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                   | 25        | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 24        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 24        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 925       | 57.31%  |
| Qualcomm Atheros                      | 232       | 14.37%  |
| Realtek Semiconductor                 | 180       | 11.15%  |
| Broadcom                              | 106       | 6.57%   |
| TP-Link                               | 36        | 2.23%   |
| Ralink Technology                     | 32        | 1.98%   |
| Ralink                                | 20        | 1.24%   |
| MediaTek                              | 18        | 1.12%   |
| Edimax Technology                     | 14        | 0.87%   |
| Sierra Wireless                       | 9         | 0.56%   |
| ASUSTek Computer                      | 6         | 0.37%   |
| D-Link System                         | 5         | 0.31%   |
| D-Link                                | 5         | 0.31%   |
| NetGear                               | 4         | 0.25%   |
| Dell                                  | 4         | 0.25%   |
| Qualcomm Technologies                 | 3         | 0.19%   |
| IMC Networks                          | 3         | 0.19%   |
| Qualcomm Atheros Communications       | 2         | 0.12%   |
| Atheros                               | 2         | 0.12%   |
| AboCom Systems                        | 2         | 0.12%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Sagem                                 | 1         | 0.06%   |
| Marvell Technology Group              | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| BUFFALO                               | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 105       | 6.43%   |
| Intel Wi-Fi 6 AX200                                                     | 97        | 5.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 4.17%   |
| Intel Wireless 8260                                                     | 65        | 3.98%   |
| Intel Wireless 7265                                                     | 62        | 3.8%    |
| Intel Wi-Fi 6 AX201                                                     | 47        | 2.88%   |
| Intel Wireless 7260                                                     | 46        | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 2.39%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 39        | 2.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 36        | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 36        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 35        | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 32        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 32        | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 26        | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 26        | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 1.47%   |
| Intel Wireless 3165                                                     | 22        | 1.35%   |
| Intel Centrino Ultimate-N 6300                                          | 21        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 1.23%   |
| Intel Wireless 3160                                                     | 19        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 0.98%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 15        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 14        | 0.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 14        | 0.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.74%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.74%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 12        | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 12        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 0.67%   |
| Intel WiFi Link 5100                                                    | 11        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1100      | 44.64%  |
| Realtek Semiconductor                  | 896       | 36.36%  |
| Broadcom                               | 208       | 8.44%   |
| Qualcomm Atheros                       | 79        | 3.21%   |
| Marvell Technology Group               | 37        | 1.5%    |
| Nvidia                                 | 15        | 0.61%   |
| Samsung Electronics                    | 14        | 0.57%   |
| Xiaomi                                 | 12        | 0.49%   |
| Aquantia                               | 10        | 0.41%   |
| VIA Technologies                       | 9         | 0.37%   |
| American Megatrends                    | 8         | 0.32%   |
| D-Link System                          | 6         | 0.24%   |
| Chelsio Communications                 | 6         | 0.24%   |
| Qualcomm                               | 5         | 0.2%    |
| Google                                 | 5         | 0.2%    |
| Apple                                  | 5         | 0.2%    |
| Emulex                                 | 4         | 0.16%   |
| 3Com                                   | 4         | 0.16%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.12%   |
| JMicron Technology                     | 3         | 0.12%   |
| Cisco Systems                          | 3         | 0.12%   |
| AMD                                    | 3         | 0.12%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.08%   |
| Solarflare Communications              | 2         | 0.08%   |
| QLogic                                 | 2         | 0.08%   |
| OPPO Electronics                       | 2         | 0.08%   |
| MYRICOM                                | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| Huawei Technologies                    | 2         | 0.08%   |
| ADMtek                                 | 2         | 0.08%   |
| Accton Technology                      | 2         | 0.08%   |
| U.S. Robotics                          | 1         | 0.04%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Realtek                                | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 716       | 27.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 146       | 5.53%   |
| Intel I211 Gigabit Network Connection                                         | 110       | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 101       | 3.83%   |
| Intel I210 Gigabit Network Connection                                         | 81        | 3.07%   |
| Intel 82574L Gigabit Network Connection                                       | 66        | 2.5%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 61        | 2.31%   |
| Realtek RTL8125 2.5GbE Controller                                             | 56        | 2.12%   |
| Intel I350 Gigabit Network Connection                                         | 53        | 2.01%   |
| Intel Ethernet Connection I217-LM                                             | 51        | 1.93%   |
| Intel Ethernet Connection (2) I219-LM                                         | 39        | 1.48%   |
| Intel Ethernet Controller I225-V                                              | 36        | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                                         | 36        | 1.36%   |
| Intel Ethernet Connection (4) I219-V                                          | 30        | 1.14%   |
| Intel Ethernet Connection I219-LM                                             | 29        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 28        | 1.06%   |
| Intel 82579V Gigabit Network Connection                                       | 28        | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                         | 26        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                          | 25        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 23        | 0.87%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 23        | 0.87%   |
| Intel 82576 Gigabit Network Connection                                        | 20        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                         | 18        | 0.68%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 17        | 0.64%   |
| Intel Ethernet Connection I218-LM                                             | 15        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                                      | 15        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 14        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                          | 14        | 0.53%   |
| Nvidia MCP79 Ethernet                                                         | 13        | 0.49%   |
| Intel Ethernet Controller X550                                                | 13        | 0.49%   |
| Intel Ethernet Connection I219-V                                              | 13        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                          | 13        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 13        | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                         | 12        | 0.45%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 12        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 11        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 11        | 0.42%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 11        | 0.42%   |
| Intel Ethernet Connection I217-V                                              | 11        | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 11        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2264      | 58.93%  |
| WiFi     | 1470      | 38.26%  |
| Unknown  | 57        | 1.48%   |
| Modem    | 51        | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1950      | 67.59%  |
| WiFi     | 920       | 31.89%  |
| Unknown  | 10        | 0.35%   |
| Modem    | 5         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1343      | 51.61%  |
| 1     | 820       | 31.51%  |
| 3     | 148       | 5.69%   |
| 4     | 122       | 4.69%   |
| 0     | 102       | 3.92%   |
| 6     | 28        | 1.08%   |
| 5     | 23        | 0.88%   |
| 8     | 7         | 0.27%   |
| 7     | 5         | 0.19%   |
| 10    | 3         | 0.12%   |
| 9     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2354      | 89.37%  |
| Yes  | 280       | 10.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 663       | 60.16%  |
| Broadcom                        | 69        | 6.26%   |
| Realtek Semiconductor           | 65        | 5.9%    |
| Qualcomm Atheros Communications | 62        | 5.63%   |
| Apple                           | 53        | 4.81%   |
| Cambridge Silicon Radio         | 38        | 3.45%   |
| IMC Networks                    | 29        | 2.63%   |
| Foxconn / Hon Hai               | 26        | 2.36%   |
| Lite-On Technology              | 21        | 1.91%   |
| ASUSTek Computer                | 19        | 1.72%   |
| Dell                            | 16        | 1.45%   |
| Hewlett-Packard                 | 12        | 1.09%   |
| Skylight Digital                | 5         | 0.45%   |
| MediaTek                        | 4         | 0.36%   |
| Alps Electric                   | 4         | 0.36%   |
| Ralink                          | 3         | 0.27%   |
| USI                             | 2         | 0.18%   |
| TP-Link                         | 2         | 0.18%   |
| Toshiba                         | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Esel International              | 1         | 0.09%   |
| Creative Technology             | 1         | 0.09%   |
| Corsair                         | 1         | 0.09%   |
| Unknown                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 251       | 22.71%  |
| Intel AX201 Bluetooth                                       | 110       | 9.95%   |
| Intel AX200 Bluetooth                                       | 95        | 8.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 91        | 8.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 38        | 3.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 35        | 3.17%   |
| Realtek Bluetooth Adapter                                   | 31        | 2.81%   |
| Apple Bluetooth Host Controller                             | 28        | 2.53%   |
| Intel Wireless-AC 3168 Bluetooth                            | 25        | 2.26%   |
| Intel AX210 Bluetooth                                       | 24        | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 24        | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 22        | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.27%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 14        | 1.27%   |
| Realtek  Bluetooth 4.2 Adapter                              | 13        | 1.18%   |
| Intel AX211 Bluetooth                                       | 13        | 1.18%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 11        | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 11        | 1%      |
| IMC Networks Realtek Bluetooth Adapter                      | 10        | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 9         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 8         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 8         | 0.72%   |
| Dell DW375 Bluetooth Module                                 | 8         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 7         | 0.63%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 7         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                            | 7         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 7         | 0.63%   |
| Realtek Bluetooth 4.2 Adapter                               | 6         | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 6         | 0.54%   |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 0.54%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.45%   |
| Realtek Bluetooth 4.0 Adapter                               | 5         | 0.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 5         | 0.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 5         | 0.45%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 0.45%   |
| Apple Broadcom Built-in Bluetooth                           | 5         | 0.45%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 4         | 0.36%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 0.36%   |
| Realtek Wireless Bluetooth Adapter                          | 3         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1546      | 54.92%  |
| AMD                                          | 579       | 20.57%  |
| Nvidia                                       | 445       | 15.81%  |
| C-Media Electronics                          | 32        | 1.14%   |
| Logitech                                     | 24        | 0.85%   |
| Creative Labs                                | 17        | 0.6%    |
| Texas Instruments                            | 13        | 0.46%   |
| Lenovo                                       | 13        | 0.46%   |
| Realtek Semiconductor                        | 11        | 0.39%   |
| ASUSTek Computer                             | 8         | 0.28%   |
| GN Netcom                                    | 7         | 0.25%   |
| Generalplus Technology                       | 7         | 0.25%   |
| SteelSeries ApS                              | 6         | 0.21%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.21%   |
| Plantronics                                  | 6         | 0.21%   |
| Kingston Technology                          | 6         | 0.21%   |
| JMTek                                        | 6         | 0.21%   |
| Focusrite-Novation                           | 5         | 0.18%   |
| BEHRINGER International                      | 5         | 0.18%   |
| Sony                                         | 4         | 0.14%   |
| Creative Technology                          | 4         | 0.14%   |
| Blue Microphones                             | 4         | 0.14%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.11%   |
| Tenx Technology                              | 3         | 0.11%   |
| M-Audio                                      | 3         | 0.11%   |
| Yamaha                                       | 2         | 0.07%   |
| VIA Technologies                             | 2         | 0.07%   |
| Trust                                        | 2         | 0.07%   |
| Samsung Electronics                          | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Micro Star International                     | 2         | 0.07%   |
| FiiO Electronics Technology                  | 2         | 0.07%   |
| Corsair                                      | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| Cambridge Silicon Radio                      | 2         | 0.07%   |
| Apple                                        | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| Xilinx                                       | 1         | 0.04%   |
| Universal Audio                              | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 189       | 5.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 189       | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 144       | 4.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 141       | 4.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 106       | 3.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 96        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 88        | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 75        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 75        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 74        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 67        | 2%      |
| Intel Broadwell-U Audio Controller                                         | 65        | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 60        | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 60        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 58        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 56        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 56        | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 51        | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 46        | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 44        | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 42        | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 42        | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 41        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 39        | 1.17%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 1.08%   |
| AMD FCH Azalia Controller                                                  | 36        | 1.08%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 34        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 33        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 30        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                   | 30        | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                              | 28        | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 27        | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 26        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 24        | 0.72%   |
| Nvidia High Definition Audio Controller                                    | 22        | 0.66%   |
| Intel CM238 HD Audio Controller                                            | 21        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 595       | 21.01%  |
| SK hynix                     | 472       | 16.67%  |
| Kingston                     | 343       | 12.11%  |
| Unknown                      | 284       | 10.03%  |
| Micron Technology            | 272       | 9.6%    |
| Crucial                      | 180       | 6.36%   |
| Corsair                      | 165       | 5.83%   |
| G.Skill                      | 86        | 3.04%   |
| Unknown                      | 58        | 2.05%   |
| Ramaxel Technology           | 46        | 1.62%   |
| A-DATA Technology            | 40        | 1.41%   |
| Nanya Technology             | 26        | 0.92%   |
| Elpida                       | 26        | 0.92%   |
| Transcend                    | 21        | 0.74%   |
| Team                         | 21        | 0.74%   |
| Patriot                      | 16        | 0.56%   |
| Hewlett-Packard              | 16        | 0.56%   |
| Goodram                      | 16        | 0.56%   |
| Unknown (ABCD)               | 11        | 0.39%   |
| Avant                        | 9         | 0.32%   |
| Smart                        | 8         | 0.28%   |
| Patriot Memory (PDP Systems) | 7         | 0.25%   |
| Super Talent                 | 6         | 0.21%   |
| PNY                          | 6         | 0.21%   |
| Goldkey                      | 6         | 0.21%   |
| Neo Forza                    | 5         | 0.18%   |
| Apacer                       | 5         | 0.18%   |
| AMD                          | 5         | 0.18%   |
| Qimonda                      | 4         | 0.14%   |
| HPE                          | 4         | 0.14%   |
| 48spaces                     | 4         | 0.14%   |
| Toshiba                      | 3         | 0.11%   |
| Kingmax                      | 3         | 0.11%   |
| Golden Empire                | 3         | 0.11%   |
| ASint Technology             | 3         | 0.11%   |
| V-GeN                        | 2         | 0.07%   |
| V-Color                      | 2         | 0.07%   |
| Tigo                         | 2         | 0.07%   |
| Silicon Power                | 2         | 0.07%   |
| PUSKILL                      | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 58        | 1.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 23        | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 22        | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 19        | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 18        | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 18        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 18        | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 18        | 0.58%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s  | 15        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 14        | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 14        | 0.45%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 14        | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 13        | 0.42%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 13        | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 13        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 13        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 13        | 0.42%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 11        | 0.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 11        | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 10        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 10        | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 10        | 0.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 10        | 0.32%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 10        | 0.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s   | 10        | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 8         | 0.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 8         | 0.26%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s   | 8         | 0.26%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 8         | 0.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 8         | 0.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 8         | 0.26%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s  | 8         | 0.26%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 8         | 0.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 8         | 0.26%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 8         | 0.26%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s   | 8         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 7         | 0.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 7         | 0.23%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s    | 7         | 0.23%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 7         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 1061      | 43.15%  |
| DDR3         | 938       | 38.15%  |
| DDR2         | 150       | 6.1%    |
| Unknown      | 73        | 2.97%   |
| LPDDR3       | 58        | 2.36%   |
| LPDDR4       | 49        | 1.99%   |
| SDRAM        | 42        | 1.71%   |
| DDR          | 36        | 1.46%   |
| DDR5         | 28        | 1.14%   |
| LPDDR5       | 14        | 0.57%   |
| DRAM         | 7         | 0.28%   |
| SRAM         | 1         | 0.04%   |
| RAM          | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1172      | 47.62%  |
| DIMM         | 1124      | 45.67%  |
| Row Of Chips | 106       | 4.31%   |
| Chip         | 34        | 1.38%   |
| Unknown      | 11        | 0.45%   |
| RIMM         | 7         | 0.28%   |
| FB-DIMM      | 7         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 950       | 35.32%  |
| 4096   | 681       | 25.32%  |
| 16384  | 443       | 16.47%  |
| 2048   | 338       | 12.57%  |
| 32768  | 139       | 5.17%   |
| 1024   | 98        | 3.64%   |
| 512    | 24        | 0.89%   |
| 256    | 5         | 0.19%   |
| 65536  | 3         | 0.11%   |
| 3072   | 2         | 0.07%   |
| 128    | 2         | 0.07%   |
| 131072 | 1         | 0.04%   |
| 2560   | 1         | 0.04%   |
| 64     | 1         | 0.04%   |
| 32     | 1         | 0.04%   |
| 8      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 570       | 21.77%  |
| 3200    | 335       | 12.8%   |
| 1333    | 285       | 10.89%  |
| 2400    | 267       | 10.2%   |
| 2667    | 260       | 9.93%   |
| 2133    | 202       | 7.72%   |
| 800     | 85        | 3.25%   |
| 667     | 83        | 3.17%   |
| Unknown | 61        | 2.33%   |
| 1334    | 57        | 2.18%   |
| 1867    | 53        | 2.02%   |
| 2666    | 44        | 1.68%   |
| 1067    | 39        | 1.49%   |
| 2933    | 28        | 1.07%   |
| 1066    | 28        | 1.07%   |
| 4267    | 26        | 0.99%   |
| 533     | 26        | 0.99%   |
| 3000    | 23        | 0.88%   |
| 4800    | 22        | 0.84%   |
| 3600    | 21        | 0.8%    |
| 1866    | 18        | 0.69%   |
| 6400    | 13        | 0.5%    |
| 400     | 8         | 0.31%   |
| 4266    | 7         | 0.27%   |
| 975     | 6         | 0.23%   |
| 266     | 6         | 0.23%   |
| 2048    | 5         | 0.19%   |
| 5600    | 4         | 0.15%   |
| 3400    | 4         | 0.15%   |
| 4000    | 3         | 0.11%   |
| 1639    | 3         | 0.11%   |
| 333     | 3         | 0.11%   |
| 5200    | 2         | 0.08%   |
| 3733    | 2         | 0.08%   |
| 3534    | 2         | 0.08%   |
| 1332    | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 4133    | 1         | 0.04%   |
| 3500    | 1         | 0.04%   |
| 3066    | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 25%     |
| Prolific Technology | 3         | 18.75%  |
| Hewlett-Packard     | 2         | 12.5%   |
| ELGIN               | 2         | 12.5%   |
| Seiko Epson         | 1         | 6.25%   |
| Samsung Electronics | 1         | 6.25%   |
| QinHeng Electronics | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                                              | 3         | 18.75%  |
| ELGIN L42PRO                                                                               | 2         | 12.5%   |
| Seiko Epson Printer                                                                        | 1         | 6.25%   |
| Samsung ML-1610 Mono Laser Printer                                                         | 1         | 6.25%   |
| QinHeng CH340S                                                                             | 1         | 6.25%   |
| HP LaserJet 1012                                                                           | 1         | 6.25%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 450                                                                | 1         | 6.25%   |
| Canon LBP2900                                                                              | 1         | 6.25%   |
| Brother MFC-7360N                                                                          | 1         | 6.25%   |
| Brother HL-L5200DW series                                                                  | 1         | 6.25%   |
| Brother HL-2030 Laser Printer                                                              | 1         | 6.25%   |
| Brother HL-1430 Laser Printer                                                              | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 2         | 25%     |
| Canon CanoScan LiDE 110                                                             | 2         | 25%     |
| HP ScanJet 5300c/5370c                                                              | 1         | 12.5%   |
| Canon CanoScan LIDE 25                                                              | 1         | 12.5%   |
| Canon CanoScan LiDE 220                                                             | 1         | 12.5%   |
| Canon CanoScan LiDE 120                                                             | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 273       | 28.44%  |
| IMC Networks                           | 101       | 10.52%  |
| Microdia                               | 93        | 9.69%   |
| Bison Electronics                      | 88        | 9.17%   |
| Realtek Semiconductor                  | 76        | 7.92%   |
| Sunplus Innovation Technology          | 58        | 6.04%   |
| Logitech                               | 47        | 4.9%    |
| Lite-On Technology                     | 29        | 3.02%   |
| Suyin                                  | 24        | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 19        | 1.98%   |
| Syntek                                 | 17        | 1.77%   |
| Quanta                                 | 17        | 1.77%   |
| Apple                                  | 16        | 1.67%   |
| Luxvisions Innotech Limited            | 12        | 1.25%   |
| Silicon Motion                         | 10        | 1.04%   |
| Lenovo                                 | 9         | 0.94%   |
| Z-Star Microelectronics                | 7         | 0.73%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.73%   |
| ALi                                    | 5         | 0.52%   |
| Ricoh                                  | 4         | 0.42%   |
| Importek                               | 4         | 0.42%   |
| Alcor Micro                            | 4         | 0.42%   |
| Supreme Electronics                    | 3         | 0.31%   |
| OmniVision Technologies                | 3         | 0.31%   |
| ARC International                      | 3         | 0.31%   |
| WCM_USB                                | 2         | 0.21%   |
| Unknown                                | 2         | 0.21%   |
| Trust                                  | 2         | 0.21%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.21%   |
| Primax Electronics                     | 2         | 0.21%   |
| Pixart Imaging                         | 2         | 0.21%   |
| Jiangxi Shinetech Optical              | 2         | 0.21%   |
| Intel                                  | 2         | 0.21%   |
| Cubeternet                             | 2         | 0.21%   |
| YGTek                                  | 1         | 0.1%    |
| Valve Software                         | 1         | 0.1%    |
| USB Camera                             | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| Qtech                                  | 1         | 0.1%    |
| Nam Tai E&E Products                   | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 89        | 9.16%   |
| Bison Integrated Camera                       | 48        | 4.94%   |
| IMC Networks Integrated Camera                | 38        | 3.91%   |
| Microdia Integrated_Webcam_HD                 | 26        | 2.67%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 20        | 2.06%   |
| Chicony HD WebCam                             | 20        | 2.06%   |
| Realtek Integrated_Webcam_HD                  | 19        | 1.95%   |
| Microdia Integrated Webcam                    | 19        | 1.95%   |
| Sunplus Integrated_Webcam_HD                  | 18        | 1.85%   |
| Chicony Integrated Camera (1280x720@30)       | 18        | 1.85%   |
| Lite-On Integrated Camera                     | 16        | 1.65%   |
| Logitech Webcam C270                          | 14        | 1.44%   |
| Realtek USB 2.0 PC Camera                     | 13        | 1.34%   |
| IMC Networks Realtek PC Camera                | 11        | 1.13%   |
| Bison SunplusIT Integrated Camera             | 11        | 1.13%   |
| IMC Networks EasyCamera                       | 10        | 1.03%   |
| Syntek Integrated Camera                      | 9         | 0.93%   |
| Chicony Realtek DMFT RGB                      | 9         | 0.93%   |
| Chicony Integrated IR Camera                  | 9         | 0.93%   |
| Bison Lenovo EasyCamera                       | 9         | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 8         | 0.82%   |
| Logitech HD Pro Webcam C920                   | 8         | 0.82%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 0.82%   |
| Apple FaceTime HD Camera                      | 8         | 0.82%   |
| Microdia Integrated Webcam HD                 | 7         | 0.72%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 0.72%   |
| Chicony Integrated Camera [ThinkPad]          | 7         | 0.72%   |
| Chicony EasyCamera                            | 7         | 0.72%   |
| Apple FaceTime HD Camera (Built-in)           | 7         | 0.72%   |
| Realtek Integrated Webcam                     | 6         | 0.62%   |
| Quanta HD Webcam                              | 6         | 0.62%   |
| Luxvisions Innotech Limited Integrated Camera | 6         | 0.62%   |
| Lenovo Integrated Webcam [R5U877]             | 6         | 0.62%   |
| IMC Networks Integrated Webcam                | 6         | 0.62%   |
| Chicony Integrated HP HD Webcam               | 6         | 0.62%   |
| Syntek EasyCamera                             | 5         | 0.51%   |
| Sunplus Laptop Integrated WebCam HD           | 5         | 0.51%   |
| Sunplus HD WebCam                             | 5         | 0.51%   |
| IMC Networks UVC VGA Webcam                   | 5         | 0.51%   |
| Chicony USB 2.0 Camera                        | 5         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 85        | 31.14%  |
| Synaptics                  | 73        | 26.74%  |
| Shenzhen Goodix Technology | 36        | 13.19%  |
| Upek                       | 22        | 8.06%   |
| AuthenTec                  | 12        | 4.4%    |
| Elan Microelectronics      | 11        | 4.03%   |
| STMicroelectronics         | 10        | 3.66%   |
| LighTuning Technology      | 8         | 2.93%   |
| Broadcom                   | 8         | 2.93%   |
| FocalTech Systems          | 6         | 2.2%    |
| Samsung Electronics        | 1         | 0.37%   |
| DigitalPersona             | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 31        | 11.36%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 26        | 9.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 25        | 9.16%   |
| Shenzhen Goodix Fingerprint Reader                                           | 25        | 9.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 22        | 8.06%   |
| Validity Sensors Synaptics WBDI                                              | 20        | 7.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 13        | 4.76%   |
| Elan Fingerprint Sensor                                                      | 11        | 4.03%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 3.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 8         | 2.93%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 2.93%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 2.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 5         | 1.83%   |
| FocalTech Systems Fingerprint Reader                                         | 5         | 1.83%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 4         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 4         | 1.47%   |
| AuthenTec AES2810                                                            | 4         | 1.47%   |
| AuthenTec AES1660                                                            | 4         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 1.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.1%    |
| Validity Sensors VFS491                                                      | 2         | 0.73%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 0.73%   |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 0.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 0.73%   |
| Synaptics WBDI                                                               | 2         | 0.73%   |
| Synaptics UWP WBDI                                                           | 2         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 0.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.37%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.37%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.37%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 0.37%   |
| Synaptics TouchPad                                                           | 1         | 0.37%   |
| Synaptics Fingerprint reader [HP G6]                                         | 1         | 0.37%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.37%   |
| FocalTech Systems FocalTech Fingerprint Device                               | 1         | 0.37%   |
| DigitalPersona Fingerprint Reader                                            | 1         | 0.37%   |
| AuthenTec AES2660                                                            | 1         | 0.37%   |

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
| 1     | 834       | 31.11%  |
| 0     | 743       | 27.71%  |
| 2     | 628       | 23.42%  |
| 3     | 320       | 11.94%  |
| 4     | 118       | 4.4%    |
| 5     | 24        | 0.9%    |
| 6     | 11        | 0.41%   |
| 7     | 2         | 0.07%   |
| 9     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1473      | 45.99%  |
| Bluetooth                | 487       | 15.2%   |
| Net/wireless             | 350       | 10.93%  |
| Card reader              | 268       | 8.37%   |
| Fingerprint reader       | 265       | 8.27%   |
| Firewire controller      | 181       | 5.65%   |
| Net/ethernet             | 49        | 1.53%   |
| Sound                    | 45        | 1.4%    |
| Network                  | 36        | 1.12%   |
| Storage                  | 23        | 0.72%   |
| Modem                    | 14        | 0.44%   |
| Dvb card                 | 6         | 0.19%   |
| Storage/raid             | 2         | 0.06%   |
| Storage/ide              | 2         | 0.06%   |
| Storage/nvme             | 1         | 0.03%   |
| Graphics card            | 1         | 0.03%   |

