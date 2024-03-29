FreeBSD - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for FreeBSD.

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

Total: 1720

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E6430              | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [fb1f5f8545](https://bsd-hardware.info/?probe=fb1f5f8545) | Feb 16, 2024 |
| Dell          | Vostro 15-3568              | [cc65de13e8](https://bsd-hardware.info/?probe=cc65de13e8) | Feb 16, 2024 |
| Dell          | Latitude E7470              | [3a08bc08be](https://bsd-hardware.info/?probe=3a08bc08be) | Feb 15, 2024 |
| Google        | Ultima                      | [732adeb5e4](https://bsd-hardware.info/?probe=732adeb5e4) | Feb 15, 2024 |
| Dell          | Inspiron 3558               | [e0e665c1b5](https://bsd-hardware.info/?probe=e0e665c1b5) | Feb 13, 2024 |
| Lenovo        | ThinkPad T410 2522WAR       | [caccf07908](https://bsd-hardware.info/?probe=caccf07908) | Feb 12, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [977c74f4c0](https://bsd-hardware.info/?probe=977c74f4c0) | Feb 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Panasonic     | CF-52VDA131M                | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [e7c9d50432](https://bsd-hardware.info/?probe=e7c9d50432) | Feb 05, 2024 |
| Apple         | MacBookPro11,1              | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6a78256797](https://bsd-hardware.info/?probe=6a78256797) | Feb 04, 2024 |
| Apple         | MacBookPro8,2               | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| Acer          | Aspire A315-22              | [0bd7a59dfe](https://bsd-hardware.info/?probe=0bd7a59dfe) | Feb 02, 2024 |
| Apple         | MacBookPro14,1              | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| Acer          | TravelMate P645-SG          | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | [a2d3483ef9](https://bsd-hardware.info/?probe=a2d3483ef9) | Jan 30, 2024 |
| HP            | ZBook 17 G2                 | [db2c57b081](https://bsd-hardware.info/?probe=db2c57b081) | Jan 24, 2024 |
| Lenovo        | Legion Y9000X 2020 81TH     | [3711b11e8a](https://bsd-hardware.info/?probe=3711b11e8a) | Jan 23, 2024 |
| HP            | ProBook 650 G1              | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Dell          | Latitude E7450              | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Lenovo        | G50-80 80E5                 | [2330f23f1a](https://bsd-hardware.info/?probe=2330f23f1a) | Jan 16, 2024 |
| Dell          | Precision 7510              | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer         | Blade 16 - RZ09-0483        | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| LG Electro... | 16UD70R-G.AX59B             | [0b08d5b203](https://bsd-hardware.info/?probe=0b08d5b203) | Jan 16, 2024 |
| Dell          | Latitude 7490               | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| Dell          | Latitude 7490               | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Dell          | Latitude E5420              | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| ASUSTek       | X441UV                      | [6cdd70da49](https://bsd-hardware.info/?probe=6cdd70da49) | Jan 11, 2024 |
| Dell          | Inspiron 1525               | [e6c13bf584](https://bsd-hardware.info/?probe=e6c13bf584) | Jan 11, 2024 |
| HP            | 255 G7 Notebook PC          | [2c7e743906](https://bsd-hardware.info/?probe=2c7e743906) | Jan 10, 2024 |
| HP            | 255 G7 Notebook PC          | [ef0d0a61f8](https://bsd-hardware.info/?probe=ef0d0a61f8) | Jan 10, 2024 |
| Dell          | Inspiron 1525               | [fa7b4f0216](https://bsd-hardware.info/?probe=fa7b4f0216) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| Dell          | Inspiron 5555               | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| HP            | Pavilion g6                 | [77f3d49b2e](https://bsd-hardware.info/?probe=77f3d49b2e) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| Lenovo        | ThinkPad 11e 20D90020US     | [7d7f564886](https://bsd-hardware.info/?probe=7d7f564886) | Jan 05, 2024 |
| Apple         | MacBook5,1                  | [90346c6fe3](https://bsd-hardware.info/?probe=90346c6fe3) | Jan 04, 2024 |
| Lenovo        | G50-80 80E5                 | [a678ec59e8](https://bsd-hardware.info/?probe=a678ec59e8) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [5c583e5a9d](https://bsd-hardware.info/?probe=5c583e5a9d) | Jan 04, 2024 |
| ASUSTek       | X441UV                      | [29b63ed6a8](https://bsd-hardware.info/?probe=29b63ed6a8) | Jan 04, 2024 |
| Dell          | XPS 15 7590                 | [67a65520e6](https://bsd-hardware.info/?probe=67a65520e6) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7ac885382c](https://bsd-hardware.info/?probe=7ac885382c) | Jan 03, 2024 |
| HP            | Laptop 15t-dy100            | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| Dell          | Vostro 5470                 | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Toshiba       | Satellite P300              | [4ddf360812](https://bsd-hardware.info/?probe=4ddf360812) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [0a2c02f944](https://bsd-hardware.info/?probe=0a2c02f944) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [4b1250f831](https://bsd-hardware.info/?probe=4b1250f831) | Dec 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [a740494857](https://bsd-hardware.info/?probe=a740494857) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Inspiron MM061              | [7e4cee9689](https://bsd-hardware.info/?probe=7e4cee9689) | Dec 24, 2023 |
| Dell          | Precision 5510              | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| Dell          | Precision 7720              | [a30d05e373](https://bsd-hardware.info/?probe=a30d05e373) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [85ec93f4cd](https://bsd-hardware.info/?probe=85ec93f4cd) | Dec 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [34f3eb8059](https://bsd-hardware.info/?probe=34f3eb8059) | Dec 22, 2023 |
| Clevo         | W240BU                      | [19bb603cab](https://bsd-hardware.info/?probe=19bb603cab) | Dec 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [4bc98299dd](https://bsd-hardware.info/?probe=4bc98299dd) | Dec 18, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| HP            | Stream Notebook PC 11       | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Apple         | MacBookAir5,2               | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| CSL-Comput... | C15 v3                      | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| Dell          | XPS 13 9370                 | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Apple         | MacBookPro10,2              | [e1867819f3](https://bsd-hardware.info/?probe=e1867819f3) | Dec 15, 2023 |
| Dell          | Latitude E6220              | [372070b2f2](https://bsd-hardware.info/?probe=372070b2f2) | Dec 15, 2023 |
| Google        | Kohaku                      | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude 3420               | [3767d653b9](https://bsd-hardware.info/?probe=3767d653b9) | Dec 14, 2023 |
| Dell          | Latitude E6540              | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| Google        | Lindar rev3                 | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| Dell          | Latitude E6510              | [86c4864c0a](https://bsd-hardware.info/?probe=86c4864c0a) | Dec 11, 2023 |
| Dell          | Latitude E6510              | [dc2d54a168](https://bsd-hardware.info/?probe=dc2d54a168) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| Google        | Parrot                      | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| Google        | Parrot                      | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Dell          | Latitude 7414               | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Dell          | Precision 7560              | [13f7324bd9](https://bsd-hardware.info/?probe=13f7324bd9) | Dec 07, 2023 |
| Dell          | Precision 7560              | [5d3e6e3bd4](https://bsd-hardware.info/?probe=5d3e6e3bd4) | Dec 07, 2023 |
| HP            | ZBook 17 G2                 | [406d7a0572](https://bsd-hardware.info/?probe=406d7a0572) | Dec 07, 2023 |
| HP            | EliteBook 840 G6            | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [e63bc464f2](https://bsd-hardware.info/?probe=e63bc464f2) | Dec 05, 2023 |
| HP            | ZBook 17 G2                 | [cc4538374c](https://bsd-hardware.info/?probe=cc4538374c) | Dec 05, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Lenovo        | ThinkPad T430s 23532QG      | [b456c01e0f](https://bsd-hardware.info/?probe=b456c01e0f) | Dec 04, 2023 |
| ASUSTek       | X555LB                      | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| Acidanther... | MacBookPro16,3              | [322ea11f6c](https://bsd-hardware.info/?probe=322ea11f6c) | Dec 03, 2023 |
| Toshiba       | Satellite C50-B             | [34db2bdd7d](https://bsd-hardware.info/?probe=34db2bdd7d) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| ASUSTek       | X555LB                      | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [ae4c6d7097](https://bsd-hardware.info/?probe=ae4c6d7097) | Nov 29, 2023 |
| Dell          | Precision 5510              | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| Dell          | Inspiron N5010              | [b32ded6bb9](https://bsd-hardware.info/?probe=b32ded6bb9) | Nov 27, 2023 |
| Unknown       | Unknown                     | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [3517ce2745](https://bsd-hardware.info/?probe=3517ce2745) | Nov 26, 2023 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | [5f336b9d93](https://bsd-hardware.info/?probe=5f336b9d93) | Nov 26, 2023 |
| HP            | Laptop 15s-eq3xxx           | [f2aa7b3ebf](https://bsd-hardware.info/?probe=f2aa7b3ebf) | Nov 25, 2023 |
| Dell          | Latitude 5480               | [639ffb1573](https://bsd-hardware.info/?probe=639ffb1573) | Nov 25, 2023 |
| Lenovo        | G50-80 80E5                 | [e0d8200dfa](https://bsd-hardware.info/?probe=e0d8200dfa) | Nov 24, 2023 |
| Google        | Dragonair                   | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| HP            | Notebook                    | [aff6430eb2](https://bsd-hardware.info/?probe=aff6430eb2) | Nov 24, 2023 |
| Acer          | JM11-MS                     | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Acidanther... | MacBookPro16,3              | [5f89fa2cd2](https://bsd-hardware.info/?probe=5f89fa2cd2) | Nov 22, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [fdb7c00df7](https://bsd-hardware.info/?probe=fdb7c00df7) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | [0272396725](https://bsd-hardware.info/?probe=0272396725) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2c33e6e9e7](https://bsd-hardware.info/?probe=2c33e6e9e7) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Panasonic     | CF-31-5                     | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Toshiba       | Satellite P300              | [ece5171a1d](https://bsd-hardware.info/?probe=ece5171a1d) | Nov 17, 2023 |
| HP            | Notebook                    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [918706e110](https://bsd-hardware.info/?probe=918706e110) | Nov 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0e4ea9ccbf](https://bsd-hardware.info/?probe=0e4ea9ccbf) | Nov 15, 2023 |
| Dell          | G5 5505                     | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| OnLogic       | HX401                       | [b000c6d264](https://bsd-hardware.info/?probe=b000c6d264) | Nov 12, 2023 |
| ASUSTek       | K56CB                       | [8d4f2c439a](https://bsd-hardware.info/?probe=8d4f2c439a) | Nov 11, 2023 |
| Lenovo        | ThinkPad X270 20HN006CUS    | [dc8d596ea1](https://bsd-hardware.info/?probe=dc8d596ea1) | Nov 11, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| Dell          | Precision 7560              | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| Toshiba       | Satellite P300              | [9d4170e2d2](https://bsd-hardware.info/?probe=9d4170e2d2) | Nov 08, 2023 |
| Unknown       | Unknown                     | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| ASUSTek       | K56CB                       | [7d6d03a42b](https://bsd-hardware.info/?probe=7d6d03a42b) | Nov 05, 2023 |
| Dell          | XPS 13 9360                 | [c7d016caa9](https://bsd-hardware.info/?probe=c7d016caa9) | Nov 04, 2023 |
| LG Electro... | 16UD70R-G.AX59B             | [a7df4f645f](https://bsd-hardware.info/?probe=a7df4f645f) | Nov 04, 2023 |
| Dell          | Inspiron 1525               | [538444f1d2](https://bsd-hardware.info/?probe=538444f1d2) | Nov 02, 2023 |
| Apple         | MacBookPro7,1               | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| Toshiba       | Satellite P300              | [49d23c8fda](https://bsd-hardware.info/?probe=49d23c8fda) | Oct 28, 2023 |
| Toshiba       | Satellite P300              | [a133633304](https://bsd-hardware.info/?probe=a133633304) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| Lenovo        | G50-30 80G0                 | [e2dad0b43a](https://bsd-hardware.info/?probe=e2dad0b43a) | Oct 24, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [1f76a6c28c](https://bsd-hardware.info/?probe=1f76a6c28c) | Oct 22, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [6569410f91](https://bsd-hardware.info/?probe=6569410f91) | Oct 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | [5a7e4222f1](https://bsd-hardware.info/?probe=5a7e4222f1) | Oct 21, 2023 |
| Dell          | G16 7630                    | [deb5f3bd32](https://bsd-hardware.info/?probe=deb5f3bd32) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| Lenovo        | G550 2958                   | [6dfadd1ff2](https://bsd-hardware.info/?probe=6dfadd1ff2) | Oct 11, 2023 |
| Dell          | Precision 7550              | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Unknown       | Unknown                     | [9c6c7f9d6b](https://bsd-hardware.info/?probe=9c6c7f9d6b) | Oct 10, 2023 |
| Dell          | Inspiron 13 5320            | [43c1b405d0](https://bsd-hardware.info/?probe=43c1b405d0) | Oct 09, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [0aac5f52c9](https://bsd-hardware.info/?probe=0aac5f52c9) | Oct 08, 2023 |
| Timi          | A34R                        | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Apple         | MacBookPro6,2               | [85e94bd511](https://bsd-hardware.info/?probe=85e94bd511) | Oct 06, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [aecfeaa518](https://bsd-hardware.info/?probe=aecfeaa518) | Oct 04, 2023 |
| Lenovo        | ThinkPad X230 2325J67       | [bfbc6beca8](https://bsd-hardware.info/?probe=bfbc6beca8) | Oct 04, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| HP            | ZBook 17 G2                 | [4e12d36770](https://bsd-hardware.info/?probe=4e12d36770) | Oct 03, 2023 |
| Lenovo        | B40-30 80F1                 | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| Platform      | ARB938                      | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Dell          | Latitude 3410               | [1bd71b0bf0](https://bsd-hardware.info/?probe=1bd71b0bf0) | Sep 24, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Dell          | G16 7630                    | [4e39a5ebdf](https://bsd-hardware.info/?probe=4e39a5ebdf) | Sep 21, 2023 |
| HP            | ZBook 17 G2                 | [f29233649e](https://bsd-hardware.info/?probe=f29233649e) | Sep 20, 2023 |
| Lenovo        | ThinkPad L390 20NRS00Q00    | [b9885ea126](https://bsd-hardware.info/?probe=b9885ea126) | Sep 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7S24F0... | [bb7eb8b380](https://bsd-hardware.info/?probe=bb7eb8b380) | Sep 15, 2023 |
| Platform      | ARB938                      | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| HP            | Pavilion dv5                | [b7dad77d0d](https://bsd-hardware.info/?probe=b7dad77d0d) | Sep 14, 2023 |
| GPU Compan... | GWTC116-2                   | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| HP            | Mini 110-3100               | [14f75b6704](https://bsd-hardware.info/?probe=14f75b6704) | Sep 11, 2023 |
| HP            | ZBook 17 G2                 | [e2d694053a](https://bsd-hardware.info/?probe=e2d694053a) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3LR0... | [cbac96a24f](https://bsd-hardware.info/?probe=cbac96a24f) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [d9d6fc45f8](https://bsd-hardware.info/?probe=d9d6fc45f8) | Sep 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [e011df1d78](https://bsd-hardware.info/?probe=e011df1d78) | Sep 07, 2023 |
| Unknown       | Unknown                     | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| HP            | EliteBook 8570p             | [cfecf51114](https://bsd-hardware.info/?probe=cfecf51114) | Sep 04, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| HP            | EliteBook 8570p             | [d240fba8b7](https://bsd-hardware.info/?probe=d240fba8b7) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [1bfe26df6e](https://bsd-hardware.info/?probe=1bfe26df6e) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0ebdda5146](https://bsd-hardware.info/?probe=0ebdda5146) | Aug 31, 2023 |
| HP            | EliteBook 8570p             | [0dda7a609c](https://bsd-hardware.info/?probe=0dda7a609c) | Aug 29, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [f0fb53394d](https://bsd-hardware.info/?probe=f0fb53394d) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [dc8ad6c7c5](https://bsd-hardware.info/?probe=dc8ad6c7c5) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [c8c17a9db2](https://bsd-hardware.info/?probe=c8c17a9db2) | Aug 28, 2023 |
| Dell          | G5 5590                     | [2e496efada](https://bsd-hardware.info/?probe=2e496efada) | Aug 26, 2023 |
| Dell          | G5 5590                     | [fd4f457391](https://bsd-hardware.info/?probe=fd4f457391) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| ASUSTek       | N751JK                      | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0UD0... | [3c3610a93f](https://bsd-hardware.info/?probe=3c3610a93f) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| ASUSTek       | N751JK                      | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| HP            | EliteBook 8570p             | [434ec73823](https://bsd-hardware.info/?probe=434ec73823) | Aug 18, 2023 |
| Dell          | Latitude 3420               | [0e171f3f87](https://bsd-hardware.info/?probe=0e171f3f87) | Aug 18, 2023 |
| Acer          | Aspire A315-59              | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| MSI           | Modern 14 B11SBL            | [1e02b41824](https://bsd-hardware.info/?probe=1e02b41824) | Aug 12, 2023 |
| ASUSTek       | N751JK                      | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [ac53dba211](https://bsd-hardware.info/?probe=ac53dba211) | Aug 11, 2023 |
| ASUSTek       | 1001P                       | [2424d8acdc](https://bsd-hardware.info/?probe=2424d8acdc) | Aug 11, 2023 |
| Notebook      | N7x0WU                      | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| MSI           | Modern 14 B11SBL            | [ba3ab230dc](https://bsd-hardware.info/?probe=ba3ab230dc) | Aug 08, 2023 |
| MSI           | Modern 14 B11SBL            | [48483213f9](https://bsd-hardware.info/?probe=48483213f9) | Aug 06, 2023 |
| Dell          | Inspiron 14-3467            | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Acer          | Aspire E5-511               | [93faaaff91](https://bsd-hardware.info/?probe=93faaaff91) | Jul 30, 2023 |
| HP            | EliteBook 8570p             | [2619fadb11](https://bsd-hardware.info/?probe=2619fadb11) | Jul 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [56fc67d3eb](https://bsd-hardware.info/?probe=56fc67d3eb) | Jul 22, 2023 |
| NOBLEX        | SF20BA                      | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| HP            | EliteBook 8570p             | [9f4f71236e](https://bsd-hardware.info/?probe=9f4f71236e) | Jul 21, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BK0... | [01f4886e09](https://bsd-hardware.info/?probe=01f4886e09) | Jul 21, 2023 |
| Dell          | Precision 5550              | [4c9dd227a7](https://bsd-hardware.info/?probe=4c9dd227a7) | Jul 20, 2023 |
| Samsung       | 100NZB                      | [5515e88fc1](https://bsd-hardware.info/?probe=5515e88fc1) | Jul 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| HP            | EliteBook 6930p             | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Lenovo        | G550 2958                   | [bc36695565](https://bsd-hardware.info/?probe=bc36695565) | Jul 13, 2023 |
| HONOR         | NMH-WCX9                    | [f573d1d5c4](https://bsd-hardware.info/?probe=f573d1d5c4) | Jul 11, 2023 |
| Getac         | F110G2                      | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [4274ca291e](https://bsd-hardware.info/?probe=4274ca291e) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| HP            | EliteBook 8570p             | [44b85aad5e](https://bsd-hardware.info/?probe=44b85aad5e) | Jul 07, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [2519fb81d6](https://bsd-hardware.info/?probe=2519fb81d6) | Jul 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1HL0... | [f7b57506f0](https://bsd-hardware.info/?probe=f7b57506f0) | Jul 04, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Dell          | Latitude 3420               | [057f065baa](https://bsd-hardware.info/?probe=057f065baa) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| HP            | EliteBook 8570p             | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| HP            | Pavilion g4                 | [ef66b5588a](https://bsd-hardware.info/?probe=ef66b5588a) | Jun 23, 2023 |
| HP            | 1000                        | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| Apple         | MacBook2,1                  | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| HP            | EliteBook 8570p             | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| Notebook      | NL5xRU                      | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [834f9f8748](https://bsd-hardware.info/?probe=834f9f8748) | Jun 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [7e1aa76e45](https://bsd-hardware.info/?probe=7e1aa76e45) | Jun 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| Fujitsu Si... | AMILO Li3710                | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| HP            | EliteBook 840 G6            | [1d3675e09e](https://bsd-hardware.info/?probe=1d3675e09e) | Jun 11, 2023 |
| Acer          | Aspire E5-571G              | [9279b8ab4e](https://bsd-hardware.info/?probe=9279b8ab4e) | Jun 11, 2023 |
| Lenovo        | B40-30 80F1                 | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | [439e6a5034](https://bsd-hardware.info/?probe=439e6a5034) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Lenovo        | B590 20208                  | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| Dell          | G5 5505                     | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Dell          | G5 5505                     | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [b5f507c034](https://bsd-hardware.info/?probe=b5f507c034) | May 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [3944241750](https://bsd-hardware.info/?probe=3944241750) | May 27, 2023 |
| HP            | EliteBook 8570p             | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Acer          | Nitro AN515-42              | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| Lenovo        | ThinkPad T430 2347CTO       | [68937b1686](https://bsd-hardware.info/?probe=68937b1686) | May 24, 2023 |
| HP            | EliteBook 8570p             | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Acer          | Aspire E5-573               | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Dell          | Inspiron 5559               | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| HP            | EliteBook 8570p             | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Acer          | Aspire A514-54              | [7aed9d938a](https://bsd-hardware.info/?probe=7aed9d938a) | May 21, 2023 |
| Dell          | Inspiron 5559               | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | EliteBook 8570p             | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| Valve         | Jupiter                     | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Panasonic     | CF-30KAPAXAM                | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Dell          | Inspiron 3581               | [25c403ca33](https://bsd-hardware.info/?probe=25c403ca33) | May 15, 2023 |
| HP            | EliteBook 8570p             | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | Inspiron 3581               | [8d445a3fb3](https://bsd-hardware.info/?probe=8d445a3fb3) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Alienware     | 17 R4                       | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Medion        | Major X10                   | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Notebook      | N7x0WU                      | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| Panasonic     | CF-30KAPAXAM                | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b09acffe7b](https://bsd-hardware.info/?probe=b09acffe7b) | May 01, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [692df89c1f](https://bsd-hardware.info/?probe=692df89c1f) | Apr 26, 2023 |
| Fujitsu Si... | AMILO Li3710                | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| HP            | Unknown                     | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| Intel Clie... | LAPBC510                    | [68b1300903](https://bsd-hardware.info/?probe=68b1300903) | Apr 22, 2023 |
| Lenovo        | ThinkPad W520 4270CTO       | [51f0a87f01](https://bsd-hardware.info/?probe=51f0a87f01) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| HP            | EliteBook 8570p             | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [541f3e7f7e](https://bsd-hardware.info/?probe=541f3e7f7e) | Apr 20, 2023 |
| Dell          | Precision 5510              | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| HP            | Unknown                     | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Fujitsu Si... | AMILO Li3710                | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| Dell          | Inspiron 5567               | [a305360215](https://bsd-hardware.info/?probe=a305360215) | Apr 05, 2023 |
| Lenovo        | G50-30 80G0                 | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| HMT           | W041-TF-A-45                | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Dell          | Inspiron 5567               | [b878473783](https://bsd-hardware.info/?probe=b878473783) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Dell          | Inspiron 5567               | [b2ef9ff3dc](https://bsd-hardware.info/?probe=b2ef9ff3dc) | Mar 12, 2023 |
| Google        | Kohaku                      | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Dell          | Precision 7720              | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| Dell          | Latitude D620               | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| Samsung       | 750XEE                      | [47d2204f58](https://bsd-hardware.info/?probe=47d2204f58) | Mar 08, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [6d7b30d2c4](https://bsd-hardware.info/?probe=6d7b30d2c4) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f9db95d778](https://bsd-hardware.info/?probe=f9db95d778) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b2ed608da5](https://bsd-hardware.info/?probe=b2ed608da5) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Lenovo        | ThinkPad R60e 0658W2M       | [dba66ebfb5](https://bsd-hardware.info/?probe=dba66ebfb5) | Feb 17, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Lenovo        | ThinkPad T430 2347FV6       | [cf016ce514](https://bsd-hardware.info/?probe=cf016ce514) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Acer          | Aspire one V1.05            | [eec371a28f](https://bsd-hardware.info/?probe=eec371a28f) | Feb 13, 2023 |
| Dell          | Inspiron 5567               | [df5f01d72e](https://bsd-hardware.info/?probe=df5f01d72e) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f3b0d5ac82](https://bsd-hardware.info/?probe=f3b0d5ac82) | Feb 08, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [4fc5363829](https://bsd-hardware.info/?probe=4fc5363829) | Feb 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Samsung       | 700T1C                      | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Toshiba       | PORTEGE Z930                | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d36789c493](https://bsd-hardware.info/?probe=d36789c493) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54516414a](https://bsd-hardware.info/?probe=a54516414a) | Feb 01, 2023 |
| Lenovo        | ThinkPad T460p 20FW0018A... | [932e722b2d](https://bsd-hardware.info/?probe=932e722b2d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [341bae363a](https://bsd-hardware.info/?probe=341bae363a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [39ae8fb9c8](https://bsd-hardware.info/?probe=39ae8fb9c8) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [75b9ef6ee6](https://bsd-hardware.info/?probe=75b9ef6ee6) | Jan 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Acer          | Aspire one V1.05            | [1cbfce4d7e](https://bsd-hardware.info/?probe=1cbfce4d7e) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4eb4e63a2c](https://bsd-hardware.info/?probe=4eb4e63a2c) | Jan 25, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Dell          | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| Acer          | Aspire A514-54              | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Dell          | Latitude E6430              | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Dell          | Latitude E6430              | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | B50-80 80EW                 | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Dell          | Vostro 15-3568              | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Panasonic     | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Medion        | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| IBM           | ThinkPad T43 18714AG        | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Toshiba       | Satellite A200              | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| HP            | Pavilion g6                 | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| Notebook      | N7x0WU                      | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| Dell          | Latitude E5570              | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Dell          | Latitude E6520              | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| System76      | Lemur Pro                   | [bbeb7d48fa](https://bsd-hardware.info/?probe=bbeb7d48fa) | Apr 17, 2022 |
| HUAWEI        | NBLL-WXX9                   | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [eda0880c67](https://bsd-hardware.info/?probe=eda0880c67) | Apr 15, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [edbde611c3](https://bsd-hardware.info/?probe=edbde611c3) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| ASUSTek       | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| VIT           | M2420                       | [108b4d79a6](https://bsd-hardware.info/?probe=108b4d79a6) | Apr 03, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Deciso        | OPNsense Appliance          | [cdd056df79](https://bsd-hardware.info/?probe=cdd056df79) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Deciso        | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso        | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [6a579dca44](https://bsd-hardware.info/?probe=6a579dca44) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Gateway       | LT27                        | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [be311b6a34](https://bsd-hardware.info/?probe=be311b6a34) | Mar 10, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Dell          | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Dell          | Latitude 3420               | [f1796d75ed](https://bsd-hardware.info/?probe=f1796d75ed) | Feb 14, 2022 |
| WOOKING       | X5                          | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| ASUSTek       | A9T                         | [2962e2b02f](https://bsd-hardware.info/?probe=2962e2b02f) | Feb 09, 2022 |
| Notebook      | N7x0WU                      | [5063e8f546](https://bsd-hardware.info/?probe=5063e8f546) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| System76      | Lemur Pro                   | [713b33351f](https://bsd-hardware.info/?probe=713b33351f) | Feb 06, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [f333ed9201](https://bsd-hardware.info/?probe=f333ed9201) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [c03bfe6a21](https://bsd-hardware.info/?probe=c03bfe6a21) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| HP            | Notebook                    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [268e1621eb](https://bsd-hardware.info/?probe=268e1621eb) | Jan 18, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1763a44db9](https://bsd-hardware.info/?probe=1763a44db9) | Jan 18, 2022 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [2aea9384ac](https://bsd-hardware.info/?probe=2aea9384ac) | Jan 17, 2022 |
| ASUSTek       | N50Vc                       | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [3ef1595af6](https://bsd-hardware.info/?probe=3ef1595af6) | Jan 13, 2022 |
| Lenovo        | ThinkPad E480 20KN0048IA    | [1a2f28f5cc](https://bsd-hardware.info/?probe=1a2f28f5cc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Dell          | Latitude E6430              | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | XPS 15 9575                 | [e7925aa387](https://bsd-hardware.info/?probe=e7925aa387) | Jan 05, 2022 |
| Dell          | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Dell          | Inspiron 5558               | [3a239ea97a](https://bsd-hardware.info/?probe=3a239ea97a) | Jan 02, 2022 |
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [efccc9b019](https://bsd-hardware.info/?probe=efccc9b019) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [66b8fc8279](https://bsd-hardware.info/?probe=66b8fc8279) | Dec 18, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [32080a81c5](https://bsd-hardware.info/?probe=32080a81c5) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [e517ae0a82](https://bsd-hardware.info/?probe=e517ae0a82) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| HP            | ProBook 440 G6              | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| HP            | ProBook 440 G6              | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| HUAWEI        | KLVL-WXX9                   | [b7841e03f5](https://bsd-hardware.info/?probe=b7841e03f5) | Dec 11, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| Framework     | Laptop                      | [46dec0c088](https://bsd-hardware.info/?probe=46dec0c088) | Dec 08, 2021 |
| Framework     | Laptop                      | [a8cd4dc680](https://bsd-hardware.info/?probe=a8cd4dc680) | Dec 08, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [088facef28](https://bsd-hardware.info/?probe=088facef28) | Dec 08, 2021 |
| Toshiba       | Satellite P755              | [44818070a2](https://bsd-hardware.info/?probe=44818070a2) | Dec 08, 2021 |
| Lenovo        | ThinkPad T470s 20HGS18V0... | [a7b9f4a7f8](https://bsd-hardware.info/?probe=a7b9f4a7f8) | Dec 06, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| Samsung       | 530XBB                      | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| ASUSTek       | 1015BX                      | [9e57263095](https://bsd-hardware.info/?probe=9e57263095) | Nov 29, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [91d67ba784](https://bsd-hardware.info/?probe=91d67ba784) | Nov 27, 2021 |
| Lenovo        | ThinkPad W530 2447AV9       | [4e7fc367bc](https://bsd-hardware.info/?probe=4e7fc367bc) | Nov 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire E5-521G              | [5306253276](https://bsd-hardware.info/?probe=5306253276) | Nov 23, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Acer          | Aspire 5560                 | [e117631726](https://bsd-hardware.info/?probe=e117631726) | Nov 22, 2021 |
| Acer          | Aspire A315-21              | [44c1f82bee](https://bsd-hardware.info/?probe=44c1f82bee) | Nov 20, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| Dell          | Vostro 14-5480              | [0ba4cab539](https://bsd-hardware.info/?probe=0ba4cab539) | Nov 14, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Dell          | Vostro 1400                 | [1c594c9ded](https://bsd-hardware.info/?probe=1c594c9ded) | Nov 12, 2021 |
| Apple         | MacBook3,1                  | [61f1f0aef0](https://bsd-hardware.info/?probe=61f1f0aef0) | Nov 10, 2021 |
| HP            | Compaq 6720s                | [6b0d316afc](https://bsd-hardware.info/?probe=6b0d316afc) | Nov 10, 2021 |
| ASUSTek       | 1001P                       | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| HP            | Compaq 6720s                | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| Dell          | Latitude E6430              | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| IBM           | ThinkPad R52 185869G        | [6fd6fd89c5](https://bsd-hardware.info/?probe=6fd6fd89c5) | Nov 08, 2021 |
| Dell          | Inspiron N5050              | [2fbf2a9b2b](https://bsd-hardware.info/?probe=2fbf2a9b2b) | Nov 06, 2021 |
| Dell          | XPS 13 9350                 | [4cc0fd57a5](https://bsd-hardware.info/?probe=4cc0fd57a5) | Nov 04, 2021 |
| Lenovo        | IdeaPad S510p 20298         | [d3cfb73823](https://bsd-hardware.info/?probe=d3cfb73823) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [c469695daf](https://bsd-hardware.info/?probe=c469695daf) | Nov 04, 2021 |
| Dell          | XPS 13 9343                 | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| Toshiba       | Satellite Pro L510          | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Acer          | Aspire E5-575               | [6ea93bc344](https://bsd-hardware.info/?probe=6ea93bc344) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Lenovo        | ThinkPad T430s 23532QG      | [db2a9e5e6f](https://bsd-hardware.info/?probe=db2a9e5e6f) | Oct 29, 2021 |
| Toshiba       | Dakar10FW8                  | [06598a2ed3](https://bsd-hardware.info/?probe=06598a2ed3) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | [e390271460](https://bsd-hardware.info/?probe=e390271460) | Oct 29, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0PM0... | [7a61d90a55](https://bsd-hardware.info/?probe=7a61d90a55) | Oct 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| GPD           | MicroPC                     | [8d0ac5e551](https://bsd-hardware.info/?probe=8d0ac5e551) | Oct 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Dell          | XPS 13 9350                 | [a1ab44830c](https://bsd-hardware.info/?probe=a1ab44830c) | Oct 24, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Dell          | XPS 13 9343                 | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| Lenovo        | G580 26897SJ                | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| Dell          | Latitude E6430              | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Dell          | XPS 13 9343                 | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Acer          | Acadia V1.45                | [29fe65832b](https://bsd-hardware.info/?probe=29fe65832b) | Oct 10, 2021 |
| Google        | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [4572d8b5e7](https://bsd-hardware.info/?probe=4572d8b5e7) | Oct 08, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | F83VD                       | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | A9T                         | [83106a58ef](https://bsd-hardware.info/?probe=83106a58ef) | Oct 03, 2021 |
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| Dell          | Latitude 5490               | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Toshiba       | Dakar10FW8                  | [6a4298baaa](https://bsd-hardware.info/?probe=6a4298baaa) | Sep 24, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
| Dell          | Precision 7710              | [46e9438bf9](https://bsd-hardware.info/?probe=46e9438bf9) | Sep 22, 2021 |
| Dell          | Latitude 5491               | [006dc5a9f4](https://bsd-hardware.info/?probe=006dc5a9f4) | Sep 22, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| MSI           | P65 Creator 8RE             | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| ASUSTek       | G551JW                      | [5624c69d4b](https://bsd-hardware.info/?probe=5624c69d4b) | Sep 16, 2021 |
| System76      | Galago Pro                  | [41cd62c0fe](https://bsd-hardware.info/?probe=41cd62c0fe) | Sep 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| IBM           | ThinkPad X41 2525FAG        | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [d7812a2905](https://bsd-hardware.info/?probe=d7812a2905) | Sep 10, 2021 |
| Lenovo        | ThinkPad X395 20NL000GPG    | [cdde22fb04](https://bsd-hardware.info/?probe=cdde22fb04) | Sep 10, 2021 |
| ASUSTek       | TP300LD                     | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [ff88b24116](https://bsd-hardware.info/?probe=ff88b24116) | Sep 08, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| ASUSTek       | G551JW                      | [309b5d559f](https://bsd-hardware.info/?probe=309b5d559f) | Sep 07, 2021 |
| System76      | Galago Pro                  | [203560e1f5](https://bsd-hardware.info/?probe=203560e1f5) | Sep 07, 2021 |
| System76      | Galago Pro                  | [d3b33c7681](https://bsd-hardware.info/?probe=d3b33c7681) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b8408cb369](https://bsd-hardware.info/?probe=b8408cb369) | Sep 06, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [d160186cfb](https://bsd-hardware.info/?probe=d160186cfb) | Sep 05, 2021 |
| Panasonic     | CF-F9KWHZZQ2                | [05e94c09f6](https://bsd-hardware.info/?probe=05e94c09f6) | Sep 05, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [713b72cfff](https://bsd-hardware.info/?probe=713b72cfff) | Sep 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| HP            | 2000                        | [4e83c9da3f](https://bsd-hardware.info/?probe=4e83c9da3f) | Sep 02, 2021 |
| HP            | 2000                        | [7a48e639e6](https://bsd-hardware.info/?probe=7a48e639e6) | Sep 02, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [67fd361be0](https://bsd-hardware.info/?probe=67fd361be0) | Aug 28, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Notebook      | N7x0WU                      | [7681a46a5b](https://bsd-hardware.info/?probe=7681a46a5b) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| Apple         | MacBookPro8,3               | [455af20b0d](https://bsd-hardware.info/?probe=455af20b0d) | Aug 26, 2021 |
| BANGHO        | MAX G5                      | [d2560f69f7](https://bsd-hardware.info/?probe=d2560f69f7) | Aug 24, 2021 |
| Avell High... | A60 MUV                     | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| Dell          | Inspiron N7010              | [0db8536c63](https://bsd-hardware.info/?probe=0db8536c63) | Aug 21, 2021 |
| Toshiba       | Satellite L50-C             | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Dell          | Latitude E6540              | [7d7cc24971](https://bsd-hardware.info/?probe=7d7cc24971) | Aug 19, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [b5018b8651](https://bsd-hardware.info/?probe=b5018b8651) | Aug 14, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 115       | 8.73%   |
| FreeBSD 13.0         | 111       | 8.43%   |
| FreeBSD 14.0-CURRENT | 75        | 5.69%   |
| FreeBSD 13.2         | 73        | 5.54%   |
| FreeBSD 12.2         | 59        | 4.48%   |
| FreeBSD 14.0         | 46        | 3.49%   |
| FreeBSD 13.1-p5      | 41        | 3.11%   |
| FreeBSD 13.0-p4      | 35        | 2.66%   |
| FreeBSD 12.2-p2      | 34        | 2.58%   |
| FreeBSD 13.0-CURRENT | 31        | 2.35%   |
| FreeBSD 13.0-STABLE  | 28        | 2.13%   |
| FreeBSD 12.1         | 28        | 2.13%   |
| FreeBSD 12.1-p8      | 26        | 1.97%   |
| FreeBSD 13.0-p5      | 25        | 1.9%    |
| FreeBSD 13.0-p3      | 23        | 1.75%   |
| FreeBSD 12.2-p4      | 23        | 1.75%   |
| FreeBSD 12.1-p10     | 23        | 1.75%   |
| FreeBSD 13.1-p7      | 22        | 1.67%   |
| FreeBSD 13.1-p2      | 21        | 1.59%   |
| FreeBSD 14.0-p4      | 20        | 1.52%   |
| FreeBSD 12.1-p5      | 20        | 1.52%   |
| FreeBSD 13.0-p7      | 19        | 1.44%   |
| FreeBSD 12.2-p3      | 18        | 1.37%   |
| FreeBSD 13.0-p2      | 17        | 1.29%   |
| FreeBSD 13.1-STABLE  | 15        | 1.14%   |
| FreeBSD 12.1-STABLE  | 15        | 1.14%   |
| FreeBSD 12.1-p7      | 15        | 1.14%   |
| FreeBSD 13.2-p2      | 14        | 1.06%   |
| FreeBSD 13.0-p6      | 13        | 0.99%   |
| FreeBSD 12.2-p6      | 12        | 0.91%   |
| FreeBSD 13.2-p3      | 10        | 0.76%   |
| FreeBSD 12.2-STABLE  | 10        | 0.76%   |
| FreeBSD 13.2-p1      | 9         | 0.68%   |
| FreeBSD 13.1-p4      | 9         | 0.68%   |
| FreeBSD 13.1-p1      | 9         | 0.68%   |
| FreeBSD 13.0-p11     | 9         | 0.68%   |
| FreeBSD 15.0-CURRENT | 8         | 0.61%   |
| FreeBSD 13.2-p4      | 8         | 0.61%   |
| FreeBSD 14.0-p3      | 7         | 0.53%   |
| FreeBSD 14.0-p1      | 7         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| FreeBSD | 1092      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 1046      | 95.61%  |
| i386  | 47        | 4.3%    |
| arm64 | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 259       | 22.46%  |
| KDE5          | 234       | 20.29%  |
| Console       | 153       | 13.27%  |
| TWM           | 101       | 8.76%   |
| GNOME         | 100       | 8.67%   |
| i3            | 79        | 6.85%   |
| MATE          | 71        | 6.16%   |
| Openbox       | 35        | 3.04%   |
| Cinnamon      | 20        | 1.73%   |
| LXQt          | 19        | 1.65%   |
| AwesomeWM     | 16        | 1.39%   |
| Fluxbox       | 10        | 0.87%   |
| Enlightenment | 9         | 0.78%   |
| LXDE          | 8         | 0.69%   |
| Lumina        | 5         | 0.43%   |
| DWM           | 5         | 0.43%   |
| GNUstep       | 4         | 0.35%   |
| IceWM         | 3         | 0.26%   |
| X-Cinnamon    | 2         | 0.17%   |
| sway          | 2         | 0.17%   |
| StumpWM       | 2         | 0.17%   |
| spectrwm      | 2         | 0.17%   |
| Picom         | 2         | 0.17%   |
| Budgie        | 2         | 0.17%   |
| Xfwm4         | 1         | 0.09%   |
| wlroots       | 1         | 0.09%   |
| Window Maker  | 1         | 0.09%   |
| Potato        | 1         | 0.09%   |
| Hyprland      | 1         | 0.09%   |
| helloDesktop  | 1         | 0.09%   |
| ctwm          | 1         | 0.09%   |
| Compton       | 1         | 0.09%   |
| CDE           | 1         | 0.09%   |
| awesome       | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 912       | 81.72%  |
| Console | 158       | 14.16%  |
| Wayland | 46        | 4.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 451       | 39.35%  |
| SDDM    | 244       | 21.29%  |
| SLiM    | 178       | 15.53%  |
| LightDM | 107       | 9.34%   |
| XDM     | 87        | 7.59%   |
| GDM     | 62        | 5.41%   |
| Ly      | 14        | 1.22%   |
| PCDM    | 2         | 0.17%   |
| WDM     | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| C                | 545       | 47.43%  |
| Unknown          | 245       | 21.32%  |
| en_US            | 144       | 12.53%  |
| ru_RU            | 42        | 3.66%   |
| fr_FR            | 28        | 2.44%   |
| de_DE            | 20        | 1.74%   |
| en_GB            | 18        | 1.57%   |
| zh_CN            | 12        | 1.04%   |
| pl_PL            | 6         | 0.52%   |
| es_ES            | 6         | 0.52%   |
| en_CA            | 6         | 0.52%   |
| pt_BR            | 5         | 0.44%   |
| cs_CZ            | 5         | 0.44%   |
| nb_NO            | 4         | 0.35%   |
| en_US.ISO8859-1  | 4         | 0.35%   |
| en_NZ            | 4         | 0.35%   |
| en_AU            | 4         | 0.35%   |
| uk_UA            | 3         | 0.26%   |
| ja_JP            | 3         | 0.26%   |
| es_AR            | 3         | 0.26%   |
| en_US.US-ASCII   | 3         | 0.26%   |
| de_CH            | 3         | 0.26%   |
| it_IT            | 2         | 0.17%   |
| en_SG            | 2         | 0.17%   |
| en_IE            | 2         | 0.17%   |
| de_DE.ISO8859-1  | 2         | 0.17%   |
| de               | 2         | 0.17%   |
| zh_TW            | 1         | 0.09%   |
| zh_CN.GB2312     | 1         | 0.09%   |
| sl_SI            | 1         | 0.09%   |
| pt_PT            | 1         | 0.09%   |
| POSIX            | 1         | 0.09%   |
| nl_NL            | 1         | 0.09%   |
| ko_KR            | 1         | 0.09%   |
| it_IT.ISO8859-15 | 1         | 0.09%   |
| it_IT.ISO8859-1  | 1         | 0.09%   |
| it_CH            | 1         | 0.09%   |
| hu_HU.US-ASCII   | 1         | 0.09%   |
| fi_FI            | 1         | 0.09%   |
| es_MX            | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 812       | 73.82%  |
| BIOS | 288       | 26.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 721       | 65.07%  |
| Ufs  | 385       | 34.75%  |
| Xfs  | 1         | 0.09%   |
| Nfs  | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 987       | 89.81%  |
| MBR     | 102       | 9.28%   |
| BSD     | 7         | 0.64%   |
| Unknown | 3         | 0.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 395       | 36.17%  |
| Dell                   | 205       | 18.77%  |
| Hewlett-Packard        | 100       | 9.16%   |
| ASUSTek Computer       | 74        | 6.78%   |
| Acer                   | 60        | 5.49%   |
| Apple                  | 32        | 2.93%   |
| Toshiba                | 23        | 2.11%   |
| Samsung Electronics    | 18        | 1.65%   |
| Google                 | 15        | 1.37%   |
| System76               | 13        | 1.19%   |
| MSI                    | 12        | 1.1%    |
| HUAWEI                 | 11        | 1.01%   |
| TUXEDO                 | 9         | 0.82%   |
| Sony                   | 9         | 0.82%   |
| Unknown                | 7         | 0.64%   |
| Notebook               | 6         | 0.55%   |
| IBM                    | 6         | 0.55%   |
| Fujitsu                | 6         | 0.55%   |
| Panasonic              | 5         | 0.46%   |
| Framework              | 5         | 0.46%   |
| Alienware              | 5         | 0.46%   |
| Timi                   | 4         | 0.37%   |
| LG Electronics         | 4         | 0.37%   |
| Intel                  | 4         | 0.37%   |
| Gigabyte Technology    | 4         | 0.37%   |
| Razer                  | 3         | 0.27%   |
| Medion                 | 3         | 0.27%   |
| Gateway                | 3         | 0.27%   |
| F-Plus Mobile          | 3         | 0.27%   |
| Deciso                 | 3         | 0.27%   |
| Clevo                  | 3         | 0.27%   |
| Avell High Performance | 3         | 0.27%   |
| Valve                  | 2         | 0.18%   |
| Schenker               | 2         | 0.18%   |
| HMT                    | 2         | 0.18%   |
| GPD                    | 2         | 0.18%   |
| Fujitsu Siemens        | 2         | 0.18%   |
| BANGHO                 | 2         | 0.18%   |
| Wortmann AG            | 1         | 0.09%   |
| WOOKING                | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 11        | 1.01%   |
| HP EliteBook 840 G3             | 5         | 0.46%   |
| Framework Laptop                | 5         | 0.46%   |
| Dell Latitude E7240             | 5         | 0.46%   |
| Dell Latitude E6430             | 5         | 0.46%   |
| System76 Lemur Pro              | 4         | 0.37%   |
| HP EliteBook 8570p              | 4         | 0.37%   |
| Dell XPS 13 9360                | 4         | 0.37%   |
| Dell Latitude E7450             | 4         | 0.37%   |
| Dell Inspiron 15 7000 Gaming    | 4         | 0.37%   |
| Lenovo ThinkPad T490 20N2CTO1WW | 3         | 0.27%   |
| Lenovo IdeaPad 330-15ARR 81D2   | 3         | 0.27%   |
| HUAWEI MACH-WX9                 | 3         | 0.27%   |
| Google Peppy                    | 3         | 0.27%   |
| F-Plus Mobile FLAPTOP r         | 3         | 0.27%   |
| Dell XPS 13 9343                | 3         | 0.27%   |
| Dell Precision M4800            | 3         | 0.27%   |
| Dell Latitude E7440             | 3         | 0.27%   |
| Dell Latitude E6420             | 3         | 0.27%   |
| Dell Latitude E5470             | 3         | 0.27%   |
| Dell Latitude E5420             | 3         | 0.27%   |
| Dell Latitude 7490              | 3         | 0.27%   |
| Dell Latitude 7390              | 3         | 0.27%   |
| Dell Latitude 2100              | 3         | 0.27%   |
| Dell Inspiron 3542              | 3         | 0.27%   |
| Dell Inspiron 3521              | 3         | 0.27%   |
| Apple MacBookPro6,2             | 3         | 0.27%   |
| Valve Jupiter                   | 2         | 0.18%   |
| TUXEDO Pulse 15 Gen1            | 2         | 0.18%   |
| Toshiba Satellite A300          | 2         | 0.18%   |
| System76 Gazelle                | 2         | 0.18%   |
| System76 Galago Pro             | 2         | 0.18%   |
| System76 Bonobo Extreme         | 2         | 0.18%   |
| Samsung NC10                    | 2         | 0.18%   |
| Samsung 340XAA/350XAA/550XAA    | 2         | 0.18%   |
| Notebook NL5xRU                 | 2         | 0.18%   |
| LG 16UD70R-G.AX59B              | 2         | 0.18%   |
| Lenovo ThinkPad X220 42915CG    | 2         | 0.18%   |
| Lenovo ThinkPad X220 42872WU    | 2         | 0.18%   |
| Lenovo ThinkPad X220 4286CTO    | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 311       | 28.48%  |
| Dell Latitude         | 86        | 7.88%   |
| Dell Inspiron         | 53        | 4.85%   |
| Lenovo IdeaPad        | 40        | 3.66%   |
| Acer Aspire           | 37        | 3.39%   |
| Dell Precision        | 23        | 2.11%   |
| HP EliteBook          | 21        | 1.92%   |
| HP ProBook            | 19        | 1.74%   |
| Dell XPS              | 18        | 1.65%   |
| Toshiba Satellite     | 16        | 1.47%   |
| Dell Vostro           | 15        | 1.37%   |
| HP Pavilion           | 13        | 1.19%   |
| HP Laptop             | 12        | 1.1%    |
| Unknown               | 11        | 1.01%   |
| Lenovo Legion         | 9         | 0.82%   |
| HP Compaq             | 8         | 0.73%   |
| ASUS ZenBook          | 8         | 0.73%   |
| ASUS ASUS             | 8         | 0.73%   |
| ASUS VivoBook         | 7         | 0.64%   |
| IBM ThinkPad          | 6         | 0.55%   |
| Lenovo ThinkBook      | 5         | 0.46%   |
| Fujitsu LIFEBOOK      | 5         | 0.46%   |
| Framework Laptop      | 5         | 0.46%   |
| Apple MacBookPro8     | 5         | 0.46%   |
| Acer TravelMate       | 5         | 0.46%   |
| Acer Swift            | 5         | 0.46%   |
| TUXEDO Pulse          | 4         | 0.37%   |
| System76 Lemur        | 4         | 0.37%   |
| Lenovo Yoga           | 4         | 0.37%   |
| HP ZBook              | 4         | 0.37%   |
| HP ENVY               | 4         | 0.37%   |
| Apple MacBookPro11    | 4         | 0.37%   |
| Acer Nitro            | 4         | 0.37%   |
| Razer Blade           | 3         | 0.27%   |
| HUAWEI MACH-WX9       | 3         | 0.27%   |
| HP 255                | 3         | 0.27%   |
| Google Peppy          | 3         | 0.27%   |
| F-Plus Mobile FLAPTOP | 3         | 0.27%   |
| Dell Studio           | 3         | 0.27%   |
| Dell G5               | 3         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 131       | 12%     |
| 2021 | 103       | 9.43%   |
| 2019 | 101       | 9.25%   |
| 2018 | 91        | 8.33%   |
| 2011 | 83        | 7.6%    |
| 2022 | 75        | 6.87%   |
| 2016 | 69        | 6.32%   |
| 2015 | 66        | 6.04%   |
| 2013 | 59        | 5.4%    |
| 2012 | 58        | 5.31%   |
| 2017 | 53        | 4.85%   |
| 2010 | 47        | 4.3%    |
| 2014 | 37        | 3.39%   |
| 2023 | 32        | 2.93%   |
| 2008 | 28        | 2.56%   |
| 2009 | 23        | 2.11%   |
| 2007 | 16        | 1.47%   |
| 2006 | 10        | 0.92%   |
| 2003 | 3         | 0.27%   |
| 2005 | 2         | 0.18%   |
| 2004 | 2         | 0.18%   |
| 2002 | 2         | 0.18%   |
| 2024 | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1092      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1066      | 97.62%  |
| Yes  | 26        | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 353       | 31.8%   |
| 16.01-24.0  | 339       | 30.54%  |
| 4.01-8.0    | 182       | 16.4%   |
| 32.01-64.0  | 101       | 9.1%    |
| 2.01-3.0    | 54        | 4.86%   |
| 64.01-256.0 | 22        | 1.98%   |
| 24.01-32.0  | 18        | 1.62%   |
| 3.01-4.0    | 17        | 1.53%   |
| 0.51-1.0    | 12        | 1.08%   |
| 1.01-2.0    | 8         | 0.72%   |
| 0.01-0.5    | 4         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 456       | 40.86%  |
| 0.51-1.0   | 381       | 34.14%  |
| 1.01-2.0   | 184       | 16.49%  |
| 2.01-3.0   | 44        | 3.94%   |
| 4.01-8.0   | 19        | 1.7%    |
| 8.01-16.0  | 14        | 1.25%   |
| 3.01-4.0   | 7         | 0.63%   |
| 16.01-24.0 | 4         | 0.36%   |
| 24.01-32.0 | 3         | 0.27%   |
| 32.01-64.0 | 2         | 0.18%   |
| 0          | 2         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 796       | 71.07%  |
| 2      | 207       | 18.48%  |
| 0      | 83        | 7.41%   |
| 3      | 30        | 2.68%   |
| 4      | 3         | 0.27%   |
| 58     | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 811       | 73.66%  |
| Yes       | 290       | 26.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 888       | 81.32%  |
| No        | 204       | 18.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1070      | 97.63%  |
| No        | 26        | 2.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 792       | 71.67%  |
| No        | 313       | 28.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 235       | 21.23%  |
| Germany     | 107       | 9.67%   |
| Russia      | 89        | 8.04%   |
| France      | 73        | 6.59%   |
| UK          | 46        | 4.16%   |
| China       | 38        | 3.43%   |
| Canada      | 31        | 2.8%    |
| Poland      | 29        | 2.62%   |
| Brazil      | 28        | 2.53%   |
| Australia   | 28        | 2.53%   |
| Ukraine     | 23        | 2.08%   |
| Switzerland | 23        | 2.08%   |
| Spain       | 21        | 1.9%    |
| India       | 21        | 1.9%    |
| Austria     | 21        | 1.9%    |
| Netherlands | 20        | 1.81%   |
| Czechia     | 17        | 1.54%   |
| Indonesia   | 16        | 1.45%   |
| Italy       | 13        | 1.17%   |
| Argentina   | 13        | 1.17%   |
| Japan       | 12        | 1.08%   |
| Sweden      | 11        | 0.99%   |
| Romania     | 9         | 0.81%   |
| Thailand    | 8         | 0.72%   |
| Portugal    | 8         | 0.72%   |
| New Zealand | 7         | 0.63%   |
| Mexico      | 7         | 0.63%   |
| Ireland     | 7         | 0.63%   |
| Denmark     | 7         | 0.63%   |
| Algeria     | 7         | 0.63%   |
| Vietnam     | 6         | 0.54%   |
| Turkey      | 6         | 0.54%   |
| Norway      | 6         | 0.54%   |
| Greece      | 6         | 0.54%   |
| Finland     | 6         | 0.54%   |
| Iran        | 5         | 0.45%   |
| Hungary     | 5         | 0.45%   |
| Bulgaria    | 5         | 0.45%   |
| Slovenia    | 4         | 0.36%   |
| Philippines | 4         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Moscow          | 41        | 3.42%   |
| Vienna          | 20        | 1.67%   |
| Brooklyn        | 20        | 1.67%   |
| Sydney          | 14        | 1.17%   |
| Berlin          | 14        | 1.17%   |
| Paris           | 13        | 1.09%   |
| Kyiv            | 10        | 0.83%   |
| Zurich          | 9         | 0.75%   |
| Warsaw          | 9         | 0.75%   |
| St Petersburg   | 9         | 0.75%   |
| Shanghai        | 7         | 0.58%   |
| Portland        | 7         | 0.58%   |
| Jakarta         | 7         | 0.58%   |
| Dublin          | 7         | 0.58%   |
| Brighton        | 7         | 0.58%   |
| Amsterdam       | 7         | 0.58%   |
| Seattle         | 6         | 0.5%    |
| New York        | 5         | 0.42%   |
| Montreal        | 5         | 0.42%   |
| London          | 5         | 0.42%   |
| Chicago         | 5         | 0.42%   |
| Brno            | 5         | 0.42%   |
| Barcelona       | 5         | 0.42%   |
| Stockholm       | 4         | 0.33%   |
| Nuremberg       | 4         | 0.33%   |
| Munich          | 4         | 0.33%   |
| Milan           | 4         | 0.33%   |
| Glasgow         | 4         | 0.33%   |
| Christchurch    | 4         | 0.33%   |
| Bucharest       | 4         | 0.33%   |
| Zagreb          | 3         | 0.25%   |
| Wernigerode     | 3         | 0.25%   |
| Vancouver       | 3         | 0.25%   |
| Urcuit          | 3         | 0.25%   |
| Ulyanovsk       | 3         | 0.25%   |
| Tuklaty         | 3         | 0.25%   |
| Tehran          | 3         | 0.25%   |
| Sofia           | 3         | 0.25%   |
| Singapore       | 3         | 0.25%   |
| Shoreham-by-Sea | 3         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 271       | 380    | 21.61%  |
| WDC                 | 169       | 224    | 13.48%  |
| Seagate             | 98        | 126    | 7.81%   |
| Toshiba             | 89        | 138    | 7.1%    |
| Kingston            | 76        | 103    | 6.06%   |
| Crucial             | 73        | 105    | 5.82%   |
| SanDisk             | 53        | 68     | 4.23%   |
| Intel               | 44        | 58     | 3.51%   |
| Hitachi             | 43        | 51     | 3.43%   |
| SK hynix            | 38        | 43     | 3.03%   |
| HGST                | 28        | 96     | 2.23%   |
| Transcend           | 26        | 32     | 2.07%   |
| Micron Technology   | 24        | 30     | 1.91%   |
| A-DATA Technology   | 21        | 26     | 1.67%   |
| KIOXIA              | 16        | 16     | 1.28%   |
| Apple               | 12        | 12     | 0.96%   |
| Fujitsu             | 11        | 16     | 0.88%   |
| Phison              | 10        | 16     | 0.8%    |
| KingSpec            | 9         | 12     | 0.72%   |
| PNY                 | 8         | 9      | 0.64%   |
| LITEON              | 8         | 13     | 0.64%   |
| Gigabyte Technology | 8         | 11     | 0.64%   |
| SPCC                | 7         | 9      | 0.56%   |
| OWC                 | 7         | 8      | 0.56%   |
| Hewlett-Packard     | 7         | 7      | 0.56%   |
| SSSTC               | 6         | 8      | 0.48%   |
| Silicon Motion      | 6         | 7      | 0.48%   |
| Lenovo              | 5         | 6      | 0.4%    |
| China               | 5         | 6      | 0.4%    |
| UMIS                | 4         | 4      | 0.32%   |
| OCZ                 | 4         | 5      | 0.32%   |
| Mushkin             | 4         | 4      | 0.32%   |
| Hikvision           | 4         | 5      | 0.32%   |
| FORESEE             | 4         | 4      | 0.32%   |
| Corsair             | 4         | 5      | 0.32%   |
| Union Memory        | 3         | 3      | 0.24%   |
| BIWIN               | 3         | 4      | 0.24%   |
| Apacer              | 3         | 3      | 0.24%   |
| Zheino              | 2         | 3      | 0.16%   |
| V-GeN               | 2         | 5      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 21        | 1.61%   |
| Samsung SSD 860 EVO 500GB            | 15        | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 14        | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB       | 13        | 0.99%   |
| Toshiba MQ01ABD100 1TB               | 12        | 0.92%   |
| HGST HTS721010A9E630 1TB             | 12        | 0.92%   |
| Toshiba MQ01ABF050 500GB             | 11        | 0.84%   |
| Crucial CT500MX500SSD1 500GB         | 11        | 0.84%   |
| Seagate ST500LT012-1DG142 500GB      | 9         | 0.69%   |
| Samsung SSD 850 EVO 500GB            | 9         | 0.69%   |
| HGST HTS725050A7E630 500GB           | 9         | 0.69%   |
| Crucial CT1000MX500SSD1 1TB          | 9         | 0.69%   |
| Toshiba MQ04ABF100 1TB               | 8         | 0.61%   |
| Samsung SSD 970 EVO Plus 1TB         | 8         | 0.61%   |
| Samsung SSD 850 EVO 250GB            | 8         | 0.61%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 7         | 0.54%   |
| Samsung SSD 970 EVO 500GB            | 7         | 0.54%   |
| Samsung SSD 870 EVO 1TB              | 7         | 0.54%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 6         | 0.46%   |
| SanDisk SSD PLUS 240GB               | 6         | 0.46%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 6         | 0.46%   |
| Samsung MZVLB512HAJQ-000L7 512GB     | 6         | 0.46%   |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 6         | 0.46%   |
| Intel SSDPEKKF512G8L 512GB           | 6         | 0.46%   |
| Intel SSDPEKKF256G8L 256GB           | 6         | 0.46%   |
| Crucial CT2000MX500SSD1 2TB          | 6         | 0.46%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 5         | 0.38%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 5         | 0.38%   |
| Seagate ST9500325AS 500GB            | 5         | 0.38%   |
| Seagate ST1000LM048-2E7172 1TB       | 5         | 0.38%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 5         | 0.38%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 5         | 0.38%   |
| Kingston SA400S37480G 480GB          | 5         | 0.38%   |
| Crucial CT1000P1SSD8 1TB             | 5         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.31%   |
| Transcend TS128GMTS430S 128GB        | 4         | 0.31%   |
| Seagate ST9500420AS 500GB            | 4         | 0.31%   |
| Seagate ST9250315AS 250GB            | 4         | 0.31%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 0.31%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 96        | 124    | 28.15%  |
| WDC                 | 93        | 114    | 27.27%  |
| Toshiba             | 60        | 92     | 17.6%   |
| Hitachi             | 43        | 51     | 12.61%  |
| HGST                | 28        | 96     | 8.21%   |
| Fujitsu             | 11        | 16     | 3.23%   |
| Samsung Electronics | 7         | 7      | 2.05%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| HPE                 | 1         | 5      | 0.29%   |
| Apple               | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 135       | 192    | 25.28%  |
| Kingston            | 60        | 84     | 11.24%  |
| Crucial             | 56        | 79     | 10.49%  |
| SanDisk             | 52        | 67     | 9.74%   |
| WDC                 | 23        | 40     | 4.31%   |
| Transcend           | 23        | 28     | 4.31%   |
| Intel               | 21        | 32     | 3.93%   |
| SK hynix            | 14        | 15     | 2.62%   |
| A-DATA Technology   | 12        | 15     | 2.25%   |
| Micron Technology   | 11        | 14     | 2.06%   |
| Apple               | 11        | 11     | 2.06%   |
| Toshiba             | 10        | 11     | 1.87%   |
| KingSpec            | 9         | 12     | 1.69%   |
| OWC                 | 7         | 8      | 1.31%   |
| LITEON              | 7         | 12     | 1.31%   |
| PNY                 | 6         | 7      | 1.12%   |
| Hewlett-Packard     | 6         | 6      | 1.12%   |
| SPCC                | 5         | 6      | 0.94%   |
| Gigabyte Technology | 5         | 6      | 0.94%   |
| China               | 5         | 6      | 0.94%   |
| OCZ                 | 4         | 5      | 0.75%   |
| Corsair             | 4         | 5      | 0.75%   |
| Mushkin             | 3         | 3      | 0.56%   |
| Lenovo              | 3         | 4      | 0.56%   |
| Apacer              | 3         | 3      | 0.56%   |
| Zheino              | 2         | 3      | 0.37%   |
| Team                | 2         | 3      | 0.37%   |
| Seagate             | 2         | 2      | 0.37%   |
| Patriot             | 2         | 3      | 0.37%   |
| MidasForce          | 2         | 2      | 0.37%   |
| Lexar               | 2         | 8      | 0.37%   |
| Intenso             | 2         | 2      | 0.37%   |
| Hikvision           | 2         | 3      | 0.37%   |
| BIWIN               | 2         | 3      | 0.37%   |
| ZTC                 | 1         | 1      | 0.19%   |
| Verbatim            | 1         | 1      | 0.19%   |
| V-GeN               | 1         | 4      | 0.19%   |
| TCSUNBOW            | 1         | 1      | 0.19%   |
| SSSTC               | 1         | 1      | 0.19%   |
| SMI                 | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 477       | 726    | 41.23%  |
| NVMe | 364       | 501    | 31.46%  |
| HDD  | 316       | 507    | 27.31%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 732       | 1233   | 66.79%  |
| NVMe | 364       | 501    | 33.21%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 560       | 834    | 69.74%  |
| 0.51-1.0   | 194       | 288    | 24.16%  |
| 1.01-2.0   | 43        | 56     | 5.35%   |
| 3.01-4.0   | 4         | 52     | 0.5%    |
| 2.01-3.0   | 1         | 2      | 0.12%   |
| 4.01-10.0  | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 413       | 36.13%  |
| 251-500        | 324       | 28.35%  |
| 501-1000       | 168       | 14.7%   |
| 51-100         | 104       | 9.1%    |
| 21-50          | 62        | 5.42%   |
| 1001-2000      | 34        | 2.97%   |
| 1-20           | 30        | 2.62%   |
| Unknown        | 4         | 0.35%   |
| 2001-3000      | 3         | 0.26%   |
| More than 3000 | 1         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 833       | 72.81%  |
| 21-50          | 173       | 15.12%  |
| 51-100         | 58        | 5.07%   |
| 101-250        | 53        | 4.63%   |
| 251-500        | 14        | 1.22%   |
| 501-1000       | 8         | 0.7%    |
| Unknown        | 4         | 0.35%   |
| More than 3000 | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 4.19%   |
| HGST HTS725050A7E630 500GB         | 5         | 9      | 2.99%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 7      | 2.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 2.4%    |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 1.8%    |
| Toshiba MQ01ABD100 1TB             | 3         | 3      | 1.8%    |
| Seagate ST9500420AS 500GB          | 3         | 4      | 1.8%    |
| Seagate ST9250315AS 250GB          | 3         | 4      | 1.8%    |
| Hitachi HTS547550A9E384 500GB      | 3         | 3      | 1.8%    |
| HGST HTS721010A9E630 1TB           | 3         | 21     | 1.8%    |
| WDC WD3200BPVT-80JJ5T0 320GB       | 2         | 2      | 1.2%    |
| Toshiba MK2546GSX 250GB            | 2         | 2      | 1.2%    |
| Seagate ST9500325AS 500GB          | 2         | 4      | 1.2%    |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.2%    |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 2      | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.2%    |
| Seagate ST2000LM003 HN-M201RAD 2TB | 2         | 2      | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.2%    |
| Micron Technology 1100 SATA 256GB  | 2         | 2      | 1.2%    |
| Kingston SV300S37A120G 120GB       | 2         | 2      | 1.2%    |
| Kingston SNS4151S316GD 16GB        | 2         | 2      | 1.2%    |
| Intel SSDSCKKF256G8H 256GB         | 2         | 5      | 1.2%    |
| Hitachi HTS545032B9A300 320GB      | 2         | 3      | 1.2%    |
| Hitachi HTS541612J9SA00 120GB      | 2         | 2      | 1.2%    |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 1      | 0.6%    |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 1      | 0.6%    |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 1      | 0.6%    |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000B 500GB                  | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-75JJ5T0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BEKT-22PVMT0 320GB       | 1         | 1      | 0.6%    |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 0.6%    |
| WDC WD2000JB-00GVC0 200GB          | 1         | 1      | 0.6%    |
| WDC WD15EARS-00Z5B1 1.5TB          | 1         | 1      | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 0.6%    |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.6%    |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 0.6%    |
| Transcend TS256GSSD320 256GB       | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 54     | 24.84%  |
| Hitachi             | 21        | 24     | 13.04%  |
| Toshiba             | 19        | 27     | 11.8%   |
| WDC                 | 16        | 17     | 9.94%   |
| Samsung Electronics | 14        | 15     | 8.7%    |
| Kingston            | 11        | 13     | 6.83%   |
| HGST                | 7         | 31     | 4.35%   |
| Intel               | 6         | 9      | 3.73%   |
| SK hynix            | 3         | 3      | 1.86%   |
| SanDisk             | 3         | 3      | 1.86%   |
| Micron Technology   | 3         | 3      | 1.86%   |
| Fujitsu             | 3         | 6      | 1.86%   |
| Crucial             | 3         | 3      | 1.86%   |
| Apple               | 2         | 2      | 1.24%   |
| A-DATA Technology   | 2         | 3      | 1.24%   |
| Transcend           | 1         | 1      | 0.62%   |
| SSSTC               | 1         | 1      | 0.62%   |
| SMI                 | 1         | 1      | 0.62%   |
| OCZ                 | 1         | 1      | 0.62%   |
| Lenovo              | 1         | 1      | 0.62%   |
| IBM/Hitachi         | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 1      | 0.62%   |
| Fanxiang            | 1         | 1      | 0.62%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 54     | 36.04%  |
| Hitachi             | 21        | 24     | 18.92%  |
| Toshiba             | 19        | 27     | 17.12%  |
| WDC                 | 16        | 17     | 14.41%  |
| HGST                | 7         | 31     | 6.31%   |
| Samsung Electronics | 3         | 3      | 2.7%    |
| Fujitsu             | 3         | 6      | 2.7%    |
| IBM/Hitachi         | 1         | 1      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 107       | 164    | 68.15%  |
| SSD  | 47        | 54     | 29.94%  |
| NVMe | 3         | 3      | 1.91%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                 | 1         | 1      | 50%     |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 908       | 1501   | 84.39%  |
| Malfunc  | 157       | 221    | 14.59%  |
| Detected | 9         | 10     | 0.84%   |
| Failed   | 2         | 2      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 741       | 58.39%  |
| Samsung Electronics                     | 155       | 12.21%  |
| AMD                                     | 92        | 7.25%   |
| SanDisk                                 | 65        | 5.12%   |
| SK hynix                                | 29        | 2.29%   |
| Toshiba                                 | 26        | 2.05%   |
| Phison Electronics                      | 20        | 1.58%   |
| Kingston Technology Company             | 18        | 1.42%   |
| Micron/Crucial Technology               | 17        | 1.34%   |
| Micron Technology                       | 17        | 1.34%   |
| Silicon Motion                          | 15        | 1.18%   |
| KIOXIA                                  | 15        | 1.18%   |
| Solid State Storage Technology          | 7         | 0.55%   |
| Nvidia                                  | 7         | 0.55%   |
| ADATA Technology                        | 7         | 0.55%   |
| Union Memory (Shenzhen)                 | 6         | 0.47%   |
| Shenzhen Longsys Electronics            | 5         | 0.39%   |
| Realtek Semiconductor                   | 4         | 0.32%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.24%   |
| Shenzhen Unionmemory Information System | 3         | 0.24%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.24%   |
| Transcend                               | 2         | 0.16%   |
| Lenovo                                  | 2         | 0.16%   |
| JMicron Technology                      | 2         | 0.16%   |
| INNOGRIT                                | 2         | 0.16%   |
| ULi Electronics                         | 1         | 0.08%   |
| Marvell Technology Group                | 1         | 0.08%   |
| Lite-On Technology                      | 1         | 0.08%   |
| Broadcom / LSI                          | 1         | 0.08%   |
| Biwin Storage Technology                | 1         | 0.08%   |
| Apple                                   | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 94        | 6.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 85        | 6.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 78        | 5.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 78        | 5.79%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 77        | 5.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 54        | 4.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 3.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 2.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 33        | 2.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 31        | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 29        | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 26        | 1.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 25        | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 25        | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 25        | 1.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 1.49%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 19        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 1.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 17        | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 15        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 15        | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 1.04%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 13        | 0.97%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 12        | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 12        | 0.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 11        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 11        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 11        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 11        | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 11        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 9         | 0.67%   |
| Toshiba XG5 NVMe SSD Controller                                                | 8         | 0.59%   |
| SK hynix BC511 NVMe SSD                                                        | 8         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 732       | 56.88%  |
| NVMe | 409       | 31.78%  |
| IDE  | 90        | 6.99%   |
| RAID | 55        | 4.27%   |
| SAS  | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 934       | 85.3%   |
| AMD    | 160       | 14.61%  |
| ARM    | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 25        | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 1.82%   |
| Intel CPU Version                       | 18        | 1.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 18        | 1.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 17        | 1.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 17        | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 16        | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 15        | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 1.36%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 15        | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 15        | 1.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 14        | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 14        | 1.27%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 13        | 1.18%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz       | 11        | 1%      |
| Intel Core i5-7300U CPU @ 2.60GHz       | 11        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz       | 10        | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.91%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 10        | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 9         | 0.82%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 9         | 0.82%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 9         | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 8         | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 0.73%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 8         | 0.73%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 7         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 7         | 0.64%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 7         | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 7         | 0.64%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 7         | 0.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 7         | 0.64%   |
| Intel Core 2 Duo                        | 7         | 0.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 7         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 332       | 30.26%  |
| Intel Core i7           | 269       | 24.52%  |
| Other                   | 105       | 9.57%   |
| Intel Core i3           | 51        | 4.65%   |
| AMD Ryzen 7             | 49        | 4.47%   |
| Intel Celeron           | 48        | 4.38%   |
| Intel Core 2 Duo        | 44        | 4.01%   |
| AMD Ryzen 5             | 35        | 3.19%   |
| Intel Atom              | 20        | 1.82%   |
| Intel Pentium           | 14        | 1.28%   |
| Intel Pentium M         | 13        | 1.19%   |
| AMD Ryzen 7 PRO         | 13        | 1.19%   |
| AMD Ryzen 5 PRO         | 8         | 0.73%   |
| AMD Ryzen 3             | 8         | 0.73%   |
| Intel Core 2            | 7         | 0.64%   |
| Intel Xeon              | 6         | 0.55%   |
| AMD E                   | 6         | 0.55%   |
| Intel Pentium Silver    | 5         | 0.46%   |
| Intel Pentium Dual      | 5         | 0.46%   |
| Intel Genuine           | 5         | 0.46%   |
| AMD Ryzen 9             | 4         | 0.36%   |
| AMD A8                  | 4         | 0.36%   |
| AMD A6                  | 4         | 0.36%   |
| AMD A4                  | 4         | 0.36%   |
| Intel Pentium 4         | 3         | 0.27%   |
| Intel Core i9           | 3         | 0.27%   |
| AMD E2                  | 3         | 0.27%   |
| AMD C-50                | 3         | 0.27%   |
| AMD Athlon              | 3         | 0.27%   |
| Intel Core m3           | 2         | 0.18%   |
| Intel Celeron M         | 2         | 0.18%   |
| AMD EPYC                | 2         | 0.18%   |
| AMD E1                  | 2         | 0.18%   |
| Intel Pentium Dual-Core | 1         | 0.09%   |
| Intel Mobile Pentium 4  | 1         | 0.09%   |
| Intel Core Solo         | 1         | 0.09%   |
| Intel Core m7           | 1         | 0.09%   |
| Intel Core M            | 1         | 0.09%   |
| Intel Core Duo          | 1         | 0.09%   |
| Intel Core 2 Extreme    | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 476       | 43.35%  |
| 4       | 335       | 30.51%  |
| Unknown | 63        | 5.74%   |
| 8       | 54        | 4.92%   |
| 16      | 53        | 4.83%   |
| 6       | 45        | 4.1%    |
| 1       | 36        | 3.28%   |
| 12      | 24        | 2.19%   |
| 10      | 7         | 0.64%   |
| 20      | 2         | 0.18%   |
| 32      | 1         | 0.09%   |
| 24      | 1         | 0.09%   |
| 5       | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 1083      | 99.09%  |
| 2       | 9         | 0.82%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 748       | 68.19%  |
| 1       | 270       | 24.61%  |
| Unknown | 79        | 7.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 236       | 21.55%  |
| SandyBridge     | 94        | 8.58%   |
| IvyBridge       | 87        | 7.95%   |
| Skylake         | 74        | 6.76%   |
| Haswell         | 73        | 6.67%   |
| Unknown         | 65        | 5.94%   |
| Broadwell       | 58        | 5.3%    |
| TigerLake       | 50        | 4.57%   |
| Penryn          | 39        | 3.56%   |
| Core            | 34        | 3.11%   |
| Westmere        | 33        | 3.01%   |
| Bonnell         | 32        | 2.92%   |
| Zen 2           | 31        | 2.83%   |
| Zen+            | 26        | 2.37%   |
| Silvermont      | 25        | 2.28%   |
| Zen 3           | 23        | 2.1%    |
| CometLake       | 19        | 1.74%   |
| P6              | 16        | 1.46%   |
| Zen             | 15        | 1.37%   |
| Goldmont plus   | 13        | 1.19%   |
| Puma            | 9         | 0.82%   |
| IceLake         | 9         | 0.82%   |
| Bobcat          | 9         | 0.82%   |
| Excavator       | 7         | 0.64%   |
| NetBurst        | 4         | 0.37%   |
| Goldmont        | 3         | 0.27%   |
| Piledriver      | 2         | 0.18%   |
| Nehalem         | 2         | 0.18%   |
| K8 Hammer       | 2         | 0.18%   |
| K8 & K10 hybrid | 2         | 0.18%   |
| K10 Llano       | 1         | 0.09%   |
| K10             | 1         | 0.09%   |
| Jaguar          | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 849       | 65.06%  |
| Nvidia                           | 240       | 18.39%  |
| AMD                              | 213       | 16.32%  |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| Silicon Motion                   | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 83        | 6.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 79        | 5.79%   |
| Intel UHD Graphics 620                                                                   | 56        | 4.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 52        | 3.81%   |
| Intel HD Graphics 5500                                                                   | 52        | 3.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 48        | 3.52%   |
| Intel HD Graphics 620                                                                    | 46        | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 42        | 3.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 39        | 2.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 2.27%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 30        | 2.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 1.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 25        | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 1.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 22        | 1.61%   |
| AMD Lucienne                                                                             | 20        | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 1.32%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 15        | 1.1%    |
| Intel HD Graphics 630                                                                    | 15        | 1.1%    |
| Intel HD Graphics 530                                                                    | 15        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.1%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 14        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.59%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.59%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.51%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.51%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 7         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 571       | 51.77%  |
| Intel + Nvidia           | 163       | 14.78%  |
| 1 x AMD                  | 156       | 14.14%  |
| 2 x Intel                | 87        | 7.89%   |
| 1 x Nvidia               | 61        | 5.53%   |
| Intel + AMD              | 27        | 2.45%   |
| AMD + Nvidia             | 17        | 1.54%   |
| 2 x AMD                  | 12        | 1.09%   |
| Other                    | 3         | 0.27%   |
| 2 x Nvidia               | 2         | 0.18%   |
| 1 x SiS                  | 2         | 0.18%   |
| 1 x Silicon Motion       | 1         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 981       | 88.54%  |
| Proprietary | 117       | 10.56%  |
| Unknown     | 10        | 0.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 913       | 82.1%   |
| 0.01-0.5   | 85        | 7.64%   |
| 1.01-2.0   | 42        | 3.78%   |
| 0.51-1.0   | 27        | 2.43%   |
| 3.01-4.0   | 22        | 1.98%   |
| 7.01-8.0   | 11        | 0.99%   |
| 5.01-6.0   | 7         | 0.63%   |
| 2.01-3.0   | 3         | 0.27%   |
| 8.01-16.0  | 2         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 180       | 20.2%   |
| LG Display              | 149       | 16.72%  |
| Chimei Innolux          | 100       | 11.22%  |
| BOE                     | 98        | 11%     |
| Samsung Electronics     | 61        | 6.85%   |
| Lenovo                  | 45        | 5.05%   |
| Sharp                   | 27        | 3.03%   |
| Dell                    | 20        | 2.24%   |
| Apple                   | 19        | 2.13%   |
| Hewlett-Packard         | 14        | 1.57%   |
| InfoVision              | 12        | 1.35%   |
| Goldstar                | 12        | 1.35%   |
| Chi Mei Optoelectronics | 11        | 1.23%   |
| AOC                     | 10        | 1.12%   |
| LGD                     | 8         | 0.9%    |
| Acer                    | 8         | 0.9%    |
| Philips                 | 7         | 0.79%   |
| PANDA                   | 7         | 0.79%   |
| LG Philips              | 7         | 0.79%   |
| CSO                     | 7         | 0.79%   |
| BenQ                    | 6         | 0.67%   |
| ViewSonic               | 5         | 0.56%   |
| JDI                     | 5         | 0.56%   |
| BOE Technology Group    | 5         | 0.56%   |
| Toshiba                 | 4         | 0.45%   |
| Sceptre Tech            | 4         | 0.45%   |
| Iiyama                  | 4         | 0.45%   |
| CPT                     | 4         | 0.45%   |
| Ancor Communications    | 4         | 0.45%   |
| HKC                     | 3         | 0.34%   |
| HannStar                | 3         | 0.34%   |
| ASUSTek Computer        | 3         | 0.34%   |
| Unknown                 | 3         | 0.34%   |
| Vizio                   | 2         | 0.22%   |
| Unknown                 | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| Lenovo Group Limited    | 2         | 0.22%   |
| HUAWEI                  | 2         | 0.22%   |
| HPN                     | 2         | 0.22%   |
| Eizo                    | 2         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 11        | 1.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 7         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 6         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 6         | 0.67%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 5         | 0.55%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 5         | 0.55%   |
| BOE Technology Group LCD Monitor 1920x1080                           | 5         | 0.55%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch       | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 5         | 0.55%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 5         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 4         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.44%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.44%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.44%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.44%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 4         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch             | 4         | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.44%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch     | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch       | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 310x170mm 13.9-inch       | 4         | 0.44%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 3         | 0.33%   |
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                  | 3         | 0.33%   |
| LGD LCD Monitor 1920x1080                                            | 3         | 0.33%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 3         | 0.33%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch          | 3         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 366       | 42.66%  |
| 1366x768 (WXGA)    | 214       | 24.94%  |
| 1600x900 (HD+)     | 48        | 5.59%   |
| 3840x2160 (4K)     | 37        | 4.31%   |
| 1280x800 (WXGA)    | 36        | 4.2%    |
| 2560x1440 (QHD)    | 30        | 3.5%    |
| 1920x1200 (WUXGA)  | 25        | 2.91%   |
| 1024x600           | 16        | 1.86%   |
| 1440x900 (WXGA+)   | 13        | 1.52%   |
| 2560x1600          | 11        | 1.28%   |
| 2560x1080          | 7         | 0.82%   |
| 2256x1504          | 6         | 0.7%    |
| Unknown            | 5         | 0.58%   |
| 3440x1440          | 4         | 0.47%   |
| 3200x1800 (QHD+)   | 4         | 0.47%   |
| 1680x1050 (WSXGA+) | 4         | 0.47%   |
| 1280x1024 (SXGA)   | 4         | 0.47%   |
| 3000x2000          | 3         | 0.35%   |
| 2880x1800          | 3         | 0.35%   |
| 2160x1440          | 3         | 0.35%   |
| 1024x768 (XGA)     | 3         | 0.35%   |
| 1920x540           | 2         | 0.23%   |
| 1400x1050          | 2         | 0.23%   |
| 5760x1080          | 1         | 0.12%   |
| 5440x1080          | 1         | 0.12%   |
| 4480x1080          | 1         | 0.12%   |
| 3840x1200          | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 3520x1080          | 1         | 0.12%   |
| 3120x2080          | 1         | 0.12%   |
| 2520x1680          | 1         | 0.12%   |
| 2240x1400          | 1         | 0.12%   |
| 1360x768           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1080x2160          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 288       | 32.73%  |
| 15      | 264       | 30%     |
| 12      | 69        | 7.84%   |
| Unknown | 33        | 3.75%   |
| 17      | 32        | 3.64%   |
| 24      | 31        | 3.52%   |
| 27      | 29        | 3.3%    |
| 14      | 29        | 3.3%    |
| 11      | 21        | 2.39%   |
| 23      | 17        | 1.93%   |
| 10      | 13        | 1.48%   |
| 21      | 8         | 0.91%   |
| 34      | 7         | 0.8%    |
| 19      | 6         | 0.68%   |
| 31      | 5         | 0.57%   |
| 18      | 4         | 0.45%   |
| 29      | 3         | 0.34%   |
| 9       | 3         | 0.34%   |
| 64      | 2         | 0.23%   |
| 22      | 2         | 0.23%   |
| 49      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 35      | 1         | 0.11%   |
| 33      | 1         | 0.11%   |
| 32      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |
| 16      | 1         | 0.11%   |
| 8       | 1         | 0.11%   |
| 5       | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 483       | 55.07%  |
| 201-300     | 205       | 23.38%  |
| 501-600     | 70        | 7.98%   |
| 351-400     | 34        | 3.88%   |
| Unknown     | 33        | 3.76%   |
| 401-500     | 18        | 2.05%   |
| 601-700     | 13        | 1.48%   |
| 701-800     | 9         | 1.03%   |
| 1001-1500   | 6         | 0.68%   |
| 801-900     | 2         | 0.23%   |
| 101-200     | 2         | 0.23%   |
| 901-1000    | 1         | 0.11%   |
| 1-100       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 636       | 79.01%  |
| 16/10   | 90        | 11.18%  |
| Unknown | 32        | 3.98%   |
| 3/2     | 17        | 2.11%   |
| 21/9    | 11        | 1.37%   |
| 4/3     | 10        | 1.24%   |
| 5/4     | 4         | 0.5%    |
| 6/5     | 1         | 0.12%   |
| 3.18    | 1         | 0.12%   |
| 11/10   | 1         | 0.12%   |
| 1.96    | 1         | 0.12%   |
| 0.46    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 267       | 30.31%  |
| 91-100         | 204       | 23.16%  |
| 61-70          | 68        | 7.72%   |
| 101-110        | 61        | 6.92%   |
| 201-250        | 51        | 5.79%   |
| 71-80          | 41        | 4.65%   |
| Unknown        | 33        | 3.75%   |
| 301-350        | 32        | 3.63%   |
| 121-130        | 30        | 3.41%   |
| 51-60          | 21        | 2.38%   |
| 351-500        | 15        | 1.7%    |
| 41-50          | 15        | 1.7%    |
| 251-300        | 9         | 1.02%   |
| 111-120        | 8         | 0.91%   |
| 151-200        | 7         | 0.79%   |
| 141-150        | 5         | 0.57%   |
| 501-1000       | 5         | 0.57%   |
| More than 1000 | 3         | 0.34%   |
| 1-40           | 3         | 0.34%   |
| 131-140        | 3         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 385       | 44.41%  |
| 101-120       | 209       | 24.11%  |
| 51-100        | 114       | 13.15%  |
| 161-240       | 92        | 10.61%  |
| Unknown       | 33        | 3.81%   |
| More than 240 | 31        | 3.58%   |
| 1-50          | 3         | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 724       | 64.18%  |
| 0     | 291       | 25.8%   |
| 2     | 103       | 9.13%   |
| 3     | 9         | 0.8%    |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 769       | 45.48%  |
| Realtek Semiconductor                  | 430       | 25.43%  |
| Qualcomm Atheros                       | 192       | 11.35%  |
| Broadcom                               | 102       | 6.03%   |
| TP-Link                                | 20        | 1.18%   |
| Marvell Technology Group               | 19        | 1.12%   |
| Ralink Technology                      | 17        | 1.01%   |
| MediaTek                               | 13        | 0.77%   |
| Edimax Technology                      | 12        | 0.71%   |
| Sierra Wireless                        | 11        | 0.65%   |
| Ralink                                 | 9         | 0.53%   |
| Ericsson Business Mobile Networks      | 9         | 0.53%   |
| Xiaomi                                 | 7         | 0.41%   |
| Samsung Electronics                    | 7         | 0.41%   |
| Hewlett-Packard                        | 7         | 0.41%   |
| Google                                 | 6         | 0.35%   |
| Dell                                   | 6         | 0.35%   |
| Nvidia                                 | 5         | 0.3%    |
| D-Link System                          | 5         | 0.3%    |
| Huawei Technologies                    | 4         | 0.24%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.18%   |
| Qualcomm Technologies                  | 3         | 0.18%   |
| Qualcomm                               | 3         | 0.18%   |
| NetGear                                | 3         | 0.18%   |
| JMicron Technology                     | 3         | 0.18%   |
| D-Link                                 | 3         | 0.18%   |
| AMD                                    | 3         | 0.18%   |
| Lenovo                                 | 2         | 0.12%   |
| Arduino SA                             | 2         | 0.12%   |
| ZyXEL Communications                   | 1         | 0.06%   |
| Van Ooijen Technische Informatica      | 1         | 0.06%   |
| ULi Electronics                        | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Shenzhen Goodix Technology             | 1         | 0.06%   |
| Sagem                                  | 1         | 0.06%   |
| Realtek                                | 1         | 0.06%   |
| OPPO Electronics                       | 1         | 0.06%   |
| OpenMoko                               | 1         | 0.06%   |
| National Semiconductor                 | 1         | 0.06%   |
| HMD Global                             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 273       | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 98        | 4.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 88        | 4.05%   |
| Intel Wireless 8265 / 8275                                              | 88        | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 3.13%   |
| Intel Wireless 8260                                                     | 54        | 2.49%   |
| Intel Wi-Fi 6 AX200                                                     | 46        | 2.12%   |
| Intel Wireless 7265                                                     | 45        | 2.07%   |
| Intel Wireless 7260                                                     | 42        | 1.93%   |
| Intel Wi-Fi 6 AX201                                                     | 41        | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 34        | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 28        | 1.29%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 27        | 1.24%   |
| Intel Ethernet Connection I219-LM                                       | 27        | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 26        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                                   | 25        | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                    | 22        | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 0.92%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 20        | 0.92%   |
| Intel Ethernet Connection I217-LM                                       | 19        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 19        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 0.83%   |
| Intel Wireless 3165                                                     | 18        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 15        | 0.69%   |
| Intel Wireless 3160                                                     | 15        | 0.69%   |
| Intel Ethernet Connection I218-LM                                       | 15        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                | 15        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 13        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 728       | 61.23%  |
| Qualcomm Atheros      | 170       | 14.3%   |
| Realtek Semiconductor | 112       | 9.42%   |
| Broadcom              | 79        | 6.64%   |
| TP-Link               | 20        | 1.68%   |
| Ralink Technology     | 17        | 1.43%   |
| MediaTek              | 12        | 1.01%   |
| Edimax Technology     | 12        | 1.01%   |
| Ralink                | 9         | 0.76%   |
| Sierra Wireless       | 8         | 0.67%   |
| D-Link System         | 5         | 0.42%   |
| Dell                  | 4         | 0.34%   |
| Qualcomm Technologies | 3         | 0.25%   |
| NetGear               | 3         | 0.25%   |
| D-Link                | 3         | 0.25%   |
| ZyXEL Communications  | 1         | 0.08%   |
| Sagem                 | 1         | 0.08%   |
| BUFFALO               | 1         | 0.08%   |
| Atheros               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 88        | 7.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 5.66%   |
| Intel Wireless 8260                                                     | 54        | 4.5%    |
| Intel Wi-Fi 6 AX200                                                     | 46        | 3.83%   |
| Intel Wireless 7265                                                     | 45        | 3.75%   |
| Intel Wireless 7260                                                     | 42        | 3.5%    |
| Intel Wi-Fi 6 AX201                                                     | 41        | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 28        | 2.33%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 27        | 2.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 26        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 26        | 2.16%   |
| Intel Centrino Ultimate-N 6300                                          | 21        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 20        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 19        | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 1.5%    |
| Intel Wireless 3165                                                     | 18        | 1.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 15        | 1.25%   |
| Intel Wireless 3160                                                     | 15        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 13        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.92%   |
| Intel WiFi Link 5100                                                    | 11        | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 11        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.92%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.83%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 10        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 387       | 42.2%   |
| Realtek Semiconductor                  | 370       | 40.35%  |
| Broadcom                               | 49        | 5.34%   |
| Qualcomm Atheros                       | 47        | 5.13%   |
| Marvell Technology Group               | 19        | 2.07%   |
| Xiaomi                                 | 7         | 0.76%   |
| Samsung Electronics                    | 7         | 0.76%   |
| Nvidia                                 | 5         | 0.55%   |
| Google                                 | 5         | 0.55%   |
| Qualcomm                               | 3         | 0.33%   |
| JMicron Technology                     | 3         | 0.33%   |
| AMD                                    | 3         | 0.33%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.22%   |
| Lenovo                                 | 2         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |
| Realtek                                | 1         | 0.11%   |
| OPPO Electronics                       | 1         | 0.11%   |
| National Semiconductor                 | 1         | 0.11%   |
| MediaTek                               | 1         | 0.11%   |
| Huawei Technologies                    | 1         | 0.11%   |
| HMD Global                             | 1         | 0.11%   |
| Aquantia                               | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 273       | 29.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 98        | 10.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 88        | 9.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 34        | 3.69%   |
| Intel Ethernet Connection I219-LM                                      | 27        | 2.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 25        | 2.71%   |
| Intel Ethernet Connection (4) I219-V                                   | 22        | 2.39%   |
| Intel Ethernet Connection I217-LM                                      | 19        | 2.06%   |
| Intel Ethernet Connection I218-LM                                      | 15        | 1.63%   |
| Intel 82577LM Gigabit Network Connection                               | 15        | 1.63%   |
| Intel Ethernet Connection I219-V                                       | 11        | 1.19%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 1.19%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 1.09%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 1.09%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 9         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 8         | 0.87%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 7         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                                  | 6         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 5         | 0.54%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 0.54%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                                 | 5         | 0.54%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 0.54%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 5         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 4         | 0.43%   |
| Intel Ethernet Connection (3) I218-V                                   | 4         | 0.43%   |
| Intel 82573L Gigabit Ethernet Controller                               | 4         | 0.43%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 4         | 0.43%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 4         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1072      | 53.31%  |
| Ethernet | 890       | 44.26%  |
| Modem    | 32        | 1.59%   |
| Unknown  | 17        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 766       | 53.87%  |
| Ethernet | 648       | 45.57%  |
| Modem    | 5         | 0.35%   |
| Unknown  | 3         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 843       | 76.99%  |
| 1     | 226       | 20.64%  |
| 3     | 15        | 1.37%   |
| 0     | 7         | 0.64%   |
| 6     | 2         | 0.18%   |
| 5     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1012      | 91.09%  |
| Yes  | 99        | 8.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 488       | 61%     |
| Broadcom                        | 64        | 8%      |
| Qualcomm Atheros Communications | 54        | 6.75%   |
| Realtek Semiconductor           | 43        | 5.38%   |
| Apple                           | 31        | 3.88%   |
| Foxconn / Hon Hai               | 24        | 3%      |
| IMC Networks                    | 21        | 2.63%   |
| Lite-On Technology              | 17        | 2.13%   |
| Dell                            | 16        | 2%      |
| Hewlett-Packard                 | 12        | 1.5%    |
| ASUSTek Computer                | 6         | 0.75%   |
| Skylight Digital                | 5         | 0.63%   |
| Cambridge Silicon Radio         | 4         | 0.5%    |
| Alps Electric                   | 4         | 0.5%    |
| USI                             | 2         | 0.25%   |
| Ralink                          | 2         | 0.25%   |
| TP-Link                         | 1         | 0.13%   |
| Toshiba                         | 1         | 0.13%   |
| Ralink Technology               | 1         | 0.13%   |
| Opticis                         | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |
| Esel International              | 1         | 0.13%   |
| Creative Technology             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 208       | 26%     |
| Intel AX201 Bluetooth                                       | 85        | 10.63%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 66        | 8.25%   |
| Intel AX200 Bluetooth                                       | 45        | 5.63%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 24        | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 22        | 2.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 22        | 2.75%   |
| Apple Bluetooth Host Controller                             | 21        | 2.63%   |
| Realtek Bluetooth Adapter                                   | 19        | 2.38%   |
| Intel AX210 Bluetooth                                       | 19        | 2.38%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 14        | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                            | 13        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 12        | 1.5%    |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 11        | 1.38%   |
| Intel AX211 Bluetooth                                       | 10        | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 9         | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 8         | 1%      |
| Dell DW375 Bluetooth Module                                 | 8         | 1%      |
| Realtek  Bluetooth 4.2 Adapter                              | 7         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 7         | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 7         | 0.88%   |
| IMC Networks Realtek Bluetooth Adapter                      | 7         | 0.88%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 5         | 0.63%   |
| Realtek Bluetooth 4.0 Adapter                               | 5         | 0.63%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                            | 5         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 5         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 5         | 0.63%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 0.63%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 4         | 0.5%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 0.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 0.5%    |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 4         | 0.5%    |
| Realtek Wireless Bluetooth Adapter                          | 3         | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 3         | 0.38%   |
| Realtek Bluetooth 4.2 Adapter                               | 3         | 0.38%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.38%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 3         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 919       | 72.02%  |
| AMD                                  | 183       | 14.34%  |
| Nvidia                               | 108       | 8.46%   |
| Lenovo                               | 13        | 1.02%   |
| Logitech                             | 6         | 0.47%   |
| Realtek Semiconductor                | 5         | 0.39%   |
| Texas Instruments                    | 4         | 0.31%   |
| Plantronics                          | 4         | 0.31%   |
| GN Netcom                            | 4         | 0.31%   |
| C-Media Electronics                  | 4         | 0.31%   |
| SteelSeries ApS                      | 3         | 0.24%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.24%   |
| ASUSTek Computer                     | 3         | 0.24%   |
| Kingston Technology                  | 2         | 0.16%   |
| JMTek                                | 2         | 0.16%   |
| Generalplus Technology               | 2         | 0.16%   |
| CMX Systems                          | 2         | 0.16%   |
| ULi Electronics                      | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.08%   |
| Sony                                 | 1         | 0.08%   |
| PS Audio                             | 1         | 0.08%   |
| Microsoft                            | 1         | 0.08%   |
| M-Audio                              | 1         | 0.08%   |
| Hewlett-Packard                      | 1         | 0.08%   |
| ESS Technology                       | 1         | 0.08%   |
| Creative Technology                  | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 163       | 10.58%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 117       | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 95        | 6.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 86        | 5.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 65        | 4.22%   |
| Intel Broadwell-U Audio Controller                                                                | 58        | 3.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 55        | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 3.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 46        | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 42        | 2.73%   |
| Intel 8 Series HD Audio Controller                                                                | 42        | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 39        | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 39        | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 2.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 2.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 2.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 31        | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 1.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 19        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 1.04%   |
| AMD FCH Azalia Controller                                                                         | 14        | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 0.78%   |
| Unknown                                                                                           | 12        | 0.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 11        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.58%   |
| Lenovo Realtek USB Audio                                                                          | 8         | 0.52%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.45%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 377       | 28.96%  |
| SK hynix              | 290       | 22.27%  |
| Micron Technology     | 143       | 10.98%  |
| Kingston              | 111       | 8.53%   |
| Unknown               | 85        | 6.53%   |
| Crucial               | 65        | 4.99%   |
| Unknown               | 35        | 2.69%   |
| Ramaxel Technology    | 33        | 2.53%   |
| Elpida                | 20        | 1.54%   |
| Corsair               | 18        | 1.38%   |
| Nanya Technology      | 15        | 1.15%   |
| A-DATA Technology     | 15        | 1.15%   |
| Team                  | 11        | 0.84%   |
| Transcend             | 10        | 0.77%   |
| G.Skill               | 8         | 0.61%   |
| Smart                 | 7         | 0.54%   |
| Unknown (ABCD)        | 5         | 0.38%   |
| Neo Forza             | 5         | 0.38%   |
| Avant                 | 5         | 0.38%   |
| PNY                   | 4         | 0.31%   |
| GOODRAM               | 4         | 0.31%   |
| Goldkey               | 4         | 0.31%   |
| 48spaces              | 4         | 0.31%   |
| Super Talent          | 2         | 0.15%   |
| PUSKILL               | 2         | 0.15%   |
| Patriot               | 2         | 0.15%   |
| Magnum Tech           | 2         | 0.15%   |
| KomputerBay           | 2         | 0.15%   |
| V-GeN                 | 1         | 0.08%   |
| V-Color               | 1         | 0.08%   |
| Teikon                | 1         | 0.08%   |
| Rayson                | 1         | 0.08%   |
| Qimonda               | 1         | 0.08%   |
| Kllisre               | 1         | 0.08%   |
| KingTiger             | 1         | 0.08%   |
| Kingmax Semiconductor | 1         | 0.08%   |
| Golden Empire         | 1         | 0.08%   |
| Gold Key              | 1         | 0.08%   |
| CSX                   | 1         | 0.08%   |
| ASint Technology      | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 35        | 2.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 22        | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 20        | 1.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 18        | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 18        | 1.28%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 18        | 1.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 17        | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 16        | 1.14%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 14        | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 13        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 12        | 0.86%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 12        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 11        | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 10        | 0.71%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 10        | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 10        | 0.71%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 10        | 0.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 10        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 10        | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 8         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 8         | 0.57%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 8         | 0.57%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 8         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 7         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 7         | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 7         | 0.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 7         | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s       | 7         | 0.5%    |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s         | 7         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 7         | 0.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 7         | 0.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 7         | 0.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 7         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 7         | 0.5%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 7         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR                           | 6         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 6         | 0.43%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 6         | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s     | 6         | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 6         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 448       | 40.65%  |
| DDR3    | 427       | 38.75%  |
| DDR2    | 75        | 6.81%   |
| LPDDR3  | 47        | 4.26%   |
| LPDDR4  | 37        | 3.36%   |
| DDR     | 19        | 1.72%   |
| DDR5    | 14        | 1.27%   |
| LPDDR5  | 12        | 1.09%   |
| SDRAM   | 11        | 1%      |
| Unknown | 8         | 0.73%   |
| DRAM    | 2         | 0.18%   |
| SRAM    | 1         | 0.09%   |
| RAM     | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 974       | 87.67%  |
| Row Of Chips | 89        | 8.01%   |
| Chip         | 30        | 2.7%    |
| Unknown      | 11        | 0.99%   |
| DIMM         | 7         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 427       | 35.2%   |
| 4096  | 353       | 29.1%   |
| 2048  | 170       | 14.01%  |
| 16384 | 164       | 13.52%  |
| 1024  | 48        | 3.96%   |
| 32768 | 35        | 2.89%   |
| 512   | 11        | 0.91%   |
| 256   | 4         | 0.33%   |
| 2560  | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 273       | 23.1%   |
| 2667    | 172       | 14.55%  |
| 3200    | 153       | 12.94%  |
| 2400    | 118       | 9.98%   |
| 1333    | 79        | 6.68%   |
| 2133    | 78        | 6.6%    |
| 1334    | 53        | 4.48%   |
| 1867    | 38        | 3.21%   |
| 667     | 36        | 3.05%   |
| Unknown | 34        | 2.88%   |
| 800     | 25        | 2.12%   |
| 4267    | 23        | 1.95%   |
| 1067    | 19        | 1.61%   |
| 533     | 16        | 1.35%   |
| 4800    | 12        | 1.02%   |
| 6400    | 10        | 0.85%   |
| 1066    | 8         | 0.68%   |
| 4266    | 7         | 0.59%   |
| 975     | 6         | 0.51%   |
| 2048    | 3         | 0.25%   |
| 1866    | 3         | 0.25%   |
| 5600    | 2         | 0.17%   |
| 3733    | 2         | 0.17%   |
| 2933    | 2         | 0.17%   |
| 2666    | 1         | 0.08%   |
| 1639    | 1         | 0.08%   |
| 1596    | 1         | 0.08%   |
| 1200    | 1         | 0.08%   |
| 666     | 1         | 0.08%   |
| 333     | 1         | 0.08%   |
| 266     | 1         | 0.08%   |
| 200     | 1         | 0.08%   |
| 166     | 1         | 0.08%   |
| 100     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Prolific Technology | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 50%     |
| Samsung ML-1610 Mono Laser Printer | 1         | 25%     |
| Prolific PL2305 Parallel Port      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 262       | 30.72%  |
| IMC Networks                           | 99        | 11.61%  |
| Bison Electronics                      | 83        | 9.73%   |
| Microdia                               | 82        | 9.61%   |
| Realtek Semiconductor                  | 73        | 8.56%   |
| Sunplus Innovation Technology          | 55        | 6.45%   |
| Lite-On Technology                     | 28        | 3.28%   |
| Suyin                                  | 23        | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 19        | 2.23%   |
| Syntek                                 | 17        | 1.99%   |
| Quanta                                 | 15        | 1.76%   |
| Apple                                  | 13        | 1.52%   |
| Luxvisions Innotech Limited            | 12        | 1.41%   |
| Silicon Motion                         | 10        | 1.17%   |
| Lenovo                                 | 8         | 0.94%   |
| Shenzhen Kingcome Optoelectronic       | 7         | 0.82%   |
| Logitech                               | 6         | 0.7%    |
| ALi                                    | 5         | 0.59%   |
| Z-Star Microelectronics                | 4         | 0.47%   |
| Ricoh                                  | 4         | 0.47%   |
| Importek                               | 4         | 0.47%   |
| Alcor Micro                            | 4         | 0.47%   |
| Supreme Electronics                    | 3         | 0.35%   |
| Primax Electronics                     | 2         | 0.23%   |
| Pixart Imaging                         | 2         | 0.23%   |
| OmniVision Technologies                | 2         | 0.23%   |
| Jiangxi Shinetech Optical              | 2         | 0.23%   |
| Intel                                  | 2         | 0.23%   |
| USB Camera                             | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Qtech                                  | 1         | 0.12%   |
| Goodong Industry                       | 1         | 0.12%   |
| Genesys Logic                          | 1         | 0.12%   |
| DigiTech                               | 1         | 0.12%   |
| Cubeternet                             | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 86        | 9.95%   |
| Bison Integrated Camera                       | 45        | 5.21%   |
| IMC Networks Integrated Camera                | 36        | 4.17%   |
| Microdia Integrated_Webcam_HD                 | 26        | 3.01%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 20        | 2.31%   |
| Chicony HD WebCam                             | 20        | 2.31%   |
| Realtek Integrated_Webcam_HD                  | 19        | 2.2%    |
| Microdia Integrated Webcam                    | 19        | 2.2%    |
| Chicony Integrated Camera (1280x720@30)       | 18        | 2.08%   |
| Sunplus Integrated_Webcam_HD                  | 17        | 1.97%   |
| Lite-On Integrated Camera                     | 16        | 1.85%   |
| Realtek USB 2.0 PC Camera                     | 13        | 1.5%    |
| IMC Networks Realtek PC Camera                | 11        | 1.27%   |
| Bison SunplusIT Integrated Camera             | 11        | 1.27%   |
| IMC Networks EasyCamera                       | 10        | 1.16%   |
| Syntek Integrated Camera                      | 9         | 1.04%   |
| Chicony Integrated IR Camera                  | 9         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 8         | 0.93%   |
| Chicony Chicony USB2.0 Camera                 | 8         | 0.93%   |
| Bison Lenovo EasyCamera                       | 8         | 0.93%   |
| Microdia Integrated Webcam HD                 | 7         | 0.81%   |
| Chicony ThinkPad T490 Webcam                  | 7         | 0.81%   |
| Chicony Integrated Camera [ThinkPad]          | 7         | 0.81%   |
| Apple FaceTime HD Camera                      | 7         | 0.81%   |
| Realtek Integrated Webcam                     | 6         | 0.69%   |
| Quanta HD Webcam                              | 6         | 0.69%   |
| Luxvisions Innotech Limited Integrated Camera | 6         | 0.69%   |
| Lenovo Integrated Webcam [R5U877]             | 6         | 0.69%   |
| IMC Networks Integrated Webcam                | 6         | 0.69%   |
| Chicony Realtek DMFT RGB                      | 6         | 0.69%   |
| Chicony Integrated HP HD Webcam               | 6         | 0.69%   |
| Chicony EasyCamera                            | 6         | 0.69%   |
| Syntek EasyCamera                             | 5         | 0.58%   |
| Sunplus Laptop Integrated WebCam HD           | 5         | 0.58%   |
| Sunplus HD WebCam                             | 5         | 0.58%   |
| IMC Networks UVC VGA Webcam                   | 5         | 0.58%   |
| Chicony USB 2.0 Camera                        | 5         | 0.58%   |
| Bison ThinkPad Integrated Camera              | 5         | 0.58%   |
| Apple FaceTime HD Camera (Built-in)           | 5         | 0.58%   |
| Realtek HD WebCam                             | 4         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 81        | 31.03%  |
| Synaptics                  | 67        | 25.67%  |
| Shenzhen Goodix Technology | 36        | 13.79%  |
| Upek                       | 22        | 8.43%   |
| AuthenTec                  | 12        | 4.6%    |
| Elan Microelectronics      | 11        | 4.21%   |
| STMicroelectronics         | 10        | 3.83%   |
| LighTuning Technology      | 8         | 3.07%   |
| Broadcom                   | 8         | 3.07%   |
| FocalTech Systems          | 5         | 1.92%   |
| Samsung Electronics        | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 31        | 11.88%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 25        | 9.58%   |
| Shenzhen Goodix Fingerprint Reader                                           | 25        | 9.58%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 24        | 9.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 22        | 8.43%   |
| Validity Sensors Synaptics WBDI                                              | 18        | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 11        | 4.21%   |
| Elan Fingerprint Sensor                                                      | 11        | 4.21%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 3.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 8         | 3.07%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.07%   |
| Shenzhen Goodix  Fingerprint Device                                          | 7         | 2.68%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.3%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 5         | 1.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 4         | 1.53%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 4         | 1.53%   |
| FocalTech Systems Fingerprint Reader                                         | 4         | 1.53%   |
| AuthenTec AES2810                                                            | 4         | 1.53%   |
| AuthenTec AES1660                                                            | 4         | 1.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 1.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.15%   |
| Validity Sensors VFS491                                                      | 2         | 0.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 0.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                            | 1         | 0.38%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.38%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.38%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.38%   |
| Synaptics UWP WBDI                                                           | 1         | 0.38%   |
| Synaptics TouchPad                                                           | 1         | 0.38%   |
| Synaptics Fingerprint reader [HP G6]                                         | 1         | 0.38%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.38%   |
| FocalTech Systems FocalTech Fingerprint Device                               | 1         | 0.38%   |
| AuthenTec AES2660                                                            | 1         | 0.38%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 348       | 30.34%  |
| 1     | 325       | 28.33%  |
| 3     | 241       | 21.01%  |
| 0     | 105       | 9.15%   |
| 4     | 96        | 8.37%   |
| 5     | 22        | 1.92%   |
| 6     | 8         | 0.7%    |
| 9     | 1         | 0.09%   |
| 7     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 782       | 38.66%  |
| Bluetooth                | 362       | 17.89%  |
| Fingerprint reader       | 253       | 12.51%  |
| Card reader              | 231       | 11.42%  |
| Net/wireless             | 220       | 10.87%  |
| Firewire controller      | 97        | 4.79%   |
| Storage                  | 23        | 1.14%   |
| Sound                    | 16        | 0.79%   |
| Modem                    | 14        | 0.69%   |
| Network                  | 13        | 0.64%   |
| Net/ethernet             | 10        | 0.49%   |
| Storage/nvme             | 1         | 0.05%   |
| Graphics card            | 1         | 0.05%   |

