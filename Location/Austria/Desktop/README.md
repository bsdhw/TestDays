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

Total: 177

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ZOTAC         | Unknown                     | [f6c39a3582](https://bsd-hardware.info/?probe=f6c39a3582) | Apr 30, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | [e7e7a6470d](https://bsd-hardware.info/?probe=e7e7a6470d) | Apr 27, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | [b517729fb4](https://bsd-hardware.info/?probe=b517729fb4) | Apr 27, 2023 |
| ShenZhen M... | 3865U-6L                    | [1548471a4d](https://bsd-hardware.info/?probe=1548471a4d) | Apr 25, 2023 |
| Unknown       | Unknown                     | [0d7a1b58ed](https://bsd-hardware.info/?probe=0d7a1b58ed) | Apr 21, 2023 |
| MSI           | 2A78h                       | [8560ebd69c](https://bsd-hardware.info/?probe=8560ebd69c) | Apr 18, 2023 |
| ZOTAC         | Unknown                     | [8c3cdf29a2](https://bsd-hardware.info/?probe=8c3cdf29a2) | Apr 17, 2023 |
| Shuttle       | DS10U                       | [7f98ef1865](https://bsd-hardware.info/?probe=7f98ef1865) | Apr 10, 2023 |
| Shuttle       | FS61                        | [9c3df7e926](https://bsd-hardware.info/?probe=9c3df7e926) | Apr 09, 2023 |
| MW            | GMLK-2_5G4L                 | [8452deae22](https://bsd-hardware.info/?probe=8452deae22) | Apr 07, 2023 |
| Unknown       | Unknown                     | [11f0439894](https://bsd-hardware.info/?probe=11f0439894) | Apr 04, 2023 |
| Unknown       | Unknown                     | [9a5ccefb18](https://bsd-hardware.info/?probe=9a5ccefb18) | Mar 17, 2023 |
| Unknown       | Unknown                     | [f80047716b](https://bsd-hardware.info/?probe=f80047716b) | Mar 15, 2023 |
| Dell          | 01TN68 A02                  | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| ASUSTek       | P11C-M Series               | [80814c04b6](https://bsd-hardware.info/?probe=80814c04b6) | Mar 10, 2023 |
| ASUSTek       | P11C-M Series               | [242677230a](https://bsd-hardware.info/?probe=242677230a) | Mar 09, 2023 |
| BESSTAR Te... | TH50                        | [e27931f082](https://bsd-hardware.info/?probe=e27931f082) | Mar 07, 2023 |
| ASUSTek       | P11C-M Series               | [866573ffa0](https://bsd-hardware.info/?probe=866573ffa0) | Mar 03, 2023 |
| MW            | GMLK-2_5G4L                 | [bf21395f79](https://bsd-hardware.info/?probe=bf21395f79) | Feb 24, 2023 |
| Intel         | DENLOW_WS                   | [f6f5953979](https://bsd-hardware.info/?probe=f6f5953979) | Feb 23, 2023 |
| HP            | 3397                        | [8b231fd832](https://bsd-hardware.info/?probe=8b231fd832) | Feb 19, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [be8fb945ef](https://bsd-hardware.info/?probe=be8fb945ef) | Feb 12, 2023 |
| Intel         | ChiefRiver                  | [ae6ea07868](https://bsd-hardware.info/?probe=ae6ea07868) | Feb 05, 2023 |
| PC Engines    | APU2                        | [d59ed5b52f](https://bsd-hardware.info/?probe=d59ed5b52f) | Feb 02, 2023 |
| CncTion       | N5105-4L B0                 | [d9746ad1c3](https://bsd-hardware.info/?probe=d9746ad1c3) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | [84375af67f](https://bsd-hardware.info/?probe=84375af67f) | Jan 27, 2023 |
| Unknown       | YL-E3845L4-V2               | [d93eb933f1](https://bsd-hardware.info/?probe=d93eb933f1) | Jan 20, 2023 |
| Unknown       | Unknown                     | [22015084fc](https://bsd-hardware.info/?probe=22015084fc) | Jan 17, 2023 |
| Unknown       | Unknown                     | [87d79c88e1](https://bsd-hardware.info/?probe=87d79c88e1) | Jan 11, 2023 |
| MW            | GMLK-2_5G4L                 | [5a4affef3e](https://bsd-hardware.info/?probe=5a4affef3e) | Jan 04, 2023 |
| Hardkernel    | ODROID-H2                   | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Unknown       | Unknown                     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Techvision    | TVI7309X B0                 | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Dell          | 0T7D40 A01                  | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Gigabyte      | J3455N-D3H                  | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| PC Engines    | apu4                        | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| PC Engines    | APU2                        | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| PC Engines    | APU2                        | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Gigabyte      | J3455N-D3H                  | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Dell          | 0WMJ54 A01                  | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| MW            | GMLK-2_5G4L                 | [37cafd59eb](https://bsd-hardware.info/?probe=37cafd59eb) | Sep 20, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [e0b8ceecae](https://bsd-hardware.info/?probe=e0b8ceecae) | Sep 16, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [e082eca671](https://bsd-hardware.info/?probe=e082eca671) | Sep 08, 2022 |
| PC Engines    | APU2                        | [1650d8c419](https://bsd-hardware.info/?probe=1650d8c419) | Sep 05, 2022 |
| AAEON         | UP-APL01 V0.4               | [a8d73a9156](https://bsd-hardware.info/?probe=a8d73a9156) | Sep 01, 2022 |
| MW            | GMLK-2_5G4L                 | [63587e2fca](https://bsd-hardware.info/?probe=63587e2fca) | Aug 31, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [45043e0e42](https://bsd-hardware.info/?probe=45043e0e42) | Aug 18, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4e056b6f77](https://bsd-hardware.info/?probe=4e056b6f77) | Aug 11, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | [1cd64c78d5](https://bsd-hardware.info/?probe=1cd64c78d5) | Aug 10, 2022 |
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
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [f1dd03cdcb](https://bsd-hardware.info/?probe=f1dd03cdcb) | Feb 16, 2022 |
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


| Name             | Desktops | Percent |
|------------------|----------|---------|
| OPNsense 21.7.3  | 9        | 5.96%   |
| OPNsense 22.1.1  | 7        | 4.64%   |
| OPNsense 23.1.5  | 5        | 3.31%   |
| OPNsense 22.1    | 5        | 3.31%   |
| OPNsense 21.1.5  | 5        | 3.31%   |
| OPNsense 21.1.4  | 5        | 3.31%   |
| OPNsense 23.1    | 4        | 2.65%   |
| OPNsense 22.7.9  | 4        | 2.65%   |
| OPNsense 22.7.2  | 4        | 2.65%   |
| OPNsense 22.4.3  | 4        | 2.65%   |
| OPNsense 22.1.4  | 4        | 2.65%   |
| OPNsense 21.7.7  | 4        | 2.65%   |
| OPNsense 21.7.6  | 4        | 2.65%   |
| OPNsense 21.1.3  | 4        | 2.65%   |
| OPNsense 21.1    | 4        | 2.65%   |
| OpenBSD 6.8      | 4        | 2.65%   |
| OPNsense 23.1.6  | 3        | 1.99%   |
| OPNsense 22.7.10 | 3        | 1.99%   |
| OPNsense 22.1.9  | 3        | 1.99%   |
| OPNsense 22.1.7  | 3        | 1.99%   |
| OPNsense 22.1.10 | 3        | 1.99%   |
| OPNsense 21.1.8  | 3        | 1.99%   |
| OPNsense 21.1.2  | 3        | 1.99%   |
| OPNsense 23.4    | 2        | 1.32%   |
| OPNsense 23.1.3  | 2        | 1.32%   |
| OPNsense 23.1.1  | 2        | 1.32%   |
| OPNsense 22.7.6  | 2        | 1.32%   |
| OPNsense 22.7.4  | 2        | 1.32%   |
| OPNsense 22.7.11 | 2        | 1.32%   |
| OPNsense 22.4.1  | 2        | 1.32%   |
| OPNsense 21.7.1  | 2        | 1.32%   |
| OPNsense 21.7    | 2        | 1.32%   |
| OPNsense 21.1.9  | 2        | 1.32%   |
| OPNsense 21.1.1  | 2        | 1.32%   |
| OPNsense 20.7.8  | 2        | 1.32%   |
| OpenBSD 7.1      | 2        | 1.32%   |
| FreeBSD 13.1     | 2        | 1.32%   |
| FreeBSD 13.0-p5  | 2        | 1.32%   |
| OPNsense 23.1.2  | 1        | 0.66%   |
| OPNsense 22.7.8  | 1        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 95       | 85.59%  |
| OpenBSD     | 7        | 6.31%   |
| FreeBSD     | 7        | 6.31%   |
| helloSystem | 1        | 0.9%    |
| FreeNAS     | 1        | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 110      | 99.1%   |
| i386  | 1        | 0.9%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 102      | 91.07%  |
| helloDesktop | 3        | 2.68%   |
| KDE5         | 2        | 1.79%   |
| xinitrc      | 1        | 0.89%   |
| XFCE         | 1        | 0.89%   |
| TWM          | 1        | 0.89%   |
| LXQt         | 1        | 0.89%   |
| fvwm         | 1        | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 103      | 91.96%  |
| X11     | 8        | 7.14%   |
| Wayland | 1        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 108      | 96.43%  |
| SDDM    | 3        | 2.68%   |
| SLiM    | 1        | 0.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 100      | 88.5%   |
| C       | 8        | 7.08%   |
| en_US   | 4        | 3.54%   |
| de_DE   | 1        | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 98       | 88.29%  |
| BIOS | 13       | 11.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 73       | 65.18%  |
| Zfs     | 30       | 26.79%  |
| Ffs     | 7        | 6.25%   |
| Cd9660  | 1        | 0.89%   |
| Unknown | 1        | 0.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 100      | 90.09%  |
| MBR     | 7        | 6.31%   |
| Unknown | 4        | 3.6%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 17       | 15.32%  |
| PC Engines                 | 14       | 12.61%  |
| Dell                       | 8        | 7.21%   |
| Lenovo                     | 6        | 5.41%   |
| Deciso                     | 6        | 5.41%   |
| Gigabyte Technology        | 5        | 4.5%    |
| Shuttle                    | 4        | 3.6%    |
| Protectli                  | 4        | 3.6%    |
| MW                         | 4        | 3.6%    |
| Intel                      | 4        | 3.6%    |
| Hewlett-Packard            | 4        | 3.6%    |
| Fujitsu                    | 4        | 3.6%    |
| BESSTAR Tech               | 4        | 3.6%    |
| ASUSTek Computer           | 4        | 3.6%    |
| ASRock                     | 3        | 2.7%    |
| Techvision                 | 2        | 1.8%    |
| Secudos                    | 2        | 1.8%    |
| MSI                        | 2        | 1.8%    |
| Biostar                    | 2        | 1.8%    |
| AAEON                      | 2        | 1.8%    |
| ZOTAC                      | 1        | 0.9%    |
| Winston Marriot            | 1        | 0.9%    |
| Silicom                    | 1        | 0.9%    |
| ShenZhen MinWin Technology | 1        | 0.9%    |
| SeeedStudio                | 1        | 0.9%    |
| Seeed Studio               | 1        | 0.9%    |
| Purism                     | 1        | 0.9%    |
| NEXCOM                     | 1        | 0.9%    |
| Hardkernel                 | 1        | 0.9%    |
| CncTion                    | 1        | 0.9%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 20       | 18.02%  |
| PC Engines apu4                           | 7        | 6.31%   |
| PC Engines APU2                           | 7        | 6.31%   |
| Deciso Netboard A10 GEN2 Model G          | 6        | 5.41%   |
| MW GMLK-2_5G4L                            | 4        | 3.6%    |
| Protectli FW4B                            | 3        | 2.7%    |
| Techvision TVI7309X                       | 2        | 1.8%    |
| Shuttle DS10U                             | 2        | 1.8%    |
| Intel Q3XXG4-P V1.0                       | 2        | 1.8%    |
| Fujitsu ESPRIMO C720                      | 2        | 1.8%    |
| AAEON UP-APL01                            | 2        | 1.8%    |
| Winston Marriot PICO PC  PICOPC           | 1        | 0.9%    |
| Silicom Minnowboard Turbot D0/D1 PLATFORM | 1        | 0.9%    |
| Shuttle DS61                              | 1        | 0.9%    |
| Shuttle DH170                             | 1        | 0.9%    |
| ShenZhen MinWin 3865U-6L                  | 1        | 0.9%    |
| SeeedStudio ODYSSEY-X86J4125              | 1        | 0.9%    |
| Seeed Studio ODYSSEY-X86J4105             | 1        | 0.9%    |
| Purism Librem Mini v2                     | 1        | 0.9%    |
| Protectli FW6E                            | 1        | 0.9%    |
| NEXCOM ASG                                | 1        | 0.9%    |
| MSI MS-6788                               | 1        | 0.9%    |
| MSI Compaq dx2420 Microtower              | 1        | 0.9%    |
| Lenovo ThinkPad T400 2768W3A              | 1        | 0.9%    |
| Lenovo ThinkCentre M93p 10AB003CGE        | 1        | 0.9%    |
| Lenovo ThinkCentre M92P 3237CK4           | 1        | 0.9%    |
| Lenovo ThinkCentre M73 10B4S03V05         | 1        | 0.9%    |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE   | 1        | 0.9%    |
| Lenovo IdeaCentre 3 07ADA05 90MV007UGE    | 1        | 0.9%    |
| Intel UTC-520C                            | 1        | 0.9%    |
| Intel DENLOW_WS                           | 1        | 0.9%    |
| HP ProDesk 600 G2 SFF                     | 1        | 0.9%    |
| HP EliteDesk 800 G2 SFF                   | 1        | 0.9%    |
| HP Compaq Elite 8300 SFF                  | 1        | 0.9%    |
| HP Compaq 8200 Elite SFF PC               | 1        | 0.9%    |
| Hardkernel ODROID-H2                      | 1        | 0.9%    |
| Gigabyte J3455N-D3H                       | 1        | 0.9%    |
| Gigabyte H87-HD3                          | 1        | 0.9%    |
| Gigabyte H81M-S2PV                        | 1        | 0.9%    |
| Gigabyte B365M DS3H                       | 1        | 0.9%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 20       | 18.02%  |
| PC Engines apu4               | 7        | 6.31%   |
| PC Engines APU2               | 7        | 6.31%   |
| Deciso Netboard               | 6        | 5.41%   |
| Dell OptiPlex                 | 5        | 4.5%    |
| MW GMLK-2                     | 4        | 3.6%    |
| Protectli FW4B                | 3        | 2.7%    |
| Lenovo ThinkCentre            | 3        | 2.7%    |
| Fujitsu ESPRIMO               | 3        | 2.7%    |
| Techvision TVI7309X           | 2        | 1.8%    |
| Shuttle DS10U                 | 2        | 1.8%    |
| Lenovo IdeaCentre             | 2        | 1.8%    |
| Intel Q3XXG4-P                | 2        | 1.8%    |
| HP Compaq                     | 2        | 1.8%    |
| Dell PowerEdge                | 2        | 1.8%    |
| ASUS 1HE                      | 2        | 1.8%    |
| AAEON UP-APL01                | 2        | 1.8%    |
| Winston Marriot PICO          | 1        | 0.9%    |
| Silicom Minnowboard           | 1        | 0.9%    |
| Shuttle DS61                  | 1        | 0.9%    |
| Shuttle DH170                 | 1        | 0.9%    |
| ShenZhen MinWin 3865U-6L      | 1        | 0.9%    |
| SeeedStudio ODYSSEY-X86J4125  | 1        | 0.9%    |
| Seeed Studio ODYSSEY-X86J4105 | 1        | 0.9%    |
| Purism Librem                 | 1        | 0.9%    |
| Protectli FW6E                | 1        | 0.9%    |
| NEXCOM ASG                    | 1        | 0.9%    |
| MSI MS-6788                   | 1        | 0.9%    |
| MSI Compaq                    | 1        | 0.9%    |
| Lenovo ThinkPad               | 1        | 0.9%    |
| Intel UTC-520C                | 1        | 0.9%    |
| Intel DENLOW                  | 1        | 0.9%    |
| HP ProDesk                    | 1        | 0.9%    |
| HP EliteDesk                  | 1        | 0.9%    |
| Hardkernel ODROID-H2          | 1        | 0.9%    |
| Gigabyte J3455N-D3H           | 1        | 0.9%    |
| Gigabyte H87-HD3              | 1        | 0.9%    |
| Gigabyte H81M-S2PV            | 1        | 0.9%    |
| Gigabyte B365M                | 1        | 0.9%    |
| Gigabyte B150-HD3P-CF         | 1        | 0.9%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 14       | 12.61%  |
| 2018    | 14       | 12.61%  |
| 2016    | 14       | 12.61%  |
| 2020    | 13       | 11.71%  |
| 2017    | 12       | 10.81%  |
| 2019    | 10       | 9.01%   |
| 2022    | 8        | 7.21%   |
| 2015    | 7        | 6.31%   |
| 2014    | 4        | 3.6%    |
| 2013    | 4        | 3.6%    |
| 2012    | 3        | 2.7%    |
| 2011    | 2        | 1.8%    |
| 2009    | 2        | 1.8%    |
| Unknown | 2        | 1.8%    |
| 2023    | 1        | 0.9%    |
| 2007    | 1        | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 111      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 88       | 79.28%  |
| Yes  | 23       | 20.72%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 47       | 41.96%  |
| 4.01-8.0        | 27       | 24.11%  |
| 16.01-24.0      | 21       | 18.75%  |
| 32.01-64.0      | 6        | 5.36%   |
| 2.01-3.0        | 6        | 5.36%   |
| More than 256.0 | 1        | 0.89%   |
| 3.01-4.0        | 1        | 0.89%   |
| 24.01-32.0      | 1        | 0.89%   |
| 64.01-256.0     | 1        | 0.89%   |
| 1.01-2.0        | 1        | 0.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 63       | 55.26%  |
| 0.51-1.0   | 36       | 31.58%  |
| 1.01-2.0   | 9        | 7.89%   |
| 2.01-3.0   | 2        | 1.75%   |
| 4.01-8.0   | 1        | 0.88%   |
| 32.01-64.0 | 1        | 0.88%   |
| 3.01-4.0   | 1        | 0.88%   |
| 0          | 1        | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 81.74%  |
| 2      | 11       | 9.57%   |
| 0      | 8        | 6.96%   |
| 4      | 1        | 0.87%   |
| 3      | 1        | 0.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 91.07%  |
| Yes       | 10       | 8.93%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 111      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 90       | 80.36%  |
| Yes       | 22       | 19.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 86.49%  |
| Yes       | 15       | 13.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 111      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Vienna                   | 53       | 43.44%  |
| Graz                     | 13       | 10.66%  |
| Linz                     | 4        | 3.28%   |
| Innsbruck                | 3        | 2.46%   |
| Wels                     | 2        | 1.64%   |
| Sankt Veit an der Glan   | 2        | 1.64%   |
| Salzburg                 | 2        | 1.64%   |
| Klagenfurt               | 2        | 1.64%   |
| Feldkirch                | 2        | 1.64%   |
| Voggenberg               | 1        | 0.82%   |
| Tulln                    | 1        | 0.82%   |
| Tragwein                 | 1        | 0.82%   |
| Stockerau                | 1        | 0.82%   |
| Steyr                    | 1        | 0.82%   |
| Steinhaus                | 1        | 0.82%   |
| Spittal an der Drau      | 1        | 0.82%   |
| Sieghartskirchen         | 1        | 0.82%   |
| Siegendorf im Burgenland | 1        | 0.82%   |
| Schwechat                | 1        | 0.82%   |
| Schluesslberg            | 1        | 0.82%   |
| Sankt PÃ¶lten          | 1        | 0.82%   |
| Sankt Pantaleon          | 1        | 0.82%   |
| Rankweil                 | 1        | 0.82%   |
| Purkersdorf              | 1        | 0.82%   |
| Poelfing                 | 1        | 0.82%   |
| Pichl bei Wels           | 1        | 0.82%   |
| Ohlsdorf                 | 1        | 0.82%   |
| Oberpullendorf           | 1        | 0.82%   |
| Neulengbach              | 1        | 0.82%   |
| Mistelbach               | 1        | 0.82%   |
| Maria-Anzbach            | 1        | 0.82%   |
| Margarethen am Moos      | 1        | 0.82%   |
| Leogang                  | 1        | 0.82%   |
| Leoben                   | 1        | 0.82%   |
| Hoerndl                  | 1        | 0.82%   |
| Himberg                  | 1        | 0.82%   |
| Gmunden                  | 1        | 0.82%   |
| Gallneukirchen           | 1        | 0.82%   |
| Fieberbrunn              | 1        | 0.82%   |
| Ferndorf                 | 1        | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 21       | 25     | 17.95%  |
| Samsung Electronics | 16       | 30     | 13.68%  |
| Crucial             | 11       | 12     | 9.4%    |
| Kingston            | 10       | 11     | 8.55%   |
| WDC                 | 8        | 9      | 6.84%   |
| SanDisk             | 4        | 10     | 3.42%   |
| Phison              | 4        | 5      | 3.42%   |
| Hoodisk             | 4        | 5      | 3.42%   |
| China               | 4        | 6      | 3.42%   |
| Seagate             | 3        | 9      | 2.56%   |
| Intel               | 3        | 4      | 2.56%   |
| Toshiba             | 2        | 2      | 1.71%   |
| Patriot             | 2        | 3      | 1.71%   |
| FORESEE             | 2        | 3      | 1.71%   |
| Dogfish             | 2        | 2      | 1.71%   |
| Dell                | 2        | 2      | 1.71%   |
| Corsair             | 2        | 3      | 1.71%   |
| BORY                | 2        | 4      | 1.71%   |
| SPCC                | 1        | 2      | 0.85%   |
| SK hynix            | 1        | 3      | 0.85%   |
| OCZ                 | 1        | 1      | 0.85%   |
| Micron Technology   | 1        | 1      | 0.85%   |
| LITEONIT            | 1        | 1      | 0.85%   |
| KingSpec            | 1        | 1      | 0.85%   |
| KeepData            | 1        | 1      | 0.85%   |
| Hitachi             | 1        | 1      | 0.85%   |
| HGST                | 1        | 5      | 0.85%   |
| GOODRAM             | 1        | 1      | 0.85%   |
| Fanxiang            | 1        | 2      | 0.85%   |
| BR                  | 1        | 1      | 0.85%   |
| BIWIN               | 1        | 1      | 0.85%   |
| Apple               | 1        | 1      | 0.85%   |
| A-DATA Technology   | 1        | 3      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Transcend TS128GMSA370 128GB             | 6        | 5%      |
| Samsung SSD 840 EVO 250GB                | 5        | 4.17%   |
| Transcend TS128GMSA230S 128GB            | 4        | 3.33%   |
| Crucial CT240BX500SSD1 240GB             | 3        | 2.5%    |
| Transcend TS64GMSA230S 64GB              | 2        | 1.67%   |
| Transcend TS256GMSA230S 256GB            | 2        | 1.67%   |
| Transcend TS240GSSD220S 240GB            | 2        | 1.67%   |
| Transcend TS16GMSA370 16GB               | 2        | 1.67%   |
| SanDisk SSD PLUS 120GB                   | 2        | 1.67%   |
| Phison SATA SSD 16GB                     | 2        | 1.67%   |
| Kingston SUV500MS120G 120GB              | 2        | 1.67%   |
| Hoodisk SSD 64GB                         | 2        | 1.67%   |
| FORESEE 128GB SSD                        | 2        | 1.67%   |
| Crucial CT250P2SSD8 250GB                | 2        | 1.67%   |
| Crucial CT250MX500SSD1 250GB             | 2        | 1.67%   |
| China SATA SSD 64GB                      | 2        | 1.67%   |
| BORY M500 128G                           | 2        | 1.67%   |
| WDC WD800JD-60LSA5 80GB                  | 1        | 0.83%   |
| WDC WD1600BEVT-75ZCT2 160GB              | 1        | 0.83%   |
| WDC WD1600BEVS-00UST0 160GB              | 1        | 0.83%   |
| WDC WD120EFBX-68B0EN0 12TB               | 1        | 0.83%   |
| WDC WD10JPVT-75A1YT0 1TB                 | 1        | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 1        | 0.83%   |
| WDC WD Elements 25A1 4TB                 | 1        | 0.83%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB     | 1        | 0.83%   |
| Transcend TS64GMSA370 64GB               | 1        | 0.83%   |
| Transcend TS256GMSA370 256GB             | 1        | 0.83%   |
| Transcend TS16GMSA370I 16GB              | 1        | 0.83%   |
| Transcend TS128GMTS830S 128GB            | 1        | 0.83%   |
| Toshiba MQ04ABF100 1TB                   | 1        | 0.83%   |
| Toshiba MK3276GSX -63 320GB              | 1        | 0.83%   |
| SPCC Solid State Disk 512GB              | 1        | 0.83%   |
| SK hynix SC308 SATA 128GB                | 1        | 0.83%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 0.83%   |
| Seagate ST3160318AS 160GB                | 1        | 0.83%   |
| Seagate BarraCuda SSD ZA250CM10002 250GB | 1        | 0.83%   |
| SanDisk X400 M.2 2280 128GB              | 1        | 0.83%   |
| SanDisk SD8SBAT-256G-1006 256GB          | 1        | 0.83%   |
| Samsung SSD 980 250GB                    | 1        | 0.83%   |
| Samsung SSD 970 PRO 1TB                  | 1        | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 8      | 43.75%  |
| Toshiba | 2        | 2      | 12.5%   |
| Seagate | 2        | 2      | 12.5%   |
| Dell    | 2        | 2      | 12.5%   |
| Hitachi | 1        | 1      | 6.25%   |
| HGST    | 1        | 5      | 6.25%   |
| Apple   | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 21       | 25     | 24.71%  |
| Samsung Electronics | 13       | 20     | 15.29%  |
| Kingston            | 9        | 10     | 10.59%  |
| Crucial             | 8        | 9      | 9.41%   |
| SanDisk             | 4        | 10     | 4.71%   |
| Hoodisk             | 4        | 5      | 4.71%   |
| China               | 4        | 6      | 4.71%   |
| Phison              | 3        | 4      | 3.53%   |
| Intel               | 2        | 3      | 2.35%   |
| FORESEE             | 2        | 3      | 2.35%   |
| Dogfish             | 2        | 2      | 2.35%   |
| BORY                | 2        | 4      | 2.35%   |
| SPCC                | 1        | 2      | 1.18%   |
| SK hynix            | 1        | 3      | 1.18%   |
| Seagate             | 1        | 7      | 1.18%   |
| Patriot             | 1        | 1      | 1.18%   |
| OCZ                 | 1        | 1      | 1.18%   |
| LITEONIT            | 1        | 1      | 1.18%   |
| KingSpec            | 1        | 1      | 1.18%   |
| KeepData            | 1        | 1      | 1.18%   |
| GOODRAM             | 1        | 1      | 1.18%   |
| BR                  | 1        | 1      | 1.18%   |
| BIWIN               | 1        | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 82       | 121    | 71.93%  |
| NVMe | 17       | 28     | 14.91%  |
| HDD  | 15       | 21     | 13.16%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 91       | 142    | 84.26%  |
| NVMe | 17       | 28     | 15.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 128    | 87.37%  |
| 0.51-1.0   | 8        | 9      | 8.42%   |
| 3.01-4.0   | 1        | 1      | 1.05%   |
| 10.01-20.0 | 1        | 2      | 1.05%   |
| 1.01-2.0   | 1        | 1      | 1.05%   |
| 4.01-10.0  | 1        | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 65       | 57.52%  |
| 251-500    | 16       | 14.16%  |
| 21-50      | 11       | 9.73%   |
| 51-100     | 9        | 7.96%   |
| 1-20       | 8        | 7.08%   |
| 501-1000   | 3        | 2.65%   |
| 1001-2000  | 1        | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 108      | 96.43%  |
| 21-50    | 2        | 1.79%   |
| 101-250  | 1        | 0.89%   |
| 501-1000 | 1        | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Desktops | Drives | Percent |
|-------------------------------|----------|--------|---------|
| WDC WD1600BEVS-00UST0 160GB   | 1        | 1      | 20%     |
| SK hynix SC308 SATA 128GB     | 1        | 3      | 20%     |
| Intel SSDPEKKW128G7 128GB     | 1        | 1      | 20%     |
| Hitachi HDS721050CLA660 500GB | 1        | 1      | 20%     |
| HGST HTS725050A7E630 500GB    | 1        | 5      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 20%     |
| SK hynix | 1        | 3      | 20%     |
| Intel    | 1        | 1      | 20%     |
| Hitachi  | 1        | 1      | 20%     |
| HGST     | 1        | 5      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Hitachi | 1        | 1      | 33.33%  |
| HGST    | 1        | 5      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 7      | 60%     |
| NVMe | 1        | 1      | 20%     |
| SSD  | 1        | 3      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Crucial CT250P2SSD8 250GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Crucial | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 98       | 154    | 92.45%  |
| Malfunc  | 4        | 11     | 3.77%   |
| Detected | 3        | 4      | 2.83%   |
| Failed   | 1        | 1      | 0.94%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 81       | 61.83%  |
| AMD                         | 28       | 21.37%  |
| Samsung Electronics         | 4        | 3.05%   |
| Phison Electronics          | 4        | 3.05%   |
| Micron/Crucial Technology   | 3        | 2.29%   |
| Broadcom / LSI              | 2        | 1.53%   |
| Silicon Motion              | 1        | 0.76%   |
| SanDisk                     | 1        | 0.76%   |
| Realtek Semiconductor       | 1        | 0.76%   |
| Micron Technology           | 1        | 0.76%   |
| Marvell Technology Group    | 1        | 0.76%   |
| Kingston Technology Company | 1        | 0.76%   |
| Hewlett-Packard             | 1        | 0.76%   |
| Dell                        | 1        | 0.76%   |
| ASMedia Technology          | 1        | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21       | 15.33%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9        | 6.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8        | 5.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8        | 5.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8        | 5.84%   |
| AMD FCH SATA Controller [IDE mode]                                               | 8        | 5.84%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5        | 3.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 2.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4        | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3        | 2.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 2.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3        | 2.19%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3        | 2.19%   |
| Phison PS5013 E13 NVMe Controller                                                | 2        | 1.46%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2        | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 1.46%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 2        | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 1.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1        | 0.73%   |
| SanDisk NVMe Controller                                                          | 1        | 0.73%   |
| Samsung NVMe SSD Controller 980                                                  | 1        | 0.73%   |
| Realtek NVMe Controller                                                          | 1        | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 0.73%   |
| Phison E12 NVMe Controller                                                       | 1        | 0.73%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1        | 0.73%   |
| Micron NVMe Storage Controller                                                   | 1        | 0.73%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                            | 1        | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1        | 0.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1        | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1        | 0.73%   |
| Intel SSD 600P Series                                                            | 1        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1        | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1        | 0.73%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 1        | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 0.73%   |
| Intel 82801EB (ICH5) SATA Controller                                             | 1        | 0.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 1        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 97       | 72.93%  |
| NVMe | 17       | 12.78%  |
| IDE  | 13       | 9.77%   |
| RAID | 4        | 3.01%   |
| SAS  | 1        | 0.75%   |
| SCSI | 1        | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 83       | 74.77%  |
| AMD    | 28       | 25.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                       | 14       | 12.61%  |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 7        | 6.31%   |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 6        | 5.41%   |
| AMD GX-420MC SOC                                       | 6        | 5.41%   |
| Intel Celeron N5105 @ 2.00GHz                          | 5        | 4.5%    |
| Intel Xeon CPU E5620 @ 2.40GHz                         | 2        | 1.8%    |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 2        | 1.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz                      | 2        | 1.8%    |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 2        | 1.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz                     | 2        | 1.8%    |
| Intel Core i3-4130 CPU @ 3.40GHz                       | 2        | 1.8%    |
| Intel Celeron J4105 CPU @ 1.50GHz                      | 2        | 1.8%    |
| Intel Atom CPU E3845 @ 1.91GHz                         | 2        | 1.8%    |
| Intel Atom CPU C3558 @ 2.20GHz                         | 2        | 1.8%    |
| Intel Xeon E-2136 CPU @ 3.30GHz                        | 1        | 0.9%    |
| Intel Xeon CPU E5320 @ 1.86GHz                         | 1        | 0.9%    |
| Intel Pentium Dual-Core                                | 1        | 0.9%    |
| Intel Pentium CPU N4200 @ 1.10GHz                      | 1        | 0.9%    |
| Intel Pentium CPU G4400 @ 3.30GHz                      | 1        | 0.9%    |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class) | 1        | 0.9%    |
| Intel N200                                             | 1        | 0.9%    |
| Intel Genuine CPU 0000 @ 2.40GHz                       | 1        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz                      | 1        | 0.9%    |
| Intel Core i7-5550U CPU @ 2.00GHz                      | 1        | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz                       | 1        | 0.9%    |
| Intel Core i7-4770 CPU @ 3.40GHz                       | 1        | 0.9%    |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 1        | 0.9%    |
| Intel Core i7-3517UE CPU @ 1.70GHz                     | 1        | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz                     | 1        | 0.9%    |
| Intel Core i5-9500 CPU @ 3.00GHz                       | 1        | 0.9%    |
| Intel Core i5-8365U CPU @ 1.60GHz                      | 1        | 0.9%    |
| Intel Core i5-7500 CPU @ 3.40GHz                       | 1        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz                      | 1        | 0.9%    |
| Intel Core i5-6600 CPU @ 3.30GHz                       | 1        | 0.9%    |
| Intel Core i5-6500T CPU @ 2.50GHz                      | 1        | 0.9%    |
| Intel Core i5-6400 CPU @ 2.70GHz                       | 1        | 0.9%    |
| Intel Core i5-4590T CPU @ 2.00GHz                      | 1        | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 1        | 0.9%    |
| Intel Core i5-3570 CPU @ 3.40GHz                       | 1        | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 26       | 23.42%  |
| AMD GX                  | 21       | 18.92%  |
| Intel Core i5           | 20       | 18.02%  |
| Intel Core i7           | 10       | 9.01%   |
| Intel Core i3           | 8        | 7.21%   |
| Intel Xeon              | 4        | 3.6%    |
| Intel Pentium           | 4        | 3.6%    |
| Intel Atom              | 4        | 3.6%    |
| Other                   | 3        | 2.7%    |
| Intel Core 2 Duo        | 2        | 1.8%    |
| AMD Ryzen 7             | 2        | 1.8%    |
| Intel Pentium Dual-Core | 1        | 0.9%    |
| Intel Pentium 4         | 1        | 0.9%    |
| Intel Genuine           | 1        | 0.9%    |
| AMD Ryzen Threadripper  | 1        | 0.9%    |
| AMD Ryzen 5 PRO         | 1        | 0.9%    |
| AMD FX                  | 1        | 0.9%    |
| AMD Athlon              | 1        | 0.9%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 76       | 68.47%  |
| 2       | 23       | 20.72%  |
| 8       | 4        | 3.6%    |
| 6       | 3        | 2.7%    |
| Unknown | 2        | 1.8%    |
| 64      | 1        | 0.9%    |
| 16      | 1        | 0.9%    |
| 1       | 1        | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 106      | 95.5%   |
| Unknown | 3        | 2.7%    |
| 2       | 2        | 1.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 79       | 71.17%  |
| 2       | 29       | 26.13%  |
| Unknown | 3        | 2.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 20       | 18.02%  |
| KabyLake      | 16       | 14.41%  |
| Silvermont    | 11       | 9.91%   |
| Haswell       | 9        | 8.11%   |
| Skylake       | 8        | 7.21%   |
| Goldmont plus | 8        | 7.21%   |
| Unknown       | 6        | 5.41%   |
| IvyBridge     | 5        | 4.5%    |
| Goldmont      | 5        | 4.5%    |
| Zen           | 3        | 2.7%    |
| SandyBridge   | 3        | 2.7%    |
| Penryn        | 3        | 2.7%    |
| Westmere      | 2        | 1.8%    |
| Excavator     | 2        | 1.8%    |
| CometLake     | 2        | 1.8%    |
| Zen+          | 1        | 0.9%    |
| Zen 2         | 1        | 0.9%    |
| TigerLake     | 1        | 0.9%    |
| NetBurst      | 1        | 0.9%    |
| Jaguar        | 1        | 0.9%    |
| IceLake       | 1        | 0.9%    |
| Core          | 1        | 0.9%    |
| Broadwell     | 1        | 0.9%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 74       | 84.09%  |
| AMD                        | 8        | 9.09%   |
| Nvidia                     | 3        | 3.41%   |
| ASPEED Technology          | 2        | 2.27%   |
| Matrox Electronics Systems | 1        | 1.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 10.23%  |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8        | 9.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 6.82%   |
| Intel HD Graphics 530                                                                    | 6        | 6.82%   |
| Intel JasperLake [UHD Graphics]                                                          | 5        | 5.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 3.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3        | 3.41%   |
| Intel HD Graphics 620                                                                    | 3        | 3.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3        | 3.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 3.41%   |
| Intel HD Graphics 630                                                                    | 2        | 2.27%   |
| Intel HD Graphics 500                                                                    | 2        | 2.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 2.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 2.27%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2        | 2.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 2.27%   |
| AMD ES1000                                                                               | 2        | 2.27%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.14%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.14%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 1.14%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1        | 1.14%   |
| Intel UHD Graphics 620                                                                   | 1        | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 1.14%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1        | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 1.14%   |
| Intel HD Graphics 6000                                                                   | 1        | 1.14%   |
| Intel HD Graphics 510                                                                    | 1        | 1.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.14%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1        | 1.14%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1        | 1.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1        | 1.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1        | 1.14%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1        | 1.14%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1        | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.14%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 72       | 64.86%  |
| Other      | 23       | 20.72%  |
| 1 x AMD    | 8        | 7.21%   |
| 1 x Nvidia | 3        | 2.7%    |
| 2 x Intel  | 2        | 1.8%    |
| 1 x ASPEED | 2        | 1.8%    |
| 1 x Matrox | 1        | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 87       | 78.38%  |
| Unknown     | 23       | 20.72%  |
| Proprietary | 1        | 0.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 110      | 99.1%   |
| 1.01-2.0   | 1        | 0.9%    |

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
| 0     | 103      | 92.79%  |
| 1     | 7        | 6.31%   |
| 2     | 1        | 0.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 91       | 66.42%  |
| Realtek Semiconductor | 32       | 23.36%  |
| Broadcom              | 3        | 2.19%   |
| Qualcomm Atheros      | 2        | 1.46%   |
| LG Electronics        | 2        | 1.46%   |
| TP-Link               | 1        | 0.73%   |
| Seeed Technology      | 1        | 0.73%   |
| MediaTek              | 1        | 0.73%   |
| Edimax Technology     | 1        | 0.73%   |
| Dresden Elektronik    | 1        | 0.73%   |
| AVM                   | 1        | 0.73%   |
| Arduino SA            | 1        | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 16.27%  |
| Intel I211 Gigabit Network Connection                             | 27       | 16.27%  |
| Intel I210 Gigabit Network Connection                             | 24       | 14.46%  |
| Intel Ethernet Controller I225-V                                  | 8        | 4.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 3.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 3.01%   |
| Intel I350 Gigabit Network Connection                             | 4        | 2.41%   |
| Intel 82576 Gigabit Network Connection                            | 4        | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 1.81%   |
| Intel Ethernet Controller I226-V                                  | 3        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.2%    |
| LG Optimus Android Phone [USB tethering mode]                     | 2        | 1.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2        | 1.2%    |
| Intel Ethernet Connection X553 1GbE                               | 2        | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 2        | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                             | 2        | 1.2%    |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.2%    |
| Intel Centrino Advanced-N 6235                                    | 2        | 1.2%    |
| Intel 82583V Gigabit Network Connection                           | 2        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.2%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2        | 1.2%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1        | 0.6%    |
| Seeed Seeeduino_Cortex_M0+                                        | 1        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.6%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1        | 0.6%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 1        | 0.6%    |
| Intel Wireless 7265                                               | 1        | 0.6%    |
| Intel Wireless 7260                                               | 1        | 0.6%    |
| Intel Wireless 3165                                               | 1        | 0.6%    |
| Intel Wireless 3160                                               | 1        | 0.6%    |
| Intel Ultimate N WiFi Link 5300                                   | 1        | 0.6%    |
| Intel I210 Gigabit Fiber Network Connection                       | 1        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 1        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 12       | 54.55%  |
| Realtek Semiconductor | 5        | 22.73%  |
| Qualcomm Atheros      | 2        | 9.09%   |
| TP-Link               | 1        | 4.55%   |
| MediaTek              | 1        | 4.55%   |
| Edimax Technology     | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 13.64%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 9.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2        | 9.09%   |
| Intel Centrino Advanced-N 6235                                 | 2        | 9.09%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1        | 4.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 4.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 4.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 4.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 4.55%   |
| Intel Wireless 7265                                            | 1        | 4.55%   |
| Intel Wireless 7260                                            | 1        | 4.55%   |
| Intel Wireless 3165                                            | 1        | 4.55%   |
| Intel Wireless 3160                                            | 1        | 4.55%   |
| Intel Ultimate N WiFi Link 5300                                | 1        | 4.55%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 85       | 72.65%  |
| Realtek Semiconductor | 29       | 24.79%  |
| Broadcom              | 3        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 27       | 19.85%  |
| Intel I211 Gigabit Network Connection                                         | 27       | 19.85%  |
| Intel I210 Gigabit Network Connection                                         | 24       | 17.65%  |
| Intel Ethernet Controller I225-V                                              | 8        | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 6        | 4.41%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5        | 3.68%   |
| Intel I350 Gigabit Network Connection                                         | 4        | 2.94%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.94%   |
| Intel Ethernet Controller I226-V                                              | 3        | 2.21%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 1.47%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                                          | 2        | 1.47%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.47%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 1.47%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 2        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1        | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.74%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.74%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.74%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 0.74%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.74%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.74%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.74%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 111      | 78.72%  |
| WiFi     | 22       | 15.6%   |
| Modem    | 5        | 3.55%   |
| Unknown  | 3        | 2.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 109      | 99.09%  |
| WiFi     | 1        | 0.91%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 35       | 31.53%  |
| 3     | 25       | 22.52%  |
| 2     | 20       | 18.02%  |
| 6     | 10       | 9.01%   |
| 1     | 10       | 9.01%   |
| 8     | 4        | 3.6%    |
| 7     | 3        | 2.7%    |
| 5     | 3        | 2.7%    |
| 9     | 1        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 107      | 94.69%  |
| Yes  | 6        | 5.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 66.67%  |
| IMC Networks          | 2        | 13.33%  |
| Realtek Semiconductor | 1        | 6.67%   |
| MediaTek              | 1        | 6.67%   |
| Lite-On Technology    | 1        | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface             | 3        | 20%     |
| Intel AX200 Bluetooth                          | 3        | 20%     |
| Intel Centrino Bluetooth Wireless Transceiver  | 2        | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 13.33%  |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 13.33%  |
| Realtek RTL8821A Bluetooth                     | 1        | 6.67%   |
| MediaTek RZ608 Bluetooth Adapter               | 1        | 6.67%   |
| Lite-On Atheros AR3012 Bluetooth               | 1        | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 63       | 84%     |
| AMD                                          | 8        | 10.67%  |
| Nvidia                                       | 2        | 2.67%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 1.33%   |
| Creative Labs                                | 1        | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9        | 10.34%  |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8        | 9.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 6.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5        | 5.75%   |
| Intel Jasper Lake HD Audio                                                                        | 5        | 5.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5        | 5.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4        | 4.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 3.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3        | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3        | 3.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 3.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 3.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2        | 2.3%    |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 2.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2        | 2.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2        | 2.3%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1        | 1.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 1.15%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1        | 1.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1        | 1.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1        | 1.15%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 1.15%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 1        | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 1        | 1.15%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 1.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 1.15%   |
| AMD High Definition Audio Controller                                                              | 1        | 1.15%   |
| AMD FCH Azalia Controller                                                                         | 1        | 1.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 1.15%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 15       | 15.31%  |
| Kingston            | 13       | 13.27%  |
| Samsung Electronics | 11       | 11.22%  |
| Unknown             | 10       | 10.2%   |
| SK hynix            | 9        | 9.18%   |
| Micron Technology   | 9        | 9.18%   |
| Unknown             | 5        | 5.1%    |
| Unknown (ABCD)      | 4        | 4.08%   |
| Corsair             | 4        | 4.08%   |
| Transcend           | 3        | 3.06%   |
| G.Skill             | 3        | 3.06%   |
| Ramaxel Technology  | 2        | 2.04%   |
| Tigo                | 1        | 1.02%   |
| Nanya Technology    | 1        | 1.02%   |
| Mushkin             | 1        | 1.02%   |
| Lexar Co Limited    | 1        | 1.02%   |
| Kingmax             | 1        | 1.02%   |
| Kimtigo             | 1        | 1.02%   |
| GeIL                | 1        | 1.02%   |
| DSL                 | 1        | 1.02%   |
| ATP                 | 1        | 1.02%   |
| A-DATA Technology   | 1        | 1.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 5        | 5%      |
| Unknown                                                        | 5        | 5%      |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 4        | 4%      |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s           | 2        | 2%      |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s            | 2        | 2%      |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 2        | 2%      |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s          | 2        | 2%      |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 1%      |
| Unknown RAM Module 8GB 1600MT/s                                | 1        | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 1        | 1%      |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                      | 1        | 1%      |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s              | 1        | 1%      |
| Transcend RAM TS512MLK72V6H 4GB DIMM DDR3 1600MT/s             | 1        | 1%      |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s            | 1        | 1%      |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s          | 1        | 1%      |
| Tigo RAM 1600MHz-4G 4GB SODIMM DDR3 1600MT/s                   | 1        | 1%      |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 1%      |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1%      |
| SK hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1        | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 1%      |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 1        | 1%      |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 1%      |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 1%      |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1%      |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 1%      |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1        | 1%      |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 1        | 1%      |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 2400MT/s            | 1        | 1%      |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s            | 1        | 1%      |
| Samsung RAM K4F6E304HB-MGCJ 2GB Chip LPDDR4                    | 1        | 1%      |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1        | 1%      |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s          | 1        | 1%      |
| Nanya RAM NT2GC64B88G0NF-CG 2GB DIMM DDR3 1333MT/s             | 1        | 1%      |
| Mushkin RAM 992037 (997037) 4GB DIMM DDR3 1600MT/s             | 1        | 1%      |
| Micron RAM Module 8GB Row Of Chips LPDDR4 3200MT/s             | 1        | 1%      |
| Micron RAM Module 2GB DIMM DDR3 1333MT/s                       | 1        | 1%      |
| Micron RAM M471A1K43BB1-CRC 16GB SODIMM DDR4 2667MT/s          | 1        | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 45.05%  |
| DDR3    | 39       | 42.86%  |
| LPDDR4  | 7        | 7.69%   |
| DDR2    | 2        | 2.2%    |
| DDR5    | 1        | 1.1%    |
| Unknown | 1        | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| SODIMM       | 44       | 48.35%  |
| DIMM         | 42       | 46.15%  |
| Row Of Chips | 2        | 2.2%    |
| Unknown      | 2        | 2.2%    |
| Chip         | 1        | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 43.48%  |
| 4096  | 23       | 25%     |
| 16384 | 15       | 16.3%   |
| 2048  | 10       | 10.87%  |
| 32768 | 2        | 2.17%   |
| 1024  | 2        | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 25       | 26.6%   |
| 2400    | 18       | 19.15%  |
| 1333    | 14       | 14.89%  |
| 2667    | 12       | 12.77%  |
| 3200    | 11       | 11.7%   |
| 2133    | 5        | 5.32%   |
| 1067    | 2        | 2.13%   |
| 65535   | 1        | 1.06%   |
| 4800    | 1        | 1.06%   |
| 2666    | 1        | 1.06%   |
| 1033    | 1        | 1.06%   |
| 800     | 1        | 1.06%   |
| 667     | 1        | 1.06%   |
| Unknown | 1        | 1.06%   |

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
| 1     | 51       | 44.74%  |
| 0     | 41       | 35.96%  |
| 2     | 12       | 10.53%  |
| 3     | 8        | 7.02%   |
| 5     | 1        | 0.88%   |
| 4     | 1        | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 64       | 68.09%  |
| Net/wireless             | 11       | 11.7%   |
| Card reader              | 7        | 7.45%   |
| Bluetooth                | 7        | 7.45%   |
| Network                  | 3        | 3.19%   |
| Sound                    | 1        | 1.06%   |
| Graphics card            | 1        | 1.06%   |

