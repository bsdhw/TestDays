MidnightBSD - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for MidnightBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MidnightBSD/Desktop/README.md) and [notebooks](/Dist/MidnightBSD/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 100

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [8f541476b3](https://bsd-hardware.info/?probe=8f541476b3) | Dec 31, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [b250613285](https://bsd-hardware.info/?probe=b250613285) | Dec 29, 2025 |
| Lenovo     | ThinkPad X1 Extreme 2nd ... | Notebook    | [ba3adeef09](https://bsd-hardware.info/?probe=ba3adeef09) | Dec 16, 2025 |
| Gigabyte   | Z890 AORUS ELITE WIFI7 I... | Desktop     | [5463b7bde4](https://bsd-hardware.info/?probe=5463b7bde4) | Sep 30, 2025 |
| HPE        | ProLiant MicroServer Gen... | Desktop     | [f6ece7fbae](https://bsd-hardware.info/?probe=f6ece7fbae) | Sep 30, 2025 |
| HPE        | ProLiant DL360 Gen10        | Server      | [45feb05c9b](https://bsd-hardware.info/?probe=45feb05c9b) | Aug 06, 2025 |
| Supermicro | X10SDV-4C-TLN2F             | Server      | [95f9e94478](https://bsd-hardware.info/?probe=95f9e94478) | Jul 11, 2025 |
| Framework  | Laptop (12th Gen Intel C... | Notebook    | [d5951aeb99](https://bsd-hardware.info/?probe=d5951aeb99) | Jun 29, 2025 |
| Framework  | Laptop (12th Gen Intel C... | Notebook    | [326a5bd160](https://bsd-hardware.info/?probe=326a5bd160) | Jun 26, 2025 |
| Supermicro | X10SDV-4C-TLN2F             | Server      | [d0b2e8f49c](https://bsd-hardware.info/?probe=d0b2e8f49c) | Jun 22, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [de9d7b29ed](https://bsd-hardware.info/?probe=de9d7b29ed) | May 28, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [f09ed8b9d2](https://bsd-hardware.info/?probe=f09ed8b9d2) | May 28, 2025 |
| HPE        | ProLiant DL360 Gen10        | Server      | [0edde4283b](https://bsd-hardware.info/?probe=0edde4283b) | May 28, 2025 |
| MSI        | H170M PRO-DH                | Desktop     | [24c5a13d8a](https://bsd-hardware.info/?probe=24c5a13d8a) | May 03, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [e2b7cdd0d5](https://bsd-hardware.info/?probe=e2b7cdd0d5) | Apr 11, 2025 |
| HP         | ProLiant DL360 Gen9         | Server      | [a680c34c17](https://bsd-hardware.info/?probe=a680c34c17) | Apr 06, 2025 |
| ASRock     | B550M Steel Legend          | Desktop     | [bc700d2da8](https://bsd-hardware.info/?probe=bc700d2da8) | Apr 06, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [95625b9574](https://bsd-hardware.info/?probe=95625b9574) | Apr 03, 2025 |
| Supermicro | X10SDV-4C-TLN2F             | Server      | [bac47bcc12](https://bsd-hardware.info/?probe=bac47bcc12) | Feb 26, 2025 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | Desktop     | [e49a7e07c8](https://bsd-hardware.info/?probe=e49a7e07c8) | Feb 26, 2025 |
| HP         | ProLiant DL360 Gen9         | Server      | [aaf5ebd84f](https://bsd-hardware.info/?probe=aaf5ebd84f) | Feb 26, 2025 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [a8ecf2f04d](https://bsd-hardware.info/?probe=a8ecf2f04d) | Feb 26, 2025 |
| ASRock     | B550M Steel Legend          | Desktop     | [781be38525](https://bsd-hardware.info/?probe=781be38525) | Feb 26, 2025 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | Desktop     | [e69f71eb23](https://bsd-hardware.info/?probe=e69f71eb23) | Dec 30, 2024 |
| MSI        | B650 GAMING PLUS WIFI       | Desktop     | [434fcb2264](https://bsd-hardware.info/?probe=434fcb2264) | Nov 17, 2024 |
| MSI        | B650 GAMING PLUS WIFI       | Desktop     | [7ae29d1e0f](https://bsd-hardware.info/?probe=7ae29d1e0f) | Nov 17, 2024 |
| HP         | ProLiant DL360 Gen9         | Server      | [d3e7a9c25b](https://bsd-hardware.info/?probe=d3e7a9c25b) | Nov 12, 2024 |
| Supermicro | X10SDV-4C-TLN2F             | Server      | [38d8b42e9b](https://bsd-hardware.info/?probe=38d8b42e9b) | Nov 12, 2024 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [8f87e1ac76](https://bsd-hardware.info/?probe=8f87e1ac76) | Nov 11, 2024 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [07bdbdd1ec](https://bsd-hardware.info/?probe=07bdbdd1ec) | Aug 09, 2024 |
| HPE        | ProLiant MicroServer Gen... | Desktop     | [49344e8a17](https://bsd-hardware.info/?probe=49344e8a17) | Jun 30, 2024 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [0323476838](https://bsd-hardware.info/?probe=0323476838) | Apr 28, 2024 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [53bdb73b74](https://bsd-hardware.info/?probe=53bdb73b74) | Feb 14, 2024 |
| ASRock     | B550M Steel Legend          | Desktop     | [fa494be63d](https://bsd-hardware.info/?probe=fa494be63d) | Jan 26, 2024 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [eda92591b5](https://bsd-hardware.info/?probe=eda92591b5) | Jan 07, 2024 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [12ff062207](https://bsd-hardware.info/?probe=12ff062207) | Jan 07, 2024 |
| ASRock     | B550M Steel Legend          | Desktop     | [d24b57f807](https://bsd-hardware.info/?probe=d24b57f807) | Jan 06, 2024 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| ASUSTek    | PRIME Z890M-PLUS WIFI       | Desktop     | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | Desktop     | [50ff0c14dd](https://bsd-hardware.info/?probe=50ff0c14dd) | Apr 22, 2023 |
| ASUSTek    | P5A                         | Desktop     | [083714b968](https://bsd-hardware.info/?probe=083714b968) | Apr 07, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [31ed779fdc](https://bsd-hardware.info/?probe=31ed779fdc) | Mar 31, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [06a2d12cbe](https://bsd-hardware.info/?probe=06a2d12cbe) | Mar 29, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [2c6fc04801](https://bsd-hardware.info/?probe=2c6fc04801) | Mar 29, 2023 |
| HP         | Victus by Gaming Laptop ... | Notebook    | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| Lenovo     | B50-80 80EW                 | Notebook    | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Dell       | Latitude D610               | Notebook    | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| HP         | Victus by Gaming Laptop ... | Notebook    | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [c6824c4f4a](https://bsd-hardware.info/?probe=c6824c4f4a) | Jun 11, 2022 |
| ASUSTek    | PRIME Z590-P                | Desktop     | [3ef083287f](https://bsd-hardware.info/?probe=3ef083287f) | May 28, 2022 |
| ASUSTek    | PRIME Z590-P                | Desktop     | [53cb90d2b7](https://bsd-hardware.info/?probe=53cb90d2b7) | May 28, 2022 |
| HP         | 8767 A                      | Desktop     | [ac8a395a20](https://bsd-hardware.info/?probe=ac8a395a20) | May 20, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [50d12f98fc](https://bsd-hardware.info/?probe=50d12f98fc) | Apr 08, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [ad0ab01ca8](https://bsd-hardware.info/?probe=ad0ab01ca8) | Apr 08, 2022 |
| Lenovo     | ThinkPad X1 Extreme 20MF... | Notebook    | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [a752b8b4d6](https://bsd-hardware.info/?probe=a752b8b4d6) | Mar 22, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [ab838523ad](https://bsd-hardware.info/?probe=ab838523ad) | Jan 15, 2022 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [c13b78e6d5](https://bsd-hardware.info/?probe=c13b78e6d5) | Dec 23, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [7bf6ec598f](https://bsd-hardware.info/?probe=7bf6ec598f) | Dec 18, 2021 |
| HP         | 8767 A                      | Desktop     | [8bbd431806](https://bsd-hardware.info/?probe=8bbd431806) | Oct 14, 2021 |
| HP         | 8767 A                      | Desktop     | [6bc45054bb](https://bsd-hardware.info/?probe=6bc45054bb) | Oct 14, 2021 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [4b03ca3191](https://bsd-hardware.info/?probe=4b03ca3191) | Oct 03, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [9614fd11d7](https://bsd-hardware.info/?probe=9614fd11d7) | Aug 21, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [bd63de17b0](https://bsd-hardware.info/?probe=bd63de17b0) | Jun 07, 2021 |
| ASRock     | B550M Steel Legend          | Desktop     | [308573e703](https://bsd-hardware.info/?probe=308573e703) | Jun 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [ba938810b9](https://bsd-hardware.info/?probe=ba938810b9) | May 25, 2021 |
| ASRock     | B550M Steel Legend          | Desktop     | [29a31a7a93](https://bsd-hardware.info/?probe=29a31a7a93) | May 25, 2021 |
| HP         | 1589                        | Desktop     | [f97fc0533b](https://bsd-hardware.info/?probe=f97fc0533b) | Jan 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [778268ad6f](https://bsd-hardware.info/?probe=778268ad6f) | Dec 30, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [a27f63a72c](https://bsd-hardware.info/?probe=a27f63a72c) | Dec 30, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [78b6751c3f](https://bsd-hardware.info/?probe=78b6751c3f) | Dec 24, 2020 |
| ASUSTek    | TUF GAMING B450M-PLUS II    | Desktop     | [99fca48a73](https://bsd-hardware.info/?probe=99fca48a73) | Dec 06, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [86ba25be24](https://bsd-hardware.info/?probe=86ba25be24) | Nov 16, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [624be8f7d6](https://bsd-hardware.info/?probe=624be8f7d6) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [50ad3ee5fb](https://bsd-hardware.info/?probe=50ad3ee5fb) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [164670d170](https://bsd-hardware.info/?probe=164670d170) | Oct 29, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [4d2c24a0e3](https://bsd-hardware.info/?probe=4d2c24a0e3) | Sep 15, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [b4663b7249](https://bsd-hardware.info/?probe=b4663b7249) | Aug 28, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [53aa996eaa](https://bsd-hardware.info/?probe=53aa996eaa) | Jul 31, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [010db0aed4](https://bsd-hardware.info/?probe=010db0aed4) | May 22, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [20fac3b208](https://bsd-hardware.info/?probe=20fac3b208) | May 22, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [44681211ff](https://bsd-hardware.info/?probe=44681211ff) | May 22, 2020 |
| ASUSTek    | PRIME X370-PRO              | Desktop     | [7c311ee004](https://bsd-hardware.info/?probe=7c311ee004) | May 22, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| MidnightBSD 3.2.1 | 5         | 7.14%   |
| MidnightBSD 3.1.0 | 5         | 7.14%   |
| MidnightBSD 4.0   | 4         | 5.71%   |
| MidnightBSD 3.2.3 | 4         | 5.71%   |
| MidnightBSD 3.2.0 | 4         | 5.71%   |
| MidnightBSD 2.0.2 | 4         | 5.71%   |
| MidnightBSD 1.2   | 4         | 5.71%   |
| MidnightBSD 3.0.0 | 3         | 4.29%   |
| MidnightBSD 2.2.6 | 3         | 4.29%   |
| MidnightBSD 2.2.0 | 3         | 4.29%   |
| MidnightBSD 2.0.1 | 3         | 4.29%   |
| MidnightBSD 3.2.2 | 2         | 2.86%   |
| MidnightBSD 3.0.1 | 2         | 2.86%   |
| MidnightBSD 2.2.8 | 2         | 2.86%   |
| MidnightBSD 2.1.8 | 2         | 2.86%   |
| MidnightBSD 2.1.5 | 2         | 2.86%   |
| MidnightBSD 2.1.1 | 2         | 2.86%   |
| MidnightBSD 2.0.7 | 2         | 2.86%   |
| MidnightBSD 3.1.6 | 1         | 1.43%   |
| MidnightBSD 3.1.4 | 1         | 1.43%   |
| MidnightBSD 3.1.3 | 1         | 1.43%   |
| MidnightBSD 3.1.2 | 1         | 1.43%   |
| MidnightBSD 3.1.1 | 1         | 1.43%   |
| MidnightBSD 2.2.5 | 1         | 1.43%   |
| MidnightBSD 2.2.2 | 1         | 1.43%   |
| MidnightBSD 2.1.6 | 1         | 1.43%   |
| MidnightBSD 2.1.3 | 1         | 1.43%   |
| MidnightBSD 2.1.2 | 1         | 1.43%   |
| MidnightBSD 2.1.0 | 1         | 1.43%   |
| MidnightBSD 2.0   | 1         | 1.43%   |
| MidnightBSD 1.2.9 | 1         | 1.43%   |
| MidnightBSD 1.2.7 | 1         | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| MidnightBSD | 28        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 26        | 92.86%  |
| i386  | 2         | 7.14%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 14        | 42.42%  |
| XFCE         | 10        | 30.3%   |
| GNOME        | 7         | 21.21%  |
| Window Maker | 1         | 3.03%   |
| Cinnamon     | 1         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 20        | 58.82%  |
| X11     | 13        | 38.24%  |
| Wayland | 1         | 2.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 27        | 96.43%  |
| GDM     | 1         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 25        | 86.21%  |
| C                | 3         | 10.34%  |
| fi_FI.ISO8859-15 | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 22        | 75.86%  |
| BIOS | 7         | 24.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 23        | 79.31%  |
| Ufs  | 6         | 20.69%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 27        | 96.43%  |
| MBR  | 1         | 3.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 8         | 28.57%  |
| Hewlett-Packard     | 4         | 14.29%  |
| Supermicro          | 3         | 10.71%  |
| Lenovo              | 3         | 10.71%  |
| ASRock              | 3         | 10.71%  |
| MSI                 | 2         | 7.14%   |
| HPE                 | 2         | 7.14%   |
| Gigabyte Technology | 1         | 3.57%   |
| Framework           | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Supermicro Super Server                   | 2         | 7.14%   |
| ASUS TUF GAMING B450M-PLUS II             | 2         | 7.14%   |
| ASRock B550M Steel Legend                 | 2         | 7.14%   |
| Supermicro X9SCL/X9SCM                    | 1         | 3.57%   |
| MSI MS-7E26                               | 1         | 3.57%   |
| MSI MS-7982                               | 1         | 3.57%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QWS0M300 | 1         | 3.57%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS     | 1         | 3.57%   |
| Lenovo ThinkPad A485 20MU000VUS           | 1         | 3.57%   |
| HPE ProLiant MicroServer Gen10 Plus v2    | 1         | 3.57%   |
| HPE ProLiant DL360 Gen10                  | 1         | 3.57%   |
| HP Z420 Workstation                       | 1         | 3.57%   |
| HP Victus by Gaming Laptop 15-fa0xxx      | 1         | 3.57%   |
| HP ProLiant DL360 Gen9                    | 1         | 3.57%   |
| HP ENVY TE01-1xxx                         | 1         | 3.57%   |
| Gigabyte Z890 AORUS ELITE WIFI7 ICE       | 1         | 3.57%   |
| Framework Laptop (12th Gen Intel Core)    | 1         | 3.57%   |
| Dell Latitude D610                        | 1         | 3.57%   |
| ASUS TUF Gaming B560M-PLUS WIFI           | 1         | 3.57%   |
| ASUS TUF B350M-PLUS GAMING                | 1         | 3.57%   |
| ASUS PRIME Z890M-PLUS WIFI                | 1         | 3.57%   |
| ASUS PRIME Z590-P                         | 1         | 3.57%   |
| ASUS PRIME X370-PRO                       | 1         | 3.57%   |
| ASUS P5A                                  | 1         | 3.57%   |
| ASRock X570 Steel Legend WiFi ax          | 1         | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUS TUF         | 4         | 14.29%  |
| Lenovo ThinkPad  | 3         | 10.71%  |
| ASUS PRIME       | 3         | 10.71%  |
| Supermicro Super | 2         | 7.14%   |
| HPE ProLiant     | 2         | 7.14%   |
| ASRock B550M     | 2         | 7.14%   |
| Supermicro X9SCL | 1         | 3.57%   |
| MSI MS-7E26      | 1         | 3.57%   |
| MSI MS-7982      | 1         | 3.57%   |
| HP Z420          | 1         | 3.57%   |
| HP Victus        | 1         | 3.57%   |
| HP ProLiant      | 1         | 3.57%   |
| HP ENVY          | 1         | 3.57%   |
| Gigabyte Z890    | 1         | 3.57%   |
| Framework Laptop | 1         | 3.57%   |
| Dell Latitude    | 1         | 3.57%   |
| ASUS P5A         | 1         | 3.57%   |
| ASRock X570      | 1         | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 5         | 17.86%  |
| 2018 | 5         | 17.86%  |
| 2022 | 3         | 10.71%  |
| 2017 | 3         | 10.71%  |
| 2024 | 2         | 7.14%   |
| 2023 | 2         | 7.14%   |
| 2020 | 2         | 7.14%   |
| 2021 | 1         | 3.57%   |
| 2014 | 1         | 3.57%   |
| 2013 | 1         | 3.57%   |
| 2011 | 1         | 3.57%   |
| 2005 | 1         | 3.57%   |
| 2001 | 1         | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 18        | 64.29%  |
| Notebook | 6         | 21.43%  |
| Server   | 4         | 14.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 28        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 12        | 36.36%  |
| 32.01-64.0      | 11        | 33.33%  |
| 16.01-24.0      | 4         | 12.12%  |
| 8.01-16.0       | 2         | 6.06%   |
| More than 256.0 | 1         | 3.03%   |
| 24.01-32.0      | 1         | 3.03%   |
| 2.01-3.0        | 1         | 3.03%   |
| 0.01-0.5        | 1         | 3.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 16        | 39.02%  |
| 4.01-8.0   | 4         | 9.76%   |
| 2.01-3.0   | 4         | 9.76%   |
| 0.51-1.0   | 4         | 9.76%   |
| 32.01-64.0 | 3         | 7.32%   |
| 16.01-24.0 | 3         | 7.32%   |
| Unknown    | 3         | 7.32%   |
| 24.01-32.0 | 2         | 4.88%   |
| 0.01-0.5   | 1         | 2.44%   |
| 0          | 1         | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 9         | 23.68%  |
| 5      | 7         | 18.42%  |
| 2      | 5         | 13.16%  |
| 6      | 4         | 10.53%  |
| 8      | 3         | 7.89%   |
| 7      | 3         | 7.89%   |
| 4      | 3         | 7.89%   |
| 3      | 3         | 7.89%   |
| 0      | 1         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 80.65%  |
| Yes       | 6         | 19.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 50%     |
| No        | 14        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 53.57%  |
| Yes       | 13        | 46.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 22        | 78.57%  |
| UK      | 2         | 7.14%   |
| Romania | 1         | 3.57%   |
| Germany | 1         | 3.57%   |
| France  | 1         | 3.57%   |
| Finland | 1         | 3.57%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Ypsilanti   | 20        | 71.43%  |
| London      | 2         | 7.14%   |
| Wuppertal   | 1         | 3.57%   |
| Tampere     | 1         | 3.57%   |
| Suresnes    | 1         | 3.57%   |
| Los Angeles | 1         | 3.57%   |
| Fresno      | 1         | 3.57%   |
| Brasov      | 1         | 3.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 65     | 17.65%  |
| Samsung Electronics | 11        | 90     | 16.18%  |
| Intel               | 10        | 66     | 14.71%  |
| WDC                 | 7         | 30     | 10.29%  |
| HGST                | 5         | 29     | 7.35%   |
| Toshiba             | 4         | 11     | 5.88%   |
| SanDisk             | 4         | 14     | 5.88%   |
| KIOXIA              | 4         | 5      | 5.88%   |
| SK hynix            | 3         | 3      | 4.41%   |
| Crucial             | 3         | 7      | 4.41%   |
| Micron Technology   | 1         | 2      | 1.47%   |
| Maxtor              | 1         | 1      | 1.47%   |
| Lenovo              | 1         | 1      | 1.47%   |
| Hewlett-Packard     | 1         | 1      | 1.47%   |
| A-DATA Technology   | 1         | 2      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                   | 6         | 5.61%   |
| Intel SSDSC2KG480G8 480GB                   | 5         | 4.67%   |
| Seagate ST8000VN0022-2EL112 8TB             | 4         | 3.74%   |
| Seagate ST8000VN0002-1Z8112 8TB             | 4         | 3.74%   |
| Samsung SSD 970 PRO 512GB                   | 4         | 3.74%   |
| Seagate IronWolf ZA1000NM10002-2ZG102 1TB   | 3         | 2.8%    |
| SanDisk Ultra 3D NVMe 1TB                   | 3         | 2.8%    |
| Samsung SSD 870 EVO 1TB                     | 3         | 2.8%    |
| Samsung SSD 860 QVO 2TB                     | 3         | 2.8%    |
| Samsung SSD 860 EVO 1TB                     | 3         | 2.8%    |
| KIOXIA KBG40ZNV1T02 1TB                     | 3         | 2.8%    |
| Intel SSDPED1D480GA 480GB                   | 3         | 2.8%    |
| WDC WDS100T3X0C-00SJG0 1TB                  | 2         | 1.87%   |
| WDC WD60EFAX-68SHWN0 6TB                    | 2         | 1.87%   |
| Toshiba THNSNJ128GCSU 128GB                 | 2         | 1.87%   |
| SK hynix SHGP31-1000GM 1TB                  | 2         | 1.87%   |
| Seagate ST16000NM001G-2KK103 16TB           | 2         | 1.87%   |
| Seagate ST10000VN0008-2PJ103 10TB           | 2         | 1.87%   |
| Seagate ST10000NE0008-2PL103 10TB           | 2         | 1.87%   |
| Seagate FireCuda 120 SSD ZA500GM10001 500GB | 2         | 1.87%   |
| Samsung SSD 990 EVO Plus 4TB                | 2         | 1.87%   |
| Samsung SSD 970 EVO Plus 2TB                | 2         | 1.87%   |
| Samsung SSD 750 EVO 250GB                   | 2         | 1.87%   |
| HGST HUS724020ALA640 2TB                    | 2         | 1.87%   |
| HGST HSSC0480S5xnNMRI 480GB                 | 2         | 1.87%   |
| Crucial CT500P2SSD8 500GB                   | 2         | 1.87%   |
| Crucial CT4000P3SSD8 4TB                    | 2         | 1.87%   |
| WDC WD5002AALX-00J37A0 500GB                | 1         | 0.93%   |
| WDC WD5000LPLX-08ZNTT0 500GB                | 1         | 0.93%   |
| WDC WD5000AAKS-00UU3A0 500GB                | 1         | 0.93%   |
| WDC WD30EZRX-00MMMB0 3TB                    | 1         | 0.93%   |
| WDC WD1003FZEX-00K3CA0 1TB                  | 1         | 0.93%   |
| Toshiba TL100 120GB                         | 1         | 0.93%   |
| Toshiba MG07ACA14TE 14TB                    | 1         | 0.93%   |
| SK hynix SHGP31-2000GM 2TB                  | 1         | 0.93%   |
| Seagate ST980210A 80GB                      | 1         | 0.93%   |
| Seagate ST5000DM000-1FK178 5TB              | 1         | 0.93%   |
| Seagate ST2000DM001-1CH164 2TB              | 1         | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB              | 1         | 0.93%   |
| SanDisk SSD PLUS 240GB                      | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 53     | 38.89%  |
| WDC     | 6         | 22     | 33.33%  |
| HGST    | 3         | 13     | 16.67%  |
| Toshiba | 1         | 4      | 5.56%   |
| Maxtor  | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 60     | 33.33%  |
| Seagate             | 5         | 12     | 18.52%  |
| Intel               | 5         | 48     | 18.52%  |
| Toshiba             | 3         | 7      | 11.11%  |
| HGST                | 2         | 16     | 7.41%   |
| SanDisk             | 1         | 7      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |
| Crucial             | 1         | 2      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 18        | 81     | 38.3%   |
| SSD  | 17        | 153    | 36.17%  |
| HDD  | 12        | 93     | 25.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 246    | 56.1%   |
| NVMe | 18        | 81     | 43.9%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 19        | 97     | 44.19%  |
| 0.51-1.0   | 9         | 33     | 20.93%  |
| 1.01-2.0   | 7         | 42     | 16.28%  |
| 4.01-10.0  | 4         | 56     | 9.3%    |
| 10.01-20.0 | 3         | 17     | 6.98%   |
| 2.01-3.0   | 1         | 1      | 2.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 15        | 48.39%  |
| 101-250    | 5         | 16.13%  |
| 501-1000   | 5         | 16.13%  |
| 1001-2000  | 3         | 9.68%   |
| 21-50      | 2         | 6.45%   |
| 51-100     | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 22        | 57.89%  |
| 21-50   | 8         | 21.05%  |
| 51-100  | 4         | 10.53%  |
| 251-500 | 2         | 5.26%   |
| 101-250 | 2         | 5.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD60EFAX-68SHWN0 6TB        | 1         | 2      | 33.33%  |
| Seagate ST8000VN0022-2EL112 8TB | 1         | 2      | 33.33%  |
| Intel SSDSC2KW480H6 480GB       | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 2      | 50%     |
| Seagate | 1         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 4      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Works    | 28        | 321    | 87.5%   |
| Malfunc  | 3         | 5      | 9.38%   |
| Detected | 1         | 1      | 3.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 17        | 29.31%  |
| AMD                       | 10        | 17.24%  |
| Samsung Electronics       | 7         | 12.07%  |
| SanDisk                   | 6         | 10.34%  |
| SK hynix                  | 3         | 5.17%   |
| KIOXIA                    | 3         | 5.17%   |
| Realtek Semiconductor     | 2         | 3.45%   |
| Micron/Crucial Technology | 2         | 3.45%   |
| VIA Technologies          | 1         | 1.72%   |
| Toshiba                   | 1         | 1.72%   |
| Silicon Image             | 1         | 1.72%   |
| Micron Technology         | 1         | 1.72%   |
| Lenovo                    | 1         | 1.72%   |
| Hewlett-Packard           | 1         | 1.72%   |
| ASMedia Technology        | 1         | 1.72%   |
| Adaptec                   | 1         | 1.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 9.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 8.45%   |
| Intel Optane SSD 900P Series                                                   | 4         | 5.63%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 5.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 4.23%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3         | 4.23%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 4.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 4.23%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 2.82%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                 | 2         | 2.82%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                       | 2         | 2.82%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 2.82%   |
| Intel SATA Controller [RAID Mode]                                              | 2         | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.82%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 2.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 2.82%   |
| Unknown                                                                        | 2         | 2.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.41%   |
| Toshiba Cx5 NVMe SSD Controller                                                | 1         | 1.41%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 1.41%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 1         | 1.41%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 1         | 1.41%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                 | 1         | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 1         | 1.41%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.41%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                       | 1         | 1.41%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 1.41%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1         | 1.41%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 1         | 1.41%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.41%   |
| HP Smart Array Gen9 Controllers                                                | 1         | 1.41%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 1         | 1.41%   |
| AMD X370 Series Chipset SATA Controller                                        | 1         | 1.41%   |
| AMD 600 Series Chipset SATA Controller                                         | 1         | 1.41%   |
| Adaptec Smart Storage PQI SAS                                                  | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 19        | 40.43%  |
| SATA | 18        | 38.3%   |
| RAID | 5         | 10.64%  |
| IDE  | 3         | 6.38%   |
| SAS  | 2         | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 18        | 62.07%  |
| AMD    | 11        | 37.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 3         | 8.82%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 3         | 8.82%   |
| Intel Xeon CPU D-1521 @ 2.40GHz                 | 2         | 5.88%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz         | 2         | 5.88%   |
| AMD Ryzen 7 5700X 8-Core Processor              | 2         | 5.88%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 2         | 5.88%   |
| Intel Xeon Gold 6230 CPU @ 2.10GHz              | 1         | 2.94%   |
| Intel Xeon E-2314 CPU @ 2.80GHz                 | 1         | 2.94%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz             | 1         | 2.94%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz                | 1         | 2.94%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz             | 1         | 2.94%   |
| Intel Pentium M                                 | 1         | 2.94%   |
| Intel Core Ultra 7 265K                         | 1         | 2.94%   |
| Intel Core Ultra 5 245K                         | 1         | 2.94%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 2.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 2.94%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 2.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1         | 2.94%   |
| Intel 12th Gen Core i7-1260P                    | 1         | 2.94%   |
| Intel 12th Gen Core i5-12450H                   | 1         | 2.94%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1         | 2.94%   |
| AMD Ryzen 9 7900 12-Core Processor              | 1         | 2.94%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 2.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 2.94%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2.94%   |
| AMD Duron Processor                             | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| AMD Ryzen 7     | 8         | 26.67%  |
| Intel Xeon      | 6         | 20%     |
| Other           | 5         | 16.67%  |
| Intel Core i7   | 3         | 10%     |
| Intel Core      | 2         | 6.67%   |
| AMD Ryzen 9     | 2         | 6.67%   |
| Intel Xeon Gold | 1         | 3.33%   |
| Intel Pentium M | 1         | 3.33%   |
| Intel Core i5   | 1         | 3.33%   |
| AMD Ryzen 5 PRO | 1         | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 8      | 11        | 32.35%  |
| 4      | 6         | 17.65%  |
| 16     | 5         | 14.71%  |
| 6      | 3         | 8.82%   |
| 24     | 2         | 5.88%   |
| 1      | 2         | 5.88%   |
| 40     | 1         | 2.94%   |
| 32     | 1         | 2.94%   |
| 20     | 1         | 2.94%   |
| 14     | 1         | 2.94%   |
| 12     | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 26        | 89.66%  |
| 2      | 3         | 10.34%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 19        | 59.38%  |
| 1       | 12        | 37.5%   |
| Unknown | 1         | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 8         | 24.24%  |
| Zen 3       | 5         | 15.15%  |
| Zen+        | 4         | 12.12%  |
| Zen         | 3         | 9.09%   |
| Skylake     | 2         | 6.06%   |
| KabyLake    | 2         | 6.06%   |
| Broadwell   | 2         | 6.06%   |
| Zen 2       | 1         | 3.03%   |
| SandyBridge | 1         | 3.03%   |
| P6          | 1         | 3.03%   |
| K6          | 1         | 3.03%   |
| IvyBridge   | 1         | 3.03%   |
| Haswell     | 1         | 3.03%   |
| CometLake   | 1         | 3.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 14        | 37.84%  |
| Intel                      | 9         | 24.32%  |
| AMD                        | 8         | 21.62%  |
| Matrox Electronics Systems | 4         | 10.81%  |
| ASPEED Technology          | 2         | 5.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Nvidia GK208B [GeForce GT 710]                                   | 6         | 15.79%  |
| Nvidia GP108 [GeForce GT 1030]                                   | 3         | 7.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                  | 2         | 5.26%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 2         | 5.26%   |
| Matrox Electronics Systems MGA G200eH3                           | 2         | 5.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                        | 2         | 5.26%   |
| ASPEED Technology ASPEED Graphics Family                         | 2         | 5.26%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                  | 2         | 5.26%   |
| AMD Caicos PRO [Radeon HD 7450]                                  | 2         | 5.26%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 2.63%   |
| Matrox Electronics Systems MGA G200eW WPCM450                    | 1         | 2.63%   |
| Matrox Electronics Systems MGA G200EH                            | 1         | 2.63%   |
| Intel Skylake-S GT2 [HD Graphics 530]                            | 1         | 2.63%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                        | 1         | 2.63%   |
| Intel DG2 [Arc A750]                                             | 1         | 2.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                         | 1         | 2.63%   |
| Intel Arrow Lake-S [Intel Graphics]                              | 1         | 2.63%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                        | 1         | 2.63%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                            | 1         | 2.63%   |
| AMD RV370/M22 [Mobility Radeon X300]                             | 1         | 2.63%   |
| AMD RV280 [Radeon 9200] (Secondary)                              | 1         | 2.63%   |
| AMD RV280 [Radeon 9200]                                          | 1         | 2.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 2.63%   |
| AMD Raphael                                                      | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 11        | 34.38%  |
| 1 x AMD        | 5         | 15.63%  |
| 1 x Matrox     | 4         | 12.5%   |
| 1 x Intel      | 4         | 12.5%   |
| Intel + Nvidia | 3         | 9.38%   |
| Intel + AMD    | 2         | 6.25%   |
| 1 x ASPEED     | 2         | 6.25%   |
| 2 x AMD        | 1         | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 25        | 78.13%  |
| Proprietary | 7         | 21.88%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 76.67%  |
| 1.01-2.0   | 2         | 6.67%   |
| 8.01-16.0  | 2         | 6.67%   |
| 0.01-0.5   | 2         | 6.67%   |
| 3.01-4.0   | 1         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| LG Electronics      | 2         | 28.57%  |
| Goldstar            | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Chimei Innolux      | 1         | 14.29%  |
| Acer                | 1         | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S22C450 SAM09C5 1920x1080 480x270mm 21.7-inch | 1         | 12.5%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                 | 1         | 12.5%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                  | 1         | 12.5%   |
| Goldstar LG ULTRAGEAR GSM7765 2560x1440 700x390mm 31.5-inch       | 1         | 12.5%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch        | 1         | 12.5%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch   | 1         | 12.5%   |
| Acer LCD Monitor EI342CKR 3440x1440                               | 1         | 12.5%   |
| Acer EI342CKR ACR0763 3440x1440 800x330mm 34.1-inch               | 1         | 12.5%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 3840x2160 (4K)  | 2         | 28.57%  |
| 2560x1440 (QHD) | 2         | 28.57%  |
| 3440x1440       | 1         | 14.29%  |
| 1920x1080 (FHD) | 1         | 14.29%  |
| 1366x768 (WXGA) | 1         | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2         | 28.57%  |
| 34      | 1         | 14.29%  |
| 31      | 1         | 14.29%  |
| 27      | 1         | 14.29%  |
| 21      | 1         | 14.29%  |
| 13      | 1         | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 2         | 28.57%  |
| 701-800     | 1         | 14.29%  |
| 601-700     | 1         | 14.29%  |
| 501-600     | 1         | 14.29%  |
| 401-500     | 1         | 14.29%  |
| 301-350     | 1         | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4         | 57.14%  |
| Unknown | 2         | 28.57%  |
| 21/9    | 1         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 351-500        | 2         | 28.57%  |
| Unknown        | 2         | 28.57%  |
| 81-90          | 1         | 14.29%  |
| 301-350        | 1         | 14.29%  |
| 201-250        | 1         | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 3         | 42.86%  |
| Unknown | 2         | 28.57%  |
| 161-240 | 1         | 14.29%  |
| 51-100  | 1         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 74.19%  |
| 1     | 8         | 25.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 43.9%   |
| Realtek Semiconductor | 13        | 31.71%  |
| Broadcom              | 4         | 9.76%   |
| MediaTek              | 3         | 7.32%   |
| U-Blox                | 1         | 2.44%   |
| D-Link System         | 1         | 2.44%   |
| ASUSTek Computer      | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8125 2.5GbE Controller                                               | 5         | 9.26%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 5         | 9.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                             | 4         | 7.41%   |
| Intel Wi-Fi 6 AX200                                                             | 3         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                                      | 2         | 3.7%    |
| Intel I211 Gigabit Network Connection                                           | 2         | 3.7%    |
| Intel Ethernet Controller X550                                                  | 2         | 3.7%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                   | 2         | 3.7%    |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                                | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 2         | 3.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                              | 2         | 3.7%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                                | 2         | 3.7%    |
| U-Blox [u-blox 7]                                                               | 1         | 1.85%   |
| Realtek USB 2.5GbE Controller                                                   | 1         | 1.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                      | 1         | 1.85%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 1         | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 1         | 1.85%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 1         | 1.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 1         | 1.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 1         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                                  | 1         | 1.85%   |
| Intel I350 Gigabit Network Connection                                           | 1         | 1.85%   |
| Intel Ethernet Controller 10G X550T                                             | 1         | 1.85%   |
| Intel Ethernet Connection (7) I219-V                                            | 1         | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                                           | 1         | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 1         | 1.85%   |
| Intel 82574L Gigabit Network Connection                                         | 1         | 1.85%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                 | 1         | 1.85%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                         | 1         | 1.85%   |
| Broadcom BCM57414 NetXtreme-E 10Gb/25Gb RDMA Ethernet Controller                | 1         | 1.85%   |
| ASUS USB-AC53 Nano USB Wieless Adapter                                          | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 9         | 47.37%  |
| Realtek Semiconductor | 7         | 36.84%  |
| MediaTek              | 2         | 10.53%  |
| ASUSTek Computer      | 1         | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 4         | 21.05%  |
| Intel Wi-Fi 6 AX200                                                  | 3         | 15.79%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 10.53%  |
| Intel Wireless 8265 / 8275                                           | 2         | 10.53%  |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 5.26%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 1         | 5.26%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1         | 5.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 1         | 5.26%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 1         | 5.26%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 1         | 5.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 5.26%   |
| ASUS USB-AC53 Nano USB Wieless Adapter                               | 1         | 5.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14        | 46.67%  |
| Realtek Semiconductor | 11        | 36.67%  |
| Broadcom              | 4         | 13.33%  |
| D-Link System         | 1         | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 15.15%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 5         | 15.15%  |
| Intel I211 Gigabit Network Connection                                  | 2         | 6.06%   |
| Intel Ethernet Controller X550                                         | 2         | 6.06%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 6.06%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                       | 2         | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 6.06%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 2         | 6.06%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                       | 2         | 6.06%   |
| Realtek USB 2.5GbE Controller                                          | 1         | 3.03%   |
| Intel I350 Gigabit Network Connection                                  | 1         | 3.03%   |
| Intel Ethernet Controller 10G X550T                                    | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 3.03%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 3.03%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 3.03%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1         | 3.03%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 3.03%   |
| Broadcom BCM57414 NetXtreme-E 10Gb/25Gb RDMA Ethernet Controller       | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 63.64%  |
| WiFi     | 14        | 31.82%  |
| Modem    | 1         | 2.27%   |
| Unknown  | 1         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24        | 82.76%  |
| WiFi     | 5         | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 16        | 55.17%  |
| 1     | 8         | 27.59%  |
| 6     | 2         | 6.9%    |
| 3     | 2         | 6.9%    |
| 4     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 77.42%  |
| Yes  | 7         | 22.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 9         | 56.25%  |
| Realtek Semiconductor   | 3         | 18.75%  |
| MediaTek                | 1         | 6.25%   |
| IMC Networks            | 1         | 6.25%   |
| Foxconn / Hon Hai       | 1         | 6.25%   |
| Cambridge Silicon Radio | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 3         | 18.75%  |
| Realtek Bluetooth 4.2 Adapter                       | 2         | 12.5%   |
| Intel Bluetooth wireless interface                  | 2         | 12.5%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 6.25%   |
| MediaTek RZ616 Bluetooth Adapter                    | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 6.25%   |
| Intel AX210 Bluetooth                               | 1         | 6.25%   |
| Intel AX201 Bluetooth                               | 1         | 6.25%   |
| IMC Networks MediaTek Bluetooth Adapter             | 1         | 6.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Nvidia                      | 14        | 34.15%  |
| Intel                       | 12        | 29.27%  |
| AMD                         | 7         | 17.07%  |
| Logitech                    | 2         | 4.88%   |
| VIA Technologies            | 1         | 2.44%   |
| Texas Instruments           | 1         | 2.44%   |
| SteelSeries ApS             | 1         | 2.44%   |
| Realtek Semiconductor       | 1         | 2.44%   |
| FiiO Electronics Technology | 1         | 2.44%   |
| Creative Labs               | 1         | 2.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                                                                                                                                      | 6         | 13.33%  |
| Nvidia GP108 High Definition Audio Controller                                                                                                                                              | 3         | 6.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                                                                                                             | 2         | 4.44%   |
| Nvidia GP102 HDMI Audio Controller                                                                                                                                                         | 2         | 4.44%   |
| Logitech Blue Microphones Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone | 2         | 4.44%   |
| Intel Tiger Lake-H HD Audio Controller                                                                                                                                                     | 2         | 4.44%   |
| Intel Cannon Lake PCH cAVS                                                                                                                                                                 | 2         | 4.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                                                                                                                    | 2         | 4.44%   |
| AMD Ryzen HD Audio Controller                                                                                                                                                              | 2         | 4.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                                                                                                                    | 2         | 4.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                                                                                                        | 2         | 4.44%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                                                                                                          | 2         | 4.44%   |
| VIA Technologies VT82C686 AC97 Audio Controller                                                                                                                                            | 1         | 2.22%   |
| Texas Instruments PCM2902 Audio Codec                                                                                                                                                      | 1         | 2.22%   |
| SteelSeries ApS SteelSeries GameDAC GameDAC Hi-Res                                                                                                                                         | 1         | 2.22%   |
| Realtek Semiconductor USB Audio                                                                                                                                                            | 1         | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                                                                                                            | 1         | 2.22%   |
| Intel DG2 Audio Controller                                                                                                                                                                 | 1         | 2.22%   |
| Intel Comet Lake PCH cAVS                                                                                                                                                                  | 1         | 2.22%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                                                                                                             | 1         | 2.22%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                                                                                                           | 1         | 2.22%   |
| Intel 800 Series ACE (Audio Context Engine)                                                                                                                                                | 1         | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                                                                                                            | 1         | 2.22%   |
| FiiO Electronics Technology USB DAC                                                                                                                                                        | 1         | 2.22%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                                                                                                         | 1         | 2.22%   |
| AMD Starship/Matisse HD Audio Controller                                                                                                                                                   | 1         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                                                                                                        | 1         | 2.22%   |
| AMD Radeon High Definition Audio Controller                                                                                                                                                | 1         | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Corsair                      | 10        | 22.22%  |
| Samsung Electronics          | 9         | 20%     |
| G.Skill                      | 6         | 13.33%  |
| Unknown                      | 6         | 13.33%  |
| Unknown                      | 2         | 4.44%   |
| PNY                          | 2         | 4.44%   |
| Micron Technology            | 2         | 4.44%   |
| Kingston                     | 2         | 4.44%   |
| SK hynix                     | 1         | 2.22%   |
| Patriot Memory (PDP Systems) | 1         | 2.22%   |
| Mushkin                      | 1         | 2.22%   |
| Hewlett-Packard              | 1         | 2.22%   |
| Elpida                       | 1         | 2.22%   |
| Crucial                      | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 6         | 12.77%  |
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s                    | 4         | 8.51%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s                   | 3         | 6.38%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                     | 2         | 4.26%   |
| PNY RAM 16GU2X08QJLL42-12-K 16GB SODIMM DDR4 3200MT/s                    | 2         | 4.26%   |
| Unknown RAM Module 64MB DIMM DRAM                                        | 1         | 2.13%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM 2667MT/s                     | 1         | 2.13%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                               | 1         | 2.13%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1         | 2.13%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.13%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.13%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                      | 1         | 2.13%   |
| Samsung RAM M391A2G43BB2-CWE 16GB DIMM DDR4 3200MT/s                     | 1         | 2.13%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 32GB DIMM DDR4 2667MT/s | 1         | 2.13%   |
| Mushkin RAM MRX4U320GJJM32G 32GB DIMM DDR4 2400MT/s                      | 1         | 2.13%   |
| Micron RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 2.13%   |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s                    | 1         | 2.13%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s                    | 1         | 2.13%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| HP RAM 752369-081 16GB DIMM DDR4 2133MT/s                                | 1         | 2.13%   |
| G.Skill RAM F4-4400C19-16GTZR 16GB DIMM DDR4 2667MT/s                    | 1         | 2.13%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.13%   |
| Elpida RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1         | 2.13%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s                  | 1         | 2.13%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s                | 1         | 2.13%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2400MT/s                     | 1         | 2.13%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2400MT/s                     | 1         | 2.13%   |
| Corsair RAM CMK32GX5M2F6000Z36 16GB DIMM DDR5 6000MT/s                   | 1         | 2.13%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s                   | 1         | 2.13%   |
| Corsair RAM CMK16GX4M2Z2666C16 8GB DIMM DDR4 2666MT/s                    | 1         | 2.13%   |
| Corsair RAM CMH96GX5M2B5600C40 48GB DIMM DDR5 5600MT/s                   | 1         | 2.13%   |
| Corsair RAM CMH64GX5M2B6000C40 32GB DIMM DDR5 4800MT/s                   | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 22        | 73.33%  |
| DDR5 | 3         | 10%     |
| DDR3 | 3         | 10%     |
| DRAM | 1         | 3.33%   |
| DDR  | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 22        | 75.86%  |
| SODIMM | 7         | 24.14%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 16        | 43.24%  |
| 32768 | 10        | 27.03%  |
| 8192  | 4         | 10.81%  |
| 4096  | 3         | 8.11%   |
| 49152 | 1         | 2.7%    |
| 1024  | 1         | 2.7%    |
| 256   | 1         | 2.7%    |
| 64    | 1         | 2.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 10        | 26.32%  |
| 2667    | 9         | 23.68%  |
| 3600    | 4         | 10.53%  |
| 2400    | 3         | 7.89%   |
| 1600    | 3         | 7.89%   |
| 6000    | 1         | 2.63%   |
| 5600    | 1         | 2.63%   |
| 4800    | 1         | 2.63%   |
| 3000    | 1         | 2.63%   |
| 2933    | 1         | 2.63%   |
| 2666    | 1         | 2.63%   |
| 2133    | 1         | 2.63%   |
| 667     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Logitech                    | 6         | 54.55%  |
| Chicony Electronics         | 2         | 18.18%  |
| Realtek Semiconductor       | 1         | 9.09%   |
| Luxvisions Innotech Limited | 1         | 9.09%   |
| Bison Electronics           | 1         | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Logitech HD Pro Webcam C920                          | 3         | 27.27%  |
| Logitech C922 Pro Stream Webcam                      | 3         | 27.27%  |
| Realtek Laptop Camera                                | 1         | 9.09%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 9.09%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 9.09%   |
| Chicony Integrated Camera                            | 1         | 9.09%   |
| Bison Integrated Camera                              | 1         | 9.09%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 50%     |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 50%     |

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
| 0     | 8         | 23.53%  |
| 2     | 7         | 20.59%  |
| 4     | 6         | 17.65%  |
| 1     | 6         | 17.65%  |
| 3     | 5         | 14.71%  |
| 6     | 1         | 2.94%   |
| 5     | 1         | 2.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 17        | 37.78%  |
| Net/wireless             | 10        | 22.22%  |
| Bluetooth                | 6         | 13.33%  |
| Net/ethernet             | 3         | 6.67%   |
| Sound                    | 2         | 4.44%   |
| Fingerprint reader       | 2         | 4.44%   |
| Card reader              | 2         | 4.44%   |
| Storage/raid             | 1         | 2.22%   |
| Network                  | 1         | 2.22%   |
| Firewire controller      | 1         | 2.22%   |

