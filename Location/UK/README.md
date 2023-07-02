BSD in UK - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for BSD in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 759

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Techvision    | TVI7309X B0                 | Desktop     | [7c71b88b22](https://bsd-hardware.info/?probe=7c71b88b22) | Jun 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [ddeb9d00a6](https://bsd-hardware.info/?probe=ddeb9d00a6) | Jun 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [0dbf4904dc](https://bsd-hardware.info/?probe=0dbf4904dc) | Jun 28, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [03c29939fc](https://bsd-hardware.info/?probe=03c29939fc) | Jun 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d98798bc8](https://bsd-hardware.info/?probe=9d98798bc8) | Jun 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [748ae83ba1](https://bsd-hardware.info/?probe=748ae83ba1) | Jun 27, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [4bae8cd192](https://bsd-hardware.info/?probe=4bae8cd192) | Jun 27, 2023 |
| Cisco         | ASA5515 A0                  | Desktop     | [9d8eedf081](https://bsd-hardware.info/?probe=9d8eedf081) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [03eb1a54c8](https://bsd-hardware.info/?probe=03eb1a54c8) | Jun 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e7dfbf94d0](https://bsd-hardware.info/?probe=e7dfbf94d0) | Jun 25, 2023 |
| Supermicro    | X10SRL-FB                   | Server      | [24770c65d3](https://bsd-hardware.info/?probe=24770c65d3) | Jun 24, 2023 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [aca5df3113](https://bsd-hardware.info/?probe=aca5df3113) | Jun 24, 2023 |
| HP            | 8592                        | Desktop     | [154f28878a](https://bsd-hardware.info/?probe=154f28878a) | Jun 21, 2023 |
| HPE           | ProLiant DL20 Gen10 Plus    | Server      | [7d5925b21e](https://bsd-hardware.info/?probe=7d5925b21e) | Jun 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [81268da610](https://bsd-hardware.info/?probe=81268da610) | Jun 17, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [53bbc07cc8](https://bsd-hardware.info/?probe=53bbc07cc8) | Jun 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [04ca736537](https://bsd-hardware.info/?probe=04ca736537) | Jun 15, 2023 |
| Dell          | 0H7TGR A00                  | Desktop     | [da72cc4da4](https://bsd-hardware.info/?probe=da72cc4da4) | Jun 14, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [644e9b9d90](https://bsd-hardware.info/?probe=644e9b9d90) | Jun 14, 2023 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [f96302f46c](https://bsd-hardware.info/?probe=f96302f46c) | Jun 13, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [f6540a4d85](https://bsd-hardware.info/?probe=f6540a4d85) | Jun 13, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1307c1f267](https://bsd-hardware.info/?probe=1307c1f267) | Jun 13, 2023 |
| IP3 Tech      | VB2                         | Mini pc     | [38575bac1f](https://bsd-hardware.info/?probe=38575bac1f) | Jun 11, 2023 |
| AZW           | EQ                          | Desktop     | [f1f980d130](https://bsd-hardware.info/?probe=f1f980d130) | Jun 10, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [7b43dea184](https://bsd-hardware.info/?probe=7b43dea184) | Jun 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [5de35aa3bb](https://bsd-hardware.info/?probe=5de35aa3bb) | Jun 06, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e32011137f](https://bsd-hardware.info/?probe=e32011137f) | Jun 05, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [70fa6667b0](https://bsd-hardware.info/?probe=70fa6667b0) | Jun 05, 2023 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [c1c30d3223](https://bsd-hardware.info/?probe=c1c30d3223) | Jun 02, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [22572f1df6](https://bsd-hardware.info/?probe=22572f1df6) | Jun 01, 2023 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [45cb709a24](https://bsd-hardware.info/?probe=45cb709a24) | Jun 01, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a11ca8795e](https://bsd-hardware.info/?probe=a11ca8795e) | Jun 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e968a467d5](https://bsd-hardware.info/?probe=e968a467d5) | May 30, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [c9959faf54](https://bsd-hardware.info/?probe=c9959faf54) | May 29, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a9f82c093e](https://bsd-hardware.info/?probe=a9f82c093e) | May 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [6701dce30e](https://bsd-hardware.info/?probe=6701dce30e) | May 28, 2023 |
| Axiomtek      | NA362-DAMI-c3768-US         | Desktop     | [243efb73f6](https://bsd-hardware.info/?probe=243efb73f6) | May 27, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [65376d6b42](https://bsd-hardware.info/?probe=65376d6b42) | May 27, 2023 |
| Unknown       | 1.0                         | Desktop     | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [364d24b4f4](https://bsd-hardware.info/?probe=364d24b4f4) | May 25, 2023 |
| ASRock        | E3C224D2I                   | Desktop     | [57353597b3](https://bsd-hardware.info/?probe=57353597b3) | May 25, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [afa4b1b0df](https://bsd-hardware.info/?probe=afa4b1b0df) | May 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [a1a68c0f7d](https://bsd-hardware.info/?probe=a1a68c0f7d) | May 24, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2fec675050](https://bsd-hardware.info/?probe=2fec675050) | May 20, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [70d54595c2](https://bsd-hardware.info/?probe=70d54595c2) | May 19, 2023 |
| ASRock        | IMB-181-L                   | Desktop     | [0347664bbc](https://bsd-hardware.info/?probe=0347664bbc) | May 17, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [e252dc5ff2](https://bsd-hardware.info/?probe=e252dc5ff2) | May 15, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Supermicro    | X8SIL                       | Desktop     | [a39ebc1c3a](https://bsd-hardware.info/?probe=a39ebc1c3a) | May 10, 2023 |
| Sophos        | SG                          | Firewall    | [67e0c0dc71](https://bsd-hardware.info/?probe=67e0c0dc71) | May 07, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [8114acc225](https://bsd-hardware.info/?probe=8114acc225) | May 07, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [80d3f65191](https://bsd-hardware.info/?probe=80d3f65191) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6cc74ec4bd](https://bsd-hardware.info/?probe=6cc74ec4bd) | May 04, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [2c5d0e597f](https://bsd-hardware.info/?probe=2c5d0e597f) | May 03, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [3fbe359db7](https://bsd-hardware.info/?probe=3fbe359db7) | May 03, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2a9fc1af29](https://bsd-hardware.info/?probe=2a9fc1af29) | Apr 27, 2023 |
| Intel GMLV... | GMLR115 GMLR115             | Desktop     | [56d2fcc6e9](https://bsd-hardware.info/?probe=56d2fcc6e9) | Apr 24, 2023 |
| Samsung       | DP700A3D-A05UK SEC_SW_RE... | All in one  | [5718d8d05e](https://bsd-hardware.info/?probe=5718d8d05e) | Apr 24, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [e461f7862c](https://bsd-hardware.info/?probe=e461f7862c) | Apr 23, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [214b0c30e0](https://bsd-hardware.info/?probe=214b0c30e0) | Apr 23, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [9f7ba08cb2](https://bsd-hardware.info/?probe=9f7ba08cb2) | Apr 23, 2023 |
| Sophos        | SG                          | Firewall    | [7adec1bab7](https://bsd-hardware.info/?probe=7adec1bab7) | Apr 23, 2023 |
| Gigabyte      | N3050MD3P                   | Desktop     | [66e9ccbef8](https://bsd-hardware.info/?probe=66e9ccbef8) | Apr 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [7a5fcaf0d0](https://bsd-hardware.info/?probe=7a5fcaf0d0) | Apr 22, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [6e82f69c4c](https://bsd-hardware.info/?probe=6e82f69c4c) | Apr 20, 2023 |
| PICO PC       | MNHO-113                    | Desktop     | [ad485d27af](https://bsd-hardware.info/?probe=ad485d27af) | Apr 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | Notebook    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [385910dbe5](https://bsd-hardware.info/?probe=385910dbe5) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ceebb96d61](https://bsd-hardware.info/?probe=ceebb96d61) | Apr 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7145e5aea1](https://bsd-hardware.info/?probe=7145e5aea1) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [e163926e69](https://bsd-hardware.info/?probe=e163926e69) | Apr 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [f2fbd3c3ad](https://bsd-hardware.info/?probe=f2fbd3c3ad) | Apr 09, 2023 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6dabd5d84a](https://bsd-hardware.info/?probe=6dabd5d84a) | Apr 08, 2023 |
| HP            | 8103 A01                    | Mini pc     | [4ad245dce9](https://bsd-hardware.info/?probe=4ad245dce9) | Apr 08, 2023 |
| ASRock        | E3C224D2I                   | Desktop     | [f8f3f3c43c](https://bsd-hardware.info/?probe=f8f3f3c43c) | Apr 07, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [42a875684f](https://bsd-hardware.info/?probe=42a875684f) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [196f8d9e86](https://bsd-hardware.info/?probe=196f8d9e86) | Apr 06, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [a4957dcdd6](https://bsd-hardware.info/?probe=a4957dcdd6) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a7bd1b139](https://bsd-hardware.info/?probe=5a7bd1b139) | Apr 02, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [8fe73c707e](https://bsd-hardware.info/?probe=8fe73c707e) | Apr 02, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [1122cabca9](https://bsd-hardware.info/?probe=1122cabca9) | Apr 01, 2023 |
| ASRockRack    | EPYCD8-2T                   | Desktop     | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Lenovo        | SHARKBAY 0B98405 STD        | Desktop     | [29c6f5f74c](https://bsd-hardware.info/?probe=29c6f5f74c) | Mar 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [3c4f4abe16](https://bsd-hardware.info/?probe=3c4f4abe16) | Mar 23, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [8b3bb4ee24](https://bsd-hardware.info/?probe=8b3bb4ee24) | Mar 19, 2023 |
| ASUSTek       | Z97I-PLUS                   | Desktop     | [cdbc1b0031](https://bsd-hardware.info/?probe=cdbc1b0031) | Mar 19, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [914c4aad57](https://bsd-hardware.info/?probe=914c4aad57) | Mar 19, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [15e8aedcb6](https://bsd-hardware.info/?probe=15e8aedcb6) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [6c2382fa44](https://bsd-hardware.info/?probe=6c2382fa44) | Mar 16, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [652100bcac](https://bsd-hardware.info/?probe=652100bcac) | Mar 16, 2023 |
| ASUSTek       | 1001P                       | Notebook    | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | Notebook    | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | Notebook    | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [82759eff54](https://bsd-hardware.info/?probe=82759eff54) | Mar 11, 2023 |
| Star Labs     | StarBook                    | Notebook    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Acer          | TDPS05 R3700                | Desktop     | [6ee4404ee0](https://bsd-hardware.info/?probe=6ee4404ee0) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| HPE           | ML10Gen9                    | Server      | [6283151877](https://bsd-hardware.info/?probe=6283151877) | Mar 07, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3daad10634](https://bsd-hardware.info/?probe=3daad10634) | Mar 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [fb5b37bff5](https://bsd-hardware.info/?probe=fb5b37bff5) | Mar 02, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [e9e179e9ac](https://bsd-hardware.info/?probe=e9e179e9ac) | Mar 02, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [85aecf8c3f](https://bsd-hardware.info/?probe=85aecf8c3f) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [be81f2675f](https://bsd-hardware.info/?probe=be81f2675f) | Feb 25, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [410a7ff78e](https://bsd-hardware.info/?probe=410a7ff78e) | Feb 23, 2023 |
| Intel         | CW-J6-5L 2C                 | Desktop     | [442643937e](https://bsd-hardware.info/?probe=442643937e) | Feb 22, 2023 |
| Intel         | CW-J6-5L 2C                 | Desktop     | [90fc1b74e6](https://bsd-hardware.info/?probe=90fc1b74e6) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c063582d4](https://bsd-hardware.info/?probe=8c063582d4) | Feb 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | Notebook    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [b906471557](https://bsd-hardware.info/?probe=b906471557) | Feb 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1d9739f234](https://bsd-hardware.info/?probe=1d9739f234) | Feb 17, 2023 |
| Dell          | 0DVNTK A00                  | Mini pc     | [e49082a67c](https://bsd-hardware.info/?probe=e49082a67c) | Feb 14, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | Notebook    | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [092bbaa484](https://bsd-hardware.info/?probe=092bbaa484) | Feb 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [ecf5a46a0f](https://bsd-hardware.info/?probe=ecf5a46a0f) | Feb 01, 2023 |
| HP            | 8103 A01                    | Mini pc     | [d89405421a](https://bsd-hardware.info/?probe=d89405421a) | Jan 31, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [cd4202e58b](https://bsd-hardware.info/?probe=cd4202e58b) | Jan 30, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [283d305565](https://bsd-hardware.info/?probe=283d305565) | Jan 29, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [9d09937e2a](https://bsd-hardware.info/?probe=9d09937e2a) | Jan 28, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b938a15d41](https://bsd-hardware.info/?probe=b938a15d41) | Jan 22, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0e9d5e53b9](https://bsd-hardware.info/?probe=0e9d5e53b9) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bbf3bdc00](https://bsd-hardware.info/?probe=0bbf3bdc00) | Jan 21, 2023 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [0dc2013a9f](https://bsd-hardware.info/?probe=0dc2013a9f) | Jan 21, 2023 |
| Unknown       | PICO PC                     | Desktop     | [9e20d7dbbc](https://bsd-hardware.info/?probe=9e20d7dbbc) | Jan 20, 2023 |
| HP            | 17E2                        | Mini pc     | [ff98f389b1](https://bsd-hardware.info/?probe=ff98f389b1) | Jan 18, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [8c1f6c2733](https://bsd-hardware.info/?probe=8c1f6c2733) | Jan 12, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [9b4b30a009](https://bsd-hardware.info/?probe=9b4b30a009) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e866a006d](https://bsd-hardware.info/?probe=6e866a006d) | Jan 10, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [2428fe6bd3](https://bsd-hardware.info/?probe=2428fe6bd3) | Jan 10, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [eca179a730](https://bsd-hardware.info/?probe=eca179a730) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e87430a40](https://bsd-hardware.info/?probe=7e87430a40) | Jan 07, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ce6ccffb1b](https://bsd-hardware.info/?probe=ce6ccffb1b) | Jan 06, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [d83b84a6bb](https://bsd-hardware.info/?probe=d83b84a6bb) | Jan 05, 2023 |
| Winston Ma... | PICO PC                     | Desktop     | [d744315833](https://bsd-hardware.info/?probe=d744315833) | Jan 05, 2023 |
| Acer          | Aspire X3400                | Desktop     | [fa59d6aa07](https://bsd-hardware.info/?probe=fa59d6aa07) | Jan 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [0f727c761b](https://bsd-hardware.info/?probe=0f727c761b) | Dec 29, 2022 |
| HP            | 8000 X4                     | Desktop     | [e66d228381](https://bsd-hardware.info/?probe=e66d228381) | Dec 29, 2022 |
| Intel         | CARLOW                      | Desktop     | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Desktop     | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| Star Labs     | Lite                        | Notebook    | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [17ddf8c2e1](https://bsd-hardware.info/?probe=17ddf8c2e1) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 400            | Desktop     | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | Desktop     | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [c3ffb2c87d](https://bsd-hardware.info/?probe=c3ffb2c87d) | Dec 17, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [160d942d28](https://bsd-hardware.info/?probe=160d942d28) | Dec 17, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | 213D A01                    | Desktop     | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Intel         | CARLOW                      | Desktop     | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| HP            | ProLiant DL360 G5           | Server      | [4a44193c5f](https://bsd-hardware.info/?probe=4a44193c5f) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | Desktop     | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| Datto         | SSD                         | Desktop     | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [79c7aad234](https://bsd-hardware.info/?probe=79c7aad234) | Nov 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | Desktop     | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| HP            | 8000 X4                     | Desktop     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 1998                        | Desktop     | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 1998                        | Desktop     | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [5c70ba3a0d](https://bsd-hardware.info/?probe=5c70ba3a0d) | Nov 08, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3fa9f3aa5c](https://bsd-hardware.info/?probe=3fa9f3aa5c) | Nov 05, 2022 |
| Dell          | 0W3F1J A00                  | Mini pc     | [7c95a69cc9](https://bsd-hardware.info/?probe=7c95a69cc9) | Nov 02, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| AWOW          | AK34Pro                     | Mini pc     | [70cc64ba78](https://bsd-hardware.info/?probe=70cc64ba78) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| HP            | 8103 A01                    | Mini pc     | [9017d1ac90](https://bsd-hardware.info/?probe=9017d1ac90) | Oct 26, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [69a9ae7bde](https://bsd-hardware.info/?probe=69a9ae7bde) | Oct 25, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| ASRock        | J3355M                      | Desktop     | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Shuttle       | FH61V                       | Desktop     | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [3877787983](https://bsd-hardware.info/?probe=3877787983) | Sep 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cde2481e46](https://bsd-hardware.info/?probe=cde2481e46) | Sep 26, 2022 |
| HP            | 8592                        | Desktop     | [898ce46c1f](https://bsd-hardware.info/?probe=898ce46c1f) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [de9d75d495](https://bsd-hardware.info/?probe=de9d75d495) | Sep 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8883d36139](https://bsd-hardware.info/?probe=8883d36139) | Sep 25, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| HP            | 8103 A01                    | Mini pc     | [533a1ebabe](https://bsd-hardware.info/?probe=533a1ebabe) | Sep 17, 2022 |
| Dell          | 07WP95 A01                  | Desktop     | [98e67ff164](https://bsd-hardware.info/?probe=98e67ff164) | Sep 12, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [fb678970df](https://bsd-hardware.info/?probe=fb678970df) | Sep 09, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [6c88b88822](https://bsd-hardware.info/?probe=6c88b88822) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [3f5ad2f043](https://bsd-hardware.info/?probe=3f5ad2f043) | Sep 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Dell          | Precision 7710              | Notebook    | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [58a4089f3f](https://bsd-hardware.info/?probe=58a4089f3f) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [edb9608bc9](https://bsd-hardware.info/?probe=edb9608bc9) | Aug 24, 2022 |
| Dell          | 03X6X0 A03                  | Server      | [d77ae4f2a0](https://bsd-hardware.info/?probe=d77ae4f2a0) | Aug 24, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [0dd0325ce1](https://bsd-hardware.info/?probe=0dd0325ce1) | Aug 22, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [6dd76b10ad](https://bsd-hardware.info/?probe=6dd76b10ad) | Aug 21, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [5648905ca2](https://bsd-hardware.info/?probe=5648905ca2) | Aug 19, 2022 |
| HP            | 8592                        | Desktop     | [212adc2c89](https://bsd-hardware.info/?probe=212adc2c89) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2b5456b337](https://bsd-hardware.info/?probe=2b5456b337) | Aug 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [78340c12ef](https://bsd-hardware.info/?probe=78340c12ef) | Aug 16, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [970bec57b8](https://bsd-hardware.info/?probe=970bec57b8) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [4cf33d57a1](https://bsd-hardware.info/?probe=4cf33d57a1) | Aug 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [9783858164](https://bsd-hardware.info/?probe=9783858164) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| HP            | 8592                        | Desktop     | [7c6794942c](https://bsd-hardware.info/?probe=7c6794942c) | Aug 10, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [8176a8261d](https://bsd-hardware.info/?probe=8176a8261d) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [cbda56eddb](https://bsd-hardware.info/?probe=cbda56eddb) | Aug 03, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b33527f3ee](https://bsd-hardware.info/?probe=b33527f3ee) | Jul 25, 2022 |
| Dell          | 0T7D40 A00                  | Desktop     | [3d5e83cf1a](https://bsd-hardware.info/?probe=3d5e83cf1a) | Jul 20, 2022 |
| Gigabyte      | J1900N-D3V                  | Desktop     | [17aa06f41f](https://bsd-hardware.info/?probe=17aa06f41f) | Jul 18, 2022 |
| Dell          | 0T7D40 A00                  | Desktop     | [2aef6b2ab4](https://bsd-hardware.info/?probe=2aef6b2ab4) | Jul 18, 2022 |
| Shuttle       | FH170                       | Desktop     | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | Desktop     | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9943585bfa](https://bsd-hardware.info/?probe=9943585bfa) | Jul 16, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [9c6f76056f](https://bsd-hardware.info/?probe=9c6f76056f) | Jul 15, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0f36e9b5a4](https://bsd-hardware.info/?probe=0f36e9b5a4) | Jul 03, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [6b5f81700c](https://bsd-hardware.info/?probe=6b5f81700c) | Jul 01, 2022 |
| Intel         | CARLOW                      | Desktop     | [615107464b](https://bsd-hardware.info/?probe=615107464b) | Jul 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f8d0f1f7e0](https://bsd-hardware.info/?probe=f8d0f1f7e0) | Jun 29, 2022 |
| System76      | Gazelle                     | Notebook    | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | Notebook    | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| AMD           | Kabini CRB                  | Desktop     | [2ee9e57522](https://bsd-hardware.info/?probe=2ee9e57522) | Jun 26, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [58ff991ef8](https://bsd-hardware.info/?probe=58ff991ef8) | Jun 23, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [aa5b395a20](https://bsd-hardware.info/?probe=aa5b395a20) | Jun 19, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | Desktop     | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [02c0f92734](https://bsd-hardware.info/?probe=02c0f92734) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Gigabyte      | N3150ND3V                   | Desktop     | [56999b6746](https://bsd-hardware.info/?probe=56999b6746) | Jun 13, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Dell          | 0DVNTK A00                  | Mini pc     | [d44f80f2d9](https://bsd-hardware.info/?probe=d44f80f2d9) | Jun 01, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [31c49e462c](https://bsd-hardware.info/?probe=31c49e462c) | Jun 01, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [ee7e944260](https://bsd-hardware.info/?probe=ee7e944260) | May 31, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [2c55c55a67](https://bsd-hardware.info/?probe=2c55c55a67) | May 31, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [607561a9a4](https://bsd-hardware.info/?probe=607561a9a4) | May 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c67bf4af0a](https://bsd-hardware.info/?probe=c67bf4af0a) | May 27, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [d5773cd8b3](https://bsd-hardware.info/?probe=d5773cd8b3) | May 16, 2022 |
| Lenovo        | ThinkPad X230 2325J67       | Notebook    | [3ee0f54d2f](https://bsd-hardware.info/?probe=3ee0f54d2f) | May 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [c6faa8080e](https://bsd-hardware.info/?probe=c6faa8080e) | May 10, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | Notebook    | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| HP            | 8592                        | Desktop     | [d922327cdd](https://bsd-hardware.info/?probe=d922327cdd) | May 06, 2022 |
| Intel         | CARLOW                      | Desktop     | [6f185d9b30](https://bsd-hardware.info/?probe=6f185d9b30) | May 06, 2022 |
| Intel         | CARLOW                      | Desktop     | [2240df9d2d](https://bsd-hardware.info/?probe=2240df9d2d) | May 04, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| HP            | Pavilion m6                 | Notebook    | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1YG01    | Notebook    | [6e38eb1a4e](https://bsd-hardware.info/?probe=6e38eb1a4e) | May 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [60932d337b](https://bsd-hardware.info/?probe=60932d337b) | Apr 28, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [544b83da9f](https://bsd-hardware.info/?probe=544b83da9f) | Apr 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [3b256304a0](https://bsd-hardware.info/?probe=3b256304a0) | Apr 23, 2022 |
| Shuttle       | FH61V                       | Desktop     | [6f4c78b7db](https://bsd-hardware.info/?probe=6f4c78b7db) | Apr 23, 2022 |
| Dell          | 0N051F A01                  | Server      | [0784468d7a](https://bsd-hardware.info/?probe=0784468d7a) | Apr 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3813b46bc1](https://bsd-hardware.info/?probe=3813b46bc1) | Apr 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a2fc9672d6](https://bsd-hardware.info/?probe=a2fc9672d6) | Apr 22, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [3322ad9dac](https://bsd-hardware.info/?probe=3322ad9dac) | Apr 20, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [aa48329066](https://bsd-hardware.info/?probe=aa48329066) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [754d45f24f](https://bsd-hardware.info/?probe=754d45f24f) | Apr 11, 2022 |
| Jetway        | 1.0                         | Desktop     | [0048067292](https://bsd-hardware.info/?probe=0048067292) | Apr 11, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [f4098d352f](https://bsd-hardware.info/?probe=f4098d352f) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [a7470aa647](https://bsd-hardware.info/?probe=a7470aa647) | Apr 09, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7eee3bb3d8](https://bsd-hardware.info/?probe=7eee3bb3d8) | Apr 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0911185155](https://bsd-hardware.info/?probe=0911185155) | Apr 05, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [2a7de69b4b](https://bsd-hardware.info/?probe=2a7de69b4b) | Apr 04, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [1b382db711](https://bsd-hardware.info/?probe=1b382db711) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [6274858d8d](https://bsd-hardware.info/?probe=6274858d8d) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [137a301b9b](https://bsd-hardware.info/?probe=137a301b9b) | Mar 31, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [9fae64765f](https://bsd-hardware.info/?probe=9fae64765f) | Mar 31, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [eaa8d1a7d7](https://bsd-hardware.info/?probe=eaa8d1a7d7) | Mar 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [730dd09705](https://bsd-hardware.info/?probe=730dd09705) | Mar 28, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5d554517f2](https://bsd-hardware.info/?probe=5d554517f2) | Mar 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a25c6f603c](https://bsd-hardware.info/?probe=a25c6f603c) | Mar 26, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9913acc698](https://bsd-hardware.info/?probe=9913acc698) | Mar 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e58663aeb0](https://bsd-hardware.info/?probe=e58663aeb0) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b49ac0cf2](https://bsd-hardware.info/?probe=9b49ac0cf2) | Mar 23, 2022 |
| Intel         | DH61CR AAG14064-209         | Desktop     | [3812666505](https://bsd-hardware.info/?probe=3812666505) | Mar 23, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [87289f0c36](https://bsd-hardware.info/?probe=87289f0c36) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [8870903766](https://bsd-hardware.info/?probe=8870903766) | Mar 20, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c9fb46b179](https://bsd-hardware.info/?probe=c9fb46b179) | Mar 19, 2022 |
| HP            | 8592                        | Desktop     | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [d28bef2c37](https://bsd-hardware.info/?probe=d28bef2c37) | Mar 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [72b461ded3](https://bsd-hardware.info/?probe=72b461ded3) | Mar 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [10a235fe8f](https://bsd-hardware.info/?probe=10a235fe8f) | Mar 13, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a22c1d4ab](https://bsd-hardware.info/?probe=5a22c1d4ab) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Sophos        | SG                          | Firewall    | [70d42d9a3a](https://bsd-hardware.info/?probe=70d42d9a3a) | Mar 07, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [77c308e93e](https://bsd-hardware.info/?probe=77c308e93e) | Mar 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1ffc0a0805](https://bsd-hardware.info/?probe=1ffc0a0805) | Mar 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f1d5448b3](https://bsd-hardware.info/?probe=3f1d5448b3) | Mar 01, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [26565f3d84](https://bsd-hardware.info/?probe=26565f3d84) | Mar 01, 2022 |
| Dell          | 0M877N A01                  | Server      | [af93606e74](https://bsd-hardware.info/?probe=af93606e74) | Feb 24, 2022 |
| Biostar       | J3160NH                     | Desktop     | [536f856d94](https://bsd-hardware.info/?probe=536f856d94) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| Jumper        | EZbook                      | Notebook    | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| HP            | 8592                        | Desktop     | [fc273bb51a](https://bsd-hardware.info/?probe=fc273bb51a) | Feb 14, 2022 |
| HP            | 8592                        | Desktop     | [5accd7ce0d](https://bsd-hardware.info/?probe=5accd7ce0d) | Feb 13, 2022 |
| Dell          | 00NH4P A02                  | Server      | [5c1ea00df3](https://bsd-hardware.info/?probe=5c1ea00df3) | Feb 08, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [b6329aa072](https://bsd-hardware.info/?probe=b6329aa072) | Feb 06, 2022 |
| Dell          | 03X6X0 A03                  | Server      | [08e48565c1](https://bsd-hardware.info/?probe=08e48565c1) | Feb 06, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [a3843d55ca](https://bsd-hardware.info/?probe=a3843d55ca) | Feb 05, 2022 |
| Intel         | J1900                       | Desktop     | [3b4b841677](https://bsd-hardware.info/?probe=3b4b841677) | Feb 04, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [c3394665a0](https://bsd-hardware.info/?probe=c3394665a0) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [86cb857d00](https://bsd-hardware.info/?probe=86cb857d00) | Feb 02, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| PC Engines    | APU2                        | Desktop     | [0409aa82c2](https://bsd-hardware.info/?probe=0409aa82c2) | Feb 01, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [4b4b77d8f3](https://bsd-hardware.info/?probe=4b4b77d8f3) | Feb 01, 2022 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [a65a16decd](https://bsd-hardware.info/?probe=a65a16decd) | Jan 31, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [d08074d468](https://bsd-hardware.info/?probe=d08074d468) | Jan 28, 2022 |
| Dell          | 00NH4P A02                  | Server      | [b456eb04b7](https://bsd-hardware.info/?probe=b456eb04b7) | Jan 28, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [461b538b72](https://bsd-hardware.info/?probe=461b538b72) | Jan 28, 2022 |
| Unknown       | PICO PC                     | Desktop     | [538ca6b389](https://bsd-hardware.info/?probe=538ca6b389) | Jan 27, 2022 |
| CheckPoint    | PB-10-00                    | Firewall    | [68b230df84](https://bsd-hardware.info/?probe=68b230df84) | Jan 25, 2022 |
| CheckPoint    | PB-10-00                    | Firewall    | [ef85ae90b3](https://bsd-hardware.info/?probe=ef85ae90b3) | Jan 25, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [277f5bacdd](https://bsd-hardware.info/?probe=277f5bacdd) | Jan 22, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [6ea5e898fa](https://bsd-hardware.info/?probe=6ea5e898fa) | Jan 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Jumper        | EZbook                      | Notebook    | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [55716e7c8b](https://bsd-hardware.info/?probe=55716e7c8b) | Jan 17, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | Notebook    | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [6bde480ecd](https://bsd-hardware.info/?probe=6bde480ecd) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Winston Ma... | PICO PC                     | Desktop     | [ac1014aab2](https://bsd-hardware.info/?probe=ac1014aab2) | Jan 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [e85c24b03a](https://bsd-hardware.info/?probe=e85c24b03a) | Jan 11, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| HP            | 8169                        | Desktop     | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [9a24935dab](https://bsd-hardware.info/?probe=9a24935dab) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [de6d713222](https://bsd-hardware.info/?probe=de6d713222) | Jan 05, 2022 |
| PC Engines    | APU                         | Desktop     | [efe2fbd850](https://bsd-hardware.info/?probe=efe2fbd850) | Jan 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [3ada7b4079](https://bsd-hardware.info/?probe=3ada7b4079) | Jan 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [c3c1529f86](https://bsd-hardware.info/?probe=c3c1529f86) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [90919a642f](https://bsd-hardware.info/?probe=90919a642f) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| Dell          | 0N051F A01                  | Server      | [071ad110ab](https://bsd-hardware.info/?probe=071ad110ab) | Dec 01, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [67556468e3](https://bsd-hardware.info/?probe=67556468e3) | Nov 30, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Dell          | 012KND A00                  | Mini pc     | [71f763e932](https://bsd-hardware.info/?probe=71f763e932) | Nov 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [99ceb827fe](https://bsd-hardware.info/?probe=99ceb827fe) | Nov 20, 2021 |
| Protectli     | FW6 Ver                     | Desktop     | [53e6ac863a](https://bsd-hardware.info/?probe=53e6ac863a) | Nov 18, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [56cd34ffef](https://bsd-hardware.info/?probe=56cd34ffef) | Nov 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [8451595212](https://bsd-hardware.info/?probe=8451595212) | Nov 16, 2021 |
| Dell          | 0GXM1W A01                  | Desktop     | [e0c3737f7c](https://bsd-hardware.info/?probe=e0c3737f7c) | Nov 15, 2021 |
| Dell          | 0J3C2F A02                  | Desktop     | [a2bbadf4a5](https://bsd-hardware.info/?probe=a2bbadf4a5) | Nov 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [f0c5f5ef97](https://bsd-hardware.info/?probe=f0c5f5ef97) | Nov 09, 2021 |
| ASUSTek       | 1001P                       | Notebook    | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [abaafd0a1e](https://bsd-hardware.info/?probe=abaafd0a1e) | Nov 05, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [83480615f6](https://bsd-hardware.info/?probe=83480615f6) | Nov 04, 2021 |
| Yanling       | YL-KBR6L                    | Desktop     | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| Dell          | 081N4V A05                  | Server      | [2492e3f933](https://bsd-hardware.info/?probe=2492e3f933) | Nov 03, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| AZW           | GK55                        | Desktop     | [91db367d18](https://bsd-hardware.info/?probe=91db367d18) | Oct 28, 2021 |
| Unknown       | Unknown                     | Desktop     | [8caf15c2a5](https://bsd-hardware.info/?probe=8caf15c2a5) | Oct 22, 2021 |
| Dell          | 05XKKK A04                  | Server      | [0c40d38f1d](https://bsd-hardware.info/?probe=0c40d38f1d) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| HP            | 15                          | Notebook    | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [5e82a5d94b](https://bsd-hardware.info/?probe=5e82a5d94b) | Oct 15, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [8e11143a1d](https://bsd-hardware.info/?probe=8e11143a1d) | Oct 14, 2021 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [c8b057c4e4](https://bsd-hardware.info/?probe=c8b057c4e4) | Oct 12, 2021 |
| HP            | ProLiant DL380 G7           | Server      | [4ecdb6038a](https://bsd-hardware.info/?probe=4ecdb6038a) | Oct 10, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4b25e8e063](https://bsd-hardware.info/?probe=4b25e8e063) | Oct 10, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [40aba3842c](https://bsd-hardware.info/?probe=40aba3842c) | Oct 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [357b9d3ad2](https://bsd-hardware.info/?probe=357b9d3ad2) | Sep 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [cc7d3fa6a3](https://bsd-hardware.info/?probe=cc7d3fa6a3) | Sep 26, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [dc09f7f7cb](https://bsd-hardware.info/?probe=dc09f7f7cb) | Sep 25, 2021 |
| ASRock        | J3455M                      | Desktop     | [411b04cbba](https://bsd-hardware.info/?probe=411b04cbba) | Sep 25, 2021 |
| Intel         | NUC7i7BNB J31145-304        | Mini pc     | [31a63f86a2](https://bsd-hardware.info/?probe=31a63f86a2) | Sep 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [462d25d041](https://bsd-hardware.info/?probe=462d25d041) | Sep 19, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [63a24ea67f](https://bsd-hardware.info/?probe=63a24ea67f) | Sep 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [dcd383c684](https://bsd-hardware.info/?probe=dcd383c684) | Sep 12, 2021 |
| Dell          | 03X6X0 A03                  | Server      | [016e4443a0](https://bsd-hardware.info/?probe=016e4443a0) | Sep 10, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [8ce323def8](https://bsd-hardware.info/?probe=8ce323def8) | Sep 09, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | 0XDN97 A09                  | Server      | [4668ce0e56](https://bsd-hardware.info/?probe=4668ce0e56) | Sep 02, 2021 |
| HPE           | ML10Gen9                    | Server      | [d8a8039f9d](https://bsd-hardware.info/?probe=d8a8039f9d) | Aug 31, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [2499806edc](https://bsd-hardware.info/?probe=2499806edc) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [beda690c72](https://bsd-hardware.info/?probe=beda690c72) | Aug 19, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f4fe59224e](https://bsd-hardware.info/?probe=f4fe59224e) | Aug 18, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [2b4ad9fd77](https://bsd-hardware.info/?probe=2b4ad9fd77) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [621207a309](https://bsd-hardware.info/?probe=621207a309) | Aug 11, 2021 |
| HP            | ProLiant DL360 Gen9         | Server      | [7760e33e84](https://bsd-hardware.info/?probe=7760e33e84) | Aug 10, 2021 |
| Shuttle       | FH81                        | Desktop     | [58ddd2da40](https://bsd-hardware.info/?probe=58ddd2da40) | Aug 08, 2021 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [6106746a7f](https://bsd-hardware.info/?probe=6106746a7f) | Aug 07, 2021 |
| NU941         | 1.0                         | Desktop     | [e76f1a177c](https://bsd-hardware.info/?probe=e76f1a177c) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [aad64262b5](https://bsd-hardware.info/?probe=aad64262b5) | Jul 29, 2021 |
| Unknown       | PICO PC                     | Desktop     | [47f932c3d3](https://bsd-hardware.info/?probe=47f932c3d3) | Jul 29, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| Biostar       | A88M                        | Desktop     | [f9d3b78d58](https://bsd-hardware.info/?probe=f9d3b78d58) | Jul 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [41e0c49bcb](https://bsd-hardware.info/?probe=41e0c49bcb) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [05180e292a](https://bsd-hardware.info/?probe=05180e292a) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| HP            | 213D A01                    | Desktop     | [3b518acc68](https://bsd-hardware.info/?probe=3b518acc68) | Jul 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [17938ca56f](https://bsd-hardware.info/?probe=17938ca56f) | Jul 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [46aaff0a7c](https://bsd-hardware.info/?probe=46aaff0a7c) | Jul 14, 2021 |
| HP            | 0AE8h C                     | Desktop     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [18d373b2d3](https://bsd-hardware.info/?probe=18d373b2d3) | Jul 06, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [d8bd1a3025](https://bsd-hardware.info/?probe=d8bd1a3025) | Jul 05, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [3e1240d256](https://bsd-hardware.info/?probe=3e1240d256) | Jul 05, 2021 |
| PC Engines    | apu4                        | Desktop     | [18a1374b95](https://bsd-hardware.info/?probe=18a1374b95) | Jul 04, 2021 |
| Biostar       | B450MH                      | Desktop     | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Dell          | Latitude E6410              | Notebook    | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [1b35a7ea0a](https://bsd-hardware.info/?probe=1b35a7ea0a) | Jun 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [629973b03e](https://bsd-hardware.info/?probe=629973b03e) | Jun 26, 2021 |
| Intel CNCT... | Unknown                     | Desktop     | [d2298356a0](https://bsd-hardware.info/?probe=d2298356a0) | Jun 22, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | Notebook    | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [287ec8a2ee](https://bsd-hardware.info/?probe=287ec8a2ee) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [e6a66eac0b](https://bsd-hardware.info/?probe=e6a66eac0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [c7b4a17b7d](https://bsd-hardware.info/?probe=c7b4a17b7d) | Jun 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [c3f7e818ae](https://bsd-hardware.info/?probe=c3f7e818ae) | Jun 18, 2021 |
| HPE           | ML10Gen9                    | Server      | [1a2b1b407b](https://bsd-hardware.info/?probe=1a2b1b407b) | Jun 17, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [5ccdc16de4](https://bsd-hardware.info/?probe=5ccdc16de4) | Jun 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [9062f35935](https://bsd-hardware.info/?probe=9062f35935) | Jun 10, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [2bb2632198](https://bsd-hardware.info/?probe=2bb2632198) | Jun 04, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [23751b05a9](https://bsd-hardware.info/?probe=23751b05a9) | Jun 01, 2021 |
| PC Engines    | APU2                        | Desktop     | [c5f1ffd6c0](https://bsd-hardware.info/?probe=c5f1ffd6c0) | May 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cd60e38216](https://bsd-hardware.info/?probe=cd60e38216) | May 30, 2021 |
| HP            | 213D A01                    | Desktop     | [de3d6dcdf5](https://bsd-hardware.info/?probe=de3d6dcdf5) | May 22, 2021 |
| HP            | 18E7                        | Desktop     | [56a672af0a](https://bsd-hardware.info/?probe=56a672af0a) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [b7ea8547ce](https://bsd-hardware.info/?probe=b7ea8547ce) | May 15, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [03d2a695b2](https://bsd-hardware.info/?probe=03d2a695b2) | May 15, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| EVGA          | X299 FTW K                  | Desktop     | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [cc49321b12](https://bsd-hardware.info/?probe=cc49321b12) | May 11, 2021 |
| Dell          | 03X6X0 A08                  | Server      | [ede56150a6](https://bsd-hardware.info/?probe=ede56150a6) | May 10, 2021 |
| Biostar       | A88M                        | Desktop     | [74c3afbf45](https://bsd-hardware.info/?probe=74c3afbf45) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| Toshiba       | TECRA M11                   | Notebook    | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [a707beae6f](https://bsd-hardware.info/?probe=a707beae6f) | May 02, 2021 |
| Yanling       | YL-KBR6L Ver:1.01           | Desktop     | [0cddbdee33](https://bsd-hardware.info/?probe=0cddbdee33) | May 01, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [1653ea52ce](https://bsd-hardware.info/?probe=1653ea52ce) | Apr 29, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7636bce7be](https://bsd-hardware.info/?probe=7636bce7be) | Apr 27, 2021 |
| Dell          | 0WR7PY A02                  | Desktop     | [1a780b9a95](https://bsd-hardware.info/?probe=1a780b9a95) | Apr 27, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [d218181abb](https://bsd-hardware.info/?probe=d218181abb) | Apr 26, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [81610a700d](https://bsd-hardware.info/?probe=81610a700d) | Apr 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f888bd5312](https://bsd-hardware.info/?probe=f888bd5312) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7dacccd5f5](https://bsd-hardware.info/?probe=7dacccd5f5) | Apr 18, 2021 |
| Samsung       | NC10                        | Notebook    | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [1cef60d042](https://bsd-hardware.info/?probe=1cef60d042) | Apr 13, 2021 |
| Samsung       | NC10                        | Notebook    | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [903d74f8e7](https://bsd-hardware.info/?probe=903d74f8e7) | Apr 12, 2021 |
| Unknown       | PICO PC                     | Desktop     | [8ab959af5c](https://bsd-hardware.info/?probe=8ab959af5c) | Apr 11, 2021 |
| Biostar       | A88M                        | Desktop     | [6fc307ade8](https://bsd-hardware.info/?probe=6fc307ade8) | Apr 09, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [563ad840b0](https://bsd-hardware.info/?probe=563ad840b0) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [9eafdd3e07](https://bsd-hardware.info/?probe=9eafdd3e07) | Apr 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [5393389555](https://bsd-hardware.info/?probe=5393389555) | Apr 05, 2021 |
| Dell          | 0TP412                      | Desktop     | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [c366bef9bf](https://bsd-hardware.info/?probe=c366bef9bf) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| Dell          | 05KX61 A00                  | Server      | [56a394ac67](https://bsd-hardware.info/?probe=56a394ac67) | Mar 27, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [12909e67d4](https://bsd-hardware.info/?probe=12909e67d4) | Mar 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [159f39df79](https://bsd-hardware.info/?probe=159f39df79) | Mar 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [a81f03223e](https://bsd-hardware.info/?probe=a81f03223e) | Mar 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [04d2c36bec](https://bsd-hardware.info/?probe=04d2c36bec) | Mar 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| HP            | 1825                        | Desktop     | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [192451364a](https://bsd-hardware.info/?probe=192451364a) | Mar 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d7790b678b](https://bsd-hardware.info/?probe=d7790b678b) | Mar 16, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| Quanmax       | spo-book TECH QUAD B1       | Desktop     | [3e479a0551](https://bsd-hardware.info/?probe=3e479a0551) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| Apple         | iMac12,1                    | All in one  | [17466db7fd](https://bsd-hardware.info/?probe=17466db7fd) | Mar 14, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| PC Engines    | APU2                        | Desktop     | [14142a990a](https://bsd-hardware.info/?probe=14142a990a) | Mar 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [1ad8d8132f](https://bsd-hardware.info/?probe=1ad8d8132f) | Mar 09, 2021 |
| Toshiba       | Satellite Pro U400          | Notebook    | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | Desktop     | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f27578615f](https://bsd-hardware.info/?probe=f27578615f) | Mar 05, 2021 |
| Dell          | Latitude E5570              | Notebook    | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [99448b6fad](https://bsd-hardware.info/?probe=99448b6fad) | Mar 02, 2021 |
| ZOTAC         | Board                       | Mini pc     | [b8a097931c](https://bsd-hardware.info/?probe=b8a097931c) | Mar 01, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [d106f46dde](https://bsd-hardware.info/?probe=d106f46dde) | Mar 01, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Dell          | 0DRR0P A02                  | Server      | [b72db7df7f](https://bsd-hardware.info/?probe=b72db7df7f) | Feb 25, 2021 |
| Shuttle       | FS61                        | Desktop     | [3016999a76](https://bsd-hardware.info/?probe=3016999a76) | Feb 25, 2021 |
| Unknown       | YL-SKUL6                    | Desktop     | [96d7fbef45](https://bsd-hardware.info/?probe=96d7fbef45) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| Acer          | RS780HVF                    | Desktop     | [3367ae4413](https://bsd-hardware.info/?probe=3367ae4413) | Feb 24, 2021 |
| ASUSTek       | P8B-M SeriesG               | Server      | [04c5c07d61](https://bsd-hardware.info/?probe=04c5c07d61) | Feb 24, 2021 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| Biostar       | A88M                        | Desktop     | [2d4a32fbc3](https://bsd-hardware.info/?probe=2d4a32fbc3) | Feb 22, 2021 |
| Biostar       | A88M                        | Desktop     | [7ff97a241a](https://bsd-hardware.info/?probe=7ff97a241a) | Feb 22, 2021 |
| MSI           | A78M-E35                    | Desktop     | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [3f0003e9a2](https://bsd-hardware.info/?probe=3f0003e9a2) | Feb 19, 2021 |
| GEO           | GeoBook3                    | Notebook    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [366f8d1eaf](https://bsd-hardware.info/?probe=366f8d1eaf) | Feb 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [d1ad5d61d2](https://bsd-hardware.info/?probe=d1ad5d61d2) | Feb 17, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| Gigabyte      | M68MT-S2                    | Desktop     | [5d94572e10](https://bsd-hardware.info/?probe=5d94572e10) | Feb 16, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [27b11c7a56](https://bsd-hardware.info/?probe=27b11c7a56) | Feb 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a3380d4b0c](https://bsd-hardware.info/?probe=a3380d4b0c) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [3c043807ba](https://bsd-hardware.info/?probe=3c043807ba) | Feb 15, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [62e8f472f6](https://bsd-hardware.info/?probe=62e8f472f6) | Feb 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [ad9283aae7](https://bsd-hardware.info/?probe=ad9283aae7) | Feb 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7313a6d6e2](https://bsd-hardware.info/?probe=7313a6d6e2) | Feb 14, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | Notebook    | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Dell          | Latitude E6420              | Notebook    | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| Shuttle       | DS10U                       | Desktop     | [aef3ca0794](https://bsd-hardware.info/?probe=aef3ca0794) | Feb 12, 2021 |
| Supermicro    | X11DPi-NT                   | Server      | [d088fbcf53](https://bsd-hardware.info/?probe=d088fbcf53) | Feb 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [c1a950c4b9](https://bsd-hardware.info/?probe=c1a950c4b9) | Feb 11, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [f9f21da0eb](https://bsd-hardware.info/?probe=f9f21da0eb) | Feb 11, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [ad0f0dde9d](https://bsd-hardware.info/?probe=ad0f0dde9d) | Feb 10, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [5ab9b894a5](https://bsd-hardware.info/?probe=5ab9b894a5) | Feb 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [435f081b3b](https://bsd-hardware.info/?probe=435f081b3b) | Feb 09, 2021 |
| Alienware     | M18xR1                      | Notebook    | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [7a8ab8feaf](https://bsd-hardware.info/?probe=7a8ab8feaf) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | Notebook    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Sony          | VPCF12C5E                   | Notebook    | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [5c09abed71](https://bsd-hardware.info/?probe=5c09abed71) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [c79ea5055f](https://bsd-hardware.info/?probe=c79ea5055f) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | Desktop     | [222778ae2b](https://bsd-hardware.info/?probe=222778ae2b) | Feb 05, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [09f8c3657f](https://bsd-hardware.info/?probe=09f8c3657f) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [f827129438](https://bsd-hardware.info/?probe=f827129438) | Feb 04, 2021 |
| Unknown       | PICO PC                     | Desktop     | [de1cd4e050](https://bsd-hardware.info/?probe=de1cd4e050) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [b192745cde](https://bsd-hardware.info/?probe=b192745cde) | Feb 03, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | Desktop     | [c11da3972d](https://bsd-hardware.info/?probe=c11da3972d) | Feb 03, 2021 |
| Protectli     | FW4B                        | Desktop     | [5334bf8761](https://bsd-hardware.info/?probe=5334bf8761) | Feb 03, 2021 |
| Deciso        | Netboard A10                | Desktop     | [a3f5b21dff](https://bsd-hardware.info/?probe=a3f5b21dff) | Feb 03, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| Supermicro    | X8SIU                       | Desktop     | [57fbc2cb9a](https://bsd-hardware.info/?probe=57fbc2cb9a) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [cc7f2d0b64](https://bsd-hardware.info/?probe=cc7f2d0b64) | Feb 02, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [6b9511bf39](https://bsd-hardware.info/?probe=6b9511bf39) | Jan 31, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Unknown       | YL-SKUL6                    | Desktop     | [9f0538d38b](https://bsd-hardware.info/?probe=9f0538d38b) | Jan 31, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [996a6207dc](https://bsd-hardware.info/?probe=996a6207dc) | Jan 30, 2021 |
| Intel         | NUC5PGYB H78167-102         | Mini pc     | [ad190621be](https://bsd-hardware.info/?probe=ad190621be) | Jan 28, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| ASRock        | J3455M                      | Desktop     | [c90667d62c](https://bsd-hardware.info/?probe=c90667d62c) | Jan 27, 2021 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5e6fbbd1ee](https://bsd-hardware.info/?probe=5e6fbbd1ee) | Jan 27, 2021 |
| Lenovo        | Board                       | Desktop     | [da81aa7cb9](https://bsd-hardware.info/?probe=da81aa7cb9) | Jan 26, 2021 |
| AZW           | GK55                        | Desktop     | [077fedae7d](https://bsd-hardware.info/?probe=077fedae7d) | Jan 26, 2021 |
| Silver Pea... | Network Appliance Platfo... | Firewall    | [6f058f9a0c](https://bsd-hardware.info/?probe=6f058f9a0c) | Jan 25, 2021 |
| AZW           | GK55                        | Desktop     | [db3fc2c7b2](https://bsd-hardware.info/?probe=db3fc2c7b2) | Jan 25, 2021 |
| Acer          | Aspire V5-531               | Notebook    | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [aa5782d83e](https://bsd-hardware.info/?probe=aa5782d83e) | Jan 24, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6d11e7b348](https://bsd-hardware.info/?probe=6d11e7b348) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [aeb42f8919](https://bsd-hardware.info/?probe=aeb42f8919) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [5b3be23f50](https://bsd-hardware.info/?probe=5b3be23f50) | Jan 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [8720b818b5](https://bsd-hardware.info/?probe=8720b818b5) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7829f75120](https://bsd-hardware.info/?probe=7829f75120) | Jan 23, 2021 |
| Jetway        | 1.0                         | Desktop     | [8f47246cdf](https://bsd-hardware.info/?probe=8f47246cdf) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [f952cac718](https://bsd-hardware.info/?probe=f952cac718) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [29c88c0b95](https://bsd-hardware.info/?probe=29c88c0b95) | Jan 22, 2021 |
| Protectli     | FW4B                        | Desktop     | [ea6fcc20bc](https://bsd-hardware.info/?probe=ea6fcc20bc) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1722f1824f](https://bsd-hardware.info/?probe=1722f1824f) | Jan 22, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2e630c3c54](https://bsd-hardware.info/?probe=2e630c3c54) | Jan 22, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [6821383a38](https://bsd-hardware.info/?probe=6821383a38) | Jan 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [526fd1f7c9](https://bsd-hardware.info/?probe=526fd1f7c9) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [0fac28f2bf](https://bsd-hardware.info/?probe=0fac28f2bf) | Jan 21, 2021 |
| Shuttle       | FS67U                       | Desktop     | [8ed524df62](https://bsd-hardware.info/?probe=8ed524df62) | Jan 20, 2021 |
| Protectli     | FW4A Ver                    | Desktop     | [5725505d31](https://bsd-hardware.info/?probe=5725505d31) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [49463c91f7](https://bsd-hardware.info/?probe=49463c91f7) | Jan 19, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [fcedf7a28d](https://bsd-hardware.info/?probe=fcedf7a28d) | Jan 19, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [bb4f8afc82](https://bsd-hardware.info/?probe=bb4f8afc82) | Jan 09, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |
| Pegatron      | T12Ah                       | Notebook    | [427bb18c90](https://bsd-hardware.info/?probe=427bb18c90) | Dec 27, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [8195760dd6](https://bsd-hardware.info/?probe=8195760dd6) | Dec 23, 2020 |
| Samsung       | N140                        | Notebook    | [cab912c576](https://bsd-hardware.info/?probe=cab912c576) | Dec 21, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [20c77fd91b](https://bsd-hardware.info/?probe=20c77fd91b) | Dec 16, 2020 |
| Gigabyte      | Z97P-D3                     | Desktop     | [588af8f5b3](https://bsd-hardware.info/?probe=588af8f5b3) | Dec 16, 2020 |
| Acer          | Aspire X1440                | Desktop     | [6100b30349](https://bsd-hardware.info/?probe=6100b30349) | Dec 15, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [2b478c0d01](https://bsd-hardware.info/?probe=2b478c0d01) | Dec 08, 2020 |
| Apple         | Xserve3,1                   | Desktop     | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1076ee5826](https://bsd-hardware.info/?probe=1076ee5826) | Dec 04, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ec1363a9ea](https://bsd-hardware.info/?probe=ec1363a9ea) | Dec 04, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [f62cab95dd](https://bsd-hardware.info/?probe=f62cab95dd) | Dec 03, 2020 |
| MSI           | B450 GAMING PLUS            | Desktop     | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [1f3fa432dc](https://bsd-hardware.info/?probe=1f3fa432dc) | Nov 21, 2020 |
| ASRock        | IMB-191                     | Desktop     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| HP            | Compaq nx7400 (RU430ET#A... | Notebook    | [c9c7bae008](https://bsd-hardware.info/?probe=c9c7bae008) | Nov 01, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [e5c99b958d](https://bsd-hardware.info/?probe=e5c99b958d) | Oct 31, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [f9a374a310](https://bsd-hardware.info/?probe=f9a374a310) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Intel         | CRESCENTBAY                 | Desktop     | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | Notebook    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| ASRock        | IMB-191                     | Desktop     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | Desktop     | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Gigabyte      | MZ32-AR0-00 01000100        | Server      | [93e2466fc6](https://bsd-hardware.info/?probe=93e2466fc6) | Oct 01, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [6cd0b0ed25](https://bsd-hardware.info/?probe=6cd0b0ed25) | Sep 28, 2020 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [b9b460d9e2](https://bsd-hardware.info/?probe=b9b460d9e2) | Sep 28, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [d7d299f9fc](https://bsd-hardware.info/?probe=d7d299f9fc) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec434bfdcd](https://bsd-hardware.info/?probe=ec434bfdcd) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [628b379afb](https://bsd-hardware.info/?probe=628b379afb) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [decfd42a65](https://bsd-hardware.info/?probe=decfd42a65) | Sep 13, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [9168df8552](https://bsd-hardware.info/?probe=9168df8552) | Aug 08, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Google        | Lulu                        | Notebook    | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Biostar       | B450MH                      | Desktop     | [4ad280f947](https://bsd-hardware.info/?probe=4ad280f947) | Aug 02, 2020 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [6b015a340b](https://bsd-hardware.info/?probe=6b015a340b) | Jul 31, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [cef5a64eb8](https://bsd-hardware.info/?probe=cef5a64eb8) | Jul 11, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [2394ca7e03](https://bsd-hardware.info/?probe=2394ca7e03) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [4f34d107bc](https://bsd-hardware.info/?probe=4f34d107bc) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [067478e4be](https://bsd-hardware.info/?probe=067478e4be) | Jul 03, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | Desktop     | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| HP            | 213D A01                    | Desktop     | [23f8adb299](https://bsd-hardware.info/?probe=23f8adb299) | May 25, 2020 |
| Lenovo        | ThinkPad X220 42902WU       | Notebook    | [e8a2f44b21](https://bsd-hardware.info/?probe=e8a2f44b21) | May 24, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 20.7.8      | 16        | 2.84%   |
| helloSystem 0.7.0    | 14        | 2.48%   |
| FreeBSD 14.0-CURRENT | 14        | 2.48%   |
| FreeBSD 13.0         | 14        | 2.48%   |
| OPNsense 22.7.10     | 13        | 2.3%    |
| helloSystem 0.5.0    | 12        | 2.13%   |
| OPNsense 22.1        | 11        | 1.95%   |
| OPNsense 21.7.7      | 11        | 1.95%   |
| OPNsense 21.1.5      | 11        | 1.95%   |
| OPNsense 22.7.4      | 10        | 1.77%   |
| OPNsense 22.1.6      | 10        | 1.77%   |
| helloSystem 0.4.0    | 10        | 1.77%   |
| OPNsense 23.1.5      | 9         | 1.6%    |
| OPNsense 23.1.1      | 9         | 1.6%    |
| OPNsense 22.1.10     | 9         | 1.6%    |
| OPNsense 21.7.3      | 9         | 1.6%    |
| OPNsense 21.7.1      | 9         | 1.6%    |
| OPNsense 21.1.1      | 9         | 1.6%    |
| OPNsense 21.1        | 9         | 1.6%    |
| GhostBSD 20.04.02    | 9         | 1.6%    |
| OPNsense 23.1.9      | 8         | 1.42%   |
| OPNsense 22.7.7      | 8         | 1.42%   |
| OPNsense 22.7.6      | 8         | 1.42%   |
| OPNsense 22.7.2      | 8         | 1.42%   |
| OPNsense 21.1.7      | 8         | 1.42%   |
| OpenBSD 6.8          | 8         | 1.42%   |
| FreeBSD 13.1         | 8         | 1.42%   |
| OPNsense 23.1.6      | 7         | 1.24%   |
| OPNsense 23.1.3      | 7         | 1.24%   |
| OPNsense 22.1.8      | 7         | 1.24%   |
| OPNsense 21.1.4      | 7         | 1.24%   |
| OPNsense 21.1.3      | 7         | 1.24%   |
| OPNsense 21.1.2      | 7         | 1.24%   |
| helloSystem 0.8.1    | 7         | 1.24%   |
| FreeBSD 12.2         | 7         | 1.24%   |
| OPNsense 23.1.7      | 6         | 1.06%   |
| OPNsense 22.1.4      | 6         | 1.06%   |
| OPNsense 21.7.8      | 6         | 1.06%   |
| helloSystem 0.8.0    | 6         | 1.06%   |
| FreeBSD 13.0-STABLE  | 6         | 1.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 233       | 54.44%  |
| FreeBSD     | 82        | 19.16%  |
| helloSystem | 52        | 12.15%  |
| OpenBSD     | 24        | 5.61%   |
| GhostBSD    | 15        | 3.5%    |
| NomadBSD    | 11        | 2.57%   |
| NetBSD      | 5         | 1.17%   |
| XigmaNAS    | 3         | 0.7%    |
| pfSense     | 1         | 0.23%   |
| FuryBSD     | 1         | 0.23%   |
| DragonFly   | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 409       | 97.38%  |
| arm64 | 8         | 1.9%    |
| i386  | 2         | 0.48%   |
| riscv | 1         | 0.24%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Console          | 275       | 63.66%  |
| helloDesktop     | 58        | 13.43%  |
| KDE5             | 24        | 5.56%   |
| XFCE             | 19        | 4.4%    |
| MATE             | 16        | 3.7%    |
| Openbox          | 9         | 2.08%   |
| fvwm             | 7         | 1.62%   |
| GNOME            | 6         | 1.39%   |
| i3               | 3         | 0.69%   |
| Cinnamon         | 3         | 0.69%   |
| xinitrc          | 2         | 0.46%   |
| TWM              | 2         | 0.46%   |
| PekWM            | 1         | 0.23%   |
| Metacity (Marco) | 1         | 0.23%   |
| Fluxbox          | 1         | 0.23%   |
| Enlightenment    | 1         | 0.23%   |
| DWM              | 1         | 0.23%   |
| CDE              | 1         | 0.23%   |
| Budgie           | 1         | 0.23%   |
| AwesomeWM        | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 276       | 64.79%  |
| X11     | 145       | 34.04%  |
| Wayland | 5         | 1.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 310       | 71.93%  |
| SLiM    | 66        | 15.31%  |
| SDDM    | 29        | 6.73%   |
| LightDM | 17        | 3.94%   |
| XDM     | 5         | 1.16%   |
| GDM     | 3         | 0.7%    |
| Ly      | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 282       | 64.24%  |
| en_US           | 62        | 14.12%  |
| C               | 58        | 13.21%  |
| en_GB           | 27        | 6.15%   |
| en              | 3         | 0.68%   |
| ru_RU           | 2         | 0.46%   |
| en_GB.US-ASCII  | 2         | 0.46%   |
| it_CH           | 1         | 0.23%   |
| fr_FR           | 1         | 0.23%   |
| en_GB.ISO8859-1 | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 363       | 85.21%  |
| BIOS | 63        | 14.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 235       | 54.27%  |
| Zfs     | 158       | 36.49%  |
| Ffs     | 24        | 5.54%   |
| Cd9660  | 14        | 3.23%   |
| Hammer2 | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 390       | 92.2%   |
| MBR     | 25        | 5.91%   |
| Unknown | 7         | 1.65%   |
| BSD     | 1         | 0.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 56        | 13.33%  |
| Lenovo                  | 40        | 9.52%   |
| Hewlett-Packard         | 39        | 9.29%   |
| Unknown                 | 36        | 8.57%   |
| ASUSTek Computer        | 29        | 6.9%    |
| Intel                   | 26        | 6.19%   |
| Gigabyte Technology     | 21        | 5%      |
| ASRock                  | 14        | 3.33%   |
| AMI                     | 12        | 2.86%   |
| Apple                   | 11        | 2.62%   |
| PC Engines              | 9         | 2.14%   |
| Protectli               | 8         | 1.9%    |
| MSI                     | 7         | 1.67%   |
| Fujitsu                 | 7         | 1.67%   |
| Shuttle                 | 6         | 1.43%   |
| Samsung Electronics     | 6         | 1.43%   |
| Supermicro              | 5         | 1.19%   |
| Raspberry Pi Foundation | 5         | 1.19%   |
| Deciso                  | 5         | 1.19%   |
| Acer                    | 5         | 1.19%   |
| Toshiba                 | 4         | 0.95%   |
| Techvision              | 3         | 0.71%   |
| HUAWEI                  | 3         | 0.71%   |
| HPE                     | 3         | 0.71%   |
| Biostar                 | 3         | 0.71%   |
| ZOTAC                   | 2         | 0.48%   |
| Yanling                 | 2         | 0.48%   |
| Star Labs               | 2         | 0.48%   |
| Sophos                  | 2         | 0.48%   |
| Inventec                | 2         | 0.48%   |
| IceWhale Technology     | 2         | 0.48%   |
| AZW                     | 2         | 0.48%   |
| ASRockRack              | 2         | 0.48%   |
| Winston Marriot         | 1         | 0.24%   |
| TUXEDO                  | 1         | 0.24%   |
| System76                | 1         | 0.24%   |
| Sony UK                 | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| Silver Peak Systems     | 1         | 0.24%   |
| Seeed Studio            | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 37        | 8.81%   |
| AMI Aptio CRB                       | 9         | 2.14%   |
| Intel Q3XXG4-P V1.0                 | 8         | 1.9%    |
| PC Engines APU2                     | 5         | 1.19%   |
| Dell Wyse 5070 Extended Thin Client | 5         | 1.19%   |
| ASUS All Series                     | 5         | 1.19%   |
| Protectli FW6                       | 4         | 0.95%   |
| HP t730 Thin Client                 | 4         | 0.95%   |
| Dell OptiPlex 7010                  | 4         | 0.95%   |
| Techvision TVI7309X                 | 3         | 0.71%   |
| RPi Raspberry Pi                    | 3         | 0.71%   |
| Protectli FW4B                      | 3         | 0.71%   |
| PC Engines apu4                     | 3         | 0.71%   |
| Intel SHARKBAY                      | 3         | 0.71%   |
| HP t620 PLUS Quad Core TC           | 3         | 0.71%   |
| HP EliteBook 8570p                  | 3         | 0.71%   |
| Fujitsu FUTRO S920                  | 3         | 0.71%   |
| Dell OptiPlex 790                   | 3         | 0.71%   |
| Dell OptiPlex 760                   | 3         | 0.71%   |
| Dell OptiPlex 3020                  | 3         | 0.71%   |
| Yanling YL-KBR6L                    | 2         | 0.48%   |
| Supermicro Super Server             | 2         | 0.48%   |
| Sophos SG                           | 2         | 0.48%   |
| Lenovo ThinkCentre M920s 10SJ0041UK | 2         | 0.48%   |
| Lenovo ThinkCentre E73 10DS0015UK   | 2         | 0.48%   |
| IceWhale ZimaBoard 832 ZMB          | 2         | 0.48%   |
| HP Z600 Workstation                 | 2         | 0.48%   |
| HP ProLiant MicroServer Gen8        | 2         | 0.48%   |
| HP ProLiant DL360 Gen9              | 2         | 0.48%   |
| Gigabyte B450M DS3H                 | 2         | 0.48%   |
| Dell XPS 13 9343                    | 2         | 0.48%   |
| Dell PowerEdge R610                 | 2         | 0.48%   |
| Dell PowerEdge R210 II              | 2         | 0.48%   |
| Dell PowerEdge R210                 | 2         | 0.48%   |
| Dell OptiPlex 390                   | 2         | 0.48%   |
| Dell Inspiron 3793                  | 2         | 0.48%   |
| Deciso OPNsense Appliance           | 2         | 0.48%   |
| ASUS ZenBook S UX391UA              | 2         | 0.48%   |
| ASUS ROG STRIX X570-E GAMING        | 2         | 0.48%   |
| ASUS PRIME H510M-E                  | 2         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 37        | 8.81%   |
| Lenovo ThinkPad     | 24        | 5.71%   |
| Dell OptiPlex       | 23        | 5.48%   |
| Dell PowerEdge      | 14        | 3.33%   |
| Lenovo ThinkCentre  | 12        | 2.86%   |
| AMI Aptio           | 9         | 2.14%   |
| Intel Q3XXG4-P      | 8         | 1.9%    |
| HP ProLiant         | 8         | 1.9%    |
| ASUS ROG            | 6         | 1.43%   |
| ASUS PRIME          | 6         | 1.43%   |
| RPi Raspberry       | 5         | 1.19%   |
| PC Engines APU2     | 5         | 1.19%   |
| Dell Wyse           | 5         | 1.19%   |
| Dell Latitude       | 5         | 1.19%   |
| ASUS All            | 5         | 1.19%   |
| Acer Aspire         | 5         | 1.19%   |
| Protectli FW6       | 4         | 0.95%   |
| HP t730             | 4         | 0.95%   |
| HP EliteBook        | 4         | 0.95%   |
| Fujitsu FUTRO       | 4         | 0.95%   |
| Toshiba Satellite   | 3         | 0.71%   |
| Techvision TVI7309X | 3         | 0.71%   |
| Protectli FW4B      | 3         | 0.71%   |
| PC Engines apu4     | 3         | 0.71%   |
| Intel SHARKBAY      | 3         | 0.71%   |
| HP t620             | 3         | 0.71%   |
| HP Pavilion         | 3         | 0.71%   |
| HP EliteDesk        | 3         | 0.71%   |
| Dell Precision      | 3         | 0.71%   |
| Dell Inspiron       | 3         | 0.71%   |
| Apple MacBookPro5   | 3         | 0.71%   |
| Yanling YL-KBR6L    | 2         | 0.48%   |
| Supermicro Super    | 2         | 0.48%   |
| Sophos SG           | 2         | 0.48%   |
| Lenovo IdeaPad      | 2         | 0.48%   |
| IceWhale ZimaBoard  | 2         | 0.48%   |
| HPE ProLiant        | 2         | 0.48%   |
| HP Z600             | 2         | 0.48%   |
| HP ProDesk          | 2         | 0.48%   |
| HP ProBook          | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 44        | 10.48%  |
| 2018    | 40        | 9.52%   |
| 2014    | 40        | 9.52%   |
| 2016    | 37        | 8.81%   |
| 2019    | 35        | 8.33%   |
| 2013    | 32        | 7.62%   |
| 2022    | 31        | 7.38%   |
| 2021    | 30        | 7.14%   |
| 2015    | 26        | 6.19%   |
| 2010    | 19        | 4.52%   |
| 2011    | 18        | 4.29%   |
| 2017    | 17        | 4.05%   |
| 2012    | 17        | 4.05%   |
| 2009    | 14        | 3.33%   |
| Unknown | 6         | 1.43%   |
| 2023    | 5         | 1.19%   |
| 2008    | 5         | 1.19%   |
| 2007    | 4         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 253       | 60.24%  |
| Notebook       | 94        | 22.38%  |
| Mini pc        | 34        | 8.1%    |
| Server         | 26        | 6.19%   |
| Firewall       | 5         | 1.19%   |
| System on chip | 4         | 0.95%   |
| All in one     | 3         | 0.71%   |
| Convertible    | 1         | 0.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 404       | 96.19%  |
| Yes  | 16        | 3.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 187       | 44.21%  |
| 16.01-24.0      | 88        | 20.8%   |
| 4.01-8.0        | 80        | 18.91%  |
| 32.01-64.0      | 26        | 6.15%   |
| 2.01-3.0        | 14        | 3.31%   |
| 64.01-256.0     | 14        | 3.31%   |
| 3.01-4.0        | 5         | 1.18%   |
| 24.01-32.0      | 4         | 0.95%   |
| 0.51-1.0        | 2         | 0.47%   |
| More than 256.0 | 1         | 0.24%   |
| 1.01-2.0        | 1         | 0.24%   |
| Unknown         | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 245       | 55.94%  |
| 0.51-1.0    | 116       | 26.48%  |
| 1.01-2.0    | 35        | 7.99%   |
| 2.01-3.0    | 13        | 2.97%   |
| 3.01-4.0    | 10        | 2.28%   |
| 4.01-8.0    | 6         | 1.37%   |
| Unknown     | 5         | 1.14%   |
| 24.01-32.0  | 2         | 0.46%   |
| 8.01-16.0   | 2         | 0.46%   |
| 32.01-64.0  | 1         | 0.23%   |
| 64.01-256.0 | 1         | 0.23%   |
| 16.01-24.0  | 1         | 0.23%   |
| 0           | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 296       | 67.89%  |
| 2      | 60        | 13.76%  |
| 0      | 38        | 8.72%   |
| 3      | 17        | 3.9%    |
| 4      | 8         | 1.83%   |
| 5      | 7         | 1.61%   |
| 8      | 3         | 0.69%   |
| 7      | 3         | 0.69%   |
| 6      | 2         | 0.46%   |
| 17     | 1         | 0.23%   |
| 14     | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 338       | 79.53%  |
| Yes       | 87        | 20.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 392       | 93.33%  |
| No        | 28        | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 255       | 60.28%  |
| Yes       | 168       | 39.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 316       | 74.53%  |
| Yes       | 108       | 25.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 420       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 59        | 11.9%   |
| Glasgow             | 8         | 1.61%   |
| Brighton            | 8         | 1.61%   |
| Newcastle upon Tyne | 7         | 1.41%   |
| Cambridge           | 7         | 1.41%   |
| Bristol             | 6         | 1.21%   |
| Birmingham          | 6         | 1.21%   |
| Watford             | 5         | 1.01%   |
| Swindon             | 5         | 1.01%   |
| Sheffield           | 5         | 1.01%   |
| Kensington          | 5         | 1.01%   |
| Hull                | 5         | 1.01%   |
| Coventry            | 5         | 1.01%   |
| City of London      | 5         | 1.01%   |
| Stourbridge         | 4         | 0.81%   |
| Shoreham-by-Sea     | 4         | 0.81%   |
| Poplar              | 4         | 0.81%   |
| Milton Keynes       | 4         | 0.81%   |
| Leicester           | 4         | 0.81%   |
| Leeds               | 4         | 0.81%   |
| Islington           | 4         | 0.81%   |
| Greenwich           | 4         | 0.81%   |
| York                | 3         | 0.6%    |
| Wolverhampton       | 3         | 0.6%    |
| Woking              | 3         | 0.6%    |
| Wittersham          | 3         | 0.6%    |
| Walsall             | 3         | 0.6%    |
| Southampton         | 3         | 0.6%    |
| Scunthorpe          | 3         | 0.6%    |
| Ruthin              | 3         | 0.6%    |
| Reading             | 3         | 0.6%    |
| Notting Hill Gate   | 3         | 0.6%    |
| Mansfield           | 3         | 0.6%    |
| Manchester          | 3         | 0.6%    |
| Malton              | 3         | 0.6%    |
| Liverpool           | 3         | 0.6%    |
| Leatherhead         | 3         | 0.6%    |
| Gloucester          | 3         | 0.6%    |
| Egham               | 3         | 0.6%    |
| East Grinstead      | 3         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 77        | 137    | 16.08%  |
| WDC                 | 49        | 87     | 10.23%  |
| Seagate             | 41        | 98     | 8.56%   |
| Crucial             | 41        | 62     | 8.56%   |
| Kingston            | 37        | 57     | 7.72%   |
| Toshiba             | 23        | 62     | 4.8%    |
| SanDisk             | 22        | 26     | 4.59%   |
| Transcend           | 16        | 21     | 3.34%   |
| Intel               | 15        | 18     | 3.13%   |
| Hitachi             | 13        | 17     | 2.71%   |
| Hoodisk             | 11        | 17     | 2.3%    |
| Phison              | 10        | 14     | 2.09%   |
| HGST                | 9         | 35     | 1.88%   |
| SK hynix            | 8         | 10     | 1.67%   |
| Hewlett-Packard     | 8         | 25     | 1.67%   |
| China               | 7         | 7      | 1.46%   |
| LITEONIT            | 6         | 7      | 1.25%   |
| Micron Technology   | 5         | 6      | 1.04%   |
| Corsair             | 5         | 7      | 1.04%   |
| Apacer              | 5         | 6      | 1.04%   |
| OCZ                 | 4         | 6      | 0.84%   |
| FORESEE             | 4         | 5      | 0.84%   |
| Apple               | 4         | 5      | 0.84%   |
| A-DATA Technology   | 4         | 7      | 0.84%   |
| SPCC                | 3         | 3      | 0.63%   |
| PNY                 | 3         | 11     | 0.63%   |
| NVMe                | 3         | 3      | 0.63%   |
| Lexar               | 3         | 3      | 0.63%   |
| Intenso             | 3         | 3      | 0.63%   |
| Integral            | 3         | 5      | 0.63%   |
| Gigabyte Technology | 3         | 4      | 0.63%   |
| XUM                 | 2         | 2      | 0.42%   |
| Vaseky              | 2         | 2      | 0.42%   |
| Star Drive          | 2         | 2      | 0.42%   |
| Patriot             | 2         | 5      | 0.42%   |
| OPENBSD             | 2         | 2      | 0.42%   |
| Netac               | 2         | 6      | 0.42%   |
| Fanxiang            | 2         | 2      | 0.42%   |
| Zheino              | 1         | 1      | 0.21%   |
| UMIS                | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 7         | 1.35%   |
| Kingston SA400S37240G 240GB          | 6         | 1.16%   |
| Samsung SSD 860 EVO 500GB            | 5         | 0.96%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.96%   |
| Kingston SUV500MS120G 120GB          | 5         | 0.96%   |
| Hoodisk SSD 64GB                     | 5         | 0.96%   |
| Crucial CT500MX500SSD1 500GB         | 5         | 0.96%   |
| Crucial CT120BX500SSD1 120GB         | 5         | 0.96%   |
| Kingston SA400S37120G 120GB          | 4         | 0.77%   |
| Hoodisk SSD 32GB                     | 4         | 0.77%   |
| HGST HTS725050A7E630 500GB           | 4         | 0.77%   |
| HP RAID 1(1+0) 1TB                   | 4         | 0.77%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.77%   |
| Crucial CT1000MX500SSD1 1TB          | 4         | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB         | 3         | 0.58%   |
| Seagate ST3500418AS 500GB            | 3         | 0.58%   |
| SanDisk SSD PLUS 480GB               | 3         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.58%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.58%   |
| Samsung HM251JX 250GB                | 3         | 0.58%   |
| Phison Sabrent 1TB                   | 3         | 0.58%   |
| Kingston SUV500MS240G 240GB          | 3         | 0.58%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 3         | 0.58%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.58%   |
| XUM HX256GSSDSATA3 256GB             | 2         | 0.39%   |
| WDC WDS250G2B0B-00YS70 250GB         | 2         | 0.39%   |
| WDC WD20EZRX-22D8PB0 2TB             | 2         | 0.39%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2         | 0.39%   |
| WDC WD20EFZX-68AWUN0 2TB             | 2         | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 0.39%   |
| WDC WD1600BEVT-80A23T0 160GB         | 2         | 0.39%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 2         | 0.39%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2         | 0.39%   |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.39%   |
| Transcend TS128GMTE110S 128GB        | 2         | 0.39%   |
| Transcend TS128GMSA370 128GB         | 2         | 0.39%   |
| Toshiba HDWE140 4TB                  | 2         | 0.39%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.39%   |
| SPCC Solid State Disk 128GB          | 2         | 0.39%   |
| Seagate ST8000VN0022-2EL112 8TB      | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 98     | 29.08%  |
| WDC                 | 38        | 68     | 26.95%  |
| Toshiba             | 18        | 49     | 12.77%  |
| Hitachi             | 13        | 17     | 9.22%   |
| HGST                | 9         | 35     | 6.38%   |
| Samsung Electronics | 8         | 8      | 5.67%   |
| Hewlett-Packard     | 7         | 23     | 4.96%   |
| OPENBSD             | 2         | 2      | 1.42%   |
| NVMe                | 2         | 2      | 1.42%   |
| Fujitsu             | 1         | 6      | 0.71%   |
| Dell                | 1         | 2      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 50        | 91     | 17.61%  |
| Kingston            | 37        | 57     | 13.03%  |
| Crucial             | 35        | 56     | 12.32%  |
| SanDisk             | 22        | 26     | 7.75%   |
| Transcend           | 12        | 15     | 4.23%   |
| Intel               | 11        | 13     | 3.87%   |
| Hoodisk             | 11        | 17     | 3.87%   |
| WDC                 | 9         | 14     | 3.17%   |
| China               | 7         | 7      | 2.46%   |
| LITEONIT            | 6         | 7      | 2.11%   |
| Phison              | 5         | 6      | 1.76%   |
| Micron Technology   | 5         | 6      | 1.76%   |
| Corsair             | 5         | 7      | 1.76%   |
| Apacer              | 5         | 6      | 1.76%   |
| OCZ                 | 4         | 6      | 1.41%   |
| FORESEE             | 4         | 5      | 1.41%   |
| A-DATA Technology   | 4         | 7      | 1.41%   |
| Toshiba             | 3         | 9      | 1.06%   |
| SPCC                | 3         | 3      | 1.06%   |
| PNY                 | 3         | 9      | 1.06%   |
| Lexar               | 3         | 3      | 1.06%   |
| Intenso             | 3         | 3      | 1.06%   |
| Integral            | 3         | 5      | 1.06%   |
| Gigabyte Technology | 3         | 4      | 1.06%   |
| Apple               | 3         | 4      | 1.06%   |
| XUM                 | 2         | 2      | 0.7%    |
| Vaseky              | 2         | 2      | 0.7%    |
| SK hynix            | 2         | 2      | 0.7%    |
| Patriot             | 2         | 5      | 0.7%    |
| Netac               | 2         | 6      | 0.7%    |
| Zheino              | 1         | 1      | 0.35%   |
| TCSUNBOW            | 1         | 2      | 0.35%   |
| Star Drive          | 1         | 1      | 0.35%   |
| ShiJi               | 1         | 1      | 0.35%   |
| SATA3 60            | 1         | 1      | 0.35%   |
| OWC                 | 1         | 1      | 0.35%   |
| ORTIAL              | 1         | 3      | 0.35%   |
| NVMe                | 1         | 1      | 0.35%   |
| MicroDream          | 1         | 1      | 0.35%   |
| MARVELL             | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 261       | 428    | 60%     |
| HDD  | 115       | 311    | 26.44%  |
| NVMe | 59        | 90     | 13.56%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 344       | 739    | 85.36%  |
| NVMe | 59        | 90     | 14.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 304       | 522    | 78.15%  |
| 0.51-1.0   | 40        | 82     | 10.28%  |
| 1.01-2.0   | 24        | 52     | 6.17%   |
| 3.01-4.0   | 10        | 38     | 2.57%   |
| 4.01-10.0  | 9         | 43     | 2.31%   |
| 2.01-3.0   | 2         | 2      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 184       | 41.07%  |
| 251-500        | 68        | 15.18%  |
| 1-20           | 58        | 12.95%  |
| 51-100         | 50        | 11.16%  |
| 21-50          | 44        | 9.82%   |
| 501-1000       | 26        | 5.8%    |
| 1001-2000      | 9         | 2.01%   |
| Unknown        | 5         | 1.12%   |
| More than 3000 | 3         | 0.67%   |
| 2001-3000      | 1         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 378       | 86.1%   |
| 21-50          | 34        | 7.74%   |
| 51-100         | 10        | 2.28%   |
| 101-250        | 7         | 1.59%   |
| Unknown        | 5         | 1.14%   |
| More than 3000 | 2         | 0.46%   |
| 251-500        | 2         | 0.46%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 10     | 6.25%   |
| Seagate ST3500418AS 500GB                        | 2         | 3      | 3.13%   |
| Seagate ST3160310CS 160GB                        | 2         | 2      | 3.13%   |
| SanDisk SSD PLUS 480GB                           | 2         | 2      | 3.13%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 2         | 3      | 3.13%   |
| Samsung Electronics HM160HI 160GB                | 2         | 2      | 3.13%   |
| Crucial CT525MX300SSD1 528GB                     | 2         | 3      | 3.13%   |
| China SATA SSD 32GB                              | 2         | 2      | 3.13%   |
| WDC WD5000AAKX-221CA1 500GB                      | 1         | 1      | 1.56%   |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1         | 1      | 1.56%   |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1         | 4      | 1.56%   |
| WDC WD3200BEVT-22A23T0 320GB                     | 1         | 2      | 1.56%   |
| WDC WD3200AAJS-22B4A0 320GB                      | 1         | 1      | 1.56%   |
| WDC WD30EFRX-68EUZN0 3TB                         | 1         | 1      | 1.56%   |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 1.56%   |
| WDC WD20EFZX-68AWUN0 2TB                         | 1         | 2      | 1.56%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 1.56%   |
| WDC WD10JMVW-11AJGS0 1TB                         | 1         | 1      | 1.56%   |
| Transcend TS256GSSD320 256GB                     | 1         | 1      | 1.56%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.56%   |
| Toshiba MD04ACA400 4TB                           | 1         | 1      | 1.56%   |
| Toshiba HDWE140 4TB                              | 1         | 8      | 1.56%   |
| Toshiba DT01ACA200 2TB                           | 1         | 1      | 1.56%   |
| Toshiba DT01ABA300 3TB                           | 1         | 1      | 1.56%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 1.56%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 1.56%   |
| Seagate ST32000542AS 2TB                         | 1         | 1      | 1.56%   |
| Seagate ST250DM000-1BD141 250GB                  | 1         | 1      | 1.56%   |
| Seagate ST2000LM015-2E8174 2TB                   | 1         | 1      | 1.56%   |
| SanDisk SSD P4 16GB                              | 1         | 1      | 1.56%   |
| SanDisk SDCFHS-016G                              | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 970 EVO 500GB            | 1         | 3      | 1.56%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1         | 1      | 1.56%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 1.56%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 1.56%   |
| MARVELL SATAIII 16GB                             | 1         | 1      | 1.56%   |
| Kingston SV300S37A120G 120GB                     | 1         | 3      | 1.56%   |
| Kingston SV200S3128G 128GB                       | 1         | 1      | 1.56%   |
| Kingchuxing SSD 60GB                             | 1         | 1      | 1.56%   |
| Intel SSDSC2BB120G4 120GB                        | 1         | 2      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 15     | 16.13%  |
| Seagate             | 9         | 10     | 14.52%  |
| Samsung Electronics | 7         | 10     | 11.29%  |
| HGST                | 6         | 29     | 9.68%   |
| Toshiba             | 4         | 12     | 6.45%   |
| SanDisk             | 4         | 4      | 6.45%   |
| Crucial             | 4         | 7      | 6.45%   |
| China               | 4         | 4      | 6.45%   |
| Hitachi             | 3         | 3      | 4.84%   |
| Kingston            | 2         | 4      | 3.23%   |
| A-DATA Technology   | 2         | 3      | 3.23%   |
| Transcend           | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| MARVELL             | 1         | 1      | 1.61%   |
| Kingchuxing         | 1         | 1      | 1.61%   |
| Intel               | 1         | 2      | 1.61%   |
| Hewlett-Packard     | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 15     | 27.03%  |
| Seagate             | 9         | 10     | 24.32%  |
| HGST                | 6         | 29     | 16.22%  |
| Toshiba             | 4         | 12     | 10.81%  |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Hitachi             | 3         | 3      | 8.11%   |
| Hewlett-Packard     | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 74     | 59.02%  |
| SSD  | 24        | 32     | 39.34%  |
| NVMe | 1         | 3      | 1.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST4000NM0025 4TB  | 1         | 2      | 50%     |
| Seagate ST3160318AS 160GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 342       | 679    | 81.43%  |
| Malfunc  | 58        | 109    | 13.81%  |
| Detected | 18        | 38     | 4.29%   |
| Failed   | 2         | 3      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 310       | 62.37%  |
| AMD                                     | 70        | 14.08%  |
| Samsung Electronics                     | 27        | 5.43%   |
| Broadcom / LSI                          | 11        | 2.21%   |
| SanDisk                                 | 9         | 1.81%   |
| Phison Electronics                      | 8         | 1.61%   |
| Marvell Technology Group                | 8         | 1.61%   |
| ASMedia Technology                      | 8         | 1.61%   |
| Nvidia                                  | 7         | 1.41%   |
| SK hynix                                | 6         | 1.21%   |
| Micron/Crucial Technology               | 6         | 1.21%   |
| Hewlett-Packard                         | 5         | 1.01%   |
| Toshiba                                 | 4         | 0.8%    |
| Silicon Motion                          | 4         | 0.8%    |
| Transcend                               | 3         | 0.6%    |
| Adaptec                                 | 2         | 0.4%    |
| VIA Technologies                        | 1         | 0.2%    |
| Solid State Storage Technology          | 1         | 0.2%    |
| Silicon Integrated Systems [SiS]        | 1         | 0.2%    |
| Silicon Image                           | 1         | 0.2%    |
| Shenzhen Unionmemory Information System | 1         | 0.2%    |
| Shenzhen Longsys Electronics            | 1         | 0.2%    |
| OCZ Technology Group                    | 1         | 0.2%    |
| MAXIO Technology (Hangzhou)             | 1         | 0.2%    |
| Kingston Technology Company             | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 50        | 9.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 28        | 5.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 24        | 4.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 23        | 4.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 3.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 2.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 1.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 9         | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 1.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 1.28%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 7         | 1.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7         | 1.28%   |
| Unknown                                                                                 | 7         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 5         | 0.91%   |
| Phison E12 NVMe Controller                                                              | 5         | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5         | 0.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.91%   |
| AMD FCH IDE Controller                                                                  | 5         | 0.91%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.73%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.55%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 349       | 71.22%  |
| NVMe | 68        | 13.88%  |
| IDE  | 41        | 8.37%   |
| RAID | 23        | 4.69%   |
| SCSI | 5         | 1.02%   |
| SAS  | 4         | 0.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 332       | 79.05%  |
| AMD      | 78        | 18.57%  |
| ARM      | 6         | 1.43%   |
| Unknown  | 2         | 0.48%   |
| Research | 1         | 0.24%   |
| 11th     | 1         | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 10        | 2.35%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 10        | 2.35%   |
| AMD GX-412TC SOC                         | 8         | 1.88%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 6         | 1.41%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 6         | 1.41%   |
| Intel Celeron N5105 @ 2.00GHz            | 5         | 1.18%   |
| ARM Cortex-A72 r0p3                      | 5         | 1.18%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 4         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 4         | 0.94%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 4         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 4         | 0.94%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 4         | 0.94%   |
| Intel Core 2 Duo                         | 4         | 0.94%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 4         | 0.94%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 4         | 0.94%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 4         | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor        | 4         | 0.94%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 4         | 0.94%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 3         | 0.71%   |
| Intel CPU Version                        | 3         | 0.71%   |
| Intel Core i7-4770S CPU @ 3.10GHz        | 3         | 0.71%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 0.71%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 3         | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3         | 0.71%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 0.71%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 3         | 0.71%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 3         | 0.71%   |
| Intel Core i3-2100 CPU @ 3.10GH          | 3         | 0.71%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 3         | 0.71%   |
| Intel Celeron CPU N2940 @ 1.83GHz        | 3         | 0.71%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 3         | 0.71%   |
| AMD Ryzen Embedded V1500B                | 3         | 0.71%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 3         | 0.71%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 3         | 0.71%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 3         | 0.71%   |
| AMD GX-416RA SOC                         | 3         | 0.71%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 2         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 18.2%   |
| Intel Celeron           | 68        | 16.08%  |
| Intel Core i7           | 46        | 10.87%  |
| Intel Xeon              | 39        | 9.22%   |
| Intel Core i3           | 34        | 8.04%   |
| Other                   | 20        | 4.73%   |
| AMD GX                  | 18        | 4.26%   |
| Intel Atom              | 16        | 3.78%   |
| Intel Core 2 Duo        | 14        | 3.31%   |
| AMD Ryzen 5             | 14        | 3.31%   |
| Intel Pentium Silver    | 12        | 2.84%   |
| Intel Pentium           | 7         | 1.65%   |
| AMD Ryzen 7             | 7         | 1.65%   |
| ARM Cortex              | 6         | 1.42%   |
| AMD G                   | 4         | 0.95%   |
| AMD A6                  | 4         | 0.95%   |
| Intel Core i9           | 3         | 0.71%   |
| AMD Ryzen Embedded      | 3         | 0.71%   |
| AMD Ryzen 3             | 3         | 0.71%   |
| AMD FX                  | 3         | 0.71%   |
| Intel Xeon Silver       | 2         | 0.47%   |
| Intel Core 2 Quad       | 2         | 0.47%   |
| AMD Ryzen 9             | 2         | 0.47%   |
| AMD EPYC                | 2         | 0.47%   |
| AMD Athlon              | 2         | 0.47%   |
| AMD A4                  | 2         | 0.47%   |
| Intel Pentium Dual-Core | 1         | 0.24%   |
| Intel Core 2            | 1         | 0.24%   |
| Intel 686-class         | 1         | 0.24%   |
| AMD Ryzen Threadripper  | 1         | 0.24%   |
| AMD Ryzen 7 PRO         | 1         | 0.24%   |
| AMD Ryzen 3 PRO         | 1         | 0.24%   |
| AMD Phenom II X6        | 1         | 0.24%   |
| AMD Phenom              | 1         | 0.24%   |
| AMD Opteron             | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |
| AMD Athlon II X2        | 1         | 0.24%   |
| AMD Athlon 64 X2        | 1         | 0.24%   |
| AMD A8                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 193       | 45.41%  |
| 2       | 139       | 32.71%  |
| Unknown | 23        | 5.41%   |
| 8       | 18        | 4.24%   |
| 6       | 15        | 3.53%   |
| 12      | 14        | 3.29%   |
| 16      | 11        | 2.59%   |
| 24      | 4         | 0.94%   |
| 10      | 3         | 0.71%   |
| 1       | 3         | 0.71%   |
| 128     | 1         | 0.24%   |
| 64      | 1         | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 395       | 94.05%  |
| 2       | 13        | 3.1%    |
| Unknown | 12        | 2.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 231       | 54.61%  |
| 2       | 169       | 39.95%  |
| Unknown | 23        | 5.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 52        | 12.35%  |
| Silvermont    | 40        | 9.5%    |
| KabyLake      | 40        | 9.5%    |
| Unknown       | 30        | 7.13%   |
| IvyBridge     | 29        | 6.89%   |
| SandyBridge   | 27        | 6.41%   |
| Goldmont plus | 24        | 5.7%    |
| Skylake       | 20        | 4.75%   |
| Penryn        | 19        | 4.51%   |
| Zen 2         | 14        | 3.33%   |
| Broadwell     | 14        | 3.33%   |
| Westmere      | 11        | 2.61%   |
| Jaguar        | 11        | 2.61%   |
| Nehalem       | 10        | 2.38%   |
| Goldmont      | 10        | 2.38%   |
| Puma          | 9         | 2.14%   |
| Zen           | 8         | 1.9%    |
| Zen 3         | 7         | 1.66%   |
| Bonnell       | 7         | 1.66%   |
| Piledriver    | 5         | 1.19%   |
| Bobcat        | 5         | 1.19%   |
| Zen+          | 4         | 0.95%   |
| TigerLake     | 4         | 0.95%   |
| Steamroller   | 4         | 0.95%   |
| Core          | 4         | 0.95%   |
| K10           | 3         | 0.71%   |
| Excavator     | 3         | 0.71%   |
| IceLake       | 2         | 0.48%   |
| CometLake     | 2         | 0.48%   |
| K8 Hammer     | 1         | 0.24%   |
| K10 Llano     | 1         | 0.24%   |
| Bulldozer     | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 265       | 64.63%  |
| AMD                              | 62        | 15.12%  |
| Nvidia                           | 50        | 12.2%   |
| Matrox Electronics Systems       | 21        | 5.12%   |
| ASPEED Technology                | 11        | 2.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 5.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 5.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 4.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 3.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 3.09%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 11        | 2.61%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 11        | 2.61%   |
| Intel JasperLake [UHD Graphics]                                                          | 9         | 2.14%   |
| Intel HD Graphics 500                                                                    | 9         | 2.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.9%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 8         | 1.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8         | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.66%   |
| Intel HD Graphics 620                                                                    | 7         | 1.66%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 1.66%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.43%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 1.43%   |
| Matrox Electronics Systems MGA G200EH                                                    | 5         | 1.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.19%   |
| Intel HD Graphics 610                                                                    | 5         | 1.19%   |
| Intel HD Graphics 530                                                                    | 5         | 1.19%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.95%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 4         | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.95%   |
| Intel HD Graphics 6000                                                                   | 4         | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.95%   |
| AMD Renoir                                                                               | 4         | 0.95%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.95%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.71%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.71%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 3         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 239       | 56.64%  |
| 1 x AMD        | 57        | 13.51%  |
| 1 x Nvidia     | 39        | 9.24%   |
| Other          | 27        | 6.4%    |
| 1 x Matrox     | 21        | 4.98%   |
| 2 x Intel      | 12        | 2.84%   |
| 1 x ASPEED     | 10        | 2.37%   |
| Intel + Nvidia | 9         | 2.13%   |
| Intel + AMD    | 4         | 0.95%   |
| 2 x Nvidia     | 2         | 0.47%   |
| 1 x SiS        | 1         | 0.24%   |
| Intel + ASPEED | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 366       | 86.73%  |
| Unknown     | 35        | 8.29%   |
| Proprietary | 21        | 4.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 387       | 91.27%  |
| 0.51-1.0   | 9         | 2.12%   |
| 1.01-2.0   | 8         | 1.89%   |
| 3.01-4.0   | 6         | 1.42%   |
| 7.01-8.0   | 5         | 1.18%   |
| 0.01-0.5   | 5         | 1.18%   |
| 5.01-6.0   | 2         | 0.47%   |
| 8.01-16.0  | 2         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 13.04%  |
| Samsung Electronics     | 13        | 11.3%   |
| LG Display              | 11        | 9.57%   |
| Dell                    | 9         | 7.83%   |
| Lenovo                  | 6         | 5.22%   |
| Hewlett-Packard         | 6         | 5.22%   |
| Chimei Innolux          | 6         | 5.22%   |
| BenQ                    | 6         | 5.22%   |
| AOC                     | 5         | 4.35%   |
| Philips                 | 4         | 3.48%   |
| BOE                     | 4         | 3.48%   |
| Sharp                   | 3         | 2.61%   |
| Iiyama                  | 3         | 2.61%   |
| Acer                    | 3         | 2.61%   |
| Pixio                   | 2         | 1.74%   |
| LG Philips              | 2         | 1.74%   |
| HannStar                | 2         | 1.74%   |
| Apple                   | 2         | 1.74%   |
| Vestel Elektronik       | 1         | 0.87%   |
| unknown                 | 1         | 0.87%   |
| Sony                    | 1         | 0.87%   |
| SDC                     | 1         | 0.87%   |
| RS                      | 1         | 0.87%   |
| PANDA                   | 1         | 0.87%   |
| OEM                     | 1         | 0.87%   |
| InnoLux Display         | 1         | 0.87%   |
| Goldstar                | 1         | 0.87%   |
| CPT                     | 1         | 0.87%   |
| Chi Mei Optoelectronics | 1         | 0.87%   |
| AVX                     | 1         | 0.87%   |
| Unknown                 | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 271P4 PHL08C3 1920x1080 600x340mm 27.2-inch                   | 3         | 2.48%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 2.48%   |
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                     | 3         | 2.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 2.48%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 1.65%   |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch           | 2         | 1.65%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 1.65%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.83%   |
| unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.83%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 0.83%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.83%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 0.83%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch     | 1         | 0.83%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch  | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch  | 1         | 0.83%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1         | 0.83%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.83%   |
| Samsung Electronics S24C550 SAM0A4B 1920x1080 520x290mm 23.4-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 0.83%   |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                       | 1         | 0.83%   |
| Pixio PX7 Prime HYC2700 2560x1440 600x340mm 27.2-inch                 | 1         | 0.83%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                     | 1         | 0.83%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 0.83%   |
| Philips LCD Monitor 271P4                                             | 1         | 0.83%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 0.83%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                       | 1         | 0.83%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.83%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD052D 1920x1080 290x170mm 13.2-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 40%     |
| 1366x768 (WXGA)    | 17        | 14.78%  |
| 1600x900 (HD+)     | 7         | 6.09%   |
| 1280x800 (WXGA)    | 7         | 6.09%   |
| 1920x1200 (WUXGA)  | 5         | 4.35%   |
| 1680x1050 (WSXGA+) | 4         | 3.48%   |
| 3840x2160 (4K)     | 3         | 2.61%   |
| 3200x1800 (QHD+)   | 3         | 2.61%   |
| 2560x1440 (QHD)    | 3         | 2.61%   |
| 1440x900 (WXGA+)   | 3         | 2.61%   |
| 1280x1024 (SXGA)   | 3         | 2.61%   |
| 1024x600           | 3         | 2.61%   |
| Unknown            | 3         | 2.61%   |
| 1920x540           | 2         | 1.74%   |
| 5760x1200          | 1         | 0.87%   |
| 3840x1080          | 1         | 0.87%   |
| 3520x1080          | 1         | 0.87%   |
| 3440x1440          | 1         | 0.87%   |
| 3200x1080          | 1         | 0.87%   |
| 2880x1800          | 1         | 0.87%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 19.13%  |
| 13      | 19        | 16.52%  |
| 27      | 10        | 8.7%    |
| Unknown | 9         | 7.83%   |
| 24      | 8         | 6.96%   |
| 23      | 8         | 6.96%   |
| 19      | 7         | 6.09%   |
| 12      | 6         | 5.22%   |
| 22      | 4         | 3.48%   |
| 21      | 4         | 3.48%   |
| 17      | 4         | 3.48%   |
| 25      | 2         | 1.74%   |
| 11      | 2         | 1.74%   |
| 10      | 2         | 1.74%   |
| 49      | 1         | 0.87%   |
| 42      | 1         | 0.87%   |
| 39      | 1         | 0.87%   |
| 34      | 1         | 0.87%   |
| 31      | 1         | 0.87%   |
| 18      | 1         | 0.87%   |
| 14      | 1         | 0.87%   |
| 9       | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 27.68%  |
| 501-600     | 26        | 23.21%  |
| 201-300     | 22        | 19.64%  |
| 401-500     | 10        | 8.93%   |
| Unknown     | 9         | 8.04%   |
| 351-400     | 8         | 7.14%   |
| 601-700     | 2         | 1.79%   |
| 801-900     | 1         | 0.89%   |
| 701-800     | 1         | 0.89%   |
| 1001-1500   | 1         | 0.89%   |
| 901-1000    | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 72        | 66.67%  |
| 16/10   | 18        | 16.67%  |
| Unknown | 8         | 7.41%   |
| 5/4     | 4         | 3.7%    |
| 3/2     | 3         | 2.78%   |
| 32/9    | 2         | 1.85%   |
| 21/9    | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 20        | 17.86%  |
| 81-90          | 12        | 10.71%  |
| 91-100         | 12        | 10.71%  |
| 301-350        | 10        | 8.93%   |
| 101-110        | 10        | 8.93%   |
| Unknown        | 9         | 8.04%   |
| 71-80          | 8         | 7.14%   |
| 151-200        | 7         | 6.25%   |
| 61-70          | 6         | 5.36%   |
| 121-130        | 4         | 3.57%   |
| 41-50          | 3         | 2.68%   |
| 251-300        | 3         | 2.68%   |
| 501-1000       | 3         | 2.68%   |
| 51-60          | 2         | 1.79%   |
| 351-500        | 2         | 1.79%   |
| 141-150        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 41        | 36.61%  |
| 101-120       | 27        | 24.11%  |
| 121-160       | 23        | 20.54%  |
| 161-240       | 9         | 8.04%   |
| Unknown       | 9         | 8.04%   |
| More than 240 | 3         | 2.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 301       | 70.82%  |
| 1     | 113       | 26.59%  |
| 2     | 10        | 2.35%   |
| 3     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 300       | 52.17%  |
| Realtek Semiconductor             | 140       | 24.35%  |
| Broadcom                          | 46        | 8%      |
| Qualcomm Atheros                  | 31        | 5.39%   |
| Marvell Technology Group          | 7         | 1.22%   |
| Ralink Technology                 | 6         | 1.04%   |
| Nvidia                            | 6         | 1.04%   |
| IMC Networks                      | 5         | 0.87%   |
| Hewlett-Packard                   | 3         | 0.52%   |
| Ericsson Business Mobile Networks | 3         | 0.52%   |
| D-Link System                     | 3         | 0.52%   |
| AMD                               | 3         | 0.52%   |
| Sierra Wireless                   | 2         | 0.35%   |
| Ralink                            | 2         | 0.35%   |
| Mellanox Technologies             | 2         | 0.35%   |
| Edimax Technology                 | 2         | 0.35%   |
| Dell                              | 2         | 0.35%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.17%   |
| Xiaomi                            | 1         | 0.17%   |
| U-Blox                            | 1         | 0.17%   |
| TP-Link                           | 1         | 0.17%   |
| Solarflare Communications         | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| QLogic                            | 1         | 0.17%   |
| Napatech A/S                      | 1         | 0.17%   |
| Bluegiga Technologies             | 1         | 0.17%   |
| Belkin Components                 | 1         | 0.17%   |
| ASUSTek Computer                  | 1         | 0.17%   |
| American Megatrends               | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 116       | 16.36%  |
| Intel I211 Gigabit Network Connection                                         | 56        | 7.9%    |
| Intel I210 Gigabit Network Connection                                         | 26        | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 24        | 3.39%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 18        | 2.54%   |
| Intel I350 Gigabit Network Connection                                         | 16        | 2.26%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 2.12%   |
| Intel Wireless 7260                                                           | 13        | 1.83%   |
| Intel 82580 Gigabit Network Connection                                        | 13        | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 12        | 1.69%   |
| Intel Ethernet Controller I225-V                                              | 11        | 1.55%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                             | 10        | 1.41%   |
| Intel 82576 Gigabit Network Connection                                        | 10        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                           | 9         | 1.27%   |
| Intel Ethernet Controller I226-V                                              | 9         | 1.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.27%   |
| Intel Wireless 8260                                                           | 8         | 1.13%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 1.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 0.99%   |
| Intel 82583V Gigabit Network Connection                                       | 7         | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 6         | 0.85%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 0.85%   |
| Intel Wireless 3165                                                           | 6         | 0.85%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 0.85%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 0.85%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 0.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 5         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.71%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 5         | 0.71%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 0.56%   |
| Intel Wireless 3160                                                           | 4         | 0.56%   |
| Intel Wi-Fi 6 AX201                                                           | 4         | 0.56%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 56.18%  |
| Qualcomm Atheros      | 28        | 15.73%  |
| Realtek Semiconductor | 17        | 9.55%   |
| Broadcom              | 11        | 6.18%   |
| Ralink Technology     | 6         | 3.37%   |
| IMC Networks          | 5         | 2.81%   |
| D-Link System         | 3         | 1.69%   |
| Ralink                | 2         | 1.12%   |
| Edimax Technology     | 2         | 1.12%   |
| TP-Link               | 1         | 0.56%   |
| Sierra Wireless       | 1         | 0.56%   |
| Belkin Components     | 1         | 0.56%   |
| ASUSTek Computer      | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                        | 13        | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 12        | 6.67%   |
| Intel Wi-Fi 6 AX200                                                        | 9         | 5%      |
| Intel Wireless 8260                                                        | 8         | 4.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 6         | 3.33%   |
| Intel Wireless 8265 / 8275                                                 | 6         | 3.33%   |
| Intel Wireless 3165                                                        | 6         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 5         | 2.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 5         | 2.78%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                       | 5         | 2.78%   |
| Intel Wireless 3160                                                        | 4         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 2.22%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 2.22%   |
| Intel Centrino Advanced-N 6200                                             | 4         | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 4         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                             | 3         | 1.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 1.67%   |
| Intel Wireless 7265                                                        | 3         | 1.67%   |
| Intel WiFi Link 5100                                                       | 3         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 3         | 1.67%   |
| Intel Centrino Advanced-N 6235                                             | 3         | 1.67%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2         | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.11%   |
| Intel Wireless-AC 9260                                                     | 2         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 2         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 1.11%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 2         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 2         | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 2         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 2         | 1.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 0.56%   |
| Sierra Wireless EM7345 4G LTE                                              | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 261       | 57.36%  |
| Realtek Semiconductor     | 130       | 28.57%  |
| Broadcom                  | 39        | 8.57%   |
| Marvell Technology Group  | 7         | 1.54%   |
| Nvidia                    | 6         | 1.32%   |
| Qualcomm Atheros          | 4         | 0.88%   |
| AMD                       | 3         | 0.66%   |
| Xiaomi                    | 1         | 0.22%   |
| Solarflare Communications | 1         | 0.22%   |
| Qualcomm                  | 1         | 0.22%   |
| QLogic                    | 1         | 0.22%   |
| American Megatrends       | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 116       | 22.7%   |
| Intel I211 Gigabit Network Connection                                         | 56        | 10.96%  |
| Intel I210 Gigabit Network Connection                                         | 26        | 5.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 24        | 4.7%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 18        | 3.52%   |
| Intel I350 Gigabit Network Connection                                         | 16        | 3.13%   |
| Intel 82574L Gigabit Network Connection                                       | 15        | 2.94%   |
| Intel 82580 Gigabit Network Connection                                        | 13        | 2.54%   |
| Intel Ethernet Controller I225-V                                              | 11        | 2.15%   |
| Intel Ethernet Connection I217-LM                                             | 11        | 2.15%   |
| Realtek RTL8125 2.5GbE Controller                                             | 10        | 1.96%   |
| Intel 82576 Gigabit Network Connection                                        | 10        | 1.96%   |
| Intel Ethernet Controller I226-V                                              | 9         | 1.76%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9         | 1.76%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 8         | 1.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 7         | 1.37%   |
| Intel 82583V Gigabit Network Connection                                       | 7         | 1.37%   |
| Intel Ethernet Connection I219-LM                                             | 6         | 1.17%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 6         | 1.17%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 6         | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.98%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5         | 0.98%   |
| Intel 82579V Gigabit Network Connection                                       | 5         | 0.98%   |
| Nvidia MCP79 Ethernet                                                         | 4         | 0.78%   |
| Intel Ethernet Connection I218-LM                                             | 4         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                         | 4         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 3         | 0.59%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3         | 0.59%   |
| Intel Ethernet Controller X550                                                | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                                      | 3         | 0.59%   |
| Intel 82575EB Gigabit Network Connection                                      | 3         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 3         | 0.59%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                             | 3         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3         | 0.59%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.59%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 3         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 392       | 67.82%  |
| WiFi     | 168       | 29.07%  |
| Unknown  | 11        | 1.9%    |
| Modem    | 7         | 1.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 365       | 80.75%  |
| WiFi     | 84        | 18.58%  |
| Modem    | 3         | 0.66%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 143       | 33.57%  |
| 1     | 66        | 15.49%  |
| 4     | 64        | 15.02%  |
| 3     | 50        | 11.74%  |
| 5     | 44        | 10.33%  |
| 6     | 31        | 7.28%   |
| 0     | 9         | 2.11%   |
| 7     | 7         | 1.64%   |
| 8     | 4         | 0.94%   |
| 10    | 3         | 0.7%    |
| 9     | 2         | 0.47%   |
| 15    | 1         | 0.23%   |
| 14    | 1         | 0.23%   |
| 12    | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 385       | 88.71%  |
| Yes  | 49        | 11.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 55.05%  |
| Broadcom                        | 9         | 8.26%   |
| Apple                           | 9         | 8.26%   |
| Realtek Semiconductor           | 6         | 5.5%    |
| Cambridge Silicon Radio         | 6         | 5.5%    |
| Dell                            | 4         | 3.67%   |
| Qualcomm Atheros Communications | 3         | 2.75%   |
| IMC Networks                    | 3         | 2.75%   |
| Foxconn / Hon Hai               | 3         | 2.75%   |
| ASUSTek Computer                | 3         | 2.75%   |
| Skylight Digital                | 1         | 0.92%   |
| Lite-On Technology              | 1         | 0.92%   |
| Alps Electric                   | 1         | 0.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 26        | 23.85%  |
| Intel AX200 Bluetooth                                                               | 9         | 8.26%   |
| Intel AX201 Bluetooth                                                               | 8         | 7.34%   |
| Apple Bluetooth Host Controller                                                     | 7         | 6.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 5.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 5.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.67%   |
| Realtek Bluetooth Adapter                                                           | 3         | 2.75%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 2.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.83%   |
| Intel Wireless Bluetooth                                                            | 2         | 1.83%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 2         | 1.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.83%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.83%   |
| Skylight Digital Realtek Bluetooth Adapter                                          | 1         | 0.92%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.92%   |
| Realtek Bluetooth 5.1 Adapter                                                       | 1         | 0.92%   |
| Realtek Bluetooth 4.0 Adapter                                                       | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                                              | 1         | 0.92%   |
| Lite-On Bluetooth USB Module                                                        | 1         | 0.92%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.92%   |
| IMC Networks Realtek Bluetooth Adapter                                              | 1         | 0.92%   |
| IMC Networks Realtek Bluetooth 4.0 Adapter                                          | 1         | 0.92%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                                         | 1         | 0.92%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.92%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 0.92%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.92%   |
| Broadcom Bluetooth                                                                  | 1         | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.92%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.92%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter                             | 1         | 0.92%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.92%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.92%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 261       | 65.74%  |
| AMD                                  | 74        | 18.64%  |
| Nvidia                               | 39        | 9.82%   |
| C-Media Electronics                  | 6         | 1.51%   |
| SteelSeries ApS                      | 3         | 0.76%   |
| Texas Instruments                    | 2         | 0.5%    |
| Creative Labs                        | 2         | 0.5%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.25%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.25%   |
| Nam Tai E&E Products                 | 1         | 0.25%   |
| Logitech                             | 1         | 0.25%   |
| JMTek                                | 1         | 0.25%   |
| Griffin Technology                   | 1         | 0.25%   |
| GN Netcom                            | 1         | 0.25%   |
| Elgato Systems                       | 1         | 0.25%   |
| BEHRINGER International              | 1         | 0.25%   |
| Unknown                              | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 5.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 5.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 4.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 4.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 3.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 3.53%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 3.32%   |
| AMD FCH Azalia Controller                                                                         | 15        | 3.11%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 2.9%    |
| Intel 8 Series HD Audio Controller                                                                | 14        | 2.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 13        | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 2.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 2.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.87%   |
| Intel Jasper Lake HD Audio                                                                        | 9         | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.24%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.04%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.83%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.83%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4         | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.83%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 72        | 16.9%   |
| SK hynix            | 71        | 16.67%  |
| Unknown             | 43        | 10.09%  |
| Crucial             | 43        | 10.09%  |
| Kingston            | 41        | 9.62%   |
| Micron Technology   | 40        | 9.39%   |
| Corsair             | 34        | 7.98%   |
| Unknown (ABCD)      | 12        | 2.82%   |
| Transcend           | 9         | 2.11%   |
| Unknown             | 9         | 2.11%   |
| A-DATA Technology   | 8         | 1.88%   |
| Team                | 5         | 1.17%   |
| Ramaxel Technology  | 5         | 1.17%   |
| Elpida              | 5         | 1.17%   |
| Nanya Technology    | 4         | 0.94%   |
| TIMETEC             | 3         | 0.7%    |
| G.Skill             | 3         | 0.7%    |
| Toshiba             | 2         | 0.47%   |
| Hewlett-Packard     | 2         | 0.47%   |
| Essencore Limited   | 2         | 0.47%   |
| Unknown (AB)        | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Smart Modular       | 1         | 0.23%   |
| SK_Hynix            | 1         | 0.23%   |
| Kimtigo             | 1         | 0.23%   |
| Heoriady            | 1         | 0.23%   |
| GSkill              | 1         | 0.23%   |
| CSX                 | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| Apacer              | 1         | 0.23%   |
| A-DA                | 1         | 0.23%   |
| A Force             | 1         | 0.23%   |
| 48spaces            | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 9         | 1.96%   |
| Unknown                                                          | 9         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.31%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 1.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.09%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 5         | 1.09%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 4         | 0.87%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.87%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 3         | 0.65%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 3         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 3         | 0.65%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3         | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 0.65%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.65%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 0.65%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.65%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s              | 3         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                       | 2         | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.44%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                 | 2         | 0.44%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s                 | 2         | 0.44%   |
| Toshiba RAM KCDT82-MIE 4GB SODIMM DDR4 2400MT/s                  | 2         | 0.44%   |
| Timetec RAM UD3-1600 8GB DIMM DDR3 1600MT/s                      | 2         | 0.44%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.44%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.44%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 209       | 54.57%  |
| DDR4    | 127       | 33.16%  |
| DDR2    | 17        | 4.44%   |
| LPDDR4  | 15        | 3.92%   |
| SDRAM   | 4         | 1.04%   |
| LPDDR3  | 4         | 1.04%   |
| Unknown | 4         | 1.04%   |
| DDR     | 2         | 0.52%   |
| DDR5    | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 193       | 50.79%  |
| SODIMM       | 175       | 46.05%  |
| Row Of Chips | 6         | 1.58%   |
| Chip         | 3         | 0.79%   |
| Unknown      | 2         | 0.53%   |
| FB-DIMM      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 151       | 37.66%  |
| 8192  | 150       | 37.41%  |
| 2048  | 48        | 11.97%  |
| 16384 | 33        | 8.23%   |
| 32768 | 13        | 3.24%   |
| 1024  | 5         | 1.25%   |
| 65536 | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 137       | 33.74%  |
| 1333    | 50        | 12.32%  |
| 2400    | 42        | 10.34%  |
| 3200    | 35        | 8.62%   |
| 2667    | 30        | 7.39%   |
| 2133    | 24        | 5.91%   |
| 800     | 14        | 3.45%   |
| 667     | 13        | 3.2%    |
| 1867    | 11        | 2.71%   |
| 1334    | 9         | 2.22%   |
| 2666    | 7         | 1.72%   |
| 1067    | 6         | 1.48%   |
| 1066    | 5         | 1.23%   |
| 3600    | 4         | 0.99%   |
| 533     | 3         | 0.74%   |
| Unknown | 3         | 0.74%   |
| 2933    | 2         | 0.49%   |
| 1866    | 2         | 0.49%   |
| 65535   | 1         | 0.25%   |
| 4800    | 1         | 0.25%   |
| 4267    | 1         | 0.25%   |
| 3534    | 1         | 0.25%   |
| 3000    | 1         | 0.25%   |
| 2600    | 1         | 0.25%   |
| 933     | 1         | 0.25%   |
| 333     | 1         | 0.25%   |
| 133     | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP LaserJet 1200 | 1         | 50%     |
| HP DeskJet 5850c | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 2         | 66.67%  |
| Canon CanoScan LiDE 220 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 23.08%  |
| Logitech                               | 8         | 10.26%  |
| Realtek Semiconductor                  | 7         | 8.97%   |
| Bison Electronics                      | 6         | 7.69%   |
| Z-Star Microelectronics                | 4         | 5.13%   |
| Microdia                               | 4         | 5.13%   |
| IMC Networks                           | 4         | 5.13%   |
| Suyin                                  | 3         | 3.85%   |
| Silicon Motion                         | 3         | 3.85%   |
| Lite-On Technology                     | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Syntek                                 | 2         | 2.56%   |
| Sunplus Innovation Technology          | 2         | 2.56%   |
| Luxvisions Innotech Limited            | 2         | 2.56%   |
| Apple                                  | 2         | 2.56%   |
| Trust                                  | 1         | 1.28%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 1.28%   |
| Quanta                                 | 1         | 1.28%   |
| Lenovo                                 | 1         | 1.28%   |
| Creative Technology                    | 1         | 1.28%   |
| ARC International                      | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                   | 4         | 5.06%   |
| Chicony Integrated Camera                      | 4         | 5.06%   |
| Logitech HD Pro Webcam C920                    | 3         | 3.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)       | 3         | 3.8%    |
| Chicony Integrated HP HD Webcam                | 3         | 3.8%    |
| Z-Star Webcam                                  | 2         | 2.53%   |
| Realtek USB 2.0 Webcam                         | 2         | 2.53%   |
| Microdia USB 2.0 Camera                        | 2         | 2.53%   |
| Logitech Webcam C930e                          | 2         | 2.53%   |
| Logitech Labtec Webcam Pro                     | 2         | 2.53%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 2.53%   |
| Chicony Integrated Camera [ThinkPad]           | 2         | 2.53%   |
| Apple FaceTime HD Camera                       | 2         | 2.53%   |
| Z-Star WebCam SC-03FFL11739P                   | 1         | 1.27%   |
| Z-Star Namuga 1.3M Webcam                      | 1         | 1.27%   |
| Trust Canyon CNS-CWC6 Webcam                   | 1         | 1.27%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera  | 1         | 1.27%   |
| Syntek Integrated Camera                       | 1         | 1.27%   |
| Suyin Laptop_Integrated_Webcam_3M              | 1         | 1.27%   |
| Suyin Acer Crystal Eye webcam                  | 1         | 1.27%   |
| Suyin 1.3M HD Webcam                           | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD           | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_1.3M          | 1         | 1.27%   |
| Silicon Motion WebCam SC-13HDL11939N           | 1         | 1.27%   |
| Silicon Motion WebCam SC-10IRQ12340N           | 1         | 1.27%   |
| Silicon Motion 300k Pixel Camera               | 1         | 1.27%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera | 1         | 1.27%   |
| Realtek USB 2.0 PC Camera                      | 1         | 1.27%   |
| Quanta HD Camera                               | 1         | 1.27%   |
| Microdia Webcam Vitade AF                      | 1         | 1.27%   |
| Microdia Integrated Webcam                     | 1         | 1.27%   |
| Luxvisions Innotech Limited Integrated Camera  | 1         | 1.27%   |
| Luxvisions Innotech Limited HP HD Camera       | 1         | 1.27%   |
| Logitech Webcam C310                           | 1         | 1.27%   |
| Logitech B525 HD Webcam                        | 1         | 1.27%   |
| Lite-On Integrated Camera                      | 1         | 1.27%   |
| Lite-On HP Wide Vision HD Camera               | 1         | 1.27%   |
| Lite-On HP HD Camera                           | 1         | 1.27%   |
| Lenovo Integrated Webcam                       | 1         | 1.27%   |
| IMC Networks Integrated Webcam                 | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 27.78%  |
| Upek                       | 3         | 16.67%  |
| Shenzhen Goodix Technology | 3         | 16.67%  |
| Elan Microelectronics      | 3         | 16.67%  |
| Synaptics                  | 2         | 11.11%  |
| Broadcom                   | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 16.67%  |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 16.67%  |
| Elan Fingerprint Sensor                                                      | 3         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 11.11%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 5.56%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 5.56%   |
| Synaptics UWP WBDI                                                           | 1         | 5.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| AuthenTec AES1660                                                            | 1         | 5.56%   |

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
| 1     | 172       | 39.36%  |
| 0     | 154       | 35.24%  |
| 2     | 68        | 15.56%  |
| 3     | 28        | 6.41%   |
| 4     | 11        | 2.52%   |
| 5     | 3         | 0.69%   |
| 8     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 236       | 59.6%   |
| Bluetooth                | 44        | 11.11%  |
| Net/wireless             | 37        | 9.34%   |
| Firewire controller      | 20        | 5.05%   |
| Card reader              | 20        | 5.05%   |
| Fingerprint reader       | 16        | 4.04%   |
| Sound                    | 6         | 1.52%   |
| Network                  | 6         | 1.52%   |
| Net/ethernet             | 4         | 1.01%   |
| Graphics card            | 3         | 0.76%   |
| Storage/raid             | 2         | 0.51%   |
| Storage                  | 2         | 0.51%   |

