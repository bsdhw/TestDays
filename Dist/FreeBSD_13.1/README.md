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

Total: 206

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 161       | 95.83%  |
| arm64 | 4         | 2.38%   |
| arm   | 2         | 1.19%   |
| i386  | 1         | 0.6%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Console    | 53        | 31.55%  |
| KDE5       | 31        | 18.45%  |
| XFCE       | 26        | 15.48%  |
| GNOME      | 15        | 8.93%   |
| TWM        | 12        | 7.14%   |
| Openbox    | 6         | 3.57%   |
| MATE       | 6         | 3.57%   |
| i3         | 5         | 2.98%   |
| LXDE       | 3         | 1.79%   |
| Cinnamon   | 3         | 1.79%   |
| LXQt       | 2         | 1.19%   |
| xfwm       | 1         | 0.6%    |
| X-Cinnamon | 1         | 0.6%    |
| plasma     | 1         | 0.6%    |
| IceWM      | 1         | 0.6%    |
| dwm        | 1         | 0.6%    |
| Compton    | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 63.69%  |
| Console | 56        | 33.33%  |
| Wayland | 5         | 2.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 91        | 54.17%  |
| SDDM    | 32        | 19.05%  |
| SLiM    | 17        | 10.12%  |
| XDM     | 9         | 5.36%   |
| LightDM | 9         | 5.36%   |
| GDM     | 9         | 5.36%   |
| PCDM    | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 118       | 69.82%  |
| en_US           | 21        | 12.43%  |
| ru_RU           | 10        | 5.92%   |
| Unknown         | 7         | 4.14%   |
| zh_CN           | 4         | 2.37%   |
| fr_FR           | 4         | 2.37%   |
| ja_JP           | 1         | 0.59%   |
| en_US.ISO8859-1 | 1         | 0.59%   |
| en_GB           | 1         | 0.59%   |
| en_AU           | 1         | 0.59%   |
| de_DE           | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 124       | 73.37%  |
| BIOS | 45        | 26.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 116       | 68.64%  |
| Ufs  | 53        | 31.36%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 154       | 91.67%  |
| MBR     | 12        | 7.14%   |
| BSD     | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 32        | 19.05%  |
| Lenovo                  | 27        | 16.07%  |
| ASUSTek Computer        | 22        | 13.1%   |
| Hewlett-Packard         | 12        | 7.14%   |
| Intel                   | 10        | 5.95%   |
| Gigabyte Technology     | 9         | 5.36%   |
| Unknown                 | 7         | 4.17%   |
| MSI                     | 6         | 3.57%   |
| ASRock                  | 6         | 3.57%   |
| Acer                    | 6         | 3.57%   |
| Fujitsu                 | 3         | 1.79%   |
| TUXEDO                  | 2         | 1.19%   |
| Toshiba                 | 2         | 1.19%   |
| System76                | 2         | 1.19%   |
| Supermicro              | 2         | 1.19%   |
| Samsung Electronics     | 2         | 1.19%   |
| Google                  | 2         | 1.19%   |
| Apple                   | 2         | 1.19%   |
| Sony                    | 1         | 0.6%    |
| Raspberry Pi Foundation | 1         | 0.6%    |
| PC Engines              | 1         | 0.6%    |
| Notebook                | 1         | 0.6%    |
| NITRINOnet              | 1         | 0.6%    |
| NF-M2S                  | 1         | 0.6%    |
| MouseComputer           | 1         | 0.6%    |
| LG Electronics          | 1         | 0.6%    |
| GVC                     | 1         | 0.6%    |
| GPD                     | 1         | 0.6%    |
| Fujitsu Siemens         | 1         | 0.6%    |
| BESSTAR Tech            | 1         | 0.6%    |
| ASRockRack              | 1         | 0.6%    |
| AMI                     | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 4.17%   |
| ASUS All Series                             | 3         | 1.79%   |
| MSI MS-7817                                 | 2         | 1.19%   |
| HP EliteBook 850 G7 Notebook PC             | 2         | 1.19%   |
| Google Peppy                                | 2         | 1.19%   |
| Dell Precision M4500                        | 2         | 1.19%   |
| TUXEDO InfinityBook13V3                     | 1         | 0.6%    |
| TUXEDO Aura 15 Gen1                         | 1         | 0.6%    |
| Toshiba Satellite L305D                     | 1         | 0.6%    |
| Toshiba Satellite A300                      | 1         | 0.6%    |
| System76 Gazelle                            | 1         | 0.6%    |
| System76 Galago Pro                         | 1         | 0.6%    |
| Supermicro MBD-X8DT6-A-IS018                | 1         | 0.6%    |
| Supermicro Icebreaker 4824                  | 1         | 0.6%    |
| Sony VGN-NS21M_S                            | 1         | 0.6%    |
| Samsung R530/R730/R540                      | 1         | 0.6%    |
| Samsung 750TDA                              | 1         | 0.6%    |
| RPi Raspberry Pi                            | 1         | 0.6%    |
| PC Engines APU3                             | 1         | 0.6%    |
| Notebook N7x0WU                             | 1         | 0.6%    |
| NITRINOnet M360RUS56                        | 1         | 0.6%    |
| NF-M2S ABIT                                 | 1         | 0.6%    |
| MSI MS-B120                                 | 1         | 0.6%    |
| MSI MS-7D09                                 | 1         | 0.6%    |
| MSI MS-7D08                                 | 1         | 0.6%    |
| MSI GF63 Thin 9SC                           | 1         | 0.6%    |
| MouseComputer B360M                         | 1         | 0.6%    |
| LG 17Z990-R.AAC9U1                          | 1         | 0.6%    |
| Lenovo XiaoXinPro-13API 2019 81XD           | 1         | 0.6%    |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]-     | 1         | 0.6%    |
| Lenovo ThinkPad X270 20HMCTO1WW             | 1         | 0.6%    |
| Lenovo ThinkPad X260 20F6S0KA00             | 1         | 0.6%    |
| Lenovo ThinkPad X250 20CMS0FA00             | 1         | 0.6%    |
| Lenovo ThinkPad X220 4286CTO                | 1         | 0.6%    |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT        | 1         | 0.6%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TKS0QB00 | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon Gen 10 21CBCTO1WW | 1         | 0.6%    |
| Lenovo ThinkPad W520 4282AD4                | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L6SB2N00             | 1         | 0.6%    |
| Lenovo ThinkPad T480 20L6S29E0T             | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 16        | 9.52%   |
| Dell Latitude                | 9         | 5.36%   |
| Unknown                      | 7         | 4.17%   |
| Dell Precision               | 6         | 3.57%   |
| Dell OptiPlex                | 6         | 3.57%   |
| Dell Inspiron                | 6         | 3.57%   |
| Lenovo IdeaPad               | 4         | 2.38%   |
| ASUS ZenBook                 | 4         | 2.38%   |
| ASUS VivoBook                | 3         | 1.79%   |
| ASUS ROG                     | 3         | 1.79%   |
| ASUS PRIME                   | 3         | 1.79%   |
| ASUS All                     | 3         | 1.79%   |
| Acer Aspire                  | 3         | 1.79%   |
| Toshiba Satellite            | 2         | 1.19%   |
| MSI MS-7817                  | 2         | 1.19%   |
| Lenovo ThinkCentre           | 2         | 1.19%   |
| HP EliteDesk                 | 2         | 1.19%   |
| HP EliteBook                 | 2         | 1.19%   |
| Google Peppy                 | 2         | 1.19%   |
| Dell G5                      | 2         | 1.19%   |
| TUXEDO InfinityBook13V3      | 1         | 0.6%    |
| TUXEDO Aura                  | 1         | 0.6%    |
| System76 Gazelle             | 1         | 0.6%    |
| System76 Galago              | 1         | 0.6%    |
| Supermicro MBD-X8DT6-A-IS018 | 1         | 0.6%    |
| Supermicro Icebreaker        | 1         | 0.6%    |
| Sony VGN-NS21M               | 1         | 0.6%    |
| Samsung R530                 | 1         | 0.6%    |
| Samsung 750TDA               | 1         | 0.6%    |
| RPi Raspberry                | 1         | 0.6%    |
| PC Engines APU3              | 1         | 0.6%    |
| Notebook N7x0WU              | 1         | 0.6%    |
| NITRINOnet M360RUS56         | 1         | 0.6%    |
| NF-M2S ABIT                  | 1         | 0.6%    |
| MSI MS-B120                  | 1         | 0.6%    |
| MSI MS-7D09                  | 1         | 0.6%    |
| MSI MS-7D08                  | 1         | 0.6%    |
| MSI GF63                     | 1         | 0.6%    |
| MouseComputer B360M          | 1         | 0.6%    |
| LG 17Z990-R.AAC9U1           | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 26        | 15.48%  |
| 2020    | 23        | 13.69%  |
| 2022    | 18        | 10.71%  |
| 2019    | 15        | 8.93%   |
| 2018    | 15        | 8.93%   |
| 2014    | 11        | 6.55%   |
| 2016    | 8         | 4.76%   |
| 2013    | 8         | 4.76%   |
| 2011    | 8         | 4.76%   |
| 2015    | 6         | 3.57%   |
| 2012    | 6         | 3.57%   |
| Unknown | 6         | 3.57%   |
| 2017    | 5         | 2.98%   |
| 2010    | 5         | 2.98%   |
| 2008    | 5         | 2.98%   |
| 2009    | 3         | 1.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 82        | 48.81%  |
| Desktop        | 68        | 40.48%  |
| Mini pc        | 11        | 6.55%   |
| Server         | 3         | 1.79%   |
| Convertible    | 2         | 1.19%   |
| System on chip | 1         | 0.6%    |
| All in one     | 1         | 0.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 97.62%  |
| Yes  | 4         | 2.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 55        | 32.54%  |
| 16.01-24.0  | 47        | 27.81%  |
| 4.01-8.0    | 19        | 11.24%  |
| 32.01-64.0  | 17        | 10.06%  |
| 64.01-256.0 | 14        | 8.28%   |
| 2.01-3.0    | 6         | 3.55%   |
| 24.01-32.0  | 5         | 2.96%   |
| 0.01-0.5    | 3         | 1.78%   |
| 3.01-4.0    | 2         | 1.18%   |
| 0.51-1.0    | 1         | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 64        | 37.87%  |
| 0.51-1.0   | 51        | 30.18%  |
| 1.01-2.0   | 32        | 18.93%  |
| 2.01-3.0   | 13        | 7.69%   |
| 0          | 4         | 2.37%   |
| 3.01-4.0   | 2         | 1.18%   |
| 4.01-8.0   | 1         | 0.59%   |
| 24.01-32.0 | 1         | 0.59%   |
| 8.01-16.0  | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 52.66%  |
| 2      | 36        | 21.3%   |
| 3      | 12        | 7.1%    |
| 0      | 11        | 6.51%   |
| 4      | 9         | 5.33%   |
| 8      | 3         | 1.78%   |
| 10     | 2         | 1.18%   |
| 6      | 2         | 1.18%   |
| 18     | 1         | 0.59%   |
| 16     | 1         | 0.59%   |
| 15     | 1         | 0.59%   |
| 11     | 1         | 0.59%   |
| 5      | 1         | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 72.62%  |
| Yes       | 46        | 27.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 79.17%  |
| No        | 35        | 20.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 64.29%  |
| No        | 60        | 35.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 54.17%  |
| Yes       | 77        | 45.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 41        | 24.26%  |
| Russia      | 18        | 10.65%  |
| Germany     | 14        | 8.28%   |
| France      | 12        | 7.1%    |
| Spain       | 6         | 3.55%   |
| China       | 6         | 3.55%   |
| Canada      | 6         | 3.55%   |
| Austria     | 5         | 2.96%   |
| UK          | 4         | 2.37%   |
| Netherlands | 4         | 2.37%   |
| Japan       | 4         | 2.37%   |
| India       | 4         | 2.37%   |
| Czechia     | 4         | 2.37%   |
| Australia   | 4         | 2.37%   |
| Thailand    | 3         | 1.78%   |
| Italy       | 3         | 1.78%   |
| Venezuela   | 2         | 1.18%   |
| Turkey      | 2         | 1.18%   |
| Philippines | 2         | 1.18%   |
| New Zealand | 2         | 1.18%   |
| Hong Kong   | 2         | 1.18%   |
| Uruguay     | 1         | 0.59%   |
| Taiwan      | 1         | 0.59%   |
| South Korea | 1         | 0.59%   |
| Slovenia    | 1         | 0.59%   |
| Norway      | 1         | 0.59%   |
| Malaysia    | 1         | 0.59%   |
| Lithuania   | 1         | 0.59%   |
| Latvia      | 1         | 0.59%   |
| Kenya       | 1         | 0.59%   |
| Israel      | 1         | 0.59%   |
| Ireland     | 1         | 0.59%   |
| Hungary     | 1         | 0.59%   |
| Guadeloupe  | 1         | 0.59%   |
| Greece      | 1         | 0.59%   |
| Finland     | 1         | 0.59%   |
| Croatia     | 1         | 0.59%   |
| Bulgaria    | 1         | 0.59%   |
| Brazil      | 1         | 0.59%   |
| Belgium     | 1         | 0.59%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 8         | 4.71%   |
| Vienna            | 4         | 2.35%   |
| Paris             | 4         | 2.35%   |
| Ozersk            | 4         | 2.35%   |
| Frisco            | 4         | 2.35%   |
| Brno              | 4         | 2.35%   |
| Tamm              | 3         | 1.76%   |
| Omaha             | 3         | 1.76%   |
| Madrid            | 3         | 1.76%   |
| Wellington        | 2         | 1.18%   |
| St Petersburg     | 2         | 1.18%   |
| Redmond           | 2         | 1.18%   |
| Nashville         | 2         | 1.18%   |
| Maracaibo         | 2         | 1.18%   |
| Charlotte         | 2         | 1.18%   |
| Central           | 2         | 1.18%   |
| Carry-le-Rouet    | 2         | 1.18%   |
| Zhumadian         | 1         | 0.59%   |
| Zagreb            | 1         | 0.59%   |
| Yashio            | 1         | 0.59%   |
| Yangcheon-gu      | 1         | 0.59%   |
| Xiamen            | 1         | 0.59%   |
| Xi'an             | 1         | 0.59%   |
| Woerdense Verlaat | 1         | 0.59%   |
| Wheatland         | 1         | 0.59%   |
| Wenatchee         | 1         | 0.59%   |
| Waldbrunn         | 1         | 0.59%   |
| Vilnius           | 1         | 0.59%   |
| Vaulx-en-Velin    | 1         | 0.59%   |
| Vancouver         | 1         | 0.59%   |
| Valladolid        | 1         | 0.59%   |
| Turku             | 1         | 0.59%   |
| Trivandrum        | 1         | 0.59%   |
| Toronto           | 1         | 0.59%   |
| Tiel              | 1         | 0.59%   |
| Thousand Oaks     | 1         | 0.59%   |
| Thessaloniki      | 1         | 0.59%   |
| Tel Aviv          | 1         | 0.59%   |
| Taito             | 1         | 0.59%   |
| Taipei            | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 59        | 103    | 25.21%  |
| Samsung Electronics | 42        | 57     | 17.95%  |
| Seagate             | 28        | 72     | 11.97%  |
| Crucial             | 16        | 22     | 6.84%   |
| Kingston            | 14        | 15     | 5.98%   |
| Toshiba             | 12        | 19     | 5.13%   |
| Intel               | 7         | 16     | 2.99%   |
| SK hynix            | 6         | 6      | 2.56%   |
| Hitachi             | 5         | 6      | 2.14%   |
| Transcend           | 4         | 4      | 1.71%   |
| A-DATA Technology   | 4         | 7      | 1.71%   |
| SanDisk             | 3         | 3      | 1.28%   |
| KIOXIA              | 3         | 3      | 1.28%   |
| Hewlett-Packard     | 3         | 3      | 1.28%   |
| Gigabyte Technology | 3         | 3      | 1.28%   |
| Silicon Motion      | 2         | 2      | 0.85%   |
| Micron Technology   | 2         | 3      | 0.85%   |
| Hikvision           | 2         | 2      | 0.85%   |
| Apple               | 2         | 2      | 0.85%   |
| Verbatim            | 1         | 1      | 0.43%   |
| UMIS                | 1         | 1      | 0.43%   |
| SPCC                | 1         | 1      | 0.43%   |
| PNY                 | 1         | 2      | 0.43%   |
| Phison              | 1         | 1      | 0.43%   |
| ORICO               | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| Lexar               | 1         | 2      | 0.43%   |
| Lenovo              | 1         | 1      | 0.43%   |
| HGST                | 1         | 1      | 0.43%   |
| EAGET               | 1         | 1      | 0.43%   |
| China               | 1         | 1      | 0.43%   |
| CFD                 | 1         | 1      | 0.43%   |
| BR                  | 1         | 1      | 0.43%   |
| BIWIN               | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.47%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.47%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 1.1%    |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.1%    |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 1.1%    |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 1.1%    |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.1%    |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.1%    |
| A-DATA SU650 240GB                      | 3         | 1.1%    |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.74%   |
| WDC WD3200BPVT-80JJ5T0 320GB            | 2         | 0.74%   |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 0.74%   |
| WDC WD30EFRX-68AX9N0 3TB                | 2         | 0.74%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.74%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.74%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 0.74%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.74%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.74%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.74%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.74%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.74%   |
| KIOXIA KBG40ZNS512G NVMe 512GB          | 2         | 0.74%   |
| Kingston SA400S37120G 120GB             | 2         | 0.74%   |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.74%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.74%   |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.74%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.37%   |
| WDC WDS500G2X0C-00L350 500GB            | 1         | 0.37%   |
| WDC WDS500G1B0A-00H9H0 500GB            | 1         | 0.37%   |
| WDC WDS480G2G0A-00JH30 480GB            | 1         | 0.37%   |
| WDC WDS250G2B0C-00PXH0 250GB            | 1         | 0.37%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.37%   |
| WDC WDS250G2B0A-00SM50 250GB            | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.37%   |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.37%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.37%   |
| WDC WDS100T2B0B-00YS70 1TB              | 1         | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1         | 0.37%   |
| WDC WDBA3V5000ANC-WRSN 500GB            | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 41        | 83     | 47.67%  |
| Seagate             | 27        | 71     | 31.4%   |
| Toshiba             | 9         | 16     | 10.47%  |
| Hitachi             | 5         | 6      | 5.81%   |
| Samsung Electronics | 1         | 4      | 1.16%   |
| HGST                | 1         | 1      | 1.16%   |
| Hewlett-Packard     | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 30     | 25%     |
| Crucial             | 13        | 14     | 14.77%  |
| WDC                 | 8         | 8      | 9.09%   |
| Kingston            | 8         | 9      | 9.09%   |
| Intel               | 5         | 14     | 5.68%   |
| A-DATA Technology   | 4         | 7      | 4.55%   |
| Transcend           | 3         | 3      | 3.41%   |
| SanDisk             | 3         | 3      | 3.41%   |
| Toshiba             | 2         | 2      | 2.27%   |
| Hikvision           | 2         | 2      | 2.27%   |
| Verbatim            | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| SK hynix            | 1         | 1      | 1.14%   |
| PNY                 | 1         | 2      | 1.14%   |
| Phison              | 1         | 1      | 1.14%   |
| ORICO               | 1         | 1      | 1.14%   |
| OCZ                 | 1         | 1      | 1.14%   |
| Micron Technology   | 1         | 2      | 1.14%   |
| LITEONIT            | 1         | 1      | 1.14%   |
| Lexar               | 1         | 2      | 1.14%   |
| Lenovo              | 1         | 1      | 1.14%   |
| Hewlett-Packard     | 1         | 1      | 1.14%   |
| Gigabyte Technology | 1         | 1      | 1.14%   |
| China               | 1         | 1      | 1.14%   |
| CFD                 | 1         | 1      | 1.14%   |
| BR                  | 1         | 1      | 1.14%   |
| BIWIN               | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 78        | 113    | 37.32%  |
| HDD  | 71        | 183    | 33.97%  |
| NVMe | 60        | 71     | 28.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 296    | 67.21%  |
| NVMe | 60        | 71     | 32.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 107    | 49.69%  |
| 0.51-1.0   | 48        | 69     | 30.19%  |
| 1.01-2.0   | 13        | 27     | 8.18%   |
| 3.01-4.0   | 6         | 10     | 3.77%   |
| 4.01-10.0  | 6         | 46     | 3.77%   |
| 2.01-3.0   | 4         | 17     | 2.52%   |
| 10.01-20.0 | 3         | 20     | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 34.32%  |
| 251-500        | 39        | 23.08%  |
| 501-1000       | 29        | 17.16%  |
| 51-100         | 14        | 8.28%   |
| 21-50          | 12        | 7.1%    |
| 1001-2000      | 7         | 4.14%   |
| 1-20           | 4         | 2.37%   |
| 2001-3000      | 3         | 1.78%   |
| More than 3000 | 2         | 1.18%   |
| Unknown        | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 133       | 78.7%   |
| 21-50          | 21        | 12.43%  |
| 101-250        | 5         | 2.96%   |
| 51-100         | 5         | 2.96%   |
| 251-500        | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |
| 501-1000       | 1         | 0.59%   |
| Unknown        | 1         | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB                 | 2         | 2      | 6.9%    |
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 3.45%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 3.45%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 3.45%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 3.45%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 3.45%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 3.45%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 3.45%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 3.45%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 3.45%   |
| Phison NETLIST SSD 8GB-001                   | 1         | 1      | 3.45%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 3.45%   |
| Kingston SVP200S37A120G 120GB                | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB                 | 1         | 1      | 3.45%   |
| Kingston SNS4151S316GD 16GB                  | 1         | 1      | 3.45%   |
| Kingston SH103S3240G 240GB                   | 1         | 1      | 3.45%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 3.45%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 3.45%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.45%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 3.45%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 9      | 22.22%  |
| Seagate             | 5         | 6      | 18.52%  |
| Kingston            | 3         | 4      | 11.11%  |
| Hitachi             | 3         | 3      | 11.11%  |
| Toshiba             | 2         | 2      | 7.41%   |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Phison              | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 2      | 3.7%    |
| HGST                | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |
| A-DATA Technology   | 1         | 2      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 9      | 33.33%  |
| Seagate         | 5         | 6      | 27.78%  |
| Hitachi         | 3         | 3      | 16.67%  |
| Toshiba         | 2         | 2      | 11.11%  |
| HGST            | 1         | 1      | 5.56%   |
| Hewlett-Packard | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 22     | 65.38%  |
| SSD  | 9         | 12     | 34.62%  |

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
| Works    | 142       | 323    | 83.04%  |
| Malfunc  | 24        | 34     | 14.04%  |
| Detected | 5         | 10     | 2.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 116       | 53.7%   |
| Samsung Electronics         | 22        | 10.19%  |
| AMD                         | 21        | 9.72%   |
| SanDisk                     | 13        | 6.02%   |
| Kingston Technology Company | 6         | 2.78%   |
| Broadcom / LSI              | 6         | 2.78%   |
| Silicon Motion              | 5         | 2.31%   |
| SK hynix                    | 4         | 1.85%   |
| Micron/Crucial Technology   | 3         | 1.39%   |
| Marvell Technology Group    | 3         | 1.39%   |
| KIOXIA                      | 3         | 1.39%   |
| ASMedia Technology          | 3         | 1.39%   |
| Phison Electronics          | 2         | 0.93%   |
| Nvidia                      | 2         | 0.93%   |
| Micron Technology           | 2         | 0.93%   |
| Union Memory (Shenzhen)     | 1         | 0.46%   |
| Toshiba                     | 1         | 0.46%   |
| Silicon Image               | 1         | 0.46%   |
| Seagate Technology          | 1         | 0.46%   |
| Unknown                     | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 6.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 4.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.42%   |
| Unknown                                                                        | 8         | 3.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 2.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.14%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 2.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.71%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.71%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 4         | 1.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 4         | 1.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.28%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3         | 1.28%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3         | 1.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.28%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.28%   |
| SK hynix Gold P31 SSD                                                          | 2         | 0.85%   |
| SK hynix BC511                                                                 | 2         | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.85%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.85%   |
| SanDisk unknown                                                                | 2         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.85%   |
| Intel SSD 660P Series                                                          | 2         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 125       | 58.41%  |
| NVMe | 60        | 28.04%  |
| RAID | 13        | 6.07%   |
| IDE  | 11        | 5.14%   |
| SAS  | 5         | 2.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 135       | 80.36%  |
| AMD    | 27        | 16.07%  |
| ARM    | 6         | 3.57%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 2.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 2.37%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.78%   |
| ARM Cortex-A53 r0p4                     | 3         | 1.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 1.78%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.18%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 1.18%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 1.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.18%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.18%   |
| Intel Core i5 CPU M 560 @ 2.67GH        | 2         | 1.18%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.18%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)      | 2         | 1.18%   |
| AMD Ryzen 3 5300U with Radeon Graphics  | 2         | 1.18%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.59%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.59%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 1         | 0.59%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.59%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.59%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.59%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.59%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.59%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz     | 1         | 0.59%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.59%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.59%   |
| Intel Pentium II                        | 1         | 0.59%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz  | 1         | 0.59%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.59%   |
| Intel Pentium CPU G3240T @ 2.70GHz      | 1         | 0.59%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.59%   |
| Intel Genuine CPU                       | 1         | 0.59%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1         | 0.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.59%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 0.59%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 43        | 25.6%   |
| Intel Core i7        | 34        | 20.24%  |
| Other                | 13        | 7.74%   |
| Intel Core i3        | 11        | 6.55%   |
| Intel Xeon           | 9         | 5.36%   |
| Intel Celeron        | 9         | 5.36%   |
| AMD Ryzen 5          | 7         | 4.17%   |
| Intel Core 2 Duo     | 5         | 2.98%   |
| AMD Ryzen 7          | 5         | 2.98%   |
| AMD Ryzen 3          | 5         | 2.98%   |
| Intel Atom           | 4         | 2.38%   |
| ARM Cortex           | 4         | 2.38%   |
| Intel Pentium        | 3         | 1.79%   |
| AMD Ryzen 9          | 2         | 1.19%   |
| AMD Ryzen 7 PRO      | 2         | 1.19%   |
| Intel Xeon Gold      | 1         | 0.6%    |
| Intel Pentium Silver | 1         | 0.6%    |
| Intel Pentium Gold   | 1         | 0.6%    |
| Intel Pentium Dual   | 1         | 0.6%    |
| Intel Genuine        | 1         | 0.6%    |
| Intel Core 2 Quad    | 1         | 0.6%    |
| AMD GX               | 1         | 0.6%    |
| AMD E2               | 1         | 0.6%    |
| AMD Athlon X2        | 1         | 0.6%    |
| AMD Athlon 64 X2     | 1         | 0.6%    |
| AMD A8               | 1         | 0.6%    |
| AMD A10              | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 61        | 36.31%  |
| 2       | 53        | 31.55%  |
| 6       | 14        | 8.33%   |
| 8       | 13        | 7.74%   |
| Unknown | 9         | 5.36%   |
| 16      | 8         | 4.76%   |
| 12      | 5         | 2.98%   |
| 24      | 2         | 1.19%   |
| 1       | 2         | 1.19%   |
| 20      | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 160       | 95.24%  |
| Unknown | 6         | 3.57%   |
| 2       | 2         | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 91        | 54.17%  |
| 1       | 67        | 39.88%  |
| Unknown | 10        | 5.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 37        | 21.89%  |
| Haswell         | 18        | 10.65%  |
| Unknown         | 14        | 8.28%   |
| SandyBridge     | 13        | 7.69%   |
| IvyBridge       | 11        | 6.51%   |
| Skylake         | 8         | 4.73%   |
| TigerLake       | 7         | 4.14%   |
| CometLake       | 7         | 4.14%   |
| Zen+            | 5         | 2.96%   |
| Zen 3           | 5         | 2.96%   |
| Zen 2           | 5         | 2.96%   |
| Westmere        | 5         | 2.96%   |
| Broadwell       | 5         | 2.96%   |
| Silvermont      | 4         | 2.37%   |
| Core            | 4         | 2.37%   |
| Zen             | 3         | 1.78%   |
| Penryn          | 3         | 1.78%   |
| Goldmont plus   | 3         | 1.78%   |
| Bonnell         | 3         | 1.78%   |
| Puma            | 2         | 1.18%   |
| Piledriver      | 1         | 0.59%   |
| P6              | 1         | 0.59%   |
| K8 Hammer       | 1         | 0.59%   |
| K8 & K10 hybrid | 1         | 0.59%   |
| IceLake         | 1         | 0.59%   |
| Goldmont        | 1         | 0.59%   |
| Excavator       | 1         | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 107       | 58.79%  |
| Nvidia                               | 39        | 21.43%  |
| AMD                                  | 29        | 15.93%  |
| Matrox Electronics Systems           | 5         | 2.75%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.55%   |
| ASPEED Technology                    | 1         | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 5.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 4.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 3.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 6         | 3.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 2.67%   |
| Intel UHD Graphics 620                                                      | 4         | 2.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.14%   |
| Intel HD Graphics 5500                                                      | 4         | 2.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 2.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.6%    |
| Intel HD Graphics 630                                                       | 3         | 1.6%    |
| Intel HD Graphics 620                                                       | 3         | 1.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.6%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.6%    |
| AMD Renoir                                                                  | 3         | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 1.6%    |
| AMD Lucienne                                                                | 3         | 1.6%    |
| AMD Cezanne                                                                 | 3         | 1.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.07%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.07%   |
| Nvidia GT216GLM [Quadro FX 880M]                                            | 2         | 1.07%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.07%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 2         | 1.07%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 1.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.07%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2         | 1.07%   |
| Intel HD Graphics 530                                                       | 2         | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.07%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2         | 1.07%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 83        | 49.4%   |
| 1 x AMD                                  | 22        | 13.1%   |
| 1 x Nvidia                               | 20        | 11.9%   |
| Intel + Nvidia                           | 16        | 9.52%   |
| Other                                    | 7         | 4.17%   |
| 2 x Intel                                | 5         | 2.98%   |
| 1 x Matrox                               | 5         | 2.98%   |
| Intel + AMD                              | 3         | 1.79%   |
| 2 x AMD                                  | 2         | 1.19%   |
| AMD + Nvidia                             | 2         | 1.19%   |
| 2 x Nvidia                               | 1         | 0.6%    |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.6%    |
| 1 x ASPEED                               | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 136       | 80.95%  |
| Proprietary | 24        | 14.29%  |
| Unknown     | 8         | 4.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 79.76%  |
| 0.51-1.0   | 10        | 5.95%   |
| 1.01-2.0   | 9         | 5.36%   |
| 0.01-0.5   | 6         | 3.57%   |
| 5.01-6.0   | 3         | 1.79%   |
| 3.01-4.0   | 3         | 1.79%   |
| 7.01-8.0   | 2         | 1.19%   |
| 2.01-3.0   | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 17        | 13.93%  |
| LG Display           | 14        | 11.48%  |
| BOE                  | 14        | 11.48%  |
| AU Optronics         | 10        | 8.2%    |
| Chimei Innolux       | 9         | 7.38%   |
| Acer                 | 6         | 4.92%   |
| Lenovo               | 5         | 4.1%    |
| Goldstar             | 4         | 3.28%   |
| Dell                 | 4         | 3.28%   |
| BenQ                 | 4         | 3.28%   |
| AOC                  | 4         | 3.28%   |
| Philips              | 3         | 2.46%   |
| ViewSonic            | 2         | 1.64%   |
| Toshiba              | 2         | 1.64%   |
| Sharp                | 2         | 1.64%   |
| Sceptre Tech         | 2         | 1.64%   |
| LGD                  | 2         | 1.64%   |
| CSO                  | 2         | 1.64%   |
| YTH                  | 1         | 0.82%   |
| Vestel Elektronik    | 1         | 0.82%   |
| USR                  | 1         | 0.82%   |
| Unknown (XXX)        | 1         | 0.82%   |
| Panasonic            | 1         | 0.82%   |
| LG Philips           | 1         | 0.82%   |
| LG Electronics       | 1         | 0.82%   |
| JDI                  | 1         | 0.82%   |
| IOD                  | 1         | 0.82%   |
| Iiyama               | 1         | 0.82%   |
| Idek Iiyama          | 1         | 0.82%   |
| HannStar             | 1         | 0.82%   |
| Compal               | 1         | 0.82%   |
| ASUSTek Computer     | 1         | 0.82%   |
| Apple                | 1         | 0.82%   |
| Ancor Communications | 1         | 0.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 1.61%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 2         | 1.61%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 1.61%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 1.61%   |
| LGD LCD Monitor 1600x900                                               | 2         | 1.61%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 1.61%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 1.61%   |
| AOC 24P1X AOC2401 1920x1200 520x320mm 24.0-inch                        | 2         | 1.61%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 0.81%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.81%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 0.81%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 0.81%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.81%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 0.81%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.81%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1         | 0.81%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 0.81%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 0.81%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 0.81%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 0.81%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 0.81%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 0.81%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 0.81%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 0.81%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch           | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 51.28%  |
| 1366x768 (WXGA)    | 14        | 11.97%  |
| 3840x2160 (4K)     | 9         | 7.69%   |
| 2560x1440 (QHD)    | 7         | 5.98%   |
| 1600x900 (HD+)     | 5         | 4.27%   |
| 1920x1200 (WUXGA)  | 3         | 2.56%   |
| 1280x1024 (SXGA)   | 3         | 2.56%   |
| 2560x1600          | 2         | 1.71%   |
| 2560x1080          | 2         | 1.71%   |
| 1680x1050 (WSXGA+) | 2         | 1.71%   |
| 1280x800 (WXGA)    | 2         | 1.71%   |
| 3200x1800 (QHD+)   | 1         | 0.85%   |
| 2880x1800          | 1         | 0.85%   |
| 2048x1152          | 1         | 0.85%   |
| 1920x540           | 1         | 0.85%   |
| 1440x900 (WXGA+)   | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |
| 1024x600           | 1         | 0.85%   |
| Unknown            | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 22.95%  |
| 13      | 25        | 20.49%  |
| 24      | 13        | 10.66%  |
| Unknown | 11        | 9.02%   |
| 27      | 10        | 8.2%    |
| 21      | 6         | 4.92%   |
| 12      | 5         | 4.1%    |
| 23      | 4         | 3.28%   |
| 31      | 3         | 2.46%   |
| 29      | 2         | 1.64%   |
| 20      | 2         | 1.64%   |
| 19      | 2         | 1.64%   |
| 17      | 2         | 1.64%   |
| 64      | 1         | 0.82%   |
| 57      | 1         | 0.82%   |
| 54      | 1         | 0.82%   |
| 42      | 1         | 0.82%   |
| 22      | 1         | 0.82%   |
| 18      | 1         | 0.82%   |
| 14      | 1         | 0.82%   |
| 11      | 1         | 0.82%   |
| 10      | 1         | 0.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 37.19%  |
| 501-600     | 25        | 20.66%  |
| 201-300     | 15        | 12.4%   |
| Unknown     | 11        | 9.09%   |
| 401-500     | 9         | 7.44%   |
| 601-700     | 7         | 5.79%   |
| 351-400     | 5         | 4.13%   |
| 1001-1500   | 3         | 2.48%   |
| 901-1000    | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 76.36%  |
| 16/10   | 10        | 9.09%   |
| Unknown | 10        | 9.09%   |
| 21/9    | 2         | 1.82%   |
| 6/5     | 1         | 0.91%   |
| 5/4     | 1         | 0.91%   |
| 4/3     | 1         | 0.91%   |
| 11/10   | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 23        | 18.85%  |
| 91-100         | 21        | 17.21%  |
| 81-90          | 19        | 15.57%  |
| 301-350        | 12        | 9.84%   |
| Unknown        | 11        | 9.02%   |
| 101-110        | 8         | 6.56%   |
| 71-80          | 6         | 4.92%   |
| 61-70          | 5         | 4.1%    |
| 151-200        | 5         | 4.1%    |
| More than 1000 | 3         | 2.46%   |
| 351-500        | 3         | 2.46%   |
| 51-60          | 1         | 0.82%   |
| 41-50          | 1         | 0.82%   |
| 251-300        | 1         | 0.82%   |
| 131-140        | 1         | 0.82%   |
| 121-130        | 1         | 0.82%   |
| 501-1000       | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 38        | 31.93%  |
| 121-160       | 33        | 27.73%  |
| 101-120       | 21        | 17.65%  |
| 161-240       | 11        | 9.24%   |
| Unknown       | 11        | 9.24%   |
| More than 240 | 4         | 3.36%   |
| 1-50          | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 55.95%  |
| 0     | 59        | 35.12%  |
| 2     | 14        | 8.33%   |
| 3     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 99        | 41.77%  |
| Realtek Semiconductor    | 76        | 32.07%  |
| Qualcomm Atheros         | 23        | 9.7%    |
| Broadcom                 | 12        | 5.06%   |
| Xiaomi                   | 3         | 1.27%   |
| Ralink Technology        | 3         | 1.27%   |
| Marvell Technology Group | 3         | 1.27%   |
| TP-Link                  | 2         | 0.84%   |
| Samsung Electronics      | 2         | 0.84%   |
| MediaTek                 | 2         | 0.84%   |
| Google                   | 2         | 0.84%   |
| Sagem                    | 1         | 0.42%   |
| Qualcomm                 | 1         | 0.42%   |
| Nvidia                   | 1         | 0.42%   |
| MYRICOM                  | 1         | 0.42%   |
| LG Electronics           | 1         | 0.42%   |
| IMC Networks             | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| HMD Global               | 1         | 0.42%   |
| D-Link System            | 1         | 0.42%   |
| Arduino SA               | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 17.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.18%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.83%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.47%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.12%   |
| Intel Ethernet Controller I225-V                                  | 6         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.06%   |
| Intel Wireless-AC 9260                                            | 3         | 1.06%   |
| Intel Wireless 8260                                               | 3         | 1.06%   |
| Intel Wireless 7265                                               | 3         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.71%   |
| Realtek Realtek Bluetooth Adapter                                 | 2         | 0.71%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.71%   |
| Intel Wireless 7260                                               | 2         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.71%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.71%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 50.41%  |
| Qualcomm Atheros      | 23        | 19.01%  |
| Realtek Semiconductor | 18        | 14.88%  |
| Broadcom              | 10        | 8.26%   |
| Ralink Technology     | 3         | 2.48%   |
| TP-Link               | 2         | 1.65%   |
| MediaTek              | 2         | 1.65%   |
| Sagem                 | 1         | 0.83%   |
| IMC Networks          | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 8         | 6.61%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 5.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 4.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.13%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 4.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2.48%   |
| Intel Wireless-AC 9260                                         | 3         | 2.48%   |
| Intel Wireless 8260                                            | 3         | 2.48%   |
| Intel Wireless 7265                                            | 3         | 2.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.65%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.65%   |
| Realtek Realtek Bluetooth Adapter                              | 2         | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.65%   |
| Intel Wireless 7260                                            | 2         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.65%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.83%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.83%   |
| Sagem XG-76NA 802.11bg                                         | 1         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.83%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.83%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC           | 1         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.83%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 44.3%   |
| Intel                    | 63        | 42.28%  |
| Broadcom                 | 4         | 2.68%   |
| Xiaomi                   | 3         | 2.01%   |
| Marvell Technology Group | 3         | 2.01%   |
| Samsung Electronics      | 2         | 1.34%   |
| Google                   | 2         | 1.34%   |
| Qualcomm Atheros         | 1         | 0.67%   |
| Qualcomm                 | 1         | 0.67%   |
| Nvidia                   | 1         | 0.67%   |
| MYRICOM                  | 1         | 0.67%   |
| HMD Global               | 1         | 0.67%   |
| D-Link System            | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 30.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 6.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5.66%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 4.4%    |
| Intel I211 Gigabit Network Connection                             | 6         | 3.77%   |
| Intel Ethernet Controller I225-V                                  | 6         | 3.77%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 3.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.26%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.26%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.26%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.26%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.26%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 1.26%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.63%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                | 1         | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.63%   |
| Intel Ethernet Controller X550                                    | 1         | 0.63%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 134       | 54.47%  |
| WiFi     | 109       | 44.31%  |
| Modem    | 3         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 100       | 65.79%  |
| WiFi     | 52        | 34.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 47.62%  |
| 1     | 66        | 39.29%  |
| 3     | 8         | 4.76%   |
| 0     | 8         | 4.76%   |
| 5     | 2         | 1.19%   |
| 4     | 2         | 1.19%   |
| 7     | 1         | 0.6%    |
| 6     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 142       | 84.02%  |
| Yes  | 27        | 15.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 60.26%  |
| Qualcomm Atheros Communications | 6         | 7.69%   |
| Realtek Semiconductor           | 5         | 6.41%   |
| IMC Networks                    | 4         | 5.13%   |
| Dell                            | 4         | 5.13%   |
| Foxconn / Hon Hai               | 3         | 3.85%   |
| Lite-On Technology              | 2         | 2.56%   |
| Cambridge Silicon Radio         | 2         | 2.56%   |
| Broadcom                        | 2         | 2.56%   |
| Apple                           | 2         | 2.56%   |
| ASUSTek Computer                | 1         | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 16.67%  |
| Intel AX201 Bluetooth                                       | 12        | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 12.82%  |
| Intel AX200 Bluetooth                                       | 6         | 7.69%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.85%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 2.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.56%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 2.56%   |
| Dell DW375 Bluetooth Module                                 | 2         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.56%   |
| Apple Bluetooth Host Controller                             | 2         | 2.56%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.28%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.28%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.28%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.28%   |
| Lite-On Wireless_Device                                     | 1         | 1.28%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.28%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.28%   |
| Intel Intel Wireless Bluetooth                              | 1         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.28%   |
| Intel AX210 Bluetooth                                       | 1         | 1.28%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.28%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.28%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.28%   |
| IMC Networks Bluetooth Radio                                | 1         | 1.28%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.28%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.28%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.28%   |
| ASUS Bluetooth USB module                                   | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 115       | 59.59%  |
| AMD                         | 32        | 16.58%  |
| Nvidia                      | 29        | 15.03%  |
| Plantronics                 | 2         | 1.04%   |
| GN Netcom                   | 2         | 1.04%   |
| FiiO Electronics Technology | 2         | 1.04%   |
| XMOS                        | 1         | 0.52%   |
| SteelSeries ApS             | 1         | 0.52%   |
| Sony                        | 1         | 0.52%   |
| Realtek Semiconductor       | 1         | 0.52%   |
| Razer USA                   | 1         | 0.52%   |
| Micro Star International    | 1         | 0.52%   |
| Lenovo                      | 1         | 0.52%   |
| Kingston Technology         | 1         | 0.52%   |
| Ensoniq                     | 1         | 0.52%   |
| Creative Labs               | 1         | 0.52%   |
| Cambridge Silicon Radio     | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 4.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.74%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 1.3%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.3%    |
| Plantronics Plantronics Blackwire 315.1                                    | 2         | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                | 2         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 43        | 22.87%  |
| Samsung Electronics          | 38        | 20.21%  |
| Micron Technology            | 18        | 9.57%   |
| Crucial                      | 17        | 9.04%   |
| Kingston                     | 15        | 7.98%   |
| Corsair                      | 13        | 6.91%   |
| G.Skill                      | 7         | 3.72%   |
| Unknown                      | 6         | 3.19%   |
| Unknown                      | 6         | 3.19%   |
| Unknown (ABCD)               | 3         | 1.6%    |
| Elpida                       | 3         | 1.6%    |
| A-DATA Technology            | 3         | 1.6%    |
| Transcend                    | 2         | 1.06%   |
| Ramaxel Technology           | 2         | 1.06%   |
| KomputerBay                  | 2         | 1.06%   |
| Qimonda                      | 1         | 0.53%   |
| PNY                          | 1         | 0.53%   |
| Patriot Memory (PDP Systems) | 1         | 0.53%   |
| Patriot                      | 1         | 0.53%   |
| Nanya Technology             | 1         | 0.53%   |
| Kingmax Semiconductor        | 1         | 0.53%   |
| Kingmax                      | 1         | 0.53%   |
| Hewlett-Packard              | 1         | 0.53%   |
| Apacer                       | 1         | 0.53%   |
| AMD                          | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 6         | 2.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 1.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 3         | 1.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 2         | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s  | 2         | 0.99%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.99%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s             | 2         | 0.99%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s            | 2         | 0.99%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 2         | 0.99%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 0.99%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 2         | 0.99%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 2         | 0.99%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s            | 2         | 0.99%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 2         | 0.99%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s              | 2         | 0.99%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s         | 2         | 0.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                           | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1         | 0.49%   |
| Unknown RAM Module 2GB DIMM                                       | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1         | 0.49%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s               | 1         | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s             | 1         | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT125R7BFR8C-H9 2GB DIMM 1067MT/s                   | 1         | 0.49%   |
| SK hynix RAM HMT125R7AFP8C-H9 2GB DIMM 1067MT/s                   | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 80        | 48.78%  |
| DDR3    | 63        | 38.41%  |
| DDR2    | 8         | 4.88%   |
| LPDDR4  | 5         | 3.05%   |
| Unknown | 4         | 2.44%   |
| LPDDR3  | 2         | 1.22%   |
| LPDDR5  | 1         | 0.61%   |
| DDR     | 1         | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 58.28%  |
| DIMM         | 60        | 36.81%  |
| Row Of Chips | 7         | 4.29%   |
| Chip         | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 71        | 40.11%  |
| 4096  | 50        | 28.25%  |
| 16384 | 23        | 12.99%  |
| 2048  | 20        | 11.3%   |
| 32768 | 10        | 5.65%   |
| 1024  | 3         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 36        | 20.93%  |
| 3200    | 33        | 19.19%  |
| 2400    | 20        | 11.63%  |
| 2667    | 16        | 9.3%    |
| 2133    | 15        | 8.72%   |
| 1333    | 14        | 8.14%   |
| 1334    | 8         | 4.65%   |
| 800     | 4         | 2.33%   |
| 2666    | 3         | 1.74%   |
| 1067    | 3         | 1.74%   |
| 667     | 3         | 1.74%   |
| 3600    | 2         | 1.16%   |
| 1066    | 2         | 1.16%   |
| 975     | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| 6400    | 1         | 0.58%   |
| 4267    | 1         | 0.58%   |
| 4266    | 1         | 0.58%   |
| 3400    | 1         | 0.58%   |
| 3000    | 1         | 0.58%   |
| 2933    | 1         | 0.58%   |
| 1866    | 1         | 0.58%   |
| 933     | 1         | 0.58%   |
| 533     | 1         | 0.58%   |

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
| Chicony Electronics           | 17        | 25.37%  |
| IMC Networks                  | 10        | 14.93%  |
| Microdia                      | 8         | 11.94%  |
| Sunplus Innovation Technology | 6         | 8.96%   |
| Acer                          | 6         | 8.96%   |
| Realtek Semiconductor         | 4         | 5.97%   |
| Logitech                      | 2         | 2.99%   |
| Z-Star Microelectronics       | 1         | 1.49%   |
| Syntek                        | 1         | 1.49%   |
| Sonix Technology              | 1         | 1.49%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.49%   |
| Ricoh                         | 1         | 1.49%   |
| Quanta                        | 1         | 1.49%   |
| OmniVision Technologies       | 1         | 1.49%   |
| Luxvisions Innotech Limited   | 1         | 1.49%   |
| Lite-On Technology            | 1         | 1.49%   |
| Intel                         | 1         | 1.49%   |
| Genesys Logic                 | 1         | 1.49%   |
| DigiTech                      | 1         | 1.49%   |
| ARC International             | 1         | 1.49%   |
| Alcor Micro                   | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 5         | 7.35%   |
| Acer Integrated Camera                         | 5         | 7.35%   |
| Microdia Integrated_Webcam_HD                  | 4         | 5.88%   |
| Realtek Integrated_Webcam_HD                   | 3         | 4.41%   |
| IMC Networks EasyCamera                        | 3         | 4.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 2         | 2.94%   |
| Sunplus Integrated_Webcam_HD                   | 2         | 2.94%   |
| Microdia Integrated Webcam                     | 2         | 2.94%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 2.94%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.94%   |
| Chicony USB2.0 VGA UVC WebCam                  | 2         | 2.94%   |
| Chicony Lenovo Integrated Camera (0.3MP)       | 2         | 2.94%   |
| Chicony HP HD Camera                           | 2         | 2.94%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1         | 1.47%   |
| Syntek Integrated Camera                       | 1         | 1.47%   |
| Sunplus Laptop Integrated Webcam HD            | 1         | 1.47%   |
| Sunplus HD WebCam                              | 1         | 1.47%   |
| Sonix USB2.0 HD UVC WebCam                     | 1         | 1.47%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1         | 1.47%   |
| Ricoh Integrated Webcam                        | 1         | 1.47%   |
| Realtek Integrated Webcam HD                   | 1         | 1.47%   |
| Quanta VGA WebCam                              | 1         | 1.47%   |
| OmniVision Monitor Webcam                      | 1         | 1.47%   |
| Microdia Laptop_Integrated_Webcam_HD           | 1         | 1.47%   |
| Microdia JOYACCESS JA-Webcam                   | 1         | 1.47%   |
| Luxvisions Innotech Limited Integrated Camera  | 1         | 1.47%   |
| Logitech Webcam C270                           | 1         | 1.47%   |
| Logitech HD Pro Webcam C920                    | 1         | 1.47%   |
| Lite-On HP Wide Vision HD Camera               | 1         | 1.47%   |
| Intel RealSense 3D Camera (Front F200)         | 1         | 1.47%   |
| IMC Networks Integrated Webcam                 | 1         | 1.47%   |
| IMC Networks HP TrueVision HD Camera           | 1         | 1.47%   |
| IMC Networks HD Camera                         | 1         | 1.47%   |
| Genesys Logic Camera                           | 1         | 1.47%   |
| DigiTech WebCam SCB-0350M                      | 1         | 1.47%   |
| Chicony USB2.0 HD UVC WebCam                   | 1         | 1.47%   |
| Chicony USB 2.0 Camera                         | 1         | 1.47%   |
| Chicony LG Camera                              | 1         | 1.47%   |
| Chicony HD WebCam                              | 1         | 1.47%   |
| Chicony Chicony USB2.0 Camera                  | 1         | 1.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 66.67%  |
| Validity Sensors           | 2         | 22.22%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 22.22%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 2         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                           | 1         | 11.11%  |
| Synaptics product 0x00be                                  | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 11.11%  |
| Unknown                                                   | 1         | 11.11%  |

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
| 1     | 67        | 39.64%  |
| 2     | 44        | 26.04%  |
| 0     | 31        | 18.34%  |
| 3     | 21        | 12.43%  |
| 4     | 5         | 2.96%   |
| 5     | 1         | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 115       | 53.49%  |
| Bluetooth                | 38        | 17.67%  |
| Net/wireless             | 21        | 9.77%   |
| Firewire controller      | 13        | 6.05%   |
| Card reader              | 12        | 5.58%   |
| Fingerprint reader       | 8         | 3.72%   |
| Net/ethernet             | 4         | 1.86%   |
| Storage                  | 2         | 0.93%   |
| Sound                    | 1         | 0.47%   |
| Network                  | 1         | 0.47%   |

