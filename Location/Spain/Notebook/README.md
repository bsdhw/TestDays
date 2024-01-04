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

Total: 108

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| AMI           | Intel                       | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Dell          | Precision 5510              | [4bad5ad995](https://bsd-hardware.info/?probe=4bad5ad995) | Dec 23, 2023 |
| HP            | Stream Notebook PC 11       | [1eb8cc9d76](https://bsd-hardware.info/?probe=1eb8cc9d76) | Dec 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7a5e6024cd](https://bsd-hardware.info/?probe=7a5e6024cd) | Dec 15, 2023 |
| Toshiba       | Portable PC                 | [bee6ea8f18](https://bsd-hardware.info/?probe=bee6ea8f18) | Dec 15, 2023 |
| Dell          | Precision 5510              | [3a7b2ae214](https://bsd-hardware.info/?probe=3a7b2ae214) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b08dc9fc91](https://bsd-hardware.info/?probe=b08dc9fc91) | Oct 16, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
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
| helloSystem 0.7.0    | 16        | 17.78%  |
| helloSystem 0.8.1    | 7         | 7.78%   |
| helloSystem 0.8.0    | 6         | 6.67%   |
| helloSystem 0.5.0    | 4         | 4.44%   |
| FreeBSD 13.1         | 4         | 4.44%   |
| OpenBSD 7.2          | 3         | 3.33%   |
| helloSystem 0.6.0    | 3         | 3.33%   |
| GhostBSD 20.04.02    | 3         | 3.33%   |
| FreeBSD 13.2         | 3         | 3.33%   |
| OpenBSD 7.1          | 2         | 2.22%   |
| OpenBSD 6.8          | 2         | 2.22%   |
| helloSystem 0.8.2    | 2         | 2.22%   |
| helloSystem 0.4.0    | 2         | 2.22%   |
| FuguIta 7.2          | 2         | 2.22%   |
| FreeBSD 14.0-p3      | 2         | 2.22%   |
| FreeBSD 14.0         | 2         | 2.22%   |
| OPNsense 23.1.6      | 1         | 1.11%   |
| OPNsense 22.7.10     | 1         | 1.11%   |
| OPNsense 21.7.6      | 1         | 1.11%   |
| OPNsense 21.7.5      | 1         | 1.11%   |
| OpenBSD 7.4          | 1         | 1.11%   |
| OpenBSD 7.3          | 1         | 1.11%   |
| OpenBSD 6.9          | 1         | 1.11%   |
| NomadBSD 5806f915    | 1         | 1.11%   |
| NomadBSD 20221130    | 1         | 1.11%   |
| helloSystem 0.9.0    | 1         | 1.11%   |
| GhostBSD 23.09.06    | 1         | 1.11%   |
| GhostBSD 23.03.17    | 1         | 1.11%   |
| GhostBSD 23.01.13    | 1         | 1.11%   |
| GhostBSD 22.06.18    | 1         | 1.11%   |
| GhostBSD 21.08.27    | 1         | 1.11%   |
| FreeBSD 14.0-CURRENT | 1         | 1.11%   |
| FreeBSD 13.2-p2      | 1         | 1.11%   |
| FreeBSD 13.1-p7      | 1         | 1.11%   |
| FreeBSD 13.1-p5      | 1         | 1.11%   |
| FreeBSD 13.1-p2      | 1         | 1.11%   |
| FreeBSD 13.1-p1      | 1         | 1.11%   |
| FreeBSD 13.0-STABLE  | 1         | 1.11%   |
| FreeBSD 13.0-RC3     | 1         | 1.11%   |
| FreeBSD 13.0-RC1     | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 34        | 43.59%  |
| FreeBSD     | 21        | 26.92%  |
| OpenBSD     | 8         | 10.26%  |
| GhostBSD    | 8         | 10.26%  |
| OPNsense    | 3         | 3.85%   |
| NomadBSD    | 2         | 2.56%   |
| FuguIta     | 2         | 2.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 74        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 42        | 53.16%  |
| MATE         | 10        | 12.66%  |
| Console      | 9         | 11.39%  |
| TWM          | 4         | 5.06%   |
| XFCE         | 3         | 3.8%    |
| Openbox      | 3         | 3.8%    |
| fvwm         | 3         | 3.8%    |
| KDE5         | 2         | 2.53%   |
| i3           | 2         | 2.53%   |
| GNOME        | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 64        | 85.33%  |
| Console | 8         | 10.67%  |
| Wayland | 3         | 4%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 37        | 47.44%  |
| Console | 21        | 26.92%  |
| LightDM | 10        | 12.82%  |
| SDDM    | 4         | 5.13%   |
| GDM     | 3         | 3.85%   |
| Ly      | 2         | 2.56%   |
| XDM     | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 25        | 31.25%  |
| es_ES   | 19        | 23.75%  |
| C       | 15        | 18.75%  |
| Unknown | 14        | 17.5%   |
| es      | 3         | 3.75%   |
| zh_CN   | 1         | 1.25%   |
| ru_RU   | 1         | 1.25%   |
| fr_FR   | 1         | 1.25%   |
| de_DE   | 1         | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 62        | 83.78%  |
| BIOS | 12        | 16.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 42        | 54.55%  |
| Cd9660 | 17        | 22.08%  |
| Ffs    | 10        | 12.99%  |
| Ufs    | 8         | 10.39%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 64        | 86.49%  |
| MBR  | 10        | 13.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 22.97%  |
| Lenovo              | 16        | 21.62%  |
| Dell                | 7         | 9.46%   |
| ASUSTek Computer    | 7         | 9.46%   |
| Acer                | 5         | 6.76%   |
| Apple               | 4         | 5.41%   |
| Toshiba             | 2         | 2.7%    |
| SLIMBOOK            | 2         | 2.7%    |
| Unknown             | 2         | 2.7%    |
| TWINHEAD            | 1         | 1.35%   |
| TUXEDO              | 1         | 1.35%   |
| Sony                | 1         | 1.35%   |
| Samsung Electronics | 1         | 1.35%   |
| ReachingTech        | 1         | 1.35%   |
| Razer               | 1         | 1.35%   |
| Packard Bell        | 1         | 1.35%   |
| MSI                 | 1         | 1.35%   |
| Chuwi               | 1         | 1.35%   |
| AZW                 | 1         | 1.35%   |
| AMI                 | 1         | 1.35%   |
| Alienware           | 1         | 1.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7390                       | 3         | 4.05%   |
| Unknown                                  | 3         | 4.05%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 2.7%    |
| ASUS K55VD                               | 2         | 2.7%    |
| TWINHEAD U12CT                           | 1         | 1.35%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.35%   |
| Toshiba Satellite A300                   | 1         | 1.35%   |
| Toshiba Portable PC                      | 1         | 1.35%   |
| Sony SVE1511C5E                          | 1         | 1.35%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.35%   |
| SLIMBOOK ESSENTIAL-15-11                 | 1         | 1.35%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.35%   |
| ReachingTech DreamQuest Pro 2022         | 1         | 1.35%   |
| Razer Blade Stealth                      | 1         | 1.35%   |
| Packard Bell DOT S                       | 1         | 1.35%   |
| MSI GE75 Raider 10SGS                    | 1         | 1.35%   |
| Lenovo Yoga 2 13 20344                   | 1         | 1.35%   |
| Lenovo ThinkPad X270 20HMS06Q1D          | 1         | 1.35%   |
| Lenovo ThinkPad X200 745969G             | 1         | 1.35%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES53R00 | 1         | 1.35%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.35%   |
| Lenovo ThinkPad T470s 20HGS3AX02         | 1         | 1.35%   |
| Lenovo ThinkPad T440p 20AWS1CH00         | 1         | 1.35%   |
| Lenovo ThinkPad T440p 20AW007QMS         | 1         | 1.35%   |
| Lenovo ThinkPad L590 20Q7000YSP          | 1         | 1.35%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 1.35%   |
| Lenovo ThinkPad L440 20ASS0FP00          | 1         | 1.35%   |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 1.35%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW     | 1         | 1.35%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 1.35%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.35%   |
| Lenovo G50-80 80E5                       | 1         | 1.35%   |
| HP Stream Notebook PC 11                 | 1         | 1.35%   |
| HP ProBook 4540s                         | 1         | 1.35%   |
| HP ProBook 4340s                         | 1         | 1.35%   |
| HP ProBook 430 G7                        | 1         | 1.35%   |
| HP Pavilion dv6                          | 1         | 1.35%   |
| HP Pavilion dv4                          | 1         | 1.35%   |
| HP Pavilion dv3500                       | 1         | 1.35%   |
| HP OMEN Laptop 15-en1xxx                 | 1         | 1.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 12        | 16.22%  |
| HP Pavilion              | 5         | 6.76%   |
| Dell Latitude            | 4         | 5.41%   |
| Acer Aspire              | 4         | 5.41%   |
| HP ProBook               | 3         | 4.05%   |
| HP OMEN                  | 3         | 4.05%   |
| Unknown                  | 3         | 4.05%   |
| Lenovo IdeaPad           | 2         | 2.7%    |
| HP Laptop                | 2         | 2.7%    |
| ASUS K55VD               | 2         | 2.7%    |
| Apple MacBook5           | 2         | 2.7%    |
| TWINHEAD U12CT           | 1         | 1.35%   |
| TUXEDO Aura              | 1         | 1.35%   |
| Toshiba Satellite        | 1         | 1.35%   |
| Toshiba Portable         | 1         | 1.35%   |
| Sony SVE1511C5E          | 1         | 1.35%   |
| SLIMBOOK PROX-AMD5       | 1         | 1.35%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 1.35%   |
| Samsung 530U3C           | 1         | 1.35%   |
| ReachingTech DreamQuest  | 1         | 1.35%   |
| Razer Blade              | 1         | 1.35%   |
| Packard Bell DOT         | 1         | 1.35%   |
| MSI GE75                 | 1         | 1.35%   |
| Lenovo Yoga              | 1         | 1.35%   |
| Lenovo G50-80            | 1         | 1.35%   |
| HP Stream                | 1         | 1.35%   |
| HP EliteBook             | 1         | 1.35%   |
| HP Compaq                | 1         | 1.35%   |
| HP 250                   | 1         | 1.35%   |
| Dell Studio              | 1         | 1.35%   |
| Dell Precision           | 1         | 1.35%   |
| Dell Inspiron            | 1         | 1.35%   |
| AZW BT3                  | 1         | 1.35%   |
| ASUS X556UJ              | 1         | 1.35%   |
| ASUS U33Jc               | 1         | 1.35%   |
| ASUS TUF                 | 1         | 1.35%   |
| ASUS 1215B               | 1         | 1.35%   |
| ASUS 1201N               | 1         | 1.35%   |
| Apple MacBook6           | 1         | 1.35%   |
| Apple MacBook4           | 1         | 1.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 13        | 17.57%  |
| 2022 | 7         | 9.46%   |
| 2019 | 7         | 9.46%   |
| 2012 | 6         | 8.11%   |
| 2009 | 6         | 8.11%   |
| 2018 | 4         | 5.41%   |
| 2016 | 4         | 5.41%   |
| 2014 | 4         | 5.41%   |
| 2011 | 4         | 5.41%   |
| 2008 | 4         | 5.41%   |
| 2017 | 3         | 4.05%   |
| 2010 | 3         | 4.05%   |
| 2021 | 2         | 2.7%    |
| 2015 | 2         | 2.7%    |
| 2013 | 2         | 2.7%    |
| 2007 | 2         | 2.7%    |
| 2023 | 1         | 1.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 74        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 74        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 38.16%  |
| 4.01-8.0    | 17        | 22.37%  |
| 16.01-24.0  | 17        | 22.37%  |
| 32.01-64.0  | 6         | 7.89%   |
| 2.01-3.0    | 3         | 3.95%   |
| 3.01-4.0    | 2         | 2.63%   |
| 24.01-32.0  | 1         | 1.32%   |
| 64.01-256.0 | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 40        | 51.95%  |
| 0.51-1.0 | 25        | 32.47%  |
| 1.01-2.0 | 8         | 10.39%  |
| 2.01-3.0 | 4         | 5.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 68.42%  |
| 2      | 15        | 19.74%  |
| 0      | 6         | 7.89%   |
| 3      | 2         | 2.63%   |
| 4      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 74.67%  |
| Yes       | 19        | 25.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 89.19%  |
| No        | 8         | 10.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 95.95%  |
| No        | 3         | 4.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 78.38%  |
| No        | 16        | 21.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 74        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 12        | 14.29%  |
| Barcelona                     | 8         | 9.52%   |
| Valencia                      | 4         | 4.76%   |
| Terrassa                      | 3         | 3.57%   |
| Navalcarnero                  | 3         | 3.57%   |
| Tarragona                     | 2         | 2.38%   |
| Paterna                       | 2         | 2.38%   |
| GibraleГіn                  | 2         | 2.38%   |
| Alcobendas                    | 2         | 2.38%   |
| Zarautz                       | 1         | 1.19%   |
| Zaragoza                      | 1         | 1.19%   |
| Vitoria-Gasteiz               | 1         | 1.19%   |
| Villapresente                 | 1         | 1.19%   |
| Urnieta                       | 1         | 1.19%   |
| Tudela de Duero               | 1         | 1.19%   |
| Torrent                       | 1         | 1.19%   |
| Seville                       | 1         | 1.19%   |
| Sedavi                        | 1         | 1.19%   |
| Santa Cruz de Tenerife        | 1         | 1.19%   |
| Santa Coloma de Farners       | 1         | 1.19%   |
| Sanlucar la Mayor             | 1         | 1.19%   |
| San Vicent del Raspeig        | 1         | 1.19%   |
| San SebastiÃ¡n de los Reyes | 1         | 1.19%   |
| Rubí                         | 1         | 1.19%   |
| Redondela                     | 1         | 1.19%   |
| Padul                         | 1         | 1.19%   |
| Ourense                       | 1         | 1.19%   |
| Orihuela Costa                | 1         | 1.19%   |
| Málaga                       | 1         | 1.19%   |
| Los Realejos                  | 1         | 1.19%   |
| LogroГ±o                    | 1         | 1.19%   |
| LogroÃ±o                    | 1         | 1.19%   |
| Laguna de Duero               | 1         | 1.19%   |
| La Pobla de Farnals           | 1         | 1.19%   |
| Ibiza Town                    | 1         | 1.19%   |
| Godella                       | 1         | 1.19%   |
| Girona                        | 1         | 1.19%   |
| Fuenterrabia                  | 1         | 1.19%   |
| Esparragosa de Lares          | 1         | 1.19%   |
| Elche                         | 1         | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 15        | 29     | 17.05%  |
| WDC                                    | 9         | 11     | 10.23%  |
| Kingston                               | 7         | 8      | 7.95%   |
| NVMe                                   | 6         | 9      | 6.82%   |
| Crucial                                | 6         | 6      | 6.82%   |
| Toshiba                                | 5         | 7      | 5.68%   |
| Hitachi                                | 5         | 5      | 5.68%   |
| Seagate                                | 4         | 4      | 4.55%   |
| SanDisk                                | 4         | 4      | 4.55%   |
| Intel                                  | 3         | 3      | 3.41%   |
| HGST                                   | 3         | 3      | 3.41%   |
| Product:              USB Flash Memory | 2         | 2      | 2.27%   |
| OCZ                                    | 2         | 2      | 2.27%   |
| Micron Technology                      | 2         | 2      | 2.27%   |
| Fujitsu                                | 2         | 2      | 2.27%   |
| XrayDisk                               | 1         | 1      | 1.14%   |
| Union Memory                           | 1         | 1      | 1.14%   |
| Transcend                              | 1         | 1      | 1.14%   |
| TCSUNBOW                               | 1         | 1      | 1.14%   |
| SK hynix                               | 1         | 1      | 1.14%   |
| PNY                                    | 1         | 1      | 1.14%   |
| Netac                                  | 1         | 1      | 1.14%   |
| LITEONIT                               | 1         | 1      | 1.14%   |
| Kston                                  | 1         | 2      | 1.14%   |
| KIOXIA                                 | 1         | 1      | 1.14%   |
| KingSpec                               | 1         | 1      | 1.14%   |
| Intenso                                | 1         | 1      | 1.14%   |
| China                                  | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 2.15%   |
| NVMe Samsung SSD 980 1TB                                     | 2         | 2.15%   |
| Kingston SA400S37240G 240GB                                  | 2         | 2.15%   |
| Crucial CT480BX500SSD1 480GB                                 | 2         | 2.15%   |
| XrayDisk SSD 240GB                                           | 1         | 1.08%   |
| WDC WDS100T2B0C-00PXH0 1TB                                   | 1         | 1.08%   |
| WDC WD5000LPCX-21VHAT0 500GB                                 | 1         | 1.08%   |
| WDC WD2500BEVT-35A23T0 250GB                                 | 1         | 1.08%   |
| WDC WD1200BEVS-22UST0 120GB                                  | 1         | 1.08%   |
| WDC WD10JPCX-24UE4T0 1TB                                     | 1         | 1.08%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 1         | 1.08%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                           | 1         | 1.08%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB                           | 1         | 1.08%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                         | 1         | 1.08%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                         | 1         | 1.08%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB              | 1         | 1.08%   |
| Transcend TS120GMTS420S 120GB                                | 1         | 1.08%   |
| Toshiba MQ01ABD100 1TB                                       | 1         | 1.08%   |
| Toshiba MK5065GSXF 500GB                                     | 1         | 1.08%   |
| Toshiba MK1229GSG 120GB                                      | 1         | 1.08%   |
| Toshiba MK1059GSM 1TB                                        | 1         | 1.08%   |
| Toshiba KXG60ZNV512G NVMe 512GB                              | 1         | 1.08%   |
| TCSUNBOW X3 480GB                                            | 1         | 1.08%   |
| SK hynix HFM512GDHTNG-8710B 512GB                            | 1         | 1.08%   |
| Seagate ST9500325AS 500GB                                    | 1         | 1.08%   |
| Seagate ST500LM021-1KJ152 500GB                              | 1         | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB                               | 1         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 1         | 1.08%   |
| SanDisk SSD PLUS 240GB                                       | 1         | 1.08%   |
| SanDisk SSD i100 24GB                                        | 1         | 1.08%   |
| SanDisk SDSSDP128G 128GB                                     | 1         | 1.08%   |
| SanDisk SD9SN8W-256G-1006 256GB                              | 1         | 1.08%   |
| Samsung SSD 970 EVO Plus 2TB                                 | 1         | 1.08%   |
| Samsung SSD 970 EVO 250GB                                    | 1         | 1.08%   |
| Samsung SSD 870 QVO 8TB                                      | 1         | 1.08%   |
| Samsung SSD 870 EVO 1TB                                      | 1         | 1.08%   |
| Samsung SSD 860 PRO 512GB                                    | 1         | 1.08%   |
| Samsung SSD 860 EVO 500GB                                    | 1         | 1.08%   |
| Samsung SSD 850 EVO 500GB                                    | 1         | 1.08%   |
| Samsung SSD 850 EVO 250GB                                    | 1         | 1.08%   |

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
| Samsung Electronics | 8         | 14     | 21.05%  |
| Kingston            | 6         | 7      | 15.79%  |
| SanDisk             | 4         | 4      | 10.53%  |
| Crucial             | 4         | 4      | 10.53%  |
| OCZ                 | 2         | 2      | 5.26%   |
| NVMe                | 2         | 2      | 5.26%   |
| Intel               | 2         | 2      | 5.26%   |
| XrayDisk            | 1         | 1      | 2.63%   |
| Transcend           | 1         | 1      | 2.63%   |
| TCSUNBOW            | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| Netac               | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| Kston               | 1         | 2      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 36        | 46     | 42.35%  |
| HDD  | 29        | 34     | 34.12%  |
| NVMe | 20        | 31     | 23.53%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 55        | 80     | 73.33%  |
| NVMe | 20        | 31     | 26.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 60     | 77.05%  |
| 0.51-1.0   | 12        | 16     | 19.67%  |
| 1.01-2.0   | 1         | 3      | 1.64%   |
| 4.01-10.0  | 1         | 1      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 28        | 35.44%  |
| 101-250    | 25        | 31.65%  |
| 251-500    | 15        | 18.99%  |
| 501-1000   | 4         | 5.06%   |
| 1001-2000  | 3         | 3.8%    |
| 21-50      | 2         | 2.53%   |
| 51-100     | 2         | 2.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 68        | 89.47%  |
| 21-50    | 3         | 3.95%   |
| 51-100   | 3         | 3.95%   |
| 251-500  | 1         | 1.32%   |
| 501-1000 | 1         | 1.32%   |

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
| Works    | 57        | 86     | 74.03%  |
| Malfunc  | 14        | 14     | 18.18%  |
| Detected | 6         | 11     | 7.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 47        | 55.95%  |
| Samsung Electronics         | 8         | 9.52%   |
| AMD                         | 6         | 7.14%   |
| SanDisk                     | 5         | 5.95%   |
| Nvidia                      | 5         | 5.95%   |
| Micron/Crucial Technology   | 3         | 3.57%   |
| SK hynix                    | 2         | 2.38%   |
| Kingston Technology Company | 2         | 2.38%   |
| Union Memory (Shenzhen)     | 1         | 1.19%   |
| Toshiba                     | 1         | 1.19%   |
| Silicon Motion              | 1         | 1.19%   |
| Phison Electronics          | 1         | 1.19%   |
| Micron Technology           | 1         | 1.19%   |
| KIOXIA                      | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 6.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 5.32%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 4.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.26%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 4.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.19%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 3.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.19%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 2.13%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.13%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.13%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.06%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 1.06%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.06%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.06%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.06%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.06%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 1.06%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.06%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 1.06%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.06%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.06%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 1         | 1.06%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 54        | 60.67%  |
| NVMe | 24        | 26.97%  |
| IDE  | 7         | 7.87%   |
| RAID | 4         | 4.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 83.78%  |
| AMD    | 12        | 16.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz     | 2         | 2.7%    |
| Intel Core i5-8350U CPU @ 1.70GHz      | 2         | 2.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz      | 2         | 2.7%    |
| Intel Core i5-7300U CPU @ 2.60GHz      | 2         | 2.7%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 2         | 2.7%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz   | 2         | 2.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics | 2         | 2.7%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz | 1         | 1.35%   |
| Intel Pentium CPU B970 @ 2.30GHz       | 1         | 1.35%   |
| Intel Other                            | 1         | 1.35%   |
| Intel CPU Version                      | 1         | 1.35%   |
| Intel Core i9-10980HK CPU @ 2.40GHz    | 1         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 1         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz      | 1         | 1.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 1         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz      | 1         | 1.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz     | 1         | 1.35%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz     | 1         | 1.35%   |
| Intel Core i7-4510U CPU @ 2.00GHz      | 1         | 1.35%   |
| Intel Core i7-3610QM CPU @ 2.30GHz     | 1         | 1.35%   |
| Intel Core i7-10875H CPU @ 2.30GHz     | 1         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz     | 1         | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 1         | 1.35%   |
| Intel Core i5-8365U CPU @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.35%   |
| Intel Core i5-4300M CPU @ 2.60GHz      | 1         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 1         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.35%   |
| Intel Core i5-2537M CPU @ 1.40GHz      | 1         | 1.35%   |
| Intel Core i5-2430M CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i5 CPU U 560 @ 1.33GHz      | 1         | 1.35%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.35%   |
| Intel Core i3-4010U CPU @ 1.70GHz      | 1         | 1.35%   |
| Intel Core i3-3110M CPU @ 2.40GHz      | 1         | 1.35%   |
| Intel Core i3 CPU M 370 @ 2.40GH       | 1         | 1.35%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz   | 1         | 1.35%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz   | 1         | 1.35%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz   | 1         | 1.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 17        | 22.97%  |
| Intel Core i7      | 14        | 18.92%  |
| Intel Core 2 Duo   | 10        | 13.51%  |
| Intel Celeron      | 6         | 8.11%   |
| AMD Ryzen 7        | 6         | 8.11%   |
| Other              | 5         | 6.76%   |
| Intel Core i3      | 4         | 5.41%   |
| Intel Atom         | 3         | 4.05%   |
| AMD Ryzen 5        | 2         | 2.7%    |
| Intel Pentium Dual | 1         | 1.35%   |
| Intel Pentium      | 1         | 1.35%   |
| Intel Core i9      | 1         | 1.35%   |
| AMD Sempron        | 1         | 1.35%   |
| AMD E              | 1         | 1.35%   |
| AMD Athlon         | 1         | 1.35%   |
| AMD A4             | 1         | 1.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 30        | 40.54%  |
| 4       | 21        | 28.38%  |
| Unknown | 11        | 14.86%  |
| 8       | 5         | 6.76%   |
| 16      | 3         | 4.05%   |
| 12      | 2         | 2.7%    |
| 6       | 1         | 1.35%   |
| 1       | 1         | 1.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 69        | 93.24%  |
| 2       | 4         | 5.41%   |
| Unknown | 1         | 1.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 52.7%   |
| 1       | 24        | 32.43%  |
| Unknown | 11        | 14.86%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 12        | 16.22%  |
| Penryn          | 9         | 12.16%  |
| Haswell         | 7         | 9.46%   |
| IvyBridge       | 5         | 6.76%   |
| Skylake         | 4         | 5.41%   |
| Core            | 4         | 5.41%   |
| Zen+            | 3         | 4.05%   |
| Zen 2           | 3         | 4.05%   |
| TigerLake       | 3         | 4.05%   |
| Silvermont      | 3         | 4.05%   |
| SandyBridge     | 3         | 4.05%   |
| CometLake       | 3         | 4.05%   |
| Unknown         | 3         | 4.05%   |
| Zen 3           | 2         | 2.7%    |
| Westmere        | 2         | 2.7%    |
| Broadwell       | 2         | 2.7%    |
| Bonnell         | 2         | 2.7%    |
| K8 & K10 hybrid | 1         | 1.35%   |
| Goldmont plus   | 1         | 1.35%   |
| Excavator       | 1         | 1.35%   |
| Bobcat          | 1         | 1.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 58.43%  |
| Nvidia | 20        | 22.47%  |
| AMD    | 17        | 19.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.38%   |
| Intel UHD Graphics 620                                                                   | 4         | 4.3%    |
| Intel HD Graphics 620                                                                    | 4         | 4.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.15%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 2.15%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.15%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.15%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.15%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.15%   |
| Intel HD Graphics 530                                                                    | 2         | 2.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.15%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.08%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.08%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.08%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.08%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.08%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1.08%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.08%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.08%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.08%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 48%     |
| 1 x AMD        | 10        | 13.33%  |
| Intel + Nvidia | 8         | 10.67%  |
| 1 x Nvidia     | 7         | 9.33%   |
| 2 x Intel      | 6         | 8%      |
| AMD + Nvidia   | 4         | 5.33%   |
| Intel + AMD    | 3         | 4%      |
| 2 x Nvidia     | 1         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 67        | 88.16%  |
| Proprietary | 7         | 9.21%   |
| Unknown     | 2         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 84.62%  |
| 0.01-0.5   | 7         | 8.97%   |
| 1.01-2.0   | 2         | 2.56%   |
| 7.01-8.0   | 1         | 1.28%   |
| 5.01-6.0   | 1         | 1.28%   |
| 2.01-3.0   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 10        | 17.86%  |
| Chimei Innolux          | 7         | 12.5%   |
| BOE                     | 7         | 12.5%   |
| LG Display              | 5         | 8.93%   |
| Chi Mei Optoelectronics | 4         | 7.14%   |
| Samsung Electronics     | 3         | 5.36%   |
| Lenovo                  | 3         | 5.36%   |
| BenQ                    | 3         | 5.36%   |
| Apple                   | 3         | 5.36%   |
| Sharp                   | 2         | 3.57%   |
| Hewlett-Packard         | 2         | 3.57%   |
| PANDA                   | 1         | 1.79%   |
| Mi                      | 1         | 1.79%   |
| LGD                     | 1         | 1.79%   |
| LG Philips              | 1         | 1.79%   |
| Fujitsu Siemens         | 1         | 1.79%   |
| AOC                     | 1         | 1.79%   |
| Acer                    | 1         | 1.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch           | 3         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 2         | 3.51%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 3.51%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch                  | 1         | 1.75%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                  | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch     | 1         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.75%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.75%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                         | 1         | 1.75%   |
| LGD LCD Monitor 5760x1080                                                | 1         | 1.75%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.75%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 1.75%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.75%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.75%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch               | 1         | 1.75%   |
| Hewlett-Packard 22er HWP331B 1920x1080 500x300mm 23.0-inch               | 1         | 1.75%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 340x190mm 15.3-inch         | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.75%   |
| Chimei Innolux LCD Monitor CMN1136 1366x768 260x140mm 11.6-inch          | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 340x190mm 15.3-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 300x190mm 14.0-inch | 1         | 1.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 220x120mm 9.9-inch  | 1         | 1.75%   |
| BOE LCD Monitor BOE0960 1366x768 340x190mm 15.3-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 1.75%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 1.75%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 1.75%   |
| BenQ V2400Eco BNQ7D02 1920x1080 530x300mm 24.0-inch                      | 1         | 1.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 22        | 40.74%  |
| 1366x768 (WXGA)  | 16        | 29.63%  |
| 1280x800 (WXGA)  | 8         | 14.81%  |
| 3840x2160 (4K)   | 2         | 3.7%    |
| 1600x900 (HD+)   | 2         | 3.7%    |
| 5760x1080        | 1         | 1.85%   |
| 1280x1024 (SXGA) | 1         | 1.85%   |
| 1024x600         | 1         | 1.85%   |
| Unknown          | 1         | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 24        | 42.86%  |
| 13      | 15        | 26.79%  |
| 24      | 4         | 7.14%   |
| 12      | 3         | 5.36%   |
| 27      | 2         | 3.57%   |
| 19      | 2         | 3.57%   |
| 14      | 2         | 3.57%   |
| 23      | 1         | 1.79%   |
| 11      | 1         | 1.79%   |
| 9       | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 30        | 53.57%  |
| 201-300     | 16        | 28.57%  |
| 501-600     | 6         | 10.71%  |
| 401-500     | 2         | 3.57%   |
| 351-400     | 1         | 1.79%   |
| Unknown     | 1         | 1.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 80.77%  |
| 16/10   | 7         | 13.46%  |
| 5/4     | 1         | 1.92%   |
| 3/2     | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 21        | 37.5%   |
| 81-90          | 11        | 19.64%  |
| 71-80          | 6         | 10.71%  |
| 201-250        | 5         | 8.93%   |
| 61-70          | 3         | 5.36%   |
| 101-110        | 3         | 5.36%   |
| 301-350        | 2         | 3.57%   |
| 151-200        | 2         | 3.57%   |
| 51-60          | 1         | 1.79%   |
| 41-50          | 1         | 1.79%   |
| Unknown        | 1         | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 19        | 33.93%  |
| 121-160       | 18        | 32.14%  |
| 51-100        | 11        | 19.64%  |
| 161-240       | 5         | 8.93%   |
| More than 240 | 2         | 3.57%   |
| Unknown       | 1         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 54        | 69.23%  |
| 0     | 19        | 24.36%  |
| 2     | 5         | 6.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 41        | 32.8%   |
| Realtek Semiconductor             | 40        | 32%     |
| Qualcomm Atheros                  | 12        | 9.6%    |
| Broadcom                          | 11        | 8.8%    |
| Nvidia                            | 4         | 3.2%    |
| TP-Link                           | 2         | 1.6%    |
| Sierra Wireless                   | 2         | 1.6%    |
| Ralink Technology                 | 2         | 1.6%    |
| Ralink                            | 2         | 1.6%    |
| Marvell Technology Group          | 2         | 1.6%    |
| D-Link System                     | 2         | 1.6%    |
| Xiaomi                            | 1         | 0.8%    |
| MediaTek                          | 1         | 0.8%    |
| IMC Networks                      | 1         | 0.8%    |
| Huawei Technologies               | 1         | 0.8%    |
| Ericsson Business Mobile Networks | 1         | 0.8%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 32        | 20.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 5         | 3.27%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 3.27%   |
| Intel Wi-Fi 6 AX200                                                        | 5         | 3.27%   |
| Intel Ethernet Connection (4) I219-LM                                      | 5         | 3.27%   |
| Nvidia MCP79 Ethernet                                                      | 4         | 2.61%   |
| Intel Wireless 7265                                                        | 4         | 2.61%   |
| Intel Wireless 7260                                                        | 4         | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 1.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 1.96%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 1.96%   |
| Intel Ethernet Connection I217-LM                                          | 3         | 1.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 1.96%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 1.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 1.31%   |
| Intel Wireless 3160                                                        | 2         | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.31%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.31%   |
| Intel 82567LM Gigabit Network Connection                                   | 2         | 1.31%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 0.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 0.65%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.65%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 1         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 49.38%  |
| Realtek Semiconductor | 11        | 13.58%  |
| Broadcom              | 10        | 12.35%  |
| Qualcomm Atheros      | 8         | 9.88%   |
| TP-Link               | 2         | 2.47%   |
| Sierra Wireless       | 2         | 2.47%   |
| Ralink Technology     | 2         | 2.47%   |
| Ralink                | 2         | 2.47%   |
| D-Link System         | 2         | 2.47%   |
| MediaTek              | 1         | 1.23%   |
| IMC Networks          | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 5         | 5.95%   |
| Intel Wi-Fi 6 AX200                                                        | 5         | 5.95%   |
| Intel Wireless 7265                                                        | 4         | 4.76%   |
| Intel Wireless 7260                                                        | 4         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 3         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 3.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 3.57%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 3.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 3.57%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 2.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 2.38%   |
| Intel Wireless 3160                                                        | 2         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 2.38%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 2.38%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 1.19%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 1.19%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 1.19%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 1.19%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 1.19%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 1.19%   |
| Intel Wireless-AC 9260                                                     | 1         | 1.19%   |
| Intel Wireless 8260                                                        | 1         | 1.19%   |
| Intel Wireless 3165                                                        | 1         | 1.19%   |
| Intel WiFi Link 5100                                                       | 1         | 1.19%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 1         | 1.19%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 55.22%  |
| Intel                    | 18        | 26.87%  |
| Qualcomm Atheros         | 4         | 5.97%   |
| Nvidia                   | 4         | 5.97%   |
| Marvell Technology Group | 2         | 2.99%   |
| Xiaomi                   | 1         | 1.49%   |
| Broadcom                 | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 47.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 7.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 7.46%   |
| Nvidia MCP79 Ethernet                                             | 4         | 5.97%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 4.48%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.49%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller               | 1         | 1.49%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.49%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.49%   |
| Intel 82566MC Gigabit Network Connection                          | 1         | 1.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 51.08%  |
| Ethernet | 66        | 47.48%  |
| Modem    | 2         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 41        | 49.4%   |
| Ethernet | 41        | 49.4%   |
| Modem    | 1         | 1.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 82.43%  |
| 1     | 10        | 13.51%  |
| 6     | 1         | 1.35%   |
| 3     | 1         | 1.35%   |
| 0     | 1         | 1.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 97.3%   |
| Yes  | 2         | 2.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 52.54%  |
| Realtek Semiconductor           | 7         | 11.86%  |
| Apple                           | 4         | 6.78%   |
| Hewlett-Packard                 | 3         | 5.08%   |
| Broadcom                        | 3         | 5.08%   |
| Ralink                          | 2         | 3.39%   |
| Qualcomm Atheros Communications | 2         | 3.39%   |
| IMC Networks                    | 2         | 3.39%   |
| Foxconn / Hon Hai               | 2         | 3.39%   |
| Cambridge Silicon Radio         | 2         | 3.39%   |
| ASUSTek Computer                | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 28.33%  |
| Intel AX201 Bluetooth                                       | 5         | 8.33%   |
| Intel AX200 Bluetooth                                       | 5         | 8.33%   |
| Realtek Bluetooth Adapter                                   | 3         | 5%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 5%      |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 3.33%   |
| Ralink RT3290 Bluetooth                                     | 2         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.33%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 3.33%   |
| Apple Bluetooth Host Controller                             | 2         | 3.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.67%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.67%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.67%   |
| IMC Networks Bluetooth module                               | 1         | 1.67%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.67%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 56        | 63.64%  |
| AMD                                          | 14        | 15.91%  |
| Nvidia                                       | 13        | 14.77%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 2.27%   |
| Texas Instruments                            | 1         | 1.14%   |
| Generalplus Technology                       | 1         | 1.14%   |
| C-Media Electronics                          | 1         | 1.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.62%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 6.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 5.77%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 4.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.85%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.88%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 1.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.92%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.92%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.92%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.92%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.96%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 0.96%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.96%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.96%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.96%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.96%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 25.64%  |
| SK hynix            | 16        | 20.51%  |
| Kingston            | 9         | 11.54%  |
| Micron Technology   | 8         | 10.26%  |
| Crucial             | 5         | 6.41%   |
| Unknown             | 3         | 3.85%   |
| Ramaxel Technology  | 3         | 3.85%   |
| Unknown             | 3         | 3.85%   |
| Elpida              | 2         | 2.56%   |
| A-DATA Technology   | 2         | 2.56%   |
| Unknown (ABCD)      | 1         | 1.28%   |
| Unknown (0x0080)    | 1         | 1.28%   |
| Transcend           | 1         | 1.28%   |
| Nanya Technology    | 1         | 1.28%   |
| G.Skill             | 1         | 1.28%   |
| Corsair             | 1         | 1.28%   |
| ASint Technology    | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 3         | 3.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 2.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 2.27%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 2.27%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.27%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 2         | 2.27%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.14%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 1.14%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 1         | 1.14%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.14%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.14%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s                      | 1         | 1.14%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                      | 1         | 1.14%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.14%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s                     | 1         | 1.14%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.14%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s             | 1         | 1.14%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 1.14%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.14%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.14%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.14%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 1         | 1.14%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.14%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.14%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.14%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.14%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.14%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 41.18%  |
| DDR4    | 25        | 36.76%  |
| DDR2    | 9         | 13.24%  |
| LPDDR4  | 2         | 2.94%   |
| LPDDR3  | 2         | 2.94%   |
| SDRAM   | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 94.12%  |
| Row Of Chips | 4         | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 34.25%  |
| 8192  | 24        | 32.88%  |
| 2048  | 12        | 16.44%  |
| 16384 | 8         | 10.96%  |
| 1024  | 3         | 4.11%   |
| 32768 | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 19        | 26.03%  |
| 3200    | 9         | 12.33%  |
| 2667    | 9         | 12.33%  |
| 2400    | 9         | 12.33%  |
| 667     | 7         | 9.59%   |
| 1067    | 4         | 5.48%   |
| 1334    | 3         | 4.11%   |
| 2133    | 2         | 2.74%   |
| 1867    | 2         | 2.74%   |
| 1333    | 2         | 2.74%   |
| 1066    | 2         | 2.74%   |
| 800     | 2         | 2.74%   |
| 3733    | 1         | 1.37%   |
| 2048    | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

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
| Chicony Electronics                    | 11        | 22%     |
| Sunplus Innovation Technology          | 6         | 12%     |
| Bison Electronics                      | 5         | 10%     |
| Realtek Semiconductor                  | 4         | 8%      |
| Quanta                                 | 4         | 8%      |
| Microdia                               | 4         | 8%      |
| Suyin                                  | 3         | 6%      |
| IMC Networks                           | 3         | 6%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4%      |
| USB Camera                             | 1         | 2%      |
| Syntek                                 | 1         | 2%      |
| Silicon Motion                         | 1         | 2%      |
| Ricoh                                  | 1         | 2%      |
| Luxvisions Innotech Limited            | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| Importek                               | 1         | 2%      |
| Alcor Micro                            | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 8%      |
| Sunplus Integrated_Webcam_HD                                               | 3         | 6%      |
| Quanta HP TrueVision HD Camera                                             | 3         | 6%      |
| Realtek USB Camera                                                         | 2         | 4%      |
| Bison Integrated Camera                                                    | 2         | 4%      |
| USB Camera USB Camera                                                      | 1         | 2%      |
| Syntek EasyCamera                                                          | 1         | 2%      |
| Suyin Integrated_Webcam_HD                                                 | 1         | 2%      |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 2%      |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 2%      |
| Sunplus Integrated Camera                                                  | 1         | 2%      |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 2%      |
| Sunplus Asus Webcam                                                        | 1         | 2%      |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 2%      |
| Ricoh Integrated Webcam                                                    | 1         | 2%      |
| Realtek Integrated_Webcam_HD                                               | 1         | 2%      |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 2%      |
| Quanta Realtek DMFT RGB                                                    | 1         | 2%      |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                              | 1         | 2%      |
| Microdia Integrated Webcam                                                 | 1         | 2%      |
| Microdia HP Webcam                                                         | 1         | 2%      |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 2%      |
| Lite-On Integrated Camera                                                  | 1         | 2%      |
| Importek HP Webcam                                                         | 1         | 2%      |
| IMC Networks Realtek PC Camera                                             | 1         | 2%      |
| IMC Networks Integrated Camera                                             | 1         | 2%      |
| IMC Networks 2M Integrated Webcam                                          | 1         | 2%      |
| Chicony WebCam                                                             | 1         | 2%      |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 2%      |
| Chicony USB 2.0 Camera                                                     | 1         | 2%      |
| Chicony Lenovo EasyCamera                                                  | 1         | 2%      |
| Chicony Integrated IR Camera                                               | 1         | 2%      |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 2%      |
| Chicony Chicony USB2.0 Camera                                              | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 2%      |
| Bison SunplusIT Integrated Camera                                          | 1         | 2%      |
| Bison SunplusIT INC. Integrated Camera                                     | 1         | 2%      |
| Bison Lenovo EasyCamera                                                    | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 8         | 61.54%  |
| STMicroelectronics    | 2         | 15.38%  |
| Upek                  | 1         | 7.69%   |
| Synaptics             | 1         | 7.69%   |
| Elan Microelectronics | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 15.38%  |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 15.38%  |
| STMicroelectronics Fingerprint Reader                    | 2         | 15.38%  |
| Validity Sensors Synaptics WBDI                          | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner                     | 1         | 7.69%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 7.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Elan Fingerprint Sensor                                  | 1         | 7.69%   |

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
| 1     | 30        | 37.5%   |
| 2     | 21        | 26.25%  |
| 3     | 14        | 17.5%   |
| 0     | 10        | 12.5%   |
| 4     | 5         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 45        | 37.5%   |
| Net/wireless             | 21        | 17.5%   |
| Bluetooth                | 20        | 16.67%  |
| Card reader              | 13        | 10.83%  |
| Fingerprint reader       | 11        | 9.17%   |
| Graphics card            | 4         | 3.33%   |
| Firewire controller      | 3         | 2.5%    |
| Network                  | 2         | 1.67%   |
| Storage                  | 1         | 0.83%   |

