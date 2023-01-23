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

Total: 243

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 187       | 95.9%   |
| arm64 | 4         | 2.05%   |
| arm   | 3         | 1.54%   |
| i386  | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 61        | 31.28%  |
| KDE5          | 33        | 16.92%  |
| XFCE          | 29        | 14.87%  |
| GNOME         | 18        | 9.23%   |
| TWM           | 13        | 6.67%   |
| MATE          | 11        | 5.64%   |
| i3            | 8         | 4.1%    |
| Openbox       | 6         | 3.08%   |
| LXDE          | 3         | 1.54%   |
| Cinnamon      | 3         | 1.54%   |
| LXQt          | 2         | 1.03%   |
| xfwm          | 1         | 0.51%   |
| X-Cinnamon    | 1         | 0.51%   |
| plasma        | 1         | 0.51%   |
| IceWM         | 1         | 0.51%   |
| Enlightenment | 1         | 0.51%   |
| dwm           | 1         | 0.51%   |
| Compton       | 1         | 0.51%   |
| bspwm         | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 125       | 64.1%   |
| Console | 64        | 32.82%  |
| Wayland | 6         | 3.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 104       | 53.33%  |
| SDDM    | 35        | 17.95%  |
| SLiM    | 20        | 10.26%  |
| LightDM | 12        | 6.15%   |
| GDM     | 12        | 6.15%   |
| XDM     | 11        | 5.64%   |
| PCDM    | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 140       | 71.43%  |
| en_US           | 23        | 11.73%  |
| ru_RU           | 11        | 5.61%   |
| Unknown         | 8         | 4.08%   |
| zh_CN           | 4         | 2.04%   |
| fr_FR           | 4         | 2.04%   |
| ja_JP           | 1         | 0.51%   |
| es_ES           | 1         | 0.51%   |
| en_US.ISO8859-1 | 1         | 0.51%   |
| en_GB           | 1         | 0.51%   |
| en_AU           | 1         | 0.51%   |
| de_DE           | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 143       | 72.96%  |
| BIOS | 53        | 27.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 132       | 67.35%  |
| Ufs  | 64        | 32.65%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 179       | 91.79%  |
| MBR     | 14        | 7.18%   |
| BSD     | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 35        | 17.95%  |
| Lenovo                  | 33        | 16.92%  |
| ASUSTek Computer        | 26        | 13.33%  |
| Hewlett-Packard         | 15        | 7.69%   |
| Intel                   | 10        | 5.13%   |
| Gigabyte Technology     | 9         | 4.62%   |
| Acer                    | 8         | 4.1%    |
| Unknown                 | 8         | 4.1%    |
| ASRock                  | 7         | 3.59%   |
| MSI                     | 6         | 3.08%   |
| Google                  | 4         | 2.05%   |
| Fujitsu                 | 3         | 1.54%   |
| Apple                   | 3         | 1.54%   |
| TUXEDO                  | 2         | 1.03%   |
| Toshiba                 | 2         | 1.03%   |
| System76                | 2         | 1.03%   |
| Supermicro              | 2         | 1.03%   |
| Samsung Electronics     | 2         | 1.03%   |
| Sony                    | 1         | 0.51%   |
| Raspberry Pi Foundation | 1         | 0.51%   |
| PC Engines              | 1         | 0.51%   |
| Notebook                | 1         | 0.51%   |
| NITRINOnet              | 1         | 0.51%   |
| NF-M2S                  | 1         | 0.51%   |
| MouseComputer           | 1         | 0.51%   |
| LG Electronics          | 1         | 0.51%   |
| Inventec                | 1         | 0.51%   |
| Huanan                  | 1         | 0.51%   |
| GVC                     | 1         | 0.51%   |
| GPD                     | 1         | 0.51%   |
| Fujitsu Siemens         | 1         | 0.51%   |
| Foxconn                 | 1         | 0.51%   |
| Fanless Mini PC         | 1         | 0.51%   |
| BESSTAR Tech            | 1         | 0.51%   |
| ASRockRack              | 1         | 0.51%   |
| AMI                     | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 4.1%    |
| ASUS All Series                             | 4         | 2.05%   |
| MSI MS-7817                                 | 2         | 1.03%   |
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.03%   |
| Google Peppy                                | 2         | 1.03%   |
| Dell Precision T3600                        | 2         | 1.03%   |
| Dell Precision M4500                        | 2         | 1.03%   |
| Dell Latitude E6420                         | 2         | 1.03%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.51%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.51%   |
| Toshiba Satellite L305D                     | 1         | 0.51%   |
| Toshiba Satellite A300                      | 1         | 0.51%   |
| System76 Gazelle                            | 1         | 0.51%   |
| System76 Galago Pro                         | 1         | 0.51%   |
| Supermicro MBD-X8DT6-A-IS018                | 1         | 0.51%   |
| Supermicro Icebreaker 4824                  | 1         | 0.51%   |
| Sony VGN-NS21M_S                            | 1         | 0.51%   |
| Samsung R530/R730/R540                      | 1         | 0.51%   |
| Samsung 750TDA                              | 1         | 0.51%   |
| RPi Raspberry Pi                            | 1         | 0.51%   |
| PC Engines APU3                             | 1         | 0.51%   |
| Notebook N7x0WU                             | 1         | 0.51%   |
| NITRINOnet M360RUS56                        | 1         | 0.51%   |
| NF-M2S ABIT                                 | 1         | 0.51%   |
| MSI MS-B120                                 | 1         | 0.51%   |
| MSI MS-7D09                                 | 1         | 0.51%   |
| MSI MS-7D08                                 | 1         | 0.51%   |
| MSI GF63 Thin 9SC                           | 1         | 0.51%   |
| MouseComputer B360M                         | 1         | 0.51%   |
| LG 17Z990-R.AAC9U1                          | 1         | 0.51%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.51%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-     | 1         | 0.51%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.51%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.51%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.51%   |
| Lenovo ThinkPad X220 4291LF6                | 1         | 0.51%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.51%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.51%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 18        | 9.23%   |
| Dell Latitude                | 10        | 5.13%   |
| Unknown                      | 8         | 4.1%    |
| Dell Precision               | 7         | 3.59%   |
| Lenovo IdeaPad               | 6         | 3.08%   |
| Dell OptiPlex                | 6         | 3.08%   |
| Dell Inspiron                | 6         | 3.08%   |
| ASUS ZenBook                 | 5         | 2.56%   |
| ASUS All                     | 4         | 2.05%   |
| ASUS VivoBook                | 3         | 1.54%   |
| ASUS ROG                     | 3         | 1.54%   |
| ASUS PRIME                   | 3         | 1.54%   |
| Acer Aspire                  | 3         | 1.54%   |
| Toshiba Satellite            | 2         | 1.03%   |
| MSI MS-7817                  | 2         | 1.03%   |
| Lenovo ThinkCentre           | 2         | 1.03%   |
| HP ProLiant                  | 2         | 1.03%   |
| HP ProBook                   | 2         | 1.03%   |
| HP EliteDesk                 | 2         | 1.03%   |
| HP EliteBook                 | 2         | 1.03%   |
| Google Peppy                 | 2         | 1.03%   |
| Dell Vostro                  | 2         | 1.03%   |
| Dell G5                      | 2         | 1.03%   |
| Acer Veriton                 | 2         | 1.03%   |
| TUXEDO InfinityBook13V3      | 1         | 0.51%   |
| TUXEDO Aura                  | 1         | 0.51%   |
| System76 Gazelle             | 1         | 0.51%   |
| System76 Galago              | 1         | 0.51%   |
| Supermicro MBD-X8DT6-A-IS018 | 1         | 0.51%   |
| Supermicro Icebreaker        | 1         | 0.51%   |
| Sony VGN-NS21M               | 1         | 0.51%   |
| Samsung R530                 | 1         | 0.51%   |
| Samsung 750TDA               | 1         | 0.51%   |
| RPi Raspberry                | 1         | 0.51%   |
| PC Engines APU3              | 1         | 0.51%   |
| Notebook N7x0WU              | 1         | 0.51%   |
| NITRINOnet M360RUS56         | 1         | 0.51%   |
| NF-M2S ABIT                  | 1         | 0.51%   |
| MSI MS-B120                  | 1         | 0.51%   |
| MSI MS-7D09                  | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 29        | 14.87%  |
| 2020    | 27        | 13.85%  |
| 2022    | 21        | 10.77%  |
| 2019    | 16        | 8.21%   |
| 2018    | 15        | 7.69%   |
| 2016    | 12        | 6.15%   |
| 2014    | 11        | 5.64%   |
| 2011    | 11        | 5.64%   |
| 2013    | 10        | 5.13%   |
| 2012    | 9         | 4.62%   |
| 2015    | 7         | 3.59%   |
| Unknown | 7         | 3.59%   |
| 2017    | 6         | 3.08%   |
| 2010    | 6         | 3.08%   |
| 2008    | 5         | 2.56%   |
| 2009    | 3         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 95        | 48.72%  |
| Desktop        | 78        | 40%     |
| Mini pc        | 13        | 6.67%   |
| Server         | 4         | 2.05%   |
| Convertible    | 2         | 1.03%   |
| All in one     | 2         | 1.03%   |
| System on chip | 1         | 0.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 96.92%  |
| Yes  | 6         | 3.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 64        | 32.65%  |
| 16.01-24.0      | 52        | 26.53%  |
| 4.01-8.0        | 26        | 13.27%  |
| 64.01-256.0     | 18        | 9.18%   |
| 32.01-64.0      | 17        | 8.67%   |
| 2.01-3.0        | 7         | 3.57%   |
| 24.01-32.0      | 5         | 2.55%   |
| 0.01-0.5        | 3         | 1.53%   |
| 3.01-4.0        | 2         | 1.02%   |
| More than 256.0 | 1         | 0.51%   |
| 0.51-1.0        | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 77        | 39.29%  |
| 0.51-1.0   | 57        | 29.08%  |
| 1.01-2.0   | 35        | 17.86%  |
| 2.01-3.0   | 14        | 7.14%   |
| 3.01-4.0   | 5         | 2.55%   |
| 0          | 4         | 2.04%   |
| 4.01-8.0   | 2         | 1.02%   |
| 24.01-32.0 | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 54.59%  |
| 2      | 38        | 19.39%  |
| 3      | 15        | 7.65%   |
| 0      | 14        | 7.14%   |
| 4      | 10        | 5.1%    |
| 8      | 3         | 1.53%   |
| 10     | 2         | 1.02%   |
| 6      | 2         | 1.02%   |
| 18     | 1         | 0.51%   |
| 16     | 1         | 0.51%   |
| 15     | 1         | 0.51%   |
| 11     | 1         | 0.51%   |
| 5      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 72.82%  |
| Yes       | 53        | 27.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 80%     |
| No        | 39        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 65.13%  |
| No        | 68        | 34.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 51.79%  |
| Yes       | 94        | 48.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 46        | 23.47%  |
| Russia      | 23        | 11.73%  |
| Germany     | 14        | 7.14%   |
| France      | 14        | 7.14%   |
| Spain       | 9         | 4.59%   |
| China       | 7         | 3.57%   |
| Canada      | 7         | 3.57%   |
| India       | 6         | 3.06%   |
| UK          | 5         | 2.55%   |
| Italy       | 5         | 2.55%   |
| Austria     | 5         | 2.55%   |
| Netherlands | 4         | 2.04%   |
| Japan       | 4         | 2.04%   |
| Czechia     | 4         | 2.04%   |
| Australia   | 4         | 2.04%   |
| Thailand    | 3         | 1.53%   |
| Venezuela   | 2         | 1.02%   |
| Turkey      | 2         | 1.02%   |
| Philippines | 2         | 1.02%   |
| New Zealand | 2         | 1.02%   |
| Mexico      | 2         | 1.02%   |
| Hong Kong   | 2         | 1.02%   |
| Bulgaria    | 2         | 1.02%   |
| Belgium     | 2         | 1.02%   |
| Uruguay     | 1         | 0.51%   |
| Taiwan      | 1         | 0.51%   |
| South Korea | 1         | 0.51%   |
| Slovenia    | 1         | 0.51%   |
| Poland      | 1         | 0.51%   |
| Norway      | 1         | 0.51%   |
| Malaysia    | 1         | 0.51%   |
| Lithuania   | 1         | 0.51%   |
| Latvia      | 1         | 0.51%   |
| Kenya       | 1         | 0.51%   |
| Israel      | 1         | 0.51%   |
| Ireland     | 1         | 0.51%   |
| Hungary     | 1         | 0.51%   |
| Guadeloupe  | 1         | 0.51%   |
| Greece      | 1         | 0.51%   |
| Finland     | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 12        | 6.09%   |
| Vienna            | 4         | 2.03%   |
| Paris             | 4         | 2.03%   |
| Ozersk            | 4         | 2.03%   |
| Frisco            | 4         | 2.03%   |
| Brno              | 4         | 2.03%   |
| Tamm              | 3         | 1.52%   |
| Omaha             | 3         | 1.52%   |
| Madrid            | 3         | 1.52%   |
| Wellington        | 2         | 1.02%   |
| St Petersburg     | 2         | 1.02%   |
| Redmond           | 2         | 1.02%   |
| Nashville         | 2         | 1.02%   |
| Maracaibo         | 2         | 1.02%   |
| Charlotte         | 2         | 1.02%   |
| Central           | 2         | 1.02%   |
| Carry-le-Rouet    | 2         | 1.02%   |
| Barcelona         | 2         | 1.02%   |
| Zhumadian         | 1         | 0.51%   |
| Zagreb            | 1         | 0.51%   |
| Yashio            | 1         | 0.51%   |
| Yangcheon-gu      | 1         | 0.51%   |
| Xiamen            | 1         | 0.51%   |
| Xi'an             | 1         | 0.51%   |
| Woerdense Verlaat | 1         | 0.51%   |
| Wheatland         | 1         | 0.51%   |
| Wenatchee         | 1         | 0.51%   |
| Waldbrunn         | 1         | 0.51%   |
| Vilnius           | 1         | 0.51%   |
| Vaulx-en-Velin    | 1         | 0.51%   |
| Vancouver         | 1         | 0.51%   |
| Valladolid        | 1         | 0.51%   |
| Twickenham        | 1         | 0.51%   |
| Turku             | 1         | 0.51%   |
| Trivandrum        | 1         | 0.51%   |
| Toronto           | 1         | 0.51%   |
| Tlalnepantla      | 1         | 0.51%   |
| Tiel              | 1         | 0.51%   |
| Thousand Oaks     | 1         | 0.51%   |
| Thessaloniki      | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 64        | 111    | 24.43%  |
| Samsung Electronics | 46        | 62     | 17.56%  |
| Seagate             | 32        | 80     | 12.21%  |
| Crucial             | 19        | 28     | 7.25%   |
| Kingston            | 15        | 16     | 5.73%   |
| Toshiba             | 12        | 19     | 4.58%   |
| Intel               | 7         | 16     | 2.67%   |
| Transcend           | 6         | 6      | 2.29%   |
| SK hynix            | 6         | 6      | 2.29%   |
| Hitachi             | 6         | 7      | 2.29%   |
| A-DATA Technology   | 5         | 8      | 1.91%   |
| SanDisk             | 4         | 4      | 1.53%   |
| PNY                 | 4         | 5      | 1.53%   |
| KIOXIA              | 3         | 3      | 1.15%   |
| Hewlett-Packard     | 3         | 3      | 1.15%   |
| Gigabyte Technology | 3         | 3      | 1.15%   |
| Silicon Motion      | 2         | 2      | 0.76%   |
| Micron Technology   | 2         | 3      | 0.76%   |
| Hikvision           | 2         | 2      | 0.76%   |
| Apple               | 2         | 2      | 0.76%   |
| Verbatim            | 1         | 1      | 0.38%   |
| UMIS                | 1         | 1      | 0.38%   |
| SSSTC               | 1         | 1      | 0.38%   |
| SPCC                | 1         | 1      | 0.38%   |
| Phison              | 1         | 1      | 0.38%   |
| ORICO               | 1         | 1      | 0.38%   |
| OCZ                 | 1         | 1      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| LITEON              | 1         | 1      | 0.38%   |
| Lexar               | 1         | 2      | 0.38%   |
| Lenovo              | 1         | 1      | 0.38%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.38%   |
| HGST                | 1         | 1      | 0.38%   |
| EAGET               | 1         | 1      | 0.38%   |
| China               | 1         | 1      | 0.38%   |
| CFD                 | 1         | 1      | 0.38%   |
| BR                  | 1         | 1      | 0.38%   |
| BIWIN               | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.32%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.32%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 0.99%   |
| WDC WD30EFRX-68EUZN0 3TB                | 3         | 0.99%   |
| WDC WD30EFRX-68AX9N0 3TB                | 3         | 0.99%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 3         | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.99%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 0.99%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.99%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.99%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.99%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.99%   |
| A-DATA SU650 240GB                      | 3         | 0.99%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.66%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.66%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.66%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.66%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.66%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.66%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.66%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.66%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.66%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.66%   |
| Samsung SSD 850 EVO 1TB                 | 2         | 0.66%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.66%   |
| PNY CS900 240GB SSD                     | 2         | 0.66%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.66%   |
| Kingston SA400S37240G 240GB             | 2         | 0.66%   |
| Kingston SA400S37120G 120GB             | 2         | 0.66%   |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.66%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.66%   |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.66%   |
| Crucial CT1000BX500SSD1 1TB             | 2         | 0.66%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.33%   |
| WDC WDS500G2X0C-00L350 500GB            | 1         | 0.33%   |
| WDC WDS500G1B0A-00H9H0 500GB            | 1         | 0.33%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.33%   |
| WDC WDS250G2B0C-00PXH0 250GB            | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 89     | 46.81%  |
| Seagate             | 31        | 79     | 32.98%  |
| Toshiba             | 9         | 16     | 9.57%   |
| Hitachi             | 6         | 7      | 6.38%   |
| Samsung Electronics | 1         | 4      | 1.06%   |
| HGST                | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| Apple               | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 34     | 25%     |
| Crucial             | 15        | 19     | 14.42%  |
| Kingston            | 9         | 10     | 8.65%   |
| WDC                 | 8         | 8      | 7.69%   |
| Transcend           | 5         | 5      | 4.81%   |
| Intel               | 5         | 14     | 4.81%   |
| A-DATA Technology   | 5         | 8      | 4.81%   |
| SanDisk             | 4         | 4      | 3.85%   |
| PNY                 | 4         | 5      | 3.85%   |
| Toshiba             | 2         | 2      | 1.92%   |
| Hikvision           | 2         | 2      | 1.92%   |
| Verbatim            | 1         | 1      | 0.96%   |
| SPCC                | 1         | 1      | 0.96%   |
| SK hynix            | 1         | 1      | 0.96%   |
| Phison              | 1         | 1      | 0.96%   |
| ORICO               | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| Micron Technology   | 1         | 2      | 0.96%   |
| LITEONIT            | 1         | 1      | 0.96%   |
| LITEON              | 1         | 1      | 0.96%   |
| Lexar               | 1         | 2      | 0.96%   |
| Lenovo              | 1         | 1      | 0.96%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| China               | 1         | 1      | 0.96%   |
| CFD                 | 1         | 1      | 0.96%   |
| BR                  | 1         | 1      | 0.96%   |
| BIWIN               | 1         | 1      | 0.96%   |
| Apple               | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 93        | 132    | 39.41%  |
| HDD  | 78        | 198    | 33.05%  |
| NVMe | 65        | 76     | 27.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 330    | 68.75%  |
| NVMe | 65        | 76     | 31.25%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 125    | 50.27%  |
| 0.51-1.0   | 57        | 78     | 31.15%  |
| 1.01-2.0   | 14        | 31     | 7.65%   |
| 3.01-4.0   | 6         | 10     | 3.28%   |
| 4.01-10.0  | 6         | 46     | 3.28%   |
| 2.01-3.0   | 5         | 20     | 2.73%   |
| 10.01-20.0 | 3         | 20     | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 66        | 33.67%  |
| 251-500        | 46        | 23.47%  |
| 501-1000       | 35        | 17.86%  |
| 51-100         | 17        | 8.67%   |
| 21-50          | 13        | 6.63%   |
| 1001-2000      | 8         | 4.08%   |
| 1-20           | 5         | 2.55%   |
| 2001-3000      | 3         | 1.53%   |
| More than 3000 | 2         | 1.02%   |
| Unknown        | 1         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 157       | 80.1%   |
| 21-50          | 21        | 10.71%  |
| 51-100         | 7         | 3.57%   |
| 101-250        | 5         | 2.55%   |
| 251-500        | 3         | 1.53%   |
| More than 3000 | 1         | 0.51%   |
| 501-1000       | 1         | 0.51%   |
| Unknown        | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 5.71%   |
| WDC WD6400AAKS-22A7B2 640GB                  | 1         | 1      | 2.86%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 2.86%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.86%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 2.86%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 2.86%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 2.86%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 2.86%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 2.86%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.86%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 2.86%   |
| Seagate ST500DM002-1ER14C 500GB              | 1         | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 2.86%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 2.86%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 2.86%   |
| Phison NETLIST SSD 8GB-001                   | 1         | 1      | 2.86%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 2.86%   |
| LITEON IT LST-16S9G-HP 16GB                  | 1         | 1      | 2.86%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 2.86%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 2.86%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 2.86%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 2.86%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 2.86%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 2.86%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 2.86%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 2.86%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.86%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 2.86%   |
| A-DATA Technology SU650 120GB                | 1         | 1      | 2.86%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 10     | 21.21%  |
| Seagate             | 7         | 8      | 21.21%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Kingston            | 3         | 4      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| A-DATA Technology   | 2         | 3      | 6.06%   |
| SPCC                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Phison              | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 2      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 7         | 10     | 31.82%  |
| Seagate         | 7         | 8      | 31.82%  |
| Hitachi         | 4         | 4      | 18.18%  |
| Toshiba         | 2         | 2      | 9.09%   |
| HGST            | 1         | 1      | 4.55%   |
| Hewlett-Packard | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 26     | 65.63%  |
| SSD  | 11        | 14     | 34.38%  |

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
| Works    | 163       | 356    | 82.32%  |
| Malfunc  | 30        | 40     | 15.15%  |
| Detected | 5         | 10     | 2.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 133       | 54.29%  |
| AMD                            | 25        | 10.2%   |
| Samsung Electronics            | 23        | 9.39%   |
| SanDisk                        | 16        | 6.53%   |
| Kingston Technology Company    | 6         | 2.45%   |
| Broadcom / LSI                 | 6         | 2.45%   |
| Silicon Motion                 | 5         | 2.04%   |
| SK hynix                       | 4         | 1.63%   |
| Micron/Crucial Technology      | 4         | 1.63%   |
| ASMedia Technology             | 4         | 1.63%   |
| Marvell Technology Group       | 3         | 1.22%   |
| KIOXIA                         | 3         | 1.22%   |
| Phison Electronics             | 2         | 0.82%   |
| Nvidia                         | 2         | 0.82%   |
| Micron Technology              | 2         | 0.82%   |
| Union Memory (Shenzhen)        | 1         | 0.41%   |
| Transcend                      | 1         | 0.41%   |
| Toshiba                        | 1         | 0.41%   |
| Solid State Storage Technology | 1         | 0.41%   |
| Silicon Image                  | 1         | 0.41%   |
| Seagate Technology             | 1         | 0.41%   |
| Hewlett-Packard                | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 6.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 4.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.02%   |
| Unknown                                                                        | 8         | 3.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 1.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 1.89%   |
| SanDisk unknown                                                                | 4         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.51%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4         | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.51%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.13%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.13%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.13%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.75%   |
| SK hynix BC511                                                                 | 2         | 0.75%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 2         | 0.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 144       | 59.02%  |
| NVMe | 66        | 27.05%  |
| RAID | 15        | 6.15%   |
| IDE  | 13        | 5.33%   |
| SAS  | 6         | 2.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 156       | 80%     |
| AMD    | 32        | 16.41%  |
| ARM    | 7         | 3.59%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 2.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 2.04%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.53%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.53%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.02%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 1.02%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.02%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 2         | 1.02%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 1.02%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.02%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.02%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.02%   |
| Intel Celeron 2955U @ 1.40GHz           | 2         | 1.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.02%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 1.02%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.02%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.51%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.51%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.51%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.51%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.51%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.51%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.51%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 1         | 0.51%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.51%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH       | 1         | 0.51%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.51%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz     | 1         | 0.51%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.51%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.51%   |
| Intel Pentium II                        | 1         | 0.51%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 1         | 0.51%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 50        | 25.64%  |
| Intel Core i7          | 38        | 19.49%  |
| Other                  | 15        | 7.69%   |
| Intel Celeron          | 13        | 6.67%   |
| Intel Xeon             | 12        | 6.15%   |
| Intel Core i3          | 12        | 6.15%   |
| AMD Ryzen 5            | 7         | 3.59%   |
| Intel Core 2 Duo       | 5         | 2.56%   |
| ARM Cortex             | 5         | 2.56%   |
| AMD Ryzen 7            | 5         | 2.56%   |
| AMD Ryzen 3            | 5         | 2.56%   |
| Intel Atom             | 4         | 2.05%   |
| Intel Pentium          | 3         | 1.54%   |
| AMD Ryzen 9            | 2         | 1.03%   |
| AMD Ryzen 7 PRO        | 2         | 1.03%   |
| AMD GX                 | 2         | 1.03%   |
| AMD A8                 | 2         | 1.03%   |
| Intel Xeon Gold        | 1         | 0.51%   |
| Intel Pentium Silver   | 1         | 0.51%   |
| Intel Pentium Gold     | 1         | 0.51%   |
| Intel Pentium Dual     | 1         | 0.51%   |
| Intel Genuine          | 1         | 0.51%   |
| Intel Core 2 Quad      | 1         | 0.51%   |
| AMD Ryzen Threadripper | 1         | 0.51%   |
| AMD Phenom II X2       | 1         | 0.51%   |
| AMD FX                 | 1         | 0.51%   |
| AMD E2                 | 1         | 0.51%   |
| AMD Athlon X2          | 1         | 0.51%   |
| AMD Athlon 64 X2       | 1         | 0.51%   |
| AMD A10                | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 72        | 36.92%  |
| 2       | 62        | 31.79%  |
| 6       | 16        | 8.21%   |
| 8       | 14        | 7.18%   |
| Unknown | 10        | 5.13%   |
| 16      | 9         | 4.62%   |
| 12      | 5         | 2.56%   |
| 24      | 2         | 1.03%   |
| 1       | 2         | 1.03%   |
| 64      | 1         | 0.51%   |
| 28      | 1         | 0.51%   |
| 20      | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 184       | 94.36%  |
| Unknown | 7         | 3.59%   |
| 2       | 4         | 2.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 107       | 54.87%  |
| 1       | 77        | 39.49%  |
| Unknown | 11        | 5.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 40        | 20.41%  |
| Haswell         | 21        | 10.71%  |
| Unknown         | 19        | 9.69%   |
| SandyBridge     | 17        | 8.67%   |
| IvyBridge       | 13        | 6.63%   |
| Skylake         | 9         | 4.59%   |
| TigerLake       | 8         | 4.08%   |
| Broadwell       | 8         | 4.08%   |
| CometLake       | 7         | 3.57%   |
| Westmere        | 6         | 3.06%   |
| Zen+            | 5         | 2.55%   |
| Zen 3           | 5         | 2.55%   |
| Zen 2           | 5         | 2.55%   |
| Silvermont      | 4         | 2.04%   |
| Puma            | 4         | 2.04%   |
| Core            | 4         | 2.04%   |
| Zen             | 3         | 1.53%   |
| Penryn          | 3         | 1.53%   |
| Goldmont plus   | 3         | 1.53%   |
| Bonnell         | 3         | 1.53%   |
| Piledriver      | 2         | 1.02%   |
| P6              | 1         | 0.51%   |
| K8 Hammer       | 1         | 0.51%   |
| K8 & K10 hybrid | 1         | 0.51%   |
| K10             | 1         | 0.51%   |
| IceLake         | 1         | 0.51%   |
| Goldmont        | 1         | 0.51%   |
| Excavator       | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 122       | 57.55%  |
| Nvidia                               | 44        | 20.75%  |
| AMD                                  | 38        | 17.92%  |
| Matrox Electronics Systems           | 6         | 2.83%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.47%   |
| ASPEED Technology                    | 1         | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13        | 5.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 4.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 3.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 2.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 2.75%   |
| Intel UHD Graphics 620                                                      | 5         | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 5         | 2.29%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.83%   |
| Intel HD Graphics 620                                                       | 4         | 1.83%   |
| Intel HD Graphics 5500                                                      | 4         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 1.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.38%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 1.38%   |
| Intel HD Graphics 630                                                       | 3         | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.38%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.38%   |
| AMD Renoir                                                                  | 3         | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 3         | 1.38%   |
| AMD Lucienne                                                                | 3         | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.92%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 0.92%   |
| Nvidia GP108BM [GeForce MX250]                                              | 2         | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.92%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2         | 0.92%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 0.92%   |
| Matrox Electronics Systems MGA G200EH                                       | 2         | 0.92%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.92%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 94        | 48.21%  |
| 1 x AMD                                  | 29        | 14.87%  |
| 1 x Nvidia                               | 22        | 11.28%  |
| Intel + Nvidia                           | 18        | 9.23%   |
| Other                                    | 9         | 4.62%   |
| 1 x Matrox                               | 6         | 3.08%   |
| 2 x Intel                                | 5         | 2.56%   |
| Intel + AMD                              | 5         | 2.56%   |
| 2 x AMD                                  | 2         | 1.03%   |
| AMD + Nvidia                             | 2         | 1.03%   |
| 2 x Nvidia                               | 1         | 0.51%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.51%   |
| 1 x ASPEED                               | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 160       | 81.63%  |
| Proprietary | 26        | 13.27%  |
| Unknown     | 10        | 5.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 80%     |
| 0.51-1.0   | 14        | 7.18%   |
| 1.01-2.0   | 9         | 4.62%   |
| 0.01-0.5   | 6         | 3.08%   |
| 3.01-4.0   | 4         | 2.05%   |
| 5.01-6.0   | 3         | 1.54%   |
| 7.01-8.0   | 2         | 1.03%   |
| 2.01-3.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 17        | 12.41%  |
| LG Display              | 16        | 11.68%  |
| BOE                     | 14        | 10.22%  |
| Chimei Innolux          | 12        | 8.76%   |
| AU Optronics            | 11        | 8.03%   |
| Dell                    | 6         | 4.38%   |
| Acer                    | 6         | 4.38%   |
| Lenovo                  | 5         | 3.65%   |
| BenQ                    | 5         | 3.65%   |
| Goldstar                | 4         | 2.92%   |
| AOC                     | 4         | 2.92%   |
| Toshiba                 | 3         | 2.19%   |
| Philips                 | 3         | 2.19%   |
| ViewSonic               | 2         | 1.46%   |
| Sharp                   | 2         | 1.46%   |
| Sceptre Tech            | 2         | 1.46%   |
| Mi                      | 2         | 1.46%   |
| LGD                     | 2         | 1.46%   |
| CSO                     | 2         | 1.46%   |
| ASUSTek Computer        | 2         | 1.46%   |
| Apple                   | 2         | 1.46%   |
| YTH                     | 1         | 0.73%   |
| Vestel Elektronik       | 1         | 0.73%   |
| USR                     | 1         | 0.73%   |
| Unknown (XXX)           | 1         | 0.73%   |
| Panasonic               | 1         | 0.73%   |
| LG Philips              | 1         | 0.73%   |
| LG Electronics          | 1         | 0.73%   |
| JDI                     | 1         | 0.73%   |
| IOD                     | 1         | 0.73%   |
| Iiyama                  | 1         | 0.73%   |
| Idek Iiyama             | 1         | 0.73%   |
| HannStar                | 1         | 0.73%   |
| Compal                  | 1         | 0.73%   |
| Chi Mei Optoelectronics | 1         | 0.73%   |
| Ancor Communications    | 1         | 0.73%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 1.44%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.44%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.44%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.44%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 2         | 1.44%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.44%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.44%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch            | 2         | 1.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 2         | 1.44%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.44%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 2         | 1.44%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.72%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.72%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.72%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.72%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch               | 1         | 0.72%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.72%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.72%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.72%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.72%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.72%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.72%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.72%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.72%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.72%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.72%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.72%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.72%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.72%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch            | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 49.24%  |
| 1366x768 (WXGA)    | 19        | 14.39%  |
| 3840x2160 (4K)     | 9         | 6.82%   |
| 2560x1440 (QHD)    | 9         | 6.82%   |
| 1600x900 (HD+)     | 5         | 3.79%   |
| 1280x1024 (SXGA)   | 4         | 3.03%   |
| 1920x1200 (WUXGA)  | 3         | 2.27%   |
| 2560x1600          | 2         | 1.52%   |
| 2560x1080          | 2         | 1.52%   |
| 1680x1050 (WSXGA+) | 2         | 1.52%   |
| 1280x800 (WXGA)    | 2         | 1.52%   |
| 3440x1440          | 1         | 0.76%   |
| 3200x1800 (QHD+)   | 1         | 0.76%   |
| 2880x1800          | 1         | 0.76%   |
| 2048x1152          | 1         | 0.76%   |
| 1920x540           | 1         | 0.76%   |
| 1440x900 (WXGA+)   | 1         | 0.76%   |
| 1080x2160          | 1         | 0.76%   |
| 1024x768 (XGA)     | 1         | 0.76%   |
| 1024x600           | 1         | 0.76%   |
| Unknown            | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 22.63%  |
| 13      | 29        | 21.17%  |
| 27      | 14        | 10.22%  |
| 24      | 13        | 9.49%   |
| Unknown | 11        | 8.03%   |
| 21      | 6         | 4.38%   |
| 12      | 5         | 3.65%   |
| 23      | 4         | 2.92%   |
| 31      | 3         | 2.19%   |
| 19      | 3         | 2.19%   |
| 29      | 2         | 1.46%   |
| 20      | 2         | 1.46%   |
| 18      | 2         | 1.46%   |
| 17      | 2         | 1.46%   |
| 64      | 1         | 0.73%   |
| 57      | 1         | 0.73%   |
| 54      | 1         | 0.73%   |
| 42      | 1         | 0.73%   |
| 34      | 1         | 0.73%   |
| 22      | 1         | 0.73%   |
| 14      | 1         | 0.73%   |
| 11      | 1         | 0.73%   |
| 10      | 1         | 0.73%   |
| 5       | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 38.24%  |
| 501-600     | 29        | 21.32%  |
| 201-300     | 15        | 11.03%  |
| Unknown     | 11        | 8.09%   |
| 401-500     | 10        | 7.35%   |
| 601-700     | 7         | 5.15%   |
| 351-400     | 6         | 4.41%   |
| 1001-1500   | 3         | 2.21%   |
| 701-800     | 1         | 0.74%   |
| 901-1000    | 1         | 0.74%   |
| 1-100       | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 76.42%  |
| 16/10   | 10        | 8.13%   |
| Unknown | 10        | 8.13%   |
| 21/9    | 3         | 2.44%   |
| 5/4     | 2         | 1.63%   |
| 6/5     | 1         | 0.81%   |
| 4/3     | 1         | 0.81%   |
| 11/10   | 1         | 0.81%   |
| 0.46    | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 23        | 16.79%  |
| 201-250        | 23        | 16.79%  |
| 91-100         | 23        | 16.79%  |
| 301-350        | 16        | 11.68%  |
| Unknown        | 11        | 8.03%   |
| 101-110        | 9         | 6.57%   |
| 71-80          | 6         | 4.38%   |
| 151-200        | 6         | 4.38%   |
| 61-70          | 5         | 3.65%   |
| 351-500        | 4         | 2.92%   |
| More than 1000 | 3         | 2.19%   |
| 51-60          | 1         | 0.73%   |
| 41-50          | 1         | 0.73%   |
| 1-40           | 1         | 0.73%   |
| 251-300        | 1         | 0.73%   |
| 141-150        | 1         | 0.73%   |
| 131-140        | 1         | 0.73%   |
| 121-130        | 1         | 0.73%   |
| 501-1000       | 1         | 0.73%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 32.09%  |
| 121-160       | 36        | 26.87%  |
| 101-120       | 27        | 20.15%  |
| 161-240       | 11        | 8.21%   |
| Unknown       | 11        | 8.21%   |
| More than 240 | 5         | 3.73%   |
| 1-50          | 1         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 52.82%  |
| 0     | 74        | 37.95%  |
| 2     | 17        | 8.72%   |
| 3     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 113       | 41.24%  |
| Realtek Semiconductor    | 89        | 32.48%  |
| Qualcomm Atheros         | 28        | 10.22%  |
| Broadcom                 | 15        | 5.47%   |
| Ralink Technology        | 4         | 1.46%   |
| Xiaomi                   | 3         | 1.09%   |
| Marvell Technology Group | 3         | 1.09%   |
| TP-Link                  | 2         | 0.73%   |
| Samsung Electronics      | 2         | 0.73%   |
| MediaTek                 | 2         | 0.73%   |
| Google                   | 2         | 0.73%   |
| Sagem                    | 1         | 0.36%   |
| Ralink                   | 1         | 0.36%   |
| Qualcomm                 | 1         | 0.36%   |
| Nvidia                   | 1         | 0.36%   |
| MYRICOM                  | 1         | 0.36%   |
| LG Electronics           | 1         | 0.36%   |
| IMC Networks             | 1         | 0.36%   |
| Huawei Technologies      | 1         | 0.36%   |
| HMD Global               | 1         | 0.36%   |
| D-Link System            | 1         | 0.36%   |
| Arduino SA               | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 18.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.65%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.43%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 2.43%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.13%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.82%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.82%   |
| Intel Ethernet Controller I225-V                                  | 6         | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.22%   |
| Intel Wireless 7265                                               | 4         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.91%   |
| Intel Wireless-AC 9260                                            | 3         | 0.91%   |
| Intel Wireless 8260                                               | 3         | 0.91%   |
| Intel Wireless 7260                                               | 3         | 0.91%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 3         | 0.91%   |
| Intel I350 Gigabit Network Connection                             | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.91%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.61%   |
| Realtek Realtek Bluetooth Adapter                                 | 2         | 0.61%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.61%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 71        | 49.65%  |
| Qualcomm Atheros      | 28        | 19.58%  |
| Realtek Semiconductor | 20        | 13.99%  |
| Broadcom              | 13        | 9.09%   |
| Ralink Technology     | 4         | 2.8%    |
| TP-Link               | 2         | 1.4%    |
| MediaTek              | 2         | 1.4%    |
| Sagem                 | 1         | 0.7%    |
| Ralink                | 1         | 0.7%    |
| IMC Networks          | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 5.59%   |
| Intel Wi-Fi 6 AX200                                            | 8         | 5.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.2%    |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 4.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.8%    |
| Intel Wireless 7265                                            | 4         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.1%    |
| Intel Wireless-AC 9260                                         | 3         | 2.1%    |
| Intel Wireless 8260                                            | 3         | 2.1%    |
| Intel Wireless 7260                                            | 3         | 2.1%    |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 2.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.1%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 2.1%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.4%    |
| Realtek Realtek Bluetooth Adapter                              | 2         | 1.4%    |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.4%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.4%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.7%    |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 79        | 45.93%  |
| Intel                    | 72        | 41.86%  |
| Broadcom                 | 5         | 2.91%   |
| Xiaomi                   | 3         | 1.74%   |
| Marvell Technology Group | 3         | 1.74%   |
| Samsung Electronics      | 2         | 1.16%   |
| Google                   | 2         | 1.16%   |
| Qualcomm Atheros         | 1         | 0.58%   |
| Qualcomm                 | 1         | 0.58%   |
| Nvidia                   | 1         | 0.58%   |
| MYRICOM                  | 1         | 0.58%   |
| HMD Global               | 1         | 0.58%   |
| D-Link System            | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 32.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 6.56%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.83%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 3.83%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.28%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 3.28%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.64%   |
| Intel I350 Gigabit Network Connection                             | 3         | 1.64%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.09%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.09%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.09%   |
| Intel Ethernet Controller X550                                    | 2         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.09%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 1.09%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.55%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.55%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.55%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.55%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.55%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 157       | 54.51%  |
| WiFi     | 128       | 44.44%  |
| Modem    | 3         | 1.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 66.67%  |
| WiFi     | 59        | 33.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 96        | 49.23%  |
| 1     | 74        | 37.95%  |
| 3     | 10        | 5.13%   |
| 0     | 9         | 4.62%   |
| 5     | 2         | 1.03%   |
| 4     | 2         | 1.03%   |
| 7     | 1         | 0.51%   |
| 6     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 165       | 84.18%  |
| Yes  | 31        | 15.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 56.7%   |
| Qualcomm Atheros Communications | 10        | 10.31%  |
| Realtek Semiconductor           | 6         | 6.19%   |
| IMC Networks                    | 5         | 5.15%   |
| Dell                            | 4         | 4.12%   |
| Foxconn / Hon Hai               | 3         | 3.09%   |
| Broadcom                        | 3         | 3.09%   |
| Apple                           | 3         | 3.09%   |
| Lite-On Technology              | 2         | 2.06%   |
| Cambridge Silicon Radio         | 2         | 2.06%   |
| ASUSTek Computer                | 2         | 2.06%   |
| Ralink                          | 1         | 1.03%   |
| Creative Technology             | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 15.46%  |
| Intel AX201 Bluetooth                                       | 15        | 15.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 12.37%  |
| Intel AX200 Bluetooth                                       | 7         | 7.22%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.09%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 3.09%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 2         | 2.06%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.06%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.06%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.06%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.06%   |
| Apple Bluetooth Host Controller                             | 2         | 2.06%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.03%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.03%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.03%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.03%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.03%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.03%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.03%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.03%   |
| Lite-On Wireless_Device                                     | 1         | 1.03%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.03%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.03%   |
| Intel AX210 Bluetooth                                       | 1         | 1.03%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.03%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.03%   |
| IMC Networks Bluetooth Radio                                | 1         | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.03%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.03%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.03%   |
| Creative Creative Bluetooth Audio W2                        | 1         | 1.03%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1         | 1.03%   |
| ASUS Bluetooth USB module                                   | 1         | 1.03%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 135       | 60%     |
| AMD                         | 40        | 17.78%  |
| Nvidia                      | 32        | 14.22%  |
| Plantronics                 | 2         | 0.89%   |
| GN Netcom                   | 2         | 0.89%   |
| FiiO Electronics Technology | 2         | 0.89%   |
| XMOS                        | 1         | 0.44%   |
| SteelSeries ApS             | 1         | 0.44%   |
| Sony                        | 1         | 0.44%   |
| Realtek Semiconductor       | 1         | 0.44%   |
| Razer USA                   | 1         | 0.44%   |
| Micro Star International    | 1         | 0.44%   |
| Lenovo                      | 1         | 0.44%   |
| Kingston Technology         | 1         | 0.44%   |
| Ensoniq                     | 1         | 0.44%   |
| Creative Labs               | 1         | 0.44%   |
| Cambridge Silicon Radio     | 1         | 0.44%   |
| ASUSTek Computer            | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 5.58%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 5.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 4.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 2.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 1.86%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.49%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.49%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.49%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 4         | 1.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4         | 1.49%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.12%   |
| Intel Jasper Lake HD Audio                                                 | 3         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.12%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 48        | 21.82%  |
| Samsung Electronics          | 48        | 21.82%  |
| Micron Technology            | 22        | 10%     |
| Kingston                     | 18        | 8.18%   |
| Crucial                      | 17        | 7.73%   |
| Corsair                      | 14        | 6.36%   |
| Unknown                      | 9         | 4.09%   |
| G.Skill                      | 8         | 3.64%   |
| Unknown                      | 7         | 3.18%   |
| Elpida                       | 4         | 1.82%   |
| Unknown (ABCD)               | 3         | 1.36%   |
| Ramaxel Technology           | 3         | 1.36%   |
| A-DATA Technology            | 3         | 1.36%   |
| Transcend                    | 2         | 0.91%   |
| Nanya Technology             | 2         | 0.91%   |
| KomputerBay                  | 2         | 0.91%   |
| Qimonda                      | 1         | 0.45%   |
| PUSKILL                      | 1         | 0.45%   |
| PNY                          | 1         | 0.45%   |
| Patriot Memory (PDP Systems) | 1         | 0.45%   |
| Patriot                      | 1         | 0.45%   |
| Kingmax Semiconductor        | 1         | 0.45%   |
| Kingmax                      | 1         | 0.45%   |
| Hewlett-Packard              | 1         | 0.45%   |
| Apacer                       | 1         | 0.45%   |
| AMD                          | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 2.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 0.85%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.85%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.85%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1333MT/s           | 2         | 0.85%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s        | 2         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.42%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.42%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s              | 1         | 0.42%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.42%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1         | 0.42%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.42%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.42%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s            | 1         | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 88        | 46.32%  |
| DDR3    | 76        | 40%     |
| DDR2    | 8         | 4.21%   |
| LPDDR4  | 7         | 3.68%   |
| Unknown | 5         | 2.63%   |
| LPDDR3  | 4         | 2.11%   |
| LPDDR5  | 1         | 0.53%   |
| DDR     | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 57.14%  |
| DIMM         | 69        | 36.51%  |
| Row Of Chips | 10        | 5.29%   |
| Chip         | 1         | 0.53%   |
| Unknown      | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 38.05%  |
| 4096  | 64        | 31.22%  |
| 16384 | 27        | 13.17%  |
| 2048  | 23        | 11.22%  |
| 32768 | 11        | 5.37%   |
| 1024  | 2         | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 23.12%  |
| 3200    | 37        | 18.59%  |
| 2400    | 22        | 11.06%  |
| 2667    | 18        | 9.05%   |
| 2133    | 18        | 9.05%   |
| 1333    | 17        | 8.54%   |
| 1334    | 9         | 4.52%   |
| 800     | 4         | 2.01%   |
| 2666    | 3         | 1.51%   |
| 1067    | 3         | 1.51%   |
| 667     | 3         | 1.51%   |
| 4267    | 2         | 1.01%   |
| 3600    | 2         | 1.01%   |
| 3000    | 2         | 1.01%   |
| 1066    | 2         | 1.01%   |
| 975     | 2         | 1.01%   |
| Unknown | 2         | 1.01%   |
| 6400    | 1         | 0.5%    |
| 4266    | 1         | 0.5%    |
| 3400    | 1         | 0.5%    |
| 1867    | 1         | 0.5%    |
| 1866    | 1         | 0.5%    |
| 933     | 1         | 0.5%    |
| 533     | 1         | 0.5%    |

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
| Chicony Electronics           | 19        | 24.36%  |
| IMC Networks                  | 12        | 15.38%  |
| Sunplus Innovation Technology | 8         | 10.26%  |
| Microdia                      | 8         | 10.26%  |
| Acer                          | 6         | 7.69%   |
| Realtek Semiconductor         | 4         | 5.13%   |
| Syntek                        | 3         | 3.85%   |
| Luxvisions Innotech Limited   | 2         | 2.56%   |
| Logitech                      | 2         | 2.56%   |
| Lite-On Technology            | 2         | 2.56%   |
| Z-Star Microelectronics       | 1         | 1.28%   |
| Sonix Technology              | 1         | 1.28%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.28%   |
| Ricoh                         | 1         | 1.28%   |
| Quanta                        | 1         | 1.28%   |
| OmniVision Technologies       | 1         | 1.28%   |
| Intel                         | 1         | 1.28%   |
| Genesys Logic                 | 1         | 1.28%   |
| DigiTech                      | 1         | 1.28%   |
| ARC International             | 1         | 1.28%   |
| Apple                         | 1         | 1.28%   |
| Alcor Micro                   | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 5         | 6.33%   |
| Acer Integrated Camera                         | 5         | 6.33%   |
| Microdia Integrated_Webcam_HD                  | 4         | 5.06%   |
| IMC Networks EasyCamera                        | 4         | 5.06%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 3         | 3.8%    |
| Realtek Integrated_Webcam_HD                   | 3         | 3.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)       | 3         | 3.8%    |
| Syntek EasyCamera                              | 2         | 2.53%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 2.53%   |
| Microdia Integrated Webcam                     | 2         | 2.53%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 2.53%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.53%   |
| Chicony USB2.0 VGA UVC WebCam                  | 2         | 2.53%   |
| Chicony HP HD Camera                           | 2         | 2.53%   |
| Chicony HD WebCam                              | 2         | 2.53%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1         | 1.27%   |
| Syntek Integrated Camera                       | 1         | 1.27%   |
| Sunplus Laptop Integrated Webcam HD            | 1         | 1.27%   |
| Sunplus HP HD Webcam [Fixed]                   | 1         | 1.27%   |
| Sunplus HD WebCam                              | 1         | 1.27%   |
| Sonix USB2.0 HD UVC WebCam                     | 1         | 1.27%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1         | 1.27%   |
| Ricoh Integrated Webcam                        | 1         | 1.27%   |
| Realtek Integrated Webcam HD                   | 1         | 1.27%   |
| Quanta VGA WebCam                              | 1         | 1.27%   |
| OmniVision Monitor Webcam                      | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD           | 1         | 1.27%   |
| Microdia JOYACCESS JA-Webcam                   | 1         | 1.27%   |
| Luxvisions Innotech Limited Integrated Camera  | 1         | 1.27%   |
| Luxvisions Innotech Limited HP HD Camera       | 1         | 1.27%   |
| Logitech Webcam C270                           | 1         | 1.27%   |
| Logitech HD Pro Webcam C920                    | 1         | 1.27%   |
| Lite-On Integrated Camera                      | 1         | 1.27%   |
| Lite-On HP Wide Vision HD Camera               | 1         | 1.27%   |
| Intel RealSense 3D Camera (Front F200)         | 1         | 1.27%   |
| IMC Networks USB2.0 HD IR UVC WebCam           | 1         | 1.27%   |
| IMC Networks Integrated Webcam                 | 1         | 1.27%   |
| IMC Networks HP TrueVision HD Camera           | 1         | 1.27%   |
| IMC Networks HD Camera                         | 1         | 1.27%   |
| Genesys Logic Camera                           | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 46.15%  |
| Validity Sensors           | 3         | 23.08%  |
| Upek                       | 1         | 7.69%   |
| Shenzhen Goodix Technology | 1         | 7.69%   |
| LighTuning Technology      | 1         | 7.69%   |
| DigitalPersona             | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 7.69%   |
| Validity Sensors Synaptics WBDI                           | 1         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 1         | 7.69%   |
| Synaptics product 0x00be                                  | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 7.69%   |
| LighTuning EgisTec EH575                                  | 1         | 7.69%   |
| DigitalPersona Fingerprint Reader                         | 1         | 7.69%   |
| Unknown                                                   | 1         | 7.69%   |

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
| 1     | 73        | 37.24%  |
| 2     | 51        | 26.02%  |
| 0     | 37        | 18.88%  |
| 3     | 27        | 13.78%  |
| 4     | 6         | 3.06%   |
| 6     | 1         | 0.51%   |
| 5     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 133       | 51.35%  |
| Bluetooth                | 48        | 18.53%  |
| Net/wireless             | 29        | 11.2%   |
| Card reader              | 15        | 5.79%   |
| Firewire controller      | 13        | 5.02%   |
| Fingerprint reader       | 12        | 4.63%   |
| Net/ethernet             | 4         | 1.54%   |
| Storage                  | 3         | 1.16%   |
| Sound                    | 1         | 0.39%   |
| Network                  | 1         | 0.39%   |

