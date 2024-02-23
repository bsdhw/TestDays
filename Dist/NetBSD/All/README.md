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

Total: 117

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Unknown       | Unknown                     | Desktop     | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
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


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NetBSD 9.3        | 15        | 15.46%  |
| NetBSD 9.2        | 13        | 13.4%   |
| NetBSD 9.1        | 11        | 11.34%  |
| NetBSD 9.0_STABLE | 8         | 8.25%   |
| NetBSD 9.0        | 6         | 6.19%   |
| NetBSD 10.0_RC2   | 5         | 5.15%   |
| NetBSD 10.0_RC1   | 5         | 5.15%   |
| NetBSD 10.0_BETA  | 5         | 5.15%   |
| NetBSD 9.99.94    | 3         | 3.09%   |
| NetBSD 9.99.93    | 3         | 3.09%   |
| NetBSD 9.1_STABLE | 3         | 3.09%   |
| NetBSD 9.99.77    | 2         | 2.06%   |
| NetBSD 9.3_STABLE | 2         | 2.06%   |
| NetBSD 9.2_STABLE | 2         | 2.06%   |
| NetBSD 9.99.85    | 1         | 1.03%   |
| NetBSD 9.99.81    | 1         | 1.03%   |
| NetBSD 9.99.74    | 1         | 1.03%   |
| NetBSD 9.99.71    | 1         | 1.03%   |
| NetBSD 9.99.61    | 1         | 1.03%   |
| NetBSD 9.99.23    | 1         | 1.03%   |
| NetBSD 9.99.107   | 1         | 1.03%   |
| NetBSD 8.99.51    | 1         | 1.03%   |
| NetBSD 8.2        | 1         | 1.03%   |
| NetBSD 7.2        | 1         | 1.03%   |
| NetBSD 10.99.7    | 1         | 1.03%   |
| NetBSD 10.99.10   | 1         | 1.03%   |
| NetBSD 10.99.1    | 1         | 1.03%   |
| NetBSD 10.0_RC3   | 1         | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 86        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 66        | 76.74%  |
| evbarm  | 10        | 11.63%  |
| i386    | 7         | 8.14%   |
| macppc  | 2         | 2.33%   |
| sparc64 | 1         | 1.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 34        | 38.64%  |
| XFCE         | 23        | 26.14%  |
| helloDesktop | 9         | 10.23%  |
| CTWM         | 5         | 5.68%   |
| Fluxbox      | 4         | 4.55%   |
| DWM          | 3         | 3.41%   |
| MATE         | 2         | 2.27%   |
| Xfwm4        | 1         | 1.14%   |
| Window Maker | 1         | 1.14%   |
| sdorfehs     | 1         | 1.14%   |
| Ratpoison    | 1         | 1.14%   |
| PekWM        | 1         | 1.14%   |
| LXQt         | 1         | 1.14%   |
| JWM          | 1         | 1.14%   |
| Awesome      | 1         | 1.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 65        | 75.58%  |
| Console | 21        | 24.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 76        | 88.37%  |
| XDM     | 4         | 4.65%   |
| SLiM    | 3         | 3.49%   |
| GDM     | 2         | 2.33%   |
| LightDM | 1         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 64        | 71.11%  |
| en_US   | 16        | 17.78%  |
| ru_RU   | 3         | 3.33%   |
| fi_FI   | 2         | 2.22%   |
| C       | 2         | 2.22%   |
| hu_HU   | 1         | 1.11%   |
| fr_FR   | 1         | 1.11%   |
| en_GB   | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 82        | 95.35%  |
| EFI  | 4         | 4.65%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 85        | 98.84%  |
| Unknown | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 54        | 62.79%  |
| Unknown | 32        | 37.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 25        | 29.07%  |
| Lenovo                  | 10        | 11.63%  |
| ASUSTek Computer        | 9         | 10.47%  |
| Gigabyte Technology     | 6         | 6.98%   |
| Raspberry Pi Foundation | 5         | 5.81%   |
| Intel                   | 4         | 4.65%   |
| ASRock                  | 4         | 4.65%   |
| Hewlett-Packard         | 3         | 3.49%   |
| Dell                    | 3         | 3.49%   |
| Acer                    | 3         | 3.49%   |
| Samsung Electronics     | 2         | 2.33%   |
| MSI                     | 2         | 2.33%   |
| Apple                   | 2         | 2.33%   |
| Toshiba                 | 1         | 1.16%   |
| Sony                    | 1         | 1.16%   |
| MiTAC                   | 1         | 1.16%   |
| KLLISRE                 | 1         | 1.16%   |
| IBM                     | 1         | 1.16%   |
| Google                  | 1         | 1.16%   |
| Fujitsu Siemens         | 1         | 1.16%   |
| eMachines               | 1         | 1.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 25        | 29.07%  |
| RPi Raspberry Pi                            | 3         | 3.49%   |
| RPi Raspberry Pi 4 Model B                  | 2         | 2.33%   |
| ASUS PRIME A320M-K                          | 2         | 2.33%   |
| Toshiba Satellite A100                      | 1         | 1.16%   |
| Sony SVF1421DSGW                            | 1         | 1.16%   |
| Samsung N150/N210/N220                      | 1         | 1.16%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.16%   |
| MSI MS-7B86                                 | 1         | 1.16%   |
| MSI MS-7551                                 | 1         | 1.16%   |
| MiTAC 5033                                  | 1         | 1.16%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 1.16%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.16%   |
| Lenovo ThinkPad T470 20HES0EV0A             | 1         | 1.16%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 1.16%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 1.16%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 1.16%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 1.16%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 1.16%   |
| Lenovo ThinkCentre M72e 3598CP8             | 1         | 1.16%   |
| Lenovo G500 20236                           | 1         | 1.16%   |
| KLLISRE X99-B5 V1.0                         | 1         | 1.16%   |
| Intel NUC7PJYH                              | 1         | 1.16%   |
| Intel NUC5PPYB H76558-102                   | 1         | 1.16%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 1.16%   |
| Intel DN2820FYK H24582-203                  | 1         | 1.16%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 1.16%   |
| HP Vectra                                   | 1         | 1.16%   |
| HP ProLiant DL360 G5                        | 1         | 1.16%   |
| HP Pavilion 17                              | 1         | 1.16%   |
| Google Kohaku                               | 1         | 1.16%   |
| Gigabyte Z170X-Gaming 3                     | 1         | 1.16%   |
| Gigabyte X570 AORUS PRO                     | 1         | 1.16%   |
| Gigabyte P75-D3                             | 1         | 1.16%   |
| Gigabyte H61M-S2PV                          | 1         | 1.16%   |
| Gigabyte A320M-H                            | 1         | 1.16%   |
| Gigabyte 970A-D3P                           | 1         | 1.16%   |
| Fujitsu Siemens AMILO L7310                 | 1         | 1.16%   |
| eMachines eME642G                           | 1         | 1.16%   |
| Dell Vostro 3500                            | 1         | 1.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 25        | 29.07%  |
| Lenovo ThinkPad       | 8         | 9.3%    |
| RPi Raspberry         | 5         | 5.81%   |
| ASUS TUF              | 2         | 2.33%   |
| ASUS PRIME            | 2         | 2.33%   |
| Acer Aspire           | 2         | 2.33%   |
| Toshiba Satellite     | 1         | 1.16%   |
| Sony SVF1421DSGW      | 1         | 1.16%   |
| Samsung N150          | 1         | 1.16%   |
| Samsung DP700A3D      | 1         | 1.16%   |
| MSI MS-7B86           | 1         | 1.16%   |
| MSI MS-7551           | 1         | 1.16%   |
| MiTAC 5033            | 1         | 1.16%   |
| Lenovo ThinkCentre    | 1         | 1.16%   |
| Lenovo G500           | 1         | 1.16%   |
| KLLISRE X99-B5        | 1         | 1.16%   |
| Intel NUC7PJYH        | 1         | 1.16%   |
| Intel NUC5PPYB        | 1         | 1.16%   |
| Intel NUC5i7RYB       | 1         | 1.16%   |
| Intel DN2820FYK       | 1         | 1.16%   |
| IBM ThinkPad          | 1         | 1.16%   |
| HP Vectra             | 1         | 1.16%   |
| HP ProLiant           | 1         | 1.16%   |
| HP Pavilion           | 1         | 1.16%   |
| Google Kohaku         | 1         | 1.16%   |
| Gigabyte Z170X-Gaming | 1         | 1.16%   |
| Gigabyte X570         | 1         | 1.16%   |
| Gigabyte P75-D3       | 1         | 1.16%   |
| Gigabyte H61M-S2PV    | 1         | 1.16%   |
| Gigabyte A320M-H      | 1         | 1.16%   |
| Gigabyte 970A-D3P     | 1         | 1.16%   |
| Fujitsu Siemens AMILO | 1         | 1.16%   |
| eMachines eME642G     | 1         | 1.16%   |
| Dell Vostro           | 1         | 1.16%   |
| Dell Precision        | 1         | 1.16%   |
| Dell PowerEdge        | 1         | 1.16%   |
| ASUS X555LJ           | 1         | 1.16%   |
| ASUS E45M1-I          | 1         | 1.16%   |
| ASUS B150M-K          | 1         | 1.16%   |
| ASUS All              | 1         | 1.16%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 26        | 30.23%  |
| 2020    | 9         | 10.47%  |
| 2013    | 8         | 9.3%    |
| 2018    | 6         | 6.98%   |
| 2014    | 4         | 4.65%   |
| 2010    | 4         | 4.65%   |
| 2022    | 3         | 3.49%   |
| 2021    | 3         | 3.49%   |
| 2017    | 3         | 3.49%   |
| 2015    | 3         | 3.49%   |
| 2011    | 3         | 3.49%   |
| 2007    | 3         | 3.49%   |
| 2005    | 3         | 3.49%   |
| 2019    | 2         | 2.33%   |
| 2016    | 2         | 2.33%   |
| 2012    | 2         | 2.33%   |
| 2024    | 1         | 1.16%   |
| 2001    | 1         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 49        | 56.98%  |
| Notebook       | 25        | 29.07%  |
| System on chip | 5         | 5.81%   |
| Mini pc        | 4         | 4.65%   |
| Server         | 2         | 2.33%   |
| All in one     | 1         | 1.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 97.67%  |
| Yes  | 2         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 27.91%  |
| 16.01-24.0  | 15        | 17.44%  |
| 8.01-16.0   | 11        | 12.79%  |
| 3.01-4.0    | 10        | 11.63%  |
| 0.01-0.5    | 8         | 9.3%    |
| 0.51-1.0    | 6         | 6.98%   |
| 32.01-64.0  | 5         | 5.81%   |
| 1.01-2.0    | 3         | 3.49%   |
| 24.01-32.0  | 1         | 1.16%   |
| 64.01-256.0 | 1         | 1.16%   |
| 0           | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 86        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 42        | 46.67%  |
| 1      | 33        | 36.67%  |
| 2      | 11        | 12.22%  |
| 3      | 3         | 3.33%   |
| 4      | 1         | 1.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 96.51%  |
| Yes       | 3         | 3.49%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 80.23%  |
| No        | 17        | 19.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 55.81%  |
| No        | 38        | 44.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 54        | 62.79%  |
| Yes       | 32        | 37.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 15        | 17.44%  |
| USA          | 11        | 12.79%  |
| Italy        | 9         | 10.47%  |
| Germany      | 8         | 9.3%    |
| France       | 6         | 6.98%   |
| UK           | 5         | 5.81%   |
| Hungary      | 4         | 4.65%   |
| Spain        | 3         | 3.49%   |
| Saudi Arabia | 3         | 3.49%   |
| Finland      | 3         | 3.49%   |
| Vietnam      | 2         | 2.33%   |
| Romania      | 2         | 2.33%   |
| Poland       | 2         | 2.33%   |
| Japan        | 2         | 2.33%   |
| India        | 2         | 2.33%   |
| Norway       | 1         | 1.16%   |
| Netherlands  | 1         | 1.16%   |
| Latvia       | 1         | 1.16%   |
| Czechia      | 1         | 1.16%   |
| China        | 1         | 1.16%   |
| Canada       | 1         | 1.16%   |
| Brazil       | 1         | 1.16%   |
| Austria      | 1         | 1.16%   |
| Australia    | 1         | 1.16%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 9         | 10.34%  |
| Rome                  | 8         | 9.2%    |
| Moscow                | 5         | 5.75%   |
| Riyadh                | 3         | 3.45%   |
| Lille                 | 3         | 3.45%   |
| Gardony               | 3         | 3.45%   |
| Tampere               | 2         | 2.3%    |
| Long Beach            | 2         | 2.3%    |
| Ho Chi Minh City      | 2         | 2.3%    |
| Higashihatsuishi      | 2         | 2.3%    |
| Hayward               | 2         | 2.3%    |
| Bucharest             | 2         | 2.3%    |
| Berlin                | 2         | 2.3%    |
| Washington            | 1         | 1.15%   |
| Urupes                | 1         | 1.15%   |
| Unterhaching          | 1         | 1.15%   |
| Ulan-Ude              | 1         | 1.15%   |
| Turin                 | 1         | 1.15%   |
| Turenki               | 1         | 1.15%   |
| Sydney                | 1         | 1.15%   |
| Surrey                | 1         | 1.15%   |
| Sun Prairie           | 1         | 1.15%   |
| Stourbridge           | 1         | 1.15%   |
| Sopron                | 1         | 1.15%   |
| Sandnes               | 1         | 1.15%   |
| Royal Tunbridge Wells | 1         | 1.15%   |
| Riga                  | 1         | 1.15%   |
| Reno                  | 1         | 1.15%   |
| Prague                | 1         | 1.15%   |
| Poznan                | 1         | 1.15%   |
| Portland              | 1         | 1.15%   |
| Noyon                 | 1         | 1.15%   |
| Murcia                | 1         | 1.15%   |
| Madrid                | 1         | 1.15%   |
| London                | 1         | 1.15%   |
| Lohr a. Main          | 1         | 1.15%   |
| Leichlingen           | 1         | 1.15%   |
| Ladbergen             | 1         | 1.15%   |
| Kwidzyn               | 1         | 1.15%   |
| Kalispell             | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 15%     |
| Seagate             | 7         | 7      | 11.67%  |
| Samsung Electronics | 6         | 6      | 10%     |
| Kingston            | 6         | 7      | 10%     |
| Toshiba             | 4         | 6      | 6.67%   |
| SanDisk             | 4         | 5      | 6.67%   |
| Maxtor              | 3         | 3      | 5%      |
| Intel               | 3         | 3      | 5%      |
| Hitachi             | 3         | 4      | 5%      |
| Crucial             | 3         | 4      | 5%      |
| HGST                | 2         | 2      | 3.33%   |
| Hewlett-Packard     | 2         | 2      | 3.33%   |
| SK hynix            | 1         | 2      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| JetFlash            | 1         | 1      | 1.67%   |
| Intenso             | 1         | 1      | 1.67%   |
| IBM/Hitachi         | 1         | 1      | 1.67%   |
| Generic             | 1         | 1      | 1.67%   |
| Dell                | 1         | 2      | 1.67%   |
| China               | 1         | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 4.92%   |
| SanDisk Extreme SSD 500GB           | 2         | 3.28%   |
| Samsung SSD 860 EVO 500GB           | 2         | 3.28%   |
| Samsung HD103UJ 1TB                 | 2         | 3.28%   |
| Maxtor STM3250310AS 250GB           | 2         | 3.28%   |
| Kingston DataTraveler 3.0 32GB      | 2         | 3.28%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.64%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1.64%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 1.64%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1.64%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 1.64%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 1.64%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1.64%   |
| WDC WD200EB-00BHF0 20GB             | 1         | 1.64%   |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 1.64%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1.64%   |
| Toshiba DT01ACA200 2TB              | 1         | 1.64%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.64%   |
| Seagate ST940110A 40GB              | 1         | 1.64%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.64%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1.64%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.64%   |
| Seagate ST380011A 80GB              | 1         | 1.64%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1.64%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1.64%   |
| SanDisk SDSSDH3512G 512GB           | 1         | 1.64%   |
| SanDisk Cruzer Glide 16GB           | 1         | 1.64%   |
| Samsung HM080HC 80GB                | 1         | 1.64%   |
| Samsung HD501LJ 500GB               | 1         | 1.64%   |
| Maxtor 6E040L0 40GB                 | 1         | 1.64%   |
| Lexar USB Flash Drive 64GB          | 1         | 1.64%   |
| Kingston SM2280S3G2120G 120GB       | 1         | 1.64%   |
| Kingston SA400S37480G 480GB         | 1         | 1.64%   |
| Kingston SA400S37240G 240GB         | 1         | 1.64%   |
| Kingston SA400S37120G 120GB         | 1         | 1.64%   |
| JetFlash Transcend 16GB             | 1         | 1.64%   |
| Intenso Rainbow Line 8GB            | 1         | 1.64%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1.64%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1.64%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 20.51%  |
| Seagate             | 7         | 7      | 17.95%  |
| Toshiba             | 4         | 6      | 10.26%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| Maxtor              | 3         | 3      | 7.69%   |
| Hitachi             | 3         | 4      | 7.69%   |
| HGST                | 2         | 2      | 5.13%   |
| Hewlett-Packard     | 2         | 2      | 5.13%   |
| Lexar               | 1         | 1      | 2.56%   |
| JetFlash            | 1         | 1      | 2.56%   |
| Intenso             | 1         | 1      | 2.56%   |
| IBM/Hitachi         | 1         | 1      | 2.56%   |
| Generic             | 1         | 1      | 2.56%   |
| Dell                | 1         | 2      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 27.27%  |
| SanDisk             | 4         | 5      | 18.18%  |
| Intel               | 3         | 3      | 13.64%  |
| Crucial             | 3         | 4      | 13.64%  |
| WDC                 | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 2      | 9.09%   |
| SK hynix            | 1         | 2      | 4.55%   |
| China               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 45     | 60.38%  |
| SSD  | 21        | 26     | 39.62%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 46        | 71     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 50     | 73.68%  |
| 0.51-1.0   | 12        | 15     | 21.05%  |
| 1.01-2.0   | 2         | 4      | 3.51%   |
| 4.01-10.0  | 1         | 2      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 29.07%  |
| 251-500        | 16        | 18.6%   |
| 501-1000       | 13        | 15.12%  |
| 1-20           | 11        | 12.79%  |
| 51-100         | 9         | 10.47%  |
| 21-50          | 6         | 6.98%   |
| 2001-3000      | 3         | 3.49%   |
| 1001-2000      | 2         | 2.33%   |
| More than 3000 | 1         | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 63        | 68.48%  |
| 21-50          | 12        | 13.04%  |
| 51-100         | 6         | 6.52%   |
| 101-250        | 4         | 4.35%   |
| 251-500        | 2         | 2.17%   |
| 1001-2000      | 2         | 2.17%   |
| 501-1000       | 2         | 2.17%   |
| More than 3000 | 1         | 1.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 7.14%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 7.14%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 7.14%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 7.14%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 7.14%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 7.14%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 7.14%   |
| Maxtor 6E040L0 40GB                 | 1         | 1      | 7.14%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 7.14%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 7.14%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 7.14%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB   | 1         | 1      | 7.14%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 7.14%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 4         | 4      | 28.57%  |
| Intel       | 3         | 3      | 21.43%  |
| WDC         | 2         | 2      | 14.29%  |
| Hitachi     | 2         | 3      | 14.29%  |
| SK hynix    | 1         | 1      | 7.14%   |
| Maxtor      | 1         | 1      | 7.14%   |
| IBM/Hitachi | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Computers | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 4         | 4      | 44.44%  |
| Hitachi     | 2         | 3      | 22.22%  |
| WDC         | 1         | 1      | 11.11%  |
| Maxtor      | 1         | 1      | 11.11%  |
| IBM/Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 64.29%  |
| SSD  | 5         | 5      | 35.71%  |

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
| Works    | 27        | 44     | 51.92%  |
| Malfunc  | 14        | 15     | 26.92%  |
| Detected | 11        | 12     | 21.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 52        | 55.91%  |
| AMD                            | 17        | 18.28%  |
| Samsung Electronics            | 5         | 5.38%   |
| Silicon Motion                 | 3         | 3.23%   |
| SanDisk                        | 3         | 3.23%   |
| Phison Electronics             | 2         | 2.15%   |
| Micron/Crucial Technology      | 2         | 2.15%   |
| VIA Technologies               | 1         | 1.08%   |
| ULi Electronics                | 1         | 1.08%   |
| Solid State Storage Technology | 1         | 1.08%   |
| Nvidia                         | 1         | 1.08%   |
| Kingston Technology Company    | 1         | 1.08%   |
| Hewlett-Packard                | 1         | 1.08%   |
| Broadcom / LSI                 | 1         | 1.08%   |
| ASMedia Technology             | 1         | 1.08%   |
| Apple                          | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 7.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 5.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 5.83%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 4.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 3.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 2.91%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 3         | 2.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 2.91%   |
| Intel product 54d3                                                               | 3         | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 2.91%   |
| AMD FCH SATA Controller D                                                        | 3         | 2.91%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1.94%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.94%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 1.94%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.94%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.97%   |
| ULi M5229 IDE                                                                    | 1         | 0.97%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.97%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 0.97%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.97%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.97%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.97%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.97%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 65        | 67.01%  |
| NVMe | 16        | 16.49%  |
| IDE  | 14        | 14.43%  |
| RAID | 2         | 2.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 54        | 62.79%  |
| AMD             | 18        | 20.93%  |
| Unknown         | 6         | 6.98%   |
| Broadcom        | 2         | 2.33%   |
| Arm             | 2         | 2.33%   |
| 7447A           | 2         | 2.33%   |
| SUNW,UltraAX-i2 | 1         | 1.16%   |
| 123456789ABC    | 1         | 1.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 686-class                                 | 17        | 19.32%  |
|                                                 | 6         | 6.82%   |
| Intel N100                                      | 2         | 2.27%   |
| Broadcom BCM2711 (ARM Cortex-A72)               | 2         | 2.27%   |
| Arm Cortex-A53 r0p4 (v8-A)                      | 2         | 2.27%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 2.27%   |
| AMD 686-class                                   | 2         | 2.27%   |
| 7447A (Revision 1.2)                            | 2         | 2.27%   |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1         | 1.14%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1         | 1.14%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz             | 1         | 1.14%   |
| Intel Xeon                                      | 1         | 1.14%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz        | 1         | 1.14%   |
| Intel Pentium M processor 1.60GHz               | 1         | 1.14%   |
| Intel Pentium M processor                       | 1         | 1.14%   |
| Intel Pentium III                               | 1         | 1.14%   |
| Intel Pentium CPU 2020M @ 2.40GHz               | 1         | 1.14%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 1.14%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 1.14%   |
| Intel Core i7-5557U CPU @ 3.10GHz               | 1         | 1.14%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 1.14%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.14%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.14%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 1.14%   |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1         | 1.14%   |
| Intel Core i5-8500B CPU @ 3.00GHz               | 1         | 1.14%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 1.14%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.14%   |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1         | 1.14%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1         | 1.14%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 1         | 1.14%   |
| Intel Core i5 CPU M 560 @ 2.67GH                | 1         | 1.14%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 1.14%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1         | 1.14%   |
| Intel Core i3-3220T CPU @ 2.80GHz               | 1         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Other                | 18        | 20.45%  |
| Intel 686-class      | 17        | 19.32%  |
| Intel Core i5        | 14        | 15.91%  |
| Intel Core i7        | 7         | 7.95%   |
| Intel Xeon           | 3         | 3.41%   |
| Intel Core i3        | 3         | 3.41%   |
| AMD Ryzen 3          | 3         | 3.41%   |
| Intel Pentium M      | 2         | 2.27%   |
| Intel Core 2         | 2         | 2.27%   |
| AMD Ryzen 9          | 2         | 2.27%   |
| AMD Ryzen 5          | 2         | 2.27%   |
| AMD 686-class        | 2         | 2.27%   |
| Intel Pentium Silver | 1         | 1.14%   |
| Intel Pentium III    | 1         | 1.14%   |
| Intel Pentium        | 1         | 1.14%   |
| Intel Celeron        | 1         | 1.14%   |
| Intel Atom           | 1         | 1.14%   |
| AMD Sempron          | 1         | 1.14%   |
| AMD Ryzen 7          | 1         | 1.14%   |
| AMD Phenom II X6     | 1         | 1.14%   |
| AMD Phenom II X4     | 1         | 1.14%   |
| AMD FX               | 1         | 1.14%   |
| AMD E                | 1         | 1.14%   |
| AMD Athlon II        | 1         | 1.14%   |
| AMD A10              | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 48.86%  |
| 4       | 18        | 20.45%  |
| 2       | 17        | 19.32%  |
| 8       | 4         | 4.55%   |
| 6       | 4         | 4.55%   |
| 12      | 2         | 2.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 55        | 62.5%   |
| Unknown | 32        | 36.36%  |
| 2       | 1         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 43        | 48.86%  |
| 2       | 25        | 28.41%  |
| 1       | 20        | 22.73%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 39        | 44.32%  |
| KabyLake      | 6         | 6.82%   |
| IvyBridge     | 6         | 6.82%   |
| SandyBridge   | 4         | 4.55%   |
| Zen+          | 3         | 3.41%   |
| Zen 2         | 3         | 3.41%   |
| Skylake       | 3         | 3.41%   |
| P6            | 3         | 3.41%   |
| K10           | 3         | 3.41%   |
| Haswell       | 3         | 3.41%   |
| Core          | 3         | 3.41%   |
| Zen           | 2         | 2.27%   |
| Piledriver    | 2         | 2.27%   |
| Broadwell     | 2         | 2.27%   |
| Westmere      | 1         | 1.14%   |
| TigerLake     | 1         | 1.14%   |
| Silvermont    | 1         | 1.14%   |
| Goldmont plus | 1         | 1.14%   |
| Geode         | 1         | 1.14%   |
| Bobcat        | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 45        | 55.56%  |
| AMD                        | 21        | 25.93%  |
| Nvidia                     | 12        | 14.81%  |
| VIA Technologies           | 1         | 1.23%   |
| Trident Microsystems       | 1         | 1.23%   |
| Matrox Electronics Systems | 1         | 1.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.95%   |
| Intel HD Graphics 530                                                                    | 3         | 3.57%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 3         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 3.57%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 2.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.38%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.38%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.38%   |
| Intel Iris Graphics 6100                                                                 | 2         | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 2.38%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.38%   |
| AMD RV280 [Radeon 9200]                                                                  | 2         | 2.38%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.19%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.19%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.19%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.19%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.19%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.19%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.19%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.19%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.19%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.19%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 1.19%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.19%   |
| Intel HD Graphics 630                                                                    | 1         | 1.19%   |
| Intel HD Graphics 620                                                                    | 1         | 1.19%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.19%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.19%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 38        | 44.19%  |
| 1 x AMD                  | 18        | 20.93%  |
| Other                    | 11        | 12.79%  |
| 1 x Nvidia               | 9         | 10.47%  |
| 2 x Intel                | 3         | 3.49%   |
| Intel + Nvidia           | 2         | 2.33%   |
| 2 x AMD                  | 1         | 1.16%   |
| 1 x VIA                  | 1         | 1.16%   |
| 1 x Trident Microsystems | 1         | 1.16%   |
| 1 x Matrox               | 1         | 1.16%   |
| Intel + AMD              | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 57        | 64.77%  |
| Unknown | 31        | 35.23%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 54.02%  |
| 1.01-2.0   | 15        | 17.24%  |
| 0.01-0.5   | 10        | 11.49%  |
| 3.01-4.0   | 8         | 9.2%    |
| 0.51-1.0   | 5         | 5.75%   |
| 7.01-8.0   | 1         | 1.15%   |
| 5.01-6.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 19.44%  |
| LG Display              | 6         | 16.67%  |
| Goldstar                | 4         | 11.11%  |
| Lenovo                  | 2         | 5.56%   |
| Eizo                    | 2         | 5.56%   |
| Chimei Innolux          | 2         | 5.56%   |
| Apple                   | 2         | 5.56%   |
| ViewSonic               | 1         | 2.78%   |
| Unknown (CDD)           | 1         | 2.78%   |
| Philips                 | 1         | 2.78%   |
| NEC Computers           | 1         | 2.78%   |
| LG Philips              | 1         | 2.78%   |
| Impression              | 1         | 2.78%   |
| Iiyama                  | 1         | 2.78%   |
| Dell                    | 1         | 2.78%   |
| Chi Mei Optoelectronics | 1         | 2.78%   |
| BOE                     | 1         | 2.78%   |
| Acer                    | 1         | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch   | 2         | 5.56%   |
| Eizo M170 ENC1768 1280x1024 340x270mm 17.1-inch                         | 2         | 5.56%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 2.78%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch                | 1         | 2.78%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch    | 1         | 2.78%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch    | 1         | 2.78%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch       | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch    | 1         | 2.78%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 2.78%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch                 | 1         | 2.78%   |
| NEC Computers P221W NEC674A 1680x1050 470x300mm 22.0-inch               | 1         | 2.78%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch            | 1         | 2.78%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch             | 1         | 2.78%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch             | 1         | 2.78%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                    | 1         | 2.78%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                 | 1         | 2.78%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                  | 1         | 2.78%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                    | 1         | 2.78%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                     | 1         | 2.78%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch             | 1         | 2.78%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 2.78%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                    | 1         | 2.78%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                       | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch         | 1         | 2.78%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch         | 1         | 2.78%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch | 1         | 2.78%   |
| BOE LCD Monitor BOE0827 1366x768 310x170mm 13.9-inch                    | 1         | 2.78%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                  | 1         | 2.78%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                   | 1         | 2.78%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                       | 1         | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 11        | 30.56%  |
| 1366x768 (WXGA)    | 8         | 22.22%  |
| 1600x900 (HD+)     | 3         | 8.33%   |
| 1440x900 (WXGA+)   | 3         | 8.33%   |
| 2560x1440 (QHD)    | 2         | 5.56%   |
| 1280x800 (WXGA)    | 2         | 5.56%   |
| 1280x1024 (SXGA)   | 2         | 5.56%   |
| 2560x1600          | 1         | 2.78%   |
| 2560x1080          | 1         | 2.78%   |
| 1680x1050 (WSXGA+) | 1         | 2.78%   |
| 1600x1200          | 1         | 2.78%   |
| 1024x600           | 1         | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 9         | 25%     |
| 15     | 5         | 13.89%  |
| 27     | 4         | 11.11%  |
| 19     | 3         | 8.33%   |
| 40     | 2         | 5.56%   |
| 23     | 2         | 5.56%   |
| 21     | 2         | 5.56%   |
| 17     | 2         | 5.56%   |
| 52     | 1         | 2.78%   |
| 34     | 1         | 2.78%   |
| 24     | 1         | 2.78%   |
| 22     | 1         | 2.78%   |
| 20     | 1         | 2.78%   |
| 12     | 1         | 2.78%   |
| 9      | 1         | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 14        | 38.89%  |
| 501-600     | 7         | 19.44%  |
| 401-500     | 7         | 19.44%  |
| 201-300     | 4         | 11.11%  |
| 801-900     | 2         | 5.56%   |
| 701-800     | 1         | 2.78%   |
| 1001-1500   | 1         | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 25        | 69.44%  |
| 16/10 | 7         | 19.44%  |
| 5/4   | 2         | 5.56%   |
| 4/3   | 1         | 2.78%   |
| 21/9  | 1         | 2.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 25%     |
| 201-250        | 6         | 16.67%  |
| 301-350        | 4         | 11.11%  |
| 151-200        | 4         | 11.11%  |
| 101-110        | 3         | 8.33%   |
| 141-150        | 2         | 5.56%   |
| 501-1000       | 2         | 5.56%   |
| 91-100         | 2         | 5.56%   |
| More than 1000 | 1         | 2.78%   |
| 61-70          | 1         | 2.78%   |
| 351-500        | 1         | 2.78%   |
| 41-50          | 1         | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 17        | 47.22%  |
| 101-120 | 13        | 36.11%  |
| 121-160 | 4         | 11.11%  |
| 1-50    | 1         | 2.78%   |
| 161-240 | 1         | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 47        | 54.02%  |
| 0     | 39        | 44.83%  |
| 2     | 1         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 37        | 33.33%  |
| Intel                             | 35        | 31.53%  |
| Qualcomm Atheros                  | 13        | 11.71%  |
| Broadcom                          | 10        | 9.01%   |
| Huawei Technologies               | 3         | 2.7%    |
| Marvell Technology Group          | 2         | 1.8%    |
| VIA Technologies                  | 1         | 0.9%    |
| TP-Link                           | 1         | 0.9%    |
| Qualcomm Atheros Communications   | 1         | 0.9%    |
| Oculus VR                         | 1         | 0.9%    |
| Netchip Technology                | 1         | 0.9%    |
| Mercucys                          | 1         | 0.9%    |
| Ericsson Business Mobile Networks | 1         | 0.9%    |
| Davicom Semiconductor             | 1         | 0.9%    |
| D-Link                            | 1         | 0.9%    |
| Apple                             | 1         | 0.9%    |
| 3Com                              | 1         | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 32        | 22.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 4.29%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3         | 2.14%   |
| Intel I211 Gigabit Network Connection                                         | 3         | 2.14%   |
| Huawei USB Device                                                             | 3         | 2.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2         | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 2         | 1.43%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.43%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 1.43%   |
| Intel Wireless 8260                                                           | 2         | 1.43%   |
| Intel Wireless 7265                                                           | 2         | 1.43%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 2         | 1.43%   |
| Intel Ethernet Controller I225-V                                              | 2         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 1.43%   |
| Intel CNVi: Wi-Fi                                                             | 2         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 2         | 1.43%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 2         | 1.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.71%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.71%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1         | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 1         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 28        | 51.85%  |
| Qualcomm Atheros                | 10        | 18.52%  |
| Realtek Semiconductor           | 6         | 11.11%  |
| Broadcom                        | 6         | 11.11%  |
| TP-Link                         | 1         | 1.85%   |
| Qualcomm Atheros Communications | 1         | 1.85%   |
| Mercucys                        | 1         | 1.85%   |
| D-Link                          | 1         | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 3         | 5.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 2         | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 3.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 3.64%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 3.64%   |
| Intel Wireless 8265 / 8275                                                            | 2         | 3.64%   |
| Intel Wireless 8260                                                                   | 2         | 3.64%   |
| Intel Wireless 7265                                                                   | 2         | 3.64%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 3.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 3.64%   |
| Intel CNVi: Wi-Fi                                                                     | 2         | 3.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 3.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 3.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 2         | 3.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.82%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.82%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.82%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.82%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 1.82%   |
| Intel Wireless 7260                                                                   | 1         | 1.82%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.82%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.82%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.82%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.82%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 1.82%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                                    | 1         | 1.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 1.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.82%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 46.15%  |
| Intel                    | 23        | 29.49%  |
| Broadcom                 | 7         | 8.97%   |
| Qualcomm Atheros         | 3         | 3.85%   |
| Huawei Technologies      | 3         | 3.85%   |
| Marvell Technology Group | 2         | 2.56%   |
| VIA Technologies         | 1         | 1.28%   |
| Davicom Semiconductor    | 1         | 1.28%   |
| Apple                    | 1         | 1.28%   |
| 3Com                     | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 32        | 40.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 7.59%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 3.8%    |
| Huawei USB Device                                                      | 3         | 3.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 2.53%   |
| Intel Ethernet Controller I225-V                                       | 2         | 2.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 2.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 2         | 2.53%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 2.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 1.27%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 1.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 1.27%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.27%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.27%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.27%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.27%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.27%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 1.27%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.27%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.27%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1         | 1.27%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                         | 1         | 1.27%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.27%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 1.27%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 72        | 56.69%  |
| WiFi     | 49        | 38.58%  |
| Modem    | 4         | 3.15%   |
| Unknown  | 2         | 1.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 57        | 72.15%  |
| WiFi     | 21        | 26.58%  |
| Unknown  | 1         | 1.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 41        | 47.67%  |
| 1     | 24        | 27.91%  |
| 0     | 15        | 17.44%  |
| 3     | 5         | 5.81%   |
| 4     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 81.61%  |
| Yes  | 16        | 18.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 60.61%  |
| Apple                           | 5         | 15.15%  |
| Realtek Semiconductor           | 2         | 6.06%   |
| Broadcom                        | 2         | 6.06%   |
| Qualcomm Atheros Communications | 1         | 3.03%   |
| Lite-On Technology              | 1         | 3.03%   |
| IMC Networks                    | 1         | 3.03%   |
| Cambridge Silicon Radio         | 1         | 3.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 21.21%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 15.15%  |
| Intel AX201 Bluetooth                               | 3         | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 6.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 6.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.06%   |
| Apple Broadcom Built-in Bluetooth                   | 2         | 6.06%   |
| Apple Bluetooth Host Controller                     | 2         | 6.06%   |
| Realtek Bluetooth Adapter                           | 1         | 3.03%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 3.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.03%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 3.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.03%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 3.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 52        | 56.52%  |
| AMD                                          | 20        | 21.74%  |
| Nvidia                                       | 8         | 8.7%    |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 2.17%   |
| Logitech                                     | 2         | 2.17%   |
| Yamaha                                       | 1         | 1.09%   |
| VIA Technologies                             | 1         | 1.09%   |
| Texas Instruments                            | 1         | 1.09%   |
| Samsung Electronics                          | 1         | 1.09%   |
| Native Instruments                           | 1         | 1.09%   |
| ESS Technology                               | 1         | 1.09%   |
| Creative Labs                                | 1         | 1.09%   |
| Apple                                        | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 7.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6         | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.51%   |
| Intel Cannon Lake PCH cAVS                                                        | 4         | 3.51%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 3.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 3.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 3.51%   |
| Intel Sunrise Point-LP HD Audio                                                   | 3         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 2.63%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 3         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 2.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3         | 2.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 2.63%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.75%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2         | 1.75%   |
| Intel Jasper Lake HD Audio                                                        | 2         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.75%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 2         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.75%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.75%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2         | 1.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 1.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.75%   |
| Yamaha AG06/AG03                                                                  | 1         | 0.88%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 0.88%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.88%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1         | 0.88%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.88%   |
| Native Instruments Komplete Audio 1                                               | 1         | 0.88%   |
| Logitech Zone Wired Earbuds                                                       | 1         | 0.88%   |
| Logitech H600 [Wireless Headset]                                                  | 1         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 10        | 15.15%  |
| Crucial             | 10        | 15.15%  |
| Kingston            | 9         | 13.64%  |
| Samsung Electronics | 7         | 10.61%  |
| SK hynix            | 6         | 9.09%   |
| Micron Technology   | 6         | 9.09%   |
| G.Skill             | 4         | 6.06%   |
| A-DATA Technology   | 3         | 4.55%   |
| Ramaxel Technology  | 2         | 3.03%   |
| Patriot             | 2         | 3.03%   |
| Corsair             | 2         | 3.03%   |
| Unknown             | 2         | 3.03%   |
| SHARETRONIC         | 1         | 1.52%   |
| Nanya Technology    | 1         | 1.52%   |
| 48spaces            | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s    | 2         | 2.74%   |
| Micron RAM Module 8GB Chip LPDDR4                        | 2         | 2.74%   |
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s | 2         | 2.74%   |
| Unknown                                                  | 2         | 2.74%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 1.37%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                   | 1         | 1.37%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s             | 1         | 1.37%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s             | 1         | 1.37%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s              | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR3                       | 1         | 1.37%   |
| Unknown RAM Module 2GB FB-DIMM DDR2 667MT/s              | 1         | 1.37%   |
| Unknown RAM Module 256MB SODIMM DDR                      | 1         | 1.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1         | 1.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1         | 1.37%   |
| Unknown RAM Module 128MB DIMM DRAM                       | 1         | 1.37%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 1         | 1.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 1         | 1.37%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s   | 1         | 1.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 1         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 1         | 1.37%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s       | 1         | 1.37%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.37%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s    | 1         | 1.37%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s    | 1         | 1.37%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s    | 1         | 1.37%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s  | 1         | 1.37%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s | 1         | 1.37%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s       | 1         | 1.37%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s           | 1         | 1.37%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s     | 1         | 1.37%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s     | 1         | 1.37%   |
| Micron RAM 16JTF1G64AZ-1G6J1 8GB DIMM DDR3 1333MT/s      | 1         | 1.37%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s   | 1         | 1.37%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s        | 1         | 1.37%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 39.29%  |
| DDR3    | 22        | 39.29%  |
| DDR2    | 4         | 7.14%   |
| LPDDR4  | 2         | 3.57%   |
| DRAM    | 2         | 3.57%   |
| SDRAM   | 1         | 1.79%   |
| LPDDR3  | 1         | 1.79%   |
| DDR     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 26        | 46.43%  |
| DIMM         | 25        | 44.64%  |
| Chip         | 3         | 5.36%   |
| Row Of Chips | 1         | 1.79%   |
| FB-DIMM      | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 36.67%  |
| 4096  | 17        | 28.33%  |
| 2048  | 9         | 15%     |
| 16384 | 5         | 8.33%   |
| 1024  | 2         | 3.33%   |
| 512   | 2         | 3.33%   |
| 32768 | 1         | 1.67%   |
| 256   | 1         | 1.67%   |
| 128   | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 20.63%  |
| 2133    | 7         | 11.11%  |
| 3200    | 5         | 7.94%   |
| 2400    | 5         | 7.94%   |
| 1333    | 5         | 7.94%   |
| Unknown | 5         | 7.94%   |
| 2667    | 4         | 6.35%   |
| 800     | 3         | 4.76%   |
| 1867    | 2         | 3.17%   |
| 1334    | 2         | 3.17%   |
| 1067    | 2         | 3.17%   |
| 667     | 2         | 3.17%   |
| 3000    | 1         | 1.59%   |
| 2933    | 1         | 1.59%   |
| 2666    | 1         | 1.59%   |
| 1066    | 1         | 1.59%   |
| 533     | 1         | 1.59%   |
| 400     | 1         | 1.59%   |
| 266     | 1         | 1.59%   |
| 166     | 1         | 1.59%   |

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
| Chicony Electronics              | 9         | 37.5%   |
| Silicon Motion                   | 2         | 8.33%   |
| Realtek Semiconductor            | 2         | 8.33%   |
| Z-Star Microelectronics          | 1         | 4.17%   |
| Syntek                           | 1         | 4.17%   |
| Sunplus Innovation Technology    | 1         | 4.17%   |
| Shenzhen Kingcome Optoelectronic | 1         | 4.17%   |
| Quanta                           | 1         | 4.17%   |
| Microdia                         | 1         | 4.17%   |
| Logitech                         | 1         | 4.17%   |
| Lenovo                           | 1         | 4.17%   |
| Bison Electronics                | 1         | 4.17%   |
| ARC International                | 1         | 4.17%   |
| ALi                              | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 4         | 16%     |
| Z-Star Webcam                                                 | 1         | 4%      |
| Syntek Lenovo EasyCamera                                      | 1         | 4%      |
| Sunplus Integrated Camera                                     | 1         | 4%      |
| Silicon Motion WebCam SC-10IRQ12340N                          | 1         | 4%      |
| Silicon Motion 300k Pixel Camera                              | 1         | 4%      |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1         | 4%      |
| Realtek USB Camera                                            | 1         | 4%      |
| Realtek Acer 640 x 480 laptop camera                          | 1         | 4%      |
| Quanta VGA WebCam                                             | 1         | 4%      |
| Microdia Integrated_Webcam_HD                                 | 1         | 4%      |
| Logitech Webcam C270                                          | 1         | 4%      |
| Lenovo Integrated Webcam [R5U877]                             | 1         | 4%      |
| Chicony USB2.0 VGA UVC WebCam                                 | 1         | 4%      |
| Chicony Thinkpad T430 camera                                  | 1         | 4%      |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 4%      |
| Chicony Front Camera                                          | 1         | 4%      |
| Chicony 8M Camera                                             | 1         | 4%      |
| Chicony 720p HD Camera                                        | 1         | 4%      |
| Bison Integrated Camera                                       | 1         | 4%      |
| ARC International Camera                                      | 1         | 4%      |
| ALi Gateway Webcam                                            | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Upek             | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 50%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 50%     |

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
| 0     | 32        | 36.78%  |
| 1     | 24        | 27.59%  |
| 2     | 18        | 20.69%  |
| 3     | 8         | 9.2%    |
| 5     | 3         | 3.45%   |
| 4     | 2         | 2.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 45        | 47.87%  |
| Net/wireless             | 26        | 27.66%  |
| Card reader              | 7         | 7.45%   |
| Graphics card            | 6         | 6.38%   |
| Storage                  | 2         | 2.13%   |
| Sound                    | 2         | 2.13%   |
| Net/ethernet             | 2         | 2.13%   |
| Wireless                 | 1         | 1.06%   |
| Storage/nvme             | 1         | 1.06%   |
| Modem                    | 1         | 1.06%   |
| Bluetooth                | 1         | 1.06%   |

