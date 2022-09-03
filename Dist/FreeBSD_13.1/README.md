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

Total: 209

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| MSI           | H81M-P33                    | Desktop     | [099e1c8b15](https://bsd-hardware.info/?probe=099e1c8b15) | Aug 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b96612a45b](https://bsd-hardware.info/?probe=b96612a45b) | Aug 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [29b392331d](https://bsd-hardware.info/?probe=29b392331d) | Aug 07, 2022 |
| GVC           | DR 738                      | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | Notebook    | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| MSI           | H81M-P33                    | Desktop     | [10fc9a4368](https://bsd-hardware.info/?probe=10fc9a4368) | Jul 31, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10139014e1](https://bsd-hardware.info/?probe=10139014e1) | Jul 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1129960acb](https://bsd-hardware.info/?probe=1129960acb) | Jul 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| HP            | 1825                        | Desktop     | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2f7e57d927](https://bsd-hardware.info/?probe=2f7e57d927) | Jul 24, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [6fd0d31624](https://bsd-hardware.info/?probe=6fd0d31624) | Jul 24, 2022 |
| Dell          | Precision 5560              | Notebook    | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [321d3333dd](https://bsd-hardware.info/?probe=321d3333dd) | Jul 19, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [6308d8da4f](https://bsd-hardware.info/?probe=6308d8da4f) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [c9d1bc6685](https://bsd-hardware.info/?probe=c9d1bc6685) | Jul 17, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c02a92f29](https://bsd-hardware.info/?probe=7c02a92f29) | Jul 17, 2022 |
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
| MSI           | H81M-P33                    | Desktop     | [698249149d](https://bsd-hardware.info/?probe=698249149d) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2a2cdcbbb](https://bsd-hardware.info/?probe=c2a2cdcbbb) | Jul 10, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [0c830d88dc](https://bsd-hardware.info/?probe=0c830d88dc) | Jul 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [7bad2fce01](https://bsd-hardware.info/?probe=7bad2fce01) | Jul 07, 2022 |
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
| MSI           | H81M-P33                    | Desktop     | [e482fbe2d2](https://bsd-hardware.info/?probe=e482fbe2d2) | Jul 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d5dd169581](https://bsd-hardware.info/?probe=d5dd169581) | Jul 03, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [7a998b2fa4](https://bsd-hardware.info/?probe=7a998b2fa4) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [452aabec42](https://bsd-hardware.info/?probe=452aabec42) | Jul 02, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e0c49be06e](https://bsd-hardware.info/?probe=e0c49be06e) | Jun 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [079fcf320f](https://bsd-hardware.info/?probe=079fcf320f) | Jun 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bbc59d9815](https://bsd-hardware.info/?probe=bbc59d9815) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6eb02df970](https://bsd-hardware.info/?probe=6eb02df970) | Jun 26, 2022 |
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
| Dell          | Inspiron 5559               | Notebook    | [5b7a6bf8f8](https://bsd-hardware.info/?probe=5b7a6bf8f8) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Intel         | NUC7i5BNB J31144-306        | Mini pc     | [66f9b621be](https://bsd-hardware.info/?probe=66f9b621be) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [3344e5152d](https://bsd-hardware.info/?probe=3344e5152d) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [9f630c894a](https://bsd-hardware.info/?probe=9f630c894a) | Jun 16, 2022 |
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
| MSI           | H81M-P33                    | Desktop     | [87a66430db](https://bsd-hardware.info/?probe=87a66430db) | Jun 12, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [9b34d14850](https://bsd-hardware.info/?probe=9b34d14850) | Jun 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c281c439e8](https://bsd-hardware.info/?probe=c281c439e8) | Jun 12, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [e7017b0ea5](https://bsd-hardware.info/?probe=e7017b0ea5) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | Latitude E5420              | Notebook    | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [b9169c863c](https://bsd-hardware.info/?probe=b9169c863c) | Jun 08, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [1a9b85f6c5](https://bsd-hardware.info/?probe=1a9b85f6c5) | Jun 07, 2022 |
| Dell          | Latitude E5420              | Notebook    | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| MSI           | H81M-P33                    | Desktop     | [49ab973713](https://bsd-hardware.info/?probe=49ab973713) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7f11ab4091](https://bsd-hardware.info/?probe=7f11ab4091) | Jun 05, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10381fadd6](https://bsd-hardware.info/?probe=10381fadd6) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [0f0c2bcf67](https://bsd-hardware.info/?probe=0f0c2bcf67) | Jun 04, 2022 |
| Dell          | Latitude E5500              | Notebook    | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | Notebook    | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| GPD           | MicroPC                     | Notebook    | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ca9f2125af](https://bsd-hardware.info/?probe=ca9f2125af) | May 31, 2022 |
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
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a4b6a40758](https://bsd-hardware.info/?probe=a4b6a40758) | May 19, 2022 |
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
| amd64 | 133       | 95.68%  |
| arm64 | 4         | 2.88%   |
| i386  | 1         | 0.72%   |
| arm   | 1         | 0.72%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Console    | 47        | 33.81%  |
| KDE5       | 25        | 17.99%  |
| XFCE       | 22        | 15.83%  |
| GNOME      | 12        | 8.63%   |
| TWM        | 7         | 5.04%   |
| Openbox    | 5         | 3.6%    |
| MATE       | 5         | 3.6%    |
| i3         | 5         | 3.6%    |
| Cinnamon   | 3         | 2.16%   |
| LXQt       | 2         | 1.44%   |
| xfwm       | 1         | 0.72%   |
| X-Cinnamon | 1         | 0.72%   |
| LXDE       | 1         | 0.72%   |
| IceWM      | 1         | 0.72%   |
| dwm        | 1         | 0.72%   |
| Compton    | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 86        | 61.87%  |
| Console | 50        | 35.97%  |
| Wayland | 3         | 2.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 77        | 55.4%   |
| SDDM    | 23        | 16.55%  |
| SLiM    | 17        | 12.23%  |
| XDM     | 8         | 5.76%   |
| GDM     | 7         | 5.04%   |
| LightDM | 6         | 4.32%   |
| PCDM    | 1         | 0.72%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 95        | 67.86%  |
| en_US           | 18        | 12.86%  |
| ru_RU           | 9         | 6.43%   |
| Unknown         | 6         | 4.29%   |
| fr_FR           | 4         | 2.86%   |
| zh_CN           | 3         | 2.14%   |
| ja_JP           | 1         | 0.71%   |
| en_US.ISO8859-1 | 1         | 0.71%   |
| en_GB           | 1         | 0.71%   |
| en_AU           | 1         | 0.71%   |
| de_DE           | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 104       | 74.29%  |
| BIOS | 36        | 25.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 94        | 67.14%  |
| Ufs  | 46        | 32.86%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 127       | 91.37%  |
| MBR  | 11        | 7.91%   |
| BSD  | 1         | 0.72%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 17.99%  |
| Lenovo                  | 21        | 15.11%  |
| ASUSTek Computer        | 19        | 13.67%  |
| Intel                   | 9         | 6.47%   |
| Hewlett-Packard         | 9         | 6.47%   |
| Gigabyte Technology     | 9         | 6.47%   |
| ASRock                  | 6         | 4.32%   |
| Unknown                 | 6         | 4.32%   |
| MSI                     | 5         | 3.6%    |
| Acer                    | 5         | 3.6%    |
| Fujitsu                 | 3         | 2.16%   |
| TUXEDO                  | 2         | 1.44%   |
| Toshiba                 | 2         | 1.44%   |
| Apple                   | 2         | 1.44%   |
| System76                | 1         | 0.72%   |
| Supermicro              | 1         | 0.72%   |
| Sony                    | 1         | 0.72%   |
| Samsung Electronics     | 1         | 0.72%   |
| Raspberry Pi Foundation | 1         | 0.72%   |
| PC Engines              | 1         | 0.72%   |
| Notebook                | 1         | 0.72%   |
| NF-M2S                  | 1         | 0.72%   |
| MouseComputer           | 1         | 0.72%   |
| LG Electronics          | 1         | 0.72%   |
| GVC                     | 1         | 0.72%   |
| GPD                     | 1         | 0.72%   |
| Google                  | 1         | 0.72%   |
| Fujitsu Siemens         | 1         | 0.72%   |
| BESSTAR Tech            | 1         | 0.72%   |
| ASRockRack              | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 6         | 4.32%   |
| ASUS All Series                         | 3         | 2.16%   |
| MSI MS-7817                             | 2         | 1.44%   |
| HP EliteBook 850 G7 Notebook PC         | 2         | 1.44%   |
| TUXEDO InfinityBook13V3                 | 1         | 0.72%   |
| TUXEDO Aura 15 Gen1                     | 1         | 0.72%   |
| Toshiba Satellite L305D                 | 1         | 0.72%   |
| Toshiba Satellite A300                  | 1         | 0.72%   |
| System76 Galago Pro                     | 1         | 0.72%   |
| Supermicro Icebreaker 4824              | 1         | 0.72%   |
| Sony VGN-NS21M_S                        | 1         | 0.72%   |
| Samsung R530/R730/R540                  | 1         | 0.72%   |
| RPi Raspberry Pi                        | 1         | 0.72%   |
| PC Engines APU3                         | 1         | 0.72%   |
| Notebook N7x0WU                         | 1         | 0.72%   |
| NF-M2S ABIT                             | 1         | 0.72%   |
| MSI MS-B120                             | 1         | 0.72%   |
| MSI MS-7D09                             | 1         | 0.72%   |
| MSI GF63 Thin 9SC                       | 1         | 0.72%   |
| MouseComputer B360M                     | 1         | 0.72%   |
| LG 17Z990-R.AAC9U1                      | 1         | 0.72%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 1         | 0.72%   |
| Lenovo ThinkPad X270 20HMCTO1WW         | 1         | 0.72%   |
| Lenovo ThinkPad X260 20F6S0KA00         | 1         | 0.72%   |
| Lenovo ThinkPad X250 20CMS0FA00         | 1         | 0.72%   |
| Lenovo ThinkPad X220 4286CTO            | 1         | 0.72%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT    | 1         | 0.72%   |
| Lenovo ThinkPad W520 4282AD4            | 1         | 0.72%   |
| Lenovo ThinkPad T480 20L6SB2N00         | 1         | 0.72%   |
| Lenovo ThinkPad T480 20L6S29E0T         | 1         | 0.72%   |
| Lenovo ThinkPad T420s 41732AU           | 1         | 0.72%   |
| Lenovo ThinkPad T420 4236C92            | 1         | 0.72%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW    | 1         | 0.72%   |
| Lenovo ThinkPad L420 7854CTO            | 1         | 0.72%   |
| Lenovo ThinkPad E490 20N8CTO1WW         | 1         | 0.72%   |
| Lenovo ThinkCentre M53 10DES00F00       | 1         | 0.72%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT       | 1         | 0.72%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5        | 1         | 0.72%   |
| Lenovo IdeaPad 330-15ARR 81D2           | 1         | 0.72%   |
| Lenovo IdeaPad 130-15AST 81H5           | 1         | 0.72%   |
| Lenovo G40-45 80E1                      | 1         | 0.72%   |
| Lenovo C440 10104                       | 1         | 0.72%   |
| Intel X79 V2.72A                        | 1         | 0.72%   |
| Intel Q3XXG4-P V1.0                     | 1         | 0.72%   |
| Intel NUC9i7QNX                         | 1         | 0.72%   |
| Intel NUC7i5BNK                         | 1         | 0.72%   |
| Intel NUC7i3BNB J22859-303              | 1         | 0.72%   |
| Intel NUC11PAHi5                        | 1         | 0.72%   |
| Intel NUC10i3FNH                        | 1         | 0.72%   |
| Intel DN2820FYK H24582-203              | 1         | 0.72%   |
| Intel D945GCLF2 AAE46416-104            | 1         | 0.72%   |
| HP Z620 Workstation                     | 1         | 0.72%   |
| HP ProLiant ML310e Gen8 v2              | 1         | 0.72%   |
| HP Pavilion g6                          | 1         | 0.72%   |
| HP Laptop 15s-fq1xxx                    | 1         | 0.72%   |
| HP EliteDesk 800 G1 DM                  | 1         | 0.72%   |
| HP Desktop M01-F0xxx                    | 1         | 0.72%   |
| HP Compaq dc7900 Small Form Factor      | 1         | 0.72%   |
| GVC EQUIUM 3200M                        | 1         | 0.72%   |
| GPD MicroPC                             | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 13        | 9.35%   |
| Dell Latitude           | 8         | 5.76%   |
| Dell OptiPlex           | 6         | 4.32%   |
| Unknown                 | 6         | 4.32%   |
| Dell Inspiron           | 4         | 2.88%   |
| ASUS ZenBook            | 4         | 2.88%   |
| Lenovo IdeaPad          | 3         | 2.16%   |
| Dell Precision          | 3         | 2.16%   |
| ASUS ROG                | 3         | 2.16%   |
| ASUS PRIME              | 3         | 2.16%   |
| ASUS All                | 3         | 2.16%   |
| Toshiba Satellite       | 2         | 1.44%   |
| MSI MS-7817             | 2         | 1.44%   |
| HP EliteBook            | 2         | 1.44%   |
| Dell G5                 | 2         | 1.44%   |
| ASUS VivoBook           | 2         | 1.44%   |
| Acer Aspire             | 2         | 1.44%   |
| TUXEDO InfinityBook13V3 | 1         | 0.72%   |
| TUXEDO Aura             | 1         | 0.72%   |
| System76 Galago         | 1         | 0.72%   |
| Supermicro Icebreaker   | 1         | 0.72%   |
| Sony VGN-NS21M          | 1         | 0.72%   |
| Samsung R530            | 1         | 0.72%   |
| RPi Raspberry           | 1         | 0.72%   |
| PC Engines APU3         | 1         | 0.72%   |
| Notebook N7x0WU         | 1         | 0.72%   |
| NF-M2S ABIT             | 1         | 0.72%   |
| MSI MS-B120             | 1         | 0.72%   |
| MSI MS-7D09             | 1         | 0.72%   |
| MSI GF63                | 1         | 0.72%   |
| MouseComputer B360M     | 1         | 0.72%   |
| LG 17Z990-R.AAC9U1      | 1         | 0.72%   |
| Lenovo ThinkSystem      | 1         | 0.72%   |
| Lenovo ThinkCentre      | 1         | 0.72%   |
| Lenovo IdeaPadFlex      | 1         | 0.72%   |
| Lenovo G40-45           | 1         | 0.72%   |
| Lenovo C440             | 1         | 0.72%   |
| Intel X79               | 1         | 0.72%   |
| Intel Q3XXG4-P          | 1         | 0.72%   |
| Intel NUC9i7QNX         | 1         | 0.72%   |
| Intel NUC7i5BNK         | 1         | 0.72%   |
| Intel NUC7i3BNB         | 1         | 0.72%   |
| Intel NUC11PAHi5        | 1         | 0.72%   |
| Intel NUC10i3FNH        | 1         | 0.72%   |
| Intel DN2820FYK         | 1         | 0.72%   |
| Intel D945GCLF2         | 1         | 0.72%   |
| HP Z620                 | 1         | 0.72%   |
| HP ProLiant             | 1         | 0.72%   |
| HP Pavilion             | 1         | 0.72%   |
| HP Laptop               | 1         | 0.72%   |
| HP EliteDesk            | 1         | 0.72%   |
| HP Desktop              | 1         | 0.72%   |
| HP Compaq               | 1         | 0.72%   |
| GVC EQUIUM              | 1         | 0.72%   |
| GPD MicroPC             | 1         | 0.72%   |
| Google Peppy            | 1         | 0.72%   |
| Gigabyte Z370M          | 1         | 0.72%   |
| Gigabyte X470           | 1         | 0.72%   |
| Gigabyte P85-D3         | 1         | 0.72%   |
| Gigabyte H97M-HD3       | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 21        | 15.11%  |
| 2021    | 20        | 14.39%  |
| 2018    | 14        | 10.07%  |
| 2019    | 12        | 8.63%   |
| 2022    | 11        | 7.91%   |
| 2014    | 9         | 6.47%   |
| 2016    | 8         | 5.76%   |
| 2011    | 8         | 5.76%   |
| 2013    | 7         | 5.04%   |
| 2012    | 5         | 3.6%    |
| 2008    | 5         | 3.6%    |
| Unknown | 5         | 3.6%    |
| 2017    | 4         | 2.88%   |
| 2015    | 4         | 2.88%   |
| 2010    | 3         | 2.16%   |
| 2009    | 3         | 2.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 63        | 45.32%  |
| Desktop        | 61        | 43.88%  |
| Mini pc        | 9         | 6.47%   |
| Convertible    | 2         | 1.44%   |
| Server         | 2         | 1.44%   |
| System on chip | 1         | 0.72%   |
| All in one     | 1         | 0.72%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 136       | 97.84%  |
| Yes  | 3         | 2.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 44        | 31.43%  |
| 8.01-16.0   | 40        | 28.57%  |
| 4.01-8.0    | 17        | 12.14%  |
| 32.01-64.0  | 13        | 9.29%   |
| 64.01-256.0 | 12        | 8.57%   |
| 2.01-3.0    | 6         | 4.29%   |
| 24.01-32.0  | 3         | 2.14%   |
| 3.01-4.0    | 2         | 1.43%   |
| 0.01-0.5    | 2         | 1.43%   |
| 0.51-1.0    | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 55        | 39.29%  |
| 0.51-1.0  | 43        | 30.71%  |
| 1.01-2.0  | 25        | 17.86%  |
| 2.01-3.0  | 10        | 7.14%   |
| 0         | 3         | 2.14%   |
| 3.01-4.0  | 2         | 1.43%   |
| 4.01-8.0  | 1         | 0.71%   |
| 8.01-16.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 69        | 49.29%  |
| 2      | 32        | 22.86%  |
| 3      | 11        | 7.86%   |
| 0      | 9         | 6.43%   |
| 4      | 8         | 5.71%   |
| 8      | 3         | 2.14%   |
| 6      | 2         | 1.43%   |
| 18     | 1         | 0.71%   |
| 16     | 1         | 0.71%   |
| 15     | 1         | 0.71%   |
| 11     | 1         | 0.71%   |
| 10     | 1         | 0.71%   |
| 5      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 71.94%  |
| Yes       | 39        | 28.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 83.45%  |
| No        | 23        | 16.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 62.59%  |
| No        | 52        | 37.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 58.27%  |
| Yes       | 58        | 41.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 37        | 26.43%  |
| Russia      | 15        | 10.71%  |
| Germany     | 12        | 8.57%   |
| France      | 7         | 5%      |
| Spain       | 6         | 4.29%   |
| Austria     | 5         | 3.57%   |
| Netherlands | 4         | 2.86%   |
| Japan       | 4         | 2.86%   |
| India       | 4         | 2.86%   |
| Czechia     | 4         | 2.86%   |
| Australia   | 4         | 2.86%   |
| UK          | 3         | 2.14%   |
| Thailand    | 3         | 2.14%   |
| Italy       | 3         | 2.14%   |
| China       | 3         | 2.14%   |
| Canada      | 3         | 2.14%   |
| Philippines | 2         | 1.43%   |
| New Zealand | 2         | 1.43%   |
| Hong Kong   | 2         | 1.43%   |
| Uruguay     | 1         | 0.71%   |
| Turkey      | 1         | 0.71%   |
| Taiwan      | 1         | 0.71%   |
| Slovenia    | 1         | 0.71%   |
| Norway      | 1         | 0.71%   |
| Malaysia    | 1         | 0.71%   |
| Latvia      | 1         | 0.71%   |
| Kenya       | 1         | 0.71%   |
| Israel      | 1         | 0.71%   |
| Ireland     | 1         | 0.71%   |
| Hungary     | 1         | 0.71%   |
| Guadeloupe  | 1         | 0.71%   |
| Greece      | 1         | 0.71%   |
| Croatia     | 1         | 0.71%   |
| Bulgaria    | 1         | 0.71%   |
| Brazil      | 1         | 0.71%   |
| Belgium     | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 6         | 4.26%   |
| Vienna            | 4         | 2.84%   |
| Ozersk            | 4         | 2.84%   |
| Frisco            | 4         | 2.84%   |
| Brno              | 4         | 2.84%   |
| Tamm              | 3         | 2.13%   |
| Paris             | 3         | 2.13%   |
| Omaha             | 3         | 2.13%   |
| Madrid            | 3         | 2.13%   |
| Wellington        | 2         | 1.42%   |
| Redmond           | 2         | 1.42%   |
| Nashville         | 2         | 1.42%   |
| Charlotte         | 2         | 1.42%   |
| Central           | 2         | 1.42%   |
| Zhumadian         | 1         | 0.71%   |
| Zagreb            | 1         | 0.71%   |
| Yashio            | 1         | 0.71%   |
| Xi'an             | 1         | 0.71%   |
| Woerdense Verlaat | 1         | 0.71%   |
| Wheatland         | 1         | 0.71%   |
| Wenatchee         | 1         | 0.71%   |
| Waldbrunn         | 1         | 0.71%   |
| Vaulx-en-Velin    | 1         | 0.71%   |
| Valladolid        | 1         | 0.71%   |
| Trivandrum        | 1         | 0.71%   |
| Toronto           | 1         | 0.71%   |
| Tiel              | 1         | 0.71%   |
| Thousand Oaks     | 1         | 0.71%   |
| Thessaloniki      | 1         | 0.71%   |
| Tel Aviv          | 1         | 0.71%   |
| Taito             | 1         | 0.71%   |
| Taipei            | 1         | 0.71%   |
| Sydney            | 1         | 0.71%   |
| St. Albert        | 1         | 0.71%   |
| St Petersburg     | 1         | 0.71%   |
| Sofia             | 1         | 0.71%   |
| Shinjuku          | 1         | 0.71%   |
| Shah Alam         | 1         | 0.71%   |
| Sarasota          | 1         | 0.71%   |
| Sao Paulo         | 1         | 0.71%   |
| Sandefjord        | 1         | 0.71%   |
| San Pablo City    | 1         | 0.71%   |
| Saarbrücken      | 1         | 0.71%   |
| Riverside         | 1         | 0.71%   |
| Riga              | 1         | 0.71%   |
| Rialto            | 1         | 0.71%   |
| Poperinge         | 1         | 0.71%   |
| Pluvigner         | 1         | 0.71%   |
| Perth             | 1         | 0.71%   |
| Oswego            | 1         | 0.71%   |
| Newbury Park      | 1         | 0.71%   |
| New York          | 1         | 0.71%   |
| Nakhodka          | 1         | 0.71%   |
| Nakano            | 1         | 0.71%   |
| Nairobi           | 1         | 0.71%   |
| Münster          | 1         | 0.71%   |
| Munich            | 1         | 0.71%   |
| Mumbai            | 1         | 0.71%   |
| Mossingen         | 1         | 0.71%   |
| Montreal          | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 49        | 91     | 24.75%  |
| Samsung Electronics | 36        | 59     | 18.18%  |
| Seagate             | 27        | 75     | 13.64%  |
| Crucial             | 13        | 20     | 6.57%   |
| Toshiba             | 12        | 19     | 6.06%   |
| Kingston            | 9         | 9      | 4.55%   |
| Intel               | 6         | 15     | 3.03%   |
| SK hynix            | 5         | 5      | 2.53%   |
| Transcend           | 4         | 4      | 2.02%   |
| Hitachi             | 4         | 4      | 2.02%   |
| Hewlett-Packard     | 3         | 3      | 1.52%   |
| Gigabyte Technology | 3         | 3      | 1.52%   |
| A-DATA Technology   | 3         | 6      | 1.52%   |
| SanDisk             | 2         | 2      | 1.01%   |
| Micron Technology   | 2         | 3      | 1.01%   |
| Apple               | 2         | 2      | 1.01%   |
| Verbatim            | 1         | 1      | 0.51%   |
| SPCC                | 1         | 1      | 0.51%   |
| Silicon Motion      | 1         | 1      | 0.51%   |
| PNY                 | 1         | 2      | 0.51%   |
| ORICO               | 1         | 1      | 0.51%   |
| OCZ                 | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| Lexar               | 1         | 2      | 0.51%   |
| Lenovo              | 1         | 1      | 0.51%   |
| KIOXIA              | 1         | 1      | 0.51%   |
| Hikvision           | 1         | 1      | 0.51%   |
| HGST                | 1         | 1      | 0.51%   |
| EAGET               | 1         | 1      | 0.51%   |
| China               | 1         | 1      | 0.51%   |
| CFD                 | 1         | 1      | 0.51%   |
| BR                  | 1         | 1      | 0.51%   |
| BIWIN               | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                | 4         | 1.72%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.72%   |
| WDC WD5000LPLX-00ZNTT0 500GB            | 3         | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.29%   |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 1.29%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.29%   |
| A-DATA SU650 240GB                      | 3         | 1.29%   |
| WDC WD30EFRX-68EUZN0 3TB                | 2         | 0.86%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.86%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 2         | 0.86%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB    | 2         | 0.86%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.86%   |
| Seagate ST4000DM000-1F2168 4TB          | 2         | 0.86%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.86%   |
| Samsung SSD 870 QVO 2TB                 | 2         | 0.86%   |
| Samsung SSD 840 EVO 120GB               | 2         | 0.86%   |
| Kingston SA400S37120G 120GB             | 2         | 0.86%   |
| Intel SSDSC2CT060A3 64GB                | 2         | 0.86%   |
| Crucial CT1000P5SSD8 1TB                | 2         | 0.86%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 0.86%   |
| WDC WDS500G3X0C-00SJG0 500GB            | 1         | 0.43%   |
| WDC WDS500G2X0C-00L350 500GB            | 1         | 0.43%   |
| WDC WDS500G1B0A-00H9H0 500GB            | 1         | 0.43%   |
| WDC WDS250G2B0C-00PXH0 250GB            | 1         | 0.43%   |
| WDC WDS250G2B0B-00YS70 250GB            | 1         | 0.43%   |
| WDC WDS250G2B0A-00SM50 250GB            | 1         | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB            | 1         | 0.43%   |
| WDC WDS100T2B0B-00YS70 1TB              | 1         | 0.43%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1         | 0.43%   |
| WDC WDBA3V5000ANC-WRSN 500GB            | 1         | 0.43%   |
| WDC WD80EZZX-11CSGA0 8TB                | 1         | 0.43%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 1         | 0.43%   |
| WDC WD80EMZZ-00TBGA0 8TB                | 1         | 0.43%   |
| WDC WD80EFBX-68AZZN0 8TB                | 1         | 0.43%   |
| WDC WD8003FFBX-68B9AN0 8TB              | 1         | 0.43%   |
| WDC WD60EFRX-68L0BN1 6TB                | 1         | 0.43%   |
| WDC WD5000LUCT-63Y8HY0 500GB            | 1         | 0.43%   |
| WDC WD5000BEVT-22ZAT0 500GB             | 1         | 0.43%   |
| WDC WD40EZRZ-22GXCB0 4TB                | 1         | 0.43%   |
| WDC WD4003FRYZ-01F0DB0 4TB              | 1         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.43%   |
| WDC WD3200BEKT-60PVMT0 320GB            | 1         | 0.43%   |
| WDC WD30EFRX-68N32N0 3TB                | 1         | 0.43%   |
| WDC WD30EFRX-68AX9N0 3TB                | 1         | 0.43%   |
| WDC WD2500BEVT-24A23T0 250GB            | 1         | 0.43%   |
| WDC WD20SPZX-00UA7T0 2TB                | 1         | 0.43%   |
| WDC WD20NMVW-11EDZS2 2TB                | 1         | 0.43%   |
| WDC WD20NMVW-11AV3S2 2TB                | 1         | 0.43%   |
| WDC WD20EARX-00PASB0 2TB                | 1         | 0.43%   |
| WDC WD2003FYYS-18W0B0 2TB               | 1         | 0.43%   |
| WDC WD1600BEVT-80A23T0 160GB            | 1         | 0.43%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.43%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 1         | 0.43%   |
| WDC WD1600AAJS-60M0A0 160GB             | 1         | 0.43%   |
| WDC WD15EADS-00P8B0 1.5TB               | 1         | 0.43%   |
| WDC WD140EFGX-68B0GN0 14TB              | 1         | 0.43%   |
| WDC WD10SPZX-75Z10T3 1TB                | 1         | 0.43%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.43%   |
| WDC WD10EZEX-60M2NA0 1TB                | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 75     | 44.87%  |
| Seagate             | 26        | 74     | 33.33%  |
| Toshiba             | 9         | 16     | 11.54%  |
| Hitachi             | 4         | 4      | 5.13%   |
| Samsung Electronics | 1         | 4      | 1.28%   |
| HGST                | 1         | 1      | 1.28%   |
| Hewlett-Packard     | 1         | 1      | 1.28%   |
| Apple               | 1         | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 37     | 27.03%  |
| Crucial             | 10        | 12     | 13.51%  |
| WDC                 | 6         | 6      | 8.11%   |
| Kingston            | 5         | 5      | 6.76%   |
| Intel               | 5         | 14     | 6.76%   |
| Transcend           | 3         | 3      | 4.05%   |
| A-DATA Technology   | 3         | 6      | 4.05%   |
| Toshiba             | 2         | 2      | 2.7%    |
| SanDisk             | 2         | 2      | 2.7%    |
| Verbatim            | 1         | 1      | 1.35%   |
| SPCC                | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| PNY                 | 1         | 2      | 1.35%   |
| ORICO               | 1         | 1      | 1.35%   |
| OCZ                 | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 2      | 1.35%   |
| LITEONIT            | 1         | 1      | 1.35%   |
| Lexar               | 1         | 2      | 1.35%   |
| Lenovo              | 1         | 1      | 1.35%   |
| Hikvision           | 1         | 1      | 1.35%   |
| Hewlett-Packard     | 1         | 1      | 1.35%   |
| Gigabyte Technology | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| CFD                 | 1         | 1      | 1.35%   |
| BR                  | 1         | 1      | 1.35%   |
| BIWIN               | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 65        | 108    | 36.93%  |
| HDD  | 65        | 176    | 36.93%  |
| NVMe | 46        | 56     | 26.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 284    | 69.93%  |
| NVMe | 46        | 56     | 30.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 92     | 47.14%  |
| 0.51-1.0   | 45        | 69     | 32.14%  |
| 1.01-2.0   | 12        | 32     | 8.57%   |
| 3.01-4.0   | 6         | 16     | 4.29%   |
| 4.01-10.0  | 5         | 39     | 3.57%   |
| 2.01-3.0   | 3         | 16     | 2.14%   |
| 10.01-20.0 | 3         | 20     | 2.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 41        | 29.29%  |
| 251-500        | 31        | 22.14%  |
| 501-1000       | 26        | 18.57%  |
| 51-100         | 14        | 10%     |
| 21-50          | 11        | 7.86%   |
| 1001-2000      | 7         | 5%      |
| 1-20           | 4         | 2.86%   |
| 2001-3000      | 3         | 2.14%   |
| More than 3000 | 2         | 1.43%   |
| Unknown        | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 79.29%  |
| 21-50          | 17        | 12.14%  |
| 51-100         | 4         | 2.86%   |
| 101-250        | 3         | 2.14%   |
| 251-500        | 2         | 1.43%   |
| More than 3000 | 1         | 0.71%   |
| 501-1000       | 1         | 0.71%   |
| Unknown        | 1         | 0.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-00ZNTT0 500GB                 | 1         | 1      | 4.76%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 4.76%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 3      | 4.76%   |
| WDC WD2500BEVT-24A23T0 250GB                 | 1         | 1      | 4.76%   |
| WDC WD1600AAJS-60M0A0 160GB                  | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 4.76%   |
| SPCC M.2 SSD 256GB                           | 1         | 1      | 4.76%   |
| SK hynix SC308 SATA 128GB                    | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 4.76%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 2      | 4.76%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB | 1         | 1      | 4.76%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB   | 1         | 2      | 4.76%   |
| Hitachi HTS727575A9E364 752GB                | 1         | 1      | 4.76%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 4.76%   |
| Hitachi HTS543232L9SA00 320GB                | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4.76%   |
| Hewlett-Packard MB1000GCWCV 1TB              | 1         | 1      | 4.76%   |
| A-DATA Technology SU630 240GB                | 1         | 2      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 7      | 20%     |
| Seagate             | 4         | 5      | 20%     |
| Hitachi             | 3         | 3      | 15%     |
| Toshiba             | 2         | 2      | 10%     |
| SPCC                | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| Micron Technology   | 1         | 2      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 2      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 4         | 7      | 26.67%  |
| Seagate         | 4         | 5      | 26.67%  |
| Hitachi         | 3         | 3      | 20%     |
| Toshiba         | 2         | 2      | 13.33%  |
| HGST            | 1         | 1      | 6.67%   |
| Hewlett-Packard | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 73.68%  |
| SSD  | 5         | 7      | 26.32%  |

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
| Works    | 118       | 305    | 84.89%  |
| Malfunc  | 17        | 26     | 12.23%  |
| Detected | 4         | 9      | 2.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 97        | 54.8%   |
| Samsung Electronics         | 18        | 10.17%  |
| AMD                         | 18        | 10.17%  |
| SanDisk                     | 9         | 5.08%   |
| Silicon Motion              | 4         | 2.26%   |
| Kingston Technology Company | 4         | 2.26%   |
| Broadcom / LSI              | 4         | 2.26%   |
| SK hynix                    | 3         | 1.69%   |
| Micron/Crucial Technology   | 3         | 1.69%   |
| Marvell Technology Group    | 3         | 1.69%   |
| ASMedia Technology          | 3         | 1.69%   |
| Phison Electronics          | 2         | 1.13%   |
| Nvidia                      | 2         | 1.13%   |
| Micron Technology           | 2         | 1.13%   |
| Toshiba                     | 1         | 0.56%   |
| Silicon Image               | 1         | 0.56%   |
| Seagate Technology          | 1         | 0.56%   |
| KIOXIA                      | 1         | 0.56%   |
| Unknown                     | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 6.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 5.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 4.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 4.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.13%   |
| Unknown                                                                          | 5         | 2.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 2.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 2.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 2.08%   |
| AMD 500 Series Chipset SATA Controller                                           | 4         | 2.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.56%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 3         | 1.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.56%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 1.56%   |
| SK hynix BC511                                                                   | 2         | 1.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.04%   |
| SanDisk unknown                                                                  | 2         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 1.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 1.04%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                           | 2         | 1.04%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.52%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.52%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                               | 1         | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.52%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.52%   |
| Samsung SM951 AHCI                                                               | 1         | 0.52%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.52%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.52%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.52%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.52%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.52%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 0.52%   |
| Nvidia MCP61 IDE                                                                 | 1         | 0.52%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.52%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                     | 1         | 0.52%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 1         | 0.52%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.52%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.52%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                               | 1         | 0.52%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.52%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.52%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 105       | 60.34%  |
| NVMe | 45        | 25.86%  |
| RAID | 10        | 5.75%   |
| IDE  | 10        | 5.75%   |
| SAS  | 4         | 2.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 79.86%  |
| AMD    | 23        | 16.55%  |
| ARM    | 5         | 3.6%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 2.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 2.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 2.14%   |
| ARM Cortex-A53 r0p4                     | 3         | 2.14%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 3         | 2.14%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.43%   |
| Intel Core i5-8400 CPU @ 2.80GHz        | 2         | 1.43%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 1.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.43%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 2         | 1.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 1.43%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz     | 1         | 0.71%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 1         | 0.71%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1         | 0.71%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 1         | 0.71%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH       | 1         | 0.71%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.71%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz     | 1         | 0.71%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz     | 1         | 0.71%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz     | 1         | 0.71%   |
| Intel Pentium Silver N6000 @ 1.10GHz    | 1         | 0.71%   |
| Intel Pentium II                        | 1         | 0.71%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 0.71%   |
| Intel Pentium CPU G3220 @ 3.00GHz       | 1         | 0.71%   |
| Intel Genuine CPU                       | 1         | 0.71%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1         | 0.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 0.71%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz      | 1         | 0.71%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 1         | 0.71%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 1         | 0.71%   |
| Intel Core i7-4785T CPU @ 2.20GHz       | 1         | 0.71%   |
| Intel Core i7-4610M CPU @ 3.00GHz       | 1         | 0.71%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 1         | 0.71%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 1         | 0.71%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 0.71%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 1         | 0.71%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 1         | 0.71%   |
| Intel Core i7-2600K CPU @ 3.40GHz       | 1         | 0.71%   |
| Intel Core i7-10700K CPU @ 3.80GHz      | 1         | 0.71%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 1         | 0.71%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.71%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 1         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 0.71%   |
| Intel Core i5-7260U CPU @ 2.20GHz       | 1         | 0.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 0.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz       | 1         | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 0.71%   |
| Intel Core i5-4690 CPU @ 3.50GHz        | 1         | 0.71%   |
| Intel Core i5-4670K CPU @ 3.40GHz       | 1         | 0.71%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1         | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 1         | 0.71%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 1         | 0.71%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 35        | 25.18%  |
| Intel Core i7        | 29        | 20.86%  |
| Intel Core i3        | 10        | 7.19%   |
| Intel Xeon           | 8         | 5.76%   |
| Intel Celeron        | 8         | 5.76%   |
| Other                | 7         | 5.04%   |
| AMD Ryzen 5          | 6         | 4.32%   |
| Intel Core 2 Duo     | 5         | 3.6%    |
| AMD Ryzen 7          | 5         | 3.6%    |
| ARM Cortex           | 4         | 2.88%   |
| Intel Atom           | 3         | 2.16%   |
| Intel Pentium        | 2         | 1.44%   |
| AMD Ryzen 9          | 2         | 1.44%   |
| AMD Ryzen 7 PRO      | 2         | 1.44%   |
| AMD Ryzen 3          | 2         | 1.44%   |
| Intel Xeon Gold      | 1         | 0.72%   |
| Intel Pentium Silver | 1         | 0.72%   |
| Intel Pentium Dual   | 1         | 0.72%   |
| Intel Genuine        | 1         | 0.72%   |
| Intel Core 2 Quad    | 1         | 0.72%   |
| AMD GX               | 1         | 0.72%   |
| AMD E2               | 1         | 0.72%   |
| AMD Athlon X2        | 1         | 0.72%   |
| AMD Athlon 64 X2     | 1         | 0.72%   |
| AMD A8               | 1         | 0.72%   |
| AMD A10              | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 48        | 34.53%  |
| 2       | 46        | 33.09%  |
| 6       | 11        | 7.91%   |
| 8       | 10        | 7.19%   |
| 16      | 8         | 5.76%   |
| Unknown | 8         | 5.76%   |
| 12      | 4         | 2.88%   |
| 24      | 2         | 1.44%   |
| 1       | 2         | 1.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 133       | 95.68%  |
| Unknown | 5         | 3.6%    |
| 2       | 1         | 0.72%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 74        | 53.24%  |
| 1       | 56        | 40.29%  |
| Unknown | 9         | 6.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 32        | 22.86%  |
| Haswell         | 15        | 10.71%  |
| SandyBridge     | 12        | 8.57%   |
| IvyBridge       | 9         | 6.43%   |
| Unknown         | 9         | 6.43%   |
| Skylake         | 7         | 5%      |
| Zen 3           | 5         | 3.57%   |
| Zen 2           | 5         | 3.57%   |
| CometLake       | 5         | 3.57%   |
| TigerLake       | 4         | 2.86%   |
| Core            | 4         | 2.86%   |
| Broadwell       | 4         | 2.86%   |
| Zen+            | 3         | 2.14%   |
| Zen             | 3         | 2.14%   |
| Silvermont      | 3         | 2.14%   |
| Penryn          | 3         | 2.14%   |
| Goldmont plus   | 3         | 2.14%   |
| Bonnell         | 3         | 2.14%   |
| Westmere        | 2         | 1.43%   |
| Puma            | 2         | 1.43%   |
| Piledriver      | 1         | 0.71%   |
| P6              | 1         | 0.71%   |
| K8 Hammer       | 1         | 0.71%   |
| K8 & K10 hybrid | 1         | 0.71%   |
| IceLake         | 1         | 0.71%   |
| Goldmont        | 1         | 0.71%   |
| Excavator       | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 86        | 58.5%   |
| Nvidia                               | 30        | 20.41%  |
| AMD                                  | 25        | 17.01%  |
| Matrox Electronics Systems           | 4         | 2.72%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.68%   |
| ASPEED Technology                    | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9         | 5.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 4.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 3.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 4         | 2.65%   |
| Intel UHD Graphics 620                                                      | 4         | 2.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 1.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 1.99%   |
| Intel HD Graphics 630                                                       | 3         | 1.99%   |
| Intel HD Graphics 620                                                       | 3         | 1.99%   |
| Intel HD Graphics 5500                                                      | 3         | 1.99%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.99%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 1.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 1.99%   |
| AMD Renoir                                                                  | 3         | 1.99%   |
| AMD Cezanne                                                                 | 3         | 1.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.32%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.32%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 1.32%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.32%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)           | 2         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 2         | 1.32%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.32%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2         | 1.32%   |
| Nvidia TU117M                                                               | 1         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 0.66%   |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 0.66%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1         | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1         | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1         | 0.66%   |
| Nvidia GF108M [GeForce 610M]                                                | 1         | 0.66%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.66%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1         | 0.66%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1         | 0.66%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                          | 1         | 0.66%   |
| Nvidia G98M [GeForce 9200M GS]                                              | 1         | 0.66%   |
| Nvidia C79 [GeForce 9400M G]                                                | 1         | 0.66%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1         | 0.66%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1         | 0.66%   |
| Matrox Electronics Systems MGA G200EH                                       | 1         | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.66%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 1         | 0.66%   |
| Intel Tiger Lake UHD Graphics                                               | 1         | 0.66%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1         | 0.66%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                           | 1         | 0.66%   |
| Intel JasperLake [UHD Graphics]                                             | 1         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 70        | 50.36%  |
| 1 x Nvidia                               | 18        | 12.95%  |
| 1 x AMD                                  | 18        | 12.95%  |
| Intel + Nvidia                           | 9         | 6.47%   |
| Other                                    | 6         | 4.32%   |
| 2 x Intel                                | 4         | 2.88%   |
| 1 x Matrox                               | 4         | 2.88%   |
| Intel + AMD                              | 3         | 2.16%   |
| 2 x AMD                                  | 2         | 1.44%   |
| AMD + Nvidia                             | 2         | 1.44%   |
| 2 x Nvidia                               | 1         | 0.72%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.72%   |
| 1 x ASPEED                               | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 114       | 82.01%  |
| Proprietary | 18        | 12.95%  |
| Unknown     | 7         | 5.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 79.86%  |
| 1.01-2.0   | 7         | 5.04%   |
| 0.51-1.0   | 7         | 5.04%   |
| 0.01-0.5   | 6         | 4.32%   |
| 3.01-4.0   | 3         | 2.16%   |
| 7.01-8.0   | 2         | 1.44%   |
| 5.01-6.0   | 2         | 1.44%   |
| 2.01-3.0   | 1         | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 16.49%  |
| LG Display          | 12        | 12.37%  |
| BOE                 | 11        | 11.34%  |
| Chimei Innolux      | 7         | 7.22%   |
| AU Optronics        | 6         | 6.19%   |
| Acer                | 6         | 6.19%   |
| Lenovo              | 4         | 4.12%   |
| Dell                | 4         | 4.12%   |
| Philips             | 3         | 3.09%   |
| Goldstar            | 3         | 3.09%   |
| BenQ                | 3         | 3.09%   |
| ViewSonic           | 2         | 2.06%   |
| Sceptre Tech        | 2         | 2.06%   |
| YTH                 | 1         | 1.03%   |
| Vestel Elektronik   | 1         | 1.03%   |
| USR                 | 1         | 1.03%   |
| Unknown (XXX)       | 1         | 1.03%   |
| Sharp               | 1         | 1.03%   |
| Panasonic           | 1         | 1.03%   |
| LG Philips          | 1         | 1.03%   |
| LG Electronics      | 1         | 1.03%   |
| JDI                 | 1         | 1.03%   |
| IOD                 | 1         | 1.03%   |
| Iiyama              | 1         | 1.03%   |
| Idek Iiyama         | 1         | 1.03%   |
| HannStar            | 1         | 1.03%   |
| CSO                 | 1         | 1.03%   |
| Compal              | 1         | 1.03%   |
| ASUSTek Computer    | 1         | 1.03%   |
| Apple               | 1         | 1.03%   |
| AOC                 | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 2         | 2.04%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 2         | 2.04%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2         | 2.04%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch           | 2         | 2.04%   |
| BenQ BL2480 BNQ802C 1920x1080 530x300mm 24.0-inch                      | 2         | 2.04%   |
| YTH HS133PC YTH1330 1920x1080 250x220mm 13.1-inch                      | 1         | 1.02%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 1.02%   |
| USR LCD Monitor USR0100 1920x1080 510x290mm 23.1-inch                  | 1         | 1.02%   |
| Unknown (XXX) SMART TV XXX2851 3840x2160                               | 1         | 1.02%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch                | 1         | 1.02%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 1.02%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1         | 1.02%   |
| Samsung Electronics LS24A40xU SAM71D1 1920x1080 530x300mm 24.0-inch    | 1         | 1.02%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 330x210mm 15.4-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 290x170mm 13.2-inch  | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1420x800mm 64.2-inch | 1         | 1.02%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1         | 1.02%   |
| Philips PHL 276E7 PHLC108 1920x1080 600x340mm 27.2-inch                | 1         | 1.02%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1         | 1.02%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1         | 1.02%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1         | 1.02%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch            | 1         | 1.02%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1         | 1.02%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD05F8 2560x1600 370x230mm 17.2-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch           | 1         | 1.02%   |
| LG Display LCD Monitor LGD03DD 1366x768 340x190mm 15.3-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch            | 1         | 1.02%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch            | 1         | 1.02%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1         | 1.02%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1         | 1.02%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch               | 1         | 1.02%   |
| Lenovo LCD Monitor LEN2000 1920x1080 480x270mm 21.7-inch               | 1         | 1.02%   |
| JDI LCD Monitor JDI385A 3840x2160 290x170mm 13.2-inch                  | 1         | 1.02%   |
| IOD KH270V IOD1B3B 1920x1080 600x340mm 27.2-inch                       | 1         | 1.02%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                   | 1         | 1.02%   |
| Idek Iiyama LCD Monitor PL2730Q 2560x1440                              | 1         | 1.02%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 1.02%   |
| Goldstar LG ULTRAGEAR GSM776E 2560x1440 700x390mm 31.5-inch            | 1         | 1.02%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1         | 1.02%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 1         | 1.02%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                     | 1         | 1.02%   |
| Dell LCD Monitor SP2309W 2048x1152                                     | 1         | 1.02%   |
| Dell IN2020M DELF030 1600x900 440x250mm 19.9-inch                      | 1         | 1.02%   |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                      | 1         | 1.02%   |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                  | 1         | 1.02%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch       | 1         | 1.02%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch       | 1         | 1.02%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 48.94%  |
| 1366x768 (WXGA)    | 12        | 12.77%  |
| 3840x2160 (4K)     | 7         | 7.45%   |
| 2560x1440 (QHD)    | 6         | 6.38%   |
| 1920x1200 (WUXGA)  | 3         | 3.19%   |
| 1600x900 (HD+)     | 3         | 3.19%   |
| 2560x1080          | 2         | 2.13%   |
| 1680x1050 (WSXGA+) | 2         | 2.13%   |
| 1280x800 (WXGA)    | 2         | 2.13%   |
| 1280x1024 (SXGA)   | 2         | 2.13%   |
| 3200x1800 (QHD+)   | 1         | 1.06%   |
| 2880x1800          | 1         | 1.06%   |
| 2560x1600          | 1         | 1.06%   |
| 2048x1152          | 1         | 1.06%   |
| 1920x540           | 1         | 1.06%   |
| 1440x900 (WXGA+)   | 1         | 1.06%   |
| 1024x768 (XGA)     | 1         | 1.06%   |
| 1024x600           | 1         | 1.06%   |
| Unknown            | 1         | 1.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 22.92%  |
| 13      | 20        | 20.83%  |
| 24      | 9         | 9.38%   |
| Unknown | 9         | 9.38%   |
| 27      | 8         | 8.33%   |
| 21      | 5         | 5.21%   |
| 12      | 5         | 5.21%   |
| 23      | 3         | 3.13%   |
| 29      | 2         | 2.08%   |
| 20      | 2         | 2.08%   |
| 64      | 1         | 1.04%   |
| 57      | 1         | 1.04%   |
| 54      | 1         | 1.04%   |
| 42      | 1         | 1.04%   |
| 31      | 1         | 1.04%   |
| 22      | 1         | 1.04%   |
| 19      | 1         | 1.04%   |
| 18      | 1         | 1.04%   |
| 17      | 1         | 1.04%   |
| 14      | 1         | 1.04%   |
| 10      | 1         | 1.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 38.95%  |
| 501-600     | 18        | 18.95%  |
| 201-300     | 11        | 11.58%  |
| Unknown     | 9         | 9.47%   |
| 401-500     | 8         | 8.42%   |
| 601-700     | 5         | 5.26%   |
| 351-400     | 3         | 3.16%   |
| 1001-1500   | 3         | 3.16%   |
| 901-1000    | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 65        | 74.71%  |
| 16/10   | 9         | 10.34%  |
| Unknown | 8         | 9.2%    |
| 21/9    | 2         | 2.3%    |
| 6/5     | 1         | 1.15%   |
| 4/3     | 1         | 1.15%   |
| 11/10   | 1         | 1.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 17        | 17.71%  |
| 81-90          | 16        | 16.67%  |
| 91-100         | 16        | 16.67%  |
| 301-350        | 10        | 10.42%  |
| Unknown        | 9         | 9.38%   |
| 101-110        | 7         | 7.29%   |
| 61-70          | 5         | 5.21%   |
| 71-80          | 4         | 4.17%   |
| 151-200        | 4         | 4.17%   |
| More than 1000 | 3         | 3.13%   |
| 351-500        | 1         | 1.04%   |
| 41-50          | 1         | 1.04%   |
| 251-300        | 1         | 1.04%   |
| 131-140        | 1         | 1.04%   |
| 501-1000       | 1         | 1.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 29        | 31.18%  |
| 121-160       | 24        | 25.81%  |
| 101-120       | 19        | 20.43%  |
| Unknown       | 9         | 9.68%   |
| 161-240       | 8         | 8.6%    |
| More than 240 | 3         | 3.23%   |
| 1-50          | 1         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 75        | 53.96%  |
| 0     | 52        | 37.41%  |
| 2     | 11        | 7.91%   |
| 3     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 80        | 41.03%  |
| Realtek Semiconductor    | 66        | 33.85%  |
| Qualcomm Atheros         | 19        | 9.74%   |
| Broadcom                 | 9         | 4.62%   |
| Xiaomi                   | 3         | 1.54%   |
| Ralink Technology        | 3         | 1.54%   |
| Marvell Technology Group | 3         | 1.54%   |
| Samsung Electronics      | 2         | 1.03%   |
| TP-Link                  | 1         | 0.51%   |
| Qualcomm                 | 1         | 0.51%   |
| Nvidia                   | 1         | 0.51%   |
| MediaTek                 | 1         | 0.51%   |
| LG Electronics           | 1         | 0.51%   |
| Huawei Technologies      | 1         | 0.51%   |
| HMD Global               | 1         | 0.51%   |
| Google                   | 1         | 0.51%   |
| D-Link System            | 1         | 0.51%   |
| Arduino SA               | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 42        | 17.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 3.77%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.35%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.09%   |
| Intel I211 Gigabit Network Connection                                   | 5         | 2.09%   |
| Intel Ethernet Controller I225-V                                        | 5         | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.09%   |
| Intel 82574L Gigabit Network Connection                                 | 5         | 2.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.26%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.26%   |
| Intel Wireless 7265                                                     | 3         | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.26%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 1.26%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 2         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.84%   |
| Realtek Realtek Bluetooth Adapter                                       | 2         | 0.84%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                        | 2         | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.84%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.84%   |
| Intel Wireless 8260                                                     | 2         | 0.84%   |
| Intel Wireless 7260                                                     | 2         | 0.84%   |
| Intel I350 Gigabit Network Connection                                   | 2         | 0.84%   |
| Intel I210 Gigabit Network Connection                                   | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.84%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.84%   |
| Intel Ethernet Connection (10) I219-V                                   | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.84%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 2         | 0.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.42%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.42%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.42%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 1         | 0.42%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.42%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.42%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.42%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.42%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.42%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.42%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 0.42%   |
| Qualcomm ALCATEL Composite RNDIS Interface                              | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 51.04%  |
| Qualcomm Atheros      | 19        | 19.79%  |
| Realtek Semiconductor | 16        | 16.67%  |
| Broadcom              | 7         | 7.29%   |
| Ralink Technology     | 3         | 3.13%   |
| TP-Link               | 1         | 1.04%   |
| MediaTek              | 1         | 1.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 8         | 8.33%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 6.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 5.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 5.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 3.13%   |
| Intel Wireless 7265                                                     | 3         | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 2.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 2.08%   |
| Realtek Realtek Bluetooth Adapter                                       | 2         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.08%   |
| Intel Wireless-AC 9260                                                  | 2         | 2.08%   |
| Intel Wireless 8260                                                     | 2         | 2.08%   |
| Intel Wireless 7260                                                     | 2         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 2         | 2.08%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.04%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.04%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.04%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 1.04%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.04%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.04%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.04%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express) | 1         | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.04%   |
| Intel Wireless 3160                                                     | 1         | 1.04%   |
| Intel WiFi Link 5100                                                    | 1         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.04%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.04%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.04%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 44.62%  |
| Intel                    | 54        | 41.54%  |
| Broadcom                 | 4         | 3.08%   |
| Xiaomi                   | 3         | 2.31%   |
| Marvell Technology Group | 3         | 2.31%   |
| Samsung Electronics      | 2         | 1.54%   |
| Qualcomm Atheros         | 1         | 0.77%   |
| Qualcomm                 | 1         | 0.77%   |
| Nvidia                   | 1         | 0.77%   |
| HMD Global               | 1         | 0.77%   |
| Google                   | 1         | 0.77%   |
| D-Link System            | 1         | 0.77%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 30%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 6.43%   |
| Intel I211 Gigabit Network Connection                             | 5         | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.57%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.14%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.14%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 2.14%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.43%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 1.43%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.43%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.43%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.43%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.71%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.71%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.71%   |
| Intel Ethernet Controller X550                                    | 1         | 0.71%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.71%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 0.71%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1         | 0.71%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.71%   |
| Intel 82575GB Gigabit Network Connection                          | 1         | 0.71%   |
| Intel 82575EB Gigabit Network Connection                          | 1         | 0.71%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1         | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.71%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 0.71%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.71%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.71%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.71%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 117       | 56.25%  |
| WiFi     | 88        | 42.31%  |
| Modem    | 3         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 67.46%  |
| WiFi     | 41        | 32.54%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 51.08%  |
| 1     | 49        | 35.25%  |
| 3     | 7         | 5.04%   |
| 0     | 7         | 5.04%   |
| 5     | 2         | 1.44%   |
| 7     | 1         | 0.72%   |
| 6     | 1         | 0.72%   |
| 4     | 1         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 82.86%  |
| Yes  | 24        | 17.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 59.32%  |
| Realtek Semiconductor           | 5         | 8.47%   |
| Qualcomm Atheros Communications | 4         | 6.78%   |
| Dell                            | 4         | 6.78%   |
| IMC Networks                    | 3         | 5.08%   |
| Foxconn / Hon Hai               | 2         | 3.39%   |
| Cambridge Silicon Radio         | 2         | 3.39%   |
| Apple                           | 2         | 3.39%   |
| Broadcom                        | 1         | 1.69%   |
| ASUSTek Computer                | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 12        | 20.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 13.56%  |
| Intel AX201 Bluetooth                                       | 8         | 13.56%  |
| Intel AX200 Bluetooth                                       | 5         | 8.47%   |
| Realtek  Bluetooth Adapter                                  | 3         | 5.08%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 3.39%   |
| Dell DW375 Bluetooth Module                                 | 2         | 3.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.39%   |
| Apple Bluetooth Host Controller                             | 2         | 3.39%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.69%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.69%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.69%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.69%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.69%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.69%   |
| IMC Networks Bluetooth Radio                                | 1         | 1.69%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.69%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.69%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.69%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 1.69%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.69%   |
| ASUS Bluetooth USB module                                   | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 94        | 59.12%  |
| AMD                         | 28        | 17.61%  |
| Nvidia                      | 24        | 15.09%  |
| Plantronics                 | 2         | 1.26%   |
| FiiO Electronics Technology | 2         | 1.26%   |
| XMOS                        | 1         | 0.63%   |
| SteelSeries ApS             | 1         | 0.63%   |
| Sony                        | 1         | 0.63%   |
| Realtek Semiconductor       | 1         | 0.63%   |
| Razer USA                   | 1         | 0.63%   |
| Lenovo                      | 1         | 0.63%   |
| Kingston Technology         | 1         | 0.63%   |
| Ensoniq                     | 1         | 0.63%   |
| Cambridge Silicon Radio     | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 12        | 6.38%   |
| AMD Family 17h/19h HD Audio Controller                                            | 11        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10        | 5.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9         | 4.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8         | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 8         | 4.26%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 5         | 2.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 2.66%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 4         | 2.13%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 1.6%    |
| Nvidia GP106 High Definition Audio Controller                                     | 3         | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3         | 1.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 3         | 1.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 1.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3         | 1.6%    |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 1.6%    |
| Plantronics Plantronics Blackwire 315.1                                           | 2         | 1.06%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2         | 1.06%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                         | 2         | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 1.06%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.06%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 1.06%   |
| FiiO Electronics Technology FiiO USB DAC-E10                                      | 2         | 1.06%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2         | 1.06%   |
| AMD FCH Azalia Controller                                                         | 2         | 1.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.06%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                         | 1         | 0.53%   |
| SteelSeries ApS SteelSeries Siberia 350                                           | 1         | 0.53%   |
| Sony UAB-80                                                                       | 1         | 0.53%   |
| Realtek Semiconductor Realtek USB Audio                                           | 1         | 0.53%   |
| Razer USA Razer BlackShark V2 Pro Razer BlackShark V2 Pro                         | 1         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                                | 1         | 0.53%   |
| Nvidia MCP61 High Definition Audio                                                | 1         | 0.53%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.53%   |
| Lenovo Realtek USB Audio                                                          | 1         | 0.53%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1         | 0.53%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 0.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1         | 0.53%   |
| Intel Crystal Well HD Audio Controller                                            | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1         | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 0.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 0.53%   |
| Ensoniq 5880B / Creative Labs CT5880                                              | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 33        | 21.29%  |
| Samsung Electronics          | 28        | 18.06%  |
| Crucial                      | 16        | 10.32%  |
| Micron Technology            | 14        | 9.03%   |
| Kingston                     | 13        | 8.39%   |
| Corsair                      | 11        | 7.1%    |
| Unknown                      | 6         | 3.87%   |
| G.Skill                      | 5         | 3.23%   |
| Unknown                      | 5         | 3.23%   |
| Unknown (ABCD)               | 3         | 1.94%   |
| Elpida                       | 3         | 1.94%   |
| A-DATA Technology            | 3         | 1.94%   |
| Transcend                    | 2         | 1.29%   |
| Ramaxel Technology           | 2         | 1.29%   |
| KomputerBay                  | 2         | 1.29%   |
| Qimonda                      | 1         | 0.65%   |
| PNY                          | 1         | 0.65%   |
| Patriot Memory (PDP Systems) | 1         | 0.65%   |
| Patriot                      | 1         | 0.65%   |
| Nanya Technology             | 1         | 0.65%   |
| Kingmax Semiconductor        | 1         | 0.65%   |
| Kingmax                      | 1         | 0.65%   |
| Hewlett-Packard              | 1         | 0.65%   |
| Apacer                       | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 5         | 3.05%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 2         | 1.22%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                             | 2         | 1.22%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 2         | 1.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.22%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 1.22%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 1.22%   |
| KomputerBay RAM KB_8G_D3_1333_C9 8GB SODIMM DDR3 1334MT/s                 | 2         | 1.22%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                                   | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM                                               | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s         | 1         | 0.61%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.61%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s                       | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                              | 1         | 0.61%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s                     | 1         | 0.61%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMA84GR7DJR4N-XN 32GB DIMM DDR4 3200MT/s                     | 1         | 0.61%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.61%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.61%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.61%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                      | 1         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.61%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s                    | 1         | 0.61%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s                | 1         | 0.61%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 0.61%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 0.61%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                                 | 1         | 0.61%   |
| Samsung RAM Module 1GB SODIMM DDR3 1333MT/s                               | 1         | 0.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.61%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.61%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.61%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.61%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.61%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s               | 1         | 0.61%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s                     | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 48.51%  |
| DDR3    | 51        | 38.06%  |
| DDR2    | 8         | 5.97%   |
| LPDDR4  | 4         | 2.99%   |
| Unknown | 3         | 2.24%   |
| LPDDR3  | 2         | 1.49%   |
| DDR     | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 57.14%  |
| DIMM         | 53        | 39.85%  |
| Row Of Chips | 3         | 2.26%   |
| Chip         | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 60        | 41.67%  |
| 4096  | 38        | 26.39%  |
| 16384 | 21        | 14.58%  |
| 2048  | 16        | 11.11%  |
| 32768 | 7         | 4.86%   |
| 1024  | 2         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 21.99%  |
| 3200    | 22        | 15.6%   |
| 2400    | 17        | 12.06%  |
| 2133    | 15        | 10.64%  |
| 2667    | 13        | 9.22%   |
| 1333    | 11        | 7.8%    |
| 1334    | 6         | 4.26%   |
| 2666    | 4         | 2.84%   |
| 800     | 4         | 2.84%   |
| 667     | 3         | 2.13%   |
| 3600    | 2         | 1.42%   |
| 1066    | 2         | 1.42%   |
| 975     | 2         | 1.42%   |
| Unknown | 2         | 1.42%   |
| 4266    | 1         | 0.71%   |
| 3400    | 1         | 0.71%   |
| 2933    | 1         | 0.71%   |
| 1866    | 1         | 0.71%   |
| 1067    | 1         | 0.71%   |
| 933     | 1         | 0.71%   |
| 533     | 1         | 0.71%   |

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
| Chicony Electronics           | 14        | 26.92%  |
| IMC Networks                  | 9         | 17.31%  |
| Microdia                      | 6         | 11.54%  |
| Sunplus Innovation Technology | 5         | 9.62%   |
| Acer                          | 5         | 9.62%   |
| Realtek Semiconductor         | 2         | 3.85%   |
| Logitech                      | 2         | 3.85%   |
| Z-Star Microelectronics       | 1         | 1.92%   |
| SHENZHEN EMEET TECHNOLOGY     | 1         | 1.92%   |
| Ricoh                         | 1         | 1.92%   |
| Quanta                        | 1         | 1.92%   |
| OmniVision Technologies       | 1         | 1.92%   |
| Intel                         | 1         | 1.92%   |
| Genesys Logic                 | 1         | 1.92%   |
| DigiTech                      | 1         | 1.92%   |
| Alcor Micro                   | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 4         | 7.55%   |
| Acer Integrated Camera                         | 4         | 7.55%   |
| Microdia Integrated_Webcam_HD                  | 3         | 5.66%   |
| IMC Networks EasyCamera                        | 3         | 5.66%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 2         | 3.77%   |
| Microdia Integrated Webcam                     | 2         | 3.77%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 3.77%   |
| Chicony Lenovo Integrated Camera (0.3MP)       | 2         | 3.77%   |
| Chicony HP HD Camera                           | 2         | 3.77%   |
| Z-Star Lenovo USB2.0 UVC Camera                | 1         | 1.89%   |
| Sunplus Laptop Integrated Webcam HD            | 1         | 1.89%   |
| Sunplus Integrated_Webcam_HD                   | 1         | 1.89%   |
| Sunplus HD WebCam                              | 1         | 1.89%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1         | 1.89%   |
| Ricoh Integrated Webcam                        | 1         | 1.89%   |
| Realtek Integrated_Webcam_HD                   | 1         | 1.89%   |
| Realtek Integrated Webcam HD                   | 1         | 1.89%   |
| Quanta VGA WebCam                              | 1         | 1.89%   |
| OmniVision Monitor Webcam                      | 1         | 1.89%   |
| Microdia JOYACCESS JA-Webcam                   | 1         | 1.89%   |
| Logitech Webcam C270                           | 1         | 1.89%   |
| Logitech HD Pro Webcam C920                    | 1         | 1.89%   |
| Intel RealSense 3D Camera (Front F200)         | 1         | 1.89%   |
| IMC Networks Integrated Webcam                 | 1         | 1.89%   |
| IMC Networks HP TrueVision HD Camera           | 1         | 1.89%   |
| Genesys Logic Camera                           | 1         | 1.89%   |
| DigiTech WebCam SCB-0350M                      | 1         | 1.89%   |
| Chicony USB2.0 VGA UVC WebCam                  | 1         | 1.89%   |
| Chicony USB2.0 HD UVC WebCam                   | 1         | 1.89%   |
| Chicony USB 2.0 Camera                         | 1         | 1.89%   |
| Chicony LG Camera                              | 1         | 1.89%   |
| Chicony Chicony USB2.0 Camera                  | 1         | 1.89%   |
| Chicony Camera                                 | 1         | 1.89%   |
| Alcor Micro USB 2.0 Camera                     | 1         | 1.89%   |
| Acer ThinkPad P50 Integrated Camera            | 1         | 1.89%   |
| Acer SunplusIT Integrated Camera               | 1         | 1.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 4         | 57.14%  |
| Validity Sensors           | 2         | 28.57%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 28.57%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                           | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 14.29%  |
| Synaptics product 0x00be                                  | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 14.29%  |

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
| 1     | 55        | 39.57%  |
| 2     | 34        | 24.46%  |
| 0     | 27        | 19.42%  |
| 3     | 17        | 12.23%  |
| 4     | 5         | 3.6%    |
| 5     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 95        | 53.98%  |
| Bluetooth                | 29        | 16.48%  |
| Net/wireless             | 16        | 9.09%   |
| Firewire controller      | 11        | 6.25%   |
| Card reader              | 11        | 6.25%   |
| Fingerprint reader       | 6         | 3.41%   |
| Net/ethernet             | 4         | 2.27%   |
| Storage                  | 2         | 1.14%   |
| Sound                    | 1         | 0.57%   |
| Network                  | 1         | 0.57%   |

