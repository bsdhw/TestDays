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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 179       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 177       | 98.88%  |
| GNOME        | 2         | 1.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 179       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 179       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 170       | 94.97%  |
| de_DE | 4         | 2.23%   |
| C     | 2         | 1.12%   |
| uk_UA | 1         | 0.56%   |
| fr_FR | 1         | 0.56%   |
| es_ES | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 174       | 97.21%  |
| BIOS | 5         | 2.79%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 106       | 57.92%  |
| Zfs    | 77        | 42.08%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 176       | 98.32%  |
| MBR  | 3         | 1.68%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 32        | 17.88%  |
| Lenovo              | 27        | 15.08%  |
| Dell                | 20        | 11.17%  |
| Hewlett-Packard     | 19        | 10.61%  |
| Gigabyte Technology | 14        | 7.82%   |
| Apple               | 13        | 7.26%   |
| Acer                | 11        | 6.15%   |
| Intel               | 10        | 5.59%   |
| ASRock              | 9         | 5.03%   |
| Toshiba             | 4         | 2.23%   |
| MSI                 | 4         | 2.23%   |
| Samsung Electronics | 3         | 1.68%   |
| Pegatron            | 3         | 1.68%   |
| Unknown             | 2         | 1.12%   |
| TWINHEAD            | 1         | 0.56%   |
| TUXEDO              | 1         | 0.56%   |
| Quanta              | 1         | 0.56%   |
| Notebook            | 1         | 0.56%   |
| Medion              | 1         | 0.56%   |
| Gateway             | 1         | 0.56%   |
| Fujitsu             | 1         | 0.56%   |
| Acidanthera         | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Apple iMac9,1                            | 3         | 1.68%   |
| Dell Latitude E5470                      | 2         | 1.12%   |
| ASUS TUF GAMING X570-PLUS                | 2         | 1.12%   |
| Apple MacBook4,1                         | 2         | 1.12%   |
| Acer V5-131                              | 2         | 1.12%   |
| Unknown                                  | 2         | 1.12%   |
| TWINHEAD U12CT                           | 1         | 0.56%   |
| TUXEDO InfinityBook13V3                  | 1         | 0.56%   |
| Toshiba Satellite S55t-B                 | 1         | 0.56%   |
| Toshiba Satellite L550                   | 1         | 0.56%   |
| Toshiba Satellite C640                   | 1         | 0.56%   |
| Toshiba Satellite C50-B                  | 1         | 0.56%   |
| Samsung N150P/N210P/N220P                | 1         | 0.56%   |
| Samsung N100                             | 1         | 0.56%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 0.56%   |
| Quanta 120-1135                          | 1         | 0.56%   |
| Pegatron IPM41-D3                        | 1         | 0.56%   |
| Pegatron Compaq 505B Microtower PC       | 1         | 0.56%   |
| Pegatron AY627AA-ABA a4313w              | 1         | 0.56%   |
| Notebook N15_17RD                        | 1         | 0.56%   |
| MSI MS-7D25                              | 1         | 0.56%   |
| MSI MS-7B86                              | 1         | 0.56%   |
| MSI MS-7A33                              | 1         | 0.56%   |
| MSI MS-7758                              | 1         | 0.56%   |
| Medion H61H2-LM3                         | 1         | 0.56%   |
| Lenovo V310-14IKB 80T2                   | 1         | 0.56%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01    | 1         | 0.56%   |
| Lenovo ThinkPad X250 20CLS1WP01          | 1         | 0.56%   |
| Lenovo ThinkPad X240 20AMS2QDOC          | 1         | 0.56%   |
| Lenovo ThinkPad X220 Tablet 42962WU      | 1         | 0.56%   |
| Lenovo ThinkPad X220 4293AF4             | 1         | 0.56%   |
| Lenovo ThinkPad X220 4291H77             | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.56%   |
| Lenovo ThinkPad T61 766301U              | 1         | 0.56%   |
| Lenovo ThinkPad T60 1951FEG              | 1         | 0.56%   |
| Lenovo ThinkPad T510 4384AJ6             | 1         | 0.56%   |
| Lenovo ThinkPad T460 20FMS75800          | 1         | 0.56%   |
| Lenovo ThinkPad T440p 20AWS3RH00         | 1         | 0.56%   |
| Lenovo ThinkPad T440 20B7000PHV          | 1         | 0.56%   |
| Lenovo ThinkPad T430 2349AK1             | 1         | 0.56%   |
| Lenovo ThinkPad T410 2537EA8             | 1         | 0.56%   |
| Lenovo ThinkPad T410 2522E38             | 1         | 0.56%   |
| Lenovo ThinkPad SL510 2847R96            | 1         | 0.56%   |
| Lenovo ThinkPad R61 8935WCS              | 1         | 0.56%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 0.56%   |
| Lenovo ThinkPad E580 20KS005BRI          | 1         | 0.56%   |
| Lenovo ThinkPad E15 20RD0011MX           | 1         | 0.56%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 0.56%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL    | 1         | 0.56%   |
| Lenovo IdeaPad 510-15IKB 80SV            | 1         | 0.56%   |
| Lenovo IdeaPad 110S-11IBR 80WG           | 1         | 0.56%   |
| Lenovo E31-80 80MX                       | 1         | 0.56%   |
| Intel X58                                | 1         | 0.56%   |
| Intel NUC8i3BEH                          | 1         | 0.56%   |
| Intel NUC7i3BNK                          | 1         | 0.56%   |
| Intel NUC5i3RYH                          | 1         | 0.56%   |
| Intel NUC5CPYB H61145-404                | 1         | 0.56%   |
| Intel NUC10i7FNH                         | 1         | 0.56%   |
| Intel H81                                | 1         | 0.56%   |
| Intel DH77EB AAG39073-400                | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 21        | 11.73%  |
| Dell Latitude           | 9         | 5.03%   |
| Acer Aspire             | 6         | 3.35%   |
| ASUS ROG                | 5         | 2.79%   |
| ASUS PRIME              | 5         | 2.79%   |
| Toshiba Satellite       | 4         | 2.23%   |
| Dell Inspiron           | 4         | 2.23%   |
| Lenovo IdeaPad          | 3         | 1.68%   |
| HP Pavilion             | 3         | 1.68%   |
| HP Laptop               | 3         | 1.68%   |
| HP EliteBook            | 3         | 1.68%   |
| Dell OptiPlex           | 3         | 1.68%   |
| Apple iMac9             | 3         | 1.68%   |
| HP EliteDesk            | 2         | 1.12%   |
| ASUS TUF                | 2         | 1.12%   |
| Apple MacBook4          | 2         | 1.12%   |
| Acer V5-131             | 2         | 1.12%   |
| Unknown                 | 2         | 1.12%   |
| TWINHEAD U12CT          | 1         | 0.56%   |
| TUXEDO InfinityBook13V3 | 1         | 0.56%   |
| Samsung N150P           | 1         | 0.56%   |
| Samsung N100            | 1         | 0.56%   |
| Samsung 305E4A          | 1         | 0.56%   |
| Quanta 120-1135         | 1         | 0.56%   |
| Pegatron IPM41-D3       | 1         | 0.56%   |
| Pegatron Compaq         | 1         | 0.56%   |
| Pegatron AY627AA-ABA    | 1         | 0.56%   |
| Notebook N15            | 1         | 0.56%   |
| MSI MS-7D25             | 1         | 0.56%   |
| MSI MS-7B86             | 1         | 0.56%   |
| MSI MS-7A33             | 1         | 0.56%   |
| MSI MS-7758             | 1         | 0.56%   |
| Medion H61H2-LM3        | 1         | 0.56%   |
| Lenovo V310-14IKB       | 1         | 0.56%   |
| Lenovo Legion           | 1         | 0.56%   |
| Lenovo E31-80           | 1         | 0.56%   |
| Intel X58               | 1         | 0.56%   |
| Intel NUC8i3BEH         | 1         | 0.56%   |
| Intel NUC7i3BNK         | 1         | 0.56%   |
| Intel NUC5i3RYH         | 1         | 0.56%   |
| Intel NUC5CPYB          | 1         | 0.56%   |
| Intel NUC10i7FNH        | 1         | 0.56%   |
| Intel H81               | 1         | 0.56%   |
| Intel DH77EB            | 1         | 0.56%   |
| Intel DG41TY            | 1         | 0.56%   |
| Intel DCP847SKE         | 1         | 0.56%   |
| HP ZBook                | 1         | 0.56%   |
| HP Z230                 | 1         | 0.56%   |
| HP ProDesk              | 1         | 0.56%   |
| HP ProBook              | 1         | 0.56%   |
| HP Mini                 | 1         | 0.56%   |
| HP G62                  | 1         | 0.56%   |
| HP 844C                 | 1         | 0.56%   |
| HP 15                   | 1         | 0.56%   |
| Gigabyte Z77X-UD3H      | 1         | 0.56%   |
| Gigabyte Z77N-WIFI      | 1         | 0.56%   |
| Gigabyte Z390           | 1         | 0.56%   |
| Gigabyte X58A-UD5       | 1         | 0.56%   |
| Gigabyte X570           | 1         | 0.56%   |
| Gigabyte P41T-D3        | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 24        | 13.41%  |
| 2019 | 17        | 9.5%    |
| 2018 | 16        | 8.94%   |
| 2013 | 16        | 8.94%   |
| 2010 | 15        | 8.38%   |
| 2017 | 13        | 7.26%   |
| 2015 | 13        | 7.26%   |
| 2012 | 10        | 5.59%   |
| 2020 | 9         | 5.03%   |
| 2014 | 9         | 5.03%   |
| 2009 | 9         | 5.03%   |
| 2016 | 8         | 4.47%   |
| 2011 | 8         | 4.47%   |
| 2008 | 6         | 3.35%   |
| 2007 | 5         | 2.79%   |
| 2006 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 86        | 48.04%  |
| Desktop    | 81        | 45.25%  |
| Mini pc    | 7         | 3.91%   |
| All in one | 5         | 2.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 51        | 28.49%  |
| 4.01-8.0    | 48        | 26.82%  |
| 16.01-24.0  | 41        | 22.91%  |
| 32.01-64.0  | 19        | 10.61%  |
| 2.01-3.0    | 12        | 6.7%    |
| 64.01-256.0 | 4         | 2.23%   |
| 24.01-32.0  | 2         | 1.12%   |
| 3.01-4.0    | 1         | 0.56%   |
| 0.51-1.0    | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 96        | 53.33%  |
| 0.51-1.0  | 51        | 28.33%  |
| 1.01-2.0  | 26        | 14.44%  |
| 2.01-3.0  | 5         | 2.78%   |
| 3.01-4.0  | 1         | 0.56%   |
| 8.01-16.0 | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 97        | 53.89%  |
| 2      | 51        | 28.33%  |
| 3      | 9         | 5%      |
| 4      | 8         | 4.44%   |
| 0      | 8         | 4.44%   |
| 5      | 4         | 2.22%   |
| 6      | 2         | 1.11%   |
| 7      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 62.57%  |
| Yes       | 67        | 37.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 94.97%  |
| No        | 9         | 5.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 69.27%  |
| No        | 55        | 30.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 54.75%  |
| No        | 81        | 45.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 30        | 16.76%  |
| Russia      | 19        | 10.61%  |
| Germany     | 13        | 7.26%   |
| Poland      | 9         | 5.03%   |
| Ukraine     | 8         | 4.47%   |
| Hungary     | 8         | 4.47%   |
| Canada      | 8         | 4.47%   |
| Spain       | 7         | 3.91%   |
| UK          | 6         | 3.35%   |
| Romania     | 6         | 3.35%   |
| Italy       | 6         | 3.35%   |
| France      | 6         | 3.35%   |
| Brazil      | 6         | 3.35%   |
| India       | 4         | 2.23%   |
| Vietnam     | 3         | 1.68%   |
| Peru        | 3         | 1.68%   |
| Netherlands | 3         | 1.68%   |
| Greece      | 3         | 1.68%   |
| Denmark     | 3         | 1.68%   |
| Norway      | 2         | 1.12%   |
| Mexico      | 2         | 1.12%   |
| Indonesia   | 2         | 1.12%   |
| China       | 2         | 1.12%   |
| Chile       | 2         | 1.12%   |
| Australia   | 2         | 1.12%   |
| Turkey      | 1         | 0.56%   |
| Tanzania    | 1         | 0.56%   |
| Taiwan      | 1         | 0.56%   |
| Sweden      | 1         | 0.56%   |
| Portugal    | 1         | 0.56%   |
| Philippines | 1         | 0.56%   |
| Malaysia    | 1         | 0.56%   |
| Lithuania   | 1         | 0.56%   |
| Kazakhstan  | 1         | 0.56%   |
| Georgia     | 1         | 0.56%   |
| Finland     | 1         | 0.56%   |
| Cuba        | 1         | 0.56%   |
| Bulgaria    | 1         | 0.56%   |
| Belarus     | 1         | 0.56%   |
| Austria     | 1         | 0.56%   |
| Argentina   | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Warsaw                        | 3         | 1.65%   |
| St Petersburg                 | 3         | 1.65%   |
| Moscow                        | 3         | 1.65%   |
| Lima                          | 3         | 1.65%   |
| Kharkiv                       | 3         | 1.65%   |
| Hanoi                         | 3         | 1.65%   |
| Tiruchi                       | 2         | 1.1%    |
| Surgut                        | 2         | 1.1%    |
| Suceava                       | 2         | 1.1%    |
| Smiths Falls                  | 2         | 1.1%    |
| Sherwood Park                 | 2         | 1.1%    |
| San SebastiÃ¡n de los Reyes | 2         | 1.1%    |
| Rio de Janeiro                | 2         | 1.1%    |
| Pflugerville                  | 2         | 1.1%    |
| Myrtle Beach                  | 2         | 1.1%    |
| Leatherhead                   | 2         | 1.1%    |
| Katowice                      | 2         | 1.1%    |
| Jakarta                       | 2         | 1.1%    |
| Dreieich                      | 2         | 1.1%    |
| Dijon                         | 2         | 1.1%    |
| Coria del RÃ­o              | 2         | 1.1%    |
| Bucharest                     | 2         | 1.1%    |
| Barnaul                       | 2         | 1.1%    |
| Amsterdam                     | 2         | 1.1%    |
| Zaporizhzhya                  | 1         | 0.55%   |
| Zapopan                       | 1         | 0.55%   |
| Yunlin                        | 1         | 0.55%   |
| Youngsville                   | 1         | 0.55%   |
| Yaphank                       | 1         | 0.55%   |
| Vilnius                       | 1         | 0.55%   |
| VÃ¤sterÃ¥s                | 1         | 0.55%   |
| Ugarchin                      | 1         | 0.55%   |
| Turley                        | 1         | 0.55%   |
| Turin                         | 1         | 0.55%   |
| Torokszentmiklos              | 1         | 0.55%   |
| Thessaloniki                  | 1         | 0.55%   |
| Szeged                        | 1         | 0.55%   |
| SzÃ©kesfehÃ©rvÃ¡r       | 1         | 0.55%   |
| Susanville                    | 1         | 0.55%   |
| Stavropol                     | 1         | 0.55%   |
| Spalice                       | 1         | 0.55%   |
| Sopron                        | 1         | 0.55%   |
| Shah Alam                     | 1         | 0.55%   |
| Seville                       | 1         | 0.55%   |
| Sevastopol                    | 1         | 0.55%   |
| Seattle                       | 1         | 0.55%   |
| Santa Maria                   | 1         | 0.55%   |
| San Luis PotosÃ­ City       | 1         | 0.55%   |
| San Antonio                   | 1         | 0.55%   |
| Riverton                      | 1         | 0.55%   |
| Rho                           | 1         | 0.55%   |
| Renfrew                       | 1         | 0.55%   |
| Ransbach-Baumbach             | 1         | 0.55%   |
| QuÃ©bec                     | 1         | 0.55%   |
| Pruszcz Gdanski               | 1         | 0.55%   |
| Potsdam                       | 1         | 0.55%   |
| Piovene Rocchette             | 1         | 0.55%   |
| Pilica                        | 1         | 0.55%   |
| Penza                         | 1         | 0.55%   |
| Patterson                     | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 62     | 19.03%  |
| Seagate             | 39        | 54     | 14.55%  |
| Samsung Electronics | 38        | 44     | 14.18%  |
| Kingston            | 21        | 23     | 7.84%   |
| Toshiba             | 19        | 22     | 7.09%   |
| Crucial             | 18        | 23     | 6.72%   |
| Intel               | 9         | 10     | 3.36%   |
| Hitachi             | 8         | 8      | 2.99%   |
| SanDisk             | 7         | 8      | 2.61%   |
| A-DATA Technology   | 7         | 7      | 2.61%   |
| SK Hynix            | 5         | 7      | 1.87%   |
| HGST                | 5         | 5      | 1.87%   |
| GOODRAM             | 4         | 4      | 1.49%   |
| XPG                 | 3         | 3      | 1.12%   |
| Phison              | 3         | 3      | 1.12%   |
| Patriot             | 3         | 3      | 1.12%   |
| SPCC                | 2         | 3      | 0.75%   |
| OCZ                 | 2         | 2      | 0.75%   |
| Mushkin             | 2         | 2      | 0.75%   |
| KingSpec            | 2         | 2      | 0.75%   |
| Gigabyte Technology | 2         | 3      | 0.75%   |
| Fujitsu             | 2         | 2      | 0.75%   |
| Apple               | 2         | 2      | 0.75%   |
| Apacer              | 2         | 2      | 0.75%   |
| Transcend           | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| PNY                 | 1         | 1      | 0.37%   |
| PLEXTOR             | 1         | 1      | 0.37%   |
| Micron Technology   | 1         | 1      | 0.37%   |
| Lite-On             | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| Integral            | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| Corsair             | 1         | 1      | 0.37%   |
| China               | 1         | 1      | 0.37%   |
| AGI                 | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB             | 7         | 2.4%    |
| Crucial CT500MX500SSD1 500GB            | 6         | 2.05%   |
| HGST HTS545050A7E680 500GB              | 4         | 1.37%   |
| XPG GAMMIX S11 Pro 256GB                | 3         | 1.03%   |
| WDC WDS240G2G0A-00JH30 240GB            | 3         | 1.03%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 3         | 1.03%   |
| Toshiba MQ01ABF050 500GB                | 3         | 1.03%   |
| Seagate ST4000DM004-2CV104 4TB          | 3         | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.03%   |
| Samsung SSD 860 EVO 500GB               | 3         | 1.03%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.03%   |
| Kingston SA400S37240G 240GB             | 3         | 1.03%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.03%   |
| Crucial CT120BX500SSD1 120GB            | 3         | 1.03%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 2         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB            | 2         | 0.68%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.68%   |
| WDC WD20PURZ-85GU6Y0 2TB                | 2         | 0.68%   |
| SK Hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.68%   |
| Seagate ST3500413AS 500GB               | 2         | 0.68%   |
| Seagate ST3320418AS 320GB               | 2         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 0.68%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 0.68%   |
| Samsung SSD 980 PRO 1TB                 | 2         | 0.68%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.68%   |
| Samsung SSD 970 EVO 250GB               | 2         | 0.68%   |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.68%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.68%   |
| Samsung Portable SSD T5 500GB           | 2         | 0.68%   |
| Samsung MZVLW256HEHP-000L7 256GB        | 2         | 0.68%   |
| Hitachi HTS541680J9SA00 80GB            | 2         | 0.68%   |
| GOODRAM SSDPR-CL100-120-G2 120GB        | 2         | 0.68%   |
| Crucial CT256MX100SSD1 256GB            | 2         | 0.68%   |
| A-DATA SP550 240GB                      | 2         | 0.68%   |
| WDC WDS500G2B0B-00YS70 500GB            | 1         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1         | 0.34%   |
| WDC WDS250G1B0A-00H9H0 250GB            | 1         | 0.34%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB              | 1         | 0.34%   |
| WDC WDBNCE5000PNC 500GB                 | 1         | 0.34%   |
| WDC WDBA3V0010BNC-WRSN 1TB              | 1         | 0.34%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 0.34%   |
| WDC WD5000LPLX-60ZNTT1 500GB            | 1         | 0.34%   |
| WDC WD5000LPCX-75VHAT0 500GB            | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.34%   |
| WDC WD5000BPKX-22HPJT0 500GB            | 1         | 0.34%   |
| WDC WD5000AZLX-00CL5A0 500GB            | 1         | 0.34%   |
| WDC WD5000AAKS-22A7B0 500GB             | 1         | 0.34%   |
| WDC WD40EZRZ-00GXCB0 4TB                | 1         | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB                | 1         | 0.34%   |
| WDC WD4004FZWX-00GBGB0 4TB              | 1         | 0.34%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 0.34%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 0.34%   |
| WDC WD3200AAJS-22B4A0 320GB             | 1         | 0.34%   |
| WDC WD3003FZEX-00Z4SA0 3TB              | 1         | 0.34%   |
| WDC WD2500AAKX-75U6AA0 250GB            | 1         | 0.34%   |
| WDC WD2500AAKX-073CA1 250GB             | 1         | 0.34%   |
| WDC WD1600BEVT-80A23T0 160GB            | 1         | 0.34%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 50     | 34.23%  |
| WDC                 | 37        | 43     | 33.33%  |
| Toshiba             | 16        | 19     | 14.41%  |
| Hitachi             | 8         | 8      | 7.21%   |
| Samsung Electronics | 5         | 5      | 4.5%    |
| HGST                | 5         | 5      | 4.5%    |
| Fujitsu             | 1         | 1      | 0.9%    |
| Apple               | 1         | 1      | 0.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 23     | 18.49%  |
| Crucial             | 18        | 22     | 15.13%  |
| Kingston            | 17        | 17     | 14.29%  |
| WDC                 | 9         | 12     | 7.56%   |
| SanDisk             | 7         | 8      | 5.88%   |
| Intel               | 6         | 6      | 5.04%   |
| A-DATA Technology   | 6         | 6      | 5.04%   |
| GOODRAM             | 4         | 4      | 3.36%   |
| Patriot             | 3         | 3      | 2.52%   |
| Toshiba             | 2         | 2      | 1.68%   |
| SPCC                | 2         | 3      | 1.68%   |
| SK Hynix            | 2         | 2      | 1.68%   |
| OCZ                 | 2         | 2      | 1.68%   |
| KingSpec            | 2         | 2      | 1.68%   |
| Gigabyte Technology | 2         | 3      | 1.68%   |
| Apacer              | 2         | 2      | 1.68%   |
| Transcend           | 1         | 1      | 0.84%   |
| Team                | 1         | 1      | 0.84%   |
| PNY                 | 1         | 1      | 0.84%   |
| PLEXTOR             | 1         | 1      | 0.84%   |
| Mushkin             | 1         | 1      | 0.84%   |
| Lite-On             | 1         | 1      | 0.84%   |
| Intenso             | 1         | 1      | 0.84%   |
| Integral            | 1         | 1      | 0.84%   |
| Hewlett-Packard     | 1         | 1      | 0.84%   |
| Fujitsu             | 1         | 1      | 0.84%   |
| Corsair             | 1         | 1      | 0.84%   |
| China               | 1         | 1      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 98        | 130    | 41.7%   |
| HDD  | 95        | 132    | 40.43%  |
| NVMe | 42        | 54     | 17.87%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 157       | 262    | 78.89%  |
| NVMe | 42        | 54     | 21.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 183    | 68.72%  |
| 0.51-1.0   | 36        | 45     | 18.46%  |
| 1.01-2.0   | 14        | 15     | 7.18%   |
| 3.01-4.0   | 7         | 14     | 3.59%   |
| 2.01-3.0   | 3         | 4      | 1.54%   |
| 4.01-10.0  | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 106       | 58.56%  |
| 101-250    | 35        | 19.34%  |
| 251-500    | 24        | 13.26%  |
| 501-1000   | 7         | 3.87%   |
| 21-50      | 5         | 2.76%   |
| 51-100     | 4         | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 179       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST3500413AS 500GB           | 2         | 2      | 3.85%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2      | 3.85%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 1.92%   |
| WDC WD5000AAKS-22A7B0 500GB         | 1         | 1      | 1.92%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.92%   |
| WDC WD3200AAJS-22B4A0 320GB         | 1         | 1      | 1.92%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 1.92%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 1.92%   |
| WDC WD1600BEKT-66F3T2 160GB         | 1         | 1      | 1.92%   |
| WDC WD10EZEX-08M2NA0 1TB            | 1         | 1      | 1.92%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 1.92%   |
| Toshiba THNSNX024GMNT 24GB          | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 1.92%   |
| Toshiba MK8034GSX 80GB              | 1         | 1      | 1.92%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.92%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.92%   |
| Toshiba MD04ACA400 4TB              | 1         | 1      | 1.92%   |
| Toshiba DT01ACA100 1TB              | 1         | 3      | 1.92%   |
| Toshiba DT01ABA300 3TB              | 1         | 1      | 1.92%   |
| Seagate ST9640320AS 640GB           | 1         | 1      | 1.92%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 1.92%   |
| Seagate ST380211AS 80GB             | 1         | 1      | 1.92%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 1.92%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.92%   |
| Seagate ST3160812AS 160GB           | 1         | 1      | 1.92%   |
| Seagate ST31000528AS 1TB            | 1         | 2      | 1.92%   |
| Samsung Electronics SSD 870 EVO 1TB | 1         | 1      | 1.92%   |
| Samsung Electronics SSD 860 EVO 1TB | 1         | 1      | 1.92%   |
| Samsung Electronics HS082HB 80GB    | 1         | 1      | 1.92%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 1.92%   |
| Samsung Electronics HD322HJ 320GB   | 1         | 1      | 1.92%   |
| Kingston SV200S3128G 128GB          | 1         | 1      | 1.92%   |
| Kingston SMS200S3120G 120GB         | 1         | 1      | 1.92%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 1.92%   |
| Hitachi HTS543232L9SA02 320GB       | 1         | 1      | 1.92%   |
| Hitachi HTS542516K9SA00 160GB       | 1         | 1      | 1.92%   |
| Hitachi HTS541680J9SA00 80GB        | 1         | 1      | 1.92%   |
| Hitachi HDT721064SLA360 640GB       | 1         | 1      | 1.92%   |
| Hitachi HDT721010SLA360 1TB         | 1         | 1      | 1.92%   |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 1.92%   |
| Crucial CT240M500SSD1 240GB         | 1         | 1      | 1.92%   |
| AGI AGI512G16AI198 512GB            | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 26%     |
| Seagate             | 12        | 14     | 24%     |
| Toshiba             | 9         | 12     | 18%     |
| Hitachi             | 6         | 6      | 12%     |
| Samsung Electronics | 5         | 5      | 10%     |
| Kingston            | 2         | 2      | 4%      |
| HGST                | 1         | 1      | 2%      |
| Crucial             | 1         | 1      | 2%      |
| AGI                 | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 13     | 30.23%  |
| Seagate             | 12        | 14     | 27.91%  |
| Toshiba             | 8         | 11     | 18.6%   |
| Hitachi             | 6         | 6      | 13.95%  |
| Samsung Electronics | 3         | 3      | 6.98%   |
| HGST                | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 48     | 85.42%  |
| SSD  | 6         | 6      | 12.5%   |
| NVMe | 1         | 1      | 2.08%   |

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
| Works    | 141       | 258    | 73.82%  |
| Malfunc  | 47        | 55     | 24.61%  |
| Detected | 3         | 3      | 1.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 139       | 61.78%  |
| AMD                         | 26        | 11.56%  |
| Samsung Electronics         | 14        | 6.22%   |
| Nvidia                      | 9         | 4%      |
| Sandisk                     | 6         | 2.67%   |
| Kingston Technology Company | 4         | 1.78%   |
| ADATA Technology            | 4         | 1.78%   |
| SK Hynix                    | 3         | 1.33%   |
| Phison Electronics          | 3         | 1.33%   |
| JMicron Technology          | 3         | 1.33%   |
| ASMedia Technology          | 3         | 1.33%   |
| Silicon Motion              | 2         | 0.89%   |
| Seagate Technology          | 2         | 0.89%   |
| Marvell Technology Group    | 2         | 0.89%   |
| VIA Technologies            | 1         | 0.44%   |
| Micron/Crucial Technology   | 1         | 0.44%   |
| Micron Technology           | 1         | 0.44%   |
| KIOXIA                      | 1         | 0.44%   |
| Apple                       | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 4.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 4.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 3.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 7         | 2.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.77%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 2.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.37%   |
| Nvidia MCP79 AHCI Controller                                                     | 6         | 2.37%   |
| Intel SATA Controller [RAID mode]                                                | 6         | 2.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 2.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 1.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.98%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 1.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 4         | 1.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 1.19%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.19%   |
| Unknown                                                                          | 3         | 1.19%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.79%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.79%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.79%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.79%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.79%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 2         | 0.79%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.79%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 2         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 0.79%   |
| AMD X370 Series Chipset SATA Controller                                          | 2         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.79%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.4%    |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.4%    |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.4%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.4%    |
| Seagate FireCuda 520 SSD                                                         | 1         | 0.4%    |
| Seagate FireCuda 510 SSD                                                         | 1         | 0.4%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.4%    |
| Sandisk unknown                                                                  | 1         | 0.4%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.4%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.4%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 149       | 66.52%  |
| NVMe | 43        | 19.2%   |
| IDE  | 23        | 10.27%  |
| RAID | 9         | 4.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 148       | 82.68%  |
| AMD    | 31        | 17.32%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 2.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 1.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.68%   |
| Intel CPU Version                           | 2         | 1.12%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.12%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.12%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.12%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.12%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 2         | 1.12%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 2         | 1.12%   |
| Intel Core 2 Duo                            | 2         | 1.12%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 2         | 1.12%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.12%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 2         | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.12%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2         | 1.12%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 1.12%   |
| Intel Xeon E-2136 CPU @ 3.30GHz             | 1         | 0.56%   |
| Intel Xeon CPU X5647 @ 2.93GHz              | 1         | 0.56%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1         | 0.56%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1         | 0.56%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1         | 0.56%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz        | 1         | 0.56%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.56%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.56%   |
| Intel Xeon CPU E3-1225 v3 @ 3.20GHz         | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E6500 @         | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1         | 0.56%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.56%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.56%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.56%   |
| Intel Pentium CPU G860 @ 3.00GHz            | 1         | 0.56%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.56%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 0.56%   |
| Intel Core i9-9900 CPU @ 3.10GHz            | 1         | 0.56%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.56%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.56%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.56%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.56%   |
| Intel Core i7-6700T CPU @ 2.80GHz           | 1         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.56%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.56%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.56%   |
| Intel Core i7-10710U CPU @ 1.10GHz          | 1         | 0.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.56%   |
| Intel Core i7 CPU                           | 1         | 0.56%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49        | 27.37%  |
| Intel Core i7           | 21        | 11.73%  |
| Intel Core i3           | 20        | 11.17%  |
| Intel Core 2 Duo        | 17        | 9.5%    |
| Intel Celeron           | 10        | 5.59%   |
| AMD Ryzen 5             | 10        | 5.59%   |
| Intel Xeon              | 9         | 5.03%   |
| AMD Ryzen 7             | 7         | 3.91%   |
| Other                   | 4         | 2.23%   |
| Intel Pentium Dual-Core | 4         | 2.23%   |
| Intel Pentium           | 4         | 2.23%   |
| Intel Atom              | 4         | 2.23%   |
| Intel Core 2            | 2         | 1.12%   |
| AMD Ryzen 9             | 2         | 1.12%   |
| AMD Ryzen 3             | 2         | 1.12%   |
| AMD E2                  | 2         | 1.12%   |
| AMD A6                  | 2         | 1.12%   |
| Intel Pentium Dual      | 1         | 0.56%   |
| Intel Core M            | 1         | 0.56%   |
| Intel Core i9           | 1         | 0.56%   |
| Intel Core 2 Quad       | 1         | 0.56%   |
| AMD Ryzen Threadripper  | 1         | 0.56%   |
| AMD Phenom II X4        | 1         | 0.56%   |
| AMD FX                  | 1         | 0.56%   |
| AMD E                   | 1         | 0.56%   |
| AMD Athlon II X2        | 1         | 0.56%   |
| AMD A10                 | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 75        | 41.9%   |
| 4       | 45        | 25.14%  |
| Unknown | 22        | 12.29%  |
| 6       | 13        | 7.26%   |
| 8       | 7         | 3.91%   |
| 16      | 6         | 3.35%   |
| 12      | 6         | 3.35%   |
| 24      | 2         | 1.12%   |
| 64      | 1         | 0.56%   |
| 14      | 1         | 0.56%   |
| 1       | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 167       | 93.3%   |
| 2       | 10        | 5.59%   |
| Unknown | 2         | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 85        | 47.49%  |
| 1       | 72        | 40.22%  |
| Unknown | 22        | 12.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 24        | 13.41%  |
| Penryn      | 20        | 11.17%  |
| IvyBridge   | 18        | 10.06%  |
| Haswell     | 16        | 8.94%   |
| Skylake     | 15        | 8.38%   |
| Westmere    | 12        | 6.7%    |
| SandyBridge | 12        | 6.7%    |
| Zen 2       | 7         | 3.91%   |
| Core        | 7         | 3.91%   |
| Zen+        | 6         | 3.35%   |
| Silvermont  | 6         | 3.35%   |
| Broadwell   | 6         | 3.35%   |
| Zen 3       | 5         | 2.79%   |
| Zen         | 4         | 2.23%   |
| Bonnell     | 4         | 2.23%   |
| CometLake   | 3         | 1.68%   |
| Piledriver  | 2         | 1.12%   |
| Nehalem     | 2         | 1.12%   |
| K10         | 2         | 1.12%   |
| Excavator   | 2         | 1.12%   |
| Unknown     | 2         | 1.12%   |
| K10 Llano   | 1         | 0.56%   |
| Jaguar      | 1         | 0.56%   |
| Goldmont    | 1         | 0.56%   |
| Bobcat      | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 103       | 52.55%  |
| Nvidia | 57        | 29.08%  |
| AMD    | 36        | 18.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.48%   |
| Intel HD Graphics 620                                                                    | 6         | 2.99%   |
| Intel HD Graphics 530                                                                    | 6         | 2.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 2.49%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 2.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.99%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.49%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.49%   |
| Nvidia C79 [GeForce 9400]                                                                | 3         | 1.49%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.49%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.49%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 1.49%   |
| Nvidia TU117M                                                                            | 2         | 1%      |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 1%      |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 1%      |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1%      |
| Intel HD Graphics 630                                                                    | 2         | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1%      |
| AMD Cezanne                                                                              | 2         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.5%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.5%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.5%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.5%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.5%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.5%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 1         | 0.5%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.5%    |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.5%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.5%    |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.5%    |
| Nvidia GK107GL [Quadro K2000]                                                            | 1         | 0.5%    |
| Nvidia GK107 [GeForce GT 740]                                                            | 1         | 0.5%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.5%    |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.5%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.5%    |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 43.02%  |
| 1 x Nvidia     | 45        | 25.14%  |
| 1 x AMD        | 29        | 16.2%   |
| 2 x Intel      | 11        | 6.15%   |
| Intel + Nvidia | 10        | 5.59%   |
| Intel + AMD    | 5         | 2.79%   |
| AMD + Nvidia   | 2         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 136       | 75.56%  |
| Proprietary | 41        | 22.78%  |
| Unknown     | 3         | 1.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 63.33%  |
| 0.01-0.5   | 17        | 9.44%   |
| 1.01-2.0   | 14        | 7.78%   |
| 3.01-4.0   | 12        | 6.67%   |
| 0.51-1.0   | 11        | 6.11%   |
| 7.01-8.0   | 9         | 5%      |
| 5.01-6.0   | 3         | 1.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 14.12%  |
| LG Display              | 17        | 9.6%    |
| AU Optronics            | 15        | 8.47%   |
| Chimei Innolux          | 12        | 6.78%   |
| Lenovo                  | 11        | 6.21%   |
| BOE                     | 11        | 6.21%   |
| BenQ                    | 11        | 6.21%   |
| Dell                    | 10        | 5.65%   |
| Apple                   | 10        | 5.65%   |
| Goldstar                | 9         | 5.08%   |
| AOC                     | 8         | 4.52%   |
| Philips                 | 6         | 3.39%   |
| Acer                    | 6         | 3.39%   |
| Hewlett-Packard         | 5         | 2.82%   |
| Ancor Communications    | 5         | 2.82%   |
| Sony                    | 3         | 1.69%   |
| ASUSTek Computer        | 2         | 1.13%   |
| Westinghouse            | 1         | 0.56%   |
| Toshiba                 | 1         | 0.56%   |
| SGT                     | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| Medion                  | 1         | 0.56%   |
| Lenovo Group Limited    | 1         | 0.56%   |
| LED                     | 1         | 0.56%   |
| Iiyama                  | 1         | 0.56%   |
| Fujitsu Siemens         | 1         | 0.56%   |
| Denver                  | 1         | 0.56%   |
| Chi Mei Optoelectronics | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 240x130mm 10.7-inch  | 2         | 1.1%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 2         | 1.1%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 2         | 1.1%    |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 1.1%    |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 1.1%    |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                      | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 1.1%    |
| Apple Color LCD APP9C93 1680x1050 430x270mm 20.0-inch                  | 2         | 1.1%    |
| Westinghouse LCM-19w4 WDE1904 1440x900 410x260mm 19.1-inch             | 1         | 0.55%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.55%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.55%   |
| Sony TV SNY9C01 1360x768                                               | 1         | 0.55%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1         | 0.55%   |
| SGT YSD SGT1700 1280x1024 380x210mm 17.1-inch                          | 1         | 0.55%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.55%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 520x290mm 23.4-inch      | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                       | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0373 1680x1050 440x300mm 21.0-inch   | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.55%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 1         | 0.55%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.55%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.55%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch      | 1         | 0.55%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.55%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 1         | 0.55%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 530x300mm 24.0-inch     | 1         | 0.55%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 700x390mm 31.5-inch      | 1         | 0.55%   |
| Samsung Electronics C24FG7x SAM0E44 1920x1080 530x300mm 24.0-inch      | 1         | 0.55%   |
| Philips PHL 278E1 PHLC217 3840x2160 600x340mm 27.2-inch                | 1         | 0.55%   |
| Philips 248CLH PHLC088 1920x1080 520x290mm 23.4-inch                   | 1         | 0.55%   |
| Philips 220E PHLC02E 1920x1080 470x260mm 21.1-inch                     | 1         | 0.55%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                      | 1         | 0.55%   |
| NEC Computers LCD1770VX NEC6696 1280x1024 340x270mm 17.1-inch          | 1         | 0.55%   |
| Medion MD 20160 MED3625 1920x1080 520x290mm 23.4-inch                  | 1         | 0.55%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD03DF 1366x768 340x190mm 15.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD0324 1280x800 220x140mm 10.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch            | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 36.42%  |
| 1366x768 (WXGA)    | 42        | 24.28%  |
| 1280x800 (WXGA)    | 12        | 6.94%   |
| 2560x1440 (QHD)    | 8         | 4.62%   |
| 1280x1024 (SXGA)   | 8         | 4.62%   |
| 3840x2160 (4K)     | 7         | 4.05%   |
| 1920x1200 (WUXGA)  | 7         | 4.05%   |
| 1600x900 (HD+)     | 7         | 4.05%   |
| 1440x900 (WXGA+)   | 6         | 3.47%   |
| 1680x1050 (WSXGA+) | 5         | 2.89%   |
| 3440x1440          | 2         | 1.16%   |
| 1024x600           | 2         | 1.16%   |
| 2560x1080          | 1         | 0.58%   |
| 1920x540           | 1         | 0.58%   |
| 1360x768           | 1         | 0.58%   |
| 1024x768 (XGA)     | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 17.22%  |
| 13      | 24        | 13.33%  |
| 24      | 22        | 12.22%  |
| 27      | 13        | 7.22%   |
| 23      | 12        | 6.67%   |
| 21      | 11        | 6.11%   |
| 19      | 11        | 6.11%   |
| 12      | 10        | 5.56%   |
| 17      | 7         | 3.89%   |
| 18      | 6         | 3.33%   |
| 31      | 5         | 2.78%   |
| 14      | 5         | 2.78%   |
| 11      | 4         | 2.22%   |
| Unknown | 4         | 2.22%   |
| 20      | 3         | 1.67%   |
| 10      | 3         | 1.67%   |
| 34      | 2         | 1.11%   |
| 16      | 2         | 1.11%   |
| 54      | 1         | 0.56%   |
| 50      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 33      | 1         | 0.56%   |
| 29      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 28.41%  |
| 501-600     | 43        | 24.43%  |
| 201-300     | 31        | 17.61%  |
| 401-500     | 24        | 13.64%  |
| 351-400     | 11        | 6.25%   |
| 601-700     | 7         | 3.98%   |
| Unknown     | 4         | 2.27%   |
| 701-800     | 3         | 1.7%    |
| 1001-1500   | 2         | 1.14%   |
| 801-900     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 74.1%   |
| 16/10   | 28        | 16.87%  |
| 5/4     | 6         | 3.61%   |
| 3/2     | 3         | 1.81%   |
| 21/9    | 3         | 1.81%   |
| 4/3     | 2         | 1.2%    |
| Unknown | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 34        | 18.99%  |
| 91-100         | 26        | 14.53%  |
| 81-90          | 24        | 13.41%  |
| 151-200        | 18        | 10.06%  |
| 301-350        | 13        | 7.26%   |
| 61-70          | 10        | 5.59%   |
| 251-300        | 10        | 5.59%   |
| 351-500        | 8         | 4.47%   |
| 141-150        | 6         | 3.35%   |
| 101-110        | 6         | 3.35%   |
| 121-130        | 5         | 2.79%   |
| 71-80          | 4         | 2.23%   |
| 51-60          | 4         | 2.23%   |
| Unknown        | 4         | 2.23%   |
| 41-50          | 3         | 1.68%   |
| More than 1000 | 2         | 1.12%   |
| 111-120        | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 71        | 39.89%  |
| 101-120 | 54        | 30.34%  |
| 121-160 | 42        | 23.6%   |
| 161-240 | 6         | 3.37%   |
| Unknown | 4         | 2.25%   |
| 1-50    | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 149       | 82.32%  |
| 2     | 19        | 10.5%   |
| 0     | 12        | 6.63%   |
| 3     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 90        | 34.35%  |
| Realtek Semiconductor             | 89        | 33.97%  |
| Broadcom                          | 29        | 11.07%  |
| Qualcomm Atheros                  | 25        | 9.54%   |
| Nvidia                            | 6         | 2.29%   |
| Marvell Technology Group          | 4         | 1.53%   |
| NetGear                           | 3         | 1.15%   |
| TP-Link                           | 2         | 0.76%   |
| Ralink Technology                 | 2         | 0.76%   |
| Ralink                            | 2         | 0.76%   |
| Dell                              | 2         | 0.76%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Microchip Technology              | 1         | 0.38%   |
| Mercucys                          | 1         | 0.38%   |
| JMicron Technology                | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Google                            | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.75%   |
| Intel I211 Gigabit Network Connection                             | 8         | 2.5%    |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.19%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.88%   |
| Intel Wireless 8260                                               | 6         | 1.88%   |
| Intel Wireless 7265                                               | 6         | 1.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.56%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.56%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.25%   |
| Intel Wireless 7260                                               | 4         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.25%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.25%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 0.94%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.63%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 2         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.63%   |
| Intel Wireless-AC 9260                                            | 2         | 0.63%   |
| Intel Wireless 3165                                               | 2         | 0.63%   |
| Intel WiFi Link 5100                                              | 2         | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.63%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                     | 1         | 0.31%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.31%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.31%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.31%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 47.79%  |
| Broadcom              | 21        | 15.44%  |
| Realtek Semiconductor | 19        | 13.97%  |
| Qualcomm Atheros      | 19        | 13.97%  |
| NetGear               | 3         | 2.21%   |
| TP-Link               | 2         | 1.47%   |
| Ralink Technology     | 2         | 1.47%   |
| Ralink                | 2         | 1.47%   |
| Sierra Wireless       | 1         | 0.74%   |
| Mercucys              | 1         | 0.74%   |
| Dell                  | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 7         | 5.04%   |
| Intel Wireless 8260                                              | 6         | 4.32%   |
| Intel Wireless 7265                                              | 6         | 4.32%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller           | 6         | 4.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 5         | 3.6%    |
| Intel Wi-Fi 6 AX200                                              | 5         | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 5         | 3.6%    |
| Intel Wireless 8265 / 8275                                       | 4         | 2.88%   |
| Intel Wireless 7260                                              | 4         | 2.88%   |
| Intel Centrino Advanced-N 6200                                   | 4         | 2.88%   |
| Broadcom BCM4321 802.11a/b/g/n                                   | 4         | 2.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 3         | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 3         | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter              | 3         | 2.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                          | 3         | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 3         | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 3         | 2.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 3         | 2.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 3         | 2.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                     | 3         | 2.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                  | 3         | 2.16%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                              | 2         | 1.44%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 2         | 1.44%   |
| Realtek Realtek Bluetooth 4.2 Adapter                            | 2         | 1.44%   |
| Intel Wireless-AC 9260                                           | 2         | 1.44%   |
| Intel Wireless 3165                                              | 2         | 1.44%   |
| Intel WiFi Link 5100                                             | 2         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 2         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 2         | 1.44%   |
| Intel Centrino Ultimate-N 6300                                   | 2         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                  | 2         | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter              | 2         | 1.44%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                    | 1         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter         | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                           | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                     | 1         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                   | 1         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                            | 1         | 0.72%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                        | 1         | 0.72%   |
| Ralink RT2500 Wireless 802.11bg                                  | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)   | 1         | 0.72%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                  | 1         | 0.72%   |
| NetGear WN111(v2) RangeMax Next Wireless [Atheros AR9170+AR9101] | 1         | 0.72%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]      | 1         | 0.72%   |
| Mercucys MERCUSYS Wireless USB Adapter                           | 1         | 0.72%   |
| Intel Wireless 3160                                              | 1         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                  | 1         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection    | 1         | 0.72%   |
| Intel Centrino Wireless-N 2230                                   | 1         | 0.72%   |
| Intel Centrino Wireless-N 100                                    | 1         | 0.72%   |
| Intel Centrino Advanced-N 6235                                   | 1         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 1         | 0.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                                 | 1         | 0.72%   |
| Dell Hub of E-Port Replicator                                    | 1         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                      | 1         | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter               | 1         | 0.72%   |
| Broadcom BCM43228 802.11a/b/g/n                                  | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 80        | 45.98%  |
| Intel                    | 64        | 36.78%  |
| Broadcom                 | 10        | 5.75%   |
| Qualcomm Atheros         | 8         | 4.6%    |
| Nvidia                   | 6         | 3.45%   |
| Marvell Technology Group | 4         | 2.3%    |
| JMicron Technology       | 1         | 0.57%   |
| Google                   | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 64        | 36.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 12        | 6.82%   |
| Intel I211 Gigabit Network Connection                                         | 8         | 4.55%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8         | 4.55%   |
| Nvidia MCP79 Ethernet                                                         | 6         | 3.41%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.27%   |
| Intel 82579V Gigabit Network Connection                                       | 4         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 2.27%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.7%    |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 1.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 2         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 1.14%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 1.14%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 1.14%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                          | 2         | 1.14%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 1.14%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 2         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 1         | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 1         | 0.57%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.57%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.57%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.57%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.57%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.57%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.57%   |
| Intel 82566MM Gigabit Network Connection                                      | 1         | 0.57%   |
| Google Nexus/Pixel Device (tether)                                            | 1         | 0.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                             | 1         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 1         | 0.57%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                      | 1         | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                        | 1         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 170       | 56.86%  |
| WiFi     | 124       | 41.47%  |
| Unknown  | 3         | 1%      |
| Modem    | 2         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 62.31%  |
| WiFi     | 98        | 36.57%  |
| Unknown  | 3         | 1.12%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 58.1%   |
| 1     | 65        | 36.31%  |
| 3     | 5         | 2.79%   |
| 4     | 3         | 1.68%   |
| 0     | 2         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 169       | 94.41%  |
| Yes  | 10        | 5.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 41.84%  |
| Apple                           | 13        | 13.27%  |
| Broadcom                        | 9         | 9.18%   |
| Cambridge Silicon Radio         | 8         | 8.16%   |
| Qualcomm Atheros Communications | 6         | 6.12%   |
| Realtek Semiconductor           | 5         | 5.1%    |
| IMC Networks                    | 4         | 4.08%   |
| Lite-On Technology              | 2         | 2.04%   |
| Hewlett-Packard                 | 2         | 2.04%   |
| Foxconn / Hon Hai               | 2         | 2.04%   |
| Dell                            | 2         | 2.04%   |
| ASUSTek Computer                | 2         | 2.04%   |
| Integrated System Solution      | 1         | 1.02%   |
| HTC (High Tech Computer)        | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 23        | 23%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8         | 8%      |
| Intel AX200 Bluetooth                                                | 5         | 5%      |
| Broadcom BCM2045B (BDC-2.1)                                          | 5         | 5%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 4%      |
| Intel AX201 Bluetooth                                                | 4         | 4%      |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                              | 3         | 3%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3         | 3%      |
| Apple Built-in iSight (no firmware loaded)                           | 3         | 3%      |
| Realtek Bluetooth Radio                                              | 2         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 2%      |
| Apple Bluetooth Host Controller                                      | 2         | 2%      |
| Apple Apple Broadcom Built-in Bluetooth                              | 2         | 2%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device          | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 1%      |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)                      | 1         | 1%      |
| Lite-On Realtek Bluetooth Adapter                                    | 1         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                     | 1         | 1%      |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1         | 1%      |
| IMC Networks Realtek Bluetooth Adapter                               | 1         | 1%      |
| IMC Networks Realtek Bluetooth 4.0 Adapter                           | 1         | 1%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 1%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                    | 1         | 1%      |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                                     | 1         | 1%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1         | 1%      |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0                     | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Module                               | 1         | 1%      |
| Dell DW375 Bluetooth Module                                          | 1         | 1%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 1         | 1%      |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1%      |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 1         | 1%      |
| ASUS Bluetooth Controller                                            | 1         | 1%      |
| ASUS ASUS USB-BT500                                                  | 1         | 1%      |
| Apple Broadcom Bluetooth 2.1 module                                  | 1         | 1%      |
| Apple Bluetooth USB Host Controller                                  | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 137       | 54.15%  |
| Nvidia                    | 45        | 17.79%  |
| AMD                       | 40        | 15.81%  |
| C-Media Electronics       | 6         | 2.37%   |
| GN Netcom                 | 5         | 1.98%   |
| Texas Instruments         | 4         | 1.58%   |
| Logitech                  | 2         | 0.79%   |
| Yamaha                    | 1         | 0.4%    |
| VIA Technologies          | 1         | 0.4%    |
| SteelSeries ApS           | 1         | 0.4%    |
| Sennheiser Communications | 1         | 0.4%    |
| Nektar                    | 1         | 0.4%    |
| KORG                      | 1         | 0.4%    |
| Kingston Technology       | 1         | 0.4%    |
| JMTek                     | 1         | 0.4%    |
| Focusrite-Novation        | 1         | 0.4%    |
| Creative Technology       | 1         | 0.4%    |
| Creative Labs             | 1         | 0.4%    |
| Corsair                   | 1         | 0.4%    |
| Cambridge Silicon Radio   | 1         | 0.4%    |
| ASUSTek Computer          | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 6.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 3.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 2.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 2.08%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.74%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 1.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.39%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.04%   |
| AMD Navi 10 HDMI Audio                                                                            | 3         | 1.04%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.04%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2         | 0.69%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.69%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.69%   |
| GN Netcom Jabra SPEAK 510 USB                                                                     | 2         | 0.69%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs                                  | 2         | 0.69%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.69%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.69%   |
| Yamaha Steinberg UR12                                                                             | 1         | 0.35%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.35%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.35%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.35%   |
| SteelSeries ApS SteelSeries Arctis 5 Arctis 5 Chat Arctis 5 Game                                  | 1         | 0.35%   |
| Sennheiser Communications Sennheiser 3D G4ME1                                                     | 1         | 0.35%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 19.7%   |
| Kingston            | 28        | 14.14%  |
| SK Hynix            | 26        | 13.13%  |
| Unknown             | 23        | 11.62%  |
| Crucial             | 13        | 6.57%   |
| Micron Technology   | 11        | 5.56%   |
| Corsair             | 11        | 5.56%   |
| G.Skill             | 9         | 4.55%   |
| Ramaxel Technology  | 5         | 2.53%   |
| Nanya Technology    | 5         | 2.53%   |
| Team                | 3         | 1.52%   |
| Elpida              | 3         | 1.52%   |
| Unknown             | 3         | 1.52%   |
| Patriot             | 2         | 1.01%   |
| AMD                 | 2         | 1.01%   |
| A-DATA Technology   | 2         | 1.01%   |
| 48spaces            | 2         | 1.01%   |
| Unifosa             | 1         | 0.51%   |
| Smart               | 1         | 0.51%   |
| Silicon Power       | 1         | 0.51%   |
| Sesame              | 1         | 0.51%   |
| Kingmax             | 1         | 0.51%   |
| Hikvision           | 1         | 0.51%   |
| GOODRAM             | 1         | 0.51%   |
| Goldkey             | 1         | 0.51%   |
| Avant               | 1         | 0.51%   |
| Atermiter           | 1         | 0.51%   |
| Apacer              | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 1.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.9%    |
| Unknown                                                                   | 3         | 1.42%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                       | 2         | 0.95%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 2         | 0.95%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 2         | 0.95%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.95%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 2         | 0.95%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                          | 2         | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 0.95%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.95%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.95%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s                    | 2         | 0.95%   |
| Crucial RAM BL16G32C16U4B.16FE 16GB DIMM DDR4 3200MT/s                    | 2         | 0.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                     | 2         | 0.95%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.95%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 800MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM SDRAM 533MT/s                                 | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                  | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2                                          | 1         | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 1         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                  | 1         | 0.47%   |
| Unknown RAM Module 1GB DIMM DDR2 333MT/s                                  | 1         | 0.47%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                         | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s                       | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s                        | 1         | 0.47%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                        | 1         | 0.47%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.47%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.47%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                              | 1         | 0.47%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                              | 1         | 0.47%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                                | 1         | 0.47%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.47%   |
| SK Hynix RAM Module 1GB SODIMM DDR3 1067MT/s                              | 1         | 0.47%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.47%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.47%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3 1600MT/s                     | 1         | 0.47%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.47%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| SK Hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s                      | 1         | 0.47%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 85        | 49.13%  |
| DDR4    | 61        | 35.26%  |
| DDR2    | 18        | 10.4%   |
| SDRAM   | 3         | 1.73%   |
| Unknown | 3         | 1.73%   |
| LPDDR3  | 2         | 1.16%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 57.8%   |
| DIMM         | 72        | 41.62%  |
| Row Of Chips | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 58        | 30.69%  |
| 8192  | 54        | 28.57%  |
| 2048  | 41        | 21.69%  |
| 16384 | 23        | 12.17%  |
| 1024  | 10        | 5.29%   |
| 32768 | 3         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 47        | 25.54%  |
| 1333    | 20        | 10.87%  |
| 3200    | 15        | 8.15%   |
| 2400    | 15        | 8.15%   |
| 2667    | 14        | 7.61%   |
| 667     | 13        | 7.07%   |
| 2133    | 12        | 6.52%   |
| 1334    | 11        | 5.98%   |
| 1067    | 10        | 5.43%   |
| 2666    | 6         | 3.26%   |
| 1867    | 4         | 2.17%   |
| 800     | 4         | 2.17%   |
| Unknown | 4         | 2.17%   |
| 3600    | 2         | 1.09%   |
| 1066    | 2         | 1.09%   |
| 400     | 2         | 1.09%   |
| 3733    | 1         | 0.54%   |
| 533     | 1         | 0.54%   |
| 333     | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Prolific Technology | 1         | 50%     |
| Brother Industries  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 27.63%  |
| Realtek Semiconductor                  | 7         | 9.21%   |
| Quanta                                 | 5         | 6.58%   |
| Lite-On Technology                     | 5         | 6.58%   |
| IMC Networks                           | 5         | 6.58%   |
| Microdia                               | 4         | 5.26%   |
| Logitech                               | 4         | 5.26%   |
| Sunplus Innovation Technology          | 3         | 3.95%   |
| Z-Star Microelectronics                | 2         | 2.63%   |
| Suyin                                  | 2         | 2.63%   |
| Lenovo                                 | 2         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.63%   |
| Apple                                  | 2         | 2.63%   |
| Alcor Micro                            | 2         | 2.63%   |
| Acer                                   | 2         | 2.63%   |
| Syntek                                 | 1         | 1.32%   |
| Silicon Motion                         | 1         | 1.32%   |
| Primax Electronics                     | 1         | 1.32%   |
| Luxvisions Innotech Limited            | 1         | 1.32%   |
| Importek                               | 1         | 1.32%   |
| Hewlett-Packard                        | 1         | 1.32%   |
| Arkmicro Technologies                  | 1         | 1.32%   |
| ARC International                      | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                                   | 3         | 3.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 3.9%    |
| Chicony HD WebCam                                           | 3         | 3.9%    |
| Chicony EasyCamera                                          | 3         | 3.9%    |
| Realtek USB Camera                                          | 2         | 2.6%    |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 2.6%    |
| Quanta HP TrueVision HD Camera                              | 2         | 2.6%    |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 2.6%    |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 1.3%    |
| Z-Star Webcam                                               | 1         | 1.3%    |
| Syntek Lenovo EasyCamera                                    | 1         | 1.3%    |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.3%    |
| Suyin HD Video WebCam                                       | 1         | 1.3%    |
| Sunplus Integrated_Webcam_HD                                | 1         | 1.3%    |
| Sunplus Integrated Camera                                   | 1         | 1.3%    |
| Sunplus HP Universal Camera                                 | 1         | 1.3%    |
| Silicon Motion HP Webcam-50                                 | 1         | 1.3%    |
| Realtek Integrated_Webcam_HD                                | 1         | 1.3%    |
| Realtek Integrated_Webcam_FHD                               | 1         | 1.3%    |
| Realtek Integrated_Webcam_8M                                | 1         | 1.3%    |
| Realtek HD WebCam                                           | 1         | 1.3%    |
| Quanta Realtek DMFT - RGB                                   | 1         | 1.3%    |
| Quanta HP Webcam                                            | 1         | 1.3%    |
| Quanta HD WebCam                                            | 1         | 1.3%    |
| Primax Dell Laptop Integrated Webcam 2Mpix                  | 1         | 1.3%    |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.3%    |
| Microdia Integrated_Webcam_HD                               | 1         | 1.3%    |
| Microdia Integrated Webcam                                  | 1         | 1.3%    |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 1.3%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 1         | 1.3%    |
| Logitech Webcam C930e                                       | 1         | 1.3%    |
| Logitech Webcam C310                                        | 1         | 1.3%    |
| Logitech Webcam C270                                        | 1         | 1.3%    |
| Logitech BRIO Ultra HD Webcam                               | 1         | 1.3%    |
| Lite-On TOSHIBA Web Camera - HD                             | 1         | 1.3%    |
| Lite-On HP HD Camera                                        | 1         | 1.3%    |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 1.3%    |
| Lenovo Integrated Webcam                                    | 1         | 1.3%    |
| Importek TOSHIBA Web Camera                                 | 1         | 1.3%    |
| IMC Networks XHC Camera                                     | 1         | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.3%    |
| IMC Networks SunplusIT Integrated Camera                    | 1         | 1.3%    |
| IMC Networks Integrated Camera                              | 1         | 1.3%    |
| IMC Networks EasyCamera                                     | 1         | 1.3%    |
| HP Realtek PC Camera                                        | 1         | 1.3%    |
| Chicony Webcam-101                                          | 1         | 1.3%    |
| Chicony UVC 1.00 device HD UVC WebCam                       | 1         | 1.3%    |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.3%    |
| Chicony USB 2.0 VGA UVC WebCam                              | 1         | 1.3%    |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.3%    |
| Chicony thinkpad t430s camera                               | 1         | 1.3%    |
| Chicony Integrated Camera                                   | 1         | 1.3%    |
| Chicony HP Webcam                                           | 1         | 1.3%    |
| Chicony HP 0.3MP Webcam                                     | 1         | 1.3%    |
| Chicony HD WebCam (Acer)                                    | 1         | 1.3%    |
| Chicony Chicony USB 2.0 Camera                              | 1         | 1.3%    |
| Chicony 1.3M Webcam                                         | 1         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 1         | 1.3%    |
| Arkmicro USB2.0 PC CAMERA                                   | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 7         | 36.84%  |
| Upek                  | 5         | 26.32%  |
| STMicroelectronics    | 2         | 10.53%  |
| LighTuning Technology | 2         | 10.53%  |
| AuthenTec             | 2         | 10.53%  |
| Synaptics             | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 21.05%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 10.53%  |
| Validity Sensors Synaptics WBDI                        | 2         | 10.53%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS491                                | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.26%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| AuthenTec AES2810                                      | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

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
| 1     | 73        | 40.56%  |
| 0     | 49        | 27.22%  |
| 2     | 36        | 20%     |
| 3     | 14        | 7.78%   |
| 4     | 8         | 4.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 108       | 53.73%  |
| Net/wireless             | 34        | 16.92%  |
| Bluetooth                | 20        | 9.95%   |
| Fingerprint reader       | 19        | 9.45%   |
| Card reader              | 12        | 5.97%   |
| Sound                    | 4         | 1.99%   |
| Network                  | 2         | 1%      |
| Storage/nvme             | 1         | 0.5%    |
| Net/ethernet             | 1         | 0.5%    |

