NetBSD - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for NetBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NetBSD/Desktop/README.md) and [notebooks](/Dist/NetBSD/Notebook/README.md).

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

Total: 144

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [c70960854a](https://bsd-hardware.info/?probe=c70960854a) | May 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [23e113910f](https://bsd-hardware.info/?probe=23e113910f) | May 05, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [55560acf02](https://bsd-hardware.info/?probe=55560acf02) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B      | Soc         | [755a7a8614](https://bsd-hardware.info/?probe=755a7a8614) | Apr 28, 2024 |
| Lenovo        | 3743 NOK                    | Desktop     | [4b8389c575](https://bsd-hardware.info/?probe=4b8389c575) | Apr 27, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [47b751dfa0](https://bsd-hardware.info/?probe=47b751dfa0) | Apr 20, 2024 |
| Timi          | TM1612                      | Notebook    | [c139dfdf05](https://bsd-hardware.info/?probe=c139dfdf05) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Gigabyte      | B360M D2V                   | Desktop     | [766a437527](https://bsd-hardware.info/?probe=766a437527) | Apr 07, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3208fef860](https://bsd-hardware.info/?probe=3208fef860) | Apr 04, 2024 |
| Google        | Monroe                      | Desktop     | [7c9648d197](https://bsd-hardware.info/?probe=7c9648d197) | Apr 04, 2024 |
| Google        | Monroe                      | Desktop     | [383d7ee0f2](https://bsd-hardware.info/?probe=383d7ee0f2) | Apr 04, 2024 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [767ef499db](https://bsd-hardware.info/?probe=767ef499db) | Apr 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [3bcc4b4df3](https://bsd-hardware.info/?probe=3bcc4b4df3) | Mar 31, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | Notebook    | [5fa2016fc1](https://bsd-hardware.info/?probe=5fa2016fc1) | Mar 11, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [0dc4820d7e](https://bsd-hardware.info/?probe=0dc4820d7e) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [c3f8fdaebb](https://bsd-hardware.info/?probe=c3f8fdaebb) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [6c6fcc3427](https://bsd-hardware.info/?probe=6c6fcc3427) | Mar 04, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [b35f962bce](https://bsd-hardware.info/?probe=b35f962bce) | Mar 01, 2024 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [13c1963782](https://bsd-hardware.info/?probe=13c1963782) | Mar 01, 2024 |
| MSI           | KA790GX                     | Desktop     | [7b431178e5](https://bsd-hardware.info/?probe=7b431178e5) | Feb 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [5a03257c9a](https://bsd-hardware.info/?probe=5a03257c9a) | Feb 19, 2024 |
| Dell          | Precision 7520              | Notebook    | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2518A37       | Notebook    | [b2515cf7fb](https://bsd-hardware.info/?probe=b2515cf7fb) | Feb 19, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [9b41695cf4](https://bsd-hardware.info/?probe=9b41695cf4) | Jan 30, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [14e2e2c18c](https://bsd-hardware.info/?probe=14e2e2c18c) | Jan 16, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5d4fc3e285](https://bsd-hardware.info/?probe=5d4fc3e285) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c1c8f32b44](https://bsd-hardware.info/?probe=c1c8f32b44) | Dec 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [4ccf9a2566](https://bsd-hardware.info/?probe=4ccf9a2566) | Dec 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f3a2321558](https://bsd-hardware.info/?probe=f3a2321558) | Nov 29, 2023 |
| Google        | Kohaku                      | Notebook    | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | Notebook    | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [8b2811bcf5](https://bsd-hardware.info/?probe=8b2811bcf5) | Nov 14, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [424c33d278](https://bsd-hardware.info/?probe=424c33d278) | Oct 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [a88541d6a6](https://bsd-hardware.info/?probe=a88541d6a6) | Oct 27, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [753b30d88b](https://bsd-hardware.info/?probe=753b30d88b) | Oct 27, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [2beb3e34d8](https://bsd-hardware.info/?probe=2beb3e34d8) | Aug 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [a2119ba1fe](https://bsd-hardware.info/?probe=a2119ba1fe) | Jul 10, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Acer          | Revo RN86                   | Desktop     | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Samsung       | DP700A3D-A05UK SEC_SW_RE... | All in one  | [5718d8d05e](https://bsd-hardware.info/?probe=5718d8d05e) | Apr 24, 2023 |
| HP            | Pavilion 17                 | Notebook    | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ae1891a85](https://bsd-hardware.info/?probe=8ae1891a85) | Feb 16, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5921937764](https://bsd-hardware.info/?probe=5921937764) | Feb 06, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [5f6f4145d4](https://bsd-hardware.info/?probe=5f6f4145d4) | Feb 06, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| MiTAC         | 5033                        | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer          | Revo RN86                   | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP            | 3397                        | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Lenovo        | ThinkPad T420 4236D26       | Notebook    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | Notebook    | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310                 | Notebook    | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP            | System Board R3A            | Desktop     | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                     | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte      | P75-D3                      | Desktop     | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| Acer          | Revo RN86                   | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI           | KA790GX                     | Desktop     | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                     | Notebook    | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Unknown       | Unknown                     | Desktop     | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                         | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| NetBSD 9.3         | 17        | 14.41%  |
| NetBSD 9.2         | 13        | 11.02%  |
| NetBSD 9.1         | 11        | 9.32%   |
| NetBSD 10.0        | 10        | 8.47%   |
| NetBSD 9.0_STABLE  | 8         | 6.78%   |
| NetBSD 9.0         | 6         | 5.08%   |
| NetBSD 10.0_RC2    | 5         | 4.24%   |
| NetBSD 10.0_RC1    | 5         | 4.24%   |
| NetBSD 10.0_BETA   | 5         | 4.24%   |
| NetBSD 10.0_RC4    | 4         | 3.39%   |
| NetBSD 9.99.94     | 3         | 2.54%   |
| NetBSD 9.99.93     | 3         | 2.54%   |
| NetBSD 9.1_STABLE  | 3         | 2.54%   |
| NetBSD 10.0_RC5    | 3         | 2.54%   |
| NetBSD 9.99.77     | 2         | 1.69%   |
| NetBSD 9.3_STABLE  | 2         | 1.69%   |
| NetBSD 9.2_STABLE  | 2         | 1.69%   |
| NetBSD 10.0_RC3    | 2         | 1.69%   |
| NetBSD 9.99.85     | 1         | 0.85%   |
| NetBSD 9.99.81     | 1         | 0.85%   |
| NetBSD 9.99.74     | 1         | 0.85%   |
| NetBSD 9.99.71     | 1         | 0.85%   |
| NetBSD 9.99.61     | 1         | 0.85%   |
| NetBSD 9.99.23     | 1         | 0.85%   |
| NetBSD 9.99.107    | 1         | 0.85%   |
| NetBSD 8.99.51     | 1         | 0.85%   |
| NetBSD 8.2         | 1         | 0.85%   |
| NetBSD 7.2         | 1         | 0.85%   |
| NetBSD 10.99.7     | 1         | 0.85%   |
| NetBSD 10.99.10    | 1         | 0.85%   |
| NetBSD 10.99.1     | 1         | 0.85%   |
| NetBSD 10.0_STABLE | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 105       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 83        | 79.05%  |
| evbarm  | 11        | 10.48%  |
| i386    | 8         | 7.62%   |
| macppc  | 2         | 1.9%    |
| sparc64 | 1         | 0.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 40        | 37.38%  |
| XFCE         | 28        | 26.17%  |
| helloDesktop | 9         | 8.41%   |
| Fluxbox      | 5         | 4.67%   |
| CTWM         | 5         | 4.67%   |
| MATE         | 4         | 3.74%   |
| DWM          | 3         | 2.8%    |
| LXQt         | 2         | 1.87%   |
| iwm          | 2         | 1.87%   |
| Xfwm4        | 1         | 0.93%   |
| Window Maker | 1         | 0.93%   |
| sdorfehs     | 1         | 0.93%   |
| Ratpoison    | 1         | 0.93%   |
| PekWM        | 1         | 0.93%   |
| JWM          | 1         | 0.93%   |
| IceWM        | 1         | 0.93%   |
| GNOME        | 1         | 0.93%   |
| Awesome      | 1         | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 82        | 78.1%   |
| Console | 23        | 21.9%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 91        | 86.67%  |
| SLiM    | 7         | 6.67%   |
| XDM     | 4         | 3.81%   |
| GDM     | 2         | 1.9%    |
| LightDM | 1         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 74.55%  |
| en_US   | 17        | 15.45%  |
| ru_RU   | 3         | 2.73%   |
| fi_FI   | 2         | 1.82%   |
| C       | 2         | 1.82%   |
| hu_HU   | 1         | 0.91%   |
| fr_FR   | 1         | 0.91%   |
| es_MX   | 1         | 0.91%   |
| en_GB   | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 101       | 96.19%  |
| EFI  | 4         | 3.81%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 103       | 98.1%   |
| Cd9660  | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 71        | 67.62%  |
| Unknown | 34        | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 26        | 24.76%  |
| Lenovo                  | 15        | 14.29%  |
| Gigabyte Technology     | 9         | 8.57%   |
| ASUSTek Computer        | 9         | 8.57%   |
| Raspberry Pi Foundation | 6         | 5.71%   |
| Intel                   | 5         | 4.76%   |
| Dell                    | 5         | 4.76%   |
| ASRock                  | 5         | 4.76%   |
| Apple                   | 5         | 4.76%   |
| Hewlett-Packard         | 3         | 2.86%   |
| Acer                    | 3         | 2.86%   |
| Samsung Electronics     | 2         | 1.9%    |
| MSI                     | 2         | 1.9%    |
| Google                  | 2         | 1.9%    |
| Toshiba                 | 1         | 0.95%   |
| Timi                    | 1         | 0.95%   |
| Sony                    | 1         | 0.95%   |
| MiTAC                   | 1         | 0.95%   |
| KLLISRE                 | 1         | 0.95%   |
| IBM                     | 1         | 0.95%   |
| Fujitsu Siemens         | 1         | 0.95%   |
| eMachines               | 1         | 0.95%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 26        | 24.76%  |
| RPi Raspberry Pi                            | 3         | 2.86%   |
| RPi Raspberry Pi 4 Model B                  | 2         | 1.9%    |
| ASUS PRIME A320M-K                          | 2         | 1.9%    |
| Apple MacBookAir7,2                         | 2         | 1.9%    |
| Toshiba Satellite A100                      | 1         | 0.95%   |
| Timi TM1612                                 | 1         | 0.95%   |
| Sony SVF1421DSGW                            | 1         | 0.95%   |
| Samsung N150/N210/N220                      | 1         | 0.95%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 0.95%   |
| RPi Raspberry Pi 5 Model B                  | 1         | 0.95%   |
| MSI MS-7B86                                 | 1         | 0.95%   |
| MSI MS-7551                                 | 1         | 0.95%   |
| MiTAC 5033                                  | 1         | 0.95%   |
| Lenovo ThinkPad X260 20F60097US             | 1         | 0.95%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 0.95%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 0.95%   |
| Lenovo ThinkPad T490 20N3S4PX02             | 1         | 0.95%   |
| Lenovo ThinkPad T480s 20L8S45W00            | 1         | 0.95%   |
| Lenovo ThinkPad T470 20HES0EV0A             | 1         | 0.95%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 0.95%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 0.95%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 0.95%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 0.95%   |
| Lenovo ThinkPad T410 2518A37                | 1         | 0.95%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 0.95%   |
| Lenovo ThinkCentre M72e 3598CP8             | 1         | 0.95%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL | 1         | 0.95%   |
| Lenovo G500 20236                           | 1         | 0.95%   |
| KLLISRE X99-B5 V1.0                         | 1         | 0.95%   |
| Intel NUC7PJYH                              | 1         | 0.95%   |
| Intel NUC5PPYB H76558-102                   | 1         | 0.95%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 0.95%   |
| Intel Jasper Lake Client Platform           | 1         | 0.95%   |
| Intel DN2820FYK H24582-203                  | 1         | 0.95%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 0.95%   |
| HP Vectra                                   | 1         | 0.95%   |
| HP ProLiant DL360 G5                        | 1         | 0.95%   |
| HP Pavilion 17                              | 1         | 0.95%   |
| Google Monroe                               | 1         | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Unknown                  | 26        | 24.76%  |
| Lenovo ThinkPad          | 12        | 11.43%  |
| RPi Raspberry            | 6         | 5.71%   |
| Gigabyte X570            | 2         | 1.9%    |
| Dell Precision           | 2         | 1.9%    |
| ASUS TUF                 | 2         | 1.9%    |
| ASUS PRIME               | 2         | 1.9%    |
| ASRock 970               | 2         | 1.9%    |
| Apple MacBookAir7        | 2         | 1.9%    |
| Acer Aspire              | 2         | 1.9%    |
| Toshiba Satellite        | 1         | 0.95%   |
| Timi TM1612              | 1         | 0.95%   |
| Sony SVF1421DSGW         | 1         | 0.95%   |
| Samsung N150             | 1         | 0.95%   |
| Samsung DP700A3D         | 1         | 0.95%   |
| MSI MS-7B86              | 1         | 0.95%   |
| MSI MS-7551              | 1         | 0.95%   |
| MiTAC 5033               | 1         | 0.95%   |
| Lenovo ThinkCentre       | 1         | 0.95%   |
| Lenovo IdeaCentre        | 1         | 0.95%   |
| Lenovo G500              | 1         | 0.95%   |
| KLLISRE X99-B5           | 1         | 0.95%   |
| Intel NUC7PJYH           | 1         | 0.95%   |
| Intel NUC5PPYB           | 1         | 0.95%   |
| Intel NUC5i7RYB          | 1         | 0.95%   |
| Intel Jasper             | 1         | 0.95%   |
| Intel DN2820FYK          | 1         | 0.95%   |
| IBM ThinkPad             | 1         | 0.95%   |
| HP Vectra                | 1         | 0.95%   |
| HP ProLiant              | 1         | 0.95%   |
| HP Pavilion              | 1         | 0.95%   |
| Google Monroe            | 1         | 0.95%   |
| Google Kohaku            | 1         | 0.95%   |
| Gigabyte Z170X-Gaming    | 1         | 0.95%   |
| Gigabyte P75-D3          | 1         | 0.95%   |
| Gigabyte H61M-S2PV       | 1         | 0.95%   |
| Gigabyte GA-990FX-GAMING | 1         | 0.95%   |
| Gigabyte B360M-D2V       | 1         | 0.95%   |
| Gigabyte A320M-H         | 1         | 0.95%   |
| Gigabyte 970A-D3P        | 1         | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 25.71%  |
| 2020    | 10        | 9.52%   |
| 2018    | 9         | 8.57%   |
| 2013    | 8         | 7.62%   |
| 2022    | 6         | 5.71%   |
| 2016    | 6         | 5.71%   |
| 2010    | 5         | 4.76%   |
| 2021    | 4         | 3.81%   |
| 2019    | 4         | 3.81%   |
| 2017    | 4         | 3.81%   |
| 2014    | 4         | 3.81%   |
| 2015    | 3         | 2.86%   |
| 2011    | 3         | 2.86%   |
| 2007    | 3         | 2.86%   |
| 2005    | 3         | 2.86%   |
| 2024    | 2         | 1.9%    |
| 2012    | 2         | 1.9%    |
| 2023    | 1         | 0.95%   |
| 2001    | 1         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 57        | 54.29%  |
| Notebook       | 35        | 33.33%  |
| System on chip | 6         | 5.71%   |
| Mini pc        | 4         | 3.81%   |
| Server         | 2         | 1.9%    |
| All in one     | 1         | 0.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 97.14%  |
| Yes  | 3         | 2.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 26.67%  |
| 16.01-24.0  | 18        | 17.14%  |
| 8.01-16.0   | 16        | 15.24%  |
| 3.01-4.0    | 12        | 11.43%  |
| 0.01-0.5    | 9         | 8.57%   |
| 32.01-64.0  | 6         | 5.71%   |
| 0.51-1.0    | 6         | 5.71%   |
| 1.01-2.0    | 4         | 3.81%   |
| 24.01-32.0  | 2         | 1.9%    |
| 64.01-256.0 | 2         | 1.9%    |
| 0           | 1         | 0.95%   |
| Unknown     | 1         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 105       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 52        | 47.71%  |
| 1      | 39        | 35.78%  |
| 2      | 13        | 11.93%  |
| 3      | 3         | 2.75%   |
| 4      | 2         | 1.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 96.19%  |
| Yes       | 4         | 3.81%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 80%     |
| No        | 21        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 59.05%  |
| No        | 43        | 40.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 56.19%  |
| Yes       | 46        | 43.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Russia                 | 16        | 15.24%  |
| USA                    | 15        | 14.29%  |
| Italy                  | 9         | 8.57%   |
| Germany                | 9         | 8.57%   |
| France                 | 9         | 8.57%   |
| UK                     | 6         | 5.71%   |
| Spain                  | 5         | 4.76%   |
| Hungary                | 4         | 3.81%   |
| Saudi Arabia           | 3         | 2.86%   |
| Romania                | 3         | 2.86%   |
| Finland                | 3         | 2.86%   |
| Denmark                | 3         | 2.86%   |
| Vietnam                | 2         | 1.9%    |
| Poland                 | 2         | 1.9%    |
| Japan                  | 2         | 1.9%    |
| India                  | 2         | 1.9%    |
| Taiwan                 | 1         | 0.95%   |
| Norway                 | 1         | 0.95%   |
| Netherlands            | 1         | 0.95%   |
| Mexico                 | 1         | 0.95%   |
| Latvia                 | 1         | 0.95%   |
| Czechia                | 1         | 0.95%   |
| China                  | 1         | 0.95%   |
| Canada                 | 1         | 0.95%   |
| Brazil                 | 1         | 0.95%   |
| Bosnia and Herzegovina | 1         | 0.95%   |
| Austria                | 1         | 0.95%   |
| Australia              | 1         | 0.95%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 9         | 8.49%   |
| Rome                  | 8         | 7.55%   |
| Moscow                | 5         | 4.72%   |
| Noyon                 | 4         | 3.77%   |
| Riyadh                | 3         | 2.83%   |
| Lille                 | 3         | 2.83%   |
| Gardony               | 3         | 2.83%   |
| Frederiksberg         | 3         | 2.83%   |
| Bucharest             | 3         | 2.83%   |
| Berlin                | 3         | 2.83%   |
| Tampere               | 2         | 1.89%   |
| Long Beach            | 2         | 1.89%   |
| Ho Chi Minh City      | 2         | 1.89%   |
| Higashihatsuishi      | 2         | 1.89%   |
| Hayward               | 2         | 1.89%   |
| A Coruña             | 2         | 1.89%   |
| Washington            | 1         | 0.94%   |
| Urupes                | 1         | 0.94%   |
| Unterhaching          | 1         | 0.94%   |
| Ulan-Ude              | 1         | 0.94%   |
| Turin                 | 1         | 0.94%   |
| Turenki               | 1         | 0.94%   |
| Taipei                | 1         | 0.94%   |
| Sydney                | 1         | 0.94%   |
| Surrey                | 1         | 0.94%   |
| Sun Prairie           | 1         | 0.94%   |
| Stourbridge           | 1         | 0.94%   |
| Sopron                | 1         | 0.94%   |
| Sarajevo              | 1         | 0.94%   |
| Sandnes               | 1         | 0.94%   |
| Royal Tunbridge Wells | 1         | 0.94%   |
| Riga                  | 1         | 0.94%   |
| Reno                  | 1         | 0.94%   |
| Prague                | 1         | 0.94%   |
| Poznan                | 1         | 0.94%   |
| Portland              | 1         | 0.94%   |
| Novosibirsk           | 1         | 0.94%   |
| New York              | 1         | 0.94%   |
| Murcia                | 1         | 0.94%   |
| Madrid                | 1         | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 16.67%  |
| Seagate             | 11        | 12     | 15.28%  |
| Samsung Electronics | 6         | 6      | 8.33%   |
| Kingston            | 6         | 7      | 8.33%   |
| SanDisk             | 5         | 6      | 6.94%   |
| Toshiba             | 4         | 6      | 5.56%   |
| Maxtor              | 3         | 4      | 4.17%   |
| Intel               | 3         | 3      | 4.17%   |
| Hitachi             | 3         | 4      | 4.17%   |
| HGST                | 3         | 3      | 4.17%   |
| Crucial             | 3         | 4      | 4.17%   |
| JetFlash            | 2         | 2      | 2.78%   |
| Hewlett-Packard     | 2         | 2      | 2.78%   |
| USB                 | 1         | 1      | 1.39%   |
| SK hynix            | 1         | 2      | 1.39%   |
| Lexar               | 1         | 1      | 1.39%   |
| Intenso             | 1         | 1      | 1.39%   |
| IBM/Hitachi         | 1         | 1      | 1.39%   |
| Generic             | 1         | 1      | 1.39%   |
| Fanxiang            | 1         | 1      | 1.39%   |
| Dell                | 1         | 2      | 1.39%   |
| China               | 1         | 1      | 1.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 4.11%   |
| SanDisk Extreme SSD 500GB           | 2         | 2.74%   |
| Samsung SSD 860 EVO 500GB           | 2         | 2.74%   |
| Samsung HD103UJ 1TB                 | 2         | 2.74%   |
| Maxtor STM3250310AS 250GB           | 2         | 2.74%   |
| Kingston DataTraveler 3.0 32GB      | 2         | 2.74%   |
| JetFlash Transcend 16GB             | 2         | 2.74%   |
| HGST HTS541010A9E680 1TB            | 2         | 2.74%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 1         | 1.37%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.37%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1.37%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 1.37%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1.37%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 1.37%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 1.37%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1.37%   |
| WDC WD200EB-00BHF0 20GB             | 1         | 1.37%   |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 1.37%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1         | 1.37%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1.37%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1         | 1.37%   |
| USB SanDisk 3.2Gen1 64GB            | 1         | 1.37%   |
| Toshiba DT01ACA200 2TB              | 1         | 1.37%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.37%   |
| Seagate ST940110A 40GB              | 1         | 1.37%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.37%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1.37%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.37%   |
| Seagate ST380011A 80GB              | 1         | 1.37%   |
| Seagate ST33221A 3GB                | 1         | 1.37%   |
| Seagate ST2000DM001-1CH164 2TB      | 1         | 1.37%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1.37%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1.37%   |
| Seagate ST1000DX001-1CM162 1TB      | 1         | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1.37%   |
| SanDisk SSD i110 16GB               | 1         | 1.37%   |
| SanDisk SDSSDH3512G 512GB           | 1         | 1.37%   |
| SanDisk Cruzer Glide 16GB           | 1         | 1.37%   |
| Samsung HM080HC 80GB                | 1         | 1.37%   |
| Samsung HD501LJ 500GB               | 1         | 1.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 22.92%  |
| WDC                 | 10        | 12     | 20.83%  |
| Toshiba             | 4         | 6      | 8.33%   |
| Samsung Electronics | 4         | 4      | 8.33%   |
| Maxtor              | 3         | 4      | 6.25%   |
| Hitachi             | 3         | 4      | 6.25%   |
| HGST                | 3         | 3      | 6.25%   |
| JetFlash            | 2         | 2      | 4.17%   |
| Hewlett-Packard     | 2         | 2      | 4.17%   |
| USB                 | 1         | 1      | 2.08%   |
| Lexar               | 1         | 1      | 2.08%   |
| Intenso             | 1         | 1      | 2.08%   |
| IBM/Hitachi         | 1         | 1      | 2.08%   |
| Generic             | 1         | 1      | 2.08%   |
| Dell                | 1         | 2      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 24%     |
| SanDisk             | 5         | 6      | 20%     |
| WDC                 | 3         | 3      | 12%     |
| Intel               | 3         | 3      | 12%     |
| Crucial             | 3         | 4      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |
| SK hynix            | 1         | 2      | 4%      |
| Fanxiang            | 1         | 1      | 4%      |
| China               | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 56     | 60.66%  |
| SSD  | 24        | 29     | 39.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 85     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 58     | 71.64%  |
| 0.51-1.0   | 15        | 19     | 22.39%  |
| 1.01-2.0   | 3         | 6      | 4.48%   |
| 4.01-10.0  | 1         | 2      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 32.08%  |
| 251-500        | 19        | 17.92%  |
| 501-1000       | 16        | 15.09%  |
| 1-20           | 12        | 11.32%  |
| 51-100         | 10        | 9.43%   |
| 21-50          | 7         | 6.6%    |
| 1001-2000      | 4         | 3.77%   |
| 2001-3000      | 3         | 2.83%   |
| More than 3000 | 1         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 79        | 71.17%  |
| 21-50          | 14        | 12.61%  |
| 51-100         | 6         | 5.41%   |
| 101-250        | 4         | 3.6%    |
| 501-1000       | 3         | 2.7%    |
| 251-500        | 2         | 1.8%    |
| 1001-2000      | 2         | 1.8%    |
| More than 3000 | 1         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 6.67%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 6.67%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 6.67%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 6.67%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 6.67%   |
| Seagate ST1000DX001-1CM162 1TB      | 1         | 1      | 6.67%   |
| Maxtor 6E040L0 40GB                 | 1         | 1      | 6.67%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 6.67%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 6.67%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB   | 1         | 1      | 6.67%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 6.67%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 5         | 5      | 33.33%  |
| Intel       | 3         | 3      | 20%     |
| WDC         | 2         | 2      | 13.33%  |
| Hitachi     | 2         | 3      | 13.33%  |
| SK hynix    | 1         | 1      | 6.67%   |
| Maxtor      | 1         | 1      | 6.67%   |
| IBM/Hitachi | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 5         | 5      | 50%     |
| Hitachi     | 2         | 3      | 20%     |
| WDC         | 1         | 1      | 10%     |
| Maxtor      | 1         | 1      | 10%     |
| IBM/Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 11     | 66.67%  |
| SSD  | 5         | 5      | 33.33%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 34        | 56     | 55.74%  |
| Malfunc  | 15        | 16     | 24.59%  |
| Detected | 12        | 13     | 19.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 63        | 54.78%  |
| AMD                            | 21        | 18.26%  |
| Samsung Electronics            | 7         | 6.09%   |
| Silicon Motion                 | 4         | 3.48%   |
| SanDisk                        | 3         | 2.61%   |
| Phison Electronics             | 3         | 2.61%   |
| Micron/Crucial Technology      | 3         | 2.61%   |
| VIA Technologies               | 2         | 1.74%   |
| ULi Electronics                | 1         | 0.87%   |
| Solid State Storage Technology | 1         | 0.87%   |
| Nvidia                         | 1         | 0.87%   |
| Micron Technology              | 1         | 0.87%   |
| Kingston Technology Company    | 1         | 0.87%   |
| Hewlett-Packard                | 1         | 0.87%   |
| Broadcom / LSI                 | 1         | 0.87%   |
| ASMedia Technology             | 1         | 0.87%   |
| Apple                          | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 6.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 4.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 3.91%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 3.13%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 2.34%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 2.34%   |
| Intel product 54d3                                                             | 3         | 2.34%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3         | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 2.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 2.34%   |
| AMD FCH SATA Controller D                                                      | 3         | 2.34%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2         | 1.56%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.56%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.56%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.56%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 2         | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.56%   |
| ULi M5229 IDE                                                                  | 1         | 0.78%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 1         | 0.78%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.78%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.78%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.78%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.78%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.78%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 1         | 0.78%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 1         | 0.78%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.78%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 79        | 64.75%  |
| NVMe | 24        | 19.67%  |
| IDE  | 16        | 13.11%  |
| RAID | 3         | 2.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 67        | 63.81%  |
| AMD             | 23        | 21.9%   |
| Unknown         | 6         | 5.71%   |
| Broadcom        | 3         | 2.86%   |
| Arm             | 2         | 1.9%    |
| 7447A           | 2         | 1.9%    |
| SUNW,UltraAX-i2 | 1         | 0.95%   |
| 123456789ABC    | 1         | 0.95%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 686-class                                 | 17        | 15.89%  |
|                                                 | 6         | 5.61%   |
| Intel N100                                      | 2         | 1.87%   |
| Broadcom BCM2711 (ARM Cortex-A72)               | 2         | 1.87%   |
| Arm Cortex-A53 r0p4 (v8-A)                      | 2         | 1.87%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 1.87%   |
| AMD 686-class                                   | 2         | 1.87%   |
| 7447A (Revision 1.2)                            | 2         | 1.87%   |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1         | 0.93%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1         | 0.93%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz             | 1         | 0.93%   |
| Intel Xeon                                      | 1         | 0.93%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz        | 1         | 0.93%   |
| Intel Pentium M processor 1.60GHz               | 1         | 0.93%   |
| Intel Pentium M processor                       | 1         | 0.93%   |
| Intel Pentium III                               | 1         | 0.93%   |
| Intel Pentium CPU 2020M @ 2.40GHz               | 1         | 0.93%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 0.93%   |
| Intel Core i7-7920HQ CPU @ 3.10GHz              | 1         | 0.93%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i7-5557U CPU @ 3.10GHz               | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 0.93%   |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1         | 0.93%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1         | 0.93%   |
| Intel Core i5-8500B CPU @ 3.00GHz               | 1         | 0.93%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 0.93%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 0.93%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1         | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 0.93%   |
| Intel Core i5-5350U CPU @ 1.80GHz               | 1         | 0.93%   |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 22        | 20.56%  |
| Other                | 20        | 18.69%  |
| Intel 686-class      | 17        | 15.89%  |
| Intel Core i7        | 9         | 8.41%   |
| Intel Xeon           | 3         | 2.8%    |
| Intel Core i3        | 3         | 2.8%    |
| Intel Celeron        | 3         | 2.8%    |
| AMD Ryzen 5          | 3         | 2.8%    |
| AMD Ryzen 3          | 3         | 2.8%    |
| AMD FX               | 3         | 2.8%    |
| Intel Pentium M      | 2         | 1.87%   |
| Intel Core 2         | 2         | 1.87%   |
| AMD Ryzen 9          | 2         | 1.87%   |
| AMD Ryzen 7          | 2         | 1.87%   |
| AMD 686-class        | 2         | 1.87%   |
| Intel Pentium Silver | 1         | 0.93%   |
| Intel Pentium III    | 1         | 0.93%   |
| Intel Pentium        | 1         | 0.93%   |
| Intel Core m3        | 1         | 0.93%   |
| Intel Atom           | 1         | 0.93%   |
| AMD Sempron          | 1         | 0.93%   |
| AMD Phenom II X6     | 1         | 0.93%   |
| AMD Phenom II X4     | 1         | 0.93%   |
| AMD E                | 1         | 0.93%   |
| AMD Athlon II        | 1         | 0.93%   |
| AMD A10              | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 45        | 42.06%  |
| 4       | 24        | 22.43%  |
| 2       | 23        | 21.5%   |
| 6       | 7         | 6.54%   |
| 8       | 6         | 5.61%   |
| 12      | 2         | 1.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 72        | 67.29%  |
| Unknown | 34        | 31.78%  |
| 2       | 1         | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 45        | 42.06%  |
| 2       | 35        | 32.71%  |
| 1       | 26        | 24.3%   |
| 6       | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 43        | 40.19%  |
| KabyLake      | 10        | 9.35%   |
| Skylake       | 6         | 5.61%   |
| IvyBridge     | 6         | 5.61%   |
| SandyBridge   | 5         | 4.67%   |
| Zen 2         | 4         | 3.74%   |
| Piledriver    | 4         | 3.74%   |
| P6            | 4         | 3.74%   |
| Haswell       | 4         | 3.74%   |
| Zen+          | 3         | 2.8%    |
| K10           | 3         | 2.8%    |
| Core          | 3         | 2.8%    |
| Broadwell     | 3         | 2.8%    |
| Zen           | 2         | 1.87%   |
| Zen 3         | 1         | 0.93%   |
| Westmere      | 1         | 0.93%   |
| TigerLake     | 1         | 0.93%   |
| Silvermont    | 1         | 0.93%   |
| Goldmont plus | 1         | 0.93%   |
| Geode         | 1         | 0.93%   |
| Bobcat        | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 56        | 56.57%  |
| AMD                        | 24        | 24.24%  |
| Nvidia                     | 16        | 16.16%  |
| VIA Technologies           | 1         | 1.01%   |
| Trident Microsystems       | 1         | 1.01%   |
| Matrox Electronics Systems | 1         | 1.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 4.9%    |
| Intel HD Graphics 530                                                         | 4         | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 2.94%   |
| Intel JasperLake [UHD Graphics]                                               | 3         | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.94%   |
| Intel Alder Lake-N [UHD Graphics]                                             | 3         | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 3         | 2.94%   |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 1.96%   |
| Nvidia GF114 [GeForce GTX 560]                                                | 2         | 1.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 1.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 1.96%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 1.96%   |
| Intel Iris Graphics 6100                                                      | 2         | 1.96%   |
| Intel HD Graphics 630                                                         | 2         | 1.96%   |
| Intel HD Graphics 6000                                                        | 2         | 1.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.96%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 1.96%   |
| AMD RV280 [Radeon 9200]                                                       | 2         | 1.96%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 1.96%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 0.98%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 1         | 0.98%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                                | 1         | 0.98%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                          | 1         | 0.98%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.98%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 1         | 0.98%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 0.98%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 0.98%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.98%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.98%   |
| Nvidia G86 [GeForce 8500 GT]                                                  | 1         | 0.98%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                       | 1         | 0.98%   |
| Matrox Electronics Systems G200eR2                                            | 1         | 0.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.98%   |
| Intel UHD Graphics 620                                                        | 1         | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 0.98%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 48        | 45.71%  |
| 1 x AMD                  | 21        | 20%     |
| 1 x Nvidia               | 13        | 12.38%  |
| Other                    | 12        | 11.43%  |
| 2 x Intel                | 3         | 2.86%   |
| Intel + Nvidia           | 3         | 2.86%   |
| 2 x AMD                  | 1         | 0.95%   |
| 1 x VIA                  | 1         | 0.95%   |
| 1 x Trident Microsystems | 1         | 0.95%   |
| 1 x Matrox               | 1         | 0.95%   |
| Intel + AMD              | 1         | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 73        | 67.59%  |
| Unknown | 35        | 32.41%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 56.6%   |
| 1.01-2.0   | 15        | 14.15%  |
| 3.01-4.0   | 11        | 10.38%  |
| 0.01-0.5   | 11        | 10.38%  |
| 0.51-1.0   | 7         | 6.6%    |
| 7.01-8.0   | 1         | 0.94%   |
| 5.01-6.0   | 1         | 0.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 8         | 17.78%  |
| LG Display              | 6         | 13.33%  |
| Goldstar                | 5         | 11.11%  |
| Lenovo                  | 3         | 6.67%   |
| Apple                   | 3         | 6.67%   |
| Eizo                    | 2         | 4.44%   |
| Chimei Innolux          | 2         | 4.44%   |
| BOE                     | 2         | 4.44%   |
| Acer                    | 2         | 4.44%   |
| ViewSonic               | 1         | 2.22%   |
| Unknown (CDD)           | 1         | 2.22%   |
| Sony                    | 1         | 2.22%   |
| Philips                 | 1         | 2.22%   |
| NEC Computers           | 1         | 2.22%   |
| LG Philips              | 1         | 2.22%   |
| InfoVision              | 1         | 2.22%   |
| Impression              | 1         | 2.22%   |
| Iiyama                  | 1         | 2.22%   |
| Fujitsu Siemens         | 1         | 2.22%   |
| Dell                    | 1         | 2.22%   |
| Chi Mei Optoelectronics | 1         | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch   | 2         | 4.44%   |
| Eizo M170 ENC1768 1280x1024 340x270mm 17.1-inch                         | 2         | 4.44%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 2.22%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch                | 1         | 2.22%   |
| Sony TV SNY4D04 1920x1080                                               | 1         | 2.22%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch    | 1         | 2.22%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch    | 1         | 2.22%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch       | 1         | 2.22%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch       | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch    | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 2.22%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                 | 1         | 2.22%   |
| NEC Computers P221W NEC674A 1680x1050 470x300mm 22.0-inch               | 1         | 2.22%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch            | 1         | 2.22%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch             | 1         | 2.22%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                    | 1         | 2.22%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                 | 1         | 2.22%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                 | 1         | 2.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch            | 1         | 2.22%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                  | 1         | 2.22%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                    | 1         | 2.22%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                     | 1         | 2.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch             | 1         | 2.22%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 2.22%   |
| Goldstar L226WTQ GSM564D 1680x1050 490x320mm 23.0-inch                  | 1         | 2.22%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                    | 1         | 2.22%   |
| Fujitsu Siemens SL27T-1 LED FUS07E5 1920x1080 600x340mm 27.2-inch       | 1         | 2.22%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                       | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch         | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch | 1         | 2.22%   |
| BOE LCD Monitor BOE0827 1366x768 310x170mm 13.9-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE074F 1920x1080 310x170mm 13.9-inch                   | 1         | 2.22%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                  | 1         | 2.22%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                  | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 16        | 36.36%  |
| 1366x768 (WXGA)    | 8         | 18.18%  |
| 1440x900 (WXGA+)   | 4         | 9.09%   |
| 1600x900 (HD+)     | 3         | 6.82%   |
| 1280x800 (WXGA)    | 3         | 6.82%   |
| 2560x1440 (QHD)    | 2         | 4.55%   |
| 1680x1050 (WSXGA+) | 2         | 4.55%   |
| 1280x1024 (SXGA)   | 2         | 4.55%   |
| 2560x1600          | 1         | 2.27%   |
| 2560x1080          | 1         | 2.27%   |
| 1600x1200          | 1         | 2.27%   |
| 1024x600           | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 12        | 26.67%  |
| 27      | 5         | 11.11%  |
| 15      | 5         | 11.11%  |
| 23      | 4         | 8.89%   |
| 19      | 3         | 6.67%   |
| 40      | 2         | 4.44%   |
| 24      | 2         | 4.44%   |
| 21      | 2         | 4.44%   |
| 17      | 2         | 4.44%   |
| 52      | 1         | 2.22%   |
| 34      | 1         | 2.22%   |
| 22      | 1         | 2.22%   |
| 20      | 1         | 2.22%   |
| 14      | 1         | 2.22%   |
| 12      | 1         | 2.22%   |
| 9       | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 35.56%  |
| 501-600     | 10        | 22.22%  |
| 401-500     | 8         | 17.78%  |
| 201-300     | 6         | 13.33%  |
| 801-900     | 2         | 4.44%   |
| 701-800     | 1         | 2.22%   |
| 1001-1500   | 1         | 2.22%   |
| Unknown     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 29        | 65.91%  |
| 16/10 | 10        | 22.73%  |
| 5/4   | 2         | 4.55%   |
| 4/3   | 1         | 2.27%   |
| 3/2   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 28.89%  |
| 201-250        | 8         | 17.78%  |
| 301-350        | 5         | 11.11%  |
| 151-200        | 4         | 8.89%   |
| 101-110        | 3         | 6.67%   |
| 141-150        | 2         | 4.44%   |
| 501-1000       | 2         | 4.44%   |
| 91-100         | 2         | 4.44%   |
| More than 1000 | 1         | 2.22%   |
| 61-70          | 1         | 2.22%   |
| 351-500        | 1         | 2.22%   |
| 41-50          | 1         | 2.22%   |
| 251-300        | 1         | 2.22%   |
| Unknown        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 20        | 45.45%  |
| 101-120 | 14        | 31.82%  |
| 121-160 | 7         | 15.91%  |
| 1-50    | 1         | 2.27%   |
| 161-240 | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 56.6%   |
| 0     | 45        | 42.45%  |
| 2     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 45        | 33.58%  |
| Realtek Semiconductor             | 43        | 32.09%  |
| Qualcomm Atheros                  | 15        | 11.19%  |
| Broadcom                          | 12        | 8.96%   |
| Huawei Technologies               | 3         | 2.24%   |
| TP-Link                           | 2         | 1.49%   |
| Marvell Technology Group          | 2         | 1.49%   |
| 3Com                              | 2         | 1.49%   |
| VIA Technologies                  | 1         | 0.75%   |
| Qualcomm Atheros Communications   | 1         | 0.75%   |
| Oculus VR                         | 1         | 0.75%   |
| Netchip Technology                | 1         | 0.75%   |
| Mercucys                          | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| Dell                              | 1         | 0.75%   |
| Davicom Semiconductor             | 1         | 0.75%   |
| D-Link                            | 1         | 0.75%   |
| Apple                             | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 36        | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.51%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 2.34%   |
| Intel Wireless 8260                                                           | 4         | 2.34%   |
| Intel I211 Gigabit Network Connection                                         | 4         | 2.34%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 1.75%   |
| Huawei USB Device                                                             | 3         | 1.75%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 3         | 1.75%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.17%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.17%   |
| Intel Wireless 7265                                                           | 2         | 1.17%   |
| Intel Wireless 7260                                                           | 2         | 1.17%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2         | 1.17%   |
| Intel Wi-Fi 6 AX200                                                           | 2         | 1.17%   |
| Intel Ethernet Controller I225-V                                              | 2         | 1.17%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.17%   |
| Intel CNVi: Wi-Fi                                                             | 2         | 1.17%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.17%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 2         | 1.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 51.43%  |
| Qualcomm Atheros                | 11        | 15.71%  |
| Realtek Semiconductor           | 10        | 14.29%  |
| Broadcom                        | 8         | 11.43%  |
| TP-Link                         | 2         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 1.43%   |
| Mercucys                        | 1         | 1.43%   |
| D-Link                          | 1         | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                            | 4         | 5.63%   |
| Intel Wireless 8260                                                                   | 4         | 5.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 3         | 4.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 3         | 4.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 2         | 2.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.82%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.82%   |
| Intel Wireless 7265                                                                   | 2         | 2.82%   |
| Intel Wireless 7260                                                                   | 2         | 2.82%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 2.82%   |
| Intel Wi-Fi 6 AX200                                                                   | 2         | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 2.82%   |
| Intel CNVi: Wi-Fi                                                                     | 2         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 2.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 2.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 1.41%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.41%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.41%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 1         | 1.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.41%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 43.48%  |
| Intel                    | 30        | 32.61%  |
| Broadcom                 | 8         | 8.7%    |
| Qualcomm Atheros         | 4         | 4.35%   |
| Huawei Technologies      | 3         | 3.26%   |
| Marvell Technology Group | 2         | 2.17%   |
| 3Com                     | 2         | 2.17%   |
| VIA Technologies         | 1         | 1.09%   |
| Davicom Semiconductor    | 1         | 1.09%   |
| Apple                    | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 36        | 38.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 6.45%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 4.3%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 3.23%   |
| Huawei USB Device                                                      | 3         | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 2.15%   |
| Intel Ethernet Controller I225-V                                       | 2         | 2.15%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.15%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 2.15%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 2.15%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 2.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.08%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.08%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.08%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.08%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.08%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.08%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.08%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 1.08%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 1.08%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 1.08%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.08%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1         | 1.08%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                         | 1         | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.08%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.08%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.08%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 1.08%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1         | 1.08%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                        | 1         | 1.08%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 86        | 55.13%  |
| WiFi     | 63        | 40.38%  |
| Modem    | 4         | 2.56%   |
| Unknown  | 3         | 1.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 72.63%  |
| WiFi     | 25        | 26.32%  |
| Unknown  | 1         | 1.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 51        | 48.11%  |
| 1     | 33        | 31.13%  |
| 0     | 16        | 15.09%  |
| 3     | 5         | 4.72%   |
| 4     | 1         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 79.25%  |
| Yes  | 22        | 20.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 57.45%  |
| Apple                           | 7         | 14.89%  |
| Realtek Semiconductor           | 4         | 8.51%   |
| Broadcom                        | 3         | 6.38%   |
| Qualcomm Atheros Communications | 2         | 4.26%   |
| Cambridge Silicon Radio         | 2         | 4.26%   |
| Lite-On Technology              | 1         | 2.13%   |
| IMC Networks                    | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 23.4%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 14.89%  |
| Realtek Bluetooth Adapter                           | 3         | 6.38%   |
| Intel AX201 Bluetooth                               | 3         | 6.38%   |
| Apple Broadcom Built-in Bluetooth                   | 3         | 6.38%   |
| Apple Bluetooth Host Controller                     | 3         | 6.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 4.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 4.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 4.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 4.26%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.13%   |
| Intel AX200 Bluetooth                               | 1         | 2.13%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.13%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 64        | 57.66%  |
| AMD                                          | 24        | 21.62%  |
| Nvidia                                       | 10        | 9.01%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 1.8%    |
| Logitech                                     | 2         | 1.8%    |
| Yamaha                                       | 1         | 0.9%    |
| VIA Technologies                             | 1         | 0.9%    |
| Texas Instruments                            | 1         | 0.9%    |
| Samsung Electronics                          | 1         | 0.9%    |
| Realtek Semiconductor                        | 1         | 0.9%    |
| Native Instruments                           | 1         | 0.9%    |
| ESS Technology                               | 1         | 0.9%    |
| Creative Labs                                | 1         | 0.9%    |
| Apple                                        | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 5.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 8         | 5.8%    |
| Intel Sunrise Point-LP HD Audio                                                   | 6         | 4.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 3.62%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 3.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 3.62%   |
| Intel Cannon Lake PCH cAVS                                                        | 4         | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                          | 4         | 2.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4         | 2.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 2.17%   |
| Intel Jasper Lake HD Audio                                                        | 3         | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 2.17%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 3         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 2.17%   |
| Intel 8 Series HD Audio Controller                                                | 3         | 2.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                            | 3         | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 2.17%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3         | 2.17%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 1.45%   |
| Nvidia High Definition Audio Controller                                           | 2         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.45%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2         | 1.45%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 2         | 1.45%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.45%   |
| Yamaha AG06/AG03                                                                  | 1         | 0.72%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 0.72%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.72%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1         | 0.72%   |
| Realtek Semiconductor ATH-M50xSTS-USB                                             | 1         | 0.72%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.72%   |
| Native Instruments Komplete Audio 1                                               | 1         | 0.72%   |
| Logitech Zone Wired Earbuds                                                       | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 14.44%  |
| Crucial             | 12        | 13.33%  |
| Micron Technology   | 11        | 12.22%  |
| Kingston            | 11        | 12.22%  |
| Unknown             | 10        | 11.11%  |
| SK hynix            | 8         | 8.89%   |
| G.Skill             | 5         | 5.56%   |
| Unknown             | 4         | 4.44%   |
| Ramaxel Technology  | 3         | 3.33%   |
| Patriot             | 3         | 3.33%   |
| Corsair             | 3         | 3.33%   |
| A-DATA Technology   | 3         | 3.33%   |
| SHARETRONIC         | 1         | 1.11%   |
| Nanya Technology    | 1         | 1.11%   |
| AMD                 | 1         | 1.11%   |
| 48spaces            | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 4         | 4.04%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s    | 2         | 2.02%   |
| Micron RAM Module 8GB Chip LPDDR4                        | 2         | 2.02%   |
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s | 2         | 2.02%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 1.01%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                   | 1         | 1.01%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s             | 1         | 1.01%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 1.01%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s              | 1         | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR3                       | 1         | 1.01%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s              | 1         | 1.01%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 1         | 1.01%   |
| Unknown RAM Module 256MB SODIMM DDR                      | 1         | 1.01%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 1.01%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1         | 1.01%   |
| Unknown RAM Module 128MB DIMM DRAM                       | 1         | 1.01%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s           | 1         | 1.01%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s            | 1         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 1.01%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s         | 1         | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.01%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 1         | 1.01%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 1         | 1.01%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 1.01%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.01%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.01%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s            | 1         | 1.01%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s              | 1         | 1.01%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 1.01%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.01%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s   | 1         | 1.01%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s   | 1         | 1.01%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s   | 1         | 1.01%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s    | 1         | 1.01%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s    | 1         | 1.01%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s    | 1         | 1.01%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s      | 1         | 1.01%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s  | 1         | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 42.47%  |
| DDR3    | 28        | 38.36%  |
| DDR2    | 4         | 5.48%   |
| LPDDR4  | 2         | 2.74%   |
| LPDDR3  | 2         | 2.74%   |
| DRAM    | 2         | 2.74%   |
| SDRAM   | 1         | 1.37%   |
| LPDDR2  | 1         | 1.37%   |
| DDR     | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 50.68%  |
| DIMM         | 30        | 41.1%   |
| Chip         | 4         | 5.48%   |
| Row Of Chips | 1         | 1.37%   |
| FB-DIMM      | 1         | 1.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 35.44%  |
| 4096  | 21        | 26.58%  |
| 2048  | 12        | 15.19%  |
| 16384 | 11        | 13.92%  |
| 1024  | 2         | 2.53%   |
| 512   | 2         | 2.53%   |
| 32768 | 1         | 1.27%   |
| 256   | 1         | 1.27%   |
| 128   | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 15        | 18.29%  |
| 2133    | 9         | 10.98%  |
| 3200    | 8         | 9.76%   |
| 2667    | 8         | 9.76%   |
| 2400    | 8         | 9.76%   |
| 1333    | 6         | 7.32%   |
| Unknown | 6         | 7.32%   |
| 1867    | 3         | 3.66%   |
| 1334    | 3         | 3.66%   |
| 800     | 3         | 3.66%   |
| 667     | 3         | 3.66%   |
| 1067    | 2         | 2.44%   |
| 3000    | 1         | 1.22%   |
| 2933    | 1         | 1.22%   |
| 2666    | 1         | 1.22%   |
| 1066    | 1         | 1.22%   |
| 533     | 1         | 1.22%   |
| 400     | 1         | 1.22%   |
| 266     | 1         | 1.22%   |
| 166     | 1         | 1.22%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Chicony Electronics              | 11        | 32.35%  |
| Silicon Motion                   | 3         | 8.82%   |
| Realtek Semiconductor            | 3         | 8.82%   |
| Logitech                         | 2         | 5.88%   |
| Lenovo                           | 2         | 5.88%   |
| Bison Electronics                | 2         | 5.88%   |
| Z-Star Microelectronics          | 1         | 2.94%   |
| Syntek                           | 1         | 2.94%   |
| Sunplus Innovation Technology    | 1         | 2.94%   |
| Shenzhen Kingcome Optoelectronic | 1         | 2.94%   |
| Quanta                           | 1         | 2.94%   |
| Microdia                         | 1         | 2.94%   |
| Lite-On Technology               | 1         | 2.94%   |
| IMC Networks                     | 1         | 2.94%   |
| ARC International                | 1         | 2.94%   |
| Apple                            | 1         | 2.94%   |
| ALi                              | 1         | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 4         | 11.43%  |
| Lenovo Integrated Webcam [R5U877]                             | 2         | 5.71%   |
| Z-Star Webcam                                                 | 1         | 2.86%   |
| Syntek Lenovo EasyCamera                                      | 1         | 2.86%   |
| Sunplus Integrated Camera                                     | 1         | 2.86%   |
| Silicon Motion WebCam SC-10IRQ12340N                          | 1         | 2.86%   |
| Silicon Motion LG HD WebCam                                   | 1         | 2.86%   |
| Silicon Motion 300k Pixel Camera                              | 1         | 2.86%   |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1         | 2.86%   |
| Realtek USB Camera                                            | 1         | 2.86%   |
| Realtek USB 2.0 PC Camera                                     | 1         | 2.86%   |
| Realtek Acer 640 x 480 laptop camera                          | 1         | 2.86%   |
| Quanta VGA WebCam                                             | 1         | 2.86%   |
| Microdia Integrated_Webcam_HD                                 | 1         | 2.86%   |
| Logitech Webcam C270                                          | 1         | 2.86%   |
| Logitech C922 Pro Stream Webcam                               | 1         | 2.86%   |
| Lite-On Integrated Camera                                     | 1         | 2.86%   |
| IMC Networks Realtek PC Camera                                | 1         | 2.86%   |
| Chicony XiaoMi USB 2.0 Webcam                                 | 1         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 2.86%   |
| Chicony Thinkpad T430 camera                                  | 1         | 2.86%   |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 2.86%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 2.86%   |
| Chicony Front Camera                                          | 1         | 2.86%   |
| Chicony 8M Camera                                             | 1         | 2.86%   |
| Chicony 720p HD Camera                                        | 1         | 2.86%   |
| Bison ThinkPad P50 Integrated Camera                          | 1         | 2.86%   |
| Bison Integrated Camera                                       | 1         | 2.86%   |
| ARC International Camera                                      | 1         | 2.86%   |
| Apple FaceTime HD Camera                                      | 1         | 2.86%   |
| ALi Gateway Webcam                                            | 1         | 2.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Upek             | 1         | 25%     |
| Synaptics        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 25%     |
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |

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
| 0     | 34        | 32.08%  |
| 1     | 32        | 30.19%  |
| 2     | 24        | 22.64%  |
| 3     | 10        | 9.43%   |
| 5     | 4         | 3.77%   |
| 4     | 2         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 57        | 48.31%  |
| Net/wireless             | 36        | 30.51%  |
| Card reader              | 9         | 7.63%   |
| Graphics card            | 6         | 5.08%   |
| Storage                  | 2         | 1.69%   |
| Sound                    | 2         | 1.69%   |
| Net/ethernet             | 2         | 1.69%   |
| Wireless                 | 1         | 0.85%   |
| Storage/nvme             | 1         | 0.85%   |
| Modem                    | 1         | 0.85%   |
| Bluetooth                | 1         | 0.85%   |

