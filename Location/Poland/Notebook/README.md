BSD in Poland - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 101

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [9afa1aea18](https://bsd-hardware.info/?probe=9afa1aea18) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP4C    | [b891388109](https://bsd-hardware.info/?probe=b891388109) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | [48a63a2328](https://bsd-hardware.info/?probe=48a63a2328) | Jun 02, 2023 |
| Unknown       | Unknown                     | [3b4be5b07a](https://bsd-hardware.info/?probe=3b4be5b07a) | May 24, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Unknown       | Unknown                     | [2a2b4272f9](https://bsd-hardware.info/?probe=2a2b4272f9) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [526906c806](https://bsd-hardware.info/?probe=526906c806) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8aede62ca8](https://bsd-hardware.info/?probe=8aede62ca8) | May 14, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [add8280600](https://bsd-hardware.info/?probe=add8280600) | Apr 11, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Acer          | Aspire F5-573G              | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [97d9b10c8a](https://bsd-hardware.info/?probe=97d9b10c8a) | Feb 24, 2023 |
| HP            | Notebook                    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [bccdd2f331](https://bsd-hardware.info/?probe=bccdd2f331) | Jan 30, 2023 |
| HP            | EliteBook 840 G3            | [92c676e033](https://bsd-hardware.info/?probe=92c676e033) | Jan 26, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Intel         | H81U                        | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Intel         | H81U                        | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Dell          | Latitude E6430              | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Deciso        | NetBoard-A10                | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| Lenovo        | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Dell          | Latitude E6430              | [e18a4bc564](https://bsd-hardware.info/?probe=e18a4bc564) | Jan 10, 2022 |
| Dell          | Inspiron N5110              | [19be37f181](https://bsd-hardware.info/?probe=19be37f181) | Jan 09, 2022 |
| Acer          | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Dell          | G15 5510                    | [2da7a07664](https://bsd-hardware.info/?probe=2da7a07664) | Dec 07, 2021 |
| Dell          | G15 5510                    | [8846b3fd69](https://bsd-hardware.info/?probe=8846b3fd69) | Nov 27, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [7330a6f958](https://bsd-hardware.info/?probe=7330a6f958) | Nov 20, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| Acer          | Aspire 5742G                | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Dell          | Latitude E6430              | [46f2ef2432](https://bsd-hardware.info/?probe=46f2ef2432) | Nov 08, 2021 |
| Dell          | Latitude E6430              | [d31f35bb29](https://bsd-hardware.info/?probe=d31f35bb29) | Oct 15, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| ASUSTek       | X555LB                      | [e3443d9f27](https://bsd-hardware.info/?probe=e3443d9f27) | Oct 02, 2021 |
| IBM           | ThinkPad X41 2525FAG        | [63a34dc807](https://bsd-hardware.info/?probe=63a34dc807) | Sep 14, 2021 |
| Lenovo        | Unknown                     | [e16ce5e864](https://bsd-hardware.info/?probe=e16ce5e864) | Aug 08, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [668bf95221](https://bsd-hardware.info/?probe=668bf95221) | Jun 25, 2021 |
| Lenovo        | ThinkPad T440 20B7S1860W    | [8552205176](https://bsd-hardware.info/?probe=8552205176) | Jun 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9f82e215c3](https://bsd-hardware.info/?probe=9f82e215c3) | Jun 22, 2021 |
| Dell          | Vostro 3560                 | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Acer          | Aspire V3-571G              | [a9fe2f5aad](https://bsd-hardware.info/?probe=a9fe2f5aad) | Jun 16, 2021 |
| Dell          | Latitude 5400               | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| Dell          | Latitude E6440              | [8fa2c1f5c4](https://bsd-hardware.info/?probe=8fa2c1f5c4) | Jun 13, 2021 |
| Dell          | Latitude E6440              | [77f259babe](https://bsd-hardware.info/?probe=77f259babe) | Jun 12, 2021 |
| Dell          | Latitude E6410              | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | Latitude E6440              | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [a332efd9d9](https://bsd-hardware.info/?probe=a332efd9d9) | Mar 15, 2021 |
| HP            | ENVY dv7                    | [4637a9eeff](https://bsd-hardware.info/?probe=4637a9eeff) | Feb 14, 2021 |
| Dell          | Latitude E5430 vPro         | [bee421a110](https://bsd-hardware.info/?probe=bee421a110) | Feb 06, 2021 |
| Dell          | Latitude E5430 vPro         | [e8157ac6a3](https://bsd-hardware.info/?probe=e8157ac6a3) | Feb 06, 2021 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [3d18f3f8a9](https://bsd-hardware.info/?probe=3d18f3f8a9) | Jan 23, 2021 |
| Lenovo        | ThinkPad X200s 7470A98      | [41f36aa8b6](https://bsd-hardware.info/?probe=41f36aa8b6) | Dec 19, 2020 |
| Unknown       | Spring Peak                 | [b61f5c268a](https://bsd-hardware.info/?probe=b61f5c268a) | Dec 15, 2020 |
| PC Special... | Recoil II                   | [343eec31b5](https://bsd-hardware.info/?probe=343eec31b5) | Dec 06, 2020 |
| Panasonic     | CFMX4-1                     | [761d21f21a](https://bsd-hardware.info/?probe=761d21f21a) | Dec 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [dce3ba8c99](https://bsd-hardware.info/?probe=dce3ba8c99) | Nov 18, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [2664153a6e](https://bsd-hardware.info/?probe=2664153a6e) | Oct 29, 2020 |
| Lenovo        | ThinkPad X230 23254S6       | [f4ac5ddaa4](https://bsd-hardware.info/?probe=f4ac5ddaa4) | Oct 25, 2020 |
| HP            | 635                         | [3b21406e87](https://bsd-hardware.info/?probe=3b21406e87) | Oct 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S4GR02    | [6c2d8a57ea](https://bsd-hardware.info/?probe=6c2d8a57ea) | Oct 19, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [01d2c090de](https://bsd-hardware.info/?probe=01d2c090de) | Oct 03, 2020 |
| Dell          | Latitude XT2                | [19456100cf](https://bsd-hardware.info/?probe=19456100cf) | Jul 16, 2020 |
| Dell          | Latitude XT2                | [160725773f](https://bsd-hardware.info/?probe=160725773f) | Jul 16, 2020 |
| Sony          | SVF1521K1EB                 | [fe29d4e002](https://bsd-hardware.info/?probe=fe29d4e002) | Jun 29, 2020 |
| Lenovo        | ThinkPad W520 4284W5L       | [9ba8051e48](https://bsd-hardware.info/?probe=9ba8051e48) | Jun 09, 2020 |
| Dell          | Latitude E7240              | [1de87c0000](https://bsd-hardware.info/?probe=1de87c0000) | May 30, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 10        | 11.9%   |
| OpenBSD 7.0          | 5         | 5.95%   |
| FreeBSD 14.0-CURRENT | 5         | 5.95%   |
| OpenBSD 7.1          | 4         | 4.76%   |
| helloSystem 0.7.0    | 4         | 4.76%   |
| GhostBSD 20.04.02    | 4         | 4.76%   |
| FreeBSD 12.2         | 4         | 4.76%   |
| helloSystem 0.5.0    | 3         | 3.57%   |
| FreeBSD 13.2         | 3         | 3.57%   |
| FreeBSD 12.1         | 3         | 3.57%   |
| OPNsense 22.7.10     | 2         | 2.38%   |
| OpenBSD 6.8          | 2         | 2.38%   |
| helloSystem 0.8.2    | 2         | 2.38%   |
| helloSystem 0.8.0    | 2         | 2.38%   |
| helloSystem 0.6.0    | 2         | 2.38%   |
| FreeBSD 13.0-p5      | 2         | 2.38%   |
| FreeBSD 13.0-p4      | 2         | 2.38%   |
| FreeBSD 13.0-p2      | 2         | 2.38%   |
| OPNsense 23.4        | 1         | 1.19%   |
| OPNsense 23.1.9      | 1         | 1.19%   |
| OPNsense 23.1.7      | 1         | 1.19%   |
| OPNsense 22.7.3      | 1         | 1.19%   |
| OpenBSD 7.3          | 1         | 1.19%   |
| OpenBSD 7.2          | 1         | 1.19%   |
| OpenBSD 6.9          | 1         | 1.19%   |
| NomadBSD 5806f915    | 1         | 1.19%   |
| NomadBSD 1.3.1       | 1         | 1.19%   |
| helloSystem 0.4.0    | 1         | 1.19%   |
| GhostBSD 22.01.12    | 1         | 1.19%   |
| GhostBSD 21.08.27    | 1         | 1.19%   |
| FreeBSD 13.1-STABLE  | 1         | 1.19%   |
| FreeBSD 13.1-BETA1   | 1         | 1.19%   |
| FreeBSD 13.1         | 1         | 1.19%   |
| FreeBSD 13.0-RC2     | 1         | 1.19%   |
| FreeBSD 13.0-p7      | 1         | 1.19%   |
| FreeBSD 13.0-BETA2   | 1         | 1.19%   |
| FreeBSD 13.0         | 1         | 1.19%   |
| FreeBSD 12.3-p1      | 1         | 1.19%   |
| FreeBSD 12.2-p2      | 1         | 1.19%   |
| FreeBSD 12.1-p4      | 1         | 1.19%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 27        | 35.53%  |
| helloSystem | 23        | 30.26%  |
| OpenBSD     | 12        | 15.79%  |
| OPNsense    | 6         | 7.89%   |
| GhostBSD    | 6         | 7.89%   |
| NomadBSD    | 2         | 2.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 74        | 97.37%  |
| i386  | 2         | 2.63%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 25        | 32.89%  |
| fvwm         | 10        | 13.16%  |
| Console      | 9         | 11.84%  |
| XFCE         | 8         | 10.53%  |
| MATE         | 8         | 10.53%  |
| Openbox      | 4         | 5.26%   |
| KDE5         | 4         | 5.26%   |
| TWM          | 3         | 3.95%   |
| i3           | 3         | 3.95%   |
| GNOME        | 2         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 67        | 87.01%  |
| Console | 10        | 12.99%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 33        | 43.42%  |
| Console | 28        | 36.84%  |
| SDDM    | 7         | 9.21%   |
| LightDM | 6         | 7.89%   |
| XDM     | 2         | 2.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 22        | 28.21%  |
| en_US          | 19        | 24.36%  |
| C              | 15        | 19.23%  |
| pl_PL          | 14        | 17.95%  |
| fr_FR          | 5         | 6.41%   |
| pl             | 1         | 1.28%   |
| en_IE.US-ASCII | 1         | 1.28%   |
| en             | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 62        | 80.52%  |
| BIOS | 15        | 19.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 43        | 56.58%  |
| Ufs    | 12        | 15.79%  |
| Ffs    | 12        | 15.79%  |
| Cd9660 | 9         | 11.84%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 64        | 84.21%  |
| MBR  | 12        | 15.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 30        | 39.47%  |
| Dell             | 17        | 22.37%  |
| Hewlett-Packard  | 7         | 9.21%   |
| Acer             | 3         | 3.95%   |
| Unknown          | 3         | 3.95%   |
| Google           | 2         | 2.63%   |
| Deciso           | 2         | 2.63%   |
| ASUSTek Computer | 2         | 2.63%   |
| Sony             | 1         | 1.32%   |
| PC Specialist    | 1         | 1.32%   |
| Panasonic        | 1         | 1.32%   |
| Packard Bell     | 1         | 1.32%   |
| Notebook         | 1         | 1.32%   |
| Medion           | 1         | 1.32%   |
| Intel            | 1         | 1.32%   |
| IBM              | 1         | 1.32%   |
| Fujitsu Siemens  | 1         | 1.32%   |
| Fujitsu          | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G               | 5         | 6.58%   |
| Unknown                                    | 4         | 5.26%   |
| Dell Latitude E6430                        | 2         | 2.63%   |
| Sony SVF1521K1EB                           | 1         | 1.32%   |
| PC Specialist Recoil II                    | 1         | 1.32%   |
| Panasonic CFMX4-1                          | 1         | 1.32%   |
| Packard Bell EasyNote LJ65                 | 1         | 1.32%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 1.32%   |
| Medion E15302                              | 1         | 1.32%   |
| Lenovo ThinkPad X260 20F5S10W0H            | 1         | 1.32%   |
| Lenovo ThinkPad X230 23254S6               | 1         | 1.32%   |
| Lenovo ThinkPad X200s 7470A98              | 1         | 1.32%   |
| Lenovo ThinkPad X200 74591P0               | 1         | 1.32%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00FSUS | 1         | 1.32%   |
| Lenovo ThinkPad W520 4284W5L               | 1         | 1.32%   |
| Lenovo ThinkPad T540p 20BFS10W03           | 1         | 1.32%   |
| Lenovo ThinkPad T530 24297XG               | 1         | 1.32%   |
| Lenovo ThinkPad T500 205663G               | 1         | 1.32%   |
| Lenovo ThinkPad T495 20NJ0010PB            | 1         | 1.32%   |
| Lenovo ThinkPad T480 20L6S5VP4C            | 1         | 1.32%   |
| Lenovo ThinkPad T480 20L6S4GR02            | 1         | 1.32%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01      | 1         | 1.32%   |
| Lenovo ThinkPad T440 20B7S1860W            | 1         | 1.32%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB      | 1         | 1.32%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200      | 1         | 1.32%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH09       | 1         | 1.32%   |
| Lenovo ThinkPad A275 20KCS07010            | 1         | 1.32%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.32%   |
| Lenovo IdeaPad S130-14IGM 81J2             | 1         | 1.32%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 1.32%   |
| Lenovo G580 20150                          | 1         | 1.32%   |
| Lenovo G500s 20245                         | 1         | 1.32%   |
| Lenovo G50-30 80G0                         | 1         | 1.32%   |
| Intel H81U                                 | 1         | 1.32%   |
| IBM ThinkPad X41 2525FAG                   | 1         | 1.32%   |
| HP SpectreXT Pro 13-b000 PC                | 1         | 1.32%   |
| HP Notebook                                | 1         | 1.32%   |
| HP Laptop 15-bs0xx                         | 1         | 1.32%   |
| HP ENVY dv7                                | 1         | 1.32%   |
| HP EliteBook 850 G2                        | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 23        | 30.26%  |
| Dell Latitude         | 12        | 15.79%  |
| Unknown               | 4         | 5.26%   |
| Acer Aspire           | 3         | 3.95%   |
| Lenovo IdeaPad        | 2         | 2.63%   |
| HP EliteBook          | 2         | 2.63%   |
| Dell Vostro           | 2         | 2.63%   |
| Dell Inspiron         | 2         | 2.63%   |
| Sony SVF1521K1EB      | 1         | 1.32%   |
| PC Specialist Recoil  | 1         | 1.32%   |
| Panasonic CFMX4-1     | 1         | 1.32%   |
| Packard Bell EasyNote | 1         | 1.32%   |
| Notebook N85          | 1         | 1.32%   |
| Medion E15302         | 1         | 1.32%   |
| Lenovo Legion         | 1         | 1.32%   |
| Lenovo G580           | 1         | 1.32%   |
| Lenovo G500s          | 1         | 1.32%   |
| Lenovo G50-30         | 1         | 1.32%   |
| Intel H81U            | 1         | 1.32%   |
| IBM ThinkPad          | 1         | 1.32%   |
| HP SpectreXT          | 1         | 1.32%   |
| HP Notebook           | 1         | 1.32%   |
| HP Laptop             | 1         | 1.32%   |
| HP ENVY               | 1         | 1.32%   |
| HP 635                | 1         | 1.32%   |
| Google Sentry         | 1         | 1.32%   |
| Google Lars           | 1         | 1.32%   |
| Fujitsu Siemens AMILO | 1         | 1.32%   |
| Fujitsu CELSIUS       | 1         | 1.32%   |
| Dell G15              | 1         | 1.32%   |
| Deciso NetBoard-A20   | 1         | 1.32%   |
| Deciso NetBoard-A10   | 1         | 1.32%   |
| ASUS X71Vn            | 1         | 1.32%   |
| ASUS X555LB           | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 13.16%  |
| 2013 | 9         | 11.84%  |
| 2012 | 8         | 10.53%  |
| 2009 | 7         | 9.21%   |
| 2018 | 6         | 7.89%   |
| 2016 | 6         | 7.89%   |
| 2021 | 5         | 6.58%   |
| 2022 | 4         | 5.26%   |
| 2017 | 4         | 5.26%   |
| 2020 | 3         | 3.95%   |
| 2014 | 3         | 3.95%   |
| 2011 | 3         | 3.95%   |
| 2010 | 3         | 3.95%   |
| 2015 | 2         | 2.63%   |
| 2006 | 2         | 2.63%   |
| 2008 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 76        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 73        | 96.05%  |
| Yes  | 3         | 3.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 27        | 35.53%  |
| 16.01-24.0 | 22        | 28.95%  |
| 8.01-16.0  | 20        | 26.32%  |
| 32.01-64.0 | 3         | 3.95%   |
| 3.01-4.0   | 2         | 2.63%   |
| 2.01-3.0   | 2         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 46        | 59.74%  |
| 0.51-1.0  | 25        | 32.47%  |
| 1.01-2.0  | 4         | 5.19%   |
| 2.01-3.0  | 1         | 1.3%    |
| 8.01-16.0 | 1         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 50        | 64.1%   |
| 2      | 20        | 25.64%  |
| 0      | 5         | 6.41%   |
| 3      | 3         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 74.03%  |
| Yes       | 20        | 25.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 89.47%  |
| No        | 8         | 10.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 96.05%  |
| No        | 3         | 3.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 64.94%  |
| No        | 27        | 35.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 76        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 15        | 19.23%  |
| Wroclaw                   | 8         | 10.26%  |
| Krakow                    | 8         | 10.26%  |
| Gdansk                    | 7         | 8.97%   |
| Chrusty                   | 3         | 3.85%   |
| Zgierz                    | 2         | 2.56%   |
| Lodz                      | 2         | 2.56%   |
| Grudziądz                | 2         | 2.56%   |
| ЕљwiД™tochЕ‚owice | 1         | 1.28%   |
| Wloszczowa                | 1         | 1.28%   |
| Wieliczka                 | 1         | 1.28%   |
| Świnoujście             | 1         | 1.28%   |
| Swilcza                   | 1         | 1.28%   |
| Starogard Gdański        | 1         | 1.28%   |
| Reda                      | 1         | 1.28%   |
| Radom                     | 1         | 1.28%   |
| Pruszcz Gdanski           | 1         | 1.28%   |
| Poznan                    | 1         | 1.28%   |
| Pobiedziska               | 1         | 1.28%   |
| Pacierzow                 | 1         | 1.28%   |
| Ostrołęka               | 1         | 1.28%   |
| Opole                     | 1         | 1.28%   |
| Miedziana Gora            | 1         | 1.28%   |
| Lublin                    | 1         | 1.28%   |
| Lipie                     | 1         | 1.28%   |
| Leszno                    | 1         | 1.28%   |
| Ledziny                   | 1         | 1.28%   |
| Krasnik                   | 1         | 1.28%   |
| Klobuck                   | 1         | 1.28%   |
| Kielce                    | 1         | 1.28%   |
| Katowice                  | 1         | 1.28%   |
| Jaslo                     | 1         | 1.28%   |
| JarosÅ‚aw              | 1         | 1.28%   |
| Grajewo                   | 1         | 1.28%   |
| Gora Kalwaria             | 1         | 1.28%   |
| Gdynia                    | 1         | 1.28%   |
| CzД™stochowa           | 1         | 1.28%   |
| CheÅ‚mno               | 1         | 1.28%   |
| Bolszewo                  | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 24     | 20%     |
| WDC                 | 8         | 9      | 9.41%   |
| Seagate             | 7         | 8      | 8.24%   |
| Transcend           | 5         | 5      | 5.88%   |
| GOODRAM             | 5         | 5      | 5.88%   |
| Crucial             | 5         | 10     | 5.88%   |
| SK hynix            | 4         | 4      | 4.71%   |
| Hitachi             | 4         | 4      | 4.71%   |
| A-DATA Technology   | 4         | 4      | 4.71%   |
| Toshiba             | 3         | 4      | 3.53%   |
| SanDisk             | 3         | 3      | 3.53%   |
| Kingston            | 3         | 3      | 3.53%   |
| Plextor             | 2         | 2      | 2.35%   |
| NVMe                | 2         | 4      | 2.35%   |
| HGST                | 2         | 3      | 2.35%   |
| PNY                 | 1         | 1      | 1.18%   |
| Patriot             | 1         | 1      | 1.18%   |
| Micron Technology   | 1         | 2      | 1.18%   |
| LITEONIT            | 1         | 1      | 1.18%   |
| LITEON              | 1         | 1      | 1.18%   |
| KIOXIA              | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 1      | 1.18%   |
| China               | 1         | 1      | 1.18%   |
| BIWIN               | 1         | 1      | 1.18%   |
| Apacer              | 1         | 2      | 1.18%   |
| Advantech           | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung HM321HI 320GB                | 5         | 5.68%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2.27%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 2.27%   |
| WDC WD7500BPKT-22PK4T0 752GB         | 1         | 1.14%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 1.14%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.14%   |
| WDC WD3200BEKT-22PVMT0 320GB         | 1         | 1.14%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 1.14%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 1.14%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 1.14%   |
| WDC PC SN530 NVMe 512GB              | 1         | 1.14%   |
| Transcend TS512GMTS952T2 512GB       | 1         | 1.14%   |
| Transcend TS32GMSA370 32GB           | 1         | 1.14%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 1.14%   |
| Transcend TS128GMSA370 128GB         | 1         | 1.14%   |
| Transcend TS120GMTS420S 120GB        | 1         | 1.14%   |
| Toshiba MK6461GSYN 640GB             | 1         | 1.14%   |
| Toshiba KXG6AZNV1T02 1TB             | 1         | 1.14%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 1.14%   |
| SK hynix SC210 mSATA 256GB           | 1         | 1.14%   |
| SK hynix HFS128G39TNF-N3A0A 128GB    | 1         | 1.14%   |
| SK hynix HFM512GDHTNG-8310A 512GB    | 1         | 1.14%   |
| SK hynix BC511 NVMe 256GB            | 1         | 1.14%   |
| Seagate ST9500420AS 500GB            | 1         | 1.14%   |
| Seagate ST9500325AS 500GB            | 1         | 1.14%   |
| Seagate ST9320320AS 320GB            | 1         | 1.14%   |
| Seagate ST9160412AS 160GB            | 1         | 1.14%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.14%   |
| SanDisk SDSSDP128G 128GB             | 1         | 1.14%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.14%   |
| SanDisk SD9TN8W256G1001 256GB        | 1         | 1.14%   |
| Samsung SSD PM871b M.2 2280 128GB    | 1         | 1.14%   |
| Samsung SSD PM830 mSATA 128GB        | 1         | 1.14%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.14%   |
| Samsung SSD 980 1TB                  | 1         | 1.14%   |
| Samsung SSD 970 PRO 1TB              | 1         | 1.14%   |
| Samsung SSD 970 EVO 250GB            | 1         | 1.14%   |
| Samsung SSD 860 QVO 4TB              | 1         | 1.14%   |
| Samsung SSD 860 EVO M.2 2TB          | 1         | 1.14%   |
| Samsung SSD 860 EVO 500GB            | 1         | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 26.92%  |
| WDC                 | 6         | 7      | 23.08%  |
| Samsung Electronics | 5         | 5      | 19.23%  |
| Hitachi             | 4         | 4      | 15.38%  |
| HGST                | 2         | 3      | 7.69%   |
| Toshiba             | 1         | 2      | 3.85%   |
| NVMe                | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 14     | 16.67%  |
| GOODRAM             | 5         | 5      | 11.9%   |
| Transcend           | 4         | 4      | 9.52%   |
| Crucial             | 4         | 9      | 9.52%   |
| SanDisk             | 3         | 3      | 7.14%   |
| Kingston            | 3         | 3      | 7.14%   |
| A-DATA Technology   | 3         | 3      | 7.14%   |
| SK hynix            | 2         | 2      | 4.76%   |
| Plextor             | 2         | 2      | 4.76%   |
| Patriot             | 1         | 1      | 2.38%   |
| NVMe                | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 2      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| LITEON              | 1         | 1      | 2.38%   |
| Gigabyte Technology | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| Apacer              | 1         | 2      | 2.38%   |
| Advantech           | 1         | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 39        | 56     | 48.75%  |
| HDD  | 25        | 30     | 31.25%  |
| NVMe | 16        | 19     | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 86     | 77.78%  |
| NVMe | 16        | 19     | 22.22%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 48        | 67     | 78.69%  |
| 0.51-1.0   | 10        | 15     | 16.39%  |
| 1.01-2.0   | 2         | 2      | 3.28%   |
| 3.01-4.0   | 1         | 2      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 23        | 29.49%  |
| 1-20       | 19        | 24.36%  |
| 251-500    | 15        | 19.23%  |
| 51-100     | 11        | 14.1%   |
| 21-50      | 5         | 6.41%   |
| 501-1000   | 5         | 6.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 67        | 87.01%  |
| 21-50   | 4         | 5.19%   |
| 51-100  | 4         | 5.19%   |
| 101-250 | 2         | 2.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-22PVMT0 320GB              | 1         | 1      | 10%     |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 10%     |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 10%     |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 10%     |
| Seagate ST9160412AS 160GB                 | 1         | 1      | 10%     |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1      | 10%     |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 10%     |
| Kingston SV300S37A240G 240GB              | 1         | 1      | 10%     |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 10%     |
| Crucial CT500MX500SSD1 500GB              | 1         | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 4      | 30%     |
| WDC               | 2         | 2      | 20%     |
| SK hynix          | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| Kingston          | 1         | 1      | 10%     |
| Hitachi           | 1         | 1      | 10%     |
| Crucial           | 1         | 2      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 50%     |
| WDC     | 2         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 60%     |
| SSD  | 4         | 5      | 40%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 63        | 89     | 84%     |
| Malfunc  | 10        | 12     | 13.33%  |
| Detected | 2         | 4      | 2.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 61        | 72.62%  |
| Samsung Electronics       | 5         | 5.95%   |
| AMD                       | 4         | 4.76%   |
| SanDisk                   | 3         | 3.57%   |
| SK hynix                  | 2         | 2.38%   |
| KIOXIA                    | 2         | 2.38%   |
| VIA Technologies          | 1         | 1.19%   |
| Transcend                 | 1         | 1.19%   |
| Toshiba                   | 1         | 1.19%   |
| Silicon Motion            | 1         | 1.19%   |
| Phison Electronics        | 1         | 1.19%   |
| Micron/Crucial Technology | 1         | 1.19%   |
| Biwin Storage Technology  | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 13.64%  |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 11        | 12.5%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 7.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.41%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.41%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.27%   |
| Unknown                                                                        | 2         | 2.27%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.14%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 1.14%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.14%   |
| SK hynix BC511                                                                 | 1         | 1.14%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.14%   |
| SanDisk unknown                                                                | 1         | 1.14%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.14%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.14%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.14%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.14%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.14%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 59        | 70.24%  |
| NVMe | 17        | 20.24%  |
| RAID | 4         | 4.76%   |
| IDE  | 4         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 90.79%  |
| AMD    | 7         | 9.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 7.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 3.95%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 2         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2.63%   |
| Intel Core 2 Duo                            | 2         | 2.63%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 2         | 2.63%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.32%   |
| Intel Pentium M processor                   | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.32%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.32%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.32%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.32%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.32%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.32%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.32%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.32%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.32%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.32%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.32%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 1.32%   |
| Intel Core i5-10200H CPU @ 2.40GHz          | 1         | 1.32%   |
| Intel Core i5 CPU M 560 @ 2.67GH            | 1         | 1.32%   |
| Intel Core i3-5020U CPU @ 2.20GHz           | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 38.16%  |
| Intel Core i7           | 12        | 15.79%  |
| Intel Core 2 Duo        | 11        | 14.47%  |
| Intel Core i3           | 6         | 7.89%   |
| Intel Celeron           | 5         | 6.58%   |
| Other                   | 3         | 3.95%   |
| Intel Pentium Silver    | 1         | 1.32%   |
| Intel Pentium M         | 1         | 1.32%   |
| Intel Pentium Dual-Core | 1         | 1.32%   |
| Intel Celeron M         | 1         | 1.32%   |
| AMD Ryzen Embedded      | 1         | 1.32%   |
| AMD Ryzen 7 PRO         | 1         | 1.32%   |
| AMD Ryzen 5 PRO         | 1         | 1.32%   |
| AMD EPYC                | 1         | 1.32%   |
| AMD E                   | 1         | 1.32%   |
| AMD Athlon              | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 51.32%  |
| 4       | 20        | 26.32%  |
| Unknown | 9         | 11.84%  |
| 8       | 3         | 3.95%   |
| 6       | 2         | 2.63%   |
| 1       | 2         | 2.63%   |
| 12      | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 70        | 92.11%  |
| Unknown | 6         | 7.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 48        | 63.16%  |
| 1       | 17        | 22.37%  |
| Unknown | 11        | 14.47%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 15.79%  |
| IvyBridge     | 12        | 15.79%  |
| Penryn        | 10        | 13.16%  |
| Haswell       | 7         | 9.21%   |
| Skylake       | 6         | 7.89%   |
| Broadwell     | 6         | 7.89%   |
| SandyBridge   | 5         | 6.58%   |
| Zen+          | 2         | 2.63%   |
| Zen           | 2         | 2.63%   |
| Westmere      | 2         | 2.63%   |
| TigerLake     | 2         | 2.63%   |
| P6            | 2         | 2.63%   |
| Core          | 2         | 2.63%   |
| Zen 2         | 1         | 1.32%   |
| Silvermont    | 1         | 1.32%   |
| Goldmont plus | 1         | 1.32%   |
| Excavator     | 1         | 1.32%   |
| CometLake     | 1         | 1.32%   |
| Bobcat        | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 63        | 68.48%  |
| Nvidia           | 19        | 20.65%  |
| AMD              | 9         | 9.78%   |
| VIA Technologies | 1         | 1.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 11.83%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 9         | 9.68%   |
| Intel HD Graphics 5500                                                        | 5         | 5.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 5.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 4.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 4.3%    |
| Intel HD Graphics 620                                                         | 3         | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 3.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 2.15%   |
| Intel UHD Graphics 620                                                        | 2         | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.15%   |
| Intel HD Graphics 510                                                         | 2         | 2.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.15%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.08%   |
| Nvidia GT216M [GeForce GT 240M]                                               | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.08%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.08%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.08%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 1.08%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.08%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.08%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.08%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 420M]                                               | 1         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.08%   |
| Nvidia G96CM [GeForce 9650M GT]                                               | 1         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.08%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.08%   |
| Intel HD Graphics 630                                                         | 1         | 1.08%   |
| Intel HD Graphics                                                             | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 44.74%  |
| Intel + Nvidia | 14        | 18.42%  |
| 2 x Intel      | 11        | 14.47%  |
| 1 x Nvidia     | 5         | 6.58%   |
| 1 x AMD        | 5         | 6.58%   |
| Intel + AMD    | 4         | 5.26%   |
| Other          | 2         | 2.63%   |
| 1 x VIA        | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 65        | 84.42%  |
| Proprietary | 7         | 9.09%   |
| Unknown     | 5         | 6.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 89.61%  |
| 0.51-1.0   | 3         | 3.9%    |
| 0.01-0.5   | 2         | 2.6%    |
| 5.01-6.0   | 1         | 1.3%    |
| 3.01-4.0   | 1         | 1.3%    |
| 1.01-2.0   | 1         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 26.79%  |
| Lenovo                  | 8         | 14.29%  |
| BOE                     | 7         | 12.5%   |
| AU Optronics            | 6         | 10.71%  |
| Chimei Innolux          | 5         | 8.93%   |
| Samsung Electronics     | 3         | 5.36%   |
| InfoVision              | 2         | 3.57%   |
| Chi Mei Optoelectronics | 2         | 3.57%   |
| Philips                 | 1         | 1.79%   |
| PANDA                   | 1         | 1.79%   |
| KTC                     | 1         | 1.79%   |
| JDI                     | 1         | 1.79%   |
| Iiyama                  | 1         | 1.79%   |
| BenQ                    | 1         | 1.79%   |
| AOC                     | 1         | 1.79%   |
| Acer                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 8.93%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 3.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.79%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.79%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.79%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.79%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.79%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.79%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.79%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch                 | 1         | 1.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.79%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.79%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.79%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.79%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 1.79%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch          | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch         | 1         | 1.79%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.79%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE06FB 1920x1080 340x190mm 15.3-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE06C6 1920x1080 340x190mm 15.3-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE06BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.79%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                     | 1         | 1.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 41.82%  |
| 1366x768 (WXGA)    | 17        | 30.91%  |
| 1280x800 (WXGA)    | 7         | 12.73%  |
| 1600x900 (HD+)     | 3         | 5.45%   |
| 2560x1440 (QHD)    | 1         | 1.82%   |
| 1680x1050 (WSXGA+) | 1         | 1.82%   |
| 1440x900 (WXGA+)   | 1         | 1.82%   |
| 1280x1024 (SXGA)   | 1         | 1.82%   |
| Unknown            | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 20        | 36.36%  |
| 13      | 16        | 29.09%  |
| 12      | 11        | 20%     |
| 27      | 2         | 3.64%   |
| 17      | 2         | 3.64%   |
| 24      | 1         | 1.82%   |
| 23      | 1         | 1.82%   |
| 14      | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 64.81%  |
| 201-300     | 13        | 24.07%  |
| 501-600     | 4         | 7.41%   |
| 351-400     | 1         | 1.85%   |
| Unknown     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 41        | 78.85%  |
| 16/10   | 8         | 15.38%  |
| 5/4     | 1         | 1.92%   |
| 3/2     | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 29.09%  |
| 91-100         | 14        | 25.45%  |
| 61-70          | 11        | 20%     |
| 101-110        | 6         | 10.91%  |
| 301-350        | 2         | 3.64%   |
| 201-250        | 2         | 3.64%   |
| 71-80          | 1         | 1.82%   |
| 141-150        | 1         | 1.82%   |
| 121-130        | 1         | 1.82%   |
| Unknown        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 31        | 57.41%  |
| 101-120 | 12        | 22.22%  |
| 51-100  | 8         | 14.81%  |
| 161-240 | 2         | 3.7%    |
| Unknown | 1         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 73.08%  |
| 0     | 15        | 19.23%  |
| 2     | 6         | 7.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 60        | 48.39%  |
| Realtek Semiconductor             | 25        | 20.16%  |
| Qualcomm Atheros                  | 15        | 12.1%   |
| Broadcom                          | 9         | 7.26%   |
| Dell                              | 3         | 2.42%   |
| Qualcomm Atheros Communications   | 2         | 1.61%   |
| AMD                               | 2         | 1.61%   |
| VIA Technologies                  | 1         | 0.81%   |
| Van Ooijen Technische Informatica | 1         | 0.81%   |
| TP-Link                           | 1         | 0.81%   |
| Sierra Wireless                   | 1         | 0.81%   |
| Ralink Technology                 | 1         | 0.81%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.81%   |
| Ericsson Business Mobile Networks | 1         | 0.81%   |
| Atheros                           | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 20        | 12.74%  |
| Intel 82567LM Gigabit Network Connection                                      | 9         | 5.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 4.46%   |
| Intel Wireless 7265                                                           | 5         | 3.18%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 3.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 2.55%   |
| Intel Wireless 8260                                                           | 4         | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 2.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 1.91%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 1.91%   |
| Intel Wireless 7260                                                           | 3         | 1.91%   |
| Intel Wireless 3165                                                           | 3         | 1.91%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 1.91%   |
| Intel Ethernet Connection I218-LM                                             | 3         | 1.91%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 1.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 1.27%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 1.27%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.27%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 1.27%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.27%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 2         | 1.27%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.64%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)              | 1         | 0.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.64%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.64%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 65%     |
| Qualcomm Atheros                | 13        | 16.25%  |
| Broadcom                        | 5         | 6.25%   |
| Realtek Semiconductor           | 3         | 3.75%   |
| Qualcomm Atheros Communications | 2         | 2.5%    |
| Dell                            | 2         | 2.5%    |
| TP-Link                         | 1         | 1.25%   |
| Ralink Technology               | 1         | 1.25%   |
| Atheros                         | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 5         | 6.25%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 6.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 5%      |
| Intel Wireless 8260                                                           | 4         | 5%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 5%      |
| Intel Wireless 8265 / 8275                                                    | 3         | 3.75%   |
| Intel Wireless 7260                                                           | 3         | 3.75%   |
| Intel Wireless 3165                                                           | 3         | 3.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 3.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 2.5%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.5%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 2.5%    |
| Intel Centrino Advanced-N 6235                                                | 2         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 2.5%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 1.25%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.25%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.25%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.25%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 1.25%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.25%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.25%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 1.25%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.25%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.25%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.25%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.25%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 38        | 53.52%  |
| Realtek Semiconductor         | 23        | 32.39%  |
| Broadcom                      | 4         | 5.63%   |
| Qualcomm Atheros              | 2         | 2.82%   |
| AMD                           | 2         | 2.82%   |
| VIA Technologies              | 1         | 1.41%   |
| OnePlus Technology (Shenzhen) | 1         | 1.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 27.78%  |
| Intel 82567LM Gigabit Network Connection                          | 9         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 9.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.17%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.17%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 4.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.78%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.78%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 2         | 2.78%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.39%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 1.39%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.39%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.39%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.39%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 50%     |
| Ethernet | 68        | 46.58%  |
| Modem    | 3         | 2.05%   |
| Unknown  | 2         | 1.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 56        | 56%     |
| Ethernet | 44        | 44%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 82.89%  |
| 1     | 7         | 9.21%   |
| 3     | 3         | 3.95%   |
| 6     | 1         | 1.32%   |
| 5     | 1         | 1.32%   |
| 0     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 62%     |
| Broadcom                        | 7         | 14%     |
| IMC Networks                    | 3         | 6%      |
| Foxconn / Hon Hai               | 3         | 6%      |
| Qualcomm Atheros Communications | 2         | 4%      |
| Realtek Semiconductor           | 1         | 2%      |
| Hewlett-Packard                 | 1         | 2%      |
| Dell                            | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 15        | 30%     |
| Intel AX201 Bluetooth                                    | 6         | 12%     |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 4         | 8%      |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 6%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 2         | 4%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 2%      |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 2%      |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 2%      |
| Intel AX200 Bluetooth                                    | 1         | 2%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 2%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 2%      |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 2%      |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 2%      |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 2%      |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 1         | 2%      |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 2%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 2%      |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 2%      |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 80.95%  |
| AMD                   | 7         | 8.33%   |
| Nvidia                | 6         | 7.14%   |
| VIA Technologies      | 1         | 1.19%   |
| Realtek Semiconductor | 1         | 1.19%   |
| Kingston Technology   | 1         | 1.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 12.62%  |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 10.68%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 10.68%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 5.83%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 5.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.88%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 3.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.94%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.97%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                           | 1         | 0.97%   |
| Nvidia unknown                                                             | 1         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.97%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.97%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.97%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.97%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.97%   |
| Unknown                                                                    | 1         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 28.95%  |
| SK hynix            | 18        | 23.68%  |
| Kingston            | 7         | 9.21%   |
| Micron Technology   | 6         | 7.89%   |
| Unknown             | 5         | 6.58%   |
| Goodram             | 5         | 6.58%   |
| Ramaxel Technology  | 4         | 5.26%   |
| Transcend           | 2         | 2.63%   |
| Corsair             | 2         | 2.63%   |
| Unknown             | 2         | 2.63%   |
| Nanya Technology    | 1         | 1.32%   |
| G.Skill             | 1         | 1.32%   |
| Elpida              | 1         | 1.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 2.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 2.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 2         | 2.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 2.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 2.47%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 2.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 2.47%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 2.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 2.47%   |
| Unknown                                                   | 2         | 2.47%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 1.23%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                | 1         | 1.23%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 1         | 1.23%   |
| Transcend RAM AQD-SD3L4GN16-S G 4GB SODIMM DDR3 1600MT/s  | 1         | 1.23%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 1         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| SK hynix RAM HMT425S6MFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.23%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.23%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s    | 1         | 1.23%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 1.23%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1867MT/s       | 1         | 1.23%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s     | 1         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.23%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 1         | 1.23%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 1         | 1.23%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s    | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 32        | 50%     |
| DDR4    | 23        | 35.94%  |
| LPDDR4  | 2         | 3.13%   |
| LPDDR3  | 2         | 3.13%   |
| SDRAM   | 1         | 1.56%   |
| DRAM    | 1         | 1.56%   |
| DDR2    | 1         | 1.56%   |
| DDR     | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 93.75%  |
| Unknown      | 2         | 3.13%   |
| Row Of Chips | 1         | 1.56%   |
| DIMM         | 1         | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 33.8%   |
| 4096  | 19        | 26.76%  |
| 2048  | 16        | 22.54%  |
| 16384 | 7         | 9.86%   |
| 1024  | 4         | 5.63%   |
| 512   | 1         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 19        | 26.03%  |
| 2400    | 8         | 10.96%  |
| 2667    | 7         | 9.59%   |
| 1333    | 7         | 9.59%   |
| 3200    | 6         | 8.22%   |
| 2133    | 5         | 6.85%   |
| 1334    | 5         | 6.85%   |
| 800     | 4         | 5.48%   |
| 1867    | 3         | 4.11%   |
| 1067    | 3         | 4.11%   |
| Unknown | 2         | 2.74%   |
| 4267    | 1         | 1.37%   |
| 2048    | 1         | 1.37%   |
| 1066    | 1         | 1.37%   |
| 533     | 1         | 1.37%   |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 42%     |
| Microdia                               | 8         | 16%     |
| Realtek Semiconductor                  | 5         | 10%     |
| Bison Electronics                      | 4         | 8%      |
| IMC Networks                           | 3         | 6%      |
| Ricoh                                  | 2         | 4%      |
| Lite-On Technology                     | 2         | 4%      |
| Syntek                                 | 1         | 2%      |
| Suyin                                  | 1         | 2%      |
| Sunplus Innovation Technology          | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 5         | 10%     |
| Realtek Lenovo EasyCamera                                      | 3         | 6%      |
| Microdia Integrated Webcam                                     | 3         | 6%      |
| Chicony Realtek DMFT RGB                                       | 3         | 6%      |
| Microdia Integrated_Webcam_HD                                  | 2         | 4%      |
| Lite-On Integrated Camera                                      | 2         | 4%      |
| IMC Networks Integrated Camera                                 | 2         | 4%      |
| Chicony Integrated Camera [ThinkPad]                           | 2         | 4%      |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 4%      |
| Syntek Lenovo EasyCamera                                       | 1         | 2%      |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 2%      |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2%      |
| Ricoh Integrated Webcam                                        | 1         | 2%      |
| Ricoh HD Webcam                                                | 1         | 2%      |
| Realtek Integrated_Webcam_HD                                   | 1         | 2%      |
| Realtek HD WebCam                                              | 1         | 2%      |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 2%      |
| Microdia Integrated HD Webcam                                  | 1         | 2%      |
| Microdia Dell Integrated HD Webcam                             | 1         | 2%      |
| Logitech HD Pro Webcam C920                                    | 1         | 2%      |
| IMC Networks EasyCamera                                        | 1         | 2%      |
| Chicony ThinkPad T490 Webcam                                   | 1         | 2%      |
| Chicony HP Integrated Webcam                                   | 1         | 2%      |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2%      |
| Chicony HP HD Webcam                                           | 1         | 2%      |
| Chicony HD WebCam                                              | 1         | 2%      |
| Chicony Front Camera                                           | 1         | 2%      |
| Chicony FJ Camera                                              | 1         | 2%      |
| Chicony 1.3M Webcam                                            | 1         | 2%      |
| Chicony 1.3 MPixel UVC Webcam                                  | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) USB 2.0 UVC 1.3M WebCam | 1         | 2%      |
| Bison USB HD Webcam                                            | 1         | 2%      |
| Bison Lenovo EasyCamera                                        | 1         | 2%      |
| Bison Integrated Camera                                        | 1         | 2%      |
| Bison EasyCamera                                               | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 29.41%  |
| AuthenTec                  | 4         | 23.53%  |
| Validity Sensors           | 3         | 17.65%  |
| Broadcom                   | 3         | 17.65%  |
| STMicroelectronics         | 1         | 5.88%   |
| Shenzhen Goodix Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| AuthenTec AES2810                                                            | 3         | 17.65%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 11.76%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 5.88%   |
| Synaptics WBDI                                                               | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5.88%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.88%   |
| AuthenTec AES2660                                                            | 1         | 5.88%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 34.62%  |
| 1     | 22        | 28.21%  |
| 3     | 14        | 17.95%  |
| 0     | 9         | 11.54%  |
| 4     | 3         | 3.85%   |
| 5     | 2         | 2.56%   |
| 6     | 1         | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 45.86%  |
| Bluetooth                | 18        | 13.53%  |
| Fingerprint reader       | 16        | 12.03%  |
| Card reader              | 14        | 10.53%  |
| Net/wireless             | 10        | 7.52%   |
| Graphics card            | 8         | 6.02%   |
| Firewire controller      | 3         | 2.26%   |
| Network                  | 2         | 1.5%    |
| Modem                    | 1         | 0.75%   |

