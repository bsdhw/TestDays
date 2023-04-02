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

Total: 277

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 217       | 96.02%  |
| arm64 | 5         | 2.21%   |
| arm   | 3         | 1.33%   |
| i386  | 1         | 0.44%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 69        | 30.53%  |
| XFCE          | 40        | 17.7%   |
| KDE5          | 35        | 15.49%  |
| GNOME         | 20        | 8.85%   |
| TWM           | 15        | 6.64%   |
| MATE          | 12        | 5.31%   |
| i3            | 8         | 3.54%   |
| Openbox       | 7         | 3.1%    |
| LXDE          | 3         | 1.33%   |
| Cinnamon      | 3         | 1.33%   |
| LXQt          | 2         | 0.88%   |
| Enlightenment | 2         | 0.88%   |
| AwesomeWM     | 2         | 0.88%   |
| xfwm          | 1         | 0.44%   |
| X-Cinnamon    | 1         | 0.44%   |
| plasma        | 1         | 0.44%   |
| Lumina        | 1         | 0.44%   |
| IceWM         | 1         | 0.44%   |
| dwm           | 1         | 0.44%   |
| Compton       | 1         | 0.44%   |
| bspwm         | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 146       | 64.6%   |
| Console | 70        | 30.97%  |
| Wayland | 9         | 3.98%   |
| Tty     | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 114       | 50.44%  |
| SDDM    | 38        | 16.81%  |
| SLiM    | 22        | 9.73%   |
| LightDM | 19        | 8.41%   |
| GDM     | 15        | 6.64%   |
| XDM     | 13        | 5.75%   |
| Ly      | 4         | 1.77%   |
| PCDM    | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 158       | 69.6%   |
| en_US           | 29        | 12.78%  |
| Unknown         | 13        | 5.73%   |
| ru_RU           | 11        | 4.85%   |
| zh_CN           | 5         | 2.2%    |
| fr_FR           | 4         | 1.76%   |
| ko_KR           | 1         | 0.44%   |
| ja_JP           | 1         | 0.44%   |
| es_ES           | 1         | 0.44%   |
| en_US.ISO8859-1 | 1         | 0.44%   |
| en_GB           | 1         | 0.44%   |
| en_AU           | 1         | 0.44%   |
| de_DE           | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 171       | 75.33%  |
| BIOS | 56        | 24.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 156       | 68.72%  |
| Ufs  | 71        | 31.28%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 208       | 92.04%  |
| MBR     | 16        | 7.08%   |
| BSD     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 42        | 18.58%  |
| Dell                    | 35        | 15.49%  |
| ASUSTek Computer        | 29        | 12.83%  |
| Hewlett-Packard         | 17        | 7.52%   |
| Gigabyte Technology     | 11        | 4.87%   |
| Intel                   | 10        | 4.42%   |
| Acer                    | 10        | 4.42%   |
| MSI                     | 8         | 3.54%   |
| ASRock                  | 8         | 3.54%   |
| Unknown                 | 8         | 3.54%   |
| Google                  | 6         | 2.65%   |
| Fujitsu                 | 4         | 1.77%   |
| Apple                   | 4         | 1.77%   |
| TUXEDO                  | 3         | 1.33%   |
| Samsung Electronics     | 3         | 1.33%   |
| Toshiba                 | 2         | 0.88%   |
| System76                | 2         | 0.88%   |
| Supermicro              | 2         | 0.88%   |
| Raspberry Pi Foundation | 2         | 0.88%   |
| Sony                    | 1         | 0.44%   |
| Seeed Studio            | 1         | 0.44%   |
| PC Engines              | 1         | 0.44%   |
| Panasonic               | 1         | 0.44%   |
| Notebook                | 1         | 0.44%   |
| NITRINOnet              | 1         | 0.44%   |
| NF-M2S                  | 1         | 0.44%   |
| MouseComputer           | 1         | 0.44%   |
| LG Electronics          | 1         | 0.44%   |
| Inventec                | 1         | 0.44%   |
| Huanan                  | 1         | 0.44%   |
| GVC                     | 1         | 0.44%   |
| GPD                     | 1         | 0.44%   |
| Fujitsu Siemens         | 1         | 0.44%   |
| Foxconn                 | 1         | 0.44%   |
| Fanless Mini PC         | 1         | 0.44%   |
| BESSTAR Tech            | 1         | 0.44%   |
| ASRockRack              | 1         | 0.44%   |
| AMI                     | 1         | 0.44%   |
| Alienware               | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 8         | 3.54%   |
| ASUS All Series                         | 4         | 1.77%   |
| RPi Raspberry Pi                        | 2         | 0.88%   |
| MSI MS-7817                             | 2         | 0.88%   |
| HP EliteBook 850 G7 Notebook PC         | 2         | 0.88%   |
| Google Peppy                            | 2         | 0.88%   |
| Dell Precision T3600                    | 2         | 0.88%   |
| Dell Precision M4500                    | 2         | 0.88%   |
| Dell Latitude E6420                     | 2         | 0.88%   |
| TUXEDO InfinityBook13V3                 | 1         | 0.44%   |
| TUXEDO InfinityBook Pro 14 Gen6         | 1         | 0.44%   |
| TUXEDO Aura 15 Gen1                     | 1         | 0.44%   |
| Toshiba Satellite L305D                 | 1         | 0.44%   |
| Toshiba Satellite A300                  | 1         | 0.44%   |
| System76 Gazelle                        | 1         | 0.44%   |
| System76 Galago Pro                     | 1         | 0.44%   |
| Supermicro MBD-X8DT6-A-IS018            | 1         | 0.44%   |
| Supermicro Icebreaker 4824              | 1         | 0.44%   |
| Sony VGN-NS21M_S                        | 1         | 0.44%   |
| Seeed Studio ODYSSEY-X86J4105           | 1         | 0.44%   |
| Samsung R530/R730/R540                  | 1         | 0.44%   |
| Samsung 750TDA                          | 1         | 0.44%   |
| Samsung 700T1C                          | 1         | 0.44%   |
| PC Engines APU3                         | 1         | 0.44%   |
| Panasonic CF-30KAPAXAM                  | 1         | 0.44%   |
| Notebook N7x0WU                         | 1         | 0.44%   |
| NITRINOnet M360RUS56                    | 1         | 0.44%   |
| NF-M2S ABIT                             | 1         | 0.44%   |
| MSI MS-B120                             | 1         | 0.44%   |
| MSI MS-7D09                             | 1         | 0.44%   |
| MSI MS-7D08                             | 1         | 0.44%   |
| MSI MS-7C91                             | 1         | 0.44%   |
| MSI MS-7B86                             | 1         | 0.44%   |
| MSI GF63 Thin 9SC                       | 1         | 0.44%   |
| MouseComputer B360M                     | 1         | 0.44%   |
| LG 17Z990-R.AAC9U1                      | 1         | 0.44%   |
| Lenovo XiaoXinPro-13API 2019 81XD       | 1         | 0.44%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 0.44%   |
| Lenovo ThinkPad X270 20HMCTO1WW         | 1         | 0.44%   |
| Lenovo ThinkPad X260 20F6S0KA00         | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 23        | 10.18%  |
| Dell Latitude                 | 10        | 4.42%   |
| Unknown                       | 8         | 3.54%   |
| Lenovo IdeaPad                | 7         | 3.1%    |
| Dell Precision                | 7         | 3.1%    |
| Dell OptiPlex                 | 6         | 2.65%   |
| Dell Inspiron                 | 6         | 2.65%   |
| ASUS ZenBook                  | 5         | 2.21%   |
| ASUS All                      | 4         | 1.77%   |
| Acer Aspire                   | 4         | 1.77%   |
| HP ProBook                    | 3         | 1.33%   |
| ASUS VivoBook                 | 3         | 1.33%   |
| ASUS ROG                      | 3         | 1.33%   |
| ASUS PRIME                    | 3         | 1.33%   |
| Toshiba Satellite             | 2         | 0.88%   |
| RPi Raspberry                 | 2         | 0.88%   |
| MSI MS-7817                   | 2         | 0.88%   |
| Lenovo ThinkCentre            | 2         | 0.88%   |
| Lenovo Legion                 | 2         | 0.88%   |
| HP ProLiant                   | 2         | 0.88%   |
| HP EliteDesk                  | 2         | 0.88%   |
| HP EliteBook                  | 2         | 0.88%   |
| HP Compaq                     | 2         | 0.88%   |
| Google Peppy                  | 2         | 0.88%   |
| Dell Vostro                   | 2         | 0.88%   |
| Dell G5                       | 2         | 0.88%   |
| Acer Veriton                  | 2         | 0.88%   |
| Acer Nitro                    | 2         | 0.88%   |
| TUXEDO InfinityBook13V3       | 1         | 0.44%   |
| TUXEDO InfinityBook           | 1         | 0.44%   |
| TUXEDO Aura                   | 1         | 0.44%   |
| System76 Gazelle              | 1         | 0.44%   |
| System76 Galago               | 1         | 0.44%   |
| Supermicro MBD-X8DT6-A-IS018  | 1         | 0.44%   |
| Supermicro Icebreaker         | 1         | 0.44%   |
| Sony VGN-NS21M                | 1         | 0.44%   |
| Seeed Studio ODYSSEY-X86J4105 | 1         | 0.44%   |
| Samsung R530                  | 1         | 0.44%   |
| Samsung 750TDA                | 1         | 0.44%   |
| Samsung 700T1C                | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 31        | 13.72%  |
| 2021    | 30        | 13.27%  |
| 2022    | 29        | 12.83%  |
| 2018    | 22        | 9.73%   |
| 2019    | 15        | 6.64%   |
| 2016    | 13        | 5.75%   |
| 2014    | 12        | 5.31%   |
| 2012    | 12        | 5.31%   |
| 2011    | 12        | 5.31%   |
| 2013    | 11        | 4.87%   |
| 2017    | 8         | 3.54%   |
| 2015    | 7         | 3.1%    |
| Unknown | 7         | 3.1%    |
| 2010    | 6         | 2.65%   |
| 2008    | 6         | 2.65%   |
| 2009    | 4         | 1.77%   |
| 2023    | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 112       | 49.56%  |
| Desktop        | 90        | 39.82%  |
| Mini pc        | 14        | 6.19%   |
| Server         | 4         | 1.77%   |
| System on chip | 2         | 0.88%   |
| Convertible    | 2         | 0.88%   |
| All in one     | 2         | 0.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 218       | 96.46%  |
| Yes  | 8         | 3.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 73        | 32.16%  |
| 16.01-24.0      | 62        | 27.31%  |
| 4.01-8.0        | 31        | 13.66%  |
| 32.01-64.0      | 21        | 9.25%   |
| 64.01-256.0     | 19        | 8.37%   |
| 2.01-3.0        | 7         | 3.08%   |
| 24.01-32.0      | 6         | 2.64%   |
| 0.01-0.5        | 3         | 1.32%   |
| 3.01-4.0        | 2         | 0.88%   |
| More than 256.0 | 1         | 0.44%   |
| 1.01-2.0        | 1         | 0.44%   |
| 0.51-1.0        | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 89        | 39.21%  |
| 0.51-1.0   | 70        | 30.84%  |
| 1.01-2.0   | 41        | 18.06%  |
| 2.01-3.0   | 14        | 6.17%   |
| 3.01-4.0   | 5         | 2.2%    |
| 0          | 4         | 1.76%   |
| 4.01-8.0   | 2         | 0.88%   |
| 24.01-32.0 | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 54.63%  |
| 2      | 47        | 20.7%   |
| 3      | 15        | 6.61%   |
| 0      | 15        | 6.61%   |
| 4      | 12        | 5.29%   |
| 8      | 3         | 1.32%   |
| 10     | 2         | 0.88%   |
| 6      | 2         | 0.88%   |
| 18     | 1         | 0.44%   |
| 16     | 1         | 0.44%   |
| 15     | 1         | 0.44%   |
| 11     | 1         | 0.44%   |
| 9      | 1         | 0.44%   |
| 7      | 1         | 0.44%   |
| 5      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 171       | 75.66%  |
| Yes       | 55        | 24.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 80.53%  |
| No        | 44        | 19.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 67.7%   |
| No        | 73        | 32.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 50.88%  |
| No        | 111       | 49.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 54        | 23.79%  |
| Russia      | 27        | 11.89%  |
| Germany     | 16        | 7.05%   |
| France      | 14        | 6.17%   |
| Spain       | 10        | 4.41%   |
| China       | 9         | 3.96%   |
| UK          | 8         | 3.52%   |
| Canada      | 7         | 3.08%   |
| India       | 6         | 2.64%   |
| Czechia     | 6         | 2.64%   |
| Austria     | 6         | 2.64%   |
| Italy       | 5         | 2.2%    |
| Netherlands | 4         | 1.76%   |
| Japan       | 4         | 1.76%   |
| Australia   | 4         | 1.76%   |
| Thailand    | 3         | 1.32%   |
| Venezuela   | 2         | 0.88%   |
| Turkey      | 2         | 0.88%   |
| South Korea | 2         | 0.88%   |
| Philippines | 2         | 0.88%   |
| New Zealand | 2         | 0.88%   |
| Mexico      | 2         | 0.88%   |
| Hungary     | 2         | 0.88%   |
| Hong Kong   | 2         | 0.88%   |
| Chile       | 2         | 0.88%   |
| Bulgaria    | 2         | 0.88%   |
| Belgium     | 2         | 0.88%   |
| Uruguay     | 1         | 0.44%   |
| Taiwan      | 1         | 0.44%   |
| Sri Lanka   | 1         | 0.44%   |
| Slovenia    | 1         | 0.44%   |
| Serbia      | 1         | 0.44%   |
| Romania     | 1         | 0.44%   |
| Poland      | 1         | 0.44%   |
| Norway      | 1         | 0.44%   |
| Malaysia    | 1         | 0.44%   |
| Lithuania   | 1         | 0.44%   |
| Latvia      | 1         | 0.44%   |
| Kenya       | 1         | 0.44%   |
| Israel      | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 13        | 5.7%    |
| Vienna            | 5         | 2.19%   |
| Paris             | 4         | 1.75%   |
| Ozersk            | 4         | 1.75%   |
| Frisco            | 4         | 1.75%   |
| Brno              | 4         | 1.75%   |
| Tamm              | 3         | 1.32%   |
| Omaha             | 3         | 1.32%   |
| Madrid            | 3         | 1.32%   |
| Wellington        | 2         | 0.88%   |
| St Petersburg     | 2         | 0.88%   |
| Redmond           | 2         | 0.88%   |
| Nashville         | 2         | 0.88%   |
| Maracaibo         | 2         | 0.88%   |
| London            | 2         | 0.88%   |
| Fayetteville      | 2         | 0.88%   |
| Charlotte         | 2         | 0.88%   |
| Central           | 2         | 0.88%   |
| Carry-le-Rouet    | 2         | 0.88%   |
| Barcelona         | 2         | 0.88%   |
| Zhumadian         | 1         | 0.44%   |
| Zagreb            | 1         | 0.44%   |
| Yashio            | 1         | 0.44%   |
| Yangcheon-gu      | 1         | 0.44%   |
| Xiamen            | 1         | 0.44%   |
| Xi'an             | 1         | 0.44%   |
| Woerdense Verlaat | 1         | 0.44%   |
| Wheatland         | 1         | 0.44%   |
| Wenatchee         | 1         | 0.44%   |
| Waldbrunn         | 1         | 0.44%   |
| Vilnius           | 1         | 0.44%   |
| Villapresente     | 1         | 0.44%   |
| Vaulx-en-Velin    | 1         | 0.44%   |
| Vancouver         | 1         | 0.44%   |
| Valparaíso       | 1         | 0.44%   |
| Valladolid        | 1         | 0.44%   |
| Uiwang-si         | 1         | 0.44%   |
| Twickenham        | 1         | 0.44%   |
| Turku             | 1         | 0.44%   |
| Tucson            | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 68        | 116    | 22.44%  |
| Samsung Electronics | 52        | 68     | 17.16%  |
| Seagate             | 38        | 94     | 12.54%  |
| Crucial             | 19        | 28     | 6.27%   |
| Kingston            | 18        | 19     | 5.94%   |
| Toshiba             | 14        | 22     | 4.62%   |
| Intel               | 10        | 19     | 3.3%    |
| Transcend           | 7         | 7      | 2.31%   |
| SK hynix            | 7         | 7      | 2.31%   |
| Hitachi             | 6         | 7      | 1.98%   |
| A-DATA Technology   | 6         | 9      | 1.98%   |
| SanDisk             | 4         | 4      | 1.32%   |
| PNY                 | 4         | 5      | 1.32%   |
| Gigabyte Technology | 4         | 4      | 1.32%   |
| KIOXIA              | 3         | 3      | 0.99%   |
| Hewlett-Packard     | 3         | 3      | 0.99%   |
| UMIS                | 2         | 2      | 0.66%   |
| SSSTC               | 2         | 2      | 0.66%   |
| Silicon Motion      | 2         | 2      | 0.66%   |
| Netac               | 2         | 2      | 0.66%   |
| Micron Technology   | 2         | 3      | 0.66%   |
| Hikvision           | 2         | 2      | 0.66%   |
| HGST                | 2         | 2      | 0.66%   |
| Apple               | 2         | 2      | 0.66%   |
| XPG                 | 1         | 1      | 0.33%   |
| Verbatim            | 1         | 1      | 0.33%   |
| Team                | 1         | 1      | 0.33%   |
| T-FORCE             | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Phison              | 1         | 1      | 0.33%   |
| Patriot             | 1         | 1      | 0.33%   |
| ORICO               | 1         | 1      | 0.33%   |
| OCZ                 | 1         | 1      | 0.33%   |
| MSI                 | 1         | 1      | 0.33%   |
| LITEONIT            | 1         | 1      | 0.33%   |
| LITEON              | 1         | 1      | 0.33%   |
| Lexar               | 1         | 2      | 0.33%   |
| Lenovo              | 1         | 1      | 0.33%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.33%   |
| HPT                 | 1         | 8      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.13%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.13%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 0.85%   |
| WDC WD30EFRX-68EUZN0 3TB                | 3         | 0.85%   |
| WDC WD30EFRX-68AX9N0 3TB                | 3         | 0.85%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 3         | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.85%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.85%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.85%   |
| Kingston SA400S37240G 240GB             | 3         | 0.85%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.85%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.85%   |
| A-DATA SU650 240GB                      | 3         | 0.85%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.56%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.56%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.56%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.56%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.56%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.56%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.56%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.56%   |
| Seagate ST4000NM0035-1V4107 4TB         | 2         | 0.56%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.56%   |
| Seagate ST12000VN0008-2PH103 12TB       | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.56%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.56%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.56%   |
| Samsung SSD 850 EVO 1TB                 | 2         | 0.56%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.56%   |
| PNY CS900 240GB SSD                     | 2         | 0.56%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.56%   |
| Kingston SA400S37960G 960GB             | 2         | 0.56%   |
| Kingston SA400S37120G 120GB             | 2         | 0.56%   |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.56%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.56%   |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 48        | 94     | 45.28%  |
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

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 37     | 24.79%  |
| Crucial             | 15        | 19     | 12.82%  |
| Kingston            | 11        | 12     | 9.4%    |
| WDC                 | 8         | 8      | 6.84%   |
| Transcend           | 6         | 6      | 5.13%   |
| Intel               | 6         | 15     | 5.13%   |
| A-DATA Technology   | 5         | 8      | 4.27%   |
| SanDisk             | 4         | 4      | 3.42%   |
| PNY                 | 4         | 5      | 3.42%   |
| Toshiba             | 2         | 2      | 1.71%   |
| Hikvision           | 2         | 2      | 1.71%   |
| Verbatim            | 1         | 1      | 0.85%   |
| Team                | 1         | 1      | 0.85%   |
| SPCC                | 1         | 1      | 0.85%   |
| SK hynix            | 1         | 1      | 0.85%   |
| Seagate             | 1         | 1      | 0.85%   |
| Phison              | 1         | 1      | 0.85%   |
| Patriot             | 1         | 1      | 0.85%   |
| ORICO               | 1         | 1      | 0.85%   |
| OCZ                 | 1         | 1      | 0.85%   |
| MSI                 | 1         | 1      | 0.85%   |
| Micron Technology   | 1         | 2      | 0.85%   |
| LITEONIT            | 1         | 1      | 0.85%   |
| LITEON              | 1         | 1      | 0.85%   |
| Lexar               | 1         | 2      | 0.85%   |
| Lenovo              | 1         | 1      | 0.85%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| Gigabyte Technology | 1         | 1      | 0.85%   |
| FORESEE             | 1         | 1      | 0.85%   |
| Fanxiang            | 1         | 2      | 0.85%   |
| China               | 1         | 1      | 0.85%   |
| CFD                 | 1         | 1      | 0.85%   |
| BR                  | 1         | 1      | 0.85%   |
| BIWIN               | 1         | 1      | 0.85%   |
| Apple               | 1         | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 105       | 146    | 38.46%  |
| HDD  | 88        | 226    | 32.23%  |
| NVMe | 80        | 93     | 29.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 372    | 66.8%   |
| NVMe | 80        | 93     | 33.2%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 137    | 49.04%  |
| 0.51-1.0   | 64        | 92     | 30.77%  |
| 1.01-2.0   | 19        | 38     | 9.13%   |
| 3.01-4.0   | 8         | 13     | 3.85%   |
| 4.01-10.0  | 6         | 46     | 2.88%   |
| 2.01-3.0   | 5         | 20     | 2.4%    |
| 10.01-20.0 | 4         | 26     | 1.92%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 78        | 34.36%  |
| 251-500        | 52        | 22.91%  |
| 501-1000       | 39        | 17.18%  |
| 51-100         | 20        | 8.81%   |
| 21-50          | 14        | 6.17%   |
| 1001-2000      | 12        | 5.29%   |
| 1-20           | 5         | 2.2%    |
| More than 3000 | 3         | 1.32%   |
| 2001-3000      | 3         | 1.32%   |
| Unknown        | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 183       | 80.62%  |
| 21-50          | 24        | 10.57%  |
| 51-100         | 8         | 3.52%   |
| 101-250        | 5         | 2.2%    |
| 251-500        | 3         | 1.32%   |
| More than 3000 | 2         | 0.88%   |
| 501-1000       | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 5.26%   |
| WDC WD6400AAKS-22A7B2 640GB                  | 1         | 1      | 2.63%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 2.63%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.63%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 2.63%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 2.63%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 2.63%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 1         | 1      | 2.63%   |
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

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 11     | 22.22%  |
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

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 8         | 11     | 34.78%  |
| Seagate         | 7         | 8      | 30.43%  |
| Hitachi         | 4         | 4      | 17.39%  |
| Toshiba         | 2         | 2      | 8.7%    |
| HGST            | 1         | 1      | 4.35%   |
| Hewlett-Packard | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 27     | 62.86%  |
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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 193       | 404    | 83.19%  |
| Malfunc  | 33        | 43     | 14.22%  |
| Detected | 6         | 18     | 2.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 152       | 52.78%  |
| AMD                                     | 31        | 10.76%  |
| Samsung Electronics                     | 26        | 9.03%   |
| SanDisk                                 | 16        | 5.56%   |
| Kingston Technology Company             | 7         | 2.43%   |
| Silicon Motion                          | 6         | 2.08%   |
| Broadcom / LSI                          | 6         | 2.08%   |
| SK hynix                                | 5         | 1.74%   |
| Phison Electronics                      | 5         | 1.74%   |
| Micron/Crucial Technology               | 4         | 1.39%   |
| Marvell Technology Group                | 4         | 1.39%   |
| ASMedia Technology                      | 4         | 1.39%   |
| Nvidia                                  | 3         | 1.04%   |
| KIOXIA                                  | 3         | 1.04%   |
| Toshiba                                 | 2         | 0.69%   |
| Solid State Storage Technology          | 2         | 0.69%   |
| Micron Technology                       | 2         | 0.69%   |
| Union Memory (Shenzhen)                 | 1         | 0.35%   |
| Transcend                               | 1         | 0.35%   |
| Silicon Image                           | 1         | 0.35%   |
| Shenzhen Unionmemory Information System | 1         | 0.35%   |
| Seagate Technology                      | 1         | 0.35%   |
| Realtek Semiconductor                   | 1         | 0.35%   |
| JMicron Technology                      | 1         | 0.35%   |
| HighPoint Technologies                  | 1         | 0.35%   |
| Hewlett-Packard                         | 1         | 0.35%   |
| ADATA Technology                        | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 6.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 9         | 2.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.9%    |
| Unknown                                                                        | 9         | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 2.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.29%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.29%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.29%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 0.97%   |
| SanDisk unknown                                                                | 3         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.97%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.97%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.97%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.97%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 0.97%   |
| SK hynix BC511                                                                 | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 168       | 58.54%  |
| NVMe | 81        | 28.22%  |
| RAID | 18        | 6.27%   |
| IDE  | 14        | 4.88%   |
| SAS  | 6         | 2.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 180       | 79.65%  |
| AMD    | 38        | 16.81%  |
| ARM    | 8         | 3.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.32%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 3         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.32%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.32%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.88%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.88%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 2         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 0.88%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.88%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 2         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.88%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 0.88%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 0.88%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 0.88%   |
| Intel Core i3-3240 CPU @ 3.40GHz        | 2         | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 0.88%   |
| Intel Celeron 2955U @ 1.40GHz           | 2         | 0.88%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 2         | 0.88%   |
| ARM Cortex-A72 r0p3                     | 2         | 0.88%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 0.88%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 2         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 0.88%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 0.88%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.44%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.44%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.44%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.44%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.44%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.44%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 62        | 27.43%  |
| Intel Core i7          | 41        | 18.14%  |
| Other                  | 18        | 7.96%   |
| Intel Celeron          | 15        | 6.64%   |
| Intel Xeon             | 13        | 5.75%   |
| Intel Core i3          | 13        | 5.75%   |
| AMD Ryzen 5            | 8         | 3.54%   |
| Intel Core 2 Duo       | 7         | 3.1%    |
| AMD Ryzen 7            | 7         | 3.1%    |
| ARM Cortex             | 6         | 2.65%   |
| AMD Ryzen 3            | 5         | 2.21%   |
| Intel Atom             | 4         | 1.77%   |
| AMD Ryzen 9            | 4         | 1.77%   |
| Intel Pentium          | 3         | 1.33%   |
| AMD Ryzen 7 PRO        | 2         | 0.88%   |
| AMD GX                 | 2         | 0.88%   |
| AMD E2                 | 2         | 0.88%   |
| AMD A8                 | 2         | 0.88%   |
| Intel Xeon Gold        | 1         | 0.44%   |
| Intel Pentium Silver   | 1         | 0.44%   |
| Intel Pentium Gold     | 1         | 0.44%   |
| Intel Pentium Dual     | 1         | 0.44%   |
| Intel Genuine          | 1         | 0.44%   |
| Intel Core 2 Quad      | 1         | 0.44%   |
| AMD Ryzen Threadripper | 1         | 0.44%   |
| AMD Phenom II X2       | 1         | 0.44%   |
| AMD FX                 | 1         | 0.44%   |
| AMD Athlon X2          | 1         | 0.44%   |
| AMD Athlon 64 X2       | 1         | 0.44%   |
| AMD A10                | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 86        | 38.05%  |
| 2       | 68        | 30.09%  |
| 6       | 18        | 7.96%   |
| 8       | 14        | 6.19%   |
| Unknown | 13        | 5.75%   |
| 16      | 12        | 5.31%   |
| 12      | 6         | 2.65%   |
| 32      | 2         | 0.88%   |
| 24      | 2         | 0.88%   |
| 1       | 2         | 0.88%   |
| 64      | 1         | 0.44%   |
| 28      | 1         | 0.44%   |
| 20      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 213       | 94.25%  |
| Unknown | 8         | 3.54%   |
| 2       | 5         | 2.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 121       | 53.54%  |
| 1       | 91        | 40.27%  |
| Unknown | 14        | 6.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 47        | 20.7%   |
| Unknown         | 22        | 9.69%   |
| Haswell         | 21        | 9.25%   |
| SandyBridge     | 19        | 8.37%   |
| IvyBridge       | 17        | 7.49%   |
| Skylake         | 12        | 5.29%   |
| TigerLake       | 10        | 4.41%   |
| Broadwell       | 9         | 3.96%   |
| Zen 3           | 7         | 3.08%   |
| Zen 2           | 7         | 3.08%   |
| CometLake       | 7         | 3.08%   |
| Westmere        | 6         | 2.64%   |
| Zen+            | 5         | 2.2%    |
| Penryn          | 5         | 2.2%    |
| Silvermont      | 4         | 1.76%   |
| Puma            | 4         | 1.76%   |
| Goldmont plus   | 4         | 1.76%   |
| Core            | 4         | 1.76%   |
| Zen             | 3         | 1.32%   |
| Bonnell         | 3         | 1.32%   |
| Piledriver      | 2         | 0.88%   |
| IceLake         | 2         | 0.88%   |
| P6              | 1         | 0.44%   |
| K8 Hammer       | 1         | 0.44%   |
| K8 & K10 hybrid | 1         | 0.44%   |
| K10             | 1         | 0.44%   |
| Jaguar          | 1         | 0.44%   |
| Goldmont        | 1         | 0.44%   |
| Excavator       | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 143       | 57.89%  |
| Nvidia                               | 53        | 21.46%  |
| AMD                                  | 43        | 17.41%  |
| Matrox Electronics Systems           | 6         | 2.43%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.4%    |
| ASPEED Technology                    | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14        | 5.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 9         | 3.56%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 3.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 2.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 7         | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.77%   |
| Intel UHD Graphics 620                                                      | 6         | 2.37%   |
| Intel HD Graphics 620                                                       | 5         | 1.98%   |
| Intel HD Graphics 5500                                                      | 5         | 1.98%   |
| Intel HD Graphics 530                                                       | 5         | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 1.58%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 4         | 1.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.58%   |
| AMD Renoir                                                                  | 4         | 1.58%   |
| AMD Lucienne                                                                | 4         | 1.58%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 3         | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3         | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.19%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 1.19%   |
| Intel HD Graphics 630                                                       | 3         | 1.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.19%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 3         | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.19%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.79%   |
| Nvidia TU117M                                                               | 2         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.79%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 0.79%   |
| Nvidia GP108BM [GeForce MX250]                                              | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.79%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2         | 0.79%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 110       | 48.67%  |
| 1 x AMD                                  | 33        | 14.6%   |
| 1 x Nvidia                               | 26        | 11.5%   |
| Intel + Nvidia                           | 22        | 9.73%   |
| Other                                    | 10        | 4.42%   |
| 2 x Intel                                | 6         | 2.65%   |
| 1 x Matrox                               | 6         | 2.65%   |
| Intel + AMD                              | 5         | 2.21%   |
| AMD + Nvidia                             | 3         | 1.33%   |
| 2 x AMD                                  | 2         | 0.88%   |
| 2 x Nvidia                               | 1         | 0.44%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.44%   |
| 1 x ASPEED                               | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 185       | 81.5%   |
| Proprietary | 31        | 13.66%  |
| Unknown     | 11        | 4.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 181       | 80.09%  |
| 0.51-1.0   | 14        | 6.19%   |
| 1.01-2.0   | 11        | 4.87%   |
| 3.01-4.0   | 6         | 2.65%   |
| 0.01-0.5   | 6         | 2.65%   |
| 7.01-8.0   | 4         | 1.77%   |
| 5.01-6.0   | 3         | 1.33%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 11.97%  |
| LG Display              | 16        | 11.27%  |
| BOE                     | 14        | 9.86%   |
| Chimei Innolux          | 12        | 8.45%   |
| AU Optronics            | 11        | 7.75%   |
| Dell                    | 7         | 4.93%   |
| Acer                    | 7         | 4.93%   |
| Lenovo                  | 5         | 3.52%   |
| BenQ                    | 5         | 3.52%   |
| AOC                     | 5         | 3.52%   |
| Goldstar                | 4         | 2.82%   |
| Toshiba                 | 3         | 2.11%   |
| Philips                 | 3         | 2.11%   |
| ViewSonic               | 2         | 1.41%   |
| Sharp                   | 2         | 1.41%   |
| Sceptre Tech            | 2         | 1.41%   |
| Mi                      | 2         | 1.41%   |
| LGD                     | 2         | 1.41%   |
| LG Electronics          | 2         | 1.41%   |
| CSO                     | 2         | 1.41%   |
| ASUSTek Computer        | 2         | 1.41%   |
| Apple                   | 2         | 1.41%   |
| Ancor Communications    | 2         | 1.41%   |
| YTH                     | 1         | 0.7%    |
| Vestel Elektronik       | 1         | 0.7%    |
| USR                     | 1         | 0.7%    |
| Unknown (XXX)           | 1         | 0.7%    |
| Panasonic               | 1         | 0.7%    |
| LG Philips              | 1         | 0.7%    |
| JDI                     | 1         | 0.7%    |
| IOD                     | 1         | 0.7%    |
| Iiyama                  | 1         | 0.7%    |
| Idek Iiyama             | 1         | 0.7%    |
| HannStar                | 1         | 0.7%    |
| Compal                  | 1         | 0.7%    |
| Chi Mei Optoelectronics | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 1.39%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.39%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.39%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.39%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 2         | 1.39%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.39%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.39%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch            | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 2         | 1.39%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.39%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 2         | 1.39%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.69%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.69%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.69%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.69%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.69%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.69%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.69%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.69%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.69%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.69%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.69%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.69%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.69%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.69%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.69%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.69%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                            | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 68        | 49.64%  |
| 1366x768 (WXGA)    | 19        | 13.87%  |
| 2560x1440 (QHD)    | 10        | 7.3%    |
| 3840x2160 (4K)     | 9         | 6.57%   |
| 1600x900 (HD+)     | 5         | 3.65%   |
| 1920x1200 (WUXGA)  | 4         | 2.92%   |
| 1280x1024 (SXGA)   | 4         | 2.92%   |
| 2560x1600          | 2         | 1.46%   |
| 2560x1080          | 2         | 1.46%   |
| 1680x1050 (WSXGA+) | 2         | 1.46%   |
| 1280x800 (WXGA)    | 2         | 1.46%   |
| 3440x1440          | 1         | 0.73%   |
| 3200x1800 (QHD+)   | 1         | 0.73%   |
| 2880x1800          | 1         | 0.73%   |
| 2048x1152          | 1         | 0.73%   |
| 1920x540           | 1         | 0.73%   |
| 1440x900 (WXGA+)   | 1         | 0.73%   |
| 1080x2160          | 1         | 0.73%   |
| 1024x768 (XGA)     | 1         | 0.73%   |
| 1024x600           | 1         | 0.73%   |
| Unknown            | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 21.83%  |
| 13      | 29        | 20.42%  |
| Unknown | 16        | 11.27%  |
| 27      | 14        | 9.86%   |
| 24      | 13        | 9.15%   |
| 21      | 6         | 4.23%   |
| 12      | 5         | 3.52%   |
| 23      | 4         | 2.82%   |
| 31      | 3         | 2.11%   |
| 19      | 3         | 2.11%   |
| 29      | 2         | 1.41%   |
| 20      | 2         | 1.41%   |
| 18      | 2         | 1.41%   |
| 17      | 2         | 1.41%   |
| 64      | 1         | 0.7%    |
| 57      | 1         | 0.7%    |
| 54      | 1         | 0.7%    |
| 42      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 22      | 1         | 0.7%    |
| 14      | 1         | 0.7%    |
| 11      | 1         | 0.7%    |
| 10      | 1         | 0.7%    |
| 5       | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 36.88%  |
| 501-600     | 29        | 20.57%  |
| Unknown     | 16        | 11.35%  |
| 201-300     | 15        | 10.64%  |
| 401-500     | 10        | 7.09%   |
| 601-700     | 7         | 4.96%   |
| 351-400     | 6         | 4.26%   |
| 1001-1500   | 3         | 2.13%   |
| 701-800     | 1         | 0.71%   |
| 901-1000    | 1         | 0.71%   |
| 1-100       | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 73.44%  |
| Unknown | 15        | 11.72%  |
| 16/10   | 10        | 7.81%   |
| 21/9    | 3         | 2.34%   |
| 5/4     | 2         | 1.56%   |
| 6/5     | 1         | 0.78%   |
| 4/3     | 1         | 0.78%   |
| 11/10   | 1         | 0.78%   |
| 0.46    | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 16.2%   |
| 201-250        | 23        | 16.2%   |
| 91-100         | 23        | 16.2%   |
| 301-350        | 16        | 11.27%  |
| Unknown        | 16        | 11.27%  |
| 101-110        | 9         | 6.34%   |
| 71-80          | 6         | 4.23%   |
| 151-200        | 6         | 4.23%   |
| 61-70          | 5         | 3.52%   |
| 351-500        | 4         | 2.82%   |
| More than 1000 | 3         | 2.11%   |
| 51-60          | 1         | 0.7%    |
| 41-50          | 1         | 0.7%    |
| 1-40           | 1         | 0.7%    |
| 251-300        | 1         | 0.7%    |
| 141-150        | 1         | 0.7%    |
| 131-140        | 1         | 0.7%    |
| 121-130        | 1         | 0.7%    |
| 501-1000       | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 30.94%  |
| 121-160       | 36        | 25.9%   |
| 101-120       | 27        | 19.42%  |
| Unknown       | 16        | 11.51%  |
| 161-240       | 11        | 7.91%   |
| More than 240 | 5         | 3.6%    |
| 1-50          | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 120       | 53.1%   |
| 0     | 88        | 38.94%  |
| 2     | 17        | 7.52%   |
| 3     | 1         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 135       | 41.8%   |
| Realtek Semiconductor           | 105       | 32.51%  |
| Qualcomm Atheros                | 32        | 9.91%   |
| Broadcom                        | 16        | 4.95%   |
| TP-Link                         | 4         | 1.24%   |
| Ralink Technology               | 4         | 1.24%   |
| Xiaomi                          | 3         | 0.93%   |
| Marvell Technology Group        | 3         | 0.93%   |
| Samsung Electronics             | 2         | 0.62%   |
| Nvidia                          | 2         | 0.62%   |
| MediaTek                        | 2         | 0.62%   |
| Google                          | 2         | 0.62%   |
| Sierra Wireless                 | 1         | 0.31%   |
| Sagem                           | 1         | 0.31%   |
| Ralink                          | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| Qualcomm                        | 1         | 0.31%   |
| MYRICOM                         | 1         | 0.31%   |
| Mellanox Technologies           | 1         | 0.31%   |
| LG Electronics                  | 1         | 0.31%   |
| IMC Networks                    | 1         | 0.31%   |
| Huawei Technologies             | 1         | 0.31%   |
| HMD Global                      | 1         | 0.31%   |
| D-Link System                   | 1         | 0.31%   |
| Arduino SA                      | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 18.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.6%    |
| Intel Wireless 8265 / 8275                                        | 10        | 2.57%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.57%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.31%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.8%    |
| Intel 82574L Gigabit Network Connection                           | 7         | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.29%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.03%   |
| Intel Wireless-AC 9260                                            | 4         | 1.03%   |
| Intel Wireless 7265                                               | 4         | 1.03%   |
| Intel Wireless 7260                                               | 4         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.77%   |
| Intel Wireless 8260                                               | 3         | 0.77%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 3         | 0.77%   |
| Intel I350 Gigabit Network Connection                             | 3         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.51%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.51%   |
| Realtek Bluetooth Adapter                                         | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 51.76%  |
| Qualcomm Atheros                | 31        | 18.24%  |
| Realtek Semiconductor           | 22        | 12.94%  |
| Broadcom                        | 14        | 8.24%   |
| TP-Link                         | 4         | 2.35%   |
| Ralink Technology               | 4         | 2.35%   |
| MediaTek                        | 2         | 1.18%   |
| Sierra Wireless                 | 1         | 0.59%   |
| Sagem                           | 1         | 0.59%   |
| Ralink                          | 1         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |
| IMC Networks                    | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 10        | 5.88%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 5.88%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 4.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 2.35%   |
| Intel Wireless-AC 9260                                         | 4         | 2.35%   |
| Intel Wireless 7265                                            | 4         | 2.35%   |
| Intel Wireless 7260                                            | 4         | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 2.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.76%   |
| Intel Wireless 8260                                            | 3         | 1.76%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 1.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 1.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.18%   |
| Realtek Bluetooth Adapter                                      | 2         | 1.18%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 2         | 1.18%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.18%   |
| Intel WiFi Link 5100                                           | 2         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.18%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.18%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.18%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.18%   |
| TP-Link Wireless MU-MIMO USB Adapter                           | 1         | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 93        | 46.27%  |
| Intel                    | 85        | 42.29%  |
| Broadcom                 | 5         | 2.49%   |
| Xiaomi                   | 3         | 1.49%   |
| Marvell Technology Group | 3         | 1.49%   |
| Samsung Electronics      | 2         | 1%      |
| Qualcomm Atheros         | 2         | 1%      |
| Nvidia                   | 2         | 1%      |
| Google                   | 2         | 1%      |
| Qualcomm                 | 1         | 0.5%    |
| MYRICOM                  | 1         | 0.5%    |
| HMD Global               | 1         | 0.5%    |
| D-Link System            | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 33.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 6.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 6.54%   |
| Intel I211 Gigabit Network Connection                             | 9         | 4.21%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 3.27%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.8%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.8%    |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.34%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.4%    |
| Intel I350 Gigabit Network Connection                             | 3         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.93%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.93%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Controller X550                                    | 2         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.93%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.47%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.47%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.47%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.47%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.47%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 183       | 53.51%  |
| WiFi     | 154       | 45.03%  |
| Modem    | 3         | 0.88%   |
| Unknown  | 2         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 134       | 65.05%  |
| WiFi     | 72        | 34.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 113       | 50%     |
| 1     | 83        | 36.73%  |
| 3     | 13        | 5.75%   |
| 0     | 10        | 4.42%   |
| 5     | 3         | 1.33%   |
| 4     | 2         | 0.88%   |
| 7     | 1         | 0.44%   |
| 6     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 82.82%  |
| Yes  | 39        | 17.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 57.63%  |
| Qualcomm Atheros Communications | 12        | 10.17%  |
| Realtek Semiconductor           | 7         | 5.93%   |
| IMC Networks                    | 5         | 4.24%   |
| Dell                            | 4         | 3.39%   |
| Broadcom                        | 4         | 3.39%   |
| Apple                           | 4         | 3.39%   |
| Foxconn / Hon Hai               | 3         | 2.54%   |
| Cambridge Silicon Radio         | 3         | 2.54%   |
| ASUSTek Computer                | 3         | 2.54%   |
| Lite-On Technology              | 2         | 1.69%   |
| Ralink                          | 1         | 0.85%   |
| Creative Technology             | 1         | 0.85%   |
| Alps Electric                   | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                       | 18        | 15.25%  |
| Intel Bluetooth wireless interface                          | 17        | 14.41%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 15        | 12.71%  |
| Intel AX200 Bluetooth                                       | 9         | 7.63%   |
| Realtek Bluetooth Adapter                                   | 4         | 3.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 2.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.54%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 2.54%   |
| Apple Bluetooth Host Controller                             | 3         | 2.54%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 2         | 1.69%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.69%   |
| Intel Wireless Bluetooth                                    | 2         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.69%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 1.69%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 1.69%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.69%   |
| Dell DW375 Bluetooth Module                                 | 2         | 1.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.85%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.85%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.85%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 0.85%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.85%   |
| Intel AX210 Bluetooth                                       | 1         | 0.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.85%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.85%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.85%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.85%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.85%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 157       | 59.92%  |
| AMD                         | 46        | 17.56%  |
| Nvidia                      | 39        | 14.89%  |
| Plantronics                 | 2         | 0.76%   |
| GN Netcom                   | 2         | 0.76%   |
| FiiO Electronics Technology | 2         | 0.76%   |
| XMOS                        | 1         | 0.38%   |
| SteelSeries ApS             | 1         | 0.38%   |
| Sony                        | 1         | 0.38%   |
| Realtek Semiconductor       | 1         | 0.38%   |
| Razer USA                   | 1         | 0.38%   |
| Micro Star International    | 1         | 0.38%   |
| Lenovo                      | 1         | 0.38%   |
| Kingston Technology         | 1         | 0.38%   |
| Focusrite-Novation          | 1         | 0.38%   |
| Ensoniq                     | 1         | 0.38%   |
| Creative Labs               | 1         | 0.38%   |
| Cambridge Silicon Radio     | 1         | 0.38%   |
| ASUSTek Computer            | 1         | 0.38%   |
| Apple                       | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 5.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 5.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 3.54%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 2.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 2.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.93%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.61%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.61%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.29%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.29%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.96%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.96%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 0.96%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.64%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 59        | 23.23%  |
| SK hynix                     | 51        | 20.08%  |
| Micron Technology            | 25        | 9.84%   |
| Kingston                     | 20        | 7.87%   |
| Crucial                      | 20        | 7.87%   |
| Corsair                      | 14        | 5.51%   |
| Unknown                      | 11        | 4.33%   |
| G.Skill                      | 9         | 3.54%   |
| Unknown                      | 8         | 3.15%   |
| Unknown (ABCD)               | 4         | 1.57%   |
| Ramaxel Technology           | 4         | 1.57%   |
| Elpida                       | 4         | 1.57%   |
| A-DATA Technology            | 4         | 1.57%   |
| Transcend                    | 2         | 0.79%   |
| Patriot                      | 2         | 0.79%   |
| Nanya Technology             | 2         | 0.79%   |
| KomputerBay                  | 2         | 0.79%   |
| GOODRAM                      | 2         | 0.79%   |
| Unknown (8A5D)               | 1         | 0.39%   |
| Team                         | 1         | 0.39%   |
| Qimonda                      | 1         | 0.39%   |
| PUSKILL                      | 1         | 0.39%   |
| PNY                          | 1         | 0.39%   |
| Patriot Memory (PDP Systems) | 1         | 0.39%   |
| Kingmax Semiconductor        | 1         | 0.39%   |
| Kingmax                      | 1         | 0.39%   |
| Hewlett-Packard              | 1         | 0.39%   |
| Apacer                       | 1         | 0.39%   |
| AMD                          | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 8         | 2.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.11%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 1.11%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 2         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.74%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.74%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.74%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.74%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.74%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.74%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.74%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 2         | 0.74%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 0.74%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.74%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.37%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.37%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.37%   |
| Unknown (8A5D) RAM SKIHOTAR-8GB-2666 8GB SODIMM DDR4 2133MT/s    | 1         | 0.37%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.37%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s              | 1         | 0.37%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s              | 1         | 0.37%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.37%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 0.37%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 46.85%  |
| DDR3    | 85        | 38.29%  |
| DDR2    | 9         | 4.05%   |
| LPDDR4  | 8         | 3.6%    |
| LPDDR3  | 7         | 3.15%   |
| Unknown | 6         | 2.7%    |
| SDRAM   | 1         | 0.45%   |
| LPDDR5  | 1         | 0.45%   |
| DDR     | 1         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 124       | 56.36%  |
| DIMM         | 80        | 36.36%  |
| Row Of Chips | 14        | 6.36%   |
| Chip         | 1         | 0.45%   |
| Unknown      | 1         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 89        | 37.55%  |
| 4096  | 72        | 30.38%  |
| 16384 | 36        | 15.19%  |
| 2048  | 26        | 10.97%  |
| 32768 | 12        | 5.06%   |
| 1024  | 2         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 53        | 22.84%  |
| 3200    | 43        | 18.53%  |
| 2400    | 27        | 11.64%  |
| 2667    | 23        | 9.91%   |
| 2133    | 22        | 9.48%   |
| 1333    | 18        | 7.76%   |
| 1334    | 9         | 3.88%   |
| 3600    | 4         | 1.72%   |
| 1067    | 4         | 1.72%   |
| 800     | 4         | 1.72%   |
| Unknown | 3         | 1.29%   |
| 4267    | 2         | 0.86%   |
| 3000    | 2         | 0.86%   |
| 2666    | 2         | 0.86%   |
| 1867    | 2         | 0.86%   |
| 1066    | 2         | 0.86%   |
| 975     | 2         | 0.86%   |
| 667     | 2         | 0.86%   |
| 6400    | 1         | 0.43%   |
| 4266    | 1         | 0.43%   |
| 3400    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 1866    | 1         | 0.43%   |
| 1596    | 1         | 0.43%   |
| 933     | 1         | 0.43%   |
| 533     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1012 | 1         | 100%    |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 23        | 25%     |
| IMC Networks                  | 14        | 15.22%  |
| Sunplus Innovation Technology | 9         | 9.78%   |
| Microdia                      | 8         | 8.7%    |
| Bison Electronics             | 8         | 8.7%    |
| Syntek                        | 5         | 5.43%   |
| Realtek Semiconductor         | 4         | 4.35%   |
| Luxvisions Innotech Limited   | 3         | 3.26%   |
| Quanta                        | 2         | 2.17%   |
| Logitech                      | 2         | 2.17%   |
| Lite-On Technology            | 2         | 2.17%   |
| Z-Star Microelectronics       | 1         | 1.09%   |
| Supreme Electronics           | 1         | 1.09%   |
| Silicon Motion                | 1         | 1.09%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.09%   |
| Ricoh                         | 1         | 1.09%   |
| OmniVision Technologies       | 1         | 1.09%   |
| Intel                         | 1         | 1.09%   |
| Genesys Logic                 | 1         | 1.09%   |
| DigiTech                      | 1         | 1.09%   |
| ARC International             | 1         | 1.09%   |
| Apple                         | 1         | 1.09%   |
| Alcor Micro                   | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                       | 5         | 5.26%   |
| Bison Integrated Camera                         | 5         | 5.26%   |
| Microdia Integrated_Webcam_HD                   | 4         | 4.21%   |
| IMC Networks EasyCamera                         | 4         | 4.21%   |
| Syntek Integrated Camera                        | 3         | 3.16%   |
| Sunplus Laptop_Integrated_Webcam_FHD            | 3         | 3.16%   |
| Realtek Integrated_Webcam_HD                    | 3         | 3.16%   |
| Chicony Lenovo Integrated Camera (0.3MP)        | 3         | 3.16%   |
| Syntek EasyCamera                               | 2         | 2.11%   |
| Sunplus Integrated_Webcam_HD                    | 2         | 2.11%   |
| Microdia Integrated Webcam                      | 2         | 2.11%   |
| Luxvisions Innotech Limited Integrated Camera   | 2         | 2.11%   |
| IMC Networks Realtek PC Camera                  | 2         | 2.11%   |
| IMC Networks Realtek DMFT RGB                   | 2         | 2.11%   |
| Chicony USB2.0 VGA UVC WebCam                   | 2         | 2.11%   |
| Chicony HP HD Camera                            | 2         | 2.11%   |
| Chicony HD WebCam                               | 2         | 2.11%   |
| Z-Star Lenovo USB 2.0 UVC Camera                | 1         | 1.05%   |
| Supreme Integrated Camera                       | 1         | 1.05%   |
| Sunplus Laptop Integrated Webcam HD             | 1         | 1.05%   |
| Sunplus Integrated_Webcam_FHD                   | 1         | 1.05%   |
| Sunplus HP HD Webcam [Fixed]                    | 1         | 1.05%   |
| Sunplus HD WebCam                               | 1         | 1.05%   |
| Silicon Motion WebCam SC-50AFL11C54N            | 1         | 1.05%   |
| Silicon Motion Realtek USB 2.0 PC Camera        | 1         | 1.05%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960  | 1         | 1.05%   |
| Ricoh Integrated Webcam                         | 1         | 1.05%   |
| Realtek Integrated Webcam HD                    | 1         | 1.05%   |
| Quanta VGA WebCam                               | 1         | 1.05%   |
| Quanta HD Webcam                                | 1         | 1.05%   |
| OmniVision Monitor Webcam                       | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD            | 1         | 1.05%   |
| Microdia JOYACCESS JA-Webcam                    | 1         | 1.05%   |
| Luxvisions Innotech Limited HP Universal Camera | 1         | 1.05%   |
| Logitech Webcam C270                            | 1         | 1.05%   |
| Logitech HD Pro Webcam C920                     | 1         | 1.05%   |
| Lite-On Integrated Camera                       | 1         | 1.05%   |
| Lite-On HP Wide Vision HD Camera                | 1         | 1.05%   |
| Intel RealSense 3D Camera (Front F200)          | 1         | 1.05%   |
| IMC Networks USB2.0 HD UVC WebCam               | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 50%     |
| Validity Sensors           | 3         | 21.43%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |
| DigitalPersona             | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 14.29%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                          | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 7.14%   |
| Synaptics WBDI                                           | 1         | 7.14%   |
| Synaptics UWP WBDI                                       | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 1         | 7.14%   |
| DigitalPersona Fingerprint Reader                        | 1         | 7.14%   |

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
| 1     | 85        | 37.44%  |
| 2     | 60        | 26.43%  |
| 0     | 40        | 17.62%  |
| 3     | 32        | 14.1%   |
| 4     | 8         | 3.52%   |
| 6     | 1         | 0.44%   |
| 5     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 154       | 50.33%  |
| Bluetooth                | 62        | 20.26%  |
| Net/wireless             | 33        | 10.78%  |
| Card reader              | 17        | 5.56%   |
| Firewire controller      | 16        | 5.23%   |
| Fingerprint reader       | 13        | 4.25%   |
| Net/ethernet             | 4         | 1.31%   |
| Storage                  | 3         | 0.98%   |
| Network                  | 3         | 0.98%   |
| Sound                    | 1         | 0.33%   |

