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

Total: 94

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
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
| helloSystem 0.7.0    | 16        | 21.05%  |
| helloSystem 0.8.0    | 6         | 7.89%   |
| helloSystem 0.8.1    | 4         | 5.26%   |
| helloSystem 0.5.0    | 4         | 5.26%   |
| FreeBSD 13.1         | 4         | 5.26%   |
| OpenBSD 7.2          | 3         | 3.95%   |
| helloSystem 0.6.0    | 3         | 3.95%   |
| GhostBSD 20.04.02    | 3         | 3.95%   |
| OpenBSD 7.1          | 2         | 2.63%   |
| OpenBSD 6.8          | 2         | 2.63%   |
| helloSystem 0.4.0    | 2         | 2.63%   |
| FuguIta 7.2          | 2         | 2.63%   |
| OPNsense 23.1.6      | 1         | 1.32%   |
| OPNsense 22.7.10     | 1         | 1.32%   |
| OPNsense 21.7.6      | 1         | 1.32%   |
| OPNsense 21.7.5      | 1         | 1.32%   |
| OpenBSD 7.3          | 1         | 1.32%   |
| OpenBSD 6.9          | 1         | 1.32%   |
| NomadBSD 5806f915    | 1         | 1.32%   |
| NomadBSD 20221130    | 1         | 1.32%   |
| helloSystem 0.8.2    | 1         | 1.32%   |
| GhostBSD 23.03.17    | 1         | 1.32%   |
| GhostBSD 23.01.13    | 1         | 1.32%   |
| GhostBSD 22.06.18    | 1         | 1.32%   |
| GhostBSD 21.08.27    | 1         | 1.32%   |
| FreeBSD 14.0-CURRENT | 1         | 1.32%   |
| FreeBSD 13.2         | 1         | 1.32%   |
| FreeBSD 13.1-p7      | 1         | 1.32%   |
| FreeBSD 13.1-p5      | 1         | 1.32%   |
| FreeBSD 13.1-p2      | 1         | 1.32%   |
| FreeBSD 13.1-p1      | 1         | 1.32%   |
| FreeBSD 13.0-STABLE  | 1         | 1.32%   |
| FreeBSD 13.0-RC3     | 1         | 1.32%   |
| FreeBSD 13.0-RC1     | 1         | 1.32%   |
| FreeBSD 13.0-BETA4   | 1         | 1.32%   |
| FreeBSD 13.0         | 1         | 1.32%   |
| FreeBSD 12.3         | 1         | 1.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 29        | 43.94%  |
| FreeBSD     | 16        | 24.24%  |
| OpenBSD     | 7         | 10.61%  |
| GhostBSD    | 7         | 10.61%  |
| OPNsense    | 3         | 4.55%   |
| NomadBSD    | 2         | 3.03%   |
| FuguIta     | 2         | 3.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 62        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 36        | 53.73%  |
| MATE         | 8         | 11.94%  |
| Console      | 8         | 11.94%  |
| Openbox      | 3         | 4.48%   |
| fvwm         | 3         | 4.48%   |
| XFCE         | 2         | 2.99%   |
| TWM          | 2         | 2.99%   |
| KDE5         | 2         | 2.99%   |
| i3           | 2         | 2.99%   |
| GNOME        | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 53        | 84.13%  |
| Console | 8         | 12.7%   |
| Wayland | 2         | 3.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 32        | 48.48%  |
| Console | 18        | 27.27%  |
| LightDM | 7         | 10.61%  |
| SDDM    | 4         | 6.06%   |
| GDM     | 3         | 4.55%   |
| XDM     | 1         | 1.52%   |
| Ly      | 1         | 1.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 24        | 35.82%  |
| es_ES   | 14        | 20.9%   |
| C       | 12        | 17.91%  |
| Unknown | 11        | 16.42%  |
| es      | 3         | 4.48%   |
| zh_CN   | 1         | 1.49%   |
| ru_RU   | 1         | 1.49%   |
| de_DE   | 1         | 1.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 51        | 82.26%  |
| BIOS | 11        | 17.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 37        | 56.92%  |
| Cd9660 | 13        | 20%     |
| Ffs    | 9         | 13.85%  |
| Ufs    | 6         | 9.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 53        | 85.48%  |
| MBR  | 9         | 14.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 20.97%  |
| Lenovo              | 12        | 19.35%  |
| Dell                | 7         | 11.29%  |
| ASUSTek Computer    | 7         | 11.29%  |
| Apple               | 4         | 6.45%   |
| Acer                | 3         | 4.84%   |
| SLIMBOOK            | 2         | 3.23%   |
| Unknown             | 2         | 3.23%   |
| TWINHEAD            | 1         | 1.61%   |
| TUXEDO              | 1         | 1.61%   |
| Toshiba             | 1         | 1.61%   |
| Sony                | 1         | 1.61%   |
| Samsung Electronics | 1         | 1.61%   |
| ReachingTech        | 1         | 1.61%   |
| Razer               | 1         | 1.61%   |
| Packard Bell        | 1         | 1.61%   |
| MSI                 | 1         | 1.61%   |
| Chuwi               | 1         | 1.61%   |
| AZW                 | 1         | 1.61%   |
| Alienware           | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Latitude 7390                   | 3         | 4.84%   |
| Unknown                              | 3         | 4.84%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 2         | 3.23%   |
| ASUS K55VD                           | 2         | 3.23%   |
| TWINHEAD U12CT                       | 1         | 1.61%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.61%   |
| Toshiba Satellite A300               | 1         | 1.61%   |
| Sony SVE1511C5E                      | 1         | 1.61%   |
| SLIMBOOK PROX-AMD5                   | 1         | 1.61%   |
| SLIMBOOK ESSENTIAL-15-11             | 1         | 1.61%   |
| Samsung 530U3C/530U4C/532U3C         | 1         | 1.61%   |
| ReachingTech DreamQuest Pro 2022     | 1         | 1.61%   |
| Razer Blade Stealth                  | 1         | 1.61%   |
| Packard Bell DOT S                   | 1         | 1.61%   |
| MSI GE75 Raider 10SGS                | 1         | 1.61%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.61%   |
| Lenovo ThinkPad X270 20HMS06Q1D      | 1         | 1.61%   |
| Lenovo ThinkPad X200 745969G         | 1         | 1.61%   |
| Lenovo ThinkPad T61 765912G          | 1         | 1.61%   |
| Lenovo ThinkPad T440p 20AW007QMS     | 1         | 1.61%   |
| Lenovo ThinkPad L590 20Q7000YSP      | 1         | 1.61%   |
| Lenovo ThinkPad L450 20DSS1S402      | 1         | 1.61%   |
| Lenovo ThinkPad L440 20ASS0FP00      | 1         | 1.61%   |
| Lenovo ThinkPad E495 20NE000BSP      | 1         | 1.61%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW | 1         | 1.61%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 1         | 1.61%   |
| Lenovo G50-80 80E5                   | 1         | 1.61%   |
| HP ProBook 4540s                     | 1         | 1.61%   |
| HP ProBook 4340s                     | 1         | 1.61%   |
| HP ProBook 430 G7                    | 1         | 1.61%   |
| HP Pavilion dv6                      | 1         | 1.61%   |
| HP Pavilion dv4                      | 1         | 1.61%   |
| HP OMEN by Laptop                    | 1         | 1.61%   |
| HP OMEN by HP Laptop 17-cb1xxx       | 1         | 1.61%   |
| HP Laptop 15-db0xxx                  | 1         | 1.61%   |
| HP EliteBook 2730p                   | 1         | 1.61%   |
| HP Compaq 6735s                      | 1         | 1.61%   |
| HP 250 G4                            | 1         | 1.61%   |
| Dell Studio XPS 1340                 | 1         | 1.61%   |
| Dell Precision 5510                  | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 9         | 14.52%  |
| HP Pavilion              | 4         | 6.45%   |
| Dell Latitude            | 4         | 6.45%   |
| HP ProBook               | 3         | 4.84%   |
| Unknown                  | 3         | 4.84%   |
| HP OMEN                  | 2         | 3.23%   |
| ASUS K55VD               | 2         | 3.23%   |
| Apple MacBook5           | 2         | 3.23%   |
| Acer Aspire              | 2         | 3.23%   |
| TWINHEAD U12CT           | 1         | 1.61%   |
| TUXEDO Aura              | 1         | 1.61%   |
| Toshiba Satellite        | 1         | 1.61%   |
| Sony SVE1511C5E          | 1         | 1.61%   |
| SLIMBOOK PROX-AMD5       | 1         | 1.61%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 1.61%   |
| Samsung 530U3C           | 1         | 1.61%   |
| ReachingTech DreamQuest  | 1         | 1.61%   |
| Razer Blade              | 1         | 1.61%   |
| Packard Bell DOT         | 1         | 1.61%   |
| MSI GE75                 | 1         | 1.61%   |
| Lenovo Yoga              | 1         | 1.61%   |
| Lenovo IdeaPad           | 1         | 1.61%   |
| Lenovo G50-80            | 1         | 1.61%   |
| HP Laptop                | 1         | 1.61%   |
| HP EliteBook             | 1         | 1.61%   |
| HP Compaq                | 1         | 1.61%   |
| HP 250                   | 1         | 1.61%   |
| Dell Studio              | 1         | 1.61%   |
| Dell Precision           | 1         | 1.61%   |
| Dell Inspiron            | 1         | 1.61%   |
| AZW BT3                  | 1         | 1.61%   |
| ASUS X556UJ              | 1         | 1.61%   |
| ASUS U33Jc               | 1         | 1.61%   |
| ASUS TUF                 | 1         | 1.61%   |
| ASUS 1215B               | 1         | 1.61%   |
| ASUS 1201N               | 1         | 1.61%   |
| Apple MacBook6           | 1         | 1.61%   |
| Apple MacBook4           | 1         | 1.61%   |
| Alienware m15            | 1         | 1.61%   |
| Acer Extensa             | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 11        | 17.74%  |
| 2019 | 7         | 11.29%  |
| 2012 | 6         | 9.68%   |
| 2022 | 5         | 8.06%   |
| 2009 | 5         | 8.06%   |
| 2018 | 4         | 6.45%   |
| 2015 | 4         | 6.45%   |
| 2011 | 4         | 6.45%   |
| 2008 | 4         | 6.45%   |
| 2014 | 3         | 4.84%   |
| 2010 | 3         | 4.84%   |
| 2021 | 2         | 3.23%   |
| 2016 | 2         | 3.23%   |
| 2017 | 1         | 1.61%   |
| 2007 | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 62        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 62        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 25        | 39.06%  |
| 4.01-8.0    | 15        | 23.44%  |
| 16.01-24.0  | 12        | 18.75%  |
| 32.01-64.0  | 6         | 9.38%   |
| 3.01-4.0    | 2         | 3.13%   |
| 2.01-3.0    | 2         | 3.13%   |
| 24.01-32.0  | 1         | 1.56%   |
| 64.01-256.0 | 1         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 34        | 52.31%  |
| 0.51-1.0 | 21        | 32.31%  |
| 1.01-2.0 | 7         | 10.77%  |
| 2.01-3.0 | 3         | 4.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 45        | 71.43%  |
| 2      | 13        | 20.63%  |
| 3      | 2         | 3.17%   |
| 0      | 2         | 3.17%   |
| 4      | 1         | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 46        | 73.02%  |
| Yes       | 17        | 26.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 90.32%  |
| No        | 6         | 9.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 96.77%  |
| No        | 2         | 3.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 49        | 79.03%  |
| No        | 13        | 20.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 62        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 12        | 16.9%   |
| Barcelona                     | 8         | 11.27%  |
| Valencia                      | 4         | 5.63%   |
| Terrassa                      | 3         | 4.23%   |
| Navalcarnero                  | 3         | 4.23%   |
| Tarragona                     | 2         | 2.82%   |
| Paterna                       | 2         | 2.82%   |
| GibraleГіn                  | 2         | 2.82%   |
| Alcobendas                    | 2         | 2.82%   |
| Vitoria-Gasteiz               | 1         | 1.41%   |
| Villapresente                 | 1         | 1.41%   |
| Urnieta                       | 1         | 1.41%   |
| Tudela de Duero               | 1         | 1.41%   |
| Seville                       | 1         | 1.41%   |
| Sedavi                        | 1         | 1.41%   |
| Santa Cruz de Tenerife        | 1         | 1.41%   |
| Sanlucar la Mayor             | 1         | 1.41%   |
| San Vicent del Raspeig        | 1         | 1.41%   |
| San SebastiÃ¡n de los Reyes | 1         | 1.41%   |
| Rubí                         | 1         | 1.41%   |
| Redondela                     | 1         | 1.41%   |
| Málaga                       | 1         | 1.41%   |
| LogroГ±o                    | 1         | 1.41%   |
| LogroÃ±o                    | 1         | 1.41%   |
| Laguna de Duero               | 1         | 1.41%   |
| La Pobla de Farnals           | 1         | 1.41%   |
| Ibiza Town                    | 1         | 1.41%   |
| Fuenterrabia                  | 1         | 1.41%   |
| Esparragosa de Lares          | 1         | 1.41%   |
| Elche                         | 1         | 1.41%   |
| Coria del RÃ­o              | 1         | 1.41%   |
| Córdoba                      | 1         | 1.41%   |
| Colombres                     | 1         | 1.41%   |
| Cho                           | 1         | 1.41%   |
| Carcer                        | 1         | 1.41%   |
| Cambre                        | 1         | 1.41%   |
| Beniarjo                      | 1         | 1.41%   |
| Beneixama                     | 1         | 1.41%   |
| Badalona                      | 1         | 1.41%   |
| Ãguilas                    | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 13        | 27     | 16.88%  |
| WDC                                    | 8         | 10     | 10.39%  |
| NVMe                                   | 6         | 9      | 7.79%   |
| Toshiba                                | 5         | 7      | 6.49%   |
| Hitachi                                | 5         | 5      | 6.49%   |
| Crucial                                | 5         | 5      | 6.49%   |
| Seagate                                | 4         | 4      | 5.19%   |
| Kingston                               | 4         | 5      | 5.19%   |
| SanDisk                                | 3         | 3      | 3.9%    |
| Intel                                  | 3         | 3      | 3.9%    |
| HGST                                   | 3         | 3      | 3.9%    |
| Product:              USB Flash Memory | 2         | 2      | 2.6%    |
| Micron Technology                      | 2         | 2      | 2.6%    |
| Fujitsu                                | 2         | 2      | 2.6%    |
| XrayDisk                               | 1         | 1      | 1.3%    |
| Union Memory                           | 1         | 1      | 1.3%    |
| Transcend                              | 1         | 1      | 1.3%    |
| TCSUNBOW                               | 1         | 1      | 1.3%    |
| SK hynix                               | 1         | 1      | 1.3%    |
| PNY                                    | 1         | 1      | 1.3%    |
| Netac                                  | 1         | 1      | 1.3%    |
| LITEONIT                               | 1         | 1      | 1.3%    |
| Kston                                  | 1         | 2      | 1.3%    |
| KIOXIA                                 | 1         | 1      | 1.3%    |
| KingSpec                               | 1         | 1      | 1.3%    |
| China                                  | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 2.44%   |
| NVMe Samsung SSD 980 500GB                                   | 2         | 2.44%   |
| XrayDisk SSD 240GB                                           | 1         | 1.22%   |
| WDC WDS100T2B0C-00PXH0 1TB                                   | 1         | 1.22%   |
| WDC WD5000LPCX-21VHAT0 500GB                                 | 1         | 1.22%   |
| WDC WD2500BEVT-35A23T0 250GB                                 | 1         | 1.22%   |
| WDC WD1200BEVS-22UST0 120GB                                  | 1         | 1.22%   |
| WDC WD10JPCX-24UE4T0 1TB                                     | 1         | 1.22%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 1         | 1.22%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                           | 1         | 1.22%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB                           | 1         | 1.22%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                         | 1         | 1.22%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB              | 1         | 1.22%   |
| Transcend TS120GMTS420S 120GB                                | 1         | 1.22%   |
| Toshiba MQ01ABD100 1TB                                       | 1         | 1.22%   |
| Toshiba MK5065GSXF 500GB                                     | 1         | 1.22%   |
| Toshiba MK1229GSG 120GB                                      | 1         | 1.22%   |
| Toshiba MK1059GSM 1TB                                        | 1         | 1.22%   |
| Toshiba KXG60ZNV512G NVMe 512GB                              | 1         | 1.22%   |
| TCSUNBOW X3 480GB                                            | 1         | 1.22%   |
| SK hynix HFM512GDHTNG-8710B 512GB                            | 1         | 1.22%   |
| Seagate ST9500325AS 500GB                                    | 1         | 1.22%   |
| Seagate ST500LM021-1KJ152 500GB                              | 1         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                               | 1         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 1         | 1.22%   |
| SanDisk SSD PLUS 240GB                                       | 1         | 1.22%   |
| SanDisk SSD i100 24GB                                        | 1         | 1.22%   |
| SanDisk SDSSDP128G 128GB                                     | 1         | 1.22%   |
| Samsung SSD 970 EVO Plus 2TB                                 | 1         | 1.22%   |
| Samsung SSD 970 EVO 250GB                                    | 1         | 1.22%   |
| Samsung SSD 870 QVO 8TB                                      | 1         | 1.22%   |
| Samsung SSD 870 EVO 1TB                                      | 1         | 1.22%   |
| Samsung SSD 860 PRO 512GB                                    | 1         | 1.22%   |
| Samsung SSD 860 EVO 500GB                                    | 1         | 1.22%   |
| Samsung SSD 850 EVO 500GB                                    | 1         | 1.22%   |
| Samsung SSD 850 EVO 250GB                                    | 1         | 1.22%   |
| Samsung SSD 840 PRO Series 128GB                             | 1         | 1.22%   |
| Samsung SSD 750 EVO 250GB                                    | 1         | 1.22%   |
| Samsung PM9A1 NVMe 512GB                                     | 1         | 1.22%   |
| Samsung MZVLW512HMJP-00000 512GB                             | 1         | 1.22%   |

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
| NVMe                                   | 3         | 5      | 10%     |
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
| Samsung Electronics | 8         | 14     | 25%     |
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
| SSD  | 31        | 40     | 40.79%  |
| HDD  | 29        | 34     | 38.16%  |
| NVMe | 16        | 26     | 21.05%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 50        | 74     | 75.76%  |
| NVMe | 16        | 26     | 24.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 56     | 77.78%  |
| 0.51-1.0   | 10        | 14     | 18.52%  |
| 1.01-2.0   | 1         | 3      | 1.85%   |
| 4.01-10.0  | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 24        | 35.82%  |
| 101-250    | 21        | 31.34%  |
| 251-500    | 13        | 19.4%   |
| 501-1000   | 4         | 5.97%   |
| 1001-2000  | 2         | 2.99%   |
| 51-100     | 2         | 2.99%   |
| 21-50      | 1         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 57        | 89.06%  |
| 21-50    | 3         | 4.69%   |
| 51-100   | 2         | 3.13%   |
| 251-500  | 1         | 1.56%   |
| 501-1000 | 1         | 1.56%   |

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
| Works    | 48        | 76     | 71.64%  |
| Malfunc  | 13        | 13     | 19.4%   |
| Detected | 6         | 11     | 8.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 56.34%  |
| Samsung Electronics         | 6         | 8.45%   |
| AMD                         | 6         | 8.45%   |
| Nvidia                      | 5         | 7.04%   |
| Sandisk                     | 4         | 5.63%   |
| SK hynix                    | 2         | 2.82%   |
| Micron/Crucial Technology   | 2         | 2.82%   |
| Union Memory (Shenzhen)     | 1         | 1.41%   |
| Toshiba                     | 1         | 1.41%   |
| Phison Electronics          | 1         | 1.41%   |
| Micron Technology           | 1         | 1.41%   |
| KIOXIA                      | 1         | 1.41%   |
| Kingston Technology Company | 1         | 1.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 7.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 6.33%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 5.06%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 5.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.8%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 2.53%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.53%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.53%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.53%   |
| Union Memory (Shenzhen) NVMe 256G SSD device                                   | 1         | 1.27%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.27%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.27%   |
| Sandisk WD Black SN770 NVMe SSD                                                | 1         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.27%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.27%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 1.27%   |
| Micron NVMe Storage Controller                                                 | 1         | 1.27%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 1.27%   |
| Kingston Company unknown                                                       | 1         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.27%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.27%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.27%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 1         | 1.27%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 47        | 62.67%  |
| NVMe | 19        | 25.33%  |
| IDE  | 6         | 8%      |
| RAID | 3         | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 83.87%  |
| AMD    | 10        | 16.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz     | 2         | 3.23%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 3.23%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 2         | 3.23%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 2         | 3.23%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.61%   |
| Intel Pentium CPU B970 @ 2.30GHz       | 1         | 1.61%   |
| Intel CPU Version                      | 1         | 1.61%   |
| Intel Core i9-10980HK CPU @ 2.40GHz    | 1         | 1.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 1.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 1         | 1.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 1         | 1.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.61%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz     | 1         | 1.61%   |
| Intel Core i7-4510U CPU @ 2.00GHz      | 1         | 1.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz     | 1         | 1.61%   |
| Intel Core i7-10875H CPU @ 2.30GHz     | 1         | 1.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1         | 1.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.61%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 1         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.61%   |
| Intel Core i5-2537M CPU @ 1.40GHz      | 1         | 1.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz      | 1         | 1.61%   |
| Intel Core i5 CPU U 560 @ 1.33GHz      | 1         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.61%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1         | 1.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 1         | 1.61%   |
| Intel Core i3 CPU M 370 @ 2.40GH       | 1         | 1.61%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P9500 @ 2.53GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz   | 1         | 1.61%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz   | 1         | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 14        | 22.58%  |
| Intel Core i7      | 13        | 20.97%  |
| Intel Core 2 Duo   | 9         | 14.52%  |
| AMD Ryzen 7        | 5         | 8.06%   |
| Intel Core i3      | 4         | 6.45%   |
| Other              | 3         | 4.84%   |
| Intel Celeron      | 3         | 4.84%   |
| Intel Atom         | 3         | 4.84%   |
| AMD Ryzen 5        | 2         | 3.23%   |
| Intel Pentium Dual | 1         | 1.61%   |
| Intel Pentium      | 1         | 1.61%   |
| Intel Core i9      | 1         | 1.61%   |
| AMD Sempron        | 1         | 1.61%   |
| AMD E              | 1         | 1.61%   |
| AMD A4             | 1         | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 26        | 41.94%  |
| 4       | 16        | 25.81%  |
| Unknown | 9         | 14.52%  |
| 8       | 5         | 8.06%   |
| 16      | 2         | 3.23%   |
| 12      | 2         | 3.23%   |
| 6       | 1         | 1.61%   |
| 1       | 1         | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 57        | 91.94%  |
| 2       | 4         | 6.45%   |
| Unknown | 1         | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 34        | 54.84%  |
| 1       | 19        | 30.65%  |
| Unknown | 9         | 14.52%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 9         | 14.52%  |
| Penryn          | 8         | 12.9%   |
| IvyBridge       | 5         | 8.06%   |
| Haswell         | 5         | 8.06%   |
| Skylake         | 4         | 6.45%   |
| Zen 2           | 3         | 4.84%   |
| SandyBridge     | 3         | 4.84%   |
| Core            | 3         | 4.84%   |
| CometLake       | 3         | 4.84%   |
| Zen+            | 2         | 3.23%   |
| Westmere        | 2         | 3.23%   |
| TigerLake       | 2         | 3.23%   |
| Silvermont      | 2         | 3.23%   |
| Broadwell       | 2         | 3.23%   |
| Bonnell         | 2         | 3.23%   |
| Unknown         | 2         | 3.23%   |
| Zen 3           | 1         | 1.61%   |
| K8 & K10 hybrid | 1         | 1.61%   |
| Goldmont plus   | 1         | 1.61%   |
| Excavator       | 1         | 1.61%   |
| Bobcat          | 1         | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 43        | 56.58%  |
| Nvidia | 18        | 23.68%  |
| AMD    | 15        | 19.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.33%   |
| Intel UHD Graphics 620                                                                   | 3         | 3.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.8%    |
| Intel HD Graphics 620                                                                    | 3         | 3.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.8%    |
| AMD Renoir                                                                               | 3         | 3.8%    |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 2.53%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.53%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.53%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.53%   |
| Intel HD Graphics 530                                                                    | 2         | 2.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.27%   |
| Nvidia TU117M                                                                            | 1         | 1.27%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.27%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.27%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.27%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.27%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.27%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.27%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.27%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.27%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.27%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 1.27%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.27%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 1.27%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 28        | 44.44%  |
| 1 x AMD        | 9         | 14.29%  |
| Intel + Nvidia | 8         | 12.7%   |
| 1 x Nvidia     | 6         | 9.52%   |
| 2 x Intel      | 5         | 7.94%   |
| Intel + AMD    | 3         | 4.76%   |
| AMD + Nvidia   | 3         | 4.76%   |
| 2 x Nvidia     | 1         | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 57        | 89.06%  |
| Proprietary | 5         | 7.81%   |
| Unknown     | 2         | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 86.15%  |
| 0.01-0.5   | 7         | 10.77%  |
| 7.01-8.0   | 1         | 1.54%   |
| 2.01-3.0   | 1         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 17.39%  |
| LG Display              | 5         | 10.87%  |
| Chimei Innolux          | 5         | 10.87%  |
| BOE                     | 5         | 10.87%  |
| Chi Mei Optoelectronics | 4         | 8.7%    |
| Samsung Electronics     | 3         | 6.52%   |
| Lenovo                  | 3         | 6.52%   |
| Apple                   | 3         | 6.52%   |
| BenQ                    | 2         | 4.35%   |
| Sharp                   | 1         | 2.17%   |
| PANDA                   | 1         | 2.17%   |
| Mi                      | 1         | 2.17%   |
| LGD                     | 1         | 2.17%   |
| LG Philips              | 1         | 2.17%   |
| Hewlett-Packard         | 1         | 2.17%   |
| Fujitsu Siemens         | 1         | 2.17%   |
| AOC                     | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch           | 3         | 6.38%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 4.26%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch                  | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 2.13%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                  | 1         | 2.13%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                         | 1         | 2.13%   |
| LGD LCD Monitor 5760x1080                                                | 1         | 2.13%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 2.13%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 2.13%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch               | 1         | 2.13%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 340x190mm 15.3-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 340x190mm 15.3-inch | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 300x190mm 14.0-inch | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 220x120mm 9.9-inch  | 1         | 2.13%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 2.13%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 2.13%   |
| BenQ LCD Monitor GL2450H                                                 | 1         | 2.13%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO312C 1366x768 290x160mm 13.0-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 1         | 2.13%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 340x190mm 15.3-inch            | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 16        | 36.36%  |
| 1366x768 (WXGA)  | 13        | 29.55%  |
| 1280x800 (WXGA)  | 8         | 18.18%  |
| 1600x900 (HD+)   | 2         | 4.55%   |
| 5760x1080        | 1         | 2.27%   |
| 3840x2160 (4K)   | 1         | 2.27%   |
| 1280x1024 (SXGA) | 1         | 2.27%   |
| 1024x600         | 1         | 2.27%   |
| Unknown          | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 20        | 43.48%  |
| 13      | 13        | 28.26%  |
| 24      | 3         | 6.52%   |
| 12      | 3         | 6.52%   |
| 19      | 2         | 4.35%   |
| 14      | 2         | 4.35%   |
| 27      | 1         | 2.17%   |
| 9       | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 24        | 52.17%  |
| 201-300     | 15        | 32.61%  |
| 501-600     | 4         | 8.7%    |
| 401-500     | 1         | 2.17%   |
| 351-400     | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 32        | 76.19%  |
| 16/10   | 7         | 16.67%  |
| 5/4     | 1         | 2.38%   |
| 3/2     | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 18        | 39.13%  |
| 81-90          | 9         | 19.57%  |
| 71-80          | 6         | 13.04%  |
| 61-70          | 3         | 6.52%   |
| 201-250        | 3         | 6.52%   |
| 151-200        | 2         | 4.35%   |
| 101-110        | 2         | 4.35%   |
| 41-50          | 1         | 2.17%   |
| 301-350        | 1         | 2.17%   |
| Unknown        | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 17        | 36.96%  |
| 121-160       | 14        | 30.43%  |
| 51-100        | 8         | 17.39%  |
| 161-240       | 5         | 10.87%  |
| More than 240 | 1         | 2.17%   |
| Unknown       | 1         | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 66.67%  |
| 0     | 17        | 25.76%  |
| 2     | 5         | 7.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 34        | 31.48%  |
| Realtek Semiconductor             | 33        | 30.56%  |
| Qualcomm Atheros                  | 11        | 10.19%  |
| Broadcom                          | 11        | 10.19%  |
| Nvidia                            | 4         | 3.7%    |
| TP-Link                           | 2         | 1.85%   |
| Ralink Technology                 | 2         | 1.85%   |
| Ralink                            | 2         | 1.85%   |
| Marvell Technology Group          | 2         | 1.85%   |
| Xiaomi                            | 1         | 0.93%   |
| Sierra Wireless                   | 1         | 0.93%   |
| MediaTek                          | 1         | 0.93%   |
| IMC Networks                      | 1         | 0.93%   |
| Huawei Technologies               | 1         | 0.93%   |
| Ericsson Business Mobile Networks | 1         | 0.93%   |
| D-Link System                     | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.85%   |
| Nvidia MCP79 Ethernet                                             | 4         | 3.08%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.08%   |
| Intel Wireless 7260                                               | 4         | 3.08%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 3.08%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 2.31%   |
| Intel Wireless 7265                                               | 3         | 2.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.54%   |
| Intel Wireless 3160                                               | 2         | 1.54%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.77%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.77%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.77%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.77%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 47.83%  |
| Broadcom              | 10        | 14.49%  |
| Realtek Semiconductor | 9         | 13.04%  |
| Qualcomm Atheros      | 7         | 10.14%  |
| TP-Link               | 2         | 2.9%    |
| Ralink Technology     | 2         | 2.9%    |
| Ralink                | 2         | 2.9%    |
| Sierra Wireless       | 1         | 1.45%   |
| MediaTek              | 1         | 1.45%   |
| IMC Networks          | 1         | 1.45%   |
| D-Link System         | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 4         | 5.63%   |
| Intel Wireless 7260                                            | 4         | 5.63%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 5.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 4.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 4.23%   |
| Intel Wireless 7265                                            | 3         | 4.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 4.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 4.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 2.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 2.82%   |
| Intel Wireless 3160                                            | 2         | 2.82%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 2.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.82%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.41%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.41%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.41%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.41%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.41%   |
| Intel Wireless-AC 9260                                         | 1         | 1.41%   |
| Intel Wireless 8260                                            | 1         | 1.41%   |
| Intel Wireless 3165                                            | 1         | 1.41%   |
| Intel WiFi Link 5100                                           | 1         | 1.41%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.41%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.41%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.41%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 1         | 1.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 54.39%  |
| Intel                    | 14        | 24.56%  |
| Qualcomm Atheros         | 4         | 7.02%   |
| Nvidia                   | 4         | 7.02%   |
| Marvell Technology Group | 2         | 3.51%   |
| Xiaomi                   | 1         | 1.75%   |
| Broadcom                 | 1         | 1.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26        | 45.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 8.77%   |
| Nvidia MCP79 Ethernet                                             | 4         | 7.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 7.02%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 3.51%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.75%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.75%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.75%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.75%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.75%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.75%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 50.85%  |
| Ethernet | 56        | 47.46%  |
| Modem    | 2         | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 52.05%  |
| WiFi     | 34        | 46.58%  |
| Modem    | 1         | 1.37%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 52        | 83.87%  |
| 1     | 8         | 12.9%   |
| 6     | 1         | 1.61%   |
| 3     | 1         | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 60        | 96.77%  |
| Yes  | 2         | 3.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 52%     |
| Realtek Semiconductor           | 5         | 10%     |
| Apple                           | 4         | 8%      |
| Broadcom                        | 3         | 6%      |
| Ralink                          | 2         | 4%      |
| IMC Networks                    | 2         | 4%      |
| Hewlett-Packard                 | 2         | 4%      |
| Foxconn / Hon Hai               | 2         | 4%      |
| Cambridge Silicon Radio         | 2         | 4%      |
| Qualcomm Atheros Communications | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 29.41%  |
| Intel AX201 Bluetooth                                       | 4         | 7.84%   |
| Intel AX200 Bluetooth                                       | 4         | 7.84%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 3.92%   |
| Ralink RT3290 Bluetooth                                     | 2         | 3.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 3.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.92%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 3.92%   |
| Apple Bluetooth Host Controller                             | 2         | 3.92%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.96%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.96%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.96%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.96%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.96%   |
| IMC Networks Bluetooth module                               | 1         | 1.96%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.96%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.96%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.96%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.96%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 46        | 63.01%  |
| Nvidia                                       | 12        | 16.44%  |
| AMD                                          | 12        | 16.44%  |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.37%   |
| Texas Instruments                            | 1         | 1.37%   |
| Generalplus Technology                       | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 9.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 8.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 8.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 5.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 5.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.49%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 3.49%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.33%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.33%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.33%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.16%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.16%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.16%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.16%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 1.16%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.16%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.16%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.16%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 26.98%  |
| SK hynix            | 12        | 19.05%  |
| Kingston            | 8         | 12.7%   |
| Micron Technology   | 5         | 7.94%   |
| Crucial             | 5         | 7.94%   |
| Unknown             | 3         | 4.76%   |
| Ramaxel Technology  | 2         | 3.17%   |
| Elpida              | 2         | 3.17%   |
| Unknown             | 2         | 3.17%   |
| Unknown (ABCD)      | 1         | 1.59%   |
| Transcend           | 1         | 1.59%   |
| Nanya Technology    | 1         | 1.59%   |
| G.Skill             | 1         | 1.59%   |
| Corsair             | 1         | 1.59%   |
| ASint Technology    | 1         | 1.59%   |
| A-DATA Technology   | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.74%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 2         | 2.74%   |
| Unknown                                                                   | 2         | 2.74%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 1.37%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 1.37%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.37%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s                      | 1         | 1.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.37%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s             | 1         | 1.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 1.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.37%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.37%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.37%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 1         | 1.37%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.37%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.37%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s                     | 1         | 1.37%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 800MT/s                      | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 25        | 44.64%  |
| DDR4    | 19        | 33.93%  |
| DDR2    | 7         | 12.5%   |
| LPDDR4  | 2         | 3.57%   |
| SDRAM   | 1         | 1.79%   |
| LPDDR3  | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 94.64%  |
| Row Of Chips | 3         | 5.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 36.07%  |
| 8192  | 18        | 29.51%  |
| 2048  | 10        | 16.39%  |
| 16384 | 7         | 11.48%  |
| 1024  | 3         | 4.92%   |
| 32768 | 1         | 1.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 26.67%  |
| 3200    | 7         | 11.67%  |
| 2667    | 7         | 11.67%  |
| 2400    | 6         | 10%     |
| 667     | 5         | 8.33%   |
| 1067    | 4         | 6.67%   |
| 1334    | 3         | 5%      |
| 1867    | 2         | 3.33%   |
| 1333    | 2         | 3.33%   |
| 1066    | 2         | 3.33%   |
| 800     | 2         | 3.33%   |
| 3733    | 1         | 1.67%   |
| 2133    | 1         | 1.67%   |
| 2048    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

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
| Chicony Electronics                    | 10        | 23.26%  |
| Sunplus Innovation Technology          | 6         | 13.95%  |
| Realtek Semiconductor                  | 4         | 9.3%    |
| Microdia                               | 4         | 9.3%    |
| Suyin                                  | 3         | 6.98%   |
| Quanta                                 | 3         | 6.98%   |
| Bison Electronics                      | 3         | 6.98%   |
| IMC Networks                           | 2         | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.65%   |
| USB Camera                             | 1         | 2.33%   |
| Syntek                                 | 1         | 2.33%   |
| Silicon Motion                         | 1         | 2.33%   |
| Ricoh                                  | 1         | 2.33%   |
| Lite-On Technology                     | 1         | 2.33%   |
| Alcor Micro                            | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                                               | 3         | 6.98%   |
| Chicony Integrated Camera                                                  | 3         | 6.98%   |
| Realtek USB Camera                                                         | 2         | 4.65%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 4.65%   |
| USB Camera USB Camera                                                      | 1         | 2.33%   |
| Syntek EasyCamera                                                          | 1         | 2.33%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2.33%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 2.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 2.33%   |
| Sunplus Integrated Camera                                                  | 1         | 2.33%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2.33%   |
| Sunplus Asus Webcam                                                        | 1         | 2.33%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 2.33%   |
| Ricoh Integrated Webcam                                                    | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.33%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 2.33%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 2.33%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.33%   |
| Microdia Integrated Webcam                                                 | 1         | 2.33%   |
| Microdia HP Webcam                                                         | 1         | 2.33%   |
| Lite-On Integrated Camera                                                  | 1         | 2.33%   |
| IMC Networks Realtek PC Camera                                             | 1         | 2.33%   |
| IMC Networks 2M Integrated Webcam                                          | 1         | 2.33%   |
| Chicony WebCam                                                             | 1         | 2.33%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2.33%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.33%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.33%   |
| Chicony Integrated IR Camera                                               | 1         | 2.33%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.33%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.33%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.33%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.33%   |
| Bison Integrated Camera                                                    | 1         | 2.33%   |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 60%     |
| Upek                  | 1         | 10%     |
| Synaptics             | 1         | 10%     |
| STMicroelectronics    | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 20%     |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 10%     |
| Validity Sensors Synaptics WBDI                          | 1         | 10%     |
| Validity Sensors Fingerprint scanner                     | 1         | 10%     |
| Upek TCS5B Fingerprint sensor                            | 1         | 10%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                    | 1         | 10%     |
| Elan Fingerprint Sensor                                  | 1         | 10%     |

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
| 1     | 25        | 36.76%  |
| 2     | 17        | 25%     |
| 3     | 12        | 17.65%  |
| 0     | 9         | 13.24%  |
| 4     | 5         | 7.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 38        | 36.89%  |
| Net/wireless             | 21        | 20.39%  |
| Bluetooth                | 16        | 15.53%  |
| Card reader              | 11        | 10.68%  |
| Fingerprint reader       | 9         | 8.74%   |
| Graphics card            | 3         | 2.91%   |
| Firewire controller      | 3         | 2.91%   |
| Network                  | 2         | 1.94%   |

