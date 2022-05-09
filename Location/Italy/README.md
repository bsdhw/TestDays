BSD in Italy - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 200

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Dell          | 0TY179 A05                  | Server      | [124e42e2c1](https://bsd-hardware.info/?probe=124e42e2c1) | Apr 21, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9a50fe43a7](https://bsd-hardware.info/?probe=9a50fe43a7) | Apr 21, 2022 |
| Pegatron      | Benicia                     | Desktop     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Dell          | 07978V A08                  | Server      | [f315c33e95](https://bsd-hardware.info/?probe=f315c33e95) | Apr 06, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | Desktop     | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9f760529c1](https://bsd-hardware.info/?probe=9f760529c1) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [bb895c5df3](https://bsd-hardware.info/?probe=bb895c5df3) | Mar 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| HP            | 3397                        | Desktop     | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [6696106165](https://bsd-hardware.info/?probe=6696106165) | Feb 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [946c9acc2e](https://bsd-hardware.info/?probe=946c9acc2e) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| Dell          | 0TK7TF A00                  | Desktop     | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| PC Engines    | APU2                        | Desktop     | [54ada090c6](https://bsd-hardware.info/?probe=54ada090c6) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | Notebook    | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [8812a8e8c8](https://bsd-hardware.info/?probe=8812a8e8c8) | Dec 04, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Acer          | Veriton X2610G              | Desktop     | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [e0ad80acf9](https://bsd-hardware.info/?probe=e0ad80acf9) | Sep 20, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [f1a2baeecb](https://bsd-hardware.info/?probe=f1a2baeecb) | Sep 14, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [3607c373aa](https://bsd-hardware.info/?probe=3607c373aa) | Sep 11, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [73912d5852](https://bsd-hardware.info/?probe=73912d5852) | Sep 09, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | Desktop     | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | Desktop     | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [acfe0caa83](https://bsd-hardware.info/?probe=acfe0caa83) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [7fe4b5ff70](https://bsd-hardware.info/?probe=7fe4b5ff70) | Jul 12, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [dbacaa5c65](https://bsd-hardware.info/?probe=dbacaa5c65) | Jul 08, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | Desktop     | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [7cf77c6f1f](https://bsd-hardware.info/?probe=7cf77c6f1f) | Jun 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | Desktop     | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [de8a18ca09](https://bsd-hardware.info/?probe=de8a18ca09) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [139e702b9a](https://bsd-hardware.info/?probe=139e702b9a) | Mar 27, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [78a7c7b8cb](https://bsd-hardware.info/?probe=78a7c7b8cb) | Mar 23, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a7a25be087](https://bsd-hardware.info/?probe=a7a25be087) | Mar 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | Desktop     | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 00NH4P A07                  | Server      | [7cff5a5c58](https://bsd-hardware.info/?probe=7cff5a5c58) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [55045aa9e5](https://bsd-hardware.info/?probe=55045aa9e5) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| ASUSTek       | G1S                         | Notebook    | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [c3dc05bbac](https://bsd-hardware.info/?probe=c3dc05bbac) | Feb 26, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [7ab47e0db7](https://bsd-hardware.info/?probe=7ab47e0db7) | Feb 25, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [5ecd568ce9](https://bsd-hardware.info/?probe=5ecd568ce9) | Feb 21, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [138dbdcece](https://bsd-hardware.info/?probe=138dbdcece) | Feb 21, 2021 |
| Dell          | 00NH4P A07                  | Server      | [fff0533829](https://bsd-hardware.info/?probe=fff0533829) | Feb 20, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d6bc2b2c1d](https://bsd-hardware.info/?probe=d6bc2b2c1d) | Feb 08, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [01a2dd5a52](https://bsd-hardware.info/?probe=01a2dd5a52) | Feb 02, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [869d894f4f](https://bsd-hardware.info/?probe=869d894f4f) | Jan 30, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [2aa7735e59](https://bsd-hardware.info/?probe=2aa7735e59) | Jan 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3e37c56f14](https://bsd-hardware.info/?probe=3e37c56f14) | Jan 23, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | Desktop     | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| PC Engines    | apu2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [55c762d22e](https://bsd-hardware.info/?probe=55c762d22e) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [afbbc44ac5](https://bsd-hardware.info/?probe=afbbc44ac5) | Nov 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | Notebook    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | Desktop     | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [6b854263e7](https://bsd-hardware.info/?probe=6b854263e7) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.4.0    | 12        | 8.7%    |
| helloSystem 0.7.0    | 9         | 6.52%   |
| helloSystem 0.5.0    | 9         | 6.52%   |
| helloSystem 0.6.0    | 6         | 4.35%   |
| OPNsense 22.1.6      | 5         | 3.62%   |
| helloSystem 0.3.0    | 5         | 3.62%   |
| OPNsense 22.1        | 4         | 2.9%    |
| OPNsense 21.1        | 4         | 2.9%    |
| OPNsense 21.7.7      | 3         | 2.17%   |
| OPNsense 21.7.3      | 3         | 2.17%   |
| OPNsense 21.1.8      | 3         | 2.17%   |
| OPNsense 21.1.3      | 3         | 2.17%   |
| OPNsense 21.1.2      | 3         | 2.17%   |
| OPNsense 20.7.8      | 3         | 2.17%   |
| OpenBSD 6.8          | 3         | 2.17%   |
| NomadBSD 1.4         | 3         | 2.17%   |
| FreeBSD 13.0-p7      | 3         | 2.17%   |
| FreeBSD 12.2-p2      | 3         | 2.17%   |
| OPNsense 22.1.4      | 2         | 1.45%   |
| OPNsense 21.1.1      | 2         | 1.45%   |
| NomadBSD 1.3.2       | 2         | 1.45%   |
| GhostBSD 21.08.27    | 2         | 1.45%   |
| GhostBSD 20.04.02    | 2         | 1.45%   |
| FreeBSD 13.0-p4      | 2         | 1.45%   |
| FreeBSD 13.0-CURRENT | 2         | 1.45%   |
| FreeBSD 12.3-p1      | 2         | 1.45%   |
| FreeBSD 12.2-p6      | 2         | 1.45%   |
| FreeBSD 12.2-p4      | 2         | 1.45%   |
| FreeBSD 12.1-p10     | 2         | 1.45%   |
| OPNsense 22.1.3      | 1         | 0.72%   |
| OPNsense 22.1.2      | 1         | 0.72%   |
| OPNsense 22.1.1      | 1         | 0.72%   |
| OPNsense 21.7.8      | 1         | 0.72%   |
| OPNsense 21.7.6      | 1         | 0.72%   |
| OPNsense 21.7.4      | 1         | 0.72%   |
| OPNsense 21.7.1      | 1         | 0.72%   |
| OPNsense 21.7        | 1         | 0.72%   |
| OPNsense 21.1.7      | 1         | 0.72%   |
| OPNsense 21.1.6      | 1         | 0.72%   |
| OPNsense 21.1.5      | 1         | 0.72%   |
| OpenBSD 7.1          | 1         | 0.72%   |
| OpenBSD 6.7          | 1         | 0.72%   |
| NomadBSD 5806f915    | 1         | 0.72%   |
| NomadBSD 1.3.1       | 1         | 0.72%   |
| NetBSD 9.99.93       | 1         | 0.72%   |
| NetBSD 9.99.77       | 1         | 0.72%   |
| NetBSD 9.2_STABLE    | 1         | 0.72%   |
| NetBSD 9.2           | 1         | 0.72%   |
| NetBSD 9.1_STABLE    | 1         | 0.72%   |
| NetBSD 9.1           | 1         | 0.72%   |
| NetBSD 9.0           | 1         | 0.72%   |
| FreeBSD 14.0-CURRENT | 1         | 0.72%   |
| FreeBSD 13.1-RC5     | 1         | 0.72%   |
| FreeBSD 13.1-BETA2   | 1         | 0.72%   |
| FreeBSD 13.0-p5      | 1         | 0.72%   |
| FreeBSD 13.0-p3      | 1         | 0.72%   |
| FreeBSD 13.0         | 1         | 0.72%   |
| FreeBSD 12.2-STABLE  | 1         | 0.72%   |
| FreeBSD 12.1-p6      | 1         | 0.72%   |
| FreeBSD 12.1-p5      | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 37        | 31.9%   |
| helloSystem | 34        | 29.31%  |
| FreeBSD     | 23        | 19.83%  |
| NomadBSD    | 7         | 6.03%   |
| NetBSD      | 6         | 5.17%   |
| OpenBSD     | 5         | 4.31%   |
| GhostBSD    | 4         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 110       | 94.83%  |
| i386   | 3         | 2.59%   |
| evbarm | 3         | 2.59%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 46        | 39.32%  |
| helloDesktop  | 34        | 29.06%  |
| Openbox       | 7         | 5.98%   |
| XFCE          | 5         | 4.27%   |
| KDE5          | 4         | 3.42%   |
| fvwm          | 4         | 3.42%   |
| MATE          | 3         | 2.56%   |
| i3            | 3         | 2.56%   |
| CTWM          | 3         | 2.56%   |
| Cinnamon      | 3         | 2.56%   |
| TWM           | 2         | 1.71%   |
| xfwm          | 1         | 0.85%   |
| Fluxbox       | 1         | 0.85%   |
| Enlightenment | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 72        | 62.07%  |
| Console | 44        | 37.93%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 62        | 53.45%  |
| SLiM    | 45        | 38.79%  |
| LightDM | 6         | 5.17%   |
| XDM     | 2         | 1.72%   |
| SDDM    | 1         | 0.86%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 49        | 41.53%  |
| en_US            | 44        | 37.29%  |
| it_IT            | 13        | 11.02%  |
| C                | 7         | 5.93%   |
| it_IT.ISO8859-15 | 2         | 1.69%   |
| ru_RU            | 1         | 0.85%   |
| it_IT.ISO8859-1  | 1         | 0.85%   |
| en_GB            | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 90        | 76.27%  |
| BIOS | 28        | 23.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 57        | 48.31%  |
| Zfs    | 51        | 43.22%  |
| Ffs    | 5         | 4.24%   |
| Cd9660 | 5         | 4.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 100       | 85.47%  |
| MBR     | 14        | 11.97%  |
| Unknown | 3         | 2.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 19        | 16.38%  |
| Lenovo                     | 13        | 11.21%  |
| Intel                      | 9         | 7.76%   |
| Dell                       | 8         | 6.9%    |
| Hewlett-Packard            | 7         | 6.03%   |
| Unknown                    | 7         | 6.03%   |
| MSI                        | 5         | 4.31%   |
| Acer                       | 5         | 4.31%   |
| PC Engines                 | 4         | 3.45%   |
| Gigabyte Technology        | 4         | 3.45%   |
| Apple                      | 4         | 3.45%   |
| BESSTAR Tech               | 3         | 2.59%   |
| ASRock                     | 3         | 2.59%   |
| ZOTAC                      | 2         | 1.72%   |
| Toshiba                    | 2         | 1.72%   |
| Pegatron                   | 2         | 1.72%   |
| Fujitsu                    | 2         | 1.72%   |
| AMI                        | 2         | 1.72%   |
| TUXEDO                     | 1         | 0.86%   |
| T-bao                      | 1         | 0.86%   |
| Supermicro                 | 1         | 0.86%   |
| Sun Microsystems           | 1         | 0.86%   |
| ShenZhen MinWin Technology | 1         | 0.86%   |
| Samsung Electronics        | 1         | 0.86%   |
| Raspberry Pi Foundation    | 1         | 0.86%   |
| Packard Bell               | 1         | 0.86%   |
| MW                         | 1         | 0.86%   |
| IBM                        | 1         | 0.86%   |
| HARDKERNEL                 | 1         | 0.86%   |
| Foxconn                    | 1         | 0.86%   |
| eMachines                  | 1         | 0.86%   |
| Deciso                     | 1         | 0.86%   |
| AZW                        | 1         | 0.86%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 7         | 6.03%   |
| PC Engines APU2                          | 3         | 2.59%   |
| Intel Q3XXG4-P V1.0                      | 3         | 2.59%   |
| BESSTAR Tech N40                         | 3         | 2.59%   |
| MSI MS-7B86                              | 2         | 1.72%   |
| HP Laptop 15-da0xxx                      | 2         | 1.72%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 1.72%   |
| ASUS M4A88TD-V EVO/USB3                  | 2         | 1.72%   |
| ASUS IP4BL-ME                            | 2         | 1.72%   |
| Apple MacBook4,1                         | 2         | 1.72%   |
| AMI Aptio CRB                            | 2         | 1.72%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO         | 1         | 0.86%   |
| ZOTAC ZBOX-CI323NANO                     | 1         | 0.86%   |
| TUXEDO N14xWU                            | 1         | 0.86%   |
| Toshiba Satellite C855-1U4               | 1         | 0.86%   |
| Toshiba PORTEGE M780                     | 1         | 0.86%   |
| T-bao MINI PC                            | 1         | 0.86%   |
| Supermicro X8STi                         | 1         | 0.86%   |
| Sun Microsystems Ultra 24                | 1         | 0.86%   |
| ShenZhen MinWin MW-NANO-APL-4L           | 1         | 0.86%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.86%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.86%   |
| Pegatron Pro 3405 Series                 | 1         | 0.86%   |
| Pegatron KX629AA-ABZ a6561.it            | 1         | 0.86%   |
| PC Engines APU3                          | 1         | 0.86%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 0.86%   |
| MW GMLK-2_5G4L                           | 1         | 0.86%   |
| MSI NR074AA-ABZ CQ5125IT                 | 1         | 0.86%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159)  | 1         | 0.86%   |
| MSI GF65 Thin 10SER                      | 1         | 0.86%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 0.86%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 0.86%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 0.86%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 0.86%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 0.86%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 0.86%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 0.86%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 0.86%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 0.86%   |
| Lenovo ThinkCentre M83 10AHS35Q00        | 1         | 0.86%   |
| Lenovo G505 20240                        | 1         | 0.86%   |
| Lenovo G50-45 80E3                       | 1         | 0.86%   |
| Lenovo B590 62743PG                      | 1         | 0.86%   |
| Intel NUC6i5SYB H81131-503               | 1         | 0.86%   |
| Intel NUC5i5RYB H40999-502               | 1         | 0.86%   |
| Intel NUC10i7FNK                         | 1         | 0.86%   |
| Intel MAHOBAY                            | 1         | 0.86%   |
| Intel D945GCLF2                          | 1         | 0.86%   |
| Intel D2500CC AAG81477-401               | 1         | 0.86%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 0.86%   |
| HP Z440 Workstation                      | 1         | 0.86%   |
| HP ProBook 470 G4                        | 1         | 0.86%   |
| HP Mini 210-1000                         | 1         | 0.86%   |
| HP EliteBook 6930p                       | 1         | 0.86%   |
| HP Compaq Elite 8300 SFF                 | 1         | 0.86%   |
| HARDKERNEL ODROID-H2                     | 1         | 0.86%   |
| Gigabyte X570 AORUS PRO                  | 1         | 0.86%   |
| Gigabyte X570 AORUS ELITE                | 1         | 0.86%   |
| Gigabyte P55A-UD3                        | 1         | 0.86%   |
| Gigabyte H270M-DS3H                      | 1         | 0.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 9         | 7.76%   |
| Unknown                        | 7         | 6.03%   |
| PC Engines APU2                | 3         | 2.59%   |
| Intel Q3XXG4-P                 | 3         | 2.59%   |
| Dell PowerEdge                 | 3         | 2.59%   |
| BESSTAR Tech N40               | 3         | 2.59%   |
| ASUS VivoBook                  | 3         | 2.59%   |
| MSI MS-7B86                    | 2         | 1.72%   |
| HP Laptop                      | 2         | 1.72%   |
| Gigabyte X570                  | 2         | 1.72%   |
| Fujitsu ESPRIMO                | 2         | 1.72%   |
| Dell Precision                 | 2         | 1.72%   |
| ASUS PRIME                     | 2         | 1.72%   |
| ASUS M4A88TD-V                 | 2         | 1.72%   |
| ASUS IP4BL-ME                  | 2         | 1.72%   |
| Apple MacBook4                 | 2         | 1.72%   |
| AMI Aptio                      | 2         | 1.72%   |
| Acer Aspire                    | 2         | 1.72%   |
| ZOTAC ZBOX-MI640               | 1         | 0.86%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.86%   |
| TUXEDO N14xWU                  | 1         | 0.86%   |
| Toshiba Satellite              | 1         | 0.86%   |
| Toshiba PORTEGE                | 1         | 0.86%   |
| T-bao MINI                     | 1         | 0.86%   |
| Supermicro X8STi               | 1         | 0.86%   |
| Sun Microsystems Ultra         | 1         | 0.86%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.86%   |
| Samsung 3570R                  | 1         | 0.86%   |
| RPi Raspberry                  | 1         | 0.86%   |
| Pegatron Pro                   | 1         | 0.86%   |
| Pegatron KX629AA-ABZ           | 1         | 0.86%   |
| PC Engines APU3                | 1         | 0.86%   |
| Packard Bell EasyNote          | 1         | 0.86%   |
| MW GMLK-2                      | 1         | 0.86%   |
| MSI NR074AA-ABZ                | 1         | 0.86%   |
| MSI KBL-U                      | 1         | 0.86%   |
| MSI GF65                       | 1         | 0.86%   |
| Lenovo ThinkCentre             | 1         | 0.86%   |
| Lenovo G505                    | 1         | 0.86%   |
| Lenovo G50-45                  | 1         | 0.86%   |
| Lenovo B590                    | 1         | 0.86%   |
| Intel NUC6i5SYB                | 1         | 0.86%   |
| Intel NUC5i5RYB                | 1         | 0.86%   |
| Intel NUC10i7FNK               | 1         | 0.86%   |
| Intel MAHOBAY                  | 1         | 0.86%   |
| Intel D945GCLF2                | 1         | 0.86%   |
| Intel D2500CC                  | 1         | 0.86%   |
| IBM ThinkPad                   | 1         | 0.86%   |
| HP Z440                        | 1         | 0.86%   |
| HP ProBook                     | 1         | 0.86%   |
| HP Mini                        | 1         | 0.86%   |
| HP EliteBook                   | 1         | 0.86%   |
| HP Compaq                      | 1         | 0.86%   |
| HARDKERNEL ODROID-H2           | 1         | 0.86%   |
| Gigabyte P55A-UD3              | 1         | 0.86%   |
| Gigabyte H270M-DS3H            | 1         | 0.86%   |
| Foxconn p6-2305elm             | 1         | 0.86%   |
| eMachines eME732ZG             | 1         | 0.86%   |
| Dell Studio                    | 1         | 0.86%   |
| Dell OptiPlex                  | 1         | 0.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 14        | 12.07%  |
| 2016    | 13        | 11.21%  |
| 2010    | 10        | 8.62%   |
| 2021    | 9         | 7.76%   |
| 2020    | 9         | 7.76%   |
| 2011    | 8         | 6.9%    |
| 2008    | 8         | 6.9%    |
| 2018    | 7         | 6.03%   |
| 2014    | 7         | 6.03%   |
| 2013    | 7         | 6.03%   |
| 2012    | 7         | 6.03%   |
| 2009    | 5         | 4.31%   |
| 2017    | 3         | 2.59%   |
| 2015    | 3         | 2.59%   |
| 2007    | 2         | 1.72%   |
| Unknown | 2         | 1.72%   |
| 2022    | 1         | 0.86%   |
| 2006    | 1         | 0.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 59        | 50.86%  |
| Notebook       | 42        | 36.21%  |
| Mini pc        | 10        | 8.62%   |
| Server         | 3         | 2.59%   |
| System on chip | 1         | 0.86%   |
| All in one     | 1         | 0.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 112       | 96.55%  |
| Yes  | 4         | 3.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 42        | 35.9%   |
| 4.01-8.0    | 37        | 31.62%  |
| 16.01-24.0  | 13        | 11.11%  |
| 2.01-3.0    | 9         | 7.69%   |
| 32.01-64.0  | 7         | 5.98%   |
| 24.01-32.0  | 3         | 2.56%   |
| 64.01-256.0 | 3         | 2.56%   |
| 3.01-4.0    | 1         | 0.85%   |
| 0.51-1.0    | 1         | 0.85%   |
| 0.01-0.5    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 72        | 60.5%   |
| 0.51-1.0   | 23        | 19.33%  |
| 1.01-2.0   | 7         | 5.88%   |
| Unknown    | 6         | 5.04%   |
| 2.01-3.0   | 5         | 4.2%    |
| 4.01-8.0   | 4         | 3.36%   |
| 24.01-32.0 | 1         | 0.84%   |
| 8.01-16.0  | 1         | 0.84%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 59.66%  |
| 2      | 25        | 21.01%  |
| 0      | 10        | 8.4%    |
| 3      | 5         | 4.2%    |
| 4      | 4         | 3.36%   |
| 10     | 1         | 0.84%   |
| 9      | 1         | 0.84%   |
| 7      | 1         | 0.84%   |
| 6      | 1         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 68.1%   |
| Yes       | 37        | 31.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 93.97%  |
| No        | 7         | 6.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 51.72%  |
| No        | 56        | 48.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 67.52%  |
| Yes       | 38        | 32.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 116       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 18        | 13.53%  |
| Rome                | 16        | 12.03%  |
| Turin               | 5         | 3.76%   |
| Bologna             | 5         | 3.76%   |
| Naples              | 3         | 2.26%   |
| Venice              | 2         | 1.5%    |
| Turrivalignani      | 2         | 1.5%    |
| Trieste             | 2         | 1.5%    |
| Silea               | 2         | 1.5%    |
| Padova              | 2         | 1.5%    |
| Monterotondo        | 2         | 1.5%    |
| Lucca               | 2         | 1.5%    |
| Catania             | 2         | 1.5%    |
| Brescia             | 2         | 1.5%    |
| Viterbo             | 1         | 0.75%   |
| Vigonovo            | 1         | 0.75%   |
| Udine               | 1         | 0.75%   |
| Treviso             | 1         | 0.75%   |
| Terni               | 1         | 0.75%   |
| Soresina            | 1         | 0.75%   |
| Solarino            | 1         | 0.75%   |
| Sasso Marconi       | 1         | 0.75%   |
| Saronno             | 1         | 0.75%   |
| Sannicandro di Bari | 1         | 0.75%   |
| San Fior            | 1         | 0.75%   |
| San Donato Milanese | 1         | 0.75%   |
| Roncade             | 1         | 0.75%   |
| Rho                 | 1         | 0.75%   |
| Resana              | 1         | 0.75%   |
| Reggio Emilia       | 1         | 0.75%   |
| Ravenna             | 1         | 0.75%   |
| Ragusa              | 1         | 0.75%   |
| Prato               | 1         | 0.75%   |
| Ponsacco            | 1         | 0.75%   |
| Pistoia             | 1         | 0.75%   |
| Piovene Rocchette   | 1         | 0.75%   |
| Pioltello           | 1         | 0.75%   |
| Parma               | 1         | 0.75%   |
| Palermo             | 1         | 0.75%   |
| Ortona              | 1         | 0.75%   |
| Oleggio             | 1         | 0.75%   |
| Nughedu San Nicolo  | 1         | 0.75%   |
| Monza               | 1         | 0.75%   |
| Modena              | 1         | 0.75%   |
| Mestrino            | 1         | 0.75%   |
| Massa Lombarda      | 1         | 0.75%   |
| Mascalucia          | 1         | 0.75%   |
| Malo                | 1         | 0.75%   |
| Malnate             | 1         | 0.75%   |
| Macerata            | 1         | 0.75%   |
| Lurago Marinone     | 1         | 0.75%   |
| Grottazzolina       | 1         | 0.75%   |
| Gorgonzola          | 1         | 0.75%   |
| Genzano di Roma     | 1         | 0.75%   |
| Gallarate           | 1         | 0.75%   |
| Follonica           | 1         | 0.75%   |
| Foligno             | 1         | 0.75%   |
| Fiumicino           | 1         | 0.75%   |
| Farneto             | 1         | 0.75%   |
| Fagagna             | 1         | 0.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 46     | 16.45%  |
| Samsung Electronics | 22        | 38     | 14.47%  |
| Seagate             | 18        | 39     | 11.84%  |
| Crucial             | 17        | 26     | 11.18%  |
| Kingston            | 8         | 9      | 5.26%   |
| Transcend           | 7         | 8      | 4.61%   |
| Toshiba             | 7         | 17     | 4.61%   |
| SanDisk             | 6         | 6      | 3.95%   |
| Hitachi             | 4         | 6      | 2.63%   |
| Micron Technology   | 3         | 3      | 1.97%   |
| KingSpec            | 3         | 4      | 1.97%   |
| Intel               | 3         | 4      | 1.97%   |
| EMTEC               | 3         | 4      | 1.97%   |
| PNY                 | 2         | 5      | 1.32%   |
| Phison              | 2         | 2      | 1.32%   |
| Maxtor              | 2         | 2      | 1.32%   |
| Leven               | 2         | 2      | 1.32%   |
| Hoodisk             | 2         | 2      | 1.32%   |
| China               | 2         | 2      | 1.32%   |
| Union Memory        | 1         | 1      | 0.66%   |
| SK Hynix            | 1         | 1      | 0.66%   |
| Silicon Motion      | 1         | 1      | 0.66%   |
| OCZ                 | 1         | 1      | 0.66%   |
| KingDian            | 1         | 1      | 0.66%   |
| Intenso             | 1         | 1      | 0.66%   |
| HGST                | 1         | 1      | 0.66%   |
| Fujitsu             | 1         | 1      | 0.66%   |
| FORESEE             | 1         | 2      | 0.66%   |
| DOGFISH             | 1         | 1      | 0.66%   |
| Corsair             | 1         | 2      | 0.66%   |
| ASUSTek Computer    | 1         | 2      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |
| A-DATA Technology   | 1         | 2      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB                       | 4         | 2.37%   |
| Crucial CT240BX500SSD1 240GB                    | 4         | 2.37%   |
| Samsung SSD 850 EVO 500GB                       | 3         | 1.78%   |
| Samsung SSD 850 EVO 250GB                       | 3         | 1.78%   |
| EMTEC X150 120GB                                | 3         | 1.78%   |
| Crucial CT500MX500SSD1 500GB                    | 3         | 1.78%   |
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 1.18%   |
| WDC WD5000AAKS-22V1A0 500GB                     | 2         | 1.18%   |
| Transcend TS256GMTS430S 256GB                   | 2         | 1.18%   |
| Toshiba MQ04ABF100 1TB                          | 2         | 1.18%   |
| Seagate ST320LT007-9ZV142 320GB                 | 2         | 1.18%   |
| Seagate ST1000DM003-1ER162 1TB                  | 2         | 1.18%   |
| Samsung SSD 970 EVO 250GB                       | 2         | 1.18%   |
| Phison SATA SSD 16GB                            | 2         | 1.18%   |
| Kingston SA400S37120G 120GB                     | 2         | 1.18%   |
| KingSpec Q-720 720GB                            | 2         | 1.18%   |
| Crucial CT250MX500SSD1 250GB                    | 2         | 1.18%   |
| Crucial CT120BX500SSD1 120GB                    | 2         | 1.18%   |
| WDC WDS250G1B0A-00H9H0 250GB                    | 1         | 0.59%   |
| WDC WDS100T2B0B-00YS70 1TB                      | 1         | 0.59%   |
| WDC WDS100T2B0A-00SM50 1TB                      | 1         | 0.59%   |
| WDC WD6400AAKS-65A7B0 640GB                     | 1         | 0.59%   |
| WDC WD5000LPVT-80G33T2 500GB                    | 1         | 0.59%   |
| WDC WD5000BPKX-00HPJT0 500GB                    | 1         | 0.59%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 0.59%   |
| WDC WD5000BMVV-11A1CS0 500GB                    | 1         | 0.59%   |
| WDC WD5000BEVT-00A03T0 500GB                    | 1         | 0.59%   |
| WDC WD5000AAKX-75U6AA0 500GB                    | 1         | 0.59%   |
| WDC WD5000AAKX-00ERMA0 500GB                    | 1         | 0.59%   |
| WDC WD5000AAKS-00E4A0 500GB                     | 1         | 0.59%   |
| WDC WD5000AAKS-00D2B0 500GB                     | 1         | 0.59%   |
| WDC WD40NMZW-11GX6S1 4TB                        | 1         | 0.59%   |
| WDC WD40EFRX-68WT0N0 4TB                        | 1         | 0.59%   |
| WDC WD40EFRX-68N32N0 4TB                        | 1         | 0.59%   |
| WDC WD3200AAKS-00L9A0 320GB                     | 1         | 0.59%   |
| WDC WD30EZRZ-00Z5HB0 3TB                        | 1         | 0.59%   |
| WDC WD30EZRZ-00GXCB0 3TB                        | 1         | 0.59%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 0.59%   |
| WDC WD2500BEVT-22A23T0 250GB                    | 1         | 0.59%   |
| WDC WD2500AAJS-07M0A0 250GB                     | 1         | 0.59%   |
| WDC WD20PURZ-85GU6Y0 2TB                        | 1         | 0.59%   |
| WDC WD20EVDS-63T3B0 2TB                         | 1         | 0.59%   |
| WDC WD2002FYPS-01U1B1 2TB                       | 1         | 0.59%   |
| WDC WD15EADS-00P8B0 1.5TB                       | 1         | 0.59%   |
| WDC WD1500HLFS-01G6U0 150GB                     | 1         | 0.59%   |
| WDC WD10SDZW-11UMGS0 1TB                        | 1         | 0.59%   |
| WDC WD10EFRX-68PJCN0 1TB                        | 1         | 0.59%   |
| WDC WD1000DHTZ-04N21V1 1TB                      | 1         | 0.59%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 0.59%   |
| Transcend TS64GMSA370 64GB                      | 1         | 0.59%   |
| Transcend TS32GSSD370 32GB                      | 1         | 0.59%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 0.59%   |
| Transcend TS128GMSA370 128GB                    | 1         | 0.59%   |
| Transcend TS128GMSA230S 128GB                   | 1         | 0.59%   |
| Toshiba TR200 240GB                             | 1         | 0.59%   |
| Toshiba Q300 240GB                              | 1         | 0.59%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 0.59%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 0.59%   |
| Toshiba MQ01ABD050 500GB                        | 1         | 0.59%   |
| Toshiba MK5065GSXF 500GB                        | 1         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 41     | 38.89%  |
| Seagate             | 18        | 39     | 33.33%  |
| Toshiba             | 5         | 13     | 9.26%   |
| Hitachi             | 4         | 6      | 7.41%   |
| Samsung Electronics | 2         | 2      | 3.7%    |
| MAXTOR              | 2         | 2      | 3.7%    |
| HGST                | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 31     | 19.32%  |
| Crucial             | 16        | 25     | 18.18%  |
| Transcend           | 6         | 7      | 6.82%   |
| SanDisk             | 6         | 6      | 6.82%   |
| WDC                 | 5         | 5      | 5.68%   |
| Kingston            | 5         | 5      | 5.68%   |
| KingSpec            | 3         | 4      | 3.41%   |
| Intel               | 3         | 4      | 3.41%   |
| EMTEC               | 3         | 4      | 3.41%   |
| Toshiba             | 2         | 4      | 2.27%   |
| PNY                 | 2         | 5      | 2.27%   |
| Phison              | 2         | 2      | 2.27%   |
| Micron Technology   | 2         | 2      | 2.27%   |
| Leven               | 2         | 2      | 2.27%   |
| Hoodisk             | 2         | 2      | 2.27%   |
| China               | 2         | 2      | 2.27%   |
| SK Hynix            | 1         | 1      | 1.14%   |
| OCZ                 | 1         | 1      | 1.14%   |
| KingDian            | 1         | 1      | 1.14%   |
| Intenso             | 1         | 1      | 1.14%   |
| FORESEE             | 1         | 2      | 1.14%   |
| DOGFISH             | 1         | 1      | 1.14%   |
| Corsair             | 1         | 2      | 1.14%   |
| ASUSTek Computer    | 1         | 2      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |
| A-DATA Technology   | 1         | 2      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 71        | 124    | 56.8%   |
| HDD  | 41        | 105    | 32.8%   |
| NVMe | 13        | 14     | 10.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 229    | 88.29%  |
| NVMe | 13        | 14     | 11.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 149    | 72.41%  |
| 0.51-1.0   | 19        | 54     | 16.38%  |
| 1.01-2.0   | 7         | 9      | 6.03%   |
| 3.01-4.0   | 3         | 4      | 2.59%   |
| 2.01-3.0   | 2         | 5      | 1.72%   |
| 10.01-20.0 | 1         | 8      | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 40        | 33.9%   |
| 101-250        | 29        | 24.58%  |
| 251-500        | 18        | 15.25%  |
| 21-50          | 12        | 10.17%  |
| 51-100         | 9         | 7.63%   |
| 501-1000       | 7         | 5.93%   |
| More than 3000 | 2         | 1.69%   |
| Unknown        | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 102       | 85.71%  |
| 21-50          | 10        | 8.4%    |
| 51-100         | 2         | 1.68%   |
| More than 3000 | 1         | 0.84%   |
| 101-250        | 1         | 0.84%   |
| 1001-2000      | 1         | 0.84%   |
| 501-1000       | 1         | 0.84%   |
| Unknown        | 1         | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2         | 2      | 8.33%   |
| Seagate ST320LT007-9ZV142 320GB   | 2         | 2      | 8.33%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1         | 1      | 4.17%   |
| WDC WD5000AAKS-00E4A0 500GB       | 1         | 1      | 4.17%   |
| WDC WD20EVDS-63T3B0 2TB           | 1         | 1      | 4.17%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 4.17%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 4.17%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 2      | 4.17%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1         | 1      | 4.17%   |
| Seagate ST31500341AS 1.5TB        | 1         | 1      | 4.17%   |
| SanDisk SD9SN8W-128G-1006 128GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 4.17%   |
| OCZ VERTEX3 120GB                 | 1         | 1      | 4.17%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 4.17%   |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2      | 4.17%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 4.17%   |
| Hitachi HDS723030ALA640 3TB       | 1         | 2      | 4.17%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 3      | 4.17%   |
| China SATA3 240GB SSD             | 1         | 1      | 4.17%   |
| A-DATA Technology SX300 128GB     | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 29.17%  |
| WDC                 | 6         | 6      | 25%     |
| Hitachi             | 3         | 5      | 12.5%   |
| Toshiba             | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Samsung Electronics | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Crucial             | 1         | 3      | 4.17%   |
| China               | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 38.89%  |
| WDC                 | 6         | 6      | 33.33%  |
| Hitachi             | 3         | 5      | 16.67%  |
| Toshiba             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 21     | 72.73%  |
| SSD  | 6         | 8      | 27.27%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 92        | 199    | 77.31%  |
| Malfunc  | 22        | 29     | 18.49%  |
| Detected | 5         | 15     | 4.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 62.22%  |
| AMD                              | 21        | 15.56%  |
| Samsung Electronics              | 6         | 4.44%   |
| Marvell Technology Group         | 3         | 2.22%   |
| Kingston Technology Company      | 3         | 2.22%   |
| Broadcom / LSI                   | 3         | 2.22%   |
| VIA Technologies                 | 2         | 1.48%   |
| JMicron Technology               | 2         | 1.48%   |
| ASMedia Technology               | 2         | 1.48%   |
| Union Memory (Shenzhen)          | 1         | 0.74%   |
| Silicon Motion                   | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Nvidia                           | 1         | 0.74%   |
| Micron/Crucial Technology        | 1         | 0.74%   |
| Micron Technology                | 1         | 0.74%   |
| Integrated Technology Express    | 1         | 0.74%   |
| Adaptec                          | 1         | 0.74%   |
| Unknown                          | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 9.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 4.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 4.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 3.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 5         | 3.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 2.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 2.52%   |
| Unknown                                                                          | 4         | 2.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.89%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.89%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2         | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 1         | 0.63%   |
| Samsung SM951 AHCI                                                               | 1         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.63%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.63%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.63%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.63%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.63%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1         | 0.63%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.63%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.63%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.63%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.63%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.63%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.63%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.63%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 1         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                       | 1         | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1         | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 87        | 65.41%  |
| IDE  | 25        | 18.8%   |
| NVMe | 13        | 9.77%   |
| RAID | 6         | 4.51%   |
| SCSI | 2         | 1.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 90        | 77.59%  |
| AMD      | 23        | 19.83%  |
| Broadcom | 1         | 0.86%   |
| Arm      | 1         | 0.86%   |
| Unknown  | 1         | 0.86%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                              | 4         | 3.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.56%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 1.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.71%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.71%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.71%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 2         | 1.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD Phenom II X4 965 Processor                | 2         | 1.71%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz         | 1         | 0.85%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.85%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1         | 0.85%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.85%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1         | 0.85%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1         | 0.85%   |
| Intel Xeon CPU E3113 @ 3.00GHz                | 1         | 0.85%   |
| Intel Pentium M processor                     | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E6600             | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.85%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.85%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.85%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1         | 0.85%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.85%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 0.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.85%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 0.85%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.85%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i5-6260U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.85%   |
| Intel Core i5-4210Y CPU @ 1.50GHz             | 1         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.85%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i5 CPU                             | 1         | 0.85%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 0.85%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 1         | 0.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1         | 0.85%   |
| Intel Core i3-3225 CPU @ 3.30GHz              | 1         | 0.85%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 1         | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 1         | 0.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 17.09%  |
| Intel Celeron           | 15        | 12.82%  |
| Intel Core i7           | 12        | 10.26%  |
| Intel Core i3           | 9         | 7.69%   |
| Intel Core 2 Duo        | 8         | 6.84%   |
| Intel Xeon              | 6         | 5.13%   |
| Intel Atom              | 6         | 5.13%   |
| Intel Pentium           | 5         | 4.27%   |
| AMD Ryzen 5             | 5         | 4.27%   |
| AMD GX                  | 4         | 3.42%   |
| Other                   | 3         | 2.56%   |
| Intel Pentium Dual      | 3         | 2.56%   |
| Intel Pentium Dual-Core | 2         | 1.71%   |
| AMD Ryzen 7             | 2         | 1.71%   |
| AMD Phenom II X4        | 2         | 1.71%   |
| Intel Xeon Silver       | 1         | 0.85%   |
| Intel Pentium M         | 1         | 0.85%   |
| Intel Core 2 Quad       | 1         | 0.85%   |
| Intel Core 2 Extreme    | 1         | 0.85%   |
| Intel 686-class         | 1         | 0.85%   |
| AMD Turion 64 X2 Mobile | 1         | 0.85%   |
| AMD Ryzen Embedded      | 1         | 0.85%   |
| AMD Ryzen 9             | 1         | 0.85%   |
| AMD Ryzen 7 PRO         | 1         | 0.85%   |
| AMD Ryzen 3             | 1         | 0.85%   |
| AMD FX                  | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD E1                  | 1         | 0.85%   |
| AMD Athlon II X4        | 1         | 0.85%   |
| AMD A4                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 53        | 45.3%   |
| 4       | 32        | 27.35%  |
| Unknown | 15        | 12.82%  |
| 12      | 5         | 4.27%   |
| 8       | 5         | 4.27%   |
| 16      | 2         | 1.71%   |
| 6       | 2         | 1.71%   |
| 1       | 2         | 1.71%   |
| 32      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 109       | 93.16%  |
| 2       | 4         | 3.42%   |
| Unknown | 4         | 3.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 52        | 44.44%  |
| 2       | 50        | 42.74%  |
| Unknown | 15        | 12.82%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 11        | 9.4%    |
| SandyBridge   | 10        | 8.55%   |
| KabyLake      | 10        | 8.55%   |
| IvyBridge     | 9         | 7.69%   |
| Haswell       | 9         | 7.69%   |
| Goldmont plus | 6         | 5.13%   |
| Bonnell       | 6         | 5.13%   |
| Zen+          | 5         | 4.27%   |
| Puma          | 5         | 4.27%   |
| Core          | 5         | 4.27%   |
| Broadwell     | 5         | 4.27%   |
| Unknown       | 5         | 4.27%   |
| Westmere      | 4         | 3.42%   |
| Skylake       | 4         | 3.42%   |
| Silvermont    | 4         | 3.42%   |
| K10           | 3         | 2.56%   |
| Zen 2         | 2         | 1.71%   |
| Zen           | 2         | 1.71%   |
| Nehalem       | 2         | 1.71%   |
| Goldmont      | 2         | 1.71%   |
| CometLake     | 2         | 1.71%   |
| Zen 3         | 1         | 0.85%   |
| Piledriver    | 1         | 0.85%   |
| P6            | 1         | 0.85%   |
| K8 Hammer     | 1         | 0.85%   |
| K10 Llano     | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 70        | 60.34%  |
| AMD                              | 25        | 21.55%  |
| Nvidia                           | 18        | 15.52%  |
| Matrox Electronics Systems       | 2         | 1.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.86%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 5%      |
| Intel UHD Graphics 620                                                                   | 4         | 3.33%   |
| Intel HD Graphics 620                                                                    | 4         | 3.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.33%   |
| Intel HD Graphics 6000                                                                   | 3         | 2.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.67%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.67%   |
| Intel HD Graphics 500                                                                    | 2         | 1.67%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 1.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.67%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 1.67%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.83%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.83%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.83%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.83%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.83%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.83%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1         | 0.83%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.83%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1         | 0.83%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.83%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.83%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.83%   |
| Intel Iris Graphics 540                                                                  | 1         | 0.83%   |
| Intel HD Graphics 630                                                                    | 1         | 0.83%   |
| Intel HD Graphics 530                                                                    | 1         | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.83%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.83%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.83%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.83%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.83%   |
| AMD Whistler LE [Radeon HD 6610M/7610M]                                                  | 1         | 0.83%   |
| AMD SuperSumo [Radeon HD 6370D]                                                          | 1         | 0.83%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 48.72%  |
| 1 x AMD        | 23        | 19.66%  |
| 1 x Nvidia     | 12        | 10.26%  |
| Other          | 8         | 6.84%   |
| 2 x Intel      | 6         | 5.13%   |
| Intel + Nvidia | 6         | 5.13%   |
| 1 x Matrox     | 2         | 1.71%   |
| 2 x AMD        | 1         | 0.85%   |
| 1 x SiS        | 1         | 0.85%   |
| Intel + AMD    | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 94        | 78.99%  |
| Unknown     | 13        | 10.92%  |
| Proprietary | 12        | 10.08%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 76.27%  |
| 1.01-2.0   | 9         | 7.63%   |
| 0.01-0.5   | 8         | 6.78%   |
| 3.01-4.0   | 5         | 4.24%   |
| 0.51-1.0   | 4         | 3.39%   |
| 7.01-8.0   | 1         | 0.85%   |
| 5.01-6.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 11        | 16.42%  |
| Samsung Electronics  | 7         | 10.45%  |
| LG Display           | 6         | 8.96%   |
| Acer                 | 6         | 8.96%   |
| Hewlett-Packard      | 4         | 5.97%   |
| BOE                  | 4         | 5.97%   |
| Apple                | 4         | 5.97%   |
| Dell                 | 3         | 4.48%   |
| Chimei Innolux       | 3         | 4.48%   |
| Philips              | 2         | 2.99%   |
| Lenovo               | 2         | 2.99%   |
| HannStar             | 2         | 2.99%   |
| Goldstar             | 2         | 2.99%   |
| ___                  | 1         | 1.49%   |
| Sony                 | 1         | 1.49%   |
| Packard Bell         | 1         | 1.49%   |
| Orion                | 1         | 1.49%   |
| LG Philips           | 1         | 1.49%   |
| LG Electronics       | 1         | 1.49%   |
| Iiyama               | 1         | 1.49%   |
| Fujitsu Siemens      | 1         | 1.49%   |
| Eizo                 | 1         | 1.49%   |
| ASUSTek Computer     | 1         | 1.49%   |
| Ancor Communications | 1         | 1.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 2         | 2.99%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                      | 2         | 2.99%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.49%   |
| Sony TV SNY5D01 1360x768                                             | 1         | 1.49%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 1.49%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 1.49%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1         | 1.49%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch             | 1         | 1.49%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 1         | 1.49%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch       | 1         | 1.49%   |
| Orion LCD Monitor ORN1207 1920x1080                                  | 1         | 1.49%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.49%   |
| LG Electronics LCD Monitor E2360 1920x1080                           | 1         | 1.49%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 1.49%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 1.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.49%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 1.49%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 1.49%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1         | 1.49%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch    | 1         | 1.49%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch            | 1         | 1.49%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 1.49%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch           | 1         | 1.49%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 1.49%   |
| HannStar HSG1233 HSP0018 1920x1080 520x290mm 23.4-inch               | 1         | 1.49%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 1         | 1.49%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch          | 1         | 1.49%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 1.49%   |
| Eizo LCD Monitor S1901 1280x1024                                     | 1         | 1.49%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1         | 1.49%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                    | 1         | 1.49%   |
| Dell 2007FP DELA021 1600x1200 410x310mm 20.2-inch                    | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 1.49%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.49%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 1.49%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 1.49%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 1.49%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch        | 1         | 1.49%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch         | 1         | 1.49%   |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 1         | 1.49%   |
| Apple Color LCD APP9CB5 2560x1440 600x340mm 27.2-inch                | 1         | 1.49%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                 | 1         | 1.49%   |
| Apple Cinema HD APP9223 1920x1200 490x310mm 22.8-inch                | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 26        | 41.27%  |
| 1366x768 (WXGA)   | 15        | 23.81%  |
| 1440x900 (WXGA+)  | 4         | 6.35%   |
| 1600x900 (HD+)    | 3         | 4.76%   |
| 1280x1024 (SXGA)  | 3         | 4.76%   |
| 1920x1200 (WUXGA) | 2         | 3.17%   |
| 1280x800 (WXGA)   | 2         | 3.17%   |
| 1024x600          | 2         | 3.17%   |
| 3840x2160 (4K)    | 1         | 1.59%   |
| 2560x1440 (QHD)   | 1         | 1.59%   |
| 2560x1080         | 1         | 1.59%   |
| 1600x1200         | 1         | 1.59%   |
| 1360x768          | 1         | 1.59%   |
| 1024x768 (XGA)    | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 16        | 23.88%  |
| 13      | 9         | 13.43%  |
| Unknown | 7         | 10.45%  |
| 24      | 5         | 7.46%   |
| 23      | 5         | 7.46%   |
| 27      | 4         | 5.97%   |
| 19      | 4         | 5.97%   |
| 21      | 3         | 4.48%   |
| 31      | 2         | 2.99%   |
| 18      | 2         | 2.99%   |
| 12      | 2         | 2.99%   |
| 10      | 2         | 2.99%   |
| 28      | 1         | 1.49%   |
| 22      | 1         | 1.49%   |
| 20      | 1         | 1.49%   |
| 17      | 1         | 1.49%   |
| 14      | 1         | 1.49%   |
| 11      | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 23        | 35.38%  |
| 501-600     | 12        | 18.46%  |
| 201-300     | 8         | 12.31%  |
| Unknown     | 7         | 10.77%  |
| 401-500     | 6         | 9.23%   |
| 351-400     | 5         | 7.69%   |
| 601-700     | 4         | 6.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 45        | 75%     |
| 16/10   | 8         | 13.33%  |
| 5/4     | 2         | 3.33%   |
| 4/3     | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 21/9    | 1         | 1.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 11        | 17.19%  |
| 201-250        | 10        | 15.63%  |
| 81-90          | 9         | 14.06%  |
| Unknown        | 7         | 10.94%  |
| 151-200        | 6         | 9.38%   |
| 101-110        | 6         | 9.38%   |
| 301-350        | 4         | 6.25%   |
| 251-300        | 3         | 4.69%   |
| 61-70          | 2         | 3.13%   |
| 351-500        | 2         | 3.13%   |
| 41-50          | 2         | 3.13%   |
| 51-60          | 1         | 1.56%   |
| 121-130        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 24        | 38.1%   |
| 101-120 | 19        | 30.16%  |
| 121-160 | 12        | 19.05%  |
| Unknown | 7         | 11.11%  |
| 161-240 | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 58        | 49.15%  |
| 0     | 55        | 46.61%  |
| 2     | 5         | 4.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 66        | 40.99%  |
| Realtek Semiconductor    | 48        | 29.81%  |
| Qualcomm Atheros         | 18        | 11.18%  |
| Broadcom                 | 12        | 7.45%   |
| Ralink Technology        | 2         | 1.24%   |
| Ralink                   | 2         | 1.24%   |
| Marvell Technology Group | 2         | 1.24%   |
| OPPO Electronics         | 1         | 0.62%   |
| Nvidia                   | 1         | 0.62%   |
| NetGear                  | 1         | 0.62%   |
| IMC Networks             | 1         | 0.62%   |
| Huawei Technologies      | 1         | 0.62%   |
| Hewlett-Packard          | 1         | 0.62%   |
| Edimax Technology        | 1         | 0.62%   |
| Digital Equipment        | 1         | 0.62%   |
| Davicom Semiconductor    | 1         | 0.62%   |
| Apple                    | 1         | 0.62%   |
| AMD                      | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 41        | 20.71%  |
| Intel I211 Gigabit Network Connection                                                 | 13        | 6.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5         | 2.53%   |
| Intel 82574L Gigabit Network Connection                                               | 5         | 2.53%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 2.02%   |
| Intel Wireless 7265                                                                   | 4         | 2.02%   |
| Intel I210 Gigabit Network Connection                                                 | 4         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 3         | 1.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 3         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 1.52%   |
| Intel Wireless 8260                                                                   | 3         | 1.52%   |
| Intel Wireless 3165                                                                   | 3         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                               | 3         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 1.01%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 1.01%   |
| Intel Wireless 7260                                                                   | 2         | 1.01%   |
| Intel I350 Gigabit Network Connection                                                 | 2         | 1.01%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 1.01%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 1.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.51%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.51%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.51%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.51%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.51%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 0.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 0.51%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.51%   |
| OPPO SDM720G-IDP _SN:AB3CB1F6 RNDIS Control RNDIS Ethernet Data                       | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.51%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 0.51%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.51%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.51%   |
| Intel Ultimate N WiFi Link 5300                                                       | 1         | 0.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.51%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 0.51%   |
| Intel Ethernet Controller I225-V                                                      | 1         | 0.51%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                         | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 0.51%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 0.51%   |
| Intel Ethernet Connection I218-V                                                      | 1         | 0.51%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 38.46%  |
| Qualcomm Atheros      | 17        | 26.15%  |
| Realtek Semiconductor | 10        | 15.38%  |
| Broadcom              | 6         | 9.23%   |
| Ralink Technology     | 2         | 3.08%   |
| Ralink                | 2         | 3.08%   |
| NetGear               | 1         | 1.54%   |
| IMC Networks          | 1         | 1.54%   |
| Edimax Technology     | 1         | 1.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 7.46%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 5.97%   |
| Intel Wireless 7265                                                                   | 4         | 5.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 4.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 4.48%   |
| Intel Wireless 8260                                                                   | 3         | 4.48%   |
| Intel Wireless 3165                                                                   | 3         | 4.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.99%   |
| Intel Wireless 7260                                                                   | 2         | 2.99%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 2.99%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 2.99%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 1.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.49%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.49%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.49%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 1.49%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.49%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1         | 1.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.49%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.49%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 1.49%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.49%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.49%   |
| Intel Ultimate N WiFi Link 5300                                                       | 1         | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.49%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.49%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1         | 1.49%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1         | 1.49%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 54        | 45%     |
| Realtek Semiconductor    | 46        | 38.33%  |
| Broadcom                 | 7         | 5.83%   |
| Qualcomm Atheros         | 5         | 4.17%   |
| Marvell Technology Group | 2         | 1.67%   |
| OPPO Electronics         | 1         | 0.83%   |
| Nvidia                   | 1         | 0.83%   |
| Digital Equipment        | 1         | 0.83%   |
| Davicom Semiconductor    | 1         | 0.83%   |
| Apple                    | 1         | 0.83%   |
| AMD                      | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 41        | 32.03%  |
| Intel I211 Gigabit Network Connection                                         | 13        | 10.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 3.91%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.91%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 3.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 2.34%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 2.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 1.56%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.78%   |
| OPPO SDM720G-IDP _SN:AB3CB1F6 RNDIS Control RNDIS Ethernet Data               | 1         | 0.78%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.78%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.78%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 1         | 0.78%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.78%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.78%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.78%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.78%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.78%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                            | 1         | 0.78%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.78%   |
| Intel 82577LC Gigabit Network Connection                                      | 1         | 0.78%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.78%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 0.78%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.78%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.78%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1         | 0.78%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.78%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.78%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 0.78%   |
| Digital Equipment DECchip 21142/43                                            | 1         | 0.78%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1         | 0.78%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.78%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.78%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1         | 0.78%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                 | 1         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 1         | 0.78%   |
| Apple Ethernet Adapter [A1277]                                                | 1         | 0.78%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 109       | 63.37%  |
| WiFi     | 60        | 34.88%  |
| Modem    | 3         | 1.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 103       | 72.54%  |
| WiFi     | 39        | 27.46%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 49.14%  |
| 1     | 26        | 22.41%  |
| 3     | 12        | 10.34%  |
| 4     | 9         | 7.76%   |
| 5     | 5         | 4.31%   |
| 0     | 3         | 2.59%   |
| 7     | 2         | 1.72%   |
| 8     | 1         | 0.86%   |
| 6     | 1         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 40%     |
| Realtek Semiconductor           | 4         | 10%     |
| IMC Networks                    | 4         | 10%     |
| Qualcomm Atheros Communications | 3         | 7.5%    |
| Cambridge Silicon Radio         | 3         | 7.5%    |
| Apple                           | 3         | 7.5%    |
| Integrated System Solution      | 2         | 5%      |
| Toshiba                         | 1         | 2.5%    |
| Lite-On Technology              | 1         | 2.5%    |
| Hewlett-Packard                 | 1         | 2.5%    |
| Broadcom                        | 1         | 2.5%    |
| ASUSTek Computer                | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                         | 12        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 3         | 7.5%    |
| Realtek  Bluetooth 4.2 Adapter                             | 2         | 5%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                      | 2         | 5%      |
| Intel AX201 Bluetooth                                      | 2         | 5%      |
| Integrated System Solution Bluetooth Device                | 2         | 5%      |
| IMC Networks Bluetooth Radio                               | 2         | 5%      |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip            | 1         | 2.5%    |
| Realtek RTL8723B Bluetooth                                 | 1         | 2.5%    |
| Realtek  Bluetooth Adapter                                 | 1         | 2.5%    |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter | 1         | 2.5%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                | 1         | 2.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                   | 1         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                           | 1         | 2.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                | 1         | 2.5%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS           | 1         | 2.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]              | 1         | 2.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                 | 1         | 2.5%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                      | 1         | 2.5%    |
| Apple Built-in iSight (no firmware loaded)                 | 1         | 2.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                       | 1         | 2.5%    |
| Apple Apple Broadcom Built-in Bluetooth                    | 1         | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 79        | 63.71%  |
| AMD                              | 26        | 20.97%  |
| Nvidia                           | 13        | 10.48%  |
| Logitech                         | 2         | 1.61%   |
| C-Media Electronics              | 2         | 1.61%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Bose                             | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 7.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 6%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 4%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.33%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 2.67%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 2%      |
| AMD FCH Azalia Controller                                                                         | 3         | 2%      |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.33%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.33%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.33%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.33%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Logitech Headset H340                                                                             | 1         | 0.67%   |
| Logitech HD Webcam C510                                                                           | 1         | 0.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.67%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.67%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.67%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.67%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.67%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.67%   |
| C-Media Electronics Audio Adapter (Planet UP-100, Genius G-Talk)                                  | 1         | 0.67%   |
| Bose Bose USB Audio                                                                               | 1         | 0.67%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.67%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.67%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 19.51%  |
| Unknown             | 17        | 13.82%  |
| SK Hynix            | 17        | 13.82%  |
| Kingston            | 17        | 13.82%  |
| Crucial             | 10        | 8.13%   |
| Micron Technology   | 9         | 7.32%   |
| Unknown (ABCD)      | 5         | 4.07%   |
| Unknown             | 5         | 4.07%   |
| Nanya Technology    | 4         | 3.25%   |
| Corsair             | 4         | 3.25%   |
| Transcend           | 2         | 1.63%   |
| Ramaxel Technology  | 2         | 1.63%   |
| Unknown (F301)      | 1         | 0.81%   |
| Unknown (AB)        | 1         | 0.81%   |
| KomputerBay         | 1         | 0.81%   |
| Intersil            | 1         | 0.81%   |
| G.Skill             | 1         | 0.81%   |
| Elpida              | 1         | 0.81%   |
| A-DATA Technology   | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s   | 5         | 3.76%   |
| Unknown                                                             | 5         | 3.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.26%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 2         | 1.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 2         | 1.5%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.5%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s               | 2         | 1.5%    |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                         | 2         | 1.5%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.5%    |
| Unknown SODIMM 4GB SODIMM 800MT/s                                   | 1         | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.75%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                        | 1         | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                          | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                           | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                            | 1         | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 1         | 0.75%   |
| Unknown RAM Module 256MB SODIMM DDR                                 | 1         | 0.75%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                            | 1         | 0.75%   |
| Unknown (F301) RAM G2JT-4AFR00 16GB SODIMM DDR4 2400MT/s            | 1         | 0.75%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s                 | 1         | 0.75%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s                | 1         | 0.75%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s                 | 1         | 0.75%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1333MT/s                          | 1         | 0.75%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                        | 1         | 0.75%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 1         | 0.75%   |
| SK Hynix RAM HYMP151P72CP4-Y5 4GB DIMM DDR2 667MT/s                 | 1         | 0.75%   |
| SK Hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s                 | 1         | 0.75%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s                 | 1         | 0.75%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.75%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.75%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s                | 1         | 0.75%   |
| SK Hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                     | 1         | 0.75%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.75%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.75%   |
| SK Hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s               | 1         | 0.75%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.75%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s             | 1         | 0.75%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s               | 1         | 0.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.75%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.75%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s               | 1         | 0.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s               | 1         | 0.75%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.75%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.75%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s               | 1         | 0.75%   |
| Samsung RAM M393B5270CH0-CH9 4GB DIMM DDR3 1333MT/s                 | 1         | 0.75%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s                 | 1         | 0.75%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                 | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 51        | 46.79%  |
| DDR4    | 27        | 24.77%  |
| DDR2    | 16        | 14.68%  |
| LPDDR4  | 6         | 5.5%    |
| Unknown | 6         | 5.5%    |
| SDRAM   | 1         | 0.92%   |
| LPDDR3  | 1         | 0.92%   |
| DDR     | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 57        | 53.27%  |
| DIMM         | 47        | 43.93%  |
| Chip         | 2         | 1.87%   |
| Row Of Chips | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 44        | 38.26%  |
| 2048  | 27        | 23.48%  |
| 8192  | 23        | 20%     |
| 16384 | 14        | 12.17%  |
| 1024  | 4         | 3.48%   |
| 32768 | 2         | 1.74%   |
| 256   | 1         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 25        | 21.37%  |
| 1333    | 19        | 16.24%  |
| 2400    | 15        | 12.82%  |
| 2667    | 11        | 9.4%    |
| 1067    | 9         | 7.69%   |
| 667     | 9         | 7.69%   |
| 800     | 7         | 5.98%   |
| 2133    | 6         | 5.13%   |
| 3200    | 4         | 3.42%   |
| 1334    | 3         | 2.56%   |
| Unknown | 3         | 2.56%   |
| 1066    | 2         | 1.71%   |
| 2933    | 1         | 0.85%   |
| 2666    | 1         | 0.85%   |
| 1200    | 1         | 0.85%   |
| 333     | 1         | 0.85%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 30.56%  |
| IMC Networks                           | 5         | 13.89%  |
| Sunplus Innovation Technology          | 3         | 8.33%   |
| Realtek Semiconductor                  | 3         | 8.33%   |
| Acer                                   | 3         | 8.33%   |
| Silicon Motion                         | 2         | 5.56%   |
| Logitech                               | 2         | 5.56%   |
| Suyin                                  | 1         | 2.78%   |
| Microdia                               | 1         | 2.78%   |
| Lite-On Technology                     | 1         | 2.78%   |
| KYE Systems (Mouse Systems)            | 1         | 2.78%   |
| Genesys Logic                          | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.78%   |
| ALi                                    | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 5.56%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 5.56%   |
| Chicony Integrated Camera                                  | 2         | 5.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.78%   |
| Sunplus Integrated Camera                                  | 1         | 2.78%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.78%   |
| Sunplus Aukey-PC-LM1E Camera                               | 1         | 2.78%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.78%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.78%   |
| Realtek USB Camera                                         | 1         | 2.78%   |
| Microdia ASUS USB2.0 Webcam                                | 1         | 2.78%   |
| Logitech Webcam C310                                       | 1         | 2.78%   |
| Logitech C505 HD Webcam                                    | 1         | 2.78%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.78%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera           | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.78%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.78%   |
| IMC Networks Integrated Camera                             | 1         | 2.78%   |
| Genesys Logic Digital Microscope                           | 1         | 2.78%   |
| Chicony WebCam                                             | 1         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.78%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.78%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.78%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.78%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.78%   |
| Chicony HD WebCam (Acer)                                   | 1         | 2.78%   |
| Chicony 1.3M Webcam                                        | 1         | 2.78%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.78%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.78%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.78%   |
| Acer Integrated Camera                                     | 1         | 2.78%   |
| Acer HD Webcam                                             | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 2         | 33.33%  |
| Validity Sensors      | 1         | 16.67%  |
| Upek                  | 1         | 16.67%  |
| Synaptics             | 1         | 16.67%  |
| Elan Microelectronics | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 16.67%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 16.67%  |
| AuthenTec AES2810                                      | 1         | 16.67%  |
| AuthenTec AES1600                                      | 1         | 16.67%  |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 36.75%  |
| 0     | 38        | 32.48%  |
| 2     | 20        | 17.09%  |
| 3     | 14        | 11.97%  |
| 4     | 2         | 1.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 48.8%   |
| Net/wireless             | 16        | 12.8%   |
| Card reader              | 16        | 12.8%   |
| Bluetooth                | 14        | 11.2%   |
| Firewire controller      | 8         | 6.4%    |
| Fingerprint reader       | 6         | 4.8%    |
| Graphics card            | 2         | 1.6%    |
| Network                  | 1         | 0.8%    |
| Modem                    | 1         | 0.8%    |

