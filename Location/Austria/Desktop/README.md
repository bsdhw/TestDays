BSD in Austria - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

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

Total: 115

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e68d7a5dff](https://bsd-hardware.info/?probe=e68d7a5dff) | Jun 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | [f68b48b102](https://bsd-hardware.info/?probe=f68b48b102) | Jun 28, 2022 |
| PC Engines    | APU2                        | [b296296b84](https://bsd-hardware.info/?probe=b296296b84) | Jun 10, 2022 |
| MSI           | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Dell          | 055H3G A01                  | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Shuttle       | DS10U                       | [573358361a](https://bsd-hardware.info/?probe=573358361a) | May 22, 2022 |
| Protectli     | FW4B Ver                    | [02f79b14cb](https://bsd-hardware.info/?probe=02f79b14cb) | May 20, 2022 |
| PC Engines    | APU2                        | [7132ae8216](https://bsd-hardware.info/?probe=7132ae8216) | May 19, 2022 |
| Dell          | 0T7D40 A01                  | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | 0T7D40 A01                  | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| PC Engines    | apu4                        | [beb62ed999](https://bsd-hardware.info/?probe=beb62ed999) | Apr 07, 2022 |
| Unknown       | Unknown                     | [4d52408404](https://bsd-hardware.info/?probe=4d52408404) | Apr 04, 2022 |
| Dell          | 096JG8 A01                  | [7ee68eb371](https://bsd-hardware.info/?probe=7ee68eb371) | Apr 02, 2022 |
| Dell          | 096JG8 A01                  | [657c893958](https://bsd-hardware.info/?probe=657c893958) | Apr 02, 2022 |
| PC Engines    | APU2                        | [5aef21bfc3](https://bsd-hardware.info/?probe=5aef21bfc3) | Mar 26, 2022 |
| Secudos       | Unknown                     | [970e9962ff](https://bsd-hardware.info/?probe=970e9962ff) | Mar 24, 2022 |
| PC Engines    | apu4                        | [395eb04c69](https://bsd-hardware.info/?probe=395eb04c69) | Mar 14, 2022 |
| PC Engines    | APU2                        | [c5ed9017c3](https://bsd-hardware.info/?probe=c5ed9017c3) | Mar 05, 2022 |
| Shuttle       | DS10U                       | [1300217458](https://bsd-hardware.info/?probe=1300217458) | Feb 28, 2022 |
| HP            | 805D                        | [4c07559a11](https://bsd-hardware.info/?probe=4c07559a11) | Feb 28, 2022 |
| PC Engines    | apu4                        | [606d9c838c](https://bsd-hardware.info/?probe=606d9c838c) | Feb 26, 2022 |
| PC Engines    | apu4                        | [8b42751f17](https://bsd-hardware.info/?probe=8b42751f17) | Feb 25, 2022 |
| Unknown       | Unknown                     | [96bae6432b](https://bsd-hardware.info/?probe=96bae6432b) | Feb 24, 2022 |
| Shuttle       | FH170                       | [5fd212645c](https://bsd-hardware.info/?probe=5fd212645c) | Feb 18, 2022 |
| Dell          | 096JG8 A01                  | [6baeaf5d48](https://bsd-hardware.info/?probe=6baeaf5d48) | Feb 17, 2022 |
| Unknown       | Unknown                     | [f172be6fb0](https://bsd-hardware.info/?probe=f172be6fb0) | Feb 17, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | [f1dd03cdcb](https://bsd-hardware.info/?probe=f1dd03cdcb) | Feb 16, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [0117d61d81](https://bsd-hardware.info/?probe=0117d61d81) | Feb 07, 2022 |
| Dell          | 0NKW6Y A00                  | [1ea6d60d70](https://bsd-hardware.info/?probe=1ea6d60d70) | Jan 30, 2022 |
| HP            | 805D                        | [d7e312307f](https://bsd-hardware.info/?probe=d7e312307f) | Jan 30, 2022 |
| Unknown       | YL-J3160L4                  | [763dc53716](https://bsd-hardware.info/?probe=763dc53716) | Jan 28, 2022 |
| Lenovo        | 0B98401 WIN                 | [c5430f00cf](https://bsd-hardware.info/?probe=c5430f00cf) | Jan 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d2d10a1ffc](https://bsd-hardware.info/?probe=d2d10a1ffc) | Jan 21, 2022 |
| Biostar       | N3050NH                     | [31e33326fa](https://bsd-hardware.info/?probe=31e33326fa) | Jan 06, 2022 |
| Gigabyte      | B150-HD3P-CF                | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [765210be77](https://bsd-hardware.info/?probe=765210be77) | Dec 28, 2021 |
| Purism        | Librem Mini v2              | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| HP            | 805D                        | [324b4670b6](https://bsd-hardware.info/?probe=324b4670b6) | Dec 12, 2021 |
| Unknown       | Unknown                     | [943365b2f1](https://bsd-hardware.info/?probe=943365b2f1) | Dec 11, 2021 |
| BESSTAR Te... | IB9                         | [26717d3708](https://bsd-hardware.info/?probe=26717d3708) | Dec 10, 2021 |
| HP            | 3397                        | [ac295c89b0](https://bsd-hardware.info/?probe=ac295c89b0) | Dec 05, 2021 |
| Protectli     | FW6E                        | [3ddd9d297c](https://bsd-hardware.info/?probe=3ddd9d297c) | Dec 02, 2021 |
| Gigabyte      | B365M DS3H                  | [69194e4ead](https://bsd-hardware.info/?probe=69194e4ead) | Nov 23, 2021 |
| PC Engines    | APU2                        | [9a262221d5](https://bsd-hardware.info/?probe=9a262221d5) | Nov 03, 2021 |
| Winston Ma... | PICO PC  PICOPC             | [55a9e67b4c](https://bsd-hardware.info/?probe=55a9e67b4c) | Oct 26, 2021 |
| BESSTAR Te... | UM270 V1.0                  | [aa7ee48846](https://bsd-hardware.info/?probe=aa7ee48846) | Oct 19, 2021 |
| PC Engines    | APU2                        | [6580ee2c23](https://bsd-hardware.info/?probe=6580ee2c23) | Oct 19, 2021 |
| HP            | 805D                        | [b61f6f9d52](https://bsd-hardware.info/?probe=b61f6f9d52) | Oct 16, 2021 |
| ASRock        | B460M Pro4                  | [e0fbe78c7e](https://bsd-hardware.info/?probe=e0fbe78c7e) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | [39c65baf01](https://bsd-hardware.info/?probe=39c65baf01) | Oct 14, 2021 |
| Silicom       | MinnowBoard Turbot          | [0c6c98cbd3](https://bsd-hardware.info/?probe=0c6c98cbd3) | Oct 09, 2021 |
| ASUSTek       | P11C-I Series               | [2690a544a5](https://bsd-hardware.info/?probe=2690a544a5) | Sep 29, 2021 |
| Shuttle       | DS10U                       | [6f5d8afb4b](https://bsd-hardware.info/?probe=6f5d8afb4b) | Sep 29, 2021 |
| Unknown       | YL-J3160L4                  | [ad178dbed0](https://bsd-hardware.info/?probe=ad178dbed0) | Sep 13, 2021 |
| Intel         | Q3XXG4-P V1.0               | [d6fb115604](https://bsd-hardware.info/?probe=d6fb115604) | Aug 21, 2021 |
| Shuttle       | DS10U                       | [7e11cc28f5](https://bsd-hardware.info/?probe=7e11cc28f5) | Aug 19, 2021 |
| HP            | 1495                        | [d7e136e07f](https://bsd-hardware.info/?probe=d7e136e07f) | Aug 11, 2021 |
| PC Engines    | apu4                        | [f6d199de58](https://bsd-hardware.info/?probe=f6d199de58) | Aug 08, 2021 |
| HP            | 1495                        | [4dfe9896c4](https://bsd-hardware.info/?probe=4dfe9896c4) | Aug 04, 2021 |
| Silicom       | MinnowBoard Turbot          | [6defda405f](https://bsd-hardware.info/?probe=6defda405f) | Aug 02, 2021 |
| Shuttle       | FH170                       | [0c381808eb](https://bsd-hardware.info/?probe=0c381808eb) | Aug 02, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | [eb75d5e2a3](https://bsd-hardware.info/?probe=eb75d5e2a3) | Jul 29, 2021 |
| Unknown       | YL-J3160L4                  | [1d117c1c21](https://bsd-hardware.info/?probe=1d117c1c21) | Jul 28, 2021 |
| NEXCOM        | NSA3110 B                   | [4f532bbd9e](https://bsd-hardware.info/?probe=4f532bbd9e) | Jul 25, 2021 |
| Intel         | Q3XXG4-P V1.0               | [c1c721ac0b](https://bsd-hardware.info/?probe=c1c721ac0b) | Jul 16, 2021 |
| Shuttle       | DS10U                       | [746d0761cc](https://bsd-hardware.info/?probe=746d0761cc) | Jul 16, 2021 |
| Dell          | 0T7D40 A01                  | [f67d589e29](https://bsd-hardware.info/?probe=f67d589e29) | Jul 08, 2021 |
| Dell          | 0T7D40 A01                  | [d39de0c0dc](https://bsd-hardware.info/?probe=d39de0c0dc) | Jun 30, 2021 |
| BESSTAR Te... | IB9                         | [1c8c267ce2](https://bsd-hardware.info/?probe=1c8c267ce2) | Jun 20, 2021 |
| HP            | 1495                        | [572b748256](https://bsd-hardware.info/?probe=572b748256) | Jun 10, 2021 |
| BESSTAR Te... | IB9                         | [f152e4b3e7](https://bsd-hardware.info/?probe=f152e4b3e7) | Jun 10, 2021 |
| HP            | 3397                        | [ab3fc66a9e](https://bsd-hardware.info/?probe=ab3fc66a9e) | May 20, 2021 |
| HP            | 1495                        | [3d2d524163](https://bsd-hardware.info/?probe=3d2d524163) | May 19, 2021 |
| HP            | 3397                        | [5d2d602907](https://bsd-hardware.info/?probe=5d2d602907) | May 19, 2021 |
| Protectli     | FW4B                        | [1a8296fffd](https://bsd-hardware.info/?probe=1a8296fffd) | May 15, 2021 |
| Protectli     | FW4B                        | [47aa4d946c](https://bsd-hardware.info/?probe=47aa4d946c) | May 14, 2021 |
| Gigabyte      | B365M DS3H                  | [b77ceeed88](https://bsd-hardware.info/?probe=b77ceeed88) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| Unknown       | Unknown                     | [2d8cb88aa7](https://bsd-hardware.info/?probe=2d8cb88aa7) | May 03, 2021 |
| Unknown       | SKYBAY                      | [34073c7322](https://bsd-hardware.info/?probe=34073c7322) | Apr 21, 2021 |
| Shuttle       | DS10U                       | [491a0135a0](https://bsd-hardware.info/?probe=491a0135a0) | Apr 14, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [478a874db2](https://bsd-hardware.info/?probe=478a874db2) | Apr 09, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [fd03138dfc](https://bsd-hardware.info/?probe=fd03138dfc) | Apr 08, 2021 |
| Gigabyte      | H81M-S2PV                   | [f8d08a1ec0](https://bsd-hardware.info/?probe=f8d08a1ec0) | Apr 08, 2021 |
| HP            | 8054                        | [ab00142638](https://bsd-hardware.info/?probe=ab00142638) | Apr 07, 2021 |
| BESSTAR Te... | UM250 V1.0                  | [ec9c1e37db](https://bsd-hardware.info/?probe=ec9c1e37db) | Apr 07, 2021 |
| Shuttle       | DS10U                       | [bd2ea41c3d](https://bsd-hardware.info/?probe=bd2ea41c3d) | Apr 05, 2021 |
| BESSTAR Te... | IB9                         | [202b90b7bf](https://bsd-hardware.info/?probe=202b90b7bf) | Apr 02, 2021 |
| PC Engines    | APU2                        | [e578d2eadd](https://bsd-hardware.info/?probe=e578d2eadd) | Mar 17, 2021 |
| HP            | 3397                        | [4e4f84fe7e](https://bsd-hardware.info/?probe=4e4f84fe7e) | Mar 17, 2021 |
| PC Engines    | APU2                        | [70050ec377](https://bsd-hardware.info/?probe=70050ec377) | Mar 16, 2021 |
| Unknown       | SKYBAY                      | [e44d5add26](https://bsd-hardware.info/?probe=e44d5add26) | Mar 16, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [50caf95a09](https://bsd-hardware.info/?probe=50caf95a09) | Mar 15, 2021 |
| Shuttle       | DS10U                       | [8e895a4efd](https://bsd-hardware.info/?probe=8e895a4efd) | Mar 15, 2021 |
| Shuttle       | DS10U                       | [8fe918937b](https://bsd-hardware.info/?probe=8fe918937b) | Mar 15, 2021 |
| Unknown       | SKYBAY                      | [0cae097db1](https://bsd-hardware.info/?probe=0cae097db1) | Mar 14, 2021 |
| Unknown       | Unknown                     | [155c42b4b5](https://bsd-hardware.info/?probe=155c42b4b5) | Mar 08, 2021 |
| Unknown       | J3160-4L                    | [0390ce8498](https://bsd-hardware.info/?probe=0390ce8498) | Mar 06, 2021 |
| HP            | 3397                        | [f53c2d8ded](https://bsd-hardware.info/?probe=f53c2d8ded) | Mar 01, 2021 |
| HP            | 3397                        | [901050fb80](https://bsd-hardware.info/?probe=901050fb80) | Feb 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1439878133](https://bsd-hardware.info/?probe=1439878133) | Feb 12, 2021 |
| AAEON         | UP-APL01 V0.4               | [8fc8c1d27e](https://bsd-hardware.info/?probe=8fc8c1d27e) | Jan 31, 2021 |
| Protectli     | FW4B                        | [0a02b075ac](https://bsd-hardware.info/?probe=0a02b075ac) | Jan 24, 2021 |
| PC Engines    | apu4                        | [e7fcefa741](https://bsd-hardware.info/?probe=e7fcefa741) | Jan 21, 2021 |
| Unknown       | Unknown                     | [e69210e453](https://bsd-hardware.info/?probe=e69210e453) | Oct 29, 2020 |
| ASRock        | TRX40 Taichi                | [dda9a512ac](https://bsd-hardware.info/?probe=dda9a512ac) | Oct 29, 2020 |
| Dell          | PowerEdge 1950              | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| PC Engines    | APU2                        | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| ASUSTek       | PRIME B350M-A               | [be9c9d6b01](https://bsd-hardware.info/?probe=be9c9d6b01) | Aug 01, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| OPNsense 21.7.3      | 9        | 9.47%   |
| OPNsense 22.1.1      | 7        | 7.37%   |
| OPNsense 22.1        | 5        | 5.26%   |
| OPNsense 21.1.5      | 5        | 5.26%   |
| OPNsense 21.1.4      | 5        | 5.26%   |
| OPNsense 22.1.4      | 4        | 4.21%   |
| OPNsense 21.7.7      | 4        | 4.21%   |
| OPNsense 21.7.6      | 4        | 4.21%   |
| OPNsense 21.1.3      | 4        | 4.21%   |
| OPNsense 21.1        | 4        | 4.21%   |
| OpenBSD 6.8          | 4        | 4.21%   |
| OPNsense 22.1.7      | 3        | 3.16%   |
| OPNsense 21.1.8      | 3        | 3.16%   |
| OPNsense 21.1.2      | 3        | 3.16%   |
| OPNsense 22.1.9      | 2        | 2.11%   |
| OPNsense 21.7.1      | 2        | 2.11%   |
| OPNsense 21.7        | 2        | 2.11%   |
| OPNsense 21.1.9      | 2        | 2.11%   |
| OPNsense 21.1.1      | 2        | 2.11%   |
| OPNsense 20.7.8      | 2        | 2.11%   |
| FreeBSD 13.0-p5      | 2        | 2.11%   |
| OPNsense 22.1.8      | 1        | 1.05%   |
| OPNsense 22.1.2      | 1        | 1.05%   |
| OPNsense 21.7.8      | 1        | 1.05%   |
| OPNsense 21.7.5      | 1        | 1.05%   |
| OPNsense 21.7.4      | 1        | 1.05%   |
| OPNsense 21.7.2      | 1        | 1.05%   |
| OPNsense 21.1.7      | 1        | 1.05%   |
| OPNsense 21.1.6      | 1        | 1.05%   |
| OpenBSD 7.1          | 1        | 1.05%   |
| OpenBSD 7.0          | 1        | 1.05%   |
| FreeNAS 11.3-p8      | 1        | 1.05%   |
| FreeBSD 14.0-CURRENT | 1        | 1.05%   |
| FreeBSD 13.1         | 1        | 1.05%   |
| FreeBSD 13.0-p3      | 1        | 1.05%   |
| FreeBSD 13.0-p11     | 1        | 1.05%   |
| FreeBSD 12.1-p7      | 1        | 1.05%   |
| FreeBSD 12.1-p10     | 1        | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| OPNsense | 58       | 80.56%  |
| FreeBSD  | 7        | 9.72%   |
| OpenBSD  | 6        | 8.33%   |
| FreeNAS  | 1        | 1.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 71       | 98.61%  |
| i386  | 1        | 1.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 65       | 89.04%  |
| KDE5         | 2        | 2.74%   |
| xinitrc      | 1        | 1.37%   |
| XFCE         | 1        | 1.37%   |
| TWM          | 1        | 1.37%   |
| LXQt         | 1        | 1.37%   |
| helloDesktop | 1        | 1.37%   |
| fvwm         | 1        | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 66       | 91.67%  |
| X11     | 6        | 8.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 70       | 95.89%  |
| SDDM    | 3        | 4.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 65       | 89.04%  |
| C       | 5        | 6.85%   |
| en_US   | 2        | 2.74%   |
| de_DE   | 1        | 1.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 59       | 81.94%  |
| BIOS | 13       | 18.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 51       | 69.86%  |
| Zfs     | 15       | 20.55%  |
| Ffs     | 6        | 8.22%   |
| Unknown | 1        | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 61       | 84.72%  |
| MBR     | 7        | 9.72%   |
| Unknown | 4        | 5.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 11       | 15.28%  |
| Unknown             | 11       | 15.28%  |
| Lenovo              | 6        | 8.33%   |
| Dell                | 6        | 8.33%   |
| Protectli           | 4        | 5.56%   |
| Hewlett-Packard     | 4        | 5.56%   |
| Shuttle             | 3        | 4.17%   |
| Gigabyte Technology | 3        | 4.17%   |
| Fujitsu             | 3        | 4.17%   |
| BESSTAR Tech        | 3        | 4.17%   |
| ASUSTek Computer    | 3        | 4.17%   |
| ASRock              | 3        | 4.17%   |
| SeeedStudio         | 2        | 2.78%   |
| Intel               | 2        | 2.78%   |
| Winston Marriot     | 1        | 1.39%   |
| Silicom             | 1        | 1.39%   |
| Secudos             | 1        | 1.39%   |
| Purism              | 1        | 1.39%   |
| NEXCOM              | 1        | 1.39%   |
| MSI                 | 1        | 1.39%   |
| Biostar             | 1        | 1.39%   |
| AAEON               | 1        | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 12       | 16.67%  |
| PC Engines APU2                             | 6        | 8.33%   |
| PC Engines apu4                             | 5        | 6.94%   |
| Protectli FW4B                              | 3        | 4.17%   |
| Shuttle DS10U                               | 2        | 2.78%   |
| Intel Q3XXG4-P V1.0                         | 2        | 2.78%   |
| Fujitsu ESPRIMO C720                        | 2        | 2.78%   |
| Winston Marriot PICO PC  PICOPC             | 1        | 1.39%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM   | 1        | 1.39%   |
| Shuttle DH170                               | 1        | 1.39%   |
| SeeedStudio ODYSSEY-X86J4125                | 1        | 1.39%   |
| SeeedStudio ODYSSEY-X86J4105                | 1        | 1.39%   |
| Purism Librem Mini v2                       | 1        | 1.39%   |
| Protectli FW6E                              | 1        | 1.39%   |
| NEXCOM ASG                                  | 1        | 1.39%   |
| MSI MS-6788                                 | 1        | 1.39%   |
| Lenovo ThinkPad T400 2768W3A                | 1        | 1.39%   |
| Lenovo ThinkCentre M93p 10AB003CGE          | 1        | 1.39%   |
| Lenovo ThinkCentre M92P 3237CK4             | 1        | 1.39%   |
| Lenovo ThinkCentre M73 10B4S03V05           | 1        | 1.39%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE     | 1        | 1.39%   |
| Lenovo IdeaCentre 3 07ADA05 90MV007UGE      | 1        | 1.39%   |
| HP ProDesk 600 G2 SFF                       | 1        | 1.39%   |
| HP EliteDesk 800 G2 SFF                     | 1        | 1.39%   |
| HP Compaq Elite 8300 SFF                    | 1        | 1.39%   |
| HP Compaq 8200 Elite SFF PC                 | 1        | 1.39%   |
| Gigabyte H81M-S2PV                          | 1        | 1.39%   |
| Gigabyte B365M DS3H                         | 1        | 1.39%   |
| Gigabyte B150-HD3P-CF                       | 1        | 1.39%   |
| Fujitsu ESPRIMO C910                        | 1        | 1.39%   |
| Dell PowerEdge R610                         | 1        | 1.39%   |
| Dell PowerEdge 1950                         | 1        | 1.39%   |
| Dell OptiPlex 790                           | 1        | 1.39%   |
| Dell OptiPlex 7050                          | 1        | 1.39%   |
| Dell OptiPlex 7040                          | 1        | 1.39%   |
| Dell OptiPlex 5040                          | 1        | 1.39%   |
| Biostar N3050NH                             | 1        | 1.39%   |
| BESSTAR Tech X35G                           | 1        | 1.39%   |
| BESSTAR Tech UM270                          | 1        | 1.39%   |
| BESSTAR Tech UM250                          | 1        | 1.39%   |
| ASUS PRIME B350M-A                          | 1        | 1.39%   |
| ASUS P8H77-M PRO                            | 1        | 1.39%   |
| ASUS 1HE Intel Single-CPU RI1101H-XE Server | 1        | 1.39%   |
| ASRock TRX40 Taichi                         | 1        | 1.39%   |
| ASRock H510M-HDV/M.2                        | 1        | 1.39%   |
| ASRock B460M Pro4                           | 1        | 1.39%   |
| AAEON UP-APL01                              | 1        | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 12       | 16.67%  |
| PC Engines APU2              | 6        | 8.33%   |
| PC Engines apu4              | 5        | 6.94%   |
| Dell OptiPlex                | 4        | 5.56%   |
| Protectli FW4B               | 3        | 4.17%   |
| Lenovo ThinkCentre           | 3        | 4.17%   |
| Fujitsu ESPRIMO              | 3        | 4.17%   |
| Shuttle DS10U                | 2        | 2.78%   |
| Lenovo IdeaCentre            | 2        | 2.78%   |
| Intel Q3XXG4-P               | 2        | 2.78%   |
| HP Compaq                    | 2        | 2.78%   |
| Dell PowerEdge               | 2        | 2.78%   |
| Winston Marriot PICO         | 1        | 1.39%   |
| Silicom Minnowboard          | 1        | 1.39%   |
| Shuttle DH170                | 1        | 1.39%   |
| SeeedStudio ODYSSEY-X86J4125 | 1        | 1.39%   |
| SeeedStudio ODYSSEY-X86J4105 | 1        | 1.39%   |
| Purism Librem                | 1        | 1.39%   |
| Protectli FW6E               | 1        | 1.39%   |
| NEXCOM ASG                   | 1        | 1.39%   |
| MSI MS-6788                  | 1        | 1.39%   |
| Lenovo ThinkPad              | 1        | 1.39%   |
| HP ProDesk                   | 1        | 1.39%   |
| HP EliteDesk                 | 1        | 1.39%   |
| Gigabyte H81M-S2PV           | 1        | 1.39%   |
| Gigabyte B365M               | 1        | 1.39%   |
| Gigabyte B150-HD3P-CF        | 1        | 1.39%   |
| Biostar N3050NH              | 1        | 1.39%   |
| BESSTAR Tech X35G            | 1        | 1.39%   |
| BESSTAR Tech UM270           | 1        | 1.39%   |
| BESSTAR Tech UM250           | 1        | 1.39%   |
| ASUS PRIME                   | 1        | 1.39%   |
| ASUS P8H77-M                 | 1        | 1.39%   |
| ASUS 1HE                     | 1        | 1.39%   |
| ASRock TRX40                 | 1        | 1.39%   |
| ASRock H510M-HDV             | 1        | 1.39%   |
| ASRock B460M                 | 1        | 1.39%   |
| AAEON UP-APL01               | 1        | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 12       | 16.67%  |
| 2016    | 12       | 16.67%  |
| 2018    | 10       | 13.89%  |
| 2021    | 9        | 12.5%   |
| 2019    | 6        | 8.33%   |
| 2017    | 5        | 6.94%   |
| 2015    | 5        | 6.94%   |
| 2013    | 3        | 4.17%   |
| 2012    | 3        | 4.17%   |
| 2011    | 2        | 2.78%   |
| Unknown | 2        | 2.78%   |
| 2014    | 1        | 1.39%   |
| 2009    | 1        | 1.39%   |
| 2007    | 1        | 1.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 72       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 58       | 80.56%  |
| Yes  | 14       | 19.44%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 28       | 38.36%  |
| 4.01-8.0        | 18       | 24.66%  |
| 16.01-24.0      | 13       | 17.81%  |
| 2.01-3.0        | 5        | 6.85%   |
| 32.01-64.0      | 4        | 5.48%   |
| More than 256.0 | 1        | 1.37%   |
| 3.01-4.0        | 1        | 1.37%   |
| 24.01-32.0      | 1        | 1.37%   |
| 64.01-256.0     | 1        | 1.37%   |
| 1.01-2.0        | 1        | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 46       | 61.33%  |
| 0.51-1.0   | 19       | 25.33%  |
| 1.01-2.0   | 4        | 5.33%   |
| 2.01-3.0   | 2        | 2.67%   |
| 4.01-8.0   | 1        | 1.33%   |
| 32.01-64.0 | 1        | 1.33%   |
| 3.01-4.0   | 1        | 1.33%   |
| 0          | 1        | 1.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 80%     |
| 2      | 9        | 12%     |
| 0      | 5        | 6.67%   |
| 3      | 1        | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 90.41%  |
| Yes       | 7        | 9.59%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 72       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 57       | 78.08%  |
| Yes       | 16       | 21.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 62       | 86.11%  |
| Yes       | 10       | 13.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 72       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Vienna                   | 34       | 43.59%  |
| Graz                     | 9        | 11.54%  |
| Linz                     | 3        | 3.85%   |
| Sankt Veit an der Glan   | 2        | 2.56%   |
| Innsbruck                | 2        | 2.56%   |
| Voggenberg               | 1        | 1.28%   |
| Tulln                    | 1        | 1.28%   |
| Stockerau                | 1        | 1.28%   |
| Steyr                    | 1        | 1.28%   |
| Spittal an der Drau      | 1        | 1.28%   |
| Siegendorf im Burgenland | 1        | 1.28%   |
| Schwechat                | 1        | 1.28%   |
| Sankt PÃ¶lten          | 1        | 1.28%   |
| Salzburg                 | 1        | 1.28%   |
| Purkersdorf              | 1        | 1.28%   |
| Poelfing                 | 1        | 1.28%   |
| Pichl bei Wels           | 1        | 1.28%   |
| Oberpullendorf           | 1        | 1.28%   |
| Neulengbach              | 1        | 1.28%   |
| Maria-Anzbach            | 1        | 1.28%   |
| Margarethen am Moos      | 1        | 1.28%   |
| Leogang                  | 1        | 1.28%   |
| Leoben                   | 1        | 1.28%   |
| Hoerndl                  | 1        | 1.28%   |
| Gmunden                  | 1        | 1.28%   |
| Ferndorf                 | 1        | 1.28%   |
| Euratsfeld               | 1        | 1.28%   |
| Enzenreith               | 1        | 1.28%   |
| Eisenstadt               | 1        | 1.28%   |
| Bruck an der Mur         | 1        | 1.28%   |
| Breitenfurt bei Wien     | 1        | 1.28%   |
| Birkfeld                 | 1        | 1.28%   |
| Ansfelden                | 1        | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 24     | 16.88%  |
| Transcend           | 11       | 11     | 14.29%  |
| Crucial             | 7        | 8      | 9.09%   |
| WDC                 | 6        | 7      | 7.79%   |
| Kingston            | 5        | 6      | 6.49%   |
| Phison              | 4        | 5      | 5.19%   |
| Hoodisk             | 4        | 5      | 5.19%   |
| Seagate             | 3        | 8      | 3.9%    |
| SanDisk             | 3        | 8      | 3.9%    |
| China               | 3        | 3      | 3.9%    |
| Toshiba             | 2        | 2      | 2.6%    |
| Intel               | 2        | 3      | 2.6%    |
| FORESEE             | 2        | 2      | 2.6%    |
| Dell                | 2        | 2      | 2.6%    |
| Corsair             | 2        | 3      | 2.6%    |
| SK hynix            | 1        | 1      | 1.3%    |
| KingSpec            | 1        | 1      | 1.3%    |
| Hitachi             | 1        | 1      | 1.3%    |
| HGST                | 1        | 3      | 1.3%    |
| Goodram             | 1        | 1      | 1.3%    |
| Dogfish             | 1        | 1      | 1.3%    |
| BIWIN               | 1        | 1      | 1.3%    |
| A-DATA Technology   | 1        | 3      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 250GB                | 5        | 6.33%   |
| Transcend TS128GMSA230S 128GB            | 4        | 5.06%   |
| Crucial CT240BX500SSD1 240GB             | 3        | 3.8%    |
| Transcend TS16GMSA370 16GB               | 2        | 2.53%   |
| Phison SATA SSD 16GB                     | 2        | 2.53%   |
| Kingston SUV500MS120G 120GB              | 2        | 2.53%   |
| Hoodisk SSD 64GB                         | 2        | 2.53%   |
| FORESEE 128GB SSD                        | 2        | 2.53%   |
| Crucial CT250MX500SSD1 250GB             | 2        | 2.53%   |
| China SATA SSD 64GB                      | 2        | 2.53%   |
| WDC WD800JD-60LSA5 80GB                  | 1        | 1.27%   |
| WDC WD1600BEVS-00UST0 160GB              | 1        | 1.27%   |
| WDC WD120EFBX-68B0EN0 12TB               | 1        | 1.27%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1        | 1.27%   |
| WDC WD Elements 25A1 4TB                 | 1        | 1.27%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB     | 1        | 1.27%   |
| Transcend TS64GMSA370 64GB               | 1        | 1.27%   |
| Transcend TS64GMSA230S 64GB              | 1        | 1.27%   |
| Transcend TS256GMSA370 256GB             | 1        | 1.27%   |
| Transcend TS256GMSA230S 256GB            | 1        | 1.27%   |
| Transcend TS240GSSD220S 240GB            | 1        | 1.27%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.27%   |
| Toshiba MK3276GSX -63 320GB              | 1        | 1.27%   |
| SK hynix SC308 SATA 128GB                | 1        | 1.27%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1.27%   |
| Seagate ST3160318AS 160GB                | 1        | 1.27%   |
| Seagate BarraCuda SSD ZA250CM10002 250GB | 1        | 1.27%   |
| SanDisk X400 M.2 2280 128GB              | 1        | 1.27%   |
| SanDisk SSD PLUS 120GB                   | 1        | 1.27%   |
| SanDisk SD8SBAT-256G-1006 256GB          | 1        | 1.27%   |
| Samsung SSD 980 250GB                    | 1        | 1.27%   |
| Samsung SSD 970 PRO 1TB                  | 1        | 1.27%   |
| Samsung SSD 970 EVO Plus 2TB             | 1        | 1.27%   |
| Samsung SSD 970 EVO Plus 250GB           | 1        | 1.27%   |
| Samsung SSD 870 QVO 2TB                  | 1        | 1.27%   |
| Samsung SSD 860 PRO 256GB                | 1        | 1.27%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.27%   |
| Samsung SSD 850 EVO 250GB                | 1        | 1.27%   |
| Samsung SSD 830 Series 256GB             | 1        | 1.27%   |
| Phison SATA SSD 64GB                     | 1        | 1.27%   |
| Phison minisforum 512GB                  | 1        | 1.27%   |
| Kingston SHFS37A120G 120GB               | 1        | 1.27%   |
| Kingston SA400S37240G 240GB              | 1        | 1.27%   |
| Kingston OM8P0S3512F-00 512GB            | 1        | 1.27%   |
| Kingston OM8P0S3256B-A0 256GB            | 1        | 1.27%   |
| KingSpec NT-32 32GB                      | 1        | 1.27%   |
| Intel SSDSC2KB240G8 240GB                | 1        | 1.27%   |
| Intel SSDSA2CW160G3 160GB                | 1        | 1.27%   |
| Hoodisk SSD 32GB                         | 1        | 1.27%   |
| Hoodisk SSD 128GB                        | 1        | 1.27%   |
| Hitachi HDS721050CLA660 500GB            | 1        | 1.27%   |
| HGST HTS725050A7E630 500GB               | 1        | 1.27%   |
| Goodram SSDPR-CX400-256-G2 256GB         | 1        | 1.27%   |
| Dogfish SSD 16GB                         | 1        | 1.27%   |
| Dell PERC H700 304GB                     | 1        | 1.27%   |
| Dell PERC 5-i 499GB                      | 1        | 1.27%   |
| Crucial CT500MX500SSD1 500GB             | 1        | 1.27%   |
| Crucial CT120BX500SSD1 120GB             | 1        | 1.27%   |
| Corsair Force MP600 2TB                  | 1        | 1.27%   |
| Corsair Force MP510 240GB                | 1        | 1.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 6      | 38.46%  |
| Toshiba | 2        | 2      | 15.38%  |
| Seagate | 2        | 2      | 15.38%  |
| Dell    | 2        | 2      | 15.38%  |
| Hitachi | 1        | 1      | 7.69%   |
| HGST    | 1        | 3      | 7.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 11       | 11     | 19.64%  |
| Samsung Electronics | 10       | 15     | 17.86%  |
| Crucial             | 7        | 8      | 12.5%   |
| Kingston            | 5        | 6      | 8.93%   |
| Hoodisk             | 4        | 5      | 7.14%   |
| SanDisk             | 3        | 8      | 5.36%   |
| Phison              | 3        | 4      | 5.36%   |
| China               | 3        | 3      | 5.36%   |
| Intel               | 2        | 3      | 3.57%   |
| FORESEE             | 2        | 2      | 3.57%   |
| SK hynix            | 1        | 1      | 1.79%   |
| Seagate             | 1        | 6      | 1.79%   |
| KingSpec            | 1        | 1      | 1.79%   |
| Goodram             | 1        | 1      | 1.79%   |
| Dogfish             | 1        | 1      | 1.79%   |
| BIWIN               | 1        | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 55       | 76     | 72.37%  |
| HDD  | 12       | 16     | 15.79%  |
| NVMe | 9        | 17     | 11.84%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 63       | 92     | 87.5%   |
| NVMe | 9        | 17     | 12.5%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 59       | 84     | 89.39%  |
| 0.51-1.0   | 3        | 3      | 4.55%   |
| 3.01-4.0   | 1        | 1      | 1.52%   |
| 10.01-20.0 | 1        | 2      | 1.52%   |
| 1.01-2.0   | 1        | 1      | 1.52%   |
| 4.01-10.0  | 1        | 1      | 1.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 41       | 55.41%  |
| 251-500    | 9        | 12.16%  |
| 21-50      | 9        | 12.16%  |
| 51-100     | 6        | 8.11%   |
| 1-20       | 5        | 6.76%   |
| 501-1000   | 3        | 4.05%   |
| 1001-2000  | 1        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 69       | 95.83%  |
| 21-50    | 1        | 1.39%   |
| 101-250  | 1        | 1.39%   |
| 501-1000 | 1        | 1.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1600BEVS-00UST0 160GB   | 1        | 1      | 25%     |
| SK hynix SC308 SATA 128GB     | 1        | 1      | 25%     |
| Hitachi HDS721050CLA660 500GB | 1        | 1      | 25%     |
| HGST HTS725050A7E630 500GB    | 1        | 3      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 25%     |
| SK hynix | 1        | 1      | 25%     |
| Hitachi  | 1        | 1      | 25%     |
| HGST     | 1        | 3      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Hitachi | 1        | 1      | 33.33%  |
| HGST    | 1        | 3      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 5      | 75%     |
| SSD  | 1        | 1      | 25%     |

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
| Works    | 64       | 99     | 91.43%  |
| Detected | 3        | 4      | 4.29%   |
| Malfunc  | 3        | 6      | 4.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 54       | 63.53%  |
| AMD                      | 17       | 20%     |
| Samsung Electronics      | 4        | 4.71%   |
| Phison Electronics       | 3        | 3.53%   |
| Broadcom / LSI           | 2        | 2.35%   |
| SanDisk                  | 1        | 1.18%   |
| Realtek Semiconductor    | 1        | 1.18%   |
| Marvell Technology Group | 1        | 1.18%   |
| Hewlett-Packard          | 1        | 1.18%   |
| Dell                     | 1        | 1.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 13       | 14.44%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 8.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8        | 8.89%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5        | 5.56%   |
| AMD FCH SATA Controller [IDE mode]                                               | 5        | 5.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 3.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 3.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 2.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2        | 2.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 2.22%   |
| SanDisk PC SN530                                                                 | 1        | 1.11%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 1.11%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 1.11%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 1.11%   |
| Phison E12 NVMe Controller                                                       | 1        | 1.11%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                            | 1        | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1        | 1.11%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 1.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1        | 1.11%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.11%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 1        | 1.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1        | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.11%   |
| Intel 631xESB/632xESB IDE Controller                                             | 1        | 1.11%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1        | 1.11%   |
| HP Smart Array G6 controllers                                                    | 1        | 1.11%   |
| Dell PowerEdge Expandable RAID controller 5                                      | 1        | 1.11%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.11%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 1        | 1.11%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                     | 1        | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 1.11%   |
| Unknown                                                                          | 1        | 1.11%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 63       | 72.41%  |
| NVMe | 9        | 10.34%  |
| IDE  | 9        | 10.34%  |
| RAID | 4        | 4.6%    |
| SAS  | 1        | 1.15%   |
| SCSI | 1        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 55       | 76.39%  |
| AMD    | 17       | 23.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                       | 11       | 15.28%  |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 7        | 9.72%   |
| Intel Xeon CPU E5620 @ 2.40GHz                         | 2        | 2.78%   |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 2        | 2.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz                      | 2        | 2.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 2        | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz                     | 2        | 2.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz                       | 2        | 2.78%   |
| Intel Xeon CPU E5320 @ 1.86GHz                         | 1        | 1.39%   |
| Intel Pentium CPU G4400 @ 3.30GHz                      | 1        | 1.39%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class) | 1        | 1.39%   |
| Intel Genuine CPU 0000 @ 2.40GHz                       | 1        | 1.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1        | 1.39%   |
| Intel Core i7-5550U CPU @ 2.00GHz                      | 1        | 1.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 1        | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz                     | 1        | 1.39%   |
| Intel Core i5-8365U CPU @ 1.60GHz                      | 1        | 1.39%   |
| Intel Core i5-7500 CPU @ 3.40GHz                       | 1        | 1.39%   |
| Intel Core i5-6600 CPU @ 3.30GHz                       | 1        | 1.39%   |
| Intel Core i5-6500T CPU @ 2.50GHz                      | 1        | 1.39%   |
| Intel Core i5-6400 CPU @ 2.70GHz                       | 1        | 1.39%   |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 1        | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1        | 1.39%   |
| Intel Core i5-3570 CPU @ 3.40GHz                       | 1        | 1.39%   |
| Intel Core i5-3470T CPU @ 2.90GHz                      | 1        | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz                       | 1        | 1.39%   |
| Intel Core i5-2400S CPU @ 2.50GH                       | 1        | 1.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz                       | 1        | 1.39%   |
| Intel Core i5-10400F CPU @ 2.90GHz                     | 1        | 1.39%   |
| Intel Core i3-9100F CPU @ 3.60GHz                      | 1        | 1.39%   |
| Intel Core i3-9100 CPU @ 3.60GHz                       | 1        | 1.39%   |
| Intel Core i3-7100U CPU @ 2.40GHz                      | 1        | 1.39%   |
| Intel Core i3-6100T CPU @ 3.20GHz                      | 1        | 1.39%   |
| Intel Core i3-10105 CPU @ 3.70GHz                      | 1        | 1.39%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                     | 1        | 1.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                   | 1        | 1.39%   |
| Intel Core 2 Duo                                       | 1        | 1.39%   |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 1        | 1.39%   |
| Intel Celeron J4105 CPU @ 1.50GHz                      | 1        | 1.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1        | 1.39%   |
| Intel Celeron CPU N3050 @ 1.60GHz                      | 1        | 1.39%   |
| Intel Celeron CPU 4205U @ 1.80GHz                      | 1        | 1.39%   |
| Intel Atom CPU E3845 @ 1.91GHz                         | 1        | 1.39%   |
| Intel Atom CPU C3558 @ 2.20GHz                         | 1        | 1.39%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor         | 1        | 1.39%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx          | 1        | 1.39%   |
| AMD Ryzen 7 1700 Eight-Core Processor                  | 1        | 1.39%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx        | 1        | 1.39%   |
| AMD Athlon Silver 3050U with Radeon Graphics           | 1        | 1.39%   |
| AMD A9-9430 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1        | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 17       | 23.61%  |
| Intel Celeron          | 12       | 16.67%  |
| AMD GX                 | 11       | 15.28%  |
| Intel Core i3          | 8        | 11.11%  |
| Intel Core i7          | 6        | 8.33%   |
| Intel Xeon             | 3        | 4.17%   |
| Intel Pentium          | 3        | 4.17%   |
| Intel Core 2 Duo       | 2        | 2.78%   |
| Intel Atom             | 2        | 2.78%   |
| AMD Ryzen 7            | 2        | 2.78%   |
| Other                  | 1        | 1.39%   |
| Intel Pentium 4        | 1        | 1.39%   |
| Intel Genuine          | 1        | 1.39%   |
| AMD Ryzen Threadripper | 1        | 1.39%   |
| AMD Ryzen 5 PRO        | 1        | 1.39%   |
| AMD Athlon             | 1        | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 45       | 62.5%   |
| 2       | 17       | 23.61%  |
| 8       | 4        | 5.56%   |
| Unknown | 2        | 2.78%   |
| 64      | 1        | 1.39%   |
| 16      | 1        | 1.39%   |
| 6       | 1        | 1.39%   |
| 1       | 1        | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 67       | 93.06%  |
| Unknown | 3        | 4.17%   |
| 2       | 2        | 2.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 48       | 66.67%  |
| 2       | 21       | 29.17%  |
| Unknown | 3        | 4.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 12       | 16.67%  |
| Puma          | 11       | 15.28%  |
| Silvermont    | 9        | 12.5%   |
| Skylake       | 8        | 11.11%  |
| Haswell       | 6        | 8.33%   |
| IvyBridge     | 4        | 5.56%   |
| Zen           | 3        | 4.17%   |
| Westmere      | 2        | 2.78%   |
| SandyBridge   | 2        | 2.78%   |
| Penryn        | 2        | 2.78%   |
| Goldmont plus | 2        | 2.78%   |
| Goldmont      | 2        | 2.78%   |
| CometLake     | 2        | 2.78%   |
| Zen+          | 1        | 1.39%   |
| Zen 2         | 1        | 1.39%   |
| NetBurst      | 1        | 1.39%   |
| IceLake       | 1        | 1.39%   |
| Excavator     | 1        | 1.39%   |
| Core          | 1        | 1.39%   |
| Broadwell     | 1        | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 48       | 81.36%  |
| AMD                        | 6        | 10.17%  |
| Nvidia                     | 3        | 5.08%   |
| Matrox Electronics Systems | 1        | 1.69%   |
| ASPEED Technology          | 1        | 1.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 13.56%  |
| Intel HD Graphics 530                                                                    | 6        | 10.17%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 5.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 5.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3        | 5.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3        | 5.08%   |
| Intel HD Graphics 630                                                                    | 2        | 3.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 3.39%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 3.39%   |
| AMD ES1000                                                                               | 2        | 3.39%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1        | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.69%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.69%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 1.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 1.69%   |
| Intel HD Graphics 620                                                                    | 1        | 1.69%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.69%   |
| Intel HD Graphics 510                                                                    | 1        | 1.69%   |
| Intel HD Graphics 500                                                                    | 1        | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.69%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.69%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1        | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 46       | 63.89%  |
| Other      | 13       | 18.06%  |
| 1 x AMD    | 6        | 8.33%   |
| 1 x Nvidia | 3        | 4.17%   |
| 2 x Intel  | 2        | 2.78%   |
| 1 x Matrox | 1        | 1.39%   |
| 1 x ASPEED | 1        | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 58       | 80.56%  |
| Unknown     | 13       | 18.06%  |
| Proprietary | 1        | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 98.61%  |
| 1.01-2.0   | 1        | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 28.57%  |
| Philips             | 2        | 28.57%  |
| Medion              | 1        | 14.29%  |
| Lenovo              | 1        | 14.29%  |
| Dell                | 1        | 14.29%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1        | 14.29%  |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1        | 14.29%  |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1        | 14.29%  |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 14.29%  |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1        | 14.29%  |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1        | 14.29%  |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                    | 1        | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2        | 28.57%  |
| 3840x2160 (4K)     | 1        | 14.29%  |
| 3840x1080          | 1        | 14.29%  |
| 1680x1050 (WSXGA+) | 1        | 14.29%  |
| 1600x1200          | 1        | 14.29%  |
| 1440x900 (WXGA+)   | 1        | 14.29%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 20      | 2        | 28.57%  |
| 40      | 1        | 14.29%  |
| 31      | 1        | 14.29%  |
| 27      | 1        | 14.29%  |
| 14      | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 2        | 28.57%  |
| 801-900     | 1        | 14.29%  |
| 601-700     | 1        | 14.29%  |
| 501-600     | 1        | 14.29%  |
| 201-300     | 1        | 14.29%  |
| Unknown     | 1        | 14.29%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 3        | 42.86%  |
| 16/10 | 2        | 28.57%  |
| 4/3   | 1        | 14.29%  |
| 32/9  | 1        | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 2        | 28.57%  |
| 81-90          | 1        | 14.29%  |
| 351-500        | 1        | 14.29%  |
| 301-350        | 1        | 14.29%  |
| 501-1000       | 1        | 14.29%  |
| Unknown        | 1        | 14.29%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4        | 57.14%  |
| 121-160 | 1        | 14.29%  |
| 101-120 | 1        | 14.29%  |
| Unknown | 1        | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 66       | 91.67%  |
| 1     | 5        | 6.94%   |
| 2     | 1        | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 58       | 63.04%  |
| Realtek Semiconductor | 21       | 22.83%  |
| Broadcom              | 3        | 3.26%   |
| Qualcomm Atheros      | 2        | 2.17%   |
| LG Electronics        | 2        | 2.17%   |
| TP-Link               | 1        | 1.09%   |
| Seeed Technology      | 1        | 1.09%   |
| Edimax Technology     | 1        | 1.09%   |
| Dresden Elektronik    | 1        | 1.09%   |
| AVM                   | 1        | 1.09%   |
| Arduino SA            | 1        | 1.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 23       | 20.35%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 14.16%  |
| Intel I210 Gigabit Network Connection                                         | 14       | 12.39%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 4.42%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 3.54%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 2.65%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.77%   |
| LG Optimus Android Phone [USB tethering mode]                                 | 2        | 1.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2        | 1.77%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.77%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.77%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 1.77%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.88%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.88%   |
| Intel Wireless 7265                                                           | 1        | 0.88%   |
| Intel Wireless 7260                                                           | 1        | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                               | 1        | 0.88%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.88%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.88%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.88%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.88%   |
| Intel Centrino Ultimate-N 6300                                                | 1        | 0.88%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.88%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.88%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1        | 0.88%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                 | 1        | 0.88%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.88%   |
| AVM A1 ISDN [Fritz]                                                           | 1        | 0.88%   |
| Arduino SA Leonardo (CDC ACM, HID)                                            | 1        | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 50%     |
| Realtek Semiconductor | 4        | 25%     |
| Qualcomm Atheros      | 2        | 12.5%   |
| TP-Link               | 1        | 6.25%   |
| Edimax Technology     | 1        | 6.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 18.75%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 12.5%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2        | 12.5%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 6.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 6.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 6.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 6.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 6.25%   |
| Intel Wireless 7265                                            | 1        | 6.25%   |
| Intel Wireless 7260                                            | 1        | 6.25%   |
| Intel Ultimate N WiFi Link 5300                                | 1        | 6.25%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 6.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 55       | 72.37%  |
| Realtek Semiconductor | 18       | 23.68%  |
| Broadcom              | 3        | 3.95%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 23       | 25.56%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 16       | 17.78%  |
| Intel I210 Gigabit Network Connection                                         | 14       | 15.56%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 5.56%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 4.44%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.33%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.22%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 2.22%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 2.22%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.11%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 1.11%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.11%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 1.11%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 1.11%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.11%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 1.11%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 1.11%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.11%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 1.11%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 72       | 75.79%  |
| WiFi     | 16       | 16.84%  |
| Modem    | 5        | 5.26%   |
| Unknown  | 2        | 2.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 70       | 98.59%  |
| WiFi     | 1        | 1.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 17       | 23.61%  |
| 4     | 16       | 22.22%  |
| 2     | 14       | 19.44%  |
| 1     | 9        | 12.5%   |
| 6     | 7        | 9.72%   |
| 8     | 3        | 4.17%   |
| 7     | 3        | 4.17%   |
| 5     | 3        | 4.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 71       | 97.26%  |
| Yes  | 2        | 2.74%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 6        | 60%     |
| IMC Networks          | 2        | 20%     |
| Realtek Semiconductor | 1        | 10%     |
| Lite-On Technology    | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                          | 3        | 30%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 20%     |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 20%     |
| Realtek RTL8821A Bluetooth                     | 1        | 10%     |
| Lite-On Atheros AR3012 Bluetooth               | 1        | 10%     |
| Intel Bluetooth wireless interface             | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 40       | 81.63%  |
| AMD           | 6        | 12.24%  |
| Nvidia        | 2        | 4.08%   |
| Creative Labs | 1        | 2.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 14.04%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 10.53%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 5.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 5.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 5.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 3.51%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 3.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.75%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 1.75%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.75%   |
| AMD High Definition Audio Controller                                                              | 1        | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1        | 1.75%   |
| Unknown                                                                                           | 1        | 1.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 11       | 16.18%  |
| Unknown             | 11       | 16.18%  |
| Kingston            | 10       | 14.71%  |
| Samsung Electronics | 9        | 13.24%  |
| SK hynix            | 7        | 10.29%  |
| Micron Technology   | 5        | 7.35%   |
| Unknown (ABCD)      | 3        | 4.41%   |
| Ramaxel Technology  | 2        | 2.94%   |
| G.Skill             | 2        | 2.94%   |
| Corsair             | 2        | 2.94%   |
| Transcend           | 1        | 1.47%   |
| Tigo                | 1        | 1.47%   |
| Nanya Technology    | 1        | 1.47%   |
| Kingmax             | 1        | 1.47%   |
| Kimtigo             | 1        | 1.47%   |
| ATP                 | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown                                                           | 11       | 15.71%  |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 3        | 4.29%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s              | 2        | 2.86%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 2.86%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s             | 1        | 1.43%   |
| Tigo RAM 1600MHz-4G 4GB SODIMM DDR3 1600MT/s                      | 1        | 1.43%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.43%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.43%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.43%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s              | 1        | 1.43%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                         | 1        | 1.43%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 1        | 1.43%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s             | 1        | 1.43%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 2400MT/s               | 1        | 1.43%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s           | 1        | 1.43%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s                | 1        | 1.43%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s                | 1        | 1.43%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 1.43%   |
| Micron RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s              | 1        | 1.43%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s              | 1        | 1.43%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s             | 1        | 1.43%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 1.43%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s             | 1        | 1.43%   |
| Kingston RAM KHX1600C9S3L/8G 8GB DDR3 1600MT/s                    | 1        | 1.43%   |
| Kingston RAM KF073F-ELD 2GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 1        | 1.43%   |
| Kingston RAM CBD26D4S9S1ME-8 8GB SODIMM DDR4 2667MT/s             | 1        | 1.43%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.43%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 1        | 1.43%   |
| Kingston RAM 99P5700-014.A00G 8GB SODIMM DDR4 2667MT/s            | 1        | 1.43%   |
| Kingston RAM 9905469-143.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.43%   |
| Kingmax RAM FLFE85F-C8KJ9 2GB DIMM DDR3 1333MT/s                  | 1        | 1.43%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 1        | 1.43%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s              | 1        | 1.43%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                | 1        | 1.43%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s             | 1        | 1.43%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s           | 1        | 1.43%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 2400MT/s              | 1        | 1.43%   |
| Crucial RAM CT8G4DFS 8192MB DIMM DDR4 2133MT/s                    | 1        | 1.43%   |
| Crucial RAM CT8G4DFD8213.C16FBD1 8GB DIMM DDR4 2133MT/s           | 1        | 1.43%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s             | 1        | 1.43%   |
| Crucial RAM CT4G4SFS824A.C8FBD1 4GB SODIMM DDR4 2400MT/s          | 1        | 1.43%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s        | 1        | 1.43%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s          | 1        | 1.43%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s          | 1        | 1.43%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2400MT/s         | 1        | 1.43%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3200MT/s               | 1        | 1.43%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s             | 1        | 1.43%   |
| Corsair RAM CMK64GX4M8Z2933C16 8GB DIMM DDR4 2133MT/s             | 1        | 1.43%   |
| ATP RAM X4C04QD8BLTDSE-7-TN1 4GB DIMM DDR4 2667MT/s               | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 30       | 48.39%  |
| DDR4    | 26       | 41.94%  |
| LPDDR4  | 4        | 6.45%   |
| DDR2    | 1        | 1.61%   |
| Unknown | 1        | 1.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 32       | 51.61%  |
| SODIMM       | 27       | 43.55%  |
| Unknown      | 2        | 3.23%   |
| Row Of Chips | 1        | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 25       | 39.68%  |
| 4096  | 19       | 30.16%  |
| 16384 | 8        | 12.7%   |
| 2048  | 7        | 11.11%  |
| 32768 | 2        | 3.17%   |
| 1024  | 2        | 3.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 17       | 26.15%  |
| 1333  | 13       | 20%     |
| 2400  | 10       | 15.38%  |
| 2667  | 9        | 13.85%  |
| 3200  | 6        | 9.23%   |
| 2133  | 4        | 6.15%   |
| 1067  | 2        | 3.08%   |
| 65535 | 1        | 1.54%   |
| 2666  | 1        | 1.54%   |
| 1033  | 1        | 1.54%   |
| 667   | 1        | 1.54%   |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Logitech Webcam C170 | 1        | 100%    |

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
| 1     | 30       | 41.1%   |
| 0     | 28       | 38.36%  |
| 2     | 8        | 10.96%  |
| 3     | 5        | 6.85%   |
| 5     | 1        | 1.37%   |
| 4     | 1        | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 39       | 60.94%  |
| Net/wireless             | 9        | 14.06%  |
| Card reader              | 7        | 10.94%  |
| Bluetooth                | 5        | 7.81%   |
| Network                  | 2        | 3.13%   |
| Sound                    | 1        | 1.56%   |
| Graphics card            | 1        | 1.56%   |

