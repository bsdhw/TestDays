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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | 213D A01                    | Desktop     | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Dell          | 0VD5HY A00                  | Desktop     | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | Desktop     | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | Desktop     | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | Desktop     | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
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
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
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
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [139e702b9a](https://bsd-hardware.info/?probe=139e702b9a) | Mar 27, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
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
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
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
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [01a2dd5a52](https://bsd-hardware.info/?probe=01a2dd5a52) | Feb 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [2aa7735e59](https://bsd-hardware.info/?probe=2aa7735e59) | Jan 24, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | Desktop     | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.7.0 | 17        | 7.73%   |
| helloSystem 0.4.0 | 12        | 5.45%   |
| OpenBSD 7.1       | 9         | 4.09%   |
| helloSystem 0.5.0 | 9         | 4.09%   |
| OPNsense 22.7     | 7         | 3.18%   |
| helloSystem 0.6.0 | 6         | 2.73%   |
| OPNsense 22.1.6   | 5         | 2.27%   |
| OPNsense 21.1     | 5         | 2.27%   |
| helloSystem 0.8.0 | 5         | 2.27%   |
| helloSystem 0.3.0 | 5         | 2.27%   |
| FreeBSD 13.1      | 5         | 2.27%   |
| OPNsense 22.7.9   | 4         | 1.82%   |
| OPNsense 22.7.6   | 4         | 1.82%   |
| OPNsense 22.7.3   | 4         | 1.82%   |
| OPNsense 22.7.10  | 4         | 1.82%   |
| OPNsense 22.1.9   | 4         | 1.82%   |
| OPNsense 22.1     | 4         | 1.82%   |
| OPNsense 22.7.2   | 3         | 1.36%   |
| OPNsense 22.7.1   | 3         | 1.36%   |
| OPNsense 22.1.10  | 3         | 1.36%   |
| OPNsense 21.7.7   | 3         | 1.36%   |
| OPNsense 21.7.3   | 3         | 1.36%   |
| OPNsense 21.1.8   | 3         | 1.36%   |
| OPNsense 21.1.3   | 3         | 1.36%   |
| OPNsense 21.1.2   | 3         | 1.36%   |
| OPNsense 20.7.8   | 3         | 1.36%   |
| OpenBSD 6.8       | 3         | 1.36%   |
| NomadBSD 1.4      | 3         | 1.36%   |
| FreeBSD 13.0-p7   | 3         | 1.36%   |
| FreeBSD 12.2-p2   | 3         | 1.36%   |
| OPNsense 22.7.5   | 2         | 0.91%   |
| OPNsense 22.7.4   | 2         | 0.91%   |
| OPNsense 22.7.11  | 2         | 0.91%   |
| OPNsense 22.1.8   | 2         | 0.91%   |
| OPNsense 22.1.4   | 2         | 0.91%   |
| OPNsense 21.1.1   | 2         | 0.91%   |
| OpenBSD 7.2       | 2         | 0.91%   |
| NomadBSD 1.3.2    | 2         | 0.91%   |
| GhostBSD 21.08.27 | 2         | 0.91%   |
| GhostBSD 20.04.02 | 2         | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 65        | 37.57%  |
| helloSystem | 44        | 25.43%  |
| FreeBSD     | 30        | 17.34%  |
| OpenBSD     | 15        | 8.67%   |
| NomadBSD    | 7         | 4.05%   |
| NetBSD      | 7         | 4.05%   |
| GhostBSD    | 4         | 2.31%   |
| XigmaNAS    | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 166       | 96.51%  |
| i386   | 3         | 1.74%   |
| evbarm | 3         | 1.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 75        | 43.1%   |
| helloDesktop  | 50        | 28.74%  |
| XFCE          | 9         | 5.17%   |
| Openbox       | 7         | 4.02%   |
| KDE5          | 6         | 3.45%   |
| MATE          | 5         | 2.87%   |
| fvwm          | 4         | 2.3%    |
| CTWM          | 4         | 2.3%    |
| TWM           | 3         | 1.72%   |
| i3            | 3         | 1.72%   |
| Cinnamon      | 3         | 1.72%   |
| xfwm          | 2         | 1.15%   |
| LXQt          | 1         | 0.57%   |
| Fluxbox       | 1         | 0.57%   |
| Enlightenment | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 96        | 55.49%  |
| Console | 76        | 43.93%  |
| Wayland | 1         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 105       | 61.05%  |
| SLiM    | 56        | 32.56%  |
| LightDM | 6         | 3.49%   |
| SDDM    | 3         | 1.74%   |
| XDM     | 2         | 1.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 85        | 48.3%   |
| en_US            | 56        | 31.82%  |
| it_IT            | 14        | 7.95%   |
| C                | 13        | 7.39%   |
| it_IT.ISO8859-15 | 2         | 1.14%   |
| en               | 2         | 1.14%   |
| ru_RU            | 1         | 0.57%   |
| it_IT.ISO8859-1  | 1         | 0.57%   |
| it               | 1         | 0.57%   |
| en_GB            | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 140       | 80.46%  |
| BIOS | 34        | 19.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 83        | 46.89%  |
| Zfs    | 68        | 38.42%  |
| Ffs    | 15        | 8.47%   |
| Cd9660 | 11        | 6.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 151       | 86.78%  |
| MBR     | 19        | 10.92%  |
| Unknown | 4         | 2.3%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 28        | 16.28%  |
| Lenovo                     | 18        | 10.47%  |
| Unknown                    | 14        | 8.14%   |
| Hewlett-Packard            | 13        | 7.56%   |
| Dell                       | 13        | 7.56%   |
| Intel                      | 11        | 6.4%    |
| Acer                       | 7         | 4.07%   |
| MSI                        | 6         | 3.49%   |
| Gigabyte Technology        | 6         | 3.49%   |
| ASRock                     | 6         | 3.49%   |
| PC Engines                 | 5         | 2.91%   |
| Fujitsu                    | 5         | 2.91%   |
| BESSTAR Tech               | 4         | 2.33%   |
| Apple                      | 4         | 2.33%   |
| AMI                        | 3         | 1.74%   |
| ZOTAC                      | 2         | 1.16%   |
| Toshiba                    | 2         | 1.16%   |
| Supermicro                 | 2         | 1.16%   |
| Sophos                     | 2         | 1.16%   |
| Pegatron                   | 2         | 1.16%   |
| eMachines                  | 2         | 1.16%   |
| AZW                        | 2         | 1.16%   |
| TUXEDO                     | 1         | 0.58%   |
| T-bao                      | 1         | 0.58%   |
| Sun Microsystems           | 1         | 0.58%   |
| ShenZhen MinWin Technology | 1         | 0.58%   |
| Samsung Electronics        | 1         | 0.58%   |
| Raspberry Pi Foundation    | 1         | 0.58%   |
| Protectli                  | 1         | 0.58%   |
| Packard Bell               | 1         | 0.58%   |
| NF692                      | 1         | 0.58%   |
| MW                         | 1         | 0.58%   |
| Lex                        | 1         | 0.58%   |
| IBM                        | 1         | 0.58%   |
| HARDKERNEL                 | 1         | 0.58%   |
| Foxconn                    | 1         | 0.58%   |
| Deciso                     | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 14        | 8.14%   |
| PC Engines APU2                          | 3         | 1.74%   |
| BESSTAR Tech N40                         | 3         | 1.74%   |
| Sophos UTM                               | 2         | 1.16%   |
| MSI MS-7B86                              | 2         | 1.16%   |
| Lenovo ThinkCentre M83 10AHS35Q00        | 2         | 1.16%   |
| Intel Q3XXG4-P V1.0                      | 2         | 1.16%   |
| HP Laptop 15-da0xxx                      | 2         | 1.16%   |
| Fujitsu FUTRO S920                       | 2         | 1.16%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA   | 2         | 1.16%   |
| ASUS PRIME H410M-A                       | 2         | 1.16%   |
| ASUS M4A88TD-V EVO/USB3                  | 2         | 1.16%   |
| ASUS IP4BL-ME                            | 2         | 1.16%   |
| Apple MacBook4,1                         | 2         | 1.16%   |
| AMI Aptio CRB                            | 2         | 1.16%   |
| ZOTAC ZBOX-MI640/MI660/MI620NANO         | 1         | 0.58%   |
| ZOTAC ZBOX-CI323NANO                     | 1         | 0.58%   |
| TUXEDO N14xWU                            | 1         | 0.58%   |
| Toshiba Satellite C855-1U4               | 1         | 0.58%   |
| Toshiba PORTEGE M780                     | 1         | 0.58%   |
| T-bao MINI PC                            | 1         | 0.58%   |
| Supermicro X9SCI/X9SCA                   | 1         | 0.58%   |
| Supermicro X8STi                         | 1         | 0.58%   |
| Sun Microsystems Ultra 24                | 1         | 0.58%   |
| ShenZhen MinWin MW-NANO-APL-4L           | 1         | 0.58%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.58%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.58%   |
| Protectli FW4B                           | 1         | 0.58%   |
| Pegatron Pro 3405 Series                 | 1         | 0.58%   |
| Pegatron KX629AA-ABZ a6561.it            | 1         | 0.58%   |
| PC Engines apu4                          | 1         | 0.58%   |
| PC Engines APU3                          | 1         | 0.58%   |
| Packard Bell EasyNote_MX61-B-038         | 1         | 0.58%   |
| NF692 1.0                                | 1         | 0.58%   |
| MW GMLK-2_5G4L                           | 1         | 0.58%   |
| MSI NR074AA-ABZ CQ5125IT                 | 1         | 0.58%   |
| MSI MS-7922                              | 1         | 0.58%   |
| MSI KBL-U Pro Cubi 3 Silent S (MS-B159)  | 1         | 0.58%   |
| MSI GF65 Thin 10SER                      | 1         | 0.58%   |
| Lex Pineview-D                           | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 14        | 8.14%   |
| Lenovo ThinkPad                | 12        | 6.98%   |
| ASUS PRIME                     | 6         | 3.49%   |
| Dell PowerEdge                 | 4         | 2.33%   |
| PC Engines APU2                | 3         | 1.74%   |
| HP Compaq                      | 3         | 1.74%   |
| Dell Precision                 | 3         | 1.74%   |
| BESSTAR Tech N40               | 3         | 1.74%   |
| ASUS VivoBook                  | 3         | 1.74%   |
| Acer Aspire                    | 3         | 1.74%   |
| Sophos UTM                     | 2         | 1.16%   |
| MSI MS-7B86                    | 2         | 1.16%   |
| Lenovo ThinkCentre             | 2         | 1.16%   |
| Intel Q3XXG4-P                 | 2         | 1.16%   |
| HP Laptop                      | 2         | 1.16%   |
| Gigabyte X570                  | 2         | 1.16%   |
| Fujitsu FUTRO                  | 2         | 1.16%   |
| Fujitsu ESPRIMO                | 2         | 1.16%   |
| Dell Inspiron                  | 2         | 1.16%   |
| ASUS M4A88TD-V                 | 2         | 1.16%   |
| ASUS IP4BL-ME                  | 2         | 1.16%   |
| Apple MacBook4                 | 2         | 1.16%   |
| AMI Aptio                      | 2         | 1.16%   |
| ZOTAC ZBOX-MI640               | 1         | 0.58%   |
| ZOTAC ZBOX-CI323NANO           | 1         | 0.58%   |
| TUXEDO N14xWU                  | 1         | 0.58%   |
| Toshiba Satellite              | 1         | 0.58%   |
| Toshiba PORTEGE                | 1         | 0.58%   |
| T-bao MINI                     | 1         | 0.58%   |
| Supermicro X9SCI               | 1         | 0.58%   |
| Supermicro X8STi               | 1         | 0.58%   |
| Sun Microsystems Ultra         | 1         | 0.58%   |
| ShenZhen MinWin MW-NANO-APL-4L | 1         | 0.58%   |
| Samsung 3570R                  | 1         | 0.58%   |
| RPi Raspberry                  | 1         | 0.58%   |
| Protectli FW4B                 | 1         | 0.58%   |
| Pegatron Pro                   | 1         | 0.58%   |
| Pegatron KX629AA-ABZ           | 1         | 0.58%   |
| PC Engines apu4                | 1         | 0.58%   |
| PC Engines APU3                | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 17        | 9.88%   |
| 2021    | 14        | 8.14%   |
| 2016    | 14        | 8.14%   |
| 2014    | 14        | 8.14%   |
| 2011    | 14        | 8.14%   |
| 2018    | 13        | 7.56%   |
| 2010    | 12        | 6.98%   |
| 2020    | 11        | 6.4%    |
| 2012    | 11        | 6.4%    |
| 2022    | 9         | 5.23%   |
| 2013    | 9         | 5.23%   |
| 2008    | 8         | 4.65%   |
| 2015    | 7         | 4.07%   |
| 2009    | 7         | 4.07%   |
| 2017    | 6         | 3.49%   |
| Unknown | 3         | 1.74%   |
| 2007    | 2         | 1.16%   |
| 2006    | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 97        | 56.4%   |
| Notebook       | 55        | 31.98%  |
| Mini pc        | 11        | 6.4%    |
| Server         | 4         | 2.33%   |
| Firewall       | 2         | 1.16%   |
| All in one     | 2         | 1.16%   |
| System on chip | 1         | 0.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 167       | 97.09%  |
| Yes  | 5         | 2.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 65        | 37.14%  |
| 4.01-8.0    | 50        | 28.57%  |
| 16.01-24.0  | 23        | 13.14%  |
| 2.01-3.0    | 14        | 8%      |
| 32.01-64.0  | 13        | 7.43%   |
| 24.01-32.0  | 3         | 1.71%   |
| 64.01-256.0 | 3         | 1.71%   |
| 3.01-4.0    | 2         | 1.14%   |
| 0.51-1.0    | 1         | 0.57%   |
| 0.01-0.5    | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 105       | 59.32%  |
| 0.51-1.0   | 40        | 22.6%   |
| 1.01-2.0   | 12        | 6.78%   |
| 2.01-3.0   | 7         | 3.95%   |
| Unknown    | 7         | 3.95%   |
| 4.01-8.0   | 4         | 2.26%   |
| 24.01-32.0 | 1         | 0.56%   |
| 8.01-16.0  | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 63.48%  |
| 2      | 31        | 17.42%  |
| 0      | 13        | 7.3%    |
| 4      | 8         | 4.49%   |
| 3      | 7         | 3.93%   |
| 7      | 2         | 1.12%   |
| 10     | 1         | 0.56%   |
| 9      | 1         | 0.56%   |
| 6      | 1         | 0.56%   |
| 5      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 123       | 71.1%   |
| Yes       | 50        | 28.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 94.19%  |
| No        | 10        | 5.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 91        | 52.6%   |
| Yes       | 82        | 47.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 69.54%  |
| Yes       | 53        | 30.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 172       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milan                 | 23        | 11.39%  |
| Rome                  | 20        | 9.9%    |
| Turin                 | 6         | 2.97%   |
| Bologna               | 6         | 2.97%   |
| Trieste               | 4         | 1.98%   |
| Naples                | 3         | 1.49%   |
| Verona                | 2         | 0.99%   |
| Venice                | 2         | 0.99%   |
| Turrivalignani        | 2         | 0.99%   |
| Treviso               | 2         | 0.99%   |
| Silea                 | 2         | 0.99%   |
| Rho                   | 2         | 0.99%   |
| Reggio Emilia         | 2         | 0.99%   |
| Padova                | 2         | 0.99%   |
| Monterotondo          | 2         | 0.99%   |
| Modena                | 2         | 0.99%   |
| Lucca                 | 2         | 0.99%   |
| Gallarate             | 2         | 0.99%   |
| Catania               | 2         | 0.99%   |
| Brescia               | 2         | 0.99%   |
| Arezzo                | 2         | 0.99%   |
| Ancona                | 2         | 0.99%   |
| Adelfia               | 2         | 0.99%   |
| Viterbo               | 1         | 0.5%    |
| Villa Bartolomea      | 1         | 0.5%    |
| Vigonovo              | 1         | 0.5%    |
| Vanzago               | 1         | 0.5%    |
| Udine                 | 1         | 0.5%    |
| Trento                | 1         | 0.5%    |
| Terni                 | 1         | 0.5%    |
| Soresina              | 1         | 0.5%    |
| Solarino              | 1         | 0.5%    |
| Sesto San Giovanni    | 1         | 0.5%    |
| Selvazzano Dentro     | 1         | 0.5%    |
| Sasso Marconi         | 1         | 0.5%    |
| Saronno               | 1         | 0.5%    |
| Sarno                 | 1         | 0.5%    |
| Sannicandro di Bari   | 1         | 0.5%    |
| San Vincenzo La Costa | 1         | 0.5%    |
| San Prospero          | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 64     | 14.16%  |
| Seagate             | 27        | 54     | 12.33%  |
| Samsung Electronics | 26        | 45     | 11.87%  |
| Crucial             | 18        | 31     | 8.22%   |
| Toshiba             | 17        | 37     | 7.76%   |
| Kingston            | 15        | 17     | 6.85%   |
| Transcend           | 11        | 16     | 5.02%   |
| SanDisk             | 10        | 11     | 4.57%   |
| Hitachi             | 7         | 9      | 3.2%    |
| Emtec               | 4         | 6      | 1.83%   |
| PNY                 | 3         | 7      | 1.37%   |
| OCZ                 | 3         | 3      | 1.37%   |
| NVMe                | 3         | 3      | 1.37%   |
| Micron Technology   | 3         | 3      | 1.37%   |
| KingSpec            | 3         | 4      | 1.37%   |
| Intel               | 3         | 4      | 1.37%   |
| Innodisk            | 3         | 5      | 1.37%   |
| Hoodisk             | 3         | 3      | 1.37%   |
| Phison              | 2         | 2      | 0.91%   |
| Maxtor              | 2         | 2      | 0.91%   |
| Leven               | 2         | 2      | 0.91%   |
| HGST                | 2         | 2      | 0.91%   |
| Dogfish             | 2         | 2      | 0.91%   |
| China               | 2         | 4      | 0.91%   |
| A-DATA Technology   | 2         | 3      | 0.91%   |
| Union Memory        | 1         | 1      | 0.46%   |
| SK hynix            | 1         | 1      | 0.46%   |
| Silicon Motion      | 1         | 2      | 0.46%   |
| Plextor             | 1         | 1      | 0.46%   |
| Pccooler            | 1         | 1      | 0.46%   |
| KingDian            | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| Indilinx            | 1         | 1      | 0.46%   |
| Fujitsu             | 1         | 1      | 0.46%   |
| FORESEE             | 1         | 2      | 0.46%   |
| Fanxiang            | 1         | 1      | 0.46%   |
| Corsair             | 1         | 2      | 0.46%   |
| BAITITON            | 1         | 1      | 0.46%   |
| ASUSTek Computer    | 1         | 2      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB    | 5         | 2.07%   |
| Samsung SSD 860 EVO 250GB       | 4         | 1.66%   |
| Samsung SSD 860 EVO 500GB       | 3         | 1.24%   |
| Samsung SSD 850 EVO 500GB       | 3         | 1.24%   |
| Samsung SSD 850 EVO 250GB       | 3         | 1.24%   |
| Emtec X150 120GB                | 3         | 1.24%   |
| Crucial CT500MX500SSD1 500GB    | 3         | 1.24%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2         | 0.83%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2         | 0.83%   |
| Transcend TS256GMTS430S 256GB   | 2         | 0.83%   |
| Toshiba MQ04ABF100 1TB          | 2         | 0.83%   |
| Toshiba MQ01ABD100 1TB          | 2         | 0.83%   |
| Toshiba HDWG440 4TB             | 2         | 0.83%   |
| Toshiba DT01ACA050 500GB        | 2         | 0.83%   |
| Seagate ST320LT007-9ZV142 320GB | 2         | 0.83%   |
| Seagate ST1000DM003-1ER162 1TB  | 2         | 0.83%   |
| SanDisk SDSSDP128G 128GB        | 2         | 0.83%   |
| Samsung SSD 970 EVO 250GB       | 2         | 0.83%   |
| Samsung HM321HI 320GB           | 2         | 0.83%   |
| PNY CS900 120GB SSD             | 2         | 0.83%   |
| Phison SATA SSD 16GB            | 2         | 0.83%   |
| OCZ VERTEX3 120GB               | 2         | 0.83%   |
| NVMe Samsung SSD 980 1TB        | 2         | 0.83%   |
| Kingston SV300S37A120G 120GB    | 2         | 0.83%   |
| Kingston SEDC500M480G 480GB     | 2         | 0.83%   |
| Kingston SA400S37240G 240GB     | 2         | 0.83%   |
| Kingston SA400S37120G 120GB     | 2         | 0.83%   |
| KingSpec Q-720 720GB            | 2         | 0.83%   |
| Innodisk DEMSR- 16GB mSATA 3ME3 | 2         | 0.83%   |
| Hoodisk SSD 256GB               | 2         | 0.83%   |
| Crucial CT250MX500SSD1 250GB    | 2         | 0.83%   |
| Crucial CT120BX500SSD1 120GB    | 2         | 0.83%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB    | 1         | 0.41%   |
| WDC WDS100T2B0B-00YS70 1TB      | 1         | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1         | 0.41%   |
| WDC WD6400AAKS-65A7B0 640GB     | 1         | 0.41%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1         | 0.41%   |
| WDC WD5000LPVT-80G33T2 500GB    | 1         | 0.41%   |
| WDC WD5000BPKX-60HPJT0 500GB    | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 54     | 32.53%  |
| WDC                 | 25        | 57     | 30.12%  |
| Toshiba             | 15        | 32     | 18.07%  |
| Hitachi             | 7         | 9      | 8.43%   |
| Samsung Electronics | 3         | 3      | 3.61%   |
| Maxtor              | 2         | 2      | 2.41%   |
| HGST                | 2         | 2      | 2.41%   |
| NVMe                | 1         | 1      | 1.2%    |
| Fujitsu             | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 35     | 15.7%   |
| Crucial             | 17        | 30     | 14.05%  |
| Transcend           | 10        | 15     | 8.26%   |
| SanDisk             | 10        | 11     | 8.26%   |
| Kingston            | 10        | 11     | 8.26%   |
| WDC                 | 6         | 6      | 4.96%   |
| Emtec               | 4         | 6      | 3.31%   |
| PNY                 | 3         | 7      | 2.48%   |
| OCZ                 | 3         | 3      | 2.48%   |
| KingSpec            | 3         | 4      | 2.48%   |
| Intel               | 3         | 4      | 2.48%   |
| Innodisk            | 3         | 5      | 2.48%   |
| Hoodisk             | 3         | 3      | 2.48%   |
| Toshiba             | 2         | 5      | 1.65%   |
| Phison              | 2         | 2      | 1.65%   |
| NVMe                | 2         | 2      | 1.65%   |
| Micron Technology   | 2         | 2      | 1.65%   |
| Leven               | 2         | 2      | 1.65%   |
| Dogfish             | 2         | 2      | 1.65%   |
| China               | 2         | 4      | 1.65%   |
| A-DATA Technology   | 2         | 3      | 1.65%   |
| SK hynix            | 1         | 1      | 0.83%   |
| Plextor             | 1         | 1      | 0.83%   |
| Pccooler            | 1         | 1      | 0.83%   |
| KingDian            | 1         | 1      | 0.83%   |
| Intenso             | 1         | 1      | 0.83%   |
| Indilinx            | 1         | 1      | 0.83%   |
| FORESEE             | 1         | 2      | 0.83%   |
| Corsair             | 1         | 2      | 0.83%   |
| BAITITON            | 1         | 1      | 0.83%   |
| ASUSTek Computer    | 1         | 2      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 103       | 176    | 55.68%  |
| HDD  | 64        | 161    | 34.59%  |
| NVMe | 18        | 21     | 9.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 337    | 89.22%  |
| NVMe | 18        | 21     | 10.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 126       | 228    | 72.41%  |
| 0.51-1.0   | 28        | 65     | 16.09%  |
| 1.01-2.0   | 8         | 12     | 4.6%    |
| 3.01-4.0   | 7         | 15     | 4.02%   |
| 2.01-3.0   | 2         | 5      | 1.15%   |
| 4.01-10.0  | 2         | 4      | 1.15%   |
| 10.01-20.0 | 1         | 8      | 0.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 28.81%  |
| 1-20           | 50        | 28.25%  |
| 251-500        | 31        | 17.51%  |
| 21-50          | 15        | 8.47%   |
| 51-100         | 13        | 7.34%   |
| 501-1000       | 12        | 6.78%   |
| More than 3000 | 3         | 1.69%   |
| 1001-2000      | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 156       | 88.14%  |
| 21-50          | 11        | 6.21%   |
| 51-100         | 4         | 2.26%   |
| 501-1000       | 2         | 1.13%   |
| More than 3000 | 1         | 0.56%   |
| 101-250        | 1         | 0.56%   |
| 1001-2000      | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB       | 2         | 2      | 6.45%   |
| Seagate ST320LT007-9ZV142 320GB   | 2         | 2      | 6.45%   |
| OCZ VERTEX3 120GB                 | 2         | 2      | 6.45%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1         | 2      | 3.23%   |
| WDC WD5000AAKS-00E4A0 500GB       | 1         | 1      | 3.23%   |
| WDC WD20EVDS-63T3B0 2TB           | 1         | 1      | 3.23%   |
| WDC WD2002FYPS-01U1B1 2TB         | 1         | 1      | 3.23%   |
| WDC WD1000DHTZ-04N21V1 1TB        | 1         | 2      | 3.23%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 3.23%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 3.23%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB   | 1         | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 5      | 3.23%   |
| Seagate ST4000LM024-2AN17V 4TB    | 1         | 1      | 3.23%   |
| Seagate ST31500341AS 1.5TB        | 1         | 1      | 3.23%   |
| SanDisk SDSSDP064G 64GB           | 1         | 1      | 3.23%   |
| SanDisk SD9SN8W-128G-1006 128GB   | 1         | 1      | 3.23%   |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB      | 1         | 1      | 3.23%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 3.23%   |
| Hitachi HTS548040M9AT00 37GB      | 1         | 2      | 3.23%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 3.23%   |
| Hitachi HDS723030ALA640 3TB       | 1         | 2      | 3.23%   |
| HGST HTS541075A9E680 752GB        | 1         | 1      | 3.23%   |
| Crucial CT525MX300SSD1 528GB      | 1         | 3      | 3.23%   |
| China SATA3 240GB SSD             | 1         | 1      | 3.23%   |
| A-DATA Technology SX300 128GB     | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 13     | 29.03%  |
| WDC                 | 7         | 9      | 22.58%  |
| Hitachi             | 3         | 5      | 9.68%   |
| SanDisk             | 2         | 2      | 6.45%   |
| OCZ                 | 2         | 2      | 6.45%   |
| Toshiba             | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Crucial             | 1         | 3      | 3.23%   |
| China               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 13     | 40.91%  |
| WDC                 | 7         | 9      | 31.82%  |
| Hitachi             | 3         | 5      | 13.64%  |
| Toshiba             | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 30     | 68.97%  |
| SSD  | 9         | 11     | 31.03%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 136       | 297    | 77.71%  |
| Malfunc  | 29        | 41     | 16.57%  |
| Detected | 10        | 20     | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 126       | 62.69%  |
| AMD                              | 32        | 15.92%  |
| Samsung Electronics              | 9         | 4.48%   |
| Kingston Technology Company      | 5         | 2.49%   |
| Broadcom / LSI                   | 4         | 1.99%   |
| ASMedia Technology               | 4         | 1.99%   |
| Marvell Technology Group         | 3         | 1.49%   |
| VIA Technologies                 | 2         | 1%      |
| Silicon Integrated Systems [SiS] | 2         | 1%      |
| JMicron Technology               | 2         | 1%      |
| Union Memory (Shenzhen)          | 1         | 0.5%    |
| Transcend                        | 1         | 0.5%    |
| Silicon Motion                   | 1         | 0.5%    |
| Silicon Image                    | 1         | 0.5%    |
| SanDisk                          | 1         | 0.5%    |
| Nvidia                           | 1         | 0.5%    |
| Micron/Crucial Technology        | 1         | 0.5%    |
| Micron Technology                | 1         | 0.5%    |
| MAXIO Technology (Hangzhou)      | 1         | 0.5%    |
| KIOXIA                           | 1         | 0.5%    |
| Integrated Technology Express    | 1         | 0.5%    |
| Adaptec                          | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 9.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 4.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 3.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 3%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 6         | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 2.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 2.58%   |
| Unknown                                                                          | 6         | 2.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 4         | 1.72%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.29%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                           | 3         | 1.29%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.29%   |
| VIA VT6415 PATA IDE Host Controller                                              | 2         | 0.86%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.86%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 0.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 0.86%   |
| AMD FCH SATA Controller [IDE mode]                                               | 2         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 67.33%  |
| IDE  | 33        | 16.34%  |
| NVMe | 21        | 10.4%   |
| RAID | 9         | 4.46%   |
| SCSI | 3         | 1.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 135       | 78.49%  |
| AMD      | 34        | 19.77%  |
| Broadcom | 1         | 0.58%   |
| Arm      | 1         | 0.58%   |
| Unknown  | 1         | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                              | 5         | 2.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.31%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 4         | 2.31%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 4         | 2.31%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.73%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.73%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 1.73%   |
| AMD Phenom II X4 965 Processor                | 3         | 1.73%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 1.16%   |
| Intel Pentium CPU G3220 @ 3.00GHz             | 2         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.16%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.16%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.16%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2         | 1.16%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 2         | 1.16%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2         | 1.16%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.16%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 1.16%   |
| Intel Celeron CPU J3355 @ 2.00GHz             | 2         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.16%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 2         | 1.16%   |
| Intel Xeon Silver 4214R CPU @ 2.40GHz         | 1         | 0.58%   |
| Intel Xeon E-2236 CPU @ 3.40GHz               | 1         | 0.58%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.58%   |
| Intel Xeon CPU X3470 @ 2.93GHz                | 1         | 0.58%   |
| Intel Xeon CPU W3520 @ 2.67GHz                | 1         | 0.58%   |
| Intel Xeon CPU E5440 @ 2.83GHz                | 1         | 0.58%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.58%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH             | 1         | 0.58%   |
| Intel Xeon CPU E31245 @ 3.30GHz               | 1         | 0.58%   |
| Intel Xeon CPU E31245 @ 3.30GH                | 1         | 0.58%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.58%   |
| Intel Xeon CPU E3113 @ 3.00GHz                | 1         | 0.58%   |
| Intel Xeon CPU E3-1220 v6 @ 3.00GHz           | 1         | 0.58%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz      | 1         | 0.58%   |
| Intel Pentium M processor                     | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 16.76%  |
| Intel Celeron           | 27        | 15.61%  |
| Intel Core i7           | 14        | 8.09%   |
| Intel Core i3           | 13        | 7.51%   |
| Intel Xeon              | 12        | 6.94%   |
| Intel Atom              | 11        | 6.36%   |
| Intel Pentium           | 8         | 4.62%   |
| Intel Core 2 Duo        | 8         | 4.62%   |
| AMD GX                  | 8         | 4.62%   |
| AMD Ryzen 5             | 7         | 4.05%   |
| Other                   | 5         | 2.89%   |
| Intel Pentium Dual-Core | 4         | 2.31%   |
| Intel Pentium Dual      | 3         | 1.73%   |
| AMD Ryzen 9             | 3         | 1.73%   |
| AMD Phenom II X4        | 3         | 1.73%   |
| AMD Ryzen 7             | 2         | 1.16%   |
| Intel Xeon Silver       | 1         | 0.58%   |
| Intel Pentium Silver    | 1         | 0.58%   |
| Intel Pentium M         | 1         | 0.58%   |
| Intel Core 2 Quad       | 1         | 0.58%   |
| Intel Core 2 Extreme    | 1         | 0.58%   |
| Intel 686-class         | 1         | 0.58%   |
| AMD Turion 64 X2 Mobile | 1         | 0.58%   |
| AMD Ryzen Embedded      | 1         | 0.58%   |
| AMD Ryzen 7 PRO         | 1         | 0.58%   |
| AMD Ryzen 3             | 1         | 0.58%   |
| AMD FX                  | 1         | 0.58%   |
| AMD E2                  | 1         | 0.58%   |
| AMD E1                  | 1         | 0.58%   |
| AMD Athlon II X4        | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |
| AMD A4                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 71        | 41.04%  |
| 4       | 58        | 33.53%  |
| Unknown | 16        | 9.25%   |
| 12      | 7         | 4.05%   |
| 8       | 7         | 4.05%   |
| 1       | 6         | 3.47%   |
| 16      | 3         | 1.73%   |
| 6       | 3         | 1.73%   |
| 32      | 1         | 0.58%   |
| 24      | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 164       | 94.8%   |
| 2       | 5         | 2.89%   |
| Unknown | 4         | 2.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 86        | 49.71%  |
| 2       | 71        | 41.04%  |
| Unknown | 16        | 9.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| SandyBridge   | 16        | 9.25%   |
| KabyLake      | 15        | 8.67%   |
| Penryn        | 14        | 8.09%   |
| Haswell       | 12        | 6.94%   |
| Silvermont    | 11        | 6.36%   |
| Bonnell       | 10        | 5.78%   |
| IvyBridge     | 9         | 5.2%    |
| Goldmont plus | 8         | 4.62%   |
| Broadwell     | 8         | 4.62%   |
| Unknown       | 8         | 4.62%   |
| Skylake       | 6         | 3.47%   |
| Puma          | 6         | 3.47%   |
| Zen+          | 5         | 2.89%   |
| Zen 3         | 5         | 2.89%   |
| Westmere      | 5         | 2.89%   |
| Jaguar        | 5         | 2.89%   |
| Core          | 5         | 2.89%   |
| CometLake     | 5         | 2.89%   |
| K10           | 4         | 2.31%   |
| Goldmont      | 4         | 2.31%   |
| Zen           | 3         | 1.73%   |
| Nehalem       | 3         | 1.73%   |
| Zen 2         | 2         | 1.16%   |
| Piledriver    | 1         | 0.58%   |
| P6            | 1         | 0.58%   |
| K8 Hammer     | 1         | 0.58%   |
| K10 Llano     | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 59.88%  |
| AMD                              | 41        | 23.84%  |
| Nvidia                           | 21        | 12.21%  |
| Matrox Electronics Systems       | 5         | 2.91%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| ASPEED Technology                | 1         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 6.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 3.98%   |
| Intel HD Graphics 620                                                                    | 6         | 3.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 3.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 3.41%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 3.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.84%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.27%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.27%   |
| Intel HD Graphics 500                                                                    | 4         | 2.27%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 2.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.27%   |
| Intel HD Graphics 6000                                                                   | 3         | 1.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 1.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.14%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.14%   |
| Intel HD Graphics 630                                                                    | 2         | 1.14%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 1.14%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2         | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.14%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.14%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.57%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 47.98%  |
| 1 x AMD        | 38        | 21.97%  |
| 1 x Nvidia     | 14        | 8.09%   |
| 2 x Intel      | 11        | 6.36%   |
| Other          | 10        | 5.78%   |
| Intel + Nvidia | 7         | 4.05%   |
| 1 x Matrox     | 5         | 2.89%   |
| Intel + AMD    | 2         | 1.16%   |
| 2 x AMD        | 1         | 0.58%   |
| 1 x SiS        | 1         | 0.58%   |
| 1 x ASPEED     | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 147       | 83.52%  |
| Unknown     | 15        | 8.52%   |
| Proprietary | 14        | 7.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 79.31%  |
| 0.01-0.5   | 12        | 6.9%    |
| 1.01-2.0   | 10        | 5.75%   |
| 3.01-4.0   | 6         | 3.45%   |
| 0.51-1.0   | 6         | 3.45%   |
| 7.01-8.0   | 1         | 0.57%   |
| 5.01-6.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 13        | 14.29%  |
| Philips              | 11        | 12.09%  |
| Samsung Electronics  | 10        | 10.99%  |
| LG Display           | 9         | 9.89%   |
| Acer                 | 6         | 6.59%   |
| Hewlett-Packard      | 5         | 5.49%   |
| Chimei Innolux       | 5         | 5.49%   |
| BOE                  | 5         | 5.49%   |
| Dell                 | 4         | 4.4%    |
| Apple                | 4         | 4.4%    |
| Goldstar             | 3         | 3.3%    |
| Lenovo               | 2         | 2.2%    |
| HannStar             | 2         | 2.2%    |
| ___                  | 1         | 1.1%    |
| Sony                 | 1         | 1.1%    |
| Packard Bell         | 1         | 1.1%    |
| Orion                | 1         | 1.1%    |
| Mi                   | 1         | 1.1%    |
| LG Philips           | 1         | 1.1%    |
| LG Electronics       | 1         | 1.1%    |
| Iiyama               | 1         | 1.1%    |
| Fujitsu Siemens      | 1         | 1.1%    |
| Eizo                 | 1         | 1.1%    |
| ASUSTek Computer     | 1         | 1.1%    |
| Ancor Communications | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 9         | 9.89%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 2         | 2.2%    |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch        | 2         | 2.2%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch        | 2         | 2.2%    |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                      | 2         | 2.2%    |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 1.1%    |
| Sony TV SNY5D01 1360x768                                             | 1         | 1.1%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 1         | 1.1%    |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                     | 1         | 1.1%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch    | 1         | 1.1%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch    | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1         | 1.1%    |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch             | 1         | 1.1%    |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch             | 1         | 1.1%    |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch       | 1         | 1.1%    |
| Orion LCD Monitor ORN1207 1920x1080                                  | 1         | 1.1%    |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                     | 1         | 1.1%    |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch          | 1         | 1.1%    |
| LG Electronics LCD Monitor E2360 1920x1080                           | 1         | 1.1%    |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch         | 1         | 1.1%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 1.1%    |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch         | 1         | 1.1%    |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 1         | 1.1%    |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch          | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40A3 1920x1080 310x170mm 13.9-inch             | 1         | 1.1%    |
| Iiyama PLE2403WS IVM5604 1920x1200 520x330mm 24.2-inch               | 1         | 1.1%    |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch    | 1         | 1.1%    |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch            | 1         | 1.1%    |
| Hewlett-Packard 27f HPN354A 1920x1080 600x340mm 27.2-inch            | 1         | 1.1%    |
| Hewlett-Packard 24fw HPN3605 1920x1080 530x300mm 24.0-inch           | 1         | 1.1%    |
| Hewlett-Packard 22cw HWP3183 1920x1080 480x270mm 21.7-inch           | 1         | 1.1%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 47.13%  |
| 1366x768 (WXGA)   | 22        | 25.29%  |
| 1440x900 (WXGA+)  | 4         | 4.6%    |
| 1600x900 (HD+)    | 3         | 3.45%   |
| 1280x1024 (SXGA)  | 3         | 3.45%   |
| 2560x1080         | 2         | 2.3%    |
| 1920x1200 (WUXGA) | 2         | 2.3%    |
| 1280x800 (WXGA)   | 2         | 2.3%    |
| 1024x600          | 2         | 2.3%    |
| 3840x2400         | 1         | 1.15%   |
| 3840x2160 (4K)    | 1         | 1.15%   |
| 2560x1440 (QHD)   | 1         | 1.15%   |
| 1600x1200         | 1         | 1.15%   |
| 1360x768          | 1         | 1.15%   |
| 1024x768 (XGA)    | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 25.27%  |
| 21      | 11        | 12.09%  |
| 13      | 11        | 12.09%  |
| Unknown | 8         | 8.79%   |
| 24      | 7         | 7.69%   |
| 27      | 6         | 6.59%   |
| 23      | 5         | 5.49%   |
| 19      | 4         | 4.4%    |
| 31      | 2         | 2.2%    |
| 18      | 2         | 2.2%    |
| 12      | 2         | 2.2%    |
| 10      | 2         | 2.2%    |
| 39      | 1         | 1.1%    |
| 34      | 1         | 1.1%    |
| 28      | 1         | 1.1%    |
| 22      | 1         | 1.1%    |
| 20      | 1         | 1.1%    |
| 17      | 1         | 1.1%    |
| 14      | 1         | 1.1%    |
| 11      | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 32        | 35.96%  |
| 501-600     | 16        | 17.98%  |
| 401-500     | 14        | 15.73%  |
| 201-300     | 8         | 8.99%   |
| Unknown     | 8         | 8.99%   |
| 351-400     | 5         | 5.62%   |
| 601-700     | 4         | 4.49%   |
| 701-800     | 1         | 1.12%   |
| 901-1000    | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 67        | 79.76%  |
| 16/10   | 9         | 10.71%  |
| 5/4     | 2         | 2.38%   |
| 4/3     | 2         | 2.38%   |
| 21/9    | 2         | 2.38%   |
| Unknown | 2         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 20        | 22.73%  |
| 91-100         | 15        | 17.05%  |
| 81-90          | 11        | 12.5%   |
| 101-110        | 8         | 9.09%   |
| Unknown        | 8         | 9.09%   |
| 301-350        | 6         | 6.82%   |
| 151-200        | 6         | 6.82%   |
| 351-500        | 4         | 4.55%   |
| 61-70          | 2         | 2.27%   |
| 41-50          | 2         | 2.27%   |
| 251-300        | 2         | 2.27%   |
| 51-60          | 1         | 1.14%   |
| 121-130        | 1         | 1.14%   |
| 111-120        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 32        | 36.78%  |
| 51-100        | 32        | 36.78%  |
| 121-160       | 13        | 14.94%  |
| Unknown       | 8         | 9.2%    |
| More than 240 | 1         | 1.15%   |
| 161-240       | 1         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 88        | 50%     |
| 1     | 83        | 47.16%  |
| 2     | 5         | 2.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 98        | 40.66%  |
| Realtek Semiconductor            | 72        | 29.88%  |
| Qualcomm Atheros                 | 28        | 11.62%  |
| Broadcom                         | 17        | 7.05%   |
| Ralink Technology                | 4         | 1.66%   |
| Ralink                           | 2         | 0.83%   |
| Marvell Technology Group         | 2         | 0.83%   |
| Huawei Technologies              | 2         | 0.83%   |
| Sitecom Europe                   | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Samsung Electronics              | 1         | 0.41%   |
| OPPO Electronics                 | 1         | 0.41%   |
| Nvidia                           | 1         | 0.41%   |
| NetGear                          | 1         | 0.41%   |
| MediaTek                         | 1         | 0.41%   |
| JMicron Technology               | 1         | 0.41%   |
| IMC Networks                     | 1         | 0.41%   |
| Hewlett-Packard                  | 1         | 0.41%   |
| Google                           | 1         | 0.41%   |
| Edimax Technology                | 1         | 0.41%   |
| Digital Equipment                | 1         | 0.41%   |
| Davicom Semiconductor            | 1         | 0.41%   |
| Apple                            | 1         | 0.41%   |
| AMD                              | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 63        | 21.58%  |
| Intel I211 Gigabit Network Connection                                         | 22        | 7.53%   |
| Intel I210 Gigabit Network Connection                                         | 8         | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.4%    |
| Intel 82574L Gigabit Network Connection                                       | 7         | 2.4%    |
| Intel Wireless 7265                                                           | 6         | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 5         | 1.71%   |
| Intel Wireless 8265 / 8275                                                    | 4         | 1.37%   |
| Intel Wireless 8260                                                           | 4         | 1.37%   |
| Intel Wireless 3165                                                           | 4         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 1.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 3         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 3         | 1.03%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.03%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.03%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.03%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 2         | 0.68%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.68%   |
| Intel Wireless 7260                                                           | 2         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 2         | 0.68%   |
| Intel Ethernet Controller I225-V                                              | 2         | 0.68%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 0.68%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.68%   |
| Intel 82575EB Gigabit Network Connection                                      | 2         | 0.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.68%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 2         | 0.68%   |
| Broadcom BCM43225 802.11b/g/n                                                 | 2         | 0.68%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 34.44%  |
| Qualcomm Atheros      | 27        | 30%     |
| Realtek Semiconductor | 13        | 14.44%  |
| Broadcom              | 8         | 8.89%   |
| Ralink Technology     | 4         | 4.44%   |
| Ralink                | 2         | 2.22%   |
| Sitecom Europe        | 1         | 1.11%   |
| NetGear               | 1         | 1.11%   |
| MediaTek              | 1         | 1.11%   |
| IMC Networks          | 1         | 1.11%   |
| Edimax Technology     | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                                   | 6         | 6.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 5.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 5         | 5.38%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.3%    |
| Intel Wireless 8260                                                                   | 4         | 4.3%    |
| Intel Wireless 3165                                                                   | 4         | 4.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 3.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 3.23%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 3         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 2.15%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 2.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 2.15%   |
| Intel Wireless 7260                                                                   | 2         | 2.15%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 2.15%   |
| Broadcom BCM43228 802.11a/b/g/n                                                       | 2         | 2.15%   |
| Broadcom BCM43225 802.11b/g/n                                                         | 2         | 2.15%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 2         | 2.15%   |
| Sitecom Europe 802.11n WLAN Adapter                                                   | 1         | 1.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1         | 1.08%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 1         | 1.08%   |
| Ralink RT5572 Wireless Adapter                                                        | 1         | 1.08%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.08%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                | 1         | 1.08%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 1.08%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter                       | 1         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.08%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.08%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                                       | 1         | 1.08%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 1.08%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.08%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 84        | 46.41%  |
| Realtek Semiconductor            | 68        | 37.57%  |
| Broadcom                         | 10        | 5.52%   |
| Qualcomm Atheros                 | 8         | 4.42%   |
| Marvell Technology Group         | 2         | 1.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Samsung Electronics              | 1         | 0.55%   |
| OPPO Electronics                 | 1         | 0.55%   |
| Nvidia                           | 1         | 0.55%   |
| JMicron Technology               | 1         | 0.55%   |
| Digital Equipment                | 1         | 0.55%   |
| Davicom Semiconductor            | 1         | 0.55%   |
| Apple                            | 1         | 0.55%   |
| AMD                              | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 63        | 32.64%  |
| Intel I211 Gigabit Network Connection                                         | 22        | 11.4%   |
| Intel I210 Gigabit Network Connection                                         | 8         | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 3.63%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 3         | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 3         | 1.55%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.55%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 1.55%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.55%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 1.55%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 1.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 1.04%   |
| Intel Ethernet Controller I225-V                                              | 2         | 1.04%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 2         | 1.04%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 1.04%   |
| Intel 82575EB Gigabit Network Connection                                      | 2         | 1.04%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 1.04%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 2         | 1.04%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                 | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.52%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                                | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 1         | 0.52%   |
| Intel Ethernet Controller I226-V                                              | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                              | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                              | 1         | 0.52%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                          | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 162       | 64.8%   |
| WiFi     | 82        | 32.8%   |
| Modem    | 3         | 1.2%    |
| Unknown  | 3         | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 75.9%   |
| WiFi     | 47        | 24.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 43.93%  |
| 1     | 42        | 24.28%  |
| 3     | 17        | 9.83%   |
| 4     | 14        | 8.09%   |
| 6     | 8         | 4.62%   |
| 5     | 7         | 4.05%   |
| 7     | 3         | 1.73%   |
| 0     | 3         | 1.73%   |
| 8     | 2         | 1.16%   |
| 9     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 172       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 37.5%   |
| Qualcomm Atheros Communications | 6         | 10.71%  |
| Realtek Semiconductor           | 5         | 8.93%   |
| IMC Networks                    | 5         | 8.93%   |
| Cambridge Silicon Radio         | 5         | 8.93%   |
| Apple                           | 3         | 5.36%   |
| Lite-On Technology              | 2         | 3.57%   |
| Integrated System Solution      | 2         | 3.57%   |
| Broadcom                        | 2         | 3.57%   |
| Toshiba                         | 1         | 1.79%   |
| MediaTek                        | 1         | 1.79%   |
| Hewlett-Packard                 | 1         | 1.79%   |
| Foxconn / Hon Hai               | 1         | 1.79%   |
| ASUSTek Computer                | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 16        | 28.57%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 8.93%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 5.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 3.57%   |
| Intel AX201 Bluetooth                                       | 2         | 3.57%   |
| Integrated System Solution Bluetooth Device                 | 2         | 3.57%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 3.57%   |
| IMC Networks Bluetooth Radio                                | 2         | 3.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.57%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.79%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.79%   |
| Realtek  Bluetooth Adapter                                  | 1         | 1.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.79%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.79%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.79%   |
| MediaTek Wireless_Device                                    | 1         | 1.79%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.79%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.79%   |
| Intel AX210 Bluetooth                                       | 1         | 1.79%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.79%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.79%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.79%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.79%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 111       | 62.36%  |
| AMD                              | 41        | 23.03%  |
| Nvidia                           | 16        | 8.99%   |
| C-Media Electronics              | 4         | 2.25%   |
| Silicon Integrated Systems [SiS] | 2         | 1.12%   |
| Logitech                         | 2         | 1.12%   |
| KTMicro                          | 1         | 0.56%   |
| Bose                             | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 5.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 3.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 3.21%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 3.21%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.75%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 2.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.29%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.38%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 1.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.38%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.92%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.92%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.92%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.92%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.92%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 19.78%  |
| Kingston            | 26        | 14.29%  |
| SK hynix            | 25        | 13.74%  |
| Unknown             | 21        | 11.54%  |
| Micron Technology   | 12        | 6.59%   |
| Crucial             | 12        | 6.59%   |
| Unknown             | 9         | 4.95%   |
| Unknown (ABCD)      | 5         | 2.75%   |
| Ramaxel Technology  | 5         | 2.75%   |
| Nanya Technology    | 5         | 2.75%   |
| Transcend           | 4         | 2.2%    |
| Corsair             | 4         | 2.2%    |
| Elpida              | 3         | 1.65%   |
| Unknown (F301)      | 1         | 0.55%   |
| Unknown (AB)        | 1         | 0.55%   |
| Unknown (0x0DD5)    | 1         | 0.55%   |
| SK_Hynix            | 1         | 0.55%   |
| KomputerBay         | 1         | 0.55%   |
| Intersil            | 1         | 0.55%   |
| Heoriady            | 1         | 0.55%   |
| G.Skill             | 1         | 0.55%   |
| ASint Technology    | 1         | 0.55%   |
| Apacer              | 1         | 0.55%   |
| A-DATA Technology   | 1         | 0.55%   |
| 2C0C0843D7349CA2    | 1         | 0.55%   |
| 2C0C0843D7349C9D    | 1         | 0.55%   |
| 2C080815D82F5C7B    | 1         | 0.55%   |
| 2C0108214C359D20    | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 9         | 4.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 5         | 2.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 2.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 3         | 1.51%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 3         | 1.51%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 3         | 1.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 2         | 1.01%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 2         | 1.01%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 2         | 1.01%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.01%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 2         | 1.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 2         | 1.01%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 2         | 1.01%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                    | 2         | 1.01%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s        | 2         | 1.01%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 1.01%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                              | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                   | 1         | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 256MB SODIMM DDR                            | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 1         | 0.5%    |
| Unknown (F301) RAM G2JT-4AFR00 16GB SODIMM DDR4 2400MT/s       | 1         | 0.5%    |
| Unknown (AB) RAM Module 2048MB DIMM LPDDR4 2133MT/s            | 1         | 0.5%    |
| Unknown (0x0DD5) RAM AZ8G4SW266-8G 8GB SODIMM DDR4 2667MT/s    | 1         | 0.5%    |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s             | 1         | 0.5%    |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s           | 1         | 0.5%    |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s           | 1         | 0.5%    |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |
| SK_Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 0.5%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1333MT/s                   | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 75        | 49.02%  |
| DDR4    | 40        | 26.14%  |
| DDR2    | 21        | 13.73%  |
| Unknown | 7         | 4.58%   |
| LPDDR4  | 6         | 3.92%   |
| SDRAM   | 2         | 1.31%   |
| LPDDR3  | 1         | 0.65%   |
| DDR     | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 54.97%  |
| DIMM         | 62        | 41.06%  |
| Chip         | 3         | 1.99%   |
| Row Of Chips | 2         | 1.32%   |
| FB-DIMM      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 62        | 37.35%  |
| 8192  | 39        | 23.49%  |
| 2048  | 38        | 22.89%  |
| 16384 | 18        | 10.84%  |
| 1024  | 5         | 3.01%   |
| 32768 | 3         | 1.81%   |
| 256   | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 26.22%  |
| 1333    | 24        | 14.63%  |
| 2400    | 18        | 10.98%  |
| 2667    | 14        | 8.54%   |
| 667     | 13        | 7.93%   |
| 1067    | 10        | 6.1%    |
| 800     | 9         | 5.49%   |
| 3200    | 8         | 4.88%   |
| 2133    | 8         | 4.88%   |
| 1334    | 4         | 2.44%   |
| Unknown | 4         | 2.44%   |
| 1066    | 3         | 1.83%   |
| 2933    | 1         | 0.61%   |
| 2666    | 1         | 0.61%   |
| 1867    | 1         | 0.61%   |
| 1866    | 1         | 0.61%   |
| 1200    | 1         | 0.61%   |
| 333     | 1         | 0.61%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 29.17%  |
| IMC Networks                           | 7         | 14.58%  |
| Sunplus Innovation Technology          | 4         | 8.33%   |
| Realtek Semiconductor                  | 4         | 8.33%   |
| Acer                                   | 4         | 8.33%   |
| ALi                                    | 3         | 6.25%   |
| Silicon Motion                         | 2         | 4.17%   |
| Microdia                               | 2         | 4.17%   |
| Logitech                               | 2         | 4.17%   |
| Syntek                                 | 1         | 2.08%   |
| Suyin                                  | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |
| KYE Systems (Mouse Systems)            | 1         | 2.08%   |
| Genesys Logic                          | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                  | 3         | 6.25%   |
| Realtek Lenovo EasyCamera                                  | 2         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 2         | 4.17%   |
| Chicony HD WebCam (Acer)                                   | 2         | 4.17%   |
| ALi Gateway Webcam                                         | 2         | 4.17%   |
| Acer Integrated Camera                                     | 2         | 4.17%   |
| Syntek EasyCamera                                          | 1         | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                   | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                       | 1         | 2.08%   |
| Sunplus Integrated Camera                                  | 1         | 2.08%   |
| Sunplus Dell E5570 integrated webcam                       | 1         | 2.08%   |
| Sunplus Aukey-PC-LM1E Camera                               | 1         | 2.08%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 1         | 2.08%   |
| Silicon Motion HP Webcam-50                                | 1         | 2.08%   |
| Realtek USB Camera                                         | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                               | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                              | 1         | 2.08%   |
| Microdia ASUS USB2.0 Webcam                                | 1         | 2.08%   |
| Logitech Webcam C310                                       | 1         | 2.08%   |
| Logitech C505 HD Webcam                                    | 1         | 2.08%   |
| Lite-On HP TrueVision HD Camera                            | 1         | 2.08%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera           | 1         | 2.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                         | 1         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 1         | 2.08%   |
| IMC Networks Integrated Webcam                             | 1         | 2.08%   |
| IMC Networks Integrated RGB Camera                         | 1         | 2.08%   |
| IMC Networks Integrated Camera                             | 1         | 2.08%   |
| Genesys Logic Digital Microscope                           | 1         | 2.08%   |
| Chicony WebCam                                             | 1         | 2.08%   |
| Chicony USB2.0 VGA UVC WebCam                              | 1         | 2.08%   |
| Chicony ThinkPad T490 Webcam                               | 1         | 2.08%   |
| Chicony Thinkpad T430 camera                               | 1         | 2.08%   |
| Chicony Integrated Camera [ThinkPad]                       | 1         | 2.08%   |
| Chicony HP TrueVision HD Camera                            | 1         | 2.08%   |
| Chicony 2.0M UVC Webcam / CNF7129                          | 1         | 2.08%   |
| Chicony 1.3M Webcam                                        | 1         | 2.08%   |
| Chicony 1.3 MPixel UVC Webcam                              | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 1         | 2.08%   |
| ALi M5602 Video Camera Controller                          | 1         | 2.08%   |
| Acer SunplusIT INC. Integrated Camera                      | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 2         | 28.57%  |
| AuthenTec             | 2         | 28.57%  |
| Upek                  | 1         | 14.29%  |
| Synaptics             | 1         | 14.29%  |
| Elan Microelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 14.29%  |
| Elan ELAN WBF Fingerprint Sensor                       | 1         | 14.29%  |
| AuthenTec AES2810                                      | 1         | 14.29%  |
| AuthenTec AES1600                                      | 1         | 14.29%  |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 39.77%  |
| 0     | 57        | 32.39%  |
| 2     | 27        | 15.34%  |
| 3     | 20        | 11.36%  |
| 4     | 2         | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 90        | 51.14%  |
| Net/wireless             | 23        | 13.07%  |
| Card reader              | 21        | 11.93%  |
| Bluetooth                | 19        | 10.8%   |
| Firewire controller      | 10        | 5.68%   |
| Fingerprint reader       | 7         | 3.98%   |
| Network                  | 2         | 1.14%   |
| Graphics card            | 2         | 1.14%   |
| Sound                    | 1         | 0.57%   |
| Modem                    | 1         | 0.57%   |

