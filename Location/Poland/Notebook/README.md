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

Total: 91

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| helloSystem 0.8.1    | 8         | 10.67%  |
| OpenBSD 7.0          | 5         | 6.67%   |
| OpenBSD 7.1          | 4         | 5.33%   |
| helloSystem 0.7.0    | 4         | 5.33%   |
| GhostBSD 20.04.02    | 4         | 5.33%   |
| FreeBSD 14.0-CURRENT | 4         | 5.33%   |
| FreeBSD 12.2         | 4         | 5.33%   |
| helloSystem 0.5.0    | 3         | 4%      |
| FreeBSD 12.1         | 3         | 4%      |
| OPNsense 22.7.10     | 2         | 2.67%   |
| OpenBSD 6.8          | 2         | 2.67%   |
| helloSystem 0.8.2    | 2         | 2.67%   |
| helloSystem 0.8.0    | 2         | 2.67%   |
| helloSystem 0.6.0    | 2         | 2.67%   |
| FreeBSD 13.0-p5      | 2         | 2.67%   |
| FreeBSD 13.0-p4      | 2         | 2.67%   |
| FreeBSD 13.0-p2      | 2         | 2.67%   |
| OPNsense 22.7.3      | 1         | 1.33%   |
| OpenBSD 7.2          | 1         | 1.33%   |
| OpenBSD 6.9          | 1         | 1.33%   |
| NomadBSD 5806f915    | 1         | 1.33%   |
| NomadBSD 1.3.1       | 1         | 1.33%   |
| helloSystem 0.4.0    | 1         | 1.33%   |
| GhostBSD 22.01.12    | 1         | 1.33%   |
| GhostBSD 21.08.27    | 1         | 1.33%   |
| FreeBSD 13.2         | 1         | 1.33%   |
| FreeBSD 13.1-STABLE  | 1         | 1.33%   |
| FreeBSD 13.1-BETA1   | 1         | 1.33%   |
| FreeBSD 13.1         | 1         | 1.33%   |
| FreeBSD 13.0-RC2     | 1         | 1.33%   |
| FreeBSD 13.0-p7      | 1         | 1.33%   |
| FreeBSD 13.0-BETA2   | 1         | 1.33%   |
| FreeBSD 13.0         | 1         | 1.33%   |
| FreeBSD 12.3-p1      | 1         | 1.33%   |
| FreeBSD 12.2-p2      | 1         | 1.33%   |
| FreeBSD 12.1-p4      | 1         | 1.33%   |
| FreeBSD 12.1-p10     | 1         | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 24        | 35.82%  |
| helloSystem | 21        | 31.34%  |
| OpenBSD     | 11        | 16.42%  |
| GhostBSD    | 6         | 8.96%   |
| OPNsense    | 3         | 4.48%   |
| NomadBSD    | 2         | 2.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 65        | 97.01%  |
| i386  | 2         | 2.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 22        | 32.84%  |
| fvwm         | 10        | 14.93%  |
| MATE         | 8         | 11.94%  |
| XFCE         | 7         | 10.45%  |
| Console      | 6         | 8.96%   |
| Openbox      | 4         | 5.97%   |
| KDE5         | 4         | 5.97%   |
| TWM          | 3         | 4.48%   |
| i3           | 2         | 2.99%   |
| GNOME        | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 89.71%  |
| Console | 7         | 10.29%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 31        | 46.27%  |
| Console | 23        | 34.33%  |
| SDDM    | 6         | 8.96%   |
| LightDM | 6         | 8.96%   |
| XDM     | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_US          | 18        | 26.09%  |
| Unknown        | 17        | 24.64%  |
| pl_PL          | 14        | 20.29%  |
| C              | 13        | 18.84%  |
| fr_FR          | 4         | 5.8%    |
| pl             | 1         | 1.45%   |
| en_IE.US-ASCII | 1         | 1.45%   |
| en             | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 54        | 79.41%  |
| BIOS | 14        | 20.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 37        | 55.22%  |
| Ufs    | 11        | 16.42%  |
| Ffs    | 11        | 16.42%  |
| Cd9660 | 8         | 11.94%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 56        | 83.58%  |
| MBR  | 11        | 16.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 26        | 38.81%  |
| Dell             | 17        | 25.37%  |
| Hewlett-Packard  | 7         | 10.45%  |
| Acer             | 3         | 4.48%   |
| ASUSTek Computer | 2         | 2.99%   |
| Sony             | 1         | 1.49%   |
| PC Specialist    | 1         | 1.49%   |
| Panasonic        | 1         | 1.49%   |
| Notebook         | 1         | 1.49%   |
| Medion           | 1         | 1.49%   |
| Intel            | 1         | 1.49%   |
| IBM              | 1         | 1.49%   |
| Google           | 1         | 1.49%   |
| Fujitsu Siemens  | 1         | 1.49%   |
| Fujitsu          | 1         | 1.49%   |
| Deciso           | 1         | 1.49%   |
| Unknown          | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G               | 5         | 7.46%   |
| Dell Latitude E6430                        | 2         | 2.99%   |
| Unknown                                    | 2         | 2.99%   |
| Sony SVF1521K1EB                           | 1         | 1.49%   |
| PC Specialist Recoil II                    | 1         | 1.49%   |
| Panasonic CFMX4-1                          | 1         | 1.49%   |
| Notebook N85_N87,HJ,HJ1,HK1                | 1         | 1.49%   |
| Medion E15302                              | 1         | 1.49%   |
| Lenovo ThinkPad X260 20F5S10W0H            | 1         | 1.49%   |
| Lenovo ThinkPad X230 23254S6               | 1         | 1.49%   |
| Lenovo ThinkPad X200s 7470A98              | 1         | 1.49%   |
| Lenovo ThinkPad X200 74591P0               | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00FSUS | 1         | 1.49%   |
| Lenovo ThinkPad W520 4284W5L               | 1         | 1.49%   |
| Lenovo ThinkPad T540p 20BFS10W03           | 1         | 1.49%   |
| Lenovo ThinkPad T530 24297XG               | 1         | 1.49%   |
| Lenovo ThinkPad T495 20NJ0010PB            | 1         | 1.49%   |
| Lenovo ThinkPad T480 20L6S4GR02            | 1         | 1.49%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01      | 1         | 1.49%   |
| Lenovo ThinkPad T440 20B7S1860W            | 1         | 1.49%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200      | 1         | 1.49%   |
| Lenovo ThinkPad A275 20KCS07010            | 1         | 1.49%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.49%   |
| Lenovo IdeaPad S130-14IGM 81J2             | 1         | 1.49%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 1         | 1.49%   |
| Lenovo G580 20150                          | 1         | 1.49%   |
| Lenovo G500s 20245                         | 1         | 1.49%   |
| Lenovo G50-30 80G0                         | 1         | 1.49%   |
| Intel H81U                                 | 1         | 1.49%   |
| IBM ThinkPad X41 2525FAG                   | 1         | 1.49%   |
| HP SpectreXT Pro 13-b000 PC                | 1         | 1.49%   |
| HP Notebook                                | 1         | 1.49%   |
| HP Laptop 15-bs0xx                         | 1         | 1.49%   |
| HP ENVY dv7                                | 1         | 1.49%   |
| HP EliteBook 850 G2                        | 1         | 1.49%   |
| HP EliteBook 840 G3                        | 1         | 1.49%   |
| HP 635                                     | 1         | 1.49%   |
| Google Lars                                | 1         | 1.49%   |
| Fujitsu Siemens AMILO PRO V3515            | 1         | 1.49%   |
| Fujitsu CELSIUS H920                       | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 19        | 28.36%  |
| Dell Latitude         | 12        | 17.91%  |
| Acer Aspire           | 3         | 4.48%   |
| Lenovo IdeaPad        | 2         | 2.99%   |
| HP EliteBook          | 2         | 2.99%   |
| Dell Vostro           | 2         | 2.99%   |
| Dell Inspiron         | 2         | 2.99%   |
| Unknown               | 2         | 2.99%   |
| Sony SVF1521K1EB      | 1         | 1.49%   |
| PC Specialist Recoil  | 1         | 1.49%   |
| Panasonic CFMX4-1     | 1         | 1.49%   |
| Notebook N85          | 1         | 1.49%   |
| Medion E15302         | 1         | 1.49%   |
| Lenovo Legion         | 1         | 1.49%   |
| Lenovo G580           | 1         | 1.49%   |
| Lenovo G500s          | 1         | 1.49%   |
| Lenovo G50-30         | 1         | 1.49%   |
| Intel H81U            | 1         | 1.49%   |
| IBM ThinkPad          | 1         | 1.49%   |
| HP SpectreXT          | 1         | 1.49%   |
| HP Notebook           | 1         | 1.49%   |
| HP Laptop             | 1         | 1.49%   |
| HP ENVY               | 1         | 1.49%   |
| HP 635                | 1         | 1.49%   |
| Google Lars           | 1         | 1.49%   |
| Fujitsu Siemens AMILO | 1         | 1.49%   |
| Fujitsu CELSIUS       | 1         | 1.49%   |
| Dell G15              | 1         | 1.49%   |
| Deciso NetBoard-A10   | 1         | 1.49%   |
| ASUS X71Vn            | 1         | 1.49%   |
| ASUS X555LB           | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 10        | 14.93%  |
| 2013 | 9         | 13.43%  |
| 2012 | 8         | 11.94%  |
| 2009 | 7         | 10.45%  |
| 2018 | 5         | 7.46%   |
| 2017 | 4         | 5.97%   |
| 2016 | 4         | 5.97%   |
| 2022 | 3         | 4.48%   |
| 2021 | 3         | 4.48%   |
| 2014 | 3         | 4.48%   |
| 2011 | 3         | 4.48%   |
| 2020 | 2         | 2.99%   |
| 2015 | 2         | 2.99%   |
| 2006 | 2         | 2.99%   |
| 2010 | 1         | 1.49%   |
| 2008 | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 97.01%  |
| Yes  | 2         | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 23        | 34.33%  |
| 16.01-24.0 | 19        | 28.36%  |
| 8.01-16.0  | 19        | 28.36%  |
| 32.01-64.0 | 2         | 2.99%   |
| 3.01-4.0   | 2         | 2.99%   |
| 2.01-3.0   | 2         | 2.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 41        | 60.29%  |
| 0.51-1.0  | 23        | 33.82%  |
| 1.01-2.0  | 2         | 2.94%   |
| 2.01-3.0  | 1         | 1.47%   |
| 8.01-16.0 | 1         | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 63.77%  |
| 2      | 19        | 27.54%  |
| 3      | 3         | 4.35%   |
| 0      | 3         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 72.06%  |
| Yes       | 19        | 27.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 89.55%  |
| No        | 7         | 10.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 98.51%  |
| No        | 1         | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 67.65%  |
| No        | 22        | 32.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 12        | 17.39%  |
| Wroclaw                   | 7         | 10.14%  |
| Krakow                    | 7         | 10.14%  |
| Gdansk                    | 7         | 10.14%  |
| Chrusty                   | 3         | 4.35%   |
| Lodz                      | 2         | 2.9%    |
| Grudziądz                | 2         | 2.9%    |
| ЕљwiД™tochЕ‚owice | 1         | 1.45%   |
| Zgierz                    | 1         | 1.45%   |
| Wloszczowa                | 1         | 1.45%   |
| Wieliczka                 | 1         | 1.45%   |
| Świnoujście             | 1         | 1.45%   |
| Starogard Gdański        | 1         | 1.45%   |
| Radom                     | 1         | 1.45%   |
| Pruszcz Gdanski           | 1         | 1.45%   |
| Poznan                    | 1         | 1.45%   |
| Pobiedziska               | 1         | 1.45%   |
| Pacierzow                 | 1         | 1.45%   |
| Ostrołęka               | 1         | 1.45%   |
| Opole                     | 1         | 1.45%   |
| Miedziana Gora            | 1         | 1.45%   |
| Lublin                    | 1         | 1.45%   |
| Lipie                     | 1         | 1.45%   |
| Ledziny                   | 1         | 1.45%   |
| Krasnik                   | 1         | 1.45%   |
| Klobuck                   | 1         | 1.45%   |
| Kielce                    | 1         | 1.45%   |
| Katowice                  | 1         | 1.45%   |
| Jaslo                     | 1         | 1.45%   |
| JarosÅ‚aw              | 1         | 1.45%   |
| Grajewo                   | 1         | 1.45%   |
| Gora Kalwaria             | 1         | 1.45%   |
| Gdynia                    | 1         | 1.45%   |
| CzД™stochowa           | 1         | 1.45%   |
| CheÅ‚mno               | 1         | 1.45%   |
| Bolszewo                  | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 23     | 20.51%  |
| WDC                 | 7         | 8      | 8.97%   |
| Seagate             | 7         | 8      | 8.97%   |
| GOODRAM             | 5         | 5      | 6.41%   |
| Crucial             | 5         | 10     | 6.41%   |
| Transcend           | 4         | 4      | 5.13%   |
| A-DATA Technology   | 4         | 4      | 5.13%   |
| Toshiba             | 3         | 4      | 3.85%   |
| SK hynix            | 3         | 3      | 3.85%   |
| SanDisk             | 3         | 3      | 3.85%   |
| Kingston            | 3         | 3      | 3.85%   |
| Plextor             | 2         | 2      | 2.56%   |
| NVMe                | 2         | 4      | 2.56%   |
| Hitachi             | 2         | 2      | 2.56%   |
| HGST                | 2         | 3      | 2.56%   |
| PNY                 | 1         | 1      | 1.28%   |
| Patriot             | 1         | 1      | 1.28%   |
| Micron Technology   | 1         | 2      | 1.28%   |
| LITEONIT            | 1         | 1      | 1.28%   |
| LITEON              | 1         | 1      | 1.28%   |
| KIOXIA              | 1         | 1      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |
| BIWIN               | 1         | 1      | 1.28%   |
| Apacer              | 1         | 2      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung HM321HI 320GB             | 5         | 6.17%   |
| Seagate ST1000LM035-1RK172 1TB    | 2         | 2.47%   |
| Crucial CT500MX500SSD1 500GB      | 2         | 2.47%   |
| WDC WD7500BPKT-22PK4T0 752GB      | 1         | 1.23%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 1.23%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1.23%   |
| WDC WD3200BEKT-22PVMT0 320GB      | 1         | 1.23%   |
| WDC WD1200BEVS-07RST0 120GB       | 1         | 1.23%   |
| WDC WD1200BEVS-07LAT0 120GB       | 1         | 1.23%   |
| WDC PC SN530 NVMe 512GB           | 1         | 1.23%   |
| Transcend TS32GMSA370 32GB        | 1         | 1.23%   |
| Transcend TS256GMTE652T2 256GB    | 1         | 1.23%   |
| Transcend TS128GMSA370 128GB      | 1         | 1.23%   |
| Transcend TS120GMTS420S 120GB     | 1         | 1.23%   |
| Toshiba MK6461GSYN 640GB          | 1         | 1.23%   |
| Toshiba KXG6AZNV1T02 1TB          | 1         | 1.23%   |
| Toshiba KBG40ZNS256G NVMe 256GB   | 1         | 1.23%   |
| SK hynix SC210 mSATA 256GB        | 1         | 1.23%   |
| SK hynix HFS128G39TNF-N3A0A 128GB | 1         | 1.23%   |
| SK hynix HFM512GDHTNG-8310A 512GB | 1         | 1.23%   |
| Seagate ST9500420AS 500GB         | 1         | 1.23%   |
| Seagate ST9500325AS 500GB         | 1         | 1.23%   |
| Seagate ST9320320AS 320GB         | 1         | 1.23%   |
| Seagate ST9160412AS 160GB         | 1         | 1.23%   |
| Seagate ST500LM000-1EJ162 500GB   | 1         | 1.23%   |
| SanDisk SDSSDP128G 128GB          | 1         | 1.23%   |
| SanDisk SDSSDA120G 120GB          | 1         | 1.23%   |
| SanDisk SD9TN8W256G1001 256GB     | 1         | 1.23%   |
| Samsung SSD PM871b M.2 2280 128GB | 1         | 1.23%   |
| Samsung SSD PM830 mSATA 128GB     | 1         | 1.23%   |
| Samsung SSD 980 PRO 1TB           | 1         | 1.23%   |
| Samsung SSD 970 PRO 1TB           | 1         | 1.23%   |
| Samsung SSD 970 EVO 250GB         | 1         | 1.23%   |
| Samsung SSD 860 QVO 4TB           | 1         | 1.23%   |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 1.23%   |
| Samsung SSD 860 EVO 500GB         | 1         | 1.23%   |
| Samsung SSD 850 EVO 250GB         | 1         | 1.23%   |
| Samsung SSD 840 Series 120GB      | 1         | 1.23%   |
| Samsung MZVLB256HAHQ-000L7 256GB  | 1         | 1.23%   |
| Samsung MZMPC128HBFU-000H1 128GB  | 1         | 1.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 29.17%  |
| WDC                 | 6         | 7      | 25%     |
| Samsung Electronics | 5         | 5      | 20.83%  |
| Hitachi             | 2         | 2      | 8.33%   |
| HGST                | 2         | 3      | 8.33%   |
| Toshiba             | 1         | 2      | 4.17%   |
| NVMe                | 1         | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 14     | 17.5%   |
| GOODRAM             | 5         | 5      | 12.5%   |
| Crucial             | 4         | 9      | 10%     |
| Transcend           | 3         | 3      | 7.5%    |
| SanDisk             | 3         | 3      | 7.5%    |
| Kingston            | 3         | 3      | 7.5%    |
| A-DATA Technology   | 3         | 3      | 7.5%    |
| SK hynix            | 2         | 2      | 5%      |
| Plextor             | 2         | 2      | 5%      |
| Patriot             | 1         | 1      | 2.5%    |
| NVMe                | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 2      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| Apacer              | 1         | 2      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 54     | 50.68%  |
| HDD  | 23        | 28     | 31.51%  |
| NVMe | 13        | 16     | 17.81%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 82     | 80%     |
| NVMe | 13        | 16     | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 64     | 78.95%  |
| 0.51-1.0   | 9         | 14     | 15.79%  |
| 1.01-2.0   | 2         | 2      | 3.51%   |
| 3.01-4.0   | 1         | 2      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 19        | 27.54%  |
| 1-20       | 17        | 24.64%  |
| 251-500    | 14        | 20.29%  |
| 51-100     | 10        | 14.49%  |
| 501-1000   | 5         | 7.25%   |
| 21-50      | 4         | 5.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 59        | 86.76%  |
| 51-100  | 4         | 5.88%   |
| 21-50   | 3         | 4.41%   |
| 101-250 | 2         | 2.94%   |

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
| Works    | 56        | 82     | 82.35%  |
| Malfunc  | 10        | 12     | 14.71%  |
| Detected | 2         | 4      | 2.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 57        | 75%     |
| Samsung Electronics       | 4         | 5.26%   |
| AMD                       | 3         | 3.95%   |
| SanDisk                   | 2         | 2.63%   |
| KIOXIA                    | 2         | 2.63%   |
| VIA Technologies          | 1         | 1.32%   |
| Transcend                 | 1         | 1.32%   |
| Toshiba                   | 1         | 1.32%   |
| SK hynix                  | 1         | 1.32%   |
| Silicon Motion            | 1         | 1.32%   |
| Phison Electronics        | 1         | 1.32%   |
| Micron/Crucial Technology | 1         | 1.32%   |
| Biwin Storage Technology  | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 15%     |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 11.25%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 8.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 5%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.75%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 2.5%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2.5%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 2         | 2.5%    |
| Unknown                                                                        | 2         | 2.5%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.25%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 1.25%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.25%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 1.25%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.25%   |
| SanDisk unknown                                                                | 1         | 1.25%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.25%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.25%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.25%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 1         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 1         | 1.25%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 54        | 71.05%  |
| NVMe | 14        | 18.42%  |
| RAID | 4         | 5.26%   |
| IDE  | 4         | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 92.54%  |
| AMD    | 5         | 7.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 6         | 8.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 4.48%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 2         | 2.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 2         | 2.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 2         | 2.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 2.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 2.99%   |
| Intel Core 2 Duo                         | 2         | 2.99%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 1.49%   |
| Intel Pentium M processor                | 1         | 1.49%   |
| Intel Core i7-9750HF CPU @ 2.60GHz       | 1         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 1.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 1         | 1.49%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 1.49%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 1.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i7-3610QM CPU @ 2.30GHz       | 1         | 1.49%   |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 1.49%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 1.49%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 1.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 1         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.49%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 1.49%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i5-3360M CPU @ 2.80GHz        | 1         | 1.49%   |
| Intel Core i5-3317U CPU @ 1.70GHz        | 1         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 1         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.49%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.49%   |
| Intel Core i5-10200H CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i5 CPU M 560 @ 2.67GH         | 1         | 1.49%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 1         | 1.49%   |
| Intel Core i3-3227U CPU @ 1.90GHz        | 1         | 1.49%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 1         | 1.49%   |
| Intel Core i3-2370M CPU @ 2.40GHz        | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 27        | 40.3%   |
| Intel Core i7        | 12        | 17.91%  |
| Intel Core 2 Duo     | 10        | 14.93%  |
| Intel Core i3        | 5         | 7.46%   |
| Other                | 3         | 4.48%   |
| Intel Celeron        | 3         | 4.48%   |
| Intel Pentium Silver | 1         | 1.49%   |
| Intel Pentium M      | 1         | 1.49%   |
| Intel Celeron M      | 1         | 1.49%   |
| AMD Ryzen Embedded   | 1         | 1.49%   |
| AMD Ryzen 7 PRO      | 1         | 1.49%   |
| AMD E                | 1         | 1.49%   |
| AMD Athlon           | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 36        | 53.73%  |
| 4       | 18        | 26.87%  |
| Unknown | 7         | 10.45%  |
| 8       | 2         | 2.99%   |
| 6       | 2         | 2.99%   |
| 1       | 2         | 2.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 62        | 92.54%  |
| Unknown | 5         | 7.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 45        | 67.16%  |
| 1       | 13        | 19.4%   |
| Unknown | 9         | 13.43%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 12        | 17.91%  |
| KabyLake      | 10        | 14.93%  |
| Penryn        | 8         | 11.94%  |
| Haswell       | 7         | 10.45%  |
| Skylake       | 5         | 7.46%   |
| SandyBridge   | 5         | 7.46%   |
| Broadwell     | 4         | 5.97%   |
| Zen+          | 2         | 2.99%   |
| Westmere      | 2         | 2.99%   |
| TigerLake     | 2         | 2.99%   |
| P6            | 2         | 2.99%   |
| Core          | 2         | 2.99%   |
| Zen           | 1         | 1.49%   |
| Silvermont    | 1         | 1.49%   |
| Goldmont plus | 1         | 1.49%   |
| Excavator     | 1         | 1.49%   |
| CometLake     | 1         | 1.49%   |
| Bobcat        | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 57        | 67.86%  |
| Nvidia           | 18        | 21.43%  |
| AMD              | 8         | 9.52%   |
| VIA Technologies | 1         | 1.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 12.94%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 8         | 9.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 5.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 4.71%   |
| Intel HD Graphics 5500                                                        | 4         | 4.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 4.71%   |
| Intel HD Graphics 620                                                         | 3         | 3.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 3         | 3.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 2         | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 2.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 2.35%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 1         | 1.18%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 1.18%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 1.18%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 1.18%   |
| Nvidia GM107M [GeForce GTX 860M]                                              | 1         | 1.18%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.18%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 1.18%   |
| Nvidia GK104GLM [Quadro K3000M]                                               | 1         | 1.18%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 635M]                                               | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 525M]                                               | 1         | 1.18%   |
| Nvidia GF108M [GeForce GT 420M]                                               | 1         | 1.18%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.18%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 1.18%   |
| Nvidia G96CM [GeForce 9650M GT]                                               | 1         | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 1.18%   |
| Intel UHD Graphics 620                                                        | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.18%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 1.18%   |
| Intel HD Graphics 630                                                         | 1         | 1.18%   |
| Intel HD Graphics 510                                                         | 1         | 1.18%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.18%   |
| Intel Comet Lake-H GT1 [UHD Graphics 610]                                     | 1         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 29        | 43.28%  |
| Intel + Nvidia | 14        | 20.9%   |
| 2 x Intel      | 10        | 14.93%  |
| 1 x Nvidia     | 4         | 5.97%   |
| Intel + AMD    | 4         | 5.97%   |
| 1 x AMD        | 4         | 5.97%   |
| Other          | 1         | 1.49%   |
| 1 x VIA        | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 58        | 85.29%  |
| Proprietary | 6         | 8.82%   |
| Unknown     | 4         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 89.71%  |
| 0.51-1.0   | 3         | 4.41%   |
| 5.01-6.0   | 1         | 1.47%   |
| 3.01-4.0   | 1         | 1.47%   |
| 1.01-2.0   | 1         | 1.47%   |
| 0.01-0.5   | 1         | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 15        | 29.41%  |
| Lenovo                  | 7         | 13.73%  |
| BOE                     | 7         | 13.73%  |
| Chimei Innolux          | 4         | 7.84%   |
| AU Optronics            | 4         | 7.84%   |
| Samsung Electronics     | 3         | 5.88%   |
| Chi Mei Optoelectronics | 2         | 3.92%   |
| Philips                 | 1         | 1.96%   |
| PANDA                   | 1         | 1.96%   |
| KTC                     | 1         | 1.96%   |
| JDI                     | 1         | 1.96%   |
| InfoVision              | 1         | 1.96%   |
| Iiyama                  | 1         | 1.96%   |
| BenQ                    | 1         | 1.96%   |
| AOC                     | 1         | 1.96%   |
| Acer                    | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 9.8%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 3.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.92%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.96%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.96%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 1.96%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 1.96%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD0368 1366x768 310x170mm 13.9-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.96%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 1.96%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 1.96%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.96%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.96%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.96%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 1.96%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.96%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch          | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch         | 1         | 1.96%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.96%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE07BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06FB 1920x1080 340x190mm 15.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06C6 1920x1080 340x190mm 15.3-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06BB 1920x1080 310x170mm 13.9-inch                    | 1         | 1.96%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                     | 1         | 1.96%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                    | 1         | 1.96%   |
| BenQ RL2455 BNQ7F1C 1920x1080 530x300mm 24.0-inch                        | 1         | 1.96%   |
| AU Optronics LCD Monitor AUOA114 1280x800 260x160mm 12.0-inch            | 1         | 1.96%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 20        | 40%     |
| 1366x768 (WXGA)  | 16        | 32%     |
| 1280x800 (WXGA)  | 7         | 14%     |
| 1600x900 (HD+)   | 3         | 6%      |
| 2560x1440 (QHD)  | 1         | 2%      |
| 1440x900 (WXGA+) | 1         | 2%      |
| 1280x1024 (SXGA) | 1         | 2%      |
| Unknown          | 1         | 2%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 19        | 38%     |
| 13      | 12        | 24%     |
| 12      | 11        | 22%     |
| 27      | 2         | 4%      |
| 17      | 2         | 4%      |
| 24      | 1         | 2%      |
| 23      | 1         | 2%      |
| 14      | 1         | 2%      |
| Unknown | 1         | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 63.27%  |
| 201-300     | 12        | 24.49%  |
| 501-600     | 4         | 8.16%   |
| 351-400     | 1         | 2.04%   |
| Unknown     | 1         | 2.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 37        | 78.72%  |
| 16/10   | 7         | 14.89%  |
| 5/4     | 1         | 2.13%   |
| 3/2     | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 14        | 28%     |
| 81-90          | 13        | 26%     |
| 61-70          | 11        | 22%     |
| 101-110        | 5         | 10%     |
| 301-350        | 2         | 4%      |
| 201-250        | 2         | 4%      |
| 141-150        | 1         | 2%      |
| 121-130        | 1         | 2%      |
| Unknown        | 1         | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 27        | 55.1%   |
| 101-120 | 11        | 22.45%  |
| 51-100  | 8         | 16.33%  |
| 161-240 | 2         | 4.08%   |
| Unknown | 1         | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 52        | 75.36%  |
| 0     | 11        | 15.94%  |
| 2     | 6         | 8.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 46.36%  |
| Realtek Semiconductor             | 23        | 20.91%  |
| Qualcomm Atheros                  | 14        | 12.73%  |
| Broadcom                          | 8         | 7.27%   |
| Dell                              | 3         | 2.73%   |
| Qualcomm Atheros Communications   | 2         | 1.82%   |
| VIA Technologies                  | 1         | 0.91%   |
| Van Ooijen Technische Informatica | 1         | 0.91%   |
| TP-Link                           | 1         | 0.91%   |
| Sierra Wireless                   | 1         | 0.91%   |
| Ralink Technology                 | 1         | 0.91%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.91%   |
| Ericsson Business Mobile Networks | 1         | 0.91%   |
| Atheros                           | 1         | 0.91%   |
| AMD                               | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 19        | 13.67%  |
| Intel 82567LM Gigabit Network Connection                                      | 8         | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 5.04%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 2.88%   |
| Intel Wireless 8260                                                           | 4         | 2.88%   |
| Intel Wireless 7265                                                           | 4         | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.16%   |
| Intel Wireless 7260                                                           | 3         | 2.16%   |
| Intel Wireless 3165                                                           | 3         | 2.16%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 2.16%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 2.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 1.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 1.44%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 1.44%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.44%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 1.44%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 1.44%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 0.72%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)              | 1         | 0.72%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 0.72%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.72%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.72%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                                 | 1         | 0.72%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 63.89%  |
| Qualcomm Atheros                | 12        | 16.67%  |
| Broadcom                        | 5         | 6.94%   |
| Realtek Semiconductor           | 2         | 2.78%   |
| Qualcomm Atheros Communications | 2         | 2.78%   |
| Dell                            | 2         | 2.78%   |
| TP-Link                         | 1         | 1.39%   |
| Ralink Technology               | 1         | 1.39%   |
| Atheros                         | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Ultimate N WiFi Link 5300                                               | 5         | 6.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 5.56%   |
| Intel Wireless 8260                                                           | 4         | 5.56%   |
| Intel Wireless 7265                                                           | 4         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 5.56%   |
| Intel Wireless 7260                                                           | 3         | 4.17%   |
| Intel Wireless 3165                                                           | 3         | 4.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2         | 2.78%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 2.78%   |
| Intel Centrino Advanced-N 6235                                                | 2         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 1         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 1         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.39%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.39%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.39%   |
| Intel Wireless-AC 9260                                                        | 1         | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 1.39%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.39%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.39%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 1.39%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.39%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 1.39%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.39%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                            | 1         | 1.39%   |
| Dell Dell Wireless 5560 Single-mode HSPA Mini Card with A-GPS                 | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 32        | 51.61%  |
| Realtek Semiconductor         | 22        | 35.48%  |
| Broadcom                      | 3         | 4.84%   |
| Qualcomm Atheros              | 2         | 3.23%   |
| VIA Technologies              | 1         | 1.61%   |
| OnePlus Technology (Shenzhen) | 1         | 1.61%   |
| AMD                           | 1         | 1.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 30.65%  |
| Intel 82567LM Gigabit Network Connection                          | 8         | 12.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 11.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.84%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.84%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.23%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.61%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                     | 1         | 1.61%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.61%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.61%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.61%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.61%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.61%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.61%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 50.38%  |
| Ethernet | 60        | 45.8%   |
| Modem    | 3         | 2.29%   |
| Unknown  | 2         | 1.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 56.52%  |
| Ethernet | 40        | 43.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 57        | 85.07%  |
| 1     | 6         | 8.96%   |
| 3     | 2         | 2.99%   |
| 5     | 1         | 1.49%   |
| 0     | 1         | 1.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 58.7%   |
| Broadcom                        | 7         | 15.22%  |
| IMC Networks                    | 3         | 6.52%   |
| Foxconn / Hon Hai               | 3         | 6.52%   |
| Qualcomm Atheros Communications | 2         | 4.35%   |
| Realtek Semiconductor           | 1         | 2.17%   |
| Hewlett-Packard                 | 1         | 2.17%   |
| Dell                            | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 28.26%  |
| Intel AX201 Bluetooth                                    | 5         | 10.87%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 4         | 8.7%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 3         | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 6.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 2         | 4.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1         | 2.17%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 1         | 2.17%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device     | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS         | 1         | 2.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 2.17%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]   | 1         | 2.17%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter               | 1         | 2.17%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 2.17%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth            | 1         | 2.17%   |
| Foxconn / Hon Hai Bluetooth USB Module                   | 1         | 2.17%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module              | 1         | 2.17%   |
| Broadcom BCM43142A0 Bluetooth Module                     | 1         | 2.17%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 1         | 2.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 1         | 2.17%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 82.43%  |
| Nvidia                | 5         | 6.76%   |
| AMD                   | 5         | 6.76%   |
| VIA Technologies      | 1         | 1.35%   |
| Realtek Semiconductor | 1         | 1.35%   |
| Kingston Technology   | 1         | 1.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 14.44%  |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 10%     |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 10%     |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 4.44%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.44%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 4.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 2.22%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.11%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                           | 1         | 1.11%   |
| Nvidia unknown                                                             | 1         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.11%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.11%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.11%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.11%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.11%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.11%   |
| Unknown                                                                    | 1         | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 26.47%  |
| SK hynix            | 17        | 25%     |
| Kingston            | 7         | 10.29%  |
| Micron Technology   | 6         | 8.82%   |
| Unknown             | 5         | 7.35%   |
| GOODRAM             | 5         | 7.35%   |
| Ramaxel Technology  | 4         | 5.88%   |
| Corsair             | 2         | 2.94%   |
| Transcend           | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| G.Skill             | 1         | 1.47%   |
| Elpida              | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.74%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 2.74%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 2.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 2.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 2         | 2.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 2.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 2.74%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 2         | 2.74%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 2         | 2.74%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 2.74%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 1.37%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 1.37%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                | 1         | 1.37%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 1         | 1.37%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| SK hynix RAM HMT425S6MFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 1.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 1.37%   |
| SK hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s    | 1         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 1.37%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1867MT/s       | 1         | 1.37%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s     | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 1         | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s     | 1         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 1.37%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 1.37%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s     | 1         | 1.37%   |
| Samsung RAM M378B2873CZ0-CF7 1024MB SODIMM DDR3 800MT/s   | 1         | 1.37%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB DIMM LPDDR4 2133MT/s      | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 30        | 53.57%  |
| DDR4   | 19        | 33.93%  |
| LPDDR4 | 2         | 3.57%   |
| SDRAM  | 1         | 1.79%   |
| LPDDR3 | 1         | 1.79%   |
| DRAM   | 1         | 1.79%   |
| DDR2   | 1         | 1.79%   |
| DDR    | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 94.64%  |
| Row Of Chips | 1         | 1.79%   |
| DIMM         | 1         | 1.79%   |
| Unknown      | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 35.48%  |
| 4096  | 17        | 27.42%  |
| 2048  | 14        | 22.58%  |
| 16384 | 4         | 6.45%   |
| 1024  | 4         | 6.45%   |
| 512   | 1         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 26.15%  |
| 2400    | 8         | 12.31%  |
| 2667    | 6         | 9.23%   |
| 1333    | 6         | 9.23%   |
| 2133    | 5         | 7.69%   |
| 1334    | 5         | 7.69%   |
| 3200    | 4         | 6.15%   |
| 1067    | 3         | 4.62%   |
| 800     | 3         | 4.62%   |
| 1867    | 2         | 3.08%   |
| Unknown | 2         | 3.08%   |
| 4267    | 1         | 1.54%   |
| 2048    | 1         | 1.54%   |
| 1066    | 1         | 1.54%   |
| 533     | 1         | 1.54%   |

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
| Chicony Electronics                    | 20        | 44.44%  |
| Microdia                               | 8         | 17.78%  |
| Realtek Semiconductor                  | 5         | 11.11%  |
| Bison Electronics                      | 4         | 8.89%   |
| Ricoh                                  | 2         | 4.44%   |
| Lite-On Technology                     | 2         | 4.44%   |
| Syntek                                 | 1         | 2.22%   |
| Sunplus Innovation Technology          | 1         | 2.22%   |
| Logitech                               | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 4         | 8.89%   |
| Realtek Lenovo EasyCamera                                      | 3         | 6.67%   |
| Microdia Integrated Webcam                                     | 3         | 6.67%   |
| Chicony Realtek DMFT RGB                                       | 3         | 6.67%   |
| Microdia Integrated_Webcam_HD                                  | 2         | 4.44%   |
| Lite-On Integrated Camera                                      | 2         | 4.44%   |
| Chicony Integrated Camera [ThinkPad]                           | 2         | 4.44%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 4.44%   |
| Syntek Lenovo EasyCamera                                       | 1         | 2.22%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 2.22%   |
| Ricoh Integrated Webcam                                        | 1         | 2.22%   |
| Ricoh HD Webcam                                                | 1         | 2.22%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.22%   |
| Realtek HD WebCam                                              | 1         | 2.22%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 1         | 2.22%   |
| Microdia Integrated HD Webcam                                  | 1         | 2.22%   |
| Microdia Dell Integrated HD Webcam                             | 1         | 2.22%   |
| Logitech HD Pro Webcam C920                                    | 1         | 2.22%   |
| Chicony ThinkPad T490 Webcam                                   | 1         | 2.22%   |
| Chicony HP Integrated Webcam                                   | 1         | 2.22%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 2.22%   |
| Chicony HP HD Webcam                                           | 1         | 2.22%   |
| Chicony HD WebCam                                              | 1         | 2.22%   |
| Chicony Front Camera                                           | 1         | 2.22%   |
| Chicony FJ Camera                                              | 1         | 2.22%   |
| Chicony 1.3M Webcam                                            | 1         | 2.22%   |
| Chicony 1.3 MPixel UVC Webcam                                  | 1         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) USB 2.0 UVC 1.3M WebCam | 1         | 2.22%   |
| Bison USB HD Webcam                                            | 1         | 2.22%   |
| Bison Lenovo EasyCamera                                        | 1         | 2.22%   |
| Bison Integrated Camera                                        | 1         | 2.22%   |
| Bison EasyCamera                                               | 1         | 2.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 21.43%  |
| Synaptics                  | 3         | 21.43%  |
| Broadcom                   | 3         | 21.43%  |
| AuthenTec                  | 3         | 21.43%  |
| STMicroelectronics         | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 21.43%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 14.29%  |
| AuthenTec AES2810                                                            | 2         | 14.29%  |
| Validity Sensors Fingerprint scanner                                         | 1         | 7.14%   |
| Synaptics WBDI                                                               | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 7.14%   |
| AuthenTec AES2660                                                            | 1         | 7.14%   |

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
| 2     | 26        | 37.68%  |
| 1     | 21        | 30.43%  |
| 3     | 11        | 15.94%  |
| 0     | 5         | 7.25%   |
| 4     | 3         | 4.35%   |
| 5     | 2         | 2.9%    |
| 6     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 56        | 45.9%   |
| Bluetooth                | 17        | 13.93%  |
| Fingerprint reader       | 14        | 11.48%  |
| Card reader              | 13        | 10.66%  |
| Net/wireless             | 10        | 8.2%    |
| Graphics card            | 7         | 5.74%   |
| Network                  | 2         | 1.64%   |
| Firewire controller      | 2         | 1.64%   |
| Modem                    | 1         | 0.82%   |

