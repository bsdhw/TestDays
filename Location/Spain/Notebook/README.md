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

Total: 100

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | OMEN Laptop 15-en1xxx       | [0f92b89ffb](https://bsd-hardware.info/?probe=0f92b89ffb) | Sep 09, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Acer          | Aspire A515-56              | [301a7c7b63](https://bsd-hardware.info/?probe=301a7c7b63) | Aug 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS3AX0... | [785b9af1f4](https://bsd-hardware.info/?probe=785b9af1f4) | Jul 13, 2023 |
| HP            | Laptop 15-bs1xx             | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
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
| helloSystem 0.7.0    | 16        | 19.51%  |
| helloSystem 0.8.1    | 6         | 7.32%   |
| helloSystem 0.8.0    | 6         | 7.32%   |
| helloSystem 0.5.0    | 4         | 4.88%   |
| FreeBSD 13.1         | 4         | 4.88%   |
| OpenBSD 7.2          | 3         | 3.66%   |
| helloSystem 0.6.0    | 3         | 3.66%   |
| GhostBSD 20.04.02    | 3         | 3.66%   |
| OpenBSD 7.1          | 2         | 2.44%   |
| OpenBSD 6.8          | 2         | 2.44%   |
| helloSystem 0.8.2    | 2         | 2.44%   |
| helloSystem 0.4.0    | 2         | 2.44%   |
| FuguIta 7.2          | 2         | 2.44%   |
| FreeBSD 13.2         | 2         | 2.44%   |
| OPNsense 23.1.6      | 1         | 1.22%   |
| OPNsense 22.7.10     | 1         | 1.22%   |
| OPNsense 21.7.6      | 1         | 1.22%   |
| OPNsense 21.7.5      | 1         | 1.22%   |
| OpenBSD 7.3          | 1         | 1.22%   |
| OpenBSD 6.9          | 1         | 1.22%   |
| NomadBSD 5806f915    | 1         | 1.22%   |
| NomadBSD 20221130    | 1         | 1.22%   |
| GhostBSD 23.09.06    | 1         | 1.22%   |
| GhostBSD 23.03.17    | 1         | 1.22%   |
| GhostBSD 23.01.13    | 1         | 1.22%   |
| GhostBSD 22.06.18    | 1         | 1.22%   |
| GhostBSD 21.08.27    | 1         | 1.22%   |
| FreeBSD 14.0-CURRENT | 1         | 1.22%   |
| FreeBSD 13.2-p2      | 1         | 1.22%   |
| FreeBSD 13.1-p7      | 1         | 1.22%   |
| FreeBSD 13.1-p5      | 1         | 1.22%   |
| FreeBSD 13.1-p2      | 1         | 1.22%   |
| FreeBSD 13.1-p1      | 1         | 1.22%   |
| FreeBSD 13.0-STABLE  | 1         | 1.22%   |
| FreeBSD 13.0-RC3     | 1         | 1.22%   |
| FreeBSD 13.0-RC1     | 1         | 1.22%   |
| FreeBSD 13.0-BETA4   | 1         | 1.22%   |
| FreeBSD 13.0         | 1         | 1.22%   |
| FreeBSD 12.3         | 1         | 1.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 32        | 44.44%  |
| FreeBSD     | 18        | 25%     |
| GhostBSD    | 8         | 11.11%  |
| OpenBSD     | 7         | 9.72%   |
| OPNsense    | 3         | 4.17%   |
| NomadBSD    | 2         | 2.78%   |
| FuguIta     | 2         | 2.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 68        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 39        | 53.42%  |
| MATE         | 9         | 12.33%  |
| Console      | 8         | 10.96%  |
| XFCE         | 3         | 4.11%   |
| TWM          | 3         | 4.11%   |
| Openbox      | 3         | 4.11%   |
| fvwm         | 3         | 4.11%   |
| KDE5         | 2         | 2.74%   |
| i3           | 2         | 2.74%   |
| GNOME        | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 59        | 85.51%  |
| Console | 8         | 11.59%  |
| Wayland | 2         | 2.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 35        | 48.61%  |
| Console | 19        | 26.39%  |
| LightDM | 9         | 12.5%   |
| SDDM    | 4         | 5.56%   |
| GDM     | 3         | 4.17%   |
| XDM     | 1         | 1.39%   |
| Ly      | 1         | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 24        | 32.88%  |
| es_ES   | 19        | 26.03%  |
| C       | 12        | 16.44%  |
| Unknown | 12        | 16.44%  |
| es      | 3         | 4.11%   |
| zh_CN   | 1         | 1.37%   |
| ru_RU   | 1         | 1.37%   |
| de_DE   | 1         | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 57        | 83.82%  |
| BIOS | 11        | 16.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 39        | 54.93%  |
| Cd9660 | 16        | 22.54%  |
| Ffs    | 9         | 12.68%  |
| Ufs    | 7         | 9.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 59        | 86.76%  |
| MBR  | 9         | 13.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 16        | 23.53%  |
| Lenovo              | 14        | 20.59%  |
| Dell                | 7         | 10.29%  |
| ASUSTek Computer    | 7         | 10.29%  |
| Apple               | 4         | 5.88%   |
| Acer                | 4         | 5.88%   |
| SLIMBOOK            | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| TWINHEAD            | 1         | 1.47%   |
| TUXEDO              | 1         | 1.47%   |
| Toshiba             | 1         | 1.47%   |
| Sony                | 1         | 1.47%   |
| Samsung Electronics | 1         | 1.47%   |
| ReachingTech        | 1         | 1.47%   |
| Razer               | 1         | 1.47%   |
| Packard Bell        | 1         | 1.47%   |
| MSI                 | 1         | 1.47%   |
| Chuwi               | 1         | 1.47%   |
| AZW                 | 1         | 1.47%   |
| Alienware           | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Latitude 7390                   | 3         | 4.41%   |
| Unknown                              | 3         | 4.41%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 2         | 2.94%   |
| ASUS K55VD                           | 2         | 2.94%   |
| TWINHEAD U12CT                       | 1         | 1.47%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.47%   |
| Toshiba Satellite A300               | 1         | 1.47%   |
| Sony SVE1511C5E                      | 1         | 1.47%   |
| SLIMBOOK PROX-AMD5                   | 1         | 1.47%   |
| SLIMBOOK ESSENTIAL-15-11             | 1         | 1.47%   |
| Samsung 530U3C/530U4C/532U3C         | 1         | 1.47%   |
| ReachingTech DreamQuest Pro 2022     | 1         | 1.47%   |
| Razer Blade Stealth                  | 1         | 1.47%   |
| Packard Bell DOT S                   | 1         | 1.47%   |
| MSI GE75 Raider 10SGS                | 1         | 1.47%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.47%   |
| Lenovo ThinkPad X270 20HMS06Q1D      | 1         | 1.47%   |
| Lenovo ThinkPad X200 745969G         | 1         | 1.47%   |
| Lenovo ThinkPad T61 765912G          | 1         | 1.47%   |
| Lenovo ThinkPad T470s 20HGS3AX02     | 1         | 1.47%   |
| Lenovo ThinkPad T440p 20AWS1CH00     | 1         | 1.47%   |
| Lenovo ThinkPad T440p 20AW007QMS     | 1         | 1.47%   |
| Lenovo ThinkPad L590 20Q7000YSP      | 1         | 1.47%   |
| Lenovo ThinkPad L450 20DSS1S402      | 1         | 1.47%   |
| Lenovo ThinkPad L440 20ASS0FP00      | 1         | 1.47%   |
| Lenovo ThinkPad E495 20NE000BSP      | 1         | 1.47%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW | 1         | 1.47%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 1         | 1.47%   |
| Lenovo G50-80 80E5                   | 1         | 1.47%   |
| HP ProBook 4540s                     | 1         | 1.47%   |
| HP ProBook 4340s                     | 1         | 1.47%   |
| HP ProBook 430 G7                    | 1         | 1.47%   |
| HP Pavilion dv6                      | 1         | 1.47%   |
| HP Pavilion dv4                      | 1         | 1.47%   |
| HP Pavilion dv3500                   | 1         | 1.47%   |
| HP OMEN Laptop 15-en1xxx             | 1         | 1.47%   |
| HP OMEN by Laptop                    | 1         | 1.47%   |
| HP OMEN by HP Laptop 17-cb1xxx       | 1         | 1.47%   |
| HP Laptop 15-db0xxx                  | 1         | 1.47%   |
| HP Laptop 15-bs1xx                   | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 11        | 16.18%  |
| HP Pavilion              | 5         | 7.35%   |
| Dell Latitude            | 4         | 5.88%   |
| HP ProBook               | 3         | 4.41%   |
| HP OMEN                  | 3         | 4.41%   |
| Acer Aspire              | 3         | 4.41%   |
| Unknown                  | 3         | 4.41%   |
| HP Laptop                | 2         | 2.94%   |
| ASUS K55VD               | 2         | 2.94%   |
| Apple MacBook5           | 2         | 2.94%   |
| TWINHEAD U12CT           | 1         | 1.47%   |
| TUXEDO Aura              | 1         | 1.47%   |
| Toshiba Satellite        | 1         | 1.47%   |
| Sony SVE1511C5E          | 1         | 1.47%   |
| SLIMBOOK PROX-AMD5       | 1         | 1.47%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 1.47%   |
| Samsung 530U3C           | 1         | 1.47%   |
| ReachingTech DreamQuest  | 1         | 1.47%   |
| Razer Blade              | 1         | 1.47%   |
| Packard Bell DOT         | 1         | 1.47%   |
| MSI GE75                 | 1         | 1.47%   |
| Lenovo Yoga              | 1         | 1.47%   |
| Lenovo IdeaPad           | 1         | 1.47%   |
| Lenovo G50-80            | 1         | 1.47%   |
| HP EliteBook             | 1         | 1.47%   |
| HP Compaq                | 1         | 1.47%   |
| HP 250                   | 1         | 1.47%   |
| Dell Studio              | 1         | 1.47%   |
| Dell Precision           | 1         | 1.47%   |
| Dell Inspiron            | 1         | 1.47%   |
| AZW BT3                  | 1         | 1.47%   |
| ASUS X556UJ              | 1         | 1.47%   |
| ASUS U33Jc               | 1         | 1.47%   |
| ASUS TUF                 | 1         | 1.47%   |
| ASUS 1215B               | 1         | 1.47%   |
| ASUS 1201N               | 1         | 1.47%   |
| Apple MacBook6           | 1         | 1.47%   |
| Apple MacBook4           | 1         | 1.47%   |
| Alienware m15            | 1         | 1.47%   |
| Acer Extensa             | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 11        | 16.18%  |
| 2019 | 7         | 10.29%  |
| 2022 | 6         | 8.82%   |
| 2012 | 6         | 8.82%   |
| 2009 | 6         | 8.82%   |
| 2018 | 4         | 5.88%   |
| 2011 | 4         | 5.88%   |
| 2008 | 4         | 5.88%   |
| 2017 | 3         | 4.41%   |
| 2015 | 3         | 4.41%   |
| 2014 | 3         | 4.41%   |
| 2010 | 3         | 4.41%   |
| 2021 | 2         | 2.94%   |
| 2016 | 2         | 2.94%   |
| 2013 | 2         | 2.94%   |
| 2023 | 1         | 1.47%   |
| 2007 | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 68        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 68        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 28        | 40%     |
| 4.01-8.0    | 15        | 21.43%  |
| 16.01-24.0  | 15        | 21.43%  |
| 32.01-64.0  | 6         | 8.57%   |
| 3.01-4.0    | 2         | 2.86%   |
| 2.01-3.0    | 2         | 2.86%   |
| 24.01-32.0  | 1         | 1.43%   |
| 64.01-256.0 | 1         | 1.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 37        | 52.11%  |
| 0.51-1.0 | 23        | 32.39%  |
| 1.01-2.0 | 8         | 11.27%  |
| 2.01-3.0 | 3         | 4.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 71.01%  |
| 2      | 15        | 21.74%  |
| 3      | 2         | 2.9%    |
| 0      | 2         | 2.9%    |
| 4      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 50        | 72.46%  |
| Yes       | 19        | 27.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 91.18%  |
| No        | 6         | 8.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 97.06%  |
| No        | 2         | 2.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 80.88%  |
| No        | 13        | 19.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 68        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 12        | 15.58%  |
| Barcelona                     | 8         | 10.39%  |
| Valencia                      | 4         | 5.19%   |
| Terrassa                      | 3         | 3.9%    |
| Navalcarnero                  | 3         | 3.9%    |
| Tarragona                     | 2         | 2.6%    |
| Paterna                       | 2         | 2.6%    |
| GibraleГіn                  | 2         | 2.6%    |
| Alcobendas                    | 2         | 2.6%    |
| Zarautz                       | 1         | 1.3%    |
| Zaragoza                      | 1         | 1.3%    |
| Vitoria-Gasteiz               | 1         | 1.3%    |
| Villapresente                 | 1         | 1.3%    |
| Urnieta                       | 1         | 1.3%    |
| Tudela de Duero               | 1         | 1.3%    |
| Seville                       | 1         | 1.3%    |
| Sedavi                        | 1         | 1.3%    |
| Santa Cruz de Tenerife        | 1         | 1.3%    |
| Sanlucar la Mayor             | 1         | 1.3%    |
| San Vicent del Raspeig        | 1         | 1.3%    |
| San SebastiÃ¡n de los Reyes | 1         | 1.3%    |
| Rubí                         | 1         | 1.3%    |
| Redondela                     | 1         | 1.3%    |
| Padul                         | 1         | 1.3%    |
| Ourense                       | 1         | 1.3%    |
| Málaga                       | 1         | 1.3%    |
| LogroГ±o                    | 1         | 1.3%    |
| LogroÃ±o                    | 1         | 1.3%    |
| Laguna de Duero               | 1         | 1.3%    |
| La Pobla de Farnals           | 1         | 1.3%    |
| Ibiza Town                    | 1         | 1.3%    |
| Godella                       | 1         | 1.3%    |
| Fuenterrabia                  | 1         | 1.3%    |
| Esparragosa de Lares          | 1         | 1.3%    |
| Elche                         | 1         | 1.3%    |
| Coria del RÃ­o              | 1         | 1.3%    |
| Córdoba                      | 1         | 1.3%    |
| Colombres                     | 1         | 1.3%    |
| Cho                           | 1         | 1.3%    |
| Carcer                        | 1         | 1.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 15        | 29     | 17.65%  |
| WDC                                    | 8         | 10     | 9.41%   |
| NVMe                                   | 6         | 9      | 7.06%   |
| Kingston                               | 6         | 7      | 7.06%   |
| Crucial                                | 6         | 6      | 7.06%   |
| Toshiba                                | 5         | 7      | 5.88%   |
| Hitachi                                | 5         | 5      | 5.88%   |
| Seagate                                | 4         | 4      | 4.71%   |
| SanDisk                                | 4         | 4      | 4.71%   |
| Intel                                  | 3         | 3      | 3.53%   |
| HGST                                   | 3         | 3      | 3.53%   |
| Product:              USB Flash Memory | 2         | 2      | 2.35%   |
| Micron Technology                      | 2         | 2      | 2.35%   |
| Fujitsu                                | 2         | 2      | 2.35%   |
| XrayDisk                               | 1         | 1      | 1.18%   |
| Union Memory                           | 1         | 1      | 1.18%   |
| Transcend                              | 1         | 1      | 1.18%   |
| TCSUNBOW                               | 1         | 1      | 1.18%   |
| SK hynix                               | 1         | 1      | 1.18%   |
| PNY                                    | 1         | 1      | 1.18%   |
| OCZ                                    | 1         | 1      | 1.18%   |
| Netac                                  | 1         | 1      | 1.18%   |
| LITEONIT                               | 1         | 1      | 1.18%   |
| Kston                                  | 1         | 2      | 1.18%   |
| KIOXIA                                 | 1         | 1      | 1.18%   |
| KingSpec                               | 1         | 1      | 1.18%   |
| Intenso                                | 1         | 1      | 1.18%   |
| China                                  | 1         | 1      | 1.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 2.22%   |
| NVMe Samsung SSD 980 500GB                                   | 2         | 2.22%   |
| Kingston SA400S37240G 240GB                                  | 2         | 2.22%   |
| Crucial CT480BX500SSD1 480GB                                 | 2         | 2.22%   |
| XrayDisk SSD 240GB                                           | 1         | 1.11%   |
| WDC WDS100T2B0C-00PXH0 1TB                                   | 1         | 1.11%   |
| WDC WD5000LPCX-21VHAT0 500GB                                 | 1         | 1.11%   |
| WDC WD2500BEVT-35A23T0 250GB                                 | 1         | 1.11%   |
| WDC WD1200BEVS-22UST0 120GB                                  | 1         | 1.11%   |
| WDC WD10JPCX-24UE4T0 1TB                                     | 1         | 1.11%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 1         | 1.11%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                           | 1         | 1.11%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB                           | 1         | 1.11%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                         | 1         | 1.11%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB              | 1         | 1.11%   |
| Transcend TS120GMTS420S 120GB                                | 1         | 1.11%   |
| Toshiba MQ01ABD100 1TB                                       | 1         | 1.11%   |
| Toshiba MK5065GSXF 500GB                                     | 1         | 1.11%   |
| Toshiba MK1229GSG 120GB                                      | 1         | 1.11%   |
| Toshiba MK1059GSM 1TB                                        | 1         | 1.11%   |
| Toshiba KXG60ZNV512G NVMe 512GB                              | 1         | 1.11%   |
| TCSUNBOW X3 480GB                                            | 1         | 1.11%   |
| SK hynix HFM512GDHTNG-8710B 512GB                            | 1         | 1.11%   |
| Seagate ST9500325AS 500GB                                    | 1         | 1.11%   |
| Seagate ST500LM021-1KJ152 500GB                              | 1         | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB                               | 1         | 1.11%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 1         | 1.11%   |
| SanDisk SSD PLUS 240GB                                       | 1         | 1.11%   |
| SanDisk SSD i100 24GB                                        | 1         | 1.11%   |
| SanDisk SDSSDP128G 128GB                                     | 1         | 1.11%   |
| SanDisk SD9SN8W-256G-1006 256GB                              | 1         | 1.11%   |
| Samsung SSD 970 EVO Plus 2TB                                 | 1         | 1.11%   |
| Samsung SSD 970 EVO 250GB                                    | 1         | 1.11%   |
| Samsung SSD 870 QVO 8TB                                      | 1         | 1.11%   |
| Samsung SSD 870 EVO 1TB                                      | 1         | 1.11%   |
| Samsung SSD 860 PRO 512GB                                    | 1         | 1.11%   |
| Samsung SSD 860 EVO 500GB                                    | 1         | 1.11%   |
| Samsung SSD 850 EVO 500GB                                    | 1         | 1.11%   |
| Samsung SSD 850 EVO 250GB                                    | 1         | 1.11%   |
| Samsung SSD 840 PRO Series 128GB                             | 1         | 1.11%   |

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
| Samsung Electronics | 8         | 14     | 22.22%  |
| Kingston            | 5         | 6      | 13.89%  |
| SanDisk             | 4         | 4      | 11.11%  |
| Crucial             | 4         | 4      | 11.11%  |
| NVMe                | 2         | 2      | 5.56%   |
| Intel               | 2         | 2      | 5.56%   |
| XrayDisk            | 1         | 1      | 2.78%   |
| Transcend           | 1         | 1      | 2.78%   |
| TCSUNBOW            | 1         | 1      | 2.78%   |
| PNY                 | 1         | 1      | 2.78%   |
| OCZ                 | 1         | 1      | 2.78%   |
| Netac               | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| LITEONIT            | 1         | 1      | 2.78%   |
| Kston               | 1         | 2      | 2.78%   |
| KingSpec            | 1         | 1      | 2.78%   |
| China               | 1         | 1      | 2.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 34        | 44     | 41.46%  |
| HDD  | 29        | 34     | 35.37%  |
| NVMe | 19        | 30     | 23.17%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 78     | 73.61%  |
| NVMe | 19        | 30     | 26.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 60     | 78.95%  |
| 0.51-1.0   | 10        | 14     | 17.54%  |
| 1.01-2.0   | 1         | 3      | 1.75%   |
| 4.01-10.0  | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 27        | 36.99%  |
| 101-250    | 23        | 31.51%  |
| 251-500    | 14        | 19.18%  |
| 501-1000   | 4         | 5.48%   |
| 1001-2000  | 2         | 2.74%   |
| 51-100     | 2         | 2.74%   |
| 21-50      | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 62        | 88.57%  |
| 21-50    | 3         | 4.29%   |
| 51-100   | 3         | 4.29%   |
| 251-500  | 1         | 1.43%   |
| 501-1000 | 1         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-35A23T0 250GB                    | 1         | 1      | 7.14%   |
| Toshiba MK1229GSG 120GB                         | 1         | 1      | 7.14%   |
| Toshiba MK1059GSM 1TB                           | 1         | 1      | 7.14%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 7.14%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 7.14%   |
| OCZ AGILITY3 120GB                              | 1         | 1      | 7.14%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 1      | 7.14%   |
| Hitachi HTS543232L9SA00 320GB                   | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9A300 250GB                   | 1         | 1      | 7.14%   |
| Hitachi HTS542516K9SA00 160GB                   | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB                      | 1         | 1      | 7.14%   |
| Fujitsu MHZ2250BH G2 250GB                      | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 28.57%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Seagate             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| OCZ                 | 1         | 1      | 7.14%   |
| Micron Technology   | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

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
| HDD  | 12        | 12     | 85.71%  |
| SSD  | 2         | 2      | 14.29%  |

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
| Works    | 54        | 83     | 72.97%  |
| Malfunc  | 14        | 14     | 18.92%  |
| Detected | 6         | 11     | 8.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 44        | 55.7%   |
| Samsung Electronics         | 8         | 10.13%  |
| AMD                         | 6         | 7.59%   |
| Nvidia                      | 5         | 6.33%   |
| Sandisk                     | 4         | 5.06%   |
| SK hynix                    | 2         | 2.53%   |
| Micron/Crucial Technology   | 2         | 2.53%   |
| Kingston Technology Company | 2         | 2.53%   |
| Union Memory (Shenzhen)     | 1         | 1.27%   |
| Toshiba                     | 1         | 1.27%   |
| Silicon Motion              | 1         | 1.27%   |
| Phison Electronics          | 1         | 1.27%   |
| Micron Technology           | 1         | 1.27%   |
| KIOXIA                      | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 6.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 5.68%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.41%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.41%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.27%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 2.27%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.27%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.14%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 1.14%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 1.14%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.14%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.14%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 1.14%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 1.14%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.14%   |
| Kingston Company unknown                                                       | 1         | 1.14%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.14%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.14%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.14%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1         | 1.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.14%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 61.45%  |
| NVMe | 22        | 26.51%  |
| IDE  | 6         | 7.23%   |
| RAID | 4         | 4.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 83.82%  |
| AMD    | 11        | 16.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz     | 2         | 2.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 2         | 2.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 2         | 2.94%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 2         | 2.94%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz   | 2         | 2.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics | 2         | 2.94%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.47%   |
| Intel Pentium CPU B970 @ 2.30GHz       | 1         | 1.47%   |
| Intel CPU Version                      | 1         | 1.47%   |
| Intel Core i9-10980HK CPU @ 2.40GHz    | 1         | 1.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 1.47%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 1         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 1         | 1.47%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.47%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.47%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz     | 1         | 1.47%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz     | 1         | 1.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz      | 1         | 1.47%   |
| Intel Core i7-3610QM CPU @ 2.30GHz     | 1         | 1.47%   |
| Intel Core i7-10875H CPU @ 2.30GHz     | 1         | 1.47%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.47%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 1         | 1.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.47%   |
| Intel Core i5-2537M CPU @ 1.40GHz      | 1         | 1.47%   |
| Intel Core i5-2430M CPU @ 2.40GHz      | 1         | 1.47%   |
| Intel Core i5 CPU U 560 @ 1.33GHz      | 1         | 1.47%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.47%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1         | 1.47%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 1         | 1.47%   |
| Intel Core i3 CPU M 370 @ 2.40GH       | 1         | 1.47%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz   | 1         | 1.47%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz   | 1         | 1.47%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz   | 1         | 1.47%   |
| Intel Core 2 Duo CPU P9500 @ 2.53GHz   | 1         | 1.47%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 16        | 23.53%  |
| Intel Core i7      | 14        | 20.59%  |
| Intel Core 2 Duo   | 10        | 14.71%  |
| AMD Ryzen 7        | 6         | 8.82%   |
| Other              | 4         | 5.88%   |
| Intel Core i3      | 4         | 5.88%   |
| Intel Celeron      | 3         | 4.41%   |
| Intel Atom         | 3         | 4.41%   |
| AMD Ryzen 5        | 2         | 2.94%   |
| Intel Pentium Dual | 1         | 1.47%   |
| Intel Pentium      | 1         | 1.47%   |
| Intel Core i9      | 1         | 1.47%   |
| AMD Sempron        | 1         | 1.47%   |
| AMD E              | 1         | 1.47%   |
| AMD A4             | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 27        | 39.71%  |
| 4       | 19        | 27.94%  |
| Unknown | 10        | 14.71%  |
| 8       | 5         | 7.35%   |
| 16      | 3         | 4.41%   |
| 12      | 2         | 2.94%   |
| 6       | 1         | 1.47%   |
| 1       | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 63        | 92.65%  |
| 2       | 4         | 5.88%   |
| Unknown | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 38        | 55.88%  |
| 1       | 20        | 29.41%  |
| Unknown | 10        | 14.71%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 11        | 16.18%  |
| Penryn          | 9         | 13.24%  |
| Haswell         | 6         | 8.82%   |
| IvyBridge       | 5         | 7.35%   |
| Skylake         | 4         | 5.88%   |
| Zen 2           | 3         | 4.41%   |
| TigerLake       | 3         | 4.41%   |
| SandyBridge     | 3         | 4.41%   |
| Core            | 3         | 4.41%   |
| CometLake       | 3         | 4.41%   |
| Zen+            | 2         | 2.94%   |
| Zen 3           | 2         | 2.94%   |
| Westmere        | 2         | 2.94%   |
| Silvermont      | 2         | 2.94%   |
| Broadwell       | 2         | 2.94%   |
| Bonnell         | 2         | 2.94%   |
| Unknown         | 2         | 2.94%   |
| K8 & K10 hybrid | 1         | 1.47%   |
| Goldmont plus   | 1         | 1.47%   |
| Excavator       | 1         | 1.47%   |
| Bobcat          | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 47        | 56.63%  |
| Nvidia | 20        | 24.1%   |
| AMD    | 16        | 19.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.81%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.65%   |
| Intel HD Graphics 620                                                                    | 4         | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 3.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.49%   |
| AMD Renoir                                                                               | 3         | 3.49%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 2.33%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.33%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 2.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 2.33%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.33%   |
| Intel HD Graphics 530                                                                    | 2         | 2.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 2.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia TU117M                                                                            | 1         | 1.16%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.16%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.16%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.16%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.16%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.16%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.16%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.16%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.16%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.16%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.16%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 1.16%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.16%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 46.38%  |
| 1 x AMD        | 9         | 13.04%  |
| Intel + Nvidia | 8         | 11.59%  |
| 1 x Nvidia     | 7         | 10.14%  |
| 2 x Intel      | 5         | 7.25%   |
| AMD + Nvidia   | 4         | 5.8%    |
| Intel + AMD    | 3         | 4.35%   |
| 2 x Nvidia     | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 61        | 87.14%  |
| Proprietary | 7         | 10%     |
| Unknown     | 2         | 2.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 85.92%  |
| 0.01-0.5   | 7         | 9.86%   |
| 7.01-8.0   | 1         | 1.41%   |
| 5.01-6.0   | 1         | 1.41%   |
| 2.01-3.0   | 1         | 1.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 19.61%  |
| Chimei Innolux          | 6         | 11.76%  |
| BOE                     | 6         | 11.76%  |
| LG Display              | 5         | 9.8%    |
| Chi Mei Optoelectronics | 4         | 7.84%   |
| Samsung Electronics     | 3         | 5.88%   |
| Lenovo                  | 3         | 5.88%   |
| BenQ                    | 3         | 5.88%   |
| Apple                   | 3         | 5.88%   |
| Sharp                   | 1         | 1.96%   |
| PANDA                   | 1         | 1.96%   |
| Mi                      | 1         | 1.96%   |
| LGD                     | 1         | 1.96%   |
| LG Philips              | 1         | 1.96%   |
| Hewlett-Packard         | 1         | 1.96%   |
| Fujitsu Siemens         | 1         | 1.96%   |
| AOC                     | 1         | 1.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch           | 3         | 5.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 2         | 3.85%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 3.85%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch                  | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch     | 1         | 1.92%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.92%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.92%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                         | 1         | 1.92%   |
| LGD LCD Monitor 5760x1080                                                | 1         | 1.92%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.92%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 1.92%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.92%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.92%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch               | 1         | 1.92%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 340x190mm 15.3-inch         | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.92%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 340x190mm 15.3-inch | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 300x190mm 14.0-inch | 1         | 1.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 220x120mm 9.9-inch  | 1         | 1.92%   |
| BOE LCD Monitor BOE0960 1366x768 340x190mm 15.3-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 1.92%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 1.92%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 1.92%   |
| BenQ V2400Eco BNQ7D02 1920x1080 530x300mm 24.0-inch                      | 1         | 1.92%   |
| BenQ LCD Monitor GL2450H                                                 | 1         | 1.92%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 340x190mm 15.3-inch           | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 1         | 1.92%   |
| AU Optronics LCD Monitor AUO333C 1366x768 310x170mm 13.9-inch            | 1         | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 19        | 38.78%  |
| 1366x768 (WXGA)  | 15        | 30.61%  |
| 1280x800 (WXGA)  | 8         | 16.33%  |
| 1600x900 (HD+)   | 2         | 4.08%   |
| 5760x1080        | 1         | 2.04%   |
| 3840x2160 (4K)   | 1         | 2.04%   |
| 1280x1024 (SXGA) | 1         | 2.04%   |
| 1024x600         | 1         | 2.04%   |
| Unknown          | 1         | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 22        | 43.14%  |
| 13      | 15        | 29.41%  |
| 24      | 4         | 7.84%   |
| 12      | 3         | 5.88%   |
| 19      | 2         | 3.92%   |
| 14      | 2         | 3.92%   |
| 27      | 1         | 1.96%   |
| 9       | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 28        | 54.9%   |
| 201-300     | 15        | 29.41%  |
| 501-600     | 5         | 9.8%    |
| 401-500     | 1         | 1.96%   |
| 351-400     | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

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
| 91-100         | 20        | 39.22%  |
| 81-90          | 11        | 21.57%  |
| 71-80          | 6         | 11.76%  |
| 201-250        | 4         | 7.84%   |
| 61-70          | 3         | 5.88%   |
| 151-200        | 2         | 3.92%   |
| 101-110        | 2         | 3.92%   |
| 41-50          | 1         | 1.96%   |
| 301-350        | 1         | 1.96%   |
| Unknown        | 1         | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 19        | 37.25%  |
| 121-160       | 16        | 31.37%  |
| 51-100        | 9         | 17.65%  |
| 161-240       | 5         | 9.8%    |
| More than 240 | 1         | 1.96%   |
| Unknown       | 1         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 49        | 68.06%  |
| 0     | 18        | 25%     |
| 2     | 5         | 6.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 39        | 32.77%  |
| Realtek Semiconductor             | 37        | 31.09%  |
| Qualcomm Atheros                  | 12        | 10.08%  |
| Broadcom                          | 11        | 9.24%   |
| Nvidia                            | 4         | 3.36%   |
| TP-Link                           | 2         | 1.68%   |
| Sierra Wireless                   | 2         | 1.68%   |
| Ralink Technology                 | 2         | 1.68%   |
| Ralink                            | 2         | 1.68%   |
| Marvell Technology Group          | 2         | 1.68%   |
| Xiaomi                            | 1         | 0.84%   |
| MediaTek                          | 1         | 0.84%   |
| IMC Networks                      | 1         | 0.84%   |
| Huawei Technologies               | 1         | 0.84%   |
| Ericsson Business Mobile Networks | 1         | 0.84%   |
| D-Link System                     | 1         | 0.84%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 20.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.5%    |
| Intel Wireless 8265 / 8275                                        | 5         | 3.5%    |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 3.5%    |
| Nvidia MCP79 Ethernet                                             | 4         | 2.8%    |
| Intel Wireless 7265                                               | 4         | 2.8%    |
| Intel Wireless 7260                                               | 4         | 2.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 2.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 2.1%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.1%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 2.1%    |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.4%    |
| Intel Wireless 3160                                               | 2         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.4%    |
| Intel Centrino Advanced-N 6235                                    | 2         | 1.4%    |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.7%    |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 38        | 50%     |
| Broadcom              | 10        | 13.16%  |
| Realtek Semiconductor | 9         | 11.84%  |
| Qualcomm Atheros      | 8         | 10.53%  |
| TP-Link               | 2         | 2.63%   |
| Sierra Wireless       | 2         | 2.63%   |
| Ralink Technology     | 2         | 2.63%   |
| Ralink                | 2         | 2.63%   |
| MediaTek              | 1         | 1.32%   |
| IMC Networks          | 1         | 1.32%   |
| D-Link System         | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 5         | 6.41%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 6.41%   |
| Intel Wireless 7265                                            | 4         | 5.13%   |
| Intel Wireless 7260                                            | 4         | 5.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 3.85%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 3.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.85%   |
| Sierra Wireless EM7345 4G LTE                                  | 2         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 2.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 2.56%   |
| Intel Wireless 3160                                            | 2         | 2.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.56%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 2.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.28%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.28%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1.28%   |
| Realtek Realtek Bluetooth 4.2 Adapter                          | 1         | 1.28%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.28%   |
| Intel Wireless-AC 9260                                         | 1         | 1.28%   |
| Intel Wireless 8260                                            | 1         | 1.28%   |
| Intel Wireless 3165                                            | 1         | 1.28%   |
| Intel WiFi Link 5100                                           | 1         | 1.28%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1.28%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.28%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 1         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 35        | 55.56%  |
| Intel                    | 16        | 25.4%   |
| Qualcomm Atheros         | 4         | 6.35%   |
| Nvidia                   | 4         | 6.35%   |
| Marvell Technology Group | 2         | 3.17%   |
| Xiaomi                   | 1         | 1.59%   |
| Broadcom                 | 1         | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 47.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 7.94%   |
| Nvidia MCP79 Ethernet                                             | 4         | 6.35%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.76%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.59%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.59%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.59%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.59%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 50.77%  |
| Ethernet | 62        | 47.69%  |
| Modem    | 2         | 1.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 39        | 50%     |
| WiFi     | 38        | 48.72%  |
| Modem    | 1         | 1.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 85.29%  |
| 1     | 8         | 11.76%  |
| 6     | 1         | 1.47%   |
| 3     | 1         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 97.06%  |
| Yes  | 2         | 2.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 55.36%  |
| Realtek Semiconductor           | 5         | 8.93%   |
| Apple                           | 4         | 7.14%   |
| Hewlett-Packard                 | 3         | 5.36%   |
| Broadcom                        | 3         | 5.36%   |
| Ralink                          | 2         | 3.57%   |
| IMC Networks                    | 2         | 3.57%   |
| Foxconn / Hon Hai               | 2         | 3.57%   |
| Cambridge Silicon Radio         | 2         | 3.57%   |
| Qualcomm Atheros Communications | 1         | 1.79%   |
| ASUSTek Computer                | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 29.82%  |
| Intel AX201 Bluetooth                                       | 5         | 8.77%   |
| Intel AX200 Bluetooth                                       | 5         | 8.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 5.26%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 3.51%   |
| Ralink RT3290 Bluetooth                                     | 2         | 3.51%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.51%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 3.51%   |
| Apple Bluetooth Host Controller                             | 2         | 3.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.75%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.75%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.75%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.75%   |
| IMC Networks Bluetooth module                               | 1         | 1.75%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.75%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 51        | 62.96%  |
| Nvidia                                       | 13        | 16.05%  |
| AMD                                          | 13        | 16.05%  |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.23%   |
| Texas Instruments                            | 1         | 1.23%   |
| Generalplus Technology                       | 1         | 1.23%   |
| C-Media Electronics                          | 1         | 1.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 10.53%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 8.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 7.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 6.32%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 2.11%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 2.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.11%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 2.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.11%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.05%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 1.05%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.05%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.05%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.05%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 1.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.05%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.05%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 1.05%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.05%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.05%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 27.14%  |
| SK hynix            | 13        | 18.57%  |
| Micron Technology   | 8         | 11.43%  |
| Kingston            | 8         | 11.43%  |
| Crucial             | 5         | 7.14%   |
| Unknown             | 3         | 4.29%   |
| Ramaxel Technology  | 2         | 2.86%   |
| Elpida              | 2         | 2.86%   |
| A-DATA Technology   | 2         | 2.86%   |
| Unknown             | 2         | 2.86%   |
| Unknown (ABCD)      | 1         | 1.43%   |
| Transcend           | 1         | 1.43%   |
| Nanya Technology    | 1         | 1.43%   |
| G.Skill             | 1         | 1.43%   |
| Corsair             | 1         | 1.43%   |
| ASint Technology    | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 2.5%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 2.5%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 2         | 2.5%    |
| Unknown                                                                   | 2         | 2.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 1.25%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 1         | 1.25%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.25%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s                      | 1         | 1.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.25%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s             | 1         | 1.25%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 1.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.25%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.25%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.25%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 1.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.25%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.25%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.25%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                    | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 26        | 41.94%  |
| DDR4    | 23        | 37.1%   |
| DDR2    | 8         | 12.9%   |
| LPDDR4  | 2         | 3.23%   |
| SDRAM   | 1         | 1.61%   |
| LPDDR3  | 1         | 1.61%   |
| Unknown | 1         | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 95.16%  |
| Row Of Chips | 3         | 4.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 34.33%  |
| 4096  | 23        | 34.33%  |
| 2048  | 10        | 14.93%  |
| 16384 | 7         | 10.45%  |
| 1024  | 3         | 4.48%   |
| 32768 | 1         | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 25.76%  |
| 3200    | 9         | 13.64%  |
| 2400    | 8         | 12.12%  |
| 2667    | 7         | 10.61%  |
| 667     | 6         | 9.09%   |
| 1067    | 4         | 6.06%   |
| 1334    | 3         | 4.55%   |
| 1867    | 2         | 3.03%   |
| 1333    | 2         | 3.03%   |
| 1066    | 2         | 3.03%   |
| 800     | 2         | 3.03%   |
| 3733    | 1         | 1.52%   |
| 2133    | 1         | 1.52%   |
| 2048    | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

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
| Chicony Electronics                    | 11        | 22.92%  |
| Sunplus Innovation Technology          | 6         | 12.5%   |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Quanta                                 | 4         | 8.33%   |
| Microdia                               | 4         | 8.33%   |
| Bison Electronics                      | 4         | 8.33%   |
| Suyin                                  | 3         | 6.25%   |
| IMC Networks                           | 2         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.17%   |
| USB Camera                             | 1         | 2.08%   |
| Syntek                                 | 1         | 2.08%   |
| Silicon Motion                         | 1         | 2.08%   |
| Ricoh                                  | 1         | 2.08%   |
| Luxvisions Innotech Limited            | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |
| Importek                               | 1         | 2.08%   |
| Alcor Micro                            | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 8.33%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 6.25%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 6.25%   |
| Realtek USB Camera                                                         | 2         | 4.17%   |
| USB Camera USB Camera                                                      | 1         | 2.08%   |
| Syntek EasyCamera                                                          | 1         | 2.08%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2.08%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 2.08%   |
| Sunplus Integrated Camera                                                  | 1         | 2.08%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2.08%   |
| Sunplus Asus Webcam                                                        | 1         | 2.08%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 2.08%   |
| Ricoh Integrated Webcam                                                    | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 2.08%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 2.08%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 2.08%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 2.08%   |
| Microdia Integrated Webcam                                                 | 1         | 2.08%   |
| Microdia HP Webcam                                                         | 1         | 2.08%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 2.08%   |
| Lite-On Integrated Camera                                                  | 1         | 2.08%   |
| Importek HP Webcam                                                         | 1         | 2.08%   |
| IMC Networks Realtek PC Camera                                             | 1         | 2.08%   |
| IMC Networks 2M Integrated Webcam                                          | 1         | 2.08%   |
| Chicony WebCam                                                             | 1         | 2.08%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2.08%   |
| Chicony USB 2.0 Camera                                                     | 1         | 2.08%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 2.08%   |
| Chicony Integrated IR Camera                                               | 1         | 2.08%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2.08%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2.08%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 2.08%   |
| Bison SunplusIT INC. Integrated Camera                                     | 1         | 2.08%   |
| Bison Lenovo EasyCamera                                                    | 1         | 2.08%   |
| Bison Integrated Camera                                                    | 1         | 2.08%   |
| Alcor Micro Asus Integrated Webcam                                         | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 66.67%  |
| Upek                  | 1         | 8.33%   |
| Synaptics             | 1         | 8.33%   |
| STMicroelectronics    | 1         | 8.33%   |
| Elan Microelectronics | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 16.67%  |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 16.67%  |
| Validity Sensors Synaptics WBDI                          | 1         | 8.33%   |
| Validity Sensors Fingerprint scanner                     | 1         | 8.33%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 8.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 8.33%   |
| Elan Fingerprint Sensor                                  | 1         | 8.33%   |

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
| 1     | 28        | 37.84%  |
| 2     | 18        | 24.32%  |
| 3     | 14        | 18.92%  |
| 0     | 9         | 12.16%  |
| 4     | 5         | 6.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 42        | 37.17%  |
| Net/wireless             | 21        | 18.58%  |
| Bluetooth                | 19        | 16.81%  |
| Card reader              | 12        | 10.62%  |
| Fingerprint reader       | 11        | 9.73%   |
| Graphics card            | 3         | 2.65%   |
| Firewire controller      | 3         | 2.65%   |
| Network                  | 2         | 1.77%   |

