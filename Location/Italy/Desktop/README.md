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

Total: 134

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | Q3XXG4-P V1.0               | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek       | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| HP            | 0A98h                       | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| ASUSTek       | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
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
| PC Engines    | APU2                        | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
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
| helloSystem 0.4.0    | 7        | 7.78%   |
| OpenBSD 7.1          | 6        | 6.67%   |
| helloSystem 0.7.0    | 6        | 6.67%   |
| OPNsense 22.1        | 4        | 4.44%   |
| OPNsense 21.1        | 4        | 4.44%   |
| helloSystem 0.5.0    | 4        | 4.44%   |
| OPNsense 22.1.9      | 3        | 3.33%   |
| OPNsense 22.1.10     | 3        | 3.33%   |
| OPNsense 21.7.3      | 3        | 3.33%   |
| helloSystem 0.6.0    | 3        | 3.33%   |
| helloSystem 0.3.0    | 3        | 3.33%   |
| OPNsense 22.7        | 2        | 2.22%   |
| OPNsense 22.1.8      | 2        | 2.22%   |
| OPNsense 22.1.6      | 2        | 2.22%   |
| OPNsense 22.1.4      | 2        | 2.22%   |
| OPNsense 21.7.7      | 2        | 2.22%   |
| OPNsense 21.1.3      | 2        | 2.22%   |
| OPNsense 21.1.2      | 2        | 2.22%   |
| OPNsense 20.7.8      | 2        | 2.22%   |
| OpenBSD 6.8          | 2        | 2.22%   |
| NomadBSD 1.4         | 2        | 2.22%   |
| FreeBSD 12.3-p1      | 2        | 2.22%   |
| OPNsense 22.1.7      | 1        | 1.11%   |
| OPNsense 22.1.3      | 1        | 1.11%   |
| OPNsense 22.1.2      | 1        | 1.11%   |
| OPNsense 21.7.8      | 1        | 1.11%   |
| OPNsense 21.7.6      | 1        | 1.11%   |
| OPNsense 21.7.4      | 1        | 1.11%   |
| OPNsense 21.7.1      | 1        | 1.11%   |
| OPNsense 21.7        | 1        | 1.11%   |
| OPNsense 21.1.8      | 1        | 1.11%   |
| OPNsense 21.1.7      | 1        | 1.11%   |
| OPNsense 21.1.5      | 1        | 1.11%   |
| OPNsense 21.1.1      | 1        | 1.11%   |
| NetBSD 9.99.77       | 1        | 1.11%   |
| NetBSD 9.1_STABLE    | 1        | 1.11%   |
| FreeBSD 13.0-p7      | 1        | 1.11%   |
| FreeBSD 13.0-p5      | 1        | 1.11%   |
| FreeBSD 13.0-CURRENT | 1        | 1.11%   |
| FreeBSD 12.2-STABLE  | 1        | 1.11%   |
| FreeBSD 12.2-p6      | 1        | 1.11%   |
| FreeBSD 12.2-p2      | 1        | 1.11%   |
| FreeBSD 12.1-p6      | 1        | 1.11%   |
| FreeBSD 12.1-p10     | 1        | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 32       | 45.07%  |
| helloSystem | 17       | 23.94%  |
| FreeBSD     | 10       | 14.08%  |
| OpenBSD     | 8        | 11.27%  |
| NomadBSD    | 2        | 2.82%   |
| NetBSD      | 2        | 2.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 68       | 95.77%  |
| evbarm | 2        | 2.82%   |
| i386   | 1        | 1.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 36       | 50.7%   |
| helloDesktop  | 21       | 29.58%  |
| XFCE          | 3        | 4.23%   |
| Openbox       | 2        | 2.82%   |
| MATE          | 2        | 2.82%   |
| fvwm          | 2        | 2.82%   |
| xfwm          | 1        | 1.41%   |
| TWM           | 1        | 1.41%   |
| KDE5          | 1        | 1.41%   |
| Enlightenment | 1        | 1.41%   |
| CTWM          | 1        | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 37       | 52.11%  |
| X11     | 34       | 47.89%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 48       | 67.61%  |
| SLiM    | 21       | 29.58%  |
| LightDM | 2        | 2.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 45       | 62.5%   |
| en_US            | 18       | 25%     |
| it_IT            | 5        | 6.94%   |
| C                | 3        | 4.17%   |
| it_IT.ISO8859-15 | 1        | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 72.6%   |
| BIOS | 20       | 27.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 37       | 50%     |
| Zfs    | 25       | 33.78%  |
| Ffs    | 8        | 10.81%  |
| Cd9660 | 4        | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 60       | 83.33%  |
| MBR     | 11       | 15.28%  |
| Unknown | 1        | 1.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 16       | 22.54%  |
| Intel                      | 6        | 8.45%   |
| Unknown                    | 6        | 8.45%   |
| Hewlett-Packard            | 5        | 7.04%   |
| PC Engines                 | 4        | 5.63%   |
| MSI                        | 4        | 5.63%   |
| Gigabyte Technology        | 4        | 5.63%   |
| Dell                       | 4        | 5.63%   |
| Fujitsu                    | 3        | 4.23%   |
| ASRock                     | 3        | 4.23%   |
| Pegatron                   | 2        | 2.82%   |
| Lenovo                     | 2        | 2.82%   |
| Acer                       | 2        | 2.82%   |
| T-bao                      | 1        | 1.41%   |
| Supermicro                 | 1        | 1.41%   |
| Sun Microsystems           | 1        | 1.41%   |
| ShenZhen MinWin Technology | 1        | 1.41%   |
| Protectli                  | 1        | 1.41%   |
| NF692                      | 1        | 1.41%   |
| MW                         | 1        | 1.41%   |
| HARDKERNEL                 | 1        | 1.41%   |
| Foxconn                    | 1        | 1.41%   |
| AZW                        | 1        | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 6        | 8.45%   |
| PC Engines APU2                         | 3        | 4.23%   |
| Intel Q3XXG4-P V1.0                     | 3        | 4.23%   |
| MSI MS-7B86                             | 2        | 2.82%   |
| Lenovo ThinkCentre M83 10AHS35Q00       | 2        | 2.82%   |
| ASUS PRIME H410M-A                      | 2        | 2.82%   |
| ASUS M4A88TD-V EVO/USB3                 | 2        | 2.82%   |
| ASUS IP4BL-ME                           | 2        | 2.82%   |
| T-bao MINI PC                           | 1        | 1.41%   |
| Supermicro X8STi                        | 1        | 1.41%   |
| Sun Microsystems Ultra 24               | 1        | 1.41%   |
| ShenZhen MinWin MW-NANO-APL-4L          | 1        | 1.41%   |
| Protectli FW4B                          | 1        | 1.41%   |
| Pegatron Pro 3405 Series                | 1        | 1.41%   |
| Pegatron KX629AA-ABZ a6561.it           | 1        | 1.41%   |
| PC Engines APU3                         | 1        | 1.41%   |
| NF692 1.0                               | 1        | 1.41%   |
| MW GMLK-2_5G4L                          | 1        | 1.41%   |
| MSI NR074AA-ABZ CQ5125IT                | 1        | 1.41%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159) | 1        | 1.41%   |
| Intel MAHOBAY                           | 1        | 1.41%   |
| Intel D945GCLF2                         | 1        | 1.41%   |
| Intel D2500CC AAG81477-401              | 1        | 1.41%   |
| HP Z440 Workstation                     | 1        | 1.41%   |
| HP xw8600 Workstation                   | 1        | 1.41%   |
| HP ProLiant MicroServer Gen8            | 1        | 1.41%   |
| HP Compaq Elite 8300 SFF                | 1        | 1.41%   |
| HP Compaq 8100 Elite CMT PC             | 1        | 1.41%   |
| HARDKERNEL ODROID-H2                    | 1        | 1.41%   |
| Gigabyte X570 AORUS PRO                 | 1        | 1.41%   |
| Gigabyte X570 AORUS ELITE               | 1        | 1.41%   |
| Gigabyte P55A-UD3                       | 1        | 1.41%   |
| Gigabyte H270M-DS3H                     | 1        | 1.41%   |
| Fujitsu FUTRO S920                      | 1        | 1.41%   |
| Fujitsu ESPRIMO E7936                   | 1        | 1.41%   |
| Fujitsu ESPRIMO E3521                   | 1        | 1.41%   |
| Foxconn p6-2305elm                      | 1        | 1.41%   |
| Dell Studio XPS 435MT                   | 1        | 1.41%   |
| Dell Precision T1600                    | 1        | 1.41%   |
| Dell OptiPlex FX160                     | 1        | 1.41%   |
| Dell Inspiron 3847                      | 1        | 1.41%   |
| AZW BT3 X                               | 1        | 1.41%   |
| ASUS PRIME Z390M-PLUS                   | 1        | 1.41%   |
| ASUS PRIME X470-PRO                     | 1        | 1.41%   |
| ASUS PRIME H410M-E                      | 1        | 1.41%   |
| ASUS PRIME B550M-K                      | 1        | 1.41%   |
| ASUS P8Z77-V PRO/THUNDERBOLT            | 1        | 1.41%   |
| ASUS P8H61-M LE                         | 1        | 1.41%   |
| ASUS M4A87TD EVO                        | 1        | 1.41%   |
| ASUS M4A785TD-M EVO                     | 1        | 1.41%   |
| ASUS IP4BL-ME-Oli                       | 1        | 1.41%   |
| ASUS BM6835_BM6635_BP6335               | 1        | 1.41%   |
| ASRock H81 Pro BTC                      | 1        | 1.41%   |
| ASRock B75M R2.0                        | 1        | 1.41%   |
| ASRock 990FX Extreme9                   | 1        | 1.41%   |
| Acer Veriton X2610G                     | 1        | 1.41%   |
| Acer Aspire M3900                       | 1        | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS PRIME                     | 6        | 8.45%   |
| Unknown                        | 6        | 8.45%   |
| PC Engines APU2                | 3        | 4.23%   |
| Intel Q3XXG4-P                 | 3        | 4.23%   |
| MSI MS-7B86                    | 2        | 2.82%   |
| Lenovo ThinkCentre             | 2        | 2.82%   |
| HP Compaq                      | 2        | 2.82%   |
| Gigabyte X570                  | 2        | 2.82%   |
| Fujitsu ESPRIMO                | 2        | 2.82%   |
| ASUS M4A88TD-V                 | 2        | 2.82%   |
| ASUS IP4BL-ME                  | 2        | 2.82%   |
| T-bao MINI                     | 1        | 1.41%   |
| Supermicro X8STi               | 1        | 1.41%   |
| Sun Microsystems Ultra         | 1        | 1.41%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.41%   |
| Protectli FW4B                 | 1        | 1.41%   |
| Pegatron Pro                   | 1        | 1.41%   |
| Pegatron KX629AA-ABZ           | 1        | 1.41%   |
| PC Engines APU3                | 1        | 1.41%   |
| NF692 1.0                      | 1        | 1.41%   |
| MW GMLK-2                      | 1        | 1.41%   |
| MSI NR074AA-ABZ                | 1        | 1.41%   |
| MSI KBL-U                      | 1        | 1.41%   |
| Intel MAHOBAY                  | 1        | 1.41%   |
| Intel D945GCLF2                | 1        | 1.41%   |
| Intel D2500CC                  | 1        | 1.41%   |
| HP Z440                        | 1        | 1.41%   |
| HP xw8600                      | 1        | 1.41%   |
| HP ProLiant                    | 1        | 1.41%   |
| HARDKERNEL ODROID-H2           | 1        | 1.41%   |
| Gigabyte P55A-UD3              | 1        | 1.41%   |
| Gigabyte H270M-DS3H            | 1        | 1.41%   |
| Fujitsu FUTRO                  | 1        | 1.41%   |
| Foxconn p6-2305elm             | 1        | 1.41%   |
| Dell Studio                    | 1        | 1.41%   |
| Dell Precision                 | 1        | 1.41%   |
| Dell OptiPlex                  | 1        | 1.41%   |
| Dell Inspiron                  | 1        | 1.41%   |
| AZW BT3                        | 1        | 1.41%   |
| ASUS P8Z77-V                   | 1        | 1.41%   |
| ASUS P8H61-M                   | 1        | 1.41%   |
| ASUS M4A87TD                   | 1        | 1.41%   |
| ASUS M4A785TD-M                | 1        | 1.41%   |
| ASUS IP4BL-ME-Oli              | 1        | 1.41%   |
| ASUS BM6835                    | 1        | 1.41%   |
| ASRock H81                     | 1        | 1.41%   |
| ASRock B75M                    | 1        | 1.41%   |
| ASRock 990FX                   | 1        | 1.41%   |
| Acer Veriton                   | 1        | 1.41%   |
| Acer Aspire                    | 1        | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 8        | 11.27%  |
| 2010    | 8        | 11.27%  |
| 2012    | 7        | 9.86%   |
| 2021    | 5        | 7.04%   |
| 2020    | 5        | 7.04%   |
| 2019    | 5        | 7.04%   |
| 2018    | 5        | 7.04%   |
| 2011    | 5        | 7.04%   |
| 2008    | 5        | 7.04%   |
| 2014    | 4        | 5.63%   |
| 2009    | 4        | 5.63%   |
| 2017    | 3        | 4.23%   |
| 2015    | 3        | 4.23%   |
| Unknown | 2        | 2.82%   |
| 2022    | 1        | 1.41%   |
| 2013    | 1        | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 71       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 94.37%  |
| Yes  | 4        | 5.63%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 29       | 40.28%  |
| 4.01-8.0    | 18       | 25%     |
| 16.01-24.0  | 9        | 12.5%   |
| 2.01-3.0    | 6        | 8.33%   |
| 32.01-64.0  | 4        | 5.56%   |
| 24.01-32.0  | 2        | 2.78%   |
| 64.01-256.0 | 2        | 2.78%   |
| 3.01-4.0    | 1        | 1.39%   |
| 0.51-1.0    | 1        | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 48       | 66.67%  |
| 0.51-1.0 | 16       | 22.22%  |
| 1.01-2.0 | 4        | 5.56%   |
| Unknown  | 2        | 2.78%   |
| 4.01-8.0 | 1        | 1.39%   |
| 2.01-3.0 | 1        | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 38       | 51.35%  |
| 2      | 17       | 22.97%  |
| 4      | 7        | 9.46%   |
| 3      | 6        | 8.11%   |
| 0      | 5        | 6.76%   |
| 10     | 1        | 1.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 66.2%   |
| Yes       | 24       | 33.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 69       | 97.18%  |
| No        | 2        | 2.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 81.94%  |
| Yes       | 13       | 18.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 88.89%  |
| Yes       | 8        | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 71       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 16       | 19.05%  |
| Rome                  | 6        | 7.14%   |
| Naples                | 3        | 3.57%   |
| Turrivalignani        | 2        | 2.38%   |
| Silea                 | 2        | 2.38%   |
| Reggio Emilia         | 2        | 2.38%   |
| Lucca                 | 2        | 2.38%   |
| Viterbo               | 1        | 1.19%   |
| Venice                | 1        | 1.19%   |
| Turin                 | 1        | 1.19%   |
| Trieste               | 1        | 1.19%   |
| Treviso               | 1        | 1.19%   |
| Terni                 | 1        | 1.19%   |
| Soresina              | 1        | 1.19%   |
| Sasso Marconi         | 1        | 1.19%   |
| Sannicandro di Bari   | 1        | 1.19%   |
| San Donato Milanese   | 1        | 1.19%   |
| Ravenna               | 1        | 1.19%   |
| Pozzuolo Martesana    | 1        | 1.19%   |
| Ponsacco              | 1        | 1.19%   |
| Pistoia               | 1        | 1.19%   |
| Pisa                  | 1        | 1.19%   |
| Pioltello             | 1        | 1.19%   |
| Peschiera del Garda   | 1        | 1.19%   |
| Parma                 | 1        | 1.19%   |
| Padova                | 1        | 1.19%   |
| Ortona                | 1        | 1.19%   |
| Oleggio               | 1        | 1.19%   |
| Monza                 | 1        | 1.19%   |
| Monteleone di Fermo   | 1        | 1.19%   |
| Modena                | 1        | 1.19%   |
| Mestrino              | 1        | 1.19%   |
| Malo                  | 1        | 1.19%   |
| Grottazzolina         | 1        | 1.19%   |
| Gianico               | 1        | 1.19%   |
| Gemona                | 1        | 1.19%   |
| Follonica             | 1        | 1.19%   |
| Foligno               | 1        | 1.19%   |
| Fagagna               | 1        | 1.19%   |
| Desio                 | 1        | 1.19%   |
| Costabissara          | 1        | 1.19%   |
| Colorno               | 1        | 1.19%   |
| Collegno              | 1        | 1.19%   |
| Cellatica             | 1        | 1.19%   |
| Cavarzere             | 1        | 1.19%   |
| Catania               | 1        | 1.19%   |
| Castelnuovo del Garda | 1        | 1.19%   |
| Castellanza           | 1        | 1.19%   |
| Cassina Rizzardi      | 1        | 1.19%   |
| Cassano Magnago       | 1        | 1.19%   |
| Carpi                 | 1        | 1.19%   |
| Carmignano di Brenta  | 1        | 1.19%   |
| Cagliari              | 1        | 1.19%   |
| Belluno               | 1        | 1.19%   |
| Barlassina            | 1        | 1.19%   |
| Bari                  | 1        | 1.19%   |
| Ancona                | 1        | 1.19%   |
| Adelfia               | 1        | 1.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 20       | 38     | 19.42%  |
| Samsung Electronics | 13       | 19     | 12.62%  |
| Seagate             | 12       | 16     | 11.65%  |
| Crucial             | 11       | 19     | 10.68%  |
| Toshiba             | 7        | 17     | 6.8%    |
| Transcend           | 5        | 6      | 4.85%   |
| Kingston            | 5        | 5      | 4.85%   |
| SanDisk             | 3        | 3      | 2.91%   |
| EMTEC               | 3        | 4      | 2.91%   |
| PNY                 | 2        | 5      | 1.94%   |
| Phison              | 2        | 2      | 1.94%   |
| OCZ                 | 2        | 2      | 1.94%   |
| NVMe                | 2        | 2      | 1.94%   |
| Micron Technology   | 2        | 2      | 1.94%   |
| Maxtor              | 2        | 2      | 1.94%   |
| Hoodisk             | 2        | 2      | 1.94%   |
| Dogfish             | 2        | 2      | 1.94%   |
| Silicon Motion      | 1        | 2      | 0.97%   |
| Pccooler            | 1        | 1      | 0.97%   |
| KingSpec            | 1        | 2      | 0.97%   |
| Intel               | 1        | 2      | 0.97%   |
| Innodisk            | 1        | 1      | 0.97%   |
| Hitachi             | 1        | 1      | 0.97%   |
| China               | 1        | 1      | 0.97%   |
| A-DATA Technology   | 1        | 2      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| EMTEC X150 120GB                 | 3        | 2.59%   |
| WDC WD5000AAKS-22V1A0 500GB      | 2        | 1.72%   |
| Toshiba HDWG440 4TB              | 2        | 1.72%   |
| Toshiba DT01ACA050 500GB         | 2        | 1.72%   |
| Seagate ST320LT007-9ZV142 320GB  | 2        | 1.72%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 1.72%   |
| Samsung SSD 860 EVO 250GB        | 2        | 1.72%   |
| Samsung SSD 850 EVO 250GB        | 2        | 1.72%   |
| Samsung HM321HI 320GB            | 2        | 1.72%   |
| Phison SATA SSD 16GB             | 2        | 1.72%   |
| Crucial CT500MX500SSD1 500GB     | 2        | 1.72%   |
| Crucial CT250MX500SSD1 250GB     | 2        | 1.72%   |
| Crucial CT240BX500SSD1 240GB     | 2        | 1.72%   |
| Crucial CT120BX500SSD1 120GB     | 2        | 1.72%   |
| WDC WDS250G1B0A-00H9H0 250GB     | 1        | 0.86%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1        | 0.86%   |
| WDC WDS100T2B0A-00SM50 1TB       | 1        | 0.86%   |
| WDC WD6400AAKS-65A7B0 640GB      | 1        | 0.86%   |
| WDC WD5003ABYX-01WERA2 500GB     | 1        | 0.86%   |
| WDC WD5000LPVT-80G33T2 500GB     | 1        | 0.86%   |
| WDC WD5000BPKX-00HPJT0 500GB     | 1        | 0.86%   |
| WDC WD5000BMVV-11A1CS0 500GB     | 1        | 0.86%   |
| WDC WD5000BEVT-00A03T0 500GB     | 1        | 0.86%   |
| WDC WD5000AAKS-00E4A0 500GB      | 1        | 0.86%   |
| WDC WD5000AAKS-00D2B0 500GB      | 1        | 0.86%   |
| WDC WD40NMZW-11GX6S1 4TB         | 1        | 0.86%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.86%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.86%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 0.86%   |
| WDC WD30EZRZ-00Z5HB0 3TB         | 1        | 0.86%   |
| WDC WD30EZRZ-00GXCB0 3TB         | 1        | 0.86%   |
| WDC WD2500BEVT-22A23T0 250GB     | 1        | 0.86%   |
| WDC WD2500AAJS-07M0A0 250GB      | 1        | 0.86%   |
| WDC WD20PURZ-85GU6Y0 2TB         | 1        | 0.86%   |
| WDC WD20EVDS-63T3B0 2TB          | 1        | 0.86%   |
| WDC WD2002FYPS-01U1B1 2TB        | 1        | 0.86%   |
| WDC WD15EADS-00P8B0 1.5TB        | 1        | 0.86%   |
| WDC WD1500HLFS-01G6U0 150GB      | 1        | 0.86%   |
| WDC WD10EFRX-68PJCN0 1TB         | 1        | 0.86%   |
| WDC WD1000DHTZ-04N21V1 1TB       | 1        | 0.86%   |
| Transcend TS64GSSD370S 64GB      | 1        | 0.86%   |
| Transcend TS64GMSA370 64GB       | 1        | 0.86%   |
| Transcend TS32GSSD370 32GB       | 1        | 0.86%   |
| Transcend TS128GMSA370 128GB     | 1        | 0.86%   |
| Transcend TS128GMSA230S 128GB    | 1        | 0.86%   |
| Toshiba Q300 240GB               | 1        | 0.86%   |
| Toshiba MK5065GSXF 500GB         | 1        | 0.86%   |
| Toshiba MG06ACA800E 8TB          | 1        | 0.86%   |
| Silicon Motion ASint AS806 128GB | 1        | 0.86%   |
| Seagate ST500LX025-1U717D 500GB  | 1        | 0.86%   |
| Seagate ST500LM021-1KJ152 500GB  | 1        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB  | 1        | 0.86%   |
| Seagate ST4000LM024-2AN17V 4TB   | 1        | 0.86%   |
| Seagate ST32500NSSUN250G 250GB   | 1        | 0.86%   |
| Seagate ST31500341AS 1.5TB       | 1        | 0.86%   |
| Seagate ST3000DM007-1WY10G 3TB   | 1        | 0.86%   |
| Seagate ST1000LX015-1U7172 1TB   | 1        | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB   | 1        | 0.86%   |
| SanDisk SSD PLUS 120GB           | 1        | 0.86%   |
| SanDisk SDSSDP128G 128GB         | 1        | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 35     | 41.86%  |
| Seagate             | 12       | 16     | 27.91%  |
| Toshiba             | 6        | 14     | 13.95%  |
| Samsung Electronics | 3        | 3      | 6.98%   |
| Maxtor              | 2        | 2      | 4.65%   |
| NVMe                | 1        | 1      | 2.33%   |
| Hitachi             | 1        | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 10       | 18     | 17.24%  |
| Samsung Electronics | 9        | 14     | 15.52%  |
| Transcend           | 5        | 6      | 8.62%   |
| Kingston            | 5        | 5      | 8.62%   |
| WDC                 | 3        | 3      | 5.17%   |
| SanDisk             | 3        | 3      | 5.17%   |
| EMTEC               | 3        | 4      | 5.17%   |
| PNY                 | 2        | 5      | 3.45%   |
| Phison              | 2        | 2      | 3.45%   |
| OCZ                 | 2        | 2      | 3.45%   |
| Micron Technology   | 2        | 2      | 3.45%   |
| Hoodisk             | 2        | 2      | 3.45%   |
| Dogfish             | 2        | 2      | 3.45%   |
| Toshiba             | 1        | 3      | 1.72%   |
| Pccooler            | 1        | 1      | 1.72%   |
| NVMe                | 1        | 1      | 1.72%   |
| KingSpec            | 1        | 2      | 1.72%   |
| Intel               | 1        | 2      | 1.72%   |
| Innodisk            | 1        | 1      | 1.72%   |
| China               | 1        | 1      | 1.72%   |
| A-DATA Technology   | 1        | 2      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 45       | 81     | 55.56%  |
| HDD  | 32       | 72     | 39.51%  |
| NVMe | 4        | 5      | 4.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 66       | 153    | 94.29%  |
| NVMe | 4        | 5      | 5.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 58       | 118    | 70.73%  |
| 0.51-1.0   | 11       | 13     | 13.41%  |
| 1.01-2.0   | 6        | 8      | 7.32%   |
| 3.01-4.0   | 5        | 8      | 6.1%    |
| 2.01-3.0   | 1        | 3      | 1.22%   |
| 4.01-10.0  | 1        | 3      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 20       | 27.4%   |
| 1-20           | 19       | 26.03%  |
| 251-500        | 12       | 16.44%  |
| 21-50          | 7        | 9.59%   |
| 501-1000       | 6        | 8.22%   |
| 51-100         | 5        | 6.85%   |
| More than 3000 | 3        | 4.11%   |
| Unknown        | 1        | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 64       | 90.14%  |
| 21-50          | 3        | 4.23%   |
| More than 3000 | 1        | 1.41%   |
| 1001-2000      | 1        | 1.41%   |
| 501-1000       | 1        | 1.41%   |
| Unknown        | 1        | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2        | 2      | 14.29%  |
| Seagate ST320LT007-9ZV142 320GB   | 2        | 2      | 14.29%  |
| WDC WD5000AAKS-00E4A0 500GB       | 1        | 1      | 7.14%   |
| WDC WD20EVDS-63T3B0 2TB           | 1        | 1      | 7.14%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1        | 1      | 7.14%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 3      | 7.14%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1        | 1      | 7.14%   |
| Seagate ST31500341AS 1.5TB        | 1        | 1      | 7.14%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 7.14%   |
| OCZ VERTEX3 120GB                 | 1        | 1      | 7.14%   |
| A-DATA Technology SX300 128GB     | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 42.86%  |
| WDC                 | 5        | 5      | 35.71%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| OCZ                 | 1        | 1      | 7.14%   |
| A-DATA Technology   | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 6        | 8      | 50%     |
| WDC                 | 5        | 5      | 41.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 14     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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
| Works    | 58       | 127    | 76.32%  |
| Malfunc  | 12       | 16     | 15.79%  |
| Detected | 6        | 15     | 7.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 50       | 57.47%  |
| AMD                              | 18       | 20.69%  |
| Samsung Electronics              | 3        | 3.45%   |
| Marvell Technology Group         | 3        | 3.45%   |
| VIA Technologies                 | 2        | 2.3%    |
| Broadcom / LSI                   | 2        | 2.3%    |
| ASMedia Technology               | 2        | 2.3%    |
| Silicon Motion                   | 1        | 1.15%   |
| Silicon Integrated Systems [SiS] | 1        | 1.15%   |
| Micron/Crucial Technology        | 1        | 1.15%   |
| KIOXIA                           | 1        | 1.15%   |
| JMicron Technology               | 1        | 1.15%   |
| Integrated Technology Express    | 1        | 1.15%   |
| Adaptec                          | 1        | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 10.58%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 5.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 4.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 3.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 2.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3        | 2.88%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 3        | 2.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3        | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 2.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3        | 2.88%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 1.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 2        | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2        | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2        | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.96%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                             | 1        | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1        | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.96%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1        | 0.96%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.96%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.96%   |
| KIOXIA NVMe SSD                                                                         | 1        | 0.96%   |
| JMicron JMB361 AHCI/IDE                                                                 | 1        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1        | 0.96%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.96%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.96%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.96%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 1        | 0.96%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 1        | 0.96%   |
| Intel 631xESB/632xESB SATA RAID Controller                                              | 1        | 0.96%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 1        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.96%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 0.96%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 0.96%   |
| Broadcom / LSI SAS1068 PCI-X Fusion-MPT SAS                                             | 1        | 0.96%   |
| Broadcom / LSI MegaRAID SAS 8208ELP/8208ELP                                             | 1        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [RAID5 mode]                                      | 1        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1        | 0.96%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1        | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 0.96%   |
| Adaptec AIC-7870P/7881U [AHA-2940U/UW/D/S76]                                            | 1        | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 54       | 65.06%  |
| IDE  | 17       | 20.48%  |
| NVMe | 6        | 7.23%   |
| RAID | 3        | 3.61%   |
| SCSI | 3        | 3.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 51       | 71.83%  |
| AMD     | 18       | 25.35%  |
| Arm     | 1        | 1.41%   |
| Unknown | 1        | 1.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD GX-412TC SOC                              | 4        | 5.63%   |
| AMD Phenom II X4 965 Processor                | 3        | 4.23%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2        | 2.82%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 2.82%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 2        | 2.82%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 2.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2        | 2.82%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 2        | 2.82%   |
| Intel Xeon CPU X3470 @ 2.93GHz                | 1        | 1.41%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1        | 1.41%   |
| Intel Xeon CPU E5440 @ 2.83GHz                | 1        | 1.41%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1        | 1.41%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1        | 1.41%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1        | 1.41%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 1.41%   |
| Intel Pentium Dual-Core CPU E6600             | 1        | 1.41%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1        | 1.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1        | 1.41%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1        | 1.41%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1        | 1.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1        | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1        | 1.41%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1        | 1.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 1.41%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1        | 1.41%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1        | 1.41%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1        | 1.41%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1        | 1.41%   |
| Intel Core i5-4210Y CPU @ 1.50GHz             | 1        | 1.41%   |
| Intel Core i5 CPU                             | 1        | 1.41%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 1.41%   |
| Intel Core i3-3225 CPU @ 3.30GHz              | 1        | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 1        | 1.41%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1        | 1.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 1        | 1.41%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 1.41%   |
| Intel Core 2 Extreme CPU X9650 @ 3.00GHz      | 1        | 1.41%   |
| Intel Core 2 Duo CPU E7500                    | 1        | 1.41%   |
| Intel Core 2 Duo                              | 1        | 1.41%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 1        | 1.41%   |
| Intel Celeron CPU J3355 @ 2.00GHz             | 1        | 1.41%   |
| Intel Celeron CPU G550 @ 2.60GHz              | 1        | 1.41%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 1        | 1.41%   |
| Intel Atom CPU D2500 @ 1.86GHz                | 1        | 1.41%   |
| Intel Atom CPU 330 @ 1.60GHz                  | 1        | 1.41%   |
| Intel Atom CPU 230 @ 1.60GHz                  | 1        | 1.41%   |
| Arm Cortex-A53 r0p4 (v8-A)                    | 1        | 1.41%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 1        | 1.41%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 1        | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1        | 1.41%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 1        | 1.41%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 1        | 1.41%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 1        | 1.41%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 1        | 1.41%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 1        | 1.41%   |
| AMD FX-9590 Eight-Core Processor              | 1        | 1.41%   |
| AMD E2-3200 APU with Radeon HD Graphics       | 1        | 1.41%   |
| AMD Athlon II X4 640 Processor                | 1        | 1.41%   |
|                                               | 1        | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 9        | 12.68%  |
| Intel Celeron           | 9        | 12.68%  |
| Intel Xeon              | 7        | 9.86%   |
| Intel Core i5           | 6        | 8.45%   |
| Intel Core i7           | 5        | 7.04%   |
| AMD GX                  | 5        | 7.04%   |
| Intel Atom              | 4        | 5.63%   |
| Intel Pentium Dual      | 3        | 4.23%   |
| AMD Ryzen 5             | 3        | 4.23%   |
| AMD Phenom II X4        | 3        | 4.23%   |
| Other                   | 2        | 2.82%   |
| Intel Pentium Dual-Core | 2        | 2.82%   |
| Intel Pentium           | 2        | 2.82%   |
| Intel Core 2 Duo        | 2        | 2.82%   |
| AMD Ryzen 7             | 2        | 2.82%   |
| Intel Core 2 Quad       | 1        | 1.41%   |
| Intel Core 2 Extreme    | 1        | 1.41%   |
| AMD Ryzen 9             | 1        | 1.41%   |
| AMD Ryzen 3             | 1        | 1.41%   |
| AMD FX                  | 1        | 1.41%   |
| AMD E2                  | 1        | 1.41%   |
| AMD Athlon II X4        | 1        | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 31       | 43.66%  |
| 2       | 23       | 32.39%  |
| Unknown | 7        | 9.86%   |
| 12      | 3        | 4.23%   |
| 16      | 2        | 2.82%   |
| 8       | 2        | 2.82%   |
| 32      | 1        | 1.41%   |
| 6       | 1        | 1.41%   |
| 1       | 1        | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 67       | 94.37%  |
| Unknown | 3        | 4.23%   |
| 2       | 1        | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 37       | 52.11%  |
| 2       | 27       | 38.03%  |
| Unknown | 7        | 9.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 7        | 9.86%   |
| SandyBridge   | 6        | 8.45%   |
| Penryn        | 6        | 8.45%   |
| Puma          | 4        | 5.63%   |
| KabyLake      | 4        | 5.63%   |
| K10           | 4        | 5.63%   |
| IvyBridge     | 4        | 5.63%   |
| Core          | 4        | 5.63%   |
| Bonnell       | 4        | 5.63%   |
| Nehalem       | 3        | 4.23%   |
| Goldmont plus | 3        | 4.23%   |
| Goldmont      | 3        | 4.23%   |
| CometLake     | 3        | 4.23%   |
| Zen+          | 2        | 2.82%   |
| Zen 3         | 2        | 2.82%   |
| Zen 2         | 2        | 2.82%   |
| Silvermont    | 2        | 2.82%   |
| Unknown       | 2        | 2.82%   |
| Zen           | 1        | 1.41%   |
| Westmere      | 1        | 1.41%   |
| Piledriver    | 1        | 1.41%   |
| K10 Llano     | 1        | 1.41%   |
| Jaguar        | 1        | 1.41%   |
| Broadwell     | 1        | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 34       | 50.75%  |
| AMD                              | 17       | 25.37%  |
| Nvidia                           | 14       | 20.9%   |
| Silicon Integrated Systems [SiS] | 1        | 1.49%   |
| Matrox Electronics Systems       | 1        | 1.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 7.46%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 5.97%   |
| Intel HD Graphics 500                                                                    | 3        | 4.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 4.48%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 2.99%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.99%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 2.99%   |
| Intel HD Graphics 620                                                                    | 2        | 2.99%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2        | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.99%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.99%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 2.99%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 1.49%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.49%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.49%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 1.49%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.49%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1        | 1.49%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.49%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.49%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.49%   |
| Intel HD Graphics 630                                                                    | 1        | 1.49%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1        | 1.49%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 1.49%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.49%   |
| AMD SuperSumo [Radeon HD 6370D]                                                          | 1        | 1.49%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 1        | 1.49%   |
| AMD RS880 [Radeon HD 4250]                                                               | 1        | 1.49%   |
| AMD RS880 [Radeon HD 4200]                                                               | 1        | 1.49%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.49%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1        | 1.49%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                   | 1        | 1.49%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 1        | 1.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 32       | 44.44%  |
| 1 x AMD        | 17       | 23.61%  |
| 1 x Nvidia     | 13       | 18.06%  |
| Other          | 6        | 8.33%   |
| 2 x Intel      | 1        | 1.39%   |
| 1 x SiS        | 1        | 1.39%   |
| 1 x Matrox     | 1        | 1.39%   |
| Intel + Nvidia | 1        | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 54       | 73.97%  |
| Proprietary | 12       | 16.44%  |
| Unknown     | 7        | 9.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 54       | 73.97%  |
| 1.01-2.0   | 6        | 8.22%   |
| 3.01-4.0   | 5        | 6.85%   |
| 0.51-1.0   | 4        | 5.48%   |
| 0.01-0.5   | 2        | 2.74%   |
| 7.01-8.0   | 1        | 1.37%   |
| 5.01-6.0   | 1        | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 8        | 22.86%  |
| Samsung Electronics  | 7        | 20%     |
| Acer                 | 4        | 11.43%  |
| Hewlett-Packard      | 3        | 8.57%   |
| Goldstar             | 2        | 5.71%   |
| Dell                 | 2        | 5.71%   |
| Sony                 | 1        | 2.86%   |
| Packard Bell         | 1        | 2.86%   |
| Orion                | 1        | 2.86%   |
| LG Electronics       | 1        | 2.86%   |
| Iiyama               | 1        | 2.86%   |
| Eizo                 | 1        | 2.86%   |
| ASUSTek Computer     | 1        | 2.86%   |
| Apple                | 1        | 2.86%   |
| Ancor Communications | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 6        | 17.14%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 5.71%   |
| Sony TV SNY5D01 1360x768                                              | 1        | 2.86%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 2.86%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 2.86%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1        | 2.86%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 2.86%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1        | 2.86%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 2.86%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1        | 2.86%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1        | 2.86%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1        | 2.86%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1        | 2.86%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                | 1        | 2.86%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 2.86%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch             | 1        | 2.86%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 2.86%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 2.86%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch           | 1        | 2.86%   |
| Eizo LCD Monitor S1901 1280x1024                                      | 1        | 2.86%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                     | 1        | 2.86%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                     | 1        | 2.86%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1        | 2.86%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1        | 2.86%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 2.86%   |
| Acer X203H ACR0097 1600x900 440x250mm 19.9-inch                       | 1        | 2.86%   |
| Acer RT240Y ACR0539 1920x1080 530x300mm 24.0-inch                     | 1        | 2.86%   |
| Acer R271 ACR0496 1920x1080 600x340mm 27.2-inch                       | 1        | 2.86%   |
| Acer AL1917 ACRAD63 1280x1024 380x300mm 19.1-inch                     | 1        | 2.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 21       | 65.63%  |
| 1280x1024 (SXGA)  | 3        | 9.38%   |
| 1920x1200 (WUXGA) | 2        | 6.25%   |
| 3840x2160 (4K)    | 1        | 3.13%   |
| 2560x1080         | 1        | 3.13%   |
| 1600x900 (HD+)    | 1        | 3.13%   |
| 1440x900 (WXGA+)  | 1        | 3.13%   |
| 1360x768          | 1        | 3.13%   |
| 1024x768 (XGA)    | 1        | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 8        | 22.86%  |
| Unknown | 7        | 20%     |
| 24      | 4        | 11.43%  |
| 19      | 4        | 11.43%  |
| 27      | 3        | 8.57%   |
| 23      | 3        | 8.57%   |
| 31      | 2        | 5.71%   |
| 28      | 2        | 5.71%   |
| 22      | 1        | 2.86%   |
| 14      | 1        | 2.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 10       | 30.3%   |
| 501-600     | 8        | 24.24%  |
| Unknown     | 7        | 21.21%  |
| 601-700     | 5        | 15.15%  |
| 351-400     | 2        | 6.06%   |
| 201-300     | 1        | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 22       | 70.97%  |
| 16/10   | 3        | 9.68%   |
| 5/4     | 2        | 6.45%   |
| Unknown | 2        | 6.45%   |
| 4/3     | 1        | 3.23%   |
| 21/9    | 1        | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 36.36%  |
| Unknown        | 7        | 21.21%  |
| 151-200        | 4        | 12.12%  |
| 351-500        | 3        | 9.09%   |
| 301-350        | 3        | 9.09%   |
| 251-300        | 3        | 9.09%   |
| 101-110        | 1        | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 51.52%  |
| 101-120 | 8        | 24.24%  |
| Unknown | 7        | 21.21%  |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 41       | 56.16%  |
| 1     | 30       | 41.1%   |
| 2     | 2        | 2.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 41       | 45.56%  |
| Realtek Semiconductor | 34       | 37.78%  |
| Broadcom              | 5        | 5.56%   |
| Qualcomm Atheros      | 4        | 4.44%   |
| Ralink                | 2        | 2.22%   |
| Ralink Technology     | 1        | 1.11%   |
| IMC Networks          | 1        | 1.11%   |
| Digital Equipment     | 1        | 1.11%   |
| Davicom Semiconductor | 1        | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 29       | 28.16%  |
| Intel I211 Gigabit Network Connection                                                 | 14       | 13.59%  |
| Intel 82574L Gigabit Network Connection                                               | 4        | 3.88%   |
| Intel I210 Gigabit Network Connection                                                 | 3        | 2.91%   |
| Intel 82579V Gigabit Network Connection                                               | 3        | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 2.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2        | 1.94%   |
| Intel I350 Gigabit Network Connection                                                 | 2        | 1.94%   |
| Intel Ethernet Connection I217-LM                                                     | 2        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 0.97%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1        | 0.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 0.97%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 0.97%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 0.97%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 0.97%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 0.97%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.97%   |
| Intel Wireless 3165                                                                   | 1        | 0.97%   |
| Intel Ethernet Controller I225-V                                                      | 1        | 0.97%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                         | 1        | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                                  | 1        | 0.97%   |
| Intel Ethernet Connection (2) I218-LM                                                 | 1        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 0.97%   |
| Intel 82583V Gigabit Network Connection                                               | 1        | 0.97%   |
| Intel 82578DM Gigabit Network Connection                                              | 1        | 0.97%   |
| Intel 82575EB Gigabit Network Connection                                              | 1        | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications)         | 1        | 0.97%   |
| Intel 82571EB Gigabit Ethernet Controller                                             | 1        | 0.97%   |
| Intel 82567V-2 Gigabit Network Connection                                             | 1        | 0.97%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 1        | 0.97%   |
| Intel 82567LF-2 Gigabit Network Connection                                            | 1        | 0.97%   |
| Intel 82566DM-2 Gigabit Network Connection                                            | 1        | 0.97%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                                  | 1        | 0.97%   |
| Intel 82541GI Gigabit Ethernet Controller                                             | 1        | 0.97%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 0.97%   |
| Digital Equipment DECchip 21142/43                                                    | 1        | 0.97%   |
| Davicom DM9102 Fast Ethernet Controller                                               | 1        | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                                     | 1        | 0.97%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                               | 1        | 0.97%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                               | 1        | 0.97%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 1        | 0.97%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                         | 1        | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 28.57%  |
| Qualcomm Atheros      | 4        | 28.57%  |
| Ralink                | 2        | 14.29%  |
| Intel                 | 2        | 14.29%  |
| Ralink Technology     | 1        | 7.14%   |
| IMC Networks          | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 6.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 6.25%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 6.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 6.25%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 6.25%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 6.25%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 6.25%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 6.25%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 6.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 6.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1        | 6.25%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 6.25%   |
| Intel Wireless 3165                                                                   | 1        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 6.25%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 40       | 51.28%  |
| Realtek Semiconductor | 31       | 39.74%  |
| Broadcom              | 5        | 6.41%   |
| Digital Equipment     | 1        | 1.28%   |
| Davicom Semiconductor | 1        | 1.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 29       | 33.33%  |
| Intel I211 Gigabit Network Connection                                         | 14       | 16.09%  |
| Intel 82574L Gigabit Network Connection                                       | 4        | 4.6%    |
| Intel I210 Gigabit Network Connection                                         | 3        | 3.45%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 3        | 3.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 2.3%    |
| Intel I350 Gigabit Network Connection                                         | 2        | 2.3%    |
| Intel Ethernet Connection I217-LM                                             | 2        | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 1.15%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.15%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 1.15%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 1.15%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 1.15%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 1.15%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 1.15%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 1.15%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.15%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 1.15%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 1.15%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 1.15%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 1.15%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 1.15%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 1.15%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 1.15%   |
| Digital Equipment DECchip 21142/43                                            | 1        | 1.15%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1        | 1.15%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 1.15%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 1.15%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1        | 1.15%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 1.15%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1        | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 84.15%  |
| WiFi     | 13       | 15.85%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 69       | 92%     |
| WiFi     | 6        | 8%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 28       | 38.89%  |
| 2     | 14       | 19.44%  |
| 3     | 11       | 15.28%  |
| 4     | 9        | 12.5%   |
| 5     | 4        | 5.56%   |
| 7     | 2        | 2.78%   |
| 0     | 2        | 2.78%   |
| 8     | 1        | 1.39%   |
| 6     | 1        | 1.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 4        | 50%     |
| Integrated System Solution | 2        | 25%     |
| Realtek Semiconductor      | 1        | 12.5%   |
| Intel                      | 1        | 12.5%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 50%     |
| Integrated System Solution Bluetooth Device         | 2        | 25%     |
| Realtek  Bluetooth Adapter                          | 1        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 44       | 53.66%  |
| AMD                              | 20       | 24.39%  |
| Nvidia                           | 13       | 15.85%  |
| Logitech                         | 2        | 2.44%   |
| Silicon Integrated Systems [SiS] | 1        | 1.22%   |
| C-Media Electronics              | 1        | 1.22%   |
| Bose                             | 1        | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 5.1%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 5.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5        | 5.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 4.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 3.06%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 3.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 3.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 3.06%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 2.04%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 2.04%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 2.04%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 2.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 2.04%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2        | 2.04%   |
| AMD FCH Azalia Controller                                                                         | 2        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 2.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 2.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 2.04%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.02%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 1.02%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 1.02%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 1.02%   |
| Logitech Headset H340                                                                             | 1        | 1.02%   |
| Logitech HD Webcam C510                                                                           | 1        | 1.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.02%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1        | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1        | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.02%   |
| C-Media Electronics Audio Adapter (Planet UP-100, Genius G-Talk)                                  | 1        | 1.02%   |
| Bose Bose USB Audio                                                                               | 1        | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1        | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1        | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1        | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1        | 1.02%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 1.02%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 14       | 20.29%  |
| Kingston            | 12       | 17.39%  |
| Samsung Electronics | 7        | 10.14%  |
| SK hynix            | 6        | 8.7%    |
| Crucial             | 6        | 8.7%    |
| Corsair             | 4        | 5.8%    |
| Ramaxel Technology  | 3        | 4.35%   |
| Unknown (ABCD)      | 2        | 2.9%    |
| Nanya Technology    | 2        | 2.9%    |
| Unknown             | 2        | 2.9%    |
| Unknown (AB)        | 1        | 1.45%   |
| Transcend           | 1        | 1.45%   |
| Micron Technology   | 1        | 1.45%   |
| KomputerBay         | 1        | 1.45%   |
| Intersil            | 1        | 1.45%   |
| G.Skill             | 1        | 1.45%   |
| Elpida              | 1        | 1.45%   |
| 2C0C0843D7349CA2    | 1        | 1.45%   |
| 2C0C0843D7349C9D    | 1        | 1.45%   |
| 2C080815D82F5C7B    | 1        | 1.45%   |
| 2C0108214C359D20    | 1        | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2        | 2.6%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 2.6%    |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 2        | 2.6%    |
| Unknown                                                           | 2        | 2.6%    |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                         | 1        | 1.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.3%    |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                      | 1        | 1.3%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1        | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 1        | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1        | 1.3%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                         | 1        | 1.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 1        | 1.3%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1        | 1.3%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 1.3%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 1        | 1.3%    |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s               | 1        | 1.3%    |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s              | 1        | 1.3%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.3%    |
| SK hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s               | 1        | 1.3%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 1        | 1.3%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1        | 1.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s              | 1        | 1.3%    |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                   | 1        | 1.3%    |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.3%    |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1        | 1.3%    |
| Samsung RAM M395T5160CZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1        | 1.3%    |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s               | 1        | 1.3%    |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1        | 1.3%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.3%    |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s               | 1        | 1.3%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s           | 1        | 1.3%    |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                | 1        | 1.3%    |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s                | 1        | 1.3%    |
| Micron RAM 4ATF51264HZ-2G6B1 4GB SODIMM DDR4 1200MT/s             | 1        | 1.3%    |
| KomputerBay RAM KB_8G_D3_1600_C10 8192MB DIMM DDR3 1600MT/s       | 1        | 1.3%    |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1        | 1.3%    |
| Kingston RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.3%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s              | 1        | 1.3%    |
| Kingston RAM KHX3000C15D4/4GX 4096MB DIMM DDR4 2667MT/s           | 1        | 1.3%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s                 | 1        | 1.3%    |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s              | 1        | 1.3%    |
| Kingston RAM KHX1600C9S3L/4G 4GB SODIMM DDR3 1600MT/s             | 1        | 1.3%    |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 2400MT/s               | 1        | 1.3%    |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1067MT/s            | 1        | 1.3%    |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s              | 1        | 1.3%    |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM 667MT/s                   | 1        | 1.3%    |
| Kingston RAM 99U5474-010.A00LF 2GB DIMM DDR3 1333MT/s             | 1        | 1.3%    |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1333MT/s             | 1        | 1.3%    |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s           | 1        | 1.3%    |
| Kingston RAM 9905471-006.A01LF 4GB DIMM DDR3 1333MT/s             | 1        | 1.3%    |
| Kingston RAM 9905402-560.A00G 4GB DIMM DDR3 1333MT/s              | 1        | 1.3%    |
| Intersil RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1067MT/s             | 1        | 1.3%    |
| G.Skill RAM F3-10666CL9-4GBRL 4GB DIMM DDR3 1333MT/s              | 1        | 1.3%    |
| G.Skill RAM F3-10600CL9-2GBNT 2GB DIMM DDR3 1333MT/s              | 1        | 1.3%    |
| Elpida RAM EBJ21UE8BAFA-AE-E 2GB DIMM 1066MT/s                    | 1        | 1.3%    |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB SODIMM DDR4 2400MT/s           | 1        | 1.3%    |
| Crucial RAM CT4G4SFS824A.M8FF 4GB SODIMM DDR4 2400MT/s            | 1        | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 32       | 52.46%  |
| DDR4    | 12       | 19.67%  |
| DDR2    | 10       | 16.39%  |
| Unknown | 5        | 8.2%    |
| LPDDR4  | 2        | 3.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 42       | 71.19%  |
| SODIMM  | 16       | 27.12%  |
| FB-DIMM | 1        | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 25       | 39.06%  |
| 2048  | 17       | 26.56%  |
| 8192  | 14       | 21.88%  |
| 16384 | 4        | 6.25%   |
| 1024  | 3        | 4.69%   |
| 32768 | 1        | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 15       | 23.08%  |
| 1600  | 14       | 21.54%  |
| 2400  | 8        | 12.31%  |
| 800   | 6        | 9.23%   |
| 1067  | 5        | 7.69%   |
| 2667  | 4        | 6.15%   |
| 667   | 4        | 6.15%   |
| 2133  | 2        | 3.08%   |
| 1066  | 2        | 3.08%   |
| 3200  | 1        | 1.54%   |
| 2933  | 1        | 1.54%   |
| 2666  | 1        | 1.54%   |
| 1866  | 1        | 1.54%   |
| 1200  | 1        | 1.54%   |

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
| 1     | 41       | 56.94%  |
| 0     | 28       | 38.89%  |
| 2     | 2        | 2.78%   |
| 3     | 1        | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 33       | 71.74%  |
| Firewire controller      | 8        | 17.39%  |
| Net/wireless             | 3        | 6.52%   |
| Card reader              | 2        | 4.35%   |

