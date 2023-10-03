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

Total: 110

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | XPS 9320                    | [d80b3d5a54](https://bsd-hardware.info/?probe=d80b3d5a54) | Sep 14, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| ASUSTek       | X555LD                      | [9c0c41b663](https://bsd-hardware.info/?probe=9c0c41b663) | Jul 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [386a80104d](https://bsd-hardware.info/?probe=386a80104d) | Jul 19, 2023 |
| Unknown       | Unknown                     | [13c087ef5e](https://bsd-hardware.info/?probe=13c087ef5e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1aff07438c](https://bsd-hardware.info/?probe=1aff07438c) | Jun 28, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
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
| helloSystem 0.8.1    | 14        | 15.05%  |
| OpenBSD 7.0          | 5         | 5.38%   |
| FreeBSD 14.0-CURRENT | 5         | 5.38%   |
| OpenBSD 7.1          | 4         | 4.3%    |
| helloSystem 0.7.0    | 4         | 4.3%    |
| GhostBSD 20.04.02    | 4         | 4.3%    |
| FreeBSD 13.2         | 4         | 4.3%    |
| FreeBSD 12.2         | 4         | 4.3%    |
| OpenBSD 7.3          | 3         | 3.23%   |
| helloSystem 0.5.0    | 3         | 3.23%   |
| FreeBSD 12.1         | 3         | 3.23%   |
| OPNsense 22.7.10     | 2         | 2.15%   |
| OpenBSD 6.8          | 2         | 2.15%   |
| helloSystem 0.8.2    | 2         | 2.15%   |
| helloSystem 0.8.0    | 2         | 2.15%   |
| helloSystem 0.6.0    | 2         | 2.15%   |
| FreeBSD 13.0-p5      | 2         | 2.15%   |
| FreeBSD 13.0-p4      | 2         | 2.15%   |
| FreeBSD 13.0-p2      | 2         | 2.15%   |
| OPNsense 23.4        | 1         | 1.08%   |
| OPNsense 23.1.9      | 1         | 1.08%   |
| OPNsense 23.1.7      | 1         | 1.08%   |
| OPNsense 23.1.11     | 1         | 1.08%   |
| OPNsense 22.7.3      | 1         | 1.08%   |
| OpenBSD 7.2          | 1         | 1.08%   |
| OpenBSD 6.9          | 1         | 1.08%   |
| NomadBSD 5806f915    | 1         | 1.08%   |
| NomadBSD 1.3.1       | 1         | 1.08%   |
| helloSystem 0.4.0    | 1         | 1.08%   |
| GhostBSD 23.07.13    | 1         | 1.08%   |
| GhostBSD 22.01.12    | 1         | 1.08%   |
| GhostBSD 21.08.27    | 1         | 1.08%   |
| FreeBSD 13.1-STABLE  | 1         | 1.08%   |
| FreeBSD 13.1-BETA1   | 1         | 1.08%   |
| FreeBSD 13.1         | 1         | 1.08%   |
| FreeBSD 13.0-RC2     | 1         | 1.08%   |
| FreeBSD 13.0-p7      | 1         | 1.08%   |
| FreeBSD 13.0-BETA2   | 1         | 1.08%   |
| FreeBSD 13.0         | 1         | 1.08%   |
| FreeBSD 12.3-p1      | 1         | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 28        | 33.33%  |
| helloSystem | 27        | 32.14%  |
| OpenBSD     | 13        | 15.48%  |
| OPNsense    | 7         | 8.33%   |
| GhostBSD    | 7         | 8.33%   |
| NomadBSD    | 2         | 2.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 82        | 97.62%  |
| i386  | 2         | 2.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 30        | 35.71%  |
| fvwm         | 10        | 11.9%   |
| Console      | 10        | 11.9%   |
| XFCE         | 9         | 10.71%  |
| MATE         | 8         | 9.52%   |
| KDE5         | 5         | 5.95%   |
| Openbox      | 4         | 4.76%   |
| TWM          | 3         | 3.57%   |
| i3           | 3         | 3.57%   |
| GNOME        | 2         | 2.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 74        | 87.06%  |
| Console | 11        | 12.94%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 37        | 44.05%  |
| Console | 31        | 36.9%   |
| SDDM    | 7         | 8.33%   |
| LightDM | 7         | 8.33%   |
| XDM     | 2         | 2.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 24        | 27.91%  |
| en_US          | 19        | 22.09%  |
| pl_PL          | 18        | 20.93%  |
| C              | 16        | 18.6%   |
| fr_FR          | 6         | 6.98%   |
| pl             | 1         | 1.16%   |
| en_IE.US-ASCII | 1         | 1.16%   |
| en             | 1         | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 82.35%  |
| BIOS | 15        | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 47        | 55.95%  |
| Ufs    | 13        | 15.48%  |
| Ffs    | 13        | 15.48%  |
| Cd9660 | 11        | 13.1%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 72        | 85.71%  |
| MBR  | 12        | 14.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 38.1%   |
| Dell                | 19        | 22.62%  |
| Hewlett-Packard     | 8         | 9.52%   |
| Unknown             | 4         | 4.76%   |
| ASUSTek Computer    | 3         | 3.57%   |
| Acer                | 3         | 3.57%   |
| Google              | 2         | 2.38%   |
| Deciso              | 2         | 2.38%   |
| Sony                | 1         | 1.19%   |
| Samsung Electronics | 1         | 1.19%   |
| PC Specialist       | 1         | 1.19%   |
| Panasonic           | 1         | 1.19%   |
| Packard Bell        | 1         | 1.19%   |
| Notebook            | 1         | 1.19%   |
| Medion              | 1         | 1.19%   |
| Intel               | 1         | 1.19%   |
| IBM                 | 1         | 1.19%   |
| Fujitsu Siemens     | 1         | 1.19%   |
| Fujitsu             | 1         | 1.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G               | 5         | 5.95%   |
| Unknown                                    | 5         | 5.95%   |
| Dell Latitude E6430                        | 2         | 2.38%   |
| Sony SVF1521K1EB                           | 1         | 1.19%   |
| Samsung R530/R730/R540                     | 1         | 1.19%   |
| PC Specialist Recoil II                    | 1         | 1.19%   |
| Panasonic CFMX4-1                          | 1         | 1.19%   |
| Packard Bell EasyNote LJ65                 | 1         | 1.19%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 1.19%   |
| Medion E15302                              | 1         | 1.19%   |
| Lenovo ThinkPad X260 20F5S10W0H            | 1         | 1.19%   |
| Lenovo ThinkPad X230 23254S6               | 1         | 1.19%   |
| Lenovo ThinkPad X200s 7470A98              | 1         | 1.19%   |
| Lenovo ThinkPad X200 74591P0               | 1         | 1.19%   |
| Lenovo ThinkPad X200 7458WNZ               | 1         | 1.19%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QV001CPB  | 1         | 1.19%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00FSUS | 1         | 1.19%   |
| Lenovo ThinkPad W520 4284W5L               | 1         | 1.19%   |
| Lenovo ThinkPad T540p 20BFS10W03           | 1         | 1.19%   |
| Lenovo ThinkPad T530 24297XG               | 1         | 1.19%   |
| Lenovo ThinkPad T500 205663G               | 1         | 1.19%   |
| Lenovo ThinkPad T495 20NJ0010PB            | 1         | 1.19%   |
| Lenovo ThinkPad T480 20L6S5VP4C            | 1         | 1.19%   |
| Lenovo ThinkPad T480 20L6S4GR02            | 1         | 1.19%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01      | 1         | 1.19%   |
| Lenovo ThinkPad T440 20B7S1860W            | 1         | 1.19%   |
| Lenovo ThinkPad T14s Gen 1 20UH0019PB      | 1         | 1.19%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200      | 1         | 1.19%   |
| Lenovo ThinkPad T14 Gen 1 20S1SFJH09       | 1         | 1.19%   |
| Lenovo ThinkPad A275 20KCS07010            | 1         | 1.19%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.19%   |
| Lenovo IdeaPad S130-14IGM 81J2             | 1         | 1.19%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 1.19%   |
| Lenovo G580 20150                          | 1         | 1.19%   |
| Lenovo G500s 20245                         | 1         | 1.19%   |
| Lenovo G50-30 80G0                         | 1         | 1.19%   |
| Intel H81U                                 | 1         | 1.19%   |
| IBM ThinkPad X41 2525FAG                   | 1         | 1.19%   |
| HP SpectreXT Pro 13-b000 PC                | 1         | 1.19%   |
| HP Notebook                                | 1         | 1.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 25        | 29.76%  |
| Dell Latitude         | 13        | 15.48%  |
| Unknown               | 5         | 5.95%   |
| HP EliteBook          | 3         | 3.57%   |
| Acer Aspire           | 3         | 3.57%   |
| Lenovo IdeaPad        | 2         | 2.38%   |
| Dell Vostro           | 2         | 2.38%   |
| Dell Inspiron         | 2         | 2.38%   |
| Sony SVF1521K1EB      | 1         | 1.19%   |
| Samsung R530          | 1         | 1.19%   |
| PC Specialist Recoil  | 1         | 1.19%   |
| Panasonic CFMX4-1     | 1         | 1.19%   |
| Packard Bell EasyNote | 1         | 1.19%   |
| Notebook N85          | 1         | 1.19%   |
| Medion E15302         | 1         | 1.19%   |
| Lenovo Legion         | 1         | 1.19%   |
| Lenovo G580           | 1         | 1.19%   |
| Lenovo G500s          | 1         | 1.19%   |
| Lenovo G50-30         | 1         | 1.19%   |
| Intel H81U            | 1         | 1.19%   |
| IBM ThinkPad          | 1         | 1.19%   |
| HP SpectreXT          | 1         | 1.19%   |
| HP Notebook           | 1         | 1.19%   |
| HP Laptop             | 1         | 1.19%   |
| HP ENVY               | 1         | 1.19%   |
| HP 635                | 1         | 1.19%   |
| Google Sentry         | 1         | 1.19%   |
| Google Lars           | 1         | 1.19%   |
| Fujitsu Siemens AMILO | 1         | 1.19%   |
| Fujitsu CELSIUS       | 1         | 1.19%   |
| Dell XPS              | 1         | 1.19%   |
| Dell G15              | 1         | 1.19%   |
| Deciso NetBoard-A20   | 1         | 1.19%   |
| Deciso NetBoard-A10   | 1         | 1.19%   |
| ASUS X71Vn            | 1         | 1.19%   |
| ASUS X555LD           | 1         | 1.19%   |
| ASUS X555LB           | 1         | 1.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 11.9%   |
| 2013 | 9         | 10.71%  |
| 2012 | 8         | 9.52%   |
| 2009 | 8         | 9.52%   |
| 2018 | 7         | 8.33%   |
| 2016 | 6         | 7.14%   |
| 2022 | 5         | 5.95%   |
| 2021 | 5         | 5.95%   |
| 2010 | 5         | 5.95%   |
| 2020 | 4         | 4.76%   |
| 2017 | 4         | 4.76%   |
| 2014 | 4         | 4.76%   |
| 2011 | 3         | 3.57%   |
| 2015 | 2         | 2.38%   |
| 2006 | 2         | 2.38%   |
| 2023 | 1         | 1.19%   |
| 2008 | 1         | 1.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 84        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 96.43%  |
| Yes  | 3         | 3.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 28        | 33.33%  |
| 16.01-24.0 | 24        | 28.57%  |
| 8.01-16.0  | 23        | 27.38%  |
| 32.01-64.0 | 4         | 4.76%   |
| 3.01-4.0   | 3         | 3.57%   |
| 2.01-3.0   | 2         | 2.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 51        | 60%     |
| 0.51-1.0  | 27        | 31.76%  |
| 1.01-2.0  | 5         | 5.88%   |
| 2.01-3.0  | 1         | 1.18%   |
| 8.01-16.0 | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 55        | 63.95%  |
| 2      | 23        | 26.74%  |
| 0      | 5         | 5.81%   |
| 3      | 3         | 3.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 74.12%  |
| Yes       | 22        | 25.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 89.29%  |
| No        | 9         | 10.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 95.24%  |
| No        | 4         | 4.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 64.71%  |
| No        | 30        | 35.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 84        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 15        | 17.24%  |
| Wroclaw                   | 10        | 11.49%  |
| Krakow                    | 9         | 10.34%  |
| Gdansk                    | 7         | 8.05%   |
| Chrusty                   | 3         | 3.45%   |
| Zgierz                    | 2         | 2.3%    |
| Lublin                    | 2         | 2.3%    |
| Lodz                      | 2         | 2.3%    |
| Grudziądz                | 2         | 2.3%    |
| ЕљwiД™tochЕ‚owice | 1         | 1.15%   |
| Wloszczowa                | 1         | 1.15%   |
| Wieliczka                 | 1         | 1.15%   |
| Świnoujście             | 1         | 1.15%   |
| Swilcza                   | 1         | 1.15%   |
| Starogard Gdański        | 1         | 1.15%   |
| Reda                      | 1         | 1.15%   |
| Radom                     | 1         | 1.15%   |
| Pruszcz Gdanski           | 1         | 1.15%   |
| Poznan                    | 1         | 1.15%   |
| Pobiedziska               | 1         | 1.15%   |
| Piaseczno                 | 1         | 1.15%   |
| Pacierzow                 | 1         | 1.15%   |
| Ostrołęka               | 1         | 1.15%   |
| Opole                     | 1         | 1.15%   |
| Mosina                    | 1         | 1.15%   |
| Miedziana Gora            | 1         | 1.15%   |
| Lochowo                   | 1         | 1.15%   |
| Lipie                     | 1         | 1.15%   |
| Leszno                    | 1         | 1.15%   |
| Ledziny                   | 1         | 1.15%   |
| Krasnik                   | 1         | 1.15%   |
| Klobuck                   | 1         | 1.15%   |
| Kielce                    | 1         | 1.15%   |
| Katowice                  | 1         | 1.15%   |
| Jaslo                     | 1         | 1.15%   |
| Jarosław                 | 1         | 1.15%   |
| JarosÅ‚aw              | 1         | 1.15%   |
| Grajewo                   | 1         | 1.15%   |
| Gora Kalwaria             | 1         | 1.15%   |
| Gdynia                    | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 27     | 21.05%  |
| Seagate             | 9         | 10     | 9.47%   |
| WDC                 | 8         | 9      | 8.42%   |
| GOODRAM             | 6         | 6      | 6.32%   |
| Transcend           | 5         | 5      | 5.26%   |
| Crucial             | 5         | 10     | 5.26%   |
| Toshiba             | 4         | 5      | 4.21%   |
| SK hynix            | 4         | 4      | 4.21%   |
| Kingston            | 4         | 4      | 4.21%   |
| Hitachi             | 4         | 4      | 4.21%   |
| A-DATA Technology   | 4         | 4      | 4.21%   |
| SanDisk             | 3         | 3      | 3.16%   |
| NVMe                | 3         | 5      | 3.16%   |
| Plextor             | 2         | 2      | 2.11%   |
| HGST                | 2         | 3      | 2.11%   |
| PNY                 | 1         | 1      | 1.05%   |
| Patriot             | 1         | 1      | 1.05%   |
| Micron Technology   | 1         | 2      | 1.05%   |
| LITEONIT            | 1         | 1      | 1.05%   |
| LITEON              | 1         | 1      | 1.05%   |
| KIOXIA              | 1         | 1      | 1.05%   |
| Intel               | 1         | 1      | 1.05%   |
| Gigabyte Technology | 1         | 1      | 1.05%   |
| China               | 1         | 1      | 1.05%   |
| BIWIN               | 1         | 1      | 1.05%   |
| Apacer              | 1         | 3      | 1.05%   |
| Advantech           | 1         | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung HM321HI 320GB                | 6         | 6.12%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2.04%   |
| GOODRAM SSDPR-CX400-512-G2 512GB     | 2         | 2.04%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 2.04%   |
| WDC WD7500BPKT-22PK4T0 752GB         | 1         | 1.02%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 1.02%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1.02%   |
| WDC WD3200BEKT-22PVMT0 320GB         | 1         | 1.02%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 1.02%   |
| WDC WD1200BEVS-07LAT0 120GB          | 1         | 1.02%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 1.02%   |
| WDC PC SN530 NVMe 512GB              | 1         | 1.02%   |
| Transcend TS512GMTS952T2 512GB       | 1         | 1.02%   |
| Transcend TS32GMSA370 32GB           | 1         | 1.02%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 1.02%   |
| Transcend TS128GMSA370 128GB         | 1         | 1.02%   |
| Transcend TS120GMTS420S 120GB        | 1         | 1.02%   |
| Toshiba MK6461GSYN 640GB             | 1         | 1.02%   |
| Toshiba MK1252GSX 120GB              | 1         | 1.02%   |
| Toshiba KXG6AZNV1T02 1TB             | 1         | 1.02%   |
| Toshiba KBG40ZNS256G NVMe 256GB      | 1         | 1.02%   |
| SK hynix SC210 mSATA 256GB           | 1         | 1.02%   |
| SK hynix HFS128G39TNF-N3A0A 128GB    | 1         | 1.02%   |
| SK hynix HFM512GDHTNG-8310A 512GB    | 1         | 1.02%   |
| SK hynix BC511 NVMe 256GB            | 1         | 1.02%   |
| Seagate ST9500420AS 500GB            | 1         | 1.02%   |
| Seagate ST9500325AS 500GB            | 1         | 1.02%   |
| Seagate ST9320320AS 320GB            | 1         | 1.02%   |
| Seagate ST9250410AS 250GB            | 1         | 1.02%   |
| Seagate ST9160412AS 160GB            | 1         | 1.02%   |
| Seagate ST500LM000-1EJ162 500GB      | 1         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.02%   |
| SanDisk SDSSDP128G 128GB             | 1         | 1.02%   |
| SanDisk SDSSDA120G 120GB             | 1         | 1.02%   |
| SanDisk SD9TN8W256G1001 256GB        | 1         | 1.02%   |
| Samsung SSD PM871b M.2 2280 128GB    | 1         | 1.02%   |
| Samsung SSD PM830 mSATA 128GB        | 1         | 1.02%   |
| Samsung SSD 980 PRO 1TB              | 1         | 1.02%   |
| Samsung SSD 980 1TB                  | 1         | 1.02%   |
| Samsung SSD 970 PRO 1TB              | 1         | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 30%     |
| WDC                 | 6         | 7      | 20%     |
| Samsung Electronics | 6         | 6      | 20%     |
| Hitachi             | 4         | 4      | 13.33%  |
| Toshiba             | 2         | 3      | 6.67%   |
| HGST                | 2         | 3      | 6.67%   |
| NVMe                | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 14     | 15.91%  |
| GOODRAM             | 6         | 6      | 13.64%  |
| Transcend           | 4         | 4      | 9.09%   |
| Kingston            | 4         | 4      | 9.09%   |
| Crucial             | 4         | 9      | 9.09%   |
| SanDisk             | 3         | 3      | 6.82%   |
| A-DATA Technology   | 3         | 3      | 6.82%   |
| SK hynix            | 2         | 2      | 4.55%   |
| Plextor             | 2         | 2      | 4.55%   |
| Patriot             | 1         | 1      | 2.27%   |
| NVMe                | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 2      | 2.27%   |
| LITEONIT            | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| Gigabyte Technology | 1         | 1      | 2.27%   |
| China               | 1         | 1      | 2.27%   |
| Apacer              | 1         | 3      | 2.27%   |
| Advantech           | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 41        | 59     | 46.59%  |
| HDD  | 28        | 34     | 31.82%  |
| NVMe | 19        | 23     | 21.59%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 61        | 93     | 76.25%  |
| NVMe | 19        | 23     | 23.75%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 72     | 77.61%  |
| 0.51-1.0   | 12        | 17     | 17.91%  |
| 1.01-2.0   | 2         | 2      | 2.99%   |
| 3.01-4.0   | 1         | 2      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 25        | 29.07%  |
| 1-20       | 21        | 24.42%  |
| 251-500    | 17        | 19.77%  |
| 51-100     | 13        | 15.12%  |
| 21-50      | 5         | 5.81%   |
| 501-1000   | 5         | 5.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 74        | 86.05%  |
| 21-50   | 5         | 5.81%   |
| 51-100  | 4         | 4.65%   |
| 101-250 | 3         | 3.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-22PVMT0 320GB              | 1         | 1      | 8.33%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 8.33%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 8.33%   |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 8.33%   |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 8.33%   |
| Seagate ST9160412AS 160GB                 | 1         | 1      | 8.33%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 1      | 8.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 8.33%   |
| Kingston SV300S37A240G 240GB              | 1         | 1      | 8.33%   |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 8.33%   |
| Crucial CT500MX500SSD1 500GB              | 1         | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 5      | 33.33%  |
| WDC               | 2         | 2      | 16.67%  |
| Toshiba           | 1         | 1      | 8.33%   |
| SK hynix          | 1         | 1      | 8.33%   |
| Micron Technology | 1         | 1      | 8.33%   |
| Kingston          | 1         | 1      | 8.33%   |
| Hitachi           | 1         | 1      | 8.33%   |
| Crucial           | 1         | 2      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 9      | 63.64%  |
| SSD  | 4         | 5      | 36.36%  |

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
| Works    | 69        | 97     | 83.13%  |
| Malfunc  | 11        | 14     | 13.25%  |
| Detected | 3         | 5      | 3.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 67        | 72.04%  |
| Samsung Electronics       | 8         | 8.6%    |
| AMD                       | 4         | 4.3%    |
| SanDisk                   | 3         | 3.23%   |
| SK hynix                  | 2         | 2.15%   |
| KIOXIA                    | 2         | 2.15%   |
| VIA Technologies          | 1         | 1.08%   |
| Transcend                 | 1         | 1.08%   |
| Toshiba                   | 1         | 1.08%   |
| Silicon Motion            | 1         | 1.08%   |
| Phison Electronics        | 1         | 1.08%   |
| Micron/Crucial Technology | 1         | 1.08%   |
| Biwin Storage Technology  | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 12.37%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 12.37%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 7.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 5.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 5.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 5.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 4.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3         | 3.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 2.06%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 2.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.06%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.03%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 1.03%   |
| Transcend NVMe PCIe SSD 120S/112S (DRAM-less)                                  | 1         | 1.03%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.03%   |
| SK hynix BC511 NVMe SSD                                                        | 1         | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.03%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.03%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.03%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.03%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 1.03%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.03%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.03%   |
| Biwin Storage EX900 NVMe SSD (DRAM-less)                                       | 1         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 64        | 69.57%  |
| NVMe | 20        | 21.74%  |
| RAID | 4         | 4.35%   |
| IDE  | 4         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 91.67%  |
| AMD    | 7         | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 7         | 8.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 3.57%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 2         | 2.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 2.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 2.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 2.38%   |
| Intel Core 2 Duo                            | 2         | 2.38%   |
| Intel Celeron CPU 3855U @ 1.60GHz           | 2         | 2.38%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.19%   |
| Intel Pentium M processor                   | 1         | 1.19%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.19%   |
| Intel Genuine CPU                           | 1         | 1.19%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.19%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 1         | 1.19%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 1.19%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.19%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.19%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 1         | 1.19%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.19%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 1.19%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.19%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.19%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.19%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.19%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.19%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.19%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.19%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.19%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.19%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 38.1%   |
| Intel Core i7           | 13        | 15.48%  |
| Intel Core 2 Duo        | 12        | 14.29%  |
| Intel Core i3           | 7         | 8.33%   |
| Intel Celeron           | 5         | 5.95%   |
| Other                   | 4         | 4.76%   |
| Intel Pentium Silver    | 1         | 1.19%   |
| Intel Pentium M         | 1         | 1.19%   |
| Intel Pentium Dual-Core | 1         | 1.19%   |
| Intel Genuine           | 1         | 1.19%   |
| Intel Celeron M         | 1         | 1.19%   |
| AMD Ryzen Embedded      | 1         | 1.19%   |
| AMD Ryzen 7 PRO         | 1         | 1.19%   |
| AMD Ryzen 5 PRO         | 1         | 1.19%   |
| AMD EPYC                | 1         | 1.19%   |
| AMD E                   | 1         | 1.19%   |
| AMD Athlon              | 1         | 1.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 51.19%  |
| 4       | 22        | 26.19%  |
| Unknown | 10        | 11.9%   |
| 8       | 4         | 4.76%   |
| 6       | 2         | 2.38%   |
| 1       | 2         | 2.38%   |
| 12      | 1         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 78        | 92.86%  |
| Unknown | 6         | 7.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 55        | 65.48%  |
| 1       | 17        | 20.24%  |
| Unknown | 12        | 14.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 16.67%  |
| IvyBridge     | 12        | 14.29%  |
| Penryn        | 11        | 13.1%   |
| Haswell       | 8         | 9.52%   |
| Broadwell     | 7         | 8.33%   |
| Skylake       | 6         | 7.14%   |
| SandyBridge   | 5         | 5.95%   |
| Westmere      | 4         | 4.76%   |
| Zen+          | 2         | 2.38%   |
| Zen           | 2         | 2.38%   |
| TigerLake     | 2         | 2.38%   |
| P6            | 2         | 2.38%   |
| Core          | 2         | 2.38%   |
| Zen 2         | 1         | 1.19%   |
| Silvermont    | 1         | 1.19%   |
| Goldmont plus | 1         | 1.19%   |
| Excavator     | 1         | 1.19%   |
| CometLake     | 1         | 1.19%   |
| Bobcat        | 1         | 1.19%   |
| Unknown       | 1         | 1.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 70        | 69.31%  |
| Nvidia           | 21        | 20.79%  |
| AMD              | 9         | 8.91%   |
| VIA Technologies | 1         | 0.99%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 10.78%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 10        | 9.8%    |
| Intel HD Graphics 5500                                                        | 6         | 5.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 4.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 4.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 3.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 2.94%   |
| Intel UHD Graphics 620                                                        | 3         | 2.94%   |
| Intel HD Graphics 620                                                         | 3         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 2.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 1.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 1.96%   |
| Intel HD Graphics 510                                                         | 2         | 1.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.96%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 0.98%   |
| Nvidia GT216M [GeForce GT 240M]                                               | 1         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 0.98%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.98%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.98%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.98%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 0.98%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 0.98%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.98%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 0.98%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 0.98%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 0.98%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 1         | 0.98%   |
| Nvidia GF108M [GeForce GT 420M]                                               | 1         | 0.98%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.98%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.98%   |
| Nvidia G96CM [GeForce 9650M GT]                                               | 1         | 0.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 0.98%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 0.98%   |
| Intel HD Graphics 630                                                         | 1         | 0.98%   |
| Intel HD Graphics                                                             | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 46.43%  |
| Intel + Nvidia | 15        | 17.86%  |
| 2 x Intel      | 12        | 14.29%  |
| 1 x Nvidia     | 6         | 7.14%   |
| 1 x AMD        | 5         | 5.95%   |
| Intel + AMD    | 4         | 4.76%   |
| Other          | 2         | 2.38%   |
| 1 x VIA        | 1         | 1.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 72        | 84.71%  |
| Proprietary | 8         | 9.41%   |
| Unknown     | 5         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 89.41%  |
| 0.51-1.0   | 3         | 3.53%   |
| 3.01-4.0   | 2         | 2.35%   |
| 0.01-0.5   | 2         | 2.35%   |
| 5.01-6.0   | 1         | 1.18%   |
| 1.01-2.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 25%     |
| Lenovo                  | 9         | 14.06%  |
| BOE                     | 8         | 12.5%   |
| Samsung Electronics     | 6         | 9.38%   |
| Chimei Innolux          | 6         | 9.38%   |
| AU Optronics            | 6         | 9.38%   |
| InfoVision              | 2         | 3.13%   |
| Chi Mei Optoelectronics | 2         | 3.13%   |
| Philips                 | 1         | 1.56%   |
| PANDA                   | 1         | 1.56%   |
| KTC                     | 1         | 1.56%   |
| JDI                     | 1         | 1.56%   |
| Iiyama                  | 1         | 1.56%   |
| BOE Technology Group    | 1         | 1.56%   |
| BenQ                    | 1         | 1.56%   |
| AOC                     | 1         | 1.56%   |
| Acer                    | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 6         | 9.38%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 3.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.13%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch      | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.56%   |
| Samsung Electronics LCD Monitor SDC4163 3456x2160 290x180mm 13.4-inch    | 1         | 1.56%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.56%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.56%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.56%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.56%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch              | 1         | 1.56%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch                 | 1         | 1.56%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.56%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.56%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.56%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.56%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 1.56%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch          | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch         | 1         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.56%   |
| BOE Technology Group LCD Monitor 1920x1080                               | 1         | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 25        | 40.32%  |
| 1366x768 (WXGA)    | 20        | 32.26%  |
| 1280x800 (WXGA)    | 8         | 12.9%   |
| 1600x900 (HD+)     | 3         | 4.84%   |
| 3456x2160          | 1         | 1.61%   |
| 2560x1440 (QHD)    | 1         | 1.61%   |
| 1680x1050 (WSXGA+) | 1         | 1.61%   |
| 1440x900 (WXGA+)   | 1         | 1.61%   |
| 1280x1024 (SXGA)   | 1         | 1.61%   |
| Unknown            | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 22        | 34.92%  |
| 13      | 19        | 30.16%  |
| 12      | 12        | 19.05%  |
| 27      | 3         | 4.76%   |
| 17      | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |
| 24      | 1         | 1.59%   |
| 23      | 1         | 1.59%   |
| 14      | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 61.29%  |
| 201-300     | 16        | 25.81%  |
| 501-600     | 5         | 8.06%   |
| Unknown     | 2         | 3.23%   |
| 351-400     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 45        | 76.27%  |
| 16/10   | 10        | 16.95%  |
| Unknown | 2         | 3.39%   |
| 5/4     | 1         | 1.69%   |
| 3/2     | 1         | 1.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 18        | 28.57%  |
| 91-100         | 16        | 25.4%   |
| 61-70          | 12        | 19.05%  |
| 101-110        | 6         | 9.52%   |
| 301-350        | 3         | 4.76%   |
| 71-80          | 2         | 3.17%   |
| 201-250        | 2         | 3.17%   |
| Unknown        | 2         | 3.17%   |
| 141-150        | 1         | 1.59%   |
| 121-130        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 53.23%  |
| 101-120       | 15        | 24.19%  |
| 51-100        | 9         | 14.52%  |
| 161-240       | 2         | 3.23%   |
| Unknown       | 2         | 3.23%   |
| More than 240 | 1         | 1.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 63        | 73.26%  |
| 0     | 16        | 18.6%   |
| 2     | 7         | 8.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 49.25%  |
| Realtek Semiconductor             | 26        | 19.4%   |
| Qualcomm Atheros                  | 17        | 12.69%  |
| Broadcom                          | 9         | 6.72%   |
| Dell                              | 3         | 2.24%   |
| Qualcomm Atheros Communications   | 2         | 1.49%   |
| AMD                               | 2         | 1.49%   |
| VIA Technologies                  | 1         | 0.75%   |
| Van Ooijen Technische Informatica | 1         | 0.75%   |
| TP-Link                           | 1         | 0.75%   |
| Sierra Wireless                   | 1         | 0.75%   |
| Ralink Technology                 | 1         | 0.75%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.75%   |
| Marvell Technology Group          | 1         | 0.75%   |
| Ericsson Business Mobile Networks | 1         | 0.75%   |
| Atheros                           | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 12.28%  |
| Intel 82567LM Gigabit Network Connection                          | 10        | 5.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.09%   |
| Intel Ultimate N WiFi Link 5300                                   | 6         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.92%   |
| Intel Wireless 7265                                               | 5         | 2.92%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.34%   |
| Intel Wireless 8260                                               | 4         | 2.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.75%   |
| Intel Wireless 7260                                               | 3         | 1.75%   |
| Intel Wireless 3165                                               | 3         | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.75%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.17%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.17%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.17%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.17%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.17%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.17%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 2         | 1.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.58%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)  | 1         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.58%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 65.52%  |
| Qualcomm Atheros                | 15        | 17.24%  |
| Broadcom                        | 5         | 5.75%   |
| Realtek Semiconductor           | 3         | 3.45%   |
| Qualcomm Atheros Communications | 2         | 2.3%    |
| Dell                            | 2         | 2.3%    |
| TP-Link                         | 1         | 1.15%   |
| Ralink Technology               | 1         | 1.15%   |
| Atheros                         | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Ultimate N WiFi Link 5300                                               | 6         | 6.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 5         | 5.75%   |
| Intel Wireless 7265                                                           | 5         | 5.75%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 4.6%    |
| Intel Wireless 8260                                                           | 4         | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 4.6%    |
| Intel Wireless 7260                                                           | 3         | 3.45%   |
| Intel Wireless 3165                                                           | 3         | 3.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 2         | 2.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 2.3%    |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.3%    |
| Intel Wi-Fi 6 AX200                                                           | 2         | 2.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 2         | 2.3%    |
| Intel Centrino Advanced-N 6235                                                | 2         | 2.3%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 2.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.15%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.15%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.15%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.15%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.15%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.15%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.15%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 1.15%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.15%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 1.15%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 43        | 55.13%  |
| Realtek Semiconductor         | 24        | 30.77%  |
| Broadcom                      | 4         | 5.13%   |
| Qualcomm Atheros              | 2         | 2.56%   |
| AMD                           | 2         | 2.56%   |
| VIA Technologies              | 1         | 1.28%   |
| OnePlus Technology (Shenzhen) | 1         | 1.28%   |
| Marvell Technology Group      | 1         | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 21        | 26.58%  |
| Intel 82567LM Gigabit Network Connection                          | 10        | 12.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 8.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.8%    |
| Intel I211 Gigabit Network Connection                             | 3         | 3.8%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 3.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 3.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.8%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.53%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.53%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.53%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 2         | 2.53%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.27%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.27%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 1.27%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.27%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.27%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.27%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.27%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.27%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.27%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.27%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 50%     |
| Ethernet | 75        | 46.88%  |
| Modem    | 3         | 1.88%   |
| Unknown  | 2         | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 56.48%  |
| Ethernet | 47        | 43.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 82.14%  |
| 1     | 8         | 9.52%   |
| 3     | 3         | 3.57%   |
| 6     | 2         | 2.38%   |
| 5     | 1         | 1.19%   |
| 0     | 1         | 1.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 60%     |
| Broadcom                        | 8         | 14.55%  |
| IMC Networks                    | 3         | 5.45%   |
| Foxconn / Hon Hai               | 3         | 5.45%   |
| Qualcomm Atheros Communications | 2         | 3.64%   |
| Dell                            | 2         | 3.64%   |
| Realtek Semiconductor           | 1         | 1.82%   |
| Lite-On Technology              | 1         | 1.82%   |
| Hewlett-Packard                 | 1         | 1.82%   |
| ASUSTek Computer                | 1         | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 16        | 29.09%  |
| Intel AX201 Bluetooth                                    | 6         | 10.91%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 5         | 9.09%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 5.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 5.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 2         | 3.64%   |
| Intel AX200 Bluetooth                                    | 2         | 3.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 1.82%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 1.82%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 1.82%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 1.82%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 1.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 1.82%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 1.82%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 1.82%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 1.82%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 1         | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 1.82%   |
| Dell DW375 Bluetooth Module                              | 1         | 1.82%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 1.82%   |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 1.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 1.82%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 81.52%  |
| Nvidia                | 7         | 7.61%   |
| AMD                   | 7         | 7.61%   |
| VIA Technologies      | 1         | 1.09%   |
| Realtek Semiconductor | 1         | 1.09%   |
| Kingston Technology   | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 11.5%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 10.62%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 10.62%  |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 6.19%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 6.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 4.42%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 3.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 3.54%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 3.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.77%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.88%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                           | 1         | 0.88%   |
| Nvidia unknown                                                             | 1         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.88%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.88%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 0.88%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.88%   |
| Unknown                                                                    | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 29.41%  |
| SK hynix            | 20        | 23.53%  |
| Kingston            | 9         | 10.59%  |
| Micron Technology   | 7         | 8.24%   |
| Unknown             | 5         | 5.88%   |
| GOODRAM             | 5         | 5.88%   |
| Ramaxel Technology  | 4         | 4.71%   |
| Transcend           | 2         | 2.35%   |
| Nanya Technology    | 2         | 2.35%   |
| Corsair             | 2         | 2.35%   |
| Unknown             | 2         | 2.35%   |
| G.Skill             | 1         | 1.18%   |
| Elpida              | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.2%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.2%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 2.2%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 2.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 2         | 2.2%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s          | 2         | 2.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 2.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 2.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 2.2%    |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 2.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 2.2%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 2.2%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 2.2%    |
| Unknown                                                   | 2         | 2.2%    |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                | 1         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 1.1%    |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                | 1         | 1.1%    |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 1         | 1.1%    |
| Transcend RAM AQD-SD3L4GN16-S G 4GB SODIMM DDR3 1600MT/s  | 1         | 1.1%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 1         | 1.1%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s             | 1         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.1%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.1%    |
| SK hynix RAM HMT425S6MFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.1%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.1%    |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s    | 1         | 1.1%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 1.1%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s   | 1         | 1.1%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 1.1%    |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1867MT/s       | 1         | 1.1%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 1.1%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s     | 1         | 1.1%    |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 800MT/s      | 1         | 1.1%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 37        | 52.11%  |
| DDR4    | 25        | 35.21%  |
| LPDDR4  | 2         | 2.82%   |
| LPDDR3  | 2         | 2.82%   |
| SDRAM   | 1         | 1.41%   |
| DRAM    | 1         | 1.41%   |
| DDR2    | 1         | 1.41%   |
| DDR     | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 94.37%  |
| Unknown      | 2         | 2.82%   |
| Row Of Chips | 1         | 1.41%   |
| DIMM         | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 31.65%  |
| 4096  | 21        | 26.58%  |
| 2048  | 18        | 22.78%  |
| 16384 | 9         | 11.39%  |
| 1024  | 5         | 6.33%   |
| 512   | 1         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 25.93%  |
| 2400    | 9         | 11.11%  |
| 2667    | 8         | 9.88%   |
| 1333    | 7         | 8.64%   |
| 3200    | 6         | 7.41%   |
| 1334    | 6         | 7.41%   |
| 2133    | 5         | 6.17%   |
| 800     | 5         | 6.17%   |
| 1067    | 4         | 4.94%   |
| 1867    | 3         | 3.7%    |
| 1066    | 2         | 2.47%   |
| Unknown | 2         | 2.47%   |
| 4267    | 1         | 1.23%   |
| 2048    | 1         | 1.23%   |
| 533     | 1         | 1.23%   |

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
| Chicony Electronics                    | 24        | 44.44%  |
| Microdia                               | 8         | 14.81%  |
| Realtek Semiconductor                  | 5         | 9.26%   |
| Bison Electronics                      | 4         | 7.41%   |
| IMC Networks                           | 3         | 5.56%   |
| Ricoh                                  | 2         | 3.7%    |
| Lite-On Technology                     | 2         | 3.7%    |
| Syntek                                 | 1         | 1.85%   |
| Suyin                                  | 1         | 1.85%   |
| Sunplus Innovation Technology          | 1         | 1.85%   |
| Logitech                               | 1         | 1.85%   |
| DigiTech                               | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 6         | 11.11%  |
| Realtek Lenovo EasyCamera                                      | 3         | 5.56%   |
| Microdia Integrated Webcam                                     | 3         | 5.56%   |
| Chicony Realtek DMFT RGB                                       | 3         | 5.56%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 3.7%    |
| Lite-On Integrated Camera                                      | 2         | 3.7%    |
| IMC Networks Integrated Camera                                 | 2         | 3.7%    |
| Chicony Integrated Camera [ThinkPad]                           | 2         | 3.7%    |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 3.7%    |
| Syntek Lenovo EasyCamera                                       | 1         | 1.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 1         | 1.85%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.85%   |
| Ricoh Integrated Webcam                                        | 1         | 1.85%   |
| Ricoh HD Webcam                                                | 1         | 1.85%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.85%   |
| Realtek HD WebCam                                              | 1         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 1.85%   |
| Microdia Integrated HD Webcam                                  | 1         | 1.85%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 1.85%   |
| Logitech HD Pro Webcam C920                                    | 1         | 1.85%   |
| IMC Networks EasyCamera                                        | 1         | 1.85%   |
| DigiTech WebCam SCB-0350M                                      | 1         | 1.85%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.85%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 1.85%   |
| Chicony HP Integrated Webcam                                   | 1         | 1.85%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 1.85%   |
| Chicony HP HD Webcam                                           | 1         | 1.85%   |
| Chicony HP HD Camera                                           | 1         | 1.85%   |
| Chicony HD WebCam                                              | 1         | 1.85%   |
| Chicony Front Camera                                           | 1         | 1.85%   |
| Chicony FJ Camera                                              | 1         | 1.85%   |
| Chicony 1.3M Webcam                                            | 1         | 1.85%   |
| Chicony 1.3 MPixel UVC Webcam                                  | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) USB 2.0 UVC 1.3M WebCam | 1         | 1.85%   |
| Bison USB HD Webcam                                            | 1         | 1.85%   |
| Bison Lenovo EasyCamera                                        | 1         | 1.85%   |
| Bison Integrated Camera                                        | 1         | 1.85%   |
| Bison EasyCamera                                               | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 33.33%  |
| AuthenTec                  | 4         | 22.22%  |
| Validity Sensors           | 3         | 16.67%  |
| Broadcom                   | 3         | 16.67%  |
| STMicroelectronics         | 1         | 5.56%   |
| Shenzhen Goodix Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| AuthenTec AES2810                                                            | 3         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 11.11%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 5.56%   |
| Synaptics WBDI                                                               | 1         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 5.56%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 5.56%   |
| AuthenTec AES2660                                                            | 1         | 5.56%   |

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
| 2     | 28        | 32.56%  |
| 1     | 26        | 30.23%  |
| 3     | 15        | 17.44%  |
| 0     | 10        | 11.63%  |
| 5     | 3         | 3.49%   |
| 4     | 3         | 3.49%   |
| 6     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 68        | 47.22%  |
| Bluetooth                | 19        | 13.19%  |
| Fingerprint reader       | 17        | 11.81%  |
| Card reader              | 16        | 11.11%  |
| Net/wireless             | 10        | 6.94%   |
| Graphics card            | 8         | 5.56%   |
| Firewire controller      | 3         | 2.08%   |
| Network                  | 2         | 1.39%   |
| Modem                    | 1         | 0.69%   |

