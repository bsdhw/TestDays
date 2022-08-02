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

Total: 125

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso        | Netboard A10 GEN2 Model ... | [5c00da486d](https://bsd-hardware.info/?probe=5c00da486d) | Jul 29, 2022 |
| Dell          | 0T7D40 A01                  | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| MW            | GMLK-2_5G4L                 | [69c0b0d218](https://bsd-hardware.info/?probe=69c0b0d218) | Jul 29, 2022 |
| Biostar       | A10N-8800E                  | [fe4d305991](https://bsd-hardware.info/?probe=fe4d305991) | Jul 27, 2022 |
| Gigabyte      | H87-HD3                     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| MW            | GMLK-2_5G4L                 | [57da61c80c](https://bsd-hardware.info/?probe=57da61c80c) | Jul 17, 2022 |
| PC Engines    | apu4                        | [4e24f7aa5b](https://bsd-hardware.info/?probe=4e24f7aa5b) | Jul 15, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [bfbac4efa5](https://bsd-hardware.info/?probe=bfbac4efa5) | Jul 05, 2022 |
| Secudos       | Unknown                     | [beaf8ea459](https://bsd-hardware.info/?probe=beaf8ea459) | Jul 04, 2022 |
| Secudos       | Unknown                     | [e54c622459](https://bsd-hardware.info/?probe=e54c622459) | Jul 04, 2022 |
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
| OPNsense 21.7.3      | 9        | 8.65%   |
| OPNsense 22.1.1      | 7        | 6.73%   |
| OPNsense 22.1        | 5        | 4.81%   |
| OPNsense 21.1.5      | 5        | 4.81%   |
| OPNsense 21.1.4      | 5        | 4.81%   |
| OPNsense 22.1.4      | 4        | 3.85%   |
| OPNsense 21.7.7      | 4        | 3.85%   |
| OPNsense 21.7.6      | 4        | 3.85%   |
| OPNsense 21.1.3      | 4        | 3.85%   |
| OPNsense 21.1        | 4        | 3.85%   |
| OpenBSD 6.8          | 4        | 3.85%   |
| OPNsense 22.1.9      | 3        | 2.88%   |
| OPNsense 22.1.7      | 3        | 2.88%   |
| OPNsense 21.1.8      | 3        | 2.88%   |
| OPNsense 21.1.2      | 3        | 2.88%   |
| OPNsense 22.4.1      | 2        | 1.92%   |
| OPNsense 22.1.10     | 2        | 1.92%   |
| OPNsense 21.7.1      | 2        | 1.92%   |
| OPNsense 21.7        | 2        | 1.92%   |
| OPNsense 21.1.9      | 2        | 1.92%   |
| OPNsense 21.1.1      | 2        | 1.92%   |
| OPNsense 20.7.8      | 2        | 1.92%   |
| OpenBSD 7.1          | 2        | 1.92%   |
| FreeBSD 13.1         | 2        | 1.92%   |
| FreeBSD 13.0-p5      | 2        | 1.92%   |
| OPNsense 22.7        | 1        | 0.96%   |
| OPNsense 22.4.2      | 1        | 0.96%   |
| OPNsense 22.1.8      | 1        | 0.96%   |
| OPNsense 22.1.2      | 1        | 0.96%   |
| OPNsense 21.7.8      | 1        | 0.96%   |
| OPNsense 21.7.5      | 1        | 0.96%   |
| OPNsense 21.7.4      | 1        | 0.96%   |
| OPNsense 21.7.2      | 1        | 0.96%   |
| OPNsense 21.1.7      | 1        | 0.96%   |
| OPNsense 21.1.6      | 1        | 0.96%   |
| OpenBSD 7.0          | 1        | 0.96%   |
| FreeNAS 11.3-p8      | 1        | 0.96%   |
| FreeBSD 14.0-CURRENT | 1        | 0.96%   |
| FreeBSD 13.0-p3      | 1        | 0.96%   |
| FreeBSD 13.0-p11     | 1        | 0.96%   |
| FreeBSD 12.1-p7      | 1        | 0.96%   |
| FreeBSD 12.1-p10     | 1        | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| OPNsense | 64       | 81.01%  |
| OpenBSD  | 7        | 8.86%   |
| FreeBSD  | 7        | 8.86%   |
| FreeNAS  | 1        | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 78       | 98.73%  |
| i386  | 1        | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 71       | 88.75%  |
| KDE5         | 2        | 2.5%    |
| helloDesktop | 2        | 2.5%    |
| xinitrc      | 1        | 1.25%   |
| XFCE         | 1        | 1.25%   |
| TWM          | 1        | 1.25%   |
| LXQt         | 1        | 1.25%   |
| fvwm         | 1        | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 72       | 91.14%  |
| X11     | 7        | 8.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 77       | 96.25%  |
| SDDM    | 3        | 3.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 71       | 88.75%  |
| C       | 5        | 6.25%   |
| en_US   | 3        | 3.75%   |
| de_DE   | 1        | 1.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 66       | 83.54%  |
| BIOS | 13       | 16.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 57       | 71.25%  |
| Zfs     | 15       | 18.75%  |
| Ffs     | 7        | 8.75%   |
| Unknown | 1        | 1.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 68       | 86.08%  |
| MBR     | 7        | 8.86%   |
| Unknown | 4        | 5.06%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| PC Engines          | 12       | 15.19%  |
| Unknown             | 11       | 13.92%  |
| Lenovo              | 6        | 7.59%   |
| Dell                | 6        | 7.59%   |
| Protectli           | 4        | 5.06%   |
| Hewlett-Packard     | 4        | 5.06%   |
| Gigabyte Technology | 4        | 5.06%   |
| Shuttle             | 3        | 3.8%    |
| Fujitsu             | 3        | 3.8%    |
| BESSTAR Tech        | 3        | 3.8%    |
| ASUSTek Computer    | 3        | 3.8%    |
| ASRock              | 3        | 3.8%    |
| SeeedStudio         | 2        | 2.53%   |
| Secudos             | 2        | 2.53%   |
| Intel               | 2        | 2.53%   |
| Deciso              | 2        | 2.53%   |
| Biostar             | 2        | 2.53%   |
| Winston Marriot     | 1        | 1.27%   |
| Silicom             | 1        | 1.27%   |
| Purism              | 1        | 1.27%   |
| NEXCOM              | 1        | 1.27%   |
| MW                  | 1        | 1.27%   |
| MSI                 | 1        | 1.27%   |
| AAEON               | 1        | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 13       | 16.46%  |
| PC Engines apu4                             | 6        | 7.59%   |
| PC Engines APU2                             | 6        | 7.59%   |
| Protectli FW4B                              | 3        | 3.8%    |
| Shuttle DS10U                               | 2        | 2.53%   |
| Intel Q3XXG4-P V1.0                         | 2        | 2.53%   |
| Fujitsu ESPRIMO C720                        | 2        | 2.53%   |
| Deciso Netboard A10 GEN2 Model G            | 2        | 2.53%   |
| Winston Marriot PICO PC  PICOPC             | 1        | 1.27%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM   | 1        | 1.27%   |
| Shuttle DH170                               | 1        | 1.27%   |
| SeeedStudio ODYSSEY-X86J4125                | 1        | 1.27%   |
| SeeedStudio ODYSSEY-X86J4105                | 1        | 1.27%   |
| Purism Librem Mini v2                       | 1        | 1.27%   |
| Protectli FW6E                              | 1        | 1.27%   |
| NEXCOM ASG                                  | 1        | 1.27%   |
| MW GMLK-2_5G4L                              | 1        | 1.27%   |
| MSI MS-6788                                 | 1        | 1.27%   |
| Lenovo ThinkPad T400 2768W3A                | 1        | 1.27%   |
| Lenovo ThinkCentre M93p 10AB003CGE          | 1        | 1.27%   |
| Lenovo ThinkCentre M92P 3237CK4             | 1        | 1.27%   |
| Lenovo ThinkCentre M73 10B4S03V05           | 1        | 1.27%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE     | 1        | 1.27%   |
| Lenovo IdeaCentre 3 07ADA05 90MV007UGE      | 1        | 1.27%   |
| HP ProDesk 600 G2 SFF                       | 1        | 1.27%   |
| HP EliteDesk 800 G2 SFF                     | 1        | 1.27%   |
| HP Compaq Elite 8300 SFF                    | 1        | 1.27%   |
| HP Compaq 8200 Elite SFF PC                 | 1        | 1.27%   |
| Gigabyte H87-HD3                            | 1        | 1.27%   |
| Gigabyte H81M-S2PV                          | 1        | 1.27%   |
| Gigabyte B365M DS3H                         | 1        | 1.27%   |
| Gigabyte B150-HD3P-CF                       | 1        | 1.27%   |
| Fujitsu ESPRIMO C910                        | 1        | 1.27%   |
| Dell PowerEdge R610                         | 1        | 1.27%   |
| Dell PowerEdge 1950                         | 1        | 1.27%   |
| Dell OptiPlex 790                           | 1        | 1.27%   |
| Dell OptiPlex 7050                          | 1        | 1.27%   |
| Dell OptiPlex 7040                          | 1        | 1.27%   |
| Dell OptiPlex 5040                          | 1        | 1.27%   |
| Biostar N3050NH                             | 1        | 1.27%   |
| Biostar A10N-8800E                          | 1        | 1.27%   |
| BESSTAR Tech X35G                           | 1        | 1.27%   |
| BESSTAR Tech UM270                          | 1        | 1.27%   |
| BESSTAR Tech UM250                          | 1        | 1.27%   |
| ASUS PRIME B350M-A                          | 1        | 1.27%   |
| ASUS P8H77-M PRO                            | 1        | 1.27%   |
| ASUS 1HE Intel Single-CPU RI1101H-XE Server | 1        | 1.27%   |
| ASRock TRX40 Taichi                         | 1        | 1.27%   |
| ASRock H510M-HDV/M.2                        | 1        | 1.27%   |
| ASRock B460M Pro4                           | 1        | 1.27%   |
| AAEON UP-APL01                              | 1        | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 13       | 16.46%  |
| PC Engines apu4              | 6        | 7.59%   |
| PC Engines APU2              | 6        | 7.59%   |
| Dell OptiPlex                | 4        | 5.06%   |
| Protectli FW4B               | 3        | 3.8%    |
| Lenovo ThinkCentre           | 3        | 3.8%    |
| Fujitsu ESPRIMO              | 3        | 3.8%    |
| Shuttle DS10U                | 2        | 2.53%   |
| Lenovo IdeaCentre            | 2        | 2.53%   |
| Intel Q3XXG4-P               | 2        | 2.53%   |
| HP Compaq                    | 2        | 2.53%   |
| Dell PowerEdge               | 2        | 2.53%   |
| Deciso Netboard              | 2        | 2.53%   |
| Winston Marriot PICO         | 1        | 1.27%   |
| Silicom Minnowboard          | 1        | 1.27%   |
| Shuttle DH170                | 1        | 1.27%   |
| SeeedStudio ODYSSEY-X86J4125 | 1        | 1.27%   |
| SeeedStudio ODYSSEY-X86J4105 | 1        | 1.27%   |
| Purism Librem                | 1        | 1.27%   |
| Protectli FW6E               | 1        | 1.27%   |
| NEXCOM ASG                   | 1        | 1.27%   |
| MW GMLK-2                    | 1        | 1.27%   |
| MSI MS-6788                  | 1        | 1.27%   |
| Lenovo ThinkPad              | 1        | 1.27%   |
| HP ProDesk                   | 1        | 1.27%   |
| HP EliteDesk                 | 1        | 1.27%   |
| Gigabyte H87-HD3             | 1        | 1.27%   |
| Gigabyte H81M-S2PV           | 1        | 1.27%   |
| Gigabyte B365M               | 1        | 1.27%   |
| Gigabyte B150-HD3P-CF        | 1        | 1.27%   |
| Biostar N3050NH              | 1        | 1.27%   |
| Biostar A10N-8800E           | 1        | 1.27%   |
| BESSTAR Tech X35G            | 1        | 1.27%   |
| BESSTAR Tech UM270           | 1        | 1.27%   |
| BESSTAR Tech UM250           | 1        | 1.27%   |
| ASUS PRIME                   | 1        | 1.27%   |
| ASUS P8H77-M                 | 1        | 1.27%   |
| ASUS 1HE                     | 1        | 1.27%   |
| ASRock TRX40                 | 1        | 1.27%   |
| ASRock H510M-HDV             | 1        | 1.27%   |
| ASRock B460M                 | 1        | 1.27%   |
| AAEON UP-APL01               | 1        | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 13       | 16.46%  |
| 2016    | 12       | 15.19%  |
| 2018    | 11       | 13.92%  |
| 2021    | 10       | 12.66%  |
| 2019    | 7        | 8.86%   |
| 2017    | 7        | 8.86%   |
| 2015    | 6        | 7.59%   |
| 2013    | 3        | 3.8%    |
| 2012    | 3        | 3.8%    |
| 2011    | 2        | 2.53%   |
| Unknown | 2        | 2.53%   |
| 2014    | 1        | 1.27%   |
| 2009    | 1        | 1.27%   |
| 2007    | 1        | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 79       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 78.48%  |
| Yes  | 17       | 21.52%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 32       | 40%     |
| 4.01-8.0        | 20       | 25%     |
| 16.01-24.0      | 14       | 17.5%   |
| 2.01-3.0        | 5        | 6.25%   |
| 32.01-64.0      | 4        | 5%      |
| More than 256.0 | 1        | 1.25%   |
| 3.01-4.0        | 1        | 1.25%   |
| 24.01-32.0      | 1        | 1.25%   |
| 64.01-256.0     | 1        | 1.25%   |
| 1.01-2.0        | 1        | 1.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 49       | 59.76%  |
| 0.51-1.0   | 22       | 26.83%  |
| 1.01-2.0   | 5        | 6.1%    |
| 2.01-3.0   | 2        | 2.44%   |
| 4.01-8.0   | 1        | 1.22%   |
| 32.01-64.0 | 1        | 1.22%   |
| 3.01-4.0   | 1        | 1.22%   |
| 0          | 1        | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 80.49%  |
| 2      | 9        | 10.98%  |
| 0      | 5        | 6.1%    |
| 4      | 1        | 1.22%   |
| 3      | 1        | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 91.25%  |
| Yes       | 7        | 8.75%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 79       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 78.75%  |
| Yes       | 17       | 21.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 87.34%  |
| Yes       | 10       | 12.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 79       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Vienna                   | 38       | 44.71%  |
| Graz                     | 11       | 12.94%  |
| Linz                     | 3        | 3.53%   |
| Sankt Veit an der Glan   | 2        | 2.35%   |
| Innsbruck                | 2        | 2.35%   |
| Voggenberg               | 1        | 1.18%   |
| Tulln                    | 1        | 1.18%   |
| Stockerau                | 1        | 1.18%   |
| Steyr                    | 1        | 1.18%   |
| Spittal an der Drau      | 1        | 1.18%   |
| Siegendorf im Burgenland | 1        | 1.18%   |
| Schwechat                | 1        | 1.18%   |
| Schluesslberg            | 1        | 1.18%   |
| Sankt PÃ¶lten          | 1        | 1.18%   |
| Salzburg                 | 1        | 1.18%   |
| Purkersdorf              | 1        | 1.18%   |
| Poelfing                 | 1        | 1.18%   |
| Pichl bei Wels           | 1        | 1.18%   |
| Oberpullendorf           | 1        | 1.18%   |
| Neulengbach              | 1        | 1.18%   |
| Maria-Anzbach            | 1        | 1.18%   |
| Margarethen am Moos      | 1        | 1.18%   |
| Leogang                  | 1        | 1.18%   |
| Leoben                   | 1        | 1.18%   |
| Hoerndl                  | 1        | 1.18%   |
| Gmunden                  | 1        | 1.18%   |
| Ferndorf                 | 1        | 1.18%   |
| Euratsfeld               | 1        | 1.18%   |
| Enzenreith               | 1        | 1.18%   |
| Eisenstadt               | 1        | 1.18%   |
| Bruck an der Mur         | 1        | 1.18%   |
| Breitenfurt bei Wien     | 1        | 1.18%   |
| Birkfeld                 | 1        | 1.18%   |
| Ansfelden                | 1        | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 15       | 16     | 17.44%  |
| Samsung Electronics | 14       | 25     | 16.28%  |
| Crucial             | 8        | 9      | 9.3%    |
| WDC                 | 7        | 8      | 8.14%   |
| Kingston            | 5        | 6      | 5.81%   |
| Phison              | 4        | 5      | 4.65%   |
| Hoodisk             | 4        | 5      | 4.65%   |
| Seagate             | 3        | 8      | 3.49%   |
| SanDisk             | 3        | 8      | 3.49%   |
| China               | 3        | 3      | 3.49%   |
| Toshiba             | 2        | 2      | 2.33%   |
| Intel               | 2        | 3      | 2.33%   |
| FORESEE             | 2        | 2      | 2.33%   |
| Dell                | 2        | 2      | 2.33%   |
| Corsair             | 2        | 3      | 2.33%   |
| SK hynix            | 1        | 2      | 1.16%   |
| OCZ                 | 1        | 1      | 1.16%   |
| KingSpec            | 1        | 1      | 1.16%   |
| Hitachi             | 1        | 1      | 1.16%   |
| HGST                | 1        | 4      | 1.16%   |
| Goodram             | 1        | 1      | 1.16%   |
| Dogfish             | 1        | 1      | 1.16%   |
| BORY                | 1        | 1      | 1.16%   |
| BIWIN               | 1        | 1      | 1.16%   |
| A-DATA Technology   | 1        | 3      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Samsung SSD 840 EVO 250GB                | 5        | 5.68%   |
| Transcend TS128GMSA230S 128GB            | 4        | 4.55%   |
| Crucial CT240BX500SSD1 240GB             | 3        | 3.41%   |
| Transcend TS64GMSA230S 64GB              | 2        | 2.27%   |
| Transcend TS240GSSD220S 240GB            | 2        | 2.27%   |
| Transcend TS16GMSA370 16GB               | 2        | 2.27%   |
| Transcend TS128GMSA370 128GB             | 2        | 2.27%   |
| Phison SATA SSD 16GB                     | 2        | 2.27%   |
| Kingston SUV500MS120G 120GB              | 2        | 2.27%   |
| Hoodisk SSD 64GB                         | 2        | 2.27%   |
| FORESEE 128GB SSD                        | 2        | 2.27%   |
| Crucial CT250MX500SSD1 250GB             | 2        | 2.27%   |
| China SATA SSD 64GB                      | 2        | 2.27%   |
| WDC WD800JD-60LSA5 80GB                  | 1        | 1.14%   |
| WDC WD1600BEVS-00UST0 160GB              | 1        | 1.14%   |
| WDC WD120EFBX-68B0EN0 12TB               | 1        | 1.14%   |
| WDC WD10JPVT-75A1YT0 1TB                 | 1        | 1.14%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1        | 1.14%   |
| WDC WD Elements 25A1 4TB                 | 1        | 1.14%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB     | 1        | 1.14%   |
| Transcend TS64GMSA370 64GB               | 1        | 1.14%   |
| Transcend TS256GMSA370 256GB             | 1        | 1.14%   |
| Transcend TS256GMSA230S 256GB            | 1        | 1.14%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 1.14%   |
| Toshiba MK3276GSX -63 320GB              | 1        | 1.14%   |
| SK hynix SC308 SATA 128GB                | 1        | 1.14%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1.14%   |
| Seagate ST3160318AS 160GB                | 1        | 1.14%   |
| Seagate BarraCuda SSD ZA250CM10002 250GB | 1        | 1.14%   |
| SanDisk X400 M.2 2280 128GB              | 1        | 1.14%   |
| SanDisk SSD PLUS 120GB                   | 1        | 1.14%   |
| SanDisk SD8SBAT-256G-1006 256GB          | 1        | 1.14%   |
| Samsung SSD 980 250GB                    | 1        | 1.14%   |
| Samsung SSD 970 PRO 1TB                  | 1        | 1.14%   |
| Samsung SSD 970 EVO Plus 2TB             | 1        | 1.14%   |
| Samsung SSD 970 EVO Plus 250GB           | 1        | 1.14%   |
| Samsung SSD 870 QVO 2TB                  | 1        | 1.14%   |
| Samsung SSD 860 PRO 256GB                | 1        | 1.14%   |
| Samsung SSD 860 EVO 500GB                | 1        | 1.14%   |
| Samsung SSD 860 EVO 250GB                | 1        | 1.14%   |
| Samsung SSD 850 EVO 250GB                | 1        | 1.14%   |
| Samsung SSD 830 Series 256GB             | 1        | 1.14%   |
| Phison SATA SSD 64GB                     | 1        | 1.14%   |
| Phison minisforum 512GB                  | 1        | 1.14%   |
| OCZ VERTEX3 120GB                        | 1        | 1.14%   |
| Kingston SHFS37A120G 120GB               | 1        | 1.14%   |
| Kingston SA400S37240G 240GB              | 1        | 1.14%   |
| Kingston OM8P0S3512F-00 512GB            | 1        | 1.14%   |
| Kingston OM8P0S3256B-A0 256GB            | 1        | 1.14%   |
| KingSpec NT-32 32GB                      | 1        | 1.14%   |
| Intel SSDSC2KB240G8 240GB                | 1        | 1.14%   |
| Intel SSDSA2CW160G3 160GB                | 1        | 1.14%   |
| Hoodisk SSD 32GB                         | 1        | 1.14%   |
| Hoodisk SSD 128GB                        | 1        | 1.14%   |
| Hitachi HDS721050CLA660 500GB            | 1        | 1.14%   |
| HGST HTS725050A7E630 500GB               | 1        | 1.14%   |
| Goodram SSDPR-CX400-256-G2 256GB         | 1        | 1.14%   |
| Dogfish SSD 16GB                         | 1        | 1.14%   |
| Dell PERC H700 304GB                     | 1        | 1.14%   |
| Dell PERC 5-i 499GB                      | 1        | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 42.86%  |
| Toshiba | 2        | 2      | 14.29%  |
| Seagate | 2        | 2      | 14.29%  |
| Dell    | 2        | 2      | 14.29%  |
| Hitachi | 1        | 1      | 7.14%   |
| HGST    | 1        | 4      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 15       | 16     | 23.44%  |
| Samsung Electronics | 11       | 16     | 17.19%  |
| Crucial             | 8        | 9      | 12.5%   |
| Kingston            | 5        | 6      | 7.81%   |
| Hoodisk             | 4        | 5      | 6.25%   |
| SanDisk             | 3        | 8      | 4.69%   |
| Phison              | 3        | 4      | 4.69%   |
| China               | 3        | 3      | 4.69%   |
| Intel               | 2        | 3      | 3.13%   |
| FORESEE             | 2        | 2      | 3.13%   |
| SK hynix            | 1        | 2      | 1.56%   |
| Seagate             | 1        | 6      | 1.56%   |
| OCZ                 | 1        | 1      | 1.56%   |
| KingSpec            | 1        | 1      | 1.56%   |
| Goodram             | 1        | 1      | 1.56%   |
| Dogfish             | 1        | 1      | 1.56%   |
| BORY                | 1        | 1      | 1.56%   |
| BIWIN               | 1        | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 62       | 86     | 73.81%  |
| HDD  | 13       | 18     | 15.48%  |
| NVMe | 9        | 17     | 10.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 104    | 88.61%  |
| NVMe | 9        | 17     | 11.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 66       | 95     | 89.19%  |
| 0.51-1.0   | 4        | 4      | 5.41%   |
| 3.01-4.0   | 1        | 1      | 1.35%   |
| 10.01-20.0 | 1        | 2      | 1.35%   |
| 1.01-2.0   | 1        | 1      | 1.35%   |
| 4.01-10.0  | 1        | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 45       | 55.56%  |
| 251-500    | 10       | 12.35%  |
| 21-50      | 10       | 12.35%  |
| 51-100     | 7        | 8.64%   |
| 1-20       | 5        | 6.17%   |
| 501-1000   | 3        | 3.7%    |
| 1001-2000  | 1        | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 76       | 96.2%   |
| 21-50    | 1        | 1.27%   |
| 101-250  | 1        | 1.27%   |
| 501-1000 | 1        | 1.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1600BEVS-00UST0 160GB   | 1        | 1      | 25%     |
| SK hynix SC308 SATA 128GB     | 1        | 2      | 25%     |
| Hitachi HDS721050CLA660 500GB | 1        | 1      | 25%     |
| HGST HTS725050A7E630 500GB    | 1        | 4      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 25%     |
| SK hynix | 1        | 2      | 25%     |
| Hitachi  | 1        | 1      | 25%     |
| HGST     | 1        | 4      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Hitachi | 1        | 1      | 33.33%  |
| HGST    | 1        | 4      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 6      | 75%     |
| SSD  | 1        | 2      | 25%     |

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
| Works    | 71       | 109    | 92.21%  |
| Detected | 3        | 4      | 3.9%    |
| Malfunc  | 3        | 8      | 3.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 57       | 61.96%  |
| AMD                      | 21       | 22.83%  |
| Samsung Electronics      | 4        | 4.35%   |
| Phison Electronics       | 3        | 3.26%   |
| Broadcom / LSI           | 2        | 2.17%   |
| SanDisk                  | 1        | 1.09%   |
| Realtek Semiconductor    | 1        | 1.09%   |
| Marvell Technology Group | 1        | 1.09%   |
| Hewlett-Packard          | 1        | 1.09%   |
| Dell                     | 1        | 1.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 16       | 16.49%  |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 8.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8        | 8.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6        | 6.19%   |
| AMD FCH SATA Controller [IDE mode]                                               | 6        | 6.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4        | 4.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 3.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 3.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3        | 3.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 3.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2        | 2.06%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 2        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2        | 2.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 2.06%   |
| SanDisk PC SN530                                                                 | 1        | 1.03%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 1.03%   |
| Phison PS5013 E13 NVMe Controller                                                | 1        | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 1.03%   |
| Phison E12 NVMe Controller                                                       | 1        | 1.03%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                            | 1        | 1.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1        | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1        | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1        | 1.03%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 1.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 1.03%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 1        | 1.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1        | 1.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]      | 1        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]      | 1        | 1.03%   |
| Intel 631xESB/632xESB IDE Controller                                             | 1        | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1        | 1.03%   |
| HP Smart Array G6 controllers                                                    | 1        | 1.03%   |
| Dell PowerEdge Expandable RAID controller 5                                      | 1        | 1.03%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 1        | 1.03%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                               | 1        | 1.03%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                     | 1        | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                           | 1        | 1.03%   |
| Unknown                                                                          | 1        | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 69       | 73.4%   |
| IDE  | 10       | 10.64%  |
| NVMe | 9        | 9.57%   |
| RAID | 4        | 4.26%   |
| SAS  | 1        | 1.06%   |
| SCSI | 1        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 58       | 73.42%  |
| AMD    | 21       | 26.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                       | 12       | 15.19%  |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 7        | 8.86%   |
| Intel Xeon CPU E5620 @ 2.40GHz                         | 2        | 2.53%   |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 2        | 2.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz                      | 2        | 2.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 2        | 2.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz                     | 2        | 2.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz                       | 2        | 2.53%   |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 2        | 2.53%   |
| Intel Atom CPU C3558 @ 2.20GHz                         | 2        | 2.53%   |
| AMD GX-420MC SOC                                       | 2        | 2.53%   |
| Intel Xeon CPU E5320 @ 1.86GHz                         | 1        | 1.27%   |
| Intel Pentium CPU G4400 @ 3.30GHz                      | 1        | 1.27%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class) | 1        | 1.27%   |
| Intel Genuine CPU 0000 @ 2.40GHz                       | 1        | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1        | 1.27%   |
| Intel Core i7-5550U CPU @ 2.00GHz                      | 1        | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz                       | 1        | 1.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 1        | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz                     | 1        | 1.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz                      | 1        | 1.27%   |
| Intel Core i5-7500 CPU @ 3.40GHz                       | 1        | 1.27%   |
| Intel Core i5-6600 CPU @ 3.30GHz                       | 1        | 1.27%   |
| Intel Core i5-6500T CPU @ 2.50GHz                      | 1        | 1.27%   |
| Intel Core i5-6400 CPU @ 2.70GHz                       | 1        | 1.27%   |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 1        | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1        | 1.27%   |
| Intel Core i5-3570 CPU @ 3.40GHz                       | 1        | 1.27%   |
| Intel Core i5-3470T CPU @ 2.90GHz                      | 1        | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz                       | 1        | 1.27%   |
| Intel Core i5-2400S CPU @ 2.50GH                       | 1        | 1.27%   |
| Intel Core i5-2400 CPU @ 3.10GHz                       | 1        | 1.27%   |
| Intel Core i5-10400F CPU @ 2.90GHz                     | 1        | 1.27%   |
| Intel Core i3-9100F CPU @ 3.60GHz                      | 1        | 1.27%   |
| Intel Core i3-9100 CPU @ 3.60GHz                       | 1        | 1.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz                      | 1        | 1.27%   |
| Intel Core i3-6100T CPU @ 3.20GHz                      | 1        | 1.27%   |
| Intel Core i3-10105 CPU @ 3.70GHz                      | 1        | 1.27%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                     | 1        | 1.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                   | 1        | 1.27%   |
| Intel Core 2 Duo                                       | 1        | 1.27%   |
| Intel Celeron J4105 CPU @ 1.50GHz                      | 1        | 1.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz                      | 1        | 1.27%   |
| Intel Celeron CPU N3050 @ 1.60GHz                      | 1        | 1.27%   |
| Intel Celeron CPU 4205U @ 1.80GHz                      | 1        | 1.27%   |
| Intel Atom CPU E3845 @ 1.91GHz                         | 1        | 1.27%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor         | 1        | 1.27%   |
| AMD Ryzen 7 2700U with Radeon Vega Mobile Gfx          | 1        | 1.27%   |
| AMD Ryzen 7 1700 Eight-Core Processor                  | 1        | 1.27%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx        | 1        | 1.27%   |
| AMD FX-8800P Radeon R7, 12 Compute Cores 4C+8G         | 1        | 1.27%   |
| AMD Athlon Silver 3050U with Radeon Graphics           | 1        | 1.27%   |
| AMD A9-9430 RADEON R5, 5 COMPUTE CORES 2C+3G           | 1        | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 17       | 21.52%  |
| AMD GX                 | 14       | 17.72%  |
| Intel Celeron          | 13       | 16.46%  |
| Intel Core i3          | 8        | 10.13%  |
| Intel Core i7          | 7        | 8.86%   |
| Intel Xeon             | 3        | 3.8%    |
| Intel Pentium          | 3        | 3.8%    |
| Intel Atom             | 3        | 3.8%    |
| Intel Core 2 Duo       | 2        | 2.53%   |
| AMD Ryzen 7            | 2        | 2.53%   |
| Other                  | 1        | 1.27%   |
| Intel Pentium 4        | 1        | 1.27%   |
| Intel Genuine          | 1        | 1.27%   |
| AMD Ryzen Threadripper | 1        | 1.27%   |
| AMD Ryzen 5 PRO        | 1        | 1.27%   |
| AMD FX                 | 1        | 1.27%   |
| AMD Athlon             | 1        | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 52       | 65.82%  |
| 2       | 17       | 21.52%  |
| 8       | 4        | 5.06%   |
| Unknown | 2        | 2.53%   |
| 64      | 1        | 1.27%   |
| 16      | 1        | 1.27%   |
| 6       | 1        | 1.27%   |
| 1       | 1        | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 74       | 93.67%  |
| Unknown | 3        | 3.8%    |
| 2       | 2        | 2.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 54       | 68.35%  |
| 2       | 22       | 27.85%  |
| Unknown | 3        | 3.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 14       | 17.72%  |
| KabyLake      | 12       | 15.19%  |
| Silvermont    | 9        | 11.39%  |
| Skylake       | 8        | 10.13%  |
| Haswell       | 7        | 8.86%   |
| IvyBridge     | 4        | 5.06%   |
| Zen           | 3        | 3.8%    |
| Goldmont plus | 3        | 3.8%    |
| Goldmont      | 3        | 3.8%    |
| Westmere      | 2        | 2.53%   |
| SandyBridge   | 2        | 2.53%   |
| Penryn        | 2        | 2.53%   |
| Excavator     | 2        | 2.53%   |
| CometLake     | 2        | 2.53%   |
| Zen+          | 1        | 1.27%   |
| Zen 2         | 1        | 1.27%   |
| NetBurst      | 1        | 1.27%   |
| IceLake       | 1        | 1.27%   |
| Core          | 1        | 1.27%   |
| Broadwell     | 1        | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 50       | 80.65%  |
| AMD                        | 7        | 11.29%  |
| Nvidia                     | 3        | 4.84%   |
| Matrox Electronics Systems | 1        | 1.61%   |
| ASPEED Technology          | 1        | 1.61%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 12.9%   |
| Intel HD Graphics 530                                                                    | 6        | 9.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4        | 6.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 4.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3        | 4.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3        | 4.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3        | 4.84%   |
| Intel HD Graphics 630                                                                    | 2        | 3.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2        | 3.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 3.23%   |
| AMD ES1000                                                                               | 2        | 3.23%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1        | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.61%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.61%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 1.61%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 1.61%   |
| Intel HD Graphics 620                                                                    | 1        | 1.61%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.61%   |
| Intel HD Graphics 510                                                                    | 1        | 1.61%   |
| Intel HD Graphics 500                                                                    | 1        | 1.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1        | 1.61%   |
| Intel Coffee Lake UHD 610 Graphics Controller                                            | 1        | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1        | 1.61%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.61%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 1        | 1.61%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1        | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1        | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 48       | 60.76%  |
| Other      | 17       | 21.52%  |
| 1 x AMD    | 7        | 8.86%   |
| 1 x Nvidia | 3        | 3.8%    |
| 2 x Intel  | 2        | 2.53%   |
| 1 x Matrox | 1        | 1.27%   |
| 1 x ASPEED | 1        | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 61       | 77.22%  |
| Unknown     | 17       | 21.52%  |
| Proprietary | 1        | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 98.73%  |
| 1.01-2.0   | 1        | 1.27%   |

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
| 0     | 72       | 91.14%  |
| 1     | 6        | 7.59%   |
| 2     | 1        | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 63       | 63.64%  |
| Realtek Semiconductor | 23       | 23.23%  |
| Broadcom              | 3        | 3.03%   |
| Qualcomm Atheros      | 2        | 2.02%   |
| LG Electronics        | 2        | 2.02%   |
| TP-Link               | 1        | 1.01%   |
| Seeed Technology      | 1        | 1.01%   |
| Edimax Technology     | 1        | 1.01%   |
| Dresden Elektronik    | 1        | 1.01%   |
| AVM                   | 1        | 1.01%   |
| Arduino SA            | 1        | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 24       | 19.67%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 14.75%  |
| Intel I210 Gigabit Network Connection                                         | 17       | 13.93%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 4.1%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 3.28%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 2.46%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2        | 1.64%   |
| LG Optimus Android Phone [USB tethering mode]                                 | 2        | 1.64%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2        | 1.64%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 1.64%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.64%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 1.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1        | 0.82%   |
| Seeed Seeeduino_Cortex_M0+                                                    | 1        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1        | 0.82%   |
| Intel Wireless 7265                                                           | 1        | 0.82%   |
| Intel Wireless 7260                                                           | 1        | 0.82%   |
| Intel Ultimate N WiFi Link 5300                                               | 1        | 0.82%   |
| Intel Ethernet Controller I225-V                                              | 1        | 0.82%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.82%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.82%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.82%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                | 1        | 0.82%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.82%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 0.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.82%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 1        | 0.82%   |
| Dresden Elektronik ZigBee gateway [ConBee II]                                 | 1        | 0.82%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.82%   |
| AVM A1 ISDN [Fritz]                                                           | 1        | 0.82%   |
| Arduino SA Leonardo (CDC ACM, HID)                                            | 1        | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 47.06%  |
| Realtek Semiconductor | 5        | 29.41%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| TP-Link               | 1        | 5.88%   |
| Edimax Technology     | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 17.65%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 11.76%  |
| Intel Gemini Lake PCH CNVi WiFi                                | 2        | 11.76%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 5.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 5.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 5.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 5.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 5.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 5.88%   |
| Intel Wireless 7265                                            | 1        | 5.88%   |
| Intel Wireless 7260                                            | 1        | 5.88%   |
| Intel Ultimate N WiFi Link 5300                                | 1        | 5.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 60       | 72.29%  |
| Realtek Semiconductor | 20       | 24.1%   |
| Broadcom              | 3        | 3.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel I211 Gigabit Network Connection                                         | 24       | 24.49%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 18       | 18.37%  |
| Intel I210 Gigabit Network Connection                                         | 17       | 17.35%  |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 5.1%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 4.08%   |
| Intel I350 Gigabit Network Connection                                         | 3        | 3.06%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 2.04%   |
| Intel Ethernet Connection I217-V                                              | 2        | 2.04%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 2.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.02%   |
| Intel Ethernet Controller I225-V                                              | 1        | 1.02%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 1.02%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 1.02%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 1.02%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 1.02%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 1.02%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.02%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 1.02%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 79       | 76.7%   |
| WiFi     | 17       | 16.5%   |
| Modem    | 5        | 4.85%   |
| Unknown  | 2        | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 77       | 98.72%  |
| WiFi     | 1        | 1.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 20       | 25.32%  |
| 3     | 18       | 22.78%  |
| 2     | 15       | 18.99%  |
| 1     | 9        | 11.39%  |
| 6     | 7        | 8.86%   |
| 8     | 4        | 5.06%   |
| 7     | 3        | 3.8%    |
| 5     | 3        | 3.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 96.25%  |
| Yes  | 3        | 3.75%   |

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
| Intel         | 42       | 80.77%  |
| AMD           | 7        | 13.46%  |
| Nvidia        | 2        | 3.85%   |
| Creative Labs | 1        | 1.92%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8        | 12.9%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 9.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4        | 6.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 6.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 4.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 4.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 4.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3        | 4.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 3.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 3.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2        | 3.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1        | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.61%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1        | 1.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 1.61%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 1.61%   |
| AMD High Definition Audio Controller                                                              | 1        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.61%   |
| Unknown                                                                                           | 1        | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 12       | 16.9%   |
| Unknown             | 10       | 14.08%  |
| Kingston            | 10       | 14.08%  |
| Samsung Electronics | 9        | 12.68%  |
| SK hynix            | 7        | 9.86%   |
| Micron Technology   | 5        | 7.04%   |
| Unknown (ABCD)      | 3        | 4.23%   |
| Corsair             | 3        | 4.23%   |
| Ramaxel Technology  | 2        | 2.82%   |
| G.Skill             | 2        | 2.82%   |
| Unknown             | 2        | 2.82%   |
| Transcend           | 1        | 1.41%   |
| Tigo                | 1        | 1.41%   |
| Nanya Technology    | 1        | 1.41%   |
| Kingmax             | 1        | 1.41%   |
| Kimtigo             | 1        | 1.41%   |
| ATP                 | 1        | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 5        | 6.85%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 3        | 4.11%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s              | 2        | 2.74%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2        | 2.74%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s             | 2        | 2.74%   |
| Unknown                                                           | 2        | 2.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 1        | 1.37%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1        | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 1        | 1.37%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                         | 1        | 1.37%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s                 | 1        | 1.37%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s             | 1        | 1.37%   |
| Tigo RAM 1600MHz-4G 4GB SODIMM DDR3 1600MT/s                      | 1        | 1.37%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1        | 1.37%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.37%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s              | 1        | 1.37%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s              | 1        | 1.37%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                         | 1        | 1.37%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.37%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s             | 1        | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s               | 1        | 1.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 1        | 1.37%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s             | 1        | 1.37%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 2400MT/s               | 1        | 1.37%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s           | 1        | 1.37%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s             | 1        | 1.37%   |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s                | 1        | 1.37%   |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s                | 1        | 1.37%   |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                          | 1        | 1.37%   |
| Micron RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s              | 1        | 1.37%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s              | 1        | 1.37%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s             | 1        | 1.37%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1        | 1.37%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s             | 1        | 1.37%   |
| Kingston RAM KHX1600C9S3L/8G 8GB DDR3 1600MT/s                    | 1        | 1.37%   |
| Kingston RAM KF073F-ELD 2GB DIMM DDR3 1333MT/s                    | 1        | 1.37%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 1        | 1.37%   |
| Kingston RAM CBD26D4S9S1ME-8 8GB SODIMM DDR4 2667MT/s             | 1        | 1.37%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.37%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 1        | 1.37%   |
| Kingston RAM 99P5700-014.A00G 8GB SODIMM DDR4 2667MT/s            | 1        | 1.37%   |
| Kingston RAM 9905469-143.A00LF 4GB SODIMM DDR3 1600MT/s           | 1        | 1.37%   |
| Kingmax RAM FLFE85F-C8KJ9 2GB DIMM DDR3 1333MT/s                  | 1        | 1.37%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                    | 1        | 1.37%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3200MT/s              | 1        | 1.37%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2666MT/s                | 1        | 1.37%   |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s           | 1        | 1.37%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 2400MT/s              | 1        | 1.37%   |
| Crucial RAM CT8G4DFS 8192MB DIMM DDR4 2133MT/s                    | 1        | 1.37%   |
| Crucial RAM CT8G4DFD8213.C16FBD1 8GB DIMM DDR4 2133MT/s           | 1        | 1.37%   |
| Crucial RAM CT51264BD160B.C16F 4GB DIMM DDR3 1600MT/s             | 1        | 1.37%   |
| Crucial RAM CT4G4SFS824A.C8FBD1 4GB SODIMM DDR4 2400MT/s          | 1        | 1.37%   |
| Crucial RAM CT16G4SFRA266.M16FRS 16GB SODIMM DDR4 2667MT/s        | 1        | 1.37%   |
| Crucial RAM CT16G4SFRA266.C8FE 16GB SODIMM DDR4 2667MT/s          | 1        | 1.37%   |
| Crucial RAM CT16G4SFRA266.C8FB 16GB SODIMM DDR4 2667MT/s          | 1        | 1.37%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2400MT/s         | 1        | 1.37%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3200MT/s               | 1        | 1.37%   |
| Corsair RAM CMZ32GX3M4X1866C10 8GB DIMM DDR3 1333MT/s             | 1        | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 31       | 47.69%  |
| DDR4    | 28       | 43.08%  |
| LPDDR4  | 4        | 6.15%   |
| DDR2    | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 34       | 52.31%  |
| SODIMM       | 28       | 43.08%  |
| Unknown      | 2        | 3.08%   |
| Row Of Chips | 1        | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 28       | 42.42%  |
| 4096  | 19       | 28.79%  |
| 16384 | 8        | 12.12%  |
| 2048  | 7        | 10.61%  |
| 32768 | 2        | 3.03%   |
| 1024  | 2        | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 18       | 26.47%  |
| 1333  | 13       | 19.12%  |
| 2400  | 12       | 17.65%  |
| 2667  | 9        | 13.24%  |
| 3200  | 6        | 8.82%   |
| 2133  | 4        | 5.88%   |
| 1067  | 2        | 2.94%   |
| 65535 | 1        | 1.47%   |
| 2666  | 1        | 1.47%   |
| 1033  | 1        | 1.47%   |
| 667   | 1        | 1.47%   |

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
| 1     | 33       | 40.74%  |
| 0     | 32       | 39.51%  |
| 2     | 9        | 11.11%  |
| 3     | 5        | 6.17%   |
| 5     | 1        | 1.23%   |
| 4     | 1        | 1.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 42       | 61.76%  |
| Net/wireless             | 10       | 14.71%  |
| Card reader              | 7        | 10.29%  |
| Bluetooth                | 5        | 7.35%   |
| Network                  | 2        | 2.94%   |
| Sound                    | 1        | 1.47%   |
| Graphics card            | 1        | 1.47%   |

