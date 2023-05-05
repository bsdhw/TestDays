BSD in Spain - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Spain.

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

Total: 90

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ReachingTe... | DreamQuest Pro 2022         | [afd28a7425](https://bsd-hardware.info/?probe=afd28a7425) | Apr 30, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | [c4b2619dda](https://bsd-hardware.info/?probe=c4b2619dda) | Apr 20, 2023 |
| Dell          | Precision 5510              | [7028fde527](https://bsd-hardware.info/?probe=7028fde527) | Apr 20, 2023 |
| Chuwi         | Unknown                     | [5e687fcc83](https://bsd-hardware.info/?probe=5e687fcc83) | Apr 01, 2023 |
| Dell          | Inspiron 5547               | [4f4f6e06d7](https://bsd-hardware.info/?probe=4f4f6e06d7) | Mar 29, 2023 |
| Unknown       | Unknown                     | [2a50573c9f](https://bsd-hardware.info/?probe=2a50573c9f) | Mar 29, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Sony          | SVE1511C5E                  | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Acer          | Aspire A315-58              | [81827ccbca](https://bsd-hardware.info/?probe=81827ccbca) | Feb 10, 2023 |
| ASUSTek       | 1201N                       | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| Razer         | Blade Stealth               | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Unknown       | Unknown                     | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Unknown       | Unknown                     | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | G50-80 80E5                 | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| HP            | ProBook 430 G7              | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| Alienware     | m15 R4                      | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | ProBook 4340s               | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| ASUSTek       | X556UJ                      | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Unknown       | Unknown                     | [48d1f61478](https://bsd-hardware.info/?probe=48d1f61478) | Dec 10, 2021 |
| Unknown       | Unknown                     | [46b91a9c0c](https://bsd-hardware.info/?probe=46b91a9c0c) | Dec 10, 2021 |
| ASUSTek       | 1215B                       | [6dbcac684f](https://bsd-hardware.info/?probe=6dbcac684f) | Dec 04, 2021 |
| Alienware     | m15 R4                      | [a724a7d7c7](https://bsd-hardware.info/?probe=a724a7d7c7) | Nov 29, 2021 |
| AZW           | BT3 PRO                     | [3454b5492b](https://bsd-hardware.info/?probe=3454b5492b) | Nov 15, 2021 |
| AZW           | BT3 PRO                     | [5d4b48a3a3](https://bsd-hardware.info/?probe=5d4b48a3a3) | Nov 15, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b8408cb369](https://bsd-hardware.info/?probe=b8408cb369) | Sep 06, 2021 |
| Dell          | Latitude E6530              | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | 250 G4                      | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 250 G4                      | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| ASUSTek       | K55VD                       | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [443817737d](https://bsd-hardware.info/?probe=443817737d) | Jun 24, 2021 |
| HP            | OMEN by Laptop              | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| Dell          | Latitude 7390               | [2ad87768af](https://bsd-hardware.info/?probe=2ad87768af) | Mar 25, 2021 |
| Lenovo        | ThinkPad L590 20Q7000YSP    | [038fbabfe8](https://bsd-hardware.info/?probe=038fbabfe8) | Mar 24, 2021 |
| MSI           | GE75 Raider 10SGS           | [fea3cdb5d1](https://bsd-hardware.info/?probe=fea3cdb5d1) | Mar 24, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| HP            | Laptop 15-db0xxx            | [b1ee3da46f](https://bsd-hardware.info/?probe=b1ee3da46f) | Mar 06, 2021 |
| Dell          | Latitude 7390               | [3fe6eff89a](https://bsd-hardware.info/?probe=3fe6eff89a) | Feb 17, 2021 |
| HP            | OMEN by Laptop              | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| Apple         | MacBook5,2                  | [f1bc2178a9](https://bsd-hardware.info/?probe=f1bc2178a9) | Feb 12, 2021 |
| Lenovo        | Yoga 2 13 20344             | [c51c202b8d](https://bsd-hardware.info/?probe=c51c202b8d) | Dec 25, 2020 |
| Apple         | MacBook6,1                  | [64b1b1910c](https://bsd-hardware.info/?probe=64b1b1910c) | Nov 01, 2020 |
| Acer          | Extensa 2540                | [26670a4ae9](https://bsd-hardware.info/?probe=26670a4ae9) | Oct 30, 2020 |
| Lenovo        | G50-80 80E5                 | [e06605a92b](https://bsd-hardware.info/?probe=e06605a92b) | Oct 19, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 16        | 21.92%  |
| helloSystem 0.8.0    | 6         | 8.22%   |
| helloSystem 0.8.1    | 4         | 5.48%   |
| helloSystem 0.5.0    | 4         | 5.48%   |
| FreeBSD 13.1         | 4         | 5.48%   |
| OpenBSD 7.2          | 3         | 4.11%   |
| helloSystem 0.6.0    | 3         | 4.11%   |
| GhostBSD 20.04.02    | 3         | 4.11%   |
| OpenBSD 7.1          | 2         | 2.74%   |
| OpenBSD 6.8          | 2         | 2.74%   |
| helloSystem 0.4.0    | 2         | 2.74%   |
| FuguIta 7.2          | 2         | 2.74%   |
| OPNsense 23.1.6      | 1         | 1.37%   |
| OPNsense 22.7.10     | 1         | 1.37%   |
| OPNsense 21.7.6      | 1         | 1.37%   |
| OPNsense 21.7.5      | 1         | 1.37%   |
| OpenBSD 6.9          | 1         | 1.37%   |
| NomadBSD 5806f915    | 1         | 1.37%   |
| GhostBSD 23.03.17    | 1         | 1.37%   |
| GhostBSD 23.01.13    | 1         | 1.37%   |
| GhostBSD 22.06.18    | 1         | 1.37%   |
| GhostBSD 21.08.27    | 1         | 1.37%   |
| FreeBSD 14.0-CURRENT | 1         | 1.37%   |
| FreeBSD 13.2         | 1         | 1.37%   |
| FreeBSD 13.1-p7      | 1         | 1.37%   |
| FreeBSD 13.1-p5      | 1         | 1.37%   |
| FreeBSD 13.1-p2      | 1         | 1.37%   |
| FreeBSD 13.1-p1      | 1         | 1.37%   |
| FreeBSD 13.0-STABLE  | 1         | 1.37%   |
| FreeBSD 13.0-RC3     | 1         | 1.37%   |
| FreeBSD 13.0-RC1     | 1         | 1.37%   |
| FreeBSD 13.0-BETA4   | 1         | 1.37%   |
| FreeBSD 13.0         | 1         | 1.37%   |
| FreeBSD 12.3         | 1         | 1.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 29        | 44.62%  |
| FreeBSD     | 16        | 24.62%  |
| OpenBSD     | 7         | 10.77%  |
| GhostBSD    | 7         | 10.77%  |
| OPNsense    | 3         | 4.62%   |
| FuguIta     | 2         | 3.08%   |
| NomadBSD    | 1         | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 61        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 36        | 54.55%  |
| MATE         | 8         | 12.12%  |
| Console      | 8         | 12.12%  |
| fvwm         | 3         | 4.55%   |
| XFCE         | 2         | 3.03%   |
| TWM          | 2         | 3.03%   |
| Openbox      | 2         | 3.03%   |
| KDE5         | 2         | 3.03%   |
| i3           | 2         | 3.03%   |
| GNOME        | 1         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 52        | 83.87%  |
| Console | 8         | 12.9%   |
| Wayland | 2         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 32        | 49.23%  |
| Console | 18        | 27.69%  |
| LightDM | 7         | 10.77%  |
| SDDM    | 3         | 4.62%   |
| GDM     | 3         | 4.62%   |
| XDM     | 1         | 1.54%   |
| Ly      | 1         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 23        | 34.85%  |
| es_ES   | 14        | 21.21%  |
| C       | 12        | 18.18%  |
| Unknown | 11        | 16.67%  |
| es      | 3         | 4.55%   |
| zh_CN   | 1         | 1.52%   |
| ru_RU   | 1         | 1.52%   |
| de_DE   | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 50        | 81.97%  |
| BIOS | 11        | 18.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 36        | 56.25%  |
| Cd9660 | 13        | 20.31%  |
| Ffs    | 9         | 14.06%  |
| Ufs    | 6         | 9.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 52        | 85.25%  |
| MBR  | 9         | 14.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 21.31%  |
| Lenovo              | 11        | 18.03%  |
| Dell                | 7         | 11.48%  |
| ASUSTek Computer    | 7         | 11.48%  |
| Apple               | 4         | 6.56%   |
| Acer                | 3         | 4.92%   |
| SLIMBOOK            | 2         | 3.28%   |
| Unknown             | 2         | 3.28%   |
| TWINHEAD            | 1         | 1.64%   |
| TUXEDO              | 1         | 1.64%   |
| Toshiba             | 1         | 1.64%   |
| Sony                | 1         | 1.64%   |
| Samsung Electronics | 1         | 1.64%   |
| ReachingTech        | 1         | 1.64%   |
| Razer               | 1         | 1.64%   |
| Packard Bell        | 1         | 1.64%   |
| MSI                 | 1         | 1.64%   |
| Chuwi               | 1         | 1.64%   |
| AZW                 | 1         | 1.64%   |
| Alienware           | 1         | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Latitude 7390                   | 3         | 4.92%   |
| Unknown                              | 3         | 4.92%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 2         | 3.28%   |
| ASUS K55VD                           | 2         | 3.28%   |
| TWINHEAD U12CT                       | 1         | 1.64%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.64%   |
| Toshiba Satellite A300               | 1         | 1.64%   |
| Sony SVE1511C5E                      | 1         | 1.64%   |
| SLIMBOOK PROX-AMD5                   | 1         | 1.64%   |
| SLIMBOOK ESSENTIAL-15-11             | 1         | 1.64%   |
| Samsung 530U3C/530U4C/532U3C         | 1         | 1.64%   |
| ReachingTech DreamQuest Pro 2022     | 1         | 1.64%   |
| Razer Blade Stealth                  | 1         | 1.64%   |
| Packard Bell DOT S                   | 1         | 1.64%   |
| MSI GE75 Raider 10SGS                | 1         | 1.64%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.64%   |
| Lenovo ThinkPad X270 20HMS06Q1D      | 1         | 1.64%   |
| Lenovo ThinkPad X200 745969G         | 1         | 1.64%   |
| Lenovo ThinkPad T61 765912G          | 1         | 1.64%   |
| Lenovo ThinkPad T440p 20AW007QMS     | 1         | 1.64%   |
| Lenovo ThinkPad L590 20Q7000YSP      | 1         | 1.64%   |
| Lenovo ThinkPad L450 20DSS1S402      | 1         | 1.64%   |
| Lenovo ThinkPad L440 20ASS0FP00      | 1         | 1.64%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW | 1         | 1.64%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 1         | 1.64%   |
| Lenovo G50-80 80E5                   | 1         | 1.64%   |
| HP ProBook 4540s                     | 1         | 1.64%   |
| HP ProBook 4340s                     | 1         | 1.64%   |
| HP ProBook 430 G7                    | 1         | 1.64%   |
| HP Pavilion dv6                      | 1         | 1.64%   |
| HP Pavilion dv4                      | 1         | 1.64%   |
| HP OMEN by Laptop                    | 1         | 1.64%   |
| HP OMEN by HP Laptop 17-cb1xxx       | 1         | 1.64%   |
| HP Laptop 15-db0xxx                  | 1         | 1.64%   |
| HP EliteBook 2730p                   | 1         | 1.64%   |
| HP Compaq 6735s                      | 1         | 1.64%   |
| HP 250 G4                            | 1         | 1.64%   |
| Dell Studio XPS 1340                 | 1         | 1.64%   |
| Dell Precision 5510                  | 1         | 1.64%   |
| Dell Latitude E6530                  | 1         | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 8         | 13.11%  |
| HP Pavilion              | 4         | 6.56%   |
| Dell Latitude            | 4         | 6.56%   |
| HP ProBook               | 3         | 4.92%   |
| Unknown                  | 3         | 4.92%   |
| HP OMEN                  | 2         | 3.28%   |
| ASUS K55VD               | 2         | 3.28%   |
| Apple MacBook5           | 2         | 3.28%   |
| Acer Aspire              | 2         | 3.28%   |
| TWINHEAD U12CT           | 1         | 1.64%   |
| TUXEDO Aura              | 1         | 1.64%   |
| Toshiba Satellite        | 1         | 1.64%   |
| Sony SVE1511C5E          | 1         | 1.64%   |
| SLIMBOOK PROX-AMD5       | 1         | 1.64%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 1.64%   |
| Samsung 530U3C           | 1         | 1.64%   |
| ReachingTech DreamQuest  | 1         | 1.64%   |
| Razer Blade              | 1         | 1.64%   |
| Packard Bell DOT         | 1         | 1.64%   |
| MSI GE75                 | 1         | 1.64%   |
| Lenovo Yoga              | 1         | 1.64%   |
| Lenovo IdeaPad           | 1         | 1.64%   |
| Lenovo G50-80            | 1         | 1.64%   |
| HP Laptop                | 1         | 1.64%   |
| HP EliteBook             | 1         | 1.64%   |
| HP Compaq                | 1         | 1.64%   |
| HP 250                   | 1         | 1.64%   |
| Dell Studio              | 1         | 1.64%   |
| Dell Precision           | 1         | 1.64%   |
| Dell Inspiron            | 1         | 1.64%   |
| AZW BT3                  | 1         | 1.64%   |
| ASUS X556UJ              | 1         | 1.64%   |
| ASUS U33Jc               | 1         | 1.64%   |
| ASUS TUF                 | 1         | 1.64%   |
| ASUS 1215B               | 1         | 1.64%   |
| ASUS 1201N               | 1         | 1.64%   |
| Apple MacBook6           | 1         | 1.64%   |
| Apple MacBook4           | 1         | 1.64%   |
| Alienware m15            | 1         | 1.64%   |
| Acer Extensa             | 1         | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 11        | 18.03%  |
| 2019 | 6         | 9.84%   |
| 2012 | 6         | 9.84%   |
| 2022 | 5         | 8.2%    |
| 2009 | 5         | 8.2%    |
| 2018 | 4         | 6.56%   |
| 2015 | 4         | 6.56%   |
| 2011 | 4         | 6.56%   |
| 2008 | 4         | 6.56%   |
| 2014 | 3         | 4.92%   |
| 2010 | 3         | 4.92%   |
| 2021 | 2         | 3.28%   |
| 2016 | 2         | 3.28%   |
| 2017 | 1         | 1.64%   |
| 2007 | 1         | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 61        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 25        | 40.32%  |
| 4.01-8.0    | 15        | 24.19%  |
| 16.01-24.0  | 11        | 17.74%  |
| 32.01-64.0  | 5         | 8.06%   |
| 3.01-4.0    | 2         | 3.23%   |
| 2.01-3.0    | 2         | 3.23%   |
| 24.01-32.0  | 1         | 1.61%   |
| 64.01-256.0 | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 34        | 53.97%  |
| 0.51-1.0 | 21        | 33.33%  |
| 1.01-2.0 | 6         | 9.52%   |
| 2.01-3.0 | 2         | 3.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 44        | 72.13%  |
| 2      | 13        | 21.31%  |
| 0      | 2         | 3.28%   |
| 4      | 1         | 1.64%   |
| 3      | 1         | 1.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 72.58%  |
| Yes       | 17        | 27.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 90.16%  |
| No        | 6         | 9.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 96.72%  |
| No        | 2         | 3.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 78.69%  |
| No        | 13        | 21.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 61        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 12        | 17.14%  |
| Barcelona                     | 8         | 11.43%  |
| Valencia                      | 4         | 5.71%   |
| Terrassa                      | 3         | 4.29%   |
| Navalcarnero                  | 3         | 4.29%   |
| Tarragona                     | 2         | 2.86%   |
| Paterna                       | 2         | 2.86%   |
| GibraleГіn                  | 2         | 2.86%   |
| Alcobendas                    | 2         | 2.86%   |
| Vitoria-Gasteiz               | 1         | 1.43%   |
| Villapresente                 | 1         | 1.43%   |
| Urnieta                       | 1         | 1.43%   |
| Tudela de Duero               | 1         | 1.43%   |
| Seville                       | 1         | 1.43%   |
| Sedavi                        | 1         | 1.43%   |
| Santa Cruz de Tenerife        | 1         | 1.43%   |
| Sanlucar la Mayor             | 1         | 1.43%   |
| San Vicent del Raspeig        | 1         | 1.43%   |
| San SebastiÃ¡n de los Reyes | 1         | 1.43%   |
| Redondela                     | 1         | 1.43%   |
| Málaga                       | 1         | 1.43%   |
| LogroГ±o                    | 1         | 1.43%   |
| LogroÃ±o                    | 1         | 1.43%   |
| Laguna de Duero               | 1         | 1.43%   |
| La Pobla de Farnals           | 1         | 1.43%   |
| Ibiza Town                    | 1         | 1.43%   |
| Fuenterrabia                  | 1         | 1.43%   |
| Esparragosa de Lares          | 1         | 1.43%   |
| Elche                         | 1         | 1.43%   |
| Coria del RÃ­o              | 1         | 1.43%   |
| Córdoba                      | 1         | 1.43%   |
| Colombres                     | 1         | 1.43%   |
| Cho                           | 1         | 1.43%   |
| Carcer                        | 1         | 1.43%   |
| Cambre                        | 1         | 1.43%   |
| Beniarjo                      | 1         | 1.43%   |
| Beneixama                     | 1         | 1.43%   |
| Badalona                      | 1         | 1.43%   |
| Ãguilas                    | 1         | 1.43%   |
| Almensilla                    | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 13        | 26     | 17.11%  |
| WDC                                    | 8         | 10     | 10.53%  |
| NVMe                                   | 6         | 7      | 7.89%   |
| Toshiba                                | 5         | 7      | 6.58%   |
| Hitachi                                | 5         | 5      | 6.58%   |
| Crucial                                | 5         | 5      | 6.58%   |
| Seagate                                | 4         | 4      | 5.26%   |
| Kingston                               | 4         | 5      | 5.26%   |
| SanDisk                                | 3         | 3      | 3.95%   |
| Intel                                  | 3         | 3      | 3.95%   |
| HGST                                   | 3         | 3      | 3.95%   |
| Product:              USB Flash Memory | 2         | 2      | 2.63%   |
| Micron Technology                      | 2         | 2      | 2.63%   |
| Fujitsu                                | 2         | 2      | 2.63%   |
| XrayDisk                               | 1         | 1      | 1.32%   |
| Union Memory                           | 1         | 1      | 1.32%   |
| Transcend                              | 1         | 1      | 1.32%   |
| TCSUNBOW                               | 1         | 1      | 1.32%   |
| PNY                                    | 1         | 1      | 1.32%   |
| Netac                                  | 1         | 1      | 1.32%   |
| LITEONIT                               | 1         | 1      | 1.32%   |
| Kston                                  | 1         | 2      | 1.32%   |
| KIOXIA                                 | 1         | 1      | 1.32%   |
| KingSpec                               | 1         | 1      | 1.32%   |
| China                                  | 1         | 1      | 1.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 2.53%   |
| NVMe Samsung SSD 980 1TB                                     | 2         | 2.53%   |
| XrayDisk SSD 240GB                                           | 1         | 1.27%   |
| WDC WDS100T2B0C-00PXH0 1TB                                   | 1         | 1.27%   |
| WDC WD5000LPCX-21VHAT0 500GB                                 | 1         | 1.27%   |
| WDC WD2500BEVT-35A23T0 250GB                                 | 1         | 1.27%   |
| WDC WD1200BEVS-22UST0 120GB                                  | 1         | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB                                     | 1         | 1.27%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 1         | 1.27%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                           | 1         | 1.27%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB                           | 1         | 1.27%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                         | 1         | 1.27%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB              | 1         | 1.27%   |
| Transcend TS120GMTS420S 120GB                                | 1         | 1.27%   |
| Toshiba MQ01ABD100 1TB                                       | 1         | 1.27%   |
| Toshiba MK5065GSXF 500GB                                     | 1         | 1.27%   |
| Toshiba MK1229GSG 120GB                                      | 1         | 1.27%   |
| Toshiba MK1059GSM 1TB                                        | 1         | 1.27%   |
| Toshiba KXG60ZNV512G NVMe 512GB                              | 1         | 1.27%   |
| TCSUNBOW X3 480GB                                            | 1         | 1.27%   |
| Seagate ST9500325AS 500GB                                    | 1         | 1.27%   |
| Seagate ST500LM021-1KJ152 500GB                              | 1         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                               | 1         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 1         | 1.27%   |
| SanDisk SSD PLUS 240GB                                       | 1         | 1.27%   |
| SanDisk SSD i100 24GB                                        | 1         | 1.27%   |
| SanDisk SDSSDP128G 128GB                                     | 1         | 1.27%   |
| Samsung SSD 970 EVO Plus 2TB                                 | 1         | 1.27%   |
| Samsung SSD 970 EVO 250GB                                    | 1         | 1.27%   |
| Samsung SSD 870 QVO 8TB                                      | 1         | 1.27%   |
| Samsung SSD 870 EVO 1TB                                      | 1         | 1.27%   |
| Samsung SSD 860 PRO 512GB                                    | 1         | 1.27%   |
| Samsung SSD 860 EVO 500GB                                    | 1         | 1.27%   |
| Samsung SSD 850 EVO 500GB                                    | 1         | 1.27%   |
| Samsung SSD 850 EVO 250GB                                    | 1         | 1.27%   |
| Samsung SSD 840 PRO Series 128GB                             | 1         | 1.27%   |
| Samsung SSD 750 EVO 250GB                                    | 1         | 1.27%   |
| Samsung PM9A1 NVMe 512GB                                     | 1         | 1.27%   |
| Samsung MZVLW512HMJP-00000 512GB                             | 1         | 1.27%   |
| Samsung MZ7TE128HMGR-000L1 128GB                             | 1         | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 5         | 6      | 16.67%  |
| Hitachi                                | 5         | 5      | 16.67%  |
| Toshiba                                | 4         | 5      | 13.33%  |
| Seagate                                | 4         | 4      | 13.33%  |
| NVMe                                   | 3         | 3      | 10%     |
| HGST                                   | 3         | 3      | 10%     |
| Samsung Electronics                    | 2         | 2      | 6.67%   |
| Product:              USB Flash Memory | 2         | 2      | 6.67%   |
| Fujitsu                                | 2         | 2      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 13     | 25%     |
| Kingston            | 4         | 5      | 12.5%   |
| SanDisk             | 3         | 3      | 9.38%   |
| Crucial             | 3         | 3      | 9.38%   |
| NVMe                | 2         | 2      | 6.25%   |
| Intel               | 2         | 2      | 6.25%   |
| XrayDisk            | 1         | 1      | 3.13%   |
| Transcend           | 1         | 1      | 3.13%   |
| TCSUNBOW            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Netac               | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| Kston               | 1         | 2      | 3.13%   |
| KingSpec            | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 31        | 39     | 41.33%  |
| HDD  | 29        | 32     | 38.67%  |
| NVMe | 15        | 25     | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 71     | 76.92%  |
| NVMe | 15        | 25     | 23.08%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 53     | 75%     |
| 0.51-1.0   | 12        | 16     | 21.43%  |
| 1.01-2.0   | 1         | 1      | 1.79%   |
| 4.01-10.0  | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 24        | 36.92%  |
| 101-250    | 20        | 30.77%  |
| 251-500    | 13        | 20%     |
| 501-1000   | 4         | 6.15%   |
| 51-100     | 2         | 3.08%   |
| 21-50      | 1         | 1.54%   |
| 1001-2000  | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 56        | 88.89%  |
| 21-50    | 3         | 4.76%   |
| 51-100   | 2         | 3.17%   |
| 251-500  | 1         | 1.59%   |
| 501-1000 | 1         | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-35A23T0 250GB                    | 1         | 1      | 7.69%   |
| Toshiba MK1229GSG 120GB                         | 1         | 1      | 7.69%   |
| Toshiba MK1059GSM 1TB                           | 1         | 1      | 7.69%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 7.69%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 1      | 7.69%   |
| Hitachi HTS543232L9SA00 320GB                   | 1         | 1      | 7.69%   |
| Hitachi HTS542525K9A300 250GB                   | 1         | 1      | 7.69%   |
| Hitachi HTS542516K9SA00 160GB                   | 1         | 1      | 7.69%   |
| HGST HTS545050A7E380 500GB                      | 1         | 1      | 7.69%   |
| Fujitsu MHZ2250BH G2 250GB                      | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 30.77%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Seagate             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| Micron Technology   | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 33.33%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |
| Fujitsu             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 92.31%  |
| SSD  | 1         | 1      | 7.69%   |

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
| Works    | 47        | 74     | 71.21%  |
| Malfunc  | 13        | 13     | 19.7%   |
| Detected | 6         | 9      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 40        | 58.82%  |
| Samsung Electronics       | 6         | 8.82%   |
| AMD                       | 6         | 8.82%   |
| Nvidia                    | 5         | 7.35%   |
| SanDisk                   | 4         | 5.88%   |
| Micron/Crucial Technology | 2         | 2.94%   |
| Union Memory (Shenzhen)   | 1         | 1.47%   |
| Toshiba                   | 1         | 1.47%   |
| SK hynix                  | 1         | 1.47%   |
| Micron Technology         | 1         | 1.47%   |
| KIOXIA                    | 1         | 1.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 7.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 6.58%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 5.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4         | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 4         | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.63%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.63%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.63%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 2.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 2.63%   |
| Union Memory (Shenzhen) NVMe 256G SSD device                                     | 1         | 1.32%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 1.32%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 1.32%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.32%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 1.32%   |
| Sandisk WD Black SN770 NVMe SSD                                                  | 1         | 1.32%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.32%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 1.32%   |
| Micron NVMe Storage Controller                                                   | 1         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.32%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.32%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 1.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 47        | 63.51%  |
| NVMe | 18        | 24.32%  |
| IDE  | 6         | 8.11%   |
| RAID | 3         | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 85.25%  |
| AMD    | 9         | 14.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz     | 2         | 3.28%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 3.28%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 2         | 3.28%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 2         | 3.28%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.64%   |
| Intel Pentium CPU B970 @ 2.30GHz       | 1         | 1.64%   |
| Intel CPU Version                      | 1         | 1.64%   |
| Intel Core i9-10980HK CPU @ 2.40GHz    | 1         | 1.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 1.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 1         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 1         | 1.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.64%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz     | 1         | 1.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz      | 1         | 1.64%   |
| Intel Core i7-3610QM CPU @ 2.30GHz     | 1         | 1.64%   |
| Intel Core i7-10875H CPU @ 2.30GHz     | 1         | 1.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1         | 1.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 1.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.64%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 1         | 1.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.64%   |
| Intel Core i5-2537M CPU @ 1.40GHz      | 1         | 1.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz      | 1         | 1.64%   |
| Intel Core i5 CPU U 560 @ 1.33GHz      | 1         | 1.64%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.64%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1         | 1.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 1         | 1.64%   |
| Intel Core i3 CPU M 370 @ 2.40GH       | 1         | 1.64%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU P9500 @ 2.53GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz   | 1         | 1.64%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz   | 1         | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 14        | 22.95%  |
| Intel Core i7      | 13        | 21.31%  |
| Intel Core 2 Duo   | 9         | 14.75%  |
| Intel Core i3      | 4         | 6.56%   |
| AMD Ryzen 7        | 4         | 6.56%   |
| Other              | 3         | 4.92%   |
| Intel Celeron      | 3         | 4.92%   |
| Intel Atom         | 3         | 4.92%   |
| AMD Ryzen 5        | 2         | 3.28%   |
| Intel Pentium Dual | 1         | 1.64%   |
| Intel Pentium      | 1         | 1.64%   |
| Intel Core i9      | 1         | 1.64%   |
| AMD Sempron        | 1         | 1.64%   |
| AMD E              | 1         | 1.64%   |
| AMD A4             | 1         | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 42.62%  |
| 4       | 16        | 26.23%  |
| Unknown | 9         | 14.75%  |
| 8       | 4         | 6.56%   |
| 16      | 2         | 3.28%   |
| 12      | 2         | 3.28%   |
| 6       | 1         | 1.64%   |
| 1       | 1         | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 56        | 91.8%   |
| 2       | 4         | 6.56%   |
| Unknown | 1         | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 34        | 55.74%  |
| 1       | 18        | 29.51%  |
| Unknown | 9         | 14.75%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 9         | 14.75%  |
| Penryn          | 8         | 13.11%  |
| IvyBridge       | 5         | 8.2%    |
| Haswell         | 5         | 8.2%    |
| Skylake         | 4         | 6.56%   |
| Zen 2           | 3         | 4.92%   |
| SandyBridge     | 3         | 4.92%   |
| Core            | 3         | 4.92%   |
| CometLake       | 3         | 4.92%   |
| Westmere        | 2         | 3.28%   |
| TigerLake       | 2         | 3.28%   |
| Silvermont      | 2         | 3.28%   |
| Broadwell       | 2         | 3.28%   |
| Bonnell         | 2         | 3.28%   |
| Unknown         | 2         | 3.28%   |
| Zen+            | 1         | 1.64%   |
| Zen 3           | 1         | 1.64%   |
| K8 & K10 hybrid | 1         | 1.64%   |
| Goldmont plus   | 1         | 1.64%   |
| Excavator       | 1         | 1.64%   |
| Bobcat          | 1         | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 57.33%  |
| Nvidia | 18        | 24%     |
| AMD    | 14        | 18.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.41%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.85%   |
| Intel HD Graphics 620                                                                    | 3         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.85%   |
| AMD Renoir                                                                               | 3         | 3.85%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 2.56%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.56%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.56%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.56%   |
| Intel HD Graphics 530                                                                    | 2         | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.28%   |
| Nvidia TU117M                                                                            | 1         | 1.28%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.28%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.28%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.28%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.28%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.28%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.28%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.28%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.28%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.28%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 1.28%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.28%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.28%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.28%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 45.16%  |
| Intel + Nvidia | 8         | 12.9%   |
| 1 x AMD        | 8         | 12.9%   |
| 1 x Nvidia     | 6         | 9.68%   |
| 2 x Intel      | 5         | 8.06%   |
| Intel + AMD    | 3         | 4.84%   |
| AMD + Nvidia   | 3         | 4.84%   |
| 2 x Nvidia     | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 56        | 88.89%  |
| Proprietary | 5         | 7.94%   |
| Unknown     | 2         | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 85.94%  |
| 0.01-0.5   | 7         | 10.94%  |
| 7.01-8.0   | 1         | 1.56%   |
| 2.01-3.0   | 1         | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 18.18%  |
| LG Display              | 5         | 11.36%  |
| Chimei Innolux          | 5         | 11.36%  |
| Chi Mei Optoelectronics | 4         | 9.09%   |
| BOE                     | 4         | 9.09%   |
| Samsung Electronics     | 3         | 6.82%   |
| Lenovo                  | 3         | 6.82%   |
| Apple                   | 3         | 6.82%   |
| Sharp                   | 1         | 2.27%   |
| PANDA                   | 1         | 2.27%   |
| Mi                      | 1         | 2.27%   |
| LGD                     | 1         | 2.27%   |
| LG Philips              | 1         | 2.27%   |
| Hewlett-Packard         | 1         | 2.27%   |
| Fujitsu Siemens         | 1         | 2.27%   |
| BenQ                    | 1         | 2.27%   |
| AOC                     | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch           | 3         | 6.67%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch                  | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 2.22%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                  | 1         | 2.22%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                         | 1         | 2.22%   |
| LGD LCD Monitor 5760x1080                                                | 1         | 2.22%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 2.22%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 2.22%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 2.22%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 2.22%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch               | 1         | 2.22%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 340x190mm 15.3-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 340x190mm 15.3-inch | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 300x190mm 14.0-inch | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 220x120mm 9.9-inch  | 1         | 2.22%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 2.22%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 2.22%   |
| BenQ LCD Monitor GL2450H                                                 | 1         | 2.22%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 1         | 2.22%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO312C 1366x768 290x160mm 13.0-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 1         | 2.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 340x190mm 15.3-inch            | 1         | 2.22%   |
| Apple LCD Monitor APP9C89 1280x800 290x180mm 13.4-inch                   | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 15        | 34.88%  |
| 1366x768 (WXGA)  | 13        | 30.23%  |
| 1280x800 (WXGA)  | 8         | 18.6%   |
| 1600x900 (HD+)   | 2         | 4.65%   |
| 5760x1080        | 1         | 2.33%   |
| 3840x2160 (4K)   | 1         | 2.33%   |
| 1280x1024 (SXGA) | 1         | 2.33%   |
| 1024x600         | 1         | 2.33%   |
| Unknown          | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 20        | 45.45%  |
| 13      | 12        | 27.27%  |
| 12      | 3         | 6.82%   |
| 24      | 2         | 4.55%   |
| 19      | 2         | 4.55%   |
| 14      | 2         | 4.55%   |
| 27      | 1         | 2.27%   |
| 9       | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 52.27%  |
| 201-300     | 15        | 34.09%  |
| 501-600     | 3         | 6.82%   |
| 401-500     | 1         | 2.27%   |
| 351-400     | 1         | 2.27%   |
| Unknown     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 31        | 75.61%  |
| 16/10   | 7         | 17.07%  |
| 5/4     | 1         | 2.44%   |
| 3/2     | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 18        | 40.91%  |
| 81-90          | 8         | 18.18%  |
| 71-80          | 6         | 13.64%  |
| 61-70          | 3         | 6.82%   |
| 201-250        | 2         | 4.55%   |
| 151-200        | 2         | 4.55%   |
| 101-110        | 2         | 4.55%   |
| 41-50          | 1         | 2.27%   |
| 301-350        | 1         | 2.27%   |
| Unknown        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 17        | 38.64%  |
| 121-160       | 13        | 29.55%  |
| 51-100        | 7         | 15.91%  |
| 161-240       | 5         | 11.36%  |
| More than 240 | 1         | 2.27%   |
| Unknown       | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 67.19%  |
| 0     | 17        | 26.56%  |
| 2     | 4         | 6.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 31.13%  |
| Realtek Semiconductor             | 32        | 30.19%  |
| Qualcomm Atheros                  | 11        | 10.38%  |
| Broadcom                          | 11        | 10.38%  |
| Nvidia                            | 4         | 3.77%   |
| TP-Link                           | 2         | 1.89%   |
| Ralink Technology                 | 2         | 1.89%   |
| Ralink                            | 2         | 1.89%   |
| Marvell Technology Group          | 2         | 1.89%   |
| Xiaomi                            | 1         | 0.94%   |
| Sierra Wireless                   | 1         | 0.94%   |
| MediaTek                          | 1         | 0.94%   |
| IMC Networks                      | 1         | 0.94%   |
| Huawei Technologies               | 1         | 0.94%   |
| Ericsson Business Mobile Networks | 1         | 0.94%   |
| D-Link System                     | 1         | 0.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 19.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.94%   |
| Nvidia MCP79 Ethernet                                             | 4         | 3.15%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.15%   |
| Intel Wireless 7260                                               | 4         | 3.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 2.36%   |
| Intel Wireless 7265                                               | 3         | 2.36%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.36%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 2.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 1.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.57%   |
| Intel Wireless 3160                                               | 2         | 1.57%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.57%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.57%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.79%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.79%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.79%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Intel Wireless-AC 9260                                            | 1         | 0.79%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 47.76%  |
| Broadcom              | 10        | 14.93%  |
| Realtek Semiconductor | 8         | 11.94%  |
| Qualcomm Atheros      | 7         | 10.45%  |
| TP-Link               | 2         | 2.99%   |
| Ralink Technology     | 2         | 2.99%   |
| Ralink                | 2         | 2.99%   |
| Sierra Wireless       | 1         | 1.49%   |
| MediaTek              | 1         | 1.49%   |
| IMC Networks          | 1         | 1.49%   |
| D-Link System         | 1         | 1.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 4         | 5.8%    |
| Intel Wireless 7260                                                        | 4         | 5.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 4.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 4.35%   |
| Intel Wireless 7265                                                        | 3         | 4.35%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 4.35%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 2.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 2         | 2.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 2.9%    |
| Intel Wireless 3160                                                        | 2         | 2.9%    |
| Intel Wi-Fi 6 AX201                                                        | 2         | 2.9%    |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 2.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 1.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 1.45%   |
| Sierra Wireless EM7345 4G LTE                                              | 1         | 1.45%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 1.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 1.45%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 1.45%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.45%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 1.45%   |
| Intel Wireless-AC 9260                                                     | 1         | 1.45%   |
| Intel Wireless 8260                                                        | 1         | 1.45%   |
| Intel Wireless 3165                                                        | 1         | 1.45%   |
| Intel WiFi Link 5100                                                       | 1         | 1.45%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 1.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 1         | 1.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 1         | 1.45%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 1.45%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.45%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 1         | 1.45%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 30        | 53.57%  |
| Intel                    | 14        | 25%     |
| Qualcomm Atheros         | 4         | 7.14%   |
| Nvidia                   | 4         | 7.14%   |
| Marvell Technology Group | 2         | 3.57%   |
| Xiaomi                   | 1         | 1.79%   |
| Broadcom                 | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 44.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.93%   |
| Nvidia MCP79 Ethernet                                             | 4         | 7.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 7.14%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.79%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.79%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.79%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.79%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 50.86%  |
| Ethernet | 55        | 47.41%  |
| Modem    | 2         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 37        | 52.11%  |
| WiFi     | 33        | 46.48%  |
| Modem    | 1         | 1.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 51        | 83.61%  |
| 1     | 8         | 13.11%  |
| 6     | 1         | 1.64%   |
| 3     | 1         | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 96.72%  |
| Yes  | 2         | 3.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 25        | 52.08%  |
| Realtek Semiconductor           | 4         | 8.33%   |
| Apple                           | 4         | 8.33%   |
| Broadcom                        | 3         | 6.25%   |
| Ralink                          | 2         | 4.17%   |
| IMC Networks                    | 2         | 4.17%   |
| Hewlett-Packard                 | 2         | 4.17%   |
| Foxconn / Hon Hai               | 2         | 4.17%   |
| Cambridge Silicon Radio         | 2         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 2.08%   |
| ASUSTek Computer                | 1         | 2.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 30.61%  |
| Intel AX201 Bluetooth                                       | 4         | 8.16%   |
| Intel AX200 Bluetooth                                       | 3         | 6.12%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 4.08%   |
| Ralink RT3290 Bluetooth                                     | 2         | 4.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 4.08%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 4.08%   |
| Apple Bluetooth Host Controller                             | 2         | 4.08%   |
| Realtek Bluetooth Adapter                                   | 1         | 2.04%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 2.04%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 2.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 2.04%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 2.04%   |
| IMC Networks Bluetooth module                               | 1         | 2.04%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 2.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 2.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 2.04%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 2.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 46        | 63.89%  |
| Nvidia                                       | 12        | 16.67%  |
| AMD                                          | 11        | 15.28%  |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.39%   |
| Texas Instruments                            | 1         | 1.39%   |
| Generalplus Technology                       | 1         | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 7.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 5.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 5.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.38%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.38%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.19%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.19%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.19%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 1.19%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.19%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.19%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 1.19%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 25.81%  |
| SK hynix            | 12        | 19.35%  |
| Kingston            | 8         | 12.9%   |
| Micron Technology   | 5         | 8.06%   |
| Crucial             | 5         | 8.06%   |
| Unknown             | 3         | 4.84%   |
| Ramaxel Technology  | 2         | 3.23%   |
| Elpida              | 2         | 3.23%   |
| Unknown             | 2         | 3.23%   |
| Unknown (ABCD)      | 1         | 1.61%   |
| Transcend           | 1         | 1.61%   |
| Nanya Technology    | 1         | 1.61%   |
| G.Skill             | 1         | 1.61%   |
| Corsair             | 1         | 1.61%   |
| ASint Technology    | 1         | 1.61%   |
| A-DATA Technology   | 1         | 1.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.78%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 2         | 2.78%   |
| Unknown                                                                   | 2         | 2.78%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 1.39%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.39%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s                      | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.39%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s             | 1         | 1.39%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 1.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.39%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.39%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.39%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 1         | 1.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.39%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.39%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.39%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s                     | 1         | 1.39%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 800MT/s                      | 1         | 1.39%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 45.45%  |
| DDR4    | 18        | 32.73%  |
| DDR2    | 7         | 12.73%  |
| LPDDR4  | 2         | 3.64%   |
| SDRAM   | 1         | 1.82%   |
| LPDDR3  | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 94.55%  |
| Row Of Chips | 3         | 5.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 36.67%  |
| 8192  | 18        | 30%     |
| 2048  | 10        | 16.67%  |
| 16384 | 6         | 10%     |
| 1024  | 3         | 5%      |
| 32768 | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 27.12%  |
| 3200    | 7         | 11.86%  |
| 2667    | 6         | 10.17%  |
| 2400    | 6         | 10.17%  |
| 667     | 5         | 8.47%   |
| 1067    | 4         | 6.78%   |
| 1334    | 3         | 5.08%   |
| 1867    | 2         | 3.39%   |
| 1333    | 2         | 3.39%   |
| 1066    | 2         | 3.39%   |
| 800     | 2         | 3.39%   |
| 3733    | 1         | 1.69%   |
| 2133    | 1         | 1.69%   |
| 2048    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

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
| Chicony Electronics                    | 10        | 23.81%  |
| Sunplus Innovation Technology          | 6         | 14.29%  |
| Realtek Semiconductor                  | 4         | 9.52%   |
| Microdia                               | 4         | 9.52%   |
| Suyin                                  | 3         | 7.14%   |
| Quanta                                 | 3         | 7.14%   |
| IMC Networks                           | 2         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.76%   |
| Bison Electronics                      | 2         | 4.76%   |
| USB Camera                             | 1         | 2.38%   |
| Syntek                                 | 1         | 2.38%   |
| Silicon Motion                         | 1         | 2.38%   |
| Ricoh                                  | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| Alcor Micro                            | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 3         | 7.14%   |
| Chicony Integrated Camera                                                  | 3         | 7.14%   |
| Realtek USB Camera                                                         | 2         | 4.76%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 4.76%   |
| USB Camera USB Camera                                                      | 1         | 2.38%   |
| Syntek EasyCamera                                                          | 1         | 2.38%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2.38%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 2.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 2.38%   |
| Sunplus Integrated Camera                                                  | 1         | 2.38%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2.38%   |
| Sunplus Asus Webcam                                                        | 1         | 2.38%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 2.38%   |
| Ricoh Integrated Webcam                                                    | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.38%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 2.38%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 2.38%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2.38%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.38%   |
| Microdia Integrated Webcam                                                 | 1         | 2.38%   |
| Microdia HP Webcam                                                         | 1         | 2.38%   |
| Lite-On Integrated Camera                                                  | 1         | 2.38%   |
| IMC Networks Realtek PC Camera                                             | 1         | 2.38%   |
| IMC Networks 2M Integrated Webcam                                          | 1         | 2.38%   |
| Chicony WebCam                                                             | 1         | 2.38%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2.38%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.38%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.38%   |
| Chicony Integrated IR Camera                                               | 1         | 2.38%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.38%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.38%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.38%   |
| Bison Integrated Camera                                                    | 1         | 2.38%   |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 6         | 66.67%  |
| Upek               | 1         | 11.11%  |
| Synaptics          | 1         | 11.11%  |
| STMicroelectronics | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 22.22%  |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 11.11%  |
| Validity Sensors Synaptics WBDI                          | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner                     | 1         | 11.11%  |
| Upek TCS5B Fingerprint sensor                            | 1         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                    | 1         | 11.11%  |

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
| 1     | 25        | 37.88%  |
| 2     | 16        | 24.24%  |
| 3     | 12        | 18.18%  |
| 0     | 8         | 12.12%  |
| 4     | 5         | 7.58%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 38        | 37.62%  |
| Net/wireless             | 20        | 19.8%   |
| Bluetooth                | 16        | 15.84%  |
| Card reader              | 11        | 10.89%  |
| Fingerprint reader       | 8         | 7.92%   |
| Graphics card            | 3         | 2.97%   |
| Firewire controller      | 3         | 2.97%   |
| Network                  | 2         | 1.98%   |

