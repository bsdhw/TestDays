BSD in Italy - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 113

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Chuwi         | GemiBook Pro                | [2656d00123](https://bsd-hardware.info/?probe=2656d00123) | May 03, 2024 |
| Apple         | MacBookAir3,1               | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| ASUSTek       | K52F                        | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| ASUSTek       | K52F                        | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| ASUSTek       | X555LAB                     | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| HP            | Mini 210-1000               | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Samsung       | R510/P510                   | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| TULPAR        | A5 V20.3                    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Unknown       | Unknown                     | [426e43d7f2](https://bsd-hardware.info/?probe=426e43d7f2) | Dec 08, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| Samsung       | N150P/N210P/N220P           | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Dell          | Latitude D830               | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Acer          | TravelMate 5730             | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| ASUSTek       | N751JK                      | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| ASUSTek       | N751JK                      | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| ASUSTek       | N751JK                      | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | N751JK                      | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| ASUSTek       | 1015P                       | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| Dell          | XPS 13 9343                 | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Acer          | Aspire 5250                 | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Intel         | S1200RP_SE                  | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| HP            | Mini 210-1000               | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Unknown       | Unknown                     | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Acer          | AOD260                      | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Deciso        | OPNsense Appliance          | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| TUXEDO        | N14xWU                      | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Acer          | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| ASUSTek       | 1000                        | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Toshiba       | Satellite C855-1U4          | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| ASUSTek       | X555LJ                      | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| HP            | Laptop 15-da0xxx            | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| HP            | Laptop 15-da0xxx            | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Acer          | Extensa 5635Z               | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Dell          | Precision 3510              | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 13        | 14.77%  |
| helloSystem 0.8.1    | 11        | 12.5%   |
| helloSystem 0.5.0    | 5         | 5.68%   |
| helloSystem 0.4.0    | 5         | 5.68%   |
| helloSystem 0.8.0    | 4         | 4.55%   |
| helloSystem 0.6.0    | 3         | 3.41%   |
| NomadBSD 1.3.2       | 2         | 2.27%   |
| helloSystem 0.9.0    | 2         | 2.27%   |
| helloSystem 0.3.0    | 2         | 2.27%   |
| GhostBSD 21.08.27    | 2         | 2.27%   |
| GhostBSD 20.04.02    | 2         | 2.27%   |
| FreeBSD 13.1         | 2         | 2.27%   |
| OPNsense 23.7.9      | 1         | 1.14%   |
| OPNsense 22.1.9      | 1         | 1.14%   |
| OPNsense 22.1.6      | 1         | 1.14%   |
| OPNsense 21.7.7      | 1         | 1.14%   |
| OPNsense 21.1        | 1         | 1.14%   |
| OpenBSD 7.2          | 1         | 1.14%   |
| OpenBSD 7.1          | 1         | 1.14%   |
| OpenBSD 6.8          | 1         | 1.14%   |
| OpenBSD 6.7          | 1         | 1.14%   |
| NomadBSD 5806f915    | 1         | 1.14%   |
| NomadBSD 1.4         | 1         | 1.14%   |
| NomadBSD 1.3.1       | 1         | 1.14%   |
| NetBSD 9.2_STABLE    | 1         | 1.14%   |
| NetBSD 9.2           | 1         | 1.14%   |
| NetBSD 9.1           | 1         | 1.14%   |
| NetBSD 9.0           | 1         | 1.14%   |
| NetBSD 10.99.1       | 1         | 1.14%   |
| GhostBSD 23.10.1     | 1         | 1.14%   |
| GhostBSD 23.09.16    | 1         | 1.14%   |
| GhostBSD 23.06.05    | 1         | 1.14%   |
| GhostBSD 22.11.02    | 1         | 1.14%   |
| GhostBSD 22.06.26    | 1         | 1.14%   |
| FreeBSD 14.0-p4      | 1         | 1.14%   |
| FreeBSD 14.0-CURRENT | 1         | 1.14%   |
| FreeBSD 14.0         | 1         | 1.14%   |
| FreeBSD 13.2-p5      | 1         | 1.14%   |
| FreeBSD 13.2-p3      | 1         | 1.14%   |
| FreeBSD 13.2-p2      | 1         | 1.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 40        | 50.63%  |
| FreeBSD     | 14        | 17.72%  |
| GhostBSD    | 7         | 8.86%   |
| OPNsense    | 5         | 6.33%   |
| NomadBSD    | 5         | 6.33%   |
| OpenBSD     | 4         | 5.06%   |
| NetBSD      | 4         | 5.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 76        | 97.44%  |
| i386  | 2         | 2.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 40        | 50%     |
| Console      | 7         | 8.75%   |
| KDE5         | 6         | 7.5%    |
| XFCE         | 5         | 6.25%   |
| Openbox      | 5         | 6.25%   |
| MATE         | 3         | 3.75%   |
| i3           | 3         | 3.75%   |
| CTWM         | 3         | 3.75%   |
| Cinnamon     | 3         | 3.75%   |
| fvwm         | 2         | 2.5%    |
| TWM          | 1         | 1.25%   |
| LXQt         | 1         | 1.25%   |
| Fluxbox      | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 72        | 92.31%  |
| Console | 5         | 6.41%   |
| Wayland | 1         | 1.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 47        | 59.49%  |
| Console | 17        | 21.52%  |
| LightDM | 7         | 8.86%   |
| SDDM    | 6         | 7.59%   |
| XDM     | 1         | 1.27%   |
| GDM     | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 39        | 47.56%  |
| it_IT            | 18        | 21.95%  |
| Unknown          | 11        | 13.41%  |
| C                | 6         | 7.32%   |
| it               | 2         | 2.44%   |
| ru_RU            | 1         | 1.22%   |
| it_IT.ISO8859-15 | 1         | 1.22%   |
| it_IT.ISO8859-1  | 1         | 1.22%   |
| fr_FR            | 1         | 1.22%   |
| en_GB            | 1         | 1.22%   |
| en               | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 66        | 84.62%  |
| BIOS | 12        | 15.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 40        | 50.63%  |
| Ufs    | 19        | 24.05%  |
| Cd9660 | 16        | 20.25%  |
| Ffs    | 4         | 5.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 70        | 89.74%  |
| MBR     | 6         | 7.69%   |
| Unknown | 2         | 2.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 25.64%  |
| ASUSTek Computer    | 14        | 17.95%  |
| Dell                | 7         | 8.97%   |
| Acer                | 7         | 8.97%   |
| Hewlett-Packard     | 6         | 7.69%   |
| Apple               | 4         | 5.13%   |
| Toshiba             | 3         | 3.85%   |
| Samsung Electronics | 3         | 3.85%   |
| Unknown             | 3         | 3.85%   |
| eMachines           | 2         | 2.56%   |
| TUXEDO              | 1         | 1.28%   |
| TULPAR              | 1         | 1.28%   |
| Packard Bell        | 1         | 1.28%   |
| MSI                 | 1         | 1.28%   |
| LG Electronics      | 1         | 1.28%   |
| Intel               | 1         | 1.28%   |
| IBM                 | 1         | 1.28%   |
| Deciso              | 1         | 1.28%   |
| Chuwi               | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 4         | 5.13%   |
| HP Laptop 15-da0xxx                          | 2         | 2.56%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA       | 2         | 2.56%   |
| Apple MacBook4,1                             | 2         | 2.56%   |
| TUXEDO N14xWU                                | 1         | 1.28%   |
| TULPAR A5 V20.3                              | 1         | 1.28%   |
| Toshiba Satellite C855-1U4                   | 1         | 1.28%   |
| Toshiba PORTEGE M780                         | 1         | 1.28%   |
| Samsung R510/P510                            | 1         | 1.28%   |
| Samsung N150P/N210P/N220P                    | 1         | 1.28%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV     | 1         | 1.28%   |
| Packard Bell EasyNote_MX61-B-038             | 1         | 1.28%   |
| MSI GF65 Thin 10SER                          | 1         | 1.28%   |
| LG COLUMBIA                                  | 1         | 1.28%   |
| Lenovo ThinkPad X280 20KES5M300              | 1         | 1.28%   |
| Lenovo ThinkPad X260 20F5S82N00              | 1         | 1.28%   |
| Lenovo ThinkPad X250 20CMS0FA00              | 1         | 1.28%   |
| Lenovo ThinkPad X240 20AMS0J01N              | 1         | 1.28%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00     | 1         | 1.28%   |
| Lenovo ThinkPad W530 2447GW3                 | 1         | 1.28%   |
| Lenovo ThinkPad T495 20NJS0KP00              | 1         | 1.28%   |
| Lenovo ThinkPad T460s 20FAS3L002             | 1         | 1.28%   |
| Lenovo ThinkPad T450 20BUS06B00              | 1         | 1.28%   |
| Lenovo ThinkPad T440p                        | 1         | 1.28%   |
| Lenovo ThinkPad T440 20B7S1C600              | 1         | 1.28%   |
| Lenovo ThinkPad T430 23501B3                 | 1         | 1.28%   |
| Lenovo ThinkPad T420 4236BD5                 | 1         | 1.28%   |
| Lenovo ThinkPad T410 2537B94                 | 1         | 1.28%   |
| Lenovo ThinkPad L530 24812TG                 | 1         | 1.28%   |
| Lenovo IdeaPad 3 15ADA05 81W1                | 1         | 1.28%   |
| Lenovo G505 20240                            | 1         | 1.28%   |
| Lenovo G50-45 80E3                           | 1         | 1.28%   |
| Lenovo B590 62743PG                          | 1         | 1.28%   |
| Intel S1200RP_SE                             | 1         | 1.28%   |
| IBM ThinkPad R51 2887AVG                     | 1         | 1.28%   |
| HP ProBook 470 G4                            | 1         | 1.28%   |
| HP Pavilion 15                               | 1         | 1.28%   |
| HP Mini 210-1000                             | 1         | 1.28%   |
| HP EliteBook 6930p                           | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 16        | 20.51%  |
| Unknown               | 4         | 5.13%   |
| Dell Latitude         | 3         | 3.85%   |
| ASUS VivoBook         | 3         | 3.85%   |
| Acer Aspire           | 3         | 3.85%   |
| HP Laptop             | 2         | 2.56%   |
| Apple MacBook4        | 2         | 2.56%   |
| TUXEDO N14xWU         | 1         | 1.28%   |
| TULPAR A5             | 1         | 1.28%   |
| Toshiba Satellite     | 1         | 1.28%   |
| Toshiba PORTEGE       | 1         | 1.28%   |
| Samsung R510          | 1         | 1.28%   |
| Samsung N150P         | 1         | 1.28%   |
| Samsung 3570R         | 1         | 1.28%   |
| Packard Bell EasyNote | 1         | 1.28%   |
| MSI GF65              | 1         | 1.28%   |
| LG COLUMBIA           | 1         | 1.28%   |
| Lenovo IdeaPad        | 1         | 1.28%   |
| Lenovo G505           | 1         | 1.28%   |
| Lenovo G50-45         | 1         | 1.28%   |
| Lenovo B590           | 1         | 1.28%   |
| Intel S1200RP         | 1         | 1.28%   |
| IBM ThinkPad          | 1         | 1.28%   |
| HP ProBook            | 1         | 1.28%   |
| HP Pavilion           | 1         | 1.28%   |
| HP Mini               | 1         | 1.28%   |
| HP EliteBook          | 1         | 1.28%   |
| eMachines eME732ZG    | 1         | 1.28%   |
| eMachines eME728      | 1         | 1.28%   |
| Dell XPS              | 1         | 1.28%   |
| Dell Vostro           | 1         | 1.28%   |
| Dell Precision        | 1         | 1.28%   |
| Dell Inspiron         | 1         | 1.28%   |
| Deciso OPNsense       | 1         | 1.28%   |
| Chuwi GemiBook        | 1         | 1.28%   |
| ASUS X555LJ           | 1         | 1.28%   |
| ASUS X555LD           | 1         | 1.28%   |
| ASUS X555LAB          | 1         | 1.28%   |
| ASUS X553MA           | 1         | 1.28%   |
| ASUS X502CA           | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 10        | 12.82%  |
| 2019 | 9         | 11.54%  |
| 2010 | 9         | 11.54%  |
| 2016 | 6         | 7.69%   |
| 2011 | 6         | 7.69%   |
| 2014 | 5         | 6.41%   |
| 2008 | 5         | 6.41%   |
| 2020 | 4         | 5.13%   |
| 2018 | 4         | 5.13%   |
| 2015 | 4         | 5.13%   |
| 2022 | 3         | 3.85%   |
| 2021 | 3         | 3.85%   |
| 2012 | 3         | 3.85%   |
| 2023 | 2         | 2.56%   |
| 2009 | 2         | 2.56%   |
| 2007 | 2         | 2.56%   |
| 2005 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 98.72%  |
| Yes  | 1         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 33        | 41.77%  |
| 4.01-8.0   | 24        | 30.38%  |
| 16.01-24.0 | 8         | 10.13%  |
| 2.01-3.0   | 7         | 8.86%   |
| 32.01-64.0 | 3         | 3.8%    |
| 3.01-4.0   | 2         | 2.53%   |
| 24.01-32.0 | 1         | 1.27%   |
| 0.01-0.5   | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 51        | 64.56%  |
| 0.51-1.0  | 13        | 16.46%  |
| 2.01-3.0  | 4         | 5.06%   |
| 1.01-2.0  | 4         | 5.06%   |
| Unknown   | 4         | 5.06%   |
| 4.01-8.0  | 2         | 2.53%   |
| 8.01-16.0 | 1         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 73.42%  |
| 2      | 17        | 21.52%  |
| 0      | 4         | 5.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 61.25%  |
| Yes       | 31        | 38.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 88.46%  |
| No        | 9         | 11.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 92.31%  |
| No        | 6         | 7.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 63.29%  |
| No        | 29        | 36.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 78        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Rome                     | 14        | 15.56%  |
| Milan                    | 12        | 13.33%  |
| Bologna                  | 4         | 4.44%   |
| Turin                    | 3         | 3.33%   |
| Brescia                  | 3         | 3.33%   |
| Trieste                  | 2         | 2.22%   |
| Sesto San Giovanni       | 2         | 2.22%   |
| Rho                      | 2         | 2.22%   |
| Padova                   | 2         | 2.22%   |
| Monterotondo             | 2         | 2.22%   |
| Vigonza                  | 1         | 1.11%   |
| Vigonovo                 | 1         | 1.11%   |
| Udine                    | 1         | 1.11%   |
| Solarino                 | 1         | 1.11%   |
| Saronno                  | 1         | 1.11%   |
| Roncade                  | 1         | 1.11%   |
| Resana                   | 1         | 1.11%   |
| Prad am Stilfser Joch    | 1         | 1.11%   |
| Piovene Rocchette        | 1         | 1.11%   |
| Pessano Con Bornago      | 1         | 1.11%   |
| Passignano sul Trasimeno | 1         | 1.11%   |
| Nughedu San Nicolo       | 1         | 1.11%   |
| Naturns                  | 1         | 1.11%   |
| Naples                   | 1         | 1.11%   |
| Milano                   | 1         | 1.11%   |
| Massa Lombarda           | 1         | 1.11%   |
| Malnate                  | 1         | 1.11%   |
| Macerata                 | 1         | 1.11%   |
| Lurago Marinone          | 1         | 1.11%   |
| Lissone                  | 1         | 1.11%   |
| Iglesias                 | 1         | 1.11%   |
| Genzano di Roma          | 1         | 1.11%   |
| Gattinara                | 1         | 1.11%   |
| Galliera Veneta          | 1         | 1.11%   |
| Gallarate                | 1         | 1.11%   |
| Fiumicino                | 1         | 1.11%   |
| Fiorano Modenese         | 1         | 1.11%   |
| Farneto                  | 1         | 1.11%   |
| Cornaiano                | 1         | 1.11%   |
| Concesio                 | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 23     | 17.05%  |
| Seagate             | 9         | 12     | 10.23%  |
| WDC                 | 8         | 11     | 9.09%   |
| Kingston            | 8         | 10     | 9.09%   |
| Crucial             | 7         | 11     | 7.95%   |
| Toshiba             | 6         | 6      | 6.82%   |
| SanDisk             | 4         | 4      | 4.55%   |
| Intel               | 4         | 4      | 4.55%   |
| Hitachi             | 4         | 5      | 4.55%   |
| Transcend           | 2         | 2      | 2.27%   |
| Micron Technology   | 2         | 2      | 2.27%   |
| Leven               | 2         | 2      | 2.27%   |
| KingSpec            | 2         | 2      | 2.27%   |
| HGST                | 2         | 2      | 2.27%   |
| FORESEE             | 2         | 3      | 2.27%   |
| Apple               | 2         | 2      | 2.27%   |
| Union Memory        | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| PNY                 | 1         | 1      | 1.14%   |
| Netac               | 1         | 1      | 1.14%   |
| KingDian            | 1         | 1      | 1.14%   |
| Intenso             | 1         | 1      | 1.14%   |
| Indilinx            | 1         | 1      | 1.14%   |
| Fujitsu             | 1         | 1      | 1.14%   |
| ASUSTek Computer    | 1         | 2      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                       | 3         | 3.26%   |
| Samsung SSD 860 EVO 250GB                       | 3         | 3.26%   |
| Kingston SA400S37240G 240GB                     | 3         | 3.26%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 2.17%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 2.17%   |
| KingSpec Q-720 720GB                            | 2         | 2.17%   |
| Intel SSDSC2BF180A4L 180GB                      | 2         | 2.17%   |
| WDC WDS500G2B0A-00SM50 500GB                    | 1         | 1.09%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 1.09%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 1.09%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 1.09%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 1.09%   |
| WDC WD2500BEVT-22ZCT0 250GB                     | 1         | 1.09%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 1.09%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 1.09%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 1.09%   |
| Transcend TS120GMTS420S 120GB                   | 1         | 1.09%   |
| Toshiba TR200 240GB                             | 1         | 1.09%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.09%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.09%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1.09%   |
| Toshiba MK5065GSX 500GB                         | 1         | 1.09%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 1.09%   |
| SPCC Solid State Disk 256GB                     | 1         | 1.09%   |
| Seagate ST9750420AS 752GB                       | 1         | 1.09%   |
| Seagate ST9320320AS 320GB                       | 1         | 1.09%   |
| Seagate ST9160821AS 160GB                       | 1         | 1.09%   |
| Seagate ST9160411AS 160GB                       | 1         | 1.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1.09%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.09%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 1.09%   |
| Seagate ST250LM000 HM251HI 250GB                | 1         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 1.09%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 1         | 1.09%   |
| SanDisk X400 M.2 2280 512GB                     | 1         | 1.09%   |
| SanDisk SSD P4 8GB                              | 1         | 1.09%   |
| SanDisk SDSSDP064G 64GB                         | 1         | 1.09%   |
| SanDisk SD9SN8W-128G-1006 128GB                 | 1         | 1.09%   |
| Samsung SSD 970 EVO 250GB                       | 1         | 1.09%   |
| Samsung SSD 870 EVO 500GB                       | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 12     | 34.62%  |
| Toshiba             | 5         | 5      | 19.23%  |
| WDC                 | 4         | 5      | 15.38%  |
| Hitachi             | 4         | 5      | 15.38%  |
| HGST                | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 18     | 21.15%  |
| Crucial             | 7         | 11     | 13.46%  |
| Kingston            | 5         | 6      | 9.62%   |
| WDC                 | 4         | 6      | 7.69%   |
| SanDisk             | 4         | 4      | 7.69%   |
| Intel               | 3         | 3      | 5.77%   |
| Leven               | 2         | 2      | 3.85%   |
| KingSpec            | 2         | 2      | 3.85%   |
| FORESEE             | 2         | 3      | 3.85%   |
| Apple               | 2         | 2      | 3.85%   |
| Transcend           | 1         | 1      | 1.92%   |
| Toshiba             | 1         | 1      | 1.92%   |
| SPCC                | 1         | 1      | 1.92%   |
| PNY                 | 1         | 1      | 1.92%   |
| Netac               | 1         | 1      | 1.92%   |
| Micron Technology   | 1         | 1      | 1.92%   |
| KingDian            | 1         | 1      | 1.92%   |
| Intenso             | 1         | 1      | 1.92%   |
| Indilinx            | 1         | 1      | 1.92%   |
| ASUSTek Computer    | 1         | 2      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 47        | 68     | 56.63%  |
| HDD  | 25        | 31     | 30.12%  |
| NVMe | 11        | 12     | 13.25%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 99     | 85.71%  |
| NVMe | 11        | 12     | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 79     | 84.06%  |
| 0.51-1.0   | 11        | 20     | 15.94%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 37        | 46.25%  |
| 101-250    | 19        | 23.75%  |
| 251-500    | 9         | 11.25%  |
| 21-50      | 7         | 8.75%   |
| 51-100     | 5         | 6.25%   |
| 501-1000   | 3         | 3.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 72        | 88.89%  |
| 21-50   | 8         | 9.88%   |
| 51-100  | 1         | 1.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2BF180A4L 180GB            | 2         | 2      | 11.76%  |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 5.88%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 5.88%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 5.88%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 5.88%   |
| SanDisk SDSSDP064G 64GB               | 1         | 1      | 5.88%   |
| SanDisk SD9SN8W-128G-1006 128GB       | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 5.88%   |
| Netac SSD 256GB                       | 1         | 1      | 5.88%   |
| Hitachi HTS548040M9AT00 37GB          | 1         | 2      | 5.88%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 5.88%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 3      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 23.53%  |
| Toshiba             | 2         | 2      | 11.76%  |
| SanDisk             | 2         | 2      | 11.76%  |
| Intel               | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 3      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Netac               | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |
| Crucial             | 1         | 3      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| Toshiba | 2         | 2      | 20%     |
| Hitachi | 2         | 3      | 20%     |
| WDC     | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 58.82%  |
| SSD  | 7         | 9      | 41.18%  |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 58        | 88     | 75.32%  |
| Malfunc  | 17        | 20     | 22.08%  |
| Detected | 2         | 3      | 2.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 60        | 71.43%  |
| AMD                              | 9         | 10.71%  |
| Samsung Electronics              | 4         | 4.76%   |
| Kingston Technology Company      | 3         | 3.57%   |
| Micron Technology                | 2         | 2.38%   |
| Union Memory (Shenzhen)          | 1         | 1.19%   |
| Transcend                        | 1         | 1.19%   |
| Silicon Integrated Systems [SiS] | 1         | 1.19%   |
| SanDisk                          | 1         | 1.19%   |
| Nvidia                           | 1         | 1.19%   |
| JMicron Technology               | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 8.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 7         | 7.37%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 7.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 6.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 5.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 5.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 5.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 5.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 4         | 4.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 3.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 3.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 3.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 2         | 2.11%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                                  | 1         | 1.05%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)            | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 1.05%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 1.05%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                  | 1         | 1.05%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 1         | 1.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 1         | 1.05%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 1.05%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                       | 1         | 1.05%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 1         | 1.05%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 1         | 1.05%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                                     | 1         | 1.05%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                         | 1         | 1.05%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 1.05%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 1         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 1.05%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 1.05%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 1.05%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.05%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 64        | 71.11%  |
| NVMe | 12        | 13.33%  |
| IDE  | 12        | 13.33%  |
| RAID | 2         | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 85.9%   |
| AMD    | 11        | 14.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 5.06%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 3.8%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 3.8%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 3.8%    |
| Intel CPU Version                             | 2         | 2.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 2.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.53%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.53%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 1.27%   |
| Intel Pentium M processor                     | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.27%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.27%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 1.27%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 1.27%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.27%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.27%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.27%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.27%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.27%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.27%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.27%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.27%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.27%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.27%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.27%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.27%   |
| Intel Core 2 Duo CPU U9400 @ 1.40GHz          | 1         | 1.27%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 25.32%  |
| Intel Core i7           | 12        | 15.19%  |
| Intel Core 2 Duo        | 7         | 8.86%   |
| Other                   | 5         | 6.33%   |
| Intel Core i3           | 5         | 6.33%   |
| Intel Celeron           | 5         | 6.33%   |
| Intel Atom              | 5         | 6.33%   |
| Intel Pentium           | 4         | 5.06%   |
| AMD Ryzen 5             | 3         | 3.8%    |
| Intel Pentium Dual-Core | 2         | 2.53%   |
| Intel Xeon              | 1         | 1.27%   |
| Intel Pentium M         | 1         | 1.27%   |
| Intel Core 2            | 1         | 1.27%   |
| Intel 686-class         | 1         | 1.27%   |
| AMD Turion 64 X2 Mobile | 1         | 1.27%   |
| AMD Ryzen Embedded      | 1         | 1.27%   |
| AMD Ryzen 7 PRO         | 1         | 1.27%   |
| AMD E1                  | 1         | 1.27%   |
| AMD E                   | 1         | 1.27%   |
| AMD A6                  | 1         | 1.27%   |
| AMD A4                  | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 45        | 56.96%  |
| 4       | 13        | 16.46%  |
| Unknown | 11        | 13.92%  |
| 8       | 5         | 6.33%   |
| 1       | 3         | 3.8%    |
| 12      | 1         | 1.27%   |
| 10      | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 74        | 93.67%  |
| 2       | 3         | 3.8%    |
| Unknown | 2         | 2.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 54.43%  |
| 1       | 25        | 31.65%  |
| Unknown | 11        | 13.92%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 11        | 13.92%  |
| SandyBridge | 8         | 10.13%  |
| Broadwell   | 8         | 10.13%  |
| KabyLake    | 6         | 7.59%   |
| IvyBridge   | 6         | 7.59%   |
| Haswell     | 6         | 7.59%   |
| Bonnell     | 5         | 6.33%   |
| Unknown     | 5         | 6.33%   |
| Westmere    | 4         | 5.06%   |
| Skylake     | 4         | 5.06%   |
| Zen+        | 3         | 3.8%    |
| Zen         | 2         | 2.53%   |
| Silvermont  | 2         | 2.53%   |
| Jaguar      | 2         | 2.53%   |
| Puma        | 1         | 1.27%   |
| P6          | 1         | 1.27%   |
| Nehalem     | 1         | 1.27%   |
| K8 Hammer   | 1         | 1.27%   |
| Core        | 1         | 1.27%   |
| CometLake   | 1         | 1.27%   |
| Bobcat      | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 62.92%  |
| AMD                        | 17        | 19.1%   |
| Nvidia                     | 15        | 16.85%  |
| Matrox Electronics Systems | 1         | 1.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 8.6%    |
| Intel HD Graphics 5500                                                                   | 7         | 7.53%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 4.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 4.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 4.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 4.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 3.23%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 2         | 2.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.15%   |
| Intel HD Graphics 620                                                                    | 2         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.15%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.08%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 1.08%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.08%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 1.08%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.08%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.08%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 1.08%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 1.08%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 1         | 1.08%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.08%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 1         | 1.08%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.08%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 1.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 1.08%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.08%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.08%   |
| Intel HD Graphics 530                                                                    | 1         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.08%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 43.59%  |
| 1 x AMD        | 13        | 16.67%  |
| 2 x Intel      | 11        | 14.1%   |
| Intel + Nvidia | 9         | 11.54%  |
| 1 x Nvidia     | 6         | 7.69%   |
| Intel + AMD    | 2         | 2.56%   |
| Other          | 1         | 1.28%   |
| 2 x AMD        | 1         | 1.28%   |
| AMD + Matrox   | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 83.75%  |
| Proprietary | 8         | 10%     |
| Unknown     | 5         | 6.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 78.21%  |
| 0.01-0.5   | 9         | 11.54%  |
| 1.01-2.0   | 5         | 6.41%   |
| 5.01-6.0   | 1         | 1.28%   |
| 3.01-4.0   | 1         | 1.28%   |
| 0.51-1.0   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 16        | 29.09%  |
| LG Display              | 11        | 20%     |
| BOE                     | 6         | 10.91%  |
| Chimei Innolux          | 5         | 9.09%   |
| Samsung Electronics     | 4         | 7.27%   |
| Lenovo                  | 2         | 3.64%   |
| HannStar                | 2         | 3.64%   |
| Apple                   | 2         | 3.64%   |
| ___                     | 1         | 1.82%   |
| LPL                     | 1         | 1.82%   |
| LG Philips              | 1         | 1.82%   |
| HKC                     | 1         | 1.82%   |
| Hewlett-Packard         | 1         | 1.82%   |
| Fujitsu Siemens         | 1         | 1.82%   |
| Chi Mei Optoelectronics | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch            | 2         | 3.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 2         | 3.64%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 1.82%   |
| LPL LCD Monitor 1680x1050                                                | 1         | 1.82%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD045D 1366x768 350x190mm 15.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.82%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 1.82%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch                 | 1         | 1.82%   |
| HKC LCD Monitor 24E6C 1920x1080                                          | 1         | 1.82%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch               | 1         | 1.82%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1554 1280x800 330x210mm 15.4-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE0893 2160x1440 300x200mm 14.2-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                     | 1         | 1.82%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 1         | 1.82%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 1         | 1.82%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch           | 1         | 1.82%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch           | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 25        | 46.3%   |
| 1920x1080 (FHD)    | 16        | 29.63%  |
| 1024x600           | 4         | 7.41%   |
| 1280x800 (WXGA)    | 3         | 5.56%   |
| 1600x900 (HD+)     | 2         | 3.7%    |
| 3840x2400          | 1         | 1.85%   |
| 2160x1440          | 1         | 1.85%   |
| 1680x1050 (WSXGA+) | 1         | 1.85%   |
| 1440x900 (WXGA+)   | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 28        | 50.91%  |
| 13      | 11        | 20%     |
| 10      | 4         | 7.27%   |
| 12      | 3         | 5.45%   |
| Unknown | 3         | 5.45%   |
| 17      | 2         | 3.64%   |
| 24      | 1         | 1.82%   |
| 23      | 1         | 1.82%   |
| 14      | 1         | 1.82%   |
| 11      | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 67.27%  |
| 201-300     | 11        | 20%     |
| Unknown     | 3         | 5.45%   |
| 501-600     | 2         | 3.64%   |
| 351-400     | 2         | 3.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 43        | 82.69%  |
| 16/10   | 6         | 11.54%  |
| Unknown | 2         | 3.85%   |
| 3/2     | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 18        | 32.73%  |
| 81-90          | 11        | 20%     |
| 101-110        | 10        | 18.18%  |
| 41-50          | 4         | 7.27%   |
| 61-70          | 3         | 5.45%   |
| Unknown        | 3         | 5.45%   |
| 201-250        | 2         | 3.64%   |
| 121-130        | 2         | 3.64%   |
| 51-60          | 1         | 1.82%   |
| 111-120        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 22        | 40%     |
| 121-160       | 16        | 29.09%  |
| 51-100        | 11        | 20%     |
| Unknown       | 3         | 5.45%   |
| 161-240       | 2         | 3.64%   |
| More than 240 | 1         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 75%     |
| 0     | 17        | 21.25%  |
| 2     | 3         | 3.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 39        | 30.95%  |
| Qualcomm Atheros                 | 26        | 20.63%  |
| Realtek Semiconductor            | 24        | 19.05%  |
| Broadcom                         | 15        | 11.9%   |
| Marvell Technology Group         | 4         | 3.17%   |
| Samsung Electronics              | 2         | 1.59%   |
| Ralink Technology                | 2         | 1.59%   |
| Huawei Technologies              | 2         | 1.59%   |
| Xiaomi                           | 1         | 0.79%   |
| T & A Mobile Phones              | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |
| OPPO Electronics                 | 1         | 0.79%   |
| NetGear                          | 1         | 0.79%   |
| MediaTek                         | 1         | 0.79%   |
| Lenovo                           | 1         | 0.79%   |
| JMicron Technology               | 1         | 0.79%   |
| Hewlett-Packard                  | 1         | 0.79%   |
| Edimax Technology                | 1         | 0.79%   |
| BUFFALO                          | 1         | 0.79%   |
| AMD                              | 1         | 0.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 19        | 11.95%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.4%    |
| Intel Wireless 7265                                                     | 6         | 3.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.14%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.52%   |
| Intel Wireless 8260                                                     | 4         | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.89%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.89%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 1.26%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 1.26%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 1.26%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 1.26%   |
| Intel Wireless 7260                                                     | 2         | 1.26%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.26%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 1.26%   |
| Intel 82574L Gigabit Network Connection                                 | 2         | 1.26%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.26%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.63%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                             | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.63%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.63%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 37.5%   |
| Qualcomm Atheros      | 25        | 31.25%  |
| Broadcom              | 12        | 15%     |
| Realtek Semiconductor | 7         | 8.75%   |
| Ralink Technology     | 2         | 2.5%    |
| NetGear               | 1         | 1.25%   |
| MediaTek              | 1         | 1.25%   |
| Edimax Technology     | 1         | 1.25%   |
| BUFFALO               | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 8.75%   |
| Intel Wireless 7265                                                     | 6         | 7.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 6.25%   |
| Intel Wireless 8265 / 8275                                              | 5         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5%      |
| Intel Wireless 8260                                                     | 4         | 5%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.5%    |
| Intel Wireless 7260                                                     | 2         | 2.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.5%    |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 2.5%    |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 2.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.25%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.25%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 1.25%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.25%   |
| Intel WiFi Link 5100                                                    | 1         | 1.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.25%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 1.25%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.25%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 1         | 1.25%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.25%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.25%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                 | 1         | 1.25%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 25        | 33.33%  |
| Realtek Semiconductor            | 23        | 30.67%  |
| Qualcomm Atheros                 | 10        | 13.33%  |
| Marvell Technology Group         | 4         | 5.33%   |
| Broadcom                         | 4         | 5.33%   |
| Samsung Electronics              | 2         | 2.67%   |
| Xiaomi                           | 1         | 1.33%   |
| T & A Mobile Phones              | 1         | 1.33%   |
| Silicon Integrated Systems [SiS] | 1         | 1.33%   |
| OPPO Electronics                 | 1         | 1.33%   |
| Lenovo                           | 1         | 1.33%   |
| JMicron Technology               | 1         | 1.33%   |
| AMD                              | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 25.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 4%      |
| Intel Ethernet Connection I219-LM                                      | 3         | 4%      |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 4%      |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 2.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 2.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 2.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 2.67%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 2.67%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 2.67%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 2.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.33%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                            | 1         | 1.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.33%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.33%   |
| OPPO WAIPIO-MTP _SN:2EE444D0 RNDIS Control RNDIS Ethernet Data         | 1         | 1.33%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.33%   |
| Lenovo Lenovo Tab M10 Plus 3rd Gen RNDIS Control RNDIS Ethernet Data   | 1         | 1.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.33%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.33%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.33%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.33%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.33%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.33%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.33%   |
| Intel 82566MC Gigabit Network Connection                               | 1         | 1.33%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1.33%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 49.66%  |
| Ethernet | 69        | 47.59%  |
| Modem    | 3         | 2.07%   |
| Unknown  | 1         | 0.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 55.43%  |
| Ethernet | 41        | 44.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 79.49%  |
| 1     | 11        | 14.1%   |
| 6     | 3         | 3.85%   |
| 5     | 1         | 1.28%   |
| 3     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 77        | 98.72%  |
| Yes  | 1         | 1.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 37.74%  |
| Broadcom                        | 7         | 13.21%  |
| Qualcomm Atheros Communications | 6         | 11.32%  |
| Realtek Semiconductor           | 4         | 7.55%   |
| Lite-On Technology              | 4         | 7.55%   |
| Apple                           | 3         | 5.66%   |
| IMC Networks                    | 2         | 3.77%   |
| Cambridge Silicon Radio         | 2         | 3.77%   |
| Toshiba                         | 1         | 1.89%   |
| Hewlett-Packard                 | 1         | 1.89%   |
| Foxconn / Hon Hai               | 1         | 1.89%   |
| Dell                            | 1         | 1.89%   |
| ASUSTek Computer                | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 28.3%   |
| Intel AX201 Bluetooth                                       | 3         | 5.66%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 3.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 3.77%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 3.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.77%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 3.77%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.89%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.89%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.89%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.89%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.89%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.89%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.89%   |
| Intel AX210 Bluetooth                                       | 1         | 1.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.89%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.89%   |
| Dell Wireless 360 Bluetooth                                 | 1         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.89%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.89%   |
| Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.89%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.89%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.89%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 63        | 72.41%  |
| AMD                              | 15        | 17.24%  |
| Nvidia                           | 6         | 6.9%    |
| Silicon Integrated Systems [SiS] | 1         | 1.15%   |
| C-Media Electronics              | 1         | 1.15%   |
| Apogee Electronics               | 1         | 1.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 8.33%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 7.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 6.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 4.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.85%   |
| Unknown                                                                                           | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.93%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.93%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.93%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.93%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.93%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.93%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.93%   |
| Apogee Electronics MiniMe                                                                         | 1         | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.93%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 26.37%  |
| SK hynix            | 16        | 17.58%  |
| Unknown             | 10        | 10.99%  |
| Micron Technology   | 9         | 9.89%   |
| Unknown             | 8         | 8.79%   |
| Kingston            | 8         | 8.79%   |
| Crucial             | 6         | 6.59%   |
| Nanya Technology    | 3         | 3.3%    |
| Transcend           | 2         | 2.2%    |
| Ramaxel Technology  | 1         | 1.1%    |
| Elpida              | 1         | 1.1%    |
| ASint Technology    | 1         | 1.1%    |
| A-DATA Technology   | 1         | 1.1%    |
| 48spaces            | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 10.2%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 4.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 3.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 2.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.04%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 2.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.04%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 2.04%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1333MT/s             | 2         | 2.04%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s           | 2         | 2.04%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 2.04%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 2.04%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 1.02%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 1.02%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 1.02%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.02%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s             | 1         | 1.02%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 1.02%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 1         | 1.02%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 1.02%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s          | 1         | 1.02%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 1.02%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.02%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 38        | 50%     |
| DDR4    | 17        | 22.37%  |
| DDR2    | 11        | 14.47%  |
| SDRAM   | 3         | 3.95%   |
| Unknown | 3         | 3.95%   |
| DDR     | 2         | 2.63%   |
| LPDDR4  | 1         | 1.32%   |
| LPDDR3  | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 92%     |
| Row Of Chips | 3         | 4%      |
| Chip         | 3         | 4%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 38.82%  |
| 8192  | 22        | 25.88%  |
| 2048  | 20        | 23.53%  |
| 16384 | 4         | 4.71%   |
| 1024  | 4         | 4.71%   |
| 32768 | 1         | 1.18%   |
| 256   | 1         | 1.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 28.4%   |
| 667     | 11        | 13.58%  |
| 2667    | 7         | 8.64%   |
| 3200    | 6         | 7.41%   |
| 1333    | 6         | 7.41%   |
| 2400    | 5         | 6.17%   |
| 1067    | 5         | 6.17%   |
| 2133    | 4         | 4.94%   |
| 1334    | 3         | 3.7%    |
| 800     | 3         | 3.7%    |
| Unknown | 3         | 3.7%    |
| 2048    | 1         | 1.23%   |
| 1867    | 1         | 1.23%   |
| 1066    | 1         | 1.23%   |
| 975     | 1         | 1.23%   |
| 333     | 1         | 1.23%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 31.67%  |
| IMC Networks                           | 8         | 13.33%  |
| Realtek Semiconductor                  | 7         | 11.67%  |
| Sunplus Innovation Technology          | 5         | 8.33%   |
| Bison Electronics                      | 5         | 8.33%   |
| ALi                                    | 3         | 5%      |
| Z-Star Microelectronics                | 2         | 3.33%   |
| Silicon Motion                         | 2         | 3.33%   |
| Syntek                                 | 1         | 1.67%   |
| Suyin                                  | 1         | 1.67%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.67%   |
| Microdia                               | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Lenovo                                 | 1         | 1.67%   |
| Cubeternet                             | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.67%   |
| Apple                                  | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 4         | 6.67%   |
| Realtek Integrated_Webcam_HD               | 3         | 5%      |
| Realtek USB Camera                         | 2         | 3.33%   |
| Realtek Lenovo EasyCamera                  | 2         | 3.33%   |
| IMC Networks Realtek PC Camera             | 2         | 3.33%   |
| IMC Networks Integrated Camera             | 2         | 3.33%   |
| Chicony USB2.0 VGA UVC WebCam              | 2         | 3.33%   |
| Chicony HD WebCam (Acer)                   | 2         | 3.33%   |
| Bison Integrated Camera                    | 2         | 3.33%   |
| ALi Gateway Webcam                         | 2         | 3.33%   |
| Z-Star Webcam                              | 1         | 1.67%   |
| Z-Star Vega USB 2.0 Camera                 | 1         | 1.67%   |
| Syntek EasyCamera                          | 1         | 1.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.67%   |
| Sunplus Integrated Camera                  | 1         | 1.67%   |
| Sunplus Hy HD Camera                       | 1         | 1.67%   |
| Sunplus Dell E5570 integrated webcam       | 1         | 1.67%   |
| Sunplus 1.3M HD WebCam                     | 1         | 1.67%   |
| Silicon Motion Realtek USB 2.0 PC Camera   | 1         | 1.67%   |
| Silicon Motion HP Webcam-50                | 1         | 1.67%   |
| Shenzhen Kingcome Optoelectronic HD Webcam | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD              | 1         | 1.67%   |
| Lite-On HP TrueVision HD Camera            | 1         | 1.67%   |
| Lenovo Integrated Webcam [R5U877]          | 1         | 1.67%   |
| IMC Networks UVC VGA Webcam                | 1         | 1.67%   |
| IMC Networks USB 2.0 UVC HD Webcam         | 1         | 1.67%   |
| IMC Networks Realtek DMFT RGB              | 1         | 1.67%   |
| IMC Networks Integrated Webcam             | 1         | 1.67%   |
| Cubeternet WebCam                          | 1         | 1.67%   |
| Chicony WebCam                             | 1         | 1.67%   |
| Chicony Toshiba Integrated Webcam          | 1         | 1.67%   |
| Chicony ThinkPad T490 Webcam               | 1         | 1.67%   |
| Chicony Thinkpad T430 camera               | 1         | 1.67%   |
| Chicony Integrated Camera [ThinkPad]       | 1         | 1.67%   |
| Chicony Integrated Camera (1280x720@30)    | 1         | 1.67%   |
| Chicony HP TrueVision HD Camera            | 1         | 1.67%   |
| Chicony HD WebCam (Asus N-series)          | 1         | 1.67%   |
| Chicony 2.0M UVC Webcam / CNF7129          | 1         | 1.67%   |
| Chicony 1.3M Webcam                        | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 27.27%  |
| AuthenTec             | 3         | 27.27%  |
| Synaptics             | 2         | 18.18%  |
| Upek                  | 1         | 9.09%   |
| STMicroelectronics    | 1         | 9.09%   |
| Elan Microelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                      | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics UWP WBDI Device                              | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| Elan Fingerprint Sensor                                | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |

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
| 2     | 26        | 31.71%  |
| 1     | 23        | 28.05%  |
| 0     | 16        | 19.51%  |
| 3     | 14        | 17.07%  |
| 4     | 3         | 3.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 46        | 38.33%  |
| Net/wireless             | 18        | 15%     |
| Card reader              | 18        | 15%     |
| Bluetooth                | 17        | 14.17%  |
| Fingerprint reader       | 11        | 9.17%   |
| Graphics card            | 3         | 2.5%    |
| Storage                  | 2         | 1.67%   |
| Firewire controller      | 2         | 1.67%   |
| Sound                    | 1         | 0.83%   |
| Network                  | 1         | 0.83%   |
| Modem                    | 1         | 0.83%   |

