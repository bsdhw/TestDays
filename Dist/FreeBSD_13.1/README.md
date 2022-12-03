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

Total: 220

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 170       | 95.51%  |
| arm64 | 4         | 2.25%   |
| arm   | 3         | 1.69%   |
| i386  | 1         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Console    | 57        | 32.02%  |
| KDE5       | 32        | 17.98%  |
| XFCE       | 28        | 15.73%  |
| GNOME      | 16        | 8.99%   |
| TWM        | 12        | 6.74%   |
| MATE       | 7         | 3.93%   |
| Openbox    | 6         | 3.37%   |
| i3         | 6         | 3.37%   |
| LXDE       | 3         | 1.69%   |
| Cinnamon   | 3         | 1.69%   |
| LXQt       | 2         | 1.12%   |
| xfwm       | 1         | 0.56%   |
| X-Cinnamon | 1         | 0.56%   |
| plasma     | 1         | 0.56%   |
| IceWM      | 1         | 0.56%   |
| dwm        | 1         | 0.56%   |
| Compton    | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 113       | 63.48%  |
| Console | 59        | 33.15%  |
| Wayland | 6         | 3.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 96        | 53.93%  |
| SDDM    | 34        | 19.1%   |
| SLiM    | 18        | 10.11%  |
| XDM     | 10        | 5.62%   |
| GDM     | 10        | 5.62%   |
| LightDM | 9         | 5.06%   |
| PCDM    | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 127       | 70.95%  |
| en_US           | 22        | 12.29%  |
| ru_RU           | 10        | 5.59%   |
| Unknown         | 7         | 3.91%   |
| zh_CN           | 4         | 2.23%   |
| fr_FR           | 4         | 2.23%   |
| ja_JP           | 1         | 0.56%   |
| en_US.ISO8859-1 | 1         | 0.56%   |
| en_GB           | 1         | 0.56%   |
| en_AU           | 1         | 0.56%   |
| de_DE           | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 129       | 72.07%  |
| BIOS | 50        | 27.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 120       | 67.04%  |
| Ufs  | 59        | 32.96%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 162       | 91.01%  |
| MBR     | 14        | 7.87%   |
| BSD     | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 34        | 19.1%   |
| Lenovo                  | 28        | 15.73%  |
| ASUSTek Computer        | 24        | 13.48%  |
| Hewlett-Packard         | 13        | 7.3%    |
| Intel                   | 10        | 5.62%   |
| Gigabyte Technology     | 9         | 5.06%   |
| Unknown                 | 8         | 4.49%   |
| MSI                     | 6         | 3.37%   |
| ASRock                  | 6         | 3.37%   |
| Acer                    | 6         | 3.37%   |
| Google                  | 3         | 1.69%   |
| Fujitsu                 | 3         | 1.69%   |
| TUXEDO                  | 2         | 1.12%   |
| Toshiba                 | 2         | 1.12%   |
| System76                | 2         | 1.12%   |
| Supermicro              | 2         | 1.12%   |
| Samsung Electronics     | 2         | 1.12%   |
| Apple                   | 2         | 1.12%   |
| Sony                    | 1         | 0.56%   |
| Raspberry Pi Foundation | 1         | 0.56%   |
| PC Engines              | 1         | 0.56%   |
| Notebook                | 1         | 0.56%   |
| NITRINOnet              | 1         | 0.56%   |
| NF-M2S                  | 1         | 0.56%   |
| MouseComputer           | 1         | 0.56%   |
| LG Electronics          | 1         | 0.56%   |
| Huanan                  | 1         | 0.56%   |
| GVC                     | 1         | 0.56%   |
| GPD                     | 1         | 0.56%   |
| Fujitsu Siemens         | 1         | 0.56%   |
| Foxconn                 | 1         | 0.56%   |
| BESSTAR Tech            | 1         | 0.56%   |
| ASRockRack              | 1         | 0.56%   |
| AMI                     | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 4.49%   |
| ASUS All Series                             | 4         | 2.25%   |
| MSI MS-7817                                 | 2         | 1.12%   |
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.12%   |
| Google Peppy                                | 2         | 1.12%   |
| Dell Precision T3600                        | 2         | 1.12%   |
| Dell Precision M4500                        | 2         | 1.12%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.56%   |
| TUXEDO Aura 15 Gen1                         | 1         | 0.56%   |
| Toshiba Satellite L305D                     | 1         | 0.56%   |
| Toshiba Satellite A300                      | 1         | 0.56%   |
| System76 Gazelle                            | 1         | 0.56%   |
| System76 Galago Pro                         | 1         | 0.56%   |
| Supermicro MBD-X8DT6-A-IS018                | 1         | 0.56%   |
| Supermicro Icebreaker 4824                  | 1         | 0.56%   |
| Sony VGN-NS21M_S                            | 1         | 0.56%   |
| Samsung R530/R730/R540                      | 1         | 0.56%   |
| Samsung 750TDA                              | 1         | 0.56%   |
| RPi Raspberry Pi                            | 1         | 0.56%   |
| PC Engines APU3                             | 1         | 0.56%   |
| Notebook N7x0WU                             | 1         | 0.56%   |
| NITRINOnet M360RUS56                        | 1         | 0.56%   |
| NF-M2S ABIT                                 | 1         | 0.56%   |
| MSI MS-B120                                 | 1         | 0.56%   |
| MSI MS-7D09                                 | 1         | 0.56%   |
| MSI MS-7D08                                 | 1         | 0.56%   |
| MSI GF63 Thin 9SC                           | 1         | 0.56%   |
| MouseComputer B360M                         | 1         | 0.56%   |
| LG 17Z990-R.AAC9U1                          | 1         | 0.56%   |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.56%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-     | 1         | 0.56%   |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.56%   |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.56%   |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.56%   |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.56%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.56%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.56%   |
| Lenovo ThinkPad W520 4282AD4                | 1         | 0.56%   |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 16        | 8.99%   |
| Dell Latitude                | 9         | 5.06%   |
| Unknown                      | 8         | 4.49%   |
| Dell Precision               | 7         | 3.93%   |
| Dell OptiPlex                | 6         | 3.37%   |
| Dell Inspiron                | 6         | 3.37%   |
| Lenovo IdeaPad               | 5         | 2.81%   |
| ASUS ZenBook                 | 5         | 2.81%   |
| ASUS All                     | 4         | 2.25%   |
| ASUS VivoBook                | 3         | 1.69%   |
| ASUS ROG                     | 3         | 1.69%   |
| ASUS PRIME                   | 3         | 1.69%   |
| Acer Aspire                  | 3         | 1.69%   |
| Toshiba Satellite            | 2         | 1.12%   |
| MSI MS-7817                  | 2         | 1.12%   |
| Lenovo ThinkCentre           | 2         | 1.12%   |
| HP EliteDesk                 | 2         | 1.12%   |
| HP EliteBook                 | 2         | 1.12%   |
| Google Peppy                 | 2         | 1.12%   |
| Dell Vostro                  | 2         | 1.12%   |
| Dell G5                      | 2         | 1.12%   |
| TUXEDO InfinityBook13V3      | 1         | 0.56%   |
| TUXEDO Aura                  | 1         | 0.56%   |
| System76 Gazelle             | 1         | 0.56%   |
| System76 Galago              | 1         | 0.56%   |
| Supermicro MBD-X8DT6-A-IS018 | 1         | 0.56%   |
| Supermicro Icebreaker        | 1         | 0.56%   |
| Sony VGN-NS21M               | 1         | 0.56%   |
| Samsung R530                 | 1         | 0.56%   |
| Samsung 750TDA               | 1         | 0.56%   |
| RPi Raspberry                | 1         | 0.56%   |
| PC Engines APU3              | 1         | 0.56%   |
| Notebook N7x0WU              | 1         | 0.56%   |
| NITRINOnet M360RUS56         | 1         | 0.56%   |
| NF-M2S ABIT                  | 1         | 0.56%   |
| MSI MS-B120                  | 1         | 0.56%   |
| MSI MS-7D09                  | 1         | 0.56%   |
| MSI MS-7D08                  | 1         | 0.56%   |
| MSI GF63                     | 1         | 0.56%   |
| MouseComputer B360M          | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 28        | 15.73%  |
| 2020    | 25        | 14.04%  |
| 2022    | 17        | 9.55%   |
| 2019    | 16        | 8.99%   |
| 2018    | 15        | 8.43%   |
| 2014    | 11        | 6.18%   |
| 2016    | 10        | 5.62%   |
| 2011    | 9         | 5.06%   |
| 2013    | 8         | 4.49%   |
| 2012    | 8         | 4.49%   |
| Unknown | 7         | 3.93%   |
| 2015    | 6         | 3.37%   |
| 2017    | 5         | 2.81%   |
| 2010    | 5         | 2.81%   |
| 2008    | 5         | 2.81%   |
| 2009    | 3         | 1.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 86        | 48.31%  |
| Desktop        | 74        | 41.57%  |
| Mini pc        | 11        | 6.18%   |
| Server         | 3         | 1.69%   |
| Convertible    | 2         | 1.12%   |
| System on chip | 1         | 0.56%   |
| All in one     | 1         | 0.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 97.19%  |
| Yes  | 5         | 2.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 58        | 32.4%   |
| 16.01-24.0  | 48        | 26.82%  |
| 4.01-8.0    | 22        | 12.29%  |
| 32.01-64.0  | 17        | 9.5%    |
| 64.01-256.0 | 16        | 8.94%   |
| 2.01-3.0    | 7         | 3.91%   |
| 24.01-32.0  | 5         | 2.79%   |
| 0.01-0.5    | 3         | 1.68%   |
| 3.01-4.0    | 2         | 1.12%   |
| 0.51-1.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 69        | 38.55%  |
| 0.51-1.0   | 52        | 29.05%  |
| 1.01-2.0   | 34        | 18.99%  |
| 2.01-3.0   | 13        | 7.26%   |
| 3.01-4.0   | 4         | 2.23%   |
| 0          | 4         | 2.23%   |
| 4.01-8.0   | 1         | 0.56%   |
| 24.01-32.0 | 1         | 0.56%   |
| 8.01-16.0  | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 95        | 53.07%  |
| 2      | 37        | 20.67%  |
| 3      | 13        | 7.26%   |
| 0      | 12        | 6.7%    |
| 4      | 10        | 5.59%   |
| 8      | 3         | 1.68%   |
| 10     | 2         | 1.12%   |
| 6      | 2         | 1.12%   |
| 18     | 1         | 0.56%   |
| 16     | 1         | 0.56%   |
| 15     | 1         | 0.56%   |
| 11     | 1         | 0.56%   |
| 5      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 71.91%  |
| Yes       | 50        | 28.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 79.21%  |
| No        | 37        | 20.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 64.04%  |
| No        | 64        | 35.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 53.37%  |
| Yes       | 83        | 46.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 43        | 24.02%  |
| Russia      | 20        | 11.17%  |
| Germany     | 14        | 7.82%   |
| France      | 12        | 6.7%    |
| Spain       | 7         | 3.91%   |
| China       | 6         | 3.35%   |
| Canada      | 6         | 3.35%   |
| Italy       | 5         | 2.79%   |
| India       | 5         | 2.79%   |
| Austria     | 5         | 2.79%   |
| UK          | 4         | 2.23%   |
| Netherlands | 4         | 2.23%   |
| Japan       | 4         | 2.23%   |
| Czechia     | 4         | 2.23%   |
| Australia   | 4         | 2.23%   |
| Thailand    | 3         | 1.68%   |
| Venezuela   | 2         | 1.12%   |
| Turkey      | 2         | 1.12%   |
| Philippines | 2         | 1.12%   |
| New Zealand | 2         | 1.12%   |
| Hong Kong   | 2         | 1.12%   |
| Bulgaria    | 2         | 1.12%   |
| Uruguay     | 1         | 0.56%   |
| Taiwan      | 1         | 0.56%   |
| South Korea | 1         | 0.56%   |
| Slovenia    | 1         | 0.56%   |
| Norway      | 1         | 0.56%   |
| Mexico      | 1         | 0.56%   |
| Malaysia    | 1         | 0.56%   |
| Lithuania   | 1         | 0.56%   |
| Latvia      | 1         | 0.56%   |
| Kenya       | 1         | 0.56%   |
| Israel      | 1         | 0.56%   |
| Ireland     | 1         | 0.56%   |
| Hungary     | 1         | 0.56%   |
| Guadeloupe  | 1         | 0.56%   |
| Greece      | 1         | 0.56%   |
| Finland     | 1         | 0.56%   |
| Croatia     | 1         | 0.56%   |
| Brazil      | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 10        | 5.56%   |
| Vienna            | 4         | 2.22%   |
| Paris             | 4         | 2.22%   |
| Ozersk            | 4         | 2.22%   |
| Frisco            | 4         | 2.22%   |
| Brno              | 4         | 2.22%   |
| Tamm              | 3         | 1.67%   |
| Omaha             | 3         | 1.67%   |
| Madrid            | 3         | 1.67%   |
| Wellington        | 2         | 1.11%   |
| St Petersburg     | 2         | 1.11%   |
| Redmond           | 2         | 1.11%   |
| Nashville         | 2         | 1.11%   |
| Maracaibo         | 2         | 1.11%   |
| Charlotte         | 2         | 1.11%   |
| Central           | 2         | 1.11%   |
| Carry-le-Rouet    | 2         | 1.11%   |
| Zhumadian         | 1         | 0.56%   |
| Zagreb            | 1         | 0.56%   |
| Yashio            | 1         | 0.56%   |
| Yangcheon-gu      | 1         | 0.56%   |
| Xiamen            | 1         | 0.56%   |
| Xi'an             | 1         | 0.56%   |
| Woerdense Verlaat | 1         | 0.56%   |
| Wheatland         | 1         | 0.56%   |
| Wenatchee         | 1         | 0.56%   |
| Waldbrunn         | 1         | 0.56%   |
| Vilnius           | 1         | 0.56%   |
| Vaulx-en-Velin    | 1         | 0.56%   |
| Vancouver         | 1         | 0.56%   |
| Valladolid        | 1         | 0.56%   |
| Turku             | 1         | 0.56%   |
| Trivandrum        | 1         | 0.56%   |
| Toronto           | 1         | 0.56%   |
| Tlalnepantla      | 1         | 0.56%   |
| Tiel              | 1         | 0.56%   |
| Thousand Oaks     | 1         | 0.56%   |
| Thessaloniki      | 1         | 0.56%   |
| Tel Aviv          | 1         | 0.56%   |
| Taito             | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 105    | 24.8%   |
| Samsung Electronics | 43        | 58     | 17.48%  |
| Seagate             | 31        | 77     | 12.6%   |
| Crucial             | 18        | 25     | 7.32%   |
| Kingston            | 14        | 15     | 5.69%   |
| Toshiba             | 12        | 19     | 4.88%   |
| Intel               | 7         | 16     | 2.85%   |
| SK hynix            | 6         | 6      | 2.44%   |
| Hitachi             | 6         | 7      | 2.44%   |
| A-DATA Technology   | 5         | 8      | 2.03%   |
| Transcend           | 4         | 4      | 1.63%   |
| SanDisk             | 4         | 4      | 1.63%   |
| KIOXIA              | 3         | 3      | 1.22%   |
| Hewlett-Packard     | 3         | 3      | 1.22%   |
| Gigabyte Technology | 3         | 3      | 1.22%   |
| Silicon Motion      | 2         | 2      | 0.81%   |
| Micron Technology   | 2         | 3      | 0.81%   |
| Hikvision           | 2         | 2      | 0.81%   |
| Apple               | 2         | 2      | 0.81%   |
| Verbatim            | 1         | 1      | 0.41%   |
| UMIS                | 1         | 1      | 0.41%   |
| SPCC                | 1         | 1      | 0.41%   |
| PNY                 | 1         | 2      | 0.41%   |
| Phison              | 1         | 1      | 0.41%   |
| ORICO               | 1         | 1      | 0.41%   |
| OCZ                 | 1         | 1      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| LITEONIT            | 1         | 1      | 0.41%   |
| LITEON              | 1         | 1      | 0.41%   |
| Lexar               | 1         | 2      | 0.41%   |
| Lenovo              | 1         | 1      | 0.41%   |
| HGST                | 1         | 1      | 0.41%   |
| EAGET               | 1         | 1      | 0.41%   |
| China               | 1         | 1      | 0.41%   |
| CFD                 | 1         | 1      | 0.41%   |
| BR                  | 1         | 1      | 0.41%   |
| BIWIN               | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.41%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.41%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 1.06%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.06%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 1.06%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 1.06%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.06%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.06%   |
| A-DATA SU650 240GB                      | 3         | 1.06%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 2         | 0.7%    |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.7%    |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.7%    |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 0.7%    |
| WDC WD30EFRX-68AX9N0 3TB                | 2         | 0.7%    |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.7%    |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.7%    |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 0.7%    |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.7%    |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.7%    |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.7%    |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.7%    |
| Samsung SSD 840 EVO 120GB               | 2         | 0.7%    |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.7%    |
| Kingston SA400S37120G 120GB             | 2         | 0.7%    |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.7%    |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.7%    |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.7%    |
| Crucial CT1000BX500SSD1 1TB             | 2         | 0.7%    |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.35%   |
| WDC WDS500G2X0C-00L350 500GB            | 1         | 0.35%   |
| WDC WDS500G1B0A-00H9H0 500GB            | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.35%   |
| WDC WDS250G2B0C-00PXH0 250GB            | 1         | 0.35%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.35%   |
| WDC WDS250G2B0A-00SM50 250GB            | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.35%   |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.35%   |
| WDC WDS100T2B0B-00YS70 1TB              | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 42        | 84     | 46.15%  |
| Seagate             | 30        | 76     | 32.97%  |
| Toshiba             | 9         | 16     | 9.89%   |
| Hitachi             | 6         | 7      | 6.59%   |
| Samsung Electronics | 1         | 4      | 1.1%    |
| HGST                | 1         | 1      | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 31     | 24.47%  |
| Crucial             | 15        | 17     | 15.96%  |
| WDC                 | 8         | 8      | 8.51%   |
| Kingston            | 8         | 9      | 8.51%   |
| Intel               | 5         | 14     | 5.32%   |
| A-DATA Technology   | 5         | 8      | 5.32%   |
| SanDisk             | 4         | 4      | 4.26%   |
| Transcend           | 3         | 3      | 3.19%   |
| Toshiba             | 2         | 2      | 2.13%   |
| Hikvision           | 2         | 2      | 2.13%   |
| Verbatim            | 1         | 1      | 1.06%   |
| SPCC                | 1         | 1      | 1.06%   |
| SK hynix            | 1         | 1      | 1.06%   |
| PNY                 | 1         | 2      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| ORICO               | 1         | 1      | 1.06%   |
| OCZ                 | 1         | 1      | 1.06%   |
| Micron Technology   | 1         | 2      | 1.06%   |
| LITEONIT            | 1         | 1      | 1.06%   |
| LITEON              | 1         | 1      | 1.06%   |
| Lexar               | 1         | 2      | 1.06%   |
| Lenovo              | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| Gigabyte Technology | 1         | 1      | 1.06%   |
| China               | 1         | 1      | 1.06%   |
| CFD                 | 1         | 1      | 1.06%   |
| BR                  | 1         | 1      | 1.06%   |
| BIWIN               | 1         | 1      | 1.06%   |
| Apple               | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 83        | 120    | 37.9%   |
| HDD  | 75        | 190    | 34.25%  |
| NVMe | 61        | 72     | 27.85%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 131       | 310    | 68.23%  |
| NVMe | 61        | 72     | 31.77%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 114    | 49.41%  |
| 0.51-1.0   | 53        | 74     | 31.18%  |
| 1.01-2.0   | 14        | 29     | 8.24%   |
| 3.01-4.0   | 6         | 10     | 3.53%   |
| 4.01-10.0  | 6         | 46     | 3.53%   |
| 2.01-3.0   | 4         | 17     | 2.35%   |
| 10.01-20.0 | 3         | 20     | 1.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 61        | 34.08%  |
| 251-500        | 41        | 22.91%  |
| 501-1000       | 32        | 17.88%  |
| 51-100         | 15        | 8.38%   |
| 21-50          | 12        | 6.7%    |
| 1001-2000      | 7         | 3.91%   |
| 1-20           | 5         | 2.79%   |
| 2001-3000      | 3         | 1.68%   |
| More than 3000 | 2         | 1.12%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 142       | 79.33%  |
| 21-50          | 21        | 11.73%  |
| 101-250        | 5         | 2.79%   |
| 51-100         | 5         | 2.79%   |
| 251-500        | 3         | 1.68%   |
| More than 3000 | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 6.06%   |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 3.03%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 3.03%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 3.03%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 3.03%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 3.03%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 3.03%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 3.03%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 3.03%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 3.03%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 3.03%   |
| Phison NETLIST SSD 8GB-001                   | 1         | 1      | 3.03%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 3.03%   |
| LITEON IT LST-16S9G-HP 16GB                  | 1         | 1      | 3.03%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 3.03%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 3.03%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 3.03%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 3.03%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 3.03%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 3.03%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 3.03%   |
| Hitachi HDS721010CLA332 1TB                  | 1         | 1      | 3.03%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.03%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 3.03%   |
| A-DATA Technology SU650 120GB                | 1         | 1      | 3.03%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 9      | 19.35%  |
| Seagate             | 6         | 7      | 19.35%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Kingston            | 3         | 4      | 9.68%   |
| Toshiba             | 2         | 2      | 6.45%   |
| A-DATA Technology   | 2         | 3      | 6.45%   |
| SPCC                | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Phison              | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 2      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Hewlett-Packard     | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 9      | 30%     |
| Seagate         | 6         | 7      | 30%     |
| Hitachi         | 4         | 4      | 20%     |
| Toshiba         | 2         | 2      | 10%     |
| HGST            | 1         | 1      | 5%      |
| Hewlett-Packard | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 24     | 63.33%  |
| SSD  | 11        | 14     | 36.67%  |

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
| Works    | 149       | 334    | 81.87%  |
| Malfunc  | 28        | 38     | 15.38%  |
| Detected | 5         | 10     | 2.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 122       | 54.22%  |
| AMD                         | 23        | 10.22%  |
| Samsung Electronics         | 22        | 9.78%   |
| SanDisk                     | 14        | 6.22%   |
| Kingston Technology Company | 6         | 2.67%   |
| Broadcom / LSI              | 6         | 2.67%   |
| Silicon Motion              | 5         | 2.22%   |
| SK hynix                    | 4         | 1.78%   |
| Micron/Crucial Technology   | 3         | 1.33%   |
| Marvell Technology Group    | 3         | 1.33%   |
| KIOXIA                      | 3         | 1.33%   |
| ASMedia Technology          | 3         | 1.33%   |
| Phison Electronics          | 2         | 0.89%   |
| Nvidia                      | 2         | 0.89%   |
| Micron Technology           | 2         | 0.89%   |
| Union Memory (Shenzhen)     | 1         | 0.44%   |
| Transcend                   | 1         | 0.44%   |
| Toshiba                     | 1         | 0.44%   |
| Silicon Image               | 1         | 0.44%   |
| Seagate Technology          | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 6.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 4.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.29%   |
| Unknown                                                                        | 8         | 3.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 2.06%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.65%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4         | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.65%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.65%   |
| SanDisk unknown                                                                | 3         | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.23%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.23%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.82%   |
| SK hynix BC511                                                                 | 2         | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.82%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.82%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 133       | 59.64%  |
| NVMe | 61        | 27.35%  |
| RAID | 13        | 5.83%   |
| IDE  | 11        | 4.93%   |
| SAS  | 5         | 2.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 142       | 79.78%  |
| AMD    | 29        | 16.29%  |
| ARM    | 7         | 3.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 2.23%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 3         | 1.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.68%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.68%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.12%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 1.12%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.12%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.12%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.12%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.12%   |
| Intel Celeron 2955U @ 1.40GHz           | 2         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.12%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 1.12%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.12%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.56%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.56%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.56%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.56%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.56%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.56%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.56%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.56%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH       | 1         | 0.56%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.56%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz     | 1         | 0.56%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.56%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.56%   |
| Intel Pentium II                        | 1         | 0.56%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 1         | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.56%   |
| Intel Pentium CPU G3240T @ 2.70GHz      | 1         | 0.56%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.56%   |
| Intel Genuine CPU                       | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 45        | 25.28%  |
| Intel Core i7        | 36        | 20.22%  |
| Other                | 13        | 7.3%    |
| Intel Xeon           | 11        | 6.18%   |
| Intel Core i3        | 11        | 6.18%   |
| Intel Celeron        | 10        | 5.62%   |
| AMD Ryzen 5          | 7         | 3.93%   |
| Intel Core 2 Duo     | 5         | 2.81%   |
| ARM Cortex           | 5         | 2.81%   |
| AMD Ryzen 7          | 5         | 2.81%   |
| AMD Ryzen 3          | 5         | 2.81%   |
| Intel Atom           | 4         | 2.25%   |
| Intel Pentium        | 3         | 1.69%   |
| AMD Ryzen 9          | 2         | 1.12%   |
| AMD Ryzen 7 PRO      | 2         | 1.12%   |
| AMD A8               | 2         | 1.12%   |
| Intel Xeon Gold      | 1         | 0.56%   |
| Intel Pentium Silver | 1         | 0.56%   |
| Intel Pentium Gold   | 1         | 0.56%   |
| Intel Pentium Dual   | 1         | 0.56%   |
| Intel Genuine        | 1         | 0.56%   |
| Intel Core 2 Quad    | 1         | 0.56%   |
| AMD Phenom II X2     | 1         | 0.56%   |
| AMD GX               | 1         | 0.56%   |
| AMD E2               | 1         | 0.56%   |
| AMD Athlon X2        | 1         | 0.56%   |
| AMD Athlon 64 X2     | 1         | 0.56%   |
| AMD A10              | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 65        | 36.52%  |
| 2       | 56        | 31.46%  |
| 8       | 14        | 7.87%   |
| 6       | 14        | 7.87%   |
| Unknown | 10        | 5.62%   |
| 16      | 8         | 4.49%   |
| 12      | 5         | 2.81%   |
| 24      | 2         | 1.12%   |
| 1       | 2         | 1.12%   |
| 28      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 168       | 94.38%  |
| Unknown | 7         | 3.93%   |
| 2       | 3         | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 97        | 54.49%  |
| 1       | 70        | 39.33%  |
| Unknown | 11        | 6.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 38        | 21.23%  |
| Haswell         | 19        | 10.61%  |
| SandyBridge     | 15        | 8.38%   |
| Unknown         | 15        | 8.38%   |
| IvyBridge       | 12        | 6.7%    |
| Skylake         | 8         | 4.47%   |
| TigerLake       | 7         | 3.91%   |
| CometLake       | 7         | 3.91%   |
| Broadwell       | 7         | 3.91%   |
| Zen+            | 5         | 2.79%   |
| Zen 3           | 5         | 2.79%   |
| Zen 2           | 5         | 2.79%   |
| Westmere        | 5         | 2.79%   |
| Silvermont      | 4         | 2.23%   |
| Core            | 4         | 2.23%   |
| Zen             | 3         | 1.68%   |
| Puma            | 3         | 1.68%   |
| Penryn          | 3         | 1.68%   |
| Goldmont plus   | 3         | 1.68%   |
| Bonnell         | 3         | 1.68%   |
| Piledriver      | 1         | 0.56%   |
| P6              | 1         | 0.56%   |
| K8 Hammer       | 1         | 0.56%   |
| K8 & K10 hybrid | 1         | 0.56%   |
| K10             | 1         | 0.56%   |
| IceLake         | 1         | 0.56%   |
| Goldmont        | 1         | 0.56%   |
| Excavator       | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 111       | 57.51%  |
| Nvidia                               | 40        | 20.73%  |
| AMD                                  | 35        | 18.13%  |
| Matrox Electronics Systems           | 5         | 2.59%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.52%   |
| ASPEED Technology                    | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 11        | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 3.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 3.03%   |
| Intel UHD Graphics 620                                                      | 4         | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.02%   |
| Intel HD Graphics 620                                                       | 4         | 2.02%   |
| Intel HD Graphics 5500                                                      | 4         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 2.02%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.02%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.52%   |
| Intel HD Graphics 630                                                       | 3         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.52%   |
| AMD Renoir                                                                  | 3         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.52%   |
| AMD Lucienne                                                                | 3         | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.01%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.01%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 1.01%   |
| Nvidia GP108BM [GeForce MX250]                                              | 2         | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 1.01%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.01%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.01%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 1.01%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.01%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2         | 1.01%   |
| Intel HD Graphics 530                                                       | 2         | 1.01%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.01%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 84        | 47.19%  |
| 1 x AMD                                  | 26        | 14.61%  |
| 1 x Nvidia                               | 20        | 11.24%  |
| Intel + Nvidia                           | 17        | 9.55%   |
| Other                                    | 9         | 5.06%   |
| 2 x Intel                                | 5         | 2.81%   |
| 1 x Matrox                               | 5         | 2.81%   |
| Intel + AMD                              | 5         | 2.81%   |
| 2 x AMD                                  | 2         | 1.12%   |
| AMD + Nvidia                             | 2         | 1.12%   |
| 2 x Nvidia                               | 1         | 0.56%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.56%   |
| 1 x ASPEED                               | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 80.34%  |
| Proprietary | 25        | 14.04%  |
| Unknown     | 10        | 5.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 79.78%  |
| 0.51-1.0   | 12        | 6.74%   |
| 1.01-2.0   | 9         | 5.06%   |
| 0.01-0.5   | 6         | 3.37%   |
| 5.01-6.0   | 3         | 1.69%   |
| 3.01-4.0   | 3         | 1.69%   |
| 7.01-8.0   | 2         | 1.12%   |
| 2.01-3.0   | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 17        | 13.39%  |
| LG Display           | 15        | 11.81%  |
| BOE                  | 14        | 11.02%  |
| AU Optronics         | 11        | 8.66%   |
| Chimei Innolux       | 10        | 7.87%   |
| Acer                 | 6         | 4.72%   |
| Lenovo               | 5         | 3.94%   |
| Goldstar             | 4         | 3.15%   |
| Dell                 | 4         | 3.15%   |
| BenQ                 | 4         | 3.15%   |
| AOC                  | 4         | 3.15%   |
| Toshiba              | 3         | 2.36%   |
| Philips              | 3         | 2.36%   |
| ViewSonic            | 2         | 1.57%   |
| Sharp                | 2         | 1.57%   |
| Sceptre Tech         | 2         | 1.57%   |
| LGD                  | 2         | 1.57%   |
| CSO                  | 2         | 1.57%   |
| YTH                  | 1         | 0.79%   |
| Vestel Elektronik    | 1         | 0.79%   |
| USR                  | 1         | 0.79%   |
| Unknown (XXX)        | 1         | 0.79%   |
| Panasonic            | 1         | 0.79%   |
| Mi                   | 1         | 0.79%   |
| LG Philips           | 1         | 0.79%   |
| LG Electronics       | 1         | 0.79%   |
| JDI                  | 1         | 0.79%   |
| IOD                  | 1         | 0.79%   |
| Iiyama               | 1         | 0.79%   |
| Idek Iiyama          | 1         | 0.79%   |
| HannStar             | 1         | 0.79%   |
| Compal               | 1         | 0.79%   |
| ASUSTek Computer     | 1         | 0.79%   |
| Apple                | 1         | 0.79%   |
| Ancor Communications | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 1.55%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.55%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.55%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.55%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.55%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.55%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.55%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                      | 2         | 1.55%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.78%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.78%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.78%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.78%   |
| Toshiba ScreenXpert- TSB8888 1080x2160 60x130mm 5.6-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.78%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.78%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.78%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.78%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.78%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.78%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.78%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.78%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.78%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.78%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 1         | 0.78%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.78%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.78%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 0.78%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch           | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 51.64%  |
| 1366x768 (WXGA)    | 15        | 12.3%   |
| 3840x2160 (4K)     | 9         | 7.38%   |
| 2560x1440 (QHD)    | 7         | 5.74%   |
| 1600x900 (HD+)     | 5         | 4.1%    |
| 1920x1200 (WUXGA)  | 3         | 2.46%   |
| 1280x1024 (SXGA)   | 3         | 2.46%   |
| 2560x1600          | 2         | 1.64%   |
| 2560x1080          | 2         | 1.64%   |
| 1680x1050 (WSXGA+) | 2         | 1.64%   |
| 1280x800 (WXGA)    | 2         | 1.64%   |
| 3200x1800 (QHD+)   | 1         | 0.82%   |
| 2880x1800          | 1         | 0.82%   |
| 2048x1152          | 1         | 0.82%   |
| 1920x540           | 1         | 0.82%   |
| 1440x900 (WXGA+)   | 1         | 0.82%   |
| 1080x2160          | 1         | 0.82%   |
| 1024x768 (XGA)     | 1         | 0.82%   |
| 1024x600           | 1         | 0.82%   |
| Unknown            | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 22.83%  |
| 13      | 27        | 21.26%  |
| 24      | 13        | 10.24%  |
| 27      | 11        | 8.66%   |
| Unknown | 11        | 8.66%   |
| 21      | 6         | 4.72%   |
| 12      | 5         | 3.94%   |
| 23      | 4         | 3.15%   |
| 31      | 3         | 2.36%   |
| 29      | 2         | 1.57%   |
| 20      | 2         | 1.57%   |
| 19      | 2         | 1.57%   |
| 17      | 2         | 1.57%   |
| 64      | 1         | 0.79%   |
| 57      | 1         | 0.79%   |
| 54      | 1         | 0.79%   |
| 42      | 1         | 0.79%   |
| 22      | 1         | 0.79%   |
| 18      | 1         | 0.79%   |
| 14      | 1         | 0.79%   |
| 11      | 1         | 0.79%   |
| 10      | 1         | 0.79%   |
| 5       | 1         | 0.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 38.1%   |
| 501-600     | 26        | 20.63%  |
| 201-300     | 15        | 11.9%   |
| Unknown     | 11        | 8.73%   |
| 401-500     | 9         | 7.14%   |
| 601-700     | 7         | 5.56%   |
| 351-400     | 5         | 3.97%   |
| 1001-1500   | 3         | 2.38%   |
| 901-1000    | 1         | 0.79%   |
| 1-100       | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 88        | 76.52%  |
| 16/10   | 10        | 8.7%    |
| Unknown | 10        | 8.7%    |
| 21/9    | 2         | 1.74%   |
| 6/5     | 1         | 0.87%   |
| 5/4     | 1         | 0.87%   |
| 4/3     | 1         | 0.87%   |
| 11/10   | 1         | 0.87%   |
| 0.46    | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 18.11%  |
| 91-100         | 22        | 17.32%  |
| 81-90          | 21        | 16.54%  |
| 301-350        | 13        | 10.24%  |
| Unknown        | 11        | 8.66%   |
| 101-110        | 8         | 6.3%    |
| 71-80          | 6         | 4.72%   |
| 61-70          | 5         | 3.94%   |
| 151-200        | 5         | 3.94%   |
| More than 1000 | 3         | 2.36%   |
| 351-500        | 3         | 2.36%   |
| 51-60          | 1         | 0.79%   |
| 41-50          | 1         | 0.79%   |
| 1-40           | 1         | 0.79%   |
| 251-300        | 1         | 0.79%   |
| 131-140        | 1         | 0.79%   |
| 121-130        | 1         | 0.79%   |
| 501-1000       | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 39        | 31.45%  |
| 121-160       | 35        | 28.23%  |
| 101-120       | 22        | 17.74%  |
| 161-240       | 11        | 8.87%   |
| Unknown       | 11        | 8.87%   |
| More than 240 | 5         | 4.03%   |
| 1-50          | 1         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 54.49%  |
| 0     | 65        | 36.52%  |
| 2     | 15        | 8.43%   |
| 3     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 102       | 40.48%  |
| Realtek Semiconductor    | 82        | 32.54%  |
| Qualcomm Atheros         | 27        | 10.71%  |
| Broadcom                 | 13        | 5.16%   |
| Xiaomi                   | 3         | 1.19%   |
| Ralink Technology        | 3         | 1.19%   |
| Marvell Technology Group | 3         | 1.19%   |
| TP-Link                  | 2         | 0.79%   |
| Samsung Electronics      | 2         | 0.79%   |
| MediaTek                 | 2         | 0.79%   |
| Google                   | 2         | 0.79%   |
| Sagem                    | 1         | 0.4%    |
| Ralink                   | 1         | 0.4%    |
| Qualcomm                 | 1         | 0.4%    |
| Nvidia                   | 1         | 0.4%    |
| MYRICOM                  | 1         | 0.4%    |
| LG Electronics           | 1         | 0.4%    |
| IMC Networks             | 1         | 0.4%    |
| Huawei Technologies      | 1         | 0.4%    |
| HMD Global               | 1         | 0.4%    |
| D-Link System            | 1         | 0.4%    |
| Arduino SA               | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 17.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.34%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.68%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.34%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.34%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 2.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.01%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.01%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1%      |
| Intel Wireless-AC 9260                                            | 3         | 1%      |
| Intel Wireless 8260                                               | 3         | 1%      |
| Intel Wireless 7265                                               | 3         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.67%   |
| Realtek Realtek Bluetooth Adapter                                 | 2         | 0.67%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.67%   |
| Intel Wireless 7260                                               | 2         | 0.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.67%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.67%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 48.44%  |
| Qualcomm Atheros      | 27        | 21.09%  |
| Realtek Semiconductor | 18        | 14.06%  |
| Broadcom              | 11        | 8.59%   |
| Ralink Technology     | 3         | 2.34%   |
| TP-Link               | 2         | 1.56%   |
| MediaTek              | 2         | 1.56%   |
| Sagem                 | 1         | 0.78%   |
| Ralink                | 1         | 0.78%   |
| IMC Networks          | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 6.25%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 5.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 4.69%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.34%   |
| Intel Wireless-AC 9260                                         | 3         | 2.34%   |
| Intel Wireless 8260                                            | 3         | 2.34%   |
| Intel Wireless 7265                                            | 3         | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.56%   |
| Realtek Realtek Bluetooth Adapter                              | 2         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.56%   |
| Intel Wireless 7260                                            | 2         | 1.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.56%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.56%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.78%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.78%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.78%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC           | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 45.86%  |
| Intel                    | 65        | 41.4%   |
| Broadcom                 | 4         | 2.55%   |
| Xiaomi                   | 3         | 1.91%   |
| Marvell Technology Group | 3         | 1.91%   |
| Samsung Electronics      | 2         | 1.27%   |
| Google                   | 2         | 1.27%   |
| Qualcomm Atheros         | 1         | 0.64%   |
| Qualcomm                 | 1         | 0.64%   |
| Nvidia                   | 1         | 0.64%   |
| MYRICOM                  | 1         | 0.64%   |
| HMD Global               | 1         | 0.64%   |
| D-Link System            | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 31.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.95%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.17%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 4.17%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.57%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.79%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.19%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.19%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.19%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.19%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.19%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.19%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.19%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 1.19%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.6%    |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.6%    |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.6%    |
| Intel Ethernet Controller X550                                    | 1         | 0.6%    |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 142       | 54.62%  |
| WiFi     | 115       | 44.23%  |
| Modem    | 3         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 107       | 66.05%  |
| WiFi     | 55        | 33.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 85        | 47.75%  |
| 1     | 69        | 38.76%  |
| 3     | 9         | 5.06%   |
| 0     | 9         | 5.06%   |
| 5     | 2         | 1.12%   |
| 4     | 2         | 1.12%   |
| 7     | 1         | 0.56%   |
| 6     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 84.92%  |
| Yes  | 27        | 15.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 56.47%  |
| Qualcomm Atheros Communications | 9         | 10.59%  |
| Realtek Semiconductor           | 5         | 5.88%   |
| IMC Networks                    | 5         | 5.88%   |
| Dell                            | 4         | 4.71%   |
| Foxconn / Hon Hai               | 3         | 3.53%   |
| Lite-On Technology              | 2         | 2.35%   |
| Cambridge Silicon Radio         | 2         | 2.35%   |
| Broadcom                        | 2         | 2.35%   |
| ASUSTek Computer                | 2         | 2.35%   |
| Apple                           | 2         | 2.35%   |
| Ralink                          | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 15.29%  |
| Intel AX201 Bluetooth                                       | 12        | 14.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 11        | 12.94%  |
| Intel AX200 Bluetooth                                       | 6         | 7.06%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.53%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.35%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 2         | 2.35%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.35%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.35%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.35%   |
| Apple Bluetooth Host Controller                             | 2         | 2.35%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.18%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.18%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.18%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.18%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.18%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.18%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.18%   |
| Lite-On Wireless_Device                                     | 1         | 1.18%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.18%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.18%   |
| Intel AX210 Bluetooth                                       | 1         | 1.18%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.18%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.18%   |
| IMC Networks Bluetooth Radio                                | 1         | 1.18%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.18%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.18%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.18%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1         | 1.18%   |
| ASUS Bluetooth USB module                                   | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 122       | 59.8%   |
| AMD                         | 36        | 17.65%  |
| Nvidia                      | 29        | 14.22%  |
| Plantronics                 | 2         | 0.98%   |
| GN Netcom                   | 2         | 0.98%   |
| FiiO Electronics Technology | 2         | 0.98%   |
| XMOS                        | 1         | 0.49%   |
| SteelSeries ApS             | 1         | 0.49%   |
| Sony                        | 1         | 0.49%   |
| Realtek Semiconductor       | 1         | 0.49%   |
| Razer USA                   | 1         | 0.49%   |
| Micro Star International    | 1         | 0.49%   |
| Lenovo                      | 1         | 0.49%   |
| Kingston Technology         | 1         | 0.49%   |
| Ensoniq                     | 1         | 0.49%   |
| Creative Labs               | 1         | 0.49%   |
| Cambridge Silicon Radio     | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 6.15%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.46%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.64%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.23%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.23%   |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.82%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 45        | 22.73%  |
| Samsung Electronics          | 41        | 20.71%  |
| Micron Technology            | 20        | 10.1%   |
| Crucial                      | 17        | 8.59%   |
| Kingston                     | 15        | 7.58%   |
| Corsair                      | 13        | 6.57%   |
| G.Skill                      | 8         | 4.04%   |
| Unknown                      | 7         | 3.54%   |
| Unknown                      | 6         | 3.03%   |
| Unknown (ABCD)               | 3         | 1.52%   |
| Ramaxel Technology           | 3         | 1.52%   |
| Elpida                       | 3         | 1.52%   |
| A-DATA Technology            | 3         | 1.52%   |
| Transcend                    | 2         | 1.01%   |
| KomputerBay                  | 2         | 1.01%   |
| Qimonda                      | 1         | 0.51%   |
| PNY                          | 1         | 0.51%   |
| Patriot Memory (PDP Systems) | 1         | 0.51%   |
| Patriot                      | 1         | 0.51%   |
| Nanya Technology             | 1         | 0.51%   |
| Kingmax Semiconductor        | 1         | 0.51%   |
| Kingmax                      | 1         | 0.51%   |
| Hewlett-Packard              | 1         | 0.51%   |
| Apacer                       | 1         | 0.51%   |
| AMD                          | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 6         | 2.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 3         | 1.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 2         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s  | 2         | 0.94%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s             | 2         | 0.94%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s            | 2         | 0.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.94%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 2         | 0.94%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 2         | 0.94%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s              | 2         | 0.94%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s         | 2         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                           | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM                                       | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 1         | 0.47%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1         | 0.47%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s               | 1         | 0.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s             | 1         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s            | 1         | 0.47%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s              | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 82        | 47.4%   |
| DDR3    | 69        | 39.88%  |
| DDR2    | 8         | 4.62%   |
| LPDDR4  | 5         | 2.89%   |
| Unknown | 4         | 2.31%   |
| LPDDR3  | 3         | 1.73%   |
| LPDDR5  | 1         | 0.58%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 57.56%  |
| DIMM         | 64        | 37.21%  |
| Row Of Chips | 8         | 4.65%   |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 38.5%   |
| 4096  | 56        | 29.95%  |
| 16384 | 25        | 13.37%  |
| 2048  | 21        | 11.23%  |
| 32768 | 10        | 5.35%   |
| 1024  | 3         | 1.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 40        | 22.1%   |
| 3200    | 33        | 18.23%  |
| 2400    | 20        | 11.05%  |
| 2133    | 18        | 9.94%   |
| 2667    | 16        | 8.84%   |
| 1333    | 16        | 8.84%   |
| 1334    | 8         | 4.42%   |
| 800     | 4         | 2.21%   |
| 2666    | 3         | 1.66%   |
| 1067    | 3         | 1.66%   |
| 667     | 3         | 1.66%   |
| 3600    | 2         | 1.1%    |
| 1066    | 2         | 1.1%    |
| 975     | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 6400    | 1         | 0.55%   |
| 4267    | 1         | 0.55%   |
| 4266    | 1         | 0.55%   |
| 3400    | 1         | 0.55%   |
| 3000    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 1866    | 1         | 0.55%   |
| 933     | 1         | 0.55%   |
| 533     | 1         | 0.55%   |

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
| Chicony Electronics           | 17        | 23.94%  |
| IMC Networks                  | 11        | 15.49%  |
| Sunplus Innovation Technology | 8         | 11.27%  |
| Microdia                      | 8         | 11.27%  |
| Acer                          | 6         | 8.45%   |
| Realtek Semiconductor         | 4         | 5.63%   |
| Syntek                        | 2         | 2.82%   |
| Logitech                      | 2         | 2.82%   |
| Z-Star Microelectronics       | 1         | 1.41%   |
| Sonix Technology              | 1         | 1.41%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.41%   |
| Ricoh                         | 1         | 1.41%   |
| Quanta                        | 1         | 1.41%   |
| OmniVision Technologies       | 1         | 1.41%   |
| Luxvisions Innotech Limited   | 1         | 1.41%   |
| Lite-On Technology            | 1         | 1.41%   |
| Intel                         | 1         | 1.41%   |
| Genesys Logic                 | 1         | 1.41%   |
| DigiTech                      | 1         | 1.41%   |
| ARC International             | 1         | 1.41%   |
| Alcor Micro                   | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 5         | 6.94%   |
| Acer Integrated Camera                         | 5         | 6.94%   |
| Microdia Integrated_Webcam_HD                  | 4         | 5.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 3         | 4.17%   |
| Realtek Integrated_Webcam_HD                   | 3         | 4.17%   |
| IMC Networks EasyCamera                        | 3         | 4.17%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 2.78%   |
| Microdia Integrated Webcam                     | 2         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                  | 2         | 2.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)       | 2         | 2.78%   |
| Chicony HP HD Camera                           | 2         | 2.78%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1         | 1.39%   |
| Syntek Integrated Camera                       | 1         | 1.39%   |
| Syntek EasyCamera                              | 1         | 1.39%   |
| Sunplus Laptop Integrated Webcam HD            | 1         | 1.39%   |
| Sunplus HP HD Webcam [Fixed]                   | 1         | 1.39%   |
| Sunplus HD WebCam                              | 1         | 1.39%   |
| Sonix USB2.0 HD UVC WebCam                     | 1         | 1.39%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1         | 1.39%   |
| Ricoh Integrated Webcam                        | 1         | 1.39%   |
| Realtek Integrated Webcam HD                   | 1         | 1.39%   |
| Quanta VGA WebCam                              | 1         | 1.39%   |
| OmniVision Monitor Webcam                      | 1         | 1.39%   |
| Microdia Laptop_Integrated_Webcam_HD           | 1         | 1.39%   |
| Microdia JOYACCESS JA-Webcam                   | 1         | 1.39%   |
| Luxvisions Innotech Limited Integrated Camera  | 1         | 1.39%   |
| Logitech Webcam C270                           | 1         | 1.39%   |
| Logitech HD Pro Webcam C920                    | 1         | 1.39%   |
| Lite-On HP Wide Vision HD Camera               | 1         | 1.39%   |
| Intel RealSense 3D Camera (Front F200)         | 1         | 1.39%   |
| IMC Networks USB2.0 HD IR UVC WebCam           | 1         | 1.39%   |
| IMC Networks Integrated Webcam                 | 1         | 1.39%   |
| IMC Networks HP TrueVision HD Camera           | 1         | 1.39%   |
| IMC Networks HD Camera                         | 1         | 1.39%   |
| Genesys Logic Camera                           | 1         | 1.39%   |
| DigiTech WebCam SCB-0350M                      | 1         | 1.39%   |
| Chicony USB2.0 HD UVC WebCam                   | 1         | 1.39%   |
| Chicony USB 2.0 Camera                         | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 54.55%  |
| Validity Sensors           | 3         | 27.27%  |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| DigitalPersona             | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 18.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                           | 1         | 9.09%   |
| Synaptics product 0x00be                                  | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 9.09%   |
| DigitalPersona Fingerprint Reader                         | 1         | 9.09%   |
| Unknown                                                   | 1         | 9.09%   |

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
| 1     | 69        | 38.55%  |
| 2     | 45        | 25.14%  |
| 0     | 34        | 18.99%  |
| 3     | 24        | 13.41%  |
| 4     | 5         | 2.79%   |
| 6     | 1         | 0.56%   |
| 5     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 121       | 52.16%  |
| Bluetooth                | 42        | 18.1%   |
| Net/wireless             | 24        | 10.34%  |
| Card reader              | 14        | 6.03%   |
| Firewire controller      | 13        | 5.6%    |
| Fingerprint reader       | 10        | 4.31%   |
| Net/ethernet             | 4         | 1.72%   |
| Storage                  | 2         | 0.86%   |
| Sound                    | 1         | 0.43%   |
| Network                  | 1         | 0.43%   |

