helloSystem 0.7.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.7.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.7.0/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 269

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0D6H9T A00                  | Desktop     | [7daab72741](https://bsd-hardware.info/?probe=7daab72741) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | Notebook    | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [49627775f3](https://bsd-hardware.info/?probe=49627775f3) | Mar 31, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [11664cd9d7](https://bsd-hardware.info/?probe=11664cd9d7) | Mar 30, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [6a615f6be5](https://bsd-hardware.info/?probe=6a615f6be5) | Mar 30, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0906d116eb](https://bsd-hardware.info/?probe=0906d116eb) | Mar 29, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [89593af061](https://bsd-hardware.info/?probe=89593af061) | Mar 29, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [553f2beb91](https://bsd-hardware.info/?probe=553f2beb91) | Mar 27, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [47ef9ef91a](https://bsd-hardware.info/?probe=47ef9ef91a) | Mar 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8c89faeb24](https://bsd-hardware.info/?probe=8c89faeb24) | Mar 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ae1fa6cbce](https://bsd-hardware.info/?probe=ae1fa6cbce) | Mar 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [70d10ce47c](https://bsd-hardware.info/?probe=70d10ce47c) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [99d079bd5a](https://bsd-hardware.info/?probe=99d079bd5a) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c76aa38baf](https://bsd-hardware.info/?probe=c76aa38baf) | Mar 24, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [9b3dac520a](https://bsd-hardware.info/?probe=9b3dac520a) | Mar 24, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| ECS           | G41T-M9                     | Desktop     | [9ef50c47da](https://bsd-hardware.info/?probe=9ef50c47da) | Mar 21, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | Notebook    | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [2727a8e439](https://bsd-hardware.info/?probe=2727a8e439) | Mar 15, 2022 |
| HASEE Comp... | CW35S                       | Notebook    | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | Notebook    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| Lenovo        | IdeaCentre B545 10100       | Desktop     | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| Acer          | Aspire E1-421               | Notebook    | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [b4234170e8](https://bsd-hardware.info/?probe=b4234170e8) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | Notebook    | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Koloe         | X58                         | Desktop     | [58e098eca2](https://bsd-hardware.info/?probe=58e098eca2) | Mar 09, 2022 |
| HP            | 8054                        | Desktop     | [86b6b8373c](https://bsd-hardware.info/?probe=86b6b8373c) | Mar 08, 2022 |
| HP            | 8054                        | Desktop     | [00078554d2](https://bsd-hardware.info/?probe=00078554d2) | Mar 08, 2022 |
| Koloe         | X58                         | Desktop     | [c501dfa5c8](https://bsd-hardware.info/?probe=c501dfa5c8) | Mar 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [8b51036856](https://bsd-hardware.info/?probe=8b51036856) | Mar 06, 2022 |
| HP            | 1905                        | Desktop     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [78f79fab6f](https://bsd-hardware.info/?probe=78f79fab6f) | Feb 28, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Dell          | 0KV62T A00                  | Desktop     | [0541a207c7](https://bsd-hardware.info/?probe=0541a207c7) | Feb 28, 2022 |
| HP            | 1905                        | Desktop     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| Acer          | V5-131                      | Notebook    | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [a2df68e1d1](https://bsd-hardware.info/?probe=a2df68e1d1) | Feb 26, 2022 |
| Intel         | H81                         | Desktop     | [04d2739bdc](https://bsd-hardware.info/?probe=04d2739bdc) | Feb 25, 2022 |
| Intel         | DCP847SKE G80890-107        | Desktop     | [f9d33f1ab1](https://bsd-hardware.info/?probe=f9d33f1ab1) | Feb 23, 2022 |
| Medion        | H61H2-LM3                   | Desktop     | [beb12f2884](https://bsd-hardware.info/?probe=beb12f2884) | Feb 23, 2022 |
| ASRock        | H81M-DG4                    | Desktop     | [e20db6ad83](https://bsd-hardware.info/?probe=e20db6ad83) | Feb 23, 2022 |
| HP            | 1998                        | Desktop     | [485d417a2e](https://bsd-hardware.info/?probe=485d417a2e) | Feb 23, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [feb7882341](https://bsd-hardware.info/?probe=feb7882341) | Feb 22, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | Notebook    | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [1e6ff84e5d](https://bsd-hardware.info/?probe=1e6ff84e5d) | Feb 21, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | Notebook    | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Gigabyte      | P41T-D3                     | Desktop     | [e5417931a7](https://bsd-hardware.info/?probe=e5417931a7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | Notebook    | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | Notebook    | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3a72227408](https://bsd-hardware.info/?probe=3a72227408) | Feb 16, 2022 |
| Gigabyte      | C246M-WU4-CF                | Desktop     | [4b6c6d8bde](https://bsd-hardware.info/?probe=4b6c6d8bde) | Feb 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [257e13f206](https://bsd-hardware.info/?probe=257e13f206) | Feb 12, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [abf34bbc7e](https://bsd-hardware.info/?probe=abf34bbc7e) | Feb 12, 2022 |
| ASRock        | H61M/U3S3                   | Desktop     | [34dac4c0cd](https://bsd-hardware.info/?probe=34dac4c0cd) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Intel         | X58                         | Desktop     | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [b1931633be](https://bsd-hardware.info/?probe=b1931633be) | Feb 09, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f9c1e787a9](https://bsd-hardware.info/?probe=f9c1e787a9) | Feb 09, 2022 |
| MSI           | B75A-G43                    | Desktop     | [8e445eb2d4](https://bsd-hardware.info/?probe=8e445eb2d4) | Feb 08, 2022 |
| Acer          | Aspire E5-511G              | Notebook    | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | Notebook    | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| ASUSTek       | P6-P8H61E                   | Desktop     | [e838981914](https://bsd-hardware.info/?probe=e838981914) | Feb 06, 2022 |
| Dell          | Latitude D630               | Notebook    | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | Notebook    | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e5043f0af4](https://bsd-hardware.info/?probe=e5043f0af4) | Feb 04, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [bf63607cd6](https://bsd-hardware.info/?probe=bf63607cd6) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [64d4fb9b97](https://bsd-hardware.info/?probe=64d4fb9b97) | Feb 02, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | Notebook    | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [ee05643521](https://bsd-hardware.info/?probe=ee05643521) | Feb 01, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [5999e0ebfb](https://bsd-hardware.info/?probe=5999e0ebfb) | Jan 31, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | Notebook    | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Intel         | H81                         | Desktop     | [c2f3025900](https://bsd-hardware.info/?probe=c2f3025900) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | Notebook    | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [e34b6118a2](https://bsd-hardware.info/?probe=e34b6118a2) | Jan 30, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Intel         | DH77EB AAG39073-400         | Desktop     | [bfe6ef301b](https://bsd-hardware.info/?probe=bfe6ef301b) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [a9d799ca71](https://bsd-hardware.info/?probe=a9d799ca71) | Jan 27, 2022 |
| Dell          | Latitude 7280               | Notebook    | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [2506316700](https://bsd-hardware.info/?probe=2506316700) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8edf072b67](https://bsd-hardware.info/?probe=8edf072b67) | Jan 25, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [df08e2e8f0](https://bsd-hardware.info/?probe=df08e2e8f0) | Jan 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| HP            | 1998                        | Desktop     | [b59dbcdc9c](https://bsd-hardware.info/?probe=b59dbcdc9c) | Jan 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | Notebook    | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [670e41ed41](https://bsd-hardware.info/?probe=670e41ed41) | Jan 21, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [04abd226f3](https://bsd-hardware.info/?probe=04abd226f3) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [a780a7bab2](https://bsd-hardware.info/?probe=a780a7bab2) | Jan 18, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Acer          | V5-131                      | Notebook    | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
| Gateway       | NE56R                       | Notebook    | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9cd2758a5f](https://bsd-hardware.info/?probe=9cd2758a5f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | Notebook    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | Notebook    | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [48e9447b37](https://bsd-hardware.info/?probe=48e9447b37) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | Notebook    | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [459bb6486d](https://bsd-hardware.info/?probe=459bb6486d) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| HP            | 8169                        | Desktop     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Dell          | Latitude E6530              | Notebook    | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | Notebook    | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| ASUSTek       | GA35DX                      | Desktop     | [eccb947ae4](https://bsd-hardware.info/?probe=eccb947ae4) | Jan 05, 2022 |
| Notebook      | N15_17RD                    | Notebook    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| Unknown       | G31T-M7                     | Desktop     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Dell          | Latitude 7380               | Notebook    | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4979175779](https://bsd-hardware.info/?probe=4979175779) | Jan 01, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | Notebook    | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a671e3eb04](https://bsd-hardware.info/?probe=a671e3eb04) | Dec 31, 2021 |
| Dell          | Latitude E6540              | Notebook    | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo        | ThinkPad E580 20KS005BRI    | Notebook    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [15211db056](https://bsd-hardware.info/?probe=15211db056) | Dec 28, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Dell          | 0200DY A01                  | Desktop     | [fb37dcbb93](https://bsd-hardware.info/?probe=fb37dcbb93) | Dec 28, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Dell          | 0H9KW5 A00                  | Desktop     | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [ea002bb42a](https://bsd-hardware.info/?probe=ea002bb42a) | Dec 24, 2021 |
| Acer          | TravelMate 5760G            | Notebook    | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8ac48ba9c3](https://bsd-hardware.info/?probe=8ac48ba9c3) | Dec 23, 2021 |
| Lenovo        | ThinkPad SL510 2847R96      | Notebook    | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo        | ThinkPad T410 2537EA8       | Notebook    | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [936afa4de3](https://bsd-hardware.info/?probe=936afa4de3) | Dec 21, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42599b554e](https://bsd-hardware.info/?probe=42599b554e) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73076dd5de](https://bsd-hardware.info/?probe=73076dd5de) | Dec 21, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [a490614a39](https://bsd-hardware.info/?probe=a490614a39) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | Desktop     | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | Notebook    | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | Notebook    | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [7e8f3cf783](https://bsd-hardware.info/?probe=7e8f3cf783) | Dec 20, 2021 |
| ASUSTek       | Q170M-C                     | Desktop     | [7f9e35a31c](https://bsd-hardware.info/?probe=7f9e35a31c) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | Desktop     | [3ce808c135](https://bsd-hardware.info/?probe=3ce808c135) | Dec 20, 2021 |
| Dell          | 0TDG4V A00                  | Desktop     | [5292ad64ef](https://bsd-hardware.info/?probe=5292ad64ef) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [3c71a8ba4e](https://bsd-hardware.info/?probe=3c71a8ba4e) | Dec 20, 2021 |
| Dell          | Latitude E5470              | Notebook    | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Apple         | Mac-F2218EA9                | All in one  | [510b7cb091](https://bsd-hardware.info/?probe=510b7cb091) | Dec 19, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [73853f1fc2](https://bsd-hardware.info/?probe=73853f1fc2) | Dec 19, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7daf32eb4f](https://bsd-hardware.info/?probe=7daf32eb4f) | Dec 17, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [759ce775c9](https://bsd-hardware.info/?probe=759ce775c9) | Dec 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [32d20b9b8e](https://bsd-hardware.info/?probe=32d20b9b8e) | Dec 14, 2021 |
| HP            | ZBook Studio G4             | Notebook    | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [aea4a33dee](https://bsd-hardware.info/?probe=aea4a33dee) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6a1100cfdb](https://bsd-hardware.info/?probe=6a1100cfdb) | Dec 11, 2021 |
| Acer          | RevoOne RL85                | Desktop     | [a1e32de7da](https://bsd-hardware.info/?probe=a1e32de7da) | Dec 10, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b900b364f6](https://bsd-hardware.info/?probe=b900b364f6) | Dec 10, 2021 |
| Dell          | 0YF8P5 A00                  | Desktop     | [0f03a66475](https://bsd-hardware.info/?probe=0f03a66475) | Dec 09, 2021 |
| Dell          | 0YF8P5 A00                  | Desktop     | [83b36f7c3d](https://bsd-hardware.info/?probe=83b36f7c3d) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Apple         | MacBookAir1,1               | Notebook    | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8cfe11fe93](https://bsd-hardware.info/?probe=8cfe11fe93) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [376e006a40](https://bsd-hardware.info/?probe=376e006a40) | Nov 30, 2021 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [dd357bcaa5](https://bsd-hardware.info/?probe=dd357bcaa5) | Nov 30, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| HP            | 843B                        | Desktop     | [a8ac0e9efb](https://bsd-hardware.info/?probe=a8ac0e9efb) | Nov 29, 2021 |
| Toshiba       | Satellite S55t-B            | Notebook    | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| HP            | 1825                        | Desktop     | [32f07d2ba3](https://bsd-hardware.info/?probe=32f07d2ba3) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4cd5e5166a](https://bsd-hardware.info/?probe=4cd5e5166a) | Nov 27, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| ASRock        | 775i945GZ                   | Desktop     | [16fc4ee10d](https://bsd-hardware.info/?probe=16fc4ee10d) | Nov 26, 2021 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| Toshiba       | Satellite C640              | Notebook    | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | Notebook    | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | Notebook    | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| HP            | 844C                        | Desktop     | [fb7d8eaf5d](https://bsd-hardware.info/?probe=fb7d8eaf5d) | Nov 06, 2021 |
| Unknown       | X79                         | Desktop     | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | Notebook    | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 209       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 207       | 99.04%  |
| GNOME        | 2         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 209       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 209       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 200       | 95.69%  |
| de_DE | 4         | 1.91%   |
| C     | 2         | 0.96%   |
| uk_UA | 1         | 0.48%   |
| fr_FR | 1         | 0.48%   |
| es_ES | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 202       | 96.65%  |
| BIOS | 7         | 3.35%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 126       | 58.88%  |
| Zfs    | 88        | 41.12%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 204       | 97.61%  |
| MBR  | 5         | 2.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 37        | 17.7%   |
| Lenovo              | 35        | 16.75%  |
| Dell                | 22        | 10.53%  |
| Hewlett-Packard     | 21        | 10.05%  |
| Gigabyte Technology | 18        | 8.61%   |
| Apple               | 14        | 6.7%    |
| Acer                | 12        | 5.74%   |
| Intel               | 10        | 4.78%   |
| ASRock              | 10        | 4.78%   |
| MSI                 | 5         | 2.39%   |
| Toshiba             | 4         | 1.91%   |
| Samsung Electronics | 3         | 1.44%   |
| Pegatron            | 3         | 1.44%   |
| Unknown             | 2         | 0.96%   |
| TWINHEAD            | 1         | 0.48%   |
| TUXEDO              | 1         | 0.48%   |
| Quanta              | 1         | 0.48%   |
| Packard Bell        | 1         | 0.48%   |
| Notebook            | 1         | 0.48%   |
| Medion              | 1         | 0.48%   |
| Koloe               | 1         | 0.48%   |
| Itautec             | 1         | 0.48%   |
| HASEE Computer      | 1         | 0.48%   |
| Gateway             | 1         | 0.48%   |
| Fujitsu             | 1         | 0.48%   |
| ECS                 | 1         | 0.48%   |
| Acidanthera         | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Apple iMac9,1                            | 4         | 1.91%   |
| Dell Latitude E5470                      | 2         | 0.96%   |
| ASUS TUF GAMING X570-PLUS                | 2         | 0.96%   |
| ASUS P8Z77-V LX                          | 2         | 0.96%   |
| Apple MacBook4,1                         | 2         | 0.96%   |
| Acer V5-131                              | 2         | 0.96%   |
| Unknown                                  | 2         | 0.96%   |
| TWINHEAD U12CT                           | 1         | 0.48%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.48%   |
| Toshiba Satellite S55t-B                 | 1         | 0.48%   |
| Toshiba Satellite L550                   | 1         | 0.48%   |
| Toshiba Satellite C640                   | 1         | 0.48%   |
| Toshiba Satellite C50-B                  | 1         | 0.48%   |
| Samsung N150P/N210P/N220P                | 1         | 0.48%   |
| Samsung N100                             | 1         | 0.48%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.48%   |
| Quanta 120-1135                          | 1         | 0.48%   |
| Pegatron IPM41-D3                        | 1         | 0.48%   |
| Pegatron Compaq 505B Microtower PC       | 1         | 0.48%   |
| Pegatron AY627AA-ABA a4313w              | 1         | 0.48%   |
| Packard Bell EasyNote TE69HW             | 1         | 0.48%   |
| Notebook N15_17RD                        | 1         | 0.48%   |
| MSI MS-7D25                              | 1         | 0.48%   |
| MSI MS-7B86                              | 1         | 0.48%   |
| MSI MS-7A33                              | 1         | 0.48%   |
| MSI MS-7816                              | 1         | 0.48%   |
| MSI MS-7758                              | 1         | 0.48%   |
| Medion H61H2-LM3                         | 1         | 0.48%   |
| Lenovo Z50-70 20354                      | 1         | 0.48%   |
| Lenovo V310-14IKB 80T2                   | 1         | 0.48%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01    | 1         | 0.48%   |
| Lenovo ThinkPad X250 20CLS1WP01          | 1         | 0.48%   |
| Lenovo ThinkPad X240 20AMS2QDOC          | 1         | 0.48%   |
| Lenovo ThinkPad X220 Tablet 4298B65      | 1         | 0.48%   |
| Lenovo ThinkPad X220 Tablet 42962WU      | 1         | 0.48%   |
| Lenovo ThinkPad X220 4293B43             | 1         | 0.48%   |
| Lenovo ThinkPad X220 4293AF4             | 1         | 0.48%   |
| Lenovo ThinkPad X220 4291H77             | 1         | 0.48%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.48%   |
| Lenovo ThinkPad T61 766301U              | 1         | 0.48%   |
| Lenovo ThinkPad T60 1951FEG              | 1         | 0.48%   |
| Lenovo ThinkPad T510 4384AJ6             | 1         | 0.48%   |
| Lenovo ThinkPad T460 20FMS75800          | 1         | 0.48%   |
| Lenovo ThinkPad T440p 20AWS3RH00         | 1         | 0.48%   |
| Lenovo ThinkPad T440 20B7000PHV          | 1         | 0.48%   |
| Lenovo ThinkPad T430 2349AK1             | 1         | 0.48%   |
| Lenovo ThinkPad T410 2537EA8             | 1         | 0.48%   |
| Lenovo ThinkPad T410 2522E38             | 1         | 0.48%   |
| Lenovo ThinkPad SL510 2847R96            | 1         | 0.48%   |
| Lenovo ThinkPad R61 8935WCS              | 1         | 0.48%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 0.48%   |
| Lenovo ThinkPad L440 20ASS0FP00          | 1         | 0.48%   |
| Lenovo ThinkPad E580 20KS005BRI          | 1         | 0.48%   |
| Lenovo ThinkPad E15 20RD0011MX           | 1         | 0.48%   |
| Lenovo ThinkCentre M720q 10T7005MRU      | 1         | 0.48%   |
| Lenovo ThinkBook 14 G2 ARE 20VF          | 1         | 0.48%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 0.48%   |
| Lenovo IdeaPad N585                      | 1         | 0.48%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 1         | 0.48%   |
| Lenovo IdeaPad 510-15IKB 80SV            | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 24        | 11.48%  |
| Dell Latitude           | 9         | 4.31%   |
| Acer Aspire             | 7         | 3.35%   |
| ASUS ROG                | 5         | 2.39%   |
| ASUS PRIME              | 5         | 2.39%   |
| Toshiba Satellite       | 4         | 1.91%   |
| Lenovo IdeaPad          | 4         | 1.91%   |
| Dell OptiPlex           | 4         | 1.91%   |
| Dell Inspiron           | 4         | 1.91%   |
| Apple iMac9             | 4         | 1.91%   |
| HP Pavilion             | 3         | 1.44%   |
| HP Laptop               | 3         | 1.44%   |
| HP EliteDesk            | 3         | 1.44%   |
| HP EliteBook            | 3         | 1.44%   |
| Dell Vostro             | 2         | 0.96%   |
| ASUS TUF                | 2         | 0.96%   |
| ASUS P8Z77-V            | 2         | 0.96%   |
| Apple MacBook4          | 2         | 0.96%   |
| Acer V5-131             | 2         | 0.96%   |
| Unknown                 | 2         | 0.96%   |
| TWINHEAD U12CT          | 1         | 0.48%   |
| TUXEDO InfinityBook13V3 | 1         | 0.48%   |
| Samsung N150P           | 1         | 0.48%   |
| Samsung N100            | 1         | 0.48%   |
| Samsung 305E4A          | 1         | 0.48%   |
| Quanta 120-1135         | 1         | 0.48%   |
| Pegatron IPM41-D3       | 1         | 0.48%   |
| Pegatron Compaq         | 1         | 0.48%   |
| Pegatron AY627AA-ABA    | 1         | 0.48%   |
| Packard Bell EasyNote   | 1         | 0.48%   |
| Notebook N15            | 1         | 0.48%   |
| MSI MS-7D25             | 1         | 0.48%   |
| MSI MS-7B86             | 1         | 0.48%   |
| MSI MS-7A33             | 1         | 0.48%   |
| MSI MS-7816             | 1         | 0.48%   |
| MSI MS-7758             | 1         | 0.48%   |
| Medion H61H2-LM3        | 1         | 0.48%   |
| Lenovo Z50-70           | 1         | 0.48%   |
| Lenovo V310-14IKB       | 1         | 0.48%   |
| Lenovo ThinkCentre      | 1         | 0.48%   |
| Lenovo ThinkBook        | 1         | 0.48%   |
| Lenovo Legion           | 1         | 0.48%   |
| Lenovo IdeaCentre       | 1         | 0.48%   |
| Lenovo E31-80           | 1         | 0.48%   |
| Koloe Thurley           | 1         | 0.48%   |
| Itautec Infoway         | 1         | 0.48%   |
| Intel X58               | 1         | 0.48%   |
| Intel NUC8i3BEH         | 1         | 0.48%   |
| Intel NUC7i3BNK         | 1         | 0.48%   |
| Intel NUC5i3RYH         | 1         | 0.48%   |
| Intel NUC5CPYB          | 1         | 0.48%   |
| Intel NUC10i7FNH        | 1         | 0.48%   |
| Intel H81               | 1         | 0.48%   |
| Intel DH77EB            | 1         | 0.48%   |
| Intel DG41TY            | 1         | 0.48%   |
| Intel DCP847SKE         | 1         | 0.48%   |
| HP ZBook                | 1         | 0.48%   |
| HP Z230                 | 1         | 0.48%   |
| HP ProDesk              | 1         | 0.48%   |
| HP ProBook              | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 26        | 12.44%  |
| 2018    | 19        | 9.09%   |
| 2013    | 19        | 9.09%   |
| 2019    | 18        | 8.61%   |
| 2010    | 17        | 8.13%   |
| 2012    | 16        | 7.66%   |
| 2017    | 14        | 6.7%    |
| 2015    | 14        | 6.7%    |
| 2009    | 13        | 6.22%   |
| 2016    | 11        | 5.26%   |
| 2020    | 10        | 4.78%   |
| 2011    | 10        | 4.78%   |
| 2014    | 9         | 4.31%   |
| 2008    | 6         | 2.87%   |
| 2007    | 5         | 2.39%   |
| 2006    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 98        | 46.89%  |
| Desktop    | 96        | 45.93%  |
| Mini pc    | 8         | 3.83%   |
| All in one | 7         | 3.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 209       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 62        | 29.67%  |
| 4.01-8.0    | 60        | 28.71%  |
| 16.01-24.0  | 46        | 22.01%  |
| 32.01-64.0  | 19        | 9.09%   |
| 2.01-3.0    | 12        | 5.74%   |
| 64.01-256.0 | 4         | 1.91%   |
| 24.01-32.0  | 3         | 1.44%   |
| 3.01-4.0    | 1         | 0.48%   |
| 1.01-2.0    | 1         | 0.48%   |
| 0.51-1.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 115       | 54.76%  |
| 0.51-1.0  | 60        | 28.57%  |
| 1.01-2.0  | 27        | 12.86%  |
| 2.01-3.0  | 6         | 2.86%   |
| 3.01-4.0  | 1         | 0.48%   |
| 8.01-16.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 57.08%  |
| 2      | 56        | 26.42%  |
| 3      | 10        | 4.72%   |
| 4      | 9         | 4.25%   |
| 0      | 9         | 4.25%   |
| 5      | 4         | 1.89%   |
| 6      | 2         | 0.94%   |
| 7      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 128       | 61.24%  |
| Yes       | 81        | 38.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 95.69%  |
| No        | 9         | 4.31%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 68.42%  |
| No        | 66        | 31.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 50.72%  |
| No        | 103       | 49.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 34        | 16.27%  |
| Russia      | 25        | 11.96%  |
| Germany     | 15        | 7.18%   |
| Ukraine     | 9         | 4.31%   |
| Spain       | 9         | 4.31%   |
| Poland      | 9         | 4.31%   |
| Hungary     | 9         | 4.31%   |
| Canada      | 9         | 4.31%   |
| Brazil      | 9         | 4.31%   |
| UK          | 7         | 3.35%   |
| Romania     | 6         | 2.87%   |
| Italy       | 6         | 2.87%   |
| France      | 6         | 2.87%   |
| India       | 5         | 2.39%   |
| Vietnam     | 4         | 1.91%   |
| China       | 4         | 1.91%   |
| Peru        | 3         | 1.44%   |
| Netherlands | 3         | 1.44%   |
| Greece      | 3         | 1.44%   |
| Denmark     | 3         | 1.44%   |
| Turkey      | 2         | 0.96%   |
| South Korea | 2         | 0.96%   |
| Norway      | 2         | 0.96%   |
| Mexico      | 2         | 0.96%   |
| Indonesia   | 2         | 0.96%   |
| Chile       | 2         | 0.96%   |
| Australia   | 2         | 0.96%   |
| Thailand    | 1         | 0.48%   |
| Tanzania    | 1         | 0.48%   |
| Taiwan      | 1         | 0.48%   |
| Sweden      | 1         | 0.48%   |
| Portugal    | 1         | 0.48%   |
| Philippines | 1         | 0.48%   |
| Malaysia    | 1         | 0.48%   |
| Lithuania   | 1         | 0.48%   |
| Kazakhstan  | 1         | 0.48%   |
| Georgia     | 1         | 0.48%   |
| Finland     | 1         | 0.48%   |
| Cuba        | 1         | 0.48%   |
| Colombia    | 1         | 0.48%   |
| Bulgaria    | 1         | 0.48%   |
| Belarus     | 1         | 0.48%   |
| Austria     | 1         | 0.48%   |
| Argentina   | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 5         | 2.34%   |
| St Petersburg                 | 4         | 1.87%   |
| Hanoi                         | 4         | 1.87%   |
| Warsaw                        | 3         | 1.4%    |
| Rio de Janeiro                | 3         | 1.4%    |
| Lima                          | 3         | 1.4%    |
| Kharkiv                       | 3         | 1.4%    |
| Tiruchi                       | 2         | 0.93%   |
| Surgut                        | 2         | 0.93%   |
| Suceava                       | 2         | 0.93%   |
| Smiths Falls                  | 2         | 0.93%   |
| Sherwood Park                 | 2         | 0.93%   |
| San SebastiÃ¡n de los Reyes | 2         | 0.93%   |
| Pflugerville                  | 2         | 0.93%   |
| Myrtle Beach                  | 2         | 0.93%   |
| Leatherhead                   | 2         | 0.93%   |
| Katowice                      | 2         | 0.93%   |
| Jakarta                       | 2         | 0.93%   |
| Dreieich                      | 2         | 0.93%   |
| Dijon                         | 2         | 0.93%   |
| Coria del RÃ­o              | 2         | 0.93%   |
| Bucharest                     | 2         | 0.93%   |
| Beijing                       | 2         | 0.93%   |
| Barnaul                       | 2         | 0.93%   |
| Amsterdam                     | 2         | 0.93%   |
| Zaporizhzhya                  | 1         | 0.47%   |
| Zapopan                       | 1         | 0.47%   |
| Yunlin                        | 1         | 0.47%   |
| Youngsville                   | 1         | 0.47%   |
| Yaphank                       | 1         | 0.47%   |
| Vilnius                       | 1         | 0.47%   |
| VÃ¤sterÃ¥s                | 1         | 0.47%   |
| Ugarchin                      | 1         | 0.47%   |
| Turley                        | 1         | 0.47%   |
| Turin                         | 1         | 0.47%   |
| Torokszentmiklos              | 1         | 0.47%   |
| Thessaloniki                  | 1         | 0.47%   |
| Szombathely                   | 1         | 0.47%   |
| Szeged                        | 1         | 0.47%   |
| SzÃ©kesfehÃ©rvÃ¡r       | 1         | 0.47%   |
| Susanville                    | 1         | 0.47%   |
| Stavropol                     | 1         | 0.47%   |
| Sparta                        | 1         | 0.47%   |
| Spalice                       | 1         | 0.47%   |
| Sopron                        | 1         | 0.47%   |
| Songpa-gu                     | 1         | 0.47%   |
| Shah Alam                     | 1         | 0.47%   |
| Seville                       | 1         | 0.47%   |
| Sevastopol                    | 1         | 0.47%   |
| Seattle                       | 1         | 0.47%   |
| Santa Maria                   | 1         | 0.47%   |
| San Luis PotosÃ­ City       | 1         | 0.47%   |
| San Antonio                   | 1         | 0.47%   |
| Riverton                      | 1         | 0.47%   |
| Rho                           | 1         | 0.47%   |
| Renfrew                       | 1         | 0.47%   |
| Ransbach-Baumbach             | 1         | 0.47%   |
| QuÃ©bec                     | 1         | 0.47%   |
| Pruszcz Gdanski               | 1         | 0.47%   |
| Potsdam                       | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 58        | 70     | 18.83%  |
| Seagate             | 46        | 61     | 14.94%  |
| Samsung Electronics | 46        | 52     | 14.94%  |
| Toshiba             | 23        | 26     | 7.47%   |
| Kingston            | 23        | 26     | 7.47%   |
| Crucial             | 20        | 25     | 6.49%   |
| SanDisk             | 9         | 10     | 2.92%   |
| Intel               | 9         | 10     | 2.92%   |
| Hitachi             | 8         | 9      | 2.6%    |
| A-DATA Technology   | 8         | 8      | 2.6%    |
| HGST                | 6         | 6      | 1.95%   |
| SK Hynix            | 5         | 7      | 1.62%   |
| Patriot             | 5         | 5      | 1.62%   |
| GOODRAM             | 4         | 4      | 1.3%    |
| XPG                 | 3         | 3      | 0.97%   |
| SPCC                | 3         | 4      | 0.97%   |
| Phison              | 3         | 3      | 0.97%   |
| OCZ                 | 2         | 2      | 0.65%   |
| Mushkin             | 2         | 2      | 0.65%   |
| KingSpec            | 2         | 2      | 0.65%   |
| Gigabyte Technology | 2         | 3      | 0.65%   |
| Fujitsu             | 2         | 2      | 0.65%   |
| Apple               | 2         | 2      | 0.65%   |
| Apacer              | 2         | 2      | 0.65%   |
| Zheino              | 1         | 1      | 0.32%   |
| Transcend           | 1         | 1      | 0.32%   |
| Team                | 1         | 1      | 0.32%   |
| PNY                 | 1         | 1      | 0.32%   |
| PLEXTOR             | 1         | 1      | 0.32%   |
| Micron Technology   | 1         | 1      | 0.32%   |
| Lite-On             | 1         | 1      | 0.32%   |
| KIOXIA              | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| Integral            | 1         | 1      | 0.32%   |
| INDMEM              | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 1      | 0.32%   |
| Corsair             | 1         | 1      | 0.32%   |
| China               | 1         | 1      | 0.32%   |
| AGI                 | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB             | 8         | 2.41%   |
| Crucial CT500MX500SSD1 500GB            | 6         | 1.81%   |
| WDC WDS120G2G0A-00JH30 120GB            | 4         | 1.2%    |
| Kingston SA400S37240G 240GB             | 4         | 1.2%    |
| HGST HTS545050A7E680 500GB              | 4         | 1.2%    |
| Crucial CT240BX500SSD1 240GB            | 4         | 1.2%    |
| XPG GAMMIX S11 Pro 256GB                | 3         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB            | 3         | 0.9%    |
| WDC WD5000LPVX-22V0TT0 500GB            | 3         | 0.9%    |
| Toshiba MQ01ABF050 500GB                | 3         | 0.9%    |
| Seagate ST4000DM004-2CV104 4TB          | 3         | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 0.9%    |
| Samsung SSD 860 EVO 500GB               | 3         | 0.9%    |
| Samsung SSD 850 EVO 250GB               | 3         | 0.9%    |
| Crucial CT120BX500SSD1 120GB            | 3         | 0.9%    |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 0.6%    |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.6%    |
| WDC WD20PURZ-85GU6Y0 2TB                | 2         | 0.6%    |
| Toshiba HDWD110 1TB                     | 2         | 0.6%    |
| Toshiba DT01ACA050 500GB                | 2         | 0.6%    |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.6%    |
| Seagate ST3500413AS 500GB               | 2         | 0.6%    |
| Seagate ST3320418AS 320GB               | 2         | 0.6%    |
| Seagate ST31000528AS 1TB                | 2         | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 0.6%    |
| Samsung SSD 980 PRO 1TB                 | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB          | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.6%    |
| Samsung SSD 970 EVO 250GB               | 2         | 0.6%    |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.6%    |
| Samsung SSD 850 EVO 500GB               | 2         | 0.6%    |
| Samsung Portable SSD T5 500GB           | 2         | 0.6%    |
| Samsung MZVLW256HEHP-000L7 256GB        | 2         | 0.6%    |
| Samsung HD322HJ 320GB                   | 2         | 0.6%    |
| Patriot Burst 120GB                     | 2         | 0.6%    |
| Hitachi HTS541680J9SA00 80GB            | 2         | 0.6%    |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2         | 0.6%    |
| Crucial CT256MX100SSD1 256GB            | 2         | 0.6%    |
| Crucial CT1050MX300SSD1 1TB             | 2         | 0.6%    |
| A-DATA SP550 240GB                      | 2         | 0.6%    |
| Zheino CHN mSATAM1 256 256GB            | 1         | 0.3%    |
| WDC WDS500G2B0B-00YS70 500GB            | 1         | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB            | 1         | 0.3%    |
| WDC WDS250G1B0A-00H9H0 250GB            | 1         | 0.3%    |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB              | 1         | 0.3%    |
| WDC WDBNCE5000PNC 500GB                 | 1         | 0.3%    |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1         | 0.3%    |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPLX-66ZNTT0 500GB            | 1         | 0.3%    |
| WDC WD5000LPLX-60ZNTT1 500GB            | 1         | 0.3%    |
| WDC WD5000LPCX-75VHAT0 500GB            | 1         | 0.3%    |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.3%    |
| WDC WD5000BPKX-22HPJT0 500GB            | 1         | 0.3%    |
| WDC WD5000AZLX-00CL5A0 500GB            | 1         | 0.3%    |
| WDC WD5000AAKX-75U6AA0 500GB            | 1         | 0.3%    |
| WDC WD5000AAKS-22A7B0 500GB             | 1         | 0.3%    |
| WDC WD40EZRZ-00GXCB0 4TB                | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 45        | 57     | 34.62%  |
| WDC                 | 41        | 47     | 31.54%  |
| Toshiba             | 20        | 23     | 15.38%  |
| Samsung Electronics | 8         | 8      | 6.15%   |
| Hitachi             | 8         | 9      | 6.15%   |
| HGST                | 6         | 6      | 4.62%   |
| Fujitsu             | 1         | 1      | 0.77%   |
| Apple               | 1         | 1      | 0.77%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 27     | 18.98%  |
| Crucial             | 20        | 24     | 14.6%   |
| Kingston            | 19        | 20     | 13.87%  |
| WDC                 | 11        | 15     | 8.03%   |
| SanDisk             | 9         | 10     | 6.57%   |
| A-DATA Technology   | 7         | 7      | 5.11%   |
| Intel               | 6         | 6      | 4.38%   |
| Patriot             | 5         | 5      | 3.65%   |
| GOODRAM             | 4         | 4      | 2.92%   |
| SPCC                | 3         | 4      | 2.19%   |
| Toshiba             | 2         | 2      | 1.46%   |
| SK Hynix            | 2         | 2      | 1.46%   |
| OCZ                 | 2         | 2      | 1.46%   |
| KingSpec            | 2         | 2      | 1.46%   |
| Gigabyte Technology | 2         | 3      | 1.46%   |
| Apacer              | 2         | 2      | 1.46%   |
| Zheino              | 1         | 1      | 0.73%   |
| Transcend           | 1         | 1      | 0.73%   |
| Team                | 1         | 1      | 0.73%   |
| PNY                 | 1         | 1      | 0.73%   |
| PLEXTOR             | 1         | 1      | 0.73%   |
| Mushkin             | 1         | 1      | 0.73%   |
| Lite-On             | 1         | 1      | 0.73%   |
| Intenso             | 1         | 1      | 0.73%   |
| Integral            | 1         | 1      | 0.73%   |
| INDMEM              | 1         | 1      | 0.73%   |
| Hewlett-Packard     | 1         | 1      | 0.73%   |
| Fujitsu             | 1         | 1      | 0.73%   |
| Corsair             | 1         | 1      | 0.73%   |
| China               | 1         | 1      | 0.73%   |
| Apple               | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 114       | 150    | 42.54%  |
| HDD  | 110       | 152    | 41.04%  |
| NVMe | 44        | 57     | 16.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 185       | 302    | 80.79%  |
| NVMe | 44        | 57     | 19.21%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 155       | 212    | 68.28%  |
| 0.51-1.0   | 44        | 53     | 19.38%  |
| 1.01-2.0   | 15        | 16     | 6.61%   |
| 3.01-4.0   | 7         | 14     | 3.08%   |
| 2.01-3.0   | 4         | 5      | 1.76%   |
| 4.01-10.0  | 2         | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 124       | 58.22%  |
| 101-250    | 42        | 19.72%  |
| 251-500    | 27        | 12.68%  |
| 501-1000   | 10        | 4.69%   |
| 21-50      | 5         | 2.35%   |
| 51-100     | 5         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 207       | 99.04%  |
| 21-50   | 1         | 0.48%   |
| 101-250 | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2         | 2      | 3.39%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 3.39%   |
| Seagate ST31000528AS 1TB            | 2         | 3      | 3.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 3.39%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 1.69%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 1.69%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 1.69%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1      | 1.69%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 1.69%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 1.69%   |
| WDC WD400JB-00ENA0 40GB             | 1         | 1      | 1.69%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.69%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1         | 1      | 1.69%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 1.69%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 1.69%   |
| WDC WD1600BEKT-66F3T2 160GB         | 1         | 1      | 1.69%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 1      | 1.69%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 1.69%   |
| Toshiba THNSNX024GMNT 24GB          | 1         | 1      | 1.69%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.69%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 1.69%   |
| Toshiba MK8034GSX 80GB              | 1         | 1      | 1.69%   |
| Toshiba MK7559GSXF 752GB            | 1         | 1      | 1.69%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.69%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.69%   |
| Toshiba MD04ACA400 4TB              | 1         | 1      | 1.69%   |
| Toshiba DT01ACA100 1TB              | 1         | 3      | 1.69%   |
| Toshiba DT01ABA300 3TB              | 1         | 1      | 1.69%   |
| Seagate ST9640320AS 640GB           | 1         | 1      | 1.69%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 1.69%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.69%   |
| Seagate ST380211AS 80GB             | 1         | 1      | 1.69%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 1.69%   |
| Seagate ST3250310AS 250GB           | 1         | 1      | 1.69%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.69%   |
| Seagate ST3160812AS 160GB           | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 1.69%   |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 1      | 1.69%   |
| Samsung Electronics HS082HB 80GB    | 1         | 1      | 1.69%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 1.69%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 1.69%   |
| Samsung Electronics HD250HJ 250GB   | 1         | 1      | 1.69%   |
| Kingston SV200S3128G 128GB          | 1         | 1      | 1.69%   |
| Kingston SMS200S3120G 120GB         | 1         | 1      | 1.69%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 1.69%   |
| Hitachi HTS543232L9SA02 320GB       | 1         | 1      | 1.69%   |
| Hitachi HTS542516K9SA00 160GB       | 1         | 1      | 1.69%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 2      | 1.69%   |
| Hitachi HDT721064SLA360 640GB       | 1         | 1      | 1.69%   |
| Hitachi HDT721010SLA360 1TB         | 1         | 1      | 1.69%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 1.69%   |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 1.69%   |
| Crucial CT1050MX300SSD1 1TB         | 1         | 1      | 1.69%   |
| AGI AGI512G16AI198 512GB            | 1         | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 26.32%  |
| WDC                 | 14        | 14     | 24.56%  |
| Toshiba             | 10        | 13     | 17.54%  |
| Samsung Electronics | 6         | 6      | 10.53%  |
| Hitachi             | 6         | 7      | 10.53%  |
| Kingston            | 2         | 2      | 3.51%   |
| Crucial             | 2         | 2      | 3.51%   |
| HGST                | 1         | 1      | 1.75%   |
| AGI                 | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 30.61%  |
| WDC                 | 14        | 14     | 28.57%  |
| Toshiba             | 9         | 12     | 18.37%  |
| Hitachi             | 6         | 7      | 12.24%  |
| Samsung Electronics | 4         | 4      | 8.16%   |
| HGST                | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 55     | 85.19%  |
| SSD  | 7         | 7      | 12.96%  |
| NVMe | 1         | 1      | 1.85%   |

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
| Works    | 166       | 293    | 74.77%  |
| Malfunc  | 53        | 63     | 23.87%  |
| Detected | 3         | 3      | 1.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 161       | 61.92%  |
| AMD                         | 33        | 12.69%  |
| Samsung Electronics         | 15        | 5.77%   |
| Nvidia                      | 10        | 3.85%   |
| Sandisk                     | 7         | 2.69%   |
| Kingston Technology Company | 4         | 1.54%   |
| ADATA Technology            | 4         | 1.54%   |
| SK Hynix                    | 3         | 1.15%   |
| Phison Electronics          | 3         | 1.15%   |
| Marvell Technology Group    | 3         | 1.15%   |
| JMicron Technology          | 3         | 1.15%   |
| ASMedia Technology          | 3         | 1.15%   |
| Silicon Motion              | 2         | 0.77%   |
| Seagate Technology          | 2         | 0.77%   |
| KIOXIA                      | 2         | 0.77%   |
| VIA Technologies            | 1         | 0.38%   |
| Micron/Crucial Technology   | 1         | 0.38%   |
| Micron Technology           | 1         | 0.38%   |
| Broadcom / LSI              | 1         | 0.38%   |
| Apple                       | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 9.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 3.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 3.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 3.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 2.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 2.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 2.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.38%   |
| Nvidia MCP79 AHCI Controller                                                     | 7         | 2.38%   |
| Intel SATA Controller [RAID mode]                                                | 7         | 2.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.36%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 4         | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.36%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 1.36%   |
| Unknown                                                                          | 4         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.02%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.02%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.68%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.68%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.68%   |
| KIOXIA unknown                                                                   | 2         | 0.68%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.68%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.68%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                          | 2         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.68%   |
| AMD FCH SATA Controller D                                                        | 2         | 0.68%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.34%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.34%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.34%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.34%   |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.34%   |
| Seagate FireCuda 510 SSD                                                         | 1         | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.34%   |
| Sandisk unknown                                                                  | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 175       | 67.31%  |
| NVMe | 45        | 17.31%  |
| IDE  | 29        | 11.15%  |
| RAID | 10        | 3.85%   |
| SCSI | 1         | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 171       | 81.82%  |
| AMD    | 38        | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 2.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4         | 1.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.44%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 2         | 0.96%   |
| Intel CPU Version                           | 2         | 0.96%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.96%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.96%   |
| Intel Core i5-3450 CPU @ 3.10GHz            | 2         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.96%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 0.96%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 2         | 0.96%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 2         | 0.96%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 2         | 0.96%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 2         | 0.96%   |
| Intel Core 2 Duo                            | 2         | 0.96%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 2         | 0.96%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 0.96%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 0.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 0.96%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2         | 0.96%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 0.96%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 0.96%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 0.96%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1         | 0.48%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1         | 0.48%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1         | 0.48%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.48%   |
| Intel Xeon CPU E5504 @ 2.00GHz              | 1         | 0.48%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1         | 0.48%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz         | 1         | 0.48%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1         | 0.48%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.48%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.48%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU E6500 @         | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.48%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.48%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.48%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.48%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.48%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 0.48%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1         | 0.48%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.48%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.48%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.48%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.48%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.48%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1         | 0.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.48%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 27.75%  |
| Intel Core i7           | 23        | 11%     |
| Intel Core i3           | 22        | 10.53%  |
| Intel Core 2 Duo        | 19        | 9.09%   |
| Intel Celeron           | 12        | 5.74%   |
| Intel Xeon              | 11        | 5.26%   |
| AMD Ryzen 5             | 11        | 5.26%   |
| AMD Ryzen 7             | 7         | 3.35%   |
| Intel Pentium           | 5         | 2.39%   |
| Other                   | 4         | 1.91%   |
| Intel Pentium Dual-Core | 4         | 1.91%   |
| Intel Core 2 Quad       | 4         | 1.91%   |
| Intel Atom              | 4         | 1.91%   |
| AMD Ryzen 3             | 3         | 1.44%   |
| Intel Core 2            | 2         | 0.96%   |
| AMD Ryzen 9             | 2         | 0.96%   |
| AMD Phenom II X4        | 2         | 0.96%   |
| AMD E2                  | 2         | 0.96%   |
| AMD E1                  | 2         | 0.96%   |
| AMD A6                  | 2         | 0.96%   |
| AMD A10                 | 2         | 0.96%   |
| Intel Pentium Dual      | 1         | 0.48%   |
| Intel Core M            | 1         | 0.48%   |
| Intel Core i9           | 1         | 0.48%   |
| AMD Ryzen Threadripper  | 1         | 0.48%   |
| AMD FX                  | 1         | 0.48%   |
| AMD E                   | 1         | 0.48%   |
| AMD Athlon II X4        | 1         | 0.48%   |
| AMD Athlon II X2        | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 86        | 41.15%  |
| 4       | 60        | 28.71%  |
| Unknown | 25        | 11.96%  |
| 6       | 14        | 6.7%    |
| 8       | 7         | 3.35%   |
| 16      | 6         | 2.87%   |
| 12      | 6         | 2.87%   |
| 24      | 2         | 0.96%   |
| 64      | 1         | 0.48%   |
| 14      | 1         | 0.48%   |
| 1       | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 196       | 93.78%  |
| 2       | 11        | 5.26%   |
| Unknown | 2         | 0.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 95        | 45.45%  |
| 1       | 89        | 42.58%  |
| Unknown | 25        | 11.96%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 26        | 12.44%  |
| Penryn      | 23        | 11%     |
| Haswell     | 21        | 10.05%  |
| IvyBridge   | 20        | 9.57%   |
| Skylake     | 18        | 8.61%   |
| SandyBridge | 17        | 8.13%   |
| Westmere    | 12        | 5.74%   |
| Core        | 9         | 4.31%   |
| Zen 2       | 8         | 3.83%   |
| Zen+        | 6         | 2.87%   |
| Silvermont  | 6         | 2.87%   |
| Broadwell   | 6         | 2.87%   |
| Zen 3       | 5         | 2.39%   |
| Zen         | 5         | 2.39%   |
| K10         | 4         | 1.91%   |
| Bonnell     | 4         | 1.91%   |
| Piledriver  | 3         | 1.44%   |
| Nehalem     | 3         | 1.44%   |
| CometLake   | 3         | 1.44%   |
| Bobcat      | 3         | 1.44%   |
| Excavator   | 2         | 0.96%   |
| Unknown     | 2         | 0.96%   |
| K10 Llano   | 1         | 0.48%   |
| Jaguar      | 1         | 0.48%   |
| Goldmont    | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 120       | 52.4%   |
| Nvidia | 64        | 27.95%  |
| AMD    | 45        | 19.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.24%   |
| Intel HD Graphics 530                                                                    | 8         | 3.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.97%   |
| Intel HD Graphics 620                                                                    | 6         | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 2.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2.12%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 2.12%   |
| Nvidia C79 [GeForce 9400]                                                                | 4         | 1.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.27%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.27%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.27%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 1.27%   |
| Nvidia TU117M                                                                            | 2         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.85%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.85%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.85%   |
| Intel HD Graphics 630                                                                    | 2         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.85%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.85%   |
| AMD Renoir                                                                               | 2         | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.85%   |
| AMD Cezanne                                                                              | 2         | 0.85%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.42%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.42%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.42%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.42%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.42%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.42%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.42%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.42%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.42%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.42%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.42%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.42%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.42%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.42%   |
| Nvidia GK107GL [Quadro K2000]                                                            | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 90        | 42.65%  |
| 1 x Nvidia     | 51        | 24.17%  |
| 1 x AMD        | 37        | 17.54%  |
| 2 x Intel      | 13        | 6.16%   |
| Intel + Nvidia | 12        | 5.69%   |
| Intel + AMD    | 5         | 2.37%   |
| AMD + Nvidia   | 2         | 0.95%   |
| 2 x AMD        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 160       | 76.19%  |
| Proprietary | 46        | 21.9%   |
| Unknown     | 4         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 62.56%  |
| 0.01-0.5   | 23        | 10.9%   |
| 1.01-2.0   | 16        | 7.58%   |
| 3.01-4.0   | 14        | 6.64%   |
| 0.51-1.0   | 14        | 6.64%   |
| 7.01-8.0   | 9         | 4.27%   |
| 5.01-6.0   | 3         | 1.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 26        | 12.68%  |
| LG Display              | 22        | 10.73%  |
| AU Optronics            | 17        | 8.29%   |
| Chimei Innolux          | 15        | 7.32%   |
| Dell                    | 13        | 6.34%   |
| Lenovo                  | 12        | 5.85%   |
| Goldstar                | 11        | 5.37%   |
| BOE                     | 11        | 5.37%   |
| BenQ                    | 11        | 5.37%   |
| Apple                   | 11        | 5.37%   |
| AOC                     | 9         | 4.39%   |
| Ancor Communications    | 7         | 3.41%   |
| Acer                    | 7         | 3.41%   |
| Philips                 | 6         | 2.93%   |
| Hewlett-Packard         | 5         | 2.44%   |
| Sony                    | 3         | 1.46%   |
| ASUSTek Computer        | 3         | 1.46%   |
| Vestel Elektronik       | 2         | 0.98%   |
| Fujitsu Siemens         | 2         | 0.98%   |
| Westinghouse            | 1         | 0.49%   |
| Toshiba                 | 1         | 0.49%   |
| SGT                     | 1         | 0.49%   |
| RTK                     | 1         | 0.49%   |
| NEC Computers           | 1         | 0.49%   |
| Medion                  | 1         | 0.49%   |
| Lenovo Group Limited    | 1         | 0.49%   |
| LED                     | 1         | 0.49%   |
| Iiyama                  | 1         | 0.49%   |
| FND                     | 1         | 0.49%   |
| Denver                  | 1         | 0.49%   |
| Chi Mei Optoelectronics | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 2         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 0.95%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 2         | 0.95%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 2         | 0.95%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 0.95%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 0.95%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 0.95%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 0.95%   |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                  | 2         | 0.95%   |
| Ancor Communications MX27AQ ACI27A5 2560x1440 600x340mm 27.2-inch      | 2         | 0.95%   |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1         | 0.48%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.48%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.48%   |
| Sony TV SNY9C01 1360x768                                               | 1         | 0.48%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1         | 0.48%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.48%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.48%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1         | 0.48%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.48%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1         | 0.48%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.48%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1         | 0.48%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1         | 0.48%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1         | 0.48%   |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1         | 0.48%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                   | 1         | 0.48%   |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1         | 0.48%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1         | 0.48%   |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1         | 0.48%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1         | 0.48%   |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1         | 0.48%   |
| Medion MD 20160 MED3625 1920x1080 520x290mm 23.4-inch                  | 1         | 0.48%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch           | 1         | 0.48%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch           | 1         | 0.48%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch           | 1         | 0.48%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch           | 1         | 0.48%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch            | 1         | 0.48%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.48%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.48%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 35.82%  |
| 1366x768 (WXGA)    | 50        | 24.88%  |
| 1280x800 (WXGA)    | 12        | 5.97%   |
| 2560x1440 (QHD)    | 11        | 5.47%   |
| 1280x1024 (SXGA)   | 11        | 5.47%   |
| 1600x900 (HD+)     | 8         | 3.98%   |
| 3840x2160 (4K)     | 7         | 3.48%   |
| 1920x1200 (WUXGA)  | 7         | 3.48%   |
| 1440x900 (WXGA+)   | 7         | 3.48%   |
| 1680x1050 (WSXGA+) | 6         | 2.99%   |
| 1920x540           | 3         | 1.49%   |
| 3440x1440          | 2         | 1%      |
| 1024x600           | 2         | 1%      |
| 2560x1080          | 1         | 0.5%    |
| 1360x768           | 1         | 0.5%    |
| 1024x768 (XGA)     | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 16.83%  |
| 13      | 28        | 13.46%  |
| 24      | 23        | 11.06%  |
| 27      | 16        | 7.69%   |
| 23      | 14        | 6.73%   |
| 21      | 13        | 6.25%   |
| 19      | 13        | 6.25%   |
| 12      | 12        | 5.77%   |
| 17      | 10        | 4.81%   |
| 18      | 6         | 2.88%   |
| 14      | 6         | 2.88%   |
| 31      | 5         | 2.4%    |
| 20      | 4         | 1.92%   |
| 11      | 4         | 1.92%   |
| Unknown | 4         | 1.92%   |
| 10      | 3         | 1.44%   |
| 42      | 2         | 0.96%   |
| 34      | 2         | 0.96%   |
| 16      | 2         | 0.96%   |
| 54      | 1         | 0.48%   |
| 50      | 1         | 0.48%   |
| 40      | 1         | 0.48%   |
| 33      | 1         | 0.48%   |
| 29      | 1         | 0.48%   |
| 22      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 61        | 29.9%   |
| 501-600     | 50        | 24.51%  |
| 201-300     | 34        | 16.67%  |
| 401-500     | 29        | 14.22%  |
| 351-400     | 11        | 5.39%   |
| 601-700     | 7         | 3.43%   |
| Unknown     | 4         | 1.96%   |
| 701-800     | 3         | 1.47%   |
| 1001-1500   | 2         | 0.98%   |
| 901-1000    | 2         | 0.98%   |
| 801-900     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 144       | 74.61%  |
| 16/10   | 31        | 16.06%  |
| 5/4     | 9         | 4.66%   |
| 3/2     | 3         | 1.55%   |
| 21/9    | 3         | 1.55%   |
| 4/3     | 2         | 1.04%   |
| Unknown | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 40        | 19.32%  |
| 81-90          | 29        | 14.01%  |
| 91-100         | 29        | 14.01%  |
| 151-200        | 21        | 10.14%  |
| 301-350        | 16        | 7.73%   |
| 61-70          | 12        | 5.8%    |
| 251-300        | 10        | 4.83%   |
| 141-150        | 9         | 4.35%   |
| 351-500        | 8         | 3.86%   |
| 101-110        | 7         | 3.38%   |
| 121-130        | 5         | 2.42%   |
| 71-80          | 4         | 1.93%   |
| 51-60          | 4         | 1.93%   |
| Unknown        | 4         | 1.93%   |
| 41-50          | 3         | 1.45%   |
| 501-1000       | 3         | 1.45%   |
| More than 1000 | 2         | 0.97%   |
| 111-120        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 83        | 40.49%  |
| 101-120 | 63        | 30.73%  |
| 121-160 | 48        | 23.41%  |
| 161-240 | 6         | 2.93%   |
| Unknown | 4         | 1.95%   |
| 1-50    | 1         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 176       | 83.41%  |
| 2     | 20        | 9.48%   |
| 0     | 14        | 6.64%   |
| 3     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 107       | 34.85%  |
| Intel                             | 100       | 32.57%  |
| Qualcomm Atheros                  | 32        | 10.42%  |
| Broadcom                          | 32        | 10.42%  |
| Nvidia                            | 7         | 2.28%   |
| Marvell Technology Group          | 5         | 1.63%   |
| Ralink Technology                 | 3         | 0.98%   |
| NetGear                           | 3         | 0.98%   |
| TP-Link                           | 2         | 0.65%   |
| Ralink                            | 2         | 0.65%   |
| JMicron Technology                | 2         | 0.65%   |
| Ericsson Business Mobile Networks | 2         | 0.65%   |
| Dell                              | 2         | 0.65%   |
| Sierra Wireless                   | 1         | 0.33%   |
| Microchip Technology              | 1         | 0.33%   |
| Mercucys                          | 1         | 0.33%   |
| MediaTek                          | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| Google                            | 1         | 0.33%   |
| Edimax Technology                 | 1         | 0.33%   |
| D-Link System                     | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 21.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.95%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 2.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.14%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.14%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.88%   |
| Intel Wireless 8260                                               | 7         | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.61%   |
| Intel Wireless 7265                                               | 6         | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.34%   |
| Intel Wireless 7260                                               | 5         | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.07%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.07%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.07%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.07%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.07%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.8%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.54%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 2         | 0.54%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.54%   |
| Intel Wireless-AC 9260                                            | 2         | 0.54%   |
| Intel Wireless 3165                                               | 2         | 0.54%   |
| Intel WiFi Link 5100                                              | 2         | 0.54%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.54%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                     | 1         | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 46.5%   |
| Qualcomm Atheros      | 24        | 15.29%  |
| Realtek Semiconductor | 23        | 14.65%  |
| Broadcom              | 22        | 14.01%  |
| Ralink Technology     | 3         | 1.91%   |
| NetGear               | 3         | 1.91%   |
| TP-Link               | 2         | 1.27%   |
| Ralink                | 2         | 1.27%   |
| Sierra Wireless       | 1         | 0.64%   |
| Mercucys              | 1         | 0.64%   |
| MediaTek              | 1         | 0.64%   |
| Edimax Technology     | 1         | 0.64%   |
| Dell                  | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 8         | 5%      |
| Intel Wireless 8260                                              | 7         | 4.38%   |
| Intel Wi-Fi 6 AX200                                              | 7         | 4.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 7         | 4.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller           | 7         | 4.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 6         | 3.75%   |
| Intel Wireless 7265                                              | 6         | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 5         | 3.13%   |
| Intel Wireless 7260                                              | 5         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 4         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 4         | 2.5%    |
| Intel Wireless 8265 / 8275                                       | 4         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 4         | 2.5%    |
| Intel Centrino Advanced-N 6200                                   | 4         | 2.5%    |
| Broadcom BCM4321 802.11a/b/g/n                                   | 4         | 2.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 3         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 3         | 1.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 3         | 1.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 3         | 1.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                     | 3         | 1.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                  | 3         | 1.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 2         | 1.25%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 2         | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 2         | 1.25%   |
| Realtek Realtek Bluetooth 4.2 Adapter                            | 2         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                   | 2         | 1.25%   |
| Intel Wireless-AC 9260                                           | 2         | 1.25%   |
| Intel Wireless 3165                                              | 2         | 1.25%   |
| Intel WiFi Link 5100                                             | 2         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 2         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 2         | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 2         | 1.25%   |
| Intel Centrino Ultimate-N 6300                                   | 2         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 2         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter              | 2         | 1.25%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                    | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter         | 1         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                     | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1         | 0.63%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 1         | 0.63%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                  | 1         | 0.63%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1         | 0.63%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]      | 1         | 0.63%   |
| Mercucys MERCUSYS Wireless USB Adapter                           | 1         | 0.63%   |
| MediaTek 802.11ac Wireless LAN Card                              | 1         | 0.63%   |
| Intel Wireless 3160                                              | 1         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                  | 1         | 0.63%   |
| Intel Centrino Wireless-N 2230                                   | 1         | 0.63%   |
| Intel Centrino Wireless-N 100                                    | 1         | 0.63%   |
| Intel Centrino Advanced-N 6235                                   | 1         | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 1         | 0.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1         | 0.63%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                     | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 97        | 47.32%  |
| Intel                    | 70        | 34.15%  |
| Broadcom                 | 12        | 5.85%   |
| Qualcomm Atheros         | 11        | 5.37%   |
| Nvidia                   | 7         | 3.41%   |
| Marvell Technology Group | 5         | 2.44%   |
| JMicron Technology       | 2         | 0.98%   |
| Google                   | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 79        | 38.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 14        | 6.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 11        | 5.31%   |
| Intel Ethernet Connection I217-LM                                             | 9         | 4.35%   |
| Intel I211 Gigabit Network Connection                                         | 8         | 3.86%   |
| Nvidia MCP79 Ethernet                                                         | 7         | 3.38%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 2.42%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 1.93%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 1.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 3         | 1.45%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.45%   |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 0.97%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 2         | 0.97%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 0.97%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                                          | 2         | 0.97%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.97%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 2         | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1         | 0.48%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.48%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.48%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.48%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.48%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.48%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.48%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.48%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.48%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.48%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.48%   |
| Google Nexus/Pixel Device (tether)                                            | 1         | 0.48%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                             | 1         | 0.48%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 1         | 0.48%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                      | 1         | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 200       | 57.31%  |
| WiFi     | 143       | 40.97%  |
| Modem    | 3         | 0.86%   |
| Unknown  | 3         | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 194       | 62.78%  |
| WiFi     | 111       | 35.92%  |
| Unknown  | 3         | 0.97%   |
| Modem    | 1         | 0.32%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 122       | 58.37%  |
| 1     | 77        | 36.84%  |
| 3     | 5         | 2.39%   |
| 4     | 3         | 1.44%   |
| 0     | 2         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 94.79%  |
| Yes  | 11        | 5.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 43.4%   |
| Apple                           | 13        | 12.26%  |
| Broadcom                        | 9         | 8.49%   |
| Cambridge Silicon Radio         | 8         | 7.55%   |
| Realtek Semiconductor           | 6         | 5.66%   |
| Qualcomm Atheros Communications | 6         | 5.66%   |
| IMC Networks                    | 4         | 3.77%   |
| Lite-On Technology              | 3         | 2.83%   |
| Hewlett-Packard                 | 3         | 2.83%   |
| Foxconn / Hon Hai               | 2         | 1.89%   |
| Dell                            | 2         | 1.89%   |
| ASUSTek Computer                | 2         | 1.89%   |
| Integrated System Solution      | 1         | 0.94%   |
| HTC (High Tech Computer)        | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 26        | 24.07%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8         | 7.41%   |
| Intel AX200 Bluetooth                                                | 7         | 6.48%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 5         | 4.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5         | 4.63%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.7%    |
| Intel AX201 Bluetooth                                                | 4         | 3.7%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 3         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3         | 2.78%   |
| Apple Built-in iSight (no firmware loaded)                           | 3         | 2.78%   |
| Realtek Bluetooth Radio                                              | 2         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 2         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 1.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 1.85%   |
| Apple Bluetooth Host Controller                                      | 2         | 1.85%   |
| Apple Apple Broadcom Built-in Bluetooth                              | 2         | 1.85%   |
| Realtek RTL8723B Bluetooth                                           | 1         | 0.93%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.93%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1         | 0.93%   |
| Lite-On Realtek Bluetooth Adapter                                    | 1         | 0.93%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1         | 0.93%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1         | 0.93%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1         | 0.93%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 0.93%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 1         | 0.93%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 1         | 0.93%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0                     | 1         | 0.93%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 1         | 0.93%   |
| Dell DW375 Bluetooth Module                                          | 1         | 0.93%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 0.93%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 0.93%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 1         | 0.93%   |
| ASUS Bluetooth Controller                                            | 1         | 0.93%   |
| ASUS ASUS USB-BT500                                                  | 1         | 0.93%   |
| Apple Broadcom Bluetooth 2.1 module                                  | 1         | 0.93%   |
| Apple Bluetooth USB Host Controller                                  | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 159       | 54.45%  |
| Nvidia                    | 51        | 17.47%  |
| AMD                       | 50        | 17.12%  |
| C-Media Electronics       | 7         | 2.4%    |
| GN Netcom                 | 5         | 1.71%   |
| Texas Instruments         | 4         | 1.37%   |
| Logitech                  | 2         | 0.68%   |
| Yamaha                    | 1         | 0.34%   |
| VIA Technologies          | 1         | 0.34%   |
| SteelSeries ApS           | 1         | 0.34%   |
| Sennheiser Communications | 1         | 0.34%   |
| Nektar                    | 1         | 0.34%   |
| KORG                      | 1         | 0.34%   |
| Kingston Technology       | 1         | 0.34%   |
| JMTek                     | 1         | 0.34%   |
| Focusrite-Novation        | 1         | 0.34%   |
| Creative Technology       | 1         | 0.34%   |
| Creative Labs             | 1         | 0.34%   |
| Corsair                   | 1         | 0.34%   |
| Cambridge Silicon Radio   | 1         | 0.34%   |
| ASUSTek Computer          | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 3.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 2.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.08%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.19%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 0.89%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 0.89%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.59%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.59%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.59%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.59%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 2         | 0.59%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 2         | 0.59%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.59%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.59%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.59%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.59%   |
| Yamaha Steinberg UR12                                                                             | 1         | 0.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.3%    |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.3%    |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.3%    |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game                                  | 1         | 0.3%    |
| Sennheiser Communications Sennheiser 3D G4ME1                                                     | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 18.64%  |
| Kingston            | 39        | 16.53%  |
| SK Hynix            | 33        | 13.98%  |
| Unknown             | 28        | 11.86%  |
| Crucial             | 15        | 6.36%   |
| Micron Technology   | 14        | 5.93%   |
| Corsair             | 12        | 5.08%   |
| G.Skill             | 9         | 3.81%   |
| Ramaxel Technology  | 5         | 2.12%   |
| Nanya Technology    | 5         | 2.12%   |
| Team                | 3         | 1.27%   |
| Patriot             | 3         | 1.27%   |
| Elpida              | 3         | 1.27%   |
| A-DATA Technology   | 3         | 1.27%   |
| Unknown             | 3         | 1.27%   |
| Smart               | 2         | 0.85%   |
| AMD                 | 2         | 0.85%   |
| 48spaces            | 2         | 0.85%   |
| Unifosa             | 1         | 0.42%   |
| Silicon Power       | 1         | 0.42%   |
| Sesame              | 1         | 0.42%   |
| Kingmax             | 1         | 0.42%   |
| Hikvision           | 1         | 0.42%   |
| High Bridge         | 1         | 0.42%   |
| GOODRAM             | 1         | 0.42%   |
| Goldkey             | 1         | 0.42%   |
| Avant               | 1         | 0.42%   |
| Atermiter           | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.56%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 3         | 1.17%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.17%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.17%   |
| Unknown                                                                   | 3         | 1.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                 | 2         | 0.78%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 2         | 0.78%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 2         | 0.78%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.78%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                          | 2         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 0.78%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.78%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.78%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s                    | 2         | 0.78%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s                    | 2         | 0.78%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                     | 2         | 0.78%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                 | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                      | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                                 | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                  | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                  | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2                                          | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                       | 1         | 0.39%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 1         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                  | 1         | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                                  | 1         | 0.39%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                         | 1         | 0.39%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                       | 1         | 0.39%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s                        | 1         | 0.39%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                        | 1         | 0.39%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.39%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.39%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.39%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                              | 1         | 0.39%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                              | 1         | 0.39%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                                | 1         | 0.39%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.39%   |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                              | 1         | 0.39%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.39%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.39%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 0.39%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 102       | 50.25%  |
| DDR4    | 68        | 33.5%   |
| DDR2    | 20        | 9.85%   |
| Unknown | 7         | 3.45%   |
| SDRAM   | 3         | 1.48%   |
| LPDDR3  | 2         | 0.99%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 116       | 57.43%  |
| DIMM         | 85        | 42.08%  |
| Row Of Chips | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 75        | 33.63%  |
| 8192  | 59        | 26.46%  |
| 2048  | 51        | 22.87%  |
| 16384 | 25        | 11.21%  |
| 1024  | 10        | 4.48%   |
| 32768 | 3         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 27.65%  |
| 1333    | 27        | 12.44%  |
| 3200    | 16        | 7.37%   |
| 2667    | 16        | 7.37%   |
| 2400    | 16        | 7.37%   |
| 2133    | 15        | 6.91%   |
| 667     | 14        | 6.45%   |
| 1334    | 11        | 5.07%   |
| 1067    | 11        | 5.07%   |
| 800     | 7         | 3.23%   |
| 2666    | 6         | 2.76%   |
| 1867    | 4         | 1.84%   |
| Unknown | 4         | 1.84%   |
| 1066    | 3         | 1.38%   |
| 3600    | 2         | 0.92%   |
| 400     | 2         | 0.92%   |
| 3733    | 1         | 0.46%   |
| 533     | 1         | 0.46%   |
| 333     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Brother Industries  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 1         | 50%     |
| Brother HL-1430 Laser Printer | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 28.74%  |
| Realtek Semiconductor                  | 7         | 8.05%   |
| IMC Networks                           | 6         | 6.9%    |
| Quanta                                 | 5         | 5.75%   |
| Microdia                               | 5         | 5.75%   |
| Lite-On Technology                     | 5         | 5.75%   |
| Sunplus Innovation Technology          | 4         | 4.6%    |
| Logitech                               | 4         | 4.6%    |
| Acer                                   | 4         | 4.6%    |
| Z-Star Microelectronics                | 3         | 3.45%   |
| Syntek                                 | 2         | 2.3%    |
| Suyin                                  | 2         | 2.3%    |
| Lenovo                                 | 2         | 2.3%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.3%    |
| Apple                                  | 2         | 2.3%    |
| Alcor Micro                            | 2         | 2.3%    |
| Silicon Motion                         | 1         | 1.15%   |
| Primax Electronics                     | 1         | 1.15%   |
| Luxvisions Innotech Limited            | 1         | 1.15%   |
| Importek                               | 1         | 1.15%   |
| Hewlett-Packard                        | 1         | 1.15%   |
| Arkmicro Technologies                  | 1         | 1.15%   |
| ARC International                      | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 5.68%   |
| Chicony HD WebCam                                   | 4         | 4.55%   |
| Lite-On Integrated Camera                           | 3         | 3.41%   |
| Chicony EasyCamera                                  | 3         | 3.41%   |
| Realtek USB Camera                                  | 2         | 2.27%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 2.27%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.27%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.27%   |
| IMC Networks Integrated Camera                      | 2         | 2.27%   |
| Chicony Integrated Camera                           | 2         | 2.27%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 2.27%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 1.14%   |
| Z-Star Webcam                                       | 1         | 1.14%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 1.14%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.14%   |
| Syntek ASUS USB2.0 camera                           | 1         | 1.14%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.14%   |
| Suyin HD Video WebCam                               | 1         | 1.14%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.14%   |
| Sunplus Integrated Camera                           | 1         | 1.14%   |
| Sunplus HP Universal Camera                         | 1         | 1.14%   |
| Sunplus HD WebCam                                   | 1         | 1.14%   |
| Silicon Motion HP Webcam-50                         | 1         | 1.14%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.14%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 1.14%   |
| Realtek Integrated_Webcam_8M                        | 1         | 1.14%   |
| Realtek HD WebCam                                   | 1         | 1.14%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.14%   |
| Quanta HP Webcam                                    | 1         | 1.14%   |
| Quanta HD WebCam                                    | 1         | 1.14%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.14%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.14%   |
| Microdia Integrated Webcam                          | 1         | 1.14%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.14%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.14%   |
| Logitech Webcam C930e                               | 1         | 1.14%   |
| Logitech Webcam C310                                | 1         | 1.14%   |
| Logitech Webcam C270                                | 1         | 1.14%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.14%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.14%   |
| Lite-On HP HD Camera                                | 1         | 1.14%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.14%   |
| Lenovo Integrated Webcam                            | 1         | 1.14%   |
| Importek TOSHIBA Web Camera                         | 1         | 1.14%   |
| IMC Networks XHC Camera                             | 1         | 1.14%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.14%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.14%   |
| IMC Networks EasyCamera                             | 1         | 1.14%   |
| HP Realtek PC Camera                                | 1         | 1.14%   |
| Chicony Webcam-101                                  | 1         | 1.14%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.14%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.14%   |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 1.14%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.14%   |
| Chicony thinkpad t430s camera                       | 1         | 1.14%   |
| Chicony HP Webcam                                   | 1         | 1.14%   |
| Chicony HP 0.3MP Webcam                             | 1         | 1.14%   |
| Chicony HD WebCam (Acer)                            | 1         | 1.14%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.14%   |
| Chicony 1.3M Webcam                                 | 1         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Upek                       | 8         | 33.33%  |
| Validity Sensors           | 7         | 29.17%  |
| AuthenTec                  | 3         | 12.5%   |
| STMicroelectronics         | 2         | 8.33%   |
| LighTuning Technology      | 2         | 8.33%   |
| Synaptics                  | 1         | 4.17%   |
| Shenzhen Goodix Technology | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 7         | 29.17%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 8.33%   |
| Validity Sensors Synaptics WBDI                        | 2         | 8.33%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.17%   |
| Validity Sensors VFS491                                | 1         | 4.17%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.17%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.17%   |
| AuthenTec AES2810                                      | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.17%   |
| AuthenTec AES1600                                      | 1         | 4.17%   |

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
| 1     | 84        | 40%     |
| 0     | 58        | 27.62%  |
| 2     | 44        | 20.95%  |
| 3     | 16        | 7.62%   |
| 4     | 8         | 3.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 125       | 53.65%  |
| Net/wireless             | 39        | 16.74%  |
| Fingerprint reader       | 23        | 9.87%   |
| Bluetooth                | 22        | 9.44%   |
| Card reader              | 15        | 6.44%   |
| Sound                    | 5         | 2.15%   |
| Network                  | 2         | 0.86%   |
| Storage/nvme             | 1         | 0.43%   |
| Net/ethernet             | 1         | 0.43%   |

