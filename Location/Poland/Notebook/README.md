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

Total: 62

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OpenBSD 7.0          | 5         | 10%     |
| GhostBSD 20.04.02    | 4         | 8%      |
| FreeBSD 12.2         | 4         | 8%      |
| OpenBSD 7.1          | 3         | 6%      |
| helloSystem 0.5.0    | 3         | 6%      |
| FreeBSD 12.1         | 3         | 6%      |
| OpenBSD 6.8          | 2         | 4%      |
| helloSystem 0.7.0    | 2         | 4%      |
| helloSystem 0.6.0    | 2         | 4%      |
| FreeBSD 14.0-CURRENT | 2         | 4%      |
| FreeBSD 13.0-p5      | 2         | 4%      |
| FreeBSD 13.0-p4      | 2         | 4%      |
| FreeBSD 13.0-p2      | 2         | 4%      |
| OpenBSD 6.9          | 1         | 2%      |
| NomadBSD 5806f915    | 1         | 2%      |
| NomadBSD 1.3.1       | 1         | 2%      |
| helloSystem 0.4.0    | 1         | 2%      |
| GhostBSD 22.01.12    | 1         | 2%      |
| GhostBSD 21.08.27    | 1         | 2%      |
| FreeBSD 13.1-BETA1   | 1         | 2%      |
| FreeBSD 13.0-RC2     | 1         | 2%      |
| FreeBSD 13.0-p7      | 1         | 2%      |
| FreeBSD 13.0-BETA2   | 1         | 2%      |
| FreeBSD 13.0         | 1         | 2%      |
| FreeBSD 12.2-p2      | 1         | 2%      |
| FreeBSD 12.1-p4      | 1         | 2%      |
| FreeBSD 12.1-p10     | 1         | 2%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 18        | 41.86%  |
| OpenBSD     | 10        | 23.26%  |
| helloSystem | 7         | 16.28%  |
| GhostBSD    | 6         | 13.95%  |
| NomadBSD    | 2         | 4.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 41        | 95.35%  |
| i386  | 2         | 4.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| fvwm         | 10        | 23.26%  |
| MATE         | 8         | 18.6%   |
| helloDesktop | 7         | 16.28%  |
| XFCE         | 6         | 13.95%  |
| Openbox      | 4         | 9.3%    |
| TWM          | 2         | 4.65%   |
| KDE5         | 2         | 4.65%   |
| i3           | 2         | 4.65%   |
| GNOME        | 1         | 2.33%   |
| Console      | 1         | 2.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 42        | 95.45%  |
| Console | 2         | 4.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 17        | 39.53%  |
| SLiM    | 15        | 34.88%  |
| LightDM | 6         | 13.95%  |
| SDDM    | 4         | 9.3%    |
| XDM     | 1         | 2.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 15        | 34.09%  |
| en_US   | 12        | 27.27%  |
| pl_PL   | 8         | 18.18%  |
| C       | 8         | 18.18%  |
| fr_FR   | 1         | 2.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 31        | 70.45%  |
| BIOS | 13        | 29.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 23        | 53.49%  |
| Ffs    | 10        | 23.26%  |
| Ufs    | 9         | 20.93%  |
| Cd9660 | 1         | 2.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 32        | 74.42%  |
| MBR  | 11        | 25.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 18        | 41.86%  |
| Dell             | 13        | 30.23%  |
| Hewlett-Packard  | 2         | 4.65%   |
| Acer             | 2         | 4.65%   |
| Sony             | 1         | 2.33%   |
| PC Specialist    | 1         | 2.33%   |
| Panasonic        | 1         | 2.33%   |
| Notebook         | 1         | 2.33%   |
| IBM              | 1         | 2.33%   |
| Fujitsu Siemens  | 1         | 2.33%   |
| ASUSTek Computer | 1         | 2.33%   |
| Unknown          | 1         | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Lenovo ThinkPad X200 745969G          | 5         | 11.63%  |
| Unknown                               | 2         | 4.65%   |
| Sony SVF1521K1EB                      | 1         | 2.33%   |
| PC Specialist Recoil II               | 1         | 2.33%   |
| Panasonic CFMX4-1                     | 1         | 2.33%   |
| Notebook N85_N87,HJ,HJ1,HK1           | 1         | 2.33%   |
| Lenovo ThinkPad X230 23254S6          | 1         | 2.33%   |
| Lenovo ThinkPad X200s 7470A98         | 1         | 2.33%   |
| Lenovo ThinkPad W520 4284W5L          | 1         | 2.33%   |
| Lenovo ThinkPad T480 20L6S4GR02       | 1         | 2.33%   |
| Lenovo ThinkPad T470 W10DG 20JNS0JU01 | 1         | 2.33%   |
| Lenovo ThinkPad T440 20B7S1860W       | 1         | 2.33%   |
| Lenovo ThinkPad T14s Gen 1 20T1S0Q200 | 1         | 2.33%   |
| Lenovo Legion Y540-15IRH-PG0 81SY     | 1         | 2.33%   |
| Lenovo IdeaPad S130-14IGM 81J2        | 1         | 2.33%   |
| Lenovo IdeaPad 520-15IKB 81BF         | 1         | 2.33%   |
| Lenovo G580 20150                     | 1         | 2.33%   |
| Lenovo G500s 20245                    | 1         | 2.33%   |
| IBM ThinkPad X41 2525FAG              | 1         | 2.33%   |
| HP ENVY dv7                           | 1         | 2.33%   |
| HP 635                                | 1         | 2.33%   |
| Fujitsu Siemens AMILO PRO V3515       | 1         | 2.33%   |
| Dell Vostro 3560                      | 1         | 2.33%   |
| Dell Vostro 3550                      | 1         | 2.33%   |
| Dell Latitude XT2                     | 1         | 2.33%   |
| Dell Latitude E7240                   | 1         | 2.33%   |
| Dell Latitude E6440                   | 1         | 2.33%   |
| Dell Latitude E6430                   | 1         | 2.33%   |
| Dell Latitude E6410                   | 1         | 2.33%   |
| Dell Latitude E5470                   | 1         | 2.33%   |
| Dell Latitude E5430 vPro              | 1         | 2.33%   |
| Dell Latitude 5400                    | 1         | 2.33%   |
| Dell Inspiron N5110                   | 1         | 2.33%   |
| Dell Inspiron 5502                    | 1         | 2.33%   |
| Dell G15 5510                         | 1         | 2.33%   |
| ASUS X555LB                           | 1         | 2.33%   |
| Acer Aspire V3-571G                   | 1         | 2.33%   |
| Acer Aspire 5742G                     | 1         | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 12        | 27.91%  |
| Dell Latitude         | 8         | 18.6%   |
| Lenovo IdeaPad        | 2         | 4.65%   |
| Dell Vostro           | 2         | 4.65%   |
| Dell Inspiron         | 2         | 4.65%   |
| Acer Aspire           | 2         | 4.65%   |
| Unknown               | 2         | 4.65%   |
| Sony SVF1521K1EB      | 1         | 2.33%   |
| PC Specialist Recoil  | 1         | 2.33%   |
| Panasonic CFMX4-1     | 1         | 2.33%   |
| Notebook N85          | 1         | 2.33%   |
| Lenovo Legion         | 1         | 2.33%   |
| Lenovo G580           | 1         | 2.33%   |
| Lenovo G500s          | 1         | 2.33%   |
| IBM ThinkPad          | 1         | 2.33%   |
| HP ENVY               | 1         | 2.33%   |
| HP 635                | 1         | 2.33%   |
| Fujitsu Siemens AMILO | 1         | 2.33%   |
| Dell G15              | 1         | 2.33%   |
| ASUS X555LB           | 1         | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 13.95%  |
| 2012 | 6         | 13.95%  |
| 2013 | 5         | 11.63%  |
| 2009 | 5         | 11.63%  |
| 2018 | 3         | 6.98%   |
| 2017 | 3         | 6.98%   |
| 2014 | 3         | 6.98%   |
| 2011 | 3         | 6.98%   |
| 2021 | 2         | 4.65%   |
| 2016 | 2         | 4.65%   |
| 2006 | 2         | 4.65%   |
| 2022 | 1         | 2.33%   |
| 2015 | 1         | 2.33%   |
| 2010 | 1         | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 43        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 42        | 97.67%  |
| Yes  | 1         | 2.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 16        | 37.21%  |
| 16.01-24.0 | 12        | 27.91%  |
| 8.01-16.0  | 9         | 20.93%  |
| 32.01-64.0 | 2         | 4.65%   |
| 3.01-4.0   | 2         | 4.65%   |
| 2.01-3.0   | 2         | 4.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 28        | 63.64%  |
| 0.51-1.0  | 14        | 31.82%  |
| 1.01-2.0  | 1         | 2.27%   |
| 8.01-16.0 | 1         | 2.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 55.56%  |
| 2      | 15        | 33.33%  |
| 3      | 3         | 6.67%   |
| 0      | 2         | 4.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 75%     |
| Yes       | 11        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 95.35%  |
| No        | 2         | 4.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 59.09%  |
| No        | 18        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 43        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Warsaw                    | 8         | 18.18%  |
| Gdansk                    | 6         | 13.64%  |
| Krakow                    | 4         | 9.09%   |
| Wroclaw                   | 3         | 6.82%   |
| Chrusty                   | 3         | 6.82%   |
| ЕљwiД™tochЕ‚owice | 1         | 2.27%   |
| Zgierz                    | 1         | 2.27%   |
| Wloszczowa                | 1         | 2.27%   |
| Wieliczka                 | 1         | 2.27%   |
| Świnoujście             | 1         | 2.27%   |
| Starogard Gdański        | 1         | 2.27%   |
| Pruszcz Gdanski           | 1         | 2.27%   |
| Pobiedziska               | 1         | 2.27%   |
| Pacierzow                 | 1         | 2.27%   |
| Miedziana Gora            | 1         | 2.27%   |
| Lodz                      | 1         | 2.27%   |
| Lipie                     | 1         | 2.27%   |
| Ledziny                   | 1         | 2.27%   |
| Krasnik                   | 1         | 2.27%   |
| Klobuck                   | 1         | 2.27%   |
| Kielce                    | 1         | 2.27%   |
| JarosÅ‚aw              | 1         | 2.27%   |
| Grajewo                   | 1         | 2.27%   |
| CzД™stochowa           | 1         | 2.27%   |
| CheÅ‚mno               | 1         | 2.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 20     | 25.49%  |
| WDC                 | 6         | 7      | 11.76%  |
| Crucial             | 4         | 8      | 7.84%   |
| A-DATA Technology   | 4         | 4      | 7.84%   |
| Transcend           | 3         | 3      | 5.88%   |
| Seagate             | 3         | 4      | 5.88%   |
| SK Hynix            | 2         | 2      | 3.92%   |
| NVMe                | 2         | 4      | 3.92%   |
| Kingston            | 2         | 2      | 3.92%   |
| Hitachi             | 2         | 2      | 3.92%   |
| HGST                | 2         | 3      | 3.92%   |
| GOODRAM             | 2         | 2      | 3.92%   |
| Toshiba             | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| PLEXTOR             | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 2      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| Gigabyte Technology | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung HM321HI 320GB             | 5         | 9.26%   |
| WDC WD7500BPKT-22PK4T0 752GB      | 1         | 1.85%   |
| WDC WD5000LPCX-24VHAT0 500GB      | 1         | 1.85%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1.85%   |
| WDC WD1200BEVS-07RST0 120GB       | 1         | 1.85%   |
| WDC WD1200BEVS-07LAT0 120GB       | 1         | 1.85%   |
| WDC PC SN530 NVMe 512GB           | 1         | 1.85%   |
| Transcend TS32GMSA370 32GB        | 1         | 1.85%   |
| Transcend TS128GMSA370 128GB      | 1         | 1.85%   |
| Transcend TS120GMTS420S 120GB     | 1         | 1.85%   |
| Toshiba KBG40ZNS256G NVMe 256GB   | 1         | 1.85%   |
| SK Hynix HFS128G39TNF-N3A0A 128GB | 1         | 1.85%   |
| SK Hynix HFM512GDHTNG-8310A 512GB | 1         | 1.85%   |
| Seagate ST9500420AS 500GB         | 1         | 1.85%   |
| Seagate ST9500325AS 500GB         | 1         | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1.85%   |
| Samsung SSD PM871b M.2 2280 128GB | 1         | 1.85%   |
| Samsung SSD PM830 mSATA 128GB     | 1         | 1.85%   |
| Samsung SSD 980 PRO 1TB           | 1         | 1.85%   |
| Samsung SSD 970 EVO 250GB         | 1         | 1.85%   |
| Samsung SSD 860 QVO 4TB           | 1         | 1.85%   |
| Samsung SSD 860 EVO M.2 2TB       | 1         | 1.85%   |
| Samsung SSD 860 EVO 500GB         | 1         | 1.85%   |
| Samsung SSD 850 EVO 250GB         | 1         | 1.85%   |
| Samsung SSD 840 Series 120GB      | 1         | 1.85%   |
| PNY CS3030 1TB SSD                | 1         | 1.85%   |
| PLEXTOR PH6-CE240 240GB           | 1         | 1.85%   |
| NVMe WDC PC SN520 SDA 512GB       | 1         | 1.85%   |
| NVMe PC SN530 WD 512GB            | 1         | 1.85%   |
| NVMe INTEL SSDPEKKF25 256GB       | 1         | 1.85%   |
| Micron MTFDDAT128MAM-1J2 128GB    | 1         | 1.85%   |
| LITEONIT LMT-128M6M mSATA 128GB   | 1         | 1.85%   |
| Kingston SUV500MS480G 480GB       | 1         | 1.85%   |
| Kingston SA400S37240G 240GB       | 1         | 1.85%   |
| Hitachi HTS545032B9A300 320GB     | 1         | 1.85%   |
| Hitachi HTS543232A7A384 320GB     | 1         | 1.85%   |
| HGST HTS721010A9E630 1TB          | 1         | 1.85%   |
| HGST HTS545050A7E680 500GB        | 1         | 1.85%   |
| GOODRAM SSDPR-CX400-256-G2 256GB  | 1         | 1.85%   |
| GOODRAM SSDPR-CL100-120-G2 120GB  | 1         | 1.85%   |
| Gigabyte GP-GSTFS31256GTND 256GB  | 1         | 1.85%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 1.85%   |
| Crucial CT500MX500SSD1 500GB      | 1         | 1.85%   |
| Crucial CT250BX100SSD1 250GB      | 1         | 1.85%   |
| Crucial CT240BX500SSD1 240GB      | 1         | 1.85%   |
| Crucial CT1000P2SSD8 1TB          | 1         | 1.85%   |
| A-DATA SX8200NP 480GB             | 1         | 1.85%   |
| A-DATA SU800 256GB                | 1         | 1.85%   |
| A-DATA SU800 128GB                | 1         | 1.85%   |
| A-DATA SP550 120GB                | 1         | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 27.78%  |
| Samsung Electronics | 5         | 5      | 27.78%  |
| Seagate             | 3         | 4      | 16.67%  |
| Hitachi             | 2         | 2      | 11.11%  |
| HGST                | 2         | 3      | 11.11%  |
| NVMe                | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 13     | 24%     |
| Transcend           | 3         | 3      | 12%     |
| Crucial             | 3         | 7      | 12%     |
| A-DATA Technology   | 3         | 3      | 12%     |
| Kingston            | 2         | 2      | 8%      |
| GOODRAM             | 2         | 2      | 8%      |
| SK Hynix            | 1         | 1      | 4%      |
| PLEXTOR             | 1         | 1      | 4%      |
| NVMe                | 1         | 1      | 4%      |
| Micron Technology   | 1         | 2      | 4%      |
| LITEONIT            | 1         | 1      | 4%      |
| Gigabyte Technology | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 22        | 37     | 47.83%  |
| HDD  | 17        | 21     | 36.96%  |
| NVMe | 7         | 10     | 15.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 58     | 83.33%  |
| NVMe | 7         | 10     | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 31        | 46     | 81.58%  |
| 0.51-1.0   | 5         | 9      | 13.16%  |
| 3.01-4.0   | 1         | 2      | 2.63%   |
| 1.01-2.0   | 1         | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 24.44%  |
| 101-250    | 11        | 24.44%  |
| 1-20       | 10        | 22.22%  |
| 51-100     | 9         | 20%     |
| 21-50      | 2         | 4.44%   |
| 501-1000   | 2         | 4.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 37        | 84.09%  |
| 51-100  | 3         | 6.82%   |
| 21-50   | 2         | 4.55%   |
| 101-250 | 2         | 4.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1      | 25%     |
| Seagate ST9500420AS 500GB                 | 1         | 2      | 25%     |
| Micron Technology MTFDDAT128MAM-1J2 128GB | 1         | 1      | 25%     |
| Hitachi HTS543232A7A384 320GB             | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 25%     |
| Seagate           | 1         | 2      | 25%     |
| Micron Technology | 1         | 1      | 25%     |
| Hitachi           | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Works    | 37        | 59     | 86.05%  |
| Malfunc  | 4         | 5      | 9.3%    |
| Detected | 2         | 4      | 4.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 39        | 78%     |
| Sandisk                   | 2         | 4%      |
| Samsung Electronics       | 2         | 4%      |
| VIA Technologies          | 1         | 2%      |
| SK Hynix                  | 1         | 2%      |
| Silicon Motion            | 1         | 2%      |
| Phison Electronics        | 1         | 2%      |
| Micron/Crucial Technology | 1         | 2%      |
| KIOXIA                    | 1         | 2%      |
| AMD                       | 1         | 2%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 15.09%  |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 13.21%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 7.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 5.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 3.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 3.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 3.77%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.89%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 1.89%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1         | 1.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 1.89%   |
| Sandisk unknown                                                                | 1         | 1.89%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1         | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.89%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.89%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 1.89%   |
| KIOXIA unknown                                                                 | 1         | 1.89%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.89%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1         | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 1.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 36        | 73.47%  |
| NVMe | 8         | 16.33%  |
| IDE  | 3         | 6.12%   |
| RAID | 2         | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 97.67%  |
| AMD    | 1         | 2.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 11.63%  |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 4.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 4.65%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 2.33%   |
| Intel Pentium M processor                | 1         | 2.33%   |
| Intel Core i7-9750HF CPU @ 2.60GHz       | 1         | 2.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 2.33%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 2.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 2.33%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 1         | 2.33%   |
| Intel Core i7-3610QM CPU @ 2.30GHz       | 1         | 2.33%   |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 2.33%   |
| Intel Core i7-10610U CPU @ 1.80GHz       | 1         | 2.33%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 2.33%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 1         | 2.33%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 1         | 2.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 1         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 2.33%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 2.33%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 1         | 2.33%   |
| Intel Core i5-3360M CPU @ 2.80GHz        | 1         | 2.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 2.33%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 1         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 2.33%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 2.33%   |
| Intel Core i5-10200H CPU @ 2.40GHz       | 1         | 2.33%   |
| Intel Core i5 CPU M 560 @ 2.67GH         | 1         | 2.33%   |
| Intel Core i3-3227U CPU @ 1.90GHz        | 1         | 2.33%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 1         | 2.33%   |
| Intel Core i3-2370M CPU @ 2.40GHz        | 1         | 2.33%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 1         | 2.33%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz     | 1         | 2.33%   |
| Intel Core 2 Duo                         | 1         | 2.33%   |
| Intel Celeron M CPU                      | 1         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 1         | 2.33%   |
| AMD E-300 APU with Radeon HD Graphics    | 1         | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 19        | 44.19%  |
| Intel Core i7        | 8         | 18.6%   |
| Intel Core 2 Duo     | 7         | 16.28%  |
| Intel Core i3        | 4         | 9.3%    |
| Other                | 1         | 2.33%   |
| Intel Pentium Silver | 1         | 2.33%   |
| Intel Pentium M      | 1         | 2.33%   |
| Intel Celeron M      | 1         | 2.33%   |
| AMD E                | 1         | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 22        | 51.16%  |
| 4       | 11        | 25.58%  |
| Unknown | 6         | 13.95%  |
| 6       | 2         | 4.65%   |
| 1       | 2         | 4.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 38        | 88.37%  |
| Unknown | 5         | 11.63%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 31        | 72.09%  |
| Unknown | 8         | 18.6%   |
| 1       | 4         | 9.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 8         | 18.6%   |
| Penryn        | 7         | 16.28%  |
| KabyLake      | 7         | 16.28%  |
| SandyBridge   | 5         | 11.63%  |
| Haswell       | 4         | 9.3%    |
| Westmere      | 2         | 4.65%   |
| Skylake       | 2         | 4.65%   |
| P6            | 2         | 4.65%   |
| Broadwell     | 2         | 4.65%   |
| TigerLake     | 1         | 2.33%   |
| Goldmont plus | 1         | 2.33%   |
| CometLake     | 1         | 2.33%   |
| Bobcat        | 1         | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 39        | 69.64%  |
| Nvidia           | 13        | 23.21%  |
| AMD              | 3         | 5.36%   |
| VIA Technologies | 1         | 1.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 8         | 14.29%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 7         | 12.5%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 5         | 8.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 3.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 3.57%   |
| Intel HD Graphics 5500                                                                | 2         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 2         | 3.57%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                     | 1         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 1.79%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                               | 1         | 1.79%   |
| Nvidia GM108M [GeForce 940M]                                                          | 1         | 1.79%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 1.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 635M]                                                       | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 525M]                                                       | 1         | 1.79%   |
| Nvidia GF108M [GeForce GT 420M]                                                       | 1         | 1.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 1.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1.79%   |
| Intel UHD Graphics 620                                                                | 1         | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1.79%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                             | 1         | 1.79%   |
| Intel HD Graphics 630                                                                 | 1         | 1.79%   |
| Intel HD Graphics 620                                                                 | 1         | 1.79%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 1         | 1.79%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1.79%   |
| Intel Comet Lake UHD Graphics                                                         | 1         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 1         | 1.79%   |
| AMD Wrestler [Radeon HD 6310]                                                         | 1         | 1.79%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 1         | 1.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 41.86%  |
| Intel + Nvidia | 11        | 25.58%  |
| 2 x Intel      | 8         | 18.6%   |
| 1 x Nvidia     | 2         | 4.65%   |
| Intel + AMD    | 2         | 4.65%   |
| 1 x VIA        | 1         | 2.33%   |
| 1 x AMD        | 1         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 37        | 84.09%  |
| Proprietary | 4         | 9.09%   |
| Unknown     | 3         | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 90.91%  |
| 5.01-6.0   | 1         | 2.27%   |
| 3.01-4.0   | 1         | 2.27%   |
| 1.01-2.0   | 1         | 2.27%   |
| 0.51-1.0   | 1         | 2.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 30.23%  |
| Lenovo                  | 7         | 16.28%  |
| BOE                     | 5         | 11.63%  |
| Chimei Innolux          | 3         | 6.98%   |
| AU Optronics            | 3         | 6.98%   |
| Samsung Electronics     | 2         | 4.65%   |
| Chi Mei Optoelectronics | 2         | 4.65%   |
| Philips                 | 1         | 2.33%   |
| PANDA                   | 1         | 2.33%   |
| KTC                     | 1         | 2.33%   |
| JDI                     | 1         | 2.33%   |
| InfoVision              | 1         | 2.33%   |
| Iiyama                  | 1         | 2.33%   |
| BenQ                    | 1         | 2.33%   |
| AOC                     | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 5         | 11.63%  |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch              | 2         | 4.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 4.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 2.33%   |
| Philips PHL 275S1 PHL094B 2560x1440 600x340mm 27.2-inch                  | 1         | 2.33%   |
| PANDA LCD Monitor NCP006E 1920x1080 340x190mm 15.3-inch                  | 1         | 2.33%   |
| LG Display LCD Monitor LGD0533 1920x1080 340x190mm 15.3-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD033E 1366x768 310x170mm 13.9-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 2.33%   |
| LG Display LCD Monitor LGD0283 1920x1080 380x220mm 17.3-inch             | 1         | 2.33%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch              | 1         | 2.33%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 2.33%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 2.33%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 2.33%   |
| JDI LAM125M007D JDI1402 1920x1080 280x160mm 12.7-inch                    | 1         | 2.33%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 2.33%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15A9 1366x768 340x190mm 15.3-inch          | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 2.33%   |
| BOE LCD Monitor BOE092A 1920x1080 340x190mm 15.3-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE06FB 1920x1080 340x190mm 15.3-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE06C6 1920x1080 340x190mm 15.3-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE06BB 1920x1080 310x170mm 13.9-inch                    | 1         | 2.33%   |
| BOE LCD Monitor BOE0653 1920x1080 310x170mm 13.9-inch                    | 1         | 2.33%   |
| BenQ RL2455 BNQ7F1C 1920x1080 530x300mm 24.0-inch                        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUOA114 1280x800 260x160mm 12.0-inch            | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO463D 1920x1080 310x170mm 13.9-inch           | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 1         | 2.33%   |
| AOC Q27P1B AOC2701 1920x1080 600x340mm 27.2-inch                         | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 16        | 38.1%   |
| 1366x768 (WXGA)  | 13        | 30.95%  |
| 1280x800 (WXGA)  | 7         | 16.67%  |
| 1600x900 (HD+)   | 3         | 7.14%   |
| 2560x1440 (QHD)  | 1         | 2.38%   |
| 1440x900 (WXGA+) | 1         | 2.38%   |
| 1280x1024 (SXGA) | 1         | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 17        | 39.53%  |
| 12     | 10        | 23.26%  |
| 13     | 9         | 20.93%  |
| 27     | 2         | 4.65%   |
| 17     | 2         | 4.65%   |
| 24     | 1         | 2.33%   |
| 23     | 1         | 2.33%   |
| 14     | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 61.9%   |
| 201-300     | 11        | 26.19%  |
| 501-600     | 4         | 9.52%   |
| 351-400     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 77.5%   |
| 16/10 | 8         | 20%     |
| 5/4   | 1         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 12        | 27.91%  |
| 81-90          | 10        | 23.26%  |
| 61-70          | 10        | 23.26%  |
| 101-110        | 5         | 11.63%  |
| 301-350        | 2         | 4.65%   |
| 201-250        | 2         | 4.65%   |
| 141-150        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 24        | 57.14%  |
| 101-120 | 8         | 19.05%  |
| 51-100  | 8         | 19.05%  |
| 161-240 | 2         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 36        | 80%     |
| 0     | 5         | 11.11%  |
| 2     | 4         | 8.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 45.21%  |
| Realtek Semiconductor             | 14        | 19.18%  |
| Qualcomm Atheros                  | 12        | 16.44%  |
| Broadcom                          | 5         | 6.85%   |
| Qualcomm Atheros Communications   | 2         | 2.74%   |
| Dell                              | 2         | 2.74%   |
| VIA Technologies                  | 1         | 1.37%   |
| Van Ooijen Technische Informatica | 1         | 1.37%   |
| Sierra Wireless                   | 1         | 1.37%   |
| Ralink Technology                 | 1         | 1.37%   |
| Atheros                           | 1         | 1.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 12        | 13.04%  |
| Intel 82567LM Gigabit Network Connection                                      | 7         | 7.61%   |
| Intel Ultimate N WiFi Link 5300                                               | 5         | 5.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 3.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 2.17%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 2.17%   |
| Intel Wireless 8260                                                           | 2         | 2.17%   |
| Intel Wireless 7260                                                           | 2         | 2.17%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 2.17%   |
| Intel Ethernet Connection I218-LM                                             | 2         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 2.17%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 1         | 1.09%   |
| Van Ooijen Technische Informatica CDC-ACM class devices (modems)              | 1         | 1.09%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 1.09%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 1.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 1.09%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 1.09%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 1.09%   |
| Intel Wireless 7265                                                           | 1         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.09%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 1.09%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                         | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.09%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 1.09%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 1.09%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 1.09%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 1.09%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.09%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 1.09%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 1.09%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller              | 1         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                      | 1         | 1.09%   |
| Dell Dell Wireless 5560 Single-mode HSPA Mini Card with A-GPS                 | 1         | 1.09%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 1.09%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 1.09%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 1.09%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]          | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 62.5%   |
| Qualcomm Atheros                | 10        | 20.83%  |
| Qualcomm Atheros Communications | 2         | 4.17%   |
| Dell                            | 2         | 4.17%   |
| Broadcom                        | 2         | 4.17%   |
| Ralink Technology               | 1         | 2.08%   |
| Atheros                         | 1         | 2.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Ultimate N WiFi Link 5300                                               | 5         | 10.42%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 6.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 4.17%   |
| Intel Wireless 8265 / 8275                                                    | 2         | 4.17%   |
| Intel Wireless 8260                                                           | 2         | 4.17%   |
| Intel Wireless 7260                                                           | 2         | 4.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 4.17%   |
| Ralink RT5370 Wireless Adapter                                                | 1         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 1         | 2.08%   |
| Qualcomm Atheros TP-Link TL-WN821N v2 / TL-WN822N v1 802.11n [Atheros AR9170] | 1         | 2.08%   |
| Qualcomm Atheros AR9271 802.11n                                               | 1         | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 2.08%   |
| Intel Wireless 7265                                                           | 1         | 2.08%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 2.08%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 1         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 1         | 2.08%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 2.08%   |
| Intel Centrino Wireless-N 135                                                 | 1         | 2.08%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 2.08%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 2.08%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 2.08%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 2.08%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1         | 2.08%   |
| Dell Dell Wireless 5560 Single-mode HSPA Mini Card with A-GPS                 | 1         | 2.08%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 1         | 2.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 2.08%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]          | 1         | 2.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 51.22%  |
| Realtek Semiconductor | 14        | 34.15%  |
| Broadcom              | 3         | 7.32%   |
| Qualcomm Atheros      | 2         | 4.88%   |
| VIA Technologies      | 1         | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 29.27%  |
| Intel 82567LM Gigabit Network Connection                          | 7         | 17.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 9.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 4.88%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.88%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 4.88%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.44%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.44%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.44%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.44%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 2.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 43        | 49.43%  |
| Ethernet | 41        | 47.13%  |
| Modem    | 2         | 2.3%    |
| Unknown  | 1         | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 55.07%  |
| Ethernet | 31        | 44.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 41        | 95.35%  |
| 1     | 2         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 43        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 53.85%  |
| IMC Networks                    | 3         | 11.54%  |
| Broadcom                        | 3         | 11.54%  |
| Qualcomm Atheros Communications | 2         | 7.69%   |
| Foxconn / Hon Hai               | 2         | 7.69%   |
| Hewlett-Packard                 | 1         | 3.85%   |
| Dell                            | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 4         | 15.38%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 3         | 11.54%  |
| Intel AX201 Bluetooth                                  | 3         | 11.54%  |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]     | 3         | 11.54%  |
| Intel Centrino Bluetooth Wireless Transceiver          | 2         | 7.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 2         | 7.69%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                | 1         | 3.85%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device   | 1         | 3.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 3.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter      | 1         | 3.85%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 3.85%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter             | 1         | 3.85%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth          | 1         | 3.85%   |
| Foxconn / Hon Hai Bluetooth USB Module                 | 1         | 3.85%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 85.42%  |
| Nvidia                | 4         | 8.33%   |
| VIA Technologies      | 1         | 2.08%   |
| Realtek Semiconductor | 1         | 2.08%   |
| AMD                   | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 16.07%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 12.5%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 7.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 3.57%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 3.57%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.79%   |
| Realtek Semiconductor TX 384kb Hifi Type_C Audio                           | 1         | 1.79%   |
| Nvidia unknown                                                             | 1         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.79%   |
| Intel CM238 HD Audio Controller                                            | 1         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.79%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 1         | 1.79%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.79%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.79%   |
| Unknown                                                                    | 1         | 1.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 26.19%  |
| SK Hynix            | 9         | 21.43%  |
| Kingston            | 6         | 14.29%  |
| Micron Technology   | 4         | 9.52%   |
| GOODRAM             | 4         | 9.52%   |
| Unknown             | 3         | 7.14%   |
| Ramaxel Technology  | 3         | 7.14%   |
| ELPIDA              | 1         | 2.38%   |
| Corsair             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 2         | 4.44%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 2         | 4.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 4.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 2         | 4.44%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 2.22%   |
| Unknown RAM Module 4096MB SODIMM DDR3                     | 1         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR                         | 1         | 2.22%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s                | 1         | 2.22%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 2.22%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 2.22%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 2.22%   |
| SK Hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1066MT/s    | 1         | 2.22%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 2.22%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 2.22%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 2.22%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s     | 1         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 1         | 2.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 2.22%   |
| Samsung RAM M378B2873CZ0-CF7 1024MB SODIMM DDR3 800MT/s   | 1         | 2.22%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB DIMM LPDDR4 2133MT/s      | 1         | 2.22%   |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s   | 1         | 2.22%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s   | 1         | 2.22%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 2.22%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s      | 1         | 2.22%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s    | 1         | 2.22%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s   | 1         | 2.22%   |
| Kingston RAM ACR256X64D3S1066C7 2GB SODIMM DDR3 1067MT/s  | 1         | 2.22%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s   | 1         | 2.22%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s   | 1         | 2.22%   |
| Kingston RAM 9905630-033.A00G 16GB SODIMM DDR4 2133MT/s   | 1         | 2.22%   |
| Kingston RAM 9905630-025.A00G 8GB SODIMM DDR4 2400MT/s    | 1         | 2.22%   |
| GOODRAM RAM GR2666S464L19S/8G 8192MB SODIMM DDR4 2667MT/s | 1         | 2.22%   |
| GOODRAM RAM GR2133S464L15/16G 16GB SODIMM DDR4 2133MT/s   | 1         | 2.22%   |
| GOODRAM RAM GR1600S364L11/8G 8GB SODIMM DDR3 1600MT/s     | 1         | 2.22%   |
| GOODRAM RAM GR1333S364L9S/4G 4GB SODIMM DDR3 1333MT/s     | 1         | 2.22%   |
| ELPIDA RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1333MT/s     | 1         | 2.22%   |
| Corsair RAM CMSX8GX3M1A1600C 8192MB SODIMM DDR3 800MT/s   | 1         | 2.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 21        | 61.76%  |
| DDR4   | 10        | 29.41%  |
| LPDDR4 | 1         | 2.94%   |
| DRAM   | 1         | 2.94%   |
| DDR    | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 33        | 97.06%  |
| DIMM   | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 12        | 31.58%  |
| 8192  | 10        | 26.32%  |
| 2048  | 7         | 18.42%  |
| 16384 | 4         | 10.53%  |
| 1024  | 4         | 10.53%  |
| 512   | 1         | 2.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 9         | 22.5%   |
| 1334    | 5         | 12.5%   |
| 1333    | 5         | 12.5%   |
| 2667    | 4         | 10%     |
| 3200    | 3         | 7.5%    |
| 2400    | 3         | 7.5%    |
| 2133    | 3         | 7.5%    |
| 1067    | 2         | 5%      |
| 800     | 2         | 5%      |
| Unknown | 2         | 5%      |
| 1066    | 1         | 2.5%    |
| 533     | 1         | 2.5%    |

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
| Chicony Electronics                    | 11        | 36.67%  |
| Microdia                               | 7         | 23.33%  |
| Acer                                   | 3         | 10%     |
| Ricoh                                  | 2         | 6.67%   |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Sunplus Innovation Technology          | 1         | 3.33%   |
| Logitech                               | 1         | 3.33%   |
| Lite-On Technology                     | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Microdia Integrated Webcam                                    | 3         | 10%     |
| Realtek Lenovo EasyCamera                                     | 2         | 6.67%   |
| Microdia Integrated_Webcam_HD                                 | 2         | 6.67%   |
| Chicony Integrated Camera (1280x720@30)                       | 2         | 6.67%   |
| Chicony Integrated Camera                                     | 2         | 6.67%   |
| Syntek Lenovo EasyCamera                                      | 1         | 3.33%   |
| Sunplus Integrated_Webcam_HD                                  | 1         | 3.33%   |
| Ricoh Integrated Webcam                                       | 1         | 3.33%   |
| Ricoh HD Webcam                                               | 1         | 3.33%   |
| Microdia Laptop_Integrated_Webcam_HD                          | 1         | 3.33%   |
| Microdia Dell Integrated HD Webcam                            | 1         | 3.33%   |
| Logitech HD Pro Webcam C920                                   | 1         | 3.33%   |
| Lite-On Integrated Camera                                     | 1         | 3.33%   |
| Chicony Integrated Camera [ThinkPad]                          | 1         | 3.33%   |
| Chicony HP Integrated Webcam                                  | 1         | 3.33%   |
| Chicony HP HD Webcam [Fixed]                                  | 1         | 3.33%   |
| Chicony HD Webcam                                             | 1         | 3.33%   |
| Chicony Front Camera                                          | 1         | 3.33%   |
| Chicony Chicony USB2.0 Camera                                 | 1         | 3.33%   |
| Chicony 1.3M Webcam                                           | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M WebCam | 1         | 3.33%   |
| Acer USB HD Webcam                                            | 1         | 3.33%   |
| Acer Lenovo EasyCamera                                        | 1         | 3.33%   |
| Acer EasyCamera                                               | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| Broadcom                   | 2         | 20%     |
| STMicroelectronics         | 1         | 10%     |
| Shenzhen Goodix Technology | 1         | 10%     |
| AuthenTec                  | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Validity Sensors Fingerprint scanner                                         | 1         | 10%     |
| Synaptics  WBDI                                                              | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                                        | 1         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 10%     |
| AuthenTec AES2810                                                            | 1         | 10%     |

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
| 2     | 20        | 44.44%  |
| 1     | 12        | 26.67%  |
| 3     | 7         | 15.56%  |
| 4     | 2         | 4.44%   |
| 0     | 2         | 4.44%   |
| 6     | 1         | 2.22%   |
| 5     | 1         | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 38        | 45.78%  |
| Fingerprint reader       | 10        | 12.05%  |
| Bluetooth                | 10        | 12.05%  |
| Card reader              | 9         | 10.84%  |
| Graphics card            | 7         | 8.43%   |
| Net/wireless             | 6         | 7.23%   |
| Network                  | 1         | 1.2%    |
| Modem                    | 1         | 1.2%    |
| Firewire controller      | 1         | 1.2%    |

