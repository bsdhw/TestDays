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

Total: 487

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 411       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 407       | 99.03%  |
| GNOME        | 2         | 0.49%   |
| KDE5         | 1         | 0.24%   |
| JWM          | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 411       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 411       | 99.76%  |
| SDDM | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 182       | 43.96%  |
| fr_FR   | 84        | 20.29%  |
| ru_RU   | 33        | 7.97%   |
| de_DE   | 25        | 6.04%   |
| Unknown | 20        | 4.83%   |
| es_ES   | 19        | 4.59%   |
| pt_BR   | 11        | 2.66%   |
| pl_PL   | 10        | 2.42%   |
| it_IT   | 9         | 2.17%   |
| zh_CN   | 3         | 0.72%   |
| nl_NL   | 3         | 0.72%   |
| jp_JP   | 3         | 0.72%   |
| ko_KR   | 2         | 0.48%   |
| fi_FI   | 2         | 0.48%   |
| tr_TR   | 1         | 0.24%   |
| pt_PT   | 1         | 0.24%   |
| pt      | 1         | 0.24%   |
| fr      | 1         | 0.24%   |
| fi_DK   | 1         | 0.24%   |
| es      | 1         | 0.24%   |
| en      | 1         | 0.24%   |
| C       | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 407       | 99.03%  |
| BIOS | 4         | 0.97%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 219       | 52.52%  |
| Zfs    | 198       | 47.48%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 407       | 99.03%  |
| MBR  | 4         | 0.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 85        | 20.68%  |
| ASUSTek Computer    | 59        | 14.36%  |
| Hewlett-Packard     | 55        | 13.38%  |
| Dell                | 39        | 9.49%   |
| Gigabyte Technology | 31        | 7.54%   |
| Acer                | 17        | 4.14%   |
| MSI                 | 14        | 3.41%   |
| Intel               | 13        | 3.16%   |
| Apple               | 12        | 2.92%   |
| Fujitsu             | 10        | 2.43%   |
| Toshiba             | 9         | 2.19%   |
| Samsung Electronics | 9         | 2.19%   |
| ASRock              | 9         | 2.19%   |
| Unknown             | 5         | 1.22%   |
| Sony                | 4         | 0.97%   |
| Google              | 4         | 0.97%   |
| T-bao               | 2         | 0.49%   |
| Packard Bell        | 2         | 0.49%   |
| LG Electronics      | 2         | 0.49%   |
| Fujitsu Siemens     | 2         | 0.49%   |
| Foxconn             | 2         | 0.49%   |
| AZW                 | 2         | 0.49%   |
| TUXEDO              | 1         | 0.24%   |
| Timi                | 1         | 0.24%   |
| Shuttle             | 1         | 0.24%   |
| Plaisio             | 1         | 0.24%   |
| Pegatron            | 1         | 0.24%   |
| Panasonic           | 1         | 0.24%   |
| OEGStone            | 1         | 0.24%   |
| NVN-ED01            | 1         | 0.24%   |
| Microsoft           | 1         | 0.24%   |
| Medion              | 1         | 0.24%   |
| Irbis               | 1         | 0.24%   |
| IGEL Technology     | 1         | 0.24%   |
| HUAWEI              | 1         | 0.24%   |
| Huanan              | 1         | 0.24%   |
| Gateway             | 1         | 0.24%   |
| eMachines           | 1         | 0.24%   |
| ECS                 | 1         | 0.24%   |
| Dynabook Europe     | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 9         | 2.19%   |
| ASUS PRIME B250M-A           | 3         | 0.73%   |
| ASUS All Series              | 3         | 0.73%   |
| T-bao MINI PC                | 2         | 0.49%   |
| MSI MS-7788                  | 2         | 0.49%   |
| Intel H81                    | 2         | 0.49%   |
| HP Laptop 14-bs0xx           | 2         | 0.49%   |
| HP EliteDesk 800 G2 DM 35W   | 2         | 0.49%   |
| HP Compaq Elite 8300 USDT    | 2         | 0.49%   |
| Dell OptiPlex 7010           | 2         | 0.49%   |
| Dell OptiPlex 3020           | 2         | 0.49%   |
| ASUS ROG STRIX B550-F GAMING | 2         | 0.49%   |
| Apple MacBookPro9,2          | 2         | 0.49%   |
| Apple MacBook5,1             | 2         | 0.49%   |
| Acer Spin SP314-21           | 2         | 0.49%   |
| TUXEDO Aura 15 Gen1          | 1         | 0.24%   |
| Toshiba Satellite P300       | 1         | 0.24%   |
| Toshiba Satellite L675D      | 1         | 0.24%   |
| Toshiba Satellite L50-B      | 1         | 0.24%   |
| Toshiba Satellite L40        | 1         | 0.24%   |
| Toshiba Satellite C845       | 1         | 0.24%   |
| Toshiba Satellite A200       | 1         | 0.24%   |
| Toshiba QOSMIO X775          | 1         | 0.24%   |
| Toshiba PORTEGE R700         | 1         | 0.24%   |
| Timi TM1701                  | 1         | 0.24%   |
| Sony VPCEG15FB               | 1         | 0.24%   |
| Sony VGN-FZ19VN              | 1         | 0.24%   |
| Sony SVL2412Z1EB             | 1         | 0.24%   |
| Sony SVF14A15CBB             | 1         | 0.24%   |
| Shuttle NC10U                | 1         | 0.24%   |
| Samsung RC530/RC730          | 1         | 0.24%   |
| Samsung R530/R730/R540       | 1         | 0.24%   |
| Samsung R520/R522/R620       | 1         | 0.24%   |
| Samsung R468/R418            | 1         | 0.24%   |
| Samsung N150P/N210P/N220P    | 1         | 0.24%   |
| Samsung 370E4K               | 1         | 0.24%   |
| Samsung 305E4A/305E5A/305E7A | 1         | 0.24%   |
| Samsung 275E4E/275E5E        | 1         | 0.24%   |
| Samsung 270E5J/2570EJ        | 1         | 0.24%   |
| Plaisio Turbo X              | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 49        | 11.92%  |
| ASUS PRIME              | 14        | 3.41%   |
| Lenovo IdeaPad          | 13        | 3.16%   |
| Dell Latitude           | 12        | 2.92%   |
| Lenovo ThinkCentre      | 10        | 2.43%   |
| HP Pavilion             | 10        | 2.43%   |
| HP Compaq               | 10        | 2.43%   |
| Dell OptiPlex           | 10        | 2.43%   |
| Dell Inspiron           | 10        | 2.43%   |
| Unknown                 | 9         | 2.19%   |
| ASUS ROG                | 8         | 1.95%   |
| Acer Aspire             | 8         | 1.95%   |
| HP Laptop               | 7         | 1.7%    |
| Toshiba Satellite       | 6         | 1.46%   |
| HP ProDesk              | 5         | 1.22%   |
| HP EliteDesk            | 5         | 1.22%   |
| HP EliteBook            | 4         | 0.97%   |
| Gigabyte B450M          | 4         | 0.97%   |
| Fujitsu LIFEBOOK        | 3         | 0.73%   |
| Dell Precision          | 3         | 0.73%   |
| ASUS VivoBook           | 3         | 0.73%   |
| ASUS All                | 3         | 0.73%   |
| Apple MacBook5          | 3         | 0.73%   |
| T-bao MINI              | 2         | 0.49%   |
| MSI MS-7788             | 2         | 0.49%   |
| Lenovo Yoga             | 2         | 0.49%   |
| Lenovo Legion           | 2         | 0.49%   |
| Intel H81               | 2         | 0.49%   |
| Gigabyte B550           | 2         | 0.49%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.49%   |
| Fujitsu ESPRIMO         | 2         | 0.49%   |
| Dell Vostro             | 2         | 0.49%   |
| ASUS TUF                | 2         | 0.49%   |
| Apple MacBookPro9       | 2         | 0.49%   |
| Acer Veriton            | 2         | 0.49%   |
| Acer Spin               | 2         | 0.49%   |
| TUXEDO Aura             | 1         | 0.24%   |
| Toshiba QOSMIO          | 1         | 0.24%   |
| Toshiba PORTEGE         | 1         | 0.24%   |
| Timi TM1701             | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 38        | 9.25%   |
| 2020    | 36        | 8.76%   |
| 2012    | 34        | 8.27%   |
| 2013    | 33        | 8.03%   |
| 2021    | 32        | 7.79%   |
| 2011    | 32        | 7.79%   |
| 2019    | 29        | 7.06%   |
| 2010    | 27        | 6.57%   |
| 2018    | 21        | 5.11%   |
| 2017    | 21        | 5.11%   |
| 2016    | 21        | 5.11%   |
| 2014    | 18        | 4.38%   |
| 2009    | 18        | 4.38%   |
| 2015    | 15        | 3.65%   |
| 2008    | 15        | 3.65%   |
| 2023    | 9         | 2.19%   |
| 2007    | 7         | 1.7%    |
| 2006    | 4         | 0.97%   |
| Unknown | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 207       | 50.36%  |
| Desktop     | 187       | 45.5%   |
| Mini pc     | 7         | 1.7%    |
| Convertible | 5         | 1.22%   |
| All in one  | 3         | 0.73%   |
| Tablet      | 1         | 0.24%   |
| Server      | 1         | 0.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 405       | 98.54%  |
| Yes  | 6         | 1.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 146       | 35.52%  |
| 4.01-8.0    | 102       | 24.82%  |
| 16.01-24.0  | 100       | 24.33%  |
| 32.01-64.0  | 27        | 6.57%   |
| 2.01-3.0    | 20        | 4.87%   |
| 3.01-4.0    | 7         | 1.7%    |
| 64.01-256.0 | 5         | 1.22%   |
| 24.01-32.0  | 3         | 0.73%   |
| 0.51-1.0    | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 221       | 53.51%  |
| 0.51-1.0 | 136       | 32.93%  |
| 1.01-2.0 | 40        | 9.69%   |
| 2.01-3.0 | 14        | 3.39%   |
| 3.01-4.0 | 2         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 251       | 60.77%  |
| 2      | 80        | 19.37%  |
| 0      | 31        | 7.51%   |
| 3      | 30        | 7.26%   |
| 5      | 9         | 2.18%   |
| 4      | 6         | 1.45%   |
| 9      | 2         | 0.48%   |
| 6      | 2         | 0.48%   |
| 13     | 1         | 0.24%   |
| 7      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 64.96%  |
| Yes       | 144       | 35.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 378       | 91.97%  |
| No        | 33        | 8.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 274       | 66.5%   |
| No        | 138       | 33.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 50.12%  |
| Yes       | 205       | 49.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 58        | 14.11%  |
| Russia              | 48        | 11.68%  |
| Germany             | 30        | 7.3%    |
| Brazil              | 24        | 5.84%   |
| Poland              | 21        | 5.11%   |
| Spain               | 17        | 4.14%   |
| France              | 16        | 3.89%   |
| Italy               | 15        | 3.65%   |
| UK                  | 13        | 3.16%   |
| Canada              | 12        | 2.92%   |
| Indonesia           | 10        | 2.43%   |
| Romania             | 9         | 2.19%   |
| Hungary             | 9         | 2.19%   |
| Australia           | 9         | 2.19%   |
| Turkey              | 8         | 1.95%   |
| China               | 8         | 1.95%   |
| Belgium             | 7         | 1.7%    |
| Serbia              | 6         | 1.46%   |
| Netherlands         | 6         | 1.46%   |
| Mexico              | 6         | 1.46%   |
| India               | 6         | 1.46%   |
| Ukraine             | 5         | 1.22%   |
| Bulgaria            | 5         | 1.22%   |
| Switzerland         | 4         | 0.97%   |
| South Korea         | 4         | 0.97%   |
| Peru                | 3         | 0.73%   |
| Lithuania           | 3         | 0.73%   |
| Japan               | 3         | 0.73%   |
| Israel              | 3         | 0.73%   |
| Finland             | 3         | 0.73%   |
| Argentina           | 3         | 0.73%   |
| Sweden              | 2         | 0.49%   |
| Slovenia            | 2         | 0.49%   |
| Portugal            | 2         | 0.49%   |
| Kazakhstan          | 2         | 0.49%   |
| Dominican Republic  | 2         | 0.49%   |
| Colombia            | 2         | 0.49%   |
| Chile               | 2         | 0.49%   |
| Belarus             | 2         | 0.49%   |
| Trinidad and Tobago | 1         | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 7         | 1.68%   |
| St Petersburg      | 6         | 1.44%   |
| Sao Paulo          | 6         | 1.44%   |
| Berlin             | 5         | 1.2%    |
| Sydney             | 4         | 0.96%   |
| St. Jean Baptiste  | 4         | 0.96%   |
| Wroclaw            | 3         | 0.72%   |
| Warsaw             | 3         | 0.72%   |
| Sofia              | 3         | 0.72%   |
| Paris              | 3         | 0.72%   |
| Milan              | 3         | 0.72%   |
| Budapest           | 3         | 0.72%   |
| Brooklyn           | 3         | 0.72%   |
| Belgrade           | 3         | 0.72%   |
| Ankara             | 3         | 0.72%   |
| Zurich             | 2         | 0.48%   |
| Woodbridge         | 2         | 0.48%   |
| Vilnius            | 2         | 0.48%   |
| Valencia           | 2         | 0.48%   |
| St Albans          | 2         | 0.48%   |
| Shenzhen           | 2         | 0.48%   |
| Santo Domingo Este | 2         | 0.48%   |
| Santiago           | 2         | 0.48%   |
| Peterborough       | 2         | 0.48%   |
| Penza              | 2         | 0.48%   |
| Pensacola          | 2         | 0.48%   |
| Odesa              | 2         | 0.48%   |
| Novosibirsk        | 2         | 0.48%   |
| New York           | 2         | 0.48%   |
| Montreal           | 2         | 0.48%   |
| Melbourne          | 2         | 0.48%   |
| Madrid             | 2         | 0.48%   |
| Lisbon             | 2         | 0.48%   |
| Krasnodar          | 2         | 0.48%   |
| Krakow             | 2         | 0.48%   |
| Kirov              | 2         | 0.48%   |
| Istanbul           | 2         | 0.48%   |
| Irkutsk            | 2         | 0.48%   |
| Fleurus            | 2         | 0.48%   |
| Dresden            | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 104    | 15.23%  |
| WDC                 | 73        | 109    | 13.39%  |
| Seagate             | 67        | 93     | 12.29%  |
| Kingston            | 46        | 47     | 8.44%   |
| Toshiba             | 38        | 46     | 6.97%   |
| SanDisk             | 29        | 29     | 5.32%   |
| Hitachi             | 22        | 23     | 4.04%   |
| Crucial             | 22        | 26     | 4.04%   |
| A-DATA Technology   | 16        | 17     | 2.94%   |
| Micron Technology   | 10        | 11     | 1.83%   |
| China               | 10        | 11     | 1.83%   |
| Intel               | 9         | 9      | 1.65%   |
| Transcend           | 8         | 8      | 1.47%   |
| SK hynix            | 8         | 8      | 1.47%   |
| HGST                | 8         | 11     | 1.47%   |
| Patriot             | 7         | 7      | 1.28%   |
| SPCC                | 6         | 6      | 1.1%    |
| Maxtor              | 5         | 5      | 0.92%   |
| KingSpec            | 5         | 5      | 0.92%   |
| GOODRAM             | 4         | 4      | 0.73%   |
| Gigabyte Technology | 4         | 5      | 0.73%   |
| Apple               | 4         | 4      | 0.73%   |
| Team                | 3         | 3      | 0.55%   |
| Silicon Motion      | 3         | 3      | 0.55%   |
| PNY                 | 3         | 3      | 0.55%   |
| OCZ                 | 3         | 3      | 0.55%   |
| Intenso             | 3         | 3      | 0.55%   |
| Fujitsu             | 3         | 3      | 0.55%   |
| Apacer              | 3         | 3      | 0.55%   |
| AMD                 | 3         | 3      | 0.55%   |
| Netac               | 2         | 2      | 0.37%   |
| BHT                 | 2         | 2      | 0.37%   |
| WALRAM              | 1         | 1      | 0.18%   |
| Verbatim            | 1         | 1      | 0.18%   |
| Vaseky              | 1         | 1      | 0.18%   |
| V-GeN               | 1         | 1      | 0.18%   |
| UMIS                | 1         | 1      | 0.18%   |
| TAMMUZ              | 1         | 1      | 0.18%   |
| SUNEAST             | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB             | 11        | 1.82%   |
| Samsung SSD 860 EVO 500GB               | 9         | 1.49%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 0.99%   |
| Seagate ST3500418AS 500GB               | 5         | 0.83%   |
| Samsung SSD 850 EVO 250GB               | 5         | 0.83%   |
| Kingston SA400S37120G 120GB             | 5         | 0.83%   |
| Toshiba MQ01ABF050 500GB                | 4         | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB          | 4         | 0.66%   |
| Samsung SSD 980 1TB                     | 4         | 0.66%   |
| Samsung SSD 870 EVO 500GB               | 4         | 0.66%   |
| Crucial CT500MX500SSD1 500GB            | 4         | 0.66%   |
| Crucial CT480BX500SSD1 480GB            | 4         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB            | 3         | 0.5%    |
| WDC WD20EFRX-68EUZN0 2TB                | 3         | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.5%    |
| Toshiba HDWD110 1TB                     | 3         | 0.5%    |
| SPCC Solid State Disk 128GB             | 3         | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 0.5%    |
| SanDisk SSD PLUS 120GB                  | 3         | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB          | 3         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.5%    |
| Samsung SSD 860 EVO 250GB               | 3         | 0.5%    |
| Kingston SHFS37A240G 240GB              | 3         | 0.5%    |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.5%    |
| A-DATA SU650 120GB                      | 3         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB            | 2         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB            | 2         | 0.33%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 2         | 0.33%   |
| WDC WD20EZRX-00D8PB0 2TB                | 2         | 0.33%   |
| WDC WD10EZEX-60WN4A1 1TB                | 2         | 0.33%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.33%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB    | 2         | 0.33%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.33%   |
| Toshiba DT01ACA100 1TB                  | 2         | 0.33%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.33%   |
| SK hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.33%   |
| Seagate ST9500325AS 500GB               | 2         | 0.33%   |
| Seagate ST9250410AS 250GB               | 2         | 0.33%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 92     | 31.43%  |
| WDC                 | 57        | 87     | 27.14%  |
| Toshiba             | 33        | 39     | 15.71%  |
| Hitachi             | 22        | 23     | 10.48%  |
| Samsung Electronics | 12        | 15     | 5.71%   |
| HGST                | 8         | 11     | 3.81%   |
| Maxtor              | 5         | 5      | 2.38%   |
| Fujitsu             | 3         | 3      | 1.43%   |
| Apple               | 3         | 3      | 1.43%   |
| QUANTUM             | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 48     | 16.19%  |
| Kingston            | 36        | 37     | 14.57%  |
| SanDisk             | 29        | 29     | 11.74%  |
| Crucial             | 19        | 22     | 7.69%   |
| WDC                 | 12        | 13     | 4.86%   |
| A-DATA Technology   | 11        | 11     | 4.45%   |
| China               | 10        | 11     | 4.05%   |
| Transcend           | 6         | 6      | 2.43%   |
| Patriot             | 6         | 6      | 2.43%   |
| Intel               | 6         | 6      | 2.43%   |
| SPCC                | 5         | 5      | 2.02%   |
| Micron Technology   | 5         | 5      | 2.02%   |
| KingSpec            | 5         | 5      | 2.02%   |
| Toshiba             | 4         | 6      | 1.62%   |
| GOODRAM             | 4         | 4      | 1.62%   |
| PNY                 | 3         | 3      | 1.21%   |
| OCZ                 | 3         | 3      | 1.21%   |
| Intenso             | 3         | 3      | 1.21%   |
| Gigabyte Technology | 3         | 4      | 1.21%   |
| Apacer              | 3         | 3      | 1.21%   |
| Team                | 2         | 2      | 0.81%   |
| BHT                 | 2         | 2      | 0.81%   |
| WALRAM              | 1         | 1      | 0.4%    |
| Verbatim            | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 1      | 0.4%    |
| V-GeN               | 1         | 1      | 0.4%    |
| TAMMUZ              | 1         | 1      | 0.4%    |
| SUNEAST             | 1         | 1      | 0.4%    |
| SSSTC               | 1         | 1      | 0.4%    |
| SK hynix            | 1         | 1      | 0.4%    |
| SETHRISE            | 1         | 1      | 0.4%    |
| SemsoTai            | 1         | 1      | 0.4%    |
| RX7                 | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| Pioneer             | 1         | 1      | 0.4%    |
| Philips             | 1         | 1      | 0.4%    |
| Palit               | 1         | 1      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| MidasForce          | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 210       | 264    | 42.94%  |
| HDD  | 186       | 279    | 38.04%  |
| NVMe | 93        | 106    | 19.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 338       | 543    | 78.42%  |
| NVMe | 93        | 106    | 21.58%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 292       | 383    | 73.18%  |
| 0.51-1.0   | 71        | 88     | 17.79%  |
| 1.01-2.0   | 21        | 41     | 5.26%   |
| 3.01-4.0   | 8         | 12     | 2.01%   |
| 2.01-3.0   | 3         | 6      | 0.75%   |
| 4.01-10.0  | 3         | 12     | 0.75%   |
| 10.01-20.0 | 1         | 1      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 206       | 49.28%  |
| 101-250    | 67        | 16.03%  |
| 51-100     | 56        | 13.4%   |
| 251-500    | 55        | 13.16%  |
| 501-1000   | 19        | 4.55%   |
| 21-50      | 11        | 2.63%   |
| Unknown    | 3         | 0.72%   |
| 1001-2000  | 1         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 403       | 98.05%  |
| Unknown | 3         | 0.73%   |
| 21-50   | 2         | 0.49%   |
| 101-250 | 2         | 0.49%   |
| 251-500 | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 2.06%   |
| Seagate ST500LM000-1EJ162 500GB           | 2         | 2      | 2.06%   |
| Seagate ST3500418AS 500GB                 | 2         | 2      | 2.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3      | 2.06%   |
| Hitachi HTS542525K9A300 250GB             | 2         | 2      | 2.06%   |
| WDC WDS240G2G0A-00JH30 240GB              | 1         | 1      | 1.03%   |
| WDC WD800JD-75MSA3 80GB                   | 1         | 1      | 1.03%   |
| WDC WD6400BPVT-22HXZT3 640GB              | 1         | 1      | 1.03%   |
| WDC WD5000AAKX-08U6AA0 500GB              | 1         | 1      | 1.03%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1         | 1      | 1.03%   |
| WDC WD3200BPVT-80ZEST0 320GB              | 1         | 1      | 1.03%   |
| WDC WD30PURZ-85AKKY0 3TB                  | 1         | 1      | 1.03%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 1.03%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 1      | 1.03%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 1.03%   |
| WDC WD20EADS-00W4B0 2TB                   | 1         | 1      | 1.03%   |
| WDC WD1600YS-01SHB1 164GB                 | 1         | 1      | 1.03%   |
| WDC WD1600AAJS-60Z0A0 160GB               | 1         | 1      | 1.03%   |
| WDC WD10JPVX-60JC3T1 1TB                  | 1         | 1      | 1.03%   |
| WDC WD10EZEX-60WN4A0 1TB                  | 1         | 1      | 1.03%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 1      | 1.03%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 1.03%   |
| WDC WD10EADS-11M2B2 1TB                   | 1         | 1      | 1.03%   |
| Transcend TS120GSSD220S 120GB             | 1         | 1      | 1.03%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.03%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1      | 1.03%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 1      | 1.03%   |
| Toshiba MK8052GSX 80GB                    | 1         | 1      | 1.03%   |
| Toshiba MK5065GSX 500GB                   | 1         | 1      | 1.03%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 1      | 1.03%   |
| Toshiba MK3259GSXP 320GB                  | 1         | 1      | 1.03%   |
| Toshiba MK1646GSX 160GB                   | 1         | 1      | 1.03%   |
| Toshiba MK1229GSG 120GB                   | 1         | 1      | 1.03%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 1.03%   |
| Toshiba DT01ABA200 2TB                    | 1         | 1      | 1.03%   |
| SSSTC CVB-8D128-HP 128GB                  | 1         | 1      | 1.03%   |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 1.03%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1         | 1      | 1.03%   |
| Seagate ST9250410AS 250GB                 | 1         | 1      | 1.03%   |
| Seagate ST9160827AS 160GB                 | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 29     | 25.81%  |
| WDC                 | 17        | 18     | 18.28%  |
| Hitachi             | 13        | 13     | 13.98%  |
| Toshiba             | 11        | 11     | 11.83%  |
| Samsung Electronics | 6         | 7      | 6.45%   |
| HGST                | 5         | 6      | 5.38%   |
| Maxtor              | 3         | 3      | 3.23%   |
| Crucial             | 3         | 4      | 3.23%   |
| Kingston            | 2         | 2      | 2.15%   |
| Transcend           | 1         | 1      | 1.08%   |
| SSSTC               | 1         | 1      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| Silicon Motion      | 1         | 1      | 1.08%   |
| OCZ                 | 1         | 1      | 1.08%   |
| Micron Technology   | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |
| China               | 1         | 1      | 1.08%   |
| A-DATA Technology   | 1         | 1      | 1.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 29     | 31.58%  |
| WDC                 | 16        | 17     | 21.05%  |
| Hitachi             | 13        | 13     | 17.11%  |
| Toshiba             | 11        | 11     | 14.47%  |
| HGST                | 5         | 6      | 6.58%   |
| Samsung Electronics | 4         | 5      | 5.26%   |
| Maxtor              | 3         | 3      | 3.95%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 84     | 81.32%  |
| SSD  | 14        | 15     | 15.38%  |
| NVMe | 3         | 3      | 3.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 20%     |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 20%     |
| SanDisk pSSD 16GB                 | 1         | 1      | 20%     |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 20%     |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Samsung Electronics | 2         | 2      | 40%     |
| SanDisk             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 315       | 526    | 75%     |
| Malfunc  | 90        | 102    | 21.43%  |
| Detected | 10        | 16     | 2.38%   |
| Failed   | 5         | 5      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 313       | 61.74%  |
| AMD                                     | 63        | 12.43%  |
| Samsung Electronics                     | 35        | 6.9%    |
| SanDisk                                 | 14        | 2.76%   |
| Nvidia                                  | 11        | 2.17%   |
| Silicon Motion                          | 10        | 1.97%   |
| Kingston Technology Company             | 10        | 1.97%   |
| SK hynix                                | 7         | 1.38%   |
| ASMedia Technology                      | 7         | 1.38%   |
| Marvell Technology Group                | 6         | 1.18%   |
| Micron Technology                       | 5         | 0.99%   |
| Micron/Crucial Technology               | 4         | 0.79%   |
| Phison Electronics                      | 3         | 0.59%   |
| JMicron Technology                      | 3         | 0.59%   |
| ADATA Technology                        | 3         | 0.59%   |
| VIA Technologies                        | 2         | 0.39%   |
| Realtek Semiconductor                   | 2         | 0.39%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.39%   |
| Toshiba                                 | 1         | 0.2%    |
| Silicon Integrated Systems [SiS]        | 1         | 0.2%    |
| Shenzhen Unionmemory Information System | 1         | 0.2%    |
| Seagate Technology                      | 1         | 0.2%    |
| OCZ Technology Group                    | 1         | 0.2%    |
| KIOXIA                                  | 1         | 0.2%    |
| Broadcom / LSI                          | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34        | 5.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26        | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 4.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19        | 3.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 18        | 3.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 16        | 2.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14        | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14        | 2.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10        | 1.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9         | 1.54%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.19%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.85%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.85%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 4         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.68%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 335       | 65.94%  |
| NVMe | 93        | 18.31%  |
| IDE  | 61        | 12.01%  |
| RAID | 17        | 3.35%   |
| SAS  | 1         | 0.2%    |
| SCSI | 1         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 337       | 82%     |
| AMD    | 74        | 18%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 7         | 1.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.46%   |
| Intel CPU Version                           | 5         | 1.22%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 5         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 0.97%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4         | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 0.97%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4         | 0.97%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 0.97%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4         | 0.97%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 3         | 0.73%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 3         | 0.73%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.73%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3         | 0.73%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3         | 0.73%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.73%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.73%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.73%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 0.73%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 2         | 0.49%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.49%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2         | 0.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 0.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2         | 0.49%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.49%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 0.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 106       | 25.79%  |
| Intel Core i7           | 58        | 14.11%  |
| Intel Core i3           | 42        | 10.22%  |
| Intel Celeron           | 36        | 8.76%   |
| Intel Core 2 Duo        | 28        | 6.81%   |
| AMD Ryzen 5             | 20        | 4.87%   |
| Other                   | 18        | 4.38%   |
| Intel Xeon              | 13        | 3.16%   |
| AMD Ryzen 7             | 12        | 2.92%   |
| Intel Pentium           | 9         | 2.19%   |
| AMD Ryzen 3             | 9         | 2.19%   |
| Intel Atom              | 6         | 1.46%   |
| Intel Pentium Dual-Core | 5         | 1.22%   |
| AMD Athlon II X2        | 4         | 0.97%   |
| Intel Pentium Silver    | 3         | 0.73%   |
| AMD Phenom II X4        | 3         | 0.73%   |
| AMD A4                  | 3         | 0.73%   |
| Intel Pentium Gold      | 2         | 0.49%   |
| Intel Pentium Dual      | 2         | 0.49%   |
| Intel Genuine           | 2         | 0.49%   |
| Intel Core i9           | 2         | 0.49%   |
| Intel Core 2 Quad       | 2         | 0.49%   |
| Intel Core 2            | 2         | 0.49%   |
| AMD E                   | 2         | 0.49%   |
| AMD Athlon              | 2         | 0.49%   |
| AMD A10                 | 2         | 0.49%   |
| Intel Pentium 4         | 1         | 0.24%   |
| Intel Celeron Dual-Core | 1         | 0.24%   |
| Intel Celeron D         | 1         | 0.24%   |
| AMD Ryzen Embedded      | 1         | 0.24%   |
| AMD Ryzen 9             | 1         | 0.24%   |
| AMD Ryzen 3 PRO         | 1         | 0.24%   |
| AMD Phenom II X6        | 1         | 0.24%   |
| AMD Phenom II X2        | 1         | 0.24%   |
| AMD Phenom II           | 1         | 0.24%   |
| AMD GX                  | 1         | 0.24%   |
| AMD FX                  | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD E1                  | 1         | 0.24%   |
| AMD Athlon X2           | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 177       | 43.07%  |
| 4       | 135       | 32.85%  |
| Unknown | 31        | 7.54%   |
| 6       | 21        | 5.11%   |
| 12      | 15        | 3.65%   |
| 8       | 13        | 3.16%   |
| 16      | 9         | 2.19%   |
| 1       | 7         | 1.7%    |
| 24      | 1         | 0.24%   |
| 14      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 401       | 97.57%  |
| 2       | 9         | 2.19%   |
| Unknown | 1         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 192       | 46.72%  |
| 1       | 184       | 44.77%  |
| Unknown | 35        | 8.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 56        | 13.63%  |
| Haswell       | 44        | 10.71%  |
| IvyBridge     | 42        | 10.22%  |
| SandyBridge   | 37        | 9%      |
| Skylake       | 29        | 7.06%   |
| Penryn        | 29        | 7.06%   |
| Core          | 20        | 4.87%   |
| Zen+          | 18        | 4.38%   |
| Zen 3         | 14        | 3.41%   |
| Westmere      | 13        | 3.16%   |
| Silvermont    | 12        | 2.92%   |
| K10           | 12        | 2.92%   |
| Unknown       | 11        | 2.68%   |
| Broadwell     | 10        | 2.43%   |
| Zen           | 7         | 1.7%    |
| Goldmont plus | 7         | 1.7%    |
| CometLake     | 7         | 1.7%    |
| Bonnell       | 7         | 1.7%    |
| TigerLake     | 6         | 1.46%   |
| Zen 2         | 5         | 1.22%   |
| Piledriver    | 4         | 0.97%   |
| Nehalem       | 4         | 0.97%   |
| Excavator     | 4         | 0.97%   |
| Bobcat        | 4         | 0.97%   |
| Goldmont      | 3         | 0.73%   |
| NetBurst      | 1         | 0.24%   |
| K8 Hammer     | 1         | 0.24%   |
| K10 Llano     | 1         | 0.24%   |
| Jaguar        | 1         | 0.24%   |
| IceLake       | 1         | 0.24%   |
| Bulldozer     | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 263       | 57.17%  |
| Nvidia                           | 98        | 21.3%   |
| AMD                              | 97        | 21.09%  |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Matrox Electronics Systems       | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 6.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 4.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 2.95%   |
| Intel HD Graphics 630                                                                    | 13        | 2.74%   |
| Intel HD Graphics 530                                                                    | 13        | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 2.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.11%   |
| Intel UHD Graphics 620                                                                   | 9         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.47%   |
| Intel HD Graphics 620                                                                    | 7         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.26%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.26%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 1.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.84%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 0.84%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.63%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 0.63%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.63%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 186       | 45.04%  |
| 1 x AMD                  | 76        | 18.4%   |
| 1 x Nvidia               | 64        | 15.5%   |
| 2 x Intel                | 32        | 7.75%   |
| Intel + Nvidia           | 29        | 7.02%   |
| Intel + AMD              | 16        | 3.87%   |
| AMD + Nvidia             | 3         | 0.73%   |
| 2 x AMD                  | 2         | 0.48%   |
| Other                    | 1         | 0.24%   |
| 2 x Nvidia               | 1         | 0.24%   |
| 1 x SiS                  | 1         | 0.24%   |
| 1 x Matrox               | 1         | 0.24%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 348       | 84.47%  |
| Proprietary | 50        | 12.14%  |
| Unknown     | 14        | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 320       | 77.48%  |
| 0.01-0.5   | 21        | 5.08%   |
| 1.01-2.0   | 19        | 4.6%    |
| 3.01-4.0   | 17        | 4.12%   |
| 0.51-1.0   | 17        | 4.12%   |
| 5.01-6.0   | 8         | 1.94%   |
| 7.01-8.0   | 7         | 1.69%   |
| 2.01-3.0   | 2         | 0.48%   |
| 8.01-16.0  | 2         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 13.83%  |
| Samsung Electronics     | 25        | 13.3%   |
| Chimei Innolux          | 12        | 6.38%   |
| LG Display              | 11        | 5.85%   |
| Goldstar                | 11        | 5.85%   |
| Dell                    | 11        | 5.85%   |
| Acer                    | 11        | 5.85%   |
| BOE                     | 10        | 5.32%   |
| BenQ                    | 8         | 4.26%   |
| Hewlett-Packard         | 7         | 3.72%   |
| Lenovo                  | 6         | 3.19%   |
| Ancor Communications    | 6         | 3.19%   |
| AOC                     | 5         | 2.66%   |
| Apple                   | 4         | 2.13%   |
| Philips                 | 3         | 1.6%    |
| InfoVision              | 3         | 1.6%    |
| Chi Mei Optoelectronics | 3         | 1.6%    |
| Unknown                 | 3         | 1.6%    |
| Sharp                   | 2         | 1.06%   |
| LG Electronics          | 2         | 1.06%   |
| ASUSTek Computer        | 2         | 1.06%   |
| Vizio                   | 1         | 0.53%   |
| Semp Toshiba            | 1         | 0.53%   |
| PKB                     | 1         | 0.53%   |
| NEC Computers           | 1         | 0.53%   |
| MStar                   | 1         | 0.53%   |
| MSI                     | 1         | 0.53%   |
| Microstep               | 1         | 0.53%   |
| LG Philips              | 1         | 0.53%   |
| JXC                     | 1         | 0.53%   |
| ITE                     | 1         | 0.53%   |
| Idek Iiyama             | 1         | 0.53%   |
| Fujitsu Siemens         | 1         | 0.53%   |
| Eizo                    | 1         | 0.53%   |
| Daewoo                  | 1         | 0.53%   |
| CVT                     | 1         | 0.53%   |
| CPT                     | 1         | 0.53%   |
| AUS                     | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 3         | 1.6%    |
| Unknown                                                                | 3         | 1.6%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 2         | 1.06%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch               | 2         | 1.06%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch         | 2         | 1.06%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2         | 1.06%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1         | 0.53%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                | 1         | 0.53%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch   | 1         | 0.53%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch    | 1         | 0.53%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch      | 1         | 0.53%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1         | 0.53%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.53%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1         | 0.53%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1         | 0.53%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1         | 0.53%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1         | 0.53%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1         | 0.53%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch      | 1         | 0.53%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1         | 0.53%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1         | 0.53%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1         | 0.53%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1         | 0.53%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1         | 0.53%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 80        | 43.24%  |
| 1366x768 (WXGA)    | 48        | 25.95%  |
| 2560x1440 (QHD)    | 10        | 5.41%   |
| 1600x900 (HD+)     | 8         | 4.32%   |
| 1280x800 (WXGA)    | 5         | 2.7%    |
| 1280x1024 (SXGA)   | 5         | 2.7%    |
| 3840x2160 (4K)     | 4         | 2.16%   |
| 1680x1050 (WSXGA+) | 4         | 2.16%   |
| 1440x900 (WXGA+)   | 4         | 2.16%   |
| 2560x1600          | 3         | 1.62%   |
| 1024x600           | 3         | 1.62%   |
| 1920x1200 (WUXGA)  | 2         | 1.08%   |
| 1400x1050          | 2         | 1.08%   |
| Unknown            | 2         | 1.08%   |
| 5760x2160          | 1         | 0.54%   |
| 3840x1080          | 1         | 0.54%   |
| 3200x1800 (QHD+)   | 1         | 0.54%   |
| 2736x1824          | 1         | 0.54%   |
| 1024x768 (XGA)     | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 16.76%  |
| 13      | 27        | 14.59%  |
| 21      | 22        | 11.89%  |
| Unknown | 19        | 10.27%  |
| 24      | 13        | 7.03%   |
| 27      | 12        | 6.49%   |
| 17      | 9         | 4.86%   |
| 23      | 8         | 4.32%   |
| 19      | 7         | 3.78%   |
| 18      | 7         | 3.78%   |
| 12      | 7         | 3.78%   |
| 14      | 5         | 2.7%    |
| 31      | 4         | 2.16%   |
| 11      | 4         | 2.16%   |
| 20      | 3         | 1.62%   |
| 22      | 2         | 1.08%   |
| 10      | 2         | 1.08%   |
| 52      | 1         | 0.54%   |
| 29      | 1         | 0.54%   |
| 9       | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 27.57%  |
| 401-500     | 38        | 20.54%  |
| 501-600     | 33        | 17.84%  |
| 201-300     | 26        | 14.05%  |
| Unknown     | 19        | 10.27%  |
| 351-400     | 12        | 6.49%   |
| 601-700     | 5         | 2.7%    |
| 1001-1500   | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 76.54%  |
| Unknown | 19        | 10.61%  |
| 16/10   | 16        | 8.94%   |
| 4/3     | 3         | 1.68%   |
| 5/4     | 2         | 1.12%   |
| 6/5     | 1         | 0.56%   |
| 3/2     | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 41        | 22.16%  |
| 91-100         | 28        | 15.14%  |
| 81-90          | 22        | 11.89%  |
| Unknown        | 19        | 10.27%  |
| 151-200        | 13        | 7.03%   |
| 301-350        | 12        | 6.49%   |
| 121-130        | 8         | 4.32%   |
| 61-70          | 7         | 3.78%   |
| 101-110        | 7         | 3.78%   |
| 71-80          | 6         | 3.24%   |
| 141-150        | 6         | 3.24%   |
| 351-500        | 5         | 2.7%    |
| 51-60          | 4         | 2.16%   |
| 41-50          | 3         | 1.62%   |
| 251-300        | 2         | 1.08%   |
| More than 1000 | 1         | 0.54%   |
| 131-140        | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 59        | 32.07%  |
| 51-100        | 53        | 28.8%   |
| 121-160       | 46        | 25%     |
| Unknown       | 19        | 10.33%  |
| More than 240 | 3         | 1.63%   |
| 1-50          | 2         | 1.09%   |
| 161-240       | 2         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 347       | 84.22%  |
| 0     | 49        | 11.89%  |
| 2     | 16        | 3.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 206       | 34.97%  |
| Intel                             | 195       | 33.11%  |
| Qualcomm Atheros                  | 76        | 12.9%   |
| Broadcom                          | 29        | 4.92%   |
| Marvell Technology Group          | 11        | 1.87%   |
| Samsung Electronics               | 10        | 1.7%    |
| Ralink                            | 7         | 1.19%   |
| TP-Link                           | 6         | 1.02%   |
| Ralink Technology                 | 6         | 1.02%   |
| Nvidia                            | 6         | 1.02%   |
| Xiaomi                            | 5         | 0.85%   |
| Sierra Wireless                   | 5         | 0.85%   |
| MediaTek                          | 4         | 0.68%   |
| Ericsson Business Mobile Networks | 3         | 0.51%   |
| Qualcomm                          | 2         | 0.34%   |
| JMicron Technology                | 2         | 0.34%   |
| Huawei Technologies               | 2         | 0.34%   |
| Edimax Technology                 | 2         | 0.34%   |
| D-Link                            | 2         | 0.34%   |
| T & A Mobile Phones               | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.17%   |
| OPPO Electronics                  | 1         | 0.17%   |
| National Semiconductor            | 1         | 0.17%   |
| Google                            | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |
| Atheros                           | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |
| Arduino SA                        | 1         | 0.17%   |
| Accton Technology                 | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 153       | 21.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 30        | 4.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 3.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 1.99%   |
| Intel Wireless 8265 / 8275                                              | 14        | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 1.56%   |
| Intel Wireless 8260                                                     | 10        | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 1.28%   |
| Intel Wireless 3165                                                     | 9         | 1.28%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                   | 9         | 1.28%   |
| Intel Wireless 7265                                                     | 8         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 7         | 0.99%   |
| Intel Wireless 7260                                                     | 7         | 0.99%   |
| Intel Ethernet Controller I225-V                                        | 7         | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.85%   |
| Nvidia MCP79 Ethernet                                                   | 6         | 0.85%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 0.85%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.85%   |
| Intel Ethernet Connection I217-V                                        | 6         | 0.85%   |
| Intel 82579V Gigabit Network Connection                                 | 6         | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.71%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.57%   |
| Intel I211 Gigabit Network Connection                                   | 4         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 128       | 43.84%  |
| Qualcomm Atheros      | 62        | 21.23%  |
| Realtek Semiconductor | 45        | 15.41%  |
| Broadcom              | 24        | 8.22%   |
| Ralink                | 7         | 2.4%    |
| TP-Link               | 6         | 2.05%   |
| Ralink Technology     | 6         | 2.05%   |
| Sierra Wireless       | 3         | 1.03%   |
| MediaTek              | 3         | 1.03%   |
| Edimax Technology     | 2         | 0.68%   |
| D-Link                | 2         | 0.68%   |
| D-Link System         | 1         | 0.34%   |
| Atheros               | 1         | 0.34%   |
| ASUSTek Computer      | 1         | 0.34%   |
| Accton Technology     | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 5.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 4.71%   |
| Intel Wireless 8265 / 8275                                              | 14        | 4.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 4.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 3.7%    |
| Intel Wireless 8260                                                     | 10        | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 3.03%   |
| Intel Wireless 3165                                                     | 9         | 3.03%   |
| Intel Wireless 7265                                                     | 8         | 2.69%   |
| Intel Wireless 7260                                                     | 7         | 2.36%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 2.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.01%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.01%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.67%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 186       | 47.09%  |
| Intel                            | 134       | 33.92%  |
| Qualcomm Atheros                 | 22        | 5.57%   |
| Marvell Technology Group         | 11        | 2.78%   |
| Samsung Electronics              | 10        | 2.53%   |
| Broadcom                         | 10        | 2.53%   |
| Nvidia                           | 6         | 1.52%   |
| Xiaomi                           | 5         | 1.27%   |
| Qualcomm                         | 2         | 0.51%   |
| JMicron Technology               | 2         | 0.51%   |
| Huawei Technologies              | 2         | 0.51%   |
| T & A Mobile Phones              | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| OPPO Electronics                 | 1         | 0.25%   |
| National Semiconductor           | 1         | 0.25%   |
| MediaTek                         | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 153       | 38.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 7.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 6.77%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 2.26%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1.75%   |
| Intel Ethernet Controller I225-V                                  | 7         | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.5%    |
| Nvidia MCP79 Ethernet                                             | 6         | 1.5%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.5%    |
| Intel Ethernet Connection I217-V                                  | 6         | 1.5%    |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1%      |
| Intel I211 Gigabit Network Connection                             | 4         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1%      |
| Intel 82574L Gigabit Network Connection                           | 4         | 1%      |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1%      |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 3         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.75%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.75%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.75%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 378       | 57.27%  |
| WiFi     | 274       | 41.52%  |
| Unknown  | 6         | 0.91%   |
| Modem    | 2         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 253       | 68.75%  |
| WiFi     | 115       | 31.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 223       | 54.13%  |
| 1     | 176       | 42.72%  |
| 0     | 7         | 1.7%    |
| 3     | 6         | 1.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 388       | 93.49%  |
| Yes  | 27        | 6.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 41.63%  |
| Realtek Semiconductor           | 22        | 10.53%  |
| Qualcomm Atheros Communications | 19        | 9.09%   |
| Broadcom                        | 19        | 9.09%   |
| Apple                           | 13        | 6.22%   |
| Cambridge Silicon Radio         | 11        | 5.26%   |
| Foxconn / Hon Hai               | 8         | 3.83%   |
| ASUSTek Computer                | 7         | 3.35%   |
| Lite-On Technology              | 6         | 2.87%   |
| IMC Networks                    | 6         | 2.87%   |
| Hewlett-Packard                 | 3         | 1.44%   |
| TP-Link                         | 2         | 0.96%   |
| Dell                            | 2         | 0.96%   |
| Primax Electronics              | 1         | 0.48%   |
| Fujitsu                         | 1         | 0.48%   |
| Askey Computer                  | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 48        | 22.86%  |
| Intel AX201 Bluetooth                                       | 12        | 5.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 11        | 5.24%   |
| Realtek Bluetooth Adapter                                   | 10        | 4.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 4.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 8         | 3.81%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 2.38%   |
| Intel AX200 Bluetooth                                       | 5         | 2.38%   |
| Apple Bluetooth Host Controller                             | 5         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 4         | 1.9%    |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 1.43%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 1.43%   |
| ASUS BT-270 Bluetooth Adapter                               | 3         | 1.43%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 1.43%   |
| Apple Broadcom Built-in Bluetooth                           | 3         | 1.43%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 0.95%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.95%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 0.95%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.95%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 0.95%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 0.95%   |
| Lite-On Bluetooth USB Module                                | 2         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.95%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 0.95%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 0.95%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 0.95%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 0.95%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.48%   |
| Realtek Bluetooth 5.1 Adapter                               | 1         | 0.48%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.48%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.48%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.48%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 320       | 59.37%  |
| AMD                               | 102       | 18.92%  |
| Nvidia                            | 66        | 12.24%  |
| C-Media Electronics               | 17        | 3.15%   |
| Texas Instruments                 | 5         | 0.93%   |
| Creative Labs                     | 4         | 0.74%   |
| Realtek Semiconductor             | 2         | 0.37%   |
| JMTek                             | 2         | 0.37%   |
| Generalplus Technology            | 2         | 0.37%   |
| Unknown                           | 2         | 0.37%   |
| Yamaha                            | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Razer USA                         | 1         | 0.19%   |
| Phison Electronics                | 1         | 0.19%   |
| OPPO Electronics                  | 1         | 0.19%   |
| M-Audio                           | 1         | 0.19%   |
| KTMicro                           | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| HECATE G2 GAMING HEADSET          | 1         | 0.19%   |
| Harman                            | 1         | 0.19%   |
| GN Netcom                         | 1         | 0.19%   |
| GEMBIRD                           | 1         | 0.19%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.19%   |
| Edifier Technology                | 1         | 0.19%   |
| Creative Technology               | 1         | 0.19%   |
| Conexant Systems                  | 1         | 0.19%   |
| Cambridge Silicon Radio           | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 37        | 5.8%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 29        | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 4.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 2.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 2.66%   |
| Intel 200 Series PCH HD Audio                                                                     | 16        | 2.51%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 2.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 10        | 1.57%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.25%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.25%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.1%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 7         | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 100       | 20.79%  |
| SK hynix            | 66        | 13.72%  |
| Kingston            | 52        | 10.81%  |
| Unknown             | 43        | 8.94%   |
| Micron Technology   | 40        | 8.32%   |
| Crucial             | 28        | 5.82%   |
| Corsair             | 24        | 4.99%   |
| Unknown             | 24        | 4.99%   |
| G.Skill             | 13        | 2.7%    |
| Nanya Technology    | 11        | 2.29%   |
| A-DATA Technology   | 10        | 2.08%   |
| Ramaxel Technology  | 8         | 1.66%   |
| Elpida              | 8         | 1.66%   |
| Patriot             | 6         | 1.25%   |
| Unknown (ABCD)      | 5         | 1.04%   |
| Transcend           | 5         | 1.04%   |
| Smart               | 4         | 0.83%   |
| Apacer              | 4         | 0.83%   |
| Team                | 3         | 0.62%   |
| GOODRAM             | 3         | 0.62%   |
| SHARETRONIC         | 2         | 0.42%   |
| Multilaser          | 2         | 0.42%   |
| Kingmax             | 2         | 0.42%   |
| Atermiter           | 2         | 0.42%   |
| Unknown (8A02)      | 1         | 0.21%   |
| Toshiba             | 1         | 0.21%   |
| Teikon              | 1         | 0.21%   |
| Swissbit            | 1         | 0.21%   |
| Silicon Power       | 1         | 0.21%   |
| SemsoTai            | 1         | 0.21%   |
| Qumo                | 1         | 0.21%   |
| MemoWise            | 1         | 0.21%   |
| Lexar               | 1         | 0.21%   |
| Lenovo              | 1         | 0.21%   |
| Juhor               | 1         | 0.21%   |
| Golden Empire       | 1         | 0.21%   |
| Avant               | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |
| 48spaces            | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 24        | 4.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 0.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 0.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 0.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.59%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s              | 3         | 0.59%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 3         | 0.59%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.39%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 172       | 42.36%  |
| DDR4    | 159       | 39.16%  |
| DDR2    | 37        | 9.11%   |
| Unknown | 21        | 5.17%   |
| LPDDR4  | 7         | 1.72%   |
| SDRAM   | 6         | 1.48%   |
| LPDDR3  | 2         | 0.49%   |
| DDR     | 2         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 228       | 56.16%  |
| DIMM         | 162       | 39.9%   |
| Row Of Chips | 8         | 1.97%   |
| Chip         | 4         | 0.99%   |
| Unknown      | 4         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 155       | 34.37%  |
| 4096  | 139       | 30.82%  |
| 2048  | 87        | 19.29%  |
| 16384 | 41        | 9.09%   |
| 1024  | 25        | 5.54%   |
| 32768 | 4         | 0.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 97        | 22.4%   |
| 1333    | 55        | 12.7%   |
| 2400    | 45        | 10.39%  |
| 3200    | 44        | 10.16%  |
| 2667    | 35        | 8.08%   |
| 2133    | 33        | 7.62%   |
| 667     | 24        | 5.54%   |
| 800     | 20        | 4.62%   |
| 1067    | 19        | 4.39%   |
| Unknown | 13        | 3%      |
| 1334    | 10        | 2.31%   |
| 3600    | 6         | 1.39%   |
| 1066    | 6         | 1.39%   |
| 1867    | 5         | 1.15%   |
| 2666    | 4         | 0.92%   |
| 3000    | 3         | 0.69%   |
| 3733    | 2         | 0.46%   |
| 2048    | 2         | 0.46%   |
| 533     | 2         | 0.46%   |
| 400     | 2         | 0.46%   |
| 4400    | 1         | 0.23%   |
| 3333    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1639    | 1         | 0.23%   |
| 1200    | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet 3390         | 1         | 25%     |
| HP LaserJet 1020         | 1         | 25%     |
| Brother HL-L2300D series | 1         | 25%     |
| Brother DCP-J152W        | 1         | 25%     |

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


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 50%     |
| Canon CanoScan LiDE 120  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 44        | 25%     |
| Bison Electronics                      | 24        | 13.64%  |
| Microdia                               | 15        | 8.52%   |
| IMC Networks                           | 11        | 6.25%   |
| Sunplus Innovation Technology          | 9         | 5.11%   |
| Realtek Semiconductor                  | 9         | 5.11%   |
| Syntek                                 | 6         | 3.41%   |
| Logitech                               | 6         | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.41%   |
| Quanta                                 | 5         | 2.84%   |
| Suyin                                  | 4         | 2.27%   |
| Silicon Motion                         | 4         | 2.27%   |
| Lite-On Technology                     | 4         | 2.27%   |
| Apple                                  | 4         | 2.27%   |
| Alcor Micro                            | 4         | 2.27%   |
| Lenovo                                 | 3         | 1.7%    |
| ALi                                    | 3         | 1.7%    |
| Z-Star Microelectronics                | 2         | 1.14%   |
| Importek                               | 2         | 1.14%   |
| Y Media                                | 1         | 0.57%   |
| Trust                                  | 1         | 0.57%   |
| Supreme Electronics                    | 1         | 0.57%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.57%   |
| Luxvisions Innotech Limited            | 1         | 0.57%   |
| Jiangxi Shinetech Optical              | 1         | 0.57%   |
| Intel                                  | 1         | 0.57%   |
| Genesys Logic                          | 1         | 0.57%   |
| GEMBIRD                                | 1         | 0.57%   |
| DigiTech                               | 1         | 0.57%   |
| Cubeternet                             | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 14        | 7.95%   |
| Bison Integrated Camera                                     | 9         | 5.11%   |
| Microdia Integrated_Webcam_HD                               | 7         | 3.98%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 2.84%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.7%    |
| Microdia USB 2.0 Camera                                     | 3         | 1.7%    |
| Logitech Webcam C270                                        | 3         | 1.7%    |
| Chicony FJ Camera                                           | 3         | 1.7%    |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 1.7%    |
| Bison SunplusIT Integrated Camera                           | 3         | 1.7%    |
| Syntek Lenovo EasyCamera                                    | 2         | 1.14%   |
| Syntek Integrated Camera                                    | 2         | 1.14%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.14%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.14%   |
| Realtek USB Camera                                          | 2         | 1.14%   |
| Lite-On Integrated Camera                                   | 2         | 1.14%   |
| Lenovo Integrated Webcam                                    | 2         | 1.14%   |
| IMC Networks UVC VGA Webcam                                 | 2         | 1.14%   |
| IMC Networks Integrated Webcam                              | 2         | 1.14%   |
| IMC Networks Integrated Camera                              | 2         | 1.14%   |
| IMC Networks EasyCamera                                     | 2         | 1.14%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.14%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.14%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.14%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.14%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.14%   |
| Bison HP Webcam-101                                         | 2         | 1.14%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 1.14%   |
| Apple FaceTime HD Camera                                    | 2         | 1.14%   |
| ALi WebCam                                                  | 2         | 1.14%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.14%   |
| Z-Star Webcam                                               | 1         | 0.57%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.57%   |
| Y Media USB Camera                                          | 1         | 0.57%   |
| Trust Trust Full HD Webcam                                  | 1         | 0.57%   |
| Syntek HP Webcam                                            | 1         | 0.57%   |
| Syntek EasyCamera                                           | 1         | 0.57%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 42.31%  |
| Upek                       | 4         | 15.38%  |
| Elan Microelectronics      | 3         | 11.54%  |
| AuthenTec                  | 3         | 11.54%  |
| STMicroelectronics         | 1         | 3.85%   |
| Shenzhen Goodix Technology | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| FocalTech Systems          | 1         | 3.85%   |
| Fingerprint Cards          | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 4         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 3         | 11.54%  |
| Validity Sensors Synaptics WBDI                                                   | 3         | 11.54%  |
| Elan Fingerprint Sensor                                                           | 3         | 11.54%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 1         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 1         | 3.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                             | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 1         | 3.85%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 3.85%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 3.85%   |
| AuthenTec AES2810                                                                 | 1         | 3.85%   |
| AuthenTec AES2660                                                                 | 1         | 3.85%   |
| AuthenTec AES1660                                                                 | 1         | 3.85%   |

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
| 1     | 202       | 48.91%  |
| 0     | 99        | 23.97%  |
| 2     | 86        | 20.82%  |
| 3     | 22        | 5.33%   |
| 4     | 4         | 0.97%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 263       | 62.47%  |
| Net/wireless             | 56        | 13.3%   |
| Card reader              | 29        | 6.89%   |
| Fingerprint reader       | 26        | 6.18%   |
| Bluetooth                | 22        | 5.23%   |
| Sound                    | 16        | 3.8%    |
| Storage                  | 5         | 1.19%   |
| Network                  | 2         | 0.48%   |
| Net/ethernet             | 1         | 0.24%   |
| Dvb card                 | 1         | 0.24%   |

