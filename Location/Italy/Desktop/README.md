BSD in Italy - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

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

Total: 119

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | ProLiant MicroServer Gen... | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| T-bao         | MINI PC V1.0                | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Pegatron      | Benicia                     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| Unknown       | Unknown                     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| Unknown       | Unknown                     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| HP            | 3397                        | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| Pegatron      | 2ACF                        | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| Dell          | 0TK7TF A00                  | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| PC Engines    | APU2                        | [54ada090c6](https://bsd-hardware.info/?probe=54ada090c6) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [8812a8e8c8](https://bsd-hardware.info/?probe=8812a8e8c8) | Dec 04, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| T-bao         | MINI PC V1.0                | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| Pegatron      | 2ACF                        | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| Acer          | Veriton X2610G              | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASRock        | B75M R2.0                   | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| Unknown       | YL-J3160L4                  | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Gigabyte      | P55A-UD3                    | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| Unknown       | Unknown                     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | [de8a18ca09](https://bsd-hardware.info/?probe=de8a18ca09) | Apr 08, 2021 |
| Unknown       | Unknown                     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [78a7c7b8cb](https://bsd-hardware.info/?probe=78a7c7b8cb) | Mar 23, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 0R849J A00                  | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Foxconn       | 2ADA                        | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| Intel         | MAHOBAY                     | [c3dc05bbac](https://bsd-hardware.info/?probe=c3dc05bbac) | Feb 26, 2021 |
| Intel         | MAHOBAY                     | [7ab47e0db7](https://bsd-hardware.info/?probe=7ab47e0db7) | Feb 25, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Intel         | MAHOBAY                     | [5ecd568ce9](https://bsd-hardware.info/?probe=5ecd568ce9) | Feb 21, 2021 |
| Intel         | MAHOBAY                     | [138dbdcece](https://bsd-hardware.info/?probe=138dbdcece) | Feb 21, 2021 |
| Intel         | MAHOBAY                     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| HARDKERNEL    | ODROID-H2                   | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| Dell          | 06NWYK A00                  | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| Sun Micros... | Ultra 24 50                 | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| PC Engines    | apu2                        | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| MSI           | Boston                      | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| Unknown       | Unknown                     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | [afbbc44ac5](https://bsd-hardware.info/?probe=afbbc44ac5) | Nov 29, 2020 |
| Unknown       | Unknown                     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Intel         | D945GCLF2                   | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| ASRock        | 990FX Extreme9              | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.4.0    | 7        | 9.21%   |
| helloSystem 0.7.0    | 5        | 6.58%   |
| OPNsense 22.1        | 4        | 5.26%   |
| OPNsense 21.1        | 4        | 5.26%   |
| helloSystem 0.5.0    | 4        | 5.26%   |
| OPNsense 21.7.3      | 3        | 3.95%   |
| helloSystem 0.6.0    | 3        | 3.95%   |
| helloSystem 0.3.0    | 3        | 3.95%   |
| OPNsense 22.1.6      | 2        | 2.63%   |
| OPNsense 22.1.4      | 2        | 2.63%   |
| OPNsense 21.7.7      | 2        | 2.63%   |
| OPNsense 21.1.3      | 2        | 2.63%   |
| OPNsense 21.1.2      | 2        | 2.63%   |
| OPNsense 20.7.8      | 2        | 2.63%   |
| OpenBSD 7.1          | 2        | 2.63%   |
| OpenBSD 6.8          | 2        | 2.63%   |
| NomadBSD 1.4         | 2        | 2.63%   |
| FreeBSD 12.3-p1      | 2        | 2.63%   |
| OPNsense 22.1.8      | 1        | 1.32%   |
| OPNsense 22.1.7      | 1        | 1.32%   |
| OPNsense 22.1.3      | 1        | 1.32%   |
| OPNsense 22.1.2      | 1        | 1.32%   |
| OPNsense 21.7.8      | 1        | 1.32%   |
| OPNsense 21.7.6      | 1        | 1.32%   |
| OPNsense 21.7.4      | 1        | 1.32%   |
| OPNsense 21.7.1      | 1        | 1.32%   |
| OPNsense 21.7        | 1        | 1.32%   |
| OPNsense 21.1.8      | 1        | 1.32%   |
| OPNsense 21.1.7      | 1        | 1.32%   |
| OPNsense 21.1.5      | 1        | 1.32%   |
| OPNsense 21.1.1      | 1        | 1.32%   |
| NetBSD 9.99.77       | 1        | 1.32%   |
| NetBSD 9.1_STABLE    | 1        | 1.32%   |
| FreeBSD 13.0-p7      | 1        | 1.32%   |
| FreeBSD 13.0-p5      | 1        | 1.32%   |
| FreeBSD 13.0-CURRENT | 1        | 1.32%   |
| FreeBSD 12.2-STABLE  | 1        | 1.32%   |
| FreeBSD 12.2-p6      | 1        | 1.32%   |
| FreeBSD 12.2-p2      | 1        | 1.32%   |
| FreeBSD 12.1-p6      | 1        | 1.32%   |
| FreeBSD 12.1-p10     | 1        | 1.32%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 28       | 45.16%  |
| helloSystem | 16       | 25.81%  |
| FreeBSD     | 10       | 16.13%  |
| OpenBSD     | 4        | 6.45%   |
| NomadBSD    | 2        | 3.23%   |
| NetBSD      | 2        | 3.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 59       | 95.16%  |
| evbarm | 2        | 3.23%   |
| i386   | 1        | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 32       | 51.61%  |
| helloDesktop  | 17       | 27.42%  |
| XFCE          | 2        | 3.23%   |
| Openbox       | 2        | 3.23%   |
| MATE          | 2        | 3.23%   |
| fvwm          | 2        | 3.23%   |
| xfwm          | 1        | 1.61%   |
| TWM           | 1        | 1.61%   |
| KDE5          | 1        | 1.61%   |
| Enlightenment | 1        | 1.61%   |
| CTWM          | 1        | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 33       | 53.23%  |
| X11     | 29       | 46.77%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 40       | 64.52%  |
| SLiM    | 20       | 32.26%  |
| LightDM | 2        | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 36       | 58.06%  |
| en_US            | 17       | 27.42%  |
| it_IT            | 5        | 8.06%   |
| C                | 3        | 4.84%   |
| it_IT.ISO8859-15 | 1        | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 45       | 70.31%  |
| BIOS | 19       | 29.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 35       | 53.85%  |
| Zfs    | 22       | 33.85%  |
| Ffs    | 4        | 6.15%   |
| Cd9660 | 4        | 6.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 52       | 82.54%  |
| MBR     | 10       | 15.87%  |
| Unknown | 1        | 1.59%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 12       | 19.35%  |
| Intel                      | 6        | 9.68%   |
| Unknown                    | 6        | 9.68%   |
| PC Engines                 | 4        | 6.45%   |
| MSI                        | 4        | 6.45%   |
| Gigabyte Technology        | 4        | 6.45%   |
| Dell                       | 4        | 6.45%   |
| Hewlett-Packard            | 3        | 4.84%   |
| ASRock                     | 3        | 4.84%   |
| Pegatron                   | 2        | 3.23%   |
| Fujitsu                    | 2        | 3.23%   |
| Acer                       | 2        | 3.23%   |
| T-bao                      | 1        | 1.61%   |
| Supermicro                 | 1        | 1.61%   |
| Sun Microsystems           | 1        | 1.61%   |
| ShenZhen MinWin Technology | 1        | 1.61%   |
| Protectli                  | 1        | 1.61%   |
| MW                         | 1        | 1.61%   |
| Lenovo                     | 1        | 1.61%   |
| HARDKERNEL                 | 1        | 1.61%   |
| Foxconn                    | 1        | 1.61%   |
| AZW                        | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 6        | 9.68%   |
| PC Engines apu2                         | 3        | 4.84%   |
| Intel Q3XXG4-P V1.0                     | 3        | 4.84%   |
| MSI MS-7B86                             | 2        | 3.23%   |
| ASUS M4A88TD-V EVO/USB3                 | 2        | 3.23%   |
| ASUS IP4BL-ME                           | 2        | 3.23%   |
| T-bao MINI PC                           | 1        | 1.61%   |
| Supermicro X8STi                        | 1        | 1.61%   |
| Sun Microsystems Ultra 24               | 1        | 1.61%   |
| ShenZhen MinWin MW-NANO-APL-4L          | 1        | 1.61%   |
| Protectli FW4B                          | 1        | 1.61%   |
| Pegatron Pro 3405 Series                | 1        | 1.61%   |
| Pegatron KX629AA-ABZ a6561.it           | 1        | 1.61%   |
| PC Engines APU3                         | 1        | 1.61%   |
| MW GMLK-2_5G4L                          | 1        | 1.61%   |
| MSI NR074AA-ABZ CQ5125IT                | 1        | 1.61%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159) | 1        | 1.61%   |
| Lenovo ThinkCentre M83 10AHS35Q00       | 1        | 1.61%   |
| Intel MAHOBAY                           | 1        | 1.61%   |
| Intel D945GCLF2                         | 1        | 1.61%   |
| Intel D2500CC AAG81477-401              | 1        | 1.61%   |
| HP Z440 Workstation                     | 1        | 1.61%   |
| HP ProLiant MicroServer Gen8            | 1        | 1.61%   |
| HP Compaq Elite 8300 SFF                | 1        | 1.61%   |
| HARDKERNEL ODROID-H2                    | 1        | 1.61%   |
| Gigabyte X570 AORUS PRO                 | 1        | 1.61%   |
| Gigabyte X570 AORUS ELITE               | 1        | 1.61%   |
| Gigabyte P55A-UD3                       | 1        | 1.61%   |
| Gigabyte H270M-DS3H                     | 1        | 1.61%   |
| Fujitsu ESPRIMO E7936                   | 1        | 1.61%   |
| Fujitsu ESPRIMO E3521                   | 1        | 1.61%   |
| Foxconn p6-2305elm                      | 1        | 1.61%   |
| Dell Studio XPS 435MT                   | 1        | 1.61%   |
| Dell Precision T1600                    | 1        | 1.61%   |
| Dell OptiPlex FX160                     | 1        | 1.61%   |
| Dell Inspiron 3847                      | 1        | 1.61%   |
| AZW BT3 X                               | 1        | 1.61%   |
| ASUS PRIME Z390M-PLUS                   | 1        | 1.61%   |
| ASUS PRIME X470-PRO                     | 1        | 1.61%   |
| ASUS PRIME B550M-K                      | 1        | 1.61%   |
| ASUS P8Z77-V PRO/THUNDERBOLT            | 1        | 1.61%   |
| ASUS P8H61-M LE                         | 1        | 1.61%   |
| ASUS M4A87TD EVO                        | 1        | 1.61%   |
| ASUS IP4BL-ME-Oli                       | 1        | 1.61%   |
| ASUS BM6835_BM6635_BP6335               | 1        | 1.61%   |
| ASRock H81 Pro BTC                      | 1        | 1.61%   |
| ASRock B75M R2.0                        | 1        | 1.61%   |
| ASRock 990FX Extreme9                   | 1        | 1.61%   |
| Acer Veriton X2610G                     | 1        | 1.61%   |
| Acer Aspire M3900                       | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 6        | 9.68%   |
| PC Engines apu2                | 3        | 4.84%   |
| Intel Q3XXG4-P                 | 3        | 4.84%   |
| ASUS PRIME                     | 3        | 4.84%   |
| MSI MS-7B86                    | 2        | 3.23%   |
| Gigabyte X570                  | 2        | 3.23%   |
| Fujitsu ESPRIMO                | 2        | 3.23%   |
| ASUS M4A88TD-V                 | 2        | 3.23%   |
| ASUS IP4BL-ME                  | 2        | 3.23%   |
| T-bao MINI                     | 1        | 1.61%   |
| Supermicro X8STi               | 1        | 1.61%   |
| Sun Microsystems Ultra         | 1        | 1.61%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.61%   |
| Protectli FW4B                 | 1        | 1.61%   |
| Pegatron Pro                   | 1        | 1.61%   |
| Pegatron KX629AA-ABZ           | 1        | 1.61%   |
| PC Engines APU3                | 1        | 1.61%   |
| MW GMLK-2                      | 1        | 1.61%   |
| MSI NR074AA-ABZ                | 1        | 1.61%   |
| MSI KBL-U                      | 1        | 1.61%   |
| Lenovo ThinkCentre             | 1        | 1.61%   |
| Intel MAHOBAY                  | 1        | 1.61%   |
| Intel D945GCLF2                | 1        | 1.61%   |
| Intel D2500CC                  | 1        | 1.61%   |
| HP Z440                        | 1        | 1.61%   |
| HP ProLiant                    | 1        | 1.61%   |
| HP Compaq                      | 1        | 1.61%   |
| HARDKERNEL ODROID-H2           | 1        | 1.61%   |
| Gigabyte P55A-UD3              | 1        | 1.61%   |
| Gigabyte H270M-DS3H            | 1        | 1.61%   |
| Foxconn p6-2305elm             | 1        | 1.61%   |
| Dell Studio                    | 1        | 1.61%   |
| Dell Precision                 | 1        | 1.61%   |
| Dell OptiPlex                  | 1        | 1.61%   |
| Dell Inspiron                  | 1        | 1.61%   |
| AZW BT3                        | 1        | 1.61%   |
| ASUS P8Z77-V                   | 1        | 1.61%   |
| ASUS P8H61-M                   | 1        | 1.61%   |
| ASUS M4A87TD                   | 1        | 1.61%   |
| ASUS IP4BL-ME-Oli              | 1        | 1.61%   |
| ASUS BM6835                    | 1        | 1.61%   |
| ASRock H81                     | 1        | 1.61%   |
| ASRock B75M                    | 1        | 1.61%   |
| ASRock 990FX                   | 1        | 1.61%   |
| Acer Veriton                   | 1        | 1.61%   |
| Acer Aspire                    | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 9        | 14.52%  |
| 2010    | 7        | 11.29%  |
| 2012    | 6        | 9.68%   |
| 2020    | 5        | 8.06%   |
| 2019    | 5        | 8.06%   |
| 2011    | 5        | 8.06%   |
| 2008    | 5        | 8.06%   |
| 2018    | 4        | 6.45%   |
| 2017    | 3        | 4.84%   |
| 2014    | 3        | 4.84%   |
| 2009    | 3        | 4.84%   |
| 2021    | 2        | 3.23%   |
| Unknown | 2        | 3.23%   |
| 2022    | 1        | 1.61%   |
| 2015    | 1        | 1.61%   |
| 2013    | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 93.55%  |
| Yes  | 4        | 6.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 24       | 38.1%   |
| 4.01-8.0    | 16       | 25.4%   |
| 16.01-24.0  | 8        | 12.7%   |
| 2.01-3.0    | 6        | 9.52%   |
| 32.01-64.0  | 3        | 4.76%   |
| 24.01-32.0  | 2        | 3.17%   |
| 64.01-256.0 | 2        | 3.17%   |
| 3.01-4.0    | 1        | 1.59%   |
| 0.51-1.0    | 1        | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 41       | 65.08%  |
| 0.51-1.0 | 14       | 22.22%  |
| 1.01-2.0 | 4        | 6.35%   |
| Unknown  | 2        | 3.17%   |
| 4.01-8.0 | 1        | 1.59%   |
| 2.01-3.0 | 1        | 1.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 33       | 51.56%  |
| 2      | 15       | 23.44%  |
| 4      | 5        | 7.81%   |
| 3      | 5        | 7.81%   |
| 0      | 5        | 7.81%   |
| 10     | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 40       | 64.52%  |
| Yes       | 22       | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 96.77%  |
| No        | 2        | 3.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 80.65%  |
| Yes       | 12       | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 88.89%  |
| Yes       | 7        | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 62       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 14       | 19.44%  |
| Rome                  | 6        | 8.33%   |
| Naples                | 3        | 4.17%   |
| Turrivalignani        | 2        | 2.78%   |
| Silea                 | 2        | 2.78%   |
| Lucca                 | 2        | 2.78%   |
| Viterbo               | 1        | 1.39%   |
| Venice                | 1        | 1.39%   |
| Turin                 | 1        | 1.39%   |
| Trieste               | 1        | 1.39%   |
| Treviso               | 1        | 1.39%   |
| Terni                 | 1        | 1.39%   |
| Soresina              | 1        | 1.39%   |
| Sasso Marconi         | 1        | 1.39%   |
| Sannicandro di Bari   | 1        | 1.39%   |
| San Donato Milanese   | 1        | 1.39%   |
| Reggio Emilia         | 1        | 1.39%   |
| Ravenna               | 1        | 1.39%   |
| Ponsacco              | 1        | 1.39%   |
| Pistoia               | 1        | 1.39%   |
| Pioltello             | 1        | 1.39%   |
| Parma                 | 1        | 1.39%   |
| Padova                | 1        | 1.39%   |
| Ortona                | 1        | 1.39%   |
| Oleggio               | 1        | 1.39%   |
| Monza                 | 1        | 1.39%   |
| Modena                | 1        | 1.39%   |
| Mestrino              | 1        | 1.39%   |
| Malo                  | 1        | 1.39%   |
| Grottazzolina         | 1        | 1.39%   |
| Follonica             | 1        | 1.39%   |
| Foligno               | 1        | 1.39%   |
| Fagagna               | 1        | 1.39%   |
| Desio                 | 1        | 1.39%   |
| Costabissara          | 1        | 1.39%   |
| Colorno               | 1        | 1.39%   |
| Collegno              | 1        | 1.39%   |
| Cavarzere             | 1        | 1.39%   |
| Catania               | 1        | 1.39%   |
| Castelnuovo del Garda | 1        | 1.39%   |
| Castellanza           | 1        | 1.39%   |
| Cassina Rizzardi      | 1        | 1.39%   |
| Cassano Magnago       | 1        | 1.39%   |
| Carmignano di Brenta  | 1        | 1.39%   |
| Cagliari              | 1        | 1.39%   |
| Belluno               | 1        | 1.39%   |
| Barlassina            | 1        | 1.39%   |
| Bari                  | 1        | 1.39%   |
| Adelfia               | 1        | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 19       | 35     | 21.35%  |
| Samsung Electronics | 12       | 18     | 13.48%  |
| Seagate             | 11       | 14     | 12.36%  |
| Crucial             | 11       | 18     | 12.36%  |
| Transcend           | 4        | 4      | 4.49%   |
| Kingston            | 4        | 4      | 4.49%   |
| Toshiba             | 3        | 7      | 3.37%   |
| SanDisk             | 3        | 3      | 3.37%   |
| EMTEC               | 3        | 4      | 3.37%   |
| Phison              | 2        | 2      | 2.25%   |
| Micron Technology   | 2        | 2      | 2.25%   |
| MAXTOR              | 2        | 2      | 2.25%   |
| Hoodisk             | 2        | 2      | 2.25%   |
| Dogfish             | 2        | 2      | 2.25%   |
| Silicon Motion      | 1        | 2      | 1.12%   |
| PNY                 | 1        | 4      | 1.12%   |
| OCZ                 | 1        | 1      | 1.12%   |
| NVMe                | 1        | 1      | 1.12%   |
| KingSpec            | 1        | 2      | 1.12%   |
| Intel               | 1        | 2      | 1.12%   |
| Hitachi             | 1        | 1      | 1.12%   |
| China               | 1        | 1      | 1.12%   |
| A-DATA Technology   | 1        | 2      | 1.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| EMTEC X150 120GB                 | 3        | 2.94%   |
| WDC WD5000AAKS-22V1A0 500GB      | 2        | 1.96%   |
| Seagate ST320LT007-9ZV142 320GB  | 2        | 1.96%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.96%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.96%   |
| Samsung SSD 850 EVO 250GB        | 2        | 1.96%   |
| Phison SATA SSD 16GB             | 2        | 1.96%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.96%   |
| Crucial CT250MX500SSD1 250GB     | 2        | 1.96%   |
| Crucial CT240BX500SSD1 240GB     | 2        | 1.96%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 1.96%   |
| WDC WDS250G1B0A-00H9H0 250GB     | 1        | 0.98%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1        | 0.98%   |
| WDC WDS100T2B0A-00SM50 1TB       | 1        | 0.98%   |
| WDC WD6400AAKS-65A7B0 640GB      | 1        | 0.98%   |
| WDC WD5000LPVT-80G33T2 500GB     | 1        | 0.98%   |
| WDC WD5000BPKX-00HPJT0 500GB     | 1        | 0.98%   |
| WDC WD5000BMVV-11A1CS0 500GB     | 1        | 0.98%   |
| WDC WD5000BEVT-00A03T0 500GB     | 1        | 0.98%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.98%   |
| WDC WD5000AAKS-00D2B0 500GB      | 1        | 0.98%   |
| WDC WD40NMZW-11GX6S1 4TB         | 1        | 0.98%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.98%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.98%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.98%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 1        | 0.98%   |
| WDC WD30EZRZ-00GXCB0 3TB         | 1        | 0.98%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1        | 0.98%   |
| WDC WD2500AAJS-07M0A0 250GB      | 1        | 0.98%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.98%   |
| WDC WD20EVDS-63T3B0 2TB          | 1        | 0.98%   |
| WDC WD2002FYPS-01U1B1 2TB        | 1        | 0.98%   |
| WDC WD15EADS-00P8B0 1.5TB        | 1        | 0.98%   |
| WDC WD1500HLFS-01G6U0 150GB      | 1        | 0.98%   |
| WDC WD10EFRX-68PJCN0 1TB         | 1        | 0.98%   |
| WDC WD1000DHTZ-04N21V1 1TB       | 1        | 0.98%   |
| Transcend TS64GMSA370 64GB       | 1        | 0.98%   |
| Transcend TS32GSSD370 32GB       | 1        | 0.98%   |
| Transcend TS128GMSA370 128GB     | 1        | 0.98%   |
| Transcend TS128GMSA230S 128GB    | 1        | 0.98%   |
| Toshiba Q300 240GB               | 1        | 0.98%   |
| Toshiba MK5065GSXF 500GB         | 1        | 0.98%   |
| Toshiba DT01ACA050 500GB         | 1        | 0.98%   |
| Silicon Motion ASint AS806 128GB | 1        | 0.98%   |
| Seagate ST500LX025-1U717D 500GB  | 1        | 0.98%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 0.98%   |
| Seagate ST4000LM024-2AN17V 4TB   | 1        | 0.98%   |
| Seagate ST32500NSSUN250G 250GB   | 1        | 0.98%   |
| Seagate ST31500341AS 1.5TB       | 1        | 0.98%   |
| Seagate ST3000DM007-1WY10G 3TB   | 1        | 0.98%   |
| Seagate ST1000LX015-1U7172 1TB   | 1        | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB   | 1        | 0.98%   |
| SanDisk SSD PLUS 120GB           | 1        | 0.98%   |
| SanDisk SDSSDP128G 128GB         | 1        | 0.98%   |
| SanDisk pSSD 256GB               | 1        | 0.98%   |
| Samsung SSD 980 PRO 1TB          | 1        | 0.98%   |
| Samsung SSD 970 EVO 250GB        | 1        | 0.98%   |
| Samsung SSD 870 QVO 2TB          | 1        | 0.98%   |
| Samsung SSD 870 EVO 250GB        | 1        | 0.98%   |
| Samsung SSD 850 EVO 500GB        | 1        | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 32     | 48.57%  |
| Seagate             | 11       | 14     | 31.43%  |
| Toshiba             | 2        | 4      | 5.71%   |
| Samsung Electronics | 2        | 2      | 5.71%   |
| Maxtor              | 2        | 2      | 5.71%   |
| Hitachi             | 1        | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 10       | 17     | 19.23%  |
| Samsung Electronics | 9        | 14     | 17.31%  |
| Transcend           | 4        | 4      | 7.69%   |
| Kingston            | 4        | 4      | 7.69%   |
| WDC                 | 3        | 3      | 5.77%   |
| SanDisk             | 3        | 3      | 5.77%   |
| EMTEC               | 3        | 4      | 5.77%   |
| Phison              | 2        | 2      | 3.85%   |
| Micron Technology   | 2        | 2      | 3.85%   |
| Hoodisk             | 2        | 2      | 3.85%   |
| Dogfish             | 2        | 2      | 3.85%   |
| Toshiba             | 1        | 3      | 1.92%   |
| PNY                 | 1        | 4      | 1.92%   |
| OCZ                 | 1        | 1      | 1.92%   |
| NVMe                | 1        | 1      | 1.92%   |
| KingSpec            | 1        | 2      | 1.92%   |
| Intel               | 1        | 2      | 1.92%   |
| China               | 1        | 1      | 1.92%   |
| A-DATA Technology   | 1        | 2      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 39       | 73     | 57.35%  |
| HDD  | 25       | 55     | 36.76%  |
| NVMe | 4        | 5      | 5.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 56       | 128    | 93.33%  |
| NVMe | 4        | 5      | 6.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 48       | 100    | 69.57%  |
| 0.51-1.0   | 11       | 13     | 15.94%  |
| 1.01-2.0   | 6        | 8      | 8.7%    |
| 3.01-4.0   | 3        | 4      | 4.35%   |
| 2.01-3.0   | 1        | 3      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 29.69%  |
| 1-20           | 18       | 28.13%  |
| 251-500        | 8        | 12.5%   |
| 21-50          | 6        | 9.38%   |
| 501-1000       | 5        | 7.81%   |
| 51-100         | 5        | 7.81%   |
| More than 3000 | 2        | 3.13%   |
| Unknown        | 1        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 88.71%  |
| 21-50          | 3        | 4.84%   |
| More than 3000 | 1        | 1.61%   |
| 1001-2000      | 1        | 1.61%   |
| 501-1000       | 1        | 1.61%   |
| Unknown        | 1        | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2        | 2      | 15.38%  |
| Seagate ST320LT007-9ZV142 320GB   | 2        | 2      | 15.38%  |
| WDC WD5000AAKS-00E4A0 500GB       | 1        | 1      | 7.69%   |
| WDC WD20EVDS-63T3B0 2TB           | 1        | 1      | 7.69%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1        | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 2      | 7.69%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1        | 1      | 7.69%   |
| Seagate ST31500341AS 1.5TB        | 1        | 1      | 7.69%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 7.69%   |
| OCZ VERTEX3 120GB                 | 1        | 1      | 7.69%   |
| A-DATA Technology SX300 128GB     | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 38.46%  |
| Seagate             | 5        | 6      | 38.46%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| OCZ                 | 1        | 1      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 45.45%  |
| Seagate             | 5        | 6      | 45.45%  |
| Samsung Electronics | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 81.82%  |
| SSD  | 2        | 2      | 18.18%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 50       | 105    | 75.76%  |
| Malfunc  | 11       | 14     | 16.67%  |
| Detected | 5        | 14     | 7.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 43       | 56.58%  |
| AMD                              | 16       | 21.05%  |
| Samsung Electronics              | 3        | 3.95%   |
| Marvell Technology Group         | 3        | 3.95%   |
| VIA Technologies                 | 2        | 2.63%   |
| ASMedia Technology               | 2        | 2.63%   |
| Silicon Motion                   | 1        | 1.32%   |
| Silicon Integrated Systems [SiS] | 1        | 1.32%   |
| Micron/Crucial Technology        | 1        | 1.32%   |
| JMicron Technology               | 1        | 1.32%   |
| Integrated Technology Express    | 1        | 1.32%   |
| Broadcom / LSI                   | 1        | 1.32%   |
| Adaptec                          | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 10.99%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 6.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 5.49%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 4.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 4.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 3.3%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 3.3%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 2.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2        | 2.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2        | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 2.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 2.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.1%    |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                             | 1        | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 1.1%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1        | 1.1%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.1%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 1.1%    |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 1.1%    |
| Intel SATA Controller [RAID mode]                                                       | 1        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 1.1%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.1%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 1.1%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.1%    |
| Integrated Express IT8213 IDE Controller                                                | 1        | 1.1%    |
| Broadcom / LSI MegaRAID SAS 8208ELP/8208ELP                                             | 1        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                                      | 1        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 1.1%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.1%    |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 65.71%  |
| IDE  | 15       | 21.43%  |
| NVMe | 5        | 7.14%   |
| RAID | 2        | 2.86%   |
| SCSI | 2        | 2.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 44       | 70.97%  |
| AMD     | 16       | 25.81%  |
| Arm     | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD GX-412TC SOC                              | 4        | 6.45%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2        | 3.23%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 3.23%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 2        | 3.23%   |
| AMD Phenom II X4 965 Processor                | 2        | 3.23%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1        | 1.61%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1        | 1.61%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1        | 1.61%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1        | 1.61%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E6600             | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1        | 1.61%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1        | 1.61%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1        | 1.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1        | 1.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1        | 1.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1        | 1.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 1.61%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 1.61%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1        | 1.61%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1        | 1.61%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1        | 1.61%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1        | 1.61%   |
| Intel Core i5-4210Y CPU @ 1.50GHz             | 1        | 1.61%   |
| Intel Core i5 CPU                             | 1        | 1.61%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1        | 1.61%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 1.61%   |
| Intel Core i3-3225 CPU @ 3.30GHz              | 1        | 1.61%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 1        | 1.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 1.61%   |
| Intel Core 2 Extreme CPU X9650 @ 3.00GHz      | 1        | 1.61%   |
| Intel Core 2 Duo CPU E7500                    | 1        | 1.61%   |
| Intel Core 2 Duo                              | 1        | 1.61%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1        | 1.61%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 1        | 1.61%   |
| Intel Celeron CPU J3355 @ 2.00GHz             | 1        | 1.61%   |
| Intel Celeron CPU G550 @ 2.60GHz              | 1        | 1.61%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 1        | 1.61%   |
| Intel Atom CPU D2500 @ 1.86GHz                | 1        | 1.61%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 1        | 1.61%   |
| Intel Atom CPU 230 @ 1.60GHz                  | 1        | 1.61%   |
| Arm Cortex-A53 r0p4 (v8-A)                    | 1        | 1.61%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1        | 1.61%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1        | 1.61%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1        | 1.61%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.61%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1        | 1.61%   |
| AMD FX-9590 Eight-Core Processor              | 1        | 1.61%   |
| AMD E2-3200 APU with Radeon HD Graphics       | 1        | 1.61%   |
| AMD Athlon II X4 640 Processor                | 1        | 1.61%   |
|                                               | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 8        | 12.9%   |
| Intel Core i5           | 6        | 9.68%   |
| Intel Xeon              | 5        | 8.06%   |
| Intel Core i7           | 5        | 8.06%   |
| Intel Core i3           | 5        | 8.06%   |
| Intel Atom              | 4        | 6.45%   |
| AMD GX                  | 4        | 6.45%   |
| Intel Pentium Dual      | 3        | 4.84%   |
| AMD Ryzen 5             | 3        | 4.84%   |
| Other                   | 2        | 3.23%   |
| Intel Pentium Dual-Core | 2        | 3.23%   |
| Intel Pentium           | 2        | 3.23%   |
| Intel Core 2 Duo        | 2        | 3.23%   |
| AMD Ryzen 7             | 2        | 3.23%   |
| AMD Phenom II X4        | 2        | 3.23%   |
| Intel Core 2 Quad       | 1        | 1.61%   |
| Intel Core 2 Extreme    | 1        | 1.61%   |
| AMD Ryzen 9             | 1        | 1.61%   |
| AMD Ryzen 3             | 1        | 1.61%   |
| AMD FX                  | 1        | 1.61%   |
| AMD E2                  | 1        | 1.61%   |
| AMD Athlon II X4        | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 24       | 38.71%  |
| 2       | 22       | 35.48%  |
| Unknown | 7        | 11.29%  |
| 12      | 3        | 4.84%   |
| 16      | 2        | 3.23%   |
| 32      | 1        | 1.61%   |
| 8       | 1        | 1.61%   |
| 6       | 1        | 1.61%   |
| 1       | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 59       | 95.16%  |
| Unknown | 3        | 4.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 33       | 53.23%  |
| 2       | 22       | 35.48%  |
| Unknown | 7        | 11.29%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 6        | 9.68%   |
| Haswell       | 6        | 9.68%   |
| Penryn        | 5        | 8.06%   |
| Puma          | 4        | 6.45%   |
| KabyLake      | 4        | 6.45%   |
| IvyBridge     | 4        | 6.45%   |
| Core          | 4        | 6.45%   |
| Bonnell       | 4        | 6.45%   |
| K10           | 3        | 4.84%   |
| Goldmont plus | 3        | 4.84%   |
| Zen+          | 2        | 3.23%   |
| Zen 3         | 2        | 3.23%   |
| Zen 2         | 2        | 3.23%   |
| Silvermont    | 2        | 3.23%   |
| Nehalem       | 2        | 3.23%   |
| Goldmont      | 2        | 3.23%   |
| Unknown       | 2        | 3.23%   |
| Zen           | 1        | 1.61%   |
| Westmere      | 1        | 1.61%   |
| Piledriver    | 1        | 1.61%   |
| K10 Llano     | 1        | 1.61%   |
| Broadwell     | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 31       | 53.45%  |
| AMD                              | 13       | 22.41%  |
| Nvidia                           | 12       | 20.69%  |
| Silicon Integrated Systems [SiS] | 1        | 1.72%   |
| Matrox Electronics Systems       | 1        | 1.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 6.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 5.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 5.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3        | 5.17%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 3.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 3.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 3.45%   |
| Intel HD Graphics 620                                                                    | 2        | 3.45%   |
| Intel HD Graphics 500                                                                    | 2        | 3.45%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 3.45%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 3.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 3.45%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 1.72%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.72%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.72%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.72%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1        | 1.72%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.72%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.72%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.72%   |
| Intel HD Graphics 630                                                                    | 1        | 1.72%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.72%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 1.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.72%   |
| AMD SuperSumo [Radeon HD 6370D]                                                          | 1        | 1.72%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 1        | 1.72%   |
| AMD RS880 [Radeon HD 4250]                                                               | 1        | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.72%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 1.72%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                   | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 29       | 46.03%  |
| 1 x AMD        | 13       | 20.63%  |
| 1 x Nvidia     | 11       | 17.46%  |
| Other          | 6        | 9.52%   |
| 2 x Intel      | 1        | 1.59%   |
| 1 x SiS        | 1        | 1.59%   |
| 1 x Matrox     | 1        | 1.59%   |
| Intel + Nvidia | 1        | 1.59%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 71.88%  |
| Proprietary | 11       | 17.19%  |
| Unknown     | 7        | 10.94%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 71.88%  |
| 1.01-2.0   | 6        | 9.38%   |
| 3.01-4.0   | 4        | 6.25%   |
| 0.51-1.0   | 4        | 6.25%   |
| 0.01-0.5   | 2        | 3.13%   |
| 7.01-8.0   | 1        | 1.56%   |
| 5.01-6.0   | 1        | 1.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 23.33%  |
| Acer                 | 4        | 13.33%  |
| Philips              | 3        | 10%     |
| Hewlett-Packard      | 3        | 10%     |
| Goldstar             | 2        | 6.67%   |
| Dell                 | 2        | 6.67%   |
| Sony                 | 1        | 3.33%   |
| Packard Bell         | 1        | 3.33%   |
| Orion                | 1        | 3.33%   |
| LG Electronics       | 1        | 3.33%   |
| Iiyama               | 1        | 3.33%   |
| Eizo                 | 1        | 3.33%   |
| ASUSTek Computer     | 1        | 3.33%   |
| Apple                | 1        | 3.33%   |
| Ancor Communications | 1        | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 6.67%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 2        | 6.67%   |
| Sony TV SNY5D01 1360x768                                              | 1        | 3.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 3.33%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 3.33%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1        | 3.33%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 3.33%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1        | 3.33%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 3.33%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1        | 3.33%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1        | 3.33%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1        | 3.33%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                | 1        | 3.33%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 3.33%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch             | 1        | 3.33%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 3.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 3.33%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch           | 1        | 3.33%   |
| Eizo LCD Monitor S1901 1280x1024                                      | 1        | 3.33%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                     | 1        | 3.33%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                     | 1        | 3.33%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1        | 3.33%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1        | 3.33%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 3.33%   |
| Acer X203H ACR0097 1600x900 440x250mm 19.9-inch                       | 1        | 3.33%   |
| Acer RT240Y ACR0539 1920x1080 530x300mm 24.0-inch                     | 1        | 3.33%   |
| Acer R271 ACR0496 1920x1080 600x340mm 27.2-inch                       | 1        | 3.33%   |
| Acer AL1917 ACRAD63 1280x1024 380x300mm 19.1-inch                     | 1        | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 16       | 59.26%  |
| 1280x1024 (SXGA)  | 3        | 11.11%  |
| 1920x1200 (WUXGA) | 2        | 7.41%   |
| 3840x2160 (4K)    | 1        | 3.7%    |
| 2560x1080         | 1        | 3.7%    |
| 1600x900 (HD+)    | 1        | 3.7%    |
| 1440x900 (WXGA+)  | 1        | 3.7%    |
| 1360x768          | 1        | 3.7%    |
| 1024x768 (XGA)    | 1        | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 23.33%  |
| 24      | 4        | 13.33%  |
| 21      | 4        | 13.33%  |
| 19      | 4        | 13.33%  |
| 27      | 3        | 10%     |
| 23      | 3        | 10%     |
| 31      | 2        | 6.67%   |
| 28      | 1        | 3.33%   |
| 22      | 1        | 3.33%   |
| 14      | 1        | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 28.57%  |
| Unknown     | 7        | 25%     |
| 401-500     | 6        | 21.43%  |
| 601-700     | 4        | 14.29%  |
| 351-400     | 2        | 7.14%   |
| 201-300     | 1        | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 17       | 65.38%  |
| 16/10   | 3        | 11.54%  |
| 5/4     | 2        | 7.69%   |
| Unknown | 2        | 7.69%   |
| 4/3     | 1        | 3.85%   |
| 21/9    | 1        | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 28.57%  |
| Unknown        | 7        | 25%     |
| 151-200        | 4        | 14.29%  |
| 301-350        | 3        | 10.71%  |
| 251-300        | 3        | 10.71%  |
| 351-500        | 2        | 7.14%   |
| 101-110        | 1        | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 57.14%  |
| Unknown | 7        | 25%     |
| 101-120 | 4        | 14.29%  |
| 121-160 | 1        | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 37       | 57.81%  |
| 1     | 25       | 39.06%  |
| 2     | 2        | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 37       | 46.84%  |
| Realtek Semiconductor | 28       | 35.44%  |
| Qualcomm Atheros      | 4        | 5.06%   |
| Broadcom              | 4        | 5.06%   |
| Ralink                | 2        | 2.53%   |
| Ralink Technology     | 1        | 1.27%   |
| IMC Networks          | 1        | 1.27%   |
| Digital Equipment     | 1        | 1.27%   |
| Davicom Semiconductor | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 24       | 26.37%  |
| Intel I211 Gigabit Network Connection                                                 | 13       | 14.29%  |
| Intel 82574L Gigabit Network Connection                                               | 4        | 4.4%    |
| Intel I210 Gigabit Network Connection                                                 | 3        | 3.3%    |
| Intel 82579V Gigabit Network Connection                                               | 3        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 3.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2        | 2.2%    |
| Intel I350 Gigabit Network Connection                                                 | 2        | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.1%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.1%    |
| Realtek RTL8125 2.5GbE Controller                                                     | 1        | 1.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.1%    |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 1.1%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 1.1%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 1.1%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 1.1%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.1%    |
| Intel Wireless 3165                                                                   | 1        | 1.1%    |
| Intel Ethernet Controller I225-V                                                      | 1        | 1.1%    |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                                  | 1        | 1.1%    |
| Intel Ethernet Connection (2) I218-LM                                                 | 1        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.1%    |
| Intel 82583V Gigabit Network Connection                                               | 1        | 1.1%    |
| Intel 82575EB Gigabit Network Connection                                              | 1        | 1.1%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)         | 1        | 1.1%    |
| Intel 82567V-2 Gigabit Network Connection                                             | 1        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                                            | 1        | 1.1%    |
| Intel 82567LF-2 Gigabit Network Connection                                            | 1        | 1.1%    |
| Intel 82566DM-2 Gigabit Network Connection                                            | 1        | 1.1%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                  | 1        | 1.1%    |
| Intel 82541GI Gigabit Ethernet Controller                                             | 1        | 1.1%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 1.1%    |
| Digital Equipment DECchip 21142/43                                                    | 1        | 1.1%    |
| Davicom DM9102 Fast Ethernet Controller                                               | 1        | 1.1%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                     | 1        | 1.1%    |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                               | 1        | 1.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 1        | 1.1%    |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                         | 1        | 1.1%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 4        | 30.77%  |
| Realtek Semiconductor | 3        | 23.08%  |
| Ralink                | 2        | 15.38%  |
| Intel                 | 2        | 15.38%  |
| Ralink Technology     | 1        | 7.69%   |
| IMC Networks          | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 6.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 6.67%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 6.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 6.67%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 6.67%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 6.67%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 6.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 6.67%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 6.67%   |
| Intel Wireless 3165                                                                   | 1        | 6.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 6.67%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 36       | 52.94%  |
| Realtek Semiconductor | 26       | 38.24%  |
| Broadcom              | 4        | 5.88%   |
| Digital Equipment     | 1        | 1.47%   |
| Davicom Semiconductor | 1        | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 24       | 31.58%  |
| Intel I211 Gigabit Network Connection                                         | 13       | 17.11%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 5.26%   |
| Intel I210 Gigabit Network Connection                                         | 3        | 3.95%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 3.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 2.63%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 1.32%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.32%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.32%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.32%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 1.32%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.32%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.32%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.32%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 1.32%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 1.32%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.32%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 1.32%   |
| Digital Equipment DECchip 21142/43                                            | 1        | 1.32%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1        | 1.32%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 1.32%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1        | 1.32%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.32%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1        | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 83.33%  |
| WiFi     | 12       | 16.67%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 90.91%  |
| WiFi     | 6        | 9.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 35.48%  |
| 2     | 13       | 20.97%  |
| 3     | 10       | 16.13%  |
| 4     | 9        | 14.52%  |
| 5     | 4        | 6.45%   |
| 7     | 2        | 3.23%   |
| 0     | 2        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 3        | 42.86%  |
| Integrated System Solution | 2        | 28.57%  |
| Realtek Semiconductor      | 1        | 14.29%  |
| Intel                      | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3        | 42.86%  |
| Integrated System Solution Bluetooth Device         | 2        | 28.57%  |
| Realtek  Bluetooth Adapter                          | 1        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 38       | 54.29%  |
| AMD                              | 16       | 22.86%  |
| Nvidia                           | 11       | 15.71%  |
| Logitech                         | 2        | 2.86%   |
| Silicon Integrated Systems [SiS] | 1        | 1.43%   |
| C-Media Electronics              | 1        | 1.43%   |
| Bose                             | 1        | 1.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 7.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 6.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 4.82%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 4.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 4.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 3.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 3.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 3.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3        | 3.61%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.41%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 2.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 2.41%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2        | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 2.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 2.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 2.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.41%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.41%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.2%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.2%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.2%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.2%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.2%    |
| Logitech Headset H340                                                                             | 1        | 1.2%    |
| Logitech HD Webcam C510                                                                           | 1        | 1.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.2%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1        | 1.2%    |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.2%    |
| C-Media Electronics Audio Adapter (Planet UP-100, Genius G-Talk)                                  | 1        | 1.2%    |
| Bose Bose USB Audio                                                                               | 1        | 1.2%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1        | 1.2%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 1.2%    |
| AMD FCH Azalia Controller                                                                         | 1        | 1.2%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 1.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 24.14%  |
| Kingston            | 10       | 17.24%  |
| Crucial             | 6        | 10.34%  |
| SK Hynix            | 5        | 8.62%   |
| Samsung Electronics | 5        | 8.62%   |
| Corsair             | 4        | 6.9%    |
| Unknown (ABCD)      | 2        | 3.45%   |
| Nanya Technology    | 2        | 3.45%   |
| Unknown             | 2        | 3.45%   |
| Unknown (AB)        | 1        | 1.72%   |
| Transcend           | 1        | 1.72%   |
| Ramaxel Technology  | 1        | 1.72%   |
| Micron Technology   | 1        | 1.72%   |
| KomputerBay         | 1        | 1.72%   |
| Intersil            | 1        | 1.72%   |
| G.Skill             | 1        | 1.72%   |
| Elpida              | 1        | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2        | 3.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 3.13%   |
| Unknown                                                        | 2        | 3.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1        | 1.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1        | 1.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                   | 1        | 1.56%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1        | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 1        | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1        | 1.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 1.56%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1        | 1.56%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s            | 1        | 1.56%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s           | 1        | 1.56%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                     | 1        | 1.56%   |
| SK Hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s            | 1        | 1.56%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 1        | 1.56%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1.56%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s           | 1        | 1.56%   |
| SK Hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                | 1        | 1.56%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 1.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 1.56%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s            | 1        | 1.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s            | 1        | 1.56%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s            | 1        | 1.56%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 1        | 1.56%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s             | 1        | 1.56%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s             | 1        | 1.56%   |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s          | 1        | 1.56%   |
| KomputerBay RAM KB_8G_D3_1600_C10 8192MB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s           | 1        | 1.56%   |
| Kingston RAM KHX3000C15D4/4GX 4096MB DIMM DDR4 2667MT/s        | 1        | 1.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s              | 1        | 1.56%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s           | 1        | 1.56%   |
| Kingston RAM KHX1600C9S3L/4G 4GB SODIMM DDR3 1600MT/s          | 1        | 1.56%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 2400MT/s            | 1        | 1.56%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1067MT/s         | 1        | 1.56%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s           | 1        | 1.56%   |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM 667MT/s                | 1        | 1.56%   |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s          | 1        | 1.56%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.56%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s        | 1        | 1.56%   |
| Kingston RAM 9905471-006.A01LF 4GB DIMM DDR3 1333MT/s          | 1        | 1.56%   |
| Intersil RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1067MT/s          | 1        | 1.56%   |
| G.Skill RAM F3-10666CL9-4GBRL 4GB DIMM DDR3 1333MT/s           | 1        | 1.56%   |
| G.Skill RAM F3-10600CL9-2GBNT 2GB DIMM DDR3 1333MT/s           | 1        | 1.56%   |
| Elpida RAM EBJ21UE8BAFA-AE-E 2GB DIMM 1066MT/s                 | 1        | 1.56%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB SODIMM DDR4 2400MT/s        | 1        | 1.56%   |
| Crucial RAM CT4G4SFS824A.M8FF 4GB SODIMM DDR4 2400MT/s         | 1        | 1.56%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1        | 1.56%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 1        | 1.56%   |
| Crucial RAM BLS8G4D240FSB.16FBD 8GB DIMM DDR4 2933MT/s         | 1        | 1.56%   |
| Crucial RAM BL8G32C16U4B.M8FE 8GB DIMM DDR4 2933MT/s           | 1        | 1.56%   |
| Crucial RAM BL8G26C16S4B.8FD 8GB SODIMM DDR4 2400MT/s          | 1        | 1.56%   |
| Corsair RAM CMZ16GX3M4X1866C9 4096MB DIMM DDR3 1067MT/s        | 1        | 1.56%   |
| Corsair RAM CMX4GX3M2B1600C9 2GB DIMM DDR3 1333MT/s            | 1        | 1.56%   |
| Corsair RAM CMX4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s            | 1        | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 28       | 50%     |
| DDR4    | 12       | 21.43%  |
| DDR2    | 9        | 16.07%  |
| Unknown | 5        | 8.93%   |
| LPDDR4  | 2        | 3.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 40       | 74.07%  |
| SODIMM | 14       | 25.93%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 21       | 36.21%  |
| 2048  | 17       | 29.31%  |
| 8192  | 12       | 20.69%  |
| 16384 | 4        | 6.9%    |
| 1024  | 3        | 5.17%   |
| 32768 | 1        | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 14       | 23.73%  |
| 1600  | 10       | 16.95%  |
| 2400  | 8        | 13.56%  |
| 800   | 6        | 10.17%  |
| 1067  | 5        | 8.47%   |
| 2667  | 4        | 6.78%   |
| 667   | 3        | 5.08%   |
| 2133  | 2        | 3.39%   |
| 1066  | 2        | 3.39%   |
| 3200  | 1        | 1.69%   |
| 2933  | 1        | 1.69%   |
| 2666  | 1        | 1.69%   |
| 1866  | 1        | 1.69%   |
| 1200  | 1        | 1.69%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 2        | 33.33%  |
| Sunplus Innovation Technology | 1        | 16.67%  |
| Microdia                      | 1        | 16.67%  |
| KYE Systems (Mouse Systems)   | 1        | 16.67%  |
| Genesys Logic                 | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Sunplus Aukey-PC-LM1E Camera                     | 1        | 16.67%  |
| Microdia ASUS USB2.0 Webcam                      | 1        | 16.67%  |
| Logitech Webcam C310                             | 1        | 16.67%  |
| Logitech C505 HD Webcam                          | 1        | 16.67%  |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1        | 16.67%  |
| Genesys Logic Digital Microscope                 | 1        | 16.67%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 51.61%  |
| 0     | 27       | 43.55%  |
| 2     | 2        | 3.23%   |
| 3     | 1        | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 27       | 72.97%  |
| Firewire controller      | 6        | 16.22%  |
| Net/wireless             | 3        | 8.11%   |
| Card reader              | 1        | 2.7%    |

