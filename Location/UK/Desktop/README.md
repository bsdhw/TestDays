BSD in UK - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for BSD in UK.

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

Total: 467

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 3031h                       | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| PICO PC       | MNHO-113                    | [7653a1705b](https://bsd-hardware.info/?probe=7653a1705b) | Nov 05, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [d95762a0c0](https://bsd-hardware.info/?probe=d95762a0c0) | Nov 04, 2023 |
| Techvision    | TVI7309X B0                 | [dd3612a38f](https://bsd-hardware.info/?probe=dd3612a38f) | Nov 02, 2023 |
| Techvision    | TVI7309X B0                 | [11b5e187fc](https://bsd-hardware.info/?probe=11b5e187fc) | Nov 02, 2023 |
| Unknown       | Unknown                     | [3499447096](https://bsd-hardware.info/?probe=3499447096) | Nov 01, 2023 |
| Gigabyte      | H81M-S2V                    | [07f64c00f4](https://bsd-hardware.info/?probe=07f64c00f4) | Oct 28, 2023 |
| Unknown       | Unknown                     | [2df22c840a](https://bsd-hardware.info/?probe=2df22c840a) | Oct 28, 2023 |
| Unknown       | Unknown                     | [8c9f8e4f16](https://bsd-hardware.info/?probe=8c9f8e4f16) | Oct 21, 2023 |
| Unknown       | Unknown                     | [f15d15cba2](https://bsd-hardware.info/?probe=f15d15cba2) | Oct 21, 2023 |
| Unknown       | Unknown                     | [d63aebc59b](https://bsd-hardware.info/?probe=d63aebc59b) | Oct 19, 2023 |
| Shenzhen M... | F6BFC                       | [3e57b220ce](https://bsd-hardware.info/?probe=3e57b220ce) | Oct 18, 2023 |
| AZW           | EQ                          | [1f76967326](https://bsd-hardware.info/?probe=1f76967326) | Oct 14, 2023 |
| Protectli     | FW4B Ver                    | [e2647b46bf](https://bsd-hardware.info/?probe=e2647b46bf) | Oct 09, 2023 |
| Yanling       | YL-KBR6L Ver:1.01           | [53fab8363c](https://bsd-hardware.info/?probe=53fab8363c) | Oct 09, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [66c5aee47e](https://bsd-hardware.info/?probe=66c5aee47e) | Oct 03, 2023 |
| Dell          | 0FDY5C A00                  | [acc8dea1e2](https://bsd-hardware.info/?probe=acc8dea1e2) | Oct 03, 2023 |
| AZW           | EQ                          | [81d0adbf96](https://bsd-hardware.info/?probe=81d0adbf96) | Oct 03, 2023 |
| ASUSTek       | P10S-C Series               | [cc0a5bb631](https://bsd-hardware.info/?probe=cc0a5bb631) | Sep 30, 2023 |
| ASUSTek       | P10S-C Series               | [4e7d5e6cf9](https://bsd-hardware.info/?probe=4e7d5e6cf9) | Sep 29, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [64dac999bd](https://bsd-hardware.info/?probe=64dac999bd) | Sep 24, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [6c3728aa16](https://bsd-hardware.info/?probe=6c3728aa16) | Sep 24, 2023 |
| HP            | 859B                        | [7b8592b129](https://bsd-hardware.info/?probe=7b8592b129) | Sep 21, 2023 |
| Protectli     | FW4B Ver                    | [015620b56d](https://bsd-hardware.info/?probe=015620b56d) | Sep 11, 2023 |
| Unknown       | Unknown                     | [65240d295c](https://bsd-hardware.info/?probe=65240d295c) | Sep 10, 2023 |
| Gigabyte      | H81M-S2V                    | [f30ab73618](https://bsd-hardware.info/?probe=f30ab73618) | Sep 10, 2023 |
| Unknown       | Unknown                     | [d28c125e99](https://bsd-hardware.info/?probe=d28c125e99) | Sep 10, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [6e458d22a3](https://bsd-hardware.info/?probe=6e458d22a3) | Sep 05, 2023 |
| Gigabyte      | A520I AC                    | [e245a38088](https://bsd-hardware.info/?probe=e245a38088) | Aug 31, 2023 |
| AZW           | EQ                          | [fe5669c376](https://bsd-hardware.info/?probe=fe5669c376) | Aug 29, 2023 |
| Unknown       | Unknown                     | [c5068ec761](https://bsd-hardware.info/?probe=c5068ec761) | Aug 28, 2023 |
| CncTion       | N6000-4L B0                 | [0cab2e3af3](https://bsd-hardware.info/?probe=0cab2e3af3) | Aug 28, 2023 |
| MSI           | AM1I                        | [50183030f8](https://bsd-hardware.info/?probe=50183030f8) | Aug 27, 2023 |
| Cisco         | ASA5515 A0                  | [d4540d9ae5](https://bsd-hardware.info/?probe=d4540d9ae5) | Aug 24, 2023 |
| MSI           | AM1I                        | [0f74a7c547](https://bsd-hardware.info/?probe=0f74a7c547) | Aug 21, 2023 |
| ASRock        | E3C224D2I                   | [93bf9586db](https://bsd-hardware.info/?probe=93bf9586db) | Aug 18, 2023 |
| PICO PC       | MNHO-113                    | [95f3a15448](https://bsd-hardware.info/?probe=95f3a15448) | Aug 17, 2023 |
| Unknown       | QGLK03                      | [bb622dd456](https://bsd-hardware.info/?probe=bb622dd456) | Aug 16, 2023 |
| Supermicro    | M12SWA-TF                   | [2e38f0b91a](https://bsd-hardware.info/?probe=2e38f0b91a) | Aug 16, 2023 |
| Intel         | Q3XXG4-P V1.0               | [d830d61109](https://bsd-hardware.info/?probe=d830d61109) | Aug 15, 2023 |
| Acer          | TDPS05 R3700                | [5e3083a96d](https://bsd-hardware.info/?probe=5e3083a96d) | Aug 14, 2023 |
| Protectli     | FW6 Ver                     | [7e3965fa27](https://bsd-hardware.info/?probe=7e3965fa27) | Aug 12, 2023 |
| Protectli     | VP2410 10                   | [b4869eafb2](https://bsd-hardware.info/?probe=b4869eafb2) | Aug 12, 2023 |
| HPE           | ProLiant MicroServer Gen... | [d06166298c](https://bsd-hardware.info/?probe=d06166298c) | Aug 07, 2023 |
| Acer          | Aspire XC-115               | [7a94fde347](https://bsd-hardware.info/?probe=7a94fde347) | Aug 06, 2023 |
| Unknown       | YL-SKUL6                    | [cdd90dd470](https://bsd-hardware.info/?probe=cdd90dd470) | Aug 04, 2023 |
| Unknown       | Unknown                     | [b9f6337c0d](https://bsd-hardware.info/?probe=b9f6337c0d) | Aug 02, 2023 |
| Unknown       | 1.1                         | [745c09c8e7](https://bsd-hardware.info/?probe=745c09c8e7) | Aug 01, 2023 |
| HP            | 8617                        | [7592f46fef](https://bsd-hardware.info/?probe=7592f46fef) | Jul 30, 2023 |
| Protectli     | FW4B Ver                    | [449a3e6015](https://bsd-hardware.info/?probe=449a3e6015) | Jul 28, 2023 |
| Unknown       | Unknown                     | [f4fb011cfb](https://bsd-hardware.info/?probe=f4fb011cfb) | Jul 11, 2023 |
| Techvision    | TVI7309X B0                 | [d365b4b0df](https://bsd-hardware.info/?probe=d365b4b0df) | Jul 07, 2023 |
| Unknown       | Unknown                     | [a7e3b61154](https://bsd-hardware.info/?probe=a7e3b61154) | Jul 05, 2023 |
| CncTion       | N5105-4L-I226 B0            | [492f3e2096](https://bsd-hardware.info/?probe=492f3e2096) | Jul 05, 2023 |
| Dell          | 07WP95 A01                  | [1705a37ecb](https://bsd-hardware.info/?probe=1705a37ecb) | Jul 05, 2023 |
| CncTion       | N5105-4L-I226 B0            | [d1e58041a9](https://bsd-hardware.info/?probe=d1e58041a9) | Jul 04, 2023 |
| Techvision    | TVI7309X B0                 | [24bc6390a7](https://bsd-hardware.info/?probe=24bc6390a7) | Jul 02, 2023 |
| Techvision    | TVI7309X B0                 | [7e76f16380](https://bsd-hardware.info/?probe=7e76f16380) | Jul 01, 2023 |
| Techvision    | TVI7309X B0                 | [7c71b88b22](https://bsd-hardware.info/?probe=7c71b88b22) | Jun 30, 2023 |
| Techvision    | TVI7309X B0                 | [0dbf4904dc](https://bsd-hardware.info/?probe=0dbf4904dc) | Jun 28, 2023 |
| Unknown       | Unknown                     | [9d98798bc8](https://bsd-hardware.info/?probe=9d98798bc8) | Jun 27, 2023 |
| Cisco         | ASA5515 A0                  | [9d8eedf081](https://bsd-hardware.info/?probe=9d8eedf081) | Jun 26, 2023 |
| Protectli     | FW6 Ver                     | [03eb1a54c8](https://bsd-hardware.info/?probe=03eb1a54c8) | Jun 25, 2023 |
| Gigabyte      | Z77N-WIFI                   | [aca5df3113](https://bsd-hardware.info/?probe=aca5df3113) | Jun 24, 2023 |
| HP            | 8592                        | [154f28878a](https://bsd-hardware.info/?probe=154f28878a) | Jun 21, 2023 |
| Unknown       | Unknown                     | [81268da610](https://bsd-hardware.info/?probe=81268da610) | Jun 17, 2023 |
| Dell          | 0H7TGR A00                  | [da72cc4da4](https://bsd-hardware.info/?probe=da72cc4da4) | Jun 14, 2023 |
| Gigabyte      | Z77N-WIFI                   | [f96302f46c](https://bsd-hardware.info/?probe=f96302f46c) | Jun 13, 2023 |
| AZW           | EQ                          | [f1f980d130](https://bsd-hardware.info/?probe=f1f980d130) | Jun 10, 2023 |
| maiyunda      | www.maiyunda.com            | [7b43dea184](https://bsd-hardware.info/?probe=7b43dea184) | Jun 08, 2023 |
| Gigabyte      | Z77N-WIFI                   | [c1c30d3223](https://bsd-hardware.info/?probe=c1c30d3223) | Jun 02, 2023 |
| Gigabyte      | Z77N-WIFI                   | [45cb709a24](https://bsd-hardware.info/?probe=45cb709a24) | Jun 01, 2023 |
| Dell          | 0GXM1W A01                  | [c9959faf54](https://bsd-hardware.info/?probe=c9959faf54) | May 29, 2023 |
| Axiomtek      | NA362-DAMI-c3768-US         | [243efb73f6](https://bsd-hardware.info/?probe=243efb73f6) | May 27, 2023 |
| Unknown       | 1.0                         | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| Dell          | 0GXM1W A01                  | [364d24b4f4](https://bsd-hardware.info/?probe=364d24b4f4) | May 25, 2023 |
| ASRock        | E3C224D2I                   | [57353597b3](https://bsd-hardware.info/?probe=57353597b3) | May 25, 2023 |
| Dell          | 0GXM1W A01                  | [afa4b1b0df](https://bsd-hardware.info/?probe=afa4b1b0df) | May 25, 2023 |
| ASRock        | IMB-181-L                   | [0347664bbc](https://bsd-hardware.info/?probe=0347664bbc) | May 17, 2023 |
| Dell          | 0WN7Y6 A01                  | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| Supermicro    | X8SIL                       | [a39ebc1c3a](https://bsd-hardware.info/?probe=a39ebc1c3a) | May 10, 2023 |
| ASUSTek       | P11C-M Series               | [8114acc225](https://bsd-hardware.info/?probe=8114acc225) | May 07, 2023 |
| Unknown       | Unknown                     | [6cc74ec4bd](https://bsd-hardware.info/?probe=6cc74ec4bd) | May 04, 2023 |
| ASUSTek       | P11C-M Series               | [2c5d0e597f](https://bsd-hardware.info/?probe=2c5d0e597f) | May 03, 2023 |
| Gigabyte      | A320M-H-CF                  | [3fbe359db7](https://bsd-hardware.info/?probe=3fbe359db7) | May 03, 2023 |
| Lenovo        | SHARKBAY NOK                | [2a9fc1af29](https://bsd-hardware.info/?probe=2a9fc1af29) | Apr 27, 2023 |
| Intel GMLV... | GMLR115 GMLR115             | [56d2fcc6e9](https://bsd-hardware.info/?probe=56d2fcc6e9) | Apr 24, 2023 |
| Dell          | 0WR7PY A03                  | [e461f7862c](https://bsd-hardware.info/?probe=e461f7862c) | Apr 23, 2023 |
| Dell          | 02YYK5 A01                  | [9f7ba08cb2](https://bsd-hardware.info/?probe=9f7ba08cb2) | Apr 23, 2023 |
| Gigabyte      | N3050MD3P                   | [66e9ccbef8](https://bsd-hardware.info/?probe=66e9ccbef8) | Apr 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [7a5fcaf0d0](https://bsd-hardware.info/?probe=7a5fcaf0d0) | Apr 22, 2023 |
| PICO PC       | MNHO-113                    | [ad485d27af](https://bsd-hardware.info/?probe=ad485d27af) | Apr 15, 2023 |
| ASUSTek       | PRIME H510M-E               | [385910dbe5](https://bsd-hardware.info/?probe=385910dbe5) | Apr 11, 2023 |
| Unknown       | Unknown                     | [ceebb96d61](https://bsd-hardware.info/?probe=ceebb96d61) | Apr 11, 2023 |
| Unknown       | Unknown                     | [e163926e69](https://bsd-hardware.info/?probe=e163926e69) | Apr 10, 2023 |
| Unknown       | Unknown                     | [f2fbd3c3ad](https://bsd-hardware.info/?probe=f2fbd3c3ad) | Apr 09, 2023 |
| ASRock        | E3C224D2I                   | [f8f3f3c43c](https://bsd-hardware.info/?probe=f8f3f3c43c) | Apr 07, 2023 |
| Dell          | 0WR7PY A03                  | [42a875684f](https://bsd-hardware.info/?probe=42a875684f) | Apr 07, 2023 |
| Unknown       | Unknown                     | [196f8d9e86](https://bsd-hardware.info/?probe=196f8d9e86) | Apr 06, 2023 |
| Unknown       | Unknown                     | [5a7bd1b139](https://bsd-hardware.info/?probe=5a7bd1b139) | Apr 02, 2023 |
| ASUSTek       | PRIME H510M-E               | [8fe73c707e](https://bsd-hardware.info/?probe=8fe73c707e) | Apr 02, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [1122cabca9](https://bsd-hardware.info/?probe=1122cabca9) | Apr 01, 2023 |
| ASRockRack    | EPYCD8-2T                   | [75f414997a](https://bsd-hardware.info/?probe=75f414997a) | Mar 31, 2023 |
| Lenovo        | SHARKBAY 0B98405 STD        | [29c6f5f74c](https://bsd-hardware.info/?probe=29c6f5f74c) | Mar 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [3c4f4abe16](https://bsd-hardware.info/?probe=3c4f4abe16) | Mar 23, 2023 |
| Intel         | DENLOW_WS                   | [8b3bb4ee24](https://bsd-hardware.info/?probe=8b3bb4ee24) | Mar 19, 2023 |
| ASUSTek       | Z97I-PLUS                   | [cdbc1b0031](https://bsd-hardware.info/?probe=cdbc1b0031) | Mar 19, 2023 |
| CNCTION-IA... | Unknown                     | [914c4aad57](https://bsd-hardware.info/?probe=914c4aad57) | Mar 19, 2023 |
| Dell          | 0D28YY A00                  | [15e8aedcb6](https://bsd-hardware.info/?probe=15e8aedcb6) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| Intel         | SHARKBAY                    | [6c2382fa44](https://bsd-hardware.info/?probe=6c2382fa44) | Mar 16, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [652100bcac](https://bsd-hardware.info/?probe=652100bcac) | Mar 16, 2023 |
| Unknown       | Unknown                     | [82759eff54](https://bsd-hardware.info/?probe=82759eff54) | Mar 11, 2023 |
| Acer          | TDPS05 R3700                | [6ee4404ee0](https://bsd-hardware.info/?probe=6ee4404ee0) | Mar 09, 2023 |
| Techvision    | TVI7309X B0                 | [fb5b37bff5](https://bsd-hardware.info/?probe=fb5b37bff5) | Mar 02, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [e9e179e9ac](https://bsd-hardware.info/?probe=e9e179e9ac) | Mar 02, 2023 |
| MSI           | B450M PRO-VDH MAX           | [85aecf8c3f](https://bsd-hardware.info/?probe=85aecf8c3f) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [be81f2675f](https://bsd-hardware.info/?probe=be81f2675f) | Feb 25, 2023 |
| PC Engines    | apu4                        | [410a7ff78e](https://bsd-hardware.info/?probe=410a7ff78e) | Feb 23, 2023 |
| Intel         | CW-J6-5L 2C                 | [442643937e](https://bsd-hardware.info/?probe=442643937e) | Feb 22, 2023 |
| Intel         | CW-J6-5L 2C                 | [90fc1b74e6](https://bsd-hardware.info/?probe=90fc1b74e6) | Feb 22, 2023 |
| Unknown       | Unknown                     | [8c063582d4](https://bsd-hardware.info/?probe=8c063582d4) | Feb 20, 2023 |
| Unknown       | Unknown                     | [b906471557](https://bsd-hardware.info/?probe=b906471557) | Feb 17, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1d9739f234](https://bsd-hardware.info/?probe=1d9739f234) | Feb 17, 2023 |
| Dell          | 00V62H A01                  | [092bbaa484](https://bsd-hardware.info/?probe=092bbaa484) | Feb 01, 2023 |
| Unknown       | Unknown                     | [ecf5a46a0f](https://bsd-hardware.info/?probe=ecf5a46a0f) | Feb 01, 2023 |
| Dell          | 0F373D A00                  | [cd4202e58b](https://bsd-hardware.info/?probe=cd4202e58b) | Jan 30, 2023 |
| Dell          | 00V62H A01                  | [283d305565](https://bsd-hardware.info/?probe=283d305565) | Jan 29, 2023 |
| Dell          | 00V62H A01                  | [9d09937e2a](https://bsd-hardware.info/?probe=9d09937e2a) | Jan 28, 2023 |
| Dell          | 03KWTV A02                  | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Unknown       | Unknown                     | [0bbf3bdc00](https://bsd-hardware.info/?probe=0bbf3bdc00) | Jan 21, 2023 |
| Lenovo        | SDK0J40705 WIN 342503995... | [0dc2013a9f](https://bsd-hardware.info/?probe=0dc2013a9f) | Jan 21, 2023 |
| Unknown       | PICO PC                     | [9e20d7dbbc](https://bsd-hardware.info/?probe=9e20d7dbbc) | Jan 20, 2023 |
| Protectli     | FW6 Ver                     | [8c1f6c2733](https://bsd-hardware.info/?probe=8c1f6c2733) | Jan 12, 2023 |
| Unknown       | Unknown                     | [6e866a006d](https://bsd-hardware.info/?probe=6e866a006d) | Jan 10, 2023 |
| Unknown       | Unknown                     | [7e87430a40](https://bsd-hardware.info/?probe=7e87430a40) | Jan 07, 2023 |
| Gigabyte      | A320M-H-CF                  | [ce6ccffb1b](https://bsd-hardware.info/?probe=ce6ccffb1b) | Jan 06, 2023 |
| Winston Ma... | PICO PC                     | [d744315833](https://bsd-hardware.info/?probe=d744315833) | Jan 05, 2023 |
| Acer          | Aspire X3400                | [fa59d6aa07](https://bsd-hardware.info/?probe=fa59d6aa07) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Unknown       | Unknown                     | [0f727c761b](https://bsd-hardware.info/?probe=0f727c761b) | Dec 29, 2022 |
| HP            | 8000 X4                     | [e66d228381](https://bsd-hardware.info/?probe=e66d228381) | Dec 29, 2022 |
| Intel         | CARLOW                      | [fa30f060f3](https://bsd-hardware.info/?probe=fa30f060f3) | Dec 28, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [5dafbbced0](https://bsd-hardware.info/?probe=5dafbbced0) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | [888de76acd](https://bsd-hardware.info/?probe=888de76acd) | Dec 28, 2022 |
| Unknown       | Unknown                     | [e70af54c3f](https://bsd-hardware.info/?probe=e70af54c3f) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi 400            | [ee9cac334f](https://bsd-hardware.info/?probe=ee9cac334f) | Dec 21, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [f321130f0e](https://bsd-hardware.info/?probe=f321130f0e) | Dec 18, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [14d483ac06](https://bsd-hardware.info/?probe=14d483ac06) | Dec 18, 2022 |
| ASRock        | E3C224D2I                   | [106e525671](https://bsd-hardware.info/?probe=106e525671) | Dec 18, 2022 |
| AMI           | PEISIA E3845 VER1.0         | [c3ffb2c87d](https://bsd-hardware.info/?probe=c3ffb2c87d) | Dec 17, 2022 |
| Intel         | DN2820FYK H24582-203        | [160d942d28](https://bsd-hardware.info/?probe=160d942d28) | Dec 17, 2022 |
| HP            | 213D A01                    | [6c83f31e71](https://bsd-hardware.info/?probe=6c83f31e71) | Dec 10, 2022 |
| AMI           | PEISIA E3845 VER1.0         | [0ac47aa8a0](https://bsd-hardware.info/?probe=0ac47aa8a0) | Dec 09, 2022 |
| Intel         | CARLOW                      | [1b45524779](https://bsd-hardware.info/?probe=1b45524779) | Dec 05, 2022 |
| Intel         | D54250WYK H13922-303        | [f3b09cfb70](https://bsd-hardware.info/?probe=f3b09cfb70) | Nov 30, 2022 |
| ASRock        | B450M-HDV                   | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Unknown       | Unknown                     | [c5562e1851](https://bsd-hardware.info/?probe=c5562e1851) | Nov 24, 2022 |
| ASRock Ind... | NUC-1240P                   | [75547bc09a](https://bsd-hardware.info/?probe=75547bc09a) | Nov 24, 2022 |
| Datto         | SSD                         | [08d401fa34](https://bsd-hardware.info/?probe=08d401fa34) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| Acer          | TDPS05 R3700                | [4ebc5df17c](https://bsd-hardware.info/?probe=4ebc5df17c) | Nov 15, 2022 |
| Acer          | TDPS05 R3700                | [6e1273fdd6](https://bsd-hardware.info/?probe=6e1273fdd6) | Nov 15, 2022 |
| HP            | 8000 X4                     | [824d5f1ace](https://bsd-hardware.info/?probe=824d5f1ace) | Nov 12, 2022 |
| HP            | 1998                        | [e397526bac](https://bsd-hardware.info/?probe=e397526bac) | Nov 11, 2022 |
| HP            | 1998                        | [6a38c36a3e](https://bsd-hardware.info/?probe=6a38c36a3e) | Nov 11, 2022 |
| ASUSTek       | P5B-Deluxe                  | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [9e3a09a0b3](https://bsd-hardware.info/?probe=9e3a09a0b3) | Nov 10, 2022 |
| Intel         | SHARKBAY                    | [667abc6f38](https://bsd-hardware.info/?probe=667abc6f38) | Nov 09, 2022 |
| Unknown       | Unknown                     | [47e6a4fa8b](https://bsd-hardware.info/?probe=47e6a4fa8b) | Nov 09, 2022 |
| Intel         | SHARKBAY                    | [80a31985d9](https://bsd-hardware.info/?probe=80a31985d9) | Nov 05, 2022 |
| Unknown       | J3160-4L                    | [e05d9b2d17](https://bsd-hardware.info/?probe=e05d9b2d17) | Oct 30, 2022 |
| Unknown       | Unknown                     | [4e01e68bb2](https://bsd-hardware.info/?probe=4e01e68bb2) | Oct 27, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [10ea57e48f](https://bsd-hardware.info/?probe=10ea57e48f) | Oct 23, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [947d061849](https://bsd-hardware.info/?probe=947d061849) | Oct 22, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | [f3db09e0f0](https://bsd-hardware.info/?probe=f3db09e0f0) | Oct 19, 2022 |
| Unknown       | J3160-4L                    | [42c01a3aaf](https://bsd-hardware.info/?probe=42c01a3aaf) | Oct 13, 2022 |
| ASUSTek       | H110M-PLUS                  | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| Unknown       | Unknown                     | [b889791d9f](https://bsd-hardware.info/?probe=b889791d9f) | Oct 06, 2022 |
| ASRock        | J3355M                      | [0240dbc2bb](https://bsd-hardware.info/?probe=0240dbc2bb) | Oct 04, 2022 |
| Shuttle       | FH61V                       | [305f06cd6a](https://bsd-hardware.info/?probe=305f06cd6a) | Oct 01, 2022 |
| Protectli     | FW4B Ver                    | [05651f8664](https://bsd-hardware.info/?probe=05651f8664) | Oct 01, 2022 |
| Dell          | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [3877787983](https://bsd-hardware.info/?probe=3877787983) | Sep 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | [cde2481e46](https://bsd-hardware.info/?probe=cde2481e46) | Sep 26, 2022 |
| HP            | 8592                        | [898ce46c1f](https://bsd-hardware.info/?probe=898ce46c1f) | Sep 25, 2022 |
| Dell          | 07WP95 A01                  | [98e67ff164](https://bsd-hardware.info/?probe=98e67ff164) | Sep 12, 2022 |
| Deciso        | Netboard A10 V2.1           | [6c88b88822](https://bsd-hardware.info/?probe=6c88b88822) | Sep 07, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [3f5ad2f043](https://bsd-hardware.info/?probe=3f5ad2f043) | Sep 05, 2022 |
| MSI           | A320M-A PRO M2              | [d455ed153a](https://bsd-hardware.info/?probe=d455ed153a) | Aug 30, 2022 |
| MSI           | A320M-A PRO M2              | [9d367a6989](https://bsd-hardware.info/?probe=9d367a6989) | Aug 30, 2022 |
| Gigabyte      | H61M-DS2                    | [edb9608bc9](https://bsd-hardware.info/?probe=edb9608bc9) | Aug 24, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [5648905ca2](https://bsd-hardware.info/?probe=5648905ca2) | Aug 19, 2022 |
| HP            | 8592                        | [212adc2c89](https://bsd-hardware.info/?probe=212adc2c89) | Aug 19, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [2b5456b337](https://bsd-hardware.info/?probe=2b5456b337) | Aug 19, 2022 |
| Unknown       | Unknown                     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [78340c12ef](https://bsd-hardware.info/?probe=78340c12ef) | Aug 16, 2022 |
| Protectli     | FW6 Ver                     | [970bec57b8](https://bsd-hardware.info/?probe=970bec57b8) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | [4cf33d57a1](https://bsd-hardware.info/?probe=4cf33d57a1) | Aug 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9783858164](https://bsd-hardware.info/?probe=9783858164) | Aug 14, 2022 |
| HP            | 8592                        | [7c6794942c](https://bsd-hardware.info/?probe=7c6794942c) | Aug 10, 2022 |
| Protectli     | FW6 Ver                     | [8176a8261d](https://bsd-hardware.info/?probe=8176a8261d) | Aug 04, 2022 |
| Unknown       | Unknown                     | [cbda56eddb](https://bsd-hardware.info/?probe=cbda56eddb) | Aug 03, 2022 |
| Protectli     | FW4B Ver                    | [b33527f3ee](https://bsd-hardware.info/?probe=b33527f3ee) | Jul 25, 2022 |
| Dell          | 0T7D40 A00                  | [3d5e83cf1a](https://bsd-hardware.info/?probe=3d5e83cf1a) | Jul 20, 2022 |
| Gigabyte      | J1900N-D3V                  | [17aa06f41f](https://bsd-hardware.info/?probe=17aa06f41f) | Jul 18, 2022 |
| Dell          | 0T7D40 A00                  | [2aef6b2ab4](https://bsd-hardware.info/?probe=2aef6b2ab4) | Jul 18, 2022 |
| Shuttle       | FH170                       | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [0f36e9b5a4](https://bsd-hardware.info/?probe=0f36e9b5a4) | Jul 03, 2022 |
| Inventec      | D CLASS A02                 | [6b5f81700c](https://bsd-hardware.info/?probe=6b5f81700c) | Jul 01, 2022 |
| Intel         | CARLOW                      | [615107464b](https://bsd-hardware.info/?probe=615107464b) | Jul 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f8d0f1f7e0](https://bsd-hardware.info/?probe=f8d0f1f7e0) | Jun 29, 2022 |
| AMD           | Kabini CRB                  | [2ee9e57522](https://bsd-hardware.info/?probe=2ee9e57522) | Jun 26, 2022 |
| Dell          | 0J3C2F A02                  | [58ff991ef8](https://bsd-hardware.info/?probe=58ff991ef8) | Jun 23, 2022 |
| Dell          | 0WMJ54 A01                  | [aa5b395a20](https://bsd-hardware.info/?probe=aa5b395a20) | Jun 19, 2022 |
| Lenovo        | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Gigabyte      | N3150ND3V                   | [56999b6746](https://bsd-hardware.info/?probe=56999b6746) | Jun 13, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [31c49e462c](https://bsd-hardware.info/?probe=31c49e462c) | Jun 01, 2022 |
| Unknown       | Unknown                     | [607561a9a4](https://bsd-hardware.info/?probe=607561a9a4) | May 28, 2022 |
| Unknown       | Unknown                     | [c67bf4af0a](https://bsd-hardware.info/?probe=c67bf4af0a) | May 27, 2022 |
| ASUSTek       | A55BM-E                     | [d5773cd8b3](https://bsd-hardware.info/?probe=d5773cd8b3) | May 16, 2022 |
| Dell          | 0WMJ54 A01                  | [c6faa8080e](https://bsd-hardware.info/?probe=c6faa8080e) | May 10, 2022 |
| HP            | 8592                        | [d922327cdd](https://bsd-hardware.info/?probe=d922327cdd) | May 06, 2022 |
| Intel         | CARLOW                      | [6f185d9b30](https://bsd-hardware.info/?probe=6f185d9b30) | May 06, 2022 |
| Intel         | CARLOW                      | [2240df9d2d](https://bsd-hardware.info/?probe=2240df9d2d) | May 04, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [544b83da9f](https://bsd-hardware.info/?probe=544b83da9f) | Apr 24, 2022 |
| Unknown       | Unknown                     | [3b256304a0](https://bsd-hardware.info/?probe=3b256304a0) | Apr 23, 2022 |
| Shuttle       | FH61V                       | [6f4c78b7db](https://bsd-hardware.info/?probe=6f4c78b7db) | Apr 23, 2022 |
| Gigabyte      | 990FXA-UD3                  | [3813b46bc1](https://bsd-hardware.info/?probe=3813b46bc1) | Apr 22, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [3322ad9dac](https://bsd-hardware.info/?probe=3322ad9dac) | Apr 20, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [aa48329066](https://bsd-hardware.info/?probe=aa48329066) | Apr 20, 2022 |
| ASUSTek       | AM1M-A                      | [754d45f24f](https://bsd-hardware.info/?probe=754d45f24f) | Apr 11, 2022 |
| Jetway        | 1.0                         | [0048067292](https://bsd-hardware.info/?probe=0048067292) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| Gigabyte      | B560M DS3H                  | [a7470aa647](https://bsd-hardware.info/?probe=a7470aa647) | Apr 09, 2022 |
| MSI           | MAG B550M MORTAR            | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [2a7de69b4b](https://bsd-hardware.info/?probe=2a7de69b4b) | Apr 04, 2022 |
| Quanmax       | spo-book TECH QUAD B1       | [1b382db711](https://bsd-hardware.info/?probe=1b382db711) | Apr 04, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6274858d8d](https://bsd-hardware.info/?probe=6274858d8d) | Apr 02, 2022 |
| Foxconn       | 2ADA                        | [9fae64765f](https://bsd-hardware.info/?probe=9fae64765f) | Mar 31, 2022 |
| ASUSTek       | A55BM-E                     | [eaa8d1a7d7](https://bsd-hardware.info/?probe=eaa8d1a7d7) | Mar 30, 2022 |
| Intel         | Q3XXG4-P V1.0               | [730dd09705](https://bsd-hardware.info/?probe=730dd09705) | Mar 28, 2022 |
| Unknown       | Unknown                     | [9b49ac0cf2](https://bsd-hardware.info/?probe=9b49ac0cf2) | Mar 23, 2022 |
| Intel         | DH61CR AAG14064-209         | [3812666505](https://bsd-hardware.info/?probe=3812666505) | Mar 23, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [87289f0c36](https://bsd-hardware.info/?probe=87289f0c36) | Mar 20, 2022 |
| Unknown       | Unknown                     | [8870903766](https://bsd-hardware.info/?probe=8870903766) | Mar 20, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [c9fb46b179](https://bsd-hardware.info/?probe=c9fb46b179) | Mar 19, 2022 |
| HP            | 8592                        | [afffe00b26](https://bsd-hardware.info/?probe=afffe00b26) | Mar 19, 2022 |
| Dell          | 0GXM1W A02                  | [d28bef2c37](https://bsd-hardware.info/?probe=d28bef2c37) | Mar 17, 2022 |
| PC Engines    | APU2                        | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Intel         | DH67BL AAG10189-211         | [10a235fe8f](https://bsd-hardware.info/?probe=10a235fe8f) | Mar 13, 2022 |
| Unknown       | Unknown                     | [5a22c1d4ab](https://bsd-hardware.info/?probe=5a22c1d4ab) | Mar 10, 2022 |
| Dell          | 0WMJ54 A01                  | [77c308e93e](https://bsd-hardware.info/?probe=77c308e93e) | Mar 05, 2022 |
| Dell          | 0WMJ54 A01                  | [1ffc0a0805](https://bsd-hardware.info/?probe=1ffc0a0805) | Mar 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [26565f3d84](https://bsd-hardware.info/?probe=26565f3d84) | Mar 01, 2022 |
| Biostar       | J3160NH                     | [536f856d94](https://bsd-hardware.info/?probe=536f856d94) | Feb 23, 2022 |
| Dell          | 0VD5HY A07                  | [bb86fb3e67](https://bsd-hardware.info/?probe=bb86fb3e67) | Feb 22, 2022 |
| HP            | 8592                        | [fc273bb51a](https://bsd-hardware.info/?probe=fc273bb51a) | Feb 14, 2022 |
| HP            | 8592                        | [5accd7ce0d](https://bsd-hardware.info/?probe=5accd7ce0d) | Feb 13, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [a3843d55ca](https://bsd-hardware.info/?probe=a3843d55ca) | Feb 05, 2022 |
| Intel         | J1900                       | [3b4b841677](https://bsd-hardware.info/?probe=3b4b841677) | Feb 04, 2022 |
| PAIQ          | EC3-BT19D4L A1              | [86cb857d00](https://bsd-hardware.info/?probe=86cb857d00) | Feb 02, 2022 |
| PC Engines    | APU2                        | [0409aa82c2](https://bsd-hardware.info/?probe=0409aa82c2) | Feb 01, 2022 |
| Dell          | 0J3C2F A02                  | [4b4b77d8f3](https://bsd-hardware.info/?probe=4b4b77d8f3) | Feb 01, 2022 |
| Yanling       | YL-KBR6L Ver:1.01           | [a65a16decd](https://bsd-hardware.info/?probe=a65a16decd) | Jan 31, 2022 |
| ASUSTek       | PRIME Z490M-PLUS            | [d08074d468](https://bsd-hardware.info/?probe=d08074d468) | Jan 28, 2022 |
| Gigabyte      | J3455N-D3H                  | [461b538b72](https://bsd-hardware.info/?probe=461b538b72) | Jan 28, 2022 |
| Unknown       | PICO PC                     | [538ca6b389](https://bsd-hardware.info/?probe=538ca6b389) | Jan 27, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [277f5bacdd](https://bsd-hardware.info/?probe=277f5bacdd) | Jan 22, 2022 |
| ASRock        | QC5000M-ITX/PH              | [6ea5e898fa](https://bsd-hardware.info/?probe=6ea5e898fa) | Jan 21, 2022 |
| Intel         | SHARKBAY                    | [6bde480ecd](https://bsd-hardware.info/?probe=6bde480ecd) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Winston Ma... | PICO PC                     | [ac1014aab2](https://bsd-hardware.info/?probe=ac1014aab2) | Jan 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [d914e4c500](https://bsd-hardware.info/?probe=d914e4c500) | Jan 10, 2022 |
| HP            | 8169                        | [85e0cf058c](https://bsd-hardware.info/?probe=85e0cf058c) | Jan 10, 2022 |
| HP            | ProLiant MicroServer Gen... | [9a24935dab](https://bsd-hardware.info/?probe=9a24935dab) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [de6d713222](https://bsd-hardware.info/?probe=de6d713222) | Jan 05, 2022 |
| PC Engines    | APU                         | [efe2fbd850](https://bsd-hardware.info/?probe=efe2fbd850) | Jan 04, 2022 |
| ASRock        | B450 Steel Legend           | [e67007df20](https://bsd-hardware.info/?probe=e67007df20) | Jan 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Protectli     | FW6 Ver                     | [c3c1529f86](https://bsd-hardware.info/?probe=c3c1529f86) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c83118d6d0](https://bsd-hardware.info/?probe=c83118d6d0) | Dec 09, 2021 |
| Inventec      | Z CLASS A02                 | [67556468e3](https://bsd-hardware.info/?probe=67556468e3) | Nov 30, 2021 |
| Protectli     | FW6 Ver                     | [53e6ac863a](https://bsd-hardware.info/?probe=53e6ac863a) | Nov 18, 2021 |
| Dell          | 0J3C2F A02                  | [56cd34ffef](https://bsd-hardware.info/?probe=56cd34ffef) | Nov 17, 2021 |
| Dell          | 0F6X5P A00                  | [8451595212](https://bsd-hardware.info/?probe=8451595212) | Nov 16, 2021 |
| Dell          | 0GXM1W A01                  | [e0c3737f7c](https://bsd-hardware.info/?probe=e0c3737f7c) | Nov 15, 2021 |
| Dell          | 0J3C2F A02                  | [a2bbadf4a5](https://bsd-hardware.info/?probe=a2bbadf4a5) | Nov 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [f0c5f5ef97](https://bsd-hardware.info/?probe=f0c5f5ef97) | Nov 09, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| AZW           | GK55                        | [91db367d18](https://bsd-hardware.info/?probe=91db367d18) | Oct 28, 2021 |
| Unknown       | Unknown                     | [8caf15c2a5](https://bsd-hardware.info/?probe=8caf15c2a5) | Oct 22, 2021 |
| Gigabyte      | H61M-DS2 x.x                | [8e11143a1d](https://bsd-hardware.info/?probe=8e11143a1d) | Oct 14, 2021 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [c8b057c4e4](https://bsd-hardware.info/?probe=c8b057c4e4) | Oct 12, 2021 |
| Gigabyte      | J3455N-D3H                  | [40aba3842c](https://bsd-hardware.info/?probe=40aba3842c) | Oct 03, 2021 |
| ASUSTek       | PRIME A320M-K               | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASRockRack    | X470D4U2-2T                 | [357b9d3ad2](https://bsd-hardware.info/?probe=357b9d3ad2) | Sep 30, 2021 |
| HP            | 0AE8h C                     | [159e371cc7](https://bsd-hardware.info/?probe=159e371cc7) | Sep 30, 2021 |
| Intel         | DH67BL AAG10189-211         | [cc7d3fa6a3](https://bsd-hardware.info/?probe=cc7d3fa6a3) | Sep 26, 2021 |
| Intel         | DH67BL AAG10189-211         | [dc09f7f7cb](https://bsd-hardware.info/?probe=dc09f7f7cb) | Sep 25, 2021 |
| ASRock        | J3455M                      | [411b04cbba](https://bsd-hardware.info/?probe=411b04cbba) | Sep 25, 2021 |
| Unknown       | Unknown                     | [462d25d041](https://bsd-hardware.info/?probe=462d25d041) | Sep 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | [63a24ea67f](https://bsd-hardware.info/?probe=63a24ea67f) | Sep 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [08b4825275](https://bsd-hardware.info/?probe=08b4825275) | Sep 09, 2021 |
| ASRockRack    | X470D4U2-2T                 | [8ce323def8](https://bsd-hardware.info/?probe=8ce323def8) | Sep 09, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [f860e13b6b](https://bsd-hardware.info/?probe=f860e13b6b) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [a3fe3577b0](https://bsd-hardware.info/?probe=a3fe3577b0) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [fdeba8e75d](https://bsd-hardware.info/?probe=fdeba8e75d) | Aug 26, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [2499806edc](https://bsd-hardware.info/?probe=2499806edc) | Aug 26, 2021 |
| ASRock        | B450M-HDV                   | [996f8b5618](https://bsd-hardware.info/?probe=996f8b5618) | Aug 22, 2021 |
| Unknown       | Unknown                     | [beda690c72](https://bsd-hardware.info/?probe=beda690c72) | Aug 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | [f4fe59224e](https://bsd-hardware.info/?probe=f4fe59224e) | Aug 18, 2021 |
| Unknown       | Unknown                     | [621207a309](https://bsd-hardware.info/?probe=621207a309) | Aug 11, 2021 |
| Shuttle       | FH81                        | [58ddd2da40](https://bsd-hardware.info/?probe=58ddd2da40) | Aug 08, 2021 |
| Intel         | DH67BL AAG10189-211         | [6106746a7f](https://bsd-hardware.info/?probe=6106746a7f) | Aug 07, 2021 |
| NU941         | 1.0                         | [e76f1a177c](https://bsd-hardware.info/?probe=e76f1a177c) | Aug 07, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [aad64262b5](https://bsd-hardware.info/?probe=aad64262b5) | Jul 29, 2021 |
| Unknown       | PICO PC                     | [47f932c3d3](https://bsd-hardware.info/?probe=47f932c3d3) | Jul 29, 2021 |
| Biostar       | A88M                        | [f9d3b78d58](https://bsd-hardware.info/?probe=f9d3b78d58) | Jul 26, 2021 |
| Unknown       | Unknown                     | [41e0c49bcb](https://bsd-hardware.info/?probe=41e0c49bcb) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | [05180e292a](https://bsd-hardware.info/?probe=05180e292a) | Jul 24, 2021 |
| ASUSTek       | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| HP            | 213D A01                    | [3b518acc68](https://bsd-hardware.info/?probe=3b518acc68) | Jul 15, 2021 |
| Unknown       | Unknown                     | [17938ca56f](https://bsd-hardware.info/?probe=17938ca56f) | Jul 14, 2021 |
| Dell          | 0F6X5P A00                  | [46aaff0a7c](https://bsd-hardware.info/?probe=46aaff0a7c) | Jul 14, 2021 |
| HP            | 0AE8h C                     | [23df6b2e94](https://bsd-hardware.info/?probe=23df6b2e94) | Jul 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0c9fc39896](https://bsd-hardware.info/?probe=0c9fc39896) | Jul 11, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3d69b35f7d](https://bsd-hardware.info/?probe=3d69b35f7d) | Jul 11, 2021 |
| Unknown       | Unknown                     | [4a3836de00](https://bsd-hardware.info/?probe=4a3836de00) | Jul 08, 2021 |
| Protectli     | FW4B Ver                    | [18d373b2d3](https://bsd-hardware.info/?probe=18d373b2d3) | Jul 06, 2021 |
| ASRock        | J3355B-ITX                  | [d8bd1a3025](https://bsd-hardware.info/?probe=d8bd1a3025) | Jul 05, 2021 |
| ASRock        | B450M-HDV                   | [dca41aa10a](https://bsd-hardware.info/?probe=dca41aa10a) | Jul 05, 2021 |
| PC Engines    | apu4                        | [18a1374b95](https://bsd-hardware.info/?probe=18a1374b95) | Jul 04, 2021 |
| Biostar       | B450MH                      | [167f09a25c](https://bsd-hardware.info/?probe=167f09a25c) | Jun 29, 2021 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [1b35a7ea0a](https://bsd-hardware.info/?probe=1b35a7ea0a) | Jun 28, 2021 |
| Intel CNCT... | Unknown                     | [d2298356a0](https://bsd-hardware.info/?probe=d2298356a0) | Jun 22, 2021 |
| Intel         | DH67CL AAG10212-206         | [f2367a4249](https://bsd-hardware.info/?probe=f2367a4249) | Jun 21, 2021 |
| Unknown       | Unknown                     | [287ec8a2ee](https://bsd-hardware.info/?probe=287ec8a2ee) | Jun 19, 2021 |
| Unknown       | Unknown                     | [e6a66eac0b](https://bsd-hardware.info/?probe=e6a66eac0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z270-A                | [c7b4a17b7d](https://bsd-hardware.info/?probe=c7b4a17b7d) | Jun 19, 2021 |
| Unknown       | Unknown                     | [c3f7e818ae](https://bsd-hardware.info/?probe=c3f7e818ae) | Jun 18, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [5ccdc16de4](https://bsd-hardware.info/?probe=5ccdc16de4) | Jun 12, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [9062f35935](https://bsd-hardware.info/?probe=9062f35935) | Jun 10, 2021 |
| Dell          | 02YYK5 A01                  | [2bb2632198](https://bsd-hardware.info/?probe=2bb2632198) | Jun 04, 2021 |
| Gigabyte      | J3455N-D3H                  | [23751b05a9](https://bsd-hardware.info/?probe=23751b05a9) | Jun 01, 2021 |
| PC Engines    | APU2                        | [c5f1ffd6c0](https://bsd-hardware.info/?probe=c5f1ffd6c0) | May 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cd60e38216](https://bsd-hardware.info/?probe=cd60e38216) | May 30, 2021 |
| HP            | 213D A01                    | [de3d6dcdf5](https://bsd-hardware.info/?probe=de3d6dcdf5) | May 22, 2021 |
| HP            | 18E7                        | [56a672af0a](https://bsd-hardware.info/?probe=56a672af0a) | May 20, 2021 |
| Apple         | Mac-F221BEC8                | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [b7ea8547ce](https://bsd-hardware.info/?probe=b7ea8547ce) | May 15, 2021 |
| EVGA          | X299 FTW K                  | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [cc49321b12](https://bsd-hardware.info/?probe=cc49321b12) | May 11, 2021 |
| Biostar       | A88M                        | [74c3afbf45](https://bsd-hardware.info/?probe=74c3afbf45) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| Unknown       | Unknown                     | [a707beae6f](https://bsd-hardware.info/?probe=a707beae6f) | May 02, 2021 |
| Yanling       | YL-KBR6L Ver:1.01           | [0cddbdee33](https://bsd-hardware.info/?probe=0cddbdee33) | May 01, 2021 |
| Dell          | 0WR7PY A02                  | [1a780b9a95](https://bsd-hardware.info/?probe=1a780b9a95) | Apr 27, 2021 |
| ASUSTek       | Z87-PRO                     | [d218181abb](https://bsd-hardware.info/?probe=d218181abb) | Apr 26, 2021 |
| Intel         | Q3XXG4-P V1.0               | [f888bd5312](https://bsd-hardware.info/?probe=f888bd5312) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7dacccd5f5](https://bsd-hardware.info/?probe=7dacccd5f5) | Apr 18, 2021 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | [1cef60d042](https://bsd-hardware.info/?probe=1cef60d042) | Apr 13, 2021 |
| Dell          | 0VRWRC A00                  | [903d74f8e7](https://bsd-hardware.info/?probe=903d74f8e7) | Apr 12, 2021 |
| Unknown       | PICO PC                     | [8ab959af5c](https://bsd-hardware.info/?probe=8ab959af5c) | Apr 11, 2021 |
| Biostar       | A88M                        | [6fc307ade8](https://bsd-hardware.info/?probe=6fc307ade8) | Apr 09, 2021 |
| Unknown       | Unknown                     | [9eafdd3e07](https://bsd-hardware.info/?probe=9eafdd3e07) | Apr 07, 2021 |
| Unknown       | Unknown                     | [5393389555](https://bsd-hardware.info/?probe=5393389555) | Apr 05, 2021 |
| Dell          | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7fc044cdb6](https://bsd-hardware.info/?probe=7fc044cdb6) | Apr 03, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [12909e67d4](https://bsd-hardware.info/?probe=12909e67d4) | Mar 23, 2021 |
| AMI           | PEISIA E3845 VER1.0         | [159f39df79](https://bsd-hardware.info/?probe=159f39df79) | Mar 23, 2021 |
| Unknown       | Unknown                     | [a81f03223e](https://bsd-hardware.info/?probe=a81f03223e) | Mar 22, 2021 |
| Unknown       | Unknown                     | [04d2c36bec](https://bsd-hardware.info/?probe=04d2c36bec) | Mar 22, 2021 |
| HP            | 1825                        | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Unknown       | Unknown                     | [192451364a](https://bsd-hardware.info/?probe=192451364a) | Mar 20, 2021 |
| Quanmax       | spo-book TECH QUAD B1       | [3e479a0551](https://bsd-hardware.info/?probe=3e479a0551) | Mar 16, 2021 |
| ASUSTek       | H110M-PLUS                  | [80e7c230d7](https://bsd-hardware.info/?probe=80e7c230d7) | Mar 12, 2021 |
| ASUSTek       | H110M-PLUS                  | [cf00023cef](https://bsd-hardware.info/?probe=cf00023cef) | Mar 11, 2021 |
| PC Engines    | APU2                        | [14142a990a](https://bsd-hardware.info/?probe=14142a990a) | Mar 09, 2021 |
| Unknown       | Unknown                     | [1ad8d8132f](https://bsd-hardware.info/?probe=1ad8d8132f) | Mar 09, 2021 |
| ASUSTek       | All Series                  | [b4aec46644](https://bsd-hardware.info/?probe=b4aec46644) | Mar 07, 2021 |
| ASUSTek       | All Series                  | [f7b1921594](https://bsd-hardware.info/?probe=f7b1921594) | Mar 07, 2021 |
| ASUSTek       | P8Z77-V                     | [88ee81b089](https://bsd-hardware.info/?probe=88ee81b089) | Mar 06, 2021 |
| Unknown       | Unknown                     | [99448b6fad](https://bsd-hardware.info/?probe=99448b6fad) | Mar 02, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | [d106f46dde](https://bsd-hardware.info/?probe=d106f46dde) | Mar 01, 2021 |
| Shuttle       | FS61                        | [3016999a76](https://bsd-hardware.info/?probe=3016999a76) | Feb 25, 2021 |
| Unknown       | YL-SKUL6                    | [96d7fbef45](https://bsd-hardware.info/?probe=96d7fbef45) | Feb 25, 2021 |
| Acer          | RS780HVF                    | [3367ae4413](https://bsd-hardware.info/?probe=3367ae4413) | Feb 24, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [0aeea0fec9](https://bsd-hardware.info/?probe=0aeea0fec9) | Feb 23, 2021 |
| Biostar       | A88M                        | [2d4a32fbc3](https://bsd-hardware.info/?probe=2d4a32fbc3) | Feb 22, 2021 |
| Biostar       | A88M                        | [7ff97a241a](https://bsd-hardware.info/?probe=7ff97a241a) | Feb 22, 2021 |
| MSI           | A78M-E35                    | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [3f0003e9a2](https://bsd-hardware.info/?probe=3f0003e9a2) | Feb 19, 2021 |
| Gigabyte      | M68MT-S2                    | [5d94572e10](https://bsd-hardware.info/?probe=5d94572e10) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [3c043807ba](https://bsd-hardware.info/?probe=3c043807ba) | Feb 15, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [62e8f472f6](https://bsd-hardware.info/?probe=62e8f472f6) | Feb 15, 2021 |
| Shuttle       | DS10U                       | [ad9283aae7](https://bsd-hardware.info/?probe=ad9283aae7) | Feb 14, 2021 |
| Intel         | Q3XXG4-P V1.0               | [7313a6d6e2](https://bsd-hardware.info/?probe=7313a6d6e2) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [565ceb36f0](https://bsd-hardware.info/?probe=565ceb36f0) | Feb 14, 2021 |
| Shuttle       | DS10U                       | [aef3ca0794](https://bsd-hardware.info/?probe=aef3ca0794) | Feb 12, 2021 |
| ASUSTek       | Z87-PRO                     | [ad0f0dde9d](https://bsd-hardware.info/?probe=ad0f0dde9d) | Feb 10, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [435f081b3b](https://bsd-hardware.info/?probe=435f081b3b) | Feb 09, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [7a8ab8feaf](https://bsd-hardware.info/?probe=7a8ab8feaf) | Feb 08, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| QOTOM         | Q355G4-P V1.0               | [5c09abed71](https://bsd-hardware.info/?probe=5c09abed71) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | [c79ea5055f](https://bsd-hardware.info/?probe=c79ea5055f) | Feb 05, 2021 |
| QOTOM         | Q355G4-P V1.0               | [222778ae2b](https://bsd-hardware.info/?probe=222778ae2b) | Feb 05, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [f827129438](https://bsd-hardware.info/?probe=f827129438) | Feb 04, 2021 |
| Unknown       | PICO PC                     | [de1cd4e050](https://bsd-hardware.info/?probe=de1cd4e050) | Feb 04, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [b192745cde](https://bsd-hardware.info/?probe=b192745cde) | Feb 03, 2021 |
| Lenovo        | SDK0J40705 WIN 342503995... | [c11da3972d](https://bsd-hardware.info/?probe=c11da3972d) | Feb 03, 2021 |
| Protectli     | FW4B                        | [5334bf8761](https://bsd-hardware.info/?probe=5334bf8761) | Feb 03, 2021 |
| Deciso        | Netboard A10                | [a3f5b21dff](https://bsd-hardware.info/?probe=a3f5b21dff) | Feb 03, 2021 |
| Supermicro    | X8SIU                       | [57fbc2cb9a](https://bsd-hardware.info/?probe=57fbc2cb9a) | Feb 02, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6b9511bf39](https://bsd-hardware.info/?probe=6b9511bf39) | Jan 31, 2021 |
| Unknown       | YL-SKUL6                    | [9f0538d38b](https://bsd-hardware.info/?probe=9f0538d38b) | Jan 31, 2021 |
| ASRock        | X399 Taichi                 | [875e6714ca](https://bsd-hardware.info/?probe=875e6714ca) | Jan 27, 2021 |
| ASRock        | J3455M                      | [c90667d62c](https://bsd-hardware.info/?probe=c90667d62c) | Jan 27, 2021 |
| Lenovo        | Board                       | [da81aa7cb9](https://bsd-hardware.info/?probe=da81aa7cb9) | Jan 26, 2021 |
| AZW           | GK55                        | [077fedae7d](https://bsd-hardware.info/?probe=077fedae7d) | Jan 26, 2021 |
| AZW           | GK55                        | [db3fc2c7b2](https://bsd-hardware.info/?probe=db3fc2c7b2) | Jan 25, 2021 |
| Intel         | Q3XXG4-P V1.0               | [aa5782d83e](https://bsd-hardware.info/?probe=aa5782d83e) | Jan 24, 2021 |
| Dell          | 0WMJ54 A01                  | [6d11e7b348](https://bsd-hardware.info/?probe=6d11e7b348) | Jan 23, 2021 |
| Unknown       | Unknown                     | [aeb42f8919](https://bsd-hardware.info/?probe=aeb42f8919) | Jan 23, 2021 |
| Unknown       | Unknown                     | [5b3be23f50](https://bsd-hardware.info/?probe=5b3be23f50) | Jan 23, 2021 |
| Jetway        | 1.0                         | [8f47246cdf](https://bsd-hardware.info/?probe=8f47246cdf) | Jan 23, 2021 |
| Unknown       | Unknown                     | [f952cac718](https://bsd-hardware.info/?probe=f952cac718) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [29c88c0b95](https://bsd-hardware.info/?probe=29c88c0b95) | Jan 22, 2021 |
| Protectli     | FW4B                        | [ea6fcc20bc](https://bsd-hardware.info/?probe=ea6fcc20bc) | Jan 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | [1722f1824f](https://bsd-hardware.info/?probe=1722f1824f) | Jan 22, 2021 |
| PC Engines    | APU2                        | [0fac28f2bf](https://bsd-hardware.info/?probe=0fac28f2bf) | Jan 21, 2021 |
| Shuttle       | FS67U                       | [8ed524df62](https://bsd-hardware.info/?probe=8ed524df62) | Jan 20, 2021 |
| Protectli     | FW4A Ver                    | [5725505d31](https://bsd-hardware.info/?probe=5725505d31) | Jan 20, 2021 |
| PC Engines    | APU2                        | [49463c91f7](https://bsd-hardware.info/?probe=49463c91f7) | Jan 19, 2021 |
| Dell          | 0M863N A01                  | [4feae8b20d](https://bsd-hardware.info/?probe=4feae8b20d) | Jan 15, 2021 |
| ASRock        | 990FX Extreme4              | [20c77fd91b](https://bsd-hardware.info/?probe=20c77fd91b) | Dec 16, 2020 |
| Gigabyte      | Z97P-D3                     | [588af8f5b3](https://bsd-hardware.info/?probe=588af8f5b3) | Dec 16, 2020 |
| Acer          | Aspire X1440                | [6100b30349](https://bsd-hardware.info/?probe=6100b30349) | Dec 15, 2020 |
| Apple         | Xserve3,1                   | [7329a7650d](https://bsd-hardware.info/?probe=7329a7650d) | Dec 05, 2020 |
| ASUSTek       | PRIME X570-P                | [1076ee5826](https://bsd-hardware.info/?probe=1076ee5826) | Dec 04, 2020 |
| ASUSTek       | PRIME X570-P                | [ec1363a9ea](https://bsd-hardware.info/?probe=ec1363a9ea) | Dec 04, 2020 |
| MSI           | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| ASRock        | IMB-191                     | [76991234cd](https://bsd-hardware.info/?probe=76991234cd) | Nov 18, 2020 |
| Unknown       | Unknown                     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Intel         | CRESCENTBAY                 | [42d114559b](https://bsd-hardware.info/?probe=42d114559b) | Oct 21, 2020 |
| ASRock        | IMB-191                     | [4ac9e9cf2a](https://bsd-hardware.info/?probe=4ac9e9cf2a) | Oct 19, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| Lenovo        | 3098 SDK0E50510 WIN         | [b9b460d9e2](https://bsd-hardware.info/?probe=b9b460d9e2) | Sep 28, 2020 |
| PC Engines    | apu4                        | [f0f8a22656](https://bsd-hardware.info/?probe=f0f8a22656) | Aug 05, 2020 |
| Biostar       | B450MH                      | [4ad280f947](https://bsd-hardware.info/?probe=4ad280f947) | Aug 02, 2020 |
| HPE           | ProLiant MicroServer Gen... | [6b015a340b](https://bsd-hardware.info/?probe=6b015a340b) | Jul 31, 2020 |
| Lenovo        | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Sony UK       | Raspberry Pi 4 Model B      | [483af3998c](https://bsd-hardware.info/?probe=483af3998c) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| HP            | 213D A01                    | [23f8adb299](https://bsd-hardware.info/?probe=23f8adb299) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 23.1.11     | 13       | 3.4%    |
| OPNsense 20.7.8      | 12       | 3.14%   |
| OPNsense 22.7.10     | 11       | 2.88%   |
| OPNsense 21.7.7      | 8        | 2.09%   |
| OPNsense 21.1.5      | 8        | 2.09%   |
| helloSystem 0.5.0    | 8        | 2.09%   |
| OPNsense 23.1.5      | 7        | 1.83%   |
| OPNsense 23.1.3      | 7        | 1.83%   |
| OPNsense 23.1.1      | 7        | 1.83%   |
| OPNsense 22.1        | 7        | 1.83%   |
| OPNsense 21.7.1      | 7        | 1.83%   |
| OPNsense 21.1        | 7        | 1.83%   |
| OPNsense 23.7.7      | 6        | 1.57%   |
| OPNsense 23.1.9      | 6        | 1.57%   |
| OPNsense 23.1.6      | 6        | 1.57%   |
| OPNsense 22.7.4      | 6        | 1.57%   |
| OPNsense 22.1.6      | 6        | 1.57%   |
| OPNsense 21.1.7      | 6        | 1.57%   |
| OPNsense 21.1.4      | 6        | 1.57%   |
| helloSystem 0.4.0    | 6        | 1.57%   |
| OPNsense 23.7.6      | 5        | 1.31%   |
| OPNsense 23.7.5      | 5        | 1.31%   |
| OPNsense 23.7.2      | 5        | 1.31%   |
| OPNsense 23.7.1      | 5        | 1.31%   |
| OPNsense 22.7.9      | 5        | 1.31%   |
| OPNsense 22.7.7      | 5        | 1.31%   |
| OPNsense 22.7.6      | 5        | 1.31%   |
| OPNsense 22.7.2      | 5        | 1.31%   |
| OPNsense 22.1.9      | 5        | 1.31%   |
| OPNsense 22.1.8      | 5        | 1.31%   |
| OPNsense 22.1.3      | 5        | 1.31%   |
| OPNsense 21.7.8      | 5        | 1.31%   |
| OPNsense 21.7.3      | 5        | 1.31%   |
| OPNsense 21.1.1      | 5        | 1.31%   |
| FreeBSD 14.0-CURRENT | 5        | 1.31%   |
| OPNsense 23.7.3      | 4        | 1.05%   |
| OPNsense 23.1.7      | 4        | 1.05%   |
| OPNsense 23.1.10     | 4        | 1.05%   |
| OPNsense 23.1        | 4        | 1.05%   |
| OPNsense 22.7.8      | 4        | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 203      | 70.49%  |
| FreeBSD     | 35       | 12.15%  |
| helloSystem | 28       | 9.72%   |
| OpenBSD     | 11       | 3.82%   |
| GhostBSD    | 4        | 1.39%   |
| XigmaNAS    | 3        | 1.04%   |
| NetBSD      | 3        | 1.04%   |
| pfSense     | 1        | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 281      | 98.25%  |
| arm64 | 4        | 1.4%    |
| riscv | 1        | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Console          | 228      | 79.17%  |
| helloDesktop     | 29       | 10.07%  |
| KDE5             | 9        | 3.13%   |
| XFCE             | 7        | 2.43%   |
| MATE             | 3        | 1.04%   |
| GNOME            | 3        | 1.04%   |
| fvwm             | 2        | 0.69%   |
| TWM              | 1        | 0.35%   |
| PekWM            | 1        | 0.35%   |
| Openbox          | 1        | 0.35%   |
| Metacity (Marco) | 1        | 0.35%   |
| DWM              | 1        | 0.35%   |
| Cinnamon         | 1        | 0.35%   |
| CDE              | 1        | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 227      | 79.09%  |
| X11     | 58       | 20.21%  |
| Wayland | 2        | 0.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 245      | 84.48%  |
| SLiM    | 27       | 9.31%   |
| SDDM    | 7        | 2.41%   |
| LightDM | 6        | 2.07%   |
| XDM     | 2        | 0.69%   |
| GDM     | 2        | 0.69%   |
| Ly      | 1        | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 224      | 76.71%  |
| en_US          | 30       | 10.27%  |
| C              | 22       | 7.53%   |
| en_GB          | 11       | 3.77%   |
| en             | 3        | 1.03%   |
| fr_FR          | 1        | 0.34%   |
| en_GB.US-ASCII | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 250      | 86.21%  |
| BIOS | 40       | 13.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 170      | 57.82%  |
| Zfs     | 105      | 35.71%  |
| Ffs     | 11       | 3.74%   |
| Cd9660  | 7        | 2.38%   |
| Unknown | 1        | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 267      | 92.71%  |
| MBR     | 15       | 5.21%   |
| Unknown | 6        | 2.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 46       | 16.08%  |
| Dell                                 | 27       | 9.44%   |
| ASUSTek Computer                     | 26       | 9.09%   |
| Intel                                | 22       | 7.69%   |
| Gigabyte Technology                  | 22       | 7.69%   |
| Hewlett-Packard                      | 16       | 5.59%   |
| ASRock                               | 14       | 4.9%    |
| Lenovo                               | 13       | 4.55%   |
| Protectli                            | 10       | 3.5%    |
| PC Engines                           | 9        | 3.15%   |
| MSI                                  | 8        | 2.8%    |
| Shuttle                              | 6        | 2.1%    |
| Fujitsu                              | 6        | 2.1%    |
| Acer                                 | 5        | 1.75%   |
| Techvision                           | 4        | 1.4%    |
| Supermicro                           | 3        | 1.05%   |
| PICO PC                              | 3        | 1.05%   |
| IceWhale Technology                  | 3        | 1.05%   |
| Biostar                              | 3        | 1.05%   |
| Yanling                              | 2        | 0.7%    |
| Raspberry Pi Foundation              | 2        | 0.7%    |
| Inventec                             | 2        | 0.7%    |
| HPE                                  | 2        | 0.7%    |
| Deciso                               | 2        | 0.7%    |
| CncTion                              | 2        | 0.7%    |
| AZW                                  | 2        | 0.7%    |
| ASRockRack                           | 2        | 0.7%    |
| Apple                                | 2        | 0.7%    |
| AMI                                  | 2        | 0.7%    |
| Winston Marriot                      | 1        | 0.35%   |
| Sony UK                              | 1        | 0.35%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.35%   |
| Seeed Studio                         | 1        | 0.35%   |
| Quanmax                              | 1        | 0.35%   |
| QOTOM                                | 1        | 0.35%   |
| PAIQ                                 | 1        | 0.35%   |
| NU941                                | 1        | 0.35%   |
| maiyunda                             | 1        | 0.35%   |
| Jetway                               | 1        | 0.35%   |
| Intel GMLV114                        | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 47       | 16.43%  |
| Intel Q3XXG4-P V1.0                 | 8        | 2.8%    |
| PC Engines APU2                     | 5        | 1.75%   |
| ASUS All Series                     | 5        | 1.75%   |
| Techvision TVI7309X                 | 4        | 1.4%    |
| Protectli FW6                       | 4        | 1.4%    |
| Protectli FW4B                      | 4        | 1.4%    |
| Dell OptiPlex 7010                  | 4        | 1.4%    |
| PICO PC MNHO-113                    | 3        | 1.05%   |
| PC Engines apu4                     | 3        | 1.05%   |
| Intel SHARKBAY                      | 3        | 1.05%   |
| HP t620 PLUS Quad Core TC           | 3        | 1.05%   |
| Fujitsu FUTRO S920                  | 3        | 1.05%   |
| Dell OptiPlex 790                   | 3        | 1.05%   |
| Dell OptiPlex 760                   | 3        | 1.05%   |
| Dell OptiPlex 3020                  | 3        | 1.05%   |
| Yanling YL-KBR6L                    | 2        | 0.7%    |
| Lenovo ThinkCentre M920s 10SJ0041UK | 2        | 0.7%    |
| Lenovo ThinkCentre E73 10DS0015UK   | 2        | 0.7%    |
| IceWhale ZimaBoard 832 ZMB          | 2        | 0.7%    |
| HP Z600 Workstation                 | 2        | 0.7%    |
| HP ProLiant MicroServer Gen8        | 2        | 0.7%    |
| Gigabyte B450M DS3H                 | 2        | 0.7%    |
| Dell OptiPlex 390                   | 2        | 0.7%    |
| ASUS ROG STRIX X570-E GAMING        | 2        | 0.7%    |
| ASUS PRIME H510M-E                  | 2        | 0.7%    |
| ASUS H110M-PLUS                     | 2        | 0.7%    |
| ASRock B550 Phantom Gaming 4        | 2        | 0.7%    |
| AMI PEISIA E3845 VER1.0             | 2        | 0.7%    |
| Winston Marriot PICO PC(R)          | 1        | 0.35%   |
| Supermicro X8SIU                    | 1        | 0.35%   |
| Supermicro X8SIL                    | 1        | 0.35%   |
| Supermicro M12SWA-TF                | 1        | 0.35%   |
| Sony UK Raspberry Pi 4 Model B      | 1        | 0.35%   |
| Shuttle XH61V                       | 1        | 0.35%   |
| Shuttle XH170                       | 1        | 0.35%   |
| Shuttle SH81R                       | 1        | 0.35%   |
| Shuttle DS67U                       | 1        | 0.35%   |
| Shuttle DS61                        | 1        | 0.35%   |
| Shuttle DS10U                       | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Unknown              | 47       | 16.43%  |
| Dell OptiPlex        | 24       | 8.39%   |
| Lenovo ThinkCentre   | 11       | 3.85%   |
| Intel Q3XXG4-P       | 8        | 2.8%    |
| ASUS ROG             | 6        | 2.1%    |
| ASUS PRIME           | 6        | 2.1%    |
| PC Engines APU2      | 5        | 1.75%   |
| ASUS All             | 5        | 1.75%   |
| Acer Aspire          | 5        | 1.75%   |
| Techvision TVI7309X  | 4        | 1.4%    |
| Protectli FW6        | 4        | 1.4%    |
| Protectli FW4B       | 4        | 1.4%    |
| HP EliteDesk         | 4        | 1.4%    |
| Fujitsu FUTRO        | 4        | 1.4%    |
| PICO PC MNHO-113     | 3        | 1.05%   |
| PC Engines apu4      | 3        | 1.05%   |
| Intel SHARKBAY       | 3        | 1.05%   |
| IceWhale ZimaBoard   | 3        | 1.05%   |
| HP t620              | 3        | 1.05%   |
| HP ProDesk           | 3        | 1.05%   |
| Yanling YL-KBR6L     | 2        | 0.7%    |
| RPi Raspberry        | 2        | 0.7%    |
| HPE ProLiant         | 2        | 0.7%    |
| HP Z600              | 2        | 0.7%    |
| HP ProLiant          | 2        | 0.7%    |
| Gigabyte H61M-DS2    | 2        | 0.7%    |
| Gigabyte B450M       | 2        | 0.7%    |
| Fujitsu ESPRIMO      | 2        | 0.7%    |
| Dell Precision       | 2        | 0.7%    |
| Deciso Netboard      | 2        | 0.7%    |
| ASUS P8Z77-V         | 2        | 0.7%    |
| ASUS H110M-PLUS      | 2        | 0.7%    |
| ASRock B550          | 2        | 0.7%    |
| AMI PEISIA           | 2        | 0.7%    |
| Winston Marriot PICO | 1        | 0.35%   |
| Supermicro X8SIU     | 1        | 0.35%   |
| Supermicro X8SIL     | 1        | 0.35%   |
| Supermicro M12SWA-TF | 1        | 0.35%   |
| Sony UK Raspberry    | 1        | 0.35%   |
| Shuttle XH61V        | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 35       | 12.24%  |
| 2018    | 29       | 10.14%  |
| 2022    | 28       | 9.79%   |
| 2020    | 25       | 8.74%   |
| 2021    | 24       | 8.39%   |
| 2016    | 23       | 8.04%   |
| 2013    | 23       | 8.04%   |
| 2019    | 21       | 7.34%   |
| 2023    | 14       | 4.9%    |
| 2015    | 14       | 4.9%    |
| 2017    | 11       | 3.85%   |
| 2012    | 10       | 3.5%    |
| 2010    | 8        | 2.8%    |
| 2011    | 7        | 2.45%   |
| 2009    | 7        | 2.45%   |
| Unknown | 4        | 1.4%    |
| 2008    | 2        | 0.7%    |
| 2007    | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 286      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 274      | 95.8%   |
| Yes  | 12       | 4.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 115      | 40.07%  |
| 16.01-24.0      | 71       | 24.74%  |
| 4.01-8.0        | 55       | 19.16%  |
| 32.01-64.0      | 19       | 6.62%   |
| 2.01-3.0        | 9        | 3.14%   |
| 64.01-256.0     | 9        | 3.14%   |
| 3.01-4.0        | 4        | 1.39%   |
| 24.01-32.0      | 4        | 1.39%   |
| More than 256.0 | 1        | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.01-0.5    | 155      | 52.54%  |
| 0.51-1.0    | 89       | 30.17%  |
| 1.01-2.0    | 27       | 9.15%   |
| 3.01-4.0    | 7        | 2.37%   |
| 2.01-3.0    | 6        | 2.03%   |
| 4.01-8.0    | 4        | 1.36%   |
| Unknown     | 3        | 1.02%   |
| 24.01-32.0  | 2        | 0.68%   |
| 32.01-64.0  | 1        | 0.34%   |
| 64.01-256.0 | 1        | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 194      | 66.44%  |
| 0      | 36       | 12.33%  |
| 2      | 28       | 9.59%   |
| 3      | 12       | 4.11%   |
| 4      | 8        | 2.74%   |
| 5      | 6        | 2.05%   |
| 8      | 3        | 1.03%   |
| 7      | 3        | 1.03%   |
| 24     | 1        | 0.34%   |
| 6      | 1        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 241      | 83.68%  |
| Yes       | 47       | 16.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 280      | 97.9%   |
| No        | 6        | 2.1%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 231      | 80.49%  |
| Yes       | 56       | 19.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 248      | 86.41%  |
| Yes       | 39       | 13.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| UK      | 286      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| London                | 44       | 13.17%  |
| Newcastle upon Tyne   | 6        | 1.8%    |
| Sheffield             | 5        | 1.5%    |
| Reading               | 5        | 1.5%    |
| Hull                  | 5        | 1.5%    |
| Watford               | 4        | 1.2%    |
| Stourbridge           | 4        | 1.2%    |
| Leeds                 | 4        | 1.2%    |
| Coventry              | 4        | 1.2%    |
| Cambridge             | 4        | 1.2%    |
| Birmingham            | 4        | 1.2%    |
| York                  | 3        | 0.9%    |
| Wolverhampton         | 3        | 0.9%    |
| Wittersham            | 3        | 0.9%    |
| Walsall               | 3        | 0.9%    |
| Slough                | 3        | 0.9%    |
| Poplar                | 3        | 0.9%    |
| Milton Keynes         | 3        | 0.9%    |
| Mansfield             | 3        | 0.9%    |
| Liverpool             | 3        | 0.9%    |
| Kensington            | 3        | 0.9%    |
| Glasgow               | 3        | 0.9%    |
| Dundee                | 3        | 0.9%    |
| City of Westminster   | 3        | 0.9%    |
| Bristol               | 3        | 0.9%    |
| Basingstoke           | 3        | 0.9%    |
| Andover               | 3        | 0.9%    |
| Worthing              | 2        | 0.6%    |
| Woking                | 2        | 0.6%    |
| Telford               | 2        | 0.6%    |
| Sutton Coldfield      | 2        | 0.6%    |
| St Albans             | 2        | 0.6%    |
| Scunthorpe            | 2        | 0.6%    |
| Ruthin                | 2        | 0.6%    |
| Royal Tunbridge Wells | 2        | 0.6%    |
| Romford               | 2        | 0.6%    |
| Oldham                | 2        | 0.6%    |
| Notting Hill Gate     | 2        | 0.6%    |
| Manchester            | 2        | 0.6%    |
| Malton                | 2        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 43       | 77     | 13.65%  |
| WDC                 | 33       | 63     | 10.48%  |
| Crucial             | 32       | 48     | 10.16%  |
| Kingston            | 31       | 44     | 9.84%   |
| Seagate             | 29       | 56     | 9.21%   |
| SanDisk             | 18       | 20     | 5.71%   |
| Transcend           | 13       | 17     | 4.13%   |
| Toshiba             | 12       | 59     | 3.81%   |
| Phison              | 10       | 14     | 3.17%   |
| Hoodisk             | 10       | 18     | 3.17%   |
| Intel               | 7        | 8      | 2.22%   |
| Hitachi             | 7        | 11     | 2.22%   |
| LITEONIT            | 6        | 7      | 1.9%    |
| SK hynix            | 5        | 6      | 1.59%   |
| OCZ                 | 4        | 7      | 1.27%   |
| Micron Technology   | 3        | 4      | 0.95%   |
| Lexar               | 3        | 3      | 0.95%   |
| Integral            | 3        | 5      | 0.95%   |
| Gigabyte Technology | 3        | 4      | 0.95%   |
| Corsair             | 3        | 6      | 0.95%   |
| China               | 3        | 3      | 0.95%   |
| Vaseky              | 2        | 2      | 0.63%   |
| SPCC                | 2        | 2      | 0.63%   |
| Silicon Motion      | 2        | 2      | 0.63%   |
| PNY                 | 2        | 10     | 0.63%   |
| OPENBSD             | 2        | 2      | 0.63%   |
| Fanxiang            | 2        | 2      | 0.63%   |
| BR                  | 2        | 2      | 0.63%   |
| BIWIN               | 2        | 5      | 0.63%   |
| Apacer              | 2        | 3      | 0.63%   |
| A-DATA Technology   | 2        | 3      | 0.63%   |
| Zheino              | 1        | 1      | 0.32%   |
| TCSUNBOW            | 1        | 3      | 0.32%   |
| ShiJi               | 1        | 1      | 0.32%   |
| Patriot             | 1        | 4      | 0.32%   |
| ORTIAL              | 1        | 1      | 0.32%   |
| Netac               | 1        | 5      | 0.32%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.32%   |
| KIOXIA              | 1        | 3      | 0.32%   |
| Intenso             | 1        | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB          | 5        | 1.42%   |
| Hoodisk SSD 64GB                     | 5        | 1.42%   |
| Crucial CT120BX500SSD1 120GB         | 5        | 1.42%   |
| Hoodisk SSD 32GB                     | 4        | 1.14%   |
| Crucial CT240BX500SSD1 240GB         | 4        | 1.14%   |
| Toshiba HDWE140 4TB                  | 3        | 0.85%   |
| Seagate ST500DM002-1BD142 500GB      | 3        | 0.85%   |
| SanDisk SSD PLUS 480GB               | 3        | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB         | 3        | 0.85%   |
| Samsung SSD 850 EVO 250GB            | 3        | 0.85%   |
| Samsung SSD 840 EVO 250GB            | 3        | 0.85%   |
| Phison Sabrent 1TB                   | 3        | 0.85%   |
| Kingston SUV500MS240G 240GB          | 3        | 0.85%   |
| Kingston SUV500MS120G 120GB          | 3        | 0.85%   |
| Kingston SA400S37120G 120GB          | 3        | 0.85%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 3        | 0.85%   |
| Crucial CT500MX500SSD1 500GB         | 3        | 0.85%   |
| Crucial CT480BX500SSD1 480GB         | 3        | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2        | 0.57%   |
| WDC WD20EZRX-22D8PB0 2TB             | 2        | 0.57%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2        | 0.57%   |
| WDC WD20EFZX-68AWUN0 2TB             | 2        | 0.57%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2        | 0.57%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 2        | 0.57%   |
| Transcend TS128GMTE110S 128GB        | 2        | 0.57%   |
| Transcend TS128GMSA370 128GB         | 2        | 0.57%   |
| Toshiba DT01ACA200 2TB               | 2        | 0.57%   |
| Seagate ST8000VN0022-2EL112 8TB      | 2        | 0.57%   |
| Seagate ST4000NE001-2MA101 4TB       | 2        | 0.57%   |
| Seagate ST3500418AS 500GB            | 2        | 0.57%   |
| Seagate ST3500312CS 500GB            | 2        | 0.57%   |
| Seagate ST3160318AS 160GB            | 2        | 0.57%   |
| Seagate ST3160310CS 160GB            | 2        | 0.57%   |
| SanDisk SDSSDA120G 120GB             | 2        | 0.57%   |
| SanDisk SDCFHS-016G                  | 2        | 0.57%   |
| Samsung SSD 980 500GB                | 2        | 0.57%   |
| Samsung SSD 960 EVO 250GB            | 2        | 0.57%   |
| Samsung SSD 860 EVO 500GB            | 2        | 0.57%   |
| Samsung SSD 860 EVO 1TB              | 2        | 0.57%   |
| Samsung SSD 830 Series 256GB         | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 56     | 35.8%   |
| WDC                 | 27       | 53     | 33.33%  |
| Toshiba             | 9        | 50     | 11.11%  |
| Hitachi             | 7        | 11     | 8.64%   |
| Samsung Electronics | 5        | 5      | 6.17%   |
| OPENBSD             | 2        | 2      | 2.47%   |
| HGST                | 1        | 1      | 1.23%   |
| Hewlett-Packard     | 1        | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 30       | 43     | 15.54%  |
| Crucial             | 28       | 43     | 14.51%  |
| Samsung Electronics | 26       | 43     | 13.47%  |
| SanDisk             | 18       | 20     | 9.33%   |
| Transcend           | 11       | 14     | 5.7%    |
| Hoodisk             | 10       | 18     | 5.18%   |
| LITEONIT            | 6        | 7      | 3.11%   |
| Intel               | 5        | 5      | 2.59%   |
| WDC                 | 4        | 6      | 2.07%   |
| Phison              | 4        | 5      | 2.07%   |
| OCZ                 | 4        | 7      | 2.07%   |
| Toshiba             | 3        | 9      | 1.55%   |
| Micron Technology   | 3        | 4      | 1.55%   |
| Lexar               | 3        | 3      | 1.55%   |
| Integral            | 3        | 5      | 1.55%   |
| Gigabyte Technology | 3        | 4      | 1.55%   |
| Corsair             | 3        | 6      | 1.55%   |
| China               | 3        | 3      | 1.55%   |
| Vaseky              | 2        | 2      | 1.04%   |
| SPCC                | 2        | 2      | 1.04%   |
| SK hynix            | 2        | 2      | 1.04%   |
| PNY                 | 2        | 8      | 1.04%   |
| BIWIN               | 2        | 5      | 1.04%   |
| Apacer              | 2        | 3      | 1.04%   |
| A-DATA Technology   | 2        | 3      | 1.04%   |
| Zheino              | 1        | 1      | 0.52%   |
| TCSUNBOW            | 1        | 3      | 0.52%   |
| ShiJi               | 1        | 1      | 0.52%   |
| Patriot             | 1        | 4      | 0.52%   |
| Netac               | 1        | 5      | 0.52%   |
| Intenso             | 1        | 1      | 0.52%   |
| Innodisk            | 1        | 3      | 0.52%   |
| FORESEE             | 1        | 1      | 0.52%   |
| Fordisk             | 1        | 2      | 0.52%   |
| BAITITON            | 1        | 1      | 0.52%   |
| Argon               | 1        | 1      | 0.52%   |
| Apple               | 1        | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 175      | 294    | 61.62%  |
| HDD  | 65       | 179    | 22.89%  |
| NVMe | 44       | 72     | 15.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 219      | 473    | 83.27%  |
| NVMe | 44       | 72     | 16.73%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 202      | 337    | 79.22%  |
| 0.51-1.0   | 22       | 35     | 8.63%   |
| 1.01-2.0   | 14       | 28     | 5.49%   |
| 3.01-4.0   | 7        | 47     | 2.75%   |
| 4.01-10.0  | 7        | 16     | 2.75%   |
| 2.01-3.0   | 3        | 10     | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 140      | 47.46%  |
| 251-500        | 45       | 15.25%  |
| 1-20           | 34       | 11.53%  |
| 21-50          | 31       | 10.51%  |
| 51-100         | 27       | 9.15%   |
| 501-1000       | 12       | 4.07%   |
| 1001-2000      | 4        | 1.36%   |
| More than 3000 | 1        | 0.34%   |
| Unknown        | 1        | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 267      | 90.82%  |
| 21-50          | 15       | 5.1%    |
| 51-100         | 5        | 1.7%    |
| 101-250        | 3        | 1.02%   |
| 251-500        | 2        | 0.68%   |
| More than 3000 | 1        | 0.34%   |
| Unknown        | 1        | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Toshiba HDWE140 4TB                              | 2        | 11     | 5.41%   |
| Seagate ST3160310CS 160GB                        | 2        | 2      | 5.41%   |
| SanDisk SSD PLUS 480GB                           | 2        | 2      | 5.41%   |
| Samsung Electronics HM160HI 160GB                | 2        | 2      | 5.41%   |
| Crucial CT525MX300SSD1 528GB                     | 2        | 3      | 5.41%   |
| WDC WD5000AAKX-221CA1 500GB                      | 1        | 1      | 2.7%    |
| WDC WD5000AAKS-60WWPA0 500GB                     | 1        | 1      | 2.7%    |
| WDC WD4001FAEX-00MJRA0 4TB                       | 1        | 4      | 2.7%    |
| WDC WD3200BEVT-22A23T0 320GB                     | 1        | 2      | 2.7%    |
| WDC WD3200AAJS-22B4A0 320GB                      | 1        | 1      | 2.7%    |
| WDC WD30EFRX-68EUZN0 3TB                         | 1        | 1      | 2.7%    |
| WDC WD20EFZX-68AWUN0 2TB                         | 1        | 2      | 2.7%    |
| WDC WD10JMVW-11AJGS0 1TB                         | 1        | 1      | 2.7%    |
| Transcend TS256GSSD320 256GB                     | 1        | 1      | 2.7%    |
| Toshiba THNSNK128GCS8 SATA 128GB                 | 1        | 1      | 2.7%    |
| Toshiba MD04ACA400 4TB                           | 1        | 1      | 2.7%    |
| Toshiba DT01ACA200 2TB                           | 1        | 1      | 2.7%    |
| Toshiba DT01ABA300 3TB                           | 1        | 1      | 2.7%    |
| Seagate ST3500418AS 500GB                        | 1        | 2      | 2.7%    |
| Seagate ST32000542AS 2TB                         | 1        | 1      | 2.7%    |
| Seagate ST250DM000-1BD141 250GB                  | 1        | 1      | 2.7%    |
| Seagate ST2000LM015-2E8174 2TB                   | 1        | 1      | 2.7%    |
| SanDisk SSD P4 16GB                              | 1        | 1      | 2.7%    |
| SanDisk SDCFHS-016G                              | 1        | 1      | 2.7%    |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1        | 2      | 2.7%    |
| Samsung Electronics SSD 970 EVO 500GB            | 1        | 3      | 2.7%    |
| Samsung Electronics MZHPV512HDGL-00000 512GB     | 1        | 1      | 2.7%    |
| Kingston SV200S3128G 128GB                       | 1        | 1      | 2.7%    |
| Hewlett-Packard VB0250EAVER 250GB                | 1        | 1      | 2.7%    |
| Crucial CT480BX500SSD1 480GB                     | 1        | 2      | 2.7%    |
| China SH00M256GB                                 | 1        | 1      | 2.7%    |
| A-DATA Technology SU630 240GB                    | 1        | 2      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 13     | 22.22%  |
| Seagate             | 6        | 7      | 16.67%  |
| Toshiba             | 5        | 15     | 13.89%  |
| Samsung Electronics | 5        | 8      | 13.89%  |
| SanDisk             | 4        | 4      | 11.11%  |
| Crucial             | 3        | 5      | 8.33%   |
| Transcend           | 1        | 1      | 2.78%   |
| Kingston            | 1        | 1      | 2.78%   |
| Hewlett-Packard     | 1        | 1      | 2.78%   |
| China               | 1        | 1      | 2.78%   |
| A-DATA Technology   | 1        | 2      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 13     | 38.1%   |
| Seagate             | 6        | 7      | 28.57%  |
| Toshiba             | 4        | 14     | 19.05%  |
| Samsung Electronics | 2        | 2      | 9.52%   |
| Hewlett-Packard     | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 37     | 58.33%  |
| SSD  | 14       | 18     | 38.89%  |
| NVMe | 1        | 3      | 2.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3160318AS 160GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 232      | 472    | 84.98%  |
| Malfunc  | 33       | 58     | 12.09%  |
| Detected | 7        | 14     | 2.56%   |
| Failed   | 1        | 1      | 0.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 209      | 58.22%  |
| AMD                              | 64       | 17.83%  |
| Samsung Electronics              | 18       | 5.01%   |
| Silicon Motion                   | 10       | 2.79%   |
| SanDisk                          | 9        | 2.51%   |
| ASMedia Technology               | 8        | 2.23%   |
| Phison Electronics               | 7        | 1.95%   |
| Marvell Technology Group         | 6        | 1.67%   |
| SK hynix                         | 4        | 1.11%   |
| Micron/Crucial Technology        | 4        | 1.11%   |
| Nvidia                           | 3        | 0.84%   |
| Broadcom / LSI                   | 3        | 0.84%   |
| Shenzhen Longsys Electronics     | 2        | 0.56%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.56%   |
| Adaptec                          | 2        | 0.56%   |
| VIA Technologies                 | 1        | 0.28%   |
| Toshiba                          | 1        | 0.28%   |
| Silicon Integrated Systems [SiS] | 1        | 0.28%   |
| Silicon Image                    | 1        | 0.28%   |
| OCZ Technology Group             | 1        | 0.28%   |
| KIOXIA                           | 1        | 0.28%   |
| Kingston Technology Company      | 1        | 0.28%   |
| Hosin Global Electronics         | 1        | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 43       | 10.97%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24       | 6.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 16       | 4.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 15       | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13       | 3.32%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 11       | 2.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 2.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 10       | 2.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 9        | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 9        | 2.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 7        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7        | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6        | 1.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 1.28%   |
| Unknown                                                                                 | 5        | 1.28%   |
| Phison E12 NVMe Controller                                                              | 4        | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 4        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.02%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3        | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 0.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.77%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2        | 0.51%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                       | 2        | 0.51%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                 | 2        | 0.51%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 2        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 256      | 73.99%  |
| NVMe | 55       | 15.9%   |
| IDE  | 25       | 7.23%   |
| RAID | 5        | 1.45%   |
| SCSI | 4        | 1.16%   |
| SAS  | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 215      | 75.17%  |
| AMD      | 66       | 23.08%  |
| ARM      | 3        | 1.05%   |
| Research | 1        | 0.35%   |
| Unknown  | 1        | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 12       | 4.14%   |
| AMD GX-412TC SOC                         | 8        | 2.76%   |
| Intel Celeron N5105 @ 2.00GHz            | 7        | 2.41%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 6        | 2.07%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 6        | 2.07%   |
| Intel Atom CPU E3845 @ 1.91GHz           | 6        | 2.07%   |
| Intel N100                               | 5        | 1.72%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 5        | 1.72%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 5        | 1.72%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 4        | 1.38%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 4        | 1.38%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 4        | 1.38%   |
| AMD Ryzen 5 3600 6-Core Processor        | 4        | 1.38%   |
| Intel Core i7-4770S CPU @ 3.10GHz        | 3        | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3        | 1.03%   |
| Intel Core i5-4570T CPU @ 2.90GHz        | 3        | 1.03%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 3        | 1.03%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 3        | 1.03%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 3        | 1.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 3        | 1.03%   |
| Intel Core i3-2100 CPU @ 3.10GH          | 3        | 1.03%   |
| Intel Core 2 Duo                         | 3        | 1.03%   |
| Intel Celeron J6413 @ 1.80GHz            | 3        | 1.03%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3        | 1.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 3        | 1.03%   |
| ARM Cortex-A72 r0p3                      | 3        | 1.03%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 3        | 1.03%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 3        | 1.03%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 3        | 1.03%   |
| AMD GX-416RA SOC                         | 3        | 1.03%   |
| Intel Core i7-6700T CPU @ 2.80GHz        | 2        | 0.69%   |
| Intel Core i7-4500U CPU @ 1.80GHz        | 2        | 0.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz        | 2        | 0.69%   |
| Intel Core i7-2600 CPU @ 3.40GH          | 2        | 0.69%   |
| Intel Core i5-4590T CPU @ 2.00GHz        | 2        | 0.69%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 2        | 0.69%   |
| Intel Core i5-4430 CPU @ 3.00GHz         | 2        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 2        | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 0.69%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 2        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 59       | 20.42%  |
| Intel Core i5           | 43       | 14.88%  |
| Intel Core i3           | 32       | 11.07%  |
| Intel Core i7           | 20       | 6.92%   |
| Intel Xeon              | 19       | 6.57%   |
| AMD GX                  | 18       | 6.23%   |
| Other                   | 13       | 4.5%    |
| AMD Ryzen 5             | 13       | 4.5%    |
| Intel Atom              | 10       | 3.46%   |
| Intel Pentium Silver    | 9        | 3.11%   |
| Intel Core 2 Duo        | 6        | 2.08%   |
| AMD Ryzen 7             | 5        | 1.73%   |
| Intel Core i9           | 3        | 1.04%   |
| ARM Cortex              | 3        | 1.04%   |
| AMD Ryzen 3             | 3        | 1.04%   |
| AMD G                   | 3        | 1.04%   |
| AMD FX                  | 3        | 1.04%   |
| AMD Athlon              | 3        | 1.04%   |
| Intel Pentium           | 2        | 0.69%   |
| Intel Core 2 Quad       | 2        | 0.69%   |
| AMD Ryzen Threadripper  | 2        | 0.69%   |
| AMD Ryzen 9             | 2        | 0.69%   |
| AMD E2                  | 2        | 0.69%   |
| AMD A6                  | 2        | 0.69%   |
| AMD A4                  | 2        | 0.69%   |
| Intel Pentium Dual-Core | 1        | 0.35%   |
| Intel 686-class         | 1        | 0.35%   |
| AMD Ryzen 7 PRO         | 1        | 0.35%   |
| AMD Ryzen 5 PRO         | 1        | 0.35%   |
| AMD Phenom II X6        | 1        | 0.35%   |
| AMD Phenom              | 1        | 0.35%   |
| AMD Opteron             | 1        | 0.35%   |
| AMD EPYC                | 1        | 0.35%   |
| AMD Athlon II X2        | 1        | 0.35%   |
| AMD A8                  | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 150      | 51.55%  |
| 2       | 83       | 28.52%  |
| 6       | 13       | 4.47%   |
| 8       | 11       | 3.78%   |
| 12      | 10       | 3.44%   |
| Unknown | 9        | 3.09%   |
| 16      | 8        | 2.75%   |
| 24      | 3        | 1.03%   |
| 10      | 2        | 0.69%   |
| 64      | 1        | 0.34%   |
| 32      | 1        | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 277      | 96.85%  |
| Unknown | 6        | 2.1%    |
| 2       | 3        | 1.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 191      | 66.32%  |
| 2       | 88       | 30.56%  |
| Unknown | 9        | 3.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 38       | 13.24%  |
| Unknown       | 32       | 11.15%  |
| KabyLake      | 29       | 10.1%   |
| Silvermont    | 24       | 8.36%   |
| IvyBridge     | 17       | 5.92%   |
| Goldmont plus | 16       | 5.57%   |
| SandyBridge   | 12       | 4.18%   |
| Jaguar        | 12       | 4.18%   |
| Zen 2         | 11       | 3.83%   |
| Puma          | 10       | 3.48%   |
| Penryn        | 10       | 3.48%   |
| Goldmont      | 10       | 3.48%   |
| Skylake       | 9        | 3.14%   |
| Zen 3         | 8        | 2.79%   |
| Broadwell     | 7        | 2.44%   |
| Zen+          | 5        | 1.74%   |
| Zen           | 5        | 1.74%   |
| Piledriver    | 5        | 1.74%   |
| Nehalem       | 5        | 1.74%   |
| Bobcat        | 4        | 1.39%   |
| TigerLake     | 3        | 1.05%   |
| K10           | 3        | 1.05%   |
| Bonnell       | 3        | 1.05%   |
| Westmere      | 2        | 0.7%    |
| Excavator     | 2        | 0.7%    |
| Core          | 2        | 0.7%    |
| CometLake     | 2        | 0.7%    |
| Bulldozer     | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 180      | 65.93%  |
| AMD                              | 46       | 16.85%  |
| Nvidia                           | 35       | 12.82%  |
| ASPEED Technology                | 6        | 2.2%    |
| Matrox Electronics Systems       | 5        | 1.83%   |
| Silicon Integrated Systems [SiS] | 1        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20       | 7.22%   |
| Intel JasperLake [UHD Graphics]                                                          | 15       | 5.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 15       | 5.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14       | 5.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 3.61%   |
| Intel HD Graphics 500                                                                    | 9        | 3.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 3.25%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8        | 2.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7        | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6        | 2.17%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6        | 2.17%   |
| Intel HD Graphics 620                                                                    | 5        | 1.81%   |
| Intel HD Graphics 610                                                                    | 5        | 1.81%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 5        | 1.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5        | 1.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4        | 1.44%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 4        | 1.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4        | 1.44%   |
| Intel HD Graphics 6000                                                                   | 4        | 1.44%   |
| Intel HD Graphics 530                                                                    | 4        | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4        | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3        | 1.08%   |
| Intel HD Graphics 5500                                                                   | 3        | 1.08%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 3        | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3        | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3        | 1.08%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 3        | 1.08%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2        | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 2        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2        | 0.72%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2        | 0.72%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2        | 0.72%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2        | 0.72%   |
| Intel UHD Graphics 620                                                                   | 2        | 0.72%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 2        | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2        | 0.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2        | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 177      | 61.67%  |
| 1 x AMD     | 43       | 14.98%  |
| 1 x Nvidia  | 34       | 11.85%  |
| Other       | 18       | 6.27%   |
| 1 x ASPEED  | 6        | 2.09%   |
| 1 x Matrox  | 5        | 1.74%   |
| Intel + AMD | 2        | 0.7%    |
| 2 x Intel   | 1        | 0.35%   |
| 1 x SiS     | 1        | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 247      | 86.06%  |
| Unknown     | 23       | 8.01%   |
| Proprietary | 17       | 5.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 261      | 90.63%  |
| 3.01-4.0   | 6        | 2.08%   |
| 0.51-1.0   | 6        | 2.08%   |
| 1.01-2.0   | 5        | 1.74%   |
| 7.01-8.0   | 4        | 1.39%   |
| 5.01-6.0   | 2        | 0.69%   |
| 8.01-16.0  | 2        | 0.69%   |
| 0.01-0.5   | 2        | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Dell                | 8        | 17.39%  |
| Samsung Electronics | 7        | 15.22%  |
| BenQ                | 6        | 13.04%  |
| AOC                 | 5        | 10.87%  |
| Hewlett-Packard     | 4        | 8.7%    |
| Iiyama              | 3        | 6.52%   |
| Acer                | 3        | 6.52%   |
| Lenovo              | 2        | 4.35%   |
| unknown             | 1        | 2.17%   |
| RS                  | 1        | 2.17%   |
| Pixio               | 1        | 2.17%   |
| OEM                 | 1        | 2.17%   |
| Goldstar            | 1        | 2.17%   |
| CVT                 | 1        | 2.17%   |
| AVX                 | 1        | 2.17%   |
| Unknown             | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| BenQ GL2450 BNQ78A4 1920x1080 530x300mm 24.0-inch                    | 3        | 6%      |
| Hewlett-Packard ZR24w HWP286A 1920x1200 540x350mm 25.3-inch          | 2        | 4%      |
| unknown LCD Monitor SAMSUNG 1920x1080                                | 1        | 2%      |
| Samsung Electronics U28D590 SAM0B80 3840x2160 610x350mm 27.7-inch    | 1        | 2%      |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch    | 1        | 2%      |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch | 1        | 2%      |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch | 1        | 2%      |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch    | 1        | 2%      |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 1        | 2%      |
| Samsung Electronics S24C550 SAM0A4B 1920x1080 520x290mm 23.4-inch    | 1        | 2%      |
| RS LE2262 BTC2262 1680x1050 470x290mm 21.7-inch                      | 1        | 2%      |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                    | 1        | 2%      |
| OEM 32W_LCD_TV OEM3700 1920x540                                      | 1        | 2%      |
| Lenovo LCD Monitor LEN0990 1440x900 410x260mm 19.1-inch              | 1        | 2%      |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                 | 1        | 2%      |
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                | 1        | 2%      |
| Iiyama PL2390 IVM562D 1920x1080 510x290mm 23.1-inch                  | 1        | 2%      |
| Iiyama PL2283H IVM562E 1920x1080 500x290mm 22.8-inch                 | 1        | 2%      |
| Iiyama PL2273HD IVM561A 1920x1080 480x270mm 21.7-inch                | 1        | 2%      |
| Hewlett-Packard w1907 HWP26A2 1440x900 410x260mm 19.1-inch           | 1        | 2%      |
| Hewlett-Packard 2310e HWP2909 1920x1080 510x290mm 23.1-inch          | 1        | 2%      |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 1        | 2%      |
| Dell U4919DW DELA107 3840x1080 1200x340mm 49.1-inch                  | 1        | 2%      |
| Dell U3415W DELA0A6 3440x1440 800x330mm 34.1-inch                    | 1        | 2%      |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 1        | 2%      |
| Dell LCD Monitor S2740L 1920x1080                                    | 1        | 2%      |
| Dell LCD Monitor P2214H 1920x1080                                    | 1        | 2%      |
| Dell LCD Monitor DELD110 2560x1440 700x400mm 31.7-inch               | 1        | 2%      |
| Dell LCD Monitor 1908FP 3200x1080                                    | 1        | 2%      |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                    | 1        | 2%      |
| CVT LCD Monitor CVT4668 1440x900 360x290mm 18.2-inch                 | 1        | 2%      |
| BenQ LCD Monitor GW2780 1920x1080                                    | 1        | 2%      |
| BenQ LCD Monitor DL2215                                              | 1        | 2%      |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                    | 1        | 2%      |
| BenQ GW2475H BNQ78EE 1920x1080 530x300mm 24.0-inch                   | 1        | 2%      |
| AVX AVERMEDIA_HD AVX0003 1920x1080 380x300mm 19.1-inch               | 1        | 2%      |
| AOC N22W AOC220A 1680x1050 470x300mm 22.0-inch                       | 1        | 2%      |
| AOC LCD Monitor 2460X 5760x1200                                      | 1        | 2%      |
| AOC LCD Monitor 2460X                                                | 1        | 2%      |
| AOC G2460 AOC2460 1920x1080 530x300mm 24.0-inch                      | 1        | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 51.06%  |
| 3840x2160 (4K)     | 3        | 6.38%   |
| 1920x1200 (WUXGA)  | 3        | 6.38%   |
| 1680x1050 (WSXGA+) | 3        | 6.38%   |
| 1440x900 (WXGA+)   | 3        | 6.38%   |
| 1280x1024 (SXGA)   | 2        | 4.26%   |
| Unknown            | 2        | 4.26%   |
| 5760x1200          | 1        | 2.13%   |
| 3840x1080          | 1        | 2.13%   |
| 3440x1440          | 1        | 2.13%   |
| 3200x1080          | 1        | 2.13%   |
| 2560x1440 (QHD)    | 1        | 2.13%   |
| 1920x540           | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 8        | 17.02%  |
| Unknown | 8        | 17.02%  |
| 23      | 6        | 12.77%  |
| 19      | 6        | 12.77%  |
| 27      | 5        | 10.64%  |
| 21      | 4        | 8.51%   |
| 22      | 3        | 6.38%   |
| 25      | 2        | 4.26%   |
| 49      | 1        | 2.13%   |
| 39      | 1        | 2.13%   |
| 34      | 1        | 2.13%   |
| 31      | 1        | 2.13%   |
| 18      | 1        | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 44.44%  |
| 401-500     | 8        | 17.78%  |
| Unknown     | 8        | 17.78%  |
| 351-400     | 4        | 8.89%   |
| 601-700     | 2        | 4.44%   |
| 801-900     | 1        | 2.22%   |
| 701-800     | 1        | 2.22%   |
| 1001-1500   | 1        | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 24       | 52.17%  |
| Unknown | 7        | 15.22%  |
| 16/10   | 6        | 13.04%  |
| 5/4     | 3        | 6.52%   |
| 32/9    | 2        | 4.35%   |
| 3/2     | 2        | 4.35%   |
| 6/5     | 1        | 2.17%   |
| 21/9    | 1        | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 17       | 38.64%  |
| Unknown        | 8        | 18.18%  |
| 151-200        | 7        | 15.91%  |
| 301-350        | 5        | 11.36%  |
| 251-300        | 3        | 6.82%   |
| 351-500        | 2        | 4.55%   |
| 501-1000       | 2        | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 30       | 65.22%  |
| Unknown | 8        | 17.39%  |
| 101-120 | 6        | 13.04%  |
| 161-240 | 1        | 2.17%   |
| 121-160 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 240      | 83.62%  |
| 1     | 41       | 14.29%  |
| 2     | 5        | 1.74%   |
| 3     | 1        | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Intel                             | 218      | 58.92%  |
| Realtek Semiconductor             | 98       | 26.49%  |
| Qualcomm Atheros                  | 14       | 3.78%   |
| Broadcom                          | 13       | 3.51%   |
| Mellanox Technologies             | 5        | 1.35%   |
| Ralink Technology                 | 4        | 1.08%   |
| Ralink                            | 2        | 0.54%   |
| Nvidia                            | 2        | 0.54%   |
| Marvell Technology Group          | 2        | 0.54%   |
| IMC Networks                      | 2        | 0.54%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.27%   |
| U-Blox                            | 1        | 0.27%   |
| MYRICOM                           | 1        | 0.27%   |
| Microsoft                         | 1        | 0.27%   |
| MediaTek                          | 1        | 0.27%   |
| Ericsson Business Mobile Networks | 1        | 0.27%   |
| Bluegiga Technologies             | 1        | 0.27%   |
| ASUSTek Computer                  | 1        | 0.27%   |
| Aquantia                          | 1        | 0.27%   |
| American Megatrends               | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88       | 19.43%  |
| Intel I211 Gigabit Network Connection                                         | 49       | 10.82%  |
| Intel I210 Gigabit Network Connection                                         | 23       | 5.08%   |
| Intel Ethernet Controller I226-V                                              | 19       | 4.19%   |
| Intel Ethernet Controller I225-V                                              | 17       | 3.75%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 16       | 3.53%   |
| Intel 82574L Gigabit Network Connection                                       | 15       | 3.31%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 2.87%   |
| Realtek RTL8125 2.5GbE Controller                                             | 11       | 2.43%   |
| Intel Ethernet Connection I217-LM                                             | 10       | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 2.21%   |
| Intel 82580 Gigabit Network Connection                                        | 9        | 1.99%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9        | 1.99%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 1.55%   |
| Intel 82583V Gigabit Network Connection                                       | 6        | 1.32%   |
| Intel Wireless 7260                                                           | 5        | 1.1%    |
| Intel Wi-Fi 6 AX200                                                           | 5        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.1%    |
| Mellanox MT27500 Family [ConnectX-3]                                          | 4        | 0.88%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 3        | 0.66%   |
| Intel Wireless-AC 9260                                                        | 3        | 0.66%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 3        | 0.66%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3        | 0.66%   |
| Intel Ethernet Controller X550                                                | 3        | 0.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.66%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3        | 0.66%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 0.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2        | 0.44%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 2        | 0.44%   |
| Intel Wireless 3160                                                           | 2        | 0.44%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 31       | 53.45%  |
| Qualcomm Atheros      | 12       | 20.69%  |
| Realtek Semiconductor | 4        | 6.9%    |
| Ralink Technology     | 4        | 6.9%    |
| Ralink                | 2        | 3.45%   |
| IMC Networks          | 2        | 3.45%   |
| MediaTek              | 1        | 1.72%   |
| Broadcom              | 1        | 1.72%   |
| ASUSTek Computer      | 1        | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wireless 7260                                                    | 5        | 8.62%   |
| Intel Wi-Fi 6 AX200                                                    | 5        | 8.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3        | 5.17%   |
| Intel Wireless-AC 9260                                                 | 3        | 5.17%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 3        | 5.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2        | 3.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 3.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 3.45%   |
| Intel Wireless 3160                                                    | 2        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 3.45%   |
| Intel Centrino Advanced-N 6235                                         | 2        | 3.45%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                   | 2        | 3.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.72%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 1.72%   |
| Ralink RT3072 Wireless Adapter                                         | 1        | 1.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1        | 1.72%   |
| Ralink MT7601U Wireless Adapter                                        | 1        | 1.72%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.72%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 1.72%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.72%   |
| Intel Wireless 7265                                                    | 1        | 1.72%   |
| Intel Wireless 3165                                                    | 1        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 1.72%   |
| Intel CNVi: Wi-Fi                                                      | 1        | 1.72%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 1.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 1        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1        | 1.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 1.72%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]              | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 215      | 64.95%  |
| Realtek Semiconductor    | 94       | 28.4%   |
| Broadcom                 | 12       | 3.63%   |
| Qualcomm Atheros         | 2        | 0.6%    |
| Nvidia                   | 2        | 0.6%    |
| Marvell Technology Group | 2        | 0.6%    |
| MYRICOM                  | 1        | 0.3%    |
| Microsoft                | 1        | 0.3%    |
| Aquantia                 | 1        | 0.3%    |
| American Megatrends      | 1        | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 88       | 23.04%  |
| Intel I211 Gigabit Network Connection                                         | 49       | 12.83%  |
| Intel I210 Gigabit Network Connection                                         | 23       | 6.02%   |
| Intel Ethernet Controller I226-V                                              | 19       | 4.97%   |
| Intel Ethernet Controller I225-V                                              | 17       | 4.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 16       | 4.19%   |
| Intel 82574L Gigabit Network Connection                                       | 15       | 3.93%   |
| Intel I350 Gigabit Network Connection                                         | 13       | 3.4%    |
| Realtek RTL8125 2.5GbE Controller                                             | 11       | 2.88%   |
| Intel Ethernet Connection I217-LM                                             | 10       | 2.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10       | 2.62%   |
| Intel 82580 Gigabit Network Connection                                        | 9        | 2.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 9        | 2.36%   |
| Intel 82576 Gigabit Network Connection                                        | 7        | 1.83%   |
| Intel 82583V Gigabit Network Connection                                       | 6        | 1.57%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 1.31%   |
| Intel 82579V Gigabit Network Connection                                       | 5        | 1.31%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 4        | 1.05%   |
| Intel NM10/ICH7 Family LAN Controller                                         | 3        | 0.79%   |
| Intel Ethernet Controller X550                                                | 3        | 0.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3        | 0.79%   |
| Intel 82575EB Gigabit Network Connection                                      | 3        | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 3        | 0.79%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 3        | 0.79%   |
| Intel Ethernet Connection I217-V                                              | 2        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 2        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                         | 2        | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 1        | 0.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.26%   |
| Nvidia MCP77 Ethernet                                                         | 1        | 0.26%   |
| Nvidia MCP73 Ethernet                                                         | 1        | 0.26%   |
| MYRICOM Myri-10G Dual-Protocol NIC                                            | 1        | 0.26%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                            | 1        | 0.26%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 1        | 0.26%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.26%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.26%   |
| Intel I350 Gigabit Fiber Network Connection                                   | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 280      | 80.23%  |
| WiFi     | 56       | 16.05%  |
| Unknown  | 9        | 2.58%   |
| Modem    | 4        | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 274      | 95.8%   |
| WiFi     | 12       | 4.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 57       | 19.72%  |
| 2     | 57       | 19.72%  |
| 1     | 46       | 15.92%  |
| 3     | 41       | 14.19%  |
| 5     | 37       | 12.8%   |
| 6     | 29       | 10.03%  |
| 7     | 8        | 2.77%   |
| 0     | 5        | 1.73%   |
| 8     | 3        | 1.04%   |
| 10    | 2        | 0.69%   |
| 15    | 1        | 0.35%   |
| 14    | 1        | 0.35%   |
| 12    | 1        | 0.35%   |
| 9     | 1        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 261      | 88.47%  |
| Yes  | 34       | 11.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 25       | 62.5%   |
| Cambridge Silicon Radio | 5        | 12.5%   |
| Realtek Semiconductor   | 2        | 5%      |
| IMC Networks            | 2        | 5%      |
| ASUSTek Computer        | 2        | 5%      |
| MediaTek                | 1        | 2.5%    |
| Lite-On Technology      | 1        | 2.5%    |
| Foxconn / Hon Hai       | 1        | 2.5%    |
| Broadcom                | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                      | 5        | 12.5%   |
| Intel AX200 Bluetooth                                   | 5        | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 5        | 12.5%   |
| Intel AX201 Bluetooth                                   | 4        | 10%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 3        | 7.5%    |
| Intel Centrino Bluetooth Wireless Transceiver           | 3        | 7.5%    |
| Intel Wireless-AC 3168 Bluetooth                        | 2        | 5%      |
| Realtek Bluetooth Adapter                               | 1        | 2.5%    |
| Realtek Bluetooth 5.1 Adapter                           | 1        | 2.5%    |
| MediaTek RZ608 Bluetooth Adapter                        | 1        | 2.5%    |
| Lite-On Bluetooth USB Module                            | 1        | 2.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1        | 2.5%    |
| Intel AX211 Bluetooth                                   | 1        | 2.5%    |
| Intel AX210 Bluetooth                                   | 1        | 2.5%    |
| IMC Networks Realtek Bluetooth Adapter                  | 1        | 2.5%    |
| IMC Networks Realtek Bluetooth 4.0 Adapter              | 1        | 2.5%    |
| Foxconn / Hon Hai Bluetooth USB Module                  | 1        | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 1        | 2.5%    |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter | 1        | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                      | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 174      | 61.7%   |
| AMD                                  | 59       | 20.92%  |
| Nvidia                               | 32       | 11.35%  |
| C-Media Electronics                  | 4        | 1.42%   |
| Texas Instruments                    | 2        | 0.71%   |
| Creative Labs                        | 2        | 0.71%   |
| Trust International                  | 1        | 0.35%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.35%   |
| Silicon Integrated Systems [SiS]     | 1        | 0.35%   |
| Nam Tai E&E Products                 | 1        | 0.35%   |
| Logitech                             | 1        | 0.35%   |
| Griffin Technology                   | 1        | 0.35%   |
| Elgato Systems                       | 1        | 0.35%   |
| BEHRINGER International              | 1        | 0.35%   |
| Unknown                              | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26       | 7.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17       | 4.89%   |
| Intel Jasper Lake HD Audio                                                                        | 15       | 4.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15       | 4.31%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14       | 4.02%   |
| AMD FCH Azalia Controller                                                                         | 13       | 3.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12       | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12       | 3.45%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9        | 2.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9        | 2.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8        | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8        | 2.3%    |
| Intel Broadwell-U Audio Controller                                                                | 7        | 2.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7        | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7        | 2.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6        | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 6        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6        | 1.72%   |
| Nvidia High Definition Audio Controller                                                           | 5        | 1.44%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 5        | 1.44%   |
| Intel 200 Series PCH HD Audio                                                                     | 5        | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5        | 1.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4        | 1.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4        | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4        | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 0.86%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 3        | 0.86%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3        | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 3        | 0.86%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3        | 0.86%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 2        | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 42       | 14.24%  |
| SK hynix            | 36       | 12.2%   |
| Samsung Electronics | 36       | 12.2%   |
| Kingston            | 33       | 11.19%  |
| Corsair             | 33       | 11.19%  |
| Unknown             | 25       | 8.47%   |
| Micron Technology   | 25       | 8.47%   |
| Unknown             | 10       | 3.39%   |
| Unknown (ABCD)      | 9        | 3.05%   |
| Transcend           | 7        | 2.37%   |
| Ramaxel Technology  | 6        | 2.03%   |
| A-DATA Technology   | 6        | 2.03%   |
| Team                | 5        | 1.69%   |
| Nanya Technology    | 4        | 1.36%   |
| TIMETEC             | 3        | 1.02%   |
| Unknown (AB)        | 2        | 0.68%   |
| G.Skill             | 2        | 0.68%   |
| Essencore Limited   | 2        | 0.68%   |
| Teikon              | 1        | 0.34%   |
| Smart Modular       | 1        | 0.34%   |
| Kimtigo             | 1        | 0.34%   |
| HPE                 | 1        | 0.34%   |
| Hewlett-Packard     | 1        | 0.34%   |
| Heoriady            | 1        | 0.34%   |
| CSX                 | 1        | 0.34%   |
| Avant               | 1        | 0.34%   |
| A-DA                | 1        | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Unknown                                                          | 10       | 3.16%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 9        | 2.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4        | 1.27%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 4        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 3        | 0.95%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 3        | 0.95%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 3        | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3        | 0.95%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3        | 0.95%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s               | 3        | 0.95%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 3        | 0.95%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3        | 0.95%   |
| Kingston RAM 99U5469-045.A00LF 4GB DIMM DDR3 1600MT/s            | 3        | 0.95%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3        | 0.95%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s            | 3        | 0.95%   |
| Corsair RAM CMX8GX3M2A1333C9 4GB DIMM DDR3 1333MT/s              | 3        | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                       | 2        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2        | 0.63%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2        | 0.63%   |
| Transcend RAM TS1GLK72V6H 8GB DIMM DDR3 1600MT/s                 | 2        | 0.63%   |
| Transcend RAM TS1GLH64V1H 8GB DIMM DDR4 2133MT/s                 | 2        | 0.63%   |
| Timetec RAM UD3-1600 8GB DIMM DDR3 1600MT/s                      | 2        | 0.63%   |
| SK hynix RAM HMT451U7BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.63%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.63%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2        | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2        | 0.63%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2        | 0.63%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s              | 2        | 0.63%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 2        | 0.63%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                     | 2        | 0.63%   |
| Kingston RAM LV26D4U9S8HJ-8 8GB DIMM DDR4 2667MT/s               | 2        | 0.63%   |
| Kingston RAM 9905584-016.A00LF 4GB DIMM DDR3 1600MT/s            | 2        | 0.63%   |
| Essencore Limited RAM KD48GS880-32N2200 8GB SODIMM DDR4 3200MT/s | 2        | 0.63%   |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2666MT/s           | 2        | 0.63%   |
| Crucial RAM CT4G4DFS8213.C8FBR2 4GB DIMM DDR4 2133MT/s           | 2        | 0.63%   |
| Crucial RAM CT16G4SFRA32A.C16FP 16GB SODIMM DDR4 3200MT/s        | 2        | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 132      | 50.19%  |
| DDR4    | 98       | 37.26%  |
| LPDDR4  | 12       | 4.56%   |
| DDR2    | 8        | 3.04%   |
| DDR5    | 5        | 1.9%    |
| SDRAM   | 4        | 1.52%   |
| Unknown | 2        | 0.76%   |
| LPDDR3  | 1        | 0.38%   |
| DDR     | 1        | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 164      | 62.84%  |
| SODIMM       | 93       | 35.63%  |
| Row Of Chips | 3        | 1.15%   |
| Unknown      | 1        | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 114      | 41.76%  |
| 4096  | 87       | 31.87%  |
| 16384 | 31       | 11.36%  |
| 2048  | 26       | 9.52%   |
| 32768 | 10       | 3.66%   |
| 1024  | 5        | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 92       | 33.09%  |
| 3200    | 32       | 11.51%  |
| 2400    | 32       | 11.51%  |
| 1333    | 30       | 10.79%  |
| 2667    | 24       | 8.63%   |
| 2133    | 12       | 4.32%   |
| 800     | 12       | 4.32%   |
| 2666    | 6        | 2.16%   |
| 1867    | 6        | 2.16%   |
| 667     | 6        | 2.16%   |
| 4800    | 5        | 1.8%    |
| 3600    | 4        | 1.44%   |
| Unknown | 3        | 1.08%   |
| 1866    | 2        | 0.72%   |
| 1334    | 2        | 0.72%   |
| 1066    | 2        | 0.72%   |
| 65535   | 1        | 0.36%   |
| 3534    | 1        | 0.36%   |
| 3000    | 1        | 0.36%   |
| 2933    | 1        | 0.36%   |
| 1067    | 1        | 0.36%   |
| 933     | 1        | 0.36%   |
| 533     | 1        | 0.36%   |
| 133     | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 1200 | 1        | 50%     |
| HP DeskJet 5850c | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 220 | 1        | 50%     |
| Canon CanoScan LiDE 210 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 7        | 63.64%  |
| Trust                    | 1        | 9.09%   |
| SHENZHEN AONI ELECTRONIC | 1        | 9.09%   |
| Chicony Electronics      | 1        | 9.09%   |
| ARC International        | 1        | 9.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                    | 3        | 27.27%  |
| Logitech Labtec Webcam Pro                     | 2        | 18.18%  |
| Trust Canyon CNS-CWC6 Webcam                   | 1        | 9.09%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera | 1        | 9.09%   |
| Logitech Webcam C930e                          | 1        | 9.09%   |
| Logitech Webcam C310                           | 1        | 9.09%   |
| Chicony Integrated Camera [ThinkPad]           | 1        | 9.09%   |
| ARC International Camera                       | 1        | 9.09%   |

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
| 1     | 150      | 51.37%  |
| 0     | 100      | 34.25%  |
| 2     | 26       | 8.9%    |
| 3     | 12       | 4.11%   |
| 4     | 2        | 0.68%   |
| 9     | 1        | 0.34%   |
| 8     | 1        | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 168      | 75%     |
| Bluetooth                | 16       | 7.14%   |
| Net/wireless             | 13       | 5.8%    |
| Sound                    | 6        | 2.68%   |
| Card reader              | 6        | 2.68%   |
| Network                  | 5        | 2.23%   |
| Firewire controller      | 5        | 2.23%   |
| Net/ethernet             | 2        | 0.89%   |
| Graphics card            | 2        | 0.89%   |
| Storage/raid             | 1        | 0.45%   |

