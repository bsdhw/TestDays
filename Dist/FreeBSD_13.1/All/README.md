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

Total: 237

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Intel         | NUC5PPYB                    | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
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
| amd64 | 181       | 95.77%  |
| arm64 | 4         | 2.12%   |
| arm   | 3         | 1.59%   |
| i386  | 1         | 0.53%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 59        | 31.22%  |
| KDE5          | 33        | 17.46%  |
| XFCE          | 28        | 14.81%  |
| GNOME         | 18        | 9.52%   |
| TWM           | 13        | 6.88%   |
| MATE          | 9         | 4.76%   |
| i3            | 7         | 3.7%    |
| Openbox       | 6         | 3.17%   |
| LXDE          | 3         | 1.59%   |
| Cinnamon      | 3         | 1.59%   |
| LXQt          | 2         | 1.06%   |
| xfwm          | 1         | 0.53%   |
| X-Cinnamon    | 1         | 0.53%   |
| plasma        | 1         | 0.53%   |
| IceWM         | 1         | 0.53%   |
| Enlightenment | 1         | 0.53%   |
| dwm           | 1         | 0.53%   |
| Compton       | 1         | 0.53%   |
| bspwm         | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 122       | 64.55%  |
| Console | 61        | 32.28%  |
| Wayland | 6         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 101       | 53.44%  |
| SDDM    | 35        | 18.52%  |
| SLiM    | 19        | 10.05%  |
| GDM     | 12        | 6.35%   |
| XDM     | 11        | 5.82%   |
| LightDM | 10        | 5.29%   |
| PCDM    | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 136       | 71.58%  |
| en_US           | 23        | 12.11%  |
| ru_RU           | 10        | 5.26%   |
| Unknown         | 7         | 3.68%   |
| zh_CN           | 4         | 2.11%   |
| fr_FR           | 4         | 2.11%   |
| ja_JP           | 1         | 0.53%   |
| es_ES           | 1         | 0.53%   |
| en_US.ISO8859-1 | 1         | 0.53%   |
| en_GB           | 1         | 0.53%   |
| en_AU           | 1         | 0.53%   |
| de_DE           | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 139       | 73.16%  |
| BIOS | 51        | 26.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 128       | 67.37%  |
| Ufs  | 62        | 32.63%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 173       | 91.53%  |
| MBR     | 14        | 7.41%   |
| BSD     | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 34        | 17.99%  |
| Lenovo                  | 31        | 16.4%   |
| ASUSTek Computer        | 24        | 12.7%   |
| Hewlett-Packard         | 14        | 7.41%   |
| Intel                   | 10        | 5.29%   |
| Gigabyte Technology     | 9         | 4.76%   |
| Acer                    | 8         | 4.23%   |
| Unknown                 | 8         | 4.23%   |
| ASRock                  | 7         | 3.7%    |
| MSI                     | 6         | 3.17%   |
| Google                  | 4         | 2.12%   |
| Fujitsu                 | 3         | 1.59%   |
| Apple                   | 3         | 1.59%   |
| TUXEDO                  | 2         | 1.06%   |
| Toshiba                 | 2         | 1.06%   |
| System76                | 2         | 1.06%   |
| Supermicro              | 2         | 1.06%   |
| Samsung Electronics     | 2         | 1.06%   |
| Sony                    | 1         | 0.53%   |
| Raspberry Pi Foundation | 1         | 0.53%   |
| PC Engines              | 1         | 0.53%   |
| Notebook                | 1         | 0.53%   |
| NITRINOnet              | 1         | 0.53%   |
| NF-M2S                  | 1         | 0.53%   |
| MouseComputer           | 1         | 0.53%   |
| LG Electronics          | 1         | 0.53%   |
| Inventec                | 1         | 0.53%   |
| Huanan                  | 1         | 0.53%   |
| GVC                     | 1         | 0.53%   |
| GPD                     | 1         | 0.53%   |
| Fujitsu Siemens         | 1         | 0.53%   |
| Foxconn                 | 1         | 0.53%   |
| Fanless Mini PC         | 1         | 0.53%   |
| BESSTAR Tech            | 1         | 0.53%   |
| ASRockRack              | 1         | 0.53%   |
| AMI                     | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 4.23%   |
| ASUS All Series                             | 4         | 2.12%   |
| MSI MS-7817                                 | 2         | 1.06%   |
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.06%   |
| Google Peppy                                | 2         | 1.06%   |
| Dell Precision T3600                        | 2         | 1.06%   |
| Dell Precision M4500                        | 2         | 1.06%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.53%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.53%   |
| Toshiba Satellite L305D                     | 1         | 0.53%   |
| Toshiba Satellite A300                      | 1         | 0.53%   |
| System76 Gazelle                            | 1         | 0.53%   |
| System76 Galago Pro                         | 1         | 0.53%   |
| Supermicro MBD-X8DT6-A-IS018                | 1         | 0.53%   |
| Supermicro Icebreaker 4824                  | 1         | 0.53%   |
| Sony VGN-NS21M_S                            | 1         | 0.53%   |
| Samsung R530/R730/R540                      | 1         | 0.53%   |
| Samsung 750TDA                              | 1         | 0.53%   |
| RPi Raspberry Pi                            | 1         | 0.53%   |
| PC Engines APU3                             | 1         | 0.53%   |
| Notebook N7x0WU                             | 1         | 0.53%   |
| NITRINOnet M360RUS56                        | 1         | 0.53%   |
| NF-M2S ABIT                                 | 1         | 0.53%   |
| MSI MS-B120                                 | 1         | 0.53%   |
| MSI MS-7D09                                 | 1         | 0.53%   |
| MSI MS-7D08                                 | 1         | 0.53%   |
| MSI GF63 Thin 9SC                           | 1         | 0.53%   |
| MouseComputer B360M                         | 1         | 0.53%   |
| LG 17Z990-R.AAC9U1                          | 1         | 0.53%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.53%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-     | 1         | 0.53%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.53%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.53%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.53%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.53%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.53%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.53%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 0.53%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 17        | 8.99%   |
| Dell Latitude                | 9         | 4.76%   |
| Unknown                      | 8         | 4.23%   |
| Dell Precision               | 7         | 3.7%    |
| Lenovo IdeaPad               | 6         | 3.17%   |
| Dell OptiPlex                | 6         | 3.17%   |
| Dell Inspiron                | 6         | 3.17%   |
| ASUS ZenBook                 | 5         | 2.65%   |
| ASUS All                     | 4         | 2.12%   |
| ASUS VivoBook                | 3         | 1.59%   |
| ASUS ROG                     | 3         | 1.59%   |
| ASUS PRIME                   | 3         | 1.59%   |
| Acer Aspire                  | 3         | 1.59%   |
| Toshiba Satellite            | 2         | 1.06%   |
| MSI MS-7817                  | 2         | 1.06%   |
| Lenovo ThinkCentre           | 2         | 1.06%   |
| HP ProBook                   | 2         | 1.06%   |
| HP EliteDesk                 | 2         | 1.06%   |
| HP EliteBook                 | 2         | 1.06%   |
| Google Peppy                 | 2         | 1.06%   |
| Dell Vostro                  | 2         | 1.06%   |
| Dell G5                      | 2         | 1.06%   |
| Acer Veriton                 | 2         | 1.06%   |
| TUXEDO InfinityBook13V3      | 1         | 0.53%   |
| TUXEDO Aura                  | 1         | 0.53%   |
| System76 Gazelle             | 1         | 0.53%   |
| System76 Galago              | 1         | 0.53%   |
| Supermicro MBD-X8DT6-A-IS018 | 1         | 0.53%   |
| Supermicro Icebreaker        | 1         | 0.53%   |
| Sony VGN-NS21M               | 1         | 0.53%   |
| Samsung R530                 | 1         | 0.53%   |
| Samsung 750TDA               | 1         | 0.53%   |
| RPi Raspberry                | 1         | 0.53%   |
| PC Engines APU3              | 1         | 0.53%   |
| Notebook N7x0WU              | 1         | 0.53%   |
| NITRINOnet M360RUS56         | 1         | 0.53%   |
| NF-M2S ABIT                  | 1         | 0.53%   |
| MSI MS-B120                  | 1         | 0.53%   |
| MSI MS-7D09                  | 1         | 0.53%   |
| MSI MS-7D08                  | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 29        | 15.34%  |
| 2020    | 27        | 14.29%  |
| 2022    | 20        | 10.58%  |
| 2019    | 16        | 8.47%   |
| 2018    | 15        | 7.94%   |
| 2016    | 12        | 6.35%   |
| 2014    | 11        | 5.82%   |
| 2012    | 9         | 4.76%   |
| 2011    | 9         | 4.76%   |
| 2013    | 8         | 4.23%   |
| 2015    | 7         | 3.7%    |
| Unknown | 7         | 3.7%    |
| 2010    | 6         | 3.17%   |
| 2017    | 5         | 2.65%   |
| 2008    | 5         | 2.65%   |
| 2009    | 3         | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 92        | 48.68%  |
| Desktop        | 76        | 40.21%  |
| Mini pc        | 13        | 6.88%   |
| Server         | 3         | 1.59%   |
| Convertible    | 2         | 1.06%   |
| All in one     | 2         | 1.06%   |
| System on chip | 1         | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 183       | 96.83%  |
| Yes  | 6         | 3.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 63        | 33.16%  |
| 16.01-24.0  | 50        | 26.32%  |
| 4.01-8.0    | 25        | 13.16%  |
| 32.01-64.0  | 17        | 8.95%   |
| 64.01-256.0 | 17        | 8.95%   |
| 2.01-3.0    | 7         | 3.68%   |
| 24.01-32.0  | 5         | 2.63%   |
| 0.01-0.5    | 3         | 1.58%   |
| 3.01-4.0    | 2         | 1.05%   |
| 0.51-1.0    | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 74        | 38.95%  |
| 0.51-1.0   | 56        | 29.47%  |
| 1.01-2.0   | 35        | 18.42%  |
| 2.01-3.0   | 14        | 7.37%   |
| 3.01-4.0   | 4         | 2.11%   |
| 0          | 4         | 2.11%   |
| 4.01-8.0   | 1         | 0.53%   |
| 24.01-32.0 | 1         | 0.53%   |
| 8.01-16.0  | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 103       | 54.21%  |
| 2      | 37        | 19.47%  |
| 3      | 15        | 7.89%   |
| 0      | 13        | 6.84%   |
| 4      | 10        | 5.26%   |
| 8      | 3         | 1.58%   |
| 10     | 2         | 1.05%   |
| 6      | 2         | 1.05%   |
| 18     | 1         | 0.53%   |
| 16     | 1         | 0.53%   |
| 15     | 1         | 0.53%   |
| 11     | 1         | 0.53%   |
| 5      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 72.49%  |
| Yes       | 52        | 27.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 79.37%  |
| No        | 39        | 20.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 65.08%  |
| No        | 66        | 34.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 51.32%  |
| Yes       | 92        | 48.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 44        | 23.16%  |
| Russia      | 21        | 11.05%  |
| Germany     | 14        | 7.37%   |
| France      | 14        | 7.37%   |
| Spain       | 9         | 4.74%   |
| Canada      | 7         | 3.68%   |
| China       | 6         | 3.16%   |
| UK          | 5         | 2.63%   |
| Italy       | 5         | 2.63%   |
| India       | 5         | 2.63%   |
| Austria     | 5         | 2.63%   |
| Netherlands | 4         | 2.11%   |
| Japan       | 4         | 2.11%   |
| Czechia     | 4         | 2.11%   |
| Australia   | 4         | 2.11%   |
| Thailand    | 3         | 1.58%   |
| Venezuela   | 2         | 1.05%   |
| Turkey      | 2         | 1.05%   |
| Philippines | 2         | 1.05%   |
| New Zealand | 2         | 1.05%   |
| Mexico      | 2         | 1.05%   |
| Hong Kong   | 2         | 1.05%   |
| Bulgaria    | 2         | 1.05%   |
| Belgium     | 2         | 1.05%   |
| Uruguay     | 1         | 0.53%   |
| Taiwan      | 1         | 0.53%   |
| South Korea | 1         | 0.53%   |
| Slovenia    | 1         | 0.53%   |
| Poland      | 1         | 0.53%   |
| Norway      | 1         | 0.53%   |
| Malaysia    | 1         | 0.53%   |
| Lithuania   | 1         | 0.53%   |
| Latvia      | 1         | 0.53%   |
| Kenya       | 1         | 0.53%   |
| Israel      | 1         | 0.53%   |
| Ireland     | 1         | 0.53%   |
| Hungary     | 1         | 0.53%   |
| Guadeloupe  | 1         | 0.53%   |
| Greece      | 1         | 0.53%   |
| Finland     | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 11        | 5.76%   |
| Vienna            | 4         | 2.09%   |
| Paris             | 4         | 2.09%   |
| Ozersk            | 4         | 2.09%   |
| Frisco            | 4         | 2.09%   |
| Brno              | 4         | 2.09%   |
| Tamm              | 3         | 1.57%   |
| Omaha             | 3         | 1.57%   |
| Madrid            | 3         | 1.57%   |
| Wellington        | 2         | 1.05%   |
| St Petersburg     | 2         | 1.05%   |
| Redmond           | 2         | 1.05%   |
| Nashville         | 2         | 1.05%   |
| Maracaibo         | 2         | 1.05%   |
| Charlotte         | 2         | 1.05%   |
| Central           | 2         | 1.05%   |
| Carry-le-Rouet    | 2         | 1.05%   |
| Barcelona         | 2         | 1.05%   |
| Zhumadian         | 1         | 0.52%   |
| Zagreb            | 1         | 0.52%   |
| Yashio            | 1         | 0.52%   |
| Yangcheon-gu      | 1         | 0.52%   |
| Xiamen            | 1         | 0.52%   |
| Xi'an             | 1         | 0.52%   |
| Woerdense Verlaat | 1         | 0.52%   |
| Wheatland         | 1         | 0.52%   |
| Wenatchee         | 1         | 0.52%   |
| Waldbrunn         | 1         | 0.52%   |
| Vilnius           | 1         | 0.52%   |
| Vaulx-en-Velin    | 1         | 0.52%   |
| Vancouver         | 1         | 0.52%   |
| Valladolid        | 1         | 0.52%   |
| Twickenham        | 1         | 0.52%   |
| Turku             | 1         | 0.52%   |
| Trivandrum        | 1         | 0.52%   |
| Toronto           | 1         | 0.52%   |
| Tlalnepantla      | 1         | 0.52%   |
| Tiel              | 1         | 0.52%   |
| Thousand Oaks     | 1         | 0.52%   |
| Thessaloniki      | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 64        | 111    | 24.9%   |
| Samsung Electronics | 44        | 59     | 17.12%  |
| Seagate             | 31        | 79     | 12.06%  |
| Crucial             | 19        | 28     | 7.39%   |
| Kingston            | 15        | 16     | 5.84%   |
| Toshiba             | 12        | 19     | 4.67%   |
| Intel               | 7         | 16     | 2.72%   |
| SK hynix            | 6         | 6      | 2.33%   |
| Hitachi             | 6         | 7      | 2.33%   |
| Transcend           | 5         | 5      | 1.95%   |
| A-DATA Technology   | 5         | 8      | 1.95%   |
| SanDisk             | 4         | 4      | 1.56%   |
| PNY                 | 4         | 5      | 1.56%   |
| KIOXIA              | 3         | 3      | 1.17%   |
| Hewlett-Packard     | 3         | 3      | 1.17%   |
| Gigabyte Technology | 3         | 3      | 1.17%   |
| Silicon Motion      | 2         | 2      | 0.78%   |
| Micron Technology   | 2         | 3      | 0.78%   |
| Hikvision           | 2         | 2      | 0.78%   |
| Apple               | 2         | 2      | 0.78%   |
| Verbatim            | 1         | 1      | 0.39%   |
| UMIS                | 1         | 1      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| SPCC                | 1         | 1      | 0.39%   |
| Phison              | 1         | 1      | 0.39%   |
| ORICO               | 1         | 1      | 0.39%   |
| OCZ                 | 1         | 1      | 0.39%   |
| Netac               | 1         | 1      | 0.39%   |
| LITEONIT            | 1         | 1      | 0.39%   |
| LITEON              | 1         | 1      | 0.39%   |
| Lexar               | 1         | 2      | 0.39%   |
| Lenovo              | 1         | 1      | 0.39%   |
| HGST                | 1         | 1      | 0.39%   |
| EAGET               | 1         | 1      | 0.39%   |
| China               | 1         | 1      | 0.39%   |
| CFD                 | 1         | 1      | 0.39%   |
| BR                  | 1         | 1      | 0.39%   |
| BIWIN               | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.35%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.35%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 1.01%   |
| WDC WD30EFRX-68EUZN0 3TB                | 3         | 1.01%   |
| WDC WD30EFRX-68AX9N0 3TB                | 3         | 1.01%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 3         | 1.01%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.01%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 1.01%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 1.01%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.01%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.01%   |
| A-DATA SU650 240GB                      | 3         | 1.01%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.67%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.67%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.67%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.67%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.67%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.67%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.67%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.67%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.67%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.67%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.67%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.67%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.67%   |
| PNY CS900 240GB SSD                     | 2         | 0.67%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.67%   |
| Kingston SA400S37240G 240GB             | 2         | 0.67%   |
| Kingston SA400S37120G 120GB             | 2         | 0.67%   |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.67%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.67%   |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.67%   |
| Crucial CT1000BX500SSD1 1TB             | 2         | 0.67%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.34%   |
| WDC WDS500G2X0C-00L350 500GB            | 1         | 0.34%   |
| WDC WDS500G1B0A-00H9H0 500GB            | 1         | 0.34%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.34%   |
| WDC WDS250G2B0C-00PXH0 250GB            | 1         | 0.34%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 89     | 47.31%  |
| Seagate             | 30        | 78     | 32.26%  |
| Toshiba             | 9         | 16     | 9.68%   |
| Hitachi             | 6         | 7      | 6.45%   |
| Samsung Electronics | 1         | 4      | 1.08%   |
| HGST                | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 1      | 1.08%   |
| Apple               | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 24%     |
| Crucial             | 15        | 19     | 15%     |
| Kingston            | 9         | 10     | 9%      |
| WDC                 | 8         | 8      | 8%      |
| Intel               | 5         | 14     | 5%      |
| A-DATA Technology   | 5         | 8      | 5%      |
| Transcend           | 4         | 4      | 4%      |
| SanDisk             | 4         | 4      | 4%      |
| PNY                 | 4         | 5      | 4%      |
| Toshiba             | 2         | 2      | 2%      |
| Hikvision           | 2         | 2      | 2%      |
| Verbatim            | 1         | 1      | 1%      |
| SPCC                | 1         | 1      | 1%      |
| SK hynix            | 1         | 1      | 1%      |
| Phison              | 1         | 1      | 1%      |
| ORICO               | 1         | 1      | 1%      |
| OCZ                 | 1         | 1      | 1%      |
| Micron Technology   | 1         | 2      | 1%      |
| LITEONIT            | 1         | 1      | 1%      |
| LITEON              | 1         | 1      | 1%      |
| Lexar               | 1         | 2      | 1%      |
| Lenovo              | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 1      | 1%      |
| Gigabyte Technology | 1         | 1      | 1%      |
| China               | 1         | 1      | 1%      |
| CFD                 | 1         | 1      | 1%      |
| BR                  | 1         | 1      | 1%      |
| BIWIN               | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 89        | 128    | 38.7%   |
| HDD  | 77        | 197    | 33.48%  |
| NVMe | 64        | 75     | 27.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 325    | 68.32%  |
| NVMe | 64        | 75     | 31.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 122    | 50%     |
| 0.51-1.0   | 55        | 76     | 30.9%   |
| 1.01-2.0   | 14        | 31     | 7.87%   |
| 3.01-4.0   | 6         | 10     | 3.37%   |
| 4.01-10.0  | 6         | 46     | 3.37%   |
| 2.01-3.0   | 5         | 20     | 2.81%   |
| 10.01-20.0 | 3         | 20     | 1.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 66        | 34.74%  |
| 251-500        | 42        | 22.11%  |
| 501-1000       | 34        | 17.89%  |
| 51-100         | 17        | 8.95%   |
| 21-50          | 13        | 6.84%   |
| 1001-2000      | 7         | 3.68%   |
| 1-20           | 5         | 2.63%   |
| 2001-3000      | 3         | 1.58%   |
| More than 3000 | 2         | 1.05%   |
| Unknown        | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 151       | 79.47%  |
| 21-50          | 21        | 11.05%  |
| 51-100         | 7         | 3.68%   |
| 101-250        | 5         | 2.63%   |
| 251-500        | 3         | 1.58%   |
| More than 3000 | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |
| Unknown        | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 5.88%   |
| WDC WD6400AAKS-22A7B2 640GB                  | 1         | 1      | 2.94%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 2.94%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.94%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 2.94%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 2.94%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 2.94%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 2.94%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 2.94%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.94%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 2.94%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 2.94%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 2.94%   |
| Phison NETLIST SSD 8GB-001                   | 1         | 1      | 2.94%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 2.94%   |
| LITEON IT LST-16S9G-HP 16GB                  | 1         | 1      | 2.94%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 2.94%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 2.94%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 2.94%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 2.94%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 2.94%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 2.94%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 2.94%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 2.94%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.94%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 2.94%   |
| A-DATA Technology SU650 120GB                | 1         | 1      | 2.94%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 10     | 21.88%  |
| Seagate             | 6         | 7      | 18.75%  |
| Hitachi             | 4         | 4      | 12.5%   |
| Kingston            | 3         | 4      | 9.38%   |
| Toshiba             | 2         | 2      | 6.25%   |
| A-DATA Technology   | 2         | 3      | 6.25%   |
| SPCC                | 1         | 1      | 3.13%   |
| SK hynix            | 1         | 1      | 3.13%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| Phison              | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 2      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 7         | 10     | 33.33%  |
| Seagate         | 6         | 7      | 28.57%  |
| Hitachi         | 4         | 4      | 19.05%  |
| Toshiba         | 2         | 2      | 9.52%   |
| HGST            | 1         | 1      | 4.76%   |
| Hewlett-Packard | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 25     | 64.52%  |
| SSD  | 11        | 14     | 35.48%  |

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
| Works    | 159       | 351    | 82.38%  |
| Malfunc  | 29        | 39     | 15.03%  |
| Detected | 5         | 10     | 2.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 130       | 54.62%  |
| AMD                            | 24        | 10.08%  |
| Samsung Electronics            | 22        | 9.24%   |
| SanDisk                        | 16        | 6.72%   |
| Kingston Technology Company    | 6         | 2.52%   |
| Broadcom / LSI                 | 6         | 2.52%   |
| Silicon Motion                 | 5         | 2.1%    |
| SK hynix                       | 4         | 1.68%   |
| Micron/Crucial Technology      | 4         | 1.68%   |
| Marvell Technology Group       | 3         | 1.26%   |
| KIOXIA                         | 3         | 1.26%   |
| ASMedia Technology             | 3         | 1.26%   |
| Phison Electronics             | 2         | 0.84%   |
| Nvidia                         | 2         | 0.84%   |
| Micron Technology              | 2         | 0.84%   |
| Union Memory (Shenzhen)        | 1         | 0.42%   |
| Transcend                      | 1         | 0.42%   |
| Toshiba                        | 1         | 0.42%   |
| Solid State Storage Technology | 1         | 0.42%   |
| Silicon Image                  | 1         | 0.42%   |
| Seagate Technology             | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 6.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.5%    |
| Unknown                                                                        | 9         | 3.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 1.95%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.56%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.56%   |
| SanDisk unknown                                                                | 3         | 1.17%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.17%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.17%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 1.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.17%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.78%   |
| SK hynix BC511                                                                 | 2         | 0.78%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.78%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.78%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 141       | 59.49%  |
| NVMe | 65        | 27.43%  |
| RAID | 14        | 5.91%   |
| IDE  | 12        | 5.06%   |
| SAS  | 5         | 2.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 152       | 80.42%  |
| AMD    | 30        | 15.87%  |
| ARM    | 7         | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 2.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 2.11%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.58%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.58%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.58%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.05%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.05%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 2         | 1.05%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.05%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.05%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.05%   |
| Intel Celeron 2955U @ 1.40GHz           | 2         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.05%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 1.05%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.05%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.53%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.53%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.53%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.53%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.53%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.53%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.53%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.53%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH       | 1         | 0.53%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.53%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz     | 1         | 0.53%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.53%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.53%   |
| Intel Pentium II                        | 1         | 0.53%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 1         | 0.53%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.53%   |
| Intel Pentium CPU G3240T @ 2.70GHz      | 1         | 0.53%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 48        | 25.4%   |
| Intel Core i7        | 38        | 20.11%  |
| Other                | 15        | 7.94%   |
| Intel Celeron        | 13        | 6.88%   |
| Intel Xeon           | 11        | 5.82%   |
| Intel Core i3        | 11        | 5.82%   |
| AMD Ryzen 5          | 7         | 3.7%    |
| Intel Core 2 Duo     | 5         | 2.65%   |
| ARM Cortex           | 5         | 2.65%   |
| AMD Ryzen 7          | 5         | 2.65%   |
| AMD Ryzen 3          | 5         | 2.65%   |
| Intel Atom           | 4         | 2.12%   |
| Intel Pentium        | 3         | 1.59%   |
| AMD Ryzen 9          | 2         | 1.06%   |
| AMD Ryzen 7 PRO      | 2         | 1.06%   |
| AMD GX               | 2         | 1.06%   |
| AMD A8               | 2         | 1.06%   |
| Intel Xeon Gold      | 1         | 0.53%   |
| Intel Pentium Silver | 1         | 0.53%   |
| Intel Pentium Gold   | 1         | 0.53%   |
| Intel Pentium Dual   | 1         | 0.53%   |
| Intel Genuine        | 1         | 0.53%   |
| Intel Core 2 Quad    | 1         | 0.53%   |
| AMD Phenom II X2     | 1         | 0.53%   |
| AMD E2               | 1         | 0.53%   |
| AMD Athlon X2        | 1         | 0.53%   |
| AMD Athlon 64 X2     | 1         | 0.53%   |
| AMD A10              | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 71        | 37.57%  |
| 2       | 59        | 31.22%  |
| 6       | 16        | 8.47%   |
| 8       | 14        | 7.41%   |
| Unknown | 10        | 5.29%   |
| 16      | 8         | 4.23%   |
| 12      | 5         | 2.65%   |
| 24      | 2         | 1.06%   |
| 1       | 2         | 1.06%   |
| 28      | 1         | 0.53%   |
| 20      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 179       | 94.71%  |
| Unknown | 7         | 3.7%    |
| 2       | 3         | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 103       | 54.5%   |
| 1       | 75        | 39.68%  |
| Unknown | 11        | 5.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 21.05%  |
| Haswell         | 21        | 11.05%  |
| Unknown         | 18        | 9.47%   |
| SandyBridge     | 15        | 7.89%   |
| IvyBridge       | 12        | 6.32%   |
| Skylake         | 9         | 4.74%   |
| TigerLake       | 8         | 4.21%   |
| CometLake       | 7         | 3.68%   |
| Broadwell       | 7         | 3.68%   |
| Westmere        | 6         | 3.16%   |
| Zen+            | 5         | 2.63%   |
| Zen 3           | 5         | 2.63%   |
| Zen 2           | 5         | 2.63%   |
| Silvermont      | 4         | 2.11%   |
| Puma            | 4         | 2.11%   |
| Core            | 4         | 2.11%   |
| Zen             | 3         | 1.58%   |
| Penryn          | 3         | 1.58%   |
| Goldmont plus   | 3         | 1.58%   |
| Bonnell         | 3         | 1.58%   |
| Piledriver      | 1         | 0.53%   |
| P6              | 1         | 0.53%   |
| K8 Hammer       | 1         | 0.53%   |
| K8 & K10 hybrid | 1         | 0.53%   |
| K10             | 1         | 0.53%   |
| IceLake         | 1         | 0.53%   |
| Goldmont        | 1         | 0.53%   |
| Excavator       | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 119       | 57.77%  |
| Nvidia                               | 43        | 20.87%  |
| AMD                                  | 37        | 17.96%  |
| Matrox Electronics Systems           | 5         | 2.43%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.49%   |
| ASPEED Technology                    | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11        | 5.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 4.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 3.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 2.83%   |
| Intel UHD Graphics 620                                                      | 5         | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.89%   |
| Intel HD Graphics 620                                                       | 4         | 1.89%   |
| Intel HD Graphics 5500                                                      | 4         | 1.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 1.89%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.42%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 1.42%   |
| Intel HD Graphics 630                                                       | 3         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.42%   |
| AMD Renoir                                                                  | 3         | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.42%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 3         | 1.42%   |
| AMD Lucienne                                                                | 3         | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.94%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.94%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 0.94%   |
| Nvidia GP108BM [GeForce MX250]                                              | 2         | 0.94%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 0.94%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2         | 0.94%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 0.94%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.94%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2         | 0.94%   |
| Intel HD Graphics 530                                                       | 2         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 91        | 48.15%  |
| 1 x AMD                                  | 28        | 14.81%  |
| 1 x Nvidia                               | 21        | 11.11%  |
| Intel + Nvidia                           | 18        | 9.52%   |
| Other                                    | 9         | 4.76%   |
| 2 x Intel                                | 5         | 2.65%   |
| 1 x Matrox                               | 5         | 2.65%   |
| Intel + AMD                              | 5         | 2.65%   |
| 2 x AMD                                  | 2         | 1.06%   |
| AMD + Nvidia                             | 2         | 1.06%   |
| 2 x Nvidia                               | 1         | 0.53%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.53%   |
| 1 x ASPEED                               | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 81.05%  |
| Proprietary | 26        | 13.68%  |
| Unknown     | 10        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 150       | 79.37%  |
| 0.51-1.0   | 14        | 7.41%   |
| 1.01-2.0   | 9         | 4.76%   |
| 0.01-0.5   | 6         | 3.17%   |
| 3.01-4.0   | 4         | 2.12%   |
| 5.01-6.0   | 3         | 1.59%   |
| 7.01-8.0   | 2         | 1.06%   |
| 2.01-3.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 17        | 12.69%  |
| LG Display           | 15        | 11.19%  |
| BOE                  | 14        | 10.45%  |
| Chimei Innolux       | 12        | 8.96%   |
| AU Optronics         | 11        | 8.21%   |
| Acer                 | 6         | 4.48%   |
| Lenovo               | 5         | 3.73%   |
| Dell                 | 5         | 3.73%   |
| BenQ                 | 5         | 3.73%   |
| Goldstar             | 4         | 2.99%   |
| AOC                  | 4         | 2.99%   |
| Toshiba              | 3         | 2.24%   |
| Philips              | 3         | 2.24%   |
| ViewSonic            | 2         | 1.49%   |
| Sharp                | 2         | 1.49%   |
| Sceptre Tech         | 2         | 1.49%   |
| Mi                   | 2         | 1.49%   |
| LGD                  | 2         | 1.49%   |
| CSO                  | 2         | 1.49%   |
| ASUSTek Computer     | 2         | 1.49%   |
| Apple                | 2         | 1.49%   |
| YTH                  | 1         | 0.75%   |
| Vestel Elektronik    | 1         | 0.75%   |
| USR                  | 1         | 0.75%   |
| Unknown (XXX)        | 1         | 0.75%   |
| Panasonic            | 1         | 0.75%   |
| LG Philips           | 1         | 0.75%   |
| LG Electronics       | 1         | 0.75%   |
| JDI                  | 1         | 0.75%   |
| IOD                  | 1         | 0.75%   |
| Iiyama               | 1         | 0.75%   |
| Idek Iiyama          | 1         | 0.75%   |
| HannStar             | 1         | 0.75%   |
| Compal               | 1         | 0.75%   |
| Ancor Communications | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 1.47%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.47%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.47%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.47%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 2         | 1.47%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.47%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 2         | 1.47%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.47%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 2         | 1.47%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.74%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.74%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.74%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.74%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.74%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.74%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.74%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.74%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.74%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.74%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.74%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.74%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.74%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.74%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.74%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 50.39%  |
| 1366x768 (WXGA)    | 17        | 13.18%  |
| 3840x2160 (4K)     | 9         | 6.98%   |
| 2560x1440 (QHD)    | 9         | 6.98%   |
| 1600x900 (HD+)     | 5         | 3.88%   |
| 1280x1024 (SXGA)   | 4         | 3.1%    |
| 1920x1200 (WUXGA)  | 3         | 2.33%   |
| 2560x1600          | 2         | 1.55%   |
| 2560x1080          | 2         | 1.55%   |
| 1680x1050 (WSXGA+) | 2         | 1.55%   |
| 1280x800 (WXGA)    | 2         | 1.55%   |
| 3200x1800 (QHD+)   | 1         | 0.78%   |
| 2880x1800          | 1         | 0.78%   |
| 2048x1152          | 1         | 0.78%   |
| 1920x540           | 1         | 0.78%   |
| 1440x900 (WXGA+)   | 1         | 0.78%   |
| 1080x2160          | 1         | 0.78%   |
| 1024x768 (XGA)     | 1         | 0.78%   |
| 1024x600           | 1         | 0.78%   |
| Unknown            | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 22.39%  |
| 13      | 28        | 20.9%   |
| 27      | 14        | 10.45%  |
| 24      | 13        | 9.7%    |
| Unknown | 11        | 8.21%   |
| 21      | 6         | 4.48%   |
| 12      | 5         | 3.73%   |
| 23      | 4         | 2.99%   |
| 31      | 3         | 2.24%   |
| 19      | 3         | 2.24%   |
| 29      | 2         | 1.49%   |
| 20      | 2         | 1.49%   |
| 18      | 2         | 1.49%   |
| 17      | 2         | 1.49%   |
| 64      | 1         | 0.75%   |
| 57      | 1         | 0.75%   |
| 54      | 1         | 0.75%   |
| 42      | 1         | 0.75%   |
| 22      | 1         | 0.75%   |
| 14      | 1         | 0.75%   |
| 11      | 1         | 0.75%   |
| 10      | 1         | 0.75%   |
| 5       | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 37.59%  |
| 501-600     | 29        | 21.8%   |
| 201-300     | 15        | 11.28%  |
| Unknown     | 11        | 8.27%   |
| 401-500     | 10        | 7.52%   |
| 601-700     | 7         | 5.26%   |
| 351-400     | 6         | 4.51%   |
| 1001-1500   | 3         | 2.26%   |
| 901-1000    | 1         | 0.75%   |
| 1-100       | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 92        | 76.67%  |
| 16/10   | 10        | 8.33%   |
| Unknown | 10        | 8.33%   |
| 5/4     | 2         | 1.67%   |
| 21/9    | 2         | 1.67%   |
| 6/5     | 1         | 0.83%   |
| 4/3     | 1         | 0.83%   |
| 11/10   | 1         | 0.83%   |
| 0.46    | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 17.16%  |
| 91-100         | 23        | 17.16%  |
| 81-90          | 22        | 16.42%  |
| 301-350        | 16        | 11.94%  |
| Unknown        | 11        | 8.21%   |
| 101-110        | 8         | 5.97%   |
| 71-80          | 6         | 4.48%   |
| 151-200        | 6         | 4.48%   |
| 61-70          | 5         | 3.73%   |
| More than 1000 | 3         | 2.24%   |
| 351-500        | 3         | 2.24%   |
| 51-60          | 1         | 0.75%   |
| 41-50          | 1         | 0.75%   |
| 1-40           | 1         | 0.75%   |
| 251-300        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 131-140        | 1         | 0.75%   |
| 121-130        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 32.06%  |
| 121-160       | 36        | 27.48%  |
| 101-120       | 25        | 19.08%  |
| 161-240       | 11        | 8.4%    |
| Unknown       | 11        | 8.4%    |
| More than 240 | 5         | 3.82%   |
| 1-50          | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 100       | 52.91%  |
| 0     | 71        | 37.57%  |
| 2     | 17        | 8.99%   |
| 3     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 109       | 40.82%  |
| Realtek Semiconductor    | 87        | 32.58%  |
| Qualcomm Atheros         | 28        | 10.49%  |
| Broadcom                 | 14        | 5.24%   |
| Ralink Technology        | 4         | 1.5%    |
| Xiaomi                   | 3         | 1.12%   |
| Marvell Technology Group | 3         | 1.12%   |
| TP-Link                  | 2         | 0.75%   |
| Samsung Electronics      | 2         | 0.75%   |
| MediaTek                 | 2         | 0.75%   |
| Google                   | 2         | 0.75%   |
| Sagem                    | 1         | 0.37%   |
| Ralink                   | 1         | 0.37%   |
| Qualcomm                 | 1         | 0.37%   |
| Nvidia                   | 1         | 0.37%   |
| MYRICOM                  | 1         | 0.37%   |
| LG Electronics           | 1         | 0.37%   |
| IMC Networks             | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |
| HMD Global               | 1         | 0.37%   |
| D-Link System            | 1         | 0.37%   |
| Arduino SA               | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 18.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.14%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.52%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.2%    |
| Intel I211 Gigabit Network Connection                             | 7         | 2.2%    |
| Intel 82574L Gigabit Network Connection                           | 7         | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.89%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.89%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.26%   |
| Intel Wireless 7265                                               | 4         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.94%   |
| Intel Wireless-AC 9260                                            | 3         | 0.94%   |
| Intel Wireless 8260                                               | 3         | 0.94%   |
| Intel Wireless 7260                                               | 3         | 0.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 3         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.63%   |
| Realtek Realtek Bluetooth Adapter                                 | 2         | 0.63%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 49.28%  |
| Qualcomm Atheros      | 28        | 20.29%  |
| Realtek Semiconductor | 19        | 13.77%  |
| Broadcom              | 12        | 8.7%    |
| Ralink Technology     | 4         | 2.9%    |
| TP-Link               | 2         | 1.45%   |
| MediaTek              | 2         | 1.45%   |
| Sagem                 | 1         | 0.72%   |
| Ralink                | 1         | 0.72%   |
| IMC Networks          | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 5.8%    |
| Intel Wi-Fi 6 AX200                                            | 7         | 5.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.35%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.9%    |
| Intel Wireless 7265                                            | 4         | 2.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.17%   |
| Intel Wireless-AC 9260                                         | 3         | 2.17%   |
| Intel Wireless 8260                                            | 3         | 2.17%   |
| Intel Wireless 7260                                            | 3         | 2.17%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.45%   |
| Realtek Realtek Bluetooth Adapter                              | 2         | 1.45%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.45%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.72%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.72%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 46.39%  |
| Intel                    | 68        | 40.96%  |
| Broadcom                 | 5         | 3.01%   |
| Xiaomi                   | 3         | 1.81%   |
| Marvell Technology Group | 3         | 1.81%   |
| Samsung Electronics      | 2         | 1.2%    |
| Google                   | 2         | 1.2%    |
| Qualcomm Atheros         | 1         | 0.6%    |
| Qualcomm                 | 1         | 0.6%    |
| Nvidia                   | 1         | 0.6%    |
| MYRICOM                  | 1         | 0.6%    |
| HMD Global               | 1         | 0.6%    |
| D-Link System            | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 32.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.65%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.95%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 3.95%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.39%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.69%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.69%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.13%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.13%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.13%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.13%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.13%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.13%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.13%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 1.13%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Intel Ethernet Controller X550                                    | 1         | 0.56%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 151       | 54.32%  |
| WiFi     | 124       | 44.6%   |
| Modem    | 3         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 114       | 66.28%  |
| WiFi     | 58        | 33.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 92        | 48.68%  |
| 1     | 73        | 38.62%  |
| 3     | 9         | 4.76%   |
| 0     | 9         | 4.76%   |
| 5     | 2         | 1.06%   |
| 4     | 2         | 1.06%   |
| 7     | 1         | 0.53%   |
| 6     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 161       | 84.74%  |
| Yes  | 29        | 15.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 56.84%  |
| Qualcomm Atheros Communications | 10        | 10.53%  |
| Realtek Semiconductor           | 6         | 6.32%   |
| IMC Networks                    | 5         | 5.26%   |
| Dell                            | 4         | 4.21%   |
| Foxconn / Hon Hai               | 3         | 3.16%   |
| Apple                           | 3         | 3.16%   |
| Lite-On Technology              | 2         | 2.11%   |
| Cambridge Silicon Radio         | 2         | 2.11%   |
| Broadcom                        | 2         | 2.11%   |
| ASUSTek Computer                | 2         | 2.11%   |
| Ralink                          | 1         | 1.05%   |
| Creative Technology             | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 15.79%  |
| Intel AX201 Bluetooth                                       | 15        | 15.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 12.63%  |
| Intel AX200 Bluetooth                                       | 6         | 6.32%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.16%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.11%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.11%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.11%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.11%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.11%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.11%   |
| Apple Bluetooth Host Controller                             | 2         | 2.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.05%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.05%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.05%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.05%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.05%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.05%   |
| Lite-On Wireless_Device                                     | 1         | 1.05%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.05%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.05%   |
| Intel AX210 Bluetooth                                       | 1         | 1.05%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.05%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.05%   |
| IMC Networks Bluetooth Radio                                | 1         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.05%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.05%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.05%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 1.05%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1         | 1.05%   |
| ASUS Bluetooth USB module                                   | 1         | 1.05%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 132       | 60.55%  |
| AMD                         | 38        | 17.43%  |
| Nvidia                      | 31        | 14.22%  |
| Plantronics                 | 2         | 0.92%   |
| GN Netcom                   | 2         | 0.92%   |
| FiiO Electronics Technology | 2         | 0.92%   |
| XMOS                        | 1         | 0.46%   |
| SteelSeries ApS             | 1         | 0.46%   |
| Sony                        | 1         | 0.46%   |
| Realtek Semiconductor       | 1         | 0.46%   |
| Razer USA                   | 1         | 0.46%   |
| Micro Star International    | 1         | 0.46%   |
| Lenovo                      | 1         | 0.46%   |
| Kingston Technology         | 1         | 0.46%   |
| Ensoniq                     | 1         | 0.46%   |
| Creative Labs               | 1         | 0.46%   |
| Cambridge Silicon Radio     | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 5.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 4.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.68%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.3%    |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.92%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.53%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.53%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.53%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1.53%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.15%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.15%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.77%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.77%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 48        | 22.54%  |
| Samsung Electronics          | 47        | 22.07%  |
| Micron Technology            | 21        | 9.86%   |
| Kingston                     | 17        | 7.98%   |
| Crucial                      | 17        | 7.98%   |
| Corsair                      | 14        | 6.57%   |
| G.Skill                      | 8         | 3.76%   |
| Unknown                      | 7         | 3.29%   |
| Unknown                      | 6         | 2.82%   |
| Elpida                       | 4         | 1.88%   |
| Unknown (ABCD)               | 3         | 1.41%   |
| Ramaxel Technology           | 3         | 1.41%   |
| A-DATA Technology            | 3         | 1.41%   |
| Transcend                    | 2         | 0.94%   |
| Nanya Technology             | 2         | 0.94%   |
| KomputerBay                  | 2         | 0.94%   |
| Qimonda                      | 1         | 0.47%   |
| PNY                          | 1         | 0.47%   |
| Patriot Memory (PDP Systems) | 1         | 0.47%   |
| Patriot                      | 1         | 0.47%   |
| Kingmax Semiconductor        | 1         | 0.47%   |
| Kingmax                      | 1         | 0.47%   |
| Hewlett-Packard              | 1         | 0.47%   |
| Apacer                       | 1         | 0.47%   |
| AMD                          | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 2.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 0.87%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.87%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.87%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.87%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.87%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.87%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.87%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.44%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.44%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s              | 1         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.44%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 0.44%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.44%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.44%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s            | 1         | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 86        | 46.74%  |
| DDR3    | 73        | 39.67%  |
| DDR2    | 8         | 4.35%   |
| LPDDR4  | 7         | 3.8%    |
| LPDDR3  | 4         | 2.17%   |
| Unknown | 4         | 2.17%   |
| LPDDR5  | 1         | 0.54%   |
| DDR     | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 57.38%  |
| DIMM         | 66        | 36.07%  |
| Row Of Chips | 10        | 5.46%   |
| Chip         | 1         | 0.55%   |
| Unknown      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 38.38%  |
| 4096  | 61        | 30.81%  |
| 16384 | 25        | 12.63%  |
| 2048  | 23        | 11.62%  |
| 32768 | 11        | 5.56%   |
| 1024  | 2         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 22.28%  |
| 3200    | 36        | 18.65%  |
| 2400    | 21        | 10.88%  |
| 2667    | 18        | 9.33%   |
| 2133    | 18        | 9.33%   |
| 1333    | 16        | 8.29%   |
| 1334    | 9         | 4.66%   |
| 800     | 4         | 2.07%   |
| 2666    | 3         | 1.55%   |
| 1067    | 3         | 1.55%   |
| 667     | 3         | 1.55%   |
| 4267    | 2         | 1.04%   |
| 3600    | 2         | 1.04%   |
| 3000    | 2         | 1.04%   |
| 1066    | 2         | 1.04%   |
| 975     | 2         | 1.04%   |
| Unknown | 2         | 1.04%   |
| 6400    | 1         | 0.52%   |
| 4266    | 1         | 0.52%   |
| 3400    | 1         | 0.52%   |
| 1867    | 1         | 0.52%   |
| 1866    | 1         | 0.52%   |
| 933     | 1         | 0.52%   |
| 533     | 1         | 0.52%   |

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
| Chicony Electronics           | 18        | 23.38%  |
| IMC Networks                  | 12        | 15.58%  |
| Sunplus Innovation Technology | 8         | 10.39%  |
| Microdia                      | 8         | 10.39%  |
| Acer                          | 6         | 7.79%   |
| Realtek Semiconductor         | 4         | 5.19%   |
| Syntek                        | 3         | 3.9%    |
| Luxvisions Innotech Limited   | 2         | 2.6%    |
| Logitech                      | 2         | 2.6%    |
| Lite-On Technology            | 2         | 2.6%    |
| Z-Star Microelectronics       | 1         | 1.3%    |
| Sonix Technology              | 1         | 1.3%    |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.3%    |
| Ricoh                         | 1         | 1.3%    |
| Quanta                        | 1         | 1.3%    |
| OmniVision Technologies       | 1         | 1.3%    |
| Intel                         | 1         | 1.3%    |
| Genesys Logic                 | 1         | 1.3%    |
| DigiTech                      | 1         | 1.3%    |
| ARC International             | 1         | 1.3%    |
| Apple                         | 1         | 1.3%    |
| Alcor Micro                   | 1         | 1.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 5         | 6.41%   |
| Acer Integrated Camera                         | 5         | 6.41%   |
| Microdia Integrated_Webcam_HD                  | 4         | 5.13%   |
| IMC Networks EasyCamera                        | 4         | 5.13%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 3         | 3.85%   |
| Realtek Integrated_Webcam_HD                   | 3         | 3.85%   |
| Syntek EasyCamera                              | 2         | 2.56%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 2.56%   |
| Microdia Integrated Webcam                     | 2         | 2.56%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                  | 2         | 2.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)       | 2         | 2.56%   |
| Chicony HP HD Camera                           | 2         | 2.56%   |
| Chicony HD WebCam                              | 2         | 2.56%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1         | 1.28%   |
| Syntek Integrated Camera                       | 1         | 1.28%   |
| Sunplus Laptop Integrated Webcam HD            | 1         | 1.28%   |
| Sunplus HP HD Webcam [Fixed]                   | 1         | 1.28%   |
| Sunplus HD WebCam                              | 1         | 1.28%   |
| Sonix USB2.0 HD UVC WebCam                     | 1         | 1.28%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1         | 1.28%   |
| Ricoh Integrated Webcam                        | 1         | 1.28%   |
| Realtek Integrated Webcam HD                   | 1         | 1.28%   |
| Quanta VGA WebCam                              | 1         | 1.28%   |
| OmniVision Monitor Webcam                      | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_HD           | 1         | 1.28%   |
| Microdia JOYACCESS JA-Webcam                   | 1         | 1.28%   |
| Luxvisions Innotech Limited Integrated Camera  | 1         | 1.28%   |
| Luxvisions Innotech Limited HP HD Camera       | 1         | 1.28%   |
| Logitech Webcam C270                           | 1         | 1.28%   |
| Logitech HD Pro Webcam C920                    | 1         | 1.28%   |
| Lite-On Integrated Camera                      | 1         | 1.28%   |
| Lite-On HP Wide Vision HD Camera               | 1         | 1.28%   |
| Intel RealSense 3D Camera (Front F200)         | 1         | 1.28%   |
| IMC Networks USB2.0 HD IR UVC WebCam           | 1         | 1.28%   |
| IMC Networks Integrated Webcam                 | 1         | 1.28%   |
| IMC Networks HP TrueVision HD Camera           | 1         | 1.28%   |
| IMC Networks HD Camera                         | 1         | 1.28%   |
| Genesys Logic Camera                           | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 50%     |
| Validity Sensors           | 3         | 25%     |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| LighTuning Technology      | 1         | 8.33%   |
| DigitalPersona             | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 8.33%   |
| Validity Sensors Synaptics WBDI                           | 1         | 8.33%   |
| Synaptics product 0x00be                                  | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 8.33%   |
| LighTuning EgisTec EH575                                  | 1         | 8.33%   |
| DigitalPersona Fingerprint Reader                         | 1         | 8.33%   |
| Unknown                                                   | 1         | 8.33%   |

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
| 1     | 72        | 37.89%  |
| 2     | 49        | 25.79%  |
| 0     | 35        | 18.42%  |
| 3     | 26        | 13.68%  |
| 4     | 6         | 3.16%   |
| 6     | 1         | 0.53%   |
| 5     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 130       | 51.79%  |
| Bluetooth                | 47        | 18.73%  |
| Net/wireless             | 27        | 10.76%  |
| Card reader              | 15        | 5.98%   |
| Firewire controller      | 13        | 5.18%   |
| Fingerprint reader       | 11        | 4.38%   |
| Net/ethernet             | 4         | 1.59%   |
| Storage                  | 2         | 0.8%    |
| Sound                    | 1         | 0.4%    |
| Network                  | 1         | 0.4%    |

