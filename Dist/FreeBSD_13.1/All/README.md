FreeBSD 13.1 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_13.1/Desktop/README.md) and [notebooks](/Dist/FreeBSD_13.1/Notebook/README.md).

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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| NOBLEX        | SF20BA                      | Notebook    | [a6a17eb5ca](https://bsd-hardware.info/?probe=a6a17eb5ca) | Jul 21, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | Desktop     | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| Dell          | 0H634K A00                  | Desktop     | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| HP            | 81C6 MVB 0C                 | Server      | [65d2113596](https://bsd-hardware.info/?probe=65d2113596) | Apr 03, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [911a1723a2](https://bsd-hardware.info/?probe=911a1723a2) | Apr 02, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| HP            | 339A                        | Desktop     | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Google        | Stout                       | Notebook    | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Google        | Kohaku                      | Notebook    | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3daad10634](https://bsd-hardware.info/?probe=3daad10634) | Mar 02, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | Desktop     | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| Alienware     | m15                         | Notebook    | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [acff807555](https://bsd-hardware.info/?probe=acff807555) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8d49d50738](https://bsd-hardware.info/?probe=8d49d50738) | Feb 11, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4284c60268](https://bsd-hardware.info/?probe=4284c60268) | Feb 10, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| Samsung       | 700T1C                      | Notebook    | [91d5c568d1](https://bsd-hardware.info/?probe=91d5c568d1) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0b48f96d1e](https://bsd-hardware.info/?probe=0b48f96d1e) | Jan 31, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [21398109dc](https://bsd-hardware.info/?probe=21398109dc) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2098b8808d](https://bsd-hardware.info/?probe=2098b8808d) | Jan 29, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [afeb216c1e](https://bsd-hardware.info/?probe=afeb216c1e) | Jan 25, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| HP            | ProBook 4540s               | Notebook    | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [4471bf6465](https://bsd-hardware.info/?probe=4471bf6465) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [1ead286cbe](https://bsd-hardware.info/?probe=1ead286cbe) | Oct 13, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Dell          | Precision 5510              | Notebook    | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | Notebook    | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | Notebook    | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | Notebook    | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| GVC           | DR 738                      | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | Notebook    | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| HP            | 1825                        | Desktop     | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| Dell          | Precision 5560              | Notebook    | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| Acer          | Veriton X490G               | Desktop     | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | Notebook    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| MouseCompu... | B360M                       | Desktop     | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | Desktop     | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [886522d5e6](https://bsd-hardware.info/?probe=886522d5e6) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [81e9f8506f](https://bsd-hardware.info/?probe=81e9f8506f) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [d82547b583](https://bsd-hardware.info/?probe=d82547b583) | Jul 04, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [a3cba2571b](https://bsd-hardware.info/?probe=a3cba2571b) | Jul 04, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| MSI           | MS-B120                     | Mini pc     | [aa27c1dfd0](https://bsd-hardware.info/?probe=aa27c1dfd0) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | Desktop     | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [ee4d6d5761](https://bsd-hardware.info/?probe=ee4d6d5761) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | Desktop     | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | Desktop     | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Intel         | NUC7i5BNB J31144-306        | Mini pc     | [66f9b621be](https://bsd-hardware.info/?probe=66f9b621be) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [3079ca74a6](https://bsd-hardware.info/?probe=3079ca74a6) | Jun 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b699c2a617](https://bsd-hardware.info/?probe=b699c2a617) | Jun 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [45083c3a78](https://bsd-hardware.info/?probe=45083c3a78) | Jun 15, 2022 |
| Dell          | Latitude E5420              | Notebook    | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | Notebook    | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Dell          | Latitude E5500              | Notebook    | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | Notebook    | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | Notebook    | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| NF-M2S        | ABIT                        | Desktop     | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| System76      | Galago Pro                  | Notebook    | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| PC Engines    | APU3                        | Desktop     | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| HP            | 158A                        | Desktop     | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| Dell          | Precision M4800             | Notebook    | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| GVC           | DR 738                      | Desktop     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| Lenovo        | MAHOBAY 31900004 STD        | All in one  | [a9189728e3](https://bsd-hardware.info/?probe=a9189728e3) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | Notebook    | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [311c32e56e](https://bsd-hardware.info/?probe=311c32e56e) | May 17, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [7189b48418](https://bsd-hardware.info/?probe=7189b48418) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 223       | 96.12%  |
| arm64 | 5         | 2.16%   |
| arm   | 3         | 1.29%   |
| i386  | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 70        | 30.04%  |
| XFCE          | 40        | 17.17%  |
| KDE5          | 37        | 15.88%  |
| GNOME         | 20        | 8.58%   |
| TWM           | 15        | 6.44%   |
| MATE          | 13        | 5.58%   |
| i3            | 8         | 3.43%   |
| Openbox       | 7         | 3%      |
| LXDE          | 4         | 1.72%   |
| Cinnamon      | 3         | 1.29%   |
| LXQt          | 2         | 0.86%   |
| Enlightenment | 2         | 0.86%   |
| AwesomeWM     | 2         | 0.86%   |
| xfwm          | 1         | 0.43%   |
| X-Cinnamon    | 1         | 0.43%   |
| Window Maker  | 1         | 0.43%   |
| plasma        | 1         | 0.43%   |
| Lumina        | 1         | 0.43%   |
| IceWM         | 1         | 0.43%   |
| dwm           | 1         | 0.43%   |
| Compton       | 1         | 0.43%   |
| Budgie        | 1         | 0.43%   |
| bspwm         | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 151       | 65.09%  |
| Console | 71        | 30.6%   |
| Wayland | 9         | 3.88%   |
| Tty     | 1         | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 115       | 49.57%  |
| SDDM    | 40        | 17.24%  |
| SLiM    | 22        | 9.48%   |
| LightDM | 20        | 8.62%   |
| GDM     | 16        | 6.9%    |
| XDM     | 13        | 5.6%    |
| Ly      | 5         | 2.16%   |
| PCDM    | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 162       | 69.53%  |
| en_US           | 29        | 12.45%  |
| Unknown         | 15        | 6.44%   |
| ru_RU           | 11        | 4.72%   |
| zh_CN           | 5         | 2.15%   |
| fr_FR           | 4         | 1.72%   |
| ko_KR           | 1         | 0.43%   |
| ja_JP           | 1         | 0.43%   |
| es_ES           | 1         | 0.43%   |
| en_US.ISO8859-1 | 1         | 0.43%   |
| en_GB           | 1         | 0.43%   |
| en_AU           | 1         | 0.43%   |
| de_DE           | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 176       | 75.54%  |
| BIOS | 57        | 24.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 159       | 68.24%  |
| Ufs  | 74        | 31.76%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 214       | 92.24%  |
| MBR     | 16        | 6.9%    |
| BSD     | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 43        | 18.53%  |
| Dell                    | 36        | 15.52%  |
| ASUSTek Computer        | 29        | 12.5%   |
| Hewlett-Packard         | 18        | 7.76%   |
| Gigabyte Technology     | 11        | 4.74%   |
| Intel                   | 10        | 4.31%   |
| Acer                    | 10        | 4.31%   |
| MSI                     | 9         | 3.88%   |
| ASRock                  | 8         | 3.45%   |
| Unknown                 | 8         | 3.45%   |
| Google                  | 6         | 2.59%   |
| Fujitsu                 | 4         | 1.72%   |
| Apple                   | 4         | 1.72%   |
| TUXEDO                  | 3         | 1.29%   |
| Samsung Electronics     | 3         | 1.29%   |
| Toshiba                 | 2         | 0.86%   |
| System76                | 2         | 0.86%   |
| Supermicro              | 2         | 0.86%   |
| Raspberry Pi Foundation | 2         | 0.86%   |
| ASRockRack              | 2         | 0.86%   |
| Sony                    | 1         | 0.43%   |
| Seeed Studio            | 1         | 0.43%   |
| PC Engines              | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Notebook                | 1         | 0.43%   |
| NOBLEX                  | 1         | 0.43%   |
| NITRINOnet              | 1         | 0.43%   |
| NF-M2S                  | 1         | 0.43%   |
| MouseComputer           | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| Inventec                | 1         | 0.43%   |
| Huanan                  | 1         | 0.43%   |
| GVC                     | 1         | 0.43%   |
| GPD                     | 1         | 0.43%   |
| Fujitsu Siemens         | 1         | 0.43%   |
| Foxconn                 | 1         | 0.43%   |
| Fanless Mini PC         | 1         | 0.43%   |
| BESSTAR Tech            | 1         | 0.43%   |
| AMI                     | 1         | 0.43%   |
| Alienware               | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 8         | 3.45%   |
| ASUS All Series                         | 4         | 1.72%   |
| RPi Raspberry Pi                        | 2         | 0.86%   |
| MSI MS-7817                             | 2         | 0.86%   |
| HP EliteBook 850 G7 Notebook PC         | 2         | 0.86%   |
| Google Peppy                            | 2         | 0.86%   |
| Dell Precision T3600                    | 2         | 0.86%   |
| Dell Precision M4500                    | 2         | 0.86%   |
| Dell Latitude E6420                     | 2         | 0.86%   |
| TUXEDO InfinityBook13V3                 | 1         | 0.43%   |
| TUXEDO InfinityBook Pro 14 Gen6         | 1         | 0.43%   |
| TUXEDO Aura 15 Gen1                     | 1         | 0.43%   |
| Toshiba Satellite L305D                 | 1         | 0.43%   |
| Toshiba Satellite A300                  | 1         | 0.43%   |
| System76 Gazelle                        | 1         | 0.43%   |
| System76 Galago Pro                     | 1         | 0.43%   |
| Supermicro MBD-X8DT6-A-IS018            | 1         | 0.43%   |
| Supermicro Icebreaker 4824              | 1         | 0.43%   |
| Sony VGN-NS21M_S                        | 1         | 0.43%   |
| Seeed Studio ODYSSEY-X86J4105           | 1         | 0.43%   |
| Samsung R530/R730/R540                  | 1         | 0.43%   |
| Samsung 750TDA                          | 1         | 0.43%   |
| Samsung 700T1C                          | 1         | 0.43%   |
| PC Engines APU3                         | 1         | 0.43%   |
| Panasonic CF-30KAPAXAM                  | 1         | 0.43%   |
| Notebook N7x0WU                         | 1         | 0.43%   |
| NOBLEX SF20BA                           | 1         | 0.43%   |
| NITRINOnet M360RUS56                    | 1         | 0.43%   |
| NF-M2S ABIT                             | 1         | 0.43%   |
| MSI MS-B120                             | 1         | 0.43%   |
| MSI MS-7D16                             | 1         | 0.43%   |
| MSI MS-7D09                             | 1         | 0.43%   |
| MSI MS-7D08                             | 1         | 0.43%   |
| MSI MS-7C91                             | 1         | 0.43%   |
| MSI MS-7B86                             | 1         | 0.43%   |
| MSI GF63 Thin 9SC                       | 1         | 0.43%   |
| MouseComputer B360M                     | 1         | 0.43%   |
| LG 17Z990-R.AAC9U1                      | 1         | 0.43%   |
| Lenovo XiaoXinPro-13API 2019 81XD       | 1         | 0.43%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 23        | 9.91%   |
| Dell Latitude                 | 10        | 4.31%   |
| Unknown                       | 8         | 3.45%   |
| Lenovo IdeaPad                | 7         | 3.02%   |
| Dell Precision                | 7         | 3.02%   |
| Dell OptiPlex                 | 7         | 3.02%   |
| Dell Inspiron                 | 6         | 2.59%   |
| ASUS ZenBook                  | 5         | 2.16%   |
| ASUS All                      | 4         | 1.72%   |
| Acer Aspire                   | 4         | 1.72%   |
| HP ProBook                    | 3         | 1.29%   |
| ASUS VivoBook                 | 3         | 1.29%   |
| ASUS ROG                      | 3         | 1.29%   |
| ASUS PRIME                    | 3         | 1.29%   |
| Toshiba Satellite             | 2         | 0.86%   |
| RPi Raspberry                 | 2         | 0.86%   |
| MSI MS-7817                   | 2         | 0.86%   |
| Lenovo ThinkCentre            | 2         | 0.86%   |
| Lenovo Legion                 | 2         | 0.86%   |
| HP ProLiant                   | 2         | 0.86%   |
| HP EliteDesk                  | 2         | 0.86%   |
| HP EliteBook                  | 2         | 0.86%   |
| HP Compaq                     | 2         | 0.86%   |
| Google Peppy                  | 2         | 0.86%   |
| Dell Vostro                   | 2         | 0.86%   |
| Dell G5                       | 2         | 0.86%   |
| Acer Veriton                  | 2         | 0.86%   |
| Acer Nitro                    | 2         | 0.86%   |
| TUXEDO InfinityBook13V3       | 1         | 0.43%   |
| TUXEDO InfinityBook           | 1         | 0.43%   |
| TUXEDO Aura                   | 1         | 0.43%   |
| System76 Gazelle              | 1         | 0.43%   |
| System76 Galago               | 1         | 0.43%   |
| Supermicro MBD-X8DT6-A-IS018  | 1         | 0.43%   |
| Supermicro Icebreaker         | 1         | 0.43%   |
| Sony VGN-NS21M                | 1         | 0.43%   |
| Seeed Studio ODYSSEY-X86J4105 | 1         | 0.43%   |
| Samsung R530                  | 1         | 0.43%   |
| Samsung 750TDA                | 1         | 0.43%   |
| Samsung 700T1C                | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 32        | 13.79%  |
| 2020    | 32        | 13.79%  |
| 2022    | 28        | 12.07%  |
| 2018    | 22        | 9.48%   |
| 2019    | 15        | 6.47%   |
| 2016    | 13        | 5.6%    |
| 2014    | 13        | 5.6%    |
| 2013    | 13        | 5.6%    |
| 2012    | 12        | 5.17%   |
| 2011    | 12        | 5.17%   |
| 2017    | 9         | 3.88%   |
| Unknown | 7         | 3.02%   |
| 2015    | 6         | 2.59%   |
| 2010    | 6         | 2.59%   |
| 2008    | 6         | 2.59%   |
| 2009    | 4         | 1.72%   |
| 2023    | 2         | 0.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 114       | 49.14%  |
| Desktop        | 93        | 40.09%  |
| Mini pc        | 14        | 6.03%   |
| Server         | 5         | 2.16%   |
| System on chip | 2         | 0.86%   |
| Convertible    | 2         | 0.86%   |
| All in one     | 2         | 0.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 224       | 96.55%  |
| Yes  | 8         | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 74        | 31.76%  |
| 16.01-24.0      | 64        | 27.47%  |
| 4.01-8.0        | 32        | 13.73%  |
| 32.01-64.0      | 21        | 9.01%   |
| 64.01-256.0     | 20        | 8.58%   |
| 2.01-3.0        | 8         | 3.43%   |
| 24.01-32.0      | 6         | 2.58%   |
| 0.01-0.5        | 3         | 1.29%   |
| 3.01-4.0        | 2         | 0.86%   |
| More than 256.0 | 1         | 0.43%   |
| 1.01-2.0        | 1         | 0.43%   |
| 0.51-1.0        | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 92        | 39.48%  |
| 0.51-1.0   | 72        | 30.9%   |
| 1.01-2.0   | 41        | 17.6%   |
| 2.01-3.0   | 14        | 6.01%   |
| 3.01-4.0   | 5         | 2.15%   |
| 0          | 4         | 1.72%   |
| 4.01-8.0   | 3         | 1.29%   |
| 24.01-32.0 | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 53.65%  |
| 2      | 49        | 21.03%  |
| 3      | 17        | 7.3%    |
| 0      | 16        | 6.87%   |
| 4      | 12        | 5.15%   |
| 8      | 3         | 1.29%   |
| 10     | 2         | 0.86%   |
| 6      | 2         | 0.86%   |
| 18     | 1         | 0.43%   |
| 16     | 1         | 0.43%   |
| 15     | 1         | 0.43%   |
| 11     | 1         | 0.43%   |
| 9      | 1         | 0.43%   |
| 7      | 1         | 0.43%   |
| 5      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 75.43%  |
| Yes       | 57        | 24.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 80.17%  |
| No        | 46        | 19.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 66.95%  |
| No        | 77        | 33.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 50.86%  |
| No        | 114       | 49.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 56        | 24.03%  |
| Russia      | 27        | 11.59%  |
| Germany     | 16        | 6.87%   |
| France      | 14        | 6.01%   |
| Spain       | 10        | 4.29%   |
| China       | 9         | 3.86%   |
| UK          | 8         | 3.43%   |
| Canada      | 7         | 3%      |
| Italy       | 6         | 2.58%   |
| India       | 6         | 2.58%   |
| Czechia     | 6         | 2.58%   |
| Austria     | 6         | 2.58%   |
| Netherlands | 4         | 1.72%   |
| Japan       | 4         | 1.72%   |
| Australia   | 4         | 1.72%   |
| Thailand    | 3         | 1.29%   |
| Venezuela   | 2         | 0.86%   |
| Turkey      | 2         | 0.86%   |
| Taiwan      | 2         | 0.86%   |
| South Korea | 2         | 0.86%   |
| Romania     | 2         | 0.86%   |
| Philippines | 2         | 0.86%   |
| New Zealand | 2         | 0.86%   |
| Mexico      | 2         | 0.86%   |
| Hungary     | 2         | 0.86%   |
| Hong Kong   | 2         | 0.86%   |
| Chile       | 2         | 0.86%   |
| Bulgaria    | 2         | 0.86%   |
| Belgium     | 2         | 0.86%   |
| Argentina   | 2         | 0.86%   |
| Uruguay     | 1         | 0.43%   |
| Sri Lanka   | 1         | 0.43%   |
| Slovenia    | 1         | 0.43%   |
| Serbia      | 1         | 0.43%   |
| Poland      | 1         | 0.43%   |
| Norway      | 1         | 0.43%   |
| Malaysia    | 1         | 0.43%   |
| Lithuania   | 1         | 0.43%   |
| Latvia      | 1         | 0.43%   |
| Kenya       | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 13        | 5.56%   |
| Vienna            | 5         | 2.14%   |
| Paris             | 4         | 1.71%   |
| Ozersk            | 4         | 1.71%   |
| Frisco            | 4         | 1.71%   |
| Brno              | 4         | 1.71%   |
| Tamm              | 3         | 1.28%   |
| Omaha             | 3         | 1.28%   |
| Madrid            | 3         | 1.28%   |
| Wellington        | 2         | 0.85%   |
| Taipei            | 2         | 0.85%   |
| St Petersburg     | 2         | 0.85%   |
| Redmond           | 2         | 0.85%   |
| Palo Alto         | 2         | 0.85%   |
| Nashville         | 2         | 0.85%   |
| Miercurea-Ciuc    | 2         | 0.85%   |
| Maracaibo         | 2         | 0.85%   |
| London            | 2         | 0.85%   |
| Fayetteville      | 2         | 0.85%   |
| Charlotte         | 2         | 0.85%   |
| Central           | 2         | 0.85%   |
| Carry-le-Rouet    | 2         | 0.85%   |
| Barcelona         | 2         | 0.85%   |
| Zhumadian         | 1         | 0.43%   |
| Zagreb            | 1         | 0.43%   |
| Yashio            | 1         | 0.43%   |
| Yangcheon-gu      | 1         | 0.43%   |
| Xiamen            | 1         | 0.43%   |
| Xi'an             | 1         | 0.43%   |
| Woerdense Verlaat | 1         | 0.43%   |
| Wheatland         | 1         | 0.43%   |
| Wenatchee         | 1         | 0.43%   |
| Waldbrunn         | 1         | 0.43%   |
| Vilnius           | 1         | 0.43%   |
| Villapresente     | 1         | 0.43%   |
| Vaulx-en-Velin    | 1         | 0.43%   |
| Vancouver         | 1         | 0.43%   |
| Valparaíso       | 1         | 0.43%   |
| Valladolid        | 1         | 0.43%   |
| Uiwang-si         | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 69        | 118    | 22.12%  |
| Samsung Electronics | 52        | 68     | 16.67%  |
| Seagate             | 38        | 94     | 12.18%  |
| Crucial             | 20        | 30     | 6.41%   |
| Kingston            | 19        | 20     | 6.09%   |
| Toshiba             | 14        | 22     | 4.49%   |
| Intel               | 10        | 19     | 3.21%   |
| Transcend           | 7         | 7      | 2.24%   |
| SK hynix            | 7         | 7      | 2.24%   |
| PNY                 | 6         | 7      | 1.92%   |
| Hitachi             | 6         | 7      | 1.92%   |
| A-DATA Technology   | 6         | 9      | 1.92%   |
| SanDisk             | 4         | 4      | 1.28%   |
| Gigabyte Technology | 4         | 4      | 1.28%   |
| KIOXIA              | 3         | 3      | 0.96%   |
| Hewlett-Packard     | 3         | 3      | 0.96%   |
| Verbatim            | 2         | 2      | 0.64%   |
| UMIS                | 2         | 2      | 0.64%   |
| Team                | 2         | 2      | 0.64%   |
| SSSTC               | 2         | 2      | 0.64%   |
| Silicon Motion      | 2         | 2      | 0.64%   |
| Phison              | 2         | 2      | 0.64%   |
| Patriot             | 2         | 2      | 0.64%   |
| Netac               | 2         | 2      | 0.64%   |
| Micron Technology   | 2         | 3      | 0.64%   |
| Hikvision           | 2         | 2      | 0.64%   |
| HGST                | 2         | 2      | 0.64%   |
| Apple               | 2         | 2      | 0.64%   |
| XPG                 | 1         | 1      | 0.32%   |
| T-FORCE             | 1         | 1      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| ORICO               | 1         | 1      | 0.32%   |
| OCZ                 | 1         | 1      | 0.32%   |
| MSI                 | 1         | 2      | 0.32%   |
| LITEONIT            | 1         | 1      | 0.32%   |
| LITEON              | 1         | 1      | 0.32%   |
| Lexar               | 1         | 2      | 0.32%   |
| Lenovo              | 1         | 1      | 0.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.32%   |
| HPT                 | 1         | 8      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.1%    |
| Samsung SSD 850 EVO 500GB               | 4         | 1.1%    |
| Crucial CT240BX500SSD1 240GB            | 4         | 1.1%    |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 0.82%   |
| WDC WD30EFRX-68EUZN0 3TB                | 3         | 0.82%   |
| WDC WD30EFRX-68AX9N0 3TB                | 3         | 0.82%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 3         | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.82%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 0.82%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.82%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.82%   |
| Kingston SA400S37240G 240GB             | 3         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.82%   |
| A-DATA SU650 240GB                      | 3         | 0.82%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.55%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.55%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.55%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.55%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.55%   |
| Verbatim Vi550 S3 SSD 256GB             | 2         | 0.55%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.55%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.55%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.55%   |
| Seagate ST4000NM0035-1V4107 4TB         | 2         | 0.55%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.55%   |
| Seagate ST12000VN0008-2PH103 12TB       | 2         | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.55%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.55%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.55%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.55%   |
| Samsung SSD 850 EVO 1TB                 | 2         | 0.55%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.55%   |
| PNY CS900 240GB SSD                     | 2         | 0.55%   |
| PNY CS900 120GB SSD                     | 2         | 0.55%   |
| PNY 120GB SATA SSD                      | 2         | 0.55%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.55%   |
| Kingston SA400S37960G 960GB             | 2         | 0.55%   |
| Kingston SA400S37120G 120GB             | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 48        | 95     | 45.28%  |
| Seagate             | 36        | 92     | 33.96%  |
| Toshiba             | 10        | 17     | 9.43%   |
| Hitachi             | 6         | 7      | 5.66%   |
| HGST                | 2         | 2      | 1.89%   |
| Samsung Electronics | 1         | 4      | 0.94%   |
| HPT                 | 1         | 8      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 37     | 23.39%  |
| Crucial             | 16        | 20     | 12.9%   |
| Kingston            | 12        | 13     | 9.68%   |
| WDC                 | 9         | 9      | 7.26%   |
| Transcend           | 6         | 6      | 4.84%   |
| PNY                 | 6         | 7      | 4.84%   |
| Intel               | 6         | 15     | 4.84%   |
| A-DATA Technology   | 5         | 8      | 4.03%   |
| SanDisk             | 4         | 4      | 3.23%   |
| Verbatim            | 2         | 2      | 1.61%   |
| Toshiba             | 2         | 2      | 1.61%   |
| Patriot             | 2         | 2      | 1.61%   |
| Hikvision           | 2         | 2      | 1.61%   |
| Team                | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| SK hynix            | 1         | 1      | 0.81%   |
| Seagate             | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| ORICO               | 1         | 1      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| MSI                 | 1         | 2      | 0.81%   |
| Micron Technology   | 1         | 2      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| LITEON              | 1         | 1      | 0.81%   |
| Lexar               | 1         | 2      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.81%   |
| Hewlett-Packard     | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| FORESEE             | 1         | 1      | 0.81%   |
| Fanxiang            | 1         | 2      | 0.81%   |
| China               | 1         | 1      | 0.81%   |
| CFD                 | 1         | 1      | 0.81%   |
| BR                  | 1         | 1      | 0.81%   |
| BIWIN               | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 110       | 154    | 39.15%  |
| HDD  | 88        | 227    | 31.32%  |
| NVMe | 83        | 96     | 29.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 166       | 381    | 66.67%  |
| NVMe | 83        | 96     | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 146    | 50.47%  |
| 0.51-1.0   | 63        | 92     | 29.72%  |
| 1.01-2.0   | 19        | 38     | 8.96%   |
| 3.01-4.0   | 8         | 13     | 3.77%   |
| 4.01-10.0  | 6         | 46     | 2.83%   |
| 2.01-3.0   | 5         | 20     | 2.36%   |
| 10.01-20.0 | 4         | 26     | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 80        | 34.19%  |
| 251-500        | 55        | 23.5%   |
| 501-1000       | 40        | 17.09%  |
| 51-100         | 20        | 8.55%   |
| 21-50          | 14        | 5.98%   |
| 1001-2000      | 12        | 5.13%   |
| 1-20           | 5         | 2.14%   |
| More than 3000 | 4         | 1.71%   |
| 2001-3000      | 3         | 1.28%   |
| Unknown        | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 188       | 80.69%  |
| 21-50          | 25        | 10.73%  |
| 51-100         | 8         | 3.43%   |
| 101-250        | 5         | 2.15%   |
| 251-500        | 3         | 1.29%   |
| More than 3000 | 2         | 0.86%   |
| 501-1000       | 1         | 0.43%   |
| Unknown        | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 5.26%   |
| WDC WD6400AAKS-22A7B2 640GB                  | 1         | 1      | 2.63%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 2.63%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.63%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 2.63%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 2.63%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 2.63%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1         | 2      | 2.63%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 2.63%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 2.63%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 2.63%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 2.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 2.63%   |
| Seagate ST500DM002-1ER14C 500GB              | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 2.63%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 2.63%   |
| Phison NETLIST SSD 8GB-001                   | 1         | 1      | 2.63%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 2.63%   |
| LITEON IT LST-16S9G-HP 16GB                  | 1         | 1      | 2.63%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 2.63%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 2.63%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 2.63%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 2.63%   |
| Intel SSDSA2M160G2LE 160GB                   | 1         | 1      | 2.63%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 2.63%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 2.63%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 2.63%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.63%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 2.63%   |
| Fanxiang S101-240GB                          | 1         | 1      | 2.63%   |
| A-DATA Technology SU650 120GB                | 1         | 1      | 2.63%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 12     | 22.22%  |
| Seagate             | 7         | 8      | 19.44%  |
| Hitachi             | 4         | 4      | 11.11%  |
| Kingston            | 3         | 4      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| A-DATA Technology   | 2         | 3      | 5.56%   |
| SPCC                | 1         | 1      | 2.78%   |
| SK hynix            | 1         | 1      | 2.78%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Phison              | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 2      | 2.78%   |
| LITEON              | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| Hewlett-Packard     | 1         | 1      | 2.78%   |
| Fanxiang            | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 8         | 12     | 34.78%  |
| Seagate         | 7         | 8      | 30.43%  |
| Hitachi         | 4         | 4      | 17.39%  |
| Toshiba         | 2         | 2      | 8.7%    |
| HGST            | 1         | 1      | 4.35%   |
| Hewlett-Packard | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 28     | 62.86%  |
| SSD  | 13        | 16     | 37.14%  |

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
| Works    | 198       | 415    | 83.54%  |
| Malfunc  | 33        | 44     | 13.92%  |
| Detected | 6         | 18     | 2.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 157       | 52.86%  |
| AMD                                     | 32        | 10.77%  |
| Samsung Electronics                     | 26        | 8.75%   |
| SanDisk                                 | 16        | 5.39%   |
| Phison Electronics                      | 7         | 2.36%   |
| Kingston Technology Company             | 7         | 2.36%   |
| Silicon Motion                          | 6         | 2.02%   |
| Broadcom / LSI                          | 6         | 2.02%   |
| SK hynix                                | 5         | 1.68%   |
| Micron/Crucial Technology               | 5         | 1.68%   |
| Marvell Technology Group                | 4         | 1.35%   |
| ASMedia Technology                      | 4         | 1.35%   |
| Nvidia                                  | 3         | 1.01%   |
| KIOXIA                                  | 3         | 1.01%   |
| Toshiba                                 | 2         | 0.67%   |
| Solid State Storage Technology          | 2         | 0.67%   |
| Micron Technology                       | 2         | 0.67%   |
| Union Memory (Shenzhen)                 | 1         | 0.34%   |
| Transcend                               | 1         | 0.34%   |
| Silicon Image                           | 1         | 0.34%   |
| Shenzhen Unionmemory Information System | 1         | 0.34%   |
| Seagate Technology                      | 1         | 0.34%   |
| Realtek Semiconductor                   | 1         | 0.34%   |
| JMicron Technology                      | 1         | 0.34%   |
| HighPoint Technologies                  | 1         | 0.34%   |
| Hewlett-Packard                         | 1         | 0.34%   |
| ADATA Technology                        | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 22        | 6.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 2.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 2.5%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 6         | 1.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.56%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.25%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.25%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.25%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.25%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.94%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.94%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.94%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.94%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 0.94%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.63%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.63%   |
| SanDisk WD Green SN350 NVMe SSD 240GB (DRAM-less)                              | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 172       | 58.11%  |
| NVMe | 84        | 28.38%  |
| RAID | 19        | 6.42%   |
| IDE  | 15        | 5.07%   |
| SAS  | 6         | 2.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 185       | 79.74%  |
| AMD    | 39        | 16.81%  |
| ARM    | 8         | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.29%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.29%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.29%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.29%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.29%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.86%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.86%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2         | 0.86%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.86%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.86%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 2         | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.86%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.86%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 0.86%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 0.86%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 0.86%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 2         | 0.86%   |
| Intel Core 2 Duo                        | 2         | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 0.86%   |
| Intel Celeron 2955U @ 1.40GHz           | 2         | 0.86%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 0.86%   |
| ARM Cortex-A72 r0p3                     | 2         | 0.86%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 0.86%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 0.86%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 0.86%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.43%   |
| Intel Xeon Gold 6138 CPU @ 2.00GHz      | 1         | 0.43%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.43%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.43%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.43%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 62        | 26.72%  |
| Intel Core i7          | 41        | 17.67%  |
| Other                  | 18        | 7.76%   |
| Intel Celeron          | 17        | 7.33%   |
| Intel Core i3          | 14        | 6.03%   |
| Intel Xeon             | 13        | 5.6%    |
| Intel Core 2 Duo       | 8         | 3.45%   |
| AMD Ryzen 5            | 8         | 3.45%   |
| AMD Ryzen 7            | 7         | 3.02%   |
| ARM Cortex             | 6         | 2.59%   |
| AMD Ryzen 3            | 5         | 2.16%   |
| Intel Atom             | 4         | 1.72%   |
| AMD Ryzen 9            | 4         | 1.72%   |
| Intel Pentium          | 3         | 1.29%   |
| Intel Xeon Gold        | 2         | 0.86%   |
| AMD Ryzen 7 PRO        | 2         | 0.86%   |
| AMD GX                 | 2         | 0.86%   |
| AMD E2                 | 2         | 0.86%   |
| AMD A8                 | 2         | 0.86%   |
| Intel Pentium Silver   | 1         | 0.43%   |
| Intel Pentium Gold     | 1         | 0.43%   |
| Intel Pentium Dual     | 1         | 0.43%   |
| Intel Genuine          | 1         | 0.43%   |
| Intel Core 2 Quad      | 1         | 0.43%   |
| AMD Ryzen Threadripper | 1         | 0.43%   |
| AMD Phenom II X2       | 1         | 0.43%   |
| AMD FX                 | 1         | 0.43%   |
| AMD EPYC               | 1         | 0.43%   |
| AMD Athlon X2          | 1         | 0.43%   |
| AMD Athlon 64 X2       | 1         | 0.43%   |
| AMD A10                | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 87        | 37.5%   |
| 2       | 71        | 30.6%   |
| 6       | 18        | 7.76%   |
| 8       | 14        | 6.03%   |
| Unknown | 13        | 5.6%    |
| 16      | 12        | 5.17%   |
| 12      | 6         | 2.59%   |
| 64      | 2         | 0.86%   |
| 32      | 2         | 0.86%   |
| 24      | 2         | 0.86%   |
| 1       | 2         | 0.86%   |
| 40      | 1         | 0.43%   |
| 28      | 1         | 0.43%   |
| 20      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 218       | 93.97%  |
| Unknown | 8         | 3.45%   |
| 2       | 6         | 2.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 123       | 53.02%  |
| 1       | 95        | 40.95%  |
| Unknown | 14        | 6.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 47        | 20.17%  |
| Unknown         | 23        | 9.87%   |
| Haswell         | 21        | 9.01%   |
| SandyBridge     | 19        | 8.15%   |
| IvyBridge       | 17        | 7.3%    |
| Skylake         | 13        | 5.58%   |
| TigerLake       | 10        | 4.29%   |
| Broadwell       | 9         | 3.86%   |
| CometLake       | 8         | 3.43%   |
| Zen 3           | 7         | 3%      |
| Zen 2           | 7         | 3%      |
| Westmere        | 6         | 2.58%   |
| Silvermont      | 6         | 2.58%   |
| Penryn          | 6         | 2.58%   |
| Zen+            | 5         | 2.15%   |
| Puma            | 4         | 1.72%   |
| Goldmont plus   | 4         | 1.72%   |
| Core            | 4         | 1.72%   |
| Zen             | 3         | 1.29%   |
| Bonnell         | 3         | 1.29%   |
| Piledriver      | 2         | 0.86%   |
| IceLake         | 2         | 0.86%   |
| P6              | 1         | 0.43%   |
| K8 Hammer       | 1         | 0.43%   |
| K8 & K10 hybrid | 1         | 0.43%   |
| K10             | 1         | 0.43%   |
| Jaguar          | 1         | 0.43%   |
| Goldmont        | 1         | 0.43%   |
| Excavator       | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 145       | 57.31%  |
| Nvidia                               | 54        | 21.34%  |
| AMD                                  | 45        | 17.79%  |
| Matrox Electronics Systems           | 6         | 2.37%   |
| ASPEED Technology                    | 2         | 0.79%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14        | 5.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 3.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 9         | 3.47%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 2.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 7         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.7%    |
| Intel UHD Graphics 620                                                      | 6         | 2.32%   |
| Intel HD Graphics 620                                                       | 5         | 1.93%   |
| Intel HD Graphics 5500                                                      | 5         | 1.93%   |
| Intel HD Graphics 530                                                       | 5         | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 1.54%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 1.54%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4         | 1.54%   |
| AMD Renoir                                                                  | 4         | 1.54%   |
| AMD Lucienne                                                                | 4         | 1.54%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3         | 1.16%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.16%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 1.16%   |
| Intel HD Graphics 630                                                       | 3         | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.16%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 3         | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.77%   |
| Nvidia TU117M                                                               | 2         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.77%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 0.77%   |
| Nvidia GP108BM [GeForce MX250]                                              | 2         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.77%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2         | 0.77%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 112       | 48.28%  |
| 1 x AMD                                  | 35        | 15.09%  |
| 1 x Nvidia                               | 27        | 11.64%  |
| Intel + Nvidia                           | 22        | 9.48%   |
| Other                                    | 10        | 4.31%   |
| 2 x Intel                                | 6         | 2.59%   |
| 1 x Matrox                               | 6         | 2.59%   |
| Intel + AMD                              | 5         | 2.16%   |
| AMD + Nvidia                             | 3         | 1.29%   |
| 2 x AMD                                  | 2         | 0.86%   |
| 1 x ASPEED                               | 2         | 0.86%   |
| 2 x Nvidia                               | 1         | 0.43%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 190       | 81.55%  |
| Proprietary | 32        | 13.73%  |
| Unknown     | 11        | 4.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 186       | 80.17%  |
| 0.51-1.0   | 14        | 6.03%   |
| 1.01-2.0   | 12        | 5.17%   |
| 3.01-4.0   | 6         | 2.59%   |
| 0.01-0.5   | 6         | 2.59%   |
| 7.01-8.0   | 4         | 1.72%   |
| 5.01-6.0   | 3         | 1.29%   |
| 2.01-3.0   | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 11.81%  |
| LG Display              | 16        | 11.11%  |
| BOE                     | 14        | 9.72%   |
| Chimei Innolux          | 12        | 8.33%   |
| AU Optronics            | 11        | 7.64%   |
| Dell                    | 7         | 4.86%   |
| Acer                    | 7         | 4.86%   |
| Lenovo                  | 5         | 3.47%   |
| BenQ                    | 5         | 3.47%   |
| AOC                     | 5         | 3.47%   |
| Goldstar                | 4         | 2.78%   |
| Toshiba                 | 3         | 2.08%   |
| Philips                 | 3         | 2.08%   |
| ViewSonic               | 2         | 1.39%   |
| Sharp                   | 2         | 1.39%   |
| Sceptre Tech            | 2         | 1.39%   |
| Mi                      | 2         | 1.39%   |
| LGD                     | 2         | 1.39%   |
| LG Electronics          | 2         | 1.39%   |
| CSO                     | 2         | 1.39%   |
| ASUSTek Computer        | 2         | 1.39%   |
| Apple                   | 2         | 1.39%   |
| Ancor Communications    | 2         | 1.39%   |
| YTH                     | 1         | 0.69%   |
| Vestel Elektronik       | 1         | 0.69%   |
| USR                     | 1         | 0.69%   |
| Unknown (XXX)           | 1         | 0.69%   |
| Pioneer Electronic      | 1         | 0.69%   |
| Panasonic               | 1         | 0.69%   |
| LG Philips              | 1         | 0.69%   |
| KDC                     | 1         | 0.69%   |
| JDI                     | 1         | 0.69%   |
| IOD                     | 1         | 0.69%   |
| Iiyama                  | 1         | 0.69%   |
| Idek Iiyama             | 1         | 0.69%   |
| HannStar                | 1         | 0.69%   |
| Compal                  | 1         | 0.69%   |
| Chi Mei Optoelectronics | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 2         | 1.36%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.36%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.36%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.36%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 2         | 1.36%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.36%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.36%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch            | 2         | 1.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 2         | 1.36%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.36%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 2         | 1.36%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.68%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.68%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.68%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.68%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch               | 1         | 0.68%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.68%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.68%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.68%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.68%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.68%   |
| Pioneer Electronic LCD Monitor SC-1223 1920x1080                       | 1         | 0.68%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.68%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.68%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.68%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.68%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.68%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 69        | 49.64%  |
| 1366x768 (WXGA)    | 20        | 14.39%  |
| 2560x1440 (QHD)    | 10        | 7.19%   |
| 3840x2160 (4K)     | 9         | 6.47%   |
| 1600x900 (HD+)     | 5         | 3.6%    |
| 1920x1200 (WUXGA)  | 4         | 2.88%   |
| 1280x1024 (SXGA)   | 4         | 2.88%   |
| 2560x1600          | 2         | 1.44%   |
| 2560x1080          | 2         | 1.44%   |
| 1680x1050 (WSXGA+) | 2         | 1.44%   |
| 1280x800 (WXGA)    | 2         | 1.44%   |
| 3440x1440          | 1         | 0.72%   |
| 3200x1800 (QHD+)   | 1         | 0.72%   |
| 2880x1800          | 1         | 0.72%   |
| 2048x1152          | 1         | 0.72%   |
| 1920x540           | 1         | 0.72%   |
| 1440x900 (WXGA+)   | 1         | 0.72%   |
| 1080x2160          | 1         | 0.72%   |
| 1024x768 (XGA)     | 1         | 0.72%   |
| 1024x600           | 1         | 0.72%   |
| Unknown            | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 21.38%  |
| 13      | 29        | 20%     |
| Unknown | 17        | 11.72%  |
| 27      | 14        | 9.66%   |
| 24      | 14        | 9.66%   |
| 21      | 6         | 4.14%   |
| 12      | 6         | 4.14%   |
| 23      | 4         | 2.76%   |
| 31      | 3         | 2.07%   |
| 19      | 3         | 2.07%   |
| 29      | 2         | 1.38%   |
| 20      | 2         | 1.38%   |
| 18      | 2         | 1.38%   |
| 17      | 2         | 1.38%   |
| 64      | 1         | 0.69%   |
| 57      | 1         | 0.69%   |
| 54      | 1         | 0.69%   |
| 42      | 1         | 0.69%   |
| 34      | 1         | 0.69%   |
| 22      | 1         | 0.69%   |
| 14      | 1         | 0.69%   |
| 11      | 1         | 0.69%   |
| 10      | 1         | 0.69%   |
| 5       | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 36.11%  |
| 501-600     | 30        | 20.83%  |
| Unknown     | 17        | 11.81%  |
| 201-300     | 16        | 11.11%  |
| 401-500     | 10        | 6.94%   |
| 601-700     | 7         | 4.86%   |
| 351-400     | 6         | 4.17%   |
| 1001-1500   | 3         | 2.08%   |
| 701-800     | 1         | 0.69%   |
| 901-1000    | 1         | 0.69%   |
| 1-100       | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 71.76%  |
| Unknown | 16        | 12.21%  |
| 16/10   | 12        | 9.16%   |
| 21/9    | 3         | 2.29%   |
| 5/4     | 2         | 1.53%   |
| 6/5     | 1         | 0.76%   |
| 4/3     | 1         | 0.76%   |
| 11/10   | 1         | 0.76%   |
| 0.46    | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 15.86%  |
| 201-250        | 23        | 15.86%  |
| 91-100         | 23        | 15.86%  |
| Unknown        | 17        | 11.72%  |
| 301-350        | 16        | 11.03%  |
| 101-110        | 9         | 6.21%   |
| 71-80          | 7         | 4.83%   |
| 151-200        | 6         | 4.14%   |
| 61-70          | 5         | 3.45%   |
| 351-500        | 4         | 2.76%   |
| More than 1000 | 3         | 2.07%   |
| 251-300        | 2         | 1.38%   |
| 51-60          | 1         | 0.69%   |
| 41-50          | 1         | 0.69%   |
| 1-40           | 1         | 0.69%   |
| 141-150        | 1         | 0.69%   |
| 131-140        | 1         | 0.69%   |
| 121-130        | 1         | 0.69%   |
| 501-1000       | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 44        | 30.99%  |
| 121-160       | 37        | 26.06%  |
| 101-120       | 27        | 19.01%  |
| Unknown       | 17        | 11.97%  |
| 161-240       | 11        | 7.75%   |
| More than 240 | 5         | 3.52%   |
| 1-50          | 1         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 123       | 53.02%  |
| 0     | 91        | 39.22%  |
| 2     | 17        | 7.33%   |
| 3     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 141       | 42.47%  |
| Realtek Semiconductor           | 107       | 32.23%  |
| Qualcomm Atheros                | 32        | 9.64%   |
| Broadcom                        | 16        | 4.82%   |
| TP-Link                         | 4         | 1.2%    |
| Ralink Technology               | 4         | 1.2%    |
| Xiaomi                          | 3         | 0.9%    |
| Marvell Technology Group        | 3         | 0.9%    |
| Samsung Electronics             | 2         | 0.6%    |
| Nvidia                          | 2         | 0.6%    |
| MediaTek                        | 2         | 0.6%    |
| Google                          | 2         | 0.6%    |
| Sierra Wireless                 | 1         | 0.3%    |
| Sagem                           | 1         | 0.3%    |
| Ralink                          | 1         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| Qualcomm                        | 1         | 0.3%    |
| MYRICOM                         | 1         | 0.3%    |
| Mellanox Technologies           | 1         | 0.3%    |
| LG Electronics                  | 1         | 0.3%    |
| IMC Networks                    | 1         | 0.3%    |
| Huawei Technologies             | 1         | 0.3%    |
| HMD Global                      | 1         | 0.3%    |
| D-Link System                   | 1         | 0.3%    |
| Arduino SA                      | 1         | 0.3%    |
| American Megatrends             | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 18.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.49%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.49%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.24%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.75%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.5%    |
| Intel Ethernet Controller I225-V                                  | 6         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1%      |
| Intel Wireless-AC 9260                                            | 4         | 1%      |
| Intel Wireless 7265                                               | 4         | 1%      |
| Intel Wireless 7260                                               | 4         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.75%   |
| Intel Wireless 8260                                               | 3         | 0.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 3         | 0.75%   |
| Intel I350 Gigabit Network Connection                             | 3         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.75%   |
| Intel Ethernet Controller X550                                    | 3         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 52.6%   |
| Qualcomm Atheros                | 31        | 17.92%  |
| Realtek Semiconductor           | 22        | 12.72%  |
| Broadcom                        | 14        | 8.09%   |
| TP-Link                         | 4         | 2.31%   |
| Ralink Technology               | 4         | 2.31%   |
| MediaTek                        | 2         | 1.16%   |
| Sierra Wireless                 | 1         | 0.58%   |
| Sagem                           | 1         | 0.58%   |
| Ralink                          | 1         | 0.58%   |
| Qualcomm Atheros Communications | 1         | 0.58%   |
| IMC Networks                    | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 10        | 5.78%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 5.78%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 4.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 4.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 2.31%   |
| Intel Wireless-AC 9260                                         | 4         | 2.31%   |
| Intel Wireless 7265                                            | 4         | 2.31%   |
| Intel Wireless 7260                                            | 4         | 2.31%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.73%   |
| Intel Wireless 8260                                            | 3         | 1.73%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 1.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 1.73%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.16%   |
| Realtek Bluetooth Adapter                                      | 2         | 1.16%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 2         | 1.16%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.16%   |
| Intel Wireless 3160                                            | 2         | 1.16%   |
| Intel WiFi Link 5100                                           | 2         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.16%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 94        | 45.63%  |
| Intel                    | 88        | 42.72%  |
| Broadcom                 | 5         | 2.43%   |
| Xiaomi                   | 3         | 1.46%   |
| Marvell Technology Group | 3         | 1.46%   |
| Samsung Electronics      | 2         | 0.97%   |
| Qualcomm Atheros         | 2         | 0.97%   |
| Nvidia                   | 2         | 0.97%   |
| Google                   | 2         | 0.97%   |
| Qualcomm                 | 1         | 0.49%   |
| MYRICOM                  | 1         | 0.49%   |
| HMD Global               | 1         | 0.49%   |
| D-Link System            | 1         | 0.49%   |
| American Megatrends      | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 32.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 6.31%   |
| Intel I211 Gigabit Network Connection                             | 9         | 4.05%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 3.15%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.7%    |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.25%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.35%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.35%   |
| Intel I210 Gigabit Network Connection                             | 3         | 1.35%   |
| Intel Ethernet Controller X550                                    | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.9%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.9%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.9%    |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.9%    |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.9%    |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.45%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.45%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.45%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.45%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.45%   |
| Intel Ethernet Connection X722                                    | 1         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 187       | 53.43%  |
| WiFi     | 157       | 44.86%  |
| Modem    | 3         | 0.86%   |
| Unknown  | 3         | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 138       | 64.79%  |
| WiFi     | 75        | 35.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 49.57%  |
| 1     | 85        | 36.64%  |
| 3     | 15        | 6.47%   |
| 0     | 10        | 4.31%   |
| 5     | 3         | 1.29%   |
| 4     | 2         | 0.86%   |
| 7     | 1         | 0.43%   |
| 6     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 82.4%   |
| Yes  | 41        | 17.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 58.68%  |
| Qualcomm Atheros Communications | 12        | 9.92%   |
| Realtek Semiconductor           | 7         | 5.79%   |
| IMC Networks                    | 5         | 4.13%   |
| Dell                            | 4         | 3.31%   |
| Broadcom                        | 4         | 3.31%   |
| Apple                           | 4         | 3.31%   |
| Foxconn / Hon Hai               | 3         | 2.48%   |
| Cambridge Silicon Radio         | 3         | 2.48%   |
| ASUSTek Computer                | 3         | 2.48%   |
| Lite-On Technology              | 2         | 1.65%   |
| Ralink                          | 1         | 0.83%   |
| Creative Technology             | 1         | 0.83%   |
| Alps Electric                   | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 15.7%   |
| Intel AX201 Bluetooth                                       | 19        | 15.7%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 15        | 12.4%   |
| Intel AX200 Bluetooth                                       | 9         | 7.44%   |
| Realtek Bluetooth Adapter                                   | 4         | 3.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 2.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.48%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 2.48%   |
| Apple Bluetooth Host Controller                             | 3         | 2.48%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.65%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.65%   |
| Intel Wireless Bluetooth                                    | 2         | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.65%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.65%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.65%   |
| Dell DW375 Bluetooth Module                                 | 2         | 1.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.83%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.83%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.83%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.83%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 0.83%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.83%   |
| Intel AX210 Bluetooth                                       | 1         | 0.83%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.83%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.83%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.83%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.83%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 162       | 59.78%  |
| AMD                         | 48        | 17.71%  |
| Nvidia                      | 40        | 14.76%  |
| Plantronics                 | 2         | 0.74%   |
| GN Netcom                   | 2         | 0.74%   |
| FiiO Electronics Technology | 2         | 0.74%   |
| XMOS                        | 1         | 0.37%   |
| SteelSeries ApS             | 1         | 0.37%   |
| Sony                        | 1         | 0.37%   |
| Samson Technologies         | 1         | 0.37%   |
| Realtek Semiconductor       | 1         | 0.37%   |
| Razer USA                   | 1         | 0.37%   |
| Micro Star International    | 1         | 0.37%   |
| Lenovo                      | 1         | 0.37%   |
| Kingston Technology         | 1         | 0.37%   |
| Focusrite-Novation          | 1         | 0.37%   |
| Ensoniq                     | 1         | 0.37%   |
| Creative Labs               | 1         | 0.37%   |
| Cambridge Silicon Radio     | 1         | 0.37%   |
| ASUSTek Computer            | 1         | 0.37%   |
| Apple                       | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 5.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 5%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 3.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.88%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.56%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.25%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.25%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.25%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.94%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 0.94%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 60        | 23.17%  |
| SK hynix                     | 51        | 19.69%  |
| Micron Technology            | 26        | 10.04%  |
| Kingston                     | 21        | 8.11%   |
| Crucial                      | 20        | 7.72%   |
| Corsair                      | 14        | 5.41%   |
| Unknown                      | 11        | 4.25%   |
| G.Skill                      | 9         | 3.47%   |
| Unknown                      | 8         | 3.09%   |
| Unknown (ABCD)               | 4         | 1.54%   |
| Ramaxel Technology           | 4         | 1.54%   |
| Elpida                       | 4         | 1.54%   |
| A-DATA Technology            | 4         | 1.54%   |
| Transcend                    | 2         | 0.77%   |
| Patriot Memory (PDP Systems) | 2         | 0.77%   |
| Patriot                      | 2         | 0.77%   |
| Nanya Technology             | 2         | 0.77%   |
| KomputerBay                  | 2         | 0.77%   |
| GOODRAM                      | 2         | 0.77%   |
| Unknown (8A5D)               | 1         | 0.39%   |
| Team                         | 1         | 0.39%   |
| Qimonda                      | 1         | 0.39%   |
| PUSKILL                      | 1         | 0.39%   |
| PNY                          | 1         | 0.39%   |
| Kingmax Semiconductor        | 1         | 0.39%   |
| Kingmax                      | 1         | 0.39%   |
| Hewlett-Packard              | 1         | 0.39%   |
| Goldkey                      | 1         | 0.39%   |
| Apacer                       | 1         | 0.39%   |
| AMD                          | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 8         | 2.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 1.08%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.72%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.72%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.72%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.72%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.72%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.72%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.72%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.72%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 2         | 0.72%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 0.72%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.72%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.36%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.36%   |
| Unknown (8A5D) RAM SKIHOTAR-8GB-2666 8GB SODIMM DDR4 2133MT/s    | 1         | 0.36%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.36%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s              | 1         | 0.36%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s              | 1         | 0.36%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.36%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 0.36%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 106       | 46.7%   |
| DDR3    | 86        | 37.89%  |
| DDR2    | 10        | 4.41%   |
| LPDDR4  | 8         | 3.52%   |
| LPDDR3  | 7         | 3.08%   |
| Unknown | 6         | 2.64%   |
| SDRAM   | 1         | 0.44%   |
| LPDDR5  | 1         | 0.44%   |
| DDR5    | 1         | 0.44%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 125       | 55.56%  |
| DIMM         | 84        | 37.33%  |
| Row Of Chips | 14        | 6.22%   |
| Chip         | 1         | 0.44%   |
| Unknown      | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 90        | 37.04%  |
| 4096  | 73        | 30.04%  |
| 16384 | 38        | 15.64%  |
| 2048  | 27        | 11.11%  |
| 32768 | 13        | 5.35%   |
| 1024  | 2         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 54        | 22.78%  |
| 3200    | 44        | 18.57%  |
| 2400    | 29        | 12.24%  |
| 2667    | 25        | 10.55%  |
| 2133    | 21        | 8.86%   |
| 1333    | 18        | 7.59%   |
| 1334    | 9         | 3.8%    |
| 800     | 5         | 2.11%   |
| 3600    | 4         | 1.69%   |
| 1067    | 4         | 1.69%   |
| Unknown | 3         | 1.27%   |
| 4267    | 2         | 0.84%   |
| 3000    | 2         | 0.84%   |
| 1867    | 2         | 0.84%   |
| 1066    | 2         | 0.84%   |
| 975     | 2         | 0.84%   |
| 667     | 2         | 0.84%   |
| 6400    | 1         | 0.42%   |
| 4800    | 1         | 0.42%   |
| 4266    | 1         | 0.42%   |
| 3400    | 1         | 0.42%   |
| 2048    | 1         | 0.42%   |
| 1866    | 1         | 0.42%   |
| 1596    | 1         | 0.42%   |
| 933     | 1         | 0.42%   |
| 533     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1012 | 1         | 100%    |

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
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 24        | 25.26%  |
| IMC Networks                  | 14        | 14.74%  |
| Sunplus Innovation Technology | 9         | 9.47%   |
| Microdia                      | 9         | 9.47%   |
| Bison Electronics             | 8         | 8.42%   |
| Syntek                        | 5         | 5.26%   |
| Realtek Semiconductor         | 4         | 4.21%   |
| Luxvisions Innotech Limited   | 3         | 3.16%   |
| Quanta                        | 2         | 2.11%   |
| Logitech                      | 2         | 2.11%   |
| Lite-On Technology            | 2         | 2.11%   |
| Z-Star Microelectronics       | 1         | 1.05%   |
| Trust                         | 1         | 1.05%   |
| Supreme Electronics           | 1         | 1.05%   |
| Silicon Motion                | 1         | 1.05%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.05%   |
| Ricoh                         | 1         | 1.05%   |
| OmniVision Technologies       | 1         | 1.05%   |
| Intel                         | 1         | 1.05%   |
| Genesys Logic                 | 1         | 1.05%   |
| DigiTech                      | 1         | 1.05%   |
| ARC International             | 1         | 1.05%   |
| Apple                         | 1         | 1.05%   |
| Alcor Micro                   | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                       | 5         | 5.1%    |
| Bison Integrated Camera                         | 5         | 5.1%    |
| Microdia Integrated_Webcam_HD                   | 4         | 4.08%   |
| IMC Networks EasyCamera                         | 4         | 4.08%   |
| Syntek Integrated Camera                        | 3         | 3.06%   |
| Sunplus Laptop_Integrated_Webcam_FHD            | 3         | 3.06%   |
| Realtek Integrated_Webcam_HD                    | 3         | 3.06%   |
| Chicony Lenovo Integrated Camera (0.3MP)        | 3         | 3.06%   |
| Syntek EasyCamera                               | 2         | 2.04%   |
| Sunplus Integrated_Webcam_HD                    | 2         | 2.04%   |
| Microdia Integrated Webcam                      | 2         | 2.04%   |
| Luxvisions Innotech Limited Integrated Camera   | 2         | 2.04%   |
| IMC Networks Realtek PC Camera                  | 2         | 2.04%   |
| IMC Networks Realtek DMFT RGB                   | 2         | 2.04%   |
| Chicony USB2.0 VGA UVC WebCam                   | 2         | 2.04%   |
| Chicony HP HD Camera                            | 2         | 2.04%   |
| Chicony HD WebCam                               | 2         | 2.04%   |
| Z-Star Lenovo USB 2.0 UVC Camera                | 1         | 1.02%   |
| Trust Trust QHD Webcam                          | 1         | 1.02%   |
| Supreme Integrated Camera                       | 1         | 1.02%   |
| Sunplus Laptop Integrated Webcam HD             | 1         | 1.02%   |
| Sunplus Integrated_Webcam_FHD                   | 1         | 1.02%   |
| Sunplus HP HD Webcam [Fixed]                    | 1         | 1.02%   |
| Sunplus HD WebCam                               | 1         | 1.02%   |
| Silicon Motion WebCam SC-50AFL11C54N            | 1         | 1.02%   |
| Silicon Motion Realtek USB 2.0 PC Camera        | 1         | 1.02%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960  | 1         | 1.02%   |
| Ricoh Integrated Webcam                         | 1         | 1.02%   |
| Realtek Integrated Webcam HD                    | 1         | 1.02%   |
| Quanta VGA WebCam                               | 1         | 1.02%   |
| Quanta HD Webcam                                | 1         | 1.02%   |
| OmniVision Monitor Webcam                       | 1         | 1.02%   |
| Microdia Lenovo EasyCamera                      | 1         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD            | 1         | 1.02%   |
| Microdia JOYACCESS JA-Webcam                    | 1         | 1.02%   |
| Luxvisions Innotech Limited HP Universal Camera | 1         | 1.02%   |
| Logitech Webcam C270                            | 1         | 1.02%   |
| Logitech HD Pro Webcam C920                     | 1         | 1.02%   |
| Lite-On Integrated Camera                       | 1         | 1.02%   |
| Lite-On HP Wide Vision HD Camera                | 1         | 1.02%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 46.67%  |
| Validity Sensors           | 3         | 20%     |
| Upek                       | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |
| DigitalPersona             | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 13.33%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                          | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 6.67%   |
| Synaptics WBDI                                           | 1         | 6.67%   |
| Synaptics UWP WBDI                                       | 1         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 6.67%   |
| Elan Fingerprint Sensor                                  | 1         | 6.67%   |
| DigitalPersona Fingerprint Reader                        | 1         | 6.67%   |

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
| 1     | 85        | 36.48%  |
| 2     | 62        | 26.61%  |
| 0     | 42        | 18.03%  |
| 3     | 34        | 14.59%  |
| 4     | 8         | 3.43%   |
| 6     | 1         | 0.43%   |
| 5     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 157       | 49.68%  |
| Bluetooth                | 64        | 20.25%  |
| Net/wireless             | 33        | 10.44%  |
| Card reader              | 18        | 5.7%    |
| Firewire controller      | 17        | 5.38%   |
| Fingerprint reader       | 14        | 4.43%   |
| Net/ethernet             | 5         | 1.58%   |
| Network                  | 4         | 1.27%   |
| Storage                  | 3         | 0.95%   |
| Sound                    | 1         | 0.32%   |

