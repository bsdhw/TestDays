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

Total: 219

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 0A98h                       | Desktop     | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Acer          | AOD260                      | Notebook    | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | Desktop     | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | F50SL                       | Notebook    | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | Notebook    | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
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
| PC Engines    | APU2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
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
| helloSystem 0.7.0    | 15        | 9.74%   |
| helloSystem 0.4.0    | 12        | 7.79%   |
| helloSystem 0.5.0    | 9         | 5.84%   |
| helloSystem 0.6.0    | 6         | 3.9%    |
| OPNsense 22.1.6      | 5         | 3.25%   |
| helloSystem 0.3.0    | 5         | 3.25%   |
| OPNsense 22.1        | 4         | 2.6%    |
| OPNsense 21.1        | 4         | 2.6%    |
| OpenBSD 7.1          | 4         | 2.6%    |
| OPNsense 22.1.9      | 3         | 1.95%   |
| OPNsense 21.7.7      | 3         | 1.95%   |
| OPNsense 21.7.3      | 3         | 1.95%   |
| OPNsense 21.1.8      | 3         | 1.95%   |
| OPNsense 21.1.3      | 3         | 1.95%   |
| OPNsense 21.1.2      | 3         | 1.95%   |
| OPNsense 20.7.8      | 3         | 1.95%   |
| OpenBSD 6.8          | 3         | 1.95%   |
| NomadBSD 1.4         | 3         | 1.95%   |
| FreeBSD 13.0-p7      | 3         | 1.95%   |
| FreeBSD 12.2-p2      | 3         | 1.95%   |
| OPNsense 22.1.8      | 2         | 1.3%    |
| OPNsense 22.1.4      | 2         | 1.3%    |
| OPNsense 21.1.1      | 2         | 1.3%    |
| NomadBSD 1.3.2       | 2         | 1.3%    |
| GhostBSD 21.08.27    | 2         | 1.3%    |
| GhostBSD 20.04.02    | 2         | 1.3%    |
| FreeBSD 13.0-p4      | 2         | 1.3%    |
| FreeBSD 13.0-CURRENT | 2         | 1.3%    |
| FreeBSD 12.3-p1      | 2         | 1.3%    |
| FreeBSD 12.2-p6      | 2         | 1.3%    |
| FreeBSD 12.2-p4      | 2         | 1.3%    |
| FreeBSD 12.1-p10     | 2         | 1.3%    |
| OPNsense 22.1.7      | 1         | 0.65%   |
| OPNsense 22.1.3      | 1         | 0.65%   |
| OPNsense 22.1.2      | 1         | 0.65%   |
| OPNsense 22.1.1      | 1         | 0.65%   |
| OPNsense 21.7.8      | 1         | 0.65%   |
| OPNsense 21.7.6      | 1         | 0.65%   |
| OPNsense 21.7.4      | 1         | 0.65%   |
| OPNsense 21.7.1      | 1         | 0.65%   |
| OPNsense 21.7        | 1         | 0.65%   |
| OPNsense 21.1.7      | 1         | 0.65%   |
| OPNsense 21.1.6      | 1         | 0.65%   |
| OPNsense 21.1.5      | 1         | 0.65%   |
| OpenBSD 6.7          | 1         | 0.65%   |
| NomadBSD 5806f915    | 1         | 0.65%   |
| NomadBSD 1.3.1       | 1         | 0.65%   |
| NetBSD 9.99.93       | 1         | 0.65%   |
| NetBSD 9.99.77       | 1         | 0.65%   |
| NetBSD 9.2_STABLE    | 1         | 0.65%   |
| NetBSD 9.2           | 1         | 0.65%   |
| NetBSD 9.1_STABLE    | 1         | 0.65%   |
| NetBSD 9.1           | 1         | 0.65%   |
| NetBSD 9.0           | 1         | 0.65%   |
| FreeBSD 14.0-CURRENT | 1         | 0.65%   |
| FreeBSD 13.1-RC5     | 1         | 0.65%   |
| FreeBSD 13.1-BETA2   | 1         | 0.65%   |
| FreeBSD 13.1         | 1         | 0.65%   |
| FreeBSD 13.0-p5      | 1         | 0.65%   |
| FreeBSD 13.0-p3      | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 42        | 32.31%  |
| helloSystem | 39        | 30%     |
| FreeBSD     | 24        | 18.46%  |
| OpenBSD     | 8         | 6.15%   |
| NomadBSD    | 7         | 5.38%   |
| NetBSD      | 6         | 4.62%   |
| GhostBSD    | 4         | 3.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 123       | 95.35%  |
| i386   | 3         | 2.33%   |
| evbarm | 3         | 2.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 51        | 38.93%  |
| helloDesktop  | 41        | 31.3%   |
| Openbox       | 7         | 5.34%   |
| XFCE          | 5         | 3.82%   |
| KDE5          | 5         | 3.82%   |
| fvwm          | 4         | 3.05%   |
| MATE          | 3         | 2.29%   |
| i3            | 3         | 2.29%   |
| CTWM          | 3         | 2.29%   |
| Cinnamon      | 3         | 2.29%   |
| TWM           | 2         | 1.53%   |
| xfwm          | 1         | 0.76%   |
| LXQt          | 1         | 0.76%   |
| Fluxbox       | 1         | 0.76%   |
| Enlightenment | 1         | 0.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 80        | 62.02%  |
| Console | 49        | 37.98%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 69        | 53.49%  |
| SLiM    | 50        | 38.76%  |
| LightDM | 6         | 4.65%   |
| XDM     | 2         | 1.55%   |
| SDDM    | 2         | 1.55%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 56        | 42.75%  |
| en_US            | 49        | 37.4%   |
| it_IT            | 13        | 9.92%   |
| C                | 8         | 6.11%   |
| it_IT.ISO8859-15 | 2         | 1.53%   |
| ru_RU            | 1         | 0.76%   |
| it_IT.ISO8859-1  | 1         | 0.76%   |
| en_GB            | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 103       | 78.63%  |
| BIOS | 28        | 21.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 60        | 45.11%  |
| Zfs    | 57        | 42.86%  |
| Ffs    | 8         | 6.02%   |
| Cd9660 | 8         | 6.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 113       | 86.92%  |
| MBR     | 14        | 10.77%  |
| Unknown | 3         | 2.31%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 23        | 17.83%  |
| Lenovo                     | 14        | 10.85%  |
| Hewlett-Packard            | 10        | 7.75%   |
| Intel                      | 9         | 6.98%   |
| Dell                       | 9         | 6.98%   |
| Acer                       | 7         | 5.43%   |
| Unknown                    | 7         | 5.43%   |
| MSI                        | 5         | 3.88%   |
| PC Engines                 | 4         | 3.1%    |
| Gigabyte Technology        | 4         | 3.1%    |
| Apple                      | 4         | 3.1%    |
| BESSTAR Tech               | 3         | 2.33%   |
| ASRock                     | 3         | 2.33%   |
| ZOTAC                      | 2         | 1.55%   |
| Toshiba                    | 2         | 1.55%   |
| Pegatron                   | 2         | 1.55%   |
| Fujitsu                    | 2         | 1.55%   |
| AMI                        | 2         | 1.55%   |
| TUXEDO                     | 1         | 0.78%   |
| T-bao                      | 1         | 0.78%   |
| Supermicro                 | 1         | 0.78%   |
| Sun Microsystems           | 1         | 0.78%   |
| ShenZhen MinWin Technology | 1         | 0.78%   |
| Samsung Electronics        | 1         | 0.78%   |
| Raspberry Pi Foundation    | 1         | 0.78%   |
| Protectli                  | 1         | 0.78%   |
| Packard Bell               | 1         | 0.78%   |
| NF692                      | 1         | 0.78%   |
| MW                         | 1         | 0.78%   |
| IBM                        | 1         | 0.78%   |
| HARDKERNEL                 | 1         | 0.78%   |
| Foxconn                    | 1         | 0.78%   |
| eMachines                  | 1         | 0.78%   |
| Deciso                     | 1         | 0.78%   |
| AZW                        | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 7         | 5.43%   |
| PC Engines APU2                          | 3         | 2.33%   |
| Intel Q3XXG4-P V1.0                      | 3         | 2.33%   |
| BESSTAR Tech N40                         | 3         | 2.33%   |
| MSI MS-7B86                              | 2         | 1.55%   |
| HP Laptop 15-da0xxx                      | 2         | 1.55%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 1.55%   |
| ASUS M4A88TD-V EVO/USB3                  | 2         | 1.55%   |
| ASUS IP4BL-ME                            | 2         | 1.55%   |
| Apple MacBook4,1                         | 2         | 1.55%   |
| AMI Aptio CRB                            | 2         | 1.55%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO         | 1         | 0.78%   |
| ZOTAC ZBOX-CI323NANO                     | 1         | 0.78%   |
| TUXEDO N14xWU                            | 1         | 0.78%   |
| Toshiba Satellite C855-1U4               | 1         | 0.78%   |
| Toshiba PORTEGE M780                     | 1         | 0.78%   |
| T-bao MINI PC                            | 1         | 0.78%   |
| Supermicro X8STi                         | 1         | 0.78%   |
| Sun Microsystems Ultra 24                | 1         | 0.78%   |
| ShenZhen MinWin MW-NANO-APL-4L           | 1         | 0.78%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.78%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.78%   |
| Protectli FW4B                           | 1         | 0.78%   |
| Pegatron Pro 3405 Series                 | 1         | 0.78%   |
| Pegatron KX629AA-ABZ a6561.it            | 1         | 0.78%   |
| PC Engines APU3                          | 1         | 0.78%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 0.78%   |
| NF692 1.0                                | 1         | 0.78%   |
| MW GMLK-2_5G4L                           | 1         | 0.78%   |
| MSI NR074AA-ABZ CQ5125IT                 | 1         | 0.78%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159)  | 1         | 0.78%   |
| MSI GF65 Thin 10SER                      | 1         | 0.78%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CMS0FA00          | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 0.78%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 0.78%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 0.78%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 0.78%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 0.78%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 0.78%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 0.78%   |
| Lenovo ThinkCentre M83 10AHS35Q00        | 1         | 0.78%   |
| Lenovo G505 20240                        | 1         | 0.78%   |
| Lenovo G50-45 80E3                       | 1         | 0.78%   |
| Lenovo B590 62743PG                      | 1         | 0.78%   |
| Intel NUC6i5SYB H81131-503               | 1         | 0.78%   |
| Intel NUC5i5RYB H40999-502               | 1         | 0.78%   |
| Intel NUC10i7FNK                         | 1         | 0.78%   |
| Intel MAHOBAY                            | 1         | 0.78%   |
| Intel D945GCLF2                          | 1         | 0.78%   |
| Intel D2500CC AAG81477-401               | 1         | 0.78%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 0.78%   |
| HP Z440 Workstation                      | 1         | 0.78%   |
| HP xw8600 Workstation                    | 1         | 0.78%   |
| HP ProLiant MicroServer Gen8             | 1         | 0.78%   |
| HP ProBook 470 G4                        | 1         | 0.78%   |
| HP Mini 210-1000                         | 1         | 0.78%   |
| HP EliteBook 6930p                       | 1         | 0.78%   |
| HP Compaq Elite 8300 SFF                 | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 10        | 7.75%   |
| Unknown                        | 7         | 5.43%   |
| ASUS PRIME                     | 4         | 3.1%    |
| PC Engines APU2                | 3         | 2.33%   |
| Intel Q3XXG4-P                 | 3         | 2.33%   |
| Dell PowerEdge                 | 3         | 2.33%   |
| BESSTAR Tech N40               | 3         | 2.33%   |
| ASUS VivoBook                  | 3         | 2.33%   |
| Acer Aspire                    | 3         | 2.33%   |
| MSI MS-7B86                    | 2         | 1.55%   |
| HP Laptop                      | 2         | 1.55%   |
| HP Compaq                      | 2         | 1.55%   |
| Gigabyte X570                  | 2         | 1.55%   |
| Fujitsu ESPRIMO                | 2         | 1.55%   |
| Dell Precision                 | 2         | 1.55%   |
| Dell Inspiron                  | 2         | 1.55%   |
| ASUS M4A88TD-V                 | 2         | 1.55%   |
| ASUS IP4BL-ME                  | 2         | 1.55%   |
| Apple MacBook4                 | 2         | 1.55%   |
| AMI Aptio                      | 2         | 1.55%   |
| ZOTAC ZBOX-MI640               | 1         | 0.78%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.78%   |
| TUXEDO N14xWU                  | 1         | 0.78%   |
| Toshiba Satellite              | 1         | 0.78%   |
| Toshiba PORTEGE                | 1         | 0.78%   |
| T-bao MINI                     | 1         | 0.78%   |
| Supermicro X8STi               | 1         | 0.78%   |
| Sun Microsystems Ultra         | 1         | 0.78%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.78%   |
| Samsung 3570R                  | 1         | 0.78%   |
| RPi Raspberry                  | 1         | 0.78%   |
| Protectli FW4B                 | 1         | 0.78%   |
| Pegatron Pro                   | 1         | 0.78%   |
| Pegatron KX629AA-ABZ           | 1         | 0.78%   |
| PC Engines APU3                | 1         | 0.78%   |
| Packard Bell EasyNote          | 1         | 0.78%   |
| NF692 1.0                      | 1         | 0.78%   |
| MW GMLK-2                      | 1         | 0.78%   |
| MSI NR074AA-ABZ                | 1         | 0.78%   |
| MSI KBL-U                      | 1         | 0.78%   |
| MSI GF65                       | 1         | 0.78%   |
| Lenovo ThinkCentre             | 1         | 0.78%   |
| Lenovo G505                    | 1         | 0.78%   |
| Lenovo G50-45                  | 1         | 0.78%   |
| Lenovo B590                    | 1         | 0.78%   |
| Intel NUC6i5SYB                | 1         | 0.78%   |
| Intel NUC5i5RYB                | 1         | 0.78%   |
| Intel NUC10i7FNK               | 1         | 0.78%   |
| Intel MAHOBAY                  | 1         | 0.78%   |
| Intel D945GCLF2                | 1         | 0.78%   |
| Intel D2500CC                  | 1         | 0.78%   |
| IBM ThinkPad                   | 1         | 0.78%   |
| HP Z440                        | 1         | 0.78%   |
| HP xw8600                      | 1         | 0.78%   |
| HP ProLiant                    | 1         | 0.78%   |
| HP ProBook                     | 1         | 0.78%   |
| HP Mini                        | 1         | 0.78%   |
| HP EliteBook                   | 1         | 0.78%   |
| HARDKERNEL ODROID-H2           | 1         | 0.78%   |
| Gigabyte P55A-UD3              | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 14        | 10.85%  |
| 2016    | 14        | 10.85%  |
| 2021    | 10        | 7.75%   |
| 2011    | 10        | 7.75%   |
| 2010    | 10        | 7.75%   |
| 2020    | 9         | 6.98%   |
| 2018    | 9         | 6.98%   |
| 2013    | 9         | 6.98%   |
| 2012    | 8         | 6.2%    |
| 2008    | 8         | 6.2%    |
| 2014    | 7         | 5.43%   |
| 2009    | 7         | 5.43%   |
| 2015    | 4         | 3.1%    |
| 2017    | 3         | 2.33%   |
| 2022    | 2         | 1.55%   |
| 2007    | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 2006    | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 66        | 51.16%  |
| Notebook       | 48        | 37.21%  |
| Mini pc        | 10        | 7.75%   |
| Server         | 3         | 2.33%   |
| System on chip | 1         | 0.78%   |
| All in one     | 1         | 0.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 125       | 96.9%   |
| Yes  | 4         | 3.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 47        | 35.88%  |
| 4.01-8.0    | 41        | 31.3%   |
| 16.01-24.0  | 15        | 11.45%  |
| 2.01-3.0    | 10        | 7.63%   |
| 32.01-64.0  | 8         | 6.11%   |
| 24.01-32.0  | 3         | 2.29%   |
| 64.01-256.0 | 3         | 2.29%   |
| 3.01-4.0    | 2         | 1.53%   |
| 0.51-1.0    | 1         | 0.76%   |
| 0.01-0.5    | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 83        | 62.41%  |
| 0.51-1.0   | 26        | 19.55%  |
| 1.01-2.0   | 7         | 5.26%   |
| Unknown    | 6         | 4.51%   |
| 2.01-3.0   | 5         | 3.76%   |
| 4.01-8.0   | 4         | 3.01%   |
| 24.01-32.0 | 1         | 0.75%   |
| 8.01-16.0  | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 58.65%  |
| 2      | 29        | 21.8%   |
| 0      | 10        | 7.52%   |
| 4      | 6         | 4.51%   |
| 3      | 6         | 4.51%   |
| 10     | 1         | 0.75%   |
| 9      | 1         | 0.75%   |
| 7      | 1         | 0.75%   |
| 6      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 66.92%  |
| Yes       | 43        | 33.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 93.8%   |
| No        | 8         | 6.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 51.94%  |
| No        | 62        | 48.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 66.41%  |
| Yes       | 44        | 33.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 129       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Milan                    | 20        | 13.51%  |
| Rome                     | 17        | 11.49%  |
| Turin                    | 5         | 3.38%   |
| Bologna                  | 5         | 3.38%   |
| Trieste                  | 3         | 2.03%   |
| Naples                   | 3         | 2.03%   |
| Venice                   | 2         | 1.35%   |
| Turrivalignani           | 2         | 1.35%   |
| Silea                    | 2         | 1.35%   |
| Padova                   | 2         | 1.35%   |
| Monterotondo             | 2         | 1.35%   |
| Lucca                    | 2         | 1.35%   |
| Catania                  | 2         | 1.35%   |
| Brescia                  | 2         | 1.35%   |
| Adelfia                  | 2         | 1.35%   |
| Viterbo                  | 1         | 0.68%   |
| Vigonovo                 | 1         | 0.68%   |
| Udine                    | 1         | 0.68%   |
| Treviso                  | 1         | 0.68%   |
| Terni                    | 1         | 0.68%   |
| Soresina                 | 1         | 0.68%   |
| Solarino                 | 1         | 0.68%   |
| Sasso Marconi            | 1         | 0.68%   |
| Saronno                  | 1         | 0.68%   |
| Sannicandro di Bari      | 1         | 0.68%   |
| San Fior                 | 1         | 0.68%   |
| San Donato Milanese      | 1         | 0.68%   |
| Roncade                  | 1         | 0.68%   |
| Rho                      | 1         | 0.68%   |
| Resana                   | 1         | 0.68%   |
| Reggio Emilia            | 1         | 0.68%   |
| Ravenna                  | 1         | 0.68%   |
| Ragusa                   | 1         | 0.68%   |
| Prato                    | 1         | 0.68%   |
| Ponsacco                 | 1         | 0.68%   |
| Pistoia                  | 1         | 0.68%   |
| Piovene Rocchette        | 1         | 0.68%   |
| Pioltello                | 1         | 0.68%   |
| Passignano sul Trasimeno | 1         | 0.68%   |
| Parma                    | 1         | 0.68%   |
| Palermo                  | 1         | 0.68%   |
| Ortona                   | 1         | 0.68%   |
| Oleggio                  | 1         | 0.68%   |
| Nughedu San Nicolo       | 1         | 0.68%   |
| Monza                    | 1         | 0.68%   |
| Monteleone di Fermo      | 1         | 0.68%   |
| Modena                   | 1         | 0.68%   |
| Mestrino                 | 1         | 0.68%   |
| Massa Lombarda           | 1         | 0.68%   |
| Malo                     | 1         | 0.68%   |
| Malnate                  | 1         | 0.68%   |
| Macerata                 | 1         | 0.68%   |
| Lurago Marinone          | 1         | 0.68%   |
| Lissone                  | 1         | 0.68%   |
| Grottazzolina            | 1         | 0.68%   |
| Gorgonzola               | 1         | 0.68%   |
| Gianico                  | 1         | 0.68%   |
| Genzano di Roma          | 1         | 0.68%   |
| Gemona                   | 1         | 0.68%   |
| Galliera Veneta          | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 50     | 16.67%  |
| Samsung Electronics | 23        | 40     | 13.69%  |
| Seagate             | 19        | 42     | 11.31%  |
| Crucial             | 17        | 26     | 10.12%  |
| Toshiba             | 11        | 27     | 6.55%   |
| Kingston            | 9         | 10     | 5.36%   |
| Transcend           | 8         | 9      | 4.76%   |
| SanDisk             | 7         | 7      | 4.17%   |
| Hitachi             | 5         | 7      | 2.98%   |
| Micron Technology   | 3         | 3      | 1.79%   |
| KingSpec            | 3         | 4      | 1.79%   |
| Intel               | 3         | 4      | 1.79%   |
| EMTEC               | 3         | 4      | 1.79%   |
| PNY                 | 2         | 5      | 1.19%   |
| Phison              | 2         | 2      | 1.19%   |
| OCZ                 | 2         | 2      | 1.19%   |
| Maxtor              | 2         | 2      | 1.19%   |
| Leven               | 2         | 2      | 1.19%   |
| Hoodisk             | 2         | 2      | 1.19%   |
| Dogfish             | 2         | 2      | 1.19%   |
| China               | 2         | 2      | 1.19%   |
| Union Memory        | 1         | 1      | 0.6%    |
| SK hynix            | 1         | 1      | 0.6%    |
| Silicon Motion      | 1         | 2      | 0.6%    |
| NVMe                | 1         | 1      | 0.6%    |
| KingDian            | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| HGST                | 1         | 1      | 0.6%    |
| Fujitsu             | 1         | 1      | 0.6%    |
| FORESEE             | 1         | 2      | 0.6%    |
| Corsair             | 1         | 2      | 0.6%    |
| ASUSTek Computer    | 1         | 2      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |
| A-DATA Technology   | 1         | 2      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB                       | 4         | 2.14%   |
| Crucial CT240BX500SSD1 240GB                    | 4         | 2.14%   |
| Samsung SSD 850 EVO 500GB                       | 3         | 1.6%    |
| Samsung SSD 850 EVO 250GB                       | 3         | 1.6%    |
| EMTEC X150 120GB                                | 3         | 1.6%    |
| Crucial CT500MX500SSD1 500GB                    | 3         | 1.6%    |
| WDC WDS240G2G0A-00JH30 240GB                    | 2         | 1.07%   |
| WDC WD5000AAKS-22V1A0 500GB                     | 2         | 1.07%   |
| Transcend TS256GMTS430S 256GB                   | 2         | 1.07%   |
| Toshiba MQ04ABF100 1TB                          | 2         | 1.07%   |
| Toshiba DT01ACA050 500GB                        | 2         | 1.07%   |
| Seagate ST320LT007-9ZV142 320GB                 | 2         | 1.07%   |
| Seagate ST1000DM003-1ER162 1TB                  | 2         | 1.07%   |
| Samsung SSD 970 EVO 250GB                       | 2         | 1.07%   |
| Samsung HM321HI 320GB                           | 2         | 1.07%   |
| Phison SATA SSD 16GB                            | 2         | 1.07%   |
| Kingston SA400S37240G 240GB                     | 2         | 1.07%   |
| Kingston SA400S37120G 120GB                     | 2         | 1.07%   |
| KingSpec Q-720 720GB                            | 2         | 1.07%   |
| Crucial CT250MX500SSD1 250GB                    | 2         | 1.07%   |
| Crucial CT120BX500SSD1 120GB                    | 2         | 1.07%   |
| WDC WDS250G1B0A-00H9H0 250GB                    | 1         | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB                    | 1         | 0.53%   |
| WDC WDS100T2B0B-00YS70 1TB                      | 1         | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB                      | 1         | 0.53%   |
| WDC WD6400AAKS-65A7B0 640GB                     | 1         | 0.53%   |
| WDC WD5003ABYX-01WERA2 500GB                    | 1         | 0.53%   |
| WDC WD5000LPVT-80G33T2 500GB                    | 1         | 0.53%   |
| WDC WD5000BPKX-00HPJT0 500GB                    | 1         | 0.53%   |
| WDC WD5000BPKT-00PK4T0 500GB                    | 1         | 0.53%   |
| WDC WD5000BMVV-11A1CS0 500GB                    | 1         | 0.53%   |
| WDC WD5000BEVT-00A03T0 500GB                    | 1         | 0.53%   |
| WDC WD5000AAKX-75U6AA0 500GB                    | 1         | 0.53%   |
| WDC WD5000AAKX-00ERMA0 500GB                    | 1         | 0.53%   |
| WDC WD5000AAKS-00E4A0 500GB                     | 1         | 0.53%   |
| WDC WD5000AAKS-00D2B0 500GB                     | 1         | 0.53%   |
| WDC WD40NMZW-11GX6S1 4TB                        | 1         | 0.53%   |
| WDC WD40EFRX-68WT0N0 4TB                        | 1         | 0.53%   |
| WDC WD40EFRX-68N32N0 4TB                        | 1         | 0.53%   |
| WDC WD3200BEKX-60B7WT0 320GB                    | 1         | 0.53%   |
| WDC WD3200AAKS-00L9A0 320GB                     | 1         | 0.53%   |
| WDC WD30EZRZ-00Z5HB0 3TB                        | 1         | 0.53%   |
| WDC WD30EZRZ-00GXCB0 3TB                        | 1         | 0.53%   |
| WDC WD2500LPCX-24C6HT0 250GB                    | 1         | 0.53%   |
| WDC WD2500BEVT-22A23T0 250GB                    | 1         | 0.53%   |
| WDC WD2500BEVS-22UST0 250GB                     | 1         | 0.53%   |
| WDC WD2500AAJS-07M0A0 250GB                     | 1         | 0.53%   |
| WDC WD20PURZ-85GU6Y0 2TB                        | 1         | 0.53%   |
| WDC WD20EVDS-63T3B0 2TB                         | 1         | 0.53%   |
| WDC WD2002FYPS-01U1B1 2TB                       | 1         | 0.53%   |
| WDC WD15EADS-00P8B0 1.5TB                       | 1         | 0.53%   |
| WDC WD1500HLFS-01G6U0 150GB                     | 1         | 0.53%   |
| WDC WD10SDZW-11UMGS0 1TB                        | 1         | 0.53%   |
| WDC WD10EFRX-68PJCN0 1TB                        | 1         | 0.53%   |
| WDC WD1000DHTZ-04N21V1 1TB                      | 1         | 0.53%   |
| Union Memory UMIS LENSE40512GMSP34MESTB3A 512GB | 1         | 0.53%   |
| Transcend TS64GSSD370S 64GB                     | 1         | 0.53%   |
| Transcend TS64GMSA370 64GB                      | 1         | 0.53%   |
| Transcend TS32GSSD370 32GB                      | 1         | 0.53%   |
| Transcend TS256GMTE652T2 256GB                  | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 44     | 36.51%  |
| Seagate             | 19        | 42     | 30.16%  |
| Toshiba             | 9         | 23     | 14.29%  |
| Hitachi             | 5         | 7      | 7.94%   |
| Samsung Electronics | 3         | 3      | 4.76%   |
| Maxtor              | 2         | 2      | 3.17%   |
| HGST                | 1         | 1      | 1.59%   |
| Fujitsu             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 32     | 17.89%  |
| Crucial             | 16        | 25     | 16.84%  |
| Transcend           | 7         | 8      | 7.37%   |
| SanDisk             | 7         | 7      | 7.37%   |
| WDC                 | 6         | 6      | 6.32%   |
| Kingston            | 6         | 6      | 6.32%   |
| KingSpec            | 3         | 4      | 3.16%   |
| Intel               | 3         | 4      | 3.16%   |
| EMTEC               | 3         | 4      | 3.16%   |
| Toshiba             | 2         | 4      | 2.11%   |
| PNY                 | 2         | 5      | 2.11%   |
| Phison              | 2         | 2      | 2.11%   |
| OCZ                 | 2         | 2      | 2.11%   |
| Micron Technology   | 2         | 2      | 2.11%   |
| Leven               | 2         | 2      | 2.11%   |
| Hoodisk             | 2         | 2      | 2.11%   |
| Dogfish             | 2         | 2      | 2.11%   |
| China               | 2         | 2      | 2.11%   |
| SK hynix            | 1         | 1      | 1.05%   |
| NVMe                | 1         | 1      | 1.05%   |
| KingDian            | 1         | 1      | 1.05%   |
| Intenso             | 1         | 1      | 1.05%   |
| FORESEE             | 1         | 2      | 1.05%   |
| Corsair             | 1         | 2      | 1.05%   |
| ASUSTek Computer    | 1         | 2      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |
| A-DATA Technology   | 1         | 2      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 78        | 132    | 56.12%  |
| HDD  | 48        | 123    | 34.53%  |
| NVMe | 13        | 15     | 9.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 255    | 89.52%  |
| NVMe | 13        | 15     | 10.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 96        | 171    | 73.85%  |
| 0.51-1.0   | 20        | 55     | 15.38%  |
| 1.01-2.0   | 7         | 9      | 5.38%   |
| 3.01-4.0   | 4         | 7      | 3.08%   |
| 2.01-3.0   | 2         | 5      | 1.54%   |
| 10.01-20.0 | 1         | 8      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 42        | 31.82%  |
| 101-250        | 32        | 24.24%  |
| 251-500        | 21        | 15.91%  |
| 21-50          | 14        | 10.61%  |
| 51-100         | 10        | 7.58%   |
| 501-1000       | 9         | 6.82%   |
| More than 3000 | 3         | 2.27%   |
| Unknown        | 1         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 116       | 87.22%  |
| 21-50          | 10        | 7.52%   |
| 51-100         | 2         | 1.5%    |
| More than 3000 | 1         | 0.75%   |
| 101-250        | 1         | 0.75%   |
| 1001-2000      | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2         | 2      | 8%      |
| Seagate ST320LT007-9ZV142 320GB   | 2         | 2      | 8%      |
| WDC WD5000AAKX-75U6AA0 500GB      | 1         | 1      | 4%      |
| WDC WD5000AAKS-00E4A0 500GB       | 1         | 1      | 4%      |
| WDC WD20EVDS-63T3B0 2TB           | 1         | 1      | 4%      |
| WDC WD2002FYPS-01U1B1 2TB         | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 4%      |
| Seagate ST9160821AS 160GB         | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 4%      |
| Seagate ST500DM002-1BD142 500GB   | 1         | 3      | 4%      |
| Seagate ST4000LM024-2AN17V 4TB    | 1         | 1      | 4%      |
| Seagate ST31500341AS 1.5TB        | 1         | 1      | 4%      |
| SanDisk SDSSDP064G 64GB           | 1         | 1      | 4%      |
| SanDisk SD9SN8W-128G-1006 128GB   | 1         | 1      | 4%      |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 4%      |
| OCZ VERTEX3 120GB                 | 1         | 1      | 4%      |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 4%      |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2      | 4%      |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 4%      |
| Hitachi HDS723030ALA640 3TB       | 1         | 2      | 4%      |
| Crucial CT525MX300SSD1 528GB      | 1         | 3      | 4%      |
| China SATA3 240GB SSD             | 1         | 1      | 4%      |
| A-DATA Technology SX300 128GB     | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 28%     |
| WDC                 | 6         | 6      | 24%     |
| Hitachi             | 3         | 5      | 12%     |
| SanDisk             | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| OCZ                 | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Crucial             | 1         | 3      | 4%      |
| China               | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 38.89%  |
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
| HDD  | 16        | 22     | 69.57%  |
| SSD  | 7         | 9      | 30.43%  |

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
| Works    | 103       | 223    | 78.03%  |
| Malfunc  | 23        | 31     | 17.42%  |
| Detected | 6         | 16     | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 94        | 62.67%  |
| AMD                              | 23        | 15.33%  |
| Samsung Electronics              | 7         | 4.67%   |
| Broadcom / LSI                   | 4         | 2.67%   |
| Marvell Technology Group         | 3         | 2%      |
| Kingston Technology Company      | 3         | 2%      |
| VIA Technologies                 | 2         | 1.33%   |
| Silicon Integrated Systems [SiS] | 2         | 1.33%   |
| JMicron Technology               | 2         | 1.33%   |
| ASMedia Technology               | 2         | 1.33%   |
| Union Memory (Shenzhen)          | 1         | 0.67%   |
| Silicon Motion                   | 1         | 0.67%   |
| Nvidia                           | 1         | 0.67%   |
| Micron/Crucial Technology        | 1         | 0.67%   |
| Micron Technology                | 1         | 0.67%   |
| Integrated Technology Express    | 1         | 0.67%   |
| Adaptec                          | 1         | 0.67%   |
| Unknown                          | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 9.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 3.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.95%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 3.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 3.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 5         | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 2.26%   |
| Unknown                                                                          | 4         | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.69%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.69%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.69%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2         | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.13%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.56%   |
| Samsung SM951 AHCI                                                               | 1         | 0.56%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.56%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.56%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.56%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.56%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.56%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.56%   |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.56%   |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.56%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.56%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.56%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.56%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.56%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 0.56%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 0.56%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.56%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.56%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1         | 0.56%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                       | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 65.1%   |
| IDE  | 28        | 18.79%  |
| NVMe | 14        | 9.4%    |
| RAID | 7         | 4.7%    |
| SCSI | 3         | 2.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 101       | 78.29%  |
| AMD      | 25        | 19.38%  |
| Broadcom | 1         | 0.78%   |
| Arm      | 1         | 0.78%   |
| Unknown  | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                              | 4         | 3.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.31%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 2.31%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.54%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.54%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 1.54%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.54%   |
| AMD Phenom II X4 965 Processor                | 2         | 1.54%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz         | 1         | 0.77%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.77%   |
| Intel Xeon CPU X3470 @ 2.93GHz                | 1         | 0.77%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1         | 0.77%   |
| Intel Xeon CPU E5440 @ 2.83GHz                | 1         | 0.77%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.77%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1         | 0.77%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1         | 0.77%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.77%   |
| Intel Xeon CPU E3113 @ 3.00GHz                | 1         | 0.77%   |
| Intel Pentium M processor                     | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E6600             | 1         | 0.77%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.77%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.77%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.77%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 0.77%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.77%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1         | 0.77%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.77%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 0.77%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.77%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.77%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.77%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 0.77%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.77%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.77%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.77%   |
| Intel Core i5-6260U CPU @ 1.80GHz             | 1         | 0.77%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.77%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.77%   |
| Intel Core i5-4210Y CPU @ 1.50GHz             | 1         | 0.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.77%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 0.77%   |
| Intel Core i5 CPU                             | 1         | 0.77%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 0.77%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 16.15%  |
| Intel Celeron           | 18        | 13.85%  |
| Intel Core i7           | 12        | 9.23%   |
| Intel Core i3           | 10        | 7.69%   |
| Intel Xeon              | 9         | 6.92%   |
| Intel Core 2 Duo        | 8         | 6.15%   |
| Intel Atom              | 7         | 5.38%   |
| Intel Pentium           | 6         | 4.62%   |
| AMD Ryzen 5             | 6         | 4.62%   |
| AMD GX                  | 4         | 3.08%   |
| Other                   | 3         | 2.31%   |
| Intel Pentium Dual-Core | 3         | 2.31%   |
| Intel Pentium Dual      | 3         | 2.31%   |
| AMD Ryzen 7             | 2         | 1.54%   |
| AMD Phenom II X4        | 2         | 1.54%   |
| Intel Xeon Silver       | 1         | 0.77%   |
| Intel Pentium M         | 1         | 0.77%   |
| Intel Core 2 Quad       | 1         | 0.77%   |
| Intel Core 2 Extreme    | 1         | 0.77%   |
| Intel 686-class         | 1         | 0.77%   |
| AMD Turion 64 X2 Mobile | 1         | 0.77%   |
| AMD Ryzen Embedded      | 1         | 0.77%   |
| AMD Ryzen 9             | 1         | 0.77%   |
| AMD Ryzen 7 PRO         | 1         | 0.77%   |
| AMD Ryzen 3             | 1         | 0.77%   |
| AMD FX                  | 1         | 0.77%   |
| AMD E2                  | 1         | 0.77%   |
| AMD E1                  | 1         | 0.77%   |
| AMD Athlon II X4        | 1         | 0.77%   |
| AMD A6                  | 1         | 0.77%   |
| AMD A4                  | 1         | 0.77%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 56        | 43.08%  |
| 4       | 38        | 29.23%  |
| Unknown | 16        | 12.31%  |
| 12      | 6         | 4.62%   |
| 8       | 6         | 4.62%   |
| 1       | 3         | 2.31%   |
| 16      | 2         | 1.54%   |
| 6       | 2         | 1.54%   |
| 32      | 1         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 121       | 93.08%  |
| 2       | 5         | 3.85%   |
| Unknown | 4         | 3.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 60        | 46.15%  |
| 2       | 54        | 41.54%  |
| Unknown | 16        | 12.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 13        | 10%     |
| SandyBridge   | 11        | 8.46%   |
| KabyLake      | 10        | 7.69%   |
| IvyBridge     | 9         | 6.92%   |
| Haswell       | 9         | 6.92%   |
| Bonnell       | 7         | 5.38%   |
| Silvermont    | 6         | 4.62%   |
| Goldmont plus | 6         | 4.62%   |
| Broadwell     | 6         | 4.62%   |
| Zen+          | 5         | 3.85%   |
| Westmere      | 5         | 3.85%   |
| Puma          | 5         | 3.85%   |
| Core          | 5         | 3.85%   |
| Unknown       | 5         | 3.85%   |
| Skylake       | 4         | 3.08%   |
| Nehalem       | 3         | 2.31%   |
| K10           | 3         | 2.31%   |
| Goldmont      | 3         | 2.31%   |
| CometLake     | 3         | 2.31%   |
| Zen 3         | 2         | 1.54%   |
| Zen 2         | 2         | 1.54%   |
| Zen           | 2         | 1.54%   |
| Jaguar        | 2         | 1.54%   |
| Piledriver    | 1         | 0.77%   |
| P6            | 1         | 0.77%   |
| K8 Hammer     | 1         | 0.77%   |
| K10 Llano     | 1         | 0.77%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 76        | 58.91%  |
| AMD                              | 29        | 22.48%  |
| Nvidia                           | 20        | 15.5%   |
| Matrox Electronics Systems       | 3         | 2.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 4.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 3.76%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.01%   |
| Intel HD Graphics 620                                                                    | 4         | 3.01%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 3.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 3.01%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4         | 3.01%   |
| Intel HD Graphics 6000                                                                   | 3         | 2.26%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.26%   |
| Intel HD Graphics 500                                                                    | 3         | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.26%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.5%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.5%    |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 1.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.5%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.75%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.75%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.75%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.75%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.75%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.75%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1         | 0.75%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.75%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1         | 0.75%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.75%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.75%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.75%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.75%   |
| Intel Iris Graphics 540                                                                  | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 530                                                                    | 1         | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.75%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.75%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.75%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1         | 0.75%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 47.69%  |
| 1 x AMD        | 27        | 20.77%  |
| 1 x Nvidia     | 14        | 10.77%  |
| Other          | 8         | 6.15%   |
| 2 x Intel      | 7         | 5.38%   |
| Intel + Nvidia | 6         | 4.62%   |
| 1 x Matrox     | 3         | 2.31%   |
| 2 x AMD        | 1         | 0.77%   |
| 1 x SiS        | 1         | 0.77%   |
| Intel + AMD    | 1         | 0.77%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 106       | 80.3%   |
| Proprietary | 13        | 9.85%   |
| Unknown     | 13        | 9.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 76.34%  |
| 0.01-0.5   | 10        | 7.63%   |
| 1.01-2.0   | 9         | 6.87%   |
| 3.01-4.0   | 6         | 4.58%   |
| 0.51-1.0   | 4         | 3.05%   |
| 7.01-8.0   | 1         | 0.76%   |
| 5.01-6.0   | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 11        | 14.67%  |
| Samsung Electronics  | 9         | 12%     |
| LG Display           | 7         | 9.33%   |
| Acer                 | 6         | 8%      |
| Philips              | 5         | 6.67%   |
| BOE                  | 5         | 6.67%   |
| Hewlett-Packard      | 4         | 5.33%   |
| Chimei Innolux       | 4         | 5.33%   |
| Apple                | 4         | 5.33%   |
| Dell                 | 3         | 4%      |
| Lenovo               | 2         | 2.67%   |
| HannStar             | 2         | 2.67%   |
| Goldstar             | 2         | 2.67%   |
| ___                  | 1         | 1.33%   |
| Sony                 | 1         | 1.33%   |
| Packard Bell         | 1         | 1.33%   |
| Orion                | 1         | 1.33%   |
| LG Philips           | 1         | 1.33%   |
| LG Electronics       | 1         | 1.33%   |
| Iiyama               | 1         | 1.33%   |
| Fujitsu Siemens      | 1         | 1.33%   |
| Eizo                 | 1         | 1.33%   |
| ASUSTek Computer     | 1         | 1.33%   |
| Ancor Communications | 1         | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 3         | 4%      |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 2         | 2.67%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                      | 2         | 2.67%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.33%   |
| Sony TV SNY5D01 1360x768                                             | 1         | 1.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 1.33%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 1.33%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                     | 1         | 1.33%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 1.33%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1         | 1.33%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch             | 1         | 1.33%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch             | 1         | 1.33%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch       | 1         | 1.33%   |
| Orion LCD Monitor ORN1207 1920x1080                                  | 1         | 1.33%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.33%   |
| LG Electronics LCD Monitor E2360 1920x1080                           | 1         | 1.33%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 1.33%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.33%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 1.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 1.33%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 1.33%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1         | 1.33%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch    | 1         | 1.33%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch            | 1         | 1.33%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 1.33%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch           | 1         | 1.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 1.33%   |
| HannStar HSG1233 HSP0018 1920x1080 520x290mm 23.4-inch               | 1         | 1.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 1         | 1.33%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch          | 1         | 1.33%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 1.33%   |
| Eizo LCD Monitor S1901 1280x1024                                     | 1         | 1.33%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1         | 1.33%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                    | 1         | 1.33%   |
| Dell 2007FP DELA021 1600x1200 410x310mm 20.2-inch                    | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 1.33%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.33%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 1.33%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 1.33%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 1.33%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                 | 1         | 1.33%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 1         | 1.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch        | 1         | 1.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 30        | 42.25%  |
| 1366x768 (WXGA)   | 19        | 26.76%  |
| 1440x900 (WXGA+)  | 4         | 5.63%   |
| 1600x900 (HD+)    | 3         | 4.23%   |
| 1280x1024 (SXGA)  | 3         | 4.23%   |
| 1920x1200 (WUXGA) | 2         | 2.82%   |
| 1280x800 (WXGA)   | 2         | 2.82%   |
| 1024x600          | 2         | 2.82%   |
| 3840x2160 (4K)    | 1         | 1.41%   |
| 2560x1440 (QHD)   | 1         | 1.41%   |
| 2560x1080         | 1         | 1.41%   |
| 1600x1200         | 1         | 1.41%   |
| 1360x768          | 1         | 1.41%   |
| 1024x768 (XGA)    | 1         | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 20        | 26.67%  |
| 13      | 9         | 12%     |
| Unknown | 8         | 10.67%  |
| 24      | 5         | 6.67%   |
| 23      | 5         | 6.67%   |
| 21      | 5         | 6.67%   |
| 27      | 4         | 5.33%   |
| 19      | 4         | 5.33%   |
| 31      | 2         | 2.67%   |
| 28      | 2         | 2.67%   |
| 18      | 2         | 2.67%   |
| 12      | 2         | 2.67%   |
| 10      | 2         | 2.67%   |
| 22      | 1         | 1.33%   |
| 20      | 1         | 1.33%   |
| 17      | 1         | 1.33%   |
| 14      | 1         | 1.33%   |
| 11      | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 36.99%  |
| 501-600     | 12        | 16.44%  |
| 401-500     | 8         | 10.96%  |
| 201-300     | 8         | 10.96%  |
| Unknown     | 8         | 10.96%  |
| 601-700     | 5         | 6.85%   |
| 351-400     | 5         | 6.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 77.94%  |
| 16/10   | 8         | 11.76%  |
| 5/4     | 2         | 2.94%   |
| 4/3     | 2         | 2.94%   |
| Unknown | 2         | 2.94%   |
| 21/9    | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 13        | 18.06%  |
| 201-250        | 12        | 16.67%  |
| 81-90          | 9         | 12.5%   |
| 101-110        | 8         | 11.11%  |
| Unknown        | 8         | 11.11%  |
| 151-200        | 6         | 8.33%   |
| 301-350        | 4         | 5.56%   |
| 351-500        | 3         | 4.17%   |
| 251-300        | 3         | 4.17%   |
| 61-70          | 2         | 2.78%   |
| 41-50          | 2         | 2.78%   |
| 51-60          | 1         | 1.39%   |
| 121-130        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 27        | 38.03%  |
| 101-120 | 23        | 32.39%  |
| 121-160 | 12        | 16.9%   |
| Unknown | 8         | 11.27%  |
| 161-240 | 1         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 67        | 50.38%  |
| 0     | 61        | 45.86%  |
| 2     | 5         | 3.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 71        | 39.01%  |
| Realtek Semiconductor            | 53        | 29.12%  |
| Qualcomm Atheros                 | 22        | 12.09%  |
| Broadcom                         | 15        | 8.24%   |
| Ralink Technology                | 2         | 1.1%    |
| Ralink                           | 2         | 1.1%    |
| Marvell Technology Group         | 2         | 1.1%    |
| Huawei Technologies              | 2         | 1.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Samsung Electronics              | 1         | 0.55%   |
| OPPO Electronics                 | 1         | 0.55%   |
| Nvidia                           | 1         | 0.55%   |
| NetGear                          | 1         | 0.55%   |
| JMicron Technology               | 1         | 0.55%   |
| IMC Networks                     | 1         | 0.55%   |
| Hewlett-Packard                  | 1         | 0.55%   |
| Edimax Technology                | 1         | 0.55%   |
| Digital Equipment                | 1         | 0.55%   |
| Davicom Semiconductor            | 1         | 0.55%   |
| Apple                            | 1         | 0.55%   |
| AMD                              | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 44        | 19.73%  |
| Intel I211 Gigabit Network Connection                                                 | 15        | 6.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 2.24%   |
| Intel Wireless 7265                                                                   | 5         | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5         | 2.24%   |
| Intel 82574L Gigabit Network Connection                                               | 5         | 2.24%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.79%   |
| Intel I210 Gigabit Network Connection                                                 | 4         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 3         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 3         | 1.35%   |
| Intel Wireless 8260                                                                   | 3         | 1.35%   |
| Intel Wireless 3165                                                                   | 3         | 1.35%   |
| Intel 82579V Gigabit Network Connection                                               | 3         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 0.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 0.9%    |
| Intel Wireless 7260                                                                   | 2         | 0.9%    |
| Intel I350 Gigabit Network Connection                                                 | 2         | 0.9%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                         | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                                 | 2         | 0.9%    |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 0.9%    |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                         | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.45%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.45%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.45%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.45%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.45%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.45%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 0.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1         | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.45%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data                       | 1         | 0.45%   |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.45%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                                | 1         | 0.45%   |
| Intel Wireless-AC 9260                                                                | 1         | 0.45%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.45%   |
| Intel Ultimate N WiFi Link 5300                                                       | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 35.62%  |
| Qualcomm Atheros      | 21        | 28.77%  |
| Realtek Semiconductor | 12        | 16.44%  |
| Broadcom              | 7         | 9.59%   |
| Ralink Technology     | 2         | 2.74%   |
| Ralink                | 2         | 2.74%   |
| NetGear               | 1         | 1.37%   |
| IMC Networks          | 1         | 1.37%   |
| Edimax Technology     | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 6.67%   |
| Intel Wireless 7265                                                                   | 5         | 6.67%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 4%      |
| Intel Wireless 8260                                                                   | 3         | 4%      |
| Intel Wireless 3165                                                                   | 3         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 2.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 2.67%   |
| Intel Wireless 7260                                                                   | 2         | 2.67%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 2.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 2.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.33%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 1.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.33%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.33%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 1.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.33%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.33%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.33%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 1.33%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.33%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                                       | 1         | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.33%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.33%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1         | 1.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1         | 1.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 59        | 43.7%   |
| Realtek Semiconductor            | 49        | 36.3%   |
| Broadcom                         | 9         | 6.67%   |
| Qualcomm Atheros                 | 7         | 5.19%   |
| Marvell Technology Group         | 2         | 1.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Samsung Electronics              | 1         | 0.74%   |
| OPPO Electronics                 | 1         | 0.74%   |
| Nvidia                           | 1         | 0.74%   |
| JMicron Technology               | 1         | 0.74%   |
| Digital Equipment                | 1         | 0.74%   |
| Davicom Semiconductor            | 1         | 0.74%   |
| Apple                            | 1         | 0.74%   |
| AMD                              | 1         | 0.74%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 44        | 30.56%  |
| Intel I211 Gigabit Network Connection                                         | 15        | 10.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 3.47%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.47%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 2.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 2.08%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 2.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 1.39%   |
| Intel I350 Gigabit Network Connection                                         | 2         | 1.39%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 1         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.69%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data               | 1         | 0.69%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.69%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.69%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.69%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.69%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.69%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.69%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.69%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                            | 1         | 0.69%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.69%   |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 0.69%   |
| Intel 82577LC Gigabit Network Connection                                      | 1         | 0.69%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.69%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 0.69%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.69%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 0.69%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.69%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1         | 0.69%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.69%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.69%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 0.69%   |
| Digital Equipment DECchip 21142/43                                            | 1         | 0.69%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1         | 0.69%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.69%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.69%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.69%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 121       | 63.02%  |
| WiFi     | 67        | 34.9%   |
| Modem    | 3         | 1.56%   |
| Unknown  | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 111       | 72.08%  |
| WiFi     | 43        | 27.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 48.84%  |
| 1     | 29        | 22.48%  |
| 3     | 13        | 10.08%  |
| 4     | 10        | 7.75%   |
| 5     | 5         | 3.88%   |
| 0     | 3         | 2.33%   |
| 8     | 2         | 1.55%   |
| 7     | 2         | 1.55%   |
| 6     | 2         | 1.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 36.96%  |
| Realtek Semiconductor           | 4         | 8.7%    |
| Qualcomm Atheros Communications | 4         | 8.7%    |
| IMC Networks                    | 4         | 8.7%    |
| Cambridge Silicon Radio         | 4         | 8.7%    |
| Apple                           | 3         | 6.52%   |
| Lite-On Technology              | 2         | 4.35%   |
| Integrated System Solution      | 2         | 4.35%   |
| Broadcom                        | 2         | 4.35%   |
| Toshiba                         | 1         | 2.17%   |
| Hewlett-Packard                 | 1         | 2.17%   |
| Foxconn / Hon Hai               | 1         | 2.17%   |
| ASUSTek Computer                | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 28.26%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 8.7%    |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 4.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 4.35%   |
| Intel AX201 Bluetooth                                       | 2         | 4.35%   |
| Integrated System Solution Bluetooth Device                 | 2         | 4.35%   |
| IMC Networks Bluetooth Radio                                | 2         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 4.35%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 2.17%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 2.17%   |
| Realtek  Bluetooth Adapter                                  | 1         | 2.17%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2.17%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 2.17%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2.17%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2.17%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 2.17%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 2.17%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2.17%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 62.59%  |
| AMD                              | 30        | 21.58%  |
| Nvidia                           | 15        | 10.79%  |
| Silicon Integrated Systems [SiS] | 2         | 1.44%   |
| Logitech                         | 2         | 1.44%   |
| C-Media Electronics              | 2         | 1.44%   |
| Bose                             | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 6.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 5.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.98%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.98%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 2.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.19%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.19%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.6%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.6%    |
| Logitech Headset H340                                                                             | 1         | 0.6%    |
| Logitech HD Webcam C510                                                                           | 1         | 0.6%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.6%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.6%    |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.6%    |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.6%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.6%    |
| C-Media Electronics Audio Adapter (Planet UP-100, Genius G-Talk)                                  | 1         | 0.6%    |
| Bose Bose USB Audio                                                                               | 1         | 0.6%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.6%    |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.6%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 20.14%  |
| Unknown             | 24        | 17.27%  |
| Kingston            | 21        | 15.11%  |
| SK hynix            | 18        | 12.95%  |
| Crucial             | 10        | 7.19%   |
| Micron Technology   | 9         | 6.47%   |
| Unknown (ABCD)      | 5         | 3.6%    |
| Nanya Technology    | 4         | 2.88%   |
| Corsair             | 4         | 2.88%   |
| Transcend           | 2         | 1.44%   |
| Ramaxel Technology  | 2         | 1.44%   |
| Unknown (F301)      | 1         | 0.72%   |
| Unknown (AB)        | 1         | 0.72%   |
| KomputerBay         | 1         | 0.72%   |
| Intersil            | 1         | 0.72%   |
| G.Skill             | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| ASint Technology    | 1         | 0.72%   |
| A-DATA Technology   | 1         | 0.72%   |
| 2C0C0843D7349CA2    | 1         | 0.72%   |
| 2C0C0843D7349C9D    | 1         | 0.72%   |
| 2C080815D82F5C7B    | 1         | 0.72%   |
| 2C0108214C359D20    | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 24        | 15.79%  |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 5         | 3.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 1.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 1.32%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 2         | 1.32%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.32%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| Unknown (F301) RAM G2JT-4AFR00 16GB SODIMM DDR4 2400MT/s          | 1         | 0.66%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s               | 1         | 0.66%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s              | 1         | 0.66%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 1         | 0.66%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.66%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.66%   |
| SK hynix RAM HYMP151P72CP4-Y5 4GB DIMM DDR2 667MT/s               | 1         | 0.66%   |
| SK hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s               | 1         | 0.66%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 1         | 0.66%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s              | 1         | 0.66%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                   | 1         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 1         | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s            | 1         | 0.66%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s             | 1         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1         | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s           | 1         | 0.66%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 1         | 0.66%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 1         | 0.66%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.66%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.66%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s             | 1         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 1         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s             | 1         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s            | 1         | 0.66%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s            | 1         | 0.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 1         | 0.66%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 667MT/s             | 1         | 0.66%   |
| Samsung RAM M395T5160QZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1         | 0.66%   |
| Samsung RAM M395T5160CZ4-CE66 4GB FB-DIMM DDR2 667MT/s            | 1         | 0.66%   |
| Samsung RAM M393B5270CH0-CH9 4GB DIMM DDR3 1333MT/s               | 1         | 0.66%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s               | 1         | 0.66%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s               | 1         | 0.66%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.66%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s               | 1         | 0.66%   |
| Samsung RAM GXM8G4SCL116P-PB 8GB DIMM DDR3 1333MT/s               | 1         | 0.66%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 1         | 0.66%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s              | 1         | 0.66%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s                | 1         | 0.66%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1067MT/s              | 1         | 0.66%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s                | 1         | 0.66%   |
| Micron RAM MT41K512M8RH-125:E 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.66%   |
| Micron RAM Module 8GB Chip LPDDR4                                 | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 59        | 49.17%  |
| DDR4    | 27        | 22.5%   |
| DDR2    | 18        | 15%     |
| LPDDR4  | 6         | 5%      |
| Unknown | 6         | 5%      |
| SDRAM   | 2         | 1.67%   |
| LPDDR3  | 1         | 0.83%   |
| DDR     | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 54.24%  |
| DIMM         | 50        | 42.37%  |
| Chip         | 2         | 1.69%   |
| Row Of Chips | 1         | 0.85%   |
| FB-DIMM      | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 49        | 38.58%  |
| 2048  | 30        | 23.62%  |
| 8192  | 26        | 20.47%  |
| 16384 | 14        | 11.02%  |
| 1024  | 5         | 3.94%   |
| 32768 | 2         | 1.57%   |
| 256   | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 30        | 23.08%  |
| 1333    | 20        | 15.38%  |
| 2400    | 15        | 11.54%  |
| 2667    | 11        | 8.46%   |
| 667     | 11        | 8.46%   |
| 1067    | 10        | 7.69%   |
| 800     | 8         | 6.15%   |
| 2133    | 6         | 4.62%   |
| 3200    | 4         | 3.08%   |
| Unknown | 4         | 3.08%   |
| 1334    | 3         | 2.31%   |
| 1066    | 2         | 1.54%   |
| 2933    | 1         | 0.77%   |
| 2666    | 1         | 0.77%   |
| 1867    | 1         | 0.77%   |
| 1866    | 1         | 0.77%   |
| 1200    | 1         | 0.77%   |
| 333     | 1         | 0.77%   |

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
| Chicony Electronics                    | 13        | 30.95%  |
| IMC Networks                           | 6         | 14.29%  |
| Realtek Semiconductor                  | 4         | 9.52%   |
| Acer                                   | 4         | 9.52%   |
| Sunplus Innovation Technology          | 3         | 7.14%   |
| Silicon Motion                         | 2         | 4.76%   |
| Logitech                               | 2         | 4.76%   |
| ALi                                    | 2         | 4.76%   |
| Suyin                                  | 1         | 2.38%   |
| Microdia                               | 1         | 2.38%   |
| Lite-On Technology                     | 1         | 2.38%   |
| KYE Systems (Mouse Systems)            | 1         | 2.38%   |
| Genesys Logic                          | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.38%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 4.76%   |
| Chicony Integrated Camera                                  | 2         | 4.76%   |
| Chicony HD WebCam (Acer)                                   | 2         | 4.76%   |
| Acer Integrated Camera                                     | 2         | 4.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.38%   |
| Sunplus Integrated Camera                                  | 1         | 2.38%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.38%   |
| Sunplus Aukey-PC-LM1E Camera                               | 1         | 2.38%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.38%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.38%   |
| Realtek USB Camera                                         | 1         | 2.38%   |
| Realtek Integrated_Webcam_HD                               | 1         | 2.38%   |
| Microdia ASUS USB2.0 Webcam                                | 1         | 2.38%   |
| Logitech Webcam C310                                       | 1         | 2.38%   |
| Logitech C505 HD Webcam                                    | 1         | 2.38%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.38%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera           | 1         | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.38%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.38%   |
| IMC Networks Integrated Webcam                             | 1         | 2.38%   |
| IMC Networks Integrated Camera                             | 1         | 2.38%   |
| Genesys Logic Digital Microscope                           | 1         | 2.38%   |
| Chicony WebCam                                             | 1         | 2.38%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.38%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.38%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.38%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.38%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.38%   |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.38%   |
| Chicony 1.3M Webcam                                        | 1         | 2.38%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.38%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.38%   |
| ALi Gateway Webcam                                         | 1         | 2.38%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.38%   |
| Acer HD Webcam                                             | 1         | 2.38%   |

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
| 1     | 50        | 38.17%  |
| 0     | 43        | 32.82%  |
| 2     | 22        | 16.79%  |
| 3     | 14        | 10.69%  |
| 4     | 2         | 1.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 66        | 48.89%  |
| Card reader              | 18        | 13.33%  |
| Net/wireless             | 17        | 12.59%  |
| Bluetooth                | 15        | 11.11%  |
| Firewire controller      | 9         | 6.67%   |
| Fingerprint reader       | 6         | 4.44%   |
| Graphics card            | 2         | 1.48%   |
| Network                  | 1         | 0.74%   |
| Modem                    | 1         | 0.74%   |

