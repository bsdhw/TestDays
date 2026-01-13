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

Total: 148

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d80d321b9c](https://bsd-hardware.info/?probe=d80d321b9c) | Dec 28, 2025 |
| HP            | EliteBook 860 16 inch G9... | [cdfec7a726](https://bsd-hardware.info/?probe=cdfec7a726) | Dec 12, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | [8b275be7b0](https://bsd-hardware.info/?probe=8b275be7b0) | Dec 10, 2025 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [576e8fb25d](https://bsd-hardware.info/?probe=576e8fb25d) | Dec 08, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | [97c632ed57](https://bsd-hardware.info/?probe=97c632ed57) | Nov 25, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2340... | [1618017f79](https://bsd-hardware.info/?probe=1618017f79) | Nov 17, 2025 |
| Apple         | MacBookPro6,2               | [70a14286fc](https://bsd-hardware.info/?probe=70a14286fc) | Nov 08, 2025 |
| Lenovo        | ThinkPad X220 4291ZFR       | [c7e13a8f2d](https://bsd-hardware.info/?probe=c7e13a8f2d) | Oct 31, 2025 |
| ASUSTek       | K53SJ                       | [092f586122](https://bsd-hardware.info/?probe=092f586122) | Oct 28, 2025 |
| ASUSTek       | K52JB                       | [831c17b144](https://bsd-hardware.info/?probe=831c17b144) | Oct 28, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [8921028708](https://bsd-hardware.info/?probe=8921028708) | Sep 27, 2025 |
| ASUSTek       | K53SJ                       | [7105ddca26](https://bsd-hardware.info/?probe=7105ddca26) | May 31, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [47d8451b23](https://bsd-hardware.info/?probe=47d8451b23) | May 21, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [5189ae5b2c](https://bsd-hardware.info/?probe=5189ae5b2c) | May 08, 2025 |
| ASUSTek       | K53SJ                       | [4fc246d3b4](https://bsd-hardware.info/?probe=4fc246d3b4) | May 01, 2025 |
| LG Electro... | 16Z90P-G.AP75D              | [c855a0ced2](https://bsd-hardware.info/?probe=c855a0ced2) | Apr 22, 2025 |
| ASUSTek       | K53SJ                       | [3a312f438d](https://bsd-hardware.info/?probe=3a312f438d) | Apr 18, 2025 |
| ASUSTek       | K53SJ                       | [1e240331e0](https://bsd-hardware.info/?probe=1e240331e0) | Apr 18, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [38343a4b77](https://bsd-hardware.info/?probe=38343a4b77) | Mar 27, 2025 |
| Apple         | MacBook5,1                  | [8c618c0e44](https://bsd-hardware.info/?probe=8c618c0e44) | Mar 09, 2025 |
| ASUSTek       | K55VD                       | [4672d15867](https://bsd-hardware.info/?probe=4672d15867) | Mar 04, 2025 |
| ASUSTek       | K55VD                       | [7eac5f9cf2](https://bsd-hardware.info/?probe=7eac5f9cf2) | Mar 02, 2025 |
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


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| helloSystem 0.8.1      | 16        | 14.16%  |
| helloSystem 0.7.0      | 13        | 11.5%   |
| helloSystem 0.9.0      | 5         | 4.42%   |
| helloSystem 0.5.0      | 5         | 4.42%   |
| helloSystem 0.4.0      | 5         | 4.42%   |
| helloSystem 0.8.0      | 4         | 3.54%   |
| helloSystem 0.6.0      | 3         | 2.65%   |
| NomadBSD 1.3.2         | 2         | 1.77%   |
| helloSystem 0.3.0      | 2         | 1.77%   |
| GhostBSD 21.08.27      | 2         | 1.77%   |
| GhostBSD 20.04.02      | 2         | 1.77%   |
| FreeBSD 13.1           | 2         | 1.77%   |
| OPNsense 25.4          | 1         | 0.88%   |
| OPNsense 23.7.9        | 1         | 0.88%   |
| OPNsense 23.10.3       | 1         | 0.88%   |
| OPNsense 22.1.9        | 1         | 0.88%   |
| OPNsense 22.1.6        | 1         | 0.88%   |
| OPNsense 21.7.7        | 1         | 0.88%   |
| OPNsense 21.1          | 1         | 0.88%   |
| OpenBSD 7.6            | 1         | 0.88%   |
| OpenBSD 7.5            | 1         | 0.88%   |
| OpenBSD 7.2            | 1         | 0.88%   |
| OpenBSD 7.1            | 1         | 0.88%   |
| OpenBSD 6.8            | 1         | 0.88%   |
| OpenBSD 6.7            | 1         | 0.88%   |
| NomadBSD 5806f915      | 1         | 0.88%   |
| NomadBSD 1.4           | 1         | 0.88%   |
| NomadBSD 1.3.1         | 1         | 0.88%   |
| NetBSD 9.2_STABLE      | 1         | 0.88%   |
| NetBSD 9.2             | 1         | 0.88%   |
| NetBSD 9.1             | 1         | 0.88%   |
| NetBSD 9.0             | 1         | 0.88%   |
| NetBSD 10.99.1         | 1         | 0.88%   |
| NetBSD 10.1_STABLE     | 1         | 0.88%   |
| NetBSD 10.1            | 1         | 0.88%   |
| GhostBSD 25.01-R14.2p1 | 1         | 0.88%   |
| GhostBSD 23.10.1       | 1         | 0.88%   |
| GhostBSD 23.09.16      | 1         | 0.88%   |
| GhostBSD 23.06.05      | 1         | 0.88%   |
| GhostBSD 22.11.02      | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 48        | 47.06%  |
| FreeBSD     | 23        | 22.55%  |
| GhostBSD    | 8         | 7.84%   |
| OPNsense    | 7         | 6.86%   |
| OpenBSD     | 6         | 5.88%   |
| NomadBSD    | 5         | 4.9%    |
| NetBSD      | 5         | 4.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 98        | 98%     |
| i386  | 2         | 2%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 49        | 46.67%  |
| Console      | 10        | 9.52%   |
| XFCE         | 9         | 8.57%   |
| KDE5         | 7         | 6.67%   |
| Openbox      | 5         | 4.76%   |
| MATE         | 4         | 3.81%   |
| i3           | 4         | 3.81%   |
| TWM          | 3         | 2.86%   |
| fvwm         | 3         | 2.86%   |
| ctwm         | 3         | 2.86%   |
| Cinnamon     | 3         | 2.86%   |
| mango        | 1         | 0.95%   |
| LXQt         | 1         | 0.95%   |
| KDE          | 1         | 0.95%   |
| IceWM        | 1         | 0.95%   |
| Fluxbox      | 1         | 0.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 91        | 91%     |
| Console | 7         | 7%      |
| Wayland | 2         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 55        | 54.46%  |
| Console | 25        | 24.75%  |
| SDDM    | 9         | 8.91%   |
| LightDM | 9         | 8.91%   |
| XDM     | 1         | 0.99%   |
| Ly      | 1         | 0.99%   |
| GDM     | 1         | 0.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_US            | 41        | 39.42%  |
| it_IT            | 25        | 24.04%  |
| Unknown          | 16        | 15.38%  |
| C                | 13        | 12.5%   |
| it               | 2         | 1.92%   |
| ru_RU            | 1         | 0.96%   |
| LANG="en_US"     | 1         | 0.96%   |
| it_IT.ISO8859-15 | 1         | 0.96%   |
| it_IT.ISO8859-1  | 1         | 0.96%   |
| fr_FR            | 1         | 0.96%   |
| en_GB            | 1         | 0.96%   |
| en               | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 86%     |
| BIOS | 14        | 14%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 53        | 51.96%  |
| Ufs    | 22        | 21.57%  |
| Cd9660 | 21        | 20.59%  |
| Ffs    | 6         | 5.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 90        | 90%     |
| MBR     | 7         | 7%      |
| Unknown | 3         | 3%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 26%     |
| ASUSTek Computer    | 20        | 20%     |
| Dell                | 10        | 10%     |
| Hewlett-Packard     | 7         | 7%      |
| Acer                | 7         | 7%      |
| Apple               | 6         | 6%      |
| Toshiba             | 3         | 3%      |
| Samsung Electronics | 3         | 3%      |
| Deciso              | 3         | 3%      |
| Unknown             | 3         | 3%      |
| LG Electronics      | 2         | 2%      |
| eMachines           | 2         | 2%      |
| TUXEDO              | 1         | 1%      |
| TULPAR              | 1         | 1%      |
| Packard Bell        | 1         | 1%      |
| MSI                 | 1         | 1%      |
| Intel               | 1         | 1%      |
| IBM                 | 1         | 1%      |
| HUAWEI              | 1         | 1%      |
| Chuwi               | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 4         | 4%      |
| Dell Latitude E7250                          | 3         | 3%      |
| HP Laptop 15-da0xxx                          | 2         | 2%      |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA       | 2         | 2%      |
| Apple MacBook4,1                             | 2         | 2%      |
| TUXEDO N14xWU                                | 1         | 1%      |
| TULPAR A5 V20.3                              | 1         | 1%      |
| Toshiba Satellite C855-1U4                   | 1         | 1%      |
| Toshiba PORTEGE M780                         | 1         | 1%      |
| Samsung R510/P510                            | 1         | 1%      |
| Samsung N150P/N210P/N220P                    | 1         | 1%      |
| Samsung 3570R/370R/470R/450R/510R/4450RV     | 1         | 1%      |
| Packard Bell EasyNote_MX61-B-038             | 1         | 1%      |
| MSI GF65 Thin 10SER                          | 1         | 1%      |
| LG COLUMBIA                                  | 1         | 1%      |
| LG 16Z90P-G.AP75D                            | 1         | 1%      |
| Lenovo ThinkPad X280 20KES5M300              | 1         | 1%      |
| Lenovo ThinkPad X270 20HN0015MX              | 1         | 1%      |
| Lenovo ThinkPad X260 20F5S82N00              | 1         | 1%      |
| Lenovo ThinkPad X250 20CMS0FA00              | 1         | 1%      |
| Lenovo ThinkPad X240 20AMS0J01N              | 1         | 1%      |
| Lenovo ThinkPad X220 4291ZFR                 | 1         | 1%      |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1%      |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00     | 1         | 1%      |
| Lenovo ThinkPad W530 2447GW3                 | 1         | 1%      |
| Lenovo ThinkPad T495 20NJS0KP00              | 1         | 1%      |
| Lenovo ThinkPad T480s 20L8S2340E             | 1         | 1%      |
| Lenovo ThinkPad T460s 20FAS3L002             | 1         | 1%      |
| Lenovo ThinkPad T450 20BUS06B00              | 1         | 1%      |
| Lenovo ThinkPad T440p                        | 1         | 1%      |
| Lenovo ThinkPad T440 20B7S1C600              | 1         | 1%      |
| Lenovo ThinkPad T430 23501B3                 | 1         | 1%      |
| Lenovo ThinkPad T420 4236BD5                 | 1         | 1%      |
| Lenovo ThinkPad T410 2537B94                 | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 2i 20W0003LUS        | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 1 20S1S4K500         | 1         | 1%      |
| Lenovo ThinkPad L530 24812TG                 | 1         | 1%      |
| Lenovo ThinkBook 16 G6 IRL 21KH              | 1         | 1%      |
| Lenovo IdeaPad 3 15ADA05 81W1                | 1         | 1%      |
| Lenovo G505 20240                            | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 21        | 21%     |
| Dell Latitude         | 6         | 6%      |
| Unknown               | 4         | 4%      |
| ASUS VivoBook         | 3         | 3%      |
| Acer Aspire           | 3         | 3%      |
| HP Laptop             | 2         | 2%      |
| HP EliteBook          | 2         | 2%      |
| Apple MacBook4        | 2         | 2%      |
| TUXEDO N14xWU         | 1         | 1%      |
| TULPAR A5             | 1         | 1%      |
| Toshiba Satellite     | 1         | 1%      |
| Toshiba PORTEGE       | 1         | 1%      |
| Samsung R510          | 1         | 1%      |
| Samsung N150P         | 1         | 1%      |
| Samsung 3570R         | 1         | 1%      |
| Packard Bell EasyNote | 1         | 1%      |
| MSI GF65              | 1         | 1%      |
| LG COLUMBIA           | 1         | 1%      |
| LG 16Z90P-G.AP75D     | 1         | 1%      |
| Lenovo ThinkBook      | 1         | 1%      |
| Lenovo IdeaPad        | 1         | 1%      |
| Lenovo G505           | 1         | 1%      |
| Lenovo G50-45         | 1         | 1%      |
| Lenovo B590           | 1         | 1%      |
| Intel S1200RP         | 1         | 1%      |
| IBM ThinkPad          | 1         | 1%      |
| HUAWEI BOHK-WAX9X     | 1         | 1%      |
| HP ProBook            | 1         | 1%      |
| HP Pavilion           | 1         | 1%      |
| HP Mini               | 1         | 1%      |
| eMachines eME732ZG    | 1         | 1%      |
| eMachines eME728      | 1         | 1%      |
| Dell XPS              | 1         | 1%      |
| Dell Vostro           | 1         | 1%      |
| Dell Precision        | 1         | 1%      |
| Dell Inspiron         | 1         | 1%      |
| Deciso OPNsense       | 1         | 1%      |
| Deciso NetBoard-A20   | 1         | 1%      |
| Deciso NetBoard-A10   | 1         | 1%      |
| Chuwi GemiBook        | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 12        | 12%     |
| 2010 | 10        | 10%     |
| 2019 | 9         | 9%      |
| 2020 | 8         | 8%      |
| 2011 | 8         | 8%      |
| 2022 | 6         | 6%      |
| 2008 | 6         | 6%      |
| 2021 | 5         | 5%      |
| 2018 | 5         | 5%      |
| 2016 | 5         | 5%      |
| 2015 | 5         | 5%      |
| 2014 | 5         | 5%      |
| 2012 | 4         | 4%      |
| 2009 | 3         | 3%      |
| 2023 | 2         | 2%      |
| 2017 | 2         | 2%      |
| 2007 | 2         | 2%      |
| 2025 | 1         | 1%      |
| 2024 | 1         | 1%      |
| 2005 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 100       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 99%     |
| Yes  | 1         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 43        | 42.57%  |
| 4.01-8.0   | 27        | 26.73%  |
| 16.01-24.0 | 14        | 13.86%  |
| 2.01-3.0   | 7         | 6.93%   |
| 32.01-64.0 | 5         | 4.95%   |
| 3.01-4.0   | 3         | 2.97%   |
| 24.01-32.0 | 1         | 0.99%   |
| 0.01-0.5   | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 61        | 60.4%   |
| 0.51-1.0  | 21        | 20.79%  |
| 1.01-2.0  | 7         | 6.93%   |
| Unknown   | 5         | 4.95%   |
| 2.01-3.0  | 4         | 3.96%   |
| 4.01-8.0  | 2         | 1.98%   |
| 8.01-16.0 | 1         | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 69.31%  |
| 2      | 19        | 18.81%  |
| 0      | 12        | 11.88%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 64.71%  |
| Yes       | 36        | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 87%     |
| No        | 13        | 13%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 92%     |
| No        | 8         | 8%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 63.73%  |
| No        | 37        | 36.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 100       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Milan                    | 15        | 13.04%  |
| Rome                     | 14        | 12.17%  |
| Turin                    | 5         | 4.35%   |
| Bologna                  | 5         | 4.35%   |
| Brescia                  | 4         | 3.48%   |
| Padova                   | 3         | 2.61%   |
| Trieste                  | 2         | 1.74%   |
| Sesto San Giovanni       | 2         | 1.74%   |
| Rho                      | 2         | 1.74%   |
| Naples                   | 2         | 1.74%   |
| Monterotondo             | 2         | 1.74%   |
| Como                     | 2         | 1.74%   |
| Villalfonsina            | 1         | 0.87%   |
| Vigonza                  | 1         | 0.87%   |
| Vigonovo                 | 1         | 0.87%   |
| Udine                    | 1         | 0.87%   |
| Treviso                  | 1         | 0.87%   |
| Solarino                 | 1         | 0.87%   |
| Settimo Milanese         | 1         | 0.87%   |
| Sasso Marconi            | 1         | 0.87%   |
| Sassari                  | 1         | 0.87%   |
| Saronno                  | 1         | 0.87%   |
| Roncade                  | 1         | 0.87%   |
| Resana                   | 1         | 0.87%   |
| Prad am Stilfser Joch    | 1         | 0.87%   |
| Poggio Renatico          | 1         | 0.87%   |
| Piovene Rocchette        | 1         | 0.87%   |
| Pessano Con Bornago      | 1         | 0.87%   |
| Passignano sul Trasimeno | 1         | 0.87%   |
| Palermo                  | 1         | 0.87%   |
| Nughedu San Nicolo       | 1         | 0.87%   |
| Naturns                  | 1         | 0.87%   |
| Monza                    | 1         | 0.87%   |
| Milano                   | 1         | 0.87%   |
| Massa Lombarda           | 1         | 0.87%   |
| Malnate                  | 1         | 0.87%   |
| Macerata                 | 1         | 0.87%   |
| Lurago Marinone          | 1         | 0.87%   |
| Lissone                  | 1         | 0.87%   |
| Latina                   | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 27     | 17.48%  |
| WDC                 | 10        | 15     | 9.71%   |
| Seagate             | 10        | 13     | 9.71%   |
| Kingston            | 9         | 11     | 8.74%   |
| Crucial             | 8         | 13     | 7.77%   |
| Toshiba             | 7         | 7      | 6.8%    |
| SanDisk             | 5         | 5      | 4.85%   |
| Intel               | 4         | 4      | 3.88%   |
| Hitachi             | 4         | 5      | 3.88%   |
| Transcend           | 3         | 3      | 2.91%   |
| SPCC                | 2         | 3      | 1.94%   |
| Micron Technology   | 2         | 2      | 1.94%   |
| Leven               | 2         | 2      | 1.94%   |
| KingSpec            | 2         | 2      | 1.94%   |
| HGST                | 2         | 3      | 1.94%   |
| FORESEE             | 2         | 3      | 1.94%   |
| Apple               | 2         | 2      | 1.94%   |
| Union Memory        | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 1      | 0.97%   |
| Silicon             | 1         | 1      | 0.97%   |
| PNY                 | 1         | 1      | 0.97%   |
| Netac               | 1         | 1      | 0.97%   |
| Lexar               | 1         | 1      | 0.97%   |
| KingDian            | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| Indilinx            | 1         | 1      | 0.97%   |
| Fujitsu             | 1         | 1      | 0.97%   |
| ASUSTek Computer    | 1         | 2      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                       | 4         | 3.7%    |
| Samsung SSD 860 EVO 250GB                       | 3         | 2.78%   |
| Kingston SA400S37240G 240GB                     | 3         | 2.78%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 1.85%   |
| SPCC Solid State Disk 256GB                     | 2         | 1.85%   |
| Samsung SSD 850 EVO 500GB                       | 2         | 1.85%   |
| KingSpec Q-720 720GB                            | 2         | 1.85%   |
| Intel SSDSC2BF180A4L 180GB                      | 2         | 1.85%   |
| WDC WDS500G2B0A-00SM50 500GB                    | 1         | 0.93%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 0.93%   |
| WDC WDS100T1X0E-00AFY0 1TB                      | 1         | 0.93%   |
| WDC WD5000BPVT-80HXZT1 500GB                    | 1         | 0.93%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 0.93%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 0.93%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 0.93%   |
| WDC WD2500BEVT-22ZCT0 250GB                     | 1         | 0.93%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 0.93%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 0.93%   |
| Transcend TS256GMTE710T 256GB                   | 1         | 0.93%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 0.93%   |
| Transcend TS120GMTS420S 120GB                   | 1         | 0.93%   |
| Toshiba TR200 240GB                             | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                          | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 0.93%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 0.93%   |
| Toshiba MK5065GSX 500GB                         | 1         | 0.93%   |
| Toshiba MK2561GSYN 250GB                        | 1         | 0.93%   |
| SPCC Solid State Disk 128GB                     | 1         | 0.93%   |
| SK hynix SC210 mSATA 256GB                      | 1         | 0.93%   |
| Silicon SATA3 120GB SSD                         | 1         | 0.93%   |
| Seagate ST9750420AS 752GB                       | 1         | 0.93%   |
| Seagate ST9320320AS 320GB                       | 1         | 0.93%   |
| Seagate ST9160821AS 160GB                       | 1         | 0.93%   |
| Seagate ST9160411AS 160GB                       | 1         | 0.93%   |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 0.93%   |
| Seagate ST500LT012-9WS142 500GB                 | 1         | 0.93%   |
| Seagate ST500LM030-1RK17D 500GB                 | 1         | 0.93%   |
| Seagate ST250LM000 HM251HI 250GB                | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                  | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 34.48%  |
| Toshiba             | 6         | 6      | 20.69%  |
| WDC                 | 5         | 8      | 17.24%  |
| Hitachi             | 4         | 5      | 13.79%  |
| HGST                | 2         | 3      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 22     | 22.58%  |
| Crucial             | 8         | 13     | 12.9%   |
| Kingston            | 6         | 7      | 9.68%   |
| SanDisk             | 5         | 5      | 8.06%   |
| WDC                 | 4         | 6      | 6.45%   |
| Intel               | 3         | 3      | 4.84%   |
| SPCC                | 2         | 3      | 3.23%   |
| Leven               | 2         | 2      | 3.23%   |
| KingSpec            | 2         | 2      | 3.23%   |
| FORESEE             | 2         | 3      | 3.23%   |
| Apple               | 2         | 2      | 3.23%   |
| Transcend           | 1         | 1      | 1.61%   |
| Toshiba             | 1         | 1      | 1.61%   |
| SK hynix            | 1         | 1      | 1.61%   |
| Silicon             | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| Lexar               | 1         | 1      | 1.61%   |
| KingDian            | 1         | 1      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| Indilinx            | 1         | 1      | 1.61%   |
| ASUSTek Computer    | 1         | 2      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 56        | 81     | 57.73%  |
| HDD  | 28        | 37     | 28.87%  |
| NVMe | 13        | 14     | 13.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 118    | 85.71%  |
| NVMe | 13        | 14     | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 93     | 81.71%  |
| 0.51-1.0   | 15        | 25     | 18.29%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 42        | 40.78%  |
| 101-250    | 29        | 28.16%  |
| 251-500    | 12        | 11.65%  |
| 21-50      | 7         | 6.8%    |
| 51-100     | 7         | 6.8%    |
| 501-1000   | 6         | 5.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 91        | 86.67%  |
| 21-50   | 10        | 9.52%   |
| 51-100  | 3         | 2.86%   |
| 101-250 | 1         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2BF180A4L 180GB            | 2         | 2      | 9.52%   |
| WDC WD2500BEVT-22ZCT0 250GB           | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 4.76%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 4.76%   |
| SK hynix SC210 mSATA 256GB            | 1         | 1      | 4.76%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 4.76%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 4.76%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1         | 1      | 4.76%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 4.76%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 4.76%   |
| SanDisk SDSSDP064G 64GB               | 1         | 1      | 4.76%   |
| SanDisk SD9SN8W-128G-1006 128GB       | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 4.76%   |
| Netac SSD 256GB                       | 1         | 1      | 4.76%   |
| Hitachi HTS548040M9AT00 37GB          | 1         | 2      | 4.76%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 4.76%   |
| Crucial CT750MX300SSD1 752GB          | 1         | 1      | 4.76%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 3      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 19.05%  |
| Toshiba             | 3         | 3      | 14.29%  |
| SanDisk             | 3         | 3      | 14.29%  |
| Intel               | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 3      | 9.52%   |
| Crucial             | 2         | 4      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| HGST                | 1         | 2      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 36.36%  |
| Toshiba | 3         | 3      | 27.27%  |
| Hitachi | 2         | 3      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 13     | 52.38%  |
| SSD  | 10        | 12     | 47.62%  |

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
| Works    | 69        | 104    | 75%     |
| Malfunc  | 21        | 25     | 22.83%  |
| Detected | 2         | 3      | 2.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 71        | 66.98%  |
| AMD                              | 9         | 8.49%   |
| Samsung Electronics              | 8         | 7.55%   |
| Transcend                        | 3         | 2.83%   |
| SanDisk                          | 3         | 2.83%   |
| Kingston Technology Company      | 3         | 2.83%   |
| Nvidia                           | 2         | 1.89%   |
| Micron Technology                | 2         | 1.89%   |
| Union Memory (Shenzhen)          | 1         | 0.94%   |
| SK hynix                         | 1         | 0.94%   |
| Silicon Integrated Systems [SiS] | 1         | 0.94%   |
| Phison Electronics               | 1         | 0.94%   |
| JMicron Technology               | 1         | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 7.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 7.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 6.78%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 5.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 5.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 4.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 4.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 4.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 4.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 4.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 2.54%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                      | 2         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.69%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.85%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 1         | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.85%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.85%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 1         | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1         | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.85%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.85%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 0.85%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.85%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.85%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 1         | 0.85%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 0.85%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 0.85%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 1         | 0.85%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD [E8]                            | 1         | 0.85%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.85%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 0.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.85%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 66.96%  |
| NVMe | 22        | 19.64%  |
| IDE  | 12        | 10.71%  |
| RAID | 3         | 2.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 86%     |
| AMD    | 14        | 14%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 3.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 3.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 2.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.97%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 2.97%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.97%   |
| Intel CPU Version                             | 2         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.98%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.98%   |
| AMD Ryzen Embedded V1500B                     | 2         | 1.98%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.99%   |
| Intel Pentium M processor                     | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.99%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.99%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 0.99%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.99%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.99%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 1         | 0.99%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.99%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.99%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.99%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.99%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.99%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 28.71%  |
| Intel Core i7           | 16        | 15.84%  |
| Other                   | 9         | 8.91%   |
| Intel Core 2 Duo        | 8         | 7.92%   |
| Intel Atom              | 6         | 5.94%   |
| Intel Core i3           | 5         | 4.95%   |
| Intel Celeron           | 5         | 4.95%   |
| Intel Pentium           | 4         | 3.96%   |
| AMD Ryzen 5             | 4         | 3.96%   |
| Intel Pentium Dual-Core | 2         | 1.98%   |
| AMD Ryzen Embedded      | 2         | 1.98%   |
| Intel Xeon              | 1         | 0.99%   |
| Intel Pentium M         | 1         | 0.99%   |
| Intel Core 2            | 1         | 0.99%   |
| Intel 686-class         | 1         | 0.99%   |
| AMD Turion 64 X2 Mobile | 1         | 0.99%   |
| AMD Ryzen 7 PRO         | 1         | 0.99%   |
| AMD EPYC                | 1         | 0.99%   |
| AMD E1                  | 1         | 0.99%   |
| AMD E                   | 1         | 0.99%   |
| AMD A6                  | 1         | 0.99%   |
| AMD A4                  | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 55        | 54.46%  |
| 4       | 20        | 19.8%   |
| Unknown | 13        | 12.87%  |
| 8       | 6         | 5.94%   |
| 1       | 3         | 2.97%   |
| 12      | 2         | 1.98%   |
| 16      | 1         | 0.99%   |
| 10      | 1         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 94        | 93.07%  |
| 2       | 4         | 3.96%   |
| Unknown | 3         | 2.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 59        | 58.42%  |
| 1       | 29        | 28.71%  |
| Unknown | 13        | 12.87%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 12        | 11.88%  |
| Broadwell   | 11        | 10.89%  |
| SandyBridge | 10        | 9.9%    |
| KabyLake    | 8         | 7.92%   |
| Unknown     | 8         | 7.92%   |
| IvyBridge   | 7         | 6.93%   |
| Haswell     | 7         | 6.93%   |
| Westmere    | 6         | 5.94%   |
| Bonnell     | 6         | 5.94%   |
| Skylake     | 5         | 4.95%   |
| Zen+        | 4         | 3.96%   |
| Zen         | 4         | 3.96%   |
| TigerLake   | 2         | 1.98%   |
| Silvermont  | 2         | 1.98%   |
| Jaguar      | 2         | 1.98%   |
| Puma        | 1         | 0.99%   |
| P6          | 1         | 0.99%   |
| Nehalem     | 1         | 0.99%   |
| K8 Hammer   | 1         | 0.99%   |
| Core        | 1         | 0.99%   |
| CometLake   | 1         | 0.99%   |
| Bobcat      | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 73        | 63.48%  |
| Nvidia                     | 22        | 19.13%  |
| AMD                        | 19        | 16.52%  |
| Matrox Electronics Systems | 1         | 0.87%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U GT2 [HD Graphics 5500]                                  | 10        | 8.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 8.4%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 5         | 4.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 5         | 4.2%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.2%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 4         | 3.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 3.36%   |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 3.36%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 3         | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 2.52%   |
| Nvidia GT216M [GeForce GT 330M]                                           | 2         | 1.68%   |
| Nvidia GM107M [GeForce GTX 850M]                                          | 2         | 1.68%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.68%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]          | 2         | 1.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.84%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.84%   |
| Nvidia GT218M [ION 2]                                                     | 1         | 0.84%   |
| Nvidia GM108M [GeForce MX130]                                             | 1         | 0.84%   |
| Nvidia GM108M [GeForce 930MX]                                             | 1         | 0.84%   |
| Nvidia GK107M [GeForce GT 750M]                                           | 1         | 0.84%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.84%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.84%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 0.84%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.84%   |
| Nvidia G86M [Quadro NVS 140M]                                             | 1         | 0.84%   |
| Nvidia G86M [GeForce 8600M GS]                                            | 1         | 0.84%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 0.84%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.84%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 1         | 0.84%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)         | 1         | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.84%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 1         | 0.84%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 1         | 0.84%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 1         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 45        | 45%     |
| 1 x AMD                | 15        | 15%     |
| Intel + Nvidia         | 14        | 14%     |
| 2 x Intel              | 11        | 11%     |
| 1 x Nvidia             | 7         | 7%      |
| Other                  | 3         | 3%      |
| Intel + AMD            | 2         | 2%      |
| 2 x Intel + 1 x Nvidia | 1         | 1%      |
| 2 x AMD                | 1         | 1%      |
| AMD + Matrox           | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 86        | 84.31%  |
| Proprietary | 9         | 8.82%   |
| Unknown     | 7         | 6.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 82%     |
| 0.01-0.5   | 10        | 10%     |
| 1.01-2.0   | 5         | 5%      |
| 5.01-6.0   | 1         | 1%      |
| 3.01-4.0   | 1         | 1%      |
| 0.51-1.0   | 1         | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 27.14%  |
| LG Display              | 14        | 20%     |
| Chimei Innolux          | 9         | 12.86%  |
| BOE                     | 9         | 12.86%  |
| Samsung Electronics     | 5         | 7.14%   |
| HannStar                | 3         | 4.29%   |
| Lenovo                  | 2         | 2.86%   |
| Apple                   | 2         | 2.86%   |
| ___                     | 1         | 1.43%   |
| LPL                     | 1         | 1.43%   |
| LG Philips              | 1         | 1.43%   |
| HKC                     | 1         | 1.43%   |
| Hewlett-Packard         | 1         | 1.43%   |
| Fujitsu Siemens         | 1         | 1.43%   |
| Chi Mei Optoelectronics | 1         | 1.43%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 3         | 4.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 4.29%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch         | 2         | 2.86%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 340x190mm 15.3-inch | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 1.43%   |
| LPL LCD Monitor 1680x1050                                             | 1         | 1.43%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD0694 2560x1600 340x220mm 15.9-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 1.43%   |
| LG Display LCD Monitor LGD045D 1366x768 350x190mm 15.7-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD045C 1366x768 340x190mm 15.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD038E 1366x768 340x190mm 15.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.43%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 1.43%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch              | 1         | 1.43%   |
| HKC LCD Monitor 24E6C 1920x1080                                       | 1         | 1.43%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch            | 1         | 1.43%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch              | 1         | 1.43%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN160F 1920x1200 340x220mm 15.9-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch      | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 33        | 47.83%  |
| 1920x1080 (FHD)    | 21        | 30.43%  |
| 1024x600           | 4         | 5.8%    |
| 1280x800 (WXGA)    | 3         | 4.35%   |
| 1600x900 (HD+)     | 2         | 2.9%    |
| 3840x2400          | 1         | 1.45%   |
| 2560x1600          | 1         | 1.45%   |
| 2160x1440          | 1         | 1.45%   |
| 1920x1200 (WUXGA)  | 1         | 1.45%   |
| 1680x1050 (WSXGA+) | 1         | 1.45%   |
| 1440x900 (WXGA+)   | 1         | 1.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 50%     |
| 13      | 13        | 18.57%  |
| 12      | 9         | 12.86%  |
| 10      | 4         | 5.71%   |
| Unknown | 3         | 4.29%   |
| 17      | 2         | 2.86%   |
| 24      | 1         | 1.43%   |
| 23      | 1         | 1.43%   |
| 14      | 1         | 1.43%   |
| 11      | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 65.71%  |
| 201-300     | 17        | 24.29%  |
| Unknown     | 3         | 4.29%   |
| 501-600     | 2         | 2.86%   |
| 351-400     | 2         | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 56        | 83.58%  |
| 16/10   | 6         | 8.96%   |
| 3/2     | 3         | 4.48%   |
| Unknown | 2         | 2.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 23        | 32.86%  |
| 81-90          | 13        | 18.57%  |
| 101-110        | 10        | 14.29%  |
| 61-70          | 9         | 12.86%  |
| 41-50          | 4         | 5.71%   |
| 111-120        | 3         | 4.29%   |
| Unknown        | 3         | 4.29%   |
| 201-250        | 2         | 2.86%   |
| 121-130        | 2         | 2.86%   |
| 51-60          | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 37.14%  |
| 101-120       | 25        | 35.71%  |
| 51-100        | 11        | 15.71%  |
| 161-240       | 4         | 5.71%   |
| Unknown       | 3         | 4.29%   |
| More than 240 | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 76        | 74.51%  |
| 0     | 23        | 22.55%  |
| 2     | 3         | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 52        | 32.91%  |
| Qualcomm Atheros                 | 32        | 20.25%  |
| Realtek Semiconductor            | 28        | 17.72%  |
| Broadcom                         | 18        | 11.39%  |
| Marvell Technology Group         | 4         | 2.53%   |
| AMD                              | 3         | 1.9%    |
| Samsung Electronics              | 2         | 1.27%   |
| Ralink Technology                | 2         | 1.27%   |
| JMicron Technology               | 2         | 1.27%   |
| Huawei Technologies              | 2         | 1.27%   |
| Xiaomi                           | 1         | 0.63%   |
| T & A Mobile Phones              | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| OPPO Electronics                 | 1         | 0.63%   |
| Nvidia                           | 1         | 0.63%   |
| NetGear                          | 1         | 0.63%   |
| Motorola PCS                     | 1         | 0.63%   |
| MediaTek                         | 1         | 0.63%   |
| Lenovo                           | 1         | 0.63%   |
| Hewlett-Packard                  | 1         | 0.63%   |
| Edimax Technology                | 1         | 0.63%   |
| Dell                             | 1         | 0.63%   |
| BUFFALO                          | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 22        | 10.89%  |
| Intel Wireless 7265                                                     | 9         | 4.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.47%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.97%   |
| Intel Ethernet Connection (3) I218-LM                                   | 6         | 2.97%   |
| Intel Wireless 8260                                                     | 4         | 1.98%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 3         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.49%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.49%   |
| AMD XGMAC 10GbE Controller                                              | 3         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.99%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 0.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.99%   |
| Intel Wireless 7260                                                     | 2         | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.99%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.99%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 0.99%   |
| Intel 82574L Gigabit Network Connection                                 | 2         | 0.99%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.99%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.99%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.5%    |
| T & A Mobile Phones ALCATEL RNDIS Interface                             | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 40.59%  |
| Qualcomm Atheros      | 30        | 29.7%   |
| Broadcom              | 15        | 14.85%  |
| Realtek Semiconductor | 8         | 7.92%   |
| Ralink Technology     | 2         | 1.98%   |
| NetGear               | 1         | 0.99%   |
| MediaTek              | 1         | 0.99%   |
| Edimax Technology     | 1         | 0.99%   |
| Dell                  | 1         | 0.99%   |
| BUFFALO               | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 9         | 8.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 7.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 6.86%   |
| Intel Wireless 8265 / 8275                                              | 7         | 6.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 5.88%   |
| Intel Wireless 8260                                                     | 4         | 3.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.96%   |
| Intel Wireless 7260                                                     | 2         | 1.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 1.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 1.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.96%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.98%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.98%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.98%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.98%   |
| Intel WiFi Link 5100                                                    | 1         | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.98%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.98%   |
| Intel Jasper Lake PCH CNVi WiFi                                         | 1         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 36        | 37.5%   |
| Realtek Semiconductor            | 26        | 27.08%  |
| Qualcomm Atheros                 | 11        | 11.46%  |
| Broadcom                         | 5         | 5.21%   |
| Marvell Technology Group         | 4         | 4.17%   |
| AMD                              | 3         | 3.13%   |
| Samsung Electronics              | 2         | 2.08%   |
| JMicron Technology               | 2         | 2.08%   |
| Xiaomi                           | 1         | 1.04%   |
| T & A Mobile Phones              | 1         | 1.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.04%   |
| OPPO Electronics                 | 1         | 1.04%   |
| Nvidia                           | 1         | 1.04%   |
| Motorola PCS                     | 1         | 1.04%   |
| Lenovo                           | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 22        | 22.92%  |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 6.25%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 3.13%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 3.13%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 3.13%   |
| AMD XGMAC 10GbE Controller                                             | 3         | 3.13%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 2.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 2.08%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 2.08%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 2.08%   |
| Intel 82574L Gigabit Network Connection                                | 2         | 2.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.04%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                            | 1         | 1.04%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.04%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 1.04%   |
| OPPO OPPO Find X3 Neo 5G RNDIS Control RNDIS Ethernet Data             | 1         | 1.04%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.04%   |
| Motorola PCS USB RNDIS Device                                          | 1         | 1.04%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.04%   |
| Lenovo Lenovo Tab M10 Plus 3rd Gen RNDIS Control RNDIS Ethernet Data   | 1         | 1.04%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.04%   |
| Intel Ethernet Controller I226-V                                       | 1         | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.04%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.04%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.04%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 1.04%   |
| Intel Ethernet Connection (23) I219-V                                  | 1         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.04%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 50.27%  |
| Ethernet | 87        | 47.54%  |
| Modem    | 3         | 1.64%   |
| Unknown  | 1         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 65        | 56.52%  |
| Ethernet | 50        | 43.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 78        | 78%     |
| 1     | 15        | 15%     |
| 6     | 4         | 4%      |
| 5     | 2         | 2%      |
| 3     | 1         | 1%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 98%     |
| Yes  | 2         | 2%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 43.48%  |
| Broadcom                        | 7         | 10.14%  |
| Qualcomm Atheros Communications | 6         | 8.7%    |
| Apple                           | 5         | 7.25%   |
| Realtek Semiconductor           | 4         | 5.8%    |
| Lite-On Technology              | 4         | 5.8%    |
| IMC Networks                    | 4         | 5.8%    |
| Cambridge Silicon Radio         | 2         | 2.9%    |
| ASUSTek Computer                | 2         | 2.9%    |
| Toshiba                         | 1         | 1.45%   |
| Skylight Digital                | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |
| Dell                            | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 20        | 28.99%  |
| Intel AX201 Bluetooth                                       | 6         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.9%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.9%    |
| Intel AX210 Bluetooth                                       | 2         | 2.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.9%    |
| Apple Broadcom Built-in Bluetooth                           | 2         | 2.9%    |
| Apple Bluetooth Host Controller                             | 2         | 2.9%    |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.45%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 1.45%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.45%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.45%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.45%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.45%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.45%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.45%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.45%   |
| Intel AX211 Bluetooth                                       | 1         | 1.45%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.45%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.45%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS     | 1         | 1.45%   |
| IMC Networks Bluetooth module                               | 1         | 1.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.45%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.45%   |
| Dell Wireless 360 Bluetooth                                 | 1         | 1.45%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.45%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.45%   |
| Broadcom BCM2070 Bluetooth                                  | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.45%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.45%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.45%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 81        | 73.64%  |
| AMD                              | 18        | 16.36%  |
| Nvidia                           | 8         | 7.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.91%   |
| C-Media Electronics              | 1         | 0.91%   |
| Apogee Electronics               | 1         | 0.91%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 8.82%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 8.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 7.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.62%   |
| AMD Ryzen HD Audio Controller                                                                     | 8         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 5.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 4.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 3.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 3.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.21%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 2.21%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.21%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.47%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.47%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.74%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.74%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.74%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.74%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.74%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 26.79%  |
| SK hynix            | 22        | 19.64%  |
| Micron Technology   | 11        | 9.82%   |
| Unknown             | 10        | 8.93%   |
| Unknown             | 9         | 8.04%   |
| Kingston            | 8         | 7.14%   |
| Crucial             | 7         | 6.25%   |
| Transcend           | 4         | 3.57%   |
| Nanya Technology    | 3         | 2.68%   |
| Elpida              | 2         | 1.79%   |
| A-DATA Technology   | 2         | 1.79%   |
| Ramaxel Technology  | 1         | 0.89%   |
| Corsair             | 1         | 0.89%   |
| ASint Technology    | 1         | 0.89%   |
| 48spaces            | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 10        | 8.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 3.33%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 3         | 2.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 2.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 2         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.67%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 2         | 1.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 2         | 1.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.67%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3200MT/s        | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 2         | 1.67%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1333MT/s         | 2         | 1.67%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s       | 2         | 1.67%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 1.67%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 2         | 1.67%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                            | 1         | 0.83%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                  | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                   | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                        | 1         | 0.83%   |
| Unknown RAM Module 256MB SODIMM DDR                          | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.83%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s         | 1         | 0.83%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 0.83%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s         | 1         | 0.83%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s         | 1         | 0.83%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.83%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s       | 1         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s      | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 51.04%  |
| DDR4    | 23        | 23.96%  |
| DDR2    | 11        | 11.46%  |
| SDRAM   | 3         | 3.13%   |
| Unknown | 3         | 3.13%   |
| LPDDR4  | 2         | 2.08%   |
| DDR5    | 2         | 2.08%   |
| DDR     | 2         | 2.08%   |
| LPDDR3  | 1         | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 91.58%  |
| Row Of Chips | 5         | 5.26%   |
| Chip         | 3         | 3.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 41        | 38.68%  |
| 8192  | 26        | 24.53%  |
| 2048  | 24        | 22.64%  |
| 16384 | 8         | 7.55%   |
| 1024  | 4         | 3.77%   |
| 32768 | 2         | 1.89%   |
| 256   | 1         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 25.96%  |
| 3200    | 12        | 11.54%  |
| 667     | 11        | 10.58%  |
| 1333    | 9         | 8.65%   |
| 1067    | 8         | 7.69%   |
| 2667    | 7         | 6.73%   |
| 2400    | 6         | 5.77%   |
| 2133    | 4         | 3.85%   |
| 1334    | 4         | 3.85%   |
| 800     | 4         | 3.85%   |
| Unknown | 3         | 2.88%   |
| 1867    | 2         | 1.92%   |
| 5600    | 1         | 0.96%   |
| 4800    | 1         | 0.96%   |
| 4267    | 1         | 0.96%   |
| 2048    | 1         | 0.96%   |
| 1066    | 1         | 0.96%   |
| 975     | 1         | 0.96%   |
| 333     | 1         | 0.96%   |

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
| Chicony Electronics                    | 27        | 34.62%  |
| IMC Networks                           | 12        | 15.38%  |
| Realtek Semiconductor                  | 8         | 10.26%  |
| Sunplus Innovation Technology          | 7         | 8.97%   |
| Bison Electronics                      | 7         | 8.97%   |
| ALi                                    | 3         | 3.85%   |
| Z-Star Microelectronics                | 2         | 2.56%   |
| Silicon Motion                         | 2         | 2.56%   |
| Microdia                               | 2         | 2.56%   |
| Syntek                                 | 1         | 1.28%   |
| Suyin                                  | 1         | 1.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.28%   |
| Lite-On Technology                     | 1         | 1.28%   |
| Lenovo                                 | 1         | 1.28%   |
| Cubeternet                             | 1         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 6         | 7.69%   |
| Bison Integrated Camera                    | 4         | 5.13%   |
| Realtek Integrated_Webcam_HD               | 3         | 3.85%   |
| Realtek USB Camera                         | 2         | 2.56%   |
| Realtek Lenovo EasyCamera                  | 2         | 2.56%   |
| Microdia Integrated_Webcam_HD              | 2         | 2.56%   |
| IMC Networks UVC VGA Webcam                | 2         | 2.56%   |
| IMC Networks Realtek PC Camera             | 2         | 2.56%   |
| IMC Networks Integrated Webcam             | 2         | 2.56%   |
| IMC Networks Integrated Camera             | 2         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam              | 2         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)    | 2         | 2.56%   |
| Chicony HD WebCam (Asus N-series)          | 2         | 2.56%   |
| Chicony HD WebCam (Acer)                   | 2         | 2.56%   |
| ALi Gateway Webcam                         | 2         | 2.56%   |
| Z-Star Webcam                              | 1         | 1.28%   |
| Z-Star Vega USB 2.0 Camera                 | 1         | 1.28%   |
| Syntek EasyCamera                          | 1         | 1.28%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 1         | 1.28%   |
| Sunplus Laptop Integrated Webcam HD        | 1         | 1.28%   |
| Sunplus Integrated_Webcam_HD               | 1         | 1.28%   |
| Sunplus Integrated Camera                  | 1         | 1.28%   |
| Sunplus Hy HD Camera                       | 1         | 1.28%   |
| Sunplus Dell E5570 integrated webcam       | 1         | 1.28%   |
| Sunplus 1.3M HD WebCam                     | 1         | 1.28%   |
| Silicon Motion Realtek USB 2.0 PC Camera   | 1         | 1.28%   |
| Silicon Motion HP Webcam-50                | 1         | 1.28%   |
| Shenzhen Kingcome Optoelectronic HD Webcam | 1         | 1.28%   |
| Realtek USB2.0 VGA UVC WebCam              | 1         | 1.28%   |
| Lite-On HP TrueVision HD Camera            | 1         | 1.28%   |
| Lenovo Integrated Webcam [R5U877]          | 1         | 1.28%   |
| IMC Networks USB 2.0 UVC HD Webcam         | 1         | 1.28%   |
| IMC Networks Realtek DMFT RGB              | 1         | 1.28%   |
| IMC Networks ov9734_azurewave_camera       | 1         | 1.28%   |
| IMC Networks ASUS USB 2.0 UVC VGA WebCam   | 1         | 1.28%   |
| Cubeternet WebCam                          | 1         | 1.28%   |
| Chicony WebCam                             | 1         | 1.28%   |
| Chicony UVC 1.00 device HD UVC WebCam      | 1         | 1.28%   |
| Chicony Toshiba Integrated Webcam          | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 26.32%  |
| Validity Sensors           | 4         | 21.05%  |
| AuthenTec                  | 3         | 15.79%  |
| Upek                       | 2         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| STMicroelectronics         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |
| Broadcom                   | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 10.53%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 10.53%  |
| AuthenTec AES1600                                                            | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 5.26%   |
| Synaptics UWP WBDI Device                                                    | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.26%   |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.26%   |
| Elan Fingerprint Sensor                                                      | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| AuthenTec AES2810                                                            | 1         | 5.26%   |

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
| 2     | 33        | 31.43%  |
| 1     | 32        | 30.48%  |
| 0     | 19        | 18.1%   |
| 3     | 17        | 16.19%  |
| 4     | 4         | 3.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 40.13%  |
| Bluetooth                | 22        | 14.47%  |
| Net/wireless             | 20        | 13.16%  |
| Card reader              | 20        | 13.16%  |
| Fingerprint reader       | 18        | 11.84%  |
| Graphics card            | 3         | 1.97%   |
| Firewire controller      | 3         | 1.97%   |
| Storage                  | 2         | 1.32%   |
| Sound                    | 1         | 0.66%   |
| Network                  | 1         | 0.66%   |
| Modem                    | 1         | 0.66%   |

