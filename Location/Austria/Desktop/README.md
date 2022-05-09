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

Total: 107

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| PC Engines    | apu2                        | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
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
| OPNsense 21.7.3      | 9        | 10.34%  |
| OPNsense 22.1.1      | 7        | 8.05%   |
| OPNsense 22.1        | 5        | 5.75%   |
| OPNsense 21.1.5      | 5        | 5.75%   |
| OPNsense 21.1.4      | 5        | 5.75%   |
| OPNsense 22.1.4      | 4        | 4.6%    |
| OPNsense 21.7.7      | 4        | 4.6%    |
| OPNsense 21.7.6      | 4        | 4.6%    |
| OPNsense 21.1.3      | 4        | 4.6%    |
| OPNsense 21.1        | 4        | 4.6%    |
| OpenBSD 6.8          | 4        | 4.6%    |
| OPNsense 21.1.8      | 3        | 3.45%   |
| OPNsense 21.1.2      | 3        | 3.45%   |
| OPNsense 21.7.1      | 2        | 2.3%    |
| OPNsense 21.7        | 2        | 2.3%    |
| OPNsense 21.1.9      | 2        | 2.3%    |
| OPNsense 21.1.1      | 2        | 2.3%    |
| OPNsense 20.7.8      | 2        | 2.3%    |
| FreeBSD 13.0-p5      | 2        | 2.3%    |
| OPNsense 22.1.2      | 1        | 1.15%   |
| OPNsense 21.7.8      | 1        | 1.15%   |
| OPNsense 21.7.5      | 1        | 1.15%   |
| OPNsense 21.7.4      | 1        | 1.15%   |
| OPNsense 21.7.2      | 1        | 1.15%   |
| OPNsense 21.1.7      | 1        | 1.15%   |
| OPNsense 21.1.6      | 1        | 1.15%   |
| OpenBSD 7.0          | 1        | 1.15%   |
| FreeNAS 11.3-p8      | 1        | 1.15%   |
| FreeBSD 14.0-CURRENT | 1        | 1.15%   |
| FreeBSD 13.0-p3      | 1        | 1.15%   |
| FreeBSD 13.0-p11     | 1        | 1.15%   |
| FreeBSD 12.1-p7      | 1        | 1.15%   |
| FreeBSD 12.1-p10     | 1        | 1.15%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| OPNsense | 53       | 81.54%  |
| FreeBSD  | 6        | 9.23%   |
| OpenBSD  | 5        | 7.69%   |
| FreeNAS  | 1        | 1.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 65       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 59       | 89.39%  |
| KDE5    | 2        | 3.03%   |
| xinitrc | 1        | 1.52%   |
| XFCE    | 1        | 1.52%   |
| TWM     | 1        | 1.52%   |
| LXQt    | 1        | 1.52%   |
| fvwm    | 1        | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 60       | 92.31%  |
| X11     | 5        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 63       | 95.45%  |
| SDDM    | 3        | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 59       | 89.39%  |
| C       | 5        | 7.58%   |
| en_US   | 2        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 55       | 84.62%  |
| BIOS | 10       | 15.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 48       | 72.73%  |
| Zfs     | 12       | 18.18%  |
| Ffs     | 5        | 7.58%   |
| Unknown | 1        | 1.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 56       | 86.15%  |
| MBR     | 6        | 9.23%   |
| Unknown | 3        | 4.62%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 16.92%  |
| PC Engines          | 9        | 13.85%  |
| Lenovo              | 5        | 7.69%   |
| Dell                | 5        | 7.69%   |
| Hewlett-Packard     | 4        | 6.15%   |
| Shuttle             | 3        | 4.62%   |
| Protectli           | 3        | 4.62%   |
| Gigabyte Technology | 3        | 4.62%   |
| Fujitsu             | 3        | 4.62%   |
| BESSTAR Tech        | 3        | 4.62%   |
| ASUSTek Computer    | 3        | 4.62%   |
| ASRock              | 3        | 4.62%   |
| SeeedStudio         | 2        | 3.08%   |
| Winston Marriot     | 1        | 1.54%   |
| Silicom             | 1        | 1.54%   |
| Secudos             | 1        | 1.54%   |
| Purism              | 1        | 1.54%   |
| NEXCOM              | 1        | 1.54%   |
| Intel               | 1        | 1.54%   |
| Biostar             | 1        | 1.54%   |
| AAEON               | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 12       | 18.46%  |
| PC Engines apu4                             | 5        | 7.69%   |
| PC Engines APU2                             | 4        | 6.15%   |
| Shuttle DS10U                               | 2        | 3.08%   |
| Protectli FW4B                              | 2        | 3.08%   |
| Fujitsu ESPRIMO C720                        | 2        | 3.08%   |
| Winston Marriot PICO PC  PICOPC             | 1        | 1.54%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM   | 1        | 1.54%   |
| Shuttle DH170                               | 1        | 1.54%   |
| SeeedStudio ODYSSEY-X86J4125                | 1        | 1.54%   |
| SeeedStudio ODYSSEY-X86J4105                | 1        | 1.54%   |
| Purism Librem Mini v2                       | 1        | 1.54%   |
| Protectli FW6E                              | 1        | 1.54%   |
| NEXCOM ASG                                  | 1        | 1.54%   |
| Lenovo ThinkPad T400 2768W3A                | 1        | 1.54%   |
| Lenovo ThinkCentre M93p 10AB003CGE          | 1        | 1.54%   |
| Lenovo ThinkCentre M92P 3237CK4             | 1        | 1.54%   |
| Lenovo ThinkCentre M73 10B4S03V05           | 1        | 1.54%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE     | 1        | 1.54%   |
| Intel Q3XXG4-P V1.0                         | 1        | 1.54%   |
| HP ProDesk 600 G2 SFF                       | 1        | 1.54%   |
| HP EliteDesk 800 G2 SFF                     | 1        | 1.54%   |
| HP Compaq Elite 8300 SFF                    | 1        | 1.54%   |
| HP Compaq 8200 Elite SFF PC                 | 1        | 1.54%   |
| Gigabyte H81M-S2PV                          | 1        | 1.54%   |
| Gigabyte B365M DS3H                         | 1        | 1.54%   |
| Gigabyte B150-HD3P-CF                       | 1        | 1.54%   |
| Fujitsu ESPRIMO C910                        | 1        | 1.54%   |
| Dell PowerEdge R610                         | 1        | 1.54%   |
| Dell PowerEdge 1950                         | 1        | 1.54%   |
| Dell OptiPlex 790                           | 1        | 1.54%   |
| Dell OptiPlex 7040                          | 1        | 1.54%   |
| Dell OptiPlex 5040                          | 1        | 1.54%   |
| Biostar N3050NH                             | 1        | 1.54%   |
| BESSTAR Tech X35G                           | 1        | 1.54%   |
| BESSTAR Tech UM270                          | 1        | 1.54%   |
| BESSTAR Tech UM250                          | 1        | 1.54%   |
| ASUS PRIME B350M-A                          | 1        | 1.54%   |
| ASUS P8H77-M PRO                            | 1        | 1.54%   |
| ASUS 1HE Intel Single-CPU RI1101H-XE Server | 1        | 1.54%   |
| ASRock TRX40 Taichi                         | 1        | 1.54%   |
| ASRock H510M-HDV/M.2                        | 1        | 1.54%   |
| ASRock B460M Pro4                           | 1        | 1.54%   |
| AAEON UP-APL01                              | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 12       | 18.46%  |
| PC Engines apu4              | 5        | 7.69%   |
| PC Engines apu2              | 4        | 6.15%   |
| Lenovo ThinkCentre           | 3        | 4.62%   |
| Fujitsu ESPRIMO              | 3        | 4.62%   |
| Dell OptiPlex                | 3        | 4.62%   |
| Shuttle DS10U                | 2        | 3.08%   |
| Protectli FW4B               | 2        | 3.08%   |
| HP Compaq                    | 2        | 3.08%   |
| Dell PowerEdge               | 2        | 3.08%   |
| Winston Marriot PICO         | 1        | 1.54%   |
| Silicom Minnowboard          | 1        | 1.54%   |
| Shuttle DH170                | 1        | 1.54%   |
| SeeedStudio ODYSSEY-X86J4125 | 1        | 1.54%   |
| SeeedStudio ODYSSEY-X86J4105 | 1        | 1.54%   |
| Purism Librem                | 1        | 1.54%   |
| Protectli FW6E               | 1        | 1.54%   |
| NEXCOM ASG                   | 1        | 1.54%   |
| Lenovo ThinkPad              | 1        | 1.54%   |
| Lenovo IdeaCentre            | 1        | 1.54%   |
| Intel Q3XXG4-P               | 1        | 1.54%   |
| HP ProDesk                   | 1        | 1.54%   |
| HP EliteDesk                 | 1        | 1.54%   |
| Gigabyte H81M-S2PV           | 1        | 1.54%   |
| Gigabyte B365M               | 1        | 1.54%   |
| Gigabyte B150-HD3P-CF        | 1        | 1.54%   |
| Biostar N3050NH              | 1        | 1.54%   |
| BESSTAR Tech X35G            | 1        | 1.54%   |
| BESSTAR Tech UM270           | 1        | 1.54%   |
| BESSTAR Tech UM250           | 1        | 1.54%   |
| ASUS PRIME                   | 1        | 1.54%   |
| ASUS P8H77-M                 | 1        | 1.54%   |
| ASUS 1HE                     | 1        | 1.54%   |
| ASRock TRX40                 | 1        | 1.54%   |
| ASRock H510M-HDV             | 1        | 1.54%   |
| ASRock B460M                 | 1        | 1.54%   |
| AAEON UP-APL01               | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 10       | 15.38%  |
| 2021    | 9        | 13.85%  |
| 2018    | 9        | 13.85%  |
| 2016    | 9        | 13.85%  |
| 2019    | 6        | 9.23%   |
| 2017    | 5        | 7.69%   |
| 2015    | 5        | 7.69%   |
| 2013    | 3        | 4.62%   |
| 2012    | 3        | 4.62%   |
| 2011    | 2        | 3.08%   |
| 2014    | 1        | 1.54%   |
| 2009    | 1        | 1.54%   |
| 2007    | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 53       | 81.54%  |
| Yes  | 12       | 18.46%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 24       | 36.36%  |
| 4.01-8.0        | 17       | 25.76%  |
| 16.01-24.0      | 13       | 19.7%   |
| 32.01-64.0      | 4        | 6.06%   |
| 2.01-3.0        | 4        | 6.06%   |
| More than 256.0 | 1        | 1.52%   |
| 3.01-4.0        | 1        | 1.52%   |
| 24.01-32.0      | 1        | 1.52%   |
| 64.01-256.0     | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 42       | 61.76%  |
| 0.51-1.0   | 18       | 26.47%  |
| 1.01-2.0   | 4        | 5.88%   |
| 4.01-8.0   | 1        | 1.47%   |
| 32.01-64.0 | 1        | 1.47%   |
| 3.01-4.0   | 1        | 1.47%   |
| 2.01-3.0   | 1        | 1.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 54       | 79.41%  |
| 2      | 8        | 11.76%  |
| 0      | 5        | 7.35%   |
| 3      | 1        | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 90.91%  |
| Yes       | 6        | 9.09%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 65       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 75.76%  |
| Yes       | 16       | 24.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 55       | 84.62%  |
| Yes       | 10       | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 65       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Vienna                   | 29       | 40.85%  |
| Graz                     | 9        | 12.68%  |
| Linz                     | 3        | 4.23%   |
| Sankt Veit an der Glan   | 2        | 2.82%   |
| Innsbruck                | 2        | 2.82%   |
| Voggenberg               | 1        | 1.41%   |
| Tulln                    | 1        | 1.41%   |
| Stockerau                | 1        | 1.41%   |
| Steyr                    | 1        | 1.41%   |
| Spittal an der Drau      | 1        | 1.41%   |
| Siegendorf im Burgenland | 1        | 1.41%   |
| Schwechat                | 1        | 1.41%   |
| Sankt PÃ¶lten          | 1        | 1.41%   |
| Salzburg                 | 1        | 1.41%   |
| Purkersdorf              | 1        | 1.41%   |
| Pichl bei Wels           | 1        | 1.41%   |
| Oberpullendorf           | 1        | 1.41%   |
| Neulengbach              | 1        | 1.41%   |
| Maria-Anzbach            | 1        | 1.41%   |
| Margarethen am Moos      | 1        | 1.41%   |
| Leogang                  | 1        | 1.41%   |
| Leoben                   | 1        | 1.41%   |
| Hoerndl                  | 1        | 1.41%   |
| Ferndorf                 | 1        | 1.41%   |
| Euratsfeld               | 1        | 1.41%   |
| Enzenreith               | 1        | 1.41%   |
| Eisenstadt               | 1        | 1.41%   |
| Bruck an der Mur         | 1        | 1.41%   |
| Breitenfurt bei Wien     | 1        | 1.41%   |
| Birkfeld                 | 1        | 1.41%   |
| Ansfelden                | 1        | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 12       | 21     | 17.14%  |
| Transcend           | 11       | 11     | 15.71%  |
| Crucial             | 7        | 8      | 10%     |
| Kingston            | 5        | 6      | 7.14%   |
| WDC                 | 4        | 5      | 5.71%   |
| Phison              | 4        | 5      | 5.71%   |
| Seagate             | 3        | 7      | 4.29%   |
| SanDisk             | 3        | 8      | 4.29%   |
| Hoodisk             | 3        | 4      | 4.29%   |
| Toshiba             | 2        | 2      | 2.86%   |
| Intel               | 2        | 3      | 2.86%   |
| FORESEE             | 2        | 2      | 2.86%   |
| Dell                | 2        | 2      | 2.86%   |
| Corsair             | 2        | 3      | 2.86%   |
| China               | 2        | 2      | 2.86%   |
| SK Hynix            | 1        | 1      | 1.43%   |
| KingSpec            | 1        | 1      | 1.43%   |
| Hitachi             | 1        | 1      | 1.43%   |
| HGST                | 1        | 3      | 1.43%   |
| GOODRAM             | 1        | 1      | 1.43%   |
| A-DATA Technology   | 1        | 3      | 1.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 250GB                | 5        | 7.04%   |
| Transcend TS128GMSA230S 128GB            | 4        | 5.63%   |
| Crucial CT240BX500SSD1 240GB             | 3        | 4.23%   |
| Transcend TS16GMSA370 16GB               | 2        | 2.82%   |
| Phison SATA SSD 16GB                     | 2        | 2.82%   |
| Kingston SUV500MS120G 120GB              | 2        | 2.82%   |
| Hoodisk SSD 64GB                         | 2        | 2.82%   |
| FORESEE 128GB SSD                        | 2        | 2.82%   |
| Crucial CT250MX500SSD1 250GB             | 2        | 2.82%   |
| WDC WD1600BEVS-00UST0 160GB              | 1        | 1.41%   |
| WDC WD120EFBX-68B0EN0 12TB               | 1        | 1.41%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1        | 1.41%   |
| WDC WD Elements 25A1 4TB                 | 1        | 1.41%   |
| Transcend TS64GMSA370 64GB               | 1        | 1.41%   |
| Transcend TS64GMSA230S 64GB              | 1        | 1.41%   |
| Transcend TS256GMSA370 256GB             | 1        | 1.41%   |
| Transcend TS256GMSA230S 256GB            | 1        | 1.41%   |
| Transcend TS240GSSD220S 240GB            | 1        | 1.41%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.41%   |
| Toshiba MK3276GSX -63 320GB              | 1        | 1.41%   |
| SK Hynix SC308 SATA 128GB                | 1        | 1.41%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1.41%   |
| Seagate ST3160318AS 160GB                | 1        | 1.41%   |
| Seagate BarraCuda SSD ZA250CM10002 250GB | 1        | 1.41%   |
| SanDisk X400 M.2 2280 128GB              | 1        | 1.41%   |
| SanDisk SSD PLUS 120GB                   | 1        | 1.41%   |
| SanDisk SD8SBAT-256G-1006 256GB          | 1        | 1.41%   |
| Samsung SSD 980 250GB                    | 1        | 1.41%   |
| Samsung SSD 970 PRO 1TB                  | 1        | 1.41%   |
| Samsung SSD 970 EVO Plus 250GB           | 1        | 1.41%   |
| Samsung SSD 860 PRO 256GB                | 1        | 1.41%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.41%   |
| Samsung SSD 850 EVO 250GB                | 1        | 1.41%   |
| Samsung SSD 830 Series 256GB             | 1        | 1.41%   |
| Phison SATA SSD 64GB                     | 1        | 1.41%   |
| Phison minisforum 512GB                  | 1        | 1.41%   |
| Kingston SHFS37A120G 120GB               | 1        | 1.41%   |
| Kingston SA400S37240G 240GB              | 1        | 1.41%   |
| Kingston OM8P0S3512F-00 512GB            | 1        | 1.41%   |
| Kingston OM8P0S3256B-A0 256GB            | 1        | 1.41%   |
| KingSpec NT-32 32GB                      | 1        | 1.41%   |
| Intel SSDSC2KB240G8 240GB                | 1        | 1.41%   |
| Intel SSDSA2CW160G3 160GB                | 1        | 1.41%   |
| Hoodisk SSD 32GB                         | 1        | 1.41%   |
| Hitachi HDS721050CLA660 500GB            | 1        | 1.41%   |
| HGST HTS725050A7E630 500GB               | 1        | 1.41%   |
| GOODRAM SSDPR-CX400-256-G2 256GB         | 1        | 1.41%   |
| Dell PERC H700 304GB                     | 1        | 1.41%   |
| Dell PERC 5-i 499GB                      | 1        | 1.41%   |
| Crucial CT500MX500SSD1 500GB             | 1        | 1.41%   |
| Crucial CT120BX500SSD1 120GB             | 1        | 1.41%   |
| Corsair Force MP600 2TB                  | 1        | 1.41%   |
| Corsair Force MP510 240GB                | 1        | 1.41%   |
| China SATA SSD 64GB                      | 1        | 1.41%   |
| China Msata-64GB                         | 1        | 1.41%   |
| A-DATA SX6000LNP 128GB                   | 1        | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 5      | 33.33%  |
| Toshiba | 2        | 2      | 16.67%  |
| Seagate | 2        | 2      | 16.67%  |
| Dell    | 2        | 2      | 16.67%  |
| Hitachi | 1        | 1      | 8.33%   |
| HGST    | 1        | 3      | 8.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 11       | 11     | 21.57%  |
| Samsung Electronics | 9        | 14     | 17.65%  |
| Crucial             | 7        | 8      | 13.73%  |
| Kingston            | 5        | 6      | 9.8%    |
| SanDisk             | 3        | 8      | 5.88%   |
| Phison              | 3        | 4      | 5.88%   |
| Hoodisk             | 3        | 4      | 5.88%   |
| Intel               | 2        | 3      | 3.92%   |
| FORESEE             | 2        | 2      | 3.92%   |
| China               | 2        | 2      | 3.92%   |
| SK Hynix            | 1        | 1      | 1.96%   |
| Seagate             | 1        | 5      | 1.96%   |
| KingSpec            | 1        | 1      | 1.96%   |
| GOODRAM             | 1        | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 50       | 70     | 73.53%  |
| HDD  | 11       | 15     | 16.18%  |
| NVMe | 7        | 14     | 10.29%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 57       | 85     | 89.06%  |
| NVMe | 7        | 14     | 10.94%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 54       | 78     | 90%     |
| 0.51-1.0   | 3        | 3      | 5%      |
| 3.01-4.0   | 1        | 1      | 1.67%   |
| 10.01-20.0 | 1        | 2      | 1.67%   |
| 4.01-10.0  | 1        | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 38       | 56.72%  |
| 251-500    | 9        | 13.43%  |
| 21-50      | 8        | 11.94%  |
| 51-100     | 5        | 7.46%   |
| 1-20       | 4        | 5.97%   |
| 501-1000   | 2        | 2.99%   |
| 1001-2000  | 1        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 62       | 95.38%  |
| 21-50    | 1        | 1.54%   |
| 101-250  | 1        | 1.54%   |
| 501-1000 | 1        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1600BEVS-00UST0 160GB   | 1        | 1      | 25%     |
| SK Hynix SC308 SATA 128GB     | 1        | 1      | 25%     |
| Hitachi HDS721050CLA660 500GB | 1        | 1      | 25%     |
| HGST HTS725050A7E630 500GB    | 1        | 3      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 25%     |
| SK Hynix | 1        | 1      | 25%     |
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
| Works    | 58       | 90     | 92.06%  |
| Malfunc  | 3        | 6      | 4.76%   |
| Detected | 2        | 3      | 3.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 50       | 65.79%  |
| AMD                      | 14       | 18.42%  |
| Samsung Electronics      | 3        | 3.95%   |
| Phison Electronics       | 3        | 3.95%   |
| Broadcom / LSI           | 2        | 2.63%   |
| Realtek Semiconductor    | 1        | 1.32%   |
| Marvell Technology Group | 1        | 1.32%   |
| Hewlett-Packard          | 1        | 1.32%   |
| Dell                     | 1        | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 11       | 13.58%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 9.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7        | 8.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5        | 6.17%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4        | 4.94%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4        | 4.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 3.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2        | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2        | 2.47%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 1.23%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 1.23%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 1.23%   |
| Phison E12 NVMe Controller                                                       | 1        | 1.23%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                            | 1        | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1        | 1.23%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1        | 1.23%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1        | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.23%   |
| Intel 631xESB/632xESB IDE Controller                                             | 1        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.23%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 1        | 1.23%   |
| HP Smart Array G6 controllers                                                    | 1        | 1.23%   |
| Dell PowerEdge Expandable RAID controller 5                                      | 1        | 1.23%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.23%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 1        | 1.23%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                     | 1        | 1.23%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 1.23%   |
| Unknown                                                                          | 1        | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 58       | 74.36%  |
| NVMe | 7        | 8.97%   |
| IDE  | 7        | 8.97%   |
| RAID | 4        | 5.13%   |
| SAS  | 1        | 1.28%   |
| SCSI | 1        | 1.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 51       | 78.46%  |
| AMD    | 14       | 21.54%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                | 9        | 13.85%  |
| Intel Celeron CPU J3160 @ 1.60GHz               | 6        | 9.23%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 2        | 3.08%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 2        | 3.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2        | 3.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2        | 3.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 2        | 3.08%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2        | 3.08%   |
| Intel Xeon CPU E5320 @ 1.86GHz                  | 1        | 1.54%   |
| Intel Pentium CPU G4400 @ 3.30GHz               | 1        | 1.54%   |
| Intel Genuine CPU 0000 @ 2.40GHz                | 1        | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1        | 1.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1        | 1.54%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1        | 1.54%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1        | 1.54%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1        | 1.54%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 1        | 1.54%   |
| Intel Core i5-4590T CPU @ 2.00GHz               | 1        | 1.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1        | 1.54%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 1        | 1.54%   |
| Intel Core i5-3470T CPU @ 2.90GHz               | 1        | 1.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.54%   |
| Intel Core i5-2400S CPU @ 2.50GH                | 1        | 1.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 1        | 1.54%   |
| Intel Core i5-10400F CPU @ 2.90GHz              | 1        | 1.54%   |
| Intel Core i3-9100F CPU @ 3.60GHz               | 1        | 1.54%   |
| Intel Core i3-9100 CPU @ 3.60GHz                | 1        | 1.54%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1        | 1.54%   |
| Intel Core i3-6100T CPU @ 3.20GHz               | 1        | 1.54%   |
| Intel Core i3-10105 CPU @ 3.70GHz               | 1        | 1.54%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 1        | 1.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 1        | 1.54%   |
| Intel Core 2 Duo                                | 1        | 1.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 1        | 1.54%   |
| Intel Celeron J4105 CPU @ 1.50GHz               | 1        | 1.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 1        | 1.54%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 1        | 1.54%   |
| Intel Celeron CPU 4205U @ 1.80GHz               | 1        | 1.54%   |
| Intel Atom CPU E3845 @ 1.91GHz                  | 1        | 1.54%   |
| Intel Atom CPU C3558 @ 2.20GHz                  | 1        | 1.54%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor  | 1        | 1.54%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx   | 1        | 1.54%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 1        | 1.54%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1        | 1.54%   |
| AMD A9-9430 RADEON R5, 5 COMPUTE CORES 2C+3G    | 1        | 1.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 16       | 24.62%  |
| Intel Celeron          | 11       | 16.92%  |
| AMD GX                 | 9        | 13.85%  |
| Intel Core i3          | 8        | 12.31%  |
| Intel Core i7          | 5        | 7.69%   |
| Intel Xeon             | 3        | 4.62%   |
| Intel Pentium          | 3        | 4.62%   |
| Intel Core 2 Duo       | 2        | 3.08%   |
| Intel Atom             | 2        | 3.08%   |
| AMD Ryzen 7            | 2        | 3.08%   |
| Other                  | 1        | 1.54%   |
| Intel Genuine          | 1        | 1.54%   |
| AMD Ryzen Threadripper | 1        | 1.54%   |
| AMD Ryzen 5 PRO        | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 41       | 63.08%  |
| 2       | 15       | 23.08%  |
| 8       | 4        | 6.15%   |
| Unknown | 2        | 3.08%   |
| 64      | 1        | 1.54%   |
| 16      | 1        | 1.54%   |
| 6       | 1        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 61       | 93.85%  |
| 2       | 2        | 3.08%   |
| Unknown | 2        | 3.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 43       | 66.15%  |
| 2       | 20       | 30.77%  |
| Unknown | 2        | 3.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 11       | 16.92%  |
| Puma          | 9        | 13.85%  |
| Skylake       | 8        | 12.31%  |
| Silvermont    | 8        | 12.31%  |
| Haswell       | 6        | 9.23%   |
| IvyBridge     | 4        | 6.15%   |
| Zen           | 3        | 4.62%   |
| Westmere      | 2        | 3.08%   |
| SandyBridge   | 2        | 3.08%   |
| Penryn        | 2        | 3.08%   |
| Goldmont plus | 2        | 3.08%   |
| Goldmont      | 2        | 3.08%   |
| CometLake     | 2        | 3.08%   |
| Zen 2         | 1        | 1.54%   |
| IceLake       | 1        | 1.54%   |
| Excavator     | 1        | 1.54%   |
| Core          | 1        | 1.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 45       | 83.33%  |
| AMD                        | 5        | 9.26%   |
| Nvidia                     | 2        | 3.7%    |
| Matrox Electronics Systems | 1        | 1.85%   |
| ASPEED Technology          | 1        | 1.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7        | 12.96%  |
| Intel HD Graphics 530                                                                    | 6        | 11.11%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 5.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 5.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3        | 5.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3        | 5.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2        | 3.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 3.7%    |
| AMD ES1000                                                                               | 2        | 3.7%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.85%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.85%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 1.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 1.85%   |
| Intel HD Graphics 630                                                                    | 1        | 1.85%   |
| Intel HD Graphics 620                                                                    | 1        | 1.85%   |
| Intel HD Graphics 510                                                                    | 1        | 1.85%   |
| Intel HD Graphics 500                                                                    | 1        | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.85%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.85%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.85%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1        | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 43       | 66.15%  |
| Other      | 11       | 16.92%  |
| 1 x AMD    | 5        | 7.69%   |
| 2 x Intel  | 2        | 3.08%   |
| 1 x Nvidia | 2        | 3.08%   |
| 1 x Matrox | 1        | 1.54%   |
| 1 x ASPEED | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 53       | 81.54%  |
| Unknown     | 11       | 16.92%  |
| Proprietary | 1        | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 64       | 98.46%  |
| 1.01-2.0   | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 33.33%  |
| Philips             | 2        | 33.33%  |
| Medion              | 1        | 16.67%  |
| Lenovo              | 1        | 16.67%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1        | 16.67%  |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1        | 16.67%  |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1        | 16.67%  |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 16.67%  |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1        | 16.67%  |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1        | 16.67%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2        | 33.33%  |
| 3840x2160 (4K)     | 1        | 16.67%  |
| 3840x1080          | 1        | 16.67%  |
| 1680x1050 (WSXGA+) | 1        | 16.67%  |
| 1440x900 (WXGA+)   | 1        | 16.67%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 40      | 1        | 16.67%  |
| 31      | 1        | 16.67%  |
| 27      | 1        | 16.67%  |
| 20      | 1        | 16.67%  |
| 14      | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 801-900     | 1        | 16.67%  |
| 601-700     | 1        | 16.67%  |
| 501-600     | 1        | 16.67%  |
| 401-500     | 1        | 16.67%  |
| 201-300     | 1        | 16.67%  |
| Unknown     | 1        | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 3        | 50%     |
| 16/10 | 2        | 33.33%  |
| 32/9  | 1        | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 81-90          | 1        | 16.67%  |
| 351-500        | 1        | 16.67%  |
| 301-350        | 1        | 16.67%  |
| 151-200        | 1        | 16.67%  |
| 501-1000       | 1        | 16.67%  |
| Unknown        | 1        | 16.67%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3        | 50%     |
| 121-160 | 1        | 16.67%  |
| 101-120 | 1        | 16.67%  |
| Unknown | 1        | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 60       | 92.31%  |
| 1     | 4        | 6.15%   |
| 2     | 1        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 53       | 63.1%   |
| Realtek Semiconductor | 19       | 22.62%  |
| Broadcom              | 3        | 3.57%   |
| Qualcomm Atheros      | 2        | 2.38%   |
| LG Electronics        | 2        | 2.38%   |
| TP-Link               | 1        | 1.19%   |
| Seeed Technology      | 1        | 1.19%   |
| Edimax Technology     | 1        | 1.19%   |
| Dresden Elektronik    | 1        | 1.19%   |
| Arduino SA            | 1        | 1.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 20       | 19.05%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 15       | 14.29%  |
| Intel I210 Gigabit Network Connection                                         | 13       | 12.38%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 4.76%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 3.81%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 2.86%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.9%    |
| LG Optimus Android Phone [USB tethering mode]                                 | 2        | 1.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2        | 1.9%    |
| Intel Ethernet Connection I217-V                                              | 2        | 1.9%    |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 1.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.95%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.95%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.95%   |
| Intel Wireless 7265                                                           | 1        | 0.95%   |
| Intel Wireless 7260                                                           | 1        | 0.95%   |
| Intel Ultimate N WiFi Link 5300                                               | 1        | 0.95%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 0.95%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.95%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.95%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                                | 1        | 0.95%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.95%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.95%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.95%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1        | 0.95%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                 | 1        | 0.95%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.95%   |
| Arduino SA Leonardo (CDC ACM, HID)                                            | 1        | 0.95%   |

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
| Intel                 | 50       | 72.46%  |
| Realtek Semiconductor | 16       | 23.19%  |
| Broadcom              | 3        | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 20       | 24.1%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 15       | 18.07%  |
| Intel I210 Gigabit Network Connection                                         | 13       | 15.66%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 6.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 6.02%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 4.82%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.61%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.41%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 2.41%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 2.41%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.2%    |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 1.2%    |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.2%    |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 1.2%    |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.2%    |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 1.2%    |
| Intel 82574L Gigabit Network Connection                                       | 1        | 1.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 1.2%    |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 65       | 74.71%  |
| WiFi     | 16       | 18.39%  |
| Modem    | 5        | 5.75%   |
| Unknown  | 1        | 1.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 98.44%  |
| WiFi     | 1        | 1.56%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 15       | 23.08%  |
| 4     | 14       | 21.54%  |
| 2     | 13       | 20%     |
| 6     | 7        | 10.77%  |
| 1     | 7        | 10.77%  |
| 8     | 3        | 4.62%   |
| 7     | 3        | 4.62%   |
| 5     | 3        | 4.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 96.97%  |
| Yes  | 2        | 3.03%   |

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


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 37       | 84.09%  |
| AMD    | 5        | 11.36%  |
| Nvidia | 2        | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7        | 13.73%  |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 11.76%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 5.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 5.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3        | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 5.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 3.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 3.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2        | 3.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.96%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.96%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.96%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.96%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 1.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 1        | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.96%   |
| AMD High Definition Audio Controller                                                              | 1        | 1.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1        | 1.96%   |
| Unknown                                                                                           | 1        | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 11       | 17.46%  |
| Kingston            | 10       | 15.87%  |
| Unknown             | 9        | 14.29%  |
| SK Hynix            | 7        | 11.11%  |
| Samsung Electronics | 7        | 11.11%  |
| Micron Technology   | 4        | 6.35%   |
| Unknown (ABCD)      | 3        | 4.76%   |
| Ramaxel Technology  | 2        | 3.17%   |
| G.Skill             | 2        | 3.17%   |
| Corsair             | 2        | 3.17%   |
| Transcend           | 1        | 1.59%   |
| Tigo                | 1        | 1.59%   |
| Nanya Technology    | 1        | 1.59%   |
| Kingmax             | 1        | 1.59%   |
| ATP                 | 1        | 1.59%   |
| Unknown             | 1        | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 4        | 6.15%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 3        | 4.62%   |
| SK Hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s              | 2        | 3.08%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 3.08%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 1.54%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 1.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 1        | 1.54%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                         | 1        | 1.54%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s                 | 1        | 1.54%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s             | 1        | 1.54%   |
| Tigo RAM 1600MHz-4G 4GB SODIMM DDR3 1600MT/s                      | 1        | 1.54%   |
| SK Hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.54%   |
| SK Hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.54%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.54%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.54%   |
| SK Hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s              | 1        | 1.54%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                         | 1        | 1.54%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.54%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.54%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s            | 1        | 1.54%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 2400MT/s               | 1        | 1.54%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s           | 1        | 1.54%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 1        | 1.54%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s                | 1        | 1.54%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s                | 1        | 1.54%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 1.54%   |
| Micron RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s              | 1        | 1.54%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s             | 1        | 1.54%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 1.54%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s             | 1        | 1.54%   |
| Kingston RAM KHX1600C9S3L/8G 8GB DDR3 1600MT/s                    | 1        | 1.54%   |
| Kingston RAM KF073F-ELD 2GB DIMM DDR3 1333MT/s                    | 1        | 1.54%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 1        | 1.54%   |
| Kingston RAM CBD26D4S9S1ME-8 8GB SODIMM DDR4 2667MT/s             | 1        | 1.54%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.54%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 1        | 1.54%   |
| Kingston RAM 99P5700-014.A00G 8GB SODIMM DDR4 2667MT/s            | 1        | 1.54%   |
| Kingston RAM 9905469-143.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.54%   |
| Kingmax RAM FLFE85F-C8KJ9 2GB DIMM DDR3 1333MT/s                  | 1        | 1.54%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s              | 1        | 1.54%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                | 1        | 1.54%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s             | 1        | 1.54%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s           | 1        | 1.54%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 2400MT/s              | 1        | 1.54%   |
| Crucial RAM CT8G4DFS 8192MB DIMM DDR4 2133MT/s                    | 1        | 1.54%   |
| Crucial RAM CT8G4DFD8213.C16FBD1 8GB DIMM DDR4 2133MT/s           | 1        | 1.54%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s             | 1        | 1.54%   |
| Crucial RAM CT4G4SFS824A.C8FBD1 4GB SODIMM DDR4 2400MT/s          | 1        | 1.54%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s        | 1        | 1.54%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s          | 1        | 1.54%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s          | 1        | 1.54%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2400MT/s         | 1        | 1.54%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3200MT/s               | 1        | 1.54%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s             | 1        | 1.54%   |
| Corsair RAM CMK64GX4M8Z2933C16 8GB DIMM DDR4 2133MT/s             | 1        | 1.54%   |
| ATP RAM X4C04QD8BLTDSE-7-TN1 4GB DIMM DDR4 2667MT/s               | 1        | 1.54%   |
| Unknown                                                           | 1        | 1.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 27       | 47.37%  |
| DDR4    | 24       | 42.11%  |
| LPDDR4  | 4        | 7.02%   |
| DDR2    | 1        | 1.75%   |
| Unknown | 1        | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 31       | 54.39%  |
| SODIMM       | 23       | 40.35%  |
| Unknown      | 2        | 3.51%   |
| Row Of Chips | 1        | 1.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 37.93%  |
| 4096  | 17       | 29.31%  |
| 16384 | 8        | 13.79%  |
| 2048  | 7        | 12.07%  |
| 32768 | 2        | 3.45%   |
| 1024  | 2        | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 25%     |
| 1333  | 12       | 20%     |
| 2667  | 9        | 15%     |
| 2400  | 9        | 15%     |
| 3200  | 5        | 8.33%   |
| 2133  | 4        | 6.67%   |
| 1067  | 2        | 3.33%   |
| 65535 | 1        | 1.67%   |
| 2666  | 1        | 1.67%   |
| 1033  | 1        | 1.67%   |
| 667   | 1        | 1.67%   |

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
| 1     | 26       | 39.39%  |
| 0     | 25       | 37.88%  |
| 2     | 8        | 12.12%  |
| 3     | 5        | 7.58%   |
| 5     | 1        | 1.52%   |
| 4     | 1        | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 37       | 61.67%  |
| Net/wireless             | 9        | 15%     |
| Card reader              | 6        | 10%     |
| Bluetooth                | 5        | 8.33%   |
| Sound                    | 1        | 1.67%   |
| Network                  | 1        | 1.67%   |
| Graphics card            | 1        | 1.67%   |

