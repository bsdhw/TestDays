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

Total: 117

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookAir7,2               | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Apple         | MacBookAir7,2               | [a26013b913](https://bsd-hardware.info/?probe=a26013b913) | Apr 05, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0ae72ec0ff](https://bsd-hardware.info/?probe=0ae72ec0ff) | Mar 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| Dell          | XPS 13 9305                 | [7cc4588e07](https://bsd-hardware.info/?probe=7cc4588e07) | Mar 07, 2024 |
| Acer          | TravelMate B115-M           | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [9ed586661c](https://bsd-hardware.info/?probe=9ed586661c) | Jan 03, 2024 |
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
| helloSystem 0.7.0    | 16        | 16.49%  |
| helloSystem 0.8.1    | 9         | 9.28%   |
| helloSystem 0.8.0    | 6         | 6.19%   |
| helloSystem 0.5.0    | 4         | 4.12%   |
| FreeBSD 13.1         | 4         | 4.12%   |
| OpenBSD 7.2          | 3         | 3.09%   |
| helloSystem 0.6.0    | 3         | 3.09%   |
| GhostBSD 20.04.02    | 3         | 3.09%   |
| FreeBSD 13.2         | 3         | 3.09%   |
| OpenBSD 7.1          | 2         | 2.06%   |
| OpenBSD 6.8          | 2         | 2.06%   |
| helloSystem 0.9.0    | 2         | 2.06%   |
| helloSystem 0.8.2    | 2         | 2.06%   |
| helloSystem 0.4.0    | 2         | 2.06%   |
| GhostBSD 24.01.1     | 2         | 2.06%   |
| FuguIta 7.2          | 2         | 2.06%   |
| FreeBSD 14.0-p3      | 2         | 2.06%   |
| FreeBSD 14.0         | 2         | 2.06%   |
| OPNsense 23.1.6      | 1         | 1.03%   |
| OPNsense 22.7.10     | 1         | 1.03%   |
| OPNsense 21.7.6      | 1         | 1.03%   |
| OPNsense 21.7.5      | 1         | 1.03%   |
| OpenBSD 7.4          | 1         | 1.03%   |
| OpenBSD 7.3          | 1         | 1.03%   |
| OpenBSD 6.9          | 1         | 1.03%   |
| NomadBSD 5806f915    | 1         | 1.03%   |
| NomadBSD 20231121    | 1         | 1.03%   |
| NomadBSD 20221130    | 1         | 1.03%   |
| NetBSD 10.0          | 1         | 1.03%   |
| GhostBSD 23.09.06    | 1         | 1.03%   |
| GhostBSD 23.03.17    | 1         | 1.03%   |
| GhostBSD 23.01.13    | 1         | 1.03%   |
| GhostBSD 22.06.18    | 1         | 1.03%   |
| GhostBSD 21.08.27    | 1         | 1.03%   |
| FreeBSD 14.0-CURRENT | 1         | 1.03%   |
| FreeBSD 13.2-p2      | 1         | 1.03%   |
| FreeBSD 13.1-p7      | 1         | 1.03%   |
| FreeBSD 13.1-p5      | 1         | 1.03%   |
| FreeBSD 13.1-p2      | 1         | 1.03%   |
| FreeBSD 13.1-p1      | 1         | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 36        | 43.37%  |
| FreeBSD     | 21        | 25.3%   |
| GhostBSD    | 10        | 12.05%  |
| OpenBSD     | 8         | 9.64%   |
| OPNsense    | 3         | 3.61%   |
| NomadBSD    | 2         | 2.41%   |
| FuguIta     | 2         | 2.41%   |
| NetBSD      | 1         | 1.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 44        | 52.38%  |
| MATE         | 13        | 15.48%  |
| Console      | 9         | 10.71%  |
| TWM          | 4         | 4.76%   |
| XFCE         | 3         | 3.57%   |
| Openbox      | 3         | 3.57%   |
| fvwm         | 3         | 3.57%   |
| KDE5         | 2         | 2.38%   |
| i3           | 2         | 2.38%   |
| GNOME        | 1         | 1.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 68        | 86.08%  |
| Console | 8         | 10.13%  |
| Wayland | 3         | 3.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 39        | 46.99%  |
| Console | 22        | 26.51%  |
| LightDM | 12        | 14.46%  |
| SDDM    | 4         | 4.82%   |
| GDM     | 3         | 3.61%   |
| Ly      | 2         | 2.41%   |
| XDM     | 1         | 1.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 25        | 28.74%  |
| es_ES   | 20        | 22.99%  |
| Unknown | 17        | 19.54%  |
| C       | 16        | 18.39%  |
| es      | 3         | 3.45%   |
| ru_RU   | 2         | 2.3%    |
| fr_FR   | 2         | 2.3%    |
| zh_CN   | 1         | 1.15%   |
| de_DE   | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 65        | 83.33%  |
| BIOS | 13        | 16.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 44        | 53.01%  |
| Cd9660 | 19        | 22.89%  |
| Ufs    | 10        | 12.05%  |
| Ffs    | 10        | 12.05%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 68        | 87.18%  |
| MBR  | 10        | 12.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 17        | 21.79%  |
| Lenovo              | 16        | 20.51%  |
| Dell                | 8         | 10.26%  |
| ASUSTek Computer    | 8         | 10.26%  |
| Acer                | 6         | 7.69%   |
| Apple               | 5         | 6.41%   |
| Toshiba             | 2         | 2.56%   |
| SLIMBOOK            | 2         | 2.56%   |
| Unknown             | 2         | 2.56%   |
| TWINHEAD            | 1         | 1.28%   |
| TUXEDO              | 1         | 1.28%   |
| Sony                | 1         | 1.28%   |
| Samsung Electronics | 1         | 1.28%   |
| ReachingTech        | 1         | 1.28%   |
| Razer               | 1         | 1.28%   |
| Packard Bell        | 1         | 1.28%   |
| MSI                 | 1         | 1.28%   |
| Chuwi               | 1         | 1.28%   |
| AZW                 | 1         | 1.28%   |
| AMI                 | 1         | 1.28%   |
| Alienware           | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude 7390                       | 3         | 3.85%   |
| Unknown                                  | 3         | 3.85%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 2.56%   |
| ASUS K55VD                               | 2         | 2.56%   |
| TWINHEAD U12CT                           | 1         | 1.28%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.28%   |
| Toshiba Satellite A300                   | 1         | 1.28%   |
| Toshiba Portable PC                      | 1         | 1.28%   |
| Sony SVE1511C5E                          | 1         | 1.28%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.28%   |
| SLIMBOOK ESSENTIAL-15-11                 | 1         | 1.28%   |
| Samsung 530U3C/530U4C/532U3C             | 1         | 1.28%   |
| ReachingTech DreamQuest Pro 2022         | 1         | 1.28%   |
| Razer Blade Stealth                      | 1         | 1.28%   |
| Packard Bell DOT S                       | 1         | 1.28%   |
| MSI GE75 Raider 10SGS                    | 1         | 1.28%   |
| Lenovo Yoga 2 13 20344                   | 1         | 1.28%   |
| Lenovo ThinkPad X270 20HMS06Q1D          | 1         | 1.28%   |
| Lenovo ThinkPad X200 745969G             | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES53R00 | 1         | 1.28%   |
| Lenovo ThinkPad T61 765912G              | 1         | 1.28%   |
| Lenovo ThinkPad T470s 20HGS3AX02         | 1         | 1.28%   |
| Lenovo ThinkPad T440p 20AWS1CH00         | 1         | 1.28%   |
| Lenovo ThinkPad T440p 20AW007QMS         | 1         | 1.28%   |
| Lenovo ThinkPad L590 20Q7000YSP          | 1         | 1.28%   |
| Lenovo ThinkPad L450 20DSS1S402          | 1         | 1.28%   |
| Lenovo ThinkPad L440 20ASS0FP00          | 1         | 1.28%   |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 1.28%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW     | 1         | 1.28%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 1         | 1.28%   |
| Lenovo IdeaPad 3 15ADA05 81W1            | 1         | 1.28%   |
| Lenovo G50-80 80E5                       | 1         | 1.28%   |
| HP Stream Notebook PC 11                 | 1         | 1.28%   |
| HP ProBook 4540s                         | 1         | 1.28%   |
| HP ProBook 4340s                         | 1         | 1.28%   |
| HP ProBook 430 G7                        | 1         | 1.28%   |
| HP Pavilion dv6                          | 1         | 1.28%   |
| HP Pavilion dv4                          | 1         | 1.28%   |
| HP Pavilion dv3500                       | 1         | 1.28%   |
| HP OMEN Laptop 15-en1xxx                 | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 12        | 15.38%  |
| HP Pavilion              | 5         | 6.41%   |
| Dell Latitude            | 4         | 5.13%   |
| Acer Aspire              | 4         | 5.13%   |
| HP ProBook               | 3         | 3.85%   |
| HP OMEN                  | 3         | 3.85%   |
| Unknown                  | 3         | 3.85%   |
| Lenovo IdeaPad           | 2         | 2.56%   |
| HP Laptop                | 2         | 2.56%   |
| ASUS K55VD               | 2         | 2.56%   |
| Apple MacBook5           | 2         | 2.56%   |
| TWINHEAD U12CT           | 1         | 1.28%   |
| TUXEDO Aura              | 1         | 1.28%   |
| Toshiba Satellite        | 1         | 1.28%   |
| Toshiba Portable         | 1         | 1.28%   |
| Sony SVE1511C5E          | 1         | 1.28%   |
| SLIMBOOK PROX-AMD5       | 1         | 1.28%   |
| SLIMBOOK ESSENTIAL-15-11 | 1         | 1.28%   |
| Samsung 530U3C           | 1         | 1.28%   |
| ReachingTech DreamQuest  | 1         | 1.28%   |
| Razer Blade              | 1         | 1.28%   |
| Packard Bell DOT         | 1         | 1.28%   |
| MSI GE75                 | 1         | 1.28%   |
| Lenovo Yoga              | 1         | 1.28%   |
| Lenovo G50-80            | 1         | 1.28%   |
| HP Stream                | 1         | 1.28%   |
| HP EliteBook             | 1         | 1.28%   |
| HP Compaq                | 1         | 1.28%   |
| HP 250                   | 1         | 1.28%   |
| Dell XPS                 | 1         | 1.28%   |
| Dell Studio              | 1         | 1.28%   |
| Dell Precision           | 1         | 1.28%   |
| Dell Inspiron            | 1         | 1.28%   |
| AZW BT3                  | 1         | 1.28%   |
| ASUS X556UJ              | 1         | 1.28%   |
| ASUS U33Jc               | 1         | 1.28%   |
| ASUS TUF                 | 1         | 1.28%   |
| ASUS ASUS                | 1         | 1.28%   |
| ASUS 1215B               | 1         | 1.28%   |
| ASUS 1201N               | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 14        | 17.95%  |
| 2022 | 8         | 10.26%  |
| 2019 | 7         | 8.97%   |
| 2012 | 6         | 7.69%   |
| 2009 | 6         | 7.69%   |
| 2014 | 5         | 6.41%   |
| 2018 | 4         | 5.13%   |
| 2016 | 4         | 5.13%   |
| 2011 | 4         | 5.13%   |
| 2008 | 4         | 5.13%   |
| 2017 | 3         | 3.85%   |
| 2010 | 3         | 3.85%   |
| 2023 | 2         | 2.56%   |
| 2021 | 2         | 2.56%   |
| 2015 | 2         | 2.56%   |
| 2013 | 2         | 2.56%   |
| 2007 | 2         | 2.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 36.25%  |
| 4.01-8.0    | 19        | 23.75%  |
| 16.01-24.0  | 19        | 23.75%  |
| 32.01-64.0  | 6         | 7.5%    |
| 2.01-3.0    | 3         | 3.75%   |
| 3.01-4.0    | 2         | 2.5%    |
| 24.01-32.0  | 1         | 1.25%   |
| 64.01-256.0 | 1         | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 41        | 49.4%   |
| 0.51-1.0 | 27        | 32.53%  |
| 1.01-2.0 | 9         | 10.84%  |
| 2.01-3.0 | 5         | 6.02%   |
| Unknown  | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 66.67%  |
| 2      | 16        | 19.75%  |
| 0      | 8         | 9.88%   |
| 3      | 2         | 2.47%   |
| 4      | 1         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 75.95%  |
| Yes       | 19        | 24.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 87.18%  |
| No        | 10        | 12.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 96.15%  |
| No        | 3         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 79.49%  |
| No        | 16        | 20.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 78        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Madrid                        | 13        | 14.61%  |
| Barcelona                     | 8         | 8.99%   |
| Valencia                      | 4         | 4.49%   |
| Terrassa                      | 3         | 3.37%   |
| Navalcarnero                  | 3         | 3.37%   |
| Tarragona                     | 2         | 2.25%   |
| Santa Cruz de Tenerife        | 2         | 2.25%   |
| Redondela                     | 2         | 2.25%   |
| Paterna                       | 2         | 2.25%   |
| GibraleГіn                  | 2         | 2.25%   |
| Alcobendas                    | 2         | 2.25%   |
| Zarautz                       | 1         | 1.12%   |
| Zaragoza                      | 1         | 1.12%   |
| Vitoria-Gasteiz               | 1         | 1.12%   |
| Villapresente                 | 1         | 1.12%   |
| Urnieta                       | 1         | 1.12%   |
| Tudela de Duero               | 1         | 1.12%   |
| Torrent                       | 1         | 1.12%   |
| Seville                       | 1         | 1.12%   |
| Sedavi                        | 1         | 1.12%   |
| Santa Coloma de Farners       | 1         | 1.12%   |
| Sanlucar la Mayor             | 1         | 1.12%   |
| San Vicent del Raspeig        | 1         | 1.12%   |
| San SebastiÃ¡n de los Reyes | 1         | 1.12%   |
| San Juan de Aznalfarache      | 1         | 1.12%   |
| Rubí                         | 1         | 1.12%   |
| Padul                         | 1         | 1.12%   |
| Ourense                       | 1         | 1.12%   |
| Orihuela Costa                | 1         | 1.12%   |
| Málaga                       | 1         | 1.12%   |
| Los Realejos                  | 1         | 1.12%   |
| LogroГ±o                    | 1         | 1.12%   |
| LogroÃ±o                    | 1         | 1.12%   |
| Laguna de Duero               | 1         | 1.12%   |
| La Pobla de Farnals           | 1         | 1.12%   |
| Ibiza Town                    | 1         | 1.12%   |
| Godella                       | 1         | 1.12%   |
| Girona                        | 1         | 1.12%   |
| Fuenterrabia                  | 1         | 1.12%   |
| Esparragosa de Lares          | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Samsung Electronics                    | 17        | 33     | 18.48%  |
| WDC                                    | 10        | 12     | 10.87%  |
| Kingston                               | 7         | 8      | 7.61%   |
| NVMe                                   | 6         | 9      | 6.52%   |
| Crucial                                | 6         | 6      | 6.52%   |
| Toshiba                                | 5         | 7      | 5.43%   |
| Hitachi                                | 5         | 5      | 5.43%   |
| Seagate                                | 4         | 4      | 4.35%   |
| SanDisk                                | 4         | 4      | 4.35%   |
| Intel                                  | 3         | 3      | 3.26%   |
| HGST                                   | 3         | 3      | 3.26%   |
| Product:              USB Flash Memory | 2         | 2      | 2.17%   |
| OCZ                                    | 2         | 2      | 2.17%   |
| Micron Technology                      | 2         | 2      | 2.17%   |
| Fujitsu                                | 2         | 2      | 2.17%   |
| XrayDisk                               | 1         | 1      | 1.09%   |
| Union Memory                           | 1         | 1      | 1.09%   |
| Transcend                              | 1         | 1      | 1.09%   |
| TCSUNBOW                               | 1         | 1      | 1.09%   |
| SK hynix                               | 1         | 1      | 1.09%   |
| PNY                                    | 1         | 1      | 1.09%   |
| Netac                                  | 1         | 1      | 1.09%   |
| LITEONIT                               | 1         | 1      | 1.09%   |
| Kston                                  | 1         | 2      | 1.09%   |
| KIOXIA                                 | 1         | 1      | 1.09%   |
| KingSpec                               | 1         | 1      | 1.09%   |
| Intenso                                | 1         | 1      | 1.09%   |
| China                                  | 1         | 1      | 1.09%   |
| Apple                                  | 1         | 1      | 1.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Product:              USB Flash Memory USB Flash Memory 16GB | 2         | 2.04%   |
| NVMe Samsung SSD 980 1TB                                     | 2         | 2.04%   |
| Kingston SA400S37240G 240GB                                  | 2         | 2.04%   |
| Crucial CT480BX500SSD1 480GB                                 | 2         | 2.04%   |
| XrayDisk SSD 240GB                                           | 1         | 1.02%   |
| WDC WDS100T2B0C-00PXH0 1TB                                   | 1         | 1.02%   |
| WDC WD5000LPVX-22V0TT0 500GB                                 | 1         | 1.02%   |
| WDC WD5000LPCX-21VHAT0 500GB                                 | 1         | 1.02%   |
| WDC WD2500BEVT-35A23T0 250GB                                 | 1         | 1.02%   |
| WDC WD1200BEVS-22UST0 120GB                                  | 1         | 1.02%   |
| WDC WD10JPCX-24UE4T0 1TB                                     | 1         | 1.02%   |
| WDC WD10EZEX-60WN4A0 1TB                                     | 1         | 1.02%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB                           | 1         | 1.02%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB                           | 1         | 1.02%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB                         | 1         | 1.02%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB                         | 1         | 1.02%   |
| Union Memory UMIS LENSE40256GMSP34MESTB3A 256GB              | 1         | 1.02%   |
| Transcend TS120GMTS420S 120GB                                | 1         | 1.02%   |
| Toshiba MQ01ABD100 1TB                                       | 1         | 1.02%   |
| Toshiba MK5065GSXF 500GB                                     | 1         | 1.02%   |
| Toshiba MK1229GSG 120GB                                      | 1         | 1.02%   |
| Toshiba MK1059GSM 1TB                                        | 1         | 1.02%   |
| Toshiba KXG60ZNV512G NVMe 512GB                              | 1         | 1.02%   |
| TCSUNBOW X3 480GB                                            | 1         | 1.02%   |
| SK hynix HFM512GDHTNG-8710B 512GB                            | 1         | 1.02%   |
| Seagate ST9500325AS 500GB                                    | 1         | 1.02%   |
| Seagate ST500LM021-1KJ152 500GB                              | 1         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB                               | 1         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                           | 1         | 1.02%   |
| SanDisk SSD PLUS 240GB                                       | 1         | 1.02%   |
| SanDisk SSD i100 24GB                                        | 1         | 1.02%   |
| SanDisk SDSSDP128G 128GB                                     | 1         | 1.02%   |
| SanDisk SD9SN8W-256G-1006 256GB                              | 1         | 1.02%   |
| Samsung SSD 980 500GB                                        | 1         | 1.02%   |
| Samsung SSD 970 EVO Plus 2TB                                 | 1         | 1.02%   |
| Samsung SSD 970 EVO 250GB                                    | 1         | 1.02%   |
| Samsung SSD 870 QVO 8TB                                      | 1         | 1.02%   |
| Samsung SSD 870 EVO 1TB                                      | 1         | 1.02%   |
| Samsung SSD 860 PRO 512GB                                    | 1         | 1.02%   |
| Samsung SSD 860 EVO 500GB                                    | 1         | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| WDC                                    | 6         | 7      | 19.35%  |
| Hitachi                                | 5         | 5      | 16.13%  |
| Toshiba                                | 4         | 5      | 12.9%   |
| Seagate                                | 4         | 4      | 12.9%   |
| NVMe                                   | 3         | 5      | 9.68%   |
| HGST                                   | 3         | 3      | 9.68%   |
| Samsung Electronics                    | 2         | 2      | 6.45%   |
| Product:              USB Flash Memory | 2         | 2      | 6.45%   |
| Fujitsu                                | 2         | 2      | 6.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 16     | 22.5%   |
| Kingston            | 6         | 7      | 15%     |
| SanDisk             | 4         | 4      | 10%     |
| Crucial             | 4         | 4      | 10%     |
| OCZ                 | 2         | 2      | 5%      |
| NVMe                | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| XrayDisk            | 1         | 1      | 2.5%    |
| Transcend           | 1         | 1      | 2.5%    |
| TCSUNBOW            | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| Kston               | 1         | 2      | 2.5%    |
| KingSpec            | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 38        | 49     | 42.7%   |
| HDD  | 30        | 35     | 33.71%  |
| NVMe | 21        | 33     | 23.6%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 84     | 73.08%  |
| NVMe | 21        | 33     | 26.92%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 64     | 78.13%  |
| 0.51-1.0   | 12        | 16     | 18.75%  |
| 1.01-2.0   | 1         | 3      | 1.56%   |
| 4.01-10.0  | 1         | 1      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 31        | 36.47%  |
| 101-250    | 27        | 31.76%  |
| 251-500    | 15        | 17.65%  |
| 501-1000   | 4         | 4.71%   |
| 21-50      | 3         | 3.53%   |
| 1001-2000  | 3         | 3.53%   |
| 51-100     | 2         | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 72        | 90%     |
| 21-50    | 3         | 3.75%   |
| 51-100   | 3         | 3.75%   |
| 251-500  | 1         | 1.25%   |
| 501-1000 | 1         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                    | 1         | 1      | 6.67%   |
| WDC WD2500BEVT-35A23T0 250GB                    | 1         | 1      | 6.67%   |
| Toshiba MK1229GSG 120GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                           | 1         | 1      | 6.67%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 6.67%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 6.67%   |
| OCZ AGILITY3 120GB                              | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                   | 1         | 1      | 6.67%   |
| Hitachi HTS543232L9SA00 320GB                   | 1         | 1      | 6.67%   |
| Hitachi HTS542525K9A300 250GB                   | 1         | 1      | 6.67%   |
| Hitachi HTS542516K9SA00 160GB                   | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB                      | 1         | 1      | 6.67%   |
| Fujitsu MHZ2250BH G2 250GB                      | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 26.67%  |
| WDC                 | 2         | 2      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Seagate             | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| OCZ                 | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 30.77%  |
| WDC                 | 2         | 2      | 15.38%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Seagate             | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 86.67%  |
| SSD  | 2         | 2      | 13.33%  |

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
| Works    | 60        | 91     | 74.07%  |
| Malfunc  | 15        | 15     | 18.52%  |
| Detected | 6         | 11     | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 48        | 54.55%  |
| Samsung Electronics         | 11        | 12.5%   |
| AMD                         | 6         | 6.82%   |
| SanDisk                     | 5         | 5.68%   |
| Nvidia                      | 5         | 5.68%   |
| Micron/Crucial Technology   | 3         | 3.41%   |
| SK hynix                    | 2         | 2.27%   |
| Kingston Technology Company | 2         | 2.27%   |
| Union Memory (Shenzhen)     | 1         | 1.14%   |
| Toshiba                     | 1         | 1.14%   |
| Silicon Motion              | 1         | 1.14%   |
| Phison Electronics          | 1         | 1.14%   |
| Micron Technology           | 1         | 1.14%   |
| KIOXIA                      | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 6.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 5.1%    |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 4.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 4.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 4.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 3.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 3.06%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 3.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 3.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 3.06%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 2.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 2.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.04%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.04%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 256GB                          | 1         | 1.02%   |
| Toshiba XG6 NVMe SSD Controller                                                | 1         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 1.02%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1         | 1.02%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 1.02%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.02%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 1.02%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 1.02%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 1.02%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.02%   |
| Nvidia MCP79 SATA Controller                                                   | 1         | 1.02%   |
| Micron/Crucial T500 NVMe PCIe SSD                                              | 1         | 1.02%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 1         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 1.02%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 1         | 1.02%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 1         | 1.02%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 1         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 56        | 60.22%  |
| NVMe | 26        | 27.96%  |
| IDE  | 7         | 7.53%   |
| RAID | 4         | 4.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 66        | 84.62%  |
| AMD    | 12        | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 2.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 2.56%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 2         | 2.56%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz    | 2         | 2.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 2.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 2         | 2.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 1         | 1.28%   |
| Intel Pentium CPU B970 @ 2.30GHz        | 1         | 1.28%   |
| Intel Other                             | 1         | 1.28%   |
| Intel CPU Version                       | 1         | 1.28%   |
| Intel Core i9-10980HK CPU @ 2.40GHz     | 1         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 1.28%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.28%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.28%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz      | 1         | 1.28%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 1         | 1.28%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 1         | 1.28%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 1         | 1.28%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 1         | 1.28%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 1         | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 1.28%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 1         | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 1.28%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 1.28%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 1         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.28%   |
| Intel Core i5-2537M CPU @ 1.40GHz       | 1         | 1.28%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 1         | 1.28%   |
| Intel Core i5 CPU U 560 @ 1.33GHz       | 1         | 1.28%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 1         | 1.28%   |
| Intel Core i3-4010U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 1         | 1.28%   |
| Intel Core i3 CPU M 370 @ 2.40GH        | 1         | 1.28%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 18        | 23.08%  |
| Intel Core i7      | 14        | 17.95%  |
| Intel Core 2 Duo   | 10        | 12.82%  |
| Other              | 7         | 8.97%   |
| Intel Celeron      | 7         | 8.97%   |
| AMD Ryzen 7        | 6         | 7.69%   |
| Intel Core i3      | 4         | 5.13%   |
| Intel Atom         | 3         | 3.85%   |
| AMD Ryzen 5        | 2         | 2.56%   |
| Intel Pentium Dual | 1         | 1.28%   |
| Intel Pentium      | 1         | 1.28%   |
| Intel Core i9      | 1         | 1.28%   |
| AMD Sempron        | 1         | 1.28%   |
| AMD E              | 1         | 1.28%   |
| AMD Athlon         | 1         | 1.28%   |
| AMD A4             | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 31        | 39.74%  |
| 4       | 23        | 29.49%  |
| Unknown | 11        | 14.1%   |
| 8       | 5         | 6.41%   |
| 16      | 3         | 3.85%   |
| 12      | 2         | 2.56%   |
| 6       | 2         | 2.56%   |
| 1       | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 73        | 93.59%  |
| 2       | 4         | 5.13%   |
| Unknown | 1         | 1.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 53.85%  |
| 1       | 25        | 32.05%  |
| Unknown | 11        | 14.1%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 12        | 15.38%  |
| Penryn          | 9         | 11.54%  |
| Haswell         | 7         | 8.97%   |
| IvyBridge       | 5         | 6.41%   |
| TigerLake       | 4         | 5.13%   |
| Skylake         | 4         | 5.13%   |
| Silvermont      | 4         | 5.13%   |
| Core            | 4         | 5.13%   |
| Unknown         | 4         | 5.13%   |
| Zen+            | 3         | 3.85%   |
| Zen 2           | 3         | 3.85%   |
| SandyBridge     | 3         | 3.85%   |
| CometLake       | 3         | 3.85%   |
| Broadwell       | 3         | 3.85%   |
| Zen 3           | 2         | 2.56%   |
| Westmere        | 2         | 2.56%   |
| Bonnell         | 2         | 2.56%   |
| K8 & K10 hybrid | 1         | 1.28%   |
| Goldmont plus   | 1         | 1.28%   |
| Excavator       | 1         | 1.28%   |
| Bobcat          | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 59.57%  |
| Nvidia | 21        | 22.34%  |
| AMD    | 17        | 18.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.1%    |
| Intel UHD Graphics 620                                                                   | 4         | 4.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 4.08%   |
| Intel HD Graphics 620                                                                    | 4         | 4.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 4.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 3.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 3.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 3.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3.06%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 3.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2.04%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 2.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 2.04%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 2.04%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.04%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.04%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.04%   |
| Intel HD Graphics 530                                                                    | 2         | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.04%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 1.02%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 1.02%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 1.02%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.02%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 1.02%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.02%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.02%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 1.02%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.02%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 1         | 1.02%   |
| Nvidia C79 [GeForce 9400M / ION]                                                         | 1         | 1.02%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 1.02%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.02%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 49.37%  |
| 1 x AMD        | 10        | 12.66%  |
| Intel + Nvidia | 9         | 11.39%  |
| 1 x Nvidia     | 7         | 8.86%   |
| 2 x Intel      | 6         | 7.59%   |
| AMD + Nvidia   | 4         | 5.06%   |
| Intel + AMD    | 3         | 3.8%    |
| 2 x Nvidia     | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 71        | 88.75%  |
| Proprietary | 7         | 8.75%   |
| Unknown     | 2         | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 85.37%  |
| 0.01-0.5   | 7         | 8.54%   |
| 1.01-2.0   | 2         | 2.44%   |
| 7.01-8.0   | 1         | 1.22%   |
| 5.01-6.0   | 1         | 1.22%   |
| 2.01-3.0   | 1         | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 18.64%  |
| Chimei Innolux          | 7         | 11.86%  |
| BOE                     | 7         | 11.86%  |
| LG Display              | 5         | 8.47%   |
| Chi Mei Optoelectronics | 4         | 6.78%   |
| Apple                   | 4         | 6.78%   |
| Samsung Electronics     | 3         | 5.08%   |
| Lenovo                  | 3         | 5.08%   |
| BenQ                    | 3         | 5.08%   |
| Sharp                   | 2         | 3.39%   |
| PANDA                   | 2         | 3.39%   |
| Hewlett-Packard         | 2         | 3.39%   |
| Mi                      | 1         | 1.69%   |
| LGD                     | 1         | 1.69%   |
| LG Philips              | 1         | 1.69%   |
| Fujitsu Siemens         | 1         | 1.69%   |
| AOC                     | 1         | 1.69%   |
| Acer                    | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO462D 1920x1080 290x170mm 13.2-inch           | 3         | 5%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 2         | 3.33%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                       | 2         | 3.33%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch                  | 1         | 1.67%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                  | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 340x190mm 15.3-inch     | 1         | 1.67%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.67%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                  | 1         | 1.67%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                         | 1         | 1.67%   |
| LGD LCD Monitor 5760x1080                                                | 1         | 1.67%   |
| LG Philips LCD Monitor LPL0120 1280x800 330x210mm 15.4-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD066E 1920x1080 340x190mm 15.3-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch              | 1         | 1.67%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch             | 1         | 1.67%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 1         | 1.67%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.67%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch               | 1         | 1.67%   |
| Hewlett-Packard 22er HWP331B 1920x1080 500x300mm 23.0-inch               | 1         | 1.67%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 340x190mm 15.3-inch         | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.67%   |
| Chimei Innolux LCD Monitor CMN1136 1366x768 260x140mm 11.6-inch          | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 340x190mm 15.3-inch | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 350x190mm 15.7-inch | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 300x190mm 14.0-inch | 1         | 1.67%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 220x120mm 9.9-inch  | 1         | 1.67%   |
| BOE LCD Monitor BOE0960 1366x768 340x190mm 15.3-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE08A6 1920x1080 290x170mm 13.2-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 1.67%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 1.67%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 1         | 1.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 24        | 42.11%  |
| 1366x768 (WXGA)  | 16        | 28.07%  |
| 1280x800 (WXGA)  | 8         | 14.04%  |
| 3840x2160 (4K)   | 2         | 3.51%   |
| 1600x900 (HD+)   | 2         | 3.51%   |
| 5760x1080        | 1         | 1.75%   |
| 1440x900 (WXGA+) | 1         | 1.75%   |
| 1280x1024 (SXGA) | 1         | 1.75%   |
| 1024x600         | 1         | 1.75%   |
| Unknown          | 1         | 1.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 25        | 42.37%  |
| 13      | 17        | 28.81%  |
| 24      | 4         | 6.78%   |
| 12      | 3         | 5.08%   |
| 27      | 2         | 3.39%   |
| 19      | 2         | 3.39%   |
| 14      | 2         | 3.39%   |
| 23      | 1         | 1.69%   |
| 11      | 1         | 1.69%   |
| 9       | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 52.54%  |
| 201-300     | 18        | 30.51%  |
| 501-600     | 6         | 10.17%  |
| 401-500     | 2         | 3.39%   |
| 351-400     | 1         | 1.69%   |
| Unknown     | 1         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 44        | 80%     |
| 16/10   | 8         | 14.55%  |
| 5/4     | 1         | 1.82%   |
| 3/2     | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 22        | 37.29%  |
| 81-90          | 12        | 20.34%  |
| 71-80          | 7         | 11.86%  |
| 201-250        | 5         | 8.47%   |
| 61-70          | 3         | 5.08%   |
| 101-110        | 3         | 5.08%   |
| 301-350        | 2         | 3.39%   |
| 151-200        | 2         | 3.39%   |
| 51-60          | 1         | 1.69%   |
| 41-50          | 1         | 1.69%   |
| Unknown        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 33.9%   |
| 101-120       | 19        | 32.2%   |
| 51-100        | 11        | 18.64%  |
| 161-240       | 6         | 10.17%  |
| More than 240 | 2         | 3.39%   |
| Unknown       | 1         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 69.51%  |
| 0     | 20        | 24.39%  |
| 2     | 5         | 6.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 43        | 32.58%  |
| Intel                             | 42        | 31.82%  |
| Qualcomm Atheros                  | 13        | 9.85%   |
| Broadcom                          | 12        | 9.09%   |
| Nvidia                            | 4         | 3.03%   |
| TP-Link                           | 2         | 1.52%   |
| Sierra Wireless                   | 2         | 1.52%   |
| Ralink Technology                 | 2         | 1.52%   |
| Ralink                            | 2         | 1.52%   |
| MediaTek                          | 2         | 1.52%   |
| Marvell Technology Group          | 2         | 1.52%   |
| D-Link System                     | 2         | 1.52%   |
| Xiaomi                            | 1         | 0.76%   |
| IMC Networks                      | 1         | 0.76%   |
| Huawei Technologies               | 1         | 0.76%   |
| Ericsson Business Mobile Networks | 1         | 0.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 34        | 21.25%  |
| Intel Wi-Fi 6 AX200                                                        | 6         | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 5         | 3.13%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                                      | 5         | 3.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4         | 2.5%    |
| Nvidia MCP79 Ethernet                                                      | 4         | 2.5%    |
| Intel Wireless 7265                                                        | 4         | 2.5%    |
| Intel Wireless 7260                                                        | 4         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 1.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 1.88%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 1.88%   |
| Intel Ethernet Connection I217-LM                                          | 3         | 1.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 1.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 1.88%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 1.25%   |
| Intel Wireless 3160                                                        | 2         | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.25%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                                   | 2         | 1.25%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 1.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1         | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 0.63%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 0.63%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.63%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 47.67%  |
| Realtek Semiconductor | 12        | 13.95%  |
| Broadcom              | 11        | 12.79%  |
| Qualcomm Atheros      | 9         | 10.47%  |
| TP-Link               | 2         | 2.33%   |
| Sierra Wireless       | 2         | 2.33%   |
| Ralink Technology     | 2         | 2.33%   |
| Ralink                | 2         | 2.33%   |
| MediaTek              | 2         | 2.33%   |
| D-Link System         | 2         | 2.33%   |
| IMC Networks          | 1         | 1.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 6         | 6.74%   |
| Intel Wireless 8265 / 8275                                                 | 5         | 5.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4         | 4.49%   |
| Intel Wireless 7265                                                        | 4         | 4.49%   |
| Intel Wireless 7260                                                        | 4         | 4.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 3.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 3         | 3.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 3         | 3.37%   |
| Intel Wi-Fi 6 AX201                                                        | 3         | 3.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 3.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 3.37%   |
| Sierra Wireless EM7345 4G LTE                                              | 2         | 2.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 2         | 2.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 2.25%   |
| Intel Wireless 3160                                                        | 2         | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 2.25%   |
| Intel Centrino Advanced-N 6235                                             | 2         | 2.25%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 1         | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 1.12%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 1.12%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 1.12%   |
| Intel Wireless 8260                                                        | 1         | 1.12%   |
| Intel Wireless 3165                                                        | 1         | 1.12%   |
| Intel WiFi Link 5100                                                       | 1         | 1.12%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 1         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 56.52%  |
| Intel                    | 18        | 26.09%  |
| Qualcomm Atheros         | 4         | 5.8%    |
| Nvidia                   | 4         | 5.8%    |
| Marvell Technology Group | 2         | 2.9%    |
| Xiaomi                   | 1         | 1.45%   |
| Broadcom                 | 1         | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 34        | 49.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 7.25%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 7.25%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 5.8%    |
| Intel Ethernet Connection I217-LM                                      | 3         | 4.35%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.45%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 1.45%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 1         | 1.45%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.45%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1.45%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1.45%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.45%   |
| Intel 82566MC Gigabit Network Connection                               | 1         | 1.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 51.72%  |
| Ethernet | 68        | 46.9%   |
| Modem    | 2         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 44        | 50.57%  |
| Ethernet | 42        | 48.28%  |
| Modem    | 1         | 1.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 63        | 80.77%  |
| 1     | 12        | 15.38%  |
| 6     | 1         | 1.28%   |
| 3     | 1         | 1.28%   |
| 0     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 97.44%  |
| Yes  | 2         | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 50.79%  |
| Realtek Semiconductor           | 7         | 11.11%  |
| Apple                           | 5         | 7.94%   |
| IMC Networks                    | 3         | 4.76%   |
| Hewlett-Packard                 | 3         | 4.76%   |
| Foxconn / Hon Hai               | 3         | 4.76%   |
| Broadcom                        | 3         | 4.76%   |
| Ralink                          | 2         | 3.17%   |
| Qualcomm Atheros Communications | 2         | 3.17%   |
| Cambridge Silicon Radio         | 2         | 3.17%   |
| ASUSTek Computer                | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 26.56%  |
| Intel AX200 Bluetooth                                       | 6         | 9.38%   |
| Intel AX201 Bluetooth                                       | 5         | 7.81%   |
| Realtek Bluetooth Adapter                                   | 3         | 4.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 4.69%   |
| Realtek Bluetooth 4.2 Adapter                               | 2         | 3.13%   |
| Ralink RT3290 Bluetooth                                     | 2         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 3.13%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 3.13%   |
| Apple Bluetooth Host Controller                             | 2         | 3.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.56%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.56%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.56%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 1.56%   |
| IMC Networks Bluetooth module                               | 1         | 1.56%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.56%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.56%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.56%   |
| Apple Broadcom Built-in Bluetooth                           | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 60        | 64.52%  |
| Nvidia                                       | 14        | 15.05%  |
| AMD                                          | 14        | 15.05%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 2.15%   |
| Texas Instruments                            | 1         | 1.08%   |
| Generalplus Technology                       | 1         | 1.08%   |
| C-Media Electronics                          | 1         | 1.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 8.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 6.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 5.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.64%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.73%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.73%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 1.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.82%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.82%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 1.82%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.82%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 0.91%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.91%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.91%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.91%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 26.19%  |
| SK hynix            | 16        | 19.05%  |
| Micron Technology   | 10        | 11.9%   |
| Kingston            | 9         | 10.71%  |
| Crucial             | 6         | 7.14%   |
| Unknown             | 4         | 4.76%   |
| Unknown             | 3         | 3.57%   |
| Ramaxel Technology  | 3         | 3.57%   |
| Elpida              | 2         | 2.38%   |
| A-DATA Technology   | 2         | 2.38%   |
| Unknown (ABCD)      | 1         | 1.19%   |
| Unknown (0x0080)    | 1         | 1.19%   |
| Transcend           | 1         | 1.19%   |
| Nanya Technology    | 1         | 1.19%   |
| G.Skill             | 1         | 1.19%   |
| Corsair             | 1         | 1.19%   |
| ASint Technology    | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 4         | 4.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 2.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 2.13%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s                    | 2         | 2.13%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 2.13%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s                    | 2         | 2.13%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 2         | 2.13%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 1         | 1.06%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.06%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.06%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3733MT/s                      | 1         | 1.06%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                      | 1         | 1.06%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                              | 1         | 1.06%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s                     | 1         | 1.06%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.06%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB Row Of Chips DDR4 3200MT/s             | 1         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.06%   |
| SK hynix RAM 161616161616161616161616161616161616 2GB SODIMM DDR2 800MT/s | 1         | 1.06%   |
| SK hynix RAM 080808080808080808080808080808080808 2GB SODIMM DDR2 800MT/s | 1         | 1.06%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                            | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 1.06%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 30        | 41.1%   |
| DDR4    | 27        | 36.99%  |
| DDR2    | 9         | 12.33%  |
| LPDDR4  | 3         | 4.11%   |
| LPDDR3  | 2         | 2.74%   |
| SDRAM   | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 93.15%  |
| Row Of Chips | 5         | 6.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 27        | 33.75%  |
| 8192  | 25        | 31.25%  |
| 2048  | 13        | 16.25%  |
| 16384 | 10        | 12.5%   |
| 1024  | 3         | 3.75%   |
| 32768 | 2         | 2.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 26.92%  |
| 3200    | 11        | 14.1%   |
| 2667    | 9         | 11.54%  |
| 2400    | 9         | 11.54%  |
| 667     | 7         | 8.97%   |
| 1067    | 4         | 5.13%   |
| 1334    | 3         | 3.85%   |
| 2133    | 2         | 2.56%   |
| 1867    | 2         | 2.56%   |
| 1333    | 2         | 2.56%   |
| 1066    | 2         | 2.56%   |
| 800     | 2         | 2.56%   |
| 4267    | 1         | 1.28%   |
| 3733    | 1         | 1.28%   |
| 2048    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Brother HL-L2340D series | 1         | 100%    |

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
| Chicony Electronics                    | 11        | 21.15%  |
| Sunplus Innovation Technology          | 7         | 13.46%  |
| Bison Electronics                      | 5         | 9.62%   |
| Realtek Semiconductor                  | 4         | 7.69%   |
| Quanta                                 | 4         | 7.69%   |
| Microdia                               | 4         | 7.69%   |
| Suyin                                  | 3         | 5.77%   |
| IMC Networks                           | 3         | 5.77%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| USB Camera                             | 1         | 1.92%   |
| Syntek                                 | 1         | 1.92%   |
| Supreme Electronics                    | 1         | 1.92%   |
| Silicon Motion                         | 1         | 1.92%   |
| Ricoh                                  | 1         | 1.92%   |
| Luxvisions Innotech Limited            | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Importek                               | 1         | 1.92%   |
| Alcor Micro                            | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 4         | 7.69%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 5.77%   |
| Quanta HP TrueVision HD Camera                                             | 3         | 5.77%   |
| Realtek USB Camera                                                         | 2         | 3.85%   |
| Bison Integrated Camera                                                    | 2         | 3.85%   |
| USB Camera USB Camera                                                      | 1         | 1.92%   |
| Syntek EasyCamera                                                          | 1         | 1.92%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 1.92%   |
| Suyin HP webcam [dv6-1190en]                                               | 1         | 1.92%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 1.92%   |
| Supreme Realtek PC Camera                                                  | 1         | 1.92%   |
| Sunplus Integrated Camera                                                  | 1         | 1.92%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 1.92%   |
| Sunplus HD WebCam                                                          | 1         | 1.92%   |
| Sunplus Asus Webcam                                                        | 1         | 1.92%   |
| Silicon Motion Realtek USB 2.0 PC Camera                                   | 1         | 1.92%   |
| Ricoh Integrated Webcam                                                    | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 1.92%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 1.92%   |
| Quanta Realtek DMFT RGB                                                    | 1         | 1.92%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 1.92%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.92%   |
| Microdia Integrated Webcam                                                 | 1         | 1.92%   |
| Microdia HP Webcam                                                         | 1         | 1.92%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 1.92%   |
| Lite-On Integrated Camera                                                  | 1         | 1.92%   |
| Importek HP Webcam                                                         | 1         | 1.92%   |
| IMC Networks Realtek PC Camera                                             | 1         | 1.92%   |
| IMC Networks Integrated Camera                                             | 1         | 1.92%   |
| IMC Networks 2M Integrated Webcam                                          | 1         | 1.92%   |
| Chicony WebCam                                                             | 1         | 1.92%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.92%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.92%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.92%   |
| Chicony Integrated IR Camera                                               | 1         | 1.92%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.92%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.92%   |
| Bison SunplusIT Integrated Camera                                          | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 53.33%  |
| STMicroelectronics         | 2         | 13.33%  |
| Upek                       | 1         | 6.67%   |
| Synaptics                  | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| Fingerprint Cards          | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                                  | 2         | 13.33%  |
| Validity Sensors VFS101 Fingerprint Reader               | 2         | 13.33%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 2         | 13.33%  |
| STMicroelectronics Fingerprint Reader                    | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                          | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                     | 1         | 6.67%   |
| Upek TCS5B Fingerprint sensor                            | 1         | 6.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                      | 1         | 6.67%   |
| Fingerprint Cards FPC Fingerprint Reader                 | 1         | 6.67%   |
| Elan Fingerprint Sensor                                  | 1         | 6.67%   |

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
| 1     | 31        | 36.05%  |
| 2     | 23        | 26.74%  |
| 3     | 15        | 17.44%  |
| 0     | 11        | 12.79%  |
| 4     | 5         | 5.81%   |
| 5     | 1         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 48        | 37.21%  |
| Net/wireless             | 23        | 17.83%  |
| Bluetooth                | 23        | 17.83%  |
| Card reader              | 13        | 10.08%  |
| Fingerprint reader       | 12        | 9.3%    |
| Graphics card            | 4         | 3.1%    |
| Firewire controller      | 3         | 2.33%   |
| Network                  | 2         | 1.55%   |
| Storage                  | 1         | 0.78%   |

