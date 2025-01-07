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

Total: 126

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E7250              | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| Lenovo        | ThinkPad X270 20HN0015MX    | [66b1686a32](https://bsd-hardware.info/?probe=66b1686a32) | Dec 25, 2024 |
| ASUSTek       | N550JV                      | [43db70e6e9](https://bsd-hardware.info/?probe=43db70e6e9) | Dec 07, 2024 |
| Dell          | Latitude E7250              | [025ea9ef12](https://bsd-hardware.info/?probe=025ea9ef12) | Sep 30, 2024 |
| Dell          | Latitude E7250              | [2dfb20ed35](https://bsd-hardware.info/?probe=2dfb20ed35) | Sep 27, 2024 |
| HP            | Mini 210-1000               | [5271409065](https://bsd-hardware.info/?probe=5271409065) | Sep 11, 2024 |
| ASUSTek       | 1215N                       | [0970f34b42](https://bsd-hardware.info/?probe=0970f34b42) | Aug 15, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [ddb6ff92c1](https://bsd-hardware.info/?probe=ddb6ff92c1) | Jun 26, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [8f7f98fc18](https://bsd-hardware.info/?probe=8f7f98fc18) | Jun 07, 2024 |
| ASUSTek       | X555UJ                      | [df9f681ce9](https://bsd-hardware.info/?probe=df9f681ce9) | Jun 05, 2024 |
| Dell          | Latitude E7250              | [b5504e5573](https://bsd-hardware.info/?probe=b5504e5573) | Jun 02, 2024 |
| ASUSTek       | X555LAB                     | [e39c22cfc5](https://bsd-hardware.info/?probe=e39c22cfc5) | May 18, 2024 |
| Deciso        | NetBoard-A20                | [121c0144ee](https://bsd-hardware.info/?probe=121c0144ee) | May 16, 2024 |
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
| helloSystem 0.8.1    | 14        | 14.29%  |
| helloSystem 0.7.0    | 13        | 13.27%  |
| helloSystem 0.5.0    | 5         | 5.1%    |
| helloSystem 0.4.0    | 5         | 5.1%    |
| helloSystem 0.9.0    | 4         | 4.08%   |
| helloSystem 0.8.0    | 4         | 4.08%   |
| helloSystem 0.6.0    | 3         | 3.06%   |
| NomadBSD 1.3.2       | 2         | 2.04%   |
| helloSystem 0.3.0    | 2         | 2.04%   |
| GhostBSD 21.08.27    | 2         | 2.04%   |
| GhostBSD 20.04.02    | 2         | 2.04%   |
| FreeBSD 13.1         | 2         | 2.04%   |
| OPNsense 23.7.9      | 1         | 1.02%   |
| OPNsense 23.10.3     | 1         | 1.02%   |
| OPNsense 22.1.9      | 1         | 1.02%   |
| OPNsense 22.1.6      | 1         | 1.02%   |
| OPNsense 21.7.7      | 1         | 1.02%   |
| OPNsense 21.1        | 1         | 1.02%   |
| OpenBSD 7.6          | 1         | 1.02%   |
| OpenBSD 7.5          | 1         | 1.02%   |
| OpenBSD 7.2          | 1         | 1.02%   |
| OpenBSD 7.1          | 1         | 1.02%   |
| OpenBSD 6.8          | 1         | 1.02%   |
| OpenBSD 6.7          | 1         | 1.02%   |
| NomadBSD 5806f915    | 1         | 1.02%   |
| NomadBSD 1.4         | 1         | 1.02%   |
| NomadBSD 1.3.1       | 1         | 1.02%   |
| NetBSD 9.2_STABLE    | 1         | 1.02%   |
| NetBSD 9.2           | 1         | 1.02%   |
| NetBSD 9.1           | 1         | 1.02%   |
| NetBSD 9.0           | 1         | 1.02%   |
| NetBSD 10.99.1       | 1         | 1.02%   |
| GhostBSD 23.10.1     | 1         | 1.02%   |
| GhostBSD 23.09.16    | 1         | 1.02%   |
| GhostBSD 23.06.05    | 1         | 1.02%   |
| GhostBSD 22.11.02    | 1         | 1.02%   |
| GhostBSD 22.06.26    | 1         | 1.02%   |
| FreeBSD 14.1         | 1         | 1.02%   |
| FreeBSD 14.0-p4      | 1         | 1.02%   |
| FreeBSD 14.0-CURRENT | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 45        | 50.56%  |
| FreeBSD     | 16        | 17.98%  |
| GhostBSD    | 7         | 7.87%   |
| OPNsense    | 6         | 6.74%   |
| OpenBSD     | 6         | 6.74%   |
| NomadBSD    | 5         | 5.62%   |
| NetBSD      | 4         | 4.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 85        | 97.7%   |
| i386  | 2         | 2.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 46        | 51.11%  |
| Console      | 8         | 8.89%   |
| XFCE         | 6         | 6.67%   |
| KDE5         | 6         | 6.67%   |
| Openbox      | 5         | 5.56%   |
| MATE         | 3         | 3.33%   |
| i3           | 3         | 3.33%   |
| fvwm         | 3         | 3.33%   |
| ctwm         | 3         | 3.33%   |
| Cinnamon     | 3         | 3.33%   |
| TWM          | 2         | 2.22%   |
| LXQt         | 1         | 1.11%   |
| Fluxbox      | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 80        | 91.95%  |
| Console | 6         | 6.9%    |
| Wayland | 1         | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 52        | 59.09%  |
| Console | 21        | 23.86%  |
| LightDM | 7         | 7.95%   |
| SDDM    | 6         | 6.82%   |
| XDM     | 1         | 1.14%   |
| GDM     | 1         | 1.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 41        | 45.05%  |
| it_IT            | 21        | 23.08%  |
| Unknown          | 14        | 15.38%  |
| C                | 6         | 6.59%   |
| it               | 2         | 2.2%    |
| ru_RU            | 1         | 1.1%    |
| LANG="en_US"     | 1         | 1.1%    |
| it_IT.ISO8859-15 | 1         | 1.1%    |
| it_IT.ISO8859-1  | 1         | 1.1%    |
| fr_FR            | 1         | 1.1%    |
| en_GB            | 1         | 1.1%    |
| en               | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 85.06%  |
| BIOS | 13        | 14.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 45        | 50.56%  |
| Ufs    | 20        | 22.47%  |
| Cd9660 | 18        | 20.22%  |
| Ffs    | 6         | 6.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 78        | 89.66%  |
| MBR     | 7         | 8.05%   |
| Unknown | 2         | 2.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 22        | 25.29%  |
| ASUSTek Computer    | 17        | 19.54%  |
| Dell                | 10        | 11.49%  |
| Acer                | 7         | 8.05%   |
| Hewlett-Packard     | 6         | 6.9%    |
| Apple               | 4         | 4.6%    |
| Toshiba             | 3         | 3.45%   |
| Samsung Electronics | 3         | 3.45%   |
| Unknown             | 3         | 3.45%   |
| eMachines           | 2         | 2.3%    |
| Deciso              | 2         | 2.3%    |
| TUXEDO              | 1         | 1.15%   |
| TULPAR              | 1         | 1.15%   |
| Packard Bell        | 1         | 1.15%   |
| MSI                 | 1         | 1.15%   |
| LG Electronics      | 1         | 1.15%   |
| Intel               | 1         | 1.15%   |
| IBM                 | 1         | 1.15%   |
| Chuwi               | 1         | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 4         | 4.6%    |
| Dell Latitude E7250                          | 3         | 3.45%   |
| HP Laptop 15-da0xxx                          | 2         | 2.3%    |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA       | 2         | 2.3%    |
| Apple MacBook4,1                             | 2         | 2.3%    |
| TUXEDO N14xWU                                | 1         | 1.15%   |
| TULPAR A5 V20.3                              | 1         | 1.15%   |
| Toshiba Satellite C855-1U4                   | 1         | 1.15%   |
| Toshiba PORTEGE M780                         | 1         | 1.15%   |
| Samsung R510/P510                            | 1         | 1.15%   |
| Samsung N150P/N210P/N220P                    | 1         | 1.15%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV     | 1         | 1.15%   |
| Packard Bell EasyNote_MX61-B-038             | 1         | 1.15%   |
| MSI GF65 Thin 10SER                          | 1         | 1.15%   |
| LG COLUMBIA                                  | 1         | 1.15%   |
| Lenovo ThinkPad X280 20KES5M300              | 1         | 1.15%   |
| Lenovo ThinkPad X270 20HN0015MX              | 1         | 1.15%   |
| Lenovo ThinkPad X260 20F5S82N00              | 1         | 1.15%   |
| Lenovo ThinkPad X250 20CMS0FA00              | 1         | 1.15%   |
| Lenovo ThinkPad X240 20AMS0J01N              | 1         | 1.15%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1.15%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00     | 1         | 1.15%   |
| Lenovo ThinkPad W530 2447GW3                 | 1         | 1.15%   |
| Lenovo ThinkPad T495 20NJS0KP00              | 1         | 1.15%   |
| Lenovo ThinkPad T460s 20FAS3L002             | 1         | 1.15%   |
| Lenovo ThinkPad T450 20BUS06B00              | 1         | 1.15%   |
| Lenovo ThinkPad T440p                        | 1         | 1.15%   |
| Lenovo ThinkPad T440 20B7S1C600              | 1         | 1.15%   |
| Lenovo ThinkPad T430 23501B3                 | 1         | 1.15%   |
| Lenovo ThinkPad T420 4236BD5                 | 1         | 1.15%   |
| Lenovo ThinkPad T410 2537B94                 | 1         | 1.15%   |
| Lenovo ThinkPad L530 24812TG                 | 1         | 1.15%   |
| Lenovo ThinkBook 16 G6 IRL 21KH              | 1         | 1.15%   |
| Lenovo IdeaPad 3 15ADA05 81W1                | 1         | 1.15%   |
| Lenovo G505 20240                            | 1         | 1.15%   |
| Lenovo G50-45 80E3                           | 1         | 1.15%   |
| Lenovo B590 62743PG                          | 1         | 1.15%   |
| Intel S1200RP_SE                             | 1         | 1.15%   |
| IBM ThinkPad R51 2887AVG                     | 1         | 1.15%   |
| HP ProBook 470 G4                            | 1         | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 17        | 19.54%  |
| Dell Latitude         | 6         | 6.9%    |
| Unknown               | 4         | 4.6%    |
| ASUS VivoBook         | 3         | 3.45%   |
| Acer Aspire           | 3         | 3.45%   |
| HP Laptop             | 2         | 2.3%    |
| Apple MacBook4        | 2         | 2.3%    |
| TUXEDO N14xWU         | 1         | 1.15%   |
| TULPAR A5             | 1         | 1.15%   |
| Toshiba Satellite     | 1         | 1.15%   |
| Toshiba PORTEGE       | 1         | 1.15%   |
| Samsung R510          | 1         | 1.15%   |
| Samsung N150P         | 1         | 1.15%   |
| Samsung 3570R         | 1         | 1.15%   |
| Packard Bell EasyNote | 1         | 1.15%   |
| MSI GF65              | 1         | 1.15%   |
| LG COLUMBIA           | 1         | 1.15%   |
| Lenovo ThinkBook      | 1         | 1.15%   |
| Lenovo IdeaPad        | 1         | 1.15%   |
| Lenovo G505           | 1         | 1.15%   |
| Lenovo G50-45         | 1         | 1.15%   |
| Lenovo B590           | 1         | 1.15%   |
| Intel S1200RP         | 1         | 1.15%   |
| IBM ThinkPad          | 1         | 1.15%   |
| HP ProBook            | 1         | 1.15%   |
| HP Pavilion           | 1         | 1.15%   |
| HP Mini               | 1         | 1.15%   |
| HP EliteBook          | 1         | 1.15%   |
| eMachines eME732ZG    | 1         | 1.15%   |
| eMachines eME728      | 1         | 1.15%   |
| Dell XPS              | 1         | 1.15%   |
| Dell Vostro           | 1         | 1.15%   |
| Dell Precision        | 1         | 1.15%   |
| Dell Inspiron         | 1         | 1.15%   |
| Deciso OPNsense       | 1         | 1.15%   |
| Deciso NetBoard-A20   | 1         | 1.15%   |
| Chuwi GemiBook        | 1         | 1.15%   |
| ASUS X555UJ           | 1         | 1.15%   |
| ASUS X555LJ           | 1         | 1.15%   |
| ASUS X555LD           | 1         | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 12        | 13.79%  |
| 2019 | 9         | 10.34%  |
| 2010 | 9         | 10.34%  |
| 2020 | 7         | 8.05%   |
| 2011 | 7         | 8.05%   |
| 2016 | 5         | 5.75%   |
| 2015 | 5         | 5.75%   |
| 2014 | 5         | 5.75%   |
| 2008 | 5         | 5.75%   |
| 2021 | 4         | 4.6%    |
| 2018 | 4         | 4.6%    |
| 2022 | 3         | 3.45%   |
| 2012 | 3         | 3.45%   |
| 2023 | 2         | 2.3%    |
| 2009 | 2         | 2.3%    |
| 2007 | 2         | 2.3%    |
| 2024 | 1         | 1.15%   |
| 2017 | 1         | 1.15%   |
| 2005 | 1         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 87        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 86        | 98.85%  |
| Yes  | 1         | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 37        | 42.05%  |
| 4.01-8.0   | 25        | 28.41%  |
| 16.01-24.0 | 11        | 12.5%   |
| 2.01-3.0   | 7         | 7.95%   |
| 32.01-64.0 | 4         | 4.55%   |
| 3.01-4.0   | 2         | 2.27%   |
| 24.01-32.0 | 1         | 1.14%   |
| 0.01-0.5   | 1         | 1.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 56        | 63.64%  |
| 0.51-1.0  | 16        | 18.18%  |
| 1.01-2.0  | 5         | 5.68%   |
| 2.01-3.0  | 4         | 4.55%   |
| Unknown   | 4         | 4.55%   |
| 4.01-8.0  | 2         | 2.27%   |
| 8.01-16.0 | 1         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 65        | 73.86%  |
| 2      | 17        | 19.32%  |
| 0      | 6         | 6.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 62.92%  |
| Yes       | 33        | 37.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 88.51%  |
| No        | 10        | 11.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 91.95%  |
| No        | 7         | 8.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 64.04%  |
| No        | 32        | 35.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 87        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Rome                     | 14        | 14.14%  |
| Milan                    | 12        | 12.12%  |
| Turin                    | 4         | 4.04%   |
| Brescia                  | 4         | 4.04%   |
| Bologna                  | 4         | 4.04%   |
| Trieste                  | 2         | 2.02%   |
| Sesto San Giovanni       | 2         | 2.02%   |
| Rho                      | 2         | 2.02%   |
| Padova                   | 2         | 2.02%   |
| Monterotondo             | 2         | 2.02%   |
| Como                     | 2         | 2.02%   |
| Villalfonsina            | 1         | 1.01%   |
| Vigonza                  | 1         | 1.01%   |
| Vigonovo                 | 1         | 1.01%   |
| Udine                    | 1         | 1.01%   |
| Treviso                  | 1         | 1.01%   |
| Solarino                 | 1         | 1.01%   |
| Sassari                  | 1         | 1.01%   |
| Saronno                  | 1         | 1.01%   |
| Roncade                  | 1         | 1.01%   |
| Resana                   | 1         | 1.01%   |
| Prad am Stilfser Joch    | 1         | 1.01%   |
| Piovene Rocchette        | 1         | 1.01%   |
| Pessano Con Bornago      | 1         | 1.01%   |
| Passignano sul Trasimeno | 1         | 1.01%   |
| Nughedu San Nicolo       | 1         | 1.01%   |
| Naturns                  | 1         | 1.01%   |
| Naples                   | 1         | 1.01%   |
| Monza                    | 1         | 1.01%   |
| Milano                   | 1         | 1.01%   |
| Massa Lombarda           | 1         | 1.01%   |
| Malnate                  | 1         | 1.01%   |
| Macerata                 | 1         | 1.01%   |
| Lurago Marinone          | 1         | 1.01%   |
| Lissone                  | 1         | 1.01%   |
| Iglesias                 | 1         | 1.01%   |
| Genzano di Roma          | 1         | 1.01%   |
| Gattinara                | 1         | 1.01%   |
| Galliera Veneta          | 1         | 1.01%   |
| Gallarate                | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 26     | 17.89%  |
| Seagate             | 10        | 13     | 10.53%  |
| Kingston            | 9         | 11     | 9.47%   |
| WDC                 | 8         | 11     | 8.42%   |
| Crucial             | 7         | 12     | 7.37%   |
| Toshiba             | 6         | 6      | 6.32%   |
| SanDisk             | 4         | 4      | 4.21%   |
| Intel               | 4         | 4      | 4.21%   |
| Hitachi             | 4         | 5      | 4.21%   |
| Transcend           | 3         | 3      | 3.16%   |
| Micron Technology   | 2         | 2      | 2.11%   |
| Leven               | 2         | 2      | 2.11%   |
| KingSpec            | 2         | 2      | 2.11%   |
| HGST                | 2         | 3      | 2.11%   |
| FORESEE             | 2         | 3      | 2.11%   |
| Apple               | 2         | 2      | 2.11%   |
| Union Memory        | 1         | 1      | 1.05%   |
| SPCC                | 1         | 1      | 1.05%   |
| SK hynix            | 1         | 1      | 1.05%   |
| Silicon             | 1         | 1      | 1.05%   |
| PNY                 | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| KingDian            | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| Indilinx            | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |
| ASUSTek Computer    | 1         | 2      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                       | 4         | 4.04%   |
| Samsung SSD 860 EVO 250GB                       | 3         | 3.03%   |
| Kingston SA400S37240G 240GB                     | 3         | 3.03%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 2.02%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 2.02%   |
| KingSpec Q-720 720GB                            | 2         | 2.02%   |
| Intel SSDSC2BF180A4L 180GB                      | 2         | 2.02%   |
| WDC WDS500G2B0A-00SM50 500GB                    | 1         | 1.01%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 1.01%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 1.01%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 1.01%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 1.01%   |
| WDC WD2500BEVT-22ZCT0 250GB                     | 1         | 1.01%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 1.01%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 1.01%   |
| Transcend TS256GMTE710T 256GB                   | 1         | 1.01%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 1.01%   |
| Transcend TS120GMTS420S 120GB                   | 1         | 1.01%   |
| Toshiba TR200 240GB                             | 1         | 1.01%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 1.01%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 1.01%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 1.01%   |
| Toshiba MK5065GSX 500GB                         | 1         | 1.01%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 1.01%   |
| SPCC Solid State Disk 256GB                     | 1         | 1.01%   |
| SK hynix SC210 mSATA 256GB                      | 1         | 1.01%   |
| Silicon SATA3 120GB SSD                         | 1         | 1.01%   |
| Seagate ST9750420AS 752GB                       | 1         | 1.01%   |
| Seagate ST9320320AS 320GB                       | 1         | 1.01%   |
| Seagate ST9160821AS 160GB                       | 1         | 1.01%   |
| Seagate ST9160411AS 160GB                       | 1         | 1.01%   |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 1.01%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 1.01%   |
| Seagate ST250LM000 HM251HI 250GB                | 1         | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1.01%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 1         | 1.01%   |
| SanDisk X400 M.2 2280 512GB                     | 1         | 1.01%   |
| SanDisk SSD P4 8GB                              | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 37.04%  |
| Toshiba             | 5         | 5      | 18.52%  |
| WDC                 | 4         | 5      | 14.81%  |
| Hitachi             | 4         | 5      | 14.81%  |
| HGST                | 2         | 3      | 7.41%   |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 21     | 22.81%  |
| Crucial             | 7         | 12     | 12.28%  |
| Kingston            | 6         | 7      | 10.53%  |
| WDC                 | 4         | 6      | 7.02%   |
| SanDisk             | 4         | 4      | 7.02%   |
| Intel               | 3         | 3      | 5.26%   |
| Leven               | 2         | 2      | 3.51%   |
| KingSpec            | 2         | 2      | 3.51%   |
| FORESEE             | 2         | 3      | 3.51%   |
| Apple               | 2         | 2      | 3.51%   |
| Transcend           | 1         | 1      | 1.75%   |
| Toshiba             | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SK hynix            | 1         | 1      | 1.75%   |
| Silicon             | 1         | 1      | 1.75%   |
| PNY                 | 1         | 1      | 1.75%   |
| Netac               | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| KingDian            | 1         | 1      | 1.75%   |
| Intenso             | 1         | 1      | 1.75%   |
| Indilinx            | 1         | 1      | 1.75%   |
| ASUSTek Computer    | 1         | 2      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 52        | 75     | 57.78%  |
| HDD  | 26        | 33     | 28.89%  |
| NVMe | 12        | 13     | 13.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 108    | 85.71%  |
| NVMe | 12        | 13     | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 86     | 84%     |
| 0.51-1.0   | 12        | 22     | 16%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 38        | 42.22%  |
| 101-250    | 25        | 27.78%  |
| 251-500    | 10        | 11.11%  |
| 21-50      | 7         | 7.78%   |
| 51-100     | 7         | 7.78%   |
| 501-1000   | 3         | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 80        | 88.89%  |
| 21-50   | 8         | 8.89%   |
| 101-250 | 1         | 1.11%   |
| 51-100  | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2BF180A4L 180GB            | 2         | 2      | 11.11%  |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 5.56%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 5.56%   |
| SK hynix SC210 mSATA 256GB            | 1         | 1      | 5.56%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 5.56%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 5.56%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 5.56%   |
| SanDisk SDSSDP064G 64GB               | 1         | 1      | 5.56%   |
| SanDisk SD9SN8W-128G-1006 128GB       | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 5.56%   |
| Netac SSD 256GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS548040M9AT00 37GB          | 1         | 2      | 5.56%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 5.56%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 3      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 22.22%  |
| Toshiba             | 2         | 2      | 11.11%  |
| SanDisk             | 2         | 2      | 11.11%  |
| Intel               | 2         | 2      | 11.11%  |
| Hitachi             | 2         | 3      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| SK hynix            | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| HGST                | 1         | 2      | 5.56%   |
| Crucial             | 1         | 3      | 5.56%   |

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
| HGST    | 1         | 2      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 55.56%  |
| SSD  | 8         | 10     | 44.44%  |

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
| Works    | 64        | 96     | 76.19%  |
| Malfunc  | 18        | 22     | 21.43%  |
| Detected | 2         | 3      | 2.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 66        | 70.97%  |
| AMD                              | 9         | 9.68%   |
| Samsung Electronics              | 5         | 5.38%   |
| Kingston Technology Company      | 3         | 3.23%   |
| Transcend                        | 2         | 2.15%   |
| SanDisk                          | 2         | 2.15%   |
| Micron Technology                | 2         | 2.15%   |
| Union Memory (Shenzhen)          | 1         | 1.08%   |
| Silicon Integrated Systems [SiS] | 1         | 1.08%   |
| Nvidia                           | 1         | 1.08%   |
| JMicron Technology               | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 8.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 7         | 6.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 5.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 5         | 4.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 4.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 5         | 4.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 5         | 4.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 3.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 2         | 1.92%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                                  | 1         | 0.96%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                              | 1         | 0.96%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)            | 1         | 0.96%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 1         | 0.96%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.96%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                         | 1         | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                  | 1         | 0.96%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 1         | 0.96%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.96%   |
| Micron 2550 NVMe SSD (DRAM-less)                                                       | 1         | 0.96%   |
| Micron 2210 NVMe SSD [Cobain]                                                          | 1         | 0.96%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                          | 1         | 0.96%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                   | 1         | 0.96%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                         | 1         | 0.96%   |
| JMicron JMB360 AHCI Controller                                                         | 1         | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                       | 1         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.96%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.96%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 69        | 69.7%   |
| NVMe | 15        | 15.15%  |
| IDE  | 12        | 12.12%  |
| RAID | 3         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 86.21%  |
| AMD    | 12        | 13.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 4.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 3.41%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 3.41%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 3.41%   |
| Intel CPU Version                             | 2         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.27%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 1.14%   |
| Intel Pentium M processor                     | 1         | 1.14%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.14%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 1.14%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.14%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 1.14%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 1.14%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.14%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 1.14%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 1.14%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 1.14%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 1.14%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 1.14%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.14%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.14%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.14%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.14%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.14%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.14%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.14%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 1.14%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.14%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 26.14%  |
| Intel Core i7           | 15        | 17.05%  |
| Intel Core 2 Duo        | 7         | 7.95%   |
| Other                   | 6         | 6.82%   |
| Intel Atom              | 6         | 6.82%   |
| Intel Core i3           | 5         | 5.68%   |
| Intel Celeron           | 5         | 5.68%   |
| Intel Pentium           | 4         | 4.55%   |
| AMD Ryzen 5             | 3         | 3.41%   |
| Intel Pentium Dual-Core | 2         | 2.27%   |
| Intel Xeon              | 1         | 1.14%   |
| Intel Pentium M         | 1         | 1.14%   |
| Intel Core 2            | 1         | 1.14%   |
| Intel 686-class         | 1         | 1.14%   |
| AMD Turion 64 X2 Mobile | 1         | 1.14%   |
| AMD Ryzen Embedded      | 1         | 1.14%   |
| AMD Ryzen 7 PRO         | 1         | 1.14%   |
| AMD EPYC                | 1         | 1.14%   |
| AMD E1                  | 1         | 1.14%   |
| AMD E                   | 1         | 1.14%   |
| AMD A6                  | 1         | 1.14%   |
| AMD A4                  | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 50        | 56.82%  |
| 4       | 14        | 15.91%  |
| Unknown | 12        | 13.64%  |
| 8       | 6         | 6.82%   |
| 1       | 3         | 3.41%   |
| 12      | 2         | 2.27%   |
| 10      | 1         | 1.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 82        | 93.18%  |
| 2       | 3         | 3.41%   |
| Unknown | 3         | 3.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 49        | 55.68%  |
| 1       | 27        | 30.68%  |
| Unknown | 12        | 13.64%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 11        | 12.5%   |
| Broadwell   | 11        | 12.5%   |
| SandyBridge | 8         | 9.09%   |
| Haswell     | 7         | 7.95%   |
| Unknown     | 7         | 7.95%   |
| KabyLake    | 6         | 6.82%   |
| IvyBridge   | 6         | 6.82%   |
| Bonnell     | 6         | 6.82%   |
| Skylake     | 5         | 5.68%   |
| Westmere    | 4         | 4.55%   |
| Zen+        | 3         | 3.41%   |
| Zen         | 3         | 3.41%   |
| Silvermont  | 2         | 2.27%   |
| Jaguar      | 2         | 2.27%   |
| Puma        | 1         | 1.14%   |
| P6          | 1         | 1.14%   |
| Nehalem     | 1         | 1.14%   |
| K8 Hammer   | 1         | 1.14%   |
| Core        | 1         | 1.14%   |
| CometLake   | 1         | 1.14%   |
| Bobcat      | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 64        | 64%     |
| Nvidia                     | 18        | 18%     |
| AMD                        | 17        | 17%     |
| Matrox Electronics Systems | 1         | 1%      |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                        | 10        | 9.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 7.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 5         | 4.81%   |
| Intel UHD Graphics 620                                                        | 4         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 3.85%   |
| Intel HD Graphics 620                                                         | 3         | 2.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.88%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 2.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 2.88%   |
| Nvidia GM107M [GeForce GTX 850M]                                              | 2         | 1.92%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.96%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.96%   |
| Nvidia GT218M [ION 2]                                                         | 1         | 0.96%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 0.96%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.96%   |
| Nvidia GM108M [GeForce 930MX]                                                 | 1         | 0.96%   |
| Nvidia GK107M [GeForce GT 750M]                                               | 1         | 0.96%   |
| Nvidia GK107GLM [Quadro K1000M]                                               | 1         | 0.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 1         | 0.96%   |
| Nvidia G86M [Quadro NVS 140M]                                                 | 1         | 0.96%   |
| Nvidia G86M [GeForce 8600M GS]                                                | 1         | 0.96%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 0.96%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                               | 1         | 0.96%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 1         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 0.96%   |
| Intel Raptor Lake-P [UHD Graphics]                                            | 1         | 0.96%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 0.96%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.96%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 0.96%   |
| Intel HD Graphics 6000                                                        | 1         | 0.96%   |
| Intel HD Graphics 530                                                         | 1         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 39        | 44.83%  |
| 1 x AMD                | 13        | 14.94%  |
| 2 x Intel              | 11        | 12.64%  |
| Intel + Nvidia         | 11        | 12.64%  |
| 1 x Nvidia             | 6         | 6.9%    |
| Other                  | 2         | 2.3%    |
| Intel + AMD            | 2         | 2.3%    |
| 2 x Intel + 1 x Nvidia | 1         | 1.15%   |
| 2 x AMD                | 1         | 1.15%   |
| AMD + Matrox           | 1         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 75        | 84.27%  |
| Proprietary | 8         | 8.99%   |
| Unknown     | 6         | 6.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 80.46%  |
| 0.01-0.5   | 9         | 10.34%  |
| 1.01-2.0   | 5         | 5.75%   |
| 5.01-6.0   | 1         | 1.15%   |
| 3.01-4.0   | 1         | 1.15%   |
| 0.51-1.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 27.42%  |
| LG Display              | 12        | 19.35%  |
| Chimei Innolux          | 7         | 11.29%  |
| BOE                     | 7         | 11.29%  |
| Samsung Electronics     | 5         | 8.06%   |
| HannStar                | 3         | 4.84%   |
| Lenovo                  | 2         | 3.23%   |
| Apple                   | 2         | 3.23%   |
| ___                     | 1         | 1.61%   |
| LPL                     | 1         | 1.61%   |
| LG Philips              | 1         | 1.61%   |
| HKC                     | 1         | 1.61%   |
| Hewlett-Packard         | 1         | 1.61%   |
| Fujitsu Siemens         | 1         | 1.61%   |
| Chi Mei Optoelectronics | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch            | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 2         | 3.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 3.23%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch     | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 340x190mm 15.3-inch    | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 1.61%   |
| LPL LCD Monitor 1680x1050                                                | 1         | 1.61%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD045D 1366x768 350x190mm 15.7-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD045C 1366x768 340x190mm 15.3-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 1.61%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch                 | 1         | 1.61%   |
| HKC LCD Monitor 24E6C 1920x1080                                          | 1         | 1.61%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch               | 1         | 1.61%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 1         | 1.61%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch         | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1554 1280x800 330x210mm 15.4-inch | 1         | 1.61%   |
| BOE LCD Monitor BOE0893 2160x1440 300x200mm 14.2-inch                    | 1         | 1.61%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                    | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 30        | 49.18%  |
| 1920x1080 (FHD)    | 18        | 29.51%  |
| 1024x600           | 4         | 6.56%   |
| 1280x800 (WXGA)    | 3         | 4.92%   |
| 1600x900 (HD+)     | 2         | 3.28%   |
| 3840x2400          | 1         | 1.64%   |
| 2160x1440          | 1         | 1.64%   |
| 1680x1050 (WSXGA+) | 1         | 1.64%   |
| 1440x900 (WXGA+)   | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 48.39%  |
| 13      | 11        | 17.74%  |
| 12      | 8         | 12.9%   |
| 10      | 4         | 6.45%   |
| Unknown | 3         | 4.84%   |
| 17      | 2         | 3.23%   |
| 24      | 1         | 1.61%   |
| 23      | 1         | 1.61%   |
| 14      | 1         | 1.61%   |
| 11      | 1         | 1.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 62.9%   |
| 201-300     | 16        | 25.81%  |
| Unknown     | 3         | 4.84%   |
| 501-600     | 2         | 3.23%   |
| 351-400     | 2         | 3.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 50        | 84.75%  |
| 16/10   | 6         | 10.17%  |
| Unknown | 2         | 3.39%   |
| 3/2     | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 20        | 32.26%  |
| 81-90          | 11        | 17.74%  |
| 101-110        | 10        | 16.13%  |
| 61-70          | 8         | 12.9%   |
| 41-50          | 4         | 6.45%   |
| Unknown        | 3         | 4.84%   |
| 201-250        | 2         | 3.23%   |
| 121-130        | 2         | 3.23%   |
| 51-60          | 1         | 1.61%   |
| 111-120        | 1         | 1.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 23        | 37.1%   |
| 121-160       | 21        | 33.87%  |
| 51-100        | 11        | 17.74%  |
| 161-240       | 3         | 4.84%   |
| Unknown       | 3         | 4.84%   |
| More than 240 | 1         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 75.28%  |
| 0     | 19        | 21.35%  |
| 2     | 3         | 3.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 32.14%  |
| Qualcomm Atheros                 | 29        | 20.71%  |
| Realtek Semiconductor            | 25        | 17.86%  |
| Broadcom                         | 16        | 11.43%  |
| Marvell Technology Group         | 4         | 2.86%   |
| Samsung Electronics              | 2         | 1.43%   |
| Ralink Technology                | 2         | 1.43%   |
| Huawei Technologies              | 2         | 1.43%   |
| AMD                              | 2         | 1.43%   |
| Xiaomi                           | 1         | 0.71%   |
| T & A Mobile Phones              | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |
| OPPO Electronics                 | 1         | 0.71%   |
| NetGear                          | 1         | 0.71%   |
| Motorola PCS                     | 1         | 0.71%   |
| MediaTek                         | 1         | 0.71%   |
| Lenovo                           | 1         | 0.71%   |
| JMicron Technology               | 1         | 0.71%   |
| Hewlett-Packard                  | 1         | 0.71%   |
| Edimax Technology                | 1         | 0.71%   |
| Dell                             | 1         | 0.71%   |
| BUFFALO                          | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 20        | 11.17%  |
| Intel Wireless 7265                                                     | 9         | 5.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.35%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.35%   |
| Intel Ethernet Connection (3) I218-LM                                   | 6         | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.23%   |
| Intel Wireless 8260                                                     | 4         | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 1.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.68%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.68%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 1.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.68%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 1.12%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 1.12%   |
| Intel Wireless 7260                                                     | 2         | 1.12%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.12%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 1.12%   |
| Intel 82574L Gigabit Network Connection                                 | 2         | 1.12%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.12%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.12%   |
| AMD XGMAC 10GbE Controller                                              | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.56%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                             | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.56%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.56%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 39.33%  |
| Qualcomm Atheros      | 27        | 30.34%  |
| Broadcom              | 13        | 14.61%  |
| Realtek Semiconductor | 7         | 7.87%   |
| Ralink Technology     | 2         | 2.25%   |
| NetGear               | 1         | 1.12%   |
| MediaTek              | 1         | 1.12%   |
| Edimax Technology     | 1         | 1.12%   |
| Dell                  | 1         | 1.12%   |
| BUFFALO               | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 9         | 10%     |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 8.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 6         | 6.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 4.44%   |
| Intel Wireless 8260                                                     | 4         | 4.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 4.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 2.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 2.22%   |
| Intel Wireless 7260                                                     | 2         | 2.22%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 2.22%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 2.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 2.22%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.11%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.11%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 1.11%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 1.11%   |
| Intel WiFi Link 5100                                                    | 1         | 1.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 1.11%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.11%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.11%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 1.11%   |
| Dell Wireless 5809e Gobi 4G LTE Mobile Broadband DM Port                | 1         | 1.11%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                 | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 36.47%  |
| Realtek Semiconductor            | 24        | 28.24%  |
| Qualcomm Atheros                 | 11        | 12.94%  |
| Marvell Technology Group         | 4         | 4.71%   |
| Broadcom                         | 4         | 4.71%   |
| Samsung Electronics              | 2         | 2.35%   |
| AMD                              | 2         | 2.35%   |
| Xiaomi                           | 1         | 1.18%   |
| T & A Mobile Phones              | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] | 1         | 1.18%   |
| OPPO Electronics                 | 1         | 1.18%   |
| Motorola PCS                     | 1         | 1.18%   |
| Lenovo                           | 1         | 1.18%   |
| JMicron Technology               | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 23.53%  |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 7.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 3.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 3.53%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 3.53%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.53%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 2.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 2.35%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 2.35%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 2.35%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 2.35%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 2.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.18%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                            | 1         | 1.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.18%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.18%   |
| OPPO KALAMA-MTP_CID:0437_SN:B2767D06 RNDIS Control RNDIS Ethernet Data | 1         | 1.18%   |
| Motorola PCS USB RNDIS Device                                          | 1         | 1.18%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.18%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.18%   |
| Lenovo Lenovo Tab M10 Plus 3rd Gen RNDIS Control RNDIS Ethernet Data   | 1         | 1.18%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1.18%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.18%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.18%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.18%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.18%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.18%   |
| Intel 82566MC Gigabit Network Connection                               | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 49.69%  |
| Ethernet | 77        | 47.83%  |
| Modem    | 3         | 1.86%   |
| Unknown  | 1         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 55.45%  |
| Ethernet | 45        | 44.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 79.31%  |
| 1     | 12        | 13.79%  |
| 6     | 4         | 4.6%    |
| 5     | 1         | 1.15%   |
| 3     | 1         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 97.7%   |
| Yes  | 2         | 2.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 41.67%  |
| Broadcom                        | 7         | 11.67%  |
| Qualcomm Atheros Communications | 6         | 10%     |
| Realtek Semiconductor           | 4         | 6.67%   |
| Lite-On Technology              | 4         | 6.67%   |
| IMC Networks                    | 4         | 6.67%   |
| Apple                           | 3         | 5%      |
| Cambridge Silicon Radio         | 2         | 3.33%   |
| Toshiba                         | 1         | 1.67%   |
| Hewlett-Packard                 | 1         | 1.67%   |
| Foxconn / Hon Hai               | 1         | 1.67%   |
| Dell                            | 1         | 1.67%   |
| ASUSTek Computer                | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 31.67%  |
| Intel AX201 Bluetooth                                       | 4         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 3.33%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.33%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 3.33%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.67%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.67%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.67%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.67%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.67%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.67%   |
| Intel AX210 Bluetooth                                       | 1         | 1.67%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.67%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.67%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS     | 1         | 1.67%   |
| IMC Networks Bluetooth module                               | 1         | 1.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.67%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.67%   |
| Dell Wireless 360 Bluetooth                                 | 1         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.67%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.67%   |
| Broadcom BCM2070 Bluetooth                                  | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.67%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.67%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.67%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 71        | 74.74%  |
| AMD                              | 15        | 15.79%  |
| Nvidia                           | 6         | 6.32%   |
| Silicon Integrated Systems [SiS] | 1         | 1.05%   |
| C-Media Electronics              | 1         | 1.05%   |
| Apogee Electronics               | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 9.17%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 9.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 5%      |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 6         | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5         | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.5%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.5%    |
| AMD FCH Azalia Controller                                                                         | 3         | 2.5%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.67%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.83%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.83%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.83%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.83%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.83%   |
| Apogee Electronics MiniMe                                                                         | 1         | 0.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.83%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 27.27%  |
| SK hynix            | 17        | 17.17%  |
| Micron Technology   | 11        | 11.11%  |
| Unknown             | 10        | 10.1%   |
| Unknown             | 9         | 9.09%   |
| Kingston            | 8         | 8.08%   |
| Crucial             | 6         | 6.06%   |
| Transcend           | 3         | 3.03%   |
| Nanya Technology    | 3         | 3.03%   |
| Ramaxel Technology  | 1         | 1.01%   |
| Elpida              | 1         | 1.01%   |
| ASint Technology    | 1         | 1.01%   |
| A-DATA Technology   | 1         | 1.01%   |
| 48spaces            | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 10        | 9.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 3.74%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.8%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.87%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 1.87%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 1.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.87%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1333MT/s             | 2         | 1.87%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                      | 2         | 1.87%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.87%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                       | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.93%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.93%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s             | 1         | 0.93%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.93%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.93%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s          | 1         | 0.93%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 0.93%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 43        | 51.81%  |
| DDR4    | 18        | 21.69%  |
| DDR2    | 11        | 13.25%  |
| SDRAM   | 3         | 3.61%   |
| Unknown | 3         | 3.61%   |
| DDR     | 2         | 2.41%   |
| LPDDR4  | 1         | 1.2%    |
| LPDDR3  | 1         | 1.2%    |
| DDR5    | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 92.68%  |
| Row Of Chips | 3         | 3.66%   |
| Chip         | 3         | 3.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 37.63%  |
| 8192  | 25        | 26.88%  |
| 2048  | 21        | 22.58%  |
| 16384 | 6         | 6.45%   |
| 1024  | 4         | 4.3%    |
| 32768 | 1         | 1.08%   |
| 256   | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 28.57%  |
| 667     | 11        | 12.09%  |
| 2667    | 8         | 8.79%   |
| 3200    | 7         | 7.69%   |
| 1333    | 7         | 7.69%   |
| 2400    | 5         | 5.49%   |
| 1067    | 5         | 5.49%   |
| 2133    | 4         | 4.4%    |
| 1334    | 4         | 4.4%    |
| 800     | 4         | 4.4%    |
| Unknown | 3         | 3.3%    |
| 1867    | 2         | 2.2%    |
| 5600    | 1         | 1.1%    |
| 2048    | 1         | 1.1%    |
| 1066    | 1         | 1.1%    |
| 975     | 1         | 1.1%    |
| 333     | 1         | 1.1%    |

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
| Chicony Electronics                    | 21        | 30.88%  |
| IMC Networks                           | 9         | 13.24%  |
| Realtek Semiconductor                  | 8         | 11.76%  |
| Sunplus Innovation Technology          | 7         | 10.29%  |
| Bison Electronics                      | 6         | 8.82%   |
| ALi                                    | 3         | 4.41%   |
| Z-Star Microelectronics                | 2         | 2.94%   |
| Silicon Motion                         | 2         | 2.94%   |
| Microdia                               | 2         | 2.94%   |
| Syntek                                 | 1         | 1.47%   |
| Suyin                                  | 1         | 1.47%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.47%   |
| Lite-On Technology                     | 1         | 1.47%   |
| Lenovo                                 | 1         | 1.47%   |
| Cubeternet                             | 1         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.47%   |
| Apple                                  | 1         | 1.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 5         | 7.35%   |
| Realtek Integrated_Webcam_HD               | 3         | 4.41%   |
| Bison Integrated Camera                    | 3         | 4.41%   |
| Realtek USB Camera                         | 2         | 2.94%   |
| Realtek Lenovo EasyCamera                  | 2         | 2.94%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.94%   |
| IMC Networks UVC VGA Webcam                | 2         | 2.94%   |
| IMC Networks Realtek PC Camera             | 2         | 2.94%   |
| IMC Networks Integrated Camera             | 2         | 2.94%   |
| Chicony USB2.0 VGA UVC WebCam              | 2         | 2.94%   |
| Chicony HD WebCam (Asus N-series)          | 2         | 2.94%   |
| Chicony HD WebCam (Acer)                   | 2         | 2.94%   |
| ALi Gateway Webcam                         | 2         | 2.94%   |
| Z-Star Webcam                              | 1         | 1.47%   |
| Z-Star Vega USB 2.0 Camera                 | 1         | 1.47%   |
| Syntek EasyCamera                          | 1         | 1.47%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 1         | 1.47%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.47%   |
| Sunplus Laptop Integrated Webcam HD        | 1         | 1.47%   |
| Sunplus Integrated_Webcam_HD               | 1         | 1.47%   |
| Sunplus Integrated Camera                  | 1         | 1.47%   |
| Sunplus Hy HD Camera                       | 1         | 1.47%   |
| Sunplus Dell E5570 integrated webcam       | 1         | 1.47%   |
| Sunplus 1.3M HD WebCam                     | 1         | 1.47%   |
| Silicon Motion Realtek USB 2.0 PC Camera   | 1         | 1.47%   |
| Silicon Motion HP Webcam-50                | 1         | 1.47%   |
| Shenzhen Kingcome Optoelectronic HD Webcam | 1         | 1.47%   |
| Realtek USB2.0 VGA UVC WebCam              | 1         | 1.47%   |
| Lite-On HP TrueVision HD Camera            | 1         | 1.47%   |
| Lenovo Integrated Webcam [R5U877]          | 1         | 1.47%   |
| IMC Networks USB 2.0 UVC HD Webcam         | 1         | 1.47%   |
| IMC Networks Realtek DMFT RGB              | 1         | 1.47%   |
| IMC Networks Integrated Webcam             | 1         | 1.47%   |
| Cubeternet WebCam                          | 1         | 1.47%   |
| Chicony WebCam                             | 1         | 1.47%   |
| Chicony Toshiba Integrated Webcam          | 1         | 1.47%   |
| Chicony ThinkPad T490 Webcam               | 1         | 1.47%   |
| Chicony Thinkpad T430 camera               | 1         | 1.47%   |
| Chicony Integrated Camera [ThinkPad]       | 1         | 1.47%   |
| Chicony Integrated Camera (1280x720@30)    | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 28.57%  |
| AuthenTec                  | 3         | 21.43%  |
| Synaptics                  | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| STMicroelectronics         | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |
| Broadcom                   | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                                            | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 7.14%   |
| Synaptics UWP WBDI Device                                                    | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 7.14%   |
| Elan Fingerprint Sensor                                                      | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| AuthenTec AES2810                                                            | 1         | 7.14%   |

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
| 2     | 29        | 31.52%  |
| 1     | 28        | 30.43%  |
| 0     | 17        | 18.48%  |
| 3     | 15        | 16.3%   |
| 4     | 3         | 3.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 39.39%  |
| Card reader              | 20        | 15.15%  |
| Net/wireless             | 19        | 14.39%  |
| Bluetooth                | 18        | 13.64%  |
| Fingerprint reader       | 13        | 9.85%   |
| Graphics card            | 3         | 2.27%   |
| Storage                  | 2         | 1.52%   |
| Firewire controller      | 2         | 1.52%   |
| Sound                    | 1         | 0.76%   |
| Network                  | 1         | 0.76%   |
| Modem                    | 1         | 0.76%   |

