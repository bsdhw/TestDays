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

Total: 156

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Veriton X2610G              | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Unknown       | Unknown                     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| ASRock        | J3355B-ITX                  | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| HP            | 1496                        | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| ASUSTek       | M4A87TD EVO                 | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Unknown       | Unknown                     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| Unknown       | Unknown                     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
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
| ASUSTek       | BM6835_BM6635_BP6335        | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
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
| Unknown       | Unknown                     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
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
| ASUSTek       | PRIME Z390M-PLUS            | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
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


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| OpenBSD 7.1       | 7        | 6.14%   |
| helloSystem 0.4.0 | 7        | 6.14%   |
| OPNsense 22.7     | 6        | 5.26%   |
| helloSystem 0.7.0 | 6        | 5.26%   |
| OPNsense 22.7.6   | 4        | 3.51%   |
| OPNsense 22.1     | 4        | 3.51%   |
| OPNsense 21.1     | 4        | 3.51%   |
| helloSystem 0.5.0 | 4        | 3.51%   |
| OPNsense 22.7.3   | 3        | 2.63%   |
| OPNsense 22.1.9   | 3        | 2.63%   |
| OPNsense 22.1.10  | 3        | 2.63%   |
| OPNsense 21.7.3   | 3        | 2.63%   |
| helloSystem 0.6.0 | 3        | 2.63%   |
| helloSystem 0.3.0 | 3        | 2.63%   |
| OPNsense 22.7.5   | 2        | 1.75%   |
| OPNsense 22.7.4   | 2        | 1.75%   |
| OPNsense 22.7.2   | 2        | 1.75%   |
| OPNsense 22.7.1   | 2        | 1.75%   |
| OPNsense 22.1.8   | 2        | 1.75%   |
| OPNsense 22.1.6   | 2        | 1.75%   |
| OPNsense 22.1.4   | 2        | 1.75%   |
| OPNsense 21.7.7   | 2        | 1.75%   |
| OPNsense 21.1.3   | 2        | 1.75%   |
| OPNsense 21.1.2   | 2        | 1.75%   |
| OPNsense 20.7.8   | 2        | 1.75%   |
| OpenBSD 6.8       | 2        | 1.75%   |
| NomadBSD 1.4      | 2        | 1.75%   |
| FreeBSD 13.1-p2   | 2        | 1.75%   |
| FreeBSD 12.3-p1   | 2        | 1.75%   |
| OPNsense 22.1.7   | 1        | 0.88%   |
| OPNsense 22.1.3   | 1        | 0.88%   |
| OPNsense 22.1.2   | 1        | 0.88%   |
| OPNsense 21.7.8   | 1        | 0.88%   |
| OPNsense 21.7.6   | 1        | 0.88%   |
| OPNsense 21.7.4   | 1        | 0.88%   |
| OPNsense 21.7.1   | 1        | 0.88%   |
| OPNsense 21.7     | 1        | 0.88%   |
| OPNsense 21.1.8   | 1        | 0.88%   |
| OPNsense 21.1.7   | 1        | 0.88%   |
| OPNsense 21.1.5   | 1        | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 42       | 49.41%  |
| helloSystem | 17       | 20%     |
| FreeBSD     | 13       | 15.29%  |
| OpenBSD     | 9        | 10.59%  |
| NomadBSD    | 2        | 2.35%   |
| NetBSD      | 2        | 2.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 82       | 96.47%  |
| evbarm | 2        | 2.35%   |
| i386   | 1        | 1.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Console       | 46       | 54.12%  |
| helloDesktop  | 21       | 24.71%  |
| XFCE          | 4        | 4.71%   |
| MATE          | 3        | 3.53%   |
| TWM           | 2        | 2.35%   |
| Openbox       | 2        | 2.35%   |
| KDE5          | 2        | 2.35%   |
| fvwm          | 2        | 2.35%   |
| xfwm          | 1        | 1.18%   |
| Enlightenment | 1        | 1.18%   |
| CTWM          | 1        | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 49       | 56.98%  |
| X11     | 37       | 43.02%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 62       | 72.94%  |
| SLiM    | 21       | 24.71%  |
| LightDM | 2        | 2.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 56       | 65.12%  |
| en_US            | 18       | 20.93%  |
| it_IT            | 6        | 6.98%   |
| C                | 5        | 5.81%   |
| it_IT.ISO8859-15 | 1        | 1.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 66       | 75.86%  |
| BIOS | 21       | 24.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Ufs    | 46       | 52.27%  |
| Zfs    | 29       | 32.95%  |
| Ffs    | 9        | 10.23%  |
| Cd9660 | 4        | 4.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 73       | 83.91%  |
| MBR     | 12       | 13.79%  |
| Unknown | 2        | 2.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUSTek Computer           | 16       | 18.82%  |
| Unknown                    | 10       | 11.76%  |
| Intel                      | 8        | 9.41%   |
| Hewlett-Packard            | 7        | 8.24%   |
| ASRock                     | 6        | 7.06%   |
| PC Engines                 | 5        | 5.88%   |
| MSI                        | 4        | 4.71%   |
| Gigabyte Technology        | 4        | 4.71%   |
| Fujitsu                    | 4        | 4.71%   |
| Dell                       | 4        | 4.71%   |
| Pegatron                   | 2        | 2.35%   |
| Lenovo                     | 2        | 2.35%   |
| Acer                       | 2        | 2.35%   |
| T-bao                      | 1        | 1.18%   |
| Supermicro                 | 1        | 1.18%   |
| Sun Microsystems           | 1        | 1.18%   |
| ShenZhen MinWin Technology | 1        | 1.18%   |
| Protectli                  | 1        | 1.18%   |
| NF692                      | 1        | 1.18%   |
| MW                         | 1        | 1.18%   |
| Lex                        | 1        | 1.18%   |
| HARDKERNEL                 | 1        | 1.18%   |
| Foxconn                    | 1        | 1.18%   |
| AZW                        | 1        | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 10       | 11.76%  |
| PC Engines APU2                         | 3        | 3.53%   |
| Intel Q3XXG4-P V1.0                     | 3        | 3.53%   |
| MSI MS-7B86                             | 2        | 2.35%   |
| Lenovo ThinkCentre M83 10AHS35Q00       | 2        | 2.35%   |
| Fujitsu FUTRO S920                      | 2        | 2.35%   |
| ASUS PRIME H410M-A                      | 2        | 2.35%   |
| ASUS M4A88TD-V EVO/USB3                 | 2        | 2.35%   |
| ASUS IP4BL-ME                           | 2        | 2.35%   |
| T-bao MINI PC                           | 1        | 1.18%   |
| Supermicro X8STi                        | 1        | 1.18%   |
| Sun Microsystems Ultra 24               | 1        | 1.18%   |
| ShenZhen MinWin MW-NANO-APL-4L          | 1        | 1.18%   |
| Protectli FW4B                          | 1        | 1.18%   |
| Pegatron Pro 3405 Series                | 1        | 1.18%   |
| Pegatron KX629AA-ABZ a6561.it           | 1        | 1.18%   |
| PC Engines apu4                         | 1        | 1.18%   |
| PC Engines APU3                         | 1        | 1.18%   |
| NF692 1.0                               | 1        | 1.18%   |
| MW GMLK-2_5G4L                          | 1        | 1.18%   |
| MSI NR074AA-ABZ CQ5125IT                | 1        | 1.18%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159) | 1        | 1.18%   |
| Lex Pineview-D                          | 1        | 1.18%   |
| Intel NCB-4210WG                        | 1        | 1.18%   |
| Intel MAHOBAY                           | 1        | 1.18%   |
| Intel J1900                             | 1        | 1.18%   |
| Intel D945GCLF2                         | 1        | 1.18%   |
| Intel D2500CC AAG81477-401              | 1        | 1.18%   |
| HP Z440 Workstation                     | 1        | 1.18%   |
| HP xw8600 Workstation                   | 1        | 1.18%   |
| HP Slim Desktop S01-aF2xxx              | 1        | 1.18%   |
| HP ProLiant MicroServer Gen8            | 1        | 1.18%   |
| HP Compaq Elite 8300 SFF                | 1        | 1.18%   |
| HP Compaq 8200 Elite USDT PC            | 1        | 1.18%   |
| HP Compaq 8100 Elite CMT PC             | 1        | 1.18%   |
| HARDKERNEL ODROID-H2                    | 1        | 1.18%   |
| Gigabyte X570 AORUS PRO                 | 1        | 1.18%   |
| Gigabyte X570 AORUS ELITE               | 1        | 1.18%   |
| Gigabyte P55A-UD3                       | 1        | 1.18%   |
| Gigabyte H270M-DS3H                     | 1        | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Unknown                        | 10       | 11.76%  |
| ASUS PRIME                     | 6        | 7.06%   |
| PC Engines APU2                | 3        | 3.53%   |
| Intel Q3XXG4-P                 | 3        | 3.53%   |
| HP Compaq                      | 3        | 3.53%   |
| MSI MS-7B86                    | 2        | 2.35%   |
| Lenovo ThinkCentre             | 2        | 2.35%   |
| Gigabyte X570                  | 2        | 2.35%   |
| Fujitsu FUTRO                  | 2        | 2.35%   |
| Fujitsu ESPRIMO                | 2        | 2.35%   |
| ASUS M4A88TD-V                 | 2        | 2.35%   |
| ASUS IP4BL-ME                  | 2        | 2.35%   |
| T-bao MINI                     | 1        | 1.18%   |
| Supermicro X8STi               | 1        | 1.18%   |
| Sun Microsystems Ultra         | 1        | 1.18%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1        | 1.18%   |
| Protectli FW4B                 | 1        | 1.18%   |
| Pegatron Pro                   | 1        | 1.18%   |
| Pegatron KX629AA-ABZ           | 1        | 1.18%   |
| PC Engines apu4                | 1        | 1.18%   |
| PC Engines APU3                | 1        | 1.18%   |
| NF692 1.0                      | 1        | 1.18%   |
| MW GMLK-2                      | 1        | 1.18%   |
| MSI NR074AA-ABZ                | 1        | 1.18%   |
| MSI KBL-U                      | 1        | 1.18%   |
| Lex Pineview-D                 | 1        | 1.18%   |
| Intel NCB-4210WG               | 1        | 1.18%   |
| Intel MAHOBAY                  | 1        | 1.18%   |
| Intel J1900                    | 1        | 1.18%   |
| Intel D945GCLF2                | 1        | 1.18%   |
| Intel D2500CC                  | 1        | 1.18%   |
| HP Z440                        | 1        | 1.18%   |
| HP xw8600                      | 1        | 1.18%   |
| HP Slim                        | 1        | 1.18%   |
| HP ProLiant                    | 1        | 1.18%   |
| HARDKERNEL ODROID-H2           | 1        | 1.18%   |
| Gigabyte P55A-UD3              | 1        | 1.18%   |
| Gigabyte H270M-DS3H            | 1        | 1.18%   |
| Foxconn p6-2305elm             | 1        | 1.18%   |
| Dell Studio                    | 1        | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2016    | 8        | 9.41%   |
| 2010    | 8        | 9.41%   |
| 2019    | 7        | 8.24%   |
| 2014    | 7        | 8.24%   |
| 2012    | 7        | 8.24%   |
| 2011    | 7        | 8.24%   |
| 2021    | 6        | 7.06%   |
| 2020    | 6        | 7.06%   |
| 2018    | 6        | 7.06%   |
| 2017    | 5        | 5.88%   |
| 2008    | 5        | 5.88%   |
| 2009    | 4        | 4.71%   |
| 2015    | 3        | 3.53%   |
| Unknown | 3        | 3.53%   |
| 2022    | 2        | 2.35%   |
| 2013    | 1        | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 85       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 80       | 94.12%  |
| Yes  | 5        | 5.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 36       | 41.86%  |
| 4.01-8.0    | 22       | 25.58%  |
| 16.01-24.0  | 10       | 11.63%  |
| 2.01-3.0    | 7        | 8.14%   |
| 32.01-64.0  | 5        | 5.81%   |
| 24.01-32.0  | 2        | 2.33%   |
| 64.01-256.0 | 2        | 2.33%   |
| 3.01-4.0    | 1        | 1.16%   |
| 0.51-1.0    | 1        | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 55       | 63.95%  |
| 0.51-1.0 | 21       | 24.42%  |
| 1.01-2.0 | 5        | 5.81%   |
| 2.01-3.0 | 2        | 2.33%   |
| Unknown  | 2        | 2.33%   |
| 4.01-8.0 | 1        | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 55.68%  |
| 2      | 18       | 20.45%  |
| 4      | 8        | 9.09%   |
| 3      | 6        | 6.82%   |
| 0      | 6        | 6.82%   |
| 10     | 1        | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 69.41%  |
| Yes       | 26       | 30.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 97.65%  |
| No        | 2        | 2.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 68       | 79.07%  |
| Yes       | 18       | 20.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 76       | 88.37%  |
| Yes       | 10       | 11.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 85       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Milan               | 17       | 17%     |
| Rome                | 6        | 6%      |
| Naples              | 3        | 3%      |
| Turrivalignani      | 2        | 2%      |
| Turin               | 2        | 2%      |
| Silea               | 2        | 2%      |
| Reggio Emilia       | 2        | 2%      |
| Modena              | 2        | 2%      |
| Lucca               | 2        | 2%      |
| Ancona              | 2        | 2%      |
| Viterbo             | 1        | 1%      |
| Villa Bartolomea    | 1        | 1%      |
| Venice              | 1        | 1%      |
| Trieste             | 1        | 1%      |
| Treviso             | 1        | 1%      |
| Trento              | 1        | 1%      |
| Terni               | 1        | 1%      |
| Soresina            | 1        | 1%      |
| Sasso Marconi       | 1        | 1%      |
| Sannicandro di Bari | 1        | 1%      |
| San Prospero        | 1        | 1%      |
| San Donato Milanese | 1        | 1%      |
| Reggio Calabria     | 1        | 1%      |
| Ravenna             | 1        | 1%      |
| Pozzuolo Martesana  | 1        | 1%      |
| Pontecagnano        | 1        | 1%      |
| Ponsacco            | 1        | 1%      |
| Pistoia             | 1        | 1%      |
| Pisa                | 1        | 1%      |
| Pioltello           | 1        | 1%      |
| Peschiera del Garda | 1        | 1%      |
| Parma               | 1        | 1%      |
| Padova              | 1        | 1%      |
| Ortona              | 1        | 1%      |
| Oleggio             | 1        | 1%      |
| Monza               | 1        | 1%      |
| Monteleone di Fermo | 1        | 1%      |
| Montegranaro        | 1        | 1%      |
| Mestrino            | 1        | 1%      |
| Malo                | 1        | 1%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 45     | 17.5%   |
| Seagate             | 14       | 19     | 11.67%  |
| Samsung Electronics | 14       | 20     | 11.67%  |
| Crucial             | 12       | 21     | 10%     |
| Toshiba             | 9        | 19     | 7.5%    |
| Kingston            | 7        | 7      | 5.83%   |
| Transcend           | 6        | 9      | 5%      |
| SanDisk             | 4        | 5      | 3.33%   |
| OCZ                 | 3        | 3      | 2.5%    |
| Innodisk            | 3        | 4      | 2.5%    |
| Hoodisk             | 3        | 3      | 2.5%    |
| EMTEC               | 3        | 4      | 2.5%    |
| PNY                 | 2        | 5      | 1.67%   |
| Phison              | 2        | 2      | 1.67%   |
| NVMe                | 2        | 2      | 1.67%   |
| Micron Technology   | 2        | 2      | 1.67%   |
| Maxtor              | 2        | 2      | 1.67%   |
| Dogfish             | 2        | 2      | 1.67%   |
| Silicon Motion      | 1        | 2      | 0.83%   |
| Pccooler            | 1        | 1      | 0.83%   |
| KingSpec            | 1        | 2      | 0.83%   |
| Intel               | 1        | 2      | 0.83%   |
| Hitachi             | 1        | 1      | 0.83%   |
| HGST                | 1        | 1      | 0.83%   |
| China               | 1        | 3      | 0.83%   |
| BAITITON            | 1        | 1      | 0.83%   |
| A-DATA Technology   | 1        | 2      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| EMTEC X150 120GB                | 3        | 2.26%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 2.26%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2        | 1.5%    |
| Toshiba HDWG440 4TB             | 2        | 1.5%    |
| Toshiba DT01ACA050 500GB        | 2        | 1.5%    |
| Seagate ST320LT007-9ZV142 320GB | 2        | 1.5%    |
| Seagate ST1000DM003-1ER162 1TB  | 2        | 1.5%    |
| Samsung SSD 860 EVO 250GB       | 2        | 1.5%    |
| Samsung SSD 850 EVO 250GB       | 2        | 1.5%    |
| Samsung HM321HI 320GB           | 2        | 1.5%    |
| Phison SATA SSD 16GB            | 2        | 1.5%    |
| OCZ VERTEX3 120GB               | 2        | 1.5%    |
| Kingston SV300S37A120G 120GB    | 2        | 1.5%    |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2        | 1.5%    |
| Hoodisk SSD 256GB               | 2        | 1.5%    |
| Crucial CT500MX500SSD1 500GB    | 2        | 1.5%    |
| Crucial CT250MX500SSD1 250GB    | 2        | 1.5%    |
| Crucial CT120BX500SSD1 120GB    | 2        | 1.5%    |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.75%   |
| WDC WDS100T2B0B-00YS70 1TB      | 1        | 0.75%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.75%   |
| WDC WD6400AAKS-65A7B0 640GB     | 1        | 0.75%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1        | 0.75%   |
| WDC WD5000LPVT-80G33T2 500GB    | 1        | 0.75%   |
| WDC WD5000BPKX-00HPJT0 500GB    | 1        | 0.75%   |
| WDC WD5000BMVV-11A1CS0 500GB    | 1        | 0.75%   |
| WDC WD5000BEVT-00A03T0 500GB    | 1        | 0.75%   |
| WDC WD5000AAKS-00E4A0 500GB     | 1        | 0.75%   |
| WDC WD5000AAKS-00D2B0 500GB     | 1        | 0.75%   |
| WDC WD40NMZW-11GX6S1 4TB        | 1        | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 0.75%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 0.75%   |
| WDC WD3200AAKS-00L9A0 320GB     | 1        | 0.75%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1        | 0.75%   |
| WDC WD30EZRZ-00GXCB0 3TB        | 1        | 0.75%   |
| WDC WD2500BEVT-22A23T0 250GB    | 1        | 0.75%   |
| WDC WD2500AAJS-07M0A0 250GB     | 1        | 0.75%   |
| WDC WD20PURZ-85GU6Y0 2TB        | 1        | 0.75%   |
| WDC WD20EVDS-63T3B0 2TB         | 1        | 0.75%   |
| WDC WD2002FYPS-01U1B1 2TB       | 1        | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 41     | 37.5%   |
| Seagate             | 14       | 19     | 29.17%  |
| Toshiba             | 8        | 16     | 16.67%  |
| Samsung Electronics | 3        | 3      | 6.25%   |
| Maxtor              | 2        | 2      | 4.17%   |
| NVMe                | 1        | 1      | 2.08%   |
| Hitachi             | 1        | 1      | 2.08%   |
| HGST                | 1        | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 11       | 20     | 16.18%  |
| Samsung Electronics | 9        | 14     | 13.24%  |
| Kingston            | 7        | 7      | 10.29%  |
| Transcend           | 6        | 9      | 8.82%   |
| SanDisk             | 4        | 5      | 5.88%   |
| WDC                 | 3        | 3      | 4.41%   |
| OCZ                 | 3        | 3      | 4.41%   |
| Innodisk            | 3        | 4      | 4.41%   |
| Hoodisk             | 3        | 3      | 4.41%   |
| EMTEC               | 3        | 4      | 4.41%   |
| PNY                 | 2        | 5      | 2.94%   |
| Phison              | 2        | 2      | 2.94%   |
| Micron Technology   | 2        | 2      | 2.94%   |
| Dogfish             | 2        | 2      | 2.94%   |
| Toshiba             | 1        | 3      | 1.47%   |
| Pccooler            | 1        | 1      | 1.47%   |
| NVMe                | 1        | 1      | 1.47%   |
| KingSpec            | 1        | 2      | 1.47%   |
| Intel               | 1        | 2      | 1.47%   |
| China               | 1        | 3      | 1.47%   |
| BAITITON            | 1        | 1      | 1.47%   |
| A-DATA Technology   | 1        | 2      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 55       | 98     | 57.29%  |
| HDD  | 35       | 84     | 36.46%  |
| NVMe | 6        | 7      | 6.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 79       | 182    | 92.94%  |
| NVMe | 6        | 7      | 7.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 138    | 71.58%  |
| 0.51-1.0   | 13       | 19     | 13.68%  |
| 1.01-2.0   | 6        | 8      | 6.32%   |
| 3.01-4.0   | 5        | 10     | 5.26%   |
| 4.01-10.0  | 2        | 4      | 2.11%   |
| 2.01-3.0   | 1        | 3      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 29       | 33.33%  |
| 1-20           | 22       | 25.29%  |
| 251-500        | 12       | 13.79%  |
| 21-50          | 7        | 8.05%   |
| 501-1000       | 7        | 8.05%   |
| 51-100         | 5        | 5.75%   |
| More than 3000 | 3        | 3.45%   |
| 1001-2000      | 1        | 1.15%   |
| Unknown        | 1        | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 75       | 87.21%  |
| 21-50          | 4        | 4.65%   |
| 501-1000       | 2        | 2.33%   |
| 51-100         | 2        | 2.33%   |
| More than 3000 | 1        | 1.16%   |
| 1001-2000      | 1        | 1.16%   |
| Unknown        | 1        | 1.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2        | 2      | 11.11%  |
| Seagate ST320LT007-9ZV142 320GB   | 2        | 2      | 11.11%  |
| OCZ VERTEX3 120GB                 | 2        | 2      | 11.11%  |
| WDC WD5000AAKS-00E4A0 500GB       | 1        | 1      | 5.56%   |
| WDC WD20EVDS-63T3B0 2TB           | 1        | 1      | 5.56%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1        | 1      | 5.56%   |
| WDC WD1000DHTZ-04N21V1 1TB        | 1        | 2      | 5.56%   |
| Seagate ST500LM021-1KJ152 500GB   | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 4      | 5.56%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1        | 1      | 5.56%   |
| Seagate ST31500341AS 1.5TB        | 1        | 1      | 5.56%   |
| Samsung Electronics HM321HI 320GB | 1        | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB      | 1        | 1      | 5.56%   |
| HGST HTS541075A9E680 752GB        | 1        | 1      | 5.56%   |
| A-DATA Technology SX300 128GB     | 1        | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 33.33%  |
| Seagate             | 6        | 9      | 33.33%  |
| OCZ                 | 2        | 2      | 11.11%  |
| Samsung Electronics | 1        | 1      | 5.56%   |
| Kingston            | 1        | 1      | 5.56%   |
| HGST                | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 42.86%  |
| Seagate             | 6        | 9      | 42.86%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 18     | 75%     |
| SSD  | 4        | 4      | 25%     |

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
| Works    | 67       | 150    | 73.63%  |
| Malfunc  | 16       | 22     | 17.58%  |
| Detected | 8        | 17     | 8.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 61       | 59.22%  |
| AMD                              | 21       | 20.39%  |
| Samsung Electronics              | 4        | 3.88%   |
| Marvell Technology Group         | 3        | 2.91%   |
| VIA Technologies                 | 2        | 1.94%   |
| Broadcom / LSI                   | 2        | 1.94%   |
| ASMedia Technology               | 2        | 1.94%   |
| Silicon Motion                   | 1        | 0.97%   |
| Silicon Integrated Systems [SiS] | 1        | 0.97%   |
| SanDisk                          | 1        | 0.97%   |
| Micron/Crucial Technology        | 1        | 0.97%   |
| KIOXIA                           | 1        | 0.97%   |
| JMicron Technology               | 1        | 0.97%   |
| Integrated Technology Express    | 1        | 0.97%   |
| Adaptec                          | 1        | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 13       | 10.74%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6        | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6        | 4.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5        | 4.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 3.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4        | 3.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 3.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4        | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4        | 3.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3        | 2.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3        | 2.48%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3        | 2.48%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3        | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3        | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                           | 3        | 2.48%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2        | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2        | 1.65%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2        | 1.65%   |
| AMD FCH SATA Controller [IDE mode]                                               | 2        | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.83%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 1        | 0.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1        | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1        | 0.83%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1        | 0.83%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1        | 0.83%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1        | 0.83%   |
| KIOXIA NVMe SSD                                                                  | 1        | 0.83%   |
| JMicron JMB361 AHCI/IDE                                                          | 1        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                | 1        | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 0.83%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1        | 0.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1        | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1        | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 66       | 66.67%  |
| IDE  | 19       | 19.19%  |
| NVMe | 8        | 8.08%   |
| RAID | 3        | 3.03%   |
| SCSI | 3        | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 62       | 72.94%  |
| AMD     | 21       | 24.71%  |
| Arm     | 1        | 1.18%   |
| Unknown | 1        | 1.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD GX-412TC SOC                            | 5        | 5.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3        | 3.53%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 3        | 3.53%   |
| AMD Phenom II X4 965 Processor              | 3        | 3.53%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 2        | 2.35%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 2        | 2.35%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 2        | 2.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2        | 2.35%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 2        | 2.35%   |
| Intel Celeron CPU J3355 @ 2.00GHz           | 2        | 2.35%   |
| Intel Celeron CPU J3160 @ 1.60GHz           | 2        | 2.35%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 2        | 2.35%   |
| Intel Xeon CPU X3470 @ 2.93GHz              | 1        | 1.18%   |
| Intel Xeon CPU W3520 @ 2.67GHz              | 1        | 1.18%   |
| Intel Xeon CPU E5440 @ 2.83GHz              | 1        | 1.18%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 1.18%   |
| Intel Xeon CPU E31245 @ 3.30GHz             | 1        | 1.18%   |
| Intel Xeon CPU E31245 @ 3.30GH              | 1        | 1.18%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 1        | 1.18%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1        | 1.18%   |
| Intel Pentium Dual-Core CPU E6600           | 1        | 1.18%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 1.18%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1        | 1.18%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1        | 1.18%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 1.18%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1        | 1.18%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 1.18%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.18%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 1.18%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1        | 1.18%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 1        | 1.18%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 1        | 1.18%   |
| Intel Core i5-4210Y CPU @ 1.50GHz           | 1        | 1.18%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1        | 1.18%   |
| Intel Core i5 CPU                           | 1        | 1.18%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.18%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 1        | 1.18%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1        | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 14       | 16.47%  |
| Intel Core i3           | 9        | 10.59%  |
| Intel Xeon              | 7        | 8.24%   |
| Intel Core i7           | 7        | 8.24%   |
| Intel Core i5           | 7        | 8.24%   |
| AMD GX                  | 7        | 8.24%   |
| Intel Atom              | 5        | 5.88%   |
| Intel Pentium Dual      | 3        | 3.53%   |
| Intel Pentium           | 3        | 3.53%   |
| AMD Ryzen 5             | 3        | 3.53%   |
| AMD Phenom II X4        | 3        | 3.53%   |
| Other                   | 2        | 2.35%   |
| Intel Pentium Dual-Core | 2        | 2.35%   |
| Intel Core 2 Duo        | 2        | 2.35%   |
| AMD Ryzen 9             | 2        | 2.35%   |
| AMD Ryzen 7             | 2        | 2.35%   |
| Intel Pentium Silver    | 1        | 1.18%   |
| Intel Core 2 Quad       | 1        | 1.18%   |
| Intel Core 2 Extreme    | 1        | 1.18%   |
| AMD Ryzen 3             | 1        | 1.18%   |
| AMD FX                  | 1        | 1.18%   |
| AMD E2                  | 1        | 1.18%   |
| AMD Athlon II X4        | 1        | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 39       | 45.88%  |
| 2       | 28       | 32.94%  |
| Unknown | 7        | 8.24%   |
| 16      | 3        | 3.53%   |
| 12      | 3        | 3.53%   |
| 8       | 2        | 2.35%   |
| 32      | 1        | 1.18%   |
| 6       | 1        | 1.18%   |
| 1       | 1        | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 81       | 95.29%  |
| Unknown | 3        | 3.53%   |
| 2       | 1        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 48       | 56.47%  |
| 2       | 30       | 35.29%  |
| Unknown | 7        | 8.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| SandyBridge   | 7        | 8.24%   |
| Haswell       | 7        | 8.24%   |
| Penryn        | 6        | 7.06%   |
| KabyLake      | 6        | 7.06%   |
| Silvermont    | 5        | 5.88%   |
| Puma          | 5        | 5.88%   |
| Goldmont plus | 5        | 5.88%   |
| Bonnell       | 5        | 5.88%   |
| K10           | 4        | 4.71%   |
| IvyBridge     | 4        | 4.71%   |
| Goldmont      | 4        | 4.71%   |
| Core          | 4        | 4.71%   |
| Zen 3         | 3        | 3.53%   |
| Nehalem       | 3        | 3.53%   |
| CometLake     | 3        | 3.53%   |
| Zen+          | 2        | 2.35%   |
| Zen 2         | 2        | 2.35%   |
| Jaguar        | 2        | 2.35%   |
| Unknown       | 2        | 2.35%   |
| Zen           | 1        | 1.18%   |
| Westmere      | 1        | 1.18%   |
| Skylake       | 1        | 1.18%   |
| Piledriver    | 1        | 1.18%   |
| K10 Llano     | 1        | 1.18%   |
| Broadwell     | 1        | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 44       | 55.7%   |
| AMD                              | 19       | 24.05%  |
| Nvidia                           | 14       | 17.72%  |
| Silicon Integrated Systems [SiS] | 1        | 1.27%   |
| Matrox Electronics Systems       | 1        | 1.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 6.33%   |
| Intel HD Graphics 620                                                                    | 4        | 5.06%   |
| Intel HD Graphics 500                                                                    | 4        | 5.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4        | 5.06%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4        | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4        | 5.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3        | 3.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 2.53%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 2.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 2.53%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2        | 2.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 2.53%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2        | 2.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.53%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2        | 2.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.53%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2        | 2.53%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 1.27%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1        | 1.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.27%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1        | 1.27%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.27%   |
| Nvidia GK107 [NVS 510]                                                                   | 1        | 1.27%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1        | 1.27%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1        | 1.27%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1        | 1.27%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1        | 1.27%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1        | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.27%   |
| Intel HD Graphics 630                                                                    | 1        | 1.27%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.27%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1        | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.27%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 1.27%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.27%   |
| AMD SuperSumo [Radeon HD 6370D]                                                          | 1        | 1.27%   |
| AMD RV730 XT [Radeon HD 4670]                                                            | 1        | 1.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 41       | 47.67%  |
| 1 x AMD        | 19       | 22.09%  |
| 1 x Nvidia     | 13       | 15.12%  |
| Other          | 8        | 9.3%    |
| 2 x Intel      | 2        | 2.33%   |
| 1 x SiS        | 1        | 1.16%   |
| 1 x Matrox     | 1        | 1.16%   |
| Intel + Nvidia | 1        | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 66       | 75.86%  |
| Proprietary | 12       | 13.79%  |
| Unknown     | 9        | 10.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 77.01%  |
| 1.01-2.0   | 6        | 6.9%    |
| 3.01-4.0   | 5        | 5.75%   |
| 0.51-1.0   | 4        | 4.6%    |
| 0.01-0.5   | 3        | 3.45%   |
| 7.01-8.0   | 1        | 1.15%   |
| 5.01-6.0   | 1        | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 9        | 23.68%  |
| Samsung Electronics  | 7        | 18.42%  |
| Acer                 | 4        | 10.53%  |
| Hewlett-Packard      | 3        | 7.89%   |
| Goldstar             | 3        | 7.89%   |
| Dell                 | 3        | 7.89%   |
| Sony                 | 1        | 2.63%   |
| Packard Bell         | 1        | 2.63%   |
| Orion                | 1        | 2.63%   |
| LG Electronics       | 1        | 2.63%   |
| Iiyama               | 1        | 2.63%   |
| Eizo                 | 1        | 2.63%   |
| ASUSTek Computer     | 1        | 2.63%   |
| Apple                | 1        | 2.63%   |
| Ancor Communications | 1        | 2.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 7        | 18.42%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 2        | 5.26%   |
| Sony TV SNY5D01 1360x768                                              | 1        | 2.63%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1        | 2.63%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1        | 2.63%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1        | 2.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1        | 2.63%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1        | 2.63%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1        | 2.63%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1        | 2.63%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1        | 2.63%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1        | 2.63%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch                | 1        | 2.63%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1        | 2.63%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch             | 1        | 2.63%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch            | 1        | 2.63%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1        | 2.63%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 1        | 2.63%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch           | 1        | 2.63%   |
| Eizo LCD Monitor S1901 1280x1024                                      | 1        | 2.63%   |
| Dell U4021QW DEL4206 2560x1080 930x390mm 39.7-inch                    | 1        | 2.63%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                     | 1        | 2.63%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                     | 1        | 2.63%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 1        | 2.63%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                 | 1        | 2.63%   |
| Ancor Communications ASUS MX239 ACI23C2 1920x1080 530x310mm 24.2-inch | 1        | 2.63%   |
| Acer X203H ACR0097 1600x900 440x250mm 19.9-inch                       | 1        | 2.63%   |
| Acer RT240Y ACR0539 1920x1080 530x300mm 24.0-inch                     | 1        | 2.63%   |
| Acer R271 ACR0496 1920x1080 600x340mm 27.2-inch                       | 1        | 2.63%   |
| Acer AL1917 ACRAD63 1280x1024 380x300mm 19.1-inch                     | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 23       | 65.71%  |
| 1280x1024 (SXGA)  | 3        | 8.57%   |
| 2560x1080         | 2        | 5.71%   |
| 1920x1200 (WUXGA) | 2        | 5.71%   |
| 3840x2160 (4K)    | 1        | 2.86%   |
| 1600x900 (HD+)    | 1        | 2.86%   |
| 1440x900 (WXGA+)  | 1        | 2.86%   |
| 1360x768          | 1        | 2.86%   |
| 1024x768 (XGA)    | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 9        | 23.68%  |
| Unknown | 7        | 18.42%  |
| 24      | 5        | 13.16%  |
| 19      | 4        | 10.53%  |
| 27      | 3        | 7.89%   |
| 23      | 3        | 7.89%   |
| 31      | 2        | 5.26%   |
| 39      | 1        | 2.63%   |
| 34      | 1        | 2.63%   |
| 28      | 1        | 2.63%   |
| 22      | 1        | 2.63%   |
| 14      | 1        | 2.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 11       | 30.56%  |
| 501-600     | 9        | 25%     |
| Unknown     | 7        | 19.44%  |
| 601-700     | 4        | 11.11%  |
| 351-400     | 2        | 5.56%   |
| 701-800     | 1        | 2.78%   |
| 201-300     | 1        | 2.78%   |
| 901-1000    | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 70.59%  |
| 16/10   | 3        | 8.82%   |
| 5/4     | 2        | 5.88%   |
| 21/9    | 2        | 5.88%   |
| Unknown | 2        | 5.88%   |
| 4/3     | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 38.89%  |
| Unknown        | 7        | 19.44%  |
| 351-500        | 4        | 11.11%  |
| 151-200        | 4        | 11.11%  |
| 301-350        | 3        | 8.33%   |
| 251-300        | 2        | 5.56%   |
| 101-110        | 1        | 2.78%   |
| 501-1000       | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 19       | 52.78%  |
| 101-120 | 9        | 25%     |
| Unknown | 7        | 19.44%  |
| 121-160 | 1        | 2.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 52       | 59.77%  |
| 1     | 33       | 37.93%  |
| 2     | 2        | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 50       | 45.05%  |
| Realtek Semiconductor | 41       | 36.94%  |
| Broadcom              | 6        | 5.41%   |
| Qualcomm Atheros      | 5        | 4.5%    |
| Ralink                | 2        | 1.8%    |
| Sitecom Europe        | 1        | 0.9%    |
| Ralink Technology     | 1        | 0.9%    |
| MediaTek              | 1        | 0.9%    |
| IMC Networks          | 1        | 0.9%    |
| Google                | 1        | 0.9%    |
| Digital Equipment     | 1        | 0.9%    |
| Davicom Semiconductor | 1        | 0.9%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 36       | 28.13%  |
| Intel I211 Gigabit Network Connection                                                 | 18       | 14.06%  |
| Intel I210 Gigabit Network Connection                                                 | 5        | 3.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4        | 3.13%   |
| Intel 82574L Gigabit Network Connection                                               | 4        | 3.13%   |
| Intel 82579V Gigabit Network Connection                                               | 3        | 2.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2        | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 1.56%   |
| Intel I350 Gigabit Network Connection                                                 | 2        | 1.56%   |
| Intel Ethernet Controller I225-V                                                      | 2        | 1.56%   |
| Intel Ethernet Connection I217-LM                                                     | 2        | 1.56%   |
| Intel 82575EB Gigabit Network Connection                                              | 2        | 1.56%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 0.78%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1        | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 0.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 0.78%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 0.78%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 0.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 0.78%   |
| Intel Wireless 3165                                                                   | 1        | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1        | 0.78%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                         | 1        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                                  | 1        | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                                 | 1        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 0.78%   |
| Intel DH8900CC Null Device                                                            | 1        | 0.78%   |
| Intel 82583V Gigabit Network Connection                                               | 1        | 0.78%   |
| Intel 82578DM Gigabit Network Connection                                              | 1        | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 5        | 26.32%  |
| Qualcomm Atheros      | 5        | 26.32%  |
| Intel                 | 3        | 15.79%  |
| Ralink                | 2        | 10.53%  |
| Sitecom Europe        | 1        | 5.26%   |
| Ralink Technology     | 1        | 5.26%   |
| MediaTek              | 1        | 5.26%   |
| IMC Networks          | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2        | 9.09%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1        | 4.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 4.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 4.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 4.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                                       | 1        | 4.55%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1        | 4.55%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1        | 4.55%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 4.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 4.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1        | 4.55%   |
| Intel Wireless 3165                                                                   | 1        | 4.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 4.55%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 49       | 51.58%  |
| Realtek Semiconductor | 38       | 40%     |
| Broadcom              | 6        | 6.32%   |
| Digital Equipment     | 1        | 1.05%   |
| Davicom Semiconductor | 1        | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 36       | 34.62%  |
| Intel I211 Gigabit Network Connection                                         | 18       | 17.31%  |
| Intel I210 Gigabit Network Connection                                         | 5        | 4.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 4        | 3.85%   |
| Intel 82574L Gigabit Network Connection                                       | 4        | 3.85%   |
| Intel 82579V Gigabit Network Connection                                       | 3        | 2.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2        | 1.92%   |
| Intel I350 Gigabit Network Connection                                         | 2        | 1.92%   |
| Intel Ethernet Controller I225-V                                              | 2        | 1.92%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 1.92%   |
| Intel 82575EB Gigabit Network Connection                                      | 2        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.96%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                          | 1        | 0.96%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1        | 0.96%   |
| Intel 82583V Gigabit Network Connection                                       | 1        | 0.96%   |
| Intel 82578DM Gigabit Network Connection                                      | 1        | 0.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.96%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1        | 0.96%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1        | 0.96%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1        | 0.96%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1        | 0.96%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1        | 0.96%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1        | 0.96%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1        | 0.96%   |
| Digital Equipment DECchip 21142/43                                            | 1        | 0.96%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1        | 0.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1        | 0.96%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 0.96%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 0.96%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1        | 0.96%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1        | 0.96%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1        | 0.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 80.58%  |
| WiFi     | 18       | 17.48%  |
| Unknown  | 2        | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 83       | 93.26%  |
| WiFi     | 6        | 6.74%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 34.88%  |
| 2     | 20       | 23.26%  |
| 3     | 12       | 13.95%  |
| 4     | 10       | 11.63%  |
| 5     | 5        | 5.81%   |
| 7     | 3        | 3.49%   |
| 6     | 2        | 2.33%   |
| 0     | 2        | 2.33%   |
| 9     | 1        | 1.16%   |
| 8     | 1        | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 85       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Cambridge Silicon Radio    | 4        | 40%     |
| Realtek Semiconductor      | 2        | 20%     |
| Integrated System Solution | 2        | 20%     |
| MediaTek                   | 1        | 10%     |
| Intel                      | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4        | 40%     |
| Integrated System Solution Bluetooth Device         | 2        | 20%     |
| Realtek  Bluetooth Adapter                          | 1        | 10%     |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 10%     |
| MediaTek Wireless_Device                            | 1        | 10%     |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 53       | 56.38%  |
| AMD                              | 22       | 23.4%   |
| Nvidia                           | 13       | 13.83%  |
| Logitech                         | 2        | 2.13%   |
| C-Media Electronics              | 2        | 2.13%   |
| Silicon Integrated Systems [SiS] | 1        | 1.06%   |
| Bose                             | 1        | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6        | 5.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5        | 4.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5        | 4.46%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5        | 4.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 3.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4        | 3.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4        | 3.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3        | 2.68%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 2.68%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3        | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 2.68%   |
| AMD FCH Azalia Controller                                                                         | 3        | 2.68%   |
| Nvidia High Definition Audio Controller                                                           | 2        | 1.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2        | 1.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2        | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 1.79%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.79%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2        | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 1.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 1.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2        | 1.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.89%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1        | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 0.89%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1        | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1        | 0.89%   |
| Logitech Headset H340                                                                             | 1        | 0.89%   |
| Logitech HD Webcam C510                                                                           | 1        | 0.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 17.86%  |
| Kingston            | 14       | 16.67%  |
| Samsung Electronics | 10       | 11.9%   |
| SK hynix            | 8        | 9.52%   |
| Crucial             | 6        | 7.14%   |
| Ramaxel Technology  | 4        | 4.76%   |
| Corsair             | 4        | 4.76%   |
| Nanya Technology    | 3        | 3.57%   |
| Elpida              | 3        | 3.57%   |
| Unknown (ABCD)      | 2        | 2.38%   |
| Transcend           | 2        | 2.38%   |
| Micron Technology   | 2        | 2.38%   |
| Unknown             | 2        | 2.38%   |
| Unknown (AB)        | 1        | 1.19%   |
| SK_Hynix            | 1        | 1.19%   |
| KomputerBay         | 1        | 1.19%   |
| Intersil            | 1        | 1.19%   |
| G.Skill             | 1        | 1.19%   |
| 2C0C0843D7349CA2    | 1        | 1.19%   |
| 2C0C0843D7349C9D    | 1        | 1.19%   |
| 2C080815D82F5C7B    | 1        | 1.19%   |
| 2C0108214C359D20    | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2        | 2.13%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 2        | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 2        | 2.13%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2        | 2.13%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s           | 2        | 2.13%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 2        | 2.13%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s           | 2        | 2.13%   |
| Unknown                                                           | 2        | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                         | 1        | 1.06%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.06%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                      | 1        | 1.06%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1        | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1        | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 1        | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1        | 1.06%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                         | 1        | 1.06%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1        | 1.06%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1        | 1.06%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 1        | 1.06%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s               | 1        | 1.06%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1        | 1.06%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s              | 1        | 1.06%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1        | 1.06%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1        | 1.06%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1        | 1.06%   |
| SK hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s               | 1        | 1.06%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 1        | 1.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.06%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s              | 1        | 1.06%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                   | 1        | 1.06%   |
| Samsung RAM M471B5773DH0-CK0 2GB DIMM DDR3 1333MT/s               | 1        | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s             | 1        | 1.06%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.06%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1        | 1.06%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 1        | 1.06%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1        | 1.06%   |
| Samsung RAM M395T5160CZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1        | 1.06%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s               | 1        | 1.06%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1        | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 37       | 51.39%  |
| DDR4    | 17       | 23.61%  |
| DDR2    | 11       | 15.28%  |
| Unknown | 5        | 6.94%   |
| LPDDR4  | 2        | 2.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 46       | 65.71%  |
| SODIMM  | 23       | 32.86%  |
| FB-DIMM | 1        | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 28       | 36.84%  |
| 2048  | 20       | 26.32%  |
| 8192  | 18       | 23.68%  |
| 16384 | 6        | 7.89%   |
| 1024  | 3        | 3.95%   |
| 32768 | 1        | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1333  | 18       | 23.08%  |
| 1600  | 17       | 21.79%  |
| 2400  | 9        | 11.54%  |
| 800   | 7        | 8.97%   |
| 2667  | 6        | 7.69%   |
| 1067  | 5        | 6.41%   |
| 667   | 4        | 5.13%   |
| 2133  | 3        | 3.85%   |
| 3200  | 2        | 2.56%   |
| 1066  | 2        | 2.56%   |
| 2933  | 1        | 1.28%   |
| 2666  | 1        | 1.28%   |
| 1866  | 1        | 1.28%   |
| 1334  | 1        | 1.28%   |
| 1200  | 1        | 1.28%   |

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
| 1     | 47       | 54.65%  |
| 0     | 34       | 39.53%  |
| 2     | 3        | 3.49%   |
| 3     | 2        | 2.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 39       | 69.64%  |
| Firewire controller      | 8        | 14.29%  |
| Net/wireless             | 6        | 10.71%  |
| Card reader              | 2        | 3.57%   |
| Network                  | 1        | 1.79%   |

