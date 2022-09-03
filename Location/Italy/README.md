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

Total: 254

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0TY179 A05                  | Server      | [482bca3952](https://bsd-hardware.info/?probe=482bca3952) | Sep 01, 2022 |
| HP            | 1496                        | Desktop     | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [02e11159f5](https://bsd-hardware.info/?probe=02e11159f5) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| BESSTAR Te... | VB9                         | All in one  | [ec5b4884a7](https://bsd-hardware.info/?probe=ec5b4884a7) | Aug 13, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | Desktop     | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
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
| helloSystem 0.7.0    | 16        | 8.74%   |
| helloSystem 0.4.0    | 12        | 6.56%   |
| helloSystem 0.5.0    | 9         | 4.92%   |
| OpenBSD 7.1          | 7         | 3.83%   |
| OPNsense 22.7        | 6         | 3.28%   |
| helloSystem 0.6.0    | 6         | 3.28%   |
| OPNsense 22.1.6      | 5         | 2.73%   |
| OPNsense 21.1        | 5         | 2.73%   |
| helloSystem 0.3.0    | 5         | 2.73%   |
| OPNsense 22.7.2      | 4         | 2.19%   |
| OPNsense 22.1.9      | 4         | 2.19%   |
| OPNsense 22.1        | 4         | 2.19%   |
| OPNsense 22.7.1      | 3         | 1.64%   |
| OPNsense 22.1.10     | 3         | 1.64%   |
| OPNsense 21.7.7      | 3         | 1.64%   |
| OPNsense 21.7.3      | 3         | 1.64%   |
| OPNsense 21.1.8      | 3         | 1.64%   |
| OPNsense 21.1.3      | 3         | 1.64%   |
| OPNsense 21.1.2      | 3         | 1.64%   |
| OPNsense 20.7.8      | 3         | 1.64%   |
| OpenBSD 6.8          | 3         | 1.64%   |
| NomadBSD 1.4         | 3         | 1.64%   |
| FreeBSD 13.1         | 3         | 1.64%   |
| FreeBSD 13.0-p7      | 3         | 1.64%   |
| FreeBSD 12.2-p2      | 3         | 1.64%   |
| OPNsense 22.1.8      | 2         | 1.09%   |
| OPNsense 22.1.4      | 2         | 1.09%   |
| OPNsense 21.1.1      | 2         | 1.09%   |
| NomadBSD 1.3.2       | 2         | 1.09%   |
| GhostBSD 21.08.27    | 2         | 1.09%   |
| GhostBSD 20.04.02    | 2         | 1.09%   |
| FreeBSD 13.0-p4      | 2         | 1.09%   |
| FreeBSD 13.0-CURRENT | 2         | 1.09%   |
| FreeBSD 12.3-p1      | 2         | 1.09%   |
| FreeBSD 12.2-p6      | 2         | 1.09%   |
| FreeBSD 12.2-p4      | 2         | 1.09%   |
| FreeBSD 12.1-p10     | 2         | 1.09%   |
| OPNsense 22.7.3      | 1         | 0.55%   |
| OPNsense 22.1.7      | 1         | 0.55%   |
| OPNsense 22.1.3      | 1         | 0.55%   |
| OPNsense 22.1.2      | 1         | 0.55%   |
| OPNsense 22.1.1      | 1         | 0.55%   |
| OPNsense 21.7.8      | 1         | 0.55%   |
| OPNsense 21.7.6      | 1         | 0.55%   |
| OPNsense 21.7.4      | 1         | 0.55%   |
| OPNsense 21.7.1      | 1         | 0.55%   |
| OPNsense 21.7        | 1         | 0.55%   |
| OPNsense 21.1.7      | 1         | 0.55%   |
| OPNsense 21.1.6      | 1         | 0.55%   |
| OPNsense 21.1.5      | 1         | 0.55%   |
| OpenBSD 6.7          | 1         | 0.55%   |
| NomadBSD 5806f915    | 1         | 0.55%   |
| NomadBSD 1.3.1       | 1         | 0.55%   |
| NetBSD 9.99.93       | 1         | 0.55%   |
| NetBSD 9.99.77       | 1         | 0.55%   |
| NetBSD 9.2_STABLE    | 1         | 0.55%   |
| NetBSD 9.2           | 1         | 0.55%   |
| NetBSD 9.1_STABLE    | 1         | 0.55%   |
| NetBSD 9.1           | 1         | 0.55%   |
| NetBSD 9.0           | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 53        | 35.81%  |
| helloSystem | 41        | 27.7%   |
| FreeBSD     | 26        | 17.57%  |
| OpenBSD     | 11        | 7.43%   |
| NomadBSD    | 7         | 4.73%   |
| NetBSD      | 6         | 4.05%   |
| GhostBSD    | 4         | 2.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 141       | 95.92%  |
| i386   | 3         | 2.04%   |
| evbarm | 3         | 2.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 62        | 41.61%  |
| helloDesktop  | 45        | 30.2%   |
| Openbox       | 7         | 4.7%    |
| XFCE          | 6         | 4.03%   |
| KDE5          | 6         | 4.03%   |
| fvwm          | 4         | 2.68%   |
| MATE          | 3         | 2.01%   |
| i3            | 3         | 2.01%   |
| ctwm          | 3         | 2.01%   |
| Cinnamon      | 3         | 2.01%   |
| xfwm          | 2         | 1.34%   |
| TWM           | 2         | 1.34%   |
| LXQt          | 1         | 0.67%   |
| Fluxbox       | 1         | 0.67%   |
| Enlightenment | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 86        | 58.11%  |
| Console | 62        | 41.89%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 85        | 57.82%  |
| SLiM    | 52        | 35.37%  |
| LightDM | 6         | 4.08%   |
| XDM     | 2         | 1.36%   |
| SDDM    | 2         | 1.36%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 70        | 46.67%  |
| en_US            | 52        | 34.67%  |
| it_IT            | 13        | 8.67%   |
| C                | 10        | 6.67%   |
| it_IT.ISO8859-15 | 2         | 1.33%   |
| ru_RU            | 1         | 0.67%   |
| it_IT.ISO8859-1  | 1         | 0.67%   |
| en_GB            | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 119       | 79.87%  |
| BIOS | 30        | 20.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 69        | 45.7%   |
| Zfs    | 63        | 41.72%  |
| Ffs    | 11        | 7.28%   |
| Cd9660 | 8         | 5.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 129       | 87.16%  |
| MBR     | 16        | 10.81%  |
| Unknown | 3         | 2.03%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 26        | 17.69%  |
| Lenovo                     | 15        | 10.2%   |
| Hewlett-Packard            | 11        | 7.48%   |
| Unknown                    | 11        | 7.48%   |
| Intel                      | 10        | 6.8%    |
| Dell                       | 10        | 6.8%    |
| Acer                       | 7         | 4.76%   |
| MSI                        | 5         | 3.4%    |
| Fujitsu                    | 5         | 3.4%    |
| PC Engines                 | 4         | 2.72%   |
| Gigabyte Technology        | 4         | 2.72%   |
| BESSTAR Tech               | 4         | 2.72%   |
| Apple                      | 4         | 2.72%   |
| ASRock                     | 3         | 2.04%   |
| AMI                        | 3         | 2.04%   |
| ZOTAC                      | 2         | 1.36%   |
| Toshiba                    | 2         | 1.36%   |
| Pegatron                   | 2         | 1.36%   |
| eMachines                  | 2         | 1.36%   |
| TUXEDO                     | 1         | 0.68%   |
| T-bao                      | 1         | 0.68%   |
| Supermicro                 | 1         | 0.68%   |
| Sun Microsystems           | 1         | 0.68%   |
| ShenZhen MinWin Technology | 1         | 0.68%   |
| Samsung Electronics        | 1         | 0.68%   |
| Raspberry Pi Foundation    | 1         | 0.68%   |
| Protectli                  | 1         | 0.68%   |
| Packard Bell               | 1         | 0.68%   |
| NF692                      | 1         | 0.68%   |
| MW                         | 1         | 0.68%   |
| Lex                        | 1         | 0.68%   |
| IBM                        | 1         | 0.68%   |
| HARDKERNEL                 | 1         | 0.68%   |
| Foxconn                    | 1         | 0.68%   |
| Deciso                     | 1         | 0.68%   |
| AZW                        | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 7.48%   |
| PC Engines APU2                          | 3         | 2.04%   |
| Intel Q3XXG4-P V1.0                      | 3         | 2.04%   |
| BESSTAR Tech N40                         | 3         | 2.04%   |
| MSI MS-7B86                              | 2         | 1.36%   |
| Lenovo ThinkCentre M83 10AHS35Q00        | 2         | 1.36%   |
| HP Laptop 15-da0xxx                      | 2         | 1.36%   |
| Fujitsu FUTRO S920                       | 2         | 1.36%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 1.36%   |
| ASUS PRIME H410M-A                       | 2         | 1.36%   |
| ASUS M4A88TD-V EVO/USB3                  | 2         | 1.36%   |
| ASUS IP4BL-ME                            | 2         | 1.36%   |
| Apple MacBook4,1                         | 2         | 1.36%   |
| AMI Aptio CRB                            | 2         | 1.36%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO         | 1         | 0.68%   |
| ZOTAC ZBOX-CI323NANO                     | 1         | 0.68%   |
| TUXEDO N14xWU                            | 1         | 0.68%   |
| Toshiba Satellite C855-1U4               | 1         | 0.68%   |
| Toshiba PORTEGE M780                     | 1         | 0.68%   |
| T-bao MINI PC                            | 1         | 0.68%   |
| Supermicro X8STi                         | 1         | 0.68%   |
| Sun Microsystems Ultra 24                | 1         | 0.68%   |
| ShenZhen MinWin MW-NANO-APL-4L           | 1         | 0.68%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.68%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.68%   |
| Protectli FW4B                           | 1         | 0.68%   |
| Pegatron Pro 3405 Series                 | 1         | 0.68%   |
| Pegatron KX629AA-ABZ a6561.it            | 1         | 0.68%   |
| PC Engines APU3                          | 1         | 0.68%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 0.68%   |
| NF692 1.0                                | 1         | 0.68%   |
| MW GMLK-2_5G4L                           | 1         | 0.68%   |
| MSI NR074AA-ABZ CQ5125IT                 | 1         | 0.68%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159)  | 1         | 0.68%   |
| MSI GF65 Thin 10SER                      | 1         | 0.68%   |
| Lex Pineview-D                           | 1         | 0.68%   |
| Lenovo ThinkPad X260 20F5S82N00          | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CMS0FA00          | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMS0J01N          | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS6PC00 | 1         | 0.68%   |
| Lenovo ThinkPad T495 20NJS0KP00          | 1         | 0.68%   |
| Lenovo ThinkPad T450 20BUS06B00          | 1         | 0.68%   |
| Lenovo ThinkPad T440 20B7S1C600          | 1         | 0.68%   |
| Lenovo ThinkPad T430 23501B3             | 1         | 0.68%   |
| Lenovo ThinkPad T420 4236BD5             | 1         | 0.68%   |
| Lenovo ThinkPad L530 24812TG             | 1         | 0.68%   |
| Lenovo G505 20240                        | 1         | 0.68%   |
| Lenovo G50-45 80E3                       | 1         | 0.68%   |
| Lenovo B590 62743PG                      | 1         | 0.68%   |
| Intel NUC6i5SYB H81131-503               | 1         | 0.68%   |
| Intel NUC5i5RYB H40999-502               | 1         | 0.68%   |
| Intel NUC10i7FNK                         | 1         | 0.68%   |
| Intel NCB-4210WG                         | 1         | 0.68%   |
| Intel MAHOBAY                            | 1         | 0.68%   |
| Intel D945GCLF2                          | 1         | 0.68%   |
| Intel D2500CC AAG81477-401               | 1         | 0.68%   |
| IBM ThinkPad R51 2887AVG                 | 1         | 0.68%   |
| HP Z440 Workstation                      | 1         | 0.68%   |
| HP xw8600 Workstation                    | 1         | 0.68%   |
| HP ProLiant MicroServer Gen8             | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 11        | 7.48%   |
| Lenovo ThinkPad                | 10        | 6.8%    |
| ASUS PRIME                     | 6         | 4.08%   |
| PC Engines APU2                | 3         | 2.04%   |
| Intel Q3XXG4-P                 | 3         | 2.04%   |
| HP Compaq                      | 3         | 2.04%   |
| Dell PowerEdge                 | 3         | 2.04%   |
| BESSTAR Tech N40               | 3         | 2.04%   |
| ASUS VivoBook                  | 3         | 2.04%   |
| Acer Aspire                    | 3         | 2.04%   |
| MSI MS-7B86                    | 2         | 1.36%   |
| Lenovo ThinkCentre             | 2         | 1.36%   |
| HP Laptop                      | 2         | 1.36%   |
| Gigabyte X570                  | 2         | 1.36%   |
| Fujitsu FUTRO                  | 2         | 1.36%   |
| Fujitsu ESPRIMO                | 2         | 1.36%   |
| Dell Precision                 | 2         | 1.36%   |
| Dell Inspiron                  | 2         | 1.36%   |
| ASUS M4A88TD-V                 | 2         | 1.36%   |
| ASUS IP4BL-ME                  | 2         | 1.36%   |
| Apple MacBook4                 | 2         | 1.36%   |
| AMI Aptio                      | 2         | 1.36%   |
| ZOTAC ZBOX-MI640               | 1         | 0.68%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.68%   |
| TUXEDO N14xWU                  | 1         | 0.68%   |
| Toshiba Satellite              | 1         | 0.68%   |
| Toshiba PORTEGE                | 1         | 0.68%   |
| T-bao MINI                     | 1         | 0.68%   |
| Supermicro X8STi               | 1         | 0.68%   |
| Sun Microsystems Ultra         | 1         | 0.68%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.68%   |
| Samsung 3570R                  | 1         | 0.68%   |
| RPi Raspberry                  | 1         | 0.68%   |
| Protectli FW4B                 | 1         | 0.68%   |
| Pegatron Pro                   | 1         | 0.68%   |
| Pegatron KX629AA-ABZ           | 1         | 0.68%   |
| PC Engines APU3                | 1         | 0.68%   |
| Packard Bell EasyNote          | 1         | 0.68%   |
| NF692 1.0                      | 1         | 0.68%   |
| MW GMLK-2                      | 1         | 0.68%   |
| MSI NR074AA-ABZ                | 1         | 0.68%   |
| MSI KBL-U                      | 1         | 0.68%   |
| MSI GF65                       | 1         | 0.68%   |
| Lex Pineview-D                 | 1         | 0.68%   |
| Lenovo G505                    | 1         | 0.68%   |
| Lenovo G50-45                  | 1         | 0.68%   |
| Lenovo B590                    | 1         | 0.68%   |
| Intel NUC6i5SYB                | 1         | 0.68%   |
| Intel NUC5i5RYB                | 1         | 0.68%   |
| Intel NUC10i7FNK               | 1         | 0.68%   |
| Intel NCB-4210WG               | 1         | 0.68%   |
| Intel MAHOBAY                  | 1         | 0.68%   |
| Intel D945GCLF2                | 1         | 0.68%   |
| Intel D2500CC                  | 1         | 0.68%   |
| IBM ThinkPad                   | 1         | 0.68%   |
| HP Z440                        | 1         | 0.68%   |
| HP xw8600                      | 1         | 0.68%   |
| HP ProLiant                    | 1         | 0.68%   |
| HP ProBook                     | 1         | 0.68%   |
| HP Mini                        | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 15        | 10.2%   |
| 2021    | 13        | 8.84%   |
| 2016    | 13        | 8.84%   |
| 2011    | 12        | 8.16%   |
| 2010    | 12        | 8.16%   |
| 2020    | 11        | 7.48%   |
| 2018    | 11        | 7.48%   |
| 2014    | 10        | 6.8%    |
| 2013    | 9         | 6.12%   |
| 2012    | 8         | 5.44%   |
| 2008    | 8         | 5.44%   |
| 2015    | 7         | 4.76%   |
| 2009    | 7         | 4.76%   |
| 2017    | 4         | 2.72%   |
| 2022    | 2         | 1.36%   |
| 2007    | 2         | 1.36%   |
| Unknown | 2         | 1.36%   |
| 2006    | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 78        | 53.06%  |
| Notebook       | 51        | 34.69%  |
| Mini pc        | 11        | 7.48%   |
| Server         | 4         | 2.72%   |
| All in one     | 2         | 1.36%   |
| System on chip | 1         | 0.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 143       | 97.28%  |
| Yes  | 4         | 2.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 55        | 36.67%  |
| 4.01-8.0    | 45        | 30%     |
| 16.01-24.0  | 18        | 12%     |
| 2.01-3.0    | 12        | 8%      |
| 32.01-64.0  | 10        | 6.67%   |
| 24.01-32.0  | 3         | 2%      |
| 64.01-256.0 | 3         | 2%      |
| 3.01-4.0    | 2         | 1.33%   |
| 0.51-1.0    | 1         | 0.67%   |
| 0.01-0.5    | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 97        | 63.82%  |
| 0.51-1.0   | 29        | 19.08%  |
| 1.01-2.0   | 9         | 5.92%   |
| Unknown    | 6         | 3.95%   |
| 2.01-3.0   | 5         | 3.29%   |
| 4.01-8.0   | 4         | 2.63%   |
| 24.01-32.0 | 1         | 0.66%   |
| 8.01-16.0  | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 61.18%  |
| 2      | 31        | 20.39%  |
| 0      | 11        | 7.24%   |
| 4      | 7         | 4.61%   |
| 3      | 6         | 3.95%   |
| 10     | 1         | 0.66%   |
| 9      | 1         | 0.66%   |
| 7      | 1         | 0.66%   |
| 6      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 68.92%  |
| Yes       | 46        | 31.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 94.56%  |
| No        | 8         | 5.44%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 50%     |
| No        | 74        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 102       | 68.46%  |
| Yes       | 47        | 31.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 147       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Milan                    | 22        | 12.87%  |
| Rome                     | 17        | 9.94%   |
| Bologna                  | 6         | 3.51%   |
| Turin                    | 5         | 2.92%   |
| Trieste                  | 3         | 1.75%   |
| Naples                   | 3         | 1.75%   |
| Venice                   | 2         | 1.17%   |
| Turrivalignani           | 2         | 1.17%   |
| Silea                    | 2         | 1.17%   |
| Rho                      | 2         | 1.17%   |
| Reggio Emilia            | 2         | 1.17%   |
| Padova                   | 2         | 1.17%   |
| Monterotondo             | 2         | 1.17%   |
| Lucca                    | 2         | 1.17%   |
| Catania                  | 2         | 1.17%   |
| Brescia                  | 2         | 1.17%   |
| Adelfia                  | 2         | 1.17%   |
| Viterbo                  | 1         | 0.58%   |
| Vigonovo                 | 1         | 0.58%   |
| Verona                   | 1         | 0.58%   |
| Udine                    | 1         | 0.58%   |
| Treviso                  | 1         | 0.58%   |
| Trento                   | 1         | 0.58%   |
| Terni                    | 1         | 0.58%   |
| Soresina                 | 1         | 0.58%   |
| Solarino                 | 1         | 0.58%   |
| Sesto San Giovanni       | 1         | 0.58%   |
| Sasso Marconi            | 1         | 0.58%   |
| Saronno                  | 1         | 0.58%   |
| Sannicandro di Bari      | 1         | 0.58%   |
| San Prospero             | 1         | 0.58%   |
| San Fior                 | 1         | 0.58%   |
| San Donato Milanese      | 1         | 0.58%   |
| Roncade                  | 1         | 0.58%   |
| Resana                   | 1         | 0.58%   |
| Reggio Calabria          | 1         | 0.58%   |
| Ravenna                  | 1         | 0.58%   |
| Ragusa                   | 1         | 0.58%   |
| Prato                    | 1         | 0.58%   |
| Pozzuolo Martesana       | 1         | 0.58%   |
| Ponsacco                 | 1         | 0.58%   |
| Pistoia                  | 1         | 0.58%   |
| Pisa                     | 1         | 0.58%   |
| Piovene Rocchette        | 1         | 0.58%   |
| Pioltello                | 1         | 0.58%   |
| Pessano Con Bornago      | 1         | 0.58%   |
| Peschiera del Garda      | 1         | 0.58%   |
| Passignano sul Trasimeno | 1         | 0.58%   |
| Parma                    | 1         | 0.58%   |
| Pandino                  | 1         | 0.58%   |
| Palermo                  | 1         | 0.58%   |
| Ortona                   | 1         | 0.58%   |
| Oleggio                  | 1         | 0.58%   |
| Nughedu San Nicolo       | 1         | 0.58%   |
| Monza                    | 1         | 0.58%   |
| Monteleone di Fermo      | 1         | 0.58%   |
| Montegranaro             | 1         | 0.58%   |
| Modena                   | 1         | 0.58%   |
| Mestrino                 | 1         | 0.58%   |
| Messina                  | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 59     | 14.81%  |
| Samsung Electronics | 25        | 44     | 13.23%  |
| Seagate             | 22        | 45     | 11.64%  |
| Crucial             | 17        | 27     | 8.99%   |
| Toshiba             | 13        | 31     | 6.88%   |
| Kingston            | 12        | 13     | 6.35%   |
| Transcend           | 10        | 14     | 5.29%   |
| SanDisk             | 8         | 8      | 4.23%   |
| Hitachi             | 5         | 7      | 2.65%   |
| PNY                 | 3         | 6      | 1.59%   |
| Micron Technology   | 3         | 3      | 1.59%   |
| KingSpec            | 3         | 4      | 1.59%   |
| Intel               | 3         | 4      | 1.59%   |
| Innodisk            | 3         | 3      | 1.59%   |
| Hoodisk             | 3         | 3      | 1.59%   |
| EMTEC               | 3         | 4      | 1.59%   |
| Phison              | 2         | 2      | 1.06%   |
| OCZ                 | 2         | 2      | 1.06%   |
| NVMe                | 2         | 2      | 1.06%   |
| Maxtor              | 2         | 2      | 1.06%   |
| Leven               | 2         | 2      | 1.06%   |
| Dogfish             | 2         | 2      | 1.06%   |
| China               | 2         | 3      | 1.06%   |
| Union Memory        | 1         | 1      | 0.53%   |
| SK hynix            | 1         | 1      | 0.53%   |
| Silicon Motion      | 1         | 2      | 0.53%   |
| Pccooler            | 1         | 1      | 0.53%   |
| KingDian            | 1         | 1      | 0.53%   |
| Intenso             | 1         | 1      | 0.53%   |
| Indilinx            | 1         | 1      | 0.53%   |
| HGST                | 1         | 1      | 0.53%   |
| Fujitsu             | 1         | 1      | 0.53%   |
| FORESEE             | 1         | 2      | 0.53%   |
| Corsair             | 1         | 2      | 0.53%   |
| ASUSTek Computer    | 1         | 2      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |
| A-DATA Technology   | 1         | 2      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 860 EVO 250GB       | 4         | 1.91%   |
| Crucial CT240BX500SSD1 240GB    | 4         | 1.91%   |
| Samsung SSD 850 EVO 500GB       | 3         | 1.44%   |
| Samsung SSD 850 EVO 250GB       | 3         | 1.44%   |
| EMTEC X150 120GB                | 3         | 1.44%   |
| Crucial CT500MX500SSD1 500GB    | 3         | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2         | 0.96%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2         | 0.96%   |
| Transcend TS256GMTS430S 256GB   | 2         | 0.96%   |
| Toshiba MQ04ABF100 1TB          | 2         | 0.96%   |
| Toshiba HDWG440 4TB             | 2         | 0.96%   |
| Toshiba DT01ACA050 500GB        | 2         | 0.96%   |
| Seagate ST320LT007-9ZV142 320GB | 2         | 0.96%   |
| Seagate ST1000DM003-1ER162 1TB  | 2         | 0.96%   |
| Samsung SSD 970 EVO 250GB       | 2         | 0.96%   |
| Samsung SSD 860 EVO 500GB       | 2         | 0.96%   |
| Samsung HM321HI 320GB           | 2         | 0.96%   |
| PNY CS900 120GB SSD             | 2         | 0.96%   |
| Phison SATA SSD 16GB            | 2         | 0.96%   |
| Kingston SV300S37A120G 120GB    | 2         | 0.96%   |
| Kingston SA400S37240G 240GB     | 2         | 0.96%   |
| Kingston SA400S37120G 120GB     | 2         | 0.96%   |
| KingSpec Q-720 720GB            | 2         | 0.96%   |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2         | 0.96%   |
| Hoodisk SSD 256GB               | 2         | 0.96%   |
| Crucial CT250MX500SSD1 250GB    | 2         | 0.96%   |
| Crucial CT120BX500SSD1 120GB    | 2         | 0.96%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1         | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB    | 1         | 0.48%   |
| WDC WDS100T2B0B-00YS70 1TB      | 1         | 0.48%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1         | 0.48%   |
| WDC WD6400AAKS-65A7B0 640GB     | 1         | 0.48%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1         | 0.48%   |
| WDC WD5000LPVT-80G33T2 500GB    | 1         | 0.48%   |
| WDC WD5000BPKX-00HPJT0 500GB    | 1         | 0.48%   |
| WDC WD5000BPKT-00PK4T0 500GB    | 1         | 0.48%   |
| WDC WD5000BMVV-11A1CS0 500GB    | 1         | 0.48%   |
| WDC WD5000BEVT-00A03T0 500GB    | 1         | 0.48%   |
| WDC WD5000AAKX-75U6AA0 500GB    | 1         | 0.48%   |
| WDC WD5000AAKX-00ERMA0 500GB    | 1         | 0.48%   |
| WDC WD5000AAKS-00E4A0 500GB     | 1         | 0.48%   |
| WDC WD5000AAKS-00D2B0 500GB     | 1         | 0.48%   |
| WDC WD40NMZW-11GX6S1 4TB        | 1         | 0.48%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1         | 0.48%   |
| WDC WD40EFRX-68N32N0 4TB        | 1         | 0.48%   |
| WDC WD3200BEKX-60B7WT0 320GB    | 1         | 0.48%   |
| WDC WD3200AAKS-00L9A0 320GB     | 1         | 0.48%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1         | 0.48%   |
| WDC WD30EZRZ-00GXCB0 3TB        | 1         | 0.48%   |
| WDC WD2500LPCX-24C6HT0 250GB    | 1         | 0.48%   |
| WDC WD2500BEVT-22A23T0 250GB    | 1         | 0.48%   |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 0.48%   |
| WDC WD2500AAJS-07M0A0 250GB     | 1         | 0.48%   |
| WDC WD20PURZ-85GU6Y0 2TB        | 1         | 0.48%   |
| WDC WD20EVDS-63T3B0 2TB         | 1         | 0.48%   |
| WDC WD2002FYPS-01U1B1 2TB       | 1         | 0.48%   |
| WDC WD15EADS-00P8B0 1.5TB       | 1         | 0.48%   |
| WDC WD1500HLFS-01G6U0 150GB     | 1         | 0.48%   |
| WDC WD10SDZW-11UMGS0 1TB        | 1         | 0.48%   |
| WDC WD10EFRX-68PJCN0 1TB        | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 53     | 33.33%  |
| Seagate             | 22        | 45     | 31.88%  |
| Toshiba             | 11        | 27     | 15.94%  |
| Hitachi             | 5         | 7      | 7.25%   |
| Samsung Electronics | 3         | 3      | 4.35%   |
| Maxtor              | 2         | 2      | 2.9%    |
| NVMe                | 1         | 1      | 1.45%   |
| HGST                | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 35     | 16.51%  |
| Crucial             | 16        | 26     | 14.68%  |
| Transcend           | 9         | 13     | 8.26%   |
| Kingston            | 9         | 9      | 8.26%   |
| SanDisk             | 8         | 8      | 7.34%   |
| WDC                 | 6         | 6      | 5.5%    |
| PNY                 | 3         | 6      | 2.75%   |
| KingSpec            | 3         | 4      | 2.75%   |
| Intel               | 3         | 4      | 2.75%   |
| Innodisk            | 3         | 3      | 2.75%   |
| Hoodisk             | 3         | 3      | 2.75%   |
| EMTEC               | 3         | 4      | 2.75%   |
| Toshiba             | 2         | 4      | 1.83%   |
| Phison              | 2         | 2      | 1.83%   |
| OCZ                 | 2         | 2      | 1.83%   |
| Micron Technology   | 2         | 2      | 1.83%   |
| Leven               | 2         | 2      | 1.83%   |
| Dogfish             | 2         | 2      | 1.83%   |
| China               | 2         | 3      | 1.83%   |
| SK hynix            | 1         | 1      | 0.92%   |
| Pccooler            | 1         | 1      | 0.92%   |
| NVMe                | 1         | 1      | 0.92%   |
| KingDian            | 1         | 1      | 0.92%   |
| Intenso             | 1         | 1      | 0.92%   |
| Indilinx            | 1         | 1      | 0.92%   |
| FORESEE             | 1         | 2      | 0.92%   |
| Corsair             | 1         | 2      | 0.92%   |
| ASUSTek Computer    | 1         | 2      | 0.92%   |
| Apple               | 1         | 1      | 0.92%   |
| A-DATA Technology   | 1         | 2      | 0.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 92        | 153    | 57.5%   |
| HDD  | 54        | 140    | 33.75%  |
| NVMe | 14        | 16     | 8.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 129       | 293    | 90.21%  |
| NVMe | 14        | 16     | 9.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 197    | 74.67%  |
| 0.51-1.0   | 21        | 60     | 14%     |
| 1.01-2.0   | 7         | 9      | 4.67%   |
| 3.01-4.0   | 5         | 10     | 3.33%   |
| 2.01-3.0   | 2         | 5      | 1.33%   |
| 4.01-10.0  | 2         | 4      | 1.33%   |
| 10.01-20.0 | 1         | 8      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 31.13%  |
| 101-250        | 38        | 25.17%  |
| 251-500        | 26        | 17.22%  |
| 21-50          | 15        | 9.93%   |
| 51-100         | 11        | 7.28%   |
| 501-1000       | 9         | 5.96%   |
| More than 3000 | 3         | 1.99%   |
| 1001-2000      | 1         | 0.66%   |
| Unknown        | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 133       | 87.5%   |
| 21-50          | 11        | 7.24%   |
| 51-100         | 3         | 1.97%   |
| More than 3000 | 1         | 0.66%   |
| 101-250        | 1         | 0.66%   |
| 1001-2000      | 1         | 0.66%   |
| 501-1000       | 1         | 0.66%   |
| Unknown        | 1         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2         | 2      | 7.14%   |
| Seagate ST320LT007-9ZV142 320GB   | 2         | 2      | 7.14%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1         | 2      | 3.57%   |
| WDC WD5000AAKS-00E4A0 500GB       | 1         | 1      | 3.57%   |
| WDC WD20EVDS-63T3B0 2TB           | 1         | 1      | 3.57%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1         | 1      | 3.57%   |
| WDC WD1000DHTZ-04N21V1 1TB        | 1         | 2      | 3.57%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 3.57%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 3.57%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 3      | 3.57%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1         | 1      | 3.57%   |
| Seagate ST31500341AS 1.5TB        | 1         | 1      | 3.57%   |
| SanDisk SDSSDP064G 64GB           | 1         | 1      | 3.57%   |
| SanDisk SD9SN8W-128G-1006 128GB   | 1         | 1      | 3.57%   |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 3.57%   |
| OCZ VERTEX3 120GB                 | 1         | 1      | 3.57%   |
| Kingston SV300S37A120G 120GB      | 1         | 1      | 3.57%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 3.57%   |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2      | 3.57%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 3.57%   |
| Hitachi HDS723030ALA640 3TB       | 1         | 2      | 3.57%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 3      | 3.57%   |
| China SATA3 240GB SSD             | 1         | 1      | 3.57%   |
| A-DATA Technology SX300 128GB     | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 28.57%  |
| WDC                 | 7         | 9      | 25%     |
| Hitachi             | 3         | 5      | 10.71%  |
| SanDisk             | 2         | 2      | 7.14%   |
| Toshiba             | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| OCZ                 | 1         | 1      | 3.57%   |
| Kingston            | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Crucial             | 1         | 3      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 10     | 40%     |
| WDC                 | 7         | 9      | 35%     |
| Hitachi             | 3         | 5      | 15%     |
| Toshiba             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 26     | 69.23%  |
| SSD  | 8         | 10     | 30.77%  |

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
| Works    | 117       | 255    | 77.48%  |
| Malfunc  | 26        | 36     | 17.22%  |
| Detected | 8         | 18     | 5.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 108       | 63.53%  |
| AMD                              | 27        | 15.88%  |
| Samsung Electronics              | 8         | 4.71%   |
| Broadcom / LSI                   | 4         | 2.35%   |
| Marvell Technology Group         | 3         | 1.76%   |
| Kingston Technology Company      | 3         | 1.76%   |
| VIA Technologies                 | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] | 2         | 1.18%   |
| JMicron Technology               | 2         | 1.18%   |
| ASMedia Technology               | 2         | 1.18%   |
| Union Memory (Shenzhen)          | 1         | 0.59%   |
| Silicon Motion                   | 1         | 0.59%   |
| Nvidia                           | 1         | 0.59%   |
| Micron/Crucial Technology        | 1         | 0.59%   |
| Micron Technology                | 1         | 0.59%   |
| KIOXIA                           | 1         | 0.59%   |
| Integrated Technology Express    | 1         | 0.59%   |
| Adaptec                          | 1         | 0.59%   |
| Unknown                          | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 9.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 4.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 3.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 3.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 3.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.01%   |
| Unknown                                                                          | 4         | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.51%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.51%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 1.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.51%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2         | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.01%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.5%    |
| Samsung SM951 AHCI                                                               | 1         | 0.5%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.5%    |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.5%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 0.5%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 1         | 0.5%    |
| Marvell Group 88SE91A3 SATA-600 Controller                                       | 1         | 0.5%    |
| KIOXIA NVMe SSD                                                                  | 1         | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.5%    |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.5%    |
| JMicron JMB361 AHCI/IDE                                                          | 1         | 0.5%    |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.5%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.5%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.5%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 1         | 0.5%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 1         | 0.5%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 0.5%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 1         | 0.5%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 1         | 0.5%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 114       | 67.06%  |
| IDE  | 30        | 17.65%  |
| NVMe | 16        | 9.41%   |
| RAID | 7         | 4.12%   |
| SCSI | 3         | 1.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 115       | 78.23%  |
| AMD      | 29        | 19.73%  |
| Broadcom | 1         | 0.68%   |
| Arm      | 1         | 0.68%   |
| Unknown  | 1         | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.7%    |
| AMD GX-412TC SOC                              | 4         | 2.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.03%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 2.03%   |
| AMD Phenom II X4 965 Processor                | 3         | 2.03%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.35%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2         | 1.35%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 2         | 1.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.35%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 1.35%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 1.35%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.35%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 2         | 1.35%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz         | 1         | 0.68%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.68%   |
| Intel Xeon CPU X3470 @ 2.93GHz                | 1         | 0.68%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1         | 0.68%   |
| Intel Xeon CPU E5440 @ 2.83GHz                | 1         | 0.68%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.68%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1         | 0.68%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1         | 0.68%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.68%   |
| Intel Xeon CPU E3113 @ 3.00GHz                | 1         | 0.68%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz           | 1         | 0.68%   |
| Intel Pentium M processor                     | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU E6600             | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.68%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GH              | 1         | 0.68%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 0.68%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 1         | 0.68%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.68%   |
| Intel Pentium CPU 997 @ 1.60GHz               | 1         | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.68%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.68%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 0.68%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.68%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 1         | 0.68%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1         | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.68%   |
| Intel Core i5-6260U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.68%   |
| Intel Core i5-4300Y CPU @ 1.60GHz             | 1         | 0.68%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 16.89%  |
| Intel Celeron           | 18        | 12.16%  |
| Intel Core i7           | 14        | 9.46%   |
| Intel Core i3           | 13        | 8.78%   |
| Intel Xeon              | 10        | 6.76%   |
| Intel Atom              | 9         | 6.08%   |
| Intel Core 2 Duo        | 8         | 5.41%   |
| Intel Pentium           | 7         | 4.73%   |
| AMD Ryzen 5             | 6         | 4.05%   |
| AMD GX                  | 6         | 4.05%   |
| Intel Pentium Dual-Core | 4         | 2.7%    |
| Other                   | 3         | 2.03%   |
| Intel Pentium Dual      | 3         | 2.03%   |
| AMD Phenom II X4        | 3         | 2.03%   |
| AMD Ryzen 9             | 2         | 1.35%   |
| AMD Ryzen 7             | 2         | 1.35%   |
| Intel Xeon Silver       | 1         | 0.68%   |
| Intel Pentium M         | 1         | 0.68%   |
| Intel Core 2 Quad       | 1         | 0.68%   |
| Intel Core 2 Extreme    | 1         | 0.68%   |
| Intel 686-class         | 1         | 0.68%   |
| AMD Turion 64 X2 Mobile | 1         | 0.68%   |
| AMD Ryzen Embedded      | 1         | 0.68%   |
| AMD Ryzen 7 PRO         | 1         | 0.68%   |
| AMD Ryzen 3             | 1         | 0.68%   |
| AMD FX                  | 1         | 0.68%   |
| AMD E2                  | 1         | 0.68%   |
| AMD E1                  | 1         | 0.68%   |
| AMD Athlon II X4        | 1         | 0.68%   |
| AMD A6                  | 1         | 0.68%   |
| AMD A4                  | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 44.59%  |
| 4       | 45        | 30.41%  |
| Unknown | 16        | 10.81%  |
| 12      | 6         | 4.05%   |
| 8       | 6         | 4.05%   |
| 16      | 3         | 2.03%   |
| 1       | 3         | 2.03%   |
| 6       | 2         | 1.35%   |
| 32      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 139       | 93.92%  |
| 2       | 5         | 3.38%   |
| Unknown | 4         | 2.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 69        | 46.62%  |
| 2       | 63        | 42.57%  |
| Unknown | 16        | 10.81%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 14        | 9.46%   |
| SandyBridge   | 13        | 8.78%   |
| KabyLake      | 13        | 8.78%   |
| Haswell       | 10        | 6.76%   |
| IvyBridge     | 9         | 6.08%   |
| Broadwell     | 8         | 5.41%   |
| Bonnell       | 8         | 5.41%   |
| Silvermont    | 7         | 4.73%   |
| Goldmont plus | 6         | 4.05%   |
| Zen+          | 5         | 3.38%   |
| Westmere      | 5         | 3.38%   |
| Skylake       | 5         | 3.38%   |
| Puma          | 5         | 3.38%   |
| Core          | 5         | 3.38%   |
| CometLake     | 5         | 3.38%   |
| Unknown       | 5         | 3.38%   |
| K10           | 4         | 2.7%    |
| Jaguar        | 4         | 2.7%    |
| Zen 3         | 3         | 2.03%   |
| Nehalem       | 3         | 2.03%   |
| Goldmont      | 3         | 2.03%   |
| Zen 2         | 2         | 1.35%   |
| Zen           | 2         | 1.35%   |
| Piledriver    | 1         | 0.68%   |
| P6            | 1         | 0.68%   |
| K8 Hammer     | 1         | 0.68%   |
| K10 Llano     | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 59.59%  |
| AMD                              | 34        | 23.29%  |
| Nvidia                           | 20        | 13.7%   |
| Matrox Electronics Systems       | 4         | 2.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 6.67%   |
| Intel HD Graphics 620                                                                    | 6         | 4%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 4%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 3.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5         | 3.33%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.67%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 2.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.67%   |
| Intel HD Graphics 6000                                                                   | 3         | 2%      |
| Intel HD Graphics 500                                                                    | 3         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2%      |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.33%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 1.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.33%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.33%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2         | 1.33%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.33%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.33%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.67%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.67%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.67%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.67%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.67%   |
| Nvidia GK107 [NVS 510]                                                                   | 1         | 0.67%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.67%   |
| Nvidia GK104GL [Quadro K4200]                                                            | 1         | 0.67%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.67%   |
| Nvidia G86 [Quadro NVS 290]                                                              | 1         | 0.67%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 0.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 0.67%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 0.67%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 1         | 0.67%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 0.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1         | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 0.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.67%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.67%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.67%   |
| Intel Iris Graphics 540                                                                  | 1         | 0.67%   |
| Intel HD Graphics 630                                                                    | 1         | 0.67%   |
| Intel HD Graphics 530                                                                    | 1         | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 47.97%  |
| 1 x AMD        | 32        | 21.62%  |
| 1 x Nvidia     | 14        | 9.46%   |
| Other          | 9         | 6.08%   |
| 2 x Intel      | 9         | 6.08%   |
| Intel + Nvidia | 6         | 4.05%   |
| 1 x Matrox     | 4         | 2.7%    |
| 2 x AMD        | 1         | 0.68%   |
| 1 x SiS        | 1         | 0.68%   |
| Intel + AMD    | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 123       | 82%     |
| Unknown     | 14        | 9.33%   |
| Proprietary | 13        | 8.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 78.52%  |
| 0.01-0.5   | 11        | 7.38%   |
| 1.01-2.0   | 9         | 6.04%   |
| 3.01-4.0   | 6         | 4.03%   |
| 0.51-1.0   | 4         | 2.68%   |
| 7.01-8.0   | 1         | 0.67%   |
| 5.01-6.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 13        | 16.05%  |
| Samsung Electronics  | 9         | 11.11%  |
| Philips              | 8         | 9.88%   |
| LG Display           | 7         | 8.64%   |
| Acer                 | 6         | 7.41%   |
| BOE                  | 5         | 6.17%   |
| Hewlett-Packard      | 4         | 4.94%   |
| Dell                 | 4         | 4.94%   |
| Chimei Innolux       | 4         | 4.94%   |
| Apple                | 4         | 4.94%   |
| Lenovo               | 2         | 2.47%   |
| HannStar             | 2         | 2.47%   |
| Goldstar             | 2         | 2.47%   |
| ___                  | 1         | 1.23%   |
| Sony                 | 1         | 1.23%   |
| Packard Bell         | 1         | 1.23%   |
| Orion                | 1         | 1.23%   |
| LG Philips           | 1         | 1.23%   |
| LG Electronics       | 1         | 1.23%   |
| Iiyama               | 1         | 1.23%   |
| Fujitsu Siemens      | 1         | 1.23%   |
| Eizo                 | 1         | 1.23%   |
| ASUSTek Computer     | 1         | 1.23%   |
| Ancor Communications | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 6         | 7.41%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 2         | 2.47%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                      | 2         | 2.47%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.23%   |
| Sony TV SNY5D01 1360x768                                             | 1         | 1.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 1.23%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 1.23%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                     | 1         | 1.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1         | 1.23%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch             | 1         | 1.23%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch             | 1         | 1.23%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch       | 1         | 1.23%   |
| Orion LCD Monitor ORN1207 1920x1080                                  | 1         | 1.23%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.23%   |
| LG Electronics LCD Monitor E2360 1920x1080                           | 1         | 1.23%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 1.23%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 1.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 1.23%   |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 1.23%   |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1         | 1.23%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch    | 1         | 1.23%   |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch            | 1         | 1.23%   |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 1.23%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch           | 1         | 1.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 1.23%   |
| HannStar HSG1233 HSP0018 1920x1080 520x290mm 23.4-inch               | 1         | 1.23%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 1         | 1.23%   |
| Goldstar 2D FHD LG TV GSM59C4 1920x1080 510x290mm 23.1-inch          | 1         | 1.23%   |
| Fujitsu Siemens B23T-6 LED FUS07FB 1920x1080 510x290mm 23.1-inch     | 1         | 1.23%   |
| Eizo LCD Monitor S1901 1280x1024                                     | 1         | 1.23%   |
| Dell U4021QW DEL4206 2560x1080 930x390mm 39.7-inch                   | 1         | 1.23%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1         | 1.23%   |
| Dell E198FP DELA028 1280x1024 380x300mm 19.1-inch                    | 1         | 1.23%   |
| Dell 2007FP DELA021 1600x1200 410x310mm 20.2-inch                    | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15B8 1366x768 340x190mm 15.3-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch     | 1         | 1.23%   |
| BOE LCD Monitor BOE07F1 1920x1080 340x190mm 15.3-inch                | 1         | 1.23%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                 | 1         | 1.23%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                 | 1         | 1.23%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 1.23%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                 | 1         | 1.23%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 340x190mm 15.3-inch       | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch       | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch        | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 220x130mm 10.1-inch        | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch       | 1         | 1.23%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 33        | 42.86%  |
| 1366x768 (WXGA)   | 21        | 27.27%  |
| 1440x900 (WXGA+)  | 4         | 5.19%   |
| 1600x900 (HD+)    | 3         | 3.9%    |
| 1280x1024 (SXGA)  | 3         | 3.9%    |
| 2560x1080         | 2         | 2.6%    |
| 1920x1200 (WUXGA) | 2         | 2.6%    |
| 1280x800 (WXGA)   | 2         | 2.6%    |
| 1024x600          | 2         | 2.6%    |
| 3840x2160 (4K)    | 1         | 1.3%    |
| 2560x1440 (QHD)   | 1         | 1.3%    |
| 1600x1200         | 1         | 1.3%    |
| 1360x768          | 1         | 1.3%    |
| 1024x768 (XGA)    | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 25.93%  |
| 13      | 10        | 12.35%  |
| 21      | 8         | 9.88%   |
| Unknown | 8         | 9.88%   |
| 24      | 5         | 6.17%   |
| 23      | 5         | 6.17%   |
| 27      | 4         | 4.94%   |
| 19      | 4         | 4.94%   |
| 31      | 2         | 2.47%   |
| 18      | 2         | 2.47%   |
| 12      | 2         | 2.47%   |
| 10      | 2         | 2.47%   |
| 39      | 1         | 1.23%   |
| 34      | 1         | 1.23%   |
| 28      | 1         | 1.23%   |
| 22      | 1         | 1.23%   |
| 20      | 1         | 1.23%   |
| 17      | 1         | 1.23%   |
| 14      | 1         | 1.23%   |
| 11      | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 36.71%  |
| 501-600     | 12        | 15.19%  |
| 401-500     | 11        | 13.92%  |
| 201-300     | 8         | 10.13%  |
| Unknown     | 8         | 10.13%  |
| 351-400     | 5         | 6.33%   |
| 601-700     | 4         | 5.06%   |
| 701-800     | 1         | 1.27%   |
| 901-1000    | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 58        | 78.38%  |
| 16/10   | 8         | 10.81%  |
| 5/4     | 2         | 2.7%    |
| 4/3     | 2         | 2.7%    |
| 21/9    | 2         | 2.7%    |
| Unknown | 2         | 2.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 15        | 19.23%  |
| 91-100         | 14        | 17.95%  |
| 81-90          | 10        | 12.82%  |
| 101-110        | 8         | 10.26%  |
| Unknown        | 8         | 10.26%  |
| 151-200        | 6         | 7.69%   |
| 351-500        | 4         | 5.13%   |
| 301-350        | 4         | 5.13%   |
| 61-70          | 2         | 2.56%   |
| 41-50          | 2         | 2.56%   |
| 251-300        | 2         | 2.56%   |
| 51-60          | 1         | 1.28%   |
| 121-130        | 1         | 1.28%   |
| 501-1000       | 1         | 1.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 36.36%  |
| 51-100  | 28        | 36.36%  |
| 121-160 | 12        | 15.58%  |
| Unknown | 8         | 10.39%  |
| 161-240 | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 48.34%  |
| 0     | 73        | 48.34%  |
| 2     | 5         | 3.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 82        | 39.81%  |
| Realtek Semiconductor            | 60        | 29.13%  |
| Qualcomm Atheros                 | 26        | 12.62%  |
| Broadcom                         | 15        | 7.28%   |
| Ralink Technology                | 2         | 0.97%   |
| Ralink                           | 2         | 0.97%   |
| Marvell Technology Group         | 2         | 0.97%   |
| Huawei Technologies              | 2         | 0.97%   |
| Sitecom Europe                   | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Samsung Electronics              | 1         | 0.49%   |
| OPPO Electronics                 | 1         | 0.49%   |
| Nvidia                           | 1         | 0.49%   |
| NetGear                          | 1         | 0.49%   |
| MediaTek                         | 1         | 0.49%   |
| JMicron Technology               | 1         | 0.49%   |
| IMC Networks                     | 1         | 0.49%   |
| Hewlett-Packard                  | 1         | 0.49%   |
| Edimax Technology                | 1         | 0.49%   |
| Digital Equipment                | 1         | 0.49%   |
| Davicom Semiconductor            | 1         | 0.49%   |
| Apple                            | 1         | 0.49%   |
| AMD                              | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 51        | 20.24%  |
| Intel I211 Gigabit Network Connection                                                 | 19        | 7.54%   |
| Intel I210 Gigabit Network Connection                                                 | 7         | 2.78%   |
| Intel Wireless 7265                                                                   | 6         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 1.98%   |
| Intel 82574L Gigabit Network Connection                                               | 5         | 1.98%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 1.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 3         | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 3         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 3         | 1.19%   |
| Intel Wireless 8260                                                                   | 3         | 1.19%   |
| Intel Wireless 3165                                                                   | 3         | 1.19%   |
| Intel I350 Gigabit Network Connection                                                 | 3         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 3         | 1.19%   |
| Intel 82579V Gigabit Network Connection                                               | 3         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 2         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.79%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 2         | 0.79%   |
| Intel Wireless 7260                                                                   | 2         | 0.79%   |
| Intel Ethernet Controller I225-V                                                      | 2         | 0.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                         | 2         | 0.79%   |
| Intel Ethernet Connection I217-LM                                                     | 2         | 0.79%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 0.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 0.79%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                         | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 0.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                                     | 1         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.4%    |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.4%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 0.4%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.4%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                              | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                            | 1         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 1         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                        | 1         | 0.4%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.4%    |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data                       | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                                                 | 1         | 0.4%    |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 33.75%  |
| Qualcomm Atheros      | 25        | 31.25%  |
| Realtek Semiconductor | 12        | 15%     |
| Broadcom              | 7         | 8.75%   |
| Ralink Technology     | 2         | 2.5%    |
| Ralink                | 2         | 2.5%    |
| Sitecom Europe        | 1         | 1.25%   |
| NetGear               | 1         | 1.25%   |
| MediaTek              | 1         | 1.25%   |
| IMC Networks          | 1         | 1.25%   |
| Edimax Technology     | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                                   | 6         | 7.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 6.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 6.02%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 3.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 3         | 3.61%   |
| Intel Wireless 8260                                                                   | 3         | 3.61%   |
| Intel Wireless 3165                                                                   | 3         | 3.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 2.41%   |
| Intel Wireless 7260                                                                   | 2         | 2.41%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 2.41%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 2.41%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1         | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 1.2%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 1.2%    |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.2%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 1.2%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.2%    |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.2%    |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.2%    |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 1.2%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 1.2%    |
| Intel Wireless-AC 9260                                                                | 1         | 1.2%    |
| Intel WiFi Link 5100                                                                  | 1         | 1.2%    |
| Intel Ultimate N WiFi Link 5300                                                       | 1         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 1.2%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.2%    |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                                  | 1         | 1.2%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1         | 1.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 1         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 70        | 45.45%  |
| Realtek Semiconductor            | 56        | 36.36%  |
| Broadcom                         | 9         | 5.84%   |
| Qualcomm Atheros                 | 8         | 5.19%   |
| Marvell Technology Group         | 2         | 1.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Samsung Electronics              | 1         | 0.65%   |
| OPPO Electronics                 | 1         | 0.65%   |
| Nvidia                           | 1         | 0.65%   |
| JMicron Technology               | 1         | 0.65%   |
| Digital Equipment                | 1         | 0.65%   |
| Davicom Semiconductor            | 1         | 0.65%   |
| Apple                            | 1         | 0.65%   |
| AMD                              | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 51        | 31.1%   |
| Intel I211 Gigabit Network Connection                                         | 19        | 11.59%  |
| Intel I210 Gigabit Network Connection                                         | 7         | 4.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6         | 3.66%   |
| Intel 82574L Gigabit Network Connection                                       | 5         | 3.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 1.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.83%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.83%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 1.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 1.22%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 1.22%   |
| Intel Ethernet Controller I225-V                                              | 2         | 1.22%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.22%   |
| Intel Ethernet Connection I217-LM                                             | 2         | 1.22%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.61%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data               | 1         | 0.61%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.61%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.61%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.61%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                          | 1         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1         | 0.61%   |
| Intel Ethernet Connection (2) I218-LM                                         | 1         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                         | 1         | 0.61%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                            | 1         | 0.61%   |
| Intel 82583V Gigabit Network Connection                                       | 1         | 0.61%   |
| Intel 82578DM Gigabit Network Connection                                      | 1         | 0.61%   |
| Intel 82577LC Gigabit Network Connection                                      | 1         | 0.61%   |
| Intel 82576 Gigabit Network Connection                                        | 1         | 0.61%   |
| Intel 82575EB Gigabit Network Connection                                      | 1         | 0.61%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.61%   |
| Intel 82571EB Gigabit Ethernet Controller                                     | 1         | 0.61%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 1         | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.61%   |
| Intel 82567LF-2 Gigabit Network Connection                                    | 1         | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.61%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                          | 1         | 0.61%   |
| Intel 82541GI Gigabit Ethernet Controller                                     | 1         | 0.61%   |
| Digital Equipment DECchip 21142/43                                            | 1         | 0.61%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 1         | 0.61%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.61%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1         | 0.61%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1         | 0.61%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express                       | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 139       | 63.76%  |
| WiFi     | 74        | 33.94%  |
| Modem    | 3         | 1.38%   |
| Unknown  | 2         | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 127       | 73.84%  |
| WiFi     | 45        | 26.16%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 68        | 45.95%  |
| 1     | 35        | 23.65%  |
| 3     | 15        | 10.14%  |
| 4     | 10        | 6.76%   |
| 5     | 6         | 4.05%   |
| 6     | 5         | 3.38%   |
| 7     | 3         | 2.03%   |
| 0     | 3         | 2.03%   |
| 8     | 2         | 1.35%   |
| 9     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 36%     |
| IMC Networks                    | 5         | 10%     |
| Cambridge Silicon Radio         | 5         | 10%     |
| Realtek Semiconductor           | 4         | 8%      |
| Qualcomm Atheros Communications | 4         | 8%      |
| Apple                           | 3         | 6%      |
| Lite-On Technology              | 2         | 4%      |
| Integrated System Solution      | 2         | 4%      |
| Broadcom                        | 2         | 4%      |
| Toshiba                         | 1         | 2%      |
| MediaTek                        | 1         | 2%      |
| Hewlett-Packard                 | 1         | 2%      |
| Foxconn / Hon Hai               | 1         | 2%      |
| ASUSTek Computer                | 1         | 2%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 28%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 10%     |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 4%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 4%      |
| Intel AX201 Bluetooth                                       | 2         | 4%      |
| Integrated System Solution Bluetooth Device                 | 2         | 4%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 4%      |
| IMC Networks Bluetooth Radio                                | 2         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 4%      |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 2%      |
| Realtek RTL8723B Bluetooth                                  | 1         | 2%      |
| Realtek  Bluetooth Adapter                                  | 1         | 2%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 2%      |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 2%      |
| MediaTek Wireless_Device                                    | 1         | 2%      |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 2%      |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 2%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 2%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 2%      |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 2%      |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 2%      |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 2%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 2%      |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 2%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96        | 62.34%  |
| AMD                              | 35        | 22.73%  |
| Nvidia                           | 15        | 9.74%   |
| C-Media Electronics              | 3         | 1.95%   |
| Silicon Integrated Systems [SiS] | 2         | 1.3%    |
| Logitech                         | 2         | 1.3%    |
| Bose                             | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.79%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.68%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 3.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.16%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.58%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 1.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 1.05%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.05%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.05%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 1.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.05%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.53%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.53%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Logitech Headset H340                                                                             | 1         | 0.53%   |
| Logitech HD Webcam C510                                                                           | 1         | 0.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.53%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 0.53%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.53%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 0.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.53%   |
| C-Media Electronics Audio Adapter (Planet UP-100, Genius G-Talk)                                  | 1         | 0.53%   |
| Bose Bose USB Audio                                                                               | 1         | 0.53%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.53%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 20.13%  |
| Kingston            | 23        | 14.47%  |
| SK hynix            | 22        | 13.84%  |
| Unknown             | 19        | 11.95%  |
| Micron Technology   | 10        | 6.29%   |
| Crucial             | 10        | 6.29%   |
| Unknown             | 8         | 5.03%   |
| Unknown (ABCD)      | 5         | 3.14%   |
| Ramaxel Technology  | 5         | 3.14%   |
| Nanya Technology    | 5         | 3.14%   |
| Corsair             | 4         | 2.52%   |
| Transcend           | 3         | 1.89%   |
| Unknown (F301)      | 1         | 0.63%   |
| Unknown (AB)        | 1         | 0.63%   |
| KomputerBay         | 1         | 0.63%   |
| Intersil            | 1         | 0.63%   |
| G.Skill             | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |
| Apacer              | 1         | 0.63%   |
| A-DATA Technology   | 1         | 0.63%   |
| 2C0C0843D7349CA2    | 1         | 0.63%   |
| 2C0C0843D7349C9D    | 1         | 0.63%   |
| 2C080815D82F5C7B    | 1         | 0.63%   |
| 2C0108214C359D20    | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown                                                           | 8         | 4.6%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 5         | 2.87%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 1.72%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s           | 3         | 1.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 1.15%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 2         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 2         | 1.15%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 1.15%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s             | 2         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s             | 2         | 1.15%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 2         | 1.15%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.15%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s           | 2         | 1.15%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 1.15%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                                 | 1         | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                         | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                           | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                         | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                          | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 256MB SODIMM DDR                               | 1         | 0.57%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                          | 1         | 0.57%   |
| Unknown (F301) RAM G2JT-4AFR00 16GB SODIMM DDR4 2400MT/s          | 1         | 0.57%   |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s               | 1         | 0.57%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s                | 1         | 0.57%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s              | 1         | 0.57%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 1         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.57%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.57%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.57%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.57%   |
| SK hynix RAM HYMP151P72CP4-Y5 4GB DIMM DDR2 667MT/s               | 1         | 0.57%   |
| SK hynix RAM HYMP125U72CP8-S6 2GB DIMM DDR2 800MT/s               | 1         | 0.57%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s               | 1         | 0.57%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s              | 1         | 0.57%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s                   | 1         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s            | 1         | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s            | 1         | 0.57%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s             | 1         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s            | 1         | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB Chip DDR4 2133MT/s           | 1         | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5273DH0-YK0 4GB DIMM DDR3 1600MT/s               | 1         | 0.57%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s             | 1         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 66        | 49.25%  |
| DDR4    | 32        | 23.88%  |
| DDR2    | 19        | 14.18%  |
| Unknown | 7         | 5.22%   |
| LPDDR4  | 6         | 4.48%   |
| SDRAM   | 2         | 1.49%   |
| LPDDR3  | 1         | 0.75%   |
| DDR     | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 55.3%   |
| DIMM         | 55        | 41.67%  |
| Chip         | 2         | 1.52%   |
| Row Of Chips | 1         | 0.76%   |
| FB-DIMM      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 56        | 38.62%  |
| 2048  | 33        | 22.76%  |
| 8192  | 31        | 21.38%  |
| 16384 | 17        | 11.72%  |
| 1024  | 5         | 3.45%   |
| 32768 | 2         | 1.38%   |
| 256   | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 24.14%  |
| 1333    | 21        | 14.48%  |
| 2400    | 16        | 11.03%  |
| 2667    | 14        | 9.66%   |
| 667     | 11        | 7.59%   |
| 1067    | 10        | 6.9%    |
| 800     | 10        | 6.9%    |
| 2133    | 7         | 4.83%   |
| 3200    | 5         | 3.45%   |
| Unknown | 4         | 2.76%   |
| 1334    | 3         | 2.07%   |
| 1066    | 3         | 2.07%   |
| 2933    | 1         | 0.69%   |
| 2666    | 1         | 0.69%   |
| 1867    | 1         | 0.69%   |
| 1866    | 1         | 0.69%   |
| 1200    | 1         | 0.69%   |
| 333     | 1         | 0.69%   |

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
| Chicony Electronics                    | 13        | 29.55%  |
| IMC Networks                           | 6         | 13.64%  |
| Realtek Semiconductor                  | 4         | 9.09%   |
| Acer                                   | 4         | 9.09%   |
| Sunplus Innovation Technology          | 3         | 6.82%   |
| ALi                                    | 3         | 6.82%   |
| Silicon Motion                         | 2         | 4.55%   |
| Microdia                               | 2         | 4.55%   |
| Logitech                               | 2         | 4.55%   |
| Suyin                                  | 1         | 2.27%   |
| Lite-On Technology                     | 1         | 2.27%   |
| KYE Systems (Mouse Systems)            | 1         | 2.27%   |
| Genesys Logic                          | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek Lenovo EasyCamera                                  | 2         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 4.55%   |
| Chicony Integrated Camera                                  | 2         | 4.55%   |
| Chicony HD WebCam (Acer)                                   | 2         | 4.55%   |
| ALi Gateway Webcam                                         | 2         | 4.55%   |
| Acer Integrated Camera                                     | 2         | 4.55%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.27%   |
| Sunplus Integrated Camera                                  | 1         | 2.27%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.27%   |
| Sunplus Aukey-PC-LM1E Camera                               | 1         | 2.27%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.27%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.27%   |
| Realtek USB Camera                                         | 1         | 2.27%   |
| Realtek Integrated_Webcam_HD                               | 1         | 2.27%   |
| Microdia Integrated_Webcam_HD                              | 1         | 2.27%   |
| Microdia ASUS USB2.0 Webcam                                | 1         | 2.27%   |
| Logitech Webcam C310                                       | 1         | 2.27%   |
| Logitech C505 HD Webcam                                    | 1         | 2.27%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.27%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera           | 1         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.27%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.27%   |
| IMC Networks Integrated Webcam                             | 1         | 2.27%   |
| IMC Networks Integrated Camera                             | 1         | 2.27%   |
| Genesys Logic Digital Microscope                           | 1         | 2.27%   |
| Chicony WebCam                                             | 1         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.27%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.27%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.27%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.27%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.27%   |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.27%   |
| Chicony 1.3M Webcam                                        | 1         | 2.27%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.27%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.27%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.27%   |
| Acer HD Webcam                                             | 1         | 2.27%   |

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
| 1     | 60        | 40%     |
| 0     | 48        | 32%     |
| 2     | 24        | 16%     |
| 3     | 16        | 10.67%  |
| 4     | 2         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 76        | 49.67%  |
| Net/wireless             | 20        | 13.07%  |
| Card reader              | 20        | 13.07%  |
| Bluetooth                | 16        | 10.46%  |
| Firewire controller      | 10        | 6.54%   |
| Fingerprint reader       | 6         | 3.92%   |
| Network                  | 2         | 1.31%   |
| Graphics card            | 2         | 1.31%   |
| Modem                    | 1         | 0.65%   |

